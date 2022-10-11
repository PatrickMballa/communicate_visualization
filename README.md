# Exploration des données du système Ford GoBike
## Par Patrick Mballa


## Dataset ( Ensemble de données)

L'ensemble de donnée utilisé provient des données du système Ford GoBike que nous avons téléchargé directement en suivant le lien laissé dans la salle de classe (le fichier.csv est fourni dans le dossier).C'est ensemble de données comprend des informations sur les trajets individuels effectués dans un système de partage de vélos couvrant la grande région de la baie de San Francisco.

 Avant d'utiliser cet ensemble de données, nous avons procédé à quelques modifications, dont les princales sont:
- Suppression de la colonne année de naissaince pour la remplacer par la colonne des âges.

- Ajout de certaines colonnes princilement les jours de la semaine, les mois etc. Mais nous avons plus travaillé avec les jours de la semaine.

Après ce léger traitement de données, nous avons d'abord enrégistré ce fichier traité sous le nom "bike_new" (fourni également dans le dossier) pour l'utiliser directement dans la partie II. Ensuite nous avons procédé à l'analyse exploratoire des données, en procédant premièrement à l'analyse univariée, puis à l'analyse bivariée et enfin, à l'analyse multivariée. Cela s'est fait en utilisant le cadre Questions-Visualisations-observations.


## Résumé des résultats

La variables d'intérêt pour nous était la durée du trajet en secondes. on l'ont poursuivait l'objectif de savoir quelles variables de l'ensemble de donnée pouvait aider à prédire les plus longues durées de trajet. selon les étapes, on a obtenu les résultats suivants:

 - L'exploration univariée a revélé que la distribution de la durée des trajets est unimodale et tournée vers la gauche et la plupart des trajets sont inférieures à 2000 secondes (nous allons intégrer ceci dans la visualisation explicative). la distribution des âges indique une forte concentration entre 20ans et 60 ans. En outre, les diagrammes en bâtons nous montres qu'il y a plus dhommmes que de femmes dans le datast, plus d'abonnées que de clients, et moins de vélos en libre service.

 - L'exploration bivariée n'a pas montrer de corrélation linéaire entre l'âge et la durée en secondes. Cependant, l'on a pu constater que les utilisateurs les plus fréquents ont entre 20 et 35 ans, que les week-end (samedi et dimanche) enrégistrent les durées de trajets les plus longs , qu'un pourcentage plus élevé de clients effectuent des trajets plus longs que les abonnés (à intéger lors de l'exploration explicative),  et que les clients ne sont pas intéressés par les vélos en libre service.

 - L'exploration multivariée, a principalement mis en évidence le fait que Les clients du samedi et du dimanche font des trajets de plus longue durée que tout les autres utilisateurs (à intégrer dans la visualisation explicative), que quelque soit le jour de la semaine, les hommes réalisent les trajets les moins longs, que le samedi les femmes et le genre autre font des trajets de même durée et qu'enfin, les clients du genre autre enrégistrent la meilleure durée moyenne de trajet (à intégrer dans la visualisation explicative)

## Apperçus clés pour la présentation

Nous nous sommes principalement intéressé à la durée du trajet comme variable principale. De ce fait la prière visualisation est un histogramme qui montre comment est répartie cette variable d'intêret; nous allons pour cela soigner l'histogramme déjà réalisé dans la partie exploratoire

Ensuite nous avons trois résultats qui peuvent aider à prédire la durée du trajet. Le premier est la grande différence de durée de trajet observée entre les clients et les abonnés; ceci a été observé à l'aide d'une boîte à moustache. A la suite de ce premier nous premier résultat, nous avons creusé un peu plus pour constater, toujours à l'aide d'une boîte à moustache que ces clients réalisent justement les trajets de longue durée le week-end. Le troisième résultat concerne la répartition moyenne des duréee en fonction du genre et du type d'utilisateur; une carte thermique (heatmap) nous a été utilisé pour cela. 

Nous n'allons pas créer une nouvelle visualisation dans l'exploration explicative. le travail consistera à peaufiner les visualisations pour les rendre conforme.