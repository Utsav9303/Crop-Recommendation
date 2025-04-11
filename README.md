

---

# 🌾 Crop Recommendation System

A Machine Learning-based system that recommends the most suitable crop to grow based on soil and environmental conditions like Nitrogen, Phosphorus, Potassium levels, Temperature, Humidity, pH, and Rainfall.

---

## 📌 Overview

This project aims to help farmers and agricultural experts make data-driven crop decisions. Given environmental parameters, the system uses an ML model to predict the best crop for cultivation.

---

## 🚀 Features

- ✅ Accurate crop prediction using ML  
- ✅ Real-world agricultural dataset  
- ✅ Easy-to-use Jupyter Notebook  
- ✅ Web integration possible via Flask (optional)

---

## 🧠 Tech Stack

| Language | Libraries | Tools |
|----------|-----------|-------|
| Python 🐍 | Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn | Jupyter Notebook, Flask (optional) |

---

## 📁 Folder Structure

```
Crop-Recommendation/
├── Crop Recommendation.ipynb       ← Main Jupyter Notebook
├── crop.csv                        ← Dataset
├── model.pkl                       ← Trained ML model
├── requirements.txt                ← Required Python packages
├── templates/                      ← HTML files
├── static/                         ← CSS/JS
└── README.md                       ← You're here!
```

---

## 📊 Dataset

- **Source:** [Kaggle - Crop Recommendation Dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)  
- **Attributes:**
  - `N`, `P`, `K` – Soil nutrients  
  - `temperature`, `humidity`, `ph`, `rainfall` – Climate data  
  - `label` – Target crop (output)

---

![Screenshot](https://github.com/Utsav9303/Crop-Recommendation/blob/main/codeimages/Screenshot%202025-01-09%20190512.png)
![Screenshot](https://github.com/Utsav9303/Crop-Recommendation/blob/main/codeimages/Screenshot%202025-01-09%20190931.png)
![Screenshot](https://github.com/Utsav9303/Crop-Recommendation/blob/main/codeimages/Screenshot%202025-01-09%20191417.png)
![Screenshot](https://github.com/Utsav9303/Crop-Recommendation/blob/main/codeimages/html.png)
![Screenshot](https://github.com/Utsav9303/Crop-Recommendation/blob/main/codeimages/js.png)
![Screenshot](https://github.com/Utsav9303/Crop-Recommendation/blob/main/codeimages/server.png)
![Screenshot](https://github.com/Utsav9303/Crop-Recommendation/blob/main/codeimages/util.png)

## ⚙️ How to Run

### 🖥️ 1. Clone the Repository

```bash
git clone https://github.com/Utsav9303/Crop-Recommendation.git
cd Crop-Recommendation
```

### 🧪 2. Create & Activate Virtual Environment (Optional)

```bash
python -m venv venv
```

**Activate it:**

- **Windows:**

```bash
venv\Scripts\activate
```

- **macOS/Linux:**

```bash
source venv/bin/activate
```

### 📦 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 📓 4. Run Jupyter Notebook

```bash
jupyter notebook
```

Open `Crop Recommendation.ipynb` and run all the cells to train and test the model.

---

## 🌐 Optional: Run Flask Web App

```bash
python app.py
```

Then go to: [http://localhost:5000](http://localhost:5000)

---

## 🧪 Sample Input & Output

| N  | P  | K  | Temperature | Humidity | pH  | Rainfall |
|----|----|----|-------------|----------|-----|----------|
| 90 | 42 | 43 | 20.5°C      | 82%      | 6.5 | 202mm    |

**🔍 Predicted Crop:** Rice 🌾

---

## 📄 Requirements

Install all dependencies:

```bash
pip install -r requirements.txt
```

**Packages used:**

- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn  
- jupyter

---

## 👨‍💻 Contributing

Contributions are welcome!

1. Fork the repo  
2. Create your feature branch  
```bash
git checkout -b feature/YourFeature
```
3. Commit your changes  
```bash
git commit -m "Add your feature"
```
4. Push to GitHub  
```bash
git push origin feature/YourFeature
```
5. Open a Pull Request 🚀

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

- [Kaggle](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset) for the dataset  
- Scikit-learn for ML tools  
- Open-source community ❤️

---
