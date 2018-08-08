---
title: "Prise en charge native des types de données Common Data Service dans les applications de canevas"
description: "Les créateurs d'application peuvent facilement utiliser les données de type groupes d'options, GUID, Date uniquement et Date uniquement sans fuseau horaire"
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
ms.openlocfilehash: 94039419a4491ff73e7b9b09418e964242036b59
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
# <a name="native-support-for-common-data-service-data-types-in-canvas-apps"></a>Prise en charge native des types de données Common Data Service dans les applications de canevas


[!include[banner](../../includes/banner.md)]

À l'heure actuelle, la prise en charge de certains types de données Common Data Service est limité ou difficile à d'utilisation. Les valeurs de groupe d'options doivent être recherchées manuellement sur le portail du créateur, les GUID sont gérés via des chaînes pouvant entraîner des problèmes dans les comparaisons, et les champs Date uniquement et Date/heure présentent des problèmes de fuseau horaire.

Cette fonctionnalité résout tous ces problèmes en ajoutant une prise en charge native pour les groupes d'options et les GUID et en améliorant la gestion des fuseaux horaires pour les valeurs de date/heure.

