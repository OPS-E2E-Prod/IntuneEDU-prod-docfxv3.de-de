---
title: Verwenden von Autopilot Reset zum Neukonfigurieren von Geräten mit InTune for Education
titleSuffix: Intune for Education
description: Erfahren Sie, wie Sie Autopilot in InTune for Education zurücksetzen.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/17/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: ''
searchScope:
- IntuneEDU
ms.openlocfilehash: 23430e2902eeb5673f1915b1a9e547bdde1e17dd
ms.sourcegitcommit: 05576d32cac5cc3998ea579404ce84a2813c9083
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/09/2019
ms.locfileid: "68866715"
---
# <a name="autopilot-reset"></a>Autopilot zurücksetzen
Sie können Autopilot Reset verwenden, um persönliche Dateien, Apps und Einstellungen von ihren Geräten zu entfernen. Die Geräte bleiben in InTune registriert und werden wieder in einen vollständig konfigurierten oder bekannten, von ihm genehmigten Zustand versetzt.
Sie können Autopilot ein Gerät lokal oder Remote über das InTune for Education-Portal zurücksetzen.  

Wenn Sie das InTune for Education-Portal verwenden, vermeiden Sie, dass IT-Mitarbeiter jedes Gerät besuchen müssen, um den Prozess zu starten. Im Portal können Sie ein einzelnes Gerät zurücksetzen oder eine Massen Zurücksetzung für alle Geräte in einer Gruppe ausführen. Durch das Zurücksetzen aller Geräte in einer Gruppe können Sie Student-Geräte schnell zurücksetzen und neu konfigurieren, um Sie auf das neue Schul Jahr vorzubereiten.  

Nach dem Zurücksetzen werden die ursprünglichen Einstellungen auf das Gerät angewendet und dann mit InTune synchronisiert, um die neuesten Richtlinien zu erhalten. Bei der Verwendung der Autopilot-Zurücksetzung auf einem Gerät, wird dessen primäre Benutzer entfernt. Der nächste Benutzer, der sich nach dem Zurücksetzen anmeldet, wird als primärer Benutzer festgelegt.   

## <a name="requirements"></a>Anforderungen
Die Verwendung von Autopilot Reset lokal steht nur für Geräte mit Windows 10, Version 1709 oder höher, zur Verfügung.
Die Verwendung von Autopilot Remote Reset ist nur für Geräte verfügbar, auf denen Windows 10 Build 17672 oder höher ausgeführt wird.

## <a name="use-autopilot-reset-locally"></a>Verwenden von Autopilot Reset lokal
Wenn Sie ein einzelnes Gerät löschen müssen, können Sie dies direkt auf dem Gerät durchführen. Drücken Sie auf dem Gerät STRG + Win + R. Nach dem Drücken von STRG + Win + R müssen Sie sich mit Administrator Anmelde Informationen authentifizieren, um die zurück Setzung zu initiieren.

## <a name="use-autopilot-reset-remotely-for-a-single-device"></a>Verwenden der Autopilot-zurück setzung für ein einzelnes Gerät
1. Wählen Sie in InTune for Education **Gruppen** aus, > Sie eine Gerätegruppe auswählen.
2. Wählen Sie ein Gerät > **Autopilot Reset**aus. Um das Zurücksetzen zu bestätigen, wählen Sie erneut **Autopilot Reset** aus.
2.  Wenn die zurück Setzung initiiert wird, wird eine Meldung angezeigt. Das Gerät wird zurückgesetzt, wenn es das nächste Mal eine Verbindung mit dem Internet herstellt.  

## <a name="use-autopilot-reset-remotely-for-devices-in-bulk"></a>Remote Zurücksetzung von Autopilot für Geräte per Massen Vorgang verwenden  
1.  Wählen Sie in InTune for Education **Gruppen** aus, > Wählen Sie die Gruppe aus.
2. Wählen Sie **Autopilot alle Geräte zurücksetzen**aus.
2. Geben Sie im **Gruppenfeld Autopilot Reset** den Namen der aktuellen Gruppe ein. Wählen Sie dann **Autopilot Reset** aus, um dies zu bestätigen.
3.  Jedes Gerät wird zurückgesetzt, wenn es das nächste Mal eine Verbindung mit dem Internet herstellt. Wenn eines der Geräte das Zurücksetzen des Remote Autopilot-Geräts nicht unterstützt, wird eine Tabelle mit dem Namen " **Geräte" nicht zurückgesetzt**. In der Tabelle werden die einzelnen Geräte und der Grund aufgeführt, warum Sie nicht zurückgesetzt werden konnten.  

## <a name="next-steps"></a>Nächste Schritte
[Verwalten von Geräten mit Remoteaktionen](edu-device-remote-actions.md)



