---
title: Plan para las implementaciones del Centro de cumplimiento de Microsoft 365 - GCC
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Esta guía está dirigida a los profesionales de ti que imponen las implementaciones de Office 365 en entidades gubernamentales de Estados Unidos, Estados, locales, Tribals o entidades gubernamentales, o en otras entidades que administran datos sujetos a los requisitos y las regulaciones gubernamentales, donde el uso de Microsoft 365 Government-GCC es adecuado para cumplir con estos requisitos.
ms.openlocfilehash: af09151b0ab1060c5a00c60d0b05bbd69c3300c0
ms.sourcegitcommit: 638bacac9e663444f7a094d5887476d8a87e3b58
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/18/2020
ms.locfileid: "47962139"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>Planeación de cumplimiento de Microsoft 365: GCC

Esta guía está dirigida a los profesionales de ti que imponen las implementaciones de Office 365 en entidades gubernamentales de Estados Unidos, Estados, locales, Tribals o entidades gubernamentales, o en otras entidades que administran datos sujetos a los requisitos y las regulaciones gubernamentales, donde el uso de Microsoft 365 Government-GCC es adecuado para cumplir con estos requisitos.

> [!NOTE]
> Si su organización ya cumple con los requisitos de elegibilidad de Microsoft 365 gubernamentales-GCC y se ha aceptado y se ha aceptado en el programa, puede omitir los pasos 1 y 2 y ir directamente al paso 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>Paso 1. Determinar si su organización necesita Microsoft 365 Government-GCC y cumple con los requisitos de elegibilidad

El entorno Microsoft 365 Government-GCC cumple con los requisitos del gobierno de Estados Unidos para los servicios en la nube, incluido el FedRAMP moderado, y los requisitos de la justicia penal y los sistemas de información de impuestos federales (tipos de datos CJI y FTI).

Además de disfrutar de las características y capacidades de Office 365, las organizaciones se benefician de las siguientes características exclusivas de Microsoft 365 Government-GCC:

- El contenido del cliente de la organización se separa lógicamente del contenido del cliente en los servicios comerciales de Office 365 de Microsoft.

- El contenido del cliente de la organización se almacena dentro de los Estados Unidos.

- El acceso al contenido del cliente de la organización está restringido a personal específico de Microsoft.

- Microsoft 365 Government-GCC cumple con las certificaciones y acreditaciones necesarias para los clientes del sector público de los Estados Unidos.

