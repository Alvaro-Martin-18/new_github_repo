# my_first_repository

Git is a timeline, which allows you to go back in time and refer to a single porject

github backs up the timelines

if you go to a certain folder (inside git) and type "git init" you will start your tmieline
Git will also make a repository of the subfolders where you initiated the timeline

## 4 conceptual areas

- Development area

- staging area

- local repository

- remote repository - github in this case

To initialise a repository, you first need to open git.

then cd to your folder/directory where your repository is

to make this folder a repository, type:

```
git init
```

you can check that the repository has been made by looking at it visualy in ungit

if you want to add a file from elsewhere into the repository, you do this by:

```
git add FILE1
```

this will add FILE1 into the respository made

to commit chaging the file inside, you then write 

```
git commit -m"meaningful_message"
```

here, m is an additional message which explains why there has been changes, what is expected of the changes, what has to be done after the changes....git log 

```
git status
```

this will show the status of the repository, if the files inside have been commited, what files are inside.

this is useful to see the timeline of the project

erfad

this will only show the differences between the files that have been commited - only after fit commitgit 

```
git log
```

this will show the history of all the commits. showing who commited, what time, what message was added to the commitment

```
git show <commitID1> <commitID2> #this will show you two different versions of the the file so you can compare 
git diff  #this only shows the differences in the code between commitments
```





this is the new line
