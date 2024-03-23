Cron est un démon système qui s'exécute en arrière plan pour exécuter des tâches souhaitées à des moments désirés.
Un fichier crontab un simple fichier texte qui contient tout simplement la listes des tâches planifiées. Il est édité en utilisant la commande crontab.

Chacune des lignes de ce fichier est constituée de trois champs : temps-et-date, la commande à exécuter et une retour de ligne '\n' tous séparé. ces champs étant séparés par espaces.

le champs temps-et-date a 5 champs non séparés par des espaces et qui permettent des valeurs comme suit :

| Champ     | Valeurs autorisées      |
|-----------|-------------------------|
| minute    | 0-59                    |
| hour      | 0-23, 0 = minuit        |
| day       | 1-31                    |
| month     | 1-12                    |
| weekday   | 0-6, 0 = dimanche       |


Dans ce projet je vous propose de découvrir une tâche de sauvegarde automatique planifiée pour s'exécuter tous les jours à 