---
title: Erstellen von Gruppen in Intune for Education
titleSuffix: Intune for Education
description: Informationen Sie zum Verwalten von Geräten mit Intune for Education.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: doueby
ms.date: 10/08/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468
searchScope:
- IntuneEDU
ms.openlocfilehash: dc0daff52ab3d0348b7cb0fb9256c6cf480def6b
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62147473"
---
# <a name="troubleshooting-group-actions"></a><span data-ttu-id="936f9-103">Problembehandlung für Gruppenaktionen</span><span class="sxs-lookup"><span data-stu-id="936f9-103">Troubleshooting group actions</span></span>

<span data-ttu-id="936f9-104">Dieser Artikel beantwortet häufige gestellte Fragen zu erstellen und Bearbeiten von Gruppen in Intune for Education.</span><span class="sxs-lookup"><span data-stu-id="936f9-104">This article answers common questions about creating and editing groups in Intune for Education.</span></span>

## <a name="why-cant-i-edit-the-default-groups"></a><span data-ttu-id="936f9-105">Warum kann ich die Standardgruppen nicht bearbeiten?</span><span class="sxs-lookup"><span data-stu-id="936f9-105">Why can't I edit the default groups?</span></span>

<span data-ttu-id="936f9-106">Zum Zeitpunkt, die Sie Ihr Konto zu erstellen, erstellt Intune for Education einen Satz von Standardgruppen, auf Mandantenebene.</span><span class="sxs-lookup"><span data-stu-id="936f9-106">At the time that you create your account, Intune for Education creates a set of default, tenant-level groups.</span></span> <span data-ttu-id="936f9-107">Diese Gruppen&ndash;**alle Benutzer** und **alle Geräte**&ndash;kann nicht geändert werden.</span><span class="sxs-lookup"><span data-stu-id="936f9-107">These groups&ndash;**All Users** and **All Devices**&ndash;can't be changed.</span></span> <span data-ttu-id="936f9-108">Nach dem Importieren Ihrer Schule und Lehrer Einträge von School Data Sync, erstellt Intune zusätzlicher Gruppen mit dem Namen **alle Lehrer** und **aller Schüler und Studenten**.</span><span class="sxs-lookup"><span data-stu-id="936f9-108">After you import your school and teacher records from School Data Sync, Intune creates additional groups, called **All Teachers** and **All Students**.</span></span> <span data-ttu-id="936f9-109">Diese Gruppen können nicht geändert werden.</span><span class="sxs-lookup"><span data-stu-id="936f9-109">These groups can't be changed either.</span></span>

<span data-ttu-id="936f9-110">In seltenen Fällen können es sich mit der gleichen Untergruppe unter zwei Gruppen kommen.</span><span class="sxs-lookup"><span data-stu-id="936f9-110">In rare situations, you might end up with the same subgroup underneath two groups.</span></span> <span data-ttu-id="936f9-111">Wenn dieses Problem auftritt, verschieben Sie eine der Gruppen der obersten Ebene über die Untergruppe ".</span><span class="sxs-lookup"><span data-stu-id="936f9-111">If this problem occurs, move one of the top-level groups above the subgroup.</span></span>

## <a name="why-cant-i-edit-dynamic-groups"></a><span data-ttu-id="936f9-112">Warum kann ich dynamische Gruppen nicht bearbeiten?</span><span class="sxs-lookup"><span data-stu-id="936f9-112">Why can't I edit dynamic groups?</span></span>

<span data-ttu-id="936f9-113">Intune for Education ermöglicht Sie eine Teilmenge von dynamischen Attribute in der vollständigen Intune-Verwaltungsportal auswählen.</span><span class="sxs-lookup"><span data-stu-id="936f9-113">Intune for Education lets you pick from a subset of dynamic attributes in Intune's full management portal.</span></span> <span data-ttu-id="936f9-114">Wenn das Attribut, das Sie bearbeiten möchten nicht in Intune for Education-Portals angezeigt wird, müssen Sie sie in Intune im Azure-Portal oder Azure Active Directory bearbeiten.</span><span class="sxs-lookup"><span data-stu-id="936f9-114">If the attribute that you want to edit is not visible in the Intune for Education portal, you must edit it in Intune in the Azure portal or Azure Active Directory.</span></span>

## <a name="why-cant-i-edit-a-specific-group"></a><span data-ttu-id="936f9-115">Warum kann ich eine bestimmte Gruppe nicht bearbeiten?</span><span class="sxs-lookup"><span data-stu-id="936f9-115">Why can't I edit a specific group?</span></span>  

<span data-ttu-id="936f9-116">Intune for Education dient eine einfache Möglichkeit zum Verwalten von Geräten in Ihrer Schulen sollen.</span><span class="sxs-lookup"><span data-stu-id="936f9-116">Intune for Education is designed to be an easy way to manage devices in your schools.</span></span> <span data-ttu-id="936f9-117">Er verwendet [Intune im Azure-Portal](https://docs.microsoft.com/intune/what-is-intune)&ndash;ein Produkt für Unternehmen&ndash;zum Verwalten von apps und Gruppen.</span><span class="sxs-lookup"><span data-stu-id="936f9-117">It uses [Intune in the Azure portal](https://docs.microsoft.com/intune/what-is-intune)&ndash;an enterprise product&ndash;to manage apps and groups.</span></span> <span data-ttu-id="936f9-118">Bestimmte Administratoren in Ihrer Organisation über die Berechtigung, Intune im Azure-Portal und Intune for Education zu verwenden, um besonderen Gruppen zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="936f9-118">Certain admins in your organization have permission to use both Intune in the Azure portal and Intune for Education to create special groups.</span></span> <span data-ttu-id="936f9-119">Wenn Sie eine Gruppe nicht bearbeiten können, ist es wahrscheinlich, dass es in Intune im Azure-Portal erstellt wurde, und Sie keine Berechtigungen zum Ändern der Gruppe besitzen.</span><span class="sxs-lookup"><span data-stu-id="936f9-119">If you can't edit a group, it's likely that it was created in Intune in the Azure portal, and you don't have permissions to modify the group.</span></span>  
