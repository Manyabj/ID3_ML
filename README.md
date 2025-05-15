## 🧠 ID3 Algorithm for Decision Tree

The **ID3 (Iterative Dichotomiser 3)** algorithm is a classical decision tree learning method developed by Ross Quinlan. It is widely used for classification problems in machine learning.

### 🔍 How It Works

ID3 builds a decision tree using a top-down, greedy approach by:

1. **Calculating Entropy** – Measures the impurity or randomness in the data.
2. **Calculating Information Gain** – Determines how much information a feature gives about the class.
3. **Choosing the Best Feature** – The feature with the highest information gain is selected as a decision node.
4. **Recursive Splitting** – The dataset is split based on the best feature, and the process repeats on each branch.

### 📊 Key Concepts

- **Entropy (H):**
 
- **Information Gain (IG):**

 

### ⚙️ Features Used in the Dataset

- `CGPA`
- `Interactiveness`
- `Practical Knowledge`
- `Communication Skills`

These features are used to predict the final class: **Job Offer (Yes/No)**.

### 📈 Output

The output of the ID3 algorithm is a decision tree that can classify new data based on learned patterns. The tree is also visualized using **Graphviz** for better understanding.

### 🖼️ Tree Visualization

The decision tree is rendered and saved as an image using the `graphviz` Python package:

```bash
pip install graphviz
