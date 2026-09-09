

> [!info] Contexte
> Cette note d’avis a été préparée par Paradigm à l’attention du Cabinet dans le cadre du projet de migration des data centers régionaux de DRP vers Microsoft Azure.
>
> L’objectif est d’éclairer la décision du Cabinet sur les implications **juridiques, réglementaires, opérationnelles et stratégiques** d’une migration totale vers Azure, alors que le cadre européen de souveraineté cloud est en train de se structurer avec le **Cloud and AI Development Act (CADA)**.
>
> La note ne constitue **pas une opposition à l’utilisation de Microsoft**. Elle recommande plutôt de ne pas prendre dès maintenant une décision de migration totale qui pourrait rendre difficile l’adaptation ultérieure de l’architecture aux exigences du CADA.

## Pourquoi cette note ?

Le projet Move2Cloud envisage une migration importante vers Azure. Or, le CADA introduit de nouvelles exigences de souveraineté cloud, notamment une **analyse de risque préalable** permettant de déterminer le niveau de souveraineté requis selon les activités.

L'enjeu identifié est donc de **ne pas figer une architecture avant de connaître les exigences réglementaires qui s'appliqueront aux différentes activités régionales**.

La question n'est pas « Microsoft ou pas Microsoft », mais plutôt :

> **Quelle place donner à Azure dans une architecture régionale qui reste conforme, réversible et suffisamment souveraine ?**

---

## Points essentiels

### 1. Le CADA change le cadre de décision

Le CADA prévoit quatre niveaux d'assurance :

- **Niveau 1** → auto-déclaration
- **Niveau 2** → audit indépendant
- **Niveau 3** → audit renforcé + garanties contre l'accès extraterritorial
- **Niveau 4** → souveraineté maximale, notamment pour les activités sensibles

Le point central est l'**Article 29**, qui impose une analyse de risque permettant notamment de déterminer :
- quelles activités publiques sont concernées ;
- quel niveau d'assurance est nécessaire pour chacune ;
- si une stratégie multi-cloud / multi-fournisseur est pertinente.

**Conséquence pour Move2Cloud :** une migration totale avant cette analyse pourrait conduire à devoir modifier ou réverser l'architecture dans les 12 mois si certaines activités nécessitent finalement un niveau 3 ou 4.

---

### 2. Le principal risque juridique est l'extraterritorialité américaine

Microsoft étant une entreprise de droit américain, la note analyse notamment :

- **CLOUD Act**
- **FISA 702**
- **Schrems II**

Le problème est particulièrement important pour les niveaux 3 et 4 du CADA.

La localisation des données en Europe ou des engagements contractuels de résidence des données ne suffisent pas nécessairement à supprimer le risque lié au droit américain.

> [!warning] Point clé
> Une offre commerciale « souveraine » de Microsoft ne permet pas, en l'état, de supprimer l'exposition de Microsoft Corporation au CLOUD Act et à FISA 702.

La note considère donc que les offres Microsoft « souveraines » ne permettront vraisemblablement pas d'atteindre les exigences des **niveaux 3 et 4 du CADA** pour les activités les plus sensibles.

---

### 3. Une migration totale crée un fort vendor lock-in

Le risque ne concerne pas seulement l'infrastructure Azure.

Une migration complète pourrait concentrer chez Microsoft plusieurs briques structurantes :

- **Entra ID** → identité et gestion des accès
- **Microsoft 365 / Teams / SharePoint** → bureautique et collaboration
- **Azure IaaS/PaaS** → infrastructure et applications
- **Intune / Endpoint Manager** → gestion des postes et appareils

Le verrouillage serait donc à la fois **technique, organisationnel et économique**.

Trois risques sont particulièrement identifiés :

**Tarifaire** → réduction de la concurrence et dépendance au fournisseur.

**Continuité** → exposition à une décision unilatérale du fournisseur.

**Irréversibilité** → coût et durée importants pour revenir vers une autre architecture.

---

### 4. Toutes les activités régionales ne présentent pas le même niveau de risque

La note propose une première segmentation :

| Activité | Niveau CADA indicatif | Azure | Risque |
|---|---|---|---|
| Bureautique & collaboration | 1 | Accessible | Faible |
| Identité & accès | 1–2 | Niveau 1 accessible | Modéré |
| Données citoyennes | 2–3 | Niveau 3 problématique | Élevé |
| Activités NIS2 critiques | 3 | Non conforme | Élevé |
| Sécurité / ordre public / justice | 3–4 | Incompatible | Critique |
| Données classifiées UE | 4 | Inaccessible | Critique |

L'approche proposée est donc une **segmentation par niveau de sensibilité**, plutôt qu'une approche « tout Azure » ou « pas de Microsoft ».

---

## Recommandations

### À faire avant toute décision de migration

**1. Réaliser l'analyse de risque CADA (Article 29)**  
C'est la priorité. Elle doit permettre de déterminer quelles activités nécessitent les niveaux 2, 3 ou 4.

**2. Définir une architecture cible segmentée**

Trois grandes catégories :

- usages sans enjeux d'ordre public → Azure possible ;
- usages à enjeux modérés → Azure sous conditions ;
- usages critiques → infrastructure souveraine européenne.

**3. Sécuriser la réversibilité contractuelle**

Tout contrat Azure devrait prévoir notamment :

- clauses de réversibilité ;
- export des données sans coût prohibitif ;
- notification en cas d'injonction légale américaine ;
- possibilité de revoir le contrat si le cadre européen évolue.

### À moyen terme

**4. Identifier des alternatives souveraines européennes** pour les usages critiques.

La note cite notamment les initiatives et acteurs suivants :
- OVHcloud
- Outscale
- CISPE
- EuroCloud Federation

**5. Ne pas concentrer l'identité sur Azure**

Entra ID est identifié comme une des briques les plus difficiles à migrer.

La stratégie devrait donc intégrer dès la conception :
- une stratégie de réversibilité ;
- ou une architecture hybride ;
- ou une fédération avec un IdP souverain.

---

## Conclusion

La note recommande de **surseoir à une migration totale et exclusive vers Azure** tant que l'analyse de risque CADA n'a pas été réalisée.

L'approche proposée est plutôt :

> **Microsoft peut rester une composante importante du SI régional, mais dans une architecture maîtrisée, segmentée et réversible, compatible avec une logique multi-cloud / multi-fournisseur.**

Les quatre risques principaux identifiés sont :

1. **Juridique** → CLOUD Act / FISA 702
2. **Réglementaire** → incompatibilité potentielle avec les niveaux 3 et 4 du CADA
3. **Stratégique** → dépendance et vendor lock-in
4. **Financier** → coût potentiel d'une réversibilité ou d'une correction architecturale ultérieure

---

## Lien vers le document source

![[Note_Avis_Move2Cloud_CADA V1.pdf]]

**Document de référence :** *Note_Avis_Move2Cloud_CADA.pdf* — Paradigm, août 2026.