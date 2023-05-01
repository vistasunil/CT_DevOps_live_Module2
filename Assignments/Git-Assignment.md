<div align="center">
<img src=https://static.wixstatic.com/media/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png/v1/fit/w_2500,h_1330,al_c/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png width="400" height="200">
 </div>

# <div align="center"> GIT ASSIGNMENT </p>

# <div align="center"> DevOps Instructor-led Training </div>




# $${\color{brown} &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; Contact us &emsp;&emsp;&emsp; }$$

<div align="right"> T O A C C E L E R A T E Y O U R C A R E E R G R O W T H </div>

### <div align="right"> For questions and more details: </div>

<div align="right"> <img src=https://w7.pngwing.com/pngs/759/922/png-transparent-telephone-logo-iphone-telephone-call-smartphone-phone-electronics-text-trademark-thumbnail.png width="20" height="20"> +91 98712 72900 </div>

<div align="right"> <img src=https://pbs.twimg.com/profile_images/1450734615946219520/jmBHQRRa_400x400.jpg width="20" height="20"> https://www.thecloudtrain.com </div>

<div align="right"> <img src=https://icons.iconarchive.com/icons/martz90/circle/512/email-icon.png width="20" height="20"> support@thecloudtrain.com </div>

<div align="right"> <img src=https://png.pngtree.com/png-vector/20221018/ourmid/pngtree-whatsapp-icon-png-image_6315990.png width="20" height="20"> +91 98712 72900 </div>

### Exercise 1: Git Commands

#### Complete below tasks as part of this exercise:

1. Setup a GitHub account and create one repository inside it named ' **devopsdemo'**
2. Clone this repo ' **devopsdemo'** to your GCP compute instance
3. cd to the repo directory you just cloned
4. Check the branch name you are checked out currently. It should be **main/master** by default.
5. Add two files using vim editor as below:
  a. File1.txt
  b. File2.txt
6. Check the git status
7. Add and Commit the changes to the repo
8. Push the changes to the repo 'devopsdemo' to github account

### Exercise 2: Git Merge

#### Complete below tasks as part of this exercise:

1. cd to the repo directory ' **devopsdemo'** on the server
2. Create a new branch with name **feature1**
3. Checkout to feature1 branch
4. Add two files using vim editor as below:
  a. File3.txt
  b. File4.txt
5. Check status, add files, commit and push to github account
6. Merge the changes in **feature1** branch to master branch
7. Check if all changes from **feature1** branch are available under master branch after merge.

### Exercise 3: Git Rebase

#### Complete below tasks as part of this exercise:

1. cd to the repo directory ' **devopsdemo'** on the server
2. Create a new branch with name **feature2**
3. Checkout to branch **master or main**
4. Add two files using vim editor as below:
  a. File5.txt
  b. File6.txt
5. Commit the changes to master branch
6. Checkout to **feature2** branch
7. Use git rebase to merge changes from **master/main** branch to **feature2** branch

### Exercise 4: Git Merge Conflicts

#### Complete below tasks as part of this exercise:

1. cd to the repo directory ' **devopsdemo'** on the server
2. Checkout to **master/main** branch if not already.
3. Create conflict scenario with next steps.
4. Add a file name **mycode.c** with below content

```
main(){
    Function1(){
        printf("This is function 1");
    }
}
```

1. Add and commit the changes.
2. Now switch to branches feature1 and feature2 one by one and sync the code file mycode.c to each branche so that both have same **mycode.c** file
3. Now checkout to feature1 branch and added Function2 in **mycode.c** file. The final code in this branch looks like below:

```
main(){
    Function1(){
        printf("This is function 1");
    }
    Function2(){
        printf("This is function 2");
    }    
}
```

1. Commit the changes to **feature1** branch and merge it with **master** branch
2. Checkout to **feature2** branch and repeat steps g and h with below content:

```
main(){
    Function1(){
        printf("This is function 1");
    }
    Function3(){
        printf("This is function 3");
    }    
}
```

1. When you merge **feature2** branch content with **master** you will see the conflict. Resolve the conflict and push the changes to remote GitHub repo.

### Exercise 5: Git Collaboration

#### Complete below tasks as part of this exercise:

1. Create another GitHub account with different email
2. Add second account as Collaborator in your **devopsdemo** GitHub repository
3. Make some changes in **feature1** branch
4. Push changes to the repository, in a **feature1** branch on GitHub
5. Create a Pull Request from the **feature1** branch to the **master** Branch
6. From the owner's account review and approve the pull request
7. Merge the branch once pull request(PR) is approved.

### Exercise 6: Git Forking and Workflow

#### Complete below tasks as part of this exercise:

1. Fork the repo [https://github.com/vistasunil/gifworkflow-examples.git](https://github.com/vistasunil/gifworkflow-examples.git)
2. Navigate to location gifworkflow-examples/.github/workflows/ on the repo
3. You will find below workflow files:
  a. mongodb-service.yml
  b. postgres-service.yml
  c. redis-service.yml
4. Review and understand the content of this file and try to run the workflows from Action tab by making some changes to the repo content or adding files to repo.
5. Review the logs of each run. All the above three workflows will tigger together upon any changes in the repo.
