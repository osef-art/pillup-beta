# KAPS. 💊
[TÉLÉCHARGER LE JEU](https://github.com/osef-art/play-kaps/raw/main/KAPS.apk) 📥👈🏾

yo, c'est adam.  
très fier de pouvoir vous montrer mon tout premier **jeu mobile** *"KAPS"*,
que j'ai codé et dessiné de A à Z avec [Unity](https://unity.com/). j'ai commencé à taffer
dessus fin juin 2022, depuis j'ai pas arrêté de poncer le truc, 7j/7, comme si
les gens allaient le télécharger tsais 🤡  

**j'explique le principe:** c'est un jeu à la *'Dr. Mario'* pour ceux qui ont la ref.pour ceux
qui voient pas, disons que ça ressemble un peu à Tetris. des pilules 💊 vont tomber dans une
grille truffée de microbes 👾. le but est de faire des combinaisons (des *matchs*) de la même
couleur pour virer tous les microbes de la grille façon Pfizer. ✨  
ça a l'air assez chill dit comme ça. sauf que les pilules **accélèrent** ⏳ au fur et à mesure,
les grilles deviennent de plus en plus **chargées** en microbes, y'en a qui vont commencer à
avoir des **pouvoir spéciaux** 💥, sans parler des **sidekicks** 🤝 qui t'aideront à travers 
les niveaux et qui eux aussi possèdent chacun leur propre **pouvoir** 🧪, je te cache pas
que le résultat est assez fun. bourré de bugs, mais fun. 

[clip]

⚠ il s'agit d'une **version bêta** du jeu, c'est à dire qu'il y a pas mal de trucs qui manquent, 
de trucs qui buggent un peu, de trucs temporaires qui vont être remplacés par des truc mieux,
du coup soyez pas surpris si parfois y'a des comportements bizarres. 😬  
*(ah oui et ceux qui sont sur iOS.... bon au moins vous avez la santé* 🤡)

bon il est probable que je parle beaucoup, du coup je te propose un petit menu
avec toutes les infos sur le jeu dont j'aimerais faire part. clique sur celle(s) qui t'intéresse

[📱 EH COMMENT ON TÉLÉCHARGE LE JEU ??](#lancer-le-jeu-)  
[🎮 EH COMMENT ON JOUE ??????](#comment-jouer-)  
[📜 EH C'EST QUOI LES RÈGLES (j'arrête)](#rgles-du-jeu-)  
~  
[🚨 DERNIÈRES UPDATES](#)  
[👨🏾‍💻 CE SUR QUOI JE TAF EN CE MOMENT](#)  
[🎯 LES IDÉES / OBJECTIFS SUR CE PROJET](#)  
[💀 BUGS CONNUS (donc venez pas me harceler)](#)  
~  
[🤝 LES SIDEKICKS](#sidekicks-)  
[👾 LES MICROBES](#bactries-)  
[💊 PILULES SPÉCIALES](#glules-spciales-)   



## LANCER LE JEU 📱
Si tu es sur Android, clique vite 
👉🏾 [ICI](https://github.com/osef-art/play-kaps/raw/main/KAPS.apk) 👈🏾 !! 
Ca va direct télécharger une `.apk` te permettant d'installer le jeu sur ton tel.  
Si tu es sur iPhone, tu pourras toujours regarder tes potes sur Android s'amuser 🙏🏾  
Si tu es sur un ordi, j'ai aucune idée de ce que tu fous là.


## COMMENT JOUER 🎮
*(si tu n'as pas lu l'intro ou [les règles](#rgles-du-jeu-), il est possible que tu ne comprennes
pas grand chose je t'avoue* 💀)  
Pour **bouger** les pilules, sélectionne-les avec ton doigt et déplace-les librement dans la grille.  
Tu peux aussi les déplacer depuis n'importe quel endroit de l'écran avec le **joystick**. Tu peux 
déplacer la pilule vers la **gauche** ⬅, la **droite** ➡, et le bas ⬇.  
Pour faire **pivoter** une pilule, **tape** 👆 dessus, ou sur n'importe quel endroit de l'écran.  
💨 MOVE STYLÉ: tu peux **swipe vers le bas** pour faire **tomber** la pilule super vite. Ca rapporte 
des points supplémentaires donc hésite pas. 😏  

Si le joystick ou le swipe te gênent, tu peux les désactiver à tout moment dans les **paramètres**.
Tu peux même changer le sens dans lequel tourne la pilule par défaut. Si ça c'est pas magnifique.

Très important aussi, quand tu combines des pilules et qu'elles se cassent, tu peux aussi bouger les
**fragments** des pilules. C'est un peu compliqué parce qu'elles sont assez rapides, mais c'est
archi rentable.


## RÈGLES DU JEU 📜

*(je vais bientôt rajouter un **tuto** dans le jeu détaillant tout ce que je vais raconter ici,
mais lis quand même on sait jamais.)*

Chaque niveau est une **grille** dont certaines cases sont occupées par des **microbes** colorés.  
Au fur et à mesure, des **pilules** colorées vont tomber dans la grille et s'empiler. Le gameplay
consiste à réaliser des **combinaisons** de **4 objets** de la **même couleur** pour détruire ces
4 objets. On appelle ça un **match-4**. (on appelle pas du tout ça un match4 mais c'est moins 
long à écrire)  

Quand les microbes se retrouvent dans des *matchs*, ils sont **éradiqués**. 
Le niveau est complété lorsqu'on a viré **tous les microbes** de la grille. J'aurais peut-être
du appeler le jeu Astrazenekaps. Attends je l'ai dit à voix haute ?  

Le jeu aurait pu s'arrêter là, mais j'ai rajouté pas mal de **mécaniques** rendant le concept plus
**challengeant** (je hais ce mot):

  - Les microbes vont développer des **pouvoirs spéciaux**, y'en a qui pourront se **multiplient**,
d'autres**supriment** des pilules de la grille, certains nécessiteront **plusieurs coups** pour être
éradiqués, bref leurs <u>effets</u> sont détaillés dans la liste des [microbes](#bactries-). 👾  
Plus il y aura de microbes spéciaux, plus il deviendra nécessaire d'élaborer des petites **stratégies**
pour compléter un niveau, genre supprimer tels microbes en priorité, ne pas poser de pilules à
proximité de certains, etc. Mais la vraie **force** du jeu réside dans une mécanique bien plus
intéressante:
  - Les **SIDEKICKS** 🤝. Ce sont des *'principes actifs'* qui pourront t'aider en cours de partie.
Chaque sidekick a sa propre **compétence**, qui pourra être déclenchée **plusieurs fois** pendant le
niveau. Certains **éradiquent** des microbes, d'autres suppriment des **lignes**, des **colonnes**
et autres **motifs**, certains génèrent des **pilules spéciales**, etc. On peut en choisir jusqu'à
**2** par partie, et certaines  équipes possèdent une **synergie** unique.
Chaque sidekick possède une **jauge de mana**, vide au début de la partie. Lorsqu'<u>un objet de la
couleur du sidekick</u> est détruit, il **remplit** sa jauge de 1. Quand la jauge est pleine, le
sidekick est **prêt**, et sa compétence peut être **déclenchée** par le joueur. ⚡ La jauge se vide
à chaque utilisation de la compétence.  
Certains sidekicks sont **passifs** et se déclenchent **automatiquement** après un certain nombre de
**tours**.

La partie est perdue quand la pile de pilules atteint <u>le haut de la grille</u>.  
Attention, le jeu devient de plus en plus **rapide** au fur et à mesure de la partie.

#### MÉCANIQUES AVANCÉES 🧠

- 📥 Le bouton **"HOLD"** sert à **conserver** une capsule dans l'inventaire pour pouvoir la
**ressortir** au moment venu. Elle est échangée avec celle déjà présente dans la grille. Il y a des
chances que la mécanique devienne payante, plus j'y réfléchit et plus je la trouve ultra cheatée.
- Lorsque qu'une pilule se sépare ou tombe, on peut **la bouger** ou **bouger ses fragments** afin
de les déposer ailleurs. Ca peut être très utile pour perpétuer un combo ou juste réaménager la grille.
- ⬇ On a vu qu'on pouvait swipe vers le bas pour faire **tomber** une pilule.  
Ce move génère des **points supplémentaires** et a une faible chance de libérer de la **mana**.
- 🎆 Réaliser des ***match-5***, des ***match-6*** ou + génère de la mana et des points supplémentaires.  
Aussi, ces *matchs* font plus de **dégâts** aux microbes qui ont une barre de vie.
- 🌡 Enchaîner plusieurs *matchs* d'affilée démarre un **combo**. Plus il est élevé, plus il a de chances
de générer de la mana supplémentaires à chaque match.
- ⏹ Il est possible de *matcher* des lignes et des colonnes, mais aussi des **carrés 3x3**.  
C'est très chaud à réaliser, mais encore une fois, c'est particulièrement **récompensant** en terme
de mana, de dégâts et de score.

