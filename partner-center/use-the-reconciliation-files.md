---
title: Usar los archivos de conciliación | Centro de Partners
ms.topic: article
ms.date: 11/21/2019
description: Use los archivos de conciliación para comprender las vistas detalladas de elementos de línea de los cargos del centro de Partners.
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
ms.assetid: FA6A6FCB-2597-44E7-93F8-8D1DD35D52EA
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: medium
ms.openlocfilehash: 6bb65718159019c9ae47aa384524d9d52043d39b
ms.sourcegitcommit: 1c3d3b95135e1daad5ba5585a090e84ab0b97594
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/22/2019
ms.locfileid: "74384803"
---
# <a name="use-your-reconciliation-files"></a><span data-ttu-id="fad67-103">Usar los archivos de conciliación</span><span class="sxs-lookup"><span data-stu-id="fad67-103">Use your reconciliation files</span></span>

<span data-ttu-id="fad67-104">Se aplica a:</span><span class="sxs-lookup"><span data-stu-id="fad67-104">Applies to:</span></span>

- <span data-ttu-id="fad67-105">Centro de partners</span><span class="sxs-lookup"><span data-stu-id="fad67-105">Partner Center</span></span>
- <span data-ttu-id="fad67-106">Centro de partners para Microsoft Cloud for US Government</span><span class="sxs-lookup"><span data-stu-id="fad67-106">Partner Center for Microsoft Cloud for US Government</span></span>

<span data-ttu-id="fad67-107">Puede descargar los archivos de conciliación del centro de partners para obtener una vista detallada de los elementos de línea de cada cargo en un ciclo de facturación.</span><span class="sxs-lookup"><span data-stu-id="fad67-107">You can download your reconciliation files from Partner Center for a detailed, line-item view of each charge in a billing cycle.</span></span> <span data-ttu-id="fad67-108">Los detalles de los elementos de línea incluyen los cargos de las suscripciones de cada cliente y eventos detallados (por ejemplo, una adición de puestos a mediados de puestos a una suscripción).</span><span class="sxs-lookup"><span data-stu-id="fad67-108">Line-item details include charges for each customer's subscriptions, and detailed events (such as a mid-term addition of seats to a subscription).</span></span>

<span data-ttu-id="fad67-109">Roles adecuados:</span><span class="sxs-lookup"><span data-stu-id="fad67-109">Appropriate roles:</span></span>

- <span data-ttu-id="fad67-110">Administrador de facturación</span><span class="sxs-lookup"><span data-stu-id="fad67-110">Billing admin</span></span>
- <span data-ttu-id="fad67-111">Administrador global</span><span class="sxs-lookup"><span data-stu-id="fad67-111">Global admin</span></span>

<span data-ttu-id="fad67-112">Para obtener información sobre cómo leer la **factura**, consulte [leer su](read-your-bill.md)factura.</span><span class="sxs-lookup"><span data-stu-id="fad67-112">For information on how to read your **invoice**, see [Read your bill](read-your-bill.md).</span></span>

## <a name="understand-reconciliation-file-fields"></a><span data-ttu-id="fad67-113">Descripción de los campos de archivo de conciliación</span><span class="sxs-lookup"><span data-stu-id="fad67-113">Understand reconciliation file fields</span></span>

- [<span data-ttu-id="fad67-114">Campos de archivos de conciliación basados en licencias</span><span class="sxs-lookup"><span data-stu-id="fad67-114">License-based reconciliation file fields</span></span>](license-based-recon-files.md)
- [<span data-ttu-id="fad67-115">Campos de archivos de conciliación basados en el uso</span><span class="sxs-lookup"><span data-stu-id="fad67-115">Usage-based reconciliation file fields</span></span>](usage-based-recon-files.md)
- [<span data-ttu-id="fad67-116">Campos de archivo de conciliación único y periódico</span><span class="sxs-lookup"><span data-stu-id="fad67-116">One-time and recurring reconciliation file fields</span></span>](one-time-recurring-recon-files.md)
- [<span data-ttu-id="fad67-117">Campos de archivo de conciliación de uso con clasificación diaria</span><span class="sxs-lookup"><span data-stu-id="fad67-117">Daily-rated usage reconciliation file fields</span></span>](daily-rated-usage-recon-files.md)

