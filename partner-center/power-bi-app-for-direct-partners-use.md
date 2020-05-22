---
title: Usar el análisis del centro de partners para Power BI
ms.topic: article
ms.date: 05/19/2020
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Obtenga información sobre cómo ver los datos empresariales con la aplicación de análisis del centro de partners para Power BI (para asociados directos en CSP).
fwlink: https://go.microsoft.com/fwlink/?linkid=852581
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: medium
ms.custom: SEOMAY.20
ms.openlocfilehash: 684ddb00a0497e01fc0fff318000c4b17dd0ea53
ms.sourcegitcommit: 2a980b50cf177753c15ebfd7770e14cf6d486cf7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/22/2020
ms.locfileid: "83795860"
---
# <a name="view-your-business-data-with-the-partner-center-analytics-app-for-microsoft-power-bi"></a><span data-ttu-id="5ce99-103">Vea los datos empresariales con la aplicación de análisis del centro de partners para Microsoft Power BI</span><span class="sxs-lookup"><span data-stu-id="5ce99-103">View your business data with the Partner Center Analytics app for Microsoft Power BI</span></span>

<span data-ttu-id="5ce99-104">**Se aplica a**</span><span class="sxs-lookup"><span data-stu-id="5ce99-104">**Applies to**</span></span>

- <span data-ttu-id="5ce99-105">Centro de partners</span><span class="sxs-lookup"><span data-stu-id="5ce99-105">Partner Center</span></span>

<span data-ttu-id="5ce99-106">**Roles adecuados**</span><span class="sxs-lookup"><span data-stu-id="5ce99-106">**Appropriate roles**</span></span>

- <span data-ttu-id="5ce99-107">Administrador global</span><span class="sxs-lookup"><span data-stu-id="5ce99-107">Global admin</span></span>
- <span data-ttu-id="5ce99-108">Administrador de usuarios</span><span class="sxs-lookup"><span data-stu-id="5ce99-108">User admin</span></span>
- <span data-ttu-id="5ce99-109">Agente de ventas</span><span class="sxs-lookup"><span data-stu-id="5ce99-109">Sales agent</span></span>
- <span data-ttu-id="5ce99-110">Agente de administrador</span><span class="sxs-lookup"><span data-stu-id="5ce99-110">Admin agent</span></span>

## <a name="view-your-business-data"></a><span data-ttu-id="5ce99-111">Visualización de los datos empresariales</span><span class="sxs-lookup"><span data-stu-id="5ce99-111">View your business data</span></span>

<span data-ttu-id="5ce99-112">Obtenga una representación visual de los datos empresariales con la aplicación del centro de partners para Power BI, entre las que se incluyen:</span><span class="sxs-lookup"><span data-stu-id="5ce99-112">Get a visual representation of your business data with the Partner Center Analytics app for Power BI, including:</span></span>

- <span data-ttu-id="5ce99-113">Crecimiento de la base de clientes, las suscripciones y las licencias</span><span class="sxs-lookup"><span data-stu-id="5ce99-113">Growth of your customer base, subscriptions, and licenses</span></span>

- <span data-ttu-id="5ce99-114">El uso que se hace de productos de Office 365, Microsoft Dynamics y Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="5ce99-114">Usage of Office 365, Microsoft Dynamics, and Microsoft Azure products</span></span>

- <span data-ttu-id="5ce99-115">Las unidades de consumo diarias de cada recurso limitado en cada suscripción de Azure durante los últimos 60 días</span><span class="sxs-lookup"><span data-stu-id="5ce99-115">Daily consumption units for each metered resource in each Azure subscription for the last 60 days</span></span>

- <span data-ttu-id="5ce99-116">Costo estimado (basado en la última carta de tarifa)</span><span class="sxs-lookup"><span data-stu-id="5ce99-116">Estimated cost (based on latest rate card)</span></span>

- <span data-ttu-id="5ce99-117">Capacidad de exportar conjuntos de valores y crear informes personalizados, incluidos por cliente.</span><span class="sxs-lookup"><span data-stu-id="5ce99-117">Ability to export datasets and create custom reports, including per customer.</span></span>

### <a name="about-the-partner-center-analytics-app-preview-release"></a><span data-ttu-id="5ce99-118">Acerca de la versión preliminar de la aplicación de análisis de Partner Center</span><span class="sxs-lookup"><span data-stu-id="5ce99-118">About the Partner Center Analytics app preview release</span></span>

