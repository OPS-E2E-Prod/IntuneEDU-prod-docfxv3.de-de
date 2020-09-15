---
title: Einrichten der iOS-geräteverwaltung
titleSuffix: Intune for Education
description: Aktivieren Sie die Verwaltung von iOS-Geräten synchronisieren und Verwalten von iOS-Geräte über Intune for Education-Portals.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 01/09/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.openlocfilehash: 7f581e8dcfc870c8b5b9994dab3b2f7a9a9428dc
ms.sourcegitcommit: fe8359eaaf216ca4938332fa7ef91d200ea72f7c
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/08/2019
ms.locfileid: "67622848"
---
# <a name="setup-ios-device-management"></a>Einrichten der iOS-geräteverwaltung 

Bevor Sie zu verwalten oder Schüler/Studenten und Lehrkräfte iOS-Geräten zuweisen können, müssen Sie die Verwaltung von iOS-Geräte in Intune for Education einrichten. Dieser Setup erfordert, dass Sie ein MDM-Push-Zertifikat hinzufügen und konfigurieren mindestens eine MDM-Servertoken (auch bekannt als ein DEP-Token).  

  ![Screenshot der Mandanteneinstellungen, iOS-Device-Management-Seite und zeigt grüne Kreise mit weißem Häkchen für die token für die MDM-Push-Zertifikat, MDM-Server und VPP-token-Karten. Kreise anzugeben, dass alle konfiguriert sind. Benutzer kann die blaue Schaltfläche "rechteckige" klicken, die besagt "Verwalten", um zu bearbeiten oder Aktualisieren von Konfigurationen.](./media/set-up-ios-management-landing-1807.png)   

Während des Setups müssen Sie Ihre Intune for Education-Konto mit Ihrem Apple School Manager-Konto verbinden. Die Verbindung wird sichergestellt, dass es sich bei Intune for Education immer die aktuellen Details über Ihre erworbenen iOS-Geräte bekannt sind.

In diesem Artikel wird beschrieben, wie Sie:

* Fügen Sie ein Apple-MDM-Push-Zertifikat hinzu.
* Konfigurieren Sie und synchronisieren Sie ein Token von Apple-MDM-Server.
* Konfigurieren Sie ein Apple VPP-Token.

## <a name="what-happens-after-i-set-up-device-management"></a>Was passiert, nachdem ich die geräteverwaltung einrichten?
Nachdem Sie die Verwaltung von iOS-Gerät eingerichtet haben, müssen Sie Intune for Education zu verwenden, um apps und Einstellungen auf Ihrem iOS-Geräten verwalten können. Sie müssen auch den Zugriff auf Berichte und Aktionen, sodass Sie an einer beliebigen Stelle Konflikte beheben können.  

Schüler/Studenten und Lehrkräften in Ihrer Schule/Universität können sicher School-Websites und e-Mail-Adresse zugreifen.  

