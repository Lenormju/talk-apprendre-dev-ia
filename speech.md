# Discours détaillé

## Intro

### Page de titre

- Bonjour, bienvenue, et merci d'être venu pour une présentation de plus sur l'IA

### Page sponsors

- Merci aux sponsors qui rendent cet événement possible
- Je m'appelle Jonathan Gaffiot, je travaille à Kaizen Solutions, je suis développeur
  d'application complète de l'idée au maintien, et ces temps-ci je travaille à mettre
  de l'IA dans le système documentaire d'une grosse entreprise.
  Merci à Kaizen Solutions, l'ESN pour laquelle je travaille,
  qui m'envoie et m'a permis de prépaper cette conférence.
- Je suis Julien Lenormand...

## Dépassionnons

### C'est normal

- [Jo] Aujourd'hui, nous allons parler du développement logiciel à l'ère de l'IA,
  et par IA on veut dire LLM, génération de code, agent, GPT-5.2/Opus 4.5...
- [Ju] Et des jeunes qui font n'importe quoi avec l'IA
- [Jo] Et des jeunes qui font n'importe quoi tout court.
  Par définition, de tout temps, dans toutes les disciplines, les débutants sont nuls,
  IA ou pas ; et les vieux s'en plaignent.
- [Ju] Les jeunes sont nuls ? On l'était aussi.
  J'ai ...
- [Jo] J'ai fait un script Perl de 1000 lignes, dont 990 dans une boucle.
  Mon premier programme, en C++, s'arrêtait sans arrêt pour demander quoi faire à
  l'utilisateur. Je savais pas qu'on pouvait passer des arguments en ligne de commande.
  Et je foutais des pointeurs partout parce que je croyais que progresser c'était gérer
  sa mémoire dynamiquement et manuellement.
- [Ju]...
- [Jo] La première chose que j'ai fait sur ma première application en Python,
  c'est écrire une lib de logging. Histoire de réinventer encore la roue carrée.