- <span data-ttu-id="5ce99-119">Esta aplicación es para asociados directos solo en el programa proveedor de soluciones en la nube.</span><span class="sxs-lookup"><span data-stu-id="5ce99-119">This app is for direct partners in the Cloud Solution Provider program only.</span></span> <span data-ttu-id="5ce99-120">Otros asociados de CSP (por ejemplo, los revendedores indirectos) no podrán iniciar sesión.</span><span class="sxs-lookup"><span data-stu-id="5ce99-120">Other partners in CSP (indirect resellers, for example) will not be able to sign in.</span></span>

- <span data-ttu-id="5ce99-121">Los costos estimados son los datos de facturación y facturación previas a los impuestos y no son legalmente vinculantes.</span><span class="sxs-lookup"><span data-stu-id="5ce99-121">Any estimated costs are pre-tax billing / invoice data, and are not legally binding.</span></span> <span data-ttu-id="5ce99-122">Los costos estimados están pensados para usarse solo para información de datos.</span><span class="sxs-lookup"><span data-stu-id="5ce99-122">Estimated costs are meant to be used for data insights only.</span></span>

- <span data-ttu-id="5ce99-123">La información del cliente se basa en las suscripciones.</span><span class="sxs-lookup"><span data-stu-id="5ce99-123">Customer information is based on subscriptions.</span></span> <span data-ttu-id="5ce99-124">Los clientes que hayan creado recientemente cuentas para, pero que aún no tienen suscripciones, no se incluyen en los recuentos.</span><span class="sxs-lookup"><span data-stu-id="5ce99-124">Any customers that you've recently created accounts for, but who do not yet have subscriptions, are not included in counts.</span></span>

- <span data-ttu-id="5ce99-125">El costo estimado se basa en la tarjeta de tarifas más reciente, que se basa en los precios de CSP.</span><span class="sxs-lookup"><span data-stu-id="5ce99-125">Estimated cost is based on latest rate card, which is based on CSP pricing.</span></span>

- <span data-ttu-id="5ce99-126">Los días son días del calendario.</span><span class="sxs-lookup"><span data-stu-id="5ce99-126">Days are calendar days.</span></span>

### <a name="business-insights-report"></a><span data-ttu-id="5ce99-127">Informe de Business Insights</span><span class="sxs-lookup"><span data-stu-id="5ce99-127">Business Insights report</span></span>

- <span data-ttu-id="5ce99-128">**Inquilinos de cliente**: el número de distintos inquilinos de Azure ad de clientes que han adquirido suscripciones.</span><span class="sxs-lookup"><span data-stu-id="5ce99-128">**Customer tenants**: Number of distinct Azure AD tenants of customers that have purchased subscriptions</span></span>

- <span data-ttu-id="5ce99-129">**Nuevo (últimos 30 días)**: nuevos clientes que compran al menos una suscripción en los últimos 30 días</span><span class="sxs-lookup"><span data-stu-id="5ce99-129">**New (last 30 days)**: New customers purchasing at least one subscription in last 30 days</span></span>

- <span data-ttu-id="5ce99-130">**Renovación (últimos 30 días)**: clientes sin ninguna suscripción "activa", "en período de gracia" o "deshabilitado"</span><span class="sxs-lookup"><span data-stu-id="5ce99-130">**Churn (last 30 days)**: Customers without any “active", “in grace" or “disabled" subscriptions</span></span>

- <span data-ttu-id="5ce99-131">**Nuevo (últimas 24 horas)**: nuevos clientes que compran al menos una suscripción en las últimas 24 horas</span><span class="sxs-lookup"><span data-stu-id="5ce99-131">**New (last 24 hours)**: New customers purchasing at least one subscription in last 24 hours</span></span>

- <span data-ttu-id="5ce99-132">**Costo mensual estimado en los últimos 12 meses**: tendencia de mes a mes del importe de dólar estimado de la factura anterior a los impuestos que se suma mensualmente durante el período de los últimos 12 meses</span><span class="sxs-lookup"><span data-stu-id="5ce99-132">**Estimated monthly cost over last 12 months**: Month over month trend of estimated pre-tax invoice dollar amount aggregated monthly over the period of last 12 months</span></span>

