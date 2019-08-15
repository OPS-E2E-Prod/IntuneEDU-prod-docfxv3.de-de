---
title: Importieren von Schul-/ unidatensätzen mit School Data Sync
titleSuffix: Intune for Education
description: Verwendet Datensynchronisierung von Schul-/ UNI-Gruppen und Benutzer in Azure AD zu importieren.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: f9cb6daf-a789-427b-bbfd-fa0a3d36e01f
searchScope:
- IntuneEDU
ms.openlocfilehash: ec80e1b8f8d2851814227420b5026dd3c488277c
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146560"
---
# <a name="microsoft-school-data-sync-and-intune-for-education"></a><span data-ttu-id="75bd4-103">Microsoft School Data Sync und Intune for Education</span><span class="sxs-lookup"><span data-stu-id="75bd4-103">Microsoft School Data Sync and Intune for Education</span></span>

<span data-ttu-id="75bd4-104">Gruppenrichtlinien-Verwaltungskonsole (Microsoft School Data Sync, SDS) ist ein kostenloser Dienst in Office 365 Education, mit denen Schul-/ unidatensätzen aus Ihrem vorhandenen für Schüler und Studenten Studenteninformationssystem (SIS) importiert werden.</span><span class="sxs-lookup"><span data-stu-id="75bd4-104">Microsoft School Data Sync (SDS) is a free service in Office 365 Education that imports school records from your existing Student Information System (SIS).</span></span> <span data-ttu-id="75bd4-105">Es erstellt online Classrooms und Gruppen für Microsoft Teams, Intune für Bildungseinrichtungen und Drittanbieter-Anwendungen.</span><span class="sxs-lookup"><span data-stu-id="75bd4-105">It creates online classrooms and groups for Microsoft Teams, Intune for Education, and third-party applications.</span></span>  

