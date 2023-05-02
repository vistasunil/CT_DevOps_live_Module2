<div align="center">
<img src=https://static.wixstatic.com/media/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png/v1/fit/w_2500,h_1330,al_c/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png width="400" height="200">
 </div>

# <div align="center"> GIT ASSIGNMENT </p>

# <div align="center"> DevOps Instructor-led Training </div>

<br />

<br />

<br />

<br />

# $${\color{brown} &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; Contact us: &emsp;&emsp;&emsp; }$$

<div align="right"> T O A C C E L E R A T E Y O U R C A R E E R G R O W T H </div>

### <div align="right"> For questions and more details: </div>

<div align="right"> <img src=https://w7.pngwing.com/pngs/759/922/png-transparent-telephone-logo-iphone-telephone-call-smartphone-phone-electronics-text-trademark-thumbnail.png width="20" height="20"> +91 98712 72900 </div>

<div align="right"> <img src=https://pbs.twimg.com/profile_images/1450734615946219520/jmBHQRRa_400x400.jpg width="20" height="20"> https://www.thecloudtrain.com </div>

<div align="right"> <img src=https://icons.iconarchive.com/icons/martz90/circle/512/email-icon.png width="20" height="20"> support@thecloudtrain.com </div>

<div align="right"> <img src=https://png.pngtree.com/png-vector/20221018/ourmid/pngtree-whatsapp-icon-png-image_6315990.png width="20" height="20"> +91 98712 72900 </div>

### Exercise 1: Git Commands

#### Complete below tasks as part of this exercise:

* Setup a GitHub account and create one repository inside it named ' **devopsdemo'**
* Clone this repo ' **devopsdemo'** to your GCP compute instance
* cd to the repo directory you just cloned
* Check the branch name you are checked out currently. It should be **main/master** by default.
* Add two files using vim editor as below:
  * File1.txt
  * File2.txt
* Check the git status
* Add and Commit the changes to the repo
* Push the changes to the repo 'devopsdemo' to github account

### Exercise 2: Git Merge

#### Complete below tasks as part of this exercise:

* cd to the repo directory ' **devopsdemo'** on the server
* Create a new branch with name **feature1**
* Checkout to feature1 branch
* Add two files using vim editor as below:
  * File3.txt
  * File4.txt
* Check status, add files, commit and push to github account
* Merge the changes in **feature1** branch to master branch
* Check if all changes from **feature1** branch are available under master branch after merge.

### Exercise 3: Git Rebase

#### Complete below tasks as part of this exercise:

* cd to the repo directory ' **devopsdemo'** on the server
* Create a new branch with name **feature2**
* Checkout to branch **master or main**
* Add two files using vim editor as below:
  * File5.txt
  * File6.txt
* Commit the changes to master branch
* Checkout to **feature2** branch
* Use git rebase to merge changes from **master/main** branch to **feature2** branch

### Exercise 4: Git Merge Conflicts

#### Complete below tasks as part of this exercise:

* cd to the repo directory ' **devopsdemo'** on the server
* Checkout to **master/main** branch if not already.
* Create conflict scenario with next steps.
* Add a file name **mycode.c** with below content

```
main(){
    Function1(){
        printf("This is function 1");
    }
}
```

* Add and commit the changes.
* Now switch to branches feature1 and feature2 one by one and sync the code file mycode.c to each branche so that both have same **mycode.c** file
* Now checkout to feature1 branch and added Function2 in **mycode.c** file. The final code in this branch looks like below:

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

* Commit the changes to **feature1** branch and merge it with **master** branch
* Checkout to **feature2** branch and repeat steps g and h with below content:

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

* When you merge **feature2** branch content with **master** you will see the conflict. Resolve the conflict and push the changes to remote GitHub repo.

### Exercise 5: Git Collaboration

#### Complete below tasks as part of this exercise:

* Create another GitHub account with different email
* Add second account as Collaborator in your **devopsdemo** GitHub repository
* Make some changes in **feature1** branch
* Push changes to the repository, in a **feature1** branch on GitHub
* Create a Pull Request from the **feature1** branch to the **master** Branch
* From the owner's account review and approve the pull request
* Merge the branch once pull request(PR) is approved.

### Exercise 6: Git Forking and Workflow

#### Complete below tasks as part of this exercise:

* Fork the repo [https://github.com/vistasunil/gifworkflow-examples.git](https://github.com/vistasunil/gifworkflow-examples.git)
* Navigate to location gifworkflow-examples/.github/workflows/ on the repo
* You will find below workflow files:
  * mongodb-service.yml
  * postgres-service.yml
  * redis-service.yml
* Review and understand the content of this file and try to run the workflows from Action tab by making some changes to the repo content or adding files to repo.
* Review the logs of each run. All the above three workflows will tigger together upon any changes in the repo.
