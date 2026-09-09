---
type:
  - Note
statut: En cours de rédaction
author: Duc PHAN
description: Liste des questions posées à Microsoft concernant la souveraineté numérique
---




La liste de questions ci-dessous vise à obtenir, lors d'échanges avec l'équipe de compte Microsoft (ou dans le cadre d'une RFP/due diligence), des réponses concrètes et vérifiables — et non de simples arguments marketing. Les questions sont regroupées par domaine de risque et formulées explicitement du point de vue d'un MSP qui utilise aujourd'hui la colocation et envisage éventuellement une migration vers AVS ou Azure Native.

**7.1 Juridique — CLOUD Act, FISA et juridiction**

1.     Microsoft peut-il garantir par écrit et contractuellement (pas uniquement via la documentation du Trust Center) que les données stockées à Belgium Central ne pourront jamais faire l'objet d'une demande CLOUD Act sans notification préalable au MSP et au client final ?

2.     Quelles mesures concrètes Microsoft a-t-il prises au cours des 12 derniers mois pour contester une demande CLOUD Act portant sur des données de clients de l'UE, et un rapport de transparence anonymisé peut-il être partagé spécifiquement pour les clients belges/Benelux ?

3.     Si un client public belge venait à tomber sous le coup d'une législation de sanctions d'un pays tiers, quelles garanties concrètes Microsoft offre-t-il que le service ne pourra pas être interrompu unilatéralement ?

4.     Existe-t-il un calendrier concret pour un équivalent belge de Bleu (France) ou de Delos Cloud (Allemagne) ? Sinon, quelle mitigation alternative Microsoft propose-t-il aux clients publics belges nécessitant une garantie CADA-Niveau 3 ?

5.     Indépendamment de sa réponse sur le CLOUD Act, Microsoft peut-il répondre séparément et explicitement au sujet du FISA (Foreign Intelligence Surveillance Act), et en particulier de sa Section 702 ainsi que de l'Executive Order 12333 : (a) dans quelle mesure les données de clients publics belges hébergées à Belgium Central peuvent-elles faire l'objet d'une demande FISA sans notification préalable au MSP ou au client final, (b) en quoi les garanties, voies de recours et mécanismes de transparence liés au FISA diffèrent-ils de ceux du CLOUD Act, et (c) Microsoft a-t-il déjà reçu, ou peut-il exclure d'avoir reçu, une demande FISA visant des données de clients belges/UE, et sous quelle forme cette information peut-elle être documentée pour le dossier de conformité du client public ?

**7.2 Disponibilité de la région et des produits (AVS)**

6.     Quelle est la date GA exacte (ou le statut actuel) d'Azure VMware Solution dans la région Belgium Central, y compris les types d'hôtes (AV36, AV36P, AV64) initialement disponibles ?

7.     Si AVS n'est pas encore pleinement disponible à Belgium Central : quelles garanties Microsoft offre-t-il que les charges de travail fonctionnant temporairement dans une autre région UE (par ex. Europe de l'Ouest) pourront être migrées vers Belgium Central sans frais ni interruption dès sa disponibilité ?

8.     Quelles garanties de SLA s'appliquent spécifiquement à Belgium Central en tant que région non appariée, et quelles options concrètes de disaster recovery (vers quelles régions) sont supportées sans que les données ne quittent l'EU Data Boundary ?

9.     Belgium Central supporte-t-il, dès son lancement, toutes les fonctionnalités AVS (Stretched Clusters, HCX Enterprise, Azure Elastic SAN), ou y a-t-il un déploiement échelonné avec des limitations fonctionnelles temporaires ?

**7.3 IAM et informatique confidentielle**

10.  Microsoft peut-il confirmer contractuellement qu'une implémentation AVS avec authentification AD DS/LDAPS sur vCenter/NSX (sans fédération Entra ID pour le plan de données) restera pleinement supportée à long terme, et ne basculera pas ultérieurement de manière obligatoire vers Entra ID ?

11.  Existe-t-il une feuille de route pour introduire l'informatique confidentielle (protection basée sur TEE) au niveau des hôtes AVS, et si oui, dans quel délai ?

