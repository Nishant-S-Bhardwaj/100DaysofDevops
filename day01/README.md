# 🛠️ Day 01: Getting My Hands Dirty with Git & GitHub

## 📌 Overview

Today officially marked **Day 1 of my #100DaysOfDevOps journey**.

Before today, I thought Git was just a tool to back up my code to GitHub whenever I finished a project. My workflow was basically:

```bash
git add .
git commit -m "message"
git push
```

But after spending an entire day learning and practicing, I realized Git is much more than a backup tool. It's the foundation that allows developers to collaborate, track changes, and build software without creating chaos.

I divided my day into two parts:

* Learning Git and GitHub concepts.
* Practicing everything hands-on through KodeKloud Git Labs.

---

## 🧠 What I Learned

### 🌿 Feature Branching

One of the biggest takeaways was understanding why branches exist.

Instead of making changes directly on the main branch, developers create separate branches for new features, bug fixes, or experiments.

This helps in:

* Keeping production code safe.
* Working on multiple features simultaneously.
* Reviewing changes before merging them.

I finally understood why branching is such a critical part of modern software development.

---

### 🔄 Understanding the Git Workflow

I learned how code moves through different stages:

```text
Working Directory
        ↓
Staging Area (git add)
        ↓
Local Repository (git commit)
        ↓
Remote Repository (git push)
```

I also learned the purpose of:

* `git add`
* `git commit`
* `git push`
* `git pull`
* `git merge`

and how they fit together in a real-world workflow.

---

### ⚔️ Resolving Merge Conflicts

Merge conflicts always seemed scary.

Today I learned that they occur when multiple people modify the same section of code and Git cannot automatically decide which version to keep.

I practiced:

1. Identifying conflict markers.
2. Understanding both versions of the code.
3. Editing the file manually.
4. Removing conflict markers.
5. Completing the merge successfully.

What seemed intimidating at first turned out to be much easier once I understood the process.

---

### 🔍 Git Fetch vs Git Pull

This was one of the most useful concepts I learned today.

#### Git Pull

Downloads and immediately merges changes into the current branch.

```bash
git pull
```

#### Git Fetch

Downloads changes without modifying local files.

```bash
git fetch
```

I like thinking of `git fetch` as a safe reconnaissance mission—it lets me inspect incoming changes before deciding to merge them.

---

## 🚀 Learning Resources

To keep things structured, I followed:

* **Rahul Wagh's Git and GitHub: Beginner to Pro Course**

Instead of jumping between random tutorials, I focused on one resource and practiced every concept immediately after learning it.

This helped me understand the reasoning behind the commands instead of simply memorizing them.

---

## 💻 Hands-On Practice with KodeKloud Labs

Most of my learning happened inside the KodeKloud Git Labs environment.

### Repository Initialization

Created repositories from scratch and configured Git globally.

```bash
git init
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

### Branch Creation and Switching

Created feature branches and switched between them.

```bash
git checkout -b feature-branch
```

### Working with Remote Repositories

Connected local repositories to remote repositories and practiced synchronization.

```bash
git remote add origin <repository-url>
git push
git pull
```

### Merge Conflict Resolution

The labs intentionally introduced merge conflicts.

I manually:

* Opened the conflicted file.
* Examined the conflict markers.
* Selected the correct changes.
* Removed unnecessary markers.
* Staged and committed the resolution.

Successfully resolving the conflict was probably the most satisfying part of the day.

---

## 🎯 Day 01 Reflection

Today's goal wasn't just to learn Git commands.

It was to understand how developers collaborate, track changes, and safely build software together.

The biggest lesson I learned is:

> The best way to learn Git is to use it, break it, fix it, and repeat.

Looking forward to Day 02 and continuing this DevOps journey. 🚀

---

## 📚 Commands Practiced Today

```bash
git init
git status
git add .
git commit -m "message"
git log
git branch
git checkout -b <branch-name>
git merge <branch-name>
git fetch
git pull
git push
git remote add origin <repository-url>
```
