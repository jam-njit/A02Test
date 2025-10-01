# A02 — Git, WebStorm, and GitHub Tutorial

**Repository Link (replace with yours):**  
https://github.com/yourUCID/A02  

This tutorial explains how to use **GIT**, **WebStorm**, and **GitHub** together. It includes step-by-step directions, a glossary of important terms, and references.

---

## Part 1 — Directions on Using WebStorm

### 1. Install Required Tools
- Install **Git**: [https://git-scm.com/downloads](https://git-scm.com/downloads)  
- Install **WebStorm** (free for students): [https://www.jetbrains.com/webstorm/download/](https://www.jetbrains.com/webstorm/download/)  
- Create a **GitHub** account: [https://github.com/](https://github.com/)

---

### 2. Create Repository on GitHub
1. Log in to **GitHub**.  
2. Click **New Repository**.  
3. Name it `A02` (capital A is required).  
4. Select **Public** (or Private if allowed).  
5. Add a README file.  
6. Click **Create repository**.

---

### 3. Clone Repository into WebStorm
1. Open WebStorm → click **Get from VCS**.  
2. Copy your repository’s SSH or HTTPS URL from GitHub.  
   - Example: `git@github.com:yourUCID/A02.git`  
3. Paste it into WebStorm and click **Clone**.  

---

### 4. Edit README.md
1. In WebStorm’s Project panel, open `README.md`.  
2. Add your tutorial and glossary text.  
3. Save your changes.  

---

### 5. Commit and Push
1. In WebStorm, go to *VCS → Commit*.  
2. Write a **Commit** message (example: `Task: Create Repository`).  
3. Click **Commit and Push**.  
4. Your changes are now uploaded to **GitHub**.  

---

### 6. Updating Work
- To get the latest changes, use **Fetch** then **Pull**.  
- To share your changes, **Push** them.  
- To work on new features, create a **Branch**.  

---

## Part 2 — Glossary

- **Branch** — A parallel version of the project that allows you to work on new features without affecting the main code.  
- **Clone** — A local copy of a remote **Repository**, including its files and full history.  
- **Commit** — A saved snapshot of changes in **GIT**, usually with a short message describing what was done.  
- **Fetch** — Downloads information about new commits from a **Remote**, but does not change your local files.  
- **GIT** — A distributed version control system used to track and manage code changes.  
- **Github** — A cloud service for hosting **GIT** **Repositories** and collaborating with others.  
- **Merge** — The process of combining changes from one **Branch** into another.  
- **Merge Conflict** — A situation where **GIT** cannot automatically combine changes because the same part of a file was edited differently.  
- **Push** — Uploads your local **Commits** to a **Remote** **Repository**.  
- **Pull** — Downloads changes from a **Remote** and integrates them into your local **Repository**.  
- **Remote** — A reference to a **Repository** hosted on a server like **Github**.  
- **Repository** — A project’s database that stores files, history, and version tracking.  

---

## Example Commit Messages
- `Task: Create Repository`  
- `Feature: Add WebStorm setup directions`  
- `Docs: Add glossary definitions`  
- `Fix: Corrected spelling in README.md`  

---

## References
- Git — [Pro Git Book](https://git-scm.com/book)  
- GitHub Docs — [Hello World Tutorial](https://docs.github.com/en/get-started/quickstart/hello-world)  
- JetBrains — [Using Git in WebStorm](https://www.jetbrains.com/help/webstorm/using-git-integration.html)  
