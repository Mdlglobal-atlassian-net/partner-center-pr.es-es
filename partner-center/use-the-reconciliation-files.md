---
title: Usar los archivos de conciliación | Centro de partners
ms.topic: article
ms.date: 10/29/2018
description: Para obtener una vista detallada del elemento de línea de cada cargo en un ciclo de facturación, descarga los archivos de conciliación del centro de partners.
ms.assetid: FA6A6FCB-2597-44E7-93F8-8D1DD35D52EA
author: KPacquer
ms.author: kenpacq
ms.localizationpriority: medium
ms.openlocfilehash: 50af14ab0e8edf6cd4576be6615cd7238b23bd99
ms.sourcegitcommit: 9ea2f05f938ea22251f3719b61f03ccb71d3494f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/03/2019
ms.locfileid: "8990997"
---
# <a name="use-the-reconciliation-files"></a><span data-ttu-id="5b901-103">Usar los archivos de conciliación</span><span class="sxs-lookup"><span data-stu-id="5b901-103">Use the reconciliation files</span></span>

**<span data-ttu-id="5b901-104">Se aplica a</span><span class="sxs-lookup"><span data-stu-id="5b901-104">Applies to</span></span>**

-  <span data-ttu-id="5b901-105">Centro de partners</span><span class="sxs-lookup"><span data-stu-id="5b901-105">Partner Center</span></span>
-  <span data-ttu-id="5b901-106">Centro de partners para Microsoft Cloud for US Government</span><span class="sxs-lookup"><span data-stu-id="5b901-106">Partner Center for Microsoft Cloud for US Government</span></span>


<span data-ttu-id="5b901-107">Para obtener una vista detallada del elemento de línea de cada cargo en un ciclo de facturación, descarga los archivos de conciliación del centro de partners.</span><span class="sxs-lookup"><span data-stu-id="5b901-107">For a detailed line-item view of each charge in a billing cycle, download the reconciliation files from Partner Center.</span></span> <span data-ttu-id="5b901-108">Los detalles incluyen los cargos para las suscripciones de cada cliente y los eventos detallados (por ejemplo, una adición intermedia de puestos en una suscripción).</span><span class="sxs-lookup"><span data-stu-id="5b901-108">The details include charges for each customer's subscriptions, and detailed events (such as a mid-term addition of seats to a subscription).</span></span>

## <a href="" id="itemizebypartner"></a><span data-ttu-id="5b901-109">Desglosar por partner</span><span class="sxs-lookup"><span data-stu-id="5b901-109">Itemize by partner</span></span>


<span data-ttu-id="5b901-110">Los partners del modelo indirecto pueden usar estos campos adicionales en ambos archivos de conciliación basada en uso y en licencia para realizar el desglose por revendedor.</span><span class="sxs-lookup"><span data-stu-id="5b901-110">Partners in the indirect model can use these additional fields in both license-based and usage-based reconciliation files to itemize by reseller.</span></span>

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="5b901-111">Id. de MPN</span><span class="sxs-lookup"><span data-stu-id="5b901-111">MPN ID</span></span></th>
<th><span data-ttu-id="5b901-112">Descripción</span><span class="sxs-lookup"><span data-stu-id="5b901-112">Description</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="5b901-113">Id. de MPN</span><span class="sxs-lookup"><span data-stu-id="5b901-113">MPN ID</span></span></td>
<td><p><span data-ttu-id="5b901-114">Id. de Microsoft Partner Network (MPN) del partner de CSP (directo o indirecto).</span><span class="sxs-lookup"><span data-stu-id="5b901-114">The Microsoft Partner Network (MPN) ID of the CSP partner (direct or indirect).</span></span></p></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-115">Id. de MPN del revendedor</span><span class="sxs-lookup"><span data-stu-id="5b901-115">Reseller MPN ID</span></span></td>
<td><p><span data-ttu-id="5b901-116">Solo aparece en los archivos de conciliación de partners en el modelo indirecto.</span><span class="sxs-lookup"><span data-stu-id="5b901-116">Only appears on reconciliation files for partners in the indirect model.</span></span></p>
<p><span data-ttu-id="5b901-117">El Id. de MPN del revendedor de registro de la suscripción.</span><span class="sxs-lookup"><span data-stu-id="5b901-117">The MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="5b901-118">Corresponde al id. de revendedor indicado para la suscripción específica en el Centro de partners.</span><span class="sxs-lookup"><span data-stu-id="5b901-118">This corresponds to the reseller ID listed for the specific subscription in Partner Center.</span></span></p>
<p><span data-ttu-id="5b901-119">Para ver o actualizar el revendedor, en el menú del centro de partners, selecciona <strong>los clientes</strong>y luego elige el cliente de la lista.</span><span class="sxs-lookup"><span data-stu-id="5b901-119">eTo view or update the reseller, from the Partner Center menu, select <strong>Customers</strong>, then choose the customer from the list.</span></span> <span data-ttu-id="5b901-120">En el menú del cliente, selecciona <strong>Suscripciones</strong> y elige la suscripción de la lista.</span><span class="sxs-lookup"><span data-stu-id="5b901-120">In the customer menu, select <strong>Subscriptions</strong>, choose the subscription from the list.</span></span> <span data-ttu-id="5b901-121">Selecciona <strong>Actualizar</strong> para cambiar el valor de <strong>Revendedor (id. de MPN)</strong>.</span><span class="sxs-lookup"><span data-stu-id="5b901-121">Select <strong>update</strong> to change the <strong>Reseller (MPN ID)</strong>.</span></span></p>
<p><span data-ttu-id="5b901-122">Si un partner CSP vendió la suscripción directamente al cliente, su id. de MPN aparece dos veces, como id. de MPN y como id. de MPN del revendedor.</span><span class="sxs-lookup"><span data-stu-id="5b901-122">If a CSP partner sold the subscription directly to the customer, their MPN ID is listed twice, as both the MPN ID and the Reseller MPN ID.</span></span></p>
<p><span data-ttu-id="5b901-123">Si un partner CSP tiene un revendedor sin un id. de MPN, este valor se establece en el id. de MPN del partner.</span><span class="sxs-lookup"><span data-stu-id="5b901-123">If a CSP partner has a reseller with no MPN ID, this value is set to the partner’s MPN ID instead.</span></span></p>
<p><span data-ttu-id="5b901-124">Si el partner CSP quita un id. de revendedor, este valor se establece en -1.</span><span class="sxs-lookup"><span data-stu-id="5b901-124">If the CSP partner removes a reseller ID, this value will be set to -1.</span></span></p></td>
</tr>
</tbody>
</table>

 

## <a href="" id="licensebasedfiles"></a> <span data-ttu-id="5b901-125">Campos de archivo basados en licencia</span><span class="sxs-lookup"><span data-stu-id="5b901-125">License-based file fields</span></span>


