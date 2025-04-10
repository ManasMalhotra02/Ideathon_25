# 📢 Innovare Technical Club - Ideathon 25 Submission Guidelines

Welcome to the official repository for **Ideathon-25**, hosted by **Innovare Technical Club, Vaish College of Engineering, Rohtak** on **March 27, 2025**.  

All participants must follow the steps below to submit their project work efficiently.

---

## 🚀 Steps to Submit Your Project  

### 1️⃣ Fork this Repository  
Click on the **Fork** button at the top-right corner of this repo to create your copy.  

### 2️⃣ Clone Your Forked Repository  
```bash
git clone https://github.com/InnovareTechnicalClub/Ideathon_25.git
cd Ideathon_25
```

### 3️⃣ Create a New Branch (Optional)
```bash
git checkout -b {team-name}
```
### 4️⃣ Follow the Folder Structure  
Inside the projects/ folder, create a new folder with your team name, for example:
```bash
projects/Team_Innovators/
```
Inside your team folder, add the following files:
```
projects/Team_Innovators/
├── README.md               # About your project
├── presentation.pptx       # Final PPT
├── requirements.txt        # Dependencies (if any)
├── code/                   # (Optional) Your source code
│   └── main.py / app.js
├── images/                 # Screenshots or diagrams
├── demo_video.mp4          # Prototype demo (compressed if possible)
└── team_award_photo.jpg    # Group photo receiving award/certificate
```
### 5️⃣ Add and Commit Your Changes to your GitHub forked repository:  
```bash
git add .
git commit -m "Add Team_Innovators project"
git push origin main
```

### 6️⃣ Go to your forked repo on GitHub and click "Contribute > Open Pull Request".

Make sure to select:

- Base repository: ideathon_25_projects

- Base branch: main

- Head repository: your team repo

- Head branch: main

---
## 🛡️ Best Practices to Avoid Merge Conflicts

To ensure a smooth and conflict-free submission process, all participants must follow these important guidelines:

### 🔐 Use Unique Team Folder Names
Each team should create a uniquely named folder inside the `projects/` directory. This helps prevent name collisions when merging.

✅ Examples:
### 🚫 Do NOT Modify Root-Level Files
Please **do not edit or change** the main repository's root-level files such as:
- `README.md`
- `.gitignore`
- Any configuration or workflow files

Making changes to these can cause conflicts and delay the merge process.

### 🔄 Always Pull the Latest Changes Before Pushing
Before committing and pushing your changes, make sure your fork is updated with the latest changes from the main repository.

Run the following commands:

```bash
git remote add upstream https://github.com/InnovareTechnicalClub/Ideathon_25.git
git pull upstream main --rebase
```

## ✅ What to Include in Your Submission?  
Each submission should contain:  
✔ **Project Title & Team Members** (Inside `README.md`)  
✔ **Well-Defined Explanation** (Inside `README.md`)  
✔ **PPT Presentation** (`Idea_Presentation.pptx`)  
✔ **MVP Code** (If available)  
✔ **Requirements or Dependencies** (if any)  

---

📌 **For any issues, contact:** Technical Coordinators or open a **GitHub Issue** in this repo.  

Happy Coding! 🚀
