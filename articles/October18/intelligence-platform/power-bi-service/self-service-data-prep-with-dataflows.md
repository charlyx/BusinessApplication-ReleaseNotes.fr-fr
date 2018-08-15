---
title: "Préparation de données en libre-service avec des flux de données"
description: "Les flux de données réduisent la durée, la complexité et le coût de développement des analyses commerciales réalisées à partir de données couvrant plusieurs applications de gestion et sources de données."
author: adiregev
manager: PaBenja
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
ms.openlocfilehash: 2ceb2263e9fb343cb8feb050198f8a16050c2e5f
ms.contentlocale: fr-fr
ms.lasthandoff: 08/15/2018

---

# <a name="self-service-data-prep-with-dataflows"></a><span data-ttu-id="e4dac-103">Préparation de données en libre-service avec des flux de données</span><span class="sxs-lookup"><span data-stu-id="e4dac-103">Self-service data prep with dataflows</span></span> 

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



<span data-ttu-id="e4dac-104">Power BI présente des flux de données permettant aux organisations d'unifier les données issues de sources disparates et de les préparer à des fins de modélisation.</span><span class="sxs-lookup"><span data-stu-id="e4dac-104">Power BI introduces dataflows to help organizations unify data from disparate sources and prepare it for modeling.</span></span> <span data-ttu-id="e4dac-105">Les analystes peuvent créer facilement des flux de données à l'aide d'outils conviviaux en libre-service.</span><span class="sxs-lookup"><span data-stu-id="e4dac-105">Analysts can easily create dataflows, using familiar, self-service tools.</span></span> <span data-ttu-id="e4dac-106">Les flux de données permettent d'ingérer, de transformer, d'intégrer et d'enrichir le big data en définissant des connexions de source de données, une logique d'ETL, des planifications d'actualisation, etc.</span><span class="sxs-lookup"><span data-stu-id="e4dac-106">Dataflows are used to ingest, transform, integrate, and enrich big data by defining data source connections, ETL logic, refresh schedules, and more.</span></span> <span data-ttu-id="e4dac-107">Les données sont stockées en tant qu'entités dans des dossiers compatibles Common Data Model dans Azure Data Lake Storage Gen2.</span><span class="sxs-lookup"><span data-stu-id="e4dac-107">Data is stored as entities in Common Data Model compliant folders in Azure Data Lake Storage Gen2.</span></span> <span data-ttu-id="e4dac-108">Les flux de données sont créés et gérés dans des espaces de travail d'applications utilisant le service Power BI.</span><span class="sxs-lookup"><span data-stu-id="e4dac-108">Dataflows are created and managed in app workspaces by using the Power BI service.</span></span>   

<span data-ttu-id="e4dac-109">Vous pouvez utiliser des flux de données pour ingérer des données issues d'un jeu volumineux et croissant de données sources locales et basées sur le cloud, comme Dynamics 365, Salesforce, Azure SQL Database, Excel, SharePoint, etc.</span><span class="sxs-lookup"><span data-stu-id="e4dac-109">You can use dataflows to ingest data from a large and growing set of supported on-premises and cloud- based data sources including Dynamics 365, Salesforce, Azure SQL Database, Excel, SharePoint, and more.</span></span>

<span data-ttu-id="e4dac-110">Vous pouvez ensuite mapper les données à des entités Common Data Model connues, modifier et étendre les entités existantes, et créer des entités personnalisées.</span><span class="sxs-lookup"><span data-stu-id="e4dac-110">You can then map data to known Common Data Model entities, modify and extend existing entities, and create custom entities.</span></span> <span data-ttu-id="e4dac-111">Les utilisateurs avancés peuvent créer des flux de données entièrement personnalisés, à l'aide d'une expérience de création Power Query en libre-service, « low-code no-code », similaire à l'expérience Power Query que des millions utilisateurs de Power BI Desktop et d'Excel connaissent déjà.</span><span class="sxs-lookup"><span data-stu-id="e4dac-111">Advanced users can create fully-customized dataflows, using a self-service, low- code/no-code, built-in Power Query authoring experience, similar to the Power Query experience that millions of Power BI Desktop and Excel users already know.</span></span>  

<span data-ttu-id="e4dac-112">Une fois que vous avez créé un flux de données, vous pouvez utiliser Power BI Desktop et le service Power BI pour créer des jeux de données, des états, des tableaux de bord et des applications tirant parti de la puissance de Common Data Model pour fournir des aperçus détaillés à vos activités commerciales.</span><span class="sxs-lookup"><span data-stu-id="e4dac-112">Once you’ve created a dataflow, you can use Power BI Desktop and the Power BI service to create datasets, reports, dashboards, and apps that leverage the power of the Common Data Model to drive deep insights into your business activities.</span></span> 

<span data-ttu-id="e4dac-113">La planification d'actualisation de flux de données est gérée directement depuis l'espace de travail dans lequel votre flux de données a été créé, tout comme vos jeux de données.</span><span class="sxs-lookup"><span data-stu-id="e4dac-113">Dataflow refresh scheduling is managed directly from the workspace in which your dataflow was created, just like your datasets.</span></span> 

<span data-ttu-id="e4dac-114">La version préliminaire inclut plus de 20 connecteurs aux sources de données courantes, tels qu'Excel, SQL Server, Oracle, Azure SQL Datawarehouse, Dynamics 365 et Salesforce.</span><span class="sxs-lookup"><span data-stu-id="e4dac-114">The preview includes more than 20 connectors to common data sources such as Excel, SQL Server, Oracle, Azure SQL Datawarehouse, Dynamics 365, and Salesforce.</span></span> 

