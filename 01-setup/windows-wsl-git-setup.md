# Windows + WSL2 + Git Setup

## Completed
- Created CyberLab folders on Windows
- Confirmed WSL2 is installed
- Confirmed Ubuntu is installed on WSL2
- Configured Git global username and email
- Created public GitHub repository
- Initialized local Git repository
- Added README and .gitignore
- Pushed first commit to GitHub

## Commands used
```bash
wsl --status
wsl --list --verbose
git --version
git config --global user.name "Parag Jindal"
git config --global user.email "paragjindal023@gmail.com"
git init
git add .
git commit -m "Initial commit: cybersecurity home lab setup"
git branch -M main
git remote add origin https://github.com/Paragjindal01/cybersecurity-home-lab.git
git push -u origin main
