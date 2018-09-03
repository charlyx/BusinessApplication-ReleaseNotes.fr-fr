---
title: Nouvelles mesures pour la surveillance de la charge de travail Azure
description: "Quatre nouvelles mesures ont été ajoutées pour surveiller la consommation des ressources Power BI Embedded et déclencher des actions lorsque des seuils configurables sont dépassés."
author: MargoC
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 082d21ac-805e-4007-8810-f1838369569c
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 38c5ad6fa4ff1160d482cb5d62a7701990bff15a
ms.contentlocale: fr-fr
ms.lasthandoff: 08/15/2018

---
#  <a name="new-metrics-for-azure-workload-monitoring"></a><span data-ttu-id="ec606-103">Nouvelles mesures pour la surveillance de la charge de travail Azure</span><span class="sxs-lookup"><span data-stu-id="ec606-103">New metrics for Azure workload monitoring</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



<span data-ttu-id="ec606-104">À présent que de nouvelles charges de travail sont disponibles dans les rapports paginés et les flux de données Power BI, trois nouvelles mesures seront ajoutées pour surveiller la consommation de la charge de travail et des ressources Power BI Embedded et déclencher des actions en cas de dépassement de seuils configurables.</span><span class="sxs-lookup"><span data-stu-id="ec606-104">As new workloads now available in Power BI- Paginated reports and Data flows, three new metrics will be added to monitor Power BI Embedded resource and workload consumption and trigger actions when configurable thresholds are exceeded.</span></span> <span data-ttu-id="ec606-105">Les nouvelles mesures reflèteront chacune des charges de travail de la ressource.</span><span class="sxs-lookup"><span data-stu-id="ec606-105">The new metrics will reflect each of the workloads in the resource.</span></span> <span data-ttu-id="ec606-106">Ces nouvelles métriques sont les suivantes :</span><span class="sxs-lookup"><span data-stu-id="ec606-106">The new metrics are:</span></span>

<span data-ttu-id="ec606-107">•   Consommation du processeur •   Consommation de la mémoire •   Consommation de l'allocation mémoire (y compris la pagination de la mémoire)</span><span class="sxs-lookup"><span data-stu-id="ec606-107">•   CPU Consumption •   Memory Consumption •   Memory Commit Consumption (Incl. memory paging)</span></span>

<span data-ttu-id="ec606-108">Les développeurs peuvent utiliser Azure pour définir des seuils afin de déclencher des actions spécifiques à l'aide d'alertes, telles que la montée en charge automatique de la ressource chaque fois qu'un moniteur spécifique franchit un seuil défini.</span><span class="sxs-lookup"><span data-stu-id="ec606-108">Developers can use Azure to define thresholds to trigger specific actions using alerts, such as automatic scale-up of the resource whenever a specific monitor crosses a defined threshold.</span></span>

