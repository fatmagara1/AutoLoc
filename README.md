# AutoLoc

Plateforme de gestion de location de véhicules multi-agences (projet UP ASI — Architecture des Systèmes d'Information).

## Objectifs du projet

AutoLoc permet de gérer la location de véhicules à travers plusieurs agences : consultation du parc, réservations, suivi des locations, et administration des utilisateurs et des agences.

## Acteurs identifiés (Séance 1)

| Acteur | Rôle |
|--------|------|
| **Client** | Consulte les véhicules disponibles, réserve / loue un véhicule, consulte ses locations. |
| **Agent d'agence** | Gère les locations au quotidien, accueil client, mise à disposition et restitution des véhicules. |
| **Responsable d'agence (Manager)** | Supervise l'agence, le parc véhicules et les agents ; suit l'activité de l'agence. |
| **Administrateur** | Administre la plateforme (utilisateurs, agences, référentiels) et supervise le système. |

## Cas d'utilisation (première liste)

- S'authentifier / gérer son compte
- Consulter le catalogue de véhicules
- Réserver / louer un véhicule
- Gérer une location (prise en charge, restitution)
- Gérer le parc de véhicules d'une agence
- Administrer les agences et les utilisateurs

## Stack technique prévue

- Java 17+, Maven, Spring Boot
- MySQL (`autoloc_db`)
- IntelliJ IDEA Ultimate, Postman, Git/GitHub

## Environnement (Atelier 0)

- JDK 17
- IntelliJ IDEA Ultimate (licence étudiante)
- MySQL (WAMP) + base `autoloc_db`
- Postman
- Git

> Atelier 0 — mise en place de l'environnement. Un commit vaut mieux qu'un dépôt vide.
