# 🚀 LazyVim Git Workflow Guide

---

## 🎯 Cloning the Repository

To start working with LazyVim, first, clone the repository:

```powershell
# Replace <repository-url> with the actual URL of the repository
git clone <repository-url>
cd lazyvim
```

---

## 🌱 Creating a New Branch

It's best practice to work on a separate branch:

```powershell
git checkout -b my-feature-branch
```

---

## ✏️ Making Changes

Edit files as needed using LazyVim.

To open LazyVim, simply run:

```powershell
nvim
```

Make necessary modifications and save them.

---

## 🔍 Checking Status & Staging Changes

Check what changes have been made:

```powershell
git status
```

Stage specific files or all changes:

```powershell
git add <file-name>

# OR

git add .
```

---

## 💾 Committing Changes

After staging the files, commit them with a descriptive message:

```powershell
git commit -m "feat: Add new feature description"
```

---

## 📤 Pushing Changes

Push the branch to the remote repository:

```powershell
git push origin my-feature-branch
```

---

## 🔀 Creating a Pull Request

1. Go to the repository on GitHub/GitLab.
2. Navigate to the **Pull Requests** tab.
3. Click **New Pull Request**.
4. Select your branch and describe your changes.
5. Submit the pull request for review.

---

## 🔄 Syncing with Upstream

If changes have been made to the main repository, sync your branch:

```powershell
git checkout main
git pull origin main
git checkout my-feature-branch
git merge main
```

---

## 🗑️ Deleting a Branch (Optional)

Once merged, you can delete your branch:

```powershell
git branch -d my-feature-branch
git push origin --delete my-feature-branch
```

---

✨ This workflow ensures an **organized and efficient** contribution process using **LazyVim and Git**! 🚀
