---
title: Características de archivo de Archivado de Exchange Online
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: En las secciones siguientes se describen las características de archivo de archivado de Microsoft Exchange Online.
ms.openlocfilehash: f14d8e5c6acefef6fd08cf8e8edf5f33acb9f9df
ms.sourcegitcommit: 433b170b26fbd9c2e9b0e520adfef6f0804df25a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/08/2018
ms.locfileid: "26215355"
---
# <a name="archive-features-in-exchange-online-archiving"></a><span data-ttu-id="79dae-103">Características de archivo de Archivado de Exchange Online</span><span class="sxs-lookup"><span data-stu-id="79dae-103">Archive Features in Exchange Online Archiving</span></span>

<span data-ttu-id="79dae-104">En las secciones siguientes se describen las características de archivo de archivado de Microsoft Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="79dae-104">The following sections describe the archive features of Microsoft Exchange Online Archiving.</span></span>
  
## <a name="archive-mailbox"></a><span data-ttu-id="79dae-105">Buzón de archivo</span><span class="sxs-lookup"><span data-stu-id="79dae-105">Archive mailbox</span></span>

<span data-ttu-id="79dae-p101">Archivado de Exchange Online ofrece a los usuarios capacidades avanzadas de archivo con la característica de buzón de archivo. Un buzón de archivo es un buzón especializado que aparece junto a las carpetas del buzón principal de los usuarios en Outlook o Outlook Web App. Los usuarios pueden acceder al archivo como si accedieran a su buzón principal y realizar búsquedas en ambos buzones.</span><span class="sxs-lookup"><span data-stu-id="79dae-p101">Exchange Online Archiving offers users advanced archiving capabilities with the archive mailbox feature. An archive mailbox is a specialized mailbox that appears alongside the users' primary mailbox folders in Outlook or Outlook Web App. Users can access the archive in the same way that they access their primary mailboxes. In addition, they can search both their archives and primary mailboxes.</span></span>
  
<span data-ttu-id="79dae-p102">Los administradores pueden habilitar la característica de archivo para usuarios específicos desde el Centro de administración de Exchange (EAC) o desde Windows PowerShell remoto. Para obtener más información, vea [Habilitar o deshabilitar un buzón de archivo en Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404425).</span><span class="sxs-lookup"><span data-stu-id="79dae-p102">Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404425).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="79dae-p103">No se permite copiar mensajes en Archivado de Exchange Online para su archivo con el registro en diario, o mediante reglas de transporte o reenvío automático. >  El buzón de archivo de un usuario está diseñado exclusivamente para dicho usuario. Microsoft se reserva el derecho de denegar el archivado ilimitado si el buzón de archivo de un usuario se usa para almacenar datos de archivo de otros usuarios.</span><span class="sxs-lookup"><span data-stu-id="79dae-p103">Using journaling, transport rules, or auto-forwarding rules to copy messages to Exchange Online Archiving for the purposes of archiving is not permitted. >  A user's archive mailbox is intended for just that user. Microsoft reserves the right to deny unlimited archiving in instances where a user's archive mailbox is used to store archive data for other users.</span></span> 
  
### <a name="move-messages-to-exchange-online-archiving"></a><span data-ttu-id="79dae-115">Mover mensajes a Exchange Online Archiving</span><span class="sxs-lookup"><span data-stu-id="79dae-115">Move messages to Exchange Online Archiving</span></span>

<span data-ttu-id="79dae-p104">Los usuarios pueden arrastrar y colocar los mensajes de los archivos .pst en el archivo, para facilitar el acceso en línea. Los usuarios también pueden mover los elementos de correo electrónico desde el buzón principal para el buzón de archivo automáticamente, uso de las directivas de archivo, para reducir el tamaño y mejorar el rendimiento del buzón principal. Aunque este comportamiento es diferente de Exchange Hosted Archive, que se va a crear una copia secundaria de cada mensaje en el archivo, se pueden lograr los requisitos de retención en los dos casos.</span><span class="sxs-lookup"><span data-stu-id="79dae-p104">Users can drag and drop messages from .pst files into the archive, for easy online access. Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox. While this behavior is different than Exchange Hosted Archive, which will create a secondary copy of each message in the archive, retention requirements can be achieved in either scenario.</span></span> 
  
### <a name="import-data-to-the-archive"></a><span data-ttu-id="79dae-119">Importar datos al archivo</span><span class="sxs-lookup"><span data-stu-id="79dae-119">Import data to the archive</span></span>

<span data-ttu-id="79dae-120">Para importar datos al archivo, los usuarios pueden:</span><span class="sxs-lookup"><span data-stu-id="79dae-120">Users can import data to the archive in the following ways:</span></span>
  
- <span data-ttu-id="79dae-121">Importar datos desde un archivo .pst con el Asistente para importar y exportar de Outlook.</span><span class="sxs-lookup"><span data-stu-id="79dae-121">Import data from a .pst file using Outlook's Import and Export wizard.</span></span>
    
- <span data-ttu-id="79dae-122">Arrastrar mensajes de correo desde archivos .pst hasta el archivo.</span><span class="sxs-lookup"><span data-stu-id="79dae-122">Drag email messages from .pst files into the archive.</span></span>
    
- <span data-ttu-id="79dae-123">Arrastrar mensajes de correo desde el buzón principal hasta el archivo.</span><span class="sxs-lookup"><span data-stu-id="79dae-123">Drag email messages from the primary mailbox into the archive.</span></span>
    
