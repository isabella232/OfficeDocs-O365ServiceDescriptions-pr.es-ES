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
description: Esta orientación es para profesionales de TI que están impulsando despliegues de Office 365 en entidades del Gobierno Federal de ee. UU. u otras entidades que manejan datos que están sujetos a regulaciones y requisitos gubernamentales, donde el uso de Microsoft 365 Gobierno – Departamento de Bienes DoD es apropiado para cumplir con estos requisitos.
ms.openlocfilehash: bc6d69c32db6801763e47984c0513da9c16ba0f8
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52546007"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Plan para las implementaciones del Centro de cumplimiento de Microsoft 365 - DoD

Esta orientación es para profesionales de TI que están impulsando despliegues de Office 365 en entidades del Gobierno Federal de ee. UU. u otras entidades que manejan datos que están sujetos a regulaciones y requisitos gubernamentales, donde el uso de Microsoft 365 Gobierno – Departamento de Bienes DoD es apropiado para cumplir con estos requisitos.

> [!NOTE]
> Si su organización ya ha cumplido con los requisitos de elegibilidad Microsoft 365 Gobierno – DoD y solicitó y fue aceptada en el programa, puede omitir los pasos 1 y 2 e ir directamente al paso 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>Paso 1. Determine si su organización necesita Microsoft 365 Gobierno - Departamento de Seguridad y cumple con los requisitos de elegibilidad

El entorno Microsoft 365 Gobierno - Departamento de Desarrollo cumple con los requisitos del Gobierno de los Estados Unidos para los servicios en la nube.

Además de disfrutar de las características y capacidades de Office 365, las organizaciones se benefician de las siguientes características que son únicas para Microsoft 365 Gobierno – Departamento de Departamento de Estado:

- El contenido del cliente de su organización se separa lógicamente del contenido del cliente en los servicios de Office 365 comerciales de Microsoft.
- El contenido del cliente de la organización se almacena dentro de los Estados Unidos.
- El acceso al contenido del cliente de la organización está restringido a personal específico de Microsoft.
- Microsoft 365 Gobierno - El Departamento de Salud cumple con las certificaciones y acreditaciones que se requieren para los clientes del sector público estadounidense.

