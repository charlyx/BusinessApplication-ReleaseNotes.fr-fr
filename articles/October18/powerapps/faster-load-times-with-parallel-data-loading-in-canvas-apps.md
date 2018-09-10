---
title: "Temps de chargement plus rapides avec le chargement des données en parallèle dans les applications de canevas"
description: "Les créateurs d'application peuvent exécuter plusieurs opérations de chargement de données simultanément, ce qui réduit le temps d'attente pour les utilisateurs d'application."
author: gregli-msft
manager: KVivek
ms.date: 9/3/2018
ms.assetid: 4b1c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: 5b2badd67a697d89e63973f5afe0977e402aead0
ms.openlocfilehash: bef6215012791ea25a52186010f46fbdd00cc4f1
ms.contentlocale: fr-fr
ms.lasthandoff: 09/10/2018

---
# <a name="faster-load-times-with-parallel-data-loading-in-canvas-apps"></a><span data-ttu-id="cfcde-103">Temps de chargement plus rapides avec le chargement des données en parallèle dans les applications de canevas</span><span class="sxs-lookup"><span data-stu-id="cfcde-103">Faster load times with parallel data loading in canvas apps</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="cfcde-104">Pour des performances optimisées, de nombreux créateurs d'application de canevas préchargeront plusieurs tables et plusieurs entités au démarrage de leur application.</span><span class="sxs-lookup"><span data-stu-id="cfcde-104">For better performance, many canvas-app makers will preload multiple tables and entities when their app starts.</span></span> <span data-ttu-id="cfcde-105">Aujourd'hui, cette opération s'effectue en séquence, un chargement après l'autre, souvent dans la formule **OnStart** de l'application.</span><span class="sxs-lookup"><span data-stu-id="cfcde-105">Today, this is done serially, one load after another, often in the **OnStart** formula of the app.</span></span> 

<span data-ttu-id="cfcde-106">Avec cette fonctionnalité, les créateurs d'application pourront charger plusieurs groupes de données en parallèle, ce qui réduira considérablement le temps d'attente des utilisateurs finaux.</span><span class="sxs-lookup"><span data-stu-id="cfcde-106">With this feature, app makers can load multiple data sets in parallel, dramatically reducing the end users' wait.</span></span>  <span data-ttu-id="cfcde-107">Cette fonctionnalité ne se limitera pas au démarrage ; les créateurs d'application pourront l'utiliser partout où des opérations parallèles amélioreraient les performances.</span><span class="sxs-lookup"><span data-stu-id="cfcde-107">And this facility isn't just limited to startup; makers can use it anywhere that parallel operations would improve performance.</span></span>

