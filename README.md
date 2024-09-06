1. Initialize Git (if not done already)

If your local folder is not yet a Git repository, you need to initialize it.


`cd /path/to/your/local/folder`
`git init`

2. Add the Remote Repository

If you haven't added the remote repository (on GitHub) yet, you need to link your local repository to the remote one:


`git remote add origin https://github.com/your-username/your-repo-name.git`

Replace your-username and your-repo-name with your actual GitHub username and repository name.

3. Check Remote

Verify that the remote repository is correctly linked:

`git remote -v`

4. Stage the Files

To add all files in your local folder to the repository, run the following command:

`git add .`
This stages all the changes, including new files, for the next commit.

5. Commit the Changes

Commit the staged files with a meaningful message:

`git commit -m "Add initial files"`
6. Push to the GitHub Repository

To push the changes to your GitHub repository, use:

`git push origin master`
If you are working on a branch other than master, replace master with your branch name.
