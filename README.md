# 📊 Linear Regression From Scratch  

A simple implementation of **Linear Regression** built from scratch (without using libraries like scikit-learn) to demonstrate the core concepts of Machine Learning.  

---

## 🚀 Getting Started  

### Clone the repository  
```bash
git clone https://github.com/santhoshclx/linear-regression-from-scratch.git
cd linear-regression-from-scratch
```

### Run the project  
Make sure you have Python 3 installed. Then run:  
```bash
python linear_regression.py
```

---

## 📖 Features  

- Implementation of **Simple Linear Regression** using:  
  - Mean Squared Error (MSE) as the cost function  
  - Gradient Descent for optimization  
- Predicts outputs for given inputs  
- Plots the regression line vs data points (if matplotlib is installed)  

---

## 📂 Project Structure  
```
linear-regression-from-scratch/
│── data.csv                # Sample dataset (optional)
│── linear_regression.py    # Core implementation
│── README.md               # Documentation
```

---

## 🧮 Example  

```python
from linear_regression import LinearRegression  

# Sample data
X = [1, 2, 3, 4, 5]  
y = [2, 4, 6, 8, 10]  

# Train model
model = LinearRegression(learning_rate=0.01, epochs=1000)  
model.fit(X, y)  

# Predictions
print(model.predict([6, 7]))  # Example output: [12, 14]
```

---

## 📊 Visualization  

If you install matplotlib:  
```bash
pip install matplotlib
```

You can visualize the dataset and regression line.  

---

## 🎯 Learning Objectives  

- Understand the math behind linear regression  
- Implement gradient descent step by step  
- Gain intuition on cost functions & optimization  

---

## 📱 Future Improvements  

- Add support for **multiple linear regression**  
- Include **polynomial regression**  
- Add performance metrics (R² Score, MAE, etc.)  

---

## 🤝 Contributing  

Contributions are welcome! Feel free to fork this repo and submit a pull request.  

---

## 📜 License  

This project is licensed under the MIT License.  
