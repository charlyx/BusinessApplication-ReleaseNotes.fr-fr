---
title: Gestion des documents SharePoint pour les portails
description: Gestion des documents SharePoint pour les portails
author: sandhangitmsft
manager: ramalingamkrishnan
ms.date: 07/22/2018
ms.assetid: aa14cee1-b121-4c02-8937-13e0717e8fb8
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: sandhan
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 318636631f44de9d4991ee0733b502fbed2403fa
ms.contentlocale: fr-fr
ms.lasthandoff: 08/15/2018

---
#  <a name="manage-sharepoint-documents"></a><span data-ttu-id="8ba80-103">Gérer les documents SharePoint</span><span class="sxs-lookup"><span data-stu-id="8ba80-103">Manage SharePoint documents</span></span>

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]




<span data-ttu-id="8ba80-104">Cette fonctionnalité étend les fonctionnalités de gestion des documents des applications Dynamics 365 aux portails, offrant aux clients une expérience cohérente et leur permettant de tirer profit de leurs investissements existants dans SharePoint avec Dynamics 365 pour la gestion des documents.</span><span class="sxs-lookup"><span data-stu-id="8ba80-104">This feature extends document management capabilities of Dynamics 365 applications to portals, providing a consistent experience and allowing customers to leverage their existing investments in SharePoint with Dynamics 365 for document management.</span></span>

<span data-ttu-id="8ba80-105">Les documents associés à des enregistrements d'entité peuvent être gérés par les utilisateurs du portail à mesure qu'ils sont stockés dans une bibliothèque de documents SharePoint, ce qui permet également aux entreprises de tirer parti des fonctionnalités de collaboration transparentes offertes en mode natif par SharePoint.</span><span class="sxs-lookup"><span data-stu-id="8ba80-105">Documents associated with entity records can be managed by portal users as they are stored in a SharePoint document library, thus also enabling businesses to leverage the seamless collaboration capabilities offered natively by SharePoint.</span></span>

<span data-ttu-id="8ba80-106">Les bibliothèques de documents en ligne SharePoint configurées avec des entités dans Dynamics 365 peuvent être utilisées à l'aide d'entités de portail et de formulaires web.</span><span class="sxs-lookup"><span data-stu-id="8ba80-106">SharePoint Online document libraries configured with entities in Dynamics 365 can be surfaced via portal entity and web forms.</span></span> <span data-ttu-id="8ba80-107">Cela permet aux utilisateurs du portail d'exécuter les actions suivantes :</span><span class="sxs-lookup"><span data-stu-id="8ba80-107">This allows portal users to perform the following actions:</span></span>

## <a name="add-documents"></a><span data-ttu-id="8ba80-108">Ajouter des documents</span><span class="sxs-lookup"><span data-stu-id="8ba80-108">Add documents</span></span>

<span data-ttu-id="8ba80-109">![Ajouter des fichiers à un enregistrement de dossier](media/SP_Portal_Add_Files.png "Ajouter des fichiers à un enregistrement de dossier")</span><span class="sxs-lookup"><span data-stu-id="8ba80-109">![Add files to a case record](media/SP_Portal_Add_Files.png "Add files to a case record")</span></span>

## <a name="view-and-download-documents"></a><span data-ttu-id="8ba80-110">Afficher et télécharger des documents</span><span class="sxs-lookup"><span data-stu-id="8ba80-110">View and download documents</span></span>

<span data-ttu-id="8ba80-111">![Afficher des documents associés à un enregistrement de dossier](media/SP_Portal_View_Files.png "Afficher des documents associés à un enregistrement de dossier")</span><span class="sxs-lookup"><span data-stu-id="8ba80-111">![View documents related to case record](media/SP_Portal_View_Files.png "View documents related to case record")</span></span> 

## <a name="create-folder"></a><span data-ttu-id="8ba80-112">Créer un dossier</span><span class="sxs-lookup"><span data-stu-id="8ba80-112">Create folder</span></span>

