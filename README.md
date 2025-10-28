# 🇲🇬 Manakalo

**Manakalo** is a simple, fast, and intuitive currency converter designed for daily use.  
It helps you convert between **USD**, **EUR**, **CNY**, and **MGA** with real-time exchange rates — and a clean, no-brainer interface.

🔗 **Live demo:** [https://tools.devambition.com/manakalo/](https://tools.devambition.com/manakalo/)

---

## ✨ Features

- 💱 Convert between **USD**, **EUR**, **CNY**, and **Ariary (MGA)**
- ⚡ **Real-time rates** fetched automatically (cached for performance)
- 💡 Toggle to **round results** or display with decimals
- 🧮 Instant conversion with no reload
- 📱 Fully responsive one-page interface
- 💾 Local caching to reduce API calls

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | HTML, CSS (Vanilla), JavaScript |
| Backend (optional) | PHP (for caching and API calls) |
| Data Source | Exchange rate API (e.g. exchangerate.host) |

---

## ⚙️ Installation

Clone the repository:
```bash
git clone https://github.com/yourusername/manakalo.git
cd manakalo
```

You can open index.html directly in your browser (note: API may require CORS support).

## 🌍 Supported Currencies

| Currency         | Code | Flag |
|------------------|------|------|
| Malagasy Ariary  | MGA  | 🇲🇬 |
| US Dollar        | USD  | 🇺🇸 |
| Euro             | EUR  | 🇪🇺 |
| Chinese Yuan     | CNY  | 🇨🇳 |

---

## 🔧 Configuration

You can edit the following options in `script.js`:

```js
const CACHE_DURATION_HOURS = 1; // how long to keep cached rates
const API_URL = "https://api.exchangerate.host/latest";
```

📸 Preview Image

🧠 Name Origin

“Manakalo” comes from the Malagasy word for “exchange” or “conversion” —
a local touch representing simplicity and accessibility.

🪪 License

This project is released under the MIT License — feel free to use, modify, and share.

---