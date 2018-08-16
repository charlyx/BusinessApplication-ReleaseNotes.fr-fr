---
title: "Modèles composites"
description: "Prise en charge du mélange de sources de données pour DirectQuery et pour l'importation dans Power BI Desktop"
author: MI77
manager: kimani
ms.date: 7/22/18
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: willthom
audience: developer, citizen developer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: f32678967b820a258a7ad9a37325f99bf11a6cc7
ms.contentlocale: fr-fr
ms.lasthandoff: 08/16/2018

---

# <a name="composite-models-public-preview"></a><span data-ttu-id="acc94-103">Modèles composites (version préliminaire publique)</span><span class="sxs-lookup"><span data-stu-id="acc94-103">Composite models (Public Preview)</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]

<span data-ttu-id="acc94-104">Les modèles composites vous permettent de mélanger des sources de données DirectQuery tabulaires et importées, mais aussi d'avoir plusieurs sources de données DirectQuery tabulaires.</span><span class="sxs-lookup"><span data-stu-id="acc94-104">Composite models allow you to mix import and tabular direct query sources as well as have multiple tabular DirectQuery sources.</span></span> <span data-ttu-id="acc94-105">Vous pouvez ainsi étoffer vos modèles de données d'entreprise avec des tables importées.</span><span class="sxs-lookup"><span data-stu-id="acc94-105">This lets you augment your enterprise data models with imported tables.</span></span> 

<span data-ttu-id="acc94-106">Les modeleurs peuvent créer un fichier Power BI Desktop sur une source de données DirectQuery, puis ajouter des tables importées à partir d'une autre source de données.</span><span class="sxs-lookup"><span data-stu-id="acc94-106">Modelers can create a Power BI Desktop file over a DirectQuery datasource, and then also add tables that are imported from another data source.</span></span> <span data-ttu-id="acc94-107">Pour prendre en charge cette nouvelle structure de modèle, nous mettons également en place des relations plusieurs-à-plusieurs et des tables en mode mixte, ce qui signifie qu'elles peuvent agir en tant qu'outil d'importation ou DirectQuery, selon les autres tables que vous ajoutez aux visuels.</span><span class="sxs-lookup"><span data-stu-id="acc94-107">To support this new model structure, we also are introducing many-to-many relationships and tables that are in dual mode, which means they can act as import or DirectQuery, depending on what other tables you add to the visuals.</span></span> <span data-ttu-id="acc94-108">Power BI répond alors intelligemment à vos questions, soit à partir des données importées, soit en envoyant une requête à la source de données sous-jacente.</span><span class="sxs-lookup"><span data-stu-id="acc94-108">Power BI will then intelligently serve answers to your analyses from either the imported data or by pushing a query to the underlying datasource.</span></span>

<!--
### Who uses this feature
This feature is intended for model developers. 
## Status
### Development status
In development
#### Target timeframe
October ‘18
-->

