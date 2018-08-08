---
title: "Prise en charge de plusieurs unités de temps sur un tarif unique"
description: "Les tarifs vous permettent de spécifier des prix pour plusieurs unités de temps"
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
ms.openlocfilehash: d2aca752e4381437a0f7f984e963cfc188f1e9d3
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
#   <a name="support-for-multiple-time-units-on-a-single-price-list"></a>Prise en charge de plusieurs unités de temps sur un tarif unique


[!include[banner](../../../../includes/banner.md)]

Project Service prend en charge la tarification de la durée d'une ressource. Les utilisateurs peuvent choisir de configurer des prix à l'heure, à la journée ou toute autre unité de temps. Toutefois, l'unité du temps est décidée dans l'en-tête des tarifs et ne peuvent pas être modifiée sur les lignes de paramétrage de prix individuelles de la durée de la ressource. 

Avec cette mise à jour, chaque tarif vous permet de spécifier des prix pour plusieurs unités de temps. Ceci est particulièrement utile pour les entreprises qui opèrent dans différentes régions géographiques avec des codes et pratiques de travail distincts. 

Par exemple : Lorsque vous définissez un taux pour un « jour ouvrable », chaque division d'une société de service de projet multinationale peut avoir sa propre définition d'un jour ouvrable. Sa division en Inde peut ouvrir 8 heures par jours, tandis que sa division en Écosse peut ouvrir 7,5 heures par jour. Avec cette fonctionnalité, les sociétés peuvent paramétrer les prix journaliers à l'aide de l'unité de jour spécifique à chaque division.

![Taux de coûts pour plusieurs unités de temps sur les tarifs](media/multiple-time-unit-on-pricelist.png "Taux de coûts pour plusieurs unités de temps sur les tarifs")
<!-- Picture 2 -->

