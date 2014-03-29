# Github Draw

This script generates a directory containing a git repository
which contains commits with the timestamps forged in order to
draw on github's activity visualization widget.


![Example Usage](http://i.imgur.com/Ed5mAJL.png "Example Usage")



## How to use it

1. Create a Github.com user without ANY activity.
2. Create a public repo, I named mine mitsuwa
3. Edit the github_draw.sh and put your username and email in the GithubUsername/GithubEmail field, this is needed or else the activity won't be "owned" by you
3. Run: bash github_draw.sh testdir
4. type: cd testdir
5. type: git remote add origin https://github.com/OneTrickPonyGuy/mitsuwa.git (Replacing OneTrickPonyGuy with your username, and mitsuwa with your git repository name)
6. type: git push -u origin master
7. When you go to your user page (click your username) you should see a drawing in your activity


### I want it to say something other than 'ben'

You can edit what it draws inside the github_draw.sh directly. Read the header of the file for which symbols mean what. 
