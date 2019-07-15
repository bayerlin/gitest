#
Git for windows portable download:

https://github.com/git-for-windows/git/releases/download/v2.22.0.windows.1/PortableGit-2.22.0-64-bit.7z.exe

- $ ssh-keygen -o
$ cat /c/Users/redcn/.ssh/id_rsa.pub
- Copy and paste a new pub ssh key at github.  

# Creat new git repositories

- $ cd /c/svn
- $  git init gitest
- $ cd gitest
- $ git remote add origin git@github.com:bayerlin/gitest.git

- $ git config --global user.email "bayerlin@gmail.com"
- $ git config --global user.name "bayerlin"
- $ git add -A
- $ git commit -m '初始化git项目'
- $ git push --set-upstream origin master


# Config sublime with git
- Ctrl+shift+p pcip
- git
- Package Settings-Git-user
  (```)
  {
    "git_command": "C:/PortableGit/bin/git.exe"
 }
(```)
- Ctrl+shift+p git:add\commit\push