Puede encontrar más información sobre la oferta de Microsoft 365 Gobierno - Departamento de Estado para clientes del gobierno de ee. UU. en [Office 365 Administración Pública planes,](https://products.office.com/government/compare-office-365-government-plans)incluidos los requisitos de elegibilidad.

La [descripción Office 365 del servicio del Gobierno de los Estados Unidos](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) describe los beneficios de la plataforma, que se centran en cumplir con los requisitos de cumplimiento dentro de los Estados Unidos.

> [!TIP]
> Es posible que desee transferir las tablas de información de la descripción del servicio a un libro de trabajo Excel y agregar dos columnas: **Relevante para mi organización Y/N** y Satisface las necesidades de mi organización **Y/N**. A continuación, puede revisar esta lista con sus colegas para confirmar que este servicio satisface las necesidades de su organización.

**Puntos de decisión**:<br/>
- *Decida si Microsoft 365 Gobierno - Departamento de Departamento de Estado es apropiado para su organización.*
- *Confirme que su organización cumple con los requisitos de elegibilidad.*

> [!NOTE]
> Microsoft 365 Gobierno - El Departamento de Estado sólo está disponible en los Estados Unidos. Los clientes gubernamentales no estadounidenses pueden elegir entre una serie de [planes de Office 365 Administración Pública.](https://products.office.com/government/compare-office-365-government-plans)

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>Paso 2. Solicitar gobierno Microsoft 365 - Departamento de Estado

Una vez decidido que este servicio es adecuado para su organización, inicie el proceso de solicitud de [este servicio.](https://products.office.com/government/eligibility-validation)

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>Paso 3. Comprender Microsoft 365 Gobierno - Configuración de seguridad predeterminada del Departamento de DoD

Le recomendamos que se tome tiempo para revisar cuidadosamente la configuración de administración y seguridad antes de modificarlas y considerar el impacto en el cumplimiento antes de realizar cualquier cambio en la configuración de seguridad predeterminada.

**Punto de decisión**: *Decida si modificará cualquiera de los ajustes de seguridad predeterminados Microsoft 365 Gobierno - DoD, resolviendo comprender primero el impacto de los cambios que pueda realizar.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>Paso 4. Comprender qué capacidades no están disponibles o deshabilitadas actualmente de forma predeterminada en Microsoft 365 Gobierno – Departamento de Bienes Unidos<sup>1</sup>

Para satisfacer los requisitos de nuestros clientes en la nube del gobierno, hay algunas diferencias entre Microsoft 365 Gobierno - Departamento de Salud y planes empresariales. Consulte la tabla siguiente para ver qué características están disponibles. Consulte [aquí](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) las últimas actualizaciones de productos de cumplimiento publicadas en Microsoft 365 hoja de ruta.<br><br>

| Área | Característica | Estado del Departamento de DoD |
|------|---------|------------|
| **Protección de la información** | Cliente de etiquetado unificado y escáner | Disponible |
| | Coincidencia exacta de datos | Disponible |
| | Clasificación y etiquetado automáticos para Exchange Online, SharePoint en línea y OneDrive para la Empresa | Implementando |
| | Clasificación automática y etiquetado para aplicaciones de Office (Word, Excel, PowerPoint, Outlook) en plataformas (web, Windows y Mac) | Disponible |
| | Clasificación automática y etiquetado para clientes Office - Móvil | En el atraso de ingeniería |
| | Clasificación y etiquetado automáticos para sitios de Teams, grupos de Microsoft 365 y SharePoint | Disponible |
| | Etiquetado obligatorio | Disponible |
| | Etiquetado manual de sensibilidad en aplicaciones Office (iOS, Android, Windows) | Disponible |
| | Configuración de etiquetas de sensibilidad para la protección de solo cifrado en mensajes de Outlook | Implementando |
| **Análisis** | Clasificación de datos: Visión general y Explorador de contenido | Implementando |
| | Análisis: Clasificadores de aprendizaje automático con etiquetado automático en el lado del servicio | En desarrollo |
| | Análisis: Clasificadores de aprendizaje automático con etiquetado automático en Office aplicaciones/lado cliente | Implementando |
| **Cifrado** | Cifrado de mensajes de Office 365 básico (E3) | Disponible |
| | Cifrado de mensajes de Office 365 avanzados (E5) | Disponible |
| | Traiga su propia clave (BYOK) para el ciclo de vida de aprovisionamiento de claves administrado por el cliente | Disponible |
| | Clave del cliente de Office 365 | Disponible |
| | Cifrado de claves doble | Disponible |
| **Prevención de pérdida de datos** | Prevención de pérdida de datos (DLP) para archivos y correo electrónico | Disponible |
| | DLP para conversaciones de chat y canal de Teams | Disponible |
| | DLP: Panel de alertas | Implementando |
| | Punto final DLP | En desarrollo |
| | DLP On-prem | En el atraso de ingeniería |
| | Página de información general de DLP | En desarrollo |
| **Gobierno de información** | Gobernanza de la información: Archivo de correo electrónico | Disponible |
| | Gobernanza de la información: Bloqueo de preservación | Disponible |
| | Gobernanza de la información: Importar PST | Disponible |
| | Gobernanza de la información: Aplique manualmente etiquetas de retención que no son de registro | Disponible |
| | Gobernanza de la información: aplique etiquetas de retención predeterminadas para bibliotecas, carpetas y conjuntos de documentos SharePoint/OneDrive para la Empresa; Exchange bandejas de entrada; y grupos de Office 365 | Disponible |
| | Gobernanza de la información: aplique una única etiqueta de retención predeterminada a toda la organización; ubicaciones o usuarios específicos; y automáticamente basado en condiciones específicas (por ejemplo, palabras clave o información confidencial) | Disponible |
| | Gobernanza de la información: aplique una etiqueta predeterminada para las bandejas de entrada de Exchange | Disponible |
| | Gobernanza de la información: Revisión de la disposición en varias etapas | En el atraso de ingeniería |
| | Gobernanza de la información: Políticas de retención con clasificadores formables | En desarrollo |
| | Gobernanza de la información: Políticas de retención para Teams chat | Implementando |
| | Gobernanza de la información: Políticas de retención para la grabación de reuniones de Teams | Disponible |
| | Gobernanza de la información: políticas de retención para Teams mensajes de canal privado | En el atraso de ingeniería |
| | Gobernanza de la información: las directivas de retención y etiquetado son ámbitos adaptables | En desarrollo |
| | Gestión de registros: aplique la etiqueta de registro manualmente | Disponible |
| | Administración de registros: aplique una etiqueta de registro predeterminada para SharePoint, bibliotecas de OneDrive para la Empresa, carpetas y conjuntos de documentos; y grupos Office 365 | Disponible |
| | Administración de registros: directivas de registros automáticas basadas en condiciones específicas (por ejemplo, palabras clave o información confidencial); y basado en un evento | Disponible |
| | Gestión de registros: Revisión de disposición | Disponible |
| | Gestión de registros: Administrador de planes de archivos | Disponible |
| | Gestión de registros: Prueba de eliminación | Disponible |
| | Gestión de registros: control de versiones de registros | Disponible |
| | Gestión de registros: Registros reglamentarios | Disponible |
| | Administración de registros: utilice SharePoint clasificación Syntex para aplicar etiquetas de registro | En el atraso de ingeniería |
| **Administración de riesgos internos** | Caja de seguridad del cliente | Disponible |
| | Gestión de riesgos internos: panel de casos, Explorador de contenido y plantillas de aviso | Implementando |
| | Gestión de riesgos internos: escala para la investigación de Advanced eDiscovery | Implementando |
| | Gestión de riesgos internos: Robo de datos por parte de usuarios que se van | Implementando |
| | Gestión de riesgos internos: fugas generales de datos | Implementando |
| | Gestión de riesgos internos: investigue las alertas de gestión de riesgos de información privilegiada | Implementando |
| | Gestión de riesgos internos: indicadores de Office para Teams, sitios de SharePoint, mensajería por correo electrónico | Implementando |
| | Explorador de actividad de gestión de riesgos internos | En el atraso de ingeniería |
| | Gestión de riesgos internos: indicadores de dispositivos para la actividad en Windows 10 Construir 1809 y superiores | En el atraso de ingeniería |
| | Gestión de riesgos internos: indicadores para microsoft defender para alertas de punto final | En el atraso de ingeniería |
| | Gestión de riesgos internos: indicadores para la violación de políticas de seguridad | En el atraso de ingeniería |
| | Gestión de riesgos internos: plantillas de políticas para filtraciones de datos por usuarios descontentos | En el atraso de ingeniería |
| | Gestión de riesgos internos: plantillas de políticas para fugas de datos por parte de usuarios prioritarios | En el atraso de ingeniería |
| | Gestión de riesgos internos: plantillas de políticas para violaciones de políticas de seguridad generales | En el atraso de ingeniería |
| | Gestión de riesgos internos: plantillas de directivas para infracciones de políticas de seguridad por parte de usuarios prioritarios, usuarios salientes, usuarios descontentos (versión preliminar) | En el atraso de ingeniería |
| | Gestión de riesgos internos: personalización de políticas | En el atraso de ingeniería |
| | Gestión de riesgos internos: alertas de exportación | En el atraso de ingeniería |
| | Gestión de riesgos internos: integración Microsoft Teams | En el atraso de ingeniería |
| | Gestión de riesgos internos: grupos de usuarios prioritarios | En el atraso de ingeniería |
| | Cumplimiento de la comunicación: Cree políticas de clientes, 3 preconfiguradas | Disponible |
| | Cumplimiento de la comunicación: compatibilidad con Teams, Exchange y quitar Teams mensaje | Disponible |
| | Cumplimiento de la comunicación: Alertas de acceso; plantillas de aviso; panel de directivas de comunicación | Disponible |
| | Cumplimiento de la comunicación: Escala para la investigación de Advanced eDiscovery | Disponible |
| | Cumplimiento de la comunicación: detecta la reincidencia del código de conducta con el tiempo | Disponible |
| | Cumplimiento de la comunicación: Soporte para permisos más granulares | Disponible |
| | Cumplimiento de la comunicación: Analizar Teams datos de chat de los usuarios con buzón en pre-prem | Disponible |
| | Cumplimiento de la comunicación: Plantilla de conflicto de intereses | Disponible |
| | Cumplimiento de la comunicación: Capacidad de ignorar la firma o el descargo de responsabilidad por correo electrónico | En desarrollo |
| | Cumplimiento de la comunicación: capacidad de establecer un período de retención para una directiva de cumplimiento de la comunicación | En el atraso de ingeniería |
| | Cumplimiento de la comunicación: Detectar contenido para adultos | En el atraso de ingeniería |
| | Cumplimiento de la comunicación: Entrega de gestión de riesgos de información privilegiada | En desarrollo |
| | Cumplimiento de la comunicación: comprobación de estado de la directiva y capacidad para pausar la política | En desarrollo |
| | Cumplimiento de la comunicación: Admite 7 idiomas para la amenaza, acoso dirigido y clasificadores de blasfemias | En desarrollo |
| | Cumplimiento de la comunicación: Traduzca contenido de salud durante la investigación | En desarrollo |
| | Barreras de información | Implementando |
| | Administración del acceso con privilegios | En el atraso de ingeniería |
| **Descubre & responder** | Exhibición electrónica principal: Conservación in situ | Disponible |
| | EDiscovery principal: Gestión de casos | Disponible |
| | EDiscovery principal: Buscar | Disponible |
| | Exhibición electrónica principal: Exportar | Disponible |
| | EDiscovery principal: descifrado RMS | Disponible |
| | EDiscovery principal: Exportación nativa | Disponible |
| | Exhibición electrónica principal: Auditoría | Disponible |
| | Exhibición electrónica principal: límites de cumplimiento para OneDrive para la Empresa | Implementando |
| | Advanced eDiscovery: Procesamiento avanzado | Disponible |
| | Advanced eDiscovery: Soporte de doble byte CJK para Advanced eDiscovery | Disponible |
| | Advanced eDiscovery: Custodio a mapeo de carga de trabajo | Disponible |
| | Advanced eDiscovery: Comunicaciones custodios | Disponible |
| | Advanced eDiscovery: Panel de control | Disponible |
| | Advanced eDiscovery: Enhebrado de correo electrónico | Disponible |
| | Advanced eDiscovery: Exportar (descargar, exportar, añadir a otro conjunto de revisión) | Disponible |
| | Advanced eDiscovery: Filtrado | Disponible |
| | Advanced eDiscovery: Identificación casi duplicada | Disponible |
| | Advanced eDiscovery: Codificación predictiva | Disponible |
| | Advanced eDiscovery: Exportación procesada con archivo de carga | Disponible |
| | Advanced eDiscovery: Redacciones | Disponible |
| | Advanced eDiscovery: Conjuntos de reseñas | Disponible |
| | Advanced eDiscovery: Revisar y anotar | Disponible |
| | Advanced eDiscovery: Informe de términos de búsqueda | Disponible |
| | Advanced eDiscovery: Soporte de contenido vinculado de OneDrive y SharePoint en línea (archivos adjuntos modernos) | Disponible |
| | Advanced eDiscovery: Etiquetado | Disponible |
| | Advanced eDiscovery: las reacciones Teams apoyan | Disponible |
| | Advanced eDiscovery: Informes de inquilinos | Disponible |
| | Advanced eDiscovery: Temas | Disponible |
| | Advanced eDiscovery: Espectadores | Disponible |
| | Advanced eDiscovery: Yammer Advanced eDiscovery en el Centro de cumplimiento de Microsoft | Disponible |
| | Advanced eDiscovery: Mantener optimizaciones | En desarrollo |
| | Advanced eDiscovery: Microsoft Compliance Center amplió la compatibilidad con la búsqueda y exportación de elementos en SharePoint, OneDrive para la Empresa, Papelera de reciclaje en Core y Advanced eDiscovery | En desarrollo |
| | Advanced eDiscovery: Retención legal para Teams mensajes de canales privados | En desarrollo |
| | Advanced eDiscovery: Nuevo módulo de codificación predictiva | En desarrollo |
| | Advanced eDiscovery: Ingestión no Office 365 | En el atraso de ingeniería |
| | Advanced eDiscovery: Informes de inquilinos | En desarrollo |
| | Auditoría básica | Disponible |
| | Auditoría avanzada: acceso a eventos cruciales (por ejemplo, mailitemsaccessed) | Disponible |
| | Auditoría avanzada: mayor ancho de banda a la API de actividad de administración | Disponible |
| | Auditoría avanzada: Retención de registros (1 año) | Disponible |
| | Auditoría avanzada: Eventos de envío de correo y envío por correo | Disponible |
| | Auditoría avanzada: disponibilidad del Centro de Seguridad y Cumplimiento | Disponible |
| | Auditoría avanzada: Retención a más largo plazo en los registros de auditoría (10 años) | En desarrollo |
| | Auditoría avanzada: eventos de términos de búsqueda en Exchange Online y SharePoint en línea | En el atraso de ingeniería |
| **Administración de cumplimiento** | Microsoft 365 Centro de Seguridad y Cumplimiento | Disponible |
| | Microsoft Cloud App Security | En desarrollo |
| | Administrador de cumplimiento | Disponible |
| | Soporte de personajes de doble byte | Disponible |
| **ecosistema** | Conectores de datos de primera parte: HR | Disponible |
| | Conectores de datos de primera parte: Instant Bloomberg, Bloomberg Mail, páginas de LinkedIn Business, ICE Chat | En el atraso de ingeniería |
| | Conectores de datos de terceros | En el atraso de ingeniería |
| | Graph API para Advanced eDiscovery | En desarrollo |
| | Graph API para datos de exportación de Teams | En el atraso de ingeniería |

<sup>1</sup> El estado identificado está sujeto a cambios a medida que se reevaluan los planes y prioridades del proyecto.<br/>

**Punto de decisión:** *decida si las características de cumplimiento satisfacen las necesidades de su organización.*
