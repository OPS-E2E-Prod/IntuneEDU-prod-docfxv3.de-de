---
title: Alle Einstellungen für iOS-Geräte
titleSuffix: Intune for Education
description: Eine Liste aller iOS-Gerät-Einstellungen in Intune for Education angezeigt.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 04/18/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 2221009e-68cf-4171-8118-0d750b0f35f1
searchScope:
- IntuneEDU
ms.openlocfilehash: b836ef9a01ac43d253b3a5543bd338cd2b4c95eb
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146674"
---
# <a name="ios-device-settings-in-intune-for-education"></a>Einstellungen für iOS-Geräte in Intune for Education  

> [!IMPORTANT]
> Werden alle iOS-Einstellungen nicht angezeigt? Wenn Sie feststellen, dass die iOS-Dropdownliste nicht angezeigt wird, oder wenn er deaktiviert ist, [Einrichten der iOS-geräteverwaltung](setup-ios-device-management.md). Nachdem Setup abgeschlossen ist, werden alle iOS-Steuerelemente aktiviert.

In diesem Artikel aufgelistet und beschrieben alle Einstellungen der iOS-Geräte in Intune for Education. Klicken Sie zum Anzeigen und bearbeiten diese Einstellungen im Portal können auf **Gruppen** >**Einstellungen** > **iOS-Geräteeinstellungen**.   

  ![Screenshot, der alle IOS-Geräte, Seite "Gruppen" in Intune for Education. Hebt die Registerkarte "Einstellungen", und zeigt iOS, Geräteeinstellungen Kategorie erweitert ist, um alle 12 Unterkategorien der Einstellungen anzuzeigen. Jede Einstellung wird reduziert.](./media/edu-ios-1904-device-settings.png)   

## <a name="apply-settings-to-groups"></a>Gelten Sie die Einstellungen für Gruppen  
Anwenden [gruppeneinstellungen](what-are-groups.md) zu, um den Zugriff und Sicherheitsgrenzen auf Geräten in Ihrer Schule/Universität herzustellen. Sie können die gleichen Einstellungen auf alle Gruppen in Ihrer Schule/Universität zuweisen. oder Sie können Anpassen der Classroom-Oberfläche und die Einstellungen gelten für einzelne Gruppen.

## <a name="configuration-options"></a>Konfigurationsoptionen  
Viele Einstellungen in Intune for Education konfiguriert **Block** oder **zulassen**. Für einige Einstellungen sind **nicht konfiguriert** ist eine Option. Beim Umschalten zu **nicht konfiguriert**, das Gerät gesperrt wird entweder:  
* Verwenden Sie die Standardeinstellung. 
* Ermöglichen Sie den Benutzer des Geräts (Student oder Lehrkraft), um die Einstellung auf ihrem Gerät anzupassen.  

## <a name="app-store-itunes-store-and-book-store"></a>Buch-Store, App Store und iTunes-Store   
|Einstellung|Beschreibung|
|---|---|
|Die App Store blockieren|Block Schüler und Studenten Zugriff auf den App Store auf School-Geräte.|
|Kennwort auf App Store erforderlich|Erfordern der Student, ein Kennwort einzugeben, bevor sie den App Store zugreifen können.|
|Herunterladen von apps auf anderen Geräten erworben wurden, automatisch blockieren|Blockieren von apps, die auf einem anderen School-Gerät heruntergeladen werden, auf ein anderes Gerät erworben wurden.|
|Block-in-app-Käufe|Block versucht, speichern Käufe aus dem in einer ausgeführten app zu erstellen.|
|Explizite Inhalte im App Store und iTunes Store blockieren|Hiermit blockieren Sie Schülern und Studenten Zugriff auf Inhalte jugendfreie in den App Store.|
|Herunterladen von Inhalten mit Apple Bücher Block bei "erotik".|Block Schülern und Studenten Herunterladen von Büchern, die als erotik klassifiziert sind.|
|Apps nach Altersfreigabe blockieren|Block Schülern und Studenten Herunterladen von apps, die die ausgewählte Altersfreigaben nicht erfüllen.| 

