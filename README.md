
```markdown
# Predikcia cien kryptomien

Tento projekt sa zaoberá predikciou cien kryptomien na základe historických údajov pomocou rôznych modelov strojového učeni, ako je lineárna regresia, Random Forest a XGBoost.

## Popis

Cieľom tohto projektu je vytvoriť  a porovnať modely na predikciu cien kryptomien (ako Bitcoin, Ethereum, atď.) na základe historických dát. V projekte sú použité rôzne modely strojového učenia s cieľom dosiahnuť čo najpresnejšie predikcie.

## Použité technológie

- Python - programovací jazyk  a jeho kinižnice:

- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost

## Postup

1. **Načítanie a predspracovanie dát:** Načítanie historických údajov o cenách kryptomien.
2. **Tréning modelov:** Tréning modelov ako Lineárna Regresia, Random Forest a XGBoost.
3. **Hodnotenie výkonu:** Vyhodnotenie modelov pomocou metriky MSE, RMSE a R^2.
4. **Vizualizácia:** Zobrazenie grafov, ktoré ukazujú výkon modelov a citlivosť modelov

## Inštalácia

Ak chcete projekt spustiť na svojom počítači, vykonajte nasledujúce kroky:
V repozitári nájdete dataset a Jupyter notbook. Tieto súbory si môžete stiahnuť a spustiť na vlastnom počítači.

## Výsledky

### Modely:
- **Lineárna regresia**: Model dosiahol hodnoty MSE: 18.54, RMSE: 4.31 a R^2: 0.9993.
- **Random Forest**: Model dosiahol hodnoty MSE: 49.40, RMSE: 7.03 a R^2: 0.9982.
- **XGBoost**: Model dosiahol hodnoty MSE: 32.66, RMSE: 5.71 a R^2: 0.9988.

Model XGBoost dosiahol najlepšie výsledky v porovnaní s ostatnými modelmi.

## Vizualizácie

V projekte sú vytvorené vizualizácie, ktoré znázorňujú predikcie modelov vs skutočné hodnoty a  citlivosť na jednotlivé vstupy(v JUpyter notbooku)

## Záver

- **Výkonnosť modelov:** Model XGBoost dosiahol najlepšie výsledky, nasledovaný Random Forest a lineárnou regresiou.
- **Vizualizácie:** Predikcie modelov boli vizualizované v porovnaní so skutočnými hodnotami a ukázali sa byť veľmi presné.
- **Citlivosť:** Analyzovali sme, ktoré vstupy najviac ovplyvňujú predikcie pomocou grafov Partial Dependence.

Tento projekt ukazuje, ako môžeme využiť rôzne modely strojového učenia na predikciu cien kryptomien a ako hodnotiť ich výkonnosť.


