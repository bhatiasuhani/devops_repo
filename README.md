🔹 Project Overview
This repository demonstrates the usage of Subversion (SVN) and Mercurial (hg) version control systems. It also includes a Git-based GitHub Pages setup to host the presentation/report.

🛠️ Version Control Tools Covered:
Subversion (SVN)
Mercurial (hg)
Git & GitHub Pages
📂 Repository Structure
bash
Copy
Edit
devops_repo/
│-- .git/                  # Git repository
│-- index.html             # Home page for GitHub Pages
│-- README.md              # Documentation file
│-- docs/                  # (Optional) Additional documentation
│-- SVN/                   # SVN demo files
│-- Mercurial/             # Mercurial demo files
│-- presentation/          # Project report & slides
🔹 GitHub Pages Deployment
This repository is hosted using GitHub Pages.

📌 Live URL: https://bhatiasuhani.github.io/devops_repo/

🚀 How GitHub Pages Was Configured
Enabled GitHub Pages in the repository settings.
Selected Deploy from a branch → main branch → /(root) folder.
Pushed the index.html file to the main branch.
Verified the site is live at the above URL.
🔹 Subversion (SVN) Usage
1️⃣ SVN Setup & Checkout
sh
Copy
Edit
svnadmin create my_svn_repo
svn checkout file:///path/to/my_svn_repo my_local_copy
2️⃣ SVN Add & Commit
sh
Copy
Edit
svn add filename
svn commit -m "Initial commit"
3️⃣ SVN Update & Status
sh
Copy
Edit
svn update
svn status
🔹 Mercurial (Hg) Usage
1️⃣ Initialize & Clone Repository
sh
Copy
Edit
hg init my_hg_repo
hg clone https://example.com/my_repo
2️⃣ Add & Commit Changes
sh
Copy
Edit
hg add filename
hg commit -m "Initial commit"
3️⃣ Push Changes to Remote
sh
Copy
Edit
hg push https://example.com/my_repo
🔹 Git Workflow
1️⃣ Initialize Repository
sh
Copy
Edit
git init
git remote add origin https://github.com/bhatiasuhani/devops_repo.git
2️⃣ Add & Commit Changes
sh
Copy
Edit
git add .
git commit -m "Initial commit"
3️⃣ Push to GitHub
sh
Copy
Edit
git push origin main
📌 Conclusion
This repository serves as a reference for SVN, Mercurial, and Git. It also demonstrates hosting documentation on GitHub Pages.

🚀 Live Site: GitHub Pages Link

✅ Happy Coding! 😊


