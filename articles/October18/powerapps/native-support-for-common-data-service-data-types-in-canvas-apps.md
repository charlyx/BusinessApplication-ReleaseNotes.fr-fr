---
title: "Prise en charge native des types de données Common Data Service dans les applications de canevas"
description: "Les créateurs d'application peuvent facilement utiliser les données de type groupes d'options, GUID, Date uniquement et Date uniquement sans fuseau horaire"
author: gregli-msft
manager: AnnBe
ms.date: 8/10/2018
ms.assetid: 3f1c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: b6df0f68e3460358864533346e69a712684da551
ms.openlocfilehash: 4ded25075d383975848319ea163e44c7d69a1112
ms.contentlocale: fr-fr
ms.lasthandoff: 08/16/2018

---
# <a name="native-support-for-common-data-service-data-types-in-canvas-apps"></a><span data-ttu-id="e3e4b-103">Prise en charge native des types de données Common Data Service dans les applications de canevas</span><span class="sxs-lookup"><span data-stu-id="e3e4b-103">Native support for Common Data Service data types in canvas apps</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="e3e4b-104">À l'heure actuelle, la prise en charge de certains types de données Common Data Service est limité ou difficile à d'utilisation.</span><span class="sxs-lookup"><span data-stu-id="e3e4b-104">Today, support for some Common Data Service data types is limited or hard to use.</span></span> <span data-ttu-id="e3e4b-105">Les valeurs de groupe d'options doivent être recherchées manuellement sur le portail du créateur, les GUID sont gérés via des chaînes pouvant entraîner des problèmes dans les comparaisons, et les champs Date uniquement et Date/heure présentent des problèmes de fuseau horaire.</span><span class="sxs-lookup"><span data-stu-id="e3e4b-105">Optionset values must be looked up manually on the maker portal, GUIDs are handled through strings that can cause problems in comparisons, and there are time zone issues with date only and date/time fields.</span></span>

<span data-ttu-id="e3e4b-106">Cette fonctionnalité résout tous ces problèmes en ajoutant une prise en charge native pour les groupes d'options et les GUID et en améliorant la gestion des fuseaux horaires pour les valeurs de date/heure.</span><span class="sxs-lookup"><span data-stu-id="e3e4b-106">This feature cleans all that up, adding native support for optionsets and GUIDs and improving the time zone handling for date/time values.</span></span>

