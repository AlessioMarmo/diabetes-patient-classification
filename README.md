# 🩺 Analisi Predittiva e Classificazione del Diabete (BRFSS 2015)

Pipeline completa di Data Science e Machine Learning in Python per l'analisi dei fattori di rischio sanitario e la predizione clinica del diabete[span_1](start_span)[span_1](end_span).

---

## 📋 Panoramica del Progetto
Questo progetto utilizza il dataset **BRFSS 2015** (Behavioral Risk Factor Surveillance System)[span_2](start_span)[span_2](end_span) per studiare la correlazione tra indicatori socio-sanitari/comportamentali e la presenza di diabete, implementando un modello di classificazione supervisionato.

### Fasi principali della pipeline:
1. **Data Loading & Quality Control:** Importazione e verifica strutturale del dataset (70.692 righe e 22 colonne) con controllo dei valori nulli[span_3](start_span)[span_3](end_span).
2. **Analisi Esplorativa (EDA):** Generazione della matrice di correlazione e visualizzazione tramite *heatmap* per identificare le feature con il peso maggiore sulla variabile target (`Diabetes_binary`)[span_4](start_span)[span_4](end_span).
3. **Machine Learning Modeling:** Addestramento e confronto di **due modelli di classificazione** per la predizione dello stato di salute dei pazienti.
4. **Valutazione:** Analisi delle performance predittive dei modelli.

---

## 🛠️ Tech Stack & Librerie
Il progetto è sviluppato in **Python** utilizzando le principali librerie per la Data Science:
* **Data Manipulation & Cleaning:** Pandas, NumPy[span_5](start_span)[span_5](end_span)
* **Data Visualization:** Matplotlib, Seaborn[span_6](start_span)[span_6](end_span)
* **Machine Learning:** Scikit-learn (o librerie equivalenti per i modelli addestrati)

---

## 📂 Struttura del Repository
```text
├── diabetes_binary_5050split_health_indicators_BRFSS2015.csv  # Dataset di riferimento
├── notebook.ipynb                                            # Jupyter Notebook con l'intera pipeline (EDA + Modelli)
└── README.md                                                 # Documentazione del progetto
