## GitBashCommand
### Create a new repository on the command line  
```
echo "# Class-29-GitHub-Tutorial" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/your-username/your-repo.git 
git push -u origin main

```
### Push an existing repository from the command line  
```
git remote add origin https://github.com/your-username/your-repo.git
git branch -M main
git push -u origin main
```

### Add a document file to a GitHub repository, follow these steps:
1.  **Clone the Repository (if not already cloned)**  
        Open a terminal (or Command Prompt) and run:
      
            git clone https://github.com/your-username/your-repo.git      
            cd your-repo

2.  **Add the Document File**  
           Copy the document file into the repository folder, then run:
    
                git add your-document-file.ext
  
3.  **Commit the Change**
   
           git commit -m "Added document file"

  
4.  **Push the Changes**  
           (Replace main with your branch name if different.)

           git push origin main  

### Update the Edited File
        git add . 
        git commit -m "THE MESSEGE OF CHANGES MADE" 
        git push -u origin main
        
### Change User
        git config --global user.name "Your GitHub User Name"
        git config --global user.email "your-GitHub-email@example.com"
**To handle the following error**       
![image](https://github.com/user-attachments/assets/2b45ca6a-f31e-40ad-a813-cd6110e30350)



   
   

 
