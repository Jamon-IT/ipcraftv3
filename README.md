# ⚡ IPCraft — Network Toolkit for IT Pros

![Version](https://img.shields.io/badge/version-2.0-7C6EF6)
![License](https://img.shields.io/badge/license-MIT-4AE3B5)
![HTML](https://img.shields.io/badge/stack-HTML%20%2F%20CSS%20%2F%20JS-F0916E)

**IPCraft** is a fast, lightweight subnet calculator and network reference tool built for IT students, sysadmins, and networking professionals. No install, no dependencies — just open and go.

🔗 **[Live Demo →](#)* https://ipcraftv3.vercel.app/*

---

## ✨ Features

- **Subnet Calculator** — Enter any IPv4 address + CIDR and instantly get network address, broadcast, usable range, host count, subnet mask, wildcard mask, and IP class.
- **Binary Visualizer** — See the network/host bit split in real time, color-coded for clarity.
- **Quick Presets** — One-click common subnets (10.0.0.0/8, 192.168.1.0/24, etc.) for fast testing.
- **Common Ports Reference** — 16 essential ports (SSH, HTTP, DNS, DHCP, RDP…) with protocol info.
- **CIDR Table** — Full reference from /8 to /32 with masks and host counts. Active CIDR is highlighted automatically.
- **Private Ranges** — RFC 1918 ranges, loopback, link-local, and default route at a glance.
- **Dark Mode** — Full dark UI designed for long sessions and low-light environments.
- **Responsive** — Works on desktop, tablet, and mobile.
- **Zero Dependencies** — Pure HTML/CSS/JS, no frameworks, no build step.

---

## 🚀 Getting Started

### Option 1 — Open locally

```bash
git clone https://github.com/YOUR_USERNAME/ipcraft.git
cd ipcraft
open ipcraft.html
```

That's it. No `npm install`, no server, no build.

### Option 2 — Deploy online (free)

**Vercel:**
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com), import the repo
3. Deploy — done in 30 seconds

**Netlify:**
1. Drag and drop the `ipcraft.html` file on [app.netlify.com/drop](https://app.netlify.com/drop)
2. Your site is live

**GitHub Pages:**
1. Go to repo Settings → Pages
2. Set source to `main` branch
3. Your site is live at `https://YOUR_USERNAME.github.io/ipcraft`

---

## 📸 Screenshot

<img width="686" height="744" alt="image" src="https://github.com/user-attachments/assets/58b36d7f-85a2-45b4-8d4a-b43406f7d8df" />

---

## 🗺️ Roadmap

- [ ] VLSM calculator (multi-subnet splitting)
- [ ] IPv6 support
- [ ] Subnet quiz / exam mode
- [ ] Export results to PDF
- [ ] Network diagram generator
- [ ] PWA support (offline use)
- [ ] Localization (FR, EN, ES)

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | DM Sans + JetBrains Mono (Google Fonts) |
| Hosting | Any static host (Vercel, Netlify, GitHub Pages) |

---

## 📁 Project Structure

```
ipcraft/
├── ipcraft.html    # Single-file application (HTML + CSS + JS)
├── README.md       # This file
└── LICENSE         # MIT License
```

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repo
2. Create a branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m "Add my feature"`
4. Push: `git push origin feature/my-feature`
5. Open a Pull Request

Please open an issue first if you want to discuss a major change.

---

> If IPCraft helped you pass an exam or saved you time at work, consider giving it a ⭐ on GitHub!
