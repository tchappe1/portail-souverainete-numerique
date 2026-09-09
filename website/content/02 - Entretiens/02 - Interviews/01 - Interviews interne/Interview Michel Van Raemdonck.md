---
type:
  - Interview
published:
created: 2026-04-27
author: Etudiants SOLVAY
---


## Q1 Depuis notre dernier échange, est-ce que votre vision du sujet a évolué ? Y a-t-il eu des événements récents qui ont changé votre regard sur la souveraineté numérique ?

Sa vision n'a pas changé. La dépendance existe à tous les niveaux et à toutes les échelles  régional, national, et même individuel. Dans une entreprise, même les collaborateurs sont tributaires de systèmes qu'ils ne contrôlent pas.

être souverain, c'est simplement avoir mitigé tous ces risques. Si on accepte que la NSA puisse contextualiser des données, ou si on suppose qu'on peut se passer du cuivre pour faire transiter l'information, on est souverain dans ces deux cas. C'est une question de définition des risques acceptés.

nouveau gouvernement et nouveau ministre, ce ministre a une vision pragmatique : on n'a pas trop le choix, on est dépendant des grandes multinationales. La priorité est donc d'assurer une portabilité constante des données et d'éviter le vendor lock-in.

si on travaille exclusivement avec Microsoft en formats propriétaires, et que Microsoft décide de nous prendre en otage, on est bloqués. Mais si on travaille avec Microsoft en s'assurant que toutes les données restent dans des formats interopérables, alors le jour où cela pose problème, on peut récupérer ses données et basculer vers une autre plateforme.

  
  

##  Q2 Quand vous pensez au chantier souveraineté chez Paradigm, quelle est la première image qui vous vient ? Qu'est-ce qui vous préoccupe le plus ?

Le chantier souveraineté est censé couvrir tous les niveaux sans réinventer la roue : regarder ce qui a été fait dans d'autres régions et pays européens, dresser un état des lieux, lister les risques et proposer une mitigation. C'est avant tout un document stratégique.

Le livrable attendu est une architecture par défaut souveraine : quels sont les principes d'architecture qui permettent d'être souverain, à quel niveau, et comment ces principes reprennent les différents niveaux de risque et de mitigation.

Le choix d'implémenter tout ou partie de ce document est politique. Paradigm ne peut pas le faire seul. Son rôle est de dresser l'état des lieux et de formuler les recommandations. La décision d'agir appartient au politique.

  
  

##  Q3 On a identifié ce qu'on appelle un paradoxe Paradigm : vous possédez des infrastructures physiques souveraines (DC, IrisNet), mais les couches logicielles et cloud qui font tourner ces infrastructures sont quasi entièrement américaines. Est-ce que ce constat vous semble juste ?

Ce n'est pas ainsi que Paradigm lit le risque la réflexion interne n'est pas encore assez avancée pour être arrivée à ce niveau de granularité. 

Pour lui, le risque n'est pas tellement lié aux fournisseurs en tant que tels : c'est une question stratégique plus large. les États-Unis ne sont pas intrinsèquement plus dangereux que d'autres. Si on retourne 70 ans en arrière, on dépendait de l'Allemagne. Le problème est géopolitique, pas commercial. Un fournisseur veut vendre et gagner de l'argent : tant qu'on est là pour payer, il est là pour vendre.

  
  

##  Q4 Parmi les dépendances qu'on a cartographiées (VMware/Broadcom, Microsoft 365, le backup Colt, la data platform sur Azure) laquelle vous inquiète le plus ? Pourquoi ?

pas de hiérarchie, le risque n'est pas dans le fournisseur. l'infrastructure réseau (Cisco) et la virtualisation (VMware) sont des couches difficiles à changer, sans pour autant être les plus préoccupantes.

Ce qui lui semble stratégiquement le plus sensible, c'est la question des données stockées sur des clouds américains : si la NSA décide de faire main basse sur les données, tant qu'on est chez un opérateur américain, c'est possible quel que soit ce que le contrat garantit. Au niveau contractuel, le fournisseur peut garantir la confidentialité, mais il possède les clés pour accéder à tous les systèmes.

eg. Le seul moyen d'être certain qu'une machine est isolée, c'est de débrancher le câble. Aujourd'hui, tous les clouds sont interconnectés. Même un cloud européen reste vulnérable à des acteurs qui pourraient accéder aux données via les interconnexions, un ingénieur très bon un peu pirate sur les côtés. 

  
  

##  Q5 On a vu que Paradigm a récemment déployé une data platform sur Snowflake / Azure à Amsterdam. Comment ce choix a-t-il été fait ? Est-ce que la question de la souveraineté a été posée à ce moment-là ?

À l'époque, la question de la souveraineté n'était tout simplement pas sur la table. Le choix a été fait de manière rationnelle par rapport aux critères du moment, mais irrationnel en termes de coût.

