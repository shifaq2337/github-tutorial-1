# GitHub Tutorial

_**by Bianna Orielle Krubitski**_

---
## Git vs. GitHub
**Git**: a platform that keeps snapshots of your code (version control)  
* Runs in the Command line 
* not open to viewers besides yourself
* One can create a directory; initalizing git allows the directory to become a repository -->   
later allowing you to:
    * edit files
    * add files
    * commit files

**Github**: stores your code in the cloud platform (a website; for example: Github.com)
* easy way to collaborate on projects when working with a partner
* It is an opensource (everyone with access to github can view your work)
* simple way to track changes made on the project with just a few commands
* MOST IMPORTANTLY: One cannot use Github without Git, however, Git does not need to contain Github to be activated 

---
## Initial Setup
_**How to set up your account with Github...**_

1. Go to github.com and press the button that says "sign up"
    * use an email and password (for HSTAT students, sign up using your school email and password)
    * once you're done signing up, check your email and verify with github  

2. Go to c9.io
    * creat an account(first/last name, email, password, etc.)
    * once set up, press on the gear in the top right corner
    * go to connected services
    * connect your github with cloud9 by clicking on the connect button  

3. In the future you will sign into cloud9 using your github account. This is how you do it...  

![ Alt if you want to sign-in to github using c9, this is where you go...](https://raw.githubusercontent.com/OperationSpark/using-c9/master/img/c9-signin-github.png)    

4. Creating an SSH key(between Github & cloud9)
    * Github
        * Being signed in at Github.com, go to your profile icon in the top right and press settings
        * go to the left sidebar and then into SSH and GPG keys
        * press New SSH and give it a title of your choice (unless a teacher instructs otherwise)
    * cloud9
        * go to the gear icon in the top right corner
        * navigate to the SSH keys tab
        * copy/paste your SSH key (begins with ssh-rsa) into Github
        * Add SSH key

---
## Repository Setup
_**To create your 1st repository...**_  
1. go to Github.com and click on the **(+)**, then click **New Repository**
    ![below is the snapshot attached](https://github-images.s3.amazonaws.com/enterprise/11.10.340/user/assets/images/help/repository/repo-create.png)    
2. Create a short and sweet name for your repository (for example: first-repo)  
3. Keep it **Public**, so people can check out your work and fork it9add their own changes and make it better with your permission)    
4. Select **initialize this repository with a README.md**  
5. finally, click **Create Repository**  

_YAY for you! You successfully created your first repository and initialized a README.md file inside of it_

_**Add, Commit, and Push your First Changes...**_
1. Go to c9.io and open your workspace  
2. (Begin typing in the commnad line) To make sure you're inside your workspace, type:
```
cd ~/workspace
```
3. next, type: 
```
mkdir and (the name you gave your first repository on github when making it)

```
```
for example: mkdir first-repo
```
4. go inside of your repository by typing:
```
cd (name of your repository) 
```
5. Then, type:
```
git init
```

---
## Workflow & Commands