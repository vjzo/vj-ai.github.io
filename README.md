# vjzo.github.io — Personal AI Portfolio

🎯 **Live Site:** [https://vjzo.github.io](https://vjzo.github.io)

This is the personal AI resume and portfolio website of **Vijay**, an experienced AI & Data Scientist with 8+ years of industry expertise in building intelligent, production-grade machine learning systems.

Built with the [`startbootstrap-resume`](https://github.com/StartBootstrap/startbootstrap-resume) template and customized to showcase real-world projects, visualizations, and experience in:

- Generative AI (LLMs, RAG, Diffusion)
- Prompt Engineering & Fine-Tuning
- MLOps & Cloud-Native Pipelines
- Autonomous Agentic Systems
- AWS, GCP, Databricks, Snowflake
- NLP, ARIMA, Bayesian Modeling
- Python, SQL, Tableau, Power BI

---

## 🚀 Getting Started Locally

> To run this site locally and make changes:

```bash
# 1. Clone the StartBootstrap source repo (not this one)
git clone https://github.com/StartBootstrap/startbootstrap-resume.git
cd startbootstrap-resume

# 2. Install dependencies
npm install

# 3. Start development server
npm start
```

This opens a live-preview server. Edit content in `src/pug/index.pug`, save, and the site auto-refreshes.

---

## 🛠️ Building and Deploying

To publish updates to `vjzo.github.io`:

```bash
# 1. Build the project (from startbootstrap-resume directory)
npm run build

# 2. Copy the generated site to this repo
cp -r dist/* ../vjzo.github.io/

# 3. Push changes
cd ../vjzo.github.io
git add .
git commit -m "Update site"
git push origin main
```

---

## 📁 Repository Structure

This repository **only contains the built static website** (`index.html`, `css/`, `js/`, etc.) — ideal for GitHub Pages hosting.

If you're looking for the editable source files, work out of the original `startbootstrap-resume` folder.

---

## 📸 Customization Features

- Fully personalized resume layout
- Icon-based skills section (Databricks, Snowflake, GCP, etc.)
- Real-time project links and visualizations
- Font Awesome & custom SVG icons support
- Responsive design (mobile-friendly)

---

## 📅 Last Updated
July 18, 2025

---

## 🧠 Credits
- Theme by [Start Bootstrap](https://github.com/StartBootstrap/startbootstrap-resume)
- Deployed using [GitHub Pages](https://pages.github.com/)
