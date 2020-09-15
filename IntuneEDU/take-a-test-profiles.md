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
# <a name="add-a-take-a-test-profile-in-intune-for-education"></a>Ein Prüfungsprofil wird in Intune for Education hinzufügen.

Die Take a Test-app können Sie sichere online Tests für Ihren Classroom des Windows 10-Geräte zu verwalten.  Schüler/Studenten verwenden Sie die Anmeldeinformationen, die Sie für diese Anmeldung für das Testprofil bereitstellen. Klicken Sie dann auf diese die bewertungs-URL, um den Test zu starten. 
 
In diesem Artikel wird beschrieben, wie Sie:
* Ein Prüfungsprofil ein Testprofil zu erstellen.
* Weisen Sie das Profil für Schüler/Studenten in Ihrer Schule/Universität.  

> [!NOTE]
> Erstellen Sie einen exklusive Benutzer für Take eine Testzwecke. Sehen Sie ein Testprofil diesem Benutzer weisen Sie zu, damit Sie Student oder Lehrkraft Geräten keine Auswirkung auf. Informationen zum Zuweisen eines Benutzers in der Windows 10 Education, [einrichten Take a Test auf mehreren PCs](https://technet.microsoft.com/edu/windows/take-a-test-multiple-pcs) Artikel.

## <a name="take-a-test-features"></a>Nehmen Sie eine Testfunktionen
Wenn ein Schüler/Student einen Test gestartet wird, sperrt der Desktop. Der dauert, wird eine Test-app in einem neuen Fenster geöffnet. Take a Test hebt die Systemvariable Zwischenablage, sodass Schüler/Studenten können nicht Inhalt kopieren und einfügen.

Während ein Tests aktiv ist, können Sie Test-Teilnehmer nicht:

* Besuchen Sie die anderen Websites.
* Öffnen oder auf andere apps zugreifen.
* Ändern Sie Einstellungen.
* Erweitern Sie die Anzeige.  
* Benachrichtigungen angezeigt.
* Erhalten Sie die app und Betriebssystemupdates.
* Textvorschläge zu empfangen.
* Verwenden Sie Cortana.
* Freigeben, drucken oder Aufzeichnen von Bildschirmen, Gerät, es sei denn, die von Geschäfts-, Schul- oder IT-Administrator zugelassen.

### <a name="how-is-assistive-technology-affected"></a>Wie ist die hilfstechnologien betroffen?
Einige Gerätefunktionen – z. B. die Sprachausgabe – und andere hilfstechnologien sind beim Erstellen eines Tests weiterhin voll funktionsfähig. Eine Liste der apps-Features, finden Sie unter [nehmen Sie eine technische Referenz für Test-app](https://docs.microsoft.com/education/windows/take-a-test-app-technical).


## <a name="take-a-test-profile-setup"></a>Nehmen Sie ein Profil testeinrichtung
Richten Sie ein Profil in Intune for Education. Bevor Sie beginnen, empfehlen wir, dass Sie ein dediziertes Benutzerkonto, das ausschließlich für Bewertungen verwendet erstellen. Benutzer werden mit diesem Konto melden Sie sich auf Tests. 

1. Intune for Education-Dashboard, klicken Sie auf **Prüfungsprofile**.    
![Liste der Optionen in der Randleiste](./media/dashboard-002-left-sidebar-list.png)  
2.  Klicken Sie Prüfungsprofil Hinzufügen eines Testprofils.  
 ![Hinzufügen einer Schaltfläche "Profil nehmen ein Test" in der linken Seite auswählen](./media/takeatest-001-new-profile.png)  
3. Geben Sie einen beschreibenden Namen für den Test aus.  
4 Geben Sie die Bewertungs-URL ein.  
 ![Nehmen Sie ein Profil Testfenster](./media/takeatest-002-new-profile-edit-window.png)  
5. Konfigurieren Sie den Rest der testeinstellungen:    
    a. Bildschirmaufnahme zulassen  
    b. Erfordern von PCs mit der Installation eines Druckers  
    c. Textvorschläge zulassen   
6. Wählen Sie ein Konto aus der Liste mit den vorhandenen Benutzern. Schüler/Studenten werden Benutzernamen und das Kennwort des Kontos zur Anmeldung bei der entsprechenden Bewertung verwenden.  

Um die Details zu einem Profil anzuzeigen, wählen Sie sie aus der linken Seite der Seite aus. Klicken Sie dann auf die **Konto** Registerkarte.  

## <a name="assign-or-change-groups"></a>Zuweisen oder Ändern von Gruppen
Zuweisen von Gruppen der Schüler/Studenten, die Zugriff auf das Testprofil benötigen. Um die Änderungen zu zu gruppenzuweisungen vornehmen, gehen Sie wie folgt vor.
1. Von der **Prüfungsprofile** klicken Sie auf die **Gruppen** Registerkarte. 
2. Klicken Sie auf **gruppenzuweisungen ändern**. 
3. Wählen Sie eine oder mehrere Gruppen von der **alle Gruppen** Menü. Klicken Sie dann auf **Gruppen hinzufügen**. 
4. Um eine Gruppe aus der Zuordnung zu entfernen, wählen Sie die Gruppe aus der **zugewiesene Gruppen** Menü. Klicken Sie dann auf **Gruppen entfernen**.
5. Klicken Sie auf **Ok** um Ihre Änderungen zu übernehmen.

## <a name="delete-take-a-test-profile"></a>Prüfungsprofil löschen  
Wenn Sie ein Prüfungsprofil löschen, wird es ein typisches Benutzerkonto an. Schüler und Studenten sind weiterhin auf das Konto mit ihren vorhandenen Anmeldeinformationen anmelden können, aber der URL-Bewertung-Link aus dem Konto entfernt wird. Anmelden bei dem Konto wird auch nicht mehr für Schüler und Studenten Geräte sperren.

1. Von der **Prüfungsprofile** Seite, wählen Sie das Profil, das Sie löschen möchten.
2. Klicken Sie auf **löschen Prüfungsprofil**.
3. Klicken Sie auf **löschen** Aktion zu bestätigen.

Weitere Informationen zu akzeptieren einen Test auf Ihren Geräten finden Sie unter [Prüfung in Windows 10-](https://technet.microsoft.com/edu/windows/take-tests-in-windows-10).
