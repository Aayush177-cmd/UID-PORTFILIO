# UID-PORTFILIO
A clean, dark-themed personal portfolio website built with pure **HTML** and **CSS**. No frameworks, no JavaScript — just semantic markup and modern CSS.
## Project Structure
portfolio
index.html      # Main HTML file
style.css       # All styles
README.md       # You're reading this

##  Getting Started
1. ""Download or clone"" the files into a folder.
2. Make sure `index.html` and `style.css` are in the **same folder**.
3. Open `index.html` in any browser — no build tools or server needed.
# Optional: serve locally with VS Code Live Server
# or just double-click index.html
## Sections
|Section |Description |

| Nav | Fixed top navbar with smooth scroll links |
| Hero | Full-screen intro with name, role, and CTA buttons |
| About | Bio text and a stat box showing months of experience |
| Skills | Tech stack cards grouped by category |
| Contact| Email, phone, and LinkedIn links |
| Footer | Credit line with name and year |
##  Design Tokens
All colors and fonts are defined as CSS variables in `:root` inside `style.css` — easy to change in one place.
css
:root {
  --bg:      #0a0a0f;   /* Page background */
  --surface: #111118;   /* Card background */
  --border:  #222230;   /* Borders */
  --yellow:  #f5e642;   /* Primary accent */
  --cyan:    #00f5d4;   /* Secondary accent */
  --pink:    #ff3cac;   /* Labels & highlights */
  --orange:  #ff6b35;   /* Tertiary accent */
  --text:    #e8e8f0;   /* Body text */
  --muted:   #6b6b80;   /* Muted / secondary text */
}
## Customisation
### Change your name
In `index.html`, update the nav logo and hero heading:
<html>
<div class="nav-logo">&lt;<span>YourName</span>.dev/&gt;</div>
<span class="name">Your Full Name</span>
### Change your location
</html>
<p>Currently based in <strong>Your City</strong> — open to remote opportunities.</p>
### Update contact links
html
<a href="mailto:your@email.com" class="contact-link"> Email me</a>
<a href="https://github.com/yourhandle" class="contact-link"> GitHub</a>
<a href="https://linkedin.com/in/yourprofile" class="contact-link">LinkedIn</a>
### Add or remove skill cards
Copy a `.skill-card` block in `index.html` and update the title and tags. The grid fills automatically.
### Change accent colors
Edit any variable in `:root` inside `style.css`:
css
--yellow: #your-color;
## Browser Support
Works in all modern browsers — Chrome, Firefox, Safari, Edge.  
The layout is responsive and adapts to screens below **768px**.
##Fonts Used
Loaded from Google Fonts — requires an internet connection to display correctly.
**Syne** — display / headings
**Space Mono** — monospace / labels and body text
html
<link href="https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&family=Syne:wght@400;700;800&display=swap" rel="stylesheet"/>
## License
Free to use and modify for personal projects.
*Built by Ayush Najbile · 2026*
