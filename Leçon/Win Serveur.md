## Introduction
### Définition
S.E développé par **Microsoft**. Conçu pour gérer, stocker, et traiter des données, ainsi que pour exécuter des services réseau et d'applications:
**Gestion serveur, Active Directory, Hyper-V, Service Web, Solution de stockage, scalabilité et performance...**


> [!NOTE] Scalabilté
> miova ny resources automatiquement. Izany we rah ohatra minana 100% ny VM iray anaty Serveur, miakatra auto ny RAM sy CPU.

### Différence avec Windows10/11
- **Conçu pour**: environnements de serveurs.
- **Utilisation principale**: Hébergement de service réseau, de bases de données, de serveurs web, de fichiers d'applications.
- **Administration**: Gestion des utilisateurs et permissions, configuration des réseaux et services

> [!NOTE] Win Serveur est multi-user
> Utilisateurs maro2 afaka mi-se-connécter en même temps


### Fonctionnalités
- **Active Directory**: gestion des identités et des accès. 
- **Hyper-V**: capacités de virtualisation robustes, y compris le supports de conteneurs
- **Sécurité**: BitLocker, Windows Defender, contrôles d'accès conditionnel
- **Gestion de stockage**: Storage Space Direct, et des systèmes de fichiers résilients (ReFS)

### Rôles et Fonctionnalités au niveau de WinServer

- **Active Directory Domain Service (ADDS)**: service de répertoire développé par Microsoft pour les environnements Windows Server. 
- **Serveur DNS**: traduit les noms de domaines lisible par l'**homme** en addresse IP lisible par les **machines**
- **Serveur DHCP**: service réseau qui attribue automatiquement des adresses IP et d'autres informations de configuration réseau aux appareils connectés à un réseau.
- **Serveur de fichiers et d'impression:** gestion centralisée des fichiers et des imprimantes. Il facilite le partage des ressources, améliore la collab et assure la sécurité et la disponibilité des données et des services d'impression.
- **Hyper-V**: plateforme de virtualisation développé par Microsoft
- **Serveur Web (IIS)**: il s'agit d'un puissant serveur web qui offre une plateforme robuste pour héberger des sites web, app web et des services web.


### Architecture de windows Server
Windows Server permet de définir des rôles et fonctionnalités à attribuer aux serveurs, selon les besoins de l'infrastructure réseau

Windows Server est fondé sur un modèle **clients-serveur**(client mangataka ressources am serveur d ny serveur manome retour). 

#### Architecture réseau, protocoles, et service de base
- **Domaine et Forêts Active Directory**: 
	Organisent les ressources réseau en unité logiques administratives, facilitant la gestion des utilisateurs, des groupes et des politiques de sécurité
- **Service réseau**:
	Incluent **DNS** pour la résolution des noms de domaines en adresses IP, et **DHCP**
- **Topologie réseau**:
	Support diverses topologies réseau, y compris LAN, WAN, et VPN
- **Protocole de communication**:
	Incluent **TCP/IP**
- **Service de gestion**:
	comme **SNMP** pour la surveillance et la gestion des périphériques réseau, **RDP** pour l'accès à distance aux ordinateurs Windows Server
- **Service de sécurité**:
	Intégration de Windows Defender pour la protection contre les logiciels malveillants, **Bitlocker** pour les cryptages des données.



> [!NOTE] LAN
> Tout ce qui est **intérieur**  

### Comparaison avec d'autres systèmes serveur
- **Windows Server**:
	- Supporte une large gamme de matériel
	- Nécessite une licence
- **Linux**:
	- Supporte une large gamme de matériel, y compris des architectures différentes
	- Gratuit
- **macOs Server**:
	- Concentré sur les services Apple
	- Utilisation courante dans les environnements éducatifs et créatifs
- **Unix**:
	- Supportes des app spécifiques à certains industries et des solutions logicielles personnalisées
	- Gestion souvent orienté en ligne de commande

### Cas d'utilisation typiques de WinServer
#### Gestion d'identité et d'accès:
**Active Directory**: utilisé pour déployer et gérer des services d'annuaire via **AD**.

#### Services de messagerie et de collab: 
**Exchange Server** : Windows Server est souvent utilisé avec **Microsoft Exgange Server** pour fournir des services de messagerie, de calendrier, de contacts et de collaboration.


> [!NOTE] Microsoft Exchange Server
> - Afaka manao calendrier local sy ny calendrier en ligne. Ampesaina matetika anaty Entreprise
> - Onpremise: manana serveur dédié mintsy. Contrôle total contrairement @ Microsoft 365(au niveau du cloud)

#### Partage de fichiers et d'Impression
**Serveur de fichier**: WinServer est configuré en tant que serveur de fichier pour le partage de fichiers. Il offre des fonctionnalités avancées telles que le contrôle d'accès basé sur les rôles, chiffrement de données (**BitLocker**), gestion de quotas de stockage .

#### Virtualisation et Cloud privé
**Hyper-V**: WinServer comprend Hyper-V. Cela permet la consolidation des serveurs, la flexibilité des charges de travail, gestion efficace des ressources informatiques.

#### Sauvegarde et Récupération
**Windows Server Backup**: cet outil offre des fonctionnalités de sauvegardes et récupérations pour protéger les données critiques et restaurer les systèmes en cas de sinistre ou de perte de données. 

#### Sécurité et gestion des Systèmes:
**Windows Defender**: offre une protection contre les menaces de sécurité telles que les virus et attaque.

#### Analyse de Données et Business intelligence:
**Microsoft SQL Server**: gestion et analyse des données d'entreprise, stockage de bases de données relationnelles, support des app critiques au niveau des entreprises.

#### Intégration avec d'autres services Microsoft
**SharePoint Server**: plateforme cloud développé par Microsoft afin de faire des collaborations en ligne(Afaka manokatra fichier iray ny olona maro be).

### Licences et Editions Windows Server

**Windows Server Essentials**:
	- conçu pour les PME avec des besoins de serveur légers
	- Licence couvrant un serveur physique avec des limitations des nbrs d'user(25)
	- Active Directory, Sauvegarde intégrée, gestion des données et des utilisateurs

**Windows Server Standard**
	- convient aux env physiques et VM
	- Licencié par processeur jusqu'à deux processeurs physiques sur un seul serveur
	-  Active Directory, Sauvegarde intégrée, bureau à distance

**Windows Server  Data Center**
	- Env Cloud privé et hautement virtualisé
	- licence couvrant un nbr illimité de VM
	- +Hyper-v, Storage space direct,etc

**Windows Server Iot**
	- intégration dans des dispositifs et des solutions IoT
	- Licence par appareil pour les dispositifs spécifiques intégrant Windows Server pour des fonctions IoT
	- Gestions appareils IoT, Azure Iot Edge, sécurité renforcée pour les env industriels.

### Prérequis 
- **Processeur**: 1.4 GHz 64 bit
- **Stockage**: 32 GB de stockage
- **RAM**: 2 GB de ram
- **Licence**: clé de produit valide
- Mises à jour du BIOS/firmeware



