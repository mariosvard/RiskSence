## RiskSense:Interactive Analytics Dashboard for Early Regional Health Monitoring

## 📌 Overview

RiskSense is an experimental analytics tool which utilizes environmental and contextual factors together to create one Dashboard that can be used for early health monitoring.

RiskSense creates a Dashboard which combines various weak indicators (such as temperature, humidity, number of tourists, etc.) into one score using a confidence measure.

---

🌐 Live Demo

🔗 Interactive Dashboard:
https://mariosvard.github.io/RiskSence/

Experience the RiskSense platform through an interactive dashboard that visualizes environmental and regional indicators, enabling real-time exploration of confidence-based monitoring results.

---

## 🎯 Objective

- Provide an early warning system to identify health risks in the region.
- Offer transparent analytics (not black-box systems).
- Dashboards help in decision-making.
- Demonstrate a proposed approach for multisignal health risk prediction.

---

🧠 Approach

The proposed system employs the following weighted aggregation formula:

Confidence = w_T * T_s + w_D * D_s + w_H * H_s

Where:- T_s: Temperature Score
- D_s: Tourist density score
- H_s: Historical incidents score.# 📉 Dashboard

The RiskSense dashboard presents a graphical interface for analyzing regional data.

---

### 🖼️ Dashboard Preview

![RiskSense Dashboard](Dashboard.png)

The dashboard visualizes how multiple weak signals are combined into a unified confidence score.

# 🗂️ Data

### Environment
- Temperature  
- Humidity

### Region 
- Tourist Density 
- Incidents in the past

### Output
- Confidence score
- Risk level 
- Suggested actions

## 🧩 System Structure
Inputs –> Processing –> Confidence Logic –> Dashboard 
## 💻 Technologies 
- JavaScript 
- D3.js 
- dc.js
- Crossfilter
---

## ⚠️ Limitations
- Data is simulated  
- Lack of real-time integration  
- Lack of machine learning  

---

# ▶️ How to Run the Project

## 1. Clone the Repository

```bash
git clone https://github.com/yourusername/RiskSense.git
```

---

## 2. Open the Project in Visual Studio Code

Open the project folder using Visual Studio Code.

---

## 3. Install the Live Server Extension

- Open Extensions (`Ctrl + Shift + X`)
- Search for:
  `Live Server`
- Install the extension by **Ritwick Dey**

---

## 4. Run the Dashboard

- Open the `index.html` file
- Right click → **Open with Live Server**

---

## 5. Open in Browser

The dashboard will automatically launch at:

```text
http://127.0.0.1:5500
```

or
```text
http://localhost:5500
```

---


## 🚀 Future Work
- Integration of real-world data  
- IoT & APIs  
- Machine learning algorithms  

---

## 📄 Paper
RiskSense: An Interactive Analytics Dashboard for Early Regional Health Monitoring

---

👨‍💻 Author

Marios Vardalachakis

⭐ Notes

This is a prototype system developed for research and demonstration purposes.

---
