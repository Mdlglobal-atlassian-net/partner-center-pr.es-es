---
title: Consolidación de los inquilinos de autorización regional de CSP | Centro de partners
ms.topic: article
ms.date: 03/15/2019
description: Usa estas instrucciones para consolidar los inquilinos para diferentes países o regiones.
ms.assetid: 749B4C6A-26BE-4942-BDA8-F08C40DF048A
author: MaggiePucciEvans
ms.author: evansma
keywords: migrar clientes, aprovisionamiento, cuenta de inquilino, consolidar inquilinos
ms.localizationpriority: medium
robots: noindex,nofollow
ms.openlocfilehash: 5e83b9720393356268f59d42b4210c427a3b3bc6
ms.sourcegitcommit: 5e67a2540b0ff9eb248e5dc41b9d9ad1fc900b36
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 06/10/2019
ms.locfileid: "66819935"
---
# <a name="csp-regional-authorization-tenant-consolidation"></a>Consolidación de los inquilinos de autorización regional de CSP

**Se aplica a**

-  Centro de partners
-  Centro de partners para Microsoft Cloud for US Government


\[Parte de la información está relacionada con productos preliminares que pueden modificarse sustancialmente antes de su lanzamiento comercial. Microsoft no ofrece ninguna garantía, expresa ni implícita, con respecto a la información proporcionada aquí.\]

Usa estas instrucciones para consolidar los inquilinos para diferentes países o regiones.

**Nota**: Debes tener en cuenta todas las suscripciones y recuentos de puestos para tus clientes aprovisionados desde las cuentas de transición. Se te volverá a aprovisionar esas mismas suscripciones exactas con la misma cantidad de puestos en la nueva cuenta de Central CSP como parte del proceso de migración. Usa la característica de lista de exportación para ayudar a crear una lista de clientes que trasladar al inquilino centralizado. Los partners eligen si consolidar sus inquilinos. Una vez completada la consolidación, los partners no pueden volver a su estado anterior. Ten en cuenta que es posible que también sean necesarias ciertas acciones por parte del cliente.



## <a name="prepare-for-migration"></a>Preparación para la migración


-   Inicie sesión en su **centro de partners** con el **transición** (existente) cuenta (el que realizará la transición) y tome nota de todos los clientes y todos los servicios aprovisionan para los clientes.

![lista de clientes regionales](images/regionalcustomer1.png)

## <a name="migrate-customer-accounts"></a>Migración de las cuentas de cliente


1.  Inicie sesión en su **centro de partners** con el **transición** (lo está realizando la transición a) de la cuenta (nuevo) y navegue a la lista de los clientes de **clientes**.

2.  Selecciona Clientes.

3.  Haz clic en **Solicitar una relación de revendedor**. Se te mostrará un mensaje de correo electrónico predeterminado que presentar a tus clientes. Este mensaje contiene una dirección URL con el identificador de organización exclusivo para tu nueva cuenta del centro de partners.

4.  **Acción de cliente:** Asegúrese de que cada uno de los clientes activos que van a migrar visita esta dirección URL. Al abrir la dirección URL, al cliente se le pedirá que inicie sesión en el portal de Office 365. El cliente iniciará sesión usando el mismo identificador de organización que utilice para acceder a los portales de administración de Azure y de Office 365.

5.  Tras iniciar sesión, al administrador Global de la cuenta del cliente se le pedirá que envíe un contrato para conceder privilegios de administrador delegado a la nueva cuenta de CSP. Si acepta, el cliente seleccionará la casilla y autorizará la relación.

Los clientes aparecerán en la lista de clientes del partner después de enviar el acuerdo, uno por uno.

## <a name="migrating-office-365-and-non-azure-usage-based-subscriptions"></a>Migración de suscripciones basadas en uso de Office 365 y que no sean de Azure


1.  Cuando el cliente haya firmado el contrato, puedes volver a crear sus suscripciones en tu inquilino de partner centralizado.

2.  Desde el **centro de partners** seleccione **clientes**.

3.  Abre el nombre de la compañía del cliente que deseas migrar.

4.  Haz clic en **Agregar suscripción**.

5.  Agrega las suscripciones y el número de puestos correctos desde el catálogo. Verifica los datos con la información proporcionada en las cuentas de partner de **Transición desde**.

![lista de clientes](images/regionalcustomer2.png)

6.  Haz clic en **Enviar**.

Ahora los servicios se proporcionan al cliente desde la cuenta de partner de **Transición a**.

Repite estos pasos para migrar las suscripciones de todos los demás clientes.

Antes de pasar a la siguiente sección, asegúrate de todas las suscripciones de cliente existente en las cuentas de partner de **Transición desde** se vuelven a aprovisionar en la cuenta de partner de **Transición a**.

**Nota** Los partners deben suspender las suscripciones en la cuenta de inquilino de partner de **Transición desde** en el Centro de partners el mismo día que se realice la transición de dichas suscripciones y configurarlas en la cuenta de inquilino de partner de **Transición a** en el Centro de partners para asegurarse de que no se produce una facturación doble. Se denegarán las solicitudes de soporte técnico referentes a créditos debidas a cualquier superposición en la facturación que se produzca por no deshabilitar correctamente las suscripciones de **Transición desde**.