<span data-ttu-id="5b901-126">Para conciliar los cargos en función de los pedidos del cliente, compara el Syndication\_Partner\_Subscription\_Number del archivo de conciliación con el identificador de suscripción del Centro de partners.</span><span class="sxs-lookup"><span data-stu-id="5b901-126">To reconcile your charges against your customer's orders, compare the Syndication\_Partner\_Subscription\_Number from the reconciliation file against the Subscription ID from Partner Center.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><strong><span data-ttu-id="5b901-127">Columna</span><span class="sxs-lookup"><span data-stu-id="5b901-127">Column</span></span></strong></td>
<td><strong><span data-ttu-id="5b901-128">Descripción</span><span class="sxs-lookup"><span data-stu-id="5b901-128">Description</span></span></strong></td>
<td><strong><span data-ttu-id="5b901-129">Valor de muestra</span><span class="sxs-lookup"><span data-stu-id="5b901-129">Sample Value</span></span></strong></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-130">PartnerId</span><span class="sxs-lookup"><span data-stu-id="5b901-130">PartnerId</span></span></td>
<td><p><span data-ttu-id="5b901-131">Identificador único de una entidad de facturación específica, con formato de GUID.</span><span class="sxs-lookup"><span data-stu-id="5b901-131">Unique identifier for a specific billing entity, in GUID format.</span></span> <span data-ttu-id="5b901-132">No es necesario para la reconciliación, pero puede ser información útil.</span><span class="sxs-lookup"><span data-stu-id="5b901-132">Not required for reconciliation, however may be useful information.</span></span> <span data-ttu-id="5b901-133">Igual en todas las filas.</span><span class="sxs-lookup"><span data-stu-id="5b901-133">Same in all rows.</span></span></p></td>
<td><span data-ttu-id="5b901-134">8ddd03642-test-test-test-46b58d356b4e</span><span class="sxs-lookup"><span data-stu-id="5b901-134">8ddd03642-test-test-test-46b58d356b4e</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-135">CustomerID</span><span class="sxs-lookup"><span data-stu-id="5b901-135">CustomerID</span></span></td>
<td><p><span data-ttu-id="5b901-136">Id. de Microsoft único, en formato GUID, usado para identificar al cliente.</span><span class="sxs-lookup"><span data-stu-id="5b901-136">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="5b901-137">12ABCD34-001A-BCD2-987C-3210ABCD5678</span><span class="sxs-lookup"><span data-stu-id="5b901-137">12ABCD34-001A-BCD2-987C-3210ABCD5678</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-138">OrderID</span><span class="sxs-lookup"><span data-stu-id="5b901-138">OrderID</span></span></td>
<td><p><span data-ttu-id="5b901-139">Identificador único de un pedido en la plataforma de facturación de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="5b901-139">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="5b901-140">Puede ser útil para identificar al pedido al ponerse en contacto con el soporte técnico, pero no para la conciliación.</span><span class="sxs-lookup"><span data-stu-id="5b901-140">May be useful to identify the order when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="5b901-141">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="5b901-141">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-142">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="5b901-142">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="5b901-143">Identificador único de una suscripción en la plataforma de facturación de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="5b901-143">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="5b901-144">Puede ser útil para identificar a la suscripción al ponerse en contacto con el soporte técnico, pero no para la reconciliación.</span><span class="sxs-lookup"><span data-stu-id="5b901-144">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="5b901-145">No es el mismo que el identificador de suscripción en la consola de administración de partners.</span><span class="sxs-lookup"><span data-stu-id="5b901-145">This is not the same as the Subscription ID on the Partner Admin Console.</span></span> <span data-ttu-id="5b901-146">Consulte Syndication_Partner_Subscription_Number.</span><span class="sxs-lookup"><span data-stu-id="5b901-146">Please see Syndication_Partner_Subscription_Number.</span></span></p></td>
<td><span data-ttu-id="5b901-147">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="5b901-147">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-148">SyndicationPartnerSubscriptionNumber</span><span class="sxs-lookup"><span data-stu-id="5b901-148">SyndicationPartnerSubscriptionNumber</span></span></td>
<td><p><span data-ttu-id="5b901-149">Identificador único de las suscripciones.</span><span class="sxs-lookup"><span data-stu-id="5b901-149">Unique identifier for subscriptions.</span></span> <span data-ttu-id="5b901-150">Un cliente puede tener varias suscripciones para el mismo plan, por lo que es importante para el análisis de archivos de conciliación.</span><span class="sxs-lookup"><span data-stu-id="5b901-150">A customer can have multiple subscriptions for the same plan, so this is important for reconciliation file analysis.</span></span></p>
<p><span data-ttu-id="5b901-151">Este campo se asigna al identificador de suscripción en la consola de administración de partners.</span><span class="sxs-lookup"><span data-stu-id="5b901-151">This field maps to the Subscription ID in the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="5b901-152">fb977ab5-test-test-test-24c8d9591708</span><span class="sxs-lookup"><span data-stu-id="5b901-152">fb977ab5-test-test-test-24c8d9591708</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-153">OfferID</span><span class="sxs-lookup"><span data-stu-id="5b901-153">OfferID</span></span></td>
<td><p><span data-ttu-id="5b901-154">Identificador único de la oferta.</span><span class="sxs-lookup"><span data-stu-id="5b901-154">Unique offer ID.</span></span> <span data-ttu-id="5b901-155">Identificador de la oferta estándar según la lista de precios.</span><span class="sxs-lookup"><span data-stu-id="5b901-155">Standard offer ID as per price list.</span></span></p>
<p><span data-ttu-id="5b901-156"><b>Nota</b>: este valor no coincide con el id. de oferta de la lista de precios.</span><span class="sxs-lookup"><span data-stu-id="5b901-156"><b>Note</b>: This value does not match Offer ID from the price list.</span></span> <span data-ttu-id="5b901-157">Consulta DurableOfferID a continuación.</span><span class="sxs-lookup"><span data-stu-id="5b901-157">See DurableOfferID below.</span></span></p></td>
<td><span data-ttu-id="5b901-158">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span><span class="sxs-lookup"><span data-stu-id="5b901-158">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-159">DurableOfferID</span><span class="sxs-lookup"><span data-stu-id="5b901-159">DurableOfferID</span></span></td>
<td><p><span data-ttu-id="5b901-160">Id. de oferta duradera único, según se define en la lista de precios.</span><span class="sxs-lookup"><span data-stu-id="5b901-160">Unique durable offer ID, as defined in the price list.</span></span></p>
<p><span data-ttu-id="5b901-161"><b>Nota</b>: este valor coincide con el id. de oferta de la lista de precios.</span><span class="sxs-lookup"><span data-stu-id="5b901-161"><b>Note</b>: This value matches the Offer ID from the price list.</span></span></p></td>
<td><span data-ttu-id="5b901-162">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span><span class="sxs-lookup"><span data-stu-id="5b901-162">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-163">OfferName</span><span class="sxs-lookup"><span data-stu-id="5b901-163">OfferName</span></span></td>
<td><p><span data-ttu-id="5b901-164">Nombre de la oferta de servicio adquirida por el cliente, según se define en la lista de precios.</span><span class="sxs-lookup"><span data-stu-id="5b901-164">The name of the service offering purchased by the customer, as defined in the price list.</span></span></p></td>
<td><span data-ttu-id="5b901-165">Microsoft Office 365 (Plan E3)</span><span class="sxs-lookup"><span data-stu-id="5b901-165">Microsoft Office 365 (Plan E3)</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-166">SubscriptionStartDate</span><span class="sxs-lookup"><span data-stu-id="5b901-166">SubscriptionStartDate</span></span></td>
<td><p><span data-ttu-id="5b901-167">Fecha de finalización de la suscripción, establecida en el día posterior al envío del pedido.</span><span class="sxs-lookup"><span data-stu-id="5b901-167">The subscription start date, set to the day after the order is submitted.</span></span> <span data-ttu-id="5b901-168">Al consultar la fecha de inicio de la suscripción junto con la fecha de finalización, puedes determinar si el cliente aún está dentro del primer año de la suscripción o si la suscripción se ha renovado para el año siguiente.</span><span class="sxs-lookup"><span data-stu-id="5b901-168">By looking at the subscription start date in conjunction with the end date, you can determine if the customer is still within the first year of the subscription or if the subscription has been renewed for the following year.</span></span></p>
<p><span data-ttu-id="5b901-169">La hora siempre corresponde al comienzo del día, 0:00.</span><span class="sxs-lookup"><span data-stu-id="5b901-169">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="5b901-170">1/2/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="5b901-170">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-171">SubscriptionEndDate</span><span class="sxs-lookup"><span data-stu-id="5b901-171">SubscriptionEndDate</span></span></td>
<td><p><span data-ttu-id="5b901-172">La fecha de finalización de la suscripción: 12 meses + x días después de la fecha de inicio (para que se alinee con la fecha de facturación del partner) o 12 meses a partir de la fecha de renovación.</span><span class="sxs-lookup"><span data-stu-id="5b901-172">The subscription end date: 12 months + x days after start date (to align with partner billing date) or 12 months from renewal date.</span></span></p>
<p><span data-ttu-id="5b901-173">En el momento de la renovación, los precios se actualizan según la lista de precios actual.</span><span class="sxs-lookup"><span data-stu-id="5b901-173">At renewal, prices are updated to the current price list.</span></span> <span data-ttu-id="5b901-174">Es posible que se necesite una comunicación con el cliente antes de la renovación automatizada.</span><span class="sxs-lookup"><span data-stu-id="5b901-174">Customer communication may be required in advance of automated renewal.</span></span></p>
<p><span data-ttu-id="5b901-175">La hora siempre corresponde al comienzo del día, 0:00.</span><span class="sxs-lookup"><span data-stu-id="5b901-175">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="5b901-176">1/2/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="5b901-176">2/1/2015 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-177">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="5b901-177">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="5b901-178">Día de inicio de los cargos.</span><span class="sxs-lookup"><span data-stu-id="5b901-178">Start day of the charges.</span></span></p>
<p><span data-ttu-id="5b901-179">Cuando un cliente cambia los números de puestos, este número se usa para calcular los cargos por día (proporcionales).</span><span class="sxs-lookup"><span data-stu-id="5b901-179">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="5b901-180">La hora siempre corresponde al comienzo del día, 0:00.</span><span class="sxs-lookup"><span data-stu-id="5b901-180">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="5b901-181">1/2/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="5b901-181">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-182">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="5b901-182">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="5b901-183">Día de finalización de los cargos.</span><span class="sxs-lookup"><span data-stu-id="5b901-183">End day of the charges.</span></span></p>
<p><span data-ttu-id="5b901-184">Cuando un cliente cambia los números de puestos, este número se usa para calcular los cargos por día (proporcionales).</span><span class="sxs-lookup"><span data-stu-id="5b901-184">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="5b901-185">La hora siempre corresponde al fin del día, 23:59.</span><span class="sxs-lookup"><span data-stu-id="5b901-185">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="5b901-186">28/2/2015 23:59</span><span class="sxs-lookup"><span data-stu-id="5b901-186">2/28/2015 23:59</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-187">ChargeType</span><span class="sxs-lookup"><span data-stu-id="5b901-187">ChargeType</span></span></td>
<td><p><span data-ttu-id="5b901-188">Tipo de cargo o ajuste.</span><span class="sxs-lookup"><span data-stu-id="5b901-188">The type of charge or adjustment.</span></span> <span data-ttu-id="5b901-189">Consulta <a href="#charge_types">Asignación de cargos entre una factura y el archivo de conciliación</a></span><span class="sxs-lookup"><span data-stu-id="5b901-189">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="5b901-190">Consulta <a href="#charge_types">Asignación de cargos entre una factura y el archivo de conciliación</a></span><span class="sxs-lookup"><span data-stu-id="5b901-190">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-191">UnitPrice</span><span class="sxs-lookup"><span data-stu-id="5b901-191">UnitPrice</span></span></td>
<td><p><span data-ttu-id="5b901-192">Precio por puesto, tal y como se publica en la lista de precios en el momento de compra.</span><span class="sxs-lookup"><span data-stu-id="5b901-192">Price per seat, as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="5b901-193">Asegúrate de que coincide con la información almacenada en tu sistema de facturación durante la conciliación.</span><span class="sxs-lookup"><span data-stu-id="5b901-193">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="5b901-194">6.82</span><span class="sxs-lookup"><span data-stu-id="5b901-194">6.82</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-195">Quantity</span><span class="sxs-lookup"><span data-stu-id="5b901-195">Quantity</span></span></td>
<td><p><span data-ttu-id="5b901-196">Número de puestos.</span><span class="sxs-lookup"><span data-stu-id="5b901-196">Number of seats.</span></span> <span data-ttu-id="5b901-197">Asegúrate de que coincide con la información almacenada en tu sistema de facturación durante la conciliación.</span><span class="sxs-lookup"><span data-stu-id="5b901-197">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="5b901-198">2</span><span class="sxs-lookup"><span data-stu-id="5b901-198">2</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-199">Amount</span><span class="sxs-lookup"><span data-stu-id="5b901-199">Amount</span></span></td>
<td><p><span data-ttu-id="5b901-200">Total del precio para la cantidad.</span><span class="sxs-lookup"><span data-stu-id="5b901-200">Total of price for quantity.</span></span> <span data-ttu-id="5b901-201">Es de utilidad para comprobar que el cálculo de la cantidad coincide con la manera de calcular este valor para los clientes.</span><span class="sxs-lookup"><span data-stu-id="5b901-201">Useful to check that the amount calculation matches how you calculate this for your customers.</span></span></p></td>
<td><span data-ttu-id="5b901-202">13.32</span><span class="sxs-lookup"><span data-stu-id="5b901-202">13.32</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-203">TotalOtherDiscount</span><span class="sxs-lookup"><span data-stu-id="5b901-203">TotalOtherDiscount</span></span></td>
<td><p><span data-ttu-id="5b901-204">Cantidad de descuento que se aplica a estos cargos.</span><span class="sxs-lookup"><span data-stu-id="5b901-204">Amount of discount applied to these charges.</span></span> <span data-ttu-id="5b901-205">Los IUR o las nuevas suscripciones que puedan optar a un incentivo también incluirán un importe de descuento en esta columna.</span><span class="sxs-lookup"><span data-stu-id="5b901-205">IUR or new subscriptions eligible for an incentive will also contain a discount amount in this column.</span></span></p></td>
<td><span data-ttu-id="5b901-206">2.32</span><span class="sxs-lookup"><span data-stu-id="5b901-206">2.32</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-207">Subtotal</span><span class="sxs-lookup"><span data-stu-id="5b901-207">Subtotal</span></span></td>
<td><p><span data-ttu-id="5b901-208">Total sin impuestos.</span><span class="sxs-lookup"><span data-stu-id="5b901-208">Total before tax.</span></span> <span data-ttu-id="5b901-209">Comprueba que el subtotal coincide con el total previsto, en el caso de un descuento.</span><span class="sxs-lookup"><span data-stu-id="5b901-209">Checks that your subtotal matches your expected total, in case of a discount.</span></span></p></td>
<td><span data-ttu-id="5b901-210">11</span><span class="sxs-lookup"><span data-stu-id="5b901-210">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-211">Tax</span><span class="sxs-lookup"><span data-stu-id="5b901-211">Tax</span></span></td>
<td><p><span data-ttu-id="5b901-212">Cargo por importe de impuestos, en función de las reglas fiscales de tu mercado y las circunstancias específicas.</span><span class="sxs-lookup"><span data-stu-id="5b901-212">Tax amount charge, based on your market's tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="5b901-213">0</span><span class="sxs-lookup"><span data-stu-id="5b901-213">0</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-214">TotalForCustomer</span><span class="sxs-lookup"><span data-stu-id="5b901-214">TotalForCustomer</span></span></td>
<td><p><span data-ttu-id="5b901-215">Total con impuestos.</span><span class="sxs-lookup"><span data-stu-id="5b901-215">Total after tax.</span></span> <span data-ttu-id="5b901-216">Comprueba si se cobran impuestos en la factura.</span><span class="sxs-lookup"><span data-stu-id="5b901-216">Checks if you are charged tax in the invoice.</span></span></p></td>
<td><span data-ttu-id="5b901-217">11</span><span class="sxs-lookup"><span data-stu-id="5b901-217">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-218">Currency</span><span class="sxs-lookup"><span data-stu-id="5b901-218">Currency</span></span></td>
<td><p><span data-ttu-id="5b901-219">Tipo de moneda.</span><span class="sxs-lookup"><span data-stu-id="5b901-219">Currency type.</span></span> <span data-ttu-id="5b901-220">Cada entidad de facturación tiene una sola moneda.</span><span class="sxs-lookup"><span data-stu-id="5b901-220">Each billing entity has only one currency.</span></span> <span data-ttu-id="5b901-221">Comprueba que coincide con la primera factura y repite la comprobación tras cualquier actualización importante de la plataforma de facturación.</span><span class="sxs-lookup"><span data-stu-id="5b901-221">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="5b901-222">EUR</span><span class="sxs-lookup"><span data-stu-id="5b901-222">EUR</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-223">CustomerName</span><span class="sxs-lookup"><span data-stu-id="5b901-223">CustomerName</span></span></td>
<td><p><span data-ttu-id="5b901-224">Nombre de la organización del cliente según se indica en el Centro de partners.</span><span class="sxs-lookup"><span data-stu-id="5b901-224">Customer's organization name as reported in Partner Center.</span></span> <span data-ttu-id="5b901-225">Esto es muy importante para conciliar la factura con la información del sistema.</span><span class="sxs-lookup"><span data-stu-id="5b901-225">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="5b901-226">Cliente de prueba A</span><span class="sxs-lookup"><span data-stu-id="5b901-226">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-227">MPNID</span><span class="sxs-lookup"><span data-stu-id="5b901-227">MPNID</span></span></td>
<td><p><span data-ttu-id="5b901-228">Id. de MPN del partner CSP</span><span class="sxs-lookup"><span data-stu-id="5b901-228">MPN ID of the CSP partner</span></span></p></td>
<td><span data-ttu-id="5b901-229">4390934</span><span class="sxs-lookup"><span data-stu-id="5b901-229">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-230">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="5b901-230">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="5b901-231">Id. de MPN del revendedor de registro de la suscripción.</span><span class="sxs-lookup"><span data-stu-id="5b901-231">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="5b901-232">Ver [Desglosar por partner](#itemizebypartner)</span><span class="sxs-lookup"><span data-stu-id="5b901-232">See [Itemize by partner](#itemizebypartner).</span></span></p></td>
<td><span data-ttu-id="5b901-233">4390934</span><span class="sxs-lookup"><span data-stu-id="5b901-233">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-234">DomainName</span><span class="sxs-lookup"><span data-stu-id="5b901-234">DomainName</span></span></td>
<td><p><span data-ttu-id="5b901-235">Nombre de dominio del cliente, que se usa para identificar al cliente.</span><span class="sxs-lookup"><span data-stu-id="5b901-235">Customer's domain name, used to help identify the customer.</span></span> <span data-ttu-id="5b901-236">No debe usarse para identificar al cliente como el partner o el cliente puede actualizar el dominio cortesía de forma predeterminada a través del portal de O365.</span><span class="sxs-lookup"><span data-stu-id="5b901-236">This should not be used to uniquely identify the customer as the customer/partner can update the vanity/default domain via the O365 portal.</span></span> <span data-ttu-id="5b901-237">Este campo puede aparecer en blanco hasta el segundo ciclo de facturación.</span><span class="sxs-lookup"><span data-stu-id="5b901-237">This field may appear blank until the second billing cycle.</span></span></p></td>
<td><span data-ttu-id="5b901-238">ejemplo.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="5b901-238">example.onmicrosoft.com</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-239">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="5b901-239">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="5b901-240">Alias de la suscripción.</span><span class="sxs-lookup"><span data-stu-id="5b901-240">Subscription nickname.</span></span> <span data-ttu-id="5b901-241">Si no se especifica ningún alias, el Centro de partners usa OfferName.</span><span class="sxs-lookup"><span data-stu-id="5b901-241">If no nickname is specified, Partner Center uses the OfferName.</span></span></p></td>
<td><span data-ttu-id="5b901-242">PROJECT ONLINE</span><span class="sxs-lookup"><span data-stu-id="5b901-242">PROJECT ONLINE</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-243">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="5b901-243">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="5b901-244">Nombre de la oferta de servicio adquirida por el cliente, según se define en la lista de precios.</span><span class="sxs-lookup"><span data-stu-id="5b901-244">The name of the service offering purchased by the customer, as defined in the price list.</span></span> <span data-ttu-id="5b901-245">(Este es un campo idéntico al nombre de la oferta).</span><span class="sxs-lookup"><span data-stu-id="5b901-245">(This is an identical field to Offer name).</span></span></p></td>
<td><span data-ttu-id="5b901-246">PROJECT ONLINE PREMIUM SIN CLIENTE DE PROJECT</span><span class="sxs-lookup"><span data-stu-id="5b901-246">PROJECT ONLINE PREMIUM WITHOUT PROJECT CLIENT</span></span></td>
</tr>
</tbody>
</table>


