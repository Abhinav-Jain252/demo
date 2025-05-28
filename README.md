# demo
This is my first Git Repo <br>
Author: Abhinav Jain

1. git clone {https-link}: for cloning git repo to the local machine

2. git status: display the status of the code.

3. 4 type of statuses:
    a. untracked: new file that git doesn't yet tracked.
    b. modified: changed
    c. staged: file is ready to be committed
    d. unmodified: unchanged

4. After a change first we had to <b>Add</b> to make it staged and then perform <b>commit</b> to change the status unchanged.

5. add: adds new or changed file in working directory of the Git staging area
    git add {file name}
    if many changes to commit then simply write: git add .

6. commit: it is the record of change
    git commit -m "some message"

7. After commit it will show on git status that we are one commit ahead on our local machine than the github code, currently on github we can't see these notes as well as index.html

8. push: upload local repo content to remote repo
    git push origin main


9. init: used to create a new git repo

    git init<br>
    git remote add origin {--link--}<br>
    git remote -v (to verify remote)<br>
    git branch (to check branch)<br>
    git branch -M main (to rename branch)<br>
    git push origin main<br>
    <br>
    here can also do: git push -u origin main<br>
    This is done to set the upstream when we want to run git push again and again no need to mention origin main further.<br>

10. Branch Commands:

    git branch (to check branch)<br>
    git branch -M main (to rename branch)<br>
    git checkout {--branch name--} (to navigate)<br>
    git checkout -b {--new branch name} (to create new branch)<br>
    git branch -d {--branch name--} (to delete branch)<br>
    git push origin {--branch name--}<br>

11. Merging Code:<br>
    Way 1:<br>
        git diff {--branch name--} (to compare commits, branches, files and more)<br>
        git merge {--branch name--} (to merge 2 branches)<br>

    Way 2:<br>
    Create a PR(Pull Request)<br>

12. Pull Request: It lets you tell others about changes you have pushed to a branch in a repository on GitHub. (When many people are working on the same project and everyone wants to merge their code with the main branch, they do it with the help of pull request). Their will be a senior developer who will be working on the main branch, they will first review our PR, they can comment on it. Then its their decesion whether they want to merge or not.

12. After Pull Request, changes had been made on the remote (i.e. Github) but not on our local machines. for making that changes in the local machine as well:<br>
<br>
git pull origin main<br>
<br>
used to fetch and download content from a remote repo and immediately update the local repo to match that content