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
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: a93e3c09095e6033a960b8fccfcb04f2f3e1f470
ms.contentlocale: fr-fr
ms.lasthandoff: 08/15/2018

---
#  <a name="cfs---integration-with-iot-central"></a><span data-ttu-id="47ece-103">CFS - Intégration avec IoT Central</span><span class="sxs-lookup"><span data-stu-id="47ece-103">CFS - Integration with IoT Central</span></span>

[!include[field-service banner](../../../includes/field-service.md)]




<span data-ttu-id="47ece-104">Pour la première étape de l'intégration, l'accent sera mis sur la solution d'intégration via Microsoft Flow.</span><span class="sxs-lookup"><span data-stu-id="47ece-104">For the first phase of integration, the focus of the integration solution will be through Microsoft Flow.</span></span> <span data-ttu-id="47ece-105">Il s'agit d'une communication à sens unique entre IoT Central et Connected Field Service.</span><span class="sxs-lookup"><span data-stu-id="47ece-105">This is a one-way communication from IoT Central to Connected Field Service.</span></span> <span data-ttu-id="47ece-106">Lorsque IoT Central surveille les appareils à distance, toutes les mesures qui dépassent des seuils définis dans IoT Central vont déclencher une alerte dans CFS.</span><span class="sxs-lookup"><span data-stu-id="47ece-106">With IoT Central monitoring remote devices, any measurements that exceed thresholds defined in IoT Central will trigger an action to fire an alert in CFS.</span></span> <span data-ttu-id="47ece-107">Les responsables du service après-vente pourront regrouper ces alertes selon des critères comme l'actif du client et le type d'incident.</span><span class="sxs-lookup"><span data-stu-id="47ece-107">Field service managers can group these alerts by criteria such as customer asset and incident type.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="47ece-108">![](media/enhanced-iot-central-integration-1.png "Intégration IoT Central améliorée")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="47ece-108">![](media/enhanced-iot-central-integration-1.png "Enhanced IoT Central integration")
<!-- picture --></span></span>


<span data-ttu-id="47ece-109">Pour la version d'octobre 2018, les techniciens peuvent disposer et s'appuyer sur des appareils IoT sur site, avec quelques options selon l'état d'IoT Central.</span><span class="sxs-lookup"><span data-stu-id="47ece-109">For the October '18 release, technicians can be equipped with and act on insight from IoT devices when on site, with a few options depending on the state of IoT Central.</span></span>

-   <span data-ttu-id="47ece-110">Visuels sur l'état et les mesures de l'appareil IoT Central intégré directement au sein de l'application mobile Field Service.</span><span class="sxs-lookup"><span data-stu-id="47ece-110">Embed IoT Central device state and measurement visuals directly within the Field Service mobile application.</span></span>
-   <span data-ttu-id="47ece-111">Stockage des données de télémétrie à partir de l'IoT Central dans un blob Azure et activation d'un Power BI intégré pour visualiser les données.</span><span class="sxs-lookup"><span data-stu-id="47ece-111">Store telemetry data from IoT Central in an Azure blob and enable an embedded Power BI visualizing the data.</span></span>
-   <span data-ttu-id="47ece-112">Possibilité pour les techniciens de renvoyer des commandes à partir de l'application mobile Field Service à IoT Central.</span><span class="sxs-lookup"><span data-stu-id="47ece-112">Allow technicians to send commands from the Field Service mobile application back to IoT Central.</span></span>

