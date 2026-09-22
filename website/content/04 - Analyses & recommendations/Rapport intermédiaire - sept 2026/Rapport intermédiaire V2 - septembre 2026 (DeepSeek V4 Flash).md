> [!info] Information
> Cette fiche définit le plan et les informations clés du rapport intermédiaire du chantier 12 prévu pour la mi-septembre 2026. Ce rapport fait un état des lieux de l'avancement du projet pour informer le sponsor du chantier, la direction, le cabinet de tutelle de Paradigm et les collaborateurs de Paradigm.
>
> **Contexte :** le rapport est demandé en priorité par le Groupe de Travail IT du Pilier 1 qui veut savoir où en est la réflexion sur la souveraineté et surtout identifier les recommandations qui pourraient impacter le Target Operating Model d'Atlas. Le rapport est purement informatif : il pourra susciter des réactions menant à des décisions, mais ce n'est pas son objectif.
>
> **Format cible :** 10 pages maximum, dont un executive summary de 2 pages maximum qui peut renvoyer vers des sections du document. Pas d'articulation à prévoir avec le rapport final de décembre : on explique où on en est dans l'analyse.

# Messages clés


> [!WARNING] Point d'attention
> Cette section ne fait pas partie du plan du rapport. Elle liste les points clés discutés ou actés par les Groupes de Travail. Ces différents points devront apparaître dans le rapport.

- On ne vise pas une autonomie totale et inaccessible lorsque l'on parle de souveraineté numérique. On fait le constat que la dépendance européenne est importante et qu'elle s'intensifie avec le cloud et l'IA. On cherche à cartographier nos dépendances et à s'organiser pour les réduire à moyen terme.

- La souveraineté numérique doit être analysée selon différents axes de risques : juridiques, économique, technologique, approvisionnement, auxquels s'ajoute l'axe compétences (cf. matrice du rapport Solvay).

- La Région dispose déjà d'actifs et de capacités propres qui constituent des leviers potentiels : infrastructures régionales, IrisNet, compétences, applications développées en interne, capacité de mutualisation.

- La transformation actuelle (Pilier 1) du paysage IT régional représente une fenêtre d'opportunité, mais également un risque de renforcer certains lock-in pour une longue période (cf. note [Move2Cloud/CADA](https://cirbbrussels.sharepoint.com/:w:/t/para-p025/IQAdcMP6bYctTaQZv7eNmzrUAcr039FeK1raQM7F58fGTmA?e=e2qsdt&wdLOR=c66FBB696-493E-0741-A2E7-18660F0E00C0)).

- L'analyse des différentes solutions explorées par d'autres entités publiques en Europe permet d'identifier 5 leviers de souveraineté actionnables, à ce stade, par la Région.

- **Les compétences humaines constituent la première dépendance critique.** L'externalisation sans transfert de connaissance est une perte de souveraineté irréversible (ratio consultant/interne, temps d'intégration, cas du DCR passé de 35 à 15 personnes). Message central des entretiens (cf. [[Interview Dominique Le Grelle]], [[Interview Damien De Meyer et Pascal Van Caldenborgh]]).

- **Le paradoxe Paradigm :** des infrastructures souveraines (DCR, fibres IrisNet, MAN privé) mais des couches logicielles et cloud quasi exclusivement américaines. Nos atouts existent mais ne sont pas toujours utilisés comme leviers, voire sont fragilisés.

- **L'impact sur le TOM :** plusieurs orientations (architecture, achats, compétences, gouvernance des données, organisation des fonctions IT) toucheront le Target Operating Model de Pilier 1. L'objet du rapport est de les signaler, pas de les décider.

- Garder la citation du rapport Solvay « la souveraineté numérique, c'est choisir ce que l'on accepte de ne pas contrôler ».

# Executive Summary (max 2 pages)

À rédiger en dernier. Il doit reprendre, avec des renvois vers les sections :

- Le sujet et pourquoi il s'impose maintenant.
- Où en est le chantier 12 et la Région (en bref).
- Les éléments structurants de la compréhension (définition, dimensions, leviers).
- Les premières implications pour le TOM (avec renvois vers les sections).
- Ce qui reste à faire.

# 1. Le chantier 12 en bref (~1 page)

Objectif : situer le rapport pour un lecteur qui ne connaît pas le chantier. Pas de détails.

- **Finalité et organisation :** les 7 groupes de travail et leur logique de flux (terrain → benchmark / écosystème / évaluation → cerveau collectif → analyse → sensibilisation → projets concrets). Réf. [[Objectifs et organisation du chantier 12]].
- **Méthode de collecte :** interviews internes et externes, sondages, benchmark, sources (rapport Solvay, rapport OCTO, note CADA, etc.).
- **Le cerveau collectif :** vault Obsidian partagé, structuration des connaissances et expérimentation d'une IA souveraine pour interroger le corpus.
- **Où on en est / ce qui reste à faire :** outil d'évaluation (GT6), projets pilotes, rapport final décembre.

