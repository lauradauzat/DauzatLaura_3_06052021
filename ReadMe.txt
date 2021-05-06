Sass Organisation 

base/ 
    - Police
    - Normes appliquées à tout le site 

utils/
    - Variables
    - Fonctions 
    - Mixins
    - Placeholder 

layouts/
    - Blocs BEMs généraux (header, footer)
    Un layout fonctionne en autonomie alors qu'un composants est un éléments spécifique d'un layout

composants/ 
    -Blocs BEMs plus spécifiques (boutons)

pages/ 
    -Blocs qui ne s'appliquent qu'à une seule page 

themes/
    -Code thématique (?)

vendors/
    -Css extérieur (Bootstrap, jQuery)
