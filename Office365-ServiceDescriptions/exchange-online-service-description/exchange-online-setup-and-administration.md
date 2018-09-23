---
title: Administración y configuración de Exchange Online
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: En esta sección se describe los controles de administración y soporte técnico que están disponibles para personalizar la configuración de Exchange Online y mantener el entorno de Exchange Online de una organización de seguridad, ejecuta y actual. Incluye información acerca de las herramientas de administración de autoservicio y funciones disponibles para las organizaciones; Las responsabilidades de administración de Microsoft y los compromisos de rendimiento; y las actualizaciones de productos y servicios.
ms.openlocfilehash: 6b7bb1d68e6d676c39e9ebb254305b2799cc0931
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036944"
---
# <a name="exchange-online-setup-and-administration"></a><span data-ttu-id="f031e-104">Administración y configuración de Exchange Online</span><span class="sxs-lookup"><span data-stu-id="f031e-104">Exchange Online Setup and Administration</span></span>

<span data-ttu-id="f031e-p102">En esta sección se describe los controles de administración y soporte técnico que están disponibles para personalizar la configuración de Exchange Online y mantener el entorno de Exchange Online de una organización de seguridad, ejecuta y actual. Incluye información acerca de las herramientas de administración de autoservicio y funciones disponibles para las organizaciones; Las responsabilidades de administración de Microsoft y los compromisos de rendimiento; y las actualizaciones de productos y servicios.</span><span class="sxs-lookup"><span data-stu-id="f031e-p102">This section describes the administration controls and support that are available to customize Exchange Online settings and keep an organization's Exchange Online environment up, running, and current. It includes information about self-service administration tools and capabilities available to organizations; Microsoft administration responsibilities and performance commitments; and service and product upgrades.</span></span>
  
## <a name="self-service-administration-tools"></a><span data-ttu-id="f031e-107">Herramientas de administración de autoservicio</span><span class="sxs-lookup"><span data-stu-id="f031e-107">Self-service administration tools</span></span>

<span data-ttu-id="f031e-p103">Si bien Microsoft controla directamente todos los centros de datos de Exchange Online y es responsable del rendimiento general del sistema, puede controlar solo una parte de los elementos que se combinan para ofrecer una experiencia completa a los usuarios de Office 365. Las organizaciones son responsables de las conexiones de red a los centros de datos, la red de área extensa (WAN) del cliente y las redes de área local (LAN) del cliente. Además, están a cargo de los dispositivos de usuario y de su configuración. También son responsables del mantenimiento de las licencias necesarias por usuario para todas las características deseadas, entre ellas, la capacidad de administrar esas características siempre que el usuario necesite acceso a la característica.</span><span class="sxs-lookup"><span data-stu-id="f031e-p103">Although Microsoft directly controls all Exchange Online data centers and is responsible for overall system performance, it can control only a portion of the elements that combine to provide the total experience for Office 365 users. Organizations themselves are responsible for the network connections to the data centers, the customer's wide area network (WAN), and the customer's local area networks (LANs). Additionally, they are in charge of user devices and their configuration.  They are also responsible for maintaining the required licensing per user for any desired feature, including, but not limited to, the ability to manage these features, for as long as the user needs access to the feature.</span></span>
  
<span data-ttu-id="f031e-112">Por lo tanto, Exchange Online ofrece a los administradores de clientes las siguientes herramientas, descritas a continuación, a fin de administrar una variedad de tareas relacionadas con la mensajería:</span><span class="sxs-lookup"><span data-stu-id="f031e-112">Exchange Online therefore provides customer administrators with the following tools, described below, to manage a variety of messaging-related tasks:</span></span>
  
