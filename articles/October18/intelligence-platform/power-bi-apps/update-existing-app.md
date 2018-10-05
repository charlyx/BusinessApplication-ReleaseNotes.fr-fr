---
title: "Mettre à jour une application Power BI existante dans AppSource"
description: "Mettre à jour une application Power BI existante dans AppSource"
author: ezaviv
manager: HaydnR
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: avive
audience: Admin, end user
ms.translationtype: HT
ms.sourcegitcommit: 2ddd4b42d13f15731ed8fd2f46f3376477b2eb3c
ms.openlocfilehash: 471d412ae40cbef021decc560fbc329cfd3fe5d8
ms.contentlocale: fr-fr
ms.lasthandoff: 09/11/2018

---
# <a name="update-an-existing-power-bi-app-in-appsource-public-preview"></a><span data-ttu-id="ea174-103">Mettre à jour une application Power BI existante dans AppSource (Version préliminaire publique)</span><span class="sxs-lookup"><span data-stu-id="ea174-103">Update an existing Power BI app in AppSource (Public Preview)</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



<span data-ttu-id="ea174-104">Application Lifecycle Management (ALM) comporte les fonctionnalités suivantes :</span><span class="sxs-lookup"><span data-stu-id="ea174-104">The application lifecycle management (ALM) story includes the following capabilities:</span></span>

- <span data-ttu-id="ea174-105">Une application est basée sur un espace de travail Power BI avec des paramètres supplémentaires.</span><span class="sxs-lookup"><span data-stu-id="ea174-105">An app is based on a Power BI workspace with additional settings (parameters).</span></span>
- <span data-ttu-id="ea174-106">Il existe trois niveaux de version pour une application : espace de travail (travaux en cours) --> package (version finale) --> application publiée (contenu disponible publiquement pour l'installation via AppSource).</span><span class="sxs-lookup"><span data-stu-id="ea174-106">There are three release levels for an app: workspace (WIP) --> package (release candidate) --> published app (content that is publicly available to install through AppSource).</span></span>
- <span data-ttu-id="ea174-107">À chaque niveau de lancement, nous conservons une version unique : un espace de travail dans les travaux en cours, un package et une application publiée.</span><span class="sxs-lookup"><span data-stu-id="ea174-107">On each release level we keep a single version: one workspace in WIP, one package, one published app.</span></span> <span data-ttu-id="ea174-108">Pour effectuer une mise à jour vers une application publiée, il vous suffit de déployer un package.</span><span class="sxs-lookup"><span data-stu-id="ea174-108">To make an update to a published app, you deploy a package.</span></span> <span data-ttu-id="ea174-109">Le déploiement d'un package remplace l'application publiée dans AppSource.</span><span class="sxs-lookup"><span data-stu-id="ea174-109">Deploying a package will overwrite the published app in AppSource.</span></span>
- <span data-ttu-id="ea174-110">La conception de l'application peut continuer à tout moment sur l'espace de travail des travaux en cours.</span><span class="sxs-lookup"><span data-stu-id="ea174-110">Building the app can continue at all times on the WIP workspace.</span></span>
- <span data-ttu-id="ea174-111">Lorsque vous êtes prêt à créer une version finale, enregistrez le package.</span><span class="sxs-lookup"><span data-stu-id="ea174-111">Whenever you are ready to create a release candidate, save the package.</span></span>

