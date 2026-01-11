<!--
Actions :
* quelques idées d'images @LESDEUX
* trame de ce qu'on dit @JONATHAN
* mise en scène (papy et junior ?), caustique ? @LESDEUX
* reformuler "on a le temps et la place" ?
-->

<style>
.reveal section[data-background-image] h1:not(:empty) {
  background: rgba(0, 0, 0, 0.6);
  padding: 20px 40px;
  border-radius: 10px;
  display: inline-block;
  color: AliceBlue;
}
</style>

<!-- .slide: data-background-image="./sgalagaev--5iSCtrJX5o-unsplash.jpg" -->
# Apprendre et enseigner le dev à l'ère de l'IA

---

<!-- .slide: data-background-image="./Slide Sponsor SnowCamp 2026 - 16.9.pptx.svg" -->

-v-

## Présentation

<style>
 .column {
  float: left;
  width: 50%;
}
</style>


<div class="row">
<div class="column">

Julien Lenormand

<img src="./julien_lenormand_logo.png" alt="" width="786" style="margin-top: 200px" />

</div>
<div class="column">

Jonathan Gaffiot

<img src="./logo-kaizen.png" alt="" width="567" />

</div>
</div>

Notes:

---

<!-- .slide: data-background-image="./sgalagaev--5iSCtrJX5o-unsplash.jpg" -->
# 1. Dépassionnons l'informatique

Notes:

anecdotes de nos erreurs grossières à nos débuts
- cf post de bitecode sur ses premières erreurs, "ça va bien se passer" https://www.bitecode.dev/p/the-kids-are-alright
- Julien : ne comprend rien à Git, et galère à contribuer solo sur un projet pas évident

perspective :
- le dev a toujours été une succession de révolution à intervalle hyper-fréquents
- liste de milestone : langage informatique, carte perforée, terminal, code structuré,
  Web, OOP, Docker & k8s, Cloud, ChatGPT, Claude Code + Sonnet 3.5
- facilité des jeunes à adopter les nouvelles pratiques, réticence pour les anciens (mon exemple), courbe d'adoption
- vitesse de diffusion limitée par les changements d'habitude et d'organisation
- les clients comprenaient déjà rien avant, ça va pas changer avec l'IA
- on continue toujours d'empiler des couches les unes sur les autres, et de faire des schémas avec des patates
- pas la première panique qu'on va être remplacés : Model-based code generation (UML), India, Stack overflow copy-pasting, Low-code/no-code, ...

de la place pour tous :
- encore du boulot aujourd'hui en FORTRAN, Cobol, C, et pour des décénnies
- des secteurs hyper-conservateurs et allergiques au changement : nucléaire, banque, transport...
- y'a de la place et du boulot pour les crafteurs et les poètes du code, mais moins

Par contre y'a un choix à faire : craft ou agent IA ("on commence à chevaucher le tigre")
Sens trouvé dans l'écriture du code (code=fin), ou dans le système final (code=moyen) ?

Pas de jugement, juste notre perspective

On vous souhaite le meilleur à tous, quelque soit votre pratique
on n'est pas là pour juger, juste présenter notre vision de la situation
Julien n'est pas du tout en avance, et pas (encore) convaincu par les agents, les skills, ...

Mise en scène :

- échange d'anecdote de quand on était jeune et noob
- pro IA/contre IA ? jeune/vieux ?
  * "contre" avance les problèmes, "pour" met en perspective

-v-

## IA

<img src=anthropic.png width="200px">
<img src=deepseek.png width="200px">
<img src=gemini.webp width="200px">
<img src=mistral-ai.png width="200px">
<img src=openai.png width="200px">
<img src=qwen.png width="200px">

-v-

## Erreurs de jeunesse

-v-

## Révolutions informatiques

-v-

## Les jeunes de nos jours ...

-v-

## C'est normal

-v-

## La vitesse du changement

-v-

## Le temps et la place

-v-

## L'heure du choix

---

<!-- .slide: data-background-image="./sgalagaev--5iSCtrJX5o-unsplash.jpg" -->
# 2. La mutation du métier