## <a href="" id="usagebasedfiles"></a><span data-ttu-id="5b901-247">Campos de archivos basados en el uso</span><span class="sxs-lookup"><span data-stu-id="5b901-247">Usage-based file fields</span></span>


<span data-ttu-id="5b901-248">Para conciliar los cargos en función del uso de tu cliente, compara los valores de ResellerID/ResellerName/ResellerBillableAccount del archivo de conciliación, el nombre del cliente y el id. de suscripción del Centro de partners.</span><span class="sxs-lookup"><span data-stu-id="5b901-248">To reconcile your charges against your customer's usage, compare the ResellerID/ResellerName/ResellerBillableAccount from the reconciliation file, the customer name, and the Subscription ID from Partner Center.</span></span>

<span data-ttu-id="5b901-249">Los siguientes campos explican los servicios usados y la clasificación.</span><span class="sxs-lookup"><span data-stu-id="5b901-249">The following fields explain which services were used and the rate.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><strong><span data-ttu-id="5b901-250">Columna</span><span class="sxs-lookup"><span data-stu-id="5b901-250">Column</span></span></strong></td>
<td><strong><span data-ttu-id="5b901-251">Descripción</span><span class="sxs-lookup"><span data-stu-id="5b901-251">Description</span></span></strong></td>
<td><strong><span data-ttu-id="5b901-252">Valor de muestra</span><span class="sxs-lookup"><span data-stu-id="5b901-252">Sample value</span></span></strong></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-253">PartnerID</span><span class="sxs-lookup"><span data-stu-id="5b901-253">PartnerID</span></span></td>
<td><p><span data-ttu-id="5b901-254">Id. de partner, en formato de GUID.</span><span class="sxs-lookup"><span data-stu-id="5b901-254">Partner ID, in GUID format.</span></span></p></td>
<td><span data-ttu-id="5b901-255">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="5b901-255">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-256">PartnerName</span><span class="sxs-lookup"><span data-stu-id="5b901-256">PartnerName</span></span></td>
<td><p><span data-ttu-id="5b901-257">Nombre del partner.</span><span class="sxs-lookup"><span data-stu-id="5b901-257">Partner Name.</span></span></p></td>
<td><span data-ttu-id="5b901-258">Acme Incorporated</span><span class="sxs-lookup"><span data-stu-id="5b901-258">Acme Incorporated</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-259">PartnerBillableAccountID</span><span class="sxs-lookup"><span data-stu-id="5b901-259">PartnerBillableAccountID</span></span></td>
<td><p><span data-ttu-id="5b901-260">Id. de cuenta del partner.</span><span class="sxs-lookup"><span data-stu-id="5b901-260">Partner Account ID.</span></span></p></td>
<td><span data-ttu-id="5b901-261">1010578050</span><span class="sxs-lookup"><span data-stu-id="5b901-261">1010578050</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-262">CustomerName</span><span class="sxs-lookup"><span data-stu-id="5b901-262">CustomerName</span></span></td>
<td><p><span data-ttu-id="5b901-263">Nombre de la organización del cliente según se indica en el Centro de partners.</span><span class="sxs-lookup"><span data-stu-id="5b901-263">Customer's organization name as reported in Partner Center.</span></span> <span data-ttu-id="5b901-264">Esto es muy importante para conciliar la factura con la información del sistema.</span><span class="sxs-lookup"><span data-stu-id="5b901-264">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="5b901-265">Cliente de prueba A</span><span class="sxs-lookup"><span data-stu-id="5b901-265">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-266">MPNID</span><span class="sxs-lookup"><span data-stu-id="5b901-266">MPNID</span></span></td>
<td><p><span data-ttu-id="5b901-267">Id. de MPN del partner CSP.</span><span class="sxs-lookup"><span data-stu-id="5b901-267">MPN ID of the CSP partner.</span></span></p></td>
<td><span data-ttu-id="5b901-268">4390934</span><span class="sxs-lookup"><span data-stu-id="5b901-268">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-269">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="5b901-269">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="5b901-270">Id. de MPN del revendedor de registro de la suscripción.</span><span class="sxs-lookup"><span data-stu-id="5b901-270">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="5b901-271">Ver [Desglosar por partner](#itemizebypartner)</span><span class="sxs-lookup"><span data-stu-id="5b901-271">See [Itemize by partner](#itemizebypartner).</span></span></p></td>
<td><span data-ttu-id="5b901-272">4390934</span><span class="sxs-lookup"><span data-stu-id="5b901-272">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-273">InvoiceNumber</span><span class="sxs-lookup"><span data-stu-id="5b901-273">InvoiceNumber</span></span></td>
<td><p><span data-ttu-id="5b901-274">Número de factura donde aparece la transacción especificada.</span><span class="sxs-lookup"><span data-stu-id="5b901-274">Invoice number where the specified transaction appears.</span></span></p></td>
<td><span data-ttu-id="5b901-275">D020001IVK</span><span class="sxs-lookup"><span data-stu-id="5b901-275">D020001IVK</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-276">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="5b901-276">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="5b901-277">Fecha de inicio del ciclo de facturación, excepto cuando se presentan fechas de datos de uso latentes no cargados previamente (del ciclo de facturación anterior).</span><span class="sxs-lookup"><span data-stu-id="5b901-277">Start date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="5b901-278">La hora siempre corresponde al comienzo del día, 0:00.</span><span class="sxs-lookup"><span data-stu-id="5b901-278">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="5b901-279">1/2/2014 0:00</span><span class="sxs-lookup"><span data-stu-id="5b901-279">2/1/2014 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-280">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="5b901-280">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="5b901-281">Fecha de finalización del ciclo de facturación, excepto cuando se presentan fechas de datos de uso latentes no cargados previamente (del ciclo de facturación anterior).</span><span class="sxs-lookup"><span data-stu-id="5b901-281">End date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="5b901-282">La hora siempre corresponde al fin del día, 23:59.</span><span class="sxs-lookup"><span data-stu-id="5b901-282">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="5b901-283">28/2/2014 23:59</span><span class="sxs-lookup"><span data-stu-id="5b901-283">2/28/2014 23:59</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-284">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="5b901-284">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="5b901-285">Identificador único de una suscripción en la plataforma de facturación de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="5b901-285">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="5b901-286">Puede ser útil para identificar a la suscripción al ponerse en contacto con el soporte técnico, pero no para la reconciliación.</span><span class="sxs-lookup"><span data-stu-id="5b901-286">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="5b901-287">No es el mismo que el identificador de suscripción en la consola de administración de partners.</span><span class="sxs-lookup"><span data-stu-id="5b901-287">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="5b901-288">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="5b901-288">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-289">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="5b901-289">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="5b901-290">Alias de la oferta de servicio.</span><span class="sxs-lookup"><span data-stu-id="5b901-290">Nickname of the service offering.</span></span></p></td>
<td><span data-ttu-id="5b901-291">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="5b901-291">Microsoft Azure</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-292">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="5b901-292">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="5b901-293">Línea de negocio de la oferta de servicio</span><span class="sxs-lookup"><span data-stu-id="5b901-293">Line of business of the service offering</span></span></p></td>
<td><span data-ttu-id="5b901-294">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="5b901-294">Microsoft Azure</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-295">OrderID</span><span class="sxs-lookup"><span data-stu-id="5b901-295">OrderID</span></span></td>
<td><p><span data-ttu-id="5b901-296">Identificador único de un pedido en la plataforma de facturación de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="5b901-296">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="5b901-297">Puede ser útil para identificar la suscripción al ponerse en contacto con el soporte técnico, pero no para la conciliación.</span><span class="sxs-lookup"><span data-stu-id="5b901-297">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="5b901-298">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="5b901-298">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-299">ServiceName</span><span class="sxs-lookup"><span data-stu-id="5b901-299">ServiceName</span></span></td>
<td><p><span data-ttu-id="5b901-300">Nombre del servicio de Azure en cuestión.</span><span class="sxs-lookup"><span data-stu-id="5b901-300">The name of the Azure service in question.</span></span></p></td>
<td><span data-ttu-id="5b901-301">MÁQUINAS VIRTUALES</span><span class="sxs-lookup"><span data-stu-id="5b901-301">VIRTUAL MACHINES</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-302">ServiceType</span><span class="sxs-lookup"><span data-stu-id="5b901-302">ServiceType</span></span></td>
<td><p><span data-ttu-id="5b901-303">Tipo específico de servicio de Microsoft Azure.</span><span class="sxs-lookup"><span data-stu-id="5b901-303">The specific type of Windows Azure service.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="5b901-304">Bus de servicio: individual o paquete</span><span class="sxs-lookup"><span data-stu-id="5b901-304">Service Bus – Individual or Pack</span></span></li>
<li><span data-ttu-id="5b901-305">Base de datos SQL Azure: edición Business o Web</span><span class="sxs-lookup"><span data-stu-id="5b901-305">SQL Azure database – Business or Web Edition</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-306">ResourceGUID</span><span class="sxs-lookup"><span data-stu-id="5b901-306">ResourceGUID</span></span></td>
<td><p><span data-ttu-id="5b901-307">Identificador único específico para toda la estructura de precios y datos del servicio.</span><span class="sxs-lookup"><span data-stu-id="5b901-307">Specific unique identifier for all the service data and pricing structure.</span></span></p></td>
<td><span data-ttu-id="5b901-308">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="5b901-308">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-309">Nombre de recurso</span><span class="sxs-lookup"><span data-stu-id="5b901-309">Resource Name</span></span></td>
<td><p><span data-ttu-id="5b901-310">Nombre del recurso de Azure.</span><span class="sxs-lookup"><span data-stu-id="5b901-310">The name of the Azure resource.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="5b901-311">Transferencia entrante de datos (GB)</span><span class="sxs-lookup"><span data-stu-id="5b901-311">Data Transfer In (GB)</span></span></li>
<li><span data-ttu-id="5b901-312">Transferencia saliente de datos (GB)</span><span class="sxs-lookup"><span data-stu-id="5b901-312">Data Transfer Out (GB)</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-313">Region</span><span class="sxs-lookup"><span data-stu-id="5b901-313">Region</span></span></td>
<td><p><span data-ttu-id="5b901-314">La región a la que se aplica el uso.</span><span class="sxs-lookup"><span data-stu-id="5b901-314">The region the usage applies to.</span></span> <span data-ttu-id="5b901-315">Se usa principalmente para asignar tarifas a las transferencias de datos, ya que las tarifas varían según la región.</span><span class="sxs-lookup"><span data-stu-id="5b901-315">Primarily used to assign rates to data transfers, as rates vary by region.</span></span></p></td>
<td><span data-ttu-id="5b901-316">Asia Pacífico, Europa, América Latina, América del Norte</span><span class="sxs-lookup"><span data-stu-id="5b901-316">Asia Pacific, Europe, Latin America, North America</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-317">SKU</span><span class="sxs-lookup"><span data-stu-id="5b901-317">SKU</span></span></td>
<td><p><span data-ttu-id="5b901-318">Identificador único de MSFT para la oferta</span><span class="sxs-lookup"><span data-stu-id="5b901-318">MSFT unique identifier for offer</span></span></p></td>
<td><span data-ttu-id="5b901-319">7UD 00001</span><span class="sxs-lookup"><span data-stu-id="5b901-319">7UD-00001</span></span></td>
</tr>
<tr class="odd">
<td><p><span data-ttu-id="5b901-320">DetailLineItemId</span><span class="sxs-lookup"><span data-stu-id="5b901-320">DetailLineItemId</span></span></p></td>
<td><p><span data-ttu-id="5b901-321">Un id. y una cantidad para desglosar las distintas clasificaciones de un servicio o un recurso en un período de facturación determinado.</span><span class="sxs-lookup"><span data-stu-id="5b901-321">An ID and quantity for itemizing the different rates for a service or resource in a given billing period.</span></span> <span data-ttu-id="5b901-322">Para clasificación en niveles de Azure, puede haber una clasificación hasta una cantidad determinada de unidades facturables y, posteriormente, una clasificación diferente.</span><span class="sxs-lookup"><span data-stu-id="5b901-322">For Azure tiered rating, there may be one rate up to a certain quantity of billable units, then a different rate after that.</span></span></p></td>
<td><span data-ttu-id="5b901-323">1</span><span class="sxs-lookup"><span data-stu-id="5b901-323">1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-324">ConsumedQuantity</span><span class="sxs-lookup"><span data-stu-id="5b901-324">ConsumedQuantity</span></span></td>
<td><p><span data-ttu-id="5b901-325">La cantidad de servicio consumida (horas, GB, etc.) durante el período de notificación.</span><span class="sxs-lookup"><span data-stu-id="5b901-325">The amount of service consumed (hours, GB, etc.) during the reporting period.</span></span></p>
<p><span data-ttu-id="5b901-326">También incluye cualquier uso no facturado de períodos anteriores.</span><span class="sxs-lookup"><span data-stu-id="5b901-326">Also includes any unbilled usage from previous reporting periods.</span></span></p></td>
<td><span data-ttu-id="5b901-327">11</span><span class="sxs-lookup"><span data-stu-id="5b901-327">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-328">IncludedQuantity</span><span class="sxs-lookup"><span data-stu-id="5b901-328">IncludedQuantity</span></span></td>
<td><p><span data-ttu-id="5b901-329">Unidades que se incluyen como parte de la oferta.</span><span class="sxs-lookup"><span data-stu-id="5b901-329">Units included as part of the offer.</span></span> <span data-ttu-id="5b901-330">No suele mostrarse en CSP.</span><span class="sxs-lookup"><span data-stu-id="5b901-330">Not typically present in CSP.</span></span></p></td>
<td><span data-ttu-id="5b901-331">0</span><span class="sxs-lookup"><span data-stu-id="5b901-331">0</span></span></td>
</tr>
<tr class="even">
<td><p><span data-ttu-id="5b901-332">OverageQuantity</span><span class="sxs-lookup"><span data-stu-id="5b901-332">OverageQuantity</span></span></p></td>
<td><p><span data-ttu-id="5b901-333">Unidades que no se incluyen como parte de la oferta y que el partner debe abonar.</span><span class="sxs-lookup"><span data-stu-id="5b901-333">Units not included as part of the offer, that must be paid for by the partner.</span></span></p>
<p><span data-ttu-id="5b901-334">Equivale a ConsumedQuantity - IncludedQuantity.</span><span class="sxs-lookup"><span data-stu-id="5b901-334">Equal to the ConsumedQuantity - IncludedQuantity.</span></span></p></td>
<td><span data-ttu-id="5b901-335">11</span><span class="sxs-lookup"><span data-stu-id="5b901-335">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-336">ListPrice</span><span class="sxs-lookup"><span data-stu-id="5b901-336">ListPrice</span></span></td>
<td><p><span data-ttu-id="5b901-337">Precio de la oferta en vigor la fecha de inicio de la suscripción.</span><span class="sxs-lookup"><span data-stu-id="5b901-337">Offer price in effect at subscription start date.</span></span></p></td>
<td><span data-ttu-id="5b901-338">0.0808 USD</span><span class="sxs-lookup"><span data-stu-id="5b901-338">$0.0808</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-339">PretaxCharges</span><span class="sxs-lookup"><span data-stu-id="5b901-339">PretaxCharges</span></span></td>
<td><p><span data-ttu-id="5b901-340">ListPrist x OverageQuantity, redondeado al céntimo más próximo.</span><span class="sxs-lookup"><span data-stu-id="5b901-340">ListPrist times OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="5b901-341">0.085 USD</span><span class="sxs-lookup"><span data-stu-id="5b901-341">$0.085</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-342">TaxAmount</span><span class="sxs-lookup"><span data-stu-id="5b901-342">TaxAmount</span></span></td>
<td><p><span data-ttu-id="5b901-343">Cargo por importe de impuestos, en función de las reglas fiscales de tu mercado y las circunstancias específicas.</span><span class="sxs-lookup"><span data-stu-id="5b901-343">Tax amount charge, based on your market's tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="5b901-344">0.08 USD</span><span class="sxs-lookup"><span data-stu-id="5b901-344">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-345">PostTaxTotal</span><span class="sxs-lookup"><span data-stu-id="5b901-345">PostTaxTotal</span></span></td>
<td><p><span data-ttu-id="5b901-346">Total con impuestos, si se aplican impuestos.</span><span class="sxs-lookup"><span data-stu-id="5b901-346">Total after tax, when tax is applicable.</span></span></p></td>
<td><span data-ttu-id="5b901-347">0.93 USD</span><span class="sxs-lookup"><span data-stu-id="5b901-347">$0.93</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-348">Currency</span><span class="sxs-lookup"><span data-stu-id="5b901-348">Currency</span></span></td>
<td><p><span data-ttu-id="5b901-349">Tipo de moneda.</span><span class="sxs-lookup"><span data-stu-id="5b901-349">Currency type.</span></span> <span data-ttu-id="5b901-350">Cada entidad de facturación tiene una sola moneda.</span><span class="sxs-lookup"><span data-stu-id="5b901-350">Each billing entity has only one currency.</span></span> <span data-ttu-id="5b901-351">Comprueba que coincide con la primera factura y repite la comprobación tras cualquier actualización importante de la plataforma de facturación.</span><span class="sxs-lookup"><span data-stu-id="5b901-351">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="5b901-352">EUR</span><span class="sxs-lookup"><span data-stu-id="5b901-352">EUR</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-353">PretaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="5b901-353">PretaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="5b901-354">Precio sin impuestos por unidad.</span><span class="sxs-lookup"><span data-stu-id="5b901-354">Pretax price per unit.</span></span> <span data-ttu-id="5b901-355">Igual que PretaxCharges/OverageQuantity, redondeado al céntimo más próximo.</span><span class="sxs-lookup"><span data-stu-id="5b901-355">Equal to PretaxCharges / OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="5b901-356">0.08 USD</span><span class="sxs-lookup"><span data-stu-id="5b901-356">$0.08</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-357">PostTaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="5b901-357">PostTaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="5b901-358">Precio después de impuestos por unidad.</span><span class="sxs-lookup"><span data-stu-id="5b901-358">Post tax price per unit.</span></span> <span data-ttu-id="5b901-359">Igual que PostTaxTotal/OverageQuantity o PretaxEffectiveRate + tipo impositivo por importe unitario, redondeado el céntimo más próximo.</span><span class="sxs-lookup"><span data-stu-id="5b901-359">Equal to PostTaxTotal / OverageQuantity, or PretaxEffectiveRate + tax rate per unit amoun, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="5b901-360">0.08 USD</span><span class="sxs-lookup"><span data-stu-id="5b901-360">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-361">ChargeType</span><span class="sxs-lookup"><span data-stu-id="5b901-361">ChargeType</span></span></td>
<td><p><span data-ttu-id="5b901-362">Tipo de cargo o ajuste.</span><span class="sxs-lookup"><span data-stu-id="5b901-362">The type of charge or adjustment.</span></span> <span data-ttu-id="5b901-363">Consulta <a href="#charge_types">Asignación de cargos entre una factura y el archivo de conciliación</a></span><span class="sxs-lookup"><span data-stu-id="5b901-363">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="5b901-364">Consulta <a href="#charge_types">Asignación de cargos entre una factura y el archivo de conciliación</a></span><span class="sxs-lookup"><span data-stu-id="5b901-364">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-365">CustomerBillableAccount</span><span class="sxs-lookup"><span data-stu-id="5b901-365">CustomerBillableAccount</span></span></td>
<td><p><span data-ttu-id="5b901-366">Id. de cuenta único en la plataforma de facturación de MSFT.</span><span class="sxs-lookup"><span data-stu-id="5b901-366">Unique account ID in the MSFT billing platform.</span></span></p></td>
<td><span data-ttu-id="5b901-367">1280018095</span><span class="sxs-lookup"><span data-stu-id="5b901-367">1280018095</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-368">UsageDate</span><span class="sxs-lookup"><span data-stu-id="5b901-368">UsageDate</span></span></td>
<td><p><span data-ttu-id="5b901-369">Fecha de implementación del servicio.</span><span class="sxs-lookup"><span data-stu-id="5b901-369">Date of service deployment.</span></span></p></td>
<td><span data-ttu-id="5b901-370">1/2/2014 0:00</span><span class="sxs-lookup"><span data-stu-id="5b901-370">2/1/2014 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-371">MeteredRegion</span><span class="sxs-lookup"><span data-stu-id="5b901-371">MeteredRegion</span></span></td>
<td><p><span data-ttu-id="5b901-372">Esta columna identifica la ubicación de un centro de datos dentro de la región para los servicios donde esto se aplica y rellena.</span><span class="sxs-lookup"><span data-stu-id="5b901-372">This column identifies the location of a data center within the region for services where this is applicable and populated.</span></span></p></td>
<td><span data-ttu-id="5b901-373">Asia Oriental, Asia Suroriental, Norte de Europa, Europa Occidental, Centro-norte de EE.UU., Centro-sur de EE.UU.</span><span class="sxs-lookup"><span data-stu-id="5b901-373">East Asia, South East Asia, North Europe, West Europe, North Central US, South Central US</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-374">MeteredService</span><span class="sxs-lookup"><span data-stu-id="5b901-374">MeteredService</span></span></td>
<td><p><span data-ttu-id="5b901-375">Esta columna se usa para hacer un seguimiento de los servicios de Microsoft Azure individuales que quizás no se identifiquen específicamente en la columna Service Name.</span><span class="sxs-lookup"><span data-stu-id="5b901-375">This column is utilized to track the individual Microsoft Azure service that may not be specifically identified in the Service Name column.</span></span> <span data-ttu-id="5b901-376">Por ejemplo, las transferencias de datos se notifican como &quot;Microsoft Azure: todos los servicios&quot; en la columna Service Name.</span><span class="sxs-lookup"><span data-stu-id="5b901-376">For example, data transfers are reported as &quot;Microsoft Azure - All Services&quot; in the Service Name column.</span></span> <span data-ttu-id="5b901-377">En esta columna MeteredService se indicará qué servicio específico pertenece el uso.</span><span class="sxs-lookup"><span data-stu-id="5b901-377">This MeteredService column will indicate to which specific service the usage pertains.</span></span></p></td>
<td><span data-ttu-id="5b901-378">AccessControl, CDN, Proceso, Base de datos, ServiceBus, Almacenamiento</span><span class="sxs-lookup"><span data-stu-id="5b901-378">AccessControl, CDN, Compute, Database, ServiceBus, Storage</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-379">MeteredServiceType</span><span class="sxs-lookup"><span data-stu-id="5b901-379">MeteredServiceType</span></span></td>
<td><p><span data-ttu-id="5b901-380">Subtítulo que aclara el servicio de Microsoft Azure individual más allá del nivel proporcionado por el campo MeteredService.</span><span class="sxs-lookup"><span data-stu-id="5b901-380">A subheading that further clarifies the individual Microsoft Azure service beyond the level provided by the MeteredService field.</span></span></p></td>
<td><span data-ttu-id="5b901-381">EXTERNO</span><span class="sxs-lookup"><span data-stu-id="5b901-381">EXTERNAL</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-382">Proyecto</span><span class="sxs-lookup"><span data-stu-id="5b901-382">Project</span></span></td>
<td><p><span data-ttu-id="5b901-383">Nombre definido por el cliente para la instancia del servicio</span><span class="sxs-lookup"><span data-stu-id="5b901-383">Customer-defined name for their service instance</span></span></p></td>
<td><span data-ttu-id="5b901-384">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="5b901-384">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-385">ServiceInfo</span><span class="sxs-lookup"><span data-stu-id="5b901-385">ServiceInfo</span></span></td>
<td><p><span data-ttu-id="5b901-386">Número de conexiones de Bus de servicio aprovisionadas y usadas en un día determinado.</span><span class="sxs-lookup"><span data-stu-id="5b901-386">The number of ServiceBus connections that were provisioned and utilized on a given day.</span></span></p></td>
<td><span data-ttu-id="5b901-387">Por ejemplo: si tenías una conexión aprovisionada individualmente durante un mes de 30 días, Service Info 1 contendría 1 "1,000000 conexiones/30 días".</span><span class="sxs-lookup"><span data-stu-id="5b901-387">For example: if you had an individually provisioned connection during a 30 day month, Service Info 1 would read “1.000000 Connections / 30 days”.</span></span> <span data-ttu-id="5b901-388">Si tenías un paquete de 25 de conexiones de Bus de servicio aprovisionadas y utilizaste 1 durante ese día, la declaración de uso diario de ese día sería "25 conexiones/30 días. Utilizadas: 1,000000".</span><span class="sxs-lookup"><span data-stu-id="5b901-388">If you had a 25 pack of ServiceBus connections provisioned and you had utilized 1 during that day, your daily usage statement for that day would indicate “25 Connections / 30 Days – Used: 1.000000”.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-389">CustomerID</span><span class="sxs-lookup"><span data-stu-id="5b901-389">CustomerID</span></span></td>
<td><p><span data-ttu-id="5b901-390">Id. de Microsoft único, en formato GUID, usado para identificar al cliente.</span><span class="sxs-lookup"><span data-stu-id="5b901-390">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="5b901-391">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="5b901-391">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b901-392">DomainName</span><span class="sxs-lookup"><span data-stu-id="5b901-392">DomainName</span></span></td>
<td><p><span data-ttu-id="5b901-393">Nombre de dominio del cliente, que se usa para identificar al cliente.</span><span class="sxs-lookup"><span data-stu-id="5b901-393">Customer's domain name, used to help identify the customer.</span></span> <span data-ttu-id="5b901-394">Este campo puede aparecer en blanco hasta el segundo ciclo de facturación.</span><span class="sxs-lookup"><span data-stu-id="5b901-394">This field may appear blank until the second billing cycle.</span></span></p></td>
<td><span data-ttu-id="5b901-395">ejemplo.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="5b901-395">example.onmicrosoft.com</span></span></td></tr>
</tr>
<tr class="even">
<td><span data-ttu-id="5b901-396">Unidad</span><span class="sxs-lookup"><span data-stu-id="5b901-396">Unit</span></span></td>
<td><p><span data-ttu-id="5b901-397">La unidad del nombre del recurso</span><span class="sxs-lookup"><span data-stu-id="5b901-397">The unit of the resource Name</span></span></p></td>
<td><span data-ttu-id="5b901-398">GB u HORAS</span><span class="sxs-lookup"><span data-stu-id="5b901-398">GB or HOURS</span></span></td>
</tr>
</tbody>
</table>

