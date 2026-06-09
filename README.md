# Robust Climate Sensor Calibration under Degraded Conditions

## 📌 Project Overview
This project utilizes Deep Reinforcement Learning (DRL) to autonomously calibrate and restore data integrity from degraded environmental climate sensors operating in harsh conditions. 

By simulating high-noise environments (such as hardware damage or severe weather), the project trains an AI agent using the Proximal Policy Optimization (PPO) algorithm to filter out chaos and predict the true environmental value. The mathematical stability of the model is translated into clear, visual performance charts to demonstrate structural robustness to stakeholders.

## 🚀 Features
* **Custom Simulation Environment:** A custom `Gymnasium` environment that simulates real-world sensor degradation by injecting extreme noise into baseline climate readings.
* **Deep Reinforcement Learning:** Utilizes the robust `Stable-Baselines3` implementation of PPO to train an agent to apply dynamic calibration adjustments.
* **Data Visualization:** Automatically generates `Matplotlib` charts comparing the true environmental baseline, the degraded noisy sensor data, and the final AI-calibrated output.

## 🛠️ Tech Stack
* **Language:** Python 3
* **Environment:** Jupyter Notebook / Google Colab
* **Libraries:** * `gymnasium` (Environment Simulation)
  * `stable-baselines3` (PPO Algorithm / AI Training)
  * `numpy` (Mathematical Operations)
  * `matplotlib` (Data Visualization)

## 💻 How to Run the Project (Browser/Colab)
The easiest way to run this project is directly in your browser using Google Colab, requiring zero local installation.

1. Navigate to [Google Colab](https://colab.research.google.com/).
2. Click **File > New Notebook**.
3. Create a new code cell and install the required dependencies:
   ```bash
   !pip install gymnasium stable-baselines3 numpy matplotlib