- <span data-ttu-id="5ce99-133">**Costo estimado por producto en los últimos 12 meses**: productos vendidos ordenados por importe en dólares estimado de la factura de impuestos previos agregada en el período de los últimos 12 meses.</span><span class="sxs-lookup"><span data-stu-id="5ce99-133">**Estimated cost by product over last 12 months**: Products sold sorted by estimated pre-tax invoice dollar amount aggregated over the period of last 12 months.</span></span> <span data-ttu-id="5ce99-134">Este estado indica los principales productos que aportan más ingresos.</span><span class="sxs-lookup"><span data-stu-id="5ce99-134">This status indicates top products bringing most revenue.</span></span>

- <span data-ttu-id="5ce99-135">**Clientes de más de 12 meses**: tendencia de mes a mes de nuevos clientes y renovación de clientes agregados mensualmente durante el período de los últimos 12 meses</span><span class="sxs-lookup"><span data-stu-id="5ce99-135">**Customers over last 12 months**: Month over month trend of new customers and churn customers aggregated monthly over the period of last 12 months</span></span>

- <span data-ttu-id="5ce99-136">**Costo estimado por cliente durante los últimos 12 meses**: clientes ordenados por importe de dólar estimado de factura previa de impuestos en el período de los últimos 12 meses.</span><span class="sxs-lookup"><span data-stu-id="5ce99-136">**Estimated cost by customer over last 12 months**: Customers sorted by estimated pre-tax invoice dollar amount aggregated over the period of last 12 months.</span></span> <span data-ttu-id="5ce99-137">Este estado indica que los clientes principales aportan más ingresos.</span><span class="sxs-lookup"><span data-stu-id="5ce99-137">This status indicates top customers bringing most revenue.</span></span>

- <span data-ttu-id="5ce99-138">**Recuento de clientes por producto**: productos vendidos ordenados por clientes asociados.</span><span class="sxs-lookup"><span data-stu-id="5ce99-138">**Customer count by product**: Products sold sorted by associated customers.</span></span> <span data-ttu-id="5ce99-139">Este estado indica los principales productos que se venden a la mayoría de los clientes.</span><span class="sxs-lookup"><span data-stu-id="5ce99-139">This status indicates top products sold to most customers.</span></span>

### <a name="subscription-insights-report"></a><span data-ttu-id="5ce99-140">Informe de información de suscripción</span><span class="sxs-lookup"><span data-stu-id="5ce99-140">Subscription Insights report</span></span>

- <span data-ttu-id="5ce99-141">**Estado**de la suscripción:</span><span class="sxs-lookup"><span data-stu-id="5ce99-141">**Subscription status**:</span></span>

- <span data-ttu-id="5ce99-142">Active: suscripciones que pertenecen a un estado "activo" o "en período de gracia"</span><span class="sxs-lookup"><span data-stu-id="5ce99-142">Active: Subscriptions belonging to either “active" or “in grace" state</span></span>

  - <span data-ttu-id="5ce99-143">Suspendido: suscripciones que pertenecen al estado "deshabilitado"</span><span class="sxs-lookup"><span data-stu-id="5ce99-143">Suspended: Subscriptions belonging to “disabled" state</span></span>

  - <span data-ttu-id="5ce99-144">Desaprovisionado: suscripciones que pertenecen al estado "desaprovisionado" o "expirado"</span><span class="sxs-lookup"><span data-stu-id="5ce99-144">De-provisioned: Subscriptions belonging to “de-provisioned" or “expired" status</span></span>

- <span data-ttu-id="5ce99-145">**Estado de expiración**:</span><span class="sxs-lookup"><span data-stu-id="5ce99-145">**Expiry status**:</span></span>

  - <span data-ttu-id="5ce99-146">Expired: suscripciones que ya han expirado (donde la fecha de finalización de la suscripción está en el pasado)</span><span class="sxs-lookup"><span data-stu-id="5ce99-146">Expired: Subscriptions that have already expired (where subscription end date is in past)</span></span>

  - <span data-ttu-id="5ce99-147">Expiración después de 30 días: suscripciones que expirarán después de 30 días (donde la fecha de finalización de la suscripción es posterior a los 30 días)</span><span class="sxs-lookup"><span data-stu-id="5ce99-147">Expiring after 30 days: Subscriptions that will expire after 30 days (where subscription end date is after next 30 days)</span></span>

  - <span data-ttu-id="5ce99-148">Expiración en 30 días: suscripciones que expirarán en los próximos 30 días (donde la fecha de finalización de la suscripción está entre hoy y los próximos 30 días)</span><span class="sxs-lookup"><span data-stu-id="5ce99-148">Expiring in 30 days: Subscriptions that will expire within next 30 days (where subscription end date is between today and next 30 days)</span></span>

