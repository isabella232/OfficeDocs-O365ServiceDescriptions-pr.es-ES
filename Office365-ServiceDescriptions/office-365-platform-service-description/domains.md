---
title: Dominios
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-domains
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 5c374309-8016-4f18-8f2a-bceeb863ca67
description: Cuando agrega un dominio, un asistente paso a paso le ayuda a agregar usuarios y convertir las direcciones de correo electrónico y otros servicios al nombre de la empresa. Al completar el asistente, el correo electrónico de la empresa empieza a llegar a Microsoft en lugar de ir a su proveedor de correo electrónico actual. Para obtener más información, vea Agregar usuarios y dominios a Microsoft. Si Office 365 operado por 21Vianet, vea Comprobar el dominio.
ms.openlocfilehash: b6bbd87a1c3f303ceec0de90b42b322ba513d354
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132404"
---
# <a name="domains"></a>Dominios

Cuando agrega un dominio, un asistente paso a paso le ayuda a agregar usuarios y convertir las direcciones de correo electrónico y otros servicios al nombre de la empresa. Al completar el asistente, el correo electrónico de la empresa empieza a llegar a Microsoft en lugar de ir a su proveedor de correo electrónico actual. Para obtener más información, vea [Agregar usuarios y dominios a Microsoft](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611). Si Office 365 operado por 21Vianet, vea [Comprobar el dominio](https://docs.microsoft.com/office365/admin/setup/add-domain).
  
## <a name="custom-domains"></a>Dominios personalizados

Puede Agregar hasta 900 dominios a su suscripción. Pero no puede agregar un dominio a Office 365 que ya use en otro servicio en la nube de Microsoft. Esto significa que no puede Agregar el mismo dominio a varias suscripciones. Para obtener más información, consulte [preguntas más frecuentes sobre dominios](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a).
  
### <a name="second-and-third-level-domains"></a>Dominios de segundo y tercer nivel

Con Office 365 Enterprise y Microsoft 365 apps for Business, puede agregar cualquier nivel de dominio, incluidos los dominios de tercer nivel, como marketing.contoso.com. Vea [agregar subdominios personalizados o varios dominios a Microsoft](https://docs.microsoft.com/office365/admin/setup/domains-faq). Si usa Office 365 operado por 21Vianet, consulte [Agregar subdominios personalizados o varios dominios a Office 365 operado por 21Vianet](https://docs.microsoft.com/office365/admin/setup/domains-faq).
  
## <a name="domain-verification-and-managing-dns-records"></a>Comprobación de dominios y administración de registros DNS

Con Microsoft 365, puede administrar todos los registros DNS en su proveedor de host DNS o optar por que Microsoft configure y administre los registros DNS de su dominio por usted. Si continúa administrando los registros, cambie los registros específicos para que apunten a los servicios de Microsoft según sea necesario. Para obtener una lista de registradores de dominios para los que proporcionaremos instrucciones paso a paso para agregar registros, incluidos los valores específicos que se deben usar para cada registro, vea [Create DNS Records](https://docs.microsoft.com/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider) o, si usa Office 365 operado por 21Vianet, vea Create DNS Records on any Provider for Office 365 operado por 21Vianet. 
  
Si Microsoft administra los registros DNS de su dominio por usted, primero debe cambiar los registros del servidor de nombres de su dominio para que apunten a Microsoft y, a continuación, Microsoft configura los servicios y, a continuación, los registros DNS de su dominio se administran en Microsoft.
  
Si su dominio está registrado en GoDaddy, Microsoft puede crear los registros necesarios en GoDaddy. 
  
Independientemente de dónde se hospeden los registros DNS, puede configurar los registros DNS para que usen el dominio para la dirección URL de un sitio web público hospedado en Microsoft o con un proveedor de hospedaje diferente. 
  
Microsoft comprueba proactivamente los registros DNS para encontrar y ayudar a solucionar problemas de DNS. Si sus registros DNS no coinciden con lo que esperamos que sean, recibirá una notificación en el centro de administración de 365 de Microsoft, junto con información que le indicará cómo corregir los posibles problemas que se han identificado.
  
Para obtener más información, vea [cómo Microsoft administra los registros DNS](https://docs.microsoft.com/office365/admin/setup/domains-faq) o, para Office 365 operado por 21Vianet, vea [crear registros dns para Office 365 cuando administre sus registros DNS](https://docs.microsoft.com/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records).
  
## <a name="sharing-a-domain"></a>Compartir un dominio

Puede realizar una prueba piloto de algunas direcciones de correo electrónico para un dominio de Microsoft y algunas en su proveedor de correo electrónico anterior. Esto solo se recomienda para su uso durante una prueba piloto, ya que requiere pasos de configuración adicionales y tiene algunas limitaciones para los servicios Microsoft. Para obtener más información, vea:
  
- [Piloto de Microsoft 365 para una pequeña empresa](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [Piloto de Microsoft 365 para una gran empresa (mediante FastTrack)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características en Microsoft 365 para los planes empresariales, las opciones independientes y las soluciones locales, vea la descripción del servicio de la [plataforma 365 y Office 365 de Microsoft](office-365-platform-service-description.md).
  

