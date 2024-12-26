# Guide to Creating a New Repository on GitHub Using Terminal in VS Code

# Guide 1

## Prerequisites
- Visual Studio Code installed
- Git installed
- GitHub account

## Steps

1. **Open Terminal in VS Code**
   - Open your project folder in VS Code.
   - Open the terminal by navigating to `View > Terminal` or using the shortcut `` Ctrl+` ``.

2. **Initialize a New Git Repository**
   ```sh
   git init
   ```

3. **Add Files to the Repository**
   ```sh
   git add .
   ```

4. **Commit the Files**
   ```sh
   git commit -m "Initial commit"
   ```

5. **Create a New Repository on GitHub**
   - Go to [GitHub](https://github.com) and log in.
   - Click on the `+` icon in the top right corner and select `New repository`.
   - Fill in the repository name and other details, then click `Create repository`.

6. **Add the Remote Repository**
   ```sh
   git remote add origin https://github.com/your-username/your-repository.git
   ```

7. **Push the Changes to GitHub**
   ```sh
   git push -u origin master
   ```

You have successfully created a new repository on GitHub and pushed your local files using the terminal in VS Code.

# Creating a GitHub Repository Using the Command Line in VS Code

# Guide 2

Follow these steps to create a new GitHub repository using the command line in Visual Studio Code:

## Prerequisites
- Ensure you have [Git](https://git-scm.com/) installed on your machine.
- Ensure you have [Visual Studio Code](https://code.visualstudio.com/) installed.
- Ensure you have a GitHub account.

## Steps

1. **Open Visual Studio Code**:
   Open your Visual Studio Code editor.

2. **Open Terminal**:
   Open the integrated terminal in VS Code by navigating to `View > Terminal` or using the shortcut `` Ctrl+` ``.

3. **Navigate to Your Project Directory**:
   Use the `cd` command to navigate to the directory where you want to initialize your repository.
   ```sh
   cd /path/to/your/project
   ```

4. **Initialize a Git Repository**:
   Initialize a new Git repository in your project directory.
   ```sh
   git init
   ```

5. **Add Your Files**:
   Add all your project files to the repository.
   ```sh
   git add .
   ```

6. **Commit Your Changes**:
   Commit the added files with a commit message.
   ```sh
   git commit -m "Initial commit"
   ```

7. **Create a New Repository on GitHub**:
   Use the GitHub CLI to create a new repository on GitHub. If you don't have the GitHub CLI installed, you can install it from [here](https://cli.github.com/).
   ```sh
   gh repo create <repository-name> --public --source=. --remote=origin
   ```
   Replace `<repository-name>` with your desired repository name.

   > Note: If you opt not to proceed Step 7, you can just click the upload button found in the bottom left part of the VS Code once you commit your changes. In that instance, you will be asked to create whether a public or private repository. Follow the presented steps and then proceed to Step 8.

8. **Push Your Changes**:
   Push your local commits to the remote repository on GitHub.
   ```sh
   git push -u origin main
   ```

You have successfully created a new GitHub repository using the command line in Visual Studio Code and pushed your local project to GitHub.