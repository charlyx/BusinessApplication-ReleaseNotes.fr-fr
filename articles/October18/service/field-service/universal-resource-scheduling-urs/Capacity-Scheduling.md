---
title: "Planification de la capacité"
description: "Planification de la capacité"
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
ms.openlocfilehash: 832f1714f8cce2602dd724f95337a0c7d4ad6a17
ms.contentlocale: fr-fr
ms.lasthandoff: 08/15/2018

---




#  <a name="capacity-scheduling"></a><span data-ttu-id="3b673-103">Planification de la capacité</span><span class="sxs-lookup"><span data-stu-id="3b673-103">Capacity scheduling</span></span>

[!include[field-service banner](../../../includes/field-service.md)]



<span data-ttu-id="3b673-104">Dans les besoins en ressources, il est désormais possible de spécifier la quantité d'effort qu'une ressource doit fournir.</span><span class="sxs-lookup"><span data-stu-id="3b673-104">Resource requirements can now specify how much effort a requirement needs from a resource.</span></span> <span data-ttu-id="3b673-105">Lors de la planification, l'assistant Planifier regarde la capacité définie dans les heures de travail d'une ressource afin de vérifier si elle peut encore fournir l'effort nécessaire.</span><span class="sxs-lookup"><span data-stu-id="3b673-105">When scheduling, the Schedule Assistant will look at a resource’s defined capacity on its work hours to check if the necessary effort is available.</span></span> <span data-ttu-id="3b673-106">La capacité d'une ressource peut considérablement varier au cours d'une journée.</span><span class="sxs-lookup"><span data-stu-id="3b673-106">A resource's capacity can vary even within a day.</span></span>

<span data-ttu-id="3b673-107">La planification de la capacité est surtout utile lors de la réservation d'une installation.</span><span class="sxs-lookup"><span data-stu-id="3b673-107">Capacity scheduling is exceptionally useful when booking a facility.</span></span> <span data-ttu-id="3b673-108">Par exemple, un fourgon peut nécessiter deux fois plus d'espace qu'une voiture standard.</span><span class="sxs-lookup"><span data-stu-id="3b673-108">By way of example, a van may require twice the space as a standard car.</span></span> <span data-ttu-id="3b673-109">Vous pouvez créer une installation ayant une certaine capacité, mais au moment de la réservation pour un fourgon, c'est comme si vous réserviez pour deux voitures ou six motos.</span><span class="sxs-lookup"><span data-stu-id="3b673-109">You can now create a facility with a certain capacity, but when booking time to work on a van, it consumes the capacity of the facility as if you were booking two cars or six motorcycles.</span></span>

<span data-ttu-id="3b673-110">Le tableau de planification propose également un indicateur visuel lorsqu'une ressource a de la capacité supplémentaire même s'il existe une réservation à un moment donné.</span><span class="sxs-lookup"><span data-stu-id="3b673-110">The Schedule Board will also offer a visual indicator when a resource has additional capacity even though there is a booking at a given time.</span></span>

* <span data-ttu-id="3b673-111">Exemple concret</span><span class="sxs-lookup"><span data-stu-id="3b673-111">Sample use cases</span></span>
    * <span data-ttu-id="3b673-112">Augmentation du personnel où les ressources n'ont pas de nom.</span><span class="sxs-lookup"><span data-stu-id="3b673-112">Staff augmentation where resources are unnamed.</span></span>
    * <span data-ttu-id="3b673-113">Ressources efficaces.</span><span class="sxs-lookup"><span data-stu-id="3b673-113">Efficient resources.</span></span>
        * <span data-ttu-id="3b673-114">Un employé peut réparer deux vélos pendant qu'un autre n'en réparer qu'un seul.</span><span class="sxs-lookup"><span data-stu-id="3b673-114">Person can fix two bikes in the time a typical person can fix one.</span></span>
    * <span data-ttu-id="3b673-115">Espace physique.</span><span class="sxs-lookup"><span data-stu-id="3b673-115">Physical space.</span></span>
        * <span data-ttu-id="3b673-116">Un espace de travail peut contenir deux voitures ou un fourgon.</span><span class="sxs-lookup"><span data-stu-id="3b673-116">One workspace can fit two cars or one van.</span></span>
        * <span data-ttu-id="3b673-117">Créez une « classe » en tant que ressource, et autorisez jusqu'à 10 clients à s'y inscrire.</span><span class="sxs-lookup"><span data-stu-id="3b673-117">Create a “class” as a resource, and allow up to 10 customers to be booked to the class.</span></span>
> <span data-ttu-id="3b673-118">Les ressources qui effectuent le travail sur le site ne peuvent pas avoir la capacité de plus d'une personne.</span><span class="sxs-lookup"><span data-stu-id="3b673-118">Resources that perform onsite work cannot have a capacity of more than one.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="3b673-119">![](media/Additional-Capacity.png "Capacité supplémentaire")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="3b673-119">![](media/Additional-Capacity.png "Additional Capacity")
<!-- picture --></span></span>

<span data-ttu-id="3b673-120">*Tableau de planification affichant une ressource avec une ligne de capacité supplémentaire développée*</span><span class="sxs-lookup"><span data-stu-id="3b673-120">*Schedule Board showing a resource with additional capacity row expanded*</span></span>

