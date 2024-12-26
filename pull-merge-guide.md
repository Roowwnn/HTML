# Creating a Pull Request and Merging in GitHub

## Creating a Pull Request

1. **Ensure your branch is up to date**:
   ```sh
   git checkout main
   git pull origin main
   ```

2. **Create a new branch**:
   ```sh
   git checkout -b feature-branch
   ```

3. **Make your changes and commit them**:
   ```sh
   git add .
   git commit -m "Description of changes"
   ```

4. **Push your branch to GitHub**:
   ```sh
   git push origin feature-branch
   ```

5. **Create a Pull Request**:
   - Go to your repository on GitHub.
   - Click on the "Compare & pull request" button.
   - Add a title and description for your pull request.
   - Click "Create pull request".

## Merging a Pull Request

1. **Review the Pull Request**:
   - Ensure all checks have passed.
   - Review the code changes.

2. **Resolve any conflicts** (if any):
   - GitHub will indicate if there are any conflicts.
   - Click on "Resolve conflicts" button.
   - Edit the conflicted files to resolve conflicts.
   - Mark the conflicts as resolved and commit the changes.

3. **Merge the Pull Request**:
   - Click on the "Merge pull request" button.
   - Confirm the merge by clicking "Confirm merge".

4. **Delete the branch** (optional but recommended):
   - Click on the "Delete branch" button after the merge is complete.

## Syncing your local repository

1. **Switch to the main branch**:
   ```sh
   git checkout main
   ```

2. **Pull the latest changes**:
   ```sh
   git pull origin main
   ```

3. **Delete the local feature branch**:
   ```sh
   git branch -d feature-branch
   ```

By following these steps, you can create a pull request, resolve any conflicts, and merge it into the main branch using GitHub.