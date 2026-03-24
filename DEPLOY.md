# 🚀 Portfolio Deployment Guide

Congratulations! Your portfolio is ready for the world. Follow these steps to host it for free on **GitHub Pages** or **Vercel**.

---

## 1. Hosting on GitHub Pages (Recommended)
GitHub Pages is perfect for static portfolios.

1. **Create a GitHub Repository**:
   - Go to [github.com](https://github.com) and create a new repository named `portfolio`.
2. **Upload your files**:
   - Upload the contents of your `portfolio` folder to the repository.
   - Files to include: `index.html`, `favicon.png`, `CV_ROBERT_ICARO.pdf`, and the `assets/` folder.
3. **Enable GitHub Pages**:
   - Go to **Settings** > **Pages**.
   - Under "Branch", select `main` and `/ (root)`.
   - Click **Save**.
4. **Visit your site**:
   - Your site will be live at `https://[your-username].github.io/portfolio/`.

---

## 2. Hosting on Vercel (Fast & Professional)
Vercel offers faster loading speeds and automatic deployments.

1. **Sign up**: Go to [vercel.com](https://vercel.com) and sign up with your GitHub account.
2. **Import Project**:
   - Click **Add New** > **Project**.
   - Import your GitHub repository.
3. **Deploy**:
   - Vercel will automatically detect your project and deploy it.
4. **Visit your site**:
   - You'll get a custom `vercel.app` domain immediately!

---

## 3. Best Practices for Maintenance
- **Updating CV**: Simply replace `CV_ROBERT_ICARO.pdf` with the new version and re-upload/git push.
- **Adding Projects**: Open `index.html`, copy an existing project card block, and update the details.
- **Visuals**: If you change `style.css`, remember to update the `?v=4.0` cache-buster in `index.html` (e.g., to `v=5.0`) to ensure returning visitors see the newest version.

---

**Built with pride by Robert N. Icaro** 🚀
