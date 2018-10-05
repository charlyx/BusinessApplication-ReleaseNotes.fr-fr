---
title: "Améliorations en matière d'extensibilité de la plateforme - 2è partie"
description: "Améliorations en matière d'extensibilité de la plateforme - 2è partie"
author: ChrisGarty
manager: AnnBe
ms.date: 08/09/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: cgarty
audience: developer, customizer
ms.translationtype: HT
ms.sourcegitcommit: 2b59c75306961c1f7182679096aa1336d32d508d
ms.openlocfilehash: eef19354500687c16206dbbba817d6da858a4071
ms.contentlocale: fr-fr
ms.lasthandoff: 09/20/2018

---

# <a name="platform-extensibility-enhancements-wave-2"></a>Améliorations en matière d'extensibilité de la plateforme - 2è partie

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

Améliorations des fonctionnalités d'extensibilité dans la mise à jour 21 de la plateforme :
- Les méthodes de la chaîne de commande prennent maintenant en charge les blocs **try-finally** ou **unchecked** de la clause suivante pour faciliter le nettoyage des ressources ou les ajustements des contrôles de sécurité (n° de réf. 215266, 223822).
- Possibilité de modifier le champ **ShowZero** sur les réels EDT (n° de réf. 198765).
- Possibilité de modifier le champ **DisplayLength** sur les chaînes EDT (n° de réf. 198766).
- Possibilité de modifier le champ **Status** sur les plages de requêtes (n° de réf. 198835).
- Possibilité de modifier le champ **UseCaptionFromMenuItem** sur les formulaires (n° de réf. 198793).
- Possibilité de modifier les champs **NeedsRecord** et **EnregistrerRecord** sur les boutons (n° de réf. 198762).
- Possibilité de modifier les champs **AllowEdit** et **Besoin requis** sur les contrôles de formulaire (n° de réf. 149754, 198836).
- Possibilité de modifier le champ **StartPosition** sur les sources de données de formulaire (n° de réf. 198821).
- Mise à jour du champ **DictClass.getAllAttributes** pour retourner les attributs définis sur les classes d'extension (n° de réf. 216149).
- Énumérations des champs **DiagnosticsArea**, **DocuFilePlace**, et **DocuTypeGroup** rendues extensibles (n° de réf. 223436, 241335, 238162).

Les numéros de référence correspondent à des ID de demande d'extensibilité spécifiques utilisés en interne et disponibles en externe.
Pour plus d'informations sur toutes les fonctionnalités d'extensibilité, voir la [page d'accueil Extensibilité](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page).
.

