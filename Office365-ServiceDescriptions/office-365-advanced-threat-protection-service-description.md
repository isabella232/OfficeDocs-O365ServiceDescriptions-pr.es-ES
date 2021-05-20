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
description: Microsoft Defender for Office 365 es un servicio de filtrado de correo electrónico basado en la nube que ayuda a proteger su organización contra malware y virus desconocidos al proporcionar una protección sólida de día cero e incluye características para proteger a su organización de vínculos dañinos en tiempo real.
ms.openlocfilehash: 76b4d2e53c8a2942d4b974c5289c9ae4c8854b72
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52545977"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Descripción del servicio de Microsoft Defender para Office 365

Microsoft Defender for Office 365 es un servicio de filtrado de correo electrónico basado en la nube que ayuda a proteger su organización contra malware y virus desconocidos al proporcionar una protección sólida de día cero e incluye características para proteger a su organización de vínculos dañinos en tiempo real. Defender for Office 365 tiene funciones enriquecidas de informes y seguimiento de URL que proporcionan a los administradores información sobre el tipo de ataques que ocurren en su organización.

A continuación se presentan las principales formas en las que puede usar Defender para Office 365 para la protección de mensajes:

- En un escenario de solo filtrado de Defender for Office 365, Defender for Office 365 proporciona protección de correo electrónico basada en la nube para el entorno de Exchange Server local o cualquier otra solución de correo electrónico SMTP local.

- Defender for Office 365 se puede habilitar para proteger Exchange Online buzones hospedados en la nube. Para obtener más información sobre Exchange Online, consulte la [descripción del servicio Exchange Online](exchange-online-service-description/exchange-online-service-description.md).

- En una implementación híbrida, Defender for Office 365 se puede configurar para proteger el entorno de mensajería y controlar el enrutamiento de correo cuando tiene una combinación de buzones locales y en la nube con Exchange Online Protection para el filtrado de correo electrónico entrante.

## <a name="microsoft-defender-for-office-365-availability"></a>Microsoft Defender para Office 365 disponibilidad

Microsoft Defender para Office 365 Plan 2 se incluye en Office 365 E5, Office 365 A5, Seguridad de Microsoft 365 E5 y Microsoft 365 E5 como se especifica aquí: [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](/microsoft-365/security/office-365-security/office-365-atp) . Defender for Office 365 Plan 1 está incluido en Microsoft 365 Empresa Premium.

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

