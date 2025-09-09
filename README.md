# IS601 Linux and Git Cheatsheet


## Linux commands
**pwd**:<br>
Show current working directory<br>
`/home/user/projects`<br>

**ls -l**:<br>
List files in long format<br>
`-rw-r--r--  1 lakshyasaharan  staff  198 Sep  9 14:51 README.md`<br>

**cd**:<br>
Change directory<br>
`cd Documents`<br>

**mkdir**:<br>
Make a new directory<br>
`mkdir folder_name`<br>

**rmdir**:<br>
Remove an empty directory<br>
`rmdir folder_name`<br>

**cp**:<br>
Copy files from one place to another<br>
`cp file_name target_folder`<br>

**mv**:<br>
Move or rename files<br>
`mv old.text new.txt`<br>

**cat**:<br>
Print file contents<br>
`cat file.txt`<br>

**grep**:<br>
Search inside files<br>
`grep "apple" fruits.txt`<br>

**history**:<br>
Check commands history<br>
```bash
 7230  git commit -m "add linux grep command"
 7231  git push origin linux-command-grep
 7232  git checkout main
 7233  git merge linux-command-grep
 7234  git push origin main
```

## Git commands
`git status`<br>
Shows status of files which are modified

`git add *file_name*`<br>
Stage files before committing 

`git diff`<br>
Check difference in files from already committed

`git commit`<br>
Commit the changes to local repo with a commit message

`git push`<br>
Push the committed changes to remote branch
