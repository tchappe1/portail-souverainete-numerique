---
type:
  - Interview
published:
created: 2026-03-23
author: Thierry Chappé et Anna Mellone
---

# Synthèse structurée des entretiens — Datacenter Régional (DCR)

Personnes interviewées : Damien De Meyer (23/03/26) et Pascal Van Cladenborgh (26/03/26) Intervieweurs : Thierry et Anna Mellone 

---

## 1. Historique du Datacenter Régional

Le DCR trouve ses origines en 2006, lorsque le datacenter était hébergé sur les site de Joseph II et de l'ULB. Il a ensuite déménagé à Arts 21, puis une salle a été ajoutée au SIAMU, créant un triangle de résilience avec l'ULB comme site arbitre (quorum). Ce dispositif permet de réattribuer les services en cas de panne sur l'un des sites.

En 2004-2005, la virtualisation est introduite (VMware), d'abord pour les propres serveurs du DCR, puis progressivement pour les clients qui avaient leurs propres infrastructures. Ces clients ont petit à petit rapatrié leurs infras vers le DCR. Viapass est cité comme exemple d'architecture résistante à la panne construite dans ce cadre.

En 2023, l'infrastructure de virtualisation a été renouvelée, avec une extension prise en 2025. Le site de ULB a quant à lui été rénové par IRISnet en 2025, mais ce changement a multiplié par 10 les coûts de location (de ~5K€/an à un tarif bien plus élevé) — une décision prise par un ancien DG dont le contrat est introuvable.

---

## 2. Architecture technique et services

### Les trois produits du DCR

Hébergement web — le produit le plus simple, un serveur virtuel partagé. Tous les segments de clients sont représentés : communes, CPAS, mais aussi plus petites structures comme les bibliothèques. Rentabilité faible car trop gourmand en personnel.

Virtual Private Server (VPS) — une machine virtuelle gérée par Paradigm jusqu'à la couche du système applicatif et ses mises à jour. Le client y ajoute sa propre couche.

Virtual DataCenter (VDC) — le produit phare, activement poussé en 2026. Le client choisit ses ressources (CPU, RAM, stockage) et virtualise toute son infrastructure de manière souveraine. Il ne paie que ce qu'il commande. Le système d'exploitation est inclus dans le prix. Depuis leur OVDC, les clients gèrent leur environnement comme s'il était chez eux, tout en ayant leurs données hébergées dans les datacenters de Paradigm.

### Infrastructure physique

- ~2 600 machines virtuelles hébergées sur une quarantaine de serveurs physiques
    
- Un châssis de 12 serveurs coûte ~550K€ HTVA
    
- Stretch cluster : 100 machines virtuelles répliquées en permanence entre Sibelga et Colt — réactivation en 5 minutes en cas de panne. Le reste du V-Cloud n'est pas répliqué entre sites.
    
- 3 sites : Colt (Bruxelles), Sibelga, ULB
    
- Conteneurisation via OpenShift (notamment pour les applications Paradigm)
    
- Metropolitan Area Network (MAN) : réseau privé haut débit reliant le DCR à tous les clients VDC via les fibres IRISnet — les données ne passent pas par internet. La Région est propriétaire des fibres, IRISnet n'en est que le gestionnaire.
    

### Backup

Le fournisseur de backup a changé en janvier 2026 : le DCR fait désormais appel à Carbonite (Hollande) pour des raisons économiques. Le volume à sauvegarder est de 850 To, ce qui représente 7 Po de données en comptant toutes les versions. Coût : 480K€/an, sans limite de stockage, montant amené à augmenter. Les données sont cryptées. La question de la loi d'extraterritorialité américaine ne s'applique pas ici, Colt n'étant qu'un locataire d'espace physique — les fibres et équipements restent sous contrôle de Paradigm.

---

## 3. Données financières

|   |   |
|---|---|
|Élément|Montant|
|Facturation clients (2026 signé)|2,9 M€|
|Revenu VDC|~2,6 M€|
|Coût annuel total DCR|2,195 M€|
|dont Énergie|365K€|
|dont Location|1,721 M€|
|dont Housing|55K€|
|dont Dark Fiber|28K€|
|dont Nettoyage|4K€|
|Colt (location, housing, énergie)|853K€|
|Sibelga (énergie, location, fibre noire, nettoyage)|1,3 M€|
|ULB|37K€ (+ potentiellement 20K€)|
|Backup Carbonite|480K€/an|

Le matériel est acheté par Paradigm et amorti sur 4 ans, mais en pratique les serveurs sont gardés 7 à 8 ans, certains ayant plus de 11 ans. Une note sera soumise au BRUGOV pour un budget de renouvellement. La consommation électrique par machine virtuelle n'est pas encore mesurée finement (connue par rack), mais NIS2 pousse vers plus de reporting.

---

## 4. Pourquoi les clients utilisent le Datacenter Régional ?

### Le prix — attractif et surtout prévisible

Le DCR propose des tarifs compétitifs, souvent inférieurs à ceux des clouds publics. Mais l'argument le plus fort est la prévisibilité budgétaire : facturation simple basée sur les ressources commandées, sans surcoût lié au volume de données transférées, sans frais réseau cachés, sans surprises sur les licences. Pour des administrations publiques travaillant sur des budgets annuels fixes, c'est un avantage décisif. Le système d'exploitation est également inclus dans le prix du VDC.

### Pas de marché public à organiser

C'est un argument très concret et souvent décisif pour les clients publics. Utiliser le DCR via Paradigm leur évite de lancer eux-mêmes un appel d'offres — une procédure longue et coûteuse en ressources administratives. Les clients bénéficient d'un accès rapide à une infrastructure performante sans contrainte procédurale.

### La localisation dans la Région — un ancrage plus qu'une conviction

