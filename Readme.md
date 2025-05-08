# 🧠 Self-Supervised Learning

Ce projet présente une introduction pratique à **l'apprentissage auto-supervisé (Self-Supervised Learning - SSL)**, en s'appuyant sur des techniques modernes comme la prédiction de contexte, les puzzles Jigsaw, la colorisation d'images, l'inpainting et la rotation d'images avec **TensorFlow** et **MNIST**.

## 📌 Objectif

Ce projet a pour but :
- De comprendre les fondements de l’apprentissage auto-supervisé.
- D’expérimenter avec des **tâches de prétexte** (pretext tasks).
- De montrer comment les représentations apprises peuvent être transférées à des tâches supervisées classiques.

## 🧰 Contenu

- `Self_supervised_Learning.ipynb` : Notebook principal contenant les implémentations et explications.
- Approches couvertes :
  - Prédiction de contexte (Context Prediction)
  - Puzzle Jigsaw (Jigsaw Puzzle)
  - Colorisation d’image (Image Colorization)
  - Reconstruction d’images (Image Inpainting)
  - Rotation d’images (RotNet)

## 📂 Datasets

- Utilisation du dataset **MNIST** pour démonstration rapide et efficace.
- Possibilité d’adapter à d'autres datasets non étiquetés (ex : CIFAR-10, STL-10, ImageNet, etc.).

## 🚀 Lancer le projet

### Prérequis

- Python ≥ 3.8
- TensorFlow ≥ 2.8
- NumPy, Matplotlib

### Installation

```bash
git clone https://github.com/khalid18031987/self-supervised-learning.git
cd self-supervised-learning
pip install -r requirements.txt
