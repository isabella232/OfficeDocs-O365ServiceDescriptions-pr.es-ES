---
title: Administración y configuración de Exchange Online
ms.author: sharik
author: skjerland
manager: mnirkhe
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
description: En esta sección se describen los controles de administración y la compatibilidad que hay disponibles para personalizar la configuración de Exchange Online y mantener el entorno de Exchange online en funcionamiento, en ejecución y actualizado de la organización. Incluye información sobre las herramientas de administración de autoservicio y las capacidades disponibles para las organizaciones, las responsabilidades de administración de Microsoft y los compromisos de rendimiento, además de las actualizaciones de productos y servicios.
ms.openlocfilehash: eae4fc583661025fdc509d4b36cf0cb46353bed6
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776491"
---
# <a name="exchange-online-setup-and-administration"></a>Administración y configuración de Exchange Online

En esta sección se describen los controles de administración y la compatibilidad que hay disponibles para personalizar la configuración de Exchange Online y mantener el entorno de Exchange online en funcionamiento, en ejecución y actualizado de la organización. Incluye información sobre las herramientas de administración de autoservicio y las capacidades disponibles para las organizaciones, las responsabilidades de administración de Microsoft y los compromisos de rendimiento, además de las actualizaciones de productos y servicios.
  
## <a name="self-service-administration-tools"></a>Herramientas de administración de autoservicio

Si bien Microsoft controla directamente todos los centros de datos de Exchange Online y es responsable del rendimiento general del sistema, puede controlar solo una parte de los elementos que se combinan para ofrecer una experiencia completa a los usuarios de Office 365. Las organizaciones son responsables de las conexiones de red a los centros de datos, la red de área extensa (WAN) del cliente y las redes de área local (LAN) del cliente. Además, están a cargo de los dispositivos de usuario y de su configuración. También son responsables del mantenimiento de las licencias necesarias por usuario para todas las características deseadas, entre ellas, la capacidad de administrar esas características siempre que el usuario necesite acceso a la característica.
  
Por lo tanto, Exchange Online ofrece a los administradores de clientes las siguientes herramientas, descritas a continuación, a fin de administrar una variedad de tareas relacionadas con la mensajería:
  
