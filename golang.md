# Golang

# Environment

Download the newest version golang [here](https://golang.org/dl/)

according to my habit, I will install it to /usr/local, and I'd like to mkdir $HOME/go as gopath  run command:

```
tar xzvf go1.7.1.linux-amd64.tar.gz -C /usr/local
```

set gopath, bin and goroute

add following lines to ～/,zshrc:

```
export PATH=$PATH:/usr/local/go/bin:/$HOME/go/bin
export GOROOT=/usr/local/go
export GOPATH=$HOME/go

```

# UI
Atom, Sublime Text, LiteIDE

In Ubuntu, LiteIDE is a good choice.

## install
Download it [here](https://sourceforge.net/projects/liteide/files/)

```
cp liteidex30.2.linux64-qt4.tar.bz2 ~/opt/
cd ~/opt
bunzip2 liteidex30.2.linux64-qt4.tar.bz2
```

run it
```
~/opt/liteide/bin/liteide
```

## GOPATH
View->Manage GOPATH->add Directory

choose path $HOME/go

OK, enjoy!