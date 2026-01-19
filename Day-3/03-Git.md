# 🚀 Git Zero to Hero – Day 3

## 📌 What You Will Learn

- Git Add
- Staging Area
- Git Commit
- Git Log
- Git Branch (Basics)

---

## 📌 Step 1: Create a File

echo hello world > index.html

yaml
Copy code

### 🔍 What does this do?

- `echo hello world` → prints text
- `>` → creates a new file
- `index.html` → file name

📌 Result:

- A new file `index.html` is created
- Old content (if any) is replaced

---

## 📌 Step 2: Add File to Staging Area

git add .

### 🔍 What does `.` mean?

- `.` means **all files**
- It adds **all new and modified files** to staging area

📌 Simple meaning:

> “Git, please select all changes.”

---

## 📌 Step 3: Commit the Changes

git commit -m "this is file"

### 🔍 What is commit?

- Commit saves changes permanently
- `-m` means **message**
- Message explains what you did

📌 Think of commit as:

> “Save button with a note”

---

## 📌 Step 4: Check Commit History

git log

### 🔍 What does git log show?

- Commit ID
- Author
- Date
- Commit message

---

## 📌 Step 5: Short Commit History

git log --oneline

### 🔍 Why use this?

- Shows history in **one line**
- Easy to read
- Used very often

---

## 📌 Step 6: Modify File (Append Content)

echo hello world + hello Youtube >> index.html

### 🔍 Difference between `>` and `>>`

| Symbol | Meaning                      |
| ------ | ---------------------------- |
| `>`    | Replace old content          |
| `>>`   | Add content to existing file |

📌 Example:

- `>` → overwrite
- `>>` → append (add at end)

---

## 📌 Step 7: Check Branches

git branch

### 🔍 What does this do?

- Shows all available branches
- Current branch is marked with `*`

---

## 📌 Step 8: Create New Branch

git branch develop

### 🔍 What is a branch?

- Branch is a separate line of work
- Used for new features or testing
- Main code stays safe

📌 `develop` is commonly used for development work

---

## 📌 Step 9: Switch to Develop Branch

git switch develop

### 🔍 What does this do?

- Moves you to `develop` branch
- Now all work happens in this branch

---

## 📌 Step 10: Add & Commit in Develop Branch

git add .
git commit -m "add index.html file"

📌 Meaning:

- Changes are saved **only in develop branch**
- Main branch remains unchanged

---
