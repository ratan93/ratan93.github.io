# Ratneshwar Singh | Mobile & AI Engineering Portfolio
A responsive, single-page portfolio presenting iOS/mobile engineering, Kotlin Multiplatform (KMP), technical leadership, and applied AI work.
Contents
- index.html - Portfolio website (HTML, CSS, and lightweight JavaScript; no build step required).
- Ratneshwar_Singh_iOS_Engineer_AI.pdf - Resume PDF linked from the site's Download CV button.
Run locally
No dependencies or build tools are needed.
1. Download or clone this folder.
2. Open index.html in a browser.
   Or run a local static server from this directory:
   python3 -m http.server 8000
   Then visit http://localhost:8000.
Publish online
GitHub Pages
1. Create a GitHub repository and upload both files in this folder.
2. Open Settings → Pages.
3. Under build/deployment, select Deploy from a branch.
4. Choose the main branch and / (root), then save.
5. Wait for the deployment and open the Pages URL shown in Settings.
Vercel
1. Import the repository into Vercel.
2. Select the static site/framework preset or Other.
3. Leave build command and output directory empty if prompted (the root index.html is the site entry point).
4. Deploy.
Customize before publishing
Review index.html and update any details that need more precision, especially:
- Experience dates and role titles.
- Project descriptions, ownership, and impact metrics.
- Project/demo links, screenshots, and any work that is safe to share publicly.
- Contact details and social/profile links.
Do not publish confidential client details, internal architecture, private screenshots, or unapproved company information.
Notes
- Keep the resume PDF in the same folder as index.html. The CV link uses a relative path: ./Ratneshwar_Singh_iOS_Engineer_AI.pdf.
- The portfolio is responsive and uses no external runtime dependencies.
