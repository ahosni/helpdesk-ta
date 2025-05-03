# Enterprise Help Desk Solution - Technical Assessment
> Vous trouverez ici un exercice avec une grande liberté d'implémentation, conçu pour être réalisé dans un temps limité.\
> L'objectif est de mettre en avant vos compétences techniques et vos choix architecturaux tout en respectant les contraintes spécifiées.
> Il n'est pas nécessaire de le terminer entièrement, mais il est important de montrer votre capacité à structurer et à organiser votre code.
> Cet exercice a pour objectif de servir de base à une discussion technique lors d'un futur entretien.\
> Nous vous recommandons de limiter votre temps à environ 8 heures, même si toutes les User Stories obligatoires ne sont pas entièrement terminées.

## Instructions Générales
L'exercice est composé d'une partie obligatoire, le [Minimum Viable Product](#mvp).\
Il y a également des [fonctionnalités avancées optionnelles](#fonctionnalités-avancées) afin d'utiliser le temps restant pour vous démarquer.\
Les stories ne possèdent pas de critères d'acceptance, c'est à vous de les définir après votre analyse fonctionnelle de la story.

**S'il vous manque une information, faites un choix et restez cohérent avec celui-ci.**

### Spécifications Techniques
- Backend : Java (Spring Boot de préférence) OU Node.js (Express/NestJS)
- Frontend : Next.js
- Git
- Fichier `README.md` -- _Explique les potentielles subtilités de votre implémentation et comment lancer votre projet_.

### Modalités de Livraison
Le code devrait être disponible sur un repository public (GitHub, GitLab, etc.).

### Critères d'Évaluation
Nous évaluerons les points suivants : 
- Vos choix d'implémentation et leur justification
- La qualité et la lisibilité de votre code
- La structure et l'architecture de votre projet
- Le respect des contraintes techniques et fonctionnelles
- La pertinence et la clarté de vos commits et messages associés
- La documentation fournie, notamment dans le fichier `README.md`
- La qualité de l'interface utilisateur, les composants choisis et leur ergonomie
- Toute valeur ajoutée apportée par des fonctionnalités avancées ou des propositions innovantes

## Cahier des Charges
### MVP
#### User Story
> En tant qu'utilisateur, je peux soumettre une demande d'assistance via un formulaire contenant les informations suivantes :
> - Titre de la demande
> - Description détaillée
> - Catégorie (à définir selon votre choix)
> - Niveau d'urgence (Normal, Urgent, Critique)

#### User Story
> En tant qu'administrateur, je peux consulter la liste de toutes les demandes d'assistance soumises.

#### User Story
> En tant qu'administrateur, je peux valider ou rejeter une demande d'assistance avec la possibilité d'ajouter un commentaire.

#### User Story
> En tant qu'utilisateur, je peux consulter la réponse à ma demande d'assistance, incluant le statut (validé ou rejeté) et le commentaire associé de l'administrateur.

### Fonctionnalités Avancées
Les fonctionnalités suivantes sont optionnelles et non exhaustives.\
Elles n'ont pas de priorité entre elles, vous pouvez implémenter celles qui vous intéressent ou en proposer d'autres.

#### Communication en Temps Réel
- Implémenter un système de notifications en temps réel (WebSocket) pour informer l'utilisateur du statut de sa demande
- Notifier l'administrateur lorsqu'une nouvelle demande est soumise

#### Gestion des Accès
- Mettre en place un système d'authentification pour les utilisateurs et administrateurs
- Gérer les autorisations appropriées pour chaque rôle

#### Interface Utilisateur Optimisée
- Intégrer un système de recherche et de filtrage des demandes

#### Architecture API
- Documenter l'API (Swagger/OpenAPI)
- Implémenter des tests d'intégration pour l'API

#### Infrastructure et Déploiement
- Proposer une configuration Docker pour faciliter le déploiement de l'application