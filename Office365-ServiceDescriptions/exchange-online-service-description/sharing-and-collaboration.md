---
title: Uso compartido y colaboración
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: 1afee4f2868a8bf0f0a1662e2d70bd8de3f2043a
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653302"
---
# <a name="sharing-and-collaboration"></a>Uso compartido y colaboración

## <a name="federated-sharing"></a>Uso compartido federado

La federación hace referencia a la infraestructura de confianza subyacente que admite el uso compartido federado, un método para que los usuarios de Microsoft Exchange Online compartan datos de calendario de disponibilidad e información de contacto con destinatarios de otras organizaciones federadas externas o con usuarios con acceso a Internet. Estas incluyen organizaciones que también están hospedadas por Exchange Online u organizaciones Exchange Server 2013 o Microsoft Exchange Server 2010 externas. Con las relaciones de la organización y las directivas de uso compartido, los administradores de Exchange Online pueden permitir a los usuarios enviar invitaciones de uso compartido de calendario de Microsoft Outlook en la web o Microsoft Outlook 2010 o posterior.
  
> [!IMPORTANT]
>  Las organizaciones externas con Exchange 2010 y Exchange 2013 deben configurar una confianza de federación con Microsoft Federation Gateway como parte de la configuración del uso compartido federado. Exchange Online las organizaciones no tienen que configurar una confianza de federación: la confianza de federación con el Microsoft Federation Gateway se crea automáticamente cuando se crea Microsoft 365 organización. 
>
>  Las organizaciones con Exchange Online deben configurar una relación de organización o una directiva de uso compartido para habilitar el uso compartido federado. 
>
>  El uso compartido de listas de acceso global (GAL) o el movimiento de buzones de usuario entre organizaciones Exchange Online en diferentes planes de Microsoft no se admite en el uso compartido federado. 
  
Para obtener más información sobre el uso compartido federado, vea [Uso compartido en Exchange Online](/exchange/sharing/sharing).
  
## <a name="site-mailboxes"></a>Buzones del sitio

El correo electrónico y los documentos se mantienen tradicionalmente en dos repositorios de datos únicos e independientes. La mayoría de los equipos colabora mediante correo electrónico y documentos. El desafío es que pueda accederse al correo electrónico y a los documentos mediante clientes diferentes. Normalmente se traduce en una reducción en la productividad del usuario y en una mala experiencia de usuario.
  
El buzón del sitio es un nuevo concepto en Exchange 2013 que intenta solucionar este problema. Los buzones en el sitio mejoran la colaboración y la productividad del usuario mediante el uso de la misma interfaz de cliente al permitir el acceso a documentos de Microsoft SharePoint 2013 y correo electrónico de Exchange. Un buzón de sitio comprende funcionalmente la pertenencia al sitio de SharePoint 2013 (propietarios y miembros), almacenamiento compartido mediante un buzón de Exchange 2013 para los mensajes de correo electrónico y un sitio SharePoint 2013 para los documentos, además de una interfaz de administración que satisface las necesidades de ciclo de vida y aprovisionamiento.
  
> [!IMPORTANT]
> El plan debe incluir SharePoint. Los buzones del sitio requieren que los usuarios tengan licencias de SharePoint y Exchange. 
  
Para obtener más información sobre los buzones de sitio, vea [Buzones del sitio](/exchange/collaboration-exo/collaboration-exo).
  
## <a name="public-folders"></a>Carpetas públicas

Las carpetas públicas en Exchange Online se han modernizado para aprovechar las tecnologías de almacenamiento y alta disponibilidad existentes de la base de datos de buzones. La arquitectura de carpeta pública usa buzones especialmente diseñados para almacenar la jerarquía y el contenido de carpeta pública. Esto significa que ya no hay una base de datos de carpetas públicas independiente. La replicación de carpetas públicas ahora utiliza el modelo de replicación continua. La alta disponibilidad para los buzones de contenido y jerarquía está suministrada por un grupo de disponibilidad de base de datos (DAG) en el centro de datos. En Exchange Online, está limitado a 1000 buzones de carpetas públicas. Cada buzón de carpeta pública también tiene un tamaño de almacenamiento máximo. Para obtener más información, vea la sección "Límites de carpetas de buzones" [en Exchange Online de correo](exchange-online-limits.md). Los buzones de carpetas públicas tienen los mismos límites de mensajes, destinatarios y alertas de capacidad que los buzones normales. Para más información, consulte [Destinatarios](recipients.md). 
  
Para obtener más información sobre las carpetas públicas, vea [Carpetas públicas](/exchange/collaboration-exo/public-folders/public-folders).
  
## <a name="group-and-shared-mailboxes"></a>Buzones compartidos y de grupo

Los buzones de correo compartidos y de grupo facilita que un grupo específico de personas supervise y envíe correo electrónico desde una cuenta común, como las direcciones de correo electrónico públicas (por ejemplo, info@contoso.com o contact@contoso.com). Cuando una persona del grupo responde a un mensaje enviado al buzón compartido, el correo electrónico parece ser del buzón compartido, no del usuario individual.
  
Normalmente, los buzones compartidos o de grupo no requieren una licencia de usuario independiente. Sin embargo, para habilitar In-Place Archive para un grupo o buzón compartido, debe asignarle una licencia Exchange Online plan 1 o Exchange Online plan 2. Una vez que se ha asignado la licencia, el tamaño del buzón se incrementa al del plan de la licencia. Para colocar un buzón compartido en In-Place, debe asignarle una Exchange Online de plan 2. Tenga en cuenta que los buzones de grupo no se pueden asignar en este momento, pero deben tenerse en cuenta en el total de licencias.
  
Solo puede usarse el Archivo local para archivar correo de una sola entidad o un único usuario (como un buzón compartido) al que se le haya aplicado una licencia. No se permite usar el Archivo local para almacenar correo de varios usuarios o entidades. Por ejemplo, un administrador de TI no puede crear un buzón compartido ni permitir que los usuarios lo copien (con los campos CC o CCO, o mediante una regla de transporte) con el fin de archivarlo. Tenga en cuenta que un buzón compartido que usan varias personas en realidad no almacena correo electrónico de esos usuarios individuales. Varios usuarios tienen acceso y envían correos electrónicos como el buzón compartido. Por lo tanto, los únicos correos electrónicos que se almacenan en el buzón compartido son aquellos enviados a o desde él, como el buzón compartido.
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, opciones independientes y soluciones locales, [consulte Exchange Online descripción del servicio](exchange-online-service-description.md).
