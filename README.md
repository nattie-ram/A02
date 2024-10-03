# Tutorial for Git, WebStorm, and GitHub 

## Part One: Directions on Using WebStorm with Git and Github 
  ### Step One: Install WebStorm 
  1. Visit :-> https://www.jetbrains.com/webstorm/download
  2. Choose the appropriate version for your operating system (Windows, macOS, or Linux)
  3. Follow the installation wizard to complete the setup.

### Step Two: Install Git 
1. Visit :-> https://git-scm.com/download
2. Download the correct version based on your operating system
3. Follow the installation wizard and confirm Git is installed by running "git --version" in the terminal

### Step Three: Set up GitHub Account 
1. Go to :-> https://github.com/
2. If you don't have an account, sign up for free.
3. After signing in, create a new repository by clicking the "+" icon in the top-right corner and selecting "New Repository" 

### Step Four: Set up Git in Webstorm
1. Open WebStorm and go to " File > Settings > Version Control > Git "
2. Ensure the path to the Git executable is correctly set (you can find it by running "which get" on Mac/Linus or "where git" on Windows in the terminal.)
3. Apply the setting and click OK.

### Step Five: Clone a GitHub Repository in WebStorm 
1. In WebStorm, go to "VCS > Get from Version Control "
2. Copy the repository URL from GitHub ( the HTTPS or SSH link ) and paste it into the "URL" field in WebStorm
3. Choose a directory where you want to clone the repository
4. Click "Clone" to download the repository locally.

### Step Six: Creating a New Branch 
1. In WebStorm, go to " VCS > Git > New Branch "
2. Name the branch
3. You have now created a branch to work on without affecting the main codebase.

### Step Seven: Making Changes and Committing 
1. Make your code changes in WebStorm
2. Go to "VCS > Commit " or click the Git icon in the bottom-right corner.
3. Add a commit message describing the change, such as " Task: Update README with tutorial instructions."
4. Click "Commit"

### Step Eight: Pushing Changes to GitHub 
1. After committing changes, click on " VCS > GIT > Push " or the push button in the bottom right.
2. This will push the changes from your local branch to the remote repository on GitHub.

### Step Nine: Pulling Updates from GitHub
1. If someone else has made changes to the repository, you need to pull the latest changes.
2. Go to " VCS > Git > Pull "
3. The latest updates from the remote repository will be fetched and merged into your local code.

### Step Ten: Handling Merge Conflicts 
1. If there are any merge conflicts ( when Git can't automatically combine changes from two branches), WebStorm will highlight the conflicts
2. Resolve the conflict by reviewing the changes and choosing which version to keep.
3. Commit the resolved files once the conflict is handled 

## Part Two 
- **Branch:** A parallel version of the repository, created to work on different features without affecting the main codebase.
- **Clone:** A copy of a GitHub repository that is downloaded to your local machine.
- **Commit:** A record of changes made to the repository, with a message describing the update.
- **Fetch:** Downloads updates from a remote repository without integrating them into your local code.
- **GIT:** A version control system used to track changes in source code during software development.
- **Github:** A platform for hosting and managing Git repositories online, providing features like collaboration and code review.
- **Merge:** Combining changes from one branch into another.
- **Merge Conflict:** Occurs when changes in different branches cannot be automatically combined and need manual resolution.
- **Push:** Sending your local repository updates to the remote repository on GitHub.
- **Pull:** Fetching and integrating changes from a remote repository into your local copy.
- **Remote:** The online repository hosted on a platform like GitHub.
- **Repository:** A storage location for code and version history, either local or on a remote platform like GitHub.

## References 
- Git Documentation :-> https://git-scm.com/doc
- GitHub Documentation :-> https://docs.github.com/en
- WebStrom Documentation :-> https://www.jetbrains.com/help/webstorm/ 


  
 






