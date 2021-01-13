---
title: Descripción del servicio de Microsoft Defender para Office 365
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
description: Microsoft Defender para Office 365 es un servicio de filtrado de correo electrónico basado en la nube que ayuda a proteger su organización contra virus y malware desconocidos al proporcionar una sólida protección de día cero e incluye características para proteger su organización de vínculos dañinos en tiempo real.
ms.openlocfilehash: b3eb9d94fdd96899a0d08e591715a07354104c25
ms.sourcegitcommit: 29db3ccfdd875fc8968e11c040c6db46c2720134
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/12/2021
ms.locfileid: "49799409"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Descripción del servicio de Microsoft Defender para Office 365

Microsoft Defender para Office 365 es un servicio de filtrado de correo electrónico basado en la nube que ayuda a proteger su organización contra virus y malware desconocidos al proporcionar una sólida protección de día cero e incluye características para proteger su organización de vínculos dañinos en tiempo real. Defender para Office 365 tiene completas capacidades de informes y seguimiento de url que proporcionan a los administradores información sobre el tipo de ataques que tienen lugar en su organización.

Las siguientes son las formas principales de usar Defender para Office 365 para la protección de mensajes:

- En un escenario de solo filtrado de Defender para Office 365, Defender para Office 365 proporciona protección de correo electrónico basada en la nube para su entorno de Exchange Server local o cualquier otra solución de correo electrónico SMTP local.

- Defender para Office 365 se puede habilitar para proteger los buzones hospedados en la nube de Exchange Online. Para obtener más información acerca de Exchange Online, consulte la descripción [del servicio de Exchange Online.](exchange-online-service-description/exchange-online-service-description.md)

- En una implementación híbrida, Defender para Office 365 se puede configurar para proteger su entorno de mensajería y controlar el enrutamiento de correo cuando tiene una combinación de buzones locales y en la nube con Exchange Online Protection para el filtrado de correo entrante.

## <a name="microsoft-defender-for-office-365-availability"></a>Disponibilidad de Microsoft Defender para Office 365

Microsoft Defender para Office 365 Plan 2 se incluye en Office 365 E5, Office 365 A5, Seguridad de Microsoft 365 E5 y Microsoft 365 E5, como se especifica aquí: [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp) . Defender para Office 365 Plan 1 se incluye en Microsoft 365 Empresa Premium.

Puede agregar Defender para Office 365 a los siguientes planes de suscripción de Exchange y Microsoft 365:

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

Para comprar Microsoft Defender para Office 365, vea [Microsoft Defender para Office 365.](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)

