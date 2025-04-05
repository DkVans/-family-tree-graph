# -family-tree-graph

## Description
# Projet d'Arbre Généalogique

## Description
Ce projet a pour objectif de créer un arbre généalogique interactif en utilisant des graphes. L'application permettra aux utilisateurs de visualiser les relations familiales et de réaliser des recherches sur les membres de la famille. Le projet est conçu avec React pour offrir une interface utilisateur réactive et intuitive.

## Fonctionnalités
- **Visualisation de l'Arbre Généalogique** : Affichage graphique des membres de la famille et de leurs relations.
- **Recherches de Membres** : Recherche par nom ou par relation (ex. : parents, enfants).
- **Ajout et Édition de Membres** : Permettre aux utilisateurs d'ajouter ou de modifier les informations des membres.

## Cas d'Utilisation
1. **Visualisation de l'Arbre Généalogique** :
   - Afficher l'arbre avec les membres de la famille.
   - Utiliser des nœuds pour représenter chaque membre et des lignes pour montrer les relations.

2. **Recherche de Membres** :
   - Permettre aux utilisateurs de rechercher un membre de la famille par nom.
   - Afficher des informations détaillées sur le membre sélectionné.

3. **Ajout et Édition de Membres** :
   - Formulaires pour ajouter de nouveaux membres ou modifier les informations existantes.
   - Validation des données saisies pour garantir l'intégrité des informations.

## Structure du Projet
family-tree-app/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   ├── FamilyTree.jsx           # Composant principal de visualisation
│   │   ├── PersonNode.jsx           # Composant pour chaque individu
│   │   ├── RelationshipEdge.jsx     # Composant pour les relations
│   │   ├── SearchPanel.jsx          # Interface de recherche
│   │   ├── PathFinder.jsx           # Composant pour trouver les chemins
│   │   ├── DescendantsView.jsx      # Vue des descendants
│   │   └── AncestorsView.jsx        # Vue des ancêtres
│   ├── utils/
│   │   ├── graphUtils.js            # Fonctions de manipulation de graphes
│   │   ├── pathAlgorithms.js        # Algorithmes de recherche de chemins
│   │   └── dataUtils.js             # Fonctions de traitement des données
│   ├── data/
│   │   └── sampleFamilyData.js      # Données d'exemple
│   ├── App.jsx
│   ├── index.jsx
│   └── styles.css
├── package.json
└── README.md

## Installation
Instructions pour installer le projet.
Pour installer le projet, clonez le dépôt et installez les dépendances :

```bash```
git clone https://github.com/DkVans/-family-tree-graph.git
cd -family-tree-graph
npm install

## Utilisation
Démarrez le serveur de développement :

```bash```
npm start
