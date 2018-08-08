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
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 40cbd22fb19eb8a5799b6ccb8a9ea5eec6a1576f
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---

# <a name="aggregations-public-preview"></a>Agrégations (version préliminaire publique)

[!include[banner](../../../includes/banner.md)]


Le volumes de données importants nécessitent de nouveaux modes de stockage des informations pour pouvoir effectuer des analyses interactives fractionnées avec des états détaillés approfondis. Les agrégations permettent aux développeurs de modèles de mettre en évidence les valeurs mises en cache à un niveau élevé d'analyse interactive, tout en continuant d'autoriser les utilisateurs à explorer au niveau du détail les données interrogées dans les données sous-jacentes.

Vous pouvez créer des modèles DirectQuery à partir de sources de données volumineuses, telles que les clusters Spark, ou des entrepôts de données massifs. Pour l'analyse interactive, l'exécution de requêtes directement dans ces jeux de données est peu pratique. Mais pour les jeux de données pouvant atteindre des centaines de téraoctets, les données ne peuvent pas toutes être mises en cache en mémoire. Les agrégations vous permettent de mettre uniquement en cache les données agrégées dans la mémoire pour un accès rapide. Vous définissez des tables dans votre modèle de données en tant que table d'agrégation, associée aux tables au niveau de détail. 

Les tables de détail restent en mode DirectQuery mais les agrégats sont définis comme étant en mode mixte, afin que les données soient également mises en cache dans la mémoire au niveau agrégé. Si les utilisateurs exécutent des requêtes ou créent des visuels pouvant être renseignés par le cache en mémoire, les résultats en sont extraits. Mais si la requête nécessite les données de détails, elle est envoyée à la source DirectQuery sous-jacente de façon dynamique. Cette expérience est transparente pour l'utilisateur dans son état Power BI.

<!--
### Who uses this feature
This feature is intended for advanced modelers. It enables them to create data models with aggregate tables linked together to make sure that their end-user reports are designed to encourage filtering of data before queries are served from the DirectQuery source. 
## Status
### Development status
In development
#### Target timeframe
October ‘18
-->

