# WordEmbedding

## Les objectifs du PAO sont doubles : 

1. Comparer les  méthodes de Word Embedding (« plongement de mots » ou « plongement lexical » en français d'après wikipédia)  existantes (notamment Word2Vec, Glove, FastText et ELMo) sur des jeux de données en chinois. Il faudra commencer par trouver des données texteulles en chinois utilisables. Il faudra ensuite proposer de bons critère de comparaison des algorithmes, et faire foncter les algorithme sur les onnées. Il faudra aussi identifier les modèles existants. 
2. Adapter Transformer (https://ai.googleblog.com/2017/08/transformer-novel-neural-network.html), un des modèles utilisé pour la tradution automatique. L'idée est d'essayer d'utiliser un mécanisme d'auto attention (Self-Attention) à la place des clasiques réseaux de type « long short term memory (LSTM) »  pour entraîner un modèle de language bi-directionnel. Il faudra ensuite comparer l'approche proposée avec l'ELMo original sur 6 differentes tâches utilisée pour l'évaler (https://allennlp.org/elmo). Cette idée sera d'abord testée en anglais puis en chinois, si les résultats le permettent.
