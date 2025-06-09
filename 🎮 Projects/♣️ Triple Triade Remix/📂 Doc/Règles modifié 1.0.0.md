
Le Triple Triad est un jeu de cartes qui se joue à deux sur un plateau de 3x3 cases. 
Le but est de retourner le plus de cartes adverses.
Quand les neuf cases du plateau sont remplies, le gagnant est celui qui a le plus de cartes de sa couleur sur le plateau. 
## Organisation d'une partie

Le joueur qui commence est désigné aléatoirement. 
Chaque joueur pose ensuite une carte l'un après l'autre. Dès que le plateau de jeu est rempli, la partie est finie. 
La partie se déroule en BO3. dès qu’un plateau est rempli et que les joueurs ne peuvent plus poser ni de carte action ni de carte équipement, le round s’arrête. Outre la victoire par round, un score sera attribué aux joueurs en fonction du nombre de cartes de leur couleur présente sur le plateau.
## Règle de base![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXebw0OuVfXCV5lDjuNPGnyQr9agKVkqFiBy98armlHekWh3CSBRJUlFtB6Gwq-8HWPG2QT4e5nrHph3-CvsoARFciJCdO0P8maZ3EElSWcj4ta-_RPtf0Zggis0tkI4hcR92QVwRNGKpHDqitrMDS3SeXM?key=opTjarTGxBxMdCxYEcOWDQ)

Une carte est composée de quatre valeurs de 1 à 10 (10 est noté A). Chaque valeur correspond à la force d'un côté de la carte. Par exemple, la valeur la plus à gauche donne la force du côté gauche de la carte.
Lorsque vous posez une carte à côté d'une autre carte (ennemie) sur le plateau, si votre carte est plus puissante sur le côté qui touche l'autre carte, alors l'autre carte est retournée (et la couleur de fond change (bleu/rouge)). 
## Les regles du projet FEFAGO
les règles régionales sont mortes, vive les règles régionales !  
il y aura 3 modes de jeu :
- libre
- normal
- compétitif
## le mode libre
Le mode libre reprend les règles du mode normal mais dévoile la main de l’adversaire.
(inspiré du mode Open du jeu de base)
## le mode normal
Vous devez choisir le deck à jouer(20 cartes). les cartes du deck sont mélangé aléatoirement puis une main de 5 cartes vous est proposé, un tour de mulligan est disponible pour le joueur ayant le deuxième tour*. (inspiré du mode aléatoire du jeu de base).
Si deux cartes adjacentes ayant un côté égal sont posées, les cartes ne seront pas retournées hormis si les propriétés spéciales ou une carte équipement avantage l’une ou l’autre. (inspiré du mode Identique du jeu de base).
Les cartes actions ou équipements peuvent être posés sur les cartes déjà présentes sur le plateau. voir le chapitre sur les cartes spéciales et celles-ci auront un effet immédiat sur le retournement des cartes sur le plateau.
Certaines cartes disposent d’un effet déjà implémenté, voir le chapitre sur les [effets](https://docs.google.com/document/d/1ltzMS-o4lZaqmxGnHV1283GR637Ew2BzABrDADuWKy4/edit#heading=h.gai57yhhpb8c).
*le premier joueur à 5 tours à jouer contrairement au deuxième qui n’en as que 4, par soucis d’équilibre, le mulligan n’est disponible que pour ce dernier

## le mode compétitif
Les règles sont les mêmes qu’en normal à la seule différence que le vainqueur gagne des points de classement correspondant à la différence entre les deux scores des joueurs. une victoire par peu de point fera moins monter le classement qu’une victoire écrasante
## Le scoring

Les règles de scoring sont simples, le joueur ayant le plus de cartes retournées à la fin du round remporte le round. Le nombre de cartes de la couleur du joueur en fin de round est comptabilisé en points, points ensuite comparé et utilisé pour les différentes récompenses du vainqueur. La partie se fait en BO3.
## La règle du vainqueur
A la fin de la partie le vainqueur récupère de la monnaie virtuelle pour l’achat de booster. Ou une carte mise en gage par son adversaire.
### Libre
Le gagnant gagne 10 pièces.
### Normal
Le vainqueur remporte l’équivalent de la différence des deux scores en pièce, multiplié par 10.
### Echange
Le joueur met en gage une carte, le matchmaking se fera suivant le niveau de la carte. ex: un joueur mettant en gage une carte de rareté 2 tombera forcément contre un joueur ayant mis en gage une carte de même valeur.
## Les effets
### Elémentaire
les effets élémentaire n’ont effet que sur les cartes non élémentaire OU d’un élément différent (voir règles spécifique)
#### terre
Cet élément ajoute un point de bouclier à la créature, cependant sur un côté de valeur “A”, l’élément terre n’aura aucun effet.
- faiblesse : eau
- force : feu

Il y à 2 niveau d’élément terre :
- niveau 1
l'élément terre ne s’applique que sur un côté de la carte au choix de l’utilisateur
- niveau 2
l'élément terre s’applique de chaque côté de la carte
#### foudre
Si une carte d’élément foudre retourne une autre carte, celle-ci est alors mise en combat contre la carte suivante dans la continuité de la ligne. Les cartes et foudre terre stop la réaction en chaîne.
#### glace
Une carte de type glace mis à côté d’une carte de type terre crée un élément “permafrost”. La carte de type terre dispose donc d’un point de bouclier supplémentaire.  
elle dispose d’un bonus d’attaque contre les cartes de type eau et un malus de dégâts contre les cartes de type feu
#### vent
Les cartes de type vent ont une portée d’attaque de 2 cases.
#### poison
Les cartes de type poison infligent un malus d’attaque à toutes les cartes adverses adjacentes.
#### feu
Les cartes de type feu placent un dot de 2 tours sur les cartes adverses adjacentes, même si la carte change d’équipe, le dot continu et peut retourner la carte affligée. Le type feu n'a aucun effet sur le type eau et le type terre.
#### eau
Les cartes de type eau suppriment l’altération de feu sur les cartes alliés adjacentes. Elles disposent aussi d’un bonus d’attaque contre le type feu et passe au travers du bouclier du type terre
### les contrôles
#### confusion
Une carte confuse attaque une carte allié adjacente aléatoire avec une de ses stats d’attaque choisie aléatoirement
#### provocation
Si une carte est posée dans une case adjacente à une case disposant de provocation, l’attaque de cette carte n’aura lieu qu’unidirectionnellement.