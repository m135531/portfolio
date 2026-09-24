# Mahnoor - Personal Portfolio

**Course:** CS344 Web Engineering  
**Section:** SE15A

This project is the updated personal portfolio for the CSS, project organization, Git, and GitHub Pages lab.

## Project Structure

```text
portfolio/
├── index.html
├── hobbies.html
├── contact.html
├── gallery.html
├── skills.html
├── css/
│   └── style.css
├── images/
│   ├── about-me.jpeg
│   ├── code.jpeg
│   ├── desk.jpeg
│   ├── desmos-graph.png
│   └── hobbies.jpeg
└── README.md
```

## Lab Requirements Implemented

- All styling is stored in `css/style.css`.
- No inline/internal CSS is used.
- No JavaScript is used.
- Navigation links are displayed horizontally using CSS floats.
- `float` and `clear` are used in navigation, page layouts, hobby cards, and gallery cards.
- The gallery contains at least five images.
- Images are stored in the `images/` folder.
- The home page is named `index.html` for GitHub Pages.

## Run Locally

Open `index.html` in a web browser.

## Git Commands

```bash
git init
git add .
git commit -m "Complete portfolio CSS and GitHub Pages lab"
git branch -M main
git remote add origin https://github.com/m135531/portfolio.git
git push -u origin main
```

If the repository already exists or has a different name, update the remote URL accordingly.

## GitHub Pages

1. Open the GitHub repository.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder.
5. Save and wait for GitHub Pages to publish the site.

If the repository is named `portfolio`, the expected addresses are:

- Repository: `https://github.com/m135531/portfolio`
- Live site: `https://m135531.github.io/portfolio/`

These links become valid only after the repository is created/pushed and GitHub Pages is enabled.
