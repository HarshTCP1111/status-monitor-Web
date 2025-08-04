# 🚀 Status Monitor System

This project is an uptime monitoring and status page solution that tracks the availability and performance of selected services. It uses GitHub automation to monitor endpoints and maintain a transparent uptime history.

---

## 📡 Live Status Dashboard

🟢 **Live Dashboard**: [stats.techconciergepro.com](https://stats.techconciergepro.com/status/car-concierge-pro)  
_Replace this with your actual GitHub Pages link or custom domain._

| Service           | Status | Response Time | Uptime   |
|-------------------|--------|----------------|----------|
| Google            | 🟩 Up  | 93ms           | 100.00%  |
| Wikipedia         | 🟩 Up  | 223ms          | 100.00%  |
| Hacker News       | 🟩 Up  | 364ms          | 100.00%  |
| Test Broken Site  | 🟥 Down| 0ms            | 0.00%    |
| IPv6 Test         | 🟥 Down| 0ms            | 0.00%    |

---

## ⚙️ Key Features

- ⏱️ Monitors service availability every 5 minutes
- 📈 Tracks and records response times automatically
- 📊 Generates uptime graphs and logs daily performance
- 📝 Automatically creates and resolves incident reports
- 🌐 Publishes a self-hosted, responsive status page
- 🔔 Optional notifications for downtime or latency spikes

---

## 💡 How It Works

- GitHub automation checks defined endpoints at set intervals
- If a site is down, an incident is logged
- When it recovers, the issue is auto-closed
- A static status page displays real-time data and uptime history

---

## 📁 Configuration

- All monitored services are listed in `.upptimerc.yml`
- Customize the status site layout and meta via `site.yml`
- GitHub Pages serves the live status interface

---

## 🧑‍💻 Maintained by

**Harsh Shuddhalwar**  
🔗 [GitHub](https://github.com/HarshTCP1111) | 🌐 [Linkedin]([https://yourdomain.com](https://www.linkedin.com/in/harsh-shuddhalwar-4b1968213/))

> Part of a suite of internal automation and reliability tools.

---

## 📄 License

This project is licensed under the **MIT License**.  
All data under `/history` is publicly available and stored within this repository.
