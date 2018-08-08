---
title: Authentification unique pour Azure SQL Database
description: Authentification unique pour Azure SQL Database
author: MargoC
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: defe56c9-38a5-48c6-ba86-e1c6371bfb75
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 4e774f63cd021959f0fe95f44598a2d937ada967
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
#  <a name="power-bi-embedded-single-sign-on-for-azure-sql-database"></a><span data-ttu-id="a865c-103">Authentification unique Power BI Embedded pour Azure SQL Database</span><span class="sxs-lookup"><span data-stu-id="a865c-103">Power BI Embedded single sign-on for Azure SQL Database</span></span>


[!include[banner](../../../includes/banner.md)]

<span data-ttu-id="a865c-104">Cela permet à Power BI Embedded de respecter les paramètres de sécurité configurés au niveau de la source de données.</span><span class="sxs-lookup"><span data-stu-id="a865c-104">This enables Power BI Embedded to respect security settings that are configured at the data source level.</span></span> <span data-ttu-id="a865c-105">Power BI Embedded n'a aucune connaissance de l'utilisateur de l'application.</span><span class="sxs-lookup"><span data-stu-id="a865c-105">Power BI Embedded has no awareness of the application’s user.</span></span> <span data-ttu-id="a865c-106">Pour les applications souhaitant définir une sécurité au niveau de la ligne dans Azure SQL Database, il est nécessaire de transférer les informations d'utilisateur de l'application à SQL Database.</span><span class="sxs-lookup"><span data-stu-id="a865c-106">For applications that want to set row-level security in Azure SQL Database, there is a need to pass the application’s user information to SQL Database.</span></span> <span data-ttu-id="a865c-107">En activant l'option d'authentification unique, Power BI Embedded envoie les informations d'identification Azure Active Directory authentifiées pour les utilisateurs accédant à des rapports dans les requêtes à Azure SQL Database.</span><span class="sxs-lookup"><span data-stu-id="a865c-107">By enabling the single sign-on option, Power BI Embedded sends authenticated Azure Active Directory credentials for users accessing reports in the queries to the Azure SQL Database.</span></span> 