## <a name="built-in-apps"></a>Integrierte Apps  
|Einstellung|Beschreibung|
|---|---|
|Kamera blockieren|Blockiert die Verwendung der Kamera auf dem Gerät.|
|Hiermit blockieren Sie FaceTime|Blockiert die Verwendung von der FaceTime-app auf dem Gerät.|
|Game Center blockieren|Sperrt die Verwendung der Game Center-app auf Geräten.|
|Hinzufügen von Freunden in Game Center blockieren|Block Schüler/Studenten über das Hinzufügen von Freunden in Game Center-app.|
|Blockiert den Musikdienst Apple|Sperrt die Verwendung der streaming-Komponente der Apple Music-app auf dem Gerät Musik. |
|Block Optionsfeld in der Apple Music|Blockiert die Verwendung von Optionsfeldern in der Apple Music-app auf dem Gerät.|
|Nachrichten blockieren|Sperrt die Verwendung der Nachrichten-app auf dem Gerät.|
|Block Apple News|Sperrt die Verwendung der Apple News-app auf dem Gerät.|
|Blockieren von Apple-Bücher|Block Schüler/Studenten, aus durchsuchen und Bücher das Buch-Store kaufen.|
|Block-Podcasts|Sperrt die Verwendung der Podcasts-app auf dem Gerät.|
|Blockiert Änderungen an Einstellungen meine Freunde suchen|Block Schüler/Studenten an der Änderung von Einstellungen für die app meine Freunde suchen.| 
  
## <a name="device-restrictions"></a>Geräteeinschränkungen  
|Einstellung|Beschreibung|
|---|---|  
|Block-Screenshots und bildschirmaufzeichnungen|Block Schülern und Studenten die Aufnahme des Bildschirminhalts als Bild zu erfassen.|  
|Änderung von Gerätenamen blockieren|Block Schüler/Studenten daran, den Namen des Geräts zu ändern.|
|Ändern des Hintergrunds blockieren|Ändern das Gerät blockiert Schülern und Studenten Sperrbildschirm und Startbildschirm-Image.|  
|Änderung von Benachrichtigungseinstellungen blockieren|Block Schüler/Studenten an der Änderung von Benachrichtigungseinstellungen des Geräts.| 
|Blockiert Änderungen an Einstellungen für die Übermittlung von Diagnosedaten|Block Schülern und Studenten ändern, wenn oder wie das Gerät für diagnostische Daten sendet. |
 |Blockiert Änderungen an Inhalten und der Datenschutz-Einschränkungen|Block Schülern und Studenten Einschränkungen (Jugendschutz) und den Bildschirm und Uhrzeiteinstellungen auf dem Gerät ändern.|
