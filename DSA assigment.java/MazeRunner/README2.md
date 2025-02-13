 To  clone the file you need to open the terminal in either the editor or terminal and dirct the terminal to the empty folder 
then write this command in the terminal git clone <repo-url> where the repo-url is where you put the url of the repositry


To commit new code to a file in GitHub, follow these steps on Mac or Windows:

1. Navigate to Your Project Folder
Open Terminal (Mac) or Git Bash/Command Prompt (Windows) and go to your project folder:
cd /path/to/your/project

To see which files have changed:

git status



If your teammates want to **contribute** to the repository, follow these steps:

---



---

## **3. Pull the Latest Changes**
Before making changes, they should pull the latest updates:

git pull origin main  # or the relevant branch


---

## **4. Create a New Branch**
Each teammate should create their own branch to work on:

git checkout -b feature-branch


---

## **5. Add, Commit, and Push Changes**
Once they’ve made changes, they can commit and push:

git add .
git commit -m "Added new feature"
git push origin feature-branch


---

## **6. Create a Pull Request (PR)**
1. Go to **GitHub** → Open the repository.
2. Click on **"Pull Requests"** → **"New Pull Request"**.
3. Select **feature-branch** and compare it with **main**.
4. Click **"Create Pull Request"**, add a description, and request reviews.

---

## **7. Review & Merge Changes**
- The repository owner or a team member with **write access** reviews the PR.
- If everything looks good, they can **merge** it into `main` using:

  git checkout main
  git pull origin main
  git merge feature-branch
  git push origin main


---

## **8. Keep Repo Updated**
To avoid conflicts, teammates should always:

git pull origin main

before making new changes.

---

That’s it! Now your team can **collaborate smoothly** on GitHub! 🚀 Let me know if you need more help.

