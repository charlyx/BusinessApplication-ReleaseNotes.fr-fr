---
title: "Configurer des groupes d'options dépendants"
description: "Vous pouvez configurer des groupes d'options dépendants pour fournir des listes déroulantes en cascade dans vos applications et garantir la validation des données simples entre les listes déroulantes."
author: clwesene
manager: AnnBe
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: clwesene
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 22c0a725d5f46f6ec89fafeb05ea1b00fb183fc1
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
# <a name="configure-dependent-option-sets"></a><span data-ttu-id="4ad02-103">Configurer des groupes d'options dépendants</span><span class="sxs-lookup"><span data-stu-id="4ad02-103">Configure dependent option sets</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="4ad02-104">Lorsque vous créez des groupes d'options dépendants, vous pouvez facilement définir des règles entre les groupes pour vérifier l'exactitude des valeurs sélectionnées.</span><span class="sxs-lookup"><span data-stu-id="4ad02-104">By creating dependent option sets, you can easily set rules between option sets to make sure that selected values make sense.</span></span> <span data-ttu-id="4ad02-105">Par exemple, vous pouvez créer un groupe d'options **Pays/région** et un groupe d'options **États**.</span><span class="sxs-lookup"><span data-stu-id="4ad02-105">As an example, you can create a **Country/region** option set and a **States** option set.</span></span> <span data-ttu-id="4ad02-106">Si un utilisateur sélectionne **États-Unis** dans la liste déroulante du premier groupe d'options, la liste déroulante du deuxième groupe d'options doit afficher uniquement les états qui se trouvent dans ce pays.</span><span class="sxs-lookup"><span data-stu-id="4ad02-106">If a user selects **United States** in the drop-down list for the first option set, the drop-down list for the second option set should show only those states that are in that country/region.</span></span> <span data-ttu-id="4ad02-107">Pour vérifier que les données sont cohérentes et exactes, vous pouvez définir cette structure au niveau de l'entité pour toutes les applications.</span><span class="sxs-lookup"><span data-stu-id="4ad02-107">You can ensure that data is consistent and accurate by defining this structure at the entity level for consumption in all apps.</span></span>

