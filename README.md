
Ovaj repozitorijum sadrži istraživanje, podatke i Jupyter sveske 
(`.ipynb`) iz mog diplomskog rada na temu prognoziranja volatilnosti 
finansijskih vremenskih serija primenom ekonometrijskih modela 
(GARCH(1,1)) i modela mašinskog učenja (Multi-Layer Perceptron - MLP).

---

## 📊 Obuhvaćeni finansijski instrumenti

Istraživanje i modeliranje su sprovedeni nad tri različite klase imovine:
1. **Akcije (mesečna volatilnost):** Microsoft (MSFT)
2. **Devizni kurs / Forex (nedeljna volatilnost):** EUR/USD
3. **Kriptovalute (dnevna volatilnost):** Bitcoin (BTC)

---

## 📁 Struktura repozitorijuma

* `data/` – Skupovi podataka u CSV formatu za sve tri klase imovine.
* `notebooks/` – 6 Jupyter sveski sa pojedinačnim GARCH i MLP modelima i 
evaluacijom rezultata.

---

## 🛠️ Tehnologije i biblioteke

* **Jezik:** Python
* **Okruženje:** Anaconda / Jupyter Notebook
* **Biblioteke:** `pandas`, `numpy`, `scikit-learn` (`MLPRegressor`), 
`arch` (GARCH), `matplotlib`
