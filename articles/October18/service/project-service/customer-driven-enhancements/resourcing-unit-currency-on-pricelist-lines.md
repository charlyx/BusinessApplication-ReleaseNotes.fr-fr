---
title: "Devise de l'unité d'allocation des ressources sur les lignes de prix du rôle pour le coût"
description: "Les taux des coûts pour la durée d'une ressource peuvent désormais être exprimés dans la devise de l'unité d'allocation des ressources"
author: rumant
manager: shellyhaverkamp
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: rumant
audience: developer, admin, end user, citizen developer, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: a40e2adff4c8ca26094dddb8bcc9bd6f8fadaacb
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
#  <a name="resourcing-unit-currency-on-role-price-lines-for-cost"></a>Devise de l'unité d'allocation des ressources sur les lignes de prix du rôle pour le coût 

[!include[project-service banner](../../../includes/project-service.md)]




Project Service permet uniquement une devise par tarifs, qui est spécifiée dans l'en-tête des tarifs. La ligne de tarifs de la tarification de la ressource dispose de la même devise spécifiée dans l'en-tête des tarifs. Toutefois, pour les sociétés de service de projet internationales ayant une tarification centralisée pour toutes leurs divisions réparties dans différents pays, cela peut nécessiter la configuration de nombreuses données pour lesquelles elles devront définir séparément des tarifs dans chaque devise dans laquelle elles vendent ou engagent des coûts. 

Avec cette fonctionnalité, Project Service permettra d'établir une devise au niveau de la ligne pour les prix des ressources différant de la devise de l'en-tête de tarifs. La devise dans l'en-tête des tarifs sera utilisée comme valeur par défaut sur les lignes des prix des ressources. Ainsi, les grandes entreprises internationales souhaitant configurer leurs tarifs de manière plus centralisée pourront utiliser un tarif global avec des prix de ressources dans diverses devises. Cela peut également permettre des scénarios où les prix gérés par chaque unité d'allocation des ressources sont réunis en une liste de tarifs principale.

L'utilisation d'une monnaie unique par tarifs continuera de fonctionner, ce qui est utile pour les entreprises permettant une tarification plus centralisée et qui suivent les taux de change des ressources. Cette fonctionnalité peut être personnalisée afin que les prix des ressource sur les tarifs correspondent à la devise dans l'en-tête de tarifs.

![Tarifs des coûts avec des lignes de tarifs dans plusieurs devises](media/Resourcing-unit-currency-on-pricelist.png "Tarifs des coûts avec des lignes de tarifs dans plusieurs devises")
<!-- Picture 2 -->