## <a href="" id="onetimefiles"></a><span data-ttu-id="5b901-399">Campos de archivos de compra de pago único</span><span class="sxs-lookup"><span data-stu-id="5b901-399">One-time purchase file fields</span></span>

|**<span data-ttu-id="5b901-400">Campo</span><span class="sxs-lookup"><span data-stu-id="5b901-400">Field</span></span>** |**<span data-ttu-id="5b901-401">Definición</span><span class="sxs-lookup"><span data-stu-id="5b901-401">Definition</span></span>**|
|:----------------|:-----------------------------|
|<span data-ttu-id="5b901-402">PartnerId</span><span class="sxs-lookup"><span data-stu-id="5b901-402">PartnerId</span></span> |<span data-ttu-id="5b901-403">Id. de partner, en formato de GUID.</span><span class="sxs-lookup"><span data-stu-id="5b901-403">Partner ID, in GUID format.</span></span> |
|<span data-ttu-id="5b901-404">CustomerId</span><span class="sxs-lookup"><span data-stu-id="5b901-404">CustomerId</span></span> |<span data-ttu-id="5b901-405">Id. de Microsoft único, en formato GUID, usado para identificar al cliente.</span><span class="sxs-lookup"><span data-stu-id="5b901-405">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span> |
|<span data-ttu-id="5b901-406">CustomerName</span><span class="sxs-lookup"><span data-stu-id="5b901-406">CustomerName</span></span> |<span data-ttu-id="5b901-407">Nombre de la organización del cliente según se indica en el Centro de partners.</span><span class="sxs-lookup"><span data-stu-id="5b901-407">Customer's organization name as reported in Partner Center.</span></span> <span data-ttu-id="5b901-408">Esto es muy importante para conciliar la factura con la información del sistema.</span><span class="sxs-lookup"><span data-stu-id="5b901-408">This is very important for reconciling the invoice with your system information.</span></span> |
|<span data-ttu-id="5b901-409">CustomerDomainName</span><span class="sxs-lookup"><span data-stu-id="5b901-409">CustomerDomainName</span></span> |<span data-ttu-id="5b901-410">Nombre de dominio del cliente.</span><span class="sxs-lookup"><span data-stu-id="5b901-410">The customer’s domain name.</span></span> |
|<span data-ttu-id="5b901-411">CustomerCountry</span><span class="sxs-lookup"><span data-stu-id="5b901-411">CustomerCountry</span></span> |<span data-ttu-id="5b901-412">El país donde se encuentra el cliente.</span><span class="sxs-lookup"><span data-stu-id="5b901-412">The country in which the customer is located.</span></span> |
|<span data-ttu-id="5b901-413">InvoiceNumber</span><span class="sxs-lookup"><span data-stu-id="5b901-413">InvoiceNumber</span></span> |<span data-ttu-id="5b901-414">Número de factura donde aparece la transacción especificada.</span><span class="sxs-lookup"><span data-stu-id="5b901-414">Invoice number where the specified transaction appears.</span></span> |
|<span data-ttu-id="5b901-415">MpnId</span><span class="sxs-lookup"><span data-stu-id="5b901-415">MpnId</span></span> |<span data-ttu-id="5b901-416">Id. de MPN del partner CSP (directo o indirecto).</span><span class="sxs-lookup"><span data-stu-id="5b901-416">MPN ID of the CSP partner (direct or indirect).</span></span> |
|<span data-ttu-id="5b901-417">Id. de MPN del revendedor</span><span class="sxs-lookup"><span data-stu-id="5b901-417">Reseller MPN ID</span></span> |<span data-ttu-id="5b901-418">Solo aparece en los archivos de conciliación de partners en el modelo indirecto.</span><span class="sxs-lookup"><span data-stu-id="5b901-418">Only appears on reconciliation files for partners in the indirect model.</span></span> <span data-ttu-id="5b901-419">Id. de MPN del revendedor de registro de la reserva.</span><span class="sxs-lookup"><span data-stu-id="5b901-419">The MPN ID of the reseller of record for the reservation.</span></span> <span data-ttu-id="5b901-420">Corresponde al id. de revendedor indicado para la reserva específica en el Centro de partners.</span><span class="sxs-lookup"><span data-stu-id="5b901-420">This corresponds to the reseller ID listed for the specific reservation in Partner Center.</span></span> <span data-ttu-id="5b901-421">Si un partner CSP vendió la reserva directamente al cliente, su id. de MPN aparece dos veces, como id. de MPN y como id. de MPN del revendedor.</span><span class="sxs-lookup"><span data-stu-id="5b901-421">If a CSP partner sold the reservation directly to the customer, their MPN ID is listed twice, as both the MPN ID and the Reseller MPN ID.</span></span> <span data-ttu-id="5b901-422">Si un partner CSP tiene un revendedor sin un id. de MPN, este valor se establece en el id. de MPN del partner.</span><span class="sxs-lookup"><span data-stu-id="5b901-422">If a CSP partner has a reseller with no MPN ID, this value is set to the partner’s MPN ID instead.</span></span> <span data-ttu-id="5b901-423">Si el partner CSP quita un id. de revendedor, este valor se establece en -1.</span><span class="sxs-lookup"><span data-stu-id="5b901-423">If the CSP partner removes a reseller ID, this value will be set to -1.</span></span> |
|<span data-ttu-id="5b901-424">OrderId</span><span class="sxs-lookup"><span data-stu-id="5b901-424">OrderId</span></span> |<span data-ttu-id="5b901-425">Identificador único de un pedido en la plataforma de facturación de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="5b901-425">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="5b901-426">Puede ser útil para identificar la reserva al ponerse en contacto con el soporte técnico, pero no para la reconciliación.</span><span class="sxs-lookup"><span data-stu-id="5b901-426">May be useful to identify the Azure reservation when contacting support but not for reconciliation.</span></span> |
|<span data-ttu-id="5b901-427">OrderDate</span><span class="sxs-lookup"><span data-stu-id="5b901-427">OrderDate</span></span> |<span data-ttu-id="5b901-428">Fecha de realización del pedido.</span><span class="sxs-lookup"><span data-stu-id="5b901-428">The date the order was placed.</span></span> |
|<span data-ttu-id="5b901-429">ProductId</span><span class="sxs-lookup"><span data-stu-id="5b901-429">ProductId</span></span> |<span data-ttu-id="5b901-430">Identificador del producto.</span><span class="sxs-lookup"><span data-stu-id="5b901-430">The ID for the product.</span></span> |
|<span data-ttu-id="5b901-431">SkuId</span><span class="sxs-lookup"><span data-stu-id="5b901-431">SkuId</span></span>  |<span data-ttu-id="5b901-432">Id. de un SKU concreto.</span><span class="sxs-lookup"><span data-stu-id="5b901-432">The ID for a particular SKU.</span></span> |
|<span data-ttu-id="5b901-433">AvailabilityId</span><span class="sxs-lookup"><span data-stu-id="5b901-433">AvailabilityId</span></span> |<span data-ttu-id="5b901-434">Id. de una disponibilidad concreta.</span><span class="sxs-lookup"><span data-stu-id="5b901-434">The ID for a particular Availability.</span></span> <span data-ttu-id="5b901-435">"Disponibilidad" hace referencia a si un SKU concreto está o no disponible para su compra para el país, la moneda, el segmento industrial determinados, etc.</span><span class="sxs-lookup"><span data-stu-id="5b901-435">“Availability” refers to whether or not a particular SKU is available for purchase for the given country, currency, industry segment, etc.</span></span> |
|<span data-ttu-id="5b901-436">SkuName</span><span class="sxs-lookup"><span data-stu-id="5b901-436">SkuName</span></span>  |<span data-ttu-id="5b901-437">Título para un SKU concreto.</span><span class="sxs-lookup"><span data-stu-id="5b901-437">The title for a particular SKU.</span></span> |
|<span data-ttu-id="5b901-438">ProductName</span><span class="sxs-lookup"><span data-stu-id="5b901-438">ProductName</span></span> |<span data-ttu-id="5b901-439">Nombre del producto.</span><span class="sxs-lookup"><span data-stu-id="5b901-439">The name of the product.</span></span> |
|<span data-ttu-id="5b901-440">ChargeType</span><span class="sxs-lookup"><span data-stu-id="5b901-440">ChargeType</span></span> |<span data-ttu-id="5b901-441">Tipo de cargo o ajuste.</span><span class="sxs-lookup"><span data-stu-id="5b901-441">The type of charge or adjustment.</span></span> |
|<span data-ttu-id="5b901-442">UnitPrice</span><span class="sxs-lookup"><span data-stu-id="5b901-442">UnitPrice</span></span> |<span data-ttu-id="5b901-443">Precio por producto pedido.</span><span class="sxs-lookup"><span data-stu-id="5b901-443">Price per product ordered.</span></span> |
|<span data-ttu-id="5b901-444">Quantity</span><span class="sxs-lookup"><span data-stu-id="5b901-444">Quantity</span></span> |<span data-ttu-id="5b901-445">Número de productos pedidos.</span><span class="sxs-lookup"><span data-stu-id="5b901-445">Number of products ordered.</span></span> |
|<span data-ttu-id="5b901-446">Subtotal</span><span class="sxs-lookup"><span data-stu-id="5b901-446">Subtotal</span></span> |<span data-ttu-id="5b901-447">Total sin impuestos.</span><span class="sxs-lookup"><span data-stu-id="5b901-447">Total before tax.</span></span> <span data-ttu-id="5b901-448">Comprueba que el subtotal coincide con el total previsto, en el caso de un descuento.</span><span class="sxs-lookup"><span data-stu-id="5b901-448">Checks that your subtotal matches your expected total, in case of a discount.</span></span> |
|<span data-ttu-id="5b901-449">TaxTotal</span><span class="sxs-lookup"><span data-stu-id="5b901-449">TaxTotal</span></span> |<span data-ttu-id="5b901-450">Total de todos los impuestos aplicables.</span><span class="sxs-lookup"><span data-stu-id="5b901-450">The total of all applicable taxes.</span></span> |
|<span data-ttu-id="5b901-451">Total</span><span class="sxs-lookup"><span data-stu-id="5b901-451">Total</span></span> |<span data-ttu-id="5b901-452">Número total de esta compra.</span><span class="sxs-lookup"><span data-stu-id="5b901-452">The total amount of this purchase.</span></span> |
|<span data-ttu-id="5b901-453">Moneda</span><span class="sxs-lookup"><span data-stu-id="5b901-453">Currency</span></span> |<span data-ttu-id="5b901-454">Tipo de moneda.</span><span class="sxs-lookup"><span data-stu-id="5b901-454">Currency type.</span></span> <span data-ttu-id="5b901-455">Cada entidad de facturación tiene una sola moneda.</span><span class="sxs-lookup"><span data-stu-id="5b901-455">Each billing entity has only one currency.</span></span> <span data-ttu-id="5b901-456">Comprueba que coincide con la primera factura y repite la comprobación tras cualquier actualización importante de la plataforma de facturación.</span><span class="sxs-lookup"><span data-stu-id="5b901-456">Check that it matches your first invoice and then after any major billing platform update.</span></span> |
|<span data-ttu-id="5b901-457">DiscountDetails</span><span class="sxs-lookup"><span data-stu-id="5b901-457">DiscountDetails</span></span> |<span data-ttu-id="5b901-458">Lista detallada de los descuentos relevantes.</span><span class="sxs-lookup"><span data-stu-id="5b901-458">Detailed listing of any relevant discounts.</span></span> |



