---
title: Validation de la prise d'effet de date sur les tarifs
description: "Grâce à la validation, les utilisateurs de Project Service évitent les erreurs dans la définition des prix par défaut. Ces erreurs pourraient être dues à plusieurs tarifs effectifs à une certaine date."
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
ms.openlocfilehash: ebe319f383c161cea41fe8d483206b72f9244de7
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
#   <a name="date-effectivity-validation-on-price-lists"></a>Validation de la prise d'effet de date sur les tarifs


[!include[banner](../../../../includes/banner.md)]


Grâce à cette fonctionnalité, les utilisateurs de Project Service évitent les erreurs dans la définition des prix par défaut. Ces erreurs pourraient être dues à plusieurs tarifs effectifs à une certaine date. Les clients de Project Service savent que ce produit permet d'associer plusieurs tarifs de projet à des devis, des contrats de projet, et à des unités d'organisation. Cela permet en effet de compenser les modifications de tarifs liées à l'inflation et représentées par des tarifs avec différentes dates effectives. 

Avec cette fonctionnalité, le système valide la configuration des tarifs pour garantir qu'aucune date effective ne se chevauche à un moment donné (un projet ou un contact, par exemple). De plus, le système garantit d'évaluer correctement le travail lorsqu'une estimation sur un devis ou un contrat couvre plusieurs périodes tarifaires. 

