# Personal Portfolio - Naveen

A simple, modern, lightweight, and responsive personal developer portfolio website designed for a Computer Science & Engineering (CSE) undergraduate specializing in Cyber Security with a passion for Artificial Intelligence and Machine Learning.

## 🚀 Built With

- **HTML5**: Semantic document structure
- **CSS3**: Modern responsive layout using Flexbox, CSS Grid, and custom CSS variables
- **Vanilla JavaScript**: Lightweight interactivity (mobile navigation menu, active link scroll highlighting, back-to-top button, dynamic footer year)

No external frameworks or heavy dependencies (Zero React, Zero Bootstrap, Zero Tailwind).

---

## 📁 Project Structure

```text
personal-portfolio/
│
├── index.html       # Main HTML markup with all 5 portfolio modules
├── style.css        # Custom responsive styling and dark navy design
├── script.js        # Vanilla JavaScript interactions
└── README.md        # Project documentation and guide
```

---

## 💻 How to Run Locally

Because this project is built using pure HTML, CSS, and JavaScript, it can be run immediately without any build steps or web servers.

### Option 1: Direct File Launch
Double-click `index.html` in your file explorer, or right-click `index.html` and choose **Open with** &rarr; your preferred browser (Chrome, Edge, Firefox, Brave, Safari).

### Option 2: Using VS Code Live Server (Optional)
If using Visual Studio Code:
1. Install the **Live Server** extension.
2. Right-click `index.html` and select **Open with Live Server**.

### Option 3: Using Python Built-in Server (Optional)
Open a terminal inside the project directory and run:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.

---

## ✏️ Placeholders to Replace With Your Real Information

Open `index.html` in your text editor and look for the marked placeholders to customize with your personal details:

1. **Projects Section (`#projects`)**:
   - `[Project Title 1: e.g., AI Threat Detection System]` &rarr; Your actual project title.
   - `[Editable Placeholder: Brief description...]` &rarr; Your project description and technologies used.
   - `https://github.com/your-username/project-1` &rarr; Link to your GitHub repository.
2. **Certificates Section (`.certificates-section`)**:
   - `https://example.com/certificate/placeholder-link` &rarr; Link to your IBM SkillsBuild certificate verification or PDF credential.
3. **Contact Section (`#contact`)**:
   - `mailto:your.email@example.com` &rarr; Your real email address.
   - `https://github.com/your-username` &rarr; Your GitHub profile URL.
   - `https://linkedin.com/in/your-profile` &rarr; Your LinkedIn profile URL.

---

## 🌐 Instructions for Uploading to GitHub

Follow these steps to publish your portfolio to GitHub:

1. **Initialize Git**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Naveen personal portfolio website"
   ```
2. **Create a Remote Repository**:
   - Go to [GitHub](https://github.com) and click **New Repository**.
   - Name it (for instance, `personal-portfolio` or `naveen-portfolio`).
   - Do not initialize with README, .gitignore, or license (already created locally).
3. **Push Local Code**:
   ```bash
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   git push -u origin main
   ```
4. **Deploy with GitHub Pages (Free Hosting)**:
   - On GitHub, navigate to your repository **Settings** &rarr; **Pages**.
   - Under **Build and deployment** &rarr; **Branch**, select `main` and root `/`.
   - Click **Save**. Your site will be live at `https://<your-username>.github.io/<your-repo-name>/`.
