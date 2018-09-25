---
title: Double monnaie
description: Double monnaie
author: Annbe
manager: AnnBe
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: end-user
ms.translationtype: HT
ms.sourcegitcommit: b1a0f1e04786d2daef091fc6f6f9c168f2b005e7
ms.openlocfilehash: 348510b1dddd8228b6dd579a79fbeee5d65bf16c
ms.contentlocale: fr-fr
ms.lasthandoff: 09/25/2018

---
#  <a name="dual-currency"></a><span data-ttu-id="b7e71-103">Double monnaie</span><span class="sxs-lookup"><span data-stu-id="b7e71-103">Dual currency</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



<span data-ttu-id="b7e71-104">La devise de déclaration sera réaffectée dans une deuxième devise comptable.</span><span class="sxs-lookup"><span data-stu-id="b7e71-104">The reporting currency will be repurposed into a true second accounting currency.</span></span> <span data-ttu-id="b7e71-105">D'un point de vue comptable, la devise de déclaration continuera à être calculée pour chaque transaction validée dans un compte général.</span><span class="sxs-lookup"><span data-stu-id="b7e71-105">From a general ledger perspective, the reporting currency will continue to be calculated for every transaction posted to a general ledger.</span></span>  <span data-ttu-id="b7e71-106">Certains processus de comptabilité seront améliorés, et un nouveau journal sera ajouté pour valider des transactions dans la devise de déclaration uniquement.</span><span class="sxs-lookup"><span data-stu-id="b7e71-106">Some general ledger processes will be enhanced, and a new journal will be added to post transactions in only the reporting currency.</span></span> <span data-ttu-id="b7e71-107">Pour d'autres comptes de sous-comptabilité, comme les immobilisations, il y aura des modifications plus importantes.</span><span class="sxs-lookup"><span data-stu-id="b7e71-107">For various subledgers, such as fixed assets, there will be larger changes.</span></span> <span data-ttu-id="b7e71-108">Pour les immobilisations, nous allons au départ conserver toutes les transactions dans la sous-comptabilité pour la devise de déclaration.</span><span class="sxs-lookup"><span data-stu-id="b7e71-108">For fixed assets, we will start to maintain all transactions in the subledger for the reporting currency.</span></span> <span data-ttu-id="b7e71-109">Lors de l'amortissement, les montants seront amortis dans la devise de déclaration à l'aide des méthodes d'amortissement, exactement comme avec la devise comptable.</span><span class="sxs-lookup"><span data-stu-id="b7e71-109">When running depreciation, it will depreciate the reporting currency amounts using the depreciation methods, just as it does the accounting currency.</span></span> <span data-ttu-id="b7e71-110">Parmi les autres modules de sous-comptabilité affectés on trouve Comptabilité fournisseur, Comptabilité client et Banques</span><span class="sxs-lookup"><span data-stu-id="b7e71-110">Other subledger modules impacted will be Accounts payable, Accounts receivable, and Cash management.</span></span>

