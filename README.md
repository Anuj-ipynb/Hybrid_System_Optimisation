

# 🚗 Hybrid Electric Systems Optimization using Reinforcement Learning (PPO)

This project aims to optimize the energy efficiency and noise reduction in Hybrid Electric Vehicles (HEVs) using **Proximal Policy Optimization (PPO)**, a cutting-edge reinforcement learning algorithm. The goal is to train an intelligent agent that learns to manage the power sources (electric and combustion) in real-time driving scenarios, minimizing fuel consumption and engine noise.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Objectives](#objectives)
- [Technologies Used](#technologies-used)
- [Methodology](#methodology)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Evaluation](#evaluation)
- [Contributors](#contributors)
- [License](#license)

---

## 📖 Overview

Hybrid Electric Vehicles rely on both electric motors and internal combustion engines. This project develops a PPO-based reinforcement learning agent trained in a simulated OpenAI Gym environment to optimize control decisions, reduce fuel consumption, and suppress noise.

---

## 🎯 Objectives

- Efficiently switch between electric and combustion modes.
- Minimize fuel consumption during operation.
- Reduce engine noise via optimized acceleration/load distribution.
- Build a scalable RL training pipeline using PPO.

---

## 🛠️ Technologies Used

- Python 3.10+
- [Stable-Baselines3 (PPO)](https://github.com/DLR-RM/stable-baselines3)
- [OpenAI Gym](https://www.gymlibrary.dev/)
- NumPy, Matplotlib
- Scikit-learn (for evaluation metrics)
- Jupyter Notebook (for experimentation)

---

## ⚙️ Methodology

1. **Custom Environment Design**:  
   Modeled vehicle system dynamics in an OpenAI Gym-compatible environment.

2. **Reward Function Engineering**:  
   Custom reward balancing fuel efficiency, speed targets, and engine noise penalties.

3. **Model Training**:  
   PPO agent trained over thousands of episodes with carefully tuned hyperparameters.

4. **Evaluation**:  
   Performance measured using episode rewards and statistical metrics like R², MSE, etc.

---

## 📊 Results

- ✅ **Final Episode Score**: ~123.62
- 📉 **Fuel Consumption**: Reduced consistently as episodes progressed.
- 🔇 **Noise Optimization**: Penalties decreased steadily with policy improvement.
- 📈 **Evaluation Metrics**: High R² score, low Mean Squared Error, and good Explained Variance.

---

## 🚀 Installation

```bash
git clone https://github.com/Anuj-ipynb/hybrid-electric-ppo.git
cd hybrid-electric-ppo
pip install -r requirements.txt
