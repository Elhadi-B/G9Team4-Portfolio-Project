# 🧑‍💻 Team Portfolio Project
Collaborative **Team Portfolio Website** – A static website showcasing our team members, built collaboratively using Git and GitHub workflows

---

## 👥 Team Members

| Name | Role | GitHub Username |
|------|------|------------------|
| **Elhadi Bachir** | Team Leader | [@Elhadi-B](https://github.com/Elhadi-B) |
| **Hamada Chakib** | Developer | [@ch2kb](https://github.com/Ch2k5) |
| **Boukeloua Yasser** | Developer | [@YasserBoukeloua](https://github.com/YasserBoukeloua) |
| **Baatchia Abderrahmane** | Developer | [@Abderrahmane-41](https://github.com/Abderrahmane-41) |
| **Hammami Chahd** | Developer | [@ChahdHammami](https://github.com/ChahdHammami) 


## 📌 Project Description

This project is a **static website** that showcases all team members through individual profile pages.  
Each member created their own page containing:
- Full name  
- Short professional biography (2–3 sentences)  
- List of technical skills  
- Link to their GitHub profile  

The homepage (`index.html`) lists all team members, with each name linking to their respective profile page.

---

## 🧱 Project Structure
team-portfolio-project/
│
├── index.html # Homepage listing all team members
├── style.css # Shared CSS styles
├── elhadi-bachir.html # Individual profile page (example)
├── hamada-chakib.html
├── boukeloua-yasser.html
├── baatchia-abderrahmane.html
├── hammami-chahd.html
└── README.md # Project documentation (this file)




---

## 🧩 Workflow Steps

1. **Team Leader (Elhadi)** created the repository and added collaborators.  
2. Created the `develop` branch and protected the `main` branch (require PR + at least 1 approving review).  
3. Each member cloned the repo and created their own feature branch from `develop`.  
4. Each member implemented their HTML profile and updated `index.html`.  
5. Commits followed the **Conventional Commits** format.

---

## 🌐 Deployed Website

🔗 **GitHub Pages Link:** [Link to our portfolio](https://elhadi-b.github.io/G9Team4-Portfolio-Project/)

---

## 🧠 Team Retrospective Analysis

During the development of our Team Portfolio Project, the most significant technical challenge we faced was maintaining a smooth collaborative workflow using Git and GitHub. Since all members were pushing changes to shared files, especially `index.html`, merge conflicts occurred frequently. To handle this, we decided to strictly follow the branching model: all work was done on individual feature branches, merged into `develop`.

One specific merge conflict occurred when two members edited the same section of `index.html`. Git marked the conflicting lines, and we manually opened the file to review both changes. We then combined the updates logically, ensuring that no teammate’s contribution was lost. After saving the file, we ran `git add .` and `git commit` to finalize the resolution, followed by pushing the resolved branch and completing the merge request on GitHub.

The pull request and peer review process proved extremely helpful in improving our workflow quality. Every feature addition required at least one approval before merging, which encouraged communication and early detection of small issues such as inconsistent formatting or missing links. This process not only improved the overall code quality but also helped each team member gain confidence in using Git collaboratively. By the end of the project, our team had a clearer understanding of real-world version control practices and how collaborative reviews directly contribute to producing clean, stable software.

---