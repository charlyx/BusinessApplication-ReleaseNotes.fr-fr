---
title: Prise en charge de l'authentification d'application Azure Active Directory
description: Prise en charge de l'authentification d'application Azure Active Directory
author: MargoC
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: cba1b690-0d07-4400-8bf6-80de880157ba
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 3c644df8af2bbc07c910cc7dd6581d55fc95686e
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
# <a name="azure-active-directory-application-authentication-public-preview"></a><span data-ttu-id="07ed2-103">Authentification d'application Azure Active Directory (version préliminaire publique)</span><span class="sxs-lookup"><span data-stu-id="07ed2-103">Azure Active Directory application authentication (Public Preview)</span></span>


[!include[banner](../../../includes/banner.md)]

<span data-ttu-id="07ed2-104">Nous ajoutons actuellement l'authentification d'application à Power BI Embedded.</span><span class="sxs-lookup"><span data-stu-id="07ed2-104">We are adding application authentication to Power BI Embedded.</span></span> <span data-ttu-id="07ed2-105">Cela permettra d'améliorer le déploiement, la sécurité et l'Application Lifecycle Management des applications Power BI Embedded.</span><span class="sxs-lookup"><span data-stu-id="07ed2-105">This will enhance the deployment, security, and application lifecycle management Power BI Embedded applications.</span></span> <span data-ttu-id="07ed2-106">Actuellement, la création d'une application Power BI Embedded requiert la création d'un compte d'utilisateur principal, le stockage des informations d'identification de ce compte, puis l'utilisation de celles-ci dans le code d'application pour effectuer une connexion non-interactive à Power BI.</span><span class="sxs-lookup"><span data-stu-id="07ed2-106">Currently, building a Power BI Embedded application requires the creation of a master user account, storing the credentials for that account, and then using them in the application code for performing non-interactive sign-in to Power BI.</span></span> <span data-ttu-id="07ed2-107">Azure Active Directory offre une prise en charge spéciale de l'authentification des applications avec leur propre identité sans contexte d'utilisateur.</span><span class="sxs-lookup"><span data-stu-id="07ed2-107">Azure Active Directory has special support for applications authenticating using their own identity without a user context.</span></span> <span data-ttu-id="07ed2-108">Cette prise en charge, conçue pour l'authentification réservée aux applications, offre un contrôle et une sécurité supérieurs, implique moins de limitations et constitue l'approche recommandée.</span><span class="sxs-lookup"><span data-stu-id="07ed2-108">This support, designed for app-only authentication, allows higher control and security, has fewer limitations, and is the recommended approach.</span></span> 

