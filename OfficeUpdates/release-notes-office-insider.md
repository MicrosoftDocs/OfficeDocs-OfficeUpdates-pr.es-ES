---
<span data-ttu-id="09c68-101">title: "Notas de la versión de Office Insiders" MS. Author: andrewmo Author: mikho Manager: andrewmo ms. Date: 2/15/2019 ms. Audience: Win32 Fast ms. topic: referencia ms. Service: o365-ProPlus-localization_priority: Critical ms. Collection: RelNotes_ProPlus Description: "proporciona una audiencia rápida de Insiders con la lista más reciente de nuevas características clave, correcciones o problemas conocidos</span><span class="sxs-lookup"><span data-stu-id="09c68-101">title: "Release Notes for Office Insiders" ms.author: andrewmo author: mikho manager: andrewmo ms.date: 2/15/2019 ms.audience: Win32 Fast ms.topic: reference ms.service: o365-proplus- localization_priority: Critical ms.collection: RelNotes_ProPlus description: "Provides Insiders Fast audience with the latest list of key new features, fixes or known issues</span></span>
---

# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="09c68-102">Notas de la versión para Office Insiders</span><span class="sxs-lookup"><span data-stu-id="09c68-102">Release Notes for Office Insiders</span></span>

<span data-ttu-id="09c68-p101">Este artículo contiene las notas de la versión para las versiones inSider de Word, Excel, PowerPoint, Outlook, Access y Project para el escritorio de Windows. Cada semana, resaltaremos las nuevas características interesantes, las correcciones importantes y cualquier problema importante que quiera conocer. Tenga en cuenta que a menudo implementamos características (y a veces incluso correcciones) en Insiders durante un período de tiempo. Esto nos permite garantizar que los elementos funcionan sin problemas antes de publicar la característica para una audiencia más amplia. Por lo tanto, si no ve algo que se describe a continuación, no se preocupe si lo consigue.</span><span class="sxs-lookup"><span data-stu-id="09c68-p101">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop. Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about. Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time. This allows us to ensure that things are working smoothly before releasing the feature to a wider audience. So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

## <a name="february-12-2019-version-1902-build-1133020014"></a><span data-ttu-id="09c68-108">Febrero de 12 2019 versión 1902 (compilación 11330,20014)</span><span class="sxs-lookup"><span data-stu-id="09c68-108">February 12 2019 Version 1902 (build 11330.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="09c68-109">Novedades:</span><span class="sxs-lookup"><span data-stu-id="09c68-109">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="09c68-110">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="09c68-110">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="09c68-111">Mejoras en la transición de transformación: transformación por nombre</span><span class="sxs-lookup"><span data-stu-id="09c68-111">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="09c68-112">Especificar las formas que desea transformar</span><span class="sxs-lookup"><span data-stu-id="09c68-112">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="09c68-113">Introducción:</span><span class="sxs-lookup"><span data-stu-id="09c68-113">Getting Started:</span></span>

- <span data-ttu-id="09c68-114">Para que transformación trate dos objetos como el mismo objeto, el usuario puede cambiar el nombre de las formas mediante el panel de selección.</span><span class="sxs-lookup"><span data-stu-id="09c68-114">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="09c68-p102">El nombre debe ir precedido de "!!". (dos signos de exclamación) para que transformación la use para invalidar nuestro comportamiento de coincidencia predeterminado, por ejemplo, "!! Denomina</span><span class="sxs-lookup"><span data-stu-id="09c68-p102">The name must be prefaced with “!!” (two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="09c68-p103">Los usuarios pueden seguir cambiando el nombre de las formas con cualquier nombre que no comience por "!!" sin preocuparse de que cambie la forma en que funciona transformación</span><span class="sxs-lookup"><span data-stu-id="09c68-p103">Users can continue to rename shapes with any name that doesn’t start with “!!” without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="09c68-119">Escenarios para probar:</span><span class="sxs-lookup"><span data-stu-id="09c68-119">Scenarios to Try:</span></span>

