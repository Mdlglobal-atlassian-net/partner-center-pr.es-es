---
title: Funcionalidades de facturación directa restringidas
ms.topic: article
ms.date: 01/24/2020
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Los asociados directos de facturación que no cumplan el nuevo requisito tendrán restringido las capacidades de factura directa.
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: medium
keywords: factura directa, restringir
ms.openlocfilehash: ae2a1a66f1a93e8b8183a307eca395e9781a00df
ms.sourcegitcommit: 3849d49261f4f652bd7c0537ebe31558af427c5c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/13/2020
ms.locfileid: "83362433"
---
# <a name="restricted-direct-bill-capabilities"></a>Funcionalidades de facturación directa restringidas  

## <a name="overview"></a>Información general

Los asociados directos de facturación deben cumplir los nuevos [requisitos](direct-partner-new-requirements.md) para permanecer en el programa de asociados de facturación directa de CSP. De lo contrario, su acceso a las capacidades de factura directa se restringirá con el tiempo y ya no podrán realizar tareas específicas, como nuevas compras para sus clientes.

> [!Note]
> Microsoft informará a los asociados directos de facturación que no cumplan los requisitos nuevos para el programa de asociados de factura de CSP Direct, siempre que se restrinjan sus capacidades de factura directa. Esto se aplica a todos los asociados directos de facturación, tanto si han optado por la [transición de Direct Bill Partner a distribuidores indirectos](transition-direct-to-indirect.md) como si no.  

## <a name="how-to-tell-if-your-direct-bill-capabilities-has-been-restricted"></a>Cómo saber si se ha restringido su funcionalidad de factura directa

Siga estos pasos para confirmar si se ha restringido el acceso desde el inquilino directo de facturación a las capacidades de factura directa.

1. Inicie sesión en el [panel del centro de Partners](https://partner.microsoft.com/dashboard).

2. Vaya a **configuración de Partner**  ->  **Perfil de socio comercial**.

3. En **información del programa**, busque **Microsoft Cloud estado del proveedor de soluciones**.

4. Si el estado del programa tiene el valor **restringido**, significa que se ha restringido el acceso del inquilino directo de Bill Partner a las capacidades de factura directa.

## <a name="affected-direct-bill-capabilities"></a>Capacidades de factura directa afectadas

Si las capacidades de factura directa se han restringido, ya no podrá realizar compras nuevas para los clientes en el centro de Partners. Esta restricción incluye:

- Suscripciones de Azure
- Suscripciones basadas en puestos
- Agregue nuevos complementos a las suscripciones basadas en puestos existentes.
- Realice compras de un solo tiempo de software y productos de reserva (por ejemplo, suscripciones de software, software perpetuo e instancias reservadas de máquina virtual de Azure).

Tampoco puede comprar nuevas suscripciones de Azure para su propio uso mediante la [oferta de servicios compartidos de asociados de Azure](shared-services.md) en el programa CSP.

Las suscripciones de factura directa existentes no se ven afectadas. Siguen siendo válidos y se renuevan. Se seguirá facturando directamente por Microsoft hasta que se cancele. Todavía puede administrar las suscripciones existentes de las siguientes maneras:

- Suspender las suscripciones existentes
- Ajustar el número de puestos de las suscripciones basadas en puestos existentes
- Ajustar el número de puestos de los complementos existentes a una suscripción. Nota: no puede agregar nuevos complementos a las suscripciones existentes, ya que se trata como una nueva compra.
- Implemente nuevos recursos de Azure y administre los recursos existentes de Azure en las suscripciones de Azure existentes. Esto incluye los recursos, que están disponibles a través de las suscripciones de Azure Marketplace y Visual Studio.

Además de las nuevas compras, no puede tener acceso a las siguientes funciones de factura directa en el centro de Partners:

- No se pueden crear nuevos inquilinos de cliente. La opción **crear cliente** en la página **clientes** del centro de Partners no estará disponible.
- No se puede generar una invitación para el cliente que solicita la relación de revendedor directa. La opción **solicitar una relación de revendedor** en la página **clientes** del centro de Partners no estará disponible.

    >[!Note]
    >Como parte de la transición de un asociado directo de factura a un revendedor indirecto, si ya ha inscrito el inquilino Direct Bill Partner como revendedor indirecto, puede generar una invitación a la solicitud del cliente para la relación de revendedor indirecta en su lugar.

- No se puede crear un nuevo inquilino de espacio aislado. Cada inquilino de remesa directo puede crear un inquilino de espacio aislado con el fin de la integración directa de la API de facturación. Si no ha creado una anteriormente, no podrá hacerlo después de que se haya restringido la funcionalidad de socio de facturación.  

## <a name="next-steps"></a>Pasos siguientes

- [Información adicional sobre cómo convertirse en revendedor indirecto](https://assetsprod.microsoft.com/csp-directbill-to-indirect-transition.pdf)

- [Nuevos requisitos de asociados directos del CSP](direct-partner-new-requirements.md)