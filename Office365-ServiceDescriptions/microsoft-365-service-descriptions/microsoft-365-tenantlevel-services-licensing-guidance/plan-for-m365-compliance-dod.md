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
ms.openlocfilehash: 4d8e4b7600abe8b41baa94462f4e8dfbebf8b277
ms.sourcegitcommit: e3b492f18443921ed33776b2db51b888bd3bc230
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/30/2021
ms.locfileid: "58702292"
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

| Área  | Característica  | Estado de doD  |
|-------|----------|-------------|
| **Protección de la información**  | | |
| Tipos de información confidencial  | Coincidencia exacta de datos  | Disponible  |
| Etiquetado de confidencialidad  | Clasificación y etiquetado automáticos para Exchange Online, SharePoint Online y OneDrive para la Empresa  | Disponible |
| | Clasificación y etiquetado automáticos para Office aplicaciones (Word, Excel, PowerPoint, Outlook) en plataformas (Web, Windows y Mac)  | Disponible  |
| | Clasificación y etiquetado automáticos para clientes Office móvil  | En el trabajo pendiente de ingeniería  |
| | Clasificación y etiquetado automáticos para Teams, Microsoft 365 grupos y SharePoint sitios  | Disponible  |
| | Etiquetado obligatorio  | Disponible  |
| | Etiquetado de confidencialidad manual en Office aplicaciones (iOS, Android, Windows)  | Disponible  |
| | Configuración de etiquetas de confidencialidad para la protección de solo cifrado en Outlook mensajes  | Disponible  |
| | Cliente y escáner de etiquetado unificados  | Disponible  |
| Análisis  | Clasificación de datos: Introducción y Explorador de contenido  | Implementando  |
| | Análisis: clasificadores de aprendizaje automático con etiquetado automático en el lado del servicio  | En desarrollo  |
| | Análisis: clasificadores de aprendizaje automático con etiquetado automático en Office aplicaciones/cliente  | En desarrollo |
| Cifrado  | Base Cifrado de mensajes de Office 365 (E3)  | Disponible  |
| | Advanced Cifrado de mensajes de Office 365 (E5)  | Disponible  |
| | Bring Your Own Key (BYOK) para el ciclo de vida de aprovisionamiento de claves administradas por el cliente  | Disponible  |
| | Clave del cliente de Office 365  | Disponible  |
| | Clave de cliente para Microsoft 365 cifrado de varias cargas de trabajo | En desarrollo  |
| | Clave de cliente para SharePoint Online y OneDrive para la Empresa | Disponible |
| | Cifrado de claves doble  | Disponible  |
| Prevención de pérdida de datos  | Prevención de pérdida de datos (DLP) para archivos y correo electrónico  | Disponible  |
| | DLP: panel de alertas y experiencia de alertas  | Disponible  |
| | DLP para conversaciones Teams chat y canal  | Disponible  |
| | Extremo DLP (versión preliminar pública)  | Versión preliminar pública |
| | Página Información general de DLP  | Implementando  |
| **Gobierno de información**  | | |
| Información de gobierno  | Gobierno de la información: ámbitos adaptables para directivas de retención y etiquetado | En el trabajo pendiente de ingeniería  |
| | Gobierno de la información: aplicar una etiqueta predeterminada para Exchange bandejas de entrada  | Disponible  |
| | Gobierno de la información: archivado de correo electrónico  | Disponible  |
| | Gobierno de la información: Importar PST  | Disponible  |
| | Gobierno de la información: bloqueo de conservación  | Disponible  |
| | Gobierno de la información: directivas de retención con clasificadores capacitados  | En desarrollo  |
| | Gobierno de la información: directivas de retención para Teams chat  | Disponible  |
| | Gobierno de la información: directivas de retención para Teams de reuniones  | Disponible  |
| | Gobierno de la información: directivas de retención Teams mensajes de canal privado  | En desarrollo  |
| | Gobierno de la información: ámbitos adaptables de directivas de retención y etiquetado  | En desarrollo  |
| Records Management  | Administración de registros: aplicar la etiqueta de registro manualmente  | Disponible  |
| | Administración de registros: aplique una etiqueta de registro predeterminada para SharePoint, OneDrive para la Empresa bibliotecas, carpetas y conjuntos de documentos; y Office 365 grupos  | Disponible  |
| | Administración de registros: directivas de registro automáticas basadas en condiciones específicas (por ejemplo, palabras clave o información confidencial); y en función de un evento  | Disponible  |
| | Administración de registros: revisión de disposición  | Disponible  |
| | Administración de registros: Administrador de planes de archivos  | Disponible  |
| | Administración de registros: revisión de disposición de varias fases  | En desarrollo  |
| | Administración de registros: conservación y etiquetado automático de datos adjuntos en la nube  | En desarrollo  |
| | Administración de registros: prueba de eliminación  | Disponible  |
| | Administración de registros: control de versiones de registros  | Disponible  |
| | Administración de registros: registros reglamentarios  | Disponible  |
| | Administración de registros: usar la SharePoint Syntex de registros para aplicar etiquetas de registro  | En el trabajo pendiente de ingeniería  |
| **Administración de riesgos**  | | |
| Administración de riesgos  | Caja de seguridad del cliente  | Disponible  |
| Cumplimiento de la comunicación  | Cumplimiento de la comunicación: capacidad para establecer un período de retención para una directiva de cumplimiento de comunicaciones (versión preliminar pública)  | En el trabajo pendiente de ingeniería  |
| | Cumplimiento de la comunicación: obtener acceso a alertas; plantillas de aviso; panel de directivas de comunicación  | Disponible  |
| | Cumplimiento de la comunicación: analizar Teams de chat de usuarios con buzón local  | Disponible  |
| | Cumplimiento de la comunicación: plantilla conflicto de intereses  | Disponible  |
| | Cumplimiento de la comunicación: crear directivas de cliente, 3 preconfiguradas  | Disponible  |
| | Cumplimiento de la comunicación: detectar contenido para adultos  | En el trabajo pendiente de ingeniería  |
| | Cumplimiento de la comunicación: detecta una infracción de código de conducta repetida con el tiempo  | Disponible  |
| | Cumplimiento de la comunicación: escala para la investigación de Advanced eDiscovery  | Disponible  |
| | Cumplimiento de la comunicación: aprovechar el reconocimiento óptico de caracteres (OCR) para extraer y evaluar mensajes  | Disponible  |
| | Cumplimiento de la comunicación: Microsoft Teams integración  | En desarrollo  |
| | Cumplimiento de la comunicación: comprobación del estado de la directiva y capacidad para pausar la directiva  | En desarrollo  |
| | Cumplimiento de la comunicación: Power Automate integración  | En el trabajo pendiente de ingeniería  |
| | Cumplimiento de la comunicación: tipos de información confidencial por informe de ubicación  | En desarrollo  |
| | Cumplimiento de la comunicación: compatibilidad con Teams, Exchange y quitar Teams mensaje  | Disponible  |
| | Cumplimiento de la comunicación: compatibilidad con permisos más granulares  | Disponible  |
| | Cumplimiento de la comunicación: admite 7 idiomas para amenazas, hostigamiento dirigido y clasificadores de profanidades  | Disponible  |
| | Cumplimiento de la comunicación: traducir contenido de estado durante la investigación  | En desarrollo  |
| Barreras de información  | Barreras de información  | Implementando  |
| Administración de riesgos de Insider  | Insider Risk Management: Registro de auditoría  | Versión preliminar pública  |
| | Administración de riesgos de Insider: Panel de casos  | Disponible  |
| | Administración de riesgos de Insider: datos que se han presentado en el Explorador de actividades  | Versión preliminar pública  |
| | Administración de riesgos de Insider: datos que se han presentado en el Explorador de contenido  | En desarrollo  |
| | Administración de riesgos de Insider: robo de datos por parte de los usuarios que salen  | Disponible  |
| | Administración de riesgos de Insider: Indicadores de dispositivos para la actividad en Windows 10 de conexión  | En desarrollo  |
| | Insider Risk Management: Escalar para Advanced eDiscovery  | Disponible  |
| | Administración de riesgos de Insider: Exportar alertas  | Versión preliminar pública  |
| | Administración de riesgos de Insider: pérdidas de datos generales  | Disponible  |
| | Administración de riesgos de Insider: compatibilidad inteligente con la configuración de dominio en Insider Risk Management  | Versión preliminar pública  |
| | Administración de riesgos de Insider: indicadores de Microsoft Defender para alertas de extremo  | En el trabajo pendiente de ingeniería  |
| | Administración de riesgos de Insider: indicadores de infracción de la directiva de seguridad  | En desarrollo  |
| | Administración de riesgos de Insider: indicadores para la Windows 10 de puntos de conexión | Versión preliminar pública  |
| | Insider Risk Management: Investigar alertas de administración de riesgos de insider  | Disponible  |
| | Administración de riesgos de Insider: Microsoft Teams y Power Automate integración  | En desarrollo  |
| | Administración de riesgos de Insider: desencadenadores nativos admiten la eliminación Azure Active Directory cuenta | Versión preliminar pública  |
| | Administración de riesgos de Insider: plantillas de aviso  | Disponible  |
| | Administración de riesgos de Insider: Office indicadores de Teams, SharePoint web, mensajería de correo electrónico  | Disponible  |
| | Administración de riesgos de Insider: plantillas de directiva para pérdidas de datos por parte de usuarios inconformes  | En el trabajo pendiente de ingeniería  |
| | Administración de riesgos de Insider: plantillas de directiva para pérdidas de datos por parte de usuarios prioritarios  | Versión preliminar pública  |
| | Administración de riesgos de Insider: plantillas de directiva para infracciones de directivas de seguridad general  | En el trabajo pendiente de ingeniería  |
| | Administración de riesgos de Insider: plantillas de directiva para infracciones de directivas de seguridad por parte de usuarios prioritarios, usuarios que salen, usuarios descontentos (versión preliminar)  | En el trabajo pendiente de ingeniería  |
| | Administración de riesgos de Insider: Personalización de directivas, comprobación de estado de directivas y asistente para la creación de directivas mejoradas  | Versión preliminar pública  |
| | Administración de riesgos de Insider: grupos de usuarios prioritarios  | Versión preliminar pública  |
| | Administración de riesgos de Insider: admite desencadenadores nativos para la eliminación Azure Active Directory cuenta | Versión preliminar pública  |
| | Insider Risk Management: "Watch the watcher" audit trail | Versión preliminar pública  |
| **Detectar & responder**  | | |
| eDiscovery | EDiscovery principal: Auditoría  | Disponible  |
| | EDiscovery principal: administración de casos  | Disponible  |
| | EDiscovery principal: límites de cumplimiento en OneDrive para la Empresa  | Disponible  |
| | EDiscovery principal: Exportar  | Disponible  |
| | Exhibición de documentos electrónicos principal: conservación local  | Disponible  |
| | EDiscovery principal: exportación nativa  | Disponible  |
| | EDiscovery principal: descifrado de RMS  | Disponible  |
| | EDiscovery principal: Búsqueda  | Disponible  |
| | Advanced eDiscovery: procesamiento avanzado  | Disponible  |
| | Advanced eDiscovery: asignación de custodia a carga de trabajo  | Disponible  |
| | Advanced eDiscovery: comunicaciones de custodia  | Disponible  |
| | Advanced eDiscovery: Panel  | Disponible  |
| | Advanced eDiscovery: capacidades de purga de datos para Microsoft Teams  | En el trabajo pendiente de ingeniería  |
| | Advanced eDiscovery: rastreo profundo/indización  | Disponible  |
| | Advanced eDiscovery: compatibilidad de doble byte para chino, japonés y coreano  | Disponible  |
| | Advanced eDiscovery: Subprocesos de correo electrónico  | Disponible  |
| | Advanced eDiscovery: Exportar (descargar, exportar, agregar a otro conjunto de opiniones)  | Disponible  |
| | Advanced eDiscovery: Filtrado  | Disponible  |
| | Advanced eDiscovery: optimizaciones de retención  | En desarrollo  |
| | Advanced eDiscovery: retención legal de mensajes Teams canales privados  | En desarrollo  |
| | Advanced eDiscovery: Microsoft Compliance Center expandió la compatibilidad para buscar y exportar elementos en SharePoint, OneDrive para la Empresa, Papelera de reciclaje en Core y Advanced eDiscovery  | En desarrollo  |
| | Advanced eDiscovery: Identificación casi duplicada  | Disponible  |
| | Advanced eDiscovery: Nuevo módulo de codificación predictiva  | En desarrollo  |
| | Advanced eDiscovery: orígenes de datos no custodiados  | Disponible  |
| | Advanced eDiscovery: ingesta sin Office 365 no  | En el trabajo pendiente de ingeniería  |
| | Advanced eDiscovery: codificación predictiva  | Disponible  |
| | Advanced eDiscovery: Exportación procesada con archivo de carga  | Disponible  |
| | Advanced eDiscovery: Redacciones  | Disponible  |
| | Advanced eDiscovery: conjuntos de revisión  | Disponible  |
| | Advanced eDiscovery: Revisar datos (datos de consulta, etiquetas inteligentes, panel) y anotación (redact)  | Disponible  |
| | Advanced eDiscovery: Informe de términos de búsqueda  | Disponible  |
| | Advanced eDiscovery: admitir contenido vinculado de OneDrive y SharePoint Online (datos adjuntos modernos)  | Disponible  |
| | Advanced eDiscovery: admitir Teams respuestas  | En el trabajo pendiente de ingeniería  |
| | Advanced eDiscovery: Etiquetado  | Disponible  |
| | Advanced eDiscovery: informes de inquilinos  | Disponible  |
| | Advanced eDiscovery: Temas  | Disponible  |
| | Advanced eDiscovery: Visores  | Disponible  |
| | Advanced eDiscovery: Yammer Advanced eDiscovery en el Centro de cumplimiento de Microsoft  | Disponible  |
| Auditoría  | Auditoría básica  | Disponible  |
| | Auditoría avanzada: acceso a eventos cruciales (por ejemplo, mailitemsaccessed)  | Disponible  |
| | Auditoría avanzada: mayor ancho de banda para la API de actividad de administración  | Disponible  |
| | Auditoría avanzada: retención de registros (1 año)  | Disponible  |
| | Auditoría avanzada: retención a largo plazo en registros de auditoría (10 años)  | Implementando  |
| | Auditoría avanzada: eventos de reenvío de correo y envío de correo  | Disponible  |
| | Auditoría avanzada: disponibilidad del Centro de seguridad y cumplimiento  | Disponible  |
| | Auditoría avanzada: eventos de término de búsqueda en Exchange Online y SharePoint Online  | Implementando  |
| | Auditoría avanzada: Teams de mensajes  | En el trabajo pendiente de ingeniería  |
| **Administración de cumplimiento** | | |
| Administración de cumplimiento  | Centro de cumplimiento de Microsoft 365  | Disponible  |
| | Microsoft Cloud App Security  | Disponible  |
| | Administrador de cumplimiento  | Disponible  |
| | Compatibilidad con caracteres de doble byte  | Disponible  |
| **Ecosistema** | | |
| Ecosistema  | Conectores de datos de origen: HR  | Disponible  |
| | Conectores de datos de origen: Instant Bloomberg, Bloomberg Mail, linkedin business pages, ICE Chat  | En desarrollo  |
| | Graph API para Advanced eDiscovery  | En el trabajo pendiente de ingeniería  |

<sup>1</sup> El estado identificado está sujeto a cambios a medida que se reevaluan los planes y las prioridades del proyecto.<br/>

**Punto de decisión:** *decida si las características de cumplimiento satisfacen* las necesidades de su organización.
