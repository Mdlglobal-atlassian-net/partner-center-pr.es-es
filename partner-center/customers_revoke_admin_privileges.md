---
title: Los clientes delegan privilegios administrativos en los partners | Centro de partners
ms.topic: article
ms.date: 12/18/2018
description: Como asociado de distribuidor, el cliente puede delegar a su administrador. También pueden quitar privilegios.
author: LauraBrenner
ms.author: labrenne
keywords: privilegios de administrador delegado, administrador en nombre de, quitar privilegios, DAP, AOBO
ms.localizationpriority: medium
ms.openlocfilehash: 9253bcca2d93d9f0d62d6d7241132f0c0c9bf5ec
ms.sourcegitcommit: b1ab80345b4e4af649fb8cc51d96d798e0791ade
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "62135455"
---
# <a name="customers-delegate-administration-privileges-to-partners"></a>Los clientes delegan privilegios administrativos en los partners

**Se aplica a**

-  Centro de partners

Para administrar la suscripción o el servicio de un cliente en su nombre, el cliente debe conceder permisos de administrador de dicho servicio. Para obtener los permisos de administrador de un cliente, envíale un correo electrónico con una solicitud de relación de revendedor. Cuando el cliente apruebe la solicitud, podrás iniciar sesión en el portal de administración del servicio y administrar el servicio en nombre del cliente. 

## <a name="invite-a-customer-to-establish-a-reseller-relationship-with-you"></a>Invitar a un cliente a establecer una relación de distribuidor contigo

1.  Seleccione **clientes** y, a continuación, seleccione **solicitar una relación de revendedor**.

2.  En la siguiente página, revisa el borrador del mensaje de correo electrónico. Puedes abrir el borrador de mensaje de correo electrónico en la aplicación de mensajería predeterminada o puedes copiar el mensaje en el portapapeles y pegarlo en un correo electrónico. 

    >[!IMPORTANT]
    >Puedes editar el texto en el correo electrónico, pero asegúrate de incluir el vínculo, ya que se trata de un vínculo personalizado que conecta al cliente directamente con tu cuenta. 
    
3.  Selecciona **Listo** cuando hayas completado este paso.

4.  Envía el correo electrónico a tu cliente.

5.  Una vez que el cliente acepte tu invitación, aparecerá en la página **Clientes** y, podrás aprovisionar y administrar el servicio para el cliente desde allí.

6.  Para administrar la cuenta del cliente, servicios, los usuarios y licencias, expanda el registro del cliente, seleccione la flecha abajo junto a su nombre y, a continuación, seleccione el portal de administración para el servicio que desea administrar.

>[!IMPORTANT]  
>Los clientes pueden volver a asignar o quitar permisos de administrador en el portal de administración de un servicio. Sin embargo, a no ser que hayas renegociado tu acuerdo con el cliente, continúas siendo el responsable de proporcionar al cliente soporte técnico y de cumplir con los términos del acuerdo de revendedor en la nube, incluso después de que el cliente reasigne o elimine los permisos de administrador. En esta situación, si el cliente necesita ayuda, póngase en contacto con soporte técnico de Microsoft para abrir una solicitud de servicio en nombre del cliente.

Los clientes pueden averiguar cuál de sus socios tienen privilegios de administrador para su inquilino de en el portal de administración de Office 365. Para ello:

1. El cliente debe iniciar sesión en el portal de administración de Office 365 como administrador Global.

2. Selecciona **Configuración** → **Relaciones con partners**.

3. En el **relaciones de asociados** página, el cliente verá una lista de los socios con los que trabajan y aquellos que se han concedido privilegios de administración puede delegar a su inquilino.

## <a name="customers-can-manage-a-partners-delegated-admin-privileges"></a>Los clientes pueden administrar los privilegios de administrador delegados en un partner 

El cliente puede decidir quitar sus privilegios de administrador delegado de su inquilino, pero conservar la relación con usted para fines de renovación de licencia y la suscripción. Los clientes administran los derechos y permisos de sus cuentas de Office 365 en la página **Relaciones con los partners** del Centro de administración de Office 365. En esta página, los clientes pueden:

- Consultar los partners con los que tienen una relación y qué partners han delegado privilegios de administrador

- Quitar los privilegios de administrador delegado de un partner para el inquilino

Quitar los privilegios de administración delegados de un partner:

