---
title: Características de cliente de archivado de Exchange Online
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
description: Lea este artículo para obtener información sobre las características de cliente disponibles en archivado de Microsoft Exchange Online.
ms.openlocfilehash: 54f066562b08eeeed90b8c9b465c4740bcc3f0df
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/28/2020
ms.locfileid: "48293646"
---
# <a name="client-features-in-exchange-online-archiving"></a>Características de cliente de archivado de Exchange Online

El archivado de Microsoft Exchange Online permite a los usuarios conectarse a sus buzones de archivo desde distintos dispositivos y plataformas. Toda la conectividad de red con el archivo del usuario se produce a través de Internet y las conexiones de red privada virtual (VPN) no son necesarias. Para permitir el acceso de los usuarios a su buzón principal con Outlook en cualquier lugar, sin necesidad de conexión VPN, las organizaciones pueden publicar en un servidor de acceso de cliente local. Si se requiere acceso a VPN para acceder al buzón de correo principal del usuario en un servidor local, este requisito no cambiará.
  
> [!IMPORTANT]
> Microsoft se reserva el derecho a bloquear o limitar las conexiones de cualquier software de cliente que afecte negativamente al estado del servicio de Archivado de Exchange Online.
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook es un programa de correo muy completo que admite calendarios, contactos y tareas. Archivado de Exchange Online es compatible con Outlook 2013, Outlook 2010 Outlook 2007. Entre sus características principales se incluyen:
  
- **Outlook Anywhere** : Outlook Anywhere permite que los usuarios de Outlook se conecten a Exchange Server y al archivado de Exchange Online a través de Internet sin necesidad de una conexión VPN. La comunicación entre Outlook y Archivado de Exchange Online se produce mediante un túnel seguro para SSL, con el componente de red de Windows RPC sobre HTTP.    
- **Autodiscover** : el servicio Detección automática de Exchange configura automáticamente Outlook para que funcione con el archivado de Exchange Online. La detección automática permite que los usuarios de Outlook reciban la configuración de perfil necesaria directamente desde Exchange la primera vez (y a intervalos fijos posteriores) que inicien sesión con su dirección de correo electrónico y contraseña. 

Outlook 2010 y versiones posteriores y Outlook en la web proporcionan a los usuarios las características completas del archivo, así como las características relacionadas, como la retención y las directivas de archivo.
  
Aunque Outlook 2007 es compatible con la funcionalidad básica de archivo, no proporciona todas las características de archivo y cumplimiento existentes. Por ejemplo, no permite a los usuarios aplicar directivas de archivo o retención a los elementos de sus buzones. En su lugar, deben usar las directivas que proporciona el administrador. Para acceder al archivo, los usuarios de Outlook 2007 precisan la actualización acumulativa de Office 2007 de febrero de 2011.
  
> [!NOTE]
> Outlook no se proporciona con Archivado de Exchange Online. Microsoft 365 apps for Enterprise (que incluye Microsoft Outlook) se incluye en algunos planes y puede adquirirse como una suscripción independiente. Para obtener más información, consulte [Opciones del plan 365 de Microsoft](../office-365-platform-service-description/office-365-plan-options.md). Para obtener más información sobre las aplicaciones de Microsoft 365 para empresas, vea la [Descripción del servicio de aplicaciones de Office](../office-applications-service-description/office-applications-service-description.md). 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Clientes compatibles con Exchange Online Archiving

La tabla siguiente contiene los clientes compatibles con Archivado de Exchange Online:<br><br>
  
| Cliente | Compatibilidad con EOA |
|:-----|:-----|
|Outlook 2013 y versiones posteriores  <br/> |Compatible con las últimas características de Archivado de Exchange Online.<sup>1</sup> <br/> |
|Outlook 2010  <br/> |Admite las características más recientes de archivado de Exchange Online solo hasta el Oct. 13, 2020|
|Outlook 2007  <br/> |No admitido |
|Outlook 2003  <br/> |No se admite  <br/> |
|Outlook para Mac 2011  <br/> |No se admite  <br/> |
|Outlook para Mac  <br/> |Admitido para su uso con archivado de Exchange Online. <sup>3</sup> <br/> |
|Microsoft Office Entourage 2008, Web Services Edition  <br/> |No se admite  <br/> |
|IMAP y POP  <br/> |No se admite  <br/> |
|Exchange ActiveSync (dispositivos móviles)  <br/> |No se admite  <br/> |
   
> [!NOTE]
> <sup>1</sup> Outlook incluido con Microsoft Office Standard no es compatible. Para obtener más información, consulte [License Requirements for personal Archive and Retention Policies](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99). <br/> 
<sup>2</sup> requiere actualización para habilitar la compatibilidad de archivado. Los usuarios de Outlook 2007 no pueden ver ni aplicar directivas de retención o archivo a los elementos de sus buzones de archivo; deben basarse en las directivas aprovisionadas por el administrador. Además, los usuarios de Outlook 2007 no pueden buscar el buzón local y el archivo al mismo tiempo. <br/> 
<sup>3</sup> no puede usar Outlook 2016 para Mac o Outlook para Mac para mover o copiar carpetas, elementos de calendario, contactos, tareas o notas a su archivo, o verlos en el buzón de archivo, si los elementos se movieron anteriormente mediante cualquier otra versión de Outlook (como Outlook 2016 para Windows). Para obtener más información, vea [usar el archivo en línea con Outlook 2016 para Mac](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238). 

## <a name="outlook-on-the-web"></a>Outlook en la web

Outlook en la web es una versión basada en web del programa de correo electrónico Outlook que se usa con Exchange Online. Siempre que los usuarios se conectan a Internet &mdash; en casa, en la oficina o en la calle, &mdash; pueden tener acceso a su correo electrónico a través de Outlook en la Web.
  
Los usuarios pueden tener acceso a su archivo iniciando sesión en Outlook en la Web local (usando la misma dirección URL). El archivo aparece junto a su buzón de correo principal en Outlook en la Web. No hay una forma explícita de obtener acceso al archivo directamente desde Outlook en la Web.
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, las opciones independientes y las soluciones locales, consulte [Descripción del servicio de archivado de Exchange Online](exchange-online-archiving-service-description.md).