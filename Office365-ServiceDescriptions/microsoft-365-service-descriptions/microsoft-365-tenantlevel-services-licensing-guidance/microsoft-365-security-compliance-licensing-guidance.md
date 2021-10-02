---
title: Microsoft 365 guía para el cumplimiento de & seguridad
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: En este artículo se proporcionan instrucciones Microsoft 365 cumplimiento normativo para ayudar a evitar posibles interrupciones del servicio debido al acceso sin licencia.
ms.openlocfilehash: e889cdbfe23bbea76fcaf66596dad202be4918fd
ms.sourcegitcommit: 0107453467d2f1b4971118273631248432d0aa28
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/02/2021
ms.locfileid: "60082860"
---
# <a name="microsoft-365-guidance-for-security-amp-compliance"></a>Microsoft 365 guía para el cumplimiento de &amp; la seguridad

Para los fines de este artículo, un servicio de nivel de inquilino es un servicio en línea que cuando se compra para cualquier usuario del inquilino (independiente o como parte de planes Office 365 o Microsoft 365) se activa en parte o en su totalidad para todos los usuarios del &mdash; &mdash; inquilino. Aunque algunos usuarios sin licencia pueden tener acceso técnicamente al servicio, se requiere una licencia para cualquier usuario que tenga la intención de beneficiarse del servicio.

> [!NOTE]
> Algunos servicios de inquilinos no son actualmente capaces de limitar las ventajas para usuarios específicos. Se deben realizar esfuerzos para limitar las ventajas del servicio a los usuarios con licencia. Esto ayudará a evitar posibles interrupciones del servicio en la organización una vez que las capacidades de destino estén disponibles.

