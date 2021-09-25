---
title: Descripción del servicio de Archivado de Exchange Online
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-archiving-service-description
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 21ebd4bb-7d88-489f-a8aa-376e2536900c
description: Lea este artículo para obtener información sobre Microsoft Exchange Online archivado.
ms.openlocfilehash: 5030c265b309641a0d69e79c1aa8942c45360550
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/24/2021
ms.locfileid: "59670699"
---
# <a name="exchange-online-archiving-service-description"></a>Descripción del servicio de Archivado de Exchange Online

Microsoft Exchange Online El archivado es una Microsoft 365 de archivado de clase empresarial basada en la nube para las organizaciones que han implementado Microsoft Exchange Server 2019, Microsoft Exchange Server 2016, Microsoft Exchange Server 2013, Microsoft Exchange Server 2010 (SP2 y versiones posteriores) o suscribirse a determinados planes Exchange Online o Microsoft365. Archivado de Exchange Online ayuda a satisfacer las necesidades de estas organizaciones relacionadas con el archivo, el cumplimiento normativo, las disposiciones legales y la exhibición de documentos electrónicos, al mismo tiempo que simplifica la infraestructura local, reduce costes y facilita el trabajo de TI.
  
Como un servicio online de Microsoft, el Archivado de Exchange Online fue diseñado para ayudar a satisfacer la necesidad de una seguridad sólida, confiabilidad y productividad de los usuarios. Para obtener más información sobre Microsoft 365, incluidas las características comunes a todos los servicios en línea de Microsoft, vea Microsoft 365 [y Office 365 de servicio de la plataforma](../office-365-platform-service-description/office-365-platform-service-description.md).
  
