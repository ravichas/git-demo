# git-demo

This repository is a **teaching sandbox** used for live demonstrations of Git and GitHub workflows.

It is intentionally reused, reset, and modified during class to illustrate how Git tracks changes over time.

---

## Purpose of this repository

This repository is used to demonstrate:

- Cloning a GitHub repository into Google Colab
- Creating directories and files inside a repository
- Staging, committing, and pushing changes
- Deleting directories and committing removals
- Understanding that Git tracks **changes**, not folders
- Working with an ephemeral environment (Google Colab) and a persistent remote (GitHub)

The contents of this repository may change frequently as part of live demos.

---

## Important note for students

> ⚠️ **This is NOT a project or assignment repository.**

- Do **not** rely on this repository for permanent files
- Do **not** submit work here
- Do **not** assume files will persist between classes

Students should use their **own GitHub repositories** for assignments and projects.

---

## Why files appear and disappear

Google Colab runs on a temporary virtual machine.  
Each class session starts from a clean environment, but GitHub retains the repository history.

As part of the demo, directories (such as `demos/`) may be:
- created
- modified
- deleted
- recreated

This is intentional and demonstrates how version control works.

---

## How to follow along in class

1. Clone this repository into Colab
2. Observe changes via `git status`
3. Watch how commits reflect additions and deletions
4. Practice the same workflow in your own repository

---

## Key takeaway

> GitHub reflects your **commit history**, not your local filesystem state.
