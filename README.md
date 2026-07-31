# LF TKD

Ressources numériques pour l’apprentissage et la préparation aux passages de grade de taekwondo.  
Le site regroupe des fiches de poomsés, des outils de tirage aléatoire et des cartes de révision pour les modules de **kibon** des 1er, 2e et 3e Dan.

> Les contenus sont présentés comme des outils pédagogiques ; ils ne remplacent pas les documents, consignes ni validations de la FFTDA.

## Fonctionnalités

- **Fiches de poomsés** : Taegeuk 1 à 8 et Dan 1–2, avec éléments de symbolique et repères techniques.
- **Tirages de kibon** : sélection aléatoire de deux cartes dans chaque catégorie pour les 1er, 2e et 3e Dan.
- **Cartes de révision** : consultation par catégorie, avec navigation au clavier et au balayage tactile.
- **Lexiques** : liens vers des documents de référence de la FFTDA (termes courants, positions, techniques de bras et de pieds).
- Interface responsive, pensée aussi pour les écrans mobiles.

## Démarrage

Le projet est un site statique : aucun paquet, compilation ni serveur applicatif n’est requis.

1. Clonez le dépôt :

   ```bash
   git clone https://github.com/lionel-fd/LF_TKD.git
   cd LF_TKD
   ```

2. Ouvrez `index.html` dans votre navigateur.

Pour un test plus proche des conditions de publication (et pour éviter les restrictions éventuelles de certains navigateurs), copiez le lien de l'objet à tester après le lien preview GitHub suivant:
```bash
https://htmlpreview.github.io/?
```
exemple : https://htmlpreview.github.io/?https://github.com/lionel-fd/LF_TKD/blob/Test/index.html
## Utilisation

Depuis la page d’accueil :

1. Choisissez une ressource : fiches de poomsés, tirage ou cartes de kibon.
2. Pour un **tirage**, cliquez sur « Tirer 2 cartes par catégorie ».
3. Pour les **cartes**, choisissez une catégorie, puis un numéro de carte.
4. Dans l’affichage d’une carte, utilisez les flèches, les touches `←`/`→` ou le balayage tactile pour naviguer.

Les trois niveaux de kibon proposent les catégories suivantes :

- membres supérieurs et positions ;
- membres inférieurs ;
- membres supérieurs, membres inférieurs et positions.

Chaque catégorie contient actuellement huit combinaisons.

## Structure du projet

```text
.
├── index.html                     # Page d’accueil et accès aux ressources
├── fiches-poomses.html            # Fiches de poomsés
├── kibon_{1,2,3}dan_tirage.html   # Tirages aléatoires par niveau de Dan
├── cartes-kibon-{1,2,3}dan.html   # Consultation des cartes par catégorie
├── cards-{1,2,3}dan/              # Images des cartes de kibon
├── Documents-TKD/                 # Documents et lexiques de référence
└── favicon_io/                    # Icônes du site
```

Les pages HTML embarquent leur style et leur logique JavaScript. Certaines utilisent des polices Google Fonts ; une connexion internet est donc nécessaire pour leur chargement.

## Contribution

Les contributions sont bienvenues. Avant de proposer une modification :

1. Ouvrez une issue pour les changements importants ou les corrections de contenu.
2. Créez une branche dédiée.
3. Gardez les modifications ciblées et testez les pages concernées dans un navigateur, sur ordinateur et mobile.
4. Décrivez clairement la modification dans votre pull request, en précisant notamment toute source utilisée pour le contenu pédagogique.

Évitez de modifier les référentiels ou documents fédéraux sans vérification préalable de leur version et de leur autorisation de diffusion.

## Licence

Aucune licence n’est actuellement fournie dans ce dépôt. En l’absence de licence explicite, les droits restent réservés à leurs titulaires : contactez le mainteneur avant de réutiliser, redistribuer ou modifier le contenu en dehors de ce dépôt.

## Remerciements

- Documents et références liés à la **FFTDA**.
- Réalisation : Lionel Fruchard.
