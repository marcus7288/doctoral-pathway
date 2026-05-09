# VS Code + GitHub Setup Guide
## Cloning Your Doctoral Repository for Local Use

**Professor Maine | Evangel University**  
*Step-by-step guide for editing your doctoral project files locally in VS Code*

---

## What You'll Have When This Is Done

- Your doctoral project repo cloned to your local computer
- VS Code configured for Markdown editing with live preview
- Two recommended extensions installed
- A daily commit-and-push workflow you can run in under 2 minutes

---

## Prerequisites Checklist

Before starting, confirm you have these installed:

- [ ] **Git** — [git-scm.com/downloads](https://git-scm.com/downloads) — download and install if not present
- [ ] **VS Code** — [code.visualstudio.com](https://code.visualstudio.com) — install if not present
- [ ] **GitHub account** — you already have this ✅
- [ ] **Your doctoral repo exists on GitHub** — push your files first if not already done

To check if Git is installed: open any terminal and type `git --version`. If you see a version number, you're good.

---

## Part 1 — Configure Git with Your Identity

> Skip this if you've used Git on this machine before.

Open a terminal (PowerShell on Windows, Terminal on Mac) and run these two commands, replacing the values with your actual name and email:

```bash
git config --global user.name "Mark Maine"
git config --global user.email "mainem@evangel.edu"
```

**Verify it worked:**
```bash
git config --global --list
```
You should see your name and email in the output.

---

## Part 2 — Authenticate VS Code with GitHub

VS Code needs permission to push to your GitHub repos.

### Step 1 — Open VS Code

Launch VS Code. You should see the welcome screen.

### Step 2 — Open the Source Control Panel

Click the **branch icon** in the left sidebar (third icon down, looks like a node diagram), or press `Ctrl+Shift+G` (Windows) / `Cmd+Shift+G` (Mac).

### Step 3 — Sign In to GitHub

1. At the bottom-left corner of VS Code, click the **person icon** (Accounts)
2. Click **Sign in with GitHub**
3. A browser window opens — log in to GitHub and click **Authorize Visual Studio Code**
4. Return to VS Code — you'll see your GitHub username at the bottom left

---

## Part 3 — Clone Your Repository

### Step 1 — Get Your Repo URL

1. Go to [github.com](https://github.com) and navigate to your doctoral project repository
2. Click the green **Code** button
3. Make sure **HTTPS** is selected
4. Click the copy icon to copy the URL
   - It will look like: `https://github.com/your-username/your-repo-name.git`

### Step 2 — Clone via VS Code

1. In VS Code, press `Ctrl+Shift+P` (Windows) / `Cmd+Shift+P` (Mac) to open the **Command Palette**
2. Type `Git: Clone` and select it
3. Paste your repo URL and press `Enter`
4. A folder picker opens — choose where to save the repo on your computer

   **Recommended location:**
   ```
   C:\Users\secon\Documents\doctoral-project\
   ```
   or wherever you keep your working files — just not inside OneDrive if you can avoid it (Git and OneDrive sync can conflict)

5. Click **Select as Repository Destination**
6. VS Code will download all your files. When it finishes, click **Open** in the notification that appears

### Step 3 — Confirm the Clone Worked

You should now see your file tree in the VS Code **Explorer** panel (first icon in the left sidebar, or `Ctrl+Shift+E`). You'll see:

```
doctoral-project/
├── README.md
├── docs/
├── independent-study/
├── literature-review/
├── reading-lists/
├── reading-notes/
├── resources/
├── schedule/
└── dissertation/
```

If you see these folders, the clone was successful. ✅

---

## Part 4 — Install Recommended Extensions

Press `Ctrl+Shift+X` to open the Extensions panel. Search for and install each of these:

### Extension 1 — Markdown All in One
**Search:** `Markdown All in One`  
**Publisher:** Yu Zhang  
**Install:** Click **Install**

**What it gives you:**
- `Tab` to jump between table cells (makes filling in your weekly log much faster)
- Auto-formatting for lists and headings
- Keyboard shortcuts for bold (`Ctrl+B`), italic (`Ctrl+I`), etc.
- Table of contents generation

### Extension 2 — Markdown Preview Enhanced
**Search:** `Markdown Preview Enhanced`  
**Publisher:** Yiyi Wang  
**Install:** Click **Install**

**What it gives you:**
- A live preview panel that updates as you type
- Renders tables, checkboxes, and formatting exactly as GitHub will show them

### Optional — GitLens
**Search:** `GitLens`  
**Publisher:** GitKraken  
**What it gives you:** See who changed what and when, inline commit history — useful once you're deep into dissertation writing

---

## Part 5 — Your Daily Editing Workflow

### Opening a File to Edit

1. In the **Explorer** panel (`Ctrl+Shift+E`), click any `.md` file to open it
2. To open the live preview alongside it:
   - Press `Ctrl+Shift+V` (built-in preview), **or**
   - Right-click the tab → **Open Preview to the Side** (Markdown Preview Enhanced)
3. You'll have the raw Markdown on the left and the rendered preview on the right

**Recommended layout for the weekly log:**

```
[Explorer panel] | [weekly-log.md editor] | [Live Preview]
```

Press `Ctrl+\` to split the editor and arrange as above.

### Filling In the Weekly Log — Step by Step

1. Open `independent-study/Pre-Program/weekly-log.md`
2. Find the current week's section
3. Add a new row to the sessions table:
   ```
   | May 12 | Guzdial Ch. 3–4 | pp. 45–78 | 1.5 | Instapaper | Reading notes started |
   ```
   - Press `Tab` to move between cells (Markdown All in One handles alignment automatically)
4. Add 2–3 bullet points under **Key Insights**
5. Fill in **Next Week's Plan**
6. Save: `Ctrl+S`

### Filling In the Adler Worksheet — Step by Step

1. Copy `docs/adler-reading-worksheet.md`
2. Rename the copy: `reading-notes/lastname-year-shorttitle.md`
   - Example: `reading-notes/guzdial-2015-learner-centered.md`
3. Open the file and fill in the bibliographic information at the top
4. Work through the worksheet section by section as you read
5. Save after each section: `Ctrl+S`
6. Checkboxes (` - [ ] `) can be clicked directly in the preview panel, or typed manually in the editor

---

## Part 6 — Committing and Pushing Changes to GitHub

After every editing session, push your changes so they're saved to GitHub.

### Using the VS Code GUI (Recommended)

1. Click the **Source Control** icon in the left sidebar (`Ctrl+Shift+G`)
2. You'll see a list of files you've changed under **Changes**
3. Hover over the files you want to commit → click the **+** icon to **Stage** them
   - Or click **+** next to **Changes** to stage everything at once
4. In the **Message** box at the top, type a descriptive commit message:
   ```
   Update weekly log: May 12 — Guzdial Ch. 3-4
   ```
   ```
   Add reading notes: guzdial-2015-learner-centered (Ch. 1-3)
   ```
   ```
   Add monthly reflection: May 2026
   ```
5. Press `Ctrl+Enter` to commit
6. Click the **Sync Changes** button (circular arrows) that appears, or press the **...** menu → **Push**

### Using the Integrated Terminal (Optional)

Press `` Ctrl+` `` to open the terminal in VS Code, then:

```bash
git add .
git commit -m "Update weekly log: May 12 — Guzdial Ch. 3-4"
git push
```

---

## Part 7 — Pulling Updates (If You Edit on GitHub.com or Mobile)

If you ever edit a file directly on GitHub.com or via the GitHub mobile app, you need to pull those changes to your local copy before editing locally.

**Always pull before you start editing locally:**

In VS Code Source Control panel → click **...** menu → **Pull**

Or in the terminal:
```bash
git pull
```

> **Why this matters:** If you edit locally without pulling first, and there are changes on GitHub, you'll get a merge conflict. Always pull first — it takes two seconds and prevents headaches.

---

## Part 8 — Commit Message Conventions

All commit messages use a `[prefix]` format so your history is machine-readable and tells admissions committees exactly what kind of work you did.

### Prefixes

| Prefix | Use for | Example |
|---|---|---|
| `[ocw]` | OCW lecture notes, problem sets | `[ocw] 6.1200J week 3 problem set - modular arithmetic` |
| `[read]` | Adler worksheets, reading notes | `[read] Adler worksheet - Guzdial 2015 - Learner-Centered Design` |
| `[log]` | Monthly reading logs | `[log] Reading log - June 2026` |
| `[docs]` | Strategic documents updated | `[docs] Update implementation guide v2.1` |
| `[tools]` | Tool workflows updated | `[tools] Update Zotero annotation workflow` |
| `[reflect]` | Course or phase reflections | `[reflect] 6.1200J complete - course reflection` |
| `[lit]` | Literature review updates | `[lit] Annotated bibliography - Theme 3 faith pedagogy` |
| `[fix]` | Corrections to any document | `[fix] Broken link in pre-program reading list` |

### Full format

```
[prefix] Short description of what was added or changed
```

**Examples:**
```
[ocw] 6.1200J week 1 lecture notes - propositions and logic
[ocw] 6.1200J PS2 - sets and functions
[read] Adler worksheet - margolis-2002-unlocking-clubhouse
[read] Reading notes - guzdial-2015-learner-centered (Ch. 1-3)
[log] Reading log - May 2026
[log] Reading log - June 2026
[reflect] 6.1200J complete - course reflection
[docs] Update doctoral schedule - corrected timeline
[lit] Annotated bibliography - Theme 7B trauma-informed
[fix] Corrected weekly log session date
```

### Why this format matters

Every commit with a `[ocw]` prefix is evidence of mathematical self-study. Every `[read]` prefix is evidence of research literacy. Admissions committees reviewing your GitHub history can filter by prefix and see a complete record of your scholarly development. Keep messages descriptive — `[ocw] 6.1200J PS3 - modular arithmetic and number theory` tells a stronger story than `[ocw] PS3 done`.

---

## Troubleshooting

| Problem | Solution |
|---|---|
| "git is not recognized" | Git isn't installed or not in PATH — reinstall from git-scm.com |
| VS Code asks for password every push | Set up a GitHub Personal Access Token (Settings → Developer Settings → PAT) |
| "Please tell me who you are" error | Run `git config --global user.name` and `git config --global user.email` (Part 1) |
| Merge conflict warning | Run `git pull` first, resolve conflicts, then commit |
| Preview not showing checkboxes | Use **Markdown Preview Enhanced** extension, not the built-in preview |
| Table not formatting correctly | Markdown All in One — press `Alt+Shift+F` to auto-format the table |
| Changes not showing in Source Control | Make sure you opened the cloned folder (`File → Open Folder`), not just a file |

---

## Quick Reference Card

| Action | Shortcut |
|---|---|
| Open Explorer (file tree) | `Ctrl+Shift+E` |
| Open Source Control | `Ctrl+Shift+G` |
| Open Command Palette | `Ctrl+Shift+P` |
| Open integrated terminal | `` Ctrl+` `` |
| Split editor (edit + preview) | `Ctrl+\` |
| Open Markdown preview | `Ctrl+Shift+V` |
| Save file | `Ctrl+S` |
| Bold text | `Ctrl+B` |
| Italic text | `Ctrl+I` |
| Jump between table cells | `Tab` |
| Format table | `Alt+Shift+F` |
| Commit (after staging) | `Ctrl+Enter` |

---

*Professor Maine | Evangel University | Doctoral Project*  
*Last updated: May 2026*
