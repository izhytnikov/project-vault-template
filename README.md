# 📘 Project Vault Template
An **Obsidian vault template** designed to track tasks, meetings, and project notes.  
It uses a **Daily Notes–based structure** to help you:
- Track what tasks were completed on a specific date
- Automatically generate daily summaries
- Paste results into your project time management tool

---
## 👤 Who is this for?
- Best for **self-managing your work on projects**
- Intended for **solo use only** (not for team collaboration)

---
## ❓ What problem does it solve?
- Provides an **out-of-the-box solution** with:
    - Preconfigured plugins
    - File and folder structures
- Saves time compared to starting with a blank vault

---
## ⚙️ Requirements
- Tested on **Obsidian v1.9.13**
- All plugins are already included in the template  
    (no need to install them separately)

---
## 🚀 Getting Started
1. Install **Obsidian** → [Download here](https://obsidian.md/download)
2. Download the latest release → [Releases page](https://github.com/izhytnikov/project-vault-template/releases)
3. In Obsidian:
    - Click **Open folder as vault**
    - Select the downloaded template folder
4. Remove demo files:
    - Daily notes
    - Meetings
    - Tasks (Specific + Uncategorized)

---
## 🗂 Template Overview
### 📁 Absence
Folder contains three files:
- **General holidays** → list of public holidays
- **Sick leaves** → list of sick days
- **Vacations** → list of paid vacations

👉 You can change this structure if needed.

---
### 📅 Daily Notes
Each daily note has two sections:
- **Tasks list**
    - Shows tasks grouped by project → folder → file
    - Only tasks under a `To-Do` section **with a scheduled date** appear
- **Summary**
    - Shows files containing tasks completed that day
    - To exclude folders, configure the `Path to exclude from summary` setting in **Project Vault Tools**

#### 🔹 To-Do section
- Any file that contains a `To-Do` section will appear in the daily note/dashboard
- You can freely create subfolders/files
#### 🔹 Summary section
- Completed tasks automatically appear in the Summary
- Exclusions can be set in **Project Vault Tools**

---
### 📝 Meetings
Each meeting note has two sections:
- **To-Do** → meeting-related tasks
- **Raw notes** → notes you take during the meeting

---
### 📓 Notes
- Empty by default
- Add any subfolders/files to fit your project needs

---
### 📚 Resources
⚠️ **Must-have folder — do not delete!**
- **Attachments** → for images/audio dropped into notes
- **Canvases** → Obsidian Canvas files
- **Excalidraw** → Excalidraw sketches
- **Templates** → note templates (tasks, meetings, etc.)

💡 Example: Add common tasks to the **Task file template** so every new task file already includes them.

---
### ✅ Tasks
- **Specific** → structured task files
- **Uncategorized** → tasks excluded from summaries
#### Default Task File Structure
Each `To-Do` section has three subsections:
1. **General** → common tasks (tag with `#tasks/general`)
2. **Recurring** → repeat tasks
3. **Other tasks** → everything else

💡 This helps fold/unfold recurring or general tasks and focus on specifics.

---
### 📊 Dashboard
Three sections:
1. **General tasks** → tasks with `#tasks/general`
2. **Non-general tasks** → all other tasks
3. **Raw notes** → quick notes without structure

---
## 🔌 Plugins Overview
### 📅 Calendar
- Easier navigation between daily notes
- Simple way to create daily notes by date
### 📊 Dataview
- Used by **Project Vault Tools** to generate daily summaries
- Can be extended for custom queries
### 🎨 Excalidraw
- Alternative to Canvas for more flexible diagrams
### 🛠 Project Vault Tools
- Custom plugin created for this template
- **Automatically generates daily summaries**
- Learn more → [Plugin repository](https://github.com/izhytnikov/project-vault-tools)
### ✅ Tasks Plugin
The main tool for managing tasks.
#### Task Statuses
- Basic
	- [ ] to-do
	- [/] incomplete
	- [x] done
	- [-] canceled
	- [>] forwarded
	- [<] scheduling
- Extras
	- [?] question
	- [!] important
	- [*] star
	- ["] quote
	- [l] location
	- [b] bookmark
	- [i] information
	- [S] savings
	- [I] idea
	- [p] pros
	- [c] cons
	- [f] fire
	- [k] key
	- [w] win
	- [u] up
	- [d] down
	- [D] draft pull request
	- [P] open pull request
	- [M] merged pull request

👉 Use these freely to highlight tasks.
#### Dates
- **Scheduled date** is required for tasks to show up in daily notes
#### Recurrence
- Supports recurring tasks
- Completing one creates the next scheduled task automatically
#### Tags
- `#tasks/general` is used for Dashboard grouping
- You can create your own tags
#### Presets
- Reusable instruction/query blocks
- Update once → applies everywhere (daily notes + dashboard)

---
## 📌 Tips
- Keep tasks inside a **`To-Do` section** so they appear in dashboards/daily notes
- **Resources** folder must not be deleted
- Other folders (Tasks, Notes, etc.) can be safely renamed
- Use templates to keep meeting/task notes consistent
- Fold **General/Recurring** subsections to stay focused