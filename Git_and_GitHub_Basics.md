
- git :- gives a list of commands that can be used.

- touch filename.format :- creates a file

- .git is a folder (called Repository) which is used to store the changes and all versions of project

- ls -a :- to see the hidden . folders also

- ls folder_name :- to see the files in specific folder 

- git add file_name :- makes the file staged (Called to stage)

- git add .  :- all files in current directory are staged 

- git commit -m "Commit_message"  :-  To make files tracked (Clicked photo )

- git log :- To See the History (All Photographs)

- vi file_name :- To edit the file

To save a file and exit Vim: (Esc,:x,Enter)

1. Switch to command mode by pressing the ESC key.

2. Press : (colon) to open the prompt bar in the bottom left corner of the window.

3. Type x after the colon and hit Enter. This will save the changes and exit.

- master: It is the default branch name

- HEAD : It is the Pointer. If any commits are made , The branch to which HEAD is pointed to (*) is the place where commits go.

- We can use "Learn Git Branching" to understand Branching Better

- git branch name_of_branch :- Creates a New Branch


- git checkout name_of_branch :- To point HEAD to the branch created 

- git merge name_of_branch :- To merge a branch with master when we are on master branch.


- git clone Url_from_gitHub :- Makes a Local copy of Repository

- git remote -v :- Gives the details of URL's

- origin : Indicates that Project Link is from our own account

- upstream : Indicates that URL is from Main Project

- git remote add upstream Copy_of_Url_from_Main_Project : Adds the Url with name upstream 

- git pull origin master : Means to pull changes from the origin Link Project Master Branch

- git reset Commit_Id :-  Will unstage all the commits done after provided Commit_Id

- Never commit on master branch

- git push origin temp :- Pushes the temp branch to the origin URL

- After Pushing to our own forked Repo it will ask whether we want to make PR to the Master branch of MAIN REPO

- We write in this manner :- Fixes "#IssueNumber" during PR

- When we first create a PR from a branch then If we add new commits to the same branch, It wont let us create a new PR


- Making changes to the branch already sent for PR , will push the changes in commits section to the same PR, It wont create a new PR


- If we made mistake in a PR, We can revert it using reset option


- Creating a separate branch for each extra feature allows us to make separate PR . It is so advisable.



#### How to keep my fork's(origin) master branch updated with the Main Repo's(upstream) master branch

        1.git fetch --all --prune
        2.git checkout master
        3.git reset --hard upstream/master
        4.git push origin master


- git fetch --all --prune  :- It fetches all the changes from all the branches of the upstream , prune means the ones that are deleted will be created which is optional 

- git reset --hard upstream/master :- First we checkout to the master branch of our forked repo and use this command to replace our master branch with updated upstream's master

- git push origin master :- This is used finally 


- history :- To know history of commits
