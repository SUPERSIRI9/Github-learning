# Overview of Code Scanning on GitHub 🔍

Code scanning helps find bugs and security problems in your code automatically.

---

## How It Works

- Scanning tools analyze your code and create **SARIF files** with results.
- GitHub shows these results as **alerts** in your repository.
- You can upload SARIF files from other tools or run scans directly on GitHub.

---

## Ways to Upload SARIF Files

1. **Code Scanning API**  
   Upload and get scan results using GitHub’s API.

2. **CodeQL CLI**  
   A tool that analyzes code and creates SARIF files to upload.

3. **GitHub Actions Workflow**  
   Automate scanning and upload SARIF results using a workflow file.

---

## Important Tips

- GitHub uses fingerprints to avoid showing duplicate alerts.  
- SARIF files should be under 10 MB and contain less than 5,000 results.  
- Focus scans on important rules if results are too large.  

---

Using code scanning keeps your code safe and helps catch issues early! 🚀
