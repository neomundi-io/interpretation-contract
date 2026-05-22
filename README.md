# Interpretation Contract

## Version française de travail

Notes méthodologiques publiques sur les frontières d’interprétation des signaux, métriques et décisions de gouvernance runtime NeoMundi.

Ce dépôt documente le contrat d’interprétation applicable aux signaux produits ou exposés dans le cadre NeoMundi.

Il ne divulgue pas les formules propriétaires, les coefficients de production, les pondérations internes, les seuils, les règles décisionnelles complètes, ni les mécanismes d’inférence runtime utilisés dans le moteur NeoMundi.

## Objectif

L’objectif de ce dépôt est de clarifier comment les signaux NeoMundi peuvent être interprétés dans un cadre de gouvernance runtime.

Il vise à distinguer clairement :

- un signal ;
- une métrique ;
- une décision de gouvernance ;
- une preuve ;
- une responsabilité humaine ou métier ;
- une interprétation contextuelle.

Le contrat d’interprétation ne cherche pas à imposer une lecture universelle des systèmes IA.

Il fournit un cadre minimal pour éviter les confusions, les surinterprétations et les usages abusifs des signaux.

## Principe central

Un signal n’est pas une vérité.

Une métrique n’est pas une décision.

Une décision de gouvernance n’est pas une preuve juridique automatique.

Un score ne remplace pas l’analyse humaine, métier ou réglementaire.

Les signaux NeoMundi doivent être compris comme des artefacts d’observabilité et de gouvernance runtime.

Ils aident à interpréter l’état d’une génération IA ou d’un segment d’exécution, mais ils ne prétendent pas produire une vérité absolue.

## Signal

Un signal est une information observable produite pendant ou à propos d’une exécution IA.

Exemples :

- G ;
- ΔG ;
- cohérence ;
- densité informationnelle ;
- énergie informationnelle ;
- ESI.

Un signal peut aider à identifier une stabilité, une variation, une fragilité, une transition ou une zone d’attention.

Un signal ne constitue pas, à lui seul, une conclusion définitive.

## Métrique

Une métrique est une mesure structurée ou un indicateur calculé à partir de variables observables.

Elle peut être descriptive, dérivée ou composite.

Une métrique permet d’organiser l’observation.

Elle ne doit pas être confondue avec une preuve, une vérité ou une décision automatique.

## Décision de gouvernance

Une décision de gouvernance correspond à un état opérationnel produit à partir d’un ou plusieurs signaux, métriques ou règles configurées.

Exemples :

- ALLOW ;
- FLAG ;
- BLOCK ;
- SIGNAL ;
- REVIEW ;
- ESCALATE.

Une décision de gouvernance ne signifie pas nécessairement que la réponse est vraie, fausse, dangereuse ou conforme.

Elle signifie qu’un système applique une politique d’action à partir de signaux observés et de seuils définis.

## Preuve

Une preuve implique un niveau d’ancrage, de vérification, de traçabilité ou de validation supérieur à un simple signal runtime.

Un signal peut contribuer à une chaîne de preuve.

Mais un signal runtime, pris isolément, ne constitue pas une preuve juridique, scientifique ou factuelle complète.

## Responsabilité d’interprétation

L’interprétation finale dépend toujours du contexte d’usage.

Elle peut relever :

- de l’utilisateur ;
- de l’opérateur humain ;
- du système d’orchestration ;
- du responsable conformité ;
- de l’auditeur ;
- du fournisseur d’application ;
- du cadre réglementaire applicable.

NeoMundi fournit des signaux de gouvernance runtime.

L’usage, le paramétrage, les seuils, les politiques d’action et les décisions finales relèvent du système ou de l’organisation qui les exploite.

## Interprétation contextuelle

Un même signal peut avoir des significations différentes selon :

- le domaine d’application ;
- le niveau de risque ;
- le type de tâche ;
- le modèle utilisé ;
- le contexte métier ;
- les seuils configurés ;
- la présence ou non d’un humain dans la boucle ;
- les exigences réglementaires ;
- le niveau de preuve attendu.

Un score faible ne prouve pas automatiquement une erreur.

Un score élevé ne garantit pas une vérité absolue.

Un FLAG ne signifie pas nécessairement que la réponse est fausse.

Un ALLOW ne signifie pas que la réponse est parfaite.

Un BLOCK ne signifie pas que la réponse est universellement dangereuse.

## Non-revendications

Le contrat d’interprétation précise que les signaux NeoMundi ne prétendent pas fournir :

- une vérité sémantique absolue ;
- une certitude factuelle universelle ;
- une reconstruction de la cognition interne du modèle ;
- une garantie d’absence d’hallucination ;
- une certification juridique automatique ;
- une décision morale ;
- une conformité réglementaire complète à eux seuls ;
- une substitution à la responsabilité humaine.

## Relation avec l’interopérabilité

Le contrat d’interopérabilité définit comment les signaux peuvent circuler entre plusieurs couches techniques ou organisationnelles.

Le contrat d’interprétation définit ce que ces signaux peuvent signifier, ce qu’ils ne signifient pas, et quelles responsabilités restent attachées à leur usage.

Interopérabilité : comment les couches se parlent.

Interprétation : comment les signaux doivent être lus.

## Position méthodologique

Le contrat d’interprétation vise à rendre les signaux NeoMundi lisibles, auditables et exploitables sans les transformer en vérités absolues.

Il protège à la fois :

- la rigueur méthodologique ;
- l’utilisateur final ;
- l’auditeur ;
- l’intégrateur ;
- le fournisseur d’application ;
- la responsabilité humaine ;
- et le cœur propriétaire du moteur NeoMundi.

## Limites

Ce dépôt fournit une définition publique et méthodologique.

Il ne documente pas les paramètres internes de production.

Il ne constitue pas une documentation complète du moteur NeoMundi.

Il ne remplace pas un audit technique, juridique, scientifique ou réglementaire.

Il sert de base commune pour interpréter les signaux dans un cadre de gouvernance runtime.
