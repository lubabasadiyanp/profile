# Personal Portfolio Website - Lubaba Sadiya N P

A clean, modern, and professional personal portfolio website for Lubaba Sadiya N P, MSc Data Analytics & Computational Science student.

---

## Folder Structure

This repository is kept completely minimal and modular in **one single page** to be directly uploaded to hosting platforms without any build steps:

```
portfolio/
├── index.html          # Core portfolio page (includes inline styles and scripts)
├── README.md           # Project documentation and deployment instructions
└── favicon.ico         # Favicon file
```

---

## Key Content Sections Included

- **Hero & Role**: Highlighting MSc coursework and details.
- **About**: Summarizing computation interests.
- **Projects**: Linking exact repositories:
  - `LogisticsShippingRates`
  - `Loan-Default-Risk-Classification-ML-Model`
  - `sentimental-analysis-of-product-review`
  - `WATER-QUALITY-CLASSIFICATION-FOR-SAFE-DRINKING-PREDICTION`
- **Research**: One paper marked clearly "In Progress".
- **Education**: Detailing Undergraduate Degree completed in 2025 and ongoing MSc.
- **Certifications**: Google Data Analytics Professional Certificate and two placeholder Course fields.
- **Skills**: List containing exact toolkit tags.
- **Contact**: GitHub and LinkedIn hooks.

---

## Deployment Steps on GitHub Pages

1. Create a public repository on GitHub named `portfolio` or `YOUR_USERNAME.github.io`.
2. Push this directory's files directly to the repository:
   ```bash
   git init
   git add .
   git commit -m "feat: setup clean data portfolio"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
   git push -u origin main
   ```
3. Go to the **Settings** tab of the GitHub repository.
4. On the left sidebar, click **Pages** (under "Code and automation").
5. Under **Build and deployment**, select **Deploy from a branch** as the source.
6. Under **Branch**, select **main** and `/ (root)`. Click **Save**.
7. Wait 1-2 minutes; your portfolio will be live at `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/`.
