
## Definition

Annuaire pour un OS Windows, ..

## Rôle Active directory
- **Stockage centralisé**:
	Active Directory fournit un emplacement centralisé pour la gestion des infos d'identification et des ressources réseau
- **Gestion des identités et des accès:**
	Il permet de gérer les utilisateurs, les groupes, les ordinateurs et d'autres objets, en offrant des mécanismes d'authentification et d'autorisation
- **Répartition des services**:
	Active Directory permet la répartition des services et des ressources à travers un réseau, assurant ainsi la disponibilité et l'accès efficace

## Concepts clés dans un Active Directory
- **Domaine et forêts**:
	regroupements d' objets(user, groupes, pc) qui partagent un même **bdd AD**. Une **Forêts** est un ensemble de domaine

> [!NOTE] Domaine
> !!!!Representé par un **triangle**!!!

- **Contrôleurs de domaine**:
	serveur qui héberge l'AD: responsable de l'auth des users uet PC dans le réseau
- **Objets**: 
	Entités gérées par l' AD: user, groupe, ....
- **Organizational Units (OU):**
	Conteneurs dans un domaine qui peuvent contenir d'autres objets AD, permettant une gestion hiérarchique et l'app de stratégies de groupe (Group Polices).
- **Group Policies**:
	Ensemble de règles qui contrôlent l'environnement de travail des utilisateurs et des ordinateurs
- **Authentification et autorisation**: 
	AD est responsable de vérifier les identités des utilisateurs (authentification) et de déterminer  à quelles ressources ils peuvent accéder (autorisation).

## Composants du Schéma AD
- **Classes d'objets**
	- classes structurées (création d'objets)
	- classes abstraites (modèles pour les autres classes)
	- classes auxiliaires 
	- classes dynamique ()
- **Attributs**
	Les attributs définissent les propriétés des objets. Par exemple, un utilisateur peut avoir des attributs tels que nom, prénom, mail
- **OID (Object Identifier)**
	Chaque classe et attribut est identifié de manière unique par un OID, garantissant l'unicité globale
- **Règles de syntaxe**
	Les règles qui définissent les types de données que les attributs peuvent stocker (chaînes de caractères, nombres, dates, etc, ...)