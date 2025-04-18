# Mise à zéro automatique des cellules de charge

Les cellules de charge se mettent automatiquement à zéro quand la trémie à grain est vide ou lorsqu'un nouveau numéro
de série de cellule est installé.

La trémie est supposée vide lorsque les 3 cellules passent en dessous de la tension de sortie minimum et y restent pendant
une durée de 10 secondes.

Le logiciel utilise cette valeur de sortie comme nouvelle valeur zéro pour cette charge.
