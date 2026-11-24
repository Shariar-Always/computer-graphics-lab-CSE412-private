# 🎨 Computer Graphics Lab (CSE412)

![Language](https://img.shields.io/badge/Language-C%20%7C%20C%2B%2B-blue.svg)
![Graphics API](https://img.shields.io/badge/API-OpenGL%20%7C%20GLUT-red.svg)
![Course](https://img.shields.io/badge/Course-CSE412%20Computer%20Graphics%20Lab-orange.svg)
![University](https://img.shields.io/badge/University-Daffodil%20International%20University-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)

A comprehensive academic repository containing all lab experiments, algorithms, 2D/3D transformations, animations, lab evaluations, and documentation for **CSE412: Computer Graphics Lab** at **Daffodil International University (DIU)**.

---

## 📌 Table of Contents
- [📖 Overview & Objectives](#-overview--objectives)
- [🛠️ Technologies & Tools](#️-technologies--tools)
- [📂 Lab Curriculum & Repository Structure](#-lab-curriculum--repository-structure)
- [⚙️ Setup & Environment Configuration](#️-setup--environment-configuration)
- [👨‍💻 Author & Academic Information](#-author--academic-information)
- [📜 Privacy Notice & License](#-privacy-notice--license)

---

## 📖 Overview & Objectives
This repository documents practical implementations of fundamental and advanced Computer Graphics principles using **OpenGL and GLUT**:
- **Primitive Drawing:** Points, Lines, Triangles, Rectangles, and Custom Polygons.
- **Line Drawing Algorithms:** DDA (Digital Differential Analyzer) & Bresenham's Line Algorithm (All octants / slopes).
- **Circle & Curve Generation:** Midpoint Circle Algorithm & S-Shape curves.
- **2D Transformations:** Translation, Rotation, Scaling, Reflection, and Shearing.
- **3D Transformations:** 3D Pyramid modeling with translation, scaling, and rotation.
- **2D Computer Animation:** Moving shapes, wave animations (e.g., Animated Bangladesh Flag), and robotic kinematics.
- **Evaluations:** Lab Evaluation 01 & Lab Evaluation 02 (Robot Animation).

---

## 🛠️ Technologies & Tools
- **Languages:** C, C++
- **Graphics Library:** OpenGL (Open Graphics Library)
- **Toolkit:** GLUT / FreeGLUT
- **Compiler:** MinGW (GCC / G++)
- **IDE:** Visual Studio Code
- **Modeling & Plotting:** GeoGebra (for geometric verification)

---

## 📂 Lab Curriculum & Repository Structure

```bash
computer-graphics-lab-CSE412-private/
│
├── lab-01/                                      # Basic OpenGL Primitives
│   ├── 1 draw_point/                            # Points rendering
│   ├── 2 draw_line/                             # Lines rendering
│   ├── 3 draw_triangle/                         # Triangles rendering
│   ├── 4 draw_rectangle/                        # Rectangles rendering
│   ├── 5 draw_house_shape/                      # Composite house model
│   └── lab_report/                              # Lab 1 Report PDF
│
├── lab-02/                                      # Polygons & Multi-Shape Drawing
│   ├── draw_multiple_polygons/                  # Convex & concave polygons
│   └── lab_report/                              # Lab 2 Report PDF
│
├── lab-03/                                      # DDA Line Algorithm
│   ├── dda-line-opengl/                         # DDA line drawing implementation
│   └── lab_report/                              # Lab 3 Report PDF
│
├── lab-04/                                      # Bresenham's Line Algorithm
│   ├── Implementation of Bresenham.../
│   │   ├── basic_code/                          # Basic Bresenham line algorithm
│   │   └── bresenham_all_cases/                 # Generalized for all slopes (|m| < 1, |m| >= 1)
│   └── lab_report/                              # Lab 4 Report PDF
│
├── lab-05 (Lab Evaluation-01)/                  # Trapezium Drawing using DDA & Bresenham
│   ├── Drawing a Trapezium.../                  # Trapezium implementation & GeoGebra file
│   └── lab_report/                              # Lab Evaluation 1 Report PDF
│
├── lab-06/                                      # Circle Drawing Algorithms
│   ├── Implementation of Midpoint Circle.../
│   │   ├── 1_midpoint-circle.cpp                # Standard Midpoint Circle algorithm
│   │   ├── 2_s-shape-midpoint.cpp               # S-Shape curve generation
│   │   └── 3_circle-opengl.cpp                  # Native OpenGL circle rendering
│   └── lab_report/                              # Lab 6 Report PDF
│
├── lab-07/                                      # 2D Geometric Transformations
│   ├── 01 Drawing Four Colored Hexagons/        # 2D Translation
│   ├── 02 Scaling of a Hexagon/                 # 2D Scaling
│   ├── 03 Translation & Rotation/               # 2D Rotation
│   ├── 04 Reflection of a Hexagon/              # 2D Reflection
│   ├── 05 Shearing of a Hexagon/                # 2D Shearing
│   ├── 06 Animated Bangladesh Flag/             # Flag wave animation
│   ├── 07 Bangladesh Flag Transformations/      # All 2D transformations applied
│   └── lab_report/                              # Lab 7 Report PDF
│
├── lab-08/                                      # 3D Transformations
│   ├── 01 Pyramid with 3D Translation/          # 3D translation
│   ├── 02 Pyramid with 3D Scaling/              # 3D scaling
│   ├── 03 Pyramid with 3D Rotation/             # 3D rotation
│   └── lab_report/                              # Lab 8 Report PDF
│
├── lab-09/                                      # 2D Animations
│   ├── 01 OpenGL Moving Shapes Animation/       # Continuous dynamic transformations
│   └── lab_report/                              # Lab 9 Report PDF
│
├── lab-10 (Lab Evaluation-02)/                  # Advanced OpenGL Animation
│   ├── robot-animation-opengl.cpp               # Animated Robot with interactive kinematics
│   └── lab_report/                              # Lab Evaluation 2 Report PDF
│
└── note.txt                                     # Environment setup reference
```

---

## ⚙️ Setup & Environment Configuration

To configure the development environment in Visual Studio Code with MinGW and FreeGLUT on Windows, follow the setup guide:

👉 **Setup Guide Repository:** [graphics-design-vscode-environment-setup](https://github.com/Shariar-Always/graphics-design-vscode-environment-setup)

### Compilation Command (MinGW)
```bash
g++ filename.cpp -o app -lfreeglut -lopengl32 -lglu32
./app
```

---

## 👨‍💻 Author & Academic Information

* **Student Name:** Shahriar Ahammed
* **GitHub:** [@Shariar-Always](https://github.com/Shariar-Always)
* **Portfolio:** [shariarahamed.com](https://www.shariarahamed.com)
* **Student ID:** 0242310005101019
* **Department:** Computer Science and Engineering
* **University:** Daffodil International University (DIU)
* **Course:** CSE412 – Computer Graphics Lab

---

## 📜 Privacy Notice & License

This repository is maintained for academic evaluation and personal learning reference. All materials, source codes, and reports are completed as part of the official curriculum at Daffodil International University.
