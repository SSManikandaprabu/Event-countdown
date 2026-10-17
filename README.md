<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=gradient&customColorList=12,14,30&text=EMBER%20Summit%202027&fontSize=48&fontColor=ffffff&animation=fadeIn&desc=A%20scroll-driven%20event%20countdown%20website&descSize=18&descAlignY=72" alt="EMBER Summit 2027 banner" />

![HTML5](https://img.shields.io/badge/HTML5-E8480F?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-2965F1?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-2EA043?style=for-the-badge)
![Responsive](https://img.shields.io/badge/Responsive-Yes-8B5CF6?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-FF5A1F?style=for-the-badge)

### 🔥 Count down to anything, in style.

[**🌐 Live Demo**](https://YOUR-USERNAME.github.io/ember-countdown) · [**🐛 Report a Bug**](../../issues) · [**✨ Request a Feature**](../../issues)

</div>

---

## 🎯 About

**EMBER Summit 2027** is a single-page, scroll-driven countdown website for a tech event. It has a live ticking timer, smooth reveal animations, a tabbed schedule and a ticket reservation flow. It runs on plain HTML, CSS and JavaScript, with no frameworks and no build step.

## ✨ Features

| | Feature | Details |
|---|---|---|
| ⏱️ | **Live countdown** | Days, hours, minutes and seconds, with "live now" and "ended" states |
| 📜 | **Scroll experience** | Progress bar, reveal-on-scroll, parallax glow, animated counters |
| 🗓️ | **Tabbed schedule** | Two-day timeline with accessible tabs |
| 🎤 | **Speakers and venue** | Hover cards, stylised map and an "Open in Maps" link |
| 🎟️ | **Ticket passes** | Three tiers with a validated reservation form |
| 🧮 | **Personal countdowns** | Add your own events, saved in `localStorage` |
| 🌗 | **Light and dark themes** | Follows system preference, with a manual toggle |
| ♿ | **Accessible** | Keyboard friendly, visible focus states, respects `prefers-reduced-motion` |
| 📱 | **Fully responsive** | Works from 360px phones to wide desktops |

## 🛠️ Tech Stack

- 🧱 **HTML5**: semantic markup, `<dialog>`, `<details>`
- 🎨 **CSS3**: custom properties, grid, `color-mix()`, keyframe animations
- ⚡ **Vanilla JavaScript**: `IntersectionObserver`, `requestAnimationFrame`, `localStorage`
- 🔤 **Google Fonts**: Big Shoulders Display and Manrope

## 🚀 Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/YOUR-USERNAME/ember-countdown.git

# 2. Open the folder
cd ember-countdown

# 3. Launch it (any one of these)
open index.html                 # macOS
start index.html                # Windows
npx serve .                     # local server
```

No installs and no build. Just open the file.

## 🎨 Make It Yours

**1. Change the event date**

```js
const T0 = new Date("2027-01-23T09:00:00+05:30").getTime(); // start
const T1 = new Date("2027-01-24T18:00:00+05:30").getTime(); // end
```

**2. Change the theme colours** in the `:root` block:

```css
--a: #e8480f;   /* accent */
--bg: #f2ede3;  /* background */
--ink: #14110d; /* text */
```

**3. Edit the content**: the `DAYS` (schedule), speaker and `TX` (tickets) arrays sit at the top of the script.

## 📁 Project Structure

```
ember-countdown/
├── index.html    # the whole site: markup, styles and scripts
└── README.md
```

## 🌍 Deploy for Free

| Platform | Steps |
|---|---|
| 🐙 **GitHub Pages** | Settings → Pages → Deploy from branch → `main` |
| ▲ **Vercel** | Import the repo and deploy |
| 🟢 **Netlify** | Drag and drop the folder |

## 🗺️ Roadmap

- [x] Live countdown with event states
- [x] Schedule, speakers, venue and tickets
- [x] Personal countdowns with saved data
- [x] Light and dark themes
- [ ] Add to Calendar (`.ics`) button
- [ ] Multi-language support
- [ ] Real payments and a backend for tickets
- [ ] Admin panel to edit events

## 🤝 Contributing

Contributions are welcome.

1. 🍴 Fork the project
2. 🌿 Create your branch: `git checkout -b feature/amazing-idea`
3. 💾 Commit your changes: `git commit -m "Add amazing idea"`
4. 🚀 Push the branch: `git push origin feature/amazing-idea`
5. 🔁 Open a Pull Request

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for details.

## 👨‍💻 Author

**S.S. Manikanda Prabu**
B.Tech CSE, SRM Institute of Science and Technology, Ramapuram

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR-USERNAME)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-PROFILE)

<div align="center">

⭐ **If you like this project, give it a star.** ⭐

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=gradient&customColorList=12,14,30&section=footer" alt="footer wave" />

</div>
