# Human_Giat_Analysis
# Automated Gait Identification and Analysis via Video Recording

## 📌 Overview
This repository contains my MSc Data Science dissertation project completed at **Nottingham Trent University** (2024).  
The research explores **automating gait analysis using video recordings** to study the effect of different terrains on human gait sequences.  
By applying **computer vision techniques** (pose estimation, intelligent frame selection) and **machine learning models** (Random Forest), the project demonstrates how gait patterns vary across surfaces and provides a framework for automated gait analysis in real-world settings.  

---

## 🎯 Research Objectives
- Develop an automated gait analysis system using video recordings.  
- Implement targeted frame extraction and pose estimation for feature analysis.  
- Analyse gait parameters such as step length, step width, knee angle, stride time, and step time.  
- Evaluate gait across multiple surfaces: **track, pavement, stairs, sand, pebbles, grass, forest, uphill, and downhill**.  
- Train and validate a **Random Forest classifier** to predict gait phases and surface-specific adaptations.  

---

## 🧩 Methodology
1. **Data Collection** – Video recordings of 8 participants walking across terrains.  
2. **Video Processing** – Frame extraction using **OpenCV** and **MediaPipe** for pose estimation.  
3. **Preprocessing** – Frame alignment, noise reduction, and color space conversion.  
4. **Feature Extraction** – Calculation of gait parameters (stride length, knee angle, etc.).  
5. **Machine Learning** – Random Forest model trained to classify gait phases and detect terrain-specific patterns.  
6. **Validation** – Results compared with traditional gait analysis approaches.  

---

## 📊 Results
- Significant **variations in gait parameters** across surfaces were observed.  
- **Stable surfaces** (track, pavement) supported longer stride length and reduced variability.  
- **Unstable terrains** (sand, pebbles, forest) showed shorter stride length, increased knee flexion, and slower step times.  
- The **Random Forest model** achieved **high accuracy (~95–99%)** in predicting gait phases.  
- Findings have implications for:
  - **Clinical rehabilitation** (tailored recovery programs)  
  - **Sports science** (performance optimisation on varied terrains)  
  - **Prosthetics & robotics** (adaptive locomotion systems)  

---

## 🛠️ Tools & Technologies
- **Programming:** Python  
- **Libraries:** OpenCV, MediaPipe, NumPy, Pandas, Matplotlib, Scikit-learn  
- **ML Model:** Random Forest Classifier  
- **Platform:** Jupyter Notebook  

---

## Data Requirement

This project uses video recordings of participants walking on different surfaces (track, pavement, stairs, sand, grass, forest, pebbles, uphill, and downhill).

Due to privacy and research restrictions, the original dataset cannot be shared publicly.

However, you can replicate the pipeline with your own video recordings:

Record a short video of a person walking on different terrains.

Place the videos inside a folder, e.g., data/videos/.

Update the file paths inside the Jupyter notebooks.

## 📂 Repository Structure
