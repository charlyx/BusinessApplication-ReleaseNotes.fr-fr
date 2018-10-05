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
# <a name="embed-power-bi-visualizations"></a>Intégrer les visualisations Power BI

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]

[Power BI](https://powerbi.microsoft.com) est l'un des meilleurs outils pour fournir des aperçus en une visualisation simple et interactive. Avec les fonctionnalités et cas d'utilisation proposés aux utilisateurs, Power BI demeure l'une des idées les plus plébiscitées.

Actuellement, l'intégration sécurisée d'états Power BI dans un portail est une tâche complexe. Cela inclut l'écriture d'une logique personnalisée pour traiter et gérer le jeton de sécurité. Cette fonctionnalité rationalise l'intégration Dynamics 365 Portal et Power BI. 

## <a name="enable-power-bi"></a>Activer Power BI

Les administrateurs pourront configurer et activer Power BI pour un portail. Cela nécessitera une licence Power BI adaptée.

>[!div class="mx-imgBorder"]
>![Activer l'intégration Power BI à partir du Centre d'administration du portail](media/PBI_Admin_Center_EnablePBI.png "Activer l'intégration Power BI à partir du Centre d'administration du portail")

## <a name="add-power-bi-visualization"></a>Ajouter la visualisation Power BI

Les personnalisateurs peuvent utiliser du code Liquid pour inclure des tableaux de bord et des états Power BI dans les pages. Lors de l'intégration du contenu Power BI, les personnalisateurs peuvent utiliser des [paramètres de filtre](https://docs.microsoft.com/power-bi/service-url-filters) pour créer des vues personnalisées. L'indicateur powerbi Liquid intègre les tableaux de bord et les états Power BI dans les pages.

```
{% powerbi path:"https://app.powerbi.com/view?r=eyJrIjoiNjMzZTY1ZTItMDE2My00NGY5LWIwYmItNjUwMGY5NzEY3IiwidCI6IjU3NGMzZTU2LTQ5MjQtNDAwNC1hZDFhLWQ4NDI3ZTdkYjI0MSiOjZ9" %}
```

### <a name="parameters"></a>Paramètres

L'indicateur powerbi accepte les paramètres suivants :

**chemin d'accès**

Chemin d'accès de l'état ou du tableau de bord Power BI. Si l'état ou le tableau de bord Power BI est sécurisé, vous devez fournir le type d'authentification.

**authentication_type**

Type d'authentification requis pour l'état ou le tableau de bord Power BI. Les valeurs valides pour ce paramètre sont **Anonymous** ou **AAD**. La valeur par défaut est **Anonymous**.

Lors de l'ajout de l'état ou du tableau de bord Power BI sécurisé, assurez-vous qu'il est partagé avec les utilisateurs authentifiés de Dynamics 365 Portal Azure Active Directory. 

```
{% powerbi authentication_type:"AAD" path:"https://app.powerbi.com/groups/00000000-0000-0000-0000-000000000000/reports/00000000-0000-0000-0000-000000000001/ReportSectionc01" %}
```

**tileid**

Affiche la vignette spécifiée du tableau de bord. Vous devez fournir l'ID de la vignette.

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

## <a name="wed-like-to-thank"></a>Nous voulons remercier

Merci d'avoir soumis [cette idée](https://experience.dynamics.com/ideas/idea/?ideaid=76fe3c62-62ea-e611-80c1-00155d460d59) avec des votes et des commentaires, cela nous a permis de la traiter en priorité.

