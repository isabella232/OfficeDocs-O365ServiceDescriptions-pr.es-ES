---
title: Plan para las implementaciones del Centro de cumplimiento de Microsoft 365 - GCC High
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Esta guía está para profesionales de TI que impulsan implementaciones de Office 365 en entidades del Gobierno Federal de Estados Unidos u otras entidades que controlan datos que están sujetos a normativas y requisitos gubernamentales, donde el uso de Microsoft 365 Government – GCC High es adecuado para cumplir estos requisitos.
ms.openlocfilehash: 14c92229fa5ec147ff995d0cebe991cfdce0de70
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173085"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Planear el cumplimiento de Microsoft 365: GCC High

Esta guía está para profesionales de TI que impulsan implementaciones de Office 365 en entidades del Gobierno Federal de Estados Unidos u otras entidades que controlan datos que están sujetos a normativas y requisitos gubernamentales, donde el uso de Microsoft 365 Government – GCC High es adecuado para cumplir estos requisitos.

> [!NOTE]
>Si su organización ya ha cumplido los requisitos de elegibilidad de Microsoft 365 Government – GCC High y solicitó y se aceptó en el programa, puede omitir los pasos 1 y 2 e ir directamente al paso 3.
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>Paso 1. Determinar si su organización necesita Microsoft 365 Government: GCC High y cumple los requisitos de elegibilidad

El entorno de Microsoft 365 Government - GCC High cumple con los requisitos del Gobierno de Estados Unidos para los servicios en la nube. Además de disfrutar de las características y capacidades de Office 365, las organizaciones se benefician de las siguientes características que son exclusivas de Microsoft 365 Government: GCC High:

- El contenido de cliente de su organización se separa lógicamente del contenido de los clientes en los servicios comerciales de Office 365 de Microsoft.
- El contenido del cliente de la organización se almacena dentro de los Estados Unidos.
- El acceso al contenido del cliente de la organización está restringido a personal específico de Microsoft.
- Microsoft 365 Government: GCC High cumple con las certificaciones y acreditaciones necesarias para los clientes del sector público estadounidense.

