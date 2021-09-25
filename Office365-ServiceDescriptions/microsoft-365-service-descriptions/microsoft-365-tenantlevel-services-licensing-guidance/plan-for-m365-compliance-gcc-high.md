---
title: Plan para las implementaciones del Centro de cumplimiento de Microsoft 365 - GCC High
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: Esta guía está para profesionales de TI que impulsan implementaciones de Office 365 en entidades del Gobierno Federal de Estados Unidos u otras entidades que controlan datos que están sujetos a normativas y requisitos gubernamentales, donde el uso de Microsoft 365 Government – GCC High es adecuado para cumplir estos requisitos.
ms.openlocfilehash: 9237de0625a481ce8f82411ad3f8ac384a9acf63
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/24/2021
ms.locfileid: "59670389"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Plan for Microsoft 365 compliance – GCC High

Esta guía está para profesionales de TI que impulsan implementaciones de Office 365 en entidades del Gobierno Federal de Estados Unidos u otras entidades que controlan datos que están sujetos a normativas y requisitos gubernamentales, donde el uso de Microsoft 365 Government – GCC High es adecuado para cumplir estos requisitos.

> [!NOTE]
>Si su organización ya ha cumplido con los requisitos de elegibilidad de Microsoft 365 Government– GCC High eligibility requirements and applied for and been accepted into the program, puede omitir los pasos 1 y 2 e ir directamente al paso 3.
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>Paso 1. Determinar si su organización necesita Microsoft 365 administración: GCC alto y cumple los requisitos de elegibilidad

El Microsoft 365: el GCC high cumple con los requisitos del Gobierno de los Estados Unidos para los servicios en la nube. Además de disfrutar de las características y capacidades de Office 365, las organizaciones se benefician de las siguientes características que son exclusivas de Microsoft 365 Government – GCC High:

- El contenido de cliente de su organización se separa lógicamente del contenido del cliente en los servicios Office 365 comerciales de Microsoft.
- El contenido del cliente de la organización se almacena dentro de los Estados Unidos.
- El acceso al contenido del cliente de la organización está restringido a personal específico de Microsoft.
- Microsoft 365 Gobierno: GCC High cumple con las certificaciones y acreditaciones necesarias para los clientes del sector público de Estados Unidos.

