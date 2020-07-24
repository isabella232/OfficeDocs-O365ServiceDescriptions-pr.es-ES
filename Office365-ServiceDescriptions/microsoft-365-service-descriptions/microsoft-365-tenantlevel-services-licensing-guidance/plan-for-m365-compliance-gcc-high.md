---
title: Plan para las implementaciones del Centro de cumplimiento de Microsoft 365 - GCC High
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Esta guía está dirigida a los profesionales de ti que imponen las implementaciones de Office 365 en entidades del gobierno federal de Estados Unidos u otras entidades que administran datos sujetos a las regulaciones y los requisitos gubernamentales, donde el uso de Microsoft 365 Government – GCC High es apropiado para cumplir estos requisitos.
ms.openlocfilehash: f81f2382f41d2ba1aa6fcd5dabc593b20eba7bc1
ms.sourcegitcommit: d4025c73f14b663ffcaa1ef8db4174b51debdae7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/23/2020
ms.locfileid: "45388076"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Plan para Microsoft 365 Compliance – GCC High

Esta guía está dirigida a los profesionales de ti que imponen las implementaciones de Office 365 en entidades del gobierno federal de Estados Unidos u otras entidades que administran datos sujetos a las regulaciones y los requisitos gubernamentales, donde el uso de Microsoft 365 Government – GCC High es apropiado para cumplir estos requisitos.

> [!NOTE]
>Si su organización ya ha cumplido con los requisitos de elegibilidad elevados de Microsoft 365 gubernamentales – GCC y ha sido aceptado en el programa, puede omitir los pasos 1 y 2 e ir directamente al paso 3.
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>Paso 1. Determinar si su organización necesita Microsoft 365 Government – GCC High y cumple los requisitos de elegibilidad

El entorno alto de Microsoft 365 Government-GCC cumple con los requisitos del gobierno de Estados Unidos para los servicios en la nube. Además de disfrutar de las características y capacidades de Office 365, las organizaciones se benefician de las siguientes características exclusivas de Microsoft 365 Government – GCC High:

- El contenido del cliente de la organización se separa lógicamente del contenido del cliente en los servicios comerciales de Office 365 de Microsoft.
- El contenido del cliente de la organización se almacena dentro de los Estados Unidos.
- El acceso al contenido del cliente de la organización está restringido a personal específico de Microsoft.
- Microsoft 365 Government – GCC High cumple con las certificaciones y acreditaciones necesarias para los clientes del sector público de los Estados Unidos.

