# Application intern de Planification des Visites Médicales – Projet Réel Hébergé en Privé (SQLi) 🔒

> ⚠️ ** Disclaimer **  
Ce dépôt public a uniquement pour objectif de **présenter le contexte et la description technique** d’un projet interne réalisé durant mon **stage chez SQLI**.  
Le **code source complet** du projet est **hébergé sur un dépôt GitLab privé** appartenant à SQLI, et **n’est pas publié** ici pour des raisons de **confidentialité**.

---

## 🔹 Contexte du projet

Chez **SQLI**, j’ai participé au développement d’une **application web interne** visant à **automatiser** et **optimiser** la **planification des visites médicales**, un processus jusque-là **manuel** et **source d’erreurs**.

---

## 🔹 Partie Backend

Le backend reposait sur **Symfony 7**, avec une **architecture CQRS partielle**, ce qui a permis d’améliorer la **scalabilité** et la **maintenabilité** du système.  
J’ai également mis en œuvre un **event-driven design** pour :
- Automatiser l’envoi d’**invitations** et de **rappels**  
- Gérer la **séquence d’envoi des emails** (collaborateur → médecin → RH)

### 🔹 Design Patterns et Bonnes Pratiques

- **Factory Pattern** : génération des invitations selon le type d’utilisateur  
- **Repository Pattern** : isolation propre de la logique d’accès aux données  
- Utilisation de **Services**, **DTOs**, **Mappers**, **Resolvers**, **Validators**  
- Application des **principes SOLID** pour garantir un code maintenable et robuste  

---

## 🔹 Partie Frontend

Côté frontend, j’ai contribué à l’amélioration de l’**expérience utilisateur** via une interface de planification en **drag-and-drop** développée avec **FullCalendar.js**, remplaçant le formulaire classique par une approche beaucoup plus intuitive et visuelle.

---

## 🐳 Déploiement et Outils

Déploiements à l’aide de :
- **Jenkins**
- **Docker**
- **Ansible**
- **GitLab**

---

## 🎯 Résultats et Impact

L’application a permis une **automatisation complète** du processus de planification, entraînant un **gain de temps significatif** pour les **RH**.  
L’administration a exprimé une **forte satisfaction** quant aux **performances** et à **l’efficacité** de la solution mise en place.

---

## 🔒 Dépôt Privé

Le projet complet est **hébergé sur GitLab** (dépôt privé interne à SQLI) et **ne peut être partagé publiquement**.  
Ce dépôt GitHub sert uniquement à **documenter mon expérience** et à **illustrer les aspects techniques du projet**, sans enfreindre la confidentialité de l’entreprise.

---

> 💬 *Cette expérience m’a permis de devenir pleinement opérationnel dans un environnement complexe et de livrer une solution à fort impact technique et organisationnel.*
