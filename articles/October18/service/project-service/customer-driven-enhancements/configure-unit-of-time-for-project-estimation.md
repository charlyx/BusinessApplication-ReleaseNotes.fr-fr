---
title: "Configurer une unité de temps pour estimer les efforts sur des tâches de projet"
description: "Il est possible d'estimer les efforts sur des tâches de projet à l'aide d'une unité de temps configurable"
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
ms.openlocfilehash: 25e88afe31f492f72f29e3fde9ce38530ecc1291
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
#  <a name="configure-a-unit-of-time-for-estimating-work-on-project-tasks"></a>Configurer une unité de temps pour estimer les efforts sur des tâches de projet


[!include[banner](../../../../includes/banner.md)]

Project Service utilise l'*heure* comme seule unité de temps pour estimer les efforts sur des tâches de projet. Dans de nombreux pays, l'estimation est effectuée en « jours de travail ». Chaque pays définit le nombre d'heures dans une journée de travail typique. Par conséquent, selon la division qui est responsable de la livraison du projet, l'unité d'estimation du projet doit être définie par défaut sur le nombre d'heures d'une journée de travail de cette division. 

Avec cette fonctionnalité, chaque unité d'organisation peut identifier un calendrier de travail et spécifier une unité de référence pour évaluer les efforts. Tous les projets appartenant à l'unité d'organisation utilisent alors ce calendrier de travail et cette unité pour évaluer les efforts. 

Prenons un exemple : Si Contoso Écosse travaille 7,5 heures par jour et que son unité de référence pour évaluer les efforts est « une journée de travail écossaise », alors tous les projets appartenant à Contoso Écosse utiliseront une journée de travail écossaise comme unité d'estimation, et le multiplicateur de 7,5 servira à traduire cette estimation en heures. 

## <a name="setting-up-time-unit-and-calendar-on-the-organizational-unit"></a>Configuration d'une unité de temps et d'un calendrier sur l'unité d'organisation

![Configuration d'une unité de temps et d'un calendrier sur l'unité d'organisation](media/Setting-time-unit-on-the-orgunit.png "Configuration d'une unité de temps et d'un calendrier sur l'unité d'organisation")

## <a name="defaulting-time-unit-and-calendar-on-the-project-from-the-settings-on-the-organizational-unit"></a>Unité de temps et calendrier par défaut du projet à partir des paramètres de l'unité d'organisation

![Unité de temps et calendrier par défaut du projet](media/Defaulting-time-unit-calendar-on-the-project.png "Unité de temps et calendrier par défaut du projet")
<!-- Picture 2 -->

