---
title: Plan para las implementaciones del Centro de cumplimiento de Microsoft 365 - GCC
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Esta guía está para profesionales de TI que impulsan implementaciones de Office 365 en entidades gubernamentales federales, estatales, locales, tribales o territoriales de Estados Unidos u otras entidades que administran datos que están sujetos a normativas y requisitos gubernamentales, donde el uso de Microsoft 365 Government - GCC es adecuado para cumplir estos requisitos.
ms.openlocfilehash: d3be49d3171e07cfc11e6d6924a8b5ec2395d920
ms.sourcegitcommit: f7874215059c1e5a9d383da0539f87b6f85a57e6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/25/2021
ms.locfileid: "52001906"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>Planear el cumplimiento de Microsoft 365: GCC

Esta guía está para profesionales de TI que impulsan implementaciones de Office 365 en entidades gubernamentales federales, estatales, locales, tribales o territoriales de Estados Unidos u otras entidades que administran datos que están sujetos a normativas y requisitos gubernamentales, donde el uso de Microsoft 365 Government - GCC es adecuado para cumplir estos requisitos.

> [!NOTE]
> Si su organización ya ha cumplido los requisitos de elegibilidad de Microsoft 365 Government - GCC y ha solicitado y aceptado en el programa, puede omitir los pasos 1 y 2 e ir directamente al paso 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>Paso 1. Determinar si su organización necesita Microsoft 365 Government - GCC y cumple los requisitos de elegibilidad

El entorno de Microsoft 365 Government - GCC cumple con los requisitos gubernamentales de Los Estados Unidos para los servicios en la nube, incluido FedRAMP Moderado, y los requisitos para la justicia penal y los sistemas de información fiscal federal (tipos de datos CJI y FTI).

Además de disfrutar de las características y capacidades de Office 365, las organizaciones se benefician de las siguientes características que son exclusivas de Microsoft 365 Government - GCC:

- El contenido de cliente de su organización se separa lógicamente del contenido de los clientes en los servicios comerciales de Office 365 de Microsoft.

- El contenido del cliente de la organización se almacena dentro de los Estados Unidos.

- El acceso al contenido del cliente de la organización está restringido a personal específico de Microsoft.

- Microsoft 365 Government: GCC cumple con las certificaciones y acreditaciones necesarias para los clientes del sector público de Estados Unidos.

