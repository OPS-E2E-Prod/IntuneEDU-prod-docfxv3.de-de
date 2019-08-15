---
title: Neuheiten
titleSuffix: Intune for Education
description: Erfahren Sie, was vor kurzem in InTune for Education veröffentlicht wurde.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/18/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 7d8dfd82-8cee-4874-85f6-edaf84e49c4c
searchScope:
- IntuneEDU
.#ms.devlang: ''
ms.openlocfilehash: 258768b919d824e511452c3974b2c86c61c87a3d
ms.sourcegitcommit: 1791319c6f8a8fb2c35cf9620ca4785c421b2071
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/19/2019
ms.locfileid: "68329425"
---
# <a name="whats-new-in-intune-for-education"></a>Neues in InTune for Education
Erfahren Sie mehr über die Neuerungen in InTune for Education. Informieren Sie sich über bevorstehende Änderungen, Produkt Hinweise und Features aus früheren Versionen.


## <a name="july-2019"></a>2019. Juli  

### <a name="perform-bulk-rename"></a>Massen Umbenennen ausführen  
Benennen Sie jeweils bis zu 100 Geräte um. Wenn Sie eine Massenauswahl treffen möchten, können Sie Geräte in der Geräteliste manuell auswählen oder die **STRG** -Taste oder die **Befehls** Taste gedrückt halten, um mehrere Geräte gleichzeitig auszuwählen.  

Anschließend können Sie eine Benennungs Vorlage auf die Gruppe ausgewählter Geräte anwenden, die ein benutzerdefiniertes Präfix enthält, das von einem eindeutigen Bezeichner angefügt wird. Bei dem eindeutigen Bezeichner kann es sich um eine Seriennummer, einen Counter oder eine WLAN-MAC-Adresse handeln.  

 
 ![Screenshot der Seite "Geräte", Massen umbenennen mit aktivierten Counter-Bezeichnern.](./media/edu-bulk-rename-1907.png)  


 ![Screenshot der Geräteseite, Massen Umbenennung wird ausgeführt, mit ausgewählter Seriennummer.](./media/edu-bulk-rename-1907-01.png)   


## <a name="june-2019"></a>2019. Juni  

### <a name="perform-bulk-actions"></a>Ausführen von Massenaktionen 
Führen Sie bestimmte Remote Aktionen auf bis zu 100 Geräten gleichzeitig aus.  Wenn Sie eine Massenauswahl treffen möchten, können Sie Geräte in der Geräteliste manuell auswählen oder die **STRG** -Taste oder die **Befehls** Taste gedrückt halten, um mehrere Geräte gleichzeitig auszuwählen. 
 
 ![Beispiel Abbildung mehrerer ausgewählter Geräte und Bestätigung des Massen Neustarts.](./media/1906-remote-bulk.png)  

InTune for Education werden die Massen Funktionalität für die folgenden Geräte Aktionen unterstützen:  

* Neu starten  
* Wiederherstellung der Herstellerstandards  
* Synchronisierung  
* Autopilot zurücksetzen  
* Löschen   

 ![Beispiel Bild der Bestätigung der Massen Synchronisierung.](./media/1906-remote-bulk-selection.png)  

### <a name="easier-migration-to-intune-for-education-licenses"></a>Einfachere Migration zu InTune for Education Lizenzen  
Nachdem Sie sich für InTune for Education angemeldet haben, konfiguriert InTune automatisch einige Einstellungen in der Gruppe "alle Geräte" mit Werten, die für Schulen empfohlen werden. Wenn Sie nun InTune for Education einem Mandanten hinzufügen, der bereits über ein InTune-Abonnement verfügt, werden die empfohlenen Richtlinien angezeigt, aber InTune weist Sie nicht automatisch zu. Diese Änderung stellt sicher, dass keine unerwünschten Änderungen an Ihrer vorhandenen Umgebung vorgenommen werden.  

