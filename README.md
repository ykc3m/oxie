🌟 Oxie.Club - Minecraft Server Discovery
Discover, join, and share the best Minecraft servers!
Welcome to Oxie.Club, a vibrant platform for Minecraft players to find and explore top-tier servers. Whether you’re into survival, minigames, factions, or pixelmon, our site makes it easy to discover servers with real-time status updates, player counts, and community-driven suggestions. Built with React and styled with Tailwind CSS, Oxie.Club offers a sleek, purple-themed interface that’s as fun to use as a freshly crafted diamond pickaxe! 🪓

✨ Features

Server Discovery: Browse a curated list of 50+ Minecraft servers with details like name, IP, Discord link, description, and tags (e.g., survival, skyblock, PvP).
Real-Time Status: Check server status and player counts using the MCSrvStat API.
Robust Icon Loading: Server icons load reliably with exponential backoff retries and a fallback image for seamless UX.
Search & Filter: Find servers by name, IP, tags, minimum players, or online/offline status.
Pagination: Navigate through servers with ease, 10 per page.
User Profiles: Create a persistent profile (stored in localStorage) to submit server suggestions without re-logging in.
Community Suggestions: Suggest new servers via a simple form, stored locally for admin review.
Social Integration: Join our Discord, follow us on TikTok, and check out Instagram for updates and community fun!
Support Us: Keep the site running with a donation via Ko-fi.

🖼️ Screenshot
Explore servers with a sleek, purple-themed interface!
🚀 Getting Started
Follow these steps to set up the project locally or deploy it to Vercel.
Prerequisites

Node.js (v16 or higher)
Git
A Vercel account for deployment

Installation

Clone the Repository:
git clone https://github.com/YOUR_USERNAME/oxie.club.git
cd oxie.club


Install Dependencies:The project uses CDN-hosted dependencies (React, ReactDOM, Tailwind CSS) in index.html, so no local npm install is needed for the static app.

Run Locally:

Use a local server (e.g., VS Code Live Server or Python’s HTTP server):python -m http.server 8000


Open http://localhost:8000 in your browser to view the site.


Customize the Logo:

Replace the placeholder favicon and site icon (https://via.placeholder.com/32?text=MC) in index.html:<link rel="icon" href="https://your-cdn.com/favicon.png" type="image/png">
<img src="https://your-cdn.com/favicon.png" alt="Website Icon" className="w-8 h-8 mr-2" />


Upload your logo (e.g., generated via Looka) to the project folder (e.g., favicon.png) or a CDN (e.g., Imgur).


Deploy to Vercel:

Push the repository to GitHub:git add .
git commit -m "Initial commit"
git push origin main


In Vercel, create a new project, link your GitHub repo, and deploy. No build settings are needed for this static site.
Update the logo and donation link (https://ko-fi.com/oxied_site) in index.html before deploying.



📚 Usage

Browse Servers: Use the search bar, player count filter, status dropdown, or tag selector to find servers.
Create/Edit Profile: Click the profile icon (top-left) to set up or edit your username, email, and profile picture. Profiles persist across sessions via localStorage.
Suggest a Server: Fill out the suggestion form in the footer (requires a profile). Suggestions are stored in localStorage for admin review.
Join the Community: Connect via Discord, TikTok, or Instagram.
Support Us: Donate via Ko-fi to keep the site running!

🛠️ Contributing
We’d love your help to make Oxie.Club even better! Here’s how to contribute:

Fork the Repository:

Click “Fork” on the GitHub page and clone your fork:git clone https://github.com/YOUR_USERNAME/oxie.club.git




Create a Branch:
git checkout -b feature/your-feature-name


Make Changes:

Edit index.html or add new files (e.g., assets for logos).
Test locally using a simple HTTP server.


Submit a Pull Request:

Push your branch:git push origin feature/your-feature-name


Open a PR on GitHub with a clear description of your changes.



Contribution Ideas

Add a backend (e.g., Node.js with MongoDB) for server and suggestion management.
Implement server icon caching to reduce MCSrvStat API calls.
Enhance the suggestion system with admin approval workflows.
Add sorting options (e.g., by player count or alphabetical order).
Improve accessibility (e.g., ARIA labels, keyboard navigation).

📜 License
This project is licensed under the MIT License.
🙌 Acknowledgments

MCSrvStat API for server status and icons.
React and Tailwind CSS for the frontend.
Vercel for hosting.
Our amazing community on Discord, TikTok, and Instagram!

📬 Contact

Discord: https://discord.gg/oxied
Email: oxiedsite@gmail.com
Issues: Open a GitHub issue


🌍 Happy exploring!
