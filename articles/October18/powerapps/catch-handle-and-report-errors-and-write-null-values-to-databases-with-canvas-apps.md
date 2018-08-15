---
title: "Détecter, gérer et signaler les erreurs, et entrer des valeurs Null dans les bases de données avec des applications de canevas"
description: "Les créateurs d'application peuvent prendre le contrôle des erreurs lorsqu'elles se produisent et entrer des valeurs Null, ce qui est un autre avantage."
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
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 6b7018a8f71dfbdc937430575e6c561b0d1a4e05
ms.contentlocale: fr-fr
ms.lasthandoff: 08/15/2018

---
# <a name="catch-handle-and-report-errors-and-write-null-values-to-databases-with-canvas-apps"></a><span data-ttu-id="2d5f2-103">Détecter, gérer et signaler les erreurs, et entrer des valeurs Null dans les bases de données avec des applications de canevas</span><span class="sxs-lookup"><span data-stu-id="2d5f2-103">Catch, handle, and report errors, and write Null values to databases with canvas apps</span></span>

[!include[powerapps banner](../includes/powerapps.md)]




<span data-ttu-id="2d5f2-104">Des erreurs se produisent.</span><span class="sxs-lookup"><span data-stu-id="2d5f2-104">Errors happen.</span></span>  <span data-ttu-id="2d5f2-105">Les applications de canevas adoptent un comportement par défaut dans ce cas, mais cela ne correspond pas toujours à ce qui est attendu.</span><span class="sxs-lookup"><span data-stu-id="2d5f2-105">Canvas apps provide a default behavior when they do, but this may not always match what you want.</span></span>  <span data-ttu-id="2d5f2-106">Avec cette fonctionnalité, vous pouvez intercepter, interroger, signaler, supprimer, consigner et envoyer des messages d'erreur aux utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="2d5f2-106">With this feature, you can catch, interrogate, throw, suppress, log, and message errors to your users.</span></span>

<span data-ttu-id="2d5f2-107">Il était auparavant impossible de faire la différence entre les erreurs et les valeurs Null, la transmission de valeurs Null aux bases de données posait donc problème.</span><span class="sxs-lookup"><span data-stu-id="2d5f2-107">Errors and Null values were previously indistinguishable, so pushing Null values to databases was a problem.</span></span>  <span data-ttu-id="2d5f2-108">La valeur Null est une valeur légitime dans de nombreux systèmes de base de données.</span><span class="sxs-lookup"><span data-stu-id="2d5f2-108">Null is a legitimate value in many database systems.</span></span>  <span data-ttu-id="2d5f2-109">Quand les erreurs sont correctement séparées dans des applications de canevas, vous pouvez entrer des valeurs Null dans toutes les bases de données.</span><span class="sxs-lookup"><span data-stu-id="2d5f2-109">With errors properly separated out in canvas apps, you can write Null values to all databases.</span></span>