## <a href="" id="charge_types"></a><span data-ttu-id="5b901-459">Asignación de cargos entre una factura y el archivo de conciliación</span><span class="sxs-lookup"><span data-stu-id="5b901-459">Mapping charges between an invoice and the reconciliation file</span></span>

<span data-ttu-id="5b901-460">La factura proporciona un resumen de los cargos, mientras que el archivo de conciliación proporciona un desglose detallado de las transacciones de elementos de línea, incluidos los tipos de cargo.</span><span class="sxs-lookup"><span data-stu-id="5b901-460">Your invoice provides a summary of charges, while your reconciliation file provides a detailed breakdown of line-item transactions, including charge types.</span></span>

<span data-ttu-id="5b901-461">Para hacer referencias cruzadas de cantidades de cargos entre el archivo de conciliación y la factura, puedes usar las opciones de filtro de Microsoft Excel para filtrar por tipo de cargo en el archivo de conciliación con el fin de asignar los cargos de facturación a un conjunto de desgloses de cargos del archivo de conciliación.</span><span class="sxs-lookup"><span data-stu-id="5b901-461">To cross-reference charge amounts between the invoice and reconciliation file, you can use Microsoft Excel's filter options to filter by charge types on the reconciliation file to map the invoice charges to a set of charge breakdowns on reconciliation file.</span></span>

