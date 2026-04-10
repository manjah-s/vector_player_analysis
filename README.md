# ⚽ Player Vector Analysis

## 📌 Overview
This project models football (or basketball) players as high-dimensional vectors and uses vector mathematics to compare, rank, and visualize player similarity.

Each player is represented as a vector of numerical attributes such as:
- Goals
- Assists
- Speed
- Stamina
- Passing
- Dribbling
- Defense

Using these vectors, we compute similarity between players and identify the most balanced players.

---

## 🧠 Core Concepts

- Vectors & Scalars  
- Dot Product  
- L1 and L2 Norms  
- Cosine Similarity  
- Unit Vectors  
- Vector Normalization  

---

## 🧮 Mathematics Used

### 🔹 Dot Product
The dot product between two vectors:

$$
\mathbf{a} \cdot \mathbf{b} = \sum_{i=1}^{n} a_i b_i
$$

---

### 🔹 L2 Norm (Euclidean Length)
Measures the magnitude of a vector:

$$
||\mathbf{v}||_2 = \sqrt{\sum_{i=1}^{n} v_i^2}
$$

---

### 🔹 Cosine Similarity
Measures the angle between two vectors:

$$
\cos(\theta) = \frac{\mathbf{a} \cdot \mathbf{b}}{||\mathbf{a}|| \cdot ||\mathbf{b}||}
$$

---

### 🔹 Unit Vectors
A normalized vector with length = 1:

$$
\hat{v} = \frac{v}{||v||}
$$

---

## ⚙️ Features

- Represent players as NumPy vectors  
- Compute similarity using:
  - Dot product
  - Cosine similarity (implemented from scratch)  
- Normalize vectors for fair comparison  
- Rank players by similarity  
- Find the most balanced player using L2 norm  
- CLI tool for querying similar players  
- Visualizations:
  - Radar charts
  - Bar charts
  - 2D vector projections (quiver plots)

---

## 📂 Project Structure

```
player-vector-analysis/
│
├── data/
├── src/
├── notebooks/
├── outputs/
```

---

## ▶️ How to Run

### 1. Clone the repository
```
git clone https://github.com/your-username/player-vector-analysis.git
cd player-vector-analysis
```

---

### 2. Install dependencies
```
pip install -r requirements.txt
```

---

### 3. Run the main program
```
python notebook/project1.pynb
```

---

### 4. Run CLI tool
```
python -m src.cli "Messi"
```

Example output:
```
Top 3 similar players:
1. Neymar (0.91)
2. Mbappé (0.89)
3. Salah (0.87)
```

---

## 📊 Sample Outputs

### 🔹 Radar Chart
![Radar Chart](outputs/charts/radar.png)

### 🔹 Similarity Comparison
![Bar Chart](outputs/charts/bar.png)

### 🔹 2D Vector Projection
![Scatter Plot](outputs/charts/scatter.png)

---

## 📘 Jupyter Notebook

See:
```
notebooks/project1.ipynb
```

This notebook explains:
- Vector operations step-by-step
- Dot product intuition
- Cosine similarity derivation (from first principles)

---

## 🎯 Key Insight

By converting players into vectors, we can compare playing styles mathematically instead of relying on subjective opinions.

---

## 🚀 Future Improvements

- Add clustering of players
- Support multiple leagues
- Interactive dashboard

---

## 👨‍💻 Author
manjah-s# vector_player_analysis
