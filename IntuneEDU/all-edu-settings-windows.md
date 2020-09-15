---
title: Alle Einstellungen für Windows 10-Geräte
titleSuffix: Intune for Education
description: Eine Liste mit allen Einstellungen für Windows 10-Gerät in Intune for Education angezeigt
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 01/10/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 2221009e-68cf-4171-8118-0d750b0f35f1
searchScope:
- IntuneEDU
ms.openlocfilehash: 63705b1370379efe03b70876b6313a906a57719e
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146804"
---
# <a name="windows-10-device-settings-in-intune-for-education"></a>Einstellungen von Windows 10-Geräte in Intune for Education

In diesem Artikel aufgelistet und beschrieben alle Einstellungen der Windows-Geräte in Intune for Education. Klicken Sie zum Anzeigen und bearbeiten diese Einstellungen im Portal können auf **Gruppen** > **Einstellungen** > **Windows-Geräteeinstellungen**.  


  ![Screenshot, der alle Geräte, Seite "Gruppen" in Intune for Education. Hebt die Registerkarte "Einstellungen", und zeigt, dass die Einstellungen für Windows-Geräte-Kategorie erweitert ist, um alle 10 Unterkategorien der Einstellungen anzuzeigen. Jede Einstellung wird reduziert.](./media/edu-windows-device-settings-1812.png)   

## <a name="apply-settings"></a>Einstellungen anwenden  
Anwenden [gruppeneinstellungen](what-are-groups.md) Zugriff und Sicherheit von Grenzen auf den Geräten in Ihrer Schule/Universität herstellen. Sie können die gleichen Einstellungen auf alle Gruppen in Ihrer Schule/Universität zuweisen. oder Sie können Anpassen der Classroom-Oberfläche und die Einstellungen gelten für einzelne Gruppen.  

## <a name="configuration-options"></a>Konfigurationsoptionen  
Viele Einstellungen in Intune for Education konfiguriert **Block** oder **zulassen**. Für einige Einstellungen sind **nicht konfiguriert** ist eine Option. Beim Umschalten zu **nicht konfiguriert**, das Gerät gesperrt wird entweder:  
* Verwenden Sie die Standardeinstellung. 
* Ermöglichen Sie den Benutzer des Geräts (Student oder Lehrkraft), um die Einstellung auf ihrem Gerät anzupassen.    

> [!NOTE]
> Benutzer, Geräte und app-Einstellungen unterscheiden sich von [mandanteneinstellungen](edu-tenant-general-settings.md). Mandanteneinstellungen beheben Sie die Abonnement und die Einstellungen für Ihre Organisation.

## <a name="accounts-and-sign-in"></a>Konten und -Anmeldung  
Konfigurieren Sie, wie Benutzer bei School-Geräte anmelden.

|Einstellung|Funktion|
|---|---|
|Blockieren Sie Hinzufügen von und Anmelden mit persönlichen Microsoft-Konten|Hiermit werden Benutzer nicht mit seinem Microsoft-Konto anmelden.|
|Blockieren Sie Hinzufügen von und Anmelden mit nicht-Microsoft-Konten|Hiermit werden Benutzer von einem anderen Konto als ihr Microsoft-Konto hinzufügen. Verwenden Sie diese Einstellung, wenn Sie erzwingen, dass Benutzer nur ihre Microsoft-Konten für die e-Mail-Adresse verwenden möchten.| 
|Konfigurieren Sie bevorzugte Azure Active Directory-mandantendomäne|Ermöglicht Benutzern, die an Windows anmelden, ohne Sie den Domänennamen eingeben. Wenn Sie diese Einstellung konfigurieren, wird der Domänenname des Mandanten wird vorab aufzufüllen, aber kann noch bearbeitet werden.|  

## <a name="apps"></a>Apps  
Konfigurieren Sie Einstellungen wie z. B. wie die Benutzer installieren und Zugreifen auf apps auf ihren Geräten.  