Para comprar Microsoft Defender para Office 365, consulte [Microsoft Defender para obtener Office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Para obtener información detallada sobre el plan sobre las suscripciones que permiten a los usuarios de Microsoft Defender para Office 365, consulte la [tabla de comparación de suscripciones completa.](https://go.microsoft.com/fwlink/?linkid=2139145)

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>¿Qué hay de nuevo en Microsoft Defender para Office 365

Seguimos agregando nuevas características a Defender para Office 365. Para obtener más información sobre las nuevas características que llegan a Defender para Office 365 (o Microsoft 365 en general), consulte los siguientes recursos:

- [Plan de desarrollo de Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [¿Qué hay de nuevo en Microsoft Defender para Office 365](/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Requisitos para Microsoft Defender para Office 365

Defender para Office 365 se puede usar con cualquier agente de transferencia de correo SMTP, como Microsoft Exchange Server. Para obtener información acerca de los sistemas operativos, exploradores web e idiomas compatibles con Defender para Office 365, consulte las secciones "Exploradores admitidos" e "Idiomas admitidos" en [Exchange centro de administración en Exchange Online Protection](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Disponibilidad de características en defender planes de Office 365

A continuación, se incluye cada característica. Cuando se menciona Exchange Online, por lo general se refiere a la familia de servicios de Office 365 Enterprise.<br><br>

| Característica | Defender para Office 365 Plan 1 | Defender para Office 365 Plan 2 | Seguridad Microsoft 365 E5 / A5|
|:-----|:-----|:-----|:-----|
|*Configuración, protección y detección*|
|[Datos adjuntos seguros](#safe-attachments)|Sí|Sí|Sí|
|Caja fuerte Accesorios en Teams|Sí|Sí|Sí|
|[Vínculos seguros](#safe-links)|Sí|Sí|Sí|
|[Documentos seguros](#safe-documents)|No|No|Sí|
|Vínculos seguros en Teams|Sí|Sí|Sí|
|[ATP para SharePoint, OneDrive y Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Sí|Sí|Sí|
|[Directivas contra phishing](#anti-phishing-policies)|Sí|Sí|Sí|
|[Informes en tiempo real](#real-time-reports)|Sí|Sí|Sí|
|*Automatización, investigación, remediación y educación*|
|[Rastreadores de amenazas](#threat-trackers)|No|Sí|Sí|
|Investigación de amenazas (investigación avanzada de amenazas)|[Detecciones en tiempo real](#real-time-detections)|[Explorador](#explorer)|[Explorador](#explorer)|
|[Respuesta automatizada a incidentes](#automated-incident-response)|No|Sí|Sí|
|[Entrenamiento de simulación de ataque](#attack-simulation-training)|No|Sí|Sí|
|*Integración con [Microsoft 365 Defender](/microsoft-365/security/mtp/microsoft-threat-protection)*|No|Sí|Sí|

> [!NOTE]
> Si su inquilino solo tiene Microsoft Defender para Office licencia de prueba del Plan P2 o Office 365 licencia de prueba E5, sin otra licencia elegible para Microsoft 365 Defender, no podrá acceder a Microsoft 365 Defender. Para obtener más información sobre la licencia MTP, consulte [Microsoft 365 Requisitos de Defender](/microsoft-365/security/mtp/prerequisites).

## <a name="defender-for-office-365-capabilities"></a>Defensor de las capacidades de Office 365

### <a name="safe-attachments"></a>Archivos adjuntos seguros

[Caja fuerte Attachments](/microsoft-365/security/office-365-security/atp-safe-attachments) protege contra malware y virus desconocidos, y proporciona protección de día cero para proteger su sistema de mensajería. Todos los mensajes y archivos adjuntos que no tienen una firma de virus/malware conocida se enrutan a un entorno especial donde Defender for Office 365 utiliza una variedad de técnicas de aprendizaje automático y análisis para detectar intenciones maliciosas. Si no se detecta ninguna actividad sospechosa, se libera el mensaje para su entrega al buzón de correo.

> [!NOTE]
> Caja fuerte La exploración de archivos adjuntos tiene lugar en la misma región donde residen los datos de Office 365. Para más información sobre la geografía de centros de datos, consulte [¿Dónde se encuentran los datos?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Vínculos seguros

La característica [vínculos de Caja fuerte](/microsoft-365/security/office-365-security/atp-safe-links) protege proactivamente a los usuarios de direcciones URL maliciosas en un mensaje o en un documento de Office. La protección se mantiene cada vez que seleccionan el vínculo, ya que los vínculos maliciosos se bloquean de forma dinámica mientras se puede acceder a los vínculos buenos.

Los vínculos seguros están disponibles para las direcciones URL en las siguientes aplicaciones:

- Aplicaciones Microsoft 365 para empresas en Windows o Mac

- Office para la web (Microsoft Word en la Web, Microsoft Excel en la Web, Microsoft PowerPoint en la Web, y Microsoft OneNote en la Web)

- Palabra, Excel y PowerPoint el Windows

- Canales de Microsoft Teams y chats

> [!NOTE]
> Los usuarios deben tener licencia para Defender para <sup>\*</sup> Office 365, deben incluirse en Caja fuerte directivas de vínculos y deben iniciar sesión en sus dispositivos para que haya protección.
>
> <sup>\*</sup>Para las licencias de Defender para Office 365 en toda la organización (por ejemplo, ATP_ENTERPRISE_FACULTY), no es necesario asignar Defender para licencias de Office 365 a usuarios individuales.
>
> Para obtener más información acerca de Caja fuerte protección de vínculos, vea [vínculos Caja fuerte en Microsoft Defender para obtener Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

### <a name="safe-documents"></a>Documentos seguros

La [característica documentos Caja fuerte](/microsoft-365/security/office-365-security/safe-docs) usa Microsoft Defender para endpoint [para](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) analizar documentos y archivos que se abren en la [vista protegida.](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)

¿Qué necesita saber antes de comenzar?

- Caja fuerte Los documentos ahora están generalmente disponibles para los usuarios con Office versión 2004 (12730.x) o superior! Esta característica está desactivada de forma predeterminada y el Administrador de seguridad tendrá que habilitarla.

- Esta función solo está disponible para los usuarios con la licencia de Microsoft 365 E5 o Seguridad de Microsoft 365 E5 (no incluida en Defender para planes de Office 365).

- Palabra, Excel y PowerPoint el Windows

- Canales de Microsoft Teams y chats

> [!NOTE]
> Los usuarios deben tener licencia para Microsoft 365 E5 o <sup>\*</sup> Seguridad de Microsoft 365 E5, deben incluirse en Caja fuerte directivas de documentos y deben iniciar sesión en sus dispositivos para que haya protección.
>
> Para obtener más información acerca de Caja fuerte Protección de documentos, consulte [documentos Caja fuerte en Microsoft 365 E5](/microsoft-365/security/office-365-security/safe-docs).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP para SharePoint, OneDrive y Microsoft Teams

[ATP para SharePoint, OneDrive y Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) ayuda a detectar y bloquear archivos que se identifican como maliciosos en sitios de equipo y bibliotecas de documentos. Además, Caja fuerte protección de enlaces ya está disponible en canales y chats Microsoft Teams.

### <a name="anti-phishing-policies"></a>Directivas de protección contra phishing

[Antiphishing](/microsoft-365/security/office-365-security/atp-anti-phishing) comprueba los mensajes entrantes en busca de indicadores de que un mensaje podría ser un intento de phishing. Cuando defender para Office 365 las directivas de Office 365 (Caja fuerte adjuntos, vínculos Caja fuerte o antiphishing), los mensajes entrantes son evaluados por varios modelos de aprendizaje automático que analizan los mensajes y se realiza la acción adecuada, en función de las directivas configuradas.

### <a name="real-time-reports"></a>Informes en tiempo real

Las capacidades de supervisión disponibles en el Centro de cumplimiento de & de seguridad ( [https://protection.office.com](https://protection.office.com) ) incluyen informes en tiempo real e [información](/microsoft-365/security/office-365-security/view-reports-for-atp) que permiten a los administradores de seguridad y cumplimiento centrarse en problemas de alta prioridad, como ataques de seguridad o mayor actividad sospechosa. Además de resaltar las áreas problemáticas, los informes e información inteligentes incluyen recomendaciones y enlaces para ver y explorar datos y también tomar medidas rápidas.

### <a name="explorer"></a>Explorador

Explorer (también conocido como el explorador de amenazas) es un informe en tiempo real que permite a los usuarios autorizados identificar y analizar las amenazas recientes. De forma predeterminada, este informe muestra datos de los últimos siete días; sin embargo, las vistas se pueden modificar para mostrar datos durante los últimos 30 días.

El Explorador contiene vistas, como Malware (para correo electrónico y contenido), Envíos, Phish y Todo el correo electrónico. Para ver cómo se compara explorer con detecciones en tiempo real, [descargue este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obtener más información acerca del Explorador (en Microsoft Defender para Office 365 Plan 2) y detecciones en tiempo real (en Microsoft Defender para Office 365 Plan 1), vea [Explorador de amenazas y detecciones en tiempo real.](/microsoft-365/security/office-365-security/threat-explorer)

### <a name="real-time-detections"></a>Detecciones en tiempo real

Las detecciones en tiempo real son un informe en tiempo real que permite a los usuarios autorizados identificar y analizar las amenazas recientes. De forma similar al Explorador, de forma predeterminada, este informe muestra datos de los últimos siete días.

Las detecciones en tiempo real contienen vistas, como Malware (para correo electrónico y contenido), Envíos y Phishing. Para ver cómo se comparan las detecciones en tiempo real con explorer, [descargue este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obtener más información acerca del Explorador (en Microsoft Defender para Office 365 Plan 2) y detecciones en tiempo real (en Microsoft Defender para Office 365 Plan 1), vea [Explorador de amenazas (y detecciones en tiempo real).](/microsoft-365/security/office-365-security/threat-explorer)

### <a name="threat-trackers"></a>Rastreadores de amenazas

[Los rastreadores de amenazas](/microsoft-365/security/office-365-security/threat-trackers) son widgets informativos y vistas que proporcionan a los usuarios autorizados inteligencia sobre problemas de ciberseguridad que podrían afectar a su organización.

### <a name="automated-incident-response"></a>Respuesta automatizada a incidentes

Las capacidades [automatizadas de respuesta](/microsoft-365/security/office-365-security/office-365-air) a incidentes (AIR) disponibles en Defender para Office 365 Plan 2 le permiten ejecutar procesos de investigación automatizados en respuesta a amenazas conocidas que existen hoy en día. Mediante ciertas tareas de investigación automatizadas, su equipo de operaciones de seguridad puede funcionar de manera más eficiente y eficaz. Las acciones de corrección, como la eliminación de mensajes de correo electrónico malintencionados, se toman tras la aprobación del equipo de operaciones de seguridad. Para obtener más información, consulte [Cómo funciona AIR en Office 365](/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulation-training"></a>Entrenamiento de simulación de ataque

[La formación en simulación de](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) ataques es una herramienta inteligente de gestión de riesgos sociales que automatiza la creación y gestión de simulaciones de phishing. Las simulaciones ayudan a los clientes a detectar, priorizar y corregir los riesgos de phishing mediante el uso de señuelos de phishing del mundo real y capacitación hiper-dirigida para cambiar los comportamientos de los empleados.

- El entrenamiento de simulación de ataques ya está disponible en ww y GCC (estará en GCC a partir del 21 de junio).
- Para obtener más información sobre cómo empezar, consulte [Introducción al entrenamiento de simulación de ataques.](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)
- Varias técnicas de ataque que aplican cargas útiles de phishing des-armas y del mundo real están disponibles que replican el comportamiento de los atacantes del mundo real para hacer que las simulaciones de phishing sean relevantes.
- Este servicio está disponible para organizaciones que tienen licencias de Microsoft 365 E5, Office 365 E5 o [Microsoft Defender para Office 365 Plan 2.](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) Se ofrece un subconjunto de capacidades a los clientes de E3 como prueba.
- Para obtener más información y probar una simulación, consulte [Simular un ataque de phishing.](/microsoft-365/security/office-365-security/attack-simulation-training)