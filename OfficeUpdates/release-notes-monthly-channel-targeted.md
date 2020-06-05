---
title: Las compilaciones de notas de la versión del canal mensual (dirigido)
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 'Proporciona a los participantes del modo anticipado de Insider Lento la lista más reciente de las nuevas características, correcciones o problemas conocidos principales '
ms.openlocfilehash: 41dba1efa79735aafd74b318fd49c7c3211736e3
ms.sourcegitcommit: e9b127c7dfd80f3beb3c9aa9dadfb9e7f442c58c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/04/2020
ms.locfileid: "44563680"
---
# <a name="release-notes-for-office-monthly-channel-targeted"></a><span data-ttu-id="b02b8-103">Las compilaciones de notas de la versión del canal mensual de Office (dirigido)</span><span class="sxs-lookup"><span data-stu-id="b02b8-103">Release Notes for Office Monthly Channel (Targeted)</span></span>

<span data-ttu-id="b02b8-104">En este artículo hay notas de la versión para las compilaciones del canal mensual (dirigido) de las versiones de escritorio de Word, Excel, PowerPoint, Outlook, Access y Project para Windows.</span><span class="sxs-lookup"><span data-stu-id="b02b8-104">This article contains release notes for Monthly Channel (Targeted) builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="b02b8-105">Todas las semanas se incluyen las nuevas características, correcciones importantes y los problemas principales de mayor interés para usted.</span><span class="sxs-lookup"><span data-stu-id="b02b8-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="b02b8-106">Tenga en cuenta que a menudo publicamos características (y a veces incluso correcciones) para el Canal mensual (dirigido) durante un período de tiempo.</span><span class="sxs-lookup"><span data-stu-id="b02b8-106">Note that we often roll out features (and sometimes even fixes) to Monthly Channel (Targeted) over a period of time.</span></span> <span data-ttu-id="b02b8-107">Esto nos permite asegurarnos de que todo funciona correctamente antes de publicar la característica para un público más amplio.</span><span class="sxs-lookup"><span data-stu-id="b02b8-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="b02b8-108">Por tanto, si a continuación no ve algo descrito, no se preocupe, lo recibirá con el tiempo.</span><span class="sxs-lookup"><span data-stu-id="b02b8-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="b02b8-109">Estamos realizando algunos cambios en los canales de actualización de las Aplicaciones de Microsoft 365, incluida la adición de un nuevo canal de actualización (canal empresarial mensual) y el cambio de los nombres de los canales de actualización existentes.</span><span class="sxs-lookup"><span data-stu-id="b02b8-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="b02b8-110">[Lea este artículo](https://go.microsoft.com/fwlink/p/?linkid=2127441) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="b02b8-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="b02b8-111">La fecha de publicación de las notas de versión pueden no coincidir con la fecha real de lanzamiento de la compilación.</span><span class="sxs-lookup"><span data-stu-id="b02b8-111">The release notes publication date may not match the actual build release date.</span></span>


[//]: # (NO ELIMINAR)

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

## <a name="version-2005-june-04"></a><span data-ttu-id="b02b8-115">Versión 2005:4 de junio</span><span class="sxs-lookup"><span data-stu-id="b02b8-115">Version 2005: June 04</span></span>
<span data-ttu-id="b02b8-116">*Versión 2005 (compilación 12827,20320)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-116">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="b02b8-118">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="b02b8-118">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="b02b8-119">Access</span><span class="sxs-lookup"><span data-stu-id="b02b8-119">Access</span></span>

- <span data-ttu-id="b02b8-120">**Manténgase al día con las horas. El tipo de datos extendidos de fecha y hora tiene mejor precisión.:** introducción de un tipo de datos nuevo y mejorado.</span><span class="sxs-lookup"><span data-stu-id="b02b8-120">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="b02b8-121">Para mejorar la compatibilidad de la sintaxis con SQL y aumentar la precisión y el nivel de detalle en los registros que incluyen fechas y horas, estamos implementando el tipo de datos DateTime2 en Access.</span><span class="sxs-lookup"><span data-stu-id="b02b8-121">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="b02b8-122">Este tipo de datos de fecha & hora adicionales incluirá un intervalo de fechas mayor (de 0001-01-01 a 9999-12-31), con precisión de tiempo mayor (nanosegundos, en lugar de segundos) que podrá proporcionar y realizar cálculos en.</span><span class="sxs-lookup"><span data-stu-id="b02b8-122">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="b02b8-123">Para habilitarla, seleccione nuevo campo > fecha & tiempo ampliado.</span><span class="sxs-lookup"><span data-stu-id="b02b8-123">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="b02b8-124">Más información</span><span class="sxs-lookup"><span data-stu-id="b02b8-124">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="b02b8-125">Excel</span><span class="sxs-lookup"><span data-stu-id="b02b8-125">Excel</span></span>

- <span data-ttu-id="b02b8-126">**Cree tablas dinámicas de conjuntos de elementos en Power BI en Excel:** Puede crear tablas dinámicas en Excel que estén conectadas a los conjuntos de valores almacenados en Power BI con unos pocos clics.</span><span class="sxs-lookup"><span data-stu-id="b02b8-126">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="b02b8-127">Esto le permite sacar el máximo partido de las tablas dinámicas y de Power BI.</span><span class="sxs-lookup"><span data-stu-id="b02b8-127"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="b02b8-128">Calcule, resume y analice los datos con tablas dinámicas de los datasets de Power BI protegidos.</span><span class="sxs-lookup"><span data-stu-id="b02b8-128">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="b02b8-129">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-129">Outlook</span></span>

- <span data-ttu-id="b02b8-130">**Opción para volver a abrir rápidamente los elementos de la sesión anterior de Outlook:** Se ha agregado una opción para volver a abrir rápidamente los elementos de una sesión anterior de Outlook.</span><span class="sxs-lookup"><span data-stu-id="b02b8-130">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="b02b8-133">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="b02b8-133">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="b02b8-134">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b02b8-134">PowerPoint</span></span>

- <span data-ttu-id="b02b8-135">Esto soluciona un bloqueo cuando los usuarios tienen comentarios modernos y heredados en un archivo, lo que desencadena una actualización en los comentarios.</span><span class="sxs-lookup"><span data-stu-id="b02b8-135">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b02b8-136">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="b02b8-136">Office Suite</span></span>

- <span data-ttu-id="b02b8-137">Se ha resuelto el problema de tasa de error de ValidateInstall estableciendo la validación de la instalación del complemento de Bing en true de forma predeterminada y considerando que MSI Return Success como una instalación correcta.</span><span class="sxs-lookup"><span data-stu-id="b02b8-137">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2005-may-29"></a><span data-ttu-id="b02b8-139">Versión 2005:29 de mayo</span><span class="sxs-lookup"><span data-stu-id="b02b8-139">Version 2005: May 29</span></span>
<span data-ttu-id="b02b8-140">*Versión 2005 (compilación 12827,20268)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-140">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="b02b8-142">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="b02b8-142">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="b02b8-143">Excel</span><span class="sxs-lookup"><span data-stu-id="b02b8-143">Excel</span></span>

- <span data-ttu-id="b02b8-144">**Vista de hoja:** Ordenar o filtrar mientras colaboran con otras personas en el escritorio de Excel.</span><span class="sxs-lookup"><span data-stu-id="b02b8-144">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="b02b8-145">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-145">Outlook</span></span>

- <span data-ttu-id="b02b8-146">**Botones adicionales agregados a las notificaciones del sistema de Outlook:** Ahora aparecen botones de acción rápidos en las notificaciones del sistema de Outlook al ejecutar Outlook en Windows 10.</span><span class="sxs-lookup"><span data-stu-id="b02b8-146">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="b02b8-149">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="b02b8-149">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="b02b8-150">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-150">Outlook</span></span>

- <span data-ttu-id="b02b8-151">Se ha solucionado un problema que provocaba que los usuarios de versiones de Windows 10 Server consultaran la advertencia Estado de antivirus: no válido.</span><span class="sxs-lookup"><span data-stu-id="b02b8-151">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="b02b8-152">Esta versión de Windows es compatible con la detección antivirus, pero no se ha encontrado ningún antivirus a pesar de haber instalado correctamente anti-virus.</span><span class="sxs-lookup"><span data-stu-id="b02b8-152">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b02b8-153">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="b02b8-153">Office Suite</span></span>

- <span data-ttu-id="b02b8-154">El host de Office se bloqueaba en Windows, cuando se activa un complemento mientras la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth se establece en cero.</span><span class="sxs-lookup"><span data-stu-id="b02b8-154">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="b02b8-155">Este cambio solucionará este problema.</span><span class="sxs-lookup"><span data-stu-id="b02b8-155">This change would fix this issue.</span></span>


[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2005-may-21"></a><span data-ttu-id="b02b8-157">Versión 2005:21 de mayo</span><span class="sxs-lookup"><span data-stu-id="b02b8-157">Version 2005: May 21</span></span>
<span data-ttu-id="b02b8-158">*Versión 2005 (compilación 12827,20210)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-158">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="b02b8-160">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="b02b8-160">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b02b8-161">Excel</span><span class="sxs-lookup"><span data-stu-id="b02b8-161">Excel</span></span>

- <span data-ttu-id="b02b8-162">**Obtener datos de la organización de Power BI con tipos de datos de Excel:** Puede insertar datos de la organización con los tipos de datos de Excel.</span><span class="sxs-lookup"><span data-stu-id="b02b8-162">**Get Organization Data from Power BI using Excel Data Types:** You can insert data from your Organization using Excel Data Types.</span></span> <span data-ttu-id="b02b8-163">Convierta una celda en el libro y obtenga información adicional y actualice los datos en cualquier momento que necesite.</span><span class="sxs-lookup"><span data-stu-id="b02b8-163">Convert a cell in your workbook and get additional information, and refresh the data anytime you need!</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="b02b8-166">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="b02b8-166">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b02b8-167">Excel</span><span class="sxs-lookup"><span data-stu-id="b02b8-167">Excel</span></span>

- <span data-ttu-id="b02b8-168">Se ha corregido un problema por el que Excel podía no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía a través de Teams.</span><span class="sxs-lookup"><span data-stu-id="b02b8-168">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="b02b8-169">En algunos casos, al hacer clic en un hipervínculo en un lugar dentro del mismo libro hará que se oculte el libro.</span><span class="sxs-lookup"><span data-stu-id="b02b8-169">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="b02b8-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-170">Outlook</span></span>

- <span data-ttu-id="b02b8-171">Se ha solucionado un problema con el evento de auditoría CLP para la etiqueta de respuesta/reenvío.</span><span class="sxs-lookup"><span data-stu-id="b02b8-171">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="b02b8-172">Se ha solucionado un problema que provocaba que los usuarios experimentaran un bloqueo al enviar comentarios desde una notificación de administrador.</span><span class="sxs-lookup"><span data-stu-id="b02b8-172">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2005-may-14"></a><span data-ttu-id="b02b8-174">Versión 2005:14 de mayo</span><span class="sxs-lookup"><span data-stu-id="b02b8-174">Version 2005: May 14</span></span>
<span data-ttu-id="b02b8-175">*Versión 2005 (compilación 12827,20160)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-175">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="b02b8-177">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="b02b8-177">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b02b8-178">Excel</span><span class="sxs-lookup"><span data-stu-id="b02b8-178">Excel</span></span>

- <span data-ttu-id="b02b8-179">**Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.</span><span class="sxs-lookup"><span data-stu-id="b02b8-179">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b02b8-180">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b02b8-180">PowerPoint</span></span>

- <span data-ttu-id="b02b8-181">**No es necesario hacer clic: sus miniauriculares tienen que cubrir lo siguiente:** Usar sus Surface Earbuds para controlar sus presentaciones de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="b02b8-181">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="b02b8-182">Importante: Debe emparejar sus Surface Earbuds en la aplicación Surface Audio para Windows 10 para poder usar gestos para controlar las presentaciones.</span><span class="sxs-lookup"><span data-stu-id="b02b8-182">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="b02b8-183">Aquí encontrará instrucciones para empezar a usar la aplicación Surface Audio en Windows 10.</span><span class="sxs-lookup"><span data-stu-id="b02b8-183">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="b02b8-184">Más información</span><span class="sxs-lookup"><span data-stu-id="b02b8-184">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="b02b8-185">**Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.</span><span class="sxs-lookup"><span data-stu-id="b02b8-185">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="b02b8-186">Word</span><span class="sxs-lookup"><span data-stu-id="b02b8-186">Word</span></span>

- <span data-ttu-id="b02b8-187">**Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.</span><span class="sxs-lookup"><span data-stu-id="b02b8-187">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="b02b8-190">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="b02b8-190">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="b02b8-191">Excel</span><span class="sxs-lookup"><span data-stu-id="b02b8-191">Excel</span></span>

- <span data-ttu-id="b02b8-192">Se aumentó el tamaño de los controles de edición de referencia de celda en el cuadro de diálogo Barras de error personalizadas utilizado con gráficos.</span><span class="sxs-lookup"><span data-stu-id="b02b8-192">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="b02b8-193">Se ha corregido un problema por el que las tablas de datos de los gráficos podían representar incorrectamente los valores de un eje de fechas.</span><span class="sxs-lookup"><span data-stu-id="b02b8-193">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="b02b8-194">Se ha corregido un problema por el que los saltos de página no se podían deshabilitar después de ir al diseño de página o la vista previa de salto de página</span><span class="sxs-lookup"><span data-stu-id="b02b8-194">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="b02b8-195">Se ha corregido un problema por el que los estilos de línea de los gráficos podían perderse tras ocultar y mostrar columnas con datos de series.</span><span class="sxs-lookup"><span data-stu-id="b02b8-195">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="b02b8-196">Se ha corregido un problema que provocaba que la inserción de una columna en una lista filtrada tardara más de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="b02b8-196">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="b02b8-197">Corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.</span><span class="sxs-lookup"><span data-stu-id="b02b8-197">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="b02b8-198">Se ha corregido un problema por el que el vínculo externo dejaba de funcionar después de volver a abrir el archivo si la ruta de acceso del archivo es demasiado larga.</span><span class="sxs-lookup"><span data-stu-id="b02b8-198">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="b02b8-199">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="b02b8-199">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="b02b8-200">Application.Evaluate (VBA) no funcionaba para funciones definidas por el usuario en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="b02b8-200">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="b02b8-201">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="b02b8-201">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="b02b8-202">Este cambio corrige un problema que hacía que la información de formato condicional (CF) no se guardase correctamente en los archivos XLSB.</span><span class="sxs-lookup"><span data-stu-id="b02b8-202">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="b02b8-203">Este cambio corrige un problema en el que el valor de la línea de tendencia del gráfico R-cuadrado (en el caso de la intersección forzada y) era incorrecto aunque la función de ESTIMACIÓN devuelva el valor correcto.</span><span class="sxs-lookup"><span data-stu-id="b02b8-203">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="b02b8-204">Este cambio arregla un problema en el que no siempre se guardaba el formato de la línea de tendencia de los gráficos personalizados.</span><span class="sxs-lookup"><span data-stu-id="b02b8-204">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="b02b8-205">Puede producirse un bloqueo al intentar enumerar los cambios en una hoja nueva para un libro mediante el modo heredado "libro compartido".</span><span class="sxs-lookup"><span data-stu-id="b02b8-205">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="b02b8-206">Se ha corregido el problema por el que el formato personalizado de un gráfico dinámico podía no guardarse si estaba habilitada la opción "Invertir si es negativo".</span><span class="sxs-lookup"><span data-stu-id="b02b8-206">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="b02b8-207">Se ha corregido un problema por el que el formato personalizado de un único punto de datos de un gráfico dinámico no se guardaba si estaba seleccionada la opción "invertir si es negativo".</span><span class="sxs-lookup"><span data-stu-id="b02b8-207">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="b02b8-208">Este cambio corrige un problema por el que el carácter "@" cargado en un archivo CSV causaba que la cadena tras el carácter "@" se convirtiera en una fórmula.</span><span class="sxs-lookup"><span data-stu-id="b02b8-208">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="b02b8-209">Se ha corregido un problema por el que los valores decimales de la función SECUENCIA no se redondeaban correctamente.</span><span class="sxs-lookup"><span data-stu-id="b02b8-209">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="b02b8-210">OneNote</span><span class="sxs-lookup"><span data-stu-id="b02b8-210">OneNote</span></span>

- <span data-ttu-id="b02b8-211">Corregido un problema en el que los saltos de línea se almacenaban como pestañas verticales.</span><span class="sxs-lookup"><span data-stu-id="b02b8-211">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="b02b8-212">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-212">Outlook</span></span>

- <span data-ttu-id="b02b8-213">Soluciona un problema que hacía que los usuarios no pudieran agregar un grupo de contactos personal como asistente de la reunión.</span><span class="sxs-lookup"><span data-stu-id="b02b8-213">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="b02b8-214">Se ha corregido un problema por el que se deshabilitó el botón clasificar para calendarios de grupo en la cinta de Office.</span><span class="sxs-lookup"><span data-stu-id="b02b8-214">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="b02b8-215">Se ha corregido un problema que provocaba que Outlook se bloqueara al abrir archivos .msg y .oft guardados localmente después de una actualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="b02b8-215">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="b02b8-216">Se ha solucionado un problema por el que los clientes de las empresas con carpetas de grupo no implementadas o que no funcionaban, hacían que Outlook mostrara un mensaje de "no responde".</span><span class="sxs-lookup"><span data-stu-id="b02b8-216">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="b02b8-217">Se ha solucionado un problema que provocaba un safelinks muy largo en el que los usuarios hacían clic en el cliente de escritorio de Outlook para que no se cargaran debido al truncamiento.</span><span class="sxs-lookup"><span data-stu-id="b02b8-217">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="b02b8-218">Se ha corregido un problema por el que las carpetas de Outlook con nombres que contenían caracteres DBCS (conjunto de caracteres de doble byte) desaparecían intermitentemente al sincronizar con el servidor.</span><span class="sxs-lookup"><span data-stu-id="b02b8-218">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="b02b8-219">Esto sucedía si Outlook estaba configurado con una cuenta IMAP y se ejecutaba en un sistema con la configuración regional configurada en japonés.</span><span class="sxs-lookup"><span data-stu-id="b02b8-219">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="b02b8-220">Se ha solucionado un problema que provocaba que las reglas de eliminación creadas para buzones de correo que no son el buzón principal del usuario dejara de ser válidas.</span><span class="sxs-lookup"><span data-stu-id="b02b8-220">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="b02b8-221">Se ha solucionado un problema que provocaba la pérdida de datos adjuntos al reenviar un mensaje cifrado.</span><span class="sxs-lookup"><span data-stu-id="b02b8-221">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="b02b8-222">Se ha solucionado un problema que provocaba que las reuniones de más de 2 meses no mostraran un asunto de la reunión en el Asistente para programación.</span><span class="sxs-lookup"><span data-stu-id="b02b8-222">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="b02b8-223">Se ha corregido un problema que hacía que los usuarios vieran truncado el cuerpo del mensaje al reenviar mensajes HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="b02b8-223">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="b02b8-224">Se agregó la capacidad de aplicar la configuración de firma predeterminada de S/MIME a través de la directiva de grupo.</span><span class="sxs-lookup"><span data-stu-id="b02b8-224">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b02b8-225">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b02b8-225">PowerPoint</span></span>

- <span data-ttu-id="b02b8-226">Se ha corregido un problema por el que el borrador de los comentarios dejaba de estar disponible si un usuario creaba un comentario sin publicarlo, cerraba el panel de comentarios, abría una nueva ventana, se desplazaba por varias diapositivas, cerraba la ventana y volvía a abrir el panel de comentarios en la presentación original.</span><span class="sxs-lookup"><span data-stu-id="b02b8-226">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="b02b8-227">Se ha solucionado un problema por el que al pasar el ratón por encima del símbolo del asterisco (\*) no aparecía el nombre de usuario y la fecha de la última persona que actualizó el documento.</span><span class="sxs-lookup"><span data-stu-id="b02b8-227">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="b02b8-228">Proyecto</span><span class="sxs-lookup"><span data-stu-id="b02b8-228">Project</span></span>

- <span data-ttu-id="b02b8-229">Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se activa un evento ProjectBeforeTaskChange adicional.</span><span class="sxs-lookup"><span data-stu-id="b02b8-229">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="b02b8-230">Se solucionó un problema por el cual Proyect podía bloquearse al cambiar el campo de estado del tablero en un proyecto que conectado a una lista de tareas de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="b02b8-230">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="b02b8-231">Corregido un problema por el que Project podía bloquearse al guardar proyectos creados con versiones anteriores de Project.</span><span class="sxs-lookup"><span data-stu-id="b02b8-231">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="b02b8-232">Se ha corregido un problema por el que, si el proyecto está conectado a Project Web App y el separador decimal es una coma, se produce un error en el método Add en TaskDependencies cuando se agrega lag.</span><span class="sxs-lookup"><span data-stu-id="b02b8-232">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="b02b8-233">Word</span><span class="sxs-lookup"><span data-stu-id="b02b8-233">Word</span></span>

- <span data-ttu-id="b02b8-234">Se ha corregido un problema por el que la inserción de comentarios en un documento en el modo de colaboración no funcionaba en ocasiones.</span><span class="sxs-lookup"><span data-stu-id="b02b8-234">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="b02b8-235">Este cambio corrige un problema por el que la tarjeta de contactos parpadeaba si se hacía clic en la mención @.</span><span class="sxs-lookup"><span data-stu-id="b02b8-235">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="b02b8-236">Al habilitar la opción "Mostrar marcadores" no se mostrarán los marcadores.</span><span class="sxs-lookup"><span data-stu-id="b02b8-236">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="b02b8-237">Este error se ha corregido.</span><span class="sxs-lookup"><span data-stu-id="b02b8-237">This has been fixed.</span></span>

- <span data-ttu-id="b02b8-238">Se ha corregido el problema por el que al cerrar un documento con borrador de comentarios se preguntaba al usuario si deseaba cerrar el documento sin guardar los comentarios del borrador.</span><span class="sxs-lookup"><span data-stu-id="b02b8-238">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="b02b8-239">Al cancelar la solicitud, se cerraba el documento en lugar de quedar abierto.</span><span class="sxs-lookup"><span data-stu-id="b02b8-239">Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="b02b8-240">Se ha corregido un problema en la copia y pegado de títulos.</span><span class="sxs-lookup"><span data-stu-id="b02b8-240">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="b02b8-241">Se ha corregido un problema por el que, al traducir un comentario publicado, se producía un error "no se pudo insertar el texto traducido".</span><span class="sxs-lookup"><span data-stu-id="b02b8-241">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="b02b8-242">Este cambio corrige un problema que provocaba que no se mostrara el texto con hipervínculos si se habilitaba la opción: "Mostrar códigos de campo en lugar de sus valores".</span><span class="sxs-lookup"><span data-stu-id="b02b8-242">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="b02b8-243">En la Vista web o en el lector inmersivo, al hacer clic en una sugerencia se desplazaba a la parte superior incluso aunque ya estuviera a la vista.</span><span class="sxs-lookup"><span data-stu-id="b02b8-243">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="b02b8-244">Este error se ha corregido.</span><span class="sxs-lookup"><span data-stu-id="b02b8-244">This has been fixed.</span></span>

- <span data-ttu-id="b02b8-245">Se ha corregido un problema por el que al intentar guardar un archivo que contenía una macro con un nombre nuevo, este se guardaba con la extensión. docx y el nombre de archivo WRO0004.docx, independientemente de lo que el usuario escribiera, lo que hacía que el archivo no se pudiera volver a usar.</span><span class="sxs-lookup"><span data-stu-id="b02b8-245">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b02b8-246">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="b02b8-246">Office Suite</span></span>

- <span data-ttu-id="b02b8-247">Cuando a un usuario se le concede una directiva que los mueve a Microsoft Teams, aún puede usar el complemento de Outlook para Skype empresarial para programar reuniones.</span><span class="sxs-lookup"><span data-stu-id="b02b8-247">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="b02b8-248">Después de esta actualización, ya no podrá programar reuniones de Skype empresarial después de que el cliente Lea la Directiva, lo que indica que el usuario es solo Microsoft Teams y solo entra en el modo de unirse a la reunión.</span><span class="sxs-lookup"><span data-stu-id="b02b8-248">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="b02b8-249">Además, el complemento de Outlook para Skype empresarial no se activará durante el inicio si ve que el cliente de Skype empresarial está en modo de solo unirse a la reunión.</span><span class="sxs-lookup"><span data-stu-id="b02b8-249">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="b02b8-250">Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.</span><span class="sxs-lookup"><span data-stu-id="b02b8-250">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="b02b8-251">Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.</span><span class="sxs-lookup"><span data-stu-id="b02b8-251">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (NO QUITAR ERRORES DE DETALLES DE CONTENIDO FINAL)

## <a name="version-2004-may-11"></a><span data-ttu-id="b02b8-253">Versión 2004: 11 de mayo</span><span class="sxs-lookup"><span data-stu-id="b02b8-253">Version 2004: May 11</span></span>
<span data-ttu-id="b02b8-254">*Versión 2004 (compilación 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-254">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="b02b8-256">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="b02b8-256">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b02b8-257">Excel</span><span class="sxs-lookup"><span data-stu-id="b02b8-257">Excel</span></span>

- <span data-ttu-id="b02b8-258">**Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.</span><span class="sxs-lookup"><span data-stu-id="b02b8-258">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="b02b8-259">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-259">Outlook</span></span>

- <span data-ttu-id="b02b8-260">**Vínculos mejorados en el correo electrónico:** al incluir un vínculo a un archivo, la dirección URL se reemplaza por el nombre del archivo.</span><span class="sxs-lookup"><span data-stu-id="b02b8-260">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="b02b8-261">Puede cambiar los permisos para que todos los destinatarios tengan acceso.</span><span class="sxs-lookup"><span data-stu-id="b02b8-261">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="b02b8-262">Más información</span><span class="sxs-lookup"><span data-stu-id="b02b8-262">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="b02b8-263">Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span><span class="sxs-lookup"><span data-stu-id="b02b8-263">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="b02b8-264">**Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office. Sus documentos han pasado a ser más elegantes.</span><span class="sxs-lookup"><span data-stu-id="b02b8-264">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b02b8-265">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b02b8-265">PowerPoint</span></span>

- <span data-ttu-id="b02b8-266">**Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.</span><span class="sxs-lookup"><span data-stu-id="b02b8-266">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>  [<span data-ttu-id="b02b8-267">Más información</span><span class="sxs-lookup"><span data-stu-id="b02b8-267">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="b02b8-268">Word</span><span class="sxs-lookup"><span data-stu-id="b02b8-268">Word</span></span>

- <span data-ttu-id="b02b8-269">**Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.</span><span class="sxs-lookup"><span data-stu-id="b02b8-269">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a><span data-ttu-id="b02b8-272">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="b02b8-272">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b02b8-273">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-273">Outlook</span></span>

- <span data-ttu-id="b02b8-274">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al mostrar las notificaciones del sistema.</span><span class="sxs-lookup"><span data-stu-id="b02b8-274">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2004-may-04"></a><span data-ttu-id="b02b8-276">Versión 2004: 4 de mayo</span><span class="sxs-lookup"><span data-stu-id="b02b8-276">Version 2004: May 04</span></span>
<span data-ttu-id="b02b8-277">*Versión 2004 (Compilación 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-277">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="b02b8-279">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="b02b8-279">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b02b8-280">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-280">Outlook</span></span>

- <span data-ttu-id="b02b8-281">**Mejores resultados, en un instante:** actualizamos la experiencia de búsqueda para que sea más inteligente, rápida y fiable que nunca.</span><span class="sxs-lookup"><span data-stu-id="b02b8-281">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="b02b8-282">Más información</span><span class="sxs-lookup"><span data-stu-id="b02b8-282">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="b02b8-283">**Notificación de incidentes para administradores de TI:** se notificará a los administradores globales de espacios empresariales de Microsoft 365 y a los administradores de aplicaciones de Office acerca de los incidentes de Outlook y Exchange de O365 que afectan a sus usuarios con una nueva notificación en el panel derecho en Outlook para Windows.</span><span class="sxs-lookup"><span data-stu-id="b02b8-283">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a><span data-ttu-id="b02b8-286">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="b02b8-286">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="b02b8-287">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="b02b8-287">Office Suite</span></span>

- <span data-ttu-id="b02b8-288">Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.</span><span class="sxs-lookup"><span data-stu-id="b02b8-288">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (NO QUITAR ERRORES DE DETALLES DE CONTENIDO FINAL)

## <a name="version-2004-april-29"></a><span data-ttu-id="b02b8-290">Versión 2004: 29 de abril</span><span class="sxs-lookup"><span data-stu-id="b02b8-290">Version 2004: April 29</span></span>
<span data-ttu-id="b02b8-291">*Versión 2004 (compilación 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-291">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="b02b8-293">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="b02b8-293">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b02b8-294">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-294">Outlook</span></span>

- <span data-ttu-id="b02b8-295">**Protección de datos del grupo:** la etiqueta de confidencialidad que elija al crear un grupo se aplica al correo electrónico del grupo, a los documentos y a los sitios de equipo.</span><span class="sxs-lookup"><span data-stu-id="b02b8-295">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a><span data-ttu-id="b02b8-298">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="b02b8-298">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b02b8-299">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-299">Outlook</span></span>

- <span data-ttu-id="b02b8-300">Corrige un problema que causaba que Outlook se bloqueara en algunas compilaciones de Windows.</span><span class="sxs-lookup"><span data-stu-id="b02b8-300">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2004-april-25"></a><span data-ttu-id="b02b8-302">Versión 2004: 25 de abril</span><span class="sxs-lookup"><span data-stu-id="b02b8-302">Version 2004: April 25</span></span>
<span data-ttu-id="b02b8-303">*Versión 2004 (compilación 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-303">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="b02b8-305">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="b02b8-305">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b02b8-306">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-306">Outlook</span></span>

- <span data-ttu-id="b02b8-307">Se ha corregido un problema que provocaba que Outlook se bloqueara al abrir archivos .msg y .oft guardados localmente después de una actualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="b02b8-307">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="b02b8-308">Project</span><span class="sxs-lookup"><span data-stu-id="b02b8-308">Project</span></span>

- <span data-ttu-id="b02b8-309">Se ha corregido un problema que hace que si está usando Project conectado a Project Web App y el separador decimal es una coma, el método TaskDependencies Add producirá un error al intentar agregar retardo a una dependencia.</span><span class="sxs-lookup"><span data-stu-id="b02b8-309">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b02b8-310">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="b02b8-310">Office Suite</span></span>

- <span data-ttu-id="b02b8-311">Esta corrección resuelve un error que impide restringir el acceso y proteger los archivos con una contraseña de forma simultánea.</span><span class="sxs-lookup"><span data-stu-id="b02b8-311">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (NO ELIMINAR LOS DETALLES DEL CONTENIDO FINAL)

## <a name="version-2004-april-21"></a><span data-ttu-id="b02b8-313">Versión 2004: 21 de abril</span><span class="sxs-lookup"><span data-stu-id="b02b8-313">Version 2004: April 21</span></span>
<span data-ttu-id="b02b8-314">*Versión 2004 (compilación 12730.20182)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-314">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a><span data-ttu-id="b02b8-316">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="b02b8-316">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b02b8-317">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-317">Outlook</span></span>

- <span data-ttu-id="b02b8-318">Corrige un problema que provocaba que el ancho del panel de carpetas cambiara de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="b02b8-318">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="b02b8-319">Corrige un problema que provocaba que los usuarios experimentaran un error al salir de Outlook.</span><span class="sxs-lookup"><span data-stu-id="b02b8-319">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2004-april-15"></a><span data-ttu-id="b02b8-321">Versión 2004: 15 de abril</span><span class="sxs-lookup"><span data-stu-id="b02b8-321">Version 2004: April 15</span></span>
<span data-ttu-id="b02b8-322">*Versión 2004 (compilación 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-322">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="b02b8-324">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="b02b8-324">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b02b8-325">Excel</span><span class="sxs-lookup"><span data-stu-id="b02b8-325">Excel</span></span>

- <span data-ttu-id="b02b8-326">**El soporte para el conector de Facebook va a terminar:** a partir de abril de 2020. Excel ya no admitirá conexiones de datos externos que usen el conector de Facebook.</span><span class="sxs-lookup"><span data-stu-id="b02b8-326">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="b02b8-327">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-327">Outlook</span></span>

- <span data-ttu-id="b02b8-328">\*\*Nueva opción para desactivar las sugerencias de @menciones al escribir correo en Outlook: \*\*¿le resulta el selector de @menciones más molesto que útil?</span><span class="sxs-lookup"><span data-stu-id="b02b8-328">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="b02b8-329">Ahora puede desactivarlo si lo prefiere.</span><span class="sxs-lookup"><span data-stu-id="b02b8-329">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b02b8-330">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b02b8-330">PowerPoint</span></span>

- <span data-ttu-id="b02b8-331">**Sincronice los cambios mientras realiza la presentación:** sincronice los cambios cuando se hagan aunque la presentación esté en el modo de presentación con diapositivas.</span><span class="sxs-lookup"><span data-stu-id="b02b8-331">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="b02b8-332">Word</span><span class="sxs-lookup"><span data-stu-id="b02b8-332">Word</span></span>

- <span data-ttu-id="b02b8-333">**Anote su copia privada:** cree notas escritas a mano privadas realizando una copia privada de un documento compartido.</span><span class="sxs-lookup"><span data-stu-id="b02b8-333">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="b02b8-334">Vaya a Ver > Crear una copia privada para empezar.</span><span class="sxs-lookup"><span data-stu-id="b02b8-334">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="b02b8-337">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="b02b8-337">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b02b8-338">Access</span><span class="sxs-lookup"><span data-stu-id="b02b8-338">Access</span></span>

- <span data-ttu-id="b02b8-339">Se han corregido problema al cambiar el tamaño y actualizar tablas en el panel de tareas.</span><span class="sxs-lookup"><span data-stu-id="b02b8-339">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="b02b8-340">Se ha corregido un problema por el que las versiones internacionales de Access mostraban cadenas en inglés en la interfaz de usuario.</span><span class="sxs-lookup"><span data-stu-id="b02b8-340">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="b02b8-341">Excel</span><span class="sxs-lookup"><span data-stu-id="b02b8-341">Excel</span></span>

- <span data-ttu-id="b02b8-342">Se ha corregido un problema por el que seleccionar un rango de celdas en una hoja daba lugar a la selección de una sola celda.</span><span class="sxs-lookup"><span data-stu-id="b02b8-342">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="b02b8-343">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="b02b8-343">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="b02b8-344">Se ha corregido un problema que hacía que Excel se bloqueara en ciertos casos después de copiar una hoja que contenía una tabla dinámica.</span><span class="sxs-lookup"><span data-stu-id="b02b8-344">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="b02b8-345">Application.Evaluate (VBA) no funcionaba para funciones definidas por el usuario en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="b02b8-345">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="b02b8-346">Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al editar un rango de celdas grande por programación.</span><span class="sxs-lookup"><span data-stu-id="b02b8-346">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="b02b8-347">Se ha corregido un problema de rendimiento al abrir archivos CSV con entornos japoneses.</span><span class="sxs-lookup"><span data-stu-id="b02b8-347">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="b02b8-348">Se ha corregido un problema que provocaba que al insertar una plantilla de gráfico definida por el usuario como predeterminada se guardara como un gráfico de columnas.</span><span class="sxs-lookup"><span data-stu-id="b02b8-348">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="b02b8-349">Se ha corregido un problema por el que las etiquetas de datos en los gráficos se mostraban en blanco cuando las celdas de datos subyacentes no tuvieran un título.</span><span class="sxs-lookup"><span data-stu-id="b02b8-349">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="b02b8-350">Se ha corregido un problema que podía provocar que Excel dejara de responder al reducir el tamaño de un gráfico con algunos rangos de eje x.</span><span class="sxs-lookup"><span data-stu-id="b02b8-350">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="b02b8-351">Se ha corregido un problema por el que, en una hoja de Excel con referencia de celda F1C1 habilitada y en coautoría o compartida, al pasar el ratón por el icono de presencia del usuario no se mostraba la referencia de celda activa en modo F1C1.</span><span class="sxs-lookup"><span data-stu-id="b02b8-351">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="b02b8-352">Este cambio corrige retrasos al procesar imágenes con información de protocolo mal formada o incorrecta.</span><span class="sxs-lookup"><span data-stu-id="b02b8-352">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="b02b8-353">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-353">Outlook</span></span>

- <span data-ttu-id="b02b8-354">Este cambio corrige retrasos al procesar imágenes con información de protocolo mal formada o incorrecta.</span><span class="sxs-lookup"><span data-stu-id="b02b8-354">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="b02b8-355">Este cambio corrige un problema por el que los cambios más recientes en los borradores de correo electrónico no se actualizaban.</span><span class="sxs-lookup"><span data-stu-id="b02b8-355">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="b02b8-356">Se corrigió un problema por el que hacer clic derecho del mouse en un archivo y usar "Enviar a" no funcionaba.</span><span class="sxs-lookup"><span data-stu-id="b02b8-356">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="b02b8-357">Se ha corregido un problema que provocaba que los delegados viesen distintas jerarquías de carpetas en diferentes equipos para los buzones compartidos.</span><span class="sxs-lookup"><span data-stu-id="b02b8-357">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="b02b8-358">Se ha corregido un problema que provocaba que las categorías desapareciesen en ocasiones de los mensajes de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="b02b8-358">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="b02b8-359">Se ha corregido un problema que provocaba que se produjesen errores en la activación de algunos avisos al cambiar la zona horaria en un equipo.</span><span class="sxs-lookup"><span data-stu-id="b02b8-359">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="b02b8-360">Se ha corregido un problema que provocaba que los usuarios experimentasen un error al intentar ver las propiedades de un formulario de la organización.</span><span class="sxs-lookup"><span data-stu-id="b02b8-360">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="b02b8-361">Se corrigió un problema por el que si un usuario tenía una ruta de búsqueda personalizada para la libreta de direcciones, el ámbito de la resolución de nombres de Outlook se limitaba a la ruta personalizada, en lugar de incluir la lista global de direcciones (LGD).</span><span class="sxs-lookup"><span data-stu-id="b02b8-361">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="b02b8-362">Se ha corregido un problema que hacía que el botón "Guardar en la nube" faltara en las Herramientas de datos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="b02b8-362">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="b02b8-363">Se ha corregido un problema que hacía que los usuarios no pudieran agregar una firma al responder a un mensaje administrado con derechos digitales desde una ventana de inspección cuando el usuario no tenía permiso de propietario sobre el mensaje al que se respondía.</span><span class="sxs-lookup"><span data-stu-id="b02b8-363">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="b02b8-364">Se ha corregido un problema que hacía que los usuarios no pudieran agregar archivos adjuntos adicionales desde una ubicación web a una reunión creada previamente.</span><span class="sxs-lookup"><span data-stu-id="b02b8-364">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="b02b8-365">Se ha corregido un problema que hacía que la fecha de "última modificación" de un archivo se actualizara al agregar un archivo adjunto a un correo electrónico o al guardar un archivo adjunto desde un correo arrastrándolo y colocándolo (en lugar de hacerlo a través de un menú).</span><span class="sxs-lookup"><span data-stu-id="b02b8-365">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="b02b8-366">Se ha corregido un problema que hacía que al presionar Entrar en el panel de búsqueda expandido no se iniciara la búsqueda y requería que los usuarios hiciesen clic en el botón de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="b02b8-366">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="b02b8-367">Se ha corregido un problema que hacía que al ordenar los resultados por categorías, en un conjunto de resultados de búsqueda devuelto no se mostraran los colores de la categoría.</span><span class="sxs-lookup"><span data-stu-id="b02b8-367">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="b02b8-368">Se ha corregido un problema por el que la búsqueda no mostraba información sobre los usuarios cuando se había deshabilitado la opción "Mostrar fotografías de usuario cuando estén disponibles".</span><span class="sxs-lookup"><span data-stu-id="b02b8-368">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b02b8-369">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b02b8-369">PowerPoint</span></span>

- <span data-ttu-id="b02b8-370">Este cambio corrige un error que podría causar que los archivos de PowerPoint que contienen emojis fallen al guardarlos.</span><span class="sxs-lookup"><span data-stu-id="b02b8-370">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="b02b8-371">Este cambio corrige un problema en el que es posible que no siempre se muestre el título del gráfico al representar un gráfico de Excel heredado incrustado como objeto OLE en PowerPoint o Word.</span><span class="sxs-lookup"><span data-stu-id="b02b8-371">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="b02b8-372">Se ha corregido un problema por el que al copiar texto de Excel en PowerPoint podía cambiar el formato.</span><span class="sxs-lookup"><span data-stu-id="b02b8-372">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="b02b8-373">Este cambio corrige un problema que provocaba que la búsqueda de caracteres especiales con "Buscar solo palabras completas" no siempre funcionase como se esperaba.</span><span class="sxs-lookup"><span data-stu-id="b02b8-373">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="b02b8-374">Project</span><span class="sxs-lookup"><span data-stu-id="b02b8-374">Project</span></span>

- <span data-ttu-id="b02b8-375">Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.</span><span class="sxs-lookup"><span data-stu-id="b02b8-375">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="b02b8-376">Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="b02b8-376">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="b02b8-377">Se ha corregido un problema que hacía que el evento "ProjectBeforeTaskChange" de las aplicaciones de Visual Basic (VBA) no se activara cuando un usuario hacía clic en el botón "Desactivar" que se encuentra en la cinta de tareas en el grupo de programación.</span><span class="sxs-lookup"><span data-stu-id="b02b8-377">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="b02b8-378">Si establece los detalles de predecesor o sucesor desde una vista de tipo formulario, el evento de las aplicaciones de Visual Basic (VBA) ProjectBeforeTaskChange no siempre captura los cambios.</span><span class="sxs-lookup"><span data-stu-id="b02b8-378">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="b02b8-379">Por ejemplo, si ha eliminado una dependencia y ha hecho clic en Aceptar en el formulario, el evento no se ha desencadenado.</span><span class="sxs-lookup"><span data-stu-id="b02b8-379">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="b02b8-380">Este comportamiento se ha corregido.</span><span class="sxs-lookup"><span data-stu-id="b02b8-380">This behavior has been fixed.</span></span>

- <span data-ttu-id="b02b8-381">Se corrigió un problema por el que los valores más recientes del coste real del trabajo realizado (CRTR) no se mostraba después de realizar un cambio, como un cambio de fecha.</span><span class="sxs-lookup"><span data-stu-id="b02b8-381">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="b02b8-382">Se corrigió un problema por el que al abrir un proyecto con el menú Usados más recientemente se abría el archivo de proyecto con acceso de lectura y escritura.</span><span class="sxs-lookup"><span data-stu-id="b02b8-382">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="b02b8-383">Este cambio corrige un problema por el que si creaba una tarea manual con una fecha y hora de inicio (sin la duración), se mostraba con una hora incorrecta en la escala de tiempo.</span><span class="sxs-lookup"><span data-stu-id="b02b8-383">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="b02b8-384">Se corrigió un problema por el que la impresión de una escala de tiempo con el calendario Hijri saltaba un mes o lo duplicaba en la vista de impresión.</span><span class="sxs-lookup"><span data-stu-id="b02b8-384">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="b02b8-385">Este cambio resuelve un problema por el que trabajar en el Organizador de equipo con objetos de GDI podía provocar la sobreasignación de dichos objetos y crear condiciones de memoria insuficiente.</span><span class="sxs-lookup"><span data-stu-id="b02b8-385">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="b02b8-386">Se ha solucionado un problema por el que si se ejecuta "Lista de valores de campos personalizados GetItem" y no existe una tabla de búsqueda para el campo personalizado, se crea una tabla de búsqueda vacía aunque no debería existir.</span><span class="sxs-lookup"><span data-stu-id="b02b8-386">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="b02b8-387">Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se activa un evento ProjectBeforeTaskChange adicional.</span><span class="sxs-lookup"><span data-stu-id="b02b8-387">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="b02b8-388">Se corrigió un problema por el que el usuario no podía especificar el trabajo previsto con fases temporales al activar la configuración para proteger el trabajo real.</span><span class="sxs-lookup"><span data-stu-id="b02b8-388">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="b02b8-389">Word</span><span class="sxs-lookup"><span data-stu-id="b02b8-389">Word</span></span>

- <span data-ttu-id="b02b8-390">Este cambio corrige un problema que provoca que al colocar el cursor sobre una sugerencia no se resalte la tarjeta.</span><span class="sxs-lookup"><span data-stu-id="b02b8-390">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="b02b8-391">Este cambio corrige un problema con varias páginas seleccionadas en el menú Ver, donde el panel de comentarios podía mostrarse en blanco.</span><span class="sxs-lookup"><span data-stu-id="b02b8-391">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="b02b8-392">Se corrigió un problema por el que se había deshabilitado la función para publicar comentarios.</span><span class="sxs-lookup"><span data-stu-id="b02b8-392">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="b02b8-393">Este cambio corrige un problema que haría que el texto de las formas agrupadas desaparezca temporalmente al usar la herramienta Selección de lazo.</span><span class="sxs-lookup"><span data-stu-id="b02b8-393">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="b02b8-394">Este cambio corrige retrasos al procesar imágenes con información de protocolo mal formada o incorrecta.</span><span class="sxs-lookup"><span data-stu-id="b02b8-394">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="b02b8-395">Este cambio corrige un problema en el que es posible que no siempre se muestre el título del gráfico al representar un gráfico de Excel heredado incrustado como objeto OLE en PowerPoint o Word.</span><span class="sxs-lookup"><span data-stu-id="b02b8-395">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="b02b8-396">Este cambio resuelve un problema en el que el administrador de cuentas no enviaba mensajes, lo que provocaba un error en aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="b02b8-396">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="b02b8-397">Este cambio corrige un problema por el que, en la vista de dos páginas, al crear un comentario, el anclaje del comentario no siempre aparecía.</span><span class="sxs-lookup"><span data-stu-id="b02b8-397">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="b02b8-398">Se ha corregido un problema por el que al escribir o editar un comentario y usar Ctrl + A se seleccionaba texto en el lienzo en lugar de seleccionar texto en la tarjeta del comentario.</span><span class="sxs-lookup"><span data-stu-id="b02b8-398">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="b02b8-399">Se ha corregido un problema que hacía que si un párrafo con un estilo antecesor de un estilo estaba vinculado a una lista, se podía perder la numeración de la lista.</span><span class="sxs-lookup"><span data-stu-id="b02b8-399">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="b02b8-400">Este cambio corrige un problema en el que la tabla de contenido se actualizaba con estilos de título que no estaban presentes en el documento.</span><span class="sxs-lookup"><span data-stu-id="b02b8-400">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="b02b8-401">Se ha corregido un problema por el que la alineación de las palabras de un documento se puede codificar al intentar editar después de imprimir con la impresión rápida.</span><span class="sxs-lookup"><span data-stu-id="b02b8-401">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="b02b8-402">Se ha corregido un problema al combinar dos documentos en uno.</span><span class="sxs-lookup"><span data-stu-id="b02b8-402">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="b02b8-403">Se corrigió un problema por el que las firmas digitales guardadas en documentos de Word se eliminaban al enviar los documentos.</span><span class="sxs-lookup"><span data-stu-id="b02b8-403">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="b02b8-404">Se ha corregido un problema que hacía que el marcado de revisiones que impliquen ecuaciones ocasionase un error al guardar el archivo.</span><span class="sxs-lookup"><span data-stu-id="b02b8-404">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-april-14"></a><span data-ttu-id="b02b8-406">Versión 2003: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="b02b8-406">Version 2003: April 14</span></span>
<span data-ttu-id="b02b8-407">*Versión 2003 (compilación 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-407">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="b02b8-408">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b02b8-408">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

- <span data-ttu-id="b02b8-410">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="b02b8-410">Various bugs and performance fixes.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

## <a name="version-2003-april-09"></a><span data-ttu-id="b02b8-412">Versión 2003: 09 de abril</span><span class="sxs-lookup"><span data-stu-id="b02b8-412">Version 2003: April 09</span></span>
<span data-ttu-id="b02b8-413">*Versión 2003 (compilación 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-413">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="b02b8-415">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="b02b8-415">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b02b8-416">Excel</span><span class="sxs-lookup"><span data-stu-id="b02b8-416">Excel</span></span>

- <span data-ttu-id="b02b8-417">**Selector de contenido de M365 Premium:** de vida a sus documentos.</span><span class="sxs-lookup"><span data-stu-id="b02b8-417">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="b02b8-418">Explore gratis miles de imágenes, iconos y adhesivos [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="b02b8-418">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="b02b8-419">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-419">Outlook</span></span>

- <span data-ttu-id="b02b8-420">**Selector de contenido de M365 Premium:** de vida a sus documentos.</span><span class="sxs-lookup"><span data-stu-id="b02b8-420">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="b02b8-421">Explore gratis miles de imágenes, iconos y adhesivos [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="b02b8-421">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b02b8-422">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b02b8-422">PowerPoint</span></span>

- <span data-ttu-id="b02b8-423">**Selector de contenido de M365 Premium:** de vida a sus documentos.</span><span class="sxs-lookup"><span data-stu-id="b02b8-423">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="b02b8-424">Explore gratis miles de imágenes, iconos y adhesivos [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="b02b8-424">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="b02b8-425">Word</span><span class="sxs-lookup"><span data-stu-id="b02b8-425">Word</span></span>

- <span data-ttu-id="b02b8-426">**Selector de contenido de M365 Premium:** de vida a sus documentos.</span><span class="sxs-lookup"><span data-stu-id="b02b8-426">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="b02b8-427">Explore gratis miles de imágenes, iconos y adhesivos [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="b02b8-427">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)




[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO FINAL)

## <a name="version-2003-april-03"></a><span data-ttu-id="b02b8-431">Versión 2003: 03 de abril</span><span class="sxs-lookup"><span data-stu-id="b02b8-431">Version 2003: April 03</span></span>
<span data-ttu-id="b02b8-432">*Versión 2003 (Compilación 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-432">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a><span data-ttu-id="b02b8-434">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="b02b8-434">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b02b8-435">Excel</span><span class="sxs-lookup"><span data-stu-id="b02b8-435">Excel</span></span>

- <span data-ttu-id="b02b8-436">El uso de la Aplicación VBA.Evaluar no trabajaba para las funciones definidas por el usuario en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="b02b8-436">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="b02b8-437">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-437">Outlook</span></span>

- <span data-ttu-id="b02b8-438">Abordó un problema que causó que los usuarios experimentaran ocasionalmente un choque al usar el botón "X" de su ratón.</span><span class="sxs-lookup"><span data-stu-id="b02b8-438">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="b02b8-439">Project</span><span class="sxs-lookup"><span data-stu-id="b02b8-439">Project</span></span>

- <span data-ttu-id="b02b8-440">Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se dispara un ProyectoAntesdeCambiarTareaEvento extra.</span><span class="sxs-lookup"><span data-stu-id="b02b8-440">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="b02b8-441">Word</span><span class="sxs-lookup"><span data-stu-id="b02b8-441">Word</span></span>

- <span data-ttu-id="b02b8-442">Abordó un problema que causó que los usuarios experimentaran ocasionalmente un choque al usar el botón "X" de su ratón.</span><span class="sxs-lookup"><span data-stu-id="b02b8-442">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-march-31"></a><span data-ttu-id="b02b8-444">Versión 2003: 31 de marzo</span><span class="sxs-lookup"><span data-stu-id="b02b8-444">Version 2003: March 31</span></span>
<span data-ttu-id="b02b8-445">*Versión 2003 (compilación 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-445">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="b02b8-447">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="b02b8-447">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="b02b8-448">Access</span><span class="sxs-lookup"><span data-stu-id="b02b8-448">Access</span></span>

- <span data-ttu-id="b02b8-449">**Panel de tareas "Agregar tablas":** ¡Ya está disponible el acceso al nuevo panel de tareas "Agregar tablas"!</span><span class="sxs-lookup"><span data-stu-id="b02b8-449">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="b02b8-450">Esta característica le permite seleccionar y hacer selección múltiple de las tablas que desea agregar o quitar de forma sencilla en una ventana de consulta, sin tener que desplazarse hasta el cuadro de diálogo "Mostrar tablas" para las consultas y la vista de relación.</span><span class="sxs-lookup"><span data-stu-id="b02b8-450">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="b02b8-451">Esto también incluye una nueva pestaña "vínculos" para mostrar las tablas vinculadas, un cuadro de búsqueda para filtrar la lista actual, el comportamiento de "arrastrar y soltar", ¡y mucho más!</span><span class="sxs-lookup"><span data-stu-id="b02b8-451">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a><span data-ttu-id="b02b8-454">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="b02b8-454">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="b02b8-455">Project</span><span class="sxs-lookup"><span data-stu-id="b02b8-455">Project</span></span>

- <div><span data-ttu-id="b02b8-456"><span style="display:inline !important;">Se corrigió un problema por el que el usuario no podía especificar el trabajo previsto con fases temporales al activar la configuración para proteger el trabajo real.</span></span><span class="sxs-lookup"><span data-stu-id="b02b8-456"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br></div>



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2003-march-25"></a><span data-ttu-id="b02b8-458">Versión 2003: 25 de marzo</span><span class="sxs-lookup"><span data-stu-id="b02b8-458">Version 2003: March 25</span></span>
<span data-ttu-id="b02b8-459">*Versión 2003 (compilación 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-459">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="b02b8-460">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="b02b8-460">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="b02b8-461">Versión 2003: 23 de marzo</span><span class="sxs-lookup"><span data-stu-id="b02b8-461">Version 2003: March 23</span></span>
<span data-ttu-id="b02b8-462">*Versión 2003 (compilación 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-462">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="b02b8-463">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="b02b8-463">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="b02b8-464">Versión 2003: 21 de marzo</span><span class="sxs-lookup"><span data-stu-id="b02b8-464">Version 2003: March 21</span></span>
<span data-ttu-id="b02b8-465">*Versión 2003 (compilación 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-465">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="b02b8-467">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="b02b8-467">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b02b8-468">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-468">Outlook</span></span>

- <span data-ttu-id="b02b8-469">**Unirse a reuniones sin salir de la bandeja de entrada:** no es necesario cambiar al calendario para unirse a reuniones en línea.</span><span class="sxs-lookup"><span data-stu-id="b02b8-469">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="b02b8-470">Con el Calendario de Outlook anclado en el panel de tareas pendientes, únase a una reunión con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="b02b8-470">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="b02b8-471">**Actualización visual del calendario:** el año pasado, hemos incorporado una experiencia de correo actualizada y este año le toca al calendario tener una cara nueva.</span><span class="sxs-lookup"><span data-stu-id="b02b8-471">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="b02b8-472">Las actualizaciones son recientes pero son familiares, para que, como usuario de Outlook veterano, pueda empezar a ser más productivo en seguida.</span><span class="sxs-lookup"><span data-stu-id="b02b8-472">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b02b8-473">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b02b8-473">PowerPoint</span></span>

- <span data-ttu-id="b02b8-474">**Actualización de las diapositivas durante la presentación:** actualice diapositivas editadas por otros autores durante la presentación.</span><span class="sxs-lookup"><span data-stu-id="b02b8-474">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

## <a name="version-2003-march-16"></a><span data-ttu-id="b02b8-476">Versión 2003: 16 de marzo</span><span class="sxs-lookup"><span data-stu-id="b02b8-476">Version 2003: March 16</span></span>
<span data-ttu-id="b02b8-477">*Versión 2003 (compilación 12624,20224)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-477">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (NO QUITAR DETALLES DE CARACTERÍSTICAS CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="b02b8-479">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="b02b8-479">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b02b8-480">Excel</span><span class="sxs-lookup"><span data-stu-id="b02b8-480">Excel</span></span>

- <span data-ttu-id="b02b8-481">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="b02b8-481">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="b02b8-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-482">Outlook</span></span>

- <span data-ttu-id="b02b8-483">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="b02b8-483">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b02b8-484">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b02b8-484">PowerPoint</span></span>

- <span data-ttu-id="b02b8-485">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="b02b8-485">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="b02b8-486">Word</span><span class="sxs-lookup"><span data-stu-id="b02b8-486">Word</span></span>

- <span data-ttu-id="b02b8-487">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="b02b8-487">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b02b8-488">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="b02b8-488">Office Suite</span></span>

- <span data-ttu-id="b02b8-489">**Paneles con pestañas:** ahora puede cambiar entre varios paneles con la pestaña situada en la parte derecha de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="b02b8-489">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="b02b8-490">Esta interfaz de usuario solo será visible cuando haya dos o más paneles abiertos.</span><span class="sxs-lookup"><span data-stu-id="b02b8-490">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="b02b8-493">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="b02b8-493">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b02b8-494">Excel</span><span class="sxs-lookup"><span data-stu-id="b02b8-494">Excel</span></span>

- <span data-ttu-id="b02b8-495">Se abordó un problema donde los enlaces externos no se actualizan cuando se cierra el libro de fuentes.</span><span class="sxs-lookup"><span data-stu-id="b02b8-495">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="b02b8-496">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-496">Outlook</span></span>

- <span data-ttu-id="b02b8-497">Se abordó un problema que causó que los usuarios vieran que el proceso de Outlook permanecía en el administrador de tareas después de salir.</span><span class="sxs-lookup"><span data-stu-id="b02b8-497">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2003-march-10"></a><span data-ttu-id="b02b8-499">Versión 2003: 10 de marzo</span><span class="sxs-lookup"><span data-stu-id="b02b8-499">Version 2003: March 10</span></span>
<span data-ttu-id="b02b8-500">*Versión 2003 (compilación 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-500">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="b02b8-501">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b02b8-501">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)
### <a name="feature-updates"></a><span data-ttu-id="b02b8-503">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="b02b8-503">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b02b8-504">Excel</span><span class="sxs-lookup"><span data-stu-id="b02b8-504">Excel</span></span>
- <span data-ttu-id="b02b8-505">**Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados.</span><span class="sxs-lookup"><span data-stu-id="b02b8-505">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="b02b8-506">Más información</span><span class="sxs-lookup"><span data-stu-id="b02b8-506">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="b02b8-507">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b02b8-507">PowerPoint</span></span>
- <span data-ttu-id="b02b8-508">**Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados.</span><span class="sxs-lookup"><span data-stu-id="b02b8-508">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="b02b8-509">Más información</span><span class="sxs-lookup"><span data-stu-id="b02b8-509">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="b02b8-510">Word</span><span class="sxs-lookup"><span data-stu-id="b02b8-510">Word</span></span>
- <span data-ttu-id="b02b8-511">**Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados.</span><span class="sxs-lookup"><span data-stu-id="b02b8-511">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="b02b8-512">Más información</span><span class="sxs-lookup"><span data-stu-id="b02b8-512">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="b02b8-513">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="b02b8-513">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b02b8-514">Excel</span><span class="sxs-lookup"><span data-stu-id="b02b8-514">Excel</span></span>

- <span data-ttu-id="b02b8-515">Se ha corregido un problema estético en el que el botón "Aceptar" del cuadro de diálogo de Archivo \ Opciones se mostraba atenuado, pero la función no se veía afectada.</span><span class="sxs-lookup"><span data-stu-id="b02b8-515">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="b02b8-516">Se ha corregido un problema que los usuarios pueden haber experimentado al cambiar el nombre de las medidas de tabla dinámica.</span><span class="sxs-lookup"><span data-stu-id="b02b8-516">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="b02b8-517">Se ha corregido un problema en el que el texto de una segmentación de datos no se escalaba correctamente en la vista previa de impresión.</span><span class="sxs-lookup"><span data-stu-id="b02b8-517">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="b02b8-518">Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al usar una macro de VBA para borrar el contenido de un rango.</span><span class="sxs-lookup"><span data-stu-id="b02b8-518">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="b02b8-519">Se ha corregido un problema que provocaba que la interfaz de usuario parpadeara cuando un usuario ejecutaba una macro que interactuaba con la cinta de opciones.</span><span class="sxs-lookup"><span data-stu-id="b02b8-519">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="b02b8-520">Se ha corregido un problema por el que los archivos CSV se cargaban de forma incorrecta cuando la primera palabra del archivo estaba era TABLE.</span><span class="sxs-lookup"><span data-stu-id="b02b8-520">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="b02b8-521">Se ha corregido un problema por el que los usuarios pueden haber sufrido bloqueos al cambiar entre dos libros que tienen diferentes niveles de zoom.</span><span class="sxs-lookup"><span data-stu-id="b02b8-521">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="b02b8-522">Se ha solucionado un problema por el que las funciones CUBEVALUE a veces daban un resultado incorrecto.</span><span class="sxs-lookup"><span data-stu-id="b02b8-522">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="b02b8-523">Este cambio resuelve un error en tiempo de ejecución en el modelo de objetos y el potencial bloqueo de la aplicación (Excel o Word) cuando los complementos pedían elementos host en documentos y hojas de cálculo que contienen formas con bloqueos noSelect.</span><span class="sxs-lookup"><span data-stu-id="b02b8-523">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="b02b8-524">Corrige un problema que causaba que los usuarios de Outlook experimentaran un error al sincronizar la configuración.</span><span class="sxs-lookup"><span data-stu-id="b02b8-524">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="b02b8-525">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-525">Outlook</span></span>

- <span data-ttu-id="b02b8-526">Se ha corregido un problema que hacía que la creación de una regla con Outlook Web Access no se almacenara en el servidor de Exchange y produjera un conflicto.</span><span class="sxs-lookup"><span data-stu-id="b02b8-526">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="b02b8-527">Corregido un problema que causaba que los usuarios de Outlook experimentaran un error al sincronizar la configuración.</span><span class="sxs-lookup"><span data-stu-id="b02b8-527">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="b02b8-528">Se ha corregido un problema por el que, en el modo oscuro de Outlook, no se mostraba la lista desplegable en el campo "De:".</span><span class="sxs-lookup"><span data-stu-id="b02b8-528">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="b02b8-529">Se ha corregido un problema que hizo que Outlook generara inesperadamente resultados de registro en algunas situaciones, incluso cuando el registro se desactivaba.</span><span class="sxs-lookup"><span data-stu-id="b02b8-529">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="b02b8-530">Se ha corregido un problema que provocaba que los usuarios no puedan abrir mensajes de la carpeta pública cuando Outlook se dejaba en marcha durante la noche.</span><span class="sxs-lookup"><span data-stu-id="b02b8-530">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="b02b8-531">Se ha corregido una condición en la que los botones "Permitir" y "Denegar" de la página de permisos se deshabilitan durante el flujo de trabajo de autenticación para agregar una cuenta de Gmail.</span><span class="sxs-lookup"><span data-stu-id="b02b8-531">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="b02b8-532">Se ha corregido un problema que provocaba que los usuarios perdieran el acceso al cuadro de diálogo de permisos de calendario &quot;Opciones de disponibilidad&quot;.</span><span class="sxs-lookup"><span data-stu-id="b02b8-532">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="b02b8-533">Se ha corregido un problema que podría provocar alerta: &quot;"Lo sentimos, tenemos problemas para abrir este elemento"&quot; al abrir algunas instancias de reuniones periódicas que se han enviado desde una zona horaria diferente.</span><span class="sxs-lookup"><span data-stu-id="b02b8-533">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="b02b8-534">Se ha corregido un problema que podría ocasionar que los usuarios no puedan abrir un archivo .msg después de arrastrar y soltar datos adjuntos desde el mensaje.</span><span class="sxs-lookup"><span data-stu-id="b02b8-534">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="b02b8-535">Se ha corregido un problema por el que, después de cargar un archivo adjunto desde Outlook a OneDrive, se podía cambiar el nombre de archivo si el nombre de los datos adjuntos contenía paréntesis.</span><span class="sxs-lookup"><span data-stu-id="b02b8-535">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="b02b8-536">Corregido un problema por el que los usuarios no pueden adjuntar un archivo a un mensaje de correo electrónico a través del explorador de archivos cuando el archivo se abre en otra aplicación.</span><span class="sxs-lookup"><span data-stu-id="b02b8-536">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="b02b8-537">Corregido un problema que causaba que los usuarios de Outlook experimentaran un error al sincronizar la configuración.</span><span class="sxs-lookup"><span data-stu-id="b02b8-537">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b02b8-538">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b02b8-538">PowerPoint</span></span>

- <span data-ttu-id="b02b8-539">Se ha corregido un problema por el que las miniaturas recomendadas parpadean al pasar el ratón por encima de las miniaturas.</span><span class="sxs-lookup"><span data-stu-id="b02b8-539">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="b02b8-540">En algunos casos, esto provocaba un bloqueo de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="b02b8-540">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="b02b8-541">Se ha corregido un problema estético en el que el botón "Aceptar" del cuadro de diálogo de Archivo \ Opciones se mostraba atenuado, pero la función no se veía afectada.</span><span class="sxs-lookup"><span data-stu-id="b02b8-541">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="b02b8-542">Se ha corregido un problema que podría provocar un error al guardar un documento en PowerPoint o en Word con un gráfico de Excel.</span><span class="sxs-lookup"><span data-stu-id="b02b8-542">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="b02b8-543">Project</span><span class="sxs-lookup"><span data-stu-id="b02b8-543">Project</span></span>

- <span data-ttu-id="b02b8-544">Corregido un problema por el que el porcentaje completado de la tarea se cambiaba incorrectamente a un valor inferior al 100 % después de que se marcara como completada.</span><span class="sxs-lookup"><span data-stu-id="b02b8-544">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="b02b8-545">Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="b02b8-545">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="b02b8-546">Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.</span><span class="sxs-lookup"><span data-stu-id="b02b8-546">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="b02b8-547">Visio</span><span class="sxs-lookup"><span data-stu-id="b02b8-547">Visio</span></span>

- <span data-ttu-id="b02b8-548">El panel información de la forma mostraba en la sección Datos de formas detalles que no coincidían con los del archivo al abrirlo en la aplicación de escritorio de Visio.</span><span class="sxs-lookup"><span data-stu-id="b02b8-548">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="b02b8-549">Ya se ha corregido.</span><span class="sxs-lookup"><span data-stu-id="b02b8-549">It has now been fixed.</span></span>

- <span data-ttu-id="b02b8-550">Los mapas de bits importados en versiones anteriores a 2016 no se representaban por motivos de seguridad.</span><span class="sxs-lookup"><span data-stu-id="b02b8-550">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="b02b8-551">Este problema se ha corregido en la suscripción de Visio.</span><span class="sxs-lookup"><span data-stu-id="b02b8-551">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="b02b8-552">Word</span><span class="sxs-lookup"><span data-stu-id="b02b8-552">Word</span></span>

- <span data-ttu-id="b02b8-553">Se ha corregido un problema en el que las tarjetas con comentario no siempre se resaltan cuando se desplaza el puntero del mouse sobre la tarjeta del comentario.</span><span class="sxs-lookup"><span data-stu-id="b02b8-553">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="b02b8-554">Se ha corregido un problema por el que al ir a la tarjeta del comentario, el foco en el cuadro de edición del comentario no era visible.</span><span class="sxs-lookup"><span data-stu-id="b02b8-554">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="b02b8-555">Se ha corregido un problema estético en el que el botón "Aceptar" del cuadro de diálogo de Archivo \ Opciones se mostraba atenuado, pero la función no se veía afectada.</span><span class="sxs-lookup"><span data-stu-id="b02b8-555">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="b02b8-556">Durante una sesión de coautoría de documentos activos, agregar una imagen directamente en una tarjeta de comentario puede dar como resultado la adición de una etiqueta.</span><span class="sxs-lookup"><span data-stu-id="b02b8-556">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="b02b8-557">Este problema se ha corregido.</span><span class="sxs-lookup"><span data-stu-id="b02b8-557">This issue has been fixed.</span></span>

- <span data-ttu-id="b02b8-558">Si se inserta un control (como un control de contenido de texto) en una ecuación, al guardar y abrir el archivo se produce un error de contenido ilegible.</span><span class="sxs-lookup"><span data-stu-id="b02b8-558">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="b02b8-559">Se ha corregido un problema que hacía que no se pudiera guardar un archivo protegido con contraseña anteriormente en un almacenamiento en la nube.</span><span class="sxs-lookup"><span data-stu-id="b02b8-559">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="b02b8-560">Se ha corregido un problema con la característica Comparación para los documentos protegidos para la edición.</span><span class="sxs-lookup"><span data-stu-id="b02b8-560">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="b02b8-561">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="b02b8-561">Office Suite</span></span>

- <span data-ttu-id="b02b8-562">Al usar las propiedades Multichoice/Lookup/Managed-metadata con documentos de Word/Excel/PowerPoint y guardar en una biblioteca de documentos de SharePoint, estas propiedades se limitaban anteriormente a 255 caracteres.</span><span class="sxs-lookup"><span data-stu-id="b02b8-562">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="b02b8-563">Cuando estas propiedades superaban 255 caracteres, estos documentos no se podían guardar.</span><span class="sxs-lookup"><span data-stu-id="b02b8-563">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="b02b8-564">Con este cambio, este límite se ha aumentado a 2048 caracteres.</span><span class="sxs-lookup"><span data-stu-id="b02b8-564">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="b02b8-565">Se ha corregido un problema en Word/Excel/PowerPoint. Ahora, el nombre principal de usuario (UPN) ya no distingue entre mayúsculas y minúsculas, lo que provoca menos errores al trabajar con archivos en SharePoint.</span><span class="sxs-lookup"><span data-stu-id="b02b8-565">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="b02b8-566">Corregido un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.</span><span class="sxs-lookup"><span data-stu-id="b02b8-566">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-march-05"></a><span data-ttu-id="b02b8-568">Versión 2002: 05 de marzo</span><span class="sxs-lookup"><span data-stu-id="b02b8-568">Version 2002: March 05</span></span>
<span data-ttu-id="b02b8-569">*Versión 2002 (compilación 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-569">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="b02b8-570">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="b02b8-570">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="b02b8-571">Versión 2002: 04 de marzo</span><span class="sxs-lookup"><span data-stu-id="b02b8-571">Version 2002: March 04</span></span>
<span data-ttu-id="b02b8-572">*Versión 2002 (compilación 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-572">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="b02b8-574">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="b02b8-574">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="b02b8-575">Proyecto</span><span class="sxs-lookup"><span data-stu-id="b02b8-575">Project</span></span>
- <div><span data-ttu-id="b02b8-576">Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.</span><span class="sxs-lookup"><span data-stu-id="b02b8-576">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="b02b8-577">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="b02b8-577">Office Suite</span></span>
- <div><span data-ttu-id="b02b8-578">Corrige un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.</span><span class="sxs-lookup"><span data-stu-id="b02b8-578">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span></div>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-march-01"></a><span data-ttu-id="b02b8-580">Versión 2002: 01 de marzo</span><span class="sxs-lookup"><span data-stu-id="b02b8-580">Version 2002: March 01</span></span>
<span data-ttu-id="b02b8-581">*Versión 2002 (compilación 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-581">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="b02b8-582">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="b02b8-582">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b02b8-583">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-583">Outlook</span></span>

- <div><span data-ttu-id="b02b8-584">Corrige un problema que provocaba que las aplicaciones de terceros no pudiesen enviar correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="b02b8-584">Addresses an issue that caused third party applications to be unable to send email.</span></span></div>



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2002-february-24"></a><span data-ttu-id="b02b8-586">Versión de 2002: 24 de febrero</span><span class="sxs-lookup"><span data-stu-id="b02b8-586">Version 2002: February 24</span></span>
<span data-ttu-id="b02b8-587">*Versión de 2002 (compilación 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-587">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="b02b8-588">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="b02b8-588">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="b02b8-589">Versión de 2002: 22 de febrero</span><span class="sxs-lookup"><span data-stu-id="b02b8-589">Version 2002: February 22</span></span>
<span data-ttu-id="b02b8-590">*Versión de 2002 (compilación 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-590">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="b02b8-591">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="b02b8-591">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="b02b8-592">Versión 2002: 21 de febrero</span><span class="sxs-lookup"><span data-stu-id="b02b8-592">Version 2002: February 21</span></span>
<span data-ttu-id="b02b8-593">*Versión 2002 (compilación 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-593">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="b02b8-595">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="b02b8-595">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="b02b8-596">Access</span><span class="sxs-lookup"><span data-stu-id="b02b8-596">Access</span></span>

- <span data-ttu-id="b02b8-597">**Aumente su productividad con el Diseñador de consultas, la vista SQL y la ventana Relaciones:** haga clic con el botón derecho en una tabla para abrirla, diseñarla, cambiar su tamaño y ocultarla.</span><span class="sxs-lookup"><span data-stu-id="b02b8-597">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="b02b8-598">Buscar y reemplazar texto en la vista SQL.</span><span class="sxs-lookup"><span data-stu-id="b02b8-598">Search and replace text in SQL View.</span></span> <span data-ttu-id="b02b8-599">Seleccione múltiples tablas en la ventana Relaciones.</span><span class="sxs-lookup"><span data-stu-id="b02b8-599">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="b02b8-600">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-600">Outlook</span></span>

- <span data-ttu-id="b02b8-601">**Nueva experiencia para redes WiFi cautivas:** ¿alguna vez se ha unido a una red WiFi que requiere una página web para iniciar sesión?</span><span class="sxs-lookup"><span data-stu-id="b02b8-601">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="b02b8-602">Outlook ahora lo detecta y le ayuda a estar conectado.</span><span class="sxs-lookup"><span data-stu-id="b02b8-602">Outlook now detects this and helps you get connected.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a><span data-ttu-id="b02b8-605">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="b02b8-605">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b02b8-606">Excel</span><span class="sxs-lookup"><span data-stu-id="b02b8-606">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="b02b8-607">Se ha solucionado un problema por el que las funciones de CUBEVALUE a veces daban un resultado incorrecto.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="b02b8-607">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;</span></span></div><div><span style="display:inline !important;"></span><br></div>


### <a name="outlook"></a><span data-ttu-id="b02b8-608">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-608">Outlook</span></span>

- <div><span data-ttu-id="b02b8-609">Corregido un tema que causó que las comas en el campo de ubicación de una reunión se convirtieran en punto y coma.</span><span class="sxs-lookup"><span data-stu-id="b02b8-609">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span></div>


- <div><span data-ttu-id="b02b8-610">Corregido un problema que podría resultar en un choque al ver el mismo elemento en varias ventanas.</span><span class="sxs-lookup"><span data-stu-id="b02b8-610">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span></div>


- <div><span data-ttu-id="b02b8-611">Corregido un problema que causó que Outlook sincronizara inesperadamente todo el correo, incluso cuando el deslizador de sincronización está configurado en un ajuste más pequeño.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="b02b8-611">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span></div>


- <div><span data-ttu-id="b02b8-612">Corregido un problema que causó que los usuarios con el Tema Negro vieran&quot;de&quot; el desplegable muestra un texto blanco sobre un fondo blanco.</span><span class="sxs-lookup"><span data-stu-id="b02b8-612">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span></div>


- <div><span data-ttu-id="b02b8-613"><span style="display:inline !important;">Este cambio restaura la capacidad de ver sujetos de varias líneas en el encabezado del mensaje.</span></span><span class="sxs-lookup"><span data-stu-id="b02b8-613"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br></div>



[//]: # (NO ELIMINE EL CONTENIDO FINAL DE LOS DETALLES )

## <a name="version-2002-february-18"></a><span data-ttu-id="b02b8-615">Versión 2002: 18 de febrero</span><span class="sxs-lookup"><span data-stu-id="b02b8-615">Version 2002: February 18</span></span>
<span data-ttu-id="b02b8-616">*Versión 2002 (compilación 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-616">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="b02b8-617">Versión 2002: 11 de febrero</span><span class="sxs-lookup"><span data-stu-id="b02b8-617">Version 2002: February 11</span></span>
<span data-ttu-id="b02b8-618">*Versión 2002 (compilación 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="b02b8-618">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="b02b8-619">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b02b8-619">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="b02b8-621">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="b02b8-621">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b02b8-622">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-622">Outlook</span></span>

- <span data-ttu-id="b02b8-623">**Arrastre el correo electrónico a un grupo de tu propiedad:** Mueva y copie mensajes y conversaciones arrastrándolos desde su bandeja de entrada.</span><span class="sxs-lookup"><span data-stu-id="b02b8-623">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="b02b8-624">Los mensajes que arrastres serán compartidos con todos los miembros del grupo.</span><span class="sxs-lookup"><span data-stu-id="b02b8-624">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="b02b8-625">Word</span><span class="sxs-lookup"><span data-stu-id="b02b8-625">Word</span></span>

- <span data-ttu-id="b02b8-626">**Otros usuarios verán los cambios rápidamente**: las mejoras en la coautoría significan que los colaboradores podrán ver los cambios más rápido que nunca.</span><span class="sxs-lookup"><span data-stu-id="b02b8-626">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b02b8-627">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="b02b8-627">Office Suite</span></span>

- <span data-ttu-id="b02b8-628">**Iconos de la barra de estado más nítidos:** los iconos de la barra de estado ahora son más fáciles de ver.</span><span class="sxs-lookup"><span data-stu-id="b02b8-628">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="b02b8-631">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="b02b8-631">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b02b8-632">Access</span><span class="sxs-lookup"><span data-stu-id="b02b8-632">Access</span></span>

- <span data-ttu-id="b02b8-633">Las plantillas de Access ya no deberían causar errores en columnas de datos adjuntos en una base de datos.</span><span class="sxs-lookup"><span data-stu-id="b02b8-633">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="b02b8-634">Después de crear la instancia de una plantilla, ahora debería poder agregar un campo de datos adjuntos a la base de datos.</span><span class="sxs-lookup"><span data-stu-id="b02b8-634">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="b02b8-635">Esta actualización corrige un problema por el que al usar un objeto de grabación de ADODB</span><span class="sxs-lookup"><span data-stu-id="b02b8-635">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="b02b8-636">en el código de VB, se puede notificar un error incorrectamente.</span><span class="sxs-lookup"><span data-stu-id="b02b8-636">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="b02b8-637">Esta actualización corrige un problema que puede hacer que Microsoft Access no identifique una Columna de identidad en una tabla vinculada de SQL Server, lo que puede provocar que las filas aparezcan como eliminadas de forma incorrecta.</span><span class="sxs-lookup"><span data-stu-id="b02b8-637">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="b02b8-638">Excel</span><span class="sxs-lookup"><span data-stu-id="b02b8-638">Excel</span></span>

- <span data-ttu-id="b02b8-639">Se ha corregido un problema por el que los comandos de comentario en el menú contextual no aparecían.</span><span class="sxs-lookup"><span data-stu-id="b02b8-639">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="b02b8-640">Se ha corregido un problema que causaba que algunos usuarios experimentasen bloqueos al convertir texto en columnas con celdas que tienen una matriz derramada.</span><span class="sxs-lookup"><span data-stu-id="b02b8-640">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="b02b8-641">Se ha corregido un problema por el que Excel se bloquea al usar la opción Texto a columnas con matrices dinámicas.</span><span class="sxs-lookup"><span data-stu-id="b02b8-641">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="b02b8-642">Outlook</span><span class="sxs-lookup"><span data-stu-id="b02b8-642">Outlook</span></span>

- <span data-ttu-id="b02b8-643">Se ha corregido un problema en el que el desplazamiento en el calendario con la vista de mes no muestra eventos de calendario anteriores.</span><span class="sxs-lookup"><span data-stu-id="b02b8-643">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="b02b8-644">Las carpetas guardadas en "favoritos" en el panel de navegación izquierdo podían desaparecer de forma esporádica.</span><span class="sxs-lookup"><span data-stu-id="b02b8-644">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="b02b8-645">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.</span><span class="sxs-lookup"><span data-stu-id="b02b8-645">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="b02b8-646">Se ha corregido un problema que hacía que la opción deshabilitar el resaltado de elementos marcados no se pudiera respetar en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="b02b8-646">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="b02b8-647">Se ha corregido un problema que provocaba que los usuarios experimentaran un error al cancelar la configuración de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="b02b8-647">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="b02b8-648">Se ha corregido un problema por el que los mensajes de correo electrónico que expiraban en función de una directiva de retención mostraban dos etiquetas.</span><span class="sxs-lookup"><span data-stu-id="b02b8-648">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="b02b8-649">Una mostraba que el correo expiraba en un día y otra que expiraba en dos días.</span><span class="sxs-lookup"><span data-stu-id="b02b8-649">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="b02b8-650">Se ha corregido un problema que causaba que los usuarios sufrieran un error al visualizar más de 30 calendarios en un entorno Citrix.</span><span class="sxs-lookup"><span data-stu-id="b02b8-650">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b02b8-651">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b02b8-651">PowerPoint</span></span>

- <span data-ttu-id="b02b8-652">Se ha corregido un problema por el que la entrada de lápiz no se procesaba por completo u se omitía al usarla en una animación de entrada de lápiz de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="b02b8-652">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="b02b8-653">Se ha corregido un problema que provocaba que, después de cerrar un archivo, PowerPoint no lo quitara inmediatamente de la colección Presentaciones si había algún controlador de eventos en ejecución.</span><span class="sxs-lookup"><span data-stu-id="b02b8-653">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="b02b8-654">Por lo tanto, el número de presentaciones que informa el modelo de objetos es incorrecto y se evita el cierre de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="b02b8-654">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="b02b8-655">Se ha corregido un problema con el marcador de resaltado: los textos blancos con un marcador oscuro se imprimen como negros en escala de grises.</span><span class="sxs-lookup"><span data-stu-id="b02b8-655">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="b02b8-656">Project</span><span class="sxs-lookup"><span data-stu-id="b02b8-656">Project</span></span>

- <span data-ttu-id="b02b8-657">Se ha corregido un problema por el que el 100 % de las tareas de tipo duración fija podían tener un cálculo del porcentaje incorrecto con menos del 100% completado.</span><span class="sxs-lookup"><span data-stu-id="b02b8-657">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="b02b8-658">Word</span><span class="sxs-lookup"><span data-stu-id="b02b8-658">Word</span></span>

- <span data-ttu-id="b02b8-659">Al actualizar y desplazarse por una tabla de contenido, es posible que se muestre un área gris en el documento.</span><span class="sxs-lookup"><span data-stu-id="b02b8-659">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="b02b8-660">Se ha corregido un problema por el que usar "Examinar" para guardar un archivo podía no funcionar si se escribió un comentario sin publicarlo y el usuario intentó guardar el archivo.</span><span class="sxs-lookup"><span data-stu-id="b02b8-660">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="b02b8-661">Se ha corregido un problema por el que al ir de una tarjeta de comentario a otra se podía mostrar el comentario seleccionado inicialmente con una selección resaltada.</span><span class="sxs-lookup"><span data-stu-id="b02b8-661">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="b02b8-662">Se ha corregido un problema por el que el formato de cursiva se perdía después de editar un comentario, ponerlo en cursiva y, después, publicarlo.</span><span class="sxs-lookup"><span data-stu-id="b02b8-662">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="b02b8-663">Se ha corregido un problema por el que la sugerencia de comentario no se veía en el modo lectura con el color de página invertido.</span><span class="sxs-lookup"><span data-stu-id="b02b8-663">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="b02b8-664">Se ha corregido un problema por el que si se trabajaba en coautoría en un documento, la versión de borrador de un comentario raíz podía no conservarse.</span><span class="sxs-lookup"><span data-stu-id="b02b8-664">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="b02b8-665">Con el Control de cambios habilitado y el panel de comentarios cerrado, Ctrl + Alt + M podía no funcionar para abrir el panel Comentarios.</span><span class="sxs-lookup"><span data-stu-id="b02b8-665">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="b02b8-666">Corregido un problema al agregar una @mención en una tabla que podía generar el mensaje de error: "Una tabla de este documento está dañada".</span><span class="sxs-lookup"><span data-stu-id="b02b8-666">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="b02b8-667">Se ha corregido un problema por el que los comandos de comentario (Modificar comentario, Responder a comentario, Eliminar comentario, Resolver comentario) en el menú contextual de comentarios no se mostraban.</span><span class="sxs-lookup"><span data-stu-id="b02b8-667">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b02b8-668">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="b02b8-668">Office Suite</span></span>

- <span data-ttu-id="b02b8-669">Resuelto un problema que podía causar que el paquete de herramientas de corrección de Noruega Nynorsk (NN-no) no se instalara correctamente.</span><span class="sxs-lookup"><span data-stu-id="b02b8-669">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="b02b8-670">Este cambio resuelve problemas con adaptadores gráficos que aprovechan la GPU integrada de Intel.</span><span class="sxs-lookup"><span data-stu-id="b02b8-670">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

