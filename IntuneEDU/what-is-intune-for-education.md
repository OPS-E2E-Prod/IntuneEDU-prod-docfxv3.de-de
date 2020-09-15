---
title: Was ist Intune for Education?
titleSuffix: Intune for Education
description: Erfahren Sie mehr über Intune, Education und wie Sie IOS- und Windows-Geräte in einer akademischen Umgebung verwalten können.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 01/03/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: c66e1700-aac0-44c0-af89-d5d9d4fac9ae
searchScope:
- IntuneEDU
ms.openlocfilehash: 6e85a1c80c3a74735b716dbaa553baa06bbe7f3f
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146838"
---
# <a name="what-is-intune-for-education"></a>Was ist Intune for Education?

Microsoft Intune for Education ist ein Cloud-basierte, mobile Geräte (MDM) für Schulen. Sie können Ihre Lehrer und Schüler/Studenten auf Classroom Geräten produktiv zu bleiben und gewährleistet die Sicherheit der Schul-/ unidaten. 

Intune for Education ermöglicht Ihnen Folgendes:
* Verwalten Sie die Nutzung der Desktop- und mobile Geräte Schüler/Studenten für den Classroom-Datenzugriff.
* Konfigurieren und Zuweisen von apps Schüler und Studenten im Classroom verwenden.
* Steuern Sie, wie Schüler/Studenten und Lehrkräften Zugriff auf und Classroom Informationen gemeinsam nutzen.
* Anwenden von School-sicherheitsanforderungen für Geräte und apps.

Intune for Education-Portals wurde entwickelt, um nur die Einstellungen zu übernehmen und UNI Workflows müssen Sie zum Verwalten von iOS und Windows-Geräte. Über das Portal können Sie anzeigen und Maßnahmen ergreifen, die auf Ihrem Gerät, Benutzer- und app-Bestand. Intune for Education unterstützt auch die Take a Test-app, mit dem Lehrer für Schüler und Studenten Fortschritt direkt von Classroom-Geräten bewerten kann.  

