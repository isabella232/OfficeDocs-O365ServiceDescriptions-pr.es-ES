---
title: Límites de Exchange Online
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-limits
ms.service: o365-administration
localization_priority: Priority
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 70b38a05-6cfa-4ced-a137-116019262fed
description: Encuentre los límites de Exchange Online para las distintas áreas de servicio, entre los que se incluyen los límites de la libreta de direcciones, los de almacenamiento de los buzones y los de seguimiento de informes y mensajes.
ms.openlocfilehash: fbcbca12cd08727bb9093cc06c32dace24495c43
ms.sourcegitcommit: fc58d29a2429d04d3a1f8d51dbf6c2b063bc66a9
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 07/12/2021
ms.locfileid: "53383703"
---
# <a name="exchange-online-limits"></a>Límites de Exchange Online

Encuentre los límites de Exchange Online para las distintas áreas de servicio, entre los que se incluyen los límites de la libreta de direcciones, los de almacenamiento de los buzones y los de seguimiento de informes y mensajes.

> [!NOTE]
> Si necesita ayuda con una tarea o si está solucionando un problema, es posible que los artículos siguientes le resulten útiles:
> - [Correo electrónico](https://support.office.com/article/94275804-7147-4332-9ccd-5d421760a9ed) (para obtener ayuda para crear y enviar correo electrónico)
>- [Correo electrónico en Microsoft 365 para empresas: ayuda para administradores](/microsoft-365/admin/email/)
>- [Solucionar problemas de Outlook y Microsoft 365 con el Asistente para soporte y recuperación de Microsoft](https://diagnostics.office.com/)
>- [Informes de no entrega de correo electrónico en Exchange Online](/Exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/non-delivery-reports-in-exchange-online)
>- [Ayuda de Exchange Online](/exchange/exchange-online)

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
> - Los límites aplicados a una organización de Microsoft 365 pueden ser diferentes según el tiempo que la organización haya estado inscrita en el servicio. 
> - Cuando se cambia un límite en los centros de datos de Microsoft, la aplicación de los cambios en todos los clientes existentes puede tardar cierto tiempo.
> - No puede modificar la mayoría de estos límites, pero usted y sus usuarios deben conocerlos.
> - Estos límites se aplican tanto a los destinatarios internos como a los externos.
> - De manera predeterminada, Exchange Online Protection (EOP) protege los buzones de Exchange Online. Para los límites que se aplican a las características de EOP en Exchange Online, vea [Límites de Exchange Online Protection](../exchange-online-protection-service-description/exchange-online-protection-limits.md).
> - Para obtener información acerca de límites de grupos de Office 365, vea "¿Cómo administrar mis grupos?" en [Obtener más información sobre los grupos de Microsoft 365](https://go.microsoft.com/fwlink/?linkid=846714)

## <a name="address-book-limits"></a>Límites de la libreta de direcciones

- **Límite de listas de direcciones**: El número máximo de listas de direcciones que se pueden crear en una organización de Exchange Online o Exchange Server 2013. Este número incluye las listas de direcciones predeterminadas en Exchange Online, como todos los contactos y todos los grupos.

    > [!NOTE]
    > Puede asignarse un máximo de 20 listas de direcciones a cada libreta de direcciones sin conexión (OAB).

- **Límite de libretas de direcciones sin conexión** El número máximo de libretas de direcciones sin conexión (OAB) que se pueden crear en una organización de Exchange Online o Exchange Server 2013.

- **Límite de directivas de libreta de direcciones** El número máximo de directivas de libreta de direcciones (ABP) que se pueden crear en una organización de Exchange Online o Exchange Server 2013.

- **Listas globales de direcciones** El número máximo de listas globales de direcciones (GAL) que se pueden crear en una organización de Exchange Online o Exchange Server 2013.

### <a name="address-book-limits"></a>Límites de la libreta de direcciones

| Característica | Microsoft 365 Empresa Básico | Microsoft 365 Empresa Estándar | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Límite de listas de direcciones|1000|1000|1000|1000|1000|1000|
|Límite de libretas de direcciones sin conexión (OAB)|250|250|250|250|250|250|
|Límite de directivas de libreta de direcciones (ABP)|250|250|250|250|250|250|
|Límite de listas globales de direcciones|250|250|250|250|250|250|

### <a name="address-book-limits-across-standalone-plans"></a>Límites de la libreta de direcciones a través de planes independientes

| Característica | Exchange Server 2013 | Plan 1 de Exchange Online | Plan 2 de Exchange Online | Quiosco de Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Límite de listas de direcciones|1000|1000|1000|1000|
|Límite de libretas de direcciones sin conexión (OAB)|250|250|250|250|
|Límite de directivas de libreta de direcciones (ABP)|250|250|250|250|
|Límite de listas globales de direcciones|250|250|250|250|

## <a name="mailbox-storage-limits"></a>Límites de almacenamiento de los buzones

El espacio de almacenamiento del buzón disponible para un usuario está determinado por el tipo de buzón y la licencia de suscripción del usuario. Los administradores pueden reducir el tamaño máximo del buzón de correo por usuario o de forma global.

> [!NOTE]
> Con el registro en diario, el uso de reglas de transporte o reglas de transferencia automática para copiar mensajes en un buzón de Exchange Online con fines de archivado no está permitido. El buzón de archivo de un usuario está diseñado exclusivamente para dicho usuario. Microsoft se reserva el derecho de denegar el archivado ilimitado si el buzón de archivo de un usuario se usa para almacenar datos de archivo de otros usuarios o en otros casos de uso inadecuado.

### <a name="storage-limits"></a>Límites de almacenamiento

| Característica | Microsoft 365 Empresa Básico | Microsoft 365 Empresa Estándar | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Buzones de usuario|50 GB|50 GB|50 GB|100 GB|100 GB|2 GB|
|Buzones de archivo<sup>7, 8</sup>|50 GB|50 GB|50 GB|Ilimitado<sup>1</sup>|Unlimited<sup>1</sup>|No disponible<sup>4</sup>|
|<sup>10</sup>Buzones compartidos|50 GB<sup>2</sup>|50 GB<sup>2</sup>|50 GB<sup>2</sup>|50/100 GB<sup>2,9</sup>|50/100 GB<sup>2,9</sup>|50 GB<sup>2</sup>|
|Buzones de recursos|50 GB<sup>3</sup>|50 GB<sup>3</sup>|50 GB<sup>3</sup>|50 GB<sup>3,9</sup>|50 GB<sup>3,9</sup>|50 GB<sup>3</sup>|
|Buzones de sitio<sup>5</sup>|50 GB|50 GB|50 GB|50 GB|50 GB|No disponible|
|Buzones de carpetas públicas|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|
|Buzones de grupo|50 GB|50 GB|50 GB|50 GB|50 GB|50 GB|

> [!NOTE]
> <sup>1</sup> Cada usuario recibe inicialmente 100 GB de almacenamiento en el buzón de archivo. Cuando el archivado de expansión automática está activado, se agrega almacenamiento adicional automáticamente cuando se alcanza la capacidad de almacenamiento de 100 GB. Para obtener más información, vea [Información general sobre el archivado ilimitado en Office 365](/microsoft-365/compliance/unlimited-archiving). <br/> <sup>2</sup> Para acceder a un buzón de correo compartido, un usuario debe tener una licencia de Exchange Online, pero el buzón de correo compartido no requiere una licencia separada. Sin una licencia, los buzones compartidos están limitados a 50 GB. Para aumentar el límite de tamaño a 100 GB, el buzón compartido debe tener asignada una licencia de Exchange Online Plan 2. Si se asigna una licencia del plan 1 de Exchange Online con una licencia de complemento de Archivado de Exchange Online, esto le permitirá habilitar el archivado de expansión automático para una capacidad ilimitada de almacenamiento de archivos. Del mismo modo, si desea colocar un buzón compartido en retención por litigio, el buzón compartido debe tener una licencia de Exchange Online Plan 2 o una licencia de Exchange Online Plan 1 con una licencia complementaria de Exchange Online Archiving. Si desea aplicar funciones avanzadas como Microsoft Defender para Office 365, eDiscovery avanzado o directivas de retención automática, el buzón de correo compartido debe tener licencia para esas funciones. <br/> <sup>3</sup> Los buzones de recursos no requieren licencia. Sin embargo, sin una licencia, estos buzones están limitados a 50 GB. Para aumentar el tamaño del buzón, debe tener asignada una licencia E3 o E5. Esto aumentará el buzón en 100 GB. <br/> <sup>4</sup> Los buzones de archivo no están incluidos en Quiosco de Exchange Online. Sin embargo, se pueden adquirir como un complemento a través de Archivado de Exchange Online. Para obtener más información, vea [Descripción del servicio de Archivado de Exchange Online](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md). <br/> <sup>5</sup> Los buzones de correo de sitio fueron retirados de Exchange Online y SharePoint Online en 2017. <br/> <sup>6</sup> Tiene un límite de 1000 buzones de correo de carpetas públicas y el tamaño total máximo de todos los buzones de correo de carpetas públicas es de 100 TB. Los buzones que sirven a la jerarquía se limitan a 100 buzones de carpetas públicas. <br/> <sup>7</sup> Solo puede usarse los buzones de archivo para archivar correo de una sola entidad o un único usuario (como un buzón compartido) al que se le haya aplicado una licencia. No se permite usar los buzones de archivo para almacenar correo de varios usuarios o entidades. Por ejemplo, un administrador de TI no puede crear un buzón compartido ni permitir que los usuarios lo copien (con los campos CC o CCO, o mediante una regla de transporte) con el fin de archivarlo. Tenga en cuenta que un buzón compartido que usan varias personas en realidad no almacena correo electrónico de esos usuarios individuales. Varios usuarios tienen acceso y envían correos electrónicos como el buzón compartido. Por lo tanto, los únicos correos electrónicos que se almacenan en el buzón compartido son aquellos enviados a o desde él, *como* el buzón compartido. <br/> <sup>8</sup> Si ha creado una directiva de retención en Exchange Online, los mensajes se moverán automáticamente al buzón de archivos de un usuario solo si el tamaño del buzón principal del usuario supera los 10 MB. La directiva de retención no se ejecutará automáticamente para los buzones cuyo tamaño sea inferior a 10 MB. <br/> <sup>9</sup> Los buzones de recursos o compartidos no requieren licencia. Sin embargo, sin una licencia, estos buzones están limitados a 50 GB. Para aumentar el tamaño del buzón, debe tener asignada una licencia E3 o E5. Esto aumentará el buzón en 100 GB. <br/> <sup>10</sup> De forma predeterminada, los buzones de correo compartidos tienen una cuenta de usuario activa asociada con una contraseña generada por el sistema (desconocida). Para bloquear el inicio de sesión para la cuenta de buzón de correo compartida asociada, consulte [Bloquear el inicio de sesión para la cuenta de buzón de correo compartido](/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account)

### <a name="storage-limits-across-standalone-plans"></a>Límites de almacenamiento en planes independientes

| Característica | Exchange Server 2013 | Plan 1 de Exchange Online | Plan 2 de Exchange Online | Quiosco de Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Buzones de usuario|2 GB<sup>1</sup>|50 GB|100 GB|2 GB|
|Buzones de archivo<sup>8, 9</sup>|100 GB<sup>1</sup>|50 GB|Ilimitado<sup>2</sup>|No disponible<sup>5</sup>|
|Buzones compartidos <sup>11</sup>|2 GB<sup>1</sup>|50 GB<sup>3</sup>|50 GB<sup>3,10</sup>|50 GB<sup>3</sup>|
|Buzones de recursos|2 GB<sup>1</sup>|50 GB<sup>4</sup>|50 GB<sup>4,10</sup>|50 GB<sup>4</sup>|
|Buzones de carpetas públicas|2 GB<sup>6</sup>|50 GB<sup>7</sup>|100 GB<sup>7</sup>|No disponible|
|Buzones de grupo|50 GB|50 GB|50 GB|50 GB|

> [!NOTE]
> <sup>1</sup> Es el tamaño de buzón predeterminado para organizaciones de Exchange Server 2013. Los administradores pueden cambiar este valor para su organización. No hay un límite máximo de almacenamiento para los buzones locales. <br/> <sup>2</sup> Cada usuario recibe inicialmente 100 GB de almacenamiento en el buzón de archivo. Cuando el archivado de expansión automática está activado, se agrega almacenamiento adicional automáticamente cuando se alcanza la capacidad de almacenamiento de 100 GB. Para obtener más información, vea [Información general sobre el archivado ilimitado en Office 365](/microsoft-365/compliance/unlimited-archiving). Vea el [Mapa de ruta de Microsoft 365](https://go.microsoft.com/fwlink/?LinkId=509914) para obtener más información acerca de la disponibilidad del archivado de expansión automática. <br/> <sup>3</sup> Para acceder a un buzón de correo compartido, un usuario debe tener una licencia de Exchange Online, pero el buzón de correo compartido no requiere una licencia independiente. Sin una licencia, los buzones compartidos están limitados a 50 GB. Para aumentar el límite de tamaño a 100 GB, el buzón compartido debe tener asignada una licencia de Exchange Online Plan 2 o una licencia de Exchange Online Plan 1 con una licencia complementaria de Archivad de Exchange Online. Esto también le permitirá habilitar el archivo de expansión automática para una cantidad ilimitada de capacidad de almacenamiento de archivos. Del mismo modo, si desea colocar un buzón compartido en retención por litigio, el buzón compartido debe tener una licencia de Exchange Online Plan 2 o una licencia de Exchange Online Plan 1 con una licencia complementaria de Exchange Online Archiving. Si desea aplicar funciones avanzadas como Microsoft Defender para Office 365, eDiscovery avanzado o directivas de retención automática, el buzón de correo compartido debe tener licencia para esas funciones. <br/> <sup>4</sup> Los buzones de recursos no requieren licencia. Sin embargo, sin una licencia, los buzones de recursos están limitados a 50 GB. Para aumentar el tamaño del buzón, debe tener asignada una licencia del Plan 2 de Exchange Online. Esto aumentará el buzón en 100 GB. <br/> <sup>5</sup> Los buzones de archivo no están incluidos en Quiosco de Exchange Online. Sin embargo, se pueden adquirir como un complemento a través de Archivado de Exchange Online. Para obtener más información, vea [Descripción del servicio de Archivado de Exchange Online](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md). <br/> <sup>6</sup> Es el tamaño de buzón predeterminado para organizaciones de Microsoft Exchange Server 2013. Los administradores pueden cambiar este valor para su organización. En Exchange Server 2013, existe un límite de 100 buzones de carpetas públicas y un tamaño total máximo de 50 TB para todos los buzones de carpetas públicas. <br/> <sup>7</sup> En Exchange Online, existe un límite de 1 000 buzones de carpetas públicas y un tamaño total máximo de 50 TB para todos los buzones de carpetas públicas.  <br/> <sup>8</sup> Los buzones de archivo solo pueden usarse para archivar correo de una sola entidad o un único usuario al que se le haya aplicado una licencia. No se permite usar los buzones de archivo para almacenar correo de varios usuarios o entidades. Por ejemplo, los administradores de TI no pueden crear buzones compartidos ni permitir que los usuarios copien (con los campos CC o CCO, o mediante una regla de transporte) buzones compartidos para archivarlos. <br/> <sup>9</sup> Si ha creado una directiva de retención en Exchange Online, los mensajes se moverán automáticamente al buzón de archivos de un usuario solo si el tamaño del buzón principal del usuario supera los 10 MB. La directiva de retención no se ejecutará automáticamente para los buzones cuyo tamaño sea inferior a 10 MB. <br/> <sup>10</sup> Los buzones de recursos o compartidos no requieren licencia. Sin embargo, sin una licencia, estos buzones están limitados a 50 GB. Para aumentar el tamaño del buzón, debe tener asignada una licencia del Plan 2 de Exchange Online. Esto aumentará el buzón en 100 GB. <br/> <sup>11</sup> De forma predeterminada, los buzones de correo compartidos tienen una cuenta de usuario activa asociada con una contraseña generada por el sistema (desconocida). Para bloquear el inicio de sesión para la cuenta de buzón de correo compartida asociada, consulte [Bloquear el inicio de sesión para la cuenta de buzón de correo compartido](/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account)

## <a name="capacity-alerts"></a>Alertas de capacidad

Exchange Online ofrece tres tipos de notificaciones cuando el buzón de un usuario se acerca o alcanza su máxima capacidad:

- **Advertencia**: El usuario recibe un correo electrónico en el que se le advierte de que el buzón de correo se acerca a su límite de capacidad máxima. Esta advertencia está diseñada para animar a los usuarios a eliminar el correo no deseado.

- **Prohibir envío** El usuario recibe una notificación de prohibir el envío cuando se alcanza el límite de capacidad máxima del buzón de correo. El usuario no puede enviar mensajes nuevos hasta que se elimine suficiente correo electrónico para que el buzón de correo esté por debajo del límite de tamaño.

- **Prohibir envío y recepción**: Exchange Online rechaza todo el correo entrante cuando se alcanza el límite de tamaño del buzón de correo y envía un informe de no entrega (NDR) al remitente. El remitente tiene la opción de intentar reenviar el correo más tarde. Para volver a recibir mensajes, el usuario debe eliminar el correo electrónico hasta que esté por debajo del límite de tamaño.

### <a name="capacity-alerts"></a>Alertas de capacidad

| Característica | Microsoft 365 Empresa Básico | Microsoft 365 Empresa Estándar | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Advertencia|49 GB|49 GB|49 GB|98 GB|98 GB|1,96 GB|
|Prohibir envío|49,5 GB|49,5 GB|49,5 GB|99 GB|99 GB|1,98 GB|
|Prohibir envío y recepción|50 GB|50 GB|50 GB|100 GB|100 GB|2 GB|

### <a name="capacity-alerts-across-standalone-plans"></a>Alertas de capacidad en planes independientes

| Característica | Exchange Server 2013 | Plan 1 de Exchange Online | Plan 2 de Exchange Online | Quiosco de Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Advertencia|1,9 GB<sup>1</sup>|49 GB|98 GB|1,96 GB|
|Prohibir envío|2 GB<sup>1</sup>|49,5 GB|99 GB|1,98 GB|
|Prohibir envío y recepción|2,3 GB<sup>1</sup>|50 GB|100 GB|2 GB|

> [!NOTE]
> <sup>1</sup> Este es el valor predeterminado para organizaciones de Exchange Server 2013. Los administradores pueden cambiar este valor para su organización.

## <a name="mailbox-folder-limits"></a>Límites de la carpeta de buzón de correo

Estos límites se usan para limitar el tamaño de los buzones de correo y garantizar la compatibilidad en Exchange Online. El objetivo de estos límites es evitar que exista un número ilimitado de elementos de buzón de correo por carpeta, un número ilimitado de carpetas por buzón de correo o un número ilimitado de carpetas públicas por organización de Exchange Online. Por cuestiones prácticas, los límites de carpetas de buzón de correo se aplican de forma permanente para garantizar la compatibilidad de la mayoría de los buzones de Exchange Online y locales que se migran a Exchange Online.

- **Número máximo de mensajes por carpeta de buzón de correo**: Especifica el número máximo de mensajes que puede contener una carpeta de buzón de correo. Los nuevos mensajes no se entregarán ni se guardarán en una carpeta cuando se alcance este límite.

- **Advertencia de número de mensajes por carpeta de buzón de correo**: Especifica el número de mensajes que una carpeta de buzón de correo puede almacenar antes de Exchange Online envíe un mensaje de advertencia al propietario del buzón de correo. Cuando se alcanza esta cuota, se envían mensajes de advertencia una vez al día.

- **Número máximo de mensajes por carpeta de la carpeta Elementos recuperables**: Especifica el número máximo de mensajes que puede almacenarse en cada una de las carpetas de la carpeta Elementos recuperables. Cuando una carpeta supera este límite, ya no puede almacenar mensajes nuevos. Por ejemplo, si la carpeta Eliminaciones de la carpeta Elementos recuperables superó el límite de número de mensajes y el propietario del buzón intenta eliminar elementos de su buzón de forma permanente, no se podrá realizar la eliminación.

- **Advertencia de número de mensajes por carpeta en la carpeta Elementos recuperables** Especifica el número de mensajes que puede contener cada carpeta de la carpeta Elementos recuperables antes de que Exchange Online registre un evento en el registro de eventos de la aplicación.

- **Número máximo de subcarpetas por carpeta de buzón de correo**: Especifica el número máximo de subcarpetas que se pueden crear en una carpeta de buzón de correo. El propietario del buzón no podrá crear una subcarpeta nueva una vez alcanzado este límite.

- **Advertencia de número de subcarpetas por carpeta de buzón de correo**: Especifica el número de subcarpetas que se pueden crear en una carpeta de buzón de correo antes de que Exchange Online envíe un mensaje de advertencia al propietario del buzón de correo. Cuando se alcanza esta cuota, se envían mensajes de advertencia una vez al día.

- **Profundidad máxima de jerarquía de carpeta**: Especifica el número máximo de niveles en la jerarquía de carpetas de una carpeta de buzón. El propietario del buzón no podrá crear otro nivel en la jerarquía de carpetas de la carpeta de buzón una vez alcanzado este límite.

- **Advertencia de profundidad de jerarquía de carpeta**: Especifica el número de niveles que se pueden crear en la jerarquía de carpeta de un buzón de correo antes de que Exchange Online envíe un mensaje de advertencia al propietario del buzón de correo. Cuando se alcanza esta cuota, se envían mensajes de advertencia una vez al día.

- **Número máximo de carpetas públicas**: Especifica el número máximo de carpetas públicas para toda la jerarquía de carpetas públicas. Cuando se alcanza este límite, deben eliminarse las carpetas públicas existentes para poder crear otras nuevas.

- **Número máximo de subcarpetas por carpeta pública**: Especifica el número máximo de subcarpetas que se pueden crear en una carpeta pública. Cuando se alcanza este límite, no se pueden crear subcarpetas nuevas en la carpeta pública.

- **Advertencia de número de subcarpetas por carpeta pública**: Especifica el número de subcarpetas que se pueden crear en una carpeta pública antes de que Exchange Online envíe un mensaje de advertencia al propietario de la carpeta. Si no hay ningún propietario, se enviarán mensajes de advertencia a los usuarios con permisos de propietario. Cuando se alcanza esta cuota, se envían mensajes de advertencia una vez al día.

### <a name="mailbox-folder-limits"></a>Límites de la carpeta de buzón de correo

| Característica | Microsoft 365 Empresa Básico | Microsoft 365 Empresa Estándar | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Número máximo de mensajes por carpeta de buzón de correo|1 millón|1 millón|1 millón|1 millón|1 millón|1 millón|
|Advertencia de número de mensajes por carpeta de buzón de correo|900,000|900,000|900,000|900,000|900,000|900,000|
|Número máximo de mensajes por carpeta de la carpeta Elementos recuperables|3 millones|3 millones|3 millones|3 millones|3 millones|3 millones|
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón principal (no en espera)|30 GB|30 GB|30 GB|30 GB|30 GB|30 GB|
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón principal (en espera)|100 GB|100 GB|100 GB|100 GB|100 GB|100 GB|
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón de archivo (no en espera)|30 GB|30 GB|30 GB|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|30 GB|
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón de archivo (en espera)|100 GB<sup>1</sup>|100 GB<sup>1</sup>|100 GB<sup>1</sup>|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|100 GB<sup>1</sup>|
|Advertencia de número de mensajes por carpeta en la carpeta Elementos recuperables|2,75 millones|2,75 millones|2,75 millones|2,75 millones|2,75 millones|2,75 millones|
|Número máximo de subcarpetas por carpeta de buzón de correo|10 000<sup>2</sup>|10 000<sup>2</sup>|10 000<sup>2</sup>|10 000<sup>2</sup>|10 000<sup>2</sup>|10 000<sup>2</sup>|
|Advertencia de número de subcarpetas por carpeta de buzón de correo|9000|9000|9000|9000|9000|9000|
|Profundidad máxima de jerarquía de carpeta|300|300|300|300|300|300|
|Advertencia de profundidad de jerarquía de carpeta|250|250|250|250|250|250|
|Número máximo de carpetas públicas|500 000|500 000|500 000|500 000|500 000|No disponible|
|Número máximo de subcarpetas por carpeta pública|10,000|10,000|10,000|10,000|10,000|No disponible|
|Advertencia de número de subcarpetas por carpeta pública|9000|9000|9000|9000|9000|No disponible|

> [!NOTE]
> <sup>1</sup> Es la cuota de almacenamiento de la carpeta Elementos recuperables, y no la cuota de todo el buzón de archivo. La cuota de almacenamiento del buzón de archivo es ilimitada para los usuarios que cuentan con una licencia de Exchange Online Plan 2 o para los usuarios que tienen una licencia de Plan 1 de Exchange Online y de Archivado de Exchange Online. Para obtener más información sobre la cuota de elementos recuperables, vea [Aumentar la cuota de elementos recuperables para los buzones de correo en retención](/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold). <br/> <sup>2</sup> La cuota de almacenamiento inicial para la carpeta Elementos recuperables de un buzón de archivo es de 100 GB. Cuando el archivado de expansión automática está activado, se agrega almacenamiento adicional automáticamente cuando se alcanza la capacidad de almacenamiento de la carpeta Elementos recuperables. Para obtener más información, vea [Información general sobre el archivado ilimitado en Office 365](/microsoft-365/compliance/unlimited-archiving). Vea el [Plan de desarrollo de Microsoft 365](https://go.microsoft.com/fwlink/?LinkId=509914) para obtener información sobre la disponibilidad del archivado de expansión automática.
> <sup>2</sup> Este es un límite de tienda; es una de las limitaciones de la forma del buzón. Solo puede haber 10,000 carpetas secundarias directas para un padre determinado. Esto se aplica independientemente de la migración u otros clientes que creen carpetas.

### <a name="mailbox-folder-limits-across-standalone-plans"></a>Límites de carpetas de buzones de correo de los distintos planes independientes

| Característica | Exchange Server 2013 | Plan 1 de Exchange Online | Plan 2 de Exchange Online | Quiosco de Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Número máximo de mensajes por carpeta de buzón de correo|Sin límite<sup>1</sup>|1 millón|1 millón|1 millón|
|Advertencia de número de mensajes por carpeta de buzón de correo|Sin límite|900,000|900,000|900,000|
|Número máximo de mensajes por carpeta de la carpeta Elementos recuperables|Sin límite|3 millones|3 millones|3 millones|
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón principal (no en espera)|30 GB|30 GB|30 GB|30 GB|
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón principal (en espera)|100 GB|100 GB|100 GB|100 GB|
|Cuota de almacenamiento para la carpeta Elementos recuperables del buzón de archivo (no en espera)|30 GB|30 GB|30 GB|30 GB|
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
> <sup>1</sup> Microsoft recomienda no más de 1 000 000 de mensajes por carpeta del buzón. > <br/> <sup>2</sup> Es la cuota de almacenamiento de la carpeta Elementos recuperables, y no la cuota de todo el buzón de archivo. La cuota de almacenamiento del buzón de archivo es ilimitada para los usuarios que cuentan con una licencia de Exchange Online Plan 2 o para los usuarios que tienen una licencia de Plan 1 de Exchange Online y de Archivado de Exchange Online. Para obtener más información sobre la cuota de elementos recuperables, vea [Aumentar la cuota de elementos recuperables para los buzones de correo en retención](/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold). <br/> <sup>3</sup> La cuota de almacenamiento inicial para la carpeta Elementos recuperables de un buzón de archivo es de 100 GB. Cuando el archivado de expansión automática está activado, se agrega almacenamiento adicional automáticamente cuando se alcanza la capacidad de almacenamiento de la carpeta Elementos recuperables. Para obtener más información, vea [Información general sobre el archivado ilimitado en Office 365](/microsoft-365/compliance/unlimited-archiving). Vea el [Plan de desarrollo de Microsoft 365](https://go.microsoft.com/fwlink/?LinkId=509914) para obtener información sobre la disponibilidad del archivado de expansión automática.

## <a name="message-limits"></a>Límites de mensajes

Los siguientes límites se aplican a todos los mensajes de correo electrónico.

- **Límite del tamaño del mensaje** Los límites de tamaño de los mensajes son necesarios para evitar que los mensajes grandes bloqueen la entrega de otros mensajes y afecten el rendimiento del servicio para todos los usuarios. Estos límites incluyen documentos adjuntos y se aplican a todos los mensajes de la organización (entrantes, salientes e internos). Los mensajes más grandes que este límite no se entregarán y el remitente recibirá un informe de no entrega (NDR). Aunque los límites de tamaño de los mensajes se pueden configurar hacia arriba, abajo o por usuario, los administradores además pueden crear reglas de transporte para limitar el tamaño máximo de un adjunto concreto. Para obtener más información, consulte [Microsoft admite mensajes de correo electrónico más grandes](https://go.microsoft.com/fwlink/?linkid=2144144).

    > [!NOTE]
    > Algunos clientes de correo electrónico pueden tener límites de tamaño de mensaje más bajos o pueden limitar el tamaño de un archivo adjunto individual a un valor menor que el límite de tamaño de mensaje de Exchange Online.

- **Límite de tamaño de encabezados de mensaje** especifica el tamaño máximo de todos los campos de encabezado de mensaje en un mensaje. El límite actual es 256 KB. Si el tamaño total de todos los encabezados de mensajes supera los 256 KB, Exchange Online rechazará el mensaje con el error "552 5.3.4 El tamaño del encabezado excede el tamaño máximo establecido." No se tiene en cuenta el tamaño del cuerpo del mensaje ni de los datos adjuntos. Como los campos del encabezado son texto sin formato, el tamaño del encabezado lo determinan el número de caracteres de cada campo y el número total de campos del encabezado. Cada carácter de texto consume 1 byte.

- **Límite de longitud del asunto**: La cantidad máxima de caracteres de texto permitidos en la línea de asunto de un mensaje de correo electrónico.

- **Límite de datos adjuntos del archivo**: El número máximo de datos adjuntos permitidos en un mensaje de correo electrónico. Aunque el tamaño total de todos los datos adjuntos no infrinja el límite de tamaño del mensaje, sigue habiendo un límite en cuanto al número de datos adjuntos permitidos en el mensaje. Este límite está controlado por el límite de mensaje con varias partes.

- **Límite del tamaño de un archivo de datos adjunto**: El tamaño máximo de archivo de un solo dato adjunto.

    > [!NOTE]
    > Este es el tamaño de archivo máximo de un solo archivo adjunto. Los programas de clientes individuales, incluido Outlook en la Web, pueden limitar el tamaño de los archivos adjuntos por debajo de este valor máximo. Exchange ActiveSync no implementa límites de tamaño de archivo adjunto en archivos adjuntos individuales. El tamaño total de todos los archivos adjuntos en un mensaje de Exchange ActiveSync debe ser inferior al límite de tamaño del mensaje.

- **Límite de mensaje con varias partes**: El número máximo de partes del cuerpo del mensaje que se permiten en un mensaje MIME con varias partes. Este límite también controla el número máximo de archivos adjuntos permitidos en un mensaje.

- **Límite de profundidad de incrustación de mensajes** La cantidad máxima de mensajes de correo electrónico reenviados que se permiten en un mensaje de correo electrónico.

### <a name="message-limits"></a>Límites de mensajes

| Característica | Microsoft 365 Empresa Básico | Microsoft 365 Empresa Estándar | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Límite de tamaño de mensaje - Outlook|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|
|Límite de tamaño de mensaje - OWA|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|
|Límite de tamaño de mensaje - Outlook para Mac|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|
|Límite de tamaño de mensaje: migración|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|
|Límite de tamaño de mensaje - Outlook para iOS y Android | 33 MB| 33 MB| 33 MB| 33 MB| 33 MB| 33 MB|
|Límite de tamaño de los mensajes cifrados (para los suscriptores que usan el Cifrado de mensajes de Office 365 con nuevas funciones)<sup>5</sup>|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|Límite de tamaño de los mensajes cifrados (para los suscriptores que usan la versión heredada del Cifrado de mensajes de Office 365)<sup>5</sup>|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|Límite de longitud del asunto|255 caracteres|255 caracteres|255 caracteres|255 caracteres|255 caracteres|255 caracteres|
|Límite de datos adjuntos|250 datos adjuntos|250 datos adjuntos|250 datos adjuntos|250 datos adjuntos|250 datos adjuntos|250 datos adjuntos|
|Límite del tamaño de un archivo de datos adjunto - Outlook|150 MB|150 MB|150 MB|150 MB|150 MB|150 MB|
|Límite del tamaño de un archivo de datos adjunto - OWA |112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|
|Límite del tamaño de un archivo de datos adjunto - Outlook para Mac|150 MB|150 MB|150 MB|150 MB|150 MB|150 MB|
|Límite de tamaño de archivo adjunto: Outlook para iOS y Android|33 MB |33 MB |33 MB |33 MB |33 MB |33 MB |
|Límite de mensaje con varias partes|250 partes|250 partes|250 partes|250 partes|250 partes|250 partes|
|Límite de profundidad de incrustación de mensajes|30 mensajes incrustados|30 mensajes incrustados|30 mensajes incrustados|30 mensajes incrustados|30 mensajes incrustados|30 mensajes incrustados|

> [!NOTE]
> <sup>1</sup> El tamaño máximo predeterminado de los buzones de Microsoft es 25 MB. Los administradores de Microsoft pueden especificar un límite personalizado entre 1 y 150 MB. Sin embargo, el tamaño de los mensajes que usted puede enviar o recibir también depende de qué admite el cliente de correo electrónico o la solución. Para obtener más información sobre cómo personalizar el tamaño máximo de mensaje permitido para su organización, consulte [Microsoft admite mensajes de correo electrónico más grandes](https://go.microsoft.com/fwlink/?linkid=2144144) 
<br/> <sup>2</sup> Puede enviar y recibir mensajes de hasta 150 MB entre usuarios (donde el mensaje nunca sale de los centros de datos de Microsoft) Los mensajes que se enrutan fuera de los centros de datos de Microsoft están sujetos a un aumento de codificación de traducción de 33% adicional, en cuyo caso el tamaño máximo de mensaje es 112 MB. <br/> 
<sup>3</sup> OWA permite que su mensaje esté sujeto al incremento de codificación del 33 % y limita el tamaño del mensaje que se puede enviar al 25 % menos que el valor configurado. Por ejemplo, si personaliza la configuración de tamaño de mensaje máximo en 100 MB, no se pueden enviar mensajes que superen los 75 MB. 
<br/> <sup>4</sup> Exchange Online calcula el tamaño de los mensajes que desea mover a Exchange Online. Las versiones de Exchange anteriores a Exchange Server 2013 pueden informar un tamaño de elemento más pequeño. Este límite se aplica para mover migraciones basadas mediante cualquier servicio de replicación de buzones de Exchange que sea compatible. Otros métodos de migración (total, preconfigurada, IMAP, PST) y otras herramientas de terceros están limitados por el límite de tamaño de mensaje general. <br/> 
<sup>5</sup> Para obtener información sobre OME con nuevas funciones, vea [Configurar las nuevas funciones de Cifrado de mensajes de Office 365 basadas en Azure Information Protection](https://support.office.com/article/7ff0c040-b25c-4378-9904-b1b50210d00e).<br/> 
<sup>6</sup> Los archivos adjuntos clásicos tienen un límite de 112 MB, pero los archivos adjuntos de OneDrive pueden tener hasta 2 GB.


### <a name="message-limits-across-standalone-options"></a>Límites de mensajes en las opciones independientes

| Característica | Exchange Server 2013 | Plan 1 de Exchange Online | Plan 2 de Exchange Online | Quiosco de Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Límite de tamaño de mensaje - Outlook|10 MB<sup>4</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>2</sup>|
|Límite de tamaño de mensaje - OWA|10 MB<sup>4</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|150 MB<sup>1, 2</sup>|
|Límite de tamaño de mensaje - Outlook para Mac|10 MB<sup>4</sup>|150 MB|150 MB||
|Límite de tamaño de mensaje: migración|No aplicable|150 MB<sup>5</sup>|150 MB<sup>5</sup>|150 MB<sup>5</sup>|
|Límite de tamaño de mensaje - Outlook para iOS y Android |25 MB |33 MB |33 MB |33 MB |
|Límite de tamaño de los mensajes cifrados (para los suscriptores que usan el Cifrado de mensajes de Office 365 con nuevas funciones)<sup>6</sup>|150 MB|150 MB|150 MB|150 MB|
|Límite de tamaño de los mensajes cifrados (para los suscriptores que usan la versión heredada del Cifrado de mensajes de Office 365)<sup>6</sup>|25 MB|25 MB|25 MB|25 MB|
|Límite de longitud del asunto|255 caracteres|255 caracteres|255 caracteres|255 caracteres|
|Límite de datos adjuntos|1024 attachments<sup>4</sup>|250 datos adjuntos|250 datos adjuntos|250 datos adjuntos|
|Límite del tamaño de un archivo de datos adjunto - Outlook|35 MB<sup>4</sup>|150 MB|150 MB|150 MB|
|Límite del tamaño de un archivo de datos adjunto - OWA|35 MB<sup>4</sup>|112 MB<sup>3</sup>|112 MB<sup>3</sup>|112 MB<sup>3</sup>|
|Límite del tamaño de un archivo de datos adjunto - Outlook para Mac|35 MB<sup>4</sup>|150 MB|150 MB|35 MB|
|Límite de tamaño de archivo adjunto: Outlook para iOS y Android|25 MB |33 MB|33 MB|33 MB|
|Límite de mensaje con varias partes|250 partes|250 partes|250 partes|250 partes|
|Límite de profundidad de incrustación de mensajes|30 mensajes incrustados|30 mensajes incrustados|30 mensajes incrustados|30 mensajes incrustados|

> [!NOTE]
> <sup>1</sup> Los administradores de Microsoft pueden especificar un límite personalizado entre 1 y 150 MB. Sin embargo, el tamaño de los mensajes que usted puede enviar o recibir también depende de qué admite el cliente de correo electrónico o la solución. Para obtener más información sobre cómo personalizar el tamaño máximo de mensaje permitido para su organización, consulte [Microsoft admite mensajes de correo electrónico más grandes](https://go.microsoft.com/fwlink/?linkid=2144144) <br/> <sup>2</sup> Puede enviar y recibir mensajes de hasta 150 MB entre usuarios (donde el mensaje nunca sale de los centros de datos de Microsoft) Los mensajes que se enrutan fuera de los centros de datos de Microsoft están sujetos a un aumento de codificación de traducción de 33% adicional, en cuyo caso el tamaño máximo de mensaje es 112 MB. <br/> 
<sup>3</sup> OWA permite que su mensaje esté sujeto al incremento de codificación del 33 % y limita el tamaño del mensaje que se puede enviar al 25 % menos que el valor configurado. Por ejemplo, si personaliza la configuración de tamaño máximo del mensaje en 100 MB, se pueden enviar mensajes que no superen los 75 MB. <br/> 
<sup>4</sup> Es el límite predeterminado para organizaciones de Exchange Server 2013. Los administradores pueden cambiar este valor para su organización. <br/> 
<sup>5</sup> Exchange Online calcula el tamaño de los mensajes que se van a mover a Exchange Online. Las versiones de Exchange anteriores a Exchange Server 2013 pueden informar de un tamaño de elemento más pequeño. <br/> 
<sup>6</sup> Para obtener información sobre OME con nuevas funciones, vea [Configurar las nuevas funciones de Cifrado de mensajes de Office 365 basadas en Azure Information Protection](https://support.office.com/article/7ff0c040-b25c-4378-9904-b1b50210d00e).

## <a name="receiving-and-sending-limits"></a>Límites de envío y recepción

Los límites de envío y recepción se aplican para combatir el correo no deseado o el envío masivo por correo de gusanos o virus. Estos límites ayudan a proteger nuestros sistemas y a mantener seguros a nuestros usuarios.

### <a name="receiving-limits"></a>Límites de recepción

Los límites de recepción se aplican al número de mensajes que un usuario, grupo o carpeta pública pueden recibir por hora *desde cualquier origen*. Esto incluye los mensajes de remitentes internos, los mensajes de Internet y los mensajes de servidores locales. Cuando se ha superado el límite de recepción de un buzón, los mensajes enviados al buzón se devolverán al remitente en un informe de no entrega (también conocido como NDR o mensaje de devolución) que indica que el buzón ha superado el umbral de entrega máximo. Pasada una hora, se actualizará el límite y el buzón podrá volver a recibir mensajes.

| Característica | Microsoft 365 Empresa Básico | Microsoft 365 Empresa Estándar Office | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Mensajes recibidos|3 600 mensajes por hora|3 600 mensajes por hora|3 600 mensajes por hora|3 600 mensajes por hora|3 600 mensajes por hora|3600 mensajes por hora|

### <a name="sending-limits"></a>Límites de envío

Los límites de envío se aplican al número de destinatarios, número de mensajes y número de destinatarios por mensaje que puede enviar un usuario desde su cuenta de Exchange Online.

> [!NOTE]
> Para los grupos de distribución almacenados en la libreta de direcciones de una organización, el grupo se contabiliza como un destinatario. Para los grupos de distribución almacenados en la carpeta Contactos de un buzón de correo, los miembros del grupo se contabilizan de forma individual.

- **Límite de frecuencia de destinatarios**: Para disuadir la entrega de mensajes de correo no solicitados masivos, Exchange Online tiene límites de destinatarios que evitan que los usuarios y las aplicaciones envíen grandes volúmenes de correo electrónico. Estos límites se aplican por usuario a todos los mensajes (salientes e internos).

    > [!NOTE]
    > Los clientes de Exchange Online que deben enviar un correo electrónico comercial masivo válido (por ejemplo, boletines para clientes) deberían usar proveedores de terceros especializados en dichos servicios.

- **Límite de destinatarios** La cantidad máxima de destinatarios permitidos en los campos Para:, CC: y CCO: en un solo mensaje de correo electrónico.

    > [!NOTE]
    > Para el límite de frecuencia de destinatarios y el límite de destinatarios, un grupo de distribución almacenado en la libreta de direcciones compartida de la organización se cuenta como un destinatario. En una lista personal de distribución, cada destinatario se cuenta por separado.

- **Límite de direcciones de proxy de destinatarios**: el límite de direcciones de proxy de destinatarios es el número máximo de alias (direcciones de correo electrónico) que puede tener un buzón de correo de destinatarios. 

- **Límite de frecuencia de mensajes** Los límites de frecuencia de mensajes determinan el número de mensajes que un usuario puede enviar desde su cuenta de Exchange Online durante un período determinado. Este límite ayuda a prevenir el consumo excesivo de recursos del sistema por un solo remitente. Si un usuario envía mensajes a una velocidad que supera el límite mediante el envío de cliente SMTP, se rechazarán los mensajes y el cliente tendrá que volver a intentarlo.

#### <a name="sending-limits"></a>Límites de envío

| Característica | Microsoft 365 Empresa Básico | Microsoft 365 Empresa Estándar | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Límite de frecuencia de destinatario <sup>1</sup>|10 000 destinatarios por día|10 000 destinatarios por día|10 000 destinatarios por día|10 000 destinatarios por día|10 000 destinatarios por día|10 000 destinatarios por día|
|Límite de destinatario <sup>2</sup>|Personalizable hasta 1000 destinatarios|Personalizable hasta 1000 destinatarios|Personalizable hasta 1000 destinatarios|Personalizable hasta 1000 destinatarios|Personalizable hasta 1000 destinatarios|Personalizable hasta 1000 destinatarios|
|Límite de direcciones proxy de destinatarios|400|400|400|400|400|400|
|Límite de frecuencia de mensajes<sup>3</sup>|30 mensajes por minuto|30 mensajes por minuto|30 mensajes por minuto|30 mensajes por minuto|30 mensajes por minuto|30 mensajes por minuto|

> [!NOTE]
> <sup>1</sup>: Una vez que se alcanza el límite de tasa de destinatarios, no se pueden enviar mensajes desde el buzón de correo hasta que la cantidad de destinatarios a los que se enviaron mensajes en las últimas 24 horas baje por debajo del límite. Por ejemplo, un usuario envía un mensaje de correo electrónico a 5000 destinatarios a las 09:00 a.m., luego envía otro mensaje a 2500 destinatarios a las 10:00 a.m. y luego envía otro mensaje a 2500 destinatarios a las 11:00 a.m., alcanzando el límite de 10,000 mensajes. El usuario no podrá volver a enviar mensajes hasta las 09:00 a.m. del día siguiente.  
> <sup>2</sup> Puede personalizar los límites de destinatarios entre 1 y 1000 para los buzones de correo existentes y para los nuevos que se crearán en el futuro. Edite el límite de destinatarios en los buzones de correo existentes de forma individual o en masa mediante el centro de administración de Exchange y personalice la configuración predeterminada para los nuevos buzones de correo a través de Remote PowerShell. Para obtener más información, consulte [Límites de destinatarios personalizables en Office 365](https://techcommunity.microsoft.com/t5/exchange-team-blog/customizable-recipient-limits-in-office-365/ba-p/1183228)  
> <sup>3</sup> Cuando los volúmenes de mensajes salientes superen el límite de tasa de mensajes, el exceso de envío de mensajes se limitará y se traspasó sucesivamente a los minutos siguientes. Normalmente, esto no bloqueará la cuenta del remitente, pero Exchange Online no se adapta a los escenarios de envío de correo masivo. Para este caso de uso, se recomiendan las opciones 2 y 3 [aquí](/exchange/mail-flow-best-practices/how-to-set-up-a-multifunction-device-or-application-to-send-email-using-microsoft-365-or-office-365) alternativa.

#### <a name="sending-limits-across-standalone-options"></a>Límites de envío en las opciones independientes

| Característica | Exchange Server 2013 | Plan 1 de Exchange Online | Plan 2 de Exchange Online | Quiosco de Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Límite de frecuencia de destinatario|Sin límite<sup>1</sup>|10 000 destinatarios por día <sup>2</sup>|10 000 destinatarios por día <sup>2</sup>|10 000 destinatarios por día <sup>2</sup>|
|Límite de destinatarios|1000 destinatarios<sup>1</sup>|1000 destinatarios|1000 destinatarios|1000 destinatarios|
|Límite de direcciones proxy de destinatarios|400|400|400|400|
|Límite de frecuencia de mensajes|Sin límite|30 mensajes por minuto|30 mensajes por minuto|30 mensajes por minuto|

> [!NOTE]
> <sup>1</sup> Es el límite predeterminado para organizaciones de Exchange Server 2013. Los administradores pueden cambiar este valor para su organización.<br/>
<sup>2</sup>: una vez que se alcanza el límite de tasa de destinatarios, no se pueden enviar mensajes desde el buzón de correo hasta que la cantidad de destinatarios a los que se enviaron mensajes en las últimas 24 horas baje por debajo del límite. Por ejemplo, un usuario envía un mensaje de correo electrónico a 5000 destinatarios a las 09:00 a.m., luego envía otro mensaje a 2500 destinatarios a las 10:00 a.m. y luego envía otro mensaje a 2500 destinatarios a las 11:00 a.m., alcanzando el límite de 10,000 mensajes. El usuario no podrá volver a enviar mensajes hasta las 09:00 a.m. del día siguiente.

## <a name="reporting-and-message-trace-limits"></a>Límites de seguimiento de mensajes y creación de informes

Para conocer los límites de seguimiento de mensajes y creación de informes, vea la sección sobre disponibilidad y latencia de datos de seguimiento de mensajes y creación de informes en [Informes y seguimiento de mensajes en Exchange Online Protection](/microsoft-365/security/office-365-security/reporting-and-message-trace-in-exchange-online-protection).

## <a name="retention-limits"></a>Límites de retención

Estos límites controlan el tiempo durante el cual es posible obtener acceso a los elementos de determinadas carpetas de la Bandeja de entrada.

- **Período de retención de la carpeta Elementos eliminados** La cantidad máxima de días que los elementos pueden permanecer en la carpeta Elementos eliminados antes de que se quiten automáticamente.

- **Período de retención de los elementos eliminados de la carpeta Elementos eliminados**: el número máximo de días que los elementos eliminados de la carpeta Elementos eliminados se retienen antes de eliminarlos de forma permanente.

- **Período de retención de la carpeta Correo no deseado** La cantidad máxima de días que los elementos pueden permanecer en la carpeta Correo no deseado antes de que se eliminen automáticamente.

> [!NOTE]
> Un buzón de usuario eliminado temporalmente&mdash;, un buzón eliminado mediante el Centro de administración de Microsoft 365 o el cmdlet Remove-Mailbox en Exchange Online PowerShell y que todavía está en la papelera de reciclaje de Azure Active Directory&mdash; se puede recuperar en un plazo de 30 días.

### <a name="retention-limits"></a>Límites de retención

| Característica | Microsoft 365 Empresa Básico | Microsoft 365 Empresa Estándar | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Período de retención de la carpeta Elementos eliminados|Sin límite<sup>1</sup>|Sin límite<sup>1</sup>|Sin límite<sup>1</sup>|Sin límite<sup>1</sup>|Sin límite<sup>1</sup>|Sin límite<sup>1</sup>|
|Período de retención de los elementos quitados de la carpeta Elementos eliminados|14 días<sup>1</sup>|14 días<sup>1</sup>|14 días<sup>1</sup>|14 días<sup>1</sup>|14 días<sup>1</sup>|14 días<sup>1</sup>|
|Período de retención de la carpeta Correo no deseado|30 días|30 días|30 días|30 días|30 días|30 días|

> [!NOTE]
> <sup>1</sup> Este es el valor predeterminado para las organizaciones de Microsoft 365. Los administradores pueden cambiar este valor a un máximo de 30 días para los buzones de su organización.

### <a name="retention-limits-across-standalone-options"></a>Límites de retención en las opciones independientes

| Característica | Exchange Server 2013 | Plan 1 de Exchange Online | Plan 2 de Exchange Online | Quiosco de Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Período de retención de la carpeta Elementos eliminados|Sin límite<sup>1</sup>|Sin límite<sup>1</sup>|Sin límite<sup>1</sup>|Sin límite<sup>1</sup>|
|Período de retención de los elementos quitados de la carpeta Elementos eliminados|14 días<sup>1</sup>|14 días<sup>2</sup>|14 días<sup>2</sup>|14 días<sup>2</sup>|
|Período de retención de la carpeta Correo no deseado|2 años<sup>1</sup>|30 días|30 días|30 días|

> [!NOTE]
> <sup>1</sup> Es el límite predeterminado. Los administradores pueden cambiar este valor para su organización.<br/> <sup>2</sup> Es el valor predeterminado para organizaciones de Exchange Online. Los administradores pueden cambiar este valor a un máximo de 30 días para los buzones de su organización.

## <a name="distribution-group-limits"></a>Límites de grupos de distribución

Estos límites se aplican a grupos de distribución en la libreta de direcciones compartida de su organización.

- **Número máximo de miembros de un grupo de distribución** La cantidad total de destinatarios se determina tras la expansión del grupo de distribución.

- **Límite de envío de mensajes a grandes grupos de distribución**: Los grupos de distribución que contienen este número de miembros especificado por este límite deben tener opciones configuradas de administración y aprobación de mensajes. La administración especifica una lista de remitentes con permiso para enviar mensajes al grupo de distribución. La aprobación de mensajes especifica uno o varios moderadores que deben aprobar que todos los mensajes se envíen al grupo de distribución.

- **Tamaño máximo de mensaje para grandes grupos de distribución** Si un mensaje se envía a 5000 o más destinatarios, el tamaño del mensaje no puede exceder este límite. Si lo excede, el mensaje no se entrega y el remitente recibe un informe de no entrega (NDR).

### <a name="distribution-group-limits"></a>Límites de grupos de distribución

| Característica | Microsoft 365 Empresa Básico | Microsoft 365 Empresa Estándar | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Número máximo de miembros de un grupo de distribución<sup>1</sup>|100 000 miembros|100 000 miembros|100 000 miembros|100 000 miembros|100 000 miembros|100 000 miembros|
|Límite de envío de mensajes a un grupo de distribución grande|5 000 o más miembros|5 000 o más miembros|5 000 o más miembros|5 000 o más miembros|5 000 o más miembros|5 000 o más miembros|
|Tamaño máximo de mensaje para grupos de distribución con entre 5 000 y 99 999 miembros.|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|Tamaño máximo de mensaje para grupos de distribución con 100 000 miembros.|5 MB|5 MB|5 MB|5 MB|5 MB|5 MB|
|Número máximo de propietarios de un grupo de distribución|10|10|10|10|10|10|
|Número máximo de grupos que un usuario puede crear|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> Si usa Azure Active Directory DirSync, el número máximo de miembros del grupo de distribución que se pueden sincronizar de Active Directory local a Azure Active Directory es 15 000. Si usa Azure AD Connect, el número asciende a 50 000. <br/> <sup>2</sup> Este límite se aplica también a los administradores.

### <a name="distribution-group-limits-across-standalone-options"></a>Límites de grupo de distribución en las opciones independientes

| Característica | Exchange Server 2013 | Plan 1 de Exchange Online | Plan 2 de Exchange Online | Quiosco de Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Número máximo de miembros de un grupo de distribución|100 000 miembros<sup>1</sup>|100 000 miembros|100 000 miembros|100 000 miembros|
|Límite de envío de mensajes a un grupo de distribución grande|5000 o más miembros<sup>1</sup>|5 000 o más miembros|5 000 o más miembros|5 000 o más miembros|
|Número máximo de propietarios de un grupo de distribución|10|10|10|10|
|Número máximo de grupos que un usuario puede crear|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> Es el límite predeterminado para organizaciones de Exchange Server 2013. Los administradores pueden cambiar este valor para su organización. <br/> <sup>2</sup> Este límite se aplica también a los administradores.

## <a name="journal-transport-and-inbox-rule-limits"></a>Límites de las reglas de la bandeja de entrada, del diario y de transporte

La lista siguiente incluye los límites que se aplican a las reglas del diario, a las reglas de transporte (también conocidas como reglas de toda la organización) y los límites que se aplican a la Bandeja de entrada. Los distintos usuarios configuran las reglas de la bandeja de entrada que se aplican a los mensajes que se envían y reciben en sus buzones correspondientes.

- **Número máximo de reglas del diario**: El número máximo de reglas del diario que puede existir en la organización.

- **Número máximo de reglas de transporte**: El número máximo de reglas que puede existir en la organización.

- **Tamaño máximo de una regla de transporte individual**: El número máximo de caracteres que se pueden usar en una sola regla de transporte. Los caracteres se emplean en las condiciones, excepciones y acciones.

- **Límite de caracteres para todas las expresiones regulares utilizadas en todas las reglas de transporte**: El número total de caracteres utilizados, incluidas todas las expresiones regulares en todas las condiciones y excepciones de las reglas de transporte en la organización. Puede disponer de unas cuantas reglas que usen expresiones largas y complejas, o muchas reglas con expresiones regulares sencillas.

- **Límites de análisis del contenido de los archivos adjuntos**: las condiciones de la regla de transporte le permiten examinar el contenido de los archivos adjuntos de los mensajes, pero solo se inspecciona el primer MB del texto extraído de un archivo adjunto. Este límite de 1 MB se refiere al texto extraído de los datos adjuntos, no al tamaño de archivo de los datos adjuntos. Por ejemplo, un archivo de 2 MB puede tener menos de 1 MB de texto, en cuyo caso todo el texto sería inspeccionado.

- **Número máximo de recipientes agregados a un mensaje por todas las reglas de trasporte**: Cuando en un mensaje actúan diferentes reglas de transporte, solo se puede agregar al mensaje un número finito de destinatarios. Una vez alcanzado el límite, los demás destinatarios no se agregan al mensaje. Asimismo, los grupos de distribución no pueden agregarse a un mensaje mediante una regla de transporte.

- **Límite de reenvío**: El número máximo de destinatarios que se puede configurar para una regla de transporte o de bandeja de entrada con una acción de redireccionamiento. Si se configura una regla para redireccionar un mensaje a más de este número de destinatarios, la regla no se aplicará y cualquier mensaje que satisfaga la condición de la regla no redirigirá ninguno de los destinatarios enumerados en la regla.
    
- **Número de veces que se redirige un mensaje** El número de veces que se redirigirá, reenviará o responderá automáticamente un mensaje en función de las reglas de la Bandeja de entrada. Por ejemplo, el usuario A tiene una regla de Bandeja de entrada que redirige los mensajes al usuario B, en función del remitente. El usuario B tiene una regla de Bandeja de entrada que reenvía los mensajes al usuario C, en función de palabras clave en la línea del asunto. Si un mensaje cumple estas dos condiciones, el mensaje solo se envía al usuario B; no se reenvía al usuario C ya que solo se permite un redireccionamiento. En este caso, el mensaje se descarta sin enviar un informe de no entrega (NDR) al Usuario B que indica que el mensaje no se entregó al Usuario C. Hacemos uso del encabezado X-MS-Exchange-Inbox-Rules-Loop para determinar el número de veces que se redirigió un mensaje. Este encabezado también se mantiene a través de los límites organizacionales de Exchange.

- **Número de veces que un mensaje es redirigido por las reglas de transporte**: el número de veces que un mensaje será redirigido según las reglas de transporte. Por ejemplo, la organización de Exchange Tailspin Toys tiene una regla de transporte para redirigir todos los mensajes que se enviaron al Usuario A al Usuario B, que se encuentra en la organización de Exchange Contoso. Dentro de la organización de Exchange Contoso, existe una regla de transporte para redirigir cada mensaje que se envió al usuario B al usuario C, que se encuentra en la organización de Exchange A. Datum Corporation. En este caso, el mensaje se descarta y un informe de no entrega (NDR) con el código de estado y el mensaje de rechazo *550 5.7.128 TRANSPORT.RULES.RejectMessage; Se superó el recuento de bucles de reglas de transporte y el mensaje rechazado* se envía al usuario A. Hacemos uso del encabezado X-MS-Exchange-Transport-Rules-Loop para determinar la cantidad de veces que un mensaje fue redirigido por las reglas de transporte. Este encabezado también se mantiene a través de los límites organizacionales de Exchange.

### <a name="journal-transport-and-inbox-rule-limits"></a>Límites de las reglas de la bandeja de entrada, del diario y de transporte

| Característica | Microsoft 365 Empresa Básico | Microsoft 365 Empresa Estándar | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Número máximo de reglas del diario|300 reglas|300 reglas|300 reglas|300 reglas|300 reglas|300 reglas|
|Número máximo de reglas de transporte|300 reglas|300 reglas|300 reglas|300 reglas|300 reglas|300 reglas|
|Tamaño máximo de una regla de transporte individual|8 KB|8 KB|8 KB|8 KB|8 KB|8 KB|
|Límite de caracteres para todas las expresiones regulares usadas en todas las reglas de transporte|20 KB|20 KB|20 KB|20 KB|20 KB|20 KB|
|Límites de análisis para el contenido de datos adjuntos|1 MB|1 MB|1 MB|1 MB|1 MB|1 MB|
|Número máximo de destinatarios agregados a un mensaje por todas las reglas de trasporte|100 destinatarios|100 destinatarios|100 destinatarios|100 destinatarios|100 destinatarios|100 destinatarios|
|Límite de reenvío|10 destinatarios|10 destinatarios|10 destinatarios|10 destinatarios|10 destinatarios|10 destinatarios|
|Número de veces que se redirige un mensaje|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|
|Número de veces que se redirige un mensaje por las reglas de transporte|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|
|Número de veces que se redirige un mensaje|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|
|Reglas de la bandeja de entrada|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|

> [!NOTE]
> <sup>1</sup> Si se migró un buzón a Exchange Online, el límite de la regla de la bandeja de entrada se puede establecer en un valor inferior al valor EXO predeterminado. Si ese es el caso, se puede aumentar el valor de la regla de la bandeja de entrada. Para obtener instrucciones, consulte [Modificar el espacio utilizado por las reglas de la Bandeja de entrada en Exchange Online](/exchange/clients-and-mobile-in-exchange-online/outlook-on-the-web/increase-the-space-used-by-inbox-rules). 

### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>Límites de reglas del diario, transporte y Bandeja de entrada en las opciones independientes

| Característica | Exchange Server 2013 | Plan 1 de Exchange Online | Plan 2 de Exchange Online | Quiosco de Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Número máximo de reglas del diario|Sin límite|50 reglas|50 reglas|50 reglas|
|Número máximo de reglas de transporte|Sin límite|300 reglas|300 reglas|300 reglas|
|Tamaño máximo de una regla de transporte individual|40 KB|8 KB|8 KB|8 KB|
|Límite de caracteres para todas las expresiones regulares usadas en todas las reglas de transporte|Sin límite|20 KB|20 KB|20 KB|
|Número máximo de destinatarios agregados a un mensaje por todas las reglas de trasporte|Sin límite|100 destinatarios|100 destinatarios|100 destinatarios|
|Límite de reenvío|Sin límite|10 destinatarios|10 destinatarios|10 destinatarios|
|Número de veces que se redirige un mensaje|3 redireccionamientos|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|
|Número de veces que se redirige un mensaje por las reglas de transporte|Sin límite|1 redireccionamiento|1 redireccionamiento|1 redireccionamiento|

## <a name="moderation-limits"></a>Límites de moderación

Estos límites controlan la configuración de la moderación empleada para la aprobación de mensajes que se aplica a los grupos de distribución y las reglas de transporte.

- **Tamaño máximo de buzón de correo de arbitraje**: Si el buzón de correo de arbitraje excede este límite, los mensajes que requieren moderación se devolverán al remitente en un informe de no entrega (NDR).

- **Cantidad máxima de moderadores**: La cantidad máxima de moderadores que puede asignar a un solo grupo de distribución moderado o que puede agregarse a un mensaje utilizando una regla de transporte. Tenga en cuenta que no puede especificar un grupo de distribución como moderador.

- **Expiración de mensajes en espera de ser moderados**: De forma predeterminada, un mensaje en espera de ser moderado expira a los dos días. No obstante, el procesamiento de mensajes moderados expirados se ejercita cada siete días. Esto significa que un mensaje moderado puede expirar en cualquier momento entre dos y nueve días.

- **Máximo índice de mensajes de notificación de moderación caducada**: Este límite establece la cantidad máxima de mensajes de notificación acerca de mensajes moderados expirados en el período de una hora. Este límite se coloca en cada base de datos de buzones de correo del centro de datos.

Durante períodos de gran actividad, algunos remitentes no recibirán mensajes de notificación de mensajes moderados que hayan expirado. Sin embargo, estas notificaciones aún se pueden detectar usando informes de entrega.

### <a name="moderation-limits"></a>Límites de moderación

| Característica | Microsoft 365 Empresa Básico | Microsoft 365 Empresa Estándar | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Tamaño máximo de buzón de correo de arbitraje|10 GB|10 GB|10 GB|10 GB|10 GB|10 GB|
|Número máximo de moderadores|10 moderadores|10 moderadores|10 moderadores|10 moderadores|10 moderadores|10 moderadores|
|Caducidad de mensajes en espera de ser moderados|2 días|2 días|2 días|2 días|2 días|2 días|
|Máximo índice de mensajes de notificación de moderación caducada|300 notificaciones de caducidad por hora|300 notificaciones de caducidad por hora|300 notificaciones de caducidad por hora|300 notificaciones de caducidad por hora|300 notificaciones de caducidad por hora|300 notificaciones de caducidad por hora|

### <a name="moderation-limits-across-standalone-options"></a>Límites de moderación en las opciones independientes

| Característica | Exchange Server 2013 | Plan 1 de Exchange Online | Plan 2 de Exchange Online | Quiosco de Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Tamaño máximo de buzón de correo de arbitraje|Sin límite<sup>1</sup>|10 GB|10 GB|10 GB|
|Número máximo de moderadores|Sin límite|10 moderadores|10 moderadores|10 moderadores|
|Caducidad de mensajes en espera de ser moderados|5 días<sup>1</sup>|2 días|2 días|2 días|
|Máximo índice de mensajes de notificación de moderación caducada|300 notificaciones de caducidad por hora|300 notificaciones de caducidad por hora|300 notificaciones de caducidad por hora|300 notificaciones de caducidad por hora|

> [!NOTE]
> <sup>1</sup> Es el límite predeterminado para organizaciones de Exchange Server 2013. Los administradores pueden cambiar este valor para su organización.

## <a name="exchange-activesync-limits"></a>Límites de Exchange ActiveSync

Los siguientes límites se aplican a Microsoft Exchange ActiveSync, un protocolo de cliente que sincroniza los datos de los buzones entre los dispositivos móviles y Exchange.

- **Límite de dispositivos Exchange ActiveSync**: El número máximo de dispositivos Exchange ActiveSync por buzón.

- **Límite de eliminación de dispositivos Exchange ActiveSync**: La cantidad máxima de dispositivos Exchange ActiveSync que un administrador de Exchange puede eliminar en un solo mes.

### <a name="exchange-activesync-limits"></a>Límites de Exchange ActiveSync

| Característica | Microsoft 365 Empresa Básico | Microsoft 365 Empresa Estándar | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Límite de dispositivos de Exchange ActiveSync|100|100|100|100|100|100|
|Límite de eliminación de dispositivos de Exchange ActiveSync|20|20|20|20|20|20|

### <a name="exchange-activesync-limits-across-standalone-options"></a>Límites de Exchange ActiveSync en opciones independientes

| Característica | Exchange Server 2013 | Plan 1 de Exchange Online | Plan 2 de Exchange Online | Quiosco de Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Límite de dispositivos de Exchange ActiveSync|100|100|100|100|
|Límite de eliminación de dispositivos de Exchange ActiveSync|20|20|20|20|