## <a name="disabling-the-office-365-subscriptions-under-the-transitioning-from-partner-account"></a>Deshabilitar las suscripciones de Office 365 en la cuenta de partner de Transición desde


Deshabilitar la suscripción de CSP de las cuentas de partner de **Transición desde** detiene toda facturación futura. No es necesario deshabilitar manualmente las suscripciones de Azure, porque las suscripciones de Azure se deshabilitan automáticamente durante el proceso de migración.

1.  Inicie sesión en el **centro de partners** con el **transición desde** CSP cuenta y vaya a la lista de clientes.

2.  Abre al cliente cuyas suscripciones quieras deshabilitar y, a continuación, selecciona la primera oferta que deshabilitar.
3.  Establece la suscripción en **suspendida**y, a continuación, haz clic en **enviar**.

 >[! **Nota**] suspender la suscripción garantiza que no se produce facturación doble.



~~~
The Subscription shows **suspended** on the subscriptions list.
~~~

4.  Repite estos pasos para todas las suscripciones del cliente. Comprueba que todas muestran **suspendida.**

5.  Selecciona al siguiente cliente de la lista y repite el proceso de deshabilitar todas las suscripciones.

## <a name="migrating-azure-usage-based-subscriptions"></a>Migración de suscripciones basadas en uso de Azure


Ten en cuenta que no es necesario migrar las suscripciones de CSP basadas en el uso de Azure de forma manual, como sucede con las suscripciones de CSP de Office 365. El soporte técnico de Microsoft Azure puede migrar las suscripciones de Azure, así como todos los servicios o los recursos implementados, desde las cuentas de revendedor de CSP de **Transición desde** a la cuenta de revendedor de CSP de **Transición a**. Durante esta transición, el cliente no experimentará ninguna interrupción del servicio.

1.  Asegúrate de que las cuentas de cliente que necesitan que se migren las suscripciones de Azure han aceptado el acuerdo que se asociará con la nueva cuenta de CSP de **Transición a**.
2.  Los partners notifican a Microsoft qué cuentas de cliente que tienen suscripciones de Azure están listas para migrar y proporciona los nombres de compañía de dichos clientes.
3.  Microsoft migra las suscripciones basadas en uso de Azure y notifica a los partners cuándo se ha completado la migración.
4.  El partner confirma que la suscripción de Azure en las cuentas de revendedor de CSP de **Transición desde** ahora muestra suspendida en el Centro de partners, en la sección de suscripciones del cliente.
5.  El partner confirma que la suscripción de Azure las cuenta de revendedor de CSP de **Transición a** ahora muestra un estado de **activa** en el Centro de partners, en la sección de suscripciones del cliente.

>[! **Nota**] deshabilitar las suscripciones en el cliente no cambia la apariencia del cliente en la lista de los clientes. Actualmente no hay ninguna opción para quitar clientes de la lista. Los partners deben evitar volver a agregar suscripciones a estos clientes en el futuro desde su cuenta de **Transición desde**.



6.  Repite estos pasos para todas las suscripciones de todos tus clientes para detener futuros cargos en las cuentas **Transición desde**. El partner recibirá una factura final con un crédito por el número de días sin usar entre el día de la cancelación y el último día del período de facturación. Tras ese período de facturación final, no se generarán más futuras.

### <a name="notes"></a>Notas

-   Deshabilitar la suscripción desde la cuenta de CSP de **Transición desde** no afecta a servicio del cliente final, siempre que el servicio se haya aprovisionado desde la cuenta de CSP **Transición a** antes de la deshabilitación.

-   El cliente no puede usar las suscripciones y estas no generarán cargos cuando se suspendan o se cancelen.

-   Actualmente no hay ninguna manera de quitar por completo a un cliente de la lista de clientes.

-   **Nota** Los partners deben suspender las suscripciones en la cuenta de inquilino de partner de **Transición desde** en el Centro de partners el mismo día que se realice la transición de dichas suscripciones y configurarlas en la cuenta de inquilino de partner de **Transición a** en el Centro de partners para asegurarse de que no se produce una facturación doble. Microsoft no admitirá las solicitudes de soporte técnico referentes a créditos debidas a cualquier superposición en la facturación que se produzca por no deshabilitar correctamente las suscripciones de **Transición desde**.



### <a name="simplify-migration-using-export"></a>Simplificación de la migración mediante la exportación

Si usas la **Función de exportación**, puedes capturar las suscripciones que necesites usar en tu nueva estructura consolidada:

1.  Haga clic en **clientes** en el centro de partners para ver la lista de clientes en la estructura existente.

2.  Abre el nombre del cliente deseado.

3.  En la página **Suscripciones**, haz clic en **Exportar suscripciones** para exportar los detalles de las suscripciones a un archivo de Excel.

4.  Usa esta lista para volver a crear las suscripciones en el nuevo inquilino consolidado.

### <a name="api-registration"></a>Registro de API

Para obtener más información acerca del registro de API, visita esta [página web](https://go.microsoft.com/fwlink/?linkid=847990) (en inglés).








