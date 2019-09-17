---
title: Descripción del servicio de Protección contra amenazas avanzada de Office 365
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced Threat Protection (ATP) es un servicio de filtrado de correo electrónico basado en la nube que ayuda a proteger a su organización frente a virus y malware desconocidos proporcionando una protección de día cero eficaz e incluye características para proteger su Organización de vínculos perjudiciales en tiempo real. ATP tiene capacidades enriquecidas de informes y seguimiento de URL que proporcionan a los administradores información sobre el tipo de ataques que ocurren en la organización.
ms.openlocfilehash: 6ab6b9832496127f8ceba6d3383c20b68f2f6dbe
ms.sourcegitcommit: 00fdb4a016cfc4422f38a0f415214eaffe04e8b6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/16/2019
ms.locfileid: "36998472"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Descripción del servicio de Protección contra amenazas avanzada de Office 365

Microsoft Office 365 Advanced Threat Protection (ATP) es un servicio de filtrado de correo electrónico basado en la nube que ayuda a proteger a su organización frente a virus y malware desconocidos proporcionando una protección de día cero eficaz e incluye características para proteger su Organización de vínculos perjudiciales en tiempo real. ATP tiene capacidades enriquecidas de informes y seguimiento de URL que proporcionan a los administradores información sobre el tipo de ataques que ocurren en la organización.

Las siguientes son las principales formas en las que puede usar ATP para la protección de mensajes:

- En un escenario de solo filtrado de ATP de Office 365, ATP proporciona protección de correo electrónico basada en la nube para su entorno de Exchange Server local o cualquier otra solución de correo SMTP local.

- Office 365 ATP se puede habilitar para proteger buzones de Exchange Online hospedados en la nube. Para obtener más información sobre Exchange Online, vea [Descripción del servicio Exchange Online](exchange-online-service-description/exchange-online-service-description.md).

- En una implementación híbrida, ATP se puede configurar para proteger el entorno de mensajería y controlar el enrutamiento del correo cuando se tiene una mezcla de buzones locales y en la nube con Exchange Online Protection para el filtrado de correo electrónico entrante.

## <a name="office-365-advanced-threat-protection-atp-availability"></a>Disponibilidad de la protección contra amenazas avanzada (ATP) de Office 365

ATP se incluye en Office 365 Enterprise E5, Office 365 Education A5 y Microsoft 365 Business.

Puede agregar ATP en los siguientes planes de suscripción de Exchange y Office 365:

- Plan 1 de Exchange Online

- Plan 2 de Exchange Online

- Quiosco de Exchange Online

- Exchange Online Protection

- Office 365 Empresa Essentials

- Office 365 Empresa Premium

- Office 365 Enterprise E1

- Office 365 Enterprise E3

- Office 365 Enterprise F1

- Office 365 A1

- Office 365 A3

