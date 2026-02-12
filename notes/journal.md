## Jour 1 – Introduction à JavaScript

### Ce que j’ai appris
- Ce qu’est JavaScript et son rôle dans le navigateur
- Ce que JavaScript peut faire lorsqu’il est intégré au navigateur
- Le lien fort entre JavaScript, HTML et CSS
- Que JavaScript n’est plus limité au navigateur
- L’existence des langages transpilés vers JavaScript
- Les IDE et éditeurs de texte
- Les outils de développement du navigateur (console, erreurs, variables)

### Pratique
- Utilisation de la balise `<script>` directement dans le HTML
- Utilisation d’un fichier JavaScript externe avec `src`
- Exécution de mes premières lignes de code avec `alert()`

### Ressenti
- Contenu dense mais intéressant
- Contente d’avoir exécuté mon premier code JavaScript
  
### Jour 2 - Les types de variables 
- Compris la différence entre let et const
- Utilisé alert() pour afficher des variables
- Encore un peu confuse mais je progresse
### Jour3 - Les types de données
Il existe 8 types de données de base en JavaScript.

Sept types de données primitifs :
number pour les nombres de toute nature : entiers ou en virgule flottante, les entiers sont limités par .±(253-1)
bigint pour des nombres entiers de longueur arbitraire.
string pour les cordes. Une chaîne peut avoir zéro caractère ou plus, il n’y a pas de type séparé à caractère unique.
boolean pour /.truefalse
null pour des valeurs inconnues – un type autonome ayant une seule valeur .null
undefined pour les valeurs non attribuées – un type autonome ayant une seule valeur .undefined
symbol pour des identifiants uniques.
Et un type de données non primitif :
object pour des structures de données plus complexes.
L’opérateur nous permet de voir quel type est stocké dans une variable.typeof

Généralement utilisé comme , mais c’est aussi possible.typeof xtypeof(x)
Retourne une chaîne avec le nom du type, comme ."string"
Pour les retours – c’est une erreur dans le langage, ce n’est pas réellement un objet.null"object"
Dans les prochains chapitres, nous nous concentrerons sur les valeurs primitives et, une fois que nous les connaissons, nous passerons aux objets.
### Jour4 -Interaction: alert, prompt, confirm
Nous avons couvert 3 fonctions spécifiques au navigateur pour interagir avec les visiteurs :

alert
Montre un message.
prompt
affiche un message demandant à l’utilisateur de saisir du texte. Il renvoie le texte ou, si le bouton Annuler est cliqué, .Escnull
confirm
affiche un message et attend que l’utilisateur appuie sur « OK » ou « Annuler ». Il revient pour OK et pour Annuler/.truefalseEsc
Toutes ces méthodes sont modales : elles mettent en pause l’exécution du script et ne permettent pas au visiteur d’interagir avec le reste de la page tant que la fenêtre n’a pas été fermée.

Il existe deux limites partagées par toutes les méthodes ci-dessus :

L’emplacement exact de la fenêtre modale est déterminé par le navigateur. En général, c’est au centre.
L’aspect exact de la fenêtre dépend aussi du navigateur. Nous ne pouvons pas le modifier.
C’est le prix à payer pour la simplicité. Il existe d’autres moyens de montrer de meilleures fenêtres et une interaction plus riche avec le visiteur, mais si les « gadgets » n’ont pas vraiment d’importance, ces méthodes fonctionnent très bien.