- <span data-ttu-id="5ce99-149">**Total de suscripciones**: suscripciones en estado "activo", "en período de gracia" o "deshabilitado"</span><span class="sxs-lookup"><span data-stu-id="5ce99-149">**Total subscriptions**: Subscriptions in “active," “in grace" or “disabled" status</span></span>

- <span data-ttu-id="5ce99-150">**Nuevo (últimos 30 días)**: nuevas suscripciones compradas por los clientes en los últimos 30 días</span><span class="sxs-lookup"><span data-stu-id="5ce99-150">**New (last 30 days)**: New subscriptions purchased by customers within last 30 days</span></span>

- <span data-ttu-id="5ce99-151">**Nuevo (últimas 24 horas)**: nuevas suscripciones adquiridas por los clientes en las últimas 24 horas</span><span class="sxs-lookup"><span data-stu-id="5ce99-151">**New (last 24 hours)**: New subscriptions purchased by customers within last 24 hours</span></span>

- <span data-ttu-id="5ce99-152">**Expiración en 30 días**: suscripciones que expirarán en los próximos 30 días</span><span class="sxs-lookup"><span data-stu-id="5ce99-152">**Expiring in 30 days**: Subscriptions that will expire within next 30 days</span></span>

- <span data-ttu-id="5ce99-153">**Renovación (últimos 30 días)**: las suscripciones que se han desaprovisionado o suspendido (deshabilitado) en los últimos 30 días</span><span class="sxs-lookup"><span data-stu-id="5ce99-153">**Churn (last 30 days)**: Subscriptions that have been de-provisioned or Suspended (disabled) within last 30 days</span></span>

- <span data-ttu-id="5ce99-154">**Distribución por tipos de suscripción**:% distribución de suscripciones totales por licencia y tipo de suscripción basado en el uso</span><span class="sxs-lookup"><span data-stu-id="5ce99-154">**Distribution by subscription types**: % distribution of total subscriptions by License based and usage-based subscription type</span></span>

- <span data-ttu-id="5ce99-155">**Número de suscripciones activas por producto**: productos vendidos ordenados por recuento de suscripciones activas</span><span class="sxs-lookup"><span data-stu-id="5ce99-155">**Active subscription count by product**: Products sold sorted by active subscriptions count</span></span>

- <span data-ttu-id="5ce99-156">**Suscripciones en los últimos 12 meses**: tendencia de mes a mes de nuevas suscripciones y suscripciones de renovación agregadas mensualmente durante el período de los últimos 12 meses</span><span class="sxs-lookup"><span data-stu-id="5ce99-156">**Subscriptions over last 12 months**: Month over month trend of new subscriptions and churn subscriptions aggregated monthly over the period of last 12 months</span></span>

- <span data-ttu-id="5ce99-157">**Detalles**de la suscripción del cliente: vista detallada de los clientes, las suscripciones y las ofertas</span><span class="sxs-lookup"><span data-stu-id="5ce99-157">**Customer subscription details**: Detailed view of the customers, subscriptions, and offers</span></span>

### <a name="license-insights-report"></a><span data-ttu-id="5ce99-158">Informe de información de licencias:</span><span class="sxs-lookup"><span data-stu-id="5ce99-158">License Insights report:</span></span>

- <span data-ttu-id="5ce99-159">**Total de licencias**: número total de licencias agregadas en todas las suscripciones basadas en licencias</span><span class="sxs-lookup"><span data-stu-id="5ce99-159">**Total licenses**: Total number of licenses aggregated across all license-based subscriptions</span></span>

- <span data-ttu-id="5ce99-160">**Nuevo (últimos 30 días)**: adición de licencias en los últimos 30 días</span><span class="sxs-lookup"><span data-stu-id="5ce99-160">**New (last 30 days)**: License addition within last 30 days</span></span>

- <span data-ttu-id="5ce99-161">**Renovación (últimos 30 días)**: reducción de la licencia en los últimos 30 días</span><span class="sxs-lookup"><span data-stu-id="5ce99-161">**Churn (last 30 days)**: License reduction within last 30 days</span></span>

- <span data-ttu-id="5ce99-162">**Nuevo (últimas 24 horas)**: adición de licencias en las últimas 24 horas</span><span class="sxs-lookup"><span data-stu-id="5ce99-162">**New (last 24 hours)**: License addition within last 24 hours</span></span>

