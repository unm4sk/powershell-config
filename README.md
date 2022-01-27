# Instructions

### *What to do?**
#### Configuring autocompletion:
* Don't forget to install a beta version of PSReadLine by typing:
```
Install-Module -Name PSReadLine -AllowPrerelease -Force -SkipPublisherCheck
```
* Copy `user_profile.ps1` into `$HOME/config/powershell`
* Add to $PROFILE.CurrentUserCurrentHost this line:
```
. $env:USERPROFILE\.config\powershell\user_profile.ps1
```
#### Installing neovim:
* Firstly, installing scoop: 
```
iwr -useb get.scoop.sh | iex
```

* Installing neovim itself: 
```
scoop install neovim gcc
```

That's all!
