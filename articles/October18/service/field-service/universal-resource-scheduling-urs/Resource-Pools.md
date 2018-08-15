---
title: Regroupements de ressources
description: "Les regroupements de ressources permettent aux planificateurs de réserver du travail dans un regroupement générique sans avoir à décider quelle ressource réalisera réellement le travail."
author: Dgittler
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 96e82715-35fd-4587-a004-bbf57a14c1b2
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 830930100198d4925033687fd372f7df8b345bb6
ms.contentlocale: fr-fr
ms.lasthandoff: 08/15/2018

---

#  <a name="resource-pools"></a><span data-ttu-id="9f75b-103">Regroupements de ressources</span><span class="sxs-lookup"><span data-stu-id="9f75b-103">Resource pools</span></span>

[!include[field-service banner](../../../includes/field-service.md)]



<span data-ttu-id="9f75b-104">Associez des ressources aux regroupements de ressources pour permettre aux planificateurs de réserver des besoins dans un regroupement générique sans avoir à décider quelle ressource réalisera réellement le travail.</span><span class="sxs-lookup"><span data-stu-id="9f75b-104">Associate resources to resource pools to enable schedulers to book requirements to a generic pool without needing to decide which resource will actually perform the work.</span></span>

# <a name="why"></a><span data-ttu-id="9f75b-105">Pourquoi ?</span><span class="sxs-lookup"><span data-stu-id="9f75b-105">Why?</span></span>

- <span data-ttu-id="9f75b-106">Évitez d'être forcé de réserver des ressources spécifiques immédiatement et réservez à la place un « regroupement de ressources » tout en vous assurant que de ne pas les surcharger.</span><span class="sxs-lookup"><span data-stu-id="9f75b-106">Avoid being forced to book specific resources up front and instead book the “resource pool” while ensuring you are not overcommitting.</span></span>
- <span data-ttu-id="9f75b-107">Évitez aux planificateurs centraux de se préoccuper de détails dont se charge le gestionnaire des ressources local.</span><span class="sxs-lookup"><span data-stu-id="9f75b-107">Enable central schedulers to be shielded from details and leave the details to the local resource manager.</span></span>
- <span data-ttu-id="9f75b-108">Les ressources spécifiques peuvent ne pas encore être nommées mais la capacité du regroupement est établie et les ressources seront nommées ultérieurement.</span><span class="sxs-lookup"><span data-stu-id="9f75b-108">Specific resources may not be named yet but capacity of the pool is established and resources will be named later.</span></span> <span data-ttu-id="9f75b-109">Les planificateurs peuvent toujours planifier puisque la capacité du regroupement peut être définie comme si toutes les ressources étaient nommées (gestion de la capacité).</span><span class="sxs-lookup"><span data-stu-id="9f75b-109">Schedulers can still schedule since capacity of the pool can be set as if all the resources were named (capacity management).</span></span>
- <span data-ttu-id="9f75b-110">Activez la surréservation délibérément pour les annulations prévues.</span><span class="sxs-lookup"><span data-stu-id="9f75b-110">Deliberately enable overbooking for expected cancellations.</span></span>

# <a name="what"></a><span data-ttu-id="9f75b-111">Quoi ?</span><span class="sxs-lookup"><span data-stu-id="9f75b-111">What?</span></span>

- <span data-ttu-id="9f75b-112">Les pools de ressources peuvent être des regroupements d'installations ou des regroupements de comptes/contacts/utilisateurs, ou des regroupements d'équipements.</span><span class="sxs-lookup"><span data-stu-id="9f75b-112">Resource pools can be either pools of facilities, or pools of accounts/contacts/users, or pools of equipment.</span></span> <span data-ttu-id="9f75b-113">Les regroupements sont prévus pour être un ensemble de ressources homogènes.</span><span class="sxs-lookup"><span data-stu-id="9f75b-113">Pools are intended to be a set of homogenous resources.</span></span>
- <span data-ttu-id="9f75b-114">Les membres du regroupement peuvent être attribués définitivement ou temporairement à des regroupements, à date d'effet.</span><span class="sxs-lookup"><span data-stu-id="9f75b-114">Pool members can be permanently or temporarily assigned to pools, date effective.</span></span>
- <span data-ttu-id="9f75b-115">Vous pouvez éventuellement obtenir la capacité générale du regroupement des membres du regroupement.</span><span class="sxs-lookup"><span data-stu-id="9f75b-115">Optionally derive overall pool capacity from pool members.</span></span>

> <span data-ttu-id="9f75b-116">*Les besoins sur site ne sont pas prévus pour être pris en charge avec des regroupements de ressources*</span><span class="sxs-lookup"><span data-stu-id="9f75b-116">*Onsite requirements not planned to be supported with resource pools*</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="9f75b-117">![](media/ResourcePools.png "Scénarios de regroupements de ressources")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="9f75b-117">![](media/ResourcePools.png "Resource pool scenarios")
<!-- picture --></span></span>

<span data-ttu-id="9f75b-118">*Scénarios de regroupements de ressources*</span><span class="sxs-lookup"><span data-stu-id="9f75b-118">*Resource pool scenarios*</span></span>

