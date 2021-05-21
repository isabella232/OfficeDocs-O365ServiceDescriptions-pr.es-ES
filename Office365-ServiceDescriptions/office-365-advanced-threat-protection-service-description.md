---
title: Descripción del servicio de Microsoft Defender para Office 365
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Defender para Office 365 es un servicio de filtrado de correo electrónico basado en la nube que ayuda a proteger su organización contra malware y virus desconocidos al proporcionar una protección sólida de día cero e incluye características para proteger su organización de vínculos dañinos en tiempo real.
ms.openlocfilehash: 76b4d2e53c8a2942d4b974c5289c9ae4c8854b72
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52545977"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Descripción del servicio de Microsoft Defender para Office 365

Microsoft Defender para Office 365 es un servicio de filtrado de correo electrónico basado en la nube que ayuda a proteger su organización contra malware y virus desconocidos al proporcionar una protección sólida de día cero e incluye características para proteger su organización de vínculos dañinos en tiempo real. Defender para Office 365 cuenta con funciones completas de informes y seguimiento de direcciones URL que proporcionan a los administradores información sobre el tipo de ataques que ocurren en su organización.

Las siguientes son las formas principales de usar Defender para Office 365 protección de mensajes:

- En un escenario de solo filtrado de Defender para Office 365, Defender para Office 365 proporciona protección de correo electrónico basada en la nube para su entorno de Exchange Server local o cualquier otra solución de correo electrónico SMTP local.

- Defender para Office 365 puede habilitarse para proteger Exchange Online buzones hospedados en la nube. Para obtener más información sobre Exchange Online, consulte [la Exchange Online descripción del servicio](exchange-online-service-description/exchange-online-service-description.md).

- En una implementación híbrida, Defender para Office 365 se puede configurar para proteger el entorno de mensajería y controlar el enrutamiento de correo cuando se tiene una combinación de buzones locales y en la nube con Exchange Online Protection para el filtrado de correo entrante.

## <a name="microsoft-defender-for-office-365-availability"></a>Disponibilidad de Microsoft Defender Office 365 disponibilidad

Microsoft Defender para Office 365 Plan 2 se incluye en Office 365 E5, Office 365 A5, Seguridad de Microsoft 365 E5 y Microsoft 365 E5 como se especifica aquí: [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](/microsoft-365/security/office-365-security/office-365-atp) . Defender for Office 365 Plan 1 se incluye en Microsoft 365 Empresa Premium.

Puede agregar Defender for Office 365 a los siguientes planes Exchange y Microsoft 365 suscripción:

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

