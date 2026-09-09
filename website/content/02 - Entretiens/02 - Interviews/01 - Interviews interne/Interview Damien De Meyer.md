---
type:
  - Interview
published:
author: Etudiants SOLVAY
---

# 1 — Présentation personnelle et rôle

## Pouvez-vous vous présenter brièvement — votre rôle chez Paradigm et votre périmètre de responsabilité ?

Product Manager pour les produits d'hébergement de Paradigm. Couvre trois types de services :

### Hébergement web

Equivalent de ce que propose OVH. Paradigm gère toute la pile technologique sous-jacente, y compris le système d'exploitation. Le client dispose de droits administrateurs pour installer ses applications ou sites web comme il le souhaite. C'est plus souple et plus puissant qu'un hébergement web classique, et sécurisé.

### VPS (Virtual Private Server)

Un serveur dédié pour le client, avec la même logique de gestion complète par Paradigm de la couche sous-jacente.

### VDC (Virtual Data Center)

C'est le cœur de business de Paradigm. Concrètement, c'est une salle serveur virtuelle dans laquelle on alloue des ressources à un client — CPU, RAM, stockage — et le client construit son infrastructure virtuelle comme il l'entend. Cela lui permet soit de décommissionner une partie ou toute son infrastructure physique, soit d'avoir une redondance chez Paradigm en cas de panne chez lui. Le datacenter étant réparti sur deux sites distincts, le client peut aussi choisir où placer ses machines virtuelles pour obtenir une redondance multi-sites, en plus de la redondance par rapport à son propre site.


# 2 — Mission du datacenter

## Comment décririez-vous en quelques mots la mission du datacenter de Paradigm aujourd'hui ?

L'avantage principal du VDC par rapport à des concurrents comme Azure : **le datacenter est régional, donc complètement isolé des infrastructures privées ou étrangères. Les données sont stockées dans un environnement souverain**. Le modèle tarifaire est aussi un différenciateur majeur : là où Azure a une composante variable selon le trafic (avec parfois des mauvaises surprises), Paradigm propose un modèle totalement prédictible. Le client sait exactement ce qu'il paiera en fonction des ressources commandées, ce qui facilite la planification budgétaire annuelle — une bonne pratique pour les dépenses publiques.

Sur la mission plus large : dès qu'il y a des données à caractère privé, les obligations RGPD s'appliquent, et **les clients font davantage confiance à une structure locale et dédiée**. Un cloud privé européen offre des garanties contractuelles: les applications ont des failles de sécurité — organisées ou non — qui peuvent exposer des données. C'est un sujet très sensible pour les administrations régionales.

Il souligne aussi le contexte géopolitique actuel : on ne peut plus accorder une confiance aveugle même à nos alliés. Cela renforce la pertinence d'un hébergement local, même si une stratégie politique permettant une vraie souveraineté reste difficile à construire — on reste lié à Microsoft et à des applicatifs étrangers dont on ne maîtrise pas le code source.

Sur les enjeux de sécurité : Paradigm fait constamment l'objet d'attaques, principalement d'origine étrangère (mais avec les VPN et les opérations sous faux drapeau, l'attribution est incertaine). **À ce stade, aucun vol de données n'a été constaté**. La protection est de bon niveau, mais personne n'est à l'abri d'une faille. Il mentionne aussi l'IA comme facteur émergent dans la cybersécurité — tant en attaque qu'en défense.


# 3 - Souveraineté numérique : perception et enjeux


## Quand vous entendez « souveraineté numérique », qu'est-ce que cela évoque concrètement dans votre métier au quotidien ?


Souveraineté rime avec local. C'est la capacité à héberger et traiter des données localement, sans les confier à des acteurs privés étrangers aux ambitions commerciales. En tant que service public, l'objectif est de permettre l'utilisation de ressources de manière souveraine — ce qui implique d'éviter de dépendre de moteurs ou de modèles chinois, américains ou même français.

