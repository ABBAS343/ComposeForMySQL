---

Copyright:
  years: 2017,2018
lastupdated: "2017-11-20"
---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}

# Présentation du service

La page _Vue d'ensemble_ affiche des informations concernant la base de données Compose d'{{site.data.keyword.cloud}}. La vue d'ensemble contient des informations d'identification essentielles et indique l'utilisation actuelle des ressources. Vous y trouverez également une section qui contient les chaînes de connexion que vous pouvez utiliser avec les outils pour vous connecter à votre base de données.

## Deployment Details

Le panneau _Deployment Details_ affiche des détails concernant votre déploiement.

![Deployment Details](./images/mysql-deployment-details.png "Vue du panneau Deployment Details")

### Type

Type de base de données fourni par le service et version de base de données qu'utilise votre service. Lorsqu'une version plus récente de la base de données est disponible, une notification s'affiche, accompagnée d'un lien vers la section [Mise à niveau de la version](/docs/services/ComposeForMySQL/dashboard-settings.html#upgrade-version) du tableau de bord de votre service.

### Nom

Identificateur interne du service.

### Utilisation

Taille de votre base de données et quantité de stockage fournie par le plan de service.

## Travaux en cours

Toute modification administrative (telle une mise à l'échelle ou une sauvegarde manuelle) démarre un travail. Pendant l'exécution d'un travail, le panneau _Current Jobs_, qui indique le nom du travail et présente une barre de progression, s'affiche sur la page _Vue d'ensemble_. Une fois le travail achevé, le panneau _Current Jobs_ disparaît de la page _Vue d'ensemble_.

## Chaînes de connexion

Les chaînes de connexion peuvent être utilisées par certaines bibliothèques client et contiennent toutes les informations nécessaires pour que d'autres bibliothèques se connectent. Pour savoir comment utiliser une chaîne de connexion pour vous connecter à votre service, voir [Connexion d'une application externe](./connecting-external.html).

Chaque chaîne de connexion pour votre service se trouve dans un onglet distinct du panneau _Chaînes de connexion_.

### Chaîne de connexion

La **chaîne de connexion** peut être utilisée par certaines bibliothèques client et qui contient toutes les informations requises pour la connexion d'autres bibliothèques. Pour savoir comment utiliser une chaîne de connexion pour vous connecter, voir [Connexion d'une application externe](./connecting-external.html).

### Ligne de commande

Une **ligne de commande** est une commande préformatée que vous pouvez utiliser pour vous connecter à MySQL. Pour ce faire, vous devez installer MySQL sur votre machine locale. Pour plus d'informations sur la procédure à suivre, voir [Connexion d'une application externe](./connecting-external.html).

### Certificat SSL

Le service Compose {{site.data.keyword.cloud_notm}} vous fournit un certificat SSL qui vous permet de vous connecter à votre base de données.


## API d'administration d'instance

Vous pouvez gérer votre service {{site.data.keyword.composeForMySQL}} via l'API {{site.data.keyword.cloud_notm}} Compose.

### Noeud final Foundation

Le noeud final Foundation est composé de la région où réside le service et de l'ID d'instance du service. Il se trouvera au début de chaque noeud final.

### ID de déploiement

L'ID de déploiement est nécessaire pour la plupart des appels ; il identifie l'instance de déploiement spécifique.

### Référence

Pour plus de documentation et de référence sur l'utilisation de l'API {{site.data.keyword.cloud_notm}} Compose au sein de tous les services {{site.data.keyword.cloud_notm}} Compose, voir [API {{site.data.keyword.cloud_notm}} Compose](https://www.compose.com/articles/the-ibm-cloud-compose-api/).
