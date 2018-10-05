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

# <a name="platform-extensibility-enhancements-wave-3"></a><span data-ttu-id="a8c9a-103">Améliorations en matière d'extensibilité de la plateforme - 3è partie</span><span class="sxs-lookup"><span data-stu-id="a8c9a-103">Platform extensibility enhancements wave 3</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="a8c9a-104">Améliorations des fonctionnalités d'extensibilité dans la mise à jour 22 de la plateforme :</span><span class="sxs-lookup"><span data-stu-id="a8c9a-104">Enhanced extensibility capabilities in Platform update 22:</span></span>
- <span data-ttu-id="a8c9a-105">Activation d'une chaîne de commande pour cibler les remplacements de méthode non mis en œuvre pour les tables et les entités de données (n° de réf.198772).</span><span class="sxs-lookup"><span data-stu-id="a8c9a-105">Enable Chain of Command to target method overrides that have not been implemented to Tables and Data Entities (Ref# 198772).</span></span>
- <span data-ttu-id="a8c9a-106">Possibilité pour une extension de table de modifier l'ordre des champs dans un groupe de champs (n° de réf. 198798).</span><span class="sxs-lookup"><span data-stu-id="a8c9a-106">Enable a table extension to change the order of fields in a field group (Ref# 198798).</span></span>
- <span data-ttu-id="a8c9a-107">Activation d'une chaîne de commande sur les classes d'extension de sorte que les développeurs puissent créer des **extensions d'extensions** (n° de réf. 198848).</span><span class="sxs-lookup"><span data-stu-id="a8c9a-107">Enable Chain of Command on extension classes so that developers can create **extensions of extensions** (Ref# 198848).</span></span>
- <span data-ttu-id="a8c9a-108">Prise en charge de l'ajout de **DataMemberAttribute** sur les classes d'extension (n° 199219).</span><span class="sxs-lookup"><span data-stu-id="a8c9a-108">Support adding **DataMemberAttribute** on extension classes (Ref# 199219).</span></span>
- <span data-ttu-id="a8c9a-109">Possibilité de définir les valeurs du champ cible dans une méthode de requête **insert_recordset** sur des valeurs littérales (n° de réf. 198849).</span><span class="sxs-lookup"><span data-stu-id="a8c9a-109">Allow setting the target field values in a Query **insert_recordset** method to literal values (Ref# 198849).</span></span>
- <span data-ttu-id="a8c9a-110">Prise en charge des objets de requête pour les suppressions basées sur un ensemble à l'aide d'une méthode **delete_from** (n° de réf. 185500).</span><span class="sxs-lookup"><span data-stu-id="a8c9a-110">Add query object support for set-based delete by using a **delete_from** method (Ref# 185500).</span></span>
- <span data-ttu-id="a8c9a-111">Activez la chaîne de commande pour cibler les méthodes X++ sur les contrôles de formulaire et les sources de données qui ne sont pas des méthodes de noyau remplacées (n° de réf. 238379).</span><span class="sxs-lookup"><span data-stu-id="a8c9a-111">Enable Chain of Command to target X++ methods on form controls and data sources that are not overridden kernel methods (Ref# 238379).</span></span>
- <span data-ttu-id="a8c9a-112">Prise en charge de l'extension d'un formulaire pour implémenter une interface (n° de réf. 199225).</span><span class="sxs-lookup"><span data-stu-id="a8c9a-112">Support extending a form to implement an interface (Ref# 199225).</span></span>
- <span data-ttu-id="a8c9a-113">Activation de l'ajout de méthodes d'affichage et d'édition à un FormDataSource via une extension (n° de réf. 235521).</span><span class="sxs-lookup"><span data-stu-id="a8c9a-113">Enable adding display and edit methods to a FormDataSource via extension (Ref# 235521).</span></span>
- <span data-ttu-id="a8c9a-114">Autorisation de colonnes calculées sur les extensions de vue (n° de réf. 198807).</span><span class="sxs-lookup"><span data-stu-id="a8c9a-114">Allow computed columns on view extensions (Ref# 198807).</span></span>
- <span data-ttu-id="a8c9a-115">Autorisation de l'ajout de sources de données de jointure externes et les rendre en lecture seule en ignorant les appels au noyau **Write** et **ValidateWrite** (n° de réf. 198768).</span><span class="sxs-lookup"><span data-stu-id="a8c9a-115">Allow adding outer join data sources and making them read-only by skipping the **Write** and **ValidateWrite** kernel calls (Ref# 198768).</span></span>
- <span data-ttu-id="a8c9a-116">Autorisation des modifications de **Visible**, **CountryRegionContext**, **AllowEdit**, **AllowEditOnCreate**, **Mandatory**, et **IgnoreEDTRelation** sur les champs de table (n° de réf. 198809, 198776, 199206).</span><span class="sxs-lookup"><span data-stu-id="a8c9a-116">Allow changes to **Visible**, **CountryRegionContext**, **AllowEdit**, **AllowEditOnCreate**, **Mandatory**, and **IgnoreEDTRelation** on table fields (Ref# 198809, 198776, 199206).</span></span>
- <span data-ttu-id="a8c9a-117">Autorisation des modifications de **Mandatory**, **IsManuallyUpdated**, **AllowEdit**, et **AllowEditOnCreate** sur les champs d'entité de données (n° de réf. 198818).</span><span class="sxs-lookup"><span data-stu-id="a8c9a-117">Allow changes to **Mandatory**, **IsManuallyUpdated**, **AllowEdit**, and **AllowEditOnCreate** on data entity fields (Ref# 198818).</span></span>
- <span data-ttu-id="a8c9a-118">Autorisation de l'ajout de **droits** et de **privilèges** dans un rôle de sécurité (Réf # 198819).</span><span class="sxs-lookup"><span data-stu-id="a8c9a-118">Allow adding **duties** and **privileges** into a security role (Ref# 198819).</span></span>
- <span data-ttu-id="a8c9a-119">Autorisation de modifications à **TimeZone** et **Extend** sur les types de données étendues (n° de réf. 237002, 238531).</span><span class="sxs-lookup"><span data-stu-id="a8c9a-119">Allow changes to **TimeZone** and **Extends** on extended data types (Ref# 237002, 238531).</span></span>
- <span data-ttu-id="a8c9a-120">Autorisation de l'ajout de nouvelles relations aux sources de données d'une requête (n° de réf. 198823).</span><span class="sxs-lookup"><span data-stu-id="a8c9a-120">Allow adding new relations to query datasources (Ref# 198823).</span></span>

<span data-ttu-id="a8c9a-121">Les numéros de référence correspondent à des ID de demande d'extensibilité spécifiques utilisés en interne et disponibles en externe.</span><span class="sxs-lookup"><span data-stu-id="a8c9a-121">Ref numbers correspond to specific extensibility request IDs that are used internally and available externally.</span></span>

<span data-ttu-id="a8c9a-122">Pour plus d'informations sur toutes les fonctionnalités d'extensibilité, voir la [page d'accueil Extensibilité](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page).</span><span class="sxs-lookup"><span data-stu-id="a8c9a-122">For more information about all extensibility capabilities, see the [Extensibility home page](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page).</span></span>

