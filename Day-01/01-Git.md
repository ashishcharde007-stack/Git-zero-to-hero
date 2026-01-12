# 🚀 Git Zero to Hero – Day 1

## 📌 What You Will Learn

- What is Version Control?
- Types of Version Control
- What is Git?
- Difference between Git and GitHub
- Git Three Pillars (Core Concept)
- Basic Git Commands Demo

---

## 🔹 What is Version Control?

Version Control is a system that helps us track changes in our code over time.

It allows us to:

- See who changed what
- Go back to older versions
- Work safely in a team
- Avoid breaking production code

### 📌 Example
If today’s code breaks, we can easily rollback to yesterday’s working version.

---

## 🔹 Types of Version Control

### 1️⃣ Centralized Version Control

- Single central server
- All developers connect to one place

❌ **Problems:**

- Server down → work stops
- Risk of data loss

📌 **Example:** SVN

---

### 2️⃣ Distributed Version Control

- Every developer has a full copy of the repository
- Works even offline

✅ **Advantages:**

- Faster
- More secure
- No single point of failure

📌 **Example:** Git

---

## 🔹 What is Git?

Git is a **Distributed Version Control System** used to track source code changes.

Git helps developers to:

- Track code history
- Work in parallel using branches
- Merge code safely
- Maintain stable production code

📌 Git works **locally** on your machine.

---

## 🔹 Git vs GitHub (Most Common Confusion)

| Git | GitHub |
|---|---|
| Version control tool | Online code hosting platform |
| Works offline | Requires internet |
| Installed on local system | Web-based service |
| Tracks code history | Stores Git repositories |

📌 **Easy way to remember:**

> Git is the engine, GitHub is the garage.

---

## 🔹 Git Three Pillars (Very Important Concept)

Git internally works with **three main areas**.

### 1️⃣ Working Directory

This is where you write or modify code.

**Example:**

```bash
echo new file > index.html
```

📌 The file is created but Git is **not tracking** it yet.

---

### 2️⃣ Staging Area

This is where you select changes that should go into the next commit.

**Example:**

```bash
git add .
```

📌 This tells Git:

> “These changes are ready to be saved.”

---

### 3️⃣ Repository (Commit History)

This is where changes are permanently stored with history.

**Example:**

```bash
git commit -m "this is new file"
```

📌 **Commit = Snapshot** of your project at that moment.

---

## 🔄 Git Flow Summary

**Working Directory → Staging Area → Repository**

Or in simple words:

> Code → Select → Save

---