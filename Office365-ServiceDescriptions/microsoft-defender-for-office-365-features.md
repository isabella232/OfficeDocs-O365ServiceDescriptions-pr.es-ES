---
title: Descripción del servicio De Microsoft Defender para Office 365 características
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
ms.assetid: ''
description: Obtenga información sobre las características disponibles en Microsoft Defender para Office 365.
ms.openlocfilehash: 620639a2c40d589123ebda33446411533798d2ec
ms.sourcegitcommit: 7ee8775831fd481ab2ef477245d2ae2af98ac2d7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/30/2021
ms.locfileid: "53204874"
---
# <a name="microsoft-defender-for-office-365-features-service-description"></a>Descripción del servicio De Microsoft Defender para Office 365 características

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Novedades de Microsoft Defender para Office 365

Seguimos agregando nuevas características a Defender para Office 365. Para obtener más información sobre las nuevas características que vienen a Defender Office 365 (o Microsoft 365 en general), vea los siguientes recursos:

- [Plan de desarrollo de Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap)

- [Novedades de Microsoft Defender para Office 365: Office 365 | Microsoft Docs](/microsoft-365/security/office-365-security/whats-new-in-defender-for-office-365)

## <a name="defender-for-office-365-capabilities"></a>Defender para Office 365 capacidades

### <a name="safe-attachments"></a>Archivos adjuntos seguros

[Caja fuerte datos adjuntos](/microsoft-365/security/office-365-security/atp-safe-attachments) protege contra malware y virus desconocidos y proporciona protección de día cero para proteger el sistema de mensajería. Todos los mensajes y datos adjuntos que no tienen una firma conocida de virus o malware se enruta a un entorno especial donde Defender para Office 365 usa una variedad de técnicas de aprendizaje automático y análisis para detectar intenciones malintencionadas. Si no se detecta ninguna actividad sospechosa, se libera el mensaje para su entrega al buzón de correo.

> [!NOTE]
> Caja fuerte El examen de datos adjuntos se lleva a cabo en la misma región donde residen Office 365 datos. Para más información sobre la geografía de centros de datos, consulte [¿Dónde se encuentran los datos?](/microsoft-365/enterprise/o365-data-locations)

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

### <a name="protection-for-sharepoint-onedrive-and-microsoft-teams"></a>Protección para SharePoint, OneDrive y Microsoft Teams

[La protección SharePoint, OneDrive y Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) ayuda a detectar y bloquear archivos que se identifican como malintencionados en sitios de grupo y bibliotecas de documentos. Además, la protección Caja fuerte vínculos está disponible en Microsoft Teams canales y chats.

### <a name="anti-phishing-policies"></a>Directivas de protección contra phishing

[Anti-phishing](/microsoft-365/security/office-365-security/atp-anti-phishing) comprueba los mensajes entrantes en busca de indicadores de que un mensaje puede ser un intento de suplantación de identidad. Cuando Defender cubre a los usuarios para directivas de Office 365 (datos adjuntos de Caja fuerte, vínculos de Caja fuerte o anti phishing), los mensajes entrantes se evalúan mediante varios modelos de aprendizaje automático que analizan los mensajes y se toman las medidas adecuadas, en función de las directivas configuradas.

### <a name="real-time-reports"></a>Informes en tiempo real

