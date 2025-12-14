# 📊 Traitement Numérique du Signal - TD2 : Échantillonnage

Ce dépôt contient les implémentations Python des exercices du **TD2** portant sur les concepts fondamentaux du traitement de signal numérique.

## 📝 Objectifs du TD
L'objectif est d'étudier l'impact de l'échantillonnage sur le spectre d'un signal analogique, notamment :
* La visualisation du **spectre unilatéral et bilatéral**.
* L'observation du phénomène de **repliement spectral (Aliasing)**.
* La reconstruction de signaux via des **filtres passe-bas idéaux**.
* L'application du **théorème de Shannon-Nyquist**.

## 🚀 Contenu du Notebook
Le fichier `TD2_DSP.ipynb` est divisé en 4 exercices progressifs :
1.  **Exercice 1** : Signal sinusoïdal simple à 1000 Hz échantillonné à 8 kHz.
2.  **Exercice 2** : Somme de deux cosinus et filtrage de reconstruction.
3.  **Exercice 3** : Démonstration de l'aliasing avec une fréquence supérieure à Fs/2.
4.  **Exercice 4** : Analyse complète incluant une composante continue (DC) et étude du spectre bilatéral.

## 🛠 Technologies utilisées
* **Python 3**
* **NumPy** : Pour la manipulation des vecteurs et calculs de fréquences.
* **Matplotlib** : Pour la génération des diagrammes en bâtons (Stem plots) des spectres.

## 📊 Visualisation
Le code génère des graphiques clairs montrant les raies spectrales avant et après échantillonnage :
- Les répliques spectrales à $k \cdot F_s \pm f_0$.
- La zone de Nyquist entre $[-F_s/2, F_s/2]$.

---
**ENSA Tétouan** - *Filière Génie Informatique / Systèmes Embarqués*
