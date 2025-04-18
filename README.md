# Heritage
Party game qui mélange jeu de société et jeu vidéo en réalité virtuelle (VR) et réalité augmentée (AR), avec le cardboard Google.

Sur ce jeu, j'ai assuré la direction artistique: UI du jeu en 2D, character design, design des cartes et du cardboard, logo, communication.

J'ai aussi participé au game design et aux tests du jeu avec le public.

[center]![Heritage_logo_SD](https://github.com/user-attachments/assets/da46407b-75ec-4299-be1e-0f6937e1ad5b)[/center]

![Heritage_simulation_jeu](https://github.com/user-attachments/assets/92735d79-0df5-47cb-a299-4ee82e9f623e)

## L'équipe
Gwennaël Codet-Hache - chef de projet

Adrien Gilly - développeur

Natacha Lefèvre - directrice artistique

Samuel Lepoil - narrative designer

Dimitri Roziecki - technical artist 3D

## L'histoire
Tante Léonie était une inventrice aussi brillante que loufoque. Lors de son décès elle lègue en héritage sa plus grande invention : le Vériscope, un appareil qui permet de révéler la vérité quand on le porte. Elle a chargé son robot-majordome Edgar de retrouver ses proches, afin de léguer le Vériscope à son héritier ou héritière légitime. Et on aura besoin de l'utiliser quand de nombreux prétendants à l'héritage de Tante Léonie vont se présenter...

## Fonctionnement du jeu
Heritage est un jeu à identité cachée, inspiré de jeux comme le Loup-Garou et le Cluedo, et avec un gameplay asymétrique. Chaque joueur incarne un personnage qui doit récupérer l'héritage en éliminant les autres prétendants.

Le Vériscope est incarné par le cardboard de Google. Le jeu est constitué d'une appli mobile que l'on glisse dans le cardboard, et de cartes à jouer que l'on peut scanner grâce à la technique de réalité augmentée.

En début de partie, les joueurs choisissent la carte des personnages qu'ils vont incarner, et se voient décerner un rôle : Proche ou Imposteur. À tour de rôle, chaque joueur va regarder dans le cardboard et choisir 2 joueurs qu'il suspecte d'être des imposteurs. Il désigne aussi un assistant qui va montrer une lentille dont le Vériscope a besoin pour fonctionner. Mais l'assistant peut présenter une lentille immaculée ou corrompue, sans que le joueur qui a le cardboard ne le sache. Les joueurs ciblés présentent leur carte personnage qui est scannée par l'appli, et qui affiche des informations que seul le joueur qui a le cardboard peut voir. Le joueur partage ensuite ces informations, mais... il peut mentir...

À la fin de chaque tour, les joueurs ont un temps de discussion pour se convaincre les uns les autres de qui est imposteur et qui est proche. À la fin du compte à rebours, les joueurs pointent la personne qu'ils veulent voir hériter. La personne qui a le plus de voix hérite du Vériscope.

### Teaser
https://www.youtube.com/watch?v=k_hEsn8fNog

### Demo
https://www.youtube.com/watch?v=HIbteqx4pVA


## Direction artistique
Nous avons opté pour une direction artistique inspirée du style steampunk, dans un style bande dessinée.

### Design du carboard
Afin de rendre le Vériscope plus réel, nous avons décoré le cardboard Google comme une petite machine steampunk.



### Cartes à jouer et réalité augmentée (AR)
Les cartes à jouer représentent les personnages, qui peuvent être scannées. Nous avons utilisé VuMark de Vuforia pour la réalité augmentée. Cela nous a permis de pouvoir scanner les illustrations des cartes sans devoir passer par des QR codes. En revanche, il est nécessaire que les illustrations contiennent des formes et des contrastes bien distincts pour que le logiciel les repère. J'ai adapté la direction artistique du jeu en fonction de cette contrainte.
