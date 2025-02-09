## GitBashCommand
### Create a new repository on the command line
echo "# Class-29-GitHub-Tutorial" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/your-username/your-repo.git 

git push -u origin main

### Push an existing repository from the command line
git remote add origin https://github.com/your-username/your-repo.git

git branch -M main

git push -u origin main
