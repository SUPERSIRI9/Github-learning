# GitHub Code Scanning Setup ✨

GitHub code scanning helps you find **vulnerabilities** and **errors** in your project automatically. 

---

## What is Code Scanning? 🔍

- Automatically checks your code for problems.
- Helps catch bugs and security risks early.
- Can be run by GitHub, GitHub Actions, or your CI system.

---

## Basic Setup Steps ⚙️

1. **Choose setup: Default or Advanced**
   - Default: Easy, automatic setup.
   - Advanced: You can customize how and when scans run.

2. **Workflows**
   - Stored in `.github/workflows` folder.
   - The default file for CodeQL scanning is `codeql-analysis.yml`.

---

## When Does GitHub Scan Your Code? ⏰

### Scan on Push 🚀
- Scans run every time code is pushed to default or protected branches.
- Results show in the Security tab.
- Alerts appear on related pull requests if applicable.

### Scan on Pull Request (PR) 🔃
- Scans run when a pull request is opened against the default branch.
- Shows alerts in PR checks.
- Works best if merging the PR commit is scanned (merge commit).

### Scheduled Scans 📅
- Scans can run regularly on a defined schedule.
- By default, weekly scans run on a random day/time.
- You can change the schedule by editing the workflow file.

---

## Customizing Scan Frequency and Scope 🔧

- Edit the workflow `.yml` file to set:
  - **When** to scan (`push`, `pull_request`, `schedule`)
  - **Which branches** to scan
  - **Which files** to include/exclude (e.g., skip `.md` or `.txt` files)


---

## Define Severity Levels for PR Failures 🚨

- By default, only alerts with **Error**, or **Critical/High** severity levels block PR merges.
- You can change this setting in repository **Settings > Code security and analysis**.
- Adjust which severities cause PR check failures.

---

## Summary Flow 🛠️

Start ↓ Choose Setup → Default or Advanced ↓ Commit workflow file to `.github/workflows` ↓ Scan triggers on:
	•	Push to branches 🚀
	•	Pull Requests 🔃
	•	Scheduled times 📅 ↓ Alert shown in:
	•	Security tab
	•	Pull Request checks ↓ Review and fix alerts ↓ Merge code safely ✔️


---

## Remember

- Adjust scan frequency to balance speed and coverage.
- Scan results help maintain code quality and security.
- You can customize scan triggers and severity rules anytime.



