---
title: Problemas conocidos de Office 365 ProPlus
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: Ofrece información acerca de los problemas conocidos de Office 365 ProPlus
ms.openlocfilehash: 73cd91d43e09900d81418427dab1da01d89f227b
ms.sourcegitcommit: 18190a7f0d562d254300120529a4dfd0d47d26d9
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 12/14/2019
ms.locfileid: "40023555"
---
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="79f28-103">Problemas conocidos de Office 365 ProPlus</span><span class="sxs-lookup"><span data-stu-id="79f28-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="79f28-104">Estos problemas conocidos proporcionan información sobre actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones del Canal mensual, SACT y SAC de Office 365 ProPlus 2019, Visio Pro para Office 365, el Cliente de escritorio de Project Online y Office 365 Empresa.</span><span class="sxs-lookup"><span data-stu-id="79f28-104">These known issues provide information about non-security updates that are included in Monthly Channel, SACT and SAC updates to Office 365 ProPlus in 2019, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

<span data-ttu-id="79f28-105">En esta tabla se ofrece un resumen de los problemas actualmente activos y los problemas resueltos.</span><span class="sxs-lookup"><span data-stu-id="79f28-105">This table offers a summary of current active issues and those issues that have been resolved.</span></span>  <span data-ttu-id="79f28-106">La siguiente tabla se actualizará con los problema importantes que se están investigando.</span><span class="sxs-lookup"><span data-stu-id="79f28-106">We will update the table below with significant issues we are investigating.</span></span>

