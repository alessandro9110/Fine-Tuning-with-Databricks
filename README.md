# Fine Tuning with Databricks

![Python 3.8+](https://img.shields.io/badge/python-3.8%2B-blue.svg)
![Jupyter Notebooks](https://img.shields.io/badge/notebooks-jupyter-orange.svg)
![License MIT](https://img.shields.io/badge/license-MIT-green.svg)
![Databricks](https://img.shields.io/badge/platform-Databricks-red.svg)

Questo repository raccoglie notebook, script e risorse per il fine-tuning di modelli LLM (Large Language Models) utilizzando la piattaforma Databricks.

## Contenuti

- Notebook Jupyter step-by-step per l’impostazione dell’ambiente, importazione dati, training e test di nuovi modelli.
- Esempi pratici e best practice per la gestione di pipeline ML in Databricks.
- File di requirements per la riproducibilità degli esperimenti.

## Struttura

La cartella principale contiene:
- `00.setup.ipynb`: Configurazione iniziale dell’ambiente Databricks.
- `01.import_data.ipynb`: Importazione e preparazione dei dati.
- `02.fine_tuning_with_trainer.ipynb`: Esempio di fine-tuning con HuggingFace Trainer.
- `03.test_new_model.ipynb`: Test e valutazione del modello fine-tunato.
- `requirements.txt`: Dipendenze Python necessarie.
- `README.md`: Questo file.

## Come usare

1. Clona questo repository su Databricks o localmente.
2. Installa le dipendenze indicate in `requirements.txt`.
3. Segui i notebook in ordine per imparare e riprodurre il workflow di fine-tuning.

## Requisiti

- Account Databricks
- Python 3.8+
- HuggingFace Transformers, PyTorch, e librerie ML comuni

## Note

Questi notebook sono pensati per uso didattico e sperimentale. Adattali alle tue esigenze prima di usarli in produzione.

---

Per domande o suggerimenti, apri una issue!