# Dreamy-San.github.io

Personal website hosting my resume and certificates.

## 🔗 Links
- **LinkedIn**: [linkedin.com/in/micah-scott-jr](https://linkedin.com/in/micah-scott-jr)
- **GitHub**: [github.com/Dreamy-San](https://github.com/Dreamy-San)

## 🚀 GitHub Pages Setup

A GitHub Actions workflow has been configured to automatically deploy this site to GitHub Pages. To complete the setup:

1. **Enable GitHub Pages in Repository Settings:**
   - Go to your repository settings: https://github.com/Dreamy-San/Dreamy-San.github.io/settings/pages
   - Under "Build and deployment", set **Source** to **GitHub Actions**
   - Save the settings

2. **Merge this PR to the main branch** to trigger the deployment workflow

3. Once deployed, your site will be accessible at: **https://dreamy-san.github.io**

The workflow is configured to automatically deploy whenever changes are pushed to the `main` or `master` branch.

## 📄 Adding Your Resume and Certificates

Your resume and certificates are already in the repository:
- Resume: `resume.pdf`
- Certificates: Files in the `certificates/` folder

## 🚀 Local Development

To preview the site locally:
```bash
python3 -m http.server 8080
```
Then open http://localhost:8080 in your browser.