- <span data-ttu-id="5ce99-163">**Licencias en los últimos 90 días**: tendencia de mes a mes de adiciones y reducciones de licencias agregadas mensualmente durante el período de los últimos 90 días</span><span class="sxs-lookup"><span data-stu-id="5ce99-163">**Licenses over last 90 days**: Month over month trend of license additions and reductions aggregated monthly over the period of last 90 days</span></span>

- <span data-ttu-id="5ce99-164">**Recuento de licencias activas por producto**: productos vendidos ordenados por recuento de licencias activas</span><span class="sxs-lookup"><span data-stu-id="5ce99-164">**Active license count by product**: Products sold sorted by active license count</span></span>

- <span data-ttu-id="5ce99-165">**Recuento de licencias activas por cliente**: clientes ordenados por recuento de licencias activas</span><span class="sxs-lookup"><span data-stu-id="5ce99-165">**Active license count by customer**: Customers sorted by active license count</span></span>

- <span data-ttu-id="5ce99-166">**Detalles de evento de licencia de cliente en los últimos 90 días**: vista detallada de los clientes, las suscripciones y los eventos de suscripción, incluida la fecha del evento, el nombre del evento, la cantidad y el cambio en la cantidad.</span><span class="sxs-lookup"><span data-stu-id="5ce99-166">**Customer license event details over last 90 days**: Detailed view of the customers, subscriptions, and subscription events including event date, event name, quantity, and change in quantity.</span></span>

### <a name="licenses-usage-report"></a><span data-ttu-id="5ce99-167">Informe de uso de licencias:</span><span class="sxs-lookup"><span data-stu-id="5ce99-167">Licenses Usage report:</span></span>

- <span data-ttu-id="5ce99-168">**Licencias asignadas por producto**: productos vendidos ordenados por número de asignación de licencias</span><span class="sxs-lookup"><span data-stu-id="5ce99-168">**Licenses assigned by product**: Products sold sorted by license assignment count</span></span>

- <span data-ttu-id="5ce99-169">**Licencias en uso por producto**: productos vendidos ordenados por recuento de uso de licencias</span><span class="sxs-lookup"><span data-stu-id="5ce99-169">**Licenses in use by product**: Products sold sorted by license usage count</span></span>

- <span data-ttu-id="5ce99-170">**Distribución de clientes con licencias asignadas**:% distribución de los clientes totales rotos en cubos del 20% según la asignación de licencias%</span><span class="sxs-lookup"><span data-stu-id="5ce99-170">**Customer distribution of licenses assigned**: % distribution of total customers broken in buckets of 20% range by license assignment %</span></span>

- <span data-ttu-id="5ce99-171">**Distribución del cliente de licencias en uso**:% distribución de los clientes totales rotos en cubos del 20% por uso de licencias%</span><span class="sxs-lookup"><span data-stu-id="5ce99-171">**Customer distribution of licenses in use**: % distribution of total customers broken in buckets of 20% range by license usage %</span></span>

- <span data-ttu-id="5ce99-172">**Licencias asignadas por el cliente**: vista detallada de licencias vendidas y licencias asignadas por clientes y productos</span><span class="sxs-lookup"><span data-stu-id="5ce99-172">**Licenses assigned by customer**: Detailed view of licenses sold and licenses assigned by customers and products</span></span>

- <span data-ttu-id="5ce99-173">**Licencias en uso por el cliente**: vista detallada de licencias vendidas y licencias en uso por clientes y productos</span><span class="sxs-lookup"><span data-stu-id="5ce99-173">**Licenses in use by customer**: Detailed view of licenses sold and licenses in use by customers and products</span></span>

### <a name="azure-insights-report"></a><span data-ttu-id="5ce99-174">Informe de Azure Insights:</span><span class="sxs-lookup"><span data-stu-id="5ce99-174">Azure Insights report:</span></span>

- <span data-ttu-id="5ce99-175">**Clientes basados en el uso durante los últimos 12 meses**: tendencia de mes a mes de nuevos clientes basados en el uso y de clientes basados en el uso renovados que se han agregado mensualmente durante el período de los últimos 12 meses</span><span class="sxs-lookup"><span data-stu-id="5ce99-175">**Usage-based customers over last 12 months**: Month over month trend of new usage-based customers and churned usage-based customers aggregated monthly over the period of last 12 months</span></span>

- <span data-ttu-id="5ce99-176">**Suscripciones basadas en el uso en los últimos 12 meses**: tendencia de mes a mes de nuevas suscripciones basadas en el uso y suscripciones basadas en el uso renovadas que se agregan mensualmente durante el período de los últimos 12 meses</span><span class="sxs-lookup"><span data-stu-id="5ce99-176">**Usage-based subscriptions over last 12 months**: Month over month trend of new usage-based subscriptions and churned usage-based subscriptions aggregated monthly over the period of last 12 months</span></span>

