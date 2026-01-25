# A Hundred Years of Racial Discourse in U.S. Urban Studies 

This repository contains Python Jupyter notebooks created to help **replicate results** for the article:

> *"A Hundred Years of Racial Discourse in U.S. Urban Studies."*

The notebooks are organized by analytical function to facilitate transparency, replication, and future extensions.

This project is licensed under the MIT License (see **LICENSE**).

---

## Repository Contents

### Core Analysis Notebooks
- **Race_in_Urban_Studies_LDA.ipynb**  
  Latent Dirichlet Allocation (LDA) topic modeling.

- **Race_in_Urban_Studies_W2V.ipynb**  
  Word2Vec semantic analysis.

- **Race_in_Urban_Studies_CosineSim.ipynb**  
  Cosine similarity analysis across decades.

### Data and MetaData Files
- **FullRecords.csv**  
  Complete list of abstract records used in the paper.

- **GSRRecords2Dis.csv**  
Classification of Google Scholar abstract records into three disciplinary categories.

### Demonstration Materials
- **DemoData.txt**  
A small sample of abstracts collected from Google Scholar, provided as a demo dataset.

- **DemoCode.ipynb**  
A fully executable demonstration notebook that uses DemoData.csv to illustrate the functionality, workflow, and outputs of all analysis code in this repository.

---
## Software Environment

This analysis was conducted using:

- Python 3.12.3
- Jupyter Notebook 7.2.2

---

## Data Availability

The full data used in this project consist of abstracts from the Urban Studies literature.  
Because these data require subscriptions to literature databases, the repository **does not include direct data files or download links**.  

However, researchers with institutional access to these databases can:  
Either 
1. Follow the steps described in the article.  
2. Download the appropriate abstracts.  
3. Organize them by **decade** and by **discipline**.  
4. Use the notebooks in this repository to replicate the results.  

Or,    compile the same list of abstracts from other available databases using the full list in **FullRecords.csv**

To support transparency and reproducibility, this repository includes:  
- **FullRecords.csv**, which documents all abstract records used in the study, and
- **DemoData.csv** and **DemoCode.ipynb**, which provide a complete, runnable demonstration of the analytical pipeline.

---

## Notes on Disciplinary Analysis

Codes for disciplinary analysis are not separately provided.  
They are essentially the same as:

- `Race_in_Urban_Studies_W2V.ipynb`  
- `Race_in_Urban_Studies_CosineSim.ipynb`  

with file paths modified to discipline- and decade-specific data.