# 2. Le sujet : pourquoi stratégique maintenant (~2 pages)

## 2.1 Contexte et enjeux

Expliquer pourquoi le sujet devient stratégique maintenant et s'impose aussi à la RBC :

- concentration du marché numérique autour de quelques acteurs mondiaux ;
- développement du cloud et de l'IA par des acteurs exclusivement US ou chinois ;
- évolution du contexte géopolitique (administration US) ;
- extraterritorialité de certaines législations (Cloud Act et loi FISA) ;
- évolution parfois brutale des modèles commerciaux des fournisseurs ;
- mise en place du CADA au niveau européen.

Illustrer et donner des chiffres :

- 80% du marché du logiciel-cloud capté par des acteurs américains, soit 265 Milliards d'euros par an, préjudiciable en termes d'emploi ou de recettes fiscales. (source: Etude Astérès pour le CIGREF, 2025]- le cas Broadcom/VMware (risque économique) ;
- le cas de la Cour pénale internationale (risque opérationnel) ;
- le cas iranien comme scénario extrême de rupture d'accès (à utiliser avec prudence, cf. benchmark).


## 2.2 Définition structurante et idées reçues à dépasser

Dans le cadre du chantier, nous retenons la définition suivante (cf. [[Souveraineté Numérique]]) :

> La souveraineté numérique désigne la capacité d'une organisation à connaître, maîtriser et arbitrer ses dépendances numériques afin de préserver sa capacité de décision, d'action et de continuité.

Cette définition implique que la souveraineté :

- n'est pas un état absolu ;
- n'exclut pas les fournisseurs internationaux ;
- repose sur une analyse des risques ;
- se construit progressivement.

**Encadré « ce que la souveraineté n'est pas »** (idées reçues ou simplistes à éviter par une analyse approfondie) :

- ce n'est pas une autarcie numérique ni le rejet systématique des technologies américaines ;
- ce n'est pas « tout open source » (l'open source est un levier potentiel, pas une garantie de souveraineté, cf. rapport OCTO) ;
- ce n'est pas un simple sujet d'hébergement des données (une donnée hébergée en Belgique peut rester soumise à une législation étrangère) ;
- ce n'est pas une obligation de tout développer soi-même.

## 2.3 Dimensions de la souveraineté

Reprendre les axes proposés par le rapport Solvay :

- Souveraineté Data ;
- Souveraineté Technique ;
- Souveraineté Économique ;
- Souveraineté d'Approvisionnement ;
- et y ajouter l'axe Compétences (suggestion Dominique Le Grelle, cf. [[Interview Dominique Le Grelle]]), illustré par des cas où l'externalisation a fait disparaître la capacité de Paradigm à reprendre un système.

## 2.4 Risques liés aux dépendances

Illustrer la notion abstraite de souveraineté par des risques concrets :

