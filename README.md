# SETTING GIT WITH P4MERGETOOL
## Step
- git config --global merge.tool p4merge
- git config --global mergetool.p4merge.path "C:/Program Files/Perforce/p4merge.exe
- git config --global merge.prompt false
- git config --global diff.tool p4merge
- git config --global difftool.p4merge.path "C:/Program Files/Perforce/p4merge.exe"
- git config --global difftool.prompt false
- git config --global -e
- git rebase --abort
- git rebase --continue 
- git pull --brase origin master 
- git difftool
- git mergetool 
## Setting variable 
- C:\Program Files (x86)\GitExtensions\
- C:\Program Files\Perforce
- C:\Program Files\Perforce\
- C:\Program Files\Notepad++

# Link download tool
#### Git extension 🤝
- https://github.com/gitextensions/gitextensions/releases/tag/v3.5.4
#### Git bash 🤝
- https://git-scm.com/downloads
#### Mergep4 🤝
- https://www.perforce.com/products/helix-core-apps/merge-diff-tool-p4merge
#### Notepad++ 🤝
- https://notepad-plus-plus.org/downloads/
