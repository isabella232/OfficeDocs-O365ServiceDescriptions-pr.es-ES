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
ms.openlocfilehash: 44dd4a10560fb5bd0d1c0f36f3290b621798d03d390573d789b99d62047bad1e
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663273"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>Planeación del Microsoft 365 cumplimiento normativo GCC

Esta guía está para profesionales de TI que impulsan implementaciones de Office 365 en entidades gubernamentales federales, estatales, locales, tribales o territoriales de Estados Unidos u otras entidades que administran datos que están sujetos a normativas y requisitos gubernamentales, donde el uso de Microsoft 365 Government - GCC es adecuado para cumplir estos requisitos.

> [!NOTE]
> Si su organización ya ha cumplido los requisitos de elegibilidad de Microsoft 365 Government- GCC y ha solicitado y aceptado en el programa, puede omitir los pasos 1 y 2 e ir directamente al paso 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>Paso 1. Determinar si su organización necesita Microsoft 365 gobierno: GCC y cumple los requisitos de elegibilidad

El entorno Microsoft 365 Government - GCC cumple con los requisitos gubernamentales de los Estados Unidos para los servicios en la nube, incluidos FedRAMP Moderate, y los requisitos para la justicia penal y los sistemas de información fiscal federal (tipos de datos CJI y FTI).

Además de disfrutar de las características y capacidades de Office 365, las organizaciones se benefician de las siguientes características que son únicas para Microsoft 365 Government- GCC:

- El contenido de cliente de su organización se separa lógicamente del contenido del cliente en los servicios Office 365 comerciales de Microsoft.

- El contenido del cliente de la organización se almacena dentro de los Estados Unidos.

- El acceso al contenido del cliente de la organización está restringido a personal específico de Microsoft.

- Microsoft 365 Gobierno: GCC cumple con las certificaciones y acreditaciones necesarias para los clientes del sector público de Estados Unidos.

