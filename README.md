# My LaTeX Resume 🚀

This repository contains my resume written in LaTeX. The resume is **automatically compiled into a PDF using GitHub Actions** and stored inside the `resume/` folder.

## 📄 View My Resume

[📄 Click here to view/download the latest resume (PDF)](https://gauravfs-14.github.io/resume/resume/resume.pdf)

---

## 🛠 How It Works

### ✅ **Automated Workflow**

1. **Write & Update**: Edit the `resume.latex` file (located in the root directory).
2. **GitHub Actions**: Every push automatically:
   - Compiles `resume.latex` into `resume.pdf`
   - Moves the generated `resume.pdf` into the `resume/` folder
   - Saves a backup as `resume-YYYY-MM-DD-HH-MM-SS.pdf` inside `resume/`
   - Pushes the changes back to GitHub
3. **Public Hosting via GitHub Pages**:
   - The latest resume is accessible at:
     ```
     https://gauravfs-14.github.io/resume/resume/resume.pdf
     ```
   - Preview the resume in web at:
     ```
     https://gauravfs-14.github.io/resume
     ```

---

## 🔧 How to Compile Locally

```sh
pdflatex resume.latex
mv resume.pdf resume/resume.pdf  # Move the compiled PDF into the resume/ folder
```

---

## 📝 How to Update Resume

1. **Edit** `resume.latex`
2. **Commit & Push**:
   ```sh
   git add resume.latex
   git commit -m "Updated resume"
   git push origin main
   ```
3. **GitHub Actions will handle everything else** 🚀

---

## 🗂 Resume Backup System

All previous versions of the resumes are stored inside the `resume/` folder with timestamps, following this naming format:

```
resume/resume-YYYY-MM-DD-HH-MM-SS.pdf
```

This ensures that older versions remain accessible.

---

## 🌟 Contributions

- If you have suggestions for improving this setup, feel free to open an **issue** or **pull request**.

---

🚀 **Maintained by [Gaurab Chhetri](https://github.com/gauravfs-14)**
