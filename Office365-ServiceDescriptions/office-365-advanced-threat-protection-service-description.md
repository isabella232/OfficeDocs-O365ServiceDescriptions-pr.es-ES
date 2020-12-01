---
title: Descripción del servicio de Microsoft defender para Office 365
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
description: Microsoft defender para Office 365 es un servicio de filtrado de correo electrónico basado en la nube que ayuda a proteger la organización frente a virus y malware desconocidos proporcionando una protección de día cero eficaz e incluye características para salvaguardar la organización de vínculos peligrosos en tiempo real.
ms.openlocfilehash: 1d99b59e089ecb351d436c49a4f4e3986aefa6cd
ms.sourcegitcommit: 0752cc6c082737a19c7dca24c8f3b555ea871f4f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/01/2020
ms.locfileid: "49519031"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Descripción del servicio de Microsoft defender para Office 365

Microsoft defender para Office 365 es un servicio de filtrado de correo electrónico basado en la nube que ayuda a proteger la organización frente a virus y malware desconocidos proporcionando una protección de día cero eficaz e incluye características para salvaguardar la organización de vínculos peligrosos en tiempo real. Defender para Office 365 tiene funciones enriquecidas de informes y seguimiento de URL que proporcionan a los administradores información sobre el tipo de ataques que ocurren en la organización.

Las siguientes son las principales formas en las que puede usar defender para Office 365 para la protección de mensajes:

- En un escenario de solo filtrado de defender para Office 365, defender para Office 365 proporciona protección de correo electrónico basada en la nube para el entorno local de Exchange Server o cualquier otra solución de correo SMTP local.

- Defender para Office 365 se puede habilitar para proteger buzones de Exchange Online hospedados en la nube. Para obtener más información acerca de Exchange Online, vea la [Descripción del servicio de Exchange Online](exchange-online-service-description/exchange-online-service-description.md).

- En una implementación híbrida, defender para Office 365 se puede configurar para proteger su entorno de mensajería y controlar el enrutamiento de correo cuando tiene una mezcla de buzones locales y en la nube con Exchange Online Protection para el filtrado del correo electrónico entrante.

## <a name="microsoft-defender-for-office-365-availability"></a>Microsoft defender para Office 365 disponibilidad

Defender para Office 365 plan 2 se incluye en Office 365 E5, Office 365 A5 y Microsoft 365 E5. Defender para Office 365 el plan 1 se incluye en Microsoft 365 empresa Premium.

Puede Agregar defender para Office 365 a los siguientes planes de suscripción a Exchange y Microsoft 365:

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