<span data-ttu-id="75bd4-106">Wechseln Sie in der Dokumentation School Data Sync [erfahren, wie Sie die Bereitstellung von SDS](https://support.office.com/article/Overview-of-School-Data-Sync-and-Classroom-f3d1147b-4ade-4905-8518-508e729f2e91).</span><span class="sxs-lookup"><span data-stu-id="75bd4-106">Go to the School Data Sync documentation to [learn how to deploy SDS](https://support.office.com/article/Overview-of-School-Data-Sync-and-Classroom-f3d1147b-4ade-4905-8518-508e729f2e91).</span></span> 

## <a name="create-groups-from-school-roster"></a><span data-ttu-id="75bd4-107">Erstellen von Gruppen aus der Liste der "School"</span><span class="sxs-lookup"><span data-stu-id="75bd4-107">Create groups from school roster</span></span>
<span data-ttu-id="75bd4-108">SDS erstellt Kopien der Daten aus dem SIS und speichert sie in Azure Active Directory (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="75bd4-108">SDS creates copies of the information from your SIS, and stores it in Azure Active Directory (Azure AD).</span></span> <span data-ttu-id="75bd4-109">SDS erstellt zwei Gruppen in Intune for Education, die auf dem Sie Einstellungen und apps anwenden können:</span><span class="sxs-lookup"><span data-stu-id="75bd4-109">SDS creates two groups in Intune for Education to which you can apply settings and apps:</span></span>

* <span data-ttu-id="75bd4-110">Alle Schüler/Studenten</span><span class="sxs-lookup"><span data-stu-id="75bd4-110">All Students</span></span>
* <span data-ttu-id="75bd4-111">Alle Lehrer</span><span class="sxs-lookup"><span data-stu-id="75bd4-111">All Teachers</span></span>

<span data-ttu-id="75bd4-112">Weitere Informationen zum Erstellen von Gruppen in Intune for Education finden Sie unter [Erstellen von Gruppen](create-groups.md).</span><span class="sxs-lookup"><span data-stu-id="75bd4-112">For more information about creating groups in Intune for Education, see [Create groups](create-groups.md).</span></span>  

## <a name="set-up-dynamic-group-properties"></a><span data-ttu-id="75bd4-113">Richten Sie dynamischen Gruppe-Eigenschaften</span><span class="sxs-lookup"><span data-stu-id="75bd4-113">Set up dynamic group properties</span></span>
<span data-ttu-id="75bd4-114">Beim Importieren von Informationen über Schüler aus dem SIS in Intune for Education mit School Data Sync, schließen Sie die folgenden Eigenschaften:</span><span class="sxs-lookup"><span data-stu-id="75bd4-114">When importing student information from your SIS into Intune for Education with School Data Sync, include the following properties:</span></span>
*  <span data-ttu-id="75bd4-115">Auf Unternehmensniveau</span><span class="sxs-lookup"><span data-stu-id="75bd4-115">Grade</span></span> 
*  <span data-ttu-id="75bd4-116">Abschlussjahr</span><span class="sxs-lookup"><span data-stu-id="75bd4-116">Graduation Year</span></span>  

<span data-ttu-id="75bd4-117">Diese Eigenschaften sind erforderlich, um erstellen [dynamische Gruppe](create-groups.md#dynamic-groups) Regeln für Schüler/Studenten in Intune for Education-Portals.</span><span class="sxs-lookup"><span data-stu-id="75bd4-117">These properties are necessary to create [dynamic group](create-groups.md#dynamic-groups) rules for students in the Intune for Education portal.</span></span>  <span data-ttu-id="75bd4-118">Eigenschaften aus der SDS-app konfiguriert ist, und finden Sie im __für Schüler und Studenten Optionen__ > __wählen Sie für Schüler und Studenten Eigenschaften__.</span><span class="sxs-lookup"><span data-stu-id="75bd4-118">Properties are configured from the SDS app, and are found in  __Student options__ > __Select student properties__.</span></span>

## <a name="what-is-azure-ad"></a><span data-ttu-id="75bd4-119">Was ist Azure AD?</span><span class="sxs-lookup"><span data-stu-id="75bd4-119">What is Azure AD?</span></span>
<span data-ttu-id="75bd4-120">Azure AD ist ein Microsoft-Verwaltungssystem, die in Intune integriert und unterstützt Sie beim Organisieren, Schüler/Studenten und Geräte.</span><span class="sxs-lookup"><span data-stu-id="75bd4-120">Azure AD is a Microsoft management system that integrates with Intune and helps organize students and devices.</span></span> <span data-ttu-id="75bd4-121">Sie können z. B. Erstellen von Gruppen aus Ihrer Schüler/Studenten und Lehrkräfte, *4. Zeitraum Biologie* oder *Contoso Bezirk Lehrer*.</span><span class="sxs-lookup"><span data-stu-id="75bd4-121">It lets you create groups out of your students and teachers, such as *4th period Biology* or *Contoso District teachers*.</span></span> <span data-ttu-id="75bd4-122">Gruppen sind erforderlich, um die Verteilung und Benutzer- oder gerätespezifische apps, Einstellungen und Einschränkungen.</span><span class="sxs-lookup"><span data-stu-id="75bd4-122">Groups are necessary to assign and distribute user or device-specific apps, settings, and restrictions.</span></span>

## <a name="next-steps"></a><span data-ttu-id="75bd4-123">Nächste Schritte</span><span class="sxs-lookup"><span data-stu-id="75bd4-123">Next steps</span></span>   
<span data-ttu-id="75bd4-124">Nachdem Ihre Studenten und Lehrkräften Informationen für Intune for Education synchronisiert ist, beginnen Sie mit der express-Konfiguration für [Windows](edu-express-config-settings-windows.md) oder [iOS](edu-express-config-settings-ios.md) Geräte.</span><span class="sxs-lookup"><span data-stu-id="75bd4-124">After your student and teacher information is synced with Intune for Education, get started with express configuration for [Windows](edu-express-config-settings-windows.md) or [iOS](edu-express-config-settings-ios.md) devices.</span></span>  

<span data-ttu-id="75bd4-125">Möchten Sie mehr über Microsoft School Data Sync zu erfahren?</span><span class="sxs-lookup"><span data-stu-id="75bd4-125">Want to know more about Microsoft School Data Sync?</span></span> <span data-ttu-id="75bd4-126">Besuchen Sie die [Microsoft School Data Sync-Seite](https://sds.microsoft.com) Produktinformationen.</span><span class="sxs-lookup"><span data-stu-id="75bd4-126">Visit the [Microsoft School Data Sync page](https://sds.microsoft.com) for product information.</span></span> 
