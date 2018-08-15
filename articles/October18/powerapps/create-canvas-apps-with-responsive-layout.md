---
title: "Créer des applications de canevas avec une disposition dynamique"
description: "Les auteurs avancés peuvent créer des applications qui réagissent et s'adaptent dynamiquement à différents environnements."
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
ms.openlocfilehash: a8908855955edfae9b14c67feaf2d2fdfd7482a6
ms.contentlocale: fr-fr
ms.lasthandoff: 08/15/2018

---
# <a name="create-canvas-apps-with-responsive-layout"></a><span data-ttu-id="e832a-103">Créer des applications de canevas avec une disposition dynamique</span><span class="sxs-lookup"><span data-stu-id="e832a-103">Create canvas apps with responsive layout</span></span>

[!include[powerapps banner](../includes/powerapps.md)]




<span data-ttu-id="e832a-104">Normalement les écrans d'une application de canevas sont mis à l'échelle en fonction de l'espace fourni par l'hôte de l'application.</span><span class="sxs-lookup"><span data-stu-id="e832a-104">Normally the screens of a canvas app are scaled to fit the space provided by the app host.</span></span>  <span data-ttu-id="e832a-105">Cela facilite la création d'une application et garantit qu'elle s'affichera correctement sur n'importe quel écran où elle est utilisée.</span><span class="sxs-lookup"><span data-stu-id="e832a-105">This makes it easy to create an app and know that it will look proportionally correct on any screen in which it's used.</span></span>  <span data-ttu-id="e832a-106">Mais comme les écrans sont de plus en plus grands, les applications ne peuvent pas s'adapter pour profiter de l'espace supplémentaire.</span><span class="sxs-lookup"><span data-stu-id="e832a-106">But it comes at a price - as screens get bigger, the app can't adapt to take advantage of the additional real estate.</span></span>  <span data-ttu-id="e832a-107">De nombreux sites Web ont aujourd'hui un design « réactif » : ils s'ajustent à la taille de l'écran sur lequel ils sont affichés, et s'adaptent aux petits écrans de téléphone comme aux grandes écrans d'ordinateurs de bureau.</span><span class="sxs-lookup"><span data-stu-id="e832a-107">Many websites today are "responsive" - they adjust depending on the size of the screen they are shown on, adapting from small screens on phones to large screens on desktops.</span></span>  

<span data-ttu-id="e832a-108">Avec cette fonctionnalité, les créateurs d'application expérimentés peuvent créer des applications de canevas réactives.</span><span class="sxs-lookup"><span data-stu-id="e832a-108">With this feature, experienced app makers can create responsive canvas apps.</span></span>  <span data-ttu-id="e832a-109">Vous devez entrer des formules qui s'adaptent à la taille et à la position des contrôles selon la taille de l'écran au moment de l'exécution.</span><span class="sxs-lookup"><span data-stu-id="e832a-109">You must write formulas that adapt the size and position of controls based on the size of the screen at runtime.</span></span>  <span data-ttu-id="e832a-110">Vous pouvez désactiver le comportement de redimensionnement par défaut.</span><span class="sxs-lookup"><span data-stu-id="e832a-110">You can turn off the default scaling behavior.</span></span>  <span data-ttu-id="e832a-111">Les écrans affichent ainsi plus d'informations avec des tailles de police plus appropriées, et tout cela offre une meilleure expérience d'application.</span><span class="sxs-lookup"><span data-stu-id="e832a-111">As a result, screens show more information with more appropriate font sizes, all making for a better app experience.</span></span>

