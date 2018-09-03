---
title: "Grille améliorée avec la fonction Copier/Coller"
description: "Chargement amélioré des listes et capacité de copier et coller des lignes."
author: mikebcMSFT
manager: edupont04
ms.date: 07/22/2018
ms.assetid: 011c924e-f156-4cd7-a034-99a13b5a7869
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: mikebc
audience: end user
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 0eab65dd0deeb5648202e8f6c15b2c87ed34f3d6
ms.contentlocale: fr-fr
ms.lasthandoff: 08/15/2018

---
#  <a name="improved-grid-with-copy-and-paste"></a><span data-ttu-id="9f544-103">Grille améliorée avec la fonction Copier/Coller</span><span class="sxs-lookup"><span data-stu-id="9f544-103">Improved grid with copy and paste</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]



<span data-ttu-id="9f544-104">Utilisez efficacement des listes dans Dynamics 365 Business Central avec une évolutivité de grille avancée et la capacité de copier-coller des lignes.</span><span class="sxs-lookup"><span data-stu-id="9f544-104">Work efficiently in lists in Dynamics 365 Business Central with improved grid scalability and the ability to copy and paste rows.</span></span>

<span data-ttu-id="9f544-105">Les utilisateurs des informations du back-office consacrent énormément de temps aux listes : analyse des tendances et des écarts, ou saisie et modification des données.</span><span class="sxs-lookup"><span data-stu-id="9f544-105">Back-office information workers spend significant time working with lists: analyzing trends and anomalies or entering and modifying data.</span></span> <span data-ttu-id="9f544-106">À mesure que la base de données d'entreprise se développe, l'expérience doit rester performant et permettre aux utilisateurs de continuer de travailler efficacement.</span><span class="sxs-lookup"><span data-stu-id="9f544-106">As the business database grows, the experience must remain performant and enable users to continue working efficiently.</span></span> <span data-ttu-id="9f544-107">Les tâches de saisie de données répétitives peuvent être considérablement accélérées en copiant les données entrées précédemment, et les utilisateurs attendent des raccourcis clavier aux normes du secteur, tels que Ctrl+C, pour atteindre ce niveau de productivité.</span><span class="sxs-lookup"><span data-stu-id="9f544-107">Repetitive data entry tasks can be greatly accelerated by copying data entered earlier, and users expect industry-standard keyboard shortcuts such as Ctrl+C to help achieve that level of productivity.</span></span> <span data-ttu-id="9f544-108">Pouvoir copier des données dans le Presse-papiers facilite également le déplacement des données entre les logiciels, comme le collage d'une liste d'éléments faisant l'objet d'une remise dans un courrier électronique à un client.</span><span class="sxs-lookup"><span data-stu-id="9f544-108">Being able to copy data to the clipboard also facilitates moving data across software boundaries, such as pasting a list of discounted items into an email to a customer.</span></span>

## <a name="improved-grid"></a><span data-ttu-id="9f544-109">Grille améliorée</span><span class="sxs-lookup"><span data-stu-id="9f544-109">Improved grid</span></span>
<span data-ttu-id="9f544-110">Nous avons réécrit l'affichage des listes et la manière dont elle extraient les données, afin de permettre aux grilles de s'adapter à un nombre supérieur de lignes et de colonnes.</span><span class="sxs-lookup"><span data-stu-id="9f544-110">We've rewritten how lists are displayed and how they fetch data, allowing grids to scale to more rows and more columns.</span></span> <span data-ttu-id="9f544-111">Cela améliore la rapidité globale de la navigation entre les cellules de la grille.</span><span class="sxs-lookup"><span data-stu-id="9f544-111">This improves the overall snappiness of navigating across grid cells.</span></span> <span data-ttu-id="9f544-112">Le préchargement des lignes plus fréquent offre une expérience de défilement plus transparente.</span><span class="sxs-lookup"><span data-stu-id="9f544-112">Preloading rows more frequently makes for a seamless scrolling experience.</span></span> <span data-ttu-id="9f544-113">Les utilisateurs peuvent désormais faire défiler jusqu'à n'importe quelle position de la liste à l'aide du clavier ou de la barre de défilement, et les données de la vue s'affichent immédiatement.</span><span class="sxs-lookup"><span data-stu-id="9f544-113">Users can now scroll to any position in the list using the keyboard or scroll bar, and the data in view will display immediately.</span></span>

