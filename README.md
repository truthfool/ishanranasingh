# Portfolio Deployment Guide

This guide documents how to deploy your personal portfolio website for free. All recommended options below offer a persistent "free forever" tier for personal static sites.

## Option 1: GitHub Pages (Recommended)

Since you are a developer, this is the most professional and easiest way to host your portfolio directly from your code repository.

### Steps:

1.  **Create a Repository**:

    - Go to [GitHub.com](https://github.com) and create a new repository (e.g., `portfolio`).
    - **Public** is required for the free tier of GitHub Pages (unless you have Pro).

2.  **Push Your Code**:

    - Initialize git in your project folder if you haven't already:
      ```bash
      git init
      git add .
      git commit -m "Initial commit"
      ```
    - Link it to your remote repository:
      ```bash
      git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
      git branch -M main
      git push -u origin main
      ```

3.  **Enable GitHub Pages**:

    - Go to your repository **Settings** > **Pages** (on the left sidebar).
    - Under **Build and deployment** > **Source**, select **Deploy from a branch**.
    - Under **Branch**, select `main` and `/ (root)`.
    - Click **Save**.

4.  **Live URL**:
    - Your site will be live at `https://YOUR_USERNAME.github.io/portfolio/` in a few minutes.
    - _Tip_: If you name your repository exactly `YOUR_USERNAME.github.io`, your URL will be just `https://YOUR_USERNAME.github.io` (cleaner).

---

## Option 2: Netlify (Drag & Drop)

Netlify is incredibly fast and offers a very generous free tier.

### Steps:

1.  **Sign Up**: Go to [netlify.com](https://www.netlify.com/) and sign up (free).
2.  **Deploy**:
    - Log in to your dashboard.
    - Go to the **Sites** tab.
    - Drag and drop your entire `simple-portfolio` folder area onto the box that says "Drag and drop your site output folder here".
3.  **Live URL**:
    - Netlify will deploy it instantly and give you a random URL (e.g., `funny-name-123456.netlify.app`).
    - Click **Site configuration** > **Change site name** to make it something like `ishan-portfolio.netlify.app`.

---

## Option 3: Vercel

Vercel is optimized for frontend frameworks but works perfectly for static HTML sites too.

### Steps:

1.  **Sign Up**: Go to [vercel.com](https://vercel.com/) and sign up.
2.  **Import**:
    - Install Vercel CLI `npm i -g vercel` and run `vercel` in your folder, OR
    - Connect your GitHub account on the Vercel dashboard and click **Add New** > **Project** > Import your portfolio repository.
3.  **Deploy**:
    - Keep all build settings default (Framework Preset: Other).
    - Click **Deploy**.
4.  **Live URL**:
    - You will get a `your-project.vercel.app` URL.

---

## Technical Summary

- **Tech Stack**: HTML5, CSS3, JavaScript (Vanilla)
- **Hosting**: Static Hosting (GitHub Pages / Netlify / Vercel)
- **Cost**: $0.00 / month (Free Tier)