## <a name="sign-up-for-intune-for-education"></a>Melden Sie sich für Intune for Education
Erfahren Sie, wenn Sie sich noch nicht mit Intune for Education-Konto angemeldet sind, [Einstieg](https://docs.microsoft.com/intune/account-sign-up). Der Artikel ist für Systemadministratoren, die ihre Schule für ein Intune-Abonnement registrieren möchten. 

## <a name="manually-add-users-to-you-intune-subscription"></a>Manuelles Hinzufügen von Benutzern zu Intune-Abonnements
Wenn Sie den Dienst Microsoft School Data Sync (SDS) nicht zum Importieren von Studenten und Lehrkräften Datensätzen verwenden, müssen Sie [Manuelles Hinzufügen von Benutzern zu Ihrem Intune-Abonnement](https://docs.microsoft.com/intune/users-add). Schüler/Studenten und Lehrkräfte können über das Azure-Portal oder über das Office 365-Portal hinzugefügt werden. Zum Zeitpunkt der benutzereinrichtung sollten Sie auch Administratorberechtigungen zu gewähren. 

## <a name="supported-os-and-browsers"></a>Unterstützte Betriebssystem- und Browser
Die vollständige Intune-Verwaltungsdienst unterstützt viele Gerätebetriebssysteme. School-Einstellungen, wie Ihr Konto wird empfohlen, mithilfe von Intune for Education. Das Portal wird zur Unterstützung speziell für Windows 10 eingerichtet und UNI iOS-Geräte.  

Eine vollständige Liste der von Intune unterstützte Webbrowser und Betriebssystemen finden Sie unter [unterstützte Betriebssysteme und Browser](https://docs.microsoft.com/intune/supported-devices-browsers) in der Dokumentation zu Microsoft Intune.  

## <a name="configuring-your-intune-for-education-tenant"></a>Konfigurieren Ihre Intune for Education-Mandanten
*Mandanten* bezieht sich auf die Ihrer organisationsinstanz von Intune for Education. Einstellungen auf Mandantenebene Auswirkungen auf Intune-Abonnement Ihrer Organisation. Intune for Education weist sowohl **allgemeine** Einstellungen und **iOS-Geräteverwaltung** mandanteneinstellungen. 

### <a name="general-settings"></a>Allgemeine Einstellungen
Die **allgemeine** auf der Seite Einstellungen für Mandanten Ihrer Schule fordert Informationen über IT wenden Sie sich an und Ressourcen. Die meisten dieser Informationen ist optional, aber es ist sinnvoll, einen IT-Kontaktpunkt für Schüler/Studenten und Lehrkräfte bereitzustellen.  Weitere Informationen zu den Allgemeine Einstellungen bearbeiten, finden Sie unter [bearbeiten Sie allgemeine Einstellungen](edu-tenant-general-settings.md). 

### <a name="ios-device-management-settings"></a>iOS-Device-Management-Einstellungen  
**iOS-Geräteverwaltung** Einstellungen stellen Informationen zu Ihrem Apple-Konten. Diese Einstellungen sind eine Voraussetzung für Organisationen, die ihre iOS-Geräte in Intune verwaltet werden soll. Bis Sie die Verwaltung für iOS-Geräte konfigurieren, können Sie nicht sehen oder Verwalten von iOS-bezogene Einstellungen in Intune for Education-Portals.

Weitere Informationen zum Einrichten Ihres Geräts iOS-Gerät für die Verwaltung finden Sie unter [Einrichten der iOS-geräteverwaltung](setup-ios-device-management.md).

Nur [delegierte Administratoren](group-admin-delegate.md) in Intune for Education zum Anzeigen und Ändern von Einstellungen für Mandanten zulässig sind.

## <a name="does-intune-for-education-work-on-shared-devices"></a>Werden Intune for Education kann auf gemeinsam genutzte Geräte verwendet?  
Intune for Education arbeitet mit gemeinsam genutzte Geräte und die Verwaltung von mehreren Benutzern auf einem einzelnen Gerät unterstützt. Schüler/Studenten, die Gerät verwenden, möglicherweise verschiedene apps und Einstellungen, die speziell für. Wenn Schüler/Studenten auf einem Gerät anmelden, sehen sie nur apps und Einstellungen, die speziell zugewiesen.  

## <a name="compatible-resources-and-tools"></a>Kompatible Ressourcen und tools

Haben Sie Zugriff auf andere Microsoft-Verwaltungstools wie z. B. ein:
* Microsoft Intune im Azure-Portal die [vollständige Geräte-, App- und Verwaltungsfunktionen für Benutzer](https://docs.microsoft.com/intune/understand-explore/introduction-to-microsoft-intune)
* Microsoft Azure Active Directory (Azure AD), [System für die Identitäts- und zugriffsverwaltung](https://docs.microsoft.com/azure/active-directory/active-directory-administer)
* [Microsoft School Data Sync](https://sds.microsoft.com)
* [Office 365 für Bildungseinrichtungen](https://support.office.com/article/Get-started-with-Office-365-Education-AB02ABE5-A1EE-458C-B749-5B44416CCF14)

Verwenden Sie Intune for Education mit [Microsoft Education](https://docs.microsoft.com/education/#pivot=itpro) tools, z. B.:

- [Office 365 für Bildungseinrichtungen](https://support.office.com/article/Set-up-Office-365-for-business-6a3a29a0-e616-4713-99d1-15eda62d04fa)
- [Windows 10 Education](https://docs.microsoft.com/education/windows)
- [Microsoft Store für Bildungseinrichtungen](https://docs.microsoft.com/microsoft-store/index?toc=/microsoft-store/education/toc.json)
- [Minecraft: Education-Edition](https://docs.microsoft.com/education/windows/school-get-minecraft)

> [!VIDEO https://www.youtube.com/embed/ukrnCwcLvV8]

## <a name="get-started-with-intune-for-education"></a>Erste Schritte mit Intune for Education
Importieren Sie Studentendatensätze für Schüler und Microsoft School Data Sync. Schule oder Universität Windows-Geräte mit dem Einrichten einer Schule PCs app konfigurieren, oder melden Sie sich beim [Intune for Education](https://intuneeducation.portal.azure.com) Apple-Verwaltung für iOS-Geräten einrichten.

Von der [Dashboard](how-do-i-customize-my-dashboard.md), starten Sie [Express-Konfiguration](Express-configuration-intune-edu.md). Wählen Sie eine Benutzer- oder gerätesammlung aus (z. B. Schüler/Studenten, Lehrer, oder _2. Etage Computerlabor_) und dem Zuweisen von apps und Einstellungen beginnen.

![Ein Screenshot der Zielseite, die nach der Anmeldung zu Intune for Education.](./media/dashboard-001-landing-page.png)