- accès ou contrôle des données (lois extraterritoriales US, collision avec le RGPD) ;
- vendor lock-in (exemple VMware, chiffres d'augmentation des licences pour Paradigm) ;
- augmentation des coûts (risques forts probables d'augmentation des prix des tokens IA sur les licences Copilot dans les années à venir) ;
- impossibilité ou coût élevé de migration (exemple SAP ?) ;
- perte de compétences (exemples concrets à demander à Dominique Le Grelle).

Message important :

> Une dépendance n'est pas nécessairement un problème. Elle devient un risque lorsqu'elle concerne une fonction critique et que l'organisation ne dispose pas d'alternative ou de capacité de sortie acceptable.

## 2.5 Le facteur humain : compétences et continuité

Mettre en avant le risque n°1 identifié par les entretiens :

- l'externalisation sans plan de retour est une perte de souveraineté irréversible (datacenter externalisé, applications développées par des prestataires disparus) ;
- ratio consultant/interne à maîtriser (10 à 20 % maximum de consultants, avec transfert systématique de connaissance) ;
- temps d'intégration incompressible de 6 mois : anticiper les départs plutôt que subir les pertes ;
- cas du DCR : équipe passée de 35 à 15 personnes, une personne par domaine, vulnérabilité opérationnelle.

## 2.6 Cadre européen et CADA

Voir note [[Note d’avis — Move2Cloud - CADA]]
Présenter le mouvement européen vers davantage de maîtrise du cloud et des infrastructures numériques.

Le CADA peut être présenté comme un élément structurant du cadre en construction, mais il faudra être très prudent sur son statut juridique exact et distinguer ce qui est proposé, adopté ou applicable (attention, la note Move2Cloud est un peu trop catégorique sur ce point).

La note Move2Cloud est utile pour introduire plusieurs concepts : analyse préalable des risques, niveaux différenciés de souveraineté selon les activités et intérêt d'une architecture segmentée plutôt qu'une réponse identique pour tous les services.

# 3. État des lieux de la Région bruxelloise (~2,5 pages)

## 3.1 Première cartographie des dépendances

Analyse de la liste des fournisseurs Paradigm fournie par Pascal Van C.

> « Une première analyse du portefeuille de 137 éditeurs et fabricants référencés par Paradigm montre que 42 % ont leur siège aux États-Unis, contre environ 26 % dans l'Union européenne. Cette exposition s'accentue sur les couches technologiques les plus stratégiques : 65 % des fournisseurs associés à des usages Cloud sont américains et cette proportion atteint 88 % pour les fournisseurs associés à des usages d'intelligence artificielle. »

Ces résultats ne constituent pas à eux seuls une mesure de dépendance ou de risque souverain, mais ils mettent en évidence la nécessité d'une analyse plus fine fondée sur la criticité des services, la nature des données, la juridiction applicable et la réversibilité des solutions.

Dépendances identifiées par Solvay : Microsoft 365, VMware/Broadcom, Snowflake/Azure, Cisco, Windows, Copilot.

Il s'agit à ce stade essentiellement d'un diagnostic Paradigm, pas encore d'une cartographie complète de la Région.

## 3.2 Matrice de risques et priorisation

Risque => Dépendance × criticité × réversibilité.

On peut reprendre ici la matrice des risques du rapport Solvay en précisant que cette matrice va être revue et enrichie par le chantier 12. On peut aussi citer les points critiques présentés par le rapport.

Montrer, par exemple, pourquoi VMware et Microsoft 365 ne doivent pas être traités de la même manière => VMware relève surtout d'un risque économique et technique, tandis que M365 soulève davantage des enjeux juridiques sur les données.

## 3.3 Forces et actifs régionaux et paradoxe Paradigm

Faire aussi le diagnostic de ce que nous maîtrisons, et pas seulement de nos faiblesses :

- Datacenter régional ;
- IrisNet ;
- mutualisations existantes ;
- compétences internes ;
- applications développées en interne : IRISbox, FixMyStreet, iCatalog, SWR...

Le rapport Solvay considère précisément cette combinaison infrastructure + réseau + compétences/applications + mutualisation comme un avantage spécifique de la région.

**Le paradoxe Paradigm :** nous possédons des infrastructures physiques souveraines (DCR, fibres IrisNet, MAN privé où les données ne passent pas par internet), mais les couches logicielles et cloud qui font tourner ces infrastructures sont quasi entièrement américaines. Certains de nos atouts sont fragilisés (backup déplacé en Hollande, équipe réduite, contrat ATOS) ou pas utilisés comme leviers.

L'important est de présenter ces éléments comme des actifs à évaluer, pas comme des actifs qu'il faudrait absolument conserver dans leur forme actuelle.

## 3.4 Zones restant à investiguer

Montrer ce que nous ne savons pas encore :

- dépendances des autres administrations ;
- dépendances applicatives ;
- contrats et dates de renouvellement ;
- coûts de sortie ;
- compétences critiques ;
- solutions pour lesquelles aucune alternative crédible n'existe.

Le rapport Solvay identifie déjà plusieurs zones grises : EDR, stockage objet, périmètre Snowflake, gestion des identités, usages réels de l'IA.

# 4. Ce qu'on apprend du benchmark (~2 pages)

## 4.1 Enseignements et limites du benchmark

### Ce qui semble fonctionner
Progressivité, pilotes, gouvernance claire, compétences internes, standards ouverts, anticipation plutôt que migration sous contrainte.

### Ce qui fonctionne moins bien
Big bang, approche idéologique, solutions excessivement customisées, sous-estimation de la gestion du changement utilisateur, absence d'interopérabilité, migration sans sponsor politique durable.

### Les limites du benchmark
Ces expériences européennes ne démontrent pas qu'une technologie particulière constitue la bonne solution pour Bruxelles, mais elles permettent d'identifier des principes et conditions de réussite : intérêt de la progressivité, de la réversibilité, des standards ouverts, de la mutualisation et du maintien de compétences internes.

## 4.2 Les 5 leviers pertinents pour Bruxelles

### Levier 1 : Approche différenciée selon la criticité
Principe central : tous les systèmes ne nécessitent pas le même niveau de souveraineté. Un des objectifs du chantier 12 est de proposer un outil d'évaluation et une classification simple des risques (e.g. faible, modéré, élevé, critique), puis d'associer progressivement des exigences différentes à chaque niveau.

### Levier 2 : Diversification / multi-fournisseurs
Ne pas chercher nécessairement à remplacer un fournisseur par un autre, mais éviter certaines concentrations et maintenir des alternatives. Exemple : stratégie full Azure dénoncée dans la note Move2Cloud/CADA.

### Levier 3 : Marchés publics
Sujet majeur, très concret et relativement facile à implémenter. Introduire progressivement dans nos marchés publics :

- critères de réversibilité et portabilité (formats ouverts, API documentées, export des données, limitation des dépendances propriétaires) cf. « architecture portable par défaut » dans le rapport Solvay ;
- localisation des données ;
- juridiction en vigueur ;
- standards ouverts ;
- transfert de connaissances ;
- coût de sortie.

L'idée est de faire de la souveraineté un critère d'achat et d'architecture, pas seulement un sujet traité après le choix d'une solution.

### Levier 4 : Compétences
Deux dimensions : conserver des compétences critiques en interne et organiser le transfert de connaissances lors de l'externalisation. Cf. [[Interview Dominique Le Grelle]] : la dépendance peut s'installer progressivement lorsqu'un prestataire devient le seul détenteur de la connaissance d'un système.

### Levier 5 : Open source et communs
Voir note [[Rapport OCTO - Souveraineté Numérique]]. Éviter l'équation simpliste open source = souveraineté. Présenter plutôt l'open source comme un levier potentiel de maîtrise, d'auditabilité, de réversibilité, de développement de compétences. Au-delà de la licence, c'est l'existence d'une communauté capable de faire vivre le projet qui protège de la dépendance : devenir contributeur, pas seulement utilisateur.

## 4.3 Le cas particulier de l'IA

L'IA est l'accélérateur de dépendance le plus actuel :

- risque : 88 % des fournisseurs associés à des usages d'IA sont américains, prix des tokens IA sur les licences Copilot, lobbying des grands acteurs ;
- opportunité : demande d'IA souveraine (infrastructure GPU mutualisée au DCR, investissement estimé à ~200 K€, premiers demandeurs identifiés : IBSA, Paradigm) ;
- besoin d'une alternative structurée avant que les usages se verrouillent (cf. ambassadeurs IA).

# 5. Premières orientations et implications pour le TOM (~1,5 page)

## 5.1 Principes d'une doctrine régionale

À construire autour de quelques principes :

- on ne recherche pas une autonomie absolue ;
- le niveau de souveraineté dépend de la criticité ;
- dépendance assumée plutôt que dépendance subie ;
- réversibilité par défaut ;
- maîtrise des risques.

## 5.2 Implications potentielles pour le TOM de Pilier 1

Point de bascule du rapport : répondre à la question des responsables des GT IT du Pilier 1. Signaler, sans les décider, les orientations qui impacteront le Target Operating Model :

- **Architecture :** portabilité by design, standards ouverts, segmentation par niveau de sensibilité, éviter les concentrations excessives (vs stratégie full Azure) ;
- **Procurement :** critères de souveraineté dans les marchés (réversibilité, localisation, juridiction, transfert de connaissances, coût de sortie) ;
- **Compétences :** préservation des compétences critiques, transfert de connaissance lors de l'externalisation, conséquences sur les profils et l'organisation des équipes ;
- **Gouvernance des données :** registre des dépendances critiques, démarche permanente identifier → qualifier → prioriser → traiter → suivre ;
- **Organisation des fonctions IT :** rôle de l'écosystème et de la mutualisation (rôle mutualisateur de Paradigm, DBaaS, IA souveraine).

## 5.3 Ce que le chantier va déployer

- Outil d'évaluation de la maturité et des risques (GT6) ;
- registre des dépendances numériques critiques (à terme) ;
- projets pilotes (ex. test d'alternatives sur périmètre limité) ;
- poursuite du benchmark et de la connexion à l'écosystème (GT4, GT5).

# Conclusion (~0,5 page)

- Rappeler qu'on ne cherche pas une indépendance totale, mais qu'on cherche à réduire les risques disproportionnés sur les éléments critiques.
- Les 5 leviers identifiés par le chantier peuvent être déjà partagés, discutés et intégrés dans les réflexions actuelles du Pilier 1.
- La transformation régionale en cours (Pilier 1) est une occasion d'intégrer ces principes dès la conception plutôt que de corriger ultérieurement des dépendances devenues structurelles.
- Invitation : recueillir les réactions des GT IT du Pilier 1 et ouvrir les échanges.
- Parler des prochaines étapes du chantier 12 et du livrable final (décembre).
