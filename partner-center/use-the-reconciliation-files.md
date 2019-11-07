---
title: Usar los archivos de conciliación | Centro de partners
ms.topic: article
ms.date: 07/08/2019
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Para obtener una vista detallada de los elementos de línea de cada cargo en un ciclo de facturación, descargue los archivos de conciliación del centro de Partners.
ms.assetid: FA6A6FCB-2597-44E7-93F8-8D1DD35D52EA
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: medium
ms.openlocfilehash: 7b27e99e5c0dc55fad3b06cc22316e8282dbe35c
ms.sourcegitcommit: dbaa6c2e8a0e6431f1420e024cca6d0dd54f1425
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/06/2019
ms.locfileid: "73653972"
---
# <a name="use-the-reconciliation-files"></a><span data-ttu-id="51b60-103">Usar los archivos de conciliación</span><span class="sxs-lookup"><span data-stu-id="51b60-103">Use the reconciliation files</span></span>

<span data-ttu-id="51b60-104">**Se aplica a**</span><span class="sxs-lookup"><span data-stu-id="51b60-104">**Applies to**</span></span>

-  <span data-ttu-id="51b60-105">Centro de partners</span><span class="sxs-lookup"><span data-stu-id="51b60-105">Partner Center</span></span>
-  <span data-ttu-id="51b60-106">Centro de partners para Microsoft Cloud for US Government</span><span class="sxs-lookup"><span data-stu-id="51b60-106">Partner Center for Microsoft Cloud for US Government</span></span>


<span data-ttu-id="51b60-107">Para obtener una vista detallada de los elementos de línea de cada cargo en un ciclo de facturación, descargue los archivos de conciliación del centro de Partners.</span><span class="sxs-lookup"><span data-stu-id="51b60-107">For a detailed line-item view of each charge in a billing cycle, download the reconciliation files from Partner Center.</span></span> <span data-ttu-id="51b60-108">Los detalles incluyen los cargos para las suscripciones de cada cliente y los eventos detallados (por ejemplo, una adición intermedia de puestos en una suscripción).</span><span class="sxs-lookup"><span data-stu-id="51b60-108">The details include charges for each customer's subscriptions, and detailed events (such as a mid-term addition of seats to a subscription).</span></span>

## <a name="formatting-issues"></a><span data-ttu-id="51b60-109">Problemas de formato</span><span class="sxs-lookup"><span data-stu-id="51b60-109">Formatting issues</span></span>

<span data-ttu-id="51b60-110">En ocasiones, es posible que el archivo de conciliación tenga problemas de formato.</span><span class="sxs-lookup"><span data-stu-id="51b60-110">Occasionally your recon file might have formatting issues.</span></span> <span data-ttu-id="51b60-111">(Esto puede ocurrir, por ejemplo, si no se usa la configuración regional EN-US). Siga los pasos que se indican a continuación para solucionar estos problemas.</span><span class="sxs-lookup"><span data-stu-id="51b60-111">(This can happen, for example, if the EN-US locale is not used.) Follow the steps below to fix these issues.</span></span> 

<ol>
<li><span data-ttu-id="51b60-112">Abra el archivo. csv en Excel y seleccione la primera columna.</span><span class="sxs-lookup"><span data-stu-id="51b60-112">Open the .csv file in Excel, and select the first column.</span></span> <span data-ttu-id="51b60-113">En la cinta de opciones, seleccione <strong>datos</strong>y, a continuación, seleccione <strong>texto en columnas</strong>.</span><span class="sxs-lookup"><span data-stu-id="51b60-113">On the ribbon, select <strong>Data</strong>, and then select <strong>Text to Columns</strong>.</span></span></li>

<li><span data-ttu-id="51b60-114">En el asistente convertir texto en columnas, seleccione <strong>delimitado tipo de archivo</strong>y, a continuación, seleccione <strong>siguiente</strong>.</span><span class="sxs-lookup"><span data-stu-id="51b60-114">In the Convert Text to Columns Wizard, select <strong>Delimited file type</strong>, and then select <strong>Next</strong>.</span></span></li> 

<li><span data-ttu-id="51b60-115">En el campo delimitadores, seleccione <strong>coma</strong>.</span><span class="sxs-lookup"><span data-stu-id="51b60-115">In the Delimeters field, select <strong>Comma</strong>.</span></span> <span data-ttu-id="51b60-116">Si la <strong>pestaña</strong> ya está seleccionada, puede dejarla.</span><span class="sxs-lookup"><span data-stu-id="51b60-116">If <strong>Tab</strong> is already selected, you can leave it.</span></span> <span data-ttu-id="51b60-117">Selecciona <strong>Siguiente</strong>.</span><span class="sxs-lookup"><span data-stu-id="51b60-117">Select <strong>Next</strong>.</span></span></li>

<li><span data-ttu-id="51b60-118">En el campo formato de datos de columna, seleccione <strong>Fecha: MDA</strong>y, a continuación, seleccione <strong>siguiente</strong>.</span><span class="sxs-lookup"><span data-stu-id="51b60-118">In the Column data format field, select <strong>Date: MDY</strong>, and then select <strong>Next</strong>.</span></span></li> 

<li><span data-ttu-id="51b60-119">En el campo formato de datos de columna, seleccione <strong>texto</strong> para todas las columnas de cantidad y, a continuación, seleccione <strong>Finalizar</strong>.</span><span class="sxs-lookup"><span data-stu-id="51b60-119">In the Column data format field, select <strong>Text</strong> for all amount columns, and then select <strong>Finish</strong>.</span></span></li>
</ol>

## <a name="downloading-a-large-recon-file"></a><span data-ttu-id="51b60-120">Descarga de un archivo de conciliación grande</span><span class="sxs-lookup"><span data-stu-id="51b60-120">Downloading a large recon file</span></span>

