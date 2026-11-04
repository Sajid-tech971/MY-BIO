# MD SAJID - Personal Biodata & Portfolio Website (v2 - Compact Social Icons)

## 🌟 What's New in v2:
1. **Compact Magnified Social Dock:** Social media links are now displayed as small elegant glass icons that scale up beautifully with an interactive hover effect.
2. **Automatic Empty Link Hiding System:** Added 12+ pre-configured social icon templates (GitHub, Chess.com, Facebook, Email, Discord, YouTube, Instagram, Telegram, WhatsApp, Steam, LinkedIn, X). If any `href` link is left empty `href=""` or `#`, it automatically disappears from the page!

## 📁 Repository Structure
```text
/
├── index.html                  # Main Web Portal
├── README.md                   # Setup Documentation
└── assets/
    ├── background/             # Background image/animation folder
    │   └── bg.png              # Background Image (PNG / JPG / GIF)
    ├── audio/                  # Background music folder
    │   └── bgm.mp3             # Hidden Audio file
    └── images/                 # Personal photos folder
        └── profile.png         # Profile picture
```

## 🚀 How to Host on GitHub Pages
1. Upload all contents to your GitHub Repository.
2. Put your background image in `assets/background/bg.png` (or `.gif` / `.mp4`).
3. Put your background music in `assets/audio/bgm.mp3`.
4. Enable GitHub Pages from **Settings -> Pages -> Branch: main**.

## ✨ Premium v3 Upgrade

This edition keeps the original entry overlay, background image/audio, social dock, live clock and RED-BEAST hardware panel, and adds:

- **Aura ∞ signature identity** with a custom emblem and animated glass panel.
- **Aura theme switcher** with Violet, Cyber Cyan and Solar Gold accents (preference is saved in the browser when storage is available).
- **Visible audio controls** for play/pause and volume, with status feedback.
- **Copy profile link** control using the current page URL.
- **Project Vault** showcase for the Personal Portal, RED-BEAST setup and Digital Lab.
- **SEO/social metadata**, dynamic copyright year and reduced-motion support.
- **Responsive adjustments** for the control panel and compact social dock.

### Customization notes
- Update the project card copy in `index.html` as real projects are published.
- Replace empty social link `href` values with your actual profile URLs; empty links continue to hide automatically.
- The Aura theme switcher only changes accent styling and does not alter the background image.
- Background music starts after the user presses **ENTER WORKSPACE**; visitors can pause it or change the volume at any time.

This is a static site and still works with GitHub Pages. Tailwind CSS, Google Fonts and Font Awesome are loaded from CDNs, so those visual assets require an internet connection.
