# Create a repositoty clone on your local machine.

- step 1: Create a online repository.
    ```
    https://github.com/thevedprakash/Batch77-demo3.git

    or 
    
    <your repository>
    ```

- step 2: Clone this repository on your local machine.
    ```
	git clone https://github.com/thevedprakash/Batch77-demo3.git	

    or 

    git clone <your reopository>
    ```

- step-3: Move inside the cloned folder
    ```
    cd Batch77-demo3

    or 

    cd <your_folder_name>
    ```

- step-4: Add files or folders on your local repository.
          **Add or create files and folder here based on your work**
    ```
    git add . 

    or

    git add <filename>   
    ```
    To remove a file or folder use rm 
    ```
    git rm <filename>

    ```

- step-5: Check the status of files.
    ```
    git status
    ```
    **If there is any marking with red color add them explicitly.**

- step-6: Commit your changes locally.
    ```
    git commit -m "Change is committed."

    or 

    git commit -m "<your_comment>"
    ```
- step7: Push your changes to remote repository.
    ```
    git push -u origin master

    or 

    git push -u origin <branch_name>
    ```


** Common Error **

1.  I tried to run "git commit -m "first commit" and ran in to this error   

```
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

```

2. Error while pushing the changes.

```
git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/1994lily/MYFIRST.git'

```
- First check whether your branch name matches the remote branch name or not.
	- Manually verify
- Whether your origin is set or not.
	- git remote -v
- Search your error on google <your-error message> + stackoverflow
	- src refspec main does not match any + stackoverflow
	- Maybe you just need to commit. check whether you have commited or not.
```
** Credential Error**
```


