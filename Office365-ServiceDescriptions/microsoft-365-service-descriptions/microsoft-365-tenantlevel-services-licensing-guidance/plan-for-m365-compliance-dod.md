---
title: Plan para las implementaciones del Centro de cumplimiento de Microsoft 365 - DoD
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Esta guía está para profesionales de TI que impulsan implementaciones de Office 365 en entidades del Gobierno Federal de Estados Unidos u otras entidades que controlan datos que están sujetos a normativas y requisitos gubernamentales, donde el uso de Microsoft 365 Government – DoD es adecuado para cumplir estos requisitos.
ms.openlocfilehash: 039fef8da2de151828cf9aa3c2cb7e39efb4789012f70666811a8a2ae5d24238
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663333"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Plan para las implementaciones del Centro de cumplimiento de Microsoft 365 - DoD

Esta guía está para profesionales de TI que impulsan implementaciones de Office 365 en entidades del Gobierno Federal de Estados Unidos u otras entidades que controlan datos que están sujetos a normativas y requisitos gubernamentales, donde el uso de Microsoft 365 Government – DoD es adecuado para cumplir estos requisitos.

> [!NOTE]
> Si su organización ya ha cumplido los requisitos de elegibilidad de Microsoft 365 Government – DoD y solicitó y se aceptó en el programa, puede omitir los pasos 1 y 2 e ir directamente al paso 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>Paso 1. Determinar si su organización necesita Microsoft 365 Government - DoD y cumple los requisitos de elegibilidad

El entorno Microsoft 365 Government- DoD cumple con los requisitos del Gobierno de Estados Unidos para los servicios en la nube.

Además de disfrutar de las características y capacidades de Office 365, las organizaciones se benefician de las siguientes características que son únicas para Microsoft 365 Government – DoD:

- El contenido de cliente de su organización se separa lógicamente del contenido del cliente en los servicios Office 365 comerciales de Microsoft.
- El contenido del cliente de la organización se almacena dentro de los Estados Unidos.
- El acceso al contenido del cliente de la organización está restringido a personal específico de Microsoft.
- Microsoft 365 Gobierno: DoD cumple con las certificaciones y acreditaciones necesarias para los clientes del sector público estadounidense.

