---
title: Fügen Sie ein WLAN-Profil für Windows und iOS-Geräte
titleSuffix: Intune for Education
description: Erfahren Sie, wie Sie ein WLAN-Profile für Ihre Geräte in Intune for Education erstellen.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468
searchScope:
- IntuneEDU
ms.openlocfilehash: b09d6128d8b64044165b42328f23bfddbdb3beca
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146567"
---
# <a name="add-a-wi-fi-profile"></a>Fügen Sie ein WLAN-Profil hinzu.

Ein WLAN-Profil wird beschrieben, wie mit Ihrer Schule-Netzwerk verbunden wird. Wenn Sie das Profil für einen Benutzer oder einer Gerätegruppe zuweisen, kann die Gruppe Ihrer Schule-Netzwerk automatisch über ihre Geräte zugreifen. -Profil beseitigen die Notwendigkeit für Schüler/Studenten und Lehrkräfte, manuell eine Verbindung mit dem Netzwerk herstellen.

Dieser Artikel beschreibt, wie Sie Profile für Windows 10 und iOS-Geräte zu konfigurieren.

## <a name="supported-device-platforms"></a>Unterstützte Geräteplattformen
WLAN-Profile werden auf Windows 10-Geräten, und klicken Sie auf iOS-Geräten, die über Apple-DEP erworben wurden, unterstützt. 

## <a name="configure-your-profile"></a>Konfigurieren Sie Ihr Profil
Windows 10 und iOS-WLAN-Konfigurationen variieren geringfügig. Aufgrund der Unterschiede müssen Sie eine einzelne WLAN-Profil für Windows 10-Geräte Ihrer Schule, und eine einzelne zur Ihrer Schule iOS-Geräte erstellen.
1. Melden Sie sich, zu Intune for Education > **Wi-Fi Profile**.
2. Wählen Sie die Geräteplattform, der Sie für ein Profil konfigurieren.  
    a. Klicken Sie zum Erstellen eines Profils für ein Windows-Gerät **hinzufügen Windows 10-WLAN-Profil**.   
    b. Um ein Profil für ein iOS-Gerät zu erstellen, klicken Sie auf **Hinzufügen von iOS-WLAN-Profil**. 
3. Geben Sie die Details des Drahtlosnetzwerks Ihrer Schule ein. Verwenden Sie die folgenden Tabellen, die Ihnen helfen, wie Sie diese Einstellungen angeben. Einstellungen unterscheiden sich zwischen Geräte, die Plattformen so stellen Sie sicher, dass Sie sich in der Tabelle, die für Ihr Gerät ansehen.
4. Klicken Sie auf **Speichern**, wenn Sie fertig sind.

### <a name="wi-fi-settings-for-windows-10-devices"></a>WLAN-Einstellungen für Windows 10-Geräte
|Einstellung |Beschreibung  |
|---------|---------|
|Profilname    |  Geben Sie einen eindeutigen Namen für Ihr Profil ein.| 
|Netzwerkname (SSID)    |  Geben Sie einen Anzeigenamen für die drahtlose Verbindung aus. Personen, werden dieser Name angezeigt, wenn sie die Liste der verfügbaren Netzwerke auf ihrem Gerät durchsuchen.  |
|Sicherheitstyp   |  Wählen Sie das Sicherheitsprotokoll zur Authentifizierung mit dem WLAN-Netzwerk. Intune for Education unterstützt WPA2-Personal und öffnen. Wählen Sie öffnen, wenn Sie kein Kennwort, Ihrer Schule Netzwerkzugriff benötigen. Diese Art von Netzwerk ist nicht gesichert, was bedeutet, dass jeder Benutzer darauf zugreifen kann.| 
|Kennwort    |  Geben Sie das Kennwort für das WLAN-Netzwerk ein. Das Kennwort muss 8 – 63 Zeichen lang sein. | 
|Kennwort bestätigen| Geben Sie das Kennwort für das WLAN-Netzwerk ein.|
|Beschreibung| Beschreiben Sie kurz, wer für das Netzwerk ist oder wie es verwendet werden soll.|  

