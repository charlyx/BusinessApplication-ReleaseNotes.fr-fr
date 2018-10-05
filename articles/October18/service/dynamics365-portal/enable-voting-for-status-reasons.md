---
title: Activer le vote pour des raisons de statut dans Dynamics 365 Portal
description: Activez le vote pour des raisons de statut dans votre portail.
author: neerajnandwana-ms
manager: ramalingamkrishnan
ms.date: 09/20/2018
ms.assetid: D81BD65F-E1D6-42CF-BF48-667DFA8A2852
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: nenandw
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 7e0954b5f4a23af4780aa48b1b609c68fc7ae6e3
ms.openlocfilehash: 4cc4cae09f6e22a6ec165d69a19c70777175b3ef
ms.contentlocale: fr-fr
ms.lasthandoff: 09/20/2018

---
# <a name="enable-voting-for-status-reasons"></a><span data-ttu-id="00145-103">Activer le vote pour des raisons de statut</span><span class="sxs-lookup"><span data-stu-id="00145-103">Enable voting for status reasons</span></span>

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]

<span data-ttu-id="00145-104">Actuellement, une idée est activée pour le vote uniquement lorsque la **Raison du statut** est définie sur **Nouveau**.</span><span class="sxs-lookup"><span data-stu-id="00145-104">Currently, an idea is enabled for voting only when the **Status Reason** is set to **New**.</span></span> <span data-ttu-id="00145-105">Cette fonctionnalité vous permet d'activer le vote pour une idée pour différentes raisons du statut.</span><span class="sxs-lookup"><span data-stu-id="00145-105">This feature allows you to enable the voting on an idea for different status reasons.</span></span> <span data-ttu-id="00145-106">Pour permettre le vote pour différentes raisons de statut, vous devez créer le paramètre de site **Ideas/EnableVotingForStatusReasons** et définir sa valeur sur les valeurs de raison de statut requises.</span><span class="sxs-lookup"><span data-stu-id="00145-106">To enable voting for different status reasons, you must create the **Ideas/EnableVotingForStatusReasons** site setting and set its value to the required status reason values.</span></span>
 
<span data-ttu-id="00145-107">Par exemple, si vous souhaitez activer le vote pour les raisons de statut **Nouveau**, **Accepté**, et **Rejeté**.</span><span class="sxs-lookup"><span data-stu-id="00145-107">For example, if you want to enable voting for **New**, **Accepted**, and **Rejected** status reasons.</span></span> <span data-ttu-id="00145-108">Vous devez créer le paramètre de site et définir sa valeur comme suit :</span><span class="sxs-lookup"><span data-stu-id="00145-108">You must create the site setting and set its value as:</span></span>

- <span data-ttu-id="00145-109">**Nom** : Ideas/EnableVotingForStatusReasons</span><span class="sxs-lookup"><span data-stu-id="00145-109">**Name**: Ideas/EnableVotingForStatusReasons</span></span>

- <span data-ttu-id="00145-110">**Valeur** : 1;100000000;100000002</span><span class="sxs-lookup"><span data-stu-id="00145-110">**Value**: 1;100000000;100000002</span></span>

<span data-ttu-id="00145-111">Pour plus d'informations sur les validations et les étapes à suivre pour obtenir les valeurs de raison du statut, consultez la documentation détaillée : [Activer le vote pour des raisons de statut](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/portals/crowdsource-ideas#enable-voting-for-status-reasons)</span><span class="sxs-lookup"><span data-stu-id="00145-111">For information about validations and steps to get the status reason values, see the detailed documentation: [Enable voting for status reasons](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/portals/crowdsource-ideas#enable-voting-for-status-reasons)</span></span>

<!--
### Who uses this feature
This feature is intended for customizers. A customizer can configure and decide the status reasons, where user can vote.
### License required
NA
### Setup required
No 
## Status
### Development status
Generally available
#### Target timeframe
October 2018
### Availability
Cloud
### Regional availability
This feature will be available globally. 
-->

