---
title: Suppression de liens hypertexte
description: "Les développeurs peuvent supprimer des liens hypertexte de contrôle"
author: jasongre
manager: AnnBe
ms.date: 08/10/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: jasongre
audience: developer
ms.translationtype: HT
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: 76aaf7ff6926e396df13155a5df8bd2013d407c2
ms.contentlocale: fr-fr
ms.lasthandoff: 08/16/2018

---

# <a name="suppressing-hyperlinks"></a><span data-ttu-id="14031-103">Suppression de liens hypertexte</span><span class="sxs-lookup"><span data-stu-id="14031-103">Suppressing hyperlinks</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="14031-104">Les développeurs peuvent supprimer des liens hypertexte sur des contrôles de formulaire en attribuant à la propriété **EnableFormRef** la valeur **Non**.</span><span class="sxs-lookup"><span data-stu-id="14031-104">Developers are able to suppress hyperlinks on form controls by setting the **EnableFormRef** property to **No**.</span></span> <span data-ttu-id="14031-105">Cette propriété peut être définie à la fois sur les formulaires et sur les extensions de formulaire.</span><span class="sxs-lookup"><span data-stu-id="14031-105">This property can be set on both forms and form extensions.</span></span> <span data-ttu-id="14031-106">Lorsqu'un lien hypertexte est supprimé, l'option **Afficher les détails** correspondante dans le menu contextuel qui s'affiche est également supprimé.</span><span class="sxs-lookup"><span data-stu-id="14031-106">When a hyperlink is suppressed, the corresponding **View details** option in the right-click context menu is also suppressed.</span></span> 
 
<span data-ttu-id="14031-107">Actuellement, lorsque les utilisateurs cliquent sur certains liens hypertexte, cette action génère une tentative de navigation, puis un message d'erreur car aucun formulaire cible ne s'ouvre.</span><span class="sxs-lookup"><span data-stu-id="14031-107">Currently when users click on some hyperlinks, it results in an attempted navigation and then an error message, as there is no target form to open.</span></span> <span data-ttu-id="14031-108">La suppression des liens hypertexte dans ce type de scénario améliorera l'expérience utilisateur en supprimant ces liens hypertexte déroutants.</span><span class="sxs-lookup"><span data-stu-id="14031-108">Suppressing hyperlinks in these scenarios will improve the user experience by removing these confusing hyperlinks.</span></span>  

