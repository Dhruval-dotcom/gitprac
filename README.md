
# Practical-1

1. Pull and Merge difference

- Make example of pull request and two branch merge event.

## Steps
- made 5 commits on master branch.
- checking out to commit 2 and creating feature branch and commiting 1 time.
- after that after checking out to master ,merged feature branch.

## Commands used

To run practical, the following commands are used

```bash
git commit 
    #{-upto 5 times}
git checkout c2
git checkout -b feature
git commit
git checkout master
git merge feature
```


## Here is Workflow of prac

![alt text](https://github.com/Dhruval-dotcom/Git_Practicals/blob/master/picture%20prac/Picture1.png?raw=true)

## Command Merge
![alt text](https://github.com/Dhruval-dotcom/Git_Practicals/blob/master/picture%20prac/Picture11.png?raw=true)

## Pushing to remote
![alt text](https://github.com/Dhruval-dotcom/Git_Practicals/blob/master/picture%20prac/Picture22.png?raw=true)

## Pulling repo
![alt text](https://github.com/Dhruval-dotcom/Git_Practicals/blob/master/picture%20prac/Screenshot%20from%202023-02-20%2010-23-45.png?raw=true)


## Environment Variables

To run this practical, following commands used majorly

`git merge feature`

# Practical-2

2. Rebase

- Try to rebase feature branch with master branch 

## Steps
- commiting 4 times in master branch
- checking out to c2 
- creating feature branch 
- checking out to master
- rebase feature it with main branch.

## Commands used

To run practical, the following commands are used

```bash
git commit 
    #{upto 4 times}
git checkout c2
git checkout -b feature
git commit
git checkout master
git rebase feature
```


## Here is Workflow of prac

![alt text](https://github.com/Dhruval-dotcom/Git_Practicals/blob/master/picture%20prac/Picture2.png?raw=true)

## Comand Rebase
![alt text](https://github.com/Dhruval-dotcom/Git_Practicals/blob/master/picture%20prac/Picture33.png?raw=true)


## Environment Variables

To run this practical, following commands used majorly

`git merge feature`

# Practical-3

3. Change commit message

- Commit push on commit in feature branch and then change commit message

## Steps
- commiting two times in master 
- checking out to feature 
- commiting 4 times
- commanded with commit --amend 
- and rebase -i HEAD~3

## Commands used

To run practical, the following commands are used

```bash
git commit 
    #{2 times in master}
git checkout -b feature
git commit  
    #{4 times in feature}
git commit --amend
git rebase -i HEAD~3
# put reword in place of pick edit comment 
```


## Here is Workflow of prac

![alt text](https://github.com/Dhruval-dotcom/Git_Practicals/blob/master/picture%20prac/Picture3.png?raw=true)

## Rebase and after that reword
![alt text](https://github.com/Dhruval-dotcom/Git_Practicals/blob/master/picture%20prac/Picture32.png?raw=true)


## Environment Variables

To run this practical, following commands used majorly

`git commit --amend`
`git rebase -i HEAD~3
`

# Practical-4

4. cherry pick

- Pick some commits from feature branch to master branch

## Steps

- commiting two times in master 
- make feature branch 
- commit 3 times in feature 
- checkout to master
- cherry-pick c2 c3 

## Commands used

To run practical, the following commands are used

```bash
git commit 
    #{upto 2 times}
git checkout feature
git commit 
    #{3 times in feature}
git checkout master
git cherry-pick c2 c3
```


## Here is Workflow of prac

![alt text](https://github.com/Dhruval-dotcom/Git_Practicals/blob/master/picture%20prac/Picture4.png?raw=true)

## Command cherry-pick
![alt text](https://github.com/Dhruval-dotcom/Git_Practicals/blob/master/picture%20prac/Picture41.png?raw=true)


## Environment Variables

To run this practical, following commands used majorly

`git cherry-pick c2 c3`


# Practical-5

5. Drop commit

- Remove some commit from feature branch.

## Steps

- commit 1 time in master
- Make feature branch Commit upto 3 times in feature
- Git reset Hard

## Commands used

To run practical, the following commands are used

```bash
git commit
git checkout -b feature
git commit 
    #{upto 3 times}
git reset –hard HEAD~1
git reset –hard HEAD~1
```


## Here is Workflow of prac

![alt text](https://github.com/Dhruval-dotcom/Git_Practicals/blob/master/picture%20prac/Picture6.png?raw=true)

![alt text](https://github.com/Dhruval-dotcom/Git_Practicals/blob/master/picture%20prac/Picture7.png?raw=true)

## Command reset
![alt text](https://github.com/Dhruval-dotcom/Git_Practicals/blob/master/picture%20prac/Picture51.png?raw=true)



## Environment Variables

To run this practical, following commands used majorly

`git reset –hard HEAD~1`


