# 📊 Predict the Success of Bank Telemarketing  
### MLP Project T32024

## 📌 Overview
This project aims to predict whether a client will subscribe to a bank term deposit based on data from direct marketing campaigns. The dataset is derived from phone-based marketing efforts, where multiple contacts may have been made to the same client.

The objective is to build a machine learning model that classifies whether a client will respond positively (`yes`) or negatively (`no`).

---

## 📁 Dataset Description

The dataset contains information about clients and past marketing interactions.

### Files:
- `train.csv` – Training dataset  
- `test.csv` – Test dataset  
- `sample_submission.csv` – Sample submission format  

---

## 📊 Features

### Input Variables:
| Feature | Description |
|--------|-------------|
| last_contact_date | Last contact date |
| age | Age of the client |
| job | Type of job |
| marital | Marital status (married, divorced, single) |
| education | Education level |
| default | Credit in default |
| balance | Average yearly balance (euros) |
| housing | Housing loan status |
| loan | Personal loan status |
| contact | Communication type |
| duration | Last contact duration (seconds) |
| campaign | Number of contacts in this campaign |
| pdays | Days since last contact (-1 = never contacted) |
| previous | Number of previous contacts |
| poutcome | Outcome of previous campaign |

### 🎯 Target Variable:
- `target` → Whether the client subscribed to a term deposit (`yes` / `no`)

---

## ⚙️ Tech Stack
- Python 3.x  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

---

## 🚀 Installation

```bash
git clone https://github.com/your-username/bank-telemarketing-prediction.git
cd bank-telemarketing-prediction
pip install -r requirements.txt
