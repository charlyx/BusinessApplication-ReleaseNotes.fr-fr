---
title: "Filtrage avancé"
description: "Optimisez votre productivité sur votre bureau avec des fonctionnalités de filtrage puissantes."
author: mikebcMSFT
manager: edupont04
ms.date: 09/23/2018
ms.assetid: 011c924e-f156-4cd7-a034-99a13b5a7869
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: mikebc
audience: end user
ms.translationtype: HT
ms.sourcegitcommit: 8b8612bb36ad0e7abd0c55439652b9015c944035
ms.openlocfilehash: 8c2bc84d8e3e8291d5cc07b49e7ae853a5cb5df3
ms.contentlocale: fr-fr
ms.lasthandoff: 09/24/2018

---
# <a name="advanced-filtering"></a><span data-ttu-id="9f2f1-103">Filtrage avancé</span><span class="sxs-lookup"><span data-stu-id="9f2f1-103">Advanced filtering</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]



<span data-ttu-id="9f2f1-104">Travaillez efficacement avec vos listes dans Dynamics 365 Business Central en orientant les calculs et en appliquant des filtres à plusieurs champs.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-104">Work efficiently in lists in Dynamics 365 Business Central by influencing calculations and applying filters to multiple fields.</span></span>

<span data-ttu-id="9f2f1-105">Les utilisateurs des informations du back-office consacrent énormément de temps aux listes : saisie et modification des données, analyse des tendances et des écarts, ou simplement recherche d'enregistrements spécifiques.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-105">Back-office information workers spend significant time working with lists: entering or modifying data, analyzing trends and anomalies, or simply looking for specific records.</span></span> <span data-ttu-id="9f2f1-106">Bien qu'une recherche rapide puisse réduire la liste en identifiant les correspondances les plus proches parmi toutes les colonnes, les utilisateurs ont souvent besoin d'un niveau de contrôle supérieur à mesure que la base de données de l'entreprise se développe.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-106">While a quick search can reduce the list by finding the closest matches across all columns, users often need a higher degree of control as the size of the business database grows.</span></span> <span data-ttu-id="9f2f1-107">Les puissantes fonctionnalités de filtrage de Business Central permettent d'accélérer les tâches liées aux listes grâce à un contrôle absolu du filtrage au moyen d'une expérience moderne et intuitive.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-107">The powerful filtering capabilities in Business Central accelerate list-related tasks by providing absolute control over filtering in a modern and intuitive experience.</span></span>

## <a name="filtering-lists"></a><span data-ttu-id="9f2f1-108">Filtrage des listes</span><span class="sxs-lookup"><span data-stu-id="9f2f1-108">Filtering lists</span></span>
<span data-ttu-id="9f2f1-109">Ancré à droite de vos listes, le nouveau volet de filtre dispose d'une conception conviviale facile à découvrir et efficace à utiliser.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-109">Anchored to the side of your lists, the new filter pane has a familiar design that is easy to learn and efficient to work with.</span></span> <span data-ttu-id="9f2f1-110">Basculez entre les vues filtrées prédéfinies de votre liste, ajustez une vue en ajoutant vos propres filtres ou commencez simplement à partir de zéro.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-110">Switch between predefined filtered views of your list, adjust a view by adding your own filters, or simply start from scratch.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="9f2f1-111">![alt text](media/list-page-with-advanced-filter.png "Volet de filtre, affiché en regard d'une liste.")</span><span class="sxs-lookup"><span data-stu-id="9f2f1-111">![alt text](media/list-page-with-advanced-filter.png "The filter pane, shown alongside a list.")</span></span>

<span data-ttu-id="9f2f1-112">Le volet de filtre vous permet :</span><span class="sxs-lookup"><span data-stu-id="9f2f1-112">The filter pane allows you to:</span></span>

