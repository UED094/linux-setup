# Installation of ZSH
## Locate the ZSH Utility
```bash
apt show zsh
```

## Install Zsh
```bash
sudo apt install zsh -y
```

## Install oh-my-zsh

```bash
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## Install Powerlevel10k
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

# Install SDK man
## Install prereqs
```
sudo apt install unzip
sudo apt install zip
```
## Install sdkman
```
curl -s "https://get.sdkman.io" | bash
source "$HOME/.sdkman/bin/sdkman-init.sh"
```
## Check if it is correctly installed
```
sdk version
```
Respond should be sdkman 5.18.1 or up.

## Install Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
Add Brew to path
```
eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"
```

Install build essentials
sudo apt-get install build-essential

# Install Command line tools
- brew install zsh-autosuggestions
- brew install bat
- brew install fzf
- brew install navi
- brew install zsh-syntax-highlighting
- brew install zsh-history-substring-search 

# Configure Git
- git config --global user.name "Ugur Emre Dogan"

- git config --global user.email "ue.dogan@gmail.com"

- ssh-keygen -t ed25519 -C "ue.dogan@gmail.com"


# Install Java
- sdk install java
- sdk install maven
