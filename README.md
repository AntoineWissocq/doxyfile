# Documentation de drunk_player 
[GitHub](http://github.com) ##Description

Drunk_player est un système de lecture de vidéos qui a trop bu. Il lit les vidéos contenues dans un dossier par morceaux, aléatoirement et parfois en transformant l'image.

Drunk_player utilise la bibliothèque de traitement d'image OpenCV et est composé :

 * d'une bibliothèque (drunk_player) contenant le code de base    
 * d'un programme graphique (drunk_player_gui) qui affiche le résultat à l'écran   
 * d'un programme console (drunk_player_cli) qui sort le résultat dans un fichier 
    

## Dépendances

 * OpenCV
 * Boost
 
## Compilation

	mkdir build
	__cd__ build
	_cmake .._
	__make__
	
## Utilisation

	_./drunk_player_gui.out ../data/_


![GitHub Logo](/drunk_player_gui.png)
