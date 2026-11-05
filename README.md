# 🪔 #HarRangMeinJECRC - Personalized Diwali Card Generator

A lightweight, high-performance web tool for the JECRC community to generate personalized Diwali greeting cards. Recipients can enter their **Name** and **Department / Designation**, see an instant live preview, and download a crystal-clear, high-resolution PNG card to share on WhatsApp, LinkedIn, Instagram, or Email.

---

## 📁 Repository Structure

```
HarRangMeinJECRC-card/
├── index.html        # Single-page interactive web application
├── template.jpg      # Base Diwali card template (1254 × 1254 web-optimized)
└── README.md         # Deployment & hosting guide
```

---

## 🚀 How to Host on GitHub Pages (Free, in 2 Minutes)

Follow these simple steps to deploy this tool online so anyone can access it via a link:

### Step 1: Create a New GitHub Repository
1. Go to [github.com/new](https://github.com/new).
2. Repository name: `har-rang-mein-jecrc` (or any name you prefer).
3. Set visibility to **Public**.
4. Leave "Add a README file" **unchecked**.
5. Click **Create repository**.

### Step 2: Push This Folder to GitHub
Open your terminal and run:

```bash
cd "/Users/meydivyansh/Desktop/HarRangMeinJECRC-card"

# Initialize git repository
git init
git add .
git commit -m "Initial release: #HarRangMeinJECRC Card Generator"

# Rename branch to main
git branch -M main

# Link to your GitHub repository (replace with your actual GitHub username)
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/har-rang-mein-jecrc.git

# Push the code
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub.
2. Click **Settings** (gear icon at the top).
3. In the left sidebar, click **Pages** (under "Code and automation").
4. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: Select **`main`** and folder **`/ (root)`**
   - Click **Save**.
5. Within 1–2 minutes, GitHub will give you your live URL:
   ```
   https://YOUR_GITHUB_USERNAME.github.io/har-rang-mein-jecrc/
   ```

---

## ✉️ Ready-to-Send Email Template

You can copy and send this announcement email to students, faculty, and alumni:

```text
Subject: ✨ Celebrate Diwali with #HarRangMeinJECRC — Get Your Personalized Greeting Card!

Dear JECRC Family,

May the auspicious festival of lights bring prosperity, joy, and endless opportunities to you and your loved ones.

As we celebrate the unity and spirit of our community this Diwali, we invite each of you to create your official personalized JECRC Diwali greeting card:

👉 Click here to generate your card: https://dsjangid.github.io/harrangmeinjecrc/

Simply enter your Name and Department/Designation, and click "Download High-Res PNG" to save your customized card. Share it across WhatsApp, LinkedIn, and Instagram with the hashtag #HarRangMeinJECRC!

Wishing you and your family a very Happy and Prosperous Diwali!

Warm regards,
JECRC
```

---

## 🎨 Specifications & Typography

- **Canvas Resolution**: `3919 × 3919` px (Full High Definition)
- **Primary Text Color**: `#013b2d` (Deep Emerald Green)
- **Name Font**: `Montserrat SemiBold` (600 weight)
- **Department Font**: `Montserrat Regular` (400 weight)
- **Export Format**: Lossless `.png`
- **Features**:
  - Live interactive preview
  - Fine-tuning sliders (font size, position, spacing)
  - Auto-wrapping for long department names
  - One-click copy to clipboard
  - Native mobile sharing support
