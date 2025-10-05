# 🌐 Resume Template — by [Rajat Dua](https://www.linkedin.com/in/rajatdua91/)

A **modern, responsive résumé website** built entirely with **HTML, CSS**, and a touch of **Liquid templating** — perfect for GitHub Pages or Jekyll.  
Fork this repo to create your own **personal or professional résumé site** in minutes.

---

## 🧩 Features

- 📄 **Clean & professional** design (print-friendly)  
- 🎨 **Easy customization** — edit HTML or data files directly  
- 📱 **Fully responsive** on mobile and desktop  
- 🧠 **Modular sections** — Work Experience, Education, Projects, Skills  
- 🔒 **No build tools or dependencies required**  
- ☁️ **Deploys instantly** on GitHub Pages  

---

## 🚀 Getting Started

### 1️⃣ Fork This Repository  
Click the **“Fork”** button in the top-right corner to create a copy under your GitHub account.

### 2️⃣ Clone Your Fork  
```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
````

### 3️⃣ Customize Your Information

Open `index.html` in any text editor and update the following sections:

| Section             | Description                                    |
| ------------------- | ---------------------------------------------- |
| **Header**          | Update your name, title, and contact links     |
| **Work Experience** | Each `<details>` card represents a job         |
| **Education**       | Update degrees and institutions                |
| **Projects**        | List your key accomplishments                  |
| **Skills**          | Add your core technical or professional skills |

🖼️ **Profile Photo:**
Replace this line in the header with your own image URL:

```html
<img src="your-photo-url.jpg" alt="Your Name" class="profile-photo" />
```

---

## 🌍 Deploy to GitHub Pages

1. Go to your repository **Settings → Pages**
2. Under **Build and Deployment**, set:

   * **Source:** Deploy from a branch
   * **Branch:** `main` → `/ (root)`
3. Click **Save**

Your site will be live shortly at:
➡️ **https://<your-username>.github.io/<your-repo-name>/**

---

## 🧱 File Structure

```
.
├── index.html          # Main resume layout
├── assets/
│   ├── css/
│   │   └── styles.css   # Core styling for all sections
│   └── images/          # Profile photo & icons
├── README.md            # You're reading this!
└── _config.yml          # (Optional) Jekyll/GitHub Pages config
```

---

## 🪄 Optional Enhancements

* 🖼️ Add a favicon → `assets/images/favicon.png`
* 📊 Integrate Google Analytics or Plausible
* 🧾 Export as PDF directly from browser (print-optimized)
* 📥 Add a “Download Résumé” button using `<a download>`
* 🌗 Add dark mode support with a simple CSS toggle

---

## 💡 Tips for Best Results

* Keep each bullet point under **two lines**
* Use **strong action verbs** — *Led, Designed, Automated, Built*
* Quantify results — *reduced processing time by 40%, saved $100K/year*
* Always **test on mobile** and **print preview** before publishing

---

## 🧑‍💻 About

**Created by:** [Rajat Dua](https://www.linkedin.com/in/rajatdua1991/)
*Senior Manager, Enterprise Architect @ Otis Elevator Company*

> Built to share a clean, developer-friendly résumé structure anyone can reuse.

---

## 📜 License

This project is licensed under the **MIT License** — feel free to use, modify, and share with attribution.

---

> 💬 *“A good résumé doesn’t just tell your story — it shows your impact.”*
