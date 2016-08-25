# GitLearning
## Files
* **gitLearns.txt** - As I learn command line git, I will summarize my findings here for future reference <br>
* **gitconfig.txt** - this is literally my .gitconfig. I have it hardlinked (see gitconfighard.shexe) <br>
* **justinhileman.info article git-pretty git-pretty.png** - found a great image for what to do when you mess up a commit <br>

## .shexe
a made up file extension I told my computer to run in the terminal when double clicked
They are actually just .sh files. Or .bash. I don't know if there is a difference between the two.

if it has all in its name it applies to all git directories contained one directory up. (aka includes this git directory itself)

* **allGraph** - makes pretty graphs
* **allStatus** - checks the statuses
* **pullALL** - will basically run git pull - realigns local to look like remote
* **resetALL** - will run hard-reset pull - basically makes local look like remote again
* **firstPushRepo** - initializes a newly created repo by making a directory, grabbing the .gitignore from here, and pushing the first push.
* **gitconfighard** - checks existence of ~/.gitconfig and if it doesn't exist will hardlink gitconfig.txt with it