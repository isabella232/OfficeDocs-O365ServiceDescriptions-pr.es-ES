---
title: Características de archivo de archivado de Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: En las siguientes secciones se describen las características de archivo de archivado de Microsoft Exchange Online.
ms.openlocfilehash: 7f6b5863d94862644fb90d1d0d85c3765ad05e9b
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131534"
---
# <a name="archive-features-in-exchange-online-archiving"></a><span data-ttu-id="0e286-103">Características de archivo de archivado de Exchange Online</span><span class="sxs-lookup"><span data-stu-id="0e286-103">Archive features in Exchange Online Archiving</span></span>

<span data-ttu-id="0e286-104">En las siguientes secciones se describen las características de archivo de archivado de Microsoft Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="0e286-104">The following sections describe the archive features of Microsoft Exchange Online Archiving.</span></span>
  
## <a name="archive-mailbox"></a><span data-ttu-id="0e286-105">Buzón de archivo</span><span class="sxs-lookup"><span data-stu-id="0e286-105">Archive mailbox</span></span>

<span data-ttu-id="0e286-106">Archivado de Exchange Online ofrece capacidades avanzadas de archivado para los usuarios con la característica de buzón de archivo.</span><span class="sxs-lookup"><span data-stu-id="0e286-106">Exchange Online Archiving offers users advanced archiving capabilities with the archive mailbox feature.</span></span> <span data-ttu-id="0e286-107">Un buzón de archivo es un buzón especializado que aparece junto a las carpetas de buzones principales de los usuarios en Outlook o en Outlook en la Web.</span><span class="sxs-lookup"><span data-stu-id="0e286-107">An archive mailbox is a specialized mailbox that appears alongside the users' primary mailbox folders in Outlook or Outlook on the web.</span></span> <span data-ttu-id="0e286-108">Los usuarios pueden tener acceso al archivo de la misma forma que tienen acceso a sus buzones principales.</span><span class="sxs-lookup"><span data-stu-id="0e286-108">Users can access the archive in the same way that they access their primary mailboxes.</span></span> <span data-ttu-id="0e286-109">Además, pueden buscar en sus archivos y en los buzones de correo principales.</span><span class="sxs-lookup"><span data-stu-id="0e286-109">In addition, they can search both their archives and primary mailboxes.</span></span>
  
<span data-ttu-id="0e286-p102">Los administradores pueden habilitar la característica de archivo para usuarios específicos desde el Centro de administración de Exchange (EAC) o desde Windows PowerShell remoto. Para obtener más información, vea [Habilitar o deshabilitar un buzón de archivo en Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).</span><span class="sxs-lookup"><span data-stu-id="0e286-p102">Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="0e286-112">No se permite copiar mensajes en Archivado de Exchange Online para su archivo con el registro en diario, o mediante reglas de transporte o reenvío automático.</span><span class="sxs-lookup"><span data-stu-id="0e286-112">Using journaling, transport rules, or auto-forwarding rules to copy messages to Exchange Online Archiving for the purposes of archiving is not permitted.</span></span> <br/>
>  <span data-ttu-id="0e286-113">El buzón de archivo de un usuario está diseñado exclusivamente para dicho usuario.</span><span class="sxs-lookup"><span data-stu-id="0e286-113">A user's archive mailbox is intended for just that user.</span></span> <span data-ttu-id="0e286-114">Microsoft se reserva el derecho a denegar el archivado ilimitado en los casos en que el buzón de archivo de un usuario se usa para almacenar datos de archivo para otros usuarios o en otros casos de uso inadecuado.</span><span class="sxs-lookup"><span data-stu-id="0e286-114">Microsoft reserves the right to deny unlimited archiving in instances where a user's archive mailbox is used to store archive data for other users or in other cases of inappropriate use.</span></span>
  
### <a name="move-messages-to-exchange-online-archiving"></a><span data-ttu-id="0e286-115">Mover mensajes a Exchange Online Archiving</span><span class="sxs-lookup"><span data-stu-id="0e286-115">Move messages to Exchange Online Archiving</span></span>

