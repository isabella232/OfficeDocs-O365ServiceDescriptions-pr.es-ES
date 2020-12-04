---
title: Guía de licencias de Microsoft 365 para el cumplimiento de & de seguridad
ms.author: v-trscho
author: vtrscho
audience: ITPro
ms.topic: reference
ms.date: 7/13/2020
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: En este artículo se proporcionan instrucciones de licencia para el cumplimiento de Microsoft 365 para ayudar a evitar posibles interrupciones del servicio debido al acceso sin licencia.
ms.openlocfilehash: e2c5a7f9f7c3e5a44f48efa43f239f43590b6c2c
ms.sourcegitcommit: 04f9191b177e714a8dbdd50e7a891ff295483dbe
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/03/2020
ms.locfileid: "49566672"
---
# <a name="microsoft-365-licensing-guidance-for-security--compliance"></a>Guía de licencias de Microsoft 365 para el cumplimiento de & de seguridad

Para los fines de este artículo, un servicio a nivel de inquilino es un servicio en línea que, &mdash; cuando se compra para cualquier usuario del inquilino (independiente o como parte de los planes de Office 365 o Microsoft 365), &mdash; se activa en parte o en su totalidad para todos los usuarios del espacio empresarial. Aunque es posible que algunos usuarios sin licencia puedan obtener acceso al servicio, se necesita una licencia para cualquier usuario con el que pretenda beneficiarse del servicio.

> [!NOTE]
> Algunos servicios de inquilinos actualmente no pueden limitar las ventajas a usuarios específicos. Se deben realizar esfuerzos para limitar las ventajas del servicio a los usuarios con licencia. Esto ayudará a evitar posibles interrupciones en el servicio de su organización una vez que las capacidades de destino estén disponibles.