Encontrará más información sobre la oferta de Microsoft 365 Government - GCC para los clientes de Us Government en los planes de [Office 365 Government,](https://products.office.com/government/compare-office-365-government-plans)incluidos los requisitos de elegibilidad.

La descripción del servicio de [Office 365 US Government](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) describe las ventajas de la plataforma, que se centra en cumplir los requisitos de cumplimiento dentro de los Estados Unidos.

> [!TIP]
> Es posible que desee transferir las tablas de información de la descripción del servicio a un libro de Excel y agregar dos columnas: Relevante para mi organización **Y/N** y Cumple las necesidades de mi organización **Y/N**. A continuación, puede revisar esta lista con sus compañeros para confirmar que este servicio satisface las necesidades de su organización.

> [!NOTE]
> Microsoft 365 Government: GCC solo está disponible en Los Estados Unidos. Los clientes que no son de Estados Unidos pueden elegir entre varios planes [de Office 365 Government](https://products.office.com/government/compare-office-365-government-plans).

**Puntos de decisión**: <br/>
- *Decida si Microsoft 365 Government: GCC es adecuado para su organización.*
- *Confirme que su organización cumple los requisitos de elegibilidad.*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>Paso 2. Solicitar Microsoft 365 Government - GCC

Después de haber decidido que este servicio es adecuado para su organización, inicie el proceso de [solicitud de este servicio](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>Paso 3. Información sobre Microsoft 365 Government: configuración de seguridad predeterminada de GCC

Se recomienda que se tome tiempo para revisar detenidamente la configuración de seguridad y administración antes de modificarlas y tener en cuenta el impacto en el cumplimiento antes de realizar cualquier cambio en la configuración de seguridad predeterminada.

**Punto de** decisión: decida si modificará alguna de las opciones predeterminadas de seguridad de *Microsoft 365 Government - GCC,* resolviendo primero el impacto de los cambios que pueda realizar.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>Paso 4. Comprender qué funcionalidades no están disponibles o deshabilitadas de forma predeterminada en Microsoft 365 Government – GCC<sup>1</sup>

Para satisfacer los requisitos de nuestros clientes en la nube gubernamentales, existen algunas diferencias entre Microsoft 365 Government- GCC y planes de empresa. Consulte la tabla siguiente para ver qué características están disponibles. Vea [aquí](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) las últimas actualizaciones de productos de cumplimiento publicadas en la guía básica de Microsoft 365.<br><br>

| Área | Característica | Estado de GCC |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Protección de la información**              | Cliente y escáner de etiquetado unificados         | Disponible              |
|                                         | Coincidencia exacta de datos          | Disponible              |
| Etiquetado de confidencialidad                    | Clasificación y etiquetado automáticos para Exchange Online, SharePoint Online y OneDrive                      | Disponible         |
| Etiquetado de confidencialidad                    | Clasificación y etiquetado automáticos para aplicaciones de Office (Word, Excel, PowerPoint, Outlook) en plataformas (web, Android, iOS, Windows y Mac) |  Disponible              |
| Etiquetado de confidencialidad                    | Clasificación y etiquetado automáticos para clientes de Office (Móvil)                                       | En el trabajo pendiente de ingeniería              |
| Etiquetado de confidencialidad                    | Clasificación y etiquetado automáticos para Teams, Grupos de Microsoft 365, sitios de SharePoint                            | Disponible |
| Análisis                               | Análisis de clasificación de datos: Información general y Explorador de contenido                            | Disponible |
| Análisis                               | Análisis: clasificadores de aprendizaje automático con etiquetado automático en el lado del servicio                           | En el trabajo pendiente de ingeniería  |
| Análisis                               | Análisis: clasificadores de aprendizaje automático con etiquetado automático en el lado cliente/aplicaciones de Office                           | Implementando |
| Cifrado                              | Cifrado de mensajes básico de Office 365 (E3)                            | Disponible              |
| Cifrado                              | Cifrado de mensajes avanzado de Office 365 (E5)  | Disponible              |
| Cifrado                              | Clave del cliente de Office 365    | Disponible |
| Cifrado                              | Clave de cliente: cifrado de datos en reposo para Microsoft 365    | Implementando |
| Cifrado                              | Bring Your Own Key (BYOK) para el ciclo de vida de aprovisionamiento de claves administradas por el cliente                            | Disponible |
| Cifrado                              | Cifrado de claves doble                           | Disponible |
| Cifrado                              | Cifrado de servicio de Exchange Online con claves administradas de Microsoft         | Disponible |
| Prevención de pérdida de datos                    | Prevención de pérdida de datos (DLP) para archivos y correo electrónico         | Disponible |
| Prevención de pérdida de datos                    | Conversaciones de chat y canales de DLP para Teams         | Disponible |
| Prevención de pérdida de datos                    | Extremo DLP | Implementando |
| Prevención de pérdida de datos                    | Panel de alertas | En desarrollo |
| Prevención de pérdida de datos                    | Página Información general | En desarrollo |
| **Gobierno de información** | Ámbitos adaptables para directivas de retención y etiquetado                 | En el trabajo pendiente de ingeniería              |
| Información de gobierno                 | Archivado de correo electrónico          | Disponible              |
| Información de gobierno                 | Etiquetas de retención predeterminadas para bibliotecas, carpetas y conjuntos de documentos de SharePoint, OneDrive para la Empresa; Bandejas de entrada de Exchange; y grupos de Office 365          | Disponible              |
| Información de gobierno                 | Importar PST                      | Disponible              |
| Información de gobierno                 | Etiquetas de retención manual sin registro            | Disponible |
| Información de gobierno                 | Bloqueo de conservación            | Disponible |
| Información de gobierno                 | Directivas de retención para toda la organización; ubicaciones o usuarios específicos; automáticamente en función de una condición específica (por ejemplo, palabras clave o información confidencial); y en función de un evento                                       | Disponible              |
| Información de gobierno                 | Directivas de retención para Teams                            | Disponible |
| Información de gobierno                 | Directivas de retención para el registro de reuniones de Teams                            | En desarrollo |
| Información de gobierno                 | Directivas de retención para canales privados de Teams                            | En el trabajo pendiente de ingeniería |
| Información de gobierno                 | Directivas de retención para canales compartidos de Teams                            | En el trabajo pendiente de ingeniería |
| Información de gobierno                 | Directivas de retención con clasificadores capacitados                            | En el trabajo pendiente de ingeniería |
| Información de gobierno                 | Directivas de retención para Yammer                            | En el trabajo pendiente de ingeniería |
| Administración de registros                     | Capacidad para eliminar una etiqueta de registro                           | En desarrollo              |
| Administración de registros                     | Aplicar una etiqueta de registro manualmente                            | Disponible              |
| Administración de registros                     | Aplicar etiquetas de registro predeterminadas para bibliotecas, carpetas y conjuntos de documentos de SharePoint, OneDrive para la Empresa; y grupos de Office 365                              | Disponible              |
| Administración de registros                     | Aplicar directivas de registro automáticamente en función de condiciones específicas (por ejemplo, palabras clave o información confidencial); y en función de un evento                            | Disponible              |
| Administración de registros                     | Aplicar directivas de registro automáticamente con clasificadores que se pueden entrenar  | En desarrollo              |
| Administración de registros                     | Revisión para eliminación  | Disponible              |
| Administración de registros                     | Administrador del plan de archivos    | Disponible |
| Administración de registros                     | Revisión de disposición de varias fases    | En el trabajo pendiente de ingeniería |
| Administración de registros                     | Soporte de cliente de Outlook para administración de registros    | En el trabajo pendiente de ingeniería |
| Administración de registros                     | Flujo de Power Automate al final del período de retención    | En el trabajo pendiente de ingeniería |
| Administración de registros                     | Conservación y etiquetado automático de datos adjuntos en la nube    | En el trabajo pendiente de ingeniería |
| Administración de registros                     | Prueba de eliminación                            | Disponible |
| Administración de registros                     | Control de versiones de registros                            | Disponible |
| Administración de registros                     | Registros normativos                         | Disponible |
| Administración de registros                     | Usar la clasificación de Syntex de SharePoint para aplicar etiquetas de registro | En el trabajo pendiente de ingeniería |
| **Administración de riesgos internos**             | Caja de seguridad del cliente                                | Disponible            |
| Cumplimiento de la comunicación                | Capacidad para omitir la firma de correo electrónico o la declinación de responsabilidades                         | En desarrollo |
| Cumplimiento de la comunicación                | Capacidad para establecer un período de retención para una directiva de cumplimiento de comunicaciones                         | En desarrollo |
| Cumplimiento de la comunicación                | Obtener acceso a alertas; plantillas de aviso; panel de directivas de comunicación                         | Disponible |
| Cumplimiento de la comunicación                | Analizar datos de chat de Teams de usuarios con buzón local                         | Disponible |
| Cumplimiento de la comunicación                | Supervisar automáticamente todos los equipos de los que un usuario es miembro                         | Disponible |
| Cumplimiento de la comunicación                | Plantilla de conflicto de intereses                         | Disponible |
| Cumplimiento de la comunicación                | Crear directivas de cliente, 3 preconfiguradas                         | Disponible |
| Cumplimiento de la comunicación                | Detectar contenido para adultos                         | Disponible |
| Cumplimiento de la comunicación                | Detecta la infracción de código de conducta repetida con el tiempo                         | Disponible |
| Cumplimiento de la comunicación                | Escala para la investigación de eDiscovery avanzada                         | Disponible |
| Cumplimiento de la comunicación                | Entrega de la administración de riesgos insider                         | En el trabajo pendiente de ingeniería |
| Cumplimiento de la comunicación                | Aprovechar el reconocimiento óptico de caracteres para extraer y evaluar mensajes                         | En desarrollo |
| Cumplimiento de la comunicación                | Nueva vista simplificada para empresas muy pequeñas                         | En desarrollo |
| Cumplimiento de la comunicación                | Comprobación del estado de la directiva y capacidad para pausar la directiva                         | En desarrollo |
| Cumplimiento de la comunicación                | Integración con la potencia automatizada                         | En desarrollo |
| Cumplimiento de la comunicación                | Compatibilidad con permisos más granulares                         | Disponible |
| Cumplimiento de la comunicación                | Admite siete idiomas para la amenaza, hostigamiento dirigido y clasificadores de profanaciones                         | En desarrollo |
| Cumplimiento de la comunicación                | Integración de Microsoft Teams                         | En el trabajo pendiente de ingeniería |
| Cumplimiento de la comunicación                | Contexto de conversación de Teams                         | En desarrollo |
| Cumplimiento de la comunicación                | Traducir contenido durante la investigación                         | En el trabajo pendiente de ingeniería |
| Caja de seguridad del cliente                | Caja de seguridad del cliente                         | Disponible |
| Barreras de información                | Barreras de la información                         | Disponible |
| Administración de riesgos de Insider             | Panel de casos                         | Disponible |
| Administración de riesgos de Insider             | Robo de datos por parte de los usuarios que salen                        | Disponible |
| Administración de riesgos de Insider             | Indicadores de dispositivo para la actividad en Windows 10 Build 1809 y versiones posteriores                        | En el trabajo pendiente de ingeniería |
| Administración de riesgos de Insider             | Escala para la investigación de eDiscovery avanzada                        | Disponible |
| Administración de riesgos de Insider             | Exportar alertas                        | En el trabajo pendiente de ingeniería |
| Administración de riesgos de Insider             | Pérdidas de datos generales                                | Disponible              |
| Administración de riesgos de Insider             | Indicadores de infracción de directivas de seguridad                   | En el trabajo pendiente de ingeniería              |
| Administración de riesgos de Insider             | Indicadores de alertas de Punto de conexión de Microsoft Defender      | En el trabajo pendiente de ingeniería              |
| Administración de riesgos de Insider             | Explorador de actividades de administración de riesgos de Insider      | En desarrollo              |
| Administración de riesgos de Insider             | Explorador de contenido de administración de riesgos de Insider      | En desarrollo              |
| Administración de riesgos de Insider             | Investigar alertas de administración de riesgos de insider      | Disponible              |
| Administración de riesgos de Insider             | Plantillas de aviso      | Disponible              |
| Administración de riesgos de Insider             | Indicadores de Office para Teams, sitios de SharePoint, mensajería de correo electrónico      | Disponible              |
| Administración de riesgos de Insider             | Personalización de directivas      | En el trabajo pendiente de ingeniería              |
| Administración de riesgos de Insider             | Plantillas de directiva para pérdidas de datos de usuarios inconformes      | En el trabajo pendiente de ingeniería              |
| Administración de riesgos de Insider             | Plantillas de directiva para pérdidas de datos por usuarios prioritarios | En el trabajo pendiente de ingeniería |
| Administración de riesgos de Insider             | Plantillas de directiva para infracciones de directivas de seguridad general | En el trabajo pendiente de ingeniería |
| Administración de riesgos de Insider             | Plantillas de directiva para infracciones de directivas de seguridad por parte de usuarios prioritarios, usuarios que salen, usuarios inconformes | En el trabajo pendiente de ingeniería |
| Administración de riesgos de Insider             | Grupos de usuarios prioritarios | En el trabajo pendiente de ingeniería |
| Administración de riesgos de Insider             | Integración con la potencia automatizada | En desarrollo |
| Administración de riesgos de Insider             | Integración de Microsoft Teams | En el trabajo pendiente de ingeniería |
| Privileged Access Management        | Administración del acceso con privilegios | En el trabajo pendiente de ingeniería |
| **Detectar & responder**                  | EDiscovery principal: Auditoría                            | Disponible              |
| eDiscovery                              | EDiscovery principal: administración de casos                                 | Disponible              |
| eDiscovery                              | EDiscovery principal: Exportar                                          | Disponible              |
| eDiscovery                              | Exhibición de documentos electrónicos principal: conservación local                           | Disponible              |
| eDiscovery                              | EDiscovery principal: exportación nativa                                  | Disponible              |
| eDiscovery                              | EDiscovery principal: descifrado de RMS                                   | Disponible              |
| eDiscovery                              | EDiscovery principal: Búsqueda                                   | Disponible              |
| eDiscovery                              | EDiscovery principal: Microsoft Compliance Center expandió la compatibilidad para buscar y exportar elementos en La papelera de reciclaje de SharePoint y OneDrive para la Empresa                                        | Disponible              |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: procesamiento avanzado                             | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: asignación de custodia a carga de trabajo                             | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: comunicaciones de custodia                             | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: Panel                                 | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: compatibilidad con caracteres de doble byte (chino, japonés, coreano)                                 | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: subprocesos de correo electrónico                   | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: Exportar (descargar, exportar, agregar a otro conjunto de vistas)                                          | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: filtrado                               | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: optimizaciones de retención                      | En desarrollo |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: retención legal de mensajes de canales privados de Teams            | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: Microsoft Compliance Center expandió la compatibilidad para buscar y exportar elementos en SharePoint y la Papelera de reciclaje de OneDrive para la Empresa            | En desarrollo |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: identificación casi duplicada                               | Disponible |
| eDiscovery                              | EDiscovery avanzado: nuevo módulo de codificación predictiva                   | En el trabajo pendiente de ingeniería |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: orígenes de datos no custodiados                                  | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: ingesta que no es de Office 365                                    | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: codificación predictiva                                       | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: exportación procesada con archivo de carga                   | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: redacciones                        | Disponible |
| eDiscovery                              | EDiscovery avanzado: conjuntos de revisión                                     | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: revisar datos (datos de consulta, etiquetas inteligentes, panel) y anotación (redact)                             | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: informe de términos de búsqueda                        | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: corrección de errores de elemento único                              | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: compatibilidad con la exportación de PST                              | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: compatibilidad con contenido vinculado de OneDrive y SharePoint Online (datos adjuntos modernos)                              | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: admitir las reacciones de Teams                      | En el trabajo pendiente de ingeniería |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: etiquetado                              | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: informes de inquilinos                              | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: temas                              | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: visores                              | Disponible |
| eDiscovery                              | Exhibición de documentos electrónicos avanzada: Exhibición de documentos electrónicos avanzada de Yammer en el Centro de cumplimiento de Microsoft                              | Disponible |
| Auditoría                                   | Auditoría básica                              | Disponible |
| Auditoría                                   | Auditoría avanzada: acceso a eventos cruciales (por ejemplo, *MailItemsAccessed*)                              | Disponible |
| Auditoría                                   | Auditoría avanzada: mayor ancho de banda para la API de actividad de administración                   | Disponible |
| Auditoría                                   | Auditoría avanzada: retención legal para mensajes de canales privados de Teams                   | Disponible |
| Auditoría                                   | Auditoría avanzada: retención de registros (1 año)                               | Disponible |
| Auditoría                                   | Auditoría avanzada: retención a largo plazo en registros de auditoría (10 años)              | En desarrollo |
| Auditoría                                   | Auditoría avanzada: eventos de reenvío de correo y envío de correo                               | Disponible |
| Auditoría                                   | Auditoría avanzada: Centro de seguridad y cumplimiento de Microsoft 365                    | Disponible |
| Auditoría                                   | Auditoría avanzada: eventos de términos de búsqueda en Exchange Online y SharePoint Online                              | En el trabajo pendiente de ingeniería |
|    **Administración de cumplimiento**            | Centro de seguridad y cumplimiento de Microsoft 365                              | Disponible |
|                                         | Administrador de cumplimiento                              | Disponible |
|                                         | Compatibilidad con caracteres de doble byte                              | Disponible |
|                                         | Microsoft Cloud App Security                              | En el trabajo pendiente de ingeniería |
|    **Ecosistema**            | API de Graph para eDiscovery avanzada                              | En desarrollo |
|                                         | API de Graph para exportar datos de Teams                              | En el trabajo pendiente de ingeniería |
|                                         | Conectores de datos de origen                              | En el trabajo pendiente de ingeniería |
|                                         | Conectores de datos de terceros                              | En desarrollo |




<sup>1</sup> El estado identificado está sujeto a cambios a medida que se reevaluan los planes y las prioridades del proyecto.<br/>

**Punto de decisión:** *decida si las características de cumplimiento satisfacen* las necesidades de su organización.
