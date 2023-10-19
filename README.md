### Lecture Note 3

***shell:*** There are three states in Git.
- Modified
- Staged
- Comitted
---

#### config
First time setup

to check the informaiton after write down your setup information :
```
$ git config --list
```

#### init
Initializing a repository in an Existing Directory
```
$ git init
```

#### status
Checking repository status
```
$ git status
```

#### add[file_name]
adding a new file to be staged-tracked
```
$ git add[file_name]
$ git add.
```
\+ add . (adding all files to be staged)

#### rm -cached[file_name]
Unstaging a file
```
$ git rm-cached [file_name]
```

#### .gitignore file
Ignoring file
```
$ nano .gitignore
```

#### commit -m "commit
```
$ git commit -m "commit message"
```
