# Windows Homedir

This repository is analagous to the one that is used for [Mac OSX][osx-homedir] workstation
automation. Of course there are going to be some subtle differences because of the platform
differences.

### Bootstrapping a brand spanking new machine

```
START http://boxstarter.org/package/git

git init
git remote add origin git@github.com:scottmuc/windows-homedir.git
git fetch --all
git checkout master

START http://boxstarter.org/package/url?%HOMEDIR%\boxstarter.txt
```

**Post bootstrap TODO**

* Change windows performance settings to only have font smoothing enabled

[osx-homedir]: https://github.com/scottmuc/osx-homedir

### Repave Journal

##### October 3 2018

* Need to add documentation on how to setup the bootable USB drive as it required some BIOS
  setting tweaks and downloading of drivers from dell.com
* Once install completed had to run the installer for the WiFi drivers
* Performed a complete Windows update
* Need up adjust KB and language as my laptop is from Dell Ireland but I still
  type as if I have a US QWERTY layout
* Need to install Boxstarter first before the other things
* Create ssh key on separate machine first and put on the repave USB stick
