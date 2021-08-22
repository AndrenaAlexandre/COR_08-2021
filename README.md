# Homeowrk

This will be the repo that we will push and pull from daily to further grasp the Git process

## Instructions

#### Clone this repo
First open your terminal and clone this repository onto your local machine

```bash
git clone ...
```

#### Create your branch
Once the repo has been cloned open the folder in your VS code, open your terminal and create your branch. Your branch name should be your name. 

```bash
git branch Andrena

git branch
* main
Andrena

git checkout Andrena

git branch 
main
* Andrena
```

#### Complete your Homework
Once you have created your branch, navigate into your homework directory to open and complete your assignment

```bash 
ls
Homework

cd Homework

ls
monday8_23.txt

code
monday8_23.txt
```

#### Push your Homework

Once you have completed the assignment ...

```bash
git add monday8_23.txt
git commit -m "completed my homework"
git push Andrena
```

#### Time to Pull!

Once all the homework has been reviewed and merge conflicts have been resolved during class, you will need to pull these changes from GitHub to your local machine.

```bash
git branch
main
* Andrena

git checkout main

git branch 
* main 
Andrena

git pull
# this is going to update your main branch 

# now that main has been updated, we need to merge these changes into your personal branch

git branch 
* main 
Andrena

git checkout Andrena

git branch
main
* Andrena

git merge main
# this will now merge into your branch the information that was in main
```

## Congratulations

Pat yourself on the back! Now get ready to do this all again tomorrow!!





