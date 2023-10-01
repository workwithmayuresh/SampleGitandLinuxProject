# SampleGitandLinuxProject
This is to practice and demonstrate basic skills of Linux and Git .

Project Description :

**Overview:**

The Git Skills Test - Collaborative Text File project is a hands-on exercise designed to evaluate your proficiency with Git, the version control system widely used for collaborative software development. 

In this project, you will work with a simple text file, 
demonstrating your ability to create branches, make changes, resolve conflicts, and collaborate with others in a Git-based environment.



**Project Guidlines**

**Step 1: Repository Setup**

1. Create a new Git repository on Github .
   Once created navigate to the desired path and clone it to your local system

   ```bash
   mkdir my-git-project
   cd my-git-project
   ```

   ```bash
    git clone https://github.com/workwithmayuresh/SampleGitandLinuxProject.git

   ```



2. Create a shared shell script file named `shared-script.sh` in this directory and add some content to it.

   ```bash
   echo "#!/bin/bash" > shared-script.sh
   echo "echo 'Hello, world!'" >> shared-script.sh
   ```

3. Add the file to the Git repository and make an initial commit.

   ```bash
   git add shared-script.sh
   git commit -m "Initial commit - added shared-script.sh"
   ```

**Step 2: Collaborative Editing**

1. Create your branch.

   ```bash
   git checkout -b your-branch-name
   ```

2. Edit the `shared-script.sh` file with your changes. For example, you can modify the script to do something different or add new functionality.

3. Commit your changes with a meaningful commit message.

   ```bash
   git add shared-script.sh
   git commit -m "Implemented feature X in the script"
   ```

**Step 3: Branch Merging**

1. Switch back to the main branch.

   ```bash
   git checkout main
   ```

2. Merge your branch into the main branch.

   ```bash
   git merge your-branch-name
   ```

   If there are any conflicts, Git will prompt you to resolve them. Open the `shared-script.sh` file, resolve the conflicts, and then commit the changes.

**Step 4: Commit Messages**

Ensure that you provide detailed and meaningful commit messages for each of your commits, as shown in the previous steps.

**Step 5: Simulate Collaboration**

Invite other contributors to clone the repository and follow the same steps to create branches, make changes, and commit them.