- [<span data-ttu-id="f031e-113">Portal de Microsoft Office 365</span><span class="sxs-lookup"><span data-stu-id="f031e-113">Microsoft Office 365 portal</span></span>](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [<span data-ttu-id="f031e-114">Centro de administración de Microsoft Office 365</span><span class="sxs-lookup"><span data-stu-id="f031e-114">Microsoft Office 365 admin center</span></span>](exchange-online-setup-and-administration.md#microsoft-office-365-admin-center)
    
- [<span data-ttu-id="f031e-115">Centro de administración de Exchange</span><span class="sxs-lookup"><span data-stu-id="f031e-115">Exchange admin center</span></span>](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [<span data-ttu-id="f031e-116">Windows PowerShell remoto para Exchange Online</span><span class="sxs-lookup"><span data-stu-id="f031e-116">Remote Windows PowerShell for Exchange Online</span></span>](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a><span data-ttu-id="f031e-117">Portal de Microsoft Office 365</span><span class="sxs-lookup"><span data-stu-id="f031e-117">Microsoft Office 365 portal</span></span>
<span data-ttu-id="f031e-118"><a name="BKMK_MicrosoftOnlineServicesPortal"> </a></span><span class="sxs-lookup"><span data-stu-id="f031e-118"></span></span>

<span data-ttu-id="f031e-119">El portal de Microsoft Office 365 en [https://portal.office.com](https://portal.office.com) es el sitio web a través del cual los administradores y los socios compran y administran los servicios de Office 365 y donde los usuarios tienen acceso a las herramientas de colaboración de Office 365 y las utilizan.</span><span class="sxs-lookup"><span data-stu-id="f031e-119">The Microsoft Office 365 portal, at [https://portal.office.com](https://portal.office.com), is the website through which administrators and partners purchase and manage Office 365 services and where users access and use Office 365 collaborative tools.</span></span>
  
### <a name="microsoft-office-365-admin-center"></a><span data-ttu-id="f031e-120">Centro de administración de Microsoft Office 365</span><span class="sxs-lookup"><span data-stu-id="f031e-120">Microsoft Office 365 admin center</span></span>
<span data-ttu-id="f031e-121"><a name="BKMK_Office365admincenterl"> </a></span><span class="sxs-lookup"><span data-stu-id="f031e-121"></span></span>

<span data-ttu-id="f031e-p104">El Centro de administración de Microsoft Office 365 es el portal web desde donde el administrador de servicios de cada empresa puede administrar las cuentas de usuario y la configuración de los servicios de Office 365 a los que se suscriben. Desde el Centro de administración de Office 365, los administradores pueden seguir los vínculos al Centro de administración de Exchange (EAC), donde pueden administrar la configuración específica de Exchange Online. Para obtener más información sobre cómo garantizar un funcionamiento correcto con el Centro de administración de Office 365, vea el vídeo siguiente: [Presentación de Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span><span class="sxs-lookup"><span data-stu-id="f031e-p104">The Microsoft Office 365 admin center is the web portal from which each company's service administrator can manage user accounts and settings for each of the Office 365 services to which they subscribe. From within the Office 365 admin center, administrators can follow links to the Exchange admin center (EAC), where they can manage settings specific to Exchange Online. For more information about getting up and running using the Office 365 admin center, see the following video: [Introducing Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span></span>
  
### <a name="exchange-admin-center"></a><span data-ttu-id="f031e-125">Centro de administración de Exchange</span><span class="sxs-lookup"><span data-stu-id="f031e-125">Exchange admin center</span></span>
<span data-ttu-id="f031e-126"><a name="BKMK_ExchangeAdministrationCenter"> </a></span><span class="sxs-lookup"><span data-stu-id="f031e-126"></span></span>

<span data-ttu-id="f031e-p105">Exchange Online ofrece una consola de administración unificada exclusiva que brinda facilidad de uso y está optimizada para administrar implementaciones locales, en línea o híbridas. El Centro de administración de Exchange (EAC) es donde los administradores modifican las configuraciones específicas de Exchange.</span><span class="sxs-lookup"><span data-stu-id="f031e-p105">Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.</span></span>
  
<span data-ttu-id="f031e-129">Para obtener más información sobre cómo usar el EAC para administrar Exchange Online, vea el [Centro de administración de Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271807).</span><span class="sxs-lookup"><span data-stu-id="f031e-129">For more information about how to use the EAC to manage Exchange Online, see [Exchange admin center](https://go.microsoft.com/fwlink/p/?LinkId=271807).</span></span>
  
### <a name="remote-windows-powershell-for-exchange-online"></a><span data-ttu-id="f031e-130">Windows PowerShell remoto para Exchange Online</span><span class="sxs-lookup"><span data-stu-id="f031e-130">Remote Windows PowerShell for Exchange Online</span></span>
<span data-ttu-id="f031e-131"><a name="BKMK_RemoteWindowsPowerShell"> </a></span><span class="sxs-lookup"><span data-stu-id="f031e-131"></span></span>

<span data-ttu-id="f031e-p106">Con Windows PowerShell remoto, los administradores pueden conectarse a Exchange Online para realizar tareas de administración que no estén disponibles en el EAC o no se puedan completar fácilmente. Estas acciones pueden ser automatizar tareas repetitivas, extraer datos para informes personalizados, personalizar directivas y conectar Exchange Online a los procesos e infraestructuras existentes. Para obtener más información, vea [Conectarse a Exchange Online con PowerShell remoto](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span><span class="sxs-lookup"><span data-stu-id="f031e-p106">Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span></span>
  
<span data-ttu-id="f031e-p107">Exchange Online usa los mismos cmdlets de Windows PowerShell que Exchange Server 2013, aunque algunos comandos y parámetros no están disponibles, ya que estas características no se aplican en Exchange Online. Vea la lista de los cmdlets que se usan con Exchange Online en [Cmdlets de Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span><span class="sxs-lookup"><span data-stu-id="f031e-p107">Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
<span data-ttu-id="f031e-p108">Los administradores no necesitan instalar ninguna herramienta de migración ni administración de Exchange Server para usar Windows PowerShell remoto. Sin embargo, los ordenadores de los administradores deben ejecutar Windows Management Framework 3.0, que incluye Windows PowerShell versión 3 y WinRM 3.0; y Windows .NET Framework 4.5. Estos componentes ya están instalados en ordenadores que ejecutan Windows 8 o Windows Server 2012. Los administradores pueden descargar estos componentes para los ordenadores que ejecutan Windows 7 o Windows Server 2008 R2.</span><span class="sxs-lookup"><span data-stu-id="f031e-p108">Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="f031e-141">Para evitar que se produzcan ataques por denegación de servicio (DoS), solo se pueden tener abiertas tres conexiones de Windows PowerShell a la organización de Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f031e-141">To help prevent denial of service (DoS) attacks, you're limited to three open Windows PowerShell connections to your Exchange Online organization.</span></span> 
  
## <a name="self-service-capabilities-for-exchange-online"></a><span data-ttu-id="f031e-142">Capacidades de autoservicio para Exchange Online</span><span class="sxs-lookup"><span data-stu-id="f031e-142">Self-service capabilities for Exchange Online</span></span>

<span data-ttu-id="f031e-p109">A continuación, se muestran funciones importantes disponibles para administrar Exchange Online con el EAC, Windows PowerShell remoto y otras herramientas. Muchas otras configuraciones también pueden controlarse con estas herramientas, como se describe a lo largo de este documento.</span><span class="sxs-lookup"><span data-stu-id="f031e-p109">Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.</span></span>
  
### <a name="mobile-device-security-policies-for-exchange-online"></a><span data-ttu-id="f031e-145">Directivas de seguridad de dispositivos móviles para Exchange Online</span><span class="sxs-lookup"><span data-stu-id="f031e-145">Mobile device security policies for Exchange Online</span></span>

<span data-ttu-id="f031e-p110">Exchange Online admite las mismas directivas de ActiveSync para dispositivos móviles que Exchange Server 2013. Los administradores pueden aplicar y personalizar estas directivas de seguridad para grupos y usuarios concretos usando el EAC o Windows PowerShell remoto.</span><span class="sxs-lookup"><span data-stu-id="f031e-p110">Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.</span></span>
  
### <a name="message-tracking-for-exchange-online"></a><span data-ttu-id="f031e-148">Seguimiento de mensajes para Exchange Online</span><span class="sxs-lookup"><span data-stu-id="f031e-148">Message tracking for Exchange Online</span></span>

<span data-ttu-id="f031e-149">El seguimiento de mensajes mediante la característica de informes de entrega se describe en el siguiente tema: [Herramientas de resolución de problemas y características de informes](reporting-features-and-troubleshooting-tools.md).</span><span class="sxs-lookup"><span data-stu-id="f031e-149">Message tracking via the Delivery Reports feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
### <a name="usage-reporting-for-exchange-online"></a><span data-ttu-id="f031e-150">Informes de uso para Exchange Online</span><span class="sxs-lookup"><span data-stu-id="f031e-150">Usage reporting for Exchange Online</span></span>

<span data-ttu-id="f031e-p111">Los administradores pueden usar Windows PowerShell remoto para recuperar la información sobre qué contactos de sus organizaciones usan el servicio de Exchange Online. La información disponible incluye:</span><span class="sxs-lookup"><span data-stu-id="f031e-p111">Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:</span></span>
  
- <span data-ttu-id="f031e-153">Visualización del tamaño del buzón para cada usuario de la organización.</span><span class="sxs-lookup"><span data-stu-id="f031e-153">Showing the mailbox size for each user in the organization.</span></span>
    
- <span data-ttu-id="f031e-154">Visualización de los permisos personalizados que se establecen en los buzones, como acceso delegado.</span><span class="sxs-lookup"><span data-stu-id="f031e-154">Displaying custom permissions that are set on mailboxes, such as delegate access.</span></span>
    
- <span data-ttu-id="f031e-155">Extracción de datos sobre el acceso a dispositivos móviles, como qué usuarios se conectan mediante Exchange ActiveSync, qué dispositivos están usando y cuándo fue la última vez que se conectaron.</span><span class="sxs-lookup"><span data-stu-id="f031e-155">Extracting data about mobile device access, such as which users are connecting through Exchange ActiveSync, what devices they are using, and when they last connected.</span></span>
    
<span data-ttu-id="f031e-p112">Los cmdlets de Windows PowerShell remoto que comienzan con "get-" pueden buscar los datos en el sistema de Exchange Online. Los administradores pueden exportar esta información desde Windows PowerShell en formato .csv para la generación de informes o análisis avanzados.</span><span class="sxs-lookup"><span data-stu-id="f031e-p112">Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.</span></span>
  
<span data-ttu-id="f031e-158">Para obtener más información sobre los cmdlets de Windows PowerShell que se usan con Exchange Online, vea [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span><span class="sxs-lookup"><span data-stu-id="f031e-158">For more information about Windows PowerShell cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
### <a name="auditing-for-exchange-online"></a><span data-ttu-id="f031e-159">Auditoría para Exchange Online</span><span class="sxs-lookup"><span data-stu-id="f031e-159">Auditing for Exchange Online</span></span>

<span data-ttu-id="f031e-160">La característica de registro de auditoría se describe en el siguiente tema: [Herramientas de resolución de problemas y características de informes](reporting-features-and-troubleshooting-tools.md).</span><span class="sxs-lookup"><span data-stu-id="f031e-160">The audit logging feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
## <a name="service-and-product-upgrades-for-exchange-online"></a><span data-ttu-id="f031e-161">Actualizaciones de productos y servicios para Exchange Online</span><span class="sxs-lookup"><span data-stu-id="f031e-161">Service and product upgrades for Exchange Online</span></span>

<span data-ttu-id="f031e-p113">Los clientes de Exchange Online obtienen los beneficios de actualizaciones periódicas hasta la tecnología más reciente de Exchange, incluidas las nuevas versiones de Exchange Server. Estas actualizaciones están disponibles sin coste adicional y garantizan que los clientes siempre usen el software más reciente de Exchange.</span><span class="sxs-lookup"><span data-stu-id="f031e-p113">Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.</span></span>
  
<span data-ttu-id="f031e-164">Cuando Microsoft lanza una versión principal de Exchange, los clientes tienen hasta 12 meses para actualizar su servicio a la nueva versión.</span><span class="sxs-lookup"><span data-stu-id="f031e-164">After a major version of Exchange is released by Microsoft, customers have up to 12 months to upgrade their service to the new release.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="f031e-165">Disponibilidad de características</span><span class="sxs-lookup"><span data-stu-id="f031e-165">Feature Availability</span></span>

<span data-ttu-id="f031e-166">Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [Descripción del servicio Exchange Online](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="f031e-166">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

