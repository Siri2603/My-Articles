![images (2).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627721148182/4qC_ggFU0.png)
<br>
**What is Unix?**

**Unix** is an operating system. It supports multitasking and multi-user functionality. Unix is most widely used in all forms of computing systems such as `desktops, laptops, and servers.`

![download (3).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627721352806/lM4lGVgfR.png)

Here are some common basic shell commands which will be useful for some basic operations:

1. **PWD** - Prints present working directory.  
   `eg: pwd`
2. **LS** - Lists all files and folders in a directory.
   `eg: ls`
3. **CD** - Takes an argument about the folder that you want to navigate to.
   `eg: cd Documents`
4. **CD ..** - Navigates to one level up.
   `eg: cd ..`
5. **Clear** - Clears the screen.
   `eg: clear`
6. **Exit** - Exit the terminal.
   `eg: exit`
7. **Man** - This is to get the manual of a particular command and It will give all information regarding the cd command.
   `eg: man cd`

**CRUD-Create, read, update, delete.**

7. **Touch** - To create a new text file.
   `eg: touch hello_world.txt
8. **Echo** - To type or insert the content in the file.
   `eg: echo "Hello" >> hello_world.txt`
9. **Nano** - To edit the content.
   `eg: nano hello.txt`

**CRUD on Directories:**

1. To create a directory: **mkrdir**

2. To move the directory from one location to another: **mv**

3. To remove the directory: **rm**

4. To copy the files and folders: **cp**

![images.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627720813944/dkxzESp8z.png)

**Git** is a version control system that lets you manage and keep track of your source code history.

There are three various stages in git.

- **Working tree**`(Untracked area)`: This is used to create, update and delete the file. It doesn't start the tracking yet.
- **Index**`(Staging area)`: This is the preparation area and git starts tracking changes in files. And here we can still make changes in files.
- **History**`(Committed stage)`: It keeps the commit-graph. It will create a commit.

![images (3).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627725038239/KRKSrIYIN.png)

There are some commands:

`git status` - _Check the status of a repository._

`git log` - _Check the commit history._

`git add <file name>` - _Add file to staging area._

`git commit -m "<message>"` - _Moves file from staging area to committed area._

`git restore --staged <file name>` - _Moves file from staging back to working area._

`git checkout <commit Hash>` - _Go back to the stage of working tree in a particular commit._

### Branching and Merging

Branching is a feature available in most modern _version control systems_. Instead of copying files from directory to directory, Git stores a branch as a reference to a commit. In this sense, a branch represents the tip of a series of commits. Branching facilitates the development of bug fixes.

Merging Branches. Once you've completed work on your branch, it is time to merge it into the main branch. Merging takes your branch changes and implements them into the main branch. Depending on the commit history, Git performs merges two ways: fast-forward and three-way merge.

![download (5).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627725872868/VAO9_Xc6C.png) ![download (6).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627725887761/ekxu8FHFi.png)

We have some commands:

`git branch <branchName>` - _Creates a new branch._

`git checkout <branchName>` - _Switches to the specific branch._

`git merge <branchName>` - _Merges the given branch into current branch._

`git branch -d <branchName>` - _Deletes the given branch._

`git branch -b <branchName>` - _Creates and switches to the new branch._

### Collaborating via GitHub

**GitHub** is a cloud-based hosting service that lets you manage Git repositories and helps people solve problems by building software together. _GitHub is moisture data sharing._ If you have open-source projects that use Git, then GitHub is designed to help you better manage them. GitHub allows multiple people to work on the same project/issue and everyone can get a copy of the project file without disturbing the original copy. So that everyone can add their own data and collaborate all at the end by pull request.

Collaborators on a personal repository can pull (read) the contents of the repository and push (write) changes to the repository. In a private repository, repository owners can only grant write access to collaborators. Collaborators can't have read-only access to repositories owned by a user account.

![28.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627731341022/fSOuyBjpd.png)

`git clone <remote URL>` - _Clones makes a new copy of a remote repo to our local machine._

`git fetch origin` - _Downloads all changes from origin remote repo to local._

`git push origin <branchName>` - _Uploads all changes from the local branch to the remote branch._

`git pull origin <branchName>` - _Downloads all changes from the remote branch to the local branch._

> Thanks for reading! Also, if you liked this article, be sure to ❤ it.

# Happy Coding!
