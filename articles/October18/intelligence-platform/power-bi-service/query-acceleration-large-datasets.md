---
title: "Accélération des requêtes pour les jeux de données volumineux"
description: "Accélération des requêtes pour les jeux de données volumineux"
author: MargoC
manager: AnnBe
ms.date: 07/22/2018
ms.assetid: 04524b66-4727-4ce6-9cca-2b1439428497
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 285bf3e5cbfb965d27f0b717b5cdc8fa332e28d6
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---

#  <a name="query-acceleration-for-large-datasets-public-preview"></a>Accélération des requêtes pour les grands ensembles de données (version préliminaire publique)

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



Les utilisateurs peuvent créer des modèles [DirectQuery](https://docs.microsoft.com/power-bi/desktop-directquery-about) avec des données de toutes les tailles dans les sources, comme Spark et Azure SQL Data Warehouse, puis accélérer les requêtes courantes en créant des agrégations en mémoire avec certaines des données. Les requêtes courantes utilisent le cache agrégé pour retourner des résultats en une fraction de seconde au lieu d'interroger directement la source. Les utilisateurs peuvent créer des jeux de données massifs et continuer d'offrir des interrogations interactives.

