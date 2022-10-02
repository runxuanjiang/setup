# Setting up WSL

## Installing WSL
Open powershell and use the command
```
wsl --install
```

Check the version installed by using
```
wsl -l -v
```

Install Windows terminal (from the Microsoft store)
* Set Ubuntu to be default terminal

## Installing base packages

These packages are the suggested packages for Umich EECS 280.
```
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install g++ make rsync wget git ssh gdb tree
```

## Setting up Zsh and Oh-My-Zsh

install Zsh
```
sudo apt-get install zsh
```
Install [Oh-My-Zsh](https://ohmyz.sh/#install)

Install [PowerLevel10k](https://github.com/romkatv/powerlevel10k)
* Install the font first (Meslo)
* Set the font to be Meslo for Windows Terminal
* Set the font to be Meslo for VS Code (see instructions in powerlevel10k readme)
* Install PowerLevel10k
* Configure PowerLevel10k (follow the instructions in the github readme and terminal)

## Install Anaconda
Install [Anaconda](https://www.anaconda.com/products/distribution#linux)


## Setting up Windows terminal (WT)
Set the "startingDirectory" option.

Set the background image and opacity