

## **Combinatorial Growth of Polynomial Features — Python Visualizations**

This project demonstrates **combinatorial growth** in machine learning caused by **Polynomial Feature Expansion**. Using Python, NumPy, Matplotlib, and Seaborn, the code visualizes how the number of polynomial features explodes as you increase:

* Number of original features (**n**)
* Polynomial degree (**d**)

The project includes:

* Heatmap of combinatorial feature growth
* 3D surface plot of feature explosion
* Line plots for fixed feature counts
* Formula-based feature computation
* Clean, modular Python code

---

## Why This Matters

Polynomial expansion is widely used in:

* Linear regression
* Logistic regression
* AdaBoost & Gradient Boosting
* SVM with polynomial kernels
* Feature engineering pipelines

---

## Project Structure**

```
├── combinatorial_growth.py     # Full Python code with all visualizations
├── README.md                    # Documentation (this file)
└── requirements.txt             # Dependencies
```

---

## installation**

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/combinatorial-growth-polynomials.git
cd combinatorial-growth-polynomials
```

### 2. Create & activate virtual environment (optional)

```bash
python -m venv venv
venv\Scripts\activate        # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## How to Run

Run the full visualization script:

```bash
python combinatorial_growth.py
```

This will generate:

* Heatmap
* 3D feature explosion surface
* Line plots showing feature growth

All visualizations appear inline in windows or Jupyter.

---


* Fixed number of features (e.g., n=10)
* Multiple n values (2, 5, 10, 15)

Shows exponential-like growth trends.

---


## Technologies Used

* Python
* NumPy
* Matplotlib
* Seaborn
* scikit-learn (for consistency and conventions)

---

## requirements.txt

```
numpy
matplotlib
seaborn
scikit-learn
```

---

## Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss what you’d like to propose.

---

## License

This project is open-source under the **MIT License**.

---

## If this helped you…

Please **star the repository**, share it, or cite it in your project!
It helps more learners understand combinatorial growth in machine learning.

---


