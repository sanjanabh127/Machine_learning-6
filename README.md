# Decision Tree Implementation 🌳

This project demonstrates the implementation of a **Decision Tree Classifier** using the **Iris dataset**. The focus is on building, training, evaluating, and improving the decision tree model with techniques like **post-pruning** to reduce overfitting and improve generalization.

---

## Project Structure
- `Decision_Tree_Implementation.ipynb` – Jupyter Notebook containing the full code implementation.  
- Dataset – Iris dataset is loaded from `sklearn.datasets`.  

---

## Features
- Load and preprocess the Iris dataset  
- Split the dataset into training and testing sets  
- Train a **Decision Tree Classifier**  
- Visualize the decision tree structure  
- Evaluate model performance using accuracy score  
- Apply **Post-Pruning** (cost-complexity pruning) to optimize the tree and avoid overfitting  



## Post-Pruning
Decision trees tend to overfit when they grow too deep.  
To handle this, **cost-complexity pruning (`ccp_alpha`)** was applied:  
- Higher `ccp_alpha` → more pruning (simpler tree)  
- Lower `ccp_alpha` → less pruning (more complex tree)  
- Optimal value chosen using cross-validation  



##  Technologies Used
- Python 3  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  



##  Results
- Implemented a baseline Decision Tree Classifier  
- Improved generalization and reduced overfitting using **post-pruning**  
- Achieved good accuracy on test data  



