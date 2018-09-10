---
title: "Détecter, gérer et signaler les erreurs, et entrer des valeurs Null dans les bases de données avec des applications de canevas"
description: "Les créateurs d'application peuvent prendre le contrôle des erreurs lorsqu'elles se produisent et entrer des valeurs Null, ce qui est un autre avantage."
author: gregli-msft
manager: KVivek
ms.date: 9/3/2018
ms.assetid: 461c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: 5b2badd67a697d89e63973f5afe0977e402aead0
ms.openlocfilehash: 3c5fbf4a44a8de37d7b750f4c30a28967c62c10b
ms.contentlocale: fr-fr
ms.lasthandoff: 09/10/2018

---
# <a name="catch-handle-and-report-errors-and-write-null-values-to-databases-with-canvas-apps-public-preview"></a><span data-ttu-id="9dc92-103">Détecter, gérer et signaler les erreurs, et entrer des valeurs Null dans les bases de données avec des applications de canevas (version préliminaire publique)</span><span class="sxs-lookup"><span data-stu-id="9dc92-103">Catch, handle, and report errors, and write Null values to databases with canvas apps (Public Preview)</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="9dc92-104">Des erreurs se produisent.</span><span class="sxs-lookup"><span data-stu-id="9dc92-104">Errors happen.</span></span>  <span data-ttu-id="9dc92-105">Les applications de canevas adoptent un comportement par défaut dans ce cas, mais cela ne correspond pas toujours à ce qui est attendu.</span><span class="sxs-lookup"><span data-stu-id="9dc92-105">Canvas apps provide a default behavior when they do, but this may not always match what you want.</span></span>  <span data-ttu-id="9dc92-106">Avec cette fonctionnalité, vous pouvez intercepter, interroger, signaler, supprimer, consigner et envoyer des messages d'erreur aux utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="9dc92-106">With this feature, you can catch, interrogate, throw, suppress, log, and message errors to your users.</span></span>

<span data-ttu-id="9dc92-107">Il était auparavant impossible de faire la différence entre les erreurs et les valeurs Null, la transmission de valeurs Null aux bases de données posait donc problème.</span><span class="sxs-lookup"><span data-stu-id="9dc92-107">Errors and Null values were previously indistinguishable, so pushing Null values to databases was a problem.</span></span>  <span data-ttu-id="9dc92-108">La valeur Null est une valeur légitime dans de nombreux systèmes de base de données.</span><span class="sxs-lookup"><span data-stu-id="9dc92-108">Null is a legitimate value in many database systems.</span></span>  <span data-ttu-id="9dc92-109">Quand les erreurs sont correctement séparées dans des applications de canevas, vous pouvez entrer des valeurs Null dans toutes les bases de données.</span><span class="sxs-lookup"><span data-stu-id="9dc92-109">With errors properly separated out in canvas apps, you can write Null values to all databases.</span></span>

