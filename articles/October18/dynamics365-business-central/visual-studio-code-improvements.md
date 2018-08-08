---
title: "Amélioration de l'expérience avec le langage AL dans Visual Studio Code"
description: "Améliorations apportées à l'expérience avec le langage AL dans Visual Studio Code"
author: pborring
manager: edupont04
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: pborring
audience: developer, customizer
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 161da5108c31c88f8e0f254abcf0f4b0fa6e950c
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---

# <a name="improved-visual-studio-code-al-experience"></a>Amélioration de l'expérience avec le langage AL dans Visual Studio Code

[!include[banner](../../includes/banner.md)]

La création d'extensions permet de personnaliser Business Central. La version d'octobre 2018 apporte des améliorations en termes de productivité à l'expérience de développement, ainsi que la prise en charge de scénarios d'extension supplémentaires.

Avec les améliorations apportées aux outils et aux fonctionnalités d'extension, les développeurs peuvent être plus productifs lors du développement et de la résolution de solutions, et bénéficient d'options supplémentaires pour répondre aux besoins des clients en matière de personnalisation à l'aide d'extensions.

## <a name="sandbox-with-production-data"></a>Bac à sable (sandbox) avec données de production
Un scénario courant lorsque vous utilisez des bacs à sable (sandbox), notamment lors de tests ou de résolution problèmes, consiste à souhaiter disposer de données de production. Avec cette version, nous ajoutons la possibilité de créer un bac à sable (sandbox) basé sur une copie de la dernière sauvegarde sur le cloud des données de production. Pour réduire l'interférence avec des intégrations installées dans les données de production, ces intégrations seront désactivées lors de la création du bac à sable (sandbox). En faisant preuve de prudence, les utilisateurs administrateurs peuvent activer ou reconfigurer ces intégrations au besoin pour prendre en charge l'utilisation du bac à sable (sandbox) prévue.

## <a name="new-object-extensions"></a>Nouvelles extensions d'objet
Vous pouvez désormais effectuer des extensions comme suit :

- Effectuer des énumérations (options) depuis l'application de base ainsi que créer des énumérations extensibles dans vos extensions.
- Jeux de données d'états dans les extensions. Les dispositions des données d'états sont toujours une histoire de remplacement.
- Groupes de champs.

## <a name="event-discoverability"></a>Détectabilité des événements
Un des aspects fondamentaux dans la création d'extensions consiste à s'abonner aux événements. Toutefois, il est compliqué de savoir quels événements sont disponibles dans un flux d'utilisateur donné. Le débogage peut être utile, mais il affiche uniquement les événements auxquels les utilisateurs sont déjà abonnés. Pour simplifier la détectabilité des événements et des points d'extension, un nouveau traceur d'événements est disponible dans le client. Celui-ci permet d'enregistrer un flux d'utilisateur pour répertorier les événements déclenchés, et le développeur peut obtenir le code d'abonné de l'événement généré afin de le copier facilement dans le code AL.

