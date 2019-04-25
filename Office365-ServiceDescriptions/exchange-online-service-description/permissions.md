---
title: Permisos
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: Microsoft Exchange Online utiliza el modelo Control de acceso basado en funciones (RBAC) para permitir a los administradores de la organización controlar con precisión lo que pueden hacer los usuarios y los empleados de TI en el servicio. Por ejemplo, si un responsable de cumplimiento debe controlar las solicitudes de búsqueda del buzón, el administrador puede delegar su función administrativa al responsable mediante RBAC. Exchange Online utiliza el mismo marco RBAC que Microsoft Exchange Server 2013.
ms.openlocfilehash: 9f7cad7587d3700971a9cedaf38a20161f203c01
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246356"
---
# <a name="permissions"></a>Permisos

Microsoft Exchange Online utiliza el modelo Control de acceso basado en funciones (RBAC) para permitir a los administradores de la organización controlar con precisión lo que pueden hacer los usuarios y los empleados de TI en el servicio. Por ejemplo, si un responsable de cumplimiento debe controlar las solicitudes de búsqueda del buzón, el administrador puede delegar su función administrativa al responsable mediante RBAC. Exchange Online utiliza el mismo marco RBAC que Microsoft Exchange Server 2013. 
  
En su nivel más alto, RBAC se compone de funciones de administración, grupos de funciones de administración y directivas de asignación de funciones de administración. Las secciones siguientes brindan más información sobre cada componente de RBAC.
  
Para obtener más información sobre el modelo de permisos RBAC que se usa en Exchange Online, vea [Permisos](https://go.microsoft.com/fwlink/p/?LinkId=271935).
  
## <a name="role-based-permissions"></a>Permisos basados en funciones

En Exchange Online, los permisos que concede a los administradores y usuarios se basan en funciones de administración. Una función define el conjunto de tareas que un administrador o usuario puede realizar. Por ejemplo, una función de administración denominada  `Mail Recipients` define las tareas que alguien puede realizar en un conjunto de buzones de correo, contactos y grupos de distribución. Cuando una función se asigna a un administrador o usuario, a dicha persona se conceden los permisos que proporciona la función en cuestión. 
  
Existen dos tipos de funciones: las funciones administrativas y las funciones de usuario final:
  
- **Funciones administrativas** Estas funciones contienen permisos que se pueden asignar a los administradores o usuarios especialistas mediante grupos de funciones que administran una parte de la organización de Exchange Online, como los destinatarios, los servidores o las bases de datos. 
    
- **Funciones de usuario final** Estas funciones, asignadas mediante directivas de asignación de funciones, permiten a los usuarios administrar aspectos de sus propios buzones y de los grupos de distribución de que disponen. Las funciones de usuario final empiezan por el prefijo  `My`.
    
Las funciones conceden a los administradores y usuarios permisos para realizar tareas poniendo cmdlets a disposición de aquellos usuarios que tienen asignadas las funciones en cuestión. Debido a que el Centro de admin. de Exchange (EAC) y el Shell de administración de Exchange usan cmdlets para administrar Exchange Online, si se otorga acceso a un cmdlet, los administradores o los usuarios podrán tener permiso para realizar la tarea en cada una de las interfaces de administración de Exchange Online.
  
Los permisos basados en funciones para Microsoft Online Services se superponen con los de Exchange Online RBAC de dos maneras. Primero, a los usuarios que son administradores globales o administradores de servicio en Microsoft Online se les asigna automáticamente al grupo de funciones de administración de la organización en Exchange Online. Segundo, a los usuarios que son administradores de asistencia en Microsoft Online se les asigna automáticamente al grupo de funciones de asistencia en Exchange Online. De lo contrario, los dos modelos de seguridad son administrados por separado.
  
> [!IMPORTANT]
> Algunas funciones disponibles en la versión local de Microsoft Exchange Server 2013 podrían no estar disponibles en Exchange Online. 
  
Para obtener más información sobre permisos en Exchange Online, vea [Permisos](https://go.microsoft.com/fwlink/p/?LinkId=271936).
  
## <a name="role-groups"></a>Grupos de funciones

Los grupos de funciones de administración asocian las funciones de administración a un grupo de administradores o usuarios especialistas. Los administradores administran una amplia organización de Exchange Online o configuración de destinatarios. Los usuarios especialistas administran las características específicas de Exchange Online, como el cumplimiento, o podrían tener capacidades de administración limitadas, como los miembros de asistencia, pero no cuentan con derechos administrativos amplios. Los grupos de funciones normalmente están relacionados con funciones de administración pública que permiten que los administradores y los usuarios especialistas administren la configuración de su organización y destinatarios. Por ejemplo, con los grupos de funciones se controla si los administradores pueden administrar a los destinatarios o utilizar características de detección de buzones. 
  
> [!IMPORTANT]
> Algunos grupos de funciones disponibles en la versión local de Microsoft Exchange Server 2013 podrían no estar disponibles en Exchange Online. 
  
Para obtener más información sobre grupos de roles, vea [Grupos de roles y directivas de asignación de roles](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="role-assignment-policies"></a>Directivas de asignación de funciones

Las directivas de asignación de funciones de administración asocian las funciones de administración de usuarios finales a los usuarios. Estas directivas de asignación de funciones constan de funciones que controlan lo que un usuario puede hacer con su buzón o sus grupos de distribución. Estas funciones no permiten la administración de características que no estén directamente asociadas con el usuario. Cuando se crea una directiva de asignación de funciones, se define todo lo que un usuario puede hacer con el buzón. Por ejemplo, una directiva de asignación de funciones puede permitir que un usuario establezca el nombre para mostrar, configure el correo de voz y las reglas de la bandeja de entrada. Otra directiva de asignación de funciones puede permitir que un usuario cambie la dirección, utilice la mensajería de texto y configure los grupos de distribución. De forma predeterminada, cada usuario que tenga un buzón de Exchange Online, incluidos los administradores, tiene una directiva de asignación de funciones. Puede decidir la directiva de asignación de funciones que se aplica de forma predeterminada, elegir el contenido de la directiva de asignación de funciones predeterminada, anular la directiva predeterminada en algunos buzones o no asignar ninguna directiva de asignación de funciones predeterminada.
  
> [!IMPORTANT]
> Algunas asignaciones de funciones disponibles en la versión local de Microsoft Exchange Server 2013 podrían no estar disponibles en Exchange Online. 
  
Para obtener más información sobre políticas de asignación de roles, vea [Grupos de roles y directivas de asignación de roles](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [Descripción del servicio Exchange Online](exchange-online-service-description.md).
  

