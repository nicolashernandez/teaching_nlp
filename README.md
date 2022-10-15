# teaching_nlp

Chapitre 1 [(Pré-)-Traitement Automatique des Langues](https://github.com/nicolashernandez/teaching_nlp/blob/main/01_Analyse_linguistique.ipynb)
* NLP (python) Libraries
* Analyses linguistiques du français
  * Tokénisation
  * Analyse lexicale (lemmatisation, morphologie flexionnelle et dérivationnelle mais pas compositionnelle..., CoNLL) 
  * Analyse syntaxique (constituants et dépendance)
  * Reconnaissance d'entités nommées
* Analyse de textes de genres différents
* Multilinguisme (couverture, qualité et temps de traitemen)
* Benchmark NLP libs

Chapitre 2 [Normalisation des textes](https://github.com/nicolashernandez/teaching_nlp/blob/main/02_Normalisation_des_textes.ipynb)
* Mots vides
* Opérations de normalisation
* Taille du texte vs. taille de vocabulaire
* Mots pleins (statistique et sens, loi de Zipf)

Chapitre 3 [Représentation des textes "traditionnelles" à l'aide du vocabulaire ou des thèmes](https://github.com/nicolashernandez/teaching_nlp/blob/main/03_Repr%C3%A9sentation_des_textes_%C3%A0_l'aide_du_vocabulaire_ou_des_th%C3%A8mes_.ipynb)
* Modèle "sac de mots" (bag of words)
* Vectorisation avec occurrences
* Vectorisation avec TF-IDF
* Matrice creuse
* Partitionnement sur la base d'une représentation bow des documents avec la méthode des k-moyennes
* Similarité entre documents
* Partitionnement hiérarchique des documents sur la base de la matrice de similarités inter-documents
* Partitionnement des documents sur la base de la matrice de similarités inter-documents avec la méthode des k-moyennes
* Topic modeling with LDA's gensim
* Partitionnement des documents sur la base de la matrice document-topic avec la méthode des k-moyennes

Chapitre 4 [Représentation vectorielle continue des mots et des documents](https://github.com/nicolashernandez/teaching_nlp/blob/main/04_repr%C3%A9sentation_vectorielle_continue.ipynb)
* Plongement de mots (word embeddings avec word2vec approches skipgram et cbow, fasttext)
* Charger un modèle existant à l'aide de gensim et réaliser des opérations de similarités
* Visualiser les plongements lexicaux dans un graph en 2D
* Visualiser les plongements lexicaux en 3D dynamique à l'aide du projector de tensorflow
* Construire un modèle word2vec et fasttext avec gensim
* Comparer et évaluer deux modèles
* Construire une représentation continue de document
* Partitionnement sur la base d'une représentation document-embeddings
* L'approche TextRank pour le résumé automatique (Nicolas Dugué)

Chapitre 5 [Classification de textes : tâches d'analyse de sentiment](https://github.com/nicolashernandez/teaching_nlp/blob/main/05_Classification_de_textes.ipynb)
* Allociné dataset 
* Utilisation d'une bibliothèque de haut niveau, ktrain
* Entraînement (fine-tuning) de différents modèles fasttext, nbsvm, BERT et d'autres issus d'HuggingFace
* Recherche de taux d'apprentissage (learning rate) 
* Comparaison de performance d'inférence
* Data augmentation par adversarial learning et model ensembling

## References
* https://nlp-ensae.github.io/
* https://github.com/fastai/course-nlp/
* https://github.com/dipanjanS/practical-machine-learning-with-python
* https://github.com/dipanjanS/nlp_essentials
* https://github.com/dipanjanS/text-analytics-with-python
* https://towardsdatascience.com/understanding-feature-engineering-part-3-traditional-methods-for-text-data-f6f7d70acd41
* https://github.com/clement-plancq/outils-corpus
* French word embeddings models https://fauconnier.github.io/#data