<span data-ttu-id="0e286-116">Los usuarios pueden arrastrar y soltar mensajes de archivos. pst en el archivo para facilitar el acceso en línea.</span><span class="sxs-lookup"><span data-stu-id="0e286-116">Users can drag and drop messages from .pst files into the archive, for easy online access.</span></span> <span data-ttu-id="0e286-117">Los usuarios también pueden mover elementos de correo electrónico desde el buzón principal al buzón de archivo automáticamente, mediante directivas de archivo, para reducir el tamaño y mejorar el rendimiento del buzón principal.</span><span class="sxs-lookup"><span data-stu-id="0e286-117">Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox.</span></span> 
  
### <a name="import-data-to-the-archive"></a><span data-ttu-id="0e286-118">Importar datos al archivo</span><span class="sxs-lookup"><span data-stu-id="0e286-118">Import data to the archive</span></span>

<span data-ttu-id="0e286-119">Para importar datos al archivo, los usuarios pueden:</span><span class="sxs-lookup"><span data-stu-id="0e286-119">Users can import data to the archive in the following ways:</span></span>
  
- <span data-ttu-id="0e286-120">Importar datos desde un archivo .pst con el Asistente para importar y exportar de Outlook.</span><span class="sxs-lookup"><span data-stu-id="0e286-120">Import data from a .pst file using Outlook's Import and Export wizard.</span></span>
    
- <span data-ttu-id="0e286-121">Arrastrar mensajes de correo desde archivos .pst hasta el archivo.</span><span class="sxs-lookup"><span data-stu-id="0e286-121">Drag email messages from .pst files into the archive.</span></span>
    
- <span data-ttu-id="0e286-122">Arrastrar mensajes de correo desde el buzón principal hasta el archivo.</span><span class="sxs-lookup"><span data-stu-id="0e286-122">Drag email messages from the primary mailbox into the archive.</span></span>
    
- <span data-ttu-id="0e286-p106">Permitir que las directivas de archivo muevan de manera automática los mensajes de correo desde el buzón principal, en función de la antigüedad de los mensajes. Para obtener más información, vea [Etiquetas de retención y directivas de retención](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).</span><span class="sxs-lookup"><span data-stu-id="0e286-p106">Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).</span></span>
    
