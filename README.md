# Personal Setup
⚠️ This Repository is for me :D


## Shell
### Install Brew for Linux
- [Linux Brew](https://docs.brew.sh/Homebrew-on-Linux)
``` Shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/Linuxbrew/install/master/install.sh)"
```
### Install ZSH
- Using brew
``` Shell
brew install zsh
```
### Install Oh-my-zsh
- [oh-my-zsh repository](https://github.com/robbyrussell/oh-my-zsh)
``` Shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
### Customized
#### Theme - Agnoster
- [Official Repository](https://github.com/agnoster/agnoster-zsh-theme)
- [PowerlineFont Repository](https://github.com/powerline/fonts)
- [Menlo for powerline](https://github.com/abertsch/Menlo-for-Powerline)
- [Customized](https://github.com/opnay/PersonalSetup/tree/master/oh-my-zsh)
    - Place to `~/.oh-my-zsh/custom/themes`
#### Plugin - Autojump
- Usign brew
``` Shell
brew install autojump
```
#### Plugin - Autosuggestions
- [Official Repository](https://github.com/zsh-users/zsh-autosuggestions)
``` Shell
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```
### Add SSH key
- [Github guide](https://help.github.com/en/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)


## Setup Tools and Libraries
### Visual Studio Code
- [Official (deb/rpm)](https://code.visualstudio.com)
### Android Studio
- [Official](https://developer.android.com/studio)
- [Snap](https://snapcraft.io/android-studio)
- [Flatpak](https://flathub.org/apps/details/com.google.AndroidStudio)
#### Add desktop icon
- [Copy `android-studio.desktop` file!](https://github.com/opnay/PersonalSetup/tree/master/Application/.desktop)
#### Setup ADB
1. Install Android Studio
2. Install SDK in Android Studio
    - You must know SDK Path (MY PATH: `/Workspace/Library/AndroidSDK`)
3. Add your `.bashrc` or `.zshrc`
``` Shell
export PATH=$PATH:/Workspace/Library/AndroidSDK/platform-tools
```
### Vala
- [Elementary Development](https://elementary.io/ko/docs/code/getting-started#developer-sdk)
- [Practice Repository](https://github.com/opnay/ValaPractice)

## Node
### Install NVM
- [Official Repository](https://github.com/creationix/nvm)
``` Shell
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.34.0/install.sh | bash
```
- Add `.bashrc` or `.zshrc`
``` Shell
export NVM_DIR="${XDG_CONFIG_HOME/:-$HOME/.}nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
```
- Install Node
``` Shell
# Check node versions
nvm ls-remote
# Install what you want version
nvm install 11.14.0
# Select for using node that install before line
nvm use 11.14.0
```
### Install Yarn
- Using NPM
``` Shell
npm install -g yarn
```
- [Manual Install](https://yarnpkg.com/en/docs/install#alternatives-stable)
``` Shell
curl -o- -L https://yarnpkg.com/install.sh | bash
```
