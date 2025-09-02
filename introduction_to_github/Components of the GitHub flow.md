# Guide to Branches, Commits, and Pull Requests on GitHub

## What are Branches?

Branches are like separate workspaces in your project. They let you **try new things or fix problems** without changing the main project (called the default branch).

- Your branch is a safe place to work.
- You can fix mistakes or add more changes anytime.
- Your work only goes to the main project after you say it's ready (by merging).
  

## What are Commits?

A commit is like a **snapshot of your changes** to one or more files.

- Every commit has a unique ID, time, and author.
- It tracks what you changed so people can see the history.
- You can create a commit with this command:

### git commit -m “Describe your change here”


### File Status in Git

- **Untracked:** New files not yet saved in the project.
- **Tracked:** Files that Git watches. They can be:
- Unmodified (no change)
- Modified (changed but not saved yet)
- Staged (ready to save)
- Committed (saved)

This helps keep track of what you've done.


## What are Pull Requests?

Pull requests ask others to check your changes before adding them to the main project.

- You open a pull request to say, "**Please review my work.**"
- Team members can comment, suggest edits, or approve.
- Once approved, your changes merge into the main branch.
- You can also open a **Draft Pull Request** if your work isn’t finished yet.


## How GitHub Flow Works (Simple Steps)

1. Create a new branch for your work.
2. Make your changes in the branch.
3. Open a pull request to get feedback.
4. Update your branch if needed after reviews.
5. Merge the pull request into the main branch when ready.
6. Delete the branch to keep things clean.

## What is Git Flow?

Git flow is a way to organize bigger projects with different branches for features, releases, and emergency fixes.

- **master:** The final production-ready code.
- **develop:** The place for new work on the next release.
- **feature/…:** Branches for adding new features.
- **release/…:** Preparing the next official version.
- **hotfix/…:** Quick fixes for problems in production.

### How Git Flow Works

- Make features in **feature** branches from **develop**.
- When ready for release, create a **release** branch from **develop**.
- Fix bugs on the release branch, but no new features.
- Merge release branch into **master** (and tag the version).
- Also merge release back into **develop** to stay updated.
- Fix production bugs with **hotfix** branches branched from **master**, merged back into **master** and **develop** after fix.


### When to Use Git Flow

- Good for planned releases.
- Useful if you maintain multiple versions.
- Good for slower, more controlled projects.

---

This simple guide helps understand basic GitHub workflows that keep your code organized and your team working together smoothly!

