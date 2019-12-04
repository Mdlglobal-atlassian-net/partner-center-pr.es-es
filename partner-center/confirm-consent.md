---
title: Confirmar la aceptación del cliente del Contrato de Microsoft Cloud | Centro de partners
ms.topic: article
ms.date: 11/25/2019
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
Description: Obtenga información sobre cómo confirmar la aceptación del cliente del contrato de Microsoft Cloud. Esto puede ser necesario para ordenar los productos y servicios de Microsoft para los clientes.
author: LauraBrenner
ms.author: labrenne
keywords: cliente, clientes, consentimiento, MCA, contrato de Microsoft Cloud, plantillas de contrato de cliente
ms.localizationpriority: medium
ms.openlocfilehash: 8e6493fccee9b00c953e18446ec6f101bf267210
ms.sourcegitcommit: c793c1b61f50fc0b0a12c95cedd9f57b31703093
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/03/2019
ms.locfileid: "74722088"
---
# <a name="confirm-customer-acceptance-of-the-microsoft-cloud-agreement"></a>Confirmar la aceptación del cliente del Contrato de Microsoft Cloud

**Se aplica a**
-  Centro de partners

**Roles adecuados**

- Agente de administración
- Agente de ventas

> [!NOTE]
> Actualmente, el recurso de acuerdo solo es compatible con el centro de Partners en la nube pública de Microsoft. No es aplicable a:
> * Centro de partners operado por 21Vianet
> * Centro de partners para Microsoft Cloud Alemania
> * Centro de partners para Microsoft Cloud for US Government

>[!NOTE]
>Este contrato es válido hasta el 31 de enero de 2020. Después de esa fecha, todos los clientes, existentes y nuevos, deben firmar el nuevo contrato de cliente de Microsoft. Para obtener más información, consulte [confirmar la aceptación del cliente del contrato de cliente de Microsoft](confirm-customer-agreement.md).

Como asociado, debe obtener la aceptación del cliente del contrato de Microsoft Cloud antes de poder solicitar servicios y productos de Microsoft para ese cliente. Para ayudar mejor a los partners a cumplir con los requisitos de cumplimiento, Microsoft pide a los partners que confirmen la aceptación proporcionando los siguientes detalles de la persona que haya aceptado el contrato: 

-   Nombre

-   Apellidos

-   Dirección de correo electrónico

-   Número de teléfono (opcional)

-   Fecha de aceptación

Para obtener más información, consulte las [preguntas](https://docs.microsoft.com/partner-center/confirm-consent-faq)más frecuentes sobre la confirmación de aceptación del cliente del contrato de Microsoft Cloud.

Los asociados directos de facturación y los proveedores indirectos deben confirmar la aceptación del cliente del contrato de Microsoft Cloud al actuar a través del centro de Partners o de la API del centro de Partners. La confirmación es *obligatoria*.

Si no se facilita la confirmación para un cliente determinado:

-   No podrá crear nuevos pedidos para este cliente.

-   No podrá cambiar el número de puestos de las suscripciones basadas en puestos existentes para este cliente.

La confirmación de la aceptación del cliente se puede realizar a través del centro de Partners o de la API del centro de Partners. Para hacer esto a través de la API del centro de Partners, consulte los temas siguientes: 

-   [Obtener confirmación del consentimiento del cliente](https://docs.microsoft.com/partner-center/develop/get-confirmation-of-customer-consent)

-   [Obtener metadatos del contrato](https://docs.microsoft.com/partner-center/develop/get-agreement-metadata)

-   [Confirmar el consentimiento del cliente](https://docs.microsoft.com/partner-center/develop/confirm-customer-consent)


Esto se aplica a los entornos de producción y de espacio aislado.

## <a name="confirming-customer-acceptance-in-partner-center"></a>Confirmar la aceptación del cliente en el centro de Partners

### <a name="confirm-customer-acceptance-for-a-new-customer"></a>Confirmar la aceptación del cliente para un nuevo cliente

Use el procedimiento siguiente para confirmar la aceptación del cliente mientras crea un nuevo inquilino de cliente en el centro de Partners. Ten en cuenta que debes ser agente de administración o agente de ventas para poder hacer esto.

1. Seleccione **clientes**y, después, **nuevo cliente** y, a continuación, seleccione información de la **cuenta**.
2. Introduce la información sobre la **Empresa** y el **Contacto principal**.

![Información de la compañía](images/mca/mca1.png)

3. En **Contrato de Microsoft Cloud**, selecciona **El cliente ha aceptado el último contrato Microsoft Cloud**.
4. En **Fecha de aceptación del contrato**, introduce la fecha adecuada. No puedes elegir para esto una fecha futura.
5. Introduce los detalles del usuario que proporciona la aceptación.

![Agregar fecha de aceptación](images/mca/MCA3.png)

De manera predeterminada, se mostrará la información del usuario de contacto principal. Si esto no es correcto, seleccione **Actualizar** y escriba el **nombre**, el **Apellido**, la **dirección de correo electrónico**y el **número de teléfono* (opcional) de la persona que aceptó el contrato.

6. Selecciona **Siguiente** para continuar con los pasos restantes para crear el inquilino del cliente.

### <a name="confirm-customer-acceptance-for-an-existing-customer"></a>Confirmar la aceptación del cliente para un cliente existente

Debes ser agente de administración o agente de ventas para poder hacer esto.

1. Selecciona **Clientes** y, a continuación, busca y selecciona el cliente que quieras ver.
2. Selecciona **Información de cuenta**.
3. En **Contrato de Microsoft Cloud**, selecciona **Actualizar**.

![Actualizar](images/mca/mca4.png)

4. Escriba el **nombre**, los **apellidos**, la **dirección de correo electrónico**y el **número de teléfono** (opcional) del usuario que aceptó el contrato.
5. En **Fecha de aceptación del contrato**, introduce la fecha adecuada. No puedes elegir para esto una fecha futura.
6. Selecciona **Guardar y continuar**.

### <a name="confirm-customer-acceptance-while-creating-new-order-for-an-existing-customer"></a>Confirmar la aceptación del cliente durante la creación de un nuevo pedido para un cliente existente

Si intenta crear un nuevo pedido para un cliente existente que no ha confirmado antes, recibirá un aviso para completar la confirmación. Utiliza el siguiente procedimiento para hacerlo.

1. Escriba el **nombre**, los **apellidos**, la **dirección de correo electrónico**y el **número de teléfono** (opcional) del usuario que aceptó el contrato.
2. En **Fecha de aceptación del contrato**, introduce la fecha adecuada. No puedes elegir para esto una fecha futura.
3. Selecciona **Guardar y continuar**.

### <a name="retrieve-confirmation-of-customer-acceptance-for-an-existing-customer"></a>Recuperar la aceptación del cliente para un cliente existente

Puedes recuperar la confirmación de aceptación del cliente para un cliente existente que la haya proporcionado anteriormente con el siguiente procedimiento. Debes ser agente de administración o agente de ventas para poder hacer esto.

1. Selecciona **Clientes** y, a continuación, busca y selecciona el cliente que quieras ver.
2. Selecciona **Información de cuenta**.
3. En **contrato de nube de Microsoft**, verá si se ha proporcionado una confirmación para este cliente.