12.  Quelle partie de la plateforme de gestion Azure (portail, Resource Manager, monitoring) pour un Sovereign Private Cloud AVS reste inévitablement dépendante d'Entra ID, même lorsque l'authentification du plan de données passe par un AD propre ?

**7.4 Gouvernance des données et transparence IA CADA**

13.  Quelle documentation concrète Microsoft fournit-il pour satisfaire aux exigences CADA relatives à la transparence des modèles d'IA et au contrôle des biais pour les services fonctionnant sur Azure AI/Copilot à Belgium Central ?

14.  De quelle manière le MSP peut-il faire réaliser un audit indépendant (ou via un tiers reconnu) des systèmes d'IA proposés par Microsoft, comme l'exige le CADA ?

15.  Quelles garanties Microsoft offre-t-il que les données d'entraînement des modèles d'IA sous-jacents ne sont pas traitées en dehors de l'EU Data Boundary, y compris pour l'amélioration des modèles au niveau mondial ?

**7.5 Réversibilité, contrat et SLA**

16.  Quel délai exact et quel format Microsoft garantit-il pour une exportation complète des données en cas de sortie, tant pour Azure Native (données PaaS) que pour AVS (images de VM), et ce processus est-il testé et documenté ?

17.  Quelles pénalités contractuelles ou compensations Microsoft prévoit-il si un SLA annoncé (par ex. 99,9 % pour AVS) n'est pas atteint chez un client public belge ?

18.  Microsoft peut-il partager un plan d'urgence concret pour le scénario où le service à Belgium Central deviendrait subitement (temporairement) indisponible, avec une estimation du délai de restauration (RTO/RPO) ?

19.  Quelles garanties Microsoft offre-t-il en matière de stabilité des prix et d'évitement du verrouillage fournisseur via des services PaaS propriétaires, spécifiquement pour les charges de travail que le MSP gère au nom de clients publics ?

**7.6 Trajectoire de migration colocation → Azure**

20.  Quels outils et supports concrets (par ex. Azure Migrate, VMware HCX) Microsoft met-il à disposition pour valider, avant la mise en production, la migration de l'environnement de colocation actuel (VMware/SVC) vers AVS, y compris un scénario de retour en arrière vers les racks existants ?

21.  Comment l'architecture actuelle de chiffrement et de stockage basée sur SVC (LUNs FC) est-elle migrée vers vSAN/Azure Elastic SAN sans perte des garanties de chiffrement actuelles, et une partie des charges de travail peut-elle délibérément rester en colocation pendant qu'une autre partie migre (modèle de coexistence) ?

22.  Quelles références concrètes (études de cas non anonymisées) Microsoft peut-il fournir de migrations comparables chez des clients publics européens partis d'un modèle de colocation, y compris les niveaux CADA ou de souveraineté équivalents atteints ?

23.  Quel est le plan d'action concret et le calendrier si le MSP souhaitait ultérieurement revenir à la colocation ou basculer vers une future National Partner Cloud belge ou européenne, et quelles garanties Microsoft donne-t-il dès à présent sur la faisabilité de cette transition (réversibilité dans les deux sens) ?

**7.7 Cryptographie post-quantique (PQC)**

24.  Quelle est la feuille de route concrète de Microsoft pour l'intégration d'algorithmes de chiffrement post-quantique normalisés (NIST FIPS 203/204/205 — ML-KEM, ML-DSA, SLH-DSA) dans Azure Key Vault, Managed HSM et le chiffrement vSAN d'AVS, et dans quel délai ces mécanismes seront-ils disponibles à Belgium Central ?

25.  Dans quelle mesure l'architecture proposée (Azure Native et AVS) permet-elle une migration crypto-agile — c'est-à-dire un changement d'algorithme de chiffrement sans réencodage complet des données ni interruption de service — et cette capacité a-t-elle déjà été testée en conditions réelles chez d'autres clients ?

26.  Microsoft propose-t-il déjà, à titre de mitigation intermédiaire contre le risque de type « harvest now, decrypt later » évoqué au chapitre 4.1, des mécanismes de chiffrement hybride (combinant un algorithme classique et un algorithme post-quantique) pour les données les plus sensibles hébergées à Belgium Central, et existe-t-il un calendrier pour les rendre disponibles par défaut ?