Para ver las opciones para conceder licencias a los usuarios con el fin de beneficiarse de las características de cumplimiento de Microsoft 365 a partir del 1 de abril de 2020, descargue la comparación detallada de licencias de cumplimiento de Microsoft 365. [(Pdf)](https://www.microsoft.com/download/details.aspx?id=102270)  |  [(Excel)](https://www.microsoft.com/download/details.aspx?id=102287)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

La protección de identidad de Azure Active Directory es una característica del plan P2 de Azure Active Directory Premium que le permite detectar posibles vulnerabilidades que afectan a las identidades de su organización, configurar respuestas automáticas para detectar acciones sospechosas que estén relacionadas con las identidades de su organización e investigar los incidentes sospechosos y tomar las medidas adecuadas para resolverlos.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los analistas de SecOps y los profesionales de la seguridad se benefician de tener vistas consolidadas de los usuarios marcados y de los eventos de riesgo basados en algoritmos de aprendizaje de la máquina. Los usuarios finales se benefician de la protección automática que se proporciona a través del acceso condicional basado en riesgos y la mejora de la seguridad proporcionada por la actuación en vulnerabilidades.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

Los clientes con licencias de E1 y E3 solo podrán tener acceso a la evaluación de línea base de protección de datos predeterminada. Los clientes con licencias de Office 365 E5/A5 y Microsoft 365 E5/A5 (compatibilidad, protección de información & gobernanza y SKU de eDiscovery y de auditoría incluidos) podrán acceder a la línea base de protección de datos, RGPD, NIST 800-53 e ISO 27001 de evaluaciones de salida de caja. La característica de evaluación personalizada y las evaluaciones Premium están reservadas para los clientes de Office 365 E5/A5 y Microsoft 365 E5/A5. Las evaluaciones Premium estarán disponibles para su compra durante la primera mitad de 2021 a través de VL, CSP y WebDirect. 

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características de Azure AD Identity Protection están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información acerca de Azure AD Identity Protection, vea [¿Qué es Azure Active Directory Identity Protection?](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los administradores pueden definir el ámbito de la protección de identidad de Azure AD mediante la asignación de directivas de riesgo que definen el nivel de restablecimiento de contraseña y permiten el acceso solo a los usuarios con licencia. Para obtener instrucciones sobre cómo establecer el ámbito de las implementaciones de Azure AD Identity Protection, vea [Configure The Sign-in Risk Policy](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy).

## <a name="microsoft-defender-for-identity"></a>Microsoft defender para identidad

Microsoft defender for Identity es un servicio en la nube que ayuda a proteger entornos híbridos empresariales de varios tipos de ataques cibernéticos avanzados y amenazas internas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los analistas de SecOp y los profesionales de la seguridad se benefician de la capacidad de Microsoft defender para detectar e investigar las amenazas avanzadas, las identidades en peligro y las acciones de Insider malintencionadas. Los usuarios finales aprovechan los datos supervisados por Microsoft defender para identidades.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security y Microsoft defender para identidades para los usuarios proporcionan los derechos para beneficiarse de Microsoft defender para su identidad.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, Microsoft defender para las características de identidad se habilitan en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar Microsoft defender para identidad, vea [crear su Microsoft defender para una instancia de identidad](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Actualmente, Microsoft defender para los servicios de identidad no es capaz de limitar las capacidades a usuarios específicos. Debe conceder una licencia a todos los usuarios que desee que se beneficien.

## <a name="microsoft-defender-for-office-365"></a>Microsoft defender para Office 365

Defender para Office 365 ayuda a proteger a las organizaciones contra ataques sofisticados, como suplantación de identidad y malware de día cero. Defender para Office 365 también proporciona información útil al correlacionar señales de una amplia gama de datos para ayudar a identificar, priorizar y proporcionar recomendaciones sobre cómo resolver las posibles amenazas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Defender para Office 365 protege a los usuarios de ataques sofisticados, como suplantación de identidad y malware de día cero. Para obtener una lista completa de los servicios que se proporcionan en el plan 1 y el plan 2, consulte [Microsoft defender para Office 365](https://products.office.com/exchange/advance-threat-protection).

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio? 

Microsoft defender para Office 365, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, Microsoft 365 empresa Premium y Microsoft defender para Office 365 los planes 1 y 2 proporcionan los derechos de un usuario para beneficiarse de defender para Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características de Microsoft defender para Office 365 están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar las directivas de defender para Office 365 para usuarios con licencia, consulte [Microsoft defender para office 365](https://docs.microsoft.com/office365/securitycompliance/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Para el ámbito de Microsoft defender para Office 365, siga las directivas de implementación de vínculos seguros y datos adjuntos seguros:

- Para obtener información sobre cómo configurar vínculos seguros para usuarios con licencia, consulte [configurar directivas de vínculos seguros en Microsoft defender para Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-atp-safe-links-policies).

- Para obtener información sobre cómo configurar datos adjuntos seguros para usuarios con licencia, consulte [configurar directivas de datos adjuntos seguros en Microsoft defender para Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-atp-safe-attachments-policies).

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) es un subconjunto de Microsoft Cloud App Security, con características limitadas a Office 365 y sin seguridad adicional para aplicaciones en la nube de terceros y servicios de IaaS.

OCAS proporciona a las organizaciones visibilidad de sus aplicaciones y servicios en la nube de productividad, proporciona análisis sofisticados para identificar y combatir las amenazas de la nube, y les permite controlar la forma en que los datos viajan &mdash; en Office 365.

Para comparar las características, consulte [diferencias entre Microsoft Cloud App Security y Office 365 Cloud App Security](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365).

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

OCAS detecta el sombreado, proporciona protección contra amenazas en Office 365 y puede controlar qué aplicaciones tienen permiso de acceso a los datos.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

Office 365 E5/A5/G5 proporciona los derechos para que un usuario se beneficie de OCAS.
Para obtener más información, vea la hoja de datos de [licencias de Microsoft Cloud App Security](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características de OCAS están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial.

Para obtener información sobre cómo configurar el servicio, consulte [Basic Setup for Cloud App Security](https://docs.microsoft.com/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los administradores pueden establecer el ámbito de las implementaciones de OCAS para exigir el acceso a determinadas aplicaciones y limitar los grupos de usuarios supervisados por la seguridad de aplicaciones en la nube de Office 365. Para obtener más información, vea [implementación con ámbito](https://docs.microsoft.com/cloud-app-security/scoped-deployment).

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) es una solución de agente de seguridad de acceso a la nube (CASB) que ofrece a las organizaciones visibilidad de sus aplicaciones y servicios en la nube, ofrece análisis sofisticados para identificar y combatir las amenazas de la cibernéticos, y les permite controlar la forma en que los datos viajan &mdash; por cualquier aplicación en la nube.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

MCAS descubre y evalúa la sombra, proporciona protección contra amenazas en aplicaciones en la nube de primer y terceras partes y protege la información en aplicaciones en la nube de primera y tercera empresa.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, la seguridad de Microsoft 365 E5/A5/G5, el cumplimiento de Microsoft 365 E5/A5/G5 y la protección de la información y el gobierno de Microsoft 365 proporcionan los derechos para que un usuario se beneficie de MCAS.

Azure AD P1 proporciona los derechos para que un usuario se beneficie de las capacidades de detección de MCAS.

Para beneficiarse de las capacidades de control de la aplicación de acceso condicional en MCAS, los usuarios también deben tener licencia para Azure Active Directory P1, que se incluye en Enterprise Mobility + Security E3/a3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/a3/G3, Microsoft 365 E5/A5/G5 y seguridad de Microsoft 365 E5/A5/G5.

Para beneficiarse de las etiquetas automáticas, los usuarios deben tener una licencia para Azure Information Protection P2, que se incluye en Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, cumplimiento de Microsoft 365 E5/A5/G5 y protección y control de la información de Microsoft 365.

Para obtener más información, vea la hoja de datos de [licencias de Microsoft Cloud App Security](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características de MCAS están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial.

Para obtener información sobre cómo configurar las directivas de Microsoft Cloud App Security para los usuarios con licencia, consulte [Microsoft Cloud App Security Overview](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los administradores pueden asignar el ámbito de las implementaciones de MCAS a los usuarios con licencia mediante las funciones de implementación con ámbito disponibles en el servicio. Para obtener más información, vea [implementación con ámbito](https://docs.microsoft.com/cloud-app-security/scoped-deployment).

## <a name="compliance-manager"></a>Administrador de cumplimiento

Simplificar el cumplimiento y reducir el riesgo con el administrador de cumplimiento. El administrador de cumplimiento ayuda a las organizaciones a cumplir los requisitos de regulaciones, estándares, directivas de la empresa u otros marcos de control deseados.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

A continuación, se indican las ventajas para los usuarios del servicio de administrador de cumplimiento:

- Convierte reglas complicadas, estándares, directivas de la empresa u otros marcos de control deseados en un lenguaje sencillo
- Proporciona acceso a una vasta biblioteca de evaluaciones preparadas y evaluaciones personalizadas para cumplir con las necesidades de cumplimiento exclusivas.
- Asigna controles normativos a acciones de mejora recomendadas
- Proporciona instrucciones paso a paso sobre cómo implementar las soluciones para cumplir los requisitos normativos.
- Ayuda a los usuarios a priorizar acciones que tendrán el mayor impacto en el cumplimiento de su organización al asociar una puntuación a cada acción

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

Los clientes con licencias de Office 365 E5/A5 y Microsoft 365 E5/A5 podrán tener acceso a las evaluaciones de línea base de protección de datos, RGPD, NIST 800-53 e ISO 27001, así como usar la característica de evaluación personalizada. Las evaluaciones Premium estarán disponibles para su compra a los clientes de Office 365 E5/A5 y Microsoft 365 E5/A5 durante la primera mitad de 2021. Estarán disponibles para su compra a través de VL, CSP y WebDirect.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

El administrador de cumplimiento se aprovisiona de forma predeterminada para su espacio empresarial. Los administradores establecen los permisos de usuario y asignan roles para que los usuarios que no sean administradores de la organización puedan empezar a usar el administrador de cumplimiento. Para obtener más información, vea Introducción [al administrador de cumplimiento: set User Permissions and Assign roles](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

El acceso al administrador de cumplimiento se controla mediante la configuración de los permisos de usuario y la asignación de roles. Para obtener más información, vea Introducción [al administrador de cumplimiento: set User Permissions and Assign roles](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles).

## <a name="microsoft-defender-for-endpoint"></a>Microsoft defender para extremo

Microsoft defender for Endpoint es una solución de seguridad de extremo que incluye la evaluación y la administración de vulnerabilidades basadas en riesgos; capacidades de reducción de superficie de ataques; protección de próxima generación basada en el comportamiento y en la nube; detección y respuesta de extremos (EDR); investigación y corrección automáticas; y servicios de búsqueda administrada. Consulte la página [de Microsoft defender for Endpoint](https://www.microsoft.com/microsoft-365/windows/microsoft-defender-atp?rtc=1) para obtener más información.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Windows 10 Enterprise E5, Windows 10 Education A5, Microsoft 365 E5 (M365 E5) que incluyan Windows 10 Enterprise E5, Microsoft 365 E5 Security, Microsoft 365 A5 (M365 A5) pueden beneficiarse de Microsoft defender para el punto de conexión.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los analistas de SecOps y los profesionales de la seguridad se benefician de las capacidades de seguridad de extremos de Microsoft defender para Endpoint para la protección preventiva, la detección tras incumplimiento, la investigación automatizada y la respuesta a amenazas avanzadas. Los usuarios finales aprovechan los eventos malintencionados supervisados por Microsoft defender para el punto de conexión.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características de Microsoft defender for Endpoint están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre la implementación, consulte la [Guía de implementación](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/deployment-phases).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Microsoft defender for Endpoint los administradores pueden usar el [control de acceso basado en roles (RBAC)](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac) para crear roles y grupos dentro del equipo de operaciones de seguridad para conceder el acceso adecuado al centro de seguridad de Microsoft defender.

## <a name="information-protection"></a>Protección de la información

La protección de la información ayuda a las organizaciones a descubrir, clasificar, etiquetar y proteger los documentos y mensajes confidenciales. Los administradores pueden definir reglas y condiciones para aplicar etiquetas automáticamente, los usuarios pueden aplicar etiquetas manualmente o se puede usar una combinación de ambas, en la que los usuarios tienen recomendaciones para aplicar etiquetas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios pueden beneficiarse de la capacidad de aplicar manualmente las etiquetas de confidencialidad a su contenido o de clasificar automáticamente su contenido.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

Microsoft 365 E5/A5/G5/E3/a3/G3/F1/F3/Business Premium, Enterprise Mobility + seguridad F3/E3/E5, Office 365 E5/A5/E3/a3/F3, el plan de AIP 1 y el plan AIP 2 proporcionan los derechos de un usuario para beneficiarse de la etiqueta de confidencialidad manual.

Microsoft 365 E5/A5/G5/E3/a3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, el plan 1 y el plan AIP 2 proporcionan los derechos que tiene un usuario para beneficiarse de la aplicación y visualización de las etiquetas de confidencialidad en Power BI y la protección de los datos cuando se exportan de Power BI a Excel 

> [!NOTE]
> Power BI se incluye con Microsoft 365 E5/A5/G5; en todos los demás planes, Power BI debe tener una licencia por separado.

Microsoft 365 E5/A5/G5, el cumplimiento de Microsoft 365 E5/A5/G5, la protección de la información de Microsoft 365 y el gobierno, Office 365 E5, Office 365 Advanced Compliance, Enterprise Mobility + Security E5 y el plan AIP 2 proporcionan los derechos para que un usuario se beneficie del etiquetado de sensibilidad automático.

Para obtener derechos específicos por licencia, consulte la comparación detallada de licencias de cumplimiento de Microsoft 365. [(Pdf)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) No incluye derechos para la clasificación automática basada en el aprendizaje de la máquina (clasificadores cocapacitados).

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características de protección de la información están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar directivas para los usuarios con licencia, consulte Activating Azure Rights Management.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Excepto cuando se usa la característica de escáner AIP, las directivas pueden estar en el ámbito de grupos específicos o los usuarios y los registros se pueden editar para evitar que los usuarios sin licencia ejecuten características de clasificación o etiquetado. Para obtener instrucciones sobre cómo asignar el ámbito de las implementaciones de AIP, vea [configuración de la Directiva de Azure Information Protection](https://docs.microsoft.com/azure/information-protection/configure-policy).

Para la característica de analizador de AIP, Microsoft no se compromete a ofrecer capacidades de clasificación, etiquetado o protección de archivos a los usuarios que no tienen licencia.

## <a name="information-governance"></a>Gobierno de la información

El gobierno de la información ayuda a las organizaciones a administrar su riesgo mediante el descubrimiento, la clasificación, la etiqueta y el control de sus datos. El gobierno de la información permite a las organizaciones cumplir con los requisitos empresariales y de la normativa, así como reducir su superficie de ataque proporcionando capacidades de retención y eliminación a todos los datos de Microsoft 365 y de terceros.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician al poder clasificar los datos con fines de retención para preservar directivas y regulaciones específicas.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

Microsoft 365 F3/Business Premium, Office 365 E1/a1/F3 y los planes independientes de Exchange proporcionan los derechos que tienen los usuarios para beneficiarse de la aplicación manual de etiquetas de retención que no son registros a los datos del buzón.

Microsoft 365 F3/F1/Business Premium, Office 365 E1/a1/F3 y los planes independientes de SharePoint proporcionan los derechos que tienen los usuarios para beneficiarse de la aplicación manual de etiquetas de retención que no son de registros a los archivos de SharePoint o OneDrive. 

Microsoft 365 E5/A5/E3/a3/Business Premium, Office 365 E5/A5/E3/a3, Exchange plan 2 y archivado de Exchange Online proporcionan los derechos para que un usuario se beneficie de una directiva de retención de buzones de correo básico en toda la organización o ubicación o para aplicar manualmente una etiqueta de retención que no es de registro a los datos del buzón.

Microsoft 365 E5/A5/E3/a3, Office 365 E5/A5/E3/a3 y SharePoint plan 2 proporcionan los derechos para que un usuario se beneficie de una directiva de retención básica de SharePoint o de OneDrive, o para aplicar manualmente una etiqueta de retención que no es de registros a los archivos de SharePoint o OneDrive.

Microsoft 365 E5/A5/E3/a3 y Office 365 E5/A5/E3/a3 proporcionan los derechos de un usuario para beneficiarse de una directiva de retención de Teams.

Microsoft 365 E5/A5, el cumplimiento de Microsoft 365 E5/A5, el gobierno y la protección de la información de Microsoft 365, Office 365 E5/A5 y el cumplimiento avanzado de Office 365 proporcionan los derechos que tiene un usuario para beneficiarse de la aplicación automática de etiquetas de retención o directivas. aplicación de etiquetas o directivas de retención predeterminadas, inicio del período de retención de una etiqueta de retención basada en un evento personalizado, desencadenando una revisión de disposición manual al final del período de retención de la etiqueta, importación de datos de terceros a través de conectores de datos nativos, declaración de un archivo a registro, detección de contenido con etiqueta y supervisión de la actividad de etiquetado.

Microsoft 365 E5/A5, el cumplimiento de Microsoft 365 E5/A5, la protección de la información de Microsoft 365 y el gobierno proporcionan los derechos que tiene un usuario para beneficiarse de aplicar automáticamente etiquetas de retención basadas en clasificadores que se puedan entrenar.

Para obtener derechos específicos por licencia, consulte la comparación detallada de licencias de cumplimiento de Microsoft 365. [(Pdf)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características de gobierno de información se habilitan en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar el gobierno de información para aplicar etiquetas y directivas a los usuarios con licencia, consulte [Manage Information Governance](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Las características de gobierno de la información se pueden aplicar a usuarios con licencia en ubicaciones específicas (sitios de grupo, sitios de grupo, etc.). Para obtener información sobre cómo configurar el gobierno de información para aplicar etiquetas y directivas a los usuarios con licencia, consulte [Manage Information Governance](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance).

## <a name="records-management"></a>Records Management

La administración de registros ayuda a las organizaciones a cumplir sus obligaciones de mantenimiento reglamentario y de negocios mediante el descubrimiento, la clasificación, la etiqueta, la retención y las funcionalidades de eliminación a plazo en sus datos de Microsoft 365 y de terceros.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

Microsoft 365 E5/A5, el cumplimiento de Microsoft 365 E5/A5, la protección y el gobierno de la información de Microsoft 365, Office 365 E5/A5, Office 365 el cumplimiento avanzado proporcionan los derechos que tiene un usuario para beneficiarse de la administración de registros, lo que incluye declarar elementos como registros, aplicar automáticamente etiquetas de retención o registro y ejecutar procesos de revisión de disposición

Microsoft 365 E5/A5, el cumplimiento de Microsoft 365 E5/A5, la protección de la información de Microsoft 365 y el gobierno proporcionan los derechos que tiene un usuario para beneficiarse de aplicar automáticamente etiquetas de retención o registro basadas en clasificadores que se puedan entrenar.

Para obtener derechos específicos por licencia, consulte la comparación detallada de licencias de cumplimiento de Microsoft 365. [(Pdf)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician al poder declarar el contenido como un registro y administrar su proceso completo de registros a partir de la definición y la declaración de la Directiva hasta una eliminación por pasos dejustificados.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características de administración de registros están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar la administración de registros para aplicarla a los usuarios con licencia, consulte [Administración de registros en Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/records-management).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Las características de administración de registros se pueden aplicar a usuarios con licencia en ubicaciones específicas (sitios de grupo, sitios de grupo, etc.). Para obtener información sobre cómo configurar la administración de registros para aplicarla a los usuarios con licencia, consulte [Administración de registros en Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/records-management).

## <a name="data-connectors"></a>Conectores de datos 

Microsoft proporciona conectores de datos de terceros que se pueden configurar en el centro de cumplimiento de Microsoft 365. Para obtener una lista de los conectores de datos proporcionados por Microsoft, consulte la tabla [conectores de datos de terceros](https://docs.microsoft.com/microsoft-365/compliance/archiving-third-party-data) . En esta tabla también se resumen las soluciones de cumplimiento que se pueden aplicar a los datos de terceros después de importar y archivar datos en Microsoft 365 y vínculos a las instrucciones paso a paso para cada conector.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Una de las principales ventajas de usar conectores de datos para importar y archivar datos de terceros en Microsoft 365 es que puede aplicar diversas soluciones de cumplimiento de Microsoft 365 a esa una vez que se ha importado. Esto ayuda a garantizar que los datos de su organización que no son de Microsoft cumplen con las regulaciones y los estándares que afectan a su organización.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

Las siguientes licencias proporcionan los derechos para que un usuario se beneficie de los conectores de datos:

- Microsoft 365 E5/A5
- Microsoft 365 E5/control de & de protección de información A5
- Cumplimiento de Microsoft 365 E5/A5
- Microsoft 365 E5/administración de riesgos de Insider A5
- Microsoft 365 E5/la exhibición de documentos electrónicos A5 y auditoría
- Office 365 E5/A5
- Cumplimiento avanzado de Office 365

Para los conectores de datos del centro de seguridad & cumplimiento de M365 que provienen de uno de los socios de Microsoft, la organización necesitará una relación comercial con el socio antes de poder implementar esos conectores.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

Los conectores se configuran mediante la seguridad & el centro de cumplimiento y el catálogo de conectores.

### <a name="how-can-the-service-be-applied-only---to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los servicios de conectores de datos son un valor de nivel de espacio empresarial. Todos los usuarios que se vayan a beneficiar de este servicio deben tener licencia.

## <a name="microsoft-graph-apis-for-teams-dlp"></a>API de Microsoft Graph para DLP de Teams

Al principio de este año, [anunciamos la versión preliminar pública de la API de notificación de cambios de Microsoft Graph para los mensajes en Teams](https://go.microsoft.com/fwlink/?linkid=2143888). Esta API permite a los programadores crear aplicaciones que puedan escuchar los mensajes de Microsoft Teams en tiempo casi real y habilitar implementaciones de escenario de DLP tanto para clientes como para proveedores de software independientes (ISV). Además, la API de revisión de Microsoft Graph permite aplicar acciones de DLP a los mensajes de Microsoft Teams.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Las capacidades de [prevención de pérdida de datos (DLP)](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams) se usan ampliamente en Microsoft Teams, especialmente cuando las organizaciones se han desplazado al trabajo remoto. Si su organización tiene DLP, ahora puede definir directivas que impiden que los usuarios compartan información confidencial en una sesión de chat o de canal de Microsoft Teams.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

Necesitará una de las siguientes licencias de E5 para admitir la protección de prevención de pérdida de datos (DLP) en el chat de Microsoft Teams:

- Microsoft 365 E5/A5
- Cumplimiento de Microsoft 365 E5/A5
- Microsoft 365 E5/protección y gobernanza de la información A5
- Office 365 E5/A5 

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

El acceso a la API está configurado en el nivel de espacio empresarial.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

La API de Microsoft Graph para Teams DLP es un valor de nivel de espacio empresarial. Todos los usuarios que se vayan a beneficiar de este servicio deben tener licencia.

## <a name="ediscovery"></a>eDiscovery

eDiscovery proporciona soluciones de investigación y exhibición de documentos electrónicos para departamentos de ti y legales dentro de las empresas para identificar, recopilar, preservar, reducir y revisar el contenido relacionado con una investigación o litigio antes de la exportación fuera del sistema Microsoft 365.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Un usuario se beneficia de la exhibición avanzada de documentos electrónicos cuando el usuario se selecciona como un custodio de datos (una persona con control administrativo de un documento o un archivo electrónico) para un caso.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

Microsoft 365 E5/A5/G5/E3/a3/G3, Office 365 E5/A5/G5/E3/a3/G3 y Office 365 Advanced Compliance proporcionan los derechos de un usuario para beneficiarse de la exhibición de documentos electrónicos principal.
Microsoft 365 E5/A5/G5, el cumplimiento de Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5 eDiscovery y auditoría, Office 365 E5/A5/G5 y Office 365 Advanced Compliance proporcionan los derechos que tiene un usuario para beneficiarse de la exhibición avanzada de documentos electrónicos.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características avanzadas de eDiscovery se habilitan en el nivel de inquilino para todos los usuarios del espacio empresarial cuando los administradores asignan permisos de exhibición de documentos electrónicos en el centro de seguridad & cumplimiento.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

los administradores de exhibición de documentos electrónicos pueden seleccionar usuarios específicos como custodios de datos para un caso mediante la herramienta de administración de custodios integrada en eDiscovery avanzado, tal como se describe en [Agregar custodios a un caso de exhibición avanzada](https://docs.microsoft.com/microsoft-365/compliance/add-custodians-to-case)de documentos electrónicos.

## <a name="office-365-customer-key"></a>Clave de cliente de Office 365

Con la clave de cliente, se controlan las claves de cifrado de la organización y se configura Office 365 para usarlas y cifrar los datos en reposo en los centros de datos de Microsoft. Es decir, la clave de cliente le permite agregar una capa de cifrado que le pertenece con sus propias claves. Los datos en reposo incluyen datos de Exchange Online y Skype empresarial que se almacenan en buzones de correo y archivos de SharePoint Online y OneDrive para la empresa.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de la clave de cliente al tener sus datos en reposo cifrados en el nivel de aplicación mediante claves de cifrado que se proporcionan, controlan y administran desde su propia organización.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

Microsoft 365 E5/A5, el cumplimiento de Microsoft 365 E5/A5, el gobierno y la protección de la información de Microsoft 365, la Office 365 E5/A5 y el cumplimiento avanzado de Office 365 proporcionan los derechos de un usuario para beneficiarse de la clave de cliente. Para obtener todas las ventajas de la clave de cliente, también debe tener una suscripción de Azure Key Vault.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

Se pueden habilitar las claves de cifrado de clave de cliente de Office 365 para todos los datos almacenados en los buzones de correo de Exchange Online y Skype empresarial, y en los archivos de SharePoint Online, OneDrive para la empresa y Microsoft Teams. Para obtener más información acerca de la clave de cliente de Office 365, incluido cómo empezar, consulte [Service Encryption with Customer key in Office 365](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Para Exchange Online y Skype empresarial, los buzones pueden cifrarse con la clave de cliente. Debe configurar Azure antes de poder usar la clave de cliente de Office 365. Consulte [configurar la clave de cliente](https://docs.microsoft.com/microsoft-365/compliance/customer-key-set-up) para conocer los pasos que debe seguir para crear y configurar los recursos necesarios de Azure y los pasos para configurar la clave de cliente en Office 365. Una vez completada la configuración de Azure, determine qué directiva y, por lo tanto, qué claves asignar a los buzones de correo y los archivos de su organización. Los buzones de correo y los archivos para los que no se asigna una directiva usarán directivas de cifrado controladas y administradas por Microsoft. Para obtener más información acerca de la clave de cliente o para obtener información general, consulte [Service Encryption with Customer key in Office 365](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview).

## <a name="office-365-customer-lockbox"></a>Caja de seguridad del cliente de Office 365

La caja de caja del cliente proporciona una capa de control adicional al ofrecer a los clientes la capacidad de otorgar autorización de acceso explícito para las operaciones de servicio. Al demostrar que se han implementado los procedimientos para la autorización explícita de acceso a datos, la caja de seguridad del cliente también puede ayudar a las organizaciones a cumplir ciertas obligaciones de cumplimiento, como HIPAA y FEDRAMP.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de la caja de garantía del cliente para garantizar que nadie en Microsoft pueda acceder a su contenido para realizar una operación de servicio sin la aprobación explícita del cliente. La caja de caja del cliente pone al cliente en el flujo de trabajo de aprobación para las solicitudes de acceso a su contenido. En ocasiones, los ingenieros de Microsoft están involucrados durante el proceso de soporte para solucionar problemas y solucionar problemas notificados por los clientes. En la mayoría de los casos, los problemas se arreglan mediante amplias herramientas de depuración y telemetría que Microsoft ha implementado para sus servicios. Sin embargo, puede haber casos que requieran que un ingeniero de Microsoft tenga acceso al contenido del cliente para determinar la causa raíz y corregir el problema. La caja de caja del cliente requiere que el ingeniero solicite el acceso del cliente como paso final en el flujo de trabajo de aprobación. Esto proporciona a las organizaciones la opción de aprobar o denegar estas solicitudes, lo que les proporciona el control directo sobre si un ingeniero de Microsoft puede tener acceso a los datos de los usuarios finales de las organizaciones.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, el cumplimiento de Microsoft 365 E5/A5/G5, la administración de riesgos de Insider de Microsoft 365 y Office 365 Advanced Compliance proporcionan los derechos para que un usuario se beneficie de las cajas de caja del cliente.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

Los administradores pueden activar los controles de caja de caja del cliente en el centro de administración de Microsoft 365. Para obtener más información, consulte [caja de caja del cliente en Office 365](https://docs.microsoft.com/microsoft-365/compliance/customer-lockbox-requests). Cuando la caja de caja de clientes está activada, Microsoft debe obtener la aprobación de la organización antes de tener acceso a cualquiera de sus contenidos.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

El servicio de caja de caja del cliente no se puede limitar actualmente a usuarios específicos. Debe conceder una licencia a todos los usuarios que desee que se beneficien.

## <a name="privileged-access-management-in-office-365"></a>Administración de acceso privilegiado en Office 365

La [Administración de acceso con privilegios (PAM)](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration) proporciona un control de acceso granular sobre las tareas de administración con privilegios en Office 365. Después de habilitar PAM, los usuarios tendrán que solicitar acceso justo a tiempo a través de un flujo de trabajo de aprobación con un ámbito muy limitado y con un límite de tiempo para completar las tareas elevadas y privilegiadas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

La habilitación de PAM permite a las organizaciones operar con cero derechos de posición. Los usuarios se benefician de la capa agregada de defensa contra las vulnerabilidades que se derivan de un acceso administrativo permanente que proporciona un acceso libre a sus datos.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio? 

Office 365 E5/A5, Microsoft 365 E5/A5, el cumplimiento de Microsoft 365 E5/A5 y la protección de la información y el gobierno de Microsoft 365 E5/A5 proporcionan los derechos para que un usuario se beneficie de PAM.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características de PAM se habilitan en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar directivas de PAM, consulte [Get Started with privileged Access Management](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los clientes pueden administrar PAM por usuario mediante directivas de acceso y de grupo de aprobador, que se pueden aplicar a los usuarios con licencia. Para obtener más información, vea [Administración del acceso con privilegios en Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="double-key-encryption-for-microsoft-365"></a>Cifrado de doble clave para Microsoft 365 

El cifrado de doble clave para Microsoft 365 permite proteger los datos extremadamente confidenciales para cumplir requisitos especializados y mantener el control total de la clave de cifrado. El cifrado de doble clave usa dos claves para proteger los datos, con una clave en el control y la segunda clave almacenada de forma segura en Microsoft Azure. Para ver los datos, debe tener acceso a ambas claves. Como Microsoft solo puede tener acceso a una clave, la clave y los datos no están disponibles para Microsoft, lo que garantiza que tendrá un control total sobre la privacidad y la seguridad de sus datos.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician del cifrado de doble clave al poder migrar sus datos cifrados a la nube e impedir el acceso de terceros, siempre que la clave permanezca en el control de los usuarios. Los usuarios finales pueden proteger y consumir contenido cifrado de doble clave, de forma similar a cualquier otro contenido protegido de la etiqueta de confidencialidad.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

Microsoft 365 E5/A5, el cumplimiento de Microsoft 365 E5/A5, el gobierno y la protección de la información de Microsoft 365, la Office 365 E5/A5 y el cumplimiento avanzado de Office 365 proporcionan los derechos para que un usuario se beneficie de dos claves de cifrado.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

El cifrado de doble clave admite la versión de escritorio de Microsoft Office para Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Para asignar claves de cifrado a datos dentro de una organización de Office 365 o Microsoft 365 para usuarios con licencia, siga las instrucciones de implementación de doble cifrado.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Prevención de pérdida de datos de Office 365 para Exchange Online, SharePoint Online y OneDrive para la empresa

Con Office 365 prevención de pérdida de datos (DLP) para Exchange Online, SharePoint Online y OneDrive para la empresa, las organizaciones pueden identificar, supervisar y proteger automáticamente la información confidencial en todos los correos electrónicos y archivos (incluidos los archivos almacenados en los repositorios de archivos de Microsoft Teams).

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de DLP para Exchange Online, SharePoint Online y OneDrive para la empresa cuando sus archivos y mensajes de correo electrónico se inspecciona para obtener información confidencial, tal como se ha configurado en la Directiva DLP de la organización.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

Microsoft 365 a1/E3/a3/Business, Office 365 E3/a3 y la prevención de pérdida de datos de Office 365 proporcionan los derechos para que un usuario se beneficie de Office 365 DLP para Exchange Online, SharePoint Online y OneDrive para la empresa.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, los mensajes de correo electrónico de Exchange Online, los sitios de SharePoint y las cuentas de OneDrive son *ubicaciones (cargas de trabajo) habilitadas* para estas características de DLP para todos los usuarios del espacio empresarial. Para obtener más información sobre el uso de directivas de DLP, vea [información general sobre prevención de pérdida de datos](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los administradores pueden personalizar las ubicaciones (cargas de trabajo), los usuarios incluidos y los usuarios excluidos en el centro de seguridad & cumplimiento, en ubicaciones de **prevención de pérdida de datos**  >  **Locations**.

## <a name="communication-data-loss-prevention-for-teams"></a>Prevención de pérdida de datos de comunicación para Microsoft Teams

Con DLP de comunicación para Microsoft Teams, las organizaciones pueden bloquear chats y mensajes de canal que contengan información confidencial, como información financiera, información personal de identificación, información relacionada con el estado u otra información confidencial.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Office 365 E5/A5, Microsoft 365 E5/A5, el gobierno y la protección de la información de Microsoft 365 y el cumplimiento avanzado de Office 365 pueden beneficiarse de la comunicación DLP para Teams.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los remitentes obtienen beneficios al tener información confidencial en su chat saliente y los mensajes de canal inspeccionados para la información confidencial, tal y como se ha configurado en la Directiva DLP de la organización.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, los mensajes de chat y de canal de Microsoft son una *Ubicación (carga de trabajo) habilitada* para estas características DLP para todos los usuarios dentro del espacio empresarial. Para obtener más información sobre el uso de directivas de DLP, vea [información general sobre prevención de pérdida de datos](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los administradores pueden personalizar las ubicaciones (cargas de trabajo), los usuarios incluidos y los usuarios excluidos en el centro de seguridad & cumplimiento, en ubicaciones de **prevención de pérdida de datos**  >  **Locations**.

## <a name="information-barriers"></a>Barreras de la información

Las barreras de información son directivas que un administrador puede configurar para evitar que los usuarios o grupos se comuniquen entre sí. Esto es útil si, por ejemplo, un departamento está controlando información que no debe compartirse con otros departamentos, o bien es necesario evitar que un grupo se comunique con los contactos externos. Las directivas de barrera de información también evitan búsquedas y detección. Esto significa que si intenta comunicarse con alguien con quien no debe comunicarse, no encontrará a ese usuario en el selector de personas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de las capacidades de cumplimiento avanzadas de las barreras de la información cuando están restringidas de la comunicación con otros usuarios. Por ejemplo:<br><br>

| Escenario | ¿Quién necesita una licencia? |
|:------|:------|:------|
| Dos grupos (grupo &nbsp; 1 y grupo &nbsp; 2) no pueden comunicarse entre sí (es decir, &nbsp; los usuarios de grupo 1 tienen restringida la comunicación con los usuarios del grupo &nbsp; 2 y los &nbsp; usuarios del grupo 2 están restringidos para comunicarse con &nbsp; los usuarios del grupo 1). | Usuarios en el grupo &nbsp; 1 y el grupo &nbsp; 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 cumplimiento, Microsoft 365 Insider Risk Management, Office 365 E5/A5 y Office 365 el cumplimiento avanzado proporciona los derechos para que un usuario se beneficie de las barreras de información.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

Los administradores crean y administran directivas de barrera de información mediante cmdlets de PowerShell en el centro de seguridad & cumplimiento. Los administradores deben tener asignado el rol de administrador global de Microsoft 365 Enterprise, administrador global de Office 365 o administrador de cumplimiento para crear una directiva de barrera de información. De forma predeterminada, estas directivas se aplican a todos los usuarios del espacio empresarial. Para obtener más información sobre las barreras de información, consulte [barreras de la información en Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los administradores pueden personalizar las ubicaciones (cargas de trabajo), los usuarios incluidos y los usuarios excluidos en el centro de seguridad & cumplimiento. Por ejemplo, si todos los usuarios tienen licencia para Office 365 E3 y ninguno tiene licencia para Office 365 Advanced Compliance/E5, no necesitará crear ninguna directiva de barrera de información para la organización. Para obtener más información, consulte [barreras de la información en Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).

## <a name="office-365-message-encryption"></a>Cifrado de mensajes de Office 365

El cifrado de mensajes de Office 365 (OME) es un servicio basado en Azure Rights Management (Azure RMS) que permite enviar correo electrónico cifrado a otras personas dentro o fuera de la organización, independientemente de la dirección de correo electrónico de destino (Gmail, Yahoo! Mail, Outlook.com, etc.).

Para ver los mensajes cifrados, los destinatarios pueden obtener un código de acceso único, iniciar sesión con una cuenta de Microsoft, o iniciar sesión con una cuenta profesional o educativa asociada a Office 365. Los destinatarios también pueden enviar respuestas cifradas. No necesitan una suscripción para ver mensajes cifrados ni enviar respuestas cifradas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los remitentes de mensajes se benefician del control agregado sobre los mensajes de correo electrónico confidenciales proporcionados por el cifrado de mensajes de Office 365.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

Microsoft 365 E3/a3, Office 365 E3/a3 y Azure Information Protection Plan 1 proporcionan los derechos para que un usuario se beneficie del cifrado de mensajes de Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

Los administradores crean y administran directivas de cifrado de mensajes de Office 365 en el centro de administración de Exchange en reglas de **flujo de correo**  >  **Rules**. De forma predeterminada, estas reglas se aplican a todos los usuarios del espacio empresarial. Para obtener más información acerca de la configuración de nuevas capacidades de cifrado de mensajes de Office 365, vea [set up New office 365 Message Encryption Capabilities](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los administradores deben aplicar reglas de flujo de correo para el cifrado de mensajes de Office 365 solo a usuarios con licencia. Para obtener más información acerca de la definición de reglas de flujo de correo, consulte [definir reglas de flujo de correo para cifrar mensajes de correo electrónico en Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="office-365-advanced-message-encryption"></a>Cifrado de mensajes avanzado de Office 365

Office 365 Advanced Message Encryption ayuda a los clientes a cumplir las obligaciones de cumplimiento que requieren controles más flexibles sobre los destinatarios externos y su acceso a los correos electrónicos cifrados. Con el cifrado de mensajes avanzado, los administradores pueden controlar los mensajes de correo electrónico confidenciales que se comparten fuera de la organización mediante directivas automáticas que pueden detectar los tipos de información confidencial (por ejemplo, información de identificación personal o identificadores financieros o de salud) o pueden usar palabras clave para mejorar la protección mediante la aplicación de plantillas de correo electrónico personalizadas y la expiración del acceso Además, los administradores pueden controlar más los correos electrónicos cifrados a los que se accede externamente a través de un portal web seguro al revocar el acceso en cualquier momento.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los remitentes de mensajes se benefician del control agregado sobre los correos electrónicos confidenciales proporcionados por el cifrado avanzado de mensajes.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

Office 365 E5/A5, Microsoft 365 E5/A5, el cumplimiento de Microsoft 365 E5/A5, el gobierno y la protección de la información de Microsoft 365 y el cumplimiento avanzado de Office 365 proporcionan los derechos para que un usuario se beneficie del cifrado de mensajes avanzado.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

Los administradores crean y administran directivas de cifrado de mensajes avanzadas en el centro de administración de Exchange en reglas de flujo de correo. De forma predeterminada, estas reglas se aplican a todos los usuarios del inquilino. Para obtener más información acerca de la configuración de nuevas capacidades de cifrado de mensajes, vea [set up New Office 365 Message Encryption Capabilities](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los administradores deben aplicar reglas de flujo de correo para el cifrado de mensajes avanzado solo a los usuarios con licencia. Para obtener más información acerca de la definición de reglas de flujo de correo, consulte [definir reglas de flujo de correo para cifrar mensajes de correo electrónico en Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="communication-compliance"></a>Cumplimiento de la comunicación

El cumplimiento de la comunicación en Microsoft 365 ayuda a minimizar los riesgos de comunicación al ayudarle a detectar, capturar y realizar acciones de corrección para los mensajes inapropiados de su organización. Puede definir directivas específicas que capturen el correo electrónico interno y externo, Microsoft Teams o las comunicaciones de terceros de la organización. Los revisores pueden tomar las medidas de corrección adecuadas para asegurarse de que cumplen con los estándares de mensajes de la organización.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los especialistas en cumplimiento de normas se benefician del servicio al supervisar las comunicaciones de la organización mediante directivas de cumplimiento de comunicaciones.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

Office 365 E5/A5, Microsoft 365 E5/A5, el cumplimiento de Microsoft 365 E5/A5 y la administración de riesgos de Insider de Microsoft 365 proporcionan los derechos para que un usuario se beneficie del cumplimiento de la comunicación.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

Los administradores y los especialistas en cumplimiento crean directivas de cumplimiento de la comunicación en el centro de cumplimiento de Microsoft 365. Estas directivas definen qué comunicaciones y usuarios están sujetos a revisión en la organización, definen las condiciones personalizadas que deben cumplir las comunicaciones y especifican quién debe realizar revisiones.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Los administradores eligen grupos o usuarios específicos para incluirlos en una directiva de cumplimiento de la comunicación. Al elegir un grupo, también pueden seleccionar usuarios específicos del grupo para excluirlos de la Directiva de cumplimiento de la comunicación. Para obtener más información acerca de las directivas de cumplimiento de comunicaciones, consulte [cumplimiento de la comunicación en Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/communication-compliance-configure).

## <a name="insider-risk-management"></a>Administración de riesgos de Insider

La administración de riesgos de Insider es una solución en Microsoft 365 que contribuye a minimizar los riesgos internos, ya que permite detectar, investigar y realizar acciones en actividades de riesgo de la organización.
Las directivas personalizadas le permiten detectar y realizar acciones en actividades malintencionadas e involuntarias en su organización, incluidos la escalabilidad de casos a Microsoft Advanced eDiscovery, si es necesario. Los analistas de riesgos de su organización pueden emprender rápidamente las acciones adecuadas para asegurarse de que los usuarios cumplan con los estándares de cumplimiento de la organización.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician al supervisar sus actividades para riesgo.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos que tiene un usuario para beneficiarse del servicio?

Microsoft 365 E5/A5, el cumplimiento de Microsoft 365 E5/A5 y la administración de riesgos de Insider de Microsoft 365 proporcionan los derechos de un usuario para beneficiarse de la administración de riesgos de Insider.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

Las directivas de administración de riesgos de Insider deben crearse en el centro de cumplimiento de Microsoft 365 y asignarse a los usuarios.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Al crear una directiva en el centro de cumplimiento de Microsoft 365, en la página **elegir usuarios y grupos** , seleccione **elegir usuarios o grupos** para seleccionar solo usuarios con licencia o, si todos los usuarios tienen licencia, active la casilla de verificación **todos los usuarios y grupos con correo habilitado** . Para obtener más información, consulte Introducción [a la administración de riesgos de Insider](https://docs.microsoft.com/microsoft-365/compliance/insider-risk-management-configure).

## <a name="conditional-access-policies"></a>Directivas de acceso condicional

El acceso condicional es la herramienta que Azure Active Directory usa para reunir las señales, tomar decisiones y aplicar directivas organizativas. El acceso condicional es el corazón del plano de control controlado por identidad. Las directivas de acceso condicional en su forma más sencilla son instrucciones if-then. Si un usuario desea tener acceso a un recurso, debe completar una acción. Ejemplo: un administrador de nóminas desea tener acceso a la aplicación de nóminas y es necesario para realizar la autenticación multifactor para tener acceso a ella.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Enterprise Mobility + Security E3/a3, Microsoft 365 F3/E3/a3/Business Premium y Azure Active Directory Premium plan 1 pueden beneficiarse de las directivas de acceso condicional. Los usuarios con licencia de Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5, Microsoft E5 Security y Azure Active Directory Premium plan 2 pueden beneficiarse de la protección de identidad (directivas de acceso condicional basadas en riesgos).

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los analistas de operaciones de seguridad y los profesionales de la seguridad aprovechan la capacidad de aplicar directivas organizativas a los usuarios, lo que les obliga a cumplir determinados criterios antes de conceder acceso al contenido corporativo. Los usuarios finales pueden beneficiarse de tener acceso a su trabajo dondequiera y cuando lo deseen, a la vez que protegen los activos de la organización.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, las características de acceso condicional están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

Para la protección de identidad y el acceso condicional en concreto, un usuario debe incluirse en un grupo o agregarse a una directiva de acceso condicional. La condición Users and Groups es obligatoria en una directiva de acceso condicional. En la Directiva, puede seleccionar todos los **usuarios** o bien usuarios y grupos específicos. Solo debe seleccionar los usuarios y grupos con licencia adecuada. Para obtener más información, vea [¿Qué son las condiciones de acceso condicional de Azure Active Directory?](https://docs.microsoft.com/azure/active-directory/conditional-access/conditions).

## <a name="advanced-audit"></a>Auditoría avanzada

La auditoría avanzada en Microsoft 365 proporciona una retención de un año de registros de auditoría para actividades de usuario y de administrador, y proporciona la capacidad de crear directivas de retención de registro de auditoría personalizadas para administrar la retención de registros de auditoría para otros servicios de Microsoft 365. También proporciona acceso a eventos fundamentales para las investigaciones y el acceso de gran ancho de banda a la API de actividad de administración 365 de Office. Para obtener más información, consulte [auditoría avanzada en Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit).

También puede habilitar un período de retención de 10 años con un SKU de complemento. El SKU del complemento será necesario a partir de la 2021 inicial.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Office 365 E5, Microsoft 365 E5, el cumplimiento de Microsoft 365 E5 y Microsoft 365 eDiscovery y Audit pueden beneficiarse de la auditoría avanzada.

Los usuarios con licencia con una auditoría avanzada y el complemento de retención de registro de auditoría de diez años pueden beneficiarse de la retención de registro de auditoría de 10 años.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Un usuario se beneficia de la auditoría avanzada porque los registros de auditoría relacionados con la actividad de los usuarios en los servicios de Microsoft 365 se pueden conservar hasta un año. Además, se registran los eventos de auditoría de gran valor, como cuando se tiene acceso a los elementos del buzón de un usuario o se leen. Para obtener más información, consulte [auditoría avanzada en Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit).

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se implementa o se implementa el servicio?

De forma predeterminada, la auditoría avanzada está habilitada en el nivel de espacio empresarial para todas las organizaciones que tienen una suscripción de Office 365 o Microsoft 365 E5, y proporciona automáticamente una retención de un año de registros de auditoría para actividades (realizadas por los usuarios con la licencia adecuada) en Azure Active Directory, Exchange y SharePoint. Además, las organizaciones pueden usar directivas de retención de registro de auditoría para administrar el período de retención de los registros de auditoría generados por la actividad en otros servicios de Microsoft 365. La funcionalidad de retención de registro de auditoría de 10 años también se habilita con las mismas directivas de retención. Para obtener más información, vea [administrar directivas de retención de los registros de auditoría](https://docs.microsoft.com/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino que tienen licencia para el servicio?

La retención de un año de registros de auditoría y la auditoría de eventos vitales solo se aplican a los usuarios con la licencia adecuada. Además, los administradores pueden usar directivas de retención de registro de auditoría para especificar duraciones de retención más cortas para los registros de auditoría de usuarios específicos.

la retención de 10 años de registros de auditoría solo se aplica a los usuarios con la licencia de complemento correspondiente. El SKU del complemento será necesario a partir de la 2021 inicial.
