# A Hundred Years of Racial Discourse in Urban Studies

This repository contains Python Jupyter notebooks created to help **replicate results** for the article:

> *"A Hundred Years of Racial Discourse in Urban Studies."*

The notebooks are organized by functionality for easier revisions and replication.

---

## Repository Contents

- **Race_in_Urban_Studies_LDA.ipynb**  
  Latent Dirichlet Allocation (LDA) topic modeling.

- **Race_in_Urban_Studies_W2V.ipynb**  
  Word2Vec semantic analysis.

- **Race_in_Urban_Studies_CosineSim.ipynb**  
  Cosine similarity analysis across decades.

- **Race_in_Urban_Studies_HateSpeech.ipynb**  
  Probability of hate speech analysis.

---

## Data Availability

The data used in this project consist of abstracts from the Urban Studies literature.  
Because these data require subscriptions to literature databases, the repository **does not include direct data files or download links**.  

However, researchers with institutional access to these databases can:
1. Follow the steps described in the article.  
2. Download the appropriate abstracts.  
3. Organize them by **decade** and by **discipline**.  
4. Use the notebooks in this repository to replicate the results.

---

## Notes on Disciplinary Analysis

Codes for disciplinary analysis are not separately provided.  
They are essentially the same as:

- `Race_in_Urban_Studies_W2V.ipynb`  
- `Race_in_Urban_Studies_CosineSim.ipynb`  
- `Race_in_Urban_Studies_HateSpeech.ipynb`  

with file paths modified to discipline-specific and decade-specific data.
