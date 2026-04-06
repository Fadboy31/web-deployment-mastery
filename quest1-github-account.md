# QUEST 1: Install & Configure Git

## Mission
Install Git and configure it with your identity to prepare for version control and deployments.

---

## Steps Completed

### 1️⃣ Check Git Installation
```bash
git --version
$ git --version
git version 2.53.0.windows.2


### 2️⃣ Configure Git Identity
git config --global user.name "MelekhFad31"
git config --global user.email "fadhilimgaya31@gmail.com"

### 3️⃣ Verify Configuration
MelekhFad31@MelekhFad-PC MINGW64 ~
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=schannel
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=MelekhFad31
user.email=fadhilimgaya31@gmail.com
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
core.editor=code --wait
