# To get Git going use COMMAND: git init
- to initialize git (to get git going) inside of whatever directory we are inside of. 
# Working Directory - 
- area where all of our files, directories and changes are living all the time.  This is where everything that is not saved, that we are 
  creating or working on lives.

# Staging Area- for if we explicitely want to track something - First area we add files to.
- Files and directories that we explicitly ADD to the staging area, files we are still working on (kindof a limbo where between the working 
  directory where we constantly add things, and then when we know we have what we want, we "commit" them to the git repository.) To add file 
  to Staging Area:
  1st COMMAND: git status
  2nd COMMAND: git add 'filename and type' - will get us from the working directory to this - the Staging Area

# Git Repository: COMMAND: git commit -m 'with short message in quotes in present tense about commit'
- where all our snapshots are stored COMMAND:  git commit -m "Add short brief message about what you are committing in present tense"

# Add multiple files of a certain type: COMMAND: git add *.html

# Adding all files in a directory (including hidden): COMMAND: git add -A . Then just git commit -m "Add all files" 
- git add -A adds all files and folders from the directory. This is a good command for adding everything in your project all at one time.
  Then just git commit -m "Add all files"

# Removing Files from the Staging Area: COMMAND: git reset HEAD and filename and type

# Ignoring Files
- create new file named 'gitignore'.  Any files you want git to ignore, add to that file by typing the file name and type into the
  gitignore file.  The gitignore file does not have a file type.

# Git Branches:  Branches allow us to mess around with our code and change things and not affect our original code (master branch).

- Listing all branches: COMMAND: git branch

- Adding a branch: COMMAND: git checkout -b <file_name>

- Changing branches: COMMAND: git checkout <branch_name>

- Merging a branch: COMMAND: git merge <branch_name>

- Removing a branch: COMMAND: git branch -d <branch_name>


