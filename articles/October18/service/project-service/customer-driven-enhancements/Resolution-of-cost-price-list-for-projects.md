---
title: "Résolution de la liste des prix de revient en multidevise sur des projets"
description: "Résolution de la liste des prix de revient en multidevise sur des projets"
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
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: dc40b9862dcb8c4e8eeb12168ab8497bc131c000
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
#  <a name="resolution-of-multi-currency-cost-price-list-on-projects"></a><span data-ttu-id="29b54-103">Résolution de la liste des prix de revient en multidevise sur des projets</span><span class="sxs-lookup"><span data-stu-id="29b54-103">Resolution of multi-currency cost price list on projects</span></span> 


[!include[banner](../../../../includes/banner.md)]

<span data-ttu-id="29b54-104">Project Service résout les tarifs pour les taux de coût des projets en mettant en correspondance la devise de l'unité d'organisation propriétaire du projet avec la devise des tarifs.</span><span class="sxs-lookup"><span data-stu-id="29b54-104">Project Service resolves the price list for cost rates on projects by matching the currency of the organizational unit that owns the project to the price list currency.</span></span> <span data-ttu-id="29b54-105">Dans le cas où des tarifs peuvent comporter des prix dans plusieurs devises, il doit y avoir des tarifs principaux avec des lignes de taux de coût dans plusieurs devises, et ces tarifs doivent être utilisés par tous les projets de façon globale.</span><span class="sxs-lookup"><span data-stu-id="29b54-105">In the case where a price list may have prices in multiple currencies, it's expected that there would be one master price list with cost rate lines in multiple currencies, and that this price list would be used by all projects globally.</span></span> 

<span data-ttu-id="29b54-106">Dans ce cas, résoudre une liste des prix de revient pour un projet à l'aide de la devise dans l'en-tête des tarifs ne fonctionne pas.</span><span class="sxs-lookup"><span data-stu-id="29b54-106">In that situation, resolving a cost price list for a project using the currency on the header of the price list would not work.</span></span> <span data-ttu-id="29b54-107">Avec cette fonctionnalité, il est possible de configurer la résolution par défaut de la liste des prix de revient du projet.</span><span class="sxs-lookup"><span data-stu-id="29b54-107">With this feature, it will be configurable to set up the default resolution of the project cost price list.</span></span> <span data-ttu-id="29b54-108">Les options disponibles consistent à mettre en correspondance la devise de coût du projet avec l'en-tête des tarifs tel que cela fonctionne actuellement ou d'utiliser les tarifs gérés globalement quelle que soit la devise dans son en-tête.</span><span class="sxs-lookup"><span data-stu-id="29b54-108">The options available would be to match the project’s cost currency with the header of the price list as it works today or to use the globally managed price list regardless of its header currency.</span></span>  



