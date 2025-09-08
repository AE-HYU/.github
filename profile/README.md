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

### **Leadership**
- **Name** - Team Leader
  - Role description and expertise

### **Team Members**
- **Name** - Role
  - Responsibilities and expertise
- **Name** - Role
  - Responsibilities and expertise
- **Name** - Role
  - Responsibilities and expertise
- **Name** - Role
  - Responsibilities and expertise

<div align="center">

## **Project Overview**

</div>

We are developing autonomous F1Tenth racing cars for competition. Our team focuses on three core areas:

<div align="center">

| **Perception** | **Planning** | **Control** |
|:---:|:---:|:---:|
| Processing sensor data and environment understanding | Path planning and decision making algorithms | Vehicle control and actuation systems |
| SLAM, Localization, Object Detection | Global & Local trajectory planning | Controller implementations |

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
| [F1Tenth_System](https://github.com/AE-HYU/f1tenth_system.git) | Core Systems | Basic package to drive vehicle |
| [AE_HYU_Bundle](https://github.com/AE-HYU/ae_hyu_bundle.git) | Core Systems | Core bundle package for autonomous system |
| [Global_Planner](https://github.com/AE-HYU/global_planner.git) | Planning | Global Path Planner |
| [Cartographer_SLAM](https://github.com/AE-HYU/cartographer_slam.git) | Perception | Mapping and SLAM system |

</div>

### **Main Repository Structure**
```
ae_hyu_bundle/
├── perception/               # Perception algorithms
├── planning/                 # Path planning systems
└── control/                  # Control systems
```

<div align="center">

## **Getting Started**

</div>

### **Prerequisites**
- **ROS2** (Humble/Iron recommended)
- **Ubuntu 22.04 LTS**
- **F1Tenth hardware platform**

### **Quick Setup**

<div align="center">

| **Step** | **Command** | **Description** |
|:---:|:---|:---|
| **1** | `git clone <repo_url>` | Clone main repository |
| **2** | `cd workspace && colcon build` | Build workspace |
| **3** | `source install/setup.bash` | Source environment |

</div>

### **Usage Guidelines**

<div align="center">

| **User Level** | **Starting Point** | **Focus Areas** |
|:---:|:---:|:---|
| **Beginners** | `base_code` | Understanding F1Tenth basics |
| **Developers** | `main_workspace` | Algorithm development and testing |
| **Competition** | `race_config` | Competition deployment |

</div>

---

<div align="center">

**AE-HYU - Racing towards autonomous excellence**

*F1Tenth Autonomous Racing Team*

</div>
