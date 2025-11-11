# Hypothesis Testing : Bombay Hospitality Ltd.

This project demonstrates a "one-tailed hypothesis test (z-test)" to determine whether the average weekly operating cost of "Bombay Hospitality Ltd." is higher than the model’s theoretical prediction.

🧮 Objective
To statistically verify the owners’ claim about increased weekly operating costs using Python.

🧠 Problem Statement
The company believes that its weekly operating cost exceeds the model prediction given by:  

 μ = 1000 + 5 × X̄

Using a sample of 25 weeks, we test this claim at a "5% significance level (α = 0.05)".

📊 Key Steps
1. Define hypotheses:  
   - Null Hypothesis (H₀): μ ≤ μ₀  
   - Alternative Hypothesis (H₁): μ > μ₀  

2. Compute test statistic:
   - \( z = \frac{\bar{x} - μ₀}{σ / \sqrt{n}} \)

3. Compare with critical value (zₐ = 1.645)

4. Decision & Interpretation:  
   - Reject or fail to reject H₀ based on z-statistic  
   - Calculate p-value for additional confirmation  
