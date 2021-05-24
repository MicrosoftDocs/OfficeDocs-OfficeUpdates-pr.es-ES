---
title: Notas de la versión para el canal beta
ms.author: anankani
author: anankani
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Proporciona a los participantes del Modo anticipado de Insider la lista más reciente de las nuevas características, correcciones o problemas conocidos.
ms.openlocfilehash: 289486b3abf7736825f15311524a1d87295ed78e
ms.sourcegitcommit: 830bba63e278d32baeaaaa5323e3fd25cf6b7c24
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52563346"
---
# <a name="release-notes-for-beta-channel"></a><span data-ttu-id="af9df-103">Notas de la versión para el canal beta</span><span class="sxs-lookup"><span data-stu-id="af9df-103">Release Notes for Beta Channel</span></span>

<span data-ttu-id="af9df-104">El presente artículo contiene notas de la versión para las compilaciones del canal beta de las versiones de escritorio de Word, Excel, PowerPoint, Outlook, Access y Project para Windows.</span><span class="sxs-lookup"><span data-stu-id="af9df-104">This article contains release notes for Beta Channel builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="af9df-105">Cada semana se destacarán las nuevas características, correcciones importantes y los problemas principales de mayor interés para usted.</span><span class="sxs-lookup"><span data-stu-id="af9df-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="af9df-106">Tenga en cuenta que a menudo se implementan características (o incluso correcciones) en el canal beta durante un período de tiempo.</span><span class="sxs-lookup"><span data-stu-id="af9df-106">Note that we often roll out features (and sometimes even fixes) to Beta Channel over a period of time.</span></span> <span data-ttu-id="af9df-107">Esto nos permite asegurarnos de que todo funciona correctamente antes de publicar la característica para un público más amplio.</span><span class="sxs-lookup"><span data-stu-id="af9df-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="af9df-108">Por lo tanto, si ve que no dispone de algo de lo que se describe a continuación, no se preocupe, lo obtendrá en algún momento.</span><span class="sxs-lookup"><span data-stu-id="af9df-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="af9df-p102">Estamos realizando algunos cambios en los canales de actualización de las Aplicaciones de Microsoft 365, incluida la adición de un nuevo canal de actualización (canal empresarial mensual) y el cambio de los nombres de los canales de actualización existentes. Para más información, [lea este artículo](/DeployOffice/update-channels-changes).</span><span class="sxs-lookup"><span data-stu-id="af9df-p102">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](/DeployOffice/update-channels-changes).</span></span>

> [!NOTE]
> - <span data-ttu-id="af9df-111">Las notas de publicación se publican semanalmente y pueden ser una compilación de varias versiones.</span><span class="sxs-lookup"><span data-stu-id="af9df-111">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="af9df-112">La fecha de publicación de las notas de versión pueden no coincidir con la fecha real de lanzamiento de la compilación.</span><span class="sxs-lookup"><span data-stu-id="af9df-112">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (NO ELIMINAR)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

