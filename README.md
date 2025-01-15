# Git & GitHub Practice: Task Board Project

A simple task management board to help you learn Git and GitHub workflows. This project uses vanilla JavaScript, HTML, and CSS to create a Kanban-style task board.

![Task Board Preview](/tobeadded/0)

## 🎯 Learning Objectives

By completing this project, you will learn:
- Basic Git commands and workflows
- Creating and managing branches
- Making Pull Requests (PRs)
- Reviewing code and handling merge conflicts
- Using GitHub's collaboration features

## 🚀 Getting Started

### Prerequisites
- Git installed on your computer
- GitHub account
- Basic knowledge of HTML, CSS, and JavaScript
- Any modern web browser

### Initial Setup

1. Fork this repository
```bash
# Click the 'Fork' button at the top right of this repository
```

2. Clone your forked repository
```bash
git clone https://github.com/YOUR-USERNAME/task-board.git
cd task-board
```

3. Open the project
```bash
# Open index.html in your browser
```

## 🏗️ Project Structure

```
task-board/
│
├── index.html      # Main HTML file with embedded CSS and JavaScript
├── README.md       # Project documentation (you are here)
└── .gitignore     # Git ignore file
```

## 🎓 Class Exercises

### Exercise 1: Basic Git Commands
1. Add your name to the task list
2. Check status and stage changes
```bash
git status
git add index.html
```
3. Commit your changes
```bash
git commit -m "Add [YOUR NAME] to task list"
```

### Exercise 2: Creating a Feature Branch
1. Create and checkout a new branch
```bash
git checkout -b feature/your-feature-name
```

2. Choose one feature to implement:
   - Add task priorities (High, Medium, Low)
   - Add due dates to tasks
   - Add task categories/labels
   - Add task color coding
   - Add task assignee field

3. Commit your changes
```bash
git add .
git commit -m "Add [FEATURE NAME]"
```

### Exercise 3: Creating a Pull Request
1. Push your branch to GitHub
```bash
git push origin feature/your-feature-name
```

2. Create a Pull Request on GitHub:
   - Go to your repository
   - Click "New Pull Request"
   - Select your feature branch
   - Add description of changes
   - Submit PR

### Exercise 4: Code Review
1. Find a classmate's PR to review
2. Leave constructive comments
3. Approve or request changes

### Exercise 5: Handling Merge Conflicts
1. Create a conflicting change
2. Resolve the conflict locally
3. Push resolved changes

## 💡 Feature Ideas

Here are some features you can implement for practice:

1. Task Priority
```javascript
// Add priority property to tasks
{ id: 1, title: 'Task', status: 'todo', priority: 'high' }
```

2. Due Dates
```javascript
// Add due date to tasks
{ id: 1, title: 'Task', status: 'todo', dueDate: '2025-01-20' }
```

3. Categories/Labels
```javascript
// Add category to tasks
{ id: 1, title: 'Task', status: 'todo', category: 'bug-fix' }
```

## 🤝 Contributing Guidelines

1. Branch Names:
   - Use descriptive branch names
   - Format: `feature/feature-name` or `fix/bug-name`

2. Commit Messages:
   - Be clear and descriptive
   - Start with action verb (Add, Fix, Update)
   - Keep under 50 characters

3. Pull Requests:
   - Fill out the PR template
   - Reference related issues
   - Add screenshots if UI changes

## 🐛 Common Issues & Solutions

1. **Git says "Permission denied"**
   - Check if you're using the correct GitHub credentials
   - Ensure SSH keys are set up correctly

2. **Merge conflict appears**
```bash
# 1. Update your branch with main
git checkout main
git pull origin main
git checkout your-branch
git merge main

# 2. Resolve conflicts in your editor
# 3. Stage and commit resolved files
git add .
git commit -m "Resolve merge conflicts"
```

3. **Push rejected**
```bash
# Pull latest changes first
git pull origin your-branch
# Then try pushing again
git push origin your-branch
```

## ✅ Done Checklist

- [ ] Forked and cloned repository
- [ ] Made first commit
- [ ] Created feature branch
- [ ] Implemented new feature
- [ ] Created Pull Request
- [ ] Reviewed classmate's code
- [ ] Resolved merge conflict
- [ ] Merged changes to main

## 🌟 Extra Challenges

1. Add local storage to persist tasks
2. Implement drag and drop
3. Add task filtering
4. Add search functionality
5. Add task descriptions

## 📚 Git Command Reference

```bash
# Check status
git status

# Create branch
git checkout -b branch-name

# Switch branch
git checkout branch-name

# Stage changes
git add filename
git add .  # all files

# Commit
git commit -m "message"

# Push
git push origin branch-name

# Pull
git pull origin branch-name

# Merge
git merge branch-name
```

## 🆘 Need Help?

1. Check the [Git documentation](https://git-scm.com/doc)
2. Ask  your instructor
3. Create an issue in the repository
4. Ask your peer/classmate/mentor