- <span data-ttu-id="09c68-120">Insertar una forma en una diapositiva; a continuación, digamos rectángulo</span><span class="sxs-lookup"><span data-stu-id="09c68-120">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="09c68-121">Crear una nueva diapositiva</span><span class="sxs-lookup"><span data-stu-id="09c68-121">Create a new slide</span></span>
- <span data-ttu-id="09c68-122">Insertar una forma diferente en la 2ª diapositiva, digamos triángulo</span><span class="sxs-lookup"><span data-stu-id="09c68-122">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="09c68-123">Abra SelectionPane, cambie el nombre del rectángulo en la diapositiva 1 a "!! Shape "y cambie el nombre del triángulo de la diapositiva 2 por"!! cambiar</span><span class="sxs-lookup"><span data-stu-id="09c68-123">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="09c68-124">Aplicar transformación en la 2ª diapositiva</span><span class="sxs-lookup"><span data-stu-id="09c68-124">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="09c68-125">Mejoras en la transición de transformación: SmartArt</span><span class="sxs-lookup"><span data-stu-id="09c68-125">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="09c68-126">Transformación de SmartArt con transiciones más suaves</span><span class="sxs-lookup"><span data-stu-id="09c68-126">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="09c68-127">Introducción:</span><span class="sxs-lookup"><span data-stu-id="09c68-127">Getting Started:</span></span>

<span data-ttu-id="09c68-128">Use Morph de la misma manera que lo haría con SmartArt.</span><span class="sxs-lookup"><span data-stu-id="09c68-128">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="09c68-129">Escenarios para probar:</span><span class="sxs-lookup"><span data-stu-id="09c68-129">Scenarios to Try:</span></span>

- <span data-ttu-id="09c68-130">Insertar un SmartArt en una diapositiva</span><span class="sxs-lookup"><span data-stu-id="09c68-130">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="09c68-131">Duplicar la diapositiva</span><span class="sxs-lookup"><span data-stu-id="09c68-131">Duplicate the Slide</span></span>
- <span data-ttu-id="09c68-132">Cambiar el tamaño, cambiar o mover el SmartArt en la diapositiva duplicada</span><span class="sxs-lookup"><span data-stu-id="09c68-132">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="09c68-133">Aplicar transformación en la diapositiva duplicada</span><span class="sxs-lookup"><span data-stu-id="09c68-133">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="09c68-134">Mejoras en la transición de transformación: tablas</span><span class="sxs-lookup"><span data-stu-id="09c68-134">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="09c68-135">Tablas de transformación con transiciones más suaves</span><span class="sxs-lookup"><span data-stu-id="09c68-135">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="09c68-136">Introducción:</span><span class="sxs-lookup"><span data-stu-id="09c68-136">Getting Started:</span></span>
<span data-ttu-id="09c68-137">Use Morph de la misma manera que lo haría con tablas</span><span class="sxs-lookup"><span data-stu-id="09c68-137">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="09c68-138">Escenarios para probar:</span><span class="sxs-lookup"><span data-stu-id="09c68-138">Scenarios to Try:</span></span>

- <span data-ttu-id="09c68-139">Insertar una tabla en una diapositiva</span><span class="sxs-lookup"><span data-stu-id="09c68-139">Insert a Table in a slide</span></span>
- <span data-ttu-id="09c68-140">Duplicar la diapositiva</span><span class="sxs-lookup"><span data-stu-id="09c68-140">Duplicate the slide</span></span>
- <span data-ttu-id="09c68-141">Cambiar el tamaño, cambiar o mover la tabla en la diapositiva duplicada</span><span class="sxs-lookup"><span data-stu-id="09c68-141">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="09c68-142">Aplicar transformación en la diapositiva duplicada</span><span class="sxs-lookup"><span data-stu-id="09c68-142">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="09c68-143">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span><span class="sxs-lookup"><span data-stu-id="09c68-143">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="09c68-144">Cambiar de cuenta sin problemas</span><span class="sxs-lookup"><span data-stu-id="09c68-144">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="09c68-p104">El nuevo administrador de cuentas muestra todas sus cuentas personales y laborales en un solo punto y le permite cambiar de un control a otro. Esta experiencia actualizada indica cómo ha iniciado sesión y ahora puede alternar entre las cuentas de trabajo y personales sin tener que cerrar sesión primero o trabajar con cuadros de diálogo complejos.</span><span class="sxs-lookup"><span data-stu-id="09c68-p104">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them. This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>



