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