- <span data-ttu-id="5ce99-177">**Costo estimado de uso por cliente durante los últimos 60 días**: clientes basados en el uso ordenados por importe de dólar estimado de factura previa de impuestos en el período de los últimos 60 días.</span><span class="sxs-lookup"><span data-stu-id="5ce99-177">**Estimated cost of usage by customer over last 60 days**: Usage-based customers sorted by estimated pre-tax invoice dollar amount aggregated over the period of last 60 days.</span></span> <span data-ttu-id="5ce99-178">Este estado indica que los clientes principales basados en el uso aportan la mayor parte de los ingresos</span><span class="sxs-lookup"><span data-stu-id="5ce99-178">This status indicates top usage-based customers bringing most revenue</span></span>

- <span data-ttu-id="5ce99-179">**Costo estimado de uso por Categoría en los últimos 60 días**: categorías de medida de las suscripciones basadas en el uso ordenadas por importe de dólar estimado de la factura de impuestos previos agregada en el período de los últimos 60 días.</span><span class="sxs-lookup"><span data-stu-id="5ce99-179">**Estimated cost of usage by category over last 60 days**: Meter categories of usage-based subscriptions sorted by estimated pre-tax invoice dollar amount aggregated over the period of last 60 days.</span></span>

- <span data-ttu-id="5ce99-180">**Costo estimado de uso por suscripción en los últimos 60 días**: las suscripciones basadas en el uso por importe en dólares estimado de la factura de impuestos previos sumadas en el período de los últimos 60 días.</span><span class="sxs-lookup"><span data-stu-id="5ce99-180">**Estimated cost of usage by subscription over last 60 days**: Usage-based subscriptions by estimated pre-tax invoice dollar amount aggregated over the period of last 60 days.</span></span>

- <span data-ttu-id="5ce99-181">**Costo de uso estimado del cliente por presupuesto de gasto**: clientes ordenados por porcentaje de su presupuesto de gasto de uso actual que supera el umbral (100%).</span><span class="sxs-lookup"><span data-stu-id="5ce99-181">**Customer estimated usage cost by spending budget**: Customers sorted by percentage of their current usage spending budget exceeding threshold (100%).</span></span>

### <a name="azure-resource-usage-report"></a><span data-ttu-id="5ce99-182">Informe de uso de recursos de Azure:</span><span class="sxs-lookup"><span data-stu-id="5ce99-182">Azure Resource Usage report:</span></span>

- <span data-ttu-id="5ce99-183">**Uso de recursos de Azure por día para el período seleccionado**: unidades de consumo diarias para cada recurso medido en cada suscripción basada en el uso para el período seleccionado en los últimos 60 días.</span><span class="sxs-lookup"><span data-stu-id="5ce99-183">**Usage of Azure resources by day for selected period**: Daily consumption units for each metered resource in each usage-based subscription for selected period within the last 60 days.</span></span>

- <span data-ttu-id="5ce99-184">**Costo de uso estimado de los recursos de Azure para el período seleccionado**: costo estimado basado en la última tarjeta de frecuencia para cada recurso medido en cada suscripción basada en el uso para el período seleccionado en los últimos 60 días.</span><span class="sxs-lookup"><span data-stu-id="5ce99-184">**Estimated usage cost of Azure resources for selected period**: Estimated cost based on latest rate card for each metered resource in each usage-based subscription for selected period within the last 60 days.</span></span> 

## <a name="next-steps"></a><span data-ttu-id="5ce99-185">Pasos siguientes</span><span class="sxs-lookup"><span data-stu-id="5ce99-185">Next steps</span></span>

- [<span data-ttu-id="5ce99-186">Información general de la aplicación de análisis del centro de partners para Power BI</span><span class="sxs-lookup"><span data-stu-id="5ce99-186">Partner Center Analytics for Power BI app overview</span></span>](power-bi-app-for-direct-partners.md)

- [<span data-ttu-id="5ce99-187">Instalación y versión preliminar de la Aplicación de análisis del Centro de partners para Microsoft Power BI</span><span class="sxs-lookup"><span data-stu-id="5ce99-187">Install and preview the Partner Center Analytics app for Microsoft Power BI</span></span>](power-bi-app-for-direct-partners-install.md)
