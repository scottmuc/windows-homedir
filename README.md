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
