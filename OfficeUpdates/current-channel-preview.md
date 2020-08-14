---
title: Notas de la versión del canal actual (versión preliminar)
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 'Proporciona a los participantes del modo anticipado de Insider Lento la lista más reciente de las nuevas características, correcciones o problemas conocidos principales '
ms.openlocfilehash: 1af6025eea51fcf6d231796b453eca1aac0f9cf3
ms.sourcegitcommit: 4fd6ebb878e4a30e416064d9c434c66dfc48fd47
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 08/11/2020
ms.locfileid: "46634856"
---
# <a name="release-notes-for-office-current-channel-preview"></a><span data-ttu-id="a993e-103">Notas de la versión del canal actual de Office (versión preliminar)</span><span class="sxs-lookup"><span data-stu-id="a993e-103">Release Notes for Office Current Channel (Preview)</span></span>

<span data-ttu-id="a993e-104">En este artículo hay notas de la versión para las compilaciones del canal actual (versión preliminar) de las versiones de escritorio de Word, Excel, PowerPoint, Outlook, Access y Project para Windows.</span><span class="sxs-lookup"><span data-stu-id="a993e-104">This article contains release notes for Current Channel (Preview) builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="a993e-105">Todas las semanas se incluyen las nuevas características, correcciones importantes y los problemas principales de mayor interés para usted.</span><span class="sxs-lookup"><span data-stu-id="a993e-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="a993e-106">Tenga en cuenta que a menudo publicamos características (y a veces incluso correcciones) para el Canal actual (versión preliminar) durante un período de tiempo.</span><span class="sxs-lookup"><span data-stu-id="a993e-106">Note that we often roll out features (and sometimes even fixes) to Current Channel (Preview) over a period of time.</span></span> <span data-ttu-id="a993e-107">Esto nos permite asegurarnos de que todo funciona correctamente antes de publicar la característica para un público más amplio.</span><span class="sxs-lookup"><span data-stu-id="a993e-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="a993e-108">Por tanto, si a continuación no ve algo descrito, no se preocupe, lo recibirá con el tiempo.</span><span class="sxs-lookup"><span data-stu-id="a993e-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="a993e-109">Estamos realizando algunos cambios en los canales de actualización de las Aplicaciones de Microsoft 365, incluida la adición de un nuevo canal de actualización (canal empresarial mensual) y el cambio de los nombres de los canales de actualización existentes.</span><span class="sxs-lookup"><span data-stu-id="a993e-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="a993e-110">[Lea este artículo](https://go.microsoft.com/fwlink/p/?linkid=2127441) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="a993e-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="a993e-111">La fecha de publicación de las notas de versión pueden no coincidir con la fecha real de lanzamiento de la compilación.</span><span class="sxs-lookup"><span data-stu-id="a993e-111">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (NO ELIMINAR)

## <a name="version-2008-august-11"></a><span data-ttu-id="a993e-113">Versión 2008: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="a993e-113">Version 2008: August 11</span></span>
<span data-ttu-id="a993e-114">*Versión 2008 (Compilación 13127.20164)*</span><span class="sxs-lookup"><span data-stu-id="a993e-114">*Version 2008 (Build 13127.20164)*</span></span>

<span data-ttu-id="a993e-115">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a993e-115">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-117">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-117">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a993e-118">Acceso</span><span class="sxs-lookup"><span data-stu-id="a993e-118">Access</span></span>

- <span data-ttu-id="a993e-119">Esta corrección resuelve un problema por el que al intentar ejecutar determinadas consultas anteriormente se generaba el mensaje de error "La consulta es demasiado compleja".</span><span class="sxs-lookup"><span data-stu-id="a993e-119">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="a993e-120">Si tiene Office 365 instalado, ya no necesita instalar el nuestro motor de Componente redistribuíble de ACE para exponer ACE fuera del ecosistema de Office.</span><span class="sxs-lookup"><span data-stu-id="a993e-120">If you have Office 365 installed, you no longer need to install our ACE Redistributable Engine to expose ACE outside of the Office ecosystem.</span></span> <span data-ttu-id="a993e-121">Por ello, los usuarios con Office 365 ya no necesitarán el motor de Componente redistribuíble de ACE por lo que no debería experimentar este problema.</span><span class="sxs-lookup"><span data-stu-id="a993e-121">Therefore, for those with Office 365, you will no longer need the ACE Redist Engine, and consequently you should not experience this issue.</span></span>

- <span data-ttu-id="a993e-122">Este problema se ha resuelto: ahora puede usar el controlador ODBC fuera de las aplicaciones de Hacer clic y ejecutar de Office.</span><span class="sxs-lookup"><span data-stu-id="a993e-122">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="a993e-123">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-123">Excel</span></span>

- <span data-ttu-id="a993e-124">Se ha corregido un problema por el que si se cambia el orden de una serie de gráficos, la casilla de verificación correspondiente alineada con la serie no se reordenaba junto con la serie.</span><span class="sxs-lookup"><span data-stu-id="a993e-124">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>

- <span data-ttu-id="a993e-125">Se puede producir un error al intentar guardar un archivo que contiene una fórmula con la función LET().</span><span class="sxs-lookup"><span data-stu-id="a993e-125">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="a993e-126">Se corrigió un problema por el que los gráficos no siempre se actualizaban como se esperaba al habilitar "ForceFullCalculation" a través de VBA en el libro.</span><span class="sxs-lookup"><span data-stu-id="a993e-126">We fixed an issue where charts were not always updated as expected when "ForceFullCalculation" was enabled via VBA for the workbook.</span></span>

- <span data-ttu-id="a993e-127">Se corrigió un problema por el que una copia de una imagen con un relleno degradado radial no coincidía con el original.</span><span class="sxs-lookup"><span data-stu-id="a993e-127">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="onenote"></a><span data-ttu-id="a993e-128">OneNote</span><span class="sxs-lookup"><span data-stu-id="a993e-128">OneNote</span></span>

- <span data-ttu-id="a993e-129">Se ha corregido un problema que provocaba que el texto de marcador de posición en el cuadro de edición de búsqueda se desbordase si se reducía el tamaño de la ventana de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="a993e-129">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="outlook"></a><span data-ttu-id="a993e-130">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-130">Outlook</span></span>

- <span data-ttu-id="a993e-131">Se corrigió un problema en la creación de varios perfiles en Outlook desde el mismo dominio de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="a993e-131">We fixed an issue around creating multiple profiles in Outlookfrom the same email domain.</span></span>

- <span data-ttu-id="a993e-132">Se corrigió un problema que impedía a algunos usuarios de la característica Mejoras del calendario compartido ver un calendario compartido recién agregado.</span><span class="sxs-lookup"><span data-stu-id="a993e-132">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="a993e-133">Se corrigió un problema por el que el icono de bloqueo no se mostraba en el encabezado de los mensajes cifrados S/MIME.</span><span class="sxs-lookup"><span data-stu-id="a993e-133">Addressed an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>

- <span data-ttu-id="a993e-134">Se corrigió un problema por el que la opción Permitir reenvío no aparecía en las Opciones de respuesta de las reuniones del calendario compartido en aquellos casos en los que la carpeta de descarga compartida NO se había comprobado.</span><span class="sxs-lookup"><span data-stu-id="a993e-134">We fixed an issue where the "Allow Forwarding" option was missing from the shared calendar meeting "Response Options" if Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="a993e-135">Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.</span><span class="sxs-lookup"><span data-stu-id="a993e-135">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="a993e-136">Se corrigió un problema por el que el botón Imprimir aparecía en un estado deshabilitado aunque el usuario tuviera los permisos de impresión adecuados.</span><span class="sxs-lookup"><span data-stu-id="a993e-136">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

- <span data-ttu-id="a993e-137">Se corrigió un problema por el que los datos adjuntos se quitaban de mensajes S/MIME al enviarse sin cifrar.</span><span class="sxs-lookup"><span data-stu-id="a993e-137">Addressed an issue that caused attachments to get stripped from S/MIME messages when sending as unencrypted.</span></span>

- <span data-ttu-id="a993e-138">Se corrigió un problema por el que los mensajes de texto sin formato S/MIME se volvían ilegibles al enviarse.</span><span class="sxs-lookup"><span data-stu-id="a993e-138">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>

- <span data-ttu-id="a993e-139">Se corrigió un problema por el que los datos adjuntos se dañaban al enviar un correo electrónico S/MIME sin cifrar.</span><span class="sxs-lookup"><span data-stu-id="a993e-139">Addressed an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>

- <span data-ttu-id="a993e-140">Se corrigió un problema por el que los destinatarios no podían guardar los mensajes con derechos protegidos incluso cuando el remitente otorgaba el permiso de Guardar como.</span><span class="sxs-lookup"><span data-stu-id="a993e-140">Addressed an issue that cause recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>

- <span data-ttu-id="a993e-141">Esta corrección aborda un problema que hacía que los usuarios no pudieran agregar una firma al responder a un mensaje administrado con derechos digitales desde una ventana de inspección cuando el usuario no tenía permisos de propietario sobre el mensaje al que se respondía.</span><span class="sxs-lookup"><span data-stu-id="a993e-141">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>

- <span data-ttu-id="a993e-142">La corrección aborda un problema que provocaba que Outlook no mostrara correctamente los saltos de línea en el contenido de Markdown.</span><span class="sxs-lookup"><span data-stu-id="a993e-142">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

- <span data-ttu-id="a993e-143">Se corrigió un problema por el que las etiquetas de algunas opciones de Búsqueda avanzada se truncaban en algunos idiomas.</span><span class="sxs-lookup"><span data-stu-id="a993e-143">Addressed an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a993e-144">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a993e-144">PowerPoint</span></span>

- <span data-ttu-id="a993e-145">Se ha corregido un problema por el que una copia de una imagen con un relleno degradado radial no coincidía con el original.</span><span class="sxs-lookup"><span data-stu-id="a993e-145">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="a993e-146">Se corrigió un problema por el que el botón Formularios de PowerPoint no permitía la creación de formularios cuando no se permitía el acceso a la Tienda Office.</span><span class="sxs-lookup"><span data-stu-id="a993e-146">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="a993e-147">Project</span><span class="sxs-lookup"><span data-stu-id="a993e-147">Project</span></span>

- <span data-ttu-id="a993e-148">Se corrigió un problema por el que las tareas que aparecen en la vista Panel de tareas no estaban sincronizadas con las del cuadro de diálogo Asignar recursos.</span><span class="sxs-lookup"><span data-stu-id="a993e-148">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>

- <span data-ttu-id="a993e-149">Se corrigió un problema que impedía al usuario guardar desde Project un PDF o XPS en una biblioteca de documentos de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="a993e-149">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

- <span data-ttu-id="a993e-150">Se corrigió un problema por el que si se copiaba y pegaba una tarea con varias dependencias, no se copiaban todas las dependencias correctamente.</span><span class="sxs-lookup"><span data-stu-id="a993e-150">We fixed an issue where if you copied & pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

- <span data-ttu-id="a993e-151">Se corrigió un problema por el que en una lista de tareas de SharePoint, los botones de la cinta de opciones en la segunda pestaña se podían deshabilitar.</span><span class="sxs-lookup"><span data-stu-id="a993e-151">Fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="skype"></a><span data-ttu-id="a993e-152">Skype</span><span class="sxs-lookup"><span data-stu-id="a993e-152">Skype</span></span>

- <span data-ttu-id="a993e-153">Se cambió el tono de piel del emoticono de baile a un color neutro</span><span class="sxs-lookup"><span data-stu-id="a993e-153">Changed dancing emoticon skin tone to neutral color</span></span>

### <a name="visio"></a><span data-ttu-id="a993e-154">Visio</span><span class="sxs-lookup"><span data-stu-id="a993e-154">Visio</span></span>

- <span data-ttu-id="a993e-155">Después de esta corrección, si el usuario detiene la ejecución del comando Delete con algún mecanismo intermedio (en este caso, con un complemento) la memoria no se verá afectada, y no afectará a todo el equipo.</span><span class="sxs-lookup"><span data-stu-id="a993e-155">After this fix, if the user halted the execution of delete command by any mechanism in between (in this case it was through add-in) the memory won't leak and the whole machine won't be impacted.</span></span>

### <a name="word"></a><span data-ttu-id="a993e-156">Word</span><span class="sxs-lookup"><span data-stu-id="a993e-156">Word</span></span>

- <span data-ttu-id="a993e-157">Se ha corregido un problema que provocaba que Word dejara de responder después de pegar texto y una imagen en un cuadro de comentarios.</span><span class="sxs-lookup"><span data-stu-id="a993e-157">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>

- <span data-ttu-id="a993e-158">Se corrigió un problema por el que una copia de una imagen con un relleno degradado radial no coincidía con el original.</span><span class="sxs-lookup"><span data-stu-id="a993e-158">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="a993e-159">Se ha corregido un problema que provocaba que el texto de marcador de posición en el cuadro de edición de búsqueda se desbordase si se reducía el tamaño de la ventana de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="a993e-159">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

- <span data-ttu-id="a993e-160">Se corrigió un problema por el que si se agregaba un comentario para realizar el seguimiento de un cambio, el panel de revisiones se abría de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="a993e-160">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>

- <span data-ttu-id="a993e-161">Se corrigió un problema por el que el comando Editor se deshabilitaba cuando el foco estaba en un cuadro de texto de comentario.</span><span class="sxs-lookup"><span data-stu-id="a993e-161">We fixed an issue where the Editor command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="a993e-162">Se corrigió un problema por el que el comando Mostrar marcas se deshabilitaba cuando el foco estaba en un cuadro de texto de comentario.</span><span class="sxs-lookup"><span data-stu-id="a993e-162">We fixed an issue where the Show Markup command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="a993e-163">Se corrigió un problema por el que el botón Nuevo comentario quedaba deshabilitado después de eliminar el último comentario.</span><span class="sxs-lookup"><span data-stu-id="a993e-163">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

- <span data-ttu-id="a993e-164">Se corrigió un problema por el que se deshabilitaba la opción Personas específicas de Control de cambios.</span><span class="sxs-lookup"><span data-stu-id="a993e-164">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>

- <span data-ttu-id="a993e-165">Se corrigió un problema por el que los vínculos a los documentos no se insertaban en el cuadro de comentarios a través de la lista desplegable Insertar > Vínculo.</span><span class="sxs-lookup"><span data-stu-id="a993e-165">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>

- <span data-ttu-id="a993e-166">Se corrigió un bloqueo ocasional al abrir archivos HTML.</span><span class="sxs-lookup"><span data-stu-id="a993e-166">We fixed an occasional hang while opening HTML files.</span></span>

- <span data-ttu-id="a993e-167">Se corrigió un problema en un archivo XML personalizado en el que se podía perder el estado de los comentarios al abrir el documento.</span><span class="sxs-lookup"><span data-stu-id="a993e-167">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

- <span data-ttu-id="a993e-168">Se ha corregido un problema por el que el recuento de hipervínculos en la colección de hipervínculos de VBA no realizaba correctamente la iteración después de agregar una imagen que contenía un hipervínculo.</span><span class="sxs-lookup"><span data-stu-id="a993e-168">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

- <span data-ttu-id="a993e-169">Para un antiguo panel de uso compartido basado en servicio no Web, al cerrar el documento mientras el panel de uso compartido está abierto, se podría producir un bloqueo.</span><span class="sxs-lookup"><span data-stu-id="a993e-169">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="a993e-170">Este problema ya está solucionado.</span><span class="sxs-lookup"><span data-stu-id="a993e-170">This is now fixed.</span></span>

- <span data-ttu-id="a993e-171">Se corrigió un problema en el que, después de abrir el usuario una nueva ventana de la aplicación desde la barra de tareas y crear un nuevo documento en blanco, se creaban archivos adicionales.</span><span class="sxs-lookup"><span data-stu-id="a993e-171">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>

- <span data-ttu-id="a993e-172">Se corrigió un problema por el que, si un usuario estaba editando un documento pero había perdido los permisos, no se informaba al usuario de que tenía que volver a autenticarse.</span><span class="sxs-lookup"><span data-stu-id="a993e-172">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2007-august-05"></a><span data-ttu-id="a993e-174">Versión 2007: 05 de agosto</span><span class="sxs-lookup"><span data-stu-id="a993e-174">Version 2007: August 05</span></span>
<span data-ttu-id="a993e-175">*Versión 2007 (compilación 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="a993e-175">*Version 2007 (Build 13029.20344)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)



[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-179">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-179">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a993e-180">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-180">Outlook</span></span>

- <span data-ttu-id="a993e-181">Se corrigió un problema que provocaba que Outlook no pudiese recuperar sugerencias de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="a993e-181">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="a993e-182">Se corrigió un problema que provocaba que los usuarios se bloquearan en ocasiones al recuperar información personal.</span><span class="sxs-lookup"><span data-stu-id="a993e-182">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="a993e-183">Project</span><span class="sxs-lookup"><span data-stu-id="a993e-183">Project</span></span>

- <span data-ttu-id="a993e-184">Se corrigió un problema por el que no se podía abrir un proyecto que estaba en mal estado.</span><span class="sxs-lookup"><span data-stu-id="a993e-184">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2007-july-29"></a><span data-ttu-id="a993e-186">Versión 2007: 29 de julio</span><span class="sxs-lookup"><span data-stu-id="a993e-186">Version 2007: July 29</span></span>
<span data-ttu-id="a993e-187">*Versión 2007 (compilación 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="a993e-187">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="a993e-189">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-189">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a993e-190">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-190">Excel</span></span>

- <span data-ttu-id="a993e-191">**Obtenga datos de organización de Power BI mediante Tipos de datos:** los tipos de datos de Excel de Power BI se están publicando ahora para participantes de Office Insider en las organizaciones con Office 365 E5/A5 o Microsoft 365 E5/A5.</span><span class="sxs-lookup"><span data-stu-id="a993e-191">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="a993e-192">Obtener la información que necesita y actualizarla fácilmente es fundamental para muchos de los flujos de trabajo diarios.</span><span class="sxs-lookup"><span data-stu-id="a993e-192">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="a993e-193">Le proporcionamos acceso a la información de Power BI de su empresa u organización como un tipo de datos en Excel, lo que amplía su capacidad de incorporar a las hojas de cálculo información vinculada.</span><span class="sxs-lookup"><span data-stu-id="a993e-193">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="a993e-194">Más información</span><span class="sxs-lookup"><span data-stu-id="a993e-194">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="a993e-195">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="a993e-195">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="a993e-196">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-196">Outlook</span></span>

- <span data-ttu-id="a993e-197">**Elija dónde buscar:** La nueva lista desplegable del ámbito de búsqueda le permite modificar de manera más sencilla su búsqueda y cambiar entre la carpeta actual y el buzón actual.</span><span class="sxs-lookup"><span data-stu-id="a993e-197">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="a993e-198">Gracias a todos los usuarios de Próximamente, quienes brindaron comentarios acerca de la nueva experiencia de búsqueda Search at Top.</span><span class="sxs-lookup"><span data-stu-id="a993e-198">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="a993e-199">¡Este diseño y actualización son el resultado de sus comentarios!</span><span class="sxs-lookup"><span data-stu-id="a993e-199">This design and update came out of that feedback!</span></span>

### <a name="word"></a><span data-ttu-id="a993e-200">Word</span><span class="sxs-lookup"><span data-stu-id="a993e-200">Word</span></span>

- <span data-ttu-id="a993e-201">**Mejor colaboración con comentarios modernos:** Agregue comentarios a objetos, @mencione compañeros y resuelva hilos de comentarios para disfrutar de una mejor experiencia de colaboración.</span><span class="sxs-lookup"><span data-stu-id="a993e-201">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="a993e-202">Más información</span><span class="sxs-lookup"><span data-stu-id="a993e-202">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-205">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-205">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a993e-206">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-206">Outlook</span></span>

- <span data-ttu-id="a993e-207">Se ha corregido un problema que provocaba que los usuarios de CLP experimenten un bloqueo al cambiar la dirección del remitente en una respuesta desde un contexto protegido a uno no protegido.</span><span class="sxs-lookup"><span data-stu-id="a993e-207">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="a993e-208">Se ha corregido un problema que provocaba que la página del Asistente para programación no se mostrara.</span><span class="sxs-lookup"><span data-stu-id="a993e-208">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="a993e-209">Se ha abordado un problema que causaba problemas de formato en las alertas de notificación de incidentes.</span><span class="sxs-lookup"><span data-stu-id="a993e-209">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2007-july-27"></a><span data-ttu-id="a993e-211">Versión 2007: 27 de julio</span><span class="sxs-lookup"><span data-stu-id="a993e-211">Version 2007: July 27</span></span>
<span data-ttu-id="a993e-212">*Versión 2007 (compilación 13029.20292)*</span><span class="sxs-lookup"><span data-stu-id="a993e-212">*Version 2007 (Build 13029.20292)*</span></span>
* <span data-ttu-id="a993e-213">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="a993e-213">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-20"></a><span data-ttu-id="a993e-214">Versión 2007: 20 de julio</span><span class="sxs-lookup"><span data-stu-id="a993e-214">Version 2007: July 20</span></span>
<span data-ttu-id="a993e-215">*Versión 2007 (compilación 13029.20236)*</span><span class="sxs-lookup"><span data-stu-id="a993e-215">*Version 2007 (Build 13029.20236)*</span></span>
* <span data-ttu-id="a993e-216">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="a993e-216">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-15"></a><span data-ttu-id="a993e-217">Versión 2007: 15 de julio</span><span class="sxs-lookup"><span data-stu-id="a993e-217">Version 2007: July 15</span></span>
<span data-ttu-id="a993e-218">*Versión 2007 (compilación 13029.20200)*</span><span class="sxs-lookup"><span data-stu-id="a993e-218">*Version 2007 (Build 13029.20200)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="a993e-220">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-220">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a993e-221">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-221">Excel</span></span>

- <span data-ttu-id="a993e-222">**Cree diagramas de Visio elegantes en Excel:** cree un diagrama de flujo o un organigrama con solo escribir datos en una hoja de cálculo.</span><span class="sxs-lookup"><span data-stu-id="a993e-222">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="a993e-223">Más información</span><span class="sxs-lookup"><span data-stu-id="a993e-223">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-226">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-226">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a993e-227">Acceso</span><span class="sxs-lookup"><span data-stu-id="a993e-227">Access</span></span>

- <span data-ttu-id="a993e-228">Se ha corregido un problema por el que el administrador de tablas vinculadas solicitaba una clave principal al actualizar una tabla SQL vinculada.</span><span class="sxs-lookup"><span data-stu-id="a993e-228">We fixed an issue where the linked table manager would prompt a primary key if a linked SQL table was refreshed.</span></span>

- <span data-ttu-id="a993e-229">Se ha corregido un problema por el que las consultas en el Editor de consultas quedaban desplazadas fuera de la vista.</span><span class="sxs-lookup"><span data-stu-id="a993e-229">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>

- <span data-ttu-id="a993e-230">Se ha corregido un problema que provocaba que la ejecución de consultas tardara en completarse aproximadamente el doble del tiempo esperado.</span><span class="sxs-lookup"><span data-stu-id="a993e-230">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="a993e-231">Se ha corregido un problema que provocaba que Microsoft Access no identificara una Columna de identidad en una tabla vinculada de SQL Server, lo que podía hacer que las filas aparecieran como eliminadas de forma incorrecta.</span><span class="sxs-lookup"><span data-stu-id="a993e-231">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="a993e-232">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-232">Excel</span></span>

- <span data-ttu-id="a993e-233">Se ha corregido un problema por el que las direcciones URL que no se basaban en http o https no se mostraban en la lista Utilizado recientemente.</span><span class="sxs-lookup"><span data-stu-id="a993e-233">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

- <span data-ttu-id="a993e-234">Se ha corregido un problema por el que podía producirse un error o bloqueo al cargar un libro con varias hojas en la vista previa de salto de página.</span><span class="sxs-lookup"><span data-stu-id="a993e-234">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="a993e-235">Se ha corregido un problema por el que las tablas del modelo de datos creadas en algunas versiones de Excel no se podían ver en "Vista previa de la tabla", pese a que no se había editado la consulta asociada a la tabla.</span><span class="sxs-lookup"><span data-stu-id="a993e-235">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>

- <span data-ttu-id="a993e-236">La opción "Omitir tipo de referencia (relativa o absoluta)" en el cuadro de diálogo "Definir nombre/Aplicar nombres" provocaba que las fórmulas no funcionaran.</span><span class="sxs-lookup"><span data-stu-id="a993e-236">Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>

- <span data-ttu-id="a993e-237">Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta personalizada al guardar un libro de trabajo en SharePoint o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="a993e-237">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="a993e-238">Se ha corregido un problema que provocaba que los libros de trabajo fueran de solo lectura cuando el archivo tenía activada la casilla "Se recomienda solo lectura".</span><span class="sxs-lookup"><span data-stu-id="a993e-238">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

- <span data-ttu-id="a993e-239">Se ha corregido un problema por el que podía producirse un error o bloqueo al cargar un libro con varias hojas en la vista previa de salto de página.</span><span class="sxs-lookup"><span data-stu-id="a993e-239">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="a993e-240">Se ha corregido un problema por el que no se podía aplicar el formato correcto a las líneas de cuadrícula principales de los gráficos radiales.</span><span class="sxs-lookup"><span data-stu-id="a993e-240">We fixed an issue where the major gridlines of radar charts could not be formatted correctly.</span></span>


- <span data-ttu-id="a993e-241">Se ha corregido un problema por el que al quitar filtros avanzados de datos se borraba el formato de tabla.</span><span class="sxs-lookup"><span data-stu-id="a993e-241">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>


- <span data-ttu-id="a993e-242">Se ha corregido un problema que provocaba que la ruta de acceso completa de un documento PDF incrustado se mostrara en el título del documento, en lugar de mostrarse solo en el nombre de archivo.</span><span class="sxs-lookup"><span data-stu-id="a993e-242">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>


- <span data-ttu-id="a993e-243">Se ha corregido un problema por el que deshabilitar el CloudConnector de Wolfram y, a continuación, guardar y volver a abrir un libro de Excel podía dar lugar a un bloqueo.</span><span class="sxs-lookup"><span data-stu-id="a993e-243">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>


- <span data-ttu-id="a993e-244">Se ha corregido un problema por el que iniciar Excel con el complemento Solver habilitado daba lugar a un bloqueo.</span><span class="sxs-lookup"><span data-stu-id="a993e-244">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>


### <a name="outlook"></a><span data-ttu-id="a993e-245">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-245">Outlook</span></span>

- <span data-ttu-id="a993e-246">Se ha corregido un problema por el que Outlook se bloqueaba si había más de 130 destinatarios en la línea "Para". Asimismo, se ha mejorado el rendimiento del procesamiento de texto.</span><span class="sxs-lookup"><span data-stu-id="a993e-246">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>


- <span data-ttu-id="a993e-247">Se ha corregido un problema por el que la ventana del Editor de métodos de entrada (IME) se superponía al texto subyacente escrito mediante el IME al utilizar varios monitores con resoluciones diferentes.</span><span class="sxs-lookup"><span data-stu-id="a993e-247">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>


- <span data-ttu-id="a993e-248">Se ha corregido un problema en la barra "Tareas Pendientes" que provocaba que los eventos que ocupaban más de dos días mostraran la misma hora de finalización para los siguientes días.</span><span class="sxs-lookup"><span data-stu-id="a993e-248">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>


- <span data-ttu-id="a993e-249">Se ha corregido un problema que causaba que la fecha de creación de datos adjuntos copiados en el sistema de archivos a través de la opción de arrastrar y soltar apareciera como el 1 de enero de 4501.</span><span class="sxs-lookup"><span data-stu-id="a993e-249">Addresses an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="a993e-250">Se ha corregido un problema por el que los usuarios no podían "Enviar como" o "Enviar en nombre de" en una lista de distribución.</span><span class="sxs-lookup"><span data-stu-id="a993e-250">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>


- <span data-ttu-id="a993e-251">Se ha corregido un problema que causaba que los delegados reciban un error al editar una cita de calendario existente en el calendario de un administrador.</span><span class="sxs-lookup"><span data-stu-id="a993e-251">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="a993e-252">Se ha corregido un problema que provocaba que los usuarios vieran el siguiente error al cerrar una cita guardada previamente: "No se puede guardar el elemento, porque lo cambió otro usuario o se modificó en otra ventana.</span><span class="sxs-lookup"><span data-stu-id="a993e-252">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="a993e-253">¿Desea copiarlo en la carpeta predeterminada del elemento?</span><span class="sxs-lookup"><span data-stu-id="a993e-253">Do you want to make a copy in the default folder for the item?"</span></span>


- <span data-ttu-id="a993e-254">Se ha corregido un problema que causaba que faltara la opción "Permitir reenvío" en las "Opciones de respuesta" de la reunión de calendario compartida cuando NO está marcado Descargar carpeta compartida.</span><span class="sxs-lookup"><span data-stu-id="a993e-254">Addresses an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="a993e-255">Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.</span><span class="sxs-lookup"><span data-stu-id="a993e-255">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="a993e-256">Se ha corregido un problema que provocaba que la lista de mensajes dejara de actualizarse durante varios minutos después de que los usuarios de Outlook usaran calendarios compartidos.</span><span class="sxs-lookup"><span data-stu-id="a993e-256">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>


- <span data-ttu-id="a993e-257">Se ha corregido un problema que impedía que los avisos del calendario mostraran la hora exacta de las reuniones programadas que iban a tener lugar en menos de una semana.</span><span class="sxs-lookup"><span data-stu-id="a993e-257">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span> 


- <span data-ttu-id="a993e-258">Se ha corregido un problema por el que, al insertar una imagen en un mensaje y, a continuación, guardar el mensaje como borrador, se cambiaba el tamaño de la imagen.</span><span class="sxs-lookup"><span data-stu-id="a993e-258">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>


- <span data-ttu-id="a993e-259">Se ha corregido un problema que provocaba que el cuerpo de un mensaje NDR cambiara de Unicode a ASCII después de editar el asunto.</span><span class="sxs-lookup"><span data-stu-id="a993e-259">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>


- <span data-ttu-id="a993e-260">Se ha corregido un problema por el que las fechas del minicalendario no se podían mostrar en negrita para los usuarios de Japón.</span><span class="sxs-lookup"><span data-stu-id="a993e-260">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="a993e-261">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a993e-261">PowerPoint</span></span>

- <span data-ttu-id="a993e-262">Se ha corregido un problema por el que el indicador de color de presencia de un usuario no se actualizaba en la galería de coautoría durante una sesión de coautoría en directo.</span><span class="sxs-lookup"><span data-stu-id="a993e-262">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>


- <span data-ttu-id="a993e-263">Se ha corregido un problema por el que, al tratar de pegar código HTML en un área de texto en una diapositiva, el código se pegaba en un cuadro de texto creado en la parte superior de la diapositiva.</span><span class="sxs-lookup"><span data-stu-id="a993e-263">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>


- <span data-ttu-id="a993e-264">Se ha corregido un problema por el que, al seleccionar todas las diapositivas en la vista Moderador y, a continuación, salir de dicha vista mediante ALT+TAB, volver a la presentación con diapositivas y hacer clic en "Finalizar presentación", tenía lugar una excepción no controlada.</span><span class="sxs-lookup"><span data-stu-id="a993e-264">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>


### <a name="project"></a><span data-ttu-id="a993e-265">Project</span><span class="sxs-lookup"><span data-stu-id="a993e-265">Project</span></span>

- <span data-ttu-id="a993e-266">Se ha corregido un problema que impedía guardar desde Project un PDF o XPS en una biblioteca de documentos de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="a993e-266">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="a993e-267">Se ha corregido un problema por el que los proyectos no se podían abrir en el cliente de escritorio de Project desde Project Web App si la dirección URL terminaba en .com.</span><span class="sxs-lookup"><span data-stu-id="a993e-267">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="a993e-268">Se ha corregido un problema que provocaba que Project se bloqueara al abrir determinados archivos XML.</span><span class="sxs-lookup"><span data-stu-id="a993e-268">We fixed an issue where Project may crash when opening certain XML files.</span></span>


- <span data-ttu-id="a993e-269">Se ha corregido un problema por el que los proyectos no se podían abrir en el cliente de escritorio de Project en Project Web App si la dirección URL finalizaba en ".com".</span><span class="sxs-lookup"><span data-stu-id="a993e-269">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>


- <span data-ttu-id="a993e-270">Se ha corregido un problema por el que si pegaba una tarea que tenía varias dependencias, no todas las dependencias se copiaban correctamente.</span><span class="sxs-lookup"><span data-stu-id="a993e-270">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="a993e-271">Se ha corregido un problema por el que la tarea seleccionada en el cuadro de diálogo de asignación de recursos no era la misma que la tarea seleccionada en la vista del panel de tareas.</span><span class="sxs-lookup"><span data-stu-id="a993e-271">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="a993e-272">Se ha corregido un problema que provocaba que el evento ProjectBeforeTaskChange no se activara al tener lugar un cambio en la tarea de resumen del proyecto, ya fuera en el campo de inicio o de tarea del proyecto.</span><span class="sxs-lookup"><span data-stu-id="a993e-272">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>


- <span data-ttu-id="a993e-273">Se ha corregido un problema por el que, si las tareas de duración fija estaban completas al 100 %, pero no se especificaba la fecha de finalización real, el porcentaje de finalización de la tarea se mostraba como inferior al 100 %.</span><span class="sxs-lookup"><span data-stu-id="a993e-273">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

- <span data-ttu-id="a993e-274">Se ha corregido un problema por el que una actualización o un restablecimiento de la línea base podía cambiar los recursos de trabajo o el costo presupuestado con fases temporales, y la línea base podía reflejar valores de presupuesto incorrectos.</span><span class="sxs-lookup"><span data-stu-id="a993e-274">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>


- <span data-ttu-id="a993e-275">Se ha corregido un problema que consistía en que los vínculos de Project Planner en entornos de Government Community Cloud habían sido deshabilitados.</span><span class="sxs-lookup"><span data-stu-id="a993e-275">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>


- <span data-ttu-id="a993e-276">Se ha corregido un problema por el que no se podía abrir un archivo de Project de una biblioteca de documentos de SharePoint si la biblioteca estaba en modo moderno.</span><span class="sxs-lookup"><span data-stu-id="a993e-276">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>


### <a name="word"></a><span data-ttu-id="a993e-277">Word</span><span class="sxs-lookup"><span data-stu-id="a993e-277">Word</span></span>

- <span data-ttu-id="a993e-278">Se ha corregido un problema por el que no funcionaba la opción de borrar el formato en el Panel Comentarios mediante el botón Borrar formato de la cinta de opciones de Office.</span><span class="sxs-lookup"><span data-stu-id="a993e-278">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>


- <span data-ttu-id="a993e-279">Se ha corregido un problema por el que el texto insertado en un archivo de gráficos vectoriales escalables (SVG) quedaba ilegible tras insertarlo en un archivo de Word, Excel o PowerPoint, guardar y cerrar el archivo y, a continuación, volver a abrirlo.</span><span class="sxs-lookup"><span data-stu-id="a993e-279">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>


- <span data-ttu-id="a993e-280">Se ha corregido un problema que provocaba que otras aplicaciones que se ejecutaban en segundo plano comenzaran a parpadear al cambiar el tamaño de una tabla cuando la regla no se mostraba.</span><span class="sxs-lookup"><span data-stu-id="a993e-280">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>


- <span data-ttu-id="a993e-281">Se ha corregido un problema por el que, en el modo de coautoría, las respuestas a los comentarios no se mostraban en el panel de comentarios en ocasiones, pero eran visibles en el panel de revisiones.</span><span class="sxs-lookup"><span data-stu-id="a993e-281">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>


- <span data-ttu-id="a993e-282">Se ha corregido un problema en el modo de coautoría: cuando se produce un conflicto de fusión y el usuario ya ha elegido previamente descartar los cambios, ya no se muestra la opción que da a elegir entre guardar o descartar los cambios.</span><span class="sxs-lookup"><span data-stu-id="a993e-282">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>


- <span data-ttu-id="a993e-283">Se ha corregido un problema por el que el color de los hipervínculos HTML no se representaba correctamente.</span><span class="sxs-lookup"><span data-stu-id="a993e-283">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>


- <span data-ttu-id="a993e-284">Se ha corregido un problema por el que, si Word tenía una lista de más de 50 documentos abiertos con frecuencia, después de guardar y abrir un documento, se mostraba un historial de revisiones pese a que no se había modificado dicho documento.</span><span class="sxs-lookup"><span data-stu-id="a993e-284">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>


- <span data-ttu-id="a993e-285">Se ha corregido el problema con la opción de autoguardado durante la coautoría.</span><span class="sxs-lookup"><span data-stu-id="a993e-285">We fixed in issue with autosave during coauthoring.</span></span>


- <span data-ttu-id="a993e-286">Se ha corregido un problema por el que, al intentar guardar un archivo que contenía una macro con un nombre nuevo, este se guardaba con la extensión .docx y el nombre de archivo "WRO0004.docx", independientemente de lo que el usuario escribiera, lo que provocaba que el archivo no se pudiera volver a usar.</span><span class="sxs-lookup"><span data-stu-id="a993e-286">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a993e-287">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="a993e-287">Office Suite</span></span>

- <span data-ttu-id="a993e-288">Un problema de temporización podía provocar un bloqueo al cerrar archivos de Office.</span><span class="sxs-lookup"><span data-stu-id="a993e-288">A timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="a993e-289">La corrección para este problema era asegurarse de que el servicio computase correctamente los productos agregados.</span><span class="sxs-lookup"><span data-stu-id="a993e-289">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="a993e-290">Se han filtrado los nuevos productos agregados (lo que garantiza que también se encuentren en la nueva configuración) y se han agregado al final de los ID de versión de producto existentes.</span><span class="sxs-lookup"><span data-stu-id="a993e-290">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2006-july-09"></a><span data-ttu-id="a993e-292">Versión 2006: 09 de julio</span><span class="sxs-lookup"><span data-stu-id="a993e-292">Version 2006: July 09</span></span>
<span data-ttu-id="a993e-293">*Versión 2006 (compilación 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="a993e-293">*Version 2006 (Build 13001.20384)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="a993e-295">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-295">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a993e-296">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-296">Excel</span></span>

- <span data-ttu-id="a993e-297">**Realice una conexión PDF:** Conectar, importar, actualizar los datos de un PDF.</span><span class="sxs-lookup"><span data-stu-id="a993e-297">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="a993e-298">Más información</span><span class="sxs-lookup"><span data-stu-id="a993e-298">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="a993e-299">**Crear variables para usar en fórmulas:** mejorar el rendimiento, la legibilidad y la composición con la función LET.</span><span class="sxs-lookup"><span data-stu-id="a993e-299">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="a993e-300">Esta función le permite crear variables con nombre en fórmulas nuevas o previamente existentes.</span><span class="sxs-lookup"><span data-stu-id="a993e-300">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="a993e-301">Más información</span><span class="sxs-lookup"><span data-stu-id="a993e-301">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="a993e-302">Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span><span class="sxs-lookup"><span data-stu-id="a993e-302">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="a993e-303">**Métodos abreviados de teclado de Excel:** métodos abreviados de teclado actualizados para Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-303">**Keyboard shortcuts in Excel:** Updated keyboard shortcuts for Excel</span></span>

### <a name="outlook"></a><span data-ttu-id="a993e-304">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-304">Outlook</span></span>

- <span data-ttu-id="a993e-305">**Crear sondeos en Outlook con Sondeo rápido:** cree sondeos, recopile votos y vea los resultados rápidamente en un solo correo electrónico [Más información](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="a993e-305">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="a993e-306">\*\* Mantenga la fidelidad de sus imágenes cuando las envíe como parte de un correo electrónico:\*\* una nueva configuración de Outlook está disponible para limitar la compresión de imágenes cuando envía imágenes como parte de contenido del correo electrónico</span><span class="sxs-lookup"><span data-stu-id="a993e-306">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-309">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-309">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a993e-310">Access</span><span class="sxs-lookup"><span data-stu-id="a993e-310">Access</span></span>

- <span data-ttu-id="a993e-311">Este problema se ha resuelto y ahora debería ser capaz de insertar correctamente tablas SQL vinculadas que incluyan un campo de identidad (por ejemplo, autonumeración) en Access.</span><span class="sxs-lookup"><span data-stu-id="a993e-311">This issue is resolved, and you should expect to be able to successfully insert linked SQL tables that include an identity (e.g. autonumber) field into Access.</span></span>

### <a name="excel"></a><span data-ttu-id="a993e-312">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-312">Excel</span></span>

- <span data-ttu-id="a993e-313">Se ha corregido un bloqueo que podría producirse al intentar crear una conexión de datos si había cerrado la sesión de su cuenta.</span><span class="sxs-lookup"><span data-stu-id="a993e-313">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="outlook"></a><span data-ttu-id="a993e-314">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-314">Outlook</span></span>

- <span data-ttu-id="a993e-315">Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.</span><span class="sxs-lookup"><span data-stu-id="a993e-315">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a993e-316">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="a993e-316">Office Suite</span></span>

- <span data-ttu-id="a993e-317">Hemos modificado la versión AppV51 para solucionar una regresión de la AppV51 anterior.</span><span class="sxs-lookup"><span data-stu-id="a993e-317">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="a993e-318">El host de Office se bloqueaba en Windows al activar un complemento cuando el valor del registro TabProcGrowth era del tipo REG_SZ y tenía el valor "0".</span><span class="sxs-lookup"><span data-stu-id="a993e-318">he office host was crashing in windows, when an add-in is being activated while the registry TabProcGrowth value is REG_SZ type and with value "0".</span></span>  <span data-ttu-id="a993e-319">El valor de TabProcGrowth del registro puede encontrarse en una de estas cuatro rutas: HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER \Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE \Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER \Software\Policies\Microsoft\Internet Explorer\Main. Este cambio solucionaría el problema.</span><span class="sxs-lookup"><span data-stu-id="a993e-319">That registry TabProcGrowth value can be under any one of 4 paths: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main This change would fix this issue.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2006-june-25"></a><span data-ttu-id="a993e-321">Versión 2006: 25 de junio</span><span class="sxs-lookup"><span data-stu-id="a993e-321">Version 2006: June 25</span></span>
<span data-ttu-id="a993e-322">*Versión 2006 (compilación 13001.20266)*</span><span class="sxs-lookup"><span data-stu-id="a993e-322">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="a993e-324">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-324">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="a993e-325">Visio</span><span class="sxs-lookup"><span data-stu-id="a993e-325">Visio</span></span>

- <span data-ttu-id="a993e-326">**Cree diagramas de Visio elegantes en Excel:** cree un diagrama de flujo o un organigrama basado en datos en una hoja de cálculo.</span><span class="sxs-lookup"><span data-stu-id="a993e-326">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart based on data in a worksheet.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-329">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-329">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a993e-330">Access</span><span class="sxs-lookup"><span data-stu-id="a993e-330">Access</span></span>

- <span data-ttu-id="a993e-331">Este problema se ha resuelto.</span><span class="sxs-lookup"><span data-stu-id="a993e-331">This problem is now resolved.</span></span> <span data-ttu-id="a993e-332">Informe al equipo si tiene problemas con este proceso.</span><span class="sxs-lookup"><span data-stu-id="a993e-332">Please let the team know if you experience more issues with this process.</span></span>


### <a name="outlook"></a><span data-ttu-id="a993e-333">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-333">Outlook</span></span>

- <span data-ttu-id="a993e-334"><span style="display:inline !important;">Se ha corregido un problema que causaba que<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">la fecha de creación de&nbsp; datos adjuntos copiados en el sistema de archivos a través de la opción de arrastrar y soltar&nbsp; apareciera como el 1 de enero de 4501.</span></span><span class="sxs-lookup"><span data-stu-id="a993e-334"><span style="display:inline !important;">Addresses an issue that caused users to see<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">the creation date of&nbsp; attachments that they copied to their file system via drag and drop getting&nbsp; set to January 1, 4501.</span></span></span><br>


- <span data-ttu-id="a993e-335"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Se ha corregido un problema que provocaba que los usuarios de las mejoras del Calendario compartido vieran errores en el calendario.</span></span><span class="sxs-lookup"><span data-stu-id="a993e-335"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span></span><br>


- <span data-ttu-id="a993e-336"><span style="display:inline !important;">Se ha corregido un problema que provocaba que los usuarios de Outlook vieran continuamente un aviso para que ejecutaran la herramienta de Reparación de la bandeja de entrada.</span></span><span class="sxs-lookup"><span data-stu-id="a993e-336"><span style="display:inline !important;">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span></span><br>


- <span data-ttu-id="a993e-337"><span style="display:inline !important;">Se ha corregido un problema por el que la búsqueda de una característica en Sugerir una característica no devolvía resultados y no ofrecía al usuario ninguna opción para enviar una nueva característica.</span></span><span class="sxs-lookup"><span data-stu-id="a993e-337"><span style="display:inline !important;">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span></span><br>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2006-june-18"></a><span data-ttu-id="a993e-339">Versión 2006: 18 de junio</span><span class="sxs-lookup"><span data-stu-id="a993e-339">Version 2006: June 18</span></span>
<span data-ttu-id="a993e-340">*Versión 2006 (compilación 13001.20198)*</span><span class="sxs-lookup"><span data-stu-id="a993e-340">*Version 2006 (Build 13001.20198)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="a993e-342">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-342">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a993e-343">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-343">Excel</span></span>



- <span data-ttu-id="a993e-344">**Guardar en Carpetas ancladas:** anclar tus carpetas hace que el almacenamiento de archivos de Office sea más fácil. Nuestros usuarios nos dijeron que querían tener más control sobre las carpetas disponibles al guardar un archivo nuevo.</span><span class="sxs-lookup"><span data-stu-id="a993e-344">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="a993e-345">Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar.</span><span class="sxs-lookup"><span data-stu-id="a993e-345">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="a993e-346">Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.</span><span class="sxs-lookup"><span data-stu-id="a993e-346">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="a993e-347">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="a993e-347">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a993e-348">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a993e-348">PowerPoint</span></span>

- <span data-ttu-id="a993e-349">**Guardar en Carpetas ancladas:** anclar tus carpetas hace que el almacenamiento de archivos de Office sea más fácil. Nuestros usuarios nos dijeron que querían tener más control sobre las carpetas disponibles al guardar un archivo nuevo.</span><span class="sxs-lookup"><span data-stu-id="a993e-349">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="a993e-350">Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar.</span><span class="sxs-lookup"><span data-stu-id="a993e-350">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="a993e-351">Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.</span><span class="sxs-lookup"><span data-stu-id="a993e-351">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="a993e-352">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="a993e-352">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="a993e-353">Word</span><span class="sxs-lookup"><span data-stu-id="a993e-353">Word</span></span>

- <span data-ttu-id="a993e-354">**Guardar en Carpetas ancladas:** anclar tus carpetas hace que el almacenamiento de archivos de Office sea más fácil. Nuestros usuarios nos dijeron que querían tener más control sobre las carpetas disponibles al guardar un archivo nuevo.</span><span class="sxs-lookup"><span data-stu-id="a993e-354">**Save to Pinned Folders:** Pin your folders makes saving Office files easierWe received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="a993e-355">Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar.</span><span class="sxs-lookup"><span data-stu-id="a993e-355">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="a993e-356">Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.</span><span class="sxs-lookup"><span data-stu-id="a993e-356">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="a993e-357">Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="a993e-357">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-360">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-360">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a993e-361">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-361">Excel</span></span>

- <span data-ttu-id="a993e-362">Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta al guardar en SharePoint o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="a993e-362">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

### <a name="outlook"></a><span data-ttu-id="a993e-363">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-363">Outlook</span></span>

- <span data-ttu-id="a993e-364">Se ha corregido un problema que provocaba que Ctrl + clic dejara de funcionar cuando se habilitaba la configuración de la nube.</span><span class="sxs-lookup"><span data-stu-id="a993e-364">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>

### <a name="project"></a><span data-ttu-id="a993e-365">Project</span><span class="sxs-lookup"><span data-stu-id="a993e-365">Project</span></span>

- <span data-ttu-id="a993e-366">Se ha corregido un problema por el que una tarea marcada como completada al 100 % se mostraba por error no completada al 100 %.</span><span class="sxs-lookup"><span data-stu-id="a993e-366">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2006-june-11"></a><span data-ttu-id="a993e-368">Versión 2006: 11 de junio</span><span class="sxs-lookup"><span data-stu-id="a993e-368">Version 2006: June 11</span></span>
<span data-ttu-id="a993e-369">*Versión 2006 (compilación 13001.20144)*</span><span class="sxs-lookup"><span data-stu-id="a993e-369">*Version 2006 (Build 13001.20144)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="a993e-371">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-371">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="a993e-372">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a993e-372">PowerPoint</span></span>

- <span data-ttu-id="a993e-373">**Mejor rendimiento de vídeos de Stream en PowerPoint:** hemos realizado mejoras en el rendimiento de la reproducción de los vídeos de Microsoft Stream para reducir el tiempo de carga de vídeo y crear una visualización más suave.</span><span class="sxs-lookup"><span data-stu-id="a993e-373">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="a993e-374">Use los vídeos corporativos de Microsoft Stream para crear presentaciones mejoradas.</span><span class="sxs-lookup"><span data-stu-id="a993e-374">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="word"></a><span data-ttu-id="a993e-375">Word</span><span class="sxs-lookup"><span data-stu-id="a993e-375">Word</span></span>

- <span data-ttu-id="a993e-376">**Retener texto en vectores:** ahora puede conservar el texto en mapas, gráficos y otros vectores de SVG al convertir estos objetos en Excel, Word y PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a993e-376">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-379">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-379">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a993e-380">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-380">Excel</span></span>

- <span data-ttu-id="a993e-381">Se ha corregido un problema por el que Excel se cerraba ocasionalmente al utilizar OneDrive.</span><span class="sxs-lookup"><span data-stu-id="a993e-381">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>

- <span data-ttu-id="a993e-382">Se ha corregido un problema por el que los valores personalizados en el eje del gráfico no se aplicaban correctamente.</span><span class="sxs-lookup"><span data-stu-id="a993e-382">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>

- <span data-ttu-id="a993e-383">Se ha corregido un problema por el que las hojas de cálculo que contienen varias fórmulas con nombres definidos tardaban más en guardarse.</span><span class="sxs-lookup"><span data-stu-id="a993e-383">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="a993e-384">Hemos corregido un problema que provocaba que los nombres de las impresoras se duplicaran en la lista de impresoras disponibles.</span><span class="sxs-lookup"><span data-stu-id="a993e-384">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span>

- <span data-ttu-id="a993e-385">Hemos corregido un problema para que los usuarios tengan un mejor rendimiento al eliminar las columnas combinadas.</span><span class="sxs-lookup"><span data-stu-id="a993e-385">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>

- <span data-ttu-id="a993e-386">Se ha corregido un problema por el que aparecía el mensaje de error "No se puede cerrar el libro debido a que otro libro hace referencia a él" si los complementos se cargaban en orden alfabético en lugar de en un orden especificado por el usuario.</span><span class="sxs-lookup"><span data-stu-id="a993e-386">We fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="a993e-387">Se ha corregido un problema en el que administrar fuentes entre Excel y algunas aplicaciones tecnológicas de asistencia de terceros causaba problemas de memoria.</span><span class="sxs-lookup"><span data-stu-id="a993e-387">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>

- <span data-ttu-id="a993e-388">Se ha corregido un problema por el que al hacer clic en un hipervínculo marcado en el mismo libro hacía que el libro se ocultara.</span><span class="sxs-lookup"><span data-stu-id="a993e-388">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="a993e-389">Se ha corregido un problema por el que algunos vínculos de un gráfico copiado y pegado usaban direcciones de unidad asignadas, en lugar de direcciones universales.</span><span class="sxs-lookup"><span data-stu-id="a993e-389">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="a993e-390">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="a993e-390">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

- <span data-ttu-id="a993e-391">Se ha corregido un problema por el que Excel se bloqueaba cuando los complementos solicitaban elementos de host en hojas de cálculo que tuvieran formas con bloqueos noSelect.</span><span class="sxs-lookup"><span data-stu-id="a993e-391">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="a993e-392">Se ha corregido un problema por el que Excel se bloqueaba al intentar insertar tablas dinámicas en una hoja de gráfico.</span><span class="sxs-lookup"><span data-stu-id="a993e-392">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="outlook"></a><span data-ttu-id="a993e-393">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-393">Outlook</span></span>

- <span data-ttu-id="a993e-394">Se ha corregido un problema por el que la ventana del Editor de métodos de entrada (IME) se superponía al texto subyacente escrito mediante el IME cuando se usaban varios monitores con resoluciones diferentes.</span><span class="sxs-lookup"><span data-stu-id="a993e-394">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="a993e-395">Se ha corregido un problema que causaba un bloqueo cuando se visualizaba una plantilla mientras se redactaba un nuevo mensaje de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="a993e-395">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>

- <span data-ttu-id="a993e-396">Se ha corregido un problema por el que los usuarios no podían intercambiar carpetas públicas de Exchange 2010 después de la versión 1911 de Outlook.</span><span class="sxs-lookup"><span data-stu-id="a993e-396">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>

- <span data-ttu-id="a993e-397">Se ha corregido un problema por el que se desactivaba el botón de Categorizar para los calendarios de grupo en la cinta de opciones de Office.</span><span class="sxs-lookup"><span data-stu-id="a993e-397">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="a993e-398">Se ha corregido un problema por el que Outlook no pudo habilitar consejos de directiva para la Protección de pérdida de datos para usuarios que pagaron por el servicio con planes M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="a993e-398">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="a993e-399">Se ha corregido un problema que provocaba que Outlook se bloqueara en algunas compilaciones de Windows.</span><span class="sxs-lookup"><span data-stu-id="a993e-399">Addressed an issue that caused Outlook to crash on some Windows builds.</span></span>

- <span data-ttu-id="a993e-400">Se ha corregido un problema por el que los usuarios no pudieron compartir un calendario con un usuario invitado.</span><span class="sxs-lookup"><span data-stu-id="a993e-400">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

- <span data-ttu-id="a993e-401">Se ha corregido un problema en el que los usuarios veían los elementos de calendario que pasaban de la medianoche como Eventos de todo el día.</span><span class="sxs-lookup"><span data-stu-id="a993e-401">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>

- <span data-ttu-id="a993e-402">Se ha corregido un problema por el que la lista desplegable en las propiedades de carpeta del Archivo en línea no aparecía en monitores con un alto nivel de ppp.</span><span class="sxs-lookup"><span data-stu-id="a993e-402">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>

- <span data-ttu-id="a993e-403">Se ha corregido un problema por el que el evento Folder.BeforeItemMove no se activaba correctamente cuando un usuario movía elementos entre carpetas.</span><span class="sxs-lookup"><span data-stu-id="a993e-403">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>

- <span data-ttu-id="a993e-404">Se ha corregido un problema por el que Outlook se bloqueaba cuando dos complementos agregaban un botón al mismo grupo en la cinta de opciones.</span><span class="sxs-lookup"><span data-stu-id="a993e-404">We fixed an issue where Outlook crashed when two add-ins added a button to the same group in the ribbon.</span></span>

- <span data-ttu-id="a993e-405">Se ha corregido un problema que provocaba un error en Outlook al trabajar con hipervínculos en mensajes de correo electrónico de texto sin formato.</span><span class="sxs-lookup"><span data-stu-id="a993e-405">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>

- <span data-ttu-id="a993e-406">Se ha corregido un problema que provocaba que Outlook no pudiera analizar nombres de archivo largos codificados con RFC2231.</span><span class="sxs-lookup"><span data-stu-id="a993e-406">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>

- <span data-ttu-id="a993e-407">Se ha corregido un problema que provocaba que los usuarios de Outlook experimentaran interrupciones intermitentes al usar lectores de pantalla.</span><span class="sxs-lookup"><span data-stu-id="a993e-407">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

- <span data-ttu-id="a993e-408">Se ha corregido un problema que hacía que los usuarios con contactos en conflicto experimentaran bloqueos en Outlook.</span><span class="sxs-lookup"><span data-stu-id="a993e-408">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a993e-409">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a993e-409">PowerPoint</span></span>

- <span data-ttu-id="a993e-410">Se ha corregido un problema al abrir archivos configurados por el servidor con autenticación basada en formularios.</span><span class="sxs-lookup"><span data-stu-id="a993e-410">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>

- <span data-ttu-id="a993e-411">Se ha corregido un problema por el que los archivos de PowerPoint con gráficos o libros incrustados podrían causar errores al guardar el archivo.</span><span class="sxs-lookup"><span data-stu-id="a993e-411">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>

- <span data-ttu-id="a993e-412">Se ha corregido un problema en el que al acercar y alejar el área de presentación se daba una separación entre el recuadro de selección ampliado y el puntero del mouse.</span><span class="sxs-lookup"><span data-stu-id="a993e-412">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="a993e-413">Se ha corregido un problema que hacía que las diapositivas no se centraran después de usar la rueda del mouse para hacer zoom.</span><span class="sxs-lookup"><span data-stu-id="a993e-413">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

- <span data-ttu-id="a993e-414">Hemos corregido un problema por el que la revisión ortográfica y los métodos abreviados del teclado no funcionaban de manera esperada al usar un teclado de Suiza (QWERTZ) en inglés.</span><span class="sxs-lookup"><span data-stu-id="a993e-414">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

- <span data-ttu-id="a993e-415">Se ha corregido un problema por el que un panel de Comentarios cerrado por el usuario se abría automáticamente de nuevo.</span><span class="sxs-lookup"><span data-stu-id="a993e-415">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>

- <span data-ttu-id="a993e-416">Se ha corregido un problema por el que el editor de diapositivas de una diapositiva se superponía a la siguiente diapositiva.</span><span class="sxs-lookup"><span data-stu-id="a993e-416">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="a993e-417">Project</span><span class="sxs-lookup"><span data-stu-id="a993e-417">Project</span></span>

- <span data-ttu-id="a993e-418">Se ha corregido un problema por el que el evento ProjectBeforeTaskChange no se activaba al darse un cambio en la tarea de resumen del proyecto: ya sea en el campo de inicio o tarea del proyecto.</span><span class="sxs-lookup"><span data-stu-id="a993e-418">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="a993e-419">Se ha corregido un problema por el que una tarea marcada como completada al 100 % se mostraba por error no completada al 100 %.</span><span class="sxs-lookup"><span data-stu-id="a993e-419">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="a993e-420">Se ha corregido un problema por el que Project se bloqueaba después de hacer clic en Opciones.</span><span class="sxs-lookup"><span data-stu-id="a993e-420">We fixed an issue where Project would crash after clicking on Options.</span></span>

- <span data-ttu-id="a993e-421">Se ha corregido un problema que impedía que las tareas huérfanas se eliminaran o reasignarán después de eliminar su plan primario.</span><span class="sxs-lookup"><span data-stu-id="a993e-421">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="visio"></a><span data-ttu-id="a993e-422">Visio</span><span class="sxs-lookup"><span data-stu-id="a993e-422">Visio</span></span>

- <span data-ttu-id="a993e-423">Se ha corregido la regresión en el código dependiente.</span><span class="sxs-lookup"><span data-stu-id="a993e-423">There was regression in dependent code which has been fixed.</span></span> <span data-ttu-id="a993e-424">Ahora, las imágenes se representan en los servicios de Visio que se ejecutan en SharePoint local.</span><span class="sxs-lookup"><span data-stu-id="a993e-424">Now, the images are getting rendered in Visio services running on SharePoint Onprem.</span></span>

### <a name="word"></a><span data-ttu-id="a993e-425">Word</span><span class="sxs-lookup"><span data-stu-id="a993e-425">Word</span></span>

- <span data-ttu-id="a993e-426">Se ha corregido un problema por el que las marcas de hora en los paneles de comentarios no se basaban en la hora de la configuración regional del sistema.</span><span class="sxs-lookup"><span data-stu-id="a993e-426">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>

- <span data-ttu-id="a993e-427">Se ha resuelto un problema al abrir documentos de Word desde la entrega de documentos personalizados (aspx) cuando la dirección URL contenía un componente de consulta.</span><span class="sxs-lookup"><span data-stu-id="a993e-427">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="a993e-428">Se ha corregido un problema por el que no se mostraba un texto copiado y pegado en un panel de comentarios.</span><span class="sxs-lookup"><span data-stu-id="a993e-428">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>

- <span data-ttu-id="a993e-429">Se ha corregido un problema por el que los hipervínculos en los comentarios no funcionaban.</span><span class="sxs-lookup"><span data-stu-id="a993e-429">We fixed an issue where hyperlinks in comments weren’t working.</span></span>

- <span data-ttu-id="a993e-430">Se ha corregido un problema en el que al acercar y alejar el área de presentación se daba una separación entre el recuadro de selección ampliado y el puntero del mouse.</span><span class="sxs-lookup"><span data-stu-id="a993e-430">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="a993e-431">Se ha corregido un problema por el que los comentarios entre la aplicación web y la aplicación de escritorio no estaban sincronizados.</span><span class="sxs-lookup"><span data-stu-id="a993e-431">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

- <span data-ttu-id="a993e-432">Se ha corregido un problema en el que las burbujas de sugerencias de comentarios aparecían borrosas al 100 % de zoom.</span><span class="sxs-lookup"><span data-stu-id="a993e-432">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>

- <span data-ttu-id="a993e-433">Hemos corregido un problema en el que agregar un nuevo comentario en un documento en blanco no pasaba nada.</span><span class="sxs-lookup"><span data-stu-id="a993e-433">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>

- <span data-ttu-id="a993e-434">Se ha corregido un problema por el que no funcionaba pegar HTML en WordMail para Calendario.</span><span class="sxs-lookup"><span data-stu-id="a993e-434">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>

- <span data-ttu-id="a993e-435">Se ha corregido un problema por el que responder a un comentario en una sesión de coautoría podía bloquear Word.</span><span class="sxs-lookup"><span data-stu-id="a993e-435">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

- <span data-ttu-id="a993e-436">Hemos corregido un problema que haría que la aplicación se bloqueara cuando se insertara o actualizara un índice en un documento que contuviera más de cien entradas.</span><span class="sxs-lookup"><span data-stu-id="a993e-436">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>

- <span data-ttu-id="a993e-437">Se ha corregido un problema por el que habilitar la directiva de Word 2007 y, luego, los documentos binarios y de plantillas podía causar errores en ciertos casos de coautoría.</span><span class="sxs-lookup"><span data-stu-id="a993e-437">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>

- <span data-ttu-id="a993e-438">Hemos corregido un problema que provocaba que los archivos con valores XML personalizados se abrieran muy despacio.</span><span class="sxs-lookup"><span data-stu-id="a993e-438">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

- <span data-ttu-id="a993e-439">Se ha corregido un problema por el que no se abrían los archivos con nombres de ruta largos (mayores que 32 000 caracteres) y no se mostraba un mensaje de error adecuado.</span><span class="sxs-lookup"><span data-stu-id="a993e-439">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a993e-440">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="a993e-440">Office Suite</span></span>

- <span data-ttu-id="a993e-441">Hemos estudiado y resuelto el problema por el que una implementación de Office 365 ProPlus a través de Intune se pausaba después de apagar el SO.</span><span class="sxs-lookup"><span data-stu-id="a993e-441">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

- <span data-ttu-id="a993e-442">Hemos corregido un problema en Visual Basic para las aplicaciones de Microsoft Office, por el que la aplicación de Office consideraba como corruptos ciertos proyectos de VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre o la ruta de la biblioteca.</span><span class="sxs-lookup"><span data-stu-id="a993e-442">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="a993e-443">Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.</span><span class="sxs-lookup"><span data-stu-id="a993e-443">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2005-june-08"></a><span data-ttu-id="a993e-445">Versión 2005: 8 de junio</span><span class="sxs-lookup"><span data-stu-id="a993e-445">Version 2005: June 08</span></span>
<span data-ttu-id="a993e-446">*Versión 2005 (compilación 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="a993e-446">*Version 2005 (Build 12827.20336)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-448">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-448">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="a993e-449">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a993e-449">PowerPoint</span></span>

- <span data-ttu-id="a993e-450">Se ha corregido un problema en el cuadro de diálogo Reemplazar fuente, donde la lista desplegable Reemplazar fuente solo mostraba las fuentes de la presentación, en lugar de las fuentes instaladas en el sistema.</span><span class="sxs-lookup"><span data-stu-id="a993e-450">We have fixed an issue with replace fonts dialog where replace font dropdown only shows fonts within the presentation instead of fonts installed on the system.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2005-june-04"></a><span data-ttu-id="a993e-452">Versión 2005: 4 de junio</span><span class="sxs-lookup"><span data-stu-id="a993e-452">Version 2005: June 04</span></span>
<span data-ttu-id="a993e-453">*Versión 2005 (compilación 12827.20320)*</span><span class="sxs-lookup"><span data-stu-id="a993e-453">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="a993e-455">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-455">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="a993e-456">Access</span><span class="sxs-lookup"><span data-stu-id="a993e-456">Access</span></span>

- <span data-ttu-id="a993e-457">**Manténgase al día con las horas. El tipo de datos Fecha y hora extendida tiene mayor precisión.:** Presentamos un tipo de datos nuevo y mejorado.</span><span class="sxs-lookup"><span data-stu-id="a993e-457">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="a993e-458">Para mejorar la compatibilidad de la sintaxis con SQL y la precisión y el nivel de detalle en los registros que incluyen fechas y horas, estamos implementando el tipo de datos DateTime2 en Access.</span><span class="sxs-lookup"><span data-stu-id="a993e-458">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="a993e-459">Este tipo de datos de fecha y hora adicional incluirá un intervalo de fechas mayor (de 0001-01-01 a 9999-12-31), con mayor precisión de tiempo (nanosegundos, en lugar de segundos) en el que se podrán ofrecer y realizar cálculos.</span><span class="sxs-lookup"><span data-stu-id="a993e-459">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="a993e-460">Para habilitarlo, seleccione Nuevo campo > Fecha y hora extendida.</span><span class="sxs-lookup"><span data-stu-id="a993e-460">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="a993e-461">Más información</span><span class="sxs-lookup"><span data-stu-id="a993e-461">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="a993e-462">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-462">Excel</span></span>

- <span data-ttu-id="a993e-463">**Crear tablas dinámicas de conjuntos de datos en Power BI desde Excel:** puede crear tablas dinámicas en Excel conectadas a los conjuntos de datos almacenados en Power BI con tan solo unos clics.</span><span class="sxs-lookup"><span data-stu-id="a993e-463">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="a993e-464">Así, podrá obtener lo mejor de las tablas dinámicas y de Power BI.</span><span class="sxs-lookup"><span data-stu-id="a993e-464"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="a993e-465">Calcule, resuma y analice los conjuntos de datos seguros de Power BI con las tablas dinámicas de Excel.</span><span class="sxs-lookup"><span data-stu-id="a993e-465">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="a993e-466">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-466">Outlook</span></span>

- <span data-ttu-id="a993e-467">**Opción para volver a abrir rápidamente los elementos de la sesión anterior de Outlook:** hemos agregado una opción para volver a abrir rápidamente los elementos de una sesión anterior de Outlook.</span><span class="sxs-lookup"><span data-stu-id="a993e-467">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-470">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-470">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="a993e-471">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a993e-471">PowerPoint</span></span>

- <span data-ttu-id="a993e-472">Hemos corregido un bloqueo cuando el usuario tiene comentarios modernos y heredados en un archivo, lo que provoca una actualización de los comentarios.</span><span class="sxs-lookup"><span data-stu-id="a993e-472">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a993e-473">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="a993e-473">Office Suite</span></span>

- <span data-ttu-id="a993e-474">Hemos resuelto el problema de la tasa de error de ValidateInstall estableciendo la validación de instalación del Complemento de Bing como verdadera de forma predeterminada y considerando el éxito de devolución de MSI como una instalación con éxito.</span><span class="sxs-lookup"><span data-stu-id="a993e-474">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2005-may-29"></a><span data-ttu-id="a993e-476">Versión 2005: 29 de mayo</span><span class="sxs-lookup"><span data-stu-id="a993e-476">Version 2005: May 29</span></span>
<span data-ttu-id="a993e-477">*Versión 2005 (compilación 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="a993e-477">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="a993e-479">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-479">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="a993e-480">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-480">Excel</span></span>

- <span data-ttu-id="a993e-481">**Vista de hoja:** ordenar y filtrar cuando colabore con otras personas en la versión de escritorio de Excel.</span><span class="sxs-lookup"><span data-stu-id="a993e-481">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="a993e-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-482">Outlook</span></span>

- <span data-ttu-id="a993e-483">**Se agregaron más botones a las notificaciones del sistema de Outlook:** los botones de Acción rápida aparecen ahora en las notificaciones del sistema de Outlook cuando se ejecuta Outlook en Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a993e-483">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-486">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-486">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="a993e-487">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-487">Outlook</span></span>

- <span data-ttu-id="a993e-488">Se ha corregido un problema que provocaba que los usuarios de las versiones de Windows 10 Server vieran la advertencia: "Estado de antivirus: no válido".</span><span class="sxs-lookup"><span data-stu-id="a993e-488">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="a993e-489">Esta versión de Windows admite la detección del antivirus, pero no se encontró ninguno a pesar de tener un antivirus correctamente instalado".</span><span class="sxs-lookup"><span data-stu-id="a993e-489">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a993e-490">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="a993e-490">Office Suite</span></span>

- <span data-ttu-id="a993e-491">El host de Office se bloqueaba en Windows, cuando se activaba un complemento si la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth estaba establecida en cero.</span><span class="sxs-lookup"><span data-stu-id="a993e-491">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="a993e-492">Este cambio arreglaría el problema.</span><span class="sxs-lookup"><span data-stu-id="a993e-492">This change would fix this issue.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2005-may-21"></a><span data-ttu-id="a993e-494">Versión 2005: 21 de mayo</span><span class="sxs-lookup"><span data-stu-id="a993e-494">Version 2005: May 21</span></span>
<span data-ttu-id="a993e-495">*Versión 2005 (compilación 12827.20210)*</span><span class="sxs-lookup"><span data-stu-id="a993e-495">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)




[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-499">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-499">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a993e-500">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-500">Excel</span></span>

- <span data-ttu-id="a993e-501">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="a993e-501">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="a993e-502">En algunos casos, al hacer clic en un hipervínculo que dirige a un lugar del mismo libro, el libro queda oculto.</span><span class="sxs-lookup"><span data-stu-id="a993e-502">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="a993e-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-503">Outlook</span></span>

- <span data-ttu-id="a993e-504">Se ha corregido un problema con el evento de auditoría CLP para la etiqueta de responder o reenviar.</span><span class="sxs-lookup"><span data-stu-id="a993e-504">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="a993e-505">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al enviar comentarios desde una Notificación de administrador.</span><span class="sxs-lookup"><span data-stu-id="a993e-505">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2005-may-14"></a><span data-ttu-id="a993e-507">Versión 2005: 14 de mayo</span><span class="sxs-lookup"><span data-stu-id="a993e-507">Version 2005: May 14</span></span>
<span data-ttu-id="a993e-508">*Versión 2005 (compilación 12827.20160)*</span><span class="sxs-lookup"><span data-stu-id="a993e-508">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="a993e-510">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-510">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a993e-511">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-511">Excel</span></span>

- <span data-ttu-id="a993e-512">**Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.</span><span class="sxs-lookup"><span data-stu-id="a993e-512">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a993e-513">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a993e-513">PowerPoint</span></span>

- <span data-ttu-id="a993e-514">**No es necesario hacer clic: sus miniauriculares tienen que cubrir lo siguiente:** Usar sus Surface Earbuds para controlar sus presentaciones de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a993e-514">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="a993e-515">Importante: Debe emparejar sus Surface Earbuds en la aplicación Surface Audio para Windows 10 para poder usar gestos para controlar las presentaciones.</span><span class="sxs-lookup"><span data-stu-id="a993e-515">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="a993e-516">Aquí encontrará instrucciones para empezar a usar la aplicación Surface Audio en Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a993e-516">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="a993e-517">Más información</span><span class="sxs-lookup"><span data-stu-id="a993e-517">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="a993e-518">**Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.</span><span class="sxs-lookup"><span data-stu-id="a993e-518">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="a993e-519">Word</span><span class="sxs-lookup"><span data-stu-id="a993e-519">Word</span></span>

- <span data-ttu-id="a993e-520">**Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.</span><span class="sxs-lookup"><span data-stu-id="a993e-520">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-523">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-523">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="a993e-524">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-524">Excel</span></span>

- <span data-ttu-id="a993e-525">Se aumentó el tamaño de los controles de edición de referencia de celda en el cuadro de diálogo Barras de error personalizadas utilizado con gráficos.</span><span class="sxs-lookup"><span data-stu-id="a993e-525">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="a993e-526">Se ha corregido un problema por el que las tablas de datos de los gráficos podían representar incorrectamente los valores de un eje de fechas.</span><span class="sxs-lookup"><span data-stu-id="a993e-526">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="a993e-527">Se ha corregido un problema por el que los saltos de página no se podían deshabilitar después de ir al diseño de página o la vista previa de salto de página</span><span class="sxs-lookup"><span data-stu-id="a993e-527">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="a993e-528">Se ha corregido un problema por el que los estilos de línea de los gráficos podían perderse tras ocultar y mostrar columnas con datos de series.</span><span class="sxs-lookup"><span data-stu-id="a993e-528">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="a993e-529">Se ha corregido un problema por el que insertar una columna en una lista filtrada llevaba más tiempo de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="a993e-529">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="a993e-530">Corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.</span><span class="sxs-lookup"><span data-stu-id="a993e-530">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="a993e-531">Se ha corregido un problema que hacía que el vínculo externo dejara de funcionar después de que se volviera a abrir el archivo si su ruta de acceso era demasiado larga.</span><span class="sxs-lookup"><span data-stu-id="a993e-531">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="a993e-532">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="a993e-532">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="a993e-533">Application.Evaluate (VBA) no funcionaba para funciones definidas por el usuario en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="a993e-533">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="a993e-534">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="a993e-534">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="a993e-535">Este cambio corrige un problema que hacía que la información de formato condicional (CF) no se guardase correctamente en los archivos XLSB.</span><span class="sxs-lookup"><span data-stu-id="a993e-535">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="a993e-536">Este cambio corrige un problema en el que el valor de la línea de tendencia del gráfico R-cuadrado (en el caso de la intersección forzada y) era incorrecto aunque la función de ESTIMACIÓN devuelva el valor correcto.</span><span class="sxs-lookup"><span data-stu-id="a993e-536">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="a993e-537">Este cambio arregla un problema en el que no siempre se guardaba el formato de la línea de tendencia de los gráficos personalizados.</span><span class="sxs-lookup"><span data-stu-id="a993e-537">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="a993e-538">Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "Libro compartido" heredado.</span><span class="sxs-lookup"><span data-stu-id="a993e-538">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="a993e-539">Se ha corregido el problema por el que el formato personalizado de un gráfico dinámico podía no guardarse si estaba habilitada la opción "Invertir si es negativo".</span><span class="sxs-lookup"><span data-stu-id="a993e-539">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="a993e-540">Se ha corregido un problema por el que el formato personalizado de un único punto de datos de un gráfico dinámico no se guardaba si estaba seleccionada la opción "invertir si es negativo".</span><span class="sxs-lookup"><span data-stu-id="a993e-540">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="a993e-541">Este cambio corrige un problema por el que el carácter "@" cargado en un archivo CSV causaba que la cadena tras el carácter "@" se convirtiera en una fórmula.</span><span class="sxs-lookup"><span data-stu-id="a993e-541">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="a993e-542">Se ha corregido un problema por el que los valores decimales de la función SECUENCIA no se redondeaban correctamente.</span><span class="sxs-lookup"><span data-stu-id="a993e-542">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="a993e-543">OneNote</span><span class="sxs-lookup"><span data-stu-id="a993e-543">OneNote</span></span>

- <span data-ttu-id="a993e-544">Corregido un problema en el que los saltos de línea se almacenaban como pestañas verticales.</span><span class="sxs-lookup"><span data-stu-id="a993e-544">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="a993e-545">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-545">Outlook</span></span>

- <span data-ttu-id="a993e-546">Soluciona un problema que hacía que los usuarios no pudieran agregar un grupo de contactos personal como asistente de la reunión.</span><span class="sxs-lookup"><span data-stu-id="a993e-546">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="a993e-547">Corregido un problema por el que se desactivaba el botón de Categorizar para los calendarios de grupo en la cinta de opciones de Office.</span><span class="sxs-lookup"><span data-stu-id="a993e-547">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="a993e-548">Se ha corregido un problema que provocaba que Outlook se bloqueara al abrir archivos .msg y .oft guardados localmente después de una actualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="a993e-548">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="a993e-549">Se ha solucionado un problema por el que los clientes de las empresas con carpetas de grupo no implementadas o que no funcionaban, hacían que Outlook mostrara un mensaje de "no responde".</span><span class="sxs-lookup"><span data-stu-id="a993e-549">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="a993e-550">Corrige un problema por el que los safelinks muy largos en los que los usuarios hacían clic en el cliente de escritorio de Outlook no se podían cargar debido a un truncamiento.</span><span class="sxs-lookup"><span data-stu-id="a993e-550">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="a993e-551">Se ha corregido un problema por el que las carpetas de Outlook con nombres que contenían caracteres DBCS (conjunto de caracteres de doble byte) desaparecían intermitentemente al sincronizar con el servidor.</span><span class="sxs-lookup"><span data-stu-id="a993e-551">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="a993e-552">Esto sucedía si Outlook estaba configurado con una cuenta IMAP y se ejecutaba en un sistema con la configuración regional configurada en japonés.</span><span class="sxs-lookup"><span data-stu-id="a993e-552">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="a993e-553">Se solucionó un problema que hacía que las reglas de eliminación creadas para los buzones que no fueran el buzón principal del usuario dejaran de ser válidas.</span><span class="sxs-lookup"><span data-stu-id="a993e-553">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="a993e-554">Se solucionó un problema que hacía que los datos adjuntos se perdieran al reenviar un mensaje cifrado.</span><span class="sxs-lookup"><span data-stu-id="a993e-554">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="a993e-555">Se solucionó un problema que provocaba que las reuniones para las que faltan más de 2 meses no mostraran un tema de reunión en el Asistente de programación.</span><span class="sxs-lookup"><span data-stu-id="a993e-555">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="a993e-556">Se ha corregido un problema que hacía que los usuarios vieran truncado el cuerpo del mensaje al reenviar mensajes HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="a993e-556">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="a993e-557">Se agregó la capacidad de aplicar la configuración de firma predeterminada de S/MIME a través de la directiva de grupo.</span><span class="sxs-lookup"><span data-stu-id="a993e-557">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a993e-558">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a993e-558">PowerPoint</span></span>

- <span data-ttu-id="a993e-559">Se ha corregido un problema por el que el borrador de los comentarios dejaba de estar disponible si un usuario creaba un comentario sin publicarlo, cerraba el panel de comentarios, abría una nueva ventana, se desplazaba por varias diapositivas, cerraba la ventana y volvía a abrir el panel de comentarios en la presentación original.</span><span class="sxs-lookup"><span data-stu-id="a993e-559">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="a993e-560">Se ha solucionado un problema por el que al pasar el ratón por encima del símbolo del asterisco (\*) no aparecía el nombre de usuario y la fecha de la última persona que actualizó el documento.</span><span class="sxs-lookup"><span data-stu-id="a993e-560">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="a993e-561">Project</span><span class="sxs-lookup"><span data-stu-id="a993e-561">Project</span></span>

- <span data-ttu-id="a993e-562">Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se activa un evento ProjectBeforeTaskChange adicional.</span><span class="sxs-lookup"><span data-stu-id="a993e-562">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="a993e-563">Se solucionó un problema por el cual Proyect podía bloquearse al cambiar el campo de estado del tablero en un proyecto que conectado a una lista de tareas de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="a993e-563">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="a993e-564">Corregido un problema por el que Project puede bloquearse al guardar proyectos creados con versiones anteriores de Project.</span><span class="sxs-lookup"><span data-stu-id="a993e-564">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="a993e-565">Se ha corregido un problema por el que, si Project estaba conectado a Project Web App y el separador decimal era una coma, el método TaskDependencies Add producía un error al agregar retardo.</span><span class="sxs-lookup"><span data-stu-id="a993e-565">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="a993e-566">Word</span><span class="sxs-lookup"><span data-stu-id="a993e-566">Word</span></span>

- <span data-ttu-id="a993e-567">Se ha corregido un problema por el que la inserción de comentarios en un documento en el modo de colaboración no funcionaba en ocasiones.</span><span class="sxs-lookup"><span data-stu-id="a993e-567">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="a993e-568">Este cambio corrige un problema por el que la tarjeta de contactos parpadeaba si se hacía clic en la mención @.</span><span class="sxs-lookup"><span data-stu-id="a993e-568">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="a993e-569">Al habilitar la opción "Mostrar marcadores" no se mostrarán los marcadores.</span><span class="sxs-lookup"><span data-stu-id="a993e-569">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="a993e-570">Este error se ha corregido.</span><span class="sxs-lookup"><span data-stu-id="a993e-570">This has been fixed.</span></span>

- <span data-ttu-id="a993e-571">Se ha corregido el problema por el que al cerrar un documento con borrador de comentarios se preguntaba al usuario si deseaba cerrar el documento sin guardar los comentarios del borrador.</span><span class="sxs-lookup"><span data-stu-id="a993e-571">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="a993e-572">Al cancelar la solicitud, se cerraba el documento en lugar de quedar abierto.</span><span class="sxs-lookup"><span data-stu-id="a993e-572">Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="a993e-573">Se ha corregido un problema al copiar y pegar títulos.</span><span class="sxs-lookup"><span data-stu-id="a993e-573">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="a993e-574">Se ha corregido un problema por el que al traducir un comentario publicado se producía el error "Error al insertar el texto traducido".</span><span class="sxs-lookup"><span data-stu-id="a993e-574">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="a993e-575">Este cambio soluciona un problema por el que el texto con hipervínculos podía no aparecer si la opción "Mostrar códigos de campo en lugar de sus valores" estaba activada.</span><span class="sxs-lookup"><span data-stu-id="a993e-575">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="a993e-576">En la Vista web o en el lector inmersivo, al hacer clic en una sugerencia se desplazaba a la parte superior incluso aunque ya estuviera a la vista.</span><span class="sxs-lookup"><span data-stu-id="a993e-576">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="a993e-577">Este error se ha corregido.</span><span class="sxs-lookup"><span data-stu-id="a993e-577">This has been fixed.</span></span>

- <span data-ttu-id="a993e-578">Se ha corregido un problema por el que al intentar guardar un archivo que contenía una macro con un nombre nuevo, este se guardaba con la extensión. docx y el nombre de archivo WRO0004.docx, independientemente de lo que el usuario escribiera, lo que hacía que el archivo no se pudiera volver a usar.</span><span class="sxs-lookup"><span data-stu-id="a993e-578">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a993e-579">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="a993e-579">Office Suite</span></span>

- <span data-ttu-id="a993e-580">Cuando se asignaba a un usuario una directiva que lo llevaba a Teams solo, aún se podía usar el complemento para Outlook de Skype Empresarial para programar reuniones.</span><span class="sxs-lookup"><span data-stu-id="a993e-580">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="a993e-581">Tras esta actualización, ya no se podrán programar reuniones de Skype Empresarial después de que el cliente lea la directiva en la que se indica que el usuario participa en Teams solo y entra en la reunión como Unirse solo.</span><span class="sxs-lookup"><span data-stu-id="a993e-581">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="a993e-582">Además, el complemento de Outlook para Skype Empresarial no se activará durante el inicio si ve que el cliente de Skype Empresarial se encuentra en modo de Unirse solo.</span><span class="sxs-lookup"><span data-stu-id="a993e-582">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="a993e-583">Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.</span><span class="sxs-lookup"><span data-stu-id="a993e-583">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="a993e-584">Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.</span><span class="sxs-lookup"><span data-stu-id="a993e-584">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2004-may-11"></a><span data-ttu-id="a993e-586">Versión 2004: 11 de mayo</span><span class="sxs-lookup"><span data-stu-id="a993e-586">Version 2004: May 11</span></span>
<span data-ttu-id="a993e-587">*Versión 2004 (compilación 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="a993e-587">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="a993e-589">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-589">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a993e-590">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-590">Excel</span></span>

- <span data-ttu-id="a993e-591">**Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.</span><span class="sxs-lookup"><span data-stu-id="a993e-591">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="a993e-592">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-592">Outlook</span></span>

- <span data-ttu-id="a993e-593">**Vínculos mejorados en el correo electrónico:** al incluir un vínculo a un archivo, la dirección URL se reemplaza por el nombre del archivo.</span><span class="sxs-lookup"><span data-stu-id="a993e-593">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="a993e-594">Puede cambiar los permisos para que todos los destinatarios tengan acceso.</span><span class="sxs-lookup"><span data-stu-id="a993e-594">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="a993e-595">Más información</span><span class="sxs-lookup"><span data-stu-id="a993e-595">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="a993e-596">Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span><span class="sxs-lookup"><span data-stu-id="a993e-596">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="a993e-597">**Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office. Sus documentos han pasado a ser más elegantes.</span><span class="sxs-lookup"><span data-stu-id="a993e-597">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a993e-598">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a993e-598">PowerPoint</span></span>

- <span data-ttu-id="a993e-599">**Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.</span><span class="sxs-lookup"><span data-stu-id="a993e-599">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>  [<span data-ttu-id="a993e-600">Más información</span><span class="sxs-lookup"><span data-stu-id="a993e-600">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="a993e-601">Word</span><span class="sxs-lookup"><span data-stu-id="a993e-601">Word</span></span>

- <span data-ttu-id="a993e-602">**Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.</span><span class="sxs-lookup"><span data-stu-id="a993e-602">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-605">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-605">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a993e-606">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-606">Outlook</span></span>

- <span data-ttu-id="a993e-607">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al mostrar las notificaciones del sistema.</span><span class="sxs-lookup"><span data-stu-id="a993e-607">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2004-may-04"></a><span data-ttu-id="a993e-609">Versión 2004: 4 de mayo</span><span class="sxs-lookup"><span data-stu-id="a993e-609">Version 2004: May 04</span></span>
<span data-ttu-id="a993e-610">*Versión 2004 (Compilación 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="a993e-610">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="a993e-612">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-612">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a993e-613">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-613">Outlook</span></span>

- <span data-ttu-id="a993e-614">**Mejores resultados, en un instante:** actualizamos la experiencia de búsqueda para que sea más inteligente, rápida y fiable que nunca.</span><span class="sxs-lookup"><span data-stu-id="a993e-614">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="a993e-615">Más información</span><span class="sxs-lookup"><span data-stu-id="a993e-615">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="a993e-616">**Notificación de incidentes para administradores de TI:** se notificará a los administradores globales de espacios empresariales de Microsoft 365 y a los administradores de aplicaciones de Office acerca de los incidentes de Outlook y Exchange de O365 que afectan a sus usuarios con una nueva notificación en el panel derecho en Outlook para Windows.</span><span class="sxs-lookup"><span data-stu-id="a993e-616">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="a993e-617">Más información</span><span class="sxs-lookup"><span data-stu-id="a993e-617">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-620">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-620">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="a993e-621">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="a993e-621">Office Suite</span></span>

- <span data-ttu-id="a993e-622">Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.</span><span class="sxs-lookup"><span data-stu-id="a993e-622">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (NO QUITAR ERRORES DE DETALLES DE CONTENIDO FINAL)

## <a name="version-2004-april-29"></a><span data-ttu-id="a993e-624">Versión 2004: 29 de abril</span><span class="sxs-lookup"><span data-stu-id="a993e-624">Version 2004: April 29</span></span>
<span data-ttu-id="a993e-625">*Versión 2004 (compilación 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="a993e-625">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="a993e-627">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-627">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a993e-628">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-628">Outlook</span></span>

- <span data-ttu-id="a993e-629">**Protección de datos del grupo:** la etiqueta de confidencialidad que elija al crear un grupo se aplica al correo electrónico del grupo, a los documentos y a los sitios de equipo.</span><span class="sxs-lookup"><span data-stu-id="a993e-629">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-632">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-632">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a993e-633">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-633">Outlook</span></span>

- <span data-ttu-id="a993e-634">Corrige un problema que causaba que Outlook se bloqueara en algunas compilaciones de Windows.</span><span class="sxs-lookup"><span data-stu-id="a993e-634">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2004-april-25"></a><span data-ttu-id="a993e-636">Versión 2004: 25 de abril</span><span class="sxs-lookup"><span data-stu-id="a993e-636">Version 2004: April 25</span></span>
<span data-ttu-id="a993e-637">*Versión 2004 (compilación 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="a993e-637">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-639">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-639">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a993e-640">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-640">Outlook</span></span>

- <span data-ttu-id="a993e-641">Se ha corregido un problema que provocaba que Outlook se bloqueara al abrir archivos .msg y .oft guardados localmente después de una actualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="a993e-641">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="a993e-642">Project</span><span class="sxs-lookup"><span data-stu-id="a993e-642">Project</span></span>

- <span data-ttu-id="a993e-643">Se ha corregido un problema que hace que si está usando Project conectado a Project Web App y el separador decimal es una coma, el método TaskDependencies Add producirá un error al intentar agregar retardo a una dependencia.</span><span class="sxs-lookup"><span data-stu-id="a993e-643">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a993e-644">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="a993e-644">Office Suite</span></span>

- <span data-ttu-id="a993e-645">Esta corrección resuelve un error que impide restringir el acceso y proteger los archivos con una contraseña de forma simultánea.</span><span class="sxs-lookup"><span data-stu-id="a993e-645">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (NO ELIMINAR LOS DETALLES DEL CONTENIDO FINAL)

## <a name="version-2004-april-21"></a><span data-ttu-id="a993e-647">Versión 2004: 21 de abril</span><span class="sxs-lookup"><span data-stu-id="a993e-647">Version 2004: April 21</span></span>
<span data-ttu-id="a993e-648">*Versión 2004 (compilación 12730.20182)*</span><span class="sxs-lookup"><span data-stu-id="a993e-648">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-650">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-650">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a993e-651">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-651">Outlook</span></span>

- <span data-ttu-id="a993e-652">Corrige un problema que provocaba que el ancho del panel de carpetas cambiara de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="a993e-652">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="a993e-653">Corrige un problema que provocaba que los usuarios experimentaran un error al salir de Outlook.</span><span class="sxs-lookup"><span data-stu-id="a993e-653">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2004-april-15"></a><span data-ttu-id="a993e-655">Versión 2004: 15 de abril</span><span class="sxs-lookup"><span data-stu-id="a993e-655">Version 2004: April 15</span></span>
<span data-ttu-id="a993e-656">*Versión 2004 (compilación 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="a993e-656">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="a993e-658">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-658">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a993e-659">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-659">Excel</span></span>

- <span data-ttu-id="a993e-660">**El soporte para el conector de Facebook va a terminar:** a partir de abril de 2020. Excel ya no admitirá conexiones de datos externos que usen el conector de Facebook.</span><span class="sxs-lookup"><span data-stu-id="a993e-660">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="a993e-661">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-661">Outlook</span></span>

- <span data-ttu-id="a993e-662">\*\*Nueva opción para desactivar las sugerencias de @menciones al escribir correo en Outlook: \*\*¿le resulta el selector de @menciones más molesto que útil?</span><span class="sxs-lookup"><span data-stu-id="a993e-662">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="a993e-663">Ahora puede desactivarlo si lo prefiere.</span><span class="sxs-lookup"><span data-stu-id="a993e-663">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a993e-664">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a993e-664">PowerPoint</span></span>

- <span data-ttu-id="a993e-665">**Sincronice los cambios mientras realiza la presentación:** sincronice los cambios cuando se hagan aunque la presentación esté en el modo de presentación con diapositivas.</span><span class="sxs-lookup"><span data-stu-id="a993e-665">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="a993e-666">Word</span><span class="sxs-lookup"><span data-stu-id="a993e-666">Word</span></span>

- <span data-ttu-id="a993e-667">**Anote su copia privada:** cree notas escritas a mano privadas realizando una copia privada de un documento compartido.</span><span class="sxs-lookup"><span data-stu-id="a993e-667">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="a993e-668">Vaya a Ver > Crear una copia privada para empezar.</span><span class="sxs-lookup"><span data-stu-id="a993e-668">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-671">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-671">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a993e-672">Access</span><span class="sxs-lookup"><span data-stu-id="a993e-672">Access</span></span>

- <span data-ttu-id="a993e-673">Se han corregido problema al cambiar el tamaño y actualizar tablas en el panel de tareas.</span><span class="sxs-lookup"><span data-stu-id="a993e-673">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="a993e-674">Se ha corregido un problema por el que las versiones internacionales de Access mostraban cadenas en inglés en la interfaz de usuario.</span><span class="sxs-lookup"><span data-stu-id="a993e-674">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="a993e-675">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-675">Excel</span></span>

- <span data-ttu-id="a993e-676">Se ha corregido un problema por el que seleccionar un rango de celdas en una hoja daba lugar a la selección de una sola celda.</span><span class="sxs-lookup"><span data-stu-id="a993e-676">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="a993e-677">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="a993e-677">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="a993e-678">Se ha corregido un problema que hacía que Excel se bloqueara en ciertos casos después de copiar una hoja que contenía una tabla dinámica.</span><span class="sxs-lookup"><span data-stu-id="a993e-678">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="a993e-679">Application.Evaluate (VBA) no funcionaba para funciones definidas por el usuario en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="a993e-679">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="a993e-680">Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al editar un rango de celdas grande por programación.</span><span class="sxs-lookup"><span data-stu-id="a993e-680">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="a993e-681">Se ha corregido un problema de rendimiento al abrir archivos CSV con entornos japoneses.</span><span class="sxs-lookup"><span data-stu-id="a993e-681">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="a993e-682">Se ha corregido un problema que provocaba que al insertar una plantilla de gráfico definida por el usuario como predeterminada se guardara como un gráfico de columnas.</span><span class="sxs-lookup"><span data-stu-id="a993e-682">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="a993e-683">Se ha corregido un problema por el que las etiquetas de datos en los gráficos se mostraban en blanco cuando las celdas de datos subyacentes no tuvieran un título.</span><span class="sxs-lookup"><span data-stu-id="a993e-683">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="a993e-684">Se ha corregido un problema que podía provocar que Excel dejara de responder al reducir el tamaño de un gráfico con algunos rangos de eje x.</span><span class="sxs-lookup"><span data-stu-id="a993e-684">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="a993e-685">Se ha corregido un problema por el que, en una hoja de Excel con referencia de celda F1C1 habilitada y en coautoría o compartida, al pasar el ratón por el icono de presencia del usuario no se mostraba la referencia de celda activa en modo F1C1.</span><span class="sxs-lookup"><span data-stu-id="a993e-685">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="a993e-686">Este cambio corrige retrasos al procesar imágenes con información de protocolo mal formada o incorrecta.</span><span class="sxs-lookup"><span data-stu-id="a993e-686">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="a993e-687">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-687">Outlook</span></span>

- <span data-ttu-id="a993e-688">Este cambio corrige retrasos al procesar imágenes con información de protocolo mal formada o incorrecta.</span><span class="sxs-lookup"><span data-stu-id="a993e-688">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="a993e-689">Este cambio corrige un problema por el que los cambios más recientes en los borradores de correo electrónico no se actualizaban.</span><span class="sxs-lookup"><span data-stu-id="a993e-689">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="a993e-690">Se corrigió un problema por el que hacer clic derecho del mouse en un archivo y usar "Enviar a" no funcionaba.</span><span class="sxs-lookup"><span data-stu-id="a993e-690">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="a993e-691">Se ha corregido un problema que provocaba que los delegados viesen distintas jerarquías de carpetas en diferentes equipos para los buzones compartidos.</span><span class="sxs-lookup"><span data-stu-id="a993e-691">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="a993e-692">Se ha corregido un problema que provocaba que las categorías desapareciesen en ocasiones de los mensajes de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="a993e-692">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="a993e-693">Se ha corregido un problema que provocaba que se produjesen errores en la activación de algunos avisos al cambiar la zona horaria en un equipo.</span><span class="sxs-lookup"><span data-stu-id="a993e-693">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="a993e-694">Se ha corregido un problema que provocaba que los usuarios experimentasen un error al intentar ver las propiedades de un formulario de la organización.</span><span class="sxs-lookup"><span data-stu-id="a993e-694">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="a993e-695">Se corrigió un problema por el que si un usuario tenía una ruta de búsqueda personalizada para la libreta de direcciones, el ámbito de la resolución de nombres de Outlook se limitaba a la ruta personalizada, en lugar de incluir la lista global de direcciones (LGD).</span><span class="sxs-lookup"><span data-stu-id="a993e-695">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="a993e-696">Se ha corregido un problema que hacía que el botón "Guardar en la nube" faltara en las Herramientas de datos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="a993e-696">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="a993e-697">Se ha corregido un problema que hacía que los usuarios no pudieran agregar una firma al responder a un mensaje administrado con derechos digitales desde una ventana de inspección cuando el usuario no tenía permiso de propietario sobre el mensaje al que se respondía.</span><span class="sxs-lookup"><span data-stu-id="a993e-697">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="a993e-698">Se ha corregido un problema que hacía que los usuarios no pudieran agregar archivos adjuntos adicionales desde una ubicación web a una reunión creada previamente.</span><span class="sxs-lookup"><span data-stu-id="a993e-698">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="a993e-699">Se ha corregido un problema que hacía que la fecha de "última modificación" de un archivo se actualizara al agregar un archivo adjunto a un correo electrónico o al guardar un archivo adjunto desde un correo arrastrándolo y colocándolo (en lugar de hacerlo a través de un menú).</span><span class="sxs-lookup"><span data-stu-id="a993e-699">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="a993e-700">Se ha corregido un problema que hacía que al presionar Entrar en el panel de búsqueda expandido no se iniciara la búsqueda y requería que los usuarios hiciesen clic en el botón de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="a993e-700">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="a993e-701">Se ha corregido un problema que hacía que al ordenar los resultados por categorías, en un conjunto de resultados de búsqueda devuelto no se mostraran los colores de la categoría.</span><span class="sxs-lookup"><span data-stu-id="a993e-701">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="a993e-702">Se ha corregido un problema por el que la búsqueda no mostraba información sobre los usuarios cuando se había deshabilitado la opción "Mostrar fotografías de usuario cuando estén disponibles".</span><span class="sxs-lookup"><span data-stu-id="a993e-702">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="a993e-703">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a993e-703">PowerPoint</span></span>

- <span data-ttu-id="a993e-704">Este cambio corrige un error que podría causar que los archivos de PowerPoint que contienen emojis fallen al guardarlos.</span><span class="sxs-lookup"><span data-stu-id="a993e-704">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="a993e-705">Este cambio corrige un problema en el que es posible que no siempre se muestre el título del gráfico al representar un gráfico de Excel heredado incrustado como objeto OLE en PowerPoint o Word.</span><span class="sxs-lookup"><span data-stu-id="a993e-705">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="a993e-706">Se ha corregido un problema por el que al copiar texto de Excel en PowerPoint podía cambiar el formato.</span><span class="sxs-lookup"><span data-stu-id="a993e-706">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="a993e-707">Este cambio corrige un problema que provocaba que la búsqueda de caracteres especiales con "Buscar solo palabras completas" no siempre funcionase como se esperaba.</span><span class="sxs-lookup"><span data-stu-id="a993e-707">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="a993e-708">Proyecto</span><span class="sxs-lookup"><span data-stu-id="a993e-708">Project</span></span>

- <span data-ttu-id="a993e-709">Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.</span><span class="sxs-lookup"><span data-stu-id="a993e-709">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="a993e-710">Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="a993e-710">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="a993e-711">Se ha corregido un problema que hacía que el evento "ProjectBeforeTaskChange" de las aplicaciones de Visual Basic (VBA) no se activara cuando un usuario hacía clic en el botón "Desactivar" que se encuentra en la cinta de tareas en el grupo de programación.</span><span class="sxs-lookup"><span data-stu-id="a993e-711">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="a993e-712">Si establece los detalles de predecesor o sucesor desde una vista de tipo formulario, el evento de las aplicaciones de Visual Basic (VBA) ProjectBeforeTaskChange no siempre captura los cambios.</span><span class="sxs-lookup"><span data-stu-id="a993e-712">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="a993e-713">Por ejemplo, si ha eliminado una dependencia y ha hecho clic en Aceptar en el formulario, el evento no se ha desencadenado.</span><span class="sxs-lookup"><span data-stu-id="a993e-713">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="a993e-714">Este comportamiento se ha corregido.</span><span class="sxs-lookup"><span data-stu-id="a993e-714">This behavior has been fixed.</span></span>

- <span data-ttu-id="a993e-715">Se corrigió un problema por el que los valores más recientes del coste real del trabajo realizado (CRTR) no se mostraba después de realizar un cambio, como un cambio de fecha.</span><span class="sxs-lookup"><span data-stu-id="a993e-715">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="a993e-716">Se corrigió un problema por el que al abrir un proyecto con el menú Usados más recientemente se abría el archivo de proyecto con acceso de lectura y escritura.</span><span class="sxs-lookup"><span data-stu-id="a993e-716">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="a993e-717">Este cambio corrige un problema por el que si creaba una tarea manual con una fecha y hora de inicio (sin la duración), se mostraba con una hora incorrecta en la escala de tiempo.</span><span class="sxs-lookup"><span data-stu-id="a993e-717">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="a993e-718">Se corrigió un problema por el que la impresión de una escala de tiempo con el calendario Hijri saltaba un mes o lo duplicaba en la vista de impresión.</span><span class="sxs-lookup"><span data-stu-id="a993e-718">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="a993e-719">Este cambio resuelve un problema por el que trabajar en el Organizador de equipo con objetos de GDI podía provocar la sobreasignación de dichos objetos y crear condiciones de memoria insuficiente.</span><span class="sxs-lookup"><span data-stu-id="a993e-719">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="a993e-720">Se ha solucionado un problema por el que si se ejecuta "Lista de valores de campos personalizados GetItem" y no existe una tabla de búsqueda para el campo personalizado, se crea una tabla de búsqueda vacía aunque no debería existir.</span><span class="sxs-lookup"><span data-stu-id="a993e-720">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="a993e-721">Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se activa un evento ProjectBeforeTaskChange adicional.</span><span class="sxs-lookup"><span data-stu-id="a993e-721">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="a993e-722">Se corrigió un problema por el que el usuario no podía especificar el trabajo previsto con fases temporales al activar la configuración para proteger el trabajo real.</span><span class="sxs-lookup"><span data-stu-id="a993e-722">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="a993e-723">Word</span><span class="sxs-lookup"><span data-stu-id="a993e-723">Word</span></span>

- <span data-ttu-id="a993e-724">Este cambio corrige un problema que provoca que al colocar el cursor sobre una sugerencia no se resalte la tarjeta.</span><span class="sxs-lookup"><span data-stu-id="a993e-724">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="a993e-725">Este cambio corrige un problema con varias páginas seleccionadas en el menú Ver, donde el panel de comentarios podía mostrarse en blanco.</span><span class="sxs-lookup"><span data-stu-id="a993e-725">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="a993e-726">Se corrigió un problema por el que se había deshabilitado la función para publicar comentarios.</span><span class="sxs-lookup"><span data-stu-id="a993e-726">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="a993e-727">Este cambio corrige un problema que haría que el texto de las formas agrupadas desaparezca temporalmente al usar la herramienta Selección de lazo.</span><span class="sxs-lookup"><span data-stu-id="a993e-727">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="a993e-728">Este cambio corrige retrasos al procesar imágenes con información de protocolo mal formada o incorrecta.</span><span class="sxs-lookup"><span data-stu-id="a993e-728">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="a993e-729">Este cambio corrige un problema en el que es posible que no siempre se muestre el título del gráfico al representar un gráfico de Excel heredado incrustado como objeto OLE en PowerPoint o Word.</span><span class="sxs-lookup"><span data-stu-id="a993e-729">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="a993e-730">Este cambio resuelve un problema en el que el administrador de cuentas no enviaba mensajes, lo que provocaba un error en aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="a993e-730">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="a993e-731">Este cambio corrige un problema por el que, en la vista de dos páginas, al crear un comentario, el anclaje del comentario no siempre aparecía.</span><span class="sxs-lookup"><span data-stu-id="a993e-731">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="a993e-732">Se ha corregido un problema por el que al escribir o editar un comentario y usar Ctrl + A se seleccionaba texto en el lienzo en lugar de seleccionar texto en la tarjeta del comentario.</span><span class="sxs-lookup"><span data-stu-id="a993e-732">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="a993e-733">Se ha corregido un problema que hacía que si un párrafo con un estilo antecesor de un estilo estaba vinculado a una lista, se podía perder la numeración de la lista.</span><span class="sxs-lookup"><span data-stu-id="a993e-733">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="a993e-734">Este cambio corrige un problema en el que la tabla de contenido se actualizaba con estilos de título que no estaban presentes en el documento.</span><span class="sxs-lookup"><span data-stu-id="a993e-734">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="a993e-735">Se ha corregido un problema por el que la alineación de las palabras de un documento se puede codificar al intentar editar después de imprimir con la impresión rápida.</span><span class="sxs-lookup"><span data-stu-id="a993e-735">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="a993e-736">Se ha corregido un problema al combinar dos documentos en uno.</span><span class="sxs-lookup"><span data-stu-id="a993e-736">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="a993e-737">Se corrigió un problema por el que las firmas digitales guardadas en documentos de Word se eliminaban al enviar los documentos.</span><span class="sxs-lookup"><span data-stu-id="a993e-737">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="a993e-738">Se ha corregido un problema que hacía que el marcado de revisiones que impliquen ecuaciones ocasionase un error al guardar el archivo.</span><span class="sxs-lookup"><span data-stu-id="a993e-738">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-april-14"></a><span data-ttu-id="a993e-740">Versión 2003: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="a993e-740">Version 2003: April 14</span></span>
<span data-ttu-id="a993e-741">*Versión 2003 (compilación 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="a993e-741">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="a993e-742">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a993e-742">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

- <span data-ttu-id="a993e-744">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="a993e-744">Various bugs and performance fixes.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

## <a name="version-2003-april-09"></a><span data-ttu-id="a993e-746">Versión 2003: 09 de abril</span><span class="sxs-lookup"><span data-stu-id="a993e-746">Version 2003: April 09</span></span>
<span data-ttu-id="a993e-747">*Versión 2003 (compilación 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="a993e-747">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="a993e-749">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-749">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a993e-750">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-750">Excel</span></span>

- <span data-ttu-id="a993e-751">**Selector de contenido de M365 Premium:** de vida a sus documentos.</span><span class="sxs-lookup"><span data-stu-id="a993e-751">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a993e-752">Explore gratis miles de imágenes, iconos y adhesivos [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a993e-752">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="a993e-753">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-753">Outlook</span></span>

- <span data-ttu-id="a993e-754">**Selector de contenido de M365 Premium:** de vida a sus documentos.</span><span class="sxs-lookup"><span data-stu-id="a993e-754">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a993e-755">Explore gratis miles de imágenes, iconos y adhesivos [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a993e-755">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a993e-756">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a993e-756">PowerPoint</span></span>

- <span data-ttu-id="a993e-757">**Selector de contenido de M365 Premium:** de vida a sus documentos.</span><span class="sxs-lookup"><span data-stu-id="a993e-757">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a993e-758">Explore gratis miles de imágenes, iconos y adhesivos [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a993e-758">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="a993e-759">Word</span><span class="sxs-lookup"><span data-stu-id="a993e-759">Word</span></span>

- <span data-ttu-id="a993e-760">**Selector de contenido de M365 Premium:** de vida a sus documentos.</span><span class="sxs-lookup"><span data-stu-id="a993e-760">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a993e-761">Explore gratis miles de imágenes, iconos y adhesivos [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a993e-761">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO INICIAL)




[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO FINAL)

## <a name="version-2003-april-03"></a><span data-ttu-id="a993e-765">Versión 2003: 03 de abril</span><span class="sxs-lookup"><span data-stu-id="a993e-765">Version 2003: April 03</span></span>
<span data-ttu-id="a993e-766">*Versión 2003 (Compilación 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="a993e-766">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-768">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-768">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a993e-769">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-769">Excel</span></span>

- <span data-ttu-id="a993e-770">El uso de la Aplicación VBA.Evaluar no trabajaba para las funciones definidas por el usuario en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="a993e-770">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="a993e-771">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-771">Outlook</span></span>

- <span data-ttu-id="a993e-772">Abordó un problema que causó que los usuarios experimentaran ocasionalmente un choque al usar el botón "X" de su ratón.</span><span class="sxs-lookup"><span data-stu-id="a993e-772">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="a993e-773">Project</span><span class="sxs-lookup"><span data-stu-id="a993e-773">Project</span></span>

- <span data-ttu-id="a993e-774">Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se dispara un ProyectoAntesdeCambiarTareaEvento extra.</span><span class="sxs-lookup"><span data-stu-id="a993e-774">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="a993e-775">Word</span><span class="sxs-lookup"><span data-stu-id="a993e-775">Word</span></span>

- <span data-ttu-id="a993e-776">Abordó un problema que causó que los usuarios experimentaran ocasionalmente un choque al usar el botón "X" de su ratón.</span><span class="sxs-lookup"><span data-stu-id="a993e-776">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-march-31"></a><span data-ttu-id="a993e-778">Versión 2003: 31 de marzo</span><span class="sxs-lookup"><span data-stu-id="a993e-778">Version 2003: March 31</span></span>
<span data-ttu-id="a993e-779">*Versión 2003 (compilación 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="a993e-779">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="a993e-781">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-781">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="a993e-782">Access</span><span class="sxs-lookup"><span data-stu-id="a993e-782">Access</span></span>

- <span data-ttu-id="a993e-783">**Panel de tareas "Agregar tablas":** ¡Ya está disponible el acceso al nuevo panel de tareas "Agregar tablas"!</span><span class="sxs-lookup"><span data-stu-id="a993e-783">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="a993e-784">Esta característica le permite seleccionar y hacer selección múltiple de las tablas que desea agregar o quitar de forma sencilla en una ventana de consulta, sin tener que desplazarse hasta el cuadro de diálogo "Mostrar tablas" para las consultas y la vista de relación.</span><span class="sxs-lookup"><span data-stu-id="a993e-784">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="a993e-785">Esto también incluye una nueva pestaña "vínculos" para mostrar las tablas vinculadas, un cuadro de búsqueda para filtrar la lista actual, el comportamiento de "arrastrar y soltar", ¡y mucho más!</span><span class="sxs-lookup"><span data-stu-id="a993e-785">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-788">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-788">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="a993e-789">Project</span><span class="sxs-lookup"><span data-stu-id="a993e-789">Project</span></span>

- <span data-ttu-id="a993e-790"><span style="display:inline !important;">Se corrigió un problema por el que el usuario no podía especificar el trabajo previsto con fases temporales al activar la configuración para proteger el trabajo real.</span></span><span class="sxs-lookup"><span data-stu-id="a993e-790"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-march-25"></a><span data-ttu-id="a993e-792">Versión 2003: 25 de marzo</span><span class="sxs-lookup"><span data-stu-id="a993e-792">Version 2003: March 25</span></span>
<span data-ttu-id="a993e-793">*Versión 2003 (compilación 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="a993e-793">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="a993e-794">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="a993e-794">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="a993e-795">Versión 2003: 23 de marzo</span><span class="sxs-lookup"><span data-stu-id="a993e-795">Version 2003: March 23</span></span>
<span data-ttu-id="a993e-796">*Versión 2003 (compilación 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="a993e-796">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="a993e-797">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="a993e-797">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="a993e-798">Versión 2003: 21 de marzo</span><span class="sxs-lookup"><span data-stu-id="a993e-798">Version 2003: March 21</span></span>
<span data-ttu-id="a993e-799">*Versión 2003 (compilación 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="a993e-799">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="a993e-801">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-801">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a993e-802">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-802">Outlook</span></span>

- <span data-ttu-id="a993e-803">**Unirse a reuniones sin salir de la bandeja de entrada:** no es necesario cambiar al calendario para unirse a reuniones en línea.</span><span class="sxs-lookup"><span data-stu-id="a993e-803">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="a993e-804">Con el Calendario de Outlook anclado en el panel de tareas pendientes, únase a una reunión con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="a993e-804">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="a993e-805">**Actualización visual del calendario:** el año pasado, hemos incorporado una experiencia de correo actualizada y este año le toca al calendario tener una cara nueva.</span><span class="sxs-lookup"><span data-stu-id="a993e-805">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="a993e-806">Las actualizaciones son recientes pero son familiares, para que, como usuario de Outlook veterano, pueda empezar a ser más productivo en seguida.</span><span class="sxs-lookup"><span data-stu-id="a993e-806">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a993e-807">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a993e-807">PowerPoint</span></span>

- <span data-ttu-id="a993e-808">**Actualización de las diapositivas durante la presentación:** actualice diapositivas editadas por otros autores durante la presentación.</span><span class="sxs-lookup"><span data-stu-id="a993e-808">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

## <a name="version-2003-march-16"></a><span data-ttu-id="a993e-810">Versión 2003: 16 de marzo</span><span class="sxs-lookup"><span data-stu-id="a993e-810">Version 2003: March 16</span></span>
<span data-ttu-id="a993e-811">*Versión 2003 (compilación 12624,20224)*</span><span class="sxs-lookup"><span data-stu-id="a993e-811">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (NO QUITAR DETALLES DE CARACTERÍSTICAS CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="a993e-813">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-813">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a993e-814">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-814">Excel</span></span>

- <span data-ttu-id="a993e-815">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="a993e-815">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="a993e-816">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-816">Outlook</span></span>

- <span data-ttu-id="a993e-817">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="a993e-817">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a993e-818">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a993e-818">PowerPoint</span></span>

- <span data-ttu-id="a993e-819">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="a993e-819">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="a993e-820">Word</span><span class="sxs-lookup"><span data-stu-id="a993e-820">Word</span></span>

- <span data-ttu-id="a993e-821">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="a993e-821">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a993e-822">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="a993e-822">Office Suite</span></span>

- <span data-ttu-id="a993e-823">**Paneles con pestañas:** ahora puede cambiar entre varios paneles con la pestaña situada en la parte derecha de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="a993e-823">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="a993e-824">Esta interfaz de usuario solo será visible cuando haya dos o más paneles abiertos.</span><span class="sxs-lookup"><span data-stu-id="a993e-824">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-827">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-827">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a993e-828">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-828">Excel</span></span>

- <span data-ttu-id="a993e-829">Se abordó un problema donde los enlaces externos no se actualizan cuando se cierra el libro de fuentes.</span><span class="sxs-lookup"><span data-stu-id="a993e-829">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="a993e-830">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-830">Outlook</span></span>

- <span data-ttu-id="a993e-831">Se abordó un problema que causó que los usuarios vieran que el proceso de Outlook permanecía en el administrador de tareas después de salir.</span><span class="sxs-lookup"><span data-stu-id="a993e-831">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-march-10"></a><span data-ttu-id="a993e-833">Versión 2003: 10 de marzo</span><span class="sxs-lookup"><span data-stu-id="a993e-833">Version 2003: March 10</span></span>
<span data-ttu-id="a993e-834">*Versión 2003 (compilación 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="a993e-834">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="a993e-835">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a993e-835">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)
### <a name="feature-updates"></a><span data-ttu-id="a993e-837">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-837">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a993e-838">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-838">Excel</span></span>
- <span data-ttu-id="a993e-839">**Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados.</span><span class="sxs-lookup"><span data-stu-id="a993e-839">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="a993e-840">Más información</span><span class="sxs-lookup"><span data-stu-id="a993e-840">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="a993e-841">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a993e-841">PowerPoint</span></span>
- <span data-ttu-id="a993e-842">**Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados.</span><span class="sxs-lookup"><span data-stu-id="a993e-842">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="a993e-843">Más información</span><span class="sxs-lookup"><span data-stu-id="a993e-843">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="a993e-844">Word</span><span class="sxs-lookup"><span data-stu-id="a993e-844">Word</span></span>
- <span data-ttu-id="a993e-845">**Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados.</span><span class="sxs-lookup"><span data-stu-id="a993e-845">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="a993e-846">Más información</span><span class="sxs-lookup"><span data-stu-id="a993e-846">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="a993e-847">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-847">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a993e-848">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-848">Excel</span></span>

- <span data-ttu-id="a993e-849">Se ha corregido un problema estético en el que el botón "Aceptar" del cuadro de diálogo de Archivo \ Opciones se mostraba atenuado, pero la función no se veía afectada.</span><span class="sxs-lookup"><span data-stu-id="a993e-849">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="a993e-850">Se ha corregido un problema que los usuarios pueden haber experimentado al cambiar el nombre de las medidas de tabla dinámica.</span><span class="sxs-lookup"><span data-stu-id="a993e-850">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="a993e-851">Se ha corregido un problema en el que el texto de una segmentación de datos no se escalaba correctamente en la vista previa de impresión.</span><span class="sxs-lookup"><span data-stu-id="a993e-851">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="a993e-852">Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al usar una macro de VBA para borrar el contenido de un rango.</span><span class="sxs-lookup"><span data-stu-id="a993e-852">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="a993e-853">Se ha corregido un problema que provocaba que la interfaz de usuario parpadeara cuando un usuario ejecutaba una macro que interactuaba con la cinta de opciones.</span><span class="sxs-lookup"><span data-stu-id="a993e-853">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="a993e-854">Se ha corregido un problema por el que los archivos CSV se cargaban de forma incorrecta cuando la primera palabra del archivo estaba era TABLE.</span><span class="sxs-lookup"><span data-stu-id="a993e-854">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="a993e-855">Se ha corregido un problema por el que los usuarios pueden haber sufrido bloqueos al cambiar entre dos libros que tienen diferentes niveles de zoom.</span><span class="sxs-lookup"><span data-stu-id="a993e-855">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="a993e-856">Se ha solucionado un problema por el que las funciones CUBEVALUE a veces daban un resultado incorrecto.</span><span class="sxs-lookup"><span data-stu-id="a993e-856">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="a993e-857">Este cambio resuelve un error en tiempo de ejecución en el modelo de objetos y el potencial bloqueo de la aplicación (Excel o Word) cuando los complementos pedían elementos host en documentos y hojas de cálculo que contienen formas con bloqueos noSelect.</span><span class="sxs-lookup"><span data-stu-id="a993e-857">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="a993e-858">Corrige un problema que causaba que los usuarios de Outlook experimentaran un error al sincronizar la configuración.</span><span class="sxs-lookup"><span data-stu-id="a993e-858">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="a993e-859">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-859">Outlook</span></span>

- <span data-ttu-id="a993e-860">Se ha corregido un problema que hacía que la creación de una regla con Outlook Web Access no se almacenara en el servidor de Exchange y produjera un conflicto.</span><span class="sxs-lookup"><span data-stu-id="a993e-860">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="a993e-861">Corregido un problema que causaba que los usuarios de Outlook experimentaran un error al sincronizar la configuración.</span><span class="sxs-lookup"><span data-stu-id="a993e-861">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="a993e-862">Se ha corregido un problema por el que, en el modo oscuro de Outlook, no se mostraba la lista desplegable en el campo "De:".</span><span class="sxs-lookup"><span data-stu-id="a993e-862">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="a993e-863">Se ha corregido un problema que hizo que Outlook generara inesperadamente resultados de registro en algunas situaciones, incluso cuando el registro se desactivaba.</span><span class="sxs-lookup"><span data-stu-id="a993e-863">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="a993e-864">Se ha corregido un problema que provocaba que los usuarios no puedan abrir mensajes de la carpeta pública cuando Outlook se dejaba en marcha durante la noche.</span><span class="sxs-lookup"><span data-stu-id="a993e-864">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="a993e-865">Se ha corregido una condición en la que los botones "Permitir" y "Denegar" de la página de permisos se deshabilitan durante el flujo de trabajo de autenticación para agregar una cuenta de Gmail.</span><span class="sxs-lookup"><span data-stu-id="a993e-865">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="a993e-866">Se ha corregido un problema que provocaba que los usuarios perdieran el acceso al cuadro de diálogo de permisos de calendario &quot;Opciones de disponibilidad&quot;.</span><span class="sxs-lookup"><span data-stu-id="a993e-866">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="a993e-867">Se ha corregido un problema que podría provocar alerta: &quot;"Lo sentimos, tenemos problemas para abrir este elemento"&quot; al abrir algunas instancias de reuniones periódicas que se han enviado desde una zona horaria diferente.</span><span class="sxs-lookup"><span data-stu-id="a993e-867">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="a993e-868">Se ha corregido un problema que podría ocasionar que los usuarios no puedan abrir un archivo .msg después de arrastrar y soltar datos adjuntos desde el mensaje.</span><span class="sxs-lookup"><span data-stu-id="a993e-868">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="a993e-869">Se ha corregido un problema por el que, después de cargar un archivo adjunto desde Outlook a OneDrive, se podía cambiar el nombre de archivo si el nombre de los datos adjuntos contenía paréntesis.</span><span class="sxs-lookup"><span data-stu-id="a993e-869">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="a993e-870">Corregido un problema por el que los usuarios no pueden adjuntar un archivo a un mensaje de correo electrónico a través del explorador de archivos cuando el archivo se abre en otra aplicación.</span><span class="sxs-lookup"><span data-stu-id="a993e-870">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="a993e-871">Corregido un problema que causaba que los usuarios de Outlook experimentaran un error al sincronizar la configuración.</span><span class="sxs-lookup"><span data-stu-id="a993e-871">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a993e-872">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a993e-872">PowerPoint</span></span>

- <span data-ttu-id="a993e-873">Se ha corregido un problema por el que las miniaturas recomendadas parpadean al pasar el ratón por encima de las miniaturas.</span><span class="sxs-lookup"><span data-stu-id="a993e-873">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="a993e-874">En algunos casos, esto provocaba un bloqueo de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a993e-874">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="a993e-875">Se ha corregido un problema estético en el que el botón "Aceptar" del cuadro de diálogo de Archivo \ Opciones se mostraba atenuado, pero la función no se veía afectada.</span><span class="sxs-lookup"><span data-stu-id="a993e-875">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="a993e-876">Se ha corregido un problema que podría provocar un error al guardar un documento en PowerPoint o en Word con un gráfico de Excel.</span><span class="sxs-lookup"><span data-stu-id="a993e-876">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="a993e-877">Project</span><span class="sxs-lookup"><span data-stu-id="a993e-877">Project</span></span>

- <span data-ttu-id="a993e-878">Corregido un problema por el que el porcentaje completado de la tarea se cambiaba incorrectamente a un valor inferior al 100 % después de que se marcara como completada.</span><span class="sxs-lookup"><span data-stu-id="a993e-878">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="a993e-879">Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="a993e-879">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="a993e-880">Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.</span><span class="sxs-lookup"><span data-stu-id="a993e-880">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="a993e-881">Visio</span><span class="sxs-lookup"><span data-stu-id="a993e-881">Visio</span></span>

- <span data-ttu-id="a993e-882">El panel información de la forma mostraba en la sección Datos de formas detalles que no coincidían con los del archivo al abrirlo en la aplicación de escritorio de Visio.</span><span class="sxs-lookup"><span data-stu-id="a993e-882">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="a993e-883">Ya se ha corregido.</span><span class="sxs-lookup"><span data-stu-id="a993e-883">It has now been fixed.</span></span>

- <span data-ttu-id="a993e-884">Los mapas de bits importados en versiones anteriores a 2016 no se representaban por motivos de seguridad.</span><span class="sxs-lookup"><span data-stu-id="a993e-884">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="a993e-885">Este problema se ha corregido en la suscripción de Visio.</span><span class="sxs-lookup"><span data-stu-id="a993e-885">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="a993e-886">Word</span><span class="sxs-lookup"><span data-stu-id="a993e-886">Word</span></span>

- <span data-ttu-id="a993e-887">Se ha corregido un problema en el que las tarjetas con comentario no siempre se resaltan cuando se desplaza el puntero del mouse sobre la tarjeta del comentario.</span><span class="sxs-lookup"><span data-stu-id="a993e-887">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="a993e-888">Se ha corregido un problema por el que al ir a la tarjeta del comentario, el foco en el cuadro de edición del comentario no era visible.</span><span class="sxs-lookup"><span data-stu-id="a993e-888">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="a993e-889">Se ha corregido un problema estético en el que el botón "Aceptar" del cuadro de diálogo de Archivo \ Opciones se mostraba atenuado, pero la función no se veía afectada.</span><span class="sxs-lookup"><span data-stu-id="a993e-889">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="a993e-890">Durante una sesión de coautoría de documentos activos, agregar una imagen directamente en una tarjeta de comentario puede dar como resultado la adición de una etiqueta.</span><span class="sxs-lookup"><span data-stu-id="a993e-890">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="a993e-891">Este problema se ha corregido.</span><span class="sxs-lookup"><span data-stu-id="a993e-891">This issue has been fixed.</span></span>

- <span data-ttu-id="a993e-892">Si se inserta un control (como un control de contenido de texto) en una ecuación, al guardar y abrir el archivo se produce un error de contenido ilegible.</span><span class="sxs-lookup"><span data-stu-id="a993e-892">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="a993e-893">Se ha corregido un problema que hacía que no se pudiera guardar un archivo protegido con contraseña anteriormente en un almacenamiento en la nube.</span><span class="sxs-lookup"><span data-stu-id="a993e-893">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="a993e-894">Se ha corregido un problema con la característica Comparación para los documentos protegidos para la edición.</span><span class="sxs-lookup"><span data-stu-id="a993e-894">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="a993e-895">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="a993e-895">Office Suite</span></span>

- <span data-ttu-id="a993e-896">Al usar las propiedades Multichoice/Lookup/Managed-metadata con documentos de Word/Excel/PowerPoint y guardar en una biblioteca de documentos de SharePoint, estas propiedades se limitaban anteriormente a 255 caracteres.</span><span class="sxs-lookup"><span data-stu-id="a993e-896">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="a993e-897">Cuando estas propiedades superaban 255 caracteres, estos documentos no se podían guardar.</span><span class="sxs-lookup"><span data-stu-id="a993e-897">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="a993e-898">Con este cambio, este límite se ha aumentado a 2048 caracteres.</span><span class="sxs-lookup"><span data-stu-id="a993e-898">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="a993e-899">Se ha corregido un problema en Word/Excel/PowerPoint. Ahora, el nombre principal de usuario (UPN) ya no distingue entre mayúsculas y minúsculas, lo que provoca menos errores al trabajar con archivos en SharePoint.</span><span class="sxs-lookup"><span data-stu-id="a993e-899">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="a993e-900">Corregido un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.</span><span class="sxs-lookup"><span data-stu-id="a993e-900">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-march-05"></a><span data-ttu-id="a993e-902">Versión 2002: 05 de marzo</span><span class="sxs-lookup"><span data-stu-id="a993e-902">Version 2002: March 05</span></span>
<span data-ttu-id="a993e-903">*Versión 2002 (compilación 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="a993e-903">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="a993e-904">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="a993e-904">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="a993e-905">Versión 2002: 04 de marzo</span><span class="sxs-lookup"><span data-stu-id="a993e-905">Version 2002: March 04</span></span>
<span data-ttu-id="a993e-906">*Versión 2002 (compilación 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="a993e-906">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-908">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-908">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="a993e-909">Project</span><span class="sxs-lookup"><span data-stu-id="a993e-909">Project</span></span>
- <span data-ttu-id="a993e-910">Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.</span><span class="sxs-lookup"><span data-stu-id="a993e-910">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a993e-911">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="a993e-911">Office Suite</span></span>
- <span data-ttu-id="a993e-912">Corrige un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.</span><span class="sxs-lookup"><span data-stu-id="a993e-912">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-march-01"></a><span data-ttu-id="a993e-914">Versión 2002: 01 de marzo</span><span class="sxs-lookup"><span data-stu-id="a993e-914">Version 2002: March 01</span></span>
<span data-ttu-id="a993e-915">*Versión 2002 (compilación 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="a993e-915">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="a993e-916">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-916">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a993e-917">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-917">Outlook</span></span>

- <span data-ttu-id="a993e-918">Corrige un problema que provocaba que las aplicaciones de terceros no pudiesen enviar correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="a993e-918">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-february-24"></a><span data-ttu-id="a993e-920">Versión de 2002: 24 de febrero</span><span class="sxs-lookup"><span data-stu-id="a993e-920">Version 2002: February 24</span></span>
<span data-ttu-id="a993e-921">*Versión de 2002 (compilación 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="a993e-921">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="a993e-922">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="a993e-922">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="a993e-923">Versión de 2002: 22 de febrero</span><span class="sxs-lookup"><span data-stu-id="a993e-923">Version 2002: February 22</span></span>
<span data-ttu-id="a993e-924">*Versión de 2002 (compilación 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="a993e-924">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="a993e-925">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="a993e-925">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="a993e-926">Versión 2002: 21 de febrero</span><span class="sxs-lookup"><span data-stu-id="a993e-926">Version 2002: February 21</span></span>
<span data-ttu-id="a993e-927">*Versión 2002 (compilación 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="a993e-927">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="a993e-929">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-929">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="a993e-930">Access</span><span class="sxs-lookup"><span data-stu-id="a993e-930">Access</span></span>

- <span data-ttu-id="a993e-931">**Aumente su productividad con el Diseñador de consultas, la vista SQL y la ventana Relaciones:** haga clic con el botón derecho en una tabla para abrirla, diseñarla, cambiar su tamaño y ocultarla.</span><span class="sxs-lookup"><span data-stu-id="a993e-931">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="a993e-932">Buscar y reemplazar texto en la vista SQL.</span><span class="sxs-lookup"><span data-stu-id="a993e-932">Search and replace text in SQL View.</span></span> <span data-ttu-id="a993e-933">Seleccione múltiples tablas en la ventana Relaciones.</span><span class="sxs-lookup"><span data-stu-id="a993e-933">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="a993e-934">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-934">Outlook</span></span>

- <span data-ttu-id="a993e-935">**Nueva experiencia para redes WiFi cautivas:** ¿alguna vez se ha unido a una red WiFi que requiere una página web para iniciar sesión?</span><span class="sxs-lookup"><span data-stu-id="a993e-935">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="a993e-936">Outlook ahora lo detecta y le ayuda a estar conectado.</span><span class="sxs-lookup"><span data-stu-id="a993e-936">Outlook now detects this and helps you get connected.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-939">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-939">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a993e-940">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-940">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="a993e-941">Se ha corregido un problema por el que las funciones CUBEVALUE a veces daban un resultado incorrecto.&nbsp;<span style="display:inline !important;"></span></span><span class="sxs-lookup"><span data-stu-id="a993e-941">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;<span style="display:inline !important;"></span></span></span><br>


### <a name="outlook"></a><span data-ttu-id="a993e-942">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-942">Outlook</span></span>

- <span data-ttu-id="a993e-943">Corregido un tema que causó que las comas en el campo de ubicación de una reunión se convirtieran en punto y coma.</span><span class="sxs-lookup"><span data-stu-id="a993e-943">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>


- <span data-ttu-id="a993e-944">Corregido un problema que podría resultar en un choque al ver el mismo elemento en varias ventanas.</span><span class="sxs-lookup"><span data-stu-id="a993e-944">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>


- <span data-ttu-id="a993e-945">Corregido un problema que causó que Outlook sincronizara inesperadamente todo el correo, incluso cuando el deslizador de sincronización está configurado en un ajuste más pequeño.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="a993e-945">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span>


- <span data-ttu-id="a993e-946">Corregido un problema que causó que los usuarios con el Tema Negro vieran&quot;de&quot; el desplegable muestra un texto blanco sobre un fondo blanco.</span><span class="sxs-lookup"><span data-stu-id="a993e-946">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>


- <span data-ttu-id="a993e-947"><span style="display:inline !important;">Este cambio restaura la capacidad de ver sujetos de varias líneas en el encabezado del mensaje.</span></span><span class="sxs-lookup"><span data-stu-id="a993e-947"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br>



[//]: # (NO ELIMINE EL CONTENIDO FINAL DE LOS DETALLES )

## <a name="version-2002-february-18"></a><span data-ttu-id="a993e-949">Versión 2002: 18 de febrero</span><span class="sxs-lookup"><span data-stu-id="a993e-949">Version 2002: February 18</span></span>
<span data-ttu-id="a993e-950">*Versión 2002 (compilación 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="a993e-950">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="a993e-951">Versión 2002: 11 de febrero</span><span class="sxs-lookup"><span data-stu-id="a993e-951">Version 2002: February 11</span></span>
<span data-ttu-id="a993e-952">*Versión 2002 (compilación 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="a993e-952">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="a993e-953">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a993e-953">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="a993e-955">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="a993e-955">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a993e-956">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-956">Outlook</span></span>

- <span data-ttu-id="a993e-957">**Arrastre el correo electrónico a un grupo de tu propiedad:** Mueva y copie mensajes y conversaciones arrastrándolos desde su bandeja de entrada.</span><span class="sxs-lookup"><span data-stu-id="a993e-957">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="a993e-958">Los mensajes que arrastres serán compartidos con todos los miembros del grupo.</span><span class="sxs-lookup"><span data-stu-id="a993e-958">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="a993e-959">Word</span><span class="sxs-lookup"><span data-stu-id="a993e-959">Word</span></span>

- <span data-ttu-id="a993e-960">**Otros usuarios verán los cambios rápidamente**: las mejoras en la coautoría significan que los colaboradores podrán ver los cambios más rápido que nunca.</span><span class="sxs-lookup"><span data-stu-id="a993e-960">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a993e-961">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="a993e-961">Office Suite</span></span>

- <span data-ttu-id="a993e-962">**Iconos de la barra de estado más nítidos:** los iconos de la barra de estado ahora son más fáciles de ver.</span><span class="sxs-lookup"><span data-stu-id="a993e-962">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="a993e-965">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="a993e-965">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a993e-966">Access</span><span class="sxs-lookup"><span data-stu-id="a993e-966">Access</span></span>

- <span data-ttu-id="a993e-967">Las plantillas de Access ya no deberían causar errores en columnas de datos adjuntos en una base de datos.</span><span class="sxs-lookup"><span data-stu-id="a993e-967">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="a993e-968">Después de crear la instancia de una plantilla, ahora debería poder agregar un campo de datos adjuntos a la base de datos.</span><span class="sxs-lookup"><span data-stu-id="a993e-968">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="a993e-969">Esta actualización corrige un problema por el que al usar un objeto de grabación de ADODB</span><span class="sxs-lookup"><span data-stu-id="a993e-969">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="a993e-970">en el código de VB, se puede notificar un error incorrectamente.</span><span class="sxs-lookup"><span data-stu-id="a993e-970">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="a993e-971">Esta actualización corrige un problema que puede hacer que Microsoft Access no identifique una Columna de identidad en una tabla vinculada de SQL Server, lo que puede provocar que las filas aparezcan como eliminadas de forma incorrecta.</span><span class="sxs-lookup"><span data-stu-id="a993e-971">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="a993e-972">Excel</span><span class="sxs-lookup"><span data-stu-id="a993e-972">Excel</span></span>

- <span data-ttu-id="a993e-973">Se ha corregido un problema por el que los comandos de comentario en el menú contextual no aparecían.</span><span class="sxs-lookup"><span data-stu-id="a993e-973">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="a993e-974">Se ha corregido un problema que causaba que algunos usuarios experimentasen bloqueos al convertir texto en columnas con celdas que tienen una matriz derramada.</span><span class="sxs-lookup"><span data-stu-id="a993e-974">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="a993e-975">Se ha corregido un problema por el que Excel se bloquea al usar la opción Texto a columnas con matrices dinámicas.</span><span class="sxs-lookup"><span data-stu-id="a993e-975">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="a993e-976">Outlook</span><span class="sxs-lookup"><span data-stu-id="a993e-976">Outlook</span></span>

- <span data-ttu-id="a993e-977">Se ha corregido un problema en el que el desplazamiento en el calendario con la vista de mes no muestra eventos de calendario anteriores.</span><span class="sxs-lookup"><span data-stu-id="a993e-977">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="a993e-978">Las carpetas guardadas en "favoritos" en el panel de navegación izquierdo podían desaparecer de forma esporádica.</span><span class="sxs-lookup"><span data-stu-id="a993e-978">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="a993e-979">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.</span><span class="sxs-lookup"><span data-stu-id="a993e-979">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="a993e-980">Se ha corregido un problema que hacía que la opción deshabilitar el resaltado de elementos marcados no se pudiera respetar en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="a993e-980">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="a993e-981">Se ha corregido un problema que provocaba que los usuarios experimentaran un error al cancelar la configuración de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="a993e-981">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="a993e-982">Se ha corregido un problema por el que los mensajes de correo electrónico que expiraban en función de una directiva de retención mostraban dos etiquetas.</span><span class="sxs-lookup"><span data-stu-id="a993e-982">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="a993e-983">Una mostraba que el correo expiraba en un día y otra que expiraba en dos días.</span><span class="sxs-lookup"><span data-stu-id="a993e-983">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="a993e-984">Se ha corregido un problema que causaba que los usuarios sufrieran un error al visualizar más de 30 calendarios en un entorno Citrix.</span><span class="sxs-lookup"><span data-stu-id="a993e-984">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="a993e-985">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a993e-985">PowerPoint</span></span>

- <span data-ttu-id="a993e-986">Se ha corregido un problema por el que la entrada de lápiz no se procesaba por completo u se omitía al usarla en una animación de entrada de lápiz de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a993e-986">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="a993e-987">Se ha corregido un problema que provocaba que, después de cerrar un archivo, PowerPoint no lo quitara inmediatamente de la colección Presentaciones si había algún controlador de eventos en ejecución.</span><span class="sxs-lookup"><span data-stu-id="a993e-987">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="a993e-988">Por lo tanto, el número de presentaciones que informa el modelo de objetos es incorrecto y se evita el cierre de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a993e-988">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="a993e-989">Se ha corregido un problema con el marcador de resaltado: los textos blancos con un marcador oscuro se imprimen como negros en escala de grises.</span><span class="sxs-lookup"><span data-stu-id="a993e-989">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="a993e-990">Project</span><span class="sxs-lookup"><span data-stu-id="a993e-990">Project</span></span>

- <span data-ttu-id="a993e-991">Se ha corregido un problema por el que el 100 % de las tareas de tipo duración fija podían tener un cálculo del porcentaje incorrecto con menos del 100% completado.</span><span class="sxs-lookup"><span data-stu-id="a993e-991">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="a993e-992">Word</span><span class="sxs-lookup"><span data-stu-id="a993e-992">Word</span></span>

- <span data-ttu-id="a993e-993">Al actualizar y desplazarse por una tabla de contenido, es posible que se muestre un área gris en el documento.</span><span class="sxs-lookup"><span data-stu-id="a993e-993">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="a993e-994">Se ha corregido un problema por el que usar "Examinar" para guardar un archivo podía no funcionar si se escribió un comentario sin publicarlo y el usuario intentó guardar el archivo.</span><span class="sxs-lookup"><span data-stu-id="a993e-994">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="a993e-995">Se ha corregido un problema por el que al ir de una tarjeta de comentario a otra se podía mostrar el comentario seleccionado inicialmente con una selección resaltada.</span><span class="sxs-lookup"><span data-stu-id="a993e-995">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="a993e-996">Se ha corregido un problema por el que el formato de cursiva se perdía después de editar un comentario, ponerlo en cursiva y, después, publicarlo.</span><span class="sxs-lookup"><span data-stu-id="a993e-996">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="a993e-997">Se ha corregido un problema por el que la sugerencia de comentario no se veía en el modo lectura con el color de página invertido.</span><span class="sxs-lookup"><span data-stu-id="a993e-997">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="a993e-998">Se ha corregido un problema por el que si se trabajaba en coautoría en un documento, la versión de borrador de un comentario raíz podía no conservarse.</span><span class="sxs-lookup"><span data-stu-id="a993e-998">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="a993e-999">Con el Control de cambios habilitado y el panel de comentarios cerrado, Ctrl + Alt + M podía no funcionar para abrir el panel Comentarios.</span><span class="sxs-lookup"><span data-stu-id="a993e-999">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="a993e-1000">Corregido un problema al agregar una @mención en una tabla que podía generar el mensaje de error: "Una tabla de este documento está dañada".</span><span class="sxs-lookup"><span data-stu-id="a993e-1000">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="a993e-1001">Se ha corregido un problema por el que los comandos de comentario (Modificar comentario, Responder a comentario, Eliminar comentario, Resolver comentario) en el menú contextual de comentarios no se mostraban.</span><span class="sxs-lookup"><span data-stu-id="a993e-1001">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a993e-1002">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="a993e-1002">Office Suite</span></span>

- <span data-ttu-id="a993e-1003">Resuelto un problema que podía causar que el paquete de herramientas de corrección de Noruega Nynorsk (NN-no) no se instalara correctamente.</span><span class="sxs-lookup"><span data-stu-id="a993e-1003">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="a993e-1004">Este cambio resuelve problemas con adaptadores gráficos que aprovechan la GPU integrada de Intel.</span><span class="sxs-lookup"><span data-stu-id="a993e-1004">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

