# 2. Demande, assertion et bond

Un demandeur crée une requête décrivant un identifiant, une période, une unité et un actif de règlement. L’assertion associe cette demande à une valeur proposée et à une garantie destinée à décourager les mensonges.

Le protocole conserve l’état de la requête : non proposée, proposée, contestée ou réglée selon la version du contrat. Les paramètres de délai et de bond sont propres à l’intégration.

Le client doit encoder exactement l’identifiant et l’horodatage attendus. Une erreur de précision ou d’unité peut produire une réponse techniquement valide mais économiquement fausse.

Suite : [fenêtre de contestation](03-dispute.md).
