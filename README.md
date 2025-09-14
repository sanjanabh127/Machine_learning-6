# Decision Tree Implementation 🌳

This project demonstrates the implementation of a **Decision Tree Classifier** using the **Iris dataset**.  
The focus is on:
- Training and visualizing a decision tree  
- Applying **pre-pruning techniques** to prevent overfitting  
- Applying **post-pruning (cost-complexity pruning)** to further optimize the model  

---

## Project Structure
- Dataset – Iris dataset loaded directly from `sklearn.datasets`  



## Features
- Load and preprocess the Iris dataset  
- Train a **Decision Tree Classifier**  
- Visualize the tree structure  
- Evaluate accuracy on training and test data  


## ⚡ Pre-Pruning
Pre-pruning involves restricting tree growth **while training** to avoid overfitting.  
Parameters used:
- `max_depth` → maximum depth of the tree  
- `criterion` →criteria for calculating the leaf node  
- `splitter` → the best way to split the tree
- `max_features` → number of features to be used 

This helps in building a smaller, simpler tree that generalizes better.  



## 📊 Post-Pruning
Post-pruning (also known as **cost-complexity pruning**) is applied **after training** the full tree.  


## This helps in reducing overfitting and improves model performance on unseen data. 



## Technologies Used
- Python 3  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  



## Results
- Implemented baseline Decision Tree Classifier  
- Applied **pre-pruning hyperparameters** to control depth and splits  
- Applied **post-pruning** to simplify the tree  
- Achieved good accuracy while reducing overfitting  


