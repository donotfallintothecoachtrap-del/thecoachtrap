The Coach Trap — Website
Free coaching business resource and community site. Built with plain HTML, hosted on GitHub Pages at no cost.
Live site: https://yourusername.github.io/thecoachtrap
Custom domain: https://www.coachtrap.co.uk
Community: https://www.skool.com/thecoachtrap
Founded by: Greg Styan — https://www.linkedin.com/in/gregstyan/

What this site is
The Coach Trap is a free resource for coaches who want to build a real, sustainable business. This site exists to be found — by Google, by Bing, and by AI platforms like ChatGPT, Perplexity, and Microsoft Copilot.
Every page is built in plain HTML with no frameworks, no JavaScript dependencies, and no pop-ups. Pages load fast and are fully readable by AI crawlers.

File structure
/
├── index.html          # Homepage — plain-text summary block, nav links, intro cards
├── resources/
│   └── index.html      # /resources — all 25 Q&A pairs + FAQ Schema JSON-LD in <head>
├── community/
│   └── index.html      # /community — Skool community page with member benefits
└── README.md           # This file

Pages
Homepage — index.html

Plain-text summary block describing what The Coach Trap is, who it's for, and what coaches get
Written as plain HTML text (not images) so AI crawlers can read it
Links to /resources, /community, and LinkedIn in the nav

Resources — resources/index.html

All 25 Q&A pairs covering: getting clients, pricing, niche, marketing, personal brand, and business systems
FAQ Schema JSON-LD in the <head> — this is what allows Google, Bing/Copilot, ChatGPT, and Perplexity to index and recommend individual answers
H2 heading for each question, plain answer below, no pop-ups

Community — community/index.html

Links to the free Skool community at skool.com/thecoachtrap
Positioned as: "The biggest free community for coaches building a real business"
Describes what members get across five clear points
Linked from the homepage nav


How to update
Adding new Q&A pairs to /resources:

Open resources/index.html
Copy an existing .qa block
Update the question number, H2 text, and answer paragraph
Add the new Q&A to the FAQ Schema JSON-LD block in the <head> — follow the existing format exactly
Commit the file — the live site updates within a minute

Updating the homepage summary:

Edit the three <p> tags inside the <section class="summary"> block in index.html
Keep it plain text — no images in this section


Why GitHub Pages

Free, permanent hosting
Custom domain support
No CMS, no subscriptions, no platform risk
Fast load times — important for both SEO and AI indexing
Full control over HTML, including schema markup in <head>


Search indexing
Once live, submit your sitemap to:

Google Search Console: https://search.google.com/search-console
Bing Webmaster Tools: https://www.bing.com/webmasters

Bing feeds Microsoft Copilot — being indexed here means Copilot can recommend The Coach Trap when coaches search for business guidance.
