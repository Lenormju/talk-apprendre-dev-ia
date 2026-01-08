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
- [Jo] La première chose que j'ai fait sur ma première application en Python, c'est écrire
  une lib de logging. Histoire de réinventer encore la roue carrée.
- [Ju]...
- [Jo] J'ai mis du code en prod sans le moindre test, et on perdu des semaines de prod sur
  une centrale solaire (mais c'était pas moi).
  Les jeunes font des conneries parce qu'ils sont jeunes et savent pas, pas à cause de
  l'IA.
  En plus, le dev est une discipline très jeune, il y a des gens plus vieux que la
  discipline !
- [Ju] Oui mais l'IA va tout chambouler !
- [Jo] Mais le dev a toujours été une succession de révolution à intervalle hyper-fréquents :
  langage informatique, carte perforée, terminal, code structuré, OOP, Google, langage
  haut-niveau, Git, npm, Web, Docker & k8s, Cloud, ChatGPT, Claude Code + Sonnet 3.5...
  Ça bouge beaucoup, tout le temps, et les jeunes ont une facilité à adopter les
  nouvelles pratiques alors que les anciens sont plus réticents.
- [Ju] Mais les jeunes font n'importe quoi avec le vibe coding, ça va trop vite !
- [Jo] Et les vieux se plaignent que les jeunes en ont pas chiés autant qu'eux, et
  qu'ils arrivent à faire en 2 jours ce qui leur prenait 2 mois, avec la dernière techno
  qui facilite la vie.
- [Ju] Mais ils savent pas gérer la mémoire. Ils savent pas ce qu'est une socket.
  Ils savent pas se passer de Stack Overflow.
- [Jo] Et c'est normal, ils font des apps mobiles maintenant.
  Oui les jeunes auront pas les mêmes difficultés que nous, encore heureux ! Sinon à
  quoi sert tout ce qu'on a codé ? Ils auront les problèmes de leur temps.
  Donc les vieux, vous vous sentez peut être bousculés par l'IA, mais vous avez vous
  mêmes bousculés vos prédécesseurs, et dans notre industrie la bousculade est récurrente.
  Donc en fait tout est normal. Suprenant, bousculant mais normal.

### On a le temps et de la place

- [Ju] Mais j'aime bien coder moi. Là c'est l'IA qui écrit tout le code.
- [Jo] L'IA va pas se répandre si vite que ça.
  Il faut changer les habitudes, former les développeurs, c'est long
  Il faut aussi changer les organisations, régler les problèmes de cybersec et
  confidentialité des données, donner confiances aux manageurs et donneurs d'ordre
  En plus, y'a des secteurs hyper-conservateurs et allergiques au changement :
  nucléaire, banque, transport...
  Et pis, honnêtement, entre nous, qui n'a jamais fait une mission ou un job avec un
  chef persuadé que le changement est trop risqué ? Que le code tombé en marche ne doit
  plus être touché ? D'ici à mettre de l'IA dedans...
- [Ju] Donc y'a de la place et du boulot pour les crafteurs et les poètes du code ?
- [Jo] Et y'en aura demain, et encore dans 10 ans
- [Ju] Mais sans doute moins
- [Jo] Oui parce qu'avec la pression des concurrents, pas mal de boites vont quand même
  devoir bouger. Mais y'a le temps, et y'a de la place.

### L'heure du choix

- [Ju] Donc en fait il ne se passe rien
- [Jo] Si, comme tous les 5 ans à la louche, le dev change, et il va falloir choisir
  y aller ou pas ? Craft ou agent IA ? On saute sur le tigre ou pas ?
  On a tous une question à se poser : est-ce que pour moi le but est dans l'écriture
  du code ? Ou dans le système final ? Le code est-il une fin en soi, ou un moyen ?
- [Ju] Nous, on a pas d'avis. Vous faites ce que vous voulez, et comme on a dit, y'a le temps
  et la place.
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
- [Jo] Oui, on a moins besoin de compétence au rat du code, on se recentre sur
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
- [Ju] de l'ingéniérie. Qui va vite, qui itère, avec des POC, du  80/20...
- [Jo] oui avec une particularité : vous êtes responsable du code livré, pour le meilleur
  et pour le pire. Il faut faire sien le code généré, l'endosser, par la relecture,
  le test, et en posant des questions à l'IA tant qu'on a doute, tant qu'on a pas tout
  compris.
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


## Le nouveau rôle des seniors


## Conclusion
