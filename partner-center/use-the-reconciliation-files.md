---
title: Usar los archivos de conciliación | Centro de partners
ms.topic: article
ms.date: 03/15/2019
description: Para obtener una vista detallada del elemento de línea de cada carga de un ciclo de facturación, descargue los archivos de conciliación de centro de partners.
ms.assetid: FA6A6FCB-2597-44E7-93F8-8D1DD35D52EA
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: medium
ms.openlocfilehash: 8e7b17cb39f266c404d7873dc17e471741d52b32
ms.sourcegitcommit: b1ab80345b4e4af649fb8cc51d96d798e0791ade
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "62132785"
---
# <a name="use-the-reconciliation-files"></a>Usar los archivos de conciliación

**Se aplica a**

-  Centro de partners
-  Centro de partners para Microsoft Cloud for US Government


Para obtener una vista detallada del elemento de línea de cada carga de un ciclo de facturación, descargue los archivos de conciliación de centro de partners. Los detalles incluyen los cargos para las suscripciones de cada cliente y los eventos detallados (por ejemplo, una adición intermedia de puestos en una suscripción).

## <a name="formatting-issues"></a>Problemas de formato

En ocasiones, el archivo de conciliación podría tener problemas de formato. (Esto puede ocurrir, por ejemplo, si no se usa la configuración regional EN-US). Siga estos pasos para corregir estos problemas. 

<ol>
<li>Abra el archivo .csv en Excel y seleccione la primera columna. En la cinta de opciones, seleccione <strong>datos</strong>y, a continuación, seleccione <strong>texto en columnas</strong>.</li>

<li>En convertir texto en el Asistente de columnas, seleccione <strong>delimitado por tipo de archivo</strong>y, a continuación, seleccione <strong>siguiente</strong>.</li> 

<li>En el campo delimitadores, seleccione <strong>comas</strong>. Si <strong>ficha</strong> está ya seleccionado, puede dejarla. Selecciona <strong>Siguiente</strong>.</li>

<li>En el campo de formato de datos de columna, seleccione <strong>fecha: MDY</strong>y, a continuación, seleccione <strong>siguiente</strong>.</li> 

<li>En el campo de formato de datos de columna, seleccione <strong>texto</strong> para amount, todas las columnas y, a continuación, seleccione <strong>finalizar</strong>.</li>
</ol>

## <a href="" id="itemizebypartner"></a>Detallar asociado


Los partners del modelo indirecto pueden usar estos campos adicionales en ambos archivos de conciliación basada en uso y en licencia para realizar el desglose por revendedor.

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Id. de MPN</th>
<th>Descripción</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Id. de MPN</td>
<td><p>Id. de Microsoft Partner Network (MPN) del partner de CSP (directo o indirecto).</p></td>
</tr>
<tr class="even">
<td>Id. de MPN del revendedor</td>
<td><p>Solo aparece en los archivos de conciliación de partners en el modelo indirecto.</p>
<p>El Id. de MPN del revendedor de registro de la suscripción. Corresponde al id. de revendedor indicado para la suscripción específica en el Centro de partners.</p>
<p>muestra de eTo o actualiza el distribuidor, en el menú del centro de partners, seleccione <strong>clientes</strong>, a continuación, elija el cliente de la lista. En el menú del cliente, selecciona <strong>Suscripciones</strong> y elige la suscripción de la lista. Selecciona <strong>Actualizar</strong> para cambiar el valor de <strong>Revendedor (id. de MPN)</strong>.</p>
<p>Si un partner CSP vendió la suscripción directamente al cliente, su id. de MPN aparece dos veces, como id. de MPN y como id. de MPN del revendedor.</p>
<p>Si un partner CSP tiene un revendedor sin un id. de MPN, este valor se establece en el id. de MPN del partner.</p>
<p>Si el partner CSP quita un id. de revendedor, este valor se establece en -1.</p></td>
</tr>
</tbody>
</table>

 

## <a href="" id="licensebasedfiles"></a> Campos de archivo de licencia


