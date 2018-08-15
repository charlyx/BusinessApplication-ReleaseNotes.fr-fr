---
title: Validation de la prise d'effet de date sur les tarifs
description: "Grâce à la validation, les utilisateurs de Project Service évitent les erreurs dans la définition des prix par défaut. Ces erreurs pourraient être dues à plusieurs tarifs effectifs à une certaine date."
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
ms.openlocfilehash: 45118e9b8562da5b617c2ad1e983ffddc466259c
ms.contentlocale: fr-fr
ms.lasthandoff: 08/15/2018

---
#   <a name="date-effectivity-validation-on-price-lists"></a><span data-ttu-id="e0fd2-103">Validation de la prise d'effet de date sur les tarifs</span><span class="sxs-lookup"><span data-stu-id="e0fd2-103">Date effectivity validation on price lists</span></span>

[!include[project-service banner](../../../includes/project-service.md)]





<span data-ttu-id="e0fd2-104">Grâce à cette fonctionnalité, les utilisateurs de Project Service évitent les erreurs dans la définition des prix par défaut. Ces erreurs pourraient être dues à plusieurs tarifs effectifs à une certaine date.</span><span class="sxs-lookup"><span data-stu-id="e0fd2-104">This feature ensures that Project Service users avoid errors in price defaulting arising from having more than one price list effective for a certain date.</span></span> <span data-ttu-id="e0fd2-105">Les clients de Project Service savent que ce produit permet d'associer plusieurs tarifs de projet à des devis, des contrats de projet, et à des unités d'organisation.</span><span class="sxs-lookup"><span data-stu-id="e0fd2-105">As Project Service customers are aware, the product allows for multiple project price lists to be associated to quotes, project contracts, and organizational units.</span></span> <span data-ttu-id="e0fd2-106">Cela permet en effet de compenser les modifications de tarifs liées à l'inflation et représentées par des tarifs avec différentes dates effectives.</span><span class="sxs-lookup"><span data-stu-id="e0fd2-106">This is to allow for inflationary pricing changes represented by price lists with different date effectivities.</span></span> 

<span data-ttu-id="e0fd2-107">Avec cette fonctionnalité, le système valide la configuration des tarifs pour garantir qu'aucune date effective ne se chevauche à un moment donné (un projet ou un contact, par exemple).</span><span class="sxs-lookup"><span data-stu-id="e0fd2-107">With this feature, the system will validate the price list setup to ensure no overlapping date effectivities given a single context such as a project or a contract.</span></span> <span data-ttu-id="e0fd2-108">De plus, le système garantit d'évaluer correctement le travail lorsqu'une estimation sur un devis ou un contrat couvre plusieurs périodes tarifaires.</span><span class="sxs-lookup"><span data-stu-id="e0fd2-108">Also, the system will ensure that when an estimate on a quote or contract spans multiple price periods, the system is able to correctly price the work.</span></span> 

