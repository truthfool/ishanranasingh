# Portfolio Deployment Guide

This guide documents how to deploy your personal portfolio website for free.

## Option 1: GitHub Pages (Recommended)

Since you are a developer, this is the most professional and easiest way to host your portfolio directly from your code repository.

### Steps:

1.  **Create a Repository**:

    - Go to [GitHub.com](https://github.com) and create a new repository (e.g., `portfolio`).
    - **Public** is required for the free tier of GitHub Pages.

2.  **Push Your Code**:

    - Initialize git in your project folder:
      ```bash
      git init
      git add .
      git commit -m "Initial commit"
      ```
    - Link to your remote repository:
      ```bash
      git remote add origin https://github.com/truthfool/portfolio.git
      git branch -M main
      git push -u origin main
      ```

3.  **Enable GitHub Pages**:

    - Go to your repository **Settings** > **Pages**.
    - Under **Source**, select **Deploy from a branch**.
    - Under **Branch**, select `main` / `root`.
    - Click **Save**.

4.  **Live URL**:
    - Your live site will be at: [https://truthfool.github.io/ishanranasingh/](https://truthfool.github.io/ishanranasingh/)

---

## Option 2: Netlify (Drag & Drop)

1.  **Sign Up**: Go to [netlify.com](https://www.netlify.com/).
2.  **Deploy**: Drag and drop your project folder onto the dashboard.
3.  **Live URL**: You will get a customizable URL like `ishan-portfolio.netlify.app`.

---

## Technical Summary

- **Tech Stack**: HTML5, CSS3, JavaScript (Vanilla)
- **Hosting**: GitHub Pages (Recommended)
- **Cost**: Free Forever
