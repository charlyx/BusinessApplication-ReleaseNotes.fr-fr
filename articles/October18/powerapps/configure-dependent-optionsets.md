---
title: "Configurer des groupes d'options dépendants"
description: "Vous pouvez configurer des groupes d'options dépendants pour fournir des listes déroulantes en cascade dans vos applications et permettre une validation simple des données entre les listes déroulantes."
author: clwesene
manager: KVivek
ms.date: 9/3/2018
ms.assetid: 641c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: clwesene
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: 5b2badd67a697d89e63973f5afe0977e402aead0
ms.openlocfilehash: 47474939488d1eb295a7da01faa359c0f5859a37
ms.contentlocale: fr-fr
ms.lasthandoff: 09/10/2018

---
# <a name="configure-dependent-option-sets-public-preview"></a><span data-ttu-id="21a66-103">Configurer des groupes d'options dépendants (version préliminaire publique)</span><span class="sxs-lookup"><span data-stu-id="21a66-103">Configure dependent option sets (Public Preview)</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="21a66-104">Lorsque vous créez des groupes d'options dépendants, vous pouvez facilement définir des règles entre les groupes pour vérifier l'exactitude des valeurs sélectionnées.</span><span class="sxs-lookup"><span data-stu-id="21a66-104">By creating dependent option sets, you can easily set rules between option sets to make sure that selected values make sense.</span></span> <span data-ttu-id="21a66-105">Par exemple, vous pouvez créer un groupe d'options **Pays/région** et un groupe d'options **États**.</span><span class="sxs-lookup"><span data-stu-id="21a66-105">As an example, you can create a **Country/region** option set and a **States** option set.</span></span> <span data-ttu-id="21a66-106">Si un utilisateur sélectionne **États-Unis** dans la liste déroulante du premier groupe d'options, la liste déroulante du deuxième groupe d'options doit afficher uniquement les états qui se trouvent dans ce pays.</span><span class="sxs-lookup"><span data-stu-id="21a66-106">If a user selects **United States** in the drop-down list for the first option set, the drop-down list for the second option set should show only those states that are in that country/region.</span></span> <span data-ttu-id="21a66-107">Pour vérifier que les données sont cohérentes et exactes, vous pouvez définir cette structure au niveau de l'entité pour toutes les applications.</span><span class="sxs-lookup"><span data-stu-id="21a66-107">You can ensure that data is consistent and accurate by defining this structure at the entity level for consumption in all apps.</span></span>

