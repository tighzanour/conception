# L'immitateur

Ce site présente la faisabilité d'un *concept d'expérience multimédia* présenté dans le cours *582-501MO Conception d'une expérience multimédia* au collège Montmorency enseigné par Thomas O Fredericks.

## Équipe

- Nour : Programation
- Rada : Technique
- Iryna : Esthétique
- Bradley : Programation

## Résumé du projet
un jeu d’arcade multijoueur où quatre soldats doivent s’échapper d’une forêt labyrinthique en communiquant par radio, tout en découvrant lequel d’entre eux est un imposteur qui cherche à les éliminer et à saboter leur extraction. 

## Le parcours de l'interacteur
Lorsque le joueur arrive devant l'installation il voit 4 écrans disposés l'un devant l'autre de façon à ce que les joueurs ne voient qu'un écran à la fois lorsqu'ils jouent. Les joueurs sont invités à se placer devant un écran et avoir en main leur manette. Devant le menu du jeu, ils doivent appuyer sur un bouton de la manette afin de montrer qu'ils sont prêts à jouer. Lorsque qu'un joueur se met prêt, un compte à rebour se lance avant de commencer la partie (cela évite de toujours attendre qu'il y est 4 joueurs pour jouer). Une fois la partie lancée, les joueurs verront une animation qui montre le rôle qui leur sera attribué de façon aléatoire. Ensuite, chaque rôle aura une interface similaire mais avec quelques différences; 

- imitateur : sur l'écran, il voit sur la droite au coin une instruction pour chacun de ses boutons. Un bouton pour courrir, un autre pour attacker / tuer et un bouton timé par utilisation de sneak up on a player. Sur la main de son personnage, il voit une main tachée.
  
- cartographe :  sur l'écran, il voit sur la droite au coin une instruction pour chacun de ses boutons. Un bouton pour courrir, un bouton pour voir la carte en grand écran avec une durée d'usage limité et un bouton pour tracer un chemin sur son path temporaire d'une durée de 5 secondes avec 2 usages unique. Dans la main de son personnage, quand il appuie sur le bouton pour aggrandir la carte, la main fait une animation d'ouvrir la carte.
  
- radio-opérateur : sur l'écran, il voit sur la droite au coin une instruction pour chacun de ses boutons. Un bouton pour courrir, un bouton pour faire un appelle radio à l'helico et ses coordonner avec un usage limiter de 2 usages et un bouton pour obtenir une echo localisation de la position des personnage selon lui sur la radio, usage limité de 5 secondes. Dans la main du personnage il tient une radio militaire assez vielle, dessus est affocher une faible battery, un radio echo localisateur et les coordonner de l'helicoptere qui afficheront temporairement.
  
- porteur de charge : sur l'écran, il voit sur la droite au coin une instruction pour chacun de ses boutons. Un bouton pour courrir, un bouton pour jetter une grenade et un bouton pour placer une mine, la grenade et la mine ont un chiffre ui placer qui montre la quantité qui est de 1. Dans la main du porteur de charge, il voit une grenade. Quand il appuie sur un des bouttons de projection de l'arme, une animation de lance ainsi qu'un crosshair est visible lors de l'execution de l'action declencher.

Tous les joueurs ont une barre de stamina en bas au milieu de leur ecran qui indique l'usage maximum du bouton pour courrir. Ils voient aussi un compte à rebours centré en haut de l'écran.

Pendant la partie, les joueurs se retrouvent séparés virtuellement dans un environnement sombre. Lorsqu'une partie se termine, les joueurs voient un résumé de la partie (détails comme leaderboard, scores, survivants, gagnants). 

Deux boutons seront disponibles dans le UI à ce moment; ''Menu'' et ''Rejouer''. 



## Comment le projet s'adapte pour un à plusieurs interacteurs
Par rapport à une personne, il est possible qu'il y ait un joueur humain, mais que le reste soit des bots. L'aspect communautaire restera possible.

## Pourquoi ce projet est original ?
L'originalité vient beaucoup de l'esthétique, l'idée est inspirée des jeux de chase, mais ce projet encourage les joueurs à communiquer entre eux pour s'entraider plutôt qu'un jeu classique où chacun doit se sauver par lui-même. Les éléments de rôles enrichissent l'expérience et renforcent la communication. Il y a un aspect solo de la part du joueur qui est le mimic, car il doit s'assurer de gagner par lui-même, mais il doit communiquer pour essayer de gagner la confiance des autres puisqu'ils doutent tous entre eux.