> [!NOTE]
>- <span data-ttu-id="79f28-107">Esta lista no es exhaustiva.</span><span class="sxs-lookup"><span data-stu-id="79f28-107">This list is not comprehensive.</span></span>
>- <span data-ttu-id="79f28-108">Si experimenta un problema en un canal que no sea el canal que se muestra como resuelto, puede esperar una resolución pronto.</span><span class="sxs-lookup"><span data-stu-id="79f28-108">If you are experiencing an issue in a channel other than the channel shown as resolved, you can expect resolution soon.</span></span> [<span data-ttu-id="79f28-109">Más información</span><span class="sxs-lookup"><span data-stu-id="79f28-109">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/overview-of-update-channels-for-office-365-proplus#BKMK_SAC)
>- <span data-ttu-id="79f28-110">Los problemas resueltos también se documentan en las páginas de canales correspondientes.</span><span class="sxs-lookup"><span data-stu-id="79f28-110">Resolved issues are documented in their respective channel pages as well.</span></span>

<br>

### <a name="last-updated-november-12-2019"></a><span data-ttu-id="79f28-111">Última actualización: 12 de noviembre de 2019</span><span class="sxs-lookup"><span data-stu-id="79f28-111">Last Updated November 12, 2019</span></span>

### <a name="excel"></a><span data-ttu-id="79f28-112">Excel</span><span class="sxs-lookup"><span data-stu-id="79f28-112">Excel</span></span>

- <span data-ttu-id="79f28-113">Los controles de casilla podrían reducirse al usar el autoajuste para ajustar el alto de fila.</span><span class="sxs-lookup"><span data-stu-id="79f28-113">Check box controls could shrink when using autofit to adjust row height</span></span><br><br><span data-ttu-id="79f28-114">**Investigando**: mensualmente, SACT</span><span class="sxs-lookup"><span data-stu-id="79f28-114">**Investigating**: Monthly, SACT</span></span>

- <span data-ttu-id="79f28-115">Problema de rendimiento con las funciones asíncronas definidas por el usuario que hacía que se ejecutaran de forma sincrónica.</span><span class="sxs-lookup"><span data-stu-id="79f28-115">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span><br><br><span data-ttu-id="79f28-116">**Resuelto**: SACT versión 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="79f28-116">**Resolved**: SACT Version 1908 (11929.20436)</span></span> 

- <span data-ttu-id="79f28-117">Se podría impedir que los usuarios guarden en el formato de hoja de trabajo en Office 365 Excel</span><span class="sxs-lookup"><span data-stu-id="79f28-117">Users could be prevented from saving in Office 365 Excel Workbook format</span></span><br><br><span data-ttu-id="79f28-118">**Resuelto**: SACT versión 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="79f28-118">**Resolved**: SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="79f28-119">Problema de rendimiento bajo al hacer clic en el botón Color de fuente cuando un archivo tiene un formato condicional extenso.</span><span class="sxs-lookup"><span data-stu-id="79f28-119">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span><br><br><span data-ttu-id="79f28-120">**Resuelto**: SACT versión 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="79f28-120">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="79f28-121">Mejoras significativas en el rendimiento al eliminar columnas con celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="79f28-121">Significant improvements to the performance of deleting columns with merged cells</span></span><br><br><span data-ttu-id="79f28-122">**Investigando**: SACT</span><span class="sxs-lookup"><span data-stu-id="79f28-122">**Investigating**: SACT</span></span><br><span data-ttu-id="79f28-123">**Resuelto**: Versión mensual 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="79f28-123">**Resolved**:  Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="79f28-124">Resultados incorrectos al convertir los filtros de un informe junto con el resto de la tabla dinámica de consultas enviadas a servidores tabulares SQL.</span><span class="sxs-lookup"><span data-stu-id="79f28-124">Incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span><br><br><span data-ttu-id="79f28-125">**Investigando**: mensualmente </span><span class="sxs-lookup"><span data-stu-id="79f28-125">**Investigating**: Monthly</span></span>

- <span data-ttu-id="79f28-126">Se han corregido los colores que se usan en las vistas previas al insertar gráficos con plantillas de gráficos.</span><span class="sxs-lookup"><span data-stu-id="79f28-126">Fix to correct colors used in previews when inserting charts using chart templates</span></span><br><br><span data-ttu-id="79f28-127">**Resuelto**: versión mensual 1910 (12130.20272) y versión SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="79f28-127">**Resolved**:  Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="79f28-128">Se identificó un problema al insertar archivos como objeto desde OneDrive.</span><span class="sxs-lookup"><span data-stu-id="79f28-128">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="79f28-129">**Resuelto**: Versión mensual 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="79f28-129">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="79f28-130">Se identificó un problema en el que los libros creados en versiones anteriores de Office podrían hacer que Excel se bloqueara cuando se abría en las versiones actuales de Office.</span><span class="sxs-lookup"><span data-stu-id="79f28-130">Identified an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span><br><br>
<span data-ttu-id="79f28-131">**Resuelto**: versión mensual 1910 (12130.20272), versión SACT 1908 (11929.20436) y SAC Version 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="79f28-131">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="79f28-132">Identificó un problema que provocaba retrasos en la visualización de valores escritos después de eliminar un rango.</span><span class="sxs-lookup"><span data-stu-id="79f28-132">Identified an issue that was causing delays in displaying typed values after deleting a range.</span></span><br><br>
<span data-ttu-id="79f28-133">**Resuelto**: versión SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="79f28-133">**Resolved**: SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="79f28-134">Corregimos un problema en el que al seleccionar una celda luego de desplazar, podía resultar en la selección de la celda incorrecta.</span><span class="sxs-lookup"><span data-stu-id="79f28-134">Identified an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span><br><br>
<span data-ttu-id="79f28-135">**Investigando**: SACT</span><span class="sxs-lookup"><span data-stu-id="79f28-135">**Investigating**: SACT</span></span> <br><span data-ttu-id="79f28-136">**Resuelto**: Versión mensual 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="79f28-136">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="79f28-137">Hemos corregido un problema que podía haber causado que los gráficos de líneas de dispersión no se renderizaran correctamente al cambiar la colección de series.</span><span class="sxs-lookup"><span data-stu-id="79f28-137">Identified an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span><br><br>
<span data-ttu-id="79f28-138">**Resuelto**: versión mensual 1910 (12130.20272) y versión SACT 1908 (11929.20300)</span><span class="sxs-lookup"><span data-stu-id="79f28-138">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20300)</span></span>