Para conciliar los cargos en función de los pedidos del cliente, compara el Syndication\_Partner\_Subscription\_Number del archivo de conciliación con el id. de suscripción del Centro de partners.

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><strong>Columna</strong></td>
<td><strong>Descripción</strong></td>
<td><strong>Valor de ejemplo</strong></td>
</tr>
<tr class="even">
<td>PartnerId</td>
<td><p>Identificador único de una entidad de facturación específica, con formato de GUID. No es necesario para la reconciliación, pero puede ser información útil. Igual en todas las filas.</p></td>
<td>8ddd03642-test-test-test-46b58d356b4e</td>
</tr>
<tr class="odd">
<td>CustomerID</td>
<td><p>Id. de Microsoft único, en formato GUID, usado para identificar al cliente.</p></td>
<td>12ABCD34-001A-BCD2-987C-3210ABCD5678</td>
</tr>
<tr class="even">
<td>OrderID</td>
<td><p>Identificador único de un pedido en la plataforma de facturación de Microsoft. Puede ser útil para identificar al pedido al ponerse en contacto con el soporte técnico, pero no para la conciliación.</p></td>
<td>566890604832738111</td>
</tr>
<tr class="odd">
<td>SubscriptionID</td>
<td><p>Identificador único de una suscripción en la plataforma de facturación de Microsoft. Puede ser útil para identificar a la suscripción al ponerse en contacto con el soporte técnico, pero no para la reconciliación.</p>
<p>No es el mismo que el identificador de suscripción en la consola de administración de partners. Consulte Syndication_Partner_Subscription_Number.</p></td>
<td>usCBMgAAAAAAAAIA</td>
</tr>
<tr class="even">
<td>SyndicationPartnerSubscriptionNumber</td>
<td><p>Identificador único de las suscripciones. Un cliente puede tener varias suscripciones para el mismo plan, por lo que es importante para el análisis de archivos de conciliación.</p>
<p>Este campo se asigna al identificador de suscripción en la consola de administración de partners.</p></td>
<td>fb977ab5-test-test-test-24c8d9591708</td>
</tr>
<tr class="odd">
<td>OfferID</td>
<td><p>Identificador único de la oferta. Identificador de la oferta estándar según la lista de precios.</p>
<p><b>Nota</b>: Este valor no coincide con Id. de oferta desde la lista de precios. Consulta DurableOfferID a continuación.</p></td>
<td>FE616D64-E9A8-40EF-843F-152E9BBEF3D1</td>
</tr>
<tr class="even">
<td>DurableOfferID</td>
<td><p>Identificador único de oferta duradera, según se define en la lista de precios.</p>
<p><b>Nota</b>: Este valor coincide con el Id. de oferta desde la lista de precios.</p></td>
<td>1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</td>
</tr>
<tr class="odd">
<td>OfferName</td>
<td><p>Nombre de la oferta de servicio adquirida por el cliente, según se define en la lista de precios.</p></td>
<td>Microsoft Office 365 (Plan E3)</td>
</tr>
<tr class="even">
<td>SubscriptionStartDate</td>
<td><p>Fecha de finalización de la suscripción, establecida en el día posterior al envío del pedido. Al consultar la fecha de inicio de la suscripción junto con la fecha de finalización, puedes determinar si el cliente aún está dentro del primer año de la suscripción o si la suscripción se ha renovado para el año siguiente.</p>
<p>La hora siempre corresponde al comienzo del día, 0:00.</p></td>
<td>1/2/2015 0:00</td>
</tr>
<tr class="odd">
<td>SubscriptionEndDate</td>
<td><p>La fecha de finalización de la suscripción: 12 meses + x días después de la fecha de inicio (para alinearse con fecha de facturación del asociado) o 12 meses a partir de la fecha de renovación.</p>
<p>En el momento de la renovación, los precios se actualizan según la lista de precios actual. Es posible que se necesite una comunicación con el cliente antes de la renovación automatizada.</p>
<p>La hora siempre corresponde al comienzo del día, 0:00.</p></td>
<td>1/2/2015 0:00</td>
</tr>
<tr class="even">
<td>ChargeStartDate</td>
<td><p>Día de inicio de los cargos.</p>
<p>Cuando un cliente cambia los números de puestos, este número se usa para calcular los cargos por día (proporcionales).</p>
<p>La hora siempre corresponde al comienzo del día, 0:00.</p></td>
<td>1/2/2015 0:00</td>
</tr>
<tr class="odd">
<td>ChargeEndDate</td>
<td><p>Día de finalización de los cargos.</p>
<p>Cuando un cliente cambia los números de puestos, este número se usa para calcular los cargos por día (proporcionales).</p>
<p>La hora siempre corresponde al fin del día, 23:59.</p></td>
<td>28/2/2015 23:59</td>
</tr>
<tr class="even">
<td>ChargeType</td>
<td><p>Tipo de cargo o ajuste. Consulta <a href="#charge_types">Asignación de cargos entre una factura y el archivo de conciliación</a></p></td>
<td><p>Consulta <a href="#charge_types">Asignación de cargos entre una factura y el archivo de conciliación</a></p></td>
</tr>
<tr class="odd">
<td>UnitPrice</td>
<td><p>Precio por puesto, tal y como se publica en la lista de precios en el momento de compra. Asegúrate de que coincide con la información almacenada en tu sistema de facturación durante la conciliación.</p></td>
<td>6.82</td>
</tr>
<tr class="even">
<td>Cantidad</td>
<td><p>Número de puestos. Asegúrate de que coincide con la información almacenada en tu sistema de facturación durante la conciliación.</p></td>
<td>2</td>
</tr>
<tr class="odd">
<td>Volumen</td>
<td><p>Total del precio para la cantidad. Es de utilidad para comprobar que el cálculo de la cantidad coincide con la manera de calcular este valor para los clientes.</p></td>
<td>13.32</td>
</tr>
<tr class="even">
<td>TotalOtherDiscount</td>
<td><p>Cantidad de descuento que se aplica a estos cargos. Los IUR o las nuevas suscripciones que puedan optar a un incentivo también incluirán un importe de descuento en esta columna.</p></td>
<td>2.32</td>
</tr>
<tr class="odd">
<td>Subtotal</td>
<td><p>Total sin impuestos. Comprueba que el subtotal coincide con el total previsto, en el caso de un descuento.</p></td>
<td>11</td>
</tr>
<tr class="even">
<td>Impuestos</td>
<td><p>Importe de impuestos, según el mercado&#39;reglas s y circunstancias concretas.</p></td>
<td>0</td>
</tr>
<tr class="odd">
<td>TotalForCustomer</td>
<td><p>Total con impuestos. Comprueba si se cobran impuestos en la factura.</p></td>
<td>11</td>
</tr>
<tr class="even">
<td>Moneda</td>
<td><p>Tipo de moneda. Cada entidad de facturación tiene una sola moneda. Comprueba que coincide con la primera factura y repite la comprobación tras cualquier actualización importante de la plataforma de facturación.</p></td>
<td>EUR</td>
</tr>
<tr class="odd">
<td>CustomerName</td>
<td><p>Cliente&#39;nombre de la organización s notificados en el centro de partners. Esto es muy importante para conciliar la factura con la información del sistema.</p></td>
<td>Cliente de prueba A</td>
</tr>
<tr class="even">
<td>MPNID</td>
<td><p>Id. de MPN del partner CSP</p></td>
<td>4390934</td>
</tr>
<tr class="odd">
<td>ResellerMPNID</td>
<td><p>Id. de MPN del revendedor de registro de la suscripción. Ver <a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">Desglosar por partner</a></p></td>
<td>4390934</td>
</tr>
<tr class="even">
<td>DomainName</td>
<td><p>Cliente&#39;nombre de dominio de s, que ayuda a identificar el cliente. No debe usarse para identificar al cliente como el cliente o socio puede actualizar el dominio personal de forma predeterminada a través del portal de Office 365. Este campo puede aparecer en blanco hasta el segundo ciclo de facturación.</p></td>
<td>ejemplo.onmicrosoft.com</td>
</tr>
<tr class="odd">
<td>SubscriptionName</td>
<td><p>Alias de la suscripción. Si no se especifica ningún alias, el Centro de partners usa OfferName.</p></td>
<td>PROJECT ONLINE</td>
</tr>
<tr class="even">
<td>SubscriptionDescription</td>
<td><p>Nombre de la oferta de servicio adquirida por el cliente, según se define en la lista de precios. (Este es un campo idéntico al nombre de la oferta).</p></td>
<td>PROJECT ONLINE PREMIUM SIN CLIENTE DE PROJECT</td>
</tr>
</tbody>
</table>


