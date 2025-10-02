<div align="center">

# 🎓 TPE: Analyse convexe avec SymPy

## INF4127 - Optimisation II

</div>

---

## 📄 Description

Ce dépôt contient le **TP INF4127 — Optimisation II** (Fiche de TPE n°1) : étude symbolique et numérique des fonctions de perte (MSE, BCE, CCE / softmax, Huber), leurs gradients et Hessiennes, vérification des propriétés de convexité, visualisations (2D/3D/heatmaps) et applications sur petits jeux de données (régression et classification).

Le travail utilise **Python**, **SymPy** pour le calcul symbolique, **NumPy / SciPy / scikit-learn / Matplotlib** pour la partie numérique et graphique.

---

## 📌 Objectifs du TP

- Calculer les gradients et Hessiennes des fonctions de perte demandées.  
- Étudier rigoureusement la convexité (analyse via Hessienne).  
- Appliquer les fonctions sur des jeux de données (n<100, 2 attributs).  
- Visualiser les surfaces de perte, lignes de niveau et tangentes à une ellipse (application géométrique).  
- Fournir des vérifications numériques.

---

## 👥 Équipe du projet

| Nom & Prénom | Matricule | Rôle |
|---|:---:|:---:|
| ESSUTHI MBANGUE ANGE ARMEL | 24F2456 | Membre |
| TAGNE TALLA IDRISS CHANEL | 19M2351 | Membre |
| DJATCHE NKAMGANG SYLVANO | 22W2163 | Membre |
| GOUJOU GUIMATSA ZIDANE | 21T2899 | Membre |

---

## 📁 Contenu principal

- `TP_INF4127_OptimisationII.ipynb` — Notebook Jupyter enrichi : démonstrations symboliques, vérifications numériques, visualisations et exercices guidés.  
- `README_TP_INF4127.md` — Ce fichier (présentation, instructions et auteurs).  


---

## 🛠️ Prérequis

Assurez-vous d'avoir Python 3.8+ et installez les dépendances :

```bash
pip install numpy scipy sympy matplotlib scikit-learn seaborn jupyterlab
```

---

## ▶️ Lancer le notebook

1. Ouvrir un terminal dans le dossier du projet.  
2. Démarrer JupyterLab / Jupyter Notebook :

```bash
jupyter lab
# ou
jupyter notebook
```

3. Ouvrir `TP_INF4127_OptimisationII.ipynb`.  
4. Exécuter les cellules (de haut en bas). Le notebook est prêt à l'emploi et inclut des exemples numériques et graphiques.

> Remarque : pour la partie symbolique (SymPy), le notebook utilise `sp.init_printing()` pour un affichage lisible. Si vous exécutez sur un serveur distant, activez l'affichage graphique (X11) ou téléchargez les figures générées.

---

## 🔬 Jeux de données utilisés

- **Régression** : jeu synthétique linéaire (n ≈ 80–100, 2 features) généré dans le notebook.  
- **Classification** : jeu synthétique (ou jeu Iris réduit à 2 classes/2 features).  

Ces jeux de données sont petits pour faciliter l'exécution sur une machine personnelle et pour les besoins pédagogiques du TP.

---

## 🧾 Résultats et livrables

- Notebook prêt à exécution : `TP_INF4127_OptimisationII_Ameliore.ipynb`.  
- Graphiques : courbes 1D, surfaces 3D, heatmaps et visualisation de tangente à l'ellipse.  
- Synthèse et tableau comparatif des pertes en fin de notebook.

---



## 📚 Références

- Boyd, S., & Vandenberghe, L. (2004). *Convex Optimization*.  
- Goodfellow, I., Bengio, Y., & Courville, A. (2016). *Deep Learning*.  
- Documentation SymPy et scikit-learn.

---

## 📝 Licence

Le contenu de ce TP est fourni pour un usage pédagogique. Vous pouvez le réutiliser en citant les auteurs.

---


