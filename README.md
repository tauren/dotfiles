# tauren's dotfiles

Inspired by [sobolevn's dotfiles](https://github.com/sobolevn/dotfiles)

## Improvement ideas

- http://stratus3d.com/blog/2015/02/28/sync-iterm2-profile-with-dotfiles-repository/
- https://blog.jez.io/noteworthy-dotfile-hacks/
- Remove Oh-my-zsh but keep goodies https://seesparkbox.com/foundry/cleaning_house_on_my_dotfiles
- Zazu Open source launcher instead of alfred http://zazuapp.org
- Integrate https://github.com/sobolevn/git-secret
- Use a different theme, but keep some features of https://github.com/sobolevn/sobole-zsh-theme
- Add Alfred config workflows
- Configure oDrive
- Configure MacOS settings https://github.com/mathiasbynens/dotfiles/blob/master/.macos
- Setup BitWarden
- BitWarden Alfred Workflow http://www.packal.org/workflow/bitwarden-cli
- Move elements from ~/dotfiles.notused to ~/dotfiles
- Add Workona for tab management https://workona.com/
- Or Toby for tab management https://www.gettoby.com/
- And/or The Great Suspender https://chrome.google.com/webstore/detail/the-great-suspender/klbibkeccnjlkjkiokjodocebajanakg?hl=en
- Might be some useful stuff here: https://github.com/alexramirez/mac-setup

## Contents

What's included?

- `brew` dependencies including: applications, fonts, etc. See `Brewfile`
- `macOS` configuration. See `macos`
- shell configuration. See `shell/` and `config/zshrc`
- `vscode` configuration. See `vscode/`
- `ssh` configuration. See `ssh/`
- `iterm2` configuration. See `etc/iterm2/`
- `alfred` configuration. See `etc/alfred/`
- `oh-my-zsh` configuration. See `oh-my-zsh/`

## Installation

We are using `dotbot` to handle installations. Steps:

1. Clone this repo
2. `cd` into `dotfiles/` folder
3. Run: `./install`

### iTerm2

In order for iTerm to pick up customized settings, do the following:

1. Go into Preferences -> General
1. Check the `Load preferences from a custom folder or URL`.
1. Select the `~/etc/iterm2` folder

### Alfred

1. Go into Alfred Preferences -> Advanced
1. Click the `Set sync folder...` button
1. Select the `~/etc/alfred` folder

## CLI

I am using `iTerm2` as my terminal emulator.
I am using `zsh` with `oh-my-zsh` as a main shell.
I also have a lot of tools to make my working experience better.

I mainly work with these stacks and tools:

- `node`
- `react`

## Infrastructure

<!--
TODO:
I try to containerize everything.
So `docker` is my main development and deployment tool.
You can install it from its [official site](https://docs.docker.com/docker-for-mac/) (`brew` [version](https://github.com/Homebrew/homebrew-core/blob/master/Formula/docker.rb) is also an option).

I prefer to use `edge` version of `docker`.
So, you will have to download it manually.

However, I also use several databases and other services locally:

- `postgresql` (with `postgis`)
- `mysql`
- `redis`
- `rabbitmq`
 -->

## VS Code

Here are some of the packages I use:

- `ayu` theme and `A File Icon` icons
- `editorconfig` integration
- `prettier` integration
- `wakatime` integration
- [`Git Lens`](https://github.com/eamodio/vscode-gitlens)
- [`Vetur`](https://github.com/vuejs/vetur) for `Vue` features

## External services

I'm trying out the [`wakatime`](https://wakatime.com/) service.
It is used to track the time of your work and is a free service.

There are two main plugins I am using:

1. For `vscode`: https://wakatime.com/sublime-text
2. For `zsh`: https://github.com/sobolevn/wakatime-zsh-plugin#wakatime-zsh-plugin

## Local configuration

Some of the used tools requires local configuration, such as `git` with username and email.

Here's the full list:

1. `~/.gitconfig_local` to store any user-specific data
2. `~/.shell_env_local` to store local shell config, like: usernames, passwords, tokens, access keys and so on

## License

[WTFPL](https://en.wikipedia.org/wiki/WTFPL): do the fuck you want. Enjoy!