## <a name="requirements"></a>Anforderungen
Bevor Sie beginnen, sicher, dass Sie haben:  
* Eine Internetverbindung.
* Anmeldeinformationen für das Apple School Manager.
* Intune for Education-Gerät-Lizenzen. Erfahren Sie mehr über die Gerätelizenzen in die [Intune-Lizenzen Docs](https://docs.microsoft.com/intune/get-started/start-with-a-paid-subscription-to-microsoft-intune-step-4).  

> [!IMPORTANT]
> Intune for Education unterstützt nur die iOS-geräteregistrierung für Geräte, die über Apple-DEP erworben wurden Weitere Informationen zum Apple School Manager finden Sie unter den [Support-Website von Apple Education](https://support.apple.com/education).  

## <a name="add-an-mdm-push-certificate"></a>Hinzufügen eines MDM-Push-Zertifikats
Ein Apple-MDM-Push-Zertifikat ist eine sichere Verbindung zwischen Ihrem Intune und Apple School Manager-Konto eingerichtet. Wenn verbunden, kann Intune kontinuierlich synchronisieren und verwalten Sie Ihre Apple-Geräten und apps. 

1. Melden Sie sich bei Intune for Education-Portals.
2. Rufen Sie die Randleiste, und klicken Sie auf **Mandanteneinstellungen** > **iOS-Geräteverwaltung**.
3. Klicken Sie auf die **MDM-Push-Zertifikat** Registerkarte.
4. Befolgen Sie die Anweisungen auf der **MDM-Push-Zertifikat** Seite. Sie müssen das Apple Push Certificates-Portal, um ein MDM-Push-Zertifikat zu erstellen, finden Sie unter. Melden Sie sich beim Apple Push Certificates-Portal mit Ihrer Schule Apple-ID, nicht der persönlichen USt.
5. Führen Sie die Schritte im Apple-Portal. Nachdem Sie das Zertifikat erstellt haben, klicken Sie zum Herunterladen und speichern Sie sie.
6. Zurück zu Intune for Education-Portals, und geben Sie die Apple-ID, die Sie zur Anmeldung beim Apple Push Certificates-Portal verwendet.
7. Laden Sie das Zertifikat, das Sie heruntergeladen haben hoch.
8. Klicken Sie auf **Speichern**.  

Das Push-Zertifikat läuft 365 Tage. Das Zertifikat ist erforderlich, um Intune for Education also mit Ihrem Apple School Manager-Konto verbinden [müssen Sie es jährlich verlängern](renew-ios-certificate-token.md).  


## <a name="configure-mdm-server-token"></a>Konfigurieren Sie die MDM-servertoken  
Manchmal als ein DEP-Token bezeichnet wird, kann die MDM-servertoken Intune synchronisieren Gerätedetails aus Apple School Manager. Diese Details zu informieren, Intune die Geräte zu verwalten, muss und füllt Sie Ihr Inventar in Intune for Education-Portals.  

### <a name="shared-ipad-configuration"></a>Gemeinsam genutztes iPad-Konfiguration  
Sie können Ihre iOS-Geräte, die als freigegebene iPad-Geräte registrieren, konfigurieren. Mit freigegebenem iPad Schüler/Studenten und Lehrkräfte melden Sie sich bei Ihrer Schule-Geräte mit ihrer eindeutigen verwaltete Apple-ID Wenn sie zwischen Geräten verschieben, verschieben ihre apps und Daten, mit ihnen. Schüler/Student kann ein Gerät verwenden, um zu beginnen, schreiben ein Dokument, und melden Sie sich auf einem anderen Gerät später zu diesem Dokument fertig zu stellen. Erfahren Sie mehr über *gemeinsam genutztes iPad* und *verwalteten Apple-IDs*, besuchen Sie die [Education von Apple-Website](https://www.apple.com/education/it/) und [Dokumentation](https://go.microsoft.com/fwlink/?linkid=2060097&clcid=0x409).  

Classroom-Geräte können weiterhin Schüler/Studenten, auch ohne gemeinsam genutztes iPad gemeinsam genutzt werden. Benutzerdaten werden jedoch nicht zwischen Geräten verschieben. Bevor Sie Ihr servertoken konfigurieren, können Sie auswählen, wenn Sie gemeinsam genutztes iPad aktivieren möchten. 

### <a name="server-token-setup"></a>Server-Setup-token  

Die folgenden Schritte beschreiben, wie Sie Ihre MDM-Servertoken konfigurieren. 

1. Wechseln Sie zu **Mandanteneinstellungen** > **iOS-Geräteverwaltung**, und wählen Sie die **MDM Server Token** Registerkarte.
2. Wählen Sie **Token einrichten**.
3. Wählen Sie, wie Sie das neue servertoken zugeordneten Geräte zu registrieren möchten.  
    * Wählen Sie zum Konfigurieren dieses Token für freigegebene iPad **Benutzer anmelden, auf Geräten mit ihrer verwalteten Apple-IDs**. Alle Geräte, die dieses Token zugewiesen werden eingerichtet, damit sie mit einer verwalteten Apple-ID anmelden müssen  
        > [!IMPORTANT]
        > Sie können nicht Ihrer Wahl ändern, nachdem Sie das servertoken erstellt. Nach diesem Schritt, wenn Sie ändern, wie Geräte möchten, müssen Sie ein neues servertoken zu erstellen.  

        > [!NOTE]
        > Wenn Sie ein Gerät mit freigegebenem iPad festlegen, erhalten alle Features Sie, die mit gemeinsam genutztes iPad, mit Ausnahme der Classroom und Schulaufgaben apps stammen. Diese apps werden nicht von Intune for Education unterstützt. Alle anderen freigegebene iPad-Funktionen werden zur Verfügung, nachdem Sie die MDM-servertoken eingerichtet.  

    * Wenn es sich bei Ihrer Schule/Universität verwalteten Apple-IDs verwendet, wählen Sie **kann alle Benutzer dieser Geräte entsperren...** Geräte können weiterhin von Studenten, die freigegeben werden&ndash;sie werden nur direkt zugegriffen werden, ohne die Notwendigkeit für die Anmeldung. Sie können eine gerätekennung erfordern, wenn Sie eine Eigenschaft festgelegt.  

4. Wählen Sie **herunterladen** zum Herunterladen des erforderlichen Intune öffentlichen Schlüssels. Sie müssen zum Hochladen dieser Datei in Apple School Manager zum Erstellen Ihres MDM-Server-Tokens. Speichern Sie die Datei auf Ihrem Computer.
5. Wählen Sie **wechseln Sie zu Meine MDM-Server im Apple School Manager**. Wenn Sie dazu aufgefordert werden, melden Sie sich, um Apple School Manager mit der Apple-ID Ihrer Schule, nicht der persönlichen USt.
6. Führen Sie die Schritte auf dem Bildschirm, um die MDM-Server zu erstellen. Klicken Sie dann Ihre Änderungen zu speichern. Wenn Sie die Informationen zum Ausführen dieses Schritts nicht haben, wenden Sie sich an den Intune-Administrator Ihrer Schule.
7. Laden Sie und speichern Sie das Token für den MDM-Server.
8. Behalten Sie die Apple School Manager, und wechseln Sie zu **Gerätezuweisungen**. Geben Sie die Seriennummer für jedes Gerät, das die Bestellnummer für das gesamte Gerät erwerben oder eine Liste von Geräten in eine CSV-Datei ein.  

  ![Screenshot von Gerätezuweisungen-Seite der Apple School Manager-Website. Zeigt Schritt 1, "Geräte auswählen" mit Auswahl an Sender und ein leeres Feld Feld für Benutzer zur Eingabe, wie sie die erworbene Geräte manuell eingeben möchten. Wird Schritt 2, "Aktion auswählen" mit einem Dropdown-Menü, in denen Benutzer auswählen "Zu Server zuweisen".](./media/Apple-School-Manager-MDM-Server-token-1807.png)   

9. Wählen Sie im Dropdown-Menü **zu Server zuweisen**. Wählen Sie dann den MDM-Server, die, den Sie gerade erstellt haben.
10. Zurück zu Intune for Education-Portals, und geben Sie die Apple-ID, die Sie zur Anmeldung beim Apple School Manager verwendet.
11. Hochladen der MDM-Server-Token, das Sie heruntergeladen haben.
12. Klicken Sie auf **Speichern**.

MDM-Server-Token ablaufen 365 Tage. Das Token ist erforderlich, zum Anzeigen und verwalten Ihre Geräte in Intune for Education-Portals. Sie müssen [jährlich erneuern](renew-ios-certificate-token.md).

### <a name="device-enrollment-profile"></a>Anmeldungsprofil für Geräte
Intune for Education erstellt und ein iOS-Registrierungsprofil zu den einzelnen MDM-Server-Token, die Sie konfigurieren.

Alle iOS-Geräte zu Intune for Education hinzugefügt werden auf den überwachten Modus festgelegt. Als Administrator kann im überwachten Modus Sie mehr Kontrolle über Ihre Schule Geräte. Beispielsweise können Sie neue apps oder app-Updates im Hintergrund auf einem Gerät übertragen. Eine vollständige Liste der Einstellungen für reine überwacht werden soll, finden Sie im Artikel [Konfigurationen, die Überwachung erfordern](/intune/device-restrictions-ios#settings-that-require-supervised-mode).

Intune for Education gilt ein Benennungsschema für Geräte, die Sie mit einem MDM-Server-Token zu registrieren. Der Name hilft Ihnen beim Identifizieren und Gruppieren von einzelnen Geräten. Standardmäßig werden die Geräte mit die Seriennummer des Geräts benannt. Sie können auch einen benutzerdefinierten Namen hinzufügen, wenn Sie Ihr MDM-Server-Token einrichten.  

Für Weitere Informationen zu registrierungsprofile, Anzeigen der [Liste der konfigurierten Einstellungen](add-devices-ios-edu.md#preconfigured-settings) während der Registrierung.  

### <a name="sync-managed-devices"></a>Synchronisieren verwalteter Geräte
Nun, dass Intune for Education hat die Berechtigung zum Verwalten von iOS-Geräten mit Apple zum Anzeigen einer Liste der von Ihnen verwalteten Geräte synchronisieren.  
1. Anmelden bei Intune for Education.
2. Klicken Sie auf **Mandanteneinstellungen** > **iOS-Geräteverwaltung** > **DEP-Token**.
3. Klicken Sie auf eines der aufgeführten Token.
4. Klicken Sie auf **Geräteliste synchronisieren**. 

Geräte, die in der Liste angezeigt werden, sind bereit für Registrierung. Schalten Sie sie an, an die Registrierung zu starten.

## <a name="configure-vpp-tokens"></a>Konfigurieren von VPP-Token

 Ein VPP-Token werden Ihre Intune for Education-Konto mit Ihrem Apple VPP- oder Apple School Manager-Konto verknüpft. Sie können ein einzelnes VPP-Token zum Verwalten von apps in der gesamten Organisation erstellen. oder Sie können mehreren VPP-Token, um verschiedene Speicherorte oder Administratoren Management verteilt erstellen.  

VPP-Token sind Intune erforderlich:  
* Einzelheiten zur app in Intune for Education-Portals zu synchronisieren.
* Zuweisen von VPP per Volumenlizenz erworbene apps zu Gruppen
* Im Hintergrund installieren Sie VPP per Volumenlizenz erworbene apps auf "School" Geräten, ohne dass des Gerätebenutzers Apple-ID

Ohne ein VPP-Token verwenden, können Sie weiterhin suchen und abrufen [kostenlose iOS-apps über den App Store](add-apps-ios.md). Allerdings muss zum Installieren der app auf dem Gerät, Benutzer des Geräts mit einer Apple ID anmelden 

1. Auf der **iOS-Geräteverwaltung** klicken Sie auf die **VPP-Token** Registerkarte.
2. Klicken Sie auf **öffnen Apple School Manager** und melden Sie sich mit Ihrer Schule Apple-ID, nicht der persönlichen USt.
3. Führen Sie die Schritte in das Verwalten von Apple Schule zum Erstellen und laden das Token aus. Speichern Sie das Token, auf dem lokalen Laufwerk.
4. Zurück zu Intune for Education-Portals. Geben Sie die Apple-ID, die Sie zur Anmeldung beim Apple School Manager verwendet werden soll.
5. Klicken Sie auf das Ordnersymbol, um Dateien von Ihrem Computer zu durchsuchen. Wählen Sie die token-Datei, die Sie heruntergeladen haben und die zuvor gespeichert haben.
6. Wählen Sie den Speicherort der Geräte von Ihrer Schule.
7. Wenn Sie keine automatische app-Updates aktivieren möchten, wechseln Sie die Einstellung, um sie zu deaktivieren. 
8. Klicken Sie auf **Speichern**.

Token ablaufen 365 Tage. Token sind erforderlich, um das Verwalten von VPP per Volumenlizenz erworbene apps, also [müssen Sie diese jährlich verlängern](renew-ios-certificate-token.md).

### <a name="whats-a-managed-device"></a>Was ist ein verwaltetes Gerät?
Damit können Sie den Unterschied zwischen einer verwalteten und nicht verwalteten Gerät zu verstehen, betrachten wir das folgende Szenario.

Ein Lehrer bringt einen persönlichen iOS-Gerät an. Während der Schule Stunden verwendet der Lehrer das Gerät aus, übergeordneten Besprechungstermine und Klasse-Zuweisungen von.  

 Das Gerät wurde nicht von der Schule über das Apple-DEP-Programm erworben haben. Es ist nicht in Intune for Education-Mandanten registriert. Daher besteht keine Möglichkeit für Intune, um die Kommunikation mit dem der Lehrkraft Gerät zur Verfügung. Das Gerät wird nicht berücksichtigt, verwaltet werden – die IT-Administrator hat keine Kontrolle darüber, wie der Lehrer das Gerät während der Schule Stunden verwendet. 

Auf ähnliche Weise, da es sich nicht um ein bekanntes, verwalteten Gerät handelt, der Kursleiter geschützten uniressourcen wie z. B. e-Mail-Zugriff auf nicht.  

## <a name="next-steps"></a>Nächste Schritte

Kauf [kostenlose apps aus dem App Store](add-apps-ios.md), oder [bieten Sie Ihre VPP per Volumenlizenz erworbene apps](add-vpp-apps-ios.md) zu Intune for Education-Portals.  

