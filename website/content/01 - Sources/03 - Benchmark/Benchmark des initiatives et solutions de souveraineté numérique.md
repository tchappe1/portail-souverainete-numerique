---
type:
  - Analyse
GT: GT 4
---

## 🎯 Objet

Le GT4 a pour objectif d'identifier et d'analyser les **stratégies, initiatives, solutions et retours d'expérience** en matière de souveraineté numérique, afin d'en tirer des enseignements applicables à la Région de Bruxelles-Capitale et à Paradigm.

Cette fiche constitue le **point de départ du benchmark réalisé par les étudiants de Solvay/ULB en juin 2026**.

Elle est destinée à être enrichie et actualisée par le GT4 au fur et à mesure de ses travaux.

> **Principe :** ne pas chercher uniquement des « solutions souveraines », mais comprendre ce que d'autres organisations ont concrètement fait, pourquoi elles l'ont fait, avec quels résultats, quelles difficultés et ce qui pourrait être transposable à Bruxelles.

---

# 1. Périmètre du benchmark

Le benchmark initial couvre plusieurs dimensions de la souveraineté numérique :

- dépendances aux fournisseurs ;
- infrastructures et cloud ;
- systèmes d'exploitation ;
- bases de données ;
- messagerie et outils collaboratifs ;
- ERP et logiciels métier ;
- IA ;
- certification et qualification des infrastructures ;
- coopération et écosystèmes européens.

Les références étudiées sont principalement européennes, avec quelques exemples internationaux utilisés comme points de comparaison ou signaux d'alerte.

---

# 2. Premières pistes identifiées pour Paradigm

## 2.1 Cartographier les dépendances numériques

**Priorité : 1 — urgent**  
**Horizon proposé : 0–3 mois**

### Proposition

Produire un inventaire des dépendances numériques, fournisseur par fournisseur et juridiction par juridiction, avec un niveau de risque associé.

### Références

**Schleswig-Holstein — Allemagne**
- création d'un Open Source Program Office (OSPO) dédié ;
- objectif : cartographier l'existant et piloter la stratégie.

**France — Décret DINUM, 8 avril 2026**
- chaque ministère doit formaliser un plan de réduction des dépendances ;
- six axes identifiés : poste de travail, outils collaboratifs, antivirus, IA, bases de données et équipements réseau.

### Enseignement pour Paradigm

La cartographie est présentée comme un **préalable à toute décision stratégique**.

Le benchmark suggère de s'inspirer du modèle OSPO avec une petite équipe dédiée plutôt qu'une restructuration importante.

### À approfondir par GT4

- Vérifier les expériences citées.
- Identifier d'autres administrations ayant réalisé une cartographie comparable.
- Identifier les méthodes/outils utilisés.
- Comparer les périmètres et critères de risque.
- Évaluer la transposabilité à Paradigm.

---

## 2.2 Anticiper la sortie de VMware / Broadcom

**Priorité : 1 — urgent**  
**Horizon proposé : 0–6 mois**

### Proposition

Analyser les alternatives à VMware, notamment **Proxmox VE**, et préparer un plan de migration avant le renouvellement du contrat.

### Références

Plusieurs Länder allemands et administrations néerlandaises auraient migré vers Proxmox VE après les évolutions tarifaires consécutives au rachat de VMware par Broadcom.

### Enseignement pour Paradigm

Le benchmark souligne que le risque est d'abord **budgétaire**, mais qu'il constitue également une question de dépendance fournisseur.

L'idée proposée est de tester Proxmox sur un environnement non critique avant une éventuelle migration.

### À approfondir par GT4

- Identifier précisément les administrations ayant migré.
- Documenter les motivations.
- Comparer VMware / Proxmox / autres alternatives.
- Identifier les coûts et difficultés de migration.
- Vérifier les conditions dans lesquelles ces migrations sont réellement pertinentes pour Paradigm.

---

## 2.3 Piloter une messagerie souveraine

**Priorité : 2 — moyen terme**  
**Horizon proposé : 6–12 mois**

### Proposition

Tester une alternative aux outils Microsoft sur un périmètre limité d'administrations sensibles.

Solutions citées :
- Nextcloud ;
- Open-Xchange.

### Références