### <a name="outlook"></a><span data-ttu-id="79f28-139">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f28-139">Outlook</span></span>

- <span data-ttu-id="79f28-140">Identificó un problema que causaba que algunos usuarios vean carpetas especiales duplicadas al agregar una cuenta de Exchange secundaria.</span><span class="sxs-lookup"><span data-stu-id="79f28-140">Identified an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="79f28-141">**Resuelto**: versión mensual 1910 (12130.20272) y versión SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="79f28-141">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="79f28-142">Se ha corregido un problema que podría haber provocado una pérdida de memoria.</span><span class="sxs-lookup"><span data-stu-id="79f28-142">Identified an issue which could have resulted in a memory leak.</span></span> <br><br>
<span data-ttu-id="79f28-143">**Resuelto**: versión mensual 1910 (12130.20272), versión SACT 1908 (11929.20388) y SAC Version 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="79f28-143">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20388), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="79f28-144">Se ha abordado un problema que causaba que algunos usuarios vean carpetas especiales duplicadas al agregar una cuenta de Exchange secundaria.</span><span class="sxs-lookup"><span data-stu-id="79f28-144">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="79f28-145">**Resuelto**: versión mensual 1910 (12130.20272) y versión SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="79f28-145">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="79f28-146">Se ha corregido un problema que a veces podría causar un bloqueo cuando un usuario recibe un mensaje de "conversación perdida" de Skype.</span><span class="sxs-lookup"><span data-stu-id="79f28-146">Identified an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype.</span></span><br><br>
<span data-ttu-id="79f28-147">**Resuelto**: Versión mensual 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="79f28-147">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="79f28-148">Se identificó un problema que provocaba que los usuarios reciban un error genérico "error en la operación" al abrir datos adjuntos en un equipo en el que DisableBGSave está habilitado.</span><span class="sxs-lookup"><span data-stu-id="79f28-148">Identified an issue that caused Users to receive a generic ""operation failed"" error when opening an attachment on a machine where DisableBGSave is enabled.</span></span><br><br>
<span data-ttu-id="79f28-149">**Resuelto**: Versión mensual 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="79f28-149">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="79f28-150">Se identificó un problema con los vínculos de CID: no se pudieron romper las imágenes (imágenes basadas en mensajes de correo electrónico de Outlook).</span><span class="sxs-lookup"><span data-stu-id="79f28-150">Identified an issue with the links of cid: images (Outlook email-based images) were not able to be broken.</span></span><br><br>
<span data-ttu-id="79f28-151">**Resuelto**: SACT versión 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="79f28-151">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="79f28-152">Se ha corregido un problema que pudo haber provocado un mensaje de error incorrecto al intentar enviar correo electrónico cifrado con s/MIME.</span><span class="sxs-lookup"><span data-stu-id="79f28-152">Identified an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail.</span></span><br><br><span data-ttu-id="79f28-153">**Resuelto**: Versión mensual 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="79f28-153">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="79f28-154">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="79f28-154">PowerPoint</span></span>

- <span data-ttu-id="79f28-155">Algunos caracteres katakana pueden mostrarse incorrectamente en un cuadro de texto vertical.</span><span class="sxs-lookup"><span data-stu-id="79f28-155">Some katakana characters may display incorrectly in a vertical text box.</span></span><br><br>
<span data-ttu-id="79f28-156">**Investigando**: mensualmente </span><span class="sxs-lookup"><span data-stu-id="79f28-156">**Investigating**: Monthly</span></span>

