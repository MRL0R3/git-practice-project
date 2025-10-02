# 📘 Git Practice Project






### 1) Clone the repository
```bash
git clone https://github.com/<YourOrg>/git-practice-project.git
cd git-practice-project
```

### 2) Create your own branch
Each student must create a branch with their own name.

```bash
git checkout -b feature/<student-name>
```

🔹 Example:
```bash
git checkout -b feature/ali
```

### 3) Add your student info file
Inside the `students/` folder, create a new markdown file with your name in English.  
For example: `students/ali.md`

Inside the file, include the following:

```markdown
# Student Info
Name: Ali Ahmadi  
ID: 12345678  

## My Git Command
`git branch` → used to create or list branches.
```

### 4) Commit and push your changes
```bash
git add students/ali.md
git commit -m "feat(student): add Ali Ahmadi info"
git push origin feature/ali
```

### 5) Create a Pull Request
- Go to the GitHub repository page.  
- Create a Pull Request from your branch (`feature/ali`) into the `develop` branch.  

PR Title Example:
```
Add student Ali Ahmadi info
```

PR Description Example:
```
Added my student information file (ali.md) inside the students/ folder.
```

---

## ✅ Project Rules
- Students must only make changes inside the `students/` folder.  
- Commit messages should follow this format:
  ```
  feat(student): add <Your Name> info
  ```
- All changes must be done in a separate branch (`feature/<name>`).  
- After submitting a PR, wait for review by **Ahmad** or **Matin**.  

---

## 🔎 Review Process
- Ahmad and Matin will review your changes.  
- If there are issues, comments will be added to your PR.  
- Make corrections and push updates to your branch.  
- Once everything looks good, your PR will be merged.  

---

## 🏆 Expected Learning Outcomes
By completing this project, students will practice and understand:
- `git clone`  
- `git branch`  
- `git add / commit`  
- `git push`  
- Pull Requests in GitHub  
- How to track changes and collaborate in a real-world Git workflow

---

## 📁 Repository Structure
```
git-practice-project/
├── README.md
├── students/        # Folder where each student adds their info file
└── develop.txt      # Placeholder for develop branch
```