### <a name="wi-fi-settings-for-ios-devices"></a>WLAN-Einstellungen für iOS-Geräte
|Einstellung |Beschreibung  |
|---------|---------|
|Profilname    |  Geben Sie einen eindeutigen Namen für Ihr Profil ein.       | 
|Netzwerkname (SSID)    |  Geben Sie einen Anzeigenamen für die drahtlose Verbindung aus. Personen, werden dieser Name angezeigt, wenn sie die Liste der verfügbaren Netzwerke auf ihrem Gerät durchsuchen.        |
|Sicherheitstyp   |  Wählen Sie das Sicherheitsprotokoll zur Authentifizierung mit dem WLAN-Netzwerk. Intune for Education unterstützt WPA2-Personal und öffnen. Wählen Sie öffnen, wenn Sie kein Kennwort, Ihrer Schule Netzwerkzugriff benötigen. Diese Art von Netzwerk ist nicht gesichert, was bedeutet, dass jeder Benutzer darauf zugreifen kann.       |  
|Kennwort    |  Geben Sie das Kennwort für das WLAN-Netzwerk ein. Das Kennwort muss 8 – 63 Zeichen lang sein. | 
|Kennwort bestätigen| Geben Sie das Kennwort für das WLAN-Netzwerk ein.|
|Automatisch verbinden   |  Wenn aktiviert, werden automatisch zugewiesenen Geräte im Bereich des Netzwerks eine Verbindung herstellen. Wenn nicht aktiviert, müssen Ihre Schüler/Studenten oder Lehrer manuell im Netzwerk aus der Liste der verfügbaren Netzwerke auswählen.       | 
|Stellen Sie ein verstecktes Netzwerk   | Wenn aktiviert, wird nicht Ihr Netzwerk für Benutzer in der Liste der verfügbaren Netzwerke angezeigt. Sie müssen in der Netzwerkname (SSID) eine Verbindung herstellen, geben Sie manuell.       | 
|Konfigurieren von Proxyeinstellungen| Wenn aktiviert, können Sie die Proxyeinstellungen für Ihrer Schule Netzwerk konfigurieren.|
|Proxyeinstellungen   |  Wählen Sie, wenn Sie die Proxyeinstellungen manuell konfigurieren möchten oder wenn Sie ein Proxyskript Einstellungen automatisch erkennen aktivieren möchten.     | 
|Proxyserveradresse   | Geben Sie die IP-Adresse des Proxyservers an. Nicht zutreffend, wenn Sie ausgewählt haben, Proxyeinstellungen automatisch erkennen.      |
|Proxyserverport| Geben Sie die virtuellen Port-Nummer, die auf dem sich der Proxy befindet.    | 
|Proxyserver-URL  | Geben Sie in der Server-URL, die Sie verwenden, um automatisch eine Verbindung mit dem Proxyserver herstellen möchten. Nicht zutreffend, wenn Sie ausgewählt haben, um Proxyeinstellungen manuell konfigurieren.       |   

## <a name="assign-profile-to-groups"></a>Profil Gruppen zuweisen.
1. Rufen Sie die Randleiste, und klicken Sie auf **Gruppen**.
2. Klicken Sie auf der Gruppenseite auf die **Einstellungen** Registerkarte.
3. Klicken Sie auf diese Option, um die entsprechende Gruppe von Einstellungen für Geräte für Ihr Betriebssystem zu erweitern.
4. Klicken Sie auf WLAN-Profile aus, und wählen Sie ein Profil, weisen Sie in der Gruppe. Deaktivieren Sie ein Profil aus, um die Zuweisung der Gruppe zu entfernen.
5. Klicken Sie auf **Speichern**.  
