# Wild Circus 
___ 
 
[**Wild Circus**](https://jsfiddle.net/Benjah8/ubhj8f0o/) est un projet organisé par la [**Wild Code School**](https://wildcodeschool.fr) pour de la sélection des candidats lors de l'inscription. 
 
Le fiddle envoyé sur _Odyssey_ -> [https://jsfiddle.net/Benjah8/ubhj8f0o/](https://jsfiddle.net/Benjah8/ubhj8f0o/) 
 
## Exercices GitHub: 
 
[Cliquez ici](http://rogerdudler.github.io/git-guide/index.fr.html) pour avoir un memento sur quelques commandes de Git. 
 
### Réaliser un nouveau commit avec la console git: 
 
1) Si l'on est pas déjà connecté au dépôt distant, on devrait d'abord le faire: `git remote add origin https://github.com/benjahdev/Wild-Circus.git`. Cela nous permet de vérifier si n'y a pas eu de nouvelles modifications sur les fichiers: `git log -p`. On doit alors récupérer la dernière version du fichier si il y a eu des modifications dessus: `git fetch origin`. 
2) Pour effectuer un nouveau commit sur ce dépôt, je dois d'abord modifier l'un des fichiers qui y est présent, ce que je suis en train de faire parfait ! 
3) Une fois les modifications terminées, on vérifie que cette modification est prise en compte par git en faisant la commande `git status`. On observe donc que le fichier README.md est indiqué comme modifié. 
4) On ajoute le fichier au HEAD pour indiquer qu'il doit être mise à jour dans le prochain commit: `git add README.md`. 
5) On rentre ensuite la commande qui va nous permettre de valider la mise à jour du fichier: `git commit -m "Ajout du tutoriel"` avec un message pertinent concernant la modification apportée par le commit. 
6) On envoie les modifications de la branche locale '_origin_' vers la branche principale du projet sur GitHub '_master_' avec la commande `git push -u origin master`.
