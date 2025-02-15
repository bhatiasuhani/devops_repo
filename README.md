# Version Control Assignment 1 - DevOps

## 📌 Project Overview
This project demonstrates the usage of **Subversion (SVN), Mercurial (HG), and Git** as version control systems.
It includes step-by-step execution of commands along with explanations and screenshots.

The assignment is also hosted on **GitHub Pages** for easy access.

---

## 📂 Contents of the Repository
This repository contains the following files:

- 📄 `Suhani_500105647_assignment1_devops.pdf` - Detailed documentation with commands, explanations, and screenshots.
- 📜 `README.md` - This file, explaining the project structure and usage.

---

## 🚀 Demonstration of Version Control Systems

### 🔹 Subversion (SVN) Commands
Below are the essential SVN commands used in this assignment:

```sh
# Step 1: Create a new SVN repository
svnadmin create my_svn_repo

# Step 2: Checkout the repository to start working
svn checkout file:///path/to/my_svn_repo my_working_copy
cd my_working_copy

# Step 3: Create a file and add it to version control
echo "Hello SVN" > file.txt
svn add file.txt

# Step 4: Commit the changes
svn commit -m "Initial commit"

# Step 5: View commit history
svn log

# Step 6: Check the status of working directory
svn status

# Step 7: Get repository details
svn info
```

---

### 🔹 Mercurial (HG) Commands
Below are the commands used for Mercurial version control:

```sh
# Step 1: Initialize a new Mercurial repository  
hg init my_hg_repo  
cd my_hg_repo  

# Step 2: Create a file and add it to version control  
echo "Hello Mercurial" > file.txt  
hg add file.txt  

# Step 3: Commit the changes  
hg commit -m "Initial commit"  

# Step 4: View commit history  
hg log  

# Step 5: Check repository status  
hg status  

# Step 6: Get repository details  
hg summary  
```

---

### 🔹 Git Commands & GitHub Hosting
Below are the Git commands used for managing version control and hosting the repository on GitHub:

```sh
# Step 1: Initialize a new Git repository
git init  

# Step 2: Add files to the repository
git add README.md Suhani_500105647_assignment1_devops.pdf  

# Step 3: Commit the changes
git commit -m "Initial commit"  

# Step 4: Connect to GitHub repository
git remote add origin https://github.com/your-github-username/your-repo.git  

# Step 5: Rename the default branch to main
git branch -M main  

# Step 6: Push changes to GitHub
git push -u origin main  

# Step 7: View commit history
git log  

# Step 8: Check repository status
git status  

# Step 9: Get repository details
git remote -v  
```

---

## 🌐 Hosted GitHub Pages
The assignment is hosted on **GitHub Pages**.  
You can access the **PDF documentation here**.  

---

## 🎯 Conclusion
This assignment successfully demonstrates the usage of **Subversion (SVN), Mercurial (HG), and Git** for version control.  
The commands were executed, and the results were documented with screenshots.  

---

## 📌 Prepared By
👩‍💻 **Suhani Bhatia**  
🎓 **UPES Dehradun**  

---

## 📌 Submission To
👨‍🏫 **Mr. Prateek Raj Gautam**  