- [Portal de Microsoft Office 365](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [Centro de administración de 365 de Microsoft](#microsoft-365-admin-center)
    
- [Centro de administración de Exchange](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [Windows PowerShell remoto para Exchange Online](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a>Portal de Microsoft Office 365
<a name="BKMK_MicrosoftOnlineServicesPortal"> </a>

El portal de Microsoft Office 365 en [https://portal.office.com](https://portal.office.com) es el sitio web a través del cual los administradores y los socios compran y administran los servicios de Office 365 y donde los usuarios tienen acceso a las herramientas de colaboración de Office 365 y las utilizan.
  
### <a name="microsoft-365-admin-center"></a>Centro de administración de 365 de Microsoft
<a name="BKMK_Office365admincenterl"> </a>

El centro de administración de 365 de Microsoft es el portal web desde el que el administrador de servicios de cada empresa puede administrar la configuración y las cuentas de usuario para cada uno de los servicios de Office 365 a los que se suscriben. Desde el centro de administración de 365 de Microsoft, los administradores pueden seguir los vínculos al centro de administración de Exchange (EAC), donde pueden administrar la configuración específica de Exchange Online. Para obtener más información acerca de cómo empezar a usar el centro de administración de Microsoft 365, consulte el siguiente vídeo: [Introducción a Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).
  
### <a name="exchange-admin-center"></a>Centro de administración de Exchange
<a name="BKMK_ExchangeAdministrationCenter"> </a>

Exchange Online ofrece una consola de administración unificada exclusiva que brinda facilidad de uso y está optimizada para administrar implementaciones locales, en línea o híbridas. El Centro de administración de Exchange (EAC) es donde los administradores modifican las configuraciones específicas de Exchange.
  
Para obtener más información sobre cómo usar el EAC para administrar Exchange Online, vea el [Centro de administración de Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271807).
  
### <a name="remote-windows-powershell-for-exchange-online"></a>Windows PowerShell remoto para Exchange Online
<a name="BKMK_RemoteWindowsPowerShell"> </a>

Con Windows PowerShell remoto, los administradores pueden conectarse a Exchange Online para realizar tareas de administración que no estén disponibles en el EAC o no se puedan completar fácilmente. Estas acciones pueden ser automatizar tareas repetitivas, extraer datos para informes personalizados, personalizar directivas y conectar Exchange Online a los procesos e infraestructuras existentes. Para obtener más información, vea [Conectarse a Exchange Online con PowerShell remoto](https://go.microsoft.com/fwlink/p/?LinkId=308994).
  
Exchange Online usa los mismos cmdlets de Windows PowerShell que Exchange Server 2013, aunque algunos comandos y parámetros no están disponibles, ya que estas características no se aplican en Exchange Online. Vea la lista de los cmdlets que se usan con Exchange Online en [Cmdlets de Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
Los administradores no necesitan instalar ninguna herramienta de migración ni administración de Exchange Server para usar Windows PowerShell remoto. Sin embargo, los ordenadores de los administradores deben ejecutar Windows Management Framework 3.0, que incluye Windows PowerShell versión 3 y WinRM 3.0; y Windows .NET Framework 4.5. Estos componentes ya están instalados en ordenadores que ejecutan Windows 8 o Windows Server 2012. Los administradores pueden descargar estos componentes para los ordenadores que ejecutan Windows 7 o Windows Server 2008 R2.
  
> [!IMPORTANT]
> Para evitar que se produzcan ataques por denegación de servicio (DoS), solo se pueden tener abiertas tres conexiones de Windows PowerShell a la organización de Exchange Online. 
  
## <a name="self-service-capabilities-for-exchange-online"></a>Capacidades de autoservicio para Exchange Online

A continuación, se muestran funciones importantes disponibles para administrar Exchange Online con el EAC, Windows PowerShell remoto y otras herramientas. Muchas otras configuraciones también pueden controlarse con estas herramientas, como se describe a lo largo de este documento.
  
### <a name="mobile-device-security-policies-for-exchange-online"></a>Directivas de seguridad de dispositivos móviles para Exchange Online

Exchange Online admite las mismas directivas de ActiveSync para dispositivos móviles que Exchange Server 2013. Los administradores pueden aplicar y personalizar estas directivas de seguridad para grupos y usuarios concretos usando el EAC o Windows PowerShell remoto.
  
### <a name="message-tracking-for-exchange-online"></a>Seguimiento de mensajes para Exchange Online

El seguimiento de mensajes mediante la característica de informes de entrega se describe en el siguiente tema: [Herramientas de resolución de problemas y características de informes](reporting-features-and-troubleshooting-tools.md).
  
### <a name="usage-reporting-for-exchange-online"></a>Informes de uso para Exchange Online

Los administradores pueden usar Windows PowerShell remoto para recuperar la información sobre qué contactos de sus organizaciones usan el servicio de Exchange Online. La información disponible incluye:
  
- Visualización del tamaño del buzón para cada usuario de la organización.
    
- Visualización de los permisos personalizados que se establecen en los buzones, como acceso delegado.
    
- Extracción de datos sobre el acceso a dispositivos móviles, como qué usuarios se conectan mediante Exchange ActiveSync, qué dispositivos están usando y cuándo fue la última vez que se conectaron.
    
Los cmdlets de Windows PowerShell remoto que comienzan con "get-" pueden buscar los datos en el sistema de Exchange Online. Los administradores pueden exportar esta información desde Windows PowerShell en formato .csv para la generación de informes o análisis avanzados.
  
Para obtener más información sobre los cmdlets de Windows PowerShell que se usan con Exchange Online, vea [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
### <a name="auditing-for-exchange-online"></a>Auditoría para Exchange Online

La característica de registro de auditoría se describe en el siguiente tema: [Herramientas de resolución de problemas y características de informes](reporting-features-and-troubleshooting-tools.md).
  
## <a name="service-and-product-upgrades-for-exchange-online"></a>Actualizaciones de productos y servicios para Exchange Online

Los clientes de Exchange Online obtienen los beneficios de actualizaciones periódicas hasta la tecnología más reciente de Exchange, incluidas las nuevas versiones de Exchange Server. Estas actualizaciones están disponibles sin coste adicional y garantizan que los clientes siempre usen el software más reciente de Exchange.
  
Cuando Microsoft lanza una versión principal de Exchange, los clientes tienen hasta 12 meses para actualizar su servicio a la nueva versión.
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [Descripción del servicio Exchange Online](exchange-online-service-description.md).
  

