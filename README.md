# Drashti's Work Tracker

A personal tracker for additional work at Samco Securities — blogs, help articles, internal comms, assessments, e-learning scripts, NISM prep, sales docs, and ad hoc tasks.

---

## How to set up on GitHub Pages

### Step 1 — Create a new GitHub repo
1. Go to [github.com](https://github.com) → click **New repository**
2. Name it something like `work-tracker`
3. Set it to **Public** (required for free GitHub Pages)
4. Click **Create repository**

### Step 2 — Upload the files
1. Click **Add file → Upload files**
2. Upload both `index.html` and `data.json`
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Branch: `main` / Folder: `/ (root)`
4. Click **Save**
5. Wait ~1 minute, then your tracker is live at:
   `https://YOUR-USERNAME.github.io/work-tracker/`

---

## How to use it

### Adding a task
- Type the task name in the quick-add bar and press **Enter** or click **+ Add**
- The edit modal opens automatically — fill in the details and click **Save task**

### Editing a task
- Click **Edit** on any row to update details

### Saving permanently
- Every time you add/edit/delete a task, a purple banner appears at the top
- Click **Download JSON** — this downloads an updated `data.json`
- Go to your GitHub repo → click on `data.json` → click the pencil (edit) icon
- OR just drag and drop the new `data.json` file via **Add file → Upload files**
- Commit the change — your tracker updates on next page load

---

## Files

| File | What it does |
|---|---|
| `index.html` | The full tracker UI — open this in browser |
| `data.json` | Your task data — update this on GitHub to save |
| `README.md` | This setup guide |
