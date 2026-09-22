---
type:
  - Guide de rédaction
projet: Chantier 12
version: V6
date: 2026-09
statut: Support de préparation
---

> [!info] Objet de cette fiche
> Cette V6 consolide les cinq fiches précédentes consacrées au rapport intermédiaire de septembre 2026. Elle est conçue comme une spécification destinée à l'IA qui rédigera le rapport. Elle ne constitue ni le rapport lui-même, ni une doctrine validée, ni une source factuelle autonome.

# 0. Mode d'emploi pour l'IA

## Mission

Produire le rapport intermédiaire sur le **Chantier Souveraineté numérique**, à partir des sources du cerveau collectif et non à partir de connaissances supposées.

Le rapport doit répondre clairement à deux questions :

1. Où en est la réflexion et l'avancement du chantier à la date de référence ?
2. Quels premiers repères doivent être pris en considération dans la conception du TOM IT d'Atlas ?

Le rapport est un **point d'étape informatif**. Il doit éclairer la réflexion, pas demander une décision, imposer une doctrine, choisir un fournisseur ou annoncer un plan de migration.

## Livrable attendu

- Une synthèse autonome de **2 pages maximum**, rédigée après le corps du rapport.
- Un corps de rapport de **10 pages environ**, hors synthèse et annexes.
- Des annexes ciblées uniquement si elles augmentent la traçabilité ou évitent de surcharger le corps.
- Un document compréhensible par un décideur non spécialiste, mais suffisamment rigoureux pour des lecteurs IT, juridiques et achats.
- Des références précises aux sources utilisées, avec des [[wikilinks]] dans la version de travail Obsidian.

## Méthode obligatoire avant rédaction

1. Lire les sources prioritaires listées à la fin de cette fiche.
2. Établir une table de preuves avec, pour chaque affirmation importante : source, date, périmètre, statut, niveau de confiance et éventuelle validation requise.
3. Confirmer la date de référence du rapport et l'état d'avancement réel de chaque GT.
4. Résoudre les contradictions en revenant à la source la plus primaire et la plus récente.
5. Rédiger d'abord le corps du rapport, puis la synthèse.
6. Effectuer le contrôle qualité final de la section 8.

Si une information nécessaire manque, l'indiquer comme limite ou la retirer. Ne jamais combler une lacune par une supposition.

# 1. Cadrage éditorial

## Destinataires

**Destinataire prioritaire :** le groupe de travail IT d'Atlas, chargé de définir le Target Operating Model IT, ou TOM IT.

**Autres lecteurs :** sponsor du chantier, direction, cabinet de tutelle et collaborateurs de Paradigm.

À la première mention, écrire : **« Atlas, la nouvelle administration Bruxelles-Transversalité, anciennement appelée Pilier 1 »**. Utiliser ensuite « Atlas ».

## Objectifs du rapport

- Clarifier la notion de souveraineté numérique dans le contexte régional.
- Remplacer les réponses simplistes par une approche fondée sur les dépendances, leurs conséquences et les capacités de maîtrise.
- Présenter la démarche du chantier et son avancement réel.
- Partager les premiers constats, enseignements et limites du diagnostic.
- Mettre en évidence les implications potentielles pour le TOM IT d'Atlas, sans les présenter comme des décisions.
- Expliquer le travail restant d'ici décembre et ce qui devra se poursuivre au-delà.

## Hors périmètre

Le rapport ne doit pas :

- recommander une sortie générale de Microsoft ou des fournisseurs non européens ;
- affirmer que l'open source, le multi-cloud, l'hébergement local ou l'internalisation garantissent à eux seuls la souveraineté ;
- présenter une cartographie de Paradigm comme une cartographie complète de la Région ;
- annoncer une doctrine, une méthode d'évaluation ou des recommandations comme validées si elles ne le sont pas ;
- transformer un témoignage individuel en constat général ;
- présenter le rapport final de décembre comme l'achèvement du sujet ;
- construire un récit alarmiste, défensif ou promotionnel.

## Ton et style

- Factuel, sobre, pédagogique et coopératif.
- Direct, sans jargon inutile ni développement géopolitique disproportionné.
- Neutre à l'égard de Paradigm, des fournisseurs et d'Atlas.
- Orienté vers la continuité des services publics et les besoins des administrations.
- Peu d'exemples, mais des exemples solides, contextualisés et sourcés.
- Une idée principale par paragraphe et une conclusion explicite par section.
- Privilégier les tableaux comparatifs, schémas simples et encadrés pédagogiques.

