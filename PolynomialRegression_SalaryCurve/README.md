📈 Polynomial Regression – Salary Curve Prediction
🧠 Goal

Predict how salary increases with years of experience when the growth is non-linear (curved) instead of a straight line.

🧩 What I Learned

Linear regression only draws straight lines.

Polynomial regression adds new math features like 
𝑥
2
x
2
, 
𝑥
3
x
3
, etc., so the model can bend and fit curves.

The model can now follow real-life patterns — slow salary growth at first, then steep jumps later.

🧮 Core Math Idea
𝑆
𝑎
𝑙
𝑎
𝑟
𝑦
=
𝑏
0
+
𝑏
1
𝑥
+
𝑏
2
𝑥
2
Salary=b
0
	​

+b
1
	​

x+b
2
	​

x
2

Here 
𝑥
x = Years of Experience.
Adding 
𝑥
2
x
2
 makes the curve flexible to fit data points better.

🧰 Tools Used

Python

scikit-learn → PolynomialFeatures, LinearRegression

matplotlib → for data visualization

🧾 Steps

Created sample data (experience → salary).

Added polynomial feature 
𝑥
2
x
2
.

Trained model with LinearRegression.

Visualized actual vs predicted salaries.

Predicted salary for 12 years of experience.

📊 Output

Blue dots → actual data

Red curve → model prediction

Example: 12 years → Predicted ≈ $350 K
