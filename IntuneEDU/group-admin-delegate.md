---
title: Delegieren von Administratorberechtigungen für Gruppen
titleSuffix: Intune for Education
description: Erfahren Sie, wie Sie Rollen für die Gruppen in Intune for Education verwalten.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 06/20/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 9319be2e-cb7e-43c1-98fe-64281c8c09fd
searchScope:
- IntuneEDU
ms.openlocfilehash: 6538520b0364b6ecf4b7ec45d57a465d49907778
ms.sourcegitcommit: c766ef357fb0257951f4e35f6ec6f53d63de811e
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/20/2019
ms.locfileid: "67285182"
---
# <a name="delegate-admin-permissions-to-groups"></a>Delegieren von Administratorberechtigungen für Gruppen
Sie und Ihre IT-Mitarbeiter verwalten mehrere Gruppen von Schüler/Studenten, Lehrkräfte und Administratoren in Ihrer Schule/Universität.  

Im Gegensatz zu IT-Mitarbeiter verwalten Administratorgruppen nur die Gruppen, die Sie ihnen zuweisen. Wenn Sie über Administratorberechtigungen für eine Gruppe von qualifizierten Personen gestatten, können Sie unbefugte oder versehentliche Änderungen zu verringern.  

## <a name="group-admin-permissions"></a>Administratorberechtigungen für die Gruppe 

Gruppenadministratoren werden in Intune for Education zugewiesen, und es über die Berechtigung zum School-Geräte und apps zu verwalten. Gruppenadministratoren können Aktionen ausführen:  

- Anzeigen von Informationen zu Geräten, Benutzern und apps.
- Weisen Sie zu, erstellen Sie, löschen Sie, zeigen Sie an und aktualisieren Sie der Einstellungen für Geräte und Benutzer.
- Zuweisen, erstellen, löschen, anzeigen und Aktualisieren von apps.
- Anzeigen von Berichten.
- Aktionen Sie remote für Geräte, einschließlich der auf die werkseitigen Standardeinstellungen zurücksetzen, Neustarten, einem entsperrten Gerät sperren und eine Synchronisierung zu erzwingen.  
- Erstellen Sie, löschen Sie, zeigen Sie an und aktualisieren Sie den iOS MDM-Push-Zertifikat, den iOS MDM-Server-Token und die iOS-VPP-Token.   

> [!TIP]
> Ändern von Administratorberechtigungen ist eine komplexe Aufgabe. Wenn Sie die Berechtigungen ändern oder einen benutzerdefinierten Satz von Berechtigungen erstellen möchten, müssen Sie zum wechseln [erleben Sie die vollständige Verwaltung in Intune](https://docs.microsoft.com/intune/role-based-access-control). Diese Berechtigungen umfassen, die in Intune integrierten schuladministratorrolle. 

## <a name="assign-an-admin-group"></a>Weisen Sie eine Administratorengruppe

1. Intune for Education-Dashboard, klicken Sie auf **Gruppen**.
2. Wählen Sie eine Gruppe aus. Diese Gruppe werden die, die Ihre Administratoren zu verwalten.
3. Klicken Sie auf die **Administratoren** Registerkarte > **fügen Administratoren**.
4. Wählen Sie eine Gruppe aus, um ihr Administrator eine Zugriffsberechtigung für das Verwalten von apps und Einstellungen zu geben.
5. Klicken Sie auf **auswählen Gruppe**.

## <a name="remove-an-admin-group"></a>Entfernen einer Administratorengruppe
1. Intune for Education-Dashboard, klicken Sie auf **Gruppen**.
2. Wählen Sie eine Gruppe aus. Diese Gruppe wird sein, die Sie Administratorengruppe aus Verwaltung entfernen.
3. Klicken Sie auf die **Administratoren** Registerkarte.
4. Wählen Sie eine oder mehrere Gruppen aus der Liste der Administratoren ein. Klicken Sie dann auf **Administratoren entfernen**.  
