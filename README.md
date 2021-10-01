# Simple-Web-Project
![](https://img.shields.io/badge/Hactoberfest-%202021-brightgreen)

This project aims to simplify and guide the way beginners make their first contribution to open source . 
If you are looking to make your first contribution. This repository is the right place to start.
## Prerequisites:
* Install git in your machine.
* Have basic command line experiance.

## Follow the given steps

1. Fork this repository 
   Click the button on top right corner labelled fork.
2. Clone this repository using the link into your local machine.
   On the forked repo click the green button labelled code and copy the https url.
   Once it is copied open the terminal/cmd and type in the following code
   ```
    git clone "http url you just copied"
    ```
    
3. Going to the required project directory

   ```
    cd Simple-web-Project
    ```
4. Create a branch
   The best practise is to create another branch work on it and finally merge it .
   So after changing to project directory ,to creata new branch type in the foll code.
   ```
    git checkout -b your_new_branch_name
    ```
    for example : 
    ```
    git checkout -b branch-2
    ``` 
5. Add the necessary contribution and commit those contributions.
    To add the necessary contrbution that will get you accepeted refer contributiion.md file.
    After making the changes type in the below command this command will let you know which files have been modified.
   ```
    git clone 
    ```
    Add those changes to the branch you just created using the below command.
     ```
    git add .
    ``` 
    Now commit those changes using the below command:
    
     ```
    git commiit -m "The changes that you done must be mentioned here"
    ```
<!--  
6. Merge the branch into the main branch -->

6. Push changes to github
    Push your changes using the below command:

    ```
    git push origin branch_name
    ```
    replace branch_name with the name of the branch you created earlier.
    
    For example:
    
    ```
    git push origin branch-2
    ```
7. Submit your changes for review
    If you go to your repository on GitHub, you'll see a Compare & pull request button. Click on that button.
    Then if you want to mention anything about the changes type it in and finally  submit the pull request.
