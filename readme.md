# toy Repo

This is a temporary repo just to teach the Lexos team about basic git commands:  

## a couple of important files
  * .gitignore
    * all the filenames in this file will be ignored by git (so these files you are unable to add)
  * .git/
    * the folder with all the git information

## commands

  * add  
    * add the files that you have edited and want to push to the remote repo  
  * commit  
    * make a local image of the current program  
    * kind of like creating a restore point
  * pull  
    * sync from the remote to local  
  * push  
    * sync from the local to remote 
  * reset (`--soft` `--hard` and undo add)  
    * reset your program status to a commit  
        * `--soft` only reset your git info to that restore point (thereby losing all the commits in between)  
        * `--hard` reset all the program, including the git info to a certain commit   
        * undo `add` command  
  * status  
    * show the status of the current git information
  * diff  
    * show the difference between current and a commit (default is the latest commit)

## a decent tutorial on git
https://www.atlassian.com/git/tutorials/saving-changes/git-add

## a sample session

```
$ vi readme.md
$ git add readme.md
$ git commit -m "small edits to readme; just practing"
$ git pull
$ git push
```