Para comprar Archivado de Exchange Online, vea [Archivado de Exchange Online para el servidor](https://products.office.com/exchange/microsoft-exchange-online-archiving-email).
  
## <a name="available-plans"></a>Planes disponibles

Para obtener información detallada del plan sobre las suscripciones que permiten a los usuarios Archivado de Exchange Online, consulte la tabla de comparación [de suscripciones completa](https://go.microsoft.com/fwlink/?linkid=2139145).
  
> [!TIP]
> Puede exportar, guardar e imprimir páginas en las descripciones del servicio. Obtenga información sobre cómo [exportar resultados de búsqueda de contenido](/office365/securitycompliance/export-search-results). 
  
## <a name="exchange-online-archiving-plans"></a>Planes de Archivado de Exchange Online

Archivado de Exchange Online está disponible a través de los siguientes planes.<br><br>
  
| Plan | Descripción |
|:-----|:-----|
|**Archivado de Exchange Online para Exchange Server** <br/> |Archivo basado en la nube para usuarios con buzones principales en Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 o Exchange 2010 (SP2 o posterior). <br/> Si desea agregar un archivo basado en la nube a un buzón principal que está en un servidor de Exchange local, necesita configurar una implementación híbrida. Para obtener más información acerca de las implementaciones [híbridas, vea Exchange Server implementaciones híbridas](/exchange/exchange-hybrid). <br/> |
|**Archivado de Exchange Online para Exchange Server (a través de Enterprise CAL Suite)** <br/> |Archivo basado en la nube para usuarios con buzones principales en Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 o Exchange 2010 (SP2 o posterior). Para obtener más información, [vea Licencias de acceso de cliente y Licencias de administración.](https://www.microsoft.com/licensing/product-licensing/client-access-license) <br/> |
|**Archivado de Exchange Online para Exchange Online** <br/> | Archivo basado en la nube y retención local como complemento para los siguientes planes<sup>1,2,3</sup>:<br/> Plan 1 de Exchange Online <br/> Quiosco de Exchange Online <br/> Microsoft 365 Empresa Básico <br/> Microsoft 365 Empresa Estándar <br/> Microsoft 365 Empresa Premium <br/> Office 365 E1 <br/> Office 365 A1 <br/> Office 365 G1 <br/> Office 365 F3 <br/> Microsoft 365 F3<br/> <b>Nota:</b> Los siguientes planes ya incluyen archivado y no requieren Archivado de Exchange Online como complemento:<br/>Office 365 A3 <br/> Office 365 A5 <br/> Office 365 E3 <br/> Office 365 E5 <br/> Plan 2 de Exchange Online <br/>Microsoft 365 E3 <br/> Microsoft 365 E5 <br/> Microsoft 365 Cumplimiento F5 <br/> Para obtener información detallada sobre las capacidades de archivado de Exchange Online buzones de correo, vea [Archive features in Archivado de Exchange Online](./archive-features.md).|

<sup>1</sup> No se necesita una implementación híbrida para las organizaciones basadas exclusivamente en la nube en las que no hay buzones de correo ubicados en un servidor Exchange local. Sin embargo, si existen buzones locales, la implementación híbrida es necesaria.
<br/>
<sup>2</sup> Exchange Online plan 1, Office 365 E1/A1/G1 y Microsoft 365 Empresa Básico/Standard/Premium tienen un límite de tamaño en el buzón y el archivo. Para más información, vea [Límites de Exchange Online](../exchange-online-service-description/exchange-online-limits.md). El complemento Archivado de Exchange Online para Exchange Online agrega [Retención local y retención por juicio](compliance-and-security-features.md#in-place-hold-and-litigation-hold) y funcionalidad de archivado basada en la nube sin limitaciones.
<br/>
<sup>3</sup> Incluye planes GCC, GCC-High y DoD para us government.

¿Está buscando información sobre todos Microsoft 365 planes? Microsoft 365 está disponible en una variedad de planes para satisfacer mejor las necesidades de su organización. Para obtener información sobre diferentes planes, incluidas las opciones de plan independientes y la información sobre cómo pasar de un plan a otro, [vea Office 365 plan options](../office-365-platform-service-description/office-365-plan-options.md).
  
## <a name="requirements"></a>Requirements

Para usar Archivado de Exchange Online para Exchange Server, los buzones de usuario deben residir en Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 o Exchange Server 2010 (SP2 o posterior).
  
### <a name="federated-identity-and-single-sign-on"></a>Identidad federada e inicio de sesión único

Los administradores pueden usar un enfoque de inicio de sesión único para la autenticación con Active Directory local. Para ello, los administradores pueden configurar los Servicios de federación de Active Directory locales(un servicio de Microsoft Windows Server 2008) para federar con el &reg; Microsoft Federation Gateway. Una vez configurados los Servicios de federación de Active Directory, todos los usuarios cuyas identidades se basan en el dominio federado pueden usar su inicio de sesión corporativo existente para autenticarse automáticamente en Office 365.
  
### <a name="user-subscriptions"></a>Suscripciones de usuario

Cada usuario que acceda al servicio de Archivado de Exchange Online debe tener una suscripción de Archivado de Exchange Online. Cada suscripción de archivado de correo electrónico solo se puede utilizar para almacenar los datos de mensajería de un usuario.
  
## <a name="unlimited-archive-storage-quota"></a>Cuota de almacenamiento de archivo ilimitada

 La característica de archivado ilimitado (denominada *archivado de ampliación automática*) proporciona espacio de almacenamiento adicional en los buzones de archivo. Cada suscriptor de Archivado de Exchange Online recibe inicialmente 100 GB de almacenamiento en el buzón de archivo. Cuando se activa el archivado de expansión automática, se agrega espacio de almacenamiento adicional automáticamente cuando se alcanza la capacidad de almacenamiento de 100 GB. En las implementaciones híbridas de Exchange, el archivado de expansión automática solo se admite para buzones de archivo basados en la nube cuando el buzón del usuario local reside en Exchange Server 2019, Exchange Server 2016 o Exchange Server 2013 (SP1 o posterior). Para obtener más información, consulte [Información general del archivado ilimitado](/office365/securitycompliance/unlimited-archiving).
  
> [!IMPORTANT]
> Los administradores no pueden ajustar la cuota de almacenamiento.<br/>
> El archivado de expansión automática no es compatible con buzones que residen en Exchange Server 2010.
  
> [!IMPORTANT]
> El archivo de expansión automática solo se admite para buzones de correo usados para usuarios individuales o buzones compartidos con una tasa de crecimiento que no supere *1 &nbsp; GB al día.* No se permite copiar mensajes en Archivado de Exchange Online para su archivo con el registro en diario, o mediante reglas de transporte o reenvío automático. El buzón de archivo de un usuario está diseñado exclusivamente para dicho usuario. Microsoft se reserva el derecho a denegar el archivado ilimitado en los casos en que el buzón de archivo de un usuario se utilice para almacenar datos de archivo para otros usuarios o en otros casos de uso inadecuado.
  
## <a name="feature-availability-across-exchange-online-archiving-plans"></a>Disponibilidad de características en los planes de Archivado de Exchange Online

| Característica | Archivado de Exchange Online para Exchange Server<sup>1</sup> | Archivado de Exchange Online para Exchange Online<sup>2</sup> |
|:-----|:-----|:-----|
|**[Características de archivo en Archivado de Exchange Online](archive-features.md)** <br/> |||
|Buzón de archivo  <br/> |Sí  <br/> |Sí  <br/> |
|Mover mensajes mediante la directiva de archivo  <br/> |Sí  <br/> |Sí  <br/> |
|Importar datos al archivo  <br/> |Sí  <br/> |Sí  <br/> |
|Recuperación de elementos eliminados  <br/> |Sí  <br/> |Sí  <br/> |
|Recuperación de buzones eliminados  <br/> |Sí  <br/> |Sí  <br/> |
|Copia de seguridad del buzón  <br/> |Sí  <br/> |Sí  <br/> |
|**[Características de cliente en Archivado de Exchange Online](client-features.md)** <br/> |||
|Outlook<sup>3</sup> <br/> |Sí  <br/> |Sí  <br/> |
|Outlook en la Web  <br/> |Sí  <br/> |Sí  <br/> |
|**[Características de cumplimiento y seguridad en Archivado de Exchange Online](compliance-and-security-features.md)** <br/> |||
|Directivas de retención  <br/> |Sí  <br/> |Sí  <br/> |
|Conservación local y retención por juicio<sup>6</sup> <br/> |Sí  <br/> |Sí  <br/> |
|Exhibición de documentos electrónicos en contexto  <br/> |Sí  <br/> |Sí  <br/> |
|Cifrado entre servidores locales y el Archivado de Exchange Online  <br/> |Sí  <br/> |Sí  <br/> |
|Cifrado entre clientes y el Archivado de Exchange Online  <br/> |Sí  <br/> |Sí  <br/> |
|Cifrado: S/MIME y PGP  <br/> |Sí  <br/> |Sí  <br/> |
|IRM con Azure Information Protection  <br/> |No  <br/> |No<sup>4</sup> <br/> |
|IRM con Windows Server AD RMS  <br/> |Sí<sup>5</sup> <br/> |Sí<sup>5</sup> <br/> |
|Auditoría  <br/> |Sí  <br/> |Sí  <br/> |
   

<sup>1</sup> Los buzones de correo del usuario deben residir en Exchange 2010 SP2 u otra versión posterior.
<br/>
<sup>2</sup> Solo puede usarse Archivo local para archivar correo de una sola entidad o un único usuario al que se le haya aplicado una licencia. No se permite usar Archivo local para almacenar correo de varios usuarios o entidades. Por ejemplo, los administradores de TI no pueden crear buzones compartidos ni permitir que los usuarios copien (con los campos CC o CCO, o mediante una regla de transporte) buzones compartidos para archivarlos. <br/> 
<sup>3</sup> Para obtener una lista de las versiones de Microsoft Outlook compatibles, vea [Características de cliente en Archivado de Exchange Online](client-features.md). <br/>
<sup>4</sup> Azure Information Protection no se incluye, pero puede adquirirse como complemento independiente y habilitará las características admitidas de Information Rights Management (IRM). Algunas características de Azure Information Protection requieren una suscripción a Aplicaciones Microsoft 365 para empresas, que no se incluye con Microsoft 365 Empresa Básico, Microsoft 365 Empresa Estándar, Office 365 Enterprise E1, Office 365 Educación o Office 365 Enterprise F3. <br/>
<sup>5</sup> Windows Server AD RMS es un servidor local que debe comprarse y administrarse por separado para habilitar las características de IRM admitidas. <br/>
<sup>6</sup> Si coloca un buzón en Conservación local o retención por juicio, la conservación o retención se aplica al buzón principal y al buzón de archivo.