Puede encontrar más información sobre la oferta de Microsoft 365 Government – GCC High offer for US Government customers en [Office 365, planes gubernamentales](https://products.office.com/government/compare-office-365-government-plans), incluidos los requisitos de elegibilidad.

La [Descripción del servicio Office 365 US Government](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) describe los beneficios de la plataforma, que se centran en cumplir con los requisitos de cumplimiento en los Estados Unidos.

> [!TIP]
> Es posible que desee transferir las tablas de información de la descripción del servicio a un libro de Excel y agregar dos columnas: **importante para mi organización y/n**   y **que satisfaga las necesidades de la organización y/n**. A continuación, puede revisar esta lista con sus colegas para confirmar que este servicio cumple con las necesidades de su organización.

**Puntos de decisión**:<br/>
- *Decida si Microsoft 365 Government – GCC-High es adecuado para su organización.*
- *Confirmar que la organización cumple los requisitos de elegibilidad.*

> [!NOTE]
> Microsoft 365 Government-GCC High solo está disponible en Estados Unidos. Los clientes que no son del gobierno de Estados Unidos pueden elegir entre varios [planes de Office 365 administración pública](https://products.office.com/government/compare-office-365-government-plans).

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>Paso 2. Solicitud para Microsoft 365 Government – GCC-High

Tras haber decidido que este servicio es adecuado para su organización, inicie el proceso de [solicitud para este servicio](https://products.office.com/government/eligibility-validation).
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>Paso 3. Descripción de la configuración de seguridad predeterminada de Microsoft 365 Government – GCC-High

Le recomendamos que tenga tiempo para revisar minuciosamente la configuración de administración y seguridad antes de modificarla y tenga en cuenta el impacto en el cumplimiento antes de realizar cambios en la configuración de seguridad predeterminada.

**Punto de decisión**: *decida si va a modificar cualquiera de los valores predeterminados de configuración de Microsoft 365 Government-High Security, que se resuelven para comprender primero el impacto de los cambios que puede realizar.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>Paso 4. Comprenda las funcionalidades que actualmente no están disponibles o deshabilitadas de forma predeterminada en Microsoft 365 Government – GCC-High<sup>1</sup>

Para cumplir con los requisitos de nuestros clientes de la nube de administración pública, existen algunas diferencias entre los planes de Microsoft 365 administración pública – GCC-High y Enterprise. Consulte la tabla siguiente para ver las características que están disponibles.

|                                         | Característica                                         | Estado alta de GCC        |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Protección de la información & gobernanza** | Archivado                                       | Disponible              |
|                                         | Etiquetas y directivas manuales<sup>2</sup>          | Disponible              |
|                                         | Aplicación automática de etiquetas                      | Sobre el trabajo pendiente de ingeniería |
|                                         | Etiquetas basadas en tipos de datos confidenciales            | Sobre el trabajo pendiente de ingeniería |
|                                         | Etiquetas y directivas asociadas basadas en consultas | Sobre el trabajo pendiente de ingeniería |
|                                         | Plan de archivos                                       | Sobre el trabajo pendiente de ingeniería |
|                                         | Directivas recomendadas                            | Sobre el trabajo pendiente de ingeniería |
|                                         | Filtros de importación inteligente                            | Sobre el trabajo pendiente de ingeniería |
|                                         | Retención basada en eventos                           | Sobre el trabajo pendiente de ingeniería |
|                                         | Revisión para eliminación                              | Sobre el trabajo pendiente de ingeniería |
|                                         | Barreras de información                            | Disponible              |
|                                         | Prevención de pérdida de datos (DLP) para archivos y correo electrónico  | Disponible              |
|                                         | DLP para las conversaciones de canales y chat de Microsoft Teams    | Sobre el trabajo pendiente de ingeniería |
|                                         | Coincidencia exacta de datos de DLP                            | Sobre el trabajo pendiente de ingeniería |
|                                         | Explorador de actividad de etiquetas                         | Sobre el trabajo pendiente de ingeniería |
|                                         | Clasificadores capacitados                           | Sobre el trabajo pendiente de ingeniería |
|                                         | Etiquetas unificadas y de confidencialidad         | Sobre el trabajo pendiente de ingeniería |
| **Administración de riesgos internos**             | Cifrado de mensajes avanzado                     | Disponible              |
|                                         | Administración de riesgos de Insider                         | Sobre el trabajo pendiente de ingeniería |
|                                         | Cumplimiento de las comunicaciones                        | Sobre el trabajo pendiente de ingeniería |
|                                         | Caja de seguridad del cliente                                | Disponible              |
|                                         | Clave de cliente                                    | Disponible              |
|                                         | Administración del acceso con privilegios                    | Sobre el trabajo pendiente de ingeniería |
| **Detección de & responder**                  | Exhibición de documentos electrónicos principal: preservación local                            | Disponible              |
|                                         | Exhibición de documentos electrónicos principal: administración de casos                                 | Disponible              |
|                                         | Exhibición de documentos electrónicos principal: búsqueda                                          | Disponible              |
|                                         | Exhibición de documentos electrónicos principal: exportación                                          | Disponible              |
|                                         | Exhibición de documentos electrónicos principal: descifrado de RMS                                  | Disponible              |
|                                         | Exhibición de documentos electrónicos principal: exportación nativa                                   | Disponible              |
|                                         | Exhibición de documentos electrónicos principal: procesamiento avanzado                             | Disponible              |
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
| **Administración de cumplimiento**               | Puntuación de cumplimiento                                 | Sobre el trabajo pendiente de ingeniería |

<sup>1</sup> el estado identificado está sujeto a cambios a medida que se reevalúan los planes y las prioridades de los proyectos.<br/>
<sup>2</sup> la aplicación manual de etiquetas requiere el [cliente de Azure Information Protection (AIP) versión 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history). 


**Punto de decisión**: *decida si las características de cumplimiento satisfacen las necesidades de su organización.*
