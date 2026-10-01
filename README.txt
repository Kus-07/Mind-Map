MindMate v3 (AI-powered) — project folder

Upload ALL of these files and folders to a GitHub repository, then connect it to Netlify.
Full steps: MindMate_v3_AI_Setup_Guide (PDF/Word).

  index.html            the app
  netlify/functions/    the AI brain (calls Claude through Netlify AI Gateway — no API key needed)
  package.json          tells Netlify to install the Claude library
  netlify.toml          tells Netlify where things are
  manifest.webmanifest, sw.js, icon-192.png, icon-512.png   phone-app install + offline

Optional Netlify environment variables: MODEL (default claude-sonnet-5), COURSE_NOTES (extra guidance, e.g. your counsellor's contact).