## <a href="" id="usagebasedfiles"></a>Campos de archivo basada en uso


Para conciliar los cargos en función del uso de tu cliente, compara los valores de ResellerID/ResellerName/ResellerBillableAccount del archivo de conciliación, el nombre del cliente y el id. de suscripción del Centro de partners.

Los siguientes campos explican los servicios usados y la clasificación.

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><strong>Columna</strong></td>
<td><strong>Descripción</strong></td>
<td><strong>Valor de ejemplo</strong></td>
</tr>
<tr class="even">
<td>PartnerID</td>
<td><p>Id. de partner, en formato de GUID.</p></td>
<td>DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</td>
</tr>
<tr class="odd">
<td>PartnerName</td>
<td><p>Nombre del partner.</p></td>
<td>Acme Incorporated</td>
</tr>
<tr class="even">
<td>PartnerBillableAccountID</td>
<td><p>Id. de cuenta del partner.</p></td>
<td>1010578050</td>
</tr>
<tr class="odd">
<td>CustomerName</td>
<td><p>Cliente&#39;nombre de la organización s notificados en el centro de partners. Esto es muy importante para conciliar la factura con la información del sistema.</p></td>
<td>Cliente de prueba A</td>
</tr>
<tr class="even">
<td>MPNID</td>
<td><p>Id. de MPN del partner CSP.</p></td>
<td>4390934</td>
</tr>
<tr class="odd">
<td>ResellerMPNID</td>
<td><p>Id. de MPN del revendedor de registro de la suscripción. Ver <a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">Desglosar por partner</a></p></td>
<td>4390934</td>
</tr>
<tr class="even">
<td>InvoiceNumber</td>
<td><p>Número de factura donde aparece la transacción especificada.</p></td>
<td>D020001IVK</td>
</tr>
<tr class="odd">
<td>ChargeStartDate</td>
<td><p>Fecha de inicio del ciclo de facturación, excepto cuando se presentan fechas de datos de uso latentes no cargados previamente (del ciclo de facturación anterior).</p>
<p>La hora siempre corresponde al comienzo del día, 0:00.</p></td>
<td>1/2/2014 0:00</td>
</tr>
<tr class="even">
<td>ChargeEndDate</td>
<td><p>Fecha de finalización del ciclo de facturación, excepto cuando se presentan fechas de datos de uso latentes no cargados previamente (del ciclo de facturación anterior).</p>
<p>La hora siempre corresponde al fin del día, 23:59.</p></td>
<td>28/2/2014 23:59</td>
</tr>
<tr class="odd">
<td>SubscriptionID</td>
<td><p>Identificador único de una suscripción en la plataforma de facturación de Microsoft. Puede ser útil para identificar a la suscripción al ponerse en contacto con el soporte técnico, pero no para la reconciliación.</p>
<p>No es el mismo que el identificador de suscripción en la consola de administración de partners.</p></td>
<td>usCBMgAAAAAAAAIA</td>
</tr>
<tr class="even">
<td>SubscriptionName</td>
<td><p>Alias de la oferta de servicio.</p></td>
<td>Microsoft Azure</td>
</tr>
<tr class="odd">
<td>SubscriptionDescription</td>
<td><p>Línea de negocio de la oferta de servicio</p></td>
<td>Microsoft Azure</td>
</tr>
<tr class="even">
<td>OrderID</td>
<td><p>Identificador único de un pedido en la plataforma de facturación de Microsoft. Puede ser útil para identificar a la suscripción al ponerse en contacto con el soporte técnico, pero no para la reconciliación.</p></td>
<td>566890604832738111</td>
</tr>
<tr class="odd">
<td>ServiceName</td>
<td><p>Nombre del servicio de Azure en cuestión.</p></td>
<td>MÁQUINAS VIRTUALES</td>
</tr>
<tr class="even">
<td>ServiceType</td>
<td><p>Tipo específico de servicio de Microsoft Azure.</p></td>
<td><ul>
<li>Bus de servicio: individual o paquete</li>
<li>Base de datos SQL Azure: edición Business o Web</li>
</ul></td>
</tr>
<tr class="odd">
<td>ResourceGUID</td>
<td><p>Identificador único específico para toda la estructura de precios y datos del servicio.</p></td>
<td>DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</td>
</tr>
<tr class="even">
<td>Nombre de recurso</td>
<td><p>Nombre del recurso de Azure.</p></td>
<td><ul>
<li>Transferencia entrante de datos (GB)</li>
<li>Transferencia saliente de datos (GB)</li>
</ul></td>
</tr>
<tr class="odd">
<td>Region</td>
<td><p>La región a la que se aplica el uso. Se usa principalmente para asignar tarifas a las transferencias de datos, ya que las tarifas varían según la región.</p></td>
<td>Asia Pacífico, Europa, América Latina, América del Norte</td>
</tr>
<tr class="even">
<td>SKU</td>
<td><p>Identificador único de MSFT para la oferta</p></td>
<td>7UD 00001</td>
</tr>
<tr class="odd">
<td><p>DetailLineItemId</p></td>
<td><p>Un id. y una cantidad para desglosar las distintas clasificaciones de un servicio o un recurso en un período de facturación determinado. Para clasificación en niveles de Azure, puede haber una clasificación hasta una cantidad determinada de unidades facturables y, posteriormente, una clasificación diferente.</p></td>
<td>1</td>
</tr>
<tr class="even">
<td>ConsumedQuantity</td>
<td><p>La cantidad de servicio consumida (horas, GB, etc.) durante el período de notificación.</p>
<p>También incluye cualquier uso no facturado de períodos anteriores.</p></td>
<td>11</td>
</tr>
<tr class="odd">
<td>IncludedQuantity</td>
<td><p>Unidades que se incluyen como parte de la oferta. No suele mostrarse en CSP.</p></td>
<td>0</td>
</tr>
<tr class="even">
<td><p>OverageQuantity</p></td>
<td><p>Unidades que no se incluyen como parte de la oferta y que el partner debe abonar.</p>
<p>Equivale a ConsumedQuantity - IncludedQuantity.</p></td>
<td>11</td>
</tr>
<tr class="odd">
<td>ListPrice</td>
<td><p>Precio de la oferta en vigor la fecha de inicio de la suscripción.</p></td>
<td>0.0808 USD</td>
</tr>
<tr class="even">
<td>PretaxCharges</td>
<td><p>ListPrist x OverageQuantity, redondeado al céntimo más próximo.</p></td>
<td>0.085 USD</td>
</tr>
<tr class="odd">
<td>TaxAmount</td>
<td><p>Importe de impuestos, según el mercado&#39;reglas s y circunstancias concretas.</p></td>
<td>0.08 USD</td>
</tr>
<tr class="even">
<td>PostTaxTotal</td>
<td><p>Total con impuestos, si se aplican impuestos.</p></td>
<td>0.93 USD</td>
</tr>
<tr class="odd">
<td>Moneda</td>
<td><p>Tipo de moneda. Cada entidad de facturación tiene una sola moneda. Comprueba que coincide con la primera factura y repite la comprobación tras cualquier actualización importante de la plataforma de facturación.</p></td>
<td>EUR</td>
</tr>
<tr class="even">
<td>PretaxEffectiveRate</td>
<td><p>Precio sin impuestos por unidad. Igual que PretaxCharges/OverageQuantity, redondeado al céntimo más próximo.</p></td>
<td>0.08 USD</td>
</tr>
<tr class="odd">
<td>PostTaxEffectiveRate</td>
<td><p>Precio después de impuestos por unidad. Igual que PostTaxTotal/OverageQuantity o PretaxEffectiveRate + tipo impositivo por importe unitario, redondeado el céntimo más próximo.</p></td>
<td>0.08 USD</td>
</tr>
<tr class="even">
<td>ChargeType</td>
<td><p>Tipo de cargo o ajuste. Consulta <a href="#charge_types">Asignación de cargos entre una factura y el archivo de conciliación</a></p></td>
<td><p>Consulta <a href="#charge_types">Asignación de cargos entre una factura y el archivo de conciliación</a></p></td>
</tr>
<tr class="odd">
<td>CustomerBillableAccount</td>
<td><p>Id. de cuenta único en la plataforma de facturación de MSFT.</p></td>
<td>1280018095</td>
</tr>
<tr class="even">
<td>UsageDate</td>
<td><p>Fecha de implementación del servicio.</p></td>
<td>1/2/2014 0:00</td>
</tr>
<tr class="odd">
<td>MeteredRegion</td>
<td><p>Esta columna identifica la ubicación de un centro de datos dentro de la región para los servicios donde esto se aplica y rellena.</p></td>
<td>Asia oriental, Sur asiático, Norte de Europa, Europa occidental, Norte central de EE. UU., Sur central de EE. UU.</td>
</tr>
<tr class="even">
<td>MeteredService</td>
<td><p>Esta columna se usa para hacer un seguimiento de los servicios de Microsoft Azure individuales que quizás no se identifiquen específicamente en la columna Service Name. Por ejemplo, las transferencias de datos se notifican como &quot;Microsoft Azure: todos los servicios&quot; en la columna Service Name. En esta columna MeteredService se indicará qué servicio específico pertenece el uso.</p></td>
<td>AccessControl, CDN, Proceso, Base de datos, ServiceBus, Almacenamiento</td>
</tr>
<tr class="odd">
<td>MeteredServiceType</td>
<td><p>Subtítulo que aclara el servicio de Microsoft Azure individual más allá del nivel proporcionado por el campo MeteredService.</p></td>
<td>EXTERNO</td>
</tr>
<tr class="even">
<td>Proyecto</td>
<td><p>Nombre definido por el cliente para la instancia del servicio</p></td>
<td>ORDDC52E52FDEF405786F0642DD0108BE4</td>
</tr>
<tr class="odd">
<td>ServiceInfo</td>
<td><p>Número de conexiones de Bus de servicio aprovisionadas y usadas en un día determinado.</p></td>
<td>Por ejemplo: si tenías una conexión aprovisionada individualmente durante un mes de 30 días, Service Info 1 contendría 1 "1,000000 conexiones/30 días". Si tuviera un paquete de 25 de conexiones de bus de servicio aprovisionada y ha utilizado 1 durante ese día, el extracto de uso diario durante ese día indicaría "25 conexiones / 30 días: utilizado: 1.000000”.</td>
</tr>
<tr class="even">
<td>CustomerID</td>
<td><p>Id. de Microsoft único, en formato GUID, usado para identificar al cliente.</p></td>
<td>ORDDC52E52FDEF405786F0642DD0108BE4</td>
</tr>
<tr class="odd">
<td>DomainName</td>
<td><p>Cliente&#39;nombre de dominio de s, que ayuda a identificar el cliente. Este campo puede aparecer en blanco hasta el segundo ciclo de facturación.</p></td>
<td>ejemplo.onmicrosoft.com</td></tr>
</tr>
<tr class="even">
<td>Unidad</td>
<td><p>La unidad del nombre del recurso</p></td>
<td>GB u HORAS</td>
</tr>
</tbody>
</table>