Las capacidades de supervisión disponibles en el Centro de seguridad y cumplimiento de [&](https://protection.office.com) incluyen informes y [conocimientos](/microsoft-365/security/office-365-security/view-reports-for-atp) en tiempo real que permiten a los administradores de seguridad y cumplimiento centrarse en problemas de alta prioridad, como ataques de seguridad o mayor actividad sospechosa. Además de destacar las áreas problemáticas, los informes inteligentes y los conocimientos incluyen recomendaciones y vínculos para ver y explorar datos y también realizar acciones rápidas.

### <a name="threat-explorer"></a>Explorador de amenazas

El Explorador de amenazas (también denominado Explorador) es un informe en tiempo real que permite a los usuarios autorizados identificar y analizar las amenazas recientes. De forma predeterminada, este informe muestra los datos de los últimos siete días; sin embargo, las vistas se pueden modificar para mostrar los datos de los últimos 30 días.

El Explorador contiene vistas, como Malware (para correo electrónico y contenido), Envíos, Suplantación de identidad y Todo el correo electrónico. Para ver cómo se compara Explorer con las detecciones en tiempo real, [descargue este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obtener más información acerca del Explorador (en Microsoft Defender para Office 365 Plan 2) y las detecciones en tiempo real (en Microsoft Defender para el Plan 1 de Office 365), consulte Explorador de amenazas y detecciones en tiempo [real.](/microsoft-365/security/office-365-security/threat-explorer)

### <a name="real-time-detections"></a>Detecciones en tiempo real

Las detecciones en tiempo real son un informe en tiempo real que permite a los usuarios autorizados identificar y analizar las amenazas recientes. De forma predeterminada, al igual que el Explorador, este informe muestra datos de los últimos siete días.

Las detecciones en tiempo real contienen vistas, como malware (para correo electrónico y contenido), envíos y phishing. Para ver cómo se comparan las detecciones en tiempo real con el Explorador, [descargue este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obtener más información acerca del Explorador (en Microsoft Defender para Office 365 Plan 2) y las detecciones en tiempo real (en Microsoft Defender para el Plan 1 de Office 365), consulte Explorador de amenazas y detecciones en tiempo [real.](/microsoft-365/security/office-365-security/threat-explorer)

### <a name="threat-trackers"></a>Rastreadores de amenazas

[Los rastreadores de amenazas](/microsoft-365/security/office-365-security/threat-trackers) son widgets informativos y vistas que proporcionan a los usuarios autorizados inteligencia sobre problemas de ciberseguridad que pueden afectar a su organización.

### <a name="automated-investigation--response"></a>Respuesta automática de & investigación

[Las capacidades](/microsoft-365/security/office-365-security/office-365-air) de respuesta & investigación automatizada (AIR) disponibles en Defender for Office 365 Plan 2 le permiten ejecutar procesos de investigación automatizados en respuesta a amenazas conocidas que existen actualmente. Al automatizar determinadas tareas de investigación, el equipo de operaciones de seguridad puede funcionar de forma más eficaz y eficaz. Las acciones de corrección, como eliminar mensajes de correo electrónico malintencionados, se toman tras la aprobación del equipo de operaciones de seguridad. Para obtener más información, vea [How AIR works in Office 365](/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulation-training"></a>Aprendizaje de simulación de ataque

[El aprendizaje de simulación](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) de ataques es una herramienta inteligente de administración de riesgos sociales que automatiza la creación y administración de simulaciones de phishing. Las simulaciones ayudan a los clientes a detectar, priorizar y corregir los riesgos de suplantación de identidad mediante el uso de señuelos de phishing en el mundo real y formación hiperespeda para cambiar el comportamiento de los empleados.

- El entrenamiento de simulación de ataques ya está disponible en WW y GCC (estará en GCC a partir del 21 de junio).
- Para obtener más información sobre cómo empezar, consulta Introducción al [aprendizaje de simulación de ataques.](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)
- Hay disponibles varias técnicas de ataque que aplican cargas de suplantación de identidad sin armas en el mundo real que replican el comportamiento de los atacantes del mundo real para hacer que las simulaciones de suplantación de identidad sean relevantes.
- Este servicio está disponible para las organizaciones que tienen Microsoft 365 E5, Office 365 E5 o Microsoft Defender para Office 365 [licencias del Plan 2.](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) Como prueba, se ofrece un subconjunto de capacidades a los clientes de E3.
- Para obtener más información y probar una simulación, vea [Simulate a phishing attack](/microsoft-365/security/office-365-security/attack-simulation-training).