eg. la STIB utilisait déjà un stack technologique similaire (Snowflake + Microsoft pour l'intégration des données). À l'époque, il existait une volonté politique forte de mutualiser les infrastructures IT régionales. Pour que la STIB puisse être embarquée dans l'aventure Paradigm, il fallait adopter le même stack technologique. C'est cette logique d'alignement qui a motivé le choix.

Il précise : l'Europe proposait alors un stack entièrement open source qui aurait été plus opportun  il n'était pas moins performant, simplement moins aligné avec celui de la STIB. Aujourd'hui, ce choix ne serait pas fait de la même façon. La migration vers un stack différent est techniquement possible, mais n'est pas à l'ordre du jour.

  
  

##  Q6 Si vous deviez définir la souveraineté numérique en une phrase, pour vous, pas pour un rapport, ce serait quoi ?

> [!QUOTE]
> « Choisir ce que je veux bien partager et sur quoi je veux bien ne pas avoir la main. »

Ce n'est pas une question d'autarcie absolue. Instagram ou TikTok  dès qu'on y publie quelque chose, on en perd la maîtrise. La souveraineté consiste à être conscient de ce qu'on partage et à faire des choix éclairés. 

débats internes sur ce que signifie concrètement la souveraineté n'ont pas encore eu lieu chez Paradigm  la stratégie a démarré il y a quelques mois seulement. Il faudra trancher à un moment : qu'est-ce qu'on accepte, qu'est-ce qu'on n'accepte pas, où fixe-t-on les limites ? La c'est trop tôt.

  
  

##  Q7 Quand on regarde ce que Schleswig-Holstein a fait, 30 000 fonctionnaires migrés hors Microsoft en 2 ans, 15 millions d'euros économisés par an, est-ce que c'est un scénario réaliste pour Paradigm ? Qu'est-ce qui vous semble transposable et qu'est-ce qui ne l'est pas ?

Une décision politique prise en 2020-2021, avec un déploiement démarré en mars 2024 — soit 3 à 4 ans d'écart, l'Allemagne est rigoureuse et que cela irait moins vite en Belgique.

Sur les outils : il utilise Proton (avec toute la suite : calendrier, coffre-fort de mots de passe, cloud, et bientôt un équivalent Teams). Il a aussi utilisé Thunderbird, mais problématique : en tant que client lourd, tous les mails sont stockés en local, et si la machine plante, les mails sont perdus. Il préfère donc des fournisseurs européens qui gèrent la messagerie côté serveur.

Sur les freins réels à une telle migration, trois niveaux :

- La gestion du changement : les gens utilisent la suite Office depuis des décennies. Même si en réalité ils n'utilisent que 5% des fonctionnalités — et que celles-ci sont disponibles sur des outils open source — l'argument « j'ai plus cette fonctionnalité » sera massif. C'est un frein humain avant d'être un frein technique.
    
- Le coût : passer à une suite open source ne coûte rien en licences, mais coûte en gestion du changement et en migration. C'est un coût réel mais gérable.
    
- Les infrastructures : une migration massive implique de réinvestir dans des data centers propres. Le data center bruxellois actuel est insuffisant. La migration des bases de données, des flux de données (notamment ceux développés sur Azure Data Factory) représente un redéveloppement complet — dev, test, production. Cela prendra 5 à 10 ans. Et on vient à peine de terminer le trajet dans l'autre sens.
    

le choix politique est secondaire par rapport à la gestion du changement. Si ceux qui gèrent l'IT régionale présentent un plan de migration solide, le politique suivra.

  
  

##  Q8 Le politique bruxellois est-il conscient des enjeux de souveraineté numérique ? Est-ce un sujet sur lequel vous avez eu des échanges avec le cabinet du Ministre ?

La souveraineté numérique est devenue un sujet à la mode depuis la réélection de Trump. Avant cela, tout le monde s'en désintéressait  sauf quelques précurseurs comme la gendarmerie nationale française ou certains acteurs allemands. En Belgique, on n'en parlait pas.

Obama n'était pas plus gentil que Trump, il avait juste un discours différent. Au fond, les États-Unis entrent en guerre quand ils veulent, contre qui ils veulent, et l'Europe n'est pas à l'abri.

La commune de Ganshoren a sorti son premier chatbot en utilisant un LLM scandinave. Microsoft est venu se plaindre auprès de la direction générale de Paradigm, en accusant Paradigm de travailler dans leur dos alors qu'ils investissaient massivement ensemble sur Copilot. Initiative qui n'était pourtant pas celle de Paradigm, mais de la commune elle-même.

Le lobbying des grands acteurs internationaux aura un impact si Paradigm décide de changer de fournisseur. L'Europe propose des alternatives open source et commence à prendre conscience de sa vulnérabilité, mais le lobbying européen reste moins efficace que celui des GAFAM.

Le ministre de tutelle est conscient des contraintes: être portable, éviter le vendor lock-in. Cela ne veut pas dire ne pas travailler avec les grands acteurs  cela veut dire être capable de les quitter si nécessaire.

  
  

##  Q9 Quels seraient les principaux obstacles internes à une stratégie de souveraineté chez Paradigm ? On pense à des résistances, des contraintes contractuelles, des dépendances qui seraient difficiles à défaire.

deux obstacles principaux :

- La gestion du changement : tout le monde n'est pas informaticien chez Paradigm, et même parmi les informaticiens, certains sont très résistants au changement. C'est un frein massif.
    
- job protection: des collaborateurs ont investi des années dans la maîtrise d'un outil spécifique. Si on change de système, ils s'interrogent sur leur avenir. Salesforce  une équipe entière spécialisée dans cet outil. Si on décide d'arrêter Salesforce pour des raisons de souveraineté, toute cette équipe se pose la question de ce que devient son expertise. Plutôt que d'accepter de se former à une nouvelle technologie, certains administrateurs préfèrent démissionner. Ce n'est pas seulement une perte de compétences techniques, c'est aussi une connaissance métier qui part avec eux, beaucoup plus difficile à reconstruire.
    

  
  

## Q10 Si on devait choisir un seul dossier à ouvrir en priorité — celui qui aurait le plus d'impact et qui serait politiquement et techniquement faisable — ce serait lequel selon vous ?

Thierry nous a orientés vers un deep dive sur le data center régional, intéressant car c'est un atout régional mais pas certain de son intérêt politique.

En termes de bureautique open source (migration hors Office), il ne prendrait pas ce chemin maintenant : dans les 2-3 ans à venir, Paradigm va déjà devoir absorber un changement organisationnel majeur (fusion des départements IT de la région, simplification administrative, regroupement des ressources humaines via Talent, etc.). Rajouter un changement d'environnement de travail par-dessus serait contre-productif.

Par contre:

- Migration des serveurs Windows vers Linux en local.
    
- Migration des bases de données propriétaires (SQL Server) vers PostgreSQL ou équivalent open source.
    
- Travail sur la conteneurisation et la standardisation des solutions cloud pour les rendre facilement déplaçables d'un fournisseur à l'autre, sans nécessairement viser le full open source.
    

volonté politique bruxelloise d'avoir un seul département IT pour toute la région (Connect pour l'administration centrale, Paradigm pour les administrations et pouvoirs locaux, Bruxelles Fiscalité, Easy, etc. aujourd'hui éparpillés). Ce changement organisationnel est peut-être le vrai chantier structurant.

  

## Q11 Notre livrable final est une présentation en juin. Mais au-delà du format — qu'est-ce qui serait vraiment utile pour vous ? Un document qu'on peut envoyer au cabinet ? Une note interne ? Quelque chose de plus opérationnel ?

rester dans le mode conceptuel. Rentrer trop dans la technique (interopérabilité au niveau SGBD, conteneurisation détaillée) ne serait pas utile. Par contre, maîtriser les concepts est indispensable pour que le document soit crédible.

intéressant à creuser : la portabilité. Comment se défaire d'un partenaire avec lequel on ne veut plus travailler ? Comment migrer facilement vers un autre fournisseur ? C'est à la fois un sujet stratégique, politique et technologique  et c'est là que se joue réellement la souveraineté au quotidien.

  
  

## Q12 On va interviewer Ivan Cols sur l'IA et la souveraineté. Y a-t-il des angles ou des questions qu'on devrait absolument aborder avec lui, selon vous ?

qu'est-ce qui existe comme IA souveraine en Europe ? Mistral est français, mais le LLM en tant que tel a été entraîné sur des data centers américains. Il n'existe pas en Europe d'infrastructure comparable en taille et en ressources à ce que possèdent les acteurs américains.

on n'a pas qu'un train de retard  on n'a pas de train du tout. Si on commence maintenant, on ne rattrapera jamais ce retard par les voies classiques.

idée à lui:  un modèle peer-to-peer pour les ressources de calcul. Sur n'importe quel PC, le CPU tourne en moyenne entre 5 et 20% de sa capacité le reste est dormant. Si chaque entité mettait à disposition la partie dormante de son CPU (50% par exemple, tant que le PC est allumé), on pourrait agréger en Europe une puissance de calcul collective suffisante pour développer des LLM souverains. c'est très conceptuel, mais techniquement réalisable en principe.

  
  

## Q13 Dernière question : si dans 3 ans Paradigm est vraiment reconnu comme un opérateur souverain de référence en Belgique — qu'est-ce que ça veut dire concrètement ? À quoi ça ressemble ?

une souveraineté absolue, on ne l'aura jamais. 2030, c'est trop tôt. En 2040, on pourra peut-être parler d'une « souveraineté mitigée »  être un peu plus en contrôle de nos données. 

le volet transactionnel : SWIFT, qui gère les transactions financières internationales et est américain. Il n'y a pas de concurrent identifié pour l'instant.

  ex. défense, il donne l'exemple des F-35 belges : les systèmes embarqués sont gérés par Siemens, mais les données sont traitées aux États-Unis. Siemens décide quelles données transmettre à la défense belge. En cas de tension géostratégique, les Américains pourraient couper l'accès aux données  l'avion volait toujours, mais à l'aveugle. Comme une Tesla sans données. C'est cela, la vraie dépendance souveraine.

  
**


Chantier 12 - Souveraineté Numérique de la RBC -  Confidentiel - usage interne

