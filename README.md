# Configuration

This is a basic configuration starter "package" for setting up a new Mac environment, according to what I need. Having always needed to configure everything by hand along with referring (or trying to remember) older machine configurations, this helps me get going quickly.

> This idea came from @mdo with the repo [github.com/mdo/config](github.com/mdo/config "Link to mdo config repository")

## What's included

| File           | What's it for? |
|:--             | --             |
| `.gitconfig`    | Configuration file for git |
| `.gitignore`   | Ignores pesky hidden files and design program files |
| `.vimrc`       | Configure my VIM profile |
| `.zshrc`       | My ZSH configuration with shortcuts |

## Checklist

1. Downloads

- Arc browser
- Homebrew
- iTerm2
- ZSH + OhMyZSH
- VIM (if not preinstalled)
- Xcode
  - enter `xcode-select --install` in iTerm2 to install command line tools
  - open Xcode to agree to the Ts and Cs

2. Install and Configure iTerm2

- `brew install iterm2`
- Load `.gitconfig`
- Customize as desired
  - See my [configuration](iterm/config.md)

3. Install ZSH & OhMyZSH

- Install [ZSH](https://www.zsh.org/ "External link to ZSH install page")
- Install [OhMyZSH](https://ohmyz.sh/ "External link to OhMyZSH homepage") using the [Basic installation](https://github.com/ohmyzsh/ohmyzsh?tab=readme-ov-file#basic-installation "External link to Readme") instructions

> Any changes to the `.zshrc` file must be followed up by restarting iTerm2 or by entering `source .zshrc` from the root directory.

4. GitHub access

- [Create an access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens) for authenticating to GitHub

5. Dev setup

- I like to created a `/dev` directory as a top-level item where all development work (particularly repositories) reside.

6. Configure Node Version Manager (NVM)

- [Install script](https://github.com/nvm-sh/nvm?tab=readme-ov-file#installing-and-updating "Link to nvm-sh repository")

## Helpful tools

- Raycast
  - `brew install raycast`
- VLC
  - `brew install vlc`
- Ice (for cleaning up the menu bar)
  - [Ice by Jordan Baird](https://github.com/jordanbaird/Ice "External link to Ice repo on GitHub")

## Can I use it?

Yes, though if it does not work for you please reference the various linked references. Oh, and change anything with [INSERT EMAIL] or [INSERT NAME] to match your's :-D