Para ver las opciones para otorgar licencias a los usuarios para que se beneficien de Microsoft 365 de cumplimiento normativo, descargue la [Microsoft 365 de comparación](https://go.microsoft.com/fwlink/?linkid=2139145).

## <a name="advanced-audit"></a>Auditoría avanzada

La auditoría avanzada en Microsoft 365 proporciona una retención de un año de registros de auditoría para las actividades de usuario y administrador y proporciona la capacidad de crear directivas de retención de registros de auditoría personalizadas para administrar la retención de registros de auditoría para otros servicios Microsoft 365 auditoría. También proporciona acceso a eventos cruciales para investigaciones y acceso de ancho de banda alto a la API Office 365 actividad de administración. Para obtener más información, vea [Advanced Audit in Microsoft 365](/microsoft-365/compliance/advanced-audit).

También puede habilitar un período de retención de 10 años con una SKU de complemento.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance, Microsoft 365 F5 Security & Compliance y Microsoft 365 E5/A5/G5 eDiscovery and Audit pueden beneficiarse de la auditoría avanzada.

Los usuarios con licencia con auditoría avanzada y el complemento retención de registros de auditoría de 10 años pueden beneficiarse de la retención de registros de auditoría de 10 años.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de la auditoría avanzada porque los registros de auditoría relacionados con la actividad del usuario en Microsoft 365 servicios pueden conservarse durante un año. Además, se registran eventos de auditoría de alto valor, como cuando se tiene acceso o se lee a los elementos del buzón de un usuario. Para obtener más información, vea [Advanced Audit in Microsoft 365](/microsoft-365/compliance/advanced-audit).

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, la auditoría avanzada está habilitada en el nivel de inquilino para todos los usuarios que se benefician del servicio y proporciona automáticamente una retención de un año de registros de auditoría para actividades (realizadas por usuarios con la licencia adecuada) en Azure Active Directory, Exchange y SharePoint. Además, las organizaciones pueden usar directivas de retención de registros de auditoría para administrar el período de retención de los registros de auditoría generados por la actividad en otros servicios Microsoft 365 auditoría. La funcionalidad de retención de registros de auditoría de 10 años también está habilitada con las mismas directivas de retención. Para obtener más información, vea [administrar directivas de retención de los registros de auditoría](/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

La retención de registros de auditoría de un año y la auditoría de eventos cruciales solo se aplican a los usuarios con la licencia adecuada. Además, los administradores pueden usar directivas de retención de registros de auditoría para especificar duraciones de retención más cortas para los registros de auditoría de usuarios específicos.

La retención de registros de auditoría de 10 años solo se aplica a los usuarios con la licencia de complemento adecuada. La SKU del complemento será necesaria a partir de principios de 2021.

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory La protección de identidades es una característica del plan de Azure Active Directory Premium P2 que le permite detectar posibles vulnerabilidades que afectan a las identidades de su organización, configurar respuestas automatizadas para detectar acciones sospechosas relacionadas con las identidades de su organización e investigar incidentes sospechosos y tomar las medidas adecuadas para resolverlas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los analistas y profesionales de seguridad de SecOps se benefician de tener vistas consolidadas de usuarios marcados y eventos de riesgo basados en algoritmos de aprendizaje automático. Los usuarios finales se benefician de la protección automática proporcionada a través del acceso condicional basado en riesgos y la seguridad mejorada proporcionada al actuar en vulnerabilidades.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

- Azure Active Directory Plan 1: Microsoft 365 E3/A3/G3/F1/F3, Enterprise Mobility & Security E3 y Microsoft 365 Empresa Premium
- Azure Active Directory Plan 2: Microsoft 365 E5/A5/G5, Enterprise Mobility & Security E5, Microsoft 365 E5/F5 Security y Microsoft 365 F5 Security & Compliance

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de Azure AD Identity Protection están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información acerca de Azure AD Identity Protection, consulte [¿Qué es Identity Protection?](/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores pueden establecer el ámbito de Azure AD Identity Protection mediante la asignación de directivas de riesgo que definen el nivel de restablecimiento de contraseña y permiten el acceso solo a usuarios con licencia. Para obtener instrucciones sobre cómo establecer el ámbito de las implementaciones de Azure AD Identity Protection, consulte [How to configure and enable risk policies](/azure/active-directory/identity-protection/howto-sign-in-risk-policy).

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory Gobierno de identidades

Azure Active Directory Identity Governance le permite equilibrar la necesidad de la organización de seguridad y productividad de los empleados con los procesos y la visibilidad adecuados. Usa la administración de derechos, revisiones de acceso, administración de identidades privilegiadas y directivas de términos de uso para garantizar que las personas adecuadas tengan acceso a los recursos adecuados.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Azure Active Directory Identity Governance aumenta la productividad de los usuarios al facilitar la solicitud de acceso a aplicaciones, grupos y Microsoft Teams un paquete de acceso. Los usuarios también se pueden configurar como aprobadores, sin la participación de administradores. Para las revisiones de acceso, los usuarios pueden revisar las pertenencias a grupos con recomendaciones inteligentes para tomar medidas en intervalos regulares.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5/F5 Security y F5 Security & Compliance y Azure Active Directory Premium Plan 2 proporcionan los derechos para que un usuario se beneficie de Azure Active Directory Identity Governance.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

Las características de Gobierno de identidad de Azure AD están habilitadas en el nivel de inquilino, pero se implementan por usuario. Para obtener información acerca de Azure AD Identity Governance, consulte [¿Qué es Azure AD Identity Governance?](/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores pueden establecer el ámbito de Azure AD Identity Governance mediante la asignación de paquetes de acceso, revisiones de acceso o administración de identidades con privilegios solo para usuarios con licencia. Para obtener instrucciones sobre cómo tener en cuenta las implementaciones de Azure AD Identity Governance, consulte:

- [Requisitos de licencia de administración de derechos de Azure AD](/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Requisitos de licencia de revisión de acceso de Azure AD](/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Requisitos de licencia para usar Privileged Identity Management](/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="communication-compliance"></a>Cumplimiento de la comunicación

El cumplimiento de la comunicación en Microsoft 365 ayuda a minimizar los riesgos de comunicación al ayudarle a detectar, capturar y tomar medidas de corrección para mensajes inadecuados en su organización. Puede definir directivas específicas que capturen correo electrónico interno y externo, Microsoft Teams o comunicaciones de terceros en su organización. Los revisores pueden realizar las acciones de corrección adecuadas para asegurarse de que cumplen con los estándares de mensajes de su organización.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los especialistas en cumplimiento se benefician del servicio al tener las comunicaciones de la organización supervisadas por directivas de cumplimiento de comunicaciones.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance, Microsoft 365 F5 Security & Compliance y Microsoft 365 E5/A5/G5 Insider Risk Management proporcionan los derechos para que un usuario se beneficie del cumplimiento de las comunicaciones.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

Los administradores y los especialistas en cumplimiento crean directivas de cumplimiento de comunicaciones en el Centro de cumplimiento de Microsoft 365. Estas directivas definen qué comunicaciones y usuarios están sujetos a revisión en la organización, definen las condiciones personalizadas que deben cumplir las comunicaciones y especifican quién debe realizar revisiones.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores eligen grupos o usuarios específicos para incluir en una directiva de cumplimiento de comunicaciones. Al elegir un grupo, también pueden seleccionar usuarios específicos del grupo para excluirlos de la directiva de cumplimiento de comunicaciones. Para obtener más información acerca de las directivas de cumplimiento de comunicaciones, vea Introducción al cumplimiento [de comunicaciones en Microsoft 365](/microsoft-365/compliance/communication-compliance-configure).

## <a name="compliance-manager"></a>Administrador de cumplimiento

[Microsoft Compliance Manager](https://compliance.microsoft.com/compliancemanager) es una característica de la Centro de cumplimiento de Microsoft 365 [que](/microsoft-365/compliance/microsoft-365-compliance-center) le ayuda a administrar los requisitos de cumplimiento de su organización con mayor facilidad y comodidad. El Administrador de cumplimiento puede ayudarle a lo largo del proceso de cumplimiento, desde realizar un inventario de los riesgos de protección de datos hasta administrar las complejidades de la implementación de controles, estar al corriente de las normativas y certificaciones e informar a los auditores.

El Administrador de cumplimiento ayuda a simplificar el cumplimiento y reducir los riesgos proporcionando:

- Evaluaciones predefinidas para normas y reglamentos regionales y comunes del sector y evaluaciones personalizadas para satisfacer sus propias necesidades de cumplimiento.
- Funcionalidades de flujo de trabajo que permiten completar de manera eficiente las evaluaciones de riesgos a través de una sola herramienta.
- Instrucciones detalladas paso a paso sobre las acciones de mejora sugeridas para ayudarle a cumplir con los estándares y normativas más relevantes para su organización. Para las acciones administradas por Microsoft, verá los detalles de implementación y los resultados de auditoría.
- Una puntuación de cumplimiento basada en riesgos que le ayudará a comprender su posición de cumplimiento midiendo su progreso en la realización de acciones de mejora.

### <a name="who-can-access-compliance-manager"></a>Quién Puede tener acceso al Administrador de cumplimiento?

El Administrador de cumplimiento está disponible para las organizaciones con licencias Office 365 y Microsoft 365, y para los clientes de Government Community Cloud (GCC), GCC High y Department of Defense (DoD). La disponibilidad de evaluación y las capacidades de administración dependen del contrato de licencia.

### <a name="what-are-premium-assessments"></a>¿Qué son las evaluaciones premium?

Premium evaluaciones son un valor de complemento para el Administrador de cumplimiento y ayuda:

- Traducir requisitos normativos complejos a controles específicos
- Sugerir acciones de mejora recomendadas
- Proporcionar medidas cuantificables de cumplimiento con las normativas

El Administrador de cumplimiento tiene más de 300 evaluaciones premium que los clientes pueden usar para evaluar su cumplimiento con una amplia gama de normativas y estándares globales, regionales e industriales.

Cualquier cliente con una suscripción que incluya Microsoft Exchange Online licencia puede comprar evaluaciones premium del Administrador de cumplimiento.

### <a name="which-premium-assessments-are-available"></a>¿Qué evaluaciones premium están disponibles?

Esta es la [lista de evaluaciones premium](/microsoft-365/compliance/compliance-manager-templates-list#premium-templates).

### <a name="which-assessments-are-included-by-default-free-of-cost"></a>¿Qué evaluaciones se incluyen de forma predeterminada (sin costo)?

Algunas evaluaciones se incluyen como parte del Administrador de cumplimiento y el tipo de licencia de cliente. Vea la tabla siguiente para obtener más información:

| Tipo de licencia | Plantillas de evaluación (incluidas de forma predeterminada) |
|:-----|:-----|
|<ul><li>Microsoft 365 o Office 365 A1/E1/F1/G1</li><li>Microsoft 365 o Office 365 A3/E3/F3/G3</li></ul>|<ul><li>Línea base de Protección de datos</li></ul>|
|<ul><li>Microsoft 365 o Office 365 A5/E5/G5</li><li>Microsoft 365 A5/E5/F5/G5 Compliance</li><li>Microsoft 365 A5/E5/F5/G5 eDiscovery and Audit</li><li>Microsoft 365 A5/E5/F5/G5 Insider Risk Management</li><li>Microsoft 365 A5/E5/F5/G5 Information Protection and Governance</li></ul>|<ul><li>Línea base de Protección de datos</li><li>UE GDPR</li><li>NIST 800-53</li><li>ISO 27001</li><li>Nivel 1-5 de CMMC (solo disponible para G5)</li><li>Evaluaciones personalizadas</li></ul>|

### <a name="what-are-custom-assessments"></a>¿Qué son las evaluaciones personalizadas?

Las evaluaciones personalizadas son una característica del Administrador de cumplimiento que proporciona la capacidad de crear una plantilla nueva o personalizar una plantilla de evaluación existente, incluida la adición o actualización de controles y acciones de mejora.

### <a name="who-can-access-custom-assessments"></a>Quién Puede tener acceso a evaluaciones personalizadas?

La característica de evaluaciones personalizadas está disponible para los clientes con una suscripción A5 como se muestra a continuación:

- Microsoft 365 o Office 365 A5/E5/G5
- Microsoft 365 A5/E5/F5/G5 Compliance
- Microsoft 365 A5/E5/F5/G5 eDiscovery and Audit
- Microsoft 365 A5/E5/F5/G5 Insider Risk Management
- Microsoft 365 A5/E5/F5/G5 Information Protection and Governance

## <a name="customer-key-for-microsoft-365"></a>Clave de cliente para Microsoft 365

Con la clave de cliente, controla las claves de cifrado de su organización y configura Microsoft 365 para usarlas para cifrar los datos en reposo en los centros de datos de Microsoft. En otras palabras, la clave de cliente le permite agregar una capa de cifrado que le pertenece, con sus propias claves. La clave de cliente proporciona compatibilidad de cifrado de datos en reposo para varias cargas Microsoft 365 [de](/microsoft-365/compliance/customer-key-overview#about-data-encryption-policies) trabajo a través Microsoft 365 servicio de cifrado de datos en reposo. Además, la clave de cliente proporciona cifrado para SharePoint online y OneDrive para la Empresa datos, así como Exchange Online nivel de buzón de correo.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de la clave de cliente al tener sus datos cifrados en reposo en la capa de aplicación mediante claves de cifrado proporcionadas, controladas y administradas por su propia organización.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance, Microsoft 365 F5 Security & Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance y Office 365 E5/A5/G5 proporcionan los derechos para que un usuario se beneficie de la clave de cliente. Para obtener todas las ventajas de la clave de cliente, también debe tener una suscripción a Azure Key Vault.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

El [artículo Configurar clave](/microsoft-365/compliance/customer-key-set-up) de cliente describe los pasos que debe seguir para crear y configurar los recursos de Azure necesarios y, a continuación, proporciona los pasos para configurar la clave de cliente.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Microsoft 365 servicio de datos en reposo que proporciona compatibilidad con cifrado de varias cargas de trabajo es un servicio de nivel de inquilino. Aunque algunos usuarios sin licencia pueden tener acceso técnicamente al servicio, se requiere una licencia para cualquier usuario que tenga la intención de beneficiarse del servicio. Para Exchange Online de nivel de buzón de correo, el buzón de usuario debe tener una licencia para asignar una directiva de cifrado de datos.

## <a name="data-connectors"></a>Conectores de datos

Microsoft proporciona conectores de datos de terceros que se pueden configurar en el Centro de cumplimiento de Microsoft 365. Para obtener una lista de conectores de datos proporcionados por Microsoft, consulte la [tabla Conectores](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) de datos de terceros. En esta tabla también se resumen las soluciones de cumplimiento que puede aplicar a datos de terceros después de importar y archivar datos en Microsoft 365 y vínculos a las instrucciones paso a paso para cada conector.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

La principal ventaja de usar conectores de datos para importar y archivar datos de terceros en Microsoft 365 es que puede aplicar varias soluciones de cumplimiento de Microsoft 365 a los datos después de importarlos. Esto ayuda a garantizar que los datos de su organización que no son de Microsoft cumplan con las normativas y estándares que afectan a su organización.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Las siguientes licencias proporcionan los derechos para que un usuario se beneficie de los conectores de datos:

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Info Protection &amp; Governance
- Microsoft 365 E5/A5/G5/F5 Compliance
- Microsoft 365 F5 Security & Compliance
- Microsoft 365 E5/A5/G5 Insider Risk Management
- Microsoft 365 E5/A5/G5 eDiscovery and Audit
- Office 365 E5/A5/G5

Para los conectores de datos del Centro de cumplimiento de seguridad de Microsoft 365 proporcionados por un partner de Microsoft, la organización necesitará una relación comercial con el partner antes de poder implementar &amp; dichos conectores.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

Los conectores se configuran mediante el Centro de &amp; seguridad y el Catálogo de conectores.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los servicios de Conectores de datos son un valor de nivel de inquilino. Todos los usuarios destinados a beneficiarse de este servicio deben tener licencia.

## <a name="data-classification-analytics-overview-content-amp-activity-explorer"></a>Análisis de clasificación de datos: Overview Content &amp; Activity Explorer

Las capacidades analíticas de clasificación de datos están disponibles Centro de cumplimiento de Microsoft 365 experiencia. Información general muestra las ubicaciones de contenido digital y los tipos y etiquetas de información confidencial más comunes presentes. El Explorador de contenido proporciona visibilidad sobre la cantidad y los tipos de datos confidenciales y permite a los usuarios filtrar por etiqueta o tipo de confidencialidad para obtener una vista detallada de las ubicaciones donde se almacenan los datos confidenciales. El Explorador de actividades muestra actividades relacionadas con etiquetas y datos confidenciales, como degradaciones de etiquetas o uso compartido externo que podrían exponer el contenido a riesgos.

El Explorador de actividades proporciona un único panel de cristal para que los administradores obtengan visibilidad sobre las actividades relacionadas con la información confidencial que usan los usuarios finales. Estos datos incluyen actividades de etiqueta, registros de prevención de pérdida de datos (DLP), etiquetado automático, DLP de extremo y mucho más.

El Explorador de contenido proporciona a los administradores la capacidad de indizar los documentos confidenciales almacenados en las cargas de trabajo Microsoft 365 compatibles e identificar la información confidencial que almacenan. Además, el Explorador de contenido ayuda a identificar documentos clasificados con etiquetas de confidencialidad y retención.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los administradores de protección de la información y cumplimiento pueden acceder al servicio para obtener acceso a estos registros y datos indizados para comprender dónde se almacenan los datos confidenciales y qué actividades están relacionadas con estos datos y las que realizan los usuarios finales.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Los usuarios con licencia de Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance, Microsoft 365 F5 Security & Compliance, Microsoft 365 E5/A5/G5 Information Protection Governance y Office 365 E5 pueden beneficiarse de los análisis de clasificación de datos de &amp; Microsoft 365.

Microsoft 365 E3/A3/G3 y Office 365 E3/A3/G3 permiten a los usuarios beneficiarse únicamente de la agregación de datos del Explorador de contenido.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características De introducción al contenido y al Explorador de actividades están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar análisis de clasificación de datos para usuarios con licencia, vea:

- **Explorador de contenido:** [introducción al explorador de contenido: Microsoft 365 cumplimiento | Microsoft Docs](/microsoft-365/compliance/data-classification-content-explorer).
- **Explorador de actividades:** introducción al explorador de actividades: Microsoft 365 [cumplimiento | Microsoft Docs](/microsoft-365/compliance/data-classification-activity-explorer).
- **Notas de la versión de clasificación de** datos: notas de la versión de clasificación de datos: Microsoft 365 [cumplimiento | Microsoft Docs](/microsoft-365/compliance/data-classification-pub-preview-relnotes).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Esta característica debe estar en el ámbito de los usuarios que usan activamente la solución en Microsoft 365 portal de cumplimiento.

## <a name="data-loss-prevention-for-teams"></a>Prevención de pérdida de datos para Teams

Con DLP de comunicación para Teams, las organizaciones pueden bloquear chats y canalizar mensajes que contienen información confidencial, como información financiera, información de identificación personal, información relacionada con el estado u otra información confidencial.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5/F5 Compliance y F5 Security & Compliance
- Microsoft 365 E5/A5/G5 Information Protection and Governance
- Office 365 E5/A5/G5

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los remitentes se benefician al tener información confidencial en el chat saliente y los mensajes de canal inspeccionados para obtener información confidencial, tal como se configura en la directiva DLP de la organización.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, Teams chat y los mensajes de canal son una ubicación *habilitada (carga* de trabajo) para estas características DLP para todos los usuarios del espacio empresarial. Para obtener más información acerca del uso de directivas DLP, vea [Overview of data loss prevention](/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores pueden personalizar ubicaciones (cargas de trabajo), usuarios incluidos y usuarios excluidos en el Centro de cumplimiento de seguridad, en Ubicaciones de prevención &amp; **de pérdida de**  >  **datos.**

## <a name="data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Prevención de pérdida de datos para Exchange Online, SharePoint Online y OneDrive para la Empresa

Con Office 365 prevención de pérdida de datos (DLP) para Exchange Online, SharePoint Online y OneDrive para la Empresa, las organizaciones pueden identificar, supervisar y proteger automáticamente información confidencial en correos electrónicos y archivos (incluidos los archivos almacenados en repositorios de archivos de Microsoft Teams).

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de DLP para Exchange Online, SharePoint Online y OneDrive para la Empresa cuando sus correos electrónicos y archivos se inspeccionan para obtener información confidencial, tal como se configura en la directiva DLP de la organización.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E3/A3/Business Premium, Office 365 E3/A3 y Office 365 Data Loss Prevention y F5 Compliance y F5 Security & Compliance proporcionan los derechos para que un usuario se beneficie de dlp de Office 365 para Exchange Online, SharePoint Online y OneDrive para la Empresa.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, Exchange Online correos electrónicos, SharePoint sitios y cuentas de OneDrive son ubicaciones *habilitadas (cargas* de trabajo) para estas características dlp para todos los usuarios del espacio empresarial. Para obtener más información acerca del uso de directivas DLP, vea [Overview of data loss prevention](/microsoft-365/compliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores pueden personalizar ubicaciones (cargas de trabajo), usuarios incluidos y usuarios excluidos en el Centro de cumplimiento de seguridad, en Ubicaciones de prevención &amp; **de pérdida de**  >  **datos.**

## <a name="double-key-encryption-for-microsoft-365"></a>Cifrado de clave doble para Microsoft 365

Double Key Encryption for Microsoft 365 permite proteger los datos altamente confidenciales para cumplir los requisitos especializados y mantener el control total de la clave de cifrado. Double Key Encryption usa dos claves para proteger los datos, con una clave en el control y la segunda clave almacenada de forma segura por Microsoft Azure. Para ver los datos, debe tener acceso a ambas claves. Dado que Microsoft solo puede tener acceso a una clave, la clave y también los datos no están disponibles para Microsoft, lo que garantiza que tenga control total sobre la privacidad y la seguridad de los datos.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician del cifrado de doble clave al poder migrar sus datos cifrados a la nube, lo que impide el acceso de terceros mientras la clave permanezca en control de los usuarios. Los usuarios pueden proteger y consumir contenido cifrado de doble clave similar a cualquier otro contenido protegido con etiquetas de confidencialidad.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance y F5 Security & Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance, Office 365 E5/A5/G5 y EMS E5 proporcionan los derechos para que un usuario se beneficie del cifrado de clave doble.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

Double Key Encryption admite la versión de escritorio de Microsoft Office para Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Para asignar claves de cifrado a datos de una organización Office 365 o Microsoft 365 para usuarios con licencia, siga las instrucciones de implementación de cifrado de clave doble.

## <a name="ediscovery"></a>eDiscovery

eDiscovery proporciona soluciones de investigación y exhibición de documentos electrónicos para que los departamentos de TI y jurídicos de las corporaciones identifiquen, recopile, conserven, reduzcan y revisen el contenido relacionado con una investigación o litigio antes de exportarlo fuera del sistema Microsoft 365.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Un usuario se beneficia de Advanced eDiscovery cuando se selecciona al usuario como administrador de datos (una persona que tiene el control administrativo de un documento o archivo electrónico) para un caso.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3 y F5 Cumplimiento y Cumplimiento de F5 Seguridad & Compliance proporcionan los derechos para que un usuario se beneficie de la exhibición de documentos electrónicos principal.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance y F5 Security & Compliance, Microsoft 365 E5/A5/G5 eDiscovery and Audit y Office 365 E5/A5/G5 proporcionan los derechos para que un usuario se beneficie de Advanced eDiscovery.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, Advanced eDiscovery características están habilitadas en el nivel de inquilino para todos los usuarios del inquilino cuando los administradores asignan permisos de exhibición de documentos electrónicos en el Centro de &amp; cumplimiento de seguridad.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores de exhibición de documentos electrónicos pueden seleccionar usuarios específicos como custodios de datos para un caso mediante la herramienta de administración de custodia integrada en Advanced eDiscovery, tal como se describe en Agregar [custodios](/microsoft-365/compliance/add-custodians-to-case)a un caso Advanced eDiscovery .

## <a name="information-barriers"></a>Barreras de información

Las barreras de información son directivas que un administrador puede configurar para impedir que individuos o grupos se comuniquen entre sí. Esto es útil si, por ejemplo, un departamento administra información que no debe compartirse con otros departamentos o si es necesario impedir que un grupo se comunique con contactos externos. Las directivas de barrera de información también impiden las búsquedas y la detección. Esto significa que si intenta comunicarse con alguien con quien no debe comunicarse, no encontrará ese usuario en el selector de personas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de las capacidades avanzadas de cumplimiento de las barreras de información cuando están restringidos a comunicarse con otros usuarios. Las directivas de barreras de información se pueden definir para impedir que determinados segmentos de usuarios se comuniquen con cada uno o permitir que segmentos específicos se comuniquen solo con ciertos otros segmentos. Para obtener más información sobre cómo definir directivas de barrera de información, vea [Definir directivas de barrera de información.](/microsoft-365/compliance/information-barriers-policies) Para escenarios en los que dos grupos no se pueden comunicar entre sí, los usuarios de ambos grupos requieren una licencia para beneficiarse del servicio (vea el ejemplo siguiente).<br><br>

| Escenario | Quién Requiere una licencia? |
|:------|:------|
| Dos grupos (grupo 1 y grupo 2) no se pueden comunicar entre sí (es decir, los usuarios del grupo 1 tienen restringida la comunicación con los usuarios del grupo 2 y los usuarios del grupo 2 tienen restricciones para comunicarse con los usuarios del grupo &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 1. | Usuarios del grupo &nbsp; 1 y del &nbsp; grupo 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance y F5 Security & Compliance, Microsoft 365 E5/A5/G5 Insider Risk Management y Office 365 E5/A5/G5, proporcionan los derechos para que un usuario se beneficie de las barreras de información.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

Los administradores crean y administran directivas de barrera de información mediante cmdlets de PowerShell en el Centro de &amp; seguridad y cumplimiento. A los administradores se les debe asignar Microsoft 365 Enterprise administrador global, Office 365 global o administrador de cumplimiento para crear una directiva de barrera de información. De forma predeterminada, estas directivas se aplican a todos los usuarios del espacio empresarial. Para obtener más información acerca de las barreras de información, vea [Information barriers in Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores pueden personalizar ubicaciones (cargas de trabajo), usuarios incluidos y usuarios excluidos en el Centro de &amp; cumplimiento de seguridad. Por ejemplo, si todos los usuarios tienen licencia para Office 365 E3 y ninguno tiene licencia para Cumplimiento avanzado de Office 365/E5, no tendrían que crear directivas de barrera de información para la organización. Para más información, vea [Barreras de información en Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams).

## <a name="information-protection"></a>Protección de la información

Information Protection ayuda a las organizaciones a detectar, clasificar, etiquetar y proteger documentos y correos electrónicos confidenciales. Los administradores pueden definir reglas y condiciones para aplicar etiquetas automáticamente, los usuarios pueden aplicar etiquetas manualmente o se puede usar una combinación de las dos, donde los usuarios reciben recomendaciones sobre cómo aplicar etiquetas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician al tener la capacidad de aplicar manualmente etiquetas de confidencialidad a su contenido o al clasificar su contenido automáticamente.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Cumplimiento F5 y F5 Seguridad & Cumplimiento, Enterprise Mobility + Security E3/E5, M365 E5/A5/G5, Office 365 E5/A5/E3/A3/F3, AIP Plan 1 y AIP Plan 2 proporcionan los derechos para que un usuario se beneficie de la etiqueta de confidencialidad manual.

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium y Enterprise Mobility + Security E3/E5, AIP Plan 1 y AIP Plan 2 y F5 Compliance y F5 Security & Compliance proporcionan los derechos para que un usuario se beneficie de la aplicación y visualización de etiquetas de confidencialidad en Power BI y para proteger los datos cuando es exportada de Power BI a Excel, PowerPoint o PDF.

Microsoft 365 Empresa Premium y Enterprise Mobility proporcionan los derechos para usar el módulo [de PowerShell de AIPService](/powershell/azure/aip/overview#aipservice) para administrar el servicio de protección de Azure Rights Management para Azure Information Protection.

> [!NOTE]
> Power BI se incluye con Microsoft 365 E5/A5/G5; en todos los demás planes, Power BI tener licencia por separado.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance y F5 Security & Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance, Office 365 E5, Enterprise Mobility + Security E5/A5/G5 , y el Plan 2 de AIP proporcionan los derechos para que un usuario se beneficie del etiquetado de confidencialidad automático.

Information Protection no incluye derechos a la clasificación automática en función Machine Learning (clasificadores que se pueden entrenar).

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de protección de la información están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar directivas para usuarios con licencia, vea Activating Azure Rights Management.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Excepto cuando se usa la característica de escáner AIP, las directivas pueden tener ámbito para grupos o usuarios y registros específicos que se pueden editar para evitar que los usuarios sin licencia ejecuten características de clasificación o etiquetado.

Para la característica de escáner AIP, Microsoft no se compromete a proporcionar capacidades de clasificación, etiquetado o protección de archivos a los usuarios que no tienen licencia.

Para obtener más información, vea [Create and publish sensitivity labels](/microsoft-365/compliance/create-sensitivity-labels#publish-sensitivity-labels-by-creating-a-label-policy) y Understanding the Azure Information Protection unified [labeling scanner](/azure/information-protection/deploy-aip-scanner).

## <a name="information-governance"></a>Gobierno de la información

Information Governance ayuda a las organizaciones a administrar sus riesgos mediante el descubrimiento, la clasificación, el etiquetado y la administración de sus datos. Information Governance permite a las organizaciones cumplir los requisitos normativos y empresariales, así como reducir su superficie de ataque al proporcionar capacidades de retención y eliminación en sus Microsoft 365 datos de terceros.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician al poder clasificar los datos con fines de retención para cumplir las directivas y normativas específicas.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 F3/Business Premium, Office 365 E5/A5/G5/E3/A3/G3/E1/A1/G1/F3 y planes de Exchange independientes proporcionan los derechos para que un usuario se beneficie de la aplicación manual de etiquetas de retención sin registro a los datos del buzón.

Microsoft 365 F3/F1/Business Premium, Office 365 E5/A5/G5/E3/A3/G3/F3/E1/A1/G1 y planes de SharePoint independientes proporcionan los derechos para que un usuario se beneficie de la aplicación manual de etiquetas de retención sin registro a archivos de SharePoint o OneDrive.

Microsoft 365 E5/A5/G5/E3/A3/Business Premium, Office 365 E5/A5/G5/E3/A3, plan 2 de Exchange y Archivado de Exchange Online proporcionan los derechos para que un usuario se beneficie de una directiva básica de retención de buzones en toda la organización o en toda la ubicación.

Microsoft 365 E5/A5/G5/E3/A3, Office 365 E5/A5/G5/E3/A3 y SharePoint Plan 2 proporcionan los derechos para que un usuario se beneficie de una directiva de retención básica de SharePoint o OneDrive o para aplicar manualmente una etiqueta de retención sin registro a archivos de SharePoint o OneDrive.

Las organizaciones pueden usar directivas de retención para mantener o eliminar Teams de acuerdo con sus directivas. Esto incluye la administración de mensajes en Teams chats y conversaciones.

Las siguientes licencias proporcionan los derechos para que un usuario se beneficie de una Teams de retención:

- Microsoft 365 E5/G5/A5/E3/G3/A3/F3/F1, Business Basic, Business Standard y Business Premium
- Office 365 E5/G5/A5/E3/G3/A3/F3/E1/G1

Para los usuarios con las siguientes licencias, el período mínimo de retención o eliminación admitido es de 30 días:

- Microsoft 365 F1/F3, Business Basic, Business Standard y Business Premium
- Office 365 E1/G1 y F3

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance y F5 Security & Compliance, Microsoft 365 Information Protection and Governance E5/A5/G5 y Office 365 E5/A5 proporcionan los derechos para que un usuario se beneficie de aplicar automáticamente etiquetas o directivas de retención, aplicar la retención predeterminada etiquetas o directivas, iniciando el período de retención de una etiqueta de retención basada en un evento personalizado, desencadenando una revisión manual de disposición al final del período de retención de la etiqueta, importando datos de terceros a través de conectores de datos nativos, declarando un archivo un registro, descubriendo contenido etiquetado y supervisando la actividad de etiquetado.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance y F5 Security & Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance proporcionan los derechos para que un usuario se beneficie de la aplicación automática de etiquetas de retención basadas en clasificadores capacitados.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de Gobierno de información están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar Information Governance para aplicar la etiqueta automática y las directivas para los usuarios con licencia, consulte [Microsoft Information Governance in Microsoft 365](/microsoft-365/compliance/manage-information-governance).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Las características de Gobierno de la información se pueden aplicar a usuarios con licencia en ubicaciones específicas (sitios de grupo, sitios de grupo, etc.). Para obtener información sobre cómo configurar Information Governance para aplicar la etiqueta automática y las directivas para los usuarios con licencia, consulte [Microsoft Information Governance in Microsoft 365](/microsoft-365/compliance/manage-information-governance).

## <a name="insider-risk-management"></a>Administración de riesgos de Insider

La administración de riesgos de Insider es una solución en Microsoft 365 que ayuda a minimizar los riesgos internos al permitirle detectar, investigar y tomar medidas en actividades de riesgo en su organización.

Las directivas personalizadas le permiten detectar y tomar medidas en actividades malintencionadas e involuntariamente arriesgadas en su organización, incluido el aumento de casos a Microsoft Advanced eDiscovery, si es necesario. Los analistas de riesgos de la organización pueden tomar rápidamente las acciones adecuadas para asegurarse de que los usuarios cumplen con los estándares de cumplimiento de la organización.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician al tener sus actividades supervisadas en busca de riesgos.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance y F5 Security & Compliance y Microsoft 365 E5/A5/G5 Insider Risk Management proporcionan los derechos para que un usuario se beneficie de la administración de riesgos de Insider.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

Las directivas de administración de riesgos de Insider deben crearse en el Centro de cumplimiento de Microsoft 365 y asignarse a los usuarios.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Al crear una directiva en el Centro de cumplimiento de Microsoft 365, en la página  Elegir usuarios y grupos, seleccione Elegir usuarios o grupos para seleccionar  solo usuarios con licencia o, si todos los usuarios tienen licencia, puede activar la casilla Todos los usuarios y grupos habilitados para correo.  Para obtener más información, vea [Introducción a la administración de riesgos de insider](/microsoft-365/compliance/insider-risk-management-configure).

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender for Identity

Microsoft Defender for Identity (anteriormente Azure Advanced Threat Protection) es un servicio en la nube que ayuda a proteger los entornos híbridos empresariales de varios tipos de ciberataques avanzados dirigidos y amenazas internas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los analistas y profesionales de seguridad de SecOp se benefician de la capacidad de Microsoft Defender for Identity para detectar e investigar amenazas avanzadas, identidades comprometidas y acciones malintencionadas de insider. Los usuarios finales se benefician al tener sus datos supervisados por Microsoft Defender for Identity.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Security, Microsoft F5 Security & Compliance y Microsoft Defender for Identity for Users proporcionan los derechos para beneficiarse de Microsoft Defender for Identity.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de Microsoft Defender para Identity están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar Azure ATP, consulte [Create your Microsoft Defender for Identity instance](/defender-for-identity/install-step1).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los servicios de Microsoft Defender for Identity actualmente no son capaces de limitar las capacidades para usuarios específicos. Debe licenciar todos los usuarios que desea beneficiar.

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender para Office 365

Microsoft Defender para Office 365 (anteriormente Office 365 protección contra amenazas avanzada) ayuda a proteger a las organizaciones contra ataques sofisticados como phishing y malware de día cero. Microsoft Defender para Office 365 también proporciona información útil al correlacionar las señales de una amplia gama de datos para ayudar a identificar, priorizar y proporcionar recomendaciones sobre cómo abordar amenazas potenciales.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Microsoft Defender para Office 365 protege a los usuarios de ataques sofisticados como phishing y malware de día cero. Para obtener la lista completa de servicios proporcionados en plan 1 y plan 2, vea [Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio? 

Los planes 1 y 2 de Microsoft Defender para Office 365, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Security, Microsoft 365 F5 Security & Compliance y Microsoft 365 Empresa Premium proporcionan los derechos para que un usuario se beneficie de Microsoft Defender para Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de Microsoft Defender Office 365 están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar Microsoft Defender para Office 365 directivas para usuarios con licencia, vea [Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Para ámbito de Microsoft Defender para Office 365, siga las directivas de implementación Caja fuerte vínculos y Caja fuerte datos adjuntos:

- Para obtener información sobre cómo configurar Caja fuerte para usuarios con licencia, vea [Caja fuerte Links in Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

- Para obtener información sobre cómo configurar Caja fuerte datos adjuntos para usuarios con licencia, consulte [Caja fuerte Attachments in Microsoft Defender para Office 365](/microsoft-365/security/office-365-security/atp-safe-attachments).

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) es una solución de Cloud Access Security Broker (CASB) que proporciona a las organizaciones visibilidad de sus aplicaciones y servicios en la nube, proporciona análisis sofisticados para identificar y combatir las amenazas cibernéticas y les permite controlar cómo se desplazan los datos a través de cualquier aplicación en la &mdash; nube.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

MCAS detecta y evalúa shadow IT, proporciona protección contra amenazas en aplicaciones en la nube de primera y de terceros y protege la información en aplicaciones en la nube de primera y de terceros.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Enterprise Mobility + Security E5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Security, Microsoft 365 E5/A5/G5/F5 Compliance, Microsoft 365 F5 Security & Compliance y Microsoft 365 Information Protection and Governance proporcionan los derechos para que un usuario se beneficie de MCAS.

Azure AD P1 proporciona los derechos para que un usuario se beneficie de las funcionalidades de detección en MCAS.

Para beneficiarse de las funciones de control de aplicaciones de acceso condicional en MCAS, los usuarios también deben tener licencia para Azure Active Directory P1, que se incluye en Enterprise Mobility + Security F1/F3/E3/A3/G3, Enterprise Mobility + Security E5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 y Microsoft 365 E5/A5/G5/F5 Security y Microsoft 365 F5 Security & Compliance.

Para beneficiarse del etiquetado automático del lado cliente, los usuarios deben tener licencia para Azure Information Protection P2, que se incluye en Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance, Microsoft 365 F5 Security & Cumplimiento y Microsoft 365 protección de la información y gobierno.

> [!NOTE]
> El etiquetado automático del lado servidor requiere Information Protection para Office 365- Premium licencias ( `MIP_S_CLP2` o `efb0351d-3b08-4503-993d-383af8de41e3` ). Para obtener referencia, vea [Nombres de productos e identificadores del plan de servicio para licencias](/azure/active-directory/enterprise-users/licensing-service-plan-reference).

Para obtener más información, vea [el Microsoft Cloud App Security de datos de licencias .](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de MCAS están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial.

Para obtener información sobre cómo configurar Microsoft Cloud App Security para usuarios con licencia, vea [Microsoft Cloud App Security información general.](/cloud-app-security/what-is-cloud-app-security)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores pueden establecer el ámbito de las implementaciones de MCAS a usuarios con licencia mediante las funcionalidades de implementación de ámbito disponibles en el servicio. Para obtener más información, vea [Scoped deployment](/cloud-app-security/scoped-deployment).

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender para punto de conexión

Microsoft Defender para endpoint (anteriormente ATP de Microsoft Defender) es una solución de seguridad de puntos de conexión que incluye administración de vulnerabilidades y evaluación; capacidades de reducción de superficie de ataque; protección de próxima generación basada en el comportamiento y basada en la nube; detección y respuesta de puntos de conexión (EDR); investigación y corrección automáticas; y servicios de búsqueda administrados. Consulta [la página Microsoft Defender para endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) para obtener más información.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Windows 10 Enterprise E5, Windows 10 Education A5, Microsoft 365 E5/G5, que incluye Windows 10 Enterprise E5, Microsoft 365 E5/A5/G5/F5 Security y Microsoft 365 F5 Security & Compliance pueden beneficiarse de Microsoft Defender para Endpoint.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los analistas y profesionales de seguridad de SecOps se benefician de las capacidades de seguridad de puntos de conexión de Microsoft Defender para Endpoint para realizar protección preventiva, detección posterior a la infracción, investigación automatizada y respuesta a amenazas avanzadas. Los usuarios finales se benefician al tener eventos malintencionados supervisados por Microsoft Defender para endpoint.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de Microsoft Defender para endpoint están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre la implementación, vea [Deployment phases](/windows/security/threat-protection/microsoft-defender-atp/deployment-phases).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores de Microsoft Defender para puntos de conexión pueden usar el control de acceso basado en roles (RBAC) para crear roles y grupos en el equipo de operaciones de seguridad para conceder acceso adecuado a la Centro de seguridad de Microsoft Defender. Para obtener más información, vea [Manage portal access using role-based access control](/windows/security/threat-protection/microsoft-defender-atp/rbac).

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp-and-for-teams-export"></a>API de Microsoft Graph para Teams prevención de pérdida de datos (DLP) y para Teams Export

Estas API permiten a los desarrolladores crear aplicaciones de seguridad y cumplimiento que pueden "escuchar" mensajes de Microsoft Teams en tiempo casi real o exportar mensajes de equipos en 1:1/chat de grupo o canales Teams grupo. Estas API habilitan DLP y otros escenarios de protección de la información y gobierno para clientes e ISV. Además, la API Graph patch de Microsoft permite aplicar acciones DLP a Teams mensajes.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

[Las capacidades de](/microsoft-365/compliance/dlp-microsoft-teams) prevención de pérdida de datos (DLP) se usan ampliamente en Microsoft Teams, especialmente a medida que las organizaciones se han desplazado al trabajo remoto. Si su organización tiene DLP, ahora puede definir directivas que impidan que las personas compartan información confidencial en un canal Microsoft Teams sesión de chat.

La protección de la información y las capacidades de gobierno se usan ampliamente en Microsoft Teams, especialmente a medida que las organizaciones se han desplazado al trabajo remoto. Con [Teams Export API,](/microsoftteams/export-teams-content)los datos se pueden exportar a una aplicación de archivado de cumplimiento o exhibición de documentos electrónicos de terceros para garantizar que se cumplan las prácticas de cumplimiento.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

El acceso a la API se configura en el nivel de inquilino.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Las API Graph microsoft para Teams DLP y Teams Export proporcionan un valor de nivel de inquilino. Todos los usuarios destinados a beneficiarse de este servicio deben tener licencia. Como valor agregado, estamos agregando capacidad de eded por usuario con licencia, calculado por mes y agregado en el nivel de inquilino. Para el uso más allá de la capacidad de eded, los propietarios de la aplicación se facturarán por el consumo de API.

Para obtener más información sobre la capacidad de eded y las tarifas de [consumo, vea Graph requisitos para obtener acceso a los mensajes de chat.](/graph/teams-licenses)

## <a name="office-365-advanced-message-encryption"></a>Cifrado de mensajes avanzado de Office 365

Cifrado de mensajes avanzado de Office 365 ayuda a los clientes a cumplir las obligaciones de cumplimiento que requieren controles más flexibles sobre los destinatarios externos y su acceso a correos electrónicos cifrados. Con el cifrado de mensajes avanzado, los administradores pueden controlar los correos electrónicos confidenciales compartidos fuera de la organización mediante directivas automáticas que pueden detectar tipos de información confidencial (por ejemplo, identificar personalmente información o identificadores financieros o de estado), o pueden usar palabras clave para mejorar la protección aplicando plantillas de correo electrónico personalizadas y expirando el acceso a correos electrónicos cifrados a través de un portal web seguro. Además, los administradores pueden controlar aún más los correos electrónicos cifrados a los que se accede externamente a través de un portal web seguro revocando el acceso en cualquier momento.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los remitentes de mensajes se benefician del control agregado sobre los correos electrónicos confidenciales proporcionados por el cifrado de mensajes avanzado.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance and F5 Security & Compliance, y Microsoft 365 E5/A5/G5 Information Protection and Governance proporcionan los derechos para que un usuario se beneficie del cifrado avanzado de mensajes.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

Los administradores crean y administran directivas de cifrado de mensajes avanzados en el centro de administración Exchange en **Reglas de flujo de**  >  **correo**. De forma predeterminada, estas reglas se aplican a todos los usuarios del espacio empresarial. Para obtener más información acerca de cómo configurar nuevas funcionalidades de cifrado de mensajes, vea [Configurar nuevas Cifrado de mensajes de Office 365 de cifrado.](/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores deben aplicar reglas de flujo de correo para el cifrado de mensajes avanzado solo a los usuarios con licencia. Para obtener más información acerca de la definición de reglas de flujo de correo, vea [Define mail flow rules to encrypt email messages in Office 365](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) es un subconjunto de Microsoft Cloud App Security, con características limitadas a Office 365 y sin seguridad adicional para aplicaciones en la nube de terceros y servicios iaaS.

OCAS proporciona a las organizaciones visibilidad de sus servicios y aplicaciones en la nube de productividad, proporciona análisis sofisticados para identificar y combatir las amenazas cibernéticas y les permite controlar cómo se desplazan los datos a &mdash; través de Office 365.

Para comparar características, vea [Diferencias entre Microsoft Cloud App Security y Office 365 Cloud App Security](/cloud-app-security/editions-cloud-app-security-o365).

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

OCAS detecta Shadow IT, proporciona protección contra amenazas en Office 365 y puede controlar qué aplicaciones tienen permiso para obtener acceso a los datos.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Office 365 E5/A3/A5/G5 proporcionan los derechos para que un usuario se beneficie de OCAS.
Para obtener más información, vea [el Microsoft Cloud App Security de datos de licencias .](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de OCAS están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial.

Para obtener información sobre cómo configurar el servicio, vea [Configuración básica para Cloud App Security](/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores pueden establecer el ámbito de las implementaciones de OCAS para exigir cómo se accede a determinadas aplicaciones y limitar los grupos de usuarios supervisados por Office 365 Cloud App Security. Para obtener más información, vea [Scoped deployment](/cloud-app-security/scoped-deployment).

## <a name="office-365-customer-lockbox"></a>Caja de seguridad del cliente de Office 365

La caja de seguridad del cliente proporciona una capa adicional de control al ofrecer a los clientes la capacidad de dar autorización explícita de acceso para las operaciones de servicio. Al demostrar que hay procedimientos para la autorización explícita de acceso a datos, la caja de seguridad del cliente también puede ayudar a las organizaciones a cumplir determinadas obligaciones de cumplimiento, como HIPAA y FedRAMP.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Caja de seguridad del cliente garantiza que nadie de Microsoft pueda acceder al contenido del cliente para realizar una operación de servicio sin la aprobación explícita del cliente. Caja de seguridad del cliente lleva al cliente al flujo de trabajo de aprobación para que las solicitudes accedan a su contenido. En ocasiones, los ingenieros de Microsoft participan durante el proceso de soporte técnico para solucionar problemas notificados por el cliente. En la mayoría de los casos, los problemas se solucionan a través de extensas herramientas de telemetría y depuración que Microsoft tiene en sus servicios. Sin embargo, puede haber casos que requieran que un ingeniero de Microsoft acceda al contenido del cliente para determinar la causa raíz y solucionar el problema. La Caja de seguridad del cliente requiere que el ingeniero solicite acceso al cliente como un último paso en el flujo de trabajo de aprobación. Esto ofrece a las organizaciones la opción de aprobar o denegar estas solicitudes, lo que les da control directo sobre si un ingeniero de Microsoft puede acceder a los datos del usuario final de la organización.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance and F5 Security & Compliance, y Microsoft 365 E5/A5/G5 Insider Risk Management proporcionan los derechos para que un usuario se beneficie de la caja de seguridad del cliente.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

Los administradores pueden activar la caja de seguridad del cliente en el Centro de administración de Microsoft 365. Para obtener más información, [vea Customer Lockbox in Office 365](/microsoft-365/compliance/customer-lockbox-requests). Cuando la caja de seguridad del cliente está activada, Microsoft debe obtener la aprobación de una organización antes de acceder a cualquiera de sus contenidos.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Actualmente, el servicio de caja de seguridad del cliente no puede limitarse a usuarios específicos. Aunque actualmente los servicios de inquilino no son capaces de limitar las ventajas para usuarios específicos, se deben realizar esfuerzos para limitar las ventajas del servicio a los usuarios con licencia. Esto ayudará a evitar posibles interrupciones del servicio una vez que estén disponibles las capacidades de destino.

## <a name="office-365-message-encryption"></a>Cifrado de mensajes de Office 365

El cifrado de mensajes de Office 365 (OME) es un servicio basado en Azure Rights Management (Azure RMS) que permite enviar correo electrónico cifrado a otras personas dentro o fuera de la organización, independientemente de la dirección de correo electrónico de destino (Gmail, Yahoo! Mail, Outlook.com, etc.).

Para ver los mensajes cifrados, los destinatarios pueden obtener un código de acceso único, iniciar sesión con una cuenta de Microsoft, o iniciar sesión con una cuenta profesional o educativa asociada a Office 365. Los destinatarios también pueden enviar respuestas cifradas. No necesitan una suscripción para ver mensajes cifrados o enviar respuestas cifradas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los remitentes de mensajes se benefician del control agregado sobre los correos electrónicos confidenciales proporcionados por Cifrado de mensajes de Office 365.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E3/A3/G3, Office 365 E3/A3/G3 y Azure Information Protection Plan 1 proporcionan los derechos para que un usuario se beneficie de Cifrado de mensajes de Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

Los administradores crean y administran directivas Cifrado de mensajes de Office 365 en el Centro de administración de Exchange en **Reglas de flujo de**  >  **correo**. De forma predeterminada, estas reglas se aplican a todos los usuarios del espacio empresarial. Para obtener más información acerca de cómo configurar nuevas Cifrado de mensajes de Office 365, vea [Configurar nuevas capacidades de cifrado de mensajes](/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores deben aplicar reglas de flujo de correo Cifrado de mensajes de Office 365 solo a los usuarios con licencia. Para obtener más información acerca de cómo definir reglas de flujo de correo, vea Definir reglas de flujo de correo [para cifrar mensajes de correo electrónico.](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="privileged-access-management-in-office-365"></a>Administración de acceso privilegiado en Office 365

[La administración de acceso con privilegios (PAM)](/microsoft-365/compliance/privileged-access-management-configuration) proporciona control de acceso granular sobre las tareas de administración con privilegios en Office 365. Después de habilitar PAM, para completar tareas con privilegios elevados y privilegiados, los usuarios tendrán que solicitar acceso just-in-time a través de un flujo de trabajo de aprobación con un ámbito alto y con límite de tiempo.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Habilitar PAM permite que las organizaciones funcionen con privilegios permanentes cero. Los usuarios se benefician de la capa de defensa agregada frente a las vulnerabilidades derivadas del acceso administrativo permanente que proporciona acceso sin problemas a sus datos.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio? 

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5/F5 Compliance y F5 Security & Compliance, y Microsoft 365 E5/A5 Information Protection and Governance proporcionan los derechos para que un usuario se beneficie de PAM.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de PAM están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar directivas de PAM, vea [Introducción a la administración de acceso con privilegios.](/microsoft-365/compliance/privileged-access-management-configuration)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los clientes pueden administrar PAM por usuario a través de directivas de acceso y grupos de aprobadores, que se pueden aplicar a los usuarios con licencia. Para obtener más información, vea [Privileged access management in Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="records-management"></a>Records Management

Administración de registros ayuda a las organizaciones a cumplir sus obligaciones de mantenimiento de registros normativos y empresariales mediante la detección, clasificación, etiquetado, retención y capacidades de eliminación defendibles en sus Microsoft 365 datos de terceros.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance y F5 Security & Compliance, Microsoft 365 Information Protection and Governance E5/A5/G5 y Office 365 E5/A5/G5 proporcionan los derechos para que un usuario se beneficie de la Administración de registros, incluida la declaración de elementos como registros o registros reglamentarios, aplicar automáticamente etiquetas de retención o registro y ejecutar procesos de revisión de disposición (excluyendo aplicar automáticamente una etiqueta de retención basada en clasificadores capacitados).

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance y F5 Security & Compliance y Microsoft 365 Information Protection and Governance proporcionan los derechos para que un usuario se beneficie de aplicar automáticamente etiquetas de retención o registros basadas en clasificadores capacitados.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician al poder declarar el contenido como un registro y administrar su proceso de registros completos desde la definición de directiva y la declaración a través de eliminación defendible.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de administración de registros están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar la administración de registros para aplicar a usuarios con licencia, vea [Learn about records Management in Microsoft 365](/microsoft-365/compliance/records-management).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Las características de administración de registros se pueden aplicar a usuarios con licencia en ubicaciones específicas (sitios de grupo, sitios de grupo, etc.). Para obtener información sobre cómo configurar la administración de registros para aplicar a usuarios con licencia, vea [Learn about records Management in Microsoft 365](/microsoft-365/compliance/records-management).
