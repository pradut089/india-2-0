# 📋 Submission Guidelines

## 📋 Table of Contents
- [What to Submit](#-what-to-submit)
- [Project Structure](#-project-structure)
- [Git Workflow for Teams](#-git-workflow-for-teams)
- [Submission Using GitHub Web Interface](#-submission-using-github-web-interface)
- [README.md Template](#-readmemd-template)
- [Technical Requirements](#️-technical-requirements)
- [Common Pitfalls to Avoid](#-common-pitfalls-to-avoid)
- [Getting Help](#-getting-help)
- [License](#-license)

## 🎯 What to Submit

### Required Components
1. **Project Documentation** (`README.md`)
   - Team information (names, roles, contacts)
   - **Country/Region information** (required for multi-country tracking)
   - Problem statement and solution overview
   - Technical implementation details
   - Setup and usage instructions
   - Demo video link

2. **Demo Materials**
   - Demo video link (hosted on YouTube, Vimeo, or similar platform)
   - Screenshots or screen recordings
   - Live demo link (if applicable)

3. **Source Code**
   - Well-documented code with clear comments
   - All source files in your team folder
   - Dependencies list (e.g., `requirements.txt` for Python, `package.json` for Node.js)

## 📂 Project Structure

**Simple Structure:** Create ONE folder with your team name. All your submission files go directly in this folder.

```
submissions/
└── your-team-name/       # Use hyphens, no spaces (e.g., "team-innovators")
    ├── README.md         # REQUIRED: All project documentation here
    ├── [your source code files]  # All code files directly in this folder
    ├── [screenshots/images]       # Demo materials directly in this folder
    └── [any other files]         # Everything in one place
```

> 💡 **Keep it simple:** Put everything (code, docs, images, etc.) directly in your team folder. No subfolders needed!

## 🔀 Git Workflow for Teams

### Step-by-Step Submission Process

1. **Team Leader Forks the Repository**
   - Go to the main repository: `https://github.com/DakshmA-Health/rare-impact-2025`
   - Click "Fork" button to create your own copy

2. **Create a Submission Branch** (Recommended)
   ```bash
   git clone https://github.com/your-username/rare-impact-2025.git
   cd rare-impact-2025
   git checkout -b your-team-name
   ```
   > 💡 **Why use a branch?** It keeps your main branch clean, allows easy updates, and follows Git best practices.

3. **Set Up Team Collaboration**
   - **Option A:** Leader adds team members as collaborators to their fork (Settings → Collaborators)
   - **Option B:** Team members clone the leader's fork and work on the same branch
   
   For team members joining:
   ```bash
   git clone https://github.com/leader-username/rare-impact-2025.git
   cd rare-impact-2025
   git checkout your-team-name
   ```

4. **Create Your Submission Folder**
   ```bash
   mkdir -p submissions/your-team-name
   cd submissions/your-team-name
   # Add all your files here: README.md, source code, images, etc.
   # Everything goes directly in this folder - no subfolders needed!
   ```

5. **Commit and Push Your Work**
   ```bash
   git add .
   git commit -m "Add submission for team-name"
   git push origin your-team-name
   ```

6. **Create Pull Request**
   - Go to your fork on GitHub
   - Click "New Pull Request"
   - **Source:** `your-username/rare-impact-2025:your-team-name`
   - **Target:** `DakshmA-Health/rare-impact-2025:main`
   - Fill out the [Pull Request Template](../PULL_REQUEST_TEMPLATE.md)

### ⚠️ Important Notes

- **Always create a branch** - Do NOT submit PRs directly from `main` branch
- **Branch naming:** Use `team-name` (use hyphens, no spaces)
- **Updating your submission:** Push new commits to the same branch - your PR will automatically update
- **Keep fork updated:** Periodically sync with the main repository:
  ```bash
  git remote add upstream https://github.com/DakshmA-Health/rare-impact-2025.git
  git fetch upstream
  git merge upstream/main
  ```

## 🌐 Submission Using GitHub Web Interface

If you prefer using GitHub's web interface instead of command line, follow these steps:

### Step-by-Step Web Interface Process

1. **Fork the Repository**
   - Go to: `https://github.com/DakshmA-Health/rare-impact-2025`
   - Click the **"Fork"** button (top right)
   - Select your account to create the fork

2. **Create a New Branch**
   - In your forked repository, click the branch dropdown (usually shows "main")
   - Type your team name (e.g., `your-team-name`) in the branch name field
   - Click **"Create branch: your-team-name from main"**
   - ✅ You're now on your team branch!

3. **Create Your Submission Folder**
   - Navigate to the `submissions/` folder
   - Click **"Add file"** → **"Create new file"**
   - Type: `submissions/your-team-name/README.md` (this creates the folder automatically)
   - Add your README content (see template below)
   - Click **"Commit new file"** at the bottom

4. **Add Your Project Files**
   - Navigate to `submissions/your-team-name/`
   - Click **"Add file"** → **"Upload files"** to upload multiple files at once
   - Or click **"Add file"** → **"Create new file"** for individual files
   - For each file:
     - Add your code, images, or other files
     - Write a clear commit message (e.g., "Add UI components", "Add API endpoints")
     - Select **"Commit directly to the your-team-name branch"**
     - Click **"Commit changes"**

5. **Create Pull Request**
   - After adding all your files, go to the **"Pull requests"** tab
   - Click **"New pull request"**
   - **Base repository:** `DakshmA-Health/rare-impact-2025` → `main`
   - **Head repository:** `your-username/rare-impact-2025` → `your-team-name`
   - Click **"Create pull request"**
   - Fill out the PR title and description using the [Pull Request Template](../PULL_REQUEST_TEMPLATE.md)
   - Click **"Create pull request"**

### 📝 Tips for Web Interface Users

- **File Size Limits:** GitHub web interface has file size limits (usually 100MB). For larger files, use command line or GitHub Desktop
- **Multiple Files:** Use "Upload files" to add multiple files at once
- **Editing Files:** Click any file → Click the pencil icon (✏️) to edit
- **Deleting Files:** Click any file → Click the trash icon (🗑️) to delete
- **Commit Messages:** Always write clear, descriptive commit messages
- **Daily Updates:** Push code daily by committing new changes to your branch

### 🔄 Updating Your Submission

To update your submission after creating the PR:

1. Go to your forked repository
2. Make sure you're on your team branch (`your-team-name`)
3. Navigate to the file you want to update
4. Click the **pencil icon** (✏️) to edit
5. Make your changes
6. Write a commit message (e.g., "Fix API bug", "Update README")
7. Select **"Commit directly to the your-team-name branch"**
8. Click **"Commit changes"**
9. Your PR will automatically update with the new changes!

### ⚠️ Important Reminders for Web Users

- ✅ **Always work on your team branch** - Never commit to `main`
- ✅ **Check your branch** - Look at the branch dropdown to confirm you're on `your-team-name`
- ✅ **Use clear commit messages** - Help the IT team track your progress
- ✅ **Include README.md** - Required in `submissions/your-team-name/README.md`
- ✅ **Include demo video link** - In your README, not as a file upload
- ❌ **Don't upload large files** - Use links instead (videos, large binaries)
- ❌ **Don't commit to main** - Always use your team branch

## 📝 README.md Template

Your team's `README.md` file must be placed at `submissions/your-team-name/README.md`. Use this template:

```markdown
# [Project Name]

## 👥 Team
- [Team Member 1] (Role, Contact)
- [Team Member 2] (Role, Contact)
- [Team Member 3] (Role, Contact)

## 🌍 Team Location
- **Country/Region:** [e.g., India, Malaysia, Philippines]
- **City:** [Optional: e.g., Mumbai, Kuala Lumpur, Manila]

## 🎯 Problem Statement
[1-2 paragraphs about the problem you're solving and why it matters for rare disease care]

## 💡 Solution
[Detailed explanation of your solution, including how it addresses the problem]

## 🛠️ Technical Implementation
- **Tech Stack**: [List technologies, frameworks, and tools used]
- **Key Features**: [List main features and functionalities]
- **Architecture**: [Brief system architecture or high-level design]

## 🚀 Getting Started
### Prerequisites
[List any prerequisites or requirements]

### Installation
[Step-by-step installation instructions]

### Usage
[How to run and use your solution]

## 📹 Demo
- **Demo Video:** [Link to your demo video on YouTube, Vimeo, or other platform]
- **Screenshots:** [Brief description of included screenshots]

## 📈 Future Work
[Potential improvements, next steps, or scalability considerations]

## 📚 Additional Resources
[Links to documentation, APIs used, or other relevant resources]
```

## ⚙️ Technical Requirements

### Code Quality
- Follow language-specific best practices
- Include clear, concise comments
- Document all public APIs and functions

### Version Control
- Use meaningful commit messages
- Keep commits focused and atomic
- Follow Git branching best practices

### Dependencies
- List all third-party libraries and tools
- Include version numbers
- Document any setup requirements

## 🚫 Common Pitfalls to Avoid

1. **Incomplete Submissions**
   - Missing demo video link (must be a link, not a file upload)
   - Missing country/region information in README
   - Incomplete team information
   - No clear setup instructions
   - Missing dependencies list

2. **Technical Issues**
   - Broken dependencies or missing dependency files
   - Missing environment variables or configuration
   - Platform-specific assumptions without documentation
   - Large files committed directly (use links instead)

3. **Documentation Gaps**
   - Unclear problem statement
   - Missing technical implementation details
   - No setup or usage instructions
   - Missing demo video or screenshots

4. **Git Workflow Mistakes**
   - Committing directly to `main` branch
   - Not creating a branch for your submission
   - Unclear commit messages
   - Not updating your PR regularly

## 🆘 Getting Help

If you encounter issues or have questions:

- **Email:** bikash.prasad@dakshamahealth.org
- **Review Documentation:** Check the [Submissions README](./submissions/README.md) for quick reference
- **Check Workflows:** Review both [Command Line Workflow](#-git-workflow-for-teams) and [Web Interface Guide](#-submission-using-github-web-interface)

> ⏰ **Remember**: Submit early and test thoroughly before the deadline! Automated validation will check your submission structure, but make sure all content is complete.

## 📜 License

By submitting your project, you agree that your submission will be made available under the same license terms as this repository. All participants retain ownership of their intellectual property.
