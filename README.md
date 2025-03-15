# **GNCsim: Python Library for Satellite & Launch Vehicle GNC**  

🚀 **GNCsim** is a modular Python library for **Guidance, Navigation, and Control (GNC)** of satellites and launch vehicles. It includes **trajectory simulation, attitude dynamics, and interactive 3D visualization** for better analysis and debugging.  

---

## **Features**  
✔ **Guidance & Trajectory Simulation** – Solve optimal flight paths for rockets and satellites.  
✔ **Attitude Dynamics & Control** – Quaternion-based attitude propagation and stabilization.  
✔ **Modular Design** – Easily extendable with additional features.  
✔ **Realistic 3D Visualization** – Interactive rocket tracking with lighting, camera control, and animations.  
✔ **Multi-Environment Support** – Simulates both space and atmospheric flight.  

---

## **Installation**  
### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/YOUR_USERNAME/GNCsim.git
cd GNCsim
```

### **2️⃣ Install Dependencies**  
```bash
pip install numpy matplotlib vpython scipy
```

---

## **Usage**  
### **1️⃣ Run a Simple Rocket Trajectory Simulation**  
```python
from gnc_sim import RocketSimulator

sim = RocketSimulator()
sim.run_simulation()
sim.visualize()
```

### **2️⃣ Simulate Attitude Dynamics**  
```python
from gnc_sim import AttitudeSimulator

attitude = AttitudeSimulator(initial_quaternion=[1, 0, 0, 0])
attitude.run_simulation()
attitude.visualize()
```

### **3️⃣ Interactive 3D Rocket Visualization**  
```python
from gnc_sim.visualization import visualize_rocket

visualize_rocket(states, obj_file="rocket.obj")
```

---

## **Development**  
### **Contribute to the Project**  
1. **Fork the repo** on GitHub.  
2. **Create a new branch** for your feature.  
3. **Commit your changes** and open a pull request.  

---

## **Planned Features 🚀**  
- 🔥 **Exhaust Flame Animation**  
- 🌍 **Realistic Atmospheric Effects**  
- 📡 **GPS & Sensor Simulation**  
- 🛰️ **Advanced Satellite GNC Algorithms**  

---

## **License**  
This project is licensed under the **MIT License** – see the `LICENSE` file for details.  

---

## **Author**  
Developed by **Yajur Kumar** – GNC Engineer specializing in satellite and rocket control.  
```

### **How to Save It**  
1. Create a file in your project directory:  
   ```bash
   touch README.md
   ```
2. Open `README.md` in a text editor and **paste** the content above.  
3. Save and commit:  
   ```bash
   git add README.md
   git commit -m "Added project README"
   git push origin main
   ```
