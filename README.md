# google-homepage
golugolu homupajiru

Attempt at making a look-alike html copy of google's home page.

Structure:

<!-- header -->
<!--logo+ recherche-->
<!--grille 2 -1 footer-->

On décide que le header sera en pos abso, fix is a possible choice.

absolute + right empechait l'inhéritance de style,


idée: se servir d'une liste li mais comment retirer le point ?

Après vérif, bonne solution!!!!

on opte pour un #nav >* {} car ce qui est spéciale, c'est le ul, pas le li

problème résolu:
On veut une barre de nav qui occupe tout l'espace.
//
---------------------------------------------|
|  HEADER à 100% WIDTH        UL LI LI LI    |
|                             en FLOAT:RIGHT; 
|--------------------------------------------|

div div div

UL ne peut pas occuper plus que lespace occupé par header.


//

ne fonctionne qu'en display grid, tho


A deviné que la barre de recherge google était un text area décoré par des images et icones aux alentours !!!!
la lunette est juste un bloc cliaquable (bouton invisible?)


*Idée: travailler en display : grid
^
inutile, block suffit.