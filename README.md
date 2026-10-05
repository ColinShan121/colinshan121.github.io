# Colin Shan — Engineering Portfolio

Personal portfolio of Colin Shan, an Electrical Engineering student at
the University of Illinois Urbana-Champaign, graduating in May 2028.

Website: https://colinshan121.github.io

## Contents

- Freight Search: a FastAPI and PostgreSQL project featuring listing
  creation and updates, ranked full-text search, filters, and pagination.
- Medical imaging research at UT Southwestern.
- Bioprinting research at UT Dallas.
- Education, Illinois Space Society involvement, and programming skills.
- GitHub, LinkedIn, and email contact links.

Freight Search repository:
https://github.com/ColinShan121/freight-search-platform

## Technology

Static HTML and CSS hosted on GitHub Pages.
No dependencies or build step are required.

## Preview locally

Run from the website repository directory in WSL Ubuntu:

    python3 -m http.server 8000 --bind 127.0.0.1

Open http://localhost:8000 in your browser.
Stop the server with Ctrl+C.

## Edit and publish

Edit index.html and preview the changes locally. Check desktop and
mobile layouts, navigation, and external links before publishing.

    git add index.html README.md .nojekyll
    git commit -m "Update portfolio"
    git push origin main

GitHub Pages is configured to publish from main at the repository root.
Check the Pages deployment in GitHub Actions after pushing.

## Project structure

- index.html — portfolio content and styles
- .nojekyll — disables Jekyll processing
- README.md — repository overview and editing instructions

## Contact

Email: colinshan2007@gmail.com
LinkedIn: https://www.linkedin.com/in/colin-shan-7125b1384/
