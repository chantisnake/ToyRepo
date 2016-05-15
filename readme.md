# toy Repo

This is a temporary repo just to teach Lexos team about the basic git commands:  

## couple of important file
  * .gitignore
    * all the filename in this file will be ignored by git(not able to add)
  * .git/
    * the folder with all the git information

## commands

  * add  
    * add the files that you want to push to the remote  
  * commit  
    * make a local image of the current program  
    * kind of like creating a restore point
  * pull  
    * sync from the remote to local  
  * push  
    * sync from the local to remote (I don't really understand why git don't just provide a `sync` command)
  * reset (`--soft` `--hard` and undo add)  
    * reset your program status to a commit  
    * `--soft` only reset your git info to that restore point(lost all the commits in between)  
    * `--hard` reset all the program, including the git info to a certain commit   
    * undo `add` command  
  * status  
    * show the status of the current git information
  * diff  
    * show the difference between current and a commit (default is the latest commit)
