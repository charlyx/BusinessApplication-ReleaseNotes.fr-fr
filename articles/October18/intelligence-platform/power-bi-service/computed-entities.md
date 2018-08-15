---
title: "Entités calculées"
description: "La prise en charge des entités calculées permet à des tiers de créer des applications Power BI en exploitant des flux de données avec des informations plus riches et des fonctionnalités d'IA."
author: adiregev
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: adiregev
audience: 
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 1cf4c587631512b432a437794c2825f40863f43f
ms.contentlocale: fr-fr
ms.lasthandoff: 08/15/2018

---
# <a name="computed-entities-public-preview"></a><span data-ttu-id="856a8-103">Entités calculées (Version préliminaire publique)</span><span class="sxs-lookup"><span data-stu-id="856a8-103">Computed entities (Public Preview)</span></span>  

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



<span data-ttu-id="856a8-104">Les entités de flux de données sont enregistrées dans des dossiers compatibles Common Data Model (dossiers CDM), dans Azure Data Lake Storage Gen2.</span><span class="sxs-lookup"><span data-stu-id="856a8-104">Dataflow entities are stored in Common Data Model compliant folders (CDM folders), in Azure Data Lake Storage Gen2.</span></span> <span data-ttu-id="856a8-105">Une fois les entités chargées dans les dossiers CDM, vous pouvez générer de nouvelles informations en transformant, en modifiant, et en enrichissant des entités, et en regroupant des données à grande échelle.</span><span class="sxs-lookup"><span data-stu-id="856a8-105">After your entities have been loaded to CDM folders, you can generate new insights by transforming, modifying, and enriching entities, and aggregating large-scale data.</span></span> <span data-ttu-id="856a8-106">Ces entités nouvellement créées sont également stockées dans des dossiers CDM.</span><span class="sxs-lookup"><span data-stu-id="856a8-106">These newly created entities are also stored in CDM folders.</span></span> <span data-ttu-id="856a8-107">L'analyse statique des expressions Power Query M permet d'identifier automatiquement les dépendances entre les entités. Ainsi, elles sont toujours mises à jour dans l'ordre optimal, sans intervention manuelle.</span><span class="sxs-lookup"><span data-stu-id="856a8-107">Static analysis of Power Query M expressions makes it possible to identify dependencies between entities automatically, so they’ll always be updated in the optimal order, with no need for manual orchestration.</span></span> 

<span data-ttu-id="856a8-108">La prise en charge des entités calculées permet à des tiers de créer des applications Power BI en exploitant des flux de données avec des informations plus riches et des fonctionnalités d'IA.</span><span class="sxs-lookup"><span data-stu-id="856a8-108">Support for computed entities allows third parties to build Power BI apps leveraging dataflows with richer insights and AI capabilities.</span></span> <span data-ttu-id="856a8-109">Par exemple, vous pouvez enrichir une entité de compte client à partir de Dynamics 365 for Sales avec des informations provenant des tickets de service dans Dynamics 365 for Service et des informations répondant aux besoins des clients à partir de Office 365.</span><span class="sxs-lookup"><span data-stu-id="856a8-109">For example, you could enrich a customer account entity from Dynamics 365 for Sales with information from open service tickets in Dynamics 365 for Service, and relevant customer meeting information from Office 365.</span></span>
<span data-ttu-id="856a8-110">Power BI Premium est requis pour pouvoir actualiser les entités calculées.</span><span class="sxs-lookup"><span data-stu-id="856a8-110">Refreshing computed entities requires Power BI Premium.</span></span> 

