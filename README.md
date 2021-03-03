# Start_Git
My first repository ,dedicated to learning and documenting Git.

1) To create a new repository in git
    # mkdir new_repo
    # cd new_repo
    # git init   (git inti command to create a new repo) 

  2) To clone a already existing repo on GitHub (start_git) we need the repo url,
  selecting the green code button you can choose between the SSH option and the https,
  copy the line next to it,  exmpl.(ssh)git@github.com:jesusgc2033/Start_Git.git and,
  (https) https://github.com/jesusgc2033/Start_Git.git ,
  To copy this repository onto your local machine...        //ssh option gave me errors trying to clone so i used https and worked fine.
   
   # cd desktop/html
   # clone git https://github.com/jesusgc2033/Start_Git.git
  Now that we have cloned the repository to our local machine we can test this by :
   # cd start_git
   # git remote -v
   Results:
origin  https://github.com/jesusgc2033/Start_Git.git (fetch)
origin  https://github.com/jesusgc2033/Start_Git.git (push)

/////////////////////////////////  Git Workflow  ////////////////////////

3) To Create a new folder , we use the command mkdir
  # cd Start_Git
  # mkdir workflow
  
4) To create a new file in this folder , use comand touch
  # cd workflow
  # touch workflow.txt
  # echo "hello workflow and github" >> workflow.txt     // echo adds text to the new file , to open.. start workflow.txt

5) To see if file is staged or not Type.. git status , 
In the output, notice that x file is shown in red, which means that x is not staged..
 # git status

6) To add file to stageing area Type... git add workflow,
Now, type git status again. In the output, notice that your file is now shown in green,
which means that this file is now in the staging area.

  # git add workflow
  # git status
  
7) The git reset command is used to undo a git add
8) The git commit command is then used to Commit a snapshot of the staging directory to the repositories commit history.
Type git commit -m "workflow" and then type git status once more. The output should now say, “nothing to commit, working tree clean”, indicating that your changes have been committed. 

  # git commit -m workflow
  # git status
  
9) Type git log.. and look at the output. You should see an entry for your “workflow” commit. You will also see details on the author who made the commit and the date and time for when the commit was made.
  
  # git log
  
10) Type git push origin main To upload your work to the GitHub repository "start_git"

  # git push origin main
 
 11) Type git pull "repo" to download repository from github
 
  # git pull workflow.txt
  
 //////////////
 mkdir ""
 cd ""
 touch "".html
 git add ""             // tracks your files and changes in git
 git commit (-m -a)""   // Saves your files and changes in git
 git push origin main   // Uploads git commits to github
 git pull ""            // Downloads git repo to local
 
 ///////////////
                   TEST REPOSITORY 
                   
 1) Create a local directory
    # mkdir git-test 
   
 2) Enter fdirectory
    # cd git-test

3)  create file
    # touch index.html
   
4)  Add text
    # echo "first test repo" >> index.html
   
5) inicialize repository 
    # git init
    
6) add 
 
  
  echo "# git-test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/jesusgc2033/git-test.git
git push -u origin main
  
 



