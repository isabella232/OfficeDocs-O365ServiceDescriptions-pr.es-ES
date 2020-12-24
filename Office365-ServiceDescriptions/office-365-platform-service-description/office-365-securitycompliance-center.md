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
description: El centro de seguridad &amp; y cumplimiento está diseñado para ayudarle a administrar las características de cumplimiento en Office 365 para su organización. Los vínculos a las características de cumplimiento existentes de SharePoint y Exchange reúnen las capacidades de cumplimiento en Office 365.
ms.openlocfilehash: 972ead8dd3cb7411355d215a3a77f597a24461b9
ms.sourcegitcommit: a30f8263170877468df92cdf882f0c8a09eca6df
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/23/2020
ms.locfileid: "49730728"
---
# <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

El [centro de seguridad y &amp; cumplimiento](https://protection.office.com/) está diseñado para ayudarle a administrar las características de cumplimiento en Office 365 para su organización. Los vínculos a las características de cumplimiento existentes de SharePoint y Exchange reúnen las capacidades de cumplimiento en Office 365.
  
> [!NOTE]
> Currently, many of the compliance features are still accessible through service-specific management interfaces, such as the Exchange admin center (EAC). However, this will change in the future as more service-independent compliance features are added to the Security &amp; Compliance Center.

Para ver las opciones para conceder licencias a los usuarios con el fin de beneficiarse de las características de cumplimiento de Microsoft 365 a partir del 1 de abril de 2020, descargue la comparación detallada de licencias de cumplimiento de Microsoft 365. [(Pdf)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)
  
## <a name="security-amp-compliance-center-availability-for-business-and-enterprise-plans"></a>&amp;Disponibilidad del centro de cumplimiento de seguridad para planes empresariales y empresariales

| Característica | Microsoft 365 Empresa Básico | Microsoft 365 Empresa Estándar | Microsoft 365 Empresa Premium | Office 365 E1, Office 365 US Government G1 | Office 365 E3, Office 365 US Government G3 | Office 365 E5 | Office 365 F3, Office 365 US Government F3|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[Acceso al centro de seguridad y &amp; cumplimiento](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |
|[Prevención de pérdida de datos para Exchange Online, SharePoint Online y OneDrive para la empresa](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)<sup>1, 3</sup> |No   |Sí  |Sí   |No   |Sí   |Sí   |No   |
|[Etiquetas de sensibilidad manual](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)<sup>4</sup> | No | No  |No   | Sí | Sí | Sí | No  |
|[casos de eDiscovery](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |
|[suspensiones de eDiscovery (incluidas las suspensiones de exhibición de documentos electrónicos basadas en consultas)](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-4-place-content-locations-on-hold)  |No   |No   |No  |No   |Sí   |Sí   |No   |
|[exportación de exhibición de documentos electrónicos](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |No   |No   |No   |No   |Sí   |Sí   |No   |
|[Auditoría básica](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>2</sup> |Sí   |Sí   |Sí|Sí   |Sí   |Sí   |Sí   |
|[Office 365 cifrado de mensajes (OME) Basic](https://docs.microsoft.com/microsoft-365/compliance/ome)  |No   |No   |No   |No   |Sí  |Sí   |No   |

<sup>1</sup> incluye los archivos almacenados en repositorios de Microsoft Teams.

<sup>2</sup> los registros de auditoría para todos los planes que incluyen auditoría básica (excepto para E5) se conservan durante 90 días. Dado que E5 incluye auditoría avanzada, los registros de auditoría se conservan durante un año. Además, puede usar la [API de actividad de administración 365 de Office](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) para recuperar eventos del registro de auditoría unificado.

<sup>3</sup> requiere el complemento de prevención de pérdida de datos de Office 365.

<sup>4</sup> las etiquetas de confidencialidad también se incluyen en Azure Information Protection P1 y P2.

## <a name="security-amp-compliance-center-availability-for-standalone-plans"></a>&amp;Disponibilidad del centro de cumplimiento de seguridad para planes independientes

| Característica | Plan 1 de Exchange Online | Plan 2 de Exchange Online | Quiosco de Exchange Online | SharePoint Online Plan 1 | SharePoint Online Plan 2 | OneDrive para la Empresa Plan 1 | OneDrive para la Empresa Plan 2 | Skype Empresarial Online plan 1 | Skype Empresarial Online Plan 2|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[Acceso al centro de seguridad y &amp; cumplimiento](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |
|[Office 365 Cloud App Security](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)  |No   |No   |No   |No   |No   |No   |No   |No   |Sí   |
|[Administración de amenazas](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security), como filtrado de correo y protección contra malware   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |
|[Administración avanzada de amenazas](https://docs.microsoft.com/office365/securitycompliance/office-365-ti), como el explorador de amenazas para las campañas de suplantación de identidad   |No   |No   |No   |No   |No   |No   |No   |No   |No  |
|[Caja de seguridad del cliente](https://docs.microsoft.com/office365/securitycompliance/customer-lockbox-requests)  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Administración de dispositivos móviles](https://support.office.com/article/set-up-mobile-device-management-mdm-in-office-365-dd892318-bc44-4eb1-af00-9db5430be3cd)  |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |Sí   |
|[Prevención de pérdida de datos para Exchange Online, SharePoint Online y OneDrive para la empresa](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)<sup>9</sup>  |No   |Sí   |No   |No   |Sí<sup>7<sup>  |No  |Sí<sup>10</sup> |No   |Sí   |
|[Prevención de pérdida de datos de comunicación para Microsoft Teams](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams)  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Barreras de información](https://docs.microsoft.com/office365/securitycompliance/information-barriers)  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Gobierno de información](https://docs.microsoft.com/office365/securitycompliance/retention-policies)<sup>1</sup>  |Sí<sup>2</sup>  |Sí   |Sí   |Sí   |Sí   |Sí<sup>10</sup>  |Sí<sup>10</sup>  |Sí   |Sí   |
|[Gobierno de información avanzado](https://docs.microsoft.com/office365/securitycompliance/labels)<sup>3</sup>  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Búsqueda de contenido](https://docs.microsoft.com/office365/securitycompliance/search-for-content)  |Sí   |Sí   |Sí   |Sí   |Sí  | Sí<sup>10</sup>  |Sí<sup>10</sup>  |Sí   |Sí   |
|[casos de eDiscovery](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |Sí   |Sí   |Sí   |Sí   |Sí   |Sí<sup>10</sup>  |Sí<sup>10</sup>  |No   |No   |
|[exportación de exhibición de documentos electrónicos](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |No   |Sí   |No   |No   |Sí   |No  |Sí<sup>10</sup> |No<sup>4</sup>  |No<sup>4</sup>  |
|[suspensiones de eDiscovery (incluidas las suspensiones de exhibición de documentos electrónicos basadas en consultas)](https://support.office.com/article/eDiscovery-cases-in-the-Office-365-Security-Compliance-Center-8dd335ab-29d0-41c3-8dd8-9f7c7481e60c#step3_1)  |No   |Sí   |No   |No   |Sí   |No  |Sí<sup>10</sup> |No<sup>4</sup>  |No<sup>4</sup>  |
|[EDiscovery avanzado](https://docs.microsoft.com/office365/securitycompliance/compliance20/overview-ediscovery-20)<sup>5</sup>  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Archivado](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)<sup>6</sup>  |No   |Sí   |No   |Sí   |Sí   |Sí<sup>10</sup> |Sí<sup>10</sup>  |No   |No   |
|[Auditoría básica](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>8</sup>|Sí|Sí|Sí|Sí|Sí|Sí<sup>10</sup>|Sí<sup>10</sup>|No|No|
|Auditoría avanzada|No|No|No|No|No|No|No|No|No|
|[Cumplimiento de la comunicación (directivas de supervisión)](https://docs.microsoft.com/office365/securitycompliance/supervision-policies)  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Cifrado de mensajes de Office 365 (OME)](https://docs.microsoft.com/microsoft-365/compliance/ome)  |No   |No   |No   |No   |Sí   |No   |No|No|No|
|[Cifrado avanzado de mensajes de Office 365](https://docs.microsoft.com/microsoft-365/compliance/ome-advanced-message-encryption)  |No   |No   |No   |No   |Sí   |No   |No|No|No|
|[Administración del acceso con privilegios](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-overview)  |No   |No   |No   |No   |Sí   |No   |No|No|No|

<sup>1</sup> el gobierno de la información permite a los usuarios crear, publicar y aplicar manualmente etiquetas a los documentos; importar datos mediante el envío de la unidad o a través de la red. Estas características están disponibles en E3 y E5, con solo disponibilidad limitada en E1. Para obtener una lista completa de las características disponibles en E1, E3 y E5, vea la comparación detallada de licencias de cumplimiento de 365 de Microsoft. [(Pdf)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

<sup>2</sup> requiere la compra del complemento de archivado de Exchange Online.

<sup>3</sup> el gobierno de información avanzado le permite conservar información importante y eliminar información inimportante mediante la clasificación de la información basándose en una directiva de retención o eliminación o en ambas. Incluye acciones inteligentes/automatizadas, como recomendaciones de directivas, la aplicación automática de etiquetas a datos, la aplicación de etiquetas basadas en tipos de datos confidenciales o consultas, la revisión de disposición y el uso de filtros de importación inteligente. También incluye la característica de supervisión para revisar las comunicaciones de los empleados con fines de seguridad y cumplimiento.

<sup>4</sup> las conversaciones de Skype se almacenan como parte del buzón de correo.

<sup>5</sup> la exhibición avanzada de documentos electrónicos requiere Office 365 E5 o una licencia de complemento.

<sup>6</sup> el archivado de Skype se encuentra en el buzón del usuario.

<sup>7</sup> incluye los archivos almacenados en repositorios de Microsoft Teams.

<sup>8</sup> los registros de auditoría para todos los planes que incluyen auditoría básica se conservan durante 90 días. Además, puede usar la [API de actividad de administración 365 de Office](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) para recuperar eventos del registro de auditoría unificado.

<sup>9</sup> requiere el complemento de prevención de pérdida de datos de Office 365.

<sup>10</sup> limitado a los archivos almacenados en OneDrive para la empresa.

<sup>11</sup> se requiere una licencia de archivado de Exchange Online plan 2 o Exchange Online para poner un buzón de usuario en espera con una directiva de retención.
  
## <a name="security-amp-compliance-center-availability-in-office-365-operated-by-21vianet"></a>&amp;Disponibilidad del centro de cumplimiento de seguridad en Office 365 operado por 21Vianet

El centro de cumplimiento está disponible en el plan E3 para Office 365 operado por 21Vianet.
  
## <a name="security-amp-compliance-center-availability-in-office-365-germany"></a>Security &amp; Compliance Center availability in Office 365 Germany

El centro de seguridad & cumplimiento está disponible para Office 365 Germany. Para obtener información sobre Office 365 Germany, consulte [office 365 Germany](office-365-germany.md).
