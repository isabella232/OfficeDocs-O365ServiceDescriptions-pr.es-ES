---
title: SharePoint entornos gubernamentales de Estados Unidos
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: Obtenga información sobre la SharePoint de características para los clientes en la nube del gobierno de Estados Unidos.
ms.openlocfilehash: 3d0660316b53d9aaef8adf514c8835950150abd8
ms.sourcegitcommit: b47c4912a47ce47bb3c20e696cc3700b14464c7b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/04/2021
ms.locfileid: "60088513"
---
# <a name="sharepoint-for-us-government-environments"></a>SharePoint entornos gubernamentales de Estados Unidos

En este artículo se proporciona información general sobre las diferencias de características entre la nube del gobierno de Estados Unidos y la nube [comercial,](../../sharepoint-online-service-description/sharepoint-online-service-description.md)tal como se muestra en SharePoint descripción del servicio . SharePoint está disponible para los entornos Government Community Cloud (GCC), GCC High y DoD. 

Para obtener más información acerca de la nube gubernamental, incluida la elegibilidad y la compra, vea [Microsoft 365 Government - how to buy](./microsoft-365-government-how-to-buy.md). Para comparar Office 365 Administración Pública planes, [vea Office 365 Administración Pública planes](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).

Para obtener información sobre los puntos de conexión necesarios al administrar la conectividad de red, vea Office 365 [U.S. Government GCC High endpoints](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) or [Office 365 U.S. Government DoD endpoints](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

Además de disfrutar de las características y capacidades de Office 365, las organizaciones se benefician de las siguientes características que son exclusivas de los entornos en la nube del gobierno de Estados Unidos:

-   El contenido de cliente de su organización se separa lógicamente del contenido del cliente en los servicios Office 365 comerciales de Microsoft.
-   El contenido del cliente de la organización se almacena dentro de los Estados Unidos.
-   El acceso al contenido del cliente de la organización está restringido a personal específico de Microsoft.
-   Los entornos de nube gubernamentales cumplen con las certificaciones y acreditaciones necesarias para los clientes del sector público de Estados Unidos.

Nuestro objetivo es ofrecer todas las SharePoint y funcionalidades comerciales a los entornos de nube gubernamentales. Algunas características no están disponibles debido a los requisitos de los clientes de la nube gubernamental. Otras características están llegando a los entornos gubernamentales, pero aún no están disponibles. Consulte las secciones siguientes para obtener información sobre la disponibilidad de características en los entornos de nube gubernamentales.

## <a name="developer-features"></a>Características de desarrollador

No hay diferencias conocidas entre las características de desarrollador para clientes comerciales y las características de desarrollador para los clientes de la nube gubernamental.

- Las conexiones a aplicaciones externas, como orígenes de datos para complementos, se limitan a orígenes que se encuentran dentro de los límites de seguridad del sistema admitidos por el entorno gubernamental.
- Servicios de conectividad empresarial (BCS) es compatible con escenarios de conectividad en los que los orígenes de datos permanecen accesibles dentro del límite de seguridad del servicio en la nube.

Si usa aplicaciones de terceros en sitios, revise las declaraciones de privacidad y cumplimiento proporcionadas por los terceros al evaluar el uso adecuado de estos servicios para su organización. Las aplicaciones y servicios de terceros pueden implicar almacenar, transmitir y procesar los datos de clientes de su organización en sistemas de terceros que están fuera de la nube gubernamental y, por lo tanto, no están cubiertos por sus compromisos de cumplimiento y protección de datos. 

## <a name="it-admin-features"></a>Características de administración de TI

Estas son las diferencias entre las características de administración de TI para clientes comerciales y las características de administración de TI para los clientes de la nube del gobierno.

- Cambiar una dirección de sitio no está disponible para GCC high
- La SharePoint de migración y el Administrador de migración requieren un cambio de configuración. Para obtener información, consulta [SPMT government cloud support](/sharepointmigration/spmt-install-issues#government-cloud-support).
- Mover.io aún no se admite
- Multi-geo no está disponible para todos los clientes de la nube gubernamental

Para obtener información sobre FastTrack migración, [consulta la Office 365 de servicio de US Government](./office-365-us-government.md#data-migrations-performed-by-fasttrack).

## <a name="security-and-compliance-features"></a>Características de seguridad y cumplimiento

No hay diferencias conocidas entre las características de seguridad y cumplimiento para clientes comerciales y las características de seguridad y cumplimiento para los clientes de la nube gubernamental.

Para obtener información sobre las características de seguridad y cumplimiento, vea [el Centro de seguridad & cumplimiento](../office-365-securitycompliance-center.md).

Para obtener información Azure Active Directory características de administración pública, consulte [Azure Government Security + Identity documentation](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory). 

Para obtener información acerca de las características de Azure Information Protection para el gobierno, vea la descripción del servicio [de azure information protection Premium government .](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description) 

Para obtener información sobre SharePoint Syntex características, vea el SharePoint Syntex [descripción del servicio de características.](/office365/servicedescriptions/sharepoint-syntex-service-description/sharepoint-syntex-features)

## <a name="sites-and-content"></a>Sitios y contenido

Estas son las diferencias entre los sitios y las características de contenido para clientes comerciales y los sitios y las características de contenido para los clientes de la nube gubernamental:

- Los elementos web que dependen de las conexiones a servicios de Internet, como los elementos web Amazon Kindle, mapas de Bing, Twitter y YouTube, no funcionarán como se esperaba.
- La biblioteca de activos de la organización no está disponible
- Graph funcionalidad de SharePoint Online para GCC High está deshabilitada actualmente. Cualquier servicio que se base en Microsoft Graph puede que no esté disponible actualmente
- Las características que dependen de las conexiones a servicios de Internet, como la pestaña imágenes de stock, no funcionarán como se esperaba
- Las notificaciones de actividad de archivo y sitio no están disponibles
- El elemento web de noticias solo extraerá noticias del sitio actual. Las noticias de sitios seleccionados o paquetes acumulativos de noticias centrales de sitios asociados no están disponibles para clientes GCC high y doD

## <a name="search-features"></a>Características de búsqueda

Estas son las diferencias entre las características de búsqueda para clientes comerciales y las características de búsqueda para los clientes de la nube gubernamental:

- Búsqueda de Microsoft no está disponible en GCC.

## <a name="sharing-and-sync"></a>Uso compartido y sincronización

Para obtener información sobre las diferencias de características entre la nube comercial y los entornos de nube gubernamentales, vea [Uso compartido de archivos.](./gcc-high-and-dod.md#file-sharing)

## <a name="plan-for-governance"></a>Plan for governance

El paso a la nube ofrece experiencias transformadoras con controles de administración integrados. Determine los requisitos de gobierno y cómo puede cumplirlos. Vaya a [Plan for governance to transform teamwork with Microsoft 365](https://resources.techcommunity.microsoft.com/teamwork-governance/) para obtener más información. Encontrará instrucciones sobre grupos de Office 365, SharePoint, Teams y más.

## <a name="deploy-sharepoint-for-collaboration"></a>Implementar SharePoint para colaboración

Después de configurar la organización en la nube del gobierno de Microsoft US, siga la ruta de implementación recomendada que se describe en el centro de recursos [SharePoint adopción.](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/) Asegúrese de interactuar con sus campeones de adopción y administración de cambios.
También puede trabajar con [FastTrack](https://www.microsoft.com/fasttrack) o el partner elegido para realizar el servicio a los usuarios.
Visite el [Centro de confianza](https://www.microsoft.com/trust-center) de Microsoft para obtener más información sobre cómo Microsoft aborda la seguridad, la privacidad y el cumplimiento, principios básicos de cómo habilitamos a las organizaciones para que sirvan a sus clientes.

## <a name="configuring-sharepoint-hybrid-configuration-wizard-support-for-all-government-cloud-customers"></a>Configuración de la SharePoint de configuración híbrida para todos los clientes de la nube gubernamental

El SharePoint de configuración híbrida contiene compatibilidad con SharePoint características híbridas con entornos de SPO especiales.

Debe editar el valor de un parámetro relacionado con el entorno en un archivo **.config** para que las SharePoint híbridas estén disponibles para ese entorno. Consulte [Edición del archivo de configuración](#editing-configuration-file).

> [!NOTE]
> Para obtener información sobre los entornos de SPO especiales para los que SharePoint características híbridas ofrecen compatibilidad, vea [Supported Environments](#supported-environments).

## <a name="editing-configuration-file"></a>Editar archivo de configuración

1. Instale o actualice el Asistente SharePoint de configuración híbrida.
2. Vaya a la carpeta en la que está instalado SharePoint de configuración híbrida. Por ejemplo: `%LOCALAPPDATA%\Apps\HybridSP\HybridSP`
3. Inicie el **archivomicrosoft.online.cse.hybridsp.common.dll.config** en un editor de texto como Bloc de notas.
El contenido de este archivo se muestra en la siguiente captura de pantalla:

:::image type="content" source="../../media/content.png" alt-text="El contenido del archivo de configuración":::

4. Modifique el valor del `SPOEnvironmentType` parámetro.
5. Guarde los cambios en el **microsoft.online.cse.hybridsp.common.dll.config** archivo.
6. Vuelva a iniciar el Asistente SharePoint configuración híbrida.
   La configuración se aplica y las SharePoint híbridas están disponibles en el entorno de SPO configurado.

## <a name="supported-environments"></a>Entornos compatibles

SharePoint características híbridas admiten los siguientes entornos de SPO:

- Public
- PPE
- GCC
- GccHigh
- DoD
- Personalizado

Si un cliente establece el valor en Custom , , y las claves se usan para establecer esos puntos de conexión `SPOEnvironmentType` para ese entorno  `AuthorityEndPoint` `AADGraphEndPoint` `MSGraphEndPoint` SPO personalizado.

Si el valor se establece en cualquier valor que no sea Custom , las claves , y se omiten y el Asistente para configuración híbrida de SharePoint usa valores codificados de forma rígida adecuados para esos tipos de entorno `SPOEnvironmentType`  `AuthorityEndPoint` de `AADGraphEndPoint` `MSGraphEndPoint` SPO.
