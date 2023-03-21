# Git

## Differences between Git & GitHub

- Git is the sport. GitHub is the stadium.
- GitHub is a way to share and store your code.
- Git is a version control system.

**Version Control:**

> Allows users to update and revist various versions of a file.
>>**Local Version Control:** 
- Personal Computer

>>**Remote Version Control:**
- GitHub

**Cloning:**

*Enables users to copy a file from GitHub by using the following command in terminal:*

- git clone *url*

**Cloning Process:**

In GitHub:

- Navigate to desired repository
- Select Green code button
- Copy https link

In Terminal:

- Navigate to folder that you would like to clone file into
- Type Command: git clone *url*
- Navigate into cloned repository
- Type Command: code .

## ADD (File staging)

- Terminal Command: git status
- Terminal Command Options:

> git add *filename* *filename* *filename*
>
> git add * 
>>(*adds all files in the entire project*)
>
>git add .
>> (*adds files in current directory that have been changed*)

## COMMIT (Snapshot)

- Terminal Command: git status
- Terminal Command: git commit -m "reason for change"

## PUSH (Sends Changes to Repository)

- Terminal Command: git status
- Terminal Command: git push origin main