> [!NOTE]
> <span data-ttu-id="0e286-p107">Los administradores también pueden usar el servicio de importación de Office 365 para importar archivos .pst a los buzones de archivos basados en la nube de los usuarios. Para obtener más información, vea [Usar la carga en la red para importar archivos PST en Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span><span class="sxs-lookup"><span data-stu-id="0e286-p107">Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span> 
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="0e286-127">Recuperación de elementos eliminados</span><span class="sxs-lookup"><span data-stu-id="0e286-127">Deleted item recovery</span></span>

<span data-ttu-id="0e286-p108">Los usuarios pueden restaurar elementos que han eliminado con anterioridad desde cualquier carpeta de correo de su archivo. Cuando se elimina un elemento, permanece en la carpeta Elementos eliminados del archivo. El elemento permanece ahí hasta que el usuario lo elimina de forma manual o hasta que las directivas de retención lo quitan de forma automática.</span><span class="sxs-lookup"><span data-stu-id="0e286-p108">Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.</span></span>
  
<span data-ttu-id="0e286-131">Cuando el elemento se quita de la carpeta Elementos eliminados del archivo, se conserva en la carpeta Elementos recuperables del archivo durante 14 días, antes de eliminarse de forma permanente.</span><span class="sxs-lookup"><span data-stu-id="0e286-131">After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed.</span></span> <span data-ttu-id="0e286-132">Los usuarios pueden recuperar estos elementos mediante la característica **recuperar elementos eliminados** de Microsoft Outlook o Outlook en la Web.</span><span class="sxs-lookup"><span data-stu-id="0e286-132">Users can recover these items using the **Recover Deleted Items** feature in Microsoft Outlook or Outlook on the web.</span></span> 
  
<span data-ttu-id="0e286-p110">Si un usuario purga de manera manual un elemento de la carpeta Elementos recuperables, los administradores pueden recuperarlo a lo largo de los 14 días siguientes con la característica Recuperación de un único elemento. Esta característica permite a los administradores realizar una búsqueda en varios buzones para buscar los elementos que se han purgado y, después, transferirlos desde el buzón de correo de detección hasta los buzones de los usuarios con el cmdlet  `Search-Mailbox` de Windows PowerShell. Para obtener más información, vea [Habilitar o deshabilitar la recuperación de elementos individuales de un buzón de correo](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span><span class="sxs-lookup"><span data-stu-id="0e286-p110">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="0e286-136">El período predeterminado de recuperación de un único elemento es de 14 días, pero se puede personalizar en situaciones determinadas.</span><span class="sxs-lookup"><span data-stu-id="0e286-136">The Single Item Recovery period is 14 days by default, but it can be customized in some circumstances.</span></span> <br/>
>  <span data-ttu-id="0e286-137">Si un administrador ha colocado el buzón de un usuario en conservación local o retención por juicio, los elementos purgados se conservan de manera indefinida y no se aplica el período de 14 días.</span><span class="sxs-lookup"><span data-stu-id="0e286-137">If an administrator has placed a user's mailbox on In-Place Hold or Litigation Hold, purged items are retained indefinitely and the 14-day window does not apply.</span></span> 
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="0e286-138">Recuperación de buzones eliminados</span><span class="sxs-lookup"><span data-stu-id="0e286-138">Deleted mailbox recovery</span></span>

<span data-ttu-id="0e286-139">Cuando los administradores eliminan usuarios de una implementación local de Exchange Server, también se eliminan los archivos correspondientes.</span><span class="sxs-lookup"><span data-stu-id="0e286-139">When administrators delete users from the on-premises Exchange Server, the users' archives are also deleted.</span></span> <span data-ttu-id="0e286-140">Si los buzones de archivo eliminados deben recuperarse, el equipo de soporte técnico de Microsoft puede llevar a cabo esta recuperación.</span><span class="sxs-lookup"><span data-stu-id="0e286-140">If the deleted archive mailboxes need to be recovered, the Microsoft support team can perform this recovery.</span></span> <span data-ttu-id="0e286-141">Los archivos recuperados conservarán todo el correo que contenían almacenado en el momento de su eliminación.</span><span class="sxs-lookup"><span data-stu-id="0e286-141">A recovered archive will contain all of the mail stored in it at the time it was deleted.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="0e286-p113">A partir del momento en que se elimina el buzón de un usuario, los administradores tienen 30 días para solicitar la recuperación del buzón de archivo. Transcurrido este período, los buzones de archivo ya no pueden recuperarse.</span><span class="sxs-lookup"><span data-stu-id="0e286-p113">Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable.</span></span> 
  
## <a name="mailbox-service-redundancy"></a><span data-ttu-id="0e286-144">Redundancia de servicios de buzón</span><span class="sxs-lookup"><span data-stu-id="0e286-144">Mailbox service redundancy</span></span>

<span data-ttu-id="0e286-145">Los buzones de archivo de Exchange Online archiving se replican en varias copias de bases de datos, en centros de datos de Microsoft dispersos geográficamente, para proporcionar la capacidad de restauración de datos en caso de que se produzca un error en la infraestructura de mensajería.</span><span class="sxs-lookup"><span data-stu-id="0e286-145">Archive mailboxes in Exchange Online Archiving are replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a messaging infrastructure failure.</span></span> <span data-ttu-id="0e286-146">Para los errores a gran escala, se inicia la administración de la continuidad empresarial.</span><span class="sxs-lookup"><span data-stu-id="0e286-146">For large-scale failures, business continuity management is initiated.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="0e286-147">Disponibilidad de características</span><span class="sxs-lookup"><span data-stu-id="0e286-147">Feature availability</span></span>

<span data-ttu-id="0e286-148">Para ver la disponibilidad de características entre planes, las opciones independientes y las soluciones locales, consulte [Descripción del servicio de archivado de Exchange Online](exchange-online-archiving-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="0e286-148">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Archiving service description](exchange-online-archiving-service-description.md).</span></span>
  
