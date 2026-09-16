# 7. Bots, monitoring et intégration

Les packages de bot observent les événements, suivent les requêtes actives et peuvent proposer ou contester selon une politique. Un bot doit distinguer une absence d’événement, une erreur RPC, une requête expirée et une décision finale.

Une intégration DeFi doit limiter les identifiants acceptés, choisir une valeur de bond, surveiller les délais et prévoir une action de secours. Les contrats d’application ne doivent pas traiter une proposition comme définitive avant le règlement.

La surface inclut les oracles, les tokens de bond, les registres, les permissions et les services hors chaîne. Le code opérationnel doit donc être accompagné d’une supervision et d’une stratégie de reprise.

Suite : [limites et périmètre](08-limites.md).
