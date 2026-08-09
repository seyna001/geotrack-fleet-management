# VOLET 3 – Validation de la qualité

Ce volet vise à vérifier que l’architecture proposée pour GeoTrack répond aux exigences de qualité, de performance, de sécurité et de disponibilité du système.

## Stratégie de tests

La validation de GeoTrack repose sur plusieurs catégories de tests : tests fonctionnels, tests d’intégration, tests de performance, tests de charge et tests de résilience. Les scénarios principaux portent notamment sur la réception de la télémétrie, l’affichage des véhicules, la génération des alertes et le comportement du système en cas de panne.

## Analyse des performances

Les principaux indicateurs surveillés sont le nombre de messages traités par seconde (MPS), le nombre de requêtes par seconde (QPS), la latence, le taux d’erreur et la disponibilité. Le système doit supporter environ 2 000 messages par seconde en fonctionnement normal et des pics pouvant atteindre 5 000 MPS, tout en maintenant une mise à jour de la position en moins de 3 secondes.

## Analyse de sécurité

Les principales menaces identifiées concernent les accès non autorisés, l’interception des données, les attaques contre les API, l’usurpation d’un appareil GPS et les attaques par déni de service. Les protections proposées comprennent l’authentification, le contrôle d’accès par rôles, TLS, le chiffrement des données, la validation des entrées, la journalisation et la limitation du nombre de requêtes.

## Observabilité

GeoTrack utilise une stratégie de journalisation et de monitoring permettant de surveiller l’état des services, les erreurs, les performances, les files d’événements et les bases de données. Des alertes sont générées automatiquement lorsqu’une anomalie ou un dépassement de seuil est détecté.

## Maintenance et évolution

L’architecture orientée événements facilite l’évolution du système. Les différents services peuvent être mis à jour et déployés indépendamment. La mise à l’échelle horizontale permet également d’ajouter des ressources lorsque le nombre de véhicules augmente.


