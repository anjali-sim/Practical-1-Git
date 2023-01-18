# Practical-1-Git

In this Practical, I have performed some Github task using commands

## 1.Pull and Merge
  First of all, I have created a file named demo.txt and saved it. Then in the terminal, we will enter ```git init``` command which creates a new Git repository.
Then we can enter the command to set the Git username 
```
git config --global user.name "Your Name"
``` 
And to set the Git email we use the following command
```
git config --global user.email "Your email"
```
<br>
  Then I have created a New Repository named Practical-1-Git.<br><br>
  
  After saving demo.txt file, I have used the following command to add the file in staging area.
  ```
  git add .
  ```
  and then commit it using the following command to perform a commit.
   ```
   git commit -m "Message"
   ```
  
![Screenshot from 2023-01-17 17-56-32](https://user-images.githubusercontent.com/122269010/213085951-f1bd85fc-081f-4a29-a2fb-c999a5d24d63.png)<br>

  Then I have pushed it by using ```git push``` command which is used to upload local repository. So, the demo.txt file will be uploaded to the Repository.<br><br>
<img src="Screenshot from 2023-01-17 17-57-54.png">
  
  Then, I have created a feature branch using ```git branch feature``` command and switched to feature branch using ```git checkout feature``` command.<br>
  Then made changes in demo file and then added and commited the file and pushed it to the Repository.<br>
  Then switched to master branch and then pulled it using ```git pull``` command.<br>
  
<img src="Screenshot from 2023-01-17 17-59-35.png">

Then in the Repository, we received the Compare and Pull Request and accept it and then merge it.<br>

<img src="Screenshot from 2023-01-17 17-59-46.png"><br><br>

<img src="Screenshot from 2023-01-17 18-00-07.png"><br><br>

Then accept merge pull request.<br><br>
<img src="Screenshot from 2023-01-17 18-00-15.png"><br><br>
<img src="Screenshot from 2023-01-17 18-00-20.png"><br><br>
<img src="Screenshot from 2023-01-17 18-00-28.png">

After merging the content is copied to master branch. We can use the git merge feature command for merging.<br><br>
<img src="Screenshot from 2023-01-17 18-00-39.png">

## 2.Rebase
Rebasing is the process of moving or combining a sequence of commits to a new base commit. 
Git rebase is the linear process of merging.
For this, we will make changes in demo file of master branch and then add and commit it using the commands.
To rebase, we just simply go to master branch and then write ```git rebase feature``` command to copy it in feature branch.<br><br>
<img src="Screenshot from 2023-01-17 18-03-36.png"><br>

<img src="Screenshot from 2023-01-17 18-11-08.png"><br>
<img src="Screenshot from 2023-01-17 18-18-14.png">

## 3.Change commit message
To view all the commits, we use ```git log``` command which lists the commits with its ID's we made in repository.
To change a commit, we use the command ```git commit --amend -m "Message changed"``` and the changes are made successfully and we view it using git log command.<br><br>
<img src="Screenshot from 2023-01-17 18-14-11.png">

## 4.Cherry Pick
Cherry-picking in Git stands for applying some commit from one branch into another branch. In case you made a mistake and committed a change into the wrong branch, but do not want to merge the whole branch.
You can revert the commit and apply it on another branch.
To cherry-pick a commit, we can use the command ```git cherry-pick commit-ID```. We can get the ID from the ```git log``` command.<br>

<img src="Screenshot from 2023-01-17 18-23-16.png"><br>
<img src="Screenshot from 2023-01-17 18-23-22.png"><br>
<img src="Screenshot from 2023-01-17 18-22-41.png">

## 5.Drop Commit
To drop a commit, we can use ```git rebase -i -r commit-ID``` command.
I have dropped a commit in feature branch.<br>

<img src="Screenshot from 2023-01-17 18-25-33.png"><br>
<img src="Screenshot from 2023-01-17 18-25-36.png"><br>
<img src="Screenshot from 2023-01-17 18-25-04.png">










