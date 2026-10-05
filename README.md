# Colin Shan — Engineering Portfolio

Static HTML/CSS portfolio. No dependencies or build step.

## Publish
Use the public repository `ColinShan121/colinshan121.github.io`.
Put `index.html` and `.nojekyll` in its root. In Settings → Pages,
select Deploy from a branch → main → /(root) → Save.

## Edit locally (WSL)
```bash
cd /home/colin/projects
git clone git@github.com:ColinShan121/colinshan121.github.io.git
cd colinshan121.github.io
code .
python3 -m http.server 8000 --bind 127.0.0.1
```
Open http://localhost:8000. After editing, review desktop and phone widths.
Stop the server with Ctrl+C, then:
```bash
git add index.html .nojekyll README.md
git commit -m "Update engineering portfolio"
git push origin main
```
Wait for the Pages deployment to succeed, then check the live page.

## Content accuracy
Research and education follow the supplied resume. Backend progress follows
Colin's reported local validation on October 4, 2026. No backend repository URL,
hosted demo, performance benchmark, or planned feature is presented as complete.
The original resume PDF is excluded because it includes a phone number.
