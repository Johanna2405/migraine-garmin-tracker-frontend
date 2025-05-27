# 🧠 Migraine / Garmin Tracker App

A web application to track migraines and correlate them with personal health metrics like heart rate, stress level, and sleep quality — using manually uploaded data from a Garmin device.

This project is designed for private use and learning purposes, with a strong focus on data visualization and identifying potential patterns or triggers for migraine attacks.

---

## ✨ Features

- Upload and process exported Garmin data (JSON format)
- Track and log migraine attacks manually
- Visualize health metrics (heart rate, stress, sleep) over time
- Overlay migraine incidents on health data charts
- Identify correlations between health patterns and migraine events

---

## 🛠 Tech Stack

### Frontend

- **React** – Component-based UI
- **Tailwind CSS** – Utility-first styling
- **Recharts** or **Chart.js** – For interactive data visualization

### Backend

- **Node.js** + **Express.js** – REST API for file upload and data processing
- **MongoDB** + **Mongoose** – Flexible NoSQL database for storing health and migraine data
- **Multer** – Middleware for handling file uploads

---

## 🚧 Status

This is a work-in-progress personal project to explore health-related data handling, analysis, and UI design. More features and polish will be added incrementally.

---

## 📌 Disclaimer

This app is not a medical product and is intended for **personal use and educational purposes only**.

---

### 📈 Vision & Future Plans

- Automated data integration (e.g. cloud storage, Garmin sync in future)
- User authentication and multi-user support
- Interactive analytics dashboard with filters and insights
- Export and sharing features (PDF, CSV)
- Mobile support for migraine logging on the go
- ML-based trigger suggestion (experimental)