## <a href="" id="marketplacefilefields"></a>Campos del archivo periódicas y únicas

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Column</th>
<th>Descripción</th>
</tr>
</thead>
<tbody>


<tr class="odd">
<td>PartnerId</td>
<td><p>Identificador único del inquilino de Microsoft Azure Active Directory para una entidad de facturación específica, en formato GUID. No es necesario para la reconciliación, pero puede ser información útil. Igual en todas las filas.</p></td>
</tr>

<tr class="even">
<td>Id. de cliente</td>
<td><p>Microsoft Azure Active Directory inquilino identificador único, en formato GUID, que usa para identificar al cliente.</p></td>
</tr>

<tr class="odd">
<td>Nombre del cliente</td>
<td><p>Nombre de la organización del cliente según se indica en el Centro de partners.</p></td>
</tr>

<tr class="even">
<td>CustomerDomainName</td>
<td><p>Nombre de dominio del cliente, que se usa para identificar al cliente. No debe usarse para identificar al cliente como el cliente o socio puede actualizar el dominio personal de forma predeterminada a través del portal de Office 365. Este campo puede aparecer en blanco hasta el segundo ciclo de facturación.</p></td>
</tr>

<tr class="odd">
<td>País del cliente</td>
<td><p>El país donde se encuentra el cliente.</p></td>
</tr>

