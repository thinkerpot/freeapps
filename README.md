# 🎯 FreeApps – Free App Download Center

Welcome to **FreeApps**, a blazing-fast, SEO-friendly website for listing and downloading the best free desktop & mobile applications. Built with simplicity, performance, and scalability in mind. Powered by Astro + Tailwind + Markdown.

> 📦 Repo: `thinkerpot/freeapps`  
> 🚀 Demo: [freeapps.educentrals.com](https://freeapps.educentrals.com) (example)

---

## ✨ Features

- 🧠 Simple and intuitive UI for app discovery  
- ⚡ Static site – ultra fast and lightweight  
- 🔍 SEO-optimized with meta tags and Open Graph  
- 🌙 Dark Mode support  
- 🎯 Integrated with GitHub for auto updates  
- 🖼️ Each app page supports screenshots, descriptions, download links, and more

---

## 📁 Project Structure

```
/
├── public/             # Static assets (images, icons, etc)
├── src/
│   ├── content/        # Markdown-based app listings
│   ├── components/     # UI components (cards, navbar, etc)
│   ├── layouts/        # Layout templates
│   └── pages/          # Routes for homepage, categories, etc
├── astro.config.mjs    # Astro config file
└── package.json        # Project metadata + dependencies
```

---

## 🚀 Getting Started (Local Setup)

1. **Clone the repo**

```bash
git clone https://github.com/thinkerpot/freeapps.git
cd freeapps
```

2. **Install dependencies**

```bash
npm install
```

3. **Run locally**

```bash
npm run dev
```

4. **Build for production**

```bash
npm run build
```

5. **Deploy**  
   You can deploy this site to **Cloudflare Pages**, **Vercel**, **Netlify**, or any static hosting.

---

## 🧩 Add New App

To add a new app:

1. Go to `src/content/`  
2. Create a new `.md` file:

```markdown
---
title: "CoolApp"
slug: "coolapp"
description: "A cool app for productivity"
version: "1.0.0"
platform: ["Windows", "Mac"]
download_url: "https://example.com/coolapp.exe"
image: "/assets/coolapp.png"
tags: ["productivity", "free", "offline"]
---

## About CoolApp

CoolApp is a powerful tool to help you stay focused and organized...
```

3. Done! It’ll show up automatically on the homepage or tag page.

---

## 📌 Tech Stack

- [Astro](https://astro.build/) – Modern static site generator  
- [Tailwind CSS](https://tailwindcss.com/) – Utility-first CSS  
- [Markdown](https://www.markdownguide.org/) – For content  
- [Cloudflare Pages](https://pages.cloudflare.com/) – Recommended hosting

---

## 💡 Future Plans

- ✅ Add platform filter (Windows, Mac, Linux)
- ✅ Progressive Web App (PWA) support
- ✅ Versioning & changelog per app
- 🕵️‍♂️ Search by app name or tags
- 🌐 Multilingual support

---

## 🤝 Contributing

Wanna help? Contributions welcome!

- Fork this repo
- Create a new branch (`git checkout -b feature-xyz`)
- Commit your changes
- Open a PR

Don't forget to ❤️ the repo if this project helps you!

---

## 📄 License

MIT License – free to use, modify, and share.

---

## 🔗 Related Projects

- [DataCenter Educentrals](https://data.educentrals.com)
- [Hilal Technologic](https://github.com/hilaltechnologic)

---

> “Build tools. Share knowledge. Repeat.”
