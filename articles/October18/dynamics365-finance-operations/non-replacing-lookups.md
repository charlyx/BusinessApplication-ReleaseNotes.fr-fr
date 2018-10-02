---
title: "Comportement amélioré des recherches non remplaçantes"
description: "Un certain nombre d'améliorations fonctionnelles ont été apportées aux recherches non remplaçantes dans Finance and Operations."
author: jasongre
manager: AnnBe
ms.date: 08/10/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: jasongre
audience: developer, admin, end user, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: bc5017cc0df74ed2071e2b77c65d62dc3cc5a198
ms.contentlocale: fr-fr
ms.lasthandoff: 08/16/2018

---

# <a name="improved-behavior-of-non-replacing-lookups"></a>Comportement amélioré des recherches non remplaçantes

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

Certaines recherches dans Finance and Operations sont *non remplaçantes* : cela signifie que lorsqu'une valeur est sélectionnée dans la recherche, cette valeur ne remplace pas la ou les valeurs déjà présentes dans le champ mais elle est ajoutée dans le champ. Par exemple, les recherches de la boîte de dialogue **Tri/filtre avancé** sont non remplaçantes par défaut.  

Le comportement des recherches non remplaçantes a été amélioré des manières suivantes : 

- Le comportement de la saisie semi-automatique a été désactivée pour les recherches non remplaçantes. 

- Seuls les caractères saisis une fois la recherche ouverte sont utilisés dans la grille de recherche.

- La valeur sélectionnée dans la recherche est ajoutée à ce qui se trouvait dans le champ avant l'ouverture de la recherche (autrement dit, tous les caractères saisis lorsque la recherche était ouverte sont remplacés lors de l'ajout de la valeur sélectionnée dans la recherche).  

- Une nouvelle icône s'affiche désormais sur les recherches non remplaçantes afin qu'elles se différencient visuellement des recherches classiques.

Ces ajustements permettent aux utilisateurs de filtrer plus facilement les données à l'aide de la boîte de dialogue **Tri/filtre avancé**.

