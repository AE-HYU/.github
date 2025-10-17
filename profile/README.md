<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=AE-HYU&fontSize=90&animation=fadeIn&fontAlignY=38&desc=F1Tenth%20Autonomous%20Racing%20Team&descAlignY=65&descAlign=62)

### 🏎️ **Building F1Tenth Autonomous Racing Cars** 🏎️

**Automotive Engineering - Hanyang University**  
**Racing towards autonomous excellence in F1Tenth competition**

</div>

---

<div align="center">

## **Our Team**

</div>

**AE-HYU** is a student-led autonomous racing team from Hanyang University's Department of Automotive Engineering, dedicated to pushing the boundaries of autonomous vehicle technology through competitive F1Tenth racing.

### **Team Leader**
- **Jisang Yun**
  - Perception (Localization - MCL)
  - Project Management (Git, GitHub)

### **Team Members**

**Perception Team**
- **Minki Ju** - Localization (MCL), Code Maintenance
- **Dahye Kim** - Object Detection, Team Schedule Organization

**Planning Team**
- **Minwon Lee** - Global Planning, Documentation (Notion)
- **Yongsu Lee** - Local Planning, File Management

**Control Team**
- **Seokyeong Jang** - MAP Controller, External Cooperation

<div align="center">

## **Project Overview**

</div>

We are developing autonomous F1Tenth racing cars for competition. Our team focuses on three core areas:

<div align="center">

| **Perception** | **Planning** | **Control** |
|:---:|:---:|:---:|
| Sensor data processing and environment understanding | Path planning and decision-making algorithms | Vehicle dynamics and actuation systems |
| SLAM, Localization, Object Detection | Global & Local Trajectory Planning | Controller Implementations |

</div>

<div align="center">

## **Repository Architecture**

</div>

### **Technology Stack**

<div align="center">

<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white">
<img src="https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white">

</div>

### **Key Repositories**

<div align="center">

| **Repository** | **Category** | **Description** |
|:---|:---:|:---|
| [F1Tenth_System](https://github.com/AE-HYU/f1tenth_system.git) | Core Systems | Basic package for vehicle operation |
| [AE_HYU_Bundle](https://github.com/AE-HYU/ae_hyu_bundle.git) | Core Systems | Integrated autonomous system bundle |
| [Global_Planner](https://github.com/AE-HYU/global_planner.git) | Planning | Global path planning algorithms |
| [Cartographer_SLAM](https://github.com/AE-HYU/cartographer_slam.git) | Perception | SLAM and mapping system |

</div>

### **Main Repository Structure**
```
ae_hyu_bundle/
├── ae_hyu_database/                # Database for maps and raceline
├── src/
│   ├── ae_hyu_monitor/             # RViz monitoring and visualization
│   ├── ae_hyu_msgs/                # Common message definitions
│   ├── cartographer/               # Cartographer SLAM
│   ├── perception_ws/
│   │   ├── monte_carlo_localization/   # Monte Carlo Localization (MCL - Particle Filter)
│   │   └── object_detection/       # Object detection
│   ├── planning_ws/
│   │   ├── planner_pkg/            # Cubic spline path planner (main)
│   └── control_ws/
│       └── crazy_controller/       # Vehicle dynamics controller
```

<div align="center">

## **Getting Started**

</div>

### **Prerequisites**
- **ROS2 Humble** or higher
- **Ubuntu 22.04 LTS**
- **F1Tenth Hardware Platform**
- **Dependencies**: OpenCV, Eigen3

### **Installation**

```bash
# Clone the repository
git clone https://github.com/AE-HYU/ae_hyu_bundle.git

# Navigate to workspace
cd ae_hyu_bundle

# Build the workspace
colcon build --symlink-install

# Source the environment
source install/setup.bash
```


---

<div align="center">

**AE-HYU - Racing towards autonomous excellence**

*F1Tenth Autonomous Racing Team*

</div>
