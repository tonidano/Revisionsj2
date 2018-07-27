# Revisions HTML-CSS

## Description
http://www.csszengarden.com/ : prenez le fichier HTML et habillez-le de CSS sans modifier le HTML et faites un truc qui casse des culs. Pour des idées, cliquez sur [view all designs]. monprayfayray

## Question
Pourquoi la forme géométrique varie-t-elle selon le navigateur utilisé?

Réponse :
Ce serait à cause de la manipulation de l'outline-offset.
Lorsque celui-ci a une valeur négative inférieur à -50px, alors la forme géométrique changera selon le navigateur, quelque soit la valeur de l'outline.
Si la valeur de l'outline-offset est supérieur à -50px, la forme reste inchangée.

Outline-offset < -50px =>

EDGE: Realism
FireFox: Modernism
Safari: Impressionism
IE: Classism
Chrome: Cubism
