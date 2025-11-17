# 📁 Submissions Directory

> **Note:** This is an instructions file for the submissions folder. Each team should create their own folder and README.md file inside it.

This directory contains all hackathon project submissions. Each team should create their own folder following the naming convention below.

## 📋 Folder Structure

**Simple Structure:** Create ONE folder with your team name. Put ALL your files directly in this folder.

```
submissions/
└── your-team-name/       # Example: "team-innovators" or "rare-disease-trackers"
    ├── README.md         # ⚠️ REQUIRED - Your project documentation (see template below)
    ├── [all your code files]     # Put source code files directly here
    ├── [screenshots/images]      # Put demo materials directly here
    └── [any other files]         # Everything in one place - no subfolders!
```

> 💡 **Keep it simple:** All files (code, docs, images, etc.) go directly in your team folder. No subfolders needed!

## 📝 Your Team's README.md

**Important:** You must create a `README.md` file inside your team folder (`submissions/your-team-name/README.md`) with:

### Required Sections:
- ✅ **Team information** (names, roles, contacts)
- ✅ **Country/Region information** (required for multi-country tracking)
- ✅ **Problem statement** (what problem are you solving?)
- ✅ **Solution overview** (how does your solution work?)
- ✅ **Technical implementation** (tech stack, features, architecture)
- ✅ **Demo video link** (hosted on YouTube, Vimeo, etc. - NOT a file upload)
- ✅ **Setup instructions** (how to install and run your project)

📘 See the complete template in [Submission Guidelines](../SUBMISSION_GUIDELINES.md#-readmemd-template)

## ✅ Quick Checklist

Before submitting your PR, ensure:

### Repository Setup
- [ ] Your team leader has forked the repository
- [ ] You're working on a branch (e.g., `team-name`) - NOT on `main`
- [ ] Your team folder is named using hyphens (e.g., `team-name`, not `team name`)

### Documentation
- [ ] You've created `submissions/your-team-name/README.md` with all required information
- [ ] Your README.md includes **team information** (names, roles, contacts)
- [ ] Your README.md includes **country/region information** (required)
- [ ] Your README.md includes a **demo video link** (not the video file itself)
- [ ] Your README.md includes **setup instructions** and **dependencies**

### Code & Submission
- [ ] All code is properly documented with comments
- [ ] You've followed the [Git Workflow](../SUBMISSION_GUIDELINES.md#-git-workflow-for-teams) or [Web Interface Guide](../SUBMISSION_GUIDELINES.md#-submission-using-github-web-interface)
- [ ] Your PR follows the [Pull Request Template](../PULL_REQUEST_TEMPLATE.md)
- [ ] Your PR is created from your branch, not from `main`
- [ ] All automated validation checks pass

## 📝 Important Notes

1. **Demo Videos**: 
   - Include a **link** to your demo video (YouTube, Vimeo, Google Drive, etc.) in your team's README.md
   - Do NOT commit video files (`.mp4`, `.mov`, etc.) to this repository
   - Video files are large and will cause issues

2. **File Size**: 
   - Keep screenshots and images reasonable in size (< 5MB recommended)
   - Large files may cause repository issues or slow down cloning

3. **Code Organization**: 
   - Put all your source code files directly in your team folder
   - No subfolders needed - keep it simple!
   - Include dependency files (`requirements.txt`, `package.json`, etc.)

4. **Documentation**: 
   - Your team's `README.md` is **required** and must be comprehensive
   - Follow the template provided in the [Submission Guidelines](../SUBMISSION_GUIDELINES.md#-readmemd-template)
   - Include country/region information for multi-country tracking

5. **Branch Safety**: 
   - Always work on your team branch, never on `main`
   - Check which branch you're on before committing (especially when using web interface)

## 🚫 What NOT to Include

- Video files (`.mp4`, `.mov`, etc.) - use links instead
- Large binary files
- Environment files (`.env`, config files with secrets)
- Dependencies (`node_modules/`, `venv/`, etc.)
- IDE-specific files (`.vscode/`, `.idea/`, etc.)

These are automatically ignored by `.gitignore`, but please be mindful.

## 📞 Need Help?

If you have questions about the submission process:
- **Email:** bikash.prasad@dakshamahealth.org
- Review the [Submission Guidelines](../SUBMISSION_GUIDELINES.md)

---

**Good luck with your submission! 🚀**

