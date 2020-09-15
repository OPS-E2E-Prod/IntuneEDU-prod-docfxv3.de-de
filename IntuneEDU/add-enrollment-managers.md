---
title: Fügen Sie geräteregistrierungs-Manager hinzu.
titleSuffix: Intune for Education
description: Erfahren Sie, wie Sie Geräteregistrierungs-Manager in Intune für Bildungseinrichtungen hinzufügen.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 08/30/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: b496bc02-714e-4391-b533-4c9bdcf57483
searchScope:
- IntuneEDU
ms.openlocfilehash: 26b9a9c6eaabe85dbe77acd9a52f7b86b8a99d4d
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146974"
---
# <a name="add-enrollment-managers"></a>Fügen Sie geräteregistrierungs-Manager hinzu.  

Geben Sie an Ihre vorhandenen Benutzer Gerät-Registrierungsberechtigungen. Benutzer mit Konten für geräteregistrierungs-Manager können bis zu 1000 Windows 10-Geräten in Intune for Education registrieren.

 Konten für geräteregistrierungs-Manager sind hilfreich in großen Organisationen, die Tausende von freigegebenen Windows 10-Geräte zu registrieren.  

## <a name="requirements"></a>Anforderungen  

Es müssen Benutzer im Azure-Portal vorhanden sein, damit sie als Geräteregistrierungs-Manager hinzugefügt werden können.

Registrierungsberechtigungen Gerät können nicht mit folgenden anderen Registrierungsmethoden verwendet werden: Apple Configurator mit Setup-Assistenten, mit Apple Configurator mit direkter Registrierung, Apple School Manager (ASM) oder (Device Enrollment Program, DEP).  

## <a name="assign-enrollment-permissions"></a>Neue Registrierungsberechtigungen zuweisen  

1. Intune for Education-Dashboard, klicken Sie auf **Geräteregistrierungs-Manager**.
2. **Klicken Sie auf Registrierungsberechtigungen zuweisen**.
3. Wählen Sie den Benutzer, dem Sie Berechtigungen zuweisen möchten. Wenn Sie den Namen des Benutzers kennen, können Sie Sie in das Suchfeld suchen.
4. Klicken Sie auf **Speichern**.

## <a name="remove-enrollment-permissions"></a>Registrierungsberechtigungen entfernen  
1. Von **Geräteregistrierungs-Manager**, fahren Sie mit der linken Seite des Bildschirms, und wählen Sie einen Benutzer. 
2. Klicken Sie auf **Registrierungsberechtigungen entfernen**.
3. Klicken Sie auf **entfernen** Aktion zu bestätigen. Wenn Sie einen Geräteregistrierungs-Manager entfernen, wirkt sich dies nicht auf registrierte Geräte aus.
  ![Entfernen Sie die Registrierung Schaltfläche "Berechtigungen" beim Anzeigen einer einzelnen Geräteregistrierungs-Manager-Seite aktiviert wurde.](./media/enroll-mgrs-003-remove-enrollment-permissions.png)
