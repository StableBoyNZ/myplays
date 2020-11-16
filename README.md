# myplays
Custom ansible playbooks for simple tasks and queries
Generaly consists of templates however code meant to be universal
----Reference CheatSheet Memory Refresher Below-------
1. GitHub allows you to host your code repositories online. I'll set up everything for it in this video. I'll also cover remote depositories in general.
2. Remote repositories are normally read only, or read write only to those who are authorized
3. You either push or pull updates from these remote repositories.
4. To push your directory to GitHub ----------------
a. git init
b. git add . # Stages all new and modified files and directories
c. git commit -m 'Initial Project Version'
d. git remote add origin URL
e. git push origin master
5. git remote -v # Lists all remotes and their URLs
6. git fetch origin # Gets data from the remote, but it doesn't merge changes with your work
7. git pull URL
a. Pulls all changes and saves them to your directory
8. How to push changes to GitHub ----------------
a. I add .gitignore for Android on my local machine
b. In the terminal type
I. git add .gitignore # Stage .gitignore
II. git commit -m 'Added .gitignore for Android' # Commit
III. git push # Push the changes to GitHub
9. git remote rename origin sf # Renames remote to sf
10. Tagging ----------------
a. Tags are used to tag files at important points in history
b. git tag -a v0.1 -m 'version 0.1' # Creates an annotated tag
c. git tag # Shows all the tags
d. git show v0.1 # Shows details about the commit that was tagged
e. git tag v0.4-lw
I. Creates a lightweight tag on a commit that stores the hash for the commit
f. git tag -a v0.01 c930a8
I. You can tag commits after the event also. When you enter this command an editor opens for you to leave a comment. The final part is the hash for the commit you want to tag.
g. git push sf v0.1 # You can also push tags
I. The tag shows up under releases on GitHub
II. git push sf --tags # You can also push all tags at once
h. You can set aliases to save time
I. git config --global alias.co commit
II. Now you can type git co to commit
i. Clone a GitHub Repository
I. Go to the directory you want to use
II. git clone URL