# 2. Fil conducteur et messages structurants

## Fil conducteur

> La souveraineté numérique ne consiste pas à rechercher une indépendance totale ni à engager une rupture technologique générale. Elle consiste à connaître, maîtriser et arbitrer les dépendances numériques qui peuvent limiter la capacité de décision, d'action et de continuité des services publics. Le chantier construit progressivement les connaissances, les méthodes et les options qui permettront à la Région de décider où agir, comment et avec quels moyens.

Progression narrative : **comprendre le sujet, situer le chantier, présenter les premiers enseignements, éclairer le TOM IT d'Atlas, préparer la suite.**

## Messages à faire apparaître

1. **La souveraineté est une capacité de maîtrise, pas une autonomie absolue.** Une dépendance peut être acceptée si elle est connue, proportionnée et pilotée.
2. **Le risque dépend du contexte d'usage.** Il faut examiner ensemble la criticité du service, les données, les juridictions, les dépendances techniques, la concentration, les compétences, les coûts et la capacité de transition.
3. **Les compétences sont une condition transversale de souveraineté.** Les entretiens montrent qu'une externalisation sans documentation, transmission ni relève peut faire perdre la capacité de comprendre, piloter ou reprendre un service.
4. **La Région dispose déjà de points d'appui.** Infrastructures, datacenter régional, IrisNet, applications, compétences et capacités de mutualisation doivent être évalués comme des ressources, sans présumer qu'ils doivent être conservés à l'identique.
5. **Une première analyse du portefeuille fournisseurs doit encore être validée avant publication.** Même confirmée, elle indiquera une exposition, pas un niveau de risque : un comptage de fournisseurs ne renseigne ni les dépenses, ni la criticité, ni les usages, ni la réversibilité.
6. **La transformation Atlas est une occasion d'intégrer tôt la maîtrise des dépendances.** Elle peut aussi créer des verrouillages durables si l'architecture, l'identité, les achats et les compétences sont pensés séparément. Formuler ce point comme un enjeu à examiner, pas comme un reproche ou une urgence décisionnelle.
7. **Les expériences extérieures fournissent des principes, pas des recettes.** Progressivité, pilotes, standards ouverts, compétences, gouvernance et accompagnement des utilisateurs semblent plus robustes que les migrations généralisées ou idéologiques.
8. **Le chantier est une démarche progressive.** Septembre présente un état des lieux partiel. Décembre doit consolider l'analyse et proposer des suites réalistes sur un périmètre explicite, sans prétendre clore le sujet.

La citation « La souveraineté, c'est choisir ce que l'on accepte de ne pas contrôler » peut servir d'accroche uniquement si son attribution exacte au rapport Solvay ou à Michel Van Raemdonck est vérifiée et formulée sans ambiguïté.

# 3. Discipline factuelle

## Hiérarchie des sources

En cas de contradiction, appliquer cet ordre :

1. Source officielle ou document primaire daté.
2. Donnée interne confirmée par son propriétaire ou responsable.
3. Compte rendu d'entretien, présenté comme témoignage attribué.
4. Analyse d'un GT, avec son statut de validation.
5. Source secondaire documentée.
6. Fiches V1 à V5, uniquement comme plans de travail et listes de pistes.

Cette V6 organise le travail mais ne remplace pas les sources. Une affirmation répétée dans plusieurs versions n'est pas mieux établie si toutes les versions reprennent la même source non vérifiée.

## Statuts à distinguer

| Statut | Traitement rédactionnel |
| --- | --- |
| Fait documenté | Donner la source, la date, le périmètre et la limite utile. |
| Donnée interne à confirmer | Ne l'utiliser qu'après validation ou l'indiquer explicitement comme provisoire. |
| Témoignage | Attribuer le propos et ne pas le généraliser. Vérifier si sa diffusion est autorisée. |
| Constat du chantier validé | L'attribuer au chantier et préciser le périmètre. |
| Principe proposé | Employer « le chantier propose d'examiner » ou « nous proposons de retenir ». |
| Piste ou scénario | Présenter bénéfices, limites, conditions et informations manquantes. |
| Information non vérifiée | Vérifier avant publication ou retirer. |

