# Données — Vide-grenier du quartier

## Données nécessaires et provenance

| Donnée | Valeur pour cet exercice | Source / validation attendue |
| --- | --- | --- |
| Titre | Vide-grenier du quartier | Sujet du cours |
| Date | 15 mai 2027 — date fictive | Valeur inventée pour l’exercice ; à remplacer uniquement après confirmation par l’association |
| Horaires | Non renseignés | À demander à l’association si le projet est poursuivi |
| Lieu et adresse | Non renseignés | À demander à l’association si le projet est poursuivi |
| Présentation et conditions de participation | Non renseignées | Texte officiel à fournir et valider par l’association |
| Contact public | Non renseigné | Coordonnées officielles autorisées par l’association |

Aucune date, adresse ou coordonnée réelle n’est supposée. Le fichier index.html utilise uniquement le titre et la date fictive. Aucun appel à une API ni aucune collecte de données personnelles n’est nécessaire.

## Où ranger les données

Pour ce squelette, le titre et la date sont écrits directement dans index.html. Ce document conserve leur provenance et indique les informations encore manquantes. Une modification de la date doit être reportée dans index.html, ACCUEIL.md et ce document pour préserver la cohérence.

## Où ranger une éventuelle clé

Aucune clé n’est nécessaire pour cet exercice. Si un futur service exige une clé secrète :

- La ranger dans un fichier .env local, ignoré par Git, ou dans les secrets de l’environnement d’exécution.
- Ne jamais la placer dans index.html, un fichier JavaScript envoyé au navigateur, un document ou une issue.
- Utiliser un service côté serveur si la clé doit rester confidentielle : une page HTML publique ne peut pas la protéger.
- Partager uniquement le nom de la variable et une valeur factice dans un éventuel .env.example.

Le .gitignore du dépôt exclut .env et .env.* et autorise .env.example. Aucun fichier contenant une vraie clé ne doit être ajouté.
