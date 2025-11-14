# Personal Portfolio Website

A modern, responsive personal portfolio website showcasing projects, skills, and achievements.

## Features

- Responsive design for all devices
- Modern UI with smooth animations
- Project showcase with video embeds
- Skills section with technology icons
- Co-curricular activities gallery
- Resume PDF viewer modal
- Social media integration

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Swiper.js
- ScrollReveal

## GitHub Pages Setup

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `your-username.github.io` (replace `your-username` with your GitHub username) OR any name you prefer
3. Do NOT initialize with README, .gitignore, or license

### Step 2: Push Your Code to GitHub

```bash
# Add your GitHub repository as remote (replace with your repository URL)
git remote add origin https://github.com/your-username/your-repo-name.git

# Rename branch to main (if needed)
git branch -M main

# Push to GitHub
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings**
3. Scroll down to **Pages** section (in the left sidebar)
4. Under **Source**, select **Deploy from a branch**
5. Select **main** branch and **/ (root)** folder
6. Click **Save**

### Step 4: Access Your Website

- If repository name is `your-username.github.io`: Your site will be available at `https://your-username.github.io`
- If repository name is different: Your site will be available at `https://your-username.github.io/repository-name`

**Note:** It may take a few minutes for the site to be live after enabling GitHub Pages.

## Local Development

Simply open `index.html` in your web browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server
```

Then visit `http://localhost:8000` in your browser.

## Customization

- Update personal information in `index.html`
- Modify colors in `assets/css/main.css` (CSS variables)
- Add your own images to `assets/img/`
- Update social media links in the navigation and footer

## License

© 2025 Taufique's Code. All Rights Reserved.

