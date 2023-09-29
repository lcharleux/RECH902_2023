# RECH 902 2023-2024

## Setup

1. **Install Software**: 
    - **Install Git**: Begin by installing Git on your computer. You can download it from the official Git website (https://git-scm.com/).
    - **Install VScode**: To install Visual Studio Code, first, visit the official VSCode website (https://code.visualstudio.com/) and click on the "Download for [your operating system]" button. Choose the appropriate version for your computer (Windows, macOS, or Linux). Once the download is complete, run the installer and follow the on-screen instructions. After the installation is finished, you can launch VSCode from your application menu (on Linux), Start menu (on Windows), or Applications folder (on macOS). VSCode is now ready to use, and you can start coding in your favorite programming languages or editing LaTeX documents with its rich set of extensions and features.
    - **Install Anaconda**: To install the Anaconda Python distribution, first, visit the Anaconda website (https://www.anaconda.com/products/distribution) and download the Anaconda installer that matches your operating system (Windows, macOS, or Linux). Choose the version that corresponds to your Python preference (Python 3.x is recommended). Once the download is complete, run the installer and follow the installation instructions. You can choose to add Anaconda to your system's PATH during installation, which is a convenient option. After the installation is complete, you can open Anaconda Navigator or use the Anaconda command-line tools to manage Python environments and install packages. Anaconda provides a powerful environment for data science and scientific computing, making it a valuable tool for various programming and research tasks.

1. **Create a GIThub account**:

    1. **Visit the GitHub Website**:
    Open your web browser and go to the GitHub website by entering the following URL: https://github.com/.

    2. **Start Sign-Up Process**:
    On the GitHub homepage, you will see a "Sign up" button in the upper-right corner. Click on it to begin the registration process.

    3. **Enter Your Information**:
    You will be taken to the sign-up page, where you'll need to provide the following information:
    - **Username**: Choose a unique username that will be your GitHub identity. If the username is already taken, GitHub will prompt you to choose another.
    - **Email Address**: Enter a valid email address. This will be used for account-related notifications and password resets.
    - **Password**: Create a strong password for your account. GitHub will provide feedback on the password's strength.

    4. **Verify Your Email Address**:
    After providing your email and password, GitHub will send you a verification email to the address you provided. Open your email inbox and find the email from GitHub. Click on the verification link to confirm your email address.

    5. **Choose a Plan**:
    For most users, the free plan (GitHub Free) is sufficient. Select the free plan by clicking on the "Choose Free" button.



## Why GIT ?

Git is a version control system that is incredibly useful for students producing texts like source code or LaTeX documents. Here are some key reasons why:

1. **Version Control**: Git allows students to track changes to their documents over time. This is crucial when working on lengthy projects or collaborating with others. It keeps a history of every change made to the document, so you can always revert to a previous version if something goes wrong or if you want to see how the document evolved.

2. **Collaboration**: Git facilitates collaboration among students. Multiple students can work on the same document simultaneously, and Git helps manage and merge their changes. It prevents conflicts by allowing students to merge changes in an organized manner.

3. **Backup**: With Git, your documents are stored in a remote repository (e.g., GitHub, GitLab, Bitbucket). This serves as an off-site backup, ensuring that even if something happens to your local files (e.g., a computer crash), your work is safe and can be retrieved from the remote repository.

4. **Branching**: Git allows you to create branches, which are essentially separate lines of development. Students can create branches for different features or sections of their documents. This makes it easier to work on isolated parts of the document without affecting the rest of it.

5. **Annotations and Comments**: Git provides tools for adding comments and annotations to changes. This can be useful for providing feedback to peers or for keeping notes about why specific changes were made.

6. **Conflict Resolution**: When multiple students work on the same document, conflicts may arise when they try to merge their changes. Git provides tools to resolve these conflicts systematically and ensures that changes are integrated without data loss.

7. **Learning Tool**: Using Git introduces students to a valuable skill widely used in the software development industry. It's not just about version control but also about collaboration, communication, and structured document management.

8. **Portability**: Git is platform-independent, meaning it works on Windows, macOS, and Linux. Students can easily switch between different operating systems without worrying about compatibility issues.

9. **Branching Strategies**: Git encourages the use of branching strategies like Gitflow, which can help students organize their work and manage complex projects more effectively.

10. **Documentation and Commit Messages**: Git encourages good documentation practices. Students are encouraged to write clear and informative commit messages, which can serve as a log of changes made to the document.

In summary, Git is a powerful tool for students working on textual documents like source code or LaTeX files because it provides version control, collaboration, backup, and organizational benefits. It not only helps manage the document's history but also fosters good practices in project management and teamwork, which are valuable skills for students and professionals alike.

## Basic concepts

1. **Repository**:
   - Think of a repository as a project folder. It's where you store all your source code or LaTeX documents and their history.

2. **Commit**:
   - A commit is like taking a snapshot of your project at a particular point in time. When you commit changes, you're saving the current state of your documents.

3. **Branch**:
   - A branch is like a separate line of work. You can create branches to work on specific features or sections of your document without affecting the main version.

4. **Master (Main) Branch**:
   - The master branch (or main branch) is the primary branch of your project. It usually represents the stable, main version of your document.

5. **Clone**:
   - To clone a repository means to make a copy of it on your own computer. This allows you to work on your project locally.

6. **Pull/Pull Request**:
   - Pulling is like getting the latest updates from the remote repository. A pull request is a way to propose changes you've made in your branch to be merged into the main branch.

7. **Push**:
   - Pushing means sending your local commits to the remote repository. This is how you share your work with others or back it up online.

8. **Merge**:
   - Merging is combining changes from one branch (e.g., a feature branch) into another (e.g., the main branch). It's like integrating your work into the main document.

9. **Conflict**:
   - A conflict happens when Git can't automatically merge changes because they conflict with each other. You'll need to manually resolve these conflicts.

10. **Pull Down/Pull Upstream**:
    - Pulling down or pulling upstream means getting the latest changes from the remote repository into your local copy. It keeps your local version up to date with what others are working on.

11. **Commit Message**:
    - When you make a commit, it's a good practice to write a clear commit message explaining what you changed. This helps you and others understand the history of your project.

12. **Remote Repository**:
    - The remote repository is where your project is stored online (e.g., GitHub, GitLab). It's a backup and collaboration hub for your code or LaTeX documents.

13. **Fork** (for code):
    - In code projects, forking means creating your own copy of someone else's repository. You can make changes to your fork without affecting the original project.

14. **Latex Diff** (for LaTeX documents):
    - LaTeX diff tools show the differences between two versions of a LaTeX document. This can be helpful for tracking changes in LaTeX files.

Remember, Git can seem a bit complex at first, but with practice, it becomes a valuable tool for managing and collaborating on projects like source code and LaTeX documents. Start with the basics, and as you become more comfortable, you can explore more advanced Git features.

## Practical exercices

Learning Git can be a valuable skill for a student working with source code or LaTeX documents. Here are some key steps and things to do to start learning Git effectively:

2. **Set Up Your Identity**:
   - Configure your Git identity by setting your name and email address. This information is included in your commit messages.
   
        ```bash
        git config --global user.name "Your Name"
        git config --global user.email "your@email.com"
        ```

3. **Learn Basic Commands**:
   - Familiarize yourself with basic Git commands such as `git init`, `git clone`, `git add`, `git commit`, `git push`, and `git pull`. These are the fundamental operations you'll use most often.

4. **Create a GitHub Account (Optional)**:
   - If you're working on code, consider creating an account on GitHub (or a similar platform like GitLab or Bitbucket). These platforms make it easier to collaborate and share your work.

5. **Start a Simple Project**:
   - Begin with a simple project (e.g., a small source code project or a LaTeX document). Initialize a Git repository for it using `git init`.

6. **Make Commits Frequently**:
   - Get into the habit of making frequent and meaningful commits. Each commit should represent a logical change or addition to your project.

7. **Write Good Commit Messages**:
   - Write clear and concise commit messages that explain what you did in each commit. Follow a consistent format, such as "Add feature X" or "Fix issue Y."

8. **Learn Branching and Merging**:
   - Understand how branching works in Git. Create branches for different tasks or features. Practice merging branches into the main branch (usually called "master" or "main").

9. **Resolve Conflicts**:
   - Learn how to resolve merge conflicts, which occur when Git can't automatically merge changes. This is an essential skill for collaborative work.

10. **Explore Git Documentation and Tutorials**:
    - Git has extensive documentation and numerous tutorials available online. Explore these resources to deepen your understanding.

11. **Collaborate with Others**:
    - If possible, collaborate with classmates or colleagues on a Git project. Real-world experience working on a shared repository is invaluable.

12. **Use a Git GUI (Optional)**:
    - While learning the command-line interface is important, you can also use Git GUI tools like GitHub Desktop or Sourcetree to help you visualize and manage your Git repositories.

13. **Practice, Practice, Practice**:
    - Git proficiency comes with practice. Create, modify, and manage different repositories to gain hands-on experience.

14. **Troubleshoot Issues**:
    - Don't be discouraged by errors or issues. Git has a helpful error message system. When in doubt, search for solutions online or ask for help from more experienced Git users.

15. **Learn Advanced Git Features (Optional)**:
    - Once you're comfortable with the basics, explore more advanced Git features like rebasing, tagging, and stashing.

16. **Backup Your Work**:
    - Regularly push your work to a remote repository (e.g., GitHub) to ensure it's backed up and accessible from anywhere.

Remember that learning Git can take time, so be patient with yourself. Start with the basics, and as you become more confident, you can delve into more advanced Git concepts. 