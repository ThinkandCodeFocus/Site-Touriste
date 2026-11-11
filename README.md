# Site Touriste

Site vitrine statique pour une agence de voyage (billets d'avion au depart de Dakar,
packages Omra et Hajj, hotels, visa et assurance voyage).

## Contenu

| Page | Role |
| --- | --- |
| `index.html` | accueil, avec le formulaire de recherche |
| `resultats.html` | resultats de recherche de vols |
| `services.html` | prestations de l'agence |
| `about.html` | presentation |
| `contact.html` | formulaire de contact |
| `elements.html` | page de reference des composants du gabarit |

Les styles sont ecrits en SCSS dans `scss/` et compiles vers `css/style.css`.
`prepros-6.config` est la configuration Prepros qui sert a cette compilation :
modifier le SCSS sans recompiler ne change rien a l'affichage.

## Mise en route

Aucune dependance a installer, aucune etape de build pour simplement ouvrir le site.
Il suffit de le servir depuis la racine du depot :

```sh
python -m http.server 8000
```

puis d'ouvrir http://localhost:8000.

## Gabarit d'origine

Base sur le gabarit libre **Tour** de [Untree.co](https://untree.co/),
sous licence [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/).
Voir `README.txt` pour la notice de l'auteur.

## Notifications Discord

L'activité du dépôt est renvoyée dans un salon Discord de l'équipe : tickets
ouverts, fermés et rouverts, commentaires, commits, branches, et releases.

Le salon n'est pas un canal de décision : ce qui compte reste écrit dans le
ticket. Discord sert à savoir qu'il s'est passé quelque chose, pas à discuter à
la place du ticket.

L'adresse du webhook est un secret. Elle vit dans les réglages du dépôt
(Settings, Webhooks) et ne doit jamais être écrite dans un fichier, un ticket ou
un message : toute personne qui l'a peut publier dans le salon.