<span data-ttu-id="51b60-121">Los archivos de conciliación pueden llegar a ser muy grandes y a veces son difíciles de descargar.</span><span class="sxs-lookup"><span data-stu-id="51b60-121">Recon files can grow very large and are sometimes difficult to download.</span></span> <span data-ttu-id="51b60-122">Para obtener un script de PowerShell que ayude a descargar archivos de conciliación grandes, consulte [obtener artículos de línea de factura](https://docs.microsoft.com/partner-center/develop/get-invoiceline-items).</span><span class="sxs-lookup"><span data-stu-id="51b60-122">For a PowerShell script to help download large recon files, see [Get invoice line items](https://docs.microsoft.com/partner-center/develop/get-invoiceline-items).</span></span>

## <a href="" id="itemizebypartner"></a><span data-ttu-id="51b60-123">Elemento por asociado</span><span class="sxs-lookup"><span data-stu-id="51b60-123">Itemize by partner</span></span>


<span data-ttu-id="51b60-124">Los partners del modelo indirecto pueden usar estos campos adicionales en ambos archivos de conciliación basada en uso y en licencia para realizar el desglose por revendedor.</span><span class="sxs-lookup"><span data-stu-id="51b60-124">Partners in the indirect model can use these additional fields in both license-based and usage-based reconciliation files to itemize by reseller.</span></span>

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="51b60-125">Id. de MPN</span><span class="sxs-lookup"><span data-stu-id="51b60-125">MPN ID</span></span></th>
<th><span data-ttu-id="51b60-126">Descripción</span><span class="sxs-lookup"><span data-stu-id="51b60-126">Description</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="51b60-127">Id. de MPN</span><span class="sxs-lookup"><span data-stu-id="51b60-127">MPN ID</span></span></td>
<td><p><span data-ttu-id="51b60-128">Id. de Microsoft Partner Network (MPN) del partner de CSP (directo o indirecto).</span><span class="sxs-lookup"><span data-stu-id="51b60-128">The Microsoft Partner Network (MPN) ID of the CSP partner (direct or indirect).</span></span></p></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-129">Id. de MPN del revendedor</span><span class="sxs-lookup"><span data-stu-id="51b60-129">Reseller MPN ID</span></span></td>
<td><p><span data-ttu-id="51b60-130">Solo aparece en los archivos de conciliación de partners en el modelo indirecto.</span><span class="sxs-lookup"><span data-stu-id="51b60-130">Only appears on reconciliation files for partners in the indirect model.</span></span></p>
<p><span data-ttu-id="51b60-131">El Id. de MPN del revendedor de registro de la suscripción.</span><span class="sxs-lookup"><span data-stu-id="51b60-131">The MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="51b60-132">Corresponde al id. de revendedor indicado para la suscripción específica en el Centro de partners.</span><span class="sxs-lookup"><span data-stu-id="51b60-132">This corresponds to the reseller ID listed for the specific subscription in Partner Center.</span></span></p>
<p><span data-ttu-id="51b60-133">eTo ver o actualizar el distribuidor, en el menú del centro de Partners, seleccione <strong>clientes</strong>y, a continuación, elija el cliente de la lista.</span><span class="sxs-lookup"><span data-stu-id="51b60-133">eTo view or update the reseller, from the Partner Center menu, select <strong>Customers</strong>, then choose the customer from the list.</span></span> <span data-ttu-id="51b60-134">En el menú del cliente, selecciona <strong>Suscripciones</strong> y elige la suscripción de la lista.</span><span class="sxs-lookup"><span data-stu-id="51b60-134">In the customer menu, select <strong>Subscriptions</strong>, choose the subscription from the list.</span></span> <span data-ttu-id="51b60-135">Selecciona <strong>Actualizar</strong> para cambiar el valor de <strong>Revendedor (id. de MPN)</strong>.</span><span class="sxs-lookup"><span data-stu-id="51b60-135">Select <strong>update</strong> to change the <strong>Reseller (MPN ID)</strong>.</span></span></p>
<p><span data-ttu-id="51b60-136">Si un partner CSP vendió la suscripción directamente al cliente, su id. de MPN aparece dos veces, como id. de MPN y como id. de MPN del revendedor.</span><span class="sxs-lookup"><span data-stu-id="51b60-136">If a CSP partner sold the subscription directly to the customer, their MPN ID is listed twice, as both the MPN ID and the Reseller MPN ID.</span></span></p>
<p><span data-ttu-id="51b60-137">Si un asociado de CSP tiene un revendedor sin identificador de MPN, este valor se establece en el identificador de MPN del asociado en su lugar.</span><span class="sxs-lookup"><span data-stu-id="51b60-137">If a CSP partner has a reseller with no MPN ID, this value is set to the partner's MPN ID instead.</span></span></p>
<p><span data-ttu-id="51b60-138">Si el partner CSP quita un id. de revendedor, este valor se establece en -1.</span><span class="sxs-lookup"><span data-stu-id="51b60-138">If the CSP partner removes a reseller ID, this value will be set to -1.</span></span></p></td>
</tr>
</tbody>
</table>

 

## <a href="" id="licensebasedfiles"></a><span data-ttu-id="51b60-139">Campos de archivos basados en licencias</span><span class="sxs-lookup"><span data-stu-id="51b60-139">License-based file fields</span></span>


<span data-ttu-id="51b60-140">Para conciliar los cargos en función de los pedidos del cliente, compara el Syndication\_Partner\_Subscription\_Number del archivo de conciliación con el id. de suscripción del Centro de partners.</span><span class="sxs-lookup"><span data-stu-id="51b60-140">To reconcile your charges against your customer's orders, compare the Syndication\_Partner\_Subscription\_Number from the reconciliation file against the Subscription ID from Partner Center.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span data-ttu-id="51b60-141"><strong>Artículo</strong></span><span class="sxs-lookup"><span data-stu-id="51b60-141"><strong>Column</strong></span></span></td>
<td><span data-ttu-id="51b60-142"><strong>Descripción</strong></span><span class="sxs-lookup"><span data-stu-id="51b60-142"><strong>Description</strong></span></span></td>
<td><span data-ttu-id="51b60-143"><strong>Valor de ejemplo</strong></span><span class="sxs-lookup"><span data-stu-id="51b60-143"><strong>Sample Value</strong></span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-144">PartnerId</span><span class="sxs-lookup"><span data-stu-id="51b60-144">PartnerId</span></span></td>
<td><p><span data-ttu-id="51b60-145">Identificador único de una entidad de facturación específica, con formato de GUID.</span><span class="sxs-lookup"><span data-stu-id="51b60-145">Unique identifier for a specific billing entity, in GUID format.</span></span> <span data-ttu-id="51b60-146">No es necesario para la reconciliación, pero puede ser información útil.</span><span class="sxs-lookup"><span data-stu-id="51b60-146">Not required for reconciliation, however may be useful information.</span></span> <span data-ttu-id="51b60-147">Igual en todas las filas.</span><span class="sxs-lookup"><span data-stu-id="51b60-147">Same in all rows.</span></span></p></td>
<td><span data-ttu-id="51b60-148">8ddd03642-test-test-test-46b58d356b4e</span><span class="sxs-lookup"><span data-stu-id="51b60-148">8ddd03642-test-test-test-46b58d356b4e</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-149">CustomerID</span><span class="sxs-lookup"><span data-stu-id="51b60-149">CustomerID</span></span></td>
<td><p><span data-ttu-id="51b60-150">Id. de Microsoft único, en formato GUID, usado para identificar al cliente.</span><span class="sxs-lookup"><span data-stu-id="51b60-150">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="51b60-151">12ABCD34-001A-BCD2-987C-3210ABCD5678</span><span class="sxs-lookup"><span data-stu-id="51b60-151">12ABCD34-001A-BCD2-987C-3210ABCD5678</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-152">OrderID</span><span class="sxs-lookup"><span data-stu-id="51b60-152">OrderID</span></span></td>
<td><p><span data-ttu-id="51b60-153">Identificador único de un pedido en la plataforma de facturación de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="51b60-153">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="51b60-154">Puede ser útil para identificar al pedido al ponerse en contacto con el soporte técnico, pero no para la conciliación.</span><span class="sxs-lookup"><span data-stu-id="51b60-154">May be useful to identify the order when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="51b60-155">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="51b60-155">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-156">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="51b60-156">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="51b60-157">Identificador único de una suscripción en la plataforma de facturación de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="51b60-157">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="51b60-158">Puede ser útil para identificar a la suscripción al ponerse en contacto con el soporte técnico, pero no para la reconciliación.</span><span class="sxs-lookup"><span data-stu-id="51b60-158">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="51b60-159">No es el mismo que el identificador de suscripción en la consola de administración de partners.</span><span class="sxs-lookup"><span data-stu-id="51b60-159">This is not the same as the Subscription ID on the Partner Admin Console.</span></span> <span data-ttu-id="51b60-160">Consulte Syndication_Partner_Subscription_Number.</span><span class="sxs-lookup"><span data-stu-id="51b60-160">Please see Syndication_Partner_Subscription_Number.</span></span></p></td>
<td><span data-ttu-id="51b60-161">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="51b60-161">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-162">SyndicationPartnerSubscriptionNumber</span><span class="sxs-lookup"><span data-stu-id="51b60-162">SyndicationPartnerSubscriptionNumber</span></span></td>
<td><p><span data-ttu-id="51b60-163">Identificador único de las suscripciones.</span><span class="sxs-lookup"><span data-stu-id="51b60-163">Unique identifier for subscriptions.</span></span> <span data-ttu-id="51b60-164">Un cliente puede tener varias suscripciones para el mismo plan, por lo que es importante para el análisis de archivos de conciliación.</span><span class="sxs-lookup"><span data-stu-id="51b60-164">A customer can have multiple subscriptions for the same plan, so this is important for reconciliation file analysis.</span></span></p>
<p><span data-ttu-id="51b60-165">Este campo se asigna al identificador de suscripción en la consola de administración de partners.</span><span class="sxs-lookup"><span data-stu-id="51b60-165">This field maps to the Subscription ID in the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="51b60-166">fb977ab5-test-test-test-24c8d9591708</span><span class="sxs-lookup"><span data-stu-id="51b60-166">fb977ab5-test-test-test-24c8d9591708</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-167">OfferID</span><span class="sxs-lookup"><span data-stu-id="51b60-167">OfferID</span></span></td>
<td><p><span data-ttu-id="51b60-168">Identificador único de la oferta.</span><span class="sxs-lookup"><span data-stu-id="51b60-168">Unique offer ID.</span></span> <span data-ttu-id="51b60-169">Identificador de la oferta estándar según la lista de precios.</span><span class="sxs-lookup"><span data-stu-id="51b60-169">Standard offer ID as per price list.</span></span></p>
<p><span data-ttu-id="51b60-170"><b>Nota</b>: este valor no coincide con el id. de oferta de la lista de precios.</span><span class="sxs-lookup"><span data-stu-id="51b60-170"><b>Note</b>: This value does not match Offer ID from the price list.</span></span> <span data-ttu-id="51b60-171">Consulta DurableOfferID a continuación.</span><span class="sxs-lookup"><span data-stu-id="51b60-171">See DurableOfferID below.</span></span></p></td>
<td><span data-ttu-id="51b60-172">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span><span class="sxs-lookup"><span data-stu-id="51b60-172">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-173">DurableOfferID</span><span class="sxs-lookup"><span data-stu-id="51b60-173">DurableOfferID</span></span></td>
<td><p><span data-ttu-id="51b60-174">Id. de oferta duradera único, según se define en la lista de precios.</span><span class="sxs-lookup"><span data-stu-id="51b60-174">Unique durable offer ID, as defined in the price list.</span></span></p>
<p><span data-ttu-id="51b60-175"><b>Nota</b>: este valor coincide con el id. de oferta de la lista de precios.</span><span class="sxs-lookup"><span data-stu-id="51b60-175"><b>Note</b>: This value matches the Offer ID from the price list.</span></span></p></td>
<td><span data-ttu-id="51b60-176">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span><span class="sxs-lookup"><span data-stu-id="51b60-176">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-177">OfferName</span><span class="sxs-lookup"><span data-stu-id="51b60-177">OfferName</span></span></td>
<td><p><span data-ttu-id="51b60-178">Nombre de la oferta de servicio adquirida por el cliente, según se define en la lista de precios.</span><span class="sxs-lookup"><span data-stu-id="51b60-178">The name of the service offering purchased by the customer, as defined in the price list.</span></span></p></td>
<td><span data-ttu-id="51b60-179">Microsoft Office 365 (Plan E3)</span><span class="sxs-lookup"><span data-stu-id="51b60-179">Microsoft Office 365 (Plan E3)</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-180">SubscriptionStartDate</span><span class="sxs-lookup"><span data-stu-id="51b60-180">SubscriptionStartDate</span></span></td>
<td><p><span data-ttu-id="51b60-181">Fecha de finalización de la suscripción, establecida en el día posterior al envío del pedido.</span><span class="sxs-lookup"><span data-stu-id="51b60-181">The subscription start date, set to the day after the order is submitted.</span></span> <span data-ttu-id="51b60-182">Al consultar la fecha de inicio de la suscripción junto con la fecha de finalización, puedes determinar si el cliente aún está dentro del primer año de la suscripción o si la suscripción se ha renovado para el año siguiente.</span><span class="sxs-lookup"><span data-stu-id="51b60-182">By looking at the subscription start date in conjunction with the end date, you can determine if the customer is still within the first year of the subscription or if the subscription has been renewed for the following year.</span></span></p>
<p><span data-ttu-id="51b60-183">La hora siempre corresponde al comienzo del día, 0:00.</span><span class="sxs-lookup"><span data-stu-id="51b60-183">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="51b60-184">1/2/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="51b60-184">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-185">SubscriptionEndDate</span><span class="sxs-lookup"><span data-stu-id="51b60-185">SubscriptionEndDate</span></span></td>
<td><p><span data-ttu-id="51b60-186">La fecha de finalización de la suscripción: 12 meses + x días después de la fecha de inicio (para que se alinee con la fecha de facturación del partner) o 12 meses a partir de la fecha de renovación.</span><span class="sxs-lookup"><span data-stu-id="51b60-186">The subscription end date: 12 months + x days after start date (to align with partner billing date) or 12 months from renewal date.</span></span></p>
<p><span data-ttu-id="51b60-187">En el momento de la renovación, los precios se actualizan según la lista de precios actual.</span><span class="sxs-lookup"><span data-stu-id="51b60-187">At renewal, prices are updated to the current price list.</span></span> <span data-ttu-id="51b60-188">Es posible que se necesite una comunicación con el cliente antes de la renovación automatizada.</span><span class="sxs-lookup"><span data-stu-id="51b60-188">Customer communication may be required in advance of automated renewal.</span></span></p>
<p><span data-ttu-id="51b60-189">La hora siempre corresponde al comienzo del día, 0:00.</span><span class="sxs-lookup"><span data-stu-id="51b60-189">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="51b60-190">1/2/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="51b60-190">2/1/2015 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-191">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="51b60-191">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="51b60-192">Día de inicio de los cargos.</span><span class="sxs-lookup"><span data-stu-id="51b60-192">Start day of the charges.</span></span></p>
<p><span data-ttu-id="51b60-193">Cuando un cliente cambia los números de puestos, este número se usa para calcular los cargos por día (proporcionales).</span><span class="sxs-lookup"><span data-stu-id="51b60-193">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="51b60-194">La hora siempre corresponde al comienzo del día, 0:00.</span><span class="sxs-lookup"><span data-stu-id="51b60-194">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="51b60-195">1/2/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="51b60-195">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-196">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="51b60-196">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="51b60-197">Día de finalización de los cargos.</span><span class="sxs-lookup"><span data-stu-id="51b60-197">End day of the charges.</span></span></p>
<p><span data-ttu-id="51b60-198">Cuando un cliente cambia los números de puestos, este número se usa para calcular los cargos por día (proporcionales).</span><span class="sxs-lookup"><span data-stu-id="51b60-198">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="51b60-199">La hora siempre corresponde al fin del día, 23:59.</span><span class="sxs-lookup"><span data-stu-id="51b60-199">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="51b60-200">28/2/2015 23:59</span><span class="sxs-lookup"><span data-stu-id="51b60-200">2/28/2015 23:59</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-201">ChargeType</span><span class="sxs-lookup"><span data-stu-id="51b60-201">ChargeType</span></span></td>
<td><p><span data-ttu-id="51b60-202">Tipo de cargo o ajuste.</span><span class="sxs-lookup"><span data-stu-id="51b60-202">The type of charge or adjustment.</span></span> <span data-ttu-id="51b60-203">Consulta <a href="#charge_types">Asignación de cargos entre una factura y el archivo de conciliación</a></span><span class="sxs-lookup"><span data-stu-id="51b60-203">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="51b60-204">Consulta <a href="#charge_types">Asignación de cargos entre una factura y el archivo de conciliación</a></span><span class="sxs-lookup"><span data-stu-id="51b60-204">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-205">UnitPrice</span><span class="sxs-lookup"><span data-stu-id="51b60-205">UnitPrice</span></span></td>
<td><p><span data-ttu-id="51b60-206">Precio por puesto, tal y como se publica en la lista de precios en el momento de compra.</span><span class="sxs-lookup"><span data-stu-id="51b60-206">Price per seat, as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="51b60-207">Asegúrate de que coincide con la información almacenada en tu sistema de facturación durante la conciliación.</span><span class="sxs-lookup"><span data-stu-id="51b60-207">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="51b60-208">6.82</span><span class="sxs-lookup"><span data-stu-id="51b60-208">6.82</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-209">Cantidad</span><span class="sxs-lookup"><span data-stu-id="51b60-209">Quantity</span></span></td>
<td><p><span data-ttu-id="51b60-210">Número de puestos.</span><span class="sxs-lookup"><span data-stu-id="51b60-210">Number of seats.</span></span> <span data-ttu-id="51b60-211">Asegúrate de que coincide con la información almacenada en tu sistema de facturación durante la conciliación.</span><span class="sxs-lookup"><span data-stu-id="51b60-211">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="51b60-212">2</span><span class="sxs-lookup"><span data-stu-id="51b60-212">2</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-213">Volumen</span><span class="sxs-lookup"><span data-stu-id="51b60-213">Amount</span></span></td>
<td><p><span data-ttu-id="51b60-214">Total del precio para la cantidad.</span><span class="sxs-lookup"><span data-stu-id="51b60-214">Total of price for quantity.</span></span> <span data-ttu-id="51b60-215">Es de utilidad para comprobar que el cálculo de la cantidad coincide con la manera de calcular este valor para los clientes.</span><span class="sxs-lookup"><span data-stu-id="51b60-215">Useful to check that the amount calculation matches how you calculate this for your customers.</span></span></p></td>
<td><span data-ttu-id="51b60-216">13.32</span><span class="sxs-lookup"><span data-stu-id="51b60-216">13.32</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-217">TotalOtherDiscount</span><span class="sxs-lookup"><span data-stu-id="51b60-217">TotalOtherDiscount</span></span></td>
<td><p><span data-ttu-id="51b60-218">Cantidad de descuento que se aplica a estos cargos.</span><span class="sxs-lookup"><span data-stu-id="51b60-218">Amount of discount applied to these charges.</span></span> <span data-ttu-id="51b60-219">Las licencias de producto incluidas con una competencia o asignaciones o nuevas suscripciones válidas para un incentivo también incluirán un importe de descuento en esta columna.</span><span class="sxs-lookup"><span data-stu-id="51b60-219">Product Licenses included with a competency or MAPS or new subscriptions eligible for an incentive will also contain a discount amount in this column.</span></span></p></td>
<td><span data-ttu-id="51b60-220">2.32</span><span class="sxs-lookup"><span data-stu-id="51b60-220">2.32</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-221">Subtotal</span><span class="sxs-lookup"><span data-stu-id="51b60-221">Subtotal</span></span></td>
<td><p><span data-ttu-id="51b60-222">Total sin impuestos.</span><span class="sxs-lookup"><span data-stu-id="51b60-222">Total before tax.</span></span> <span data-ttu-id="51b60-223">Comprueba que el subtotal coincide con el total previsto, en el caso de un descuento.</span><span class="sxs-lookup"><span data-stu-id="51b60-223">Checks that your subtotal matches your expected total, in case of a discount.</span></span></p></td>
<td><span data-ttu-id="51b60-224">11</span><span class="sxs-lookup"><span data-stu-id="51b60-224">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-225">Impuestos</span><span class="sxs-lookup"><span data-stu-id="51b60-225">Tax</span></span></td>
<td><p><span data-ttu-id="51b60-226">Cargo del importe de los impuestos, en&#39;función de las reglas de impuestos del mercado y las circunstancias específicas.</span><span class="sxs-lookup"><span data-stu-id="51b60-226">Tax amount charge, based on your market&#39;s tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="51b60-227">0</span><span class="sxs-lookup"><span data-stu-id="51b60-227">0</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-228">TotalForCustomer</span><span class="sxs-lookup"><span data-stu-id="51b60-228">TotalForCustomer</span></span></td>
<td><p><span data-ttu-id="51b60-229">Total con impuestos.</span><span class="sxs-lookup"><span data-stu-id="51b60-229">Total after tax.</span></span> <span data-ttu-id="51b60-230">Comprueba si se cobran impuestos en la factura.</span><span class="sxs-lookup"><span data-stu-id="51b60-230">Checks if you are charged tax in the invoice.</span></span></p></td>
<td><span data-ttu-id="51b60-231">11</span><span class="sxs-lookup"><span data-stu-id="51b60-231">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-232">Moneda</span><span class="sxs-lookup"><span data-stu-id="51b60-232">Currency</span></span></td>
<td><p><span data-ttu-id="51b60-233">Tipo de moneda.</span><span class="sxs-lookup"><span data-stu-id="51b60-233">Currency type.</span></span> <span data-ttu-id="51b60-234">Cada entidad de facturación tiene una sola moneda.</span><span class="sxs-lookup"><span data-stu-id="51b60-234">Each billing entity has only one currency.</span></span> <span data-ttu-id="51b60-235">Comprueba que coincide con la primera factura y repite la comprobación tras cualquier actualización importante de la plataforma de facturación.</span><span class="sxs-lookup"><span data-stu-id="51b60-235">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="51b60-236">EUR</span><span class="sxs-lookup"><span data-stu-id="51b60-236">EUR</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-237">CustomerName</span><span class="sxs-lookup"><span data-stu-id="51b60-237">CustomerName</span></span></td>
<td><p><span data-ttu-id="51b60-238">Nombre&#39;de la organización del cliente como se indicó en el centro de Partners.</span><span class="sxs-lookup"><span data-stu-id="51b60-238">Customer&#39;s organization name as reported in Partner Center.</span></span> <span data-ttu-id="51b60-239">Esto es muy importante para conciliar la factura con la información del sistema.</span><span class="sxs-lookup"><span data-stu-id="51b60-239">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="51b60-240">Cliente de prueba A</span><span class="sxs-lookup"><span data-stu-id="51b60-240">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-241">MPNID</span><span class="sxs-lookup"><span data-stu-id="51b60-241">MPNID</span></span></td>
<td><p><span data-ttu-id="51b60-242">Id. de MPN del partner CSP</span><span class="sxs-lookup"><span data-stu-id="51b60-242">MPN ID of the CSP partner</span></span></p></td>
<td><span data-ttu-id="51b60-243">4390934</span><span class="sxs-lookup"><span data-stu-id="51b60-243">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-244">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="51b60-244">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="51b60-245">Id. de MPN del revendedor de registro de la suscripción.</span><span class="sxs-lookup"><span data-stu-id="51b60-245">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="51b60-246">Ver <a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">Desglosar por partner</a></span><span class="sxs-lookup"><span data-stu-id="51b60-246">See <a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">Itemize by partner</a>.</span></span></p></td>
<td><span data-ttu-id="51b60-247">4390934</span><span class="sxs-lookup"><span data-stu-id="51b60-247">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-248">DomainName</span><span class="sxs-lookup"><span data-stu-id="51b60-248">DomainName</span></span></td>
<td><p><span data-ttu-id="51b60-249">Nombre&#39;de dominio del cliente, que se usa para ayudar a identificar al cliente.</span><span class="sxs-lookup"><span data-stu-id="51b60-249">Customer&#39;s domain name, used to help identify the customer.</span></span> <span data-ttu-id="51b60-250">No debe usarse para identificar de forma exclusiva al cliente como cliente o asociado puede actualizar el dominio de cortesía/predeterminado mediante el portal de O365.</span><span class="sxs-lookup"><span data-stu-id="51b60-250">This should not be used to uniquely identify the customer as the customer/partner can update the vanity/default domain via the O365 portal.</span></span> <span data-ttu-id="51b60-251">Este campo puede aparecer en blanco hasta el segundo ciclo de facturación.</span><span class="sxs-lookup"><span data-stu-id="51b60-251">This field may appear blank until the second billing cycle.</span></span></p></td>
<td><span data-ttu-id="51b60-252">ejemplo.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="51b60-252">example.onmicrosoft.com</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-253">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="51b60-253">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="51b60-254">Alias de la suscripción.</span><span class="sxs-lookup"><span data-stu-id="51b60-254">Subscription nickname.</span></span> <span data-ttu-id="51b60-255">Si no se especifica ningún alias, el Centro de partners usa OfferName.</span><span class="sxs-lookup"><span data-stu-id="51b60-255">If no nickname is specified, Partner Center uses the OfferName.</span></span></p></td>
<td><span data-ttu-id="51b60-256">PROJECT ONLINE</span><span class="sxs-lookup"><span data-stu-id="51b60-256">PROJECT ONLINE</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-257">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="51b60-257">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="51b60-258">Nombre de la oferta de servicio adquirida por el cliente, según se define en la lista de precios.</span><span class="sxs-lookup"><span data-stu-id="51b60-258">The name of the service offering purchased by the customer, as defined in the price list.</span></span> <span data-ttu-id="51b60-259">(Este es un campo idéntico al nombre de la oferta).</span><span class="sxs-lookup"><span data-stu-id="51b60-259">(This is an identical field to Offer name).</span></span></p></td>
<td><span data-ttu-id="51b60-260">PROJECT ONLINE PREMIUM SIN CLIENTE DE PROJECT</span><span class="sxs-lookup"><span data-stu-id="51b60-260">PROJECT ONLINE PREMIUM WITHOUT PROJECT CLIENT</span></span></td>
</tr>
</tbody>
</table>


## <a href="" id="usagebasedfiles"></a><span data-ttu-id="51b60-261">Campos de archivos basados en el uso</span><span class="sxs-lookup"><span data-stu-id="51b60-261">Usage-based file fields</span></span>


<span data-ttu-id="51b60-262">Para conciliar los cargos en función del uso de tu cliente, compara los valores de ResellerID/ResellerName/ResellerBillableAccount del archivo de conciliación, el nombre del cliente y el id. de suscripción del Centro de partners.</span><span class="sxs-lookup"><span data-stu-id="51b60-262">To reconcile your charges against your customer's usage, compare the ResellerID/ResellerName/ResellerBillableAccount from the reconciliation file, the customer name, and the Subscription ID from Partner Center.</span></span>

<span data-ttu-id="51b60-263">Los siguientes campos explican los servicios usados y la clasificación.</span><span class="sxs-lookup"><span data-stu-id="51b60-263">The following fields explain which services were used and the rate.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span data-ttu-id="51b60-264"><strong>Artículo</strong></span><span class="sxs-lookup"><span data-stu-id="51b60-264"><strong>Column</strong></span></span></td>
<td><span data-ttu-id="51b60-265"><strong>Descripción</strong></span><span class="sxs-lookup"><span data-stu-id="51b60-265"><strong>Description</strong></span></span></td>
<td><span data-ttu-id="51b60-266"><strong>Valor de ejemplo</strong></span><span class="sxs-lookup"><span data-stu-id="51b60-266"><strong>Sample value</strong></span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-267">PartnerID</span><span class="sxs-lookup"><span data-stu-id="51b60-267">PartnerID</span></span></td>
<td><p><span data-ttu-id="51b60-268">Id. de partner, en formato de GUID.</span><span class="sxs-lookup"><span data-stu-id="51b60-268">Partner ID, in GUID format.</span></span></p></td>
<td><span data-ttu-id="51b60-269">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="51b60-269">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-270">PartnerName</span><span class="sxs-lookup"><span data-stu-id="51b60-270">PartnerName</span></span></td>
<td><p><span data-ttu-id="51b60-271">Nombre del partner.</span><span class="sxs-lookup"><span data-stu-id="51b60-271">Partner Name.</span></span></p></td>
<td><span data-ttu-id="51b60-272">Acme Incorporated</span><span class="sxs-lookup"><span data-stu-id="51b60-272">Acme Incorporated</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-273">PartnerBillableAccountID</span><span class="sxs-lookup"><span data-stu-id="51b60-273">PartnerBillableAccountID</span></span></td>
<td><p><span data-ttu-id="51b60-274">Id. de cuenta del partner.</span><span class="sxs-lookup"><span data-stu-id="51b60-274">Partner Account ID.</span></span></p></td>
<td><span data-ttu-id="51b60-275">1010578050</span><span class="sxs-lookup"><span data-stu-id="51b60-275">1010578050</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-276">CustomerName</span><span class="sxs-lookup"><span data-stu-id="51b60-276">CustomerName</span></span></td>
<td><p><span data-ttu-id="51b60-277">Nombre&#39;de la organización del cliente como se indicó en el centro de Partners.</span><span class="sxs-lookup"><span data-stu-id="51b60-277">Customer&#39;s organization name as reported in Partner Center.</span></span> <span data-ttu-id="51b60-278">Esto es muy importante para conciliar la factura con la información del sistema.</span><span class="sxs-lookup"><span data-stu-id="51b60-278">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="51b60-279">Cliente de prueba A</span><span class="sxs-lookup"><span data-stu-id="51b60-279">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-280">MPNID</span><span class="sxs-lookup"><span data-stu-id="51b60-280">MPNID</span></span></td>
<td><p><span data-ttu-id="51b60-281">Id. de MPN del partner CSP.</span><span class="sxs-lookup"><span data-stu-id="51b60-281">MPN ID of the CSP partner.</span></span></p></td>
<td><span data-ttu-id="51b60-282">4390934</span><span class="sxs-lookup"><span data-stu-id="51b60-282">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-283">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="51b60-283">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="51b60-284">Id. de MPN del revendedor de registro de la suscripción.</span><span class="sxs-lookup"><span data-stu-id="51b60-284">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="51b60-285">Ver <a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">Desglosar por partner</a></span><span class="sxs-lookup"><span data-stu-id="51b60-285">See <a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">Itemize by partner</a>.</span></span></p></td>
<td><span data-ttu-id="51b60-286">4390934</span><span class="sxs-lookup"><span data-stu-id="51b60-286">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-287">InvoiceNumber</span><span class="sxs-lookup"><span data-stu-id="51b60-287">InvoiceNumber</span></span></td>
<td><p><span data-ttu-id="51b60-288">Número de factura donde aparece la transacción especificada.</span><span class="sxs-lookup"><span data-stu-id="51b60-288">Invoice number where the specified transaction appears.</span></span></p></td>
<td><span data-ttu-id="51b60-289">D020001IVK</span><span class="sxs-lookup"><span data-stu-id="51b60-289">D020001IVK</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-290">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="51b60-290">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="51b60-291">Fecha de inicio del ciclo de facturación, excepto cuando se presentan fechas de datos de uso latentes no cargados previamente (del ciclo de facturación anterior).</span><span class="sxs-lookup"><span data-stu-id="51b60-291">Start date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="51b60-292">La hora siempre corresponde al comienzo del día, 0:00.</span><span class="sxs-lookup"><span data-stu-id="51b60-292">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="51b60-293">1/2/2014 0:00</span><span class="sxs-lookup"><span data-stu-id="51b60-293">2/1/2014 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-294">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="51b60-294">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="51b60-295">Fecha de finalización del ciclo de facturación, excepto cuando se presentan fechas de datos de uso latentes no cargados previamente (del ciclo de facturación anterior).</span><span class="sxs-lookup"><span data-stu-id="51b60-295">End date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="51b60-296">La hora siempre corresponde al fin del día, 23:59.</span><span class="sxs-lookup"><span data-stu-id="51b60-296">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="51b60-297">28/2/2014 23:59</span><span class="sxs-lookup"><span data-stu-id="51b60-297">2/28/2014 23:59</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-298">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="51b60-298">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="51b60-299">Identificador único de una suscripción en la plataforma de facturación de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="51b60-299">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="51b60-300">Puede ser útil para identificar a la suscripción al ponerse en contacto con el soporte técnico, pero no para la reconciliación.</span><span class="sxs-lookup"><span data-stu-id="51b60-300">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="51b60-301">No es el mismo que el identificador de suscripción en la consola de administración de partners.</span><span class="sxs-lookup"><span data-stu-id="51b60-301">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="51b60-302">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="51b60-302">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-303">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="51b60-303">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="51b60-304">Alias de la oferta de servicio.</span><span class="sxs-lookup"><span data-stu-id="51b60-304">Nickname of the service offering.</span></span></p></td>
<td><span data-ttu-id="51b60-305">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="51b60-305">Microsoft Azure</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-306">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="51b60-306">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="51b60-307">Línea de negocio de la oferta de servicio</span><span class="sxs-lookup"><span data-stu-id="51b60-307">Line of business of the service offering</span></span></p></td>
<td><span data-ttu-id="51b60-308">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="51b60-308">Microsoft Azure</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-309">OrderID</span><span class="sxs-lookup"><span data-stu-id="51b60-309">OrderID</span></span></td>
<td><p><span data-ttu-id="51b60-310">Identificador único de un pedido en la plataforma de facturación de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="51b60-310">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="51b60-311">Puede ser útil para identificar a la suscripción al ponerse en contacto con el soporte técnico, pero no para la reconciliación.</span><span class="sxs-lookup"><span data-stu-id="51b60-311">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="51b60-312">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="51b60-312">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-313">ServiceName</span><span class="sxs-lookup"><span data-stu-id="51b60-313">ServiceName</span></span></td>
<td><p><span data-ttu-id="51b60-314">Nombre del servicio de Azure en cuestión.</span><span class="sxs-lookup"><span data-stu-id="51b60-314">The name of the Azure service in question.</span></span></p></td>
<td><span data-ttu-id="51b60-315">MÁQUINAS VIRTUALES</span><span class="sxs-lookup"><span data-stu-id="51b60-315">VIRTUAL MACHINES</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-316">ServiceType</span><span class="sxs-lookup"><span data-stu-id="51b60-316">ServiceType</span></span></td>
<td><p><span data-ttu-id="51b60-317">Tipo específico de servicio de Microsoft Azure.</span><span class="sxs-lookup"><span data-stu-id="51b60-317">The specific type of Windows Azure service.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="51b60-318">Service Bus: individual o Pack</span><span class="sxs-lookup"><span data-stu-id="51b60-318">Service Bus - Individual or Pack</span></span></li>
<li><span data-ttu-id="51b60-319">Base de datos de SQL Azure: Business o Web Edition</span><span class="sxs-lookup"><span data-stu-id="51b60-319">SQL Azure database - Business or Web Edition</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-320">ResourceGUID</span><span class="sxs-lookup"><span data-stu-id="51b60-320">ResourceGUID</span></span></td>
<td><p><span data-ttu-id="51b60-321">Identificador único específico para toda la estructura de precios y datos del servicio.</span><span class="sxs-lookup"><span data-stu-id="51b60-321">Specific unique identifier for all the service data and pricing structure.</span></span></p></td>
<td><span data-ttu-id="51b60-322">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="51b60-322">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-323">Nombre del recurso</span><span class="sxs-lookup"><span data-stu-id="51b60-323">Resource Name</span></span></td>
<td><p><span data-ttu-id="51b60-324">Nombre del recurso de Azure.</span><span class="sxs-lookup"><span data-stu-id="51b60-324">The name of the Azure resource.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="51b60-325">Transferencia entrante de datos (GB)</span><span class="sxs-lookup"><span data-stu-id="51b60-325">Data Transfer In (GB)</span></span></li>
<li><span data-ttu-id="51b60-326">Transferencia saliente de datos (GB)</span><span class="sxs-lookup"><span data-stu-id="51b60-326">Data Transfer Out (GB)</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-327">Región</span><span class="sxs-lookup"><span data-stu-id="51b60-327">Region</span></span></td>
<td><p><span data-ttu-id="51b60-328">La región a la que se aplica el uso.</span><span class="sxs-lookup"><span data-stu-id="51b60-328">The region the usage applies to.</span></span> <span data-ttu-id="51b60-329">Se usa principalmente para asignar tarifas a las transferencias de datos, ya que las tarifas varían según la región.</span><span class="sxs-lookup"><span data-stu-id="51b60-329">Primarily used to assign rates to data transfers, as rates vary by region.</span></span></p></td>
<td><span data-ttu-id="51b60-330">Asia Pacífico, Europa, América Latina, América del Norte</span><span class="sxs-lookup"><span data-stu-id="51b60-330">Asia Pacific, Europe, Latin America, North America</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-331">SKU</span><span class="sxs-lookup"><span data-stu-id="51b60-331">SKU</span></span></td>
<td><p><span data-ttu-id="51b60-332">Identificador único de MSFT para la oferta</span><span class="sxs-lookup"><span data-stu-id="51b60-332">MSFT unique identifier for offer</span></span></p></td>
<td><span data-ttu-id="51b60-333">7UD 00001</span><span class="sxs-lookup"><span data-stu-id="51b60-333">7UD-00001</span></span></td>
</tr>
<tr class="odd">
<td><p><span data-ttu-id="51b60-334">DetailLineItemId</span><span class="sxs-lookup"><span data-stu-id="51b60-334">DetailLineItemId</span></span></p></td>
<td><p><span data-ttu-id="51b60-335">Un id. y una cantidad para desglosar las distintas clasificaciones de un servicio o un recurso en un período de facturación determinado.</span><span class="sxs-lookup"><span data-stu-id="51b60-335">An ID and quantity for itemizing the different rates for a service or resource in a given billing period.</span></span> <span data-ttu-id="51b60-336">Para clasificación en niveles de Azure, puede haber una clasificación hasta una cantidad determinada de unidades facturables y, posteriormente, una clasificación diferente.</span><span class="sxs-lookup"><span data-stu-id="51b60-336">For Azure tiered rating, there may be one rate up to a certain quantity of billable units, then a different rate after that.</span></span></p></td>
<td><span data-ttu-id="51b60-337">1</span><span class="sxs-lookup"><span data-stu-id="51b60-337">1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-338">ConsumedQuantity</span><span class="sxs-lookup"><span data-stu-id="51b60-338">ConsumedQuantity</span></span></td>
<td><p><span data-ttu-id="51b60-339">La cantidad de servicio consumida (horas, GB, etc.) durante el período de notificación.</span><span class="sxs-lookup"><span data-stu-id="51b60-339">The amount of service consumed (hours, GB, etc.) during the reporting period.</span></span></p>
<p><span data-ttu-id="51b60-340">También incluye cualquier uso no facturado de períodos anteriores.</span><span class="sxs-lookup"><span data-stu-id="51b60-340">Also includes any unbilled usage from previous reporting periods.</span></span></p></td>
<td><span data-ttu-id="51b60-341">11</span><span class="sxs-lookup"><span data-stu-id="51b60-341">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-342">IncludedQuantity</span><span class="sxs-lookup"><span data-stu-id="51b60-342">IncludedQuantity</span></span></td>
<td><p><span data-ttu-id="51b60-343">Unidades que se incluyen como parte de la oferta.</span><span class="sxs-lookup"><span data-stu-id="51b60-343">Units included as part of the offer.</span></span> <span data-ttu-id="51b60-344">No suele mostrarse en CSP.</span><span class="sxs-lookup"><span data-stu-id="51b60-344">Not typically present in CSP.</span></span></p></td>
<td><span data-ttu-id="51b60-345">0</span><span class="sxs-lookup"><span data-stu-id="51b60-345">0</span></span></td>
</tr>
<tr class="even">
<td><p><span data-ttu-id="51b60-346">OverageQuantity</span><span class="sxs-lookup"><span data-stu-id="51b60-346">OverageQuantity</span></span></p></td>
<td><p><span data-ttu-id="51b60-347">Unidades que no se incluyen como parte de la oferta y que el partner debe abonar.</span><span class="sxs-lookup"><span data-stu-id="51b60-347">Units not included as part of the offer, that must be paid for by the partner.</span></span></p>
<p><span data-ttu-id="51b60-348">Equivale a ConsumedQuantity - IncludedQuantity.</span><span class="sxs-lookup"><span data-stu-id="51b60-348">Equal to the ConsumedQuantity - IncludedQuantity.</span></span></p></td>
<td><span data-ttu-id="51b60-349">11</span><span class="sxs-lookup"><span data-stu-id="51b60-349">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-350">ListPrice</span><span class="sxs-lookup"><span data-stu-id="51b60-350">ListPrice</span></span></td>
<td><p><span data-ttu-id="51b60-351">Precio de la oferta en vigor la fecha de inicio de la suscripción.</span><span class="sxs-lookup"><span data-stu-id="51b60-351">Offer price in effect at subscription start date.</span></span></p></td>
<td><span data-ttu-id="51b60-352">0\.0808 USD</span><span class="sxs-lookup"><span data-stu-id="51b60-352">$0.0808</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-353">PretaxCharges</span><span class="sxs-lookup"><span data-stu-id="51b60-353">PretaxCharges</span></span></td>
<td><p><span data-ttu-id="51b60-354">ListPrist x OverageQuantity, redondeado al céntimo más próximo.</span><span class="sxs-lookup"><span data-stu-id="51b60-354">ListPrist times OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="51b60-355">0\.085 USD</span><span class="sxs-lookup"><span data-stu-id="51b60-355">$0.085</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-356">TaxAmount</span><span class="sxs-lookup"><span data-stu-id="51b60-356">TaxAmount</span></span></td>
<td><p><span data-ttu-id="51b60-357">Cargo del importe de los impuestos, en&#39;función de las reglas de impuestos del mercado y las circunstancias específicas.</span><span class="sxs-lookup"><span data-stu-id="51b60-357">Tax amount charge, based on your market&#39;s tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="51b60-358">0\.08 USD</span><span class="sxs-lookup"><span data-stu-id="51b60-358">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-359">PostTaxTotal</span><span class="sxs-lookup"><span data-stu-id="51b60-359">PostTaxTotal</span></span></td>
<td><p><span data-ttu-id="51b60-360">Total con impuestos, si se aplican impuestos.</span><span class="sxs-lookup"><span data-stu-id="51b60-360">Total after tax, when tax is applicable.</span></span></p></td>
<td><span data-ttu-id="51b60-361">0\.93 USD</span><span class="sxs-lookup"><span data-stu-id="51b60-361">$0.93</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-362">Moneda</span><span class="sxs-lookup"><span data-stu-id="51b60-362">Currency</span></span></td>
<td><p><span data-ttu-id="51b60-363">Tipo de moneda.</span><span class="sxs-lookup"><span data-stu-id="51b60-363">Currency type.</span></span> <span data-ttu-id="51b60-364">Cada entidad de facturación tiene una sola moneda.</span><span class="sxs-lookup"><span data-stu-id="51b60-364">Each billing entity has only one currency.</span></span> <span data-ttu-id="51b60-365">Comprueba que coincide con la primera factura y repite la comprobación tras cualquier actualización importante de la plataforma de facturación.</span><span class="sxs-lookup"><span data-stu-id="51b60-365">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="51b60-366">EUR</span><span class="sxs-lookup"><span data-stu-id="51b60-366">EUR</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-367">PretaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="51b60-367">PretaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="51b60-368">Precio sin impuestos por unidad.</span><span class="sxs-lookup"><span data-stu-id="51b60-368">Pretax price per unit.</span></span> <span data-ttu-id="51b60-369">Igual que PretaxCharges/OverageQuantity, redondeado al céntimo más próximo.</span><span class="sxs-lookup"><span data-stu-id="51b60-369">Equal to PretaxCharges / OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="51b60-370">0\.08 USD</span><span class="sxs-lookup"><span data-stu-id="51b60-370">$0.08</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-371">PostTaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="51b60-371">PostTaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="51b60-372">Precio después de impuestos por unidad.</span><span class="sxs-lookup"><span data-stu-id="51b60-372">Post tax price per unit.</span></span> <span data-ttu-id="51b60-373">Igual que PostTaxTotal/OverageQuantity o PretaxEffectiveRate + tipo impositivo por importe unitario, redondeado el céntimo más próximo.</span><span class="sxs-lookup"><span data-stu-id="51b60-373">Equal to PostTaxTotal / OverageQuantity, or PretaxEffectiveRate + tax rate per unit amoun, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="51b60-374">0\.08 USD</span><span class="sxs-lookup"><span data-stu-id="51b60-374">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-375">ChargeType</span><span class="sxs-lookup"><span data-stu-id="51b60-375">ChargeType</span></span></td>
<td><p><span data-ttu-id="51b60-376">Tipo de cargo o ajuste.</span><span class="sxs-lookup"><span data-stu-id="51b60-376">The type of charge or adjustment.</span></span> <span data-ttu-id="51b60-377">Consulta <a href="#charge_types">Asignación de cargos entre una factura y el archivo de conciliación</a></span><span class="sxs-lookup"><span data-stu-id="51b60-377">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="51b60-378">Consulta <a href="#charge_types">Asignación de cargos entre una factura y el archivo de conciliación</a></span><span class="sxs-lookup"><span data-stu-id="51b60-378">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-379">CustomerBillableAccount</span><span class="sxs-lookup"><span data-stu-id="51b60-379">CustomerBillableAccount</span></span></td>
<td><p><span data-ttu-id="51b60-380">Id. de cuenta único en la plataforma de facturación de MSFT.</span><span class="sxs-lookup"><span data-stu-id="51b60-380">Unique account ID in the MSFT billing platform.</span></span></p></td>
<td><span data-ttu-id="51b60-381">1280018095</span><span class="sxs-lookup"><span data-stu-id="51b60-381">1280018095</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-382">UsageDate</span><span class="sxs-lookup"><span data-stu-id="51b60-382">UsageDate</span></span></td>
<td><p><span data-ttu-id="51b60-383">Fecha de implementación del servicio.</span><span class="sxs-lookup"><span data-stu-id="51b60-383">Date of service deployment.</span></span></p></td>
<td><span data-ttu-id="51b60-384">1/2/2014 0:00</span><span class="sxs-lookup"><span data-stu-id="51b60-384">2/1/2014 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-385">MeteredRegion</span><span class="sxs-lookup"><span data-stu-id="51b60-385">MeteredRegion</span></span></td>
<td><p><span data-ttu-id="51b60-386">Esta columna identifica la ubicación de un centro de datos dentro de la región para los servicios donde esto se aplica y rellena.</span><span class="sxs-lookup"><span data-stu-id="51b60-386">This column identifies the location of a data center within the region for services where this is applicable and populated.</span></span></p></td>
<td><span data-ttu-id="51b60-387">Asia Oriental, Asia Suroriental, Norte de Europa, Europa Occidental, Centro-norte de EE. UU., Centro-sur de EE. UU.</span><span class="sxs-lookup"><span data-stu-id="51b60-387">East Asia, South East Asia, North Europe, West Europe, North Central US, South Central US</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-388">MeteredService</span><span class="sxs-lookup"><span data-stu-id="51b60-388">MeteredService</span></span></td>
<td><p><span data-ttu-id="51b60-389">Esta columna se usa para hacer un seguimiento de los servicios de Microsoft Azure individuales que quizás no se identifiquen específicamente en la columna Service Name.</span><span class="sxs-lookup"><span data-stu-id="51b60-389">This column is utilized to track the individual Microsoft Azure service that may not be specifically identified in the Service Name column.</span></span> <span data-ttu-id="51b60-390">Por ejemplo, las transferencias de datos se notifican como &quot;Microsoft Azure: todos los servicios&quot; en la columna Service Name.</span><span class="sxs-lookup"><span data-stu-id="51b60-390">For example, data transfers are reported as &quot;Microsoft Azure - All Services&quot; in the Service Name column.</span></span> <span data-ttu-id="51b60-391">En esta columna MeteredService se indicará qué servicio específico pertenece el uso.</span><span class="sxs-lookup"><span data-stu-id="51b60-391">This MeteredService column will indicate to which specific service the usage pertains.</span></span></p></td>
<td><span data-ttu-id="51b60-392">AccessControl, CDN, Proceso, Base de datos, ServiceBus, Almacenamiento</span><span class="sxs-lookup"><span data-stu-id="51b60-392">AccessControl, CDN, Compute, Database, ServiceBus, Storage</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-393">MeteredServiceType</span><span class="sxs-lookup"><span data-stu-id="51b60-393">MeteredServiceType</span></span></td>
<td><p><span data-ttu-id="51b60-394">Subtítulo que aclara el servicio de Microsoft Azure individual más allá del nivel proporcionado por el campo MeteredService.</span><span class="sxs-lookup"><span data-stu-id="51b60-394">A subheading that further clarifies the individual Microsoft Azure service beyond the level provided by the MeteredService field.</span></span></p></td>
<td><span data-ttu-id="51b60-395">EXTERNO</span><span class="sxs-lookup"><span data-stu-id="51b60-395">EXTERNAL</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-396">Proyecto</span><span class="sxs-lookup"><span data-stu-id="51b60-396">Project</span></span></td>
<td><p><span data-ttu-id="51b60-397">Nombre definido por el cliente para la instancia del servicio</span><span class="sxs-lookup"><span data-stu-id="51b60-397">Customer-defined name for their service instance</span></span></p></td>
<td><span data-ttu-id="51b60-398">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="51b60-398">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-399">ServiceInfo</span><span class="sxs-lookup"><span data-stu-id="51b60-399">ServiceInfo</span></span></td>
<td><p><span data-ttu-id="51b60-400">Número de conexiones de Bus de servicio aprovisionadas y usadas en un día determinado.</span><span class="sxs-lookup"><span data-stu-id="51b60-400">The number of ServiceBus connections that were provisioned and utilized on a given day.</span></span></p></td>
<td><span data-ttu-id="51b60-401">Por ejemplo: Si tuviera una conexión aprovisionada individualmente durante un mes de 30 días, la información de servicio 1 leería "1,000000 conexiones/30 días".</span><span class="sxs-lookup"><span data-stu-id="51b60-401">For example: if you had an individually provisioned connection during a 30 day month, Service Info 1 would read “1.000000 Connections / 30 days".</span></span> <span data-ttu-id="51b60-402">Si tiene un 25 paquete de conexiones de ServiceBus aprovisionadas y usó 1 durante ese día, la instrucción de uso diario de ese día indicaría "25 conexiones/30 días-usado: 1,000000".</span><span class="sxs-lookup"><span data-stu-id="51b60-402">If you had a 25 pack of ServiceBus connections provisioned and you had utilized 1 during that day, your daily usage statement for that day would indicate “25 Connections / 30 Days - Used: 1.000000".</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-403">CustomerID</span><span class="sxs-lookup"><span data-stu-id="51b60-403">CustomerID</span></span></td>
<td><p><span data-ttu-id="51b60-404">Id. de Microsoft único, en formato GUID, usado para identificar al cliente.</span><span class="sxs-lookup"><span data-stu-id="51b60-404">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="51b60-405">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="51b60-405">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="51b60-406">DomainName</span><span class="sxs-lookup"><span data-stu-id="51b60-406">DomainName</span></span></td>
<td><p><span data-ttu-id="51b60-407">Nombre&#39;de dominio del cliente, que se usa para ayudar a identificar al cliente.</span><span class="sxs-lookup"><span data-stu-id="51b60-407">Customer&#39;s domain name, used to help identify the customer.</span></span> <span data-ttu-id="51b60-408">Este campo puede aparecer en blanco hasta el segundo ciclo de facturación.</span><span class="sxs-lookup"><span data-stu-id="51b60-408">This field may appear blank until the second billing cycle.</span></span></p></td>
<td><span data-ttu-id="51b60-409">ejemplo.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="51b60-409">example.onmicrosoft.com</span></span></td></tr>
</tr>
<tr class="even">
<td><span data-ttu-id="51b60-410">Unidad</span><span class="sxs-lookup"><span data-stu-id="51b60-410">Unit</span></span></td>
<td><p><span data-ttu-id="51b60-411">La unidad del nombre del recurso</span><span class="sxs-lookup"><span data-stu-id="51b60-411">The unit of the resource Name</span></span></p></td>
<td><span data-ttu-id="51b60-412">GB u HORAS</span><span class="sxs-lookup"><span data-stu-id="51b60-412">GB or HOURS</span></span></td>
</tr>
</tbody>
</table>

## <a href="" id="marketplacefilefields"></a><span data-ttu-id="51b60-413">Campos de archivo de una sola vez y periódicos</span><span class="sxs-lookup"><span data-stu-id="51b60-413">One-time and recurring file fields</span></span>

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="51b60-414">Column</span><span class="sxs-lookup"><span data-stu-id="51b60-414">Column</span></span></th>
<th><span data-ttu-id="51b60-415">Descripción</span><span class="sxs-lookup"><span data-stu-id="51b60-415">Description</span></span></th>
</tr>
</thead>
<tbody>

<tr class="odd">
<td><span data-ttu-id="51b60-416">PartnerId</span><span class="sxs-lookup"><span data-stu-id="51b60-416">PartnerId</span></span></td>
<td><p><span data-ttu-id="51b60-417">Identificador único del inquilino de Microsoft Azure Active Directory para una entidad de facturación específica, en formato GUID.</span><span class="sxs-lookup"><span data-stu-id="51b60-417">Unique Microsoft Azure Active Directory tenant identifier for a specific billing entity, in GUID format.</span></span> <span data-ttu-id="51b60-418">No es necesario para la reconciliación, pero puede ser información útil.</span><span class="sxs-lookup"><span data-stu-id="51b60-418">Not required for reconciliation, however may be useful information.</span></span> <span data-ttu-id="51b60-419">Igual en todas las filas.</span><span class="sxs-lookup"><span data-stu-id="51b60-419">Same in all rows.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-420">Identificador de cliente</span><span class="sxs-lookup"><span data-stu-id="51b60-420">Customer Id</span></span></td>
<td><p><span data-ttu-id="51b60-421">IDENTIFICADOR único del inquilino de Microsoft Azure Active Directory, en formato GUID, que se usa para identificar al cliente.</span><span class="sxs-lookup"><span data-stu-id="51b60-421">Unique Microsoft Azure Active Directory tenant ID, in GUID format, used to identify the customer.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-422">Nombre del cliente</span><span class="sxs-lookup"><span data-stu-id="51b60-422">Customer Name</span></span></td>
<td><p><span data-ttu-id="51b60-423">Nombre de la organización del cliente según se indica en el Centro de partners.</span><span class="sxs-lookup"><span data-stu-id="51b60-423">Customer's organization name as reported in Partner Center.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-424">CustomerDomainName</span><span class="sxs-lookup"><span data-stu-id="51b60-424">CustomerDomainName</span></span></td>
<td><p><span data-ttu-id="51b60-425">Nombre de dominio del cliente, que se usa para identificar al cliente.</span><span class="sxs-lookup"><span data-stu-id="51b60-425">Customer's domain name, used to help identify the customer.</span></span> <span data-ttu-id="51b60-426">No debe usarse para identificar de forma exclusiva al cliente como cliente o asociado puede actualizar el dominio de cortesía/predeterminado mediante el portal de O365.</span><span class="sxs-lookup"><span data-stu-id="51b60-426">This should not be used to uniquely identify the customer as the customer/partner can update the vanity/default domain via the O365 portal.</span></span> <span data-ttu-id="51b60-427">Este campo puede aparecer en blanco hasta el segundo ciclo de facturación.</span><span class="sxs-lookup"><span data-stu-id="51b60-427">This field may appear blank until the second billing cycle.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-428">País del cliente</span><span class="sxs-lookup"><span data-stu-id="51b60-428">Customer Country</span></span></td>
<td><p><span data-ttu-id="51b60-429">El país donde se encuentra el cliente.</span><span class="sxs-lookup"><span data-stu-id="51b60-429">The country in which the customer is located.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-430">Número de factura</span><span class="sxs-lookup"><span data-stu-id="51b60-430">Invoice number</span></span></td>
<td><p><span data-ttu-id="51b60-431">Número de factura donde aparece la transacción especificada.</span><span class="sxs-lookup"><span data-stu-id="51b60-431">Invoice number where the specified transaction appears.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-432">MpnId</span><span class="sxs-lookup"><span data-stu-id="51b60-432">MpnId</span></span></td>
<td><p><span data-ttu-id="51b60-433">Id. de MPN del partner CSP.</span><span class="sxs-lookup"><span data-stu-id="51b60-433">MPN ID of the CSP partner.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-434">Reseller MpnId</span><span class="sxs-lookup"><span data-stu-id="51b60-434">Reseller MpnId</span></span></td>
<td><p><span data-ttu-id="51b60-435">Id. de MPN del revendedor de registro de la suscripción.</span><span class="sxs-lookup"><span data-stu-id="51b60-435">MPN ID of the reseller of record for the subscription.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-436">Id. de pedido</span><span class="sxs-lookup"><span data-stu-id="51b60-436">Order ID</span></span></td>
<td><p><span data-ttu-id="51b60-437">Identificador único para un pedido en la plataforma de comercio de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="51b60-437">Unique identifier for an order in the Microsoft commerce platform.</span></span> <span data-ttu-id="51b60-438">Puede ser útil para identificar al pedido al ponerse en contacto con el soporte técnico, pero no para la conciliación.</span><span class="sxs-lookup"><span data-stu-id="51b60-438">May be useful to identify the order when contacting support but not for reconciliation.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-439">Fecha del pedido</span><span class="sxs-lookup"><span data-stu-id="51b60-439">Order date</span></span></td>
<td><p><span data-ttu-id="51b60-440">Fecha de realización del pedido.</span><span class="sxs-lookup"><span data-stu-id="51b60-440">The date the order was placed.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-441">ProductId</span><span class="sxs-lookup"><span data-stu-id="51b60-441">ProductId</span></span></td>
<td><p><span data-ttu-id="51b60-442">Identificador del producto.</span><span class="sxs-lookup"><span data-stu-id="51b60-442">The ID for the product.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-443">SkuId</span><span class="sxs-lookup"><span data-stu-id="51b60-443">SkuId</span></span></td>
<td><p><span data-ttu-id="51b60-444">Id. de un SKU concreto.</span><span class="sxs-lookup"><span data-stu-id="51b60-444">The ID for a particular SKU.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-445">AvailabilityId</span><span class="sxs-lookup"><span data-stu-id="51b60-445">AvailabilityId</span></span></td>
<td><p><span data-ttu-id="51b60-446">Id. de una disponibilidad concreta.</span><span class="sxs-lookup"><span data-stu-id="51b60-446">The ID for a particular Availability.</span></span> <span data-ttu-id="51b60-447">"Disponibilidad" se refiere a si una SKU determinada está disponible para su compra en el país, la moneda, el segmento del sector, etc.</span><span class="sxs-lookup"><span data-stu-id="51b60-447">“Availability" refers to whether or not a particular SKU is available for purchase for the given country, currency, industry segment, etc.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-448">Nombre de SKU</span><span class="sxs-lookup"><span data-stu-id="51b60-448">SKU Name</span></span></td>
<td><p><span data-ttu-id="51b60-449">Título para un SKU concreto.</span><span class="sxs-lookup"><span data-stu-id="51b60-449">The title for a particular SKU.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-450">Nombre del producto</span><span class="sxs-lookup"><span data-stu-id="51b60-450">Product name</span></span></td>
<td><p><span data-ttu-id="51b60-451">Nombre del producto.</span><span class="sxs-lookup"><span data-stu-id="51b60-451">The name of the product.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-452">PublisherName</span><span class="sxs-lookup"><span data-stu-id="51b60-452">PublisherName</span></span></td>
<td><p><span data-ttu-id="51b60-453">Nombre del publicador del producto.</span><span class="sxs-lookup"><span data-stu-id="51b60-453">The name of the product's publisher.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-454">PublisherID</span><span class="sxs-lookup"><span data-stu-id="51b60-454">PublisherID</span></span></td>
<td><p><span data-ttu-id="51b60-455">IDENTIFICADOR único para este publicador.</span><span class="sxs-lookup"><span data-stu-id="51b60-455">Unique ID for this publisher.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-456">Descripción de la suscripción</span><span class="sxs-lookup"><span data-stu-id="51b60-456">Subscription Description</span></span></td>
<td><p><span data-ttu-id="51b60-457">Nombre descriptivo de una suscripción.</span><span class="sxs-lookup"><span data-stu-id="51b60-457">Friendly name of a subscription.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-458">Id. de la suscripción</span><span class="sxs-lookup"><span data-stu-id="51b60-458">Subscription ID</span></span></td>
<td><p><span data-ttu-id="51b60-459">Identificador único de una suscripción en la plataforma de comercio de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="51b60-459">Unique identifier for a subscription in the Microsoft commerce platform.</span></span> <span data-ttu-id="51b60-460">Puede ser útil para identificar a la suscripción al ponerse en contacto con el soporte técnico, pero no para la reconciliación.</span><span class="sxs-lookup"><span data-stu-id="51b60-460">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span> <span data-ttu-id="51b60-461">No es el mismo que el identificador de suscripción en la consola de administración de partners.</span><span class="sxs-lookup"><span data-stu-id="51b60-461">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-462">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="51b60-462">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="51b60-463">Día de inicio de los cargos.</span><span class="sxs-lookup"><span data-stu-id="51b60-463">Start day of the charges.</span></span> <span data-ttu-id="51b60-464">La hora siempre corresponde al comienzo del día, 0:00.</span><span class="sxs-lookup"><span data-stu-id="51b60-464">The time is always the beginning of the day, 0:00.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-465">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="51b60-465">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="51b60-466">Día de finalización de los cargos.</span><span class="sxs-lookup"><span data-stu-id="51b60-466">End day of the charges.</span></span> <span data-ttu-id="51b60-467">La hora siempre corresponde al fin del día, 23:59.</span><span class="sxs-lookup"><span data-stu-id="51b60-467">The time is always the end of the day, 23:59.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-468">Term y Billingcycle</span><span class="sxs-lookup"><span data-stu-id="51b60-468">Term and Billingcycle</span></span></td>
<td><p><span data-ttu-id="51b60-469">La duración del período y el ciclo de facturación de la compra.</span><span class="sxs-lookup"><span data-stu-id="51b60-469">The term length and billing cycle for the purchase.</span></span> <span data-ttu-id="51b60-470">Por ejemplo, "1 año, mensualmente".</span><span class="sxs-lookup"><span data-stu-id="51b60-470">For example, “1 Year, Monthly."</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-471">Tipo de cargo</span><span class="sxs-lookup"><span data-stu-id="51b60-471">Charge Type</span></span></td>
<td><p><span data-ttu-id="51b60-472">Tipo de cargo o ajuste.</span><span class="sxs-lookup"><span data-stu-id="51b60-472">The type of charge or adjustment.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-473">Precio unitario</span><span class="sxs-lookup"><span data-stu-id="51b60-473">Unit Price</span></span></td>
<td><p><span data-ttu-id="51b60-474">El precio publicado en el pricelist en el momento de la compra.</span><span class="sxs-lookup"><span data-stu-id="51b60-474">The price as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="51b60-475">Asegúrate de que coincide con la información almacenada en tu sistema de facturación durante la conciliación.</span><span class="sxs-lookup"><span data-stu-id="51b60-475">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-476">Precio unitario efectivo</span><span class="sxs-lookup"><span data-stu-id="51b60-476">Effective Unit Price</span></span></td>
<td><p><span data-ttu-id="51b60-477">Precio unitario tras realizar los ajustes.</span><span class="sxs-lookup"><span data-stu-id="51b60-477">The unit price after adjustments have been made.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-478">Cantidad</span><span class="sxs-lookup"><span data-stu-id="51b60-478">Quantity</span></span></td>
<td><p><span data-ttu-id="51b60-479">Número de unidades.</span><span class="sxs-lookup"><span data-stu-id="51b60-479">Number of units.</span></span> <span data-ttu-id="51b60-480">Asegúrate de que coincide con la información almacenada en tu sistema de facturación durante la conciliación.</span><span class="sxs-lookup"><span data-stu-id="51b60-480">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-481">Tipo de unidad</span><span class="sxs-lookup"><span data-stu-id="51b60-481">Unit type</span></span></td>
<td><p><span data-ttu-id="51b60-482">Tipo de unidad que se va a adquirir.</span><span class="sxs-lookup"><span data-stu-id="51b60-482">The type of unit being purchased.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-483">DiscountDetails</span><span class="sxs-lookup"><span data-stu-id="51b60-483">DiscountDetails</span></span></td>
<td><p><span data-ttu-id="51b60-484">Explicación de cualquier descuento aplicable.</span><span class="sxs-lookup"><span data-stu-id="51b60-484">An explanation of any applicable discount.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-485">Subtotal</span><span class="sxs-lookup"><span data-stu-id="51b60-485">Sub Total</span></span></td>
<td><p><span data-ttu-id="51b60-486">Total sin impuestos.</span><span class="sxs-lookup"><span data-stu-id="51b60-486">Total before tax.</span></span> <span data-ttu-id="51b60-487">Comprueba que el subtotal coincide con el total previsto, en el caso de un descuento.</span><span class="sxs-lookup"><span data-stu-id="51b60-487">Checks that your subtotal matches your expected total, in case of a discount.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-488">Total de impuestos</span><span class="sxs-lookup"><span data-stu-id="51b60-488">Tax Total</span></span></td>
<td><p><span data-ttu-id="51b60-489">Cargo por importe de impuestos, en función de las reglas fiscales de tu mercado y las circunstancias específicas.</span><span class="sxs-lookup"><span data-stu-id="51b60-489">Tax amount charge, based on your market's tax rules and specific circumstances.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-490">Total</span><span class="sxs-lookup"><span data-stu-id="51b60-490">Total</span></span></td>
<td><p><span data-ttu-id="51b60-491">Total con impuestos.</span><span class="sxs-lookup"><span data-stu-id="51b60-491">Total after tax.</span></span> <span data-ttu-id="51b60-492">Comprueba si se cobran impuestos en la factura.</span><span class="sxs-lookup"><span data-stu-id="51b60-492">Checks if you are charged tax in the invoice.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-493">Moneda</span><span class="sxs-lookup"><span data-stu-id="51b60-493">Currency</span></span></td>
<td><p><span data-ttu-id="51b60-494">Tipo de moneda.</span><span class="sxs-lookup"><span data-stu-id="51b60-494">Currency type.</span></span> <span data-ttu-id="51b60-495">Cada entidad de facturación tiene una sola moneda.</span><span class="sxs-lookup"><span data-stu-id="51b60-495">Each billing entity has only one currency.</span></span> <span data-ttu-id="51b60-496">Comprueba que coincide con la primera factura y repite la comprobación tras cualquier actualización importante de la plataforma de facturación.</span><span class="sxs-lookup"><span data-stu-id="51b60-496">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-497">AlternateID</span><span class="sxs-lookup"><span data-stu-id="51b60-497">AlternateID</span></span></td>
<td><p><span data-ttu-id="51b60-498">Un identificador alternativo a un identificador de pedido.</span><span class="sxs-lookup"><span data-stu-id="51b60-498">An alternate identifier to an order ID.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-499">BillingFrequency</span><span class="sxs-lookup"><span data-stu-id="51b60-499">BillingFrequency</span></span></td>
<td><p> <span data-ttu-id="51b60-500">Muestra mensualmente cuando se habilita la facturación mensual.</span><span class="sxs-lookup"><span data-stu-id="51b60-500">Displays monthly when monthly billing is enabled.</span></span> <span data-ttu-id="51b60-501">En caso contrario, en blanco.</span><span class="sxs-lookup"><span data-stu-id="51b60-501">Otherwise blank.</span></span> </p></td>
</tr>

</tbody>
</table>


## <a href="" id="dailyratedusagefields"></a><span data-ttu-id="51b60-502">Campos de archivo de uso con clasificación diaria</span><span class="sxs-lookup"><span data-stu-id="51b60-502">Daily-rated usage file fields</span></span>


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="51b60-503">Column</span><span class="sxs-lookup"><span data-stu-id="51b60-503">Column</span></span></th>
<th><span data-ttu-id="51b60-504">Descripción</span><span class="sxs-lookup"><span data-stu-id="51b60-504">Description</span></span></th>
</tr>
</thead>
<tbody>

<tr class="odd">
<td><span data-ttu-id="51b60-505">PartnerId</span><span class="sxs-lookup"><span data-stu-id="51b60-505">PartnerId</span></span></td>
<td><p><span data-ttu-id="51b60-506">Id. de partner, en formato de GUID.</span><span class="sxs-lookup"><span data-stu-id="51b60-506">Partner ID, in GUID format.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-507">PartnerName</span><span class="sxs-lookup"><span data-stu-id="51b60-507">PartnerName</span></span></td>
<td><p><span data-ttu-id="51b60-508">Nombre del partner.</span><span class="sxs-lookup"><span data-stu-id="51b60-508">Partner Name.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-509">CustomerId</span><span class="sxs-lookup"><span data-stu-id="51b60-509">CustomerId</span></span></td>
<td><p><span data-ttu-id="51b60-510">Id. de Microsoft único, en formato GUID, usado para identificar al cliente.</span><span class="sxs-lookup"><span data-stu-id="51b60-510">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-511">CustomerCompanyName</span><span class="sxs-lookup"><span data-stu-id="51b60-511">CustomerCompanyName</span></span></td>
<td><p><span data-ttu-id="51b60-512">Nombre de la organización del cliente según se indica en el Centro de partners.</span><span class="sxs-lookup"><span data-stu-id="51b60-512">Customer's organization name as reported in Partner Center.</span></span> <span data-ttu-id="51b60-513">Esto es muy importante para conciliar la factura con la información del sistema.</span><span class="sxs-lookup"><span data-stu-id="51b60-513">This is very important for reconciling the invoice with your system information.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-514">CustomerDomainName</span><span class="sxs-lookup"><span data-stu-id="51b60-514">CustomerDomainName</span></span></td>
<td><p><span data-ttu-id="51b60-515">El nombre de dominio del cliente.</span><span class="sxs-lookup"><span data-stu-id="51b60-515">The customer's domain name.</span></span> <span data-ttu-id="51b60-516">No está disponible para la actividad actual.</span><span class="sxs-lookup"><span data-stu-id="51b60-516">Not available for current activity.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-517">País del cliente</span><span class="sxs-lookup"><span data-stu-id="51b60-517">Customer country</span></span></td>
<td><p><span data-ttu-id="51b60-518">El país donde se encuentra el cliente.</span><span class="sxs-lookup"><span data-stu-id="51b60-518">The country in which the customer is located.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-519">MPNID</span><span class="sxs-lookup"><span data-stu-id="51b60-519">MPNID</span></span></td>
<td><p><span data-ttu-id="51b60-520">Id. de MPN del partner CSP.</span><span class="sxs-lookup"><span data-stu-id="51b60-520">MPN ID of the CSP partner.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-521">Reseller MPNID</span><span class="sxs-lookup"><span data-stu-id="51b60-521">Reseller MPNID</span></span></td>
<td><p><span data-ttu-id="51b60-522">Id. de MPN del revendedor de registro de la suscripción.</span><span class="sxs-lookup"><span data-stu-id="51b60-522">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="51b60-523">No está disponible para la actividad actual.</span><span class="sxs-lookup"><span data-stu-id="51b60-523">Not available for current activity.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-524">InvoiceNumber</span><span class="sxs-lookup"><span data-stu-id="51b60-524">InvoiceNumber</span></span></td>
<td><p><span data-ttu-id="51b60-525">Número de factura donde aparece la transacción especificada.</span><span class="sxs-lookup"><span data-stu-id="51b60-525">Invoice number where the specified transaction appears.</span></span> <span data-ttu-id="51b60-526">No está disponible para la actividad actual.</span><span class="sxs-lookup"><span data-stu-id="51b60-526">Not available for current activity.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-527">ProductId</span><span class="sxs-lookup"><span data-stu-id="51b60-527">ProductId</span></span></td>
<td><p><span data-ttu-id="51b60-528">Identificador del producto.</span><span class="sxs-lookup"><span data-stu-id="51b60-528">The ID for the product.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-529">SkuId</span><span class="sxs-lookup"><span data-stu-id="51b60-529">SkuId</span></span></td>
<td><p><span data-ttu-id="51b60-530">Id. de un SKU concreto.</span><span class="sxs-lookup"><span data-stu-id="51b60-530">The ID for a particular SKU.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-531">AvailabilityId</span><span class="sxs-lookup"><span data-stu-id="51b60-531">AvailabilityId</span></span></td>
<td><p><span data-ttu-id="51b60-532">Id. de una disponibilidad concreta.</span><span class="sxs-lookup"><span data-stu-id="51b60-532">The ID for a particular Availability.</span></span> <span data-ttu-id="51b60-533">"Disponibilidad" se refiere a si una SKU determinada está disponible para su compra en el país, la moneda, el segmento del sector, etc.</span><span class="sxs-lookup"><span data-stu-id="51b60-533">“Availability" refers to whether or not a particular SKU is available for purchase for the given country, currency, industry segment, etc.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-534">Nombre de SKU</span><span class="sxs-lookup"><span data-stu-id="51b60-534">SKU Name</span></span></td>
<td><p><span data-ttu-id="51b60-535">Título para un SKU concreto.</span><span class="sxs-lookup"><span data-stu-id="51b60-535">The title for a particular SKU.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-536">PublisherName</span><span class="sxs-lookup"><span data-stu-id="51b60-536">PublisherName</span></span></td>
<td><p><span data-ttu-id="51b60-537">Nombre del publicador.</span><span class="sxs-lookup"><span data-stu-id="51b60-537">The name of the publisher.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-538">PublisherID</span><span class="sxs-lookup"><span data-stu-id="51b60-538">PublisherID</span></span></td>
<td><p><span data-ttu-id="51b60-539">IDENTIFICADOR del publicador, en formato GUID.</span><span class="sxs-lookup"><span data-stu-id="51b60-539">The ID of the publisher, in GUID format.</span></span> <span data-ttu-id="51b60-540">No está disponible para la actividad actual.</span><span class="sxs-lookup"><span data-stu-id="51b60-540">Not available for current activity.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-541">Descripción de la suscripción</span><span class="sxs-lookup"><span data-stu-id="51b60-541">Subscription Description</span></span></td>
<td><p><span data-ttu-id="51b60-542">Nombre de la oferta de servicio adquirida por el cliente, según se define en la lista de precios.</span><span class="sxs-lookup"><span data-stu-id="51b60-542">The name of the service offering purchased by the customer, as defined in the price list.</span></span> <span data-ttu-id="51b60-543">(Este es un campo idéntico al nombre de la oferta).</span><span class="sxs-lookup"><span data-stu-id="51b60-543">(This is an identical field to Offer name).</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-544">Id. de la suscripción</span><span class="sxs-lookup"><span data-stu-id="51b60-544">Subscription ID</span></span></td>
<td><p><span data-ttu-id="51b60-545">Identificador único de una suscripción en la plataforma de facturación de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="51b60-545">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="51b60-546">Puede ser útil para identificar a la suscripción al ponerse en contacto con el soporte técnico, pero no para la reconciliación.</span><span class="sxs-lookup"><span data-stu-id="51b60-546">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span> <span data-ttu-id="51b60-547">No es el mismo que el identificador de suscripción en la consola de administración de partners.</span><span class="sxs-lookup"><span data-stu-id="51b60-547">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-548">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="51b60-548">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="51b60-549">Fecha de inicio del ciclo de facturación, excepto cuando se presentan fechas de datos de uso latentes no cargados previamente (del ciclo de facturación anterior).</span><span class="sxs-lookup"><span data-stu-id="51b60-549">Start date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span> <span data-ttu-id="51b60-550">La hora siempre corresponde al comienzo del día, 0:00.</span><span class="sxs-lookup"><span data-stu-id="51b60-550">The time is always the beginning of the day, 0:00.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-551">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="51b60-551">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="51b60-552">Fecha de finalización del ciclo de facturación, excepto cuando se presentan fechas de datos de uso latentes no cargados previamente (del ciclo de facturación anterior).</span><span class="sxs-lookup"><span data-stu-id="51b60-552">End date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span> <span data-ttu-id="51b60-553">La hora siempre corresponde al fin del día, 23:59.</span><span class="sxs-lookup"><span data-stu-id="51b60-553">The time is always the end of the day, 23:59.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-554">Fecha de uso</span><span class="sxs-lookup"><span data-stu-id="51b60-554">Usage Date</span></span></td>
<td><p><span data-ttu-id="51b60-555">Fecha del uso del servicio.</span><span class="sxs-lookup"><span data-stu-id="51b60-555">Date of service usage.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-556">Tipo de medidor</span><span class="sxs-lookup"><span data-stu-id="51b60-556">Meter Type</span></span></td>
<td><p><span data-ttu-id="51b60-557">Tipo de medidor.</span><span class="sxs-lookup"><span data-stu-id="51b60-557">The type of meter.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-558">Categoría de medidor</span><span class="sxs-lookup"><span data-stu-id="51b60-558">Meter Category</span></span></td>
<td><p><span data-ttu-id="51b60-559">El servicio de nivel superior para el uso.</span><span class="sxs-lookup"><span data-stu-id="51b60-559">The top-level service for the usage.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-560">ID. de medidor</span><span class="sxs-lookup"><span data-stu-id="51b60-560">Meter Id</span></span></td>
<td><p><span data-ttu-id="51b60-561">IDENTIFICADOR del medidor que se está usando.</span><span class="sxs-lookup"><span data-stu-id="51b60-561">The ID for the meter being used.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-562">Subcategoría de medidor</span><span class="sxs-lookup"><span data-stu-id="51b60-562">Meter Sub-category</span></span></td>
<td><p><span data-ttu-id="51b60-563">El tipo de servicio de Azure que puede afectar a la tarifa.</span><span class="sxs-lookup"><span data-stu-id="51b60-563">The type of Azure service that can affect the rate.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-564">Nombre del medidor</span><span class="sxs-lookup"><span data-stu-id="51b60-564">Meter Name</span></span></td>
<td><p><span data-ttu-id="51b60-565">Unidad de medida del medidor que se está consumiendo.</span><span class="sxs-lookup"><span data-stu-id="51b60-565">The unit of measure for the meter being consumed.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-566">Región de medidor</span><span class="sxs-lookup"><span data-stu-id="51b60-566">Meter Region</span></span></td>
<td><p><span data-ttu-id="51b60-567">Esta columna identifica la ubicación de un centro de datos dentro de la región para los servicios donde esto se aplica y rellena.</span><span class="sxs-lookup"><span data-stu-id="51b60-567">This column identifies the location of a data center within the region for services where this is applicable and populated.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-568">Unidad</span><span class="sxs-lookup"><span data-stu-id="51b60-568">Unit</span></span></td>
<td><p><span data-ttu-id="51b60-569">Unidad del nombre del recurso.</span><span class="sxs-lookup"><span data-stu-id="51b60-569">The unit of the resource Name.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-570">Cantidad consumida</span><span class="sxs-lookup"><span data-stu-id="51b60-570">Consumed Quantity</span></span></td>
<td><p><span data-ttu-id="51b60-571">La cantidad de servicio consumida (horas, GB, etc.) durante el período de notificación.</span><span class="sxs-lookup"><span data-stu-id="51b60-571">The amount of service consumed (hours, GB, etc.) during the reporting period.</span></span> <span data-ttu-id="51b60-572">También incluye cualquier uso no facturado de períodos anteriores.</span><span class="sxs-lookup"><span data-stu-id="51b60-572">Also includes any unbilled usage from previous reporting periods.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-573">Ubicación del recurso</span><span class="sxs-lookup"><span data-stu-id="51b60-573">Resource Location</span></span></td>
<td><p><span data-ttu-id="51b60-574">Centro de recursos en el que se está ejecutando el medidor.</span><span class="sxs-lookup"><span data-stu-id="51b60-574">The datacenter where the meter is running.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-575">Servicio consumido</span><span class="sxs-lookup"><span data-stu-id="51b60-575">Consumed Service</span></span></td>
<td><p><span data-ttu-id="51b60-576">El servicio de la plataforma Azure que ha usado.</span><span class="sxs-lookup"><span data-stu-id="51b60-576">The Azure platform service that you used.</span></span></p></td>
</tr>


<tr class="even">
<td><span data-ttu-id="51b60-577">URI de recurso</span><span class="sxs-lookup"><span data-stu-id="51b60-577">Resource URI</span></span></td>
<td><p><span data-ttu-id="51b60-578">URI del recurso que se va a usar.</span><span class="sxs-lookup"><span data-stu-id="51b60-578">The URI of the resource being used.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-579">Tipo de cargo</span><span class="sxs-lookup"><span data-stu-id="51b60-579">Charge type</span></span></td>
<td><p><span data-ttu-id="51b60-580">Tipo de cargo o ajuste.</span><span class="sxs-lookup"><span data-stu-id="51b60-580">The type of charge or adjustment.</span></span> <span data-ttu-id="51b60-581">No está disponible para la actividad actual.</span><span class="sxs-lookup"><span data-stu-id="51b60-581">Not available for current activity.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-582">Precio unitario</span><span class="sxs-lookup"><span data-stu-id="51b60-582">Unit price</span></span></td>
<td><p><span data-ttu-id="51b60-583">Precio por licencia, tal y como se publica en el pricelist en el momento de la compra.</span><span class="sxs-lookup"><span data-stu-id="51b60-583">Price per license, as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="51b60-584">Asegúrate de que coincide con la información almacenada en tu sistema de facturación durante la conciliación.</span><span class="sxs-lookup"><span data-stu-id="51b60-584">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-585">Cantidad</span><span class="sxs-lookup"><span data-stu-id="51b60-585">Quantity</span></span></td>
<td><p><span data-ttu-id="51b60-586">Número de licencias.</span><span class="sxs-lookup"><span data-stu-id="51b60-586">Number of licenses.</span></span> <span data-ttu-id="51b60-587">Asegúrate de que coincide con la información almacenada en tu sistema de facturación durante la conciliación.</span><span class="sxs-lookup"><span data-stu-id="51b60-587">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-588">Tipo de unidad</span><span class="sxs-lookup"><span data-stu-id="51b60-588">Unit type</span></span></td>
<td><p><span data-ttu-id="51b60-589">Tipo de unidad en la que se carga el medidor.</span><span class="sxs-lookup"><span data-stu-id="51b60-589">The type of unit the meter is charged in.</span></span> <span data-ttu-id="51b60-590">No está disponible para la actividad actual.</span><span class="sxs-lookup"><span data-stu-id="51b60-590">Not available for current activity.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-591">Impuesto previo de facturación</span><span class="sxs-lookup"><span data-stu-id="51b60-591">Billing pre tax</span></span></td>
<td><p><span data-ttu-id="51b60-592">Importe total antes de los impuestos.</span><span class="sxs-lookup"><span data-stu-id="51b60-592">Total amount before taxes.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-593">Moneda de facturación</span><span class="sxs-lookup"><span data-stu-id="51b60-593">Billing currency</span></span></td>
<td><p><span data-ttu-id="51b60-594">La moneda en la región geográfica del cliente</span><span class="sxs-lookup"><span data-stu-id="51b60-594">The currency in the customer's geographic region</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-595">Precio pretax total</span><span class="sxs-lookup"><span data-stu-id="51b60-595">Pricing pretax total</span></span></td>
<td><p><span data-ttu-id="51b60-596">Los precios antes de que se agreguen los impuestos.</span><span class="sxs-lookup"><span data-stu-id="51b60-596">The pricing before taxes are added.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-597">Moneda de precios</span><span class="sxs-lookup"><span data-stu-id="51b60-597">Pricing currency</span></span></td>
<td><p><span data-ttu-id="51b60-598">La moneda en el pricelist.</span><span class="sxs-lookup"><span data-stu-id="51b60-598">The currency in the pricelist.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="51b60-599">Información de servicio 1</span><span class="sxs-lookup"><span data-stu-id="51b60-599">Service Info 1</span></span></td>
<td><p><span data-ttu-id="51b60-600">Número de conexiones de Bus de servicio aprovisionadas y usadas en un día determinado.</span><span class="sxs-lookup"><span data-stu-id="51b60-600">The number of ServiceBus connections that were provisioned and utilized on a given day.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-601">Información de servicio 2</span><span class="sxs-lookup"><span data-stu-id="51b60-601">Service Info 2</span></span></td>
<td><p><span data-ttu-id="51b60-602">Campo heredado que captura los metadatos específicos del servicio opcionales.</span><span class="sxs-lookup"><span data-stu-id="51b60-602">A legacy field that captures optional service-specific metadata.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="51b60-603">Información adicional</span><span class="sxs-lookup"><span data-stu-id="51b60-603">Additional Info</span></span></td>
<td><p><span data-ttu-id="51b60-604">Cualquier información adicional no incluida en otras columnas.</span><span class="sxs-lookup"><span data-stu-id="51b60-604">Any additional information not covered in other columns.</span></span></p></td>
</tr>

</tbody>
</table>


## <a href="" id="charge_types"></a><span data-ttu-id="51b60-605">Asignación de cargos entre una factura y el archivo de conciliación</span><span class="sxs-lookup"><span data-stu-id="51b60-605">Mapping charges between an invoice and the reconciliation file</span></span>

<span data-ttu-id="51b60-606">La factura proporciona un resumen de los cargos, mientras que el archivo de conciliación proporciona un desglose detallado de las transacciones de elementos de línea, incluidos los tipos de cargo.</span><span class="sxs-lookup"><span data-stu-id="51b60-606">Your invoice provides a summary of charges, while your reconciliation file provides a detailed breakdown of line-item transactions, including charge types.</span></span>

<span data-ttu-id="51b60-607">Para hacer referencias cruzadas de cantidades de cargos entre el archivo de conciliación y la factura, puedes usar las opciones de filtro de Microsoft Excel para filtrar por tipo de cargo en el archivo de conciliación con el fin de asignar los cargos de facturación a un conjunto de desgloses de cargos del archivo de conciliación.</span><span class="sxs-lookup"><span data-stu-id="51b60-607">To cross-reference charge amounts between the invoice and reconciliation file, you can use Microsoft Excel's filter options to filter by charge types on the reconciliation file to map the invoice charges to a set of charge breakdowns on reconciliation file.</span></span>

<span data-ttu-id="51b60-608">Los archivos de conciliación, tanto basados en uso como en licencias, solo muestran cargos y transacciones relacionados con el uso (unidades consumidas y cargos relacionados).</span><span class="sxs-lookup"><span data-stu-id="51b60-608">Reconciliation files, both usage- and license-based, only show usage related transactions and charges (units consumed and related charges).</span></span> <span data-ttu-id="51b60-609">No se muestran en el archivo de conciliación los créditos, los descuentos o los reembolsos que aparecen en la factura como "ajustes".</span><span class="sxs-lookup"><span data-stu-id="51b60-609">One off credits, discounts or refunds which appear on the invoice as “Adjustments" are not shown in the reconciliation file.</span></span>

<span data-ttu-id="51b60-610">La siguiente tabla muestra las asignaciones entre una sección de factura y los tipos de cargo asociados que es posible que se muestren en los archivos de conciliación.</span><span class="sxs-lookup"><span data-stu-id="51b60-610">The table below shows the mappings between an invoice section and associated charge types that might show up on the reconciliation files.</span></span> 

<table>
<tbody>
<tr>
<td>
<p><span data-ttu-id="51b60-611"><strong>Descripción del cargo de la factura</strong></span><span class="sxs-lookup"><span data-stu-id="51b60-611"><strong>Invoice charge description</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-612"><strong>Descripción del cargo del archivo de conciliación (columna ChargeType)</strong></span><span class="sxs-lookup"><span data-stu-id="51b60-612"><strong>Reconciliation file charge description (ChargeType column)</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-613"><strong>¿Qué es este cargo?</strong></span><span class="sxs-lookup"><span data-stu-id="51b60-613"><strong>What is this charge?</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-614"><strong>Cómo asignar estos ChargeTypes a la factura?</strong></span><span class="sxs-lookup"><span data-stu-id="51b60-614"><strong>How do I map these ChargeTypes to the invoice?</strong></span></span></p>
</td>
</tr>
<tr>
<td rowspan="10">
<p><span data-ttu-id="51b60-615"><strong>Cargos basados en licencias</strong></span><span class="sxs-lookup"><span data-stu-id="51b60-615"><strong>License-based charges</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-616">Tarifa de activación</span><span class="sxs-lookup"><span data-stu-id="51b60-616">Activation fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-617">El importe cobrado al cliente cuando usa la suscripción después de adquirirla</span><span class="sxs-lookup"><span data-stu-id="51b60-617">The amount charged to the customer when they use the subscription after purchasing it</span></span></p>
</td>
<td rowspan="10">
<p><span data-ttu-id="51b60-618">Desde el archivo basado en licencia, suma la columna <strong>Amount</strong>.</span><span class="sxs-lookup"><span data-stu-id="51b60-618">From license-based file, sum the <strong>Amount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="51b60-619">Cuota de cancelación</span><span class="sxs-lookup"><span data-stu-id="51b60-619">Cancel fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-620">Cargos prorrateados reembolsados al cliente al cambiar los puestos asociados</span><span class="sxs-lookup"><span data-stu-id="51b60-620">Prorated charges refunded to the customer when associated seats are changed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="51b60-621">Tarifa de ciclo</span><span class="sxs-lookup"><span data-stu-id="51b60-621">Cycle fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-622">Cargos periódicos de una suscripción</span><span class="sxs-lookup"><span data-stu-id="51b60-622">Periodic charges for a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="51b60-623">Prorrateo de instancia de ciclo</span><span class="sxs-lookup"><span data-stu-id="51b60-623">Cycle instance prorate</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-624">Cargos prorrateados evaluados del cliente al cambiar los puestos asociados</span><span class="sxs-lookup"><span data-stu-id="51b60-624">Prorated charges assessed from the customer when associated seats are changed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="51b60-625">Tarifas prorrateadas al cancelar</span><span class="sxs-lookup"><span data-stu-id="51b60-625">Prorate fees when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-626">Reembolso prorrateado de la parte no usada del servicio tras la cancelación</span><span class="sxs-lookup"><span data-stu-id="51b60-626">Prorated refund for unused portion of service upon cancellation</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="51b60-627">Tarifas prorrateadas al comprar</span><span class="sxs-lookup"><span data-stu-id="51b60-627">Prorate fees when purchase</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-628">El tipo de cargo de una suscripción cuando se usa la facturación anual</span><span class="sxs-lookup"><span data-stu-id="51b60-628">The charge type for a subscription when using annual billing</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="51b60-629">Tarifa de compra</span><span class="sxs-lookup"><span data-stu-id="51b60-629">Purchase fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-630">El tipo de cargo de una suscripción cuando se usa la facturación mensual</span><span class="sxs-lookup"><span data-stu-id="51b60-630">The charge type for a subscription when using monthly billing</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="51b60-631">Tarifa prorrateada al renovar</span><span class="sxs-lookup"><span data-stu-id="51b60-631">Prorate fee when renew</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-632">Tarifas prorrateadas tras la renovación de la suscripción</span><span class="sxs-lookup"><span data-stu-id="51b60-632">Prorated fees upon subscription renewal</span></span></p>
</td>
</tr>
<tr>

<td>
<p><span data-ttu-id="51b60-633">Tarifa de renovación</span><span class="sxs-lookup"><span data-stu-id="51b60-633">Renew fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-634">Cargo por renovar una suscripción</span><span class="sxs-lookup"><span data-stu-id="51b60-634">Charge for renewing a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="51b60-635">Tarifas prorrateadas al activar</span><span class="sxs-lookup"><span data-stu-id="51b60-635">Prorate fees when activate</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-636">Tarifas prorrateadas desde la activación hasta el final del período de facturación</span><span class="sxs-lookup"><span data-stu-id="51b60-636">Prorated fees from activation until end of billing period</span></span></p>
</td>
</tr>



<tr>
<td rowspan="5">
<p><span data-ttu-id="51b60-637"><strong>Cargos por única vez</strong></span><span class="sxs-lookup"><span data-stu-id="51b60-637"><strong>One-time Charges</strong></span></span></p>

</td>
<td>
<p><span data-ttu-id="51b60-638">Nuevo</span><span class="sxs-lookup"><span data-stu-id="51b60-638">New</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-639">Se usa cuando se crea una nueva compra</span><span class="sxs-lookup"><span data-stu-id="51b60-639">Used when a new purchase is created</span></span></p>
</td>

<p></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="51b60-640">addQuantity</span><span class="sxs-lookup"><span data-stu-id="51b60-640">addQuantity</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-641">Se usa tanto en el reembolso de la compra original como en la nueva cantidad después del aumento</span><span class="sxs-lookup"><span data-stu-id="51b60-641">Used in both the refund of the original purchase and the new quantity after increase</span></span></p>
</td>
</tr>

</tr>
<tr>
<td>
<p><span data-ttu-id="51b60-642">removeQuantity</span><span class="sxs-lookup"><span data-stu-id="51b60-642">removeQuantity</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-643">Se usa tanto en el reembolso de la compra original como en la nueva cantidad después de la disminución.</span><span class="sxs-lookup"><span data-stu-id="51b60-643">Used in both the refund of the original purchase and the new quantity after decrease</span></span></p>
</td>
</tr>

</tr>
<tr>
<td>
<p><span data-ttu-id="51b60-644">Cancelar</span><span class="sxs-lookup"><span data-stu-id="51b60-644">Cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-645">Se usa cuando se cancela una suscripción</span><span class="sxs-lookup"><span data-stu-id="51b60-645">Used when a subscription is cancelled</span></span></p>
</td>
</tr>

</tr>
<tr>
<td>
<p><span data-ttu-id="51b60-646">Conversión</span><span class="sxs-lookup"><span data-stu-id="51b60-646">Convert</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-647">Se usa cuando se actualiza una licencia pero el número de puestos permanece inalterado.</span><span class="sxs-lookup"><span data-stu-id="51b60-647">Used when a license is upgraded but the number of seats remains unchanged</span></span></p>
</td>
</tr>

<tr>
<td rowspan="2">
<p><span data-ttu-id="51b60-648"><strong>Cargos de uso</strong></span><span class="sxs-lookup"><span data-stu-id="51b60-648"><strong>Usage Charges</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-649">Evaluar la tarifa de uso al cancelar</span><span class="sxs-lookup"><span data-stu-id="51b60-649">Assess usage fee when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-650">Tarifa de uso de acceso tras la cancelación por uso impagado durante el período de facturación actual</span><span class="sxs-lookup"><span data-stu-id="51b60-650">Access usage fee upon cancellation for unpaid usage during the current billing period</span></span></p>
</td>
<td rowspan="2">
<p><span data-ttu-id="51b60-651">Desde el archivo basado en uso, suma la columna <strong>PretaxCharges</strong>.</span><span class="sxs-lookup"><span data-stu-id="51b60-651">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="51b60-652">Evaluar la tarifa de uso para el ciclo actual</span><span class="sxs-lookup"><span data-stu-id="51b60-652">Assess usage fee for current cycle</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-653">tarifa de uso de acceso para el período de facturación actual</span><span class="sxs-lookup"><span data-stu-id="51b60-653">Access usage fee for the current billing period</span></span></p>
</td>
</tr>

<tr>
<td>
<p><span data-ttu-id="51b60-654"><strong>Plaza</strong></span><span class="sxs-lookup"><span data-stu-id="51b60-654"><strong>Credits</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-655">Desplazamiento de un elemento de línea</span><span class="sxs-lookup"><span data-stu-id="51b60-655">Offset a line item</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-656">Reembolso parcial o total de un elemento de línea, incluidos impuestos</span><span class="sxs-lookup"><span data-stu-id="51b60-656">Partial or whole refund to a line item, including taxes</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-657">Desde el archivo basado en licencia, suma la columna <strong>TotalForCustomer</strong>.</span><span class="sxs-lookup"><span data-stu-id="51b60-657">From license-based file, sum the <strong>TotalForCustomer</strong> column</span></span></p>
<p><span data-ttu-id="51b60-658">Desde el archivo basado en uso, suma la columna <strong>PostTaxTotal</strong>.</span><span class="sxs-lookup"><span data-stu-id="51b60-658">From usage-based file, sum the <strong>PostTaxTotal</strong> column</span></span></p>
</td>
</tr>
<tr>
<td rowspan="4">
<p><span data-ttu-id="51b60-659"><strong>Descuentos basados en el uso</strong></span><span class="sxs-lookup"><span data-stu-id="51b60-659"><strong>Usage-based discounts</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-660">Descuento de activación</span><span class="sxs-lookup"><span data-stu-id="51b60-660">Activation discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-661">Descuento que se aplica cuando se activa la suscripción</span><span class="sxs-lookup"><span data-stu-id="51b60-661">Discount applied when subscription activated</span></span></p>
</td>

<td rowspan="4">
<p><span data-ttu-id="51b60-662">Desde el archivo basado en uso, suma la columna <strong>PretaxCharges</strong>.</span><span class="sxs-lookup"><span data-stu-id="51b60-662">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="51b60-663">Descuento de ciclo</span><span class="sxs-lookup"><span data-stu-id="51b60-663">Cycle discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-664">Descuento que se aplica en cargos periódicos</span><span class="sxs-lookup"><span data-stu-id="51b60-664">Discount applied on periodic charges</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="51b60-665">Descuento de renovación</span><span class="sxs-lookup"><span data-stu-id="51b60-665">Renew discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-666">Descuento que se aplica cuando se renueva la suscripción</span><span class="sxs-lookup"><span data-stu-id="51b60-666">Discount applied when subscription renewed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="51b60-667">Descuento de cancelación</span><span class="sxs-lookup"><span data-stu-id="51b60-667">Cancel discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-668">Cargos que se aplican cuando se cancelan los descuentos</span><span class="sxs-lookup"><span data-stu-id="51b60-668">Charges applied when discounts cancelled</span></span></p>
</td>
</tr>


<tr>
<td>
<p><span data-ttu-id="51b60-669"><strong>Descuentos basados en licencias</strong></span><span class="sxs-lookup"><span data-stu-id="51b60-669"><strong>License-based discounts</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-670"><em>Se puede aplicar a varios tipos de cargos</em></span><span class="sxs-lookup"><span data-stu-id="51b60-670"><em>May be applied to multiple charge types</em></span></span></p>
</td>
<td>
<p></p>
</td>
<td>
<p><span data-ttu-id="51b60-671">Desde el archivo basado en licencia, suma la columna <strong>TotalOtherDiscount</strong>.</span><span class="sxs-lookup"><span data-stu-id="51b60-671">From license-based file, sum the <strong>TotalOtherDiscount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="51b60-672"><strong>Impuestos</strong>&nbsp;o&nbsp;<strong>IVA</strong></span><span class="sxs-lookup"><span data-stu-id="51b60-672"><strong>Taxes</strong>&nbsp;or&nbsp;<strong>VAT</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-673"><em>Se puede aplicar a varios tipos de cargos</em></span><span class="sxs-lookup"><span data-stu-id="51b60-673"><em>May be applied to multiple charge types</em></span></span></p>
<p><span data-ttu-id="51b60-674"><em>Excepción: &quot;Offset un elemento de línea &quot; ya incluye los impuestos. Consulte créditos, arriba.</em></span><span class="sxs-lookup"><span data-stu-id="51b60-674"><em>Exception: &quot;Offset a line item&quot; already includes taxes. See Credits, above.</em></span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-675">Impuestos o impuesto de valor añadido (IVA)</span><span class="sxs-lookup"><span data-stu-id="51b60-675">Taxes or value-added taxes (VAT)</span></span></p>
</td>
<td>
<p><span data-ttu-id="51b60-676">Desde el archivo basado en licencia, suma la columna <strong>Tax</strong>.</span><span class="sxs-lookup"><span data-stu-id="51b60-676">From license-based file, sum the <strong>Tax</strong> column</span></span></p>
<p><span data-ttu-id="51b60-677">Desde el archivo basado en uso, suma la columna <strong>TaxAmount</strong>.</span><span class="sxs-lookup"><span data-stu-id="51b60-677">From usage-based file, sum the <strong>TaxAmount</strong> column</span></span></p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