Puede encontrar más información sobre la oferta de Microsoft 365 Government – GCC High para clientes del gobierno de ESTADOS UNIDOS en los planes de [Office 365 Government,](https://products.office.com/government/compare-office-365-government-plans)incluidos los requisitos de elegibilidad.

La descripción del servicio de [Office 365 US Government](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) describe las ventajas de la plataforma, que se centra en cumplir los requisitos de cumplimiento dentro de los Estados Unidos.

> [!TIP]
> Es posible que desee transferir las tablas de información de la descripción del servicio a un libro de Excel y agregar dos columnas: Relevante para mi organización **Y/N** y Cumple las necesidades de mi organización **Y/N**. A continuación, puede revisar esta lista con sus compañeros para confirmar que este servicio satisface las necesidades de su organización.

**Puntos de decisión**:<br/>
- *Decida si Microsoft 365 Government: GCC-High es adecuado para su organización.*
- *Confirme que su organización cumple los requisitos de elegibilidad.*

> [!NOTE]
> Microsoft 365 Government: GCC High solo está disponible en Los Estados Unidos. Los clientes que no son de Estados Unidos pueden elegir entre varios planes [de Office 365 Government](https://products.office.com/government/compare-office-365-government-plans).

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>Paso 2. Solicitar Microsoft 365 Government : GCC-High

Después de haber decidido que este servicio es adecuado para su organización, inicie el proceso de [solicitud de este servicio](https://products.office.com/government/eligibility-validation).
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>Paso 3. Comprender Microsoft 365 Government: GCC-High configuración de seguridad predeterminada

Se recomienda que se tome tiempo para revisar detenidamente la configuración de seguridad y administración antes de modificarlas y tener en cuenta el impacto en el cumplimiento antes de realizar cualquier cambio en la configuración de seguridad predeterminada.

**Punto de** decisión: decida si modificará alguna de las opciones predeterminadas de *Microsoft 365 Government* GCC-High seguridad, resolviendo primero el impacto de los cambios que pueda realizar.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>Paso 4. Comprender qué funcionalidades no están disponibles o deshabilitadas de forma predeterminada en Microsoft 365 Government – GCC-High<sup>1</sup>

Para cumplir con los requisitos de nuestros clientes en la nube gubernamentales, existen algunas diferencias entre Microsoft 365 Government, GCC-High y los planes de empresa. Consulte la tabla siguiente para ver qué características están disponibles. Vea [aquí](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) las últimas actualizaciones de productos de cumplimiento publicadas en la guía básica de Microsoft 365.<br><br>

| Área                                    | Característica                                         | Estado de GCC             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Protección de la información**              | Cliente y escáner de etiquetado unificados         | Disponible              |
|                                         | Coincidencia exacta de datos          | Disponible              |
|                                         | Clasificación y etiquetado automáticos para Exchange Online, SharePoint Online y OneDrive                      | Implementando              |
|                                         | Clasificación y etiquetado automáticos para aplicaciones de Office (Word, Excel, PowerPoint, Outlook) en la web, Android, iOS, Windows y Mac            | En desarrollo |
|                                         | Clasificación y etiquetado automáticos para clientes de Office (Móvil)                                       | En el trabajo pendiente de ingeniería              |
|                                         | Clasificación y etiquetado automáticos para Teams                            | En el trabajo pendiente de ingeniería |
|                                         | Análisis de clasificación de datos: Información general y Explorador de contenido                            | En el trabajo pendiente de ingeniería |
|                                         | Análisis: clasificadores de aprendizaje automático con etiquetado automático en el lado del servicio                           | En el trabajo pendiente de ingeniería  |
|                                         | Análisis: clasificadores de aprendizaje automático con etiquetado automático en el lado cliente/aplicaciones de Office                           | En el trabajo pendiente de ingeniería  |
|                                         | Cifrado de mensajes básico de Office 365 (E3)                            | Disponible              |
|                                         | Cifrado de mensajes avanzado de Office 365 (E5)  | Disponible              |
|                                         | Clave del cliente de Office 365    | Disponible |
|                                         | Bring Your Own Key (BYOK) para el ciclo de vida de aprovisionamiento de claves administradas por el cliente                            | Disponible |
|                                         | Hold Your Own Key (HYOK) que abarca Azure Information Protection y Active Directory (AD) Rights Management para escenarios altamente regulados (versión preliminar)                         | Disponible |
|                                         | Cifrado de claves doble                           | Disponible |
|                                         | Cifrado: co-autoría en documentos cifrados con aplicaciones web WXP         | En el trabajo pendiente de ingeniería |
|                                         | Prevención de pérdida de datos (DLP) para archivos y correo electrónico         | Disponible |
|                                         | Conversaciones de chat y canales de DLP para Teams | En el trabajo pendiente de ingeniería |
|                                         | Extremo DLP | En el trabajo pendiente de ingeniería |
| **Gobierno de información** | Gobierno de la información: Archivado de correo electrónico                                       | Disponible              |
|                                         | Gobierno de la información: bloqueo de conservación          | Disponible              |
|                                         | Gobierno de la información: Importar PST                      | Disponible              |
|                                         | Gobierno de la información: Etiquetas de retención manual sin registro            | Disponible |
|                                         | Gobierno de la información: etiquetas de retención predeterminadas para bibliotecas, carpetas y conjuntos de documentos de SharePoint/OneDrive para la Empresa; Bandejas de entrada de Exchange; y grupos de Office 365 | Disponible              |
|                                         | Gobierno de la información: directivas de retención para toda la organización; ubicaciones o usuarios específicos; automáticamente en función de una condición específica (por ejemplo, palabras clave o información confidencial); y en función de un evento                                       | Disponible              |
|                                         | Gobierno de la información: directivas de retención para Teams                            | En el trabajo pendiente de ingeniería |
|                                         | Gobierno de la información: etiquetas de retención que usan la clasificación de Syntex de SharePoint                            | En el trabajo pendiente de ingeniería |
|                                         | Gobierno de la información: directivas de retención con clasificadores capacitados                            | En el trabajo pendiente de ingeniería |
|                                         | Gobierno de la información: directivas de retención para el registro de reuniones de Teams                            | En el trabajo pendiente de ingeniería |
|                                         | Gobierno de la información: directivas de retención para Yammer                            | En el trabajo pendiente de ingeniería |
|                                         | Administración de registros: clasificación manual para etiquetas de registros                           | Disponible              |
|                                         | Administración de registros: etiquetas de registro predeterminadas para SharePoint, bibliotecas, carpetas y conjuntos de documentos de OneDrive para la Empresa; y grupos de Office 365                              | Disponible              |
|                                         | Administración de registros: directivas de registro automáticas basadas en condiciones específicas (por ejemplo, palabras clave o información confidencial); y en función de un evento                            | Disponible              |
|                                         | Administración de registros: revisión de disposición  | Disponible              |
|                                         | Administración de registros: Administrador de planes de archivos    | Disponible |
|                                         | Administración de registros: prueba de eliminación                            | Disponible |
|                                         | Administración de registros: control de versiones de registros                         | Disponible |
|                                         | Administración de registros: registros reglamentarios                         | En el trabajo pendiente de ingeniería |
|                                         | Administración de registros: revisión de disposición de varias fases | En el trabajo pendiente de ingeniería |
|                                         | Administración de registros: usar la clasificación de Syntex de SharePoint para aplicar etiquetas de registro | En el trabajo pendiente de ingeniería |
| **Administración de riesgos internos**             | Caja de seguridad del cliente                                | Disponible            |
|                                         | Administración de riesgos de Insider: indicadores de Office para Teams, sitios de SharePoint, mensajería de correo electrónico                         | En desarrollo |
|                                         | Administración de riesgos de Insider: robo de datos por parte de los usuarios que salen                        | En desarrollo |
|                                         | Administración de riesgos de Insider: pérdidas de datos generales                                | En desarrollo              |
|                                         | Insider Risk Management: Investigar alertas de administración de riesgos de insider                                   | En desarrollo              |
|                                         | Administración de riesgos de Insider: panel de casos, explorador de contenido y plantillas de aviso | En desarrollo |
|                                         | Insider Risk Management: Escalar para la investigación de eDiscovery avanzada | En desarrollo|
|                                         | Administración de riesgos de Insider: Indicadores de dispositivos para la actividad en Windows 10 Build 1809 y versiones posteriores | En el trabajo pendiente de ingeniería|
|                                         | Administración de riesgos de Insider: indicadores de infracción de directiva de seguridad (versión preliminar) | En el trabajo pendiente de ingeniería|
|                                         | Administración de riesgos de Insider: indicadores de Microsoft Defender para alertas de extremo (versión preliminar) | En el trabajo pendiente de ingeniería|
|                                         | Administración de riesgos de Insider: plantillas de directiva para pérdidas de datos por usuarios prioritarios (versión preliminar) | En el trabajo pendiente de ingeniería |
|                                         | Administración de riesgos de Insider: plantillas de directiva para pérdidas de datos por parte de usuarios inconformes (versión preliminar) | En el trabajo pendiente de ingeniería |
|                                         | Administración de riesgos de Insider: plantillas de directiva para infracciones de directivas de seguridad general (versión preliminar) | En el trabajo pendiente de ingeniería |
|                                         | Administración de riesgos de Insider: plantillas de directiva para infracciones de directivas de seguridad por parte de usuarios prioritarios, usuarios que salen, usuarios descontentos (versión preliminar) | En el trabajo pendiente de ingeniería |
|                                         | Insider Risk Management: Personalización de directivas (versión preliminar) | En el trabajo pendiente de ingeniería |
|                                         | Administración de riesgos de Insider: Exportar alertas (versión preliminar) | En el trabajo pendiente de ingeniería |
|                                         | Administración de riesgos de Insider: grupos de usuarios prioritarios (versión preliminar) | En el trabajo pendiente de ingeniería |
|                                         | Cumplimiento de comunicaciones (incluidas las directivas de supervisión): crear directivas de cliente, 3 preconfiguradas  | En desarrollo |
|                                         | Cumplimiento de la comunicación (incluidas las directivas de supervisión): compatibilidad con Teams, Exchange y quitar el mensaje de Teams | En desarrollo |
|                                         | Cumplimiento de la comunicación (incluidas las directivas de supervisión): obtener acceso a alertas; plantillas de aviso; panel de directivas de comunicación | En desarrollo  |
|                                         | Cumplimiento de comunicaciones (incluidas las directivas de supervisión): escala para la investigación de eDiscovery avanzada | En desarrollo |
|                                         | Cumplimiento de la comunicación (incluidas las directivas de supervisión): detectar contenido para adultos | En desarrollo |
|                                         | Cumplimiento de comunicaciones (incluidas las directivas de supervisión): detecta una infracción de código de conducta repetida con el tiempo | Implementando |
|                                         | Cumplimiento de comunicaciones (incluidas las directivas de supervisión): compatibilidad con permisos más granulares | Implementando |
|                                         | Cumplimiento de comunicaciones (incluidas las directivas de supervisión): analizar datos de chat de Teams de usuarios con buzón local | Implementando |
|                                         | Cumplimiento de comunicaciones (incluidas las directivas de supervisión): Plantilla de conflicto de intereses | En el trabajo pendiente de ingeniería |
|                                         | Cumplimiento de la comunicación (incluidas las directivas de supervisión): capacidad para omitir la firma de correo electrónico o la declinación de responsabilidades | En el trabajo pendiente de ingeniería |
|                                         | Cumplimiento de comunicaciones (incluidas las directivas de supervisión): entrega de la administración de riesgos insider | En el trabajo pendiente de ingeniería |
|                                         | Cumplimiento de la comunicación (incluidas las directivas de supervisión): comprobación del estado de la directiva y capacidad de pausar la directiva | En el trabajo pendiente de ingeniería |
|                                         | Cumplimiento de la comunicación (incluidas las directivas de supervisión): traducir contenido de estado durante la investigación | En el trabajo pendiente de ingeniería |
|                                         | Cumplimiento de la comunicación (incluidas las directivas de supervisión): detección de ataques y detección de suicidios | En el trabajo pendiente de ingeniería |
|                                         | Barreras de información | En el trabajo pendiente de ingeniería |
|                                         | Administración del acceso con privilegios                    | En el trabajo pendiente de ingeniería |
| **Detectar & responder**                  | Exhibición de documentos electrónicos principal: conservación local                            | Disponible              |
|                                         | EDiscovery principal: administración de casos                                 | Disponible              |
|                                         | EDiscovery principal: Búsqueda                                          | Disponible              |
|                                         | EDiscovery principal: Exportar                                          | Disponible              |
|                                         | EDiscovery principal: descifrado de RMS                                  | Disponible              |
|                                         | EDiscovery principal: exportación nativa                                   | Disponible              |
|                                         | EDiscovery principal: Auditoría                                        | Disponible              |
|                                         | EDiscovery principal: Microsoft Compliance Center expandió la compatibilidad para buscar y exportar elementos en SharePoint y la Papelera de reciclaje de OneDrive para la Empresa                                        | En desarrollo              |
|                                         | Exhibición de documentos electrónicos avanzada: procesamiento avanzado                             | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: asignación de custodia a carga de trabajo                             | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: comunicaciones de custodia                             | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: Panel                             | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: subprocesos de correo electrónico                                 | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: Exportar (descargar, exportar, agregar a otro conjunto de opiniones)                   | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: filtrado                                          | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: retención legal de mensajes de canales privados de Teams                               | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: identificación casi duplicada                 | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: orígenes de datos no custodiados                                         | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: ingesta que no es de Office 365                                         | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: codificación predictiva                                      | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: exportación procesada con archivo de carga                                       | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: redacciones                   | Disponible |
|                                         | EDiscovery avanzado: conjuntos de revisión                        | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: revisar datos (datos de consulta, etiquetas inteligentes, panel) y anotación (redact)                                     | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: informe de términos de búsqueda                             | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: corrección de errores de elemento único                        | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: compatibilidad con la exportación de PST                              | Implementando |
|                                         | Exhibición de documentos electrónicos avanzada: compatibilidad con contenido vinculado de OneDrive y SharePoint Online (datos adjuntos modernos)                              | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: etiquetado                              | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: informes de inquilinos                              | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: temas                               | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: visores                              | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: Exhibición de documentos electrónicos avanzada de Yammer en el Centro de cumplimiento de Microsoft                              | Disponible |
|                                         | Exhibición de documentos electrónicos avanzada: compatibilidad con CJK/Double byte para eDiscovery avanzado                              | En desarrollo |
|                                         | Exhibición de documentos electrónicos avanzada: admitir las reacciones de Teams                             | En desarrollo |
|                                         | Exhibición de documentos electrónicos avanzada: Microsoft Compliance Center expandió la compatibilidad para buscar y exportar elementos en SharePoint y la Papelera de reciclaje de OneDrive para la Empresa                               | En el trabajo pendiente de ingeniería |
|                                         | Auditoría básica                              | Disponible |
|                                         | Auditoría avanzada: acceso a eventos cruciales (por ejemplo, mailitemsaccessed)                              | Disponible |
|                                         | Auditoría avanzada: mayor ancho de banda para la API de actividad de administración                              | Disponible |
|                                         | Auditoría avanzada: retención legal para mensajes de canales privados de Teams                              | Disponible |
|                                         | Auditoría avanzada: retención de registros (1 año)                              | Implementando |
|                                         | Auditoría avanzada: disponibilidad del Centro de seguridad y cumplimiento                              | Disponible |
|                                         | Auditoría avanzada: retención a largo plazo en registros de auditoría (10 años)                              | En el trabajo pendiente de ingeniería |
|                                         | Auditoría avanzada: eventos de reenvío de correo y envío de correo                              | En el trabajo pendiente de ingeniería |
|                                         | Auditoría avanzada: información de auditoría procesada                              | En el trabajo pendiente de ingeniería |
|                                         | Auditoría avanzada: eventos de términos de búsqueda en Exchange Online y SharePoint Online                              | En el trabajo pendiente de ingeniería |
|    **Administración de cumplimiento**            | Centro de seguridad y cumplimiento de Microsoft 365                              | Disponible |
|                                         | Administrador de cumplimiento                                 | Disponible              |
|                                         | Microsoft Cloud App Security                                 | Disponible              |
|                                         | Compatibilidad con caracteres de doble byte                                 | En el trabajo pendiente de ingeniería              |
|    **Ecosistema**            | API de Graph para eDiscovery avanzada                              | En desarrollo |
|                                         | Conectores de datos de origen                                 | En el trabajo pendiente de ingeniería              |
|                                         | Conectores de datos de terceros                                 | En el trabajo pendiente de ingeniería              |
|                                         | API de Graph para exportar datos de Teams                                 | En el trabajo pendiente de ingeniería              |

<sup>1</sup> El estado identificado está sujeto a cambios a medida que se reevaluan los planes y las prioridades del proyecto.<br/>

**Punto de decisión:** *decida si las características de cumplimiento satisfacen* las necesidades de su organización.