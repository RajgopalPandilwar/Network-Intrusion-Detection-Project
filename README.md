# Network Intrusion Detection

Network Intrusion Detection Project with Code and Documents.

**Author:** Rajgopal Pandilwar  

---

### Youtube Video: https://youtu.be/fUMWwDYPjOk  
### Full Code: [LINK](https://colab.research.google.com/drive/1LCaFLFNf4dOUU1jznIhaVEdBeb_F7K4L?usp=sharing)

---

## About the Project

This project studies the prediction of anomalies and attacks in a network. The task is to build a **Network Intrusion Detection System (NIDS)** to detect anomalies and attacks using Machine Learning algorithms.

### Problem Statement

The task is to build a network intrusion detection system to detect anomalies and attacks in the network. We use Machine Learning algorithms in this project, implemented in Python.

## Features

- Detects network intrusions and anomalies using ML algorithms
- Uses Decision Tree and Random Forest classifiers
- Includes feature selection with VarianceThreshold
- Full notebook with step-by-step analysis

## Research Papers (Base Papers)

1. https://esource.dbs.ie/handle/10788/4251
2. https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3428211
3. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8049129/
4. https://journalofbigdata.springeropen.com/articles/10.1186/s40537-018-0145-4

## Tech Stack

- **Language** - Python
- **Libraries** - scikit-learn, pandas, numpy
- **ML Algorithms** - Decision Tree, Random Forest
- **Dataset** - `networkintrusion.csv` (included in repo)

## How to Run

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Open the Jupyter Notebook: `jupyter notebook Intrusion_Detection_System_D.ipynb`
4. Run all cells to train and evaluate the model

## Dataset

The dataset `networkintrusion.csv` contains network traffic features labeled as either normal or attack types. It includes features like duration, protocol type, service, flag, bytes transferred, and various error rates.

## Credits

- Modified and maintained by **Rajgopal Pandilwar**
