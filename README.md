# 6-DOF Robotic Arm (Autodesk Fusion 360)

## 📌 Project Overview
This repository contains the complete 3D CAD models and mechanical assemblies for a 6-Degree-of-Freedom (6-DOF) robotic arm. Designed entirely in Autodesk Fusion 360 during an internship at Softnexis, this project demonstrates advanced mechanical design, joint kinematics, and industrial robotics principles. 

The arm is structured to mimic the articulation of an industrial manipulator, capable of complex spatial positioning and orientation.

## 🛠️ Design Specifications & Features
* **Software Used:** Autodesk Fusion 360
* **Degrees of Freedom:** 6 independent axes for full spatial manipulation (Base, Shoulder, Elbow, Wrist Pitch, Wrist Roll, Wrist Yaw).
* **Mechanical Assembly:** Fully constrained joint connections (revolute joints) allowing for accurate motion studies and kinematic testing within the CAD environment.
* **Manufacturing Readiness:** Components are optimized for real-world fabrication, with clearances and tolerances considered for 3D printing or CNC machining.
* **Export Formats:** Includes native Fusion 360 files (`.f3d`), standard exchange files (`.step`), and mesh files (`.stl`) for easy 3D printing.

## 📂 Repository Structure
* `/Fusion360_Source/` - Contains the native `.f3d` assembly and individual part files.
* `/STEP_Files/` - Universal 3D models for importing into SolidWorks, Inventor, or other CAD software.
* `/STL_Files/` - Exported meshes ready for slicing and 3D printing.
* `/Renders/` - High-quality rendered images of the completed robotic arm.

## 🚀 How to View and Use the Models
**If you have Autodesk Fusion 360:**
1. Download or clone this repository.
2. Open Fusion 360 and open the Data Panel.
3. Click `Upload` and select the main `.f3d` assembly file from the `/Fusion360_Source/` folder.
4. Once uploaded, open the file to view the model, inspect the sketches, and animate the revolute joints.

**If you do not have CAD software:**
You can easily view the `.step` or `.stl` files using free online 3D viewers (like Autodesk Viewer) or simply click on the `.stl` files right here in GitHub to use its built-in 3D viewer.

## 🔮 Future Improvements
* [ ] Perform structural Finite Element Analysis (FEA) on the primary load-bearing linkages.
* [ ] Select and map specific NEMA stepper motors and servo brackets to the joints.
* [ ] Develop the inverse kinematics algorithms using Python to control the physical prototype.
