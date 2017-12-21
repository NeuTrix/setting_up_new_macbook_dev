# settingup_new_macbook_dev
Tracking resources used to set up my macbook dev environment

## Key links
[How to set up- Guide](https://alexw.me/2013/10/definitive-guid-to-development-mac-setup/)

# Install Core Applications
### Enable Git- Install [X-Code]() 
Mac dev environment to enable Git.  To install the command line tools:
- `xcode-select --install`

*In order to set up global storage of git login (to eliminate continuous prompts:*
```bash
$ git config credential.helper store
$ git push http://example.com/repo.git
Username: <type your username>
Password: <type your password>
```
### Install [iTerm 3]
A better way to terminal

### Set up a [bash_profile](https://redfinsolutions.com/blog/creating-bashprofile-your-mac)
```
cd ~
touch .bash_profile
```
You can open and edit this file with a text editor.  With nano:
`nano ~/.bash_profile`

### Install [Sublime](https://www.sublimetext.com/download)
This is my favorite text editor.  To set it up as default editor in your bash profile, follow [these instructions](https://stackoverflow.com/questions/16199581/open-sublime-text-from-terminal-in-macos)

### Install [Homebrew](https://www.howtogeek.com/211541/homebrew-for-os-x-easily-installs-desktop-apps-and-terminal-utilities/)
Make sure you have the xcode command line tools installed, then run:

- `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
- `brew doctor`
- `brew install caskroom/cask/brew-cask`

### Install [Yarn](https://yarnpkg.com/lang/en/docs/install/)
- `brew install yarn`


### Install [Node](http://blog.teamtreehouse.com/install-node-js-npm-mac)
- `brew install node`
- `node -v` to verify installation

-----------

# Usefull packages
-- NPM

## Global
-- [tree-cli](https://www.npmjs.com/package/tree-cli)


### Git
- Setting up a new remote



-------------

## Helpful apps
- Alfred app: search
- spectacle: window management

### Iterm 3
- Color profiles (Plumbtree from Iterm Profiles folder, local) <link>

