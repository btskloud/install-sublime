# install-sublime Ubuntu 18.04 desktop
sublime installation for Ubuntu 18.40 desktop.

## open a terminal.
** NOTE: if you don't know how to open a terminal in Ubuntu 18.04 this the first challenge to build your independent solution finding skills. It is pretty easy and I am sure you can do it. FYI the $ signs will not be necessary when using these commands, but I am sure you knew that. Good luck.

## get sublime gpg
```
$ wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
```
## put sublime gpg in source list for install
```
$ echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
```
## update apt-get repo
```
$ sudo apt-get update
```
## install sublime 
```
$ sudo apt-get install sublime-text
```
# Good job you're done.. open sublime and enjoy.


## Uninstall if you need to.
```
$ sudo apt-get remove sublime-text && sudo apt-get autoremove
```
