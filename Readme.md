# Static Website Hosting with GitHub Pages

## Project Overview

This project demonstrates how to create and deploy a static website using HTML, CSS, Git, GitHub, and GitHub Pages. The website is hosted publicly and can be accessed through a GitHub Pages URL.

## Objectives

- Create a static website using HTML and CSS.
- Manage source code using Git and GitHub.
- Deploy the website using GitHub Pages.
- Customize the website with CSS styling.
- Learn the basics of static website hosting.

## Technologies Used

- HTML5
- CSS3
- Git
- GitHub
- GitHub Pages

## Project Structure

```text
github-pages-website/
├── index.html
├── style.css
└── README.md
```

## Features

- Responsive webpage layout
- Custom CSS styling
- Header, main content, and footer sections
- Hover effects on links
- Public hosting through GitHub Pages
- Version control using Git

## Deployment Steps

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/github-pages-website.git
cd github-pages-website
```

### 2. Preview Locally

Run a local development server using Python:

```bash
python3 -m http.server 8000
```

Open the following URL in your browser:

```text
http://localhost:8000
```

### 3. Push Changes to GitHub

```bash
git add .
git commit -m "Update website"
git push origin main
```

### 4. Enable GitHub Pages

1. Open the repository on GitHub.
2. Navigate to **Settings → Pages**.
3. Under Build and deployment, select **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder.
5. Click **Save**.
6. Wait for deployment to complete.

## Live Website

**Website URL:**
https://YOUR_USERNAME.github.io/github-pages-website/

**GitHub Repository:**
https://github.com/YOUR_USERNAME/github-pages-website

Replace `YOUR_USERNAME` with your GitHub username.

## What I Learned

- Creating a static website with HTML and CSS.
- Initializing and managing a Git repository.
- Pushing code to GitHub.
- Configuring GitHub Pages for deployment.
- Updating a live website through Git commits and pushes.

## Future Improvements

- Add a navigation bar.
- Improve mobile responsiveness.
- Add a projects section.
- Include social media and portfolio links.
- Enhance the design with animations and additional CSS.

## Author

**Ratnesh Vansh Saxena**

- GitHub: https://github.com/ratneshvansh13
- LinkedIn: https://www.linkedin.com/in/ratneshvansh13/

---

_Created as part of Task 6: Host a Static Website with GitHub Pages._
