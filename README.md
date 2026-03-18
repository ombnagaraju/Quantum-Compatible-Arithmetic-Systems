# Hardware-Validated Parity-Preserving Reversible Vedic Multiplier

This repository contains supporting materials for the manuscript:

**"Hardware-Validated Parity-Preserving Reversible Vedic Multiplier with Clifford+T Fault-Tolerant Realization for Quantum-Compatible Arithmetic Systems"**

Submitted to *e-Prime – Advances in Electrical Engineering, Electronics and Energy*.

---

## ✅ Reproducibility Status

- ✔ Fully reproducible
- ✔ Hardware validated (IBM Quantum)
- ✔ Noise-aware simulation included
- ✔ Application-level benchmarking included

---

## 📌 Overview

This work presents a parity-preserving reversible Vedic multiplier architecture with:

- Reduced quantum cost
- Clifford+T fault-tolerant decomposition
- Hardware validation on IBM Quantum backend (ibm_brisbane)
- Image processing application benchmarking

---

## 📁 Repository Structure

/notebooks/       → Jupyter notebooks (main experiments)
/data/            → Sample images
/results/         → Output plots
requirements.txt  → Dependencies
README.md         → Documentation

---

## ⚙️ Requirements

pip install -r requirements.txt
or
# Core quantum stack
!pip install qiskit==2.3.0
!pip install qiskit-aer==0.17.2
!pip install qiskit-ibm-runtime==0.45.0

# Scientific stack
!pip install numpy==1.26.4
!pip install matplotlib==3.8.4
!pip install pillow==10.3.0

# Metrics
!pip install scipy==1.13.1
!pip install scikit-image==0.23.2

# Notebook environment
!pip install jupyter==1.0.0 notebook==7.2.1 ipykernel==6.29.4

---

## ▶️ How to Run (IMPORTANT FOR REVIEWERS)

### Step 1: Prepare Files

- Download the notebook:
  QIP Python Codes E-prime.ipynb
- Place your input image (e.g., cameraman.png, and peeprs.png) in the same folder as the notebook  

👉 Both files must be in the same directory

---

### Step 2: Launch Jupyter Notebook

jupyter notebook

---

### Step 3: Open Notebook

Open:
QIP Python Codes E-prime.ipynb

---

### Step 4: Execute

- Run all cells sequentially  
- Ensure no cells are skipped  

---

## 📊 Expected Outputs

After execution, you should observe:

- ✔ Quantum circuit visualization  
- ✔ Simulation histogram (ideal case)  
- ✔ Noise comparison results  
- ✔ Image processing outputs  
- ✔ PSNR and SSIM values  

---

## 🧪 Experimental Components

- Reversible Vedic multiplier (2×2 and 4×4)  
- Clifford+T decomposition analysis  
- Noise-aware simulation  
- IBM Quantum hardware execution  
- Image processing applications  

---

## 📊 Evaluation Metrics

- Quantum Cost (QC)  
- T-count and T-depth  
- Fidelity analysis  
- PSNR  
- SSIM  

---

## ☁️ Quantum Backend

- IBM Quantum Platform  
- Backend: ibm_brisbane  
- Shots: 1024  

---

## 🔁 Reproducibility

All results in the manuscript can be reproduced using the provided notebook and dataset.

---

## 👤 Author

Dr. Naga Raju Bathula  
VIT-AP University

---

## 📩 Contact

nagaraju.23phd7022@vitap.ac.in
