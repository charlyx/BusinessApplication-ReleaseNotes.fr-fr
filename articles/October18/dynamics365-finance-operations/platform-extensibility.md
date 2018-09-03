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
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: 374dad1c0120667f742ef9bd216b79c591c04742
ms.contentlocale: fr-fr
ms.lasthandoff: 08/16/2018

---

# <a name="platform-extensibility-enhancements"></a><span data-ttu-id="8f0fc-103">Améliorations en matière d'extensibilité de la plateforme</span><span class="sxs-lookup"><span data-stu-id="8f0fc-103">Platform extensibility enhancements</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="8f0fc-104">Améliorations des fonctionnalités d'extensibilité :</span><span class="sxs-lookup"><span data-stu-id="8f0fc-104">Enhanced extensibility capabilities:</span></span>
- <span data-ttu-id="8f0fc-105">Possibilité de modifier un formulaire pour utiliser un modèle personnalisé à l'aide d'une extension de formulaire.</span><span class="sxs-lookup"><span data-stu-id="8f0fc-105">Enable changing a form to use a custom pattern using a form extension.</span></span> <span data-ttu-id="8f0fc-106">Cela permet aux éditeur de logiciels indépendant d'ajouter des onglets et d'autres parties de formulaire qui ne tenaient pas sur le modèle d'origine.</span><span class="sxs-lookup"><span data-stu-id="8f0fc-106">This is to enable ISVs to add tabs and other form parts that do not fit the original pattern.</span></span> <span data-ttu-id="8f0fc-107">Les développeurs peuvent désormais **utiliser un modèle personnalisé** et **restaurer le modèle d'origine**.</span><span class="sxs-lookup"><span data-stu-id="8f0fc-107">Developers now have actions to **Set pattern to custom** and **Restore original pattern**.</span></span>
- <span data-ttu-id="8f0fc-108">Possibilité pour une extension de modifier **TableField.AssetClassification** afin que les informations de classification des données du Règlement général sur la protection des données (RGPD) soient fournies.</span><span class="sxs-lookup"><span data-stu-id="8f0fc-108">Allow an extension to change **TableField.AssetClassification** so General Data Protection Regulation (GDPR) data classification information can be provided.</span></span>
- <span data-ttu-id="8f0fc-109">Possibilité pour les méthodes d'extension de formulaire d'appeler les méthodes et les contrôles ajoutés via d'autres extensions.</span><span class="sxs-lookup"><span data-stu-id="8f0fc-109">Enable form extension methods to call methods and controls added via other extensions.</span></span> <span data-ttu-id="8f0fc-110">Par exemple, désormais, lorsque qu'un formulaire contient un bouton et des méthodes ajoutés via une extension, les prochaines extensions à ce formulaire pourront appeler le nouveau bouton et les nouvelles méthodes.</span><span class="sxs-lookup"><span data-stu-id="8f0fc-110">For example, now when a form has a button and some methods added via extension, then future extensions to that form will be able to call the new button and methods.</span></span>
- <span data-ttu-id="8f0fc-111">Prise en charge des objets de requête pour les instructions de mise à jour basées sur un ensemble via une méthode **update_recordset**.</span><span class="sxs-lookup"><span data-stu-id="8f0fc-111">Add query object support for set-based update statements via an **update_recordset** method.</span></span>
- <span data-ttu-id="8f0fc-112">Possibilité pour une extension de requête d'ajouter une source de données racine à une requête Union.</span><span class="sxs-lookup"><span data-stu-id="8f0fc-112">Allow a query extension to add a root datasource to a union query.</span></span>
- <span data-ttu-id="8f0fc-113">Possibilité d'ajouter des lignes dans une vue à l'aide d'une extension.</span><span class="sxs-lookup"><span data-stu-id="8f0fc-113">Enable the addition of ranges into a view using an extension.</span></span>
- <span data-ttu-id="8f0fc-114">Possibilité de définir **SupportsSetBasedSqlOperations** sur les extensions de vue d'entité de données.</span><span class="sxs-lookup"><span data-stu-id="8f0fc-114">Enable setting **SupportsSetBasedSqlOperations** on data entity view extensions.</span></span> <span data-ttu-id="8f0fc-115">La valeur Oui ne peut être attribuée que si cette valeur a été attribuée à toutes les extensions, y compris à l'élément de base.</span><span class="sxs-lookup"><span data-stu-id="8f0fc-115">Yes can only be set if all extensions have it set to Yes including the base element.</span></span> <span data-ttu-id="8f0fc-116">Si la valeur Non est attribuée à une extension ou à l'élément de base, le résultat de l'exécution sera Non.</span><span class="sxs-lookup"><span data-stu-id="8f0fc-116">If any extension or the base element has the value set to No, then runtime result will be No.</span></span>
- <span data-ttu-id="8f0fc-117">Possibilité pour une extension de formulaire d'ajouter un workflow à un formulaire en modifiant **WorkflowEnabled**, **WorkflowDataSource** et **WorkflowType**.</span><span class="sxs-lookup"><span data-stu-id="8f0fc-117">Allow a form extension to add workflow to a form by editing **WorkflowEnabled**, **WorkflowDataSource**, and **WorkflowType**.</span></span>
- <span data-ttu-id="8f0fc-118">Activation d'une chaîne de commande pour les méthodes de formulaire.</span><span class="sxs-lookup"><span data-stu-id="8f0fc-118">Enable Chain of Command for form methods.</span></span> <span data-ttu-id="8f0fc-119">En particulier, cela permet à une extension d'ajouter un workflow à un formulaire en remplaçant la méthode **canSubmitToWorkflow**.</span><span class="sxs-lookup"><span data-stu-id="8f0fc-119">In particular this allows an extension to add workflow to a form by overriding the **canSubmitToWorkflow** method.</span></span> <span data-ttu-id="8f0fc-120">Notez que si la méthode de formulaire ciblée est une méthode de noyau sans remplacement de X++, la recompilation du formulaire cible sera nécessaire.</span><span class="sxs-lookup"><span data-stu-id="8f0fc-120">Note that if the targeted form method is a kernel method without an X++ override, then a recompile of the target form will be needed.</span></span> 
- <span data-ttu-id="8f0fc-121">Activation d'une chaîne de commande pour les entités de données.</span><span class="sxs-lookup"><span data-stu-id="8f0fc-121">Enable Chain of Command for data entities.</span></span>
- <span data-ttu-id="8f0fc-122">Activation d'une chaîne de commande sur les types imbriqués dans les formulaires contenant des source de données et des contrôles.</span><span class="sxs-lookup"><span data-stu-id="8f0fc-122">Enable Chain of Command on nested types within forms including datasources and controls.</span></span>

<span data-ttu-id="8f0fc-123">Pour plus d'informations sur toutes les fonctionnalités d'extensibilité, voir la [page d'accueil Extensiblité](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page).</span><span class="sxs-lookup"><span data-stu-id="8f0fc-123">For more information about all the extensibility capabilities, see the [Extensiblity home page](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page).</span></span>