Puede encontrar más información sobre la oferta de Microsoft 365 Government-GCC para los clientes del gobierno de Estados Unidos en [Office 365 planes de administración pública](https://products.office.com/government/compare-office-365-government-plans), incluidos los requisitos de elegibilidad.

La [Descripción del servicio Office 365 US Government](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) describe los beneficios de la plataforma, que se centran en cumplir con los requisitos de cumplimiento en los Estados Unidos.

> [!TIP]
> Es posible que desee transferir las tablas de información de la descripción del servicio a un libro de Excel y agregar dos columnas: **importante para mi organización y/n**   y **que satisfaga las necesidades de la organización y/n**. A continuación, puede revisar esta lista con sus colegas para confirmar que este servicio cumple con las necesidades de su organización.

> [!NOTE]
> Microsoft 365 Government-GCC solo está disponible en Estados Unidos. Los clientes que no son del gobierno de Estados Unidos pueden elegir entre varios [planes de Office 365 administración pública](https://products.office.com/government/compare-office-365-government-plans).

**Puntos de decisión**: <br/>
- *Decida si Microsoft 365 Government-GCC es adecuado para su organización.*
- *Confirmar que la organización cumple los requisitos de elegibilidad.*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>Paso 2. Solicitud para Microsoft 365 Government-GCC

Tras haber decidido que este servicio es adecuado para su organización, inicie el proceso de [solicitud para este servicio](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>Paso 3. Descripción de la configuración de seguridad predeterminada de Microsoft 365 Government-GCC

Le recomendamos que tenga tiempo para revisar minuciosamente la configuración de administración y seguridad antes de modificarla y tenga en cuenta el impacto en el cumplimiento antes de realizar cambios en la configuración de seguridad predeterminada.

**Punto de decisión**: *decida si va a modificar cualquiera de las configuraciones de seguridad predeterminadas de Microsoft 365 Government-GCC, que se resuelven para comprender primero el impacto de los cambios que puede realizar.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>Paso 4. Conocer las funcionalidades que actualmente no están disponibles o deshabilitadas de forma predeterminada en Microsoft 365 Government – GCC<sup>1</sup>

Para cumplir los requisitos de nuestros clientes de la nube de administración pública, existen algunas diferencias entre los planes de Microsoft 365 gubernamentales-GCC y Enterprise. Consulte la tabla siguiente para ver las características que están disponibles.

|                                         | **Característica**                                     | **Estado GCC**         |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Protección de la información**              | Etiquetas unificadas y de confidencialidad         | Disponible              |
|                                         | Etiquetas de contenedor para SharePoint Online, grupos de Office          | Publicación              |
|                                         | Etiquetado automático basado en tipos de datos confidenciales para Excel online, SharePoint Online, OneDrive para la empresa                      | Publicación              |
|                                         | Etiquetas basadas en tipos de datos confidenciales para los clientes de Office Win32 y Mac            | Sobre el trabajo pendiente de ingeniería |
|                                         | Etiquetado automático basado en tipos de datos confidenciales para Win 32, Mac |  Sobre el trabajo pendiente de ingeniería              |
|                                         | Etiquetado automático basado en tipos de datos confidenciales para Teams                                       |Sobre el trabajo pendiente de ingeniería              |
|                                         | Etiquetado automático basado en tipos de datos confidenciales para dispositivos móviles                            |Sobre el trabajo pendiente de ingeniería |
|                                         | Etiquetas y directivas asociadas basadas en consultas                            | Disponible |
|                                         | Explorador de actividad de etiquetas                           | Sobre el trabajo pendiente de ingeniería  |
|                                         | Clasificadores que se pueden entrenar                              | Sobre el trabajo pendiente de ingeniería              |
|                                         | Cifra básico de mensajes de Office 365 (E3)                            | Disponible              |
|                                         | Cifrado avanzado de mensajes de Office 365 (e5)  | Disponible              |
|                                         | Clave del cliente de Office 365    | Disponible |
|                                         | Traer su propia clave (BYOK) para el ciclo de vida de aprovisionamiento de claves administradas por el cliente                            | Disponible |
|                                         | Mantenga su propia clave (HYOK) que abarca Azure Information Protection y Active Directory (AD) Rights Management (AD) Rights Management para escenarios altamente regulados (versión preliminar)                         | Disponible |
|                                         | Cifrado de claves doble                           | Sobre el trabajo pendiente de ingeniería |
|                                         | Prevención de pérdida de datos (DLP) para archivos y correo electrónico         | Disponible |
|                                         | DLP para las conversaciones de canales y chat de Microsoft Teams         | Publicación |
|                                         | Coincidencia exacta de datos de DLP | Sobre el trabajo pendiente de ingeniería |
|                                         | Punto de conexión de DLP | Sobre el trabajo pendiente de ingeniería |
| **Gobierno de la información** | Archivado de correo electrónico                                       | Disponible              |
|                                         | Bloqueo de conservación          | Disponible              |
|                                         | Archivo PST de importación                      | Disponible              |
|                                         | Etiquetas de retención manuales sin registro            | Disponible |
|                                         | Etiquetas de retención predeterminadas para bibliotecas, carpetas y conjuntos de documentos de SharePoint/OneDrive para la empresa; Buzones de Exchange; y Office 365 grupos | Disponible              |
|                                         | Directivas de retención para toda la organización; ubicaciones o usuarios específicos; y automáticamente según la condición específica (por ejemplo, palabras clave o información confidencial)                                       | Disponible              |
|                                         | Directivas de retención con clasificador capacitado                            | Sobre el trabajo pendiente de ingeniería |
|                                         | Directivas de retención para Yammer y Teams                            | Sobre el trabajo pendiente de ingeniería |
|                                         | Etiquetas de registros manuales                           | Disponible              |
|                                         | Etiquetas de registro predeterminadas para SharePoint, bibliotecas de documentos, carpetas y bibliotecas de OneDrive para la empresa; y Office 365 grupos                              | Disponible              |
|                                         | Directivas de registro automáticas basadas en condiciones específicas (por ejemplo, palabras clave o información confidencial); y se basa en un evento                            | Disponible              |
|                                         | Revisión para eliminación  | Disponible              |
|                                         | Administrador del plan de archivos    | Disponible |
|                                         | Prueba de la eliminación                            | Disponible |
|                                         | Registros normativos                         | Sobre el trabajo pendiente de ingeniería |
|                                         | Obligatoriedad de licencias de administración de registros                           | Sobre el trabajo pendiente de ingeniería |
|                                         | Revisión de disposición en varias fases de administración de registros | Sobre el trabajo pendiente de ingeniería |
|                                         | Explorador de actividad de etiquetas | Sobre el trabajo pendiente de ingeniería |
|                                         | Clasificadores que se pueden entrenar | Sobre el trabajo pendiente de ingeniería |
|                                         | Etiquetas unificadas y de confidencialidad         | Sobre el trabajo pendiente de ingeniería |
| **Administración de riesgos internos**             | Caja de seguridad del cliente                                | Disponible            |
|                                         | Indicadores de Office para equipos, sitios de SharePoint, mensajes de correo electrónico                         | Publicación |
|                                         | Robo de datos al pertenecer a los usuarios                        | Publicación |
|                                         | Pérdidas de datos generales                                | Publicación              |
|                                         | Investigar las alertas de administración de riesgos de Insider                                   | Publicación              
|                                         | Panel de caso de administración de riesgos de Insider, plantillas de aviso y explorador de contenido | Publicación |
|                                         | Escalar para la investigación de eDiscovery avanzado | Publicación|
|                                         | Pérdidas de datos por usuarios con prioridad (versión preliminar) | sobre el trabajo pendiente de ingeniería |
|                                         | Pérdidas de datos por usuarios descontentos (versión preliminar) | sobre el trabajo pendiente de ingeniería |
|                                         | Infracciones de directivas de seguridad generales (versión preliminar) | sobre el trabajo pendiente de ingeniería |
|                                         | Infracciones de directivas de seguridad por usuarios de prioridad, usuarios de desactivación, usuarios descontentos (versión preliminar) | sobre el trabajo pendiente de ingeniería |
|                                         | Personalización de la Directiva (versión preliminar) | sobre el trabajo pendiente de ingeniería |
|                                         | Exportar alertas (versión preliminar) | sobre el trabajo pendiente de ingeniería |
|                                         | Grupos de usuarios con prioridad (versión preliminar) | sobre el trabajo pendiente de ingeniería |
|                                         | Crear directivas de cliente, 3 preconfiguradas para el cumplimiento de comunicaciones (incl. directivas de supervisión)  | Publicación |
|                                         | Compatibilidad con la comunicación (directivas de control incl.) para Teams, Exchange y quitar mensajes de Microsoft Teams | Publicación |
|                                         | Cumplimiento de comunicaciones (directivas de supervisión incl.) acceso a alertas; plantillas de aviso; panel de directivas de comunicación | Publicación  |
|                                         | Cumplimiento de la comunicación (con directivas de supervisión) escala para la investigación para la exhibición avanzada de documentos electrónicos | Publicación |
|                                         | Cumplimiento de comunicaciones (directivas de supervisión incl.) detectar contenido para adultos | Publicación |
|                                         | Barreras de información | Sobre el trabajo pendiente de ingeniería |
|                                         | Privileged Access Management                    | Sobre el trabajo pendiente de ingeniería |
| **Detección de & responder**                  | Exhibición de documentos electrónicos principal: preservación local                            | Disponible              |
|                                         | Exhibición de documentos electrónicos principal: administración de casos                                 | Disponible              |
|                                         | Exhibición de documentos electrónicos principal: búsqueda                                          | Disponible              |
|                                         | Exhibición de documentos electrónicos principal: exportación                                          | Disponible              |
|                                         | Exhibición de documentos electrónicos principal: descifrado de RMS                                  | Disponible              |
|                                         | Exhibición de documentos electrónicos principal: exportación nativa                                   | Disponible              |
|                                         | Exhibición de documentos electrónicos principal: auditoría                                        | Disponible              |
|                                         | Exhibición avanzada de documentos electrónicos: procesamiento avanzado                             | Disponible |
|                                         | EDiscovery avanzado: subprocesamiento de correo electrónico                                 | Disponible |
|                                         | EDiscovery avanzado: identificación Near duplicada                   | Disponible |
|                                         | Exhibición avanzada de documentos electrónicos: temas                                          | Disponible |
|                                         | EDiscovery avanzado: Codificación predictiva                               | Disponible |
|                                         | Exhibición avanzada de documentos electrónicos: exportación procesada con cargar archivo                 | Disponible |
|                                         | Exhibición avanzada de documentos electrónicos: etiquetado                                         | Disponible |
|                                         | Exhibición avanzada de documentos electrónicos: Visores                                         | Disponible |
|                                         | Exhibición avanzada de documentos electrónicos: redacciones                                      | Disponible |
|                                         | Exhibición avanzada de documentos electrónicos: filtrado                                       | Disponible |
|                                         | EDiscovery avanzado: custodio a asignación de carga de trabajo                   | Disponible |
|                                         | Exhibición avanzada de documentos electrónicos: comunicaciones de custodios                        | Disponible |
|                                         | Exhibición avanzada de documentos electrónicos: conjuntos de revisión                                     | Disponible |
|                                         | EDiscovery avanzado: revisión y anotaciones                             | Disponible |
|                                         | EDiscovery avanzado: ingesta no de Office 365                        | Disponible |
|                                         | Exhibición avanzada de documentos electrónicos: informe de términos de búsqueda                              | Disponible |
|                                         | Auditoría básica                              | Disponible |
|                                         | Auditoría avanzada: acceso a eventos vitales (por ejemplo, mailitemsaccessed)                              | Publicación |
|                                         | Retención de registro de auditoría avanzada (1 año)                               | Publicación |
|                                         | Mayor ancho de banda de auditoría avanzada para la API de actividad de administración                              | Publicación |
|    **Administración de cumplimiento**            | Relevancia y administrador de cumplimiento                              | Sobre el trabajo pendiente de ingeniería |




<sup>1</sup> el estado identificado está sujeto a cambios a medida que se reevalúan los planes y las prioridades de los proyectos.<br/>
<sup>2</sup> la aplicación manual de etiquetas requiere el [cliente de Azure Information Protection (AIP) versión 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history).


**Punto de decisión**: *decida si las características de cumplimiento satisfacen las necesidades de su organización.*
