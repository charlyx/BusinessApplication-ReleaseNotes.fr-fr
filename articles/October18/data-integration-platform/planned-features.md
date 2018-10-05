---
title: "Nouveautés dans l'intégration de données"
description: "Obtenez un résumé des nouveautés dans l'intégration de données pour la version d'octobre 2018 de vos applications de gestion Microsoft."
author: shellyhaverkamp
manager: AnnBe
ms.date: 9/7/2018
ms.assetid: 7326561e-192f-4897-ad72-af64d29849da
ms.topic: summary
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: tpalmer
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 7e0954b5f4a23af4780aa48b1b609c68fc7ae6e3
ms.openlocfilehash: 571d4025b4fe454cc95c9c2b2e7bbaf91cd5f656
ms.contentlocale: fr-fr
ms.lasthandoff: 09/20/2018

---
#  <a name="summary-of-whats-new-in-data-integration"></a>Résumé des nouveautés dans l'intégration de données

Les améliorations apportées à cette fonctionnalité de plateforme permettent une connectivité plus riche aux services et applications Microsoft et tiers.

(Ces notes de publication décrivent des fonctionnalités qui n'ont peut-être pas encore été publiées. Les délais de livraison peuvent changer et la fonctionnalité prévue peut ne pas être lancée (voir [Stratégie de Microsoft](https://go.microsoft.com/fwlink/p/?linkid=2007332)).
    
Pour obtenir la liste des régions dans lesquelles les applications de gestion Dynamics 365 sont disponibles, consultez le [Guide de disponibilité internationale](https://aka.ms/dynamics_365_international_availability_deck). 

|**Produit** | **Fonctionnalités**| **Type de version** | **Date**|
|---------|-----------------------------------|---------|---------|
| Power BI | [Connecteurs nouveaux et améliorés](1-power-query.md#enterprise-grade-connectors)<br> * Prise en charge complète du protocole OData v4 <br> * Connecteur HDInsight Spark <br> * Connecteur Google BigQuery <br><br> * SAP HANA   <br>   - Prise en charge de la validation de certificat SSL dans le service Power BI (via la passerelle)   <br>   - [Authentification unique basée sur SAML](5-data-gateway.md#saml-based-single-sign-on-for-supported-data-sources) (y compris Power BI Desktop et la passerelle) <br><br> * SAP BW   <br>   - Améliorations des performances   <br>   - Métadonnées DirectQuery supplémentaires (propriétés, devise, unités de mesure)   <br>   - Certification   <br>   - Authentification unique dans Power BI Desktop + le service Power BI (via la passerelle) <br><br> * Connecteur (non HDInsight) Spark <br> * Authentification unique dans Power BI Desktop + le service Power BI (via la passerelle) <br> * Améliorations du connecteur HTML (extraction de données par exemple)  | Disponibilité générale | Octobre 2018 |
| Power BI | [Prise en charge des connecteurs personnalisés certifiés dans l'expérience Obtenir les données](1-power-query.md#certified-custom-connectors-in-power-bi-desktop) | Disponibilité générale | Octobre 2018 |
| Power BI | Documentation de développement du connecteur personnalisé améliorée avec du contenu pour les développeurs ODBC | Disponibilité générale | Octobre 2018 |
| Power BI | [Nouveau connecteur PDF](1-power-query.md#enterprise-grade-connectors)| Disponibilité générale | Décembre 2018 |
| Power BI | [Transformation « Fusion approximative »](1-power-query.md#new-power-query-data-preparation-capabilities) | Version préliminaire publique | Octobre 2018 |
| Power BI | [Connecteurs nouveaux et améliorés](1-power-query.md#enterprise-grade-connectors) <br> * Connecteur AtScale <br> * Connecteur Essbase <br> * IBM DB2 DirectQuery <br> * Vertica dans le service PBI (via la passerelle) <br> * HDInsight Interactive Query dans le service PBI (via la passerelle) | Version préliminaire publique | Octobre 2018 |
| Power BI | Connecteur AtScale (préversion privée sur invitation - octobre 2018)* | Version préliminaire publique* | Janvier 2019* |
| Power BI | Connecteur Essbase (préversion privée sur invitation - décembre 2018)* | Version préliminaire publique* | Mars 2019* |
| Passerelle de données sur site | [Prise en charge des connecteurs personnalisés dans la passerelle familiale et d'entreprise](5-data-gateway.md#certified-custom-connectors-in-power-bi-desktop) | Disponibilité générale | Octobre 2018 |
| Passerelle de données sur site | [Garantie de haute disponibilité des passerelles à l'aide du clustering](5-data-gateway.md#guarantee-high-availability-of-gateways-via-clustering) | Disponibilité générale | Octobre 2018 |
| Passerelle de données sur site | [Amélioration de la prise en charge de l'authentification unique Kerberos](5-data-gateway.md#improved-kerberos-single-sign-on-support) | Disponibilité générale | Octobre 2018 |
| Passerelle de données sur site | [Fonctionnalités de sources de données supplémentaires existant dans Power BI Desktop](5-data-gateway.md#additional-cloud-data-refresh-capabilities-for-parity-with-pbi-desktop) | Disponibilité générale | Octobre 2018 |
| Passerelle de données sur site | [Amélioration de l'expérience avec les paramètres des sources de données](5-data-gateway.md#improved-data-sources-settings-experience) | Disponibilité générale | Octobre 2018 |
| Passerelle de données sur site | [Possibilité de gérer toutes les passerelles du client dans le portail d'administration D365*](5-data-gateway.md#tenant-level-administration-of-on-premises-data-gateway) | Disponibilité générale* | Décembre 2018* |
| Passerelle de données sur site | [Équilibrage de charge du trafic dans la passerelle de données sur site](5-data-gateway.md#basic-traffic-load-balancing-in-the-on-premises-data-gateway) | Version préliminaire publique | Octobre 2018 |
| Flux de données CDS pour les applications et Power BI | Prise en charge de l'actualisation planifiée pour les projets d'intégration de données dans le portail des créateurs PowerApps | Disponibilité générale | Octobre 2018 |
| Flux de données CDS pour les applications et Power BI | RGPD (possibilité d'exporter les données utilisateur, d'auditer toutes les opérations CRUD d'un utilisateur, document DPIA) | Disponibilité générale | Octobre 2018 |
| Flux de données CDS pour les applications et Power BI | Améliorations pour les administrateurs de l'intégrateur de données <br> * Nouvelle expérience dans le centre d'administration de plateforme d'entreprise <br> * Possibilité de créer des tickets de support depuis le portail d'administration <br> * Amélioration de la vérification des enregistrements d'historique (pagination dans l'historique d'exécution) | Disponibilité générale | Octobre 2018 |
| Flux de données CDS pour les applications et Power BI | Prise en charge du téléchargement de fichiers dans le cadre des expériences avec les connecteurs de fichiers | Version préliminaire publique | Octobre 2018 |
| Flux de données CDS pour les applications et Power BI | Possibilité d'accéder aux stockages de fichiers basés sur le cloud (OneDrive Entreprise, OneDrive Famille, sites d'équipe SharePoint) | Version préliminaire publique | Octobre 2018 |
| Flux de données CDS pour les applications et Power BI | Prise en charge des principaux connecteurs relationnels professionnels (y compris Oracle database, la base de données IBM DB2 et PostgreSQL)| Version préliminaire publique | Octobre 2018 |
| Flux de données CDS pour les applications et Power BI | Prise en charge des transformations de données intégrées à un lac | Version préliminaire publique | Octobre 2018 |
| Flux de données CDS pour les applications et Power BI | Modèles de fonctionnalités nouveaux et améliorés <br> * Nouveau modèle Salesforce permettant d'importer des données dans CDS pour les applications et les flux de données Power BI <br> * Nouveaux modèles d'intégration de données supplémentaires <br> * Amélioration de la possibilité de personnaliser des modèles (création de projet vide sans sélectionner de modèle existant) <br> * Prise en charge de la gestion des versions <br> * Validation de la ou des solutions sources ou de destination<br> * Possibilité de créer un projet DI à partir des modèles publiés sur le marché (depuis DI ou le marché) <br> * Partage de modèles entre les clients et au sein des clients | Version préliminaire publique | Octobre 2018 |
| Flux de données CDS pour les applications et Power BI | Expérience d'installation centralisée pour DI (empêcher le basculement entre les portails créateur/administrateur) | Version préliminaire publique | Octobre 2018 |
| Flux de données CDS pour les applications et Power BI | Améliorations des performances, y compris parallélisme des données et du traitement par lot | Version préliminaire publique | Octobre 2018 |
| Flux de données CDS pour les applications et Power BI | Possibilité d'annuler une exécution en cours | Version préliminaire publique | Octobre 2018 |
| Flux de données CDS pour les applications et Power BI | Amélioration de la documentation, notamment le guide des modèles courants (solutions aux problèmes courants) et les directives sur l'évolutivité | Version préliminaire publique | Octobre 2018 |
| Flux de données CDS pour les applications et Power BI | Possibilité de partager des projets dans le client | Version préliminaire publique | Octobre 2018 |
| Flux de données CDS pour les applications et Power BI | Tableau de bord enrichi avec des aperçus essentiels provenant des données d'intégration et des statistiques supplémentaires associées à l'intégration | Version préliminaire publique | Octobre 2018 |
| Flux de données CDS pour les applications et Power BI | Création automatique de relations entre les entités via l'intégration de données lorsque les entités source sont liées | Version préliminaire publique | Octobre 2018 |
| Microsoft Flow et PowerApps | Utilisation d'exemples de données dans les déclencheurs pour les principaux connecteurs | Disponibilité générale | Octobre 2018 |
| Microsoft Flow et PowerApps | Connecteurs améliorés <br> * Oracle Database (disponibilité générale) <br> * MQ (disponibilité générale) <br> * Prise en charge de clés intégrées pour Microsoft Translator, Recherche Bing et Bing Maps | Disponibilité générale | Octobre 2018 |
| Microsoft Flow et PowerApps | Prise en charge de nouvelles zones : <br> * Brésil | Disponibilité générale | Octobre 2018 |
| Microsoft Flow et PowerApps | Prise en charge de nouvelles zones : <br> * Gouvernement des États-Unis (GCC) | Version préliminaire publique* | Novembre 2018* |
| Microsoft Flow et PowerApps | Connecteurs nouveaux et améliorés <br> * Oracle Database <br> * Prise en charge des procédures stockées <br> * Prise en charge des vues matérialisées <br> * Azure SQL Data Warehouse <br> * Prise en charge des opérations d'écriture <br> * Excel Online <br> * Prise en charge des opérations de mise à jour | Version préliminaire publique | Octobre 2018 |
| Microsoft Flow et PowerApps | Prise en charge des modèles de stratégie dans les connecteurs personnalisés | Version préliminaire publique | Octobre 2018 |
| Microsoft Flow et PowerApps | [Prise en charge de Power Query pour remettre en forme des données dans Microsoft Flow (avec le connecteur SQL Server)](1-power-query.md#flow-support-for-data-filtering--mashup) | Version préliminaire publique | Octobre 2018 |
| Power Query | [Lancement du site web de la communauté](1-power-query.md#power-query-community-website) | Disponibilité générale | Octobre 2018 |
| Power Query | [Fonctionnalités de profilage de données pour identifier facilement les erreurs et les valeurs hors norme dans le cadre de la charge de travail de préparation des données](1-power-query.md#new-power-query-data-preparation-capabilities) | Version préliminaire publique | Octobre 2018 |
| Power Query | [Prise en charge d'IntelliSense pour le langage M](1-power-query.md#intellisense-support-for-the-m-formula-language) | Version préliminaire publique | Octobre 2018 |
| Extensibilité de la plateforme du connecteur | [Programme de certification de connecteur consolidé destiné aux partenaires pour certifier et lancer des connecteurs pour tous les produits de la plateforme (Power BI, Microsoft Flow, PowerApps et CDS)](3-connector-ecosystem.md#unified-connector-certification-program)| Disponibilité générale | Octobre 2018 |
| Extensibilité de la plateforme du connecteur | [Prise en charge des connecteurs personnalisés à l'aide du kit de développement logiciel Power Query](3-connector-ecosystem.md#improved-development-for-connectors-across-the-platform) | Disponibilité générale | Octobre 2018 |
| Extensibilité de la plateforme du connecteur | [Amélioration des outils de développement et de validation pour les connecteurs basés sur le langage M, OpenAPI et OData](3-connector-ecosystem.md#improved-development-for-connectors-across-the-platform) | Version préliminaire publique | Octobre 2018 |
| Common Data Model | [Référentiel GitHub CDM où les définitions d'entité sont en open source avec de la documentation et des outils supplémentaires](2-cdm.md)  | Disponibilité générale | Octobre 2018 |
| Common Data Model | [Amélioration de la documentation CDM expliquant la proposition de valeur et fournissant des conseils d'usage pour créer des extensions](2-cdm.md#docs)  | Disponibilité générale | Octobre 2018 |
| Common Data Model | [Explorateur d'entité Common Data Model graphique et interactif, avec des améliorations GitHub CDM](2-cdm.md#explorer) | Disponibilité générale | Octobre 2018 |
| Common Data Model | [Packs d'entités CDM d'origine pour les solutions métier comme le secteur médical, les services financiers et la vente au détail](2-cdm.md#industry) | Version préliminaire publique | Octobre 2018 |
| Common Data Model | [Définitions d'entités CDM supplémentaires couvrant des scénarios essentiels d'offres Dynamics populaires incluant Finance, Operations et Marketing](2-cdm.md#dynamics) | Version préliminaire publique | Octobre 2018 |

Légende :  
* Ces dates ont été mises à jour depuis la publication précédente des notes de publication.  
** Le type de version (version préliminaire publique ou disponibilité générale) de ces éléments a été incorrectement indiqué et a été mis à jour.  
*** Il s'agit de nouvelles fonctionnalités dont le lancement est prévu pour octobre.  

Éléments supprimés de cette liste :  

|Fonctionnalité | Motif |
|-----|--------------------------|
| Prise en charge des connecteurs personnalisés (via la passerelle) dans CDS pour les applications et les flux de données Power BI <br> (initialement prévue en Version préliminaire publique en octobre 2018) | L'examen de la prise en charge de cette fonctionnalité est toujours en cours ; nous ne connaissons pas encore la chronologie exacte de sa prise en charge. Donnez votre avis sur cette suggestion sur [Idées PowerApps](https://powerusers.microsoft.com/t5/PowerApps-Ideas/idb-p/PowerAppsIdeas) et/ou [Idées Power BI](https://ideas.powerbi.com) afin d'aider à établir un ordre de priorité. |
| Prise en charge de passerelle avec Power BI Premium dans différentes régions de capacité <br> (initialement prévue en Disponibilité générale en octobre 2018)| En raison d'un changement des priorités, le délai prévu pour cette fonctionnalité n'a pas été déterminé. L'examen de cette prise en charge se poursuivant, donnez votre avis sur cette suggestion sur https://ideas.powerbi.com afin d'aider à établir un ordre de priorité.| 

