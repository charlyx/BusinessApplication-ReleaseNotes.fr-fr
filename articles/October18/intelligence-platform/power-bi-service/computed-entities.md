---
title: "Entités calculées"
description: "La prise en charge des entités calculées permet à des tiers de créer des applications Power BI en exploitant des flux de données avec des informations plus riches et des fonctionnalités d'IA."
author: adiregev
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: adiregev
audience: 
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 43b015ad18453b1bd9a9f9f60c79f23c3afa5bce
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
# <a name="computed-entities-public-preview"></a>Entités calculées (Version préliminaire publique)  

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



Les entités de flux de données sont enregistrées dans des dossiers compatibles Common Data Model (dossiers CDM), dans Azure Data Lake Storage Gen2. Une fois les entités chargées dans les dossiers CDM, vous pouvez générer de nouvelles informations en transformant, en modifiant, et en enrichissant des entités, et en regroupant des données à grande échelle. Ces entités nouvellement créées sont également stockées dans des dossiers CDM. L'analyse statique des expressions Power Query M permet d'identifier automatiquement les dépendances entre les entités. Ainsi, elles sont toujours mises à jour dans l'ordre optimal, sans intervention manuelle. 

La prise en charge des entités calculées permet à des tiers de créer des applications Power BI en exploitant des flux de données avec des informations plus riches et des fonctionnalités d'IA. Par exemple, vous pouvez enrichir une entité de compte client à partir de Dynamics 365 for Sales avec des informations provenant des tickets de service dans Dynamics 365 for Service et des informations répondant aux besoins des clients à partir de Office 365.
Power BI Premium est requis pour pouvoir actualiser les entités calculées. 

