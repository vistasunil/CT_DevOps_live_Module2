<p align="center">
<img src=https://static.wixstatic.com/media/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png/v1/fit/w_2500,h_1330,al_c/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png width="400" height="200">
 </p>

# <div align="right"> GIT COMMON COMMANDS </div>

# DevOps Instructor-led Training

# **Contact us**
T O A C C E L E R A T E Y O U R C A R E E R G R O W T H

**For questions and more details:**

please call @ +91 98712 72900, or

visit [https://www.thecloudtrain.com/](https://www.thecloudtrain.com/), or

email at [support@thecloudtrain.com](mailto:join@thecloudtrain.com), or

WhatsApp us @ +91 98712 72900
</style>

##


##


## GIT COMMON COMMANDS

### Step 1: git init

You can create a repository using the command **git init**. Navigate to your project folder and enter the command git init to initialize a git repository for your project on the local system.

![](RackMultipart20230501-1-vxzewr_html_8e439cd334784e83.png)

### Step 2: git status

Once the directory has been initialized you can check the status of the files, whether they are being tracked by git or not, using the command **git status.**

$ git status

![](RackMultipart20230501-1-vxzewr_html_f356bdacbac97e94.png)

### Step 3: git add

If we want to track all the files in the project folder, we can type the command, **git add.**

![Shape5](RackMultipart20230501-1-vxzewr_html_286202bef367026a.gif) ![](RackMultipart20230501-1-vxzewr_html_98b022193abd9854.png)

###


###


### Step 4: git commit

Once the files or changes have been staged, we are ready to commit them in our repository. We can commit the files using the command **"git commit –m "custom message"**.

$ git commit -m "first commit"

![](RackMultipart20230501-1-vxzewr_html_fe97ce336a3e61c7.png)

### Step 5:git remote

Once everything is ready on our local, we can start pushing our changes to the remote repository. Copy your repository link and paste it in the command git remote add origin "\<URL to repository\>"

$ git remote add origin "\<URL to repository\>"

![](RackMultipart20230501-1-vxzewr_html_fd1a48e40a6a50e4.png)

![](RackMultipart20230501-1-vxzewr_html_7a3dfaa1dedaed34.png)

![](RackMultipart20230501-1-vxzewr_html_d2004597d2aea7cc.png)

###


###


### Step 6: git push

To push the changes to your repository, enter the command **git push** origin \<branch-name\> and hit enter. In our case the branch is master, hence **git push origin master**. This command will then prompt for username and password, enter the values and hit enter.

$ git push origin master

![](RackMultipart20230501-1-vxzewr_html_8e81112fd9f3a9d.png)

### Step 7: git clone

If we want to download the remote repository to our local system, we can use the command **git clone \<URL\>.**

$ git clone \<URL\>

![](RackMultipart20230501-1-vxzewr_html_28cb1cb0033ff71d.png)

### Step 8:git pull

The git pull command is also used for pulling the latest changes from the repository, unlike git clone, this command can only work inside an initialized git repository. This command is used when you are already working in the cloned repository, and want to pull the latest changes, that others might have pushed to the remote repository **git pull \<URL of link\>**

$ git pull \<URL of link\>

![](RackMultipart20230501-1-vxzewr_html_70e72a7b534ac601.png)

### Step 9:git branch

Until now, we saw how you can work on git. But now imagine, multiple developers working on the same project or repository. To handle the workspace of multiple developers, we use branches. To create a branch from an existing branch, we type **git branch \<name-of-new-branch\>**

Similarly, to delete a branch use the command **git branch –D \<branch name\>**

$ git branch \<name-of-new-branch\>

![](RackMultipart20230501-1-vxzewr_html_a518136e9677b5be.png)

![](RackMultipart20230501-1-vxzewr_html_48810a6077b6f9a7.png)

### Step 10: git checkout

To switch to the new branch, we type the command **git checkout \<branch-name\>**

$ git checkout \<branch-name\>

![](RackMultipart20230501-1-vxzewr_html_7b2a49ae3193b3c2.png)

### Step 11: git log

Want to check the log for every commit detail in your repository? You can accomplish that using the command **git log**![](RackMultipart20230501-1-vxzewr_html_9f649ec291864900.png)

###


###


### Step 12: git stash

To stash your staged files without committing just type in git stash. If you want to stash your untracked files as well, type **git stash –u**. Once you are back and want to retrieve working, type in **git stash pop**

$ git stash. ![](RackMultipart20230501-1-vxzewr_html_90f5d4c78a2dd664.png)

$ git stash –u ![](RackMultipart20230501-1-vxzewr_html_81c80fd9d9849187.png)

$git stash pop . ![](RackMultipart20230501-1-vxzewr_html_4b71d49af06db80c.png)

**Step 13: git revert**  **git revert \<commit-id\>** command helps you in reverting a commit, to a previous version

![](RackMultipart20230501-1-vxzewr_html_96d83364eef5ea81.png)

![](RackMultipart20230501-1-vxzewr_html_1f8b7f073852de17.png)

www.thecloudtrain.com