-   <span data-ttu-id="9f2f1-113">D'obtenir une vue d'ensemble des filtres appliqués, peu importe s'ils ont été définis par vous ou pas, à l'aide d'une vue filtrée ou par l'application elle-même.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-113">Get an overview of the currently applied filters, no matter if they were set by you, by a filtered view, or by the application itself.</span></span>
-   <span data-ttu-id="9f2f1-114">D'ajouter autant de colonnes filtrées que vous le souhaitez en les saisissant pour choisir rapidement à partir de n'importe quel champ dans la table source.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-114">Add as many filtered columns as you like by typing to quickly pick from any field on the source table.</span></span>
-   <span data-ttu-id="9f2f1-115">D'obtenir de l'aide pour spécifier des valeurs de filtre à l'aide des recherches ou du type de données du champ.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-115">Get assistance with specifying filter values using lookups or the field's data type.</span></span>
-   <span data-ttu-id="9f2f1-116">De créer des filtres complexes à l'aide d'opérateurs, de plages, de formules et de nouveaux jetons de filtrage tels que %MyCustomers.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-116">Create complex filters using operators, ranges, formulas and the new filter tokens such as %MyCustomers.</span></span>
-   <span data-ttu-id="9f2f1-117">De rétablir les modifications de filtre selon la vue non filtrée ou la vue prédéfinie de la liste.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-117">Revert your filter changes back to the unfiltered view or predefined view of the list.</span></span>

<span data-ttu-id="9f2f1-118">Business Central se souvient des filtres que vous avez appliqués tout au long de la session à mesure que vous naviguez entre les pages.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-118">Business Central remembers the filters you applied throughout the session as you navigate back and forth across pages.</span></span> <span data-ttu-id="9f2f1-119">La possibilité d'enregistrer définitivement vos modifications en tant que vue filtrée sera disponible ultérieurement.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-119">The ability to permanently save your changes as a filtered view will be available at a later date.</span></span>

<span data-ttu-id="9f2f1-120">Le volet de filtre est disponible sur toutes les pages où la liste représente le contenu principal, comme les feuilles de calcul.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-120">The filter pane is available on all pages where the list represents the primary content, such as worksheets.</span></span> <span data-ttu-id="9f2f1-121">Les listes incorporées en tant qu'éléments de liste continuent à utiliser un filtrage simple et adopteront ultérieurement le volet de filtre.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-121">Lists embedded as list parts continue to use simple filtering and will adopt the filter pane at a later date.</span></span>

## <a name="filtering-totals"></a><span data-ttu-id="9f2f1-122">Filtrage des totaux</span><span class="sxs-lookup"><span data-stu-id="9f2f1-122">Filtering totals</span></span>
<span data-ttu-id="9f2f1-123">L'une des fonctionnalités les plus populaires de Dynamics NAV fait son entrée dans Business Central.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-123">One of the most popular features of Dynamics NAV now makes its way to Business Central.</span></span> <span data-ttu-id="9f2f1-124">Les listes affichent souvent des valeurs regroupées ou calculées via des FlowFields, telles que des montants totaux en devises.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-124">Lists often display aggregated or computed values through FlowFields, such as currency amount totals.</span></span> <span data-ttu-id="9f2f1-125">Avec cette version, Business Central vous fournit un tout nouveau niveau de contrôle vous permettant d'appliquer des filtres à une ou plusieurs dimensions ayant une influence sur les valeurs calculées.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-125">With this release, Business Central gives you a whole new level of control through which you can apply filters to one or more dimensions that influence computed values.</span></span> <span data-ttu-id="9f2f1-126">Utilisez cette fonctionnalité en combinaison avec des filtres, triez, puis effectuez des recherches pour parcourir et analyser vos données.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-126">Use this in combination with filters, sort, and search to explore and analyze your data.</span></span>

