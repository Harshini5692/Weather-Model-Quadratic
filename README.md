# Weather-Model-Quadratic
Weather modeling using quadratic Equation with Waterfall, Iterative, Agile Models.
Weather Modelling Using Quadratic Equation and Waterfall, Iterative, Agile Models
📌 Overview

This project demonstrates how a quadratic equation can be used to predict daily temperature trends. Along with the math model, three software development models (Waterfall, Iterative, Agile) are applied to show different approaches to building the system.

🧮 Quadratic Weather Model

We use the formula:

𝑇
(
𝑡
)
=
𝑎
𝑡
2
+
𝑏
𝑡
+
𝑐
T(t)=at
2
+bt+c

Where:

T(t) = Predicted temperature (°C)

t = Time in hours

a, b, c = Coefficients (assumed or fitted using data)

The program calculates temperature values and plots them using NumPy and Matplotlib.

🛠️ Development Models
🔹 Waterfall Model

Linear phases: Plan → Develop → Test → Deliver

Prediction done in one cycle (e.g., every 6 hours).

🔹 Iterative Model

Small updates in multiple versions.

Iteration 1: Fixed values of a, b, c

Iteration 2: User input for coefficients

Iteration 3: File input/output

Iteration 4: Error handling and validations

🔹 Agile Model (Scrum)

Short sprints with feedback and continuous improvement.

Sprint 1: Basic input/output

Sprint 2: User input for coefficients

Sprint 3: File input/output + testing

Sprint 4: CLI/GUI + deployment

📊 Sample Output
=== WATERFALL MODE ===
Time: 0 hrs  -> Temp: 24.00°C
Time: 6 hrs  -> Temp: 28.40°C
Time: 12 hrs -> Temp: 28.80°C
Time: 18 hrs -> Temp: 25.20°C
Time: 24 hrs -> Temp: 17.60°C

✅ Conclusion

The quadratic model approximates temperature variations.

The Waterfall model provides structure,

The Iterative model adds features step by step,

The Agile model enables teamwork and flexibility.
