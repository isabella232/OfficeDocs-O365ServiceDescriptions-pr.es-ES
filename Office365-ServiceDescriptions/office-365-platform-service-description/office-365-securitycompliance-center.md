---
title: Centro de seguridad y cumplimiento
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5a693243-2f13-4c7e-af1a-779c0752ae35
description: El Centro de cumplimiento de seguridad está diseñado para ayudarle a administrar las características de cumplimiento &amp; en Office 365 para su organización. Los vínculos a las características de cumplimiento existentes de SharePoint y Exchange reúnen las capacidades de cumplimiento en Office 365.
ms.openlocfilehash: 4daf754f5472620482eced63a9970b05a4e61a6c
ms.sourcegitcommit: 02dd535b01c4ca7b19b43188ddd1a1f02c01afb5
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/05/2021
ms.locfileid: "50460199"
---
# <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

El [Centro de cumplimiento de &amp; seguridad](https://protection.office.com/) está diseñado para ayudarle a administrar las características de cumplimiento en Office 365 para su organización. Los vínculos a las características de cumplimiento existentes de SharePoint y Exchange reúnen las capacidades de cumplimiento en Office 365.
  
> [!NOTE]
> Currently, many of the compliance features are still accessible through service-specific management interfaces, such as the Exchange admin center (EAC). However, this will change in the future as more service-independent compliance features are added to the Security &amp; Compliance Center.

Para ver las opciones para otorgar licencias a los usuarios para que se beneficien de las características de cumplimiento de Microsoft 365 a partir del 1 de abril de 2020, descargue la comparación detallada de licencias de cumplimiento de Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)
  
## <a name="security-amp-compliance-center-availability-for-business-and-enterprise-plans"></a>Disponibilidad &amp; del Centro de seguridad y cumplimiento para planes empresariales y empresariales

