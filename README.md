# Settings
Follow these steps to mitigate the chore of manually installing all of the programs that you need on your development machine.

Installs `git`, `node`, `yarn`, `npm`, `homebrew`, `google chrome`, `firefox`, `charles`, `copyq`, `docker`, `github for desktop`, `insomnia`, `iterm2`, `postman`, `slack`, `spotify`, `whatsapp`, `zeplin`.

Sets `zsh` as the default shell for your machine.

Installs `Visual Studio Code` with some useful extensions, the `DankMono` font, and some opinionated settings.

## Prerequisites
* You will need an asos github account with access to all of the repos in `asosteam`. Contact Dom Green or Tony Gorman if you don't already have access to these repositories in github.

* You will be offered the option to download some of the most popular asos repos, if you wish to do this then you need to [create an access token](https://help.github.com/en/enterprise/2.17/user/articles/creating-a-personal-access-token-for-the-command-line) and use that as your password to install the repos.

* Don't leave your mac as you will be required to enter your password a few times and will be asked to enter/configure git credentials.

## Manual steps before installation
* Download [this gist](https://gist.github.com/asos-oliverwilson/692c8faeed167fe6e16443d6ef2ee40d). 

* Open the terminal and go to the directory where you saved [the gist](https://gist.github.com/asos-oliverwilson/692c8faeed167fe6e16443d6ef2ee40d) and run `sh setup.sh`.
  * You might need to extract the file if you've downloaded it as a zip.

## Manual steps after installation
Disclaimer: you should have some settings files downloaded into the `~/mac-setup-files` directory.

### iTerm2
* Go to `Preferences -> Profiles -> Colors -> Color Presets -> Import...` and select `~/mac-setup-files/iterm2/iterm2-color-preset.itermcolors`. Then select the `iterm2-color-preset` option from the presets.

* Go to `Preferences -> Profiles -> Text -> Font -> Change Font` and select a font that has _for Powerline_ in the name. Change your font size here too if you wish.

* Go to `Preferences -> Profiles -> Keys -> Load Preset...` and select _Natural Text Editing_ - you can now jump around the text using the alt+arrow keys.

### Reboot your mac
* `Press the apple button in the top left of the screen -> Reboot...`

![](gifs/reboot mac.gif)

## Some useful links
* [Download virtualbox](https://www.virtualbox.org/wiki/Downloads) - the cask requires manual intervention, which is distracting from the rest of the setup script.
* [Microsoft VM download for virtualbox](https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/) - this takes quite a while to download.
* [Forward network traffic from mac to VM](https://medium.com/@urubuz/accessing-localhost-in-mac-from-windows-vm-in-virtualbox-312a3de6fedb)
* [Useful iTerm2 keybindings](https://medium.com/@_simon__says/useful-iterm2-keybindings-d9e4e9b8a3ed)
