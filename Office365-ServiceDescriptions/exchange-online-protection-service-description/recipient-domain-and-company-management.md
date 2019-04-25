---
title: Administración de destinatarios, dominios e información de la compañía
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Microsoft Exchange Online Protection (EOP) ofrece varios medios para administrar la información de destinatarios, dominios y compañías. Como administrador, puede realizar ciertas tareas de administración dentro del centro de administración de Exchange (EAC) y comprobar otras tareas de administración realizadas en el centro de administración de Microsoft 365.
ms.openlocfilehash: ff773ca3e19c9f9419ad907ed102f6af8a3567c2
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246276"
---
# <a name="recipient-domain-and-company-management"></a>Administración de destinatarios, dominios e información de la compañía

Microsoft Exchange Online Protection (EOP) ofrece varios medios para administrar la información de destinatarios, dominios y compañías. Como administrador, puede realizar ciertas tareas de administración dentro del centro de administración de Exchange (EAC) y comprobar otras tareas de administración realizadas en el centro de administración de Microsoft 365.
  
¿Busca información sobre todas las características de EOP? Vea [Descripción de servicio Protección en línea de Exchange](exchange-online-protection-service-description.md).
  
## <a name="mail-recipients"></a>Mail recipients
<a name="BKMK_mailrecipients"> </a>

Los destinatarios de correo se clasifican como grupos o usuarios de correo y se pueden administrar mediante la sincronización de directorios, directamente en el EAC o mediante el modo remoto de Windows PowerShell. Si va a administrar los destinatarios localmente, debe ejecutar la sincronización de directorios para que los destinatarios de correo se reflejen en el EAC. Los usuarios administrados únicamente en el centro de administración de Microsoft 365 no se pueden ver en el EAC, pero se pueden agregar o quitar de la pertenencia a un grupo de roles de administrador en el EAC. Para más información sobre los destinatarios en EOP, vea [Administrar destinatarios en EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions
<a name="BKMK_adminrolegrouppermissions"> </a>

En EOP, solo puede configurar roles administrativos. Puede agregar y quitar usuarios de los grupos de roles administrativos predeterminados directamente en el EAC, pero no puede personalizar el control de acceso basado en funciones (RBAC). Para más información, vea [Administrar permisos de grupos de roles de administración en EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).
  
## <a name="domain-management"></a>Domain management
<a name="BKMK_domainmanagement"> </a>

Los dominios administrados son dominios que están protegidos por EOP. En el EAC, se pueden ver los dominios administrados y editar los tipos de dominio. El aprovisionamiento y la administración de dominios se produce en el centro de administración de Microsoft 365 y los cambios se reflejan en el EAC. Para obtener más información, vea [Administrar dominios aceptados en EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
  
## <a name="match-subdomains"></a>Subdominios coincidentes
<a name="BKMK_EOP_Match_Subdomains"> </a>

En EOP, puede habilitar el flujo del correo para los subdominios de un dominio administrado. Para obtener más información, vea [Habilitar el flujo de correo electrónico para los subdominios en EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213). 
  
## <a name="directory-based-edge-blocking-dbeb"></a>Directory Based Edge Blocking (DBEB)
<a name="BKMK_DBEB"> </a>

La característica Bloqueo perimetral basado en directorios permite rechazar mensajes para destinatarios no válidos en el perímetro de la red de servicio. El DBEB permite que los administradores agreguen destinatarios habilitados para correo a Office 365 y bloqueen todos los mensajes enviados a direcciones de correo electrónico que no están presentes en Office 365. Si un mensaje se envía a una dirección de correo electrónico válida que está presente en Office 365, el mensaje continúa a través de las demás capas de filtrado del servicio (antimalware, correo no deseado, reglas de transporte). Si la dirección no se encuentra, el servicio bloquea el mensaje incluso antes de que se produzca el filtrado y se envía un informe de no entrega (NDR) al remitente informándole que su mensaje no se entregó. 
  
Para habilitar DBEB es necesario realizar una configuración de usuario y de dominio. Para obtener más información, vea [Usar bloqueo perimetral basado en directorios para rechazar mensajes enviados a destinatarios no válidos](https://go.microsoft.com/fwlink/p/?LinkId=390676).
  
## <a name="feature-availability"></a>Disponibilidad de características
<a name="BKMK_DBEB"> </a>

Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [Descripción de servicio Protección en línea de Exchange](exchange-online-protection-service-description.md).
  