Puede encontrar más información sobre la oferta Microsoft 365 Government - GCC para los clientes del gobierno de estados unidos en [Office 365 Administración Pública planes,](https://products.office.com/government/compare-office-365-government-plans)incluidos los requisitos de elegibilidad.

La [Office 365 de servicio del](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) Gobierno de ESTADOS UNIDOS describe las ventajas de la plataforma, que se centra en cumplir los requisitos de cumplimiento dentro de los Estados Unidos.

> [!TIP]
> Es posible que desee transferir las tablas de información de la descripción del servicio a un libro de Excel y agregar dos columnas: Relevante para mi organización **Y/N** y Cumple las necesidades de mi organización **Y/N**. A continuación, puede revisar esta lista con sus compañeros para confirmar que este servicio satisface las necesidades de su organización.

> [!NOTE]
> Microsoft 365 Gobierno: GCC solo está disponible en Los Estados Unidos. Los clientes que no son del Gobierno de Estados Unidos pueden elegir entre una serie [de Office 365 Administración Pública planes](https://products.office.com/government/compare-office-365-government-plans).

**Puntos de decisión**: <br/>
- *Decida si Microsoft 365 Gobierno: GCC es adecuado para su organización.*
- *Confirme que su organización cumple los requisitos de elegibilidad.*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>Paso 2. Aplicar para Microsoft 365 Government - GCC

Después de haber decidido que este servicio es adecuado para su organización, inicie el proceso de [solicitud de este servicio](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>Paso 3. Comprender Microsoft 365 gobierno: GCC configuración de seguridad predeterminada

Se recomienda que se tome tiempo para revisar detenidamente la configuración de seguridad y administración antes de modificarlas y tener en cuenta el impacto en el cumplimiento antes de realizar cualquier cambio en la configuración de seguridad predeterminada.

**Punto de** decisión: decida si modificará alguna de las opciones predeterminadas de *Microsoft 365 Government:* GCC configuración de seguridad, resolviendo primero para comprender el impacto de los cambios que pueda realizar.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>Paso 4. Comprender qué funcionalidades actualmente no están disponibles o deshabilitadas de forma predeterminada en Microsoft 365 Government – GCC<sup>1</sup>

Para satisfacer los requisitos de nuestros clientes en la nube gubernamentales, existen algunas diferencias entre Microsoft 365 Administración pública - GCC y planes empresariales. Consulte la tabla siguiente para ver qué características están disponibles. Vea [aquí](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) las últimas actualizaciones de productos de cumplimiento publicadas en Microsoft 365 guía.<br><br>

| Área | Característica | GCC Estado |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Protección de la información**              | Cliente y escáner de etiquetado unificados         | Disponible              |
|                                         | Coincidencia exacta de datos          | Disponible              |
| Etiquetado de confidencialidad                    | Clasificación y etiquetado automáticos para Exchange Online, SharePoint Online y OneDrive                      | Disponible         |
| Etiquetado de confidencialidad                    | Clasificación y etiquetado automáticos para Aplicación de Office (Word, Excel, PowerPoint, Outlook) en plataformas (web, Android, iOS, Windows y Mac) |  Disponible              |
| Etiquetado de confidencialidad                    | Clasificación y etiquetado automáticos para Office clientes (móvil)                                       | En el trabajo pendiente de ingeniería              |
| Etiquetado de confidencialidad                    | Clasificación y etiquetado automáticos para Teams, Microsoft 365 grupos, SharePoint sitios                            | Disponible |
| Análisis                               | Análisis de clasificación de datos: Información general y Explorador de contenido                            | Disponible |
| Análisis                               | Análisis: clasificadores de aprendizaje automático con etiquetado automático en el lado del servicio                           | En el trabajo pendiente de ingeniería  |
| Análisis                               | Análisis: clasificadores de aprendizaje automático con etiquetado automático en Office aplicaciones/cliente                           | Implementando |
| Cifrado                              | Base Cifrado de mensajes de Office 365 (E3)                            | Disponible              |
| Cifrado                              | Advanced Cifrado de mensajes de Office 365 (E5)  | Disponible              |
| Cifrado                              | Clave del cliente de Office 365    | Disponible |
| Cifrado                              | Clave de cliente: cifrado de datos en reposo para Microsoft 365    | Implementando |
| Cifrado                              | Bring Your Own Key (BYOK) para el ciclo de vida de aprovisionamiento de claves administradas por el cliente                            | Disponible |
| Cifrado                              | Cifrado de claves doble                           | Disponible |
| Cifrado                              | Exchange Online cifrado de servicio con claves administradas de Microsoft         | Disponible |
| Prevención de pérdida de datos                    | Prevención de pérdida de datos (DLP) para archivos y correo electrónico         | Disponible |
| Prevención de pérdida de datos                    | DLP para conversaciones Teams chat y canal         | Disponible |
| Prevención de pérdida de datos                    | Extremo DLP | Implementando |
| Prevención de pérdida de datos                    | Panel de alertas | En desarrollo |
| Prevención de pérdida de datos                    | Página Información general | En desarrollo |
| **Gobierno de información** | Ámbitos adaptables para directivas de retención y etiquetado                 | En el trabajo pendiente de ingeniería              |
| Información de gobierno                 | Archivado de correo electrónico          | Disponible              |
| Información de gobierno                 | Etiquetas de retención predeterminadas SharePoint, OneDrive para la Empresa bibliotecas, carpetas y conjuntos de documentos; Exchange bandejas de entrada; y Office 365 grupos          | Disponible              |
| Información de gobierno                 | Importar PST                      | Disponible              |
| Información de gobierno                 | Etiquetas de retención manual sin registro            | Disponible |
| Información de gobierno                 | Bloqueo de conservación            | Disponible |
| Información de gobierno                 | Directivas de retención para toda la organización; ubicaciones o usuarios específicos; automáticamente en función de una condición específica (por ejemplo, palabras clave o información confidencial); y en función de un evento                                       | Disponible              |
| Información de gobierno                 | Directivas de retención para Teams                            | Disponible |
| Información de gobierno                 | Directivas de retención para Teams de reuniones                            | En desarrollo |
| Información de gobierno                 | Directivas de retención para Teams canales privados                            | En el trabajo pendiente de ingeniería |
| Información de gobierno                 | Directivas de retención para Teams canales compartidos                            | En el trabajo pendiente de ingeniería |
| Información de gobierno                 | Directivas de retención con clasificadores capacitados                            | En el trabajo pendiente de ingeniería |
| Información de gobierno                 | Directivas de retención para Yammer                            | En el trabajo pendiente de ingeniería |
| Administración de registros                     | Capacidad para eliminar una etiqueta de registro                           | En desarrollo              |
| Administración de registros                     | Aplicar una etiqueta de registro manualmente                            | Disponible              |
| Administración de registros                     | Aplicar etiquetas de registro predeterminadas para SharePoint, OneDrive para la Empresa bibliotecas, carpetas y conjuntos de documentos; y Office 365 grupos                              | Disponible              |
| Administración de registros                     | Aplicar directivas de registro automáticamente en función de condiciones específicas (por ejemplo, palabras clave o información confidencial); y en función de un evento                            | Disponible              |
| Administración de registros                     | Aplicar directivas de registro automáticamente con clasificadores que se pueden entrenar  | En desarrollo              |
| Administración de registros                     | Revisión para eliminación  | Disponible              |
| Administración de registros                     | Administrador del plan de archivos    | Disponible |
| Administración de registros                     | Revisión de disposición de varias fases    | En el trabajo pendiente de ingeniería |
| Administración de registros                     | Outlook cliente de administración de registros    | En el trabajo pendiente de ingeniería |
| Administración de registros                     | Power Automate Flow al final del período de retención    | En el trabajo pendiente de ingeniería |
| Administración de registros                     | Conservación y etiquetado automático de datos adjuntos en la nube    | En el trabajo pendiente de ingeniería |
| Administración de registros                     | Prueba de eliminación                            | Disponible |
| Administración de registros                     | Control de versiones de registros                            | Disponible |
| Administración de registros                     | Registros normativos                         | Disponible |
| Administración de registros                     | Usar SharePoint Syntex clasificación de registros para aplicar etiquetas de registro | En el trabajo pendiente de ingeniería |
| **Administración de riesgos de Insider**             | Caja de seguridad del cliente                                | Disponible            |
| Cumplimiento de la comunicación                | Capacidad para omitir la firma de correo electrónico o la declinación de responsabilidades                         | En desarrollo |
| Cumplimiento de la comunicación                | Capacidad para establecer un período de retención para una directiva de cumplimiento de comunicaciones                         | En desarrollo |
| Cumplimiento de la comunicación                | Obtener acceso a alertas; plantillas de aviso; panel de directivas de comunicación                         | Disponible |
| Cumplimiento de la comunicación                | Analizar Teams de chat de usuarios con buzón local                         | Disponible |
| Cumplimiento de la comunicación                | Supervisar automáticamente todos los Teams de los que un usuario es miembro                         | Disponible |
| Cumplimiento de la comunicación                | Plantilla de conflicto de intereses                         | Disponible |
| Cumplimiento de la comunicación                | Crear directivas de cliente, 3 preconfiguradas                         | Disponible |
| Cumplimiento de la comunicación                | Detectar contenido para adultos                         | Disponible |
| Cumplimiento de la comunicación                | Detecta la infracción de código de conducta repetida con el tiempo                         | Disponible |
| Cumplimiento de la comunicación                | Escala para investigación para Advanced eDiscovery                         | Disponible |
| Cumplimiento de la comunicación                | Entrega de la administración de riesgos insider                         | En el trabajo pendiente de ingeniería |
| Cumplimiento de la comunicación                | Aprovechar el reconocimiento óptico de caracteres para extraer y evaluar mensajes                         | En desarrollo |
| Cumplimiento de la comunicación                | Nueva vista simplificada para empresas muy pequeñas                         | En desarrollo |
| Cumplimiento de la comunicación                | Comprobación del estado de la directiva y capacidad para pausar la directiva                         | En desarrollo |
| Cumplimiento de la comunicación                | Integración con la potencia automatizada                         | En desarrollo |
| Cumplimiento de la comunicación                | Compatibilidad con permisos más granulares                         | Disponible |
| Cumplimiento de la comunicación                | Admite siete idiomas para la amenaza, hostigamiento dirigido y clasificadores de profanaciones                         | En desarrollo |
| Cumplimiento de la comunicación                | Microsoft Teams integración                         | En el trabajo pendiente de ingeniería |
| Cumplimiento de la comunicación                | Teams contexto de conversación                         | En desarrollo |
| Cumplimiento de la comunicación                | Traducir contenido durante la investigación                         | En el trabajo pendiente de ingeniería |
| Caja de seguridad del cliente                | Caja de seguridad del cliente                         | Disponible |
| Barreras de información                | Barreras de información                         | Disponible |
| Administración de riesgos de Insider             | Panel de casos                         | Disponible |
| Administración de riesgos de Insider             | Robo de datos por parte de los usuarios que abandonan la organización                        | Disponible |
| Administración de riesgos de Insider             | Indicadores de dispositivos para la actividad Windows 10 compilación 1809 y posterior                        | En el trabajo pendiente de ingeniería |
| Administración de riesgos de Insider             | Escala para investigación para Advanced eDiscovery                        | Disponible |
| Administración de riesgos de Insider             | Exportar alertas                        | En el trabajo pendiente de ingeniería |
| Administración de riesgos de Insider             | Filtraciones de datos generales                                | Disponible              |
| Administración de riesgos de Insider             | Indicadores de infracción de directivas de seguridad                   | En el trabajo pendiente de ingeniería              |
| Administración de riesgos de Insider             | Indicadores de alertas de Punto de conexión de Microsoft Defender      | En el trabajo pendiente de ingeniería              |
| Administración de riesgos de Insider             | Explorador de actividades de administración de riesgos de Insider      | En desarrollo              |
| Administración de riesgos de Insider             | Explorador de contenido de administración de riesgos de Insider      | En desarrollo              |
| Administración de riesgos de Insider             | Investigar alertas de administración de riesgos de insider      | Disponible              |
| Administración de riesgos de Insider             | Plantillas de aviso      | Disponible              |
| Administración de riesgos de Insider             | Office indicadores de Teams, SharePoint web, mensajería de correo electrónico      | Disponible              |
| Administración de riesgos de Insider             | Personalización de directivas      | En el trabajo pendiente de ingeniería              |
| Administración de riesgos de Insider             | Plantillas de directiva para pérdidas de datos de usuarios inconformes      | En el trabajo pendiente de ingeniería              |
| Administración de riesgos de Insider             | Plantillas de directiva para pérdidas de datos por usuarios prioritarios | En el trabajo pendiente de ingeniería |
| Administración de riesgos de Insider             | Plantillas de directiva para infracciones de directivas de seguridad general | En el trabajo pendiente de ingeniería |
| Administración de riesgos de Insider             | Plantillas de directiva para infracciones de directivas de seguridad por parte de usuarios prioritarios, usuarios que salen, usuarios inconformes | En el trabajo pendiente de ingeniería |
| Administración de riesgos de Insider             | Grupos de usuarios prioritarios | En el trabajo pendiente de ingeniería |
| Administración de riesgos de Insider             | Integración con la potencia automatizada | En desarrollo |
| Administración de riesgos de Insider             | Microsoft Teams integración | En el trabajo pendiente de ingeniería |
| Privileged Access Management        | Administración del acceso con privilegios | En el trabajo pendiente de ingeniería |
| **Detectar & responder**                  | EDiscovery principal: Auditoría                            | Disponible              |
| eDiscovery                              | EDiscovery principal: administración de casos                                 | Disponible              |
| eDiscovery                              | EDiscovery principal: Exportar                                          | Disponible              |
| eDiscovery                              | Exhibición de documentos electrónicos principal: conservación local                           | Disponible              |
| eDiscovery                              | EDiscovery principal: exportación nativa                                  | Disponible              |
| eDiscovery                              | EDiscovery principal: descifrado de RMS                                   | Disponible              |
| eDiscovery                              | EDiscovery principal: Búsqueda                                   | Disponible              |
| eDiscovery                              | EDiscovery principal: Microsoft Compliance Center expandió la compatibilidad para buscar y exportar elementos en SharePoint y OneDrive para la Empresa papelera de reciclaje                                        | Disponible              |
| eDiscovery                              | Advanced eDiscovery: procesamiento avanzado                             | Disponible |
| eDiscovery                              | Advanced eDiscovery: asignación de custodia a carga de trabajo                             | Disponible |
| eDiscovery                              | Advanced eDiscovery: comunicaciones de custodia                             | Disponible |
| eDiscovery                              | Advanced eDiscovery: Panel                                 | Disponible |
| eDiscovery                              | Advanced eDiscovery: Compatibilidad con caracteres de doble byte (chino, japonés, coreano)                                 | Disponible |
| eDiscovery                              | Advanced eDiscovery: Subprocesos de correo electrónico                   | Disponible |
| eDiscovery                              | Advanced eDiscovery: Exportar (descargar, exportar, agregar a otro conjunto de vistas)                                          | Disponible |
| eDiscovery                              | Advanced eDiscovery: Filtrado                               | Disponible |
| eDiscovery                              | Advanced eDiscovery: optimizaciones de retención                      | En desarrollo |
| eDiscovery                              | Advanced eDiscovery: retención legal de mensajes Teams canales privados            | Disponible |
| eDiscovery                              | Advanced eDiscovery: Microsoft Compliance Center expandió la compatibilidad para buscar y exportar elementos en SharePoint y OneDrive para la Empresa papelera de reciclaje            | En desarrollo |
| eDiscovery                              | Advanced eDiscovery: Identificación casi duplicada                               | Disponible |
| eDiscovery                              | Advanced eDiscovery: Nuevo módulo de codificación predictiva                   | En el trabajo pendiente de ingeniería |
| eDiscovery                              | Advanced eDiscovery: orígenes de datos no custodiados                                  | Disponible |
| eDiscovery                              | Advanced eDiscovery: ingesta sin Office 365 no                                    | Disponible |
| eDiscovery                              | Advanced eDiscovery: codificación predictiva                                       | Disponible |
| eDiscovery                              | Advanced eDiscovery: Exportación procesada con archivo de carga                   | Disponible |
| eDiscovery                              | Advanced eDiscovery: Redacciones                        | Disponible |
| eDiscovery                              | Advanced eDiscovery: conjuntos de revisión                                     | Disponible |
| eDiscovery                              | Advanced eDiscovery: Revisar datos (datos de consulta, etiquetas inteligentes, panel) y anotación (redact)                             | Disponible |
| eDiscovery                              | Advanced eDiscovery: Informe de términos de búsqueda                        | Disponible |
| eDiscovery                              | Advanced eDiscovery: corrección de errores de elemento único                              | Disponible |
| eDiscovery                              | Advanced eDiscovery: Compatibilidad con la exportación de PST                              | Disponible |
| eDiscovery                              | Advanced eDiscovery: admitir contenido vinculado de OneDrive y SharePoint Online (datos adjuntos modernos)                              | Disponible |
| eDiscovery                              | Advanced eDiscovery: admitir Teams respuestas                      | En el trabajo pendiente de ingeniería |
| eDiscovery                              | Advanced eDiscovery: Etiquetado                              | Disponible |
| eDiscovery                              | Advanced eDiscovery: informes de inquilinos                              | Disponible |
| eDiscovery                              | Advanced eDiscovery: Temas                              | Disponible |
| eDiscovery                              | Advanced eDiscovery: Visores                              | Disponible |
| eDiscovery                              | Advanced eDiscovery: Yammer Advanced eDiscovery en el Centro de cumplimiento de Microsoft                              | Disponible |
| Auditoría                                   | Auditoría básica                              | Disponible |
| Auditoría                                   | Auditoría avanzada: acceso a eventos cruciales (por ejemplo, *MailItemsAccessed*)                              | Disponible |
| Auditoría                                   | Auditoría avanzada: mayor ancho de banda para la API de actividad de administración                   | Disponible |
| Auditoría                                   | Auditoría avanzada: retención legal para Teams mensajes de canales privados                   | Disponible |
| Auditoría                                   | Auditoría avanzada: retención de registros (1 año)                               | Disponible |
| Auditoría                                   | Auditoría avanzada: retención a largo plazo en registros de auditoría (10 años)              | En desarrollo |
| Auditoría                                   | Auditoría avanzada: eventos de reenvío de correo y envío de correo                               | Disponible |
| Auditoría                                   | Auditoría avanzada: centro Microsoft 365 seguridad y cumplimiento                    | Disponible |
| Auditoría                                   | Auditoría avanzada: eventos de término de búsqueda en Exchange Online y SharePoint Online                              | En el trabajo pendiente de ingeniería |
|    **Administración de cumplimiento**            | Microsoft 365 Centro de seguridad y cumplimiento                              | Disponible |
|                                         | Administrador de cumplimiento                              | Disponible |
|                                         | Compatibilidad con caracteres de doble byte                              | Disponible |
|                                         | Microsoft Cloud App Security                              | En el trabajo pendiente de ingeniería |
|    **Ecosistema**            | Graph API para Advanced eDiscovery                              | En desarrollo |
|                                         | Graph API para Teams exportar datos                              | En el trabajo pendiente de ingeniería |
|                                         | Conectores de datos de origen                              | En el trabajo pendiente de ingeniería |
|                                         | Conectores de datos de terceros                              | En desarrollo |




<sup>1</sup> El estado identificado está sujeto a cambios a medida que se reevaluan los planes y las prioridades del proyecto.<br/>

**Punto de decisión:** *decida si las características de cumplimiento satisfacen* las necesidades de su organización.
