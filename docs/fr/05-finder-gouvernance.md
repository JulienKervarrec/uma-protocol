# 5. Finder, registres et gouvernance

Les contrats UMA utilisent des registres d’adresses et des clés d’interface pour découvrir l’Oracle, le Store, les whitelists et les composants de gouvernance. Finder permet de remplacer une implémentation sans modifier chaque consommateur.

Les listes d’identifiants, d’adresses et de collatéraux bornent les paramètres acceptés. Leur gouvernance est une partie du modèle de confiance, au même titre que le code de l’oracle.

Une intégration doit lire l’adresse active du réseau ciblé et ne jamais supposer qu’un déploiement ou une version est universel. Les packages du dépôt proposent des configurations distinctes.

Suite : [versions et SDK](06-versions-sdk.md).
