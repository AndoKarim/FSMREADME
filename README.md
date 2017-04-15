######Auteur
*Abdelkarim Andolerzak - SI4*

#Introduction
Deux projets sont présents : 
- Un projet **Generator** qui génère le code de la state machine
- Un projet **Stimulateur** qui va utiliser le code généré pour stimuler la machine

#Supporté
- Gestion des Etats d'un graphe
- Gestion des Transitions d'un graphe
- Gestion des SEND
- Gestion des LOG
- Gestion des OnEntry 
- Gestion des OnExit
- Association d'une fonction à un évenement dans le Stimulateur

#TODO
- Les events "event.*", "event.x" etc. 
- Les états hierarchiques
- Les états parallèles
- Les Raise (à cause de la librairie utilisée)


##Lancer le script de compilation et d'execution de la chaine complète (Generator + Stimulateur)
>./setupGenerator.sh chart.scxml

**chart.scxml : Doit être présent dans Generator/src/main/resources**
