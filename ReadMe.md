git ini
git config --global user.name "ahmedelwaraky"
 git config --global user.email "ahmed.elwaraky1@gmail.com"
 git add ..
  git status
   git commit -m "index is added"
   git add .
   git commit -m "sec change"
   git log
   ssh-keygen -C "ahmed.elwaraky1@gmail.com"
#git remote add origin git@github.com:ahmedelwaraky/GitHub-ITI-Task.git
git branch -M main
git push origin main
git branch dev 
git checkout dev 
git add dev.html
git commit -m "dev is added"
git push origin dev
git branch tetx
git checkout text 
git add text.html
git commit -m "text is added"
git push origin text
● Tell me how to remove them locally and remotely.
git rm file
git commit -m "Remove files file"
git push origin your-branch-name
●Tell me how to checkout another branch without commit changes
git stash
git checkout new-branch
git stash apply


git tag -a v1.7 813e22e -m "sec tag" 
git push origin v1.7 

● Tell me how to list tags.
git tag
git tag -n1
git tag --list "v1*"
git ls-remote --tags origin

● Tell me how to delete tag locally and remotely.
git tag -d v1.7
git push origin --delete v1.7
git push origin --delete v1.7

![Alt Text](Logo%20AW-03.png)

