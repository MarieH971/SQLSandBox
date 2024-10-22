## BASE DE DONNEES

base de données = programme qui permet de stocker des informations de façon ordonnée

base de données relationnelle : les fiches ont des relations entre elles (fiche identité et fiche médicale)

moteur de template

SQL 

serveurs php :  Apache (nginx caddy) permet de transformer le php en html

il faudra configurer ton serveur avec des paramètres particuliers // 

METHODE 1 svt tu bosses d abord en local et apres tu envoie sur le serveur généralisé

METHODE 2 Utilisation de DOCKER 

utilise une machine virtuelle et prendra uniquement ce qui l interesse // permet de mieux repartir les ressources // docker desktop permet de creer des machine virtuelles plus facilement

kubernet permet de gerer les flux pour eviter toute saturation

*LES 3 environnements du net*

1/  le dev 
2/  le staging ou recette (pour tester le code)
3/  la production (la page web consultable)

## DOCKER

fichier qui permet de deployer des services 

1 image php + 1 image pour le mySQL

1 docker compose pour charger les 2

format yml ?

2 services :
- web
- db

creation de service = definir une image

variable d environnement ?

franken php






