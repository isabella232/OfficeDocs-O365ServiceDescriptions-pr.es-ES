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
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/07/2019
ms.locfileid: "30466907"
---
# <a name="recipient-domain-and-company-management"></a><span data-ttu-id="f7838-104">Administración de destinatarios, dominios e información de la compañía</span><span class="sxs-lookup"><span data-stu-id="f7838-104">Recipient, Domain, and Company Management</span></span>

<span data-ttu-id="f7838-105">Microsoft Exchange Online Protection (EOP) ofrece varios medios para administrar la información de destinatarios, dominios y compañías.</span><span class="sxs-lookup"><span data-stu-id="f7838-105">Microsoft Exchange Online Protection (EOP) offers several means of managing your recipient, domain, and company information.</span></span> <span data-ttu-id="f7838-106">Como administrador, puede realizar ciertas tareas de administración dentro del centro de administración de Exchange (EAC) y comprobar otras tareas de administración realizadas en el centro de administración de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f7838-106">As an administrator, you can perform certain management tasks within the Exchange admin center (EAC), and verify other management tasks performed in the Microsoft 365 admin center.</span></span>
  
<span data-ttu-id="f7838-107">¿Busca información sobre todas las características de EOP?</span><span class="sxs-lookup"><span data-stu-id="f7838-107">Looking for information about all EOP features?</span></span> <span data-ttu-id="f7838-108">Vea [Descripción de servicio Protección en línea de Exchange](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="f7838-108">See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="mail-recipients"></a><span data-ttu-id="f7838-109">Mail recipients</span><span class="sxs-lookup"><span data-stu-id="f7838-109">Mail recipients</span></span>
<span data-ttu-id="f7838-110"><a name="BKMK_mailrecipients"> </a></span><span class="sxs-lookup"><span data-stu-id="f7838-110"></span></span>

<span data-ttu-id="f7838-111">Los destinatarios de correo se clasifican como grupos o usuarios de correo y se pueden administrar mediante la sincronización de directorios, directamente en el EAC o mediante el modo remoto de Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="f7838-111">Mail recipients are categorized as mail users or groups and can be managed through directory synchronization, directly in the EAC, or via remote Windows PowerShell.</span></span> <span data-ttu-id="f7838-112">Si va a administrar los destinatarios localmente, debe ejecutar la sincronización de directorios para que los destinatarios de correo se reflejen en el EAC.</span><span class="sxs-lookup"><span data-stu-id="f7838-112">If you're managing your recipients on-premises, you must run directory synchronization in order for your mail recipients to be reflected in the EAC.</span></span> <span data-ttu-id="f7838-113">Los usuarios administrados únicamente en el centro de administración de Microsoft 365 no se pueden ver en el EAC, pero se pueden agregar o quitar de la pertenencia a un grupo de roles de administrador en el EAC.</span><span class="sxs-lookup"><span data-stu-id="f7838-113">Users managed solely in the Microsoft 365 admin center aren't viewable in the EAC, but they can be added to or removed from membership in an administrator role group in the EAC.</span></span> <span data-ttu-id="f7838-114">Para más información sobre los destinatarios en EOP, vea [Administrar destinatarios en EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span><span class="sxs-lookup"><span data-stu-id="f7838-114">For more information about recipients in EOP, see [Recipients in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span></span>
  
## <a name="admin-role-group-permissions"></a><span data-ttu-id="f7838-115">Admin role group permissions</span><span class="sxs-lookup"><span data-stu-id="f7838-115">Admin role group permissions</span></span>
<span data-ttu-id="f7838-116"><a name="BKMK_adminrolegrouppermissions"> </a></span><span class="sxs-lookup"><span data-stu-id="f7838-116"></span></span>

<span data-ttu-id="f7838-p105">En EOP, solo puede configurar roles administrativos. Puede agregar y quitar usuarios de los grupos de roles administrativos predeterminados directamente en el EAC, pero no puede personalizar el control de acceso basado en funciones (RBAC). Para más información, vea [Administrar permisos de grupos de roles de administración en EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span><span class="sxs-lookup"><span data-stu-id="f7838-p105">In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span></span>
  
## <a name="domain-management"></a><span data-ttu-id="f7838-121">Domain management</span><span class="sxs-lookup"><span data-stu-id="f7838-121">Domain management</span></span>
<span data-ttu-id="f7838-122"><a name="BKMK_domainmanagement"> </a></span><span class="sxs-lookup"><span data-stu-id="f7838-122"></span></span>

<span data-ttu-id="f7838-123">Los dominios administrados son dominios que están protegidos por EOP.</span><span class="sxs-lookup"><span data-stu-id="f7838-123">Managed domains are domains that are protected by EOP.</span></span> <span data-ttu-id="f7838-124">En el EAC, se pueden ver los dominios administrados y editar los tipos de dominio.</span><span class="sxs-lookup"><span data-stu-id="f7838-124">Managed domains can be viewed and domain types can be edited in the EAC.</span></span> <span data-ttu-id="f7838-125">El aprovisionamiento y la administración de dominios se produce en el centro de administración de Microsoft 365 y los cambios se reflejan en el EAC.</span><span class="sxs-lookup"><span data-stu-id="f7838-125">Domain provisioning and management occurs in the Microsoft 365 admin center and changes are reflected in the EAC.</span></span> <span data-ttu-id="f7838-126">Para obtener más información, vea [Administrar dominios aceptados en EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span><span class="sxs-lookup"><span data-stu-id="f7838-126">For more information, see [View or Edit Managed Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span></span>
  
## <a name="match-subdomains"></a><span data-ttu-id="f7838-127">Subdominios coincidentes</span><span class="sxs-lookup"><span data-stu-id="f7838-127">Match subdomains</span></span>
<span data-ttu-id="f7838-128"><a name="BKMK_EOP_Match_Subdomains"> </a></span><span class="sxs-lookup"><span data-stu-id="f7838-128"></span></span>

<span data-ttu-id="f7838-p107">En EOP, puede habilitar el flujo del correo para los subdominios de un dominio administrado. Para obtener más información, vea [Habilitar el flujo de correo electrónico para los subdominios en EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span><span class="sxs-lookup"><span data-stu-id="f7838-p107">In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span></span> 
  
## <a name="directory-based-edge-blocking-dbeb"></a><span data-ttu-id="f7838-131">Directory Based Edge Blocking (DBEB)</span><span class="sxs-lookup"><span data-stu-id="f7838-131">Directory Based Edge Blocking (DBEB)</span></span>
<span data-ttu-id="f7838-132"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="f7838-132"></span></span>

<span data-ttu-id="f7838-p108">La característica Bloqueo perimetral basado en directorios permite rechazar mensajes para destinatarios no válidos en el perímetro de la red de servicio. El DBEB permite que los administradores agreguen destinatarios habilitados para correo a Office 365 y bloqueen todos los mensajes enviados a direcciones de correo electrónico que no están presentes en Office 365. Si un mensaje se envía a una dirección de correo electrónico válida que está presente en Office 365, el mensaje continúa a través de las demás capas de filtrado del servicio (antimalware, correo no deseado, reglas de transporte). Si la dirección no se encuentra, el servicio bloquea el mensaje incluso antes de que se produzca el filtrado y se envía un informe de no entrega (NDR) al remitente informándole que su mensaje no se entregó.</span><span class="sxs-lookup"><span data-stu-id="f7838-p108">The Directory Based Edge Blocking feature lets you reject messages for invalid recipients at the service network perimeter. DBEB lets admins add mail-enabled recipients to Office 365 and block all messages sent to email addresses that aren't present in Office 365. If a message is sent to a valid email address present in Office 365, the message continues through the rest of the service filtering layers (anti-malware, anti-spam, transport rules). If the address is not present, the service blocks the message before filtering even occurs, and a non-delivery report (NDR) is sent to the sender informing them that their message was not delivered.</span></span> 
  
<span data-ttu-id="f7838-p109">Para habilitar DBEB es necesario realizar una configuración de usuario y de dominio. Para obtener más información, vea [Usar bloqueo perimetral basado en directorios para rechazar mensajes enviados a destinatarios no válidos](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span><span class="sxs-lookup"><span data-stu-id="f7838-p109">Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="f7838-139">Disponibilidad de características</span><span class="sxs-lookup"><span data-stu-id="f7838-139">Feature Availability</span></span>
<span data-ttu-id="f7838-140"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="f7838-140"></span></span>

<span data-ttu-id="f7838-141">Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [Descripción de servicio Protección en línea de Exchange](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="f7838-141">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  