|Manuelle Installation von Konfigurationsprofilen blockieren |Block Schüler/Studenten zusatzkonfiguration Profile auf dem Gerät manuell zu installieren.|
|Block-Schaltfläche, die alle Inhalte und Einstellungen werden gelöscht|Block Schülern und Studenten Löschen aller Inhalte und Einstellungen auf dem Gerät. Die Schaltfläche "löschen" ist nicht mehr verfügbar und kann nicht ausgewählt werden. |  
|Nicht vertrauenswürdige TLS-Zertifikate blockieren|Hiermit blockieren Sie nicht vertrauenswürdige Zertifikate von Transport Layer Security (TSL) auf dem Gerät.|  
|Vertrauenswürdige apps von Unternehmensentwickler blockieren|Sperrt die Verwendung der der **Unternehmensentwickler vertrauen** Schaltfläche. Wenn blockiert, Schüler/Studenten können nicht vertrauen, und Installieren von apps von Autoren neuer Unternehmens als. Schüler/Studenten verlieren nicht den Zugriff für ihre vorhandene Unternehmens-apps. Sie können auch noch Unternehmens-apps erhalten, die über Intune mithilfe von Push übertragen werden. Wenn Sie diese Einstellung nicht blockieren, können Schüler/Studenten vertrauen und Herunterladen von apps vor.|
|Blockiert Änderungen an Einstellungen der Enterprise Developer-Vertrauensstellung|Block Schüler und Studenten die Zertifikat-Trust- und app-Installation-Einstellungen ändern.| 
|Blockiert Änderungen an Einstellungen für Geräte-Konto|Block Schüler/Studenten kontospezifische-Einstellungen in der Einstellungs-app ändern. Schüler/Studenten können keine neue gerätekonten erstellen oder ändern Sie ihren Benutzernamen, Kennwort oder andere Einstellungen im Zusammenhang mit ihrem Konto.|   
|Blockiert die remotebildschirmüberwachung durch Classroom-app |Block Lehrkräfte mit der Classroom-app ihre Schüler/Studenten Bildschirme anzeigen.|  
|Unangekündigte bildschirmüberwachung über Classroom-app blockieren|Block Lehrkräfte mit der Classroom-app ihre students'screen, ohne für Schüler und Studenten benachrichtigungs- und Genehmigungsaktivitäten anzeigen.|  
|Aktivierungssperre zulassen|Aktiviert die Aktivierungssperre auf überwachten Geräten bei der Schüler/Studenten und Lehrkräfte suchen mein iPhone zu aktivieren. Die Aktivierungssperre ist ein, die verhindert, dass Personen Reaktivieren von einem Smartphone verloren gegangenen oder gestohlenen iOS-Feature. Wenn die Aktivierungssperre aktiviert ist, muss das Kennwort des Gerätebenutzers-Apple-ID deaktivieren mein iPhone suchen, das Gerät zu löschen oder erneuten Aktivieren des Geräts.  |  

## <a name="icloud"></a>iCloud  
|Einstellung|Beschreibung|  
|---|---|  
|ICloud-Sicherung blockieren|Block Schüler und Studenten aus der Sicherung von Geräten in iCloud.|  
|Synchronisierung von Dokumenten in iCloud blockieren|Hiermit blockieren Sie Dokumente in einen Speicher iCloud synchronisieren.|  
|Müssen Sie iCloud-Sicherungen verschlüsselt werden|Fordert an, dass Gerätesicherungen verschlüsselt werden.|  
|ICloud-Fotomediathek blockieren|Block Schüler und Studenten von Fotos und Videos in der Cloud speichern. Fotos, die vollständig aus der iCloud-Fotomediathek heruntergeladen werden nicht werden aus dem lokalen Speicher entfernt. | 
|Mein Photo Stream blockieren|Block Schülern und Studenten mein Photo Stream zu aktivieren. Mein Photo Stream ist ein iOS-Feature, die kürzlich (innerhalb der letzten 30 Tage) Gerät Fotos mit iCloud synchronisiert wird. Schüler/Studenten können dann die Photo Stream auf allen Geräten anzeigen, die mit der iCloud-Konto zugreifen.|  
|Block freigegeben Alben|Block Schüler/Studenten, abonnieren oder freigegebene Alben in der Fotos-app veröffentlichen.| 
|Übergabe blockieren|Fortsetzen der Arbeit Block Schülern und Studenten, die sie auf einem iOS-Gerät auf einem anderen iOS-Gerät gestartet.|  

## <a name="keyboard-and-dictionary"></a>Tastatur und Wörterbuch  
|Einstellung|Beschreibung|  
|---|---|  
|Tastatur-Rechtschreibprüfung blockieren|Sperrt die Verwendung der Rechtschreibprüfung des Geräts.|
|Hiermit blockieren Sie Tastenkombinationen|Sperrt die Verwendung der Tastenkombinationen in Visual Studio.|
|Tastaturvorschläge blockieren|Blockieren Sie tastaturwortvorschläge, die Wörter vorschlagen, bei der Eingabe an.|
|Block Diktat|Block Schüler/Studenten Spracheingabe zur Eingabe von Text.|
|Nach Wortdefinitionen blockieren|Blockiert die Verwendung des iOS-Features, mit dem Sie ein Wort markieren und dessen Definition nachschlagen.|
|Word AutoKorrektur blockieren|Hiermit blockieren Sie das Gerät falsch geschriebene Wörter automatisch korrigiert.|

