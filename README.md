Sreenivas Vinnakota — AI Product Portfolio
A static, responsive portfolio designed for GitHub Pages. All pages work without a JavaScript build system or API keys. The simulated sourcing walkthrough runs entirely in the browser using fictitious example information.
What is in this version
Home (`index.html`) — Featured projects with Autonomous Sourcing Agent first, Agentic Employee Records second, plus professional experience, education, certifications and recruiter contact.
Autonomous Sourcing Agent (`projects/autonomous-sourcing-agent/index.html`) — Dedicated case study covering tail-spend problem discovery, user personas, buyer journey, four-agent solution design, Level 2 human approval gates, MVP boundaries, evaluation and success metrics.
Sourcing walkthrough (`projects/autonomous-sourcing-agent/prototype.html`) — Interactive simulated buyer flow, with three mandatory human gates and a sample supplier award; it does not connect to a live procurement system.
Agentic Employee Records (`projects/agentic-employee-records/index.html`) — Dedicated case study covering HR and compliance pain points, user journey, four proposed agents, human review, MVP prioritization and pilot evaluation strategy. Links to the working demo and the presentation PDF.
`assets/` — Stylesheets, product cover, product review PDF and a public-resume PDF.
```text
index.html
README.md
assets/
    site.css
    case-study.css
    agentic-employee-records-cover.webp
    agentic-employee-records-product-review.pdf
    sreenivas-vinnakota-resume.pdf
projects/
    autonomous-sourcing-agent/
        index.html
        prototype.html
    agentic-employee-records/
        index.html
```
Publish to GitHub Pages
Extract the complete ZIP on your computer. Do not upload the ZIP itself as a single repository file.
Open your portfolio repository on GitHub: https://github.com/vasuart-cloud/ai-product-portfolio (or whichever repository hosts your GitHub Pages site).
On the repository's main branch, upload/replace the contents of this folder. Preserve exactly the `assets/` and `projects/` subfolder structure. You can do this in the browser by using Add file → Upload files and dragging in the contents from the extracted folder, or push the entire folder with Git.
Click Commit changes to save.
Under Settings → Pages, choose Deploy from a branch → main → / (root), then Save, if it is not already configured.
Once GitHub completes the deployment, open the link shown under Pages. For the suggested repository path, the address is https://vasuart-cloud.github.io/ai-product-portfolio/.
Test the two Read complete case study links, the Try simulated sourcing walkthrough link, the live Agentic Employee Records demo and its presentation PDF, LinkedIn, and resume.
External links
Public Agentic Employee Records demo: https://agentic-employee-record.vercel.app/
LinkedIn: https://www.linkedin.com/in/vasuart/
Independent project GitHub: https://github.com/vasuart-cloud/Agentic-Employee-Record
Important publishing notes
Privacy & intellectual property: The employer-facing Autonomous Sourcing Agent case study was rewritten as a high-level, generalized product concept. Original private PRDs and leadership decks are not in this package or linked publicly. Before posting, personally check that all descriptions, metrics, and examples are approved for disclosure.
Claim accuracy: Sourcing workflow and its browser demo are labeled a concept/simulation, not a production launch. Employee Records has a working public frontend prototype; its enterprise integrations and proposed outcomes are not represented as shipped. No specific pilot outcome is implied without proof.
Portrait: The homepage uses your public GitHub avatar as a placeholder. To use your chosen photo, upload `assets/profile-photo.jpg` and change the hero image `src` in `index.html` to `assets/profile-photo.jpg`.
Resume: The included publicly shareable PDF has its phone number redacted. Review the email and the remaining personal details before you publish it.
Site security: The site is static, contains no secrets or API keys, and sends no visitor details to a backend. Enable two-factor authentication on GitHub and Enforce HTTPS on Pages. Any new AI-backed live demo should use a separate server with access control, rate limits, and server-side keys.
