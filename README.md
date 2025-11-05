# CVML-project Introduction
Dans le cadre du projet CVML, nous allons concevoir, entraîner et évaluer un modèle d’apprentissage pour une tâche de classification multi-classe. Contrairement aux tâches précédemment abordées en cours TIP, où chaque image était associée à une seule classe, ce projet introduit une nouvelle difficulté en exigeant la prédiction de plusieurs classes simultanément pour chaque image. Ce type de mission reflète davantage les défis du monde réel, où les données ne sont pas limitées à une seule catégorie.

La base de données MS COCO, bien connue pour sa diversité d’images, a été adaptée pour ce projet afin de réduire sa taille et faciliter le traitement. Les données se divisent en deux sous-ensembles : un ensemble d’entraînement (65 000 images) accompagné de leurs étiquettes, et un ensemble de test (environ 5 000 images).

Ce rapport renseigne notre méthodologie de travail, les décisions techniques prises aux différentes étapes du projet, et les performances obtenues par notre modèle sur cette tâche exigeante. Par ailleurs, nous analyserons également les résultats en termes de métriques d’évaluation standards telles que la précision, le rappel et la F1-score. Enfin, des perspectives pour améliorer les performances seront présentées.

Pour réaliser ce projet, nous disposons de trois GPU : 
NVIDIA GeForce RTX 4050 Laptop GPU
NVIDIA GeForce RTX 4070 Laptop GPU
NVIDIA GeForce RTX 3050 Laptop GPU

En ce qui concerne le langage de programmation utilisé, après de nombreuses réflexions, nous avons décidé d’utiliser MATLAB en raison de sa simplicité et de sa facilité d’utilisation. Contrairement à PyTorch (Python), qui nécessite un temps d’apprentissage plus important, MATLAB s’est révélé être une solution plus adaptée à nos besoins. De plus, nous avons estimé que PyTorch pourrait être plus exigeant en termes de compilation et de performances sur nos équipements.
