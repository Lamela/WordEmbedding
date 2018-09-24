# WordEmbedding

## Le but du PAO

1. Comparer 4 méthodes de Word Embedding sur les jeux de données en chinois : Word2Vec, Glove, FastText, ELMo. L'objectif principal de cet étape est de comparer les 4 méthodes sur les jeux de données de différentes tailles et de trouver les meilleurs algorithmes correspondent aux jeux de données de différentes tailles. Peut-être sur un jeu de données de taille relativement petite(à définir), le meilleur algorithme est différent que celui de l'état de l'art.

2. Transformer est un des meilleurs modèle dans l'application de Machine translation. Nous proposons d'essayer d'utiliser Self-Attention au lieu de LSTM pour entraîner le Modèle de Langue Bi-directionnel de ELMo. Comparer le avec l'ELMo original sur des tâches mentionnées dans l'ELMo. Nous pouvons d'abord tester cet idée en anglais, si nous obtenons un résultat performant, nous pouvons l'appliquer en corpus chinois.
