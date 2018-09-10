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
ms.sourcegitcommit: b6df0f68e3460358864533346e69a712684da551
ms.openlocfilehash: c198c53f04636c4cbef3f6723cfa5246afc06cfa
ms.contentlocale: fr-fr
ms.lasthandoff: 08/16/2018

---
# <a name="catch-handle-and-report-errors-and-write-null-values-to-databases-with-canvas-apps-public-preview"></a>Détecter, gérer et signaler les erreurs, et entrer des valeurs Null dans les bases de données avec des applications de canevas (version préliminaire publique)


[!include[banner](../../includes/banner.md)]

Des erreurs se produisent.  Les applications de canevas adoptent un comportement par défaut dans ce cas, mais cela ne correspond pas toujours à ce qui est attendu.  Avec cette fonctionnalité, vous pouvez intercepter, interroger, signaler, supprimer, consigner et envoyer des messages d'erreur aux utilisateurs.

Il était auparavant impossible de faire la différence entre les erreurs et les valeurs Null, la transmission de valeurs Null aux bases de données posait donc problème.  La valeur Null est une valeur légitime dans de nombreux systèmes de base de données.  Quand les erreurs sont correctement séparées dans des applications de canevas, vous pouvez entrer des valeurs Null dans toutes les bases de données.

