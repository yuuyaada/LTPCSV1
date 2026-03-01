# LTPCS — LaSalle Thermal Pollution Control System

A mobile-first, industrial-grade web interface for monitoring and controlling thermal pollution equipment across multiple stations.

---

## 🚀 Live Demo

> Deployed via Netlify: **[your-site-name].netlify.app**

---

## 📋 Features

- **Multi-System Management** — Add, edit, and delete monitoring stations dynamically
- **4 Variable Panels** per system:
  - **A · Input Variables** — Flow rate, inlet temp, heat load, TSS, pH, particle size
  - **B · Operating Variables** — ΔT, coolant flow, pressure, cooling mode, bypass valve
  - **C · Performance Variables** — Collection efficiency, emissions, energy consumption, compliance
  - **D · Output Variables** — Treated temp, discharge rate, blowdown, DO, pH correction
- **Data Reports** — Daily, weekly, and EPA monthly reports with 7-day historical table
- **Alerts & Logs** — Active alerts with severity levels, timestamped event log
- **Compliance Center** — Configurable alarm thresholds (EPA §316(a), NPDES, Clean Water Act)
- **Settings** — General config, notifications, SCADA integration, data retention, security
- **Account** — User profile, access permissions, certifications

## 📱 Responsive Design

- **Mobile** — Bottom navigation bar, slide-out drawer sidebar, swipeable KPI cards, large touch targets
- **Tablet / Desktop** — Pinned sidebar, expanded grid layouts

---

## 🗂 Project Structure

```
LTPCS/
├── index.html       # Single-file application (HTML + CSS + JS)
├── README.md        # This file
├── netlify.toml     # Netlify deployment config
└── .gitignore       # Git ignore rules
```

---

## 🛠 Deployment

### GitHub Pages
1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Your site will be live at `https://<username>.github.io/<repo-name>/`

### Netlify (Recommended)
1. Push this repository to GitHub
2. Go to [netlify.com](https://netlify.com) → **Add new site → Import an existing project**
3. Connect your GitHub repository
4. Build settings are auto-detected via `netlify.toml`
5. Click **Deploy site**

---

## ⚙️ Tech Stack

- **Vanilla HTML / CSS / JavaScript** — No build tools, no dependencies
- **Google Fonts** — Alata (display), Exo 2 (body), Share Tech Mono (data labels)
- **CSS Custom Properties** — Full theming via CSS variables
- **Single-file SPA** — All logic in `index.html`, deployable anywhere

---

## 📐 Variable Reference

| Section | Key Variables |
|---|---|
| **Input (A)** | Phase type, particle size, flow rate, inlet temp, heat load, TSS, DO, pH |
| **Operating (B)** | ΔT, ambient temp, coolant flow, plume radius, pressure drop, bypass valve, cooling mode |
| **Performance (C)** | Collection efficiency, HX effectiveness, TSS removal, energy consumption, ΔT discharge, EPA compliance |
| **Output (D)** | Treated temp, discharge rate, blowdown rate, output pH, DO restoration, heat recovered |

---

## 🏫 About

Built for **De La Salle University** Environmental Engineering — Thermal Pollution Control monitoring interface.

**Version:** LTPCS v1.0.0
