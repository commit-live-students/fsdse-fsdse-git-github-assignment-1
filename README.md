# Git and Github - Assignment 1

### GitHub
* Create an account at [Github](https://github.com/)
* There’s nothing to install

### Git
#### Mac OS X
* Installed Homebrew - OS X Package Manager (skip this step if you already have Homebrew installed)  <br />
`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)`
* Open your terminal and install Git using Homebrew <br />
  `brew install git`
* Verify the installation was successful by typing <br />
  `git --version`
#### Linux
* In Git packages are available via [apt](https://wiki.debian.org/Apt)
* From your terminal first update you apt by running command <br />
  `sudo apt-get update`
* Now install git by runing command <br />
  `sudo apt-get install git`
* Verify the installation was successful by typing command <br />
  `git --version`
#### Configure 
* Configure your Git username and email using the following commands. These details will be associated with any commits that you create <br />
`git config --global user.name “YOUR USERNAME”` <br />
`git config --global user.email “YOUR EMAIL”`
* Use the same email address you used with your GitHub account
* (Optional) To make Git remember your username and password follow [add new ssh key to your github account](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/). 
