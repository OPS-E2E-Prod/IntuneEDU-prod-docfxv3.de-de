---
title: Prüfungsprofile
titleSuffix: Intune for Education
description: Informationen Sie zum Verwenden von nehmen ein Test Profile zu verwalten und Testergebnisse für Schüler und Studenten zu erfassen.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 3ad65b15-015a-402e-9dd5-0748dee79459
searchScope:
- IntuneEDU
ms.openlocfilehash: 18c4e4db1bfe3a5759058d5e4b3cc90945097146
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62147528"
---
# <a name="add-a-take-a-test-profile-in-intune-for-education"></a><span data-ttu-id="183e0-103">Ein Prüfungsprofil wird in Intune for Education hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="183e0-103">Add a Take a Test profile in Intune for Education</span></span>

<span data-ttu-id="183e0-104">Die Take a Test-app können Sie sichere online Tests für Ihren Classroom des Windows 10-Geräte zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="183e0-104">The Take a Test app lets you securely administer online tests on your classroom's Windows 10 devices.</span></span>  <span data-ttu-id="183e0-105">Schüler/Studenten verwenden Sie die Anmeldeinformationen, die Sie für diese Anmeldung für das Testprofil bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="183e0-105">Students use the credentials you provide for them to sign in to the test profile.</span></span> <span data-ttu-id="183e0-106">Klicken Sie dann auf diese die bewertungs-URL, um den Test zu starten.</span><span class="sxs-lookup"><span data-stu-id="183e0-106">Then they click the assessment URL to launch the test.</span></span> 
 
<span data-ttu-id="183e0-107">In diesem Artikel wird beschrieben, wie Sie:</span><span class="sxs-lookup"><span data-stu-id="183e0-107">This article describes how to:</span></span>
* <span data-ttu-id="183e0-108">Ein Prüfungsprofil ein Testprofil zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="183e0-108">Create a Take a Test profile.</span></span>
* <span data-ttu-id="183e0-109">Weisen Sie das Profil für Schüler/Studenten in Ihrer Schule/Universität.</span><span class="sxs-lookup"><span data-stu-id="183e0-109">Assign the profile to students in your school.</span></span>  

> [!NOTE]
> <span data-ttu-id="183e0-110">Erstellen Sie einen exklusive Benutzer für Take eine Testzwecke.</span><span class="sxs-lookup"><span data-stu-id="183e0-110">Create an exclusive user for Take a Test purposes.</span></span> <span data-ttu-id="183e0-111">Sehen Sie ein Testprofil diesem Benutzer weisen Sie zu, damit Sie Student oder Lehrkraft Geräten keine Auswirkung auf.</span><span class="sxs-lookup"><span data-stu-id="183e0-111">Assign your Take a Test profile to this user so that you don't impact student or teacher devices.</span></span> <span data-ttu-id="183e0-112">Informationen zum Zuweisen eines Benutzers in der Windows 10 Education, [einrichten Take a Test auf mehreren PCs](https://technet.microsoft.com/edu/windows/take-a-test-multiple-pcs) Artikel.</span><span class="sxs-lookup"><span data-stu-id="183e0-112">Learn how to assign a user in the Windows 10 for Education, [Set up Take a Test on multiple PCs](https://technet.microsoft.com/edu/windows/take-a-test-multiple-pcs) article.</span></span>

## <a name="take-a-test-features"></a><span data-ttu-id="183e0-113">Nehmen Sie eine Testfunktionen</span><span class="sxs-lookup"><span data-stu-id="183e0-113">Take a Test features</span></span>
<span data-ttu-id="183e0-114">Wenn ein Schüler/Student einen Test gestartet wird, sperrt der Desktop.</span><span class="sxs-lookup"><span data-stu-id="183e0-114">When a student launches a test, their desktop locks.</span></span> <span data-ttu-id="183e0-115">Der dauert, wird eine Test-app in einem neuen Fenster geöffnet.</span><span class="sxs-lookup"><span data-stu-id="183e0-115">The Take a Test app opens in a new window.</span></span> <span data-ttu-id="183e0-116">Take a Test hebt die Systemvariable Zwischenablage, sodass Schüler/Studenten können nicht Inhalt kopieren und einfügen.</span><span class="sxs-lookup"><span data-stu-id="183e0-116">Take a Test clears the system's clipboard so that students can't copy and paste content.</span></span>

