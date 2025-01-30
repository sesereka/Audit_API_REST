# Audit de l'API VAmPI suivant le référentiel OWASP API Top 10
Ce projet consiste à réaliser un audit de sécurité manuel de l'API REST VAmPI en suivant le référentiel OWASP API Top 10. L'objectif est d'identifier les vulnérabilités courantes dans les API, de les documenter de manière détaillée, et de proposer des correctifs pour renforcer la sécurité

**Objectifs du projet**
L'audit se concentre sur les 10 risques principaux définis par l'OWASP API Top 10, tels que les problèmes d'autorisation, d'authentification, d'exposition excessive de données, et bien d'autres. Chaque vulnérabilité identifiée sera analysée manuellement, documentée, et accompagnée de recommandations pour la corriger. Un rapport complet sera rédigé pour résumer les résultats de l'audit.

**Outils utilisés**
Pour cet audit, j'utilise des outils comme Postman pour tester les endpoints de l'API et Burp Suite pour analyser les requêtes et réponses de manière plus approfondie. Ces outils permettent de simuler des attaques et d'identifier les failles de sécurité de manière précise.

**Structure du projet**
Le projet est organisé pour être clair et facile à parcourir. Le dossier /docs contient le rapport détaillé de l'audit, avec une explication des vulnérabilités trouvées et des recommandations pour les corriger. Le dossier /results regroupe les captures d'écran et les preuves des tests effectués, tandis que /remediations propose des solutions concrètes pour chaque problème identifié.

**Comment utiliser ce projet**
Pour explorer ce projet, il suffit de cloner le repository. Le rapport final, disponible dans le dossier /docs, offre une vue d'ensemble des vulnérabilités trouvées et des recommandations pour les corriger. Les captures d'écran et les preuves des tests sont disponibles dans le dossier /results pour une consultation plus approfondie.
