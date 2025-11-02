# Problem Statement
The electric vehicle (EV) industry is rapidly growing, and understanding EV specifications is essential for analyzing performance, efficiency, and market trends. However, information about EV models is often scattered, making it difficult to compare features such as battery capacity, driving range, charging capability, and pricing.

This project focuses on analyzing an Electric Vehicle Specifications dataset to uncover insights about EV performance trends and feature relationships. The goal of this analysis is to build a foundation for a machine learning model that can predict EV range or cost, and later integrate a GenAI chatbot to help users query EV information easily.


## Dataset
I used the Electric Vehicle Specifications dataset from Kaggle:
https://www.kaggle.com/datasets/urvishahir/electric-vehicle-specifications-dataset-2025

(Note: dataset not uploaded here; open the link to download.)


### What I did (Week 1)
- Imported dataset into Google Colab
- Performed initial cleaning (duplicates & basic NA handling)
- Conducted EDA: histograms, scatter plots, top-brands bar chart, correlation heatmap
- Key observations:
  - Most EVs are sedans/SUVs
  - Higher battery capacity → higher range
  - Fast-charging power varies by model
  - Several technical fields contain missing values
