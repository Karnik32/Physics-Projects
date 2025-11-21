# Physics-Projects 

#Projectile motion Simulator

# Projectile Motion Simulator (Python)

This project is a complete **Projectile Motion Simulator** implemented in Python. It models projectile motion both **with** and **without air resistance**, calculates key parameters, and visualizes the full trajectory.

---

## 🚀 Features

* Analytic (exact) projectile motion without drag
* Numerical simulation using **RK4 (Runge–Kutta)** for quadratic air resistance
* Plots real-time trajectory graphs
* Computes:

  * Maximum height
  * Time to reach maximum height
  * Total time of flight
  * Horizontal range
* Adjustable input parameters
* Easy to extend or modify

---

## 📂 Project Structure

```
projectile-motion-simulator/
│
├── projectile_simulator.py
└── README.md
```

---

## 🧠 Physics Behind the Project

### 1. **No-Air-Resistance Equation**

Projectile motion follows:

* x(t) = v₀ cos(θ) t
* y(t) = y₀ + v₀ sin(θ) t − ½ g t²

### 2. **With Air Resistance**

Drag force:

* F_drag = ½ ρ C_d A v²
  It acts opposite to the direction of motion.

The numerical RK4 method solves the resulting non-linear differential equations accurately.

---

## ▶️ How to Run

### **1. Install Dependencies**

```
pip install matplotlib numpy
```

### **2. Run the Simulation**

```
python projectile_simulator.py
```

### **3. Enter Input Values**

The script will ask for:

* Initial velocity (m/s)
* Launch angle (degrees)
* Initial height (m)
* Whether to include air resistance
* Physical drag parameters (if enabled)

---

## 📊 Output

The program prints:

* Maximum height
* Time of flight
* Range
* Whether drag increases/decreases values

And displays a graph comparing:

* **Trajectory without drag**
* **Trajectory with drag** (if enabled)

---

## 🛠️ Technologies Used

* Python
* Matplotlib (plotting)
* NumPy (math operations)

---

## ✔️ Good for LinkedIn & GitHub

This project shows:

* Physics understanding
* ODE solving (RK4)
* Numerical methods
* Visualization skills
* Clean, modular code

Perfect for showcasing technical skills.

---

## 📌 Possible Extensions

* Add linear drag option
* Add real-time animation
* Export graphs to images
* Build a Streamlit web UI
* Create a parameter sweep heat-map

---

## 📝 License

MIT License

---

If you want, I can also generate:

* A logo
* A GIF of the trajectory
* A Streamlit web app version
* A cleaner modular project folder
