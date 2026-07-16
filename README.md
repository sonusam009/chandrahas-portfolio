Chandrahas Parmar — Portfolio Site
A single self-contained page (index.html) — no build step, no dependencies to install. resume.pdf is your resume, already wired up to the "Download résumé" buttons.
Fastest ways to host it (all free)
Option A — Netlify Drop (easiest, 1 minute)
Go to https://app.netlify.com/drop
Drag the whole portfolio folder (with both index.html and resume.pdf) onto the page.
You get a live URL instantly. You can add a custom domain later in Netlify settings.
Option B — GitHub Pages (free, good if you want a github.io URL)
Create a new GitHub repo, e.g. chandrahas-portfolio.
Upload index.html and resume.pdf to the repo root.
Go to Settings → Pages → set Source to "Deploy from branch", branch main, folder /root.
Your site goes live at https://<your-username>.github.io/chandrahas-portfolio/.
Option C — Vercel
Go to https://vercel.com/new
Import the folder (via GitHub repo or drag-and-drop with the Vercel CLI: npx vercel).
Deploy — Vercel gives you a live URL immediately.
Using a custom domain
All three options above let you attach a custom domain (e.g. chandrahasparmar.dev) for free — buy the domain from any registrar (Namecheap, GoDaddy, etc.) and point it per that platform's DNS instructions.
Editing content later
Everything is in index.html — search for the section you want (About, Stack, Changelog, Releases, Education, Contact) and edit the text directly. No compiling needed, just save and re-upload/re-deploy.
Replacing the resume PDF
Swap out resume.pdf with a newer version any time — keep the filename the same and the download buttons will keep working automatically.

