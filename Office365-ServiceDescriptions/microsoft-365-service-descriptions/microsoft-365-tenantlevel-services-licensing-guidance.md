---
title: Microsoft 365 información sobre licencias de servicios de nivel de inquilino
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: En este artículo se proporcionan instrucciones de licencia para los servicios a nivel de inquilino de Microsoft 365 para evitar posibles interrupciones del servicio debido al acceso sin licencia.
ms.openlocfilehash: 3c77928869c3735a5bad14eafeac0a248455f5e0
ms.sourcegitcommit: 61b4778f15b4b793b41033c4692e632a0351a0e3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/06/2019
ms.locfileid: "36206870"
---
# <a name="microsoft-365-tenant-level-services-licensing-guidance"></a>Microsoft 365 información sobre licencias de servicios de nivel de inquilino

Para los fines de este artículo, un servicio a nivel de inquilino es un servicio en&mdash;línea que, cuando se compra para cualquier usuario del inquilino (independiente o como parte de los planes de Office&mdash;365 o Microsoft 365), se activa en parte o en su totalidad para todos los usuarios del espacio empresarial. Aunque es posible que algunos usuarios sin licencia puedan obtener acceso al servicio, se necesita una licencia para cualquier usuario con el que pretenda beneficiarse del servicio.

> [!NOTE]
> Algunos servicios de inquilinos actualmente no pueden limitar las ventajas a usuarios específicos. Se deben realizar esfuerzos para limitar las ventajas del servicio a los usuarios con licencia. Esto ayudará a evitar posibles interrupciones en el servicio de su organización una vez que las capacidades de destino estén disponibles.

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

