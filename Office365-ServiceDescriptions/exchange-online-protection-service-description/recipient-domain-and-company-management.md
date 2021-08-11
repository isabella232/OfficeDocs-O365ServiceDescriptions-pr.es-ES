---
title: Administración de destinatarios, dominios y empresas en Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Lea este artículo para obtener información sobre la administración de destinatarios, dominios y empresas en Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: fc2b9f6fbd797e8e765758c11c486ce6afaba5a5855602e79f5418c1e80bb1ea
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/06/2021
ms.locfileid: "54664063"
---
# <a name="recipient-domain-and-company-management-in-exchange-online-protection"></a>Administración de destinatarios, dominios y empresas en Exchange Online Protection

Microsoft Exchange Online Protection (EOP) ofrece varios medios para administrar la información de su destinatario, dominio y empresa. Como administrador, puede realizar determinadas tareas de administración en el Centro de administración de Exchange (EAC) y comprobar otras tareas de administración realizadas en el Centro de administración de Microsoft 365.
  
¿Busca información sobre todas las características de EOP? Vea la [Exchange Online Protection descripción del servicio .](exchange-online-protection-service-description.md)
  
## <a name="mail-recipients"></a>Mail recipients

Los destinatarios de correo se clasifican como grupos o usuarios de correo y se pueden administrar mediante la sincronización de directorios, directamente en el EAC o mediante el modo remoto de Windows PowerShell. Si va a administrar los destinatarios localmente, debe ejecutar la sincronización de directorios para que los destinatarios de correo se reflejen en el EAC. Los usuarios administrados únicamente en el Centro de administración de Microsoft 365 no se pueden ver en el EAC, pero se pueden agregar o quitar de la pertenencia a un grupo de roles de administrador en el EAC. Para más información sobre los destinatarios en EOP, vea [Administrar destinatarios en EOP](/microsoft-365/security/office-365-security/manage-recipients-in-eop).
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions

En EOP, solo puede configurar roles administrativos. Puede agregar y quitar usuarios de los grupos de roles administrativos predeterminados directamente en el EAC, pero no puede personalizar el control de acceso basado en funciones (RBAC). Para más información, vea [Administrar permisos de grupos de roles de administración en EOP](/microsoft-365/security/office-365-security/manage-admin-role-group-permissions-in-eop).
  
## <a name="domain-management"></a>Administración de dominios

Los dominios administrados son dominios que están protegidos por EOP. En el EAC, se pueden ver los dominios administrados y editar los tipos de dominio. El aprovisionamiento y la administración de dominios se producen en Centro de administración de Microsoft 365 y los cambios se reflejan en el EAC. Para obtener más información, vea [Administrar dominios aceptados en EOP](/microsoft-365/security/office-365-security/exchange-online-protection-overview).
  
## <a name="match-subdomains"></a>Subdominios coincidentes

En EOP, puede habilitar el flujo del correo para los subdominios de un dominio administrado. Para obtener más información, vea [Habilitar el flujo de correo electrónico para los subdominios en EOP](/microsoft-365/security/office-365-security/mail-flow-in-eop). 
  
## <a name="directory-based-edge-blocking-dbeb"></a>Bloqueo perimetral basado en directorios (DBEB)

La característica Bloqueo perimetral basado en directorios permite rechazar mensajes para destinatarios no válidos en el perímetro de la red de servicio. DBEB permite a los administradores agregar destinatarios habilitados para correo a Microsoft y bloquear todos los mensajes enviados a direcciones de correo electrónico que no están presentes en Microsoft. Si un mensaje se envía a una dirección de correo electrónico válida presente en Microsoft, el mensaje continúa a través del resto de las capas de filtrado del servicio (antimalware, antispam, reglas de transporte). Si la dirección no se encuentra, el servicio bloquea el mensaje incluso antes de que se produzca el filtrado y se envía un informe de no entrega (NDR) al remitente informándole que su mensaje no se entregó. 
  
Para habilitar DBEB es necesario realizar una configuración de usuario y de dominio. Para obtener más información, vea [Usar bloqueo perimetral basado en directorios para rechazar mensajes enviados a destinatarios no válidos](/exchange/mail-flow-best-practices/use-directory-based-edge-blocking).
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, opciones independientes y soluciones locales, [vea Exchange Online Protection descripción del servicio](exchange-online-protection-service-description.md).