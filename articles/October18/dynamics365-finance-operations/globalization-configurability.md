---
title: "Globalisation – Configurabilité améliorée"
description: "Cette rubrique décrit la configuration avancée dans la gestion des états électroniques, le moteur de taxes de globalisation."
author: yijialuan
manager: sshvedov
ms.date: 09/07/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: riluan
audience: Admin, developer, end-user
ms.translationtype: HT
ms.sourcegitcommit: 82ebd0def3ad9a394a1764eb77a8e2ece04f5048
ms.openlocfilehash: 34b2a3e3f30b9d6be72b7bfefb30f887661d1c04
ms.contentlocale: fr-fr
ms.lasthandoff: 09/07/2018

---

# <a name="globalization--enhanced-configurability"></a><span data-ttu-id="cb9a8-103">Globalisation – configurabilité améliorée</span><span class="sxs-lookup"><span data-stu-id="cb9a8-103">Globalization – enhanced configurability</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="cb9a8-104">La configurabilité des fonctionnalités permet aux partenaires et aux clients de créer des extensions et des personnalisations sans codage.</span><span class="sxs-lookup"><span data-stu-id="cb9a8-104">Configurability of features lets partners and customers do extensions and customizations without coding.</span></span> <span data-ttu-id="cb9a8-105">Nous continuons à étendre l'étendue de la configurabilité et avons ajouté les nouvelles fonctionnalités suivantes dans ce domaine :</span><span class="sxs-lookup"><span data-stu-id="cb9a8-105">We continue to extend both the depth and the breadth of configurability and added the following new capabilities in this area:</span></span>

- <span data-ttu-id="cb9a8-106">Validations statiques et règles de performances dynamiques pour la configuration.</span><span class="sxs-lookup"><span data-stu-id="cb9a8-106">Static validations and dynamic performance rules for configuration.</span></span> <span data-ttu-id="cb9a8-107">Cette fonctionnalité permet d'éviter une dégradation des performances lorsque les partenaires ou les clients personnalisent les configurations et de guider les utilisateurs pendant ces personnalisations.</span><span class="sxs-lookup"><span data-stu-id="cb9a8-107">This feature prevents performance degradation when partners or customers customize configurations and guide users while doing such customizations.</span></span>
- <span data-ttu-id="cb9a8-108">Comparaison automatique des exécutions des formats de gestion des états électroniques avec les lignes de base définies dans les guides de tâche, ce qui nous fournit, ainsi qu'à nos partenaires et à nos clients, des fonctionnalités de test automatique.</span><span class="sxs-lookup"><span data-stu-id="cb9a8-108">Automatic comparison of electronic reporting format executions with baselines defined in task guides, which provides us and our partners and customers with automatic test capabilities.</span></span> <span data-ttu-id="cb9a8-109">Ces tests portent sur les utilisateurs professionnels plutôt que sur les ingénieurs.</span><span class="sxs-lookup"><span data-stu-id="cb9a8-109">These tests focus on business users rather than engineers.</span></span>
- <span data-ttu-id="cb9a8-110">Chemins d'accès relatifs dans les formules de gestion d'états électroniques.</span><span class="sxs-lookup"><span data-stu-id="cb9a8-110">Relative paths in electronic reporting formulas.</span></span> <span data-ttu-id="cb9a8-111">Cette fonctionnalité permet un remappage rapide du format si vous devez basculer vers une autre entité de données ou un autre nœud XML avec une structure similaire.</span><span class="sxs-lookup"><span data-stu-id="cb9a8-111">This feature allows quick remapping of the format if you need to switch to another data entity or XML node with a similar structure.</span></span>
- <span data-ttu-id="cb9a8-112">Modèles de factures financières configurables et prêtes à l'emploi que les clients et les partenaires du monde entier peuvent facilement modifier pour satisfaire aux obligations légales locales.</span><span class="sxs-lookup"><span data-stu-id="cb9a8-112">Out-of-the-box configurable free text invoice templates that customers and partners around the globe can easily modify to meet their local requirements.</span></span>
- <span data-ttu-id="cb9a8-113">Mappage de modèles séparé des documents fiscaux, afin qu'un ensemble de documents fiscaux puisse être partagé par des différentes versions de Finance and Operations.</span><span class="sxs-lookup"><span data-stu-id="cb9a8-113">Separated model mapping from taxable documents, so that one set of taxable documents can be shared by different Finance and Operations versions.</span></span>
- <span data-ttu-id="cb9a8-114">Il est possible d'activer la configuration de la devise de taxe par des recherches sur la composante de taxe dans les documents fiscaux.</span><span class="sxs-lookup"><span data-stu-id="cb9a8-114">Enable configuring tax currency by lookups on the tax component in tax documents.</span></span> <span data-ttu-id="cb9a8-115">Ceci est utile pour les entreprises ayant plusieurs immatriculations fiscales dans différents pays.</span><span class="sxs-lookup"><span data-stu-id="cb9a8-115">This is useful for companies with multiple tax registrations in different countries.</span></span> <span data-ttu-id="cb9a8-116">Cela permet d'utiliser différentes devises pour les taxes utilisées dans différents pays.</span><span class="sxs-lookup"><span data-stu-id="cb9a8-116">This enables the use of different currencies for taxes that are used in different countries.</span></span>
- <span data-ttu-id="cb9a8-117">Calculateur d'équations linéaires pour le calcul des taxes.</span><span class="sxs-lookup"><span data-stu-id="cb9a8-117">Linear equations solver for tax calculation.</span></span> <span data-ttu-id="cb9a8-118">Cela nécessite que les utilisateurs créent des formules de calcul des taxes avec des équations linéaires.</span><span class="sxs-lookup"><span data-stu-id="cb9a8-118">This requires users to create tax calculation formulas with linear equations.</span></span> <span data-ttu-id="cb9a8-119">Le résultat apportera des améliorations aux performances de calcul des taxes.</span><span class="sxs-lookup"><span data-stu-id="cb9a8-119">The result will be performance improvements in tax calculation.</span></span>
- <span data-ttu-id="cb9a8-120">Activation de la configuration de la visibilité des mesures fiscales dans les documents fiscaux.</span><span class="sxs-lookup"><span data-stu-id="cb9a8-120">Enable configuring the visibility of tax measures in tax documents.</span></span> <span data-ttu-id="cb9a8-121">Les formules de taxe peuvent utiliser des mesures fiscales intermédiaires qui ne doivent pas nécessairement être affichées sur la page des documents fiscaux de Dynamics 365 Finance and Operations. Il est donc possible de masquer ces mesures fiscales.</span><span class="sxs-lookup"><span data-stu-id="cb9a8-121">Tax formulas may use some intermediate tax measures that do not need to be shown on the Tax document page in Dynamics 365 Finance and Operations, so it is possible to hide these tax measures.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="cb9a8-122">![Configuration de la visibilité des mesures fiscales dans les documents fiscaux](../../media/Configure-tax-measure-visibility.png)</span><span class="sxs-lookup"><span data-stu-id="cb9a8-122">![Configure the visibility of tax measures in tax documents](../../media/Configure-tax-measure-visibility.png)</span></span>

