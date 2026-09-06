# Mohamed Ahmed Mokhtar — Portfolio

A single-page portfolio site (HTML/CSS, no build step needed).

## Structure
```
portfolio/
├── index.html        # the whole site
└── assets/
    └── profile.jpg    # profile photo
```

## Run locally
Just open `index.html` in a browser — no server needed.

## Publish with GitHub Pages
1. Create a new repo on GitHub, e.g. `mohamed-portfolio`.
2. In this folder, run:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub: go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`,
   branch `main`, folder `/ (root)`. Save.
5. Your site will be live in a minute or two at:
   `https://<your-username>.github.io/<repo-name>/`

   (If you name the repo `<your-username>.github.io` exactly, it will be
   served at `https://<your-username>.github.io/` directly, with no
   sub-path.)

## Editing content
Open `index.html` in any text editor. All placeholder text (job title,
experience, projects, skills, achievements) is marked clearly — search
for words like "Job Title", "Company Name", "Project Name" and replace
them with your real content.
