---
title: Descripción del servicio de Protección contra amenazas avanzada de Office 365
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced Threat Protection (ATP) es un servicio de filtrado de correo electrónico basado en la nube que ayuda a proteger a su organización frente a virus y malware desconocidos proporcionando una protección de día cero eficaz e incluye características para proteger a su organización de vínculos dañinos en tiempo real.
ms.openlocfilehash: 0e9c7e76cabd9f39a13c16689a4255732617b09d
ms.sourcegitcommit: 0f2d249dfc93432e17344f70b8317a455204f018
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/01/2020
ms.locfileid: "47318947"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Descripción del servicio de Protección contra amenazas avanzada de Office 365

Microsoft Office 365 Advanced Threat Protection (ATP) es un servicio de filtrado de correo electrónico basado en la nube que ayuda a proteger a su organización frente a virus y malware desconocidos proporcionando una protección de día cero eficaz e incluye características para proteger a su organización de vínculos dañinos en tiempo real. ATP tiene capacidades enriquecidas de informes y seguimiento de URL que proporcionan a los administradores información sobre el tipo de ataques que ocurren en la organización.

Las siguientes son las principales formas en que puede usar ATP para la protección de mensajes:

- En un escenario de solo filtrado ATP de Office 365, ATP proporciona protección de correo electrónico basado en la nube para su entorno de Exchange Server local o cualquier otra solución de correo electrónico SMTP local.

- Se puede habilitar Office 365 ATP para proteger los buzones hospedados en la nube de Exchange Online. Para obtener más información acerca de Exchange Online, vea la [Descripción del servicio de Exchange Online](exchange-online-service-description/exchange-online-service-description.md).

- En una implementación híbrida ATP puede configurarse para proteger su entorno de mensajería y controlar el enrutamiento de correo cuando tiene una mezcla de buzones en el nivel local y en la nube con Exchange Online Protection para filtrar los correos electrónicos entrantes.

## <a name="office-365-advanced-threat-protection-atp-availability"></a>Disponibilidad de la protección contra amenazas avanzada (ATP) de Office 365

El plan 2 de ATP de Office 365 está incluido en Office 365 E5, Office 365 A5 y en Microsoft 365 E5. El plan 1 de ATP de Office 365 está incluido en Microsoft 365 Empresa Premium.

Puede Agregar ATP a los siguientes planes de suscripción de Exchange y Microsoft 365:

- Plan 1 de Exchange Online

- Plan 2 de Exchange Online

- Quiosco de Exchange Online

- Exchange Online Protection

- Microsoft 365 Empresa Básico

- Microsoft 365 Empresa Estándar

- Office 365 Enterprise E1

- Office 365 Enterprise E3

- Office 365 Enterprise F3

- Office 365 A1

- Office 365 A3