Cependant une souveraineté totale est illusoire dans le contexte actuel : on reste liés à Microsoft et à des applicatifs étrangers dont le code source n'est pas maîtrisé. Ce n'est pas une raison de ne pas progresser sur le sujet, mais il faut être réaliste.

La souveraineté est aussi une question de réputation : exemple les piratages d'organismes publics français qui font régulièrement la une — un risque de réputation et de confiance publique que les administrations bruxelloises ne peuvent pas se permettre.


# 4 - Services souverains : potentiel et faisabilité

## Comment voyez-vous l'opportunité d'une infrastructure IA souveraine ? Quels seraient les cas d'usage cibles ?

la souveraineté numérique en matière d'IA passe par le local. Il milite activement en interne pour qu'un investissement soit fait sur ces technologies afin de ne plus dépendre de moteurs chinois, américains ou français — qui restent des sociétés privées aux ambitions commerciales, incompatibles avec les exigences d'un service public.

Sur la faisabilité économique : c'est là que le bât blesse. Convaincre sur le besoin ne pose pas de problème — trouver les fonds, si. Un investissement minimal pour démarrer à petite échelle représente environ 200 000 euros. Or Paradigm n'est pas en capacité de demander de tels fonds dans le contexte budgétaire actuel.

Sa stratégie pour contourner ce frein : travailler conjointement avec le responsable du datacenter pour identifier plusieurs cas d'usage internes à Paradigm qui justifieraient un investissement — améliorer les processus internes, démontrer la valeur ajoutée, puis dédier le surplus de ressources à des clients externes pour monter en puissance progressivement. Un modèle d'amortissement par l'usage interne d'abord.

Sur le groupe exploratoire IA constitué en interne : il existe, mais les expertises présentes ne couvrent pas tous les aspects — notamment les développeurs d'applications ne sont pas représentés. Les managers sollicités pour des cas d'usage restent à un niveau très basique, sans conscience de la valeur qu'on pourrait tirer de l'IA. la dimension technique du développement est sous-représentée dans les instances de décision.

Sur les compétences disponibles en interne : il y a des profils techniques, mais pas d'experts IA. Les équipes techniques sont surtout orientées maintien et amélioration de l'existant (opérationnel), pas vers l'innovation ou de nouveaux cas d'usage. À la marge, certaines applications s'appuient sur de l'IA pour quelques fonctionnalités, mais ce n'est pas une démarche systématique ou un mot d'ordre de direction.

Paradigm est dans une architecture réactive, pas proactive. Ce n'est que son avis personnel, dit-il — mais c'est un avis affirmé.

Sur la concurrence : les hyperscalers (Microsoft, Amazon) ont des économies d'échelle incomparables. Sur le modèle financier, les solutions clés en main (OPEX) passent plus facilement que les investissements en propre (CAPEX). Sur 5 ans, l'investissement en propre n'est pas forcément plus cher — mais ce n'est pas comme ça qu'on raisonne dans le secteur public.

Sur l'avantage régional il y a un avantage à être un acteur régional — mais à condition d'agir. « si on est trop passif par rapport à l'IA, c'est l'IA qui va nous utiliser, pas l'inverse. » Il faut anticiper. Mais sans go politique, même une vision interne claire ne suffira pas.


# 5 - Contraintes opérationnelles et réalisme stratégique

## Quelles sont les principales contraintes qui limitent le développement de nouveaux services souverains ?

Damien identifie plusieurs niveaux de contraintes, qui se cumulent :

- Budget : c'est la contrainte dominante. Paradigm vient d'atteindre l'équilibre budgétaire après des années d'effort de redressement suite à des choix stratégiques difficiles de l'ancienne direction. Mais on lui demande encore d'économiser 10% du budget total. Résultat : « on est quasi à l'os. » Il n'est plus possible de simplement faire moins — il faudrait faire mieux, mais on n'en a pas l'occasion. Le politique attend des économies, pas de l'innovation.
    
