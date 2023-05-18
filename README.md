# fine_tuning_bert_stackoverflow
Fine-tuning bert for multi-label classification on stackoverflow dataset (question and tags = labels) d'après https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/BERT/Fine_tuning_BERT_(and_friends)_for_multi_label_text_classification.ipynb

Entrainement (fine tuning) et évaluation d'un modèle bert préentrainé pour la classification multi-label.
On utilise un jeu de 10000 questions de stackoverflow parmi des questions n'étant labelisées que par les 100 tags les plus fréquemment utilisées dans un jeu de 50000 questions.
Par conséquent, on travaille avec 100 labels (booléenne) et 1 texte (concaténation du titre et du corps de la question).

Le notebook comprend le preprocessing des données, l'entrainement du modèle et son évaluation.