Para comprar la protección contra amenazas avanzada de Office 365, consulte [protección contra amenazas avanzada de office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Para comparar las características de los planes, vea [eficaces herramientas para apoyar su empresa](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) y [transformar su empresa con Microsoft 365](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Novedades de la protección contra amenazas avanzada (ATP) de Office 365

Seguimos agregando nuevas características a Office 365 ATP. Para obtener más información sobre las nuevas características disponibles para ATP (o Microsoft 365 en general), vea los siguientes recursos:

- [Plan de desarrollo de Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Novedades de Office 365 ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Requisitos para la protección contra amenazas avanzada de Office 365 (ATP)

ATP puede usarse con cualquier agente de transferencia de correo SMTP, como Microsoft Exchange Server. Para obtener información sobre los sistemas operativos, exploradores Web e idiomas compatibles con ATP, consulte las secciones "exploradores admitidos" y "idiomas compatibles" en el [centro de administración de Exchange en Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Disponibilidad de características en los planes de protección contra amenazas avanzada (ATP)

A continuación, se incluye cada característica. Cuando se menciona Exchange Online, por lo general se refiere a la familia de servicios de Office 365 Enterprise.

|**Característica**|**Plan ATP 1**<br>(anteriormente ATP independiente)|**Plan ATP 2**<br>(anteriormente, inteligencia de amenazas <br>independientemente| Seguridad de Microsoft 365 E5/E5|
|:-----|:-----|:-----|:-----|
|*Configuración, protección y detección*|
|[Archivos adjuntos seguros](#safe-attachments)|Sí|Sí|Sí|
|Datos adjuntos seguros en Microsoft Teams|Sí|Sí|Sí|
|[Vínculos seguros](#safe-links)|Sí|Sí|Sí|
|[Documentos seguros](#safe-documents)|No|No|Sí|
|Vínculos seguros en Teams|Sí|Sí|Sí|
|[ATP para SharePoint, OneDrive y Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Sí|Sí|Sí|
|[directivas contra la suplantación de identidad](#anti-phishing-policies)|Sí|Sí|Sí|
|[Informes en tiempo real](#real-time-reports)|Sí|Sí|Sí|
|*Automatización, investigación, corrección y educación*|
|[Rastreadores de amenazas](#threat-trackers)|No|Sí|Sí|
|Investigación de amenazas (investigación de amenazas avanzada)|[Detecciones en tiempo real](#real-time-detections)|[Explorador](#explorer)|[Explorador](#explorer)|
|[Respuesta de incidente automatizada](#automated-incident-response)|No|Sí|Sí|
|[Simulador de ataque](#attack-simulator)|No|Sí|Sí|

> [!TIP]
> ¿Desea descargar una lista de diferencias entre Office 365 ATP plan 1 y plan 2? [Obtener el pdf](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf). 

## <a name="advanced-threat-protection-atp-capabilities"></a>Capacidades de protección contra amenazas avanzada (ATP)

### <a name="safe-attachments"></a>Datos adjuntos seguros

Los [datos adjuntos seguros de ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) protegen contra malware y virus desconocidos y proporcionan protección de día cero para proteger el sistema de mensajería. Todos los mensajes y datos adjuntos que no tienen una firma de virus/código dañino conocida se enrutan a un entorno especial donde ATP usa diversas técnicas de análisis y aprendizaje automático para detectar intentos malintencionados. Si no se detecta ninguna actividad sospechosa, se libera el mensaje para su entrega al buzón de correo.

> [!NOTE]
> El análisis de Datos adjuntos seguros de ATP tiene lugar en la misma región en la que residen los datos de Office 365. Para más información sobre la geografía de centros de datos, consulte [¿Dónde se encuentran los datos?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Vínculos seguros

La característica de [vínculos seguros de ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) protege de forma proactiva a los usuarios de direcciones URL malintencionadas en un mensaje o en un documento de Office. La protección se mantiene cada vez que seleccionan el vínculo, ya que los vínculos maliciosos se bloquean de forma dinámica mientras se puede acceder a los vínculos buenos.

Vínculos seguros está disponible para las direcciones URL en las siguientes aplicaciones:

- Microsoft 365 apps for Enterprise en Windows o Mac

- Office para la web (Word para la web, Excel para el Web, PowerPoint para el Web y OneNote para la web)

- Word, Excel, PowerPoint y Visio en Windows, así como aplicaciones de Office en dispositivos iOS y Android

- Canales de Microsoft Teams y charlas

> [!NOTE]
> Los usuarios deben tener una licencia para ATP <sup>\*</sup> , deben estar incluidos en las directivas de vínculos seguros de ATP y deben haber iniciado sesión en sus dispositivos para que la protección esté en su lugar.
>
> <sup>\*</sup> Para las licencias de ATP de toda la organización (por ejemplo, ATP_ENTERPRISE_FACULTY), no es necesario asignar licencias ATP a usuarios individuales.
>
> Para obtener más información acerca de la protección de vínculos seguros de ATP, consulte [how ATP Safe links Works with URL in Office Documents](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents).

### <a name="safe-documents"></a>Documentos seguros

La característica de [documentos seguros de ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) usa la [protección contra amenazas avanzada de Microsoft defender](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) para examinar documentos y archivos que se abren en la [vista protegida](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653).

¿Qué necesita saber antes de empezar?

- Documentos seguros ahora está disponible para los usuarios con la versión de Office 2004 (12730. x) o superior. Esta característica está desactivada de forma predeterminada y el administrador de seguridad la tendrá que habilitar.

- Esta característica solo está disponible para los usuarios con la licencia de seguridad Microsoft 365 E5 o Microsoft 365 E5 (no se incluye en los planes de ATP de Office 365).

- Word, Excel, PowerPoint y Visio en Windows, así como aplicaciones de Office en dispositivos iOS y Android

- Canales de Microsoft Teams y charlas

> [!NOTE]
> Los usuarios deben tener una licencia para la seguridad de Microsoft 365 E5 o Microsoft 365 E5 <sup>\*</sup> , deben incluirse en las directivas de documentos seguros de ATP y deben haber iniciado sesión en sus dispositivos para que la protección esté en su lugar.
>
> Para obtener más información acerca de la protección de documentos seguros de ATP, consulte [documentos seguros en Microsoft 365 E5](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP para SharePoint, OneDrive y Microsoft Teams

[ATP para SharePoint, OneDrive y Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  ayuda a detectar y bloquear los archivos identificados como malintencionados en los sitios de grupo y las bibliotecas de documentos. Además, la protección de vínculos seguros de ATP ahora está disponible en canales y chats de Microsoft Teams.

### <a name="anti-phishing-policies"></a>Directivas contra phishing

[Anti-phishing de ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) comprueba los mensajes entrantes en busca de indicadores de que un mensaje puede ser un intento de suplantación de identidad. Cuando los usuarios están cubiertos por directivas de ATP (datos adjuntos seguros, vínculos seguros o contra la suplantación de identidad), los mensajes entrantes se evalúan en varios modelos de aprendizaje automáticos que analizan mensajes y se lleva a cabo la acción adecuada en función de las directivas configuradas.

### <a name="real-time-reports"></a>Informes en tiempo real

Las capacidades de supervisión disponibles en el centro de seguridad & cumplimiento incluyen [informes en tiempo real y perspectivas](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) que permiten que los administradores de seguridad y cumplimiento se centren en problemas de alta prioridad, como ataques de seguridad o mayor actividad sospechosa. Además de resaltar las áreas problemáticas, los informes y la información inteligentes incluyen recomendaciones y vínculos para ver y explorar los datos, además de realizar acciones rápidas.

### <a name="explorer"></a>Explorador

Explorer (también conocido como el explorador de amenazas) es un informe en tiempo real que permite a los usuarios autorizados identificar y analizar las amenazas recientes. De forma predeterminada, en este informe se muestran los datos de los últimos 7 días; sin embargo, las vistas se pueden modificar para mostrar los datos de los últimos 30 días.

El explorador contiene vistas, como malware (para correo electrónico y contenido), envíos, phish y todo el correo electrónico. Para ver cómo se compara el explorador con las detecciones en tiempo real, [Descargue este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obtener más información sobre el explorador (en Office 365 Advanced Threat Protection Plan 2) y las detecciones en tiempo real (en Office 365 plan de protección contra amenazas avanzada 1), consulte [Threat Explorer y detección en tiempo real](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).

### <a name="real-time-detections"></a>Detecciones en tiempo real

Las detecciones en tiempo real son un informe en tiempo real que permite a los usuarios autorizados identificar y analizar las amenazas recientes. Al igual que en Explorer, de forma predeterminada, este informe muestra los datos de los últimos 7 días.

Las detecciones en tiempo real contienen vistas, como malware (para correo electrónico y contenido), envíos y phish. Para ver cómo las detecciones en tiempo real se comparan con el explorador, [Descargue este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obtener más información sobre el explorador (en Office 365 Advanced Threat Protection Plan 2) y las detecciones en tiempo real (en Office 365 plan de protección contra amenazas avanzada 1), consulte [Threat Explorer (y detección en tiempo real)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).

### <a name="threat-trackers"></a>Rastreadores de amenazas

Los [rastreadores de amenazas](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) son widgets informativos y vistas que proporcionan a los usuarios autorizados una inteligencia sobre problemas de Cybersecurity que pueden afectar a su organización.

### <a name="automated-incident-response"></a>Respuesta de incidente automatizada

Las capacidades de respuesta a incidentes (Air) [automatizada](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) disponibles en Office 365 ATP plan 2 le permiten ejecutar procesos de investigación automatizada en respuesta a amenazas bien conocidas que existen actualmente. Mediante la automatización de determinadas tareas de investigación, el equipo de operaciones de seguridad puede funcionar de forma más eficiente y efectiva. Las acciones de corrección, como la eliminación de mensajes de correo electrónico malintencionado, se toman al aprobar el equipo de operaciones de seguridad. Para obtener más información, vea [Cómo funciona Air en Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulator"></a>Simulador de ataque

El [simulador de ataques](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) permite que los usuarios autorizados ejecuten escenarios de ataque realistas en su organización. Hay disponibles varios tipos de ataques, como un ataque de suplantación de identidad (Spear-phishing), un ataque rociado por contraseña y un ataque de contraseña de fuerza bruta.