## <a name="understand-charge-types-in-reconciliation-files"></a><span data-ttu-id="fad67-118">Descripción de los tipos de carga en los archivos de conciliación</span><span class="sxs-lookup"><span data-stu-id="fad67-118">Understand charge types in reconciliation files</span></span>

<span data-ttu-id="fad67-119">Para comprender los tipos de cargos de los archivos de conciliación (la columna **ChargeType** ), vea [reconciliar tipos de cargos de archivo](recon-file-charge-types.md).</span><span class="sxs-lookup"><span data-stu-id="fad67-119">To understand the types of charges in reconciliation files (the **ChargeType** column), see [Reconciliation file charge types](recon-file-charge-types.md).</span></span>

## <a name="fix-formatting-issues"></a><span data-ttu-id="fad67-120">Corregir problemas de formato</span><span class="sxs-lookup"><span data-stu-id="fad67-120">Fix formatting issues</span></span>

<span data-ttu-id="fad67-121">En ocasiones, un archivo de conciliación puede contener problemas de formato.</span><span class="sxs-lookup"><span data-stu-id="fad67-121">Occasionally, a reconciliation file might contain formatting issues.</span></span> <span data-ttu-id="fad67-122">Por ejemplo, este problema podría producirse si no se utiliza la configuración regional en-US.</span><span class="sxs-lookup"><span data-stu-id="fad67-122">For example, this issue might occur if the en-US locale is not used.</span></span>

<span data-ttu-id="fad67-123">Siga estos pasos para corregir los problemas de formato en los archivos de conciliación:</span><span class="sxs-lookup"><span data-stu-id="fad67-123">Follow these steps for fix any formatting issues in your reconciliation files:</span></span>

1. <span data-ttu-id="fad67-124">Abra el archivo de conciliación (en formato. csv) en Microsoft Excel.</span><span class="sxs-lookup"><span data-stu-id="fad67-124">Open the reconciliation file (in .csv format) in Microsoft Excel.</span></span>
2. <span data-ttu-id="fad67-125">Seleccione la primera columna del archivo.</span><span class="sxs-lookup"><span data-stu-id="fad67-125">Select the first column in the file.</span></span>
3. <span data-ttu-id="fad67-126">Abra el **Asistente para convertir texto en columnas**.</span><span class="sxs-lookup"><span data-stu-id="fad67-126">Open the **Convert Text to Columns Wizard**.</span></span> <span data-ttu-id="fad67-127">En la cinta de opciones, seleccione **datos**y, a continuación, seleccione **texto en columnas**.</span><span class="sxs-lookup"><span data-stu-id="fad67-127">On the ribbon, select **Data**, then select **Text to Columns**.</span></span>
4. <span data-ttu-id="fad67-128">En el asistente, seleccione **tipo de archivo delimitado**.</span><span class="sxs-lookup"><span data-stu-id="fad67-128">In the wizard, select **Delimited file type**.</span></span> <span data-ttu-id="fad67-129">A continuación, seleccione **siguiente**.</span><span class="sxs-lookup"><span data-stu-id="fad67-129">Then, select **Next**.</span></span>
5. <span data-ttu-id="fad67-130">En el campo **delimitadores** , seleccione **coma**.</span><span class="sxs-lookup"><span data-stu-id="fad67-130">In the **Delimiters** field, select **Comma**.</span></span> <span data-ttu-id="fad67-131">(Si la **pestaña** ya está seleccionada, puede dejar esta opción seleccionada). A continuación, seleccione **siguiente**.</span><span class="sxs-lookup"><span data-stu-id="fad67-131">(If **Tab** is already selected, you can leave this option selected.) Then, select **Next**.</span></span>
6. <span data-ttu-id="fad67-132">En el campo **formato de datos de columna** , seleccione **Fecha: MDA**.</span><span class="sxs-lookup"><span data-stu-id="fad67-132">In the **Column data format** field, select **Date:MDY**.</span></span> <span data-ttu-id="fad67-133">A continuación, seleccione **siguiente**.</span><span class="sxs-lookup"><span data-stu-id="fad67-133">Then, select **Next**.</span></span>
7. <span data-ttu-id="fad67-134">En el campo **formato de datos de columna** , seleccione **texto** para todas las columnas de importe.</span><span class="sxs-lookup"><span data-stu-id="fad67-134">In the **Column data format** field, select **Text** for all amount columns.</span></span> <span data-ttu-id="fad67-135">A continuación, seleccione **Finalizar**.</span><span class="sxs-lookup"><span data-stu-id="fad67-135">Then, select **Finish**.</span></span>

