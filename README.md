# Diet Recommender System 🥗

This project implements a **Diet Recommender System** using Python and Gradio.  
It takes user input such as age, weight, height, and activity level, then suggests a personalized dietary plan.

## 📌 Project Overview
- Collects user health information (age, weight, height, activity level).
- Calculates **BMI** and interprets health categories.
- Generates diet recommendations based on health metrics.
- Provides an **interactive UI** built with Gradio.

## 📂 Datasets Used
- diet_recommendations_dataset.csv
- food.csv

## ⚙️ Technologies Used
- Python 3
- Gradio (for interactive web UI)
- Pandas, NumPy (if extended data handling is used)

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/MuhammadAsad29/Diet-recommendation-system
   cd diet-recommender
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook diet_recommender.ipynb
   ```

4. Run the Gradio app inside the notebook:
   ```python
   demo.launch(inline=True)
   ```

## 🎯 Features
- BMI calculation and interpretation.
- Personalized diet suggestions based on inputs.
- Interactive Gradio interface for real-time recommendations.

## 📝 Author
Developed by Muhammad Asad.
