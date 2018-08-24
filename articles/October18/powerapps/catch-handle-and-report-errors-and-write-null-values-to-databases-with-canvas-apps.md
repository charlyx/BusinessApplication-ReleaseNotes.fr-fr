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
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: e79ea4939906626d448c7a389f7507061bed596b
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
# <a name="catch-handle-and-report-errors-and-write-null-values-to-databases-with-canvas-apps"></a>Détecter, gérer et signaler les erreurs, et entrer des valeurs Null dans les bases de données avec des applications de canevas

[!include[powerapps banner](../includes/powerapps.md)]




Des erreurs se produisent.  Les applications de canevas adoptent un comportement par défaut dans ce cas, mais cela ne correspond pas toujours à ce qui est attendu.  Avec cette fonctionnalité, vous pouvez intercepter, interroger, signaler, supprimer, consigner et envoyer des messages d'erreur aux utilisateurs.

Il était auparavant impossible de faire la différence entre les erreurs et les valeurs Null, la transmission de valeurs Null aux bases de données posait donc problème.  La valeur Null est une valeur légitime dans de nombreux systèmes de base de données.  Quand les erreurs sont correctement séparées dans des applications de canevas, vous pouvez entrer des valeurs Null dans toutes les bases de données.