> [!div class="mx-imgBorder"]
> ![Traceur d'événements](media/Event-tracer.png "Traceur d'événements")

En outre, un grand nombre de nouveaux événements a été ajouté, ce qui permet d'effectuer des extensions à des emplacements supplémentaires.

## <a name="visual-studio-code-al-extension-enhancements"></a>Améliorations des extensions AL de Visual Studio Code
Avec la vérification et la rétrocompatibilité des versions, vous pouvez désormais installer l'extension AL Language du marché Visual Studio Code et l'utiliser pour développer des solutions depuis différentes plateformes, y compris les bacs à sable (sandbox) sur le cloud, la version d'avril 2018 de Business Central, la version d'octobre 2018 de Business Central et les versions à venir. Le compileur vérifie que le client connecté est compatible, et compile par rapport à la plateforme cible définie dans la nouvelle propriété app.json.

En outre, l'extension AL est désormais plus rapide et plus réactive lors de l'utilisation de projets plus volumineux contenant de nombreux fichiers/extensions d'objet.

## <a name="debugger-enhancements"></a>Améliorations du débogueur
Comme dans le débogueur Dynamics NAV hérité, vous pouvez désormais utiliser la fonctionnalité courante Arrêt en cas d'erreur, ainsi que Arrêt en cas d'écriture. Vous pouvez également atteindre la définition dans le code de l'application de base et y définir des points d'arrêt.

> [!div class="mx-imgBorder"]
> ![F12 Atteindre la définition pour le code d'application de base](media/Go-to-definition-F12.gif "F12 Atteindre la définition pour le code d'application de base")

## <a name="intellisense-enhancements"></a>Améliorations IntelliSense
Dans AL, toutes les propriétés, avec aperçu flottant et dans IntelliSense, disposent désormais des liens d'aide qui vous redirigent vers la documentation en ligne connexe. En outre, la documentation relative à la construction de langage AL est générée automatiquement et utilisée à la fois pour la documentation de référence en ligne et IntelliSense, afin qu'elle soit à jour et alignée.

> [!div class="mx-imgBorder"]
> ![Lien d'aide dans IntelliSense](media/Help-link-from-IntelliSense.gif "Lien d'aide dans IntelliSense")

Les suggestions concernant les propriétés d'image dans une extension proposent désormais uniquement celles pouvant être utilisées dans le contexte donné, avec un avertissement pour les images ne pouvant pas être utilisées dans ce contexte, et vous pouvez afficher un aperçu des images lorsque vous utilisez IntelliSense et l'aperçu flottant.

> [!div class="mx-imgBorder"]
> ![Sélectionner et afficher un aperçu des images avec IntelliSense](media/IntelliSense-Preview-Images.gif "Sélectionner et afficher un aperçu des images avec IntelliSense")

## <a name="working-with-permissions"></a>Utilisation des autorisations
Pour simplifier l'utilisation des autorisations, il est désormais possible d'exporter des ensembles d'autorisations depuis l'application, à l'aide du client, et d'importer celles-ci dans l'extension AL de Visual Studio Code. Vous pouvez également générer de nouveaux fichiers d'autorisations pour les objets dans une extension depuis le projet AL de Visual Studio Code.

> [!div class="mx-imgBorder"]
> ![Commande AL de Visual Studio Code pour la génération d'un fichier d'autorisations pour les objets d'extension](media/Permissions-AL-command.png "Commande AL de Visual Studio Code pour la génération d'un fichier d'autorisations pour les objets d'extension")

## <a name="net-interop"></a>.NET Interop
Lorsque vous utilisez des solutions Business Central ciblant les déploiements sur site, vous pouvez désormais ajouter .NET Interop dans le code AL. Notez que cela implique que la solution ne peut pas être déplacée vers le cloud ultérieurement sans remplacer .NET Interop.

> [!div class="mx-imgBorder"]
> ![.NET Interop sur AL local](media/DotNet-interop.png ".NET Interop sur AL local")

## <a name="translation-enhancements"></a>Améliorations de la traduction
De nouvelles informations contextuelles décrivant l'objet et l'élément auxquels une chaîne donnée s'applique ont été ajoutées aux fichiers de traduction XLIFF générées. Cela permet aux traducteurs d'obtenir un meilleure aperçu de l'emplacement auquel une chaîne est affichée dans l'interface utilisateur, ce qui améliore la qualité de la traduction.

> [!div class="mx-imgBorder"]
> ![Indicateur de note de fichier de traduction XLIFF](media/xliff-note.png "Indicateur de note de fichier de traduction XLIFF")

## <a name="odata-bound-actions-in-al"></a>Actions liées à OData dans AL
Il est désormais possible d'indiquer les actions liées à OData dans AL. Un nouvel attribut et un nouveau type d'AL ont été ajoutés pour cela.

```
[ServiceEnabled]
procedure CreateCustomerCopy(var actionContext : WebServiceActionContext)
var
createdCustomerGuid : Guid;
customer : Record Customer;
begin
actionContext.SetObjectType(ObjectType::Page);
actionContext.SetObjectId(Pages::Customer);
actionContext.AddEntityKey(customer.fieldNo(Id), createdCustomerGuid);
actionContext.SetResultCode(WebServiceActionResultCode::Created);
end;
```
<!--
### Who uses this feature
These features are intended for ISV and VAR developers.
## Status
### Availability
Cloud, On-premises
### Regional availability
Globally
-->

## <a name="tell-us-what-you-think"></a>Donnez-nous votre avis
Aidez-nous à améliorer Dynamics 365 Business Central en proposant des idées, en fournissant des suggestions et en offrant des commentaires. Utilisez le forum de Business Central à l'adresse [https://aka.ms/businesscentralfeedback](https://aka.ms/businesscentralfeedback).

