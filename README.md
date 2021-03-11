# Welcome!

This Readme file will give you the idea about how to upload your project from your local system to the GitHub using Git Bash.

## Following are the steps to get started:

1. **Create a new repository**: You can create it from homepage or by clicking on the **+** icon near the bell icon.

2. **Open Git Bash**: Open Git Bash in your project directory or change the current directory to the project directory.

3. **Initialize the project directory as the Git repo**:
   ```
   git init
   ```
4. **Add files to your repo**:
   ```
   git add .
   #This will add all your files to the local repo and will prepare them for being commit.
   ```
5. **Commit the files**:
   ```
   git commit -m "Your commit message here"
   #This will prepare the files to be pushed to the remote repo.
   ```
6. **Copy the Github's repo url**: You can find the url by clicking the get code button inside your repository. The color of the button is **green**.

7. **Use the repo url to specify where to push the project files**:
   ```
   git remote add origin <REPO URL>
   #This command simply sets the remote url
   git remote -v
   # This command simply verifies the url
   ```
8. **Push the changes made in the local repo to _GitHub_**:
   ```
   git push origin main
   ```

### I hope you enjoyed reading this _README_ for better understanding. If you liked it, give this repo a _star_

# THANKYOU 
