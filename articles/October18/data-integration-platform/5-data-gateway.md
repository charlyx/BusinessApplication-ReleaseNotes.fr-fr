---
title: "Connectivité hybride de niveau professionnel via la passerelle de données sur site"
description: "Connectivité hybride de niveau professionnel via la passerelle de données sur site"
author: shellyhaverkamp
manager: AnnBe
ms.date: 8/16/2018
ms.assetid: 5b0c45ea-97e4-4e6f-8555-f2bc05ccb336
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: tpalmer
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: a1561a448e7906d9509fc41293ac499a4722f458
ms.openlocfilehash: 29480860b839d38f18ef16541c9f2c3a45c0dff3
ms.contentlocale: fr-fr
ms.lasthandoff: 08/16/2018

---
#  <a name="enterprise-grade-hybrid-connectivity-using-the-on-premises-data-gateway"></a>Connectivité hybride de niveau professionnel via la passerelle de données sur site


[!include[banner](../../includes/banner.md)]

Cette version comprend plusieurs mises à jour visant à amélioration la passerelle de données sur site.

## <a name="certified-custom-connectors-in-power-bi-desktop"></a>Connecteurs personnalisés certifiés dans Power BI Desktop

En début d'année, nous avons annoncé la prise en charge de connecteurs personnalisés dans Power BI Desktop, en utilisant des fonctionnalités puissantes de langage M permettant aux partenaires d'écrire leurs propres connecteurs et de les distribuer à chaque utilisateur Power BI.

La prise en charge des connecteurs personnalisés dans la passerelle permet aux utilisateurs d'avoir leurs états générés avec des connecteurs personnalisés tenus à jour dans le service Power BI en actualisant les données via la passerelle de données sur site.

![Prise en charge des connecteurs personnalisés dans la passerelle de données sur site](media/custom-connectors-support-premises-data-gateway-1.jpg "Prise en charge des connecteurs personnalisés dans la passerelle de données sur site")

## <a name="gateway-multi-geo-support-for-power-bi-premium"></a>Prise en charge de la passerelle dans plusieurs régions pour Power BI Premium
En raison d'un changement des priorités, le délai prévu pour cette fonctionnalité n'a pas été déterminé. L'examen de cette prise en charge se poursuivant, donnez votre avis sur cette suggestion sur https://ideas.powerbi.com afin d'aider à établir un ordre de priorité.

## <a name="guarantee-high-availability-of-gateways-via-clustering"></a>Garantie de haute disponibilité des passerelles à l'aide du clustering
Les fonctionnalités de haute disponibilité dans la passerelle de données sur site que nous avons lancées en novembre 2017 passent de la version préliminaire publique à la disponibilité générale. Dans le cadre de cet effort, plusieurs améliorations de l'expérience ont été apportées, en particulier une meilleure génération de rapports d'erreurs et une expérience utilisateur améliorée.

## <a name="improved-kerberos-single-sign-on-support"></a>Amélioration de la prise en charge de l'authentification unique Kerberos
Nous envisageons de prendre en charge plusieurs domaines dans notre mise en œuvre de l'authentification unique, ainsi que de faciliter les tests de connexion SSO et les diagnostics des problèmes.

![Amélioration de la prise en charge de l'authentification unique Kerberos](media/improved-kerberos-single-sign-support-premises-data-gateway-1.png "Amélioration de la prise en charge de l'authentification unique Kerberos")

## <a name="saml-based-single-sign-on-for-supported-data-sources"></a>Authentification unique SAML des sources de données prises en charge

L'an dernier, nous avons ajouté la prise en charge de l'authentification unique Kerberos à la passerelle pour plusieurs sources, notamment SQL Server, SAP HANA et Teradata.

Pour cette période, nous envisageons de continuer d'investir dans la prise en charge de l'authentification unique en ajoutant des scénarios d'authentification unique SAML pour les sources de données prises en charge.

<a name="additional-cloud-data-refresh-capabilities-for-parity-with-pbi-desktop"></a>  
## <a name="additional-cloud-data-refresh-capabilities-for-parity-with-power-bi-desktop"></a>Fonctionnalités supplémentaires d'actualisation de données cloud pour la parité avec Power BI Desktop

Il existe des situations où un jeu de données Power BI peut s'actualiser sans problème dans Power BI Desktop mais échoue à s'actualiser dans le service Power BI. Cela se produit généralement en raison des paramètres de confidentialité des différentes sources de données utilisées dans ce jeu de données.

Dans Power BI Desktop, les utilisateurs peuvent modifier les paramètres de confidentialité de chaque source de données, ce qui permet l'actualisation du jeu de données. Nous prévoyons de permettre aux utilisateurs d'actualiser avec succès ces jeux de données dans le service Power BI.

<a name="improved-data-sources-settings-experience"></a>  
## <a name="improved-data-source-settings-experience"></a>Amélioration de l'expérience avec les paramètres de source de données

Nous prévoyons d'améliorer l'expérience de création de sources de données sur la page « Gérer les passerelles » du service Power BI en ajoutant certaines fonctionnalités les plus demandées, notamment la possibilité d'ignorer l'étape du test de connexion, de renommer des sources de données et de créer plusieurs sources de données avec des informations d'identification distinctes.

## <a name="tenant-level-administration-of-on-premises-data-gateway"></a>Administration au niveau du client de la passerelle de données sur site
Nous prévoyons d'ajouter à l'attention des administrateurs de client la fonctionnalité de gérer toutes les passerelles de données sur site dans leur client grâce à une API et à l'interface utilisateur.

## <a name="basic-traffic-load-balancing-in-the-on-premises-data-gateway"></a>Équilibrage de charge du trafic de base dans la passerelle de données sur site
Nous prévoyons de fournir la possibilité de fractionner le trafic des demandes pour un cluster de passerelle donné entre toutes les passerelles de ce cluster.
L'administrateur de passerelle pourra activer et désactiver cette fonctionnalité en fonction des besoins de son organisation.