Puede encontrar más información sobre la oferta Microsoft 365 Government - DoD para los clientes del gobierno de estados unidos en [Office 365 Administración Pública planes,](https://products.office.com/government/compare-office-365-government-plans)incluidos los requisitos de elegibilidad.

La [Office 365 de servicio del](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) Gobierno de ESTADOS UNIDOS describe las ventajas de la plataforma, que se centra en cumplir los requisitos de cumplimiento dentro de los Estados Unidos.

> [!TIP]
> Es posible que desee transferir las tablas de información de la descripción del servicio a un libro de Excel y agregar dos columnas: Relevante para mi organización **Y/N** y Cumple las necesidades de mi organización **Y/N**. A continuación, puede revisar esta lista con sus compañeros para confirmar que este servicio satisface las necesidades de su organización.

**Puntos de decisión**:<br/>
- *Decida si Microsoft 365 Gobierno: DoD es adecuado para su organización.*
- *Confirme que su organización cumple los requisitos de elegibilidad.*

> [!NOTE]
> Microsoft 365 Gobierno: el DoD solo está disponible en Los Estados Unidos. Los clientes que no son del Gobierno de Estados Unidos pueden elegir entre una serie [de Office 365 Administración Pública planes](https://products.office.com/government/compare-office-365-government-plans).

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>Paso 2. Aplicar para Microsoft 365 Government - DoD

Después de haber decidido que este servicio es adecuado para su organización, inicie el proceso de [solicitud de este servicio](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>Paso 3. Comprender Microsoft 365 gobierno: configuración de seguridad predeterminada de DoD

Se recomienda que se tome tiempo para revisar detenidamente la configuración de seguridad y administración antes de modificarlas y tener en cuenta el impacto en el cumplimiento antes de realizar cualquier cambio en la configuración de seguridad predeterminada.

**Punto de** decisión: decida si modificará alguna de las opciones predeterminadas de *Microsoft 365 Government- DoD security settings, resolving to first understand the impact of any changes you might make.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>Paso 4. Comprender qué funcionalidades actualmente no están disponibles o deshabilitadas de forma predeterminada en Microsoft 365 Government – DoD<sup>1</sup>

Para satisfacer los requisitos de nuestros clientes en la nube gubernamentales, hay algunas diferencias entre Microsoft 365 Government - DoD y planes de empresa. Consulte la tabla siguiente para ver qué características están disponibles. Vea [aquí](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) las últimas actualizaciones de productos de cumplimiento publicadas en Microsoft 365 guía.<br><br>

| Área | Característica | Estado de doD |
|------|---------|------------|
| **Protección de la información** | Cliente y escáner de etiquetado unificados | Disponible |
| | Coincidencia exacta de datos | Disponible |
| | Clasificación y etiquetado automáticos para Exchange Online, SharePoint Online y OneDrive para la Empresa | Implementando |
| | Clasificación y etiquetado automáticos para Office aplicaciones (Word, Excel, PowerPoint, Outlook) en plataformas (web, Windows y Mac) | Disponible |
| | Clasificación y etiquetado automáticos para clientes Office móvil | En el trabajo pendiente de ingeniería |
| | Clasificación y etiquetado automáticos para Teams, Microsoft 365 grupos y SharePoint sitios | Disponible |
| | Etiquetado obligatorio | Disponible |
| | Etiquetado de confidencialidad manual en Office aplicaciones (iOS, Android, Windows) | Disponible |
| | Configuración de etiquetas de confidencialidad para la protección de solo cifrado en Outlook mensajes | Implementando |
| **Análisis** | Clasificación de datos: Introducción y Explorador de contenido | Implementando |
| | Análisis: clasificadores de aprendizaje automático con etiquetado automático en el lado del servicio | En desarrollo |
| | Análisis: clasificadores de aprendizaje automático con etiquetado automático en Office aplicaciones/cliente | Implementando |
| **Cifrado** | Base Cifrado de mensajes de Office 365 (E3) | Disponible |
| | Advanced Cifrado de mensajes de Office 365 (E5) | Disponible |
| | Bring Your Own Key (BYOK) para el ciclo de vida de aprovisionamiento de claves administradas por el cliente | Disponible |
| | Clave del cliente de Office 365 | Disponible |
| | Cifrado de claves doble | Disponible |
| **Prevención de pérdida de datos** | Prevención de pérdida de datos (DLP) para archivos y correo electrónico | Disponible |
| | DLP para conversaciones Teams chat y canal | Disponible |
| | DLP: Panel de alertas | Implementando |
| | Extremo DLP | En desarrollo |
| | DLP On-prem | En el trabajo pendiente de ingeniería |
| | Página Información general de DLP | En desarrollo |
| **Gobierno de información** | Gobierno de la información: Archivado de correo electrónico | Disponible |
| | Gobierno de la información: bloqueo de conservación | Disponible |
| | Gobierno de la información: Importar PST | Disponible |
| | Gobierno de la información: aplicar etiquetas de retención que no son de registro manualmente | Disponible |
| | Gobierno de la información: aplicar etiquetas de retención predeterminadas para SharePoint/OneDrive para la Empresa bibliotecas, carpetas y conjuntos de documentos; Exchange bandejas de entrada; y Office 365 grupos | Disponible |
| | Gobierno de la información: aplicar una única etiqueta de retención predeterminada a toda la organización; ubicaciones o usuarios específicos; y automáticamente en función de una condición específica (por ejemplo, palabras clave o información confidencial) | Disponible |
| | Gobierno de la información: aplicar una etiqueta predeterminada para Exchange bandejas de entrada | Disponible |
| | Gobierno de la información: revisión de disposición de varias fases | En el trabajo pendiente de ingeniería |
| | Gobierno de la información: directivas de retención con clasificadores capacitados | En desarrollo |
| | Gobierno de la información: directivas de retención para Teams chat | Implementando |
| | Gobierno de la información: directivas de retención para Teams de reuniones | Disponible |
| | Gobierno de la información: directivas de retención Teams mensajes de canal privado | En el trabajo pendiente de ingeniería |
| | Gobierno de la información: ámbitos adaptables de directivas de retención y etiquetado | En desarrollo |
| | Administración de registros: aplicar la etiqueta de registro manualmente | Disponible |
| | Administración de registros: aplique una etiqueta de registro predeterminada para SharePoint, OneDrive para la Empresa bibliotecas, carpetas y conjuntos de documentos; y Office 365 grupos | Disponible |
| | Administración de registros: directivas de registro automáticas basadas en condiciones específicas (por ejemplo, palabras clave o información confidencial); y en función de un evento | Disponible |
| | Administración de registros: revisión de disposición | Disponible |
| | Administración de registros: Administrador de planes de archivos | Disponible |
| | Administración de registros: prueba de eliminación | Disponible |
| | Administración de registros: control de versiones de registros | Disponible |
| | Administración de registros: registros reglamentarios | Disponible |
| | Administración de registros: usar la SharePoint Syntex de registros para aplicar etiquetas de registro | En el trabajo pendiente de ingeniería |
| **Administración de riesgos de Insider** | Caja de seguridad del cliente | Disponible |
| | Administración de riesgos de Insider: panel de casos, Explorador de contenido y plantillas de aviso | Implementando |
| | Administración de riesgos de Insider: escala para la investigación de Advanced eDiscovery | Implementando |
| | Administración de riesgos de Insider: robo de datos por parte de los usuarios que salen | Implementando |
| | Administración de riesgos de Insider: pérdidas de datos generales | Implementando |
| | Insider Risk Management: Investigar alertas de administración de riesgos de insider | Implementando |
| | Administración de riesgos de Insider: Office indicadores de Teams, SharePoint web, mensajería de correo electrónico | Implementando |
| | Explorador de actividades de administración de riesgos de Insider | En el trabajo pendiente de ingeniería |
| | Administración de riesgos de Insider: Indicadores de dispositivos para la actividad en Windows 10 compilación 1809 y posterior | En el trabajo pendiente de ingeniería |
| | Administración de riesgos de Insider: indicadores de Microsoft Defender para alertas de extremo | En el trabajo pendiente de ingeniería |
| | Administración de riesgos de Insider: indicadores de infracción de la directiva de seguridad | En el trabajo pendiente de ingeniería |
| | Administración de riesgos de Insider: plantillas de directiva para pérdidas de datos por parte de usuarios inconformes | En el trabajo pendiente de ingeniería |
| | Administración de riesgos de Insider: plantillas de directiva para pérdidas de datos por parte de usuarios prioritarios | En el trabajo pendiente de ingeniería |
| | Administración de riesgos de Insider: plantillas de directiva para infracciones de directivas de seguridad general | En el trabajo pendiente de ingeniería |
| | Administración de riesgos de Insider: plantillas de directiva para infracciones de directivas de seguridad por parte de usuarios prioritarios, usuarios que salen, usuarios descontentos (versión preliminar) | En el trabajo pendiente de ingeniería |
| | Administración de riesgos de Insider: personalización de directivas | En el trabajo pendiente de ingeniería |
| | Administración de riesgos de Insider: Exportar alertas | En el trabajo pendiente de ingeniería |
| | Administración de riesgos de Insider: Microsoft Teams integración | En el trabajo pendiente de ingeniería |
| | Administración de riesgos de Insider: grupos de usuarios prioritarios | En el trabajo pendiente de ingeniería |
| | Cumplimiento de la comunicación: crear directivas de cliente, 3 preconfiguradas | Disponible |
| | Cumplimiento de la comunicación: compatibilidad con Teams, Exchange y quitar Teams mensaje | Disponible |
| | Cumplimiento de la comunicación: obtener acceso a alertas; plantillas de aviso; panel de directivas de comunicación | Disponible |
| | Cumplimiento de la comunicación: escala para la investigación de Advanced eDiscovery | Disponible |
| | Cumplimiento de la comunicación: detecta una infracción de código de conducta repetida con el tiempo | Disponible |
| | Cumplimiento de la comunicación: compatibilidad con permisos más granulares | Disponible |
| | Cumplimiento de la comunicación: analizar Teams de chat de usuarios con buzón local | Disponible |
| | Cumplimiento de la comunicación: plantilla conflicto de intereses | Disponible |
| | Cumplimiento de la comunicación: capacidad para omitir la firma de correo electrónico o la declinación de responsabilidades | En desarrollo |
| | Cumplimiento de la comunicación: capacidad para establecer un período de retención para una directiva de cumplimiento de comunicaciones | En el trabajo pendiente de ingeniería |
| | Cumplimiento de la comunicación: detectar contenido para adultos | En el trabajo pendiente de ingeniería |
| | Cumplimiento de la comunicación: entrega de la administración de riesgos de Insider | En desarrollo |
| | Cumplimiento de la comunicación: comprobación del estado de la directiva y capacidad para pausar la directiva | En desarrollo |
| | Cumplimiento de la comunicación: admite 7 idiomas para amenazas, hostigamiento dirigido y clasificadores de profanidades | En desarrollo |
| | Cumplimiento de la comunicación: traducir contenido de estado durante la investigación | En desarrollo |
| | Barreras de información | Implementando |
| | Administración del acceso con privilegios | En el trabajo pendiente de ingeniería |
| **Detectar & responder** | Exhibición de documentos electrónicos principal: conservación local | Disponible |
| | EDiscovery principal: administración de casos | Disponible |
| | EDiscovery principal: Búsqueda | Disponible |
| | EDiscovery principal: Exportar | Disponible |
| | EDiscovery principal: descifrado de RMS | Disponible |
| | EDiscovery principal: exportación nativa | Disponible |
| | EDiscovery principal: Auditoría | Disponible |
| | EDiscovery principal: límites de cumplimiento para OneDrive para la Empresa | Implementando |
| | Advanced eDiscovery: procesamiento avanzado | Disponible |
| | Advanced eDiscovery: compatibilidad con bytes CJK/Double para Advanced eDiscovery | Disponible |
| | Advanced eDiscovery: asignación de custodia a carga de trabajo | Disponible |
| | Advanced eDiscovery: comunicaciones de custodia | Disponible |
| | Advanced eDiscovery: Panel | Disponible |
| | Advanced eDiscovery: Subprocesos de correo electrónico | Disponible |
| | Advanced eDiscovery: Exportar (descargar, exportar, agregar a otro conjunto de opiniones) | Disponible |
| | Advanced eDiscovery: Filtrado | Disponible |
| | Advanced eDiscovery: Identificación casi duplicada | Disponible |
| | Advanced eDiscovery: codificación predictiva | Disponible |
| | Advanced eDiscovery: Exportación procesada con archivo de carga | Disponible |
| | Advanced eDiscovery: Redacciones | Disponible |
| | Advanced eDiscovery: conjuntos de revisión | Disponible |
| | Advanced eDiscovery: Revisar y anotar | Disponible |
| | Advanced eDiscovery: Informe de términos de búsqueda | Disponible |
| | Advanced eDiscovery: admitir contenido vinculado de OneDrive y SharePoint Online (datos adjuntos modernos) | Disponible |
| | Advanced eDiscovery: Etiquetado | Disponible |
| | Advanced eDiscovery: compatibilidad Teams de reacciones | Disponible |
| | Advanced eDiscovery: informes de inquilinos | Disponible |
| | Advanced eDiscovery: Temas | Disponible |
| | Advanced eDiscovery: Visores | Disponible |
| | Advanced eDiscovery: Yammer Advanced eDiscovery en el Centro de cumplimiento de Microsoft | Disponible |
| | Advanced eDiscovery: optimizaciones de retención | En desarrollo |
| | Advanced eDiscovery: Microsoft Compliance Center expandió la compatibilidad para buscar y exportar elementos en SharePoint, OneDrive para la Empresa, Papelera de reciclaje en Core y Advanced eDiscovery | En desarrollo |
| | Advanced eDiscovery: retención legal de mensajes Teams canales privados | En desarrollo |
| | Advanced eDiscovery: Nuevo módulo de codificación predictiva | En desarrollo |
| | Advanced eDiscovery: ingesta sin Office 365 no | En el trabajo pendiente de ingeniería |
| | Advanced eDiscovery: informes de inquilinos | En desarrollo |
| | Auditoría básica | Disponible |
| | Auditoría avanzada: acceso a eventos cruciales (por ejemplo, mailitemsaccessed) | Disponible |
| | Auditoría avanzada: mayor ancho de banda para la API de actividad de administración | Disponible |
| | Auditoría avanzada: retención de registros (1 año) | Disponible |
| | Auditoría avanzada: eventos de reenvío de correo y envío de correo | Disponible |
| | Auditoría avanzada: disponibilidad del Centro de seguridad y cumplimiento | Disponible |
| | Auditoría avanzada: retención a largo plazo en registros de auditoría (10 años) | En desarrollo |
| | Auditoría avanzada: eventos de término de búsqueda en Exchange Online y SharePoint Online | En el trabajo pendiente de ingeniería |
| **Administración de cumplimiento** | Microsoft 365 Centro de seguridad y cumplimiento | Disponible |
| | Microsoft Cloud App Security | En desarrollo |
| | Administrador de cumplimiento | Disponible |
| | Compatibilidad con caracteres de doble byte | Disponible |
| **Ecosistema** | Conectores de datos de origen: HR | Disponible |
| | Conectores de datos de origen: Instant Bloomberg, Bloomberg Mail, linkedin business pages, ICE Chat | En el trabajo pendiente de ingeniería |
| | Conectores de datos de terceros | En el trabajo pendiente de ingeniería |
| | Graph API para Advanced eDiscovery | En desarrollo |
| | Graph API para Teams exportar datos | En el trabajo pendiente de ingeniería |

<sup>1</sup> El estado identificado está sujeto a cambios a medida que se reevaluan los planes y las prioridades del proyecto.<br/>

**Punto de decisión:** *decida si las características de cumplimiento satisfacen* las necesidades de su organización.
