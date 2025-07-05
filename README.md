# QuickHybridSort Analysis

This project analyzes the performance of a hybrid sorting algorithm that switches between QuickSort and Insertion Sort based on a threshold value `k`.

---

### 🧠 Overview

- Written in **Python**
- Investigates the crossover point where **Insertion Sort** becomes more efficient than **QuickSort**
- Compares runtimes on random and sorted arrays of varying sizes
- Uses **matplotlib** to visualize algorithm performance

---

### 📁 Files

- `qhs.py`: Main program that defines and benchmarks the hybrid sort
- `plot.png`: Graph output showing runtime comparisons (auto-generated)

---

### 📊 Output

Running the script generates a plot comparing:
- Pure QuickSort
- Pure Insertion Sort
- QuickHybridSort

The crossover behavior shows where hybridizing the algorithm improves performance.

---

### 📌 Concepts Used

- Divide-and-conquer with **QuickSort**
- Cache-friendly local behavior of **Insertion Sort**
- Hybrid algorithm design for real-world optimization
- Empirical runtime analysis with Python’s `time` module
- Plotting with `matplotlib`

---

### 🔧 How to Run

Make sure you have Python and matplotlib installed.

In your terminal:

```bash
python qhs.py
```

---

### 🧪 Sample Research Focus

> What threshold `k` provides the best runtime when switching from QuickSort to Insertion Sort in practice?

This simulation explores how algorithm selection impacts efficiency on differently sized arrays.

---

### 📍 Author

Max Heitzman  
Texas Tech University – Spring 2025  
🔗 [LinkedIn](https://www.linkedin.com/in/maxheitzman)