Para comprar la protección contra amenazas avanzada de Office 365, consulte [protección contra amenazas avanzada de office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Para comparar las características entre planes, consulte [comparar los planes de Office 365 para empresas](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) y [Descubra la solución empresarial de Microsoft 365 que más le conviene](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Novedades de la protección contra amenazas avanzada (ATP) de Office 365

Seguimos agregando nuevas características a Office 365 ATP. A continuación se muestra una lista de varias características nuevas, algunas de las cuales llaman para revisar y actualizar una directiva de ATP. Para obtener más información acerca de las nuevas características disponibles para ATP (o Microsoft 365 en general), visite el [plan de desarrollo de microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365).

|Actualizaciones de características|Elementos de acción|
|---------|---------|
|[Inteligencia sobre amenazas de Office 365](https://docs.microsoft.com/office365/securitycompliance/office-365-ti) Las capacidades de (TI) ahora son capacidades de investigación y respuesta de amenazas como parte del plan ATP 2. Se están implementando nuevas características, como la [investigación y la respuesta automatizadas](https://docs.microsoft.com/office365/securitycompliance/automated-investigation-response-office), y las mejoras en el [Explorador de amenazas](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance).<br/><br/>Si su organización no tiene ATP, o si había ATP pero no TI, ahora tiene varias opciones que debe tener en cuenta, con la disponibilidad del plan de ATP 1 y el plan de ATP 2. Para obtener más información, consulte [disponibilidad de características en los planes de protección contra amenazas avanzada (ATP)](#feature-availability-across-advanced-threat-protection-atp-plans) (en este artículo) y [planes y precios de la protección contra amenazas avanzada de Office 365](https://products.office.com/exchange/advance-threat-protection).|Revise la suscripción de su organización y, si es necesario, [compre o edite un complemento](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/buy-or-edit-an-add-on).|
|Cuando los usuarios usan Outlook o la aplicación Web de Outlook (OWA), los [vínculos seguros ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) representan las direcciones URL originales, no las direcciones URL reescritas. (Llamamos a esta representación de vínculos nativos).<br>Cuando la representación de vínculos nativos está disponible para su organización, esta característica funcionará en Outlook 365 (hacer clic y ejecutar), OWA y en Windows y Mac OS.|Ninguno|
|[Las páginas de advertencia de ATP de Office 365](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links-warning-pages) presentan una nueva combinación de colores, más detalles y la posibilidad de continuar a un sitio a pesar de determinadas advertencias y recomendaciones.|Ninguno|
|La protección de [vínculos seguros de ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) se extiende para aplicarse a las direcciones URL en Office para la web (Word para la web, Excel para el Web, PowerPoint para el Web y OneNote para la web) y Office 365 ProPlus en Mac.|[Revisar y editar las directivas de vínculos seguros de ATP](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies)|
|Las funciones de cuarentena del &amp; centro de seguridad y cumplimiento se amplían a [ATP para SharePoint Online, OneDrive para la empresa y Microsoft Teams](https://docs.microsoft.com/office365/SecurityCompliance/atp-for-spo-odb-and-teams).|[Revisar y editar las directivas de datos adjuntos seguros de ATP](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-attachments-policies)|
|La protección de [vínculos seguros de ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) se extiende para aplicarse al correo electrónico enviado entre personas dentro de una organización.|[Revisar y editar las directivas de vínculos seguros de ATP](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies)|
|La protección de [vínculos seguros de ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) se extiende para aplicarse a las direcciones URL en el correo electrónico, así como a las direcciones URL de los documentos de Office 365 ProPlus, como Word, Excel, PowerPoint y Visio en Windows, así como las aplicaciones de Office en dispositivos iOS y Android.|Asegurarse de que está usando la [autenticación moderna para Office](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016)|


## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Requisitos para la protección contra amenazas avanzada de Office 365 (ATP)

ATP puede usarse con cualquier agente de transferencia de correo SMTP, como Microsoft Exchange Server. Para obtener información sobre los sistemas operativos, los exploradores web y los idiomas compatibles con ATP, vea las secciones "Exploradores compatibles" e "Idiomas admitidos en EOP" en el [Centro de administración de Exchange en Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Disponibilidad de características en los planes de protección contra amenazas avanzada (ATP)

A continuación, se incluye cada característica. Cuando se menciona Exchange Online, por lo general se refiere a la familia de servicios de Office 365 Enterprise.

|**Característica**|**Plan ATP 1**<br>(anteriormente ATP independiente)|**Plan ATP 2**<br>(anteriormente, inteligencia de amenazas <br>independientemente| Office 365 Enterprise E5|
|:-----|:-----|:-----|:-----|
|*Configuración, protección y detección*|
|Datos adjuntos seguros|Sí|Sí|Sí|
|Vínculos seguros|Sí|Sí|Sí|
|Directivas contra la suplantación de identidad|Sí|Sí|Sí|
|ATP para SharePoint, OneDrive y Microsoft Teams|Sí|Sí|Sí|
|Datos adjuntos seguros en Microsoft Teams|Sí|Sí|Sí|
|Vínculos seguros en Microsoft Teams|No|No|No|
|Informes en tiempo real|Sí|Sí|Sí|
|*Automatización, investigación, corrección y educación*|
|Rastreadores de amenazas|No|Sí|Sí|
|Explorer (investigación de amenazas avanzada)|No|Sí|Sí|
|Investigación y respuesta automatizada|No|Sí|Sí|
|Simulador de ataque|No|Sí|Sí|

## <a name="advanced-threat-protection-atp-capabilities"></a>Capacidades de la protección contra amenazas avanzada (ATP)

### <a name="safe-attachments"></a>Datos adjuntos seguros

Los [datos adjuntos seguros de ATP](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments) protegen contra malware y virus desconocidos y proporcionan protección de día cero para proteger el sistema de mensajería. Todos los mensajes y datos adjuntos que no tienen una firma de virus/código dañino conocida se enrutan a un entorno especial donde ATP usa diversas técnicas de análisis y aprendizaje automático para detectar intentos malintencionados. Si no se detecta ninguna actividad sospechosa, se libera el mensaje para su entrega al buzón de correo.

> [!NOTE]
> El análisis de datos adjuntos seguros de ATP tiene lugar en la misma región en la que residen los datos de Office 365. Para obtener más información acerca de la geografía del centro de datos, consulte [¿dónde están los datos ubicados?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Vínculos seguros

La característica de [vínculos seguros de ATP](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links) protege de forma proactiva a los usuarios de direcciones URL malintencionadas en un mensaje o en un documento de Office. La protección permanece cada vez que se hace clic en el vínculo, ya que los vínculos dañinos se bloquean dinámicamente mientras que los vínculos seguros se pueden acceder.

Vínculos seguros está disponible para las direcciones URL en las siguientes aplicaciones:

- Office 365 ProPlus en Windows o Mac.

- Office para la web (Word para la web, Excel para el Web, PowerPoint para el Web y OneNote para la web).

- Word, Excel, PowerPoint y Visio en Windows, así como aplicaciones de Office en dispositivos iOS y Android.

> [!NOTE]
> Los usuarios deben tener una licencia<sup>\*</sup>para ATP, deben estar incluidos en las directivas de vínculos seguros de ATP y deben haber iniciado sesión en sus dispositivos para que la protección esté en su lugar.

<sup>\*</sup>Para las licencias de ATP de toda la organización (por ejemplo, ATP_ENTERPRISE_FACULTY), no es necesario asignar licencias ATP a usuarios individuales.

### <a name="anti-phishing-policies"></a>Directivas contra la suplantación de identidad

[Anti-phishing de ATP](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing) comprueba los mensajes entrantes en busca de indicadores de que un mensaje puede ser un intento de suplantación de identidad. Cuando los usuarios están cubiertos por las directivas de ATP (datos adjuntos seguros, vínculos seguros o antiphishing), los mensajes entrantes se evalúan en varios modelos de aprendizaje automático que analizan los mensajes y se realiza la acción apropiada, en función de las directivas configuradas.

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP para SharePoint, OneDrive y Microsoft Teams.

[ATP para SharePoint, OneDrive y Microsoft Teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams) ayuda a detectar y bloquear los archivos identificados como malintencionados en los sitios de grupo y las bibliotecas de documentos.

### <a name="real-time-reports"></a>Informes en tiempo real

Las capacidades de supervisión disponibles en el centro de seguridad & cumplimiento de Office 365 incluyen [informes en tiempo real y perspectivas](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp) que permiten a los administradores de seguridad y cumplimiento centrarse en problemas de alta prioridad, como ataques de seguridad o aumento actividad sospechosa. Además de resaltar las áreas problemáticas, los informes y la información inteligentes incluyen recomendaciones y vínculos para ver y explorar los datos, además de realizar acciones rápidas.

### <a name="threat-trackers"></a>Rastreadores de amenazas

Los [rastreadores de amenazas](https://docs.microsoft.com/office365/securitycompliance/threat-trackers) son widgets informativos y vistas que proporcionan a los usuarios autorizados una inteligencia sobre problemas de Cybersecurity que pueden afectar a su organización.

### <a name="explorer"></a>Explorer

El explorador (también conocido como explorador de amenazas) es un informe en tiempo real que permite a los usuarios autorizados identificar y analizar amenazas recientes. De forma predeterminada, este informe muestra los datos de los últimos 7 días; sin embargo, las vistas se pueden modificar para mostrar los datos de los últimos 30 días.

Para obtener más información sobre el explorador (en Office 365 Advanced Threat Protection Plan 2) y las detecciones en tiempo real (en Office 365 plan de protección contra amenazas avanzada 1), consulte [Threat Explorer (y detección en tiempo real)](https://docs.microsoft.com/office365/securitycompliance/threat-explorer).

### <a name="attack-simulator"></a>Simulador de ataque

El [simulador de ataques](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator) permite a los usuarios autorizados ejecutar escenarios de ataques realistas en su organización. Hay disponibles varios tipos de ataques, como un ataque de suplantación de identidad (Spear-phishing), un ataque rociado por contraseña y un ataque de contraseña de fuerza bruta.