**Autriche — Ministère de l'Intérieur**
- migration vers Nextcloud en remplacement de SharePoint et Teams ;
- migration annoncée comme réalisée en quatre mois.

**Schleswig-Holstein — Allemagne**
- migration de 44 000 boîtes mail d'Exchange vers Open-Xchange + Thunderbird ;
- Nextcloud utilisé en remplacement de SharePoint.

### Enseignement pour Paradigm

Le benchmark recommande une approche par **pilote limité**, plutôt qu'une migration généralisée.

L'existence de l'infrastructure Sibelga est présentée comme un avantage potentiel pour Paradigm.

### À approfondir par GT4

- Vérifier les architectures réellement mises en œuvre.
- Identifier les coûts.
- Documenter les conditions de réussite.
- Évaluer les fonctionnalités perdues / conservées.
- Identifier les freins utilisateurs et organisationnels.
- Identifier d'autres expériences européennes.

---

## 2.4 Migrer progressivement Windows / SQL Server vers Linux / PostgreSQL

**Priorité : 2 — moyen terme**  
**Horizon proposé : 6–18 mois**

### Proposition

Sur les environnements non critiques :
- remplacer SQL Server par PostgreSQL ou une alternative open source ;
- migrer progressivement les serveurs Windows vers Linux.

### Référence

**Gendarmerie française — GendBuntu**
- migration progressive vers Ubuntu Linux ;
- démarche réalisée sur une longue période ;
- migration par couches et au rythme du renouvellement matériel.

**France — Décret DINUM**
- plan de migration hors Microsoft incluant notamment les systèmes d'exploitation et bases de données.

### Enseignement pour Paradigm

Éviter le **« big bang »** et privilégier une migration progressive.

Le benchmark identifie cette piste comme potentiellement plus facilement réalisable qu'une migration complète de la bureautique.

### À approfondir par GT4

- Identifier les cas comparables dans les administrations.
- Comparer les solutions Linux retenues.
- Documenter les coûts de migration et d'exploitation.
- Identifier les applications qui constituent des blocages.
- Examiner les impacts sur les compétences internes.

---

## 2.5 Lancer un DBaaS souverain

**Priorité : 2 — moyen terme**  
**Horizon proposé : 12–18 mois**

### Proposition

Proposer aux administrations bruxelloises un service de **Database as a Service (DBaaS)** administré et hébergé sur Sibelga, avec garanties de localisation et de juridiction.

### Références

**Ville de Lyon — TNO**
- suite de services comprenant notamment Nextcloud, OnlyOffice et Jitsi ;
- hébergement dans des datacenters régionaux ;
- mutualisation entre collectivités.

**France — LaSuite numérique**
- modèle reposant notamment sur la mutualisation entre administrations.

### Enseignement pour Paradigm

Le rôle mutualisateur de Paradigm est présenté comme un **atout spécifique**.

Un service de base de données souverain pourrait combiner :
- mutualisation ;
- infrastructure régionale ;
- maîtrise des données ;
- réduction des dépendances.

### À approfondir par GT4

- Identifier les offres DBaaS existantes.
- Benchmark des technologies.
- Comparer les modèles économiques.
- Identifier les exigences de sécurité et d'exploitation.
- Évaluer la demande potentielle des administrations régionales.

---

## 2.6 Explorer les alternatives aux ERP propriétaires

**Priorité : 2 — moyen terme**  
**Horizon proposé : 12–24 mois**

### Proposition

Explorer le remplacement progressif de certains ERP propriétaires par des alternatives souveraines/open source.

### Référence

**Odoo — Belgique**
- ERP open source ;
- fondé et hébergé en Belgique ;
- large couverture fonctionnelle ;
- possibilité de déploiement sur une infrastructure propre.

### Enseignement pour Paradigm

Les ERP constituent un **angle mort potentiel des stratégies de souveraineté numérique** : ils concentrent des fonctions métier importantes et des données sensibles.

Un scénario combinant :
- logiciel open source ;
- hébergement régional ;
- maîtrise des données

pourrait constituer une piste intéressante.

### À approfondir par GT4

- Identifier les ERP utilisés dans la Région.
- Identifier les dépendances associées.
- Comparer Odoo et d'autres alternatives.
- Identifier les coûts de migration.
- Identifier les administrations ayant réalisé ce type de migration.

