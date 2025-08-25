# Probability and Stochastic Processes

This repository contains code, notes, and practical exercises for the Strathmore University course, **STA 8405: Probability and Stochastic Processes**.  

The course introduces stochastic modeling, emphasizing its applications in **industry, business, and science**.  

---

## 📘 Course Overview

**Aim:**  
To provide a firm foundation in stochastic theory and develop the ability to formulate and use stochastic models for forecasting and problem-solving.

**Objectives:**  
- Apply continuous and discrete-time Markov processes.  
- Formulate practical problems using appropriate stochastic models.  
- Apply advanced time series models (e.g., AR, Hidden Markov Models).  
- Fit models to data using Python and apply them for forecasting.  

---

## 📂 Repository Structure

- `notebooks/` → Jupyter notebooks for each weekly topic (explanations, code, and exercises).  
- `assignments/` → Solutions and code for assignments and projects.  
- `data/` → Datasets used in exercises and projects.  
- `scripts/` → Standalone Python scripts for models or simulations.  
- `README.md` → This file, providing repository overview.  
- `requirements.txt` → Python dependencies for running the code.  

---

## 📅 Weekly Topics & Learning Progress

- **Week 1:** Discrete and continuous stochastic processes.  
- **Week 2:** Random walk and the Gambler’s Ruin problem.  
- **Weeks 3–4:** Markov chains and Hidden Markov Models (HMMs).  
- **Week 5:** Branching processes.  
- **Week 6:** Poisson processes and continuous-time Markov chains.  
- **Week 7:** Linear systems theory, AR models, and transfer function modeling.  
- **Weeks 8–9:** Martingale theory, Brownian motion, and diffusion processes.  
- **Weeks 10–11:** Renewal processes, regenerative and renewal-reward processes.  
- **Weeks 12–13:** Queueing models and systems (e.g., M/M/1).  
- **Week 14:** Birth and death processes.  
- **Week 15:** Revision and integration of concepts.  

---

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/STA-8405-Stochastic-Processes.git
cd STA-8405-Stochastic-Processes
```

### 2. Create a virtual environment (recommended)
```bash
python3 -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

---

## 📦 Requirements

The required libraries are listed in **requirements.txt**:

```
numpy
scipy
matplotlib
pandas
statsmodels
hmmlearn
networkx
jupyter
```

### Why these packages?  
- **numpy** → Numerical computations, arrays, random sampling.  
- **scipy** → Optimization, integration, and advanced probability functions.  
- **matplotlib** → Visualization of processes and simulations.  
- **pandas** → Data manipulation and structured dataset handling.  
- **statsmodels** → Time series models (e.g., AR, ARMA), statistical tests.  
- **hmmlearn** → Implementation of Hidden Markov Models.  
- **networkx** → Graph representation of Markov chains and stochastic networks.  
- **jupyter** → Interactive notebooks for teaching and exercises.  

---

## ✨ Contribution Guidelines
- Fork the repository and create a new branch for any new content or fixes.  
- Submit a pull request with a clear description of changes.  
- Ensure code is well-documented and follows Python best practices.  

---

## 📚 License
This repository is for educational use within Strathmore University.  

