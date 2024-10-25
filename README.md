# TP : Fuzzy C-means (FCM) pour la Segmentation d'Images

Ce projet implémente l'algorithme Fuzzy C-means (FCM) pour la segmentation d'images, en particulier appliqué à une image de la Voie Lactée. Contrairement aux méthodes traditionnelles comme K-means, FCM permet à chaque pixel d’appartenir simultanément à plusieurs clusters avec des degrés d’appartenance variables. Cette caractéristique rend FCM particulièrement adapté aux images où les frontières entre zones sont floues ou progressives.

## Contenu

- **Paramètres de FCM** : Ajustement de l'exposant de flou \( m \), du nombre de clusters \( C \), du nombre maximal d'itérations et du critère de convergence \( \epsilon \).
- **Segmentation** : Visualisation de la segmentation de l'image pour différents nombres de clusters.
- **Heatmaps de degrés d'appartenance** : Affichage des degrés d'appartenance pour chaque cluster, illustrant la flexibilité et la transition douce de FCM.

## Résultats

En augmentant le nombre de clusters, FCM produit des segmentations de plus en plus détaillées, capturant les variations subtiles de l'image. Les heatmaps révèlent également la capacité de FCM à modéliser des zones intermédiaires sans frontières rigides.