<span data-ttu-id="183e0-117">Während ein Tests aktiv ist, können Sie Test-Teilnehmer nicht:</span><span class="sxs-lookup"><span data-stu-id="183e0-117">While a test is active, test takers cannot:</span></span>

* <span data-ttu-id="183e0-118">Besuchen Sie die anderen Websites.</span><span class="sxs-lookup"><span data-stu-id="183e0-118">Visit other websites.</span></span>
* <span data-ttu-id="183e0-119">Öffnen oder auf andere apps zugreifen.</span><span class="sxs-lookup"><span data-stu-id="183e0-119">Open or access other apps.</span></span>
* <span data-ttu-id="183e0-120">Ändern Sie Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="183e0-120">Change settings.</span></span>
* <span data-ttu-id="183e0-121">Erweitern Sie die Anzeige.</span><span class="sxs-lookup"><span data-stu-id="183e0-121">Extend the display.</span></span>  
* <span data-ttu-id="183e0-122">Benachrichtigungen angezeigt.</span><span class="sxs-lookup"><span data-stu-id="183e0-122">See notifications.</span></span>
* <span data-ttu-id="183e0-123">Erhalten Sie die app und Betriebssystemupdates.</span><span class="sxs-lookup"><span data-stu-id="183e0-123">Receive app and OS updates.</span></span>
* <span data-ttu-id="183e0-124">Textvorschläge zu empfangen.</span><span class="sxs-lookup"><span data-stu-id="183e0-124">Receive text suggestions.</span></span>
* <span data-ttu-id="183e0-125">Verwenden Sie Cortana.</span><span class="sxs-lookup"><span data-stu-id="183e0-125">Use Cortana.</span></span>
* <span data-ttu-id="183e0-126">Freigeben, drucken oder Aufzeichnen von Bildschirmen, Gerät, es sei denn, die von Geschäfts-, Schul- oder IT-Administrator zugelassen.</span><span class="sxs-lookup"><span data-stu-id="183e0-126">Share, print, or record device screens, unless allowed by school or IT administrator.</span></span>

