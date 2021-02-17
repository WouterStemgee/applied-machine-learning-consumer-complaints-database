# Applied Machine Learning: Project
## [Sprint 1: Supervised Learning](./notebooks/sprint1_supervised-learning/sprint1.ipynb)
### Research Question
- "Kunnen we de categorie van een klacht gaan voorspellen?"

### Technical implementations
- TF-IDF
- Cross-Validation
    - Random Forest
    - Linear Support Vector Machine
    - Multinomial Naive Bayes
    - Logistic Regression
    - K-nearest neighbors
- Confusion Matrix

## [Sprint 2: Unsupervised Learning](./notebooks/sprint2_unsupervised-learning/sprint2.ipynb)
### Retrospect (sprint 1)
- Pre-processing optimaliseren: meervouden, stamvorm en vervoegingen wegfilteren

### Research Question
- "Kunnen we de verschillende categorieën van de dataset beter gaan onderverdelen?"

### Technical implementations
- K-means, DBScan, Topic Modeling (LDA)

## [Sprint 3: Sentiment Analysis](./notebooks/sprint3_sentiment_analysis/sprint3.ipynb)
### Retrospect (sprint 2)
- Modellen van sprint 2 nog evalueren en resultaten aantonen aan de hand van experimenten 
    - klachten in een gevonden cluster gaan onderzoeken
    - [LDA](https://www.kaggle.com/dhorvay/consumer-complaint-classifier-lda-topic-modeling/comments#Latent-Dirichlet-Allocation-(LDA))
- cluster center weergeven (afhankelijk van algoritme)
- duplicate/verwante klachten zoeken (als experiment uitwerken om te kijken of feature extraction goed werkt)
- t-SNE plots gebruiken en interpreteren (visualiseren van hoog dimensionale data)
    - [tsne](https://distill.pub/2016/misread-tsne/)
- niet trainen op 2D/3D data bekomen door PCA (te veel dataverlies!)

### Research Questions
#### Data Analysis
- "Wat is het effect van het aantal financiële assets van de verschillende banken op het aantal gerapporteerde klachten bij deze banken?"

#### Machine Learning
- "Kunnen we de kans dat een klacht opgelost geraakt gaan voorspellen?"
- "Kunnen we de geografische locatie van een klacht gaan voorspellen?"
- "Kunnen we de reactie van een bedrijf op een klacht gaan voorspellen?"

#### Extra
- "Kunnen we het sentiment van een klacht bepalen?"
    - [sentiment analysis](https://www.datacamp.com/community/tutorials/simplifying-sentiment-analysis-python)

    
### Technical implementations
- Meerdere invoerparameters gebruiken voor het model (verschillen bepalen indien bepaalde parameters weggelaten worden)
- Cascading classifiers
- Sentiment analysis & classification 
