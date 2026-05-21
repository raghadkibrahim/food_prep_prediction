# Food Delivery Prep Time Prediction

**Overview**

This project focuses on predicting food preparation time for orders placed through a food delivery marketplace operating in Jordan and Saudi Arabia.

Accurate preparation time estimation is critical for:

- Courier dispatch timing
- ETA prediction
- Customer communication
- Marketplace efficiency
- Reducing delivery delays

The goal of this project is to explore the data, understand the factors affecting preparation time, and build machine learning models capable of estimating how long a store will take to prepare an order.

When a customer places an order, the platform must estimate:

> How many minutes will the store need to prepare the order?

Poor estimates can lead to:

- Late deliveries
- Idle couriers
- Incorrect ETAs
- Poor customer experience

This project investigates historical order data to model and predict preparation time.

<hr>

## Project Structure

foodprep_project/
│
├── dataset/
│   └── prep_time_dataset.csv
│
├── 01_data_cleaning.ipynb
│
├── .gitignore
├── requirements.txt
├── README.md

## Environment Setup

Clone the repository

```
git clone https://github.com/raghadkibrahim/food_prep_prediction.git
cd food_prep_prediction
```

Create and activate conda environment
```
conda create -n foodprep_project python=3.11
conda activate foodprep_project
```