## <a name="copy-and-paste"></a><span data-ttu-id="9f544-114">Copier et coller</span><span class="sxs-lookup"><span data-stu-id="9f544-114">Copy and paste</span></span>
<span data-ttu-id="9f544-115">Cette fonctionnalité vous permet :</span><span class="sxs-lookup"><span data-stu-id="9f544-115">This enables you to:</span></span>

* <span data-ttu-id="9f544-116">De copier une ou plusieurs lignes dans une liste et de les coller dans la même liste (ou similaire).</span><span class="sxs-lookup"><span data-stu-id="9f544-116">Copy one or more rows in a list and paste them to the same (or similar) list.</span></span>
* <span data-ttu-id="9f544-117">De copier une ou plusieurs lignes et de les coller dans Microsoft Excel, y compris les légendes des colonnes.</span><span class="sxs-lookup"><span data-stu-id="9f544-117">Copy one or more rows and paste them into Microsoft Excel, including the column captions.</span></span>
  <span data-ttu-id="9f544-118">Vous n'utilisez pas Excel ?</span><span class="sxs-lookup"><span data-stu-id="9f544-118">Not using Excel?</span></span> <span data-ttu-id="9f544-119">La plupart des applications comme Microsoft Outlook permettent de coller du contenu tabulaire à l'endroit où les légendes des colonnes s'afficheront.</span><span class="sxs-lookup"><span data-stu-id="9f544-119">Most applications such as Microsoft Outlook allow pasting tabular content where the column captions will be displayed.</span></span>
* <span data-ttu-id="9f544-120">De copier une ou plusieurs lignes dans Excel et de la coller dans Business Central.</span><span class="sxs-lookup"><span data-stu-id="9f544-120">Copy one or more rows from Excel and paste them into DBusiness Central.</span></span>

## <a name="keyboard-shortcuts"></a><span data-ttu-id="9f544-121">Raccourcis clavier</span><span class="sxs-lookup"><span data-stu-id="9f544-121">Keyboard shortcuts</span></span>
<span data-ttu-id="9f544-122">Hormis les raccourcis au normes du secteur Ctrl+C et Ctrl+V, nous avons ajouté raccourci F8 très demandé permettant de copier la cellule du dessus.</span><span class="sxs-lookup"><span data-stu-id="9f544-122">Apart from the industry-standard shortcuts Ctrl+C and Ctrl+V, we've added the highly requested F8 shortcut that copies the cell above.</span></span> <span data-ttu-id="9f544-123">Vous pouvez rapidement remplir une nouvelle ligne en appuyant sur la touche Tab dans les cellules et en sélectionnant F8 sur les cellules dans lesquelles vous souhaitez copier la valeur de la ligne du dessus.</span><span class="sxs-lookup"><span data-stu-id="9f544-123">You can rapidly fill in a new row by tabbing across cells and selecting F8 on the cells where you want to copy the value from the row above.</span></span>

<!--
### Who uses these features
These features are available to all desktop users without additional setup in the browser or Windows 10 companion app.
## Status
### Availability
Cloud, on-premises, hybrid
### Regional availability
No regional restrictions. Available to all Dynamics 365 Business Central supported markets.
-->

## <a name="tell-us-what-you-think"></a><span data-ttu-id="9f544-124">Donnez-nous votre avis</span><span class="sxs-lookup"><span data-stu-id="9f544-124">Tell us what you think</span></span>
<span data-ttu-id="9f544-125">Aidez-nous à améliorer Dynamics 365 Business Central en proposant des idées, en fournissant des suggestions et en offrant des commentaires.</span><span class="sxs-lookup"><span data-stu-id="9f544-125">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="9f544-126">Utilisez le forum de Business Central à l'adresse https://aka.ms/businesscentralideas.</span><span class="sxs-lookup"><span data-stu-id="9f544-126">Use the Business Central forum at https://aka.ms/businesscentralideas.</span></span>

