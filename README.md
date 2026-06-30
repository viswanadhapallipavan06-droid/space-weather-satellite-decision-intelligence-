# 🚀 HELIONYX SYNC
## Decision Intelligence System for Satellite Constellation Optimization

## 🛰️ Live Dashboard

[**View the interactive HELIONYX SYNC dashboard →**](https://viswanadhapallipavan06-droid.github.io/space-weather-satellite-decision-intelligence-/ISRO_SpaceWeather_3D.html)

Fully interactive — hover, zoom, pan, and explore live satellite constellation decisions in real time.

---

## 📌 Overview
This project presents a Decision Intelligence System designed to optimize satellite constellation operations under space weather uncertainties. It integrates machine learning, space physics, and optimization techniques to predict radiation risks and improve satellite communication reliability.

The system combines forecasting models, physical simulations, and decision algorithms into a unified pipeline that enables risk-aware satellite scheduling and management.

---

## 🧠 Key Features

- Space Weather Forecasting  
  - LSTM-based model for electron flux prediction  
  - Storm-aware training using weighted loss functions  
  - Handles rare-event imbalance (solar storms)  

- Uncertainty Quantification  
  - Monte Carlo Dropout for probabilistic predictions  
  - Generates confidence intervals for safer decision-making  

- Physics-Based Modeling  
  - Solar wind propagation delays (Sun → L1 → Earth)  
  - Dst proxy modeling for geomagnetic storm intensity  
  - Composite radiation intensity score (0–1 scale)  

- Satellite Constellation Simulation  
  - Multi-orbit fleet (LEO, GEO, MEO, SSO)  
  - Orbital mechanics using Kepler’s laws & Newtonian physics  

- Risk Scoring System  
  - Radiation-aware satellite reliability modeling  
  - Markov-based state transitions (Active, Idle, Faulty, etc.)  

- Optimization Engine  
  - Integer Linear Programming (ILP) for communication scheduling  
  - Maximizes link utility under radiation constraints  

---

## 🏗️ System Architecture

Space Weather Data → Forecast Model → Radiation Modeling  
        ↓                    ↓  
   Physics Engine → Risk Scoring → Optimization Engine  
                                   ↓  
                         Satellite Scheduling Decisions  

---

## ⚙️ Tech Stack

Backend & Modeling:
- Python
- NumPy, Pandas
- TensorFlow / PyTorch (LSTM models)
- SciPy (optimization)

Optimization:
- Integer Linear Programming (ILP)

Simulation:
- Orbital Mechanics (Kepler Equations)
- Markov Chains

Optional Frontend:
- Three.js (3D visualization)
- FastAPI (API deployment)

---

## 📈 Model Highlights

- ~43% improvement over baseline forecasting models  
- Accurate prediction of solar storm peaks  
- Confidence interval coverage up to ~89%  

---

## 🔬 Core Concepts

Radiation Intensity Model:
Radiation = 0.5 * flux + 0.3 * storm + 0.2 * flare

Solar Propagation Insight:
- Sun → Earth delay ≈ 4 days  
- L1 → Earth delay ≈ ~1 hour actionable window  

Key Insight:
Forecasting failures in rare-event systems are usually caused by multiple small issues interacting together
---

## 📊 Use Cases

- Satellite fleet management  
- Space weather risk prediction  
- Communication scheduling under uncertainty  
- Autonomous space systems  

---

## 🔮 Future Improvements

- Real-time satellite telemetry integration  
- Reinforcement Learning for adaptive scheduling  
- Global ground station network simulation  
- Deployment as a live decision-support dashboard  


Viswanadhapalli Pavan
M.Sc. Statistics, Banaras Hindu University  