Notes:

nouvelle orientation du métier de dev ? c'est quoi le nouveau métier ?
=> + haut niveau, solution ...

constat : le dev médiocre qui pissait du code, et des architectes/clients dans des tours d'ivoire, ne marchait déjà pas
Si l'IA peut remplacer les échelles du bas, on commence déjà à un plus haut niveau

l'IA sait générer du code, donc les codeurs vont disparaître :
Dev "pisseur de ligne" vs dev "solution"
Est-ce qu'on est payé pour écrire du code, ou résoudre des problèmes ?
From "writing lines of code" to "navigating systems towards value"
"Si c'est Copilot qui génère ton code, et moi qui le relit, tu sers à quoi ?" - Florian G.

moins besoin de compétences de code : l'expertise au niveau de la ligne de code perd de son importance
recentrage sur l'ingénierie haut-niveau : boucle au niveau du besoin, faire des choix, complètement assisté par IA
devenons des "développeurs de solutions", pas simples codeurs

processus d'ingénierie :
- appropriation du problème (pas qu'une collecte du besoin)
- comment imaginer une solution
- comment traduire ça en code qui marche : langage + écosystème moderne
  (dans le corpus d'entrainement de l'IA),
  capacité à évaluer les différentes propositions et faire des choix,
  éviter les régressions, boucler rapidement, tests, CI, sécurité
  Pareto 80/20 pour faire des POC
- le code est un outil, c'est vous qui en êtes responsable, pour le pire et le meilleur
 (félicitations et engueulades), pas l'IA
  => faire sien le code, endosser le code (relecture, questionnement de l'IA)
  => challenger le code généré
  https://simonwillison.net/2025/Feb/3/a-computer-can-never-be-held-accountable/
  => prouver que ça marche : https://simonwillison.net/2025/Dec/18/code-proven-to-work/

l'IA rend le métier plus exigeant qu'avant (démultiplicateur)
- besoin d'une connaissance + transverse, moins spécialisée, T-shaped
- les champions s'en sortent mieux encore, les loosers n'ont plus aucun avantage

Dev assisté IA pour client qui cherche pas un codeur pour rentrer son idée dans l'ordinateur,
mais un (co-)solutionneur
Avec la vitesse de production de l'IA, les devs mettent maintenant la pression aux PO/PM, et vont donc devoir grignoter

ça + les limitations d'accès à l'IA vont faire du tri, le gap va s'élargir

nouvel avantage aux start-ups, aux idées portées par des devs


Source : https://github.com/Pierre-Loic/prez-Pyconfr-2025/blob/main/slides.md

Source : https://creatoreconomy.so/p/so-whats-going-to-happen-to-product-management-anyway

Quentin Adam parle de révolution industrielle de la prestation intellectuelle

la valeur des devs ne réside pas dans le code mais dans l'automatisation des processus métier

Mise en scène :
Dompter le tigre ? Dev avec/contre IA ? Un qui fait le dev, l'autre l'IA ?
Code review en ligne ?

-v-

## L'IA qui code, le dev qui décide

<img src="./Gemini_Generated_Image_control.png" class="r-stretch" alt="" />

-v-

## Le retour de l'ingénierie

<img src="./Gemini_Generated_Image_engineering.png" class="r-stretch" alt="" />

-v-

## L'IA est irresponsalbe, donc **vous** êtes responsable

![](./a-computer-can-never-be-held-accountable.jpg)

-v-

## La vitesse et le produit

<img src="./Gemini_Generated_Image_product.png" class="r-stretch" alt="" />

---

<!-- .slide: data-background-image="./sgalagaev--5iSCtrJX5o-unsplash.jpg" -->

# 3. La nouvelle posture des juniors

TODO image

Notes:
"vibe engineering" : du vibe coding, mais avec un recul d'ingénierie (regarder sous le capot)

ne pas trop accepter le code généré, le remettre en question, poser des questions
auto-code review
faire générer des plans, faire générer des propositions, accélérer sa biblio, choisir vite
faire des tests, faire générer des tests

code review importante, mais quand le code est prêt, compris, endossé (pas juste généré)

avant on déléguait à des gens, maintenant aux IA

un stagiaire est déjà manager de plusieurs IAs

challenger le code, rassembler et synthétiser l'info, apprendre plus vite

Comment apprendre si c'est l'IA qui code ?

Mise en scène :
jeune / vieux ?

-v-

## Vibe coding ?

<img src="./Gemini_Generated_Image_vibe_coding.png" class="r-stretch" alt="" />

-v-

## Vibe engineering !

<img src="./Gemini_Generated_Image_vibe_engineering.png" class="r-stretch" alt="" />

-v-

## Apprendre à faire des projets

<img src="./Gemini_Generated_Image_project.png" class="r-stretch" alt="" />

-v-

## L'interaction avec les agents

<img src="./Gemini_Generated_Image_agents.png" class="r-stretch" alt="" />

-v-

## Trouver du boulot ...

<img src="./Gemini_Generated_Image_hiring.png" class="r-stretch" alt="" />

---

<!-- .slide: data-background-image="./sgalagaev--5iSCtrJX5o-unsplash.jpg" -->
# 4. La nouvelle posture des seniors

TODO image

Notes:
focus sur les juniors !

suivre les évolutions technologiques et les pratiques !
auto-formation, biblio encore plus importantes qu'avant

jusque là ce métier est très essentiellement appris sur le tas
la formation initiale va changer très lentement et inégalement
va falloir que les vieux passent plus de temps avec les jeunes "sur le terrain"

enseignement par mentoring : le tech lead ne demande plus "code moi ce petit bout",
mais "cette grosse fonctionnalité", et on revoit ensemble
notre aprentissage passait par le code qu'on écrivait, leur apprentissage passera par
le code qu'ils auront généré

au tout début ça va prendre le même temps que manuellement, apprendre à utiliser l'IA,
à challenger, à comprendre, jusqu'à assumer la responsabilité de sa PR (comme avant)
transformation de "faire" à "comprendre pourquoi fait comme ça" et refaire le lien
(cohérence, bonne intégration)

apprendre aux jeunes à quoi faire attention, évaluer les perfs à la louche, s'assurer
que les entrées sont validées...
ne pas chercher à leur faire faire des trucs de base, petit, facile
ne pas chercher à leur faire reproduire votre parcours : ils vont tout de suite plus haut

faire l'enseignement au lieu de laisser produire de l'AI slop, prendre le temps d'enseigner
maitre/disciple, appel à la solidarité inter-générationnelle : en attendant que le client
vous réponde, prenez le temps de passer le flambeau
responsabilité renforcée sur le tech lead

Exercice de code review, à partir de code généré par IA

Quid de l'évolution de mes skills tech en tant que senior si l'IA code à ma place ?
C'est quoi un senior ? C'est quoi un plan de carrière ? Un profil en V T W ...

Mise en scène:
Scène de bureaux : deux vieux dev, comment tu fais toi ?

-v-

## Les avantages des IAs

<img src="./Gemini_Generated_Image_temps_libéré.png" class="r-stretch" alt="" />

-v-

## Passer le flambeau

<img src="./Gemini_Generated_Image_flambeau.png" class="r-stretch" alt="" />

---

<!-- .slide: data-background-image="./sgalagaev--5iSCtrJX5o-unsplash.jpg" -->
# 5. Le futur

TODO image

Notes:
ouverture

la partie "tutoring" des outils d'IA n'est pas encore assez mature

le futur ? une IA secrétaire + facilitatrice de réunion, coach professionnel, un tuteur
omniscient (surveille l'écran, le code, et fait des remarques pertinentes : le retour de Clippy !!)

la vision de la solution devient encore plus importante, rôle de PO/PM, prendre
la vision client, mais le rôle de PM conserve un peu de sens pour le côté commerce,
vision longue, management, coordination/centralisation, ...

question : quid de nous au milieu ?

centaure, centaure inversé, centaure technologique (moi dans ma voiture avec mon GPS),
centaure inversé technologique (le livreur asservi à son GPS)

faites attention à toujours rester des centaures aux commandes de l'IA, la sphère
économique (entreprises, fournisseurs d'IA) veut faire de vous des centaures inversés

tech feudalism

-v-

## Clippy 📎

<img src="./Gemini_Generated_Image_Clippy.png" class="r-stretch" alt="" />

-v-

## Centaure 

![](./centaur.png)

-v-

## Centaure inversé

![](./reverse_centaur.png)
-v-

## Centaure technologique

![](./GPS.jpg)
-v-

## Centaure inversé technologique

![](./delivery.png)
-v-

## IA is the new prolo ?

![](./charlie.webp)
-v-

---

<!-- .slide: data-background-image="./sgalagaev--5iSCtrJX5o-unsplash.jpg" -->
# Pour aller + loin

TODO

---

<!-- .slide: data-background-image="./sgalagaev--5iSCtrJX5o-unsplash.jpg" -->
# Crédits photos

- ChatGPT
- Google Gemini

---

<!-- .slide: data-background-image="./sgalagaev--5iSCtrJX5o-unsplash.jpg" -->
# Questions

<style>
 .column {
  float: left;
  width: 50%;
}
</style>


<div class="row">
<div class="column">

Slides

[https://github.com/Lenormju/talk-apprendre-dev-ia/](https://github.com/Lenormju/talk-apprendre-dev-ia/)

<img src="qr-code-slides.png" alt="" height="700px" />

</div>
<div class="column">

OpenFeedback

TODO lien feedback

TODO qr code feedback

</div>
</div>

Notes:

---

<style>
.reveal .small-text blockquote {
    font-size: 0.7em;
    text-align: left;
}
.reveal .small-text blockquote p {
    text-indent: 1.2em;
}
</style>

<!-- .slide: class="small-text" -->

### Abstract

> À l'ère de l'IA, les devs expérimentés qui ont l'habitude de piloter une équipe
> sautent facilement dans le train de l'IA, utilisant un ou plusieurs agents dernier cri
> pour se transformer en "équipe à soi tout seul" capable d'accélérer spectaculairement
> leur projet. De l'autre côté, les développeurs débutants, pas formés à l'usage de
> l'IA, se retrouvent critiqués pour accepter trop facilement le code approximatif
> généré par leur modèle et saturer le pipeline de revue de code. Alors, comment
> fait-on maintenant pour passer du débutant à l'expert ?
>
> Après avoir rappelé que l'IA ne se diffuse pas si vite que ça chez les industriels,
> que nous avons tous démarré en faisant des erreurs grossières, et que la nouvelle
> génération plongée dans l'IA dès le premier commit est mieux armée que l'ancienne pour
> dompter ce nouveau paradigme, nous présenterons la nouvelle orientation prise par le
> métier de développeur. Moins de lignes de code délicatement ciselées, et davantage de
> revue de code généré, le développeur doit migrer vers un rôle de plus haut niveau,
> plus exigeant, en insistant sur les fondamentaux de l’ingénierie :
> définir le problème, proposer des solutions, les challenger, choisir, implémenter,
> tester, recommencer, le tout assisté par l'IA à toutes les étapes.
>
> En parallèle, il devient encore plus important d'insister sur la vision globale des
> technos logicielles afin de naviguer dans un écosystème qui accélère encore,
> et sur la communication avec à la fois le commanditaire du code et ses utilisateurs,
> essentielle pour atteindre le but du projet.
>
> Enfin, certaines compétences perdent de l'importance, comme la connaissance exhaustive
> d'un langage ou d'une techno, et la spécialisation perd de l'importance face à la
> capacité de s'adapter et d'aller vite.
>
> Les experts et enseignants doivent donc insister davantage sur le processus, et moins
> sur le code. En parallèle, les débutants doivent apprendre à tester et valider chaque
> ligne, pas seulement en faisant générer un test à l'IA, mais en s'assurant que le test
> garanti effectivement ce qui est attendu dans la spec. Et tout le monde se recentrer
> sur notre cœur de métier : développeurs de solutions, pas simples codeurs.
