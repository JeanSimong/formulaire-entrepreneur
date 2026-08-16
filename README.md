# Questionnaire Medialo

Questionnaire statique de diagnostic client pour recueillir les besoins, irritants et priorites de migration ou de modernisation.

Le site est une page HTML autonome. La sauvegarde locale du navigateur est conservee avec `localStorage`, et les soumissions sont envoyees avec Netlify Forms.

## Deploiement GitHub + Netlify

1. Initialiser un depot Git et pousser ce dossier sur GitHub.
2. Dans Netlify, creer un nouveau site a partir du depot GitHub.
3. Laisser le dossier de publication a la racine du projet.
4. Ne pas definir de commande de build: `index.html` est servi directement.
5. Publier le site, puis tester une soumission.

Les reponses seront visibles dans Netlify, section Forms, sous le formulaire `diagnostic-medialo`.
