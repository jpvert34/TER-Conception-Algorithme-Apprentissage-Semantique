# Projet JeuxDeMots

Ce projet s'inscrit dans le cadre du réseau lexical collaboratif **JeuxDeMots**, développé au LIRMM à Montpellier.
L'objectif principal était de concevoir un algorithme distribué sur la plateforme **Grid5000** afin d'apprendre les
liens sémantiques à partir de larges volumes de données.

## Défis

Nous avons relevé plusieurs défis techniques :

- Gestion d'une table de données massive (> 12 Go, des centaines de millions d'enregistrements).
- Répartition égale des informations pour optimiser la charge de travail.
- Utilisation de frameworks tels que **Hadoop** pour assurer un calcul parallèle performant.

## Algorithmes Développés

Deux algorithmes essentiels ont été créés dans le cadre de ce projet :

1. **Algorithme d'apprentissage** :
    - Garantit une distribution équitable des données.
    - Met en œuvre une exécution efficace sur la grille de calcul.

2. **Algorithme d'exploitation** :
    - Combine et regroupe les résultats pour une exploitation optimale.

## Résultats

Ce projet a permis d'élaborer et de perfectionner le réseau lexical **JeuxDeMots**, renforçant ainsi ses fonctionnalités
sémantiques.

## Visualisation

### Algorithme d'apprentissage

![Algorithme d'apprentissage](./images/Algorithme%20d'apprentissage.jpg)

### Algorithme d'exploitation

![Algorithme d'exploitation](./images/Algorithme%20de%20Prédictions.jpg)

---

Pour plus de détails, consultez la documentation ou contactez l'équipe de développement.
