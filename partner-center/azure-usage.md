---
title: Microsoft Azure el tamaño de la máquina virtual para el uso máximo de reserva | Centro de Partners
ms.topic: article
ms.date: 08/05/2019
Description: Al comprar reservas de Microsoft Azure en nombre de tus clientes, deberás elegir una máquina virtual (VM) con el tamaño adecuado para satisfacer las necesidades informáticas del cliente.
author: LauraBrenner
ms.author: labrenne
keywords: azure, reservas, vm, administrar, uso, cambio de tamaño
ms.localizationpriority: medium
ms.custom: seodec18
ms.openlocfilehash: 1c1c0170c5efd8abf2e1afb7bb6ef1dfac2b7e5b
ms.sourcegitcommit: bae29ab191c72e15259d99c40c69a9e7c3f2b502
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 08/06/2019
ms.locfileid: "68820194"
---
# <a name="microsoft-azure-vm-sizing-for-maximum-reservation-usage"></a>Cambio de tamaño de la VM de Microsoft Azure para el uso máximo de reserva

**Se aplica a**

- Centro de partners
- Azure Portal
- Partners de CSP

## <a name="determine-the-vm-size-for-a-customers-azure-reservation"></a>Determinar el tamaño de la máquina virtual para la reserva de Azure de un cliente 

Al comprar reservas de Microsoft Azure en nombre de tus clientes, deberás elegir una máquina virtual (VM) con el tamaño adecuado para satisfacer las necesidades informáticas del cliente. Encontrarás esta información usando uno de estos métodos:

- API Azure Utilization
- El Portal de Azure
- Azure PowerShell
- La API de Azure Resource Manager (ARM)

A continuación, encontrarás instrucciones para cada uno de estos métodos. Después de comprar una reserva, el descuento de reserva se aplicará automáticamente a las máquinas virtuales que coincidan con los atributos y la cantidad de la reserva. No es necesario asignar la reserva a una máquina virtual.

>[!NOTE]
>Los descuentos de reserva no se aplican a máquinas virtuales clásicas o promocionales.

>[!IMPORTANT]
>Para identificar correctamente el tipo y el tamaño de la máquina virtual que se debe comprar en nombre del cliente, debes usar uno de los métodos que se describen a continuación ya que el tipo de serie de la máquina virtual no se muestra correctamente en los archivos de conciliación del Centro de partners.

**Obtención de información de tamaño de la máquina virtual mediante la API de uso de Azure**

