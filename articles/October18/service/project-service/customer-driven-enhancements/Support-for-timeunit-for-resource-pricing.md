---
title: "Prise en charge de plusieurs unités de temps sur un tarif unique"
description: "Les tarifs vous permettent de spécifier des prix pour plusieurs unités de temps"
author: rumant
manager: shellyhaverkamp
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: rumant
audience: developer, admin, end user, citizen developer, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: ec0b4b4fbef8ec0a6ca8c3d59c5ded858615d6c3
ms.contentlocale: fr-fr
ms.lasthandoff: 08/15/2018

---
#   <a name="support-for-multiple-time-units-on-a-single-price-list"></a><span data-ttu-id="839ce-103">Prise en charge de plusieurs unités de temps sur un tarif unique</span><span class="sxs-lookup"><span data-stu-id="839ce-103">Support for multiple time units on a single price list</span></span>

[!include[project-service banner](../../../includes/project-service.md)]




<span data-ttu-id="839ce-104">Project Service prend en charge la tarification de la durée d'une ressource.</span><span class="sxs-lookup"><span data-stu-id="839ce-104">Project Service supports pricing resource time.</span></span> <span data-ttu-id="839ce-105">Les utilisateurs peuvent choisir de configurer des prix à l'heure, à la journée ou toute autre unité de temps.</span><span class="sxs-lookup"><span data-stu-id="839ce-105">Users may choose to set up prices in hours, days, or any other unit of time.</span></span> <span data-ttu-id="839ce-106">Toutefois, l'unité du temps est décidée dans l'en-tête des tarifs et ne peuvent pas être modifiée sur les lignes de paramétrage de prix individuelles de la durée de la ressource.</span><span class="sxs-lookup"><span data-stu-id="839ce-106">One current limitation is that the unit of time is decided on the header of the price list, and can't be changed on individual price setup lines for resource time.</span></span> 

<span data-ttu-id="839ce-107">Avec cette mise à jour, chaque tarif vous permet de spécifier des prix pour plusieurs unités de temps.</span><span class="sxs-lookup"><span data-stu-id="839ce-107">With this update, each price list will allow you to specify prices for multiple time units.</span></span> <span data-ttu-id="839ce-108">Ceci est particulièrement utile pour les entreprises qui opèrent dans différentes régions géographiques avec des codes et pratiques de travail distincts.</span><span class="sxs-lookup"><span data-stu-id="839ce-108">This is particularly useful for companies that operate across geographies with different labor laws and practices.</span></span> 

<span data-ttu-id="839ce-109">Par exemple : Lorsque vous définissez un taux pour un « jour ouvrable », chaque division d'une société de service de projet multinationale peut avoir sa propre définition d'un jour ouvrable.</span><span class="sxs-lookup"><span data-stu-id="839ce-109">For example: When expressing rates for a “working day,” each division of a multi-national project service company might have its own definition of a working day.</span></span> <span data-ttu-id="839ce-110">Sa division en Inde peut ouvrir 8 heures par jours, tandis que sa division en Écosse peut ouvrir 7,5 heures par jour.</span><span class="sxs-lookup"><span data-stu-id="839ce-110">Its India division might work 8-hour days, while its Scotland division might work 7.5-hour days.</span></span> <span data-ttu-id="839ce-111">Avec cette fonctionnalité, les sociétés peuvent paramétrer les prix journaliers à l'aide de l'unité de jour spécifique à chaque division.</span><span class="sxs-lookup"><span data-stu-id="839ce-111">With this feature, companies will be able to set up prices per day using the day unit that is specific to each division.</span></span>

<span data-ttu-id="839ce-112">![Taux de coûts pour plusieurs unités de temps sur les tarifs](media/multiple-time-unit-on-pricelist.png "Taux de coûts pour plusieurs unités de temps sur les tarifs")
<!-- Picture 2 --></span><span class="sxs-lookup"><span data-stu-id="839ce-112">![Cost rates for multiple time units on Price List](media/multiple-time-unit-on-pricelist.png "Cost rates for multiple time units on price list")
<!-- Picture 2 --></span></span>

