# ⚡ Power Plant Energy Prediction using ANN

Predicts the electrical energy output of a Combined Cycle Power Plant using an Artificial Neural Network built in PyTorch, based on environmental operating conditions.

Implementation: `Power_plant_ANN.ipynb`

---

## 📊 Dataset

| Feature | Description |
|---|---|
| AT | Ambient Temperature |
| V  | Exhaust Vacuum |
| AP | Ambient Pressure |
| RH | Relative Humidity |
| PE | **Electrical Energy Output (target)**|

---

## 🧠 Model

A fully connected ANN (2 hidden layers, ReLU activation) trained to regress PE from AT, V, AP, and RH.

---

## 🔧 Tech Stack

Python · NumPy · Pandas · Matplotlib · Seaborn · Scikit-learn · PyTorch

---

## ▶️ How to Run

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd PowerPlant-ANN-Prediction
pip install numpy pandas matplotlib seaborn scikit-learn torch jupyter
jupyter notebook Power_plant_ANN.ipynb
```

Run all cells top to bottom.

---

## 📈 Results

```text
training MSE : 20.319076538085938
test MSE : 18.777429580688477
r2 socre :  0.9343777285123931
```


## 👨‍💻 Author

**Aakash Jadhav** — B.E. Computer Engineering