## <a name="lock-screen-and-wallpaper"></a>Sperrbildschirm und Hintergrund  
|Einstellung|Beschreibung|
|---|---|
|Benachrichtigungen auf Sperrbildschirm blockieren|Block Schüler/Studenten, Benachrichtigungen anzeigen, wenn das Gerät gesperrt ist.|
|Hiermit blockieren Sie Siri bei gesperrtem Gerät|Block Schüler und Studenten aus der Verwendung von Siri, iOS virtueller Assistenten, wenn das Gerät gesperrt ist.|
|Wird der Zugriff auf das Kontrollcenter über Sperrbildschirm blockieren|Block Schülern und Studenten Zugriff auf die Kontrollcenter-app aus, wenn das Gerät gesperrt ist.|
|Wird der Zugriff auf Wallet über Sperrbildschirm blockieren|Block Schüler und Studenten Zugriff auf die Wallet-app aus, wenn das Gerät gesperrt ist.|
|Blockansicht "heute" auf Sperrbildschirm|Block Schüler und Studenten aus der Ansicht "heute" angezeigt, wenn das Gerät gesperrt ist.|
|Informationen zum Bestandskennzeichen|Anwenden von einem bestimmten Tag an alle Geräte in einer Gruppe. Z. B. **im Besitz von Contoso-Schulbezirk.** Das Tag wird auf dem gerätesperrbildschirm angezeigt werden.| 
|Fußnote zum Sperrbildschirm|Gilt die Notiz oder die Anweisung auf dem Sperrbildschirm angezeigt, sodass, wenn das Gerät Fundbüro ist, es entsprechend zurückgegeben werden kann. Z. B. **Wenn gefunden, die Contoso-Schulbezirk in 555-555-5555 aufrufen.**
|Set-Gerät Hintergrundbild für Sperrbildschirm| Wählen Sie ein benutzerdefiniertes Image als das Hintergrundbild für Sperrbildschirm des Geräts angezeigt werden.|
|Set-home-Bildschirm gerätebilds| Wählen Sie ein benutzerdefiniertes Bild als Hintergrund für den für die Startseite des Geräts angezeigt werden.| 


## <a name="network-and-connectivity"></a>Die Netzwerk- und Konnektivitätsoptionen
Dieser Abschnitt enthält die Einstellungen für:
* Drahtlose Verbindungen  
* WLAN-Profile   
 
### <a name="wireless-connections"></a>Drahtlose Verbindungen  
|Einstellung|Beschreibung|
|---|---|
|Blockieren der Änderung der Bluetooth-Einstellungen|Block Schüler/Studenten, Bluetooth-Einstellungen auf dem Gerät ändern.| 
|Blockieren persönlichen Hotspot|Block Schüler/Studenten, verwenden Sie das Gerät als persönlicher Hotspot.|
|Hiermit blockieren Sie AirDrop|Blockiert die Verwendung von airdrop. Zum Austauschen von Inhalten mit Geräten in Ihrer Nähe können Schüler/Studenten nicht gelöst werden.|

### <a name="wi-fi-profiles"></a>WLAN-Profile   
|Einstellung|Beschreibung|
|---|---|
|Wählen Sie die iOS-WLAN-Profile, die sie dieser Gruppe zuweisen.|Eine Liste der WLAN-Profile, die Sie erstellt haben in diesem Abschnitt angezeigt und können Sie zuweisen. Sichtbare Details umfassen die **Profilname**, **Netzwerkname (SSID)**, **Sicherheitstyp**, und **Beschreibung**.  

