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
# <a name="networking"></a><span data-ttu-id="2501a-103">Conexión de red</span><span class="sxs-lookup"><span data-stu-id="2501a-103">Networking</span></span>

<span data-ttu-id="2501a-104">Microsoft Office 365 admite las siguientes características de red.</span><span class="sxs-lookup"><span data-stu-id="2501a-104">Microsoft Office 365 supports the following networking features.</span></span>
  
## <a name="ports-protocols-and-ip-addresses"></a><span data-ttu-id="2501a-105">Puertos, protocolos y direcciones IP</span><span class="sxs-lookup"><span data-stu-id="2501a-105">Ports, protocols, and IP addresses</span></span>

<span data-ttu-id="2501a-p101">Office 365 usa direcciones IPv4 e IPv6. El uso de direcciones IPv6 es opcional y no se requiere para la conectividad con Office 365. No todas las características de Office 365 están habilitadas por completo mediante IPv6. Para obtener más información sobre la compatibilidad de Ipv6 en Office 365, consulte [Compatibilidad con IPv6 en los servicios de Office 365](https://go.microsoft.com/fwlink/?LinkID=785121&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="2501a-p101">Office 365 uses IPv4 and IPv6 addresses. Use of IPv6 addressing is optional and not required for connectivity with Office 365. Not all Office 365 features are fully enabled using IPv6. For more information about Ipv6 support in Office 365, see [IPv6 support in Office 365 services](https://go.microsoft.com/fwlink/?LinkID=785121&amp;clcid=0x409).</span></span>
  
<span data-ttu-id="2501a-p102">En la ayuda de Office 365, se muestra una lista de las direcciones IP permitidas en Office 365. Para obtener más información, vea [URL de Office 365 e intervalos de direcciones IP](https://go.microsoft.com/fwlink/p/?LinkID=243567). Para Office 365 operado por 21Vianet, consulte [URL y direcciones IP para Office 365 operado por 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733351&amp;clcid=0x409). Para Office 365 Germany, consulte [Puntos de conexión de Office 365 Germany](https://support.office.com/en-us/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span><span class="sxs-lookup"><span data-stu-id="2501a-p102">Office 365 maintains a list of allowed IP addresses in the Office 365 help. For more information, see [Office 365 URLs and IP address ranges](https://go.microsoft.com/fwlink/p/?LinkID=243567). For Office 365 operated by 21Vianet, see [URLs and IP Addresses for Office 365 operated by 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733351&amp;clcid=0x409). For Office 365 Germany, see [Office 365 Germany endpoints](https://support.office.com/en-us/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="2501a-p103">Se recomienda encarecidamente habilitar el enrutamiento a los nombres de dominio raíz que se enumeran en los artículos anteriores (como \*.Outlook.com, \*.MicrosoftOnline.com y \*.SharePoint.com) en lugar de enrutar a subredes de direcciones IP específicas. Al depender de subredes de direcciones IP, se corre el riesgo de interrupciones para los usuarios a medida que se realizan cambios.</span><span class="sxs-lookup"><span data-stu-id="2501a-p103">We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made.</span></span> 
  
## <a name="bandwidth-requirements"></a><span data-ttu-id="2501a-116">Requisitos de ancho de banda</span><span class="sxs-lookup"><span data-stu-id="2501a-116">Bandwidth requirements</span></span>

<span data-ttu-id="2501a-117">Para obtener información sobre los requisitos de ancho de banda, vea [Planificación del ancho de banda de Internet](https://go.microsoft.com/fwlink/p/?LinkID=282467).</span><span class="sxs-lookup"><span data-stu-id="2501a-117">For information on bandwidth requirements, see [Internet bandwidth planning](https://go.microsoft.com/fwlink/p/?LinkID=282467).</span></span>
  
## <a name="connecting-to-office-365"></a><span data-ttu-id="2501a-118">Conexión a Office 365</span><span class="sxs-lookup"><span data-stu-id="2501a-118">Connecting to Office 365</span></span>

<span data-ttu-id="2501a-p104">Todas las conexiones a Office 365 se realizan a través de Internet público o en una conexión privada de Azure ExpressRoute, y están protegidas con SSL según corresponda. Azure ExpressRoute permite conectarse directamente a la red global de Microsoft y omitir Internet. Un partner de redes de Microsoft proporciona la conectividad a la red global de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="2501a-p104">All Connections to Office 365 are done over the public Internet or over a private Azure ExpressRoute connection, and are secured by SSL as appropriate. Azure ExpressRoute allows connecting directly to the global Microsoft network, bypassing the Internet. A Microsoft networking partner provides the connectivity to the global Microsoft network.</span></span>
  
<span data-ttu-id="2501a-122">Para obtener más información sobre Azure ExpressRoute, consulte [Azure ExpressRoute para Office 365.](https://aka.ms/expressrouteoffice365).</span><span class="sxs-lookup"><span data-stu-id="2501a-122">For more information about Azure ExpressRoute, see [Azure ExpressRoute for Office 365.](https://aka.ms/expressrouteoffice365)</span></span>
  
### <a name="wan-accelerators"></a><span data-ttu-id="2501a-123">Aceleradores WAN</span><span class="sxs-lookup"><span data-stu-id="2501a-123">WAN accelerators</span></span>

<span data-ttu-id="2501a-p105">Microsoft no ofrece compatibilidad con los dispositivos de almacenamiento en caché y aceleración de WAN propios del cliente en Office 365. Si decide usar un controlador de optimización de WAN para mejorar el rendimiento en condiciones de alta latencia o bajo ancho de banda, deberá deshabilitarlo cuando se intenten resolver solicitudes de servicio con Microsoft y trabajar con el proveedor de su dispositivo para la compatibilidad de dispositivos. Para obtener más información, vea [Dispositivos de almacenamiento en caché y aceleración de WAN con Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282468).</span><span class="sxs-lookup"><span data-stu-id="2501a-p105">Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282468).</span></span>
  
## <a name="the-global-microsoft-network"></a><span data-ttu-id="2501a-127">Red global de Microsoft</span><span class="sxs-lookup"><span data-stu-id="2501a-127">The global Microsoft network</span></span>

<span data-ttu-id="2501a-p106">La infraestructura de red de Office 365 está compuesta por una gran cartera global de centros de datos, servidores, redes de distribución de contenido, nodos informáticos perimetrales y redes de fibra óptica para ofrecer distribución global de servicios. La supervisión e instrumentación de servicios sofisticados se integran en los niveles más profundos con cada componente, lo que brinda visibilidad del centro de datos, la red troncal de las redes, los intercambios de Internet y más, para ayudar a detectar, diagnosticar y administrar la causa de las interrupciones que se presentan. La red está diseñada para mantener la capacidad suficiente incluso en el caso de interrupciones de red a gran escala sin degradación del rendimiento. Para obtener más información, vea [Global Foundation Services](https://go.microsoft.com/fwlink/p/?LinkID=282622).</span><span class="sxs-lookup"><span data-stu-id="2501a-p106">The Office 365 networking infrastructure is comprised of a large global portfolio of data centers, servers, content distribution networks, edge computing nodes, and fiber optic networks to provide global distribution of services. Sophisticated service instrumentation and monitoring integrates at the deepest levels with each component, giving visibility into the data center, network backbone, internet exchanges and beyond, to help spot, diagnose and manage the cause of disruptions that arise. The network is built to maintain sufficient capacity even for large scale network interruptions without degradation of performance. For more information, see [Global Foundation Services](https://go.microsoft.com/fwlink/p/?LinkID=282622).</span></span> 
  
<span data-ttu-id="2501a-p107">Con el fin de conservar la confidencialidad e integridad de los datos de los clientes, Microsoft mantiene las redes de servicios a clientes separadas de las redes de Office 365. Se utilizan diversas técnicas para controlar los flujos de información; a continuación, se mencionan algunas de ellas:</span><span class="sxs-lookup"><span data-stu-id="2501a-p107">To maintain the confidentiality and integrity of customer data, Microsoft keeps consumer services networks separate from Office 365 networks. Multiple techniques are used to control information flows, including but not limited to:</span></span>
  
- <span data-ttu-id="2501a-p108">Separación física. Los segmentos de red se encuentran separados físicamente por enrutadores configurados para impedir patrones de comunicación específicos.</span><span class="sxs-lookup"><span data-stu-id="2501a-p108">Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.</span></span>
    
- <span data-ttu-id="2501a-p109">Separación lógica. La tecnología LAN Virtual (VLAN) se utiliza para separar aun más las comunicaciones.</span><span class="sxs-lookup"><span data-stu-id="2501a-p109">Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.</span></span>
    
- <span data-ttu-id="2501a-p110">Firewalls. Los firewalls y otros puntos de aplicación de seguridad de red se utilizan para limitar los intercambios de datos con los sistemas que están expuestos a Internet y para aislar los sistemas de los sistemas de servidor que administra Microsoft.</span><span class="sxs-lookup"><span data-stu-id="2501a-p110">Firewalls. Firewalls and other network security enforcement points are used to limit data exchanges with systems that are exposed to the Internet, and to isolate systems from back-end systems managed by Microsoft.</span></span> 
    
- <span data-ttu-id="2501a-140">Restricciones de protocolo.</span><span class="sxs-lookup"><span data-stu-id="2501a-140">Protocol restrictions.</span></span>
    
<span data-ttu-id="2501a-141">Para obtener más información, vea [Centro de confianza de Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282621).</span><span class="sxs-lookup"><span data-stu-id="2501a-141">For more information, see the [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkID=282621).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="2501a-142">Disponibilidad de características</span><span class="sxs-lookup"><span data-stu-id="2501a-142">Feature availability</span></span>

<span data-ttu-id="2501a-143">Para ver la disponibilidad de características entre planes de Office 365, consulte [Descripción del servicio de la plataforma de Office 365](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).</span><span class="sxs-lookup"><span data-stu-id="2501a-143">To view feature availability across Office 365 plans, see [Office 365 Platform Service Description](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).</span></span>
  

