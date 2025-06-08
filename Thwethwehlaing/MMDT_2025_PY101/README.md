# MMDT_2025_PY101
This repository serves as the central submission point for homework assignments from students enrolled in the Python 101 course offered by MMDT

# Submission Guidelines: Using GitHub Branches

To ensure smooth and organized submissions, all students must submit their homework via **one shared GitHub repository**. Each student will create their own **branch** for submission. Please follow the instructions below to properly submit your work.

## Steps for Submission

### 1. Fork the Shared Repository
- Go to the shared GitHub repository [https://github.com/Myanmar-Data-Tech/MMDT_2025_PY101](Py101_batch01).
- Click the **“Fork”** button at the top-right corner to create a personal copy of the repository.

### 2. Clone Your Forked Repository
Once you've forked the repository, clone it to your local machine:
```bash
git clone https://github.com/YOUR_USERNAME/MMDT_2025_PY101.git
```

### 3. Create a Branch for Your Submission
Create a new branch using your **name** to clearly identify your submission:
```bash
git checkout -b yourname
```
> Example: `git checkout -b alex-chen`

### 4. Add Your Work
- Complete the homework locally (e.g., `<Your_name>_Ex_01.ipynb`).
- Put your completed notebook or code in a folder named `Your-name`.

### 5. Commit and Push Your Changes
After adding your work, commit and push your changes to your branch:
```bash
git add .
git commit -m "Completed Ex01 and add reflection"
git push origin yourname
```

### 6. Create a Pull Request
- Go to your GitHub repository.
- Click **“Compare & pull request”**.
- Title the pull request as: `<Mid-term> Project Submission - Your Name`
- Confirm your changes and submit the pull request to the **main repository**.

## Summary Checklist
- [ ] Forked the repo
- [ ] Created a personal branch (e.g., `yourname`)
- [ ] Added all required files in the `[Yourname]/` [Yourname]
- [ ] Committed & pushed changes
