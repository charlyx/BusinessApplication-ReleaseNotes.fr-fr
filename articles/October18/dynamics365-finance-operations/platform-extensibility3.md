---
title: "Améliorations en matière d'extensibilité de la plateforme - 3è partie"
description: "Améliorations en matière d'extensibilité de la plateforme - 3è partie"
author: ChrisGarty
manager: AnnBe
ms.date: 09/18/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: cgarty
audience: developer, customizer
ms.translationtype: HT
ms.sourcegitcommit: 2b59c75306961c1f7182679096aa1336d32d508d
ms.openlocfilehash: ce99db818fd1609c944fd2602a04dab5928ccb85
ms.contentlocale: fr-fr
ms.lasthandoff: 09/20/2018

---

# <a name="platform-extensibility-enhancements-wave-3"></a>Améliorations en matière d'extensibilité de la plateforme - 3è partie

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

Améliorations des fonctionnalités d'extensibilité dans la mise à jour 22 de la plateforme :
- Activation d'une chaîne de commande pour cibler les remplacements de méthode non mis en œuvre pour les tables et les entités de données (n° de réf.198772).
- Possibilité pour une extension de table de modifier l'ordre des champs dans un groupe de champs (n° de réf. 198798).
- Activation d'une chaîne de commande sur les classes d'extension de sorte que les développeurs puissent créer des **extensions d'extensions** (n° de réf. 198848).
- Prise en charge de l'ajout de **DataMemberAttribute** sur les classes d'extension (n° 199219).
- Possibilité de définir les valeurs du champ cible dans une méthode de requête **insert_recordset** sur des valeurs littérales (n° de réf. 198849).
- Prise en charge des objets de requête pour les suppressions basées sur un ensemble à l'aide d'une méthode **delete_from** (n° de réf. 185500).
- Activez la chaîne de commande pour cibler les méthodes X++ sur les contrôles de formulaire et les sources de données qui ne sont pas des méthodes de noyau remplacées (n° de réf. 238379).
- Prise en charge de l'extension d'un formulaire pour implémenter une interface (n° de réf. 199225).
- Activation de l'ajout de méthodes d'affichage et d'édition à un FormDataSource via une extension (n° de réf. 235521).
- Autorisation de colonnes calculées sur les extensions de vue (n° de réf. 198807).
- Autorisation de l'ajout de sources de données de jointure externes et les rendre en lecture seule en ignorant les appels au noyau **Write** et **ValidateWrite** (n° de réf. 198768).
- Autorisation des modifications de **Visible**, **CountryRegionContext**, **AllowEdit**, **AllowEditOnCreate**, **Mandatory**, et **IgnoreEDTRelation** sur les champs de table (n° de réf. 198809, 198776, 199206).
- Autorisation des modifications de **Mandatory**, **IsManuallyUpdated**, **AllowEdit**, et **AllowEditOnCreate** sur les champs d'entité de données (n° de réf. 198818).
- Autorisation de l'ajout de **droits** et de **privilèges** dans un rôle de sécurité (Réf # 198819).
- Autorisation de modifications à **TimeZone** et **Extend** sur les types de données étendues (n° de réf. 237002, 238531).
- Autorisation de l'ajout de nouvelles relations aux sources de données d'une requête (n° de réf. 198823).

Les numéros de référence correspondent à des ID de demande d'extensibilité spécifiques utilisés en interne et disponibles en externe.

Pour plus d'informations sur toutes les fonctionnalités d'extensibilité, voir la [page d'accueil Extensibilité](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page).

