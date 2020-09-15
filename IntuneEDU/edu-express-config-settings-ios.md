---
title: Standardeinstellungen für IOS in der Express-Konfiguration
titleSuffix: Intune for Education
description: Listet die Standard Einstellungs Namen und-Verhaltensweisen auf, die bei der Verwendung der Express-Konfiguration
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 04/19/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 2221009e-68cf-4171-8118-0d750b0f35f1
searchScope:
- IntuneEDU
ms.openlocfilehash: 4b1d0141eb9ad0f581c47b963607f88227a1d4fa
ms.sourcegitcommit: f9aea851d80c2bbbe70fbea5666f07b9992dc975
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/02/2019
ms.locfileid: "68740471"
---
# <a name="default-ios-settings-in-express-configuration"></a>Standardeinstellungen für IOS in der Express-Konfiguration
Die Express-Konfiguration ist mit IOS-Einstellungs Vorschlägen voreingestellt, die Ihnen helfen, eine Gruppe von Geräten oder Benutzern schnell einzurichten. InTune for Education wählt Einstellungen aus, die sowohl von Microsoft empfohlen als auch für Schulumgebungen am besten geeignet sind. Nehmen Sie Änderungen an den Regeln und Richtlinien Ihrer Bildungseinrichtung vor, oder klicken Sie auf die Seite "Einstellungen", um unsere Empfehlungen zu übernehmen. 

Die vollständige Liste der Einstellungen und Beschreibungen, finden Sie unter [alle iOS-Einstellungen in Intune for Education](all-edu-settings-ios.md). 

> [!IMPORTANT]
> Wenn IOS-Konfigurationen beim Starten der Express-Konfiguration deaktiviert sind, stellen Sie sicher, dass Sie sowohl ihr MDM-Apple-Push-Zertifikat als auch das DEP-Token eingerichtet haben. Wenn Sie beides haben, stellen Sie sicher, dass keines der beiden abgelaufen ist. Weitere Informationen zum Einrichten der IOS-Geräteverwaltung finden Sie unter [Einrichten der IOS-Geräteverwaltung](setup-ios-device-management.md) .


## <a name="app-store-itunes-store-and-book-store"></a>App Store, iTunes Store und Book Store  
Einstellung|Funktion|  
|---|---|
|App Store blockieren|Blockieren von Studenten am Zugriff auf den App Store auf Schul Geräten.|
|In-App-Käufe blockieren|Blockiert Versuche, in einer laufenden App Store-Käufe zu tätigen.|
|Expliziten Inhalt im App Store und iTunes Store blockieren|Verhindern, dass Studenten auf Inhalte zugreifen, die im App Store als "Erwachsener" eingestuft sind.|
|Herunterladen von Apple-Bücher Inhalt, gekennzeichnet als Erotik blockieren|Verhindern, dass studentenbücher herunterladen, die als Erotica klassifiziert sind.|  

## <a name="built-in-apps"></a>Integrierte Apps  
Einstellung|Funktion|  
|---|---|
|Kamera blockieren|Blockieren Sie die Verwendung der Kamera auf dem Gerät.|
|Facetzeit blockieren|Blockiert die Verwendung der FaceTime-App auf dem Gerät.|
|Game Center blockieren|Blockieren Sie die Verwendung der Game Center-App auf Geräten.|  
|Apple Music blockieren|Blockieren Sie die Verwendung der Musikstreaming-Komponente der Apple Music-App auf dem Gerät.|
|Nachrichten-APP blockieren|Blockieren Sie die Verwendung der Nachrichten-APP auf dem Gerät.|
|Apple-Bücher blockieren|Hindern Sie Schüler und Studenten daran, Bücher im Buch Speicher zu durchsuchen und zu kaufen.|  

## <a name="device-restrictions"></a>Geräteeinschränkungen  
Einstellungsname|Funktion|
|---|---|
|Änderung des Geräte namens blockieren|Verhindern, dass Schüler/Studenten den Namen des Geräts ändern.|
|Ändern des Hintergrund Blocks blockieren|Verhindert, dass Schüler/Studenten den Geräte Sperrbildschirm und das Startbildschirm Bild ändern.|
|Ändern von Benachrichtigungseinstellungen blockieren|Verhindern, dass Studenten die Geräte Benachrichtigungseinstellungen ändern.|
|Änderungen an Inhalten und Datenschutzbestimmungen blockieren|Verhindern, dass Schüler/Studenten Einschränkungen (Jugend schutzkontrollen) und bildschirmzeit Einstellungen auf dem Gerät ändern.|
|Schaltfläche "blockieren", die den gesamten Inhalt und die Einstellungen löscht|Verhindern, dass Studenten alle Inhalte und Einstellungen auf dem Gerät löschen. Die Schaltfläche zum Löschen ist nicht mehr verfügbar und kann nicht ausgewählt werden.|  

