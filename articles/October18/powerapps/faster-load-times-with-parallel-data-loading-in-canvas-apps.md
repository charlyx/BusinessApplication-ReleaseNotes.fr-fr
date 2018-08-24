---
title: "Temps de chargement plus rapides avec le chargement des données en parallèle dans les applications de canevas"
description: "Les créateurs d'application peuvent exécuter plusieurs opérations de chargement de données simultanément, ce qui réduit le temps d'attente pour les utilisateurs d'application."
author: gregli-msft
manager: AnnBe
ms.date: 8/10/2018
ms.assetid: 4b1c1f60-ce73-e811-a96b-000d3a18c83b
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
# <a name="faster-load-times-with-parallel-data-loading-in-canvas-apps"></a>Temps de chargement plus rapides avec le chargement des données en parallèle dans les applications de canevas


[!include[banner](../../includes/banner.md)]

Pour des performances optimisées, de nombreux créateurs d'application de canevas préchargeront plusieurs tables et plusieurs entités au démarrage de leur application. Aujourd'hui, cette opération s'effectue en séquence, un chargement après l'autre, souvent dans la formule **OnStart** de l'application. 

Avec cette fonctionnalité, les créateurs d'application pourront charger plusieurs groupes de données en parallèle, ce qui réduira considérablement le temps d'attente des utilisateurs finaux.  Cette fonctionnalité ne se limitera pas au démarrage ; les créateurs d'application pourront l'utiliser partout où des opérations parallèles amélioreraient les performances.

