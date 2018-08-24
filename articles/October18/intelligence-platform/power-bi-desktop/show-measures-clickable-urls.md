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
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 0ae8e309078c1aea0a4b24abe8eb4b253db34b29
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---

# <a name="show-measures-as-clickable-urls"></a>Afficher les mesures en tant qu'URL interactives

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]

Les utilisateurs finaux ont besoin d'un moyen simple de naviguer entre les états, ou entre les états et d'autres applications, tout en conservant toujours le contexte des données qu'ils consultaient. Les mesures peuvent générer des URL permettant la navigation, et peuvent être affichées en tant que liens hypertexte permettant de se déplacer facilement entre des états ou des applications.

Une mesure DAX peut retourner une URL, à laquelle des filtres sont ajoutés correspondant aux sélections de données effectuées dans l'état. Cela peut être affiché dans des visuels de table et de matrice en tant que lien hypertexte, ajusté de manière dynamique selon les sélections effectuées. Les utilisateurs finaux peuvent cliquer sur ce lien pour ouvrir un nouvel onglet avec l'état cible affiché.

La mesure DAX peut être similaire à ceci :

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

