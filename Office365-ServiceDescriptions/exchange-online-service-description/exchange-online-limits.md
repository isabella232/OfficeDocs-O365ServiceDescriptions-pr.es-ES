---
title: Límites de Exchange Online
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
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
ms.openlocfilehash: 8e76ab8e0c3391d77923f2b66f4d4842ae86a759
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776751"
---
# <a name="exchange-online-limits"></a>Límites de Exchange Online

Encuentre los límites de Exchange Online para las distintas áreas de servicio, entre los que se incluyen los límites de la libreta de direcciones, los de almacenamiento de los buzones y los de seguimiento de informes y mensajes.

> [!NOTE]
> Si necesita ayuda con una tarea o si está solucionando un problema, es posible que los artículos siguientes le resulten útiles:  <br/> • [Correo electrónico](https://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&amp;rs=en-US&amp;ad=US) (para obtener ayuda para crear y enviar correo electrónico)  <br/> •  [Correo electrónico en Office 365 para empresas: ayuda para administradores](https://go.microsoft.com/fwlink/?linkid=529722) <br/>   •  [Solucionar problemas de Outlook y Office 365 con el Asistente para soporte y recuperación para Office 365 de Microsoft](https://diagnostics.office.com/) <br/>  •  [Informes de no entrega de correo electrónico en Office 365](https://go.microsoft.com/fwlink/?linkid=526653) <br/> •  [Ayuda de Exchange Online](https://go.microsoft.com/fwlink/?linkid=825607)

Los límites de Microsoft Exchange Online pertenecen a una de las categorías siguientes:

- [Address book limits](#address-book-limits)

- [Mailbox storage limits](#mailbox-storage-limits)

- [Capacity alerts](#capacity-alerts)

- [Mailbox folder limits](#mailbox-folder-limits)

- [Message limits](#message-limits)

- [Límites de envío y recepción](#receiving-and-sending-limits)

- [Reporting and message trace limits](#reporting-and-message-trace-limits)

- [Retention limits](#retention-limits)

- [Distribution group limits](#distribution-group-limits)

- [Límites de las reglas de la Bandeja de entrada, del diario y de transporte](#journal-transport-and-inbox-rule-limits)

- [Límites de moderación](#moderation-limits)

- [Límites de Exchange ActiveSync](#exchange-activesync-limits)

> [!IMPORTANT]
> •  Los límites aplicados a una organización de Microsoft Office 365 pueden ser diferentes según el tiempo que la organización haya estado inscrita en el servicio. <br/> •  Cuando se cambia un límite en los centros de datos de Microsoft, la aplicación de los cambios en todos los clientes existentes puede tardar cierto tiempo. <br/> •  No puede modificar la mayoría de estos límites, pero usted y sus usuarios deben conocerlos. <br/> •  Estos límites se aplican tanto a los destinatarios internos como a los externos. <br/> •  De manera predeterminada, Exchange Online Protection (EOP) protege los buzones de Exchange Online. Para conocer los límites que se aplican a las características de EOP en Exchange Online, vea [Límites de Exchange Online Protection](../exchange-online-protection-service-description/exchange-online-protection-limits.md). <br/> •    Para obtener información acerca de límites de grupos de Office 365, vea "¿Cómo administrar mis grupos?" en [Más información sobre grupos de Office 365](https://go.microsoft.com/fwlink/?linkid=846714).

## <a name="address-book-limits"></a>Límites de la libreta de direcciones

- **Límite**de la lista de direcciones: el número máximo de listas de direcciones que se pueden crear en una organización de Exchange online o exchange Server 2013. Este número incluye las listas de direcciones predeterminadas en Exchange Online, como todos los contactos y todos los grupos.

    > [!NOTE]
    > Puede asignarse un máximo de 20 listas de direcciones a cada libreta de direcciones sin conexión (OAB).

- **Límite de la libreta de direcciones sin conexión**: el número máximo de libretas de direcciones sin conexión (OAB) que se pueden crear en una organización de Exchange online o exchange Server 2013.

- **Límite de directivas**de la libreta de direcciones: el número máximo de directivas de libreta de direcciones (ABP) que se crean en una organización de Exchange online o exchange Server 2013.

- **Listas globales de direcciones**: el número máximo de listas globales de direcciones (GAL) que se pueden crear en una organización de Exchange online o exchange Server 2013.

### <a name="address-book-limits-across-office-365-options"></a>Límites de la libreta de direcciones en las distintas opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Office 365 Empresa Essentials**|**Office 365 Empresa Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Límite de listas de direcciones|1000|1000|1000|1000|1000|1000|
|Límite de libretas de direcciones sin conexión (OAB)|250|250|250|250|250|250|
|Límite de directivas de libreta de direcciones (ABP)|250|250|250|250|250|250|
|Límite de listas globales de direcciones|250|250|250|250|250|250|

### <a name="address-book-limits-across-standalone-plans"></a>Límites de la libreta de direcciones a través de planes independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Exchange Server 2013**|**Exchange Online (plan 1)**|**Exchange Online (plan 2)**|**Quiosco de Exchange Online**|
|Límite de listas de direcciones|1000|1000|1000|1000|
|Límite de libretas de direcciones sin conexión (OAB)|250|250|250|250|
|Límite de directivas de libreta de direcciones (ABP)|250|250|250|250|
|Límite de listas globales de direcciones|250|250|250|250|

## <a name="mailbox-storage-limits"></a>Límites de almacenamiento de los buzones

El espacio de almacenamiento del buzón disponible para un usuario está determinado por el tipo de buzón y la licencia de suscripción del usuario. Los administradores pueden reducir el tamaño máximo del buzón de correo por usuario o de forma global.

> [!NOTE]
> Con el registro en diario, el uso de reglas de transporte o reglas de transferencia automática para copiar mensajes en un buzón de Exchange Online con fines de archivado no está permitido. El buzón de archivo de un usuario está diseñado exclusivamente para dicho usuario. Microsoft se reserva el derecho de denegar el archivado ilimitado si el buzón de archivo de un usuario se usa para almacenar datos de archivo de otros usuarios.

### <a name="storage-limits-across-office-365-options"></a>Límites de almacenamiento en las opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Office 365 Empresa Essentials**|**Office 365 Empresa Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Buzones de usuario|50 GB|50 GB|50 GB|100 GB|100 GB|2 GB|
|Buzones<sup>de archivo 7, 8</sup>|50 GB|50 GB|50 GB|Ilimitado<sup>1</sup>|Unlimited<sup>1</sup>|No disponible<sup>4</sup>|
|Buzones compartidos<sup>10</sup>|50 GB<sup>2</sup>|50 GB<sup>2</sup>|50 GB<sup>2</sup>|50 GB<sup>2,9</sup>|50 GB<sup>2,9</sup>|50 GB<sup>2</sup>|
|Buzones de recursos|50 GB<sup>3</sup>|50 GB<sup>3</sup>|50 GB<sup>3</sup>|50 GB<sup>3,9</sup>|50 GB<sup>3,9</sup>|50 GB<sup>3</sup>|
|Buzones de sitio<sup>5</sup>|50 GB|50 GB|50 GB|50 GB|50 GB|No disponible|
|Buzones de carpetas públicas|50 GB<sup>6</sup>|50 GB<sup>6</sup>|50 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|No disponible|
|Buzones de grupo|50 GB|50 GB|50 GB|50 GB|50 GB|50 GB|

> [!NOTE]
> <sup>1</sup> Cada usuario recibe inicialmente 100 GB de almacenamiento en el buzón de archivo. Cuando el archivado de expansión automática está activado, se agrega almacenamiento adicional automáticamente cuando se alcanza la capacidad de almacenamiento de 100 GB. Para obtener más información, vea [Información general sobre el archivado ilimitado en Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Vea el [Mapa de ruta de Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) para obtener información sobre la disponibilidad. <br/> <sup>2</sup> para acceder a un buzón compartido, un usuario debe tener una licencia de Exchange Online, pero el buzón de correo compartido no requiere una licencia independiente. Sin una licencia, los buzones compartidos están limitados a 50 GB. Para aumentar el límite de tamaño a 100 GB, el buzón compartido debe tener asignada una licencia de plan 2 de Exchange online o una licencia de plan 1 de Exchange Online con una licencia de complemento de archivado de Exchange Online. Esto también le permitirá habilitar el archivado de expansión automática para una cantidad ilimitada de capacidad de almacenamiento de archivos. De forma similar, si desea poner un buzón compartido en retención por juicio o asignarle una directiva de retención, el buzón de correo compartido debe tener una licencia de Exchange Online (plan 2) o una licencia de plan 1 de Exchange Online con una licencia de complemento de archivado de Exchange Online. <br/> <sup>3</sup> Los buzones de recursos no requieren licencia. Sin embargo, sin una licencia, los buzones compartidos están limitados a 50 GB. Para aumentar el tamaño del buzón, debe tener asignada una licencia E3 o E5. Esto aumentará el buzón en 100 GB. <br/> <sup>4</sup> Los buzones de archivo no están incluidos en Quiosco de Exchange Online. Sin embargo, se pueden adquirir como un complemento a través de Archivado de Exchange Online. Para obtener más información, vea [Descripción del servicio de archivado de Exchange Online](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md). <br/> <sup>5</sup> los buzones de sitio se quitaron de Exchange Online y SharePoint online en 2017. <br/> <sup>6</sup> Existe un límite de 1 000 buzones de carpetas públicas y un tamaño total máximo de 50 TB para todos los buzones de carpetas públicas. Los buzones que sirven a la jerarquía se limitan a 100 buzones de carpetas públicas. <br/> <sup>7</sup> Solo puede usarse los buzones de archivo para archivar correo de una sola entidad o un único usuario (como un buzón compartido) al que se le haya aplicado una licencia. No se permite usar los buzones de archivo para almacenar correo de varios usuarios o entidades. Por ejemplo, un administrador de TI no puede crear un buzón compartido ni permitir que los usuarios lo copien (con los campos CC o CCO, o mediante una regla de transporte) con el fin de archivarlo. Tenga en cuenta que un buzón compartido que usan varias personas en realidad no almacena correo electrónico de esos usuarios individuales. Varios usuarios tienen acceso y envían correos electrónicos como el buzón compartido. Por lo tanto, los únicos correos electrónicos que se almacenan en el buzón compartido son aquellos enviados a o desde él, *como* el buzón compartido. <br/> <sup>8</sup> Si ha creado una directiva de retención en Exchange Online, los mensajes se moverán automáticamente al buzón de archivos de un usuario solo si el tamaño del buzón principal del usuario supera los 10 MB. La directiva de retención no se ejecutará automáticamente para los buzones cuyo tamaño sea inferior a 10 MB. <br/> <sup>9</sup> Los buzones de recursos o compartidos no requieren licencia. Sin embargo, sin una licencia, los buzones compartidos están limitados a 50 GB. Para aumentar el tamaño del buzón, debe tener asignada una licencia E3 o E5. Esto aumentará el buzón en 100 GB. <br/> <sup>10</sup> de forma predeterminada, los buzones compartidos tienen una cuenta de usuario activa asociada con una contraseña (desconocida) generada por el sistema. Para bloquear el inicio de sesión para la cuenta de buzón de correo compartido asociada, vea [bloquear el inicio de sesión para la cuenta de buzón compartido](https://docs.microsoft.com/en-us/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account).

### <a name="storage-limits-across-standalone-plans"></a>Límites de almacenamiento en planes independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Exchange Server 2013**|**Exchange Online (plan 1)**|**Exchange Online (plan 2)**|**Quiosco de Exchange Online**|
|Buzones de usuario|2 GB<sup>1</sup>|50 GB|100 GB|2 GB|
|Buzones de archivo<sup>8, 9</sup>|100 GB<sup>1</sup>|50 GB|Ilimitado<sup>2</sup>|No disponible<sup>5</sup>|
|Buzones compartidos<sup>11</sup>|2 GB<sup>1</sup>|50 GB<sup>3</sup>|50 GB<sup>3,10</sup>|50 GB<sup>3</sup>|
|Buzones de recursos|2 GB<sup>1</sup>|50 GB<sup>4</sup>|50 GB<sup>4,10</sup>|50 GB<sup>4</sup>|
|Buzones de carpetas públicas|2 GB<sup>6</sup>|50 GB<sup>7</sup>|100 GB<sup>7</sup>|No disponible|
|Buzones de grupo|50 GB|50 GB|50 GB|50 GB|

> [!NOTE]
> <sup>1</sup> Es el tamaño de buzón predeterminado para organizaciones de Exchange Server 2013. Los administradores pueden cambiar este valor para su organización. No hay un límite máximo de almacenamiento para los buzones locales. <br/> <sup>2</sup> Cada usuario recibe inicialmente 100 GB de almacenamiento en el buzón de archivo. Cuando el archivado de expansión automática está activado, se agrega almacenamiento adicional automáticamente cuando se alcanza la capacidad de almacenamiento de 100 GB. Para obtener más información, vea [Información general sobre el archivado ilimitado en Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Vea el [Mapa de ruta de Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) para obtener más información acerca de la disponibilidad del archivado de expansión automática. <br/> <sup>3</sup> para acceder a un buzón compartido, un usuario debe tener una licencia de Exchange Online, pero el buzón de correo compartido no requiere una licencia independiente. Sin una licencia, los buzones compartidos están limitados a 50 GB. Para aumentar el límite de tamaño a 100 GB, el buzón compartido debe tener asignada una licencia de plan 2 de Exchange online o una licencia de plan 1 de Exchange Online con una licencia de complemento de archivado de Exchange Online. Esto también le permitirá habilitar el archivado de expansión automática para una cantidad ilimitada de capacidad de almacenamiento de archivos. De forma similar, si desea poner un buzón compartido en retención por juicio o asignarle una directiva de retención, el buzón de correo compartido debe tener una licencia de Exchange Online (plan 2) o una licencia de plan 1 de Exchange Online con una licencia de complemento de archivado de Exchange Online. <br/> <sup>4</sup> Los buzones de recursos no requieren licencia. Sin embargo, sin una licencia, los buzones compartidos están limitados a 50 GB. Para aumentar el tamaño del buzón, debe tener asignada una licencia del Plan 2 de Exchange Online. Esto aumentará el buzón en 100 GB. <br/> <sup>5</sup> Los buzones de archivo no están incluidos en Quiosco de Exchange Online. Sin embargo, se pueden adquirir como un complemento a través de Archivado de Exchange Online. Para obtener más información, vea [Descripción del servicio de archivado de Exchange Online](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md). <br/> <sup>6</sup> Es el tamaño de buzón predeterminado para organizaciones de Microsoft Exchange Server 2013. Los administradores pueden cambiar este valor para su organización. En Exchange Server 2013, existe un límite de 100 buzones de carpetas públicas y un tamaño total máximo de 50 TB para todos los buzones de carpetas públicas. <br/> <sup>7</sup> En Exchange Online, existe un límite de 1 000 buzones de carpetas públicas y un tamaño total máximo de 50 TB para todos los buzones de carpetas públicas.  <br/> <sup>8</sup> Los buzones de archivo solo pueden usarse para archivar correo de una sola entidad o un único usuario al que se le haya aplicado una licencia. No se permite usar los buzones de archivo para almacenar correo de varios usuarios o entidades. Por ejemplo, los administradores de TI no pueden crear buzones compartidos ni permitir que los usuarios copien (con los campos CC o CCO, o mediante una regla de transporte) buzones compartidos para archivarlos. <br/> <sup>9</sup> Si ha creado una directiva de retención en Exchange Online, los mensajes se moverán automáticamente al buzón de archivos de un usuario solo si el tamaño del buzón principal del usuario supera los 10 MB. La directiva de retención no se ejecutará automáticamente para los buzones cuyo tamaño sea inferior a 10 MB. <br/> <sup>10</sup> Los buzones de recursos o compartidos no requieren una licencia asignada. Sin embargo, sin una licencia, estos buzones están limitados a 50 GB. Para aumentar el tamaño del buzón, debe tener asignada una licencia del Plan 2 de Exchange Online. Esto aumentará el buzón en 100 GB. <br/> <sup>11</sup> de forma predeterminada, los buzones compartidos tienen una cuenta de usuario activa asociada con una contraseña (desconocida) generada por el sistema. Para bloquear el inicio de sesión para la cuenta de buzón de correo compartido asociada, vea [bloquear el inicio de sesión para la cuenta de buzón compartido](https://docs.microsoft.com/en-us/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account).

## <a name="capacity-alerts"></a>Alertas de capacidad

Exchange Online ofrece tres tipos de notificaciones cuando el buzón de un usuario se acerca o alcanza su máxima capacidad:

- **ADVERTENCIA**: el usuario recibe un mensaje de advertencia que indica que el buzón de correo está llegando al límite de tamaño máximo. Esta advertencia está diseñada para animar a los usuarios a eliminar el correo no deseado.

- **Prohibir envío**: el usuario recibe un correo electrónico de notificación de prohibición de envío cuando se alcanza el límite de tamaño del buzón. El usuario no puede enviar nuevos mensajes hasta que se elimine suficiente correo para que el buzón de correo esté por debajo del límite de tamaño.

- **Prohibir envío o recepción**: Exchange Online rechaza los mensajes entrantes cuando se alcanza el límite de tamaño del buzón y envía un informe de no entrega (NDR) al remitente. El remitente tiene la opción de intentar reenviar el correo más tarde. Para volver a recibir mensajes, el usuario debe eliminar el correo electrónico hasta que esté por debajo del límite de tamaño.

### <a name="capacity-alerts-across-office-365-options"></a>Alertas de capacidad en las opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Office 365 Empresa Essentials**|**Office 365 Empresa Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Advertencia|49 GB|49 GB|49 GB|98 GB|98 GB|1,96 GB|
|Prohibir envío|49,5 GB|49,5 GB|49,5 GB|99 GB|99 GB|1,98 GB|
|Prohibir envío y recepción|50 GB|50 GB|50 GB|100 GB|100 GB|2 GB|

### <a name="capacity-alerts-across-standalone-plans"></a>Alertas de capacidad en planes independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Exchange Server 2013**|**Exchange Online (plan 1)**|**Exchange Online (plan 2)**|**Quiosco de Exchange Online**|
|Advertencia|1,9 GB<sup>1</sup>|49 GB|98 GB|1,96 GB|
|Prohibir envío|2 GB<sup>1</sup>|49,5 GB|99 GB|1,98 GB|
|Prohibir envío y recepción|2,3 GB<sup>1</sup>|50 GB|100 GB|2 GB|

> [!NOTE]
> <sup>1</sup> Este es el valor predeterminado para organizaciones de Exchange Server 2013. Los administradores pueden cambiar este valor para su organización.

## <a name="mailbox-folder-limits"></a>Límites de la carpeta de buzón de correo

Estos límites se usan para limitar el tamaño de los buzones de correo y garantizar la compatibilidad en Exchange Online. El objetivo de estos límites es evitar que exista un número ilimitado de elementos de buzón de correo por carpeta, un número ilimitado de carpetas por buzón de correo o un número ilimitado de carpetas públicas por organización de Exchange Online. Por cuestiones prácticas, los límites de carpetas de buzón de correo se aplican de forma permanente para garantizar la compatibilidad de la mayoría de los buzones de Exchange Online y locales que se migran a Exchange Online.

- **Número máximo de mensajes por carpeta de buzón de correo**: especifica el número máximo de mensajes para una carpeta de buzón de correo. Los nuevos mensajes no se entregarán ni se guardarán en una carpeta cuando se alcance este límite.

- **Advertencia de número de mensajes por carpeta de buzón de correo**: especifica el número de mensajes que puede contener una carpeta de buzón de correo antes de que Exchange Online envíe un mensaje de advertencia al propietario del buzón. Cuando se alcanza esta cuota, se envían mensajes de advertencia una vez al día.

- **Número máximo de mensajes por carpeta en la carpeta elementos recuperables**: especifica el número máximo de mensajes que se pueden incluir en cada carpeta de la carpeta elementos recuperables. Cuando una carpeta supera este límite, ya no puede almacenar mensajes nuevos. Por ejemplo, si la carpeta Eliminaciones de la carpeta Elementos recuperables superó el límite de número de mensajes y el propietario del buzón intenta eliminar elementos de su buzón de forma permanente, no se podrá realizar la eliminación.

- **Advertencia de número de mensajes por carpeta en la carpeta elementos recuperables**: especifica el número de mensajes que puede contener cada carpeta de la carpeta elementos recuperables antes de que Exchange Online registre un evento en el registro de eventos de la aplicación.

- **Número máximo de subcarpetas por carpeta de buzón de correo**: especifica el número máximo de subcarpetas que se pueden crear en una carpeta de buzón de correo. El propietario del buzón no podrá crear una subcarpeta nueva una vez alcanzado este límite.

- **Advertencia de número de subcarpetas por carpeta de buzón de correo**: especifica el número de subcarpetas que se pueden crear en una carpeta de buzón de correo antes de que Exchange Online envíe un mensaje de advertencia al propietario del buzón. Cuando se alcanza esta cuota, se envían mensajes de advertencia una vez al día.

- **Profundidad máxima de jerarquía de carpetas**: especifica el número máximo de niveles de la jerarquía de carpetas de un buzón. El propietario del buzón no podrá crear otro nivel en la jerarquía de carpetas de la carpeta de buzón una vez alcanzado este límite.

- **ADVERTENCIA para la profundidad de jerarquía de carpeta**: especifica el número de niveles de la jerarquía de carpetas de una carpeta de buzón de correo que se pueden crear antes de que Exchange Online envíe un mensaje de advertencia al propietario del buzón. Cuando se alcanza esta cuota, se envían mensajes de advertencia una vez al día.

- **Número máximo de carpetas públicas**: especifica el número máximo de carpetas públicas en toda la jerarquía de carpetas públicas. Cuando se alcanza este límite, deben eliminarse las carpetas públicas existentes para poder crear otras nuevas.

- **Número máximo de subcarpetas por carpeta pública**: especifica el número máximo de subcarpetas que se pueden crear en una carpeta pública. Cuando se alcanza este límite, no se pueden crear subcarpetas nuevas en la carpeta pública.

- **Advertencia de número de subcarpetas por carpeta pública**: especifica el número de subcarpetas que se pueden crear en una carpeta pública antes de que Exchange Online envíe un mensaje de advertencia al propietario de la carpeta. Si no hay ningún propietario, se enviarán mensajes de advertencia a los usuarios con permisos de propietario. Cuando se alcanza esta cuota, se envían mensajes de advertencia una vez al día.

### <a name="mailbox-folder-limits-across-office-365-options"></a>Límites de la carpeta de buzón de correo de las distintas opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Office 365 Empresa Essentials**|**Office 365 Empresa Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Número máximo de mensajes por carpeta de buzón de correo|1 millón|1 millón|1 millón|1 millón|1 millón|1 millón|
|Advertencia de número de mensajes por carpeta de buzón de correo|900,000|900,000|900,000|900,000|900,000|900,000|
|Número máximo de mensajes por carpeta de la carpeta Elementos recuperables|3 millones|3 millones|3 millones|3 millones|3 millones|3 millones|
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón principal (no en espera)|30 GB|30 GB|30 GB|30 GB|30 GB|30 GB|
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón principal (en espera)|100 GB|100 GB|100 GB|100 GB|100 GB|100 GB|
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón de archivo (no en espera)|30 GB|30 GB|30 GB|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|30 GB|
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón de archivo (en espera)|100 GB<sup>1</sup>|100 GB<sup>1</sup>|100 GB<sup>1</sup>|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|100 GB<sup>1</sup>|
|Advertencia de número de mensajes por carpeta en la carpeta Elementos recuperables|2,75 millones|2,75 millones|2,75 millones|2,75 millones|2,75 millones|2,75 millones|
|Número máximo de subcarpetas por carpeta de buzón de correo|10,000|10,000|10,000|10,000|10,000|10,000|
|Advertencia de número de subcarpetas por carpeta de buzón de correo|9000|9000|9000|9000|9000|9000|
|Profundidad máxima de jerarquía de carpeta|300|300|300|300|300|300|
|Advertencia de profundidad de jerarquía de carpeta|250|250|250|250|250|250|
|Número máximo de carpetas públicas|500 000|500 000|500 000|500 000|500 000|No disponible|
|Número máximo de subcarpetas por carpeta pública|10,000|10,000|10,000|10,000|10,000|No disponible|
|Advertencia de número de subcarpetas por carpeta pública|9000|9000|9000|9000|9000|No disponible|

> [!NOTE]
> <sup>1</sup> Es la cuota de almacenamiento de la carpeta Elementos recuperables, y no la cuota de todo el buzón de archivo. La cuota de almacenamiento del buzón de archivo es ilimitada para los usuarios que cuentan con una licencia de Exchange Online Plan 2 o para los usuarios que tienen una licencia de Plan 1 de Exchange Online y de Archivado de Exchange Online. Para obtener más información sobre la cuota de elementos recuperables, vea [Aumentar la cuota de elementos recuperables para los buzones de correo en retención](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx). <br/> <sup>2</sup> La cuota de almacenamiento inicial para la carpeta Elementos recuperables de un buzón de archivo es de 100 GB. Cuando el archivado de expansión automática está activado, se agrega almacenamiento adicional automáticamente cuando se alcanza la capacidad de almacenamiento de la carpeta Elementos recuperables. Para obtener más información, vea [Información general sobre el archivado ilimitado en Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Vea el [Mapa de ruta de Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) para obtener información sobre la disponibilidad del archivado de expansión automática.

### <a name="mailbox-folder-limits-across-standalone-plans"></a>Límites de carpetas de buzones de correo de los distintos planes independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Exchange Server 2013**|**Exchange Online (plan 1)**|**Exchange Online (plan 2)**|**Quiosco de Exchange Online**|
|Número máximo de mensajes por carpeta de buzón de correo|Sin límite<sup>1</sup>|1 millón|1 millón|1 millón|
|Advertencia de número de mensajes por carpeta de buzón de correo|Sin límite|900,000|900,000|900,000|
|Número máximo de mensajes por carpeta de la carpeta Elementos recuperables|Sin límite|3 millones|3 millones|3 millones|
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón principal (no en espera)|30 GB|30 GB|30 GB|30 GB|
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón principal (en espera)|100 GB|100 GB|100 GB|100 GB|
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón de archivo (no en espera)|30 GB|30 GB|30 GB|30 GB|
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón de archivo (en espera)|100 GB<sup>2</sup>|100 GB<sup>2</sup>|Unlimited<sup>3</sup>|Unlimited<sup>3</sup>|
|Advertencia de número de mensajes por carpeta en la carpeta Elementos recuperables|Sin límite|2,75 millones|2,75 millones|2,75 millones|
|Número máximo de subcarpetas por carpeta de buzón de correo|Sin límite|1000|1000|1000|
|Advertencia de número de subcarpetas por carpeta de buzón de correo|Sin límite|900|900|900|
|Profundidad máxima de jerarquía de carpeta|Sin límite|300|300|300|
|Advertencia de profundidad de jerarquía de carpeta|Sin límite|250|250|250|
|Número máximo de carpetas públicas|1,000,000|100,000|100,000|No disponible|
|Número máximo de subcarpetas por carpeta pública|N/D|1,000|1,000|No disponible|
|Advertencia de número de subcarpetas por carpeta pública|N/D|900|900|No disponible|

> [!NOTE]
> <sup>1</sup> Microsoft recomienda no más de 1 000 000 de mensajes por carpeta del buzón. > <br/> <sup>2</sup> Es la cuota de almacenamiento de la carpeta Elementos recuperables, y no la cuota de todo el buzón de archivo. La cuota de almacenamiento del buzón de archivo es ilimitada para los usuarios que cuentan con una licencia de Exchange Online Plan 2 o para los usuarios que tienen una licencia de Plan 1 de Exchange Online y de Archivado de Exchange Online. Para obtener más información sobre la cuota de elementos recuperables, vea [Aumentar la cuota de elementos recuperables para los buzones de correo en retención](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx). <br/> <sup>3</sup> La cuota de almacenamiento inicial para la carpeta Elementos recuperables de un buzón de archivo es de 100 GB. Cuando el archivado de expansión automática está activado, se agrega almacenamiento adicional automáticamente cuando se alcanza la capacidad de almacenamiento de la carpeta Elementos recuperables. Para obtener más información, vea [Información general sobre el archivado ilimitado en Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Vea el [Mapa de ruta de Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) para obtener información sobre la disponibilidad del archivado de expansión automática.

## <a name="message-limits"></a>Límites de mensajes

Los siguientes límites se aplican a todos los mensajes de correo electrónico.

- **Límite de tamaño**de mensajes: los límites de tamaño de los mensajes son necesarios para evitar que los mensajes grandes bloqueen la entrega de otros mensajes y afecten al rendimiento del servicio de todos los usuarios. Estos límites incluyen documentos adjuntos y se aplican a todos los mensajes de la organización (entrantes, salientes e internos). Los mensajes más grandes que este límite no se entregarán y el remitente recibirá un informe de no entrega (NDR). Aunque los límites de tamaño de los mensajes se pueden configurar hacia arriba, abajo o por usuario, los administradores además pueden crear reglas de transporte para limitar el tamaño máximo de un adjunto concreto. Para obtener más información, consulte [Office 365 ahora admite mensajes de correo electrónico más grandes](https://www.microsoft.com/en-us/microsoft-365/blog/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/).

    > [!NOTE]
    > Los clientes de correo electrónico particulares pueden tener límites de tamaño de mensajes más bajos o pueden limitar el tamaño de un archivo adjunto concreto a un valor inferior al límite de tamaño del mensaje de Exchange Online.

- **Límite de tamaño de encabezado de mensaje**: especifica el tamaño máximo de todos los campos de encabezado de mensaje de un mensaje. El límite actual es 256 KB. Si el tamaño total de todos los encabezados de mensajes supera los 256 KB, Exchange Online rechazará el mensaje con el error "552 5.3.4 El tamaño del encabezado excede el tamaño máximo establecido." No se tiene en cuenta el tamaño del cuerpo del mensaje ni de los datos adjuntos. Como los campos del encabezado son texto sin formato, el tamaño del encabezado lo determinan el número de caracteres de cada campo y el número total de campos del encabezado. Cada carácter de texto consume 1 byte.

- **Límite de longitud del asunto**: el número máximo de caracteres de texto permitidos en la línea de asunto de un mensaje de correo electrónico.

- **Límite de datos**adjuntos de archivos: el número máximo de archivos adjuntos permitidos en un mensaje de correo electrónico. Aunque el tamaño total de todos los datos adjuntos no infrinja el límite de tamaño del mensaje, sigue habiendo un límite en cuanto al número de datos adjuntos permitidos en el mensaje. Este límite está controlado por el límite de mensaje con varias partes.

- **Límite de tamaño**de los datos adjuntos del archivo: el tamaño máximo de archivo de un solo dato adjunto.

    > [!NOTE]
    > Este es el tamaño de archivo máximo de un solo archivo adjunto. Los programas de clientes individuales, incluido Outlook Web App, pueden limitar el tamaño de los archivos adjuntos por debajo de este valor máximo. Exchange ActiveSync no implementa límites de tamaño de archivo adjunto en archivos adjuntos individuales. El tamaño total de todos los archivos adjuntos en un mensaje de Exchange ActiveSync debe ser inferior al límite de tamaño del mensaje.

- **Límite de mensajes de varias partes**: el número máximo de partes del cuerpo del mensaje que se permiten en un mensaje MIME de varias partes. Este límite también controla el número máximo de archivos adjuntos permitidos en un mensaje.

- **Límite de profundidad del mensaje incrustado**: el número máximo de mensajes de correo electrónico reenviados que se permiten en un mensaje de correo electrónico.

### <a name="message-limits-across-office-365-options"></a>Límites de mensajes en las opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Office 365 Empresa Essentials**|**Office 365 Empresa Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Límite de tamaño de mensaje - Outlook|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|
|Límite de tamaño de mensaje - OWA|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|
|Límite de tamaño de mensaje - Outlook para Mac|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|
|Límite de tamaño de mensaje: migración|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|
|Límite de tamaño de los mensajes cifrados (para los suscriptores que usan el Cifrado de mensajes de Office 365 con nuevas funciones)<sup>5</sup>|150 MB|150 MB|150 MB|150 MB|150 MB|150 MB|
|Límite de tamaño de los mensajes cifrados (para los suscriptores que usan la versión heredada del Cifrado de mensajes de Office 365)<sup>5</sup>|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|Límite de longitud del asunto|255 caracteres|255 caracteres|255 caracteres|255 caracteres|255 caracteres|255 caracteres|
|Límite de datos adjuntos|250 datos adjuntos|250 datos adjuntos|250 datos adjuntos|250 datos adjuntos|250 datos adjuntos|250 datos adjuntos|
|Límite del tamaño de un archivo de datos adjunto - Outlook|150 MB|150 MB|150 MB|150 MB|150 MB|150 MB|
|Límite del tamaño de un archivo de datos adjunto - OWA <sup>6</sup>|35 MB|35 MB|35 MB|35 MB|35 MB|35 MB|
|Límite del tamaño de un archivo de datos adjunto - Outlook para Mac|150 MB|150 MB|150 MB|150 MB|150 MB|150 MB|
|Límite de mensaje con varias partes|250 partes|250 partes|250 partes|250 partes|250 partes|250 partes|
|Límite de profundidad de incrustación de mensajes|30 mensajes incrustados|30 mensajes incrustados|30 mensajes incrustados|30 mensajes incrustados|30 mensajes incrustados|30 mensajes incrustados|

> [!NOTE]
> <sup>1</sup> El tamaño máximo predeterminado de los buzones de Office 365 es 25 MB. Los administradores de Office 365 pueden especificar un límite personalizado entre 1 y 150 MB. Sin embargo, el tamaño de los mensajes que usted puede enviar o recibir también depende de qué admite el cliente de correo electrónico o la solución. Para obtener más información sobre cómo personalizar el tamaño máximo de mensaje permitido para su organización, consulte [Office 365 now supports larger email messages](https://www.microsoft.com/en-us/microsoft-365/blog/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/) (Office 365 ahora admite mensajes de correo electrónico más grandes). <br/> <sup>2</sup> Pueden enviarse y recibirse mensajes de hasta 150 MB entre los usuarios de Office 365 (los mensajes nunca abandonan los centros de datos de Office 365). Los mensajes que se enrutan fuera de los centros de datos de Office 365 están sujetos a un aumento de codificación de traducción de 33 % adicional, en cuyo caso el tamaño máximo de mensaje es 112 MB. <br/> <sup>3</sup> OWA permite que su mensaje esté sujeto al incremento de codificación del 33 % y limita el tamaño del mensaje que se puede enviar al 25 % menos que el valor configurado. Por ejemplo, si personaliza la configuración de tamaño de mensaje máximo en 100 MB, no se pueden enviar mensajes que superen los 75 MB. <br/> <sup>4</sup> Exchange Online calcula el tamaño de los mensajes que desea mover a Exchange Online. Las versiones de Exchange anteriores a Exchange Server 2013 pueden informar un tamaño de elemento más pequeño. Este límite se aplica para mover migraciones basadas mediante cualquier servicio de replicación de buzones de Exchange que sea compatible. Otros métodos de migración (total, preconfigurada, IMAP, PST) y otras herramientas de terceros están limitados por el límite de tamaño de mensaje general. <br/> 
  <sup>5</sup> Para obtener información sobre OME con nuevas funciones, vea [Configurar las nuevas funciones de Cifrado de mensajes de Office 365 basadas en Azure Information Protection](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US). <br/> <sup>6</sup> No puede adjuntar un único archivo que supere los 35 MB. Además, no puede adjuntar archivos que colectivamente superen los 35 MB. Por ejemplo, si adjunta un archivo de 34 MB, solo puede adjuntar un archivo de 1 MB adicional.

### <a name="message-limits-across-standalone-options"></a>Límites de mensajes en las opciones independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Exchange Server 2013**|**Exchange Online (plan 1)**|**Exchange Online (plan 2)**|**Quiosco de Exchange Online**|
|Límite de tamaño de mensaje - Outlook|10 MB<sup>4</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>2</sup>|
|Límite de tamaño de mensaje - OWA|10 MB<sup>4</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|150 MB<sup>1, 2</sup>|
|Límite de tamaño de mensaje - Outlook para Mac|10 MB<sup>4</sup>|150 MB|150 MB||
|Límite de tamaño de mensaje: migración|No aplicable|150 MB<sup>5</sup>|150 MB<sup>5</sup>|150 MB<sup>5</sup>|
|Límite de tamaño de los mensajes cifrados (para los suscriptores que usan el Cifrado de mensajes de Office 365 con nuevas funciones)<sup>6</sup>|150 MB|150 MB|150 MB|150 MB|
|Límite de tamaño de los mensajes cifrados (para los suscriptores que usan la versión heredada del Cifrado de mensajes de Office 365)<sup>6</sup>|25 MB|25 MB|25 MB|25 MB|
|Límite de longitud del asunto|255 caracteres|255 caracteres|255 caracteres|255 caracteres|
|Límite de datos adjuntos|1024 attachments<sup>4</sup>|250 datos adjuntos|250 datos adjuntos|250 datos adjuntos|
|Límite del tamaño de un archivo de datos adjunto - Outlook|35 MB<sup>4</sup>|150 MB|150 MB|150 MB|
|Límite del tamaño de un archivo de datos adjunto - OWA|35 MB<sup>4</sup>|35 MB|35 MB|35 MB|
|Límite del tamaño de un archivo de datos adjunto - Outlook para Mac|35 MB<sup>4</sup>|150 MB|150 MB|35 MB|
|Límite de mensaje con varias partes|250 partes|250 partes|250 partes|250 partes|
|Límite de profundidad de incrustación de mensajes|30 mensajes incrustados|30 mensajes incrustados|30 mensajes incrustados|30 mensajes incrustados|

> [!NOTE]
> <sup>1</sup> Los administradores de Office 365 pueden especificar un límite personalizado entre 1 y 150 MB. Sin embargo, el tamaño de los mensajes que usted puede enviar o recibir también depende de qué admite el cliente de correo electrónico o la solución. Para obtener más información sobre cómo personalizar el tamaño máximo de mensaje permitido para su organización, consulte [Office 365 now supports larger email messages](https://www.microsoft.com/en-us/microsoft-365/blog/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/) (Office 365 ahora admite mensajes de correo electrónico más grandes). <br/> <sup>2</sup> Pueden enviarse y recibirse mensajes de hasta 150 MB entre los usuarios de Office 365 (los mensajes nunca abandonan los centros de datos de Office 365). Los mensajes que se enrutan fuera de los centros de datos de Office 365 están sujetos a un aumento de codificación de traducción de 33 % adicional, en cuyo caso el tamaño máximo de mensaje es 112 MB. <br/> <sup>3</sup> OWA permite que su mensaje esté sujeto al incremento de codificación del 33 % y limita el tamaño del mensaje que se puede enviar al 25 % menos que el valor configurado. Por ejemplo, si personaliza la configuración de tamaño de mensaje máximo en 100 MB, no se pueden enviar mensajes que superen los 75 MB. <br/> <sup>4</sup> Es el límite predeterminado para organizaciones de Exchange Server 2013. Los administradores pueden cambiar este valor para su organización. <br/> <sup>5</sup> Exchange Online calcula el tamaño de los mensajes que desea mover a Exchange Online. Las versiones de Exchange anteriores a Exchange Server 2013 pueden informar un tamaño de elemento más pequeño. <br/> 
  <sup>6</sup> Para obtener información sobre OME con nuevas funciones, vea [Configurar las nuevas funciones de Cifrado de mensajes de Office 365 basadas en Azure Information Protection](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US).

## <a name="receiving-and-sending-limits"></a>Límites de envío y recepción

Los límites de envío y recepción se aplican para combatir el correo no deseado o el envío masivo por correo de gusanos o virus. Estos límites ayudan a proteger nuestros sistemas y a mantener seguros a nuestros usuarios.

### <a name="receiving-limits"></a>Límites de recepción

Los límites de recepción se aplican al número de mensajes que un usuario, grupo o carpeta pública pueden recibir por hora. Esto se aplica tanto a los mensajes recibidos de Internet como de los servidores locales. Al superar el límite de recepción, los mensajes de correo electrónico enviados al buzón recibirá un informe de no entrega que indica que el buzón ha superado el umbral de entrega máximo. Pasada una hora, se actualizará el límite y el buzón podrá volver a recibir mensajes.

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Office 365 Empresa Essentials**|**Office 365 Empresa Premium Office**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Mensajes recibidos|3 600 mensajes por hora|3 600 mensajes por hora|3 600 mensajes por hora|3 600 mensajes por hora|3 600 mensajes por hora|3600 mensajes por hora|

### <a name="sending-limits"></a>Límites de envío

Los límites de envío se aplican al número de destinatarios, número de mensajes y número de destinatarios por mensaje que puede enviar un usuario desde su cuenta de Exchange Online.

> [!NOTE]
> Para los grupos de distribución almacenados en la libreta de direcciones de una organización, el grupo se contabiliza como un destinatario. Para los grupos de distribución almacenados en la carpeta Contactos de un buzón de correo, los miembros del grupo se contabilizan de forma individual.

- **Límite de frecuencia**de destinatarios: para impedir la entrega de mensajes masivos no solicitados, Exchange Online tiene límites de destinatarios que impiden que los usuarios y las aplicaciones envíen grandes volúmenes de correo electrónico. Estos límites se aplican por usuario a todos los mensajes (salientes e internos).

    > [!NOTE]
    > Los clientes de Exchange Online que deben enviar un correo electrónico comercial masivo válido (por ejemplo, boletines para clientes) deberían usar proveedores de terceros especializados en dichos servicios.

- **Límite**de destinatarios: este es el número máximo de destinatarios permitidos en los campos para:, CC: y CCO: de un solo mensaje de correo electrónico.

    > [!NOTE]
    > Para el límite de frecuencia de destinatarios y el límite de destinatarios, un grupo de distribución almacenado en la libreta de direcciones compartida de la organización se cuenta como un destinatario. En una lista personal de distribución, cada destinatario se cuenta por separado.

- **Límite de velocidad**de mensajes: los límites de velocidad de mensajes determinan cuántos mensajes puede enviar un usuario desde su cuenta de Exchange online en un período de tiempo especificado. Este límite ayuda a prevenir el consumo excesivo de recursos del sistema por un solo remitente. Si un usuario envía mensajes a una velocidad que supera el límite mediante el envío de cliente SMTP, se rechazarán los mensajes y el cliente tendrá que volver a intentarlo.

#### <a name="sending-limits-across-office-365-options"></a>Límites de envío en las opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Office 365 Empresa Essentials**|**Office 365 Empresa Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Límite de frecuencia de destinatario|10 000 destinatarios por día|10 000 destinatarios por día|10 000 destinatarios por día|10 000 destinatarios por día|10 000 destinatarios por día|10 000 destinatarios por día|
|Límite de destinatarios|500 destinatarios|500 destinatarios|500 destinatarios|500 destinatarios|500 destinatarios|500 destinatarios|
|Límite de direcciones proxy de destinatarios|400|400|400|400|400|400|
|Límite de frecuencia de mensajes|30 mensajes por minuto|30 mensajes por minuto|30 mensajes por minuto|30 mensajes por minuto|30 mensajes por minuto|30 mensajes por minuto|

#### <a name="sending-limits-across-standalone-options"></a>Límites de envío en las opciones independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Exchange Server 2013**|**Exchange Online (plan 1)**|**Exchange Online (plan 2)**|**Quiosco de Exchange Online**|
|Límite de frecuencia de destinatario|Sin límite<sup>1</sup>|10 000 destinatarios por día|10 000 destinatarios por día|10 000 destinatarios por día|
|Límite de destinatarios|500 destinatarios<sup>1</sup>|500 destinatarios|500 destinatarios|500 destinatarios|
|Límite de direcciones proxy de destinatarios|400|400|400|400|

> [!NOTE]
> <sup>1</sup> Es el límite predeterminado para organizaciones de Exchange Server 2013. Los administradores pueden cambiar este valor para su organización.

## <a name="reporting-and-message-trace-limits"></a>Límites de seguimiento de mensajes y creación de informes
<a name="bkmk_Reporting_Message_Trace_Limits"> </a>

Para conocer los límites de seguimiento de mensajes y creación de informes, vea la sección sobre disponibilidad y latencia de datos de seguimiento de mensajes y creación de informes en [Informes y seguimiento de mensajes en la Protección en línea de Exchange](http://go.microsoft.com/fwlink/p/?LinkId=394248).

## <a name="retention-limits"></a>Límites de retención
<a name="RetentionLimits"> </a>

Estos límites controlan el tiempo durante el cual es posible obtener acceso a los elementos de determinadas carpetas de la Bandeja de entrada.

- **Período de retención de la carpeta elementos eliminados**: el número máximo de días que los elementos pueden permanecer en la carpeta elementos eliminados antes de que se quiten automáticamente.

- **Período de retención de los elementos quitados de la carpeta elementos eliminados**: el número máximo de días que se conservan los elementos quitados de la carpeta elementos eliminados antes de que se eliminen de forma permanente.

- **Período de retención de la carpeta correo no deseado**: el número máximo de días que los elementos pueden permanecer en la carpeta correo electrónico no deseado antes de que se eliminen automáticamente.

### <a name="retention-limits-across-office-365-options"></a>Límites de retención en las opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Office 365 Empresa Essentials**|**Office 365 Empresa Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Período de retención de la carpeta Elementos eliminados|Sin límite<sup>1</sup>|Sin límite<sup>1</sup>|Sin límite<sup>1</sup>|Sin límite<sup>1</sup>|Sin límite<sup>1</sup>|Sin límite<sup>1</sup>|
|Período de retención de los elementos quitados de la carpeta Elementos eliminados|14 días<sup>1</sup>|14 días<sup>1</sup>|14 días<sup>1</sup>|14 días<sup>1</sup>|14 días<sup>1</sup>|14 días<sup>1</sup>|
|Período de retención de la carpeta Correo no deseado|30 días|30 días|30 días|30 días|30 días|30 días|

> [!NOTE]
> <sup>1</sup> Este es el valor predeterminado para las organizaciones de Office 365. Los administradores pueden cambiar este valor a un máximo de 30 días para los buzones de su organización.

### <a name="retention-limits-across-standalone-options"></a>Límites de retención en las opciones independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Exchange Server 2013**|**Exchange Online (plan 1)**|**Exchange Online (plan 2)**|**Quiosco de Exchange Online**|
|Período de retención de la carpeta Elementos eliminados|Sin límite<sup>1</sup>|Sin límite<sup>1</sup>|Sin límite<sup>1</sup>|Sin límite<sup>1</sup>|
|Período de retención de los elementos quitados de la carpeta Elementos eliminados|14 días<sup>1</sup>|14 días<sup>2</sup>|14 días<sup>2</sup>|14 días<sup>2</sup>|
|Período de retención de la carpeta Correo no deseado|2 años<sup>1</sup>|30 días|30 días|30 días|

> [!NOTE]
> <sup>1</sup> Es el límite predeterminado. Los administradores pueden cambiar este valor para su organización.<br/> <sup>2</sup> Es el valor predeterminado para organizaciones de Exchange Online. Los administradores pueden cambiar este valor a un máximo de 30 días para los buzones de su organización.

## <a name="distribution-group-limits"></a>Límites de grupos de distribución

Estos límites se aplican a grupos de distribución en la libreta de direcciones compartida de su organización.

- **Número máximo de miembros del grupo de distribución**: el número total de destinatarios se determina tras la expansión del grupo de distribución.

- **Limitar el envío de mensajes a grupos de distribución grandes**: los grupos de distribución que contienen el número de miembros especificados por este límite deben tener configuradas opciones de administración de entrega o de aprobación de mensajes. La administración especifica una lista de remitentes con permiso para enviar mensajes al grupo de distribución. La aprobación de mensajes especifica uno o varios moderadores que deben aprobar que todos los mensajes se envíen al grupo de distribución.

- **Tamaño máximo de mensaje para grandes grupos de distribución**: Si un mensaje se envía a 5.000 o más destinatarios, el tamaño del mensaje no puede exceder este límite. Si lo excede, el mensaje no se entrega y el remitente recibe un informe de no entrega (NDR). La contabilización total de destinatarios se determina tras la expansión del grupo de distribución.

### <a name="distribution-group-limits-across-office-365-options"></a>Límites de grupos de distribución en las opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Office 365 Empresa Essentials**|**Office 365 Empresa Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Número máximo de miembros de un grupo de distribución<sup>1</sup>|100 000 miembros|100 000 miembros|100 000 miembros|100 000 miembros|100 000 miembros|100 000 miembros|
|Límite de envío de mensajes a un grupo de distribución grande|5 000 o más miembros|5 000 o más miembros|5 000 o más miembros|5 000 o más miembros|5 000 o más miembros|5 000 o más miembros|
|Tamaño máximo de mensaje para grupos de distribución con entre 5 000 y 99 999 miembros.|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|Tamaño máximo de mensaje para grupos de distribución con 100 000 miembros.|5 MB|5 MB|5 MB|5 MB|5 MB|5 MB|
|Número máximo de propietarios de un grupo de distribución|10 |10 |10 |10 |10 |10 |
|Número máximo de grupos que un usuario puede crear|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> Si usa Azure Active Directory DirSync, el número máximo de miembros del grupo de distribución que se pueden sincronizar de Active Directory local a Azure Active Directory es 15 000. Si usa Azure AD Connect, el número asciende a 50 000. <br/> <sup>2</sup> Este límite se aplica también a los administradores.

### <a name="distribution-group-limits-across-standalone-options"></a>Límites de grupo de distribución en las opciones independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Exchange Server 2013**|**Exchange Online (plan 1)**|**Exchange Online (plan 2)**|**Quiosco de Exchange Online**|
|Número máximo de miembros de un grupo de distribución|100 000 miembros<sup>1</sup>|100 000 miembros|100 000 miembros|100 000 miembros|
|Límite de envío de mensajes a un grupo de distribución grande|5000 o más miembros<sup>1</sup>|5 000 o más miembros|5 000 o más miembros|5 000 o más miembros|
|Número máximo de propietarios de un grupo de distribución|10 |10 |10 |10 |
|Número máximo de grupos que un usuario puede crear|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> Es el límite predeterminado para organizaciones de Exchange Server 2013. Los administradores pueden cambiar este valor para su organización. <br/> <sup>2</sup> Este límite se aplica también a los administradores.

## <a name="journal-transport-and-inbox-rule-limits"></a>Límites de las reglas de la Bandeja de entrada, del diario y de transporte

La lista siguiente incluye los límites que se aplican a las reglas del diario, a las reglas de transporte (también conocidas como reglas de toda la organización) y los límites que se aplican a la Bandeja de entrada. Los distintos usuarios configuran las reglas de la bandeja de entrada que se aplican a los mensajes que se envían y reciben en sus buzones correspondientes.

- **Número máximo de reglas del diario** El número máximo de reglas del diario que puede existir en la organización.

- **Número máximo de reglas de transporte** El número máximo de reglas que puede existir en la organización.

- **Tamaño máximo de una regla de transporte individual** El número máximo de caracteres que se pueden usar en una sola regla de transporte. Los caracteres se emplean en las condiciones, excepciones y acciones.

- **Límite de caracteres para todas las expresiones regulares usadas en todas las reglas de transporte** El número total de caracteres usados por todas las expresiones regulares en todas las condiciones y excepciones de las reglas de transporte de una organización. Puede disponer de unas cuantas reglas que usen expresiones largas y complejas, o muchas reglas con expresiones regulares sencillas.

- **Límites de análisis para el contenido de datos adjuntos** Las condiciones de regla de transporte le permiten examinar el contenido de los datos adjuntos del mensaje, pero se inspecciona solo el primer 1 MB del texto extraído de un archivo adjunto. Este límite de 1 MB se refiere al texto extraído de los datos adjuntos, no al tamaño de archivo de los datos adjuntos. Por ejemplo, un archivo de 2 MB puede tener menos de 1 MB de texto, en cuyo caso todo el texto sería inspeccionado.

- **Número máximo de recipientes agregados a un mensaje por todas las reglas de trasporte** Cuando en un mensaje actúan diferentes reglas de transporte, solo se puede agregar al mensaje un número finito de destinatarios. Una vez alcanzado el límite, los demás destinatarios no se agregan al mensaje. Asimismo, los grupos de distribución no pueden agregarse a un mensaje mediante una regla de transporte.

- **Límite de reenvío** El número máximo de destinatarios que se puede configurar para una regla de transporte o de bandeja de entrada con una acción de redireccionamiento. Si se configura una regla para redireccionar un mensaje a más de este número de destinatarios, la regla no se aplicará y cualquier mensaje que satisfaga la condición de la regla no redirigirá ninguno de los destinatarios enumerados en la regla.
    
- **Número de veces que se redirige un mensaje** El número de veces que se redirigirá, reenviará o responderá automáticamente un mensaje en función de las reglas de la Bandeja de entrada. Por ejemplo, el usuario A tiene una regla de Bandeja de entrada que redirige los mensajes al usuario B, en función del remitente. El usuario B tiene una regla de Bandeja de entrada que reenvía los mensajes al usuario C, en función de palabras clave en la línea del asunto. Si un mensaje cumple estas dos condiciones, el mensaje solo se envía al usuario B; no se reenvía al usuario C ya que solo se permite un redireccionamiento. En este caso, el mensaje se elimina sin enviar un informe de no entrega (NDR) al usuario B que indica que el mensaje no se entregó al usuario C. Usamos el encabezado X-MS-Exchange-Inbox-rules-loop para determinar el número de veces que se redirigió un mensaje. Este encabezado también se mantiene entre los límites de la organización de Exchange.

- **Número de veces que las reglas de transporte redirigen un mensaje** El número de veces que se redirigirá un mensaje en función de las reglas de transporte. Por ejemplo, la organización de Exchange Tailspin Toys tiene una regla de transporte para redirigir todos los mensajes enviados al usuario a al usuario B, que se encuentra en la organización de Exchange contoso. En la organización de Exchange contoso hay una regla de transporte en su ubicación para redirigir todos los mensajes enviados al usuario B al usuario C que se encuentra en la organización de Exchange a. Datum Corporation. En este caso, el mensaje se elimina y un informe de no entrega (NDR) con código de estado y el mensaje de rechazo *550 5.7.128 transporte. Reglas. RejectMessage Se superó el número de bucles de reglas de transporte y el mensaje rechazado* es enviar al usuario a. Usamos el encabezado X-MS-Exchange-Transport-rules-loop para determinar el número de veces que un mensaje fue redirigido por las reglas de transporte. Este encabezado también se mantiene entre los límites de la organización de Exchange.

### <a name="journal-transport-and-inbox-rule-limits-across-office-365-options"></a>Límites de reglas del diario, transporte y Bandeja de entrada en las opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Office 365 Empresa Essentials**|**Office 365 Empresa Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Número máximo de reglas del diario|reglas de 50|reglas de 50|reglas de 50|reglas de 50|reglas de 50|reglas de 50|
|Número máximo de reglas de transporte|300 reglas|300 reglas|300 reglas|300 reglas|300 reglas|300 reglas|
|Tamaño máximo de una regla de transporte individual|8 KB|8 KB|8 KB|8 KB|8 KB|8 KB|
|Límite de caracteres para todas las expresiones regulares usadas en todas las reglas de transporte|20 KB|20 KB|20 KB|20 KB|20 KB|20 KB|
|Límites de análisis para el contenido de datos adjuntos|1 MB|1 MB|1 MB|1 MB|1 MB|1 MB|
|Número máximo de destinatarios agregados a un mensaje por todas las reglas de trasporte|100 destinatarios|100 destinatarios|100 destinatarios|100 destinatarios|100 destinatarios|100 destinatarios|
|Límite de reenvío|10 destinatarios|10 destinatarios|10 destinatarios|10 destinatarios|10 destinatarios|10 destinatarios|
|Número de veces que se redirige un mensaje|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|
|Número de veces que las reglas de transporte redirigen un mensaje|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|

### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>Límites de reglas del diario, transporte y Bandeja de entrada en las opciones independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Exchange Server 2013**|**Exchange Online (plan 1)**|**Exchange Online (plan 2)**|**Quiosco de Exchange Online**|
|Número máximo de reglas del diario|Sin límite|reglas de 50|reglas de 50|reglas de 50|
|Número máximo de reglas de transporte|Sin límite|300 reglas|300 reglas|300 reglas|
|Tamaño máximo de una regla de transporte individual|40 KB|8 KB|8 KB|8 KB|
|Límite de caracteres para todas las expresiones regulares usadas en todas las reglas de transporte|Sin límite|20 KB|20 KB|20 KB|
|Número máximo de destinatarios agregados a un mensaje por todas las reglas de trasporte|Sin límite|100 destinatarios|100 destinatarios|100 destinatarios|
|Límite de reenvío|Sin límite|10 destinatarios|10 destinatarios|10 destinatarios|
|Número de veces que se redirige un mensaje|3 redireccionamientos|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|
|Número de veces que las reglas de transporte redirigen un mensaje|Sin límite|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|

## <a name="moderation-limits"></a>Límites de moderación
<a name="ModerationLimits"> </a>

Estos límites controlan la configuración de la moderación empleada para la aprobación de mensajes que se aplica a los grupos de distribución y las reglas de transporte.

- **Tamaño máximo del buzón de correo de arbitraje**: Si el buzón de correo de arbitraje supera este límite, los mensajes que requieren moderación se devolverán al remitente en un informe de no entrega (NDR).

- **Número máximo de moderadores**: el número máximo de moderadores que puede asignar a un solo grupo de distribución moderado o que pueden agregarse a un mensaje con una sola regla de transporte. Tenga en cuenta que no puede especificar un grupo de distribución como moderador.

- **Expiración de mensajes en espera de moderación**: de forma predeterminada, un mensaje en espera de moderación expira después de dos días. No obstante, el procesamiento de mensajes moderados expirados se ejercita cada siete días. Esto significa que un mensaje moderado puede expirar en cualquier momento entre dos y nueve días.

- **Tasa máxima de mensajes de notificación de moderación caducada**: este límite establece el número máximo de mensajes de notificación para los mensajes moderados expirados en un período de una hora. Este límite se coloca en cada base de datos de buzones de correo del centro de datos.

Durante períodos de gran actividad, algunos remitentes no recibirán mensajes de notificación de mensajes moderados que hayan expirado. Sin embargo, estas notificaciones aún se pueden detectar usando informes de entrega.

### <a name="moderation-limits-across-office-365-options"></a>Límites de moderación en las opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Office 365 Empresa Essentials**|**Office 365 Empresa Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Tamaño máximo de buzón de correo de arbitraje|10 GB|10 GB|10 GB|10 GB|10 GB|10 GB|
|Número máximo de moderadores|10 moderadores|10 moderadores|10 moderadores|10 moderadores|10 moderadores|10 moderadores|
|Caducidad de mensajes en espera de ser moderados|2 días|2 días|2 días|2 días|2 días|2 días|
|Máximo índice de mensajes de notificación de moderación caducada|300 notificaciones de caducidad por hora|300 notificaciones de caducidad por hora|300 notificaciones de caducidad por hora|300 notificaciones de caducidad por hora|300 notificaciones de caducidad por hora|300 notificaciones de caducidad por hora|

### <a name="moderation-limits-across-standalone-options"></a>Límites de moderación en las opciones independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Exchange Server 2013**|**Exchange Online (plan 1)**|**Exchange Online (plan 2)**|**Quiosco de Exchange Online**|
|Tamaño máximo de buzón de correo de arbitraje|Sin límite<sup>1</sup>|10 GB|10 GB|10 GB|
|Número máximo de moderadores|Sin límite|10 moderadores|10 moderadores|10 moderadores|
|Caducidad de mensajes en espera de ser moderados|5 días<sup>1</sup>|2 días|2 días|2 días|
|Máximo índice de mensajes de notificación de moderación caducada|300 notificaciones de caducidad por hora|300 notificaciones de caducidad por hora|300 notificaciones de caducidad por hora|300 notificaciones de caducidad por hora|

> [!NOTE]
> <sup>1</sup> Es el límite predeterminado para organizaciones de Exchange Server 2013. Los administradores pueden cambiar este valor para su organización.

## <a name="exchange-activesync-limits"></a>Límites de Exchange ActiveSync
<a name="BKMK_ExchangeActiveSync_Limits"> </a>

Los siguientes límites se aplican a Microsoft Exchange ActiveSync, un protocolo de cliente que sincroniza los datos de los buzones entre los dispositivos móviles y Exchange.

- **Límite de dispositivos de Exchange ActiveSync**: el número máximo de dispositivos de Exchange ActiveSync por buzón de correo.

- **Límite de eliminación de dispositivos de Exchange ActiveSync**: el número máximo de dispositivos de Exchange ActiveSync que un administrador de Exchange puede eliminar en un mes.

- **Límite de datos adjuntos de archivo de Exchange ActiveSync**: el tamaño máximo de los datos adjuntos de un archivo de mensaje que puede enviar o recibir un dispositivo de Exchange ActiveSync.

### <a name="exchange-activesync-limits-across-office-365-options"></a>Límites de Exchange ActiveSync en las opciones de Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Office 365 Empresa Essentials**|**Office 365 Empresa Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Límite de dispositivos de Exchange ActiveSync|100|100|100|100|100|100|
|Límite de eliminación de dispositivos de Exchange ActiveSync|20|20|20|20|20|20|
|Límite de datos adjuntos del archivo de Exchange ActiveSync|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|

### <a name="exchange-activesync-limits-across-standalone-options"></a>Límites de Exchange ActiveSync en opciones independientes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica**|**Exchange Server 2013**|**Exchange Online (plan 1)**|**Exchange Online (plan 2)**|**Quiosco de Exchange Online**|
|Límite de dispositivos de Exchange ActiveSync|100|100|100|100|
|Límite de eliminación de dispositivos de Exchange ActiveSync|20|20|20|20|
|Límite de datos adjuntos del archivo de Exchange ActiveSync|25 MB|25 MB|25 MB|25 MB|
