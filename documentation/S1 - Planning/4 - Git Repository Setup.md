### **Initialize Local Git Repository and Map to Remote**
Prerequisite
- Github subscription (Credentials in 1Password)
- Github remote repository

#### **Step 1: Open Terminal in the Project Folder**
Navigate to the folder containing your project:
```bash
cd /path/to/your/local/LoadedDiceQuotesApp
```

#### **Step 2: Initialize Local Git Repository**
Run the following command to initialize Git:
```bash
git init
```

#### **Step 3: Stage All Files**
Add all project files to the Git staging area:
```bash
git add .
```

#### **Step 4: Commit the Files**
Create an initial commit with a message:
```bash
git commit -m "Initial commit"
```

#### **Step 5: Map to Remote Repository**
Link your local repository to the GitHub repository:
```bash
git remote add origin https://github.com/OluOrija/LoadedDiceQuotesApp.git
```

#### **Step 6: Push to GitHub**
Ensure the branch is named `main`:
```bash
git branch -M main
```
Push the changes to the remote repository:
```bash
git push -u origin main
```

#### **Step 7: Verify Setup**
1. Check repository status:
   ```bash
   git status
   ```
2. Confirm remote URL:
   ```bash
   git remote -v
   ```

---