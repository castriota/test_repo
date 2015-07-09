# 1 - Command Line Interface

CLI - Win: Git Bash; Mac/Linus: Terminal

root directory: "/"
home directory: "~"
working directory: the one you are in.

pwd: print working directory

command flags arguments
[pwd] [no flags] [no arguments]

clear [back to initial prompt]

ls [list files in current directory]

ls -a [hidden and unhidden files (start with "."]

ls -al [hidden and unhidden files AND folders]

(-a and -al are both flags)

cd [change directory] takes to home directory.
cd .. [one level above]
cd Music/Debussry goes to this dir.
cd .. [moves to Users/castriota/Music]

mkdir [make directory]

touch [creates empty file]

cp [copy]
cp test_file Documents [copy test_files to Documents]

cp -r [copy contents of the entire folder]
mkdir More_docs
cp -r Documents More_docs [moves everything in Docs to More_docs]

rm [remove]
rm test_file
rm -r [remove everything in directory; there is no undo!]

mv [move or rename]
mv new_file renamed_file

echo [print out contents of a particular variable]
date [prints the date]


# 2 - Git 

Version control [records changes that you can recall] :: wikipedia [revision control]

Downloading and setting username and usermail in Git Bash.
Now moving to Git Hub.

# 3 - GitHub

Social (learning) aspect: users can share and contribute to each other's projects.

# 4- Creatinh GitHub Repository (repo)

Fork - creates a Fork of the repo 

can clone it:
git clone (url)
then you can contribute and hope they make your suggested changes

# 5 Basic Git Commands

Adding: [let Git know that the files you are adding under version control need to be tracked]
git add . [add new files]
git add -u [updates tracking for files that changed names]
git add -A [both of the previous]


Committing [you have chanves you wanna commit to be saved as intermediate version]
git commit -m "message" ["description of what I did"] :: only updates local repo (on GitBash) not remote (on GitHub)

Pushing [to Github]
git push

Branches [version used by many other people; use this so you don't mess with their work]
git checkout -b branchname [create a new branch]
git branch [see what branch you are on]
git checkout master [switch back to master]

Pull requests [GitHub feature; this will merge changes into the other branch/repo]
Click on "Compare Pull Request" [to the individual that owns the branch/repo]

-- Where to start learning:
1) if you don't have any idea of what you're doing:
git-scm.com/doc
help.github.com

2) if you have
google or stackoverflow

#6 Basic Markdown [text file formated in a very simple way so it can be recognized later]

README.md [this md is markdown]

Syntax:

using ## you have a larger bold text, indicating it is a secondary reading.
using ### you have a smaller text, indicating it is a tertiary reading.

creating lists using *

[links in this video for Introduction to Markdown and R Markdown]

# 7 Installing R packages

Downlaod R in CRAN [Comprehensive R Archive Network]: basic R system.
But there are R packages being developed by larger R community.

Obtaining info about available packages:
a <- available.packages() [there are currently 5200 packages] - use Task Views link.
head (rownames(a), 3)  [show the first three new packages by alfabetical order]

install.packages("package-name")
install.packages(c("pack1", "pack2", "pack3"))

in RStudio: Tools/Install Packages

Loading packages
library(package-name) [don't use ""]

after that, use the search() function to see all functions that are part of the package.

# 8 Rtools for Windows













