# git-practice

intially the local changesin the code it wil be pushed in to the stagging area with the command called git add. to add all files or git add filename with extension 

After it is pushed into the stagged area we can use a command called git Commit to pushed it into the local repository and when the code from the 
local repository is pushed into the git or remote repository

The code from the remote repositoy can be pulled backed into the local repository with all the commits or all the cganges history by using a 
coonad called git pull 


Practicing all the GitHub commands via LinkedIn Learning 
intially the local changesin the code it wil be pushed in to the stagging area with the command called git add. to add all files or git add filename with extension 

After it is pushed into the stagged area we can use a command called git Commit to pushed it into the local repository and when the code from the 
local repository is pushed into the git or remote repository

The code from the remote repositoy can be pulled backed into the local repository with all the commits or all the cganges history by using a 
coonad called git pull 

we can also add a message to the commits that we had done while using git command like git commit -m " some messgae that you wanna add " 


git status is used to know status of the files in the staging area or files those are yet to be commited . 

After all the files are committed then all the files will be in the local repository and are ready to push into remote repository 
it can be done using 

git push 

all the changes in the local repository are updated in the remote repository after this command 

git diff is used to know what were the changes made to the code or to know the changes made to the code 

If the code is added into the staging area after making the changes and then at that moment if we wanna know the differences 

then we have to use git diff -chached or git diff -filename to understand specific file name changes 

git log can be used to get the history of all the changes made to the repository 


git show b358204378578697ca9185d1262deccf386d1efd[commit chekcsum or code that we get whne we enter the git log ]

to know what has happened to that speific commit . 

git log -p command is used to know what has happened in each commit . 

git log --graph to understand what branches commits had done what or to understand commits in terms of branches . 

git log --grep="diff" command is used to search with a key word in commits 

Let's say that I am searching for a commit that has a keyword diff in it then we have to use 

--grep="diff" If we had committed something on diff it will search for all the commits in diff and give us that specific commit 

After renaming the file and saving it Git will think that a new file with new name is created bu new contents and old file is deleted in our case we had chnaged the name of example.txt file to firstexample.txt and git will think that example.txt is deleted and a new file called 
firstexample.txt is created with new contents but after we added the file to the staging area then git understands that the file has been renamed . 

git restore --stagged filename 

to restore or undo the file changes those were in the staging area 

To Explain more ,For example if made changes in the two files let's say Readme.md and FirstExample.txt then  we can use git add . commad to add the changes that we were made for the two files to the staging area  ,
now if you don't wanna add one file let's say readme file into the staging area you wanna undo it then we can use 

git restore -stagged filename in this case 
git restore -stagged README.md 

this will restore the file from stagging area to the original file 

so now the status is only one file is in the staging area not all

use can also use git restore -stagged . to move all the files or undo the files from stagged area to original files . 


we can also use git restore .  which is so powerful command to undo all the changes to the two files to the original content 

git log --oneline  to see all the commits in oneline 