<span data-ttu-id="8ba80-113">![Créer un sous-dossier dans la liste des documents pour organiser les fichiers](media/SP_Portal_Create_Folder.png "Créer un sous-dossier dans la liste des documents pour organiser les fichiers")</span><span class="sxs-lookup"><span data-stu-id="8ba80-113">![Create subfolder within document list to organize files](media/SP_Portal_Create_Folder.png "Create subfolder within document list to organize files")</span></span>

## <a name="delete-document"></a><span data-ttu-id="8ba80-114">Supprimer un document</span><span class="sxs-lookup"><span data-stu-id="8ba80-114">Delete document</span></span>

<span data-ttu-id="8ba80-115">![Supprimer des fichiers d'un enregistrement de dossier](media/SP_Portal_Delete_File.png "Supprimer des fichiers d'un enregistrement de dossier")</span><span class="sxs-lookup"><span data-stu-id="8ba80-115">![Delete files from a case record](media/SP_Portal_Delete_File.png "Delete files from a case record")</span></span>

<!--
### Who uses this feature
This feature is intended for portal end users, allowing them access to SharePoint documents from portal web pages.
Portal administrators customize the form to display document lists on a portal. Entity permission configuration is used to control actions available to portal end users on files and folders.
### Setup required
This feature requires that document management is set up for [Dynamics 365 with SharePoint Online](https://go.microsoft.com/fwlink/p/?linkid=859386).
-->

## <a name="quick-steps"></a><span data-ttu-id="8ba80-116">Étapes rapides</span><span class="sxs-lookup"><span data-stu-id="8ba80-116">Quick steps</span></span>

### <a name="configuring-document-list-on-entity-forms"></a><span data-ttu-id="8ba80-117">Configuration de la liste des documents sur les formulaires d'entité</span><span class="sxs-lookup"><span data-stu-id="8ba80-117">Configuring document list on entity forms</span></span>

<span data-ttu-id="8ba80-118">![Configurer la sous-grille de la liste de documents sur un formulaire d'entité de dossier](media/SP_Portal_configure_entity_form_doc_location.png "Configuration de la sous-grille d'emplacements de document")</span><span class="sxs-lookup"><span data-stu-id="8ba80-118">![Configure document list subgrid on case entity form](media/SP_Portal_configure_entity_form_doc_location.png "Document location subgrid configuration")</span></span>

### <a name="configuring-permissions-on-document-list"></a><span data-ttu-id="8ba80-119">Configuration des autorisations sur la liste des documents</span><span class="sxs-lookup"><span data-stu-id="8ba80-119">Configuring permissions on document list</span></span>

<span data-ttu-id="8ba80-120">![Configurer les autorisations de la liste des documents](media/SP_Portal_configure_doc_permissions.png "Configurer les autorisations de la liste des documents")</span><span class="sxs-lookup"><span data-stu-id="8ba80-120">![Configure document list permissions](media/SP_Portal_configure_doc_permissions.png "Configure permissions")</span></span>

<span data-ttu-id="8ba80-121">Un modèle basé sur des autorisations permet de contrôler ces actions sur les fichiers et les dossiers pour des scénarios client spécifiques.</span><span class="sxs-lookup"><span data-stu-id="8ba80-121">A permissions-based model allows controlling these actions on files and folders for specific customer scenarios.</span></span>

<!--
## Status
### Development status
Generally available
#### Target timeframe
October 2018
### Availability
Cloud
### Regional availability
Global
-->

## <a name="wed-like-to-thank"></a><span data-ttu-id="8ba80-122">Nous voulons remercier</span><span class="sxs-lookup"><span data-stu-id="8ba80-122">We'd like to thank</span></span>

<span data-ttu-id="8ba80-123">Merci d'avoir soumis [cette idée](https://experience.dynamics.com/ideas/idea/?ideaid=d3398770-f9ac-e611-80c2-00155d4616d6) avec des votes et des commentaires, cela nous a permis de la traiter en priorité.</span><span class="sxs-lookup"><span data-stu-id="8ba80-123">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=d3398770-f9ac-e611-80c2-00155d4616d6) with votes and comments that helped us prioritize it.</span></span>

