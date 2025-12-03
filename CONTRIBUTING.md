# 🤝 Contributing Guide

Welcome to the **Object Detection in Hazy and Foggy Conditions on NVIDIA Jetson Nano** project! This guide outlines the workflow, roles, and contribution process for all team members.

---

## 👥 Team Structure

### Project Team Members

| Member | GitHub Username | Role | Focus Area |
|--------|-----------------|------|------------|
| **Wassi Haider Kabir** | @wassihaiderkabir | Team Lead / Embedded | Jetson Nano deployment, TensorRT optimization |
| **Muhammad Ashar Javid** | *Update when available* | Simulation | Model training, benchmarking |
| **Hamza Irshad Bhatti** | *Update when available* | Simulation | Dataset preparation, model evaluation |
| **Ammar** | *Update when available* | Documentation | Literature review, reports |

> **Note:** Team members should update this table with their GitHub usernames.

### Oversight Members

| Member | Role | Responsibilities |
|--------|------|------------------|
| **Ms. Tehniyat Siddiqui** | Lab Engineer | Project monitoring, technical guidance |
| **Dr. Tauseef ur Rehman** | Instructor | Academic oversight, milestone reviews |

---

## 🔄 Workflow: Kanban Board

We use a **Kanban-style GitHub Project Board** to track all tasks.

### Board Columns

```
Backlog → To Do → In Progress → Review/Testing → Done
```

| Column | Description | Who Moves Here |
|--------|-------------|----------------|
| **Backlog** | Ideas and potential tasks | Anyone |
| **To Do** | Committed tasks for the week | Team Lead |
| **In Progress** | Currently being worked on | Assigned member |
| **Review/Testing** | Pending verification | After work completion |
| **Done** | Completed and verified | After review passes |

---

## 📝 Creating Tasks

### Using Issue Templates

We have three issue templates for different task types:

1. **🔧 Simulation Task** - For model training, testing, benchmarking
2. **📄 Documentation Task** - For reports, literature review, README updates
3. **💻 Embedded Task** - For Jetson Nano deployment, optimization

### Task Assignment by Role

| Role | Types of Tasks |
|------|----------------|
| **Simulation** | Model training, dataset prep, accuracy testing, benchmarking |
| **Documentation** | Literature review, IEEE reports, README updates, guides |
| **Embedded** | TensorRT conversion, Jetson Nano testing, FPS optimization |

---

## 🏷️ Labels

Use appropriate labels when creating issues:

| Label | Use For |
|-------|---------|
| `simulation` | Model and training related |
| `documentation` | Documentation tasks |
| `embedded` | Hardware deployment |
| `high-priority` | Urgent tasks |
| `phase-1` | Literature Review phase |
| `phase-2` | Implementation phase |
| `bug` | Something isn't working |
| `enhancement` | New feature or improvement |

---

## 📅 Weekly Updates

All team members must update the project board **weekly**:

### Weekly Checklist

- [ ] Update status of your assigned tasks
- [ ] Move completed items to Review/Testing
- [ ] Add comments on blockers or progress
- [ ] Create new issues for identified work
- [ ] Attend weekly sync (if scheduled)

### Milestone Snapshots

At key milestones, the team lead will:
1. Take a screenshot of the board
2. Document completed work
3. Share progress with oversight members

---

## 💻 Development Workflow

### Branch Naming Convention

```
feature/<description>    # New features
fix/<description>        # Bug fixes
docs/<description>       # Documentation updates
```

### Commit Message Format

```
<type>: <short description>

Types: feat, fix, docs, test, refactor
```

**Examples:**
```
feat: Add YOLOv5 inference script
docs: Update literature review section
fix: Correct TensorRT quantization parameters
```

### Pull Request Process

1. Create a branch from `main`
2. Make your changes
3. Create a Pull Request
4. Request review from a team member
5. Address feedback
6. Merge after approval

---

## 📁 Repository Structure

```
├── /docs                    # Documentation & reports
│   ├── LiteratureReview.pdf
│   └── references/          # Research papers
├── /src                     # Source code
│   └── main.py             # Main implementation
├── /data                    # Sample data & images
├── /results                 # Benchmark results
├── README.md               # Project overview
├── CONTRIBUTING.md         # This file
├── KANBAN_SETUP.md         # Project board setup guide
└── TEAM.md                 # Team roles & responsibilities
```

---

## ✅ Code Quality

### Before Submitting

- [ ] Code is tested locally
- [ ] Documentation is updated if needed
- [ ] No hardcoded paths or credentials
- [ ] Follows existing code style

### For Python Code

- Use meaningful variable names
- Add docstrings to functions
- Follow PEP 8 style guidelines
- Test on target hardware when possible

---

## 🆘 Getting Help

- **Technical Issues**: Post in GitHub Issues
- **Board/Process Questions**: Contact Team Lead
- **Academic Guidance**: Contact oversight members

---

## 📞 Communication

- **Primary**: GitHub Issues and Project Board
- **Updates**: Weekly board updates
- **Reviews**: Pull Request comments

---

Thank you for contributing to this research project! 🚀
