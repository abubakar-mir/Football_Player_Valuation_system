# ⚽ Football Player Valuation System

The Football Player Valuation System is an end-to-end data science pipeline that utilizes Multivariate Linear Regression to estimate professional football players' weekly wages based on their physical and technical attributes. It features a responsive, interactive web application interface built with Gradio.

## 🚀 Key Features
* **Multivariate ML Modeling:** Trained an Ordinary Least Squares (OLS) regression model to eliminate scouting bias.
* **Sports Science Aging Curve:** Built custom progression logic tracking physical decay (Pace/Physic) vs. technical retention (Passing/Defending) over a 5-year career window.
* **Interactive Gradio UI:** A clean, dual-column web panel featuring parameter sliders and real-time inference cards.

## 🛠️ System Architecture
* **Language:** Python 3
* **Libraries:** Scikit-Learn, NumPy, Gradio, Joblib
* **Deployment:** Production script designed for seamless environment replication.

## 📊 Feature Importance Insights
Through data analysis, technical metrics (**Passing** and **Dribbling**) demonstrated a significantly higher statistical correlation with elite tier wage distributions compared to raw physical metrics (**Pace**).
