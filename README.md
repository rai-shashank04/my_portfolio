# Personal Portfolio - Shashank Rai

Welcome to the repository for my personal portfolio website. This site showcases my work experience, education, key analytics projects, and certifications.

## 🛠️ Technologies & Tools

- **Core**: React, Gatsby, Styled Components, GraphQL
- **Analytics & BI**: Microsoft Excel, Power BI, SQL
- **Styling**: Styled Components, Vanilla CSS
- **Deployment & Hosting**: GitHub Pages / Netlify

## 📁 Project Structure

- `content/featured/`: Contains key data analytics dashboard projects (Excel and Power BI).
- `content/jobs/`: Contains educational history (MBA at Maharishi University & B.Com at D.A.V. College).
- `content/projects/`: Contains professional certifications (Power BI, AI workflow automation, advanced Excel).
- `src/images/`: Images and brand logos (including the profile headshot `me.png`).

## 🚀 Development Guide

To run this project locally, ensure you have **Node.js** installed and follow these steps:

1. **Install Gatsby CLI globally** (if you haven't already):

   ```bash
   npm install -g gatsby-cli
   ```

2. **Install dependencies**:

   ```bash
   npm install --legacy-peer-deps
   ```

3. **Start the development server**:
   Since the project uses an older version of Webpack/Gatsby and Node 17+, you need to enable the legacy OpenSSL provider:

   ```bash
   # Windows PowerShell
   $env:NODE_OPTIONS="--openssl-legacy-provider"; npm run develop
   ```

   The site will load at `http://localhost:8000/`.

4. **Compile a production build**:
   ```bash
   $env:NODE_OPTIONS="--openssl-legacy-provider"; npm run build
   ```

## 🎨 Acknowledgements

Original template designed by Brittany Chiang.