<tr class="even">
<td>Número de factura</td>
<td><p>Número de factura donde aparece la transacción especificada.</p></td>
</tr>

<tr class="odd">
<td>MpnId</td>
<td><p>Id. de MPN del partner CSP.</p></td>
</tr>

<tr class="even">
<td>Reseller MpnId</td>
<td><p>Id. de MPN del revendedor de registro de la suscripción.</p></td>
</tr>

<tr class="odd">
<td>Id. de pedido</td>
<td><p>Identificador único para un pedido en la plataforma de comercio de Microsoft. Puede ser útil para identificar al pedido al ponerse en contacto con el soporte técnico, pero no para la conciliación.</p></td>
</tr>

<tr class="even">
<td>Fecha del pedido</td>
<td><p>Fecha de realización del pedido.</p></td>
</tr>

<tr class="odd">
<td>ProductId</td>
<td><p>Identificador del producto.</p></td>
</tr>

<tr class="even">
<td>SkuId</td>
<td><p>Id. de un SKU concreto.</p></td>
</tr>

<tr class="odd">
<td>AvailabilityId</td>
<td><p>Id. de una disponibilidad concreta. "Disponibilidad" hace referencia a si un SKU concreto está o no disponible para su compra para el país, la moneda, el segmento industrial determinados, etc.</p></td>
</tr>

<tr class="even">
<td>Nombre de SKU</td>
<td><p>Título para un SKU concreto.</p></td>
</tr>

<tr class="odd">
<td>Nombre del producto</td>
<td><p>Nombre del producto.</p></td>
</tr>

<tr class="even">
<td>PublisherName</td>
<td><p>El nombre del publicador del producto.</p></td>
</tr>

<tr class="odd">
<td>PublisherID</td>
<td><p>Identificador único para este publicador.</p></td>
</tr>

<tr class="even">
<td>Descripción de la suscripción</td>
<td><p>Nombre descriptivo de una suscripción.</p></td>
</tr>

<tr class="odd">
<td>Id. de la suscripción</td>
<td><p>Identificador único para una suscripción en la plataforma de comercio de Microsoft. Puede ser útil para identificar a la suscripción al ponerse en contacto con el soporte técnico, pero no para la reconciliación. No es el mismo que el identificador de suscripción en la consola de administración de partners.</p></td>
</tr>

<tr class="even">
<td>ChargeStartDate</td>
<td><p>Día de inicio de los cargos. La hora siempre corresponde al comienzo del día, 0:00.</p></td>
</tr>

<tr class="odd">
<td>ChargeEndDate</td>
<td><p>Día de finalización de los cargos. La hora siempre corresponde al fin del día, 23:59.</p></td>
</tr>

