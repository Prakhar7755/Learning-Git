Sure, here are the Git commands you would typically use to clone an open-source repository, make changes, and then propose those changes to the project maintainers:

1. **Clone the repository**: 
    - `git clone <repository_url>`: This command is used to clone (copy) a repository from GitHub onto your local machine.

2. **Create a new branch**:
    - `git checkout -b <branch_name>`: This command creates a new branch in the repository and switches to it.

3. **Make changes and commit**:
    - `git add .` or `git add <file_name>`: This command adds changes in the working directory to the staging area.
    - `git commit -m "<commit_message>"`: This command commits any files you've added with the `git add` command and also commits any files you've changed since then.

4. **Push changes to GitHub**:
    - `git push origin <branch_name>`: This command sends the committed changes of the branch to your remote repository.

5. **Open a Pull Request (PR)**:
    - At this point, you can navigate to your repository on GitHub and click the "Compare & pull request" button to open a new pull request.

6. **Update the PR as necessary**:
    - If the maintainers ask for changes, repeat steps 3 and 4 and the updates will automatically be added to your existing pull request.

7. **Once the PR is approved**:
    - The maintainers of the original repository will merge your proposed changes.

Remember, open source is all about collaboration. Always read the contributing guidelines for the project before making a pull request.