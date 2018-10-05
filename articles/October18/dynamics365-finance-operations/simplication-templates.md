---
title: "Simplification via des modèles configurables"
description: "Simplification via des modèles configurables"
author: Annbe
manager: AnnBe
ms.date: 09/06/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: end-user
ms.translationtype: HT
ms.sourcegitcommit: b1a0f1e04786d2daef091fc6f6f9c168f2b005e7
ms.openlocfilehash: b6a9664c7dee1e53db19eaf6ea09f30073f255ea
ms.contentlocale: fr-fr
ms.lasthandoff: 09/25/2018

---
#  <a name="simplification-through-configurable-templates"></a><span data-ttu-id="f86df-103">Simplification via des modèles configurables</span><span class="sxs-lookup"><span data-stu-id="f86df-103">Simplification through configurable templates</span></span> 

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="f86df-104">Les clients peuvent de gagner du temps et de l'argent à l'aide de la facture client configurable et d'autres formats d'états externes.</span><span class="sxs-lookup"><span data-stu-id="f86df-104">Customers will save time and money by using configurable customer invoice and other external report formats.</span></span> <span data-ttu-id="f86df-105">Les formats fournissent des options d'impression des documents dans des formulaires pré-imprimés, ainsi que sur du papier standard.</span><span class="sxs-lookup"><span data-stu-id="f86df-105">The formats provide options to print documents to preprinted forms as well as plain paper.</span></span> <span data-ttu-id="f86df-106">Les modèles configurables permettront ainsi d'éliminer ou de limiter la modification des factures et des relevés client en code X++ ou dans SQL Server Reporting Services (SSRS).</span><span class="sxs-lookup"><span data-stu-id="f86df-106">Using the configurable templates will either eliminate or minimize the need to modify invoices and customer statements in X++ code or in SQL Server Reporting Services (SSRS).</span></span> <span data-ttu-id="f86df-107">Dans la version d'octobre 2018, le modèle configurable est disponible pour les facture financières uniquement.</span><span class="sxs-lookup"><span data-stu-id="f86df-107">In the October '18 release, the configurable template is available for free text invoices only.</span></span> <span data-ttu-id="f86df-108">Un modèle peut être créé à partir d'une facture financière existante, ou un modèle peut être créé et utilisé lors de la création de factures.</span><span class="sxs-lookup"><span data-stu-id="f86df-108">A template can be created from an existing free text invoice, or a new template can be created and used when creating new invoices.</span></span> <span data-ttu-id="f86df-109">Dans des mises à jour à venir, nous étendrons le nombre de modèles configurables aux factures client, états et autres documents externes.</span><span class="sxs-lookup"><span data-stu-id="f86df-109">In later updates we will extend the number of configurable templates for customer invoices, statements, and other external documents.</span></span>

> [!NOTE]
> <span data-ttu-id="f86df-110">Dans la version d'octobre 2018, l'exemple de configuration du modèle de facture en texte libre utilisé pour la consultation publique et le modèle de données sur lequel il est basé (modèle de facturation client) sont abandonnés et ne peuvent plus être utilisés.</span><span class="sxs-lookup"><span data-stu-id="f86df-110">In the October '18 release, the sample Free Text Invoice template configuration that was used for public review and the data model it is based on (Customer invoicing model) are discontinued and can no longer be used.</span></span>

<span data-ttu-id="f86df-111">![Exemple de facture en texte libre configurable](media/configurablefti.png "Exemple de facture en texte libre configurable")</span><span class="sxs-lookup"><span data-stu-id="f86df-111">![Configurable free text invoice example](media/configurablefti.png "Configurable free text invoice example")</span></span>