## <a name="passcode-touch-id-and-face-id"></a>Kennung, Touch ID und Face ID  
|Einstellung|Beschreibung|
|---|---|  
|Kennung erforderlich|Erfordern Sie Schüler/Studenten, eine Kennung zum Entsperren des Geräts eingeben.|
|Ändern der Kennung blockieren|Block Schülern und Studenten ändern, hinzufügen oder entfernen die Kennung des Geräts. |
|Minuten der Inaktivität bis zur Sperrung des Bildschirms|Nachdem das Gerät zu lange im Leerlauf bleibt, wird der Bildschirm gesperrt. Um diese Einstellung konfigurieren, geben Sie die maximale Anzahl von Minuten an, denen das Gerät im Leerlauf befinden kann.|
|Minuten gewartet werden soll, kennungsanforderung auf Sperrbildschirm|Nachdem das Gerät zu lange im Leerlauf bleibt, muss der Benutzer das Gerätekennwort, um wieder Zugriff erhalten erneut eingeben. Um diese Einstellung konfigurieren, geben Sie die maximale Anzahl von Minuten an, denen das Gerät im Leerlauf befinden kann.|
|Anzahl fehlerhafter Versuche für kennungseingabe bis zum Gerät|Wenn ein Benutzer die zulässige Anzahl von Anmeldeversuchen, Gerät löscht alle Inhalte und Einstellungen vom Gerät überschreitet z.B. personenbezogene Daten, Software für iOS, e-Mail-Konten, System und app-Einstellungen, heruntergeladenen apps und Media. Mit der Art und Weise, die sie beim ersten aktiviert wurde, wird das Gerät wiederhergestellt. Um diese Einstellung konfigurieren, geben Sie die maximale Anzahl von Anmeldeversuchen zulässig.|  
|Block Touch ID und Face ID|Block Schülern und Studenten mit einem Fingerabdruck oder gesichtserkennung verwendet zum Entsperren von Geräten.|  
|Blockieren der Änderung der Einstellungen für Touch ID und Face ID|Block Schülern und Studenten ändern, hinzufügen oder Entfernen von Touch ID und Face ID-Einstellungen.| 


## <a name="safari"></a>Safari   
|Einstellung|Beschreibung|  
|---|---|  
|Block Safari|Hiermit blockieren Sie den Safari-Browser auf dem Gerät.|  
|AutoAusfüllen: blockieren|Block Schüler/Studenten an der Änderung von Einstellungen für AutoAusfüllen im Browser.|  
|Popups blockieren|Popups blockieren, die im Browser angezeigt werden.| 
|Sperren von cookies|Hiermit blockieren Sie die Verwendung von Cookies durch den Browser.|  
|Erfordern von gefälschten Website-Warnungen|Anzeigen von betrugswarnungen im Browser.|  

## <a name="siri-and-search"></a>Siri und Suche  
|Einstellung|Beschreibung|  
|---|---| 
|Hiermit blockieren Sie Siri|Block Schüler/Studenten aus der Verwendung von Siri-iOS Sprach-Assistent.|
|Hiermit blockieren Sie Siri-Filter für anstößige Ausdrücke|Hiermit blockieren Sie Siri diktiert oder verwendet.|
|Hiermit blockieren Sie Siri vom Benutzer generierte Inhalte werden gesucht|Blockieren Sie Siri den Zugriff auf Websites, um Fragen zu beantworten.|  
|Zurückgeben der Suchergebnisse Internet-Blickpunkt blockieren|Hiermit blockieren Sie Spotlight-Suche, eine Verbindung herstellen das Internet, um weitere Ergebnisse bereitzustellen.|  

## <a name="update-restrictions"></a>Aktualisieren von Einschränkungen  
|Einstellung|Beschreibung|
|---|---|
|Aktualisieren von bestimmten Zeiten von Geräten zu verhindern|Updates für das Gerät gemäß Ihrer Auswahl Tages- und zu beenden.|  

> [!NOTE]
> Benutzer, Geräte und app-Einstellungen unterscheiden sich von [mandanteneinstellungen](edu-tenant-general-settings.md). Mandanteneinstellungen werden als Ziel die Abonnement und verwaltungseinstellungen administrative Ebene der Organisation.  

## <a name="next-steps"></a>Nächste Schritte  
Konfigurieren Sie Ihre Gruppe, die app und die Einstellungen für Geräte in Intune for Education-Portals ein. Wenn Sie noch nicht erfolgt, fahren Sie mit [express-Konfiguration](edu-express-config-settings-ios.md) und Ihrer Schule/Universität mit Microsoft-empfohlenen Einstellungen einrichten.    