1. Usa el valor del atributo ServiceType de additionalInfo en la respuesta de la API para identificar el tamaño de la máquina virtual que se comprará.
2. Para obtener más información, consulta [Obtener los registros de uso de un cliente para Azure](https://docs.microsoft.com/partner-center/develop/get-a-customer-s-utilization-record-for-azure) en la [API del Centro de partners](https://docs.microsoft.com/partner-center/develop/).

**Obtención de información de tamaño de la máquina virtual mediante el Microsoft Azure Portal**

1. En el centro de Partners, vaya a la página de **clientes** .
2. Encuentra al cliente que quiera comprar reservas de VM de Azure y, a continuación, selecciona la flecha abajo para expandir la información del cliente. Selecciona **Portal de administración de Microsoft Azure** para abrir el registro del cliente en el portal de Azure.
3. Selecciona **Máquinas virtuales** en el menú del portal y, a continuación, la máquina virtual para la que quieras comprar una reserva.
4. En la página de detalles de la VM, encuentra la información de tamaño y región, como se muestra a continuación, y usa esta información para comprar la reserva en el Centro de partners.  

    ![Información de tamaño y región en la página de detalles](images/usage1.png)

**Obtención de información de tamaño de máquina virtual mediante Microsoft Azure PowerShell**

Usa la información de la imagen siguiente para obtener la ubicación y el tamaño de la VM para la que quieres comprar una reserva. 

![Ubicación y tamaño de la máquina virtual](images/usage2.png)

**Obtención de información de tamaño de la máquina virtual mediante la API de Azure Resource Manager (ARM)**

1. Con ARMClient o las API de ARM, llama al cliente de ARM para la VM para la que quieres comprar una reserva.

2. /subscriptions/<Subscription ID>/resourceGroups/<Resource group name>/providers/Microsoft.Compute/virtualMachines/<VM Instance Name>?api-version=2017-12-01

3. La llamada devuelve los valores de **vmSize** y **ubicación**, como se muestra a continuación.

    ![valor de](images/usage3.png) Ubicación del valor ![de vmSize](images/usage4.png)

## <a name="verify-azure-vm-usage-and-reservation-discount"></a>Comprobar descuento de reserva y uso de la VM de Azure

Después de adquirir una instancia de VM reservada de Azure en nombre de un cliente, el descuento de pagar por adelantado el espacio de la VM se aplica automáticamente a las máquinas virtuales que coinciden con los atributos y la cantidad de la reserva del cliente.

Puedes comprobar el uso de la reserva del cliente y ver a qué máquinas virtuales se aplican los descuentos de reserva mediante uno de los siguientes métodos:

- El Portal de Azure
- API Azure Utilization

A continuación, encontrarás instrucciones para cada uno de estos métodos.

>[!NOTE]
>Solo la API Azure Utilization muestra a qué máquina virtual se está aplicando el descuento.  

### <a name="verify-the-customers-reservation-usage-in-the-microsoft-azure-portal"></a>Comprobar el uso de reserva del cliente en el portal de Microsoft Azure

1. En el centro de Partners, vaya a la página de **clientes** .

2. Encuentra al cliente del que quieres comprar el uso y el descuento de la reserva y, a continuación, selecciona la flecha abajo para expandir la información del cliente. Selecciona **Portal de administración de Microsoft Azure** para abrir el registro del cliente en el portal de Azure.
3. Selecciona **Reservas** en el menú del portal y, a continuación, la reserva para la que quieras comprobar el uso.
4. En la página **Introducción**, comprueba el gráfico de uso de la reserva, que muestra la cantidad de la reserva aplicada a máquinas virtuales.

    >[!NOTE]
    >Los datos de uso se pueden retrasar hasta un máximo de 8 horas.

    a. Si el uso de la reserva es 100 %, el cliente obtiene el posible ahorro que la compra de la reserva pueda proporcionar.
    b. Si el uso de la reserva es del 0 %, el descuento no se está aplicando a ninguna máquina virtual.
    c. Si el uso de la reserva es de entre el 1 y el 99 %, hay ventajas que no se emplean.

5. Para evitar esta situación, determina la VM de tamaño correcto para admitir las necesidades informáticas del cliente antes de realizar la compra.

### <a name="verify-the-customers-reservation-usage-with-the-azure-utilization-api"></a>Comprobar el uso de reserva del cliente con la API Azure Utilization

>[!NOTE]
>Solo la API Azure Utilization muestra a qué máquina virtual se está aplicando el descuento.  

Puedes obtener datos de uso de reserva con la API Azure Utilization para comprobar que el cliente está obteniendo el descuento de la reserva y para ver a qué VM (máquinas virtuales) se aplica el descuento. Compara el ejemplo A con el ejemplo B para ver cómo comprobar el uso de reserva de un cliente.

![Ejemplos de uso de reserva](images/usage5.png)

- El reservationId identifica la reserva de Azure que se usó para aplicar el descuento a la VM.
- consumptionMeter es el MeterId para la VM que tiene el descuento de reserva aplicado.
- El ReservationMeter muestra un costo de 0 $ desde que se aplicó el descuento de reserva.

Para obtener más información, consulta [Obtener los registros de uso de un cliente para Azure](https://docs.microsoft.com/partner-center/develop/get-a-customer-s-utilization-record-for-azure) en la [API del Centro de partners](https://docs.microsoft.com/partner-center/develop/).

>[!IMPORTANT]
>Los costes de software, como Microsoft Windows Server, no se incluyen actualmente en el precio de una reserva de VM y aparecerán como elementos de línea independientes en el registro de pedido y en tu factura. Sin embargo, si el cliente dispone de la Ventaja de uso híbrido de Microsoft Azure, no se aplicarán los costos de software. Para obtener más información, consulta [Costos de software de Windows no incluidos con las instancias reservadas](https://docs.microsoft.com/azure/billing/billing-reserved-instance-windows-software-costs).  

## <a name="azure-reservations-resources"></a>Recursos de Azure Reservations

|**Para obtener información sobre**   |**Lea este**    |
|:-----------------------------|:-----------------|
|Reservas de Azure en la introducción del CSP  | [Vender Microsoft Azure instancias reservadas de máquina virtual](azure-reservations.md)
|Compra de reservas de Azure para sus clientes en el centro de Partners   |[Comprar reservas de Azure](azure-reservations-buying.md)
|Administración de las reservas de Azure en el centro de Partners | [Administración de las reservas de Azure en el centro de Partners](azure-reservations-manage.md)
|Compra de reservas de Azure en Azure Portal | [Pagar por adelantado máquinas virtuales con instancias reservadas de máquina virtual](https://docs.microsoft.com/azure/virtual-machines/windows/prepay-reserved-vm-instances) en la Ayuda de Azure |
|Administración de Azure Reservations en el Azure Portal   |[Administración de instancias reservadas de máquina virtual](https://docs.microsoft.com/azure/billing/billing-manage-reserved-vm-instance) en la Ayuda de Azure  |
|Compra de reservas de Azure usando la API del Centro de partners | [Purchase Azure Reserved VM Instances (Comprar Azure Reserved VM Instances)](https://docs.microsoft.com/partner-center/develop/purchase-azure-reservations) en la documentación de desarrolladores del Centro de partners
