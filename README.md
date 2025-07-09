# K-Means from Scratch 🧠

This repository contains a from-scratch implementation of the **K-Means clustering algorithm** in Python. It is a step-by-step educational project designed to understand how K-Means works under the hood — without relying on libraries like `scikit-learn`.

---

## 📌 Project Overview

K-Means is an unsupervised learning algorithm used for clustering data points into groups based on similarity. This implementation:

- Uses **NumPy** for vectorized operations.
- Initializes centroids randomly or with a fixed seed.
- Iteratively updates cluster assignments and centroids until convergence.
- Visualizes the final clustering result.

---

## 🗂️ Project Structure

```
K-means-from-scratch-main/
├── kmeans.py              # Main class implementing the algorithm
├── utils.py               # Helper functions (e.g., distance calc, plotting)
├── test.ipynb             # Notebook to test and visualize the algorithm
├── data/                  # Optional folder with datasets
└── README.md              # You're here
```

---

## 🚀 How to Run

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/K-means-from-scratch.git
cd K-means-from-scratch
```

2. **Install dependencies**
```bash
pip install numpy matplotlib
```

3. **Run the notebook**
```bash
jupyter notebook test.ipynb
```

Or run the script:
```bash
python kmeans.py
```

---

## 📊 Example Output

You can generate and visualize clusters using matplotlib or plotly. See `test.ipynb` for examples.

---

## 🧠 Concepts Covered

- Euclidean distance
- Centroid initialization
- Convergence criteria
- Data visualization
- Cluster evaluation (e.g., inertia)

---

## 📚 References

- [K-Means Clustering - Wikipedia](https://en.wikipedia.org/wiki/K-means_clustering)
- [Scikit-learn User Guide - KMeans](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)

---

## 📜 License

This project is licensed under the MIT License.

---

## ✨ Author

Created with ❤️ by [Your Name](https://github.com/yourusername)
