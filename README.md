

---

## 🪙 Predikcia cien kryptomien pomocou modelov strojového učenia

Tento projekt sa zameriava na predikciu cien kryptomien (napr. Bitcoin, Ethereum) na základe historických údajov. Cieľom je porovnať rôzne modely strojového učenia a vyhodnotiť ich presnosť.

---

### 🎯 Cieľ projektu

Cieľom projektu je:

- vytvoriť modely pre predikciu cien kryptomien na základe historických dát,
- porovnať ich výkonnosť pomocou metrík MAE, MSE, RMSE a R²,
- analyzovať, ktoré faktory najviac ovplyvňujú predikciu,
- vizualizovať výstupy modelov a citlivosť na vstupy.

---

### 🛠️ Použité technológie a knižnice

- **Python**
- **Pandas**, **NumPy** – spracovanie dát  
- **Matplotlib**, **Seaborn** – vizualizácia  
- **Scikit-learn** – lineárna regresia, metriky  
- **XGBoost**, **RandomForestRegressor**

---

### 📁 Štruktúra projektu

- `coin_Aave.csv` – dataset s historickými dátami
- `predikcia_kryptomien.ipynb` – Jupyter/Colab notebook s kompletnou analýzou a vizualizáciami
- `README.md` – tento popis projektu

---

### 📊 Vyhodnotenie modelov

| Model               | MAE    | MSE     | RMSE   | R²     |
|---------------------|--------|---------|--------|--------|
| Lineárna regresia   | 3.7095 | 24.7251 | 4.9724 | 0.9990 |
| Random Forest       | 3.2829 | 22.1162 | 4.7028 | 0.9991 |
| XGBoost             | 3.8207 | 26.2968 | 5.1280 | 0.9989 |

📌 **Najpresnejší model**: *Random Forest* (najnižšie MSE a najvyššie R²)

---

### 📈 Vizualizácie

- Predikované vs. skutočné hodnoty pre každý model
- Citlivosť modelov na vstupy (feature importance)
- Grafy reziduí a vývoj ceny kryptomien

---

### 🧠 Záver

- Všetky modely dosiahli veľmi presné výsledky, Random Forest mierne prekonal ostatné.
- Modely boli vhodne zvolené pre predikciu nelineárnych trendov.
- Vizualizácie pomohli pochopiť výstupy a správanie modelov.






















.
