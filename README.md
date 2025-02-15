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

### **🔹 Subversion (SVN) Commands**  
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
