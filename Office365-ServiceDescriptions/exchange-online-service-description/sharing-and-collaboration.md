---
title: Uso compartido y colaboración
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: 8e5ce6ce41f206c5736241340c393833ae78fea7
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132594"
---
# <a name="sharing-and-collaboration"></a>Uso compartido y colaboración

## <a name="federated-sharing"></a>Uso compartido federado

La Federación se refiere a la infraestructura de confianza subyacente que admite el uso compartido federado, un método para que los usuarios de Microsoft Exchange Online compartan datos de calendario e información de contacto de disponibilidad con los destinatarios de otras organizaciones federadas externas o con los usuarios que tienen acceso a Internet. Estas incluyen organizaciones que también están hospedadas por Exchange Online u organizaciones Exchange Server 2013 o Microsoft Exchange Server 2010 externas. Mediante el uso de las relaciones de organización y las directivas de uso compartido, los administradores de Exchange online pueden permitir a los usuarios enviar invitaciones de uso compartido de calendarios desde Microsoft Outlook en la web o Microsoft Outlook 2010 o posterior.
  
> [!IMPORTANT]
>  Las organizaciones externas con Exchange 2010 y Exchange 2013 deben configurar una confianza de federación con Microsoft Federation Gateway como parte de la configuración del uso compartido federado. Las organizaciones de Exchange online no tienen que configurar una confianza de Federación: la confianza de Federación con Microsoft Federation Gateway se crea automáticamente cuando se crea la organización 365 de Microsoft. 
>
>  Las organizaciones con Exchange Online deben configurar una relación de organización o una directiva de uso compartido para habilitar el uso compartido federado. 
>
>  No se admite el uso compartido de listas de acceso global (GAL) o el traslado de buzones de usuario entre organizaciones de Exchange online en distintos planes de Microsoft en el uso compartido federado. 
  
Para obtener más información sobre el uso compartido federado, vea [Uso compartido en Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).
  
## <a name="site-mailboxes"></a>Buzones del sitio

Email and documents are traditionally kept in two unique and separate data repositories. Most teams collaborate by using both email and documents. The challenge is that email and documents are accessed by using different clients. This usually results in a reduction in user productivity and a degraded user experience.
  
The site mailbox is a new concept in Exchange 2013 that attempts to solve this problem. Site mailboxes improve collaboration and user productivity by using the same client interface to allow access to both Microsoft SharePoint 2013 documents and Exchange email. A site mailbox functionally consists of SharePoint 2013 site membership (owners and members), shared storage through an Exchange 2013 mailbox for email messages and a SharePoint 2013 site for documents, and a management interface that addresses provisioning and life cycle needs.
  
> [!IMPORTANT]
> El plan debe incluir SharePoint. Los buzones del sitio requieren que los usuarios tengan licencias de SharePoint y Exchange. 
  
Para obtener más información sobre los buzones de sitio, vea [Buzones del sitio](https://go.microsoft.com/fwlink/p/?LinkId=271789).
  
## <a name="public-folders"></a>Carpetas públicas

Las carpetas públicas en Exchange Online se han modernizado para aprovechar las tecnologías de almacenamiento y alta disponibilidad existentes de la base de datos de buzones. La arquitectura de carpeta pública usa buzones especialmente diseñados para almacenar la jerarquía y el contenido de carpeta pública. Esto significa que ya no hay una base de datos de carpetas públicas independiente. La replicación de carpetas públicas ahora utiliza el modelo de replicación continua. La alta disponibilidad para los buzones de contenido y jerarquía está suministrada por un grupo de disponibilidad de base de datos (DAG) en el centro de datos. En Exchange Online, se limita a 1000 buzones de carpetas públicas. Cada buzón de carpeta pública también tiene un tamaño de almacenamiento máximo. Para obtener más información, consulte la sección "límites de carpetas de buzón" en [límites de Exchange Online](exchange-online-limits.md). Los buzones de carpetas públicas tienen los mismos límites de mensajes, destinatarios y alertas de capacidad que los buzones normales. Para más información, consulte [Destinatarios](recipients.md). 
  
Para obtener más información sobre las carpetas públicas, vea [Carpetas públicas](https://go.microsoft.com/fwlink/p/?LinkId=271790).
  
## <a name="group-and-shared-mailboxes"></a>Buzones compartidos y de grupo

Los buzones compartidos y de grupo facilitan a un grupo específico de personas supervisar y enviar correo electrónico desde una cuenta común, como direcciones de correo electrónico públicas (por ejemplo, info@contoso.com o contact@contoso.com). Cuando una persona del Grupo responde a un mensaje enviado al buzón compartido, el correo electrónico parece pertenecer al buzón compartido y no al usuario individual.
  
Normalmente, los buzones compartidos o de grupo no requieren una licencia de usuario independiente. Sin embargo, para habilitar el archivo local para un buzón de correo de grupo o compartido, debe asignar una licencia de plan 1 de Exchange online o plan 2 de Exchange Online. Una vez que se ha asignado la licencia, el tamaño del buzón se incrementa al del plan de la licencia. Para poner un buzón compartido en conservación local, debe asignar una licencia de plan 2 de Exchange Online. Tenga en cuenta que los buzones de grupo no se pueden asignar en este momento, pero se deben tener en cuenta en las licencias totales.
  
Solo puede usarse el Archivo local para archivar correo de una sola entidad o un único usuario (como un buzón compartido) al que se le haya aplicado una licencia. No se permite usar el Archivo local para almacenar correo de varios usuarios o entidades. Por ejemplo, un administrador de TI no puede crear un buzón compartido ni permitir que los usuarios lo copien (con los campos CC o CCO, o mediante una regla de transporte) con el fin de archivarlo. Tenga en cuenta que un buzón compartido que usan varias personas en realidad no almacena correo electrónico de esos usuarios individuales. Varios usuarios tienen acceso y envían correos electrónicos como el buzón compartido. Por lo tanto, los únicos correos electrónicos almacenados en el buzón compartido son los que se envían a o desde él como el buzón compartido.
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, las opciones independientes y las soluciones locales, consulte [Exchange Online Service Description](exchange-online-service-description.md).
  

