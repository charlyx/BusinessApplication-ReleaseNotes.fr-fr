---
title: Activer une application pour utiliser les slicers par programme
description: "L'API des slicers permet à une application (tout au long d'une session) de contrôler les slicers avec lesquels l'utilisateur interagit."
author: Annbe
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 21ca0fd2-7676-4c50-af47-f6b7cbc7fe8a
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: b1a0f1e04786d2daef091fc6f6f9c168f2b005e7
ms.openlocfilehash: f1a07b0c712e65870086749c584cfe5c97d12dbc
ms.contentlocale: fr-fr
ms.lasthandoff: 09/25/2018

---
#  <a name="enable-an-application-to-programmatically-use-slicers"></a><span data-ttu-id="4aee3-103">Activer une application pour utiliser les slicers par programme</span><span class="sxs-lookup"><span data-stu-id="4aee3-103">Enable an application to programmatically use slicers</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



<span data-ttu-id="4aee3-104">L'API des slicers permet à une application (tout au long d'une session) de contrôler les slicers avec lesquels l'utilisateur interagit.</span><span class="sxs-lookup"><span data-stu-id="4aee3-104">The slicers API will give the application control, throughout the session, of the slicers the user interacts with.</span></span> <span data-ttu-id="4aee3-105">Cette API est semblable à l'API des filtres, elle est donc simple et intuitive pour le développeur.</span><span class="sxs-lookup"><span data-stu-id="4aee3-105">The API will be like the filters API so that it will be easy and intuitive for the developer.</span></span> <span data-ttu-id="4aee3-106">Les fonctionnalités prises en charge sont les suivantes :</span><span class="sxs-lookup"><span data-stu-id="4aee3-106">The supported capabilities are:</span></span>

-   <span data-ttu-id="4aee3-107">Obtenir la valeur des slicers</span><span class="sxs-lookup"><span data-stu-id="4aee3-107">Get slicers value</span></span>
-   <span data-ttu-id="4aee3-108">Définir la valeur des slicers lors du chargement</span><span class="sxs-lookup"><span data-stu-id="4aee3-108">Set slicers value on load</span></span>
-   <span data-ttu-id="4aee3-109">Définir la valeur des slicers pendant la session</span><span class="sxs-lookup"><span data-stu-id="4aee3-109">Set slicers value during the session</span></span>
-   <span data-ttu-id="4aee3-110">Obtenir la valeur du slicer appliqué par l'utilisateur</span><span class="sxs-lookup"><span data-stu-id="4aee3-110">Get the value of the user’s applied slicer</span></span>

