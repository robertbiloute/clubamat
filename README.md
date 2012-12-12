clubamat
========

Ceci est une expérience.
Il s'agit d'utiliser la méthode 'git' pour faire des trucs à plusieurs.
Pour ce que j'ai compris, en bref:
- quand des mecs travaillent à plusieurs sur un projet informatique, 
il faut un outil pour gérer la collaboration simultanée sur le même code.
- Le système 'classique' est centralisé: un serveur central garde le programme de référence 
("repository" ou "dépôt" en français), et chaque modification doit avoir l'aval d'un ou plusieurs masters 
(genre l'auteur original du code par ex.)
- Le système git est décentralisé: mettons qu'on veuille bosser sur le projet X. On fait une copie du dépôt X ('fork'), 
on fait toutes les modifs qu'on veut, ensuite on peut proposer aux autres participants d'accepter les modifications 
qu'on a faites (= 'pull request'), ou juste attendre.
- Au final on a aussi un espéce de schéma darwinien: chacun sélectionne dans son coin les modifs qu'il trouve
pertinentes, à force de brassage et de sélection une version majoritaire du projet peut émerger, tout en laissant la 
possibilité à tout le monde de continuer à faire son truc dans son coin en refusant les modifs majoritaires.

un article pas mal sur github, ça explique bien la philosophie et l'historique:
http://www.wired.com/wiredenterprise/2012/02/github/

aide github, très bien faite:
https://help.github.com/

note sur le 'network visualizer', outil très pratique qui permet de représenter graphiquement les différentes branches 
de développement, autrement dit les 'forks' de tout le monde et les différentes modifs en fonction du temps:
https://github.com/blog/39-say-hello-to-the-network-graph-visualizer

pour exemple j'ai créer un autre utilisateur 'robobiloute' qui a fait des modifs sur le truc original.
Si vous cliquez sur 'Network' en haut, vous verrez, du point de vue de robertbiloute, que robobiloute a fait 2 premières 
modifs, il a fait un 'pull request' sur chacune de ces modifs, robertbiloute a accepté ces 2 pull request 
(il accepte que les modifs soit effective aussi chez lui) le graphe de robobiloute rejoint donc celui de robertbiloute.
Sauf que robobiloute a créé ensuite un nouveau fichier nommé YHVH, il n'a pas fait de pull request, robertbiloute 
n'a pas pris en compte ces modifs, donc la denière branche de robobiloute reste distincte de celle de robertbiloute.
(lisez le lien plus haut c'est bien expliqué..)

ça peut paraitre contre-intuitif au début, mais je pense que ça vaut le coup de s'y mettre, au moins pour essayer quoi.

Et pour quoi faire ? 
bah je sais pas, un texte dans un fichier? des phrases , une par fichier ? les 2? des codes ? 
tout ce qu'on veut du moment que ça se met sous forme de fichier texte.
Je vais donc commencer par crééer un bête fichier texte, dont le nom m'est venu à l'esprit dans la Xroom de Chaos/Darwin 
pour la petite histoire.

Ouvrez un compte Github, forkez le dépôt 'clubamat' de robertbiloute (robertbiloute/clubamat), vous aurez alors votre dépôt
X/clubamat, si vou vous appelez X (ce qui est un peu la loose quand même), et c'est parti.

Ce message ne s'autodétruira PAS.

Robert
