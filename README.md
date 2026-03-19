# Workus Shield

### AI-Powered Predictive Income Protection for Gig Delivery Workers

**Hackathon:** Guidewire DEVTrails 2026

---

## 🔷 Product Identity

**Workus Shield is not just an insurance platform — it is a predictive income protection system for gig workers.**

It combines AI prediction, parametric insurance, and real-time verification to protect workers **before, during, and after disruptions.**

---

# 👥 Team

### Team Leader

* Aman Kesarwani

### Team Members

* Abhay Gupta
* Abhay Singh Rajawat
* Brahmdev Arya
* Anamika Maddeshiya

---

# 📌 Problem Statement

India’s gig delivery ecosystem (Zomato, Swiggy, Blinkit, Zepto, Amazon, etc.) forms a major part of the modern digital economy.

Delivery partners depend on **daily work hours and completed deliveries** to earn income.

However, external disruptions such as:

* heavy rainfall
* floods
* extreme heatwaves
* severe pollution spikes
* curfews or strikes
* platform outages

can suddenly stop their work and cause **direct income loss**.

Currently, gig workers bear this loss themselves because there is **no specialized income protection system designed for their work model.**

---

# 🎯 Solution Overview

**Workus Shield** is an AI-powered parametric insurance platform that protects gig workers from income loss.

Instead of traditional insurance:

1. monitors environmental + operational data
2. predicts disruptions before they happen
3. detects disruption events automatically
4. verifies affected workers
5. triggers instant payouts

👉 This ensures **fast, fair, and reliable income protection**

---

# 👤 Target Persona

Gig delivery workers:

* Zomato riders
* Swiggy partners
* Blinkit / Zepto delivery agents

### Characteristics:

* earn per delivery
* weekly income cycle
* outdoor work
* highly disruption-sensitive

---

# 🚀 Key Innovations

## 🤖 AI Predictive Risk Alerts

The system predicts disruptions using:

* weather forecasts
* AQI trends
* historical data
* location-based risk patterns

### Example:

Heavy Rain Expected
Location: Karol Bagh
Time: 45 min
Risk Level: High
Confidence: 82%

👉 Workers get early warning

---

## 🌍 City-Specific Baseline Logic (CORE INNOVATION)

Environmental conditions vary across cities.

### Example:

| City      | Normal AQI | Trigger |
| --------- | ---------- | ------- |
| Delhi     | 250        | >400    |
| Bangalore | 80         | >150    |

### Formula:

Trigger = Baseline × Multiplier

👉 Prevents false payouts
👉 Ensures real disruptions only

---

## ⚖️ Rare Event Filtering

Only disruptive events trigger payouts:

| Situation      | Payout |
| -------------- | ------ |
| Light rain     | ❌      |
| Flood rainfall | ✅      |
| Normal AQI     | ❌      |
| Extreme AQI    | ✅      |

👉 Keeps system sustainable

---

## 📍 Zone-Based Verification

```text
distance(worker, event) < radius
AND worker_active = true
AND policy_active = true
```

👉 Ensures worker is actually affected

---

## 🛡 Worker Activity Validation

Checks:

* online status
* delivery activity
* GPS

👉 prevents fake claims

---

## 🔍 Transparent Claim Explanation

Every claim shows:

* Rainfall: 72 mm
* Baseline: 30 mm
* Threshold: 60 mm
* Distance: 200 m
* Worker Status: Active

👉 builds trust + clarity

---

## 📊 AI Risk Scoring

Each prediction includes:

* Risk Level (Low / Medium / High)
* Confidence Score (e.g., 82%)

👉 improves decision-making

---

# 💰 Weekly Pricing Model

| Plan     | Price | Coverage        |
| -------- | ----- | --------------- |
| Basic    | ₹15   | Rain            |
| Standard | ₹25   | Rain + Heat     |
| Premium  | ₹35   | All disruptions |

👉 aligned with gig worker income cycle

---

# ⚙️ Parametric Insurance Model

Automatic payout when:

* rainfall exceeds threshold
* extreme heat
* pollution spike
* platform outage
* local disruptions

👉 no manual claim required

---

# 🧠 AI System

AI models perform:

* risk prediction
* anomaly detection
* premium optimization

---

# 🛡️ Adversarial Defense Strategy (MARKET CRASH READY)

To handle fraud scenarios like fake GPS and coordinated claims:

### Multi-Layer Verification

* GPS consistency
* activity validation
* policy status

---

### Anomaly Detection

* sudden claim spikes
* unusual behavior patterns
* abnormal frequency

---

### Trust Score System

Each worker gets a trust score based on:

* past claims
* behavior consistency
* activity patterns

---

### Group Fraud Detection

* detect clusters of suspicious claims
* identify coordinated fraud rings

---

### Cross Verification

* validate with nearby workers
* compare with real disruption data

---

👉 Ensures system remains **secure, fair, and fraud-resistant**

---

# 🏗 System Architecture

Worker App
↓
Backend API
↓
Database
↓
AI Risk Engine
↓
Event Detection
↓
Verification Engine
↓
Claim Engine
↓
Wallet System

---

# 🔄 Workflow

1. Worker logs in
2. Activates insurance
3. AI predicts risk
4. Disruption occurs
5. Worker verified
6. Claim approved
7. Payout credited

---

# 📱 Prototype Scope

Includes:

* Login + OTP
* Mission Control Dashboard
* Insurance plans
* Disruption alert
* Claim verification
* Claim approval
* Claim history
* Risk map

---

# 🛠 Tech Stack

Frontend: React, Tailwind
Backend: FastAPI
Database: MySQL
AI: Python ML models
APIs: Weather, AQI
Maps: Leaflet.js

---

# 🏁 Conclusion

Workus Shield combines:

* AI prediction
* parametric insurance
* smart verification
* fraud detection

to create a **complete income protection system for gig workers**

---

## 💡 Vision

**From reactive insurance → to predictive protection**

---
