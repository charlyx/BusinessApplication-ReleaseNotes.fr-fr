---
title: Migration de la configuration
description: Il est possible de migrer la configuration du portail Dynamics 365 entre les environnements
author: sandhangitmsft
manager: ramalingamkrishnan
ms.date: 7/22/2018
ms.assetid: f454a2d3-c047-4a57-8a9f-7ddf38781971
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: sandhan
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 2f1b97389e79909e67c1f60ab00862dbb805ccf3
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
# <a name="configuration-migration"></a>Migration de la configuration

[!include[banner](../../../includes/banner.md)]


Plusieurs configurations et personnalisations sont nécessaires pour développer un portail, et ce pour que les utilisateurs finaux puissent bénéficier de l'expérience souhaitée. Pour réduire le temps et les efforts nécessaires pour gérer la configuration du portail dans les environnements, nous avons publié un schéma de migration. Il fonctionne avec l'[Outil SDK de migration de la configuration](https://technet.microsoft.com/library/dn647421.aspx).

Les personnalisateurs du portail procèdent de différentes façons (notamment par la création complète des fichiers du schéma) pour que l'outil SDK de migration de la configuration puisse déplacer les configurations vers différents environnements (généralement des environnements de développement, de test, de production). La création complète du schéma peut être chronophage, entraîner une migration partielle des données et peut aussi être source d'erreur.

Il est possible d'utiliser toutes les fonctionnalités de l'outil SDK de migration de la configuration avec ce schéma pour gérer la configuration du portail :

 - **Créer un schéma** : Le schéma peut être adapté pour l'implémentation à l'aide des méthodes standard fournies par l'outil. Les fichiers du schéma peuvent être chargés dans l'outil et être modifiés pour ajouter, supprimer, et modifier des entités, des attributs, etc. pour répondre aux besoins de migration de la configuration.
 - **Exporter des données** : Utilisez le fichier du schéma pour exporter les données d'un environnement dans un fichier .zip, puis utilisez-le pour la sauvegarde, le contrôle de code source, ou l'importation dans un environnement cible.
 - **Importer des données** : Utiliser les données exportées pour importer dans un environnement cible.

<!--
### Who uses this feature
This feature is intended for administrators and customizers who need to migrate their portal configuration between environments.
## Status
### Development status
Generally available
#### Target timeframe
October 2018
### Availability
Cloud
### Regional availability
Global
-->

## <a name="wed-like-to-thank"></a>Nous voulons remercier

Merci d'avoir soumis [cette idée](https://experience.dynamics.com/ideas/idea/?ideaid=b75ece29-1481-e611-80c1-00155d460f3c) avec des votes et des commentaires, cela nous a permis de la traiter en priorité.


