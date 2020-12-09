---
title: Plan para las implementaciones del Centro de cumplimiento de Microsoft 365 - DoD
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Esta guía está dirigida a los profesionales de ti que imponen las implementaciones de Office 365 en entidades de gobierno federal de Estados Unidos u otras entidades que administran datos que están sujetos a los requisitos y las regulaciones gubernamentales, donde el uso de Microsoft 365 Government – DoD es adecuado para cumplir con estos requisitos.
ms.openlocfilehash: a619943b5eed63007b78613ab9b6715a52ef467d
ms.sourcegitcommit: d0ca41de5b242d2d5688d92d55064d9eecbb89a9
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/08/2020
ms.locfileid: "49601725"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Plan para las implementaciones del Centro de cumplimiento de Microsoft 365 - DoD

Esta guía está dirigida a los profesionales de ti que imponen las implementaciones de Office 365 en entidades de gobierno federal de Estados Unidos u otras entidades que administran datos que están sujetos a los requisitos y las regulaciones gubernamentales, donde el uso de Microsoft 365 Government – DoD es adecuado para cumplir con estos requisitos.

> [!NOTE]
> Si su organización ya ha cumplido los requisitos de elegibilidad de Microsoft 365 Government – DoD y ha sido aceptado en el programa, puede omitir los pasos 1 y 2 y ir directamente al paso 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>Paso 1. Determinar si su organización necesita Microsoft 365 Government-DoD y cumple con los requisitos de elegibilidad

El entorno Microsoft 365 Government-DoD cumple con los requisitos del gobierno de Estados Unidos para los servicios en la nube.

Además de disfrutar de las características y capacidades de Office 365, las organizaciones se benefician de las siguientes características que son exclusivas de Microsoft 365 Government – DoD:

- El contenido del cliente de la organización se separa lógicamente del contenido del cliente en los servicios comerciales de Office 365 de Microsoft.
- El contenido del cliente de la organización se almacena dentro de los Estados Unidos.
- El acceso al contenido del cliente de la organización está restringido a personal específico de Microsoft.
- Microsoft 365 Government-DoD cumple con las certificaciones y acreditaciones necesarias para los clientes del sector público de los Estados Unidos.

