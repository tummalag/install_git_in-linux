# install_git_in-linux

## Installing to the machine

    sudo apt install git
   
configuring username and email (optional)

    git config --global user.name "username"

    git config --global user.email "email@xyz.com"
    
### Cloning a repository from website:
    
    git clone <link_of_the_repository>
    
### Pushing  to the gitHub:

Conditions: Following steps are for already created repository in GitHub and cloned in your local system.
    
    git init
    
    git add .
    
    git commit -m "First commit"
    
Optional,
 Sets the new remote

     git remote add origin remote repository URL

 Verifies the new remote URL
  
    git remote -v

 Pushes the changes in your local repository up to the remote repository you specified as the origin    
 
    git push origin master   
    
    
    
    
    
