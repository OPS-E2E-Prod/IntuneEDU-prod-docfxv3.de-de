---
title: Delegieren von Administratorberechtigungen für Gruppen
titleSuffix: Intune for Education
description: Erfahren Sie, wie Sie Rollen für die Gruppen in Intune for Education verwalten.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 06/20/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 9319be2e-cb7e-43c1-98fe-64281c8c09fd
searchScope:
- IntuneEDU
ms.openlocfilehash: 6538520b0364b6ecf4b7ec45d57a465d49907778
ms.sourcegitcommit: c766ef357fb0257951f4e35f6ec6f53d63de811e
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/20/2019
ms.locfileid: "67285182"
---
# <a name="delegate-admin-permissions-to-groups"></a><span data-ttu-id="0fb8b-103">Delegieren von Administratorberechtigungen für Gruppen</span><span class="sxs-lookup"><span data-stu-id="0fb8b-103">Delegate admin permissions to groups</span></span>
<span data-ttu-id="0fb8b-104">Sie und Ihre IT-Mitarbeiter verwalten mehrere Gruppen von Schüler/Studenten, Lehrkräfte und Administratoren in Ihrer Schule/Universität.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-104">You and your IT staff manage multiple groups of students, teachers, and administrators throughout your school.</span></span>  

<span data-ttu-id="0fb8b-105">Im Gegensatz zu IT-Mitarbeiter verwalten Administratorgruppen nur die Gruppen, die Sie ihnen zuweisen.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-105">Unlike IT staff, admin groups only manage the groups you assign to them.</span></span> <span data-ttu-id="0fb8b-106">Wenn Sie über Administratorberechtigungen für eine Gruppe von qualifizierten Personen gestatten, können Sie unbefugte oder versehentliche Änderungen zu verringern.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-106">When you give admin permissions to a group of qualified individuals, you help reduce the risk of unauthorized or accidental changes.</span></span>  

## <a name="group-admin-permissions"></a><span data-ttu-id="0fb8b-107">Administratorberechtigungen für die Gruppe</span><span class="sxs-lookup"><span data-stu-id="0fb8b-107">Group admin permissions</span></span> 

<span data-ttu-id="0fb8b-108">Gruppenadministratoren werden in Intune for Education zugewiesen, und es über die Berechtigung zum School-Geräte und apps zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-108">Group admins are assigned in Intune for Education and have permission to manage school devices and apps.</span></span> <span data-ttu-id="0fb8b-109">Gruppenadministratoren können Aktionen ausführen:</span><span class="sxs-lookup"><span data-stu-id="0fb8b-109">Group admins can:</span></span>  

- <span data-ttu-id="0fb8b-110">Anzeigen von Informationen zu Geräten, Benutzern und apps.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-110">View information about devices, users, and apps.</span></span>
- <span data-ttu-id="0fb8b-111">Weisen Sie zu, erstellen Sie, löschen Sie, zeigen Sie an und aktualisieren Sie der Einstellungen für Geräte und Benutzer.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-111">Assign, create, delete, view, and update device and user settings.</span></span>
- <span data-ttu-id="0fb8b-112">Zuweisen, erstellen, löschen, anzeigen und Aktualisieren von apps.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-112">Assign, create, delete, view, and update apps.</span></span>
- <span data-ttu-id="0fb8b-113">Anzeigen von Berichten.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-113">View reports.</span></span>
- <span data-ttu-id="0fb8b-114">Aktionen Sie remote für Geräte, einschließlich der auf die werkseitigen Standardeinstellungen zurücksetzen, Neustarten, einem entsperrten Gerät sperren und eine Synchronisierung zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-114">Take remote actions on devices, including resetting to factory settings, rebooting, locking an unlocked device, and forcing a sync.</span></span>  
- <span data-ttu-id="0fb8b-115">Erstellen Sie, löschen Sie, zeigen Sie an und aktualisieren Sie den iOS MDM-Push-Zertifikat, den iOS MDM-Server-Token und die iOS-VPP-Token.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-115">Create, delete, view, and update the iOS MDM Push Certificate, iOS MDM server tokens, and iOS VPP tokens.</span></span>   

