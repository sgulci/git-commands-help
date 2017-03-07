### if you forget .gitignore file in the first place, want to remove files from repo that should be ignored
```sh
$ git rm --cached -r .  
$ git add .
```
### İf you want repo to another server 
```sh
$  git clone --mirror <URL to my OLD repo location>
$  cd <New directory where your OLD repo was cloned>
$  git remote set-url origin <URL to my NEW repo location>
$  git push -f origin
```