#### <a name="scenarios-to-try"></a><span data-ttu-id="09c68-147">Escenarios para probar:</span><span class="sxs-lookup"><span data-stu-id="09c68-147">Scenarios to Try:</span></span>
- <span data-ttu-id="09c68-148">Cambiar entre cuentas</span><span class="sxs-lookup"><span data-stu-id="09c68-148">Switch between accounts</span></span>
- <span data-ttu-id="09c68-149">Agregar una cuenta nueva [Nota: es posible que quiera ir primero a archivo | Account | Servicios conectados y quitar cualquier servicio personal conectado a las cuentas de trabajo o viceversa]</span><span class="sxs-lookup"><span data-stu-id="09c68-149">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="09c68-150">Cerrar sesión en una cuenta</span><span class="sxs-lookup"><span data-stu-id="09c68-150">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="09c68-151">Revisiones más importantes:</span><span class="sxs-lookup"><span data-stu-id="09c68-151">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="09c68-152">Word</span><span class="sxs-lookup"><span data-stu-id="09c68-152">Word</span></span> 
- <span data-ttu-id="09c68-153">Se ha corregido un problema con la vista previa del contexto para las tablas &</span><span class="sxs-lookup"><span data-stu-id="09c68-153">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="09c68-154">Excel</span><span class="sxs-lookup"><span data-stu-id="09c68-154">Excel</span></span>
- <span data-ttu-id="09c68-155">Se ha corregido un problema por el que el texto en el campo de búsqueda Autofiltro está en blanco en negro</span><span class="sxs-lookup"><span data-stu-id="09c68-155">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="09c68-156">Hemos corregido un problema con la interfaz de usuario de consentimiento con el nuevo complemento de Office</span><span class="sxs-lookup"><span data-stu-id="09c68-156">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="09c68-157">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="09c68-157">PowerPoint</span></span>
- <span data-ttu-id="09c68-158">Se ha corregido un problema con la ampliación automática de la pantalla al presentar presentaciones en equipos portátiles o tabletas.</span><span class="sxs-lookup"><span data-stu-id="09c68-158">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="09c68-159">Outlook</span><span class="sxs-lookup"><span data-stu-id="09c68-159">Outlook</span></span>
- <span data-ttu-id="09c68-160">Se ha corregido un problema con la presentación del botón Enviar a OneNote</span><span class="sxs-lookup"><span data-stu-id="09c68-160">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="09c68-161">Acceder</span><span class="sxs-lookup"><span data-stu-id="09c68-161">Access</span></span>
- <span data-ttu-id="09c68-162">Varias correcciones de rendimiento y estabilidad</span><span class="sxs-lookup"><span data-stu-id="09c68-162">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="09c68-163">Project</span><span class="sxs-lookup"><span data-stu-id="09c68-163">Project</span></span>
- <span data-ttu-id="09c68-164">Varias correcciones de rendimiento y estabilidad</span><span class="sxs-lookup"><span data-stu-id="09c68-164">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-9-2019-version-1902-build-1133020014"></a><span data-ttu-id="09c68-165">Febrero de 9 2019 versión 1902 (compilación 11330,20014)</span><span class="sxs-lookup"><span data-stu-id="09c68-165">February 9 2019 Version 1902 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="09c68-166">Revisiones más importantes:</span><span class="sxs-lookup"><span data-stu-id="09c68-166">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="09c68-167">Word</span><span class="sxs-lookup"><span data-stu-id="09c68-167">Word</span></span> 
- <span data-ttu-id="09c68-168">Se ha corregido un problema por el que algunos estilos personalizados no se podían aplicar a Word online</span><span class="sxs-lookup"><span data-stu-id="09c68-168">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="09c68-169">Hemos corregido problemas de vista previa de contexto con objetos enriquecidos en Word</span><span class="sxs-lookup"><span data-stu-id="09c68-169">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="09c68-170">Se ha corregido un problema que provocaba que al pegar las listas se bloqueara Word.</span><span class="sxs-lookup"><span data-stu-id="09c68-170">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="09c68-171">Excel</span><span class="sxs-lookup"><span data-stu-id="09c68-171">Excel</span></span>
- <span data-ttu-id="09c68-172">Se ha corregido un problema por el que los espacios agregados después de que ya no se mostraban los formatos de número cuando no hay ningún símbolo de moneda</span><span class="sxs-lookup"><span data-stu-id="09c68-172">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="09c68-173">Se ha corregido un problema con detección automática de existencias</span><span class="sxs-lookup"><span data-stu-id="09c68-173">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="09c68-174">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="09c68-174">PowerPoint</span></span>
- <span data-ttu-id="09c68-175">Varias correcciones de rendimiento y estabilidad</span><span class="sxs-lookup"><span data-stu-id="09c68-175">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="09c68-176">Outlook</span><span class="sxs-lookup"><span data-stu-id="09c68-176">Outlook</span></span>
- <span data-ttu-id="09c68-177">Varias correcciones de rendimiento y estabilidad</span><span class="sxs-lookup"><span data-stu-id="09c68-177">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="09c68-178">Acceder</span><span class="sxs-lookup"><span data-stu-id="09c68-178">Access</span></span>
- <span data-ttu-id="09c68-179">Varias correcciones de rendimiento y estabilidad</span><span class="sxs-lookup"><span data-stu-id="09c68-179">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="09c68-180">Project</span><span class="sxs-lookup"><span data-stu-id="09c68-180">Project</span></span>
- <span data-ttu-id="09c68-181">Varias correcciones de rendimiento y estabilidad</span><span class="sxs-lookup"><span data-stu-id="09c68-181">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="january-30-2019-version-1902-build-1132620000"></a><span data-ttu-id="09c68-182">30 de enero de 2019 versión 1902 (compilación 11326,20000)</span><span class="sxs-lookup"><span data-stu-id="09c68-182">January 30, 2019 Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="09c68-183">Revisiones más importantes</span><span class="sxs-lookup"><span data-stu-id="09c68-183">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="09c68-184">Word</span><span class="sxs-lookup"><span data-stu-id="09c68-184">Word</span></span> 
- <span data-ttu-id="09c68-185">Se ha corregido un problema con el cambio de tamaño de las celdas en una tabla de Excel incrustada</span><span class="sxs-lookup"><span data-stu-id="09c68-185">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="09c68-186">Se ha corregido un problema con copiar o pegar formas en un lienzo de dibujo.</span><span class="sxs-lookup"><span data-stu-id="09c68-186">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="09c68-187">Excel</span><span class="sxs-lookup"><span data-stu-id="09c68-187">Excel</span></span>
- <span data-ttu-id="09c68-188">Se ha corregido un problema al abrir archivos desde Excel Web App</span><span class="sxs-lookup"><span data-stu-id="09c68-188">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="09c68-189">Se ha corregido un problema por el que al guardar un archivo CSV como. Se produjo un error en XLSX debido al tamaño del nombre de archivo</span><span class="sxs-lookup"><span data-stu-id="09c68-189">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="09c68-190">El menú contextual se ha corregido para mostrar las opciones del menú contextual</span><span class="sxs-lookup"><span data-stu-id="09c68-190">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="09c68-191">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="09c68-191">PowerPoint</span></span>
- <span data-ttu-id="09c68-192">Hemos corregido un emitido donde los usuarios no pudieron usar el método abreviado de teclado Ctrl + Alt + 7/Ctrl + Alt + 8 para escribir corchetes.</span><span class="sxs-lookup"><span data-stu-id="09c68-192">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="09c68-193">Se ha corregido un problema por el que, al insertar un vídeo local en el PPT, se reduciría el espacio en disco de la unidad C</span><span class="sxs-lookup"><span data-stu-id="09c68-193">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="09c68-194">Hemos corregido el botón publicar en Microsoft Stream que no se mostraba a algunos usuarios</span><span class="sxs-lookup"><span data-stu-id="09c68-194">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="09c68-195">Outlook</span><span class="sxs-lookup"><span data-stu-id="09c68-195">Outlook</span></span>
- <span data-ttu-id="09c68-196">Se ha corregido un problema que provocaba que la vista de tareas del calendario no mostrara correctamente el asunto de la tarea</span><span class="sxs-lookup"><span data-stu-id="09c68-196">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="09c68-197">Acceder</span><span class="sxs-lookup"><span data-stu-id="09c68-197">Access</span></span>
- <span data-ttu-id="09c68-198">Se ha corregido un problema de escalamiento con los gráficos</span><span class="sxs-lookup"><span data-stu-id="09c68-198">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="09c68-199">Project</span><span class="sxs-lookup"><span data-stu-id="09c68-199">Project</span></span>
- <span data-ttu-id="09c68-200">Varias correcciones de rendimiento y estabilidad</span><span class="sxs-lookup"><span data-stu-id="09c68-200">Various performance and stability fixes</span></span>
