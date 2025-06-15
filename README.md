SES‑Website
Official website for the Space Exploration Society (SES) at IIT Bhilai for the academic year 2025–26. A Jekyll-based static site showcasing society initiatives, team members, portfolio, and event highlights.

🚀 Features
Landing page with hero banners and navigation

About & legal pages (e.g. legal.md)

Portfolio section to showcase projects/events

Custom Jekyll theme forked from raviriley/agency-jekyll-theme

Responsive layout with SCSS styling and JavaScript enhancements

SEO-friendly structure via _includes, _layouts, and _data

📁 Repository Structure
.
├── _config.yml        # Jekyll configuration
├── _data/             # Data files (e.g. navigation, people)
├── _includes/         # Reusable HTML snippets
├── _layouts/          # Layout templates
├── _pages/            # Static pages (About, Contact, etc.)
├── _portfolio/        # Portfolio entries
├── assets/            # Images, JS, SCSS
├── Gemfile            # Jekyll and plugin dependencies
├── fix-assets.sh      # Script: fix asset paths
├── fix-links.sh       # Script: update internal links
├── index.md           # Home page content
├── legal.md           # Legal & privacy information
└── 404.html           # Custom “Page not found”
🛠️ Setup & Deployment
Prerequisites
Ruby & Bundler (gem install bundler)
Jekyll (bundle install will include it)

Run Locally
git clone https://github.com/Ashish‑Kumar‑Dash/SES‑Website.git
cd SES‑Website
bundle install
bundle exec jekyll serve
Then visit http://localhost:4000/ in your browser.

Deployment
Static site—can be deployed via GitHub Pages, Netlify, or any static host:

For GitHub Pages, push to the main branch (or turn on GH Pages in repo settings).

For Netlify, connect the repo and set the build command to jekyll build (or let Netlify auto-recognize Jekyll).

🧩 Customization
Content: Add or modify files in _pages, _portfolio, or _data.

Theme/Styling: Edit SCSS under assets/ or tweak layout templates in _layouts/.

Scripts: Re-run fix-assets.sh or fix-links.sh post-renaming/moving files.

🤝 License & Contribution
License: MIT 
Contributions welcome! Feel free to open issues or pull requests.