| Característica | Microsoft 365 Empresa Básico | Microsoft 365 Empresa Estándar | Microsoft 365 Empresa Premium | Office 365 E1, Office 365 US Government G1 | Office 365 E3, Office 365 US Government G3 | Office 365 E5 | Office 365 F3, Office 365 US Government F3|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[Acceso al Centro de &amp; cumplimiento de seguridad](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |
|[Prevención de pérdida de datos para Exchange Online, SharePoint Online y OneDrive para la Empresa](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)<sup>2</sup> | No | No  |Sí   | Sí | Sí | Sí | No  |
|[Etiquetas de confidencialidad manuales](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)<sup>3</sup> | No | No  |No   | Sí | Sí | Sí | No  |
|[Casos de exhibición de documentos electrónicos](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |
|[Retenciones de exhibición de documentos electrónicos (incluidas las retenciones de exhibición de documentos electrónicos basadas en consultas)](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-4-place-content-locations-on-hold)  |No   |No   |No  |No   |Sí   |Sí   |No   |
|[Exportación de exhibición de documentos electrónicos](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |No   |No   |No   |No   |Sí   |Sí   |No   |
|[Auditoría básica](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>1</sup> |Sí   |Sí   |Sí|Sí   |Sí   |Sí   |Sí   |
|[Cifrado de mensajes de Office 365 (OME) Básico](https://docs.microsoft.com/microsoft-365/compliance/ome)  |No   |No   |No   |No   |Sí  |Sí   |No   |

<sup>1</sup> Los registros de auditoría de todos los planes que incluyen auditoría básica (excepto E5) se conservan durante 90 días. Dado que E5 incluye auditoría avanzada, los registros de auditoría se conservan hasta un año. Además, puede usar la API de actividad de administración de [Office 365](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) para recuperar eventos del registro de auditoría unificado.

<sup>2</sup> Requiere un complemento de prevención de pérdida de datos de Office 365.

<sup>3 Las</sup> etiquetas de confidencialidad también se incluyen en Azure Information Protection P1 y P2.

## <a name="security-amp-compliance-center-availability-for-standalone-plans"></a>Disponibilidad &amp; del Centro de seguridad y cumplimiento para planes independientes

| Característica | Plan 1 de Exchange Online | Plan 2 de Exchange Online | Quiosco de Exchange Online | SharePoint Online Plan 1 | SharePoint Online Plan 2 | OneDrive para la Empresa Plan 1 | OneDrive para la Empresa Plan 2 | Skype Empresarial Online plan 1 | Skype Empresarial Online Plan 2|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[Acceso al Centro de &amp; cumplimiento de seguridad](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |
|[Office 365 Cloud App Security](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)  |No   |No   |No   |No   |No   |No   |No   |No   |Sí   |
|[Administración de amenazas,](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)como filtrado de correo y antimalware   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |
|[Administración avanzada de amenazas,](https://docs.microsoft.com/office365/securitycompliance/office-365-ti)como explorador de amenazas para campañas de suplantación de identidad   |No   |No   |No   |No   |No   |No   |No   |No   |No  |
|[Caja de seguridad del cliente](https://docs.microsoft.com/office365/securitycompliance/customer-lockbox-requests)  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Administración de dispositivos móviles](https://support.office.com/article/set-up-mobile-device-management-mdm-in-office-365-dd892318-bc44-4eb1-af00-9db5430be3cd)  |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |
|[Prevención de pérdida de datos para Exchange Online, SharePoint Online y OneDrive para la Empresa](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)<sup>9</sup>  |No   |Sí   |No   |No   |Sí<sup>7<sup>  |No  |Sí<sup>10</sup> |No   |Sí   |
|[Prevención de pérdida de datos de comunicación para Microsoft Teams](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams)  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Barreras de información](https://docs.microsoft.com/office365/securitycompliance/information-barriers)  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Gobierno de la](https://docs.microsoft.com/office365/securitycompliance/retention-policies)<sup>información 1</sup>  |Sí<sup>2</sup>  |Sí   |Sí   |Sí   |Sí   |Sí<sup>10</sup>  |Sí<sup>10</sup>  |Sí   |Sí   |
|[Gobierno avanzado de la](https://docs.microsoft.com/office365/securitycompliance/labels)<sup>información 3</sup>  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Búsqueda de contenido](https://docs.microsoft.com/office365/securitycompliance/search-for-content)  |Sí   |Sí   |Sí   |Sí   |Sí  | Sí<sup>10</sup>  |Sí<sup>10</sup>  |Sí   |Sí   |
|[Casos de exhibición de documentos electrónicos](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |Sí   |Sí   |Sí   |Sí   |Sí   |Sí<sup>10</sup>  |Sí<sup>10</sup>  |No   |No   |
|[Exportación de exhibición de documentos electrónicos](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |No   |Sí   |No   |No   |Sí   |No  |Sí<sup>10</sup> |No<sup>4</sup>  |No<sup>4</sup>  |
|[Retenciones de exhibición de documentos electrónicos (incluidas las retenciones de exhibición de documentos electrónicos basadas en consultas)](https://support.office.com/article/eDiscovery-cases-in-the-Office-365-Security-Compliance-Center-8dd335ab-29d0-41c3-8dd8-9f7c7481e60c#step3_1)  |No   |Sí   |No   |No   |Sí   |No  |Sí<sup>10</sup> |No<sup>4</sup>  |No<sup>4</sup>  |
|[Exhibición de documentos electrónicos avanzada](https://docs.microsoft.com/office365/securitycompliance/compliance20/overview-ediscovery-20)<sup>5</sup>  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Archivado](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)<sup>6</sup>  |No   |Sí   |No   |Sí   |Sí   |Sí<sup>10</sup> |Sí<sup>10</sup>  |No   |No   |
|[Auditoría básica](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>8</sup>|Sí|Sí|Sí|Sí|Sí|Sí<sup>10</sup>|Sí<sup>10</sup>|No|No|
|Auditoría avanzada|No|No|No|No|No|No|No|No|No|
|[Cumplimiento de comunicaciones (directivas de supervisión)](https://docs.microsoft.com/office365/securitycompliance/supervision-policies)  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Cifrado de mensajes de Office 365 (OME)](https://docs.microsoft.com/microsoft-365/compliance/ome)  |No   |Sí   |No   |No   |Sí   |No   |No|No|No|
|[Cifrado avanzado de mensajes de Office 365](https://docs.microsoft.com/microsoft-365/compliance/ome-advanced-message-encryption)  |No   |No   |No   |No   |Sí   |No   |No|No|No|
|[Privileged Access Management](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-overview)  |No   |No   |No   |No   |Sí   |No   |No|No|No|

<sup>1</sup> El gobierno de la información permite a los usuarios crear, publicar y aplicar manualmente etiquetas a los documentos; importar datos mediante el trasvase de unidades o a través de la red. Estas características están disponibles en E3 y E5, con una disponibilidad limitada en E1. Para obtener una lista completa de las características disponibles en E1, E3 y E5, consulte la comparación detallada de licencias de cumplimiento de Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

<sup>2</sup> Requiere la compra de Archivado de Exchange Online complemento.

<sup>3</sup> El gobierno avanzado de la información le permite conservar información importante y eliminar información no importante mediante la clasificación de información basada en una directiva de retención o eliminación o ambas. Incluye acciones inteligentes y automatizadas, como recomendar directivas, aplicar automáticamente etiquetas a los datos, aplicar etiquetas basadas en tipos o consultas de datos confidenciales, revisar la disposición y usar filtros de importación inteligentes. También incluye la característica Supervisión para revisar las comunicaciones de los empleados con fines de seguridad y cumplimiento.

<sup>4 Las</sup> conversaciones de Skype se almacenan como parte del buzón.

<sup>5</sup> La exhibición de documentos electrónicos avanzada requiere Office 365 E5 o una licencia de complemento.

<sup>6 El</sup> archivado de Skype está dentro del buzón del usuario.

<sup>7</sup> Incluye archivos almacenados en repositorios de Microsoft Teams.

<sup>8</sup> Los registros de auditoría de todos los planes que incluyen auditoría básica se conservan durante 90 días. Además, puede usar la API de actividad de administración de [Office 365](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) para recuperar eventos del registro de auditoría unificado.

<sup>9</sup> Requiere un complemento de prevención de pérdida de datos de Office 365.

<sup>10</sup> Limitado a los archivos almacenados en OneDrive para la Empresa.

<sup>11</sup> Se requiere una licencia de Archivado de Exchange Online o plan 2 de Exchange Online para poner un buzón de usuario en espera mediante una directiva de retención.
  
## <a name="security-amp-compliance-center-availability-in-office-365-operated-by-21vianet"></a>Disponibilidad &amp; del Centro de seguridad y cumplimiento en Office 365 operado por 21Vianet

El Centro de cumplimiento está disponible en el plan E3 para Office 365 operado por 21Vianet.
  
## <a name="security-amp-compliance-center-availability-in-office-365-germany"></a>Security &amp; Compliance Center availability in Office 365 Germany

El Centro de seguridad & cumplimiento está disponible para Office 365 Germany. Para obtener información sobre Office 365 Germany, vea [Office 365 Germany](office-365-germany.md).
