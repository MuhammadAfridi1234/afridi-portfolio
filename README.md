# Md. Afridi — Portfolio

Responsive personal portfolio built with HTML, CSS, and JavaScript. Includes the supplied portrait, downloadable CV, six selected projects, research, education, awards, and contact links. No build dependencies.

## Preview
Open index.html in a browser or use VS Code Live Server.

## Deploy on Netlify
1. Push this folder to the GitHub repository.
2. In Netlify, choose Add new project > Import an existing project > GitHub.
3. Select the portfolio repository and main branch.
4. Leave the build command empty. Set the publish directory to a single dot (.). netlify.toml also provides this setting.
5. Deploy. Future pushes to main will deploy automatically.

Alternatively, drag this folder into Netlify's manual deployment area. Include index.html, style.css, script.js, and assets.

## Files
- index.html: content, projects, contact links.
- style.css: responsive layout and light teal design.
- script.js: mobile navigation, project filtering, scroll progress.
- assets/profile.png: the user's supplied replacement photo.
- assets/AFRIDI-CV.docx: original CV download.
- netlify.toml: deployment settings and response headers.

## Verification
JavaScript syntax, internal anchors, unique HTML IDs, and local asset existence were checked. Menu and filter logic checks passed. Visual browser QA could not run because no browser was connected.
