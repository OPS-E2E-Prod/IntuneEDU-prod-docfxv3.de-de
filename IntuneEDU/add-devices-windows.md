---
title: Windows 10-Geräte registrieren
titleSuffix: Intune for Education
description: Informationen Sie zum Einrichten von Windows 10-Geräte für Intune for Education.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 06/18/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.openlocfilehash: 29d4b238fb906eac01f3ffe36dd252f8b657d046
ms.sourcegitcommit: 9c43411a2c210cf1d755c3120015c89611e33613
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/18/2019
ms.locfileid: "67213393"
---
# <a name="enroll-windows-10-devices"></a>Windows 10-Geräte registrieren

Nachdem Sie Intune for Education mit Ihren Informationen eingerichtet haben, z. B. Studentendatensätze, apps und Einstellungen für Geräte, verbinden Sie die Geräte zu Intune for Education. Für neue Windows 10-Geräten wird eine Verbindung während der Installation des ersten Gerät hergestellt.   

## <a name="when-to-use-set-up-school-pcs-vs-windows-autopilot"></a>Bei Verwendung von School-PCs und Windows Autopilot einrichten  
Die folgende Tabelle beschreibt die beim Einrichten von School-PCs und/oder Windows Autopilot für die Einrichtung des ersten Gerät verwenden. Verwenden der **zu berücksichtigende Punkte** Spalte zu Ihrer eigenen Schule Umgebung und Anforderungen berücksichtigen.  

