---
title: Migration de la configuration
description: Il est possible de migrer la configuration du Dynamics 365 Portal entre les environnements
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
ms.sourcegitcommit: 7e0954b5f4a23af4780aa48b1b609c68fc7ae6e3
ms.openlocfilehash: 589c266f81868780f660f9c174dc5538728174ef
ms.contentlocale: fr-fr
ms.lasthandoff: 09/20/2018

---
# <a name="configuration-migration"></a><span data-ttu-id="445f6-103">Migration de la configuration</span><span class="sxs-lookup"><span data-stu-id="445f6-103">Configuration migration</span></span>

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]

<span data-ttu-id="445f6-104">Plusieurs configurations et personnalisations sont nécessaires pour développer un portail, et ce pour que les utilisateurs finaux puissent bénéficier de l'expérience souhaitée.</span><span class="sxs-lookup"><span data-stu-id="445f6-104">Portal development involves several configurations and customizations to achieve a desired experience for portal end users.</span></span> <span data-ttu-id="445f6-105">Pour réduire le temps et les efforts nécessaires pour gérer la configuration du portail dans les environnements, nous avons publié un schéma de migration. Il fonctionne avec l'[Outil SDK de migration de la configuration](https://technet.microsoft.com/library/dn647421.aspx).</span><span class="sxs-lookup"><span data-stu-id="445f6-105">To reduce the time and effort required to manage portal configuration across environments, we are publishing schema for configuration migration that works with the [Configuration Migration SDK tool](https://technet.microsoft.com/library/dn647421.aspx).</span></span>

<span data-ttu-id="445f6-106">Les personnalisateurs du portail procèdent de différentes façons (notamment par la création complète des fichiers du schéma) pour que l'outil SDK de migration de la configuration puisse déplacer les configurations vers différents environnements (généralement des environnements de développement, de test, de production).</span><span class="sxs-lookup"><span data-stu-id="445f6-106">Portal customizers use various ways, including creation of schema files from scratch, for the Configuration Migration SDK tool to move configurations to different environments, typically development, test, and production.</span></span> <span data-ttu-id="445f6-107">La création complète du schéma peut être chronophage, entraîner une migration partielle des données et peut aussi être source d'erreur.</span><span class="sxs-lookup"><span data-stu-id="445f6-107">Creating schema from scratch can be time-consuming, sometimes causing partial data migration, and can be error-prone.</span></span>

<span data-ttu-id="445f6-108">Il est possible d'utiliser toutes les fonctionnalités de l'outil SDK de migration de la configuration avec ce schéma pour gérer la configuration du portail :</span><span class="sxs-lookup"><span data-stu-id="445f6-108">All Configuration Migration SDK tool capabilities can be used with this schema to manage portal configuration:</span></span>

 - <span data-ttu-id="445f6-109">**Créer un schéma** : Le schéma peut être adapté pour l'implémentation à l'aide des méthodes standard fournies par l'outil.</span><span class="sxs-lookup"><span data-stu-id="445f6-109">**Create schema**: The schema can be tailored for the implementation using standard ways provided by the tool.</span></span> <span data-ttu-id="445f6-110">Les fichiers du schéma peuvent être chargés dans l'outil et être modifiés pour ajouter, supprimer, et modifier des entités, des attributs, etc. pour répondre aux besoins de migration de la configuration.</span><span class="sxs-lookup"><span data-stu-id="445f6-110">Schema files can be loaded in the tool and altered to add, remove, and modify entities, attributes, and so on to suit configuration migration needs.</span></span>
 - <span data-ttu-id="445f6-111">**Exporter des données** : Utilisez le fichier du schéma pour exporter les données d'un environnement dans un fichier .zip, puis utilisez-le pour la sauvegarde, le contrôle de code source, ou l'importation dans un environnement cible.</span><span class="sxs-lookup"><span data-stu-id="445f6-111">**Export data**: Use the schema file to export data from an environment into a .zip file, and use it for backup, source control, or importing into a target environment.</span></span>
 - <span data-ttu-id="445f6-112">**Importer des données** : Utiliser les données exportées pour importer dans un environnement cible.</span><span class="sxs-lookup"><span data-stu-id="445f6-112">**Import data**: Use the exported data to import into a target environment.</span></span>

<span data-ttu-id="445f6-113">Pour plus d'informations sur la migration d'une configuration de portail, consultez la documentation détaillée : [Migrer la Dynamics 365 Portal configuration](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/portals/migrate-portal-configuration)</span><span class="sxs-lookup"><span data-stu-id="445f6-113">For information about how to migrate a portal configuration, see the detailed documentation: [Migrate Dynamics 365 Portal configuration](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/portals/migrate-portal-configuration)</span></span>

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

## <a name="wed-like-to-thank"></a><span data-ttu-id="445f6-114">Nous voulons remercier</span><span class="sxs-lookup"><span data-stu-id="445f6-114">We'd like to thank</span></span>

<span data-ttu-id="445f6-115">Merci d'avoir soumis [cette idée](https://experience.dynamics.com/ideas/idea/?ideaid=b75ece29-1481-e611-80c1-00155d460f3c) avec des votes et des commentaires, cela nous a permis de la traiter en priorité.</span><span class="sxs-lookup"><span data-stu-id="445f6-115">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=b75ece29-1481-e611-80c1-00155d460f3c) with votes and comments that helped us prioritize it.</span></span>


