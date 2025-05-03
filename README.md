# Autonomous Path Mapping Robot  
![Robotics Simulation](https://img.shields.io/badge/Field-Robotics-blue) 
![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python) 
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-5C3EE8?logo=opencv) 
![PyBullet](https://img.shields.io/badge/PyBullet-3.x-000000)

A simulated autonomous robot that processes live overhead camera feed to navigate complex arenas using computer vision and optimal path planning algorithms.



## 🌟 Features
- **Real-time vision processing** using overhead camera feed  
- **Aruco marker detection** for precise localization  
- **Dijkstra's algorithm** implementation for optimal pathfinding  
- **PyBullet simulation** with physics integration  

## � Tech Stack
| Component          | Technology Used         | Industry Equivalent               |
|--------------------|-------------------------|-----------------------------------|
| Physics Engine    | PyBullet                | NVIDIA Isaac Sim                 |
| Computer Vision   | OpenCV + Aruco          | Amazon RoboMaker vision systems  |
| Path Planning     | Dijkstra's Algorithm    | Boston Dynamics path optimization|
| Matrix Operations | NumPy                   | Robotics middleware (ROS)        |

---

## 🚀 Getting Started  

### Prerequisites
- **Python 3.8+** ([Download](https://www.python.org/downloads/))
- **Git** ([Install Guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git))
- **Webcam** (for live demo) or image files (for simulation)

---

### ⚡ Installation

1. **Clone the repository**:
   ```bash
   git clone https://https://github.com/OmSingh314/Autonomous_Path_Mapping_Robot.git
   cd Autonomous_Path_Mapping_Robot
   
2. **Create a virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate    # Windows
   
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt

4. **Running the Simulation**
   - *Requirements*:
   - Webcam connected
   - Aruco markers printed (find templates in /assets/markers)
   ```bash
   python src/main.py --mode live
---

## 🌍 Real-World Applications
This project demonstrates core technologies used in:

### 🏭 Industrial Automation
- **Warehouse Robots**  
  *(Like Amazon Kiva robots)*  
  - Overhead cameras track mobile robots  
  - Aruco markers identify storage bins  
  - Dijkstra's algorithm optimizes pick paths  

### 🚑 Medical Logistics  
- **Hospital Delivery Robots**  
  - Navigate corridors using ceiling markers  
  - Avoid dynamic obstacles (gurneys, people)  
  - Priority routing for emergency supplies  

### 🚜 Agricultural Robotics  
- **Crop Monitoring Robots**  
  - Greenhouse navigation via aerial markers  
  - Optimal path planning between plant rows  
  - Obstacle avoidance for irrigation systems  

### 🚀 Space Exploration  
- **Mars Rover Prototyping**  
  - Simulates terrain navigation  
  - Marker-based position correction  
  - Energy-efficient path planning  

--- 

## 📊 Why This Matters  
This simulation mirrors real industrial systems by:  
1. **Reducing Physical Testing Costs** - Validate algorithms before hardware deployment  
2. **Safety Critical Development** - Test collision scenarios risk-free  
3. **Rapid Prototyping** - Modify arena layouts in seconds vs. physical rebuilds  

---  
