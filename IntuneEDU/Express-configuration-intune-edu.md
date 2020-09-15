---
title: Express-Konfiguration
titleSuffix: Intune for Education
description: Verwenden von Express-Konfiguration zum Einrichten von Gruppen in Intune for Education.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: af5d35ee-84f5-4245-a441-671600bcc376
searchScope:
- IntuneEDU
ms.openlocfilehash: eb3b697973d37d5b4697559b3ba87b64ba9afdb3
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62147323"
---
# <a name="express-configuration-in-intune-for-education"></a>Express-Konfiguration in Intune for Education

  ![Die Express-Konfiguration-Kachel, die besagt, dass "Launch Express-Konfiguration, klicken Sie hier, um apps und Einstellungen für eine Gruppe auszuwählen."](./media/express-config-001-launch-tile.png)

Express-Konfiguration können Sie Einstellungen und apps für Benutzer und Geräte zuweisen. Die Kachel "Start", für die schrittweise exemplarische Vorgehensweise befindet sich auf der Titelseite des der [Intune for Education-Portals](https://intuneeducation.portal.azure.com). 

Wenn Sie durch jeden Schritt klicken, sehen Sie sich, dass die meisten Windows oder iOS-Einstellungen bereits konfiguriert sind. Diese Konfigurationen sind die Standardwerte, und werden als Empfehlungen festgelegt. Empfohlene Betriebssystem-spezifische apps werden auch bereits markiert. Ändern Sie die Standardauswahl für Deine Bildungseinrichtung nach Bedarf. 

Express-Konfiguration wiederherstellen Sie, jedes Mal, wenn Sie Einstellungen oder apps von einer Gruppenstatus ändern möchten. 

## <a name="launch-express-configuration"></a>Express-Konfiguration starten
In diesem Abschnitt wird beschrieben, wie Sie die Schritte im express-Konfiguration. Stellen Sie sicher, dass Sie Ihre Schul-/ unidaten synchronisiert oder Gruppen in Azure AD erstellt haben, rufen Sie optimal von express-Konfiguration. 

1. Melden Sie sich Intune for Education-Portals.
2. Klicken Sie auf dem Dashboard auf **Express-Konfiguration starten**.  

Wenn iOS-Konfigurationen deaktiviert sind, wenn Sie die express-Konfiguration starten:  
1. Wählen Sie aus dem Dashboard **alle** > **iOS-Geräteverwaltung**.
2. Hochladen eines Apple-MDM-Push-Zertifikats an.
3. Registrieren einer [Token von Apple-MDM-Server](setup-ios-device-management.md).

## <a name="choose-a-group-to-configure"></a>Wählen Sie eine Gruppe zu konfigurieren

Einige Gruppen werden erstellt und in Ihre Intune for Education-Abonnement enthalten. Intune for Education füllt die Gruppen mit den Details von Schul-/ unidatensätzen. Diese Gruppen sind:  

 * Alle Geräte  
 * Allen Benutzern  
 
Wenn Sie School Data Sync (SDS) verwenden, um Ihrer Schule Datensätze zu importieren, sehen Sie auch:  

 * Alle Lehrer  
 * Alle Schüler/Studenten  

Intune for Education empfiehlt, beginnen Sie mit der **alle Benutzer** Gruppe. Weisen Sie die Einstellungen, die alle Benutzer benötigen. Beispielsweise sind kennwortanforderungen und Popup Einschränkungen wahrscheinlich für alle Benutzer identisch.

  ![Wählen Sie Gruppe Bildschirmgröße abfragt, eine Gruppe auszuwählen.](./media/express-config-004-choose-group.png)

Klicken Sie auf den Pfeil erweitern/reduzieren, zum Anzeigen oder Ausblenden aller Gruppen. Denken Sie daran: Wenn Sie eine Gruppe der obersten Ebene konfigurieren, deren Untergruppen erben alle zugehörigen Einstellungen.

## <a name="choose-apps"></a>Apps auswählen

Sie können die folgenden app-Typen auf Geräten hinzufügen:
* [Web-Apps](add-web-apps-edu.md)
* Windows 10-apps
    * [Microsoft Office](install-office.md)
    * [Microsoft Store für Bildungseinrichtungen-apps](acquire-store-apps.md)
    * [Desktop-App](add-desktop-apps-edu.md)
* iOS-apps
    * [Kostenlose Apps aus dem iOS-App Store](add-apps-ios.md)
    * [Über ein volumenprogramm erworbenen Program (VPP-apps)](add-vpp-apps-ios.md)

Wählen Sie eine oder mehrere apps zuweisen. Apps werden sofort Ihrer Gruppe zugewiesen werden, nachdem Sie auf **Weiter**.

  ![Bildschirm der app-Zuweisung. Apps sind für die Zuweisung von unterschiedlichen Typen, einschließlich Web-apps und Microsoft Store für Bildungseinrichtungen-apps organisiert.](./media/express-config-005-choose-apps.png)

Intune for Education zeigt auch [beliebte apps aus dem Microsoft Store für Bildungseinrichtungen](add-popular-apps-edu.md) aus auf alle Intune for Education-Benutzer.


## <a name="choose-settings"></a>Wählen Sie die Einstellungen
Express-Konfiguration zeigt allgemeine Einstellungen für Geräte und Benutzer in Intune. Einstellungen werden in betriebssystemspezifischen Kategorien unterteilt: Einstellungen für Windows und iOS-Einstellungen.

Die Standardeinstellungen werden empfohlene Werte voreingestellt. Bleiben Sie bei der Empfehlungen und keine Änderungen vornehmen, klicken Sie auf Wunsch **Weiter**. Einstellungen werden sofort auf Ihre Verwaltungsgruppe angewendet werden. 

  ![Wählen Sie Seite mit den Einstellungen. Einstellungen werden in einer reduzierten Liste, einschließlich der Bereiche wie z. B. die gemeinsame Nutzung von Geräten, grundlegende geräteeinstellungen, app-Einstellungen, Einstellungen für den Browser und mehr organisiert.](./media/express-config-006-choose-settings.png)


Express-Konfiguration-Auswahl jederzeit anpassen Ihrer Schule/Universität Ändern der Richtlinien geändert werden. Weitere Anpassung in Intune for Education, zeigen Sie die vollständige Liste der [Windows 10](all-edu-settings-windows.md) und [iOS](all-edu-settings-ios.md) geräteeinstellungen.

## <a name="review-settings"></a>Überprüfen Sie die Einstellungen

Überprüfen Sie vor dem Speichern Sie Ihre apps und Einstellungen. Klicken Sie auf **wieder** Änderungen vornehmen. Wenn die Überprüfung abgeschlossen ist, klicken Sie auf **speichern**.

 ![Die Überprüfung Ihren Bildschirm für die Auswahl. Apps und Einstellungen, die während der Express-Konfiguration aktiviert werden.](./media/express-config-007-save-changes.png)  

  ![Der letzten Seite. Es zeigt die Schaltfläche "Konfigurieren der Gruppe" und die vollständige Optionen. Die Option für alle fertig bietet eine kurze Erläuterung, was in den Prozess, einschließlich Hinzufügen von Geräten zu Intune for Education belauschen, indem diese mit Azure Active Directory als Nächstes kommt.](./media/express-config-008-all-done.png)

## <a name="next-steps"></a>Nächste Schritte
[Weisen Sie Administratoren für](group-admin-delegate.md) können Sie die Gruppe verwalten Sie gerade erstellt haben. Bearbeiten Sie die Gruppe jederzeit, indem Sie unter neuen Gesichtspunkten express-Konfiguration. Weitere Einstellungen an [finden Sie auf der Registerkarte "Gruppen"](create-groups.md).

