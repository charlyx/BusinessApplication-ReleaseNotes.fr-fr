---
title: "CFS - Intégration avec IoT Central"
description: "Pour la première étape de l'intégration, l'accent sera mis sur la solution d'intégration via Flow."
author: MargoC
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: ce0f2e97-8ded-4530-9c50-fc82ce4a6171
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 822172ac452b6513ec700dc421fa61b7faffa195
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
#  <a name="cfs---integration-with-iot-central"></a>CFS - Intégration avec IoT Central


[!include[banner](../../../../includes/banner.md)]

Pour la première étape de l'intégration, l'accent sera mis sur la solution d'intégration via Microsoft Flow. Il s'agit d'une communication à sens unique entre IoT Central et Connected Field Service. Lorsque IoT Central surveille les appareils à distance, toutes les mesures qui dépassent des seuils définis dans IoT Central vont déclencher une alerte dans CFS. Les responsables du service après-vente pourront regrouper ces alertes selon des critères comme l'actif du client et le type d'incident.

> [!div class="mx-imgBorder"]
> ![](media/enhanced-iot-central-integration-1.png "Intégration IoT Central améliorée")
<!-- picture -->


Pour la version d'octobre 2018, les techniciens peuvent disposer et s'appuyer sur des appareils IoT sur site, avec quelques options selon l'état d'IoT Central.

-   Visuels sur l'état et les mesures de l'appareil IoT Central intégré directement au sein de l'application mobile Field Service.
-   Stockage des données de télémétrie à partir de l'IoT Central dans un blob Azure et activation d'un Power BI intégré pour visualiser les données.
-   Possibilité pour les techniciens de renvoyer des commandes à partir de l'application mobile Field Service à IoT Central.