### <a name="how-is-assistive-technology-affected"></a><span data-ttu-id="183e0-127">Wie ist die hilfstechnologien betroffen?</span><span class="sxs-lookup"><span data-stu-id="183e0-127">How is assistive technology affected?</span></span>
<span data-ttu-id="183e0-128">Einige Gerätefunktionen – z. B. die Sprachausgabe – und andere hilfstechnologien sind beim Erstellen eines Tests weiterhin voll funktionsfähig.</span><span class="sxs-lookup"><span data-stu-id="183e0-128">Some device features--such as narrator--and other assistive technology are still fully functional while taking a test.</span></span> <span data-ttu-id="183e0-129">Eine Liste der apps-Features, finden Sie unter [nehmen Sie eine technische Referenz für Test-app](https://docs.microsoft.com/education/windows/take-a-test-app-technical).</span><span class="sxs-lookup"><span data-stu-id="183e0-129">For a list of the apps features, see [Take a Test app technical reference](https://docs.microsoft.com/education/windows/take-a-test-app-technical).</span></span>


## <a name="take-a-test-profile-setup"></a><span data-ttu-id="183e0-130">Nehmen Sie ein Profil testeinrichtung</span><span class="sxs-lookup"><span data-stu-id="183e0-130">Take a Test profile setup</span></span>
<span data-ttu-id="183e0-131">Richten Sie ein Profil in Intune for Education.</span><span class="sxs-lookup"><span data-stu-id="183e0-131">Set up a profile in Intune for Education.</span></span> <span data-ttu-id="183e0-132">Bevor Sie beginnen, empfehlen wir, dass Sie ein dediziertes Benutzerkonto, das ausschließlich für Bewertungen verwendet erstellen.</span><span class="sxs-lookup"><span data-stu-id="183e0-132">Before you begin, we recommend that you create a dedicated user account used solely for assessments.</span></span> <span data-ttu-id="183e0-133">Benutzer werden mit diesem Konto melden Sie sich auf Tests.</span><span class="sxs-lookup"><span data-stu-id="183e0-133">Users will sign in to this account to access tests.</span></span> 

1. <span data-ttu-id="183e0-134">Intune for Education-Dashboard, klicken Sie auf **Prüfungsprofile**.</span><span class="sxs-lookup"><span data-stu-id="183e0-134">From Intune for Education dashboard, click **Take a Test profiles**.</span></span>    
<span data-ttu-id="183e0-135">![Liste der Optionen in der Randleiste](./media/dashboard-002-left-sidebar-list.png)</span><span class="sxs-lookup"><span data-stu-id="183e0-135">![List of options in the sidebar](./media/dashboard-002-left-sidebar-list.png)</span></span>  
2.  <span data-ttu-id="183e0-136">Klicken Sie Prüfungsprofil Hinzufügen eines Testprofils.</span><span class="sxs-lookup"><span data-stu-id="183e0-136">Click Add Take a Test profile.</span></span>  
 ![Hinzufügen einer Schaltfläche "Profil nehmen ein Test" in der linken Seite auswählen](./media/takeatest-001-new-profile.png)  
3. <span data-ttu-id="183e0-138">Geben Sie einen beschreibenden Namen für den Test aus.</span><span class="sxs-lookup"><span data-stu-id="183e0-138">Enter a descriptive name for the test.</span></span>  
<span data-ttu-id="183e0-139">4 Geben Sie die Bewertungs-URL ein.</span><span class="sxs-lookup"><span data-stu-id="183e0-139">4 Enter the Assessment URL.</span></span>  
 ![Nehmen Sie ein Profil Testfenster](./media/takeatest-002-new-profile-edit-window.png)  
5. <span data-ttu-id="183e0-141">Konfigurieren Sie den Rest der testeinstellungen:</span><span class="sxs-lookup"><span data-stu-id="183e0-141">Configure the rest of the test settings:</span></span>    
    <span data-ttu-id="183e0-142">a.</span><span class="sxs-lookup"><span data-stu-id="183e0-142">a.</span></span> <span data-ttu-id="183e0-143">Bildschirmaufnahme zulassen</span><span class="sxs-lookup"><span data-stu-id="183e0-143">Allow screen capture</span></span>  
    <span data-ttu-id="183e0-144">b.</span><span class="sxs-lookup"><span data-stu-id="183e0-144">b.</span></span> <span data-ttu-id="183e0-145">Erfordern von PCs mit der Installation eines Druckers</span><span class="sxs-lookup"><span data-stu-id="183e0-145">Require PCs to have a printer installed</span></span>  
    <span data-ttu-id="183e0-146">c.</span><span class="sxs-lookup"><span data-stu-id="183e0-146">c.</span></span> <span data-ttu-id="183e0-147">Textvorschläge zulassen</span><span class="sxs-lookup"><span data-stu-id="183e0-147">Allow text suggestions</span></span>   
6. <span data-ttu-id="183e0-148">Wählen Sie ein Konto aus der Liste mit den vorhandenen Benutzern.</span><span class="sxs-lookup"><span data-stu-id="183e0-148">Select an account from your list of existing users.</span></span> <span data-ttu-id="183e0-149">Schüler/Studenten werden Benutzernamen und das Kennwort des Kontos zur Anmeldung bei der entsprechenden Bewertung verwenden.</span><span class="sxs-lookup"><span data-stu-id="183e0-149">Students will use the account's username and password to sign in to the appropriate assessment.</span></span>  

<span data-ttu-id="183e0-150">Um die Details zu einem Profil anzuzeigen, wählen Sie sie aus der linken Seite der Seite aus.</span><span class="sxs-lookup"><span data-stu-id="183e0-150">To view the details of any profile, select it from the left side of the page.</span></span> <span data-ttu-id="183e0-151">Klicken Sie dann auf die **Konto** Registerkarte.</span><span class="sxs-lookup"><span data-stu-id="183e0-151">Then click the **Account** tab.</span></span>  

## <a name="assign-or-change-groups"></a><span data-ttu-id="183e0-152">Zuweisen oder Ändern von Gruppen</span><span class="sxs-lookup"><span data-stu-id="183e0-152">Assign or change groups</span></span>
<span data-ttu-id="183e0-153">Zuweisen von Gruppen der Schüler/Studenten, die Zugriff auf das Testprofil benötigen.</span><span class="sxs-lookup"><span data-stu-id="183e0-153">Assign groups of students that require access to the test profile.</span></span> <span data-ttu-id="183e0-154">Um die Änderungen zu zu gruppenzuweisungen vornehmen, gehen Sie wie folgt vor.</span><span class="sxs-lookup"><span data-stu-id="183e0-154">Follow these steps to make edits to group assignments too.</span></span>
1. <span data-ttu-id="183e0-155">Von der **Prüfungsprofile** klicken Sie auf die **Gruppen** Registerkarte.</span><span class="sxs-lookup"><span data-stu-id="183e0-155">From the **Take a Test profiles** page, click the **Groups** tab.</span></span> 
2. <span data-ttu-id="183e0-156">Klicken Sie auf **gruppenzuweisungen ändern**.</span><span class="sxs-lookup"><span data-stu-id="183e0-156">Click **Change group assignments**.</span></span> 
3. <span data-ttu-id="183e0-157">Wählen Sie eine oder mehrere Gruppen von der **alle Gruppen** Menü.</span><span class="sxs-lookup"><span data-stu-id="183e0-157">Select one or more groups from the **All Groups** menu.</span></span> <span data-ttu-id="183e0-158">Klicken Sie dann auf **Gruppen hinzufügen**.</span><span class="sxs-lookup"><span data-stu-id="183e0-158">Then click **Add Groups**.</span></span> 
4. <span data-ttu-id="183e0-159">Um eine Gruppe aus der Zuordnung zu entfernen, wählen Sie die Gruppe aus der **zugewiesene Gruppen** Menü.</span><span class="sxs-lookup"><span data-stu-id="183e0-159">To remove a group from the assignment, select the group from the **Groups assigned** menu.</span></span> <span data-ttu-id="183e0-160">Klicken Sie dann auf **Gruppen entfernen**.</span><span class="sxs-lookup"><span data-stu-id="183e0-160">Then click **Remove Groups**.</span></span>
5. <span data-ttu-id="183e0-161">Klicken Sie auf **Ok** um Ihre Änderungen zu übernehmen.</span><span class="sxs-lookup"><span data-stu-id="183e0-161">Click **Ok** to submit your changes.</span></span>

## <a name="delete-take-a-test-profile"></a><span data-ttu-id="183e0-162">Prüfungsprofil löschen</span><span class="sxs-lookup"><span data-stu-id="183e0-162">Delete Take a Test profile</span></span>  
<span data-ttu-id="183e0-163">Wenn Sie ein Prüfungsprofil löschen, wird es ein typisches Benutzerkonto an.</span><span class="sxs-lookup"><span data-stu-id="183e0-163">When you delete a Take a Test profile, it becomes a typical user account.</span></span> <span data-ttu-id="183e0-164">Schüler und Studenten sind weiterhin auf das Konto mit ihren vorhandenen Anmeldeinformationen anmelden können, aber der URL-Bewertung-Link aus dem Konto entfernt wird.</span><span class="sxs-lookup"><span data-stu-id="183e0-164">Students are still able to sign in to the account with its existing credentials, but the URL assessment link is removed from the account.</span></span> <span data-ttu-id="183e0-165">Anmelden bei dem Konto wird auch nicht mehr für Schüler und Studenten Geräte sperren.</span><span class="sxs-lookup"><span data-stu-id="183e0-165">Signing into the account will also no longer lock student devices.</span></span>

1. <span data-ttu-id="183e0-166">Von der **Prüfungsprofile** Seite, wählen Sie das Profil, das Sie löschen möchten.</span><span class="sxs-lookup"><span data-stu-id="183e0-166">From the **Take a Test profiles** page, choose the profile you want to delete.</span></span>
2. <span data-ttu-id="183e0-167">Klicken Sie auf **löschen Prüfungsprofil**.</span><span class="sxs-lookup"><span data-stu-id="183e0-167">Click **Delete Take a Test profile**.</span></span>
3. <span data-ttu-id="183e0-168">Klicken Sie auf **löschen** Aktion zu bestätigen.</span><span class="sxs-lookup"><span data-stu-id="183e0-168">Click **Delete** to confirm your action.</span></span>

<span data-ttu-id="183e0-169">Weitere Informationen zu akzeptieren einen Test auf Ihren Geräten finden Sie unter [Prüfung in Windows 10-](https://technet.microsoft.com/edu/windows/take-tests-in-windows-10).</span><span class="sxs-lookup"><span data-stu-id="183e0-169">To find out more about Take a Test on your devices, see [Take a Test in Windows 10](https://technet.microsoft.com/edu/windows/take-tests-in-windows-10).</span></span>
