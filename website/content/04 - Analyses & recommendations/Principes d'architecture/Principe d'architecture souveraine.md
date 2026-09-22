# Principes d’architecture souveraine

> [!info] Source et statut
> Synthèse critique de [[Principes d'Architecture - Rapport V1.pdf]], *Principes d’architecture de la souveraineté numérique. Cadre de référence pour l’évaluation et la maîtrise des dépendances numériques critiques*, Michel Van Raemdonck, Digital Transformation, juin 2026.
>
> Le document porte le numéro de version **0.1**. Il doit être considéré comme une proposition de cadre en cours de construction, et non comme une doctrine régionale validée.

[[Principes d'Architecture - Rapport V1.pdf]]
[[Principes d'Architecture - Présentation V1.pdf]]

## Résumé du rapport

Le rapport définit la souveraineté numérique comme la capacité d’une organisation publique à conserver une maîtrise suffisante de ses données, services, infrastructures et décisions numériques pour exercer durablement ses missions. Il ne vise ni l’indépendance totale ni l’autarcie technologique, mais une **maîtrise graduée des dépendances**, adaptée à la criticité des usages.

Sa doctrine peut être résumée par le principe **« as sovereign as necessary »** : identifier les dépendances, réduire celles qui créent un risque disproportionné et accepter explicitement les risques résiduels lorsque leur suppression n’est ni réaliste ni justifiée. La souveraineté devient ainsi un critère d’arbitrage au même titre que la sécurité, le coût, la performance, la conformité et la continuité de service.

Le rapport distingue quatre niveaux de maîtrise :

- **Données** : localisation, juridiction applicable, contrôle des accès, maîtrise des clés de chiffrement, traçabilité et auditabilité.
- **Services et applications** : portabilité, interopérabilité, standards ouverts, modularité et capacité de substitution.
- **Infrastructures** : conditions d’hébergement et d’exploitation, dépendance aux opérateurs, diversification et stratégie de sortie.
- **Décision** : capacité de la Région à arbitrer, négocier, auditer et faire évoluer ses solutions sans contrainte excessive d’un tiers.

### Principes proposés

| Domaine | Principes principaux |
|---|---|
| Données | Qualifier leur sensibilité ; analyser localisation et juridiction ; garder la maîtrise des identités, accès, clés et journaux ; permettre un audit indépendant. |
| Applications | Rechercher la portabilité dès la conception ; utiliser des formats et standards ouverts ; documenter les interfaces ; découpler les composants ; limiter le verrouillage fournisseur. |
| Infrastructures | Renforcer le contrôle juridique pour les traitements critiques ; prévoir une stratégie de sortie documentée et testable ; diversifier lorsque cela apporte une réduction effective du risque ; envisager la mutualisation régionale. |
| Sécurité et résilience | Intégrer la cybersécurité dès la conception ; assurer supervision, détection et réponse ; organiser la continuité et la reprise en tenant compte des dépendances externes. |
| Contrats et achats | Rendre la réversibilité explicite ; imposer une portabilité exploitable des données ; encadrer les coûts et délais de sortie ; documenter les juridictions et risques extraterritoriaux ; exiger API, formats et interfaces suffisamment ouverts. |
| Gouvernance | Répartir les responsabilités entre pilotage stratégique, architecture, sécurité, achats et exploitation ; intégrer les critères de souveraineté en amont des projets ; tracer les arbitrages et réviser périodiquement les principes. |

Le cadre d’évaluation classe une solution sur trois niveaux de maîtrise, faible, partielle ou renforcée, selon cinq dimensions : données, applications, infrastructures, sécurité et résilience, maîtrise décisionnelle et contractuelle. Cette évaluation doit être croisée avec trois niveaux de criticité afin d’identifier les mesures de mitigation, les alternatives ou les risques à faire accepter par l’instance compétente.

## Analyse critique

### Points intéressants à conserver

1. **Une définition pragmatique de la souveraineté.** Le refus d’une autonomie absolue est cohérent avec la définition retenue par le chantier 12 dans [[Souveraineté Numérique]]. Il permet de concentrer l’effort sur les dépendances critiques plutôt que sur l’origine nationale de chaque composant.

2. **La proportionnalité selon la criticité.** Le principe d’exigences différenciées évite d’appliquer les mêmes contraintes à un outil banal et à un service public essentiel. Il rejoint l’approche segmentée proposée dans la note Move2Cloud/CADA.

3. **La souveraineté comme capacité d’arbitrage future.** Le rapport ne réduit pas la souveraineté à la localisation des données. Il met utilement l’accent sur la liberté de décision, la réversibilité, la substituabilité et la maîtrise contractuelle.

4. **Le lien entre architecture et achats publics.** Les exigences techniques n’ont d’effet que si elles sont traduites en clauses évaluables et opposables. Les propositions sur les formats d’export, les métadonnées, les API, les responsabilités et les coûts de sortie constituent une base concrète.

5. **La distinction entre extraction et portabilité réelle.** Une copie brute des données ne suffit pas si elle ne peut pas être comprise et réutilisée. Cette distinction doit être conservée et étendue aux configurations, historiques, règles métier, identités et dépendances nécessaires à la reprise du service.

6. **La prise en compte du risque de concentration.** L’évaluation d’une solution ne doit pas rester isolée : plusieurs choix acceptables séparément peuvent produire une dépendance systémique envers un même fournisseur, cloud, système d’identité ou socle technique.

7. **La traçabilité des risques acceptés.** La documentation des hypothèses, mesures de mitigation, responsables et décisions d’acceptation est indispensable pour éviter que des dépendances temporaires deviennent permanentes par défaut.

8. **La checklist “souveraineté by design”.** Elle fournit une bonne base de contrôle en amont des projets, sous réserve de la rendre vérifiable et de l’associer à des livrables, des responsables et des critères de décision.

### Limites, incohérences et angles morts

1. **Un cadre inachevé.** Les chapitres consacrés aux cas d’usage, à la situation actuelle, à l’architecture cible, aux jalons et aux indicateurs sont uniquement des titres. Le glossaire, les références réglementaires et les modèles de clauses sont également absents. Le rapport décrit donc une intention, mais pas encore une trajectoire applicable.

2. **Une grille trop qualitative pour arbitrer.** Les trois niveaux de maîtrise ne définissent ni preuves attendues, ni seuils, ni critères éliminatoires, ni méthode d’agrégation. Une faiblesse critique sur une seule dimension pourrait être masquée par une appréciation globale favorable. La grille ne doit pas être utilisée comme un score validé en l’état.

3. **Une portée juridique imprécise.** La formule « hébergement sous contrôle juridique européen » n’est pas définie. La localisation dans l’Union européenne ne neutralise pas nécessairement l’exposition extraterritoriale d’un fournisseur contrôlé depuis un pays tiers. L’analyse doit distinguer au minimum le lieu de stockage et de traitement, le contrôle capitalistique, les juridictions applicables, les accès d’administration et de support, les sous-traitants et les voies de recours.

4. **Une définition dite “non politique” discutable.** Le rapport propose en réalité un cadrage opérationnel, mais les choix de souveraineté publique ont nécessairement des dimensions politiques, industrielles, budgétaires et géopolitiques. Il est préférable de parler de **définition opérationnelle** plutôt que de définition non politique.

5. **Des dimensions importantes sous-traitées.** Les compétences internes ne sont citées que comme une dépendance à analyser. Les risques économiques, la dépendance aux licences, la chaîne d’approvisionnement, le matériel, les micrologiciels, les composants logiciels, les capacités d’exploitation et le transfert de connaissances ne deviennent pas de véritables principes d’architecture. Or le chantier retient aussi les dimensions économique, d’approvisionnement et de compétences.

6. **Un chevauchement avec la sécurité et la résilience.** Le rapport distingue correctement ces notions de la souveraineté, puis les réintroduit comme une dimension de son score. Elles devraient plutôt être traitées comme des exigences transversales ou des prérequis, afin d’éviter de compter deux fois les mêmes garanties et de faire croire qu’un système sécurisé est nécessairement souverain.

7. **Des leviers présentés sans conditions de succès suffisantes.** Le multi-cloud peut accroître les coûts, la complexité et les besoins en compétences sans produire de réversibilité réelle. La mutualisation peut renforcer la capacité régionale, mais aussi concentrer un point de défaillance ou un verrouillage commun. Ces options doivent être évaluées par rapport à une menace et à un scénario de sortie précis, pas considérées comme souveraines par nature.

8. **Une portabilité potentiellement surprescrite.** Rendre chaque composant interchangeable peut dégrader les coûts, les délais ou les performances. Il faut préciser quels actifs doivent être portables par défaut, notamment les données, interfaces, configurations et composants critiques, et où une dépendance propriétaire reste acceptable après arbitrage documenté.

9. **Une maîtrise des clés insuffisamment qualifiée.** Le contrôle des clés est utile, mais ne garantit pas à lui seul la confidentialité si le fournisseur peut accéder aux données en clair pendant leur traitement ou contrôler le plan d’administration. Les exigences doivent découler d’un modèle de menace et distinguer stockage, transit, traitement et administration.

10. **Des lacunes sur le cycle complet des données.** Les sauvegardes, copies techniques, journaux, métadonnées, télémétrie, effacement vérifiable, données utilisées pour l’entraînement de modèles et fin de contrat ne sont pas traités explicitement.

11. **Des prescriptions non opposables.** Le texte emploie principalement « devrait » sans hiérarchie entre obligations, recommandations et exceptions. Il manque un mécanisme de dérogation, une autorité d’acceptation, une durée de validité des exceptions et une fréquence de réévaluation.

12. **Une absence de validation externe.** La version analysée ne fournit aucune référence réglementaire, méthodologique ou retour d’expérience permettant d’étayer les seuils et principes proposés. Leur cohérence avec le droit des marchés publics, le RGPD, NIS2 et les futurs cadres européens doit être vérifiée séparément.

## Intégration recommandée dans l’analyse globale

### À retenir

- La souveraineté comme **maîtrise proportionnée de dépendances identifiées**, et non comme autonomie totale.
- La criticité des missions, données et services comme point de départ de l’évaluation.
- La capacité de décision et de sortie comme résultat recherché.
- La réversibilité effective, testée et financée, au-delà du simple export de données.
- Les standards ouverts, interfaces documentées et architectures modulaires comme leviers, non comme fins en soi.
- L’intégration des exigences dans l’architecture, les marchés, les contrats et la gouvernance.
- L’analyse du cumul et de la concentration des dépendances à l’échelle régionale.
- La traçabilité des arbitrages et la révision périodique des risques acceptés.

### À retenir sous réserve de reformulation ou de compléments

- Le contrôle européen, après définition précise de ses dimensions juridiques, capitalistiques, techniques et opérationnelles.
- Le multi-cloud et le multi-fournisseur, uniquement lorsqu’ils réduisent une dépendance démontrée et restent exploitables.
- La mutualisation régionale, si elle évite de créer une concentration excessive ou un point unique de défaillance.
- La maîtrise des clés de chiffrement, à compléter par l’analyse des accès au traitement et au plan de contrôle.
- La grille à trois niveaux, après ajout de preuves attendues, critères bloquants, responsables, règles d’exception et correspondance explicite avec les niveaux de criticité.

### À ne pas reprendre comme conclusions établies

- L’idée que l’hébergement en Europe suffit à garantir la maîtrise juridique.
- L’idée qu’une architecture multi-cloud, mutualisée, modulaire ou fondée sur des standards ouverts est souveraine par construction.
- La grille d’évaluation comme méthode de notation validée ou comme outil suffisant pour décider.
- Les chapitres 8 et 9, les indicateurs, les clauses contractuelles et les références comme contenus disponibles : ils sont seulement annoncés.
- L’affirmation implicite que le cadre couvre toutes les dimensions de la souveraineté : les compétences, l’économie et la chaîne d’approvisionnement restent à intégrer.
- Toute interprétation de cette version 0.1 comme une décision, une norme ou une cible d’architecture déjà approuvée par la Région.

## Conclusion

Le rapport constitue une **bonne base doctrinale** pour inscrire la souveraineté dans les décisions d’architecture et les achats IT. Ses apports les plus solides sont la proportionnalité, la réversibilité, l’analyse multicouche et la traçabilité des arbitrages. Il n’est toutefois pas encore un référentiel opérationnel : il doit être complété par des définitions vérifiables, une méthode d’évaluation robuste, des exigences selon la criticité, des clauses types, des responsabilités précises et une trajectoire de mise en œuvre adaptée aux actifs et compétences de la Région.

Voir également [[Rapport OCTO - Souveraineté Numérique]] pour le rôle des standards ouverts, des communs numériques et des compétences dans la maîtrise des dépendances.
