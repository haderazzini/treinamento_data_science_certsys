# Questões

1. Carregue o data set [**WINE**](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_wine.html).
2. Divida o dataset em [treino e teste](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html), com 75% das amostras para treino e 25% para teste.
3. Aplique o classificador SVM (kernel="linear", C=0.001) e RANDOM FOREST(max_depth=5, n_estimators=3, max_features=1).
4. Use o Método **score** para comparar os resultados. Ambos os métodos calculam a mesma métrica para esses classificadores, *Mean accuracy*: [score SVM](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html#sklearn.svm.SVC.score) e [score RANDOM FOREST](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html#sklearn.ensemble.RandomForestClassifier.score).
5. Varie os hiperparâmetros dos classificadores para encontrar um score mais próximo de 1
