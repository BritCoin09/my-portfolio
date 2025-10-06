Basic portfolio sample

Files created:
- `index.html` — the main page (replace personal placeholders with your details)
- `styles.css` — small stylesheet used by `index.html`

How to open

PowerShell (from the project folder):

```powershell
ii .\index.html
```

Or double-click `index.html` in File Explorer.

Using your resume

The page currently links to your resume using an absolute file URL (`file:///C:/Users/britn/Downloads/BritsResume.pdf`). That works locally on your machine but won't work for others when you share the folder or deploy the site.

To make the resume link portable:

1. Copy `BritsResume.pdf` into the project folder (next to `index.html`).
2. Update the resume link in `index.html` to a relative link: `href="./BritsResume.pdf"`.

From PowerShell you can copy the file like this (run from any location):

```powershell
copy "C:\Users\britn\Downloads\BritsResume.pdf" "C:\Users\britn\OneDrive\Desktop\my-portfolio\BritsResume.pdf"
```

After copying, open `index.html` and change the two `file:///...` links to `./BritsResume.pdf` (or I can update it for you).

Next steps
- Replace placeholders (name, bio, contact) with your real info if you haven't already.
- Tell me if you'd like me to copy the resume for you and switch to a relative link — I can do that if you allow me to access the file path.