🗂️ **Apprendre à faire un MCD (Modèle Conceptuel de Données)**

🎯**Objectif**

Le MCD est utilisé pour modéliser les données d’un système avant de créer une base de données.
Il permet de représenter les entités, leurs attributs et les relations entre elles.

En résumé :

- Entité → correspond à un objet du système (ex : Utilisateur, Produit, Commande)

- Attributs → propriétés d’une entité (ex : nom, prénom, date de naissance)

- Relation → lien entre deux entités (ex : un utilisateur passe des commandes)

🏗️ **Étapes pour créer un MCD**

**1. Identifier les entités**

- Ce sont les "objets principaux" de ton système.

- Exemple : Auteur, Livre, CompteBancaire, Titulaire.

**2. Lister les attributs de chaque entité**

- Exemple pour Auteur : nom, prénom, dateNaissance

- Exemple pour Livre : titre, année, nbPages, prix

**3. Identifier les relations entre les entités**

- Une relation décrit comment les entités sont liées.

- Exemple : un Auteur peut écrire plusieurs Livres → relation 1-à-plusieurs

**4. Définir la cardinalité**

- Cardinalité minimale et maximale de chaque côté de la relation.

  - Exemples :

- 1 Auteur — Écrit → 0..* Livre

- 1 Livre — Appartient à → 1 Auteur

- 1 Titulaire — Possède → 0..* CompteBancaire

**5. Dessiner le diagramme**

- Entités sous forme de rectangles

- Attributs listés à l’intérieur

- Relations sous forme de losanges ou de lignes avec cardinalités

📝 **Bonnes pratiques**

- Chaque entité doit avoir une clé primaire unique (ex : idAuteur, idLivre)

- Bien définir la nature des relations (1-1, 1-n, n-m)

- Les attributs identifiants doivent être clairs et uniques

- Ne pas oublier les relations facultatives ou obligatoires
