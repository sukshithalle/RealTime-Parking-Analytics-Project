# 🚗 Real-Time Parking Pricing – Summer Analytics 2025 Capstone Project

This project is built as part of **Summer Analytics 2025**, hosted by **Consulting & Analytics Club × Pathway**.

## 📌 Overview

This project builds a **real-time dynamic pricing model** for 14 urban parking lots using live data streaming. The goal is to improve parking utilization by dynamically updating prices based on demand, traffic, special events, and other factors using **Pathway**.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas & NumPy** – Data manipulation & computation
- **Pathway** – Real-time stream processing
- **Bokeh** – Interactive visualizations
- **Google Colab** – Development environment
- **GitHub** – Version control and submission

---

## 📊 Models Implemented

### ✅ Model 1: Baseline Linear Model
- Linear price increase based on occupancy
- `Price(t+1) = Price(t) + α * (Occupancy / Capacity)`

### ✅ Model 2: Demand-Based Pricing Model
- Price depends on multiple features:
  - Occupancy rate
  - Queue length
  - Traffic level
  - Special day indicator
  - Vehicle type
- Formula:
### 🔁 Model 3 (Optional): Competitive Model
- Considers competitor pricing using geographic proximity (latitude/longitude)
- Dynamic price adjustment and rerouting based on nearby parking lots

---
## 🧠 Workflow

1. **Ingest CSV as a simulated real-time stream** using `Pathway`
2. **Parse & process time columns** using `datetime` logic
3. **Apply dynamic pricing models**
 - Aggregation & demand estimation
4. **Visualize pricing behavior** in real-time using Bokeh
5. **Upload & version** code on GitHub