## Règles de prudence

- Distinguer systématiquement **Paradigm**, **Atlas** et **la Région de Bruxelles-Capitale**.
- Distinguer ce qui existait avant le chantier de ce que le chantier a effectivement produit.
- Ne pas reprendre la formule « risque = dépendance x criticité x réversibilité » comme méthode validée. Une bonne réversibilité réduit normalement le risque et toute formule exige des échelles définies.
- Ne pas confondre criticité du service, niveau actuel de maîtrise et niveau de maîtrise requis.
- Ne pas qualifier un actif de « souverain » sur la seule base de sa localisation ou de sa propriété.
- Ne pas qualifier une solution de « souveraine » sans préciser les dimensions concernées et les limites.
- Traiter les entretiens marqués « confidentiel, usage interne » avec prudence. Agréger les enseignements par défaut ; demander validation avant de publier noms, chiffres sensibles ou situations identifiables.

# 4. Plan de rédaction recommandé

## Synthèse exécutive, 2 pages hors corps

La rédiger en dernier. Elle doit pouvoir être lue seule et contenir :

- l'objet du point d'étape et son destinataire prioritaire ;
- la définition opérationnelle de la souveraineté ;
- trois à cinq constats clés, accompagnés de leurs limites ;
- les principaux repères utiles au TOM IT d'Atlas ;
- le travail restant d'ici décembre ;
- une conclusion sans rubrique « décisions demandées ».

Ne pas transformer la synthèse en table des matières. Chaque phrase doit apporter un message ou un fait utile.

## 1. Comprendre la souveraineté numérique, environ 2 pages

### 1.1 Pourquoi le sujet mérite l'attention

Expliquer brièvement : concentration de certaines couches numériques, approfondissement des dépendances par le cloud, l'identité et l'IA, évolutions commerciales, incertitudes géopolitiques, législations extraterritoriales et évolution du cadre européen.

Sélectionner au maximum deux exemples bien documentés. Le cas Broadcom/VMware peut illustrer un risque économique et technique. Un cas régional de perte de compétences peut illustrer la perte de capacité d'action.

### 1.2 Définition et idées reçues

Définition de travail à utiliser sous réserve de confirmation collective :

> La souveraineté numérique désigne la capacité d'une organisation à connaître, maîtriser et arbitrer ses dépendances numériques afin de préserver sa capacité de décision, d'action et de continuité.

Expliquer qu'elle n'implique ni autarcie, ni rejet systématique des fournisseurs internationaux, ni internalisation totale.

Prévoir un encadré très court distinguant souveraineté, sécurité, résilience et conformité. Message clé : un service peut être sécurisé et conforme tout en étant très difficile à remplacer.

### 1.3 Les dimensions de la souveraineté

Présenter cinq dimensions liées entre elles :

| Dimension | Question principale | Exemple possible |
| --- | --- | --- |
| Données et droit | Qui contrôle les données et quelles juridictions s'appliquent ? | Hébergement européen par un fournisseur soumis à une législation extraterritoriale. |
| Technique | Pouvons-nous exploiter, faire évoluer ou déplacer le service ? | Formats, API, identité et services propriétaires. |
| Économique | Sommes-nous exposés à des conditions ou coûts difficiles à maîtriser ? | Évolution tarifaire après un changement de contrôle du fournisseur. |
| Approvisionnement et continuité | Pouvons-nous maintenir le service si un produit, un support ou un fournisseur disparaît ? | Brique critique sans alternative rapidement mobilisable. |
| Compétences et organisation | Savons-nous comprendre, piloter, maintenir et reprendre le service ? | Prestataire seul détenteur de la connaissance. |

Présenter les compétences comme une condition transversale. Leur ajout comme axe distinct dans l'outil du GT6 reste à confirmer.

### 1.4 Cadre européen

Présenter uniquement ce qui est utile au raisonnement régional. Pour le CADA, vérifier auprès de sources officielles à la date du rapport : nom exact, nature du texte, statut, calendrier, articles, niveaux éventuels et champ d'application.

La [[Note d’avis — Move2Cloud - CADA|note Move2Cloud/CADA]] est une analyse interne utile, pas une source suffisante pour établir le droit applicable. Distinguer explicitement ses recommandations des obligations juridiques en vigueur.

## 2. Le chantier : démarche et avancement, environ 1 page

Présenter sobrement :