Para comprar Microsoft Defender para Office 365, consulte [Microsoft Defender for Office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Para obtener información detallada del plan sobre las suscripciones que permiten a los usuarios de Microsoft Defender Office 365, consulte la tabla de comparación [de suscripciones completa.](https://go.microsoft.com/fwlink/?linkid=2139145)

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Novedades de Microsoft Defender para Office 365

Seguimos agregando nuevas características a Defender para Office 365. Para obtener más información sobre las nuevas características que vienen a Defender Office 365 (o Microsoft 365 en general), vea los siguientes recursos:

- [Plan de desarrollo de Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Novedades de Microsoft Defender para Office 365](/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Requisitos para Microsoft Defender para Office 365

Defender para Office 365 puede usarse con cualquier agente de transferencia de correo SMTP, como Microsoft Exchange Server. Para obtener información sobre los sistemas operativos, exploradores web e idiomas compatibles con Defender para Office 365, vea las secciones "Exploradores compatibles" y "Idiomas admitidos" en el Centro de administración de Exchange en [Exchange Online Protection](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Disponibilidad de características en Defender para Office 365 planes

A continuación, se incluye cada característica. Cuando se menciona Exchange Online, por lo general se refiere a la familia de servicios de Office 365 Enterprise.<br><br>

| Característica | Defender para Office 365 Plan 1 | Defender para Office 365 Plan 2 | Microsoft 365 E5 / Seguridad A5|
|:-----|:-----|:-----|:-----|
|*Configuración, protección y detección*|
|[Datos adjuntos seguros](#safe-attachments)|Sí|Sí|Sí|
|Caja fuerte Datos adjuntos en Teams|Sí|Sí|Sí|
|[Vínculos seguros](#safe-links)|Sí|Sí|Sí|
|[Documentos seguros](#safe-documents)|No|No|Sí|
|Vínculos seguros en Teams|Sí|Sí|Sí|
|[ATP para SharePoint, OneDrive y Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Sí|Sí|Sí|
|[Directivas contra phishing](#anti-phishing-policies)|Sí|Sí|Sí|
|[Informes en tiempo real](#real-time-reports)|Sí|Sí|Sí|
|*Automatización, investigación, corrección y educación*|
|[Rastreadores de amenazas](#threat-trackers)|No|Sí|Sí|
|Investigación de amenazas (investigación avanzada de amenazas)|[Detecciones en tiempo real](#real-time-detections)|[Explorador](#explorer)|[Explorador](#explorer)|
|[Respuesta automatizada a incidentes](#automated-incident-response)|No|Sí|Sí|
|[Aprendizaje de simulación de ataques](#attack-simulation-training)|No|Sí|Sí|
|*Integración con [Microsoft 365 Defender](/microsoft-365/security/mtp/microsoft-threat-protection)*|No|Sí|Sí|

> [!NOTE]
> Si su inquilino solo tiene una licencia de prueba del Plan P2 de Microsoft Defender para Office o una licencia de prueba de E5, sin ninguna otra licencia elegible para Microsoft 365 Defender, no podrá acceder Office 365 Microsoft 365 Defender. Para obtener más información acerca de la licencia MTP, [consulte Microsoft 365 Defender requirements](/microsoft-365/security/mtp/prerequisites).

## <a name="defender-for-office-365-capabilities"></a>Defender para Office 365 capacidades

### <a name="safe-attachments"></a>Archivos adjuntos seguros

[Caja fuerte datos adjuntos](/microsoft-365/security/office-365-security/atp-safe-attachments) protege contra malware y virus desconocidos y proporciona protección de día cero para proteger el sistema de mensajería. Todos los mensajes y datos adjuntos que no tienen una firma conocida de virus o malware se enruta a un entorno especial donde Defender para Office 365 usa una variedad de técnicas de aprendizaje automático y análisis para detectar intenciones malintencionadas. Si no se detecta ninguna actividad sospechosa, se libera el mensaje para su entrega al buzón de correo.

> [!NOTE]
> Caja fuerte El examen de datos adjuntos se lleva a cabo en la misma región donde residen Office 365 datos. Para más información sobre la geografía de centros de datos, consulte [¿Dónde se encuentran los datos?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Vínculos seguros

La [característica Caja fuerte links protege](/microsoft-365/security/office-365-security/atp-safe-links) proactivamente a los usuarios de direcciones URL malintencionadas en un mensaje o en un Office documento. La protección se mantiene cada vez que seleccionan el vínculo, ya que los vínculos maliciosos se bloquean de forma dinámica mientras se puede acceder a los vínculos buenos.

Los vínculos seguros están disponibles para las direcciones URL en las siguientes aplicaciones:

- Aplicaciones Microsoft 365 para empresas en Windows o Mac

- Office para la web (Microsoft Word en la Web, Microsoft Excel en la Web, Microsoft PowerPoint en la Web, y Microsoft OneNote en la Web)

- Word, Excel y PowerPoint en Windows

- Canales de Microsoft Teams y chats

> [!NOTE]
> Los usuarios deben tener licencia para Defender para Office 365 , deben incluirse en las directivas de vínculos de Caja fuerte y deben haber iniciado sesión en sus dispositivos para que la protección esté <sup>\*</sup> en su lugar.
>
> <sup>\*</sup>Para defender en toda la organización Office 365 licencias (por ejemplo, ATP_ENTERPRISE_FACULTY), no es necesario asignar Defender para Office 365 licencias a usuarios individuales.
>
> Para obtener más información acerca de Caja fuerte de vínculos, [vea Caja fuerte Links in Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

### <a name="safe-documents"></a>Documentos seguros

La [característica Caja fuerte documents usa](/microsoft-365/security/office-365-security/safe-docs) Microsoft Defender para [Endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) para examinar documentos y archivos que se abren en la [vista protegida](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653).

¿Qué necesita saber antes de comenzar?

- Caja fuerte Los documentos ya están disponibles para los usuarios con Office versión 2004 (12730.x) o superior. Esta característica está desactivada de forma predeterminada y deberá estar habilitada por el administrador de seguridad.

- Esta característica solo está disponible para los usuarios con la licencia Microsoft 365 E5 o Seguridad de Microsoft 365 E5 (no se incluye en Defender para Office 365 planes).

- Word, Excel y PowerPoint en Windows

- Canales de Microsoft Teams y chats

> [!NOTE]
> Los usuarios deben tener licencia para Microsoft 365 E5 o Seguridad de Microsoft 365 E5 , deben incluirse en las directivas de documentos de Caja fuerte y deben haber iniciado sesión en sus dispositivos para que la protección esté <sup>\*</sup> en su lugar.
>
> Para obtener más información sobre Caja fuerte documentos, [vea Caja fuerte Documents in Microsoft 365 E5](/microsoft-365/security/office-365-security/safe-docs).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP para SharePoint, OneDrive y Microsoft Teams

[ATP para SharePoint, OneDrive y Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) ayuda a detectar y bloquear archivos que se identifican como malintencionados en sitios de grupo y bibliotecas de documentos. Además, la protección Caja fuerte vínculos está disponible en Microsoft Teams canales y chats.

### <a name="anti-phishing-policies"></a>Directivas de protección contra phishing

[Anti-phishing](/microsoft-365/security/office-365-security/atp-anti-phishing) comprueba los mensajes entrantes en busca de indicadores de que un mensaje puede ser un intento de suplantación de identidad. Cuando Defender cubre a los usuarios para directivas de Office 365 (datos adjuntos de Caja fuerte, vínculos de Caja fuerte o anti phishing), los mensajes entrantes se evalúan mediante varios modelos de aprendizaje automático que analizan los mensajes y se toman las medidas adecuadas, en función de las directivas configuradas.

### <a name="real-time-reports"></a>Informes en tiempo real

Las funcionalidades de supervisión disponibles en el Centro de seguridad & Cumplimiento ( ) incluyen informes y conocimientos en tiempo real que permiten a los administradores de seguridad y cumplimiento centrarse en problemas de alta prioridad, como ataques de seguridad o mayor actividad [https://protection.office.com](https://protection.office.com) sospechosa. [](/microsoft-365/security/office-365-security/view-reports-for-atp) Además de destacar las áreas problemáticas, los informes inteligentes y los conocimientos incluyen recomendaciones y vínculos para ver y explorar datos y también realizar acciones rápidas.

### <a name="explorer"></a>Explorador

Explorer (también conocido como el explorador de amenazas) es un informe en tiempo real que permite a los usuarios autorizados identificar y analizar las amenazas recientes. De forma predeterminada, este informe muestra los datos de los últimos siete días; sin embargo, las vistas se pueden modificar para mostrar los datos de los últimos 30 días.

El Explorador contiene vistas, como Malware (para correo electrónico y contenido), Envíos, Suplantación de identidad y Todo el correo electrónico. Para ver cómo se compara Explorer con las detecciones en tiempo real, [descargue este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obtener más información acerca del Explorador (en Microsoft Defender para Office 365 Plan 2) y las detecciones en tiempo real (en Microsoft Defender para el Plan 1 de Office 365), consulte Explorador de amenazas y detecciones en tiempo [real.](/microsoft-365/security/office-365-security/threat-explorer)

### <a name="real-time-detections"></a>Detecciones en tiempo real

Las detecciones en tiempo real son un informe en tiempo real que permite a los usuarios autorizados identificar y analizar las amenazas recientes. De forma predeterminada, al igual que el Explorador, este informe muestra datos de los últimos siete días.

Las detecciones en tiempo real contienen vistas, como malware (para correo electrónico y contenido), envíos y phishing. Para ver cómo se comparan las detecciones en tiempo real con el Explorador, [descargue este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obtener más información acerca del Explorador (en Microsoft Defender para Office 365 Plan 2) y las detecciones en tiempo real (en Microsoft Defender para el Plan 1 de Office 365), vea Explorador de amenazas (y detecciones en tiempo [real).](/microsoft-365/security/office-365-security/threat-explorer)

### <a name="threat-trackers"></a>Rastreadores de amenazas

[Los rastreadores de amenazas](/microsoft-365/security/office-365-security/threat-trackers) son widgets informativos y vistas que proporcionan a los usuarios autorizados inteligencia sobre problemas de ciberseguridad que pueden afectar a su organización.

### <a name="automated-incident-response"></a>Respuesta automatizada a incidentes

[Las capacidades](/microsoft-365/security/office-365-security/office-365-air) automatizadas de respuesta a incidentes (AIR) disponibles en Defender para Office 365 Plan 2 le permiten ejecutar procesos de investigación automatizados en respuesta a amenazas conocidas que existen actualmente. Al automatizar determinadas tareas de investigación, el equipo de operaciones de seguridad puede funcionar de forma más eficaz y eficaz. Las acciones de corrección, como eliminar mensajes de correo electrónico malintencionados, se toman tras la aprobación del equipo de operaciones de seguridad. Para obtener más información, vea [How AIR works in Office 365](/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulation-training"></a>Aprendizaje de simulación de ataques

[El aprendizaje de simulación](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) de ataques es una herramienta inteligente de administración de riesgos sociales que automatiza la creación y administración de simulaciones de phishing. Las simulaciones ayudan a los clientes a detectar, priorizar y corregir los riesgos de suplantación de identidad mediante el uso de señuelos de phishing en el mundo real y formación hiperespeda para cambiar el comportamiento de los empleados.

- El entrenamiento de simulación de ataques ya está disponible en WW y GCC (estará en GCC a partir del 21 de junio).
- Para obtener más información sobre cómo empezar, consulta Introducción al [aprendizaje de simulación de ataques.](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)
- Hay disponibles varias técnicas de ataque que aplican cargas de suplantación de identidad sin armas en el mundo real que replican el comportamiento de los atacantes del mundo real para hacer que las simulaciones de suplantación de identidad sean relevantes.
- Este servicio está disponible para las organizaciones que tienen Microsoft 365 E5, Office 365 E5 o Microsoft Defender para Office 365 [licencias del Plan 2.](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) Como prueba, se ofrece un subconjunto de capacidades a los clientes de E3.
- Para obtener más información y probar una simulación, vea [Simulate a phishing attack](/microsoft-365/security/office-365-security/attack-simulation-training).