- <span data-ttu-id="79f28-157">Se ha corregido un problema que evitó la creación de hipervínculos al pegar el texto con hipervínculos</span><span class="sxs-lookup"><span data-stu-id="79f28-157">Identified an issue which prevented hyperlink from being created when pasting text with hyperlink.</span></span> <br><br><span data-ttu-id="79f28-158">**Resuelto**: Versión mensual 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="79f28-158">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="79f28-159">Se ha corregido un problema que podría provocar la ruptura de TextRanges después de pegar el texto en el encabezado o pie de página, los marcadores de posición en el patrón de diapositivas y en los diseños de diapositiva.</span><span class="sxs-lookup"><span data-stu-id="79f28-159">Identified an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout.</span></span> <br><br><span data-ttu-id="79f28-160">**Resuelto**: Versión mensual 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="79f28-160">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="79f28-161">Se identificó un problema de rendimiento en Win7, donde la galería para insertar formas de la cinta de opciones de todas las aplicaciones tardaba aproximadamente 4 segundos en aparecer. </span><span class="sxs-lookup"><span data-stu-id="79f28-161">Identified a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span><br>
<br><span data-ttu-id="79f28-162">**Resuelto**: versión mensual 1910 (12130.20272), versión SACT 1908 (11929.20396) y SAC Version 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="79f28-162">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20396), SAC Version 1902 (11328.20468)</span></span>

### <a name="project"></a><span data-ttu-id="79f28-163">Project</span><span class="sxs-lookup"><span data-stu-id="79f28-163">Project</span></span>

- <span data-ttu-id="79f28-164">Si tiene una tarea sin nada de trabajo, es posible que la tarea no se pueda marcar como completada y siempre se mostrará en el 99 %.</span><span class="sxs-lookup"><span data-stu-id="79f28-164">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span><br><br>
<span data-ttu-id="79f28-165">**Investigando**: mensualmente </span><span class="sxs-lookup"><span data-stu-id="79f28-165">**Investigating**: Monthly</span></span><br>
<span data-ttu-id="79f28-166">**Resuelto**: SACT versión 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="79f28-166">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="79f28-167">Las sobreasignaciones no se resuelven al redistribuir</span><span class="sxs-lookup"><span data-stu-id="79f28-167">Overallocations are not resolved by leveling</span></span><br><br>
<span data-ttu-id="79f28-168">**Investigando**: mensualmente </span><span class="sxs-lookup"><span data-stu-id="79f28-168">**Investigating**: Monthly</span></span>

- <span data-ttu-id="79f28-169">Identificamos un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de solo lectura.</span><span class="sxs-lookup"><span data-stu-id="79f28-169">Identified an issue where users could get several messages when opening a read-only project.</span></span><br><br>
<span data-ttu-id="79f28-170">**Resuelto**: versión mensual 1910 (12130.20344) y versión SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="79f28-170">**Resolved**: Monthly Version 1910 (12130.20344), SACT Version 1908 (11929.20436)</span></span>

### <a name="word"></a><span data-ttu-id="79f28-171">Word</span><span class="sxs-lookup"><span data-stu-id="79f28-171">Word</span></span>

- <span data-ttu-id="79f28-172">Puede que se produzcan errores al buscar desde el panel de navegación</span><span class="sxs-lookup"><span data-stu-id="79f28-172">Searching from the Navigation pane may fail</span></span><br><br>
<span data-ttu-id="79f28-173">**Investigando**: mensualmente </span><span class="sxs-lookup"><span data-stu-id="79f28-173">**Investigating**: Monthly</span></span>

- <span data-ttu-id="79f28-174">Se identificó un problema al insertar archivos como objeto desde OneDrive.</span><span class="sxs-lookup"><span data-stu-id="79f28-174">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="79f28-175">**Resuelto**: Versión mensual 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="79f28-175">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="office-suite"></a><span data-ttu-id="79f28-176">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="79f28-176">Office Suite</span></span>
- <span data-ttu-id="79f28-177">Al intentar guardar un archivo en un recurso compartido de red desconectado, se pueden producir problemas **Investigando**: mensualmente</span><span class="sxs-lookup"><span data-stu-id="79f28-177">Attempting to save a file to a disconnected network share may result in issues **Investigating**: Monthly</span></span>



<br>
<br>

> [!NOTE]
> <span data-ttu-id="79f28-178">Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="79f28-178">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
