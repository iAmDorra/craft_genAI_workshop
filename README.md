# Workshop Craft & Gen AI

Faire le kata en s'appuyant fortement sur GitHub Copilot

# Kata

Calculer la date d'invitation par rapport à l'éligibilité à un type de depistage, une date de naissance et la date du jour. 

La date d'invitation correspond au jour de naissance du mois de naissance auquel on ajoute le nombre de mois associé au type de depistage et de l'année courante. 

Il faut vérifier que la date d'invitation est bien valide, sinon on décale au jour ouvré valide. Si la date d'invitation est antérieure à la date du jour, on ajoute un an à l'année courante. Si la date d'invitation est un jour férié, on la décale au jour ouvré suivant. Si la date d'invitation est un samedi ou un dimanche, on la décale au lundi suivant.