1. En la página **Relaciones de partners**, selecciona el partner de interés.
2. En el panel de detalles, selecciona **Quitar administrador delegado**.
3. En el panel de confirmación, seleccione **Quitar**.

>[!IMPORTANT]  
>Las asignaciones de roles de Azure AD al partner son implícitas. Si intentas enumerar los miembros de los roles de Azure AD mediante Portal/PowerShell/Graph de Azure AD, no aparecerá el partner. Para averiguar si los socios están asignados a roles de Azure AD, debes hacer referencia a la página de relaciones con partners del Portal de administración de Office 365, para averiguar si el privilegio de administrador delegado se ha concedido al partner o no.

## <a name="delegated-admin-privileges-in-azure-ad"></a>Privilegios de administrador delegado en Azure AD 

Hay dos grupos de seguridad, agentes de administración y agentes del departamento de soporte técnico, en el inquilino de Azure AD, que se usan para administración delegada. Cuando un cliente concede el privilegio de administración delegada a un partner:

- El grupo de agentes de administración se asigna a la función de administrador global en el inquilino de Azure AD del cliente.

- El grupo de agentes del departamento de soporte técnico se asigna a la función de administrador del departamento de soporte técnico en el inquilino de Azure AD del cliente.

En función de los roles de directorio asignados, los miembros de ambos grupos pueden iniciar sesión en el inquilino de Azure AD del cliente y en los servicios de O365, con sus credenciales de partner y administrador, en nombre del cliente.

Si el cliente quita privilegios de administrador delegado, se quitan las asignaciones de rol de Azure AD y ya no podrás administrar el inquilino de Azure AD del cliente.

### <a name="azure-subscriptions-and-resource-management"></a>Suscripciones de Azure y administración de recursos

Cada suscripción de Azure tiene su propio conjunto de roles de administración de recursos. Para que un partner de CSP pueda administrar una suscripción de Azure de un cliente, el partner debe estar asignado a uno o más roles en la suscripción de Azure. Concretamente:

- Cuando un cliente acepta una invitación de un revendedor y concede privilegio de administración delegada a un partner, este último no obtiene automáticamente acceso a las suscripciones de Azure existentes en el inquilino del cliente.

- Cuando el partner CSP aprovisiona una nueva suscripción de Azure para el cliente, al grupo de agentes de administración del inquilino de partner de CSP se le asigna automáticamente el rol de propietario en la suscripción. En función de esta asignación de roles, los miembros del grupo pueden acceder a recursos y administrarlos en la suscripción.

- Cuando un cliente quita privilegios administrativos delegadas de un asociado con el Portal de Office 365, el partner sigue pudiendo administrar la suscripción de Azure del cliente, en tanto que el partner aún está asignado a una o más funciones en la suscripción. Para que el partner deje de administrar la suscripción de Azure, el cliente debe quitar la asignación de roles.

## <a name="windows-autopilot"></a>Windows Autopilot

<!--Maggie, 12/5/18 - Removed table showing what different CSP partner types can and can't do because all partner types are now in parity. As per Bhavya Chopra in bug 19841770.-->

Desde el centro de partners, los asociados de CSP pueden administrar los perfiles de Autopilot para sus clientes sin privilegios de administrador delegado en estas circunstancias: 

- Si un cliente quita los privilegios de administración delegada, pero conserva ninguna relación de revendedor con usted, aún puede administrar los perfiles de Autopilot para ellos.

- Puede administrar los dispositivos de cliente que haya agregado usted o a otro asociado. 

- No puede administrar los dispositivos que cliente se ha agregado a través de la Microsoft Store para empresas, Microsoft Store para educación o el Portal de Microsoft Intune.

Para obtener más información acerca de Autopilot, consulte [simplificar la configuración de dispositivo con Windows Autopilot](https://docs.microsoft.com/partner-center/autopilot).

>[!IMPORTANT]  
>Puede seguir cambiando la experiencia de administración de Autopilot actual en el centro de partners. En el momento en que se publicó este artículo, se consideran los cambios siguientes:

- Los partners deben tener privilegios de administración delegada del cliente para poder agregar, actualizar o eliminar perfiles y aplicar o quitar perfiles de todos los dispositivos del inquilino del cliente.

- Socio debe tener privilegios de administración delegada por el cliente antes de que el asociado puede eliminar los dispositivos agregados por otros socios o por el cliente en el inquilino del cliente. En caso contrario, el asociado puede quitar solo los dispositivos que agregó previamente por el mismo socio comercial.