- <span data-ttu-id="79dae-p105">Permitir que las directivas de archivo muevan de manera automática los mensajes de correo desde el buzón principal, en función de la antigüedad de los mensajes. Para obtener más información, vea [Etiquetas de retención y directivas de retención](https://go.microsoft.com/fwlink/p/?LinkId=314153).</span><span class="sxs-lookup"><span data-stu-id="79dae-p105">Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkId=314153).</span></span>
    
> [!NOTE]
> <span data-ttu-id="79dae-p106">Los administradores también pueden usar el servicio de importación de Office 365 para importar archivos .pst a los buzones de archivos basados en la nube de los usuarios. Para obtener más información, vea [Usar la carga en la red para importar archivos PST en Office 365](https://go.microsoft.com/fwlink/p/?linkid=823074).</span><span class="sxs-lookup"><span data-stu-id="79dae-p106">Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://go.microsoft.com/fwlink/p/?linkid=823074).</span></span> 
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="79dae-128">Recuperación de elementos eliminados</span><span class="sxs-lookup"><span data-stu-id="79dae-128">Deleted item recovery</span></span>

<span data-ttu-id="79dae-p107">Los usuarios pueden restaurar elementos que han eliminado con anterioridad desde cualquier carpeta de correo de su archivo. Cuando se elimina un elemento, permanece en la carpeta Elementos eliminados del archivo. El elemento permanece ahí hasta que el usuario lo elimina de forma manual o hasta que las directivas de retención lo quitan de forma automática.</span><span class="sxs-lookup"><span data-stu-id="79dae-p107">Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.</span></span>
  
<span data-ttu-id="79dae-p108">Cuando el elemento se quita de la carpeta Elementos eliminados del archivo, se conserva en la carpeta Elementos recuperables del archivo durante 14 días, antes de eliminarse de forma permanente. Los usuarios pueden recuperar estos elementos con la característica **Recuperar elementos eliminados** de Microsoft Outlook o Outlook Web App.</span><span class="sxs-lookup"><span data-stu-id="79dae-p108">After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed. Users can recover these items using the **Recover Deleted Items** feature in Microsoft Outlook or Outlook Web App.</span></span> 
  
<span data-ttu-id="79dae-p109">Si un usuario purga de manera manual un elemento de la carpeta Elementos recuperables, los administradores pueden recuperarlo a lo largo de los 14 días siguientes con la característica Recuperación de un único elemento. Esta característica permite a los administradores realizar una búsqueda en varios buzones para buscar los elementos que se han purgado y, después, transferirlos desde el buzón de correo de detección hasta los buzones de los usuarios con el cmdlet  `Search-Mailbox` de Windows PowerShell. Para obtener más información, vea [Habilitar o deshabilitar la recuperación de elementos individuales de un buzón de correo](https://go.microsoft.com/fwlink/p/?LinkId=314155).</span><span class="sxs-lookup"><span data-stu-id="79dae-p109">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314155).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="79dae-p110">El período predeterminado de recuperación de un único elemento es de 14 días, pero se puede personalizar en situaciones determinadas. >  Si un administrador ha establecido el buzón de un usuario en conservación local o retención por juicio, los elementos purgados se conservan de manera indefinida y no se aplica este período de 14 días.</span><span class="sxs-lookup"><span data-stu-id="79dae-p110">The Single Item Recovery period is 14 days by default, but it can be customized in some circumstances. >  If an administrator has placed a user's mailbox on In-Place Hold or Litigation Hold, purged items are retained indefinitely and the 14-day window does not apply.</span></span> 
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="79dae-139">Recuperación de buzones eliminados</span><span class="sxs-lookup"><span data-stu-id="79dae-139">Deleted mailbox recovery</span></span>

<span data-ttu-id="79dae-p111">Cuando los administradores eliminan usuarios de una implementación local de Exchange Server, también se eliminan los archivos correspondientes. El equipo de soporte técnico de Office 365 puede recuperar los buzones de archivo eliminados si resulta necesario. Los archivos recuperados conservarán todo el correo que contenían almacenado en el momento de su eliminación.</span><span class="sxs-lookup"><span data-stu-id="79dae-p111">When administrators delete users from the on-premises Exchange Server, the users' archives are also deleted. If the deleted archive mailboxes need to be recovered, the Office 365 support team can perform this recovery. A recovered archive will contain all of the mail stored in it at the time it was deleted.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="79dae-p112">A partir del momento en que se elimina el buzón de un usuario, los administradores tienen 30 días para solicitar la recuperación del buzón de archivo. Transcurrido este período, los buzones de archivo ya no pueden recuperarse.</span><span class="sxs-lookup"><span data-stu-id="79dae-p112">Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable.</span></span> 
  
## <a name="mailbox-service-redundancy"></a><span data-ttu-id="79dae-145">Redundancia de servicios de buzón</span><span class="sxs-lookup"><span data-stu-id="79dae-145">Mailbox service redundancy</span></span>

<span data-ttu-id="79dae-p113">Buzones de archivo en Archiving en línea de Exchange se replican en varias copias de base de datos, en centros de datos dispersos geográficamente de Microsoft, para proporcionar capacidad de restauración de datos en caso de error de infraestructura de mensajería. Si hay errores a gran escala, se inicia la administración de continuidad empresarial.</span><span class="sxs-lookup"><span data-stu-id="79dae-p113">Archive mailboxes in Exchange Online Archiving are replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a messaging infrastructure failure. For large-scale failures, business continuity management is initiated.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="79dae-148">Disponibilidad de características</span><span class="sxs-lookup"><span data-stu-id="79dae-148">Feature Availability</span></span>

<span data-ttu-id="79dae-149">Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, vea [Descripción del servicio de archivado de Exchange Online](exchange-online-archiving-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="79dae-149">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Archiving Service Description](exchange-online-archiving-service-description.md).</span></span>
  
