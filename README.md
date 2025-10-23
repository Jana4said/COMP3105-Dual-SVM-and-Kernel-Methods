# Dual SVM and Kernel Methods (COMP 3105)


A **Machine Learning project** that implements the **dual form of Support Vector Machines (SVM)** and explores different **kernel functions** to classify MNIST digits (4 vs 9).  
This project demonstrates how to apply convex optimization and kernel-based learning techniques to real-world data.

---

## Features 
- Implements **dual-form SVM** using `cvxopt`  
- Supports multiple **kernel functions**: Linear, Polynomial, Gaussian  
- Performs **cross-validation** for λ (regularization parameter) selection  
- Compares model performance across different kernels  
- Includes reproducible setup via `requirements.txt`

---

## Core Concepts 
- Dual formulation of SVM  
- Kernel methods (Polynomial & Gaussian)  
- Cross-validation and hyperparameter tuning  
- Model evaluation and analysis  
- Application to real dataset (MNIST 4 vs 9)

---

## File Overview 
| File | Description |
|------|--------------|
| `A2codes.py` | Python implementation of Dual SVM and kernel methods |
| `A2 report.pdf` | Report summarizing results and kernel performance |
| `requirements.txt` | Required dependencies for execution |

---

## Technologies Used 
- **Python 3.10+**  
- **NumPy**  
- **CVXOPT**  
- **Matplotlib**  
- **Pandas**

---


**Gana Said**   
Bachelor of Computer Science (AI Stream) – Carleton University  
📧 [janasaid@cmail.carleton.ca](mailto:janasaid@cmail.carleton.ca)

---

## How It Works
1. Loads MNIST subset for digits 4 and 9.  
2. Trains SVM models using different kernels (Linear, Polynomial, Gaussian).  
3. Uses cross-validation to select the best λ and kernel parameters.  
4. Evaluates model accuracy and compares results in a summary table.  
5. Presents conclusions and visual results in the report.

---
 *This project showcases mathematical depth and strong practical skills in implementing kernel-based learning models using SVMs.* 
