---
title: Límites de Exchange Online
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 7/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 70b38a05-6cfa-4ced-a137-116019262fed
description: Encuentre los límites de Exchange Online para las distintas áreas de servicio, entre los que se incluyen los límites de la libreta de direcciones, los de almacenamiento de los buzones y los de seguimiento de informes y mensajes.
ms.openlocfilehash: f6b47ddbbba3eeb40c564bbcfa5ace25671ade9e
ms.sourcegitcommit: 451688016111b1ccae37b9b84d7cf53d844acdbc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/08/2018
ms.locfileid: "25450582"
---
# <a name="exchange-online-limits"></a>Límites de Exchange Online

Encuentre los límites de Exchange Online para las distintas áreas de servicio, entre los que se incluyen los límites de la libreta de direcciones, los de almacenamiento de los buzones y los de seguimiento de informes y mensajes.
  
> [!NOTE]
>  Si necesita ayuda con una tarea o si está solucionando un problema, es posible que los artículos siguientes le resulten útiles:  <br/> • [Correo electrónico](https://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&amp;rs=en-US&amp;ad=US) (para obtener ayuda creación y envío de correo electrónico)  <br/> • [Correo electrónico en Office 365 para profesionales - ayuda de administración](https://go.microsoft.com/fwlink/?linkid=529722) <br/>   • [Corregir Outlook y problemas de Office 365 con soporte técnico de Microsoft y recuperación Ayudante de Office 365](https://diagnostics.office.com/) <br/>  • [Informes de no entrega de correo electrónico en Office 365](https://go.microsoft.com/fwlink/?linkid=526653) <br/> • [Ayuda en pantalla de exchange](https://go.microsoft.com/fwlink/?linkid=825607) <br/>
  
Los límites en Microsoft Exchange Online se ajustan a una de las siguientes categorías:
  
- [Límites de la libreta de direcciones](#address-book-limits)
    
- [Límites de almacenamiento de los buzones](#mailbox-storage-limits)
    
- [Alertas de capacidad](#capacity-alerts)
    
- [Límites de la carpeta de buzón de correo](#mailbox-folder-limits)
    
- [Límites de mensajes](#message-limits)

- [Límites de envío y recepción](#receiving-and-sending-limits)
    
- [Límites de seguimiento de mensajes y creación de informes](#reporting-and-message-trace-limits)
    
- [Límites de retención](#retention-limits)
    
- [Límites de grupos de distribución](#distribution-group-limits)
    
- [Límites de reglas de diario, el transporte y Bandeja de entrada](#journal-transport-and-inbox-rule-limits)
    
- [Límites de moderación](#moderation-limits)
    
- [Límites de Exchange ActiveSync](#exchange-activesync-limits)
    
> [!IMPORTANT]
>  • Los límites que se aplican a una organización de Microsoft Office 365 pueden diferir dependiendo de cuánto la organización ha inscrito en el servicio.<br/> Centros de • cuando un límite se han realizado en los datos de Microsoft, puede tardar algún tiempo para aplicar el cambio a todos los clientes existentes.<br/> • No se puede modificar la mayoría de estos límites, pero usted y los usuarios deben ser conscientes de ellos.<br/> • Estos límites se aplican a los destinatarios internos y externos.<br/> • De forma predeterminada, Exchange Online Protection (EOP) protege los buzones de Exchange Online. Para conocer los límites que se aplican a las características de EOP en Exchange Online, consulte [Exchange Online Protection Limits](../exchange-online-protection-service-description/exchange-online-protection-limits.md).<br/> • Para obtener información acerca de los límites de grupo de Office 365, vea "¿cómo administrar Mis groups?" in [Aprenda acerca de los grupos de Office 365](https://go.microsoft.com/fwlink/?linkid=846714). 
  
## <a name="address-book-limits"></a>Límites de la libreta de direcciones

- **Límite de listas de direcciones** El número máximo de listas de direcciones que se pueden crear en una organización de Exchange Online o Exchange Server 2013. Este número incluye las listas de direcciones predeterminadas en Exchange Online, como todos los contactos y todos los grupos. 
    
    > [!NOTE]
    > Puede asignarse un máximo de 20 listas de direcciones a cada libreta de direcciones sin conexión (OAB). 
  
- **Límite de libretas de direcciones sin conexión** El número máximo de libretas de direcciones sin conexión (OAB) que se pueden crear en una organización de Exchange Online o Exchange Server 2013. 
    
- **Límite de directivas de libreta de direcciones** El número máximo de directivas de libreta de direcciones (ABP) que se pueden crear en una organización de Exchange Online o Exchange Server 2013. 
    
- **Listas globales de direcciones** El número máximo de listas globales de direcciones (GAL) que se pueden crear en una organización de Exchange Online o Exchange Server 2013. 
    
### <a name="address-book-limits-across-office-365-options"></a>Límites de la libreta de direcciones en las distintas opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Office 365 Empresa Essentials** <br/> |**Office 365 Empresa Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Límite de listas de direcciones  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|Límite de libretas de direcciones sin conexión (OAB)  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Límite de directivas de libreta de direcciones (ABP)  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Límite de listas globales de direcciones  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
   
### <a name="address-book-limits-across-standalone-plans"></a>Límites de la libreta de direcciones a través de planes independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (plan 1)** <br/> |**Exchange Online (plan 2)** <br/> |**Quiosco de Exchange Online** <br/> |
|Límite de listas de direcciones  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|Límite de libretas de direcciones sin conexión (OAB)  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Límite de directivas de libreta de direcciones (ABP)  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Límite de listas globales de direcciones  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
   
## <a name="mailbox-storage-limits"></a>Límites de almacenamiento de los buzones

El espacio de almacenamiento del buzón disponible para un usuario está determinado por el tipo de buzón y la licencia de suscripción del usuario. Los administradores pueden reducir el tamaño máximo del buzón de correo por usuario o de forma global.
  
> [!NOTE]
> Con el registro en diario, el uso de reglas de transporte o reglas de transferencia automática para copiar mensajes en un buzón de Exchange Online con fines de archivado no está permitido. El buzón de archivo de un usuario está diseñado exclusivamente para dicho usuario. Microsoft se reserva el derecho de denegar el archivado ilimitado si el buzón de archivo de un usuario se usa para almacenar datos de archivo de otros usuarios. 
  
### <a name="storage-limits-across-office-365-options"></a>Límites de almacenamiento en las opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Office 365 Empresa Essentials** <br/> |**Office 365 Empresa Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Buzones de usuario  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |100 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
|Buzones de archivo<sup>7, 8</sup> <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |Ilimitado<sup>1</sup> <br/> |Ilimitado<sup>1</sup> <br/> |No disponible<sup>4</sup> <br/> |
|Buzones compartidos  <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2,9</sup> <br/> |50 GB<sup>2,9</sup> <br/> |50 GB<sup>2</sup> <br/> |
|Buzones de recursos  <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3,9</sup> <br/> |50 GB<sup>3,9</sup> <br/> |50 GB<sup>3</sup> <br/> |
|Buzones de sitio<sup>5</sup> <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |No disponible  <br/> |
|Buzones de carpetas públicas  <br/> |<sup>6</sup> de 50 GB <br/> |<sup>6</sup> de 50 GB <br/> |<sup>6</sup> de 50 GB <br/> |<sup>6</sup> de 100 GB <br/> |<sup>6</sup> de 100 GB <br/> |No disponible  <br/> |
|Buzones de grupo  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup> cada usuario recibe inicialmente 100 GB de almacenamiento en el buzón de archivo. Cuando está activado el crecimiento automático de archivado, almacenamiento adicional se agrega automáticamente cuando se alcanza la capacidad de almacenamiento de 100 GB. Para obtener más información, vea [información general sobre el archivo ilimitado en Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Vea la [Guía básica de Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) para obtener información detallada acerca de la disponibilidad.<br/>  <sup>2</sup> para obtener acceso a un buzón compartido, un usuario debe tener una licencia de Exchange Online. Buzones compartidos no requieren una licencia independiente. Sin embargo, sin una licencia, buzones de correo compartidos se limitan a 50 GB. Para aumentar el tamaño del buzón, se debe asignar una licencia E3 o E5. Esto aumentará el buzón de correo a 100 GB. Si desea habilitar el buzón de archivo o poner un juicio en un buzón compartido, una licencia de Exchange Online Plan 2 o un Exchange Online Plan 1 con licencia de archivado de Exchange Online es necesario. Si habilita el buzón de archivo y la ampliación automática de archivado para un buzón compartido, almacenamiento adicional se agrega automáticamente cuando se alcanza la capacidad de almacenamiento de 100 GB para el buzón de archivo.<br/>  <sup>3</sup> buzones de recursos no requieren una licencia. Sin embargo, sin una licencia, buzones de correo compartidos se limitan a 50 GB. Para aumentar el tamaño del buzón, se debe asignar una licencia E3 o E5. Esto aumentará el buzón de correo a 100 GB.<br/>  <sup>4</sup> buzones de archivo no se incluyen en Exchange Online quiosco. Sin embargo, puede adquirirse como un complemento a través de archivado de Exchange Online. Para obtener más información, consulte la [Descripción de Exchange Online Archiving Service](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md).<br/>  <sup>5</sup> los buzones del sitio se crean y administran en SharePoint Online. Para obtener más información, consulte [Prepare para el uso de los buzones del sitio en Office 365](http://go.microsoft.com/fwlink/p/?LinkId=299131).<br/>  <sup>6</sup> está limitado a 1.000 buzones de carpetas públicas y el tamaño total máximo de todos los buzones de carpetas públicas es de 50 TB.<br/>  <sup>7</sup> buzones de archivo sólo pueden utilizarse para archivar correo para un solo usuario o una entidad (por ejemplo, un buzón compartido) para que se ha aplicado una licencia. Se prohíbe el uso de buzones de archivo como un medio de almacenar el correo de varios usuarios o entidades. Por ejemplo, un administrador de TI no se puede crear un buzón compartido y tienen los usuarios copiar (a través del campo Cc o CCO, o a través de una regla de transporte) con el fin explícito de archivado. Tenga en cuenta que un buzón compartido que usan varias personas no almacena en realidad el correo electrónico para los usuarios individuales. Varios usuarios tienen acceso y que envían correo electrónico como el buzón compartido. Por lo tanto, los mensajes de correo electrónico únicas almacenadas en el buzón compartido son aquellos enviados a o desde él, *como* el buzón compartido.<br/>  <sup>8</sup> si ha creado una directiva de retención en Exchange Online, los mensajes se moverá automáticamente al buzón de archivo de un usuario sólo si el buzón del usuario principal es mayor que 10 MB. No se ejecutará automáticamente la directiva de retención para los buzones que tienen menos de 10 MB.<br/>  Buzones de correo compartidos y recursos de <sup>9</sup> no requieren una licencia. Sin embargo, sin una licencia, buzones de correo compartidos se limitan a 50 GB. Para aumentar el tamaño del buzón, se debe asignar una licencia E3 o E5. Esto aumentará el buzón de correo a 100 GB. 
  
### <a name="storage-limits-across-standalone-plans"></a>Límites de almacenamiento en planes independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (plan 1)** <br/> |**Exchange Online (plan 2)** <br/> |**Quiosco de Exchange Online** <br/> |
|Buzones de usuario  <br/> |<sup>1</sup> de 2 GB <br/> |50 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
|Buzones de archivo<sup>8, 9</sup> <br/> |100 GB<sup>1</sup> <br/> |50 GB  <br/> |Ilimitado<sup>2</sup> <br/> |No disponible<sup>5</sup> <br/> |
|Buzones compartidos  <br/> |<sup>1</sup> de 2 GB <br/> |50 GB<sup>3</sup> <br/> |<sup>3,10</sup> de 50 GB <br/> |50 GB<sup>3</sup> <br/> |
|Buzones de recursos  <br/> |<sup>1</sup> de 2 GB <br/> |50 GB<sup>4</sup> <br/> |<sup>4,10</sup> de 50 GB <br/> |50 GB<sup>4</sup> <br/> |
|Buzones de carpetas públicas  <br/> |<sup>6</sup> de 2 GB <br/> |<sup>7</sup> de 50 GB <br/> |<sup>7</sup> de 100 GB <br/> |No disponible  <br/> |
|Buzones de grupo  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup> es el tamaño del buzón de correo predeterminada para las organizaciones de Exchange Server 2013. Los administradores pueden cambiar este valor para su organización. No hay un límite máximo de almacenamiento para los buzones locales.<br/>  <sup>2</sup> cada usuario recibe inicialmente 100 GB de almacenamiento en el buzón de archivo. Cuando está activado el crecimiento automático de archivado, almacenamiento adicional se agrega automáticamente cuando se alcanza la capacidad de almacenamiento de 100 GB. Para obtener más información, vea [información general sobre el archivo ilimitado en Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Vea la [Guía básica de Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) para obtener información detallada acerca de la disponibilidad de ampliación automática archivado.<br/> <sup>3</sup> para obtener acceso a un buzón compartido, un usuario debe tener una licencia de Exchange Online. Buzones compartidos no requieren una licencia independiente. Sin embargo, sin una licencia, buzones de correo compartidos se limitan a 50 GB. Para aumentar el tamaño del buzón, se debe asignar una licencia de Exchange Online Plan 2. Esto aumentará el buzón de correo a 100 GB. Si desea habilitar el buzón de archivo o poner un juicio en un buzón compartido, una licencia de Exchange Online Plan 2 o un Exchange Online Plan 1 con licencia de archivado de Exchange Online es necesario. Si habilita el buzón de archivo y la ampliación automática de archivado para un buzón compartido, almacenamiento adicional se agrega automáticamente cuando se alcanza la capacidad de almacenamiento de 100 GB para el buzón de archivo.<br/> <sup>4</sup> los buzones de recursos no requieren una licencia. Sin embargo, sin una licencia, buzones de correo compartidos se limitan a 50 GB. Para aumentar el tamaño del buzón, se debe asignar una licencia de Exchange Online Plan 2. Esto aumentará el buzón de correo a 100 GB.<br/>  <sup>5</sup> buzones de archivo no se incluyen en Exchange Online quiosco. Sin embargo, puede adquirirse como un complemento a través de archivado de Exchange Online. Para obtener más información, consulte la [Descripción de Exchange Online Archiving Service](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md).<br/>  <sup>6</sup> es el tamaño del buzón de correo predeterminada para las organizaciones de Microsoft Exchange Server 2013. Los administradores pueden cambiar este valor para su organización. En Exchange Server 2013, está limitado a 100 buzones de carpetas públicas y el tamaño total máximo de todos los buzones de carpetas públicas es de 50 TB.<br/>  <sup>7</sup> en Exchange Online, está limitado a 1.000 buzones de carpetas públicas y el tamaño total máximo de todos los buzones de carpetas públicas es de 50 TB.<br/>  <sup>8</sup> buzones de archivo sólo pueden utilizarse para archivar el correo para un único usuario o entidad para la que se ha aplicado una licencia. Se prohíbe el uso de un buzón de archivo como un medio para almacenar el correo de varios usuarios o entidades. Por ejemplo, los administradores de TI no se pueden crear buzones de correo compartidos y tienen los usuarios copiar (a través del campo Cc o CCO, o a través de una regla de transporte) de un buzón compartido con el fin explícito de archivado.<br/>  <sup>9</sup> si ha creado una directiva de retención en Exchange Online, los mensajes se moverá automáticamente al buzón de archivo de un usuario sólo si el buzón del usuario principal es mayor que 10 MB. No se ejecutará automáticamente la directiva de retención para los buzones que tienen menos de 10 MB.<br/>  <sup>10</sup> compartidos y los buzones de recursos no requieren una licencia que se asignará. Sin embargo, sin una licencia, estos buzones de correo se limitan a 50 GB. Para aumentar el tamaño del buzón, debe asignarse una licencia de Exchange Online Plan 2. Esto aumentará el buzón de correo a 100 GB. 
  
> [!NOTE]
> Un buzón compartido no está diseñado para el inicio de sesión directo. La cuenta de usuario para el propio buzón compartido debe permanecer en un **deshabilitado** (o "desconectado") estado. 
  
## <a name="capacity-alerts"></a>Alertas de capacidad

Exchange Online ofrece tres tipos de notificaciones cuando el buzón de un usuario se acerca o alcanza su máxima capacidad:
  
- **Advertencia** El usuario recibe un correo electrónico en el que se le advierte de que el buzón de correo se acerca a su límite de capacidad máxima. Esta advertencia está diseñada para animar a los usuarios a eliminar el correo no deseado. 
    
- **Prohibir envío** El usuario recibe una notificación de prohibir el envío cuando se alcanza el límite de capacidad máxima del buzón de correo. El usuario no puede enviar nuevos mensajes hasta que se elimine suficiente correo para que el buzón de correo esté por debajo del límite de tamaño. 
    
- **Prohibir envío y recepción** Exchange Online rechaza todo el correo entrante cuando se alcanza el límite de tamaño del buzón de correo y envía un informe de no entrega (NDR) al remitente. El remitente tiene la opción de intentar reenviar el correo más tarde. Para volver a recibir mensajes, el usuario debe eliminar el correo electrónico hasta que esté por debajo del límite de tamaño. 
    
### <a name="capacity-alerts-across-office-365-options"></a>Alertas de capacidad en las opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Office 365 Empresa Essentials** <br/> |**Office 365 Empresa Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Advertencia  <br/> |49 GB  <br/> |49 GB  <br/> |49 GB  <br/> |98 GB  <br/> |98 GB  <br/> |1,96 GB  <br/> |
|Prohibir envío  <br/> |49,5 GB  <br/> |49,5 GB  <br/> |49,5 GB  <br/> |99 GB  <br/> |99 GB  <br/> |1,98 GB  <br/> |
|Prohibir envío y recepción  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |100 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
   
### <a name="capacity-alerts-across-standalone-plans"></a>Alertas de capacidad en planes independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (plan 1)** <br/> |**Exchange Online (plan 2)** <br/> |**Quiosco de Exchange Online** <br/> |
|Advertencia  <br/> |1,9 GB<sup>1</sup> <br/> |49 GB  <br/> |98 GB  <br/> |1,96 GB  <br/> |
|Prohibir envío  <br/> |<sup>1</sup> de 2 GB <br/> |49,5 GB  <br/> |99 GB  <br/> |1,98 GB  <br/> |
|Prohibir envío y recepción  <br/> |2,3 GB<sup>1</sup> <br/> |50 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup> Este es el valor predeterminado para organizaciones de Exchange Server 2013. Los administradores pueden cambiar este valor para su organización. 
  
## <a name="mailbox-folder-limits"></a>Límites de la carpeta de buzón de correo

Estos límites se usan para limitar el tamaño de los buzones de correo y garantizar la compatibilidad en Exchange Online. El objetivo de estos límites es evitar que exista un número ilimitado de elementos de buzón de correo por carpeta, un número ilimitado de carpetas por buzón de correo o un número ilimitado de carpetas públicas por organización de Exchange Online. Por cuestiones prácticas, los límites de carpetas de buzón de correo se aplican de forma permanente para garantizar la compatibilidad de la mayoría de los buzones de Exchange Online y locales que se migran a Exchange Online.
  
- **Número máximo de mensajes por carpeta de buzón de correo** Especifica el número máximo de mensajes que puede contener una carpeta de buzón de correo. Los nuevos mensajes no se entregarán ni se guardarán en una carpeta cuando se alcance este límite. 
    
- **Advertencia de número de mensajes por carpeta de buzón de correo** Especifica el número de mensajes que una carpeta de buzón de correo puede almacenar antes de Exchange Online envíe un mensaje de advertencia al propietario del buzón de correo. Cuando se alcanza esta cuota, se envían mensajes de advertencia una vez al día. 
    
- **Número máximo de mensajes por carpeta de la carpeta Elementos recuperables** Especifica el número máximo de mensajes que puede almacenarse en cada una de las carpetas de la carpeta Elementos recuperables. Cuando una carpeta supera este límite, ya no puede almacenar mensajes nuevos. Por ejemplo, si la carpeta Eliminaciones de la carpeta Elementos recuperables superó el límite de número de mensajes y el propietario del buzón intenta eliminar elementos de su buzón de forma permanente, no se podrá realizar la eliminación. 
    
- **Advertencia de número de mensajes por carpeta en la carpeta Elementos recuperables** Especifica el número de mensajes que puede contener cada carpeta de la carpeta Elementos recuperables antes de que Exchange Online registre un evento en el registro de eventos de la aplicación. 
    
- **Número máximo de subcarpetas por carpeta de buzón de correo** Especifica el número máximo de subcarpetas que se pueden crear en una carpeta de buzón de correo. El propietario del buzón no podrá crear una subcarpeta nueva una vez alcanzado este límite. 
    
- **Advertencia de número de subcarpetas por carpeta de buzón de correo** Especifica el número de subcarpetas que se pueden crear en una carpeta de buzón de correo antes de que Exchange Online envíe un mensaje de advertencia al propietario del buzón de correo. Cuando se alcanza esta cuota, se envían mensajes de advertencia una vez al día. 
    
- **Profundidad máxima de jerarquía de carpeta** Especifica el número máximo de niveles en la jerarquía de carpetas de una carpeta de buzón. El propietario del buzón no podrá crear otro nivel en la jerarquía de carpetas de la carpeta de buzón una vez alcanzado este límite. 
    
- **Advertencia de profundidad de jerarquía de carpeta** Especifica el número de niveles que se pueden crear en la jerarquía de carpeta de un buzón de correo antes de que Exchange Online envíe un mensaje de advertencia al propietario del buzón de correo. Cuando se alcanza esta cuota, se envían mensajes de advertencia una vez al día. 
    
- **Número máximo de carpetas públicas** Especifica el número máximo de carpetas públicas para toda la jerarquía de carpetas públicas. Cuando se alcanza este límite, deben eliminarse las carpetas públicas existentes para poder crear otras nuevas. 
    
- **Número máximo de subcarpetas por carpeta pública** Especifica el número máximo de subcarpetas que se pueden crear en una carpeta pública. Cuando se alcanza este límite, no se pueden crear subcarpetas nuevas en la carpeta pública. 
    
- **Advertencia de número de subcarpetas por carpeta pública** Especifica el número de subcarpetas que se pueden crear en una carpeta pública antes de que Exchange Online envíe un mensaje de advertencia al propietario de la carpeta. Si no hay ningún propietario, se enviarán mensajes de advertencia a los usuarios con permisos de propietario. Cuando se alcanza esta cuota, se envían mensajes de advertencia una vez al día. 
    
### <a name="mailbox-folder-limits-across-office-365-options"></a>Límites de la carpeta de buzón de correo de las distintas opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Office 365 Empresa Essentials** <br/> |**Office 365 Empresa Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Número máximo de mensajes por carpeta de buzón de correo  <br/> |1 millón  <br/> |1 millón  <br/> |1 millón  <br/> |1 millón  <br/> |1 millón  <br/> |1 millón  <br/> |
|Advertencia de número de mensajes por carpeta de buzón de correo  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |
|Número máximo de mensajes por carpeta de la carpeta Elementos recuperables  <br/> |3 millones  <br/> |3 millones  <br/> |3 millones  <br/> |3 millones  <br/> |3 millones  <br/> |3 millones  <br/> |
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón principal (no en espera)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón principal (en espera)  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón de archivo (no en espera)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |Ilimitado<sup>2</sup> <br/> |Ilimitado<sup>2</sup> <br/> |30 GB  <br/> |
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón de archivo (en espera)  <br/> |100 GB<sup>1</sup> <br/> |100 GB<sup>1</sup> <br/> |100 GB<sup>1</sup> <br/> |Ilimitado<sup>2</sup> <br/> |Ilimitado<sup>2</sup> <br/> |100 GB<sup>1</sup> <br/> |
|Advertencia de número de mensajes por carpeta en la carpeta Elementos recuperables  <br/> |2,75 millones  <br/> |2,75 millones  <br/> |2,75 millones  <br/> |2,75 millones  <br/> |2,75 millones  <br/> |2,75 millones  <br/> |
|Número máximo de subcarpetas por carpeta de buzón de correo  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |
|Advertencia de número de subcarpetas por carpeta de buzón de correo  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |
|Profundidad máxima de jerarquía de carpeta  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |
|Advertencia de profundidad de jerarquía de carpeta  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Número máximo de carpetas públicas  <br/> |500,000  <br/> |500,000  <br/> |500,000  <br/> |500,000  <br/> |500,000  <br/> |No disponible  <br/> |
|Número máximo de subcarpetas por carpeta pública  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |No disponible  <br/> |
|Advertencia de número de subcarpetas por carpeta pública  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |No disponible  <br/> |
   
> [!NOTE]
> <sup>1</sup> es la cuota de almacenamiento para la carpeta elementos recuperables, no la cuota para el buzón de archivo completo. La cuota de almacenamiento para el buzón de archivo sea ilimitada para los usuarios con una licencia de Exchange Online Plan 2 o para los usuarios que tienen un Exchange Online Plan 1 y una licencia de archivado de Exchange Online. Para obtener información acerca de cómo aumentar la cuota de elementos recuperables, vea [aumentar la cuota de buzones de correo en suspensión de elementos recuperables](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx).<br/> <sup>2</sup> la cuota de almacenamiento de información inicial para la carpeta elementos recuperables de un buzón de archivo es de 100 GB. Cuando está activado el crecimiento automático de archivado, almacenamiento adicional se agrega automáticamente cuando se alcanza la capacidad de almacenamiento para la carpeta elementos recuperables. Para obtener más información, vea [información general sobre el archivo ilimitado en Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Vea la [Guía básica de Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) para obtener información detallada acerca de la disponibilidad de ampliación automática archivado. 
  
### <a name="mailbox-folder-limits-across-standalone-plans"></a>Límites de carpetas de buzones de correo de los distintos planes independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (plan 1)** <br/> |**Exchange Online (plan 2)** <br/> |**Quiosco de Exchange Online** <br/> |
|Número máximo de mensajes por carpeta de buzón de correo  <br/> |Sin límite<sup>1</sup> <br/> |1 millón  <br/> |1 millón  <br/> |1 millón  <br/> |
|Advertencia de número de mensajes por carpeta de buzón de correo  <br/> |Sin límite  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |
|Número máximo de mensajes por carpeta de la carpeta Elementos recuperables  <br/> |Sin límite  <br/> |3 millones  <br/> |3 millones  <br/> |3 millones  <br/> |
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón principal (no en espera)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón principal (en espera)  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón de archivo (no en espera)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón de archivo (en espera)  <br/> |100 GB<sup>2</sup> <br/> |100 GB<sup>2</sup> <br/> |Ilimitado<sup>3</sup> <br/> |Ilimitado<sup>3</sup> <br/> |
|Advertencia de número de mensajes por carpeta en la carpeta Elementos recuperables  <br/> |Sin límite  <br/> |2,75 millones  <br/> |2,75 millones  <br/> |2,75 millones  <br/> |
|Número máximo de subcarpetas por carpeta de buzón de correo  <br/> |Sin límite  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|Advertencia de número de subcarpetas por carpeta de buzón de correo  <br/> |Sin límite  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Profundidad máxima de jerarquía de carpeta  <br/> |Sin límite  <br/> |300  <br/> |300  <br/> |300  <br/> |
|Advertencia de profundidad de jerarquía de carpeta  <br/> |Sin límite  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Número máximo de carpetas públicas  <br/> |1,000,000  <br/> |100,000  <br/> |100,000  <br/> |No disponible  <br/> |
|Número máximo de subcarpetas por carpeta pública  <br/> |N/D  <br/> |1,000  <br/> |1,000  <br/> |No disponible  <br/> |
|Advertencia de número de subcarpetas por carpeta pública  <br/> |N/D  <br/> |900  <br/> |900  <br/> |No disponible  <br/> |
   
> [!NOTE]
> <sup>1</sup> Microsoft recomienda no más de 1.000.000 mensajes por carpeta de buzón de correo. ><br/> <sup>2</sup> es la cuota de almacenamiento para la carpeta elementos recuperables, no la cuota para el buzón de archivo completo. La cuota de almacenamiento para el buzón de archivo sea ilimitada para los usuarios con una licencia de Exchange Online Plan 2 o para los usuarios que tienen un Exchange Online Plan 1 y una licencia de archivado de Exchange Online. Para obtener información acerca de cómo aumentar la cuota de elementos recuperables, vea [aumentar la cuota de buzones de correo en suspensión de elementos recuperables](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx).<br/> <sup>3</sup> la cuota de almacenamiento de información inicial para la carpeta elementos recuperables de un buzón de archivo es de 100 GB. Cuando está activado el crecimiento automático de archivado, almacenamiento adicional se agrega automáticamente cuando se alcanza la capacidad de almacenamiento para la carpeta elementos recuperables. Para obtener más información, vea [información general sobre el archivo ilimitado en Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Vea la [Guía básica de Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) para obtener información detallada acerca de la disponibilidad de ampliación automática archivado. 
  
## <a name="message-limits"></a>Límites de mensajes

Los siguientes límites se aplican a todos los mensajes de correo electrónico.
  
- **Límite del tamaño del mensaje** Los límites del tamaño del mensaje son necesarios para evitar que los mensajes grandes bloqueen la entrega de otros mensajes y que afecten al rendimiento del servicio de todos los usuarios. Estos límites incluyen documentos adjuntos y se aplican a todos los mensajes de la organización (entrantes, salientes e internos). Los mensajes más grandes que este límite no se entregarán y el remitente recibirá un informe de no entrega (NDR). Aunque los límites de tamaño de los mensajes se pueden configurar hacia arriba, abajo o por usuario, los administradores además pueden crear reglas de transporte para limitar el tamaño máximo de un adjunto concreto. Para obtener más información, consulte [Office 365 ahora admite mensajes de correo electrónico más grandes](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/).
    
    > [!NOTE]
    > Los clientes de correo electrónico particulares pueden tener límites de tamaño de mensajes más bajos o pueden limitar el tamaño de un archivo adjunto concreto a un valor inferior al límite de tamaño del mensaje de Exchange Online. 
  
- **Límite de longitud del asunto** La cantidad máxima de caracteres de texto permitidos en la línea de asunto de un mensaje de correo electrónico. 
    
- **Límite de datos adjuntos del archivo** El número máximo de datos adjuntos permitidos en un mensaje de correo electrónico. Aunque el tamaño total de todos los datos adjuntos no infrinja el límite de tamaño del mensaje, sigue habiendo un límite en cuanto al número de datos adjuntos permitidos en el mensaje. Este límite está controlado por el límite de mensaje con varias partes. 
    
- **Límite del tamaño de un archivo de datos adjunto** El tamaño máximo de archivo de un solo dato adjunto. 
    
    > [!NOTE]
    > Este es el tamaño de archivo máximo de un solo archivo adjunto. Los programas de clientes individuales, incluido Outlook Web App, pueden limitar el tamaño de los archivos adjuntos por debajo de este valor máximo. Exchange ActiveSync no implementa límites de tamaño de archivo adjunto en archivos adjuntos individuales. El tamaño total de todos los archivos adjuntos en un mensaje de Exchange ActiveSync debe ser inferior al límite de tamaño del mensaje. 
  
- **Límite de mensaje con varias partes** El número máximo de partes del cuerpo del mensaje que se permiten en un mensaje MIME con varias partes. Este límite también controla el número máximo de archivos adjuntos permitidos en un mensaje. 
    
- **Límite de profundidad de incrustación de mensajes** La cantidad máxima de mensajes de correo electrónico reenviados que se permiten en un mensaje de correo electrónico. 
    
### <a name="message-limits-across-office-365-options"></a>Límites de mensajes en las opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Office 365 Empresa Essentials** <br/> |**Office 365 Empresa Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Límite de tamaño de mensaje - Outlook  <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |
|Límite de tamaño de mensaje - OWA  <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |
|Límite de tamaño de mensaje - Outlook para Mac  <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |
|Límite de tamaño de mensaje: migración  <br/> |150 MB<sup>4</sup> <br/> |150 MB<sup>4</sup> <br/> |150 MB<sup>4</sup> <br/> |150 MB<sup>4</sup> <br/> |150 MB<sup>4</sup> <br/> |150 MB<sup>4</sup> <br/> |
|Límite de tamaño de los mensajes cifrados (para los suscriptores que usan el Cifrado de mensajes de Office 365 con nuevas funciones)<sup>5</sup> <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Límite de tamaño de los mensajes cifrados (para los suscriptores que usan la versión heredada del Cifrado de mensajes de Office 365)<sup>5</sup> <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
|Límite de longitud del asunto  <br/> |255 caracteres  <br/> |255 caracteres  <br/> |255 caracteres  <br/> |255 caracteres  <br/> |255 caracteres  <br/> |255 caracteres  <br/> |
|Límite de datos adjuntos  <br/> |250 datos adjuntos  <br/> |250 datos adjuntos  <br/> |250 datos adjuntos  <br/> |250 datos adjuntos  <br/> |250 datos adjuntos  <br/> |250 datos adjuntos  <br/> |
|Límite del tamaño de un archivo de datos adjunto - Outlook  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Límite del tamaño de un archivo de datos adjunto - OWA <sup>6</sup> <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |
|Límite del tamaño de un archivo de datos adjunto - Outlook para Mac  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Límite de mensaje con varias partes  <br/> |250 partes  <br/> |250 partes  <br/> |250 partes  <br/> |250 partes  <br/> |250 partes  <br/> |250 partes  <br/> |
|Límite de profundidad de incrustación de mensajes  <br/> |30 mensajes incrustados  <br/> |30 mensajes incrustados  <br/> |30 mensajes incrustados  <br/> |30 mensajes incrustados  <br/> |30 mensajes incrustados  <br/> |30 mensajes incrustados  <br/> |
   
> [!NOTE]
> <sup>1</sup> el tamaño máximo de mensaje predeterminado para los buzones de correo de Office 365 es 25 MB. Los administradores de Office 365 pueden especificar un límite personalizado entre 1 y 150 MB. Sin embargo, el tamaño de mensaje puede enviar o recibir también depende de lo que admite el cliente de correo electrónico o la solución. Para obtener más información acerca de cómo personalizar el tamaño máximo de mensaje permitido para su organización, vea [Office 365 ahora es compatible con los mensajes de correo electrónico más grandes](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/).<br/> <sup>2</sup> puede enviar y recibir una copia de seguridad a los mensajes de 150 MB entre los usuarios de Office 365 (que el mensaje nunca abandona los centros de datos de Office 365). Los mensajes que se enrutan fuera de los centros de datos de Office 365 están sujetos a una traducción 33% adicional codificación aumento, en cuyo caso el tamaño máximo de mensaje es 112 MB.<br/> <sup>3</sup> OWA cuentas para la posibilidad de que el mensaje puede estar sujeto al 33% de aumento de codificación y restringe el tamaño de mensaje que puede enviar en un 25% menor que el valor configurado. Por ejemplo, si personaliza la configuración para un tamaño de mensaje máximo de 100 MB, puede enviar mensajes no más de 75 MB.<br/> <sup>4</sup> Exchange Online calcula el tamaño de los mensajes que se van a mover a Exchange Online. Las versiones de Exchange anteriores a Exchange Server 2013 pueden informar de un tamaño de elemento más pequeño. Este límite se aplica para mover migraciones basadas mediante cualquier servicio de replicación de buzones de Exchange que sea compatible. Otros métodos de migración (total, preconfigurada, IMAP, PST) y otras herramientas de terceros están limitados por el límite de tamaño de mensaje general. <br/> <sup>5</sup> Para obtener información sobre OME con nuevas funciones, vea [Configurar las nuevas funciones de Cifrado de mensajes de Office 365 basadas en Azure Information Protection](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US).<br/> <sup>6</sup> No puede adjuntar un único archivo que supere los 35 MB. Además, no puede adjuntar archivos que colectivamente superen los 35 MB. Por ejemplo, si adjunta un archivo de 34 MB, solo puede adjuntar un archivo de 1 MB adicional. 
  
### <a name="message-limits-across-standalone-options"></a>Límites de mensajes en las opciones independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (plan 1)** <br/> |**Exchange Online (plan 2)** <br/> |**Quiosco de Exchange Online** <br/> |
|Límite de tamaño de mensaje - Outlook  <br/> |<sup>4</sup> de 10 MB <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>2</sup> <br/> |
|Límite de tamaño de mensaje - OWA  <br/> |<sup>4</sup> de 10 MB <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |
|Límite de tamaño de mensaje - Outlook para Mac  <br/> |<sup>4</sup> de 10 MB <br/> |150 MB  <br/> |150 MB  <br/> ||
|Límite de tamaño de mensaje: migración  <br/> |No aplicable  <br/> |150 MB<sup>5</sup> <br/> |150 MB<sup>5</sup> <br/> |150 MB<sup>5</sup> <br/> |
|Límite de tamaño de los mensajes cifrados (para los suscriptores que usan el Cifrado de mensajes de Office 365 con nuevas funciones)<sup>6</sup> <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Límite de tamaño de los mensajes cifrados (para los suscriptores que usan la versión heredada del Cifrado de mensajes de Office 365)<sup>6</sup> <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
|Límite de longitud del asunto  <br/> |255 caracteres  <br/> |255 caracteres  <br/> |255 caracteres  <br/> |255 caracteres  <br/> |
|Límite de datos adjuntos  <br/> |1024 datos adjuntos<sup>4</sup> <br/> |250 datos adjuntos  <br/> |250 datos adjuntos  <br/> |250 datos adjuntos  <br/> |
|Límite del tamaño de un archivo de datos adjunto - Outlook  <br/> |35 MB<sup>4</sup> <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Límite del tamaño de un archivo de datos adjunto - OWA  <br/> |35 MB<sup>4</sup> <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |
|Límite del tamaño de un archivo de datos adjunto - Outlook para Mac  <br/> |35 MB<sup>4</sup> <br/> |150 MB  <br/> |150 MB  <br/> |35 MB  <br/> |
|Límite de mensaje con varias partes  <br/> |250 partes  <br/> |250 partes  <br/> |250 partes  <br/> |250 partes  <br/> |
|Límite de profundidad de incrustación de mensajes  <br/> |30 mensajes incrustados  <br/> |30 mensajes incrustados  <br/> |30 mensajes incrustados  <br/> |30 mensajes incrustados  <br/> |
   
> [!NOTE]
> <sup>1</sup> los administradores de office 365 puede especificar un límite personalizado entre 1 y 150 MB. Sin embargo, el tamaño de mensaje puede enviar o recibir también depende de lo que admite el cliente de correo electrónico o la solución. Para obtener más información acerca de cómo personalizar el tamaño máximo de mensaje permitido para su organización, vea [Office 365 ahora es compatible con los mensajes de correo electrónico más grandes](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/).<br/> <sup>2</sup> puede enviar y recibir una copia de seguridad a los mensajes de 150 MB entre los usuarios de Office 365 (que el mensaje nunca abandona los centros de datos de Office 365). Los mensajes que se enrutan fuera de los centros de datos de Office 365 están sujetos a una traducción 33% adicional codificación aumento, en cuyo caso el tamaño máximo de mensaje es 112 MB.<br/> <sup>3</sup> OWA cuentas para la posibilidad de que el mensaje puede estar sujeto al 33% de aumento de codificación y restringe el tamaño de mensaje que puede enviar en un 25% menor que el valor configurado. Por ejemplo, si personaliza la configuración para un tamaño de mensaje máximo de 100 MB, puede enviar mensajes no más de 75 MB.<br/> <sup>4</sup> esto es el límite predeterminado para las organizaciones de Exchange Server 2013. Los administradores pueden cambiar este valor para su organización.<br/> <sup>5</sup> se calcula el tamaño de los mensajes que desea mover a Exchange Online por Exchange Online. Las versiones de Exchange anteriores a Exchange Server 2013 pueden presentarse a un tamaño más pequeño de elemento.<br/> <sup>6</sup> Para obtener información sobre OME con nuevas funciones, vea [Configurar las nuevas funciones de Cifrado de mensajes de Office 365 basadas en Azure Information Protection](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US). 
  
## <a name="receiving-and-sending-limits"></a>Límites de envío y recepción

Los límites de envío y recepción se aplican para combatir el correo no deseado o el envío masivo por correo de gusanos o virus. Estos límites ayudan a proteger nuestros sistemas y a mantener seguros a nuestros usuarios.
  
### <a name="receiving-limits"></a>Límites de recepción

Los límites de recepción se aplican al número de mensajes que un usuario, grupo o carpeta pública pueden recibir por hora. Esto se aplica tanto a los mensajes recibidos de Internet como de los servidores locales. Al superar el límite de recepción, los mensajes de correo electrónico enviados al buzón recibirá un informe de no entrega que indica que el buzón ha superado el umbral de entrega máximo. Pasada una hora, se actualizará el límite y el buzón podrá volver a recibir mensajes.
  
||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Office 365 Empresa Essentials** <br/> |**Office 365 Empresa Premium Office** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Mensajes recibidos  <br/> |3.600 mensajes por hora  <br/> |3.600 mensajes por hora  <br/> |3.600 mensajes por hora  <br/> |3.600 mensajes por hora  <br/> |3600 mensajes por hora  <br/> |3600 mensajes por hora  <br/> |
   
### <a name="sending-limits"></a>Límites de envío

Los límites de envío se aplican al número de destinatarios, número de mensajes y número de destinatarios por mensaje que puede enviar un usuario desde su cuenta de Exchange Online.
  
> [!NOTE]
> Para los grupos de distribución almacenados en la libreta de direcciones de una organización, el grupo se contabiliza como un destinatario. Para los grupos de distribución almacenados en la carpeta Contactos de un buzón de correo, los miembros del grupo se contabilizan de forma individual. 
  
- **Límite de frecuencia de destinatarios** Para disuadir la entrega de mensajes de correo no solicitados masivos, Exchange Online tiene límites de destinatarios que evitan que los usuarios y las aplicaciones envíen grandes volúmenes de correo electrónico. Estos límites se aplican por usuario a todos los mensajes (salientes e internos). 
    
    > [!NOTE]
    > Los clientes de Exchange Online que deben enviar un correo electrónico comercial masivo válido (por ejemplo, boletines para clientes) deberían usar proveedores de terceros especializados en dichos servicios. 
  
- **Límite de destinatarios** La cantidad máxima de destinatarios permitidos en los campos Para:, CC: y CCO: en un solo mensaje de correo electrónico. 
    
    > [!NOTE]
    > Para el límite de frecuencia de destinatarios y el límite de destinatarios, un grupo de distribución almacenado en la libreta de direcciones compartida de la organización se cuenta como un destinatario. En una lista personal de distribución, cada destinatario se cuenta por separado. 
  
- **Límite de frecuencia de mensajes** Los límites de frecuencia de mensajes determinan el número de mensajes que un usuario puede enviar desde su cuenta de Exchange Online durante un período determinado. Este límite ayuda a prevenir el consumo excesivo de recursos del sistema por un solo remitente. Si un usuario envía mensajes a una velocidad que supera el límite mediante el envío de cliente SMTP, se rechazarán los mensajes y el cliente tendrá que volver a intentarlo. 
    
#### <a name="sending-limits-across-office-365-options"></a>Límites de envío en las opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Office 365 Empresa Essentials** <br/> |**Office 365 Empresa Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Límite de frecuencia de destinatario  <br/> |10 000 destinatarios por día  <br/> |10 000 destinatarios por día  <br/> |10 000 destinatarios por día  <br/> |10 000 destinatarios por día  <br/> |10 000 destinatarios por día  <br/> |10 000 destinatarios por día  <br/> |
|Límite de destinatarios  <br/> |500 destinatarios  <br/> |500 destinatarios  <br/> |500 destinatarios  <br/> |500 destinatarios  <br/> |500 destinatarios  <br/> |500 destinatarios  <br/> |
|Límite de direcciones proxy de destinatarios  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |
|Límite de velocidad de transferencia de mensajes (solo envío del cliente SMTP)  <br/> |30 mensajes por minuto  <br/> |30 mensajes por minuto  <br/> |30 mensajes por minuto  <br/> |30 mensajes por minuto  <br/> |30 mensajes por minuto  <br/> |30 mensajes por minuto  <br/> |
   
#### <a name="sending-limits-across-standalone-options"></a>Límites de envío en las opciones independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (plan 1)** <br/> |**Exchange Online (plan 2)** <br/> |**Quiosco de Exchange Online** <br/> |
|Límite de frecuencia de destinatario  <br/> |Sin límite<sup>1</sup> <br/> |10 000 destinatarios por día  <br/> |10 000 destinatarios por día  <br/> |10 000 destinatarios por día  <br/> |
|Límite de destinatarios  <br/> |500 destinatarios<sup>1</sup> <br/> |500 destinatarios  <br/> |500 destinatarios  <br/> |500 destinatarios  <br/> |
|Límite de direcciones proxy de destinatarios  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |
   
> [!NOTE]
> <sup>1</sup> Es el límite predeterminado para organizaciones de Exchange Server 2013. Los administradores pueden cambiar este valor para su organización. 
  
## <a name="reporting-and-message-trace-limits"></a>Límites de seguimiento de mensajes y creación de informes
<a name="bkmk_Reporting_Message_Trace_Limits"> </a>

Para conocer los límites de seguimiento de mensajes y creación de informes, vea la sección sobre disponibilidad y latencia de datos de seguimiento de mensajes y creación de informes en [Informes y seguimiento de mensajes en la Protección en línea de Exchange](http://go.microsoft.com/fwlink/p/?LinkId=394248).
  
## <a name="retention-limits"></a>Límites de retención
<a name="RetentionLimits"> </a>

Estos límites controlan el tiempo durante el cual es posible obtener acceso a los elementos de determinadas carpetas de la Bandeja de entrada.
  
- **Período de retención de la carpeta Elementos eliminados** La cantidad máxima de días que los elementos pueden permanecer en la carpeta Elementos eliminados antes de que se quiten automáticamente. 
    
- **Período de retención de los elementos quitados de la carpeta Elementos eliminados** Se conserva el número máximo de días que los elementos quitados de la carpeta Elementos eliminados antes de eliminarse permanentemente. 
    
- **Período de retención de la carpeta Correo no deseado** La cantidad máxima de días que los elementos pueden permanecer en la carpeta Correo no deseado antes de que se quiten automáticamente. 
    
### <a name="retention-limits-across-office-365-options"></a>Límites de retención en las opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Office 365 Empresa Essentials** <br/> |**Office 365 Empresa Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Período de retención de la carpeta Elementos eliminados  <br/> |Sin límite<sup>1</sup> <br/> |Sin límite<sup>1</sup> <br/> |Sin límite<sup>1</sup> <br/> |Sin límite<sup>1</sup> <br/> |Sin límite<sup>1</sup> <br/> |Sin límite<sup>1</sup> <br/> |
|Período de retención de los elementos quitados de la carpeta Elementos eliminados  <br/> |<sup>1</sup> de 14 días <br/> |<sup>1</sup> de 14 días <br/> |<sup>1</sup> de 14 días <br/> |<sup>1</sup> de 14 días <br/> |<sup>1</sup> de 14 días <br/> |<sup>1</sup> de 14 días <br/> |
|Período de retención de la carpeta Correo no deseado  <br/> |30 días  <br/> |30 días  <br/> |30 días  <br/> |30 días  <br/> |30 días  <br/> |30 días  <br/> |
   
> [!NOTE]
> <sup>1</sup> Es el límite predeterminado. Los administradores pueden cambiar este valor para su organización. 
  
### <a name="retention-limits-across-standalone-options"></a>Límites de retención en las opciones independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (plan 1)** <br/> |**Exchange Online (plan 2)** <br/> |**Quiosco de Exchange Online** <br/> |
|Período de retención de la carpeta Elementos eliminados  <br/> |Sin límite<sup>1</sup> <br/> |Sin límite<sup>1</sup> <br/> |Sin límite<sup>1</sup> <br/> |Sin límite<sup>1</sup> <br/> |
|Período de retención de los elementos quitados de la carpeta Elementos eliminados  <br/> |<sup>1</sup> de 14 días <br/> |<sup>2</sup> de 14 días <br/> |<sup>2</sup> de 14 días <br/> |<sup>2</sup> de 14 días <br/> |
|Período de retención de la carpeta Correo no deseado  <br/> |<sup>1</sup> de 2 años <br/> |30 días  <br/> |30 días  <br/> |30 días  <br/> |
   
> [!NOTE]
> <sup>1</sup> Es el límite predeterminado. Los administradores pueden cambiar este valor para su organización.<br/> <sup>2</sup> esto es el valor predeterminado para las organizaciones de Exchange Online. Los administradores pueden cambiar este valor a un máximo de 30 días para los buzones de correo de su organización. 
  
## <a name="distribution-group-limits"></a>Límites de grupos de distribución

Estos límites se aplican a grupos de distribución en la libreta de direcciones compartida de su organización.
  
- **Número máximo de miembros de un grupo de distribución** La cantidad total de destinatarios se determina tras la expansión del grupo de distribución. 
    
- **Límite de envío de mensajes a grandes grupos de distribución** Los grupos de distribución que contienen este número de miembros especificado por este límite deben tener opciones configuradas de administración y aprobación de mensajes. La administración especifica una lista de remitentes con permiso para enviar mensajes al grupo de distribución. La aprobación de mensajes especifica uno o varios moderadores que deben aprobar que todos los mensajes se envíen al grupo de distribución. 
    
- **Tamaño máximo de mensaje para grandes grupos de distribución** Si un mensaje se envía a 5000 o más destinatarios, el tamaño del mensaje no puede exceder este límite. Si lo excede, el mensaje no se entrega y el remitente recibe un informe de no entrega (NDR). La contabilización total de destinatarios se determina tras la expansión del grupo de distribución. 
    
### <a name="distribution-group-limits-across-office-365-options"></a>Límites de grupos de distribución en las opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Office 365 Empresa Essentials** <br/> |**Office 365 Empresa Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Número máximo de miembros de un grupo de distribución<sup>1</sup> <br/> |100 000 miembros  <br/> |100 000 miembros  <br/> |100 000 miembros  <br/> |100 000 miembros  <br/> |100 000 miembros  <br/> |100 000 miembros  <br/> |
|Límite de envío de mensajes a un grupo de distribución grande  <br/> |5 000 o más miembros  <br/> |5 000 o más miembros  <br/> |5 000 o más miembros  <br/> |5 000 o más miembros  <br/> |5 000 o más miembros  <br/> |5 000 o más miembros  <br/> |
|Tamaño máximo de mensaje para grupos de distribución con 5.000 y 100.000 miembros  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
|Tamaño máximo de mensaje para grupos de distribución con 100.000 o más miembros  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |
|Número máximo de propietarios de un grupo de distribución  <br/> |10    <br/> |10    <br/> |10    <br/> |10    <br/> |10    <br/> |10    <br/> |
|Número máximo de grupos que un usuario puede crear  <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> si se usa la sincronización de directorios de Azure Active Directory, el número máximo de miembros del grupo de distribución que se pueden sincronizar desde su Active Directory local a Active Directory de Azure es 15.000. Si está usando Azure Connect de AD, ese número es 50.000.<br/> <sup>2</sup> Este límite se aplica también a los administradores. 
  
### <a name="distribution-group-limits-across-standalone-options"></a>Límites de grupo de distribución en las opciones independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (plan 1)** <br/> |**Exchange Online (plan 2)** <br/> |**Quiosco de Exchange Online** <br/> |
|Número máximo de miembros de un grupo de distribución  <br/> |100 000 miembros<sup>1</sup> <br/> |100 000 miembros  <br/> |100 000 miembros  <br/> |100 000 miembros  <br/> |
|Límite de envío de mensajes a un grupo de distribución grande  <br/> |5000 o más miembros<sup>1</sup> <br/> |5 000 o más miembros  <br/> |5 000 o más miembros  <br/> |5 000 o más miembros  <br/> |
|Número máximo de propietarios de un grupo de distribución  <br/> |10    <br/> |10    <br/> |10    <br/> |10    <br/> |
|Número máximo de grupos que un usuario puede crear  <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Es el límite predeterminado para organizaciones de Exchange Server 2013. Los administradores pueden cambiar este valor para su organización.<br/> <sup>2</sup> Este límite se aplica también a los administradores. 
  
## <a name="journal-transport-and-inbox-rule-limits"></a>Límites de las reglas de la Bandeja de entrada, del diario y de transporte

La lista siguiente incluye los límites que se aplican a las reglas del diario, a las reglas de transporte (también conocidas como reglas de toda la organización) y los límites que se aplican a la Bandeja de entrada. Los distintos usuarios configuran las reglas de la bandeja de entrada que se aplican a los mensajes que se envían y reciben en sus buzones correspondientes.
  
- **Número máximo de reglas del diario** El número máximo de reglas del diario que puede existir en la organización. 
    
- **Número máximo de reglas de transporte** El número máximo de reglas que puede existir en la organización. 
    
- **Tamaño máximo de una regla de transporte individual** El número máximo de caracteres que se pueden usar en una sola regla de transporte. Los caracteres se emplean en las condiciones, excepciones y acciones. 
    
- **Límite de caracteres para todas las expresiones regulares usadas en todas las reglas de transporte** El número total de caracteres usados por todas las expresiones regulares en todas las condiciones y excepciones de las reglas de transporte de una organización. Puede disponer de unas cuantas reglas que usen expresiones largas y complejas, o muchas reglas con expresiones regulares sencillas. 
    
- **Límites de análisis para el contenido de datos adjuntos** Las condiciones de regla de transporte le permiten examinar el contenido de los datos adjuntos del mensaje, pero se inspecciona solo el primer 1 MB del texto extraído de un archivo adjunto. Este límite de 1 MB se refiere al texto extraído de los datos adjuntos, no al tamaño de archivo de los datos adjuntos. Por ejemplo, un archivo de 2 MB puede tener menos de 1 MB de texto, por lo que se inspeccionaría todo el texto. 
    
- **Número máximo de recipientes agregados a un mensaje por todas las reglas de trasporte** Cuando en un mensaje actúan diferentes reglas de transporte, solo se puede agregar al mensaje un número finito de destinatarios. Una vez alcanzado el límite, los demás destinatarios no se agregan al mensaje. Asimismo, los grupos de distribución no pueden agregarse a un mensaje mediante una regla de transporte. 
    
- **Límite de reenvío** El número máximo de destinatarios que se puede configurar para una regla de transporte o de bandeja de entrada con una acción de redireccionamiento. Si se configura una regla para redireccionar un mensaje a más de este número de destinatarios, la regla no se aplicará y cualquier mensaje que satisfaga la condición de la regla no redirigirá ninguno de los destinatarios enumerados en la regla. 
    
- **Número de veces que se redirige un mensaje** El número de veces que se redirigirá, reenviará o responderá automáticamente un mensaje en función de las reglas de la Bandeja de entrada. Por ejemplo, el usuario A tiene una regla de Bandeja de entrada que redirige los mensajes al usuario B, en función del remitente. El usuario B tiene una regla de Bandeja de entrada que reenvía los mensajes al usuario C, en función de palabras clave en la línea del asunto. Si un mensaje cumple estas dos condiciones, el mensaje solo se envía al usuario B; no se reenvía al usuario C ya que solo se permite un redireccionamiento. En este caso, el mensaje se elimina sin enviarle al usuario B ningún informe de no entrega (NDR) que indique que el mensaje no se entregó al usuario C. 
    
### <a name="journal-transport-and-inbox-rule-limits-across-office-365-options"></a>Límites de reglas del diario, transporte y Bandeja de entrada en las opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Office 365 Empresa Essentials** <br/> |**Office 365 Empresa Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Número máximo de reglas del diario  <br/> |10 reglas  <br/> |10 reglas  <br/> |10 reglas  <br/> |10 reglas  <br/> |10 reglas  <br/> |10 reglas  <br/> |
|Número máximo de reglas de transporte  <br/> |300 reglas  <br/> |300 reglas  <br/> |300 reglas  <br/> |300 reglas  <br/> |300 reglas  <br/> |300 reglas  <br/> |
|Tamaño máximo de una regla de transporte individual  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |
|Límite de caracteres para todas las expresiones regulares usadas en todas las reglas de transporte  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |
|Límites de análisis para el contenido de datos adjuntos  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |
|Número máximo de destinatarios agregados a un mensaje por todas las reglas de trasporte  <br/> |100 destinatarios  <br/> |100 destinatarios  <br/> |100 destinatarios  <br/> |100 destinatarios  <br/> |100 destinatarios  <br/> |100 destinatarios  <br/> |
|Límite de reenvío  <br/> |10 destinatarios  <br/> |10 destinatarios  <br/> |10 destinatarios  <br/> |10 destinatarios  <br/> |10 destinatarios  <br/> |10 destinatarios  <br/> |
|Número de veces que se redirige un mensaje  <br/> |1 redireccionamiento  <br/> |1 redireccionamiento  <br/> |1 redireccionamiento  <br/> |1 redireccionamiento  <br/> |1 redireccionamiento  <br/> |1 redireccionamiento  <br/> |
   
### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>Límites de reglas del diario, transporte y Bandeja de entrada en las opciones independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (plan 1)** <br/> |**Exchange Online (plan 2)** <br/> |**Quiosco de Exchange Online** <br/> |
|Número máximo de reglas del diario  <br/> |Sin límite  <br/> |10 reglas  <br/> |10 reglas  <br/> |10 reglas  <br/> |
|Número máximo de reglas de transporte  <br/> |Sin límite  <br/> |300 reglas  <br/> |300 reglas  <br/> |300 reglas  <br/> |
|Tamaño máximo de una regla de transporte individual  <br/> |40 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |
|Límite de caracteres para todas las expresiones regulares usadas en todas las reglas de transporte  <br/> |Sin límite  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |
|Número máximo de destinatarios agregados a un mensaje por todas las reglas de trasporte  <br/> |Sin límite  <br/> |100 destinatarios  <br/> |100 destinatarios  <br/> |100 destinatarios  <br/> |
|Límite de reenvío  <br/> |Sin límite  <br/> |10 destinatarios  <br/> |10 destinatarios  <br/> |10 destinatarios  <br/> |
|Número de veces que se redirige un mensaje  <br/> |3 redireccionamientos  <br/> |1 redireccionamiento  <br/> |1 redireccionamiento  <br/> |1 redireccionamiento  <br/> |
  
## <a name="moderation-limits"></a>Límites de moderación
<a name="ModerationLimits"> </a>

Estos límites controlan la configuración de la moderación empleada para la aprobación de mensajes que se aplica a los grupos de distribución y las reglas de transporte.
  
- **Tamaño máximo de buzón de correo de arbitraje** Si el buzón de correo de arbitraje excede este límite, los mensajes que requieren moderación se devolverán al remitente en un informe de no entrega (NDR). 
    
- **Cantidad máxima de moderadores** La cantidad máxima de moderadores que puede asignar a un solo grupo de distribución moderado o que puede agregarse a un mensaje utilizando una regla de transporte. Tenga en cuenta que no puede especificar un grupo de distribución como moderador. 
    
- **Expiración de mensajes en espera de ser moderados** De forma predeterminada, un mensaje en espera de ser moderado expira a los dos días. No obstante, el procesamiento de mensajes moderados expirados se ejercita cada siete días. Esto significa que un mensaje moderado puede expirar en cualquier momento entre dos y nueve días. 
    
- **Máximo índice de mensajes de notificación de moderación caducada** Este límite establece la cantidad máxima de mensajes de notificación acerca de mensajes moderados expirados en el período de una hora. Este límite se coloca en cada base de datos de buzones de correo del centro de datos. 
    
    Durante períodos de gran actividad, algunos remitentes no recibirán mensajes de notificación de mensajes moderados que hayan expirado. Sin embargo, estas notificaciones aún se pueden detectar usando informes de entrega.
    
### <a name="moderation-limits-across-office-365-options"></a>Límites de moderación en las opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Office 365 Empresa Essentials** <br/> |**Office 365 Empresa Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Tamaño máximo de buzón de correo de arbitraje  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |
|Número máximo de moderadores  <br/> |10 moderadores  <br/> |10 moderadores  <br/> |10 moderadores  <br/> |10 moderadores  <br/> |10 moderadores  <br/> |10 moderadores  <br/> |
|Caducidad de mensajes en espera de ser moderados  <br/> |2 días  <br/> |2 días  <br/> |2 días  <br/> |2 días  <br/> |2 días  <br/> |2 días  <br/> |
|Máximo índice de mensajes de notificación de moderación caducada  <br/> |300 notificaciones de caducidad por hora  <br/> |300 notificaciones de caducidad por hora  <br/> |300 notificaciones de caducidad por hora  <br/> |300 notificaciones de caducidad por hora  <br/> |300 notificaciones de caducidad por hora  <br/> |300 notificaciones de caducidad por hora  <br/> |
   
### <a name="moderation-limits-across-standalone-options"></a>Límites de moderación en las opciones independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (plan 1)** <br/> |**Exchange Online (plan 2)** <br/> |**Quiosco de Exchange Online** <br/> |
|Tamaño máximo de buzón de correo de arbitraje  <br/> |Sin límite<sup>1</sup> <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |
|Número máximo de moderadores  <br/> |Sin límite  <br/> |10 moderadores  <br/> |10 moderadores  <br/> |10 moderadores  <br/> |
|Caducidad de mensajes en espera de ser moderados  <br/> |<sup>1</sup> de 5 días <br/> |2 días  <br/> |2 días  <br/> |2 días  <br/> |
|Máximo índice de mensajes de notificación de moderación caducada  <br/> |300 notificaciones de caducidad por hora  <br/> |300 notificaciones de caducidad por hora  <br/> |300 notificaciones de caducidad por hora  <br/> |300 notificaciones de caducidad por hora  <br/> |
   
> [!NOTE]
> <sup>1</sup> Es el límite predeterminado para organizaciones de Exchange Server 2013. Los administradores pueden cambiar este valor para su organización. 
  
## <a name="exchange-activesync-limits"></a>Límites de Exchange ActiveSync
<a name="BKMK_ExchangeActiveSync_Limits"> </a>

Los siguientes límites se aplican a Microsoft Exchange ActiveSync, un protocolo de cliente que sincroniza los datos de los buzones entre los dispositivos móviles y Exchange. 
  
- Límite de dispositivos de **Exchange ActiveSync** El número máximo de dispositivos de Exchange ActiveSync por buzón de correo. 
    
- Límite de eliminación de dispositivos de **Exchange ActiveSync** El número máximo de dispositivos de Exchange ActiveSync que un administrador de Exchange puede eliminar en un mes. 
    
- **Límite de datos adjuntos del archivo de Exchange ActiveSync** El tamaño máximo de datos adjuntos del mensaje que puede enviar o recibir un dispositivo de Exchange ActiveSync. 
    
### <a name="exchange-activesync-limits-across-office-365-options"></a>Límites de Exchange ActiveSync en las opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Office 365 Empresa Essentials** <br/> |**Office 365 Empresa Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Límite de dispositivos de Exchange ActiveSync  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |
|Límite de eliminación de dispositivos de Exchange ActiveSync  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |
|Límite de datos adjuntos del archivo de Exchange ActiveSync  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
   
### <a name="exchange-activesync-limits-across-standalone-options"></a>Límites de Exchange ActiveSync en opciones independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (plan 1)** <br/> |**Exchange Online (plan 2)** <br/> |**Quiosco de Exchange Online** <br/> |
|Límite de dispositivos de Exchange ActiveSync  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |
|Límite de eliminación de dispositivos de Exchange ActiveSync  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |
|Límite de datos adjuntos del archivo de Exchange ActiveSync  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