Les clients apprécient que les données soient hébergées à Bruxelles, dans des infrastructures connues opérées par Paradigm. Mais il faut nuancer : la souveraineté n'est généralement pas la raison première qui conduit les clients vers le DCR. Elle fonctionne davantage comme un frein au changement — elle surgit et prend toute son importance au moment où l'on envisage de modifier un service existant.

Deux exemples concrets illustrent ce mécanisme :

- Le passage à Microsoft 365 : la migration des mails régionaux vers une solution Microsoft suscite des résistances, notamment parce que les données se retrouveraient accessibles à Copilot et hébergées hors de Bruxelles. De nombreux clients préfèrent rester sur l'ancienne infrastructure mail — localisée chez Paradigm, économique et compatible avec leurs équipements existants.
    
- Le déménagement du backup en Hollande (Carbonite, janvier 2026) : lorsque le fournisseur de backup a changé pour des raisons économiques, plusieurs CPAS ont immédiatement exprimé leur inquiétude sur la localisation de leurs données sensibles hors de la Région. Même avec des données cryptées, le simple fait de sortir les backups de Bruxelles a déclenché des questions de fond.
    

En résumé : les clients viennent au DCR pour le prix et la simplicité administrative. Ils y restent — et résistent aux changements — parce que leurs données sont ancrées localement. La souveraineté est moins un argument de vente initial qu'un réflexe de prudence qui se manifeste dès que quelque chose change.

---

## 5. Enjeux stratégiques et perspectives

### Services à développer

Database as a Service : le DCR a déjà hébergé les bases de données du SPRB pendant des années. Dans le cadre de NIS2, il est envisagé de proposer des DB ultra-sécurisées en service. L'infrastructure sera d'abord déployée pour les propres services Paradigm, puis reproductible de manière automatisée chez les clients. Attention : la perte d'un DBA parti chez SPRB (IT-Cell) a mis fin à un embryon de produit prometteur.

Infrastructure pour l'IA : il existe une demande pour de la souveraineté IA. L'idée est d'acquérir du matériel spécifique (GPU/GPI) pour entraîner des modèles, mutualiser les ressources et offrir ce service aux clients de manière souveraine et économique. Investissement estimé à ~200K€. L'IBSA et Paradigm (Tanguy et Ivan) sont cités comme premiers demandeurs potentiels. Ce sujet n'est pas encore intégré dans la réflexion du groupe ambassadeurs IA d'Ivan Cols, mais Damien considère que Paradigm a un rôle à jouer : laisser les clients basculer vers Copilot sans alternative souveraine serait une occasion manquée, comparable au retard pris sur le cloud.

### Services à reconsidérer

L'hébergement web et le VPS standard pourraient être externalisés vers le cloud public — d'autres acteurs font ça mieux et moins cher, et ces services ne nécessitent pas de souveraineté particulière. Le DCR doit se concentrer sur ce qui a une réelle valeur ajoutée souveraine : le VDC, le Database as a Service et à terme l'IA.

### Enjeu humain et opérationnel

L'équipe est passée de 35 à 15 personnes, en grande partie à cause du contrat ATOS. ATOS Pologne gère l'opérationnel (mises à jour OS, firmware, réseau, configurations) mais crée des problèmes de proximité — c'est finalement Jean-Marc qui doit intervenir au quotidien. Le contrat ATOS se termine l'année prochaine. Le plan envisagé : recours temporaire à des spécialistes externes, puis réinternalisation progressive d'ici 2029-2030, sous réserve de l'accord du BRUGOV (moratoire sur les engagements de personnel). Actuellement, il n'y a plus qu'une personne par domaine (stockage, Oracle, réseau…) — toute absence crée une vulnérabilité opérationnelle. Pascal note que la direction n'a pas de position claire sur le sujet, alors que des lobbyistes de Microsoft auraient approché des cabinets pour migrer l'ensemble vers Azure — une option jugée bien plus coûteuse.

### Modèle d'investissement matériel

Contrairement au cloud public qui lisse les coûts, le DCR fait face à des cycles d'investissement lourds : un châssis de 12 serveurs à 550K€, acheté en bloc, amorti sur 4 ans mais utilisé 7 à 8 ans. Quand les machines atteignent leur fin de vie simultanément, le renouvellement représente un effort budgétaire concentré. Une note au BRUGOV est prévue pour anticiper ce besoin. Par ailleurs, avec la flambée des prix liée à l'IA, il est dans l'intérêt du DCR de conserver ses équipements actuels le plus longtemps possible.

---

## 6. Éléments utiles pour la présentation de la visite du DC

|   |   |
|---|---|
|Angle|Message clé|
|Histoire|Du Joseph II à aujourd'hui — 20 ans d'infrastructure régionale bruxelloise|
|Chiffres d'accroche|2 600 machines virtuelles, 40 serveurs physiques, 3 sites|
|Stockage|850 To de données actives, 7 Po de backups|
|Réseau|MAN privé sur fibres propriété de la Région — les données ne quittent pas Bruxelles|
|Clients|Communes, CPAS, bibliothèques, SIAMU, IBSA…|
|Pourquoi ils viennent|Prix prévisible, pas de marché public, simplicité|
|Pourquoi ils restent|Ancrage local, réflexe de prudence face aux changements|
|Résilience|Stretch cluster, triangle ULB-Sibelga-Colt, arbitrage automatique|
|Futur|DB as a service, IA souveraine, renouvellement infrastructure|

Contacts identifiés : Pascal Van Cladenborgh, Damien De Meyer, Jean-Marc De Vriese (partie DC), Frédérique Lambillotte (GT souveraineté), Francis De Mets (certifications sécurité), Christophe Dernelle (historique).








Chantier 12 - Souveraineté Numérique de la RBC -  Confidentiel - usage interne

