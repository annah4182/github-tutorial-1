# GitHub Tutorial

_by Augustus Roman_

---
## Git vs. GitHub
Git is the local where the code is at.
GitHub is a website where you can upload your code to the cloud keeping it safe if anything bad happens to the code at git you call always pull whatever was saved in the cloud. It also requires Git and allows collaboration.


---
## Initial Setup
##### This is how you make a GitHub account where things form git get send to the cloud(github)
To set up your github account all you would need to do is head to this link here [GitHub](https://github.com/join)
##### The ide is where all the code goes this is git and were its used.
Follow the instructions there and when you set that up you should head to this link [ide](Ide.cs50.io) and sign in with your username and passwords you just made moments ago.

---
## Repository Setup
* In order to set up a repository, go to GitHub and login, then hit the plus sign in the right hand corner then click on new repository, give it a name, then you click create repository at the bottm, you add a description but that's up to you.  
* You also want to be on SSH all the time if you are cloning or connecting the the remote or repository.
Now in order to connect yourself to the remote to the cloud
Type `git init` in the beginning to start
then `git add .`
So when you add all the code you wanted then you have to save it using  
`git commit -m "message"`
Then you have to use this command to make it as a definit save of your work.  
When you put a message make it similar to something you changed or did, make sure it is in present tense 

---
## Workflow & Commands
so 2 more commands for you to know is... 
#### git status
what `git status` does is that it will let you know if you have added the code to the stage and if you have commited your last changes.  
#### git push
if you have connected your repo to the code, then you type this in and all the code will be pushed into GitHub but make sure you have added and commited. 

---
## Rolling Back Changes
To discard changes all you have to type in is
#### git checkout -- file
_where it says file just put the files name like for me it is README.md_