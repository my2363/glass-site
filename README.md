# GLASS Honors Program Portfolio
 
A single-page portfolio site built for NYU's GLASS Honors Program, showcasing coursework, fieldwork, and growth across five core pillars.
 
Live site: https://my2363.github.io/glass-site (once GitHub Pages is enabled, see below)
 
## About
 
This site documents my journey through the GLASS Honors Program: leadership, service, global experience, academic milestones, and professional development, tracked year by year.
 
Author: Mohamed Youssef
Program: Electrical and Computer Engineering, Class of 2028
Contact: mohamed.youssef@nyu.edu, [LinkedIn](http://www.linkedin.com/in/mohamed-youssef16)
 
## Sections
 
- Hero intro and quick stats
- Five Core Pillars, tabbed portfolio entries across Global Competency, Service, Leadership, Academic Excellence, and Professional experience
- Timeline, year by year progress through the program (2025 to 2028)
- Contact, email, LinkedIn, and resume
## Tech stack
 
Plain HTML, CSS, and vanilla JavaScript. No frameworks, no build step. Fonts loaded from Google Fonts (Space Grotesk, Inter, JetBrains Mono).
 
## Project structure
 
```
glass-site/
├── index.html          (all markup, styles, and script in one file)
├── images/             (photos, headshot, and resume PDF)
├── README.md
└── .gitignore
```
 
## Running locally
 
No build tools required. Either open index.html directly in a browser, or serve it locally:
 
```bash
python3 -m http.server 8000
```
 
Then visit http://localhost:8000.
 
## Deployment
 
Hosted for free via GitHub Pages:
 
1. Go to this repo's Settings, then Pages
2. Under Source, select the main branch and / (root) folder
3. Save. The site will be live at https://my2363.github.io/glass-site within a couple of minutes
