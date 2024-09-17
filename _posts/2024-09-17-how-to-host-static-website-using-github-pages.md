---

title: How to Host a Static Website Using GitHub Pages  
description: A simple guide to hosting a static website with GitHub Pages.  
Author: CSEdge
date: 2024-09-17  
categories: [Development, Guide]  
tags: [GitHub Pages, Hosting, Static Website]  
image:  
  path: /assets/img/github-pages.webp 
  alt: GitHub Pages hosting  

---

## What is GitHub Pages?

GitHub Pages is a free service provided by GitHub that allows you to host static websites directly from a GitHub repository. It’s ideal for personal projects, portfolios, or documentation.

## Why Use GitHub Pages?

- **Free Hosting**: GitHub Pages is completely free.
- **Easy Setup**: No server management required.
- **Custom Domains**: You can use a custom domain if needed.

## Step-by-Step Guide

### 1. Create a GitHub Repository
To host your site, you need to first create a repository on GitHub.

- Go to [GitHub](https://github.com) and log in.
- Click on the **New Repository** button.
- Name your repository (e.g., `my-website`).
- Initialize it with a `README.md` file.

### 2. Upload Your Website Files
Your static website consists of HTML, CSS, and JavaScript files. You can upload them via GitHub’s interface or push them through Git using the following commands:

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/yourusername/your-repository.git
git push -u origin master
```

### 3. Enable GitHub Pages
After uploading your files:

- Go to the **Settings** of your repository.
- Scroll down to the **Pages** section.
- Select the branch (typically `main` or `master`) and the root directory to serve your site.
- GitHub will provide a URL where your site will be hosted (e.g., `https://yourusername.github.io/your-repository`).

### 4. Access Your Website
Once the Pages settings are configured, your website will be live at the provided URL.

## Optional: Use a Custom Domain
If you have a custom domain, you can point it to your GitHub Pages site by creating a `CNAME` file in the root of your repository and setting up DNS records with your domain provider.

## Conclusion
Hosting a static website using GitHub Pages is a straightforward process that provides free and reliable hosting for your projects. It's an excellent solution for developers looking to quickly deploy websites without the hassle of managing servers.
