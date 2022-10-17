1)git --version

![git version](https://user-images.githubusercontent.com/114742949/194249028-b624447f-6c8b-4564-9e73-ba6eded2bed9.png)

this command is used to check our current version of git

2)git init

![git init](https://user-images.githubusercontent.com/114742949/194251064-7bc2d427-c06d-4b83-aba3-49650e2abbfb.png)

the git init command creates a new repository 
It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository

3)git config --global user.name "shoaibakthar18nov"

![git config username 3](https://user-images.githubusercontent.com/114742949/194276421-87ffd4e9-4eaa-4af9-a6ea-1a63b726031a.png)


this command is to set our git username as shoaibakthar18nov firts time only

4) git config --global user.email "shoaibakthar18nov@gmail.com"

![git config useremail2](https://user-images.githubusercontent.com/114742949/194276740-03d140a9-fb30-4a02-97b8-699f9c8c3d31.png)

this command is to set our git useremail as shoaibakthar18nov@gmail.com firts time only

5)git status

![git status](https://user-images.githubusercontent.com/114742949/194277242-69d28122-fe5b-4c71-8ffd-af9440281b14.png)

this command displays the state of the working directory 
and the staging area and also in this untracked files: it means the file README.md which is created but not tracking the file

6)git add README.md

![git add readme](https://user-images.githubusercontent.com/114742949/194278894-d152304d-f941-4334-b02b-1c3cf8f99de8.png)

this command is used to adding the file .the name of the new file which is added is README.md

7)git add .

![git add 2](https://user-images.githubusercontent.com/114742949/194281052-25b3d546-de68-4fae-9f6a-26b6303d8e83.png)


this command is used to adding all the file and changes to be commited and tracking the files.
in this we can see two files are added


8)git commit -m "this is my first commit"

![git commit m](https://user-images.githubusercontent.com/114742949/194284712-669d4e20-cb5c-4305-8908-43e2fccf560c.png)

a shortcut command immediately creates a commit with a passed commit messages that is 2 files changed,3 insertions

9)git branch

![git branch](https://user-images.githubusercontent.com/114742949/194285863-ccb728e6-be54-46cf-91e4-c292c4e0e1b1.png)

this command checks the which branch we are in 

10)git remote add origin https://github.com/shoaibakthar18nov/ineuron-industry-assignement1.git

![git remote add origin](https://user-images.githubusercontent.com/114742949/194287414-f45bd037-4140-433c-a1f4-271c5f25df71.png)

this command is used to new remote, it use the git remote add command on the terminal in the dirctory our repository is stored at.

11)git remote -v

![git remote -v](https://user-images.githubusercontent.com/114742949/194288166-a35f4b3c-121d-4349-9a24-b0a2d35d247b.png)

this allows to use commands such as a git without any arguement and also fetch and push branch has setted.

12)git push -u origin main

![git push -u origin main](https://user-images.githubusercontent.com/114742949/194288869-3287cdc1-d701-4995-9279-f7d14cfe7637.png)

push all the files to main with respect to all things that been added and this is will goes to the github repository.

13)git pull origin main

![git pull origin main](https://user-images.githubusercontent.com/114742949/194294391-87f92767-b658-4d02-a61c-1c1e4e5db4f1.png)

pull request for new file that is  assignment-1-task-1 file to add main


14)git push origin main

![git push origin main](https://user-images.githubusercontent.com/114742949/194292090-b73fbae7-a8ab-415d-ad04-54c97a0f8ac6.png)

pushing all the files from the origin to main branch

15)git branch developer1

![git branch develp1](https://user-images.githubusercontent.com/114742949/194294938-90cbc6b6-1946-4d36-a0d9-9705e418a101.png)

creating new branch with name as developer1

16)git checkout developer1

![git checkout devep1](https://user-images.githubusercontent.com/114742949/194295287-8b9e2729-9e22-498b-8eaf-036828e104e7.png)

switching main branch to developer1 branch

17)git merge developer2

![git merge deve2](https://user-images.githubusercontent.com/114742949/194296048-2b930786-5b9b-4e42-a83d-9770fbe008e8.png)

this command lets takes the indepenedent lines of development created by git branch and integrate them into a single branch

18)git log

![git log](https://user-images.githubusercontent.com/114742949/194299647-036361be-d35e-48c7-9380-d4bc72638bef.png)

this command gives the how many commits are happened