La protección de identidad de Azure Active Directory (AADIP) es una característica del plan P2 de Azure Active Directory Premium que le permite detectar posibles vulnerabilidades que afectan a las identidades de su organización, configurar las respuestas automáticas para que se detecten sospechosos acciones relacionadas con las identidades de la organización e investigue los incidentes sospechosos y tome las medidas adecuadas para resolverlos.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, la seguridad de Microsoft 365 E5/A5/G5 y Azure Active Directory Premium plan 2 pueden beneficiarse de AADIP.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los analistas de SecOps y los profesionales de la seguridad se benefician de tener vistas consolidadas de los usuarios marcados y de los eventos de riesgo basados en algoritmos de aprendizaje de la máquina. Los usuarios finales se benefician de la protección automática que se proporciona a través del acceso condicional basado en riesgos y la mejora de la seguridad proporcionada por la actuación en vulnerabilidades.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características de AADIP están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre la configuración de AADIP, consulte [Enabling Azure Active Directory Identity Protection](https://docs.microsoft.com/azure/active-directory/identity-protection/enable).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los administradores pueden establecer el ámbito AADIP mediante la asignación de directivas de riesgo que definen el nivel de restablecimiento de contraseña y permiten el acceso solo a los usuarios con licencia. Para obtener instrucciones sobre cómo establecer el ámbito de las implementaciones de AADIP, vea [Configure The Sign-in Risk Policy](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy).

## <a name="azure-advanced-threat-protection"></a>Protección contra amenazas avanzada de Azure

La protección contra amenazas avanzada de Azure (ATP) es un servicio en la nube que ayuda a proteger los entornos híbridos empresariales de varios tipos de ataques avanzados y amenazas de Insider específicos.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, la seguridad de Microsoft 365 E5/A5/G5 y la protección contra amenazas avanzada de Azure para los usuarios pueden beneficiarse de ATP de Azure.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los analistas de SecOp y los profesionales de la seguridad se benefician de la capacidad de Azure ATP para detectar e investigar amenazas avanzadas, identidades en peligro y acciones insiderias malintencionadas. Los usuarios finales aprovechan los datos supervisados por ATP de Azure.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características de ATP de Azure están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar ATP de Azure, consulte [Create Your Azure ATP Instance](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Microsoft no se compromete a ofrecer capacidades de detección de amenazas a los usuarios que no tienen licencia. Con el tiempo, las comprobaciones de licencia o las herramientas de destino se agregarán a Azure ATP para garantizar que la funcionalidad de Azure ATP solo se aplica a los usuarios con licencia.

## <a name="azure-information-protection"></a>Azure Information Protection

Azure Information Protection (AIP) ayuda a las organizaciones a descubrir, clasificar, etiquetar y proteger los documentos y mensajes confidenciales. Los administradores pueden definir reglas y condiciones para aplicar etiquetas automáticamente, los usuarios pueden aplicar etiquetas manualmente o se puede usar&mdash;una combinación de las dos en la que los usuarios tengan recomendaciones para aplicar etiquetas.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Microsoft 365 F1, Microsoft 365 Business, Microsoft 365 E3/a3/G3 y el plan 1 de AIP pueden beneficiarse del plan de AIP 1. Los usuarios con licencia de Microsoft 365 E5/A5/G5, el cumplimiento de Microsoft 365 E5/A5/G5 y el plan 2 de AIP pueden beneficiarse del plan de AIP 2.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

La característica de examen de AIP clasifica, etiqueta y protege automáticamente los archivos que residen en repositorios de archivos locales.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características de AIP están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar directivas de AIP para usuarios con licencia, consulte [Activating Azure Rights Management](https://docs.microsoft.com/azure/information-protection/activate-service).
### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Las directivas de características de AIP (excepto la característica de escáner) se pueden limitar a grupos o usuarios específicos; los registros se pueden editar para evitar que los usuarios sin licencia ejecuten las características de etiquetado o clasificación de AIP. Para obtener instrucciones sobre cómo asignar el ámbito de las implementaciones de AIP, vea [configuración de la Directiva de Azure Information Protection](https://docs.microsoft.com/azure/information-protection/configure-policy).

Para la característica de analizador de AIP, Microsoft no se compromete a ofrecer capacidades de clasificación, etiquetado o protección de archivos a los usuarios que no tienen licencia. Con el tiempo, las comprobaciones de licencia o las herramientas de destino se agregarán a AIP para asegurarse de que la característica de escáner sea asignable a los usuarios con licencia.

## <a name="office-365-advanced-threat-protection"></a>Protección contra amenazas avanzada de Office 365

La protección contra amenazas avanzada (ATP) ayuda a proteger a las organizaciones contra ataques sofisticados, como suplantación de identidad y malware de día cero. También proporciona información útil al correlacionar señales de una amplia gama de datos para ayudar a identificar, priorizar y proporcionar recomendaciones sobre cómo resolver las posibles amenazas.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Usuarios con licencia de Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, seguridad de Microsoft 365 E5/A5/G5, Microsoft 365 Business y Office 365 los planes de ATP 1 y 2 pueden beneficiarse de ATP.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

ATP protege a los usuarios de ataques sofisticados, como suplantación de identidad y malware de día cero. Para obtener una lista completa de los servicios proporcionados en el plan 1 y el plan 2, consulte [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection).

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características de ATP están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar las directivas de ATP para los usuarios con licencia, consulte [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Para el ámbito ATP, siga las directivas de implementación de vínculos seguros y datos adjuntos seguros:

  - Para obtener información sobre cómo configurar vínculos seguros para usuarios con licencia, consulte [configurar las directivas de vínculos seguros de Office 365 ATP](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-links-policies).

  - Para obtener información sobre cómo configurar datos adjuntos seguros para usuarios con licencia, consulte [configurar las directivas de datos adjuntos seguros de Office 365 ATP](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-attachments-policies).

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) es un subconjunto de Microsoft Cloud App Security, con características limitadas a Office 365 y sin seguridad adicional para aplicaciones en la nube de terceros y servicios de IaaS.

OCAS proporciona a las organizaciones visibilidad de sus aplicaciones y servicios en la nube de productividad, proporciona análisis sofisticados para identificar y combatir las amenazas de la nube&mdash;, y les permite controlar la forma en que los datos viajan en Office 365.

Para comparar las características, consulte [diferencias entre Microsoft Cloud App Security y Office 365 Cloud App Security](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365).

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Office 365 E5/A5/G5 pueden beneficiarse de OCAS.

Para obtener más información, vea la hoja de datos de [licencias de Microsoft Cloud App Security](http://www.aka.ms/mcaslicensing).

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

OCAS detecta el sombreado, proporciona protección contra amenazas en Office 365 y puede controlar qué aplicaciones tienen permiso de acceso a los datos de Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características de OCAS están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial.

Para obtener información sobre cómo configurar el servicio, consulte [Basic Setup for Cloud App Security](https://docs.microsoft.com/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los administradores pueden establecer el ámbito de las implementaciones de OCAS para exigir el acceso a determinadas aplicaciones y limitar los grupos de usuarios supervisados por la seguridad de aplicaciones en la nube de Office 365. Para obtener más información, vea [implementación con ámbito](https://docs.microsoft.com/cloud-app-security/scoped-deployment).

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) es una solución de agente de seguridad de acceso a la nube (CASB) que ofrece a las organizaciones visibilidad de sus aplicaciones y servicios en la nube, ofrece análisis sofisticados para identificar y combatir las amenazas de la cibernéticos, y les permite controlar la forma en que los datos viaja&mdash;en cualquier aplicación de la nube.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5 y la seguridad de Microsoft 365 E5/A5/G5 pueden beneficiarse de MCAS.

Los usuarios con licencia de Azure AD P1 pueden beneficiarse de las capacidades de detección de MCAS.

Para beneficiarse de las capacidades de control de la [aplicación de acceso condicional](https://docs.microsoft.com/cloud-app-security/proxy-intro-aad) en MCAS, los usuarios también deben tener una licencia para Azure Active Directory P1, que se incluye en Enterprise Mobility + Security E3/a3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/ A3/G3, Microsoft 365 E5/A5/G5 y seguridad de Microsoft 365 E5/A5/G5.

Para beneficiarse de la [etiquetación automática](https://docs.microsoft.com/cloud-app-security/data-protection-policies), los usuarios deben tener una licencia para Azure Information Protection P2, que se incluye en Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5 y cumplimiento de Microsoft 365 E5/A5/G5.

Para obtener más información, vea la hoja de datos de [licencias de Microsoft Cloud App Security](http://www.aka.ms/mcaslicensing).

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

MCAS descubre y evalúa la sombra, proporciona protección contra amenazas en aplicaciones en la nube de primer y terceras partes y protege la información en aplicaciones en la nube de primera y tercera empresa.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características de MCAS están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial.

Para obtener información sobre cómo configurar las directivas de Microsoft Cloud App Security para los usuarios con licencia, consulte [Microsoft Cloud App Security Overview](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los administradores pueden asignar el ámbito de las implementaciones de MCAS a los usuarios con licencia mediante las funciones de implementación con ámbito disponibles en el servicio. Para obtener más información, vea [implementación con ámbito](https://docs.microsoft.com/cloud-app-security/scoped-deployment).

## <a name="office-365-advanced-data-governance"></a>Gobierno de datos avanzado de Office 365

El gobierno de datos avanzado (ADG) ayuda a las organizaciones a cumplir los requisitos de control de la información con políticas para habilitar la retención y la eliminación. ADG permite a las organizaciones contenido de etiqueta automática en función de la información confidencial escriba y aplique directivas de gobierno a ese contenido.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, el cumplimiento de Microsoft 365 E5/A5/G5 y el cumplimiento avanzado de Office 365 pueden beneficiarse de ADG.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

ADG permite a los usuarios aplicar etiquetas a datos específicos para mantener directivas específicas, etiquetar automáticamente el contenido como un registro y administrar el proceso de registros completos de declaración a eliminación.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características de ADG están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información acerca de la configuración de ADG para aplicar etiquetas y directivas automáticas para los usuarios con licencia, consulte [Overview of Retention](https://docs.microsoft.com/office365/securitycompliance/labels)Labels.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Las directivas de retención de ADG se pueden aplicar a usuarios con licencia en ubicaciones específicas (sitios de grupo, sitios de grupo, etc.) a través de la clasificación automática. Para obtener instrucciones sobre cómo aplicar directivas de retención de ADG, vea [aplicar una directiva de retención a toda la organización o a ubicaciones específicas](https://docs.microsoft.com/office365/securitycompliance/retention-policies#applying-a-retention-policy-to-an-entire-organization-or-specific-locations).

## <a name="office-365-advanced-ediscovery"></a>eDiscovery avanzado de Office 365

Office 365 Advanced eDiscovery proporciona soluciones de investigación y exhibición de documentos electrónicos para departamentos de ti y legales dentro de las empresas para identificar, recopilar, preservar, reducir y revisar el contenido relacionado con una investigación o litigio antes de la exportación desde el Office 365 System.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, el cumplimiento de Microsoft 365 E5/A5/G5 y el cumplimiento avanzado de Office 365 pueden beneficiarse de la exhibición avanzada de documentos electrónicos.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Un usuario se beneficia de la exhibición avanzada de documentos electrónicos cuando el usuario se selecciona como un custodio de datos (una persona con control administrativo de un documento o un archivo electrónico) para un caso.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características avanzadas de eDiscovery se habilitan en el nivel de inquilino para todos los usuarios del espacio empresarial cuando los administradores asignan permisos de exhibición de documentos electrónicos en el centro de seguridad & cumplimiento.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

los administradores de exhibición de documentos electrónicos pueden seleccionar usuarios específicos como custodios de datos para un caso mediante la herramienta de administración de custodios integrada en eDiscovery avanzado, tal como se describe en [Agregar custodios a un caso de exhibición avanzada](https://docs.microsoft.com/office365/securitycompliance/compliance20/add-custodians-to-case)de documentos electrónicos.

## <a name="office-365-customer-key"></a>Clave de cliente de Office 365

Con la clave de cliente, se controlan las claves de cifrado de la organización y se configura Office 365 para usarlas y cifrar los datos en reposo en los centros de datos de Microsoft. Es decir, la clave de cliente le permite agregar una capa de cifrado que le pertenece con sus propias claves. Los datos en reposo incluyen datos de Exchange Online y Skype empresarial que se almacenan en buzones de correo y archivos de SharePoint Online y OneDrive para la empresa.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, el cumplimiento de Microsoft 365 E5/A5/G5 y el cumplimiento avanzado de Office 365 pueden beneficiarse de la clave de cliente. Para obtener todas las ventajas de la clave de cliente, también debe tener una suscripción de Azure Key Vault.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de la clave de cliente al tener sus datos en reposo cifrados en el nivel de aplicación mediante claves de cifrado que se proporcionan, controlan y administran desde su propia organización.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

Se pueden habilitar las claves de cifrado de clave de cliente de Office 365 para todos los datos almacenados en los buzones de correo de Exchange Online y Skype empresarial, y los archivos de SharePoint Online y OneDrive para la empresa. Para obtener información sobre cómo configurar la clave de cliente de Office 365 para cifrar los datos en reposo, vea [controlar los datos en Office 365 mediante la clave de cliente](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Para asignar claves de cifrado a datos dentro de un inquilino de Office 365 o Microsoft 365 para usuarios con licencia, siga las directivas de implementación de claves de cifrado de clave de cliente:

  - Para SharePoint Online, los archivos de uno o varios sitios pueden cifrarse con la clave de cliente, tal como se describe aquí: configuración de la [clave de cliente de SharePoint Online y OneDrive para la empresa](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-sharepoint-online-and-onedrive-for-business).

  - Para Exchange Online y Skype empresarial online, los buzones pueden cifrarse con la clave de cliente, tal y como se describe aquí: configuración de la [clave de cliente para Exchange Online y Skype empresarial](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-exchange-online-and-skype-for-business)

## <a name="office-365-customer-lockbox"></a>Caja de seguridad del cliente de Office 365

La caja de caja del cliente proporciona una capa de control adicional al ofrecer a los clientes la capacidad de otorgar autorización de acceso explícito para las operaciones de servicio. Al demostrar que se han implementado los procedimientos para la autorización explícita de acceso a datos, la caja de seguridad del cliente también puede ayudar a las organizaciones a cumplir ciertas obligaciones de cumplimiento, como HIPAA y FEDRAMP.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, el cumplimiento de Microsoft 365 E5/A5/G5 y el cumplimiento avanzado de Office 365 pueden beneficiarse de las cajas de caja de clientes.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de la caja de garantía del cliente para garantizar que nadie en Microsoft pueda acceder a su contenido para realizar una operación de servicio sin la aprobación explícita del cliente. La caja de caja del cliente pone al cliente en el flujo de trabajo de aprobación para las solicitudes de acceso a su contenido. En ocasiones, los ingenieros de Microsoft están involucrados durante el proceso de soporte para solucionar problemas y solucionar problemas notificados por los clientes. En la mayoría de los casos, los problemas se arreglan mediante amplias herramientas de depuración y telemetría que Microsoft ha implementado para sus servicios. Sin embargo, puede haber casos que requieran que un ingeniero de Microsoft tenga acceso al contenido del cliente para determinar la causa raíz y corregir el problema. La caja de caja del cliente requiere que el ingeniero solicite el acceso del cliente como paso final en el flujo de trabajo de aprobación. Esto proporciona a las organizaciones la opción de aprobar o denegar estas solicitudes, lo que les proporciona el control directo sobre si un ingeniero de Microsoft puede tener acceso a los datos de los usuarios finales de las organizaciones.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

Los administradores pueden activar los controles de caja de caja del cliente en el centro de administración de Microsoft 365. Para obtener más información, consulte [caja de caja del cliente en Office 365](https://docs.microsoft.com/Office365/Admin/manage/customer-lockbox-requests). Cuando la caja de caja de clientes está activada, Microsoft debe obtener la aprobación de la organización antes de tener acceso a cualquiera de sus contenidos.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Microsoft no se compromete a ofrecer solicitudes de aprobación de control de acceso de Lockbox de clientes para usuarios que no tienen licencia. Con el tiempo, las comprobaciones de licencia o las herramientas de destino se agregarán a la caja de caja del cliente para garantizar que los usuarios con licencia puedan asignar la caja de caja del cliente.

## <a name="privileged-access-management-in-office-365"></a>Administración del acceso con privilegios en Office 365

La administración de acceso con privilegios (PAM) proporciona un control de acceso granular sobre las tareas de administración con privilegios en Office 365. Después de habilitar PAM, los usuarios tendrán que solicitar acceso justo a tiempo a través de un flujo de trabajo de aprobación con un ámbito muy limitado y con un límite de tiempo para completar las tareas elevadas y privilegiadas.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, el cumplimiento de Microsoft 365 E5/A5/G5 y el cumplimiento avanzado de Office 365 pueden beneficiarse de PAM.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

La habilitación de PAM permite a las organizaciones operar con cero derechos de posición. Los usuarios se benefician de la capa agregada de defensa contra las vulnerabilidades que se derivan de un acceso administrativo permanente que proporciona un acceso libre a sus datos.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características de PAM se habilitan en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar directivas de PAM, consulte [Configuring privileged Access Management in Office 365](https://docs.microsoft.com/office365/securitycompliance/privileged-access-management-configuration).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los clientes pueden administrar PAM por usuario mediante directivas de acceso y de grupo de aprobador, que se pueden aplicar a los usuarios con licencia. Para obtener más información, vea [Administración del acceso con privilegios en Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Prevención de pérdida de datos para Exchange Online, SharePoint Online y OneDrive para la empresa

Con la prevención de pérdida de datos (DLP) para Exchange Online, SharePoint Online y OneDrive para la empresa, las organizaciones pueden identificar, supervisar y proteger automáticamente la información confidencial en los correos electrónicos y archivos (incluidos los archivos almacenados en el archivo de Microsoft Teams). repositorios).

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Office 365 E3/a3/G3, Microsoft 365 Business, Microsoft 365 E3/a3/G3 y la prevención de pérdida de datos de Office 365 pueden beneficiarse de DLP para Exchange Online, SharePoint Online y OneDrive para la empresa.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de DLP para Exchange Online, SharePoint Online y OneDrive para la empresa cuando sus archivos y mensajes de correo electrónico se inspecciona para obtener información confidencial, tal como se ha configurado en la Directiva DLP de la organización.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, los mensajes de correo electrónico de Exchange Online, los sitios de SharePoint y las cuentas de OneDrive son *ubicaciones (cargas de trabajo) habilitadas* para estas características de DLP para todos los usuarios del espacio empresarial. Para obtener más información sobre el uso de directivas de DLP, vea [información general sobre prevención de pérdida de datos](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los administradores pueden personalizar las ubicaciones (cargas de trabajo), los usuarios incluidos y los usuarios excluidos en el centro de seguridad & cumplimiento de Office 365, en**ubicaciones**de **prevención** > de pérdida de datos.

## <a name="data-loss-prevention-for-teams-chat-and-channel-messages"></a>Prevención de pérdida de datos para los mensajes de chat y canales de Microsoft Teams

Con la prevención de pérdida de datos (DLP) de los mensajes de chat y de canal de Microsoft Teams, las organizaciones pueden bloquear los chats y los mensajes de canal que contienen información confidencial, como información financiera, información personal de identificación, información relacionada con el estado o otra información confidencial.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, el cumplimiento de Microsoft 365 E5/A5/G5 y el cumplimiento avanzado de Office 365 pueden beneficiarse de DLP para los mensajes de chat y de canal de Microsoft Teams.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los remitentes obtienen beneficios al tener información confidencial en su chat saliente y los mensajes de canal inspeccionados para la información confidencial, tal y como se ha configurado en la Directiva DLP de la organización.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, los mensajes de chat y de canal de Microsoft son una *Ubicación (carga de trabajo) habilitada* para estas características DLP para todos los usuarios dentro del espacio empresarial. Para obtener más información sobre el uso de directivas de DLP, vea [información general sobre prevención de pérdida de datos](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los administradores pueden personalizar las ubicaciones (cargas de trabajo), los usuarios incluidos y los usuarios excluidos en el centro de seguridad & cumplimiento de Office 365, en**ubicaciones**de **prevención** > de pérdida de datos.

## <a name="information-barriers"></a>Barreras de la información

Las barreras de información son directivas que un administrador puede configurar para evitar que los usuarios o grupos se comuniquen entre sí. Esto es útil si, por ejemplo, un departamento está controlando información que no debe compartirse con otros departamentos, o bien es necesario evitar que un grupo se comunique con los contactos externos. Las directivas de barrera de información también evitan búsquedas y detección. Esto significa que si intenta comunicarse con alguien con quien no debe comunicarse, no encontrará a ese usuario en el selector de personas.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, el cumplimiento de Microsoft 365 E5/A5/G5 y el cumplimiento avanzado de Office 365 pueden beneficiarse de las barreras de información.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de las capacidades de cumplimiento avanzadas de las barreras de la información cuando están restringidas de la comunicación con otros usuarios. Por ejemplo:

| Escenario                                                                                                                                                                                                              | ¿Quién necesita una licencia? |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| Dos grupos (Grupo 1 y grupo 2) no pueden comunicarse entre sí (es decir, los usuarios de grupo 1 tienen restringida la comunicación con los usuarios del grupo 2 y los usuarios del grupo 2 están restringidos para comunicarse con los usuarios del grupo 1). | Usuarios en el grupo 1 y el grupo 2                    |
| Los usuarios del grupo 1 están restringidos para comunicarse con el resto de la compañía.                                                                                                                                       | Solo usuarios del grupo 1                                |
| El resto de la compañía tiene restringida la comunicación con el grupo 1.                                                                                                                                                 | Todos los usuarios excepto los del grupo 1                    |
| Los usuarios de grupo 1 tienen restricciones para comunicarse con los usuarios del grupo 2, pero los usuarios de grupo 2 pueden comunicarse con los usuarios del grupo 1.                                                                                              | Solo usuarios del grupo 1                                |

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

Los administradores crean y administran directivas de barrera de información mediante cmdlets de PowerShell en el centro de seguridad & cumplimiento. Los administradores deben tener asignado el rol de administrador global de Microsoft 365 Enterprise, administrador global de Office 365 o administrador de cumplimiento para crear una directiva de barrera de información. De forma predeterminada, estas directivas se aplican a todos los usuarios del espacio empresarial. Para obtener más información sobre las barreras de información, consulte [barreras de la información en Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los administradores pueden personalizar las ubicaciones (cargas de trabajo), los usuarios incluidos y los usuarios excluidos en el centro de seguridad & cumplimiento de Office 365. Por ejemplo, si todos los usuarios tienen licencia para Office 365 E3 y ninguno tiene licencia para Office 365 Advanced Compliance/E5, no necesitará crear ninguna directiva de barrera de información para la organización. Para obtener más información, consulte [barreras de la información en Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).

## <a name="office-365-message-encryption"></a>Cifrado de mensajes de Office 365

El cifrado de mensajes de Office 365 (OME) es un servicio basado en Azure Rights Management (Azure RMS) que permite enviar correo electrónico cifrado a otras personas dentro o fuera de la organización, independientemente de la dirección de correo electrónico de destino (Gmail, Yahoo! Mail, Outlook.com, etc.).

Para ver los mensajes cifrados, los destinatarios pueden obtener un código de acceso único, iniciar sesión con una cuenta de Microsoft, o iniciar sesión con una cuenta profesional o educativa asociada a Office 365. Los destinatarios también pueden enviar respuestas cifradas. No necesitan una suscripción de Office 365 para ver mensajes cifrados ni enviar respuestas cifradas.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Office 365 E3/a3/G3, Microsoft 365 E3/a3/G3 y el plan 1 de Azure Information Protection pueden beneficiarse de la codificación de mensajes de Office 365.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los remitentes de mensajes se benefician del control agregado sobre los mensajes de correo electrónico confidenciales proporcionados por el cifrado de mensajes de Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

Los administradores crean y administran directivas de cifrado de mensajes de Office 365 en el centro de administración de Exchange en**reglas**de **flujo** > de correo. De forma predeterminada, estas reglas se aplican a todos los usuarios del espacio empresarial. Para obtener más información acerca de la configuración de nuevas capacidades de cifrado de mensajes de Office 365, vea [set up New office 365 Message Encryption Capabilities](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los administradores deben aplicar reglas de flujo de correo para el cifrado de mensajes de Office 365 solo a usuarios con licencia. Para obtener más información acerca de la definición de reglas de flujo de correo, consulte [definir reglas de flujo de correo para cifrar mensajes de correo electrónico en Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).


## <a name="office-365-advanced-message-encryption"></a>Cifrado avanzado de mensajes de Office 365

El cifrado de mensajes avanzado ayuda a los clientes a cumplir las obligaciones de cumplimiento que necesitan controles más flexibles sobre los destinatarios externos y su acceso a los correos electrónicos cifrados. Con el cifrado de mensajes avanzado, los administradores pueden controlar los mensajes de correo electrónico confidenciales que se comparten fuera de la organización mediante directivas automáticas que pueden detectar los tipos de información confidencial (por ejemplo, información de identificación personal, o identificadores financieros o de salud) o pueden usar palabras clave para mejorar la protección mediante la aplicación de plantillas de correo electrónico personalizadas y la expiración del acceso a correos electrónicos cifrados a través de un portal web seguro. Además, los administradores pueden controlar más los correos electrónicos cifrados a los que se accede externamente a través de un portal web seguro al revocar el acceso en cualquier momento.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, el cumplimiento de Microsoft 365 E5/A5/G5 y el cumplimiento avanzado de Office 365 pueden beneficiarse del cifrado avanzado de mensajes.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los remitentes de mensajes se benefician del control agregado sobre los correos electrónicos confidenciales proporcionados por el cifrado avanzado de mensajes.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

Los administradores crean y administran directivas de cifrado de mensajes avanzadas en el centro de administración de Exchange en reglas de flujo de correo. De forma predeterminada, estas reglas se aplican a todos los usuarios del inquilino. Para obtener más información acerca de la configuración de nuevas capacidades de cifrado de mensajes, vea [set up New Office 365 Message Encryption Capabilities](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los administradores deben aplicar reglas de flujo de correo para el cifrado de mensajes avanzado solo a los usuarios con licencia. Para obtener más información acerca de la definición de reglas de flujo de correo, consulte [definir reglas de flujo de correo para cifrar mensajes de correo electrónico en Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="supervision-policies"></a>Directivas de supervisión

Las directivas de supervisión en Office 365 permiten capturar comunicaciones de los empleados para que las examinen los revisores designados. Puede definir directivas específicas que capturen el correo electrónico interno y externo, Microsoft Teams o las comunicaciones de terceros de la organización. A continuación, los revisores pueden examinar los mensajes para asegurarse de que cumplen con los estándares de mensajes de la organización y los resuelven con el tipo de clasificación.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, el cumplimiento de Microsoft 365 E5/A5/G5 y el cumplimiento avanzado de Office 365 pueden beneficiarse de las directivas de supervisión.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician del servicio al supervisar sus comunicaciones mediante directivas de supervisión.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

Los administradores crean directivas de supervisión en el centro de seguridad & cumplimiento. Estas directivas definen qué comunicaciones y usuarios están sujetos a revisión en la organización, definen las condiciones personalizadas que deben cumplir las comunicaciones y especifican quién debe realizar revisiones.
 
### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los administradores eligen grupos o usuarios específicos para incluirlos en una directiva de supervisión. Al elegir un grupo, también pueden seleccionar usuarios específicos del grupo para excluirlos de la Directiva de supervisión. Para obtener más información acerca de las directivas de supervisión, consulte [directivas de supervisión en Office 365](https://docs.microsoft.com/office365/SecurityCompliance/supervision-policies).
