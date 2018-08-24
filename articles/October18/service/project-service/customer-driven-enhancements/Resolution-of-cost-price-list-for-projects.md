---
title: "Résolution de la liste des prix de revient en multidevise sur des projets"
description: "Résolution de la liste des prix de revient en multidevise sur des projets"
author: rumant
manager: shellyhaverkamp
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: rumant
audience: developer, admin, end user, citizen developer, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: dc40b9862dcb8c4e8eeb12168ab8497bc131c000
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
#  <a name="resolution-of-multi-currency-cost-price-list-on-projects"></a>Résolution de la liste des prix de revient en multidevise sur des projets 

[!include[project-service banner](../../../includes/project-service.md)]




Project Service résout les tarifs pour les taux de coût des projets en mettant en correspondance la devise de l'unité d'organisation propriétaire du projet avec la devise des tarifs. Dans le cas où des tarifs peuvent comporter des prix dans plusieurs devises, il doit y avoir des tarifs principaux avec des lignes de taux de coût dans plusieurs devises, et ces tarifs doivent être utilisés par tous les projets de façon globale. 

Dans ce cas, résoudre une liste des prix de revient pour un projet à l'aide de la devise dans l'en-tête des tarifs ne fonctionne pas. Avec cette fonctionnalité, il est possible de configurer la résolution par défaut de la liste des prix de revient du projet. Les options disponibles consistent à mettre en correspondance la devise de coût du projet avec l'en-tête des tarifs tel que cela fonctionne actuellement ou d'utiliser les tarifs gérés globalement quelle que soit la devise dans son en-tête.  



