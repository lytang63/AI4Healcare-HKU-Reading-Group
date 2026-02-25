# Tutorial: How to add a session (AI4Healcare@HKU Reading Group)

This tutorial explains how to create weekly materials using `template.md` and update the schedule in `README.md`.

---

## TL;DR (Presenter checklist)
1. Create folder: `sessions/<term>/YYYY-MM-DD-<type>-<short-title>/`
2. Copy `template.md` → `notes.md` and fill it
3. Add materials:
   - Upload PDFs (slides/paper), **or**
   - Put external links into `links.md`
4. Add **one row** to the schedule table in `README.md`
5. Open a Pull Request

---

## Step 0: Decide your session type
Use one of these types (same as the README table):

- `completed` — completed work / full project
- `wip` — work in progress + challenges + feedback request
- `paper` — paper sharing
- `tool` — new model/tool exploration or technical experience
- `conf` — conference experience sharing
- `other` — anything else valuable

---

## Step 1: Create a session folder

### Folder format
`sessions/<term>/YYYY-MM-DD-<type>-<short-title>/`

### Term examples
- `2026-spring`
- `2026-fall`
- `2027-spring`

### Short-title rules
- lowercase + hyphen (kebab-case)
- keep it short (3–8 words)
- avoid special characters

### Examples
- `sessions/2026-spring/2026-03-04-wip-ehr-phenotyping/`
- `sessions/2026-spring/2026-03-11-paper-diffusion-for-mri/`
- `sessions/2026-spring/2026-03-18-tool-vllm-serving/`

---

## Step 2: Create `notes.md` from the template

1. Copy `template.md` into your session folder
2. Rename it to `notes.md`
3. Fill it in

### Minimal acceptable notes (recommended baseline)
- **Basic Info** filled
- **Summary**: 3–8 bullets
- **Discussion Questions**: 2–3 questions
- At least one of: slides/paper/code/doc links (in `notes.md` or `links.md`)

### Tip
Keep the section headings unchanged so all sessions stay consistent and searchable.

---

## Step 3: Add materials (PDFs or links)

You can do either approach (or both).

### Option A: Upload PDFs into the session folder
Common filenames:
- `slides.pdf`
- `paper.pdf` (optional)

### Option B: Put external links into `links.md`
Create `links.md` under the same session folder.

Example `links.md`:
```md
# Links

- Slides: <link>
- Paper: <link>
- Code: <link>
- Dataset/Benchmark: <link>
- Recording (if any): <link>