- la finalité du chantier : identifier, comprendre, maîtriser et réduire les dépendances numériques critiques ;
- les quatre objectifs : état des lieux, sensibilisation, connexion à l'écosystème et projets concrets ;
- les sept GT et leur logique de flux, sans produire sept comptes rendus juxtaposés ;
- le cerveau collectif comme mémoire structurée et réversible du chantier ;
- la méthode : entretiens, benchmark, sources documentaires, analyses internes et outil d'évaluation en construction.

Ajouter un tableau d'avancement fondé sur des confirmations récentes :

| Objectif | Réalisé et apport obtenu | En cours ou restant | Source et statut |
| --- | --- | --- | --- |
| État des lieux | À confirmer | À confirmer | À compléter |
| Sensibilisation | À confirmer | À confirmer | À compléter |
| Écosystème | À confirmer | À confirmer | À compléter |
| Projets concrets | À confirmer | À confirmer | À compléter |

Ne pas présenter l'expérimentation d'une IA sur le cerveau collectif comme réalisée sans confirmation. Expliquer le lien entre ce rapport de septembre et les livrables annoncés fin août, sans conclure automatiquement à un retard.

## 3. Premiers enseignements régionaux, environ 2,5 pages

### 3.1 Une première lecture des fournisseurs de Paradigm

Les chiffres de 137 fournisseurs, 42 % de sièges aux États-Unis, 26 % dans l'Union européenne, 65 % pour le sous-ensemble cloud et 88 % pour l'IA ne sont présents, à ce stade, que dans les fiches de préparation retrouvées. Ne les publier qu'après obtention de l'analyse source et vérification des dénominateurs, catégories, doublons, date et périmètre.

Si les chiffres sont confirmés, afficher immédiatement leurs limites : comptage de fournisseurs, périmètre Paradigm, siège social comme indicateur incomplet, absence de pondération par dépenses, usages ou criticité.

### 3.2 Des dépendances de nature différente

Choisir deux ou trois cas suffisamment documentés, par exemple VMware/Broadcom, Microsoft 365 et une dépendance de compétences. Pour chacun, utiliser la même grille :

| Élément | Question |
| --- | --- |
| Service ou mission | Que permet la solution et à qui ? |
| Dépendance | Juridique, technique, économique, fournisseur, compétences ou combinaison ? |
| Conséquence possible | Quel impact concret sur la décision, l'action ou la continuité ? |
| Maîtrise actuelle | Quelles garanties, compétences et marges de manœuvre existent ? |
| Écart | Quel niveau de maîtrise serait nécessaire ? |
| Inconnues | Quelles preuves manquent ? |

### 3.3 Actifs et capacités régionales

Examiner le datacenter régional, IrisNet, les mutualisations, les compétences et les applications citées dans les sources. Ne pas en déduire automatiquement leur niveau de souveraineté ou leur organisation future.

Le contraste entre infrastructures régionales et couches logicielles ou cloud non européennes est une **hypothèse d'analyse utile**, mais Michel Van Raemdonck indique dans son entretien que la réflexion interne n'avait pas encore atteint ce niveau de granularité. Présenter ce contraste comme une question à instruire, pas comme un diagnostic unanimement partagé.

Les chiffres détaillés sur le DCR proviennent d'entretiens internes. Ils doivent être attribués, datés et validés avant diffusion.

### 3.4 Compétences et capacité de reprise

Présenter ce thème comme un enseignement fort des entretiens : transmission des connaissances, documentation, capacité à piloter un prestataire, relève des personnes clés et délai d'intégration.

Le ratio de 10 à 20 % de consultants est une pratique rapportée par Dominique Le Grelle, pas une norme ni une recommandation validée. Ne pas le généraliser sans analyse complémentaire.

### 3.5 L'IA : dépendances émergentes et options à instruire

Traiter brièvement l'IA comme un domaine où les usages, les fournisseurs et les dépendances évoluent rapidement. Distinguer clairement :

- les usages réellement observés et autorisés ;
- les dépendances créées par l'intégration aux suites bureautiques et aux données ;
- les enjeux de confidentialité, de compétences, de coûts et de réversibilité ;
- les options de modèles ouverts ou d'infrastructures mutualisées, qui restent à évaluer.