## <a name="keyboard-shortcuts"></a><span data-ttu-id="9f2f1-127">Raccourcis clavier</span><span class="sxs-lookup"><span data-stu-id="9f2f1-127">Keyboard shortcuts</span></span>
<span data-ttu-id="9f2f1-128">Bien que le volet de filtre soit accessible en un seul clic, vous pouvez également travailler sans souris avec une variété de combinaisons de raccourcis clavier, notamment le raccourci Alt+F3 pour filtrer sur la valeur actuelle.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-128">Although the filter pane is just a click away, you can work mouse-free using a variety of powerful keyboard shortcuts, including the Alt+F3 shortcut to filter to the current value.</span></span> <span data-ttu-id="9f2f1-129">Vous pouvez désormais créer des filtres composés à la volée sans jamais quitter la liste, grâce à des raccourcis permettant de parcourir les cellules puis de filtrer sur la valeur cible actuelle ou pour effacer le filtre sur la colonne actuelle.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-129">You can now create compound filters on the fly without ever leaving the list, using shortcuts to navigate across cells and then filter to the currently focused value or clear the filter on the current column.</span></span> <span data-ttu-id="9f2f1-130">Vous trouverez la liste complète des raccourcis clavier sur https://aka.ms/bckeys.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-130">Find the full list of keyboard shortcuts at https://aka.ms/bckeys.</span></span>

<!--
### Who uses these features
These features are available to all desktop users without additional setup, in the browser or Windows 10 companion app.
## Status
### Availability
Cloud, on-premises, hybrid
### Regional availability
No regional restrictions. Available in all Dynamics 365 Business Central supported markets.
-->

## <a name="try-it-now"></a><span data-ttu-id="9f2f1-131">Essayer maintenant</span><span class="sxs-lookup"><span data-stu-id="9f2f1-131">Try it now</span></span>
<span data-ttu-id="9f2f1-132">Essayez le nouveau volet de filtre de la liste d'articles en vous connectant à votre environnement en ligne à l'adresse suivante : https://businesscentral.dynamics.com/?page=31 et en tapant **Maj+F3** pour afficher le volet de filtre.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-132">Try the new filter pane on the Items list by signing in to your online environment at https://businesscentral.dynamics.com/?page=31 and typing **Shift+F3** to show the filter pane.</span></span>

## <a name="resources"></a><span data-ttu-id="9f2f1-133">Ressources</span><span class="sxs-lookup"><span data-stu-id="9f2f1-133">Resources</span></span>
[<span data-ttu-id="9f2f1-134">Tri, recherche et filtrage de listes</span><span class="sxs-lookup"><span data-stu-id="9f2f1-134">Sorting, Searching and Filtering Lists</span></span>](https://docs.microsoft.com/en-us/dynamics365/business-central/ui-enter-criteria-filters)

[<span data-ttu-id="9f2f1-135">Utilisation des dates et heures du calendrier</span><span class="sxs-lookup"><span data-stu-id="9f2f1-135">Working with calendar dates and times</span></span>](https://docs.microsoft.com/en-US/dynamics365/business-central/ui-enter-date-ranges)

[<span data-ttu-id="9f2f1-136">Documentation technique : ajout de jetons de filtrage</span><span class="sxs-lookup"><span data-stu-id="9f2f1-136">Technical documentation: adding Filter Tokens</span></span>](https://docs.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-adding-filter-tokens)

[<span data-ttu-id="9f2f1-137">Questions fréquemment posées sur la recherche et le filtrage</span><span class="sxs-lookup"><span data-stu-id="9f2f1-137">Frequently asked questions about searching and filtering</span></span>](https://docs.microsoft.com/en-us/dynamics365/business-central/ui-search-filter-faq)

## <a name="tell-us-what-you-think"></a><span data-ttu-id="9f2f1-138">Donnez-nous votre avis</span><span class="sxs-lookup"><span data-stu-id="9f2f1-138">Tell us what you think</span></span>
<span data-ttu-id="9f2f1-139">Aidez-nous à améliorer Dynamics 365 Business Central en proposant des idées, en fournissant des suggestions et en offrant des commentaires.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-139">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="9f2f1-140">Utilisez le forum de Business Central à l'adresse https://aka.ms/businesscentralideas.</span><span class="sxs-lookup"><span data-stu-id="9f2f1-140">Use the Business Central forum at https://aka.ms/businesscentralideas.</span></span>