---

## 2.7 Développer une infrastructure IA souveraine

**Priorité : 3 — long terme**  
**Horizon proposé : 18–36 mois**

### Proposition

Déployer une infrastructure permettant aux administrations d'exécuter localement des modèles d'IA open weight, sans transmettre les données à des clouds américains.

Modèles cités dans la V1 :
- LLaMA ;
- Mistral.

### Références

**France — Mistral / Outscale SecNumCloud**

**DC-EDIC**
- consortium européen consacré au développement d'infrastructures IA souveraines ;
- Belgique observatrice selon le benchmark.

### Enseignement pour Paradigm

Le benchmark identifie l'IA souveraine comme un **potentiel axe stratégique majeur**.

Un cas d'usage cité est l'utilisation d'agents IA pour FixMyStreet, notamment pour la reconnaissance d'objets et l'anonymisation RGPD.

### À approfondir par GT4

- Identifier les infrastructures IA existantes en Europe.
- Comparer les modèles open weight.
- Évaluer les besoins GPU.
- Identifier les cas d'usage régionaux.
- Examiner les coûts et modèles économiques.
- Examiner les exigences de sécurité et de certification.

---

## 2.8 Se positionner comme opérateur certifié

**Priorité : 3 — long terme**  
**Horizon proposé : 24–36 mois**

### Proposition

Étudier l'obtention d'une certification de souveraineté reconnue pour permettre à Paradigm de répondre aux besoins d'hébergement de données sensibles.

### Référence

**France — SecNumCloud / ANSSI**
- qualification utilisée pour des environnements sensibles ;
- OVHcloud et Outscale cités comme acteurs qualifiés dans le benchmark.

**Danemark — Digital Suveraenitet**
- stratégie nationale documentée ;
- financement associé à la stratégie.

### Enseignement pour Paradigm

Le benchmark identifie une possibilité de **positionnement stratégique de Paradigm** sur les marchés publics sensibles.

### À approfondir par GT4

- État des certifications européennes.
- Évolution du référentiel EUCS.
- Positionnement belge.
- Conditions de certification.
- Coût et durée.
- Intérêt réel pour Paradigm.

---

## 2.9 Rejoindre les réseaux européens

**Priorité : 3 — long terme**  
**Horizon proposé : 36 mois et +**

### Réseaux cités

- DC-EDIC ;
- ISIT ;
- INR.

### Références

**DC-EDIC**
- consortium européen autour des infrastructures numériques open source transfrontalières.

**Digital Wallonia 2025–2029 + Athumi**
- initiatives relatives à la gouvernance des données régionales.

### Enseignement pour Paradigm

Le benchmark souligne qu'une stratégie de souveraineté ne peut pas être pensée uniquement à l'échelle bruxelloise.

La coopération européenne peut permettre :
- d'accéder à des compétences ;
- de partager des briques open source ;
- de participer à des projets communs ;
- d'accéder à certains financements européens.

### À approfondir par GT4

- Cartographier les réseaux pertinents.
- Identifier les conditions d'adhésion.
- Identifier les projets auxquels Paradigm pourrait contribuer.
- Identifier les financements accessibles.
- Identifier les partenaires belges et européens potentiels.

---

# 3. Signal d'alerte : le cas iranien

Le benchmark utilise également le cas iranien comme **scénario extrême de dépendance numérique**.

Depuis les sanctions américaines, plusieurs services numériques américains sont devenus inaccessibles en Iran.

Le cas est présenté non comme un scénario directement transposable à Bruxelles, mais comme une illustration d'un risque :

> une organisation fortement dépendante de fournisseurs externes peut se retrouver sans solution de secours lorsqu'une rupture géopolitique ou réglementaire survient.

### Enseignement

L'intérêt d'une stratégie de souveraineté est notamment de disposer d'un **plan de secours avant que la dépendance ne devienne critique**.

### À traiter avec prudence

Le cas iranien doit être conservé comme **signal d'alerte / scénario extrême**, et non comme une prévision ou un benchmark directement comparable à la situation européenne.




## 📎 Sources

[[Chantier 12 - Souveraineté Numérique - Benchmark V1 - juin 2026.docx]]