Le taux de fournisseurs américains associés à l'IA, le shadow IA et l'investissement estimé pour une infrastructure régionale sont des données ou témoignages à confirmer. Ne pas présenter une « IA souveraine » régionale comme un projet décidé ni réduire la souveraineté de l'IA à la localisation du modèle.

### 3.6 Limites du diagnostic

Rendre visibles : périmètre encore centré sur Paradigm, dépendances des autres administrations, liens entre applications, données et services, contrats et renouvellements, coûts et délais de sortie, compétences critiques, dépendances communes, alternatives disponibles et cas sans substitution crédible.

## 4. Enseignements du benchmark, environ 1,5 page

Retenir trois ou quatre expériences maximum, après vérification de leurs sources, dates, résultats, coûts et limites. Pour chaque exemple : contexte, objectif, action réellement engagée, résultat établi, difficulté rencontrée et enseignement possible pour Bruxelles.

Faire ressortir les tendances, sans affirmer une causalité non démontrée :

- progressivité et pilotes limités ;
- gouvernance claire et soutien durable ;
- compétences internes et transfert de connaissances ;
- standards ouverts et portabilité ;
- coopération et mutualisation ;
- accompagnement des utilisateurs.

Présenter aussi les échecs ou difficultés : approche « big bang », solution excessivement personnalisée, interopérabilité insuffisante, gestion du changement sous-estimée et migration sans soutien durable.

Le [[Field Study SOLVAY]] et son benchmark sont des matériaux de départ produits par des étudiants. Ils ne constituent pas des conclusions validées du chantier. Une annonce publique ne vaut pas preuve de réussite.

## 5. Repères pour le TOM IT d'Atlas, environ 2 pages

Cette partie est le point de bascule du rapport. Relier chaque repère à une dimension du TOM IT sans proposer d'organisation cible.

### Principes proposés

- Niveau de maîtrise proportionné aux conséquences pour les missions, les données et la continuité.
- Dépendance connue et assumée plutôt que dépendance subie.
- Maîtrise des dépendances dès la conception et l'achat.
- Réversibilité effective, appréciée sur le service complet.
- Préservation des compétences critiques et organisation de leur transmission.
- Visibilité transversale sur les concentrations à l'échelle du portefeuille.
- Suivi dans le temps des dépendances et des risques acceptés.

### Implications potentielles

| Dimension du TOM IT | Questions à intégrer |
| --- | --- |
| Architecture | Portabilité, standards ouverts, segmentation, identité, couplages, concentration et continuité. |
| Achats et contrats | Juridiction, sous-traitance, localisation et contrôle des données, export, assistance à la sortie, coûts et délais, transfert de connaissances. |
| Compétences | Connaissances à conserver, documentation, formation, articulation interne-externe et relève. |
| Gouvernance | Responsabilité de l'évaluation, actualisation des informations, acceptation et réexamen des risques. |
| Mutualisation | Capacités partageables, économies d'échelle, coopérations et risque de fragilité commune. |

### Cinq leviers opérationnels

| Levier | Apport possible | Condition ou vigilance |
| --- | --- | --- |
| Approche différenciée selon la criticité | Concentrer les efforts là où les conséquences sont les plus fortes. | Distinguer criticité, maîtrise actuelle et maîtrise requise ; tester la méthode du GT6. |
| Diversification | Réduire certaines concentrations et maintenir des options. | Plusieurs solutions peuvent dépendre du même cloud ou système d'identité ; éviter la complexité sans gain réel. |
| Marchés publics | Intégrer la maîtrise des dépendances avant la contractualisation. | Il faut savoir spécifier, évaluer et contrôler les exigences. |
| Compétences | Maintenir la capacité de comprendre, piloter, maintenir et reprendre. | Ne pas confondre souveraineté et internalisation totale. |
| Open source et communs | Favoriser auditabilité, adaptation, portabilité et coopération. | Vérifier gouvernance, maintenance, compétences, communauté et pluralité des prestataires. |

La réversibilité, la coopération et le suivi permanent sont des exigences transversales, pas des leviers séparés à traiter une seule fois.

Présenter les options de traitement d'une dépendance : renforcer les garanties, limiter les usages, réduire les couplages, préparer une sortie, remplacer la solution ou accepter explicitement un risque résiduel légalement admissible et régulièrement réexaminé.

