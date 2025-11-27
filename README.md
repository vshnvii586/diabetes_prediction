# Diabetes Prediction System (ML + GUI)

A friendly, approachable, end-to-end machine learning project that predicts the likelihood of diabetes using a Logistic Regression model — wrapped inside a clean, simple Tkinter GUI.

This project was created with learning, clarity, and real-world ML deployment in mind.

# ✨ Highlights

* 🤖 **Machine Learning Model** trained on the PIMA Diabetes Dataset
* 🧮 **75% accuracy** after preprocessing and feature scaling
* 🖥️ **Fully interactive Tkinter GUI** (no command line required!)
* 📦 **Packaged model + scaler** using `pickle` for smooth reuse
* 🧹 Clean, readable, beginner-friendly Python code
* 🚀 Easy to run on any system with Python installed
* 🔰 Ideal project for beginners exploring ML application deployment

# ℹ️ Overview

This project predicts whether a person is likely to have diabetes based on basic medical parameters such as glucose level, BMI, and age.

It demonstrates the **full ML workflow**:

* preprocessing
* scaling
* training
* evaluation
* model saving
* deployment through a GUI

This system was built as an academic project and also as a hands-on exploration of how machine learning transitions from a Jupyter notebook into a usable application.

### Who made this?

Created by **Vaishnavi Mishra**
B.Tech Integrated M.Tech CSE (Computational & Data Science)
VIT Bhopal University

# 🔧 How It Works

The pipeline is simple and effective:

1. Load dataset (PIMA Diabetes)
2. Clean + preprocess + scale features
3. Train Logistic Regression model
4. Save model (`model.pkl`) and scaler (`scaler.pkl`)
5. Build a GUI using Tkinter that:

   * Accepts user inputs
   * Validates values
   * Scales inputs
   * Produces the prediction instantly

# 🚀 Usage

You just need Python. Then:

### **1. Install requirements**

```
pip install -r requirements.txt
```

If unavailable, install manually:

```
pip install numpy pandas scikit-learn
```

Tkinter comes built into Python.

### **2. Run the GUI**

```
python diabetes_gui.py
```

A clean prediction window will appear.

### **3. Input details**

Enter the seven medical parameters → click **Predict** → get instant result:

* 🟢 *"Not Diabetic"*
* 🔴 *"Likely Diabetic"*

---

# 📸 Screenshots
<img width="521" height="547" alt="ss 1" src="https://github.com/user-attachments/assets/db507572-2397-4112-affd-2e7c2491a38b" />
<img width="512" height="552" alt="ss 2" src="https://github.com/user-attachments/assets/53658b27-ec83-4837-8f17-554ed9f1f2eb" />
<img width="511" height="553" alt="ss 3" src="https://github.com/user-attachments/assets/1054e5cd-b69b-4da0-b944-8b8fdb6a6163" />

---

# 📦 Installation Requirements

* Python 3.8+
* scikit-learn
* pandas
* numpy
* tkinter (preinstalled)

Works on:

* Windows
* macOS
* Linux

---

# 🧠 Model Details

* Algorithm: Logistic Regression
* Scaling: StandardScaler
* Dataset: PIMA Diabetes Dataset
* Accuracy: **~75%**
* Balanced, easy-to-understand model ideal for educational use

---

# 🛠️ Project Structure

```
diabetes_prediction/
│
├── diabetes_gui.py         # Final GUI application
├── model.pkl               # Trained ML model
├── scaler.pkl              # Feature scaler
├── README.md               # Project documentation
└── requirements.txt        # Dependencies
```

# 🌱 Future Enhancements

* Add Random Forest / XGBoost for higher accuracy
* Convert GUI to a web app (Flask / FastAPI)
* Add visualization graphs
* Add patient history storage using SQLite
* Create an executable `.exe` for Windows

# 🧩 Why This Project Matters

This project shows how someone with:

* no prior ML training,
* no prior GUI experience,
* no formal software engineering background

can still build a **complete, working, ML application** from scratch.

It demonstrates the accessibility of machine learning and serves as an encouraging example for other students looking to build real-world projects.

# 🧑‍💻 Author

**Vaishnavi Mishra**
CSE (Computational & Data Science)
VIT Bhopal University

Because great software grows through curiosity, collaboration, and kindness. 💫


