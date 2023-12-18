# Modélisation de la Croissance Tumorale

## 0. Modélisation
- Utilisation du modèle de Gompertz pour décrire la croissance tumorale.
- Équation différentielle pour le volume tumoral V(t) en fonction du temps t, la constante de croissance k et la taille maximale M.

## 1. Étude Théorique
### Existence et Unicité
- Existence de la solution basée sur le théorème de Peano.
- Unicité de la solution garantie par les propriétés lipschitziennes de la fonction f.

### Dépendance Continue
- Dépendance continue par rapport à la condition initiale et à la fonction f, assurée par le théorème de Cauchy-Lipschitz.

### Stabilité des Points Fixes
- Analyse de la stabilité des points d'équilibre.
- Étude des points d'équilibre V*1 = 0 et V*2 = M.

### Ensemble Omega-Limite et Cycle Limite
- L'ensemble limite est M.
- Absence de cycle limite due à la non-périodicité de f.

### Bifurcation
- Exploration de la bifurcation en introduisant un paramètre c dans f.

## 2. Analyse Numérique
### Schéma Numérique
- Utilisation de la méthode d'Euler explicite pour la résolution numérique.
- Initialisation et calcul des itérations.

### Convergence du Schéma Numérique
- Stabilité et consistance du schéma, conduisant à la convergence.

### Interprétation et Application
- Description des phases de croissance tumorale.
- Implications pour les interventions thérapeutiques.
- Analyse de la croissance tumorale à long terme.

### Limitations et Améliorations
- Absence de données réelles pour la validation.
- Comparaison avec d'autres méthodes comme Odeint.
