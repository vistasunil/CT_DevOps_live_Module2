<div align="center">
<img src=https://static.wixstatic.com/media/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png/v1/fit/w_2500,h_1330,al_c/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png width="400" height="200">
 </div>

# <div align="center"> GIT ASSIGNMENT </p>

# <div align="center"> DevOps Instructor-led Training </div>

# <div align="right"> $`\textcolor{brown}{\text{Contact us: }}`$  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; </div>

<div align="right"> T O A C C E L E R A T E Y O U R C A R E E R G R O W T H </div>

### <div align="right"> For questions and more details: </div>

<div align="right"> <img src=https://w7.pngwing.com/pngs/759/922/png-transparent-telephone-logo-iphone-telephone-call-smartphone-phone-electronics-text-trademark-thumbnail.png width="20" height="20"> +91 98712 72900 </div>

<div align="right"> <img src=https://pbs.twimg.com/profile_images/1450734615946219520/jmBHQRRa_400x400.jpg width="20" height="20"> https://www.thecloudtrain.com </div>

<div align="right"> <img src=https://icons.iconarchive.com/icons/martz90/circle/512/email-icon.png width="20" height="20"> support@thecloudtrain.com </div>

<div align="right"> <img src=https://png.pngtree.com/png-vector/20221018/ourmid/pngtree-whatsapp-icon-png-image_6315990.png width="20" height="20"> +91 98712 72900 </div>

## GitHub Workflow
Refer [Repo](https://github.com/vistasunil/github-workflow-examples) for GITHUB WORKFLOWS discussed later.

## GIT COMMON COMMANDS

### Step 1: git init

You can create a repository using the command **git init**. Navigate to your project folder and enter the command git init to initialize a git repository for your project on the local system.

`git init`

![image](https://user-images.githubusercontent.com/37858762/235489958-7549be90-4a51-403e-9bad-2ca3e906885d.png)

### Step 2: git status

Once the directory has been initialized you can check the status of the files, whether they are being tracked by git or not, using the command **git status.**

`git status`

![image](https://user-images.githubusercontent.com/37858762/235490222-05a5244d-3930-4ab6-9c49-a40995ec592b.png)

### Step 3: git add

If we want to track all the files in the project folder, we can type the command, **git add.**

`git add .`

![image](https://user-images.githubusercontent.com/37858762/235490247-ece127a5-2b2f-4936-9b96-04b3dc5e3432.png)

### Step 4: git commit

Once the files or changes have been staged, we are ready to commit them in our repository. We can commit the files using the command **"git commit –m "custom message"**.

`git commit -m "first commit"`

![image](https://user-images.githubusercontent.com/37858762/235490295-4a710665-05f4-4c8d-b35f-5ba730de8eea.png)

### Step 5:git remote

Once everything is ready on our local, we can start pushing our changes to the remote repository. Copy your repository link and paste it in the command git remote add origin "\<URL to repository\>"

`git remote add origin <URL to repository>`

![image](https://user-images.githubusercontent.com/37858762/235490347-13792181-630a-4117-a864-dc25489bb188.png)
![image](https://user-images.githubusercontent.com/37858762/235490357-5dfb0975-72ed-4777-892e-9d72d36cf51a.png)
![image](https://user-images.githubusercontent.com/37858762/235490364-76066ca2-4ab8-4002-adf5-8e850452e0bb.png)

### Step 6: git push

To push the changes to your repository, enter the command **git push** origin \<branch-name\> and hit enter. In our case the branch is master, hence **git push origin master**. This command will then prompt for username and password, enter the values and hit enter.

`git push origin master`

![image](https://user-images.githubusercontent.com/37858762/235490384-ec526689-4eec-4aad-91c1-af5bcf9580bf.png)

### Step 7: git clone

If we want to download the remote repository to our local system, we can use the command **git clone \<URL\>.**

`git clone <URL>`

![image](https://user-images.githubusercontent.com/37858762/235490418-092dc27d-82b4-4a1f-9b90-18dfbbb54d73.png)

### Step 8:git pull

The git pull command is also used for pulling the latest changes from the repository, unlike git clone, this command can only work inside an initialized git repository. This command is used when you are already working in the cloned repository, and want to pull the latest changes, that others might have pushed to the remote repository **git pull \<URL of link\>**

`git pull <URL of link>`

![image](https://user-images.githubusercontent.com/37858762/235490449-cdf39b61-c191-414b-b340-1dae9d732ebd.png)

### Step 9:git branch

Until now, we saw how you can work on git. But now imagine, multiple developers working on the same project or repository. To handle the workspace of multiple developers, we use branches. To create a branch from an existing branch, we type **git branch \<name-of-new-branch\>**

Similarly, to delete a branch use the command **git branch –D \<branch name\>**

`git branch <name-of-new-branch>`

![image](https://user-images.githubusercontent.com/37858762/235490491-7d21a23a-34c7-45c9-bde4-71e06384d6f6.png)

![image](https://user-images.githubusercontent.com/37858762/235490504-7273fd1e-c536-48c9-9257-6f8675b9f0ff.png)

### Step 10: git checkout

To switch to the new branch, we type the command **git checkout \<branch-name\>**

`git checkout <branch-name>`

![image](https://user-images.githubusercontent.com/37858762/235490528-ee79b3a1-ef13-4f04-91cf-fc35570d582f.png)

### Step 11: git log

`git log`

Want to check the log for every commit detail in your repository? You can accomplish that using the command **git log**

![image](https://user-images.githubusercontent.com/37858762/235490569-ed3cc2d1-86f6-49b9-9c86-c3811c5083b8.png)

### Step 12: git stash

To stash your staged files without committing just type in git stash. If you want to stash your untracked files as well, type **git stash –u**. Once you are back and want to retrieve working, type in **git stash pop**

`git stash` 

![image](https://user-images.githubusercontent.com/37858762/235490881-44680f66-2d08-4bf7-a86e-a3ebf63f06f9.png)

`git stash –u`

![image](https://user-images.githubusercontent.com/37858762/235490908-9df89959-3cf1-4183-816d-8e3e474c16a0.png)

`git stash pop`

![image](https://user-images.githubusercontent.com/37858762/235490938-48f66d12-6f61-4b71-af17-d15847034f7a.png)

**Step 13: git revert**  
This command helps you in reverting a commit, to a previous version.

`git revert <commit_id>`

![image](https://user-images.githubusercontent.com/37858762/235490970-65945de8-03e9-4695-b70d-a69a4e758771.png)
![image](https://user-images.githubusercontent.com/37858762/235491028-3f6af0ba-094e-4d62-ab16-eba839183da9.png)

