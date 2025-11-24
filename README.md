📊 Netflix BI — Analyse de Visionnage (Dashboard Streaming)

Ce projet est un tableau de bord interactif permettant d’analyser le comportement de visionnage sur une plateforme de streaming (type Netflix).
Il a été pensé pour être simple à utiliser, totalement local (pas besoin de backend) et compatible avec tout fichier CSV respectant la structure de base.

🎯 Objectifs du projet

Ce dashboard a été développé dans le cadre d’un projet BI afin de :

mesurer la popularité des films et séries ;

analyser la répartition des vues par genre ;

visualiser la popularité selon les pays ;

suivre les tendances mensuelles de visionnage ;

identifier les meilleurs titres (Top films/séries) ;

fournir une plateforme adaptable à n’importe quel CSV utilisateur.

⚙️ Fonctionnalités principales
✔ Importation CSV

L'utilisateur peut importer un fichier CSV contenant l’historique de visionnage.
Le système affiche automatiquement un aperçu des données (10 premières lignes).

✔ Traitement automatique des données

Le script JavaScript gère :

normalisation des dates (YYYY-MM-DD → mois YYYY-MM)

regroupement par genre, pays, titre, mois

prise en compte directe d’une colonne Views

normalisation automatique des noms de pays

✔ Visualisations interactives

Camembert des vues par genre

Courbe des vues mensuelles

Top films/séries (bar chart)

Carte mondiale (Leaflet) avec bulles de popularité

KPIs : total vues, films distincts, pays distincts, durée totale, note moyenne

✔ Filtres dynamiques

Genre

Pays

Mois

Film (via clic sur les barres)

✔ Export

Téléchargement d’un CSV contenant les agrégats calculés.
