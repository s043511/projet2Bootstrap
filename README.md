# projet2Bootstrap
Version Initiale - Projet OpenClassRooms 2 - BOOTSTAP - Faites la promotion des activit�s de votre ville


Version 8/1/2017
----------------

MAJ suite remarques Aurelien le 04/01/2016


Sur la page principale

- Menu: les liens du menu redirigent vers les autres pages 
- Mettre le carroussel sur la partie superieure de la page et toute sa largeur
- Sur la partie inferieure
	- � droite : mettre le d�but de la derni�re actuali� avec l'image
	- � gauche : mettre le message de bienvenue
- Taille de "Bienvenue � CAEN" trop grand
- Couleur police du texte en gris, laisser les titres en orange

Page Activit� du mois

- tableau pas responsive
- les boutons en TD au lieu de TR

Page Actualit� et Index
- Taille des images 100%

Remarques g�n�rales
- Police paragraphe en gris au lieu de orange

Version 20/01/2017
-----------------------------

Pour toutes les pages HTML
  Ajout de la balise TITLE dans le HEAD :  <title>Activit�s de la ville de CAEN</title>
  Balise <HTML> ajout de lang="fr"

Page Actualit�
HTML
   Les balises de fermeture </span> et </a> sont invers�es. Corrig� 3 fois pour chaaque actualit�.

Page plus d'info
HTML
  les classes bootstrap class = "col-lg-4 col-sm-6 col-xs-12" sont mal plac�es au niveau de la balise IMG au lieu de DIV juste au dessus - � corriger 3 fois
CSS
  L'image centr�e par rapport au texte qui est sur la m�me ligne : display : flex ; et align-items: center ; pour grand ecran et tablette, pour mobile : display:block;
  Sur les paragraphe de text � c�t� de l'image, text-align:justify pour occuper toute la largeur du block

Page Activt� du mois
HTML
  Sortir le titre (DIV panel-heading) du tableau, le mettre juste au dessus du la balise TABLE, pas de DIV dans une table , que des THEAD, TR, TD,
  Enlever les blancs dans </ button > ==> </button>

Page Contact
HTML
  D�pacer la balise Legend dans le fieldset qui se trouve juste en dessous
  label for="texte" => remplacer par label for="objet" 
  label for="texte" => remplacer par label for="nom"
  label for="texte" => remplacer par label for="dateNaissance", type="text" au lieu de type="date" qui n'est pas support� par tous les navigateurs
  label for="texte" => remplacer par label for="email"

Reste � faire 
  Barre de navigation : int�gration du bouton de recherche dans la liste des choix � l'int�rieur d'un <li></li> en plus
