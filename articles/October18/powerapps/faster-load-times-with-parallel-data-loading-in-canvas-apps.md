---
title: "Temps de chargement plus rapides avec le chargement des données en parallèle dans les applications de canevas"
description: "Les créateurs d'application peuvent exécuter plusieurs opérations de chargement de données simultanément, ce qui réduit le temps d'attente pour les utilisateurs d'application."
author: gregli
manager: AnnBe
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 587d76f50fead1766f5dc810e2f9b0bf34bd760a
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
# <a name="faster-load-times-with-parallel-data-loading-in-canvas-apps"></a><span data-ttu-id="cfcde-103">Temps de chargement plus rapides avec le chargement des données en parallèle dans les applications de canevas</span><span class="sxs-lookup"><span data-stu-id="cfcde-103">Faster load times with parallel data loading in canvas apps</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="cfcde-104">Pour des performances optimisées, de nombreux créateurs d'application de canevas préchargeront plusieurs tables et plusieurs entités au démarrage de leur application.</span><span class="sxs-lookup"><span data-stu-id="cfcde-104">For better performance, many canvas-app makers will preload multiple tables and entities when their app starts.</span></span> <span data-ttu-id="cfcde-105">Aujourd'hui, cette opération s'effectue en séquence, un chargement après l'autre, souvent dans la formule **OnStart** de l'application.</span><span class="sxs-lookup"><span data-stu-id="cfcde-105">Today, this is done serially, one load after another, often in the **OnStart** formula of the app.</span></span> 

<span data-ttu-id="cfcde-106">Avec cette fonctionnalité, les créateurs d'application pourront charger plusieurs groupes de données en parallèle, ce qui réduira considérablement le temps d'attente des utilisateurs finaux.</span><span class="sxs-lookup"><span data-stu-id="cfcde-106">With this feature, app makers can load multiple data sets in parallel, dramatically reducing the end users' wait.</span></span>  <span data-ttu-id="cfcde-107">Cette fonctionnalité ne se limitera pas au démarrage ; les créateurs d'application pourront l'utiliser partout où des opérations parallèles amélioreraient les performances.</span><span class="sxs-lookup"><span data-stu-id="cfcde-107">And this facility isn't just limited to startup; makers can use it anywhere that parallel operations would improve performance.</span></span>

