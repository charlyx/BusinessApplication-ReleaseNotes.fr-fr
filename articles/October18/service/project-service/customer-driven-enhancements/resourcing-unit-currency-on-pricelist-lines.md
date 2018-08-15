---
title: "Devise de l'unité d'allocation des ressources sur les lignes de prix du rôle pour le coût"
description: "Les taux des coûts pour la durée d'une ressource peuvent désormais être exprimés dans la devise de l'unité d'allocation des ressources"
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
ms.openlocfilehash: 3991215e52ecc9eb1cf741e880bc0c04bfec71e8
ms.contentlocale: fr-fr
ms.lasthandoff: 08/15/2018

---
#  <a name="resourcing-unit-currency-on-role-price-lines-for-cost"></a><span data-ttu-id="4dcba-103">Devise de l'unité d'allocation des ressources sur les lignes de prix du rôle pour le coût</span><span class="sxs-lookup"><span data-stu-id="4dcba-103">Resourcing unit currency on role price lines for cost</span></span> 

[!include[project-service banner](../../../includes/project-service.md)]




<span data-ttu-id="4dcba-104">Project Service permet uniquement une devise par tarifs, qui est spécifiée dans l'en-tête des tarifs.</span><span class="sxs-lookup"><span data-stu-id="4dcba-104">Project Service allows only one currency per price list, which is specified on the price list header.</span></span> <span data-ttu-id="4dcba-105">La ligne de tarifs de la tarification de la ressource dispose de la même devise spécifiée dans l'en-tête des tarifs.</span><span class="sxs-lookup"><span data-stu-id="4dcba-105">The price list line for resource pricing has the same currency specified on the price list header.</span></span> <span data-ttu-id="4dcba-106">Toutefois, pour les sociétés de service de projet internationales ayant une tarification centralisée pour toutes leurs divisions réparties dans différents pays, cela peut nécessiter la configuration de nombreuses données pour lesquelles elles devront définir séparément des tarifs dans chaque devise dans laquelle elles vendent ou engagent des coûts.</span><span class="sxs-lookup"><span data-stu-id="4dcba-106">However, for globally operating project service companies that have centralized pricing across all of their divisions across countries, this can necessitate a data-intensive setup where they'll need to set up a price list for each distinct currency that they sell or incur costs in.</span></span> 

<span data-ttu-id="4dcba-107">Avec cette fonctionnalité, Project Service permettra d'établir une devise au niveau de la ligne pour les prix des ressources différant de la devise de l'en-tête de tarifs.</span><span class="sxs-lookup"><span data-stu-id="4dcba-107">With this feature, Project Service will allow for a line-level currency for resource prices that differs from the price list header currency.</span></span> <span data-ttu-id="4dcba-108">La devise dans l'en-tête des tarifs sera utilisée comme valeur par défaut sur les lignes des prix des ressources.</span><span class="sxs-lookup"><span data-stu-id="4dcba-108">Currency on the price list header will be used as a default on the resource price lines.</span></span> <span data-ttu-id="4dcba-109">Ainsi, les grandes entreprises internationales souhaitant configurer leurs tarifs de manière plus centralisée pourront utiliser un tarif global avec des prix de ressources dans diverses devises.</span><span class="sxs-lookup"><span data-stu-id="4dcba-109">This way, large global firms that would like more centralized pricing setup may work with one global price list that specifies resource prices in many currencies.</span></span> <span data-ttu-id="4dcba-110">Cela peut également permettre des scénarios où les prix gérés par chaque unité d'allocation des ressources sont réunis en une liste de tarifs principale.</span><span class="sxs-lookup"><span data-stu-id="4dcba-110">This could also enable scenarios where prices managed by each resourcing unit come together as one master price list.</span></span>

<span data-ttu-id="4dcba-111">L'utilisation d'une monnaie unique par tarifs continuera de fonctionner, ce qui est utile pour les entreprises permettant une tarification plus centralisée et qui suivent les taux de change des ressources.</span><span class="sxs-lookup"><span data-stu-id="4dcba-111">Using a single currency per price list will still function, which benefits companies that allow for more decentralized pricing and that track exchange prices for resources.</span></span> <span data-ttu-id="4dcba-112">Cette fonctionnalité peut être personnalisée afin que les prix des ressource sur les tarifs correspondent à la devise dans l'en-tête de tarifs.</span><span class="sxs-lookup"><span data-stu-id="4dcba-112">This can be customized so that the resource prices on a price list follow the currency of the price list header.</span></span>

<span data-ttu-id="4dcba-113">![Tarifs des coûts avec des lignes de tarifs dans plusieurs devises](media/Resourcing-unit-currency-on-pricelist.png "Tarifs des coûts avec des lignes de tarifs dans plusieurs devises")
<!-- Picture 2 --></span><span class="sxs-lookup"><span data-stu-id="4dcba-113">![Price list for cost with price list lines in multiple currencies](media/Resourcing-unit-currency-on-pricelist.png "Price list for cost with price list lines in multiple currencies")
<!-- Picture 2 --></span></span>

