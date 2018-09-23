---
title: Características de cliente de Exchange Online Archiving
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: Microsoft Exchange Online Archiving permite a los usuarios conectarse a sus buzones de archivo desde una variedad de plataformas y dispositivos. Toda la conectividad de red para el archivo del usuario se produce a través de Internet, y no se requieren conexiones de red privada virtual (VPN). Las organizaciones pueden publicar un servidor de acceso de cliente local para permitir a los usuarios tener acceso a su buzón principal con Outlook en cualquier lugar, sin necesidad de una conexión VPN. Si se requiere acceso VPN para tener acceso a buzón principal del usuario que se encuentra en un servidor local, este requisito no cambia.
ms.openlocfilehash: 90f384e990363294c8972a79e8b500d97ca4a839
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036925"
---
# <a name="client-features-in-exchange-online-archiving"></a>Características de cliente de Exchange Online Archiving

Microsoft Exchange Online Archiving permite a los usuarios conectarse a sus buzones de archivo desde una variedad de plataformas y dispositivos. Toda la conectividad de red para el archivo del usuario se produce a través de Internet, y no se requieren conexiones de red privada virtual (VPN). Las organizaciones pueden publicar un servidor de acceso de cliente local para permitir a los usuarios tener acceso a su buzón principal con Outlook en cualquier lugar, sin necesidad de una conexión VPN. Si se requiere acceso VPN para tener acceso a buzón principal del usuario que se encuentra en un servidor local, este requisito no cambia.
  
> [!IMPORTANT]
> Microsoft se reserva el derecho a bloquear o limitar las conexiones de cualquier software de cliente que afecte negativamente al estado del servicio de Archivado de Exchange Online. 
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook es un programa de correo muy completo que admite calendarios, contactos y tareas. Archivado de Exchange Online es compatible con Outlook 2013, Outlook 2010 Outlook 2007. Entre sus características principales se incluyen:
  
- **Outlook en cualquier lugar** Outlook en cualquier lugar permite a los usuarios de Outlook conectar con Exchange Server y Archivado de Exchange Online a través de Internet, sin necesidad de conexión VPN. La comunicación entre Outlook y Archivado de Exchange Online se produce mediante un túnel seguro para SSL, con el componente de red de Windows RPC sobre HTTP. 
    
- **Detección automática** El servicio Detección automática de Exchange configura Outlook de forma automática para que funcione con Archivado de Exchange Online. Este servicio permite a los usuarios de Outlook recibir la configuración del perfil necesaria directamente desde Exchange, cuando inician sesión por primera vez (y a intervalos regulares a partir de ese momento) con su dirección de correo y contraseña. 
    
Outlook 2010 (y versiones posteriores) y Outlook Web App ofrecen a los usuarios todas las características de archivo y una serie de características relacionadas, como las directivas de archivo y retención.
  
Aunque Outlook 2007 es compatible con la funcionalidad básica de archivo, no proporciona todas las características de archivo y cumplimiento existentes. Por ejemplo, no permite a los usuarios aplicar directivas de archivo o retención a los elementos de sus buzones. En su lugar, deben usar las directivas que proporciona el administrador. Para acceder al archivo, los usuarios de Outlook 2007 precisan la actualización acumulativa de Office 2007 de febrero de 2011.
  
> [!NOTE]
> Outlook no se proporciona con Archivado de Exchange Online. Microsoft Office 365 ProPlus (que sí incluye Microsoft Outlook) se ofrece con algunos planes de Office 365 y puede adquirirse con una suscripción independiente. Para más información, vea [Opciones de planes de Office 365](../office-365-platform-service-description/office-365-plan-options.md). Para más información sobre Office 365 ProPlus, vea [Descripción del servicio de aplicaciones de Office](../office-applications-service-description/office-applications-service-description.md). 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Clientes compatibles con Exchange Online Archiving

La tabla siguiente contiene los clientes compatibles con Archivado de Exchange Online:
  
|**Cliente**|**Compatibilidad con EOA**|
|:-----|:-----|
|Outlook 2010 y versiones posteriores  <br/> |Compatible con las últimas características de Archivado de Exchange Online.<sup>1</sup> <br/> |
|Outlook 2007  <br/> |Compatible con Archivado de Exchange Online.<sup>1,2</sup> <br/> |
|Outlook 2003  <br/> |No se admite  <br/> |
|Outlook para Mac 2011  <br/> |No se admite  <br/> |
|Outlook para Mac  <br/> |Compatibles para su uso con Exchange Online Archiving. <sup>3</sup> <br/> |
|Microsoft Office Entourage 2008, Web Services Edition  <br/> |No se admite  <br/> |
|IMAP y POP  <br/> |No se admite  <br/> |
|Exchange ActiveSync (dispositivos móviles)  <br/> |No se admite  <br/> |
   
> [!NOTE]
> <sup>1</sup> no se admite outlook incluido con Microsoft Office Standard. Para obtener más información, vea [requisitos de licencia para archivo Personal y las directivas de retención](https://go.microsoft.com/fwlink/?LinkId=389396). > <sup>2</sup> requiere actualización para habilitar la compatibilidad de archivado. Los usuarios de Outlook 2007 no pueden ver o aplicar una retención o archivar las directivas a los elementos en sus buzones de archivo; deben basarse en las directivas aprovisionado por el administrador. Además, los usuarios de Outlook 2007 no pueden buscar el buzón de correo local y el archivo al mismo tiempo. > <sup>3</sup> no se puede usar 2016 de Outlook para Mac o Outlook para Mac para mover o copiar carpetas, elementos de calendario, contactos, tareas o notas a su archivo o verlas en el buzón de archivo, si los elementos anteriormente se movieron existe mediante el uso de cualquier otra versión de Outlook ( Por ejemplo, 2016 Outlook para Windows). Para obtener más información, vea [Use su archivo en línea con 2016 de Outlook para Mac](https://support.office.com/en-us/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238). 
  
## <a name="outlook-web-app"></a>Outlook Web App

Outlook Web App es una versión basada en web del programa de correo Outlook, que se usa con Exchange Online. Siempre están conectados a Internet (ya sea en casa, en la oficina o durante un viaje), los usuarios pueden acceder al correo electrónico a través de Outlook Web App.
  
Para acceder al archivo, los usuarios deben iniciar sesión en la implementación local de Outlook Web App (con la misma URL). El archivo aparecerá junto al buzón principal en Outlook Web App. Desde Outlook Web App, no puede accederse al archivo directamente de ninguna otra forma.
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, vea [Descripción del servicio de archivado de Exchange Online](exchange-online-archiving-service-description.md).
  

