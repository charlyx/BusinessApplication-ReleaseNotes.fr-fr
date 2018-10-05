---
title: "Améliorations en matière d'extensibilité de la plateforme"
description: "Améliorations en matière d'extensibilité de la plateforme"
author: ChrisGarty
manager: AnnBe
ms.date: 08/10/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: cgarty
audience: developer, customizer
ms.translationtype: HT
ms.sourcegitcommit: 2b59c75306961c1f7182679096aa1336d32d508d
ms.openlocfilehash: de401295109fbcad486c958530bafb8c8c7ce4a0
ms.contentlocale: fr-fr
ms.lasthandoff: 09/20/2018

---

# <a name="platform-extensibility-enhancements"></a>Améliorations en matière d'extensibilité de la plateforme

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

Amélioration des fonctionnalités d'extensibilité dans Platform update 16 via Platform update 20 :

- Possibilité de modifier un formulaire pour utiliser un modèle personnalisé à l'aide d'une extension de formulaire. Cela permet aux éditeur de logiciels indépendant d'ajouter des onglets et d'autres parties de formulaire qui ne tenaient pas sur le modèle d'origine. Les développeurs peuvent désormais **utiliser un modèle personnalisé** et **restaurer le modèle d'origine**.

- Possibilité pour une extension de modifier **TableField.AssetClassification** afin que les informations de classification des données du Règlement général sur la protection des données (RGPD) soient fournies.

- Possibilité pour les méthodes d'extension de formulaire d'appeler les méthodes et les contrôles ajoutés via d'autres extensions. Par exemple, désormais, lorsque qu'un formulaire contient un bouton et des méthodes ajoutés via une extension, les prochaines extensions à ce formulaire pourront appeler le nouveau bouton et les nouvelles méthodes.

- Prise en charge des objets de requête pour les instructions de mise à jour basées sur un ensemble via une méthode **update_recordset**.

- Possibilité pour une extension de requête d'ajouter une source de données racine à une requête Union.

- Possibilité d'ajouter des lignes dans une vue à l'aide d'une extension.

- Possibilité de définir **SupportsSetBasedSqlOperations** sur les extensions de vue d'entité de données. La valeur Oui ne peut être attribuée que si cette valeur a été attribuée à toutes les extensions, y compris à l'élément de base. Si la valeur Non est attribuée à une extension ou à l'élément de base, le résultat de l'exécution sera Non.

- Possibilité pour une extension de formulaire d'ajouter un workflow à un formulaire en modifiant **WorkflowEnabled**, **WorkflowDataSource** et **WorkflowType**.

- Activation d'une chaîne de commande pour les méthodes de formulaire. En particulier, cela permet à une extension d'ajouter un workflow à un formulaire en remplaçant la méthode **canSubmitToWorkflow**. Notez que si la méthode de formulaire ciblée est une méthode de noyau sans remplacement de X++, la recompilation du formulaire cible sera nécessaire. 

- Activation d'une chaîne de commande pour les entités de données.

- Activation d'une chaîne de commande sur les types imbriqués dans les formulaires contenant des source de données et des contrôles.

Pour plus d'informations sur les fonctionnalités d'extensibilité, voir la [page d'accueil Extensibilité](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page).

