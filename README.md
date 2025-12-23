# Academic Comfort Prediction using Fuzzy Inference System (FIS)

## 📘 Project Overview
This project implements a **Fuzzy Inference System (FIS)** to predict a student’s **Academic Comfort Level** based on their academic performance.  
The system uses **fuzzy logic principles** to model uncertainty and gradual transitions in educational assessment instead of rigid grading thresholds.

The project is developed as part of a **Problem-Based Learning (PBL)** assignment for the **Knowledge Representation & Reasoning (KRR)** course.

---

## 🎯 Objective
To design and evaluate a **Mamdani-type Fuzzy Inference System** that estimates academic comfort using:
- Math score
- Reading score
- Writing score

The output is a **continuous comfort score** ranging from *Very Low* to *Very High*.

---

## 📂 Repository Structure
📁 Academic-Comfort-FIS/
│
├── Krr_pbl.ipynb # Main implementation notebook
├── StudentsPerformance.csv # Dataset (if included)
├── README.md # Project documentation


---

## 🧠 Fuzzy System Design

### 🔹 Input Variables
| Variable | Range | Linguistic Terms |
|--------|-------|-----------------|
| Math Score | 0–100 | Low, Medium, High |
| Reading Score | 0–100 | Low, Medium, High |
| Writing Score | 0–100 | Low, Medium, High |

### 🔹 Output Variable
| Variable | Range | Linguistic Terms |
|--------|-------|-----------------|
| Academic Comfort | 0–100 | Very Low, Low, Moderate, High, Very High |

---

## 📐 Membership Functions
- **Input Variables**: Triangular membership functions
- **Output Variable**: Combination of Trapezoidal and Gaussian functions

This hybrid approach ensures:
- Interpretability
- Smooth transitions
- Reduced discontinuities

---

## 📜 Fuzzy Rule Base
- Total Rules: **15**
- Inference Type: **Mamdani**
- Logical Operators: **AND**
- Defuzzification Method: **Centroid**

Example rule:
*IF Math is High AND Reading is High AND Writing is High
THEN Academic Comfort is Very High**

---

## 🧪 Experiments & Evaluation
The system is evaluated using:
- Rule consistency analysis
- Sensitivity testing
- Baseline comparison with crisp thresholds

### 📊 Results
| Metric | Value |
|------|-------|
| Mean Absolute Error (MAE) | 4.50 |
| Accuracy Proxy | 88.5% |
| User Satisfaction Proxy | 72.3% |

---

## 🛠️ Technologies Used
- Python
- NumPy
- Matplotlib
- scikit-fuzzy
- Jupyter Notebook

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/AbdulGhani002/knowledge-representation-and-reasoning-project.git
Navigate to the project directory:
cd your-repo-name
Open the notebook:
jupyter notebook Krr_pbl.ipynb
👥 Group Members

Usman — F23607004

Abdul Ghani — F23607005

Muhammad Anas — F23607044

Jawaria Sabir — F23607040

Hira Hassan — F23607055

Hamza Abdul Karim — F23607046
🎓 Academic Context

Course: Knowledge Representation & Reasoning
Department: Computer Science
University: National University of Technology
Instructor: Lec. Faria Sajjad

📌 Conclusion

This project demonstrates how fuzzy logic can be effectively applied to educational analytics, offering interpretable and flexible assessment mechanisms that outperform rigid grading systems.

📜 License

This project is for academic and educational purposes only.


---

### ✅ If you want, I can also:
- Customize it to **exact GitHub repo name**
- Add **badges** (Python, Jupyter, License)
- Make a **shorter README** for cleaner presentation
- Align it strictly with **university submission standards**

Just tell me 👍
