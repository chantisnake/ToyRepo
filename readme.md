# Toy Repo
This is a temporary repo just to teach the Lexos team about basic git.  

## Important files
  * .gitignore
    * all the files/directories listed this file will be ignored by git. At this moment we are only ignoring .idea folder which contains project specific settings of each developers IDE ([PyCharm](https://www.jetbrains.com/pycharm/)).
  * .git/
    * the folder with all the git information.

## Commands

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

## A decent tutorial on git
https://www.atlassian.com/git/tutorials/saving-changes/git-add

## Sample session

```
$ vi readme.md
$ git add readme.md
$ git commit -m "small edits to readme; just practing"
$ git pull
$ git push
```
## GitHub flavored MarkDown
* Header.
  * \# creates an \<h1\> tag.
  * \###### creates an \<h6\> tag.
* Emphasis.
  * \_Italic\_ will be _Italic_ or \*Italic\* will also be *Italic*.
  * \_\_bold\_\_ will be __bold__ or \*\*bold\*\* will also be **bold**.
  * \_\*\*Combined\*\*\_ will be _**Combined**_.
* Tables
**First Header** | **Second Header**
---------------- | -----------------
Content cell 1   | Content cell 2
Content column 1 | Content cell 2

* Unordered List
  * Mark LeBlanc
    * Computer Science Professor.
    * Wheaton College

  * Weiqi
    * Computer Science and Mathematics double Major.
    * Wheaton College
* Ordered List
  1. Wheaton College
  2. Norton
  3. MA  
  4. USA
  5. North America
* Emoji
  * GitHub supports emoji! 
  * \:emoji_name_here:
  * :octocat:  \:octocat:
  * [GitHub Emoji List](git@github.com:WheatonCS/ToyRepo.git)  
* Blockquotes
  * \> creates a blockquote 
    >This is a blockquote
* Images
    *![GitHub Logo](/images/logo.jpg|width=100)
    *Format: \[Alt Text](url)

-[x] phuens, #refs, [links](),
**formatting**, and <del>tags</del>
Do this before Monday.
-[ ] Javascript update
-[ ] CSS update
-[x] Hello