> [!TIP]
> <span data-ttu-id="0fb8b-116">Ändern von Administratorberechtigungen ist eine komplexe Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-116">Modifying admin permissions is an advanced task.</span></span> <span data-ttu-id="0fb8b-117">Wenn Sie die Berechtigungen ändern oder einen benutzerdefinierten Satz von Berechtigungen erstellen möchten, müssen Sie zum wechseln [erleben Sie die vollständige Verwaltung in Intune](https://docs.microsoft.com/intune/role-based-access-control).</span><span class="sxs-lookup"><span data-stu-id="0fb8b-117">If you want to change the permissions or create a custom set of permissions, then you need to go to [the full management experience in Intune](https://docs.microsoft.com/intune/role-based-access-control).</span></span> <span data-ttu-id="0fb8b-118">Diese Berechtigungen umfassen, die in Intune integrierten schuladministratorrolle.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-118">These permissions comprise the built-in School Administrator role in Intune.</span></span> 

## <a name="assign-an-admin-group"></a><span data-ttu-id="0fb8b-119">Weisen Sie eine Administratorengruppe</span><span class="sxs-lookup"><span data-stu-id="0fb8b-119">Assign an admin group</span></span>

1. <span data-ttu-id="0fb8b-120">Intune for Education-Dashboard, klicken Sie auf **Gruppen**.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-120">From the Intune for Education dashboard, click **Groups**.</span></span>
2. <span data-ttu-id="0fb8b-121">Wählen Sie eine Gruppe aus.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-121">Choose a group.</span></span> <span data-ttu-id="0fb8b-122">Diese Gruppe werden die, die Ihre Administratoren zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-122">This group will be the one your admins manage.</span></span>
3. <span data-ttu-id="0fb8b-123">Klicken Sie auf die **Administratoren** Registerkarte > **fügen Administratoren**.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-123">Click the **Admins** tab > **Add Admins**.</span></span>
4. <span data-ttu-id="0fb8b-124">Wählen Sie eine Gruppe aus, um ihr Administrator eine Zugriffsberechtigung für das Verwalten von apps und Einstellungen zu geben.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-124">Choose a group to give it admin permission to manage apps and settings.</span></span>
5. <span data-ttu-id="0fb8b-125">Klicken Sie auf **auswählen Gruppe**.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-125">Click **Choose group**.</span></span>

## <a name="remove-an-admin-group"></a><span data-ttu-id="0fb8b-126">Entfernen einer Administratorengruppe</span><span class="sxs-lookup"><span data-stu-id="0fb8b-126">Remove an admin group</span></span>
1. <span data-ttu-id="0fb8b-127">Intune for Education-Dashboard, klicken Sie auf **Gruppen**.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-127">From the Intune for Education dashboard, click **Groups**.</span></span>
2. <span data-ttu-id="0fb8b-128">Wählen Sie eine Gruppe aus.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-128">Choose a group.</span></span> <span data-ttu-id="0fb8b-129">Diese Gruppe wird sein, die Sie Administratorengruppe aus Verwaltung entfernen.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-129">This group will be the one you remove an admin group from managing.</span></span>
3. <span data-ttu-id="0fb8b-130">Klicken Sie auf die **Administratoren** Registerkarte.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-130">Click the **Admins** tab.</span></span>
4. <span data-ttu-id="0fb8b-131">Wählen Sie eine oder mehrere Gruppen aus der Liste der Administratoren ein.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-131">Select one or more groups from the list of admins.</span></span> <span data-ttu-id="0fb8b-132">Klicken Sie dann auf **Administratoren entfernen**.</span><span class="sxs-lookup"><span data-stu-id="0fb8b-132">Then click **Remove Admins**.</span></span>  
