---
title: Express-Konfiguration-Standard-geräteeinstellungen für Windows 10
titleSuffix: Intune for Education
description: Aufgelistet und beschrieben die Windows 10-Einstellungen in Express-Konfiguration.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 03/14/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 2221009e-68cf-4171-8118-0d750b0f35f1
searchScope:
- IntuneEDU
ms.openlocfilehash: 4aae2a3ad7d411a0212b683430d7416c7318b1a1
ms.sourcegitcommit: 106131761071c33343f6b4e8006f36ae97ee28c7
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/11/2019
ms.locfileid: "66835647"
---
# <a name="default-windows-10-configurations-in-express-configuration"></a>Windows 10-Standardkonfigurationen in Express-Konfiguration
Express-Konfiguration zeigt die am häufigsten verwendeten Windows-Einstellungen können Sie Ihre Windows-Geräte schneller eingerichtet. In diesem Artikel werden die einzelnen Einstellungen aufgeführt und beschrieben, was sie tun.

Nehmen Sie Änderungen an passen, Regeln und Richtlinien Ihrer Schule oder klicken direkt über die Seite "Einstellungen", um die vordefinierten Empfehlungen anzuwenden.

Die vollständige Liste der Einstellungen und Beschreibungen, finden Sie unter [alle Windows 10-Einstellungen in Intune for Education](all-edu-settings-windows.md). 

## <a name="accounts-and-sign-in"></a>Konten und -Anmeldung 

|Einstellung|Funktion|  
|---|---|
|Blockieren Sie Hinzufügen von und Anmelden mit persönlichen Microsoft-Konten |Block Schüler/Studenten und Lehrkräfte hinzufügt und die Anmeldung bei persönlicher Microsoft-Konten auf dem Gerät. Persönliche Microsoft-Konten finden Sie in Konten, die einen Domänennamen von Microsoft verwenden, aber nicht in Azure Active Directory-Mandanten Ihrer Schule.|  
|Blockieren Sie Hinzufügen von und Anmelden mit nicht-Microsoft-Konten|Block Schüler/Studenten und Lehrkräfte hinzufügt oder Anmelden bei nicht-Microsoft-Konten, z. B. Google, Yahoo und iCloud. Verwenden Sie diese Einstellung zu erzwingen, dass Benutzer ihren Microsoft-Konten nur für e-Mail-Adresse zu verwenden.|
|Konfigurieren Sie bevorzugte Azure Active Directory-mandantendomäne|Konfigurieren Sie Domänenname Ihrer Schule, sodass Benutzer bei Windows ohne anmelden können. Beispielsweise anstelle der Anmeldung mit Benutzername *Alain\@"contoso.com"*, Schüler/Student müssten nur für die Anmeldung *Alain*. Wenn konfiguriert, wird diese Einstellung bereits Domänennamen Ihres Mandanten, aber Sie können immer noch bearbeiten.|   

## <a name="apps"></a>Apps   
|Einstellung|Funktion|  
|---|---|
|Blockieren Sie Installieren von apps aus dem Microsoft Store für Bildungseinrichtungen|Hiermit werden Benutzer daran, apps von nicht autorisierten Orten installieren.|  
|Müssen Sie Microsoft Store für Bildungseinrichtungen-apps aus privatem Store installiert werden|Müssen Sie Benutzer nur apps aus dem Microsoft Store für Bildungseinrichtungen installieren, die Ihre Organisation eingerichtet wurde.|  

## <a name="enrollment-controls"></a>Registrierungssteuerelemente  
|Einstellung|Funktion| 
|---|---|
|Manuelle Aufhebung der Registrierung blockieren|Hiermit werden Benutzer von Geräten in der Verwaltung manuell Aufheben der Registrierung.|
|Hinzufügen von Bereitstellungspaketen blockieren|Hiermit werden Benutzer hinzufügen, neue Bereitstellung der Pakete, die geräteeinstellungen enthalten.|
|Entfernen von Bereitstellungspaketen blockieren|Hiermit werden Benutzer daran, Bereitstellungspakete, die geräteeinstellungen zu entfernen.|  

## <a name="microsoft-edge-settings"></a>Microsoft Edge-Einstellungen  
|Einstellung|Funktion|
|---|---|
|Startseiten konfigurieren|Konfigurieren Sie, wie die Homepage von Microsoft Edge Schüler/Studenten und Lehrkräfte angezeigt wird. **Öffnen Sie benutzerdefinierte Seiten** öffnet die URL Ihrer Wahl. Der Browser wird für jede URL, die Sie hinzufügen, eine neue Registerkarte geöffnet. **Öffnen Sie die letzte Sitzung Seiten** öffnet der Seiten, die den Zeitpunkt der letzten aktiv waren der Browser geschlossen wurde. Wenn Sie diese Einstellung nicht konfigurieren, können Benutzer auf der Startseite für ihre eigenen konfigurieren.| 
|InPrivate-Browsen blockieren|Hiermit werden Benutzer daran, InPrivate-Browsen, Microsoft Edge das verhindert wird, Speichern von Daten, wie das Durchsuchen von Verlauf und Cookies.|  
|Browsererweiterungen blockieren|Hiermit werden Benutzer Browsererweiterungen zu installieren.|
|Popups blockieren|Hiermit blockieren Sie Websites in neuen Fenstern öffnen.|  
|Kennwort-Manager blockieren|Hiermit werden Benutzer von mit dem Kennwortmanager zum Speichern von Kennwörtern.|
|Automatisch ausfüllen von Formulareinträgen blockieren|Speichern online in ein Formular eingegebene Daten blockieren.|
|Hiermit werden Entwicklungstools blockiert|Hiermit werden Benutzer von Microsoft Edge-Entwicklertools zu öffnen. Diese Tools ermöglichen Benutzern das Erstellen und Debuggen von Webseiten.|  

## <a name="user-experience"></a>Benutzerfreundlichkeit 
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
|Set benutzerdefiniertes Hintergrundbild für Sperrbildschirm|Fügen Sie ein benutzerdefiniertes Hintergrundbild auf dem Gerät anmelden Bildschirm hinzu. Geben Sie in den Weblink, um eine JPG- oder PNG-Bild, das weniger als 20 MB groß ist.|
|Set benutzerdefiniertes Hintergrundbild für desktop|Fügen Sie ein benutzerdefiniertes Hintergrundbild auf dem Gerät-Desktop hinzu. Geben Sie in den Weblink, um eine JPG- oder PNG-Bild, das weniger als 20 MB groß ist.|
|Blockieren des Zugriffs auf die Einstellungs-app|Blockieren Sie Benutzerzugriff auf die gesamte Einstellungen-app.|  

## <a name="reset-default-settings"></a>Standardeinstellungen zurücksetzen
Klicken Sie zum Wiederherstellen aller Einstellungen auf ihre Standardwerte **auf vorgeschlagene Standardwerte zurücksetzen**.  

