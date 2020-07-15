---
title: Permisos
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013.
ms.openlocfilehash: 0593c98857a7ce0c487c628018097395d7a5fe50
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132694"
---
# <a name="permissions"></a>Permisos

Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013. 
  
At its highest level, RBAC is made up of management roles, management role groups, and management role assignment policies. The following sections provide more information about each RBAC component.
  
Para obtener más información sobre el modelo de permisos RBAC que se usa en Exchange Online, vea [Permisos](https://go.microsoft.com/fwlink/p/?LinkId=271935).
  
## <a name="role-based-permissions"></a>Permisos basados en roles

In Exchange Online, the permissions that you grant to administrators and users are based on management roles. A role defines the set of tasks that an administrator or user can perform. For example, a management role called  `Mail Recipients` defines the tasks that someone can perform on a set of mailboxes, contacts, and distribution groups. When a role is assigned to an administrator or user, that person is granted the permissions provided by the role. 
  
Existen dos tipos de funciones: las funciones administrativas y las funciones de usuario final:
  
- **Funciones administrativas** Estas funciones contienen permisos que se pueden asignar a los administradores o usuarios especialistas mediante grupos de funciones que administran una parte de la organización de Exchange Online, como los destinatarios, los servidores o las bases de datos. 
    
- **Roles de usuario final** Estos roles, asignados mediante directivas de asignación de roles, permiten a los usuarios administrar aspectos de sus propios buzones y grupos de distribución de los que son propietarios. Las funciones de usuario final empiezan por el prefijo  `My`.
    
Roles give administrators and users permissions to perform tasks by making cmdlets available to those who are assigned the roles. Because the Exchange admin center (EAC) and Exchange Management Shell use cmdlets to manage Exchange Online, granting access to a cmdlet gives the administrator or user permission to perform the task in each of the Exchange Online management interfaces.
  
The role-based permissions for Microsoft Online Services overlap with those of Exchange Online RBAC in two ways. First, users who are Global Administrators or Service Administrators in Microsoft Online are automatically assigned to the Organization Management role group in Exchange Online. Second, users who are Help Desk Administrators in Microsoft Online are automatically assigned to the Help Desk role group in Exchange Online. Otherwise, the two security models are managed separately.
  
> [!IMPORTANT]
> Algunas funciones disponibles en la versión local de Microsoft Exchange Server 2013 podrían no estar disponibles en Exchange Online. 
  
Para obtener más información sobre permisos en Exchange Online, vea [Permisos](https://go.microsoft.com/fwlink/p/?LinkId=271936).
  
## <a name="role-groups"></a>Grupos de funciones

Los grupos de funciones de administración asocian las funciones de administración a un grupo de administradores o usuarios especialistas. Los administradores administran una amplia organización de Exchange Online o configuración de destinatarios. Los usuarios especialistas administran las características específicas de Exchange Online, como el cumplimiento, o podrían tener capacidades de administración limitadas, como los miembros de asistencia, pero no cuentan con derechos administrativos amplios. Por lo general, los grupos de roles asocian roles de administración administrativos que permiten a los administradores y usuarios especialistas administrar la configuración de la organización y los destinatarios. Por ejemplo, con los grupos de funciones se controla si los administradores pueden administrar a los destinatarios o utilizar características de detección de buzones. 
  
> [!IMPORTANT]
> Algunos grupos de funciones disponibles en la versión local de Microsoft Exchange Server 2013 podrían no estar disponibles en Exchange Online. 
  
Para obtener más información sobre grupos de roles, vea [Grupos de roles y directivas de asignación de roles](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="role-assignment-policies"></a>Directivas de asignación de funciones

Management role assignment policies associate end-user management roles to users. Role assignment policies consist of roles that control what users can do with their mailboxes or distribution groups. These roles don't allow management of features that aren't directly associated with the user. When you create a role assignment policy, you define everything a user can do with his or her mailbox. For example, a role assignment policy might allow a user to set the display name, set up voice mail, and configure Inbox rules. Another role assignment policy might allow a user to change the address, use text messaging, and set up distribution groups. Every user with an Exchange Online mailbox, including administrators, is given a role assignment policy by default. You can decide which role assignment policy should be assigned by default, choose what the default role assignment policy should include, override the default for certain mailboxes, or not assign any role assignment policies by default.
  
> [!IMPORTANT]
> Algunas asignaciones de funciones disponibles en la versión local de Microsoft Exchange Server 2013 podrían no estar disponibles en Exchange Online. 
  
Para obtener más información sobre políticas de asignación de roles, vea [Grupos de roles y directivas de asignación de roles](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, las opciones independientes y las soluciones locales, consulte [Exchange Online Service Description](exchange-online-service-description.md).
  

