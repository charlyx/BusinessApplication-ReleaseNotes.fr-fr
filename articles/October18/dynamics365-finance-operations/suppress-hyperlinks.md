---
title: Suppression de liens hypertexte
description: "Les développeurs peuvent supprimer des liens hypertexte de contrôle"
author: jasongre
manager: AnnBe
ms.date: 08/10/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: jasongre
audience: developer
ms.translationtype: HT
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: 76aaf7ff6926e396df13155a5df8bd2013d407c2
ms.contentlocale: fr-fr
ms.lasthandoff: 08/16/2018

---

# <a name="suppressing-hyperlinks"></a>Suppression de liens hypertexte

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

Les développeurs peuvent supprimer des liens hypertexte sur des contrôles de formulaire en attribuant à la propriété **EnableFormRef** la valeur **Non**. Cette propriété peut être définie à la fois sur les formulaires et sur les extensions de formulaire. Lorsqu'un lien hypertexte est supprimé, l'option **Afficher les détails** correspondante dans le menu contextuel qui s'affiche est également supprimé. 
 
Actuellement, lorsque les utilisateurs cliquent sur certains liens hypertexte, cette action génère une tentative de navigation, puis un message d'erreur car aucun formulaire cible ne s'ouvre. La suppression des liens hypertexte dans ce type de scénario améliorera l'expérience utilisateur en supprimant ces liens hypertexte déroutants.  