- Vision à court terme imposée par le cycle politique : les projets d'infrastructure souveraine se pensent sur 10, 15, 20 ans. Les mandats politiques sont beaucoup plus courts. Il n'y a plus de grands plans d'investissement comme il en existait au siècle dernier. Les décisions se prennent à la petite semaine, budgétairement.
    
- Compétences : il y a des profils techniques en interne, mais pas d'experts IA. Les équipes sont orientées maintien de l'existant, pas innovation. Pas de mot d'ordre de direction pour intégrer l'IA de manière systématique.
    
- Complexité de gouvernance : naviguer entre 6 gouvernements en Belgique est extrêmement difficile. Même en interne chez Paradigm, ne pas toujours connaître toutes les procédures. « Je fais parfois de l'archéologie. »
    
- Manque de synergie régionale : il y a de vraies compétences dans la région, mais elles sont éparpillées. Les clients des administrations ont souvent leurs propres prestataires, qui travaillent de manière non uniforme, sans toujours respecter les règles de sécurité minimales, laissant des failles importantes. La mutualisation régionale reste insuffisante.


## Y a-t-il des niches où Paradigm a un avantage structurel ?

oui, il y a un avantage régional — mais qu'il est insuffisamment exploité et promu. Le datacenter régional, sa création en son temps, a été un geste politique fort. Mais depuis, il n'y a pas assez de promotion politique pour inciter les services publics à utiliser les services de Paradigm.

Résultat : les clients (administrations, communes) sont trop libres de choisir des solutions sur mesure, en pensant à leur propre échelle. Ils réinventent la roue, ont chacun leur prestataire qui ne travaille pas de manière uniforme, laisse des failles de sécurité. Il y a une compétence réelle dans la région — mais pas de synergie.

le positionnement de Paradigm devrait être complémentaire aux hyperscalers, pas concurrent frontal. L'avantage structurel est la proximité, la confiance, la connaissance du contexte public bruxellois, et la prédictibilité tarifaire. Ce que les hyperscalers ne peuvent pas offrir à ce niveau de proximité.

## Des initiatives comme l'EDIC ou les plans numériques régionaux vous semblent-ils des opportunités concrètes ?

les budgets sont gérés « à la petite semaine », il manque d'ambition car les échéances politiques sont plus courtes que les projets (10-15-20 ans). Des projets qui auraient dû commencer il y a cinq ans ne sont pas encore lancés.


# 6 - Clôture

## Si vous deviez identifier une priorité absolue pour Paradigm en matière de souveraineté numérique, quelle serait-elle ?

- Des investissements avec une vision à long terme : c'est ce qui manque le plus. Pas des économies supplémentaires, mais des vrais investissements stratégiques assumés dans la durée, même s'ils ont été initiés par des gouvernements précédents.
    
- Une volonté politique de promouvoir activement le datacenter régional : le datacenter existe, c'est un actif précieux. Mais il n'est pas assez promu. Les administrations clientes devraient être incitées — voire obligées dans certains cas — à utiliser les services de Paradigm plutôt que de réinventer la roue chacune de leur côté avec leurs propres prestataires.


## Des personnes dans l'organisation que vous conseilleriez de rencontrer ?

Pour une vision stratégique : la direction de l'entreprise et/ou le service communication. Ils ont des dossiers déjà complets sur certaines thématiques et peuvent donner la vision du top management et du ministère de tutelle. La directrice générale elle est là depuis plusieurs législatures et peut offrir une perspective longue.

Pour les aspects sécurité et technique : peut mettre en relation avec des profils plus techniques. Il précise cependant que la souveraineté est avant tout une question stratégique et de vision — les aspects sécurité sont un sous-ensemble, pas le tout.



Chantier 12 - Souveraineté Numérique de la RBC -  Confidentiel - usage interne