Para comparar características entre planes, vea Herramientas eficaces para dar soporte [a](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) su empresa y Transformar su empresa con [Microsoft 365.](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Novedades de Microsoft Defender para Office 365

Seguimos agregando nuevas características a Defender para Office 365. Para obtener más información sobre las nuevas características que llegan a Defender para Office 365 (o Microsoft 365 en general), vea los siguientes recursos:

- [Plan de desarrollo de Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Novedades de Microsoft Defender para Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Requisitos para Microsoft Defender para Office 365

Defender para Office 365 se puede usar con cualquier agente de transferencia de correo SMTP, como Microsoft Exchange Server. Para obtener información sobre los sistemas operativos, exploradores web e idiomas compatibles con Defender para Office 365, vea las secciones "Exploradores compatibles" e "Idiomas admitidos" en el Centro de administración de Exchange en [Exchange Online Protection.](https://go.microsoft.com/fwlink/p/?LinkId=282381)

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Disponibilidad de características en los planes de Defender para Office 365

A continuación, se incluye cada característica. Cuando se menciona Exchange Online, por lo general se refiere a la familia de servicios de Office 365 Enterprise.<br><br>

| Característica | Defender para Office 365 Plan 1 | Defender para Office 365 Plan 2 | Seguridad de Microsoft 365 E5 /E5|
|:-----|:-----|:-----|:-----|
|*Configuración, protección y detección*|
|[Archivos adjuntos seguros](#safe-attachments)|Sí|Sí|Sí|
|Datos adjuntos seguros en Teams|Sí|Sí|Sí|
|[Vínculos seguros](#safe-links)|Sí|Sí|Sí|
|[Documentos seguros](#safe-documents)|No|No|Sí|
|Vínculos seguros en Teams|Sí|Sí|Sí|
|[ATP para SharePoint, OneDrive y Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Sí|Sí|Sí|
|[directivas contra la suplantación de identidad](#anti-phishing-policies)|Sí|Sí|Sí|
|[Informes en tiempo real](#real-time-reports)|Sí|Sí|Sí|
|*Automatización, investigación, corrección y educación*|
|[Rastreadores de amenazas](#threat-trackers)|No|Sí|Sí|
|Investigación de amenazas (investigación de amenazas avanzada)|[Detecciones en tiempo real](#real-time-detections)|[Explorador](#explorer)|[Explorador](#explorer)|
|[Respuesta a incidentes automatizada](#automated-incident-response)|No|Sí|Sí|
|[Simulador de ataque](#attack-simulator)|No|Sí|Sí|
|*Integración con [Microsoft 365 Defender](https://docs.microsoft.com/microsoft-365/security/mtp/microsoft-threat-protection)*|No|Sí|Sí|

> [!NOTE]
> Si su espacio empresarial solo tiene una licencia de prueba del Plan P2 de Microsoft Defender para Office u licencia de prueba de Office 365 E5, sin ninguna otra licencia apta para Microsoft 365 Defender, no podrá acceder a Microsoft 365 Defender. Para obtener más información sobre la licencia de MTP, vea [los requisitos de Microsoft 365 Defender.](https://docs.microsoft.com/microsoft-365/security/mtp/prerequisites)

## <a name="defender-for-office-365-capabilities"></a>Capacidades de Defender para Office 365

### <a name="safe-attachments"></a>Archivos adjuntos seguros

[Datos adjuntos](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) seguros protege contra malware y virus desconocidos, y proporciona protección de día cero para proteger su sistema de mensajería. Todos los mensajes y datos adjuntos que no tienen una firma de virus o malware conocida se enruta a un entorno especial donde Defender para Office 365 usa una variedad de técnicas de análisis y aprendizaje automático para detectar intenciones malintencionadas. Si no se detecta ninguna actividad sospechosa, se libera el mensaje para su entrega al buzón de correo.

> [!NOTE]
> El examen de datos adjuntos seguros tiene lugar en la misma región donde residen los datos de Office 365. Para más información sobre la geografía de centros de datos, consulte [¿Dónde se encuentran los datos?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Vínculos seguros

La [característica Vínculos seguros](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) protege de forma proactiva a los usuarios de direcciones URL malintencionadas en un mensaje o en un documento de Office. La protección se mantiene cada vez que seleccionan el vínculo, ya que los vínculos maliciosos se bloquean de forma dinámica mientras se puede acceder a los vínculos buenos.

Los vínculos seguros están disponibles para las direcciones URL en las siguientes aplicaciones:

- Aplicaciones de Microsoft 365 para empresas en Windows o Mac

- Office para la web (Microsoft Word en la Web, Microsoft Excel en la Web, Microsoft PowerPoint en la Web, y Microsoft OneNote en la Web)

- Word, Excel y PowerPoint en Windows

- Canales de Microsoft Teams y chats

> [!NOTE]
> Los usuarios deben tener licencia para Defender para Office 365, deben incluirse en las directivas de vínculos seguros y deben haber iniciado sesión en sus dispositivos para que la protección esté <sup>\*</sup> en su lugar.
>
> <sup>\*</sup> Para las licencias de Defender para Office 365 en toda la organización (por ejemplo, ATP_ENTERPRISE_FACULTY), no es necesario asignar licencias de Defender para Office 365 a usuarios individuales.
>
> Para obtener más información acerca de la protección de vínculos seguros, vea [Vínculos seguros en Microsoft Defender para Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)

### <a name="safe-documents"></a>Documentos seguros

La [característica Documentos seguros](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) usa Microsoft Defender para [endpoint](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) para examinar documentos y archivos que se abren en la [vista protegida.](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)

¿Qué necesita saber antes de comenzar?

- Documentos seguros ahora está disponible generalmente para los usuarios con Office Versión 2004 (12730.x) o posterior. Esta característica está desactivada de forma predeterminada y el administrador de seguridad deberá habilitarla.

- Esta característica solo está disponible para los usuarios con la licencia de Seguridad de Microsoft 365 E5 o Microsoft 365 E5 (no se incluye en los planes de Defender para Office 365).

- Word, Excel y PowerPoint en Windows

- Canales de Microsoft Teams y chats

> [!NOTE]
> Los usuarios deben tener licencia para Microsoft 365 E5 o Microsoft 365 E5 Security, deben estar incluidos en las directivas de documentos seguros y deben haber iniciado sesión en sus dispositivos para que la protección esté <sup>\*</sup> en su lugar.
>
> Para obtener más información acerca de la protección de documentos seguros, vea [Documentos seguros en Microsoft 365 E5.](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP para SharePoint, OneDrive y Microsoft Teams

[ATP para SharePoint, OneDrive](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  y Microsoft Teams ayuda a detectar y bloquear archivos identificados como malintencionados en sitios de grupo y bibliotecas de documentos. Además, la protección de vínculos seguros ya está disponible en los canales y chats de Microsoft Teams.

### <a name="anti-phishing-policies"></a>Directivas de protección contra phishing

[La protección contra la suplantación](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) de identidad comprueba los mensajes entrantes en busca de indicadores de que un mensaje puede ser un intento de suplantación de identidad. Cuando las directivas de Defender para Office 365 cubren a los usuarios (datos adjuntos seguros, vínculos seguros o protección contra suplantación de identidad), los mensajes entrantes se evalúan mediante varios modelos de aprendizaje automático que analizan los mensajes y se toman las medidas adecuadas, en función de las directivas configuradas.

### <a name="real-time-reports"></a>Informes en tiempo real

Las capacidades de supervisión disponibles en el Centro de seguridad & Cumplimiento ( ) incluyen informes y perspectivas en tiempo real que permiten a los administradores de seguridad y cumplimiento centrarse en problemas de prioridad alta, como ataques de seguridad o aumento de la actividad [https://protection.office.com](https://protection.office.com) sospechosa. [](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) Además de resaltar las áreas problemáticas, los informes inteligentes y las conclusiones incluyen recomendaciones y vínculos para ver y explorar datos y también realizar acciones rápidas.

### <a name="explorer"></a>Explorador

Explorer (también conocido como el explorador de amenazas) es un informe en tiempo real que permite a los usuarios autorizados identificar y analizar las amenazas recientes. De forma predeterminada, este informe muestra los datos de los últimos siete días; sin embargo, las vistas se pueden modificar para mostrar los datos de los últimos 30 días.

El explorador contiene vistas, como Malware (para correo electrónico y contenido), Envíos, Suplantación de identidad y Todo el correo electrónico. Para ver cómo se compara Explorer con las detecciones en tiempo real, [descargue este PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Para obtener más información acerca del Explorador (en Microsoft Defender para Office 365 Plan 2) y las detecciones en tiempo real (en Microsoft Defender para Office 365 Plan 1), vea El Explorador de amenazas y las detecciones en tiempo [real.](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)

### <a name="real-time-detections"></a>Detecciones en tiempo real

Las detecciones en tiempo real son un informe en tiempo real que permite a los usuarios autorizados identificar y analizar las amenazas recientes. De forma predeterminada, al igual que el Explorador, este informe muestra los datos de los últimos siete días.

Las detecciones en tiempo real contienen vistas, como malware (para correo electrónico y contenido), envíos y suplantación de identidad. Para ver cómo se comparan las detecciones en tiempo real con el Explorador, [descargue este PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Para obtener más información acerca del Explorador (en Microsoft Defender para Office 365 Plan 2) y las detecciones en tiempo real (en Microsoft Defender para Office 365 Plan 1), vea El Explorador de amenazas (y detecciones en tiempo [real).](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)

### <a name="threat-trackers"></a>Rastreadores de amenazas

[Los Rastreadores de amenazas](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) son widgets informativos y vistas que proporcionan a los usuarios autorizados inteligencia sobre problemas de ciberseguridad que pueden afectar a su organización.

### <a name="automated-incident-response"></a>Respuesta a incidentes automatizada

[Las capacidades](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) de respuesta a incidentes automatizadas (AIR) disponibles en Defender para Office 365 Plan 2 le permiten ejecutar procesos de investigación automatizados en respuesta a amenazas conocidas que existen actualmente. Al automatizar determinadas tareas de investigación, el equipo de operaciones de seguridad puede funcionar de forma más eficaz y eficaz. Las acciones de corrección, como la eliminación de mensajes de correo electrónico malintencionados, se toman tras la aprobación por parte del equipo de operaciones de seguridad. Para obtener más información, vea [Cómo funciona AIR en Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)

### <a name="attack-simulator"></a>Simulador de ataque

[El Simulador de ataques](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) permite a los usuarios autorizados ejecutar escenarios de ataque realistas en la organización. Hay disponibles varios tipos diferentes de ataques, incluido un ataque de phishing de punta de lanza de nombre para mostrar, un ataque de atomizador de contraseñas y un ataque de contraseña por fuerza bruta.
