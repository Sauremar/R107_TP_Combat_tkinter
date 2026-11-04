# 🧙‍♂️ Mini-Jeu de Combat (Tkinter & Python)

Ce projet est un prototype de mini-jeu de combat en duel au tour par tour, développé en Python. Il combine une interface graphique interactive réalisée avec **Tkinter** / **ttk** et une gestion d'images via **Pillow (PIL)**, avec une base de logique textuelle en console.

---

## 🛠️ Fonctionnalités

- **Classe `Personnage` :** Gestion des statistiques de base (Constitution/Points de vie, Force, Agilité, Intelligence).
- **Actions disponibles :** 
  - Attaque (calculée à partir de la force et de l'agilité).
  - Soin (basé sur l'intelligence).
- **Interface Graphique (GUI) :** Une fenêtre interactive gérée par `Tkinter` affichant un personnage (ex: Gandalf) avec des boutons pour déclencher des actions.
- **Mode Console / Boucle principale (`main`) :** Une boucle interactive textuelle permettant de jouer en alternant les tours entre Aragorn et Gandalf.

---

## 📋 Prérequis

Assure-toi d'avoir Python installé sur ta machine, ainsi que la bibliothèque **Pillow** pour la gestion des images.

Tu peux installer Pillow via pip si ce n'est pas déjà fait :
```bash
pip install Pillow