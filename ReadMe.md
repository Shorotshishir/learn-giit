# This is a Readme file

## How to Git
to initialize a git repository localy 
- create a directory
- open it in terminal 
- type the following
    ```
    git init
    ```
- to add a file to git system type
    ```
    git add name-of your file
    ```
- to add everything in a repository type
    ```
    git add .
    ```
- to make a commit type
    ```
    git commit -m "your-commit-message(keep-it-short)"
    ```
- your files are now under version control system. unless removed, this commit will store the a version of the files and their status of that perticular moment. versions are now saved locally.
- to store your files in git you need branches, you can have as many branch as u want, but generally there should be atleast one main branch. `git init` creates a main branch at initialization. 
- by default the initial branch is called `master` but github recommends to rename that branch to `main`
- to rename branch from `master` to `main` type
    ```
    git branch -M main
    ```

- you successfully added version control system for your directory and files in it.
## GitHub
- to store your version in github, create a repository in `GitHub` with the same name of your directory.
- after creation it will give you a git directory link that you can copy, copy that
- open the directory u want to store in terminal, and type
    ```
    git remote add origin paste-the-copied-link-here
    ```
- that will create a remote branch in `GitHub` inside your repository
- by default the initial branch is called `master` but github recommends to rename that branch to `main`
- to rename branch from `master` to `main` type
    ```
    git branch -M main
    ```
- Now to send it to you repository type
    ```
    git push -u origin main
    ```

- you are all done !
