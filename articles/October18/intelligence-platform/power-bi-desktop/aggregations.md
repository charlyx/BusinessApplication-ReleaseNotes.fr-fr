---
title: "Agrégations"
description: "Prise en charge de la mise en cache des requêtes d'agrégation tout continuant d'autoriser les utilisateurs à explorer au niveau du détail via DirectQuery"
author: MI77
manager: kimani
ms.date: 7/22/18
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: willthom
audience: developer, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: ec6fc313ef498181725c0e131d0e2ec1a91a90ce
ms.contentlocale: fr-fr
ms.lasthandoff: 08/16/2018

---

# <a name="aggregations-public-preview"></a><span data-ttu-id="40d61-103">Agrégations (version préliminaire publique)</span><span class="sxs-lookup"><span data-stu-id="40d61-103">Aggregations (Public Preview)</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]

<span data-ttu-id="40d61-104">Le volumes de données importants nécessitent de nouveaux modes de stockage des informations pour pouvoir effectuer des analyses interactives fractionnées avec des états détaillés approfondis.</span><span class="sxs-lookup"><span data-stu-id="40d61-104">Massive volumes of data require new ways of storing information to balance the needs of slice-and-dice interactive analysis with deep, detail-level reporting.</span></span> <span data-ttu-id="40d61-105">Les agrégations permettent aux développeurs de modèles de mettre en évidence les valeurs mises en cache à un niveau élevé d'analyse interactive, tout en continuant d'autoriser les utilisateurs à explorer au niveau du détail les données interrogées dans les données sous-jacentes.</span><span class="sxs-lookup"><span data-stu-id="40d61-105">Aggregations allow model developers to surface cached values at a high level for interactive analysis, but still let users drill down to detailed data that is queried from the underlying data.</span></span>

<span data-ttu-id="40d61-106">Vous pouvez créer des modèles DirectQuery à partir de sources de données volumineuses, telles que les clusters Spark, ou des entrepôts de données massifs.</span><span class="sxs-lookup"><span data-stu-id="40d61-106">You can create DirectQuery models over massive-scale data sources such as Spark clusters, or massive data warehouses.</span></span> <span data-ttu-id="40d61-107">Pour l'analyse interactive, l'exécution de requêtes directement dans ces jeux de données est peu pratique.</span><span class="sxs-lookup"><span data-stu-id="40d61-107">For interactive analysis, running queries directly against these datasets is impractical.</span></span> <span data-ttu-id="40d61-108">Mais pour les jeux de données pouvant atteindre des centaines de téraoctets, les données ne peuvent pas toutes être mises en cache en mémoire.</span><span class="sxs-lookup"><span data-stu-id="40d61-108">But for datasets that could be as large as hundreds of terabytes, the data cannot all be cached in memory.</span></span> <span data-ttu-id="40d61-109">Les agrégations vous permettent de mettre uniquement en cache les données agrégées dans la mémoire pour un accès rapide.</span><span class="sxs-lookup"><span data-stu-id="40d61-109">Aggregations lets you cache just aggregate data into memory for fast access.</span></span> <span data-ttu-id="40d61-110">Vous définissez des tables dans votre modèle de données en tant que table d'agrégation, associée aux tables au niveau de détail.</span><span class="sxs-lookup"><span data-stu-id="40d61-110">You define tables in your data model as an aggregate table, linked to tables at the detail level.</span></span> 

<span data-ttu-id="40d61-111">Les tables de détail restent en mode DirectQuery mais les agrégats sont définis comme étant en mode mixte, afin que les données soient également mises en cache dans la mémoire au niveau agrégé.</span><span class="sxs-lookup"><span data-stu-id="40d61-111">The detail tables stay in DirectQuery mode but the aggregates are defined as being in dual mode so the data is also cached in memory at the aggregate level.</span></span> <span data-ttu-id="40d61-112">Si les utilisateurs exécutent des requêtes ou créent des visuels pouvant être renseignés par le cache en mémoire, les résultats en sont extraits.</span><span class="sxs-lookup"><span data-stu-id="40d61-112">If users run queries or create visuals that can be answered from the in-memory cache, the results are retrieved from there.</span></span> <span data-ttu-id="40d61-113">Mais si la requête nécessite les données de détails, elle est envoyée à la source DirectQuery sous-jacente de façon dynamique.</span><span class="sxs-lookup"><span data-stu-id="40d61-113">But if the query requires the detail data, it’s pushed down to the underlying DirectQuery source dynamically.</span></span> <span data-ttu-id="40d61-114">Cette expérience est transparente pour l'utilisateur dans son état Power BI.</span><span class="sxs-lookup"><span data-stu-id="40d61-114">The end user doesn’t see any difference in experience in their Power BI report.</span></span>

<!--
### Who uses this feature
This feature is intended for advanced modelers. It enables them to create data models with aggregate tables linked together to make sure that their end-user reports are designed to encourage filtering of data before queries are served from the DirectQuery source. 
## Status
### Development status
In development
#### Target timeframe
October ‘18
-->

