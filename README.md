# MLP Project T3 2025 – Cinema Audience Forecasting

This repository contains my submission notebook for the **MLP Project T3 2025**, a time-series forecasting problem focused on predicting cinema audience attendance using both online and POS booking data.

---

## 📌 Project Overview

The objective of this project is to forecast **daily audience counts** for cinema theatres by combining data from:

- **BookNow** – Online ticket booking platform  
- **CinePOS** – On-site point-of-sale ticket system  

The task involves building a baseline Machine Learning model and generating predictions for the test dataset in the required submission format.

---

## 📂 Dataset Description

The dataset consists of multiple CSV files:

- `cinePOS_theaters.csv` – CinePOS theatre metadata  
- `booknow_theaters.csv` – BookNow theatre metadata  
- `movie_theater_id_relation.csv` – Mapping between platforms  
- `cinePOS_booking.csv` – POS booking transactions  
- `booknow_booking.csv` – Online booking transactions  
- `booknow_visits.csv` – Daily audience visit counts  
- `date_info.csv` – Calendar features (weekend, holiday, etc.)  
- `sample_submission.csv` – Submission format  

**Target:**  
Predict `audience_count` for each `book_theater_id + show_date`.

---

## 🧠 Approach

- Performed basic data loading and inspection
- Created a **baseline ML model (MLP / dummy model)**
- Generated predictions for the test set
- Stored predictions in a DataFrame with:
  - `id`
  - `audience_count`
- Exported predictions to `submission.csv`
- Submitted predictions on Kaggle

---

## 📄 Notebook Details

- **Notebook name:** `23f1001572-notebook-t32025.ipynb`
- **Platform:** Kaggle
- **Access:** Private (shared with `iitmbscs2008p` – view access)

---

## 🚀 How to Run

1. Open the notebook in Kaggle
2. Run all cells from top to bottom
3. The final cell generates `submission.csv`
4. Upload the CSV to the Kaggle competition page

---

## 🏁 Submission Info

- **Team Name:** Kaggle User ID  
- **Submission File:** `submission.csv`

---

## 📌 Notes

- Audience count may be zero on closed days
- Holiday and weekend effects are considered
- Dataset is anonymized
- Baseline model implemented for initial benchmarking

---

## ✍️ Author

**Abhishek Saha**  
MLP Project – T3 2025
