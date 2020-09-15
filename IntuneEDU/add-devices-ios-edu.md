---
title: Registrieren von iOS-Geräte in der Verwaltung
titleSuffix: Intune for Education
description: Informationen Sie zum Einrichten von Windows 10-Geräte für Intune for Education.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 05/16/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.openlocfilehash: 944840d0bfaa05fdcb5e099513fc5b7836068f7b
ms.sourcegitcommit: 370c0b29e905c25204a72fd5877000698ac859a9
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/16/2019
ms.locfileid: "65813873"
---
# <a name="enroll-ios-devices-in-intune-for-education"></a>Registrieren von iOS-Geräte in Intune for Education

Geräte sind bereit für einschalten und nach dem in der Verwaltung zu registrieren:

* Einrichten von Intune for Education [mit School Informationen](what-is-school-data-sync.md) – z. B. Studentendatensätze, apps und Einstellungen für Geräte.
* Aktivieren Sie für die Verwaltung von iOS-Geräte von Intune [Einrichten der Apple-MDM Push-Zertifikat und ein Token von Apple-MDM-Server](setup-ios-device-management.md#add-an-mdm-push-certificate).
* [Synchronisieren Sie Ihre Apple-MDM-Server-Token](setup-ios-device-management.md#sync-managed-devices) mit Intune Education und eine Liste der Geräte kann jetzt registrieren.  

> [!NOTE]
> Stellen Sie sicher, dass Ihre Geräte mit dem Internet verbunden sind, und Ihr Konto verfügt, genügend Intune for Education-Gerät-Lizenzen, um das Setup abzuschließen. Erfahren Sie mehr über die Lizenzierung in [Zuweisen von Lizenzen zu Benutzern](https://docs.microsoft.com/intune/get-started/start-with-a-paid-subscription-to-microsoft-intune-step-4).

## <a name="preconfigured-enrollment-profile"></a>Vorkonfigurierte Anmeldungsprofil erstellen  
Intune for Education erstellt und weist jedes synchronisierten Gerät ein Registrierungsprofil für Schule optimiert.  

Registrierungsprofile werden konfiguriert, um dem Gerät mitzuteilen, wie Sie selbst einrichten und registrieren in der Verwaltung. Intune konfiguriert die Einstellungen zum Beschleunigen Ihrer Registrierung.  Wenn Sie auf dem Gerät einschalten, beginnt das Registrierungsprofil sofort die Einrichtung Ihres Geräts.

## <a name="preconfigured-settings"></a>Vorkonfigurierte Einstellungen  
Während der Installation des ersten Gerät Registrieren von Geräten mit den folgenden Konfigurationen:

* Ohne benutzeraffinität
* Im überwachten Modus aktiviert
* Synchronisieren oder Kopplung mit anderen Geräten blockiert
* Gesperrte Registrierung können Benutzer von Bedeutung nicht verwaltungseinstellungen auf ihren Geräten ändern  

Intune for Education gilt ein Benennungsschema für Geräte, die Sie mit einem MDM-Server-Token zu registrieren. Standardmäßig werden die Geräte mit die Seriennummer des Geräts benannt. Sie können auch einen benutzerdefinierten Namen hinzufügen, wenn Sie Ihr MDM-Server-Token einrichten.  

Die folgenden Einstellungen des Setup-Assistenten werden während der Registrierung ausgeblendet:
* Kennung-setup
* Ortungsdienste
* Gerätewiederherstellung
* iCloud und Apple-ID
* Touch ID-Einrichtung
* Apple Pay-setup
* Anzeigeoptionen für Zoom
* Siri-setup
* Optionen des Diagnose-Daten  


Die folgende Einstellung für die Setup-Assistent wird während der Registrierung angezeigt:
* Geschäftsbedingungen

### <a name="what-is-setup-assistant"></a>Was ist die Setup-Assistenten?
Beim ersten, die Sie auf Ihrem Gerät aktivieren Intune für Bildungseinrichtungen der iOS-Out-of-Box-Oberfläche, startet namens *Setup-Assistenten*. Der Setup-Assistent führt Sie durch eine Reihe von Bildschirmen und bereitet Ihr Gerät für die Verwendung des "School".  

## <a name="enroll-a-device"></a>Registrieren eines Geräts

Führen Sie durch die folgenden Schritte aus, um vollständige geräteregistrierung.

1. Schalten Sie Ihr iOS-Gerät ein. 
2. Stellen Sie auf Ihrem Gerät eine WLAN-Verbindung her, nachdem Sie Ihre **Sprache** ausgewählt haben.
3. Auf der **Einrichten der iOS-Gerät** auf Ihre **Land/Region**.
4. Befolgen Sie die Anweisungen auf dem Bildschirm, um automatisch oder manuell für die WLAN-Verbindung ein. Nach dem Sie verbunden sind, die **Konfiguration** angezeigt wird, mit den Registrierungsdetails.  
5. Akzeptieren Sie die **Geschäftsbedingungen**. Klicken Sie dann entscheiden Sie, wenn Sie Diagnoseinformationen an Apple senden möchten.  

## <a name="next-steps"></a>Nächste Schritte
Nun, dass Geräte eingerichtet und einsatzbereit für die Verwendung des "School" festgelegt sind, werden Informationen Sie zum Aktualisieren, überwachen und beheben Sie diese.   
* Fügen Sie weitere [kostenlose](add-apps-ios.md) und [VPP](add-vpp-apps-ios.md) iOS-apps im Laufe des Jahres Schule
* Weisen Sie [Gruppe Administratoren](group-admin-delegate.md) helfen Ihnen beim Verwalten von Classroom-Einstellungen innerhalb Ihrer Schule/Universität oder in der Region
* Erfahren Sie, wie [einstellungsvererbung](settings-inheritance.md) wirkt sich auf neue Gruppen
* Überprüfen Sie [Berichte](what-are-reports.md) zu ermitteln, identifizieren und Beheben von Fehlern 
* Erneuern Sie [iOS-Zertifikate und Token](renew-ios-certificate-token.md) jedes Jahr