## <a name="icloud"></a>iCloud
|Einstellung|Funktion|
|---|---|
|Icloud-Sicherung blockieren|Verhindern, dass Studenten Geräte in icloud sichern.|
|Synchronisierung von Dokumenten in icloud blockieren|Blockieren Sie die Synchronisierung von Dokumenten mit einem icloud-Speicherplatz.|
|Icloud-Fotobibliothek blockieren|Hindern Sie Studenten daran, Fotos und Videos in der Cloud zu speichern. Fotos, die nicht vollständig aus der icloud Photo Library heruntergeladen werden, werden aus dem lokalen Speicher entfernt.|  

## <a name="lock-screen-and-wallpaper"></a>Sperrbildschirm und Hintergrundbild
Einstellung|Funktion|
|---|---|
|Benachrichtigungen auf Sperrbildschirm blockieren|Verhindert, dass Schüler/Studenten Benachrichtigungen anzeigen, wenn das Gerät gesperrt ist.|
|Zugriff auf Wallet vom Sperrbildschirm blockieren|Verhindern, dass Studenten auf die Wallet-App zugreifen, wenn das Gerät gesperrt ist.|
|Bild für Geräte Sperrbildschirm festlegen|Wählen Sie ein benutzerdefiniertes Bild aus, das als Hintergrundbild für den Sperrbildschirm des Geräts angezeigt werden soll.|
|Startbildschirm Bild für Gerät festlegen|Wählen Sie ein benutzerdefiniertes Bild aus, das als Hintergrundbild für den Startbildschirm des Geräts angezeigt werden soll.|  

## <a name="passcode-touch-id-and-face-id"></a>Kennung, Fingereingabe-ID und Gesicht-ID  
Einstellung|Funktion|
|---|---|  
|Kennung erforderlich|Erfordert, dass Schüler/Studenten eine Kennung eingeben, um das Gerät zu entsperren.|
|Ändern der Kennung blockieren|Verhindern, dass Schüler/Studenten die Kennung des Geräts ändern, hinzufügen oder entfernen.|
|Anzahl fehlerhafter Kennungs Versuche vor dem Zurücksetzen des Geräts|Wenn jemand die zulässige Anzahl von Anmelde versuchen überschreitet, löscht das Gerät sämtliche Inhalte und Einstellungen des Geräts, z. b. persönliche Daten, IOS-Software, e-Mail-Konten, System-und App-Einstellungen, heruntergeladene apps und Medien. Das Gerät wird auf die Art und Weise wieder hergestellt, in der es sich beim ersten Einschalten befand. Geben Sie die maximal zulässige Anzahl von Anmelde versuchen ein, um diese Einstellung zu konfigurieren.|
|Berührungs-ID und Gesicht-ID blockieren|Blockieren der Verwendung eines Fingerabdrucks oder einer Gesichtserkennung zum Entsperren von Geräten durch Studenten|

## <a name="siri-and-search"></a>Siri und Search 
Einstellung|Funktion|
|---|---|   
|Siri blockieren|Hindern Sie Studenten daran, Siri, den IOS-sprach-Assistenten zu verwenden.|  

## <a name="reset-default-settings"></a>Standardeinstellungen zurücksetzen
Klicken Sie zum Wiederherstellen aller Einstellungen auf ihre Standardwerte **auf vorgeschlagene Standardwerte zurücksetzen**. 

## <a name="next-steps"></a>Nächste Schritte  
Hier finden Sie Informationen zu Gruppen, Einstellungen und Überwachungs Konflikten in InTune for Education. 
* Ermitteln des Unterschieds zwischen [zugewiesenen und dynamischen](create-groups.md) Gruppen
* Zuweisen von [Gruppen Administratoren](group-admin-delegate.md) zur Unterstützung bei der Verwaltung von Classroom-Einstellungen innerhalb Ihrer Bildungseinrichtung oder im gesamten Bezirk
* Informationen zur Auswirkungen der [Einstellungs Vererbung](settings-inheritance.md) auf Gruppen Zuweisungen
* Überprüfen von [Berichten](what-are-reports.md) zum Ermitteln und Beheben von Einstellungs Konflikten
