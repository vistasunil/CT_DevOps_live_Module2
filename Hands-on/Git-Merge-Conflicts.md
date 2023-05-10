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

## GIT MERGE CONFLICTS

### Step 1: Let us first simulate a merge conflict by performing the following merge.

`git merge dev2`

![image](https://user-images.githubusercontent.com/37858762/235522527-1a10ab2e-e2c4-442d-9b17-22cc7211c407.png)


### Step 2: Once we have identified, there is a merge conflict we should go ahead and use the command given below:

`git mergetool`

![image](https://user-images.githubusercontent.com/37858762/235522539-f9532ccc-77d0-4f47-93e2-8b1f9ccd0e63.png)


### Step 3: The merge tool looks something like this, the top leftmost column is for Dev1 Branch changes, the center column is for the original code i.e. the master's code before any commits, and the right most column are the dev 2 branch changes. The area below these columns is where we make the changes, this is the place where we have the merged code.

![image](https://user-images.githubusercontent.com/37858762/235522566-26df579d-1e40-4721-a1b9-a78265af6220.png)

### Step 4: Once you have resolved the changes, save the file using ":wq", vim command for save and exit. Do the same for all the files.

![image](https://user-images.githubusercontent.com/37858762/235522586-c7b67fe2-cfee-4bda-bb37-9b68a04f7665.png)


### Step 5: After this step, see the status of your local repository you can see the file in conflict has been modified successfully and is merged with master. This modified file can now be committed to the master

`git status`

![image](https://user-images.githubusercontent.com/37858762/235522609-b6f92c41-0acd-4848-a304-505af60b2e96.png)


### Step 6: And finally, commit your changes, to the branch and then push it to the remote repository

`git commit -m "merged feature`

![image](https://user-images.githubusercontent.com/37858762/235522629-2e692971-923b-4754-bdf4-8d6f9b02882d.png)
