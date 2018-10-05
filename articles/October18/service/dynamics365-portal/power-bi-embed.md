---
title: "Intégrer les visualisations Power BI dans Dynamics 365 Portal"
description: "Intégrez des visualisations Power BI sur les pages de votre portail."
author: neerajnandwana-ms
manager: ramalingamkrishnan
ms.date: 09/06/2018
ms.assetid: e2a02c53-de53-4890-9a21-73cf97965494
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: nenandw
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: b2cbc7080525e92e2e62f653eaaccb0e6c24b33d
ms.openlocfilehash: 68dd102a69ff83d447c451084a755c4c7fe7447e
ms.contentlocale: fr-fr
ms.lasthandoff: 09/11/2018

---
# <a name="embed-power-bi-visualizations"></a><span data-ttu-id="e1f8d-103">Intégrer les visualisations Power BI</span><span class="sxs-lookup"><span data-stu-id="e1f8d-103">Embed Power BI visualizations</span></span>

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]

<span data-ttu-id="e1f8d-104">[Power BI](https://powerbi.microsoft.com) est l'un des meilleurs outils pour fournir des aperçus en une visualisation simple et interactive.</span><span class="sxs-lookup"><span data-stu-id="e1f8d-104">[Power BI](https://powerbi.microsoft.com) is one of the best tools to deliver insights with simple and interactive visualization.</span></span> <span data-ttu-id="e1f8d-105">Avec les fonctionnalités et cas d'utilisation proposés aux utilisateurs, Power BI demeure l'une des idées les plus plébiscitées.</span><span class="sxs-lookup"><span data-stu-id="e1f8d-105">Considering Power BI features and the use cases it enables for portal users, this feature remains one of the top-voted ideas.</span></span>

<span data-ttu-id="e1f8d-106">Actuellement, l'intégration sécurisée d'états Power BI dans un portail est une tâche complexe.</span><span class="sxs-lookup"><span data-stu-id="e1f8d-106">Currently, embedding secure Power BI reports in a portal is a complex task.</span></span> <span data-ttu-id="e1f8d-107">Cela inclut l'écriture d'une logique personnalisée pour traiter et gérer le jeton de sécurité.</span><span class="sxs-lookup"><span data-stu-id="e1f8d-107">It includes writing custom logic to handle and manage security token.</span></span> <span data-ttu-id="e1f8d-108">Cette fonctionnalité rationalise l'intégration Dynamics 365 Portal et Power BI.</span><span class="sxs-lookup"><span data-stu-id="e1f8d-108">This feature streamlines the Dynamics 365 Portal and Power BI integration.</span></span> 

## <a name="enable-power-bi"></a><span data-ttu-id="e1f8d-109">Activer Power BI</span><span class="sxs-lookup"><span data-stu-id="e1f8d-109">Enable Power BI</span></span>

<span data-ttu-id="e1f8d-110">Les administrateurs pourront configurer et activer Power BI pour un portail.</span><span class="sxs-lookup"><span data-stu-id="e1f8d-110">Administrators will be able to configure and enable Power BI for a portal.</span></span> <span data-ttu-id="e1f8d-111">Cela nécessitera une licence Power BI adaptée.</span><span class="sxs-lookup"><span data-stu-id="e1f8d-111">This will require an appropriate Power BI license.</span></span>

>[!div class="mx-imgBorder"]
><span data-ttu-id="e1f8d-112">![Activer l'intégration Power BI à partir du Centre d'administration du portail](media/PBI_Admin_Center_EnablePBI.png "Activer l'intégration Power BI à partir du Centre d'administration du portail")</span><span class="sxs-lookup"><span data-stu-id="e1f8d-112">![Enable Power BI integration from Portal Admin Center](media/PBI_Admin_Center_EnablePBI.png "Enable Power BI integration from Portal Admin Center")</span></span>

## <a name="add-power-bi-visualization"></a><span data-ttu-id="e1f8d-113">Ajouter la visualisation Power BI</span><span class="sxs-lookup"><span data-stu-id="e1f8d-113">Add Power BI visualization</span></span>

<span data-ttu-id="e1f8d-114">Les personnalisateurs peuvent utiliser du code Liquid pour inclure des tableaux de bord et des états Power BI dans les pages.</span><span class="sxs-lookup"><span data-stu-id="e1f8d-114">Customizers can use Liquid code to embed Power BI dashboards and reports within pages.</span></span> <span data-ttu-id="e1f8d-115">Lors de l'intégration du contenu Power BI, les personnalisateurs peuvent utiliser des [paramètres de filtre](https://docs.microsoft.com/power-bi/service-url-filters) pour créer des vues personnalisées.</span><span class="sxs-lookup"><span data-stu-id="e1f8d-115">While embedding the Power BI content, customizers can use [filter parameters](https://docs.microsoft.com/power-bi/service-url-filters) to create personalized views.</span></span> <span data-ttu-id="e1f8d-116">L'indicateur powerbi Liquid intègre les tableaux de bord et les états Power BI dans les pages.</span><span class="sxs-lookup"><span data-stu-id="e1f8d-116">The powerbi Liquid tag embeds the Power BI dashboards and reports within pages.</span></span>

```
{% powerbi path:"https://app.powerbi.com/view?r=eyJrIjoiNjMzZTY1ZTItMDE2My00NGY5LWIwYmItNjUwMGY5NzEY3IiwidCI6IjU3NGMzZTU2LTQ5MjQtNDAwNC1hZDFhLWQ4NDI3ZTdkYjI0MSiOjZ9" %}
```

### <a name="parameters"></a><span data-ttu-id="e1f8d-117">Paramètres</span><span class="sxs-lookup"><span data-stu-id="e1f8d-117">Parameters</span></span>

<span data-ttu-id="e1f8d-118">L'indicateur powerbi accepte les paramètres suivants :</span><span class="sxs-lookup"><span data-stu-id="e1f8d-118">The powerbi tag accepts the following parameters:</span></span>

<span data-ttu-id="e1f8d-119">**chemin d'accès**</span><span class="sxs-lookup"><span data-stu-id="e1f8d-119">**path**</span></span>

<span data-ttu-id="e1f8d-120">Chemin d'accès de l'état ou du tableau de bord Power BI.</span><span class="sxs-lookup"><span data-stu-id="e1f8d-120">Path of the Power BI report or dashboard.</span></span> <span data-ttu-id="e1f8d-121">Si l'état ou le tableau de bord Power BI est sécurisé, vous devez fournir le type d'authentification.</span><span class="sxs-lookup"><span data-stu-id="e1f8d-121">If the Power BI report or dashboard is secure, you must provide the authentication type.</span></span>

<span data-ttu-id="e1f8d-122">**authentication_type**</span><span class="sxs-lookup"><span data-stu-id="e1f8d-122">**authentication_type**</span></span>

<span data-ttu-id="e1f8d-123">Type d'authentification requis pour l'état ou le tableau de bord Power BI.</span><span class="sxs-lookup"><span data-stu-id="e1f8d-123">Type of authentication required for the Power BI report or dashboard.</span></span> <span data-ttu-id="e1f8d-124">Les valeurs valides pour ce paramètre sont **Anonymous** ou **AAD**.</span><span class="sxs-lookup"><span data-stu-id="e1f8d-124">Valid values for this parameter are **Anonymous** or **AAD**.</span></span> <span data-ttu-id="e1f8d-125">La valeur par défaut est **Anonymous**.</span><span class="sxs-lookup"><span data-stu-id="e1f8d-125">The default value is **Anonymous**.</span></span>

<span data-ttu-id="e1f8d-126">Lors de l'ajout de l'état ou du tableau de bord Power BI sécurisé, assurez-vous qu'il est partagé avec les utilisateurs authentifiés de Dynamics 365 Portal Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="e1f8d-126">While adding the secure Power BI report or dashboard, ensure that it is shared with Dynamics 365 Portal Azure Active Directory authenticated users.</span></span> 

```
{% powerbi authentication_type:"AAD" path:"https://app.powerbi.com/groups/00000000-0000-0000-0000-000000000000/reports/00000000-0000-0000-0000-000000000001/ReportSectionc01" %}
```

<span data-ttu-id="e1f8d-127">**tileid**</span><span class="sxs-lookup"><span data-stu-id="e1f8d-127">**tileid**</span></span>

<span data-ttu-id="e1f8d-128">Affiche la vignette spécifiée du tableau de bord.</span><span class="sxs-lookup"><span data-stu-id="e1f8d-128">Displays the specified tile of the dashboard.</span></span> <span data-ttu-id="e1f8d-129">Vous devez fournir l'ID de la vignette.</span><span class="sxs-lookup"><span data-stu-id="e1f8d-129">You must provide the ID of the tile.</span></span>

```
{% powerbi authentication_type:"AAD" path:"https://app.powerbi.com/groups/00000000-0000-0000-0000-000000000000/dashboards/00000000-0000-0000-0000-000000000001" tileid:"0000005" %}
```




<!--
### Who uses this feature
This feature is intended for end users and customizers. A customizer must configure Power BI in a portal to use this feature.
### License required
For Power BI configuration and content authoring, customers or administrators will need an appropriate Power BI license.
### Setup required
This feature must be configured and enabled in a portal by an administrator. 
## Status
### Development status
Generally available
#### Target timeframe
October 2018
### Availability
Cloud
### Regional availability
This feature will be available globally. 
-->

## <a name="wed-like-to-thank"></a><span data-ttu-id="e1f8d-130">Nous voulons remercier</span><span class="sxs-lookup"><span data-stu-id="e1f8d-130">We'd like to thank</span></span>

<span data-ttu-id="e1f8d-131">Merci d'avoir soumis [cette idée](https://experience.dynamics.com/ideas/idea/?ideaid=76fe3c62-62ea-e611-80c1-00155d460d59) avec des votes et des commentaires, cela nous a permis de la traiter en priorité.</span><span class="sxs-lookup"><span data-stu-id="e1f8d-131">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=76fe3c62-62ea-e611-80c1-00155d460d59) with votes and comments that helped us prioritize it.</span></span>