<span data-ttu-id="5b901-462">Los archivos de conciliación, tanto basados en uso como en licencias, solo muestran cargos y transacciones relacionados con el uso (unidades consumidas y cargos relacionados).</span><span class="sxs-lookup"><span data-stu-id="5b901-462">Reconciliation files, both usage- and license-based, only show usage related transactions and charges (units consumed and related charges).</span></span> <span data-ttu-id="5b901-463">En el archivo de conciliación no aparecen devoluciones, descuentos o créditos excepcionales que aparecen en la factura como "Ajustes".</span><span class="sxs-lookup"><span data-stu-id="5b901-463">One off credits, discounts or refunds which appear on the invoice as “Adjustments” are not shown in the reconciliation file.</span></span>

<span data-ttu-id="5b901-464">La siguiente tabla muestra las asignaciones entre una sección de factura y los tipos de cargo asociados que es posible que se muestren en los archivos de conciliación.</span><span class="sxs-lookup"><span data-stu-id="5b901-464">The table below shows the mappings between an invoice section and associated charge types that might show up on the reconciliation files.</span></span> 

<table>
<tbody>
<tr>
<td>
<p><strong><span data-ttu-id="5b901-465">Descripción del cargo de facturación</span><span class="sxs-lookup"><span data-stu-id="5b901-465">Invoice charge description</span></span></strong></p>
</td>
<td>
<p><strong><span data-ttu-id="5b901-466">Descripción del cargo del archivo de conciliación (columna ChargeType)</span><span class="sxs-lookup"><span data-stu-id="5b901-466">Reconciliation file charge description (ChargeType column)</span></span></strong></p>
</td>
<td>
<p><strong><span data-ttu-id="5b901-467">¿Qué es este cargo?</span><span class="sxs-lookup"><span data-stu-id="5b901-467">What is this charge?</span></span></strong></p>
</td>
<td>
<p><strong><span data-ttu-id="5b901-468">¿Cómo asigno estos valores de ChargeType a la factura?</span><span class="sxs-lookup"><span data-stu-id="5b901-468">How do I map these ChargeTypes to the invoice?</span></span></strong></p>
</td>
</tr>
<tr>
<td rowspan="10">
<p><strong><span data-ttu-id="5b901-469">Cargos basado en licencia</span><span class="sxs-lookup"><span data-stu-id="5b901-469">License-based charges</span></span></strong></p>
</td>
<td>
<p><span data-ttu-id="5b901-470">Tarifa de activación</span><span class="sxs-lookup"><span data-stu-id="5b901-470">Activation fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="5b901-471">El importe cobrado al cliente cuando usa la suscripción después de adquirirla</span><span class="sxs-lookup"><span data-stu-id="5b901-471">The amount charged to the customer when they use the subscription after purchasing it</span></span></p>
</td>
<td rowspan="10">
<p><span data-ttu-id="5b901-472">Desde el archivo basado en licencia, suma la columna <strong>Amount</strong>.</span><span class="sxs-lookup"><span data-stu-id="5b901-472">From license-based file, sum the <strong>Amount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="5b901-473">Cuota de cancelación</span><span class="sxs-lookup"><span data-stu-id="5b901-473">Cancel fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="5b901-474">Cargos prorrateados reembolsados al cliente al cambiar los puestos asociados</span><span class="sxs-lookup"><span data-stu-id="5b901-474">Prorated charges refunded to the customer when associated seats are changed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="5b901-475">Tarifa de ciclo</span><span class="sxs-lookup"><span data-stu-id="5b901-475">Cycle fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="5b901-476">Cargos periódicos de una suscripción</span><span class="sxs-lookup"><span data-stu-id="5b901-476">Periodic charges for a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="5b901-477">Prorrateo de instancia de ciclo</span><span class="sxs-lookup"><span data-stu-id="5b901-477">Cycle instance prorate</span></span></p>
</td>
<td>
<p><span data-ttu-id="5b901-478">Cargos prorrateados evaluados del cliente al cambiar los puestos asociados</span><span class="sxs-lookup"><span data-stu-id="5b901-478">Prorated charges assessed from the customer when associated seats are changed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="5b901-479">Tarifas prorrateadas al cancelar</span><span class="sxs-lookup"><span data-stu-id="5b901-479">Prorate fees when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="5b901-480">Reembolso prorrateado de la parte no usada del servicio tras la cancelación</span><span class="sxs-lookup"><span data-stu-id="5b901-480">Prorated refund for unused portion of service upon cancellation</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="5b901-481">Tarifas prorrateadas al comprar</span><span class="sxs-lookup"><span data-stu-id="5b901-481">Prorate fees when purchase</span></span></p>
</td>
<td>
<p><span data-ttu-id="5b901-482">El tipo de cargo de una suscripción cuando se utiliza la facturación anual</span><span class="sxs-lookup"><span data-stu-id="5b901-482">The charge type for a subscription when using annual billing</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="5b901-483">Tarifa de compra</span><span class="sxs-lookup"><span data-stu-id="5b901-483">Purchase fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="5b901-484">El tipo de cargo de una suscripción cuando se utiliza la facturación mensual</span><span class="sxs-lookup"><span data-stu-id="5b901-484">The charge type for a subscription when using monthly billing</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="5b901-485">Tarifa prorrateada al renovar</span><span class="sxs-lookup"><span data-stu-id="5b901-485">Prorate fee when renew</span></span></p>
</td>
<td>
<p><span data-ttu-id="5b901-486">Tarifas prorrateadas tras la renovación de la suscripción</span><span class="sxs-lookup"><span data-stu-id="5b901-486">Prorated fees upon subscription renewal</span></span></p>
</td>
</tr>
<tr>

