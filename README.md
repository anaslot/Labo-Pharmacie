# LaboPharma — gestion de production

Application web pédagogique en HTML, CSS et JavaScript pour gérer les médicaments, leurs compositions, les matières premières, les stocks et les lots de production d'un laboratoire pharmaceutique.

## Fonctionnalités

- Tableau de bord avec les références, lots, unités produites et alertes de stock bas.
- Ajout, modification, recherche et suppression des médicaments et matières premières.
- Composition d'un médicament avec dosage en grammes par unité et taux de perte.
- Lancement et suivi des lots ; contrôle du stock avant production.
- Calcul et déduction des matières premières selon le dosage et le taux de perte.
- Stocks de matières premières et médicaments, historique des mouvements et export CSV.
- Interface responsive et sauvegarde locale dans le navigateur.

## Démarrage

Aucune installation n'est nécessaire. Ouvrez `index.html` dans un navigateur récent. Pour une meilleure expérience, servez le dossier avec l'extension Live Server de VS Code.

Les données sont conservées localement dans le navigateur utilisé. Elles ne sont pas partagées entre appareils et ne constituent pas une base de données centralisée. Les données d'exemple sont fictives et peuvent être réinitialisées en effaçant le stockage local du navigateur pour cette page (`labopharma-v1`).

## Publication sur GitHub Pages

Le dépôt GitHub du projet est [anaslot/Labo-Pharmacie](https://github.com/anaslot/Labo-Pharmacie). Pour publier l'application avec GitHub Pages, vérifiez que ses fichiers sont présents à la racine du dépôt, puis dans **Settings > Pages**, choisissez la branche `main` et le dossier `/ (root)`. Ouvrez ensuite l'URL GitHub Pages indiquée par GitHub et vérifiez les parcours de gestion.

## Technologies

- HTML5 pour la structure et les formulaires.
- CSS3 pour l'interface responsive.
- JavaScript natif pour la validation, les calculs, le DOM et `localStorage`.

## Limites

Cette réalisation est un prototype front-end de formation. Elle ne remplace pas un logiciel pharmaceutique certifié : elle n'inclut ni authentification, ni base de données serveur, ni traçabilité réglementaire, ni validation de procédés pharmaceutiques.