<tr class="even">
<td>Término y Billingcycle</td>
<td><p>La duración del período y ciclo de facturación para la compra. Por ejemplo, "1 año, mes".</p></td>
</tr>

<tr class="odd">
<td>Tipo de cargo</td>
<td><p>Tipo de cargo o ajuste.</p></td>
</tr>

<tr class="even">
<td>Precio unitario</td>
<td><p>El precio publicado en la lista de precios en el momento de la compra. Asegúrate de que coincide con la información almacenada en tu sistema de facturación durante la conciliación.</p></td>
</tr>

<tr class="odd">
<td>Precio unitario efectivo</td>
<td><p>El precio por unidad una vez realizados los ajustes.</p></td>
</tr>

<tr class="even">
<td>Cantidad</td>
<td><p>Número de unidades. Asegúrate de que coincide con la información almacenada en tu sistema de facturación durante la conciliación.</p></td>
</tr>

<tr class="odd">
<td>Tipo de unidad</td>
<td><p>El tipo de unidad que se compra.</p></td>
</tr>

<tr class="even">
<td>DiscountDetails</td>
<td><p>Explicación de los descuentos aplicables.</p></td>
</tr>

<tr class="odd">
<td>Subtotal</td>
<td><p>Total sin impuestos. Comprueba que el subtotal coincide con el total previsto, en el caso de un descuento.</p></td>
</tr>

<tr class="even">
<td>Total de impuestos</td>
<td><p>Cargo por importe de impuestos, en función de las reglas fiscales de tu mercado y las circunstancias específicas.</p></td>
</tr>

<tr class="odd">
<td>Total</td>
<td><p>Total con impuestos. Comprueba si se cobran impuestos en la factura.</p></td>
</tr>

<tr class="even">
<td>Moneda</td>
<td><p>Tipo de moneda. Cada entidad de facturación tiene una sola moneda. Comprueba que coincide con la primera factura y repite la comprobación tras cualquier actualización importante de la plataforma de facturación.</p></td>
</tr>

<tr class="odd">
<td>AlternateID</td>
<td><p>Un identificador alternativo para un identificador de pedido.</p></td>
</tr>
</tbody>
</table>


## <a href="" id="dailyratedusagefields"></a>Campos del archivo de uso diario calificados


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Column</th>
<th>Descripción</th>
</tr>
</thead>
<tbody>

<tr class="odd">
<td>PartnerId</td>
<td><p>Id. de partner, en formato de GUID.</p></td>
</tr>

<tr class="even">
<td>PartnerName</td>
<td><p>Nombre del partner.</p></td>
</tr>

<tr class="odd">
<td>CustomerId</td>
<td><p>Id. de Microsoft único, en formato GUID, usado para identificar al cliente.</p></td>
</tr>

<tr class="even">
<td>CustomerCompanyName</td>
<td><p>Nombre de la organización del cliente según se indica en el Centro de partners. Esto es muy importante para conciliar la factura con la información del sistema.</p></td>
</tr>

<tr class="odd">
<td>CustomerDomainName</td>
<td><p>Nombre de dominio del cliente. No está disponible para la actividad actual.</p></td>
</tr>

<tr class="even">
<td>País del cliente</td>
<td><p>El país donde se encuentra el cliente.</p></td>
</tr>

<tr class="odd">
<td>MPNID</td>
<td><p>Id. de MPN del partner CSP.</p></td>
</tr>

<tr class="even">
<td>Distribuidor MPNID</td>
<td><p>Id. de MPN del revendedor de registro de la suscripción. No está disponible para la actividad actual.</p></td>
</tr>

<tr class="odd">
<td>InvoiceNumber</td>
<td><p>Número de factura donde aparece la transacción especificada. No está disponible para la actividad actual.</p></td>
</tr>

<tr class="even">
<td>ProductId</td>
<td><p>Identificador del producto.</p></td>
</tr>

<tr class="odd">
<td>SkuId</td>
<td><p>Id. de un SKU concreto.</p></td>
</tr>

<tr class="even">
<td>AvailabilityId</td>
<td><p>Id. de una disponibilidad concreta. "Disponibilidad" hace referencia a si un SKU concreto está o no disponible para su compra para el país, la moneda, el segmento industrial determinados, etc.</p></td>
</tr>

<tr class="odd">
<td>Nombre de SKU</td>
<td><p>Título para un SKU concreto.</p></td>
</tr>

<tr class="even">
<td>PublisherName</td>
<td><p>El nombre del publicador.</p></td>
</tr>

<tr class="odd">
<td>PublisherID</td>
<td><p>El identificador del publicador, en formato GUID. No está disponible para la actividad actual.</p></td>
</tr>

<tr class=”even">
<td>Descripción de la suscripción</td>
<td><p>Nombre de la oferta de servicio adquirida por el cliente, según se define en la lista de precios. (Este es un campo idéntico al nombre de la oferta).</p></td>
</tr>

<tr class="odd">
<td>Id. de la suscripción</td>
<td><p>Identificador único de una suscripción en la plataforma de facturación de Microsoft. Puede ser útil para identificar a la suscripción al ponerse en contacto con el soporte técnico, pero no para la reconciliación. No es el mismo que el identificador de suscripción en la consola de administración de partners.</p></td>
</tr>

<tr class="even">
<td>ChargeStartDate</td>
<td><p>Fecha de inicio del ciclo de facturación, excepto cuando se presentan fechas de datos de uso latentes no cargados previamente (del ciclo de facturación anterior). La hora siempre corresponde al comienzo del día, 0:00.</p></td>
</tr>