## <a name="version-2106-may-14"></a><span data-ttu-id="af9df-115">Versión 2106: 14 de mayo</span><span class="sxs-lookup"><span data-stu-id="af9df-115">Version 2106: May 14</span></span>
<span data-ttu-id="af9df-116">*Versión 2106 (Compilación 14107.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-116">*Version 2106 (Build 14107.20000)*</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-118">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-118">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-119">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-119">Outlook</span></span>

- <span data-ttu-id="af9df-120">Hemos corregido un problema que provocaba que los usuarios vieran los mensajes que requieren acción actualizándose constantemente o revertidos a los encabezados después de la descarga, cuando se ejecute el modo Descargar solo encabezados.</span><span class="sxs-lookup"><span data-stu-id="af9df-120">We fixed an issue that caused users to see actionable messages either constantly refreshing or reverting back to headers after download when running in Download Headers Only mode.</span></span>


- <span data-ttu-id="af9df-121">Hemos corregido un problema que provocaba que el selector de usuarios en Outlook se expandiera hacia arriba en lugar de hacia abajo para los usuarios con una licencia permanente.</span><span class="sxs-lookup"><span data-stu-id="af9df-121">We fixed an issue that caused the people picker in Outlook to expand upwards rather than downwards for users with a perpetual license.</span></span>


- <span data-ttu-id="af9df-122">Hemos corregido un problema que causaba que los usuarios de dominios personalizados vean un mensaje de advertencia sobre los permisos al pegar un vínculo en un mensaje de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="af9df-122">We fixed an issue that caused users of custom domains to see a warning message about permissions when pasting a link into an email message.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-123">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-123">Word</span></span>

- <span data-ttu-id="af9df-124">Hemos corregido un problema que hacía que, al presionar combinaciones de teclas como Ctrl + Mayús + @, no se generaba el carácter acentuado esperado (en este caso, "å").</span><span class="sxs-lookup"><span data-stu-id="af9df-124">We fixed an issue where pressing key combinations such as ctrl + shift + @ would not produce the expected accented character( in this case, 'å').</span></span>


- <span data-ttu-id="af9df-125">Hemos corregido un problema relacionado con la compresión de imágenes.</span><span class="sxs-lookup"><span data-stu-id="af9df-125">We fixed an issue related to image compression.</span></span>


- <span data-ttu-id="af9df-126">Se ha corregido un problema por el que se producía un fallo al copiar datos adjuntos de correo a una aplicación diferente a Word si el nombre de archivo incluía los caracteres DBCS.</span><span class="sxs-lookup"><span data-stu-id="af9df-126">We fixed an issue where copying a mail attachment to an application other than Word would fail if the filename included DBCS characters.</span></span>


- <span data-ttu-id="af9df-127">Hemos corregido un problema que hacía que Word mostrara a veces un borde alrededor del texto que no debía estar allí.</span><span class="sxs-lookup"><span data-stu-id="af9df-127">We fixed an issue where Word sometimes displayed a border around text that should have not been there.</span></span>


### <a name="office-suite"></a><span data-ttu-id="af9df-128">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-128">Office Suite</span></span>

- <span data-ttu-id="af9df-129">Hemos corregido un problema por el que OneDrive mostraba un mensaje de error de combinación cuando en realidad no había ningún conflicto en la combinación.</span><span class="sxs-lookup"><span data-stu-id="af9df-129">We fixed an issue where OneDrive would display a merge error message when there was indeed no merge conflict.</span></span>


- <span data-ttu-id="af9df-130">Hemos corregido un problema relacionado con el orden z de los objetos SVG al convertirlos a formas.</span><span class="sxs-lookup"><span data-stu-id="af9df-130">We fixed an issue related to z-order of SVG objects when converted to shapes.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2106-may-07"></a><span data-ttu-id="af9df-132">Versión 2106: 07 de mayo</span><span class="sxs-lookup"><span data-stu-id="af9df-132">Version 2106: May 07</span></span>
<span data-ttu-id="af9df-133">*Versión 2106 (compilación 14029.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-133">*Version 2106 (Build 14029.20000)*</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-135">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-135">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-136">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-136">Excel</span></span>

- <span data-ttu-id="af9df-137">Hemos corregido un problema que impide que el Administrador de nombres abra libros con un gran número de nombres ocultos.</span><span class="sxs-lookup"><span data-stu-id="af9df-137">We fixed an issue that prevented the Name Manager from opening books with a large number of hidden names.</span></span>


### <a name="outlook"></a><span data-ttu-id="af9df-138">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-138">Outlook</span></span>

- <span data-ttu-id="af9df-139">Hemos corregido un problema que causaba que los usuarios viesen copias de todos los elementos enviados en su carpeta Bandeja de salida.</span><span class="sxs-lookup"><span data-stu-id="af9df-139">We fixed an issue that caused users to see copies of all of their sent items appearing in their Outbox folder.</span></span>


- <span data-ttu-id="af9df-140">Hemos corregido un problema que causaba que Outlook se cerrara de forma inesperada al usar lectura en voz alta con otras versiones de Windows.</span><span class="sxs-lookup"><span data-stu-id="af9df-140">We fixed an issue that caused Outlook closed unexpectedly when using read aloud with other versions of Windows.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-141">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-141">Word</span></span>

- <span data-ttu-id="af9df-142">Hemos corregido un problema que causaba que Word se cerrara inesperadamente al usar lectura en voz alta con otras versiones de Windows.</span><span class="sxs-lookup"><span data-stu-id="af9df-142">We fixed an issue that caused Word closed unexpectedly when using read aloud with other versions of Windows.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2105-april-30"></a><span data-ttu-id="af9df-144">Versión 2105: 30 de abril</span><span class="sxs-lookup"><span data-stu-id="af9df-144">Version 2105: April 30</span></span>
<span data-ttu-id="af9df-145">*Versión 2105 (Compilación 14026.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-145">*Version 2105 (Build 14026.20000)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-147">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-147">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-148">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-148">Outlook</span></span>

- <span data-ttu-id="af9df-149">**Sugerencia de productividad del Comprobador de accesibilidad al enviar correos electrónicos a usuarios externos de listas de distribución de gran tamaño:** Hemos agregado la funcionalidad para que mostrar automáticamente una notificación, mediante una información sobre correo, ante una infracción de accesibilidad al redactar un correo electrónico para grandes audiencias, usuarios externos, etc. Esta configuración se encuentra en Accesibilidad</span><span class="sxs-lookup"><span data-stu-id="af9df-149">**Accessibility Checker nudge when sending emails to large DL, external users:** We added the functionally to get prompted automatically, through a mailtip, of an accessibility violation while composing an email to large audiences, external users, etc. These settings live in the Ease of Access</span></span>

### <a name="visio"></a><span data-ttu-id="af9df-150">Visio</span><span class="sxs-lookup"><span data-stu-id="af9df-150">Visio</span></span>

- <span data-ttu-id="af9df-151">**Formas y galerías de símbolos de AWS:** ahora tenemos galerías de símbolos con las formas de AWS más recientes para ayudarle a crear diagramas.</span><span class="sxs-lookup"><span data-stu-id="af9df-151">**AWS stencils and shapes:** We now have stencils with the latest AWS shapes to help you create diagrams.</span></span> [<span data-ttu-id="af9df-152">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-152">Learn more</span></span>](https://support.office.com/article/138206bf-d10f-4583-9f31-885ce706af49)

### <a name="word"></a><span data-ttu-id="af9df-153">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-153">Word</span></span>

- <span data-ttu-id="af9df-154">**Objetivos de escritura:** objetivos de escritura para WinWord</span><span class="sxs-lookup"><span data-stu-id="af9df-154">**Writing Goals:** Writing Goals for WinWord</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-157">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-157">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-158">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-158">Excel</span></span>

- <span data-ttu-id="af9df-159">Hemos corregido un problema que hacía que Excel se cerrara inesperadamente al desplazarse por los comentarios del panel Comentarios.</span><span class="sxs-lookup"><span data-stu-id="af9df-159">We fixed an issue that cause Excel to close unexpectedly when moving through comments in the Comments pane.</span></span>


- <span data-ttu-id="af9df-160">Hemos corregido un problema que causaba que el formato de fecha se mostrara de forma incorrecta en algunos idiomas al usar complementos.</span><span class="sxs-lookup"><span data-stu-id="af9df-160">We fixed an issue that caused date formatting to be displayed incorrectly in some languages when using add-ins.</span></span>


- <span data-ttu-id="af9df-161">Hemos corregido un problema que podía provocar que Excel se cerrara de forma inesperada al usar Pegado especial con formatos en determinadas situaciones.</span><span class="sxs-lookup"><span data-stu-id="af9df-161">We fixed an issue which could cause Excel to close unexpectedly when using Paste Special with formats in certain situations.</span></span>


### <a name="project"></a><span data-ttu-id="af9df-162">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-162">Project</span></span>

- <span data-ttu-id="af9df-163">Hemos corregido un problema que provocaba que los cambios realizados con los Asistentes para planificación no siempre se capturaran con eventos de cambio.</span><span class="sxs-lookup"><span data-stu-id="af9df-163">We fixed an issue where changes done through Planning Wizards weren't always captured by change events.</span></span>


- <span data-ttu-id="af9df-164">Hemos corregido un problema en el que los usuarios no podían quitar proyectos del grupo de recursos.</span><span class="sxs-lookup"><span data-stu-id="af9df-164">We fixed an issue where users were unable to remove projects from the resource pool.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-165">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-165">Word</span></span>

- <span data-ttu-id="af9df-166">Hemos corregido un problema por el cual se conservaba el formato de texto después de quitar los hipervínculos.</span><span class="sxs-lookup"><span data-stu-id="af9df-166">We fixed an issue where text formatting remains after removing hyperlinks.</span></span>


- <span data-ttu-id="af9df-167">Hemos corregido un problema que hacía que los comentarios no se mostraran después de filtrar por usuario.</span><span class="sxs-lookup"><span data-stu-id="af9df-167">We fixed an issue where comments are not displayed after filtering by people.</span></span>


- <span data-ttu-id="af9df-168">Hemos corregido un problema que impedía a Word combinar correspondencia con una base de datos de Access.</span><span class="sxs-lookup"><span data-stu-id="af9df-168">We fixed an issue where Word was unable to perform a Mail Merge with an Access database.</span></span>


- <span data-ttu-id="af9df-169">Hemos corregido un problema que hacía que estuviera disponible la capacidad de contraer los márgenes de los documentos que contuvieran varias columnas.</span><span class="sxs-lookup"><span data-stu-id="af9df-169">We fixed an issue that caused the ability to collapse margins in a document containing multiple columns to be available.</span></span>


- <span data-ttu-id="af9df-170">Hemos corregido un problema que impedía que algunos caracteres se mostraran correctamente en las celdas de la tabla cuando había comentarios en el documento.</span><span class="sxs-lookup"><span data-stu-id="af9df-170">We fixed an issue where some characters are not displayed correctly in table cells when there are comments in the document.</span></span>


- <span data-ttu-id="af9df-171">Hemos corregido un problema por el cual se producían los cambios en el formato de archivo al guardar documentos con el complemento AIP habilitado.</span><span class="sxs-lookup"><span data-stu-id="af9df-171">We fixed an issue where the file format changes occurred when saving documents with the AIP add-in enabled.</span></span>


- <span data-ttu-id="af9df-172">Hemos corregido un problema que hacía que Word no respondiera al editar campos.</span><span class="sxs-lookup"><span data-stu-id="af9df-172">We fixed an issue where Word would become unresponsive when editing fields.</span></span>


- <span data-ttu-id="af9df-173">Hemos corregido un problema por el cual no se solicitaba a los usuarios guardar documentos al usar un comando (en lugar del método abreviado de teclado CTRL+S).</span><span class="sxs-lookup"><span data-stu-id="af9df-173">We fixed an issue where users would not be prompted to save documents when using a command (rather than the CTRL+S keyboard shortcut).</span></span>


- <span data-ttu-id="af9df-174">Hemos corregido un problema por el que la etiqueta de confidencialidad desaparecía de un archivo en Word después de cargar el archivo en SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="af9df-174">We fixed an issue where the sensitivity label disappears from a file in Word after uploading the file to SharePoint Online.</span></span>


### <a name="office-suite"></a><span data-ttu-id="af9df-175">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-175">Office Suite</span></span>

- <span data-ttu-id="af9df-176">Hemos corregido un problema que causaba que el botón de dictado estuviera mal alineado al agregar comentarios a un documento.</span><span class="sxs-lookup"><span data-stu-id="af9df-176">We fixed an issue that caused the Dictation button to be misaligned when adding comments to a document.</span></span>


- <span data-ttu-id="af9df-177">Hemos corregido un problema que causaba que Outlook se cerrara de forma inesperada al usar el modo de contraste alto durante largos períodos de tiempo.</span><span class="sxs-lookup"><span data-stu-id="af9df-177">We fixed an issue where using High Contrast mode for extended periods of time would cause Outlook to close unexpectedly.</span></span>



[//]: # (NO QUITAR FINAL DE CONTENIDO CON DETALLES DE ERROR)

## <a name="version-2105-april-23"></a><span data-ttu-id="af9df-179">Versión 2105: 23 de abril</span><span class="sxs-lookup"><span data-stu-id="af9df-179">Version 2105: April 23</span></span>
<span data-ttu-id="af9df-180">*Versión 2105 (compilación 14014.20002)*</span><span class="sxs-lookup"><span data-stu-id="af9df-180">*Version 2105 (Build 14014.20002)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-182">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-182">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-183">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-183">Excel</span></span>

- <span data-ttu-id="af9df-184">**Importar datos de matrices dinámicas:** ahora puede importar, dar forma y actualizar datos de matrices dinámicas en el libro actual.</span><span class="sxs-lookup"><span data-stu-id="af9df-184">**Import data from dynamic arrays:** You can now import, shape and refresh data from dynamic arrays in the current workbook.</span></span> [<span data-ttu-id="af9df-185">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-185">Learn more</span></span>](https://support.office.com/article/205c6b06-03ba-4151-89a1-87a7eb36e531)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-188">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-188">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-189">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-189">Excel</span></span>

- <span data-ttu-id="af9df-p105">Hemos corregido un problema para ofrecer compatibilidad con versiones anteriores de Excel. El problema puede provocar que un archivo que se guarda en una versión más reciente de Excel no se cargue correctamente en versiones anteriores de Excel debido a funciones como SI.ERROR y BUSCARX agregado a Excel desde Office 2007.</span><span class="sxs-lookup"><span data-stu-id="af9df-p105">We fixed an issue to support backward compatibility with older versions of Excel. The issue may cause a file that is saved in a more recent version of Excel fail to load properly in older versions of Excel due to  functions such as IFERROR and XLOOKUP added to Excel since Office 2007.</span></span>


- <span data-ttu-id="af9df-192">Hemos corregido un problema que en ocasiones producía errores al abrir algunos archivos en la Vista protegida.</span><span class="sxs-lookup"><span data-stu-id="af9df-192">We fixed an issue where some files would occasionally fail to open in Protected View.</span></span>


- <span data-ttu-id="af9df-193">Hemos corregido un problema que causaba que la barra de estado no indicase un estado Listo para algunos usuarios.</span><span class="sxs-lookup"><span data-stu-id="af9df-193">We fixed an issue that caused the status bar to not indicate a Ready state for some users.</span></span>


### <a name="outlook"></a><span data-ttu-id="af9df-194">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-194">Outlook</span></span>

- <span data-ttu-id="af9df-195">Hemos corregido un problema que provocaba errores en la resolución de nombres al enviar en nombre de otro usuario y al resolver en una libreta de direcciones que no es la Lista global de direcciones.</span><span class="sxs-lookup"><span data-stu-id="af9df-195">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-196">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-196">Word</span></span>

- <span data-ttu-id="af9df-197">Hemos corregido un problema que hace que el texto de los marcadores de posición esté recortado en los comentarios al usar idiomas de derecha a izquierda.</span><span class="sxs-lookup"><span data-stu-id="af9df-197">We fixed a issue where placeholder text was clipped in comments when using right-to-left languages.</span></span>


### <a name="office-suite"></a><span data-ttu-id="af9df-198">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-198">Office Suite</span></span>

- <span data-ttu-id="af9df-199">Hemos corregido un problema en el que los hipervínculos que incluyen dígitos se rompen al redactar un mensaje en Outlook en un idioma de derecha a izquierda.</span><span class="sxs-lookup"><span data-stu-id="af9df-199">We fixed an issue where hyperlinks including digits would be broken when composing a message in Outlook in a right-to-left language.</span></span>


- <span data-ttu-id="af9df-200">Hemos corregido un problema que hacía que algunos Scalable Vector Graphics (SVG) no se representasen correctamente.</span><span class="sxs-lookup"><span data-stu-id="af9df-200">We fixed an issue where some Scalable Vector Graphics (SVG) did not render correctly.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2105-april-16"></a><span data-ttu-id="af9df-202">Versión 2105: 16 de abril</span><span class="sxs-lookup"><span data-stu-id="af9df-202">Version 2105: April 16</span></span>
<span data-ttu-id="af9df-203">*Versión 2105 (compilación 14007.20002)*</span><span class="sxs-lookup"><span data-stu-id="af9df-203">*Version 2105 (Build 14007.20002)*</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-205">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-205">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-206">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-206">Excel</span></span>

- <span data-ttu-id="af9df-207">Hemos corregido un problema que causaba que Excel se bloqueara al usar Office de 32 bits en Windows de 64 bits.</span><span class="sxs-lookup"><span data-stu-id="af9df-207">We fixed an issue that caused Excel to crash when using 32 bit Office on 64 bit Windows.</span></span>


- <span data-ttu-id="af9df-208">Hemos corregido un problema que causaba que Narrador leyese incorrectamente las propiedades de dos botones de la pestaña Encabezado y pie de página del cuadro de diálogo Configurar página.</span><span class="sxs-lookup"><span data-stu-id="af9df-208">We fixed an issue that caused Narrator to incorrectly read the properties of two buttons on the Header/Footer tab in the Page Setup dialog box.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="af9df-209">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-209">PowerPoint</span></span>

- <span data-ttu-id="af9df-210">Hemos corregido un problema relacionado con las imágenes vinculadas.</span><span class="sxs-lookup"><span data-stu-id="af9df-210">We fixed an issue related to linked pictures.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2105-april-09"></a><span data-ttu-id="af9df-212">Versión 2105: 09 de abril</span><span class="sxs-lookup"><span data-stu-id="af9df-212">Version 2105: April 09</span></span>
<span data-ttu-id="af9df-213">*Versión 2105 (compilación 14002.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-213">*Version 2105 (Build 14002.20000)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-215">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-215">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-216">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-216">Excel</span></span>

- <span data-ttu-id="af9df-217">**Cinta de opciones de accesibilidad:** encuentre todas las herramientas que necesita para crear contenido accesible en un solo lugar, la cinta de opciones de accesibilidad.</span><span class="sxs-lookup"><span data-stu-id="af9df-217">**Accessibility ribbon:** Find all of the tools you need to create accessible content in one place - the Accessibility ribbon!</span></span>

### <a name="word"></a><span data-ttu-id="af9df-218">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-218">Word</span></span>

- <span data-ttu-id="af9df-219">**Ahora la corrección está disponible para el texto seleccionado dentro del documento:** con estos cambios, ahora puede revisar la ortografía, la gramática y otras sugerencias de escritura inteligente solo para el texto seleccionado.</span><span class="sxs-lookup"><span data-stu-id="af9df-219">**Proofing is now available for selected text within the Document:** With these changes you can now review spelling, grammar and other intelligent writing suggestions for just the selected text.</span></span> <span data-ttu-id="af9df-220">Además, también puede revisar sugerencias para todo el documento.</span><span class="sxs-lookup"><span data-stu-id="af9df-220">Additionally you can also review suggestions for the whole document.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO FINAL)

## <a name="version-2104-april-02"></a><span data-ttu-id="af9df-222">Versión 2104: 02 de abril</span><span class="sxs-lookup"><span data-stu-id="af9df-222">Version 2104: April 02</span></span>
<span data-ttu-id="af9df-223">*Versión 2104 (Compilación 13929.20016)*</span><span class="sxs-lookup"><span data-stu-id="af9df-223">*Version 2104 (Build 13929.20016)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-225">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-225">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-226">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-226">Outlook</span></span>

- <span data-ttu-id="af9df-227">**Respuestas sugeridas en Outlook para Windows:** Cuando recibe un mensaje de correo electrónico que puede responderse con una respuesta breve, Outlook puede sugerirle tres respuestas que puede usar con tan solo hacer un par de clics.</span><span class="sxs-lookup"><span data-stu-id="af9df-227">**Suggested Replies in Outlook for Windows:** When you receive an email message that can be answered by a short response, Outlook can suggest three responses you can use to reply with just a couple of clicks.</span></span>

- <span data-ttu-id="af9df-228">**Habilitar las mejoras del calendario compartido:** Outlook puede actualizar los calendarios compartidos en Office 365 con la API de REST.</span><span class="sxs-lookup"><span data-stu-id="af9df-228">**Turn on shared calendar improvements:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="af9df-229">Active la vista previa para obtener actualizaciones más rápidas y confiables de los calendarios compartidos.</span><span class="sxs-lookup"><span data-stu-id="af9df-229">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-232">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-232">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="af9df-233">Acceso</span><span class="sxs-lookup"><span data-stu-id="af9df-233">Access</span></span>

- <span data-ttu-id="af9df-234">Hemos corregido un problema por el que, cuando una aplicación externa solicitaba una interfaz de accesibilidad, nos impedía cerrar hasta que se liberaba su referencia.</span><span class="sxs-lookup"><span data-stu-id="af9df-234">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-235">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-235">Word</span></span>

- <span data-ttu-id="af9df-p108">Con este error, Office no estaba respetando las directivas específicas (se mostraba un grupo de plantillas en la página principal cuando debían haber estado deshabilitadas). Con esta corrección, se respetan las directivas.</span><span class="sxs-lookup"><span data-stu-id="af9df-p108">In this bug, specific policies weren't being honored by Office (a group of templates were being shown on the Home Page when they should have been disabled). With this fix, the policies are being honored.</span></span>


- <span data-ttu-id="af9df-238">Hemos corregido un problema con el Autoguardado.</span><span class="sxs-lookup"><span data-stu-id="af9df-238">We fixed an issue in auto save.</span></span>


- <span data-ttu-id="af9df-239">Hemos corregido Application.OnTime donde puede que no se desencadene correctamente.</span><span class="sxs-lookup"><span data-stu-id="af9df-239">We made a fix in Application.OnTime where it might not trigger correctly.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL )

## <a name="version-2104-march-26"></a><span data-ttu-id="af9df-241">Versión 2104: 26 de marzo</span><span class="sxs-lookup"><span data-stu-id="af9df-241">Version 2104: March 26</span></span>
<span data-ttu-id="af9df-242">*Versión 2104 (compilación 13919.20002)*</span><span class="sxs-lookup"><span data-stu-id="af9df-242">*Version 2104 (Build 13919.20002)*</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-244">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-244">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-245">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-245">Outlook</span></span>

- <span data-ttu-id="af9df-246">Hemos corregido un problema que causaba que algunos usuarios experimentasen un cierre inesperado de Outlook al sincronizar los cambios en la jerarquía de carpetas.</span><span class="sxs-lookup"><span data-stu-id="af9df-246">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-247">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-247">Word</span></span>

- <span data-ttu-id="af9df-248">Hemos corregido un problema por el cual los estilos de copiar y pegar pueden no ser iguales en el texto pegado.</span><span class="sxs-lookup"><span data-stu-id="af9df-248">We fixed an issue which copy and paste styles may not be same in pasted text.</span></span>


### <a name="office-suite"></a><span data-ttu-id="af9df-249">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-249">Office Suite</span></span>

- <span data-ttu-id="af9df-250">Se ha corregido un problema de rendimiento relacionado con la iteración de texto.</span><span class="sxs-lookup"><span data-stu-id="af9df-250">Fixed a performance issue related to iteration of text.</span></span>



[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2104-march-19"></a><span data-ttu-id="af9df-252">Versión 2104: 19 de marzo</span><span class="sxs-lookup"><span data-stu-id="af9df-252">Version 2104: March 19</span></span>
<span data-ttu-id="af9df-253">*Versión 2104 (Compilación 13913.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-253">*Version 2104 (Build 13913.20000)*</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-255">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-255">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="af9df-256">Access</span><span class="sxs-lookup"><span data-stu-id="af9df-256">Access</span></span>

- <span data-ttu-id="af9df-257">Este cambio corrige un problema por el que al ejecutar una consulta que pasara por SQL Server, se mostraba en algunos casos un mensaje de error que alertaba de un "estado de cursor no válido".</span><span class="sxs-lookup"><span data-stu-id="af9df-257">This change fixes an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="af9df-258">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-258">Excel</span></span>

- <span data-ttu-id="af9df-259">Hemos corregido un problema que bloqueaba la capacidad de pegar como fórmulas en una hoja protegida.</span><span class="sxs-lookup"><span data-stu-id="af9df-259">We fixed a problem that was preventing the ability to paste as formulas on a protected sheet.</span></span>


### <a name="project"></a><span data-ttu-id="af9df-260">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-260">Project</span></span>

- <span data-ttu-id="af9df-261">Se ha corregido un problema por el que, si el formato de fecha es W4/4, el selector de fecha puede mostrar un día y un año incorrectos.</span><span class="sxs-lookup"><span data-stu-id="af9df-261">Fixed an issue where if the date format is W4/4, the date picker may show the wrong day and year.</span></span>


### <a name="office-suite"></a><span data-ttu-id="af9df-262">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-262">Office Suite</span></span>

- <span data-ttu-id="af9df-263">Soluciona un problema con el soporte técnico de GDI+ LineJoinMiterClipped en Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-263">Fixes an issue with support of GDI+ LineJoinMiterClipped in Office.</span></span>



[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2104-march-12"></a><span data-ttu-id="af9df-265">Versión 2104: 12 de marzo</span><span class="sxs-lookup"><span data-stu-id="af9df-265">Version 2104: March 12</span></span>
<span data-ttu-id="af9df-266">*Versión 2104 (Compilación 13906.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-266">*Version 2104 (Build 13906.20000)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-268">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-268">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="af9df-269">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-269">PowerPoint</span></span>

- <span data-ttu-id="af9df-270">**Insertar vídeos de Flipgrid en PowerPoint:** PowerPoint ahora admite la inserción de vídeos de Flipgrid en las diapositivas.</span><span class="sxs-lookup"><span data-stu-id="af9df-270">**Insert Flipgrid videos in PowerPoint:** PowerPoint will now support insertion of Flipgrid videos in slides.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-273">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-273">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-274">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-274">Excel</span></span>

- <span data-ttu-id="af9df-275">Hemos corregido un problema por el que los hipervínculos creados con la función HIPERVINCULO no funcionaban si el archivo se guardaba como un documento PDF.</span><span class="sxs-lookup"><span data-stu-id="af9df-275">We fixed an issue in which hyperlinks created using the HYPERLINK function would not work if the file was saved as a PDF document.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-276">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-276">Word</span></span>

- <span data-ttu-id="af9df-277">Hemos corregido un problema con los comentarios durante la coautoría.</span><span class="sxs-lookup"><span data-stu-id="af9df-277">We fixed an issue with comments during coauthoring.</span></span>



[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2103-march-05"></a><span data-ttu-id="af9df-279">Versión 2103: 05 de marzo</span><span class="sxs-lookup"><span data-stu-id="af9df-279">Version 2103: March 05</span></span>
<span data-ttu-id="af9df-280">*Versión 2103 (compilación 13901.20036)*</span><span class="sxs-lookup"><span data-stu-id="af9df-280">*Version 2103 (Build 13901.20036)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-282">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-282">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-283">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-283">Excel</span></span>

- <span data-ttu-id="af9df-284">**Autoguardado y coautoría en documentos cifrados confidenciales:** no elija entre productividad y seguridad.</span><span class="sxs-lookup"><span data-stu-id="af9df-284">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="af9df-285">Con Microsoft Information Protection, los documentos que se cifran con etiquetas de confidencialidad ahora permiten el autoguardado y la coautoría con otras personas en tiempo real, igual que los documentos sin cifrar.</span><span class="sxs-lookup"><span data-stu-id="af9df-285">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="af9df-286">Requiere que el espacio empresarial opte por participar (más información: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="af9df-286">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-287">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-287">PowerPoint</span></span>

- <span data-ttu-id="af9df-288">**Autoguardado y coautoría en documentos cifrados confidenciales:** no elija entre productividad y seguridad.</span><span class="sxs-lookup"><span data-stu-id="af9df-288">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="af9df-289">Con Microsoft Information Protection, los documentos que se cifran con etiquetas de confidencialidad ahora permiten el autoguardado y la coautoría con otras personas en tiempo real, igual que los documentos sin cifrar.</span><span class="sxs-lookup"><span data-stu-id="af9df-289">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="af9df-290">Requiere que el espacio empresarial opte por participar (más información: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="af9df-290">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="word"></a><span data-ttu-id="af9df-291">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-291">Word</span></span>

- <span data-ttu-id="af9df-292">**Autoguardado y coautoría en documentos cifrados confidenciales:** no elija entre productividad y seguridad.</span><span class="sxs-lookup"><span data-stu-id="af9df-292">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="af9df-293">Con Microsoft Information Protection, los documentos que se cifran con etiquetas de confidencialidad ahora permiten el autoguardado y la coautoría con otras personas en tiempo real, igual que los documentos sin cifrar.</span><span class="sxs-lookup"><span data-stu-id="af9df-293">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="af9df-294">Requiere que el espacio empresarial opte por participar (más información: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="af9df-294">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-297">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-297">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-298">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-298">Excel</span></span>

- <span data-ttu-id="af9df-299">Hemos corregido un problema por el que la fuente cambiaría de forma inesperada al usar un signo de multiplicación o división con una fuente japonesa.</span><span class="sxs-lookup"><span data-stu-id="af9df-299">Corrected an issue where the font would change unexpectedly when using a multiplication or divide sign with a Japanese font.</span></span> <span data-ttu-id="af9df-300">Ahora continuamos usando la misma fuente si admite el carácter.</span><span class="sxs-lookup"><span data-stu-id="af9df-300">We now continue to use the same font if it supports the character.</span></span>


- <span data-ttu-id="af9df-301">Hemos corregido un problema que causaba que algunos formatos de tabla dinámica dañaran el libro al guardar en formato .xls o .xlt.</span><span class="sxs-lookup"><span data-stu-id="af9df-301">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="af9df-302">Hemos corregido un problema por el que se muestran de forma inesperada algunas notas al abrir un libro.</span><span class="sxs-lookup"><span data-stu-id="af9df-302">We fixed an issue where some notes were unexpectedly shown when opening a workbook.</span></span>


### <a name="outlook"></a><span data-ttu-id="af9df-303">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-303">Outlook</span></span>

- <span data-ttu-id="af9df-304">Hemos corregido un problema que causaba que los caracteres que no sean ASCII se exportaran de forma incorrecta al exportar a un archivo CSV.</span><span class="sxs-lookup"><span data-stu-id="af9df-304">We fixed an issue that caused non-ASCII characters to export incorrectly when exporting to CSV.</span></span>


- <span data-ttu-id="af9df-305">Hemos corregido un problema que causaba que los usuarios no pudieran buscar un grupo de contactos con Comprobar nombres al redactar un correo.</span><span class="sxs-lookup"><span data-stu-id="af9df-305">We fixed an issue that caused users to be unable to look up a contact group with Check Names  when composing mail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="af9df-306">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-306">PowerPoint</span></span>

- <span data-ttu-id="af9df-307">Hemos corregido un problema que hacía que las flechas de los gráficos de líneas no estuvieran tal y como se esperaba en el modo de presentación de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="af9df-307">We fixed an issue where arrows in line charts were not appearing as expected in PowerPoint slideshow mode.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-308">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-308">Word</span></span>

- <span data-ttu-id="af9df-309">Hemos corregido un problema por el que, al abrir un archivo protegido con una etiqueta de Microsoft Information Protection (MIP), se puede colgar de forma indefinida si el usuario no ha iniciado sesión en una identidad que tiene acceso a la etiqueta protegida de MIP.</span><span class="sxs-lookup"><span data-stu-id="af9df-309">We fixed an issue where opening a file protected with a Microsoft Information Protection (MIP) label can hang indefinitely if the user is not signed in to an identity that has access to the MIP protected label.</span></span> <span data-ttu-id="af9df-310">El usuario no puede cancelar la apertura para mostrar la solicitud de inicio de sesión yno se puede completar correctamente gasta entonces.</span><span class="sxs-lookup"><span data-stu-id="af9df-310">The user is forced to cancel the open to show the sign-in prompt, and the open only succeeds after that point.</span></span> <span data-ttu-id="af9df-311">Para solucionar este problema, permita que se muestre la solicitud de inicio de sesión durante la apertura o descarga.</span><span class="sxs-lookup"><span data-stu-id="af9df-311">Fixing this issue by allowing the sign-in prompt to be shown during open/download.</span></span>


- <span data-ttu-id="af9df-312">Hemos corregido un problema al usar Dictado en el nuevo Comentarios de Word. Ahora, el botón de dictado de la tarjeta Comentarios se activa y desactivada correctamente.</span><span class="sxs-lookup"><span data-stu-id="af9df-312">We fixed an issue when using Dictation in the new Word Commenting, the Dictation button in the Comment card now correctly toggles on and off.</span></span>


- <span data-ttu-id="af9df-313">Se ha corregido un problema por el que no se insertaba ningún espacio entre palabras cuando los usuarios dictaban en su documento.</span><span class="sxs-lookup"><span data-stu-id="af9df-313">Fixed an issue where there was no space being inserted between words when users dictated into their document.</span></span>


- <span data-ttu-id="af9df-314">Hemos corregido un problema al publicar comentarios de varias líneas escritos en RTL que causaba que las líneas 2 en adelante se alineasen a la izquierda en lugar de a la derecha.</span><span class="sxs-lookup"><span data-stu-id="af9df-314">We fixed an issue when posting multi-line comments typed in RTL caused the 2nd and onward lines to be aligned to the left instead of the right.</span></span>


- <span data-ttu-id="af9df-315">Hemos corregido un problema que hace que la revisión ortográfica cambie entre dos menús contextuales de corrección ortográfica diferentes.</span><span class="sxs-lookup"><span data-stu-id="af9df-315">We fixed an issue where spell check switched between two different spelling correction context menus.</span></span>


- <span data-ttu-id="af9df-316">Hemos corregido un problema en el que las columnas pueden tener texto superpuesto.</span><span class="sxs-lookup"><span data-stu-id="af9df-316">We fixed an issue where columns might have overlapping text.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2103-february-26"></a><span data-ttu-id="af9df-318">Versión 2103: 26 de febrero</span><span class="sxs-lookup"><span data-stu-id="af9df-318">Version 2103: February 26</span></span>
<span data-ttu-id="af9df-319">*Versión 2103 (compilación 13819.20006)*</span><span class="sxs-lookup"><span data-stu-id="af9df-319">*Version 2103 (Build 13819.20006)*</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-321">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-321">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-322">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-322">Excel</span></span>

- <span data-ttu-id="af9df-323">Hemos corregido un problema que impedía a los usuarios exportar un libro de Excel a PDF.</span><span class="sxs-lookup"><span data-stu-id="af9df-323">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="af9df-324">Hemos corregido un problema que causaba que se perdiera algo del formato al copiar una hoja mientras se trabajaba en coautoría.</span><span class="sxs-lookup"><span data-stu-id="af9df-324">We fixed an issue where some formatting could be lost when copying a sheet while coauthoring.</span></span>


### <a name="outlook"></a><span data-ttu-id="af9df-325">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-325">Outlook</span></span>

- <span data-ttu-id="af9df-326">Hemos corregido un problema que causaba que los usuarios viesen cómo los datos adjuntos se duplicaban al quitar la protección DRM.</span><span class="sxs-lookup"><span data-stu-id="af9df-326">We fixed an issue that caused users to see attachments getting duplicated when removing DRM protection.</span></span>


### <a name="project"></a><span data-ttu-id="af9df-327">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-327">Project</span></span>

- <span data-ttu-id="af9df-328">Se ha corregido un problema por el que es posible que las divisiones de tareas se creen de forma incorrecta al guardar un proyecto desde Project Web App en un archivo local.</span><span class="sxs-lookup"><span data-stu-id="af9df-328">Fixed an issue where task splits may be wrongly created when saving a project from Project web app to a local file.</span></span> <span data-ttu-id="af9df-329">Esto sucedía al usar un calendario de tareas con horas de trabajo no estándar.</span><span class="sxs-lookup"><span data-stu-id="af9df-329">This would happen if a task calendar with non-standard working times was being used.</span></span>


- <span data-ttu-id="af9df-330">Se ha corregido un problema por el que, si la columna de indicador no está en el primer lugar de la columna, al cortar una tarea de resumen, no se advierte de que también se quitarán las subtareas.</span><span class="sxs-lookup"><span data-stu-id="af9df-330">Fixed an issue where if the indicator column is not in the first column spot, when you cut a summary task you aren't warned that the subtasks will also be removed.</span></span>


- <span data-ttu-id="af9df-331">Se ha corregido un problema por el que, si un usuario seleccionaba la opción Agregar su usuario a una función de tarea en su Timesheet, no se podrían usar correctamente las unidades de disponibilidad de recursos en la tarea creada.</span><span class="sxs-lookup"><span data-stu-id="af9df-331">Fixed an issue where if a user selected the Add Yourself to a Task function on their Timesheet, the correctly resource availability units may not be used on the created assignment.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-332">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-332">Word</span></span>

- <span data-ttu-id="af9df-333">Hemos corregido un problema con la alineación de varios comentarios.</span><span class="sxs-lookup"><span data-stu-id="af9df-333">We fixed an issue with alignment of multiple comments.</span></span>


- <span data-ttu-id="af9df-334">Hemos corregido un problema en los métodos abreviados de teclado del panel de tareas Leer en voz alta.</span><span class="sxs-lookup"><span data-stu-id="af9df-334">We fixed an issue in Read Aloud task pane keyboard shortcuts.</span></span>


### <a name="office-suite"></a><span data-ttu-id="af9df-335">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-335">Office Suite</span></span>

- <span data-ttu-id="af9df-336">Las ubicaciones de OneDrive ahora se filtran según corresponda en la configuración de directiva de grupo.</span><span class="sxs-lookup"><span data-stu-id="af9df-336">OneDrive places are now filtered out as appropriate per the group policy setting.</span></span>


- <span data-ttu-id="af9df-337">Soluciona un problema relacionado con la falta de respuesta que puede producirse al cargar imágenes EMF.</span><span class="sxs-lookup"><span data-stu-id="af9df-337">Fixes an issue related to unresponsiveness that may occur when loading EMF images.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2103-february-19"></a><span data-ttu-id="af9df-339">Versión 2103: 19 de febrero</span><span class="sxs-lookup"><span data-stu-id="af9df-339">Version 2103: February 19</span></span>
<span data-ttu-id="af9df-340">*Versión 2103 (compilación 13811.20002)*</span><span class="sxs-lookup"><span data-stu-id="af9df-340">*Version 2103 (Build 13811.20002)*</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-342">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-342">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-343">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-343">Outlook</span></span>

- <span data-ttu-id="af9df-344">Hemos corregido un problema que causaba que los usuarios viesen cómo los datos adjuntos se duplicaban al quitar la protección DRM.</span><span class="sxs-lookup"><span data-stu-id="af9df-344">We fixed an issue that caused users to see attachments getting duplicated when removing DRM protection.</span></span>


### <a name="project"></a><span data-ttu-id="af9df-345">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-345">Project</span></span>

- <span data-ttu-id="af9df-346">Se ha corregido un problema por el que, si la columna de indicador no está en el primer lugar de la columna, al cortar una tarea de resumen, no se advierte de que también se quitarán las subtareas.</span><span class="sxs-lookup"><span data-stu-id="af9df-346">Fixed an issue where if the indicator column is not in the first column spot, when you cut a summary task you aren't warned that the subtasks will also be removed.</span></span>


- <span data-ttu-id="af9df-347">Se ha corregido un problema por el que, si un usuario seleccionaba la opción Agregar su usuario a una función de tarea en su Timesheet, no se podrían usar correctamente las unidades de disponibilidad de recursos en la tarea creada.</span><span class="sxs-lookup"><span data-stu-id="af9df-347">Fixed an issue where if a user selected the Add Yourself to a Task function on their Timesheet, the correctly resource availability units may not be used on the created assignment.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-348">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-348">Word</span></span>

- <span data-ttu-id="af9df-349">Hemos corregido un problema en los métodos abreviados de teclado del panel de tareas Leer en voz alta.</span><span class="sxs-lookup"><span data-stu-id="af9df-349">We fixed an issue in Read Aloud task pane keyboard shortcuts.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2103-february-12"></a><span data-ttu-id="af9df-351">Versión 2103: 12 de febrero</span><span class="sxs-lookup"><span data-stu-id="af9df-351">Version 2103: February 12</span></span>
<span data-ttu-id="af9df-352">*Versión 2103 (Compilación 13806.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-352">*Version 2103 (Build 13806.20000)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-354">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-354">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-355">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-355">Outlook</span></span>

- <span data-ttu-id="af9df-356">**Sugerencias de redacción con tecnología de Búsqueda de Microsoft (Para\CC\CCO):** ahora la adición de personas a la línea Para\CC usa la tecnología de Búsqueda de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="af9df-356">**Microsoft Search powered compose (To\CC\BCC) suggestions:** Adding people to the To\CC line is now powered by Microsoft Search.</span></span>

- <span data-ttu-id="af9df-357">**Dictado está disponible en más idiomas:** ahora admite 7 idiomas nuevos: hindi, ruso, polaco, portugués (Portugal), coreano, tailandés y chino (Taiwán)</span><span class="sxs-lookup"><span data-stu-id="af9df-357">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>

### <a name="word"></a><span data-ttu-id="af9df-358">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-358">Word</span></span>

- <span data-ttu-id="af9df-359">**Dictado está disponible en más idiomas:** ahora admite 7 idiomas nuevos: hindi, ruso, polaco, portugués (Portugal), coreano, tailandés y chino (Taiwán)</span><span class="sxs-lookup"><span data-stu-id="af9df-359">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-362">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-362">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-363">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-363">Excel</span></span>

- <span data-ttu-id="af9df-364">Se ha corregido un problema que causaba que Excel se cerrara de forma inesperada al intentar mostrar la tarjeta tipos de datos porque una imagen no se podía recuperar.</span><span class="sxs-lookup"><span data-stu-id="af9df-364">Fixed an issue where Excel would sometimes close unexpectedly when trying to show the Data Types card due to a not being able to retrieve an image.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-365">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-365">PowerPoint</span></span>

- <span data-ttu-id="af9df-366">Corregido un problema con la reproducción de animaciones y marcadores de audio.</span><span class="sxs-lookup"><span data-stu-id="af9df-366">Fixes an issue with looping animations and audio bookmarks.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-367">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-367">Project</span></span>

- <span data-ttu-id="af9df-368">Se ha corregido un problema por el que una tarea completada al 100 % podía aparecer como completada al 99 %.</span><span class="sxs-lookup"><span data-stu-id="af9df-368">Fixed an issue where a task that are 100% complete may revert back to 99% complete.</span></span>

- <span data-ttu-id="af9df-369">Se ha corregido un problema por el que Project se cerraba inesperadamente si ejecutaba JAWS e iba al diálogo de información de la tarea.</span><span class="sxs-lookup"><span data-stu-id="af9df-369">Fixed an issue where Project may close unexpectedly if you are running JAWS and go to the task information dialog.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-370">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-370">Word</span></span>

- <span data-ttu-id="af9df-371">Hemos corregido un problema con Autoguardado.</span><span class="sxs-lookup"><span data-stu-id="af9df-371">We fixed an issue in AutoSave.</span></span>


- <span data-ttu-id="af9df-372">Hemos corregido un problema relacionado con la resolución de conflictos durante la coautoría.</span><span class="sxs-lookup"><span data-stu-id="af9df-372">We fixed an issue in resolving conflicts while in coauthoring.</span></span>




[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2102-february-05"></a><span data-ttu-id="af9df-374">Versión 2102: 05 de febrero</span><span class="sxs-lookup"><span data-stu-id="af9df-374">Version 2102: February 05</span></span>
<span data-ttu-id="af9df-375">*Versión 2102 (Compilación 13801.20004)*</span><span class="sxs-lookup"><span data-stu-id="af9df-375">*Version 2102 (Build 13801.20004)*</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-377">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-377">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="af9df-378">Access</span><span class="sxs-lookup"><span data-stu-id="af9df-378">Access</span></span>

- <span data-ttu-id="af9df-379">Ahora verá las pestañas seleccionadas más claramente en Access.</span><span class="sxs-lookup"><span data-stu-id="af9df-379">You will now see selected tabs clearer in Access.</span></span>


### <a name="excel"></a><span data-ttu-id="af9df-380">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-380">Excel</span></span>

- <span data-ttu-id="af9df-381">Hemos corregido un problema por el que Excel dejaba de responder después de seleccionar una serie de datos en un gráfico.</span><span class="sxs-lookup"><span data-stu-id="af9df-381">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="af9df-382">Hemos corregido un problema por el que, al presionar Entrar con determinados teclados de Android, se agregaba una nueva línea en lugar de pasar a la siguiente celda.</span><span class="sxs-lookup"><span data-stu-id="af9df-382">We fixed an issue where pressing Enter with certain keyboards on Android would add a new line rather than moving to the next cell.</span></span>


- <span data-ttu-id="af9df-383">Se ha corregido un problema relacionado con las imágenes que conservaban su relación de aspecto durante una operación de recorte.</span><span class="sxs-lookup"><span data-stu-id="af9df-383">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="outlook"></a><span data-ttu-id="af9df-384">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-384">Outlook</span></span>

- <span data-ttu-id="af9df-385">Hemos corregido un problema por el que los mensajes de correo electrónico se enviaban como firmados digitalmente después de que el usuario desactivara esa opción.</span><span class="sxs-lookup"><span data-stu-id="af9df-385">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="af9df-386">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-386">PowerPoint</span></span>

- <span data-ttu-id="af9df-387">Se ha corregido un problema relacionado con las imágenes que conservaban su relación de aspecto durante una operación de recorte.</span><span class="sxs-lookup"><span data-stu-id="af9df-387">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-388">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-388">Word</span></span>

- <span data-ttu-id="af9df-389">Se ha corregido un problema relacionado con las imágenes que conservaban su relación de aspecto durante una operación de recorte.</span><span class="sxs-lookup"><span data-stu-id="af9df-389">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


- <span data-ttu-id="af9df-390">Hemos corregido un problema que podía truncar un comentario con vínculos.</span><span class="sxs-lookup"><span data-stu-id="af9df-390">We fixed an issue which the comment may be truncated with links.</span></span>


- <span data-ttu-id="af9df-391">Hemos corregido un problema con el modo de conflicto al trabajar en coautoría.</span><span class="sxs-lookup"><span data-stu-id="af9df-391">We fixed an issue with conflict mode when coauthoring.</span></span>


- <span data-ttu-id="af9df-392">Hemos corregido un problema relacionado con guardar archivos en SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="af9df-392">We fixed an issue in saving to SharePoint Online</span></span>


- <span data-ttu-id="af9df-393">Hemos corregido un problema relacionado con la exportación de un documento de Word a PDF.</span><span class="sxs-lookup"><span data-stu-id="af9df-393">We fixed an issue in exporting Word document to PDF.</span></span>


### <a name="office-suite"></a><span data-ttu-id="af9df-394">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-394">Office Suite</span></span>

- <span data-ttu-id="af9df-395">Se ha corregido un problema por el que, en algunas circunstancias, Office presentaba etiquetas de confidencialidad para una cuenta con la que se había iniciado sesión en lugar de presentarlas para otra cuenta diferente con la que se había iniciado sesión.</span><span class="sxs-lookup"><span data-stu-id="af9df-395">Fixed an issue where Office would in some circumstances present sensitivity labels for one signed-in account when it should present sensitivity labels for a different signed-in account.</span></span>




[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2102-january-29"></a><span data-ttu-id="af9df-397">Versión 2102: 29 de enero</span><span class="sxs-lookup"><span data-stu-id="af9df-397">Version 2102: January 29</span></span>
<span data-ttu-id="af9df-398">*Versión 2102 (Compilación 13721.20008)*</span><span class="sxs-lookup"><span data-stu-id="af9df-398">*Version 2102 (Build 13721.20008)*</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-400">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-400">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-401">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-401">Excel</span></span>

- <span data-ttu-id="af9df-402">Hemos corregido un problema en el que Excel se cerraba inesperadamente al agregar un nombre en el cuadro de diálogo Definir nombre.</span><span class="sxs-lookup"><span data-stu-id="af9df-402">We fixed a problem where Excel would unexpectedly quit when you added a Name in the Define Name dialog.</span></span>


### <a name="outlook"></a><span data-ttu-id="af9df-403">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-403">Outlook</span></span>

- <span data-ttu-id="af9df-404">Hemos corregido un problema que causaba que no se mostrara el icono de cifrado de los correos electrónicos enviados con la opción Solo cifrar.</span><span class="sxs-lookup"><span data-stu-id="af9df-404">We fixed an issue that caused the encryption icon to fail to display for emails sent using the Encrypt Only option.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-405">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-405">Project</span></span>

- <span data-ttu-id="af9df-406">Se ha corregido un problema por el que no se podían abrir proyectos con nombres largos en alfabeto cirílico a través del Centro de proyectos.</span><span class="sxs-lookup"><span data-stu-id="af9df-406">Fixed an issue where projects with long Cyrillic names could not be opened through Project Center.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2102-january-22"></a><span data-ttu-id="af9df-408">Versión 2102: 22 de enero</span><span class="sxs-lookup"><span data-stu-id="af9df-408">Version 2102: January 22</span></span>
<span data-ttu-id="af9df-409">*Versión 2102 (compilación 13714.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-409">*Version 2102 (Build 13714.20000)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-411">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-411">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-412">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-412">Excel</span></span>

- <span data-ttu-id="af9df-413">**Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H.</span><span class="sxs-lookup"><span data-stu-id="af9df-413">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="af9df-414">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-414">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="af9df-415">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-415">Outlook</span></span>

- <span data-ttu-id="af9df-416">**Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H.</span><span class="sxs-lookup"><span data-stu-id="af9df-416">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="af9df-417">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-417">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a><span data-ttu-id="af9df-418">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-418">PowerPoint</span></span>

- <span data-ttu-id="af9df-419">**Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H.</span><span class="sxs-lookup"><span data-stu-id="af9df-419">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="af9df-420">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-420">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="word"></a><span data-ttu-id="af9df-421">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-421">Word</span></span>

- <span data-ttu-id="af9df-422">**Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H.</span><span class="sxs-lookup"><span data-stu-id="af9df-422">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="af9df-423">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-423">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-426">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-426">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-427">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-427">Excel</span></span>

- <span data-ttu-id="af9df-428">Se ha corregido un problema que hace que determinados gráficos que usan rangos de celdas discontinuos no se carguen al volver a abrir los archivos.</span><span class="sxs-lookup"><span data-stu-id="af9df-428">Fixes issue where certain charts using discontinuous ranges of cells would not load when files are re-opened.</span></span>


- <span data-ttu-id="af9df-429">Corrige un problema por el que Excel no se podía iniciar o se bloqueaba inesperadamente si se usaba determinada configuración de protección contra vulnerabilidades de Seguridad de Windows (SimExec, CallerCheck).</span><span class="sxs-lookup"><span data-stu-id="af9df-429">Fixes an issue where Excel would fail to launch or crash unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="af9df-430">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-430">PowerPoint</span></span>

- <span data-ttu-id="af9df-431">Se ha corregido un problema relacionado con la muestra de emojis con color.</span><span class="sxs-lookup"><span data-stu-id="af9df-431">Fixed an issue related to displaying emojis with color.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-432">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-432">Word</span></span>


- <span data-ttu-id="af9df-433">Corregido un problema que impedía que la escritura en tiempo real y la presencia se restauraran tras perder la conectividad a Internet durante un período de tiempo.</span><span class="sxs-lookup"><span data-stu-id="af9df-433">This fixes an issue that prevented real-time typing and presence from being restored after loosing internet connectivity for a period of time.</span></span>


- <span data-ttu-id="af9df-434">Se ha corregido un problema con la coautoría.</span><span class="sxs-lookup"><span data-stu-id="af9df-434">We fixed an issue with coauthoring.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2102-january-15"></a><span data-ttu-id="af9df-436">Versión 2102: 15 de enero</span><span class="sxs-lookup"><span data-stu-id="af9df-436">Version 2102: January 15</span></span>
<span data-ttu-id="af9df-437">*Versión 2102 (compilación 13707.20008)*</span><span class="sxs-lookup"><span data-stu-id="af9df-437">*Version 2102 (Build 13707.20008)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-439">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-439">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-440">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-440">Outlook</span></span>

- <span data-ttu-id="af9df-441">**Compartir con Teams:** compartir un correo electrónico o una conversación desde Outlook a un usuario o canal en Teams.</span><span class="sxs-lookup"><span data-stu-id="af9df-441">**Share to Teams:** Share an email or a conversation from Outlook to a person or channel in Teams.</span></span>

### <a name="visio"></a><span data-ttu-id="af9df-442">Visio</span><span class="sxs-lookup"><span data-stu-id="af9df-442">Visio</span></span>

- <span data-ttu-id="af9df-443">**Gráficos preparados para los diagramas:** elija entre una gran biblioteca de íconos, imágenes de fotografías de archivo, personas recortadas y adhesivos que puede agregar a sus dibujos de Visio.</span><span class="sxs-lookup"><span data-stu-id="af9df-443">**Ready-made graphics for your diagrams:** Choose from a large library of icons, stock photo images, cutout people, and stickers that you can add to your Visio drawings.</span></span> [<span data-ttu-id="af9df-444">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-444">Learn more</span></span>](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-447">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-447">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="af9df-448">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-448">Project</span></span>

- <span data-ttu-id="af9df-449">Se corrigió un problema por el que, cuando se asignó un recurso de costo a una tarea hito, el costo de línea base no se acumulaba correctamente.</span><span class="sxs-lookup"><span data-stu-id="af9df-449">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-450">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-450">Word</span></span>

- <span data-ttu-id="af9df-451">Se corrigió un problema por el que, al ejecutar la macro de VBA ExportAsFixedFormat2, se produce un error que indica "Valor no válido de presentación (miembro desconocido)".</span><span class="sxs-lookup"><span data-stu-id="af9df-451">Fixing a failure when running the VBA macro ExportAsFixedFormat2 fails with an error stating "Presentation (unknown member) illegal value".</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2102-january-08"></a><span data-ttu-id="af9df-453">Versión 2102: 8 de enero</span><span class="sxs-lookup"><span data-stu-id="af9df-453">Version 2102: January 08</span></span>
<span data-ttu-id="af9df-454">*Versión 2102 (compilación 13704.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-454">*Version 2102 (Build 13704.20000)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-456">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-456">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-457">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-457">Outlook</span></span>

- <span data-ttu-id="af9df-458">**El dictado se puso mejor:** Ahora es más fácil crear contenido con la voz gracias a la nueva barra de herramientas de dictado, comandos de voz y compatibilidad con la puntuación automática</span><span class="sxs-lookup"><span data-stu-id="af9df-458">**Dictation just got better:** It's now easier to create content with your voice with the new dictation toolbar, voice commands, and auto-punctuation support</span></span>

### <a name="word"></a><span data-ttu-id="af9df-459">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-459">Word</span></span>

- <span data-ttu-id="af9df-460">**El dictado se puso mejor:** Ahora es más fácil crear contenido con la voz gracias a la nueva barra de herramientas de dictado, comandos de voz y compatibilidad con la puntuación automática</span><span class="sxs-lookup"><span data-stu-id="af9df-460">**Dictation just got better:** It's now easier to create content with your voice with the new dictation toolbar, voice commands, and auto-punctuation support</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-463">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-463">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-464">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-464">Excel</span></span>

- <span data-ttu-id="af9df-465">Se ha corregido un problema que provocaba que la vista previa del intervalo de Excel insertado en PowerPoint mostrara un tamaño incorrecto.</span><span class="sxs-lookup"><span data-stu-id="af9df-465">We have fixed an issue where Preview of embedded Excel range in PowerPoint shows incorrect size.</span></span>



[//]: # (NO QUITAR LOS DETALLES DE ERROR AL FINAL DEL CONTENIDO)

## <a name="version-2101-january-01"></a><span data-ttu-id="af9df-467">Versión 2101: 01 de enero</span><span class="sxs-lookup"><span data-stu-id="af9df-467">Version 2101: January 01</span></span>
<span data-ttu-id="af9df-468">*Versión 2101 (compilación 13624.20002)*</span><span class="sxs-lookup"><span data-stu-id="af9df-468">*Version 2101 (Build 13624.20002)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-470">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-470">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-471">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-471">Excel</span></span>

- <span data-ttu-id="af9df-472">**Etiqueta obligatoria:** usuarios con la Directiva de etiquetado obligatoria se debe establecer que los administradores les etiqueten sus documentos y mensajes de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="af9df-472">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-473">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-473">PowerPoint</span></span>

- <span data-ttu-id="af9df-474">**Etiqueta obligatoria:** usuarios con la Directiva de etiquetado obligatoria se debe establecer que los administradores les etiqueten sus documentos y mensajes de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="af9df-474">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-475">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-475">Word</span></span>

- <span data-ttu-id="af9df-476">**Etiqueta obligatoria:** usuarios con la Directiva de etiquetado obligatoria se debe establecer que los administradores les etiqueten sus documentos y mensajes de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="af9df-476">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-479">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-479">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="af9df-480">OneNote</span><span class="sxs-lookup"><span data-stu-id="af9df-480">OneNote</span></span>

- <span data-ttu-id="af9df-481">Este cambio resuelve un problema de representación que afecta a OneNote.</span><span class="sxs-lookup"><span data-stu-id="af9df-481">This change addresses a rendering issue affecting OneNote.</span></span>


### <a name="outlook"></a><span data-ttu-id="af9df-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-482">Outlook</span></span>

- <span data-ttu-id="af9df-483">Este cambio permite a Outlook aprovechar una configuración de Exchange Server que suprime la presentación del buzón de correo de Exchange Online para usuarios finales.</span><span class="sxs-lookup"><span data-stu-id="af9df-483">This change enables Outlook to take advantage of an Exchange server setting that suppresses the display of the Exchange Online Archive Mailbox to end users.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="af9df-484">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-484">PowerPoint</span></span>

- <span data-ttu-id="af9df-485">Este cambio resuelve un problema con las formas de combinar trabajar con texto.</span><span class="sxs-lookup"><span data-stu-id="af9df-485">This change addresses an issue with Merge Shapes working with text.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-486">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-486">Word</span></span>

- <span data-ttu-id="af9df-487">Corrección para mejorar la solidez de los comentarios modernos.</span><span class="sxs-lookup"><span data-stu-id="af9df-487">Fix to make Modern comments more robust.</span></span>


- <span data-ttu-id="af9df-488">Se ha corregido un problema al editar una entrada de comentario con @mention.</span><span class="sxs-lookup"><span data-stu-id="af9df-488">Fixed an issue when editing commenting post with @mention.</span></span>


- <span data-ttu-id="af9df-489">Los borradores de comentarios desaparecen al crear una nueva instancia de Word.</span><span class="sxs-lookup"><span data-stu-id="af9df-489">Comment drafts disappears when creating a new Word instance.</span></span>


- <span data-ttu-id="af9df-490">Corrección y problema con las barras de desplazamiento anidadas en la ventana Comentarios.</span><span class="sxs-lookup"><span data-stu-id="af9df-490">Fix and issue with nested scrollbars in the comments pane.</span></span>



[//]: # (NO QUITAR LOS DETALLES DE ERROR AL FINAL DEL CONTENIDO)

## <a name="version-2101-december-25"></a><span data-ttu-id="af9df-492">Versión 2101: 25 de diciembre</span><span class="sxs-lookup"><span data-stu-id="af9df-492">Version 2101: December 25</span></span>
<span data-ttu-id="af9df-493">*Versión 2101 (compilación 13617.20002)*</span><span class="sxs-lookup"><span data-stu-id="af9df-493">*Version 2101 (Build 13617.20002)*</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-495">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-495">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-496">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-496">Excel</span></span>

- <span data-ttu-id="af9df-497">Actualización para que la configuración de los separadores decimales y de millares se mantenga al copiar un gráfico de Excel y pegarlo en Word.</span><span class="sxs-lookup"><span data-stu-id="af9df-497">Update so that decimal and thousands separators settings carryover when copying a chart from Excel and pasting into Word</span></span>


- <span data-ttu-id="af9df-498">Se ha corregido un problema por el que Excel se cerraba inesperadamente al abrir archivos UNC con atributos de archivo no válidos (hora de creación, fecha de modificación, etc.).</span><span class="sxs-lookup"><span data-stu-id="af9df-498">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="af9df-499">Este cambio resuelve un problema relacionado con la modificación de los colores del contorno de imágenes SVG.</span><span class="sxs-lookup"><span data-stu-id="af9df-499">This change addresses an issue related to changing outline colors of SVG images.</span></span>


### <a name="outlook"></a><span data-ttu-id="af9df-500">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-500">Outlook</span></span>

- <span data-ttu-id="af9df-501">Se ha corregido un problema que provocaba que los usuarios no pudiesen especificar durante cuánto tiempo querían permitir el acceso al iniciar una combinación de correo de Word, lo que hacía que se enviasen demasiados avisos.</span><span class="sxs-lookup"><span data-stu-id="af9df-501">We fixed an issue that caused users to be unable to specify how long they wanted to allow access for when starting a mail merge from Word, resulting in them getting excess prompts.</span></span>


- <span data-ttu-id="af9df-502">Se ha corregido un problema que provocaba que Outlook se cerrara de forma inesperada para los usuarios de complementos basados en Redemption.</span><span class="sxs-lookup"><span data-stu-id="af9df-502">We fixed an issue that caused a Outlook to close unexpectedly for users of Redemption based Add-ins.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="af9df-503">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-503">PowerPoint</span></span>

- <span data-ttu-id="af9df-504">Este cambio resuelve un problema relacionado con la modificación de los colores del contorno de imágenes SVG.</span><span class="sxs-lookup"><span data-stu-id="af9df-504">This change addresses an issue related to changing outline colors of SVG images.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-505">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-505">Word</span></span>

- <span data-ttu-id="af9df-506">Este cambio resuelve un problema relacionado con la modificación de los colores del contorno de imágenes SVG.</span><span class="sxs-lookup"><span data-stu-id="af9df-506">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="af9df-507">Corrige un problema por el que el cuadro de respuesta en una tarjeta de comentario aparece fuera de la pantalla.</span><span class="sxs-lookup"><span data-stu-id="af9df-507">Fixes an issue where the reply box on a comment card is off the screen.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO FINAL)

## <a name="version-2101-december-18"></a><span data-ttu-id="af9df-509">Versión 2101: 18 de diciembre</span><span class="sxs-lookup"><span data-stu-id="af9df-509">Version 2101: December 18</span></span>
<span data-ttu-id="af9df-510">*Version 2101 (compilación 13610.20002)*</span><span class="sxs-lookup"><span data-stu-id="af9df-510">*Version 2101 (Build 13610.20002)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-512">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-512">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-513">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-513">Excel</span></span>

- <span data-ttu-id="af9df-514">**Envío de datos de auditoría sobre el etiquetado de confidencialidad a los administradores de M365:** cuando los usuarios apliquen, cambien o eliminen las etiquetas de confidencialidad en sus documentos y correos electrónicos, Office enviará datos de auditoría al back-end de auditoría de M365 para que los administradores los vean.</span><span class="sxs-lookup"><span data-stu-id="af9df-514">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="af9df-515">Esta es una funcionalidad silenciosa (sin interfaz de usuario) para beneficio del administrador.</span><span class="sxs-lookup"><span data-stu-id="af9df-515">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-516">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-516">Outlook</span></span>

- <span data-ttu-id="af9df-517">**Envío de datos de auditoría sobre el etiquetado de confidencialidad a los administradores de M365:** cuando los usuarios apliquen, cambien o eliminen las etiquetas de confidencialidad en sus documentos y correos electrónicos, Office enviará datos de auditoría al back-end de auditoría de M365 para que los administradores los vean.</span><span class="sxs-lookup"><span data-stu-id="af9df-517">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="af9df-518">Esta es una funcionalidad silenciosa (sin interfaz de usuario) para beneficio del administrador.</span><span class="sxs-lookup"><span data-stu-id="af9df-518">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-519">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-519">PowerPoint</span></span>

- <span data-ttu-id="af9df-520">**Envío de datos de auditoría sobre el etiquetado de confidencialidad a los administradores de M365:** cuando los usuarios apliquen, cambien o eliminen las etiquetas de confidencialidad en sus documentos y correos electrónicos, Office enviará datos de auditoría al back-end de auditoría de M365 para que los administradores los vean.</span><span class="sxs-lookup"><span data-stu-id="af9df-520">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="af9df-521">Esta es una funcionalidad silenciosa (sin interfaz de usuario) para beneficio del administrador.</span><span class="sxs-lookup"><span data-stu-id="af9df-521">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-522">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-522">Word</span></span>

- <span data-ttu-id="af9df-523">**Envío de datos de auditoría sobre el etiquetado de confidencialidad a los administradores de M365:** cuando los usuarios apliquen, cambien o eliminen las etiquetas de confidencialidad en sus documentos y correos electrónicos, Office enviará datos de auditoría al back-end de auditoría de M365 para que los administradores los vean.</span><span class="sxs-lookup"><span data-stu-id="af9df-523">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="af9df-524">Esta es una funcionalidad silenciosa (sin interfaz de usuario) para beneficio del administrador.</span><span class="sxs-lookup"><span data-stu-id="af9df-524">This is a silent functionality (no UI) for administrator benefit.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-527">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-527">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-528">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-528">Excel</span></span>

- <span data-ttu-id="af9df-529">Se realizó una mejora de rendimiento al aplicar estilos de formato a tablas dinámicas.</span><span class="sxs-lookup"><span data-stu-id="af9df-529">Made a performance improvement when applying formatting styles to pivot tables.</span></span>


### <a name="outlook"></a><span data-ttu-id="af9df-530">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-530">Outlook</span></span>

- <span data-ttu-id="af9df-531">Se corrigió el problema que causaba que los usuarios no pudieran seleccionar más de una categoría para buscar.</span><span class="sxs-lookup"><span data-stu-id="af9df-531">We fixed and issue that caused users to be unable to select more than one category to search.</span></span>


- <span data-ttu-id="af9df-532">Se corrigió el problema que causaba que la hora de inicio de algunos elementos del calendario cambiara inesperadamente cuando el evento se copiaba de otra cita.</span><span class="sxs-lookup"><span data-stu-id="af9df-532">We fixed an issue that caused the start time of some calendar items to change unexpectedly when the event is copied from another appointment.</span></span>


### <a name="project"></a><span data-ttu-id="af9df-533">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-533">Project</span></span>

- <span data-ttu-id="af9df-534">Hemos corregido un problema por el cual los usuarios creaban proyectos que supuestamente se guardaban con información actualizada pero en los que no había ninguna actualización.</span><span class="sxs-lookup"><span data-stu-id="af9df-534">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-535">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-535">Word</span></span>

- <span data-ttu-id="af9df-536">Corregir animación al escribir en la parte inferior de una tarjeta de comentario.</span><span class="sxs-lookup"><span data-stu-id="af9df-536">Fix animation when typing on the bottom of a comment card.</span></span>


- <span data-ttu-id="af9df-537">Se ha corregido un problema que causaba que Word se bloqueara al guardar un documento en PDF con texto oculto.</span><span class="sxs-lookup"><span data-stu-id="af9df-537">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2101-december-11"></a><span data-ttu-id="af9df-539">Versión 2101: 11 de diciembre</span><span class="sxs-lookup"><span data-stu-id="af9df-539">Version 2101: December 11</span></span>
<span data-ttu-id="af9df-540">*Versión 2101 (compilación 13604.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-540">*Version 2101 (Build 13604.20000)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-542">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-542">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-543">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-543">Outlook</span></span>

- <span data-ttu-id="af9df-544">**Su configuración de Outlook en la nube:** elija la configuración de Outlook para Windows, como Respuestas automáticas, la Bandeja de entrada Prioritarios y Privacidad, y acceda a ellos desde cualquier PC.</span><span class="sxs-lookup"><span data-stu-id="af9df-544">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-545">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-545">Word</span></span>

- <span data-ttu-id="af9df-546">**Mejor colaboración con comentarios modernos:** Agregue comentarios a objetos, @mencione compañeros y resuelva hilos de comentarios para disfrutar de una mejor experiencia de colaboración.</span><span class="sxs-lookup"><span data-stu-id="af9df-546">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="af9df-547">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-547">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)<br /><span data-ttu-id="af9df-548">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/modern-commenting-in-word)</span><span class="sxs-lookup"><span data-stu-id="af9df-548">See details in [blog post](https://insider.office.com/es-ES/blog/modern-commenting-in-word)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-551">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-551">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-552">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-552">Excel</span></span>

- <span data-ttu-id="af9df-553">Se ha corregido un problema por el que Excel mostraba de forma incorrecta una barra de mensajes donde se indicaba que estaba disponible una nueva versión del archivo y obligaba al usuario a descartar los cambios o guardarlos en una copia del libro.</span><span class="sxs-lookup"><span data-stu-id="af9df-553">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="af9df-554">Se ha corregido un problema con los separadores de conmutación después de Selection.Parent.Copy.</span><span class="sxs-lookup"><span data-stu-id="af9df-554">Fixed an issue with switching separators after a Selection.Parent.Copy call.</span></span>


### <a name="outlook"></a><span data-ttu-id="af9df-555">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-555">Outlook</span></span>

- <span data-ttu-id="af9df-556">Se corrigió un problema por el que los mensajes de texto sin formato S/MIME se volvían ilegibles al enviarse.</span><span class="sxs-lookup"><span data-stu-id="af9df-556">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="af9df-557">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-557">PowerPoint</span></span>

- <span data-ttu-id="af9df-558">Este cambio resuelve un problema en la reproducción de vídeos de fondo en bucle en la presentación con diapositivas.</span><span class="sxs-lookup"><span data-stu-id="af9df-558">This change addresses an issue with looping background videos playback in Slide Show.</span></span>


- <span data-ttu-id="af9df-559">Se ha corregido un problema por el que el comando tamaño de fuente, agregado a la herramienta de acceso rápido, se completaba automáticamente al tamaño de fuente definido más cercano al actualizarse.</span><span class="sxs-lookup"><span data-stu-id="af9df-559">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-560">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-560">Word</span></span>

- <span data-ttu-id="af9df-561">Se ha corregido un problema en torno a la eliminación de los comentarios modernos en un control de contenido marcado como no editable.</span><span class="sxs-lookup"><span data-stu-id="af9df-561">We fixed an issue around deleting modern comments in a content control that is marked as not editable.</span></span>



[//]: # (NO QUITAR NINGÚN DETALLE DE ERROR EN EL FINAL DEL CONTENIDO)

## <a name="version-2012-december-04"></a><span data-ttu-id="af9df-563">Versión 2012: 4 de diciembre</span><span class="sxs-lookup"><span data-stu-id="af9df-563">Version 2012: December 04</span></span>
<span data-ttu-id="af9df-564">*Versión 2012 (compilación 13530.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-564">*Version 2012 (Build 13530.20000)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-566">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-566">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-567">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-567">Outlook</span></span>

- <span data-ttu-id="af9df-568">**Dar algo de tiempo entre reuniones consecutivas:** asigne a los asistentes el tiempo necesario para que descansen o se desplacen entre las distintas ubicaciones. Para ello haga que las reuniones empiecen de 5 a 10 minutos antes de forma predeterminada.</span><span class="sxs-lookup"><span data-stu-id="af9df-568">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="af9df-569">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-569">Learn more</span></span>](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

### <a name="visio"></a><span data-ttu-id="af9df-570">Visio</span><span class="sxs-lookup"><span data-stu-id="af9df-570">Visio</span></span>

- <span data-ttu-id="af9df-571">**Nuevas galerías de símbolos y formas de Azure:** Hemos agregado muchas más galerías de símbolos para ayudarle a crear diagramas de Azure actualizados.</span><span class="sxs-lookup"><span data-stu-id="af9df-571">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="af9df-572">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-572">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-575">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-575">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-576">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-576">Excel</span></span>

- <span data-ttu-id="af9df-577">Se ha corregido un problema por el que la edición en idiomas que requieren el uso del IME funcionaba mal al editar en el modo de sobrescritura.</span><span class="sxs-lookup"><span data-stu-id="af9df-577">Fixed an issue where editing in languages that require use of IME would behave poorly when editing in overwrite mode.</span></span>


- <span data-ttu-id="af9df-578">Se ha corregido un hipervínculo roto a un artículo de ayuda en una alerta que aparecía al deshabilitar Autoguardado.</span><span class="sxs-lookup"><span data-stu-id="af9df-578">Fixed a broken hyperlink to a help article in an alert in case Autosave becomes disabled.</span></span>


- <span data-ttu-id="af9df-579">Se ha corregido un problema que provocaba que Excel se cerrase de forma inesperada al copiar y pegar datos en la vista Fórmula.</span><span class="sxs-lookup"><span data-stu-id="af9df-579">Fixed an issue where Excel would close unexpectedly when copying and pasting data in formula view.</span></span>


### <a name="outlook"></a><span data-ttu-id="af9df-580">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-580">Outlook</span></span>

- <span data-ttu-id="af9df-581">Se ha corregido un problema que provocaba que SmartLinks perdiera el formato cuando se guardaba en Borradores.</span><span class="sxs-lookup"><span data-stu-id="af9df-581">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


### <a name="project"></a><span data-ttu-id="af9df-582">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-582">Project</span></span>

- <span data-ttu-id="af9df-583">Se ha corregido un problema que alargaba demasiado el tiempo de apertura de un proyecto con muchos recursos.</span><span class="sxs-lookup"><span data-stu-id="af9df-583">Fixed an issue where opening a project with a lot of resources was taking a long time.</span></span>


- <span data-ttu-id="af9df-584">Se ha corregido un problema por el que algunos proyectos específicos podrían abrirse si había un problema con el archivo del proyecto en una parte específica de la carga.</span><span class="sxs-lookup"><span data-stu-id="af9df-584">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-585">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-585">Word</span></span>

- <span data-ttu-id="af9df-586">A menudo, Pegar como texto sin formato tiene preferencia sobre Pegar como texto enriquecido.</span><span class="sxs-lookup"><span data-stu-id="af9df-586">Paste as plain text is often preferred to pasting as rich text.</span></span> <span data-ttu-id="af9df-587">La corrección de este menú contextual permite al usuario pegar como texto sin formato.</span><span class="sxs-lookup"><span data-stu-id="af9df-587">This context menu fix allows the user to paste as plain text.</span></span> <span data-ttu-id="af9df-588">De lo contrario, el usuario tendría que copiarlo en un editor de texto sin formato como el Bloc de notas y, luego, copiarlo de allí a la aplicación de destino deseada.</span><span class="sxs-lookup"><span data-stu-id="af9df-588">Else the user would have to copy into a plain-text editor like Notepad and then copy from Notepad into the desired target app</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2012-november-27"></a><span data-ttu-id="af9df-590">Versión 2012: 27 de noviembre</span><span class="sxs-lookup"><span data-stu-id="af9df-590">Version 2012: November 27</span></span>
<span data-ttu-id="af9df-591">*Versión 2012 (compilación 13519.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-591">*Version 2012 (Build 13519.20000)*</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-593">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-593">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-594">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-594">Excel</span></span>

- <span data-ttu-id="af9df-595">Corregido un problema por el que Power Pivot no importaba correctamente un archivo de texto delimitado por tabulaciones.</span><span class="sxs-lookup"><span data-stu-id="af9df-595">This fixes an issue where Power Pivot wasn't able to correctly import a tab-delimited text file.</span></span>


### <a name="outlook"></a><span data-ttu-id="af9df-596">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-596">Outlook</span></span>

- <span data-ttu-id="af9df-597">Corregido un problema que provocaba que los usuarios experimentaran problemas al enviar correo de Outlook desde aplicaciones que no son Outlook.</span><span class="sxs-lookup"><span data-stu-id="af9df-597">We fixed an issue that was causing users to experience some issues when sending Outlook mail from applications other than Outlook.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="af9df-598">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-598">PowerPoint</span></span>

- <span data-ttu-id="af9df-599">Este cambio resuelve un problema relacionado con los tiempos de espera experimentados durante el análisis de entrada de lápiz.</span><span class="sxs-lookup"><span data-stu-id="af9df-599">This change addresses an issue related to timeouts experienced during ink analysis.</span></span>


- <span data-ttu-id="af9df-600">Este cambio corrige un error gramatical en la interfaz de usuario Crear un archivo GIF animado.</span><span class="sxs-lookup"><span data-stu-id="af9df-600">This change addresses a grammatical error in the Create an Animated GIF user interface.</span></span>


- <span data-ttu-id="af9df-601">Se ha corregido un problema que evitaba que algunos archivos de PowerPoint corruptos se abrieran correctamente, incluso después de la operación de reparación de un documento.</span><span class="sxs-lookup"><span data-stu-id="af9df-601">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="af9df-602">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-602">Project</span></span>

- <span data-ttu-id="af9df-603">Se ha corregido un problema en el que los usuarios pueden ver varias tareas no asignadas asociadas a una tarea.</span><span class="sxs-lookup"><span data-stu-id="af9df-603">Fixed an issue where users may see multiple unassigned assignments associated with a task.</span></span>


- <span data-ttu-id="af9df-604">Se ha corregido un problema en el que los proyectos de gran tamaño pueden tardar más en especificar un nombre de tarea.</span><span class="sxs-lookup"><span data-stu-id="af9df-604">Fixed an issue where in large projects it can be very slow to enter a task name.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2012-november-20"></a><span data-ttu-id="af9df-606">Versión 2012: 20 de noviembre</span><span class="sxs-lookup"><span data-stu-id="af9df-606">Version 2012: November 20</span></span>
<span data-ttu-id="af9df-607">*Versión 2012 (compilación 13512.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-607">*Version 2012 (Build 13512.20000)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-609">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-609">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-610">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-610">Outlook</span></span>

- <span data-ttu-id="af9df-611">**Todas las reuniones en línea:** facilite la programación de reuniones en línea con una nueva configuración para que todas las reuniones sean en línea de forma predeterminada.</span><span class="sxs-lookup"><span data-stu-id="af9df-611">**Every meeting online:** Make it easier to schedule online meetings with a new setting to make all your meetings online by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-612">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-612">PowerPoint</span></span>

- <span data-ttu-id="af9df-613">**Biblioteca de vídeos:** Mejore sus documentos con una biblioteca de videos editados y libres de royalties disponibles en la aplicación.</span><span class="sxs-lookup"><span data-stu-id="af9df-613">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-616">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-616">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="af9df-617">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-617">PowerPoint</span></span>

- <span data-ttu-id="af9df-618">Se ha corregido un problema que evitaba que el indicador de presencia de un coautor desconocido no se actualizara por completo cuando había disponible más información sobre el coautor.</span><span class="sxs-lookup"><span data-stu-id="af9df-618">Fixed an issue where the presence indicator for an unknown coauthor does not get completely refreshed, once more information about the coauthor is available.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-619">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-619">Word</span></span>

- <span data-ttu-id="af9df-620">Se ha corregido un problema que causaba que Word se bloqueara al guardar un documento en PDF con texto oculto.</span><span class="sxs-lookup"><span data-stu-id="af9df-620">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2012-november-13"></a><span data-ttu-id="af9df-622">Versión 2012: 13 de noviembre</span><span class="sxs-lookup"><span data-stu-id="af9df-622">Version 2012: November 13</span></span>
<span data-ttu-id="af9df-623">*Versión 2012 (Compilación 13510.20004)*</span><span class="sxs-lookup"><span data-stu-id="af9df-623">*Version 2012 (Build 13510.20004)*</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-625">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-625">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-626">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-626">Excel</span></span>

- <span data-ttu-id="af9df-627">Hemos corregido un problema por el cual el comando Insertar objeto no muestra el icono correcto cuando se inserta un archivo desde la carpeta de sincronización local de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="af9df-627">We fixed an issue where the Insert Object command does not show the correct icon when inserting a file from OneDrive local sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="af9df-628">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-628">Outlook</span></span>

- <span data-ttu-id="af9df-629">Hemos corregido un problema que provocaba que el campo Para: quedara en blanco en los informes de estado de la tarea.</span><span class="sxs-lookup"><span data-stu-id="af9df-629">We fixed an issue that caused the To: field to be blank in task status reports.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="af9df-630">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-630">PowerPoint</span></span>

- <span data-ttu-id="af9df-631">Hemos corregido un problema de VBA por el cual Slide.Shapes.AddMediaObject2 se bloqueaba con formatos de vídeo heredados (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="af9df-631">We fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


### <a name="project"></a><span data-ttu-id="af9df-632">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-632">Project</span></span>

- <span data-ttu-id="af9df-633">Hemos corregidoo un problema por el cual no se podían eliminar las dependencias de las entregas si el sitio de SharePoint en el que estaba asociada la entrega ya no existía.</span><span class="sxs-lookup"><span data-stu-id="af9df-633">We fixed an issue where you couldn't delete dependencies on the deliverables if the SharePoint site the deliverable was associated with no longer existed.</span></span>


- <span data-ttu-id="af9df-634">Hemos corregido un problema por el cual los usuarios creaban proyectos que supuestamente se guardaban con información actualizada pero en lo que no había ninguna actualización.</span><span class="sxs-lookup"><span data-stu-id="af9df-634">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-635">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-635">Word</span></span>

- <span data-ttu-id="af9df-636">Hemos corregido un problema relacionado con las imágenes difuminadas por usar el zoom.</span><span class="sxs-lookup"><span data-stu-id="af9df-636">We fixed an issue related to pictures becoming blurry while zooming.</span></span>


- <span data-ttu-id="af9df-637">Hemos corregido un problema por el cual se truncaban hipervínculos largos.</span><span class="sxs-lookup"><span data-stu-id="af9df-637">We fixed an issue where long hyperlinks were getting truncated.</span></span>



[//]: # (NO QUITAR NINGÚN DETALLE DE ERROR EN EL FINAL DEL CONTENIDO)

## <a name="version-2012-november-06"></a><span data-ttu-id="af9df-639">Versión 2012: 6 de noviembre</span><span class="sxs-lookup"><span data-stu-id="af9df-639">Version 2012: November 06</span></span>
<span data-ttu-id="af9df-640">*Versión 2012 (compilación 13430.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-640">*Version 2012 (Build 13430.20000)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-642">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-642">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-643">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-643">Excel</span></span>

- <span data-ttu-id="af9df-644">**Mostrar varias hojas de cálculo al mismo tiempo:** no es necesario que se muestren las hojas de una en una, ya que se pueden mostrar varias hojas ocultas al mismo tiempo.</span><span class="sxs-lookup"><span data-stu-id="af9df-644">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="af9df-645">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-645">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

### <a name="outlook"></a><span data-ttu-id="af9df-646">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-646">Outlook</span></span>

- <span data-ttu-id="af9df-647">**Misma firma, todos los dispositivos:** su firma se almacena en la nube.</span><span class="sxs-lookup"><span data-stu-id="af9df-647">**Same signature, all devices:** Your signature is stored in the cloud.</span></span> <span data-ttu-id="af9df-648">Créelo una vez y úselo en cualquier lugar donde use Outlook.</span><span class="sxs-lookup"><span data-stu-id="af9df-648">Create it once and use it everywhere you use Outlook.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-651">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-651">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-652">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-652">Excel</span></span>

- <span data-ttu-id="af9df-653">Hemos corregido un problema en el que algunos elementos de la cinta de opciones no se localizaban en chino simplificado.</span><span class="sxs-lookup"><span data-stu-id="af9df-653">We fixed an issue where some Ribbon elements were not localized in Simplified Chinese.</span></span>


- <span data-ttu-id="af9df-654">Hemos corregido un problema en el que Excel se terminaba inesperadamente durante la actualización.</span><span class="sxs-lookup"><span data-stu-id="af9df-654">We fixed an issue where Excel terminated unexpectedly when updating.</span></span>


### <a name="outlook"></a><span data-ttu-id="af9df-655">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-655">Outlook</span></span>

- <span data-ttu-id="af9df-656">Hemos arreglado un problema en el que la adición de un archivo adjunto a un mensaje abierto desde un archivo zip fallaba.</span><span class="sxs-lookup"><span data-stu-id="af9df-656">We fixed and issue where adding an attachment to a message opened from a zip file would fail.</span></span>



[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2011-october-30"></a><span data-ttu-id="af9df-658">Versión 2011: 30 de octubre</span><span class="sxs-lookup"><span data-stu-id="af9df-658">Version 2011: October 30</span></span>
<span data-ttu-id="af9df-659">*Versión 2011 (compilación 13426.20004)*</span><span class="sxs-lookup"><span data-stu-id="af9df-659">*Version 2011 (Build 13426.20004)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-661">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-661">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-662">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-662">Excel</span></span>

- <span data-ttu-id="af9df-663">**Cuadros de diálogo de formato condicional mejorados:** Los diálogos de formato condicional ahora son de tamaño ajustable y se puede duplicar la regla con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="af9df-663">**Improved Conditional Formatting dialogs:** Conditional Formatting dialogs are now resizable, and now you can duplicate the rule with a single click.</span></span> [<span data-ttu-id="af9df-664">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-664">Learn more</span></span>](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-667">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-667">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="af9df-668">Acceso</span><span class="sxs-lookup"><span data-stu-id="af9df-668">Access</span></span>

- <span data-ttu-id="af9df-669">Se ha corregido un problema que provocaba que, al utilizar DAO desde aplicaciones que no son de Office, la aplicación se cerrara de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="af9df-669">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="excel"></a><span data-ttu-id="af9df-670">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-670">Excel</span></span>

- <span data-ttu-id="af9df-671">Se ha corregido un problema con Power Pivot cuando usa una conexión en una base de datos de Oracle.</span><span class="sxs-lookup"><span data-stu-id="af9df-671">Fixed a problem with Power Pivot when using a connection to an Oracle database.</span></span>


- <span data-ttu-id="af9df-672">Se corrigió un problema por el que Excel terminó de forma inesperada cuando se activó el proceso de calcular MTR y la actualización de objetos de directiva de grupo (por ejemplo, a través de la actualización remota de la directiva de grupo).</span><span class="sxs-lookup"><span data-stu-id="af9df-672">We fixed an issue where Excel terminated unexpectedly when the process of MTR calc and Group Policy Object update (e.g. via Remote Group Policy Refresh) was triggered.</span></span>


- <span data-ttu-id="af9df-673">Este cambio corrige un error que provoca un error en Excel al intentar cargar un archivo atomsvc.</span><span class="sxs-lookup"><span data-stu-id="af9df-673">This change fixes a bug, which causes a failure in Excel on attempt to load an atomsvc file.</span></span>


- <span data-ttu-id="af9df-674">Se corrigió un problema en el que parece que Word se bloquea al insertar un libro de Excel en un documento de Word.</span><span class="sxs-lookup"><span data-stu-id="af9df-674">We fixed an issue which Word appears to hang when insert Excel workbook into Word document.</span></span>


### <a name="outlook"></a><span data-ttu-id="af9df-675">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-675">Outlook</span></span>

- <span data-ttu-id="af9df-676">Se ha corregido un problema por el que el propietario de un buzón no podía administrar el permiso compartido en su propio Calendario de Outlook, ya que la opción se había desactivado.</span><span class="sxs-lookup"><span data-stu-id="af9df-676">We fixed an issue where a mailbox owner wasn't able to manage Shared permission for their own Calendar as the option was greyed out.</span></span>


- <span data-ttu-id="af9df-677">Se ha corregido un problema por el cual al guardar las plantillas de correo electrónico como .OFT se cambiaban los caracteres chinos por signos de interrogación.</span><span class="sxs-lookup"><span data-stu-id="af9df-677">We fixed an issue where saving email templates as .OFT changed Chinese characters to question marks.</span></span>


- <span data-ttu-id="af9df-678">Se ha corregido un problema por el cual Outlook no podía crear un mensaje con permisos restringidos.</span><span class="sxs-lookup"><span data-stu-id="af9df-678">We fixed an issue where Outlook was not able to create a message with restricted permission.</span></span>


- <span data-ttu-id="af9df-679">Resuelto un problema que hacía que Outlook dejara de funcionar esporádicamente al agregar o guardar datos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="af9df-679">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="af9df-680">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-680">PowerPoint</span></span>

- <span data-ttu-id="af9df-681">Se ha corregido un problema por el cual las líneas de cuadrícula se desplazaban de las diapositivas al cerrar el panel diseño.</span><span class="sxs-lookup"><span data-stu-id="af9df-681">We fixed an issue where grid lines were getting shifted from slides when closing design pane.</span></span>


- <span data-ttu-id="af9df-682">Se ha corregido un problema por el que la barra de desplazamiento en la diapositiva comienza a ajustarse a sí misma después de detener la grabación de pantalla con el panel de selección abierto.</span><span class="sxs-lookup"><span data-stu-id="af9df-682">We fixed an issue where the scroll bar in the slide starts adjusting itself after stopping screen recording with selection pane opened.</span></span>


### <a name="project"></a><span data-ttu-id="af9df-683">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-683">Project</span></span>

- <span data-ttu-id="af9df-684">Se ha corregido un problema que provocaba que, al guardar un proyecto desde PWA en un archivo MPP local, ProjectBeforeTaskChangeEvent se desencadenara para datos no modificados por el usuario.</span><span class="sxs-lookup"><span data-stu-id="af9df-684">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="af9df-685">Se ha corregido un problema en el que las negociaciones de recursos buscaban un recurso por nombre en lugar de un GUID lo que causaría problemas si hubiera varios recursos con el mismo nombre.</span><span class="sxs-lookup"><span data-stu-id="af9df-685">Fixed an issue where resource engagements searched for a resource by name instead of GUID which would cause issues if there were multiple resources with the same name.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-686">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-686">Word</span></span>

- <span data-ttu-id="af9df-687">Se ha corregido un problema por el que al hacer clic en la sugerencia de comentario no se mostraba la tarjeta comentario en la vista.</span><span class="sxs-lookup"><span data-stu-id="af9df-687">We fixed an issue where clicking comment hint didn't zoom out to show comment card in view.</span></span>


- <span data-ttu-id="af9df-688">Se ha corregido un problema de diseño en el que la línea entre columnas podiía haber cambiado.</span><span class="sxs-lookup"><span data-stu-id="af9df-688">We fixed a layout issue which the line between columns might have shifted.</span></span>


- <span data-ttu-id="af9df-689">Se corrigió un problema en el que parece que Word se bloquea al insertar un libro de Excel en un documento de Word.</span><span class="sxs-lookup"><span data-stu-id="af9df-689">We fixed an issue which Word appears to hang when insert Excel workbook into Word document.</span></span>


### <a name="office-suite"></a><span data-ttu-id="af9df-690">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-690">Office Suite</span></span>

- <span data-ttu-id="af9df-691">Se ha corregido un problema en la Herramienta de implementación de Office que provocaba errores en la configuración al usar la característica RemoveMSI con el producto de Office 2007 "Informes de errores de aplicaciones de Microsoft".</span><span class="sxs-lookup"><span data-stu-id="af9df-691">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL FIN DE CONTENIDO)

## <a name="version-2011-october-23"></a><span data-ttu-id="af9df-693">Versión 2011: 23 de octubre</span><span class="sxs-lookup"><span data-stu-id="af9df-693">Version 2011: October 23</span></span>
<span data-ttu-id="af9df-694">*Versión 2011 (compilación 13415.20002)*</span><span class="sxs-lookup"><span data-stu-id="af9df-694">*Version 2011 (Build 13415.20002)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-696">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-696">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="af9df-697">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-697">PowerPoint</span></span>

- <span data-ttu-id="af9df-698">**Ensaye su presentación con el asesor para moderadores:** obtenga comentarios sobre las cosas que ayuden a mantener a un público comprometido, como el ritmo, el tono, las palabras de relleno, las frases sensibles y más.</span><span class="sxs-lookup"><span data-stu-id="af9df-698">**Rehearse your presentation with Presenter Coach:** Get feedback on the things that help keep an audience engaged — like pacing, pitch, filler words, sensitive phrases, and more.</span></span> [<span data-ttu-id="af9df-699">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-699">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-702">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-702">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="af9df-703">Acceso</span><span class="sxs-lookup"><span data-stu-id="af9df-703">Access</span></span>

- <span data-ttu-id="af9df-704">Corregimos un problema por el que algunos usuarios veían el error "recurso del sistema excedido" al intentar exportar una consulta de su carpeta sincronizada de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="af9df-704">We fixed an issue where some users were seeing the "system resource exceeded" error when they tried to export a query from their synced OneDrive folder.</span></span>

- <span data-ttu-id="af9df-705">Corregimos un problema en el que el cambio automático entre las ventanas de la forma estaba cambiando a otra forma.</span><span class="sxs-lookup"><span data-stu-id="af9df-705">We fixed an issue where 'auto'-switching between form windows was switching to another form.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-706">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-706">Outlook</span></span>

- <span data-ttu-id="af9df-707">Corregimos un problema al pegar una dirección URL copiada desde la ubicación de la reunión a otro lugar (como un explorador), la dirección URL contiene un punto y coma al final.</span><span class="sxs-lookup"><span data-stu-id="af9df-707">We fixed an issue when pasting a URL copied from meeting location to somewhere else (such as a browser), the URL contains a semicolon at the end.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-708">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-708">PowerPoint</span></span>

- <span data-ttu-id="af9df-709">Corregimos un problema al duplicar la presentación con diapositivas en un monitor secundario, la presentación puede ocultarse detrás de la otra ventana.</span><span class="sxs-lookup"><span data-stu-id="af9df-709">We fixed an issue when duplicating slideshow to secondary monitor, the slideshow may hide behind other window.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-710">Proyecto</span><span class="sxs-lookup"><span data-stu-id="af9df-710">Project</span></span>

- <span data-ttu-id="af9df-711">Corregimos un problema por el que el Proyecto puede finalizar inesperadamente al abrir archivos en los que se especificaban los contornos de los recursos de una determinada manera.</span><span class="sxs-lookup"><span data-stu-id="af9df-711">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-712">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-712">Word</span></span>

- <span data-ttu-id="af9df-713">Corregimos un problema en control de cambios que a veces es posible que abra un documento de Word.</span><span class="sxs-lookup"><span data-stu-id="af9df-713">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>

- <span data-ttu-id="af9df-714">Corregimos un problema de impresión cuando se aplica la etiqueta de carácter con marcas de agua.</span><span class="sxs-lookup"><span data-stu-id="af9df-714">We fixed a print issue when sensitivity label with watermarks are applied.</span></span>


[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2011-october-16"></a><span data-ttu-id="af9df-716">Versión 2011: 16 de octubre</span><span class="sxs-lookup"><span data-stu-id="af9df-716">Version 2011: October 16</span></span>
<span data-ttu-id="af9df-717">*Versión 2011 (compilación 13408.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-717">*Version 2011 (Build 13408.20000)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-719">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-719">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-720">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-720">Excel</span></span>

- <span data-ttu-id="af9df-721">**Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="af9df-721">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="af9df-722">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-722">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a><span data-ttu-id="af9df-723">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-723">Outlook</span></span>

- <span data-ttu-id="af9df-724">**Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="af9df-724">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="af9df-725">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-725">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a><span data-ttu-id="af9df-726">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-726">PowerPoint</span></span>

- <span data-ttu-id="af9df-727">**Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="af9df-727">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="af9df-728">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-728">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="word"></a><span data-ttu-id="af9df-729">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-729">Word</span></span>

- <span data-ttu-id="af9df-730">**Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="af9df-730">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="af9df-731">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-731">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-734">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-734">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-735">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-735">Outlook</span></span>

- <span data-ttu-id="af9df-736">Se ha corregido un problema que impedía a los usuarios eliminar citas en el Calendario de Grupos de Microsoft 365 en autenticación básica.</span><span class="sxs-lookup"><span data-stu-id="af9df-736">We fixed an issue where users were unable to delete appointments in Calendar of Microsoft 365 Groups in Basic Auth.</span></span>


- <span data-ttu-id="af9df-737">Se ha corregido un problema que producía errores en el inicio de Outlook durante la carga de la caché de sobrenombres.</span><span class="sxs-lookup"><span data-stu-id="af9df-737">We fixed an issue where starting Outlook failed while loading nickname cache.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="af9df-738">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-738">PowerPoint</span></span>

- <span data-ttu-id="af9df-739">Se ha corregido un problema que provocaba que el icono del marcador de posición de contenido junto a Imágenes no incluyera información sobre herramientas.</span><span class="sxs-lookup"><span data-stu-id="af9df-739">We fixed an issue where in content placeholder icon next to Pictures didn't have a tooltip.</span></span>


- <span data-ttu-id="af9df-740">Se ha corregido un problema debido al cual la Vista protegida de presentación con diapositivas, mostrada en archivo PPTSX, permitía la captura de pantalla de documentos protegidos por IRM.</span><span class="sxs-lookup"><span data-stu-id="af9df-740">We have fixed an issue where Protected view of slide show, shown by pptsx file, allows screen capture of IRM protected document.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL FIN DE CONTENIDO)

## <a name="version-2011-october-09"></a><span data-ttu-id="af9df-742">Versión 2011: 09 de octubre</span><span class="sxs-lookup"><span data-stu-id="af9df-742">Version 2011: October 09</span></span>
<span data-ttu-id="af9df-743">*Versión 2011 (compilación 13406.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-743">*Version 2011 (Build 13406.20000)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-745">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-745">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-746">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-746">Excel</span></span>

- <span data-ttu-id="af9df-747">**Crear flujos de datos de Power Platform a partir de consultas:** ahora puede exportar sus consultas a plantillas de Power Query que se pueden usar para crear nuevos flujos de datos de Power Platform.</span><span class="sxs-lookup"><span data-stu-id="af9df-747">**Create Power Platform dataflows from queries:** You can now export your queries into Power Query templates that can be used to create new Power Platform dataflows</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-748">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-748">PowerPoint</span></span>

- <span data-ttu-id="af9df-749">**Exportar GIF animado en un rango:** seleccione un intervalo de diapositivas cuando exporte a GIF animado</span><span class="sxs-lookup"><span data-stu-id="af9df-749">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

- <span data-ttu-id="af9df-750">**Crear GIF con fondos transparentes:** cuando se exporta a un GIF animado, una nueva opción permite que el fondo sea transparente.</span><span class="sxs-lookup"><span data-stu-id="af9df-750">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-753">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-753">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-754">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-754">Excel</span></span>

- <span data-ttu-id="af9df-755">Se ha corregido un problema por el que el nombre de archivo no cambiaba después de una operación Guardar como con complementos COM habilitados.</span><span class="sxs-lookup"><span data-stu-id="af9df-755">We fixed an issue where  Filename was not changing after a SaveAs operation with COM add-ins enabled.</span></span>


- <span data-ttu-id="af9df-756">Se ha corregido un problema cuando se produce un error de Autoguardado con un mensaje de error incorrecto o engañoso cuando hay una definición de medida incorrecta en el modelo de datos de Excel.</span><span class="sxs-lookup"><span data-stu-id="af9df-756">We fixed an issue when Auto-Save fails with incorrect/misleading error message when there's a bad measure definition in the Excel data model.</span></span>


- <span data-ttu-id="af9df-757">Se ha corregido un problema en el que al acercar y alejar el área de presentación se daba una separación entre el recuadro de selección ampliado y el puntero del mouse.</span><span class="sxs-lookup"><span data-stu-id="af9df-757">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="outlook"></a><span data-ttu-id="af9df-758">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-758">Outlook</span></span>

- <span data-ttu-id="af9df-p136">Se ha corregido un problema por el que la impresión rápida de los datos adjuntos de imagen provocaba un error “Windows no puede encontrar esta imagen. Compruebe la ubicación y vuelva a intentarlo”.</span><span class="sxs-lookup"><span data-stu-id="af9df-p136">We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture. Check the location, and then try again".</span></span>


- <span data-ttu-id="af9df-761">Se ha corregido un problema que provocaba que algunos usuarios vieran que Outlook se iniciaba en un estado sin conexión hasta que optaban manualmente por trabajar en línea.</span><span class="sxs-lookup"><span data-stu-id="af9df-761">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="af9df-762">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-762">PowerPoint</span></span>

- <span data-ttu-id="af9df-763">Se ha corregido un problema que provocaba que, al acercar y alejar el área de presentación, apareciera una separación entre el recuadro de selección ampliado y el puntero del mouse.</span><span class="sxs-lookup"><span data-stu-id="af9df-763">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="project"></a><span data-ttu-id="af9df-764">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-764">Project</span></span>

- <span data-ttu-id="af9df-765">Se ha corregido un problema por el que la NewVal en el evento ProjectBeforeTaskChagne no tiene el valor correcto si se cambia un retraso en una vista de tipo de formulario de tarea.</span><span class="sxs-lookup"><span data-stu-id="af9df-765">Fixed an issue where the NewVal in the ProjectBeforeTaskChagne event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="af9df-766">Se ha corregido un problema que hace que si tiene una lista de tareas en un sitio de proyecto y agrupa la lista de tareas, no pueda editar rápidamente la lista de tareas.</span><span class="sxs-lookup"><span data-stu-id="af9df-766">Fixed an issue where if you have a task list in a project site and group the task list, you will not be able to quick edit the task list.</span></span>


- <span data-ttu-id="af9df-767">Se ha corregido un problema que hace que si actualiza un recurso de empresa a través del CSOM, puede perderse la capacidad máxima del recurso.</span><span class="sxs-lookup"><span data-stu-id="af9df-767">Fixed an issue where if you update an enterprise resource via CSOM, resource max units may be lost.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-768">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-768">Word</span></span>

- <span data-ttu-id="af9df-769">Se ha corregido un problema en el que al acercar y alejar el área de presentación se daba una separación entre el recuadro de selección ampliado y el puntero del mouse.</span><span class="sxs-lookup"><span data-stu-id="af9df-769">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="office-suite"></a><span data-ttu-id="af9df-770">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-770">Office Suite</span></span>

- <span data-ttu-id="af9df-771">Se ha corregido un problema por el que el inicio de sesión interactivo de la API de SSO devuelve un código de error.</span><span class="sxs-lookup"><span data-stu-id="af9df-771">We fixed an issue where SSO API interactive Sign-In was returning an error code.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO FINAL)

## <a name="version-2010-october-02"></a><span data-ttu-id="af9df-773">Versión 2010: 02 de octubre</span><span class="sxs-lookup"><span data-stu-id="af9df-773">Version 2010: October 02</span></span>
<span data-ttu-id="af9df-774">*Versión 2010 (Compilación 13328.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-774">*Version 2010 (Build 13328.20000)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-776">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-776">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-777">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-777">Excel</span></span>

- <span data-ttu-id="af9df-778">**Usar el cuadro de diálogo Opciones avanzadas para crear tipos de datos:** el cuadro de diálogo Opciones avanzadas le permite seleccionar manualmente las columnas que combinan el tipo de datos que está creando.</span><span class="sxs-lookup"><span data-stu-id="af9df-778">**Use the Advanced Dialog to Create Data Types:** The Advanced Dialog allows you to manually select the columns which combine the Data Type you are creating.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-781">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-781">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="af9df-782">OneNote</span><span class="sxs-lookup"><span data-stu-id="af9df-782">OneNote</span></span>

- <span data-ttu-id="af9df-783">Se ha corregido un problema que impedía al usuario seleccionar y copiar la dirección URL del bloc de notas del cuadro de texto en un archivo de OutSpace > Información.</span><span class="sxs-lookup"><span data-stu-id="af9df-783">We fixed an issue where a user was unable to select and copy notebook URL from textbox in OutSpace File > Info.</span></span>


### <a name="outlook"></a><span data-ttu-id="af9df-784">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-784">Outlook</span></span>

- <span data-ttu-id="af9df-785">Corrige un problema que causaba el envío de los mensajes de correo electrónico generados automáticamente con el cuerpo del correo en blanco cuando el asunto estaba vacío.</span><span class="sxs-lookup"><span data-stu-id="af9df-785">Addresses an issue that caused automatically generated emails to be sent with a blank body when the subject is blank.</span></span>


- <span data-ttu-id="af9df-786">Se ha corregido un problema que provocaba que se almacenara en caché para carpetas el GUID de carpeta incorrecto.</span><span class="sxs-lookup"><span data-stu-id="af9df-786">We fixed an issue where the wrong folder guid is cached for folders.</span></span>


- <span data-ttu-id="af9df-787">Cuando un usuario copia y pega una dirección de correo electrónico en el campo del destinatario con el nombre para mostrar, la dirección de correo electrónico no siempre se analizaba de forma correcta, y esto generaba que aparezca una advertencia sobre una dirección de correo electrónico no válida.</span><span class="sxs-lookup"><span data-stu-id="af9df-787">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="af9df-788">Se ha corregido y, por tanto, el nombre y la dirección de correo electrónico se analizan de forma correcta para que ya no se muestre la advertencia.</span><span class="sxs-lookup"><span data-stu-id="af9df-788">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


- <span data-ttu-id="af9df-789">Se ha corregido un problema que causaba que las carpetas compartidas en línea no devolvieran el nombre de la carpeta principal.</span><span class="sxs-lookup"><span data-stu-id="af9df-789">We fixed an issue where online shared folders did not return parent folder name.</span></span> <span data-ttu-id="af9df-790">En lugar de dar error, devolvía una ruta de acceso vacía que pasaba incorrectamente a la cuenta principal.</span><span class="sxs-lookup"><span data-stu-id="af9df-790">Intsead of failing, it returned an empty path which incorrectly went to the primary account.</span></span>


- <span data-ttu-id="af9df-791">Se ha corregido un problema que provocaba que se activara el control de cambios después de reabrir el borrador desde el panel de vista previa de solo lectura.</span><span class="sxs-lookup"><span data-stu-id="af9df-791">We fixed an issue where track changes turned on after reopening draft from read-only preview pane.</span></span>


- <span data-ttu-id="af9df-792">Se ha corregido un problema que impedía que la opción Guardar como estuviera disponible para los datos adjuntos clásicos.</span><span class="sxs-lookup"><span data-stu-id="af9df-792">We fixed an issue where the Save As option was not available for classic attachments.</span></span>


- <span data-ttu-id="af9df-793">Se ha corregido un problema para ofrecer a los usuarios una forma de personalizar el texto de justificación al anular una directiva.</span><span class="sxs-lookup"><span data-stu-id="af9df-793">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="af9df-794">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-794">PowerPoint</span></span>

- <span data-ttu-id="af9df-795">Se ha corregido un problema que impedía a PowerPoint exportar las viñetas rectangulares al exportar a PDF.</span><span class="sxs-lookup"><span data-stu-id="af9df-795">We fixed an issue where PowerPoint was not exporting rectangle bullet points while exporting to PDF.</span></span>


- <span data-ttu-id="af9df-796">Se ha corregido un problema debido al cual, si se encuentra en la última diapositiva y pasa a la siguiente diapositiva tras pulsar "Finalizar sesión" y antes de que aparezca el resumen, el cuadro de diálogo de sesión final también aparece visible en la página de resumen.</span><span class="sxs-lookup"><span data-stu-id="af9df-796">We fixed an issue that If you are on the last slide and if you swipe to the next slide after pressing 'End Session' and before the summary shows up, the End-Session dialog is visible on the summary page as well.</span></span>


### <a name="project"></a><span data-ttu-id="af9df-797">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-797">Project</span></span>

- <span data-ttu-id="af9df-798">Se ha corregido un problema que podía hacer que Project se bloqueara si aplicaba un grupo en la Vista de hoja o de uso de recursos y, a continuación, insertaba una columna.</span><span class="sxs-lookup"><span data-stu-id="af9df-798">Fixed an issue where Project may crash if you apply a group by to the Resource Usage or Sheet view and then insert a column.</span></span>


- <span data-ttu-id="af9df-799">Se ha corregido un problema debido al cual, si tiene campos personalizados con fórmulas que usan el valor acumulado, puede que observe que el rendimiento retrasa el cambio de vistas y la apertura de los detalles del proyecto/tarea.</span><span class="sxs-lookup"><span data-stu-id="af9df-799">Fixed an issue where if you have custom fields with formulas and are using earned value, you may notice performance delays switching views and opening project/task details.</span></span>


- <span data-ttu-id="af9df-800">Se ha corregido un problema que puede hacer que el método VBA ConsolidateProjects produzca errores si se intenta agregar el mismo proyecto varias veces y AttachToSources está establecido en false.</span><span class="sxs-lookup"><span data-stu-id="af9df-800">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="af9df-801">Se ha corregido un problema por el que si se ejecuta un código de evento y se intenta realizar cambios desde la vista del Formulario de tareas, es posible que el botón Aceptar no confirme los cambios.</span><span class="sxs-lookup"><span data-stu-id="af9df-801">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2010-september-25"></a><span data-ttu-id="af9df-803">Versión 2010: 25 de septiembre</span><span class="sxs-lookup"><span data-stu-id="af9df-803">Version 2010: September 25</span></span>
<span data-ttu-id="af9df-804">*Versión 2010 (Compilación 13318.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-804">*Version 2010 (Build 13318.20000)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-806">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-806">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-807">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-807">Excel</span></span>

- <span data-ttu-id="af9df-808">**Crear tipos de datos con Power Query:** crear tipos de datos enriquecidos con Power Query desde cualquier origen de datos</span><span class="sxs-lookup"><span data-stu-id="af9df-808">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-809">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-809">Outlook</span></span>

- <span data-ttu-id="af9df-810">**Actualizaciones de la experiencia de usuario en Tareas:** Una actualización visual de los elementos de las tareas</span><span class="sxs-lookup"><span data-stu-id="af9df-810">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

- <span data-ttu-id="af9df-811">**Ahorre tiempo mientras redacta mensajes:** Outlook le muestra sugerencias de escritura que le ayudarán a redactar mensajes de manera rápida.</span><span class="sxs-lookup"><span data-stu-id="af9df-811">**Save time while composing messages:** Outlook shows you writing suggestions that help you compose messages quickly.</span></span> <span data-ttu-id="af9df-812">Para aceptar la sugerencia, solo tiene que usar la tecla TAB.</span><span class="sxs-lookup"><span data-stu-id="af9df-812">To accept the suggestion, just use the Tab key.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-813">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-813">Word</span></span>

- <span data-ttu-id="af9df-814">**El panel del Editor Microsoft recibe una actualización en la versión de escritorio de Word:** Hemos actualizado la experiencia actual con el panel del Editor para los clientes de escritorio de Word.</span><span class="sxs-lookup"><span data-stu-id="af9df-814">**Microsoft Editor pane gets an update in Word for desktop:** We have upgraded the current experience with the Editor pane in Word for desktop clients.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-817">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-817">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="af9df-818">Access</span><span class="sxs-lookup"><span data-stu-id="af9df-818">Access</span></span>

- <span data-ttu-id="af9df-819">Se ha corregido un problema que provocaba que la posición de la barra de desplazamiento no se estableciera de manera correcta al cargar la ventana de consulta o relación guardada mientras se realizaba el desplazamiento.</span><span class="sxs-lookup"><span data-stu-id="af9df-819">We fixed an issue where scrollbar position was not set correctly when loading query/relationship window saved while scrolled.</span></span>


- <span data-ttu-id="af9df-820">Se ha corregido un problema que provocaba que el panel de tareas de Agregar tabla no mostrara de manera correcta los nombres que contenían "&".</span><span class="sxs-lookup"><span data-stu-id="af9df-820">We fixed an issue where Add Table Task Pane was not displaying names containing '&' correctly.</span></span>


### <a name="excel"></a><span data-ttu-id="af9df-821">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-821">Excel</span></span>

- <span data-ttu-id="af9df-822">Se ha corregido un problema que provocaba que el intervalo manual de categoría multinivel no funcionara en los gráficos.</span><span class="sxs-lookup"><span data-stu-id="af9df-822">We fixed an issue where multi-level category manual interval was not working in charts.</span></span>


- <span data-ttu-id="af9df-823">Se ha corregido un problema que podía provocar un bloqueo al actualizar las tablas dinámicas de OLAP.</span><span class="sxs-lookup"><span data-stu-id="af9df-823">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="af9df-824">Se ha corregido un problema que provocaba que no se actualizaran las opciones de todas las hojas del libro al agregar una tabla usada para la validación de datos.</span><span class="sxs-lookup"><span data-stu-id="af9df-824">We fixed an issue where adding to a table used for Data Validation did not update options for all sheets in the workbook.</span></span>


### <a name="onenote"></a><span data-ttu-id="af9df-825">OneNote</span><span class="sxs-lookup"><span data-stu-id="af9df-825">OneNote</span></span>

- <span data-ttu-id="af9df-826">Se ha corregido un problema que provocaba que OneNote no respetara los colores de contraste alto en el lienzo para temas personalizados.</span><span class="sxs-lookup"><span data-stu-id="af9df-826">We fixed an issue where OneNote didn't honor High Contrast colors in the canvas for custom themes.</span></span>


- <span data-ttu-id="af9df-827">Se ha corregido un problema que provocaba que, al pasar el ratón sobre el color verde en el selector de colores del bloc de notas, el elemento emergente muestre "tiza roja".</span><span class="sxs-lookup"><span data-stu-id="af9df-827">We fixed an issue when you hover over green color in notebook color selector, the pop up reads "red chalk".</span></span>


### <a name="powerpoint"></a><span data-ttu-id="af9df-828">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-828">PowerPoint</span></span>

- <span data-ttu-id="af9df-829">Se ha corregido un problema que provocaba que el gráfico de Excel vinculado cambiara incorrectamente a la hoja de Excel cuando el usuario cambiaba la ruta de origen a la carpeta de OneDrive local.</span><span class="sxs-lookup"><span data-stu-id="af9df-829">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-830">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-830">Word</span></span>

- <span data-ttu-id="af9df-831">Se ha corregido un problema que provocaba que los vínculos a los archivos habilitados de flujo de trabajo no se abrieran con normalidad.</span><span class="sxs-lookup"><span data-stu-id="af9df-831">We fixed an issue where links to workflow enabled files were not opening as expected.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2010-september-18"></a><span data-ttu-id="af9df-833">Versión 2010:18 de septiembre</span><span class="sxs-lookup"><span data-stu-id="af9df-833">Version 2010: September 18</span></span>
<span data-ttu-id="af9df-834">*Versión 2010 (compilación 13312.20006)*</span><span class="sxs-lookup"><span data-stu-id="af9df-834">*Version 2010 (Build 13312.20006)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-836">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-836">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-837">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-837">Outlook</span></span>

- <span data-ttu-id="af9df-838">**Revisar los mensajes con el editor:** Ahora puede obtener sugerencias de gramática y de estilo en los mensajes de correo electrónico de los usuarios de 64 bits de Outlook.</span><span class="sxs-lookup"><span data-stu-id="af9df-838">**Proofread your messages with Editor:** You can now get grammar and other style suggestions in your emails for Outlook 64-bit users.</span></span> <span data-ttu-id="af9df-839">Busque las palabras subrayadas para ver las sugerencias del editor para refinar su escritura.</span><span class="sxs-lookup"><span data-stu-id="af9df-839">Look for underlined words to see Editor’s suggestions to refine your writing.</span></span>

- <span data-ttu-id="af9df-840">**Rompa la barrera del idioma con un traductor incorporado:** Los complementos para la traducción ya no son necesarios.</span><span class="sxs-lookup"><span data-stu-id="af9df-840">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="af9df-841">En un mensaje, haga clic con el botón derecho para traducir palabras o frases específicas, o todo el mensaje.</span><span class="sxs-lookup"><span data-stu-id="af9df-841">In a message, right-click to translate specific words, phrases, or the whole message.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-844">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-844">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-845">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-845">Excel</span></span>

- <span data-ttu-id="af9df-846">Se ha corregido un problema con los gráficos de mapas 2D que provocaba que el uso de VBA para establecer los colores de los valores max, mid y min para una serie no funcione.</span><span class="sxs-lookup"><span data-stu-id="af9df-846">Fixed an issue with 2D Map Charts where using VBA to set the colors for the max, mid, and min values for a series was not working.</span></span>


- <span data-ttu-id="af9df-847">Se ha corregido un problema que aparecía cuando se configuraba el idioma de Office en español. Este problema provocaba que las listas de validación de datos puedan no mostrar todos los elementos de la lista.</span><span class="sxs-lookup"><span data-stu-id="af9df-847">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="af9df-848">Se ha corregido un problema que podría provocar un error que indicaba que Excel se quedó sin recursos al intentar calcular una o varias fórmulas.</span><span class="sxs-lookup"><span data-stu-id="af9df-848">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="af9df-849">Se ha corregido un problema que provocaba que ChartSheet se bloquee en ciertos casos cuando se insertaba una fórmula en la barra de fórmulas.</span><span class="sxs-lookup"><span data-stu-id="af9df-849">Fixed an issue where ChartSheet crashed in some cases when a formula is entered through formula bar.</span></span>


### <a name="outlook"></a><span data-ttu-id="af9df-850">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-850">Outlook</span></span>

- <span data-ttu-id="af9df-851">Cuando un usuario copia y pega una dirección de correo electrónico en el campo del destinatario con el nombre para mostrar, la dirección de correo electrónico no siempre se analizaba de forma correcta, y esto generaba que aparezca una advertencia sobre una dirección de correo electrónico no válida.</span><span class="sxs-lookup"><span data-stu-id="af9df-851">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="af9df-852">Se ha corregido y, por tanto, el nombre y la dirección de correo electrónico se analizan de forma correcta para que ya no se muestre la advertencia.</span><span class="sxs-lookup"><span data-stu-id="af9df-852">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


### <a name="word"></a><span data-ttu-id="af9df-853">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-853">Word</span></span>

- <span data-ttu-id="af9df-854">Se ha corregido un problema que provocaba que el hecho que un usuario seleccionara una marca de revisión (inserción o eliminación) mostrara un comentario emergente.</span><span class="sxs-lookup"><span data-stu-id="af9df-854">Fixed an issue where a user tapping on a tracked change (insertion/deletion) would bring up a comment pop-out.</span></span>


- <span data-ttu-id="af9df-855">Se ha corregido un problema al eliminar llamadas de comentario en Word.</span><span class="sxs-lookup"><span data-stu-id="af9df-855">We fixed an issue with deleting comment callouts in Word.</span></span>


- <span data-ttu-id="af9df-856">Se ha corregido un problema con Outlook al establecer un mensaje en No reenviar</span><span class="sxs-lookup"><span data-stu-id="af9df-856">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="af9df-857">Se ha corregido un problema al guardar un documento de Word que contenía cita y ecuación.</span><span class="sxs-lookup"><span data-stu-id="af9df-857">We fixed an issue with saving Word document that contains citation and equation.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2010-september-11"></a><span data-ttu-id="af9df-859">Versión 2010: 11 de septiembre</span><span class="sxs-lookup"><span data-stu-id="af9df-859">Version 2010: September 11</span></span>
<span data-ttu-id="af9df-860">*Versión 2010 (Compilación 13304.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-860">*Version 2010 (Build 13304.20000)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-862">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-862">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="af9df-863">Acceso</span><span class="sxs-lookup"><span data-stu-id="af9df-863">Access</span></span>

- <span data-ttu-id="af9df-864">**Office puede seguir con la configuración de modo oscuro de Windows 10:** ¿Usa Windows 10 en modo oscuro?</span><span class="sxs-lookup"><span data-stu-id="af9df-864">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="af9df-865">Ahora Office puede cambiar entre temas de modo que coincidan de manera automática: Solo seleccione "Usar configuración del sistema" como tema de Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-865">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="excel"></a><span data-ttu-id="af9df-866">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-866">Excel</span></span>

- <span data-ttu-id="af9df-867">**Office puede seguir con la configuración de modo oscuro de Windows 10:** ¿Usa Windows 10 en modo oscuro?</span><span class="sxs-lookup"><span data-stu-id="af9df-867">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="af9df-868">Ahora Office puede cambiar entre temas de modo que coincidan de manera automática: Solo seleccione "Usar configuración del sistema" como tema de Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-868">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="onenote"></a><span data-ttu-id="af9df-869">OneNote</span><span class="sxs-lookup"><span data-stu-id="af9df-869">OneNote</span></span>

- <span data-ttu-id="af9df-870">**Office puede seguir con la configuración de modo oscuro de Windows 10:** ¿Usa Windows 10 en modo oscuro?</span><span class="sxs-lookup"><span data-stu-id="af9df-870">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="af9df-871">Ahora Office puede cambiar entre temas de modo que coincidan de manera automática: Solo seleccione "Usar configuración del sistema" como tema de Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-871">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-872">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-872">Outlook</span></span>

- <span data-ttu-id="af9df-873">**Office puede seguir con la configuración de modo oscuro de Windows 10:** ¿Usa Windows 10 en modo oscuro?</span><span class="sxs-lookup"><span data-stu-id="af9df-873">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="af9df-874">Ahora Office puede cambiar entre temas de modo que coincidan de manera automática: Solo seleccione "Usar configuración del sistema" como tema de Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-874">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-875">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-875">PowerPoint</span></span>

- <span data-ttu-id="af9df-876">**Office puede seguir con la configuración de modo oscuro de Windows 10:** ¿Usa Windows 10 en modo oscuro?</span><span class="sxs-lookup"><span data-stu-id="af9df-876">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="af9df-877">Ahora Office puede cambiar entre temas de modo que coincidan de manera automática: Solo seleccione "Usar configuración del sistema" como tema de Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-877">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-878">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-878">Project</span></span>

- <span data-ttu-id="af9df-879">**Office puede seguir con la configuración de modo oscuro de Windows 10:** ¿Usa Windows 10 en modo oscuro?</span><span class="sxs-lookup"><span data-stu-id="af9df-879">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="af9df-880">Ahora Office puede cambiar entre temas de modo que coincidan de manera automática: Solo seleccione "Usar configuración del sistema" como tema de Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-880">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="publisher"></a><span data-ttu-id="af9df-881">Publisher</span><span class="sxs-lookup"><span data-stu-id="af9df-881">Publisher</span></span>

- <span data-ttu-id="af9df-882">**Office puede seguir con la configuración de modo oscuro de Windows 10:** ¿Usa Windows 10 en modo oscuro?</span><span class="sxs-lookup"><span data-stu-id="af9df-882">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="af9df-883">Ahora Office puede cambiar entre temas de modo que coincidan de manera automática: Solo seleccione "Usar configuración del sistema" como tema de Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-883">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="visio"></a><span data-ttu-id="af9df-884">Visio</span><span class="sxs-lookup"><span data-stu-id="af9df-884">Visio</span></span>

- <span data-ttu-id="af9df-885">**Office puede seguir con la configuración de modo oscuro de Windows 10:** ¿Usa Windows 10 en modo oscuro?</span><span class="sxs-lookup"><span data-stu-id="af9df-885">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="af9df-886">Ahora Office puede cambiar entre temas de modo que coincidan de manera automática: Solo seleccione "Usar configuración del sistema" como tema de Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-886">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-887">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-887">Word</span></span>

- <span data-ttu-id="af9df-888">**Office puede seguir con la configuración de modo oscuro de Windows 10:** ¿Usa Windows 10 en modo oscuro?</span><span class="sxs-lookup"><span data-stu-id="af9df-888">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="af9df-889">Ahora Office puede cambiar entre temas de modo que coincidan de manera automática: Solo seleccione "Usar configuración del sistema" como tema de Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-889">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-892">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-892">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-893">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-893">Excel</span></span>

- <span data-ttu-id="af9df-894">Se ha corregido un problema que provocaba un retraso considerable al cambiar entre hojas de cálculo con grandes cantidades de datos cuando la 'Vista previa de salto de página' estaba habilitada.</span><span class="sxs-lookup"><span data-stu-id="af9df-894">Fixed an issue where there could be a noticeable delay when switching between worksheets with large amounts of data when 'Page Break Preview' was enabled.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-895">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-895">Outlook</span></span>

- <span data-ttu-id="af9df-896">Se ha corregido un problema que provocaba que los correos electrónicos se ocultaran después de desactivar la Bandeja de entrada Prioritarios y ordenarlos.</span><span class="sxs-lookup"><span data-stu-id="af9df-896">We fixed an issue with emails being hidden after turning Focused Inbox off and doing a sort.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-897">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-897">PowerPoint</span></span>

- <span data-ttu-id="af9df-898">Se ha corregido un problema que provocaba que los GIF solo muestren la animación una vez en el editor y en las presentaciones.</span><span class="sxs-lookup"><span data-stu-id="af9df-898">We fixed an issue where GIF's would animate only once in the editor and slide shows.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2010-september-04"></a><span data-ttu-id="af9df-900">Versión 2010: 04 de septiembre </span><span class="sxs-lookup"><span data-stu-id="af9df-900">Version 2010: September 04</span></span>
<span data-ttu-id="af9df-901">*Versión 2010 (Compilación 13301.20004)*</span><span class="sxs-lookup"><span data-stu-id="af9df-901">*Version 2010 (Build 13301.20004)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-903">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-903">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-904">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-904">Outlook</span></span>

- <span data-ttu-id="af9df-905">**Anclar correo electrónico:** esta característica permite a los usuarios realizar un seguimiento de los correos electrónicos a los que necesitan volver o tenerlos como recordatorio manteniéndolos en la parte superior de la lista de mensajes.</span><span class="sxs-lookup"><span data-stu-id="af9df-905">**Pinning email:** This feature helps users keep track of mails they need to go back to you or have as a reminder by keeping them at the top of the message list.</span></span>

- <span data-ttu-id="af9df-906">**Reciba sugerencias de correo electrónico al buscar por persona:** a medida que escriba los términos de búsqueda en Outlook, recibirá los correos electrónicos más relevantes en las sugerencias.</span><span class="sxs-lookup"><span data-stu-id="af9df-906">**Receive email suggestions when searching by person:** As you type your search terms in Outlook, you'll receive the most relevant emails surfaced in the suggestions.</span></span>

- <span data-ttu-id="af9df-907">**Reciba sugerencias de correo electrónico al buscar por persona:** a medida que escriba los términos de búsqueda en Outlook, recibirá los correos electrónicos más relevantes en las sugerencias.</span><span class="sxs-lookup"><span data-stu-id="af9df-907">**Receive email suggestions when searching by person:** As you type your search terms in Outlook, you'll receive the most relevant emails surfaced in the suggestions.</span></span>

- <span data-ttu-id="af9df-908">**Microsoft Editor proporciona una actualización para los clientes de escritorio de Word y Outlook:** añadimos un nuevo modelo de revisión con un clic para las sugerencias de estilo, gramática y ortografía avanzada del Editor.</span><span class="sxs-lookup"><span data-stu-id="af9df-908">**Microsoft Editor gets an upgrade for Word and Outlook desktop clients:** We are introducing a new click-to-review model for Editor's spelling ,grammar and advanced style suggestions.</span></span> <span data-ttu-id="af9df-909">Este cambio también incluye una nueva superficie de tarjeta dedicada para revisar las sugerencias.</span><span class="sxs-lookup"><span data-stu-id="af9df-909">This change also includes a new dedicated card surface for reviewing the suggestions.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-910">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-910">Word</span></span>

- <span data-ttu-id="af9df-911">**Microsoft Editor proporciona una actualización para los clientes de escritorio de Word y Outlook:** añadimos un nuevo modelo de revisión con un clic para las sugerencias de estilo, gramática y ortografía avanzada del Editor.</span><span class="sxs-lookup"><span data-stu-id="af9df-911">**Microsoft Editor gets an upgrade for Word and Outlook desktop clients:** We are introducing a new click-to-review model for Editor's spelling ,grammar and advanced style suggestions.</span></span> <span data-ttu-id="af9df-912">Este cambio también incluye una nueva superficie de tarjeta dedicada para revisar las sugerencias.</span><span class="sxs-lookup"><span data-stu-id="af9df-912">This change also includes a new dedicated card surface for reviewing the suggestions.</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-915">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-915">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-916">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-916">Excel</span></span>

- <span data-ttu-id="af9df-917">Se corrigió un problema por el cual si abría un archivo que contiene la función LET, mostraba la alerta: "Encontramos un problema con el contenido en "su archivo.xlsx".</span><span class="sxs-lookup"><span data-stu-id="af9df-917">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="af9df-918">¿Quiere que intentemos recuperar todo lo que podamos?</span><span class="sxs-lookup"><span data-stu-id="af9df-918">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="af9df-919">Si confía en el origen de este libro, haga clic en Sí".</span><span class="sxs-lookup"><span data-stu-id="af9df-919">If you trust the source of this workbook, click Yes".</span></span>
- <span data-ttu-id="af9df-920">Se corrigió un bloqueo relacionado con las referencias de complementos XLAM y los rangos con nombre.</span><span class="sxs-lookup"><span data-stu-id="af9df-920">We fixed a crash related to XLAM add-in references and named ranges.</span></span>
- <span data-ttu-id="af9df-921">Se corrigió un problema por el cual los usuarios no podían modificar un filtro de tabla dinámica porque estaba configurado en un valor que ya no estaba presente en una base de datos de Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="af9df-921">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>
- <span data-ttu-id="af9df-p155">Se corrigió un problema por el que si un usuario aplicaba un estilo personalizado a una matriz dinámica, obtenía el error: "No se puede cambiar parte de una matriz". Se ha eliminado una restricción heredada.</span><span class="sxs-lookup"><span data-stu-id="af9df-p155">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array". This was a legacy restriction that has been removed.</span></span>
- <span data-ttu-id="af9df-924">Se corrigió un problema por el cual la barra de fórmulas de Excel no se mostraba completamente después de que se perdiera la conexión a un dispositivo, como una conexión o desconexión de sesión remota o un cambio de monitor.</span><span class="sxs-lookup"><span data-stu-id="af9df-924">We fixed an issue where the Excel formula bar would not render completely after connection to a device was lost, such as a remote session connect/disconnect or a monitor change.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-925">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-925">Outlook</span></span>

- <span data-ttu-id="af9df-926">Se corrigió un problema que proporciona más flexibilidad para habilitar o deshabilitar las opciones de registro predeterminadas mediante la directiva de grupo.</span><span class="sxs-lookup"><span data-stu-id="af9df-926">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>
- <span data-ttu-id="af9df-927">Se corrigió un problema por el que el nombre de dominio heredado de un remitente de correo electrónico se conservaba y mostraba después de que se moviera un borrador del correo electrónico entre buzones con permisos de asistente y permisos de administrador.</span><span class="sxs-lookup"><span data-stu-id="af9df-927">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>
- <span data-ttu-id="af9df-928">Se corrigió un problema que hacía que algunos usuarios vieran que Outlook se iniciaba en un estado sin conexión hasta que optaban manualmente por trabajar en línea.</span><span class="sxs-lookup"><span data-stu-id="af9df-928">We fixed an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>
- <span data-ttu-id="af9df-929">Se corrigió un problema por el cual ejecutar el código VBA ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") después de habilitar Cinta de opciones de una línea (SLR) daba como resultado un error de tiempo de ejecución.</span><span class="sxs-lookup"><span data-stu-id="af9df-929">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>
- <span data-ttu-id="af9df-930">Se corrigió un problema por el cual los botones 'Aceptar' y 'Cancelar' en el cuadro de diálogo Respuestas automáticas no eran visibles en un sistema con una resolución alta (como 1750 x 1920) combinada con un tamaño de texto grande (como 175 %).</span><span class="sxs-lookup"><span data-stu-id="af9df-930">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>
- <span data-ttu-id="af9df-931">Se corrigió una condición por la que enviar una convocatoria de reunión desde un grupo de contactos vacío a otro grupo de contactos provocaba un bloqueo.</span><span class="sxs-lookup"><span data-stu-id="af9df-931">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>
- <span data-ttu-id="af9df-932">Se corrigió un problema que provocaba que los usuarios experimentaran un bloqueo al abrir algunos correos electrónicos muy grandes.</span><span class="sxs-lookup"><span data-stu-id="af9df-932">We fixed an issue that caused users to experience a crash when opening certain very large emails.</span></span>
- <span data-ttu-id="af9df-933">Se corrigió un problema por el que si la directiva de grupo requiere que un complemento esté siempre habilitado, los complementos de supervisión no están disponibles para evitar que los usuarios deshabiliten el complemento.</span><span class="sxs-lookup"><span data-stu-id="af9df-933">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-934">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-934">PowerPoint</span></span>

- <span data-ttu-id="af9df-935">Se corrigió un problema por el que los vídeos no se reproducen automáticamente en las presentaciones.</span><span class="sxs-lookup"><span data-stu-id="af9df-935">We fixed an issue where videos were not playing automatically in slideshows.</span></span>
- <span data-ttu-id="af9df-936">Se corrigió un problema por el cual, después de iniciar PowerPoint, insertar una diapositiva y abrir y cerrar el panel de comentarios, las diapositivas en el panel de miniaturas se mostraban superpuestas.</span><span class="sxs-lookup"><span data-stu-id="af9df-936">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-937">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-937">Project</span></span>

- <span data-ttu-id="af9df-938">Se corrigió un problema por el cual si un recurso tiene varias tablas de tasas de coste, es posible que el coste restante no se calcule correctamente.</span><span class="sxs-lookup"><span data-stu-id="af9df-938">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>
- <span data-ttu-id="af9df-939">Se corrigió un problema por el que la fecha de finalización de Project no se actualizaba para los proyectos conectados a la lista de tareas de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="af9df-939">We fixed an issue where the Project finish date wasn't getting updated for projects connected to SharePoint tasks list.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-940">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-940">Word</span></span>

- <span data-ttu-id="af9df-941">Se corrigió un problema por el cual la tarjeta de Comentarios mostraba un borde alrededor del texto del comentario si el usuario hacía clic en el comentario.</span><span class="sxs-lookup"><span data-stu-id="af9df-941">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>
- <span data-ttu-id="af9df-942">Se corrigió un problema por el cual el foco no iba al panel de comentarios si el documento se ampliaba al 160 % o más y el panel de comentarios no estaba visible.</span><span class="sxs-lookup"><span data-stu-id="af9df-942">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>
- <span data-ttu-id="af9df-943">Se corrigió un problema por el cual los comentarios de un documento se mostraban en otros documentos abiertos después de cambiar entre varios documentos abiertos.</span><span class="sxs-lookup"><span data-stu-id="af9df-943">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>
- <span data-ttu-id="af9df-944">Se corrigió un problema por el cual si un usuario creaba un borrador de comentario anclado a una línea que ya contenía comentarios comprometidos, el borrador se organizaba en el orden incorrecto en relación con el comentario comprometido en SideTrack.</span><span class="sxs-lookup"><span data-stu-id="af9df-944">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>
- <span data-ttu-id="af9df-945">Se corrigió un problema por el cual los vínculos largos no se ajustaban al guardar un documento en formato HTML.</span><span class="sxs-lookup"><span data-stu-id="af9df-945">We fixed an issue where long links were not being wrapped when saving a document to HTML format.</span></span>
- <span data-ttu-id="af9df-946">Se corrigió un problema con las macros en las que AutoOpen se ejecuta antes de AutoExec.</span><span class="sxs-lookup"><span data-stu-id="af9df-946">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2009-august-28"></a><span data-ttu-id="af9df-948">Versión 2009: 28 de agosto</span><span class="sxs-lookup"><span data-stu-id="af9df-948">Version 2009: August 28</span></span>
<span data-ttu-id="af9df-949">*Versión 2009 (compilación 13219.20004)*</span><span class="sxs-lookup"><span data-stu-id="af9df-949">*Version 2009 (Build 13219.20004)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-951">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-951">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-952">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-952">Outlook</span></span>

- <span data-ttu-id="af9df-953">Resuelve un problema debido al cual los usuarios podían enviar contenido de correo electrónico que incluía una directiva de "No reenviar" aplicada a OneNote al seleccionar más de un mensaje.</span><span class="sxs-lookup"><span data-stu-id="af9df-953">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-954">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-954">PowerPoint</span></span>

- <span data-ttu-id="af9df-955">Hemos corregido un problema que deshabilitaba la funcionalidad para insertar un vídeo.</span><span class="sxs-lookup"><span data-stu-id="af9df-955">We fixed an issue where the functionality to insert a video was disabled.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-956">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-956">Word</span></span>

- <span data-ttu-id="af9df-957">Hemos corregido un problema que impedía al usuario salir del encabezado o pie de página al seleccionar un comentario.</span><span class="sxs-lookup"><span data-stu-id="af9df-957">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>
- <span data-ttu-id="af9df-958">Hemos corregido un problema que impedía a los usuarios ver los hilos de comentarios que superaran el límite de la barra de los comentarios, porque el desplazamiento por dicha barra no funcionaba.</span><span class="sxs-lookup"><span data-stu-id="af9df-958">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>
- <span data-ttu-id="af9df-959">Hemos corregido un problema que impedía la búsqueda de comentarios resueltos en el panel de los comentarios.</span><span class="sxs-lookup"><span data-stu-id="af9df-959">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>

### <a name="office-suite"></a><span data-ttu-id="af9df-960">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-960">Office Suite</span></span>

- <span data-ttu-id="af9df-961">Se ha corregido un problema en la Herramienta de implementación de Office que provocaba errores en la configuración al usar la característica RemoveMSI con el producto de Office 2007 "Informes de errores de aplicaciones de Microsoft".</span><span class="sxs-lookup"><span data-stu-id="af9df-961">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>
- <span data-ttu-id="af9df-962">Se ha corregido un problema en el cuadro de diálogo Comprimir imágenes que impedía que se conservaran algunas opciones de configuración de PPP seleccionadas por el usuario.</span><span class="sxs-lookup"><span data-stu-id="af9df-962">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>

[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2009-august-21"></a><span data-ttu-id="af9df-964">Versión 2009: 21 de agosto</span><span class="sxs-lookup"><span data-stu-id="af9df-964">Version 2009: August 21</span></span>
<span data-ttu-id="af9df-965">*Versión 2009 (Compilación 13212.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-965">*Version 2009 (Build 13212.20000)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-967">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-967">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-968">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-968">Excel</span></span>

- <span data-ttu-id="af9df-969">**Lápiz de acción en Excel:** herramienta bolígrafo que le ayudará a escribir a mano y realizar cambios rápidos en los datos</span><span class="sxs-lookup"><span data-stu-id="af9df-969">**Action Pen in Excel:** Pen Tool to help you handwrite and make quick edits to your data</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-970">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-970">Outlook</span></span>

- <span data-ttu-id="af9df-971">**Eliminar conversación por propietario del mensaje:** esta característica permite eliminar una conversación por propietario del mensaje.</span><span class="sxs-lookup"><span data-stu-id="af9df-971">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-974">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-974">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="af9df-975">Access</span><span class="sxs-lookup"><span data-stu-id="af9df-975">Access</span></span>

- <span data-ttu-id="af9df-976">Se ha corregido un problema por el que las conexiones a una base de datos ODBC no funcionaban con aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="af9df-976">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>

### <a name="excel"></a><span data-ttu-id="af9df-977">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-977">Excel</span></span>

- <span data-ttu-id="af9df-978">Se ha corregido un problema por el que, al usar una macro para establecer la propiedad FormulaR1C1 para un rango, las referencias de celda eran incorrectas si una hoja de gráfico era la hoja activa.</span><span class="sxs-lookup"><span data-stu-id="af9df-978">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>
- <span data-ttu-id="af9df-979">Se ha corregido un problema por el que las entradas manuscritas podrían hacer que Excel dejara de responder.</span><span class="sxs-lookup"><span data-stu-id="af9df-979">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-980">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-980">Outlook</span></span>

- <span data-ttu-id="af9df-981">Se ha corregido un problema por el que los usuarios ahora pueden deshabilitar IRM (Information Rights Management) para Outlook sin tener que deshabilitarlo para el resto de las aplicaciones de Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-981">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-982">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-982">Word</span></span>

- <span data-ttu-id="af9df-983">Se ha corregido un problema en el que Word se podía bloquear después de eliminar comentarios.</span><span class="sxs-lookup"><span data-stu-id="af9df-983">We fixed an issue where Word could crash after comments were deleted.</span></span>
- <span data-ttu-id="af9df-984">Se ha corregido un problema en el que, en algunos casos, las viñetas no se mostraban correctamente en el correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="af9df-984">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2009-august-14"></a><span data-ttu-id="af9df-986">Versión 2009: 14 de agosto</span><span class="sxs-lookup"><span data-stu-id="af9df-986">Version 2009: August 14</span></span>
<span data-ttu-id="af9df-987">*Versión 2009 (Compilación 13205.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-987">*Version 2009 (Build 13205.20000)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-989">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-989">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-990">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-990">Excel</span></span>

- <span data-ttu-id="af9df-991">Hemos corregido un problema en el que si un usuario escribía el nombre de una fórmula, incluidos los paréntesis, e invocaba ayuda a través de F1, el tema de ayuda específico de esa fórmula no se mostraba.</span><span class="sxs-lookup"><span data-stu-id="af9df-991">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>
- <span data-ttu-id="af9df-992">Se ha corregido un problema en el que los macros asignados a los botones no funcionaban después de restaurar una versión anterior del archivo.</span><span class="sxs-lookup"><span data-stu-id="af9df-992">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-993">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-993">Outlook</span></span>

- <span data-ttu-id="af9df-994">Este cambio corrige un problema que hace que la página de Reunión continuara mostrándose después de que el usuario había cambiado de pestaña desde la página Reunión a la página del Asistente para programación.</span><span class="sxs-lookup"><span data-stu-id="af9df-994">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-995">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-995">Word</span></span>

- <span data-ttu-id="af9df-996">Hemos corregido un problema en el que el icono de la imagen de viñeta no se mostraba correctamente.</span><span class="sxs-lookup"><span data-stu-id="af9df-996">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2009-august-07"></a><span data-ttu-id="af9df-998">Versión 2009: 07 de agosto</span><span class="sxs-lookup"><span data-stu-id="af9df-998">Version 2009: August 07</span></span>
<span data-ttu-id="af9df-999">*Versión 2009 (compilación 13130.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-999">*Version 2009 (Build 13130.20000)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1001">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1001">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-1002">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1002">Outlook</span></span>

- <span data-ttu-id="af9df-1003">Se ha corregido un problema que provocaba que los atributos de la cuenta de usuario de Active Directory para "otherTelephone" y "otherHomePhone" no se asignaran a los atributos LDAP correspondientes de Outlook.</span><span class="sxs-lookup"><span data-stu-id="af9df-1003">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1004">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1004">PowerPoint</span></span>

- <span data-ttu-id="af9df-1005">Se ha corregido un problema que provocaba que los usuarios no pudieran ver la barra de herramientas o de título en ciertas condiciones.</span><span class="sxs-lookup"><span data-stu-id="af9df-1005">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-july-31"></a><span data-ttu-id="af9df-1007">Versión 2008: 31 de julio</span><span class="sxs-lookup"><span data-stu-id="af9df-1007">Version 2008: July 31</span></span>
<span data-ttu-id="af9df-1008">*Versión 2008 (Compilación 13127.20002)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1008">*Version 2008 (Build 13127.20002)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-1010">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-1010">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-1011">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1011">Excel</span></span>

- <span data-ttu-id="af9df-1012">**Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-1012">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="af9df-1013">No es necesario realizar ninguna conversión.</span><span class="sxs-lookup"><span data-stu-id="af9df-1013">No conversion required.</span></span><br /><span data-ttu-id="af9df-1014">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="af9df-1014">See details in [blog post](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1015">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1015">Outlook</span></span>

- <span data-ttu-id="af9df-1016">**Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-1016">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="af9df-1017">No es necesario realizar ninguna conversión.</span><span class="sxs-lookup"><span data-stu-id="af9df-1017">No conversion required.</span></span><br /><span data-ttu-id="af9df-1018">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="af9df-1018">See details in [blog post](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1019">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1019">PowerPoint</span></span>

- <span data-ttu-id="af9df-1020">**Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-1020">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="af9df-1021">No es necesario realizar ninguna conversión.</span><span class="sxs-lookup"><span data-stu-id="af9df-1021">No conversion required.</span></span><br /><span data-ttu-id="af9df-1022">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="af9df-1022">See details in [blog post](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1023">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1023">Word</span></span>

- <span data-ttu-id="af9df-1024">**Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-1024">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="af9df-1025">No es necesario realizar ninguna conversión.</span><span class="sxs-lookup"><span data-stu-id="af9df-1025">No conversion required.</span></span><br /><span data-ttu-id="af9df-1026">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="af9df-1026">See details in [blog post](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1029">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1029">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="af9df-1030">Access</span><span class="sxs-lookup"><span data-stu-id="af9df-1030">Access</span></span>

- <span data-ttu-id="af9df-1031">Esta corrección resuelve el problema en el que al intentar ejecutar determinadas consultas anteriormente se generaba el mensaje de error "La consulta es demasiado compleja".</span><span class="sxs-lookup"><span data-stu-id="af9df-1031">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex.'</span></span>

### <a name="excel"></a><span data-ttu-id="af9df-1032">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1032">Excel</span></span>

- <span data-ttu-id="af9df-1033">Se ha corregido un problema por el que si se cambia el orden de una serie de gráficos, la casilla de verificación correspondiente alineada con la serie no se reordenaba junto con la serie.</span><span class="sxs-lookup"><span data-stu-id="af9df-1033">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>
- <span data-ttu-id="af9df-1034">Se ha corregido un problema por el que una copia de una imagen con un relleno degradado radial no coincidía con el original.</span><span class="sxs-lookup"><span data-stu-id="af9df-1034">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1035">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1035">Outlook</span></span>

- <span data-ttu-id="af9df-1036">Esta corrección aborda un problema que hacía que los usuarios no pudieran agregar una firma al responder a un mensaje administrado con derechos digitales desde una ventana de inspección cuando el usuario no tenía permisos de propietario sobre el mensaje al que se respondía.</span><span class="sxs-lookup"><span data-stu-id="af9df-1036">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>
- <span data-ttu-id="af9df-1037">La corrección aborda un problema que provocaba que Outlook no mostrara correctamente los saltos de línea en el contenido de Markdown.</span><span class="sxs-lookup"><span data-stu-id="af9df-1037">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1038">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1038">PowerPoint</span></span>

- <span data-ttu-id="af9df-1039">Se ha corregido un problema por el que una copia de una imagen con un relleno degradado radial no coincidía con el original.</span><span class="sxs-lookup"><span data-stu-id="af9df-1039">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>
- <span data-ttu-id="af9df-1040">Se ha corregido un problema por el que el botón Formularios de PowerPoint no permitía la creación de formularios cuando no se permitía el acceso a la Tienda Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-1040">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to the Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-1041">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-1041">Project</span></span>

- <span data-ttu-id="af9df-1042">Se ha corregido un problema por el que en una lista de tareas de SharePoint, los botones de la cinta de opciones en la segunda pestaña se podían deshabilitar.</span><span class="sxs-lookup"><span data-stu-id="af9df-1042">We fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1043">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1043">Word</span></span>

- <span data-ttu-id="af9df-1044">Se ha corregido un problema por el que una copia de una imagen con un relleno degradado radial no coincidía con el original.</span><span class="sxs-lookup"><span data-stu-id="af9df-1044">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>
- <span data-ttu-id="af9df-1045">Se ha corregido un problema que hacía que si se agregaba un comentario para realizar el seguimiento de un cambio, el panel de revisiones se abría de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="af9df-1045">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>
- <span data-ttu-id="af9df-1046">Se ha corregido un problema en el que los vínculos a los documentos no se insertaban en el cuadro de comentarios a través de la lista desplegable Insertar > Vínculo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1046">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>
- <span data-ttu-id="af9df-1047">Se ha corregido un problema por el que el recuento de hipervínculos en la colección de hipervínculos de VBA no realizaba correctamente la iteración después de agregar una imagen que contenía un hipervínculo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1047">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-july-24"></a><span data-ttu-id="af9df-1049">Versión 2008: 24 de julio</span><span class="sxs-lookup"><span data-stu-id="af9df-1049">Version 2008: July 24</span></span>
<span data-ttu-id="af9df-1050">*Versión 2008 (compilación 13117.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1050">*Version 2008 (Build 13117.20000)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-1052">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-1052">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-1053">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1053">Excel</span></span>

- <span data-ttu-id="af9df-1054">**Cree diagramas de Visio elegantes en Excel:** cree un diagrama de flujo o un organigrama con solo escribir datos en una hoja de cálculo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1054">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="af9df-1055">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-1055">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1058">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1058">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="af9df-1059">OneNote</span><span class="sxs-lookup"><span data-stu-id="af9df-1059">OneNote</span></span>

- <span data-ttu-id="af9df-1060">Se ha corregido un problema que provocaba que el texto de marcador de posición en el cuadro de edición de búsqueda se desbordase si se reducía el tamaño de la ventana de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="af9df-1060">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1061">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1061">Word</span></span>

- <span data-ttu-id="af9df-1062">Se ha corregido un problema que provocaba que el texto de marcador de posición en el cuadro de edición de búsqueda se desbordase si se reducía el tamaño de la ventana de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="af9df-1062">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>
- <span data-ttu-id="af9df-1063">Se ha corregido un problema que provocaba la deshabilitación de la opción de "Personas específicas" de Control de cambios.</span><span class="sxs-lookup"><span data-stu-id="af9df-1063">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>
- <span data-ttu-id="af9df-1064">Se ha corregido un bloqueo ocasional al abrir archivos HTML.</span><span class="sxs-lookup"><span data-stu-id="af9df-1064">We fixed an occasional hang while opening HTML files.</span></span>

[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2008-july-17"></a><span data-ttu-id="af9df-1066">Versión 2008: 17 de julio</span><span class="sxs-lookup"><span data-stu-id="af9df-1066">Version 2008: July 17</span></span>
<span data-ttu-id="af9df-1067">*Versión 2008 (compilación 13115.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1067">*Version 2008 (Build 13115.20000)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1069">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1069">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-1070">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1070">Excel</span></span>

- <span data-ttu-id="af9df-1071">Se corrigió un problema por el cual cada vez que se guardaba y volvía a abrir un gráfico dinámico con líneas guía ocultas, las líneas guía se volvían visibles.</span><span class="sxs-lookup"><span data-stu-id="af9df-1071">We fixed an issue where any time a pivot chart with hidden leader lines was saved and reopened, the leader lines would become visible.</span></span>

- <span data-ttu-id="af9df-1072">Se corrigió un problema por el que los gráficos no siempre se actualizaban como se esperaba cuando se habilitaba "ForceFullCalculation" a través de VBA para el libro.</span><span class="sxs-lookup"><span data-stu-id="af9df-1072">We fixed an issue where charts were not always updated as expected when 'ForceFullCalculation' was enabled via VBA for the workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1073">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1073">Outlook</span></span>

- <span data-ttu-id="af9df-1074">Se corrigió un problema en la creación de varios perfiles en Outlook desde el mismo dominio de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="af9df-1074">We fixed an issue around creating multiple profiles in Outlook from the same email domain.</span></span>
- <span data-ttu-id="af9df-1075">Corrige un problema que provocaba que el icono de bloqueo no se mostrara en el encabezado de los mensajes cifrados S/MIME.</span><span class="sxs-lookup"><span data-stu-id="af9df-1075">Addresses an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>
- <span data-ttu-id="af9df-1076">Corrige un problema que provocaba que los datos adjuntos se quitaran de mensajes S/MIME al enviarse sin cifrar.</span><span class="sxs-lookup"><span data-stu-id="af9df-1076">Addresses an issue that caused attachments to get stripped from S/MIME messages when sent unencrypted.</span></span>
- <span data-ttu-id="af9df-1077">Corrige un problema que provocaba que los mensajes de texto sin formato S/MIME se volvieran ilegibles al enviarse.</span><span class="sxs-lookup"><span data-stu-id="af9df-1077">Addresses an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>
- <span data-ttu-id="af9df-1078">Corrige un problema que provocaba que los datos adjuntos se dañaran al enviar un correo electrónico S/MIME sin cifrar.</span><span class="sxs-lookup"><span data-stu-id="af9df-1078">Addresses an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>
- <span data-ttu-id="af9df-1079">Corrige un problema que provocaba que los usuarios no pudiesen guardar datos adjuntos de OneDrive de fuera de su espacio empresarial en su equipo local al seleccionar la opción Guardar en el cuadro de diálogo de seguridad.</span><span class="sxs-lookup"><span data-stu-id="af9df-1079">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the 'Save' option on the security dialog.</span></span>
- <span data-ttu-id="af9df-1080">Corrige un problema que provocaba que los destinatarios no pudieran guardar los mensajes con derechos protegidos incluso cuando el remitente otorgó el permiso de Guardar como.</span><span class="sxs-lookup"><span data-stu-id="af9df-1080">Addresses an issue that caused recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>
- <span data-ttu-id="af9df-1081">Corrige un problema que provocaba que las etiquetas de algunas opciones de Búsqueda avanzada se truncaran en algunos idiomas.</span><span class="sxs-lookup"><span data-stu-id="af9df-1081">Addresses an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-1082">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-1082">Project</span></span>

- <span data-ttu-id="af9df-1083">Se corrigió un problema por el que las tareas que aparecen en la vista Panel de tareas no estaban sincronizadas con las del cuadro de diálogo Asignar recursos.</span><span class="sxs-lookup"><span data-stu-id="af9df-1083">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>
- <span data-ttu-id="af9df-1084">Se ha corregido un problema por el que si se copiaba y pegaba una tarea con varias dependencias, no se copiaban todas las dependencias correctamente.</span><span class="sxs-lookup"><span data-stu-id="af9df-1084">We fixed an issue where if you copied and pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1085">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1085">Word</span></span>

- <span data-ttu-id="af9df-1086">Se corrigió un problema por el que el comando "Editor" se deshabilitaba cuando el foco estaba en un cuadro de texto de comentario.</span><span class="sxs-lookup"><span data-stu-id="af9df-1086">We fixed an issue where the 'Editor' command was disabled when the focus was in a comment text box.</span></span>
- <span data-ttu-id="af9df-1087">Se corrigió un problema por el que el comando "Mostrar marcas" se deshabilitaba cuando el foco estaba en un cuadro de texto de comentario.</span><span class="sxs-lookup"><span data-stu-id="af9df-1087">We fixed an issue where the 'Show Markup' command was disabled when the focus was in a comment text box.</span></span>
- <span data-ttu-id="af9df-1088">Se corrigió un problema en el XML personalizado en el que se puede perder el estado de los comentarios al abrir el documento.</span><span class="sxs-lookup"><span data-stu-id="af9df-1088">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="af9df-1089">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-1089">Office Suite</span></span>

- <span data-ttu-id="af9df-1090">Se corrigió un problema en el que, después de abrir el usuario una nueva ventana de la aplicación desde la barra de tareas y crear un nuevo documento en blanco, se creaban archivos adicionales.</span><span class="sxs-lookup"><span data-stu-id="af9df-1090">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>
- <span data-ttu-id="af9df-1091">Se corrigió un problema por el que, si un usuario estaba editando un documento pero había perdido los permisos, no se informaba al usuario de que tenía que volver a autenticarse.</span><span class="sxs-lookup"><span data-stu-id="af9df-1091">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>

[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-july-10"></a><span data-ttu-id="af9df-1093">Versión 2008: 10 de julio</span><span class="sxs-lookup"><span data-stu-id="af9df-1093">Version 2008: July 10</span></span>
<span data-ttu-id="af9df-1094">*Versión 2008 (compilación 13102.20002)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1094">*Version 2008 (Build 13102.20002)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1096">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1096">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-1097">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1097">Outlook</span></span>

- <span data-ttu-id="af9df-1098">Se ha corregido un problema debido al cual la opción Permitir reenvío no aparecía en las opciones de respuesta de las reuniones del calendario compartido en aquellos casos en los que la carpeta de descarga compartida no se había comprobado.</span><span class="sxs-lookup"><span data-stu-id="af9df-1098">We fixed an issue where the Allow Forwarding option was missing from the shared calendar meeting "Response Options" if Download shared folder was NOT checked.</span></span>
- <span data-ttu-id="af9df-1099">Se ha corregido un problema que provocaba que el botón Imprimir apareciera en un estado deshabilitado aunque el usuario tuviera los permisos de impresión adecuados.</span><span class="sxs-lookup"><span data-stu-id="af9df-1099">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-1100">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-1100">Project</span></span>

- <span data-ttu-id="af9df-1101">Se ha corregido un problema que impedía al usuario guardar desde Project un PDF o XPS en una biblioteca de documentos de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="af9df-1101">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1102">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1102">Word</span></span>

- <span data-ttu-id="af9df-1103">Se ha corregido un problema que provocaba que Word dejara de responder después de pegar texto y una imagen en un cuadro de comentarios.</span><span class="sxs-lookup"><span data-stu-id="af9df-1103">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>
- <span data-ttu-id="af9df-1104">Se ha corregido un problema que causaba que el botón "Nuevo comentario" quedara deshabilitado después de eliminar el último comentario.</span><span class="sxs-lookup"><span data-stu-id="af9df-1104">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2007-july-03"></a><span data-ttu-id="af9df-1106">Versión 2007: 03 de julio</span><span class="sxs-lookup"><span data-stu-id="af9df-1106">Version 2007: July 03</span></span>
<span data-ttu-id="af9df-1107">*Versión 2007 (compilación 13029.20006)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1107">*Version 2007 (Build 13029.20006)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-1109">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-1109">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-1110">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1110">Outlook</span></span>

- <span data-ttu-id="af9df-1111">**Crear sondeos en Outlook con Sondeo rápido:** cree sondeos, recopile votos y obtenga los resultados rápidamente en un solo correo electrónico [Más información](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="af9df-1111">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="af9df-1112">**Nuevo buscador de salas:** búsqueda de salas de conferencias por distintas funcionalidades.</span><span class="sxs-lookup"><span data-stu-id="af9df-1112">**New room finder:** Search for conference rooms by different capabilities.</span></span>

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1115">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1115">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-1116">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1116">Excel</span></span>

- <span data-ttu-id="af9df-1117">Se ha corregido un problema por el que las tablas del modelo de datos creadas en algunas versiones de Excel no se podían ver en "Vista previa de la tabla", pese a que no se había editado la consulta asociada a la tabla.</span><span class="sxs-lookup"><span data-stu-id="af9df-1117">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>
- <span data-ttu-id="af9df-1118">Se ha corregido un problema por el que deshabilitar la opción "Omitir tipo de referencia (relativa o absoluta)" en el cuadro de diálogo "Definir nombre/Aplicar nombres" provocaba que las fórmulas no funcionaran.</span><span class="sxs-lookup"><span data-stu-id="af9df-1118">We fixed an issue where disabling 'Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>
- <span data-ttu-id="af9df-1119">Se ha corregido un problema por el que al quitar filtros avanzados de datos se borraba el formato de tabla.</span><span class="sxs-lookup"><span data-stu-id="af9df-1119">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>
- <span data-ttu-id="af9df-1120">Se ha corregido un problema que provocaba que la ruta de acceso completa de un documento PDF incrustado se mostrara en el título del documento, en lugar de mostrarse solo en el nombre de archivo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1120">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>
- <span data-ttu-id="af9df-1121">Se ha corregido un problema por el que deshabilitar el CloudConnector de Wolfram y, a continuación, guardar y volver a abrir un libro de Excel podía dar lugar a un bloqueo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1121">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>
- <span data-ttu-id="af9df-1122">Se ha corregido un problema por el que iniciar Excel con el complemento Solver habilitado daba lugar a un bloqueo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1122">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1123">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1123">Outlook</span></span>

- <span data-ttu-id="af9df-1124">Se ha corregido un problema por el que Outlook se bloqueaba si había más de 130 destinatarios en la línea "Para". Asimismo, se ha mejorado el rendimiento del procesamiento de texto.</span><span class="sxs-lookup"><span data-stu-id="af9df-1124">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>
- <span data-ttu-id="af9df-1125">Se ha corregido un problema en la barra "Tareas Pendientes" que provocaba que los eventos que ocupaban más de dos días mostraran la misma hora de finalización para los siguientes días.</span><span class="sxs-lookup"><span data-stu-id="af9df-1125">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>
- <span data-ttu-id="af9df-1126">Se ha corregido un problema que provocaba que la lista de mensajes dejara de actualizarse durante varios minutos después de que los usuarios de Outlook usaran calendarios compartidos.</span><span class="sxs-lookup"><span data-stu-id="af9df-1126">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1127">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1127">PowerPoint</span></span>

- <span data-ttu-id="af9df-1128">Se ha corregido un problema por el que, al tratar de pegar código HTML en un área de texto en una diapositiva, el código se pegaba en un cuadro de texto creado en la parte superior de la diapositiva.</span><span class="sxs-lookup"><span data-stu-id="af9df-1128">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>
- <span data-ttu-id="af9df-1129">Se ha corregido un problema por el que, al seleccionar todas las diapositivas en la vista Moderador y, a continuación, salir de dicha vista mediante ALT+TAB, volver a la presentación con diapositivas y hacer clic en "Finalizar presentación", tenía lugar una excepción no controlada.</span><span class="sxs-lookup"><span data-stu-id="af9df-1129">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-1130">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-1130">Project</span></span>

- <span data-ttu-id="af9df-1131">Se ha corregido un problema que provocaba que Project se bloqueara al abrir determinados archivos XML.</span><span class="sxs-lookup"><span data-stu-id="af9df-1131">We fixed an issue where Project may crash when opening certain XML files.</span></span>
- <span data-ttu-id="af9df-1132">Se ha corregido un problema por el que no se podía abrir un archivo de Project de una biblioteca de documentos de SharePoint si la biblioteca estaba en modo moderno.</span><span class="sxs-lookup"><span data-stu-id="af9df-1132">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>
- <span data-ttu-id="af9df-1133">Se ha corregido un problema por el que los proyectos no se podían abrir en el cliente de escritorio de Project en Project Web App si la dirección URL finalizaba en ".com".</span><span class="sxs-lookup"><span data-stu-id="af9df-1133">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1134">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1134">Word</span></span>

- <span data-ttu-id="af9df-1135">Se ha corregido un problema en el modo de coautoría: cuando se produce un conflicto de fusión y el usuario ya ha elegido previamente descartar los cambios, ya no se muestra la opción que da a elegir entre guardar o descartar los cambios.</span><span class="sxs-lookup"><span data-stu-id="af9df-1135">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>
- <span data-ttu-id="af9df-1136">Se ha corregido un problema por el que, al intentar guardar un archivo que contenía una macro con un nombre nuevo, este se guardaba con la extensión .docx y el nombre de archivo "WRO0004.docx", independientemente de lo que el usuario escribiera, lo que provocaba que el archivo no se pudiera volver a usar.</span><span class="sxs-lookup"><span data-stu-id="af9df-1136">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2007-june-26"></a><span data-ttu-id="af9df-1138">Versión 2007: 26 de junio</span><span class="sxs-lookup"><span data-stu-id="af9df-1138">Version 2007: June 26</span></span>
<span data-ttu-id="af9df-1139">*Versión 2007 (compilación 13020.20004)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1139">*Version 2007 (Build 13020.20004)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1141">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1141">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="af9df-1142">Access</span><span class="sxs-lookup"><span data-stu-id="af9df-1142">Access</span></span>

- <span data-ttu-id="af9df-1143">Se ha corregido un problema por el que el administrador de tablas vinculadas solicitaba una clave principal al actualizar una tabla SQL vinculada.</span><span class="sxs-lookup"><span data-stu-id="af9df-1143">We fixed an issue where the linked table manager would prompt for a primary key if a linked SQL table was refreshed.</span></span>
- <span data-ttu-id="af9df-1144">Se ha corregido un problema por el que las consultas en el Editor de consultas quedaban desplazadas fuera de la vista.</span><span class="sxs-lookup"><span data-stu-id="af9df-1144">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>
- <span data-ttu-id="af9df-1145">Se ha corregido un problema que provocaba que la ejecución de consultas tardara en completarse aproximadamente el doble del tiempo esperado.</span><span class="sxs-lookup"><span data-stu-id="af9df-1145">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1146">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1146">Outlook</span></span>

- <span data-ttu-id="af9df-1147">Se ha corregido un problema por el que los usuarios no podían "Enviar como" o "Enviar en nombre de" en una lista de distribución.</span><span class="sxs-lookup"><span data-stu-id="af9df-1147">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>
- <span data-ttu-id="af9df-1148">Se ha corregido un problema por el que, al insertar una imagen en un mensaje y, a continuación, guardar el mensaje como borrador, se cambiaba el tamaño de la imagen.</span><span class="sxs-lookup"><span data-stu-id="af9df-1148">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>
- <span data-ttu-id="af9df-1149">Se ha corregido un problema que provocaba que el cuerpo de un mensaje NDR cambiara de Unicode a ASCII después de editar el asunto.</span><span class="sxs-lookup"><span data-stu-id="af9df-1149">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-1150">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-1150">Project</span></span>

- <span data-ttu-id="af9df-1151">Se ha corregido un problema que consistía en que los vínculos de Project Planner en entornos de Government Community Cloud habían sido deshabilitados.</span><span class="sxs-lookup"><span data-stu-id="af9df-1151">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>

### <a name="office-suite"></a><span data-ttu-id="af9df-1152">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-1152">Office Suite</span></span>

- <span data-ttu-id="af9df-1153">Se ha corregido un problema por el que el texto insertado en un archivo de gráficos vectoriales escalables (SVG) quedaba ilegible tras insertarlo en un archivo de Word, Excel o PowerPoint, guardar y cerrar el archivo y, a continuación, volver a abrirlo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1153">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>

[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2007-june-19"></a><span data-ttu-id="af9df-1155">Versión 2007: 19 de junio</span><span class="sxs-lookup"><span data-stu-id="af9df-1155">Version 2007: June 19</span></span>
<span data-ttu-id="af9df-1156">*Versión 2007 (compilación 13012.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1156">*Version 2007 (Build 13012.20000)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1158">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1158">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-1159">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1159">Excel</span></span>

- <span data-ttu-id="af9df-1160">Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta personalizada al guardar un libro de trabajo en SharePoint o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="af9df-1160">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>
- <span data-ttu-id="af9df-1161">Se ha corregido un problema que provocaba que los libros de trabajo fueran de solo lectura cuando el archivo tenía activada la casilla "Se recomienda solo lectura".</span><span class="sxs-lookup"><span data-stu-id="af9df-1161">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1162">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1162">Outlook</span></span>

- <span data-ttu-id="af9df-1163">Se ha corregido un problema por el que la ventana del Editor de métodos de entrada (IME) se superponía al texto subyacente escrito mediante el IME al utilizar varios monitores con resoluciones diferentes.</span><span class="sxs-lookup"><span data-stu-id="af9df-1163">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="af9df-p161">Se ha corregido un problema que provocaba que los usuarios vieran el siguiente error al cerrar una cita guardada previamente: "No se puede guardar el elemento porque otro usuario lo modificó o se modificó en otra ventana. ¿Quiere realizar una copia en la carpeta predeterminada del elemento?".</span><span class="sxs-lookup"><span data-stu-id="af9df-p161">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved: "The item cannot be saved because it was changed by another user or in another window. Do you want to make a copy in the default folder for the item?"</span></span>
- <span data-ttu-id="af9df-1166">Se ha corregido un problema por el que las fechas del minicalendario no se podían mostrar en negrita para los usuarios de Japón.</span><span class="sxs-lookup"><span data-stu-id="af9df-1166">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>
- <span data-ttu-id="af9df-1167">Se ha corregido un problema que impedía que los avisos del calendario mostraran la hora exacta de las reuniones programadas para tener lugar en menos de una semana.</span><span class="sxs-lookup"><span data-stu-id="af9df-1167">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1168">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1168">PowerPoint</span></span>

- <span data-ttu-id="af9df-1169">Se ha corregido un problema por el que el indicador de color de presencia de un usuario no se actualizaba en la galería de coautoría durante una sesión de coautoría en directo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1169">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-1170">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-1170">Project</span></span>

- <span data-ttu-id="af9df-1171">Se ha corregido un problema por el que, si las tareas de duración fija estaban completas al 100 %, pero no se especificaba la fecha de finalización real, el porcentaje de finalización de la tarea se mostraba como inferior al 100 %.</span><span class="sxs-lookup"><span data-stu-id="af9df-1171">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1172">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1172">Word</span></span>

- <span data-ttu-id="af9df-1173">Se ha corregido un problema por el que el color de los hipervínculos HTML no se representaba correctamente.</span><span class="sxs-lookup"><span data-stu-id="af9df-1173">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="af9df-1174">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-1174">Office Suite</span></span>

- <span data-ttu-id="af9df-1175">Se ha corregido un problema por el que las direcciones URL que no se basaban en http o https no se mostraban en la lista Utilizado recientemente.</span><span class="sxs-lookup"><span data-stu-id="af9df-1175">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2007-june-12"></a><span data-ttu-id="af9df-1177">Versión 2007: 12 de junio</span><span class="sxs-lookup"><span data-stu-id="af9df-1177">Version 2007: June 12</span></span>
<span data-ttu-id="af9df-1178">*Versión 2007 (compilación 13006.20002)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1178">*Version 2007 (Build 13006.20002)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-1180">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-1180">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-1181">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1181">Excel</span></span>

- <span data-ttu-id="af9df-1182">**Obtenga datos de organización de Power BI mediante Tipos de datos:** los tipos de datos de Excel de Power BI se están publicando ahora para participantes de Office Insider en las organizaciones con Office 365 E5/A5 o Microsoft 365 E5/A5.</span><span class="sxs-lookup"><span data-stu-id="af9df-1182">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="af9df-1183">Obtener la información que necesita y actualizarla fácilmente es fundamental para muchos de los flujos de trabajo diarios.</span><span class="sxs-lookup"><span data-stu-id="af9df-1183">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="af9df-1184">Le proporcionamos acceso a la información de Power BI de su empresa u organización como un tipo de datos en Excel, lo que amplía su capacidad de incorporar a las hojas de cálculo información vinculada.</span><span class="sxs-lookup"><span data-stu-id="af9df-1184">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="af9df-1185">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-1185">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="af9df-1186">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="af9df-1186">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1189">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1189">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="af9df-1190">Access</span><span class="sxs-lookup"><span data-stu-id="af9df-1190">Access</span></span>

- <span data-ttu-id="af9df-1191">Se ha corregido un problema que provocaba que Microsoft Access no identificara una Columna de identidad en una tabla vinculada de SQL Server, lo que podía hacer que las filas aparecieran como eliminadas de forma incorrecta.</span><span class="sxs-lookup"><span data-stu-id="af9df-1191">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="af9df-1192">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1192">Excel</span></span>

- <span data-ttu-id="af9df-1193">Se ha corregido un problema por el que no se pudo aplicar el formato correcto a las líneas de cuadrícula principales de los gráficos radiales.</span><span class="sxs-lookup"><span data-stu-id="af9df-1193">We fixed an issue where the major grid lines of radar charts could not be formatted correctly.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-1194">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-1194">Project</span></span>

- <span data-ttu-id="af9df-1195">Se ha corregido un problema que provocaba que el evento ProjectBeforeTaskChange no se activara al tener lugar un cambio en la tarea de resumen del proyecto, ya fuera en el campo de inicio o de tarea del proyecto.</span><span class="sxs-lookup"><span data-stu-id="af9df-1195">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>
- <span data-ttu-id="af9df-1196">Se ha corregido un problema por el que una actualización o un restablecimiento de la línea base podía cambiar los recursos de trabajo o el costo presupuestado con fases temporales, y la línea base podía reflejar valores de presupuesto incorrectos.</span><span class="sxs-lookup"><span data-stu-id="af9df-1196">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1197">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1197">Word</span></span>

- <span data-ttu-id="af9df-1198">Se ha corregido un problema por el que no funcionaba la opción de borrar el formato en el Panel Comentarios mediante el botón Borrar formato de la cinta de opciones de Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-1198">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>
- <span data-ttu-id="af9df-1199">Se ha corregido un problema que provocaba que otras aplicaciones que se ejecutaban en segundo plano comenzaran a parpadear al cambiar el tamaño de una tabla cuando la regla no se mostraba.</span><span class="sxs-lookup"><span data-stu-id="af9df-1199">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>
- <span data-ttu-id="af9df-1200">Se ha corregido un problema por el que, en el modo de coautoría, las respuestas a los comentarios no se mostraban en el panel de comentarios en ocasiones, pero eran visibles en el panel de revisiones.</span><span class="sxs-lookup"><span data-stu-id="af9df-1200">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>
- <span data-ttu-id="af9df-1201">Se ha corregido un problema por el que, si Word tenía una lista de más de 50 documentos abiertos con frecuencia, después de guardar y abrir un documento, se mostraba un historial de revisiones pese a que no se había modificado dicho documento.</span><span class="sxs-lookup"><span data-stu-id="af9df-1201">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>

[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2006-june-05"></a><span data-ttu-id="af9df-1203">Versión 2006: 05 de junio</span><span class="sxs-lookup"><span data-stu-id="af9df-1203">Version 2006: June 05</span></span>
<span data-ttu-id="af9df-1204">*Versión 2006 (compilación 13001.20002)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1204">*Version 2006 (Build 13001.20002)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-1206">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-1206">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-1207">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1207">Excel</span></span>

- <span data-ttu-id="af9df-1208">**Ordenar o filtrar mientras colabora en Excel:** ahora puede ordenar y filtrar un archivo de Excel mientras colabora con otras personas.</span><span class="sxs-lookup"><span data-stu-id="af9df-1208">**Sort/filter while collaborating in Excel:** You can now sort and filter your Excel file while collaborating with others.</span></span> <span data-ttu-id="af9df-1209">Esta nueva característica evita que sus acciones se vean afectadas por la ordenación y los filtros de otros usuarios mientras se trabaja en un documento en coautoría.</span><span class="sxs-lookup"><span data-stu-id="af9df-1209">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span>

- <span data-ttu-id="af9df-1210">**Crear tablas dinámicas de conjuntos de datos en Power BI en Excel:** puede crear tablas dinámicas en Excel conectadas a los conjuntos de datos almacenados en Power BI con tan solo unos clics.</span><span class="sxs-lookup"><span data-stu-id="af9df-1210">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="af9df-1211">Así, podrá obtener lo mejor de las tablas dinámicas y de Power BI.</span><span class="sxs-lookup"><span data-stu-id="af9df-1211">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="af9df-1212">Calcule, resuma y analice sus datos con tablas dinámicas desde sus conjuntos de datos seguros de Power BI.</span><span class="sxs-lookup"><span data-stu-id="af9df-1212">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="af9df-1213">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-1213">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a><span data-ttu-id="af9df-1214">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1214">Outlook</span></span>

- <span data-ttu-id="af9df-1215">**Volver a abrir rápidamente los elementos de una sesión anterior:** hemos agregado una opción para volver a abrir rápidamente los elementos de una sesión anterior de Outlook.</span><span class="sxs-lookup"><span data-stu-id="af9df-1215">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="af9df-1216">Si Outlook se bloquea o usted cierra la aplicación, ahora podrá reiniciar elementos rápidamente al reabrir Outlook.</span><span class="sxs-lookup"><span data-stu-id="af9df-1216">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="af9df-1217">Esta característica está activada de forma predeterminada.</span><span class="sxs-lookup"><span data-stu-id="af9df-1217">This feature is on by default.</span></span> <span data-ttu-id="af9df-1218">Para desactivarla, vaya a Opciones > General > Opciones de inicio.</span><span class="sxs-lookup"><span data-stu-id="af9df-1218">To turn it off, go to Options > General > Start up Options.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1221">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1221">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-1222">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1222">Excel</span></span>

- <span data-ttu-id="af9df-1223">Se ha corregido un problema por el que los valores personalizados en el eje del gráfico no se aplicaban correctamente.</span><span class="sxs-lookup"><span data-stu-id="af9df-1223">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>
- <span data-ttu-id="af9df-1224">Se ha corregido un problema por el que las hojas de cálculo que contenían varias fórmulas con nombres definidos tardaban más en guardarse.</span><span class="sxs-lookup"><span data-stu-id="af9df-1224">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1225">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1225">Outlook</span></span>

- <span data-ttu-id="af9df-1226">Se ha corregido un problema por el que la ventana del Editor de métodos de entrada (IME) se superponía al texto subyacente escrito mediante el IME cuando se usaban varios monitores con resoluciones diferentes.</span><span class="sxs-lookup"><span data-stu-id="af9df-1226">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="af9df-1227">Se ha corregido un problema que causaba un bloqueo cuando se visualizaba una plantilla mientras se redactaba un nuevo mensaje de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="af9df-1227">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>
- <span data-ttu-id="af9df-1228">Se ha corregido un problema por el que los usuarios no podían intercambiar carpetas públicas de Exchange 2010 después de la versión 1911 de Outlook.</span><span class="sxs-lookup"><span data-stu-id="af9df-1228">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>
- <span data-ttu-id="af9df-1229">Se ha corregido un problema por el que se deshabilitaba el botón de Categorizar para los calendarios de grupo en la cinta de opciones de Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-1229">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="af9df-1230">Se ha corregido un problema que hacía que los usuarios con contactos en conflicto experimentaran bloqueos en Outlook.</span><span class="sxs-lookup"><span data-stu-id="af9df-1230">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>
- <span data-ttu-id="af9df-1231">Se ha corregido un problema por el que la lista desplegable del Archivo en línea en las propiedades de carpeta no aparecía en monitores con un alto nivel de ppp.</span><span class="sxs-lookup"><span data-stu-id="af9df-1231">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>
- <span data-ttu-id="af9df-1232">Se ha corregido un problema que provocaba un bloqueo en Outlook al trabajar con hipervínculos en mensajes de correo electrónico de texto sin formato.</span><span class="sxs-lookup"><span data-stu-id="af9df-1232">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>
- <span data-ttu-id="af9df-1233">Se ha corregido un problema que provocaba que Outlook no pudiera analizar nombres de archivo largos codificados con RFC2231.</span><span class="sxs-lookup"><span data-stu-id="af9df-1233">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>
- <span data-ttu-id="af9df-1234">Se ha corregido un problema que provocaba que los usuarios de Outlook experimentaran interrupciones intermitentes al usar lectores de pantalla.</span><span class="sxs-lookup"><span data-stu-id="af9df-1234">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1235">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1235">PowerPoint</span></span>

- <span data-ttu-id="af9df-1236">Se ha corregido un problema al abrir archivos configurados por el servidor con autenticación basada en formularios.</span><span class="sxs-lookup"><span data-stu-id="af9df-1236">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>
- <span data-ttu-id="af9df-1237">Se ha corregido un problema por el que los archivos de PowerPoint con gráficos o libros incrustados podían causar errores al guardar el archivo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1237">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>
- <span data-ttu-id="af9df-1238">Se ha corregido un problema que provocaba que los paneles de Comentarios cerrados por el usuario se abrieran automáticamente de nuevo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1238">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>
- <span data-ttu-id="af9df-1239">Se ha corregido un problema por el que el editor de diapositivas de una diapositiva se superponía a la siguiente diapositiva.</span><span class="sxs-lookup"><span data-stu-id="af9df-1239">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-1240">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-1240">Project</span></span>

- <span data-ttu-id="af9df-1241">Se ha corregido un problema que impedía que las tareas huérfanas se eliminaran o reasignaran después de eliminar su plan primario.</span><span class="sxs-lookup"><span data-stu-id="af9df-1241">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1242">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1242">Word</span></span>

- <span data-ttu-id="af9df-1243">Se ha corregido un problema por el que las marcas de tiempo en los paneles de comentarios no se basaban en la hora de la configuración regional del sistema.</span><span class="sxs-lookup"><span data-stu-id="af9df-1243">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>
- <span data-ttu-id="af9df-1244">Se ha corregido un problema por el que los comentarios entre la aplicación web y la aplicación de escritorio no estaban sincronizados.</span><span class="sxs-lookup"><span data-stu-id="af9df-1244">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)


## <a name="version-2006-may-29"></a><span data-ttu-id="af9df-1246">Versión 2006: 29 de mayo</span><span class="sxs-lookup"><span data-stu-id="af9df-1246">Version 2006: May 29</span></span>
<span data-ttu-id="af9df-1247">*Versión 2006 (compilación 12920.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1247">*Version 2006 (Build 12920.20000)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="af9df-1248">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-1248">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-1249">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1249">Outlook</span></span>

- <span data-ttu-id="af9df-1250">**Se agregaron más botones a las notificaciones del sistema de Outlook:** los botones de Acción rápida aparecen ahora en las notificaciones del sistema de Outlook cuando se ejecuta Outlook en Windows 10.</span><span class="sxs-lookup"><span data-stu-id="af9df-1250">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1251">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1251">PowerPoint</span></span>

- <span data-ttu-id="af9df-1252">**Rendimiento mejorado de vídeos de Stream en PowerPoint:** hemos realizado mejoras en el rendimiento de la reproducción de los vídeos de Microsoft Stream para minimizar el tiempo de carga de vídeo y lograr una visualización más fluida.</span><span class="sxs-lookup"><span data-stu-id="af9df-1252">**Improved Stream video performance in PowerPoint:** We've made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span>  <span data-ttu-id="af9df-1253">Utilice sus vídeos corporativos de Microsoft Stream para crear presentaciones mejoradas.</span><span class="sxs-lookup"><span data-stu-id="af9df-1253">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1256">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1256">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="af9df-1257">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1257">Excel</span></span>

- <span data-ttu-id="af9df-1258">Se ha corregido un problema por el que Excel se cerraba ocasionalmente al utilizar OneDrive.</span><span class="sxs-lookup"><span data-stu-id="af9df-1258">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>
- <span data-ttu-id="af9df-1259">Se ha corregido un problema que provocaba que, al hacer clic en un hipervínculo marcado en el propio libro, se ocultara dicho libro.</span><span class="sxs-lookup"><span data-stu-id="af9df-1259">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>
- <span data-ttu-id="af9df-1260">Se ha corregido un problema por el que algunos vínculos de un gráfico copiado y pegado usaban direcciones de unidad asignadas, en lugar de direcciones universales.</span><span class="sxs-lookup"><span data-stu-id="af9df-1260">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>
- <span data-ttu-id="af9df-1261">Se ha corregido un problema por el que Excel podía dejar de responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="af9df-1261">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1262">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1262">PowerPoint</span></span>

- <span data-ttu-id="af9df-1263">Se ha corregido un problema que hacía que las diapositivas no quedaran centradas después de usar la rueda del mouse para hacer zoom.</span><span class="sxs-lookup"><span data-stu-id="af9df-1263">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1264">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1264">Word</span></span>

- <span data-ttu-id="af9df-1265">Se ha corregido un problema por el que no se mostraban los textos copiados y pegados en un panel de comentarios.</span><span class="sxs-lookup"><span data-stu-id="af9df-1265">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>
- <span data-ttu-id="af9df-1266">Se ha corregido un problema debido al cual las burbujas de sugerencias de comentarios aparecían borrosas al 100 % de zoom.</span><span class="sxs-lookup"><span data-stu-id="af9df-1266">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>
- <span data-ttu-id="af9df-1267">Se ha corregido un problema que causaba errores en ciertos casos de coautoría al habilitar la directiva de Word 2007 y, después, las plantillas y documentos binarios.</span><span class="sxs-lookup"><span data-stu-id="af9df-1267">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>
- <span data-ttu-id="af9df-1268">Se ha corregido un problema por el que no se abrían los archivos con nombres de ruta largos (mayores que 32 000 caracteres) y no se mostraba un mensaje de error adecuado.</span><span class="sxs-lookup"><span data-stu-id="af9df-1268">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)


## <a name="version-2006-may-22"></a><span data-ttu-id="af9df-1270">Versión 2006: 22 de mayo</span><span class="sxs-lookup"><span data-stu-id="af9df-1270">Version 2006: May 22</span></span>
<span data-ttu-id="af9df-1271">*Versión 2006 (compilación 12914.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1271">*Version 2006 (Build 12914.20000)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-1273">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-1273">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-1274">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1274">Excel</span></span>

- <span data-ttu-id="af9df-1275">**Guardar en carpetas fijadas:** anclar las carpetas facilita el almacenamiento de archivos de Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-1275">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="af9df-1276">Recibimos un comentario en el que se nos informa de que los usuarios desean tener más control sobre las carpetas disponibles al guardar un archivo nuevo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1276">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="af9df-1277">Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar.</span><span class="sxs-lookup"><span data-stu-id="af9df-1277">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="af9df-1278">Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.</span><span class="sxs-lookup"><span data-stu-id="af9df-1278">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="af9df-1279">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="af9df-1279">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1280">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1280">PowerPoint</span></span>

- <span data-ttu-id="af9df-1281">**Guardar en carpetas fijadas:** anclar las carpetas facilita el almacenamiento de archivos de Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-1281">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="af9df-1282">Recibimos un comentario en el que se nos informa de que los usuarios desean tener más control sobre las carpetas disponibles al guardar un archivo nuevo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1282">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="af9df-1283">Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar.</span><span class="sxs-lookup"><span data-stu-id="af9df-1283">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="af9df-1284">Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.</span><span class="sxs-lookup"><span data-stu-id="af9df-1284">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="af9df-1285">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="af9df-1285">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1286">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1286">Word</span></span>

- <span data-ttu-id="af9df-1287">**Guardar en carpetas fijadas:** anclar las carpetas facilita el almacenamiento de archivos de Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-1287">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="af9df-1288">Recibimos un comentario en el que se nos informa de que los usuarios desean tener más control sobre las carpetas disponibles al guardar un archivo nuevo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1288">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="af9df-1289">Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar.</span><span class="sxs-lookup"><span data-stu-id="af9df-1289">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="af9df-1290">Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.</span><span class="sxs-lookup"><span data-stu-id="af9df-1290">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="af9df-1291">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="af9df-1291">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1294">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1294">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-1295">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1295">Excel</span></span>

- <span data-ttu-id="af9df-1296">Se ha corregido un problema que producía el siguiente mensaje de error: "No se puede cerrar el libro de trabajo debido a que otro libro hace referencia al mismo". El mensaje aparecía si los complementos se cargaban en orden alfabético en lugar de en un orden especificado por el usuario.</span><span class="sxs-lookup"><span data-stu-id="af9df-1296">We fixed an issue where the error message: “This workbook is currently referenced by another and cannot be closed” would appear because Add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>
- <span data-ttu-id="af9df-1297">Se ha corregido un problema que causaba problemas de memoria al administrar fuentes entre Excel y algunas aplicaciones tecnológicas de asistencia de terceros.</span><span class="sxs-lookup"><span data-stu-id="af9df-1297">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>
- <span data-ttu-id="af9df-1298">Se ha corregido un problema por el que Excel se bloqueaba cuando los complementos solicitaban elementos de host en hojas de cálculo que tuvieran formas con bloqueos noSelect.</span><span class="sxs-lookup"><span data-stu-id="af9df-1298">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1299">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1299">Outlook</span></span>

- <span data-ttu-id="af9df-1300">Se ha corregido un problema por el que el evento Folder.BeforeItemMove no se activaba correctamente cuando un usuario movía elementos entre carpetas.</span><span class="sxs-lookup"><span data-stu-id="af9df-1300">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>
- <span data-ttu-id="af9df-1301">Se ha corregido un problema en el que los usuarios veían los elementos del calendario que pasaban de la medianoche como Eventos de todo el día.</span><span class="sxs-lookup"><span data-stu-id="af9df-1301">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>
- <span data-ttu-id="af9df-1302">Se ha corregido un problema por el que Outlook se bloqueaba cuando dos complementos agregaban un botón al mismo grupo en la cinta de opciones.</span><span class="sxs-lookup"><span data-stu-id="af9df-1302">We fixed an issue where Outlook crashed when two Add-ins added a button to the same group in the ribbon.</span></span>
- <span data-ttu-id="af9df-1303">Se ha corregido un problema por el que los usuarios no podían compartir calendarios con usuarios invitados.</span><span class="sxs-lookup"><span data-stu-id="af9df-1303">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1304">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1304">PowerPoint</span></span>

- <span data-ttu-id="af9df-1305">Se ha corregido un problema que provocaba que, al acercar y alejar el área de presentación, apareciera una separación entre el recuadro de selección ampliado y el puntero del mouse.</span><span class="sxs-lookup"><span data-stu-id="af9df-1305">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-1306">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-1306">Project</span></span>

- <span data-ttu-id="af9df-1307">Se ha corregido un problema por el que Project se bloqueaba después de hacer clic en Opciones.</span><span class="sxs-lookup"><span data-stu-id="af9df-1307">We fixed an issue where Project would crash after clicking on Options.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1308">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1308">Word</span></span>

- <span data-ttu-id="af9df-1309">Se ha corregido un problema por el que los hipervínculos en los comentarios no funcionaban.</span><span class="sxs-lookup"><span data-stu-id="af9df-1309">We fixed an issue where hyperlinks in comments weren’t working.</span></span>
- <span data-ttu-id="af9df-1310">Se ha corregido un problema que provocaba que, al acercar y alejar el área de presentación, apareciera una separación entre el recuadro de selección ampliado y el puntero del mouse.</span><span class="sxs-lookup"><span data-stu-id="af9df-1310">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>
- <span data-ttu-id="af9df-1311">Se ha corregido un problema por el que no se podía pegar código HTML en WordMail para Calendario.</span><span class="sxs-lookup"><span data-stu-id="af9df-1311">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>
- <span data-ttu-id="af9df-1312">Se ha corregido un problema por el que, en ocasiones, Word se bloqueaba al responder a un comentario en una sesión de coautoría.</span><span class="sxs-lookup"><span data-stu-id="af9df-1312">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2006-may-15"></a><span data-ttu-id="af9df-1314">Versión 2006: 15 de mayo</span><span class="sxs-lookup"><span data-stu-id="af9df-1314">Version 2006: May 15</span></span>
<span data-ttu-id="af9df-1315">*Versión 2006 (compilación 12905.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1315">*Version 2006 (Build 12905.20000)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-1317">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-1317">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-1318">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1318">Excel</span></span>

- <span data-ttu-id="af9df-1319">**Realice una conexión PDF:** Conectar, importar, actualizar los datos de un PDF.</span><span class="sxs-lookup"><span data-stu-id="af9df-1319">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="af9df-1320">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-1320">Learn more</span></span>](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

- <span data-ttu-id="af9df-1321">**Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.</span><span class="sxs-lookup"><span data-stu-id="af9df-1321">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1322">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1322">Outlook</span></span>

- <span data-ttu-id="af9df-1323">**Encuentre lo que necesita:** Reducir la búsqueda con opciones como carpetas, remitente, fecha, información de datos adjuntos y más.</span><span class="sxs-lookup"><span data-stu-id="af9df-1323">**Find just what you need:** Narrow your search with options like folder, sender, date, attachment info, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1324">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1324">PowerPoint</span></span>

- <span data-ttu-id="af9df-1325">**No es necesario hacer clic: sus miniauriculares tienen que cubrir lo siguiente:** Usar sus Surface Earbuds para controlar sus presentaciones de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="af9df-1325">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="af9df-1326">Importante: Debe emparejar sus Surface Earbuds en la aplicación Surface Audio para Windows 10 para poder usar gestos para controlar las presentaciones.</span><span class="sxs-lookup"><span data-stu-id="af9df-1326">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="af9df-1327">Aquí encontrará instrucciones para empezar a usar la aplicación Surface Audio en Windows 10.</span><span class="sxs-lookup"><span data-stu-id="af9df-1327">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="af9df-1328">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-1328">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="af9df-1329">**Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.</span><span class="sxs-lookup"><span data-stu-id="af9df-1329">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1330">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1330">Word</span></span>

- <span data-ttu-id="af9df-1331">**Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.</span><span class="sxs-lookup"><span data-stu-id="af9df-1331">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1334">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1334">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="af9df-1335">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1335">Excel</span></span>
- <span data-ttu-id="af9df-1336">Hemos corregido un problema que provocaba que los usuarios tuvieran un mejor rendimiento al eliminar las columnas combinadas.</span><span class="sxs-lookup"><span data-stu-id="af9df-1336">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>
- <div><span data-ttu-id="af9df-1337">Hemos corregido un problema que provocaba que los nombres de las impresoras se duplicaran en la lista de impresoras disponibles.</span><span class="sxs-lookup"><span data-stu-id="af9df-1337">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1338">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1338">PowerPoint</span></span>
- <span data-ttu-id="af9df-1339">Hemos corregido un problema por el que la revisión ortográfica y los métodos abreviados del teclado no funcionaban de manera esperada al usar un teclado de Suiza (QWERTZ) en inglés.</span><span class="sxs-lookup"><span data-stu-id="af9df-1339">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1340">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1340">Word</span></span>
- <span data-ttu-id="af9df-1341">Hemos corregido un problema en el que agregar un nuevo comentario en un documento en blanco no haría nada.</span><span class="sxs-lookup"><span data-stu-id="af9df-1341">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>
- <span data-ttu-id="af9df-1342">Hemos corregido un problema que haría que la aplicación se bloqueara cuando se insertara o actualizara un índice en un documento que contuviera más de cien entradas.</span><span class="sxs-lookup"><span data-stu-id="af9df-1342">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>
- <span data-ttu-id="af9df-1343">Hemos corregido un problema que provocaba que los archivos con valores XML personalizados se abrieran muy despacio.</span><span class="sxs-lookup"><span data-stu-id="af9df-1343">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="af9df-1344">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-1344">Office Suite</span></span>
- <span data-ttu-id="af9df-1345">Hemos corregido un problema en Visual Basic para las aplicaciones de Microsoft Office, por el que la aplicación de Office consideraba como corruptos ciertos proyectos de VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre o la ruta de la biblioteca.</span><span class="sxs-lookup"><span data-stu-id="af9df-1345">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2006-may-08"></a><span data-ttu-id="af9df-1348">Versión 2006: 08 de mayo</span><span class="sxs-lookup"><span data-stu-id="af9df-1348">Version 2006: May 08</span></span>
<span data-ttu-id="af9df-1349">*Versión 2006 (Compilación 12829.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1349">*Version 2006 (Build 12829.20000)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-1351">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-1351">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-1352">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1352">Excel</span></span>

- <span data-ttu-id="af9df-1353">**Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.</span><span class="sxs-lookup"><span data-stu-id="af9df-1353">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1354">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1354">Outlook</span></span>

- <span data-ttu-id="af9df-1355">**Mejores resultados, en un instante:** actualizamos la experiencia de búsqueda para que sea más inteligente, rápida y fiable que nunca.</span><span class="sxs-lookup"><span data-stu-id="af9df-1355">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="af9df-1356">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-1356">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="af9df-1357">**Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.</span><span class="sxs-lookup"><span data-stu-id="af9df-1357">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1358">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1358">PowerPoint</span></span>

- <span data-ttu-id="af9df-p173">**Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos ahora son más elegantes. [Más información](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01).</span><span class="sxs-lookup"><span data-stu-id="af9df-p173">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier. [Learn more](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1361">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1361">Word</span></span>

- <span data-ttu-id="af9df-1362">**Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.</span><span class="sxs-lookup"><span data-stu-id="af9df-1362">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1365">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1365">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="af9df-1366">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-1366">Office Suite</span></span>

- <span data-ttu-id="af9df-1367">Hemos estudiado y resuelto el problema por el que una implementación de Office 365 ProPlus a través de Intune se pausaba después de apagar el SO.</span><span class="sxs-lookup"><span data-stu-id="af9df-1367">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2005-may-01"></a><span data-ttu-id="af9df-1369">Versión 2005: 1 de mayo</span><span class="sxs-lookup"><span data-stu-id="af9df-1369">Version 2005: May 01</span></span>
<span data-ttu-id="af9df-1370">*Versión 2005 (compilación 12827.20030)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1370">*Version 2005 (Build 12827.20030)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-1372">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-1372">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-1373">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1373">Outlook</span></span>

- <span data-ttu-id="af9df-1374">**Vínculos mejorados en el correo electrónico:** al incluir un vínculo a un archivo, la dirección URL se reemplaza por el nombre del archivo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1374">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="af9df-1375">Puede cambiar los permisos para que todos los destinatarios tengan acceso.</span><span class="sxs-lookup"><span data-stu-id="af9df-1375">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="af9df-1376">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-1376">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1379">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1379">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-1380">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1380">Excel</span></span>

- <span data-ttu-id="af9df-1381">Se ha corregido un problema por el que las tablas de datos de los gráficos podían representar incorrectamente los valores de un eje de fechas.</span><span class="sxs-lookup"><span data-stu-id="af9df-1381">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>
- <span data-ttu-id="af9df-1382">Se ha corregido un problema por el que los saltos de página no se podían deshabilitar después de ir al diseño de página o la vista previa de salto de página</span><span class="sxs-lookup"><span data-stu-id="af9df-1382">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>
- <span data-ttu-id="af9df-1383">Se ha corregido un problema por el que los estilos de línea de los gráficos podían perderse tras ocultar y mostrar columnas con datos de series.</span><span class="sxs-lookup"><span data-stu-id="af9df-1383">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>
- <span data-ttu-id="af9df-1384">Insertar una columna en una lista filtrada llevaba más tiempo de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="af9df-1384">Inserting a column in a filtered list would take longer than expected.</span></span>
- <span data-ttu-id="af9df-1385">Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.</span><span class="sxs-lookup"><span data-stu-id="af9df-1385">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>
- <span data-ttu-id="af9df-1386">Se ha corregido el problema por el que el formato personalizado de un gráfico dinámico podía no guardarse si estaba habilitada la opción "Invertir si es negativo".</span><span class="sxs-lookup"><span data-stu-id="af9df-1386">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>
- <span data-ttu-id="af9df-1387">Se ha corregido un problema por el que el formato personalizado de un único punto de datos de un gráfico dinámico no se guardaba si estaba seleccionada la opción "invertir si es negativo".</span><span class="sxs-lookup"><span data-stu-id="af9df-1387">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>
- <span data-ttu-id="af9df-1388">Este cambio corrige un problema por el que el carácter "@" cargado en un archivo CSV causaba que la cadena tras el carácter "@" se convirtiera en una fórmula.</span><span class="sxs-lookup"><span data-stu-id="af9df-1388">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>
- <span data-ttu-id="af9df-1389">Se ha corregido un problema por el que los valores decimales de la función SECUENCIA no se redondeaban correctamente.</span><span class="sxs-lookup"><span data-stu-id="af9df-1389">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1390">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1390">Outlook</span></span>

- <span data-ttu-id="af9df-1391">Corrige un problema por el que los safelinks muy largos en los que los usuarios hacían clic en el cliente de escritorio de Outlook no se podían cargar debido a un truncamiento.</span><span class="sxs-lookup"><span data-stu-id="af9df-1391">Addresses an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>
- <span data-ttu-id="af9df-1392">Se ha corregido un problema por el que las carpetas de Outlook con nombres que contenían caracteres DBCS (conjunto de caracteres de doble byte) desaparecían intermitentemente al sincronizar con el servidor.</span><span class="sxs-lookup"><span data-stu-id="af9df-1392">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="af9df-1393">Esto sucedía si Outlook estaba configurado con una cuenta IMAP y se ejecutaba en un sistema con la configuración regional configurada en japonés.</span><span class="sxs-lookup"><span data-stu-id="af9df-1393">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1394">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1394">PowerPoint</span></span>

- <span data-ttu-id="af9df-1395">Se ha corregido un problema por el que el borrador de los comentarios dejaba de estar disponible si un usuario creaba un comentario sin publicarlo, cerraba el panel de comentarios, abría una nueva ventana, se desplazaba por varias diapositivas, cerraba la ventana y volvía a abrir el panel de comentarios en la presentación original.</span><span class="sxs-lookup"><span data-stu-id="af9df-1395">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-1396">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-1396">Project</span></span>

- <span data-ttu-id="af9df-1397">Se ha corregido un problema por el que, si Project estaba conectado a Project Web App y el separador decimal era una coma, el método TaskDependencies Add producía un error al agregar retardo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1397">Fixed an issue where if Project is connected to the Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1398">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1398">Word</span></span>

- <span data-ttu-id="af9df-1399">Se ha corregido un problema por el que la inserción de comentarios en un documento en el modo de colaboración no funcionaba en ocasiones.</span><span class="sxs-lookup"><span data-stu-id="af9df-1399">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>
- <span data-ttu-id="af9df-1400">Este cambio corrige un problema por el que la tarjeta de contactos parpadeaba si se hacía clic en la mención @.</span><span class="sxs-lookup"><span data-stu-id="af9df-1400">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>
- <span data-ttu-id="af9df-p176">Se ha corregido el problema por el que al cerrar un documento con borrador de comentarios se preguntaba al usuario si deseaba cerrar el documento sin guardar los comentarios del borrador. Al cancelar la solicitud, se cerraba el documento en lugar de quedar abierto.</span><span class="sxs-lookup"><span data-stu-id="af9df-p176">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments. Cancelling the prompt would close the document rather than leaving it open.</span></span>
- <span data-ttu-id="af9df-1403">Se ha corregido un problema por el que al traducir un comentario publicado se producía el error "Error al insertar el texto traducido".</span><span class="sxs-lookup"><span data-stu-id="af9df-1403">Fixed an issue where translating a posted comment would result in the error "Inserting translated text failed".</span></span>
- <span data-ttu-id="af9df-p177">En la Vista web o en el lector inmersivo, al hacer clic en una sugerencia se desplazaba a la parte superior incluso aunque ya estuviera a la vista. Este error se ha corregido.</span><span class="sxs-lookup"><span data-stu-id="af9df-p177">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view. This has been fixed.</span></span>
- <span data-ttu-id="af9df-1406">Se ha corregido un problema por el que al intentar guardar un archivo que contenía una macro con un nombre nuevo, este se guardaba con la extensión. docx y el nombre de archivo WRO0004.docx, independientemente de lo que el usuario escribiera, lo que hacía que el archivo no se pudiera volver a usar.</span><span class="sxs-lookup"><span data-stu-id="af9df-1406">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)


## <a name="version-2005-april-24"></a><span data-ttu-id="af9df-1408">Versión 2005: 24 de abril</span><span class="sxs-lookup"><span data-stu-id="af9df-1408">Version 2005: April 24</span></span>
<span data-ttu-id="af9df-1409">*Versión 2005 (compilación 12816.20006)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1409">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1411">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1411">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-1412">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1412">Excel</span></span>
- <span data-ttu-id="af9df-1413">Este cambio corrige un problema en el que el valor de la línea de tendencia del gráfico R-cuadrado (en el caso de la intersección forzada y) era incorrecto aunque la función de ESTIMACIÓN devuelva el valor correcto.</span><span class="sxs-lookup"><span data-stu-id="af9df-1413">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="af9df-1414">Este cambio arregla un problema en el que no siempre se guardaba el formato de la línea de tendencia de los gráficos personalizados.</span><span class="sxs-lookup"><span data-stu-id="af9df-1414">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1415">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1415">Outlook</span></span>
- <span data-ttu-id="af9df-1416">Corregido un problema por el que se desactivó el botón de Categorizar para los calendarios de grupo en la cinta de opciones de Office.</span><span class="sxs-lookup"><span data-stu-id="af9df-1416">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="af9df-1417">Se ha solucionado un problema por el que los clientes de las empresas con carpetas de grupo no implementadas o que no funcionaban, hacían que Outlook mostrara un mensaje de "no responde".</span><span class="sxs-lookup"><span data-stu-id="af9df-1417">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1418">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1418">PowerPoint</span></span>
- <span data-ttu-id="af9df-1419">Se ha solucionado un problema por el que al pasar el ratón por encima del símbolo del asterisco (\*) no aparecía el nombre de usuario y la fecha de la última persona que actualizó el documento.</span><span class="sxs-lookup"><span data-stu-id="af9df-1419">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1420">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1420">Word</span></span>
- <span data-ttu-id="af9df-p178">Al habilitar la opción "Mostrar marcadores" no se mostraban los marcadores. Este error se ha corregido.</span><span class="sxs-lookup"><span data-stu-id="af9df-p178">Enabling the option "Show bookmarks" would not display bookmarks. This has been fixed.</span></span>
- <span data-ttu-id="af9df-1423">Este cambio arregla un problema por el que el texto con hipervínculos puede no aparecer si la opción "Mostrar códigos de campo en lugar de sus valores" estaba activada.</span><span class="sxs-lookup"><span data-stu-id="af9df-1423">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (NO ELIMINAR LOS DETALLES DEL CONTENIDO FINAL)


## <a name="version-2005-april-17"></a><span data-ttu-id="af9df-1425">Versión 2005: 17 de abril</span><span class="sxs-lookup"><span data-stu-id="af9df-1425">Version 2005: April 17</span></span>
<span data-ttu-id="af9df-1426">*Versión 2005 (compilación 12810.20002)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1426">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1428">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1428">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-1429">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1429">Excel</span></span>
- <span data-ttu-id="af9df-1430">Se aumentó el tamaño de los controles de edición de referencia de celda en el cuadro de diálogo Barras de error personalizadas utilizado con gráficos.</span><span class="sxs-lookup"><span data-stu-id="af9df-1430">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="af9df-1431">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="af9df-1431">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="af9df-1432">Corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.</span><span class="sxs-lookup"><span data-stu-id="af9df-1432">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="af9df-1433">Application.Evaluate (VBA) no funcionaba para funciones definidas por el usuario en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="af9df-1433">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="af9df-1434">Este cambio corrige un problema que hacía que la información de formato condicional (CF) no se guardase correctamente en los archivos XLSB.</span><span class="sxs-lookup"><span data-stu-id="af9df-1434">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="af9df-1435">OneNote</span><span class="sxs-lookup"><span data-stu-id="af9df-1435">OneNote</span></span>
- <span data-ttu-id="af9df-1436">Corregido un problema en el que los saltos de línea se almacenaban como pestañas verticales.</span><span class="sxs-lookup"><span data-stu-id="af9df-1436">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1437">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1437">Outlook</span></span>
- <span data-ttu-id="af9df-1438">Soluciona un problema que hacía que los usuarios no pudieran agregar un grupo de contactos personal como asistente de la reunión.</span><span class="sxs-lookup"><span data-stu-id="af9df-1438">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="af9df-1439">Soluciona un problema que provocaba que las reuniones para las que faltan más de 2 meses no muestren un tema de reunión en el Asistente de programación.</span><span class="sxs-lookup"><span data-stu-id="af9df-1439">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="af9df-1440">Soluciona un problema que hacía que los usuarios vieran el truncamiento del cuerpo del mensaje al reenviar mensajes HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="af9df-1440">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="af9df-1441">Se agregó la capacidad de aplicar la configuración de firma predeterminada de S/MIME a través de la directiva de grupo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1441">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="af9df-1442">Se solucionó un problema que hacía que las reglas de eliminación creadas para los buzones que no fueran el buzón principal del usuario dejaran de ser válidas.</span><span class="sxs-lookup"><span data-stu-id="af9df-1442">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="af9df-1443">Se solucionó un problema que hacía que los datos adjuntos se perdieran al reenviar un mensaje cifrado.</span><span class="sxs-lookup"><span data-stu-id="af9df-1443">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-1444">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-1444">Project</span></span>
- <span data-ttu-id="af9df-1445">Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se activa un evento ProjectBeforeTaskChange adicional.</span><span class="sxs-lookup"><span data-stu-id="af9df-1445">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="af9df-1446">Se solucionó un problema por el cual Proyect podía bloquearse al cambiar el campo de estado del tablero en un proyecto que conectado a una lista de tareas de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="af9df-1446">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="af9df-1447">Corregido un problema por el que Project podía bloquearse al guardar proyectos creados con versiones anteriores de Project.</span><span class="sxs-lookup"><span data-stu-id="af9df-1447">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)


## <a name="version-2004-april-10"></a><span data-ttu-id="af9df-1449">Versión 2004: 10 de abril</span><span class="sxs-lookup"><span data-stu-id="af9df-1449">Version 2004: April 10</span></span>
<span data-ttu-id="af9df-1450">*Versión 2004 (compilación 12730.20024)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1450">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-1452">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-1452">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="af9df-1453">Access</span><span class="sxs-lookup"><span data-stu-id="af9df-1453">Access</span></span>

- <span data-ttu-id="af9df-1454">**Omita el cuadro de diálogo Mostrar tabla, vaya directamente a un panel de tareas y simplifique la adición de tablas y consultas:** agregue tablas y consultas haciendo clic en cuatro pestañas, seleccionando múltiples nombres, buscando por texto y arrastrando desde un panel de tareas que permanece abierto mientras trabaja.</span><span class="sxs-lookup"><span data-stu-id="af9df-1454">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="af9df-1455">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1455">Excel</span></span>

- <span data-ttu-id="af9df-1456">**Selector de contenido de M365 Premium:** de vida a sus documentos.</span><span class="sxs-lookup"><span data-stu-id="af9df-1456">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="af9df-1457">Explore gratis miles de imágenes, iconos y adhesivos. [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="af9df-1457">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1458">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1458">Outlook</span></span>

- <span data-ttu-id="af9df-1459">**Selector de contenido de M365 Premium:** de vida a sus documentos.</span><span class="sxs-lookup"><span data-stu-id="af9df-1459">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="af9df-1460">Explore gratis miles de imágenes, iconos y adhesivos. [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="af9df-1460">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="af9df-1461">**Mantenga la fidelidad de sus imágenes cuando las envíe como parte de un correo electrónico:** una nueva configuración de Outlook está disponible para limitar la compresión de imágenes cuando envía imágenes como parte de contenido del correo electrónico</span><span class="sxs-lookup"><span data-stu-id="af9df-1461">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1462">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1462">PowerPoint</span></span>

- <span data-ttu-id="af9df-1463">**Selector de contenido de M365 Premium:** de vida a sus documentos.</span><span class="sxs-lookup"><span data-stu-id="af9df-1463">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="af9df-1464">Explore gratis miles de imágenes, iconos y adhesivos. [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="af9df-1464">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="af9df-1465">**Sincronice los cambios mientras realiza la presentación:** sincronice los cambios cuando se hagan aunque la presentación esté en el modo de presentación con diapositivas.</span><span class="sxs-lookup"><span data-stu-id="af9df-1465">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1466">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1466">Word</span></span>

- <span data-ttu-id="af9df-1467">**Selector de contenido de M365 Premium:** de vida a sus documentos.</span><span class="sxs-lookup"><span data-stu-id="af9df-1467">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="af9df-1468">Explore gratis miles de imágenes, iconos y adhesivos. [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="af9df-1468">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="af9df-1469">**Anote su copia privada:** cree notas escritas a mano privadas realizando una copia privada de un documento compartido.</span><span class="sxs-lookup"><span data-stu-id="af9df-1469">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="af9df-1470">Vaya a Ver > Crear una copia privada para empezar.</span><span class="sxs-lookup"><span data-stu-id="af9df-1470">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1473">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1473">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="af9df-1474">Access</span><span class="sxs-lookup"><span data-stu-id="af9df-1474">Access</span></span>

- <span data-ttu-id="af9df-1475">Se han corregido problema al cambiar el tamaño y actualizar tablas en el panel de tareas.</span><span class="sxs-lookup"><span data-stu-id="af9df-1475">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="af9df-1476">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1476">Excel</span></span>

- <span data-ttu-id="af9df-1477">Se ha corregido un problema por el que seleccionar un rango de celdas en una hoja daba lugar a la selección de una sola celda.</span><span class="sxs-lookup"><span data-stu-id="af9df-1477">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="af9df-1478">Se ha corregido un problema que podía provocar que Excel dejara de responder al reducir el tamaño de un gráfico con algunos rangos de eje x.</span><span class="sxs-lookup"><span data-stu-id="af9df-1478">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="af9df-1479">Se ha corregido un problema que provocaba que al insertar una plantilla de gráfico definida por el usuario como predeterminada se guardara como un gráfico de columnas.</span><span class="sxs-lookup"><span data-stu-id="af9df-1479">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="af9df-1480">Se ha corregido un problema por el que las etiquetas de datos en los gráficos se mostraban en blanco cuando las celdas de datos subyacentes no tuvieran un título.</span><span class="sxs-lookup"><span data-stu-id="af9df-1480">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="af9df-1481">Se ha corregido un problema por el que, en una hoja de Excel con referencia de celda F1C1 habilitada y en coautoría o compartida, al pasar el ratón por el icono de presencia del usuario no se mostraba la referencia de celda activa en modo F1C1.</span><span class="sxs-lookup"><span data-stu-id="af9df-1481">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1482">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1482">Outlook</span></span>

- <span data-ttu-id="af9df-1483">Corrige un problema que provocaba que las categorías desapareciesen en ocasiones de los mensajes de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="af9df-1483">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="af9df-1484">Corrige un problema que provocaba que los delegados viesen distintas jerarquías de carpetas en diferentes equipos para los buzones compartidos.</span><span class="sxs-lookup"><span data-stu-id="af9df-1484">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="af9df-1485">Corrige un problema que provocaba que los usuarios experimentasen un error al intentar ver las propiedades de un formulario de la organización.</span><span class="sxs-lookup"><span data-stu-id="af9df-1485">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="af9df-1486">Corrige un problema que provocaba que se produjesen errores en la activación de algunos avisos al cambiar la zona horaria en un equipo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1486">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1487">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1487">PowerPoint</span></span>

- <span data-ttu-id="af9df-1488">Este cambio corrige un problema en el que es posible que no siempre se muestre el título del gráfico al representar un gráfico de Excel heredado incrustado como objeto OLE en PowerPoint o Word.</span><span class="sxs-lookup"><span data-stu-id="af9df-1488">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="af9df-1489">Se ha corregido un problema por el que al copiar texto de Excel en PowerPoint podía cambiar el formato.</span><span class="sxs-lookup"><span data-stu-id="af9df-1489">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="af9df-1490">Este cambio corrige un problema que provocaba que la búsqueda de caracteres especiales con "Buscar solo palabras completas" no siempre funcionase como se esperaba.</span><span class="sxs-lookup"><span data-stu-id="af9df-1490">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-1491">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-1491">Project</span></span>

- <span data-ttu-id="af9df-1492">Se corrigió un problema por el que el usuario no podía especificar el trabajo previsto con fases temporales al activar la configuración para proteger el trabajo real.</span><span class="sxs-lookup"><span data-stu-id="af9df-1492">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1493">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1493">Word</span></span>

- <span data-ttu-id="af9df-1494">Este cambio corrige un problema que provoca que al colocar el cursor sobre una sugerencia no se resalte la tarjeta.</span><span class="sxs-lookup"><span data-stu-id="af9df-1494">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="af9df-1495">Este cambio corrige un problema que hacía que el texto de las formas agrupadas desapareciera temporalmente al usar la herramienta Selección de lazo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1495">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="af9df-1496">Este cambio corrige un problema en el que es posible que no siempre se muestre el título del gráfico al representar un gráfico de Excel heredado incrustado como objeto OLE en PowerPoint o Word.</span><span class="sxs-lookup"><span data-stu-id="af9df-1496">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="af9df-1497">Este cambio corrige un problema por el que, en la vista de dos páginas, al crear un comentario, el anclaje del comentario no siempre aparecía.</span><span class="sxs-lookup"><span data-stu-id="af9df-1497">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="af9df-1498">Se ha corregido un problema que hacía que si un párrafo con un estilo antecesor de un estilo estaba vinculado a una lista, se podía perder la numeración de la lista.</span><span class="sxs-lookup"><span data-stu-id="af9df-1498">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2004-march-27"></a><span data-ttu-id="af9df-1500">Versión 2004: 27 de marzo</span><span class="sxs-lookup"><span data-stu-id="af9df-1500">Version 2004: March 27</span></span>
<span data-ttu-id="af9df-1501">*Versión 2004 (compilación 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1501">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-1503">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-1503">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-1504">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1504">Outlook</span></span>

- <span data-ttu-id="af9df-1505">**Nueva opción para desactivar la mención de sugerencias al escribir el correo:**¿Encuentra el selector de @ menciones más molesto que útil?</span><span class="sxs-lookup"><span data-stu-id="af9df-1505">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="af9df-1506">Ahora puede apagarlo si lo prefiere.</span><span class="sxs-lookup"><span data-stu-id="af9df-1506">Now you can turn it off if you prefer.</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1509">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1509">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-1510">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1510">Outlook</span></span>
- <span data-ttu-id="af9df-1511">Aborde un problema que hizo que el botón "Guardar en la nube" faltara en las herramientas de adjuntos.</span><span class="sxs-lookup"><span data-stu-id="af9df-1511">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="af9df-1512">Aborde un problema que hizo que los usuarios no pudieran agregar una firma al responder a un mensaje administrado con derechos digitales desde una ventana de inspección cuando el usuario no tiene permiso de propietario sobre el mensaje al que se responde.</span><span class="sxs-lookup"><span data-stu-id="af9df-1512">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="af9df-1513">Aborde un problema que hizo que los usuarios no pudieran agregar archivos adjuntos adicionales desde una ubicación web a una reunión creada previamente.</span><span class="sxs-lookup"><span data-stu-id="af9df-1513">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1514">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1514">PowerPoint</span></span>
- <span data-ttu-id="af9df-1515">Este cambio corrige un error que podría causar que los archivos de PowerPoint que contienen emojis fallen al guardarlos.</span><span class="sxs-lookup"><span data-stu-id="af9df-1515">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-1516">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-1516">Project</span></span>
- <span data-ttu-id="af9df-1517">Se ha solucionado un problema por el que si se ejecuta "Lista de valores de campos personalizados GetItem" y no existe una tabla de búsqueda para el campo personalizado, se crea una tabla de búsqueda vacía aunque no debería existir.</span><span class="sxs-lookup"><span data-stu-id="af9df-1517">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1518">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1518">Word</span></span>
- <span data-ttu-id="af9df-1519">Este cambio corrige un problema con varias páginas seleccionadas en el menú Ver, donde el panel de comentarios podía mostrarse en blanco.</span><span class="sxs-lookup"><span data-stu-id="af9df-1519">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2004-march-20"></a><span data-ttu-id="af9df-1521">Versión 2004: 20 de marzo</span><span class="sxs-lookup"><span data-stu-id="af9df-1521">Version 2004: March 20</span></span>
<span data-ttu-id="af9df-1522">*Versión 2004 (compilación 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1522">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (NO QUITAR DETALLES DE CARACTERÍSTICAS CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-1524">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-1524">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-1525">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1525">Outlook</span></span>

- <span data-ttu-id="af9df-1526">**Actualización visual del calendario:** el año pasado, hemos incorporado una experiencia de correo actualizada y este año le toca al calendario tener una cara nueva.</span><span class="sxs-lookup"><span data-stu-id="af9df-1526">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="af9df-1527">Las actualizaciones son recientes pero son familiares, para que, como usuario de Outlook veterano, pueda empezar a ser más productivo en seguida.</span><span class="sxs-lookup"><span data-stu-id="af9df-1527">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="af9df-1528">**Protección de datos del grupo:** la etiqueta de confidencialidad que elija al crear un grupo se aplica al correo electrónico, a los documentos y a los sitios del grupo</span><span class="sxs-lookup"><span data-stu-id="af9df-1528">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1529">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1529">PowerPoint</span></span>

- <span data-ttu-id="af9df-1530">**Actualización de las diapositivas durante la presentación:** actualice diapositivas editadas por otros autores durante la presentación.</span><span class="sxs-lookup"><span data-stu-id="af9df-1530">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1533">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1533">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-1534">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1534">Excel</span></span>

- <span data-ttu-id="af9df-1535">Este cambio corrige retrasos al procesar imágenes con información de protocolo mal formada o incorrecta.</span><span class="sxs-lookup"><span data-stu-id="af9df-1535">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1536">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1536">Outlook</span></span>

- <span data-ttu-id="af9df-1537">Este cambio corrige retrasos al procesar imágenes con información de protocolo mal formada o incorrecta.</span><span class="sxs-lookup"><span data-stu-id="af9df-1537">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="af9df-1538">Este cambio corrige un problema por el que los cambios más recientes en los borradores de correo electrónico no se actualizaban.</span><span class="sxs-lookup"><span data-stu-id="af9df-1538">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="af9df-1539">Se corrigió un problema por el que hacer clic derecho del mouse en un archivo y usar "Enviar a" no funcionaba.</span><span class="sxs-lookup"><span data-stu-id="af9df-1539">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="af9df-1540">Se corrigió un problema por el que si un usuario tenía una ruta de búsqueda personalizada para la libreta de direcciones, el ámbito de la resolución de nombres de Outlook se limitaba a la ruta personalizada, en lugar de incluir la lista global de direcciones (LGD).</span><span class="sxs-lookup"><span data-stu-id="af9df-1540">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="af9df-1541">Se corrigió un problema por el que, al ordenar los resultados por categorías, en un conjunto de resultados de búsqueda devuelto no se mostraban los colores de la categoría.</span><span class="sxs-lookup"><span data-stu-id="af9df-1541">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-1542">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-1542">Project</span></span>

- <span data-ttu-id="af9df-1543">Se corrigió un problema por el que el evento "ProjectBeforeTaskChange" de las aplicaciones de Visual Basic (VBA) no se activaba cuando un usuario hacía clic en el botón "Desactivar" que se encuentra en la cinta de tareas en el grupo de programación.</span><span class="sxs-lookup"><span data-stu-id="af9df-1543">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="af9df-1544">Si establece los detalles de predecesor o sucesor desde una vista de tipo formulario, el evento de las aplicaciones de Visual Basic (VBA) ProjectBeforeTaskChange no siempre captura los cambios.</span><span class="sxs-lookup"><span data-stu-id="af9df-1544">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="af9df-1545">Por ejemplo, si ha eliminado una dependencia y ha hecho clic en Aceptar en el formulario, el evento no se ha desencadenado.</span><span class="sxs-lookup"><span data-stu-id="af9df-1545">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="af9df-1546">Este comportamiento se ha corregido.</span><span class="sxs-lookup"><span data-stu-id="af9df-1546">This behavior has been fixed.</span></span>

- <span data-ttu-id="af9df-1547">Se corrigió un problema por el que los valores más recientes del coste real del trabajo realizado (CRTR) no se mostraba después de realizar un cambio, como un cambio de fecha.</span><span class="sxs-lookup"><span data-stu-id="af9df-1547">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="af9df-1548">Se corrigió un problema por el que al abrir un proyecto con el menú Usados más recientemente se abría el archivo de proyecto con acceso de lectura y escritura.</span><span class="sxs-lookup"><span data-stu-id="af9df-1548">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="af9df-1549">Este cambio corrige un problema por el que si creaba una tarea manual con una fecha y hora de inicio (sin la duración), se mostraba con una hora incorrecta en la escala de tiempo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1549">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="af9df-1550">Se corrigió un problema por el que la impresión de una escala de tiempo con el calendario Hijri saltaba un mes o lo duplicaba en la vista de impresión.</span><span class="sxs-lookup"><span data-stu-id="af9df-1550">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="af9df-1551">Este cambio resuelve un problema por el que trabajar en el Organizador de equipo con objetos de GDI podía provocar la sobreasignación de dichos objetos y crear condiciones de memoria insuficiente.</span><span class="sxs-lookup"><span data-stu-id="af9df-1551">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1552">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1552">Word</span></span>

- <span data-ttu-id="af9df-1553">Se corrigió un problema por el que se había deshabilitado la función para publicar comentarios.</span><span class="sxs-lookup"><span data-stu-id="af9df-1553">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="af9df-1554">Este cambio corrige retrasos al procesar imágenes con información de protocolo mal formada o incorrecta.</span><span class="sxs-lookup"><span data-stu-id="af9df-1554">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="af9df-1555">Este cambio resuelve un problema en el que el administrador de cuentas no enviaba mensajes, lo que provocaba un error en aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="af9df-1555">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="af9df-1556">Este cambio corrige un problema en el que la tabla de contenido se actualizaba con estilos de título que no estaban presentes en el documento.</span><span class="sxs-lookup"><span data-stu-id="af9df-1556">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="af9df-1557">Se corrigió un problema por el que las firmas digitales guardadas en documentos de Word se eliminaban al enviar los documentos.</span><span class="sxs-lookup"><span data-stu-id="af9df-1557">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2004-march-13"></a><span data-ttu-id="af9df-1559">Versión 2004: 13 de marzo</span><span class="sxs-lookup"><span data-stu-id="af9df-1559">Version 2004: March 13</span></span>
<span data-ttu-id="af9df-1560">*Versión 2004 (compilación 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1560">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (NO QUITAR DETALLES DE CARACTERÍSTICAS CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-1562">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-1562">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="af9df-1563">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1563">Excel</span></span>
- <span data-ttu-id="af9df-1564">**Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados.</span><span class="sxs-lookup"><span data-stu-id="af9df-1564">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="af9df-1565">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-1565">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="af9df-1566">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1566">PowerPoint</span></span>
- <span data-ttu-id="af9df-1567">**Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados.</span><span class="sxs-lookup"><span data-stu-id="af9df-1567">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="af9df-1568">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-1568">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="af9df-1569">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1569">Word</span></span>
- <span data-ttu-id="af9df-1570">**Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados.</span><span class="sxs-lookup"><span data-stu-id="af9df-1570">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="af9df-1571">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-1571">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1574">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1574">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="af9df-1575">Access</span><span class="sxs-lookup"><span data-stu-id="af9df-1575">Access</span></span>
- <span data-ttu-id="af9df-1576">Se ha corregido un problema por el que las versiones internacionales de Access mostraban cadenas en inglés en la interfaz de usuario.</span><span class="sxs-lookup"><span data-stu-id="af9df-1576">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="af9df-1577">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1577">Excel</span></span>
- <span data-ttu-id="af9df-1578">Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al editar un rango de celdas grande por programación.</span><span class="sxs-lookup"><span data-stu-id="af9df-1578">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="af9df-1579">Se ha corregido un problema de rendimiento al abrir archivos CSV con entornos japoneses.</span><span class="sxs-lookup"><span data-stu-id="af9df-1579">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1580">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1580">Outlook</span></span>
- <span data-ttu-id="af9df-1581">Corrige un problema que causaba que la fecha de "última modificación" de un archivo se actualizara al agregar un archivo adjunto a un correo electrónico o al guardar un archivo adjunto desde un correo arrastrándolo y colocándolo (en lugar de hacerlo a través de un menú).</span><span class="sxs-lookup"><span data-stu-id="af9df-1581">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="af9df-1582">Corrige un problema que provocaba que al presionar Entrar en el panel de búsqueda expandido no se iniciara la búsqueda y requería que los usuarios hiciesen clic en el botón de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="af9df-1582">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="af9df-1583">Se ha corregido un problema por el que la búsqueda no muestra información sobre los usuarios cuando se ha deshabilitado la opción "Mostrar fotografías de usuario cuando estén disponibles".</span><span class="sxs-lookup"><span data-stu-id="af9df-1583">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="af9df-1584">Project</span><span class="sxs-lookup"><span data-stu-id="af9df-1584">Project</span></span>
- <span data-ttu-id="af9df-1585">Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.</span><span class="sxs-lookup"><span data-stu-id="af9df-1585">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="af9df-1586">Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="af9df-1586">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1587">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1587">Word</span></span>
- <span data-ttu-id="af9df-1588">Se ha corregido un problema por el que al escribir o editar un comentario y usar Ctrl + A se seleccionaba texto en el lienzo en lugar de seleccionar texto en la tarjeta del comentario.</span><span class="sxs-lookup"><span data-stu-id="af9df-1588">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="af9df-1589">Se ha corregido un problema por el que la alineación de las palabras de un documento se puede codificar al intentar editar después de imprimir con la impresión rápida.</span><span class="sxs-lookup"><span data-stu-id="af9df-1589">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="af9df-1590">Se ha corregido un problema al combinar dos documentos en uno.</span><span class="sxs-lookup"><span data-stu-id="af9df-1590">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="af9df-1591">Se ha corregido un problema que hacía que el marcado de revisiones que impliquen ecuaciones ocasionase un error al guardar el archivo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1591">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-march-06"></a><span data-ttu-id="af9df-1593">Versión 2003: 06 de marzo</span><span class="sxs-lookup"><span data-stu-id="af9df-1593">Version 2003: March 06</span></span>
<span data-ttu-id="af9df-1594">*Versión 2003 (compilación 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1594">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1596">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1596">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-1597">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1597">Outlook</span></span>

- <span data-ttu-id="af9df-1598">Se ha corregido un problema que hacía que la creación de una regla con Outlook Web Access no se almacenara en el servidor de Exchange y producía un conflicto.</span><span class="sxs-lookup"><span data-stu-id="af9df-1598">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="af9df-1599">Se ha corregido un problema por el que, en el modo oscuro de Outlook, no se mostraba la lista desplegable en el campo "De:".</span><span class="sxs-lookup"><span data-stu-id="af9df-1599">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="af9df-1600">Corrige un problema por el que los usuarios no pueden adjuntar un archivo a un mensaje de correo electrónico a través del explorador de archivos cuando el archivo se abre en otra aplicación.</span><span class="sxs-lookup"><span data-stu-id="af9df-1600">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1601">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1601">PowerPoint</span></span>

- <span data-ttu-id="af9df-1602">Se ha corregido un problema por el que las miniaturas recomendadas parpadean al pasar el ratón por encima de las miniaturas.</span><span class="sxs-lookup"><span data-stu-id="af9df-1602">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="af9df-1603">En algunos casos, esto provocaba un bloqueo de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="af9df-1603">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1604">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1604">Word</span></span>

- <span data-ttu-id="af9df-1605">Se ha corregido un problema con la característica de comparación de los documentos protegidos para la edición.</span><span class="sxs-lookup"><span data-stu-id="af9df-1605">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="af9df-1606">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-1606">Office Suite</span></span>

- <span data-ttu-id="af9df-1607">Se ha corregido un problema en Word/Excel/PowerPoint donde el nombre principal de usuario (UPN) ya no distingue entre mayúsculas y minúsculas, lo que provoca menos errores al trabajar con archivos en SharePoint.</span><span class="sxs-lookup"><span data-stu-id="af9df-1607">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="af9df-1608">Se ha corregido un problema estético en el que el botón "Aceptar" del cuadro de diálogo de Archivo \ Opciones se mostraba atenuado, pero la función no se veía afectada.</span><span class="sxs-lookup"><span data-stu-id="af9df-1608">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

[//]: # (NO QUITAR DETALLES DE CARACTERÍSTICAS CONTENIDO INICIO)

## <a name="version-2003-february-28"></a><span data-ttu-id="af9df-1611">Versión 2003: 28 de febrero</span><span class="sxs-lookup"><span data-stu-id="af9df-1611">Version 2003: February 28</span></span>
<span data-ttu-id="af9df-1612">*Versión de 2003 (compilación 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1612">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-1614">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-1614">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-1615">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1615">Outlook</span></span>

- <span data-ttu-id="af9df-1616">**Notificación de incidentes para administradores de TI:** se notificará a los administradores globales de espacios empresariales de Microsoft 365 y a los administradores de aplicaciones de Office acerca de los incidentes de Outlook y Exchange de O365 que afectan a sus usuarios con una nueva notificación en el panel derecho en Outlook para Windows.</span><span class="sxs-lookup"><span data-stu-id="af9df-1616">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="af9df-1617">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-1617">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a><span data-ttu-id="af9df-1618">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1618">PowerPoint</span></span>

- <span data-ttu-id="af9df-1619">**Se ha mejorado la experiencia de creación de diagramas con entrada de lápiz a formas:** dibuje mejores diagramas y convierta en objetos de Office que pueda manipular [Obtenga más información.](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="af9df-1619">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1622">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1622">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af9df-1623">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1623">Excel</span></span>

- <span data-ttu-id="af9df-1624">Se ha corregido un problema en el que el texto de una segmentación de datos no se escala correctamente en la vista previa de impresión.</span><span class="sxs-lookup"><span data-stu-id="af9df-1624">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1625">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1625">Outlook</span></span>

- <span data-ttu-id="af9df-1626">Corrige un problema que causaba que la fecha de "última modificación" de un archivo se actualizara al agregar un archivo adjunto a un correo electrónico o al guardar un archivo adjunto desde un correo arrastrándolo y colocándolo (en lugar de hacerlo a través de un menú).</span><span class="sxs-lookup"><span data-stu-id="af9df-1626">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1627">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1627">Word</span></span>

- <span data-ttu-id="af9df-1628">Se ha corregido un problema por el que al ir a la tarjeta del comentario, el foco en el cuadro de edición del comentario no era visible.</span><span class="sxs-lookup"><span data-stu-id="af9df-1628">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="af9df-1629">Si se inserta un control (como un control de contenido de texto) en una ecuación, al guardar y abrir el archivo se produce un error de contenido ilegible.</span><span class="sxs-lookup"><span data-stu-id="af9df-1629">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="af9df-1630">Se ha corregido un problema que hacía que no se pudiera guardar un archivo protegido con contraseña anteriormente en un almacenamiento en la nube.</span><span class="sxs-lookup"><span data-stu-id="af9df-1630">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="af9df-1631">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-1631">Office Suite</span></span>

- <span data-ttu-id="af9df-1632">Corrige un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.</span><span class="sxs-lookup"><span data-stu-id="af9df-1632">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-february-21"></a><span data-ttu-id="af9df-1634">Versión 2003: 21 de febrero</span><span class="sxs-lookup"><span data-stu-id="af9df-1634">Version 2003: February 21</span></span>
<span data-ttu-id="af9df-1635">*Versión 2003 (compilación 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1635">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-1637">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-1637">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="af9df-1638">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-1638">Office Suite</span></span>

- <span data-ttu-id="af9df-1639">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="af9df-1639">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1642">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1642">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="af9df-1643">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1643">Excel</span></span>
- <span data-ttu-id="af9df-1644">Se ha corregido un problema que los usuarios pueden haber experimentado al cambiar el nombre de las medidas de tabla dinámica.</span><span class="sxs-lookup"><span data-stu-id="af9df-1644">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="af9df-1645">Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al usar una macro de VBA para borrar el contenido de un rango.</span><span class="sxs-lookup"><span data-stu-id="af9df-1645">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="af9df-1646">Se ha corregido un problema que provocaba que la interfaz de usuario parpadeara cuando un usuario ejecutaba una macro que interactuaba con la cinta de opciones.</span><span class="sxs-lookup"><span data-stu-id="af9df-1646">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="af9df-1647">Se ha corregido un problema por el que los archivos CSV se cargaban de forma incorrecta cuando la primera palabra del archivo estaba era TABLE.</span><span class="sxs-lookup"><span data-stu-id="af9df-1647">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="af9df-1648">Se ha corregido un problema por el que los usuarios pueden haber sufrido bloqueos al cambiar entre dos libros que tienen diferentes niveles de zoom.</span><span class="sxs-lookup"><span data-stu-id="af9df-1648">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1649">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1649">Outlook</span></span>
- <span data-ttu-id="af9df-1650">Se ha corregido un problema que provocaba que los usuarios no puedan abrir mensajes de la carpeta pública cuando Outlook se dejaba en marcha durante la noche.</span><span class="sxs-lookup"><span data-stu-id="af9df-1650">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="af9df-1651">Se ha corregido una condición en la que los botones "Permitir" y "Denegar" de la página de permisos se deshabilitan durante el flujo de trabajo de autenticación para agregar una cuenta de Gmail.</span><span class="sxs-lookup"><span data-stu-id="af9df-1651">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="af9df-1652">Se ha corregido un problema que hizo que Outlook generara inesperadamente resultados de registro en algunas situaciones, incluso cuando el registro se desactivaba.</span><span class="sxs-lookup"><span data-stu-id="af9df-1652">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1653">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1653">Word</span></span>
- <span data-ttu-id="af9df-1654">Se ha corregido un problema en el que las tarjetas con comentario no siempre se resaltan cuando se desplaza el puntero del mouse sobre la tarjeta del comentario.</span><span class="sxs-lookup"><span data-stu-id="af9df-1654">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="af9df-p192">Durante una sesión de coautoría de documentos activos, puede que agregar una imagen directamente en una tarjeta de comentario dé como resultado la adición de una etiqueta. Este problema se ha corregido.</span><span class="sxs-lookup"><span data-stu-id="af9df-p192">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag. This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="af9df-1657">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-1657">Office Suite</span></span>
- <span data-ttu-id="af9df-1658">Al usar las propiedades Multichoice/Lookup/Managed-metadata con documentos de Word/Excel/PowerPoint y guardar en una biblioteca de documentos de SharePoint, estas propiedades se limitaban anteriormente a 255 caracteres.</span><span class="sxs-lookup"><span data-stu-id="af9df-1658">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="af9df-1659">Cuando estas propiedades superaban 255 caracteres, estos documentos no se podían guardar.</span><span class="sxs-lookup"><span data-stu-id="af9df-1659">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="af9df-1660">Con este cambio, este límite se ha aumentado a 2048 caracteres.</span><span class="sxs-lookup"><span data-stu-id="af9df-1660">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-february-14"></a><span data-ttu-id="af9df-1662">Versión 2003: 14 de febrero</span><span class="sxs-lookup"><span data-stu-id="af9df-1662">Version 2003: February 14</span></span>
<span data-ttu-id="af9df-1663">*Versión 2003 (compilación 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1663">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-1665">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-1665">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-1666">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1666">Outlook</span></span>

- <span data-ttu-id="af9df-1667">**Nueva experiencia para redes WiFi cautivas:** ¿alguna vez se ha unido a una red WiFi que requiere una página web para iniciar sesión?</span><span class="sxs-lookup"><span data-stu-id="af9df-1667">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="af9df-1668">Outlook ahora lo detecta y le ayuda a estar conectado.</span><span class="sxs-lookup"><span data-stu-id="af9df-1668">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1669">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1669">Word</span></span>

- <span data-ttu-id="af9df-1670">**Busque el editor de entrada de lápiz en el cuadro de herramientas de dibujo:** seleccione Dibujar y seleccione el lápiz del editor de entrada de lápiz para editar el documento con el dedo o un lápiz digital.</span><span class="sxs-lookup"><span data-stu-id="af9df-1670">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="af9df-1671">Más información</span><span class="sxs-lookup"><span data-stu-id="af9df-1671">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="af9df-1672">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-1672">Office Suite</span></span>

- <span data-ttu-id="af9df-1673">**Iconos de la barra de estado más nítidos:** los iconos de la barra de estado ahora son más fáciles de ver</span><span class="sxs-lookup"><span data-stu-id="af9df-1673">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1676">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1676">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="af9df-1677">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1677">Outlook</span></span>

- <span data-ttu-id="af9df-1678">Se ha corregido un problema que provocaba que los usuarios perdieran el acceso al cuadro de diálogo de permisos de calendario "opciones de disponibilidad".</span><span class="sxs-lookup"><span data-stu-id="af9df-1678">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="af9df-1679">Se ha corregido un problema que podría provocar la alerta: "lo sentimos, tenemos problemas para abrir este elemento" al abrir algunas instancias de reuniones periódicas que se han enviado desde una zona horaria diferente.</span><span class="sxs-lookup"><span data-stu-id="af9df-1679">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="af9df-1680">Se ha corregido un problema que podría ocasionar que los usuarios no puedan abrir un archivo .msg después de arrastrar y soltar datos adjuntos desde el mensaje.</span><span class="sxs-lookup"><span data-stu-id="af9df-1680">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="af9df-1681">Se ha corregido un problema por el que, después de cargar un archivo adjunto desde Outlook a OneDrive, se podía cambiar el nombre de archivo si el nombre de los datos adjuntos contenía paréntesis.</span><span class="sxs-lookup"><span data-stu-id="af9df-1681">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1682">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1682">PowerPoint</span></span>

- <span data-ttu-id="af9df-1683">Se ha corregido un problema que podría provocar un error al guardar un documento en PowerPoint o en Word con un gráfico de Excel.</span><span class="sxs-lookup"><span data-stu-id="af9df-1683">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1684">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1684">Word</span></span>

- <span data-ttu-id="af9df-1685">Se ha corregido un problema por el que las imágenes de los documentos pierden transparencia al exportarse a PDF.</span><span class="sxs-lookup"><span data-stu-id="af9df-1685">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-february-07"></a><span data-ttu-id="af9df-1687">Versión 2002: 07 de febrero</span><span class="sxs-lookup"><span data-stu-id="af9df-1687">Version 2002: February 07</span></span>
<span data-ttu-id="af9df-1688">*Versión 2002 (Compilación 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="af9df-1688">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="af9df-1690">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="af9df-1690">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="af9df-1691">Access</span><span class="sxs-lookup"><span data-stu-id="af9df-1691">Access</span></span>

- <span data-ttu-id="af9df-1692">**Aumente su productividad con el Diseñador de consultas, la vista SQL y la ventana Relaciones:** haga clic con el botón derecho en una tabla para abrirla, diseñarla, cambiar su tamaño y ocultarla.</span><span class="sxs-lookup"><span data-stu-id="af9df-1692">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="af9df-1693">Buscar y reemplazar texto en la vista SQL.</span><span class="sxs-lookup"><span data-stu-id="af9df-1693">Search and replace text in SQL View.</span></span> <span data-ttu-id="af9df-1694">Seleccione múltiples tablas en la ventana Relaciones.</span><span class="sxs-lookup"><span data-stu-id="af9df-1694">Select multiple tables in the Relationships window.</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="af9df-1697">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="af9df-1697">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="af9df-1698">Acceso</span><span class="sxs-lookup"><span data-stu-id="af9df-1698">Access</span></span>

- <span data-ttu-id="af9df-p197">Esta actualización corrige un problema por el que al usar un objeto ADODB. Recorder en código de VB podía notificarse un error incorrectamente.</span><span class="sxs-lookup"><span data-stu-id="af9df-p197">This update fixes an issue where using an ADODB. Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="af9df-1701">Esta actualización corrige un problema que puede hacer que Microsoft Access no identifique una Columna de identidad en una tabla vinculada de SQL Server, lo que puede provocar que las filas aparezcan como eliminadas de forma incorrecta.</span><span class="sxs-lookup"><span data-stu-id="af9df-1701">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="af9df-1702">Excel</span><span class="sxs-lookup"><span data-stu-id="af9df-1702">Excel</span></span>

- <span data-ttu-id="af9df-1703">Se ha corregido un problema por el que Excel se bloquea al usar la opción Texto a columnas con matrices dinámicas.</span><span class="sxs-lookup"><span data-stu-id="af9df-1703">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="af9df-1704">Outlook</span><span class="sxs-lookup"><span data-stu-id="af9df-1704">Outlook</span></span>

- <span data-ttu-id="af9df-1705">Se ha corregido un problema en el que el desplazamiento en el calendario con la vista de mes no muestra eventos de calendario anteriores.</span><span class="sxs-lookup"><span data-stu-id="af9df-1705">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="af9df-1706">Corrige un problema que causaba que los usuarios sufrieran un error al visualizar más de 30 calendarios en un entorno Citrix.</span><span class="sxs-lookup"><span data-stu-id="af9df-1706">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af9df-1707">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af9df-1707">PowerPoint</span></span>

- <span data-ttu-id="af9df-1708">Se ha corregido un problema que provocaba que, después de cerrar un archivo, PowerPoint no lo quitara inmediatamente de la colección Presentaciones si había algún controlador de eventos en ejecución.</span><span class="sxs-lookup"><span data-stu-id="af9df-1708">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="af9df-1709">Por lo tanto, el número de presentaciones que informa el modelo de objetos es incorrecto y se evita el cierre de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="af9df-1709">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="af9df-1710">Se ha corregido un problema con el marcador de resaltado: los textos blancos con un marcador oscuro se imprimen como negros en escala de grises.</span><span class="sxs-lookup"><span data-stu-id="af9df-1710">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="af9df-1711">Word</span><span class="sxs-lookup"><span data-stu-id="af9df-1711">Word</span></span>

- <span data-ttu-id="af9df-1712">Al actualizar y desplazarse por una tabla de contenido, es posible que se muestre un área gris en el documento.</span><span class="sxs-lookup"><span data-stu-id="af9df-1712">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="af9df-1713">Se ha corregido un problema por el que si se trabajaba en coautoría en un documento, la versión de borrador de un comentario raíz podía no conservarse.</span><span class="sxs-lookup"><span data-stu-id="af9df-1713">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="af9df-1714">Se ha corregido un problema por el que al ir de una tarjeta de comentario a otra se podía mostrar el comentario seleccionado inicialmente con una selección resaltada.</span><span class="sxs-lookup"><span data-stu-id="af9df-1714">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="af9df-1715">Se ha corregido un problema por el que usar "Examinar" para guardar un archivo podía no funcionar si se escribió un comentario sin publicarlo y el usuario intentó guardar el archivo.</span><span class="sxs-lookup"><span data-stu-id="af9df-1715">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="af9df-1716">Con el Control de cambios habilitado y el panel de comentarios cerrado, Ctrl + Alt + M podía no funcionar para abrir el panel Comentarios.</span><span class="sxs-lookup"><span data-stu-id="af9df-1716">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="af9df-1717">Corregido un problema al agregar una @mención en una tabla que podía generar el mensaje de error: "Una tabla de este documento está dañada".</span><span class="sxs-lookup"><span data-stu-id="af9df-1717">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="af9df-1718">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="af9df-1718">Office Suite</span></span>

- <span data-ttu-id="af9df-1719">Resuelto un problema que podía causar que el paquete de herramientas de corrección de Noruega Nynorsk (NN-no) no se instalara correctamente.</span><span class="sxs-lookup"><span data-stu-id="af9df-1719">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)


[//]: # (NO MODIFICAR EL INICIO DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
[//]: # (|Win32|DevMain|Insiders| |16.0.14107.20000|version-2106-may-14|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14029.20000|version-2106-may-07|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14026.20000|version-2105-april-30|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14014.20002|version-2105-april-23|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14007.20002|version-2105-april-16|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14002.20000|version-2105-april-09|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13929.20016|version-2104-april-02|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13919.20002|version-2104-march-26|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13913.20000|versión-2104-marzo-19|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13906.20000|version-2104-march-12|)
[//]: # (NO MODIFICAR EL FIN DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
