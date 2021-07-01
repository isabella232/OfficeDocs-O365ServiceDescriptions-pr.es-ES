---
title: Descripción del servicio Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: obtenga información sobre las características y los requisitos de Exchange Online Protection. Se incluye una lista de planes que proporcionan Exchange Online Protection, así como una comparación de características en esos planes.
ms.openlocfilehash: fbfbe39931e6037b358bb76c124937904a408783
ms.sourcegitcommit: 427dbb27426a12e8c5dba7d8b4cbaf2bedb3aaba
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/30/2021
ms.locfileid: "53222487"
---
# <a name="exchange-online-protection-service-description"></a>Descripción del servicio Exchange Online Protection

obtenga información sobre las características y los requisitos de Exchange Online Protection. Se incluye una lista de planes que proporcionan Exchange Online Protection, así como una comparación de características en esos planes.

Microsoft Exchange Online Protection (EOP) es un servicio de filtrado de correo electrónico basado en la nube que ayuda a proteger su organización contra correo no deseado y malware e incluye características para proteger su organización de infracciones de directivas de mensajería. EOP simplifica la administración de un entorno de mensajes y puede aliviar muchas de las cargas asociadas al mantenimiento del hardware y del software local.

En la siguiente lista se describen las formas principales de usar EOP para la protección de mensajería:

- **En un escenario independiente:** EOP proporciona protección de correo electrónico basada en la nube para su entorno de correo electrónico local (Exchange Server otras soluciones de correo electrónico SMTP locales).

- **Como parte de Microsoft Exchange Online:** de forma predeterminada, EOP protege Exchange Online buzones hospedados en la nube. Para obtener más información sobre Exchange Online, consulte [la Exchange Online descripción del servicio](../exchange-online-service-description/exchange-online-service-description.md).

- **En una implementación híbrida:** EOP se puede configurar para proteger el entorno de mensajería y controlar el enrutamiento de correo cuando se tiene una combinación de buzones locales y en la nube.

## <a name="available-plans"></a>Planes disponibles

En la tabla siguiente se muestran los planes que incluyen Exchange Online Protection para que pueda elegir la solución que mejor se adapte a las necesidades de su organización. Para obtener información detallada sobre el plan, [vea Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).

