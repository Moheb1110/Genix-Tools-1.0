# ⚡ Genix Tools

A free, fast, SEO-optimized online tools website built with pure HTML, CSS, and JavaScript.

## 🛠️ Tools Included

| Tool | Description | Folder |
|------|-------------|--------|
| ⌨️ Typing Test | Measure WPM & accuracy | `/typing-test/` |
| 📝 Word Counter | Count words, chars, reading time | `/word-counter/` |
| ⚖️ BMI Calculator | Body Mass Index with metric/imperial | `/bmi-calculator/` |
| 🎂 Age Calculator | Exact age + birthday countdown | `/age-calculator/` |
| 🔐 Password Generator | Strong random passwords | `/password-generator/` |

## 📁 Folder Structure

```
genix-tools/
├── index.html              ← Homepage
├── style.css               ← Shared styles
├── robots.txt
├── sitemap.xml
├── 404.html
├── typing-test/
│   └── index.html
├── word-counter/
│   └── index.html
├── bmi-calculator/
│   └── index.html
├── age-calculator/
│   └── index.html
└── password-generator/
    └── index.html
```

## 🚀 Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `genixtools`)
2. Upload all files maintaining the folder structure
3. Go to **Settings → Pages**
4. Set source to **main branch / root**
5. Your site will be live at `https://yourusername.github.io/genixtools/`

> **Note:** Update all `href` paths in the HTML if your repo is not at root level (e.g., `/genixtools/typing-test/` instead of `/typing-test/`)

## 💰 AdSense Setup

Each page has clearly marked `<!-- AdSense -->` comment placeholders inside `.ad-slot` divs. Replace with:

```html
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXX" crossorigin="anonymous"></script>
<ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-XXXXXXXX" data-ad-slot="XXXXXXXX" data-ad-format="auto"></ins>
<script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
```

## ✅ Features

- **SEO optimized**: Meta tags, canonical URLs, Schema.org JSON-LD, sitemap, robots.txt
- **AdSense ready**: Ad slot divs placed in optimal positions
- **Responsive**: Mobile-first, works on all screen sizes
- **Fast loading**: No frameworks, no dependencies, no build step
- **Privacy first**: All processing happens in the browser
- **GitHub Pages compatible**: Static files, no server needed