- [Ju]...
- [Jo] J'ai mis du code en prod sans le moindre test, et on perdu des semaines de prod
  sur une centrale solaire (mais c'était pas moi).
  Les jeunes font des conneries parce qu'ils sont jeunes et savent pas, pas à cause de
  l'IA.
  En plus, le dev est une discipline très jeune, il y a des gens plus vieux que la
  discipline !
- [Ju] Oui mais l'IA va tout chambouler !
- [Jo] Mais le dev a toujours été une succession de révolution à intervalle
  hyper-fréquents :
  langage informatique, carte perforée, terminal, code structuré, OOP, Google, langage
  haut-niveau, Git, npm, Web, Docker & k8s, Cloud, ChatGPT, Claude Code + Sonnet 3.5...
  Ça bouge beaucoup, tout le temps, et les jeunes ont une facilité à adopter les
  nouvelles pratiques alors que les anciens sont plus réticents.
- [Ju] Mais les jeunes font n'importe quoi avec le vibe coding, ça va trop vite !
- [Jo] Et les vieux se plaignent que les jeunes en ont pas chiés autant qu'eux, et
  qu'ils arrivent à faire en 2 jours ce qui leur prenait 2 mois, avec la dernière techno
  qui facilite la vie.
- [Ju] Mais ils savent pas faire un algo de tri potable, gérer la mémoire, ce qu'est une
  socket. Ils savent pas se passer de ChatGPT.
- [Jo] Et c'est normal, ils font des apps mobiles et du Cloud maintenant. L'informatique
  a grandi, explosé même, le focus de notre génération n'est plus celui de la leur, et
  on peut pas demander à tous les dev de connaitre toute l'histoire de l'informatique.
  Oui les jeunes auront pas les mêmes difficultés que nous, encore heureux ! Sinon à
  quoi sert tout ce qu'on a codé ? Ils auront les problèmes de leur temps.
  Donc les vieux, vous vous sentez peut être bousculés par l'IA, mais vous avez vous
  mêmes bousculés vos prédécesseurs, et dans notre industrie la bousculade est
  récurrente.
  Donc en fait tout est normal. Ou habituel. Suprenant, bousculant mais comme d'hab'.

### On a le temps et de la place

- [Ju] Mais j'aime bien coder moi. Là c'est l'IA qui écrit tout le code.
- [Jo] L'IA va pas se répandre si vite que ça.
  Il faut changer les habitudes, former les développeurs, c'est long
  Il faut aussi changer les organisations, régler les problèmes de cybersec et
  confidentialité des données, donner confiances aux manageurs et donneurs d'ordre.
  En plus, y'a des secteurs hyper-conservateurs et allergiques au changement :
  nucléaire, banque, transport...
  Et pis, honnêtement, entre nous, qui n'a jamais fait une mission ou un job avec un
  chef persuadé que le changement est trop risqué ? Que le code tombé en marche ne doit
  plus être touché ? D'ici à mettre de l'IA dedans...
- [Ju] Donc y'a de la place et du boulot pour les crafteurs et les poètes du code ?
- [Jo] Et y'en aura demain, et encore dans 10 ans
- [Ju] Mais sans doute moins
- [Jo] Oui parce qu'avec la pression des concurrents, pas mal de boites vont quand même
  devoir bouger. Mais y'a le temps, et y'a de la place, pour ceux qui n'aiment pas l'IA.

### L'heure du choix

- [Ju] Donc en fait il ne se passe rien
- [Jo] Si, comme tous les 5 ans à la louche, le dev change, et il va falloir choisir
  y aller ou pas ? Craft ou agent IA ? On saute sur le tigre ou pas ?
  On a tous une question à se poser : est-ce que pour moi le but est dans l'écriture
  du code ? Ou dans le système final ? Le code est-il une fin en soi, ou un moyen ?
- [Ju] Nous, on a pas d'avis. Vous faites ce que vous voulez, et comme on a dit,
  y'a le temps et la place.
- [Jo] On n'est pas là pour juger, juste présenter notre vision de la situation, et
  on vous souhaite le meilleur à tous, quelque soit votre pratique.
- [Ju] Je suis pas en avance, et pas (encore) convaincu par les agents, les skills...

## La mutation du métier

- [Jo] Par contre, maintenant, on va parler pour ceux qui veulent coder avec l'IA
  Leur métier change. Moins d'écriture de code, plus de gestion d'agent IA, le rôle
  du dev prend de la hauteur
- [Ju] Mais si on écrit plus de code, on fait que relire le code de l'IA ?
- [Jo] On va être toujours plus développeur de solution, moins pisseur de code. On va
  résoudre le problème, pas seulement mettre dans l'ordi ce que le client a en tête.
- [Ju] Donc y'a plus de rôle de simple implémentation ? On commence directement plus
  haut ?
- [Jo] Oui, on a moins besoin de compétence au raz du code, on se recentre sur
  l'ingéniérie haut-niveau :
  + s'approprier le besoin
  + imaginer la solution
  + architecturer, identifier les technos
  + superviser l'implémentation, les tests
  + intégrer tout ça et mettre en prod
- [Ju] Donc des compétences larges : langage, écosystème, technos logicielles, archi,
  test, CI, déploiement, Cloud ?
- [Jo] Oui et la capacité à trouver des solutions techniques, les évaluer, faire des
  choix et valider tout ça avec des tests.
- [Ju] De l'ingéniérie, mais à la vitesse de l'IA.
- [Jo] Oui, on va sortir des POC en quelques jours, tester plusieurs solutions...
- [Ju] Cool j'ai plus besoin de coder alors.
- [Jo] Avec un gros avertissement tout de même : vous êtes responsable du code livré,
  pour le meilleur et pour le pire, les félicitations comme l'engueulade.
  Il faut faire sien le code généré, l'endosser, par la relecture, le test,
  et en posant des questions à l'IA tant qu'on a doute, tant qu'on a pas tout compris.
- [Ju] Challenger le code et prouvé que ça marche
- [Jo] Oui, et on va pas se mentir : y'a beaucoup de code legacy en circulation, pas
  challenger, pas vraiment testé... On va pas forcément y perdre avec l'IA.
- [Ju] Et les devs commencent à mordre sur le boulot des PO et PM alors
- [Jo] Oui, le dev va aller très vite, et les devs vont s'emparer du problème, même
  spécifique à l'organisation
- [Ju] Mais c'est pas évident tout ça. J'ai l'impression que c'est encore plus exigeant
  qu'avant.
- [Jo] C'est mon impression aussi. Il faut beaucoup de compétences transverses, savoir
  pas mal de chose, se tenir au courant dans une industrie qui va très vite...
- [Ju] Mais ceux qui suivent vont aller de plus en plus vite
- [Jo] Oui, ça va donner un avantage encore plus grands aux idées portées par des devs,
  aux startups, par rapport aux organisations avec des tonnes de comité et de validation

## La nouvelle posture des juniors

- [Ju] Alors qu'est-ce qu'on fait quand on débute ?
- [Jo] On surfe sur la mode et sur les nouveaux outils qui brillent évidemment, c'est là
  qu'est le boulot ! Plus prosaïquement, on lance Claude Code, on travaille avec lui
  sur un plan d'implémentation et de test, on lui fait écrire le code, on teste et
  on itère.
- [Ju] Ça ressemble à du vibe coding ça, et on sait que ça donne du mauvais code, pas
  facile à maintenir
- [Jo] Oui mais le code de débutant était déjà pas ouf et pas facile à maintenir avant.
  Là on a un outil qui permet au dev de challenger tout seul son propre code, de prendre
  du recul : accélérer la biblio,  générer des propositions,poser des questions,
  essayer plusieurs libs, faire des tests.
- [Ju] Du vibe engineering ?
- [Jo] C'est ça. Générer le code mais avec l'attitude d'un ingénieur, qui doute de tout
  tant qu'il a pas vu la preuve que ça marche et compris pourquoi.
- [Ju] Mais ils vont se planter quand même
- [Jo] Oui, ça fait partie de l'apprentissage. La plupart d'entre nous ont appris sur le
  tas, par essai et erreur, en faisant parfois de grosses bêtises. C'est long et
  difficile de devenir un bon dev.
- [Ju] Mais on apprend pas à coder en faisant ça
- [Jo] Non, on apprend à construire un projet entier et à le mettre en prod dans la
  foulée. Comme on a dit, il va rester plein de postes de crafteurs, au raz du code et
  de l'algo, qui travailleront comme avant. Pour des jeunes et des vieux. Simplement,
  la majorité de la nouvelle génération passe à autre chose, comme à chaque fois.
- [Ju] Mais si on fait générer tout le code, on aura pas la connaissance fine du code,
  comment on saura reconnaitre que l'IA a fait du bon code ou pas ?
- [Jo] Ça va prendre du temps à reconnaitre, à l'expérience, évidemment. Mais
  reconnaissons que le code généré est la plupart du temps très bon, et il s'améliore
  tous les 3 mois.
- [Ju] Donc on commence directement avec un agent ? Des agents ?
- [Jo] Oui, même un stagiaire est déjà un manageur d'IA. Avant on déléguait aux jeunes,
  maintenant aux IA. Et on apprend, on ouvre ses horizons, on explore la stack,
  et on explore tout le processus du code à la prod.
- [Ju] Et avec tout ça, les jeunes auront du boulot ?
- [Jo] C'est la question à 1000 milliards. On a moins besoin de jeunes pour le travail
  de base, mais on va coder encore plus maintenant. Tout un tas de projet pas assez
  prioritaires, plus ou moins pris en charge par du SaaS, vont pouvoir être développés.
  Et de nouveaux secteurs vont se mettre au code. Est-ce que ça va se compenser ?
  Aujourd'hui, on voit 10 à 15% d'embauche de jeunes dev en moins aux USA, mais les
  salaires ne baissent pas. Qualité plutôt que quantité ?

## Le nouveau rôle des seniors

- [Ju] Et qu'est-ce qu'on fait quand on est seniors et qu'on est passé à l'IA ?
- [Jo] Déjà, on va beaucoup plus vite et plus loin tout seul. Moins besoin de coacher
  l'équipe, moins de communication, fait gagner du temps en plus de l'IA. On devient
  vite aussi productif qu'une petite équipe sur la partie code.
- [Ju] Ah ! Donc on abandonne les jeunes !
- [Jo] Pas forcément, parce que le temps gagner sur le code ne se traduit pas
  directement en temps gagner sur le projet. On est toujours tributaire des retours
  clients, des validations, des réunions... Donc on a du temps.
- [Ju] Et qu'est-ce qu'on en fait ?
- [Jo] On fait sa biblio, on suit les technos et les pratiques, c'est encore plus
  important maintenant que l'informatique accélère encore.
  Et on enseigne aux jeunes, on prend le temps de leur apprendre les pratiques, la
  culture de l'ingéniérie, et de regarder leur code.
- [Ju] Passer du temps ensemble sur une feature ?
- [Jo] Oui, la formation initiale est le plus souvent famélique, et le dev s'apprend
  surtout sur le tas. Là, quand un jeune pense avoir finit son code, on challenge les
  pratiques, les tests, l'archi, les entrées/sorties, la cybersec, les libs, la doc,
  la CI... avant même de regarder vraiment le code.
- [Ju] Notre apprentissage passait par le code qu'on écrivait et StackOverflow, le leur
  passe par le code généré et ChatGPT.
- [Jo] C'est ça. Donc encadrer un débutant va continuer à prendre du temps, jusqu'à ce
  qu'il soit en mesure d'assumer la responsabilité de sa PR. Passer de "faire" à
  "comprendre pourquoi c'est fait comme ça", et s'assurer que le code fait un tout
  cohérent, intégré.
- [Ju] Donc plutôt que le code, je dois apprendre aux jeunes à quoi faire attention,
  évaluer les perfs, valider les entrées, tester...
- [Jo] Oui, on leur donne plus de petite tache facile, mais il faut s'attendre à passer
  beaucoup de temps sur la validation des premières taches, avec beaucoup de reprises.
  Il ne faut pas chercher à reproduire l'apprentissage par lequel on est passé.
- [Ju] Donc en attendant que le client réponde, je prends le temps de passer le flambeau
- [Jo] Et tu apprends la techno qui vient de sortir pour gagner de nouvelles compétences


## Le futur

- [Ju] Et l'IA bouge super vite, c'est encore valide l'année prochaine ce qu'on raconte ?
- [Jo] Bonne question. Aujourd'hui, l'IA peut pas assumer le role du prof ou du maitre
  pour le disciple, mais ça va venir. Plus l'IA secrétaire, pour les réunions, et ton
  agent de code va vite être allumé en permanence, regarder ton écran, faire des
  suggestions...
- [Ju] Le retour de Clippy !
- [Jo] Mais un clippy qui marche, espérons-le. Du coup la vision de la solution, la
  communication vont devenir encore plus importantes. Il faut s'approprier la vision
  client pour faire toute la solution.
- [Ju] Mais tous les clients ne sont pas prêts à travailler comme ça
- [Jo] Oui et là aussi ce n'est pas nouveau : tant de projets logiciels mal gérés,
  avec de gros retards et surcout, ou qui ne donnent rien à la fin, déjà avant l'IA.
  La diversité des pratiques va encore augmenter, la frustration des dev aussi.
  Et c'est là que je voulais vous parler de centaure.
- [Ju] De centaure ?
- [Jo] Oui, dans la mythologie, le centaure est un monstre surpuissant : fort et rapide
  comme le cheval, intelligent et agile comme l'humain.
- [Ju] Et c'est quoi le rapport avec l'IA ?
- [Jo] Le centaure, c'est l'homme augmenté, et c'est aussi une bonne métaphore pour la
  technologie : le centaure technologique, c'est moi dans ma voiture avec mon GPS.
- [Ju] Donc un dev avec une IA, c'est un centaure technologique.
- [Jo] Oui, on est plus fort, on va plus vite. Mais il a aussi le centaure inversé.
- [Ju] Alors là va falloir m'expliquer.
- [Jo] C'est un homme avec une tête de cheval, et c'est un sous-humain. Lent comme
  l'homme, bête comme le cheval, et déséquilibré.
- [Ju] Et y'a des centaures inversés technologiques ?
- [Jo] Oui, comme le livreur Amazon dans sa camionnette, asservi aux consignes de son
  GPS. Il est là uniquement pour faire ce qui est moins cher de faire à la main qu'avec
  un robot.
- [Ju] L'aliénation du travail. Le dev soumis à son IA.
- [Jo] Oui. Les boites d'IA sont déjà des monstres, et leurs copains ne sont pas des
  gentils, comme Amazon avec ses employés, ils sont là pour le profit.
- [Ju] Ils veulent des centaures inversés. Mais moi je veux être un centaures qui
  transforme problèmes et idées en solution à toute vitesse.
- [Jo] L'avenir de notre métier est entre les deux. Il y aura des employeurs qui veulent
  un pigeon qui fait que relire le code généré et qui preine la responsabilité si l'IA
  introduit une faille ou un bug. Et d'autres qui vont sauter sur tous les marchés pas
  encore informatisés, en prenant de vitesse les acteurs existants.
  Et entre les deux toutes les formules pour monnayer nos compétences.
