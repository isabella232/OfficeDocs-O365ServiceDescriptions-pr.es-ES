---
title: Conexión de red
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft admite las siguientes características de red.
ms.openlocfilehash: 0f0554bdd907a6f0a37299dc3e38e5f778e7187e
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132334"
---
# <a name="networking"></a>Redes

Microsoft admite las siguientes características de red.
  
## <a name="ports-protocols-and-ip-addresses"></a>Puertos, protocolos y direcciones IP

Microsoft usa direcciones IPv4 e IPv6. El uso de direcciones IPv6 es opcional y no se requiere para la conectividad con Office 365. No todas las características de Microsoft 365 están totalmente habilitadas mediante IPv6. Para obtener más información acerca de la compatibilidad con IPv6, consulte [IPv6 Support in Microsoft Services](https://docs.microsoft.com/office365/enterprise/ipv6-support).
  
Microsoft mantiene una lista de direcciones IP permitidas en la ayuda de Microsoft. Para obtener más información, consulte [direcciones URL e intervalos de direcciones IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges). Para Office 365 operado por 21Vianet, consulte [URL y direcciones IP para Office 365 operado por 21Vianet](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints). Para Office 365 Germany, consulte [Puntos de conexión de Office 365 Germany](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).
  
> [!IMPORTANT]
> Se recomienda encarecidamente habilitar el enrutamiento a los nombres de dominio raíz que se enumeran en los artículos anteriores (como \*.Outlook.com, \*.MicrosoftOnline.com y \*.SharePoint.com) en lugar de enrutar a subredes de direcciones IP específicas. Al depender de subredes de direcciones IP, se corre el riesgo de interrupciones para los usuarios a medida que se realizan cambios. 
  
## <a name="bandwidth-requirements"></a>Requisitos de ancho de banda

Para obtener información sobre los requisitos de ancho de banda, vea [Planificación del ancho de banda de Internet](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance).
  
## <a name="connecting-to-microsoft"></a>Conectarse a Microsoft

Todas las conexiones a Microsoft se realizan a través de Internet público o a través de una conexión privada de Azure ExpressRoute y están protegidas por SSL según corresponda. Azure ExpressRoute permite conectarse directamente a la red global de Microsoft, pasando por alto Internet. Un partner de redes de Microsoft proporciona la conectividad a la red global de Microsoft.
  
Para obtener más información sobre Azure ExpressRoute, consulte [Azure ExpressRoute para Office 365.](https://aka.ms/expressrouteoffice365).
  
### <a name="wan-accelerators"></a>Aceleradores WAN

Microsoft no ofrece compatibilidad con los dispositivos de almacenamiento en caché y aceleración de WAN propios del cliente en Office 365. Si decide usar un controlador de optimización de WAN para mejorar el rendimiento en condiciones de alta latencia o bajo ancho de banda, deberá deshabilitarlo cuando se intenten resolver solicitudes de servicio con Microsoft y trabajar con el proveedor de su dispositivo para la compatibilidad de dispositivos. Para obtener más información, vea [Dispositivos de almacenamiento en caché y aceleración de WAN con Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).
  
## <a name="the-global-microsoft-network"></a>Red global de Microsoft

La infraestructura de red de Microsoft consta de una gran cartera global de centros de datos, servidores, redes de distribución de contenido, nodos de informática perimetral y redes de fibra óptica para proporcionar una distribución global de los servicios. La supervisión e instrumentación de servicios sofisticados se integran en los niveles más profundos con cada componente, lo que brinda visibilidad del centro de datos, la red troncal de las redes, los intercambios de Internet y más, para ayudar a detectar, diagnosticar y administrar la causa de las interrupciones que se presentan. La red está diseñada para mantener la capacidad suficiente incluso en el caso de interrupciones de red a gran escala sin degradación del rendimiento. Para obtener más información, consulte [Microsoft Global Network](https://docs.microsoft.com/azure/networking/microsoft-global-network). 
  
Para mantener la confidencialidad y la integridad de los datos de los clientes, Microsoft mantiene las redes de servicios de consumidor independientes de las redes de Microsoft. Se utilizan diversas técnicas para controlar los flujos de información; a continuación, se mencionan algunas de ellas:
  
- Separación física. Los segmentos de red se encuentran separados físicamente por enrutadores configurados para impedir patrones de comunicación específicos.
    
- Separación lógica. La tecnología LAN Virtual (VLAN) se utiliza para separar aun más las comunicaciones.
    
- Firewalls. Los firewalls y otros puntos de aplicación de seguridad de red se usan para limitar los intercambios de datos con sistemas que están expuestos a Internet y para aislar los sistemas de los sistemas back-end administrados por Microsoft. 
    
- Restricciones de protocolo.
    
Para obtener más información, vea [Centro de confianza de Office 365](https://www.microsoft.com/trust-center). 
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, consulte la descripción del servicio de la [plataforma de Microsoft 365 y Office 365](office-365-platform-service-description.md).
  

