# Greenhouse PID Control Simulator

🌐 **Live Demo:**  
https://pid-greenhouse.moeen14-aiub.workers.dev/

---

This is an interactive web-based PID controller simulation designed for educational use in control systems courses.

The simulator models a greenhouse temperature system affected by environmental disturbances (sunlight and wind) and allows users to tune PID parameters in real time.

---

## 🔧 Features

- Real-time PID tuning (Kp, Ki, Kd)
- Adjustable setpoint and initial temperature
- Configurable disturbance amplitudes:
  - Sunlight heating
  - Wind cooling
- Real-time visualization:
  - Temperature response
  - Heater output
  - Cooler output
- Performance metrics:
  - IAE (Integral of Absolute Error)
  - Overshoot Penalty
  - Control Effort
  - Total Cost (J)
  - Score
- Submission system integrated with Google Sheets

---

## 🧠 Control System Details

The simulator implements:

- PID controller with:
  - Derivative on measurement
  - Low-pass filtered derivative
  - Anti-windup integral
- Actuator dynamics and delay
- Passive thermal loss model
- Nonlinear disturbance profiles using Gaussian functions

---

## 🚀 How to Use

### Online (Recommended)
Open:
👉 https://pid-greenhouse.moeen14-aiub.workers.dev/

---

### Run Locally
Download the repository and open:


index.html


in any modern browser.

---

## 🎯 Objective

Tune PID gains to minimize:


J = 1.0 × IAE + 2.0 × Overshoot + 0.2 × Control Effort


Score:


Score = 10000 / (1 + J)


- Lower J → better control
- Higher Score → better performance

---

## 🎓 Educational Use

This tool is designed for:

- Control systems courses
- PID tuning labs
- Student competitions
- Interactive demonstrations

---

## 📦 Project Structure


├── index.html # Full simulator (frontend + logic)
├── README.md
└── LICENSE


---

## 👨‍💻 Author

**Moeen Ul Islam**  
PhD Student  
Agricultural and Biological Engineering  
Mississippi State University  

---

## 🌐 Deployment

Hosted using **Cloudflare Workers**

---

## 📌 Citation

If you use this tool in research or teaching, please cite:

Moeen Ul Islam, "Greenhouse PID Control Simulator", 2026.
Available at: https://pid-greenhouse.moeen14-aiub.workers.dev/

---

## 📄 License

This project is licensed under the MIT License — see the LICENSE file for details.

---

## ⭐ Support

If you find this useful:

- ⭐ Star the repository  
- 🍴 Fork it  
- 📢 Share with your class or lab
  