La note Move2Cloud/CADA peut servir de cas d'application pour illustrer l'analyse préalable des risques, la segmentation des usages, la concentration autour de l'identité et la réversibilité contractuelle. Ne reprendre aucune obligation, aucun niveau d'assurance ni aucun délai sans vérification juridique officielle. Présenter les conclusions de la note comme des positions à instruire, pas comme le droit applicable ni comme une décision d'Atlas.

## 6. D'ici décembre, environ 0,5 à 1 page

Présenter un programme réaliste, à confirmer avec les GT :

- consolider les entretiens, l'analyse fournisseurs et le benchmark ;
- préciser le périmètre régional effectivement analysable ;
- confronter les analyses et formaliser convergences, désaccords et niveaux de validation ;
- construire avec le GT6 une méthode distinguant criticité, maîtrise actuelle, maîtrise nécessaire et preuves attendues ;
- tester la méthode sur quelques cas ;
- identifier les capacités organisationnelles pertinentes pour le TOM IT ;
- instruire quelques scénarios ou expérimentations avec bénéfices, conditions, coûts et limites ;
- proposer les modalités de poursuite après décembre.

Ne pas promettre une cartographie exhaustive de la Région, une méthode entièrement validée, l'évaluation de chaque solution ou un plan complet de migration.

## Conclusion, environ 0,5 page

Conclure sur trois idées :

- préserver une capacité de choix et de continuité, sans rechercher une autonomie absolue ;
- intégrer tôt la maîtrise des dépendances dans la réflexion sur le TOM IT d'Atlas ;
- consolider d'ici décembre des propositions réalistes et préparer une démarche durable au-delà du rapport final.

# 5. Données et affirmations sous condition

Ne pas publier les éléments suivants sans vérification ou validation :

| Élément | Risque actuel | Action requise |
| --- | --- | --- |
| 137 fournisseurs et pourcentages 42 %, 26 %, 65 %, 88 % | Source primaire absente du corpus consulté ; méthode inconnue. | Obtenir le fichier d'analyse, vérifier calculs, catégories, date et dénominateurs. |
| 80 % du marché européen du logiciel cloud et 265 milliards d'euros | Présent uniquement dans certaines versions du plan. | Retrouver l'étude Astérès/Cigref, vérifier périmètre et formulation exacte. |
| CADA, article 29, quatre niveaux et calendrier | La note interne peut être plus catégorique que le droit applicable. | Utiliser une source européenne officielle à jour. |
| Chiffres d'augmentation VMware chez Paradigm | Chiffres absents des sources consultées. | Obtenir les données achats ou contrats, sinon ne pas chiffrer. |
| Cour pénale internationale, cas SAP et cas iranien | Faits, portée ou transposabilité insuffisamment établis. | Sourcer précisément ou retirer. |
| Résultats chiffrés des migrations étrangères | Benchmark encore à vérifier. | Confirmer les résultats auprès de sources primaires et exposer les limites. |
| Chiffres du DCR, contrats, équipe, backup et coûts | Informations issues d'entretiens internes. | Faire valider chaque donnée par son propriétaire et vérifier la diffusion autorisée. |
| Shadow IA à 80 % et 125 licences Copilot | Témoignage interne, méthode de mesure non précisée. | Attribuer et qualifier, ou faire confirmer par une donnée interne. |
| Ratio de 10 à 20 % de consultants | Pratique individuelle présentée dans un entretien. | Ne pas en faire une règle générale sans validation. |
| « Compétences = première dépendance critique » | Formulation forte issue principalement d'entretiens. | Écrire « dépendance critique et transversale » ou attribuer explicitement le jugement. |
| IA régionale mutualisée et investissement de 200 K€ | Piste rapportée lors d'un entretien, faisabilité non établie. | Présenter comme option à instruire, jamais comme projet décidé. |

# 6. Sources prioritaires

## Cadrage et concepts

