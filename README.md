<div align="center">

# Ommy Crack — URL Fixer

**Extract clean, non-watermarked audio preview URLs from stock media sites.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-7c6aef?style=for-the-badge&logo=github&logoColor=white)](https://umar-hyatt.github.io/OmmyCracks/)
[![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-222?style=for-the-badge&logo=githubpages&logoColor=white)](https://umar-hyatt.github.io/OmmyCracks/)

<br>

<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
<img src="https://img.shields.io/badge/Zero_Dependencies-34d399?style=flat-square" alt="Zero Dependencies">

</div>

---

## What It Does

Ommy Crack is a lightweight, client-side tool that recovers clean audio URLs from stock media platforms. It supports two workflows:

- **Tampered URL mode** — Paste a mangled/escaped URL and get the cleaned version instantly.
- **Page Source mode** — Paste the full HTML source (`Ctrl+U` / `Cmd+U`) from a stock audio page, and the tool extracts the best available preview URL automatically.

Everything runs **100% in your browser** — no server, no API calls, no data leaves your machine.

---

## Supported Platforms

| Platform | URL Fixing | Page Source Extraction | Prioritizes |
|---|:---:|:---:|---|
| **Storyblocks** | Yes | Yes | `_NWM` (no watermark) preview from `previewUrl` |
| **Pond5** | Yes | Yes | `_nw_prev` (no watermark) preview from `og:audio` |

---

## How to Use

1. **Visit** the [live tool](https://umar-hyatt.github.io/OmmyCracks/).
2. **Select** your platform — click **Storyblock** or **Pond5**.
3. **Paste** either:
   - A tampered/escaped URL, or
   - The full page source from the stock audio page (right-click the page > *View Page Source*).
4. **Click** "Fix URL".
5. **Copy** the clean URL or preview the audio directly in the built-in player.

---

## Features

- **Dark, modern UI** — Clean interface with a dark theme, monospace output, and smooth transitions.
- **Audio preview** — Built-in HTML5 audio player to listen to extracted URLs instantly.
- **One-click copy** — Copy the fixed URL to your clipboard with a single click.
- **Smart extraction** — Automatically picks the non-watermarked preview URL from page source HTML.
- **Multi-URL output** — Displays all found URLs when multiple are detected.
- **Quick navigation** — Clicking a platform button also opens its website in a new tab.
- **Zero dependencies** — Single HTML file, no build step, no frameworks.

---

## Running Locally

```bash
git clone https://github.com/umar-hyatt/OmmyCracks.git
cd OmmyCracks
open index.html
```

Or simply open `index.html` in any modern browser.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, flexbox) |
| Logic | Vanilla JavaScript (regex-based URL extraction) |
| Hosting | GitHub Pages |

---

## Project Structure

```
OmmyCracks/
└── index.html    # Entire app — markup, styles, and logic in one file
```

---

## License

This project is open source. Feel free to fork, modify, and use it.

---

<div align="center">

**[Try Ommy Crack](https://umar-hyatt.github.io/OmmyCracks/)**

Made by [@umar-hyatt](https://github.com/umar-hyatt)

</div>
