# Spoon-Knife

> A practice repository for learning the GitHub fork & pull request workflow.

This repo exists for one purpose: give you a safe place to practice the core GitHub collaboration loop — **fork → clone → edit → push → pull request** — without worrying about breaking anything.

---

## Prerequisites

Before you start, make sure you have:

- A [GitHub account](https://github.com/signup) (free)
- [Git](https://git-scm.com/downloads) installed on your machine
- A terminal / command prompt you're comfortable opening

That's it. No special languages or frameworks needed.

---

## Step-by-Step Guide

### 1. Fork this repository

A **fork** is your personal copy of someone else's repo, hosted on your GitHub account. Changes you make to your fork don't affect the original.

1. Click the **Fork** button in the top-right corner of this page.
2. GitHub creates `your-username/Spoon-Knife` under your account.
3. You're now on your fork — notice the URL changed.

---

### 2. Clone your fork locally

**Cloning** downloads your fork to your computer so you can edit files with your normal tools.

```bash
git clone https://github.com/YOUR-USERNAME/Spoon-Knife.git
cd Spoon-Knife
```

Replace `YOUR-USERNAME` with your actual GitHub username.

---

### 3. Create a branch

Always make changes on a **branch**, not directly on `main`. This keeps your main branch clean.

```bash
git checkout -b my-first-branch
```

You're now on a new branch called `my-first-branch`.

---

### 4. Make a change

Open `index.html` in any text editor and make a small edit — add a line, change some text, anything you like.

---

### 5. Stage and commit your change

**Staging** tells Git which changes to include in the next snapshot. **Committing** saves that snapshot with a message.

```bash
git add index.html
git commit -m "My first commit: updated index.html"
```

---

### 6. Push your branch to GitHub

Uploading your local branch back to your fork on GitHub:

```bash
git push origin my-first-branch
```

---

### 7. Open a Pull Request

A **pull request (PR)** is how you propose your changes to the original repo. It lets maintainers review, discuss, and merge your work.

1. Go to your fork on GitHub (`github.com/YOUR-USERNAME/Spoon-Knife`).
2. Click the **"Compare & pull request"** banner that appears after your push.
3. Add a title and description explaining what you changed.
4. Click **"Create pull request"**.

The original repo owner can now review your PR. For this practice repo, your PR will stay open indefinitely — that's fine.

---

## Glossary

| Term | What it means |
|---|---|
| **Repository (repo)** | A project folder tracked by Git — contains all files and their history |
| **Fork** | Your personal copy of someone else's repository, living on your GitHub account |
| **Clone** | Downloading a repository from GitHub to your local machine |
| **Branch** | An isolated line of work inside a repo — changes on one branch don't affect others until merged |
| **Commit** | A saved snapshot of your changes, with a message describing what you did |
| **Push** | Uploading your local commits to GitHub |
| **Pull Request (PR)** | A proposal to merge your branch's changes into another branch (usually `main`) |
| **Merge** | Combining one branch's changes into another |
| **Upstream** | The original repository your fork was created from |

---

## What's Next

Now that you've got the basics, here's where to go deeper:

- [GitHub Skills](https://skills.github.com/) — free interactive courses built by GitHub
- [GitHub Docs: Forking a repo](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) — official deep dive on forks
- [GitHub Docs: Creating a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) — everything about PRs
- [Git Handbook](https://guides.github.com/introduction/git-handbook/) — core Git concepts explained simply
- [GitHub Flow](https://docs.github.com/en/get-started/quickstart/github-flow) — the branch-based workflow used by most open source projects

Happy coding! :sparkles:
