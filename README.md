# Student-Performance-Prediction-using-Machine-Learning
In today’s academic environment, students often think about how their daily habits actually affect their performance, but it’s usually based on assumptions rather than anything concrete. This project is an attempt to explore that idea using machine learning.
## 📌 What This Project Does

It builds a prediction model using:

* 📖 Study Hours
* 🏫 Attendance
* 😴 Sleep Hours
* 📊 Previous Scores

👉 Based on these inputs, it predicts your expected exam score.
## 🧠 How the Model Works

We use **Linear Regression**, one of the simplest and most interpretable ML algorithms.

The model learns relationships like:

* More study hours → better score 📈
* Better attendance → higher performance 🎯
* Proper sleep → improved focus 😴

### Conceptual Formula:

```
score = (1.8 × study_hours) + (0.7 × attendance) + 
        (1.0 × sleep_hours) + (0.5 × previous_score) + noise

```

👉 This is not just random — it simulates realistic academic behavior.