- [[Contexte du projet]]
- [[Objectifs et organisation du chantier 12]]
- [[Souveraineté Numérique]]
- [[Field Study SOLVAY]]
- [[PrincipesArchitectureSouveraineteNumerique.pdf|Principes d'architecture de la souveraineté numérique]], contribution de Michel Van Raemdonck, version 0.1, juin 2026, à distinguer d'un cadre validé.

## Contexte régional et retours d'expérience

- [[Interview Dominique Le Grelle]]
- [[Interview Damien De Meyer et Pascal Van Caldenborgh]]
- [[Interview Michel Van Raemdonck]]
- [[Interview Ivan Cols]]
- Autres entretiens pertinents présents dans le dossier `02 - Entretiens/`, en vérifiant leur statut et leur confidentialité.

## Analyses et benchmark

- [[Benchmark des initiatives et solutions de souveraineté numérique]]
- [[Rapport OCTO - Souveraineté Numérique]]
- [[Note d’avis — Move2Cloud - CADA]]
- Rapport et benchmark Solvay en PDF, avec les limites indiquées dans [[Field Study SOLVAY]].
- Sources officielles européennes et textes juridiques à jour pour toute affirmation réglementaire.

## Plans antérieurs

- [[Rapport intermédiaire - septembre 2026]]
- [[Rapport intermédiaire V2 - septembre 2026 (DeepSeek V4 Flash)]]
- [[Rapport intermédiaire V3 - septembre 2026 (GPT Astra)]]
- [[Rapport intermédiaire V4 - septembre 2026]]
- [[Rapport intermédiaire V5 - septembre 2026 (GLM 5.3)]]

Les plans antérieurs servent à comprendre l'intention, les pistes et les points de vigilance. Ils ne doivent pas être cités comme preuves d'un fait externe ou interne.

# 7. Visuels et annexes

## Visuels recommandés

- Un schéma du flux entre GT3, GT4, GT5 et GT6, le cerveau collectif du GT2, l'analyse du GT1, la sensibilisation du GT7 et les projets concrets.
- Un tableau des cinq dimensions de souveraineté avec une question et un exemple par dimension.
- Une grille comparant deux ou trois dépendances de nature différente.
- Un tableau reliant principes de souveraineté et dimensions du TOM IT.
- Une frise « septembre, décembre, au-delà » montrant le caractère progressif de la démarche.

Chaque visuel doit avoir un message explicite, une source et un périmètre. Éviter les illustrations décoratives et les graphiques fondés sur des chiffres non validés.

## Annexes possibles

- Organisation détaillée des GT et inventaire des productions avec leur statut.
- Méthode et données de l'analyse fournisseurs.
- Tableau du benchmark avec sources, dates et niveau de vérification.
- Matrice Solvay clairement identifiée comme point de départ à revoir.
- Grille d'évaluation du GT6 si son statut et ses tests sont explicités.
- Glossaire et références juridiques.
- Liste des questions ouvertes.

# 8. Contrôle qualité avant livraison

Le rapport n'est livrable que si toutes les réponses suivantes sont positives :

- Le rapport répond-il aux deux questions de mission ?
- La synthèse peut-elle être comprise sans lire le corps ?
- La date de référence et le périmètre sont-ils explicites ?
- Chaque chiffre important a-t-il une source primaire, un dénominateur, une date et un périmètre ?
- Les constats Paradigm sont-ils distingués des constats régionaux ?
- Les faits, témoignages, principes proposés et pistes sont-ils clairement séparés ?
- Les informations confidentielles ou sensibles ont-elles été validées pour diffusion ?
- Le statut juridique du CADA a-t-il été vérifié sur une source officielle à jour ?
- Les exemples du benchmark ont-ils été vérifiés et contextualisés ?
- Les limites apparaissent-elles près des constats concernés ?
- Les cinq dimensions et les cinq leviers sont-ils traités sans équivalence simpliste ?
- Les implications pour Atlas sont-elles formulées comme des repères et questions, pas comme des décisions ?
- Les coûts, contraintes, compétences et effets sur les utilisateurs sont-ils visibles ?
- Toute affirmation non vérifiée a-t-elle été retirée ou explicitement qualifiée ?
- Le texte évite-t-il les répétitions, le ton alarmiste, le jargon et la valorisation institutionnelle ?
- Le corps tient-il dans environ 10 pages et la synthèse dans 2 pages ?

# 9. Instruction finale à l'IA rédactrice

Rédige un rapport démonstratif plutôt qu'exhaustif. Chaque partie doit articuler : **ce que nous savons, ce que cela signifie, les limites de ce savoir et ce que cela implique pour la suite**. N'invente aucune donnée, ne masque aucune incertitude et ne transforme aucune piste en décision. Le meilleur rapport intermédiaire sera celui qui donnera au lecteur une compréhension juste du sujet, une vision honnête de l'avancement et des repères directement utilisables pour penser le TOM IT d'Atlas.
