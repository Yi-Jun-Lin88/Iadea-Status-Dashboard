# 🖥️ IAdea Status Dashboard (Lightweight HTML Version)

A high-performance, responsive kiosk-mode dashboard designed for digital signage environments. This project focuses on UI/UX and zero-dependency frontend execution.

## 🌟 Key Features
- **Kiosk-Mode Optimized:** Dark-themed UI using **Tailwind CSS** for maximum readability on industrial displays.
- **CORS Solution:** Integrated a CORS Proxy (`allorigins`) to enable client-side data fetching directly from external government APIs.
- **Zero-Latency Search:** Implemented instant client-side filtering logic using vanilla JavaScript.
- **Responsive Design:** Fully adaptive layout that works seamlessly on both mobile devices and large-scale monitors.

## 🛠️ Tech Stack
- **Frontend:** HTML5, Tailwind CSS (via CDN)
- **Logic:** Vanilla JavaScript (ES6+)
- **Data Source:** Taipei City Open Data (CSV via Proxy)

## 🚀 Deployment
This project is hosted on **GitHub Pages**. 
Live Demo: [[My GitHub Pages URL]](https://yi-jun-lin88.github.io/IAdea-Status-Dashboard/)

## 🤖 Engineering Insights
- Solved **CORS (Cross-Origin Resource Sharing)** limitations without a dedicated backend by implementing a proxy-based fetch strategy.
- Designed a dynamic parsing engine that maps CSV columns based on content keywords rather than fixed indexes, ensuring data robustness.
