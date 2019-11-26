---
title: Dominios
ms.author: sharik
author: skjerland
manager: mnirkhe
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
description: Cuando agrega un dominio, un asistente paso a paso le ayuda a agregar usuarios y convertir las direcciones de correo electrónico de Office 365 y otros servicios al nombre de la empresa. Cuando completa el asistente, el correo electrónico de la empresa empieza a llegar a Office 365 en vez de ir su proveedor de correo electrónico actual. Para obtener más información, consulte Agregar usuarios y dominios a Office 365. Si usa Office 365 operado por 21Vianet, consulte comprobar el dominio.
ms.openlocfilehash: a1038e0ff6db0dc5def4fd5d50bd5798e45fde2c
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262793"
---
# <a name="domains"></a>Dominios

Cuando agrega un dominio, un asistente paso a paso le ayuda a agregar usuarios y convertir las direcciones de correo electrónico de Office 365 y otros servicios al nombre de la empresa. Cuando completa el asistente, el correo electrónico de la empresa empieza a llegar a Office 365 en vez de ir su proveedor de correo electrónico actual. Para obtener más información, consulte [Agregar usuarios y dominios a Office 365](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611). Si Office 365 operado por 21Vianet, vea [Comprobar el dominio](https://docs.microsoft.com/office365/admin/setup/add-domain).
  
## <a name="custom-domains"></a>Dominios personalizados

Puede agregar hasta 900 dominios a su suscripción de Office 365. Pero no puede agregar un dominio a Office 365 que ya use en otro servicio en la nube de Microsoft. Lo que significa que no puede agregar el mismo dominio a múltiples suscripciones de Office 365. Para obtener más información, consulte [preguntas más frecuentes sobre dominios](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a).
  
### <a name="second-and-third-level-domains"></a>Dominios de segundo y tercer nivel

Con Office 365 Enterprise y Office 365 Empresa, puede agregar un dominio de cualquier nivel, incluidos los dominios de tercer nivel, como marketing.contoso.com. Vea [Agregar subdominios personalizados o varios dominios a Office 365](https://docs.microsoft.com/office365/admin/setup/domains-faq). Si usa Office 365 operado por 21Vianet, consulte [Agregar subdominios personalizados o varios dominios a Office 365 operado por 21Vianet](https://docs.microsoft.com/office365/admin/setup/domains-faq).
  
## <a name="domain-verification-and-managing-dns-records"></a>Comprobación de dominios y administración de registros DNS

Con Office 365, puede administrar todos los registros DNS en su proveedor de host DNS, o bien optar por que Office 365 se encargue de configurar y administrar automáticamente los registros DNS de su dominio. Si continúa administrando los registros, deberá cambiar registros específicos para que apunten a servicios de Office 365 según sea necesario. Si quiere obtener una lista de registradores de dominios cuyas indicaciones paso a paso para agregar los registros, incluidos los valores específicos que deben usarse en cada registro, ofrecemos, vea [Crear registros DNS en cualquier proveedor de hospedaje DNS para Office 365](https://docs.microsoft.com/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider) o, si usa Office 365 operado por 21Vianet, vea Create DNS records at any provider for Office 365 operated by 21Vianet (Crear registros DNS en cualquier proveedor de Office 365 operado por 21Vianet). 
  
Si Office 365 administra los registros DNS de su dominio, primero debe cambiar los registros de servidor de nombres de su dominio para que apunten a Office 365. A continuación, Office 365 configura sus servicios de Office 365 y, luego, los registros DNS de su dominio se administran en Office 365.
  
Si su dominio está registrado en GoDaddy, Office 365 puede crear los registros necesarios en GoDaddy. 
  
Sin importar dónde estén albergados sus registros DNS, puede configurar los registros DNS para utilizar un sitio web público albergado en Office 365 o con un proveedor de host diferente. 
  
Office 365comprueba de forma proactiva los registros DNS para buscar y solucionar problemas relacionados con el DNS. Si sus registros DNS no coinciden con lo que esperamos que sean, recibirá una notificación en el centro de administración de 365 de Microsoft, junto con información que le indicará cómo corregir los posibles problemas que se han identificado.
  
Para obtener más información, vea [Cómo administra Office 365 los registros DNS](https://docs.microsoft.com/office365/admin/setup/domains-faq) o, para Office 365 operado por 21Vianet, vea [Create DNS records for Office 365 when you manage your DNS records ](https://docs.microsoft.com/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records).
  
## <a name="sharing-a-domain"></a>Compartir un dominio

Puede probar Office 365 con algunas direcciones de correo electrónico de un dominio en Office 365 y algunas en su proveedor anterior de correo electrónico. Esto solo se recomienda para su uso durante una prueba piloto de Office 365, ya que requiere pasos de configuración adicionales y tiene algunas limitaciones para los servicios de Office 365. Para obtener más información, vea:
  
- [Pilotar Office 365 para una empresa pequeña](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [Pilotar Office 365 para una gran empresa (mediante FastTrack)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [Office 365 Platform Service Description](office-365-platform-service-description.md).
  

