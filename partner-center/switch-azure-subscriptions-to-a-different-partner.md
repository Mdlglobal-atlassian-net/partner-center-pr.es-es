---
title: Transferencia de suscripciones de Azure a otro asociado
ms.topic: article
ms.date: 04/27/2020
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Obtenga información sobre cómo ayudar a un cliente a cambiar el asociado del programa CSP asociado a las suscripciones de Azure de ese cliente.
ms.assetid: 42D1D9AB-613D-4FC1-A846-EE769923E699
author: LauraBrenner
ms.author: labrenne
keywords: suscripción a Azure, cambiar asociado, cambiar asociado, obtener nuevo asociado, otro asociado
ms.custom: SEOAPR.20
ms.localizationpriority: medium
ms.openlocfilehash: 01316ceebcd2f969c89b4160bf5d95dcc44b1366
ms.sourcegitcommit: 46b86ac7467afa43bedb0943dc8dc45a69caf1dd
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/12/2020
ms.locfileid: "83194393"
---
# <a name="learn-how-to-transfer-a-customers-azure-subscriptions-to-another-partner"></a>Obtenga información sobre cómo transferir las suscripciones de Azure de un cliente a otro asociado.

**Se aplica a**

- Centro de partners para Microsoft Cloud for US Government
- Centro de partners para Microsoft global Cloud
- Partners del programa Proveedor de soluciones en la nube (CSP)

En este artículo se describe cómo un cliente puede cambiar su Microsoft Azure servicios de un proveedor de soluciones en la nube (CSP) a otro.

Para cambiar los servicios o las suscripciones de Azure de un cliente a otro asociado, siga estos pasos manuales. Tanto el socio como el cliente deben completar los pasos.

>[!Note]  
>Actualmente, solo los proveedores directos o indirectos pueden transferir suscripciones.
>No se pueden cambiar los asociados de las suscripciones del proveedor de soluciones en la nube asociadas a las suscripciones de Azure plan, Office 365, Enterprise Mobility Suite o Microsoft Dynamics CRM.

**Cambia partners para suscripciones de Azure**

1. Para transferir una suscripción de Azure a un socio nuevo, el cliente debe iniciar el proceso y ponerse en contacto con su partner de registro actual por escrito.

   >[!Note]
   >Es responsabilidad del asociado actual crear el vale de servicio que inicia el proceso de transferencia. Microsoft no puede intervenir en nombre del cliente o del nuevo socio. El cliente debe planear trabajar en estrecha colaboración con el socio actual para que la transición se lleve a cabo sin problemas.

2. El socio comercial de la suscripción debe realizar las siguientes tareas:

   Crear un vale de servicio de Azure desde el Centro de partners para solicitar una transferencia de suscripción:

   - En el menú del centro de Partners, seleccione **clientes**, seleccione el cliente en la lista y, a continuación, seleccione **Administración de servicios**. En la sección **Vales de soporte**, selecciona la lista desplegable **Nuevo vale** y elige **Microsoft Azure**.

   - En el [Azure portal](https://portal.azure.com), seleccione **nueva solicitud de soporte técnico**.

     En el paso 1, elija **Administración de suscripciones** como tipo de problema, especifique el identificador de suscripción que desea transferir y elija **proveedor de soluciones** en la nube como plan de soporte técnico.

     En el paso 2, seleccione **C-impacto mínimo** y elija **otras preguntas generales** como tipo de problema.

     Descargue el [formulario de transferencia de suscripciones de CSP](https://assets.windowsphone.com/5222c408-e546-4e01-b72a-2ec7d4c43d57/CSP_Subscription_Transfer_Form_Azure_InvariantCulture_Default.zip).

3. El socio comercial de la suscripción: Rellene el [formulario de transferencia de suscripción de CSP](https://assets.windowsphone.com/5222c408-e546-4e01-b72a-2ec7d4c43d57/CSP_Subscription_Transfer_Form_Azure_InvariantCulture_Default.zip), Regístrese y, a continuación, envíelo al cliente. Para rellenar el formulario, necesitarás la siguiente información:

   - Información de contacto del partner actual e Id. de Microsoft. En el menú del Centro de partners, selecciona **Configuración de la cuenta** &gt; **Perfil de la organización** y usa el **Id. de Microsoft**, **Nombre de la organización** y **Dirección** que se enumeran ahí.

   - Identificador de Microsoft del cliente. En el menú del Centro de partners, selecciona **Clientes** y, después, expande la lista del cliente para ver su **Id. Microsoft**.

   - Id. de suscripción que se va a transferir. En el listado de clientes expandido, selecciona **Ver suscripciones** y, a continuación, expande la suscripción seleccionada para ver el **Id. de suscripción**.

   >[!Note]
   >La transferencia de una suscripción da como resultado dos identificadores de suscripción que verá en la página **Editar suscripción** de la suscripción transferida: **1**: el identificador de suscripción del centro de Partners se usa con fines de facturación. **2**-el identificador de suscripción de Azure original se conserva y aparecerá en el centro de Partners, así como en el portal de administración de Azure. Este identificador aparecerá en el archivo de conciliación.  **Al registrar vales de soporte técnico, debe usar ambos identificadores.**

4. El cliente y el nuevo socio comercial de la suscripción:

   Revisa el formulario, rellena la información sobre el nuevo partner y fírmalo. Comprueba que el nuevo cliente tiene un acuerdo contractual en vigor. Vuelve a enviar el formulario al partner de registro actual.

   *Importante*: Si el nuevo asociado de CSP no tiene una relación de revendedor con el cliente, debe establecer uno antes de que se transfiera la suscripción. [Puedes encontrar información sobre cómo hacer esto aquí](request-a-relationship-with-a-customer.md).

   >[!Note]
   >El nuevo asociado de CSP y el inquilino del cliente deben estar en el mismo país. 

5. Socio actual:

   Asegúrese de que el formulario incluye información de contacto para ambos administradores de socios comerciales. Soporte técnico de Microsoft se pondrá en contacto con ambos administradores para comprobar la transferencia. Asegúrese de que tiene las tres firmas. A continuación, use la opción **carga de archivos** para adjuntar el formulario completado a la solicitud de servicio existente. Un ingeniero de soporte técnico de Microsoft le devolverá en el plazo de ocho horas hábiles para validar la recepción y la finalización.

6. Nuevo asociado:

   Actualiza la configuración de suscripción de Azure para quitar el partner antiguo de la cuenta. Para ver las asignaciones de roles que se aprovisionan, ejecute dos Commandletss de PowerShell.

   - Agrega el nuevo asociado como el revendedor de la cuenta:

     ```powershell
     Add-AzureRMAccount -tenant "CustomerDomainName"
     ```

     Para encontrar el valor de customerDomainName: en el menú del Centro de partners, selecciona **Clientes**. En la lista de clientes, selecciona el cliente. En el menú del cliente, selecciona **Cuenta** y usa el valor de **Nombre de dominio**.

   - Observa los roles de la cuenta, incluidos los asociados de CSP anteriores:

     ```powershell
     Get-AzureRMRoleAssignment
     ```

7. Quitar permisos de acceso obsoletos

   - En el menú del Centro de partners, selecciona **Clientes**.
   - Expande la lista del cliente y selecciona **Ver suscripciones**.
   - En el menú del cliente, selecciona **Administración de servicios**.
   - En **Microsoft Azure**, haz clic en el vínculo para ir al **Portal de administración de Microsoft Azure**.