<td>
<p><span data-ttu-id="5b901-487">Tarifa de renovación</span><span class="sxs-lookup"><span data-stu-id="5b901-487">Renew fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="5b901-488">Cargo por renovar una suscripción</span><span class="sxs-lookup"><span data-stu-id="5b901-488">Charge for renewing a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="5b901-489">Tarifas prorrateadas al activar</span><span class="sxs-lookup"><span data-stu-id="5b901-489">Prorate fees when activate</span></span></p>
</td>
<td>
<p><span data-ttu-id="5b901-490">Tarifas prorrateadas desde la activación hasta el final del período de facturación</span><span class="sxs-lookup"><span data-stu-id="5b901-490">Prorated fees from activation until end of billing period</span></span></p>
</td>
</tr>
<tr>
<td rowspan="2">
<p><strong><span data-ttu-id="5b901-491">Cargos de uso</span><span class="sxs-lookup"><span data-stu-id="5b901-491">Usage Charges</span></span></strong></p>
</td>
<td>
<p><span data-ttu-id="5b901-492">Evaluar la tarifa de uso al cancelar</span><span class="sxs-lookup"><span data-stu-id="5b901-492">Assess usage fee when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="5b901-493">Tarifa de uso de acceso tras la cancelación por uso impagado durante el período de facturación actual</span><span class="sxs-lookup"><span data-stu-id="5b901-493">Access usage fee upon cancellation for unpaid usage during the current billing period</span></span></p>
</td>
<td rowspan="2">
<p><span data-ttu-id="5b901-494">Desde el archivo basado en uso, suma la columna <strong>PretaxCharges</strong>.</span><span class="sxs-lookup"><span data-stu-id="5b901-494">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="5b901-495">Evaluar la tarifa de uso para el ciclo actual</span><span class="sxs-lookup"><span data-stu-id="5b901-495">Assess usage fee for current cycle</span></span></p>
</td>
<td>
<p><span data-ttu-id="5b901-496">tarifa de uso de acceso para el período de facturación actual</span><span class="sxs-lookup"><span data-stu-id="5b901-496">Access usage fee for the current billing period</span></span></p>
</td>
</tr>
<tr>
<td>
<p><strong><span data-ttu-id="5b901-497">Créditos</span><span class="sxs-lookup"><span data-stu-id="5b901-497">Credits</span></span></strong></p>
</td>
<td>
<p><span data-ttu-id="5b901-498">Desplazamiento de un elemento de línea</span><span class="sxs-lookup"><span data-stu-id="5b901-498">Offset a line item</span></span></p>
</td>
<td>
<p><span data-ttu-id="5b901-499">Reembolso parcial o total de un elemento de línea, incluidos impuestos</span><span class="sxs-lookup"><span data-stu-id="5b901-499">Partial or whole refund to a line item, including taxes</span></span></p>
</td>
<td>
<p><span data-ttu-id="5b901-500">Desde el archivo basado en licencia, suma la columna <strong>TotalForCustomer</strong>.</span><span class="sxs-lookup"><span data-stu-id="5b901-500">From license-based file, sum the <strong>TotalForCustomer</strong> column</span></span></p>
<p><span data-ttu-id="5b901-501">Desde el archivo basado en uso, suma la columna <strong>PostTaxTotal</strong>.</span><span class="sxs-lookup"><span data-stu-id="5b901-501">From usage-based file, sum the <strong>PostTaxTotal</strong> column</span></span></p>
</td>
</tr>
<tr>
<td rowspan="4">
<p><strong><span data-ttu-id="5b901-502">Descuentos basados en uso</span><span class="sxs-lookup"><span data-stu-id="5b901-502">Usage-based discounts</span></span></strong></p>
</td>
<td>
<p><span data-ttu-id="5b901-503">Descuento de activación</span><span class="sxs-lookup"><span data-stu-id="5b901-503">Activation discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="5b901-504">Descuento que se aplica cuando se activa la suscripción</span><span class="sxs-lookup"><span data-stu-id="5b901-504">Discount applied when subscription activated</span></span></p>
</td>

