# Version Control Assignment 1 - DevOps

## Project Overview  
This project demonstrates the usage of **Subversion (SVN), Mercurial (HG), and Git** as version control systems. It includes step-by-step execution of commands along with explanations and screenshots.  
The assignment is also hosted on **GitHub Pages** for easy access.  

---

## 📂 Contents of the Repository  
This repository contains the following files:  
- `suhani_500105647_assignment1_devops.pdf` - Detailed documentation with commands, explanations, and screenshots.  
- `README.md` - This file, explaining the project structure and usage.  

---

## 📌 Demonstration of Version Control Systems  

### **🔹 Subversion (SVN) Commands**  
```sh
svnadmin create my_svn_repo
svn checkout file:///path/to/my_svn_repo my_working_copy
cd my_working_copy
echo "Hello SVN" > file.txt
svn add file.txt
svn commit -m "Initial commit"
svn log