<tr class="odd">
<td>ChargeEndDate</td>
<td><p>Fecha de finalización del ciclo de facturación, excepto cuando se presentan fechas de datos de uso latentes no cargados previamente (del ciclo de facturación anterior). La hora siempre corresponde al fin del día, 23:59.</p></td>
</tr>

<tr class="even">
<td>Fecha de uso</td>
<td><p>Fecha de uso del servicio.</p></td>
</tr>

<tr class="odd">
<td>Tipo de medidor</td>
<td><p>El tipo de medidor.</p></td>
</tr>

<tr class="even">
<td>Categoría de medidor</td>
<td><p>El servicio de nivel superior para el uso.</p></td>
</tr>

<tr class="odd">
<td>Id. de medidor</td>
<td><p>El identificador del medidor que se va a usar.</p></td>
</tr>

<tr class="even">
<td>Subcategoría de medidor</td>
<td><p>El tipo de servicio de Azure que puede afectar a la tarifa.</p></td>
</tr>

<tr class="odd">
<td>Nombre de medidor</td>
<td><p>La unidad de medida del medidor consumido.</p></td>
</tr>

<tr class="even">
<td>Región de medidor</td>
<td><p>Esta columna identifica la ubicación de un centro de datos dentro de la región para los servicios donde esto se aplica y rellena.</p></td>
</tr>

<tr class="odd">
<td>Unidad</td>
<td><p>La unidad del nombre de recurso.</p></td>
</tr>

<tr class="even">
<td>Cantidad consumida</td>
<td><p>La cantidad de servicio consumida (horas, GB, etc.) durante el período de notificación. También incluye cualquier uso no facturado de períodos anteriores.</p></td>
</tr>

<tr class="odd">
<td>Ubicación de recursos</td>
<td><p>El centro de datos donde se está ejecutando el medidor.</p></td>
</tr>

<tr class="even">
<td>Servicio consumido</td>
<td><p>El servicio de la plataforma Azure que usó.</p></td>
</tr>

<tr class="odd">
<td>Grupo de recursos</td>
<td><p>El grupo de recursos en el que se está ejecutando el medidor implementado.</p></td>
</tr>

<tr class="even">
<td>URI de recurso</td>
<td><p>El URI del recurso que se va a usar.</p></td>
</tr>

<tr class="odd">
<td>Tipo de cargo</td>
<td><p>Tipo de cargo o ajuste. No está disponible para la actividad actual.</p></td>
</tr>

<tr class="even">
<td>Precio unitario</td>
<td><p>Precio por licencia, como se publica en la lista de precios en el momento de la compra. Asegúrate de que coincide con la información almacenada en tu sistema de facturación durante la conciliación.</p></td>
</tr>

<tr class="odd">
<td>Cantidad</td>
<td><p>Número de licencias. Asegúrate de que coincide con la información almacenada en tu sistema de facturación durante la conciliación.</p></td>
</tr>

<tr class="even">
<td>Tipo de unidad</td>
<td><p>El tipo de unidad que se cobra el medidor. No está disponible para la actividad actual.</p></td>
</tr>

<tr class="odd">
<td>Impuestos de facturación anterior a</td>
<td><p>Cantidad total antes de impuestos.</p></td>
</tr>

<tr class="even">
<td>Divisa de facturación</td>
<td><p>La moneda en la región geográfica del cliente</p></td>
</tr>

<tr class="odd">
<td>Precio total antes de impuestos</td>
<td><p>Los precios antes de que se agregan los impuestos.</p></td>
</tr>

<tr class="even">
<td>Precios de moneda</td>
<td><p>La moneda en la lista de precios.</p></td>
</tr>

<tr class="odd">
<td>Información de servicio 1</td>
<td><p>Número de conexiones de Bus de servicio aprovisionadas y usadas en un día determinado.</p></td>
</tr>

<tr class="even">
<td>Información de servicio 2</td>
<td><p>Un campo heredado que captura los metadatos específicos del servicio opcional.</p></td>
</tr>

<tr class="odd">
<td>Etiquetas</td>
<td><p>Etiquetas que asigna al medidor en orden para agrupar los registros de facturación. Por ejemplo, puede usar etiquetas para distribuir los costos por el departamento que utiliza el medidor.</p></td>
</tr>

<tr class="even">
<td>Información adicional</td>
<td><p>Cualquier información adicional que no se tratan en otras columnas.</p></td>
</tr>

</tbody>
</table>


## <a href="" id="charge_types"></a>Asignación de cargos entre una factura y el archivo de conciliación

La factura proporciona un resumen de los cargos, mientras que el archivo de conciliación proporciona un desglose detallado de las transacciones de elementos de línea, incluidos los tipos de cargo.

Para hacer referencias cruzadas de cantidades de cargos entre el archivo de conciliación y la factura, puedes usar las opciones de filtro de Microsoft Excel para filtrar por tipo de cargo en el archivo de conciliación con el fin de asignar los cargos de facturación a un conjunto de desgloses de cargos del archivo de conciliación.

Los archivos de conciliación, tanto basados en uso como en licencias, solo muestran cargos y transacciones relacionados con el uso (unidades consumidas y cargos relacionados). En el archivo de conciliación no aparecen devoluciones, descuentos o créditos excepcionales que aparecen en la factura como "Ajustes".

La siguiente tabla muestra las asignaciones entre una sección de factura y los tipos de cargo asociados que es posible que se muestren en los archivos de conciliación. 