### <a name="new-permissions-for-assigned-group-admins"></a>Neue Berechtigungen für zugewiesene Gruppen Administratoren  
Die integrierte Rolle "Schul Administrator" in InTune verfügt jetzt über Berechtigungen zum Erstellen, lesen, aktualisieren und löschen (CRUD) für verwaltete apps. Dieses Update bedeutet, dass Sie, wenn Sie in InTune for Education als Gruppenadministrator zugewiesen sind, nun die IOS-MDM-Push-Zertifikat, IOS MDM-Server Token und IOS VPP-Token zusammen mit [allen vorhandenen Berechtigungen](https://docs.microsoft.com/intune-education/group-admin-delegate#group-admin-permissions)erstellen, anzeigen, aktualisieren und löschen können. Wechseln Sie zu den Mandanten **Einstellungen** > **IOS-Geräteverwaltung**, um diese Aktionen auszuführen.  

### <a name="new-deployment-documentation"></a>Neue Dokumentation zur Bereitstellung  
Im [Abschnitt](https://docs.microsoft.com/intune-education/add-devices-windows) zur Registrierung in unserer Dokumentation finden Sie neue Informationen zum Vergleichen von PCs der Einrichtung und Windows Autopilot basierend auf der Umgebung und den Setup Anforderungen Ihrer Schule. Verwenden Sie diese Informationen, um zu entscheiden, wann die einzelnen Optionen für die Geräte Einrichtung verwendet werden sollen. 

## <a name="may-2019"></a>Mai 2019   

### <a name="distinguish-between-online-and-offline-licensed-microsoft-store-for-education-apps"></a>Unterscheidung zwischen Online-und Offline lizenzierter Microsoft Store für Bildungseinrichtungen-apps   

Sie können sehen, ob eine Microsoft Store for Education-App über eine Online-oder offline Lizenz verfügt. In InTune for Education wird der Lizenztyp in der Express-Konfiguration und auf der Detailseite der App angezeigt, sodass Sie Apps für die richtigen Gruppen einfacher verwalten und bereitstellen können. Apps mit Online Lizenzen werden installiert, nachdem sich ein Benutzer an einem Gerät angemeldet hat und eine Verbindung zu Microsoft Store benötigt, um zu verwenden. Apps mit Offline Lizenzen werden ohne Benutzeranmeldung installiert und benötigen keine Verbindung mit Microsoft Store, um zu verwenden.  

### <a name="new-ios-settings"></a>Neue IOS-Einstellungen  

Es wurden neue Einstellungen hinzugefügt, um Ihnen mehr Kontrolle über die IOS-App Classroom zu bieten.  

### <a name="apply-an-ios-device-naming-template"></a>Anwenden einer Vorlage für eine IOS-Gerätebenennung  

Wir haben neue Benennungs Einstellungen hinzugefügt, die Ihnen helfen, ihre IOS-Geräte zu gruppieren und zu identifizieren. Beim Einrichten der IOS-Registrierung und des MDM-Server Tokens benennen InTune for Education jedes Ihrer Geräte automatisch mit ihrer eindeutigen Seriennummer des Geräts. Anschließend können Sie dem Präfix einen benutzerdefinierten Namen hinzufügen, z. b. "Math1". Wenn Sie den Namen anpassen, wird die Seriennummer des Geräts an das Ende des Geräts angefügt. Beispiel: Contoso012a345b67c8. Wenn Sie eine Benennungs Vorlage für ein MDM-Server Token konfigurieren oder aktualisieren, werden alle diesem Token zugeordneten Geräte umbenannt – sowohl vorhandene als auch registrierte Geräte, die nach der namens Vorlage registriert sind. 

## <a name="april-2019"></a>2019. April  

### <a name="updated-ios-settings-names-and-added-more-tooltips"></a>Die IOS-Einstellungs Namen wurden aktualisiert und weitere Quick Infos hinzugefügt.  
Wir haben viele der IOS-Einstellungs Namen, Quick Infos und Kategorien in InTune for Education überarbeitet, damit die Einstellungen leichter zu finden und zu verstehen sind. Eine ausführliche Liste dieser Einstellungen finden Sie unter [IOS-Geräteeinstellungen in InTune for Education](all-edu-settings-ios.md).  

### <a name="refined-list-of-ios-settings-in-express-configuration"></a>Liste mit den IOS-Einstellungen in der Express-Konfiguration   
Wir haben die [Liste der IOS-Einstellungen in der Express-Konfiguration](edu-express-config-settings-ios.md) angepasst, damit Sie Ihre Geräte und Gruppen noch schneller einrichten können. Sie werden feststellen, dass einige Einstellungen aus der Express Konfiguration verschoben und neue Einstellungen in verschoben wurden. Die entfernten Einstellungen können weiterhin in **Gruppen** > **Einstellungen** > **IOS-Geräteeinstellungen**konfiguriert werden. Eine vollständige Liste der Geräteeinstellungen in InTune for Education finden Sie unter [IOS-Geräteeinstellungen](all-edu-settings-ios.md) und [Windows 10-Geräteeinstellungen](all-edu-settings-windows.md).  

###  <a name="new-settings-for-windows-10-devices"></a>Neue Einstellungen für Windows 10-Geräte  
Es gibt mehrere neue Windows 10-Geräteeinstellungen. Hier sind nur einige der Einstellungen aufgeführt, die Sie jetzt in InTune for Education konfigurieren können:
* Windows Update Benachrichtigungen: Mit dieser Einstellung können Sie auswählen, ob Benutzern Benachrichtigungen zu Windows-Updates angezeigt werden sollen.  
* Manuelles Windows Update: Mit dieser Einstellung können Sie auswählen, ob Benutzer Zugriff auf die Windows Update Scan-, Download-und Installations Features haben.  


## <a name="february-2019"></a>2019. Februar  

### <a name="set-custom-wallpaper-and-lock-screen-images-for-your-ios-devices"></a>Festlegen von benutzerdefinierten Hintergrundbildern und Sperrbildschirm Bildern für Ihre IOS-Geräte  
Sie können jetzt InTune for Education verwenden, um benutzerdefinierte Bildschirme und Sperrbildschirm Bilder auf Schul Geräten festzulegen. Wechseln Sie zum Hochladen von Images zu **Gruppen** > **IOS-Geräteeinstellungen** > **Hintergrundbild und Sperrbildschirm Bilder**.  

   ![Screenshot der IOS-Geräteeinstellungen, benutzerdefinierter Hintergrundbilder und Sperrbildschirm Bilder](./media/ios-1901-custom-image-settings.png)  


## <a name="january-2019"></a>2019. Januar  

### <a name="set-up-ios-devices-with-shared-ipad-features"></a>Einrichten von IOS-Geräten mit freigegebenen iPad-Features
Wenn Sie Einstellungen in InTune for Education für die IOS-Geräteregistrierung konfigurieren, haben Sie jetzt die Möglichkeit, ihre IOS-Geräte für die Registrierung mit aktivierten, aktivierten iPad-Features zu konfigurieren.  Gemeinsam genutztes iPad ist eine IOS-Funktion, bei der Schüler/Studenten und Lehrkräfte sich mit einer verwalteten Apple-ID bei Schul Geräten anmelden müssen. Sie können sich bei jedem aktivierten Gerät in der Schule anmelden und von dort aus auf gespeicherte und laufende Arbeitsaufgaben, Apps und Aufgaben zugreifen. Weitere Informationen zum freigegebenen iPad in InTune for Education finden Sie unter [Shared iPad Configuration](setup-ios-device-management.md#shared-ipad-configuration).  

### <a name="new-settings-for-windows-10-devices"></a>Neue Einstellungen für Windows 10-Geräte  
Wir haben neue Einstellungen hinzugefügt, mit denen Sie mehr Kontrolle über Bereiche wie Sicherheit, Windows-Updates, Geräte Anmeldung und Browsererfahrung erhalten. Hier sind nur einige der neuen Einstellungen aufgeführt, die Sie in diesem Monat sehen werden:  

* **Konfigurieren Sie die bevorzugte Azure Active Directory Mandanten Domäne**: Diese Einstellung ermöglicht es Studenten, sich bei einem Gerät ohne einen Mandanten Domänen Namen anzumelden. Schüler und Studenten können sich schnell und einfach mit ihrem Alias anmelden.  

* **Seite "neue Registerkarte Konfigurieren**": Mit dieser Einstellung können Sie die Seite auswählen, die geöffnet wird, wenn Studenten in Microsoft Edge eine Registerkarte hinzufügen. Neue Registerkarten können eine leere Seite oder eine benutzerdefinierte Seite öffnen, z. b. die Startseite Ihrer Schule.  

* **Außerhalb des S-Modus wechseln**: Mit dieser Einstellung können Administratoren Geräte aus Windows 10 im s-Modus wechseln oder verhindern, dass Schüler/Studenten ihre eigenen Geräte außerhalb des s-Modus wechseln.    

### <a name="updated-windows-settings-names-and-added-useful-tooltips"></a>Aktualisierte Windows-Einstellungs Namen und nützliche Quick Infos  
Wir haben viele der Einstellungs Namen und Quick Infos in InTune for Education überarbeitet, um Sie leichter finden und verstehen zu können. Weitere Informationen zu den einzelnen Einstellungen finden Sie unter [Windows 10-Geräteeinstellungen in InTune for Education](all-edu-settings-windows.md).  

### <a name="rename-windows-devices"></a>Windows-Geräte umbenennen  
Benennen Sie Windows 10-Geräte (Version 1803 oder höher) Remote über das InTune for Education-Portal um. Wechseln Sie zum Umbenennen zu **Geräte** , und wählen Sie ein Gerät aus, > **Gerät umbenennen**. Sie können ein Gerät auch über die Seite mit den **Geräte Details** umbenennen.  

## <a name="november-2018"></a>2018. November  

### <a name="remote-autopilot-reset"></a>Remote Autopilot Reset 
Sie können jetzt Autopilot Reset per Remote Zugriff über das InTune for Education-Portal aufrufen. Autopilot Reset entfernt alle Benutzerdaten, einschließlich Benutzer installierter apps und persönlicher Einstellungen, und hält das Gerät bei InTune registriert, damit das Gerät mit allen aktuellen apps, Richtlinien und Einstellungen auf dem neuesten Stand gehalten wird. Mit dieser Funktion können Sie die PCs von Studenten in einem Massen Vorgang schnell zurücksetzen und neu konfigurieren, um Sie für ein neues Schul Jahr vorzubereiten. Weitere Informationen zum Zurücksetzen von Autopilot [finden Sie hier](autopilot-reset.md).

### <a name="new-features-for-ios-management"></a>Neue Features für die IOS-Verwaltung
- In InTune for Education werden nun Standortinformationen für Ihre Apple School Manager-VPP-Token angezeigt, sodass Sie Ihre VPP-Token sowohl aus InTune for Education als auch aus dem Apple School Manager problemlos identifizieren können. 
- Sie können Ihre VPP-Token in InTune for Education für die einfache Bezeichnung und Organisation versehen. 
- Die Registrierung ist jetzt für Ihre IOS-Geräte noch schneller, wenn Sie ein MDM-Server Token einrichten. InTune for Education werden die Registrierungs Einstellungen automatisch konfiguriert, sodass die dem MDM-Server Token zugeordneten Geräte weniger Setup-Assistenten-Bildschirme enthalten, die durchlaufen werden können. 
 
### <a name="delete-device"></a>Gerät löschen
Sie können jetzt ein Gerät im InTune for Education-Portal löschen. Löschen eines Geräts:
- hebt die Registrierung des Geräts bei InTune auf.
- entfernt den Gerätedaten Satz aus Azure Active Directory, damit das Gerät nicht mehr Teil der Umgebung ist.
 
### <a name="immersive-reader-for-all-tenants"></a>Immersiver Reader für alle Mandanten 
Ihr Windows Store for Education-Inventar erhält unbegrenzte Lizenzen für den immersiven Reader, wenn Sie sich für InTune for Education registrieren. Der immersive Reader ist ein Lerntool, das eine Lesefunktion mit Barrierefreiheit und Begriffen für Lernmodule in allen Fällen und Fähigkeiten erstellt. Weitere Informationen zu immersiven Lesern [finden Sie hier](https://www.onenote.com/learningtools).
 
### <a name="effective-policy-page"></a>Effektive Richtlinien Seite
Auf der Seite effektive Richtlinie werden alle apps und Einstellungen angezeigt, die auf eine Benutzer-/Geräte-Kombination basierend auf Gruppenmitgliedschaften angewendet werden. Auf dieser Seite können Sie Einstellungen sehen, die möglicherweise in Konflikt stehen, und die Probleme beheben. Die Seite effektive Richtlinie kann auf zwei Arten erreicht werden:
- Klicken Sie auf einen Benutzer > wechseln Sie **zu Benutzer Details** > Wählen Sie ein Gerät aus, mit dem der Benutzer vor kurzem eingeklickt ist.
- Klicken Sie auf ein Gerät > wechseln Sie **zu Geräte Details** > Wählen Sie einen Benutzer aus, der sich vor kurzem auf diesem Gerät angemeldet hat.



## <a name="july-2018"></a>Juli 2018 

### <a name="all-new-support-for-ios-classroom-devices"></a>Alle neuen Unterstützung für IOS-Classroom-Geräte  

InTune for Education unterstützt jetzt die IOS-Geräteverwaltung im Classroom. Wir haben InTune for Education neue Features und Seiten hinzugefügt, um den Setup-und Verwaltungsprozess für alle Beteiligten zu vereinfachen. Über das Dashboard verfügen Sie über alles, was Sie zum erfolgreichen einrichten, konfigurieren und Registrieren von Geräten benötigen.  

* Einrichten der IOS-Geräteverwaltung: Wir haben eine neue Seite mit einer [Schritt-für-Schritt-Anleitung](setup-ios-device-management.md) zum schnellen verbinden Ihrer Apple-Konten mit InTune for Education hinzugefügt. Auf Bildschirm Indikatoren können Sie die erforderlichen und optionalen Schritte, die erfolgreich abgeschlossenen Schritte und diejenigen, die bald ablaufen, eindeutig anzeigen.
* Express-Konfiguration: Genau wie unsere Windows 10-Umgebung, aber auf IOS-Geräte zugeschnitten, hilft Ihnen die [Express-Konfiguration für IOS](express-configuration-intune-edu.md) beim schnellen zuweisen und Ändern von apps und Einstellungen. Wählen Sie eine Gruppe von Benutzern oder Geräten aus, und wählen Sie eine der empfohlenen Microsoft-Einstellungen aus. Diese [Empfehlungen sind vorab ausgewählt](edu-express-config-settings-ios.md). Sie können Sie jedoch jederzeit ändern, damit Sie den eigenen Richtlinien Ihrer Bildungseinrichtung entsprechen.  
* Apps und Einstellungen: Wir haben separate App-und Geräte Einstellungs Ansichten hinzugefügt, die Ihnen helfen, sich auf die [IOS](all-edu-settings-ios.md) -oder [Windows 10](all-edu-settings-windows.md) -Geräteverwaltung zu konzentrieren. Durch hinzugefügte [Apple VPP-Unterstützung](add-vpp-apps-ios.md)können Sie Ihre von VPP erworbenen apps mit InTune for Education synchronisieren und direkt aus dem Dashboard zuweisen. 
* Dynamische Gruppierung: Nun können Sie eine bestimmte Geräte Platt Form Regel auf Ihre [dynamischen Gruppen](create-groups.md#dynamic-groups)anwenden. Erstellen Sie eine Regel, die auf Geräte oder Studenten auf Windows 10- *oder* IOS-Geräten angewendet werden soll.  

Weitere Details und Informationen zum Navigieren in neuen Seiten und Workflows finden Sie in der [InTune for Education](what-is-intune-for-education.md) -Dokumentation.   

## <a name="january-2018"></a>2018. Januar

### <a name="history-of-group-actions-taken-by-admins"></a>Verlauf der von Administratoren ausgeführten Gruppenaktionen

Sie können nun einen Verlauf aller von Administratoren ausgeführten Aktionen anzeigen, um Gruppen Administratoren, Apps und Einstellungen für die genehmigten Gruppen zu ändern. Sie können das Protokoll dieses Verlaufs im **Gruppen** > **Verlauf**finden.

### <a name="windows-defender-report"></a>Windows Defender-Bericht

Wir haben einen neuen Bericht hinzugefügt. Auf der Seite Berichte können Sie **Windows Defender-Bericht** in der Liste der Berichte auswählen. Auf diese Weise können Sie den Windows Defender-Geräte Integritäts Status für alle Geräte anzeigen. Wie Sie sehen können, finden Sie im Dokument [Was sind Berichte?](what-are-reports.md) .

### <a name="use-role-based-access-control-to-enable-group-admins"></a>Verwenden der rollenbasierten Zugriffs Steuerung zum Aktivieren von Gruppen Administratoren

Sie können jetzt Gruppen von Personen auswählen, um Einstellungen für andere Gruppen zu verwalten. Angenommen, Sie verfügen über eine Gruppe mit dem Namen " *High School Administratoren*", bei der die Mitglieder Ihr Team von Administratoren für Hochschulen in Ihrem Bezirk sind. Der Gruppe " *Administratoren für hohe Schul Administratoren* " könnten Berechtigungen zum Verwalten von Einstellungen für Gruppen von Studenten mit hoher schulschule erteilt werden. Weitere Informationen finden Sie im Dokument [Was sind Gruppen?](what-are-groups.md).

### <a name="user-and-device-search"></a>Benutzer-und Gerätesuche

Wir haben der Rand Leiste zwei neue Optionen hinzugefügt: **Benutzer** und **Geräte**. Sie können diese verwenden, um nach einzelnen Benutzern oder Geräten zu suchen und schnell die **Details** für diese Elemente zu öffnen. Sie können diese Suchvorgänge der Rand Leiste hinzufügen, indem Sie **alle** > Stern Schaltflächen **(Favoriten)** anzeigen, um Sie Ihrer Favoritenliste hinzuzufügen.

### <a name="remote-actions"></a>Remoteaktionen

Sie können jetzt Remote Aktionen für Ihre Benutzer und Geräte ausführen. Wählen Sie das Gerät aus, für das Sie Maßnahmen ergreifen möchten, und wählen Sie dann auf der Seite Details eine der folgenden Aktionen aus:

#### <a name="devices"></a>Geräte

- Neu starten
- Auf Werkseinstellungen zurücksetzen
- Synchronisierung
- Aus Verwaltung entfernen

#### <a name="users"></a>Users

- Kennwort zurücksetzen

Weitere Informationen zu [Remote Aktionen](edu-device-remote-actions.md)finden Sie hier.

### <a name="wi-fi-profiles"></a>WLAN-Profile

Wir haben der Rand Leiste für **WLAN-Profile**eine neue Option hinzugefügt. Auf diese Weise können Sie WLAN-Einstellungen definieren, die Sie verschiedenen Geräten, Benutzern und Gruppen zuweisen können.

## <a name="october-2017"></a>Oktober 2017

### <a name="dynamic-groups"></a>Dynamische Gruppen

Definieren Sie Regeln, und erstellen Sie Gruppen, die basierend auf diesen automatisch aufgefüllt werden.

### <a name="new-app-status"></a>Neuer App-Status

Wenn Sie eine APP hinzufügen, sehen Sie nun einen Geräte-und benutzerspezifischen Status von App-Installationen.

### <a name="updated-details-pages"></a>Aktualisierte Detailseiten

Wählen Sie einen Benutzer oder ein Gerät in einer ihrer Gruppen aus. Ein Bereich wird jetzt vom unteren Bildschirmrand nach oben angezeigt, auf dem Sie weitere Informationen zu diesem Objekt und den Status der apps und Einstellungen erhalten, die Sie ihm zugewiesen haben.

## <a name="may-2017-initial-release"></a>Mai 2017 (erste Version)

### <a name="intune-for-education-is-now-available"></a>InTune for Education jetzt verfügbar!

Wir haben das InTune for Education-Portal gestartet. InTune for Education ist eine optimierte Lösung für Schulen und Bildungsorganisationen zum Verwalten von Windows 10-Geräten. Erfahren Sie mehr über InTune for Education in diesen Dokumentationen.

## <a name="next-steps"></a>Nächste Schritte

- [Weitere Informationen zu InTune for Education](what-is-intune-for-education.md)
- [Erfahren Sie mehr über die vollständige Geräteverwaltung in InTune.](https://docs.microsoft.com/intune/understand-explore/introduction-to-microsoft-intune)
