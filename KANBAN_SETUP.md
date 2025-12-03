# 📋 GitHub Project Board Setup Guide (Kanban Style)

This guide provides step-by-step instructions to create and configure the project's GitHub Project Board following the required Kanban methodology.

---

## 🎯 Board Requirements

### Required Columns
| Column | Purpose |
|--------|---------|
| **Backlog** | Ideas and potential tasks |
| **To Do** | Tasks committed for next sprint/week |
| **In Progress** | Currently active tasks |
| **Review/Testing** | Tasks pending verification |
| **Done** | Completed tasks |

---

## 👥 Team Members & Roles

### Project Team
| Name | Role | Responsibilities |
|------|------|------------------|
| **Wassi Haider Kabir** | Team Lead / Embedded | Hardware deployment, Jetson Nano optimization |
| **Muhammad Ashar Javid** | Simulation | Model training, testing, benchmarking |
| **Hamza Irshad Bhatti** | Simulation | Dataset preparation, model evaluation |
| **Ammar** | Documentation | Literature review, reports, documentation |

### Mandatory Oversight Members (Read & Comment Access)
| Name | Role | Access Level |
|------|------|--------------|
| **Ms. Tehniyat Siddiqui** | Lab Engineer | Read & Comment |
| **Dr. Tauseef ur Rehman** | Instructor | Read & Comment |

---

## 🚀 Setup Instructions

### Step 1: Create a New Project Board

1. Go to your repository on GitHub
2. Click on the **"Projects"** tab
3. Click **"Link a project"** → **"New project"**
4. Select **"Board"** template (Kanban style)
5. Name the project: `Object Detection - Haze/Fog - Project Board`
6. Click **"Create project"**

### Step 2: Configure Board Columns

1. In the project board, you'll see default columns
2. Rename/Add columns to match requirements:
   - **Backlog** - Ideas and potential tasks
   - **To Do** - Tasks committed for next sprint/week
   - **In Progress** - Currently active tasks
   - **Review/Testing** - Tasks pending verification
   - **Done** - Completed tasks

3. To add a column: Click **"+ New Column"** on the right side
4. To rename a column: Click the column header → Edit

### Step 3: Add Team Members

1. Go to repository **Settings** → **Collaborators and teams**
2. Click **"Add people"**
3. Add each team member with appropriate access:

   **Project Team (Write Access):**
   - Wassi Haider Kabir
   - Muhammad Ashar Javid
   - Hamza Irshad Bhatti
   - Ammar

   **Oversight Members (Read Access):**
   - Ms. Tehniyat Siddiqui (Lab Engineer)
   - Dr. Tauseef ur Rehman (Instructor)

### Step 4: Configure Project Access for Oversight

1. Go to the Project Board settings (⚙️ icon)
2. Click **"Manage access"**
3. Add oversight members:
   - Ms. Tehniyat Siddiqui → **Read** access
   - Dr. Tauseef ur Rehman → **Read** access

---

## 📝 Creating Tasks

### Method 1: Create as GitHub Issues (Preferred)

1. Go to repository **Issues** tab
2. Click **"New issue"**
3. Select appropriate template:
   - 🔧 Simulation Task
   - 📄 Documentation Task
   - 💻 Embedded Task
4. Fill in the issue details
5. Assign to appropriate team member
6. Add to the Project Board

### Method 2: Create as Notes in Project Board

1. Go to Project Board
2. Click **"+ Add item"** in any column
3. Type task description
4. Convert to Issue if needed by clicking the note

---

## 📊 Weekly Update Requirements

- [ ] Board must be updated at least **weekly**
- [ ] Move tasks between columns as progress is made
- [ ] Snapshots may be requested at milestones
- [ ] All team members should update their assigned tasks

### Weekly Checklist
1. Review **Backlog** - add new ideas/tasks
2. Move ready tasks to **To Do** for the week
3. Update **In Progress** items with comments
4. Move completed work to **Review/Testing**
5. After verification, move to **Done**

---

## 🏷️ Recommended Labels

Create these labels for better task organization:

| Label | Color | Description |
|-------|-------|-------------|
| `simulation` | 🔵 Blue | Model training & testing tasks |
| `documentation` | 🟢 Green | Documentation & reports |
| `embedded` | 🟠 Orange | Jetson Nano deployment tasks |
| `high-priority` | 🔴 Red | Urgent tasks |
| `phase-1` | 🟣 Purple | Literature Review phase |
| `phase-2` | 🟡 Yellow | Implementation phase |

---

## 📅 Project Phases

### Phase 1: Literature Review & Feasibility ✅
- Review research papers (2019-2025)
- Document feasibility for Jetson Nano
- Create literature review report

### Phase 2: Implementation & Benchmarking (Upcoming)
- Implement dehazing-detection pipelines
- Model quantization (FP16/INT8)
- Deploy on Jetson Nano
- Benchmark performance

---

## 🔗 Quick Links

- [GitHub Projects Documentation](https://docs.github.com/en/issues/planning-and-tracking-with-projects)
- [Managing Access to Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/managing-your-project/managing-access-to-your-projects)
- [Creating Issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue)

---

## ❓ Need Help?

Contact the project team or oversight members for assistance with board setup or access issues.
