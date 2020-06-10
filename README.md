# Systemback

This is a fork of systemback. The [original project](https://launchpad.net/systemback) is no longer maintained by the creator.

Simple system backup and restore application with extra features

Systemback makes it easy to create backups of the system and the users configuration files. In case of problems you can easily restore the previous state of the system. There are extra features like system copying, system installation and Live system creation.

## Install

```bash
sudo sh -c 'echo "deb [arch=amd64] http://mirrors.bwbot.org/ stable main" > /etc/apt/sources.list.d/systemback.list'
sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key 7D9C279F
sudo apt-get update
sudo apt-get install systemback
```

## Build

```bash
git clone https://github.com/BluewhaleRobot/systemback
cd systemback/sytemback
debuild
```

## Changelog

1.8.5

- Add support for Ubuntu 20.04 and large iso
