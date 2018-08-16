---
title: Afficher les mesures en tant qu'URL interactives
description: "Utilisez des mesures pour définir un lien hypertexte permettant de naviguer depuis un état vers tout autre adresse web."
author: MI77
manager: kimani
ms.date: 6/22/18
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: willthom
audience: end user, developer, citizen developer, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: 3b3db487a5e105bae80656d20640059c915a8bf2
ms.contentlocale: fr-fr
ms.lasthandoff: 08/16/2018

---

# <a name="show-measures-as-clickable-urls"></a><span data-ttu-id="337dd-103">Afficher les mesures en tant qu'URL interactives</span><span class="sxs-lookup"><span data-stu-id="337dd-103">Show measures as clickable URLS</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]

<span data-ttu-id="337dd-104">Les utilisateurs finaux ont besoin d'un moyen simple de naviguer entre les états, ou entre les états et d'autres applications, tout en conservant toujours le contexte des données qu'ils consultaient.</span><span class="sxs-lookup"><span data-stu-id="337dd-104">End users need an easy way to navigate between reports, or from reports to other applications, while still retaining the context of the data they were looking at.</span></span> <span data-ttu-id="337dd-105">Les mesures peuvent générer des URL permettant la navigation, et peuvent être affichées en tant que liens hypertexte permettant de se déplacer facilement entre des états ou des applications.</span><span class="sxs-lookup"><span data-stu-id="337dd-105">Measures can generate URLs to allow navigation, and can be shown as hyperlinks that make it easy to move between reports or applications.</span></span>

<span data-ttu-id="337dd-106">Une mesure DAX peut retourner une URL, à laquelle des filtres sont ajoutés correspondant aux sélections de données effectuées dans l'état.</span><span class="sxs-lookup"><span data-stu-id="337dd-106">A DAX measure can return a URL, appended with filters corresponding to the data selections made in the report.</span></span> <span data-ttu-id="337dd-107">Cela peut être affiché dans des visuels de table et de matrice en tant que lien hypertexte, ajusté de manière dynamique selon les sélections effectuées.</span><span class="sxs-lookup"><span data-stu-id="337dd-107">This can be shown in table and matrix visuals as a hyperlink, dynamically adjusted based on the selections that are made.</span></span> <span data-ttu-id="337dd-108">Les utilisateurs finaux peuvent cliquer sur ce lien pour ouvrir un nouvel onglet avec l'état cible affiché.</span><span class="sxs-lookup"><span data-stu-id="337dd-108">End users can click this link to open a new tab with the target report shown.</span></span>

<span data-ttu-id="337dd-109">La mesure DAX peut être similaire à ceci :</span><span class="sxs-lookup"><span data-stu-id="337dd-109">The DAX measure might look something like this:</span></span>

`Link = “http://app.powerbi.com/Report/GUID/&filter=Table1/Category eq “ & SELECTEDVALUE(Products[Category])`

<!--
### Who uses this feature
This feature is intended for end users, developers, citizen developers, customizers, business analysts, and IT pros. No additional setup is required.
## Status
### Development status
In development
#### Target timeframe
October ‘18
-->

