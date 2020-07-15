---
title: Administración y configuración de Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: En este artículo se describen los controles de administración y la compatibilidad que hay disponibles para personalizar la configuración de Exchange Online y mantener el entorno de Exchange online en funcionamiento, en ejecución y actualizado de la organización. Incluye información sobre las herramientas de administración de autoservicio y las capacidades disponibles para las organizaciones, las responsabilidades de administración de Microsoft y los compromisos de rendimiento, además de las actualizaciones de productos y servicios.
ms.openlocfilehash: 19ec50b3f502ee111de05e1a115d17f16fec3569
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45133005"
---
# <a name="exchange-online-setup-and-administration"></a>Administración y configuración de Exchange Online

En este artículo se describen los controles de administración y la compatibilidad que hay disponibles para personalizar la configuración de Exchange Online y mantener el entorno de Exchange online en funcionamiento, en ejecución y actualizado de la organización. Incluye información sobre las herramientas de administración de autoservicio y las capacidades disponibles para las organizaciones, las responsabilidades de administración de Microsoft y los compromisos de rendimiento, además de las actualizaciones de productos y servicios.
  
## <a name="self-service-administration-tools"></a>Herramientas de administración de autoservicio

Aunque Microsoft controla directamente todos los centros de datos de Exchange Online y es responsable del rendimiento general del sistema, puede controlar sólo una parte de los elementos que se combinan para proporcionar la experiencia total para los usuarios. Las organizaciones son responsables de las conexiones de red a los centros de datos, la red de área extensa (WAN) del cliente y las redes de área local (LAN) del cliente. Además, están a cargo de los dispositivos de usuario y de su configuración.También son responsables del mantenimiento de las licencias necesarias por usuario para todas las características deseadas, entre ellas, la capacidad de administrar esas características siempre que el usuario necesite acceso a la característica.
  
Por lo tanto, Exchange Online ofrece a los administradores de clientes las siguientes herramientas, descritas a continuación, a fin de administrar una variedad de tareas relacionadas con la mensajería:
  
- [Portal de Microsoft Office 365](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [Centro de administración de Microsoft 365](#microsoft-365-admin-center)
    
- [Centro de administración de Exchange](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [Windows PowerShell remoto para Exchange Online](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a>Portal de Microsoft Office 365

El portal de Microsoft Office 365 en [https://portal.office.com](https://portal.office.com) es el sitio web a través del cual los administradores y los socios compran y administran los servicios de Office 365 y donde los usuarios tienen acceso a las herramientas de colaboración de Office 365 y las utilizan.
  
### <a name="microsoft-365-admin-center"></a>Centro de administración de Microsoft 365

El centro de administración de 365 de Microsoft es el portal web desde el que el administrador de servicios de cada empresa puede administrar la configuración y las cuentas de usuario para cada uno de los servicios de Microsoft a los que se suscriben. Desde el centro de administración de 365 de Microsoft, los administradores pueden seguir los vínculos al centro de administración de Exchange (EAC), donde pueden administrar la configuración específica de Exchange Online. Para obtener más información acerca de cómo empezar a usar el centro de administración de Microsoft 365, consulte el siguiente vídeo: [Introducción a Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).
  
### <a name="exchange-admin-center"></a>Centro de administración de Exchange

Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.
  
Para obtener más información sobre cómo usar el EAC para administrar Exchange Online, vea el [Centro de administración de Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271807).
  
### <a name="remote-windows-powershell-for-exchange-online"></a>Windows PowerShell remoto para Exchange Online

Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).
  
Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.
  
> [!IMPORTANT]
> Para evitar que se produzcan ataques por denegación de servicio (DoS), solo se pueden tener abiertas tres conexiones de Windows PowerShell a la organización de Exchange Online. 
  
## <a name="self-service-capabilities-for-exchange-online"></a>Capacidades de autoservicio para Exchange Online

Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.
  
### <a name="mobile-device-security-policies-for-exchange-online"></a>Directivas de seguridad de dispositivos móviles para Exchange Online

Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.
  
### <a name="message-tracking-for-exchange-online"></a>Seguimiento de mensajes para Exchange Online

El seguimiento de mensajes mediante la característica de informes de entrega se describe en el siguiente tema: [herramientas de solución de problemas y características de informes](reporting-features-and-troubleshooting-tools.md).
  
### <a name="usage-reporting-for-exchange-online"></a>Informes de uso para Exchange Online

Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:
  
- Visualización del tamaño del buzón para cada usuario de la organización.
    
- Visualización de los permisos personalizados que se establecen en los buzones, como acceso delegado.
    
- Extracción de datos sobre el acceso a dispositivos móviles, como qué usuarios se conectan mediante Exchange ActiveSync, qué dispositivos están usando y cuándo fue la última vez que se conectaron.
    
Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.
  
Para obtener más información sobre los cmdlets de Windows PowerShell que se usan con Exchange Online, vea [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
### <a name="auditing-for-exchange-online"></a>Auditoría para Exchange Online

La característica de registro de auditoría se describe en el siguiente tema: [herramientas de solución de problemas y características de informes](reporting-features-and-troubleshooting-tools.md).
  
## <a name="service-and-product-upgrades-for-exchange-online"></a>Actualizaciones de productos y servicios para Exchange Online

Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.
  
Cuando Microsoft lanza una versión principal de Exchange, los clientes tienen hasta 12 meses para actualizar su servicio a la nueva versión.
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, las opciones independientes y las soluciones locales, consulte [Exchange Online Service Description](exchange-online-service-description.md).
  