Encontrará más información sobre la oferta Microsoft 365 Government – GCC High para los clientes del gobierno de estados unidos en [Office 365 Administración Pública](https://products.office.com/government/compare-office-365-government-plans)planes, incluidos los requisitos de elegibilidad.

La [Office 365 de servicio del](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) Gobierno de ESTADOS UNIDOS describe las ventajas de la plataforma, que se centra en cumplir los requisitos de cumplimiento dentro de los Estados Unidos.

> [!TIP]
> Es posible que desee transferir las tablas de información de la descripción del servicio a un libro de Excel y agregar dos columnas: Relevante para mi organización **Y/N** y Cumple las necesidades de mi organización **Y/N**. A continuación, puede revisar esta lista con sus compañeros para confirmar que este servicio satisface las necesidades de su organización.

**Puntos de decisión**:<br/>

- *Decida si Microsoft 365 Gobierno: GCC-High es adecuado para su organización.*
- *Confirme que su organización cumple los requisitos de elegibilidad.*

> [!NOTE]
> Microsoft 365 Gobierno: GCC High solo está disponible en Los Estados Unidos. Los clientes que no son del Gobierno de Estados Unidos pueden elegir entre una serie [de Office 365 Administración Pública planes](https://products.office.com/government/compare-office-365-government-plans).

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>Paso 2. Aplicar para Microsoft 365 Government – GCC-High

Después de haber decidido que este servicio es adecuado para su organización, inicie el proceso de [solicitud de este servicio](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>Paso 3. Comprender Microsoft 365 administración pública: GCC-High configuración de seguridad predeterminada

Se recomienda que se tome tiempo para revisar detenidamente la configuración de seguridad y administración antes de modificarlas y tener en cuenta el impacto en el cumplimiento antes de realizar cualquier cambio en la configuración de seguridad predeterminada.

**Punto de** decisión: decida si modificará alguna de las opciones predeterminadas de *Microsoft 365 Government:* GCC-High configuración de seguridad, resolviendo primero para comprender el impacto de los cambios que pueda realizar.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>Paso 4. Comprender qué funcionalidades actualmente no están disponibles o deshabilitadas de forma predeterminada en Microsoft 365 Government – GCC-High<sup>1</sup>

Para satisfacer los requisitos de nuestros clientes en la nube gubernamentales, existen algunas diferencias entre Microsoft 365 Government– GCC-High y planes empresariales. Consulte la tabla siguiente para ver qué características están disponibles. Vea [aquí](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) las últimas actualizaciones de productos de cumplimiento publicadas en la guía básica Microsoft 365 cumplimiento.<br><br>

| Área | Característica | GCC Estado alto |
|------|---------|-----------------|
| **Protección de la información** |  |  |
| Tipos de información confidencial | Coincidencia exacta de datos | Disponible |
| Etiquetado de confidencialidad | Cliente y escáner de etiquetado unificados  | Disponible |
|  | Clasificación y etiquetado automáticos para Exchange Online, SharePoint Online y OneDrive | Disponible |
|  | Clasificación y etiquetado automáticos para Office aplicaciones (Word, Excel, PowerPoint, Outlook) en la web, Windows y Mac | Disponible |
|  | Clasificación y etiquetado automáticos para Office clientes (móvil) | En el trabajo pendiente de ingeniería |
|  | Clasificación y etiquetado automáticos para Teams, Microsoft 365 grupos y SharePoint sitios | Disponible |
| Análisis | Análisis de clasificación de datos: Información general y Explorador de contenido | Disponible |
|  | Auditoría y análisis en Office aplicaciones | Disponible |
|  | Análisis: clasificadores de aprendizaje automático con etiquetado automático en Office aplicaciones/cliente | En desarrollo |
| Cifrado | Base Cifrado de mensajes de Office 365 (E3) | Disponible |
|  | Advanced Cifrado de mensajes de Office 365 (E5) | Disponible |
|  | Clave del cliente de Office 365 | Disponible |
|  | Clave de cliente para Microsoft 365 cifrado de varias cargas de trabajo | En desarrollo |
|  | Clave de cliente para SharePoint Online y OneDrive para la Empresa | Disponible |
|  | Bring Your Own Key (BYOK) para el ciclo de vida de aprovisionamiento de claves administradas por el cliente | Disponible |
|  | Cifrado de claves doble | Disponible |
|  | Exchange Online cifrado de servicio con claves administradas de Microsoft | Disponible |
| Prevención de pérdida de datos | Prevención de pérdida de datos (DLP) para archivos y correo electrónico | Disponible |
|  | DLP para conversaciones Teams chat y canal | Disponible |
|  | Extremo DLP | Versión preliminar pública |
|  | Experiencia de alertas y panel de alertas dlp | Disponible |
|  | Página Información general de DLP | Implementando |
| **Gobierno de información** |  |  |
| Información de gobierno | Gobierno de la información: ámbitos adaptables para directivas de retención y etiquetado | En el trabajo pendiente de ingeniería |
| | Gobierno de la información: Archivado de correo electrónico | Disponible |
| | Gobierno de la información: etiquetas de retención predeterminadas para SharePoint/OneDrive para la Empresa bibliotecas, carpetas y conjuntos de documentos; Exchange bandejas de entrada; y Office 365 grupos | Disponible |
| | Gobierno de la información: Importar PST | Disponible |
| | Gobierno de la información: Etiquetas de retención manual sin registro | Disponible |
| | Gobierno de la información: bloqueo de conservación | Disponible |
| | Gobierno de la información: directivas de retención para toda la organización; ubicaciones o usuarios específicos; automáticamente en función de una condición específica (por ejemplo, palabras clave o información confidencial); y en función de un evento | Disponible |
| | Gobierno de la información: directivas de retención para Teams (chat) | Disponible |
| | Gobierno de la información: directivas de retención para Teams de reuniones | Disponible |
| | Gobierno de la información: directivas de retención Teams canales privados | Disponible |
| | Gobierno de la información: directivas de retención Teams canales compartidos | En el trabajo pendiente de ingeniería |
| | Gobierno de la información: directivas de retención para Yammer | En el trabajo pendiente de ingeniería |
| Administración de registros | Administración de registros: capacidad para eliminar una etiqueta de registro | Disponible |
| | Administración de registros: aplicar una etiqueta de registro manualmente | Disponible |
| | Administración de registros: aplicar etiquetas de registro predeterminadas para SharePoint, OneDrive para la Empresa bibliotecas, carpetas y conjuntos de documentos; y Office 365 grupos | Disponible |
| | Administración de registros: aplicar directivas de registro automáticamente en función de condiciones específicas (por ejemplo, palabras clave o información confidencial); y en función de un evento | Disponible |
| | Administración de registros: revisión de disposición | Disponible |
| | Administración de registros: Administrador de planes de archivos | Disponible |
| | Administración de registros: revisión de disposición de varias fases | En desarrollo |
| | Administración de registros: conservación y etiquetado automático de datos adjuntos en la nube | En desarrollo |
| | Administración de registros: prueba de eliminación | Disponible |
| | Administración de registros: conservación y etiquetado automático de datos adjuntos en la nube | En el trabajo pendiente de ingeniería |
| | Administración de registros: control de versiones de registros | Disponible |
| | Administración de registros: registros reglamentarios | Disponible |
| **Administración de riesgos** |  |  |
| Caja de seguridad del cliente | Caja de seguridad del cliente | Disponible |
| Cumplimiento de la comunicación | Cumplimiento de la comunicación: capacidad para establecer un período de retención para una directiva de cumplimiento de comunicaciones | En desarrollo |
| | Cumplimiento de la comunicación: obtener acceso a alertas; plantillas de aviso; panel de directivas de comunicación | Disponible |
| | Cumplimiento de la comunicación: analizar Teams de chat de usuarios con buzón local | Disponible |
| | Cumplimiento de la comunicación: plantilla conflicto de intereses | Disponible |
| | Cumplimiento de la comunicación: crear directivas de cliente, 3 preconfiguradas | Disponible |
| | Cumplimiento de la comunicación: detectar contenido para adultos | En el trabajo pendiente de ingeniería |
| | Cumplimiento de la comunicación: detecta una infracción de código de conducta repetida con el tiempo | Disponible |
| | Cumplimiento de la comunicación: escala para la investigación de Advanced eDiscovery | Disponible |
| | Cumplimiento de la comunicación: aprovechar el reconocimiento óptico de caracteres para extraer y evaluar mensajes | Disponible |
| | Cumplimiento de la comunicación: comprobación del estado de la directiva y capacidad para pausar la directiva | En desarrollo |
| | Cumplimiento de la comunicación: Power Automate integración | En desarrollo |
| | Cumplimiento de la comunicación: quitar Teams mensaje | Disponible |
| | Cumplimiento de la comunicación: tipos de información confidencial por informe de ubicación  | En desarrollo |
| | Cumplimiento de la comunicación: admite siete idiomas para la amenaza, el hostigamiento dirigido y los clasificadores profanos | Disponible |
| | Cumplimiento de la comunicación: compatibilidad con permisos más granulares | Disponible |
| | Cumplimiento de la comunicación: compatibilidad con Teams, Exchange y capacidad para quitar Teams mensaje | Disponible |
| | Cumplimiento de la comunicación: Teams contexto de conversación | En el trabajo pendiente de ingeniería |
| | Cumplimiento de la comunicación: traducir contenido durante la investigación | En el trabajo pendiente de ingeniería |
| Barreras de información | Barreras de información | Implementando |
| Administración de riesgos de Insider | Insider Risk Management: Registro de auditoría | Versión preliminar pública |
| | Insider Risk Management: Panel de casos | Disponible |
| | Administración de riesgos de Insider: mejoras del Explorador de contenido y del Explorador de contenido | Disponible |
| | Administración de riesgos de Insider: datos que se han presentado en el Explorador de actividades | Disponible |
| | Administración de riesgos de Insider: robo de datos por parte de los usuarios que salen | Disponible |
| | Administración de riesgos de Insider: Indicadores de dispositivos para la actividad en Windows 10 de conexión | Versión preliminar pública |
| | Administración de riesgos de Insider: escala para la investigación de Advanced eDiscovery | Disponible |
| | Administración de riesgos de Insider: Exportar alertas | Versión preliminar pública |
| | Administración de riesgos de Insider: pérdidas de datos generales | Disponible |
| | Administración de riesgos de Insider: indicadores de infracción de la directiva de seguridad | En desarrollo |
| | Administración de riesgos de Insider: indicadores de Microsoft Defender para alertas de extremo | En el trabajo pendiente de ingeniería |
| | Administración de riesgos de Insider: indicadores para la Windows 10 de puntos de conexión | Versión preliminar pública  |
| | Administración de riesgos de Insider: compatibilidad inteligente con la configuración de dominio en Insider Risk Management | Versión preliminar pública |
| | Insider Risk Management: Investigar alertas de administración de riesgos de insider | Disponible |
| | Administración de riesgos de Insider: Microsoft Teams Power Automate integración | En desarrollo |
| | Administración de riesgos de Insider: desencadenadores nativos admiten la eliminación Azure Active Directory cuenta | Versión preliminar pública |
| | Administración de riesgos de Insider: plantillas de aviso | Disponible |
| | Administración de riesgos de Insider: Office indicadores de Teams, SharePoint web, mensajería de correo electrónico | Disponible |
| | Administración de riesgos de Insider: plantillas de directiva para pérdidas de datos por parte de usuarios prioritarios | Versión preliminar pública |
| | Administración de riesgos de Insider: plantillas de directiva para infracciones de directivas de seguridad general | En el trabajo pendiente de ingeniería |
| | Administración de riesgos de Insider: plantillas de directiva para infracciones de directivas de seguridad por parte de usuarios prioritarios y usuarios que salen | Versión preliminar pública |
| | Administración de riesgos de Insider: plantillas de directiva para infracciones de directivas de seguridad por parte de usuarios inconformes | En el trabajo pendiente de ingeniería |
| | Administración de riesgos de Insider: Personalización de directivas, comprobación de estado de directivas y asistente para la creación de directivas mejoradas | Versión preliminar pública |
| | Administración de riesgos de Insider: grupos de usuarios prioritarios | En el trabajo pendiente de ingeniería |
| | Administración de riesgos de Insider: seguimiento de auditoría "Ver a los vigilantes" | Disponible |
| **Detectar &amp; respuesta** |  |  |
| eDiscovery | EDiscovery principal: Auditoría | Disponible |
| | EDiscovery principal: administración de casos | Disponible |
| | EDiscovery principal: límites de cumplimiento en OneDrive para la Empresa | Disponible |
| | EDiscovery principal: Exportar | Disponible |
| | Exhibición de documentos electrónicos principal: conservación local | Disponible |
| | EDiscovery principal: exportación nativa | Disponible |
| | EDiscovery principal: descifrado de RMS | Disponible |
| | EDiscovery principal: Búsqueda | Disponible |
| | Advanced eDiscovery: procesamiento avanzado | Disponible |
| | Advanced eDiscovery: asignación de custodia a carga de trabajo | Disponible |
| | Advanced eDiscovery: comunicaciones de custodia | Disponible |
| | Advanced eDiscovery: Panel | Disponible |
| | Advanced eDiscovery: capacidades de purga de datos para Microsoft Teams  | En el trabajo pendiente de ingeniería |
| | Advanced eDiscovery: rastreo profundo/indización | Disponible |
| | Advanced eDiscovery: compatibilidad de doble byte para chino, japonés y coreano | Disponible |
| | Advanced eDiscovery: Subprocesos de correo electrónico | Disponible |
| | Advanced eDiscovery: Exportar (descargar, exportar, agregar a otro conjunto de opiniones) | Disponible |
| | Advanced eDiscovery: Filtrado | Disponible |
| | Advanced eDiscovery: optimizaciones de retención | En desarrollo |
| | Advanced eDiscovery: retención legal de mensajes Teams canales privados | En desarrollo |
| | Advanced eDiscovery: Microsoft Compliance Center expandió la compatibilidad para buscar y exportar elementos en SharePoint y OneDrive para la Empresa papelera de reciclaje | En desarrollo |
| | Advanced eDiscovery: Identificación casi duplicada | Disponible |
| | Advanced eDiscovery: Nueva experiencia de exportación para Core y Advanced eDiscovery  | En desarrollo |
| | Advanced eDiscovery: Nuevo módulo de codificación predictiva | En el trabajo pendiente de ingeniería |
| | Advanced eDiscovery: orígenes de datos no custodiados | Disponible |
| | Advanced eDiscovery: ingesta sin Office 365 no | Disponible |
| | Advanced eDiscovery: codificación predictiva | Disponible |
| | Advanced eDiscovery: Exportación procesada con archivo de carga | Disponible |
| | Advanced eDiscovery: Redacciones | Disponible |
| | Advanced eDiscovery: conjuntos de revisión | Disponible |
| | Advanced eDiscovery: Revisar datos (datos de consulta, etiquetas inteligentes, panel) y anotación (redact) | Disponible |
| | Advanced eDiscovery: Informe de términos de búsqueda | Disponible |
| | Advanced eDiscovery: corrección de errores de elemento único | Disponible |
| | Advanced eDiscovery: Compatibilidad con la exportación de PST | Disponible |
| | Advanced eDiscovery: admitir contenido vinculado de OneDrive y SharePoint Online (datos adjuntos modernos) | Disponible |
| | Advanced eDiscovery: admitir Teams respuestas | En el trabajo pendiente de ingeniería |
| | Advanced eDiscovery: Etiquetado | Disponible |
| | Advanced eDiscovery: informes de inquilinos | Disponible |
| | Advanced eDiscovery: Temas | Disponible |
| | Advanced eDiscovery: Visores | Disponible |
| | Advanced eDiscovery: Yammer Advanced eDiscovery en el Centro de cumplimiento de Microsoft | Disponible |
| Auditoría | Auditoría básica | Disponible |
| | Auditoría avanzada: acceso a eventos cruciales (por ejemplo, *MailItemsAccessed*) | Disponible |
| | Auditoría avanzada: mayor ancho de banda para la API de actividad de administración | Disponible |
| | Auditoría avanzada: retención legal para Teams mensajes de canales privados | Disponible |
| | Auditoría avanzada: retención de registros (1 año) | Disponible |
| | Auditoría avanzada: retención a largo plazo en registros de auditoría (10 años) | Implementando |
| | Auditoría avanzada: eventos de reenvío de correo y envío de correo | Disponible |
| | Auditoría avanzada: Microsoft 365 disponibilidad del Centro de seguridad y cumplimiento | Disponible |
| | Auditoría avanzada: eventos de término de búsqueda en Exchange Online y SharePoint Online | En desarrollo |
| | Auditoría avanzada: Teams de mensajes | En el trabajo pendiente de ingeniería |
| **Administración de cumplimiento** |  |  |
| Administración de cumplimiento | Centro de cumplimiento de Microsoft 365 | Disponible |
| | Administrador de cumplimiento | Disponible |
| | Compatibilidad con caracteres de doble byte | Disponible |
| | Microsoft Cloud App Security | Disponible |
| **Ecosistema** |  |  |
| Ecosistema | Conectores de datos de origen: HR  | En desarrollo |
| | Conectores de datos de primer nivel: error físico | En desarrollo |
| | Graph API para Advanced eDiscovery  | En desarrollo |

<sup>1</sup> El estado identificado está sujeto a cambios a medida que se reevaluan los planes y las prioridades del proyecto.<br/>

**Punto de decisión:** *decida si las características de cumplimiento satisfacen* las necesidades de su organización.