Para obtener información detallada del plan sobre las suscripciones que permiten a los usuarios Exchange Online Protection, consulte la tabla de comparación [de suscripciones completa](https://www.microsoft.com/microsoft-365/compare-microsoft-365-enterprise-plans).

### <a name="exchange-enterprise-cal-with-services-features"></a>Características de Exchange Enterprise CAL con servicios

Microsoft Exchange Enterprise CAL with Services proporciona las características de protección de correo electrónico de EOP y las siguientes características adicionales basadas en la nube:

- [Prevención de pérdida de datos](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [Creación de informes mediante servicios web](reporting-and-message-trace.md#reporting-using-web-services)

Para obtener más información sobre Exchange Enterprise licencias de CAL con servicios, [vea Exchange de licencias](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business).

Si ha Exchange Enterprise CAL con licencias de servicios y desea aprovisionar EOP, siga las instrucciones de Configurar el servicio [de EOP](/microsoft-365/security/office-365-security/set-up-your-eop-service). Los pasos de configuración son los mismos que para configurar EOP independiente.

> [!NOTE]
> Las nuevas características de Exchange Enterprise CAL con servicios se implementan al mismo tiempo que Exchange Online, en lugar de EOP independiente. Le avisamos que las programaciones de implementación para EOP independiente y Exchange Online/Exchange Enterprise CAL con servicios pueden ser ligeramente diferentes.

## <a name="requirements-for-exchange-online-protection-eop"></a>Requisitos de Online Protection (EOP)

EOP se puede usar con cualquier agente de transferencia de correo SMTP, como Microsoft Exchange Server. Para obtener información sobre los sistemas operativos, exploradores web e idiomas compatibles con EOP, vea las secciones "Exploradores compatibles" y "Idiomas admitidos" en el Centro de administración de Exchange en [Exchange Online Protection](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).

## <a name="limits"></a>Límites

Para ver los límites de EOP, [consulte Exchange Online Protection limits](exchange-online-protection-limits.md).

## <a name="feature-availability"></a>Disponibilidad de características

En la tabla siguiente se enumeran las características Exchange Online Protection principales disponibles en todos los planes. Se aplican ciertas advertencias. Vea las notas al pie para obtener más información. Esta tabla puede cambiar sin previo aviso. Para obtener la lista más actualizada y completa de características, consulta [Herramientas eficaces para admitir tu empresa.](https://products.office.com/business/compare-more-office-365-for-business-plans)

| Característica | EOP independiente | EOP en EE CAL con Servicios | Características de EOP en Exchange  Online |
|:-----|:-----|:-----|:-----|
|**Protection**||||
|Directivas antimalware (integradas y personalizadas)|Sí|Sí|Sí|
|Directivas contra correo no deseado entrantes (integradas y personalizadas)|Sí|Sí|Sí|
|Directivas contra correo no deseado salientes (integradas y personalizadas)|Sí|Sí|Sí|
|Filtrado de conexiones (lista de direcciones IP permitidos y lista de direcciones IP bloqueados)|Sí|Sí|Sí|
|Directivas contra suplantación de identidad (integradas y personalizadas)|Sí|Sí|Sí|
|Protección contra la suplantación (integrada y personalizada)|Sí|Sí|Sí|
|Purga automática de hora cero (ZAP) para mensajes de malware, correo no deseado y phishing<sup>entregados 10</sup>|No|No|Sí|
|Directivas de seguridad predefinidas|Sí|Sí|Sí|
|Analizador de configuración para directivas de protección|Sí|Sí|Sí|
|Lista de inquilinos permitidos/bloqueados|Sí|Sí|Sí|
|Bloquear listas para remitentes de mensajes|Sí|Sí|Sí|
|Permitir listas para remitentes de mensajes|Sí|Sí|Sí|
|Bloqueo perimetral|Sí|Sí|Sí|
|Bloqueo perimetral basado en directorios (DBEB) para destinatarios inexistentes|Sí|Sí|Sí|
|**Cuarentena y envíos**||||
|Envío de administrador<sup>10</sup>|No|No|Sí|
|Envío de usuario (buzón personalizado)<sup>10</sup>|No|No|Sí|
|Cuarentena de administradores|Sí|Sí|Sí|
|Cuarentena de usuarios finales|Sí|Sí|Sí|
|Complemento Mensaje de informe y Complemento de suplantación de identidad de informes para Outlook|Sí|Sí|Sí|
|**Flujo de correo**||||
|Reglas de flujo de correo (reglas de transporte)<sup>4</sup>|Sí|Sí<sup>6</sup>|Sí|
|Dominios aceptados<sup>3</sup> |Sí|Sí|Sí|
|Conectores|Sí|Sí|Sí|
|Filtrado mejorado para conectores (omitir descripción)|Sí|Sí|Sí|
|**Supervisión**||||
|Message trace|Sí|Sí|Sí|
|Informes de correo electrónico e seguridad en el Centro de administración de Microsoft 365|Sí<sup>7</sup>|Sí<sup>7,8</sup>|Sí<sup>8</sup>|
|Informes de seguridad en el centro Microsoft 365 seguridad|Sí<sup>7</sup>|Sí<sup>7,8</sup>|Sí<sup>8</sup>|
|Informes de correo electrónico en el EAC|Sí<sup>7</sup>|Sí<sup>7,8</sup>|Sí<sup>8</sup>|
|Registro de auditoría de administración<sup>5</sup>|Sí|Sí|Sí|
|**Users**||||
|Usuarios de correo y contactos de correo<sup>1</sup>|Sí|Sí|Sí|
|Buzones|No|No|Sí<sup>1a</sup>|
|Control de acceso basado en roles (RBAC)<sup>2</sup>|Sí|Sí|Sí|
|**Cumplimiento**||||
|Prevención de pérdida de datos para correo electrónico|No|Sí|Sí|
|Cifrado de mensajes de Office 365|No<sup>9</sup>|No<sup>9</sup>|Sí|
|**Administración**||||
|Centro de administración de Microsoft 365|Sí|Sí|Sí|
|Centro de administración de Exchange|Sí|Sí|Sí|
|Centro de seguridad de Microsoft 365|Sí|Sí|Sí|
|PowerShell Exchange Online Protection independiente|Sí|No|No|
|Exchange Online PowerShell|No|Sí|Sí|

<sup>1</sup> Puede crear, quitar y editar usuarios de correo y contactos de correo en el EAC. <br/>
<sup>1a</sup> Puede crear y quitar buzones en el Centro de administración de Microsoft 365. Puede editar buzones existentes en el EAC. <br/>
<sup>2</sup> En EOP independiente y EE CAL con Servicios, no hay roles de usuario final ni directivas de asignación de roles.<br/>
<sup>3</sup> Puede agregar y quitar dominios en el Centro de administración de Microsoft 365.  En el EAC, se configuran dominios como autoritativo o no autoritativo.<br/>
<sup>4</sup> Algunas condiciones de regla, excepciones y acciones no están disponibles en EOP independiente o EOP en EE CAL con Servicios. Estas diferencias se observan claramente en Exchange Online de regla de flujo de correo. <br/>
<sup>5 En</sup> EOP independiente y EE CAL con servicios:

- Los informes de auditoría de buzones no están disponibles.
- El informe de grupo de roles de administrador y el informe de registro de auditoría de administrador son los únicos informes de auditoría de administración en el EAC.
- Exportación del registro de auditoría disponible solo a través de PowerShell. <br/>

<sup>6 sugerencias</sup> de directiva DLP no están disponibles en EE CAL con Servicios. <br/>
<sup>7</sup> Los informes de EOP independiente y EE CAL con Servicios son un subconjunto de Exchange Online independientes (informes que tratan con buzones).<br/>
<sup>8 Incluye</sup> informes DLP. <br/>
<sup>9</sup> Puede comprar Azure Information Protection como una suscripción de complemento y usar OME si configura su entorno de correo electrónico local para enrutar el correo electrónico a y desde Internet a través de EOP. <br/>
<sup>10</sup> Esta característica requiere Exchange Online buzones de correo. <br/>

## <a name="learn-more"></a>Más información

Para obtener información técnica Exchange Online Protection, consulte los siguientes recursos:

La [Microsoft 365 guía básica es](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx) un buen recurso para encontrar información sobre las próximas nuevas características.

### <a name="licensing-terms"></a>Términos de licencia

Para obtener términos y condiciones de licencia para productos y servicios comprados a través de los programas de licencias por volumen comerciales de Microsoft, consulte el [sitio términos del producto](https://www.microsoft.com/licensing/terms/).

### <a name="messaging"></a>Mensajería 

Para realizar un seguimiento de los próximos cambios, incluidas las características nuevas y modificadas, el mantenimiento planeado u otros anuncios importantes, visite el Centro de mensajes. Para obtener más información, vea [Centro de mensajes](/microsoft-365/admin/manage/message-center).

### <a name="accessibility"></a>Accesibilidad

Microsoft sigue comprometido con la seguridad de sus datos y la [accesibilidad](https://www.microsoft.com/trust-center/compliance/accessibility) de nuestros servicios. Para obtener más información, vea [el Centro](https://www.microsoft.com/trust-center) de confianza de Microsoft y el Centro Office [accesibilidad](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d).
