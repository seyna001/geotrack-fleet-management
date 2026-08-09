Volet 2 — Analyse, conception logicielle et architecture système
Présentation

Le Volet 2 du projet GeoTrack — Fleet Management présente l'analyse, la conception et l'architecture proposée pour le système.

L'objectif est de définir une architecture cohérente capable de répondre aux besoins fonctionnels et non fonctionnels de l'application tout en tenant compte des contraintes de performance, de disponibilité, de sécurité et d'évolution du système.

Analyse du système

L'analyse permet d'identifier :

les principales parties prenantes ;
les besoins fonctionnels ;
les besoins non fonctionnels ;
les contraintes techniques et opérationnelles ;
les hypothèses nécessaires à la conception du système.

Les hypothèses qui ne sont pas directement fournies dans l'énoncé sont estimées et justifiées afin de permettre la conception et le dimensionnement de l'architecture.

Modélisation

La modélisation UML permet de représenter les principales interactions avec GeoTrack ainsi que le comportement du système.

Les diagrammes réalisés comprennent :

un diagramme de cas d'utilisation ;
un diagramme de séquence lié à la gestion de la télémétrie ;
un diagramme de séquence représentant un autre scénario critique du système.

Ces diagrammes permettent de mieux comprendre les interactions entre les utilisateurs, les véhicules et les différents composants de l'application.

Choix architectural

Plusieurs styles architecturaux sont comparés selon différents critères tels que :

la performance ;
la scalabilité ;
la disponibilité ;
la complexité ;
la maintenabilité ;
la résilience.

L'architecture retenue est ensuite justifiée en fonction des besoins spécifiques de GeoTrack.

Dimensionnement

Le dimensionnement permet d'estimer la charge que devra supporter le système.

Les principaux paramètres étudiés sont :

le nombre de véhicules connectés ;
la fréquence d'envoi des données ;
le nombre de messages par seconde (MPS) ;
le nombre de requêtes par seconde (QPS) ;
le volume quotidien de données ;
le débit réseau ;
la latence attendue.

Les calculs sont accompagnés des formules, unités et hypothèses utilisées.

Stratégie de données

Une stratégie de gestion des données est proposée afin de permettre le stockage efficace des informations générées par GeoTrack.

Elle prend notamment en compte :

les données des véhicules ;
les données de télémétrie ;
les données de géolocalisation ;
les données des utilisateurs ;
l'organisation et l'optimisation du stockage ;
la conservation des données ;
les sauvegardes ;
la disponibilité ;
la récupération des données après incident.
Cohérence, disponibilité et résilience

L'architecture est analysée face à différents scénarios critiques, notamment :

les accès concurrents ;
les erreurs applicatives ;
les pannes de composants ;
les pertes ou retards de communication ;
les surcharges ;
les interruptions de service ;
la reprise après incident.

Des mécanismes sont proposés afin de maintenir autant que possible la disponibilité et l'intégrité du système.

Architecture globale

Un diagramme d'architecture présente les principaux composants de GeoTrack, leurs responsabilités et leurs interactions.

Les choix technologiques et architecturaux sont reliés aux exigences du projet et les principaux compromis sont documentés.

Interface utilisateur

Une maquette haute fidélité est réalisée avec Figma afin de représenter le parcours utilisateur principal.

Le prototype comprend plusieurs écrans principaux permettant notamment de visualiser et de superviser les informations de la flotte de véhicules.

Livrables

Le Volet 2 comprend :

le dossier d'architecture ;
le diagramme de cas d'utilisation ;
les diagrammes de séquence ;
le diagramme d'architecture globale ;
les interfaces de l'application ;
les calculs de dimensionnement ;
le tableau des décisions architecturales ;
le tableau des compromis et des solutions rejetées.