## <a name="download-reconciliation-files-programmatically"></a><span data-ttu-id="fad67-136">Descargar archivos de conciliación mediante programación</span><span class="sxs-lookup"><span data-stu-id="fad67-136">Download reconciliation files programmatically</span></span>

<span data-ttu-id="fad67-137">Los archivos de conciliación pueden ser muy grandes y a veces son difíciles de descargar.</span><span class="sxs-lookup"><span data-stu-id="fad67-137">Reconciliation files can be very large and are sometimes difficult to download.</span></span> <span data-ttu-id="fad67-138">Para descargar los archivos de conciliación mediante programación, vea [obtener artículos de línea de factura](https://docs.microsoft.com/partner-center/develop/get-invoiceline-items).</span><span class="sxs-lookup"><span data-stu-id="fad67-138">To download reconciliation files programmatically, see [Get invoice line items](https://docs.microsoft.com/partner-center/develop/get-invoiceline-items).</span></span>

## <a name="map-taxes-or-vat"></a><span data-ttu-id="fad67-139">Impuestos de mapa o IVA</span><span class="sxs-lookup"><span data-stu-id="fad67-139">Map taxes or VAT</span></span>

<span data-ttu-id="fad67-140">Para asignar impuestos o impuestos sobre el valor añadido (IVA) a la factura:</span><span class="sxs-lookup"><span data-stu-id="fad67-140">To map Taxes or value-added tax (VAT) to your invoice:</span></span>

- <span data-ttu-id="fad67-141">Sume la columna **Tax** del archivo basado en licencia.</span><span class="sxs-lookup"><span data-stu-id="fad67-141">Sum the **Tax** column from the license-based file.</span></span>
- <span data-ttu-id="fad67-142">Sume la columna **TaxAmount** del archivo basado en el uso.</span><span class="sxs-lookup"><span data-stu-id="fad67-142">Sum the **TaxAmount** column from the usage-based file.</span></span>

## <a name="itemize-reconciliation-files-by-partner"></a><span data-ttu-id="fad67-143">Elemento de conciliación de elementos por asociado</span><span class="sxs-lookup"><span data-stu-id="fad67-143">Itemize reconciliation files by partner</span></span>

<span data-ttu-id="fad67-144">Los asociados en el **modelo indirecto** pueden utilizar estos campos adicionales en los archivos de conciliación basados en la licencia y en el uso para que los revendan los archivos.</span><span class="sxs-lookup"><span data-stu-id="fad67-144">Partners in the **indirect model** can use these additional fields in both license-based and usage-based reconciliation files to itemize the files by reseller.</span></span>

| <span data-ttu-id="fad67-145">Id. de MPN</span><span class="sxs-lookup"><span data-stu-id="fad67-145">MPN ID</span></span> | <span data-ttu-id="fad67-146">Descripción</span><span class="sxs-lookup"><span data-stu-id="fad67-146">Description</span></span> |
| ------ | ----------- |
| <span data-ttu-id="fad67-147">Id. de MPN</span><span class="sxs-lookup"><span data-stu-id="fad67-147">MPN ID</span></span> | <span data-ttu-id="fad67-148">Identificador Microsoft Partner Network (MPN) del asociado del proveedor de soluciones en la nube (CSP) (directo o indirecto).</span><span class="sxs-lookup"><span data-stu-id="fad67-148">The Microsoft Partner Network (MPN) identifier of the Cloud Solution Provider (CSP) partner (direct or indirect).</span></span> |
| [<span data-ttu-id="fad67-149">ID. de revendedor MPN</span><span class="sxs-lookup"><span data-stu-id="fad67-149">Reseller MPN ID</span></span>](#reseller-mpn-id) | <span data-ttu-id="fad67-150">[Identificador de MPN del distribuidor de registro de la suscripción](#reseller-mpn-id).</span><span class="sxs-lookup"><span data-stu-id="fad67-150">The [MPN identifier of the reseller of record for the subscription](#reseller-mpn-id).</span></span> <span data-ttu-id="fad67-151">Este campo corresponde al ID. de distribuidor que se muestra para la suscripción específica del centro de Partners.</span><span class="sxs-lookup"><span data-stu-id="fad67-151">This field corresponds to the reseller ID listed for the specific subscription in Partner Center.</span></span> <span data-ttu-id="fad67-152">Solo aparece en los archivos de conciliación de partners en el modelo indirecto.</span><span class="sxs-lookup"><span data-stu-id="fad67-152">Only appears on reconciliation files for partners in the indirect model.</span></span> |

### <a name="reseller-mpn-id"></a><span data-ttu-id="fad67-153">Id. de MPN del revendedor</span><span class="sxs-lookup"><span data-stu-id="fad67-153">Reseller MPN ID</span></span>

<span data-ttu-id="fad67-154">Si un asociado de CSP vendió la suscripción directamente al cliente, su **identificador de MPN** aparece dos veces, como el **identificador de MPN** y el ID. de **MPN del reseller**.</span><span class="sxs-lookup"><span data-stu-id="fad67-154">If a CSP partner sold the subscription directly to the customer, their **MPN ID** is listed twice, as both the **MPN ID** and the **Reseller MPN ID**.</span></span>

<span data-ttu-id="fad67-155">Si un asociado de CSP tiene un revendedor sin **identificador de MPN**, este valor se establece en el **identificador de MPN** del asociado en su lugar.</span><span class="sxs-lookup"><span data-stu-id="fad67-155">If a CSP partner has a reseller with no **MPN ID**, this value is set to the partner's **MPN ID** instead.</span></span>

<span data-ttu-id="fad67-156">Si el asociado de CSP quita un ID. de **revendedor de MPN**, este valor se establecerá en *-1*.</span><span class="sxs-lookup"><span data-stu-id="fad67-156">If the CSP partner removes a **Reseller MPN ID**, this value will be set to *-1*.</span></span>

<span data-ttu-id="fad67-157">Para ver o actualizar el **ID. de revendedor MPN**:</span><span class="sxs-lookup"><span data-stu-id="fad67-157">To view or update the **Reseller MPN ID**:</span></span>

1. <span data-ttu-id="fad67-158">Inicia sesión en el Centro de partners.</span><span class="sxs-lookup"><span data-stu-id="fad67-158">Sign in to Partner Center.</span></span>
2. <span data-ttu-id="fad67-159">En el menú del Centro de partners, selecciona **Clientes**.</span><span class="sxs-lookup"><span data-stu-id="fad67-159">In the Partner Center menu, select **Customers**.</span></span>
3. <span data-ttu-id="fad67-160">Elige el cliente de la lista.</span><span class="sxs-lookup"><span data-stu-id="fad67-160">Choose the customer from the list.</span></span>
4. <span data-ttu-id="fad67-161">En el menú del cliente, seleccione **suscripciones**.</span><span class="sxs-lookup"><span data-stu-id="fad67-161">In the customer menu, select **Subscriptions**.</span></span>
5. <span data-ttu-id="fad67-162">Elija la suscripción de la lista.</span><span class="sxs-lookup"><span data-stu-id="fad67-162">Choose the subscription from the list.</span></span>
6. <span data-ttu-id="fad67-163">Selecciona **Actualizar** para cambiar el valor de **Revendedor (id. de MPN)** .</span><span class="sxs-lookup"><span data-stu-id="fad67-163">Select **update** to change the **Reseller (MPN ID)**.</span></span>
