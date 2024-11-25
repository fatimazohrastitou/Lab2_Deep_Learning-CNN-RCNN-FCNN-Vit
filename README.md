# Lab2_Deep_Learning-CNN-RCNN-FCNN-Vit

Aperçu
Ce laboratoire porte sur l’implémentation et l’analyse de divers modèles d’apprentissage profond pour des tâches de classification d’images. Nous avons exploré :

Réseaux de Neurones Convolutifs (CNN)
Réseaux de Neurones Convolutifs Basés sur les Régions (RCNN)
Réseaux de Neurones Complètement Connectés (FCNN)
Transformateurs de Vision (ViTs)
Les expérimentations ont été réalisées sur le jeu de données MNIST, composé d’images en niveaux de gris représentant des chiffres manuscrits.

Objectifs
Comprendre et implémenter les architectures des modèles CNN, RCNN, FCNN et ViT à partir de zéro avec PyTorch.
Entraîner et évaluer les modèles sur le jeu de données MNIST.
Comparer les performances des approches traditionnelles et des approches basées sur les transformateurs.
Résultats
Performances des modèles sur le jeu de données MNIST
Type de modèle	Précision sur le test (%)	Observations
CNN	98,76	Très bonnes performances grâce aux convolutions.
RCNN	98,15	Légèrement inférieur dû au calcul basé sur les régions.
FCNN	96,85	Bon, mais moins adapté pour les images.
Vision Transformer (ViT)	97,31	Prometteur avec un prétraitement minimal.
Ce que j’ai appris
Architectures des modèles :

La structure et le fonctionnement des CNN, RCNN, FCNN et Vision Transformers.
Les avantages de chaque architecture pour les tâches de vision par ordinateur.
Processus d’entraînement :

Mise en place d’une boucle d’entraînement avec PyTorch.
Optimisation des modèles avec l’optimiseur Adam et suivi des performances avec la fonction de perte CrossEntropy.
Vision Transformers :

Compréhension des mécanismes d’attention et de leur impact sur la classification d’images.
Potentiel des ViTs pour surpasser les modèles traditionnels sur de grands ensembles de données.
Compétences pratiques :

Résolution des problèmes d’entraînement et gestion efficace des grands ensembles de données.
Utilisation de Git et GitHub pour le contrôle de version et la collaboration.
Comment exécuter
Prérequis
Python 3.8+
PyTorch
Torchvision
Jupyter Notebook (facultatif)
Étapes
Cloner le dépôt :

bash

git clone https://github.com/fatimazohrastitou/Lab2_Deep_Learning-CNN-RCNN-FCNN-Vit.git
Accéder au répertoire :

bash

cd Lab2_Deep_Learning-CNN-RCNN-FCNN-Vit
Installer les dépendances :

bash

pip install -r requirements.txt
Exécuter le script d’entraînement pour un modèle spécifique :

bash

python train_model.py --model cnn
Remplacez cnn par rcnn, fcnn ou vit selon le modèle que vous souhaitez exécuter.

Visualisez les résultats et comparez les performances.

Conclusion
Ce laboratoire m’a permis d’acquérir une expérience pratique dans la conception et l’évaluation de modèles d’apprentissage profond pour la classification d’images. Il a également mis en évidence l’importance croissante des Vision Transformers dans les tâches de vision par ordinateur.

