---
title: "Soumission scellée"
description: "Soumission scellée"
author: ShylaThompson
manager: AnnBe
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: shylaw
audience: end-user
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 2405e676929ee3a49bce634b83c744f138fe401a
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---

# <a name="sealed-bidding"></a>Soumission scellée 

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



Les fonctionnalités d'appel d'offre seront améliorées pour prendre en charge la soumission scellée. Un fournisseur peut saisir et envoyer une offre avec des pièces jointes au format .pdf via un formulaire dédié sur l'interface de collaboration fournisseur. L'offre ne sera pas visible dans le contexte de l'appel d'offre auquel le personnel de l'approvisionnement a accès. L'offre est stockée chiffrée. Seul le contact enregistré comme contact du fournisseur et disposant des autorisations de rôle requises peut accéder à l'offre avant qu'elle soit descellée. Le personnel de l'approvisionnement peut desceller les offres après la date d'expiration, et ensuite peut afficher l'offre du fournisseur dans le contexte de l'appel d'offre. Toute action de lecture ou d'écriture de l'utilisateur dans l'offre avant la date d'expiration sera enregistrée à des fins d'audit et ces informations seront à la disposition du fournisseur, ainsi que du personnel de l'approvisionnement une fois l'offre descellée.  