|Zu berücksichtigende Punkte| Einrichten von School-Pcs |Windows Autopilot  |
|---------|---------|---------|  
|IT-Mitarbeiter | IT-Team führt Gerät unboxing, ersten Einschalten und Konfiguration von Geräten erfolgt durch das IT-Personal.|Optimiert für begrenzte Engagement von IT-Abteilung. Schüler/Studenten und Lehrkräfte können Gerät unboxing ersten Einschalten und erste Konfiguration ausführen.|
|Benutzer des Geräts|  Am besten geeignet für gemeinsam genutzte Geräte und für jüngere Schüler/Studenten.|Am besten geeignet für 1:1-Geräte und für fortgeschrittene Schüler oder Studenten.|
|Apps     | Am besten geeignet für die Bereitstellung von großen apps gleichzeitig für eine langsamere Netzwerkverbindung.|Funktioniert gut mit apps aller Größen.| 
|Netzwerk | Zuverlässige Internetverbindung erforderlich; am besten geeignet für Netzwerke mit geringer Bandbreite.| Zuverlässige Internetverbindung erforderlich; Auslastung der Netzwerkbandbreite basierend auf der Anzahl von gleichzeitigen Gerät Setups und Größe der erforderliche apps. Schüler/Studenten können mit Geräten in ihrem privaten Netzwerk einrichten.|
|Erster Tag der-Klasse|Geräte sind bereit für die Anmeldung und sofort verwenden.| Schüler/Studenten müssen mittels Unboxing zu konvertieren und eine Verbindung mit Netzwerk herstellen. Abschluss von Setup automatisch.|
|Zeitpunkt der Bereitstellung|Kann zwischen 1 – 2 Minuten dauern; Zeit, erhöht sich abhängig von der Anzahl von Gerät-Setups, Netzwerkbandbreite und die Größe der erforderlichen Anwendungen.|Kann zwischen 1 – 2 Minuten dauern; Zeit, erhöht sich abhängig von der Anzahl von Gerät-Setups, Netzwerkbandbreite und die Größe der erforderlichen Anwendungen.|
|OEMs und Partner|Nicht zutreffend.  |Erfordert die Registrierung der Geräte-IDs für die Windows Autopilot-Dienst von einem Partner (CSP) oder der OEM-Anbieter. |
|Auf der Konfiguration vor Ort vorhandene| Mit Windows Configuration Designer nur unterstützt. | Unterstützt die Hybrid-AD-Einbindung. Gerät muss in demselben Netzwerk wie Active Directory-Domänencontroller sein.|  
### <a name="setting-up-devices-with-windows-autopilot"></a>Einrichten von Geräten mit Windows Autopilot
 Einrichten von Ihren Geräten mit [Autopilot](https://docs.microsoft.com/windows/deployment/windows-autopilot/windows-autopilot-requirements), wechseln Sie zu [Intune](https://devicemanagement.microsoft.com) > **geräteregistrierung** > **Windows-Registrierung**  >  **Geräte**.   

### <a name="setting-up-devices-with-set-up-school-pcs-app"></a>Einrichten von Geräten mit School PCs-App
Windows-Geräte in Intune über das Einrichten einer Schule PCs app hinzufügen. Die app führt Sie durch die Schritte zum Konfigurieren und speichern Sie ein einzelnes Gerät-Profil, das Sie verteilen können auf mehreren PCs. Ein USB-Laufwerk wird verwendet, um zu speichern und laden das Profil für jedes Gerät während des gerätesetups. 

Weitere Informationen zu der app, finden Sie unter den [Was ist School-PCs einrichten?](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app) Artikel. 

## <a name="setup-windows-devices"></a>Einrichten der Windows-Geräte  
Führen Sie die folgenden Schritte aus, um Ihre Windows 10-Geräte zu Intune for Education hinzuzufügen. Während des Setups müssen Geräte mit dem Internet zugreifen. 

1. Schalten Sie das neue Windows 10-Gerät. 
2. Auf einem neuen oder zurückgesetzten-Gerät, um der erste Setupbildschirm liest, **können, beginnen Sie mit der Region. Ist dies die richtige?** Wählen Sie die Region, wo sich Ihre PCs befinden. Wählen Sie dann **Ja**.  

   ![Beispielscreenshot, der im Setup-Bildschirm ab, in der Windows 10-OOBE. Vereinigte Staaten ist als der ausgewählten Region hervorgehoben.](./media/RS5_Choose_Region.png)  

3. Wählen Sie ein Tastaturlayout aus. Dieser Schritt wird die Bildschirmtastatur verwenden der Tastatur des physischen Layouts entsprechend konfiguriert. Es konfiguriert außerdem Sprach- und tastatureinstellungen Zeichen. Wählen Sie **Ja** um den Vorgang fortzusetzen.  

      ![Beispielscreenshot des Bildschirms Layout Tastatur mit USA als das ausgewählte Layout.](./media/RS5_Choose_Keyboard.png)  

4. Wenn Sie einen anderen Tastaturlayout hinzufügen möchten, wählen Sie **hinzufügen Layout**. Wählen Sie andernfalls **überspringen**.   

     ![Beispielscreenshot, der dem zweiten Tastatur Layout Bildschirm mit Optionen zum Hinzufügen von Layout und direkt in der unteren rechten Ecke.](./media/RS5_Second_keyboard.png)  

5. Wählen Sie **für Geschäfts-, Schul- oder unikonto einrichten**. Wählen Sie dann **Weiter**.  

     ![Beispielscreenshot, der die ** wie möchten Sie zum Einrichten? ** Bildschirm, markieren die Option Set einrichten für Geschäfts-, Schul- oder unikonto.](./media/RS5_Choose_Setup_Type.png)  

6. Geben Sie die e-Mail-Adresse, die mit Ihrer Schule Administrator "oder" geräteregistrierungs-Managerkonto verbunden ist. Wählen Sie dann **Weiter**.  

     ![Beispielscreenshot, der die ** melden Sie sich mit Microsoft ** Bildschirm mit dem Microsoft-Logo, und ein leeres Feld für die e-Mail-Adresse.](./media/RS5_Sign_In.png)  

7. Geben Sie das Kennwort für das Konto ein. Wählen Sie dann **Weiter**.  

     ![Beispielscreenshot, der die ** Geben Sie Ihr Kennwort ** Bildschirm mit Logo Ihrer Organisation und einem leeren Kennwortfeld.](./media/RS5_Enter_Password.png)  



8. Wählen Sie die datenschutzeinstellungen für das Gerät. Konfigurieren Sie diese Einstellungen, die basierend auf Ihrer Schule Richtlinien. Einige der Einstellungen, z. B. **Spracherkennung** und **Speicherort** sind standardmäßig aktiviert.  

     ![Festlegen von Optionen, mit einigen Einstellungen auf den Datenschutz auflisten beispielscreenshot wird standardmäßig eingeschaltet.](./media/RS5_Choose_Settings.png)  


9. Wählen Sie **Accept** Geräteinstallation abschließen. Dauert möglicherweise einige Minuten, bis Setup abgeschlossen ist, daher gerne Setup auf einem anderen Gerät zu starten.  

## <a name="next-steps"></a>Nächste Schritte
Nun, dass Geräte eingerichtet und einsatzbereit für die Verwendung des "School" festgelegt sind, werden Informationen Sie zum Aktualisieren, überwachen und beheben Sie diese.   
* Weisen Sie [Gruppe Administratoren](group-admin-delegate.md) helfen Ihnen beim Verwalten von Classroom-Einstellungen innerhalb Ihrer Schule/Universität oder in der Region
* Überprüfen Sie alle [Windows-Einstellungen](all-edu-settings-windows.md) , die Sie anpassen können
* Erfahren Sie, wie [einstellungsvererbung](settings-inheritance.md) wirkt sich auf neue Gruppen
* Überprüfen Sie [Berichte](what-are-reports.md) zu ermitteln, identifizieren und Beheben von Fehlern  

 
