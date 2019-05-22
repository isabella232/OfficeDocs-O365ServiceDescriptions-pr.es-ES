---
title: Conexión de red
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft Office 365 admite las siguientes características de red.
ms.openlocfilehash: 0a7956b5d59082f2f04f71ee2e349c2c3b238c83
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/22/2019
ms.locfileid: "34343629"
---
# <a name="networking"></a>Conexión de red

Microsoft Office 365 admite las siguientes características de red.
  
## <a name="ports-protocols-and-ip-addresses"></a>Puertos, protocolos y direcciones IP

Office 365 usa direcciones IPv4 e IPv6. El uso de direcciones IPv6 es opcional y no se requiere para la conectividad con Office 365. No todas las características de Office 365 están habilitadas por completo mediante IPv6. Para obtener más información sobre la compatibilidad de Ipv6 en Office 365, consulte [Compatibilidad con IPv6 en los servicios de Office 365](https://go.microsoft.com/fwlink/?LinkID=785121&amp;clcid=0x409).
  
En la ayuda de Office 365, se muestra una lista de las direcciones IP permitidas en Office 365. Para obtener más información, vea [URL de Office 365 e intervalos de direcciones IP](https://go.microsoft.com/fwlink/p/?LinkID=243567). Para Office 365 operado por 21Vianet, consulte [URL y direcciones IP para Office 365 operado por 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733351&amp;clcid=0x409). Para Office 365 Germany, consulte [Puntos de conexión de Office 365 Germany](https://support.office.com/en-us/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).
  
> [!IMPORTANT]
> Se recomienda encarecidamente habilitar el enrutamiento a los nombres de dominio raíz que se enumeran en los artículos anteriores (como \*.Outlook.com, \*.MicrosoftOnline.com y \*.SharePoint.com) en lugar de enrutar a subredes de direcciones IP específicas. Al depender de subredes de direcciones IP, se corre el riesgo de interrupciones para los usuarios a medida que se realizan cambios. 
  
## <a name="bandwidth-requirements"></a>Requisitos de ancho de banda

Para obtener información sobre los requisitos de ancho de banda, vea [Planificación del ancho de banda de Internet](https://go.microsoft.com/fwlink/p/?LinkID=282467).
  
## <a name="connecting-to-office-365"></a>Conexión a Office 365

Todas las conexiones a Office 365 se realizan a través de Internet público o en una conexión privada de Azure ExpressRoute, y están protegidas con SSL según corresponda. Azure ExpressRoute permite conectarse directamente a la red global de Microsoft y omitir Internet. Un partner de redes de Microsoft proporciona la conectividad a la red global de Microsoft.
  
Para obtener más información sobre Azure ExpressRoute, consulte [Azure ExpressRoute para Office 365.](https://aka.ms/expressrouteoffice365).
  
### <a name="wan-accelerators"></a>Aceleradores WAN

Microsoft no ofrece compatibilidad con los dispositivos de almacenamiento en caché y aceleración de WAN propios del cliente en Office 365. Si decide usar un controlador de optimización de WAN para mejorar el rendimiento en condiciones de alta latencia o bajo ancho de banda, deberá deshabilitarlo cuando se intenten resolver solicitudes de servicio con Microsoft y trabajar con el proveedor de su dispositivo para la compatibilidad de dispositivos. Para obtener más información, vea [Dispositivos de almacenamiento en caché y aceleración de WAN con Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282468).
  
## <a name="the-global-microsoft-network"></a>Red global de Microsoft

La infraestructura de red de Office 365 está compuesta por una gran cartera global de centros de datos, servidores, redes de distribución de contenido, nodos informáticos perimetrales y redes de fibra óptica para ofrecer distribución global de servicios. La supervisión e instrumentación de servicios sofisticados se integran en los niveles más profundos con cada componente, lo que brinda visibilidad del centro de datos, la red troncal de las redes, los intercambios de Internet y más, para ayudar a detectar, diagnosticar y administrar la causa de las interrupciones que se presentan. La red está diseñada para mantener la capacidad suficiente incluso en el caso de interrupciones de red a gran escala sin degradación del rendimiento. Para obtener más información, vea [Global Foundation Services](https://go.microsoft.com/fwlink/p/?LinkID=282622). 
  
Con el fin de conservar la confidencialidad e integridad de los datos de los clientes, Microsoft mantiene las redes de servicios a clientes separadas de las redes de Office 365. Se utilizan diversas técnicas para controlar los flujos de información; a continuación, se mencionan algunas de ellas:
  
- Separación física. Los segmentos de red se encuentran separados físicamente por enrutadores configurados para impedir patrones de comunicación específicos.
    
- Separación lógica. La tecnología LAN Virtual (VLAN) se utiliza para separar aun más las comunicaciones.
    
- Firewalls. Los firewalls y otros puntos de aplicación de seguridad de red se utilizan para limitar los intercambios de datos con los sistemas que están expuestos a Internet y para aislar los sistemas de los sistemas de servidor que administra Microsoft. 
    
- Restricciones de protocolo.
    
Para obtener más información, vea [Centro de confianza de Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282621). 
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes de Office 365, consulte [Descripción del servicio de la plataforma de Office 365](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).
  

