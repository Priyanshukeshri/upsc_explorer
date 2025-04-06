## 🌏 UPSC World Map Explorer

An interactive web app designed for UPSC aspirants to explore any location across the globe and get categorized, AI-generated insights — History, Geography, Polity, Environment, Economy, and more — all at a glance.

### 🔍 Features

- 🌐 **Map-based search** with Leaflet.js
- 📍 Clickable markers and dynamic map centering using OpenStreetMap
- 🧠 AI-generated content powered by **Gemini 1.5 Flash API**
- 🗂️ Tabbed UI for UPSC-relevant categories:
  - History
  - Geography
  - Polity
  - Environment
  - Economy
  - Science & Tech
  - Agriculture
  - Security
- 📱 Responsive design for mobile devices
- 💡 Bullet-pointed insights with date-wise detailing
  
---

### 🚀 Getting Started

#### 1. Clone the Repository

```bash
git clone https://github.com/your-username/upsc-world-map-explorer.git
cd upsc-world-map-explorer
```

#### 2. Add Your Gemini API Key

Open the `index.html` file and replace the following line with your own Gemini API key:

```js
const API_KEY = "YOUR_GEMINI_API_KEY";
```

> ⚠️ Don’t expose your real API key in public repos. Use `.env` or server-side proxy if deploying live.

#### 3. Open the App

You can open `index.html` directly in your browser:

```bash
open index.html
```

Or host it using a live server (like VSCode's Live Server extension or any static server).

---

### 🧰 Technologies Used

- 🗺️ [Leaflet.js](https://leafletjs.com/) – Open-source interactive maps
- 📦 [OpenStreetMap](https://www.openstreetmap.org/) – Geolocation services
- 🤖 [Gemini API](https://ai.google.dev/) – AI-powered content generation
- 🔧 HTML, CSS, JavaScript – Frontend core

---

### 📄 License

This project is licensed under the [MIT License](LICENSE).

---

### ✨ Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

### 🙏 Acknowledgements

- Google Gemini for API access
- OpenStreetMap for location services
- Leaflet.js for mapping UI

---

Let me know if you'd like a dark mode toggle, backend support, or deployment help (GitHub Pages, Netlify, Vercel).
