---
title: "Modèles composites"
description: "Prise en charge du mélange de sources de données pour DirectQuery et pour l'importation dans Power BI Desktop"
author: MI77
manager: kimani
ms.date: 7/22/18
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: willthom
audience: developer, citizen developer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 3256b373787e8c32a7ef80faad85e2ebd5f3634e
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---

# <a name="composite-models-public-preview"></a>Modèles composites (version préliminaire publique)

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]

Les modèles composites vous permettent de mélanger des sources de données DirectQuery tabulaires et importées, mais aussi d'avoir plusieurs sources de données DirectQuery tabulaires. Vous pouvez ainsi étoffer vos modèles de données d'entreprise avec des tables importées. 

Les modeleurs peuvent créer un fichier Power BI Desktop sur une source de données DirectQuery, puis ajouter des tables importées à partir d'une autre source de données. Pour prendre en charge cette nouvelle structure de modèle, nous mettons également en place des relations plusieurs-à-plusieurs et des tables en mode mixte, ce qui signifie qu'elles peuvent agir en tant qu'outil d'importation ou DirectQuery, selon les autres tables que vous ajoutez aux visuels. Power BI répond alors intelligemment à vos questions, soit à partir des données importées, soit en envoyant une requête à la source de données sous-jacente.

<!--
### Who uses this feature
This feature is intended for model developers. 
## Status
### Development status
In development
#### Target timeframe
October ‘18
-->