<td rowspan="4">
<p><span data-ttu-id="5b901-505">Desde el archivo basado en uso, suma la columna <strong>PretaxCharges</strong>.</span><span class="sxs-lookup"><span data-stu-id="5b901-505">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="5b901-506">Descuento de ciclo</span><span class="sxs-lookup"><span data-stu-id="5b901-506">Cycle discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="5b901-507">Descuento que se aplica en cargos periódicos</span><span class="sxs-lookup"><span data-stu-id="5b901-507">Discount applied on periodic charges</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="5b901-508">Descuento de renovación</span><span class="sxs-lookup"><span data-stu-id="5b901-508">Renew discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="5b901-509">Descuento que se aplica cuando se renueva la suscripción</span><span class="sxs-lookup"><span data-stu-id="5b901-509">Discount applied when subscription renewed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="5b901-510">Descuento de cancelación</span><span class="sxs-lookup"><span data-stu-id="5b901-510">Cancel discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="5b901-511">Cargos que se aplican cuando se cancelan los descuentos</span><span class="sxs-lookup"><span data-stu-id="5b901-511">Charges applied when discounts cancelled</span></span></p>
</td>
</tr>


<tr>
<td>
<p><strong><span data-ttu-id="5b901-512">Descuentos basado en licencia</span><span class="sxs-lookup"><span data-stu-id="5b901-512">License-based discounts</span></span></strong></p>
</td>
<td>
<p><em><span data-ttu-id="5b901-513">Se pueden aplicar a varios tipos de cargo.</span><span class="sxs-lookup"><span data-stu-id="5b901-513">May be applied to multiple charge types</span></span></em></p>
</td>
<td>
<p></p>
</td>
<td>
<p><span data-ttu-id="5b901-514">Desde el archivo basado en licencia, suma la columna <strong>TotalOtherDiscount</strong>.</span><span class="sxs-lookup"><span data-stu-id="5b901-514">From license-based file, sum the <strong>TotalOtherDiscount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="5b901-515"><strong>Impuestos</strong>&nbsp;o&nbsp;<strong>IVA</strong></span><span class="sxs-lookup"><span data-stu-id="5b901-515"><strong>Taxes</strong>&nbsp;or&nbsp;<strong>VAT</strong></span></span></p>
</td>
<td>
<p><em><span data-ttu-id="5b901-516">Se pueden aplicar a varios tipos de cargo.</span><span class="sxs-lookup"><span data-stu-id="5b901-516">May be applied to multiple charge types</span></span></em></p>
<p><em><span data-ttu-id="5b901-517">Excepción: "Desplazamiento de un elemento de línea" ya incluye impuestos.</span><span class="sxs-lookup"><span data-stu-id="5b901-517">Exception: "Offset a line item" already includes taxes.</span></span> <span data-ttu-id="5b901-518">Créditos, consulta la sección anterior.</span><span class="sxs-lookup"><span data-stu-id="5b901-518">See Credits, above.</span></span></em></p>
</td>
<td>
<p><span data-ttu-id="5b901-519">Impuestos o impuesto de valor añadido (IVA)</span><span class="sxs-lookup"><span data-stu-id="5b901-519">Taxes or value-added taxes (VAT)</span></span></p>
</td>
<td>
<p><span data-ttu-id="5b901-520">Desde el archivo basado en licencia, suma la columna <strong>Tax</strong>.</span><span class="sxs-lookup"><span data-stu-id="5b901-520">From license-based file, sum the <strong>Tax</strong> column</span></span></p>
<p><span data-ttu-id="5b901-521">Desde el archivo basado en uso, suma la columna <strong>TaxAmount</strong>.</span><span class="sxs-lookup"><span data-stu-id="5b901-521">From usage-based file, sum the <strong>TaxAmount</strong> column</span></span></p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
