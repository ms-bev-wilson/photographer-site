# Photographer Site

Simple static portfolio website (HTML, CSS, JS) — photos and gallery assets.

What I added
- A basic `.gitignore` for common files
- An MIT `LICENSE` (if you want a different license, edit or remove it)

How to create a GitHub repository and push (two options)

1) If you have the GitHub CLI (`gh`) installed and authenticated (recommended):

   gh repo create <repo-name> --public --source=. --remote=origin --push -y

   This will create a remote repository named `<repo-name>` (defaults to current folder name
   when you omit the name), add it as `origin`, and push the current branch.

2) Without the GH CLI (use GitHub website):

   - Create a new repository on github.com (choose public/private, no README).
   - Then run locally:

     git remote add origin <YOUR_REMOTE_URL>
     git branch -M main
     git push -u origin main

Notes / assumptions
- I inferred repository metadata automatically. If you prefer a different repo name or
  license, change the files accordingly.

Local usage
- Open `index.html` in your browser to view the site.
