# sample
# this is for user readibility and to know about GIT basic operation
# # Initialize a new repository
git init

# Clone an existing repository
git clone <repo-url>

# Check repository status
git status

# Stage changes
git add <file>        # add specific file
git add .             # add all changes

# Commit changes
git commit -m "Your commit message"

# View commit history
git log

# Create and switch branches
git branch <branch-name>
git checkout <branch-name>
git checkout -b <new-branch-name>

# Merge branches
git merge <branch-name>

# Push changes to remote
git push origin <branch-name>

# Pull latest changes from remote
git pull origin <branch-name>

# Set remote repository
git remote add origin <repo-url>

# Remove a file from staging
git reset <file>

# Undo last commit (keep changes staged)
git reset --soft HEAD~1

# Undo last commit (discard changes)
git reset --hard HEAD~1