Para comprar Microsoft defender para Office 365, consulte [Microsoft defender para office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Para comparar las características de los planes, vea [eficaces herramientas para apoyar su empresa](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) y [transformar su empresa con Microsoft 365](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Novedades de Microsoft defender para Office 365

Seguimos agregando nuevas características a defender para Office 365. Para obtener más información sobre las nuevas características que se incluyen en defender para Office 365 (o Microsoft 365 en general), vea los siguientes recursos:

- [Plan de desarrollo de Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Novedades de Microsoft defender para Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Requisitos para Microsoft defender para Office 365

Defender para Office 365 se puede usar con cualquier agente de transferencia de correo SMTP, como Microsoft Exchange Server. Para obtener información acerca de los sistemas operativos, exploradores Web e idiomas compatibles con defender para Office 365, consulte las secciones "exploradores compatibles" y "idiomas compatibles" en el [centro de administración de Exchange en Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Disponibilidad de características en defender para Office 365 planes

A continuación, se incluye cada característica. Cuando se menciona Exchange Online, por lo general se refiere a la familia de servicios de Office 365 Enterprise.<br><br>

| Característica | Defender para Office 365 plan 1 | Defender para Office 365 plan 2 | Seguridad de Microsoft 365 E5/E5|
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
|*Integración con Microsoft 365 defender*|No|No|Sí|

> [!TIP]
> ¿Desea descargar una lista de diferencias entre defender para Office 365 plan 1 y plan 2? [Obtener el pdf](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf). 

## <a name="defender-for-office-365-capabilities"></a>Defender para Office 365 funcionalidades

### <a name="safe-attachments"></a>Archivos adjuntos seguros

[Datos adjuntos seguros](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) protege contra malware y virus desconocidos y proporciona protección de día cero para proteger el sistema de mensajería. Todos los mensajes y los datos adjuntos que no tienen una firma de virus/malware conocida se enrutan a un entorno especial donde defender para Office 365 usa una variedad de técnicas de aprendizaje y análisis de la máquina para detectar los intentos malintencionados. Si no se detecta ninguna actividad sospechosa, se libera el mensaje para su entrega al buzón de correo.

> [!NOTE]
> El análisis de datos adjuntos seguros tiene lugar en la misma región en la que residen los datos de Office 365. Para más información sobre la geografía de centros de datos, consulte [¿Dónde se encuentran los datos?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Vínculos seguros

La característica de [vínculos seguros](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) protege de forma proactiva a los usuarios de direcciones URL malintencionadas en un mensaje o en un documento de Office. La protección se mantiene cada vez que seleccionan el vínculo, ya que los vínculos maliciosos se bloquean de forma dinámica mientras se puede acceder a los vínculos buenos.

Los vínculos seguros están disponibles para las direcciones URL en las siguientes aplicaciones:

- Microsoft 365 apps for Enterprise en Windows o Mac

- Office para la web (Microsoft Word en la Web, Microsoft Excel en la Web, Microsoft PowerPoint en la Web, y Microsoft OneNote en la Web)

- Word, Excel y PowerPoint en Windows

- Canales de Microsoft Teams y chats

> [!NOTE]
> Los usuarios deben tener una licencia de defender para Office 365 <sup>\*</sup> , deben incluirse en las directivas de vínculos seguros y deben tener una sesión iniciada en sus dispositivos para que la protección esté en su lugar.
>
> <sup>\*</sup> Para las licencias de defender para 365 Office en toda la organización (por ejemplo, ATP_ENTERPRISE_FACULTY), no es necesario asignar licencias de defender para Office 365 a usuarios individuales.
>
> Para obtener más información acerca de la protección de vínculos seguros, vea [vínculos a prueba de errores en Microsoft defender para Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links).

### <a name="safe-documents"></a>Documentos seguros

La característica [documentos seguros](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) usa [Microsoft defender para el punto de conexión](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) para examinar documentos y archivos que se abren en la [vista protegida](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653).

¿Qué necesita saber antes de empezar?

- Documentos seguros ahora está disponible para los usuarios con la versión de Office 2004 (12730. x) o superior. Esta característica está desactivada de forma predeterminada y el administrador de seguridad la tendrá que habilitar.

- Esta característica solo está disponible para los usuarios con la licencia de seguridad Microsoft 365 E5 o Microsoft 365 E5 (no se incluye en defender para los planes de Office 365).

- Word, Excel y PowerPoint en Windows

- Canales de Microsoft Teams y chats

> [!NOTE]
> Los usuarios deben tener una licencia para la seguridad de Microsoft 365 E5 o Microsoft 365 E5 <sup>\*</sup> , deben incluirse en las directivas de documentos seguros y deben iniciar sesión en sus dispositivos para que la protección esté en su lugar.
>
> Para obtener más información acerca de la protección de documentos seguros, vea [Safe Documents in Microsoft 365 E5](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP para SharePoint, OneDrive y Microsoft Teams

[ATP para SharePoint, OneDrive y Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  ayuda a detectar y bloquear los archivos identificados como malintencionados en los sitios de grupo y las bibliotecas de documentos. Además, la protección de vínculos seguros ahora está disponible en canales y chats de Microsoft Teams.

### <a name="anti-phishing-policies"></a>Directivas de protección contra phishing

[Anti-phishing](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) comprueba los mensajes entrantes en busca de indicadores de que un mensaje puede ser un intento de suplantación de identidad. Cuando los usuarios están cubiertos por defender para las directivas de Office 365 (datos adjuntos seguros, vínculos seguros o contra la suplantación de identidad), los mensajes entrantes se evalúan en varios modelos de aprendizaje automático que analizan mensajes y se realiza la acción correspondiente, en función de las directivas configuradas.

### <a name="real-time-reports"></a>Informes en tiempo real

Las capacidades de supervisión disponibles en el centro de seguridad & cumplimiento incluyen [informes en tiempo real y perspectivas](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) que permiten que los administradores de seguridad y cumplimiento se centren en problemas de alta prioridad, como ataques de seguridad o mayor actividad sospechosa. Además de resaltar las áreas problemáticas, los informes y la información inteligentes incluyen recomendaciones y vínculos para ver y explorar los datos, además de realizar acciones rápidas.

### <a name="explorer"></a>Explorador

Explorer (también conocido como el explorador de amenazas) es un informe en tiempo real que permite a los usuarios autorizados identificar y analizar las amenazas recientes. De forma predeterminada, en este informe se muestran los datos de los últimos 7 días; sin embargo, las vistas se pueden modificar para mostrar los datos de los últimos 30 días.

El explorador contiene vistas, como malware (para correo electrónico y contenido), envíos, phish y todo el correo electrónico. Para ver cómo se compara el explorador con las detecciones en tiempo real, [Descargue este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obtener más información acerca del explorador (en Microsoft defender para Office 365 plan 2) y las detecciones en tiempo real (en Microsoft defender para Office 365 plan 1), consulte [Threat Explorer y detección en tiempo real](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).

### <a name="real-time-detections"></a>Detecciones en tiempo real

Las detecciones en tiempo real son un informe en tiempo real que permite a los usuarios autorizados identificar y analizar las amenazas recientes. Al igual que en Explorer, de forma predeterminada, este informe muestra los datos de los últimos 7 días.

Las detecciones en tiempo real contienen vistas, como malware (para correo electrónico y contenido), envíos y phish. Para ver cómo las detecciones en tiempo real se comparan con el explorador, [Descargue este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obtener más información acerca del explorador (en Microsoft defender para Office 365 plan 2) y las detecciones en tiempo real (en Microsoft defender para Office 365 plan 1), consulte [Threat Explorer (y detección en tiempo real)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).

### <a name="threat-trackers"></a>Rastreadores de amenazas

Los [rastreadores de amenazas](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) son widgets informativos y vistas que proporcionan a los usuarios autorizados una inteligencia sobre problemas de Cybersecurity que pueden afectar a su organización.

### <a name="automated-incident-response"></a>Respuesta de incidente automatizada

Las capacidades de [respuesta a incidencia automatizada](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (Air) disponibles en defender para Office 365 plan 2 le permiten ejecutar procesos de investigación automatizada en respuesta a amenazas bien conocidas que ya existen en la actualidad. Mediante la automatización de determinadas tareas de investigación, el equipo de operaciones de seguridad puede funcionar de forma más eficiente y efectiva. Las acciones de corrección, como la eliminación de mensajes de correo electrónico malintencionado, se toman al aprobar el equipo de operaciones de seguridad. Para obtener más información, vea [Cómo funciona Air en Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulator"></a>Simulador de ataque

El [simulador de ataques](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) permite que los usuarios autorizados ejecuten escenarios de ataque realistas en su organización. Hay disponibles varios tipos de ataques, como un ataque de suplantación de identidad (Spear-phishing), un ataque rociado por contraseña y un ataque de contraseña de fuerza bruta.
