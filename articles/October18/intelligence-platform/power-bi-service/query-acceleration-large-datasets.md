---
title: "Accélération des requêtes pour les jeux de données volumineux"
description: "Accélération des requêtes pour les jeux de données volumineux"
author: Annbe
manager: AnnBe
ms.date: 07/22/2018
ms.assetid: 04524b66-4727-4ce6-9cca-2b1439428497
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: b1a0f1e04786d2daef091fc6f6f9c168f2b005e7
ms.openlocfilehash: 53a14ef61ef0d2ba7b794e6fc5070f6588852da2
ms.contentlocale: fr-fr
ms.lasthandoff: 09/25/2018

---

#  <a name="query-acceleration-for-large-datasets-public-preview"></a><span data-ttu-id="1f0e2-103">Accélération des requêtes pour les grands ensembles de données (version préliminaire publique)</span><span class="sxs-lookup"><span data-stu-id="1f0e2-103">Query acceleration for large datasets (Public Preview)</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



<span data-ttu-id="1f0e2-104">Les utilisateurs peuvent créer des modèles [DirectQuery](https://docs.microsoft.com/power-bi/desktop-directquery-about) avec des données de toutes les tailles dans les sources, comme Spark et Azure SQL Data Warehouse, puis accélérer les requêtes courantes en créant des agrégations en mémoire avec certaines des données.</span><span class="sxs-lookup"><span data-stu-id="1f0e2-104">Users can create [DirectQuery](https://docs.microsoft.com/power-bi/desktop-directquery-about) models over any size data in sources, such as Spark and Azure SQL Data Warehouse, and then accelerate common queries by building in-memory aggregations over some of the data.</span></span> <span data-ttu-id="1f0e2-105">Les requêtes courantes utilisent le cache agrégé pour retourner des résultats en une fraction de seconde au lieu d'interroger directement la source.</span><span class="sxs-lookup"><span data-stu-id="1f0e2-105">Common queries use the aggregated cache to return results in a fraction of a second instead of directly querying the source.</span></span> <span data-ttu-id="1f0e2-106">Les utilisateurs peuvent créer des jeux de données massifs et continuer d'offrir des interrogations interactives.</span><span class="sxs-lookup"><span data-stu-id="1f0e2-106">Users can create datasets of massive size and still provide interactive querying.</span></span>

