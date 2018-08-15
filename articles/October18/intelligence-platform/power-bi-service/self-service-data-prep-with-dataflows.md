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
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: d9823bc7031d847d66e8120ab3ddfa6c28e13390
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---

# <a name="self-service-data-prep-with-dataflows"></a>Préparation de données en libre-service avec des flux de données 

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



Power BI présente des flux de données permettant aux organisations d'unifier les données issues de sources disparates et de les préparer à des fins de modélisation. Les analystes peuvent créer facilement des flux de données à l'aide d'outils conviviaux en libre-service. Les flux de données permettent d'ingérer, de transformer, d'intégrer et d'enrichir le big data en définissant des connexions de source de données, une logique d'ETL, des planifications d'actualisation, etc. Les données sont stockées en tant qu'entités dans des dossiers compatibles Common Data Model dans Azure Data Lake Storage Gen2. Les flux de données sont créés et gérés dans des espaces de travail d'applications utilisant le service Power BI.   

Vous pouvez utiliser des flux de données pour ingérer des données issues d'un jeu volumineux et croissant de données sources locales et basées sur le cloud, comme Dynamics 365, Salesforce, Azure SQL Database, Excel, SharePoint, etc.

Vous pouvez ensuite mapper les données à des entités Common Data Model connues, modifier et étendre les entités existantes, et créer des entités personnalisées. Les utilisateurs avancés peuvent créer des flux de données entièrement personnalisés, à l'aide d'une expérience de création Power Query en libre-service, « low-code no-code », similaire à l'expérience Power Query que des millions utilisateurs de Power BI Desktop et d'Excel connaissent déjà.  

Une fois que vous avez créé un flux de données, vous pouvez utiliser Power BI Desktop et le service Power BI pour créer des jeux de données, des états, des tableaux de bord et des applications tirant parti de la puissance de Common Data Model pour fournir des aperçus détaillés à vos activités commerciales. 

La planification d'actualisation de flux de données est gérée directement depuis l'espace de travail dans lequel votre flux de données a été créé, tout comme vos jeux de données. 

La version préliminaire inclut plus de 20 connecteurs aux sources de données courantes, tels qu'Excel, SQL Server, Oracle, Azure SQL Datawarehouse, Dynamics 365 et Salesforce. 

