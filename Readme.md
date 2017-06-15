## Install NVM (Node Version Manager)

nvm is a version manager for node, it allows you to install, switch versions and has built in shasum -a 256 checksum when downloading nvm. It's similar to using rbenv or rvm in ![ruby icon](/assets/images/ruby-icon.png)ruby land![ruby icon](/assets/images/ruby-icon.png).

## Mac OS X

1. Install [brew](https://brew.sh/) if you haven't already
2. Install nvm
  ```
  brew install nvm
  ```
3. Open *~/.bash_profile* in your code editor and append
  ```
  export NVM_DIR=~/.nvm
  source $(brew --prefix nvm)/nvm.sh
  ```
4. Reopen your terminal and run command to see if nvm installed
  ```
  nvm --version
  ```
5. Install version of node you want
  ```
  nvm install 8
  ```
6. Optional: Change version (if you want to swap versions for whatever reason)
  ```
  nvm use 8
  ```
