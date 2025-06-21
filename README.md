# 🧠 Optimized Machine Learning Pipeline for Binary Classification

This project was developed as part of the **Parallel and Distributed Computing (PDC)** course at FAST-NUCES. It focuses on building a high-performance machine learning pipeline using **parallel processing**, **GPU acceleration**, and **efficient resource management** to solve a binary classification problem.

---

## 📌 Objective

To design and implement an optimized ML pipeline that reduces total processing time by at least **70%**, without compromising model performance.

---

## 🔧 Features

- ✅ Data preprocessing (missing values, encoding, normalization)
- ✅ Model training (binary classification using ML/DL)
- ✅ Parallel processing using Python `multiprocessing`
- ✅ GPU acceleration with **PyTorch**
- ✅ Performance comparison: **Serial vs Parallel**, **CPU vs GPU**
- ✅ Metrics: Accuracy, Confusion Matrix, F1-Score
- ✅ Runtime & resource analysis

---

## 🚀 How to Run

1. **Clone the repo:**
   ```bash
   git clone https://github.com/SarmadAli8824/pdc-ml-pipeline.git
   cd pdc-ml-pipeline
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run pipeline:**
   - Serial execution:
     ```bash
     python models/train_serial.py
     ```
   - Parallel execution:
     ```bash
     python models/train_parallel.py
     ```
   - GPU execution (requires CUDA & PyTorch):
     ```bash
     python models/train_gpu.py
     ```

---

## 📊 Results

| Mode           | Accuracy | F1 Score | Time Taken |
|----------------|----------|----------|-------------|
| Serial (CPU)   | 91.5%    | 0.89     | 120s        |
| Parallel (CPU) | 91.5%    | 0.89     | 45s         |
| GPU (PyTorch)  | 92.1%    | 0.91     | 32s         |

> ⚡ Achieved over **70% reduction in runtime** with GPU acceleration.

---

## 🛠️ Technologies Used

- Python, NumPy, Pandas, Scikit-learn, Matplotlib
- PyTorch (GPU acceleration)
- Multiprocessing (Python)
- CUDA-enabled GPU

---

## 📁 Deliverables

- Source code (modular and well-commented)
- Performance Report (Accuracy, Time, Confusion Matrix)
- Final Presentation (Architecture, Results, Comparative Analysis)

---

## 👨‍💻 Authors

- [Sarmad Ali](https://github.com/SarmadAli8824)
- [Abyaz Israr]
- [Mohammad Afnan]
- i221997 – FAST-NUCES Islamabad
