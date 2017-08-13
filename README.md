# Working directory
- Area where all our files and directories and changes are living all the time
- (Git init)

# Staging Area
- Files and directories that we explicitly add to the staging area
- (Git Add <file>)

# Git Repository
- Where all out snapshots are stored
- (Git Commit -m "Message here")



# Adding multiple files of a certain type
git add *.html

# Adding all files in directory (including hidden)
git add -A

# Removing files from staging area
git reset HEAD <file>

# Ignoring files 
.gitignore (file) and add the files into the file