<table>
<tbody>
<tr>
<td>
<p><strong>Descripción de cargos de facturación</strong></p>
</td>
<td>
<p><strong>Descripción de cargos del archivo de conciliación (columna ChargeType)</strong></p>
</td>
<td>
<p><strong>¿Qué es este cargo?</strong></p>
</td>
<td>
<p><strong>¿Cómo se asignan estos ChargeTypes a la factura?</strong></p>
</td>
</tr>
<tr>
<td rowspan="10">
<p><strong>Cargos de licencia</strong></p>
</td>
<td>
<p>Tarifa de activación</p>
</td>
<td>
<p>El importe cobrado al cliente cuando usa la suscripción después de adquirirla</p>
</td>
<td rowspan="10">
<p>Desde el archivo basado en licencia, suma la columna <strong>Amount</strong>.</p>
</td>
</tr>
<tr>
<td>
<p>Cuota de cancelación</p>
</td>
<td>
<p>Cargos prorrateados reembolsados al cliente al cambiar los puestos asociados</p>
</td>
</tr>
<tr>
<td>
<p>Tarifa de ciclo</p>
</td>
<td>
<p>Cargos periódicos de una suscripción</p>
</td>
</tr>
<tr>
<td>
<p>Prorrateo de instancia de ciclo</p>
</td>
<td>
<p>Cargos prorrateados evaluados del cliente al cambiar los puestos asociados</p>
</td>
</tr>
<tr>
<td>
<p>Tarifas prorrateadas al cancelar</p>
</td>
<td>
<p>Reembolso prorrateado de la parte no usada del servicio tras la cancelación</p>
</td>
</tr>
<tr>
<td>
<p>Tarifas prorrateadas al comprar</p>
</td>
<td>
<p>El tipo de gasto para una suscripción cuando se usa la facturación anual</p>
</td>
</tr>
<tr>
<td>
<p>Tarifa de compra</p>
</td>
<td>
<p>El tipo de gasto para una suscripción cuando se usa la facturación mensual</p>
</td>
</tr>
<tr>
<td>
<p>Tarifa prorrateada al renovar</p>
</td>
<td>
<p>Tarifas prorrateadas tras la renovación de la suscripción</p>
</td>
</tr>
<tr>

<td>
<p>Tarifa de renovación</p>
</td>
<td>
<p>Cargo por renovar una suscripción</p>
</td>
</tr>
<tr>
<td>
<p>Tarifas prorrateadas al activar</p>
</td>
<td>
<p>Tarifas prorrateadas desde la activación hasta el final del período de facturación</p>
</td>
</tr>
<tr>
<td rowspan="2">
<p><strong>Cargos de uso</strong></p>
</td>
<td>
<p>Evaluar la tarifa de uso al cancelar</p>
</td>
<td>
<p>Tarifa de uso de acceso tras la cancelación por uso impagado durante el período de facturación actual</p>
</td>
<td rowspan="2">
<p>Desde el archivo basado en uso, suma la columna <strong>PretaxCharges</strong>.</p>
</td>
</tr>
<tr>
<td>
<p>Evaluar la tarifa de uso para el ciclo actual</p>
</td>
<td>
<p>tarifa de uso de acceso para el período de facturación actual</p>
</td>
</tr>
<tr>
<td>
<p><strong>Créditos</strong></p>
</td>
<td>
<p>Desplazamiento de un elemento de línea</p>
</td>
<td>
<p>Reembolso parcial o total de un elemento de línea, incluidos impuestos</p>
</td>
<td>
<p>Desde el archivo basado en licencia, suma la columna <strong>TotalForCustomer</strong>.</p>
<p>Desde el archivo basado en uso, suma la columna <strong>PostTaxTotal</strong>.</p>
</td>
</tr>
<tr>
<td rowspan="4">
<p><strong>Descuentos basados en uso</strong></p>
</td>
<td>
<p>Descuento de activación</p>
</td>
<td>
<p>Descuento que se aplica cuando se activa la suscripción</p>
</td>

<td rowspan="4">
<p>Desde el archivo basado en uso, suma la columna <strong>PretaxCharges</strong>.</p>
</td>
</tr>
<tr>
<td>
<p>Descuento de ciclo</p>
</td>
<td>
<p>Descuento que se aplica en cargos periódicos</p>
</td>
</tr>
<tr>
<td>
<p>Descuento de renovación</p>
</td>
<td>
<p>Descuento que se aplica cuando se renueva la suscripción</p>
</td>
</tr>
<tr>
<td>
<p>Descuento de cancelación</p>
</td>
<td>
<p>Cargos que se aplican cuando se cancelan los descuentos</p>
</td>
</tr>


<tr>
<td>
<p><strong>Descuentos de licencias</strong></p>
</td>
<td>
<p><em>Se pueden aplicar a varios tipos de cargos</em></p>
</td>
<td>
<p></p>
</td>
<td>
<p>Desde el archivo basado en licencia, suma la columna <strong>TotalOtherDiscount</strong>.</p>
</td>
</tr>
<tr>
<td>
<p><strong>Impuestos</strong>&nbsp;o&nbsp;<strong>IVA</strong></p>
</td>
<td>
<p><em>Se pueden aplicar a varios tipos de cargos</em></p>
<p><em>Excepción: &quot;Desplazamiento de un elemento de línea&quot; ya incluye los impuestos. Consulte los créditos, más arriba.</em></p>
</td>
<td>
<p>Impuestos o impuesto de valor añadido (IVA)</p>
</td>
<td>
<p>Desde el archivo basado en licencia, suma la columna <strong>Tax</strong>.</p>
<p>Desde el archivo basado en uso, suma la columna <strong>TaxAmount</strong>.</p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