Puede encontrar más información acerca de la oferta de Microsoft 365 Government-DoD para clientes del gobierno de Estados Unidos en [Office 365 planes de administración pública](https://products.office.com/government/compare-office-365-government-plans), incluidos los requisitos de elegibilidad.

La [Descripción del servicio Office 365 US Government](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) describe los beneficios de la plataforma, que se centran en cumplir con los requisitos de cumplimiento en los Estados Unidos.

> [!TIP]
> Es posible que desee transferir las tablas de información de la descripción del servicio a un libro de Excel y agregar dos columnas: **importante para mi organización y/n** y **que satisfaga las necesidades de la organización y/n**. A continuación, puede revisar esta lista con sus colegas para confirmar que este servicio cumple con las necesidades de su organización.

**Puntos de decisión**:<br/>
- *Decida si Microsoft 365 Government-DoD es adecuado para su organización.*
- *Confirmar que la organización cumple los requisitos de elegibilidad.*

> [!NOTE]
> Microsoft 365 Government-DoD solo está disponible en Estados Unidos. Los clientes que no son del gobierno de Estados Unidos pueden elegir entre varios [planes de Office 365 administración pública](https://products.office.com/government/compare-office-365-government-plans).

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>Paso 2. Solicitud para Microsoft 365 Government-DoD

Tras haber decidido que este servicio es adecuado para su organización, inicie el proceso de [solicitud para este servicio](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>Paso 3. Descripción de Microsoft 365 Government-configuración de seguridad predeterminada de DoD

Le recomendamos que tenga tiempo para revisar minuciosamente la configuración de administración y seguridad antes de modificarla y tenga en cuenta el impacto en el cumplimiento antes de realizar cambios en la configuración de seguridad predeterminada.

**Punto de decisión**: *decida si va a modificar cualquiera de los valores predeterminados de la configuración de seguridad de Microsoft 365 Government-DOD, resolviendo para comprender primero el impacto de los cambios que puede realizar.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>Paso 4. Conocer las funcionalidades que actualmente no están disponibles o deshabilitadas de forma predeterminada en Microsoft 365 Government – DoD<sup>1</sup>

Para cumplir los requisitos de nuestros clientes de la nube de administración pública, existen algunas diferencias entre los planes de Microsoft 365 Government-Enterprise. Consulte la tabla siguiente para ver las características que están disponibles. Consulte [aquí](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) para obtener las últimas actualizaciones de productos de cumplimiento publicadas en el mapa de ruta de Microsoft 365.<br><br>

| Área                                    | Característica                                         | Estado GCC             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Protección de la información**              | Analizador y cliente de etiquetado unificado         | Disponible              |
|                                         | Coincidencia exacta de datos          | Disponible               |
|                                         | Clasificación y etiquetado automáticos para Exchange Online, SharePoint Online y OneDrive                      | Publicación              |
|                                         | Clasificación y etiquetado automáticos para las aplicaciones de Office (Word, Excel, PowerPoint, Outlook) en todas las plataformas (Web, Android, iOS, Windows y Mac)            | En desarrollo |
|                                         | Clasificación y etiquetado automáticos para dispositivos móviles                                       | Sobre el trabajo pendiente de ingeniería              |
|                                         | Clasificación y etiquetado automáticos para Teams                            | Sobre el trabajo pendiente de ingeniería |
|                                         | Clasificación de datos: introducción y explorador de contenido                            | En desarrollo |
|                                         | Análisis: clasificadores de aprendizaje en equipo con etiquetado automático en el lado del servicio                           | Sobre el trabajo pendiente de ingeniería  |
|                                         | Análisis: clasificadores de aprendizaje en equipo con etiquetado automático en aplicaciones de Office/lado del cliente                           | Sobre el trabajo pendiente de ingeniería  |
|                                         | Cifra básico de mensajes de Office 365 (E3)                            | Disponible              |
|                                         | Cifrado avanzado de mensajes de Office 365 (e5)  | Disponible              |
|                                         | Clave del cliente de Office 365    | Disponible |
|                                         | Traer su propia clave (BYOK) para el ciclo de vida de aprovisionamiento de claves administradas por el cliente                            | Disponible |
|                                         | Mantenga su propia clave (HYOK) que abarca Azure Information Protection y Active Directory (AD) Rights Management (AD) Rights Management para escenarios altamente regulados (versión preliminar)                         | Disponible |
|                                         | Cifrado de claves doble                           | Publicación |
|                                         | Prevención de pérdida de datos (DLP) para archivos y correo electrónico         | Disponible |
|                                         | DLP para las conversaciones de canales y chat de Microsoft Teams         | Sobre el trabajo pendiente de ingeniería |
|                                         | Coincidencia exacta de datos de DLP         | Sobre el trabajo pendiente de ingeniería |
|                                         | Punto de conexión de DLP | Sobre el trabajo pendiente de ingeniería |
| **Gobierno de la información** | Gobierno de la información: archivado de correo electrónico                                       | Disponible              |
|                                         | Gobierno de la información: bloqueo de preservación          | Disponible              |
|                                         | Gobierno de la información: PST de importación                      | Disponible              |
|                                         | Gobierno de la información: etiquetas de retención manuales sin registro            | Disponible |
|                                         | Gobierno de la información: etiquetas de retención predeterminadas para las bibliotecas de SharePoint/OneDrive para la empresa, carpetas y conjuntos de documentos; Buzones de Exchange; y Office 365 grupos | Disponible              |
|                                         | Gobierno de la información: directivas de retención para toda la organización; ubicaciones o usuarios específicos; y automáticamente según una condición específica (por ejemplo, palabras clave o información confidencial)                                       | Disponible              |
|                                         | Gobierno de la información: directivas de retención con clasificadores capacitados                            | Sobre el trabajo pendiente de ingeniería |
|                                         | Gobierno de la información: directivas de retención para la grabación de reuniones de Microsoft Teams                            | Sobre el trabajo pendiente de ingeniería |
|                                         | Gobierno de la información: directivas de retención para Yammer y Teams                           | Sobre el trabajo pendiente de ingeniería              |
|                                         | Administración de registros: clasificación manual para etiquetas de registros                              | Disponible              |
|                                         | Administración de registros: etiquetas de registros predeterminadas para SharePoint, bibliotecas de documentos, carpetas y bibliotecas de OneDrive para la empresa; y Office 365 grupos                            | Disponible              |
|                                         | Administración de registros: directivas de registro automáticas basadas en condiciones específicas (por ejemplo, palabras clave o información confidencial); y se basa en un evento  | Disponible              |
|                                         | Administración de registros: revisión de disposición    | Disponible |
|                                         | Administración de registros: administrador del plan de archivos                            | Disponible |
|                                         | Administración de registros: prueba de la eliminación                         | Disponible |
|                                         | Administración de registros: registros normativos | Sobre el trabajo pendiente de ingeniería |
|                                         | Administración de registros: revisión de disposición en varias fases | Sobre el trabajo pendiente de ingeniería |
|                                         | Administración de registros: usar la clasificación de SharePoint Syntex para aplicar etiquetas de registro         | Sobre el trabajo pendiente de ingeniería |
| **Administración de riesgos internos**             | Caja de seguridad del cliente                                | Disponible            |
|                                         | Administración de riesgos de Insider: indicadores de Office para Teams, sitios de SharePoint, mensajes de correo electrónico                         | Sobre el trabajo pendiente de ingeniería |
|                                         | Administración de riesgos de Insider: robo de datos al pertenecer a los usuarios                        | Sobre el trabajo pendiente de ingeniería |
|                                         | Administración de riesgos de Insider: pérdidas de datos generales                                | Sobre el trabajo pendiente de ingeniería              |
|                                         | Administración de riesgos de Insider: investigar alertas de administración de riesgos de Insider                                   | Sobre el trabajo pendiente de ingeniería              |
|                                         | Administración de riesgos de Insider: panel de casos, explorador de contenido y plantillas de aviso | Sobre el trabajo pendiente de ingeniería |
|                                         | Administración de riesgos de Insider: escalar para la investigación de eDiscovery avanzado |Sobre el trabajo pendiente de ingeniería|
|                                         | Administración de riesgos de Insider: indicadores de dispositivos de actividad en Windows 10 compilación 1809 y posteriores |Sobre el trabajo pendiente de ingeniería|
|                                         | Administración de riesgos de Insider: indicadores de infracción de la Directiva de seguridad (versión preliminar) |Sobre el trabajo pendiente de ingeniería|
|                                         | Administración de riesgos de Insider: indicadores de las alertas de Microsoft defender para Endpoint (versión preliminar) |Sobre el trabajo pendiente de ingeniería|
|                                         | Administración de riesgos de Insider: plantillas de directiva para pérdidas de datos por usuarios con prioridad (versión preliminar) | Sobre el trabajo pendiente de ingeniería |
|                                         | Administración de riesgos de Insider: plantillas de directiva para pérdidas de datos por usuarios descontentos (versión preliminar) | Sobre el trabajo pendiente de ingeniería |
|                                         | Administración de riesgos de Insider: plantillas de directiva para infracciones de directivas de seguridad generales (versión preliminar) | Sobre el trabajo pendiente de ingeniería |
|                                         | Administración de riesgos de Insider: plantillas de directiva para las infracciones de directivas de seguridad por usuarios con prioridad, usuarios que deshabilitan, usuarios disgustados (versión preliminar) | Sobre el trabajo pendiente de ingeniería |
|                                         | Administración de riesgos de Insider: personalización de la Directiva (versión preliminar) | Sobre el trabajo pendiente de ingeniería |
|                                         | Administración de riesgos de Insider: exportar alertas (versión preliminar) | Sobre el trabajo pendiente de ingeniería |
|                                         | Administración de riesgos de Insider: grupos de usuarios prioritarios (versión preliminar) | Sobre el trabajo pendiente de ingeniería |
|                                         | Cumplimiento de comunicaciones (incluye directivas de supervisión): crear directivas de cliente, 3 preconfiguradas  | Sobre el trabajo pendiente de ingeniería |
|                                         | Cumplimiento de comunicaciones (con directivas de supervisión): soporte para Teams, Exchange y quitar mensajes de Microsoft Teams | Sobre el trabajo pendiente de ingeniería |
|                                         | Cumplimiento de comunicaciones (directivas de control incl.): alertas de acceso; plantillas de aviso; panel de directivas de comunicación | Sobre el trabajo pendiente de ingeniería  |
|                                         | Cumplimiento de la comunicación (con directivas de supervisión): escalar para la investigación para la exhibición avanzada de documentos electrónicos | Sobre el trabajo pendiente de ingeniería |
|                                         | Cumplimiento de comunicaciones (incluye directivas de supervisión): detección de contenido para adultos | Sobre el trabajo pendiente de ingeniería |
|                                         | Cumplimiento de la comunicación (con directivas de supervisión): detecta la infracción del código de conducta en el tiempo | Publicación |
|                                         | Cumplimiento de comunicaciones (incl. directivas de supervisión): compatibilidad con permisos más granulares | Publicación |
|                                         | Cumplimiento de comunicaciones (incl. directivas de supervisión): analizar datos de chat de usuarios con un buzón local | Publicación |
|                                         | Cumplimiento de comunicaciones (con directivas de supervisión): conflicto de plantilla de interés | Sobre el trabajo pendiente de ingeniería |
|                                         | Cumplimiento de la comunicación (con directivas de supervisión): capacidad para omitir la firma de correo electrónico o renuncia | Sobre el trabajo pendiente de ingeniería |
|                                         | Cumplimiento de comunicaciones (incl. directivas de supervisión): entrega de administración de riesgos de Insiders | Sobre el trabajo pendiente de ingeniería |
|                                         | Cumplimiento de comunicaciones (incl. directivas de supervisión): comprobación de estado de la Directiva y capacidad para pausar la Directiva | Sobre el trabajo pendiente de ingeniería |
|                                         | Cumplimiento de comunicaciones (incl. directivas de supervisión): convertir el contenido de mantenimiento durante la investigación | Sobre el trabajo pendiente de ingeniería |
|                                         | Cumplimiento de la comunicación (con directivas de supervisión): Burnout y Suicide Detection | Sobre el trabajo pendiente de ingeniería |
|                                         | Barreras de la información | Sobre el trabajo pendiente de ingeniería |
|                                         | Privileged Access Management                    | Sobre el trabajo pendiente de ingeniería |
| **Detección de & responder**                  | Exhibición de documentos electrónicos principal: preservación local                            | Disponible              |
|                                         | Exhibición de documentos electrónicos principal: administración de casos                                 | Disponible              |
|                                         | Exhibición de documentos electrónicos principal: búsqueda                                          | Disponible              |
|                                         | Exhibición de documentos electrónicos principal: exportación                                          | Disponible              |
|                                         | Exhibición de documentos electrónicos principal: descifrado de RMS                                  | Disponible              |
|                                         | Exhibición de documentos electrónicos principal: exportación nativa                                   | Disponible              |
|                                         | Exhibición de documentos electrónicos principal: auditoría                                        | Disponible              |
|                                         | Exhibición avanzada de documentos electrónicos: procesamiento avanzado                                 | Publicación |
|                                         | EDiscovery avanzado: custodio a asignación de carga de trabajo                                 | Publicación |
|                                         | Exhibición avanzada de documentos electrónicos: comunicaciones de custodios                                 | Publicación |
|                                         | Exhibición avanzada de documentos electrónicos: panel                   | Publicación |
|                                         | EDiscovery avanzado: subprocesamiento de correo electrónico                                          | Publicación |
|                                         | EDiscovery avanzado: exportar (descargar, exportar, agregar a otro conjunto de revisión)                               | Publicación |
|                                         | Exhibición avanzada de documentos electrónicos: filtrado                 | Publicación |
|                                         | EDiscovery avanzado: retención legal para los mensajes de canales privados de Teams                                         | Publicación |
|                                         | EDiscovery avanzado: identificación Near duplicada                                         | Publicación |
|                                         | EDiscovery avanzado: ingesta no de Office 365                                      | Publicación |
|                                         | EDiscovery avanzado: Codificación predictiva                                       | Publicación |
|                                         | Exhibición avanzada de documentos electrónicos: exportación procesada con cargar archivo                   | Publicación |
|                                         | Exhibición avanzada de documentos electrónicos: redacciones                        | Publicación |
|                                         | Exhibición avanzada de documentos electrónicos: conjuntos de revisión                                     | Publicación |
|                                         | EDiscovery avanzado: revisión y anotaciones                             | Publicación |
|                                         | Exhibición avanzada de documentos electrónicos: informe de términos de búsqueda                        | Publicación |
|                                         | EDiscovery avanzado: admitir contenido vinculado de OneDrive y SharePoint Online (datos adjuntos modernos)                        | Publicación |
|                                         | Exhibición avanzada de documentos electrónicos: etiquetado                              | Publicación |
|                                         | Exhibición avanzada de documentos electrónicos: compatibilidad con las reacciones de Teams                              | Publicación |
|                                         | Exhibición avanzada de documentos electrónicos: informes de inquilino                              | Publicación |
|                                         | Exhibición avanzada de documentos electrónicos: temas                              | Publicación |
|                                         | Exhibición avanzada de documentos electrónicos: Visores                              | Publicación |
|                                         | Exhibición avanzada de documentos electrónicos: eDiscovery avanzado de Yammer en el centro de cumplimiento de Microsoft                              | Publicación |
|                                         | Exhibición avanzada de documentos electrónicos: soporte de bytes CJK o doble para la exhibición avanzada de documentos electrónicos                              | En desarrollo |
|                                         | Auditoría básica                              | Disponible |
|                                         | Auditoría avanzada: acceso a eventos vitales (por ejemplo, mailitemsaccessed)                              | Publicación |
|                                         | Auditoría avanzada: mayor ancho de banda para la API de actividad de administración                              | Publicación |
|                                         | Auditoría avanzada: retención de registro (1 año)                              | Publicación |
|                                         | Auditoría avanzada: disponibilidad del centro de seguridad y cumplimiento                              | Disponible |
|                                         | Auditoría avanzada: retención a largo plazo en registros de auditoría (10 años)                              | Sobre el trabajo pendiente de ingeniería |
|                                         | Auditoría avanzada: eventos de envío de correo y reenvío de correo                              | Sobre el trabajo pendiente de ingeniería |
|                                         | Auditoría avanzada: información de auditoría procesada                              | Sobre el trabajo pendiente de ingeniería |
|                                         | Auditoría avanzada: buscar eventos de término en Exchange Online y SharePoint Online                              | Sobre el trabajo pendiente de ingeniería |
|    **Administración de cumplimiento**            | Centro de seguridad y cumplimiento de Microsoft 365                              | Disponible |
|                                         | Microsoft Cloud App Security                              | Sobre el trabajo pendiente de ingeniería |
|                                         | Administrador de cumplimiento                              | Sobre el trabajo pendiente de ingeniería |
|                                         | Compatibilidad con caracteres de doble byte                              | Sobre el trabajo pendiente de ingeniería |
|    **Sistema**            | API de Graph para eDiscovery avanzado                              | En desarrollo |
|                                         | Conectores de datos de origen                              | Sobre el trabajo pendiente de ingeniería |
|                                         | Conectores de datos de terceros                              | Sobre el trabajo pendiente de ingeniería |
|                                         | API de Graph para la exportación de datos de Microsoft Teams                              | Sobre el trabajo pendiente de ingeniería |

<sup>1</sup> el estado identificado está sujeto a cambios a medida que se reevalúan los planes y las prioridades de los proyectos.<br/>

**Punto de decisión**: *decida si las características de cumplimiento satisfacen las necesidades de su organización.*
