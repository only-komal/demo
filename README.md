# demo
1st git repo
<br> br tag means next line 
<br>
to make changes from git there are specific commands to be used:-
<br>git config --global user.name "my name"(to name the file as you wish to the whole system with that email id)
<br>if local used then changes are made to a specific file or repo by a different particular gmail or account 
<br>git config --global user.email"someone@gmail.com"(to save changes to a paticular gmail you want to open in )
<br>git config --list(teels /shows us the changes we have made by git config )

<br>use Command git clone (http link of the repo from code section on github)to get any repo from github to our system.

<br>after making changes to that github file through local editor make sure to do the two step process:-<br>1.add<br>2.commit. 
<br>if not done changes will only appear in the file in your local system file and not on the github file.as both of them are two different files.
<br>generally there are 4 types of status
<br>1.Untracked:-new file created in the folder that git doesn't yet track.
<br>2.Modified:-changed.
<br>3.staged:-file is ready to be commited.(file which has been added but not commited.)
<br>4.Unchanged:- files after being commited.

<br>Add & Commit 
<br>add-adds new or changed files in your working directory to the git staging area.use the syntex:- git add <-file name->
<br>for eg:- git add index.html or git add README.md and then check the status again.
<br>if we want to add all the files at once and not individually then write:- git add "." 

<br>Commit:-it is the record of change using the command, git commit -m "any message you want to display".

<br>after add and commit when status checked again it'll show Your branch is ahead of 'origin/main' by 2 commits. 
  (use "git push" to publish your local commits)

  that means your local changes are ahead of the file in github and hence to make them visible on git also we'll use "PUSH" command.

  <br>Push:-upload local repo(editor/laptop) content to remote repo(github) using the command:- git push origin main.
  <br>
  origin(the repo from which we took the clone in remote,generally or by default kept as "origin we can change it if we want") main(branch name).

  <br>INIT Command:- used to create a new git repo
  create a new folder in the same folder ,open the terminal to that new folder using <br>1.cd .. (to get out the current directory)<br>2.mkdir (to create new folder through terminal,we can also normally make them using the options available)<br>3. go to the newly made repo through the command:- cd folder name

<br>
<br>Now to make changes to newly made folder/repo we'll first have to make it a git repo (we can check if it is a git repo or not using the command:- 'ls -a' if it shows .git folder in it that means it's a git repo else no)
<br>
<br>make it a git repo using command:- git init
<br>(if any issue look at shraddha khapra video from 40:55)

<br>
<br>Now if we want to upload a project from our local system to github .
<br>1.Go to github profile--->repositeries--->New--->Name it and create.

<br>
<br>now before pushing we need to run a command :- git remote add origin <-link->(that means we want to add a new remote repo and keep it's name origin from now)(link here is the link of the repo)
<br>
<br>use:-git remote -v ,to verify/check which remote repo are we talking or working on .

<br>
<br>use:- git branch ,to check which git branch are we working on.(the different copies of a project to be worked on by different teams is known as branching.) 

<br>
<br>use:-git branch -M (new name of the branch), to rename a branch.

<br>as soon as we are on our desired branch we can use the command ,git push origin main to push smtg to  it.

<br>
<br>Now if we don't want to keep on writing origin main every time we perform a push operation while working a project for a longer period of time the we can simply use the command:-git push -u origin main .(telling that we want to make all the future changes to this particular branch by default.)

<br>we can create the readme.md file manually too in any  particular repositary if not created while creating the repo.

<br>don't forget to add and commit everthing you create.


<br>
<br>try making any new project in git first as it'll be easier to clone and get it into local system to make further changes and work on.


<br>
<br>General workflow for the local git should be:- git repo--->clone--->changes--->add--->commit--->push.


<br>
<br>
<br>Branch Commands :-
<br> use git branch:- to check branch
<br> use git branch -M main:- to rename branch
<br>git checkout <-branch name->:- to navigate
<br>use git checkout -b <-new branch name->:-to create a new branch
<br>use branch-d <-branch name->:-to delete branch.

<br># to delete a particualr branch we need to be on another branch ,we can't delete a branch we are currently are.

<br>channges made to a particular branch only,will be reflected in that particular branch only.

<br>to see the changes in git ,we need to push the changes in that particcular branch using cmd:- git push origin <-branch name->
(if any issue refer to 55:20 of the video)

<br>
<br>
<br>MERGING the CODE:-
<br>WAy 1:- 
<br>use git diff<-branch name-> :- to compare commits,branches,files and more













author-komal 
