
```markdown
# Predikcia cien kryptomien

Tento projekt sa zaoberá predikciou cien kryptomien na základe historických údajov pomocou rôznych strojových modelov, ako je lineárna regresia, Random Forest a XGBoost.

## Popis

Cieľom tohto projektu je vytvoriť modely na predikciu cien kryptomien (ako Bitcoin, Ethereum, atď.) na základe historických dát. V projekte sú použité rôzne prístupy strojového učenia s cieľom dosiahnuť čo najpresnejšie predikcie.

## Použité technológie

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost

## Postup

1. **Načítanie a predspracovanie dát:** Načítanie historických údajov o cenách kryptomien.
2. **Tréning modelov:** Tréning modelov ako Lineárna Regresia, Random Forest a XGBoost.
3. **Hodnotenie výkonu:** Vyhodnotenie modelov pomocou metriky MSE, RMSE a R^2.
4. **Vizualizácia:** Zobrazenie grafov, ktoré ukazujú výkon modelov.

## Inštalácia

Ak chcete projekt spustiť na svojom počítači, vykonajte nasledujúce kroky:

1. Skopírujte tento repozitár:
   ```bash
   git clone https://github.com/uzivatel/crypto-price-prediction.git
   ```

2. Nainštalujte požiadavky:
   ```bash
   pip install -r requirements.txt
   ```

3. Spustite hlavný skript:
   ```bash
   python predikcia.py
   ```

## Výsledky

### Modely:
- **Lineárna regresia**: Model dosiahol hodnoty MSE: 18.54, RMSE: 4.31 a R^2: 0.9993.
- **Random Forest**: Model dosiahol hodnoty MSE: 49.40, RMSE: 7.03 a R^2: 0.9982.
- **XGBoost**: Model dosiahol hodnoty MSE: 32.66, RMSE: 5.71 a R^2: 0.9988.

Model XGBoost dosiahol najlepšie výsledky v porovnaní s ostatnými modelmi.

## Vizualizácie

V projekte sú vytvorené vizualizácie, ktoré znázorňujú predikcie modelov vs skutočné hodnoty a vizualizujú trendy a citlivosť na jednotlivé vstupy.

### Predikcie vs Skutočné hodnoty

#### Lineárna Regresia
```python
plt.scatter(y_test, y_pred_lr, color='blue')
plt.title('Lineárna Regresia - Predikcie vs Skutočné hodnoty')
plt.xlabel('Skutočné hodnoty')
plt.ylabel('Predikcie')
plt.show()
```

#### Random Forest
```python
plt.scatter(y_test, y_pred_rf, color='green')
plt.title('Random Forest - Predikcie vs Skutočné hodnoty')
plt.xlabel('Skutočné hodnoty')
plt.ylabel('Predikcie')
plt.show()
```

#### XGBoost
```python
plt.scatter(y_test, y_pred_xgb, color='red')
plt.title('XGBoost - Predikcie vs Skutočné hodnoty')
plt.xlabel('Skutočné hodnoty')
plt.ylabel('Predikcie')
plt.show()
```

### Citlivosť modelov

#### Random Forest
```python
from sklearn.inspection import plot_partial_dependence
plt.figure(figsize=(12, 6))
plot_partial_dependence(rf_model, X_train, features=[0, 1, 3], feature_names=X.columns, grid_resolution=50)
plt.title('Citlivosť modelu Random Forest')
plt.show()
```

#### XGBoost
```python
from sklearn.inspection import plot_partial_dependence
plt.figure(figsize=(12, 6))
plot_partial_dependence(xgb_model, X_train, features=[0, 1, 3], feature_names=X.columns, grid_resolution=50)
plt.title('Citlivosť modelu XGBoost')
plt.show()
```

## Záver

- **Výkonnosť modelov:** Model XGBoost dosiahol najlepšie výsledky, nasledovaný Random Forest a lineárnou regresiou.
- **Vizualizácie:** Predikcie modelov boli vizualizované v porovnaní so skutočnými hodnotami a ukázali sa byť veľmi presné.
- **Citlivosť:** Analyzovali sme, ktoré vstupy najviac ovplyvňujú predikcie pomocou grafov Partial Dependence.

Tento projekt ukazuje, ako môžeme využiť rôzne modely strojového učenia na predikciu cien kryptomien a ako hodnotiť ich výkonnosť.

```

Skopírujte tento markdown kód a vložte ho do súboru `README.md` na GitHub. Tento dokument je teraz jeden kompletný markdown blok, ktorý sa správne zobrazuje na GitHub a mal by byť správne zobrazený ako celok, bez toho, aby sa jednotlivé sekcie oddelili.
