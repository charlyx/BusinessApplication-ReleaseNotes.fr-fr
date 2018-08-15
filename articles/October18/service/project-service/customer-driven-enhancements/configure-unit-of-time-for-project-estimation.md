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
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 3d9c093dc2928be990b3737ca3d94d61a485c9a9
ms.contentlocale: fr-fr
ms.lasthandoff: 08/15/2018

---
#  <a name="configure-a-unit-of-time-for-estimating-work-on-project-tasks"></a><span data-ttu-id="c62a3-103">Configurer une unité de temps pour estimer les efforts sur des tâches de projet</span><span class="sxs-lookup"><span data-stu-id="c62a3-103">Configure a unit of time for estimating work on project tasks</span></span>

[!include[project-service banner](../../../includes/project-service.md)]




<span data-ttu-id="c62a3-104">Project Service utilise l'*heure* comme seule unité de temps pour estimer les efforts sur des tâches de projet.</span><span class="sxs-lookup"><span data-stu-id="c62a3-104">Project Service uses *hour* as the only time unit for estimating work effort on a project task.</span></span> <span data-ttu-id="c62a3-105">Dans de nombreux pays, l'estimation est effectuée en « jours de travail ». Chaque pays définit le nombre d'heures dans une journée de travail typique.</span><span class="sxs-lookup"><span data-stu-id="c62a3-105">In many regions across the world, estimation is done in “work days,” with each country or region having its own definition of how many hours are in a typical work day.</span></span> <span data-ttu-id="c62a3-106">Par conséquent, selon la division qui est responsable de la livraison du projet, l'unité d'estimation du projet doit être définie par défaut sur le nombre d'heures d'une journée de travail de cette division.</span><span class="sxs-lookup"><span data-stu-id="c62a3-106">Therefore, depending on which division owns the delivery of the project, the unit of estimation on the project must default to that division's definition of work day.</span></span> 

<span data-ttu-id="c62a3-107">Avec cette fonctionnalité, chaque unité d'organisation peut identifier un calendrier de travail et spécifier une unité de référence pour évaluer les efforts.</span><span class="sxs-lookup"><span data-stu-id="c62a3-107">With this feature, each organizational unit will be able to identify a working calendar and specify a preferred unit for estimating effort.</span></span> <span data-ttu-id="c62a3-108">Tous les projets appartenant à l'unité d'organisation utilisent alors ce calendrier de travail et cette unité pour évaluer les efforts.</span><span class="sxs-lookup"><span data-stu-id="c62a3-108">All projects owned by that that organizational unit will then use that working calendar and that unit for estimating effort.</span></span> 

<span data-ttu-id="c62a3-109">Prenons un exemple : Si Contoso Écosse travaille 7,5 heures par jour et que son unité de référence pour évaluer les efforts est « une journée de travail écossaise », alors tous les projets appartenant à Contoso Écosse utiliseront une journée de travail écossaise comme unité d'estimation, et le multiplicateur de 7,5 servira à traduire cette estimation en heures.</span><span class="sxs-lookup"><span data-stu-id="c62a3-109">Consider an example: If Contoso Scotland works 7.5-hour days and its preferred unit for estimating effort is a “Scottish working day,” then all projects owned by Contoso Scotland will use Scottish working day as the unit of estimation, and the multiplier of 7.5 will be used to translate that estimate into hours.</span></span> 

## <a name="setting-up-time-unit-and-calendar-on-the-organizational-unit"></a><span data-ttu-id="c62a3-110">Configuration d'une unité de temps et d'un calendrier sur l'unité d'organisation</span><span class="sxs-lookup"><span data-stu-id="c62a3-110">Setting up time unit and calendar on the organizational unit</span></span>

<span data-ttu-id="c62a3-111">![Configuration d'une unité de temps et d'un calendrier sur l'unité d'organisation](media/Setting-time-unit-on-the-orgunit.png "Configuration d'une unité de temps et d'un calendrier sur l'unité d'organisation")</span><span class="sxs-lookup"><span data-stu-id="c62a3-111">![Setting up time unit and calendar on the Org. Unit](media/Setting-time-unit-on-the-orgunit.png "Setting up time unit and calendar on the organizational unit")</span></span>

## <a name="defaulting-time-unit-and-calendar-on-the-project-from-the-settings-on-the-organizational-unit"></a><span data-ttu-id="c62a3-112">Unité de temps et calendrier par défaut du projet à partir des paramètres de l'unité d'organisation</span><span class="sxs-lookup"><span data-stu-id="c62a3-112">Defaulting time unit and calendar on the project from the settings on the organizational unit</span></span>

<span data-ttu-id="c62a3-113">![Unité de temps et calendrier par défaut du projet](media/Defaulting-time-unit-calendar-on-the-project.png "Unité de temps et calendrier par défaut du projet")
<!-- Picture 2 --></span><span class="sxs-lookup"><span data-stu-id="c62a3-113">![Defaulting time unit and calendar on the project](media/Defaulting-time-unit-calendar-on-the-project.png "Defaulting time unit and calendar on the project")
<!-- Picture 2 --></span></span>

