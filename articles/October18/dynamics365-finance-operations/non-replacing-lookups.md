---
title: "Comportement amélioré des recherches non remplaçantes"
description: "Un certain nombre d'améliorations fonctionnelles ont été apportées aux recherches non remplaçantes dans Finance and Operations."
author: jasongre
manager: AnnBe
ms.date: 08/10/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: jasongre
audience: developer, admin, end user, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 61b9767518eecaff1d4afc473490a79c2fb595cb
ms.openlocfilehash: b51868e60abd7dc8a219697a668953ad7a7cd447
ms.contentlocale: fr-fr
ms.lasthandoff: 10/02/2018

---

# <a name="improved-behavior-of-non-replacing-lookups"></a><span data-ttu-id="728b6-103">Comportement amélioré des recherches non remplaçantes</span><span class="sxs-lookup"><span data-stu-id="728b6-103">Improved behavior of non-replacing lookups</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="728b6-104">Certaines recherches dans Finance and Operations sont *non remplaçantes* : cela signifie que lorsqu'une valeur est sélectionnée dans la recherche, cette valeur ne remplace pas la ou les valeurs déjà présentes dans le champ mais elle est ajoutée dans le champ.</span><span class="sxs-lookup"><span data-stu-id="728b6-104">Some lookups in Finance and Operations are *non-replacing*, meaning that when a value is selected from the lookup, it doesn’t replace what was already in the field, but instead it appends the selected value into the field.</span></span> <span data-ttu-id="728b6-105">Par exemple, les recherches de la boîte de dialogue **Tri/filtre avancé** sont non remplaçantes par défaut.</span><span class="sxs-lookup"><span data-stu-id="728b6-105">As an example, the lookups in the **Advanced filter/sort** dialog are non-replacing by default.</span></span>  

<span data-ttu-id="728b6-106">Le comportement des recherches non remplaçantes a été amélioré des manières suivantes :</span><span class="sxs-lookup"><span data-stu-id="728b6-106">The behavior of non-replacing lookups has been improved in the following ways:</span></span> 

- <span data-ttu-id="728b6-107">Le comportement de la saisie semi-automatique a été désactivée pour les recherches non remplaçantes.</span><span class="sxs-lookup"><span data-stu-id="728b6-107">Type-ahead behavior has been turned off for non-replacing lookups.</span></span> 

- <span data-ttu-id="728b6-108">Seuls les caractères saisis une fois la recherche ouverte sont utilisés dans la grille de recherche.</span><span class="sxs-lookup"><span data-stu-id="728b6-108">Only characters typed after the lookup has been opened are used to position in the lookup grid.</span></span>

- <span data-ttu-id="728b6-109">La valeur sélectionnée dans la recherche est ajoutée à ce qui se trouvait dans le champ avant l'ouverture de la recherche (autrement dit, tous les caractères saisis lorsque la recherche était ouverte sont remplacés lors de l'ajout de la valeur sélectionnée dans la recherche).</span><span class="sxs-lookup"><span data-stu-id="728b6-109">The selected value from the lookup is appended to what was in the field before the lookup was opened (that is, any characters typed while the lookup was open are replaced when appending the selected value from the lookup).</span></span>  

- <span data-ttu-id="728b6-110">Une nouvelle icône s'affiche désormais sur les recherches non remplaçantes afin qu'elles se différencient visuellement des recherches classiques.</span><span class="sxs-lookup"><span data-stu-id="728b6-110">A new icon now appears on non-replacing lookups to visually differentiate them from regular lookups.</span></span>

<span data-ttu-id="728b6-111">Ces ajustements permettent aux utilisateurs de filtrer plus facilement les données à l'aide de la boîte de dialogue **Tri/filtre avancé**.</span><span class="sxs-lookup"><span data-stu-id="728b6-111">These adjustments make it easier for users to filter data using the **Advanced filter/sort** dialog.</span></span>

