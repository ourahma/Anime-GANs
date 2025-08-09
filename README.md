# Génération de Visages d'Animes avec DCGAN

## 📈 Description du Projet

Ce projet met en œuvre un **Deep Convolutional Generative Adversarial Network (DCGAN)** pour générer de nouveaux visages de style anime à partir de bruit aléatoire. L'objectif est de produire des images réalistes en s'appuyant sur un apprentissage profond non supervisé.

## 📊 Architecture

Le DCGAN comprend deux réseaux principaux :

* **Générateur** : Transforme un vecteur latent aléatoire en une image de visage d'anime.
* **Discriminateur** : Distingue les images réelles du dataset des images générées.

Flux de données :

```
Bruit aléatoire (z) ➔ Générateur ➔ Image d'anime synthétique ➔ Discriminateur ↔ Image d'anime réelle
```

## 📂 Dataset

Dataset utilisé : **Anime Face Dataset**

* Source : [Kaggle - Anime Face Dataset](https://www.kaggle.com/datasets/splcher/animefacedataset)
* Contient des milliers de visages recadrés et normalisés d'animes.

#

## 📊 Résultats Attendus

* Les premières époques produisent des images bruitées.
* Après plusieurs époques, les visages deviennent plus détaillés et réalistes.

*(Insérez ici des exemples d'images générées)*

## 📚 Références

* Radford, A., Metz, L., & Chintala, S. (2015). [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](https://arxiv.org/abs/1511.06434)
* Kaggle - [Anime Face Dataset](https://www.kaggle.com/datasets/splcher/animefacedataset)


## Auteur:
* OURAHMA Maroua
