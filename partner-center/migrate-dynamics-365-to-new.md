---
title: Migración de ofertas de Dynamics 365 Business Edition a versiones más recientes | Centro de Partners
ms.topic: article
ms.date: 12/12/2018
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Obtenga información sobre cómo migrar las ofertas de Dynamics 365 Business Edition a las versiones más recientes antes de que expiren.
ms.assetid: 79787bef-a6e9-4c11-8c3b-f0a77485c0a4
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: medium
ms.custom: seodec18
Keywords: Ofertas de Dynamics 365, renovar ofertas, nuevas SKU de Dynamics 365
ms.openlocfilehash: d4efd051b4d237eac5b766ed1aedc432e8b93ecc
ms.sourcegitcommit: 07eb5eb6c1cfed1c84fad3626b8f989247341e70
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/11/2019
ms.locfileid: "75005124"
---
# <a name="migrate-dynamics-365-business-edition-offers-to-newer-versions"></a>Migrar ofertas de Dynamics 365 Business Edition a versiones más recientes 

**Se aplica a**

- Centro de asociados

**Roles adecuados**
-   Administrador global
-   Administrador de usuarios
-   Agente de administración
-   Agente de ventas

A partir del 1 de enero de 2019, los clientes con suscripciones de Dynamics 365 Business Edition ya no podrán renovar en estas ofertas heredadas. las suscripciones existentes no se renovarán automáticamente cuando expiren. En la página de detalles de la suscripción, el estado de la suscripción cambiará a "expira el [fecha]" de "se renueva automáticamente en [fecha]".

Para garantizar la continuidad de los clientes, debe realizar la transición de las suscripciones que van a expirar a una opción admitida, que se enumera a continuación. Se recomienda mover a los clientes a nuevas suscripciones antes de la fecha de finalización anual de la suscripción para evitar interrupciones de servicio para los clientes.

Si usa la API (de la cresta o del centro de Partners), puede encontrar suscripciones que van a expirar mediante la evaluación de la fecha de finalización de la suscripción junto con la propiedad auto Renew = false. Las suscripciones en cuestión se establecerán en renovación automática = false el 1 de enero de 2019. Puedes mover a los clientes a un plan nuevo en cualquier momento. 

## <a name="the-dynamics-365-business-editions-being-retired"></a>Las ediciones Business de Dynamics 365 que se están retirando

- Dynamics 365 para finanzas y operaciones, edición Business
- Dynamics 365 para los miembros del equipo, edición Business

## <a name="dynamics-business-central---the-dynamics-365-business-edition-new-offers"></a>Dynamics Business central: las ofertas nuevas de Dynamics 365 Business Edition

Con las nuevas ofertas de Dynamics Business central, sus clientes pueden conectar sus finanzas, ventas, servicios y operaciones para simplificar los procesos empresariales, mejorar las interacciones de los clientes y tomar mejores decisiones. Dynamics 365 Business central se basa en la nube y está disponible a través de los asociados de programas del proveedor de soluciones en la nube (CSP).
Los clientes de Dynamics 365 Business Edition pueden recibir precios de transición con descuento para las nuevas ofertas de Business central hasta el 30 de junio de 2020.

## <a name="transition-customers-to-new-product-plans"></a>Clientes de transición hacia los nuevos planes de productos

 El traslado de los clientes de las SKU retiradas a otras más recientes requiere los pasos siguientes en este orden:

- Comprar la nueva suscripción
- Reasignar licencias de usuario actuales
- Cancelar suscripción antigua

## <a name="purchase-the-new-plan-for-your-customer"></a>Compre el nuevo plan para su cliente

1. Seleccione **customers (clientes** ) en el panel de navegación izquierdo y, a continuación, seleccione el cliente que desea desplazar a la nueva suscripción.
2. Seleccione **Agregar suscripción**.
3. Selecciona la suscripción que quieras adquirir del catálogo (en este caso, una de las opciones que se indican más arriba), escribe el número de licencias y, a continuación, **Enviar**. 

El cliente tendrá ahora la suscripción antigua y la nueva. El siguiente paso consiste en volver a asignar las licencias a los usuarios del cliente.

1. Seleccione **customers (clientes** ) en el panel de navegación izquierdo y, a continuación, seleccione el cliente que va a mover.
2. Selecciona **Usuarios y licencias**.
3. Para reasignar una licencia a un usuario, seleccione el usuario y, a continuación, seleccione **administrar licencias**. 
4. En la página **administrar licencias** , desactive la casilla Dynamics 365 for sales/Customer Engagement plan from Basic (oferta calificada) y seleccione un nuevo plan de servicio para la suscripción a la que está pasando el cliente. 
5. Seleccione **Enviar**. Lo hará para cada usuario que necesite la nueva licencia. 

Una vez que haya migrado las licencias a la nueva suscripción, puede cancelar la suscripción anterior. 

1. Seleccione **customers (clientes** ) en el panel de navegación izquierdo y, a continuación, seleccione el cliente que va a mover.
2. En la página de detalles de la suscripción, establezca la suscripción antigua en **Suspended** y seleccione **submit (enviar**).

La suscripción anterior se ha suspendido y la nueva suscripción está activa. Se cancelará el aprovisionamiento de la suscripción suspendida automáticamente después de 120 días. El cliente no incurrirá en costos adicionales por la suscripción anterior.
