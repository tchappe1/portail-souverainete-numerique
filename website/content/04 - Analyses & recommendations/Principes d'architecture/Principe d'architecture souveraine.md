

> [!info] Source et statut
> [[Principes d'Architecture - Rapport V1.pdf]], *Principes d’architecture de la souveraineté numérique. Cadre de référence pour l’évaluation et la maîtrise des dépendances numériques critiques*, Michel Van Raemdonck, Digital Transformation, juin 2026.


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


### Points clés

1. **Une définition pragmatique de la souveraineté.** Le refus d’une autonomie absolue est cohérent avec la définition retenue par le chantier 12 dans [[Souveraineté Numérique]]. Il permet de concentrer l’effort sur les dépendances critiques plutôt que sur l’origine nationale de chaque composant.

2. **La proportionnalité selon la criticité.** Le principe d’exigences différenciées évite d’appliquer les mêmes contraintes à un outil banal et à un service public essentiel. Il rejoint l’approche segmentée proposée dans la note Move2Cloud/CADA.

3. **La souveraineté comme capacité d’arbitrage future.** Le rapport ne réduit pas la souveraineté à la localisation des données. Il met utilement l’accent sur la liberté de décision, la réversibilité, la substituabilité et la maîtrise contractuelle.

4. **Le lien entre architecture et achats publics.** Les exigences techniques n’ont d’effet que si elles sont traduites en clauses évaluables et opposables. Les propositions sur les formats d’export, les métadonnées, les API, les responsabilités et les coûts de sortie constituent une base concrète.

5. **La distinction entre extraction et portabilité réelle.** Une copie brute des données ne suffit pas si elle ne peut pas être comprise et réutilisée. Cette distinction doit être conservée et étendue aux configurations, historiques, règles métier, identités et dépendances nécessaires à la reprise du service.

6. **La prise en compte du risque de concentration.** L’évaluation d’une solution ne doit pas rester isolée : plusieurs choix acceptables séparément peuvent produire une dépendance systémique envers un même fournisseur, cloud, système d’identité ou socle technique.

7. **La traçabilité des risques acceptés.** La documentation des hypothèses, mesures de mitigation, responsables et décisions d’acceptation est indispensable pour éviter que des dépendances temporaires deviennent permanentes par défaut.

8. **La checklist “souveraineté by design”.** Elle fournit une bonne base de contrôle en amont des projets, sous réserve de la rendre vérifiable et de l’associer à des livrables, des responsables et des critères de décision.



### À retenir

- La souveraineté comme **maîtrise proportionnée de dépendances identifiées**, et non comme autonomie totale.
- La criticité des missions, données et services comme point de départ de l’évaluation.
- La capacité de décision et de sortie comme résultat recherché.
- La réversibilité effective, testée et financée, au-delà du simple export de données.
- Les standards ouverts, interfaces documentées et architectures modulaires comme leviers, non comme fins en soi.
- L’intégration des exigences dans l’architecture, les marchés, les contrats et la gouvernance.
- L’analyse du cumul et de la concentration des dépendances à l’échelle régionale.
- La traçabilité des arbitrages et la révision périodique des risques acceptés.


## Conclusion

Le rapport constitue une **bonne base doctrinale** pour inscrire la souveraineté dans les décisions d’architecture et les achats IT. Ses apports les plus solides sont la proportionnalité, la réversibilité, l’analyse multicouche et la traçabilité des arbitrages. 

Voir également [[Rapport OCTO - Souveraineté Numérique]] pour le rôle des standards ouverts, des communs numériques et des compétences dans la maîtrise des dépendances.
