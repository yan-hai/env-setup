## Macbook Pro Environemnt Setup

### Homebrew
Use [Homebrew](https://brew.sh/) as the package manager
```BASH
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

brew --version
```
### List of Contents
* Environment
  * [Java](#java)
  * [Git](#git)
  * [Gradle](#gradle)
  * [Node.js](#nodejs)
  * [Python 3](#python-3)
  
* Tool
  * [iTerm2](#iterm2)
  * [IntelliJ IDEA](#intellij-idea)
  * [Google Chrome](#google-chrome)
  * [Folx](#folx)
  * [Kindle](#kindle)
  * [OneDrive](#onedrive)
  * [Sublime Text 3](#sublime-text-3)
  * [Postman](#postman)

* Entertainment
  * [IINA](#iina)
  * [Spotify](#spotify)


#### Development Environment
##### Java
```BASH
brew install openjdk@8

java --version
```

##### Git 
```BASH
brew install git

git --version
```
> Setup ssh key: `ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`

##### Gradle
> Should use gradle wrapper instead for each project
```BASH
brew install gradle

gradle -version
```

##### Node.js
```BASH
brew install node

node -v
```

##### Python 3
> macOS provides python 2&3 out of box.
```BASH
brew install python@3.7

python3 --version
```

#### Tool
##### iTerm2
```BASH
brew cask install iterm2
```

##### IntelliJ IDEA
```BASH
brew cask install intellij-idea
```
> See also: [Official Download Link](https://www.jetbrains.com/idea/download/download-thanks.html?platform=mac)

##### Google Chrome
```BASH
brew cask install google-chrome
```

##### Folx
```BASH
brew cask install folx
```

##### Kindle
```BASH
brew cask install kindle
```

##### OneDrive
```BASH
brew cask install onedrive
```

##### Sublime Text 3
```BASH
brew cask install sublime-text
brew cask install sublime-merge
```
> Install Package Control: `cmd+shift+p` -> `Install Package Control` -> `Enter`

##### Postman
```BASH
brew cask install postman
```

#### Entertainment
##### IINA
```BASH
brew cask install iina
```

##### Spotify
```BASH
brew cask install spotify
```
