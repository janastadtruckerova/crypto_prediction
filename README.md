

# **Predikcia cien nehnuteľností**

Tento projekt sa zaoberá predikciou cien nehnuteľností na základe historických údajov pomocou rôznych modelov strojového učenia, ako je lineárna regresia, Random Forest a XGBoost.

## **Prehľad projektu**

Cieľom tohto projektu je vytvoriť a porovnať modely na predikciu cien nehnuteľností (napr. ceny domov v Kalifornii) na základe rôznych faktorov, ako sú lokalita, počet izieb, a ďalšie. Modely sú navrhnuté tak, aby poskytli čo najpresnejšie predpovede na základe historických dát a identifikovali faktory, ktoré najviac ovplyvňujú cenu nehnuteľnosti.

## **Použité technológie**

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost

## **Postup projektu**

1. **Načítanie a predspracovanie dát:**
   Načítanie historických údajov o cenách nehnuteľností a ich úprava pre ďalšie použitie.
   
2. **Tréning modelov:**
   Tréning modelov strojového učenia ako lineárna regresia, Random Forest a XGBoost na datasetoch.
   
3. **Vyhodnotenie modelov:**
   Vyhodnotenie výkonu modelov pomocou metrík ako MSE (Mean Squared Error), RMSE (Root Mean Squared Error) a R² skóre.
   
4. **Vizualizácia:**
   Vizualizácia výsledkov predikcií pomocou rôznych grafov a zobrazení.

## **Inštalácia**

Ak chcete projekt spustiť na svojom počítači:

1. Stiahnite si dataset a Jupyter notebook zo repozitára.
2. Nainštalujte potrebné knižnice:
   `pip install pandas numpy matplotlib scikit-learn xgboost`
3. Otvorte Jupyter notebook a spustite kód.

## **Výsledky**

- **Lineárna regresia:**
  - MSE: 18.54
  - RMSE: 4.31
  - R²: 0.9993
- **Random Forest:**
  - MSE: 49.40
  - RMSE: 7.03
  - R²: 0.9982
- **XGBoost:**
  - MSE: 32.66
  - RMSE: 5.71
  - R²: 0.9988

Model **XGBoost** dosiahol najlepšie výsledky v porovnaní s ostatnými modelmi.

## **Vizualizácie**

V projekte sú vytvorené vizualizácie, ktoré ukazujú predikcie modelov v porovnaní so skutočnými hodnotami a vizualizujú citlivosť modelov na rôzne vstupy.

## **Záver**

- **Výkonnosť modelov:** XGBoost dosiahol najlepšie výsledky, nasledovaný Random Forest a lineárnou regresiou.
- **Vizualizácie:** Predikcie modelov boli porovnané so skutočnými hodnotami a ukázali sa byť veľmi presné.
- **Citlivosť:** Analyzovali sme, ktoré faktory najviac ovplyvňujú predikcie, pomocou grafov Partial Dependence.

Tento projekt ukazuje, ako môžeme využiť rôzne modely strojového učenia na predikciu cien nehnuteľností a ako hodnotiť ich výkonnosť.











.
