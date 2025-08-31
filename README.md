Recently, I worked on a project applying exploratory data analysis (EDA) and linear regression to predict car prices based on multiple variables.

🔍 Step 1: Understanding the problem
Before jumping into the model, I clarified the objective — whether to estimate the general car price trend or focus on specific models. This helped me think about bias-variance tradeoffs and how to handle outliers.

📊 Step 2: Research & data cleaning
I researched the car industry to understand the data norms and ensure my assumptions aligned with reality. Then, I moved on to data cleaning to handle inconsistencies and missing values.

📈 Step 3: Exploratory Data Analysis (EDA)

Numerical features: Used histograms to inspect distributions and scatter plots to explore correlations with price.

Categorical features: Applied bar charts for distribution and box plots to see how categories impact price.

⚙️ Step 4: Feature engineering & preparation

Created new features using domain knowledge.

Encoded categorical variables and scaled numerical ones to ensure consistency across units.

Performed feature selection to reduce noise and improve generalization.

Applied Ridge regularization to mitigate multicollinearity and prevent overfitting.

🤖 Step 5: Modeling
Using Linear Regression with Ridge regularization, the model achieved:

R² = 0.91 (strong explanatory power)

Mean Squared Error ≈ 2,624 (on average, predictions differ from actual prices by ~$2,600).
