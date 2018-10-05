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

# <a name="platform-extensibility-enhancements-wave-2"></a><span data-ttu-id="88271-103">Améliorations en matière d'extensibilité de la plateforme - 2è partie</span><span class="sxs-lookup"><span data-stu-id="88271-103">Platform extensibility enhancements wave 2</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="88271-104">Améliorations des fonctionnalités d'extensibilité dans la mise à jour 21 de la plateforme :</span><span class="sxs-lookup"><span data-stu-id="88271-104">Enhanced extensibility capabilities in Platform update 21:</span></span>
- <span data-ttu-id="88271-105">Les méthodes de la chaîne de commande prennent maintenant en charge les blocs **try-finally** ou **unchecked** de la clause suivante pour faciliter le nettoyage des ressources ou les ajustements des contrôles de sécurité (n° de réf. 215266, 223822).</span><span class="sxs-lookup"><span data-stu-id="88271-105">Chain of command methods now support **try-finally** or **unchecked** blocks around the next clause to facilitate resource cleanup  or security check adjustments (Ref# 215266, 223822).</span></span>
- <span data-ttu-id="88271-106">Possibilité de modifier le champ **ShowZero** sur les réels EDT (n° de réf. 198765).</span><span class="sxs-lookup"><span data-stu-id="88271-106">Allow changes to **ShowZero** on EDT Reals (Ref# 198765).</span></span>
- <span data-ttu-id="88271-107">Possibilité de modifier le champ **DisplayLength** sur les chaînes EDT (n° de réf. 198766).</span><span class="sxs-lookup"><span data-stu-id="88271-107">Allow changes to **DisplayLength** on EDT Strings (Ref# 198766).</span></span>
- <span data-ttu-id="88271-108">Possibilité de modifier le champ **Status** sur les plages de requêtes (n° de réf. 198835).</span><span class="sxs-lookup"><span data-stu-id="88271-108">Allow changes to **Status** on query ranges (Ref# 198835).</span></span>
- <span data-ttu-id="88271-109">Possibilité de modifier le champ **UseCaptionFromMenuItem** sur les formulaires (n° de réf. 198793).</span><span class="sxs-lookup"><span data-stu-id="88271-109">Allow changes to **UseCaptionFromMenuItem** on forms (Ref# 198793).</span></span>
- <span data-ttu-id="88271-110">Possibilité de modifier les champs **NeedsRecord** et **EnregistrerRecord** sur les boutons (n° de réf. 198762).</span><span class="sxs-lookup"><span data-stu-id="88271-110">Allow changes to **NeedsRecord** and **SaveRecord** on buttons (Ref# 198762).</span></span>
- <span data-ttu-id="88271-111">Possibilité de modifier les champs **AllowEdit** et **Besoin requis** sur les contrôles de formulaire (n° de réf. 149754, 198836).</span><span class="sxs-lookup"><span data-stu-id="88271-111">Allow changes to **AllowEdit** and **NeededPermission** on form controls (Ref# 149754, 198836).</span></span>
- <span data-ttu-id="88271-112">Possibilité de modifier le champ **StartPosition** sur les sources de données de formulaire (n° de réf. 198821).</span><span class="sxs-lookup"><span data-stu-id="88271-112">Allow changes to **StartPosition** on form datasources (Ref# 198821).</span></span>
- <span data-ttu-id="88271-113">Mise à jour du champ **DictClass.getAllAttributes** pour retourner les attributs définis sur les classes d'extension (n° de réf. 216149).</span><span class="sxs-lookup"><span data-stu-id="88271-113">Updated **DictClass.getAllAttributes** to return the attributes defined on extension classes (Ref# 216149).</span></span>
- <span data-ttu-id="88271-114">Énumérations des champs **DiagnosticsArea**, **DocuFilePlace**, et **DocuTypeGroup** rendues extensibles (n° de réf. 223436, 241335, 238162).</span><span class="sxs-lookup"><span data-stu-id="88271-114">Made the **DiagnosticsArea**, **DocuFilePlace**, and **DocuTypeGroup** enumerations extensible (Ref# 223436, 241335, 238162).</span></span>

<span data-ttu-id="88271-115">Les numéros de référence correspondent à des ID de demande d'extensibilité spécifiques utilisés en interne et disponibles en externe.</span><span class="sxs-lookup"><span data-stu-id="88271-115">Ref numbers correspond to specific extensibility request IDs that are used internally and available externally.</span></span>
<span data-ttu-id="88271-116">Pour plus d'informations sur toutes les fonctionnalités d'extensibilité, voir la [page d'accueil Extensibilité](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page).</span><span class="sxs-lookup"><span data-stu-id="88271-116">For more information about all extensibility capabilities, see the [Extensibility home page](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page).</span></span>
<span data-ttu-id="88271-117">.</span><span class="sxs-lookup"><span data-stu-id="88271-117">).</span></span>