|Einstellung|Funktion|
|---|---|
|Entfernen Sie die integrierte Windows 10-apps|Deinstallieren Sie bestimmte integrierte Windows-apps. Erfahren Sie, was diese apps sind [unten](all-edu-settings-windows.md#remove-built-in-apps).| 
|Zugriff auf administrative apps blockieren|Block Schüler/Studenten, öffnen Sie die apps, die Administratorrechte erforderlich.|
|Blockieren Sie Installieren von apps aus dem Microsoft Store für Bildungseinrichtungen|Hiermit werden Benutzer daran, apps von nicht autorisierten Orten installieren.|
|Müssen Sie Microsoft Store für Bildungseinrichtungen-apps aus privatem Store installiert werden|Nur können Sie Benutzer apps aus dem Microsoft Store für Bildungseinrichtungen zu installieren, die Ihre Organisation eingerichtet wurde.|
|Vertrauenswürdige apps|Zulassen Sie oder blockieren Sie Benutzer daran, vertrauenswürdigen apps, die Zertifikate von Microsoft registriert haben.|
|Nicht vertrauenswürdige apps|Zulassen Sie oder blockieren Sie Benutzer daran, apps mit Zertifikaten, die ohne Vorzeichen oder signiert von Quellen, die nicht von Microsoft vertraut wird.|
|Blockieren Sie Installieren von apps aus anderen Orten als aus dem Microsoft Store für Bildungseinrichtungen|Installieren von apps aus anderen Quellen und der app-Stores blockieren für Benutzer.
|Blockieren Sie automatische Updates für Microsoft Store für Bildungseinrichtungen-apps|Hiermit blockieren Sie Microsoft Store für Bildungseinrichtungen-apps automatisch aktualisiert wird.|
|Aktivieren der Schüler/Studenten auf gemeinsam genutzte Geräte zum Freigeben von app-Daten|Schüler und Studenten verwenden die gleiche app auf dem gleichen Gerät zum Freigeben von Daten zu aktivieren.|  


## <a name="enrollment-controls"></a>Registrierungssteuerelemente  
Konfigurieren Sie Einstellungen im Zusammenhang mit Intune Education-geräteregistrierung.

|Einstellung|Funktion|
|---|---|
|Manuelle Aufhebung der Registrierung blockieren|Hiermit werden Benutzer von Geräten in der Verwaltung manuell Aufheben der Registrierung.|
|Aktivieren Sie Autopilot zurücksetzen| Ermöglichen Sie Benutzern mit Administratorrechten, drücken STRG + Win + R auf dem gerätesperrbildschirm Trigger Autopilot zurücksetzen. Autopilot-zurücksetzen entfernt alle Benutzerdaten&ndash;z. B. Benutzer installierten apps und persönlichen Einstellungen&ndash;und behält das Gerät bei Intune registriert sind. Daher wird das Gerät auf dem neuesten Stand mit den neuesten apps, Richtlinien und Einstellungen beibehalten.|
|Hinzufügen von Bereitstellungspaketen blockieren|Hiermit werden Benutzer vom Hinzufügen neuer Bereitstellungspaketen, die Einstellungen für Geräte haben.|
|Entfernen von Bereitstellungspaketen blockieren|Hiermit werden Benutzer daran, Bereitstellungspakete, die Einstellungen für Geräte zu entfernen.|  


## <a name="microsoft-edge"></a>Microsoft Edge  
Konfigurieren Sie Einstellungen, die Auswirkungen auf die Microsoft Edge-Browser-Erfahrung und Benutzer-Daten.

### <a name="browser-experience"></a>Browserfunktionen  
|Einstellung|Funktion|
|---|---|
|Startseiten konfigurieren|Wählen Sie an, auf welcher Seite öffnet, jedes Mal, wenn ein Benutzer eine neue Microsoft Edge-Browser-Sitzung beginnt.|
|Konfigurieren Sie die neue Registerkarte|Wählen Sie an, auf welcher Seite öffnet, jedes Mal, wenn ein Benutzer eine neue Registerkarte in Microsoft Edge geöffnet.|
|Konfigurieren Sie das Verhalten der Schaltfläche "Start"|Wählen Sie an, welche Seite wird angezeigt, wenn Benutzer auf die Schaltfläche "Start" in Microsoft Edge klicken. Sie können auch auf die Schaltfläche "Start" ausblenden.|
|Bearbeitung von Favoriten blockieren|Hiermit werden Benutzer hinzufügen, importieren, sortieren oder bearbeiten die Liste der Favoriten.|
|Suchvorschläge in Adressleiste blockieren|Block Microsoft Edge aus schlägt mögliche Suchbegriffe oder zuvor besuchten Websites, während der Eingabe von eines Begriffs suchen oder URL.|
|Suchvorschläge blockieren|Microsoft-Edge von möglichen Websites vorgeschlagen, während der Eingabe von eines Begriffs suchen oder URL-Block.|
|InPrivate-Browsen blockieren|Hiermit werden Benutzer daran, InPrivate-Browsen, Microsoft Edge das verhindert wird, Speichern von Daten, wie das Durchsuchen von Verlauf und Cookies.| 
|Browsererweiterungen blockieren|Hiermit werden Benutzer von der Verwendung von Erweiterungen zum Anpassen von Microsoft Edge mit zusätzlicher Funktionalität von Microsoft und anderen Quellen.|
|Nicht vertrauenswürdige Browsererweiterungen blockieren|Hiermit werden Benutzer von sideload-Erweiterungen an den Microsoft Edge-Browser. Diese Erweiterungen werden installiert, aus nicht vertrauenswürdigen Quellen&ndash;nicht mit dem Microsoft Store&ndash;Malware werden konnte.|
|Drucken über Microsoft Edge blockieren|Hiermit werden Benutzer vom Browser Inhalt drucken.|
|Seite "-Block zuerst ausgeführt."|Hiermit werden Benutzer über die Seite erste Ausführung angezeigt. Microsoft Edge-Anpassungs-Seite wird angezeigt, wenn ein Benutzer zum ersten Mal und nach Updates für Browser Microsoft Edge öffnet.|
|Popups blockieren|Hiermit blockieren Sie Websites in neuen Fenstern öffnen.|
|Überschreiben Sicherheitswarnungen blockieren|Hiermit werden Benutzer zwischen dem Klicken auf "Fahren Sie mit der Webseite" für Websites, die ein Fehler der SSL/TLS-Zertifikat angezeigt.|
|Kennwort-Manager blockieren|Hiermit werden Benutzer von mit dem Kennwortmanager zum Speichern von Kennwörtern.|
|Automatisch ausfüllen von Formulareinträgen blockieren|Speichern online in ein Formular eingegebene Daten blockieren.|
|Blockiert den Zugriff auf about: Flags-Seite|Blockieren des Zugriffs auf die über: Flags-Seite, die experimentelle Einstellungen und Features enthält.|
|Müssen Sie Intranetwebsites in Internet Explorer angezeigt werden|Bei Festlegung auf **Block**, interner Datenverkehr an den Microsoft Edge anstelle von Internet Explorer gesendet.|
|Der Vorabstart blockieren|Microsoft Edge Vorabstart öffnet Microsoft Edge als Hintergrundprozess während des Starts von Windows. Dadurch können die Leistung des Microsoft Edge und minimiert die Menge an Zeit, die zum Starten erforderlich. Microsoft Edge jedoch ausgeführt werden, wie ein Hintergrundprozess Geräte, die als angezeigt werden, die möglicherweise *nicht konform* in Ihre sichere Bewertungen.| 
|Standardsuch-engine|Wählen Sie Bing, Yahoo oder Google als die standardmäßige Suchmaschine für Microsoft Edge.|  

### <a name="user-data"></a>Benutzerdaten  
|Einstellung|Funktion|
|---|---|
|Hiermit werden Entwicklungstools blockiert|Hiermit werden Benutzer den Zugriff auf Entwicklertools. Microsoft Edge-Entwicklertools ermöglichen Benutzern das Erstellen und Debuggen von Webseiten|
|Microsoft Edge-Favoriten mit Internet Explorer synchronisieren|Synchronisieren Sie alle Favoriten von Microsoft Edge, Internet Explorer.| 
|Browserdaten beim Beenden löschen|Löschen Sie Verlauf, Cookies und zwischengespeicherte Dateien automatisch nach dem Schließen von Microsoft Edge.|
|Cookies verwenden|Cookies können Einstellungen für die Website oder des durchsucht Track-Benutzer Verhalten.|


## <a name="network-and-connectivity"></a>Die Netzwerk- und Konnektivitätsoptionen   
Konfigurieren Sie die Netzwerk- und Konnektivitätsoptionen Einstellungen für:    
* Bluetooth  
* Einschränkungen der Internet-Konnektivität  
* Proxy  
* WLAN-Profile  

### <a name="bluetooth"></a>Bluetooth  
|Einstellung|Funktion|
|---|---|
|Hiermit blockieren Sie Bluetooth|Blockieren Sie Geräte über Bluetooth.|
|Bluetooth-Erkennbarkeit blockieren|Blockieren Sie die Geräte als erkennbar über Bluetooth festgelegt wird.|
|Empfangen von Werbung über Bluetooth blockieren|Blockieren Sie Geräte empfangen von marketing Nachrichten und Ankündigungen per Bluetooth.|  
|Block Bluetooth Swift-Paar-Benachrichtigungen|Hiermit werden Benutzer vom Erhalt von Benachrichtigungen über Bluetooth-Gerät koppeln. SWIFT-Paar ermöglicht Benutzern das wissen, wann die Bluetooth-Geräten in Ihrer Nähe und Verbindung mit Windows 10 sind.|  

### <a name="internet-connectivity-restrictions"></a>Einschränkungen der Internet-Konnektivität  
|Einstellung|Funktion|
|---|---|
|Blockiert Internet Connection Sharing|Hiermit werden Benutzer mithilfe von anderen Geräten die Verbindung des Geräts Internet freigeben gemeinsame Nutzung der Internetverbindung.|
|Block mit Wi-Fi-sinnvoll automatisch eine Verbindung herstellen, um Hotspots zu öffnen.|Wählen Sie, wenn Sie Geräte automatisch eine Verbindung mit WLAN-Hotspots herstellen blockieren möchten.|
|Blockieren von datenverbindungen beim roaming|Blockieren Sie die Verwendung von datenverbindungen beim roaming Gerät ist.|  

### <a name="proxy"></a>Proxy  
|Einstellung|Funktion|
|---|---|
|Block automatische Erkennung von Proxyeinstellungen|Wenn Sie einen Proxy auf das Gerät, Netzwerk-Datenverkehr zu bewältigen eingerichtet haben, können Sie auswählen, ob Geräte automatisch die Proxyeinstellungen, wenn eine Verbindung besteht erkennen.|
|Proxyskript verwenden|Aktivieren Sie die Verwendung eines Proxy-Skripts für Ihre Geräte. Wenn Sie **zulassen** diese Einstellung, die Sie angeben möchten einer **Setupskriptadresse**.|
|Manuelle Proxyserverkonfiguration verwenden|Wenn Sie eine manuelle Proxy eingerichtet haben, können Sie hier Einstellungen dafür definieren. Wenn Sie **zulassen** diese Einstellung, die Sie bereitstellen möchten die **Proxyserveradresse**, **Port**, **Proxyausnahmen**, und ob **Proxyserver für lokale (Intranet) Verbindungen**.|  

### <a name="wi-fi-profiles"></a>WLAN-Profile  

|Einstellung|Funktion|
|---|---|
|Wählen Sie die Windows-WLAN-Profilen, die sie dieser Gruppe zuweisen.|Eine Liste der WLAN-Profile, die Sie erstellt haben in diesem Abschnitt angezeigt und können Sie zuweisen. Sichtbare Details umfassen die **Profilname**, **Netzwerkname (SSID)**, **Sicherheitstyp**, und **Beschreibung**. 

> [!NOTE]
> Konfigurieren einer WPA-2 Enterprise Wi-Fi-Netzwerk über die [vollständige WLAN-Profil-Verwaltungsfunktionen in Intune](https://docs.microsoft.com//intune/wi-fi-settings-import-windows-8-1). Sie können Intune auch verwenden, einrichten [SCEP](https://docs.microsoft.com/intune/certificates-scep-configure) und [PKI](https://docs.microsoft.com/intune/certficates-pfx-configure) Integration.   

## <a name="printer"></a>Drucker   
Konfigurieren Sie Einstellungen zum Zulassen von Druckerzugriff von School-Geräte.    

|Einstellung|Funktion|
|---|---|
|Druckerliste|Erstellen Sie eine Liste von Druckern, die Sie für Geräte der Schüler verfügbar machen möchten. Geben Sie den Druckerhostnamen ein. Ein Beispiel für einen formatierten Hostnamen ist *printer1.contososd.edu*.| 
|Standarddrucker angeben|Stellen Sie einen Drucker als Standardoption Drucker auf Geräten zur Verfügung. Geben Sie den Druckerhostnamen ein, wie in Ihrem **Druckerliste**.|  
|Hinzufügen neuer Drucker blockieren|Hiermit blockieren Sie Gruppen, eine Verbindung mit ihren Geräten herstellen Neuer Drucker.|  


## <a name="security"></a>Sicherheit  
Konfigurieren Sie Sicherheitseinstellungen für Windows Defender und Windows SmartScreen.  

### <a name="windows-defender"></a>Windows Defender  
> [!NOTE]
> Einige Windows Defender-Einstellungen sind verfügbar, nur auf die [Mandanten](edu-tenant-general-settings.md) Ebene und werden nicht im Portal angezeigt.  

|Einstellung|Funktion|
|---|---|
|Benutzerzugriff auf Windows Defender-Einstellungen blockieren|Hiermit werden Benutzer von Windows Defender-Einstellungen auf dem Gerät ändern.|
|Aktivieren der Überwachung in Echtzeit|Aktivieren der always on-Überprüfung für Schadsoftware, Spyware und andere Bedrohungen.|
|Aktivieren der Verhaltensüberwachung|Aktivieren von Windows Defender auf bestimmte bekannte Muster verdächtiger Aktivitäten zu überprüfen.|
|Benutzer auffordern, verdächtige Dateien an Microsoft senden|Wählen Sie Dateien automatisch an Microsoft zur weiteren Analyse zu senden.|
|Typ der durchzuführenden systemüberprüfung|Wählen Sie, wenn Windows Defender einen schnell-Scan, eine vollständige Überprüfung oder keine Überprüfung der Geräte ist.|
|Zeit für tägliche schnellüberprüfung|Wählen Sie welche Stunde des Tages Windows Defender eine tägliche schnellüberprüfung ausgeführt wird.|
|Alle heruntergeladenen Dateien überprüfen|Automatisch alle heruntergeladene Dateien auf Malware zu überprüfen.|
|Überprüfen Sie Skripts zur Ausführung in Microsoft-Webbrowsern|Überprüfen Sie alle Skripts, die eine Website versucht, die in Microsoft Edge und Internet Explorer ausgeführt.|
|Wechseldatenträger während vollständiger Scans zu überprüfen|Einschließen von Wechseldatenträgern, z. B. USB-Sticks, während vollständiger Scans.|
|Überprüfen Sie über das Netzwerk geöffnete Dateien|Überprüfen Sie alle Dateien, die von Benutzern von Websites geöffnet werden, bei der Verwendung des Netzwerks.|
|Remote Scan-Ordner während der vollständigen Überprüfung|Überprüfen Sie alle Ordner an Remotestandorten während vollständiger Scans.|
|Archivdateien überprüfen|Überprüfen Sie Archivdateien, z. B. ZIP- oder RAR.|
|Eingehende e-Mails überprüfen|Überprüfen Sie alle e-Mail-Nachrichten, die über das Netzwerk empfangen.|
|Scannen Sie nach Schadsoftware beim Öffnen von Dateien oder Programme|Suchen Sie nach Malware, wenn eine Datei oder ein Programm öffnet, und Benutzer zu verdächtigen Aktivitäten warnen.|
|Tag vor dem Löschen in Quarantäne befindlicher Schadsoftware| Legen Sie die Anzahl der Tage, die eine betroffene Datei gespeichert wird. Nach dieser Anzahl von Tagen wird die Datei gelöscht. Wenn beispielsweise beim Wert 0 wird die Datei sofort gelöscht wird.|
|Anti-Malware-aktualisierungshäufigkeit festlegen|Wählen Sie die Häufigkeit sollte Windows Defender überprüfen und Herunterladen von Antischadsoftware-Updates.|
|Potenziell unerwünschte Software protection|Windows Defender warnt den Benutzer aus, und Blöcke potenziell unerwünschte Software, die versucht, sich selbst auf Geräten installiert.|
|Verdächtige Dateien blockieren|Wenn diese Einstellung konfiguriert ist, werden Windows Defender Antivirus aggressiver zum Blockieren und Scannen verdächtige Dateien zu identifizieren. Wenn nicht konfiguriert ist, wird es blockieren und Scannen weniger häufig. Sie können auswählen, **nicht konfiguriert**, **hohe**, **hoher Zuwachs**, und **Nulltoleranz**. **Hohe** aggressiv blockiert, unbekannte Dateien bei gleichzeitiger Minimierung der Auswirkungen auf die Leistung. **Hoher Zuwachs** aggressiv blockiert, unbekannte Dateien, aber die Leistung negativ beeinträchtigt werden kann. **Nulltoleranz** blockiert alle unbekannte Dateien ausgeführt wird.|
|Cloudbasierter Schutz aktivieren|Erhalten Sie Echtzeit-Schutzfunktion aus, wenn Windows Defender Informationen über potentielle Sicherheitsrisiken an Microsoft sendet. Dieses Feature funktioniert am besten mit **werden Benutzer aufgefordert, verdächtige Dateien an Microsoft senden** festgelegt werden, um Dateien zu senden.|
|Aktionen für erkannte schadsoftwarebedrohungen|Windows Defender wird automatisch unter Quarantäne gestellt erkannten Schadsoftware.|
|Aktivieren Sie Netzwerkinspektionsdienst|Schützt Geräte vor netzwerkbasierten Sicherheitslücken. Verwendet die Signaturen bekannter Sicherheitsrisiken aus dem Microsoft Endpoint Protection Center, um zu erkennen und Blockieren von schädlichen Datenverkehr.|
|Dateien mit diesen Erweiterungen von Überprüfungen und Echtzeitschutz ausschließen|Definieren Sie die Typen von Dateien, die Benutzer öffnen können, ohne die Überprüfung auf sicherheitsbedrohungen.
|Prozesse bei Überprüfungen und Echtzeitschutz ausschließen|Definieren Sie die Typen von Prozessen, die Benutzer ausführen können, ohne die Überprüfung auf sicherheitsbedrohungen.
|Verzeichnisse von Überprüfungen und Echtzeitschutz ausschließen|Definieren Sie die Speicherorte, die Benutzer zugreifen können, ohne die Überprüfung auf sicherheitsbedrohungen.|   

### <a name="windows-smartscreen"></a>Windows SmartScreen  

|Einstellung|Funktion|
|---|---|
|Außerkraftsetzen von SmartScreen-Warnungen zu Websites den Benutzer blockieren|Hiermit werden Benutzer daran wird ignoriert, und den Zugriff auf blockierten Websites vom SmartScreen-Filter.|
|Hiermit werden Benutzer daran, Außerkraftsetzen von SmartScreen-Warnungen zu Downloads aus dem web|Block Schülern und Studenten wird ignoriert und nicht überprüfte Dateien, denen SmartScreen-Filter Umstand herunterladen.|
|Aktivieren des SmartScreen-Filter für nicht erkannte apps und Dateien überprüfen|Ermöglicht die SmartScreen-Filter Geräte zu schützen, indem Sie für nicht erkannte apps überprüfen.|
|Außerkraftsetzen von SmartScreen-Warnungen zu apps und Dateien Benutzer blockieren|Block Schließen von SmartScreen-Warnungen zu potenziell schädlicher Dateien und apps von Schüler/Studenten.|


## <a name="shared-devices"></a>Gemeinsam genutzte Geräte  
Konfigurieren Sie Einstellungen, die steuern, wie Lehrer und Schüler/Studenten Geräte freigeben.

|Einstellung|Funktion|
|---|---|
|Geräte für gemeinsame Nutzung optimieren|Konfiguriert die empfohlene Einstellungen für freigegebene Geräte, wie z. B. Strom und updateverwaltung. Können mehrere Schüler/Studenten oder Lehrern bei demselben Gerät anmelden.|
|Gastbenutzer blockieren| Diese Option ist nur verfügbar, wenn Sie aktivieren **Geräte für gemeinsame Nutzung optimieren**. Blockieren Sie Gastbenutzer nicht anmelden, gemeinsam genutzte Geräte. Wenn blockiert, können nur Domänenbenutzer anmelden.|  
|Blockieren des Zugriffs auf den lokalen Speicher| Diese Option ist nur verfügbar, wenn Sie aktivieren **Geräte für gemeinsame Nutzung optimieren**. Hiermit werden Benutzer Dateien auf dem Gerät speichern. Wenn blockiert, können Benutzer nur in der Cloud speichern. | 
|Schnelle benutzerumschaltung blockieren|Können Sie Benutzer schnell zwischen Benutzerkonten über das Startmenü zu wechseln.|  


### <a name="remove-built-in-apps"></a>Entfernen von integrierten apps  

Wenn Sie auswählen, um Geräte für gemeinsame Nutzung optimieren, werden diese apps von Lehrkräften und Schülern/Studenten entfernt Computer:

* Mixed Reality-Viewer  
* Weather
* Desktop-App-Installer
* Tipps
* Mein Büro
* Solitaire-Auflistung
* Mobile-Pläne
* Windows-Feedback-Hub
* Xbox
* Groove Music
* Mail
* Kalender
* Skype  

## <a name="updates-and-upgrade"></a>Updates und Upgrades
Konfigurieren Sie, wie Geräte Updates und Upgrades erhalten.    

### <a name="updates"></a>Updates  

|Einstellung|Funktion|
|---|---|
|Branch-Bereitschaftsniveau|Wählen Sie, wenn Geräte für Unternehmen für Windows-Updates für Current Branch oder Current Branch sind.|
|Konfigurieren Sie wie und wann Updates installiert werden|Legen Sie die Updates und Wartungszeitraum für die Installation von Updates.|
|Tage Funktionsupdates zurückstellen, nachdem sie verfügbar sind (0 – 365) sind|Legen Sie, wie viele Tage warten, bis eine Funktion angewendet werden, zu aktualisieren, nachdem er wieder verfügbar ist. Wenn beispielsweise auf 0 Tage, ein featureupdate, das nur verfügbar geworden ist direkt an Ihre Geräte angewendet werden sollen.|
|Tage qualitätsupdates zurückstellen, nachdem sie verfügbar sind (0-30) sind|Legen Sie, wie viele Tage warten, bis eine Qualität anwenden zu aktualisieren, nachdem er wieder verfügbar ist. Wenn beispielsweise auf 0 Tage, ein qualitätsupdate, das nur verfügbar geworden ist direkt an Ihre Geräte angewendet werden sollen.|
|Deinstallieren Sie Tage vor dem Löschen von Dateien (2-60)|Nach dem Installieren von Features aktualisieren, behält Windows der Dateien erforderlich, deinstallieren Sie den neuen Build aus, und klicken Sie auf der vorherigen App zurückgesetzt. Festlegen Sie, wie viele Tage warten, bis Sie diese Dateien zu deinstallieren.|
|Anhalten des Windows-Updates blockieren|Blockieren Sie Benutzerzugriff auf das Feature für Updates anhalten.|
|Zulassen von Schülern und Studenten vorab veröffentlichten Features von Windows 10 finden Sie unter|Wählen Sie aus, wenn ein Schüler/Studenten vorabfeatures für Einstellungen, vorabfeatures für Einstellungen und Versuche oder keine vorabfeatures sehen können.|
|Übermittlungsoptimierungsmodus|Wählen Sie, wie Sie auf Geräten zur Verfügung stellen möchten.|  

### <a name="upgrade"></a>Upgrade/Aktualisieren
|Einstellung|Funktion|
|---|---|
|Windows-Edition zu aktualisieren.| Aktualisieren Sie die Geräte in dieser Gruppe auf eine andere Edition von Windows 10 ein. Wählen Sie die **Edition Upgrade auf** , und geben Sie die **Produktschlüssel**.|
|Wechseln Sie aus dem S-Modus|S-Modus ist bereits als Windows 10 S bezeichnet, ist eine sicherere Version von Windows 10. Mit dieser Einstellung können Benutzer ihre Geräte aus dem S-Modus zu wechseln. **Behalten Sie im S-Modus** verhindert, dass sie den Schalter. Im S-Modus können Lehrer und Schüler/Studenten nur mit Microsoft Edge und Download von apps aus Microsoft Store durchsuchen.|

## <a name="user-experience"></a>Benutzerfreundlichkeit   
Konfigurieren Sie die Installationsoptionen für:   

  * Geräteeinschränkungen  
  * Sperrbildschirm und desktop  
  * App "Einstellungen"  
  * Startmenü  

### <a name="device-restrictions"></a>Geräteeinschränkungen  

|Einstellung|Funktion|
|---|---|
|Kamera blockieren|Sperrt die Verwendung der Kamera des Geräts zugreifen.|
|Block OneDrive-dateisynchronisierung|Hiermit blockieren Sie das Gerät synchronisieren von Dateien in OneDrive.|
|Wechselmedien blockieren|Blockiert die Verwendung von Wechselmedien wie USB-Laufwerke, SD-Karten und externen Festplatten.|
|Cortana blockieren|Hiermit blockieren Sie Cortana, das digitale Assistent von Windows 10, die Fragen zu beantworten und Ausführen von Aufgaben können integriert.|
|Ortungsdienste blockieren|Blockieren von apps mithilfe von ortungsdiensten auf den Gerätestandort zuzugreifen.|  
|Beenden von Aufgaben im Task-Manager blockieren|Hiermit werden Benutzer von der Verwendung von Task-Manager ein Programm, Prozess oder Vorgang zum Schließen gezwungen.|
|Blockieren der Änderung der Einstellungen für Datum und Uhrzeit|Hiermit werden Benutzer daran, Änderungen der Datums- und Uhrzeiteinstellungen.|
|Änderung von spracheinstellungen blockieren|Hiermit werden Benutzer daran, die Sprache des Geräts zu ändern.|
|Geräteregionseinstellungen blockieren|Hiermit werden Benutzer an der Änderung von regionseinstellungen, z. B. Land und Sprache.|
|Ändern von Energie-und energiesparmoduseinstellungen blockieren|Hiermit werden Benutzer daran, Änderungen an Power und energiesparmoduseinstellungen.|
|Senden von Diagnosedaten|Definieren Sie, ob zum Erfassen und senden anonyme Nutzungsdaten an Microsoft zur Verbesserung von Windows.|  

### <a name="lock-screen-and-desktop"></a>Sperrbildschirm und desktop  

|Einstellung|Funktion|
|---|---|
|Set benutzerdefiniertes Hintergrundbild für Sperrbildschirm|Konfigurieren eines benutzerdefinierten Hintergrundbilds für die Anmeldeseite angezeigt. Sie können eine JPG- oder PNG kleiner als 20 MB Größe auswählen.|
|Set benutzerdefiniertes Hintergrundbild für desktop|Konfigurieren Sie ein benutzerdefiniertes Hintergrundbild auf dem Desktop. Sie können eine JPG- oder PNG kleiner als 20 MB Größe auswählen.|
|Windows-Blickpunkt blockieren|Hiermit blockieren Sie alle Features von Windows-Blickpunkt auf diesen Geräten.|
|Benachrichtigungen auf Sperrbildschirm blockieren|Hiermit blockieren Sie Benachrichtigungen auf dem Bildschirm ein gesperrtes Gerät angezeigt werden.|
|Block Cortana auf Sperrbildschirm|Verhindern Sie, dass Benutzer den Zugriff auf Cortana über den Sperrbildschirm.|

### <a name="settings-app"></a>App "Einstellungen"  

|Einstellung|Funktion|
|---|---|
|Blockieren des Zugriffs auf die Einstellungs-app|Blockieren Sie Benutzerzugriff auf die gesamte Einstellungen-app. Wählen Sie aus den anderen Einstellungen in diesem Abschnitt, um nur die Teile der app zu blockieren.
|Systemeinstellungen|Blockieren Sie die Anzeige, Benachrichtigungen, apps, energieeinstellungen.|
|Geräte|Blockieren Sie Bluetooth, Drucker und vieles mehr.|
|Netzwerk und Internet|Block WLAN, flugzeugmodus und VPN.|
|Personalization|Block-Hintergrund, Sperrbildschirm und Farbe bearbeiten.|
|Konten|Blockieren Sie Benutzerkonten, e-Mail, Synchronisierung, Arbeit und andere Personen.|
|Zeit und Sprache|Blockieren Sie die Größe, Region und Datum.|
|Erleichterte Bedienung|Blockieren Sie die Sprachausgabe und Bildschirmlupe, hoher Kontrast.|
|Datenschutz|Standort blockieren und Kamera.|
|Update und Sicherheit|Blockieren Sie Windows Update, Wiederherstellung und Sicherung.|  
|Apps|Blockieren Sie deinstallieren, Standardwerte und optionalen Features.|
|Spiele|Blockieren Sie Spiele Leiste, DVR, Übertragungen und Spielmodus.|  

### <a name="start-menu"></a>Startmenü  

|Einstellung|Funktion|
|---|---|
|Startmenügröße erzwingen|Definieren Sie, ob im Startmenü, Vollbildmodus angezeigt werden erzwungen.|
|Block Sprunglisten im Startmenü aus der Anzeige zuletzt geöffnete Programme|Blockieren Sie Sprunglisten im Startmenü angezeigt werden, und deaktivieren Sie der entsprechende Schalter in der Einstellungs-app.|
|Block Anzeige zuletzt hinzugefügter apps im Menü "Start"|Zuletzt hinzugefügten Block apps, nicht angezeigt, im Startmenü.|
|Zeigt die am häufigsten verwendeten apps im Startmenü blockieren|Blockieren Sie die am häufigsten verwendeten apps nicht angezeigt, im Startmenü.|
|App-Liste im Startmenü blockieren|Hiermit blockieren Sie die Liste aller apps auf dem Gerät nicht angezeigt, im Startmenü.|
|Ein-/ ausschaltmenü im Startmenü blockieren|Blockieren Sie den ein-/ ausschaltmenü (z. B. neu starten, Herunterfahren nach unten) nicht angezeigt, im Startmenü.|
|Blockieren der Benutzerkachel im Startmenü|Hiermit blockieren Sie die aktuellen Informationen des Benutzers im Startmenü angezeigt wird.|
|Blockieren Sie Optionen, die aus der Benutzerkachel im Startmenü|Sie können **kontoeinstellungen ändern**, **Sperre**, und **Abmelden**.|
|Wählen Sie im Menü "Start" angezeigten Ordner|Sie können **Datei-Explorer**, **Einstellungen**, **Dokumente**, **Downloads**, **Musik**,  **Bilder**, **Videos**, **Heimnetzgruppe**, **Netzwerk**, und **persönlichen Ordner**.|
|Benutzerdefiniertes startmenülayout anwenden|Wenden Sie ein benutzerdefiniertes startmenülayout mithilfe einer XML-Datei. Sie können eine XML-Datei ein, der kleiner als 2 MB Größe hochladen.|
|Websites als Kacheln an Startmenü anheften|PIN Websites als Kacheln an das Startmenü, die eine XML-Datei. Sie können eine XML-Datei ein, der kleiner als 2 MB Größe hochladen.|  



## <a name="next-steps"></a>Nächste Schritte  
Konfigurieren Sie Ihre Gruppe, die app und die Einstellungen für Geräte in Intune for Education-Portals ein. Wenn Sie noch nicht erfolgt, fahren Sie mit [express-Konfiguration](edu-express-config-settings-windows.md) und Ihrer Schule/Universität mit Microsoft-empfohlenen Einstellungen einrichten.  

Benötigen Sie Hilfe bei der Verwaltung von Geräten? [Weisen Sie Administratoren für](group-admin-delegate.md) in Deiner Schule oder Hochschule helfen Ihnen beim Verwalten von geräteeinstellungen.  Sie können auch [erfahren Sie mehr über die vollständige Verwaltungsfunktionen für Windows 10-Einstellungen](https://docs.microsoft.com/intune/deploy-use/windows-10-policy-settings-in-microsoft-intune) in Intune verfügbar.  
