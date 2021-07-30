---
title: Límites en Yammer
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- yammer-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: ''
description: Obtenga información sobre los límites de servicio en Yammer para Microsoft 365.
ms.openlocfilehash: 390bb642e45e2ac4868069698530d7c43a171762
ms.sourcegitcommit: c061620e1ccabec8ee97d49f25d575cde54fbc9b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/30/2021
ms.locfileid: "53661656"
---
# <a name="limits-in-yammer"></a>Límites en Yammer

Obtenga información sobre los límites de servicio en Yammer para Microsoft 365.

## <a name="network-limits"></a>Límites de red

| Característica | Detalles |
|---------|---------|
| Modo nativo | [Se recomienda](/yammer/configure-your-yammer-network/overview-native-mode) el modo nativo para la mejor compatibilidad a largo plazo. Yammer redes en Microsoft 365 modo nativo tienen características diferentes a las redes Yammer heredadas. |
| Actualización masiva para administradores de red | Las actualizaciones masivas a los usuarios se admiten para redes de modo no nativo de 2000 usuarios o menos. |
| Redes de inicio | Las redes de inicio no se pueden eliminar ni volver a crear. |

## <a name="file-limits"></a>Límites de archivos

| Característica | Detalles |
|---------|---------|
| Tamaño y almacenamiento máximos de archivos | Se recomienda migrar Microsoft 365 modo nativo para Yammer para asegurarse de que todos los archivos se almacenan en SharePoint Online. <br/>Para Yammer archivos almacenados en SharePoint: <ul><li>El tamaño máximo de un archivo adjunto es de 15 gigabytes (GB).</li><li>No hay limitaciones de dimensión para las imágenes, pero se SharePoint la configuración de tamaño máximo de la organización.</li><li>Se puede agregar cualquier tipo de archivo, pero la vista previa y la edición están limitadas a determinados tipos de archivo.</li> </ul><br/>[SharePoint límites se](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-limits) aplican Microsoft 365 [comunidades conectadas](/yammer/manage-yammer-groups/yammer-and-office-365-groups) en Yammer. <br/>Para los archivos almacenados en Yammer de archivos: <br/><ul><li>El tamaño máximo de los datos adjuntos de un solo archivo es de 5 gigabytes (GB) para las redes Yammer Enterprise y 100 megabytes (MB) para Yammer redes básicas.</li><li>Las dimensiones máximas son de 7.680 píxeles de ancho y 4.320 píxeles de alto, y el tamaño máximo de imagen es de 10 megabytes (MB).</li></ul> <br/>Para obtener más información sobre el uso de imágenes, incluidas las plantillas y las dimensiones de las fotos de portada, [vea Yammer Adoption Resources](https://adoption.microsoft.com/yammer/). |
| Número de datos adjuntos de archivo por publicación | Cada publicación puede tener un máximo de 100 archivos. |
| Formatos de vídeo compatibles | Los siguientes tipos de vídeo son compatibles con la reproducción en línea: .wmv, .avi, .mpeg, .3gp, .flv, .mov, .mp4, .mpg, .ogm, .mkv, .ogv y .ogg. <br/>Yammer usa Azure Media Services para mostrar vídeos cargados en Yammer. |
| Reproducción de vídeo en línea | Microsoft Stream, SharePoint Online, YouTube y Vimeo son compatibles con la reproducción en línea. |
| Acceso de invitado | Microsoft 365 El modo nativo para Yammer es necesario para la compatibilidad completa con invitados. <br/>Los invitados heredados de nivel de red pueden experimentar problemas de acceso a archivos. |
| Vistas previas de vínculos (Graph objetos) | Los vínculos a sistemas internos que no se pueden resolver públicamente o que requieren autenticación no mostrarán vistas previas válidas porque no se pueden extraer metadatos. |

## <a name="yammer-live-event-limits"></a>Yammer de eventos en directo

| Característica | Detalles |
|---------|---------|
| Número de visores de eventos en directo | Actualmente, el límite es de 10.000 participantes. Para eventos de mayor tamaño, trabaje a través del [Programa de asistencia de eventos en directo](https://resources.techcommunity.microsoft.com/live-events/assistance/). |
| Permisos de creación de eventos en directo | Se requiere permiso para crear eventos en directo en Stream. <br/>Community administradores de Yammer pueden crear o programar eventos en directo. |
| Acceso de invitado | Los miembros de la red canónica pueden crear o asistir a eventos en directo en Yammer. |
| Subtítulos cerrados | Los títulos cerrados no están disponibles para eventos en directo en Yammer. Una actualización futura agregará compatibilidad con los títulos cerrados. |
| Duración del evento | 4 horas |
| Eventos en directo simultáneos que se Microsoft 365 o Office 365 organización | 50 eventos por inquilino |
| ¿Límite de presentadores? | 100 presentadores |

Para obtener más límites Microsoft Teams eventos en directo y reuniones, [vea Teams Live Events](/microsoftteams/limits-specifications-teams#teams-live-events).

## <a name="yammer-community-limits"></a>Yammer de la comunidad

| Característica | Detalles |
|---------|---------|
| Número de miembros de una comunidad | Varía en función de si la comunidad está [conectada a un grupo Microsoft 365,](/yammer/manage-yammer-groups/yammer-and-office-365-groups)es una comunidad dinámica o es la comunidad De todas [las](/yammer/manage-yammer-groups/yammer-all-company-yammer-community) compañías. [](/yammer/manage-yammer-groups/create-a-dynamic-group) <br/>Límite de pertenencia dinámica a la comunidad: 500K |
| Número de comunidades que puede ser miembro | 7,000 |
| Número de actualizaciones a través de la importación de libreta de direcciones para agregar varios usuarios a la vez | 200 miembros de la comunidad por carga por lotes. |
| Límite de comunidades dinámicas | Sin límite |
| Número de administradores por comunidad | En modo nativo, los administradores pueden establecer un mínimo. Las redes de modo no nativo tienen un límite de 100 administradores por comunidad. |
| Número de administradores de red | Varía en función de la configuración del modo nativo. No hay límite de administradores de red. |
| Comunidades conectadas y Sincronización de Azure AD | La latencia con sincronización puede producirse con una pertenencia a la comunidad de más de 100 K. |
| Miembros de toda la compañía | Incluye todos los usuarios del espacio empresarial. |
| Número de comunidades oficiales | Sin límite |
| Número de comunidades de favoritos | 10  |
| Community de caracteres de nombre | Depende de la convención de nomenclatura de la red. <br/>Máximo de 255 caracteres, incluido cualquier prefijo. |
| Community de caracteres de descripción | 150 caracteres |
| Community información | Sin límite de caracteres (hasta 1 GB) |
| Límite de recursos anclados | Sin límite |
| Límite de comunidades relacionadas | No hay límite para las comunidades normales, pero los procedimientos recomendados son entre 3 y 5 comunidades relacionadas. <br/>Las comunidades relacionadas no están disponibles para Toda la compañía. |
| Límite de miembros pendientes para comunidades privadas | Sin límite. |
| Límites de la administración de la comunidad en modo nativo | Los grupos conectados deben administrarse con herramientas diseñadas para actualizar Microsoft 365 grupos, incluidos el portal de administración de Microsoft 365, el portal de Azure AD y el módulo PowerShell de Azure AD. |
| Publicar por correo electrónico | Sin límite |

## <a name="yammer-messaging-limitations"></a>Yammer limitaciones de mensajería

| Característica | Detalles |
|---------|---------|
| Límite de caracteres por mensaje | Límite de caracteres de 10.000 |
| Eliminar conversaciones | La eliminación de un subproceso completo requiere que se eliminen todos los mensajes. Al eliminar el inicio de conversación, se promoverá la primera respuesta para convertirse en el iniciador de subprocesos. <br/>Los administradores de red pueden eliminar mensajes de cualquier subproceso de conversación si [el modo de contenido privado](/yammer/manage-security-and-compliance/monitor-private-content) está habilitado. <br/>Community administradores pueden eliminar mensajes en la comunidad que administran. <br/>El autor original solo puede eliminar sus propias publicaciones. |
| Límite de mensajes por subproceso de conversación | Una conversación puede tener hasta 10 000 publicaciones. |
| Vistas previas de vínculos (Graph metadatos) |<ul><li>Las vistas previas del contenido de vínculo solo se pueden generar para el contenido público y algunos recursos Microsoft 365 compatibles.</li><li>La generación de vista previa depende de la extracción correcta de metadatos en el momento de la publicación, que puede variar en función de la disponibilidad del sitio al que se va a vincular.</li><li>No se admiten vínculos a sistemas dentro del firewall de organizaciones o que requieren autenticación. </li><li>Es posible que los metadatos de vista previa de vínculos no se actualicen después del primer uso del vínculo dentro de la red.</li></ul> |
| Modo de contenido privado | Los administradores comprobados no pueden tener acceso al contenido privado de forma predeterminada. El modo de contenido privado debe estar habilitado para tener acceso a mensajes privados y comunidades privadas. |
| Respuestas anidadas y subprocesos heredados | Los subprocesos heredados permitirán la creación de nuevas respuestas anidadas. Los mensajes "en respuesta" más antiguos permanecerían como comentarios de nivel superior, por ahora. |

## <a name="external-network-limits"></a>Límites de red externa

| Característica | Detalles |
|---------|---------|
| Redes externas | Limitación de 5 redes externas que un administrador puede crear si esas 5 redes externas tienen un solo miembro (normalmente, ese miembro es el creador de la red). <br/> Si hay al menos otro usuario en una red externa, no cuenta para ese límite. |
| Archivos | Los archivos se almacenan en Yammer y no se puede acceder a ellos a través de SharePoint. |
| Comunidades | Las comunidades no están conectadas a Microsoft 365 grupos. |
| Modo nativo | [Las características y restricciones del](/yammer/configure-your-yammer-network/overview-native-mode) modo nativo no se aplican a las redes externas. |