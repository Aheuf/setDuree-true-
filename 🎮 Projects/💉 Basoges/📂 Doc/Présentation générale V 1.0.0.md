## Table des matières
- [Gameplay](#Gameplay)
	- [Tronc commun](#Tronc-commun)
		- [Crafting](#Crafting)
		- [Les ennemis](#Les-ennemis)
			- [Variété et type d'ennemis](#Variete-et-type-dennemis)
			- [Equilibrage dynamique](#Equilibrage-dynamique)
		- [Arbre de compétence](#Arbre-de-competence)
	- [Exploration](#Exploration)
		- [Visibilité et lumière](#Visibilite-et-lumiere)
		- [Armes et équipements](#Armes-et-equipements)
		- [Limite et pression du temps](#Limite-et-pression-du-temps)
	- [Tower defense](#Tower-defense)
		- [Infrastructure de base](#Infrastructure-de-base)
	- [Fin du jeu](#Fin-du-jeu)
	- [Gestion de la fin et difficulté](#Gestion-de-la-fin-et-difficulte)
	- [Déclenchement volontaire de la fin](#Declenchement-volontaire-de-la-fin)
	- [Conditions de fin](#Conditions-de-fin)
- [Style](#Style)
	- [Ambiance Bio-Mécanique & Corruption](#Ambiance-Bio-Mecanique-&-Corruption)
	- [Palette & Contraste Visuel](#Palette-&-Contraste-Visuel)
- [Histoire](#Histoire)
	- [Prélude](#Prelude)
	- [Durant le jeu](#Durant-le-jeu)
	-  [Corruption des souvenirs](#Corruption-des-souvenirs)
## Gameplay
### Tronc commun
Le jeu est fait pour être fait en solo.
Le gameplay alterne entre deux phases : un mode Tower Defense (TD) et un mode dungeon crawler/rogue-lite<sup>1</sup>. La transition s’effectue lorsque le joueur revient à sa base pour améliorer son arbre de compétences.
Il peut alors choisir de continuer à explorer pendant plusieurs jours in-game, ou bien dépenser ses ressources pour déclencher immédiatement la phase TD après l’amélioration. Si le joueur manque de ressources pour progresser, il pourra malgré tout forcer le passage en mode TD via un bouton dédié sur le panneau d’amélioration.

Il y aura un cycle jour / nuit mais celui-ci sera indépendant du cycle de gameplay.

#### Statistique du joueur
pouvant s'appliquer à la base et au joueur :
- santé
- mana
- dgts physique
- dgts occultes
- esquive
seulement la base :
- armure
- vitesse d'attaque (compatible avec les armes que peux porter le joueur mais pas avec le joueur en lui même)
seulement le joueur :
- endurance
- santé mentale
- faim
- soif
#### Crafting
un système simple d'inventaire et de crafting de petits objets sera disponible en mode exploration, ce même système sera amélioré si le joueur est présent dans la base. Les recettes seront débloqué en trouvant des plans

#### ingrédients
- charbon
- essence de *statistique*
- argent
- ferraille
- charbon
- munitions
- piles
- nourriture
- boisson
- pilules (médicament ou autre)
- "souffle de vie" (ressource occulte)

*<sup>1</sup>différent de rogue like car des évolutions permanentes peuvent être apportée au joueur*

---
#### Les ennemis
Plusieurs factions hostiles coexisteront dans le jeu, chacune avec ses propres caractéristiques, types d’unités et comportements :

- **Les Cultistes**  
    Faction fanatique et peu puissante, ils constituent les premiers ennemis du jeu. Leur présence diminue fortement après la défaite de leur chef.  
    → _Servent principalement d’introduction au combat et à l’univers._
- **Les Mutants**  
    D’anciens humains transformés en créatures monstrueuses. Leur apparence et leurs capacités varient, souvent influencées par leur faction d’origine.
    Ils sont comme particularité de jouer sur la santé mentale du joueur. Certains mutant attaque cette santé plutôt que les points de vie, d'autre font baisser cette barre à vue. Un mutant spécial peut apparaitre durant la partie, celui-ci est à considéré un peu comme le dieu de la mutation, si celui-ci est présent dans l'explo, le joueur ne pourras jamais le voir, cependant sa santé mentale va diminuer sans s'arrêter durant cette phase, rajoutant virtuellement un chrono.
- **Les Brigands**  
    Des survivants humains vivant dans les terres désolées, violents et opportunistes. Ils pillent tout ce qu’ils peuvent, attaquant sans prévenir.
- **La Milice**  
    Groupe armé structuré, bien équipé et discipliné. Ils représentent l’adversaire humain le plus redoutable du jeu.

> **Note** : Toutes les factions humaines peuvent avoir des représentants mutants, reflétant une contamination ou transformation progressive du monde.

##### Variété et types d’ennemis
Chaque faction proposera plusieurs types d’ennemis aux rôles distincts (par exemple : éclaireur, tank, soutien, etc.), dans l’esprit de la diversité rencontrée dans [enemis présent dans left 4 dead](https://left4dead.fandom.com/wiki/The_Infected).  
Cette diversité permettra une plus grande richesse tactique dans les combats.
Certains ennemis de la phase d'explo seront fait pour être éviter le plus possible.
##### Équilibrage dynamique
La **quantité et la puissance** des ennemis seront ajustées dynamiquement en fonction de **l’avancement du joueur dans le jeu** (et non de ses statistiques ou de sa "puissance" effective).  
Ce choix sert la **narration** en soulignant l’escalade de tension et de danger, plutôt qu’un simple effet de scaling mécanique.

---
#### Arbre de compétence
L’arbre de compétences sera partagé entre le joueur et la base, contraignant ainsi le joueur à faire des choix stratégiques sur les aspects du gameplay à améliorer, et dans quel ordre le faire. Certains nœuds nécessiteront le déblocage préalable d'autres nœuds pour être activés. Les compétences pourront être de type passif ou actif *(voir [[Basoge_Arbre de compétence]])*.

Le déblocage des nœuds se fera en échange de ressources (argent, ferraille, pilules, souffle) et dépendra de la disponibilité des prérequis.  

***Un nombre maximum de nœuds déblocables par partie devra être défini, ainsi que le coût de chaque nœud (en ressources).***

Les compétences actives seront limitées en nombre — **5 maximum** par partie _(valeur à confirmer)_. Toutes les compétences actives auront un cooldown plus ou moins élevé en fonction de sa puissance.

Certains nœuds seront classés comme _occultes_ ou _scientifiques_ et influenceront le déroulement narratif ainsi que la difficulté du jeu. *(voir section ***fin du jeu***). Plus l'influence du nœud est mauvaise plus son pouvoir est fort et à un plus gros impact sur le gameplay / gamefeel.

Les impacts seront surtout sur la fin disponible pour le joueur mais impactera aussi la difficulté du jeu, les factions plus présente, la qualité des savoirs récupérés, l'aspect du joueur et l'aspect de l'environnement.

Si le joueur n'est pas satisfait de l'évolution qu'il a choisi, une réinitialisation de l'arbre est possible, cependant pour une réinitialisation les ressources qui lui sont rendu perdent 10%. Plus il réinitialise son arbre, moins de ressource lui seront rendu à raison de 5% supplémentaire à chaque réinitialisation.
Aucun indice ne sera donné au joueur quand au compétence à avoir pour tel ou tel alignement.
Cependant toute compétence ayant un alignement occulte baissera automatiquement la santé mentale maximale du joueur

---
### Exploration
Lors de cette phase, le joueur sera plongé dans un **environnement semi-urbain dévasté**, à explorer entre chaque vague de défense.  
La carte changera à chaque boucle de gameplay, avec une **structure semi-procédurale** : certains **points d’intérêt fixes** resteront présents entre les cycles, tandis que d’autres seront **mobiles ou générés aléatoirement**.

L’objectif principal de cette phase est double :
- **Récolter des ressources** nécessaires à la survie et à l’amélioration de la base.
- **Collecter du savoir**, essentiel pour comprendre l’histoire du monde et ses mystères.

Le joueur pourras aussi attaquer des campements ennemis afin de favoriser certaines factions ou diminuer la difficulté des attaques durant la prochaine phase de TD

Le **savoir** pourra prendre différentes formes :
- Enregistrements audio
- Pages de journal ou lettres
- Lieux emblématiques à explorer
- Rapports scientifiques
- Affiches ou tracts de propagande cultiste

Le savoir n'est que purement narratif et à pour but de guider le joueur sur ce qu'il s'est passé et ce contre quoi il se bat. Cela étant, les modifications de l'arbre de compétence pouvant attirer le joueur vers l'occultisme ou la science, les savoirs auront plusieurs version altérer et une réelle.
#### Visibilité et lumière
La **visibilité** du joueur dépendra de deux facteurs :
- Le **cycle jour/nuit**, influençant la luminosité ambiante
- Les **obstacles physiques** (murs, ruines, décombres, etc.)

Le champ de vision sera simulé de manière immersive :
- **120°** de champ total, dont **60° nets** au centre
- Le reste sera **flouté** ou partiellement obstrué

Le joueur pourra utiliser une **lampe torche**, à condition d’avoir des **piles** dans son inventaire.  
Elle éclairera un **cône clair de 40°**, diffusé progressivement jusqu’à **90°** devant lui.  
La gestion de la lumière devient donc stratégique, notamment la nuit ou dans des zones cloisonnées.
#### Armes et équipement
Le joueur pourra trouver ou fabriquer des **armes modernes ou improvisées**, par exemple :
- Couteau attaché à un manche à balai
- Pistolet de fortune
- Fusil à pompe
- Hache de pompier

Les armes auront une **durabilité limitée**, mais pourront être **réparées ou améliorées** à l’aide de **ferraille**.  
Les armes à distance nécessiteront des **munitions**, qui pourront être **trouvées** dans l’environnement ou **craftées** à partir de ressources. Cependant pour le craft, des plans devront être trouvés.
#### Limites et pression du temps
La carte aura une **taille définie** et un **nombre limité de ressources** disponibles à chaque cycle (tant pour le gameplay que pour la narration).  
Plus le joueur **prolonge son temps en extérieur**, plus la **dangerosité augmente** : les ennemis deviennent plus puissants, le poussant à rentrer se réfugier dans la base.

---
### Tower defense
Cette phase n’est accessible que lorsque le joueur se trouve dans la base. Chaque amélioration apportée à l’arbre de compétences (qu'elle concerne le joueur ou la base) déclenche automatiquement une vague d’ennemis. Ces modifications ne peuvent pas être apportées durant les phases de jeu.

Le joueur peut également **déclencher manuellement une vague** s’il manque de ressources pour débloquer une amélioration, afin de relancer une boucle d’exploration et de combat.

Le **cycle d’exploration étant potentiellement infini en longueur**, les vagues deviennent le **seul moyen de renouveler les ressources** présentes sur la carte. Chaque vague provoque également la **régénération partielle des ennemis et des zones non-clefs**, créant une boucle dynamique entre progression et survie.

Comme pour la phase d'exploration la carte de tower defense evoluera au fil du jeu, apportant de plus en plus de couvert et d'éléments aidant les assaillant à progresser.

> ⚠️ Cette phase ne repose pas sur un gameplay de _tower defense_ classique (piéger des chemins), mais plutôt sur une **défense active de base**, dans l’esprit de jeux comme [dome keeper](https://www.google.com/search?sca_esv=41514daaec8f90aa&sxsrf=AE3TifOZ_xphWZ55YUOM5pgINfz71VgoUQ:1749030959326&q=dome+keeper&udm=2&fbs=AIIjpHx4nJjfGojPVHhEACUHPiMQ_pbg5bWizQs3A_kIenjtci1AK0oIkDPIMLSzNdfCsSc8fzt7zKTB_5g-M4JgPZRHl2tFcRFC5GOXGn4nS2uEtMuRlbFTrEALXwih5iRT-8eIJP2WDZRtVGb2iJcrLjunAUA9rzbTTPok4cgZY7D4a_Zi3qNnFoNknsffhQnmL1-KDpsdGmQ-BBmeBkyl1hoBubhQ8A&sa=X&ved=2ahUKEwiaqaCIwNeNAxVHK_sDHUPZNtQQtKgLegQICxAB&biw=1920&bih=945&dpr=1) ou [the tower](https://www.google.com/search?sca_esv=41514daaec8f90aa&sxsrf=AE3TifPlKEYnA_W_nCeDFCbEdbh0V_XE-Q:1749031112490&q=the+tower+tower+defense+game&udm=2&fbs=AIIjpHx4nJjfGojPVHhEACUHPiMQ_pbg5bWizQs3A_kIenjtcl5m1cuBb92K2q0CMDvBK8EzCOmw7_nopkk8T-EnH0WDh_7wJ3TaKTPTBtw7jrIldI-dE3JJ8j-Xr9AG-S0KQjAp7hXILL85tgrxIcla8iUbdC9MGhzbst4d8K61p3wYBm5qSf0LwteBHj6kP9smQ3i9R9J5&sa=X&ved=2ahUKEwj60qTRwNeNAxVhVqQEHTsVAScQtKgLegQIEhAB&biw=1920&bih=945&dpr=1), où le joueur prend part directement à la défense et à la gestion des améliorations.

Par ailleurs, certaines fonctions avancées de la base nécessiteront une ressource spécifique, le **charbon**, notamment pour alimenter des systèmes automatisés ou des modules d’amélioration continue. en plus de l'automatisation de certains modules, la base aura un coup d'entretien par cycle en fonctions des modules débloqués

***La durée d'une phase de TD est à définir en temps, cependant elle se finiera toujours pas l'attaque d'une figure d'une faction adverse***
#### Infrastructure de base
cf: [[Basoge_Arbre de compétence]]
les améliorations de bases seront répartie sur les 6 catégories disponible sur l'arbre de compétences, elle permettront de déployer une meilleure attaque, résistance etc...
Toute amélioration apportant une nouveauté "structurel" aura effet immédiatement après achat de la compétence.

---
### Fin du jeu
Un **élément central situé dans la base** servira de **fil rouge narratif** et déterminera la progression vers la fin du jeu. Son **avancement en recherche et développement** conditionnera le dénouement.  
Chaque palier de progression nécessitera des **ressources communes** ainsi que des **ressources spécifiques**, et sera suivi d’un **délai imposé** pour éviter que le joueur ne complète tout d’un seul coup.
#### Gestion de la fin et difficulté
Le joueur pourra choisir **d’ignorer cet objectif final**, mais le **temps passé en jeu** étant un facteur **clé d’augmentation de la difficulté**, cela finira par le **bloquer dans la base**.  
Si ce moment arrive et que certains éléments critiques n’ont pas été découverts ou collectés, une première fin s’enclenche automatiquement :  
→ **Bonne Fin 2** : issue partielle, où le joueur survit (a court terme) mais sans avoir pu résoudre l’origine de la corruption.
#### Déclenchement volontaire de la fin
Si le joueur choisit **d’activer manuellement le projet final** via l’élément central, trois fins différentes pourront se produire, selon ses actions passées :
1. **Mauvaise Fin 1 – Destruction totale** :  
    Le processus échoue, menant à l’anéantissement complet de l’environnement.
2. **Mauvaise Fin 2 – Corruption totale** :  
    Le joueur devient lui-même vecteur de la corruption, incapable de la contenir.
3. **Bonne Fin 1 – Remède** :  
    Le joueur parvient à développer un antidote ou une solution durable, purifiant partiellement ou totalement le monde.
#### Conditions de fin
Les fins sont **déterminées dynamiquement** à partir de plusieurs facteurs :
- Le **nombre d’ennemis tués** selon leur **faction**
- Les **éléments narratifs** découverts ou manqués
- La manière dont **l’arbre de compétences** a été complété (orientation, équilibre, spécialisation…)
## Style
Le jeu adopte une **vue isométrique** pour l’exploration et les phases d’action principales. Toutefois, une transition s’opère lorsque le joueur est dans la base, où la perspective passe en **vue 2D de profil**, offrant une rupture visuelle claire et marquant le changement de rythme.

L’univers du jeu se situe dans une époque **contemporaine**, parallèle à la nôtre, mais profondément altérée par une **extinction de masse** et la **chute brutale de la civilisation**. Le monde est désormais dominé par le chaos, la ruine et des formes de vie déformées par une corruption inexpliquée.

---
#### Ambiance Bio-Mécanique & Corruption
Des éléments **bio-mécaniques** seront omniprésents dans les environnements et les ennemis, mais ils ne seront **pas issus d’une volonté de progrès technologique**. Ils devront plutôt évoquer une **contamination organique** ou une **fusion forcée et contre-nature** entre chair et machine.

L’inspiration esthétique tire principalement de :
- **[HR giger](https://www.google.com/search?q=HR+Giger&sca_esv=5ed3572dacaed608&udm=2&biw=1920&bih=945&sxsrf=AE3TifN-Ws0A3CfMi0YO-Kgc_ovEBliXIg%3A1749046110893&ei=XlNAaOKkNpGdkdUPkKSniQs&ved=0ahUKEwjiy4rB-NeNAxWRTqQEHRDSKbEQ4dUDCBE&uact=5&oq=HR+Giger&gs_lp=EgNpbWciCEhSIEdpZ2VyMggQABiABBixAzIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABEigHlCDD1jfHXADeACQAQCYAUOgAeEDqgEBOLgBA8gBAPgBAZgCC6AChwTCAgYQABgHGB7CAgQQABgewgIGEAAYCBgewgIHECMYJxjJAsICCxAAGIAEGLEDGIMBwgIOEAAYgAQYsQMYgwEYigWYAwCIBgGSBwIxMaAHoSeyBwE4uAf6A8IHBTAuNy40yAch&sclient=img)** pour le côté organique, sombre et oppressant de la **bio-mécanique**
- **[HP lovecraft](https://www.ulthar.net/h.p.lovecraft/ses-creations/+/9c::le-bestiaire-lovecraftien.html)** pour l’aspect **cosmique, indicible et corrupteur** de l’environnement et de ses créatures

---
#### Palette & Contraste Visuel
La **palette de couleurs** sera volontairement **restreinte et terne**, reflétant la désolation du monde. Les tons dominants seront froids, grisâtres ou terreux.  
Des **accents de couleurs vives ou saturées** seront utilisés de façon **exceptionnelle**, notamment pour :
- Mettre en valeur certains **éléments narratifs**
- Souligner des **zones d’horreur ou de corruption intense**
- Créer un **choc visuel** lors d’événements importants

Cette sobriété chromatique contribuera à renforcer l’atmosphère lourde, oppressante, et à faire ressortir visuellement les éléments significatifs du récit.
## Histoire
![[Schema scenario V1.svg]]
### Prélude
Dans un monde à l’agonie, surpeuplé, ravagé par les maladies et l’épuisement des ressources, une branche de recherche scientifique devient cruciale : **le transhumanisme**. L’objectif ? Fusionner l’humain avec la machine pour transcender la biologie, éliminer les maladies et s’affranchir des limites naturelles.

Mais malgré son importance, le projet piétine. Les recherches n’aboutissent pas. Peu à peu, les laboratoires ferment, les budgets s’évaporent. Certains scientifiques brûlent leurs travaux. D'autres disparaissent mystérieusement ou mettent fin à leurs jours. Des rumeurs circulent dans les couloirs abandonnés des instituts.

C’est dans ce contexte que l’histoire débute. Le joueur incarne **un chercheur obstiné**, profondément impliqué dans ce domaine. Lorsque son propre laboratoire est dissous, il refuse d’abandonner. Contre l’avis de sa famille, il installe un laboratoire clandestin chez lui et poursuit ses recherches dans l’ombre.

Les mois passent. L'isolement grandit. Le chercheur, convaincu de frôler la révélation, coupe tout contact avec l’extérieur. Seule une **présence étrange** semble encore l'accompagner : une voix, une silhouette... un être qui l’aide à progresser, mais qui **n'existe que dans son esprit** – une manifestation de sa **folie grandissante**.

C’est alors qu’un **manuscrit ancien** lui parvient. Sans explication. Sans nom d’expéditeur. Un ouvrage ésotérique, mêlant science oubliée et rites occultes, issu d’un culte voué à la machine et à l’anéantissement. Le chercheur ne s’interroge pas : il comprend. Ce texte détient la clé.

En adaptant ses découvertes à cette **science impie**, il parvient à créer un procédé de **fusion entre chair et métal**, un rituel appelé **“l’insufflation de vie”**.

Il ne lui manque qu’un test. Convaincu d’œuvrer pour le salut de l’humanité, il sacrifie sa propre femme et sa fille dans un rituel sanglant. Le résultat est une créature hybride, monstrueuse. Ce n’est plus un être humain. Mais pour lui, c’est une réussite.

Déconnecté de toute réalité, **consumé par sa vision**, il poursuit son travail, perfectionnant le rituel pour l’appliquer à l’échelle mondiale. Toute opposition devient une ressource : voisins curieux, policiers, collègues sceptiques... tous sont utilisés, leur mort servant à affiner l’insufflation.

Puis vient le jour fatidique. Retranché dans sa maison, assiégé par les forces de l’ordre, il déclenche le rituel à grande échelle.

Une **vague de corruption** engloutit le monde.

L’épicentre étant sa propre demeure, il subit l’explosion de puissance. **Il perd la mémoire, tombe dans le coma.**

À son réveil, le monde est en ruine. Son laboratoire est détruit. Il n’a aucun souvenir de son passé. Seules subsistent une **curiosité profonde** et une volonté sincère **d’aider l’humanité à survivre**… sans comprendre qu’il est à l’origine du cataclysme.

### Durant le jeu
Le joueur, amnésique, cherche à reconstruire les fragments de son passé. Mais le monde est désormais hostile :
- **Des cultistes** tentent de le sacrifier (en réalité, ils cherchent à s’approprier son savoir).
- **Des brigands**, survivants désespérés, veulent simplement piller ses ressources.
- **Une milice** bien équipée tente de l’éliminer par peur qu’il ne recommence.
- **Des créatures difformes**, conséquences directes de ses anciens rituels, errent dans les ruines.

### Corruption des souvenirs
À mesure que le joueur retrouve des fragments de souvenirs, ces derniers seront **déformés** selon ses choix dans l’**arbre de compétences**.  
Des **altérations physiques** pourront apparaître, symbolisant la tension entre **l’humain qu’il était** et **la créature qu’il pourrait devenir**.