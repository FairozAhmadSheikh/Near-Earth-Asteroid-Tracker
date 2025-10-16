# 🚀 NASA Near-Earth Asteroid Tracker (7-Day)

A modern **space-themed web app** that tracks and displays near-Earth asteroids approaching our planet within a **7-day window** using **NASA’s NeoWs (Near Earth Object Web Service)** API.

Built with:
- ⚡ **HTML5**
- 💅 **Tailwind CSS**
- 🧠 **JavaScript (Fetch API)**

---
## 🌌 Features

- Fetches **real-time asteroid approach data** from NASA’s API.
- Displays asteroid **name**, **closest approach time**, **miss distance**, **size**, and **hazard status**.
- Interactive **collapsible date sections** for organized viewing.
- Built-in **loading**, **error**, and **no-asteroid** states.
- Responsive and fully client-side — **no backend required**.
- Beautiful **dark/space-themed design** with smooth animations.
- Includes **developer credits with GitHub and Instagram links.**

---

## 🧠 How It Works

This app uses the public NASA **NeoWs API**:

> https://api.nasa.gov/neo/rest/v1/feed

It retrieves a 7-day range of data using:

```bash
GET https://api.nasa.gov/neo/rest/v1/feed?start_date=YYYY-MM-DD&end_date=YYYY-MM-DD&api_key=DEMO_KEY

```
Then it dynamically renders all asteroids detected in that range, sorted by date.

---

## 🧰 Setup & Usage

### 1. Clone this repository

```bash
git clone https://github.com/FairozAhmadSheikh/NASA-Asteroid-Tracker.git
cd NASA-Asteroid-Tracker