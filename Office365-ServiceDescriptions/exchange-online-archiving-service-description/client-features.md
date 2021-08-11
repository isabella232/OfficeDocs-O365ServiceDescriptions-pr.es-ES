---
title: Características de cliente en Archivado de Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: Lea este artículo para obtener información sobre las características de cliente disponibles en Microsoft Exchange Online archivado.
ms.openlocfilehash: df71da18d5eb2304496bc72ac2556bb3cc325e50e49cccb14ba6b5191cc95b1d
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/06/2021
ms.locfileid: "54664673"
---
# <a name="client-features-in-exchange-online-archiving"></a>Características de cliente en Archivado de Exchange Online

Microsoft Exchange Online El archivado permite a los usuarios conectarse a sus buzones de archivo desde una variedad de dispositivos y plataformas. Toda la conectividad de red al archivo del usuario se produce a través de Internet y las conexiones de red privada virtual (VPN) no son necesarias. Para permitir el acceso de los usuarios a su buzón principal con Outlook en cualquier lugar, sin necesidad de conexión VPN, las organizaciones pueden publicar en un servidor de acceso de cliente local. Si se requiere acceso a VPN para acceder al buzón de correo principal del usuario en un servidor local, este requisito no cambiará.
  
> [!IMPORTANT]
> Microsoft se reserva el derecho a bloquear o limitar las conexiones de cualquier software de cliente que afecte negativamente al estado del servicio de Archivado de Exchange Online.
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook es un programa de correo muy completo que admite calendarios, contactos y tareas. Archivado de Exchange Online es compatible con Outlook 2013, Outlook 2010 Outlook 2007. Entre sus características principales se incluyen:
  
- **Outlook anywhere:** Outlook Anywhere permite a Outlook usuarios conectarse a Exchange Server y Archivado de Exchange Online a través de Internet sin necesidad de una conexión VPN. La comunicación entre Outlook y Archivado de Exchange Online se produce mediante un túnel seguro para SSL, con el componente de red de Windows RPC sobre HTTP.    
- **Detección** automática: el Exchange de detección automática configura automáticamente Outlook para que funcione con Archivado de Exchange Online. La detección automática permite a Outlook usuarios recibir la configuración de perfil necesaria directamente desde Exchange la primera vez (y a intervalos fijos a partir de entonces) que inician sesión con su dirección de correo electrónico y contraseña. 

Outlook 2010 y posteriores y Outlook en la Web proporcionan a los usuarios todas las características del archivo, así como características relacionadas como directivas de retención y archivo.
  
Aunque Outlook 2007 es compatible con la funcionalidad básica de archivo, no proporciona todas las características de archivo y cumplimiento existentes. Por ejemplo, no permite a los usuarios aplicar directivas de archivo o retención a los elementos de sus buzones. En su lugar, deben usar las directivas que proporciona el administrador. Para acceder al archivo, los usuarios de Outlook 2007 precisan la actualización acumulativa de Office 2007 de febrero de 2011.
  
> [!NOTE]
> Outlook no se proporciona con Archivado de Exchange Online. Aplicaciones Microsoft 365 para empresas (que incluye Microsoft Outlook) se incluye en algunos planes y se puede comprar como una suscripción independiente. Para obtener más información, [vea Microsoft 365 plan options](../office-365-platform-service-description/office-365-plan-options.md). Para obtener más información acerca Aplicaciones Microsoft 365 para empresas, vea la descripción del servicio [Office aplicaciones.](../office-applications-service-description/office-applications-service-description.md) 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Clientes compatibles con Exchange Online Archiving

La tabla siguiente contiene los clientes compatibles con Archivado de Exchange Online:<br><br>
  
| Cliente | Compatibilidad con EOA |
|:-----|:-----|
|Outlook 2013 y versiones posteriores  <br/> |Compatible con las últimas características de Archivado de Exchange Online.<sup>1</sup> <br/> |
|Outlook 2010  <br/> |Admite las características más recientes de Archivado de Exchange Online hasta el 13 de octubre de 2020|
|Outlook 2007  <br/> |No admitido |
|Outlook 2003  <br/> |No se admite  <br/> |
|Outlook para Mac 2011  <br/> |No se admite  <br/> |
|Outlook para Mac  <br/> |Se admite para su uso con Archivado de Exchange Online. <sup>3</sup> <br/> |
|Microsoft Office Entourage 2008, Web Services Edition  <br/> |No se admite  <br/> |
|IMAP y POP  <br/> |No se admite  <br/> |
|Exchange ActiveSync (dispositivos móviles)  <br/> |No se admite  <br/> |
   
> [!NOTE]
> <sup>1 Outlook</sup> se incluye con Microsoft Office No se admite Standard. Para obtener más información, vea [License requirements for Personal Archive and retention policies](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99). <br/> 
<sup>2 Requiere</sup> actualización para habilitar la compatibilidad con archivado. Outlook usuarios de 2007 no pueden ver ni aplicar directivas de retención o archivo a los elementos de sus buzones de archivo; deben basarse en directivas aprovisionadas por el administrador. Además, Outlook usuarios de 2007 no pueden buscar en el buzón local y el archivo al mismo tiempo. <br/> 
<sup>3</sup> No puede usar Outlook 2016 para Mac o Outlook para Mac para mover o copiar carpetas, elementos de calendario, contactos, tareas o notas en el archivo, ni verlos en el buzón de archivo, si los elementos se movieron anteriormente allí mediante cualquier otra versión de Outlook (como Outlook 2016 para Windows). Para obtener más información, vea [Use your online archive with Outlook 2016 para Mac](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238). 

## <a name="outlook-on-the-web"></a>Outlook en la web

Outlook en la web es una versión basada en web del programa de correo electrónico Outlook que se usa con Exchange Online. Siempre que los usuarios estén conectados a Internet en casa, en la oficina o en el camino, pueden acceder a su correo electrónico a través &mdash; &mdash; de Outlook en la Web.
  
Los usuarios pueden acceder a su archivo iniciando sesión Outlook en la Web local (con la misma dirección URL). El archivo aparece junto con su buzón principal en Outlook en la Web. No hay ninguna forma explícita de obtener acceso al archivo directamente desde Outlook en la Web.
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, opciones independientes y soluciones locales, [consulte Archivado de Exchange Online descripción del servicio](exchange-online-archiving-service-description.md).