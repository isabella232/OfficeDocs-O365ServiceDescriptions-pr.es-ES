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
description: Al agregar un dominio, un asistente paso a paso le ayuda a agregar usuarios y convertir sus direcciones de correo electrónico y otros servicios al nombre de su empresa. Cuando complete el asistente, el correo electrónico empresarial empezará a llegar a Microsoft en lugar de ir a su proveedor de correo electrónico actual. Para obtener más información, consulta Agregar usuarios y dominios a Microsoft. Si Office 365 operado por 21Vianet, vea Comprobar el dominio.
ms.openlocfilehash: 57df3e7fb22e8a576099432b8cdc7c84a8462bad
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2021
ms.locfileid: "51172995"
---
# <a name="domains"></a>Dominios

Al agregar un dominio, un asistente paso a paso le ayuda a agregar usuarios y convertir sus direcciones de correo electrónico y otros servicios al nombre de su empresa. Cuando complete el asistente, el correo electrónico empresarial empezará a llegar a Microsoft en lugar de ir a su proveedor de correo electrónico actual. Para obtener más información, vea [Agregar los usuarios y dominios a Microsoft](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611). Si Office 365 operado por 21Vianet, vea [Comprobar el dominio](/office365/admin/setup/add-domain).
  
## <a name="custom-domains"></a>Dominios personalizados

Puede agregar hasta 900 dominios a la suscripción (incluidos los subdominios). No puede agregar un dominio a Microsoft 365 que ya está usando en otro servicio en la nube de Microsoft. Esto significa que no puede agregar el mismo dominio a varias suscripciones. Para obtener más información, vea [Preguntas más frecuentes sobre dominios](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a).
  
### <a name="second-and-third-level-domains"></a>Dominios de segundo y tercer nivel

Con Office 365 Enterprise y Aplicaciones de Microsoft 365 para empresas, puede agregar cualquier dominio de nivel, incluidos los dominios de tercer nivel, como marketing.contoso.com. Vea [Agregar subdominios personalizados o varios dominios a Microsoft](/office365/admin/setup/domains-faq). Si usa Office 365 operado por 21Vianet, consulte [Agregar subdominios personalizados o varios dominios a Office 365 operado por 21Vianet](/office365/admin/setup/domains-faq).
  
## <a name="domain-verification-and-managing-dns-records"></a>Comprobación de dominios y administración de registros DNS

Con Microsoft 365, puede administrar todos los registros DNS en su proveedor de hospedaje DNS o optar por que Microsoft configure y administre los registros DNS de su dominio. Si continúa administrando los registros, cambia registros específicos para que apunten a los servicios de Microsoft según sea necesario. Para obtener una lista de registradores de dominios para los que proporcionamos instrucciones paso a paso para agregar los registros, incluidos los valores específicos que se van a usar para cada registro, vea [Create DNS records](/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider) o, si usa Office 365 operado por 21Vianet, vea Create DNS records at any provider for Office 365 operated by 21Vianet. 
  
Si Microsoft administra los registros DNS de su dominio por usted, primero debe cambiar los registros de servidor de nombres de su dominio para que apunten a Microsoft y, a continuación, Microsoft configura los servicios y, a continuación, los registros DNS de su dominio se administran en Microsoft.
  
Si su dominio está registrado en GoDaddy, Microsoft puede crear los registros necesarios para usted en GoDaddy. 
  
Independientemente de dónde estén hospedados los registros DNS, puede configurar los registros DNS para que usen su dominio para la dirección URL de un sitio web público hospedado en Microsoft o con un proveedor de hospedaje diferente. 
  
Microsoft comprueba proactivamente los registros DNS para buscar y ayudar a solucionar problemas de DNS. Si los registros DNS no coinciden con lo que esperamos que sean, recibirá una notificación en el Centro de administración de Microsoft 365, junto con información que le indica cómo solucionar los posibles problemas que se han identificado.
  
Para obtener más información, vea How [Microsoft manages DNS records](/office365/admin/setup/domains-faq) o, for Office 365 operated by 21Vianet, see Create DNS records for Office [365 when you manage your DNS records](/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records).
  
## <a name="sharing-a-domain"></a>Compartir un dominio

Puede pilotar algunas direcciones de correo electrónico para un dominio en Microsoft y otras en su proveedor de correo electrónico anterior. Esto solo se recomienda para su uso durante un piloto, ya que requiere pasos de configuración adicionales y tiene algunas limitaciones para los servicios de Microsoft. Para más información, vea:
  
- [Piloto de Microsoft 365 para una pequeña empresa](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [Piloto de Microsoft 365 para una gran empresa (con FastTrack)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características en planes de Microsoft 365 para empresas, opciones independientes y soluciones locales, vea [Microsoft 365 and Office 365 platform service description](office-365-platform-service-description.md).
