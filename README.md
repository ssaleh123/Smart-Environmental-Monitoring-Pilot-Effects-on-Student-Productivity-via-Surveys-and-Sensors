# Smart Environmental Monitoring — Pilot: Effects on Student Productivity via Surveys & Sensors

## 📘 Project Overview  
This project builds a proof‑of‑concept system to monitor indoor environmental conditions (e.g. temperature, humidity) using a microcontroller / Raspberry Pi + sensor + display, and correlate environment data with student productivity via surveys. The goal is to understand how factors like room climate affect comfort and performance in an academic / learning space.

This repo includes:  
- Sensor‑reading code (e.g. using DHT11) to periodically log environmental data.  
- Data logging and storage (timestamp + sensor readings).  
- (Optional) Display output on LCD (or similar) to show real‑time environmental data.  
- A companion research report / paper with detailed analysis, methodology, and survey results.  

## 🎯 Motivation  
- Indoor environmental conditions (temperature, humidity, air quality, etc.) play a significant role in comfort, concentration, and productivity — especially for students studying or working indoors.  
- By capturing real data rather than relying solely on subjective reports, this project aims to provide objective insights into how environment affects productivity.  
- This project demonstrates hands‑on skills in hardware interfacing, data capture, and data‑driven research — combining IoT, software development, and empirical evaluation.

## 🧰 Built With / Technologies  
- **Raspberry Pi** (or similar microcontroller / SBC) — for sensor interfacing and data logging.  
- **DHT11** (or DHT22) sensor — for measuring temperature and humidity.  
- **LCD / 16×2 (or suitable display)** — optional, to show real‑time readings.  
- **Python** (or language of your choice) — for sensor reading, data logging, and data output.  
- **CSV / JSON / SQLite / file-based storage** — to persist environment data over time.  
- **Survey + Analysis (via spreadsheet / script / statistical tool)** — to correlate environmental data with survey responses (student productivity, comfort, focus, etc.).  
- **Documentation / Paper** — includes research paper PDF summarizing methodology, data collection, analysis, and findings.  

## ✅ What’s Included  

| Item | Description |
|------|-------------|
| Sensor code | Script(s) to read data from sensor at configurable intervals. |
| Data logger | Automatically timestamped recordings stored in a data file / database. |
| (Optional) Display output | Real-time display of readings on attached LCD/display module. |
| Survey + Results / Paper | A full write-up (PDF) describing methodology, data collection, survey‑analysis, and conclusions. |
| README & documentation | This README to explain purpose and usage. |
