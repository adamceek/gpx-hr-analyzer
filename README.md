# 📊 Heart Rate Accuracy Comparison Script

A Python tool to **compare the heart rate measurement accuracy** between two devices  
(e.g., Garmin HRM and Huawei Watch Fit 2) using `.gpx` files.

---

## 🚀 Features

- Upload and compare two `.gpx` files containing HR (heart rate) data  
- Automatically detect optimal time offset  
- Visualize the results  
- Export results to `.tsv` and save graphs  
- Detect HR recording dropouts

---

## 📂 File Structure

- `porovnanie.ipynb` – Main Colab notebook  
- `porovnanie.py` – Alternative script for local execution (optional)

---

## 📦 Dependencies

Runs in **Google Colab** using standard Python libraries:

- `matplotlib`  
- `numpy`  
- `xml`  
- `datetime`  

---

## 📁 Usage

1. Open `porovnanie.ipynb` in [Google Colab](https://colab.research.google.com)
2. Upload **2 GPX files** (e.g., one from Garmin, one from Huawei)
3. The script will automatically:
   - Detect the **activity date** and **type**
   - Compare HR data using the best time shift
   - Save the **graph** and export results to `.tsv` in Google Drive

---

## 🧠 Note

This project was created as a personal tool for **training data analysis**.  
Feel free to **customize it** for your own use.

---

