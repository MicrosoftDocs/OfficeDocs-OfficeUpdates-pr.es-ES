---
title: Notas de la versión para las versiones de canal empresarial semestral (vista previa) en 2020
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Proporciona a los profesionales de TI las notas de la versión para las versiones del canal semestral (dirigido) de Aplicaciones de Microsoft 365 en 2020.
ms.openlocfilehash: ea0bcf4a30146c52bb45fef6361d490580b64739
ms.sourcegitcommit: c7f7982f4d2d0d8db4fc4fbf961b79a03bc8b36e
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 12/08/2020
ms.locfileid: "49601615"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview-releases-in-2020"></a><span data-ttu-id="6f0a7-103">Notas de la versión para las versiones de canal empresarial semestral (vista previa) en 2020</span><span class="sxs-lookup"><span data-stu-id="6f0a7-103">Release notes for Semi-Annual Enterprise Channel (Preview) releases in 2020</span></span>

<span data-ttu-id="6f0a7-104">Estas notas de la versión proporcionan información sobre las nuevas características y las actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones de canal empresarial semestral (vista previa) en 2020 para las Aplicaciones de Microsoft 365 para empresas, las Aplicaciones de Microsoft 365 para negocios y las versiones de suscripción de las aplicaciones de escritorio de Project y Visio.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="6f0a7-105">Estamos realizando algunos cambios en los canales de actualización de las Aplicaciones de Microsoft 365, incluida la adición de un nuevo canal de actualización (canal empresarial mensual) y el cambio de los nombres de los canales de actualización existentes.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="6f0a7-106">[Lea este artículo](https://go.microsoft.com/fwlink/p/?linkid=2127441) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>


## <a name="version-2008-december-08"></a><span data-ttu-id="6f0a7-107">Versión 2008: 08 de diciembre</span><span class="sxs-lookup"><span data-stu-id="6f0a7-107">Version 2008: December 08</span></span>
<span data-ttu-id="6f0a7-108">*Versión 2008 (Compilación 13127.20910)*</span><span class="sxs-lookup"><span data-stu-id="6f0a7-108">*Version 2008 (Build 13127.20910)*</span></span>

<span data-ttu-id="6f0a7-109">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6f0a7-111">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6f0a7-111">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="6f0a7-112">Access</span><span class="sxs-lookup"><span data-stu-id="6f0a7-112">Access</span></span>

- <span data-ttu-id="6f0a7-113">Se ha corregido un problema de error al intentar usar el generador de DSN de ODBC</span><span class="sxs-lookup"><span data-stu-id="6f0a7-113">We fixed an error issue when trying to use ODBC DSN builder</span></span>


### <a name="excel"></a><span data-ttu-id="6f0a7-114">Excel</span><span class="sxs-lookup"><span data-stu-id="6f0a7-114">Excel</span></span>

- <span data-ttu-id="6f0a7-115">Se ha corregido un problema que provocaba que las tablas dinámicas no se pudieran editar y los libros no se pudieran guardar si se exportaban desde el plan de Project.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-115">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="6f0a7-116">Se ha corregido un problema que provocaba que, en algunos casos, aparecieran varias barras de mensajes al abrir un archivo en modo de solo lectura.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-116">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="6f0a7-117">Se ha corregido un problema que provocaba que los subtotales de esquema pudieran dejar de funcionar cuando había muchos valores de encabezado de columna duplicados.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-117">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="6f0a7-118">Se ha corregido un problema que provocaba que Excel dejara de funcionar cuando había una actualización del objeto de directiva de grupo (por ejemplo, mediante la actualización de la directiva de grupo remota) durante el recálculo multiproceso.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-118">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="6f0a7-119">Se ha corregido un problema que provocaba que Excel dejara de funcionar cuando los usuarios utilizaban la función subtotal en más de 255 columnas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-119">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="6f0a7-120">Interletraje de texto mejorado en PowerPoint cuando se copia contenido de Excel y se pega en PowerPoint con la opción Insertar.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-120">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="6f0a7-121">Se ha corregido un problema que impedía cambiar entre la vista previa de la tabla y el editor de consultas en PowerPivot.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-121">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="6f0a7-122">Se ha corregido un problema que provocaba que el usuario no pudiera abrir el archivo atomsvc (UTF8+BOM) directamente desde SharePoint.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-122">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="6f0a7-123">Se ha corregido un problema con Power Pivot. Ahora reconoce correctamente el delimitador de tabulaciones.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-123">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="outlook"></a><span data-ttu-id="6f0a7-124">Outlook</span><span class="sxs-lookup"><span data-stu-id="6f0a7-124">Outlook</span></span>

- <span data-ttu-id="6f0a7-125">Se ha corregido un problema que provocaba que el campo "Para:" estuviera vacío al enviar un informe de estado en una tarea.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-125">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="6f0a7-126">Se ha corregido un problema que provocaba que se interrumpiera el evento MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-126">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="6f0a7-127">Se ha corregido un problema que provocaba que algunos usuarios experimentaran el cierre inesperado de la aplicación Outlook al enviar correo desde aplicaciones diferentes de Outlook.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-127">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="6f0a7-128">Se ha corregido un problema que provocaba que los usuarios experimentaran un rendimiento degradado al mover varios elementos de correo entre carpetas en el modo en línea.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-128">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="6f0a7-129">Se ha agregado una clave de registro que permite a los clientes deshabilitar la inclusión de hora de archivo para los datos adjuntos en las operaciones de IDataObject (es decir, arrastrar y soltar, portapapeles).</span><span class="sxs-lookup"><span data-stu-id="6f0a7-129">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="6f0a7-130">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = horas de archivo están excluidas  1 = (determinado) horas de archivo están incluidas</span><span class="sxs-lookup"><span data-stu-id="6f0a7-130">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="6f0a7-131">Se ha corregido un problema que provocaba que las imágenes en línea desaparecieran al responder a un mensaje con una etiqueta de protección de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-131">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="6f0a7-132">Se ha corregido un problema que provocaba que el nombre de usuario se mostrara como un número de teléfono al enviar un correo de voz protegido de Azure, lo que provocaba que los usuarios de escritorio de Outlook no puedan abrir correos de voz de usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-132">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="6f0a7-133">Se ha corregido un problema que provocaba que, al configurar OME, se agregaban datos adjuntos extraños en el elemento de correo que obligaban a Outlook a cifrar el mensaje aunque la opción DecryptAttachmentsForEncryptOnly estuviera configurada en el lado del servicio.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-133">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="6f0a7-134">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6f0a7-134">PowerPoint</span></span>

- <span data-ttu-id="6f0a7-135">Se ha corregido un problema que provocaba que el gráfico de Excel vinculado cambiara incorrectamente a la hoja de Excel cuando el usuario cambiaba la ruta de origen a la carpeta de OneDrive local.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-135">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="6f0a7-136">Se ha corregido un problema que provocaba que la característica "Bienvenido de nuevo.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-136">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="6f0a7-137">Retomar el trabajo donde lo dejó en la oficina" no funcionara en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-137">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


### <a name="visio"></a><span data-ttu-id="6f0a7-138">Visio</span><span class="sxs-lookup"><span data-stu-id="6f0a7-138">Visio</span></span>

- <span data-ttu-id="6f0a7-139">Se ha corregido un problema que provocaba que los usuarios pudieran crear líneas rectas con conectores en Visio para Office 365, tanto para las galerías personalizadas de símbolos de Visio como para las plantillas predefinidas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-139">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="6f0a7-140">Word</span><span class="sxs-lookup"><span data-stu-id="6f0a7-140">Word</span></span>

- <span data-ttu-id="6f0a7-141">Se corrigió un problema que provocaba que los vínculos largos no se ajustaran al guardar un documento en formato HTML.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-141">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="6f0a7-142">Se ha corregido un problema que provocaba que, si se respondía a un comentario primario que tenía extensiones desconocidas en una lista de extensiones, la respuesta obtuviera esas mismas extensiones.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-142">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="6f0a7-143">Se ha corregido un problema con Outlook al establecer un mensaje en No reenviar</span><span class="sxs-lookup"><span data-stu-id="6f0a7-143">We fixed an issue with Outlook with message set to Do not forward.</span></span>


### <a name="office-suite"></a><span data-ttu-id="6f0a7-144">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6f0a7-144">Office Suite</span></span>

- <span data-ttu-id="6f0a7-145">Soluciona un problema que impedía que los usuarios importaran listas de SPO cuando se deshabilitaba ADAL.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-145">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-november-10"></a><span data-ttu-id="6f0a7-147">Versión 2008: 10 de julio</span><span class="sxs-lookup"><span data-stu-id="6f0a7-147">Version 2008: November 10</span></span>
<span data-ttu-id="6f0a7-148">*La versión prevista es la versión 2008 (compilación 13127.20760).*</span><span class="sxs-lookup"><span data-stu-id="6f0a7-148">*Version 2008 (Build 13127.20760)*</span></span>

<span data-ttu-id="6f0a7-149">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-149">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6f0a7-151">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6f0a7-151">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="6f0a7-152">Excel</span><span class="sxs-lookup"><span data-stu-id="6f0a7-152">Excel</span></span>

- <span data-ttu-id="6f0a7-153">Se ha corregido un problema por el que algunas funciones podían tener un resultado incorrecto después de cargar un libro.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-153">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="6f0a7-154">Se ha corregido un problema relacionado con las referencias de complemento de XLAM y los rangos con nombre que cerraba la aplicación de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-154">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="6f0a7-155">Se ha corregido un problema por el que, al usar una macro para establecer la propiedad FormulaR1C1 para un rango, las referencias de celda eran incorrectas si una hoja de gráfico era la hoja activa.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-155">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="6f0a7-156">Se ha corregido un problema por el que Excel indicaba por error que se había quedado sin recursos al intentar calcular una o varias fórmulas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-156">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="6f0a7-157">Se ha corregido un problema que aparecía cuando se configuraba el idioma de Office en español. Este problema provocaba que las listas de validación de datos puedan no mostrar todos los elementos de la lista.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-157">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="6f0a7-158">Se ha corregido un problema que podía producir un bloqueo al actualizar las tablas dinámicas de OLAP.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-158">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>

### <a name="outlook"></a><span data-ttu-id="6f0a7-159">Outlook</span><span class="sxs-lookup"><span data-stu-id="6f0a7-159">Outlook</span></span>

- <span data-ttu-id="6f0a7-160">Se ha corregido un problema por el que los usuarios ahora pueden deshabilitar IRM (Information Rights Management) para Outlook sin tener que deshabilitarlo para el resto de las aplicaciones de Office.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-160">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="6f0a7-161">Se ha corregido un problema que provocaba que los usuarios no pudieran conceder permisos de editor a los delegados.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-161">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="6f0a7-162">Se ha corregido un problema que provocaba que la aplicación finalizara de forma abrupta cuando el cliente seleccionaba un resultado de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-162">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="6f0a7-163">Se ha corregido un problema que provocaba que las búsquedas en calendarios de Grupo no dieran resultados.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-163">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="6f0a7-164">Corregido un problema que causaba que los delegados sufrieran errores intermitentemente al abrir carpetas compartidas en otro buzón.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-164">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="6f0a7-165">Corregido un problema que causaba que se enviaran algunos mensajes de correo electrónico generados automáticamente con el cuerpo en blanco cuando la línea del asunto estaba también en blanco.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-165">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="6f0a7-166">Se ha corregido un problema que provocaba que los encabezados de mensajes en chino fueran ilegibles al responder o reenviar.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-166">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>

- <span data-ttu-id="6f0a7-167">Se ha corregido un problema por el que las experiencias opcionales conectadas bloqueaban la carga de los complementos web.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-167">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <br /><span data-ttu-id="6f0a7-168">Ver detalles en la [entrada de blog](https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-168">See details in [blog post](https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span></span>


### <a name="powerpoint"></a><span data-ttu-id="6f0a7-169">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6f0a7-169">PowerPoint</span></span>

- <span data-ttu-id="6f0a7-170">Se ha corregido un problema en el que el complemento de contenido de formularios no se reproducía después de la inserción hasta que el usuario hiciera clic en otra diapositiva para hacer que aparezca.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-170">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


### <a name="office-suite"></a><span data-ttu-id="6f0a7-171">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6f0a7-171">Office Suite</span></span>

- <span data-ttu-id="6f0a7-172">Se ha atendido un problema para los clientes comerciales que usan el System Center Configuration Manager u otras herramientas de administración para Office Update mediante la prevención de pérdida de datos del punto de conexión de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-172">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>

- <span data-ttu-id="6f0a7-173">Corrección de un problema por el que no funcionaba la API de mensajería para los complementos de Office.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-173">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>



[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2008-october-13"></a><span data-ttu-id="6f0a7-175">Versión 2008: 13 de octubre</span><span class="sxs-lookup"><span data-stu-id="6f0a7-175">Version 2008: October 13</span></span>
<span data-ttu-id="6f0a7-176">*Versión 2008 (compilación 13127.20638)*</span><span class="sxs-lookup"><span data-stu-id="6f0a7-176">*Version 2008 (Build 13127.20638)*</span></span>

<span data-ttu-id="6f0a7-177">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-177">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6f0a7-179">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6f0a7-179">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6f0a7-180">Excel</span><span class="sxs-lookup"><span data-stu-id="6f0a7-180">Excel</span></span>

- <span data-ttu-id="6f0a7-181">Se ha corregido un error con las API de PivotDateFilter en el que las condiciones de filtro 'Antes' y 'Después' se revertían.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-181">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="6f0a7-182">Se corrigió un problema por el cual los usuarios no podían modificar un filtro de tabla dinámica porque estaba configurado en un valor que ya no estaba presente en una base de datos de Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-182">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="6f0a7-183">Se ha corregido un problema que provocaba que Excel se bloqueara al usar el Análisis rápido después de inmovilizar la fila superior de la hoja.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-183">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="6f0a7-184">Se ha corregido un problema que podía producir una advertencia acerca de un libro dañado si contenía fórmulas que usan SI.ND.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-184">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="6f0a7-185">Outlook</span><span class="sxs-lookup"><span data-stu-id="6f0a7-185">Outlook</span></span>

- <span data-ttu-id="6f0a7-186">Corrige un problema que provocaba que los usuarios no pudieran cerrar los calendarios compartidos haciendo clic en la "X" de la esquina.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-186">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="6f0a7-187">Corrige un problema que causaba que la configuración "Activar las mejoras del calendario compartido" en ocasiones no se pudiera aplicar a los calendarios compartidos existentes.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-187">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="6f0a7-188">Corrige un problema que provocaba que los usuarios vieran un error en la página de vínculos seguros en lugar del documento que intentaban abrir al abrir un archivo adjunto en la nube.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-188">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="6f0a7-189">Corrige un problema de rendimiento con la carga de archivos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-189">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="6f0a7-190">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6f0a7-190">PowerPoint</span></span>

- <span data-ttu-id="6f0a7-191">Este cambio corrige un problema relacionado con la característica Exportar a GIF animado, en la que no se exporta al hacer clic en el botón Exportar.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-191">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="6f0a7-192">Corrección de seguridad para solucionar un problema que deshabilita las protecciones IRM al abrir un archivo de PowerPoint en la Vista protegida.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-192">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>

- <span data-ttu-id="6f0a7-193">Se ha corregido un problema en la configuración de la Acción que provocaba un bloqueo en la aplicación PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-193">We have fixed an issue in Action Settings dialog which was causing a crash in PowerPoint app.</span></span>

### <a name="visio"></a><span data-ttu-id="6f0a7-194">Visio</span><span class="sxs-lookup"><span data-stu-id="6f0a7-194">Visio</span></span>

- <span data-ttu-id="6f0a7-195">Se ha corregido un problema que provocaba que la Vista previa en directo se bloqueara en la alineación del texto.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-195">We fixed an issue that caused the Live preview to crash on text alignment.</span></span>


### <a name="word"></a><span data-ttu-id="6f0a7-196">Word</span><span class="sxs-lookup"><span data-stu-id="6f0a7-196">Word</span></span>

- <span data-ttu-id="6f0a7-197">Corrige un problema que provocaba que los usuarios experimentaran un bloqueo al abrir algunos correos electrónicos muy grandes.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-197">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="6f0a7-198">Se ha corregido un problema por el que el usuario podría experimentar un error al abrir un documento.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-198">We fixed an issue which user might experience crash when opening a document.</span></span>


- <span data-ttu-id="6f0a7-199">Se ha corregido un problema que podía provocar un bloqueo al iniciar Word.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-199">Resolved an issue that may have caused a crash when booting Word.</span></span>


- <span data-ttu-id="6f0a7-200">Se ha corregido un problema con el cuadro de diálogo Galería de estilos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-200">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="6f0a7-201">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6f0a7-201">Office Suite</span></span>

- <span data-ttu-id="6f0a7-202">Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan toners</span><span class="sxs-lookup"><span data-stu-id="6f0a7-202">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="6f0a7-203">Cambiar mensaje para mostrar "tóner/Ink Low" & "no tóner/tinta".</span><span class="sxs-lookup"><span data-stu-id="6f0a7-203">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="6f0a7-204">Corrige el uso elevado de la CPU en modo inactivo con un GIF o un modelo 3D animado</span><span class="sxs-lookup"><span data-stu-id="6f0a7-204">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="6f0a7-205">Este cambio corrige un bloqueo al iniciar las aplicaciones de Office debido a un error al cargar d2d1.dll.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-205">This change addresses a crash when launching Office apps due to failing to load d2d1.dll.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO FINAL)

## <a name="version-2008-september-08"></a><span data-ttu-id="6f0a7-207">Versión 2008: 08 de septiembre</span><span class="sxs-lookup"><span data-stu-id="6f0a7-207">Version 2008: September 08</span></span>
<span data-ttu-id="6f0a7-208">*Versión 2008 (Compilación 13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="6f0a7-208">*Version 2008 (Build 13127.20408)*</span></span>

<span data-ttu-id="6f0a7-209">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-209">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="6f0a7-211">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="6f0a7-211">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="6f0a7-212">Access</span><span class="sxs-lookup"><span data-stu-id="6f0a7-212">Access</span></span>

- <span data-ttu-id="6f0a7-213">**Aumente su productividad con el Diseñador de consultas, la vista SQL y la ventana Relaciones:** haga clic con el botón derecho en una tabla para abrirla, diseñarla, cambiar su tamaño y ocultarla.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-213">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="6f0a7-214">Buscar y reemplazar texto en la vista SQL.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-214">Search and replace text in SQL View.</span></span> <span data-ttu-id="6f0a7-215">Seleccione múltiples tablas en la ventana Relaciones.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-215">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="6f0a7-216">**Agregue tablas con menos clics:** utilizar el panel de tareas agregar tablas, que permanece abierto mientras trabaja, para agregar tablas a relaciones y consultas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-216">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="6f0a7-217">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-217">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="6f0a7-218">Excel</span><span class="sxs-lookup"><span data-stu-id="6f0a7-218">Excel</span></span>

- <span data-ttu-id="6f0a7-219">**Gráficos de mapa mejorados:** hemos integrado los gráficos de mapa con los tipos de datos geográficos de Excel, para que revelen información de todo tipo sobre las ubicaciones que desee.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-219">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="6f0a7-220">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-220">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="6f0a7-221">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-221">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="6f0a7-222">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-222">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="6f0a7-223">**Crear tablas dinámicas de conjuntos de datos en Power BI desde Excel:** puede crear tablas dinámicas en Excel conectadas a los conjuntos de datos almacenados en Power BI con tan solo unos clics.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-223">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="6f0a7-224">Así, podrá obtener lo mejor de las tablas dinámicas y de Power BI.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-224">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="6f0a7-225">Calcule, resuma y analice sus datos con tablas dinámicas desde sus conjuntos de datos seguros de Power BI.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-225">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="6f0a7-226">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-226">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="6f0a7-227">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-227">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="6f0a7-228">**Sus funciones favoritas de Excel se han vuelto más rápidas:** las funciones SUMAR.SI.CONJUNTO, CONTAR.SI.CONJUNTO, PROMEDIO.SI.CONJUNTO, MAX.SI.CONJUNTO y MIN.SI.CONJUNTO son más rápidas que nunca.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-228">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="6f0a7-229">Llegue al final más rápidamente.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-229">Get to the bottom line more quickly.</span></span> <span data-ttu-id="6f0a7-230">Pruebe ahora una.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-230">Try one now.</span></span>

- <span data-ttu-id="6f0a7-231">**Mejoras de RealTimeData (RTD):** En la versión Microsoft Office 365 2002 canal mensual y posterior, la función RealTimeData (RTD) de Excel es mucho más rápida que calcular datos en la hoja de cálculo en Excel 2010.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-231">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="6f0a7-232">Hemos evitado atascos en su memoria subyacente y en las estructuras de datos, así como permitido el uso seguro de subprocesos para que se pueda calcular en todos los subprocesos disponibles de Recálculo multiproceso (MTR).</span><span class="sxs-lookup"><span data-stu-id="6f0a7-232">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="6f0a7-233">Outlook</span><span class="sxs-lookup"><span data-stu-id="6f0a7-233">Outlook</span></span>

- <span data-ttu-id="6f0a7-234">**Las actualizaciones del calendario compartido son más rápidas:** Outlook puede actualizar los calendarios compartidos en Office 365 con la API de REST.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-234">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="6f0a7-235">Active la vista previa para obtener actualizaciones más rápidas y confiables en los calendarios compartidos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-235">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="6f0a7-236">**Mejores resultados, en un instante:** actualizamos la experiencia de búsqueda para que sea más inteligente, rápida y fiable que nunca.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-236">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="6f0a7-237">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-237">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="6f0a7-238">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-238">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="6f0a7-239">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-239">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="6f0a7-240">**Arrastre el correo electrónico a un grupo de tu propiedad:** Mueva y copie mensajes y conversaciones arrastrándolos desde su bandeja de entrada.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-240">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="6f0a7-241">Los mensajes que arrastres serán compartidos con todos los miembros del grupo.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-241">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="6f0a7-242">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-242">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="6f0a7-243">**El calendario se transforma:** vea las actualizaciones visuales que hacen que el calendario sea más fácil de examinar.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-243">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="6f0a7-244">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-244">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="6f0a7-245">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-245">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="6f0a7-246">**Unirse a reuniones sin salir de la bandeja de entrada:** no es necesario cambiar al calendario para unirse a reuniones en línea.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-246">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="6f0a7-247">Con el Calendario de Outlook anclado en el panel de tareas pendientes, únase a una reunión con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-247">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="6f0a7-248">**Nueva experiencia para redes WiFi cautivas:** ¿alguna vez se ha unido a una red WiFi que requiere una página web para iniciar sesión?</span><span class="sxs-lookup"><span data-stu-id="6f0a7-248">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="6f0a7-249">Outlook ahora lo detecta y le ayuda a estar conectado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-249">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="6f0a7-250">Ver detalles en la [entrada de blog](https://insider.office.com/en-us/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-250">See details in [blog post](https://insider.office.com/en-us/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="6f0a7-251">**Obtener sugerencias de correo electrónico cuando busca un contacto:** cuando escriba el nombre de una persona en el cuadro de búsqueda, se incluirán los mensajes de correo electrónico más relevantes con las sugerencias de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-251">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="6f0a7-252">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-252">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a><span data-ttu-id="6f0a7-253">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6f0a7-253">PowerPoint</span></span>

- <span data-ttu-id="6f0a7-254">**Logre la atención de sus colegas con** @menciones:\@ use @menciones en los comentarios para avisar a los compañeros de trabajo cuando necesite su participación.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-254">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="6f0a7-255">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-255">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="6f0a7-256">**Gráficos de mapa mejorados:** hemos integrado los gráficos de mapa con los tipos de datos geográficos de Excel, para que revelen información de todo tipo sobre las ubicaciones que desee.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-256">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="6f0a7-257">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-257">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="6f0a7-258">**GIF en un instante:** una diapositiva, un marco.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-258">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="6f0a7-259">Cree fácilmente archivos GIF en bucle en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-259">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="6f0a7-260">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-260">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="6f0a7-261">Ver detalles en [entrada de blog](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-261">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="6f0a7-262">**Mejores diagramas** con mejores conectores y un proceso de conversión de entrada de lápiz más fluido, puede aplicar sus ideas con más confianza.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-262">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="6f0a7-263">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-263">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="6f0a7-264">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-264">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="6f0a7-265">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-265">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="6f0a7-266">**Comentarios:** la nueva experiencia de comentarios en PowerPoint permite descubrir y agregar comentarios a los documentos de forma rápida y sencilla.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-266">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="6f0a7-267">Modernice sus flujos de trabajo de colaboración con nuevas características como anclaje de comentarios, resuelva, tareas, notificaciones de menciones mejoradas y mucho más.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-267">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="6f0a7-268">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-268">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- <span data-ttu-id="6f0a7-269">**Sincronice los cambios mientras realiza la presentación:** sincronice los cambios cuando se hagan aunque la presentación esté en el modo de presentación con diapositivas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-269">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="6f0a7-270">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-270">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="6f0a7-271">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-271">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="6f0a7-272">**Vínculo a la diapositiva:** Pídale a un compañero que participe en la presentación de diapositivas y llévelo directamente a la diapositiva con la que necesita ayuda.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-272">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="6f0a7-273">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-273">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="6f0a7-274">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-274">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="6f0a7-275">**Mejor rendimiento de vídeos de Stream en PowerPoint:** hemos realizado mejoras en el rendimiento de la reproducción de los vídeos de Microsoft Stream para reducir el tiempo de carga de vídeo y crear una visualización más suave.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-275">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="6f0a7-276">Use los vídeos corporativos de Microsoft Stream para crear presentaciones mejoradas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-276">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>


### <a name="word"></a><span data-ttu-id="6f0a7-277">Word</span><span class="sxs-lookup"><span data-stu-id="6f0a7-277">Word</span></span>

- <span data-ttu-id="6f0a7-278">**Gráficos de mapa mejorados:** hemos integrado los gráficos de mapa con los tipos de datos geográficos de Excel, para que revelen información de todo tipo sobre las ubicaciones que desee.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-278">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="6f0a7-279">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-279">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="6f0a7-280">**Selección de lazo de la entrada de lápiz:** la herramienta Lazo en la pestaña Dibujar le ayuda a seleccionar objetos dibujados a mano.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-280">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="6f0a7-281">Seleccione trazos individuales o palabras completas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-281">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="6f0a7-282">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-282">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="6f0a7-283">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-283">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="6f0a7-284">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-284">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="6f0a7-285">**Confirmación de acción en lectores de pantalla:** la confirmación de la acción es un requisito de accesibilidad importante.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-285">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="6f0a7-286">Con la introducción de una nueva API de notificación de Windows, ahora podemos alertar a los usuarios de lectores de pantalla sobre el éxito de sus acciones.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-286">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="6f0a7-287">Las opciones de cortar, copiar, pegar, negrita, cursiva, subrayado, deshacer, rehacer, corrección automática y uso automático de mayúsculas ahora se anuncian a los usuarios del narrador en Word Win32.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-287">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="6f0a7-288">Para habilitar esta característica, active el narrador presionando Windows + Ctrl + Entrar.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-288">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="6f0a7-289">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-289">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="6f0a7-290">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6f0a7-290">Office Suite</span></span>

- <span data-ttu-id="6f0a7-291">**Etiquetas de confidencialidad:** ahora puede aplicar una etiqueta de confidencialidad que su organización ha configurado para solicitarle permisos personalizados.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-291">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6f0a7-294">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6f0a7-294">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="6f0a7-295">Acceso</span><span class="sxs-lookup"><span data-stu-id="6f0a7-295">Access</span></span>

- <span data-ttu-id="6f0a7-296">Se ha resuelto un problema al insertar tablas SQL vinculadas que incluyan un campo de identidad (por ejemplo, autonumeración).</span><span class="sxs-lookup"><span data-stu-id="6f0a7-296">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

- <span data-ttu-id="6f0a7-297">Se ha corregido un problema que provocaba que la ejecución de consultas tardara en completarse aproximadamente el doble del tiempo esperado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-297">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="6f0a7-298">Se ha corregido un problema para poder llamar al tipo de datos Fecha/Hora ampliado en el código sin tener que bloquear la aplicación.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-298">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span>

- <span data-ttu-id="6f0a7-299">Se ha corregido un problema de forma que ahora puede volver a la versión de Access más actualizada y usar DAO/VBA para administrar y editar un tipo de datos decimal.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-299">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>

- <span data-ttu-id="6f0a7-300">Esta corrección resuelve un problema por el que al intentar ejecutar determinadas consultas anteriormente se generaba el mensaje de error "La consulta es demasiado compleja".</span><span class="sxs-lookup"><span data-stu-id="6f0a7-300">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="6f0a7-301">Access ha corregido este problema actual, pero se está investigando nuestra interfaz adicional para asegurarnos de que este problema no se conserva.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-301">Access has fixed this current issue, but will be investigating our additional interfaces to ensure that this problem does not persist.</span></span> <span data-ttu-id="6f0a7-302">El equipo le informará en actualizaciones futuras. Agradecemos su paciencia.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-302">The team will inform you with future updates; we appreciate your patience.</span></span>

- <span data-ttu-id="6f0a7-303">Este problema fue resuelto: ahora puede usar el controlador ODBC fuera de las aplicaciones de Hacer clic y ejecutar de Office.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-303">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="6f0a7-304">Excel</span><span class="sxs-lookup"><span data-stu-id="6f0a7-304">Excel</span></span>

- <span data-ttu-id="6f0a7-305">Es posible que se haya producido una clasificación de documentos automática en los libros que se encontraban en modo de solo lectura.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-305">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="6f0a7-306">Se ha corregido un bloqueo que podría producirse al intentar crear una conexión de datos si había cerrado la sesión de su cuenta.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-306">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

- <span data-ttu-id="6f0a7-307">Se ha corregido un problema por el que Excel se bloqueaba al intentar insertar tablas dinámicas en una hoja de gráfico.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-307">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

- <span data-ttu-id="6f0a7-308">Se puede producir un error al intentar guardar un archivo que contiene una fórmula con la función LET().</span><span class="sxs-lookup"><span data-stu-id="6f0a7-308">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="6f0a7-309">Se ha corregido un problema que provocaba que Excel se bloqueara en determinadas circunstancias al usar Copiar formato.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-309">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>

- <span data-ttu-id="6f0a7-310">Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta al guardar en SharePoint o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-310">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="6f0a7-311">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-311">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="6f0a7-312">Se solucionó un problema por el cual, en algunos casos, al hacer clic en un hipervínculo a un lugar dentro del mismo libro de trabajo, el libro de trabajo se ocultaba.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-312">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

- <span data-ttu-id="6f0a7-313">Se ha corregido un problema que hacía que el vínculo externo dejara de funcionar después de que se volviera a abrir un archivo si su ruta de acceso era demasiado larga.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-313">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="6f0a7-314">Application.Evaluate (VBA) no funcionaba para funciones definidas por el usuario en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-314">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="6f0a7-315">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-315">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="6f0a7-316">Se ha corregido un problema que hacía que Excel se bloqueara en ciertos casos después de copiar una hoja que contenía una tabla dinámica.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-316">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="6f0a7-317">Esto soluciona un problema en el que las conexiones creadas por el proveedor de datos SQL en versiones anteriores de Office establecerían las propiedades de la tabla interna de manera diferente a Office 365.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-317">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="6f0a7-318">Esto provocó que el menú desplegable Vista previa de tabla / Editor de consultas se deshabilitara para los archivos con conexiones creadas en versiones anteriores de Office cuando se abrieron con Office 365.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-318">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>

- <span data-ttu-id="6f0a7-319">Corregido un problema por el que los enlaces externos no se actualizaban si el libro de origen estaba cerrado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-319">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="6f0a7-320">Se corrigió un problema por el cual las entradas manuscritas podrían hacer que Excel dejara de responder.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-320">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="onenote"></a><span data-ttu-id="6f0a7-321">OneNote</span><span class="sxs-lookup"><span data-stu-id="6f0a7-321">OneNote</span></span>

- <span data-ttu-id="6f0a7-322">Se informa a los usuarios mediante la barra de información sobre los ajustes temporales de Microsoft OneNote que les ayudarán a mejorar la sincronización y la disponibilidad del servicio durante un uso mundial elevado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-322">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

- <span data-ttu-id="6f0a7-323">Mejora de la sincronización y la estabilidad del servicio al ajustar temporalmente la frecuencia de sincronización en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-323">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="6f0a7-324">Se mejoró la detección del estado de la coautoría para reducir el uso de recursos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-324">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="6f0a7-325">Se obtiene una mejora de la sincronización y la estabilidad del servicio al reducir temporalmente el tamaño máximo de nuevos datos adjuntos insertados a 50 MB en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-325">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="6f0a7-326">Si los archivos superan este límite, los usuarios tendrán la opción de cargar el archivo a OneDrive e insertar un vínculo en OneNote.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-326">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="6f0a7-327">Se obtiene una mejora de la sincronización y la estabilidad del servicio al deshabilitar temporalmente la grabación de vídeo en la aplicación en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-327">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="6f0a7-328">La medida no afecta a los blocs de notas locales.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-328">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="6f0a7-329">Se obtiene una mejora de la sincronización y la estabilidad del servicio al alterar temporalmente la frecuencia con la que se crean los historiales de las versiones de las páginas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-329">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>

- <span data-ttu-id="6f0a7-330">Se obtiene una mejora de la sincronización y la estabilidad del servicio al deshabilitar temporalmente el desplazamiento de páginas a la papelera de reciclaje.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-330">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="6f0a7-331">A los usuarios que quieran eliminar una página se les mostrará un cuadro de diálogo en el que se le preguntará si quieren eliminar una página de forma permanente.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-331">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>

### <a name="outlook"></a><span data-ttu-id="6f0a7-332">Outlook</span><span class="sxs-lookup"><span data-stu-id="6f0a7-332">Outlook</span></span>

- <span data-ttu-id="6f0a7-333">Corrige un problema que evitaba que los usuarios que intentaran crear una solicitud de reunión desde una cuenta secundaria añadida a su perfil vieran el campo De: en blanco en lugar de su dirección de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-333">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="6f0a7-334">Corrige un problema que evitaba que los usuarios se conectaran a las carpetas públicas luego de agregar un buzón compartido.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-334">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="6f0a7-335">Se ha corregido un problema que provocaba un error al tratar de eliminar las reuniones del calendario de un administrador, cuando un delegado las rechazaba en determinadas circunstancias.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-335">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="6f0a7-336">Se corrigió un problema que impedía a algunos usuarios de la característica Mejoras del calendario compartido ver un calendario compartido recién agregado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-336">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="6f0a7-337">Corrige un problema que provocaba que los usuarios experimentaran bloqueos ocasionales al interactuar con los datos adjuntos en la nube.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-337">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="6f0a7-338">Se ha corregido un problema que provocaba que los usuarios de CLP experimenten un bloqueo al cambiar la dirección del remitente en una respuesta desde un contexto protegido a uno no protegido.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-338">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>

- <span data-ttu-id="6f0a7-339">Se ha corregido un problema por el que Outlook no pudo habilitar consejos de directiva para la Protección de pérdida de datos para usuarios que pagaron por el servicio con planes M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-339">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="6f0a7-340">Se ha corregido un problema con el evento de auditoría CLP para la etiqueta de responder o reenviar.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-340">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="6f0a7-341">Se ha corregido un problema que provocaba que el ancho del panel de carpetas cambiara inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-341">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="6f0a7-342">Se ha corregido un problema que causaba que la fecha de creación de datos adjuntos copiados en el sistema de archivos a través de la opción de arrastrar y soltar apareciera como el 1 de enero de 4501.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-342">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>

- <span data-ttu-id="6f0a7-343">Se ha corregido un problema que provocaba que los usuarios de algunos juegos de caracteres viesen nombres de archivo que se mostraban de forma incorrecta al agregar un vínculo inteligente a un archivo de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-343">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="6f0a7-344">Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange", al actualizar sus reglas en Outlook.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-344">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="6f0a7-345">Se corrigió un problema que provocaba que Outlook no pudiese recuperar sugerencias de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-345">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>

- <span data-ttu-id="6f0a7-346">Se ha corregido un problema que provocaba que los usuarios de las mejoras del Calendario compartido vieran errores en el calendario.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-346">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="6f0a7-347">Se ha corregido un problema que causaba que los usuarios experimentasen bloqueos y errores intermitentes en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-347">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>

- <span data-ttu-id="6f0a7-348">Se ha corregido un problema que provocaba que los usuarios experimentaran un error al eliminar 4 o más mensajes de correo electrónico de una cuenta POP con la opción "Descargar solo encabezados" seleccionada.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-348">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="6f0a7-349">Se ha corregido un problema que causaba que faltara la opción "Permitir reenvío" en las "Opciones de respuesta" de la reunión de calendario compartida cuando NO está marcada Descargar carpeta compartida.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-349">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="6f0a7-350">Se ha corregido un problema que causaba que los delegados recibieran un error al editar una cita de calendario existente en el calendario de un administrador.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-350">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="6f0a7-351">Se ha corregido un problema que provocaba que los usuarios experimentaran bloqueos en aplicaciones MAPI de terceros.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-351">Addressed an issue that caused users to experience crashes in third party MAPI applications.</span></span>

- <span data-ttu-id="6f0a7-352">Se ha corregido un problema que provocaba que Outlook se bloqueara al abrir archivos .msg y .oft guardados localmente después de una actualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-352">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="6f0a7-353">Se ha corregido un problema que provocaba que Outlook se bloqueara en algunas compilaciones de Windows.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-353">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="6f0a7-354">Se ha corregido un problema que provocaba que los usuarios de las versiones de Windows 10 Server vieran la advertencia "Estado del antivirus: no válido".</span><span class="sxs-lookup"><span data-stu-id="6f0a7-354">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="6f0a7-355">Esta versión de Windows admite la detección del antivirus, pero no se encontró ninguno” a pesar de tener un antivirus correctamente instalado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-355">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="6f0a7-356">Se ha corregido un problema que provocaba que Outlook se bloqueara al abrir archivos .msg y .oft guardados localmente después de una actualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-356">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="6f0a7-357">Se ha corregido un problema que provocaba que Outlook se bloqueara en algunas compilaciones de Windows.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-357">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="6f0a7-358">Se ha corregido un problema que provocaba que los usuarios de Outlook vieran continuamente un aviso para que ejecutaran la herramienta de reparación de la bandeja de entrada.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-358">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="6f0a7-359">Abordó un problema que causó que los usuarios experimentaran ocasionalmente un choque al usar el botón "X" de su ratón.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-359">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="6f0a7-360">Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-360">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="6f0a7-361">Se ha corregido un problema que provocaba que la página del Asistente para programación no se mostrara.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-361">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="6f0a7-362">Se ha corregido un problema que impedía a algunos usuarios visualizar correctamente la página del Asistente para programación.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-362">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="6f0a7-363">Se corrigió un problema que provocaba que los usuarios se bloquearan en ocasiones al recuperar información personal.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-363">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>

- <span data-ttu-id="6f0a7-364">Esto corrige un problema que provocaba que los usuarios experimentaran bloqueos ocasionales al editar los destinatarios.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-364">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="6f0a7-365">Corrige un problema que provocaba que los usuarios vieran anomalías al usar la vista compacta.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-365">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="6f0a7-366">Se ha corregido un problema que provocaba que los usuarios de Outlook tuvieran problemas con la navegación en vistas compactas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-366">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>

- <span data-ttu-id="6f0a7-367">Se ha corregido un problema que provocaba que el menú contextual del botón derecho no apareciera en los controles de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-367">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="6f0a7-368">Corrige un problema que provocaba que los usuarios recibieran el siguiente error al responder a un correo o al redactar uno nuevo: "Algunos archivos de esta página web no están en la ubicación esperada.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-368">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="6f0a7-369">¿Desea descargarlos de todos modos?</span><span class="sxs-lookup"><span data-stu-id="6f0a7-369">Do you want to download them anyway?</span></span> <span data-ttu-id="6f0a7-370">Si está seguro de que la página web es una fuente de confianza, haga clic en Sí".</span><span class="sxs-lookup"><span data-stu-id="6f0a7-370">If you’re sure the Web page is from a trusted source, click Yes"</span></span>

- <span data-ttu-id="6f0a7-371">Corrige un problema que provocaba que los usuarios experimentaran un error al salir de Outlook.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-371">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>

- <span data-ttu-id="6f0a7-372">Se ha corregido un problema que provocaba que la búsqueda de una característica en Sugerir una característica no devolviera resultados y no ofrecía al usuario ninguna opción para enviar una nueva idea de característica.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-372">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="6f0a7-373">Se ha abordado un problema que causaba problemas de formato en las alertas de notificación de incidentes.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-373">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

- <span data-ttu-id="6f0a7-374">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al enviar comentarios desde una Notificación de administrador.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-374">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="6f0a7-375">Se ha corregido un problema para copiar y pegar imágenes SVG.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-375">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="6f0a7-376">Esto corrige un problema que provocaba que los usuarios experimentaran bloqueos ocasionales al editar los destinatarios.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-376">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="6f0a7-377">Se ha corregido un problema para copiar y pegar imágenes SVG.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-377">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="6f0a7-378">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6f0a7-378">PowerPoint</span></span>

- <span data-ttu-id="6f0a7-379">Se corrigió un bloqueo cuando los usuarios tenían comentarios tanto modernos como heredados en un archivo, lo que activaba una actualización de los comentarios.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-379">Fixed a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

- <span data-ttu-id="6f0a7-380">Se ha corregido un problema de bloqueo con la aplicación de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-380">We have fixed a crash issue with PowerPoint app.</span></span>

- <span data-ttu-id="6f0a7-381">Se ha corregido un problema de bloqueo en el panel de sugerencias.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-381">We have fixed a crash issue with suggestion pane.</span></span>

### <a name="project"></a><span data-ttu-id="6f0a7-382">Project</span><span class="sxs-lookup"><span data-stu-id="6f0a7-382">Project</span></span>

- <span data-ttu-id="6f0a7-383">Se solucionó un problema cuando los datos del Predecesor/Sucesor se editaban dentro de una vista de formulario, se activaba un evento ProjectBeforeTaskChange adicional.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-383">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="6f0a7-384">Corregido un problema por el que Project puede bloquearse al guardar proyectos creados con versiones anteriores de Project.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-384">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="6f0a7-385">Se corrigió un problema por el que el usuario no podía especificar el trabajo previsto con fases temporales al activar la configuración para proteger el trabajo real.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-385">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

- <span data-ttu-id="6f0a7-386">Corregido un problema por el que el porcentaje completado de la tarea se cambiaba incorrectamente a un valor inferior al 100 % después de que se marcara como completada. </span><span class="sxs-lookup"><span data-stu-id="6f0a7-386">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="6f0a7-387">Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-387">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="6f0a7-388">Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-388">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="6f0a7-389">Corregido un problema que hace que el evento ProjectBeforeTaskChange no detecte cuándo se ha desactivado o activado una tarea mediante el botón Desactivar.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-389">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="6f0a7-390">Se ha corregido un problema que hace que si está usando Project conectado a Project Web App y el separador decimal es una coma, el método TaskDependencies Add producirá un error al intentar agregar retardo a una dependencia.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-390">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

- <span data-ttu-id="6f0a7-391">Se ha corregido un problema por el que los proyectos no se podían abrir en el cliente de escritorio de Project desde Project Web App si la dirección URL terminaba en .com.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-391">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>

- <span data-ttu-id="6f0a7-392">Se ha corregido un problema por el que si pegaba una tarea que tenía varias dependencias, no todas las dependencias se copiaban correctamente.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-392">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="6f0a7-393">Se ha corregido un problema que impedía guardar desde Project un PDF o XPS en una biblioteca de documentos de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-393">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>

- <span data-ttu-id="6f0a7-394">Se ha corregido un problema por el que una tarea marcada como completada al 100 % se mostraba por error no completada al 100 %.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-394">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="6f0a7-395">Se ha corregido un problema por el que el evento ProjectBeforeTaskChange no se activaba al darse un cambio en la tarea de resumen del proyecto: ya sea en el campo de inicio o tarea del proyecto.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-395">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="6f0a7-396">Se ha corregido un problema debido al cual, si un recurso tenía más de una tabla de tasa de costo definida, el costo restante no siempre se calculaba correctamente.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-396">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

- <span data-ttu-id="6f0a7-397">Se ha corregido un problema en el que la fecha de finalización de Project no se actualiza para los proyectos conectados a la lista de tareas de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-397">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="6f0a7-398">Se ha corregido un problema por el que la tarea seleccionada en el cuadro de diálogo de asignación de recursos no era la misma que la tarea seleccionada en la vista del panel de tareas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-398">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="6f0a7-399">Se corrigió un problema por el que no se podía abrir un proyecto que estaba en mal estado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-399">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>

### <a name="skype"></a><span data-ttu-id="6f0a7-400">Skype</span><span class="sxs-lookup"><span data-stu-id="6f0a7-400">Skype</span></span>

- <span data-ttu-id="6f0a7-401">Cuando se asignaba a un usuario una directiva que lo llevaba a Teams solo, aún se podía usar el complemento para Outlook de Skype Empresarial para programar reuniones.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-401">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="6f0a7-402">Tras esta actualización, ya no se podrán programar reuniones de Skype Empresarial después de que el cliente lea la directiva en la que se indica que el usuario participa en Teams solo y entra en la reunión como Unirse solo.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-402">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="6f0a7-403">Además, el complemento de Outlook para Skype Empresarial no se activará durante el inicio si ve que el cliente de Skype Empresarial se encuentra en modo de Unirse solo.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-403">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="6f0a7-404">Se cambió el tono de piel del emoticono de baile a un color neutro</span><span class="sxs-lookup"><span data-stu-id="6f0a7-404">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="6f0a7-405">Word</span><span class="sxs-lookup"><span data-stu-id="6f0a7-405">Word</span></span>

- <span data-ttu-id="6f0a7-406">Se ha resuelto un problema al abrir documentos de Word desde la entrega de documentos personalizados (aspx) cuando la dirección URL contenía un componente de consulta.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-406">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="6f0a7-407">Este cambio corrige un problema que provocaba que las aplicaciones de Office se queden atascadas en un estado de error de guardado silencioso después de una sesión de coautoría anterior.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-407">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="6f0a7-408">Corrige un problema que provocaba que los usuarios experimentaran un bloqueo al responder o redactar un correo nuevo.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-408">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="6f0a7-409">Abordó un problema que causó que los usuarios experimentaran ocasionalmente un choque al usar el botón "X" de su ratón.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-409">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="6f0a7-410">Se ha corregido un problema para copiar y pegar imágenes SVG.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-410">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="6f0a7-411">Se ha corregido un problema por el cual el usuario podría perder contenido al cambiar el tamaño de una forma.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-411">We fixed an issue where the user might lose content when resize a shape.</span></span>

- <span data-ttu-id="6f0a7-412">Se ha corregido un problema por el cual los estilos base no se actualizaban con el estilo Normal.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-412">We fixed an issue which the base styles are not updated with Normal style.</span></span>

- <span data-ttu-id="6f0a7-413">Se ha corregido un problema por el que se ejecuta la macro AutoOpen antes de AutoExec.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-413">We fixed an issue where macro AutoOpen runs before AutoExec.</span></span>

- <span data-ttu-id="6f0a7-414">Se ha corregido un problema para copiar y pegar imágenes SVG.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-414">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="6f0a7-415">Se ha corregido un problema que podría haber provocado un bloqueo al arrastrar contenido desde la aplicación.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-415">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="6f0a7-416">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6f0a7-416">Office Suite</span></span>

- <span data-ttu-id="6f0a7-417">Para un antiguo panel de uso compartido basado en servicio no Web, al cerrar el documento mientras el panel de uso compartido está abierto, se podría producir un bloqueo.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-417">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="6f0a7-418">Este problema ya está solucionado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-418">This is now fixed.</span></span>

- <span data-ttu-id="6f0a7-419">Se corrigió un problema de temporización que podía provocar un bloqueo al cerrar archivos de Office.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-419">Fixed a timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="6f0a7-420">Hemos resuelto el problema de la tasa de error de ValidateInstall estableciendo la validación de instalación del Complemento de Bing como verdadera de forma predeterminada y considerando el éxito de devolución de MSI como una instalación con éxito.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-420">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>

- <span data-ttu-id="6f0a7-421">Hemos modificado la versión AppV51 para solucionar una regresión de la AppV51 anterior.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-421">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="6f0a7-422">Se ha corregido un problema de hacer clic y ejecutar que generaba errores de actualización al intentar crear un vínculo físico para vínculos simbólicos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-422">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>

- <span data-ttu-id="6f0a7-423">Se ha corregido un problema que provocaba que se mostrara un mensaje de tiempo de ejecución aunque se completara la transición al producto completo.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-423">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="6f0a7-424">La corrección para este problema era asegurarse de que el servicio computase correctamente los productos agregados.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-424">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="6f0a7-425">Se han filtrado los nuevos productos agregados (lo que garantiza que también se encuentren en la nueva configuración) y se han agregado al final de los ID de versión de producto existentes.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-425">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>

- <span data-ttu-id="6f0a7-426">Se ha corregido un problema debido al cual los usuarios no podían visualizar el contenido o los elementos de la interfaz de usuario en determinadas condiciones, especialmente en la vista Moderador (o al salir de la misma) o al usar varios monitores.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-426">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>

- <span data-ttu-id="6f0a7-427">Este cambio resuelve posibles errores al cargar y reproducir contenido animado como GIF o modelos 3D.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-427">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>

- <span data-ttu-id="6f0a7-428">Este cambio resuelve un problema con el cuadro de diálogo de Comprimir imagen, que no retiene determinadas configuraciones de usuario.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-428">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>

- <span data-ttu-id="6f0a7-429">Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-429">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="6f0a7-430">Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-430">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="6f0a7-431">Esta corrección resuelve un error que impide restringir el acceso y proteger los archivos con una contraseña de forma simultánea.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-431">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="6f0a7-432">Se ha corregido un problema de bloqueo con el host de Office en Windows cuando se activa un complemento mientras el valor del registro TabProcGrowth era del tipo REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-432">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="6f0a7-433">El host de Office se bloqueaba en Windows, cuando se activaba un complemento si la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth estaba establecida en cero.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-433">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="6f0a7-434">Este cambio arreglaría el problema.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-434">This change would fix this issue.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-august-11"></a><span data-ttu-id="6f0a7-436">Versión 2002: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="6f0a7-436">Version 2002: August 11</span></span>
<span data-ttu-id="6f0a7-437">*Versión 2002 (compilación 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="6f0a7-437">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="6f0a7-438">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-438">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6f0a7-440">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6f0a7-440">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6f0a7-441">Excel</span><span class="sxs-lookup"><span data-stu-id="6f0a7-441">Excel</span></span>

- <span data-ttu-id="6f0a7-442">Se corrigió un problema por el que no se podía cambiar a la edición de archivos que se han abierto como "recomendado solo lectura".</span><span class="sxs-lookup"><span data-stu-id="6f0a7-442">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="6f0a7-443">OneNote</span><span class="sxs-lookup"><span data-stu-id="6f0a7-443">OneNote</span></span>

- <span data-ttu-id="6f0a7-444">Se quitaron las llamadas de identidad redundantes para reducir el uso de recursos</span><span class="sxs-lookup"><span data-stu-id="6f0a7-444">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="6f0a7-445">Se mejoró la detección del estado de la coautoría para reducir el uso de recursos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-445">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="6f0a7-446">Se mejoró la función de detección de errores y la calidad de la experiencia de sincronización.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-446">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="6f0a7-447">Outlook</span><span class="sxs-lookup"><span data-stu-id="6f0a7-447">Outlook</span></span>

- <span data-ttu-id="6f0a7-448">Se corrigió un problema que causaba un problema de rendimiento importante al iniciar Outlook en algunos espacios empresariales.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-448">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="6f0a7-449">Skype</span><span class="sxs-lookup"><span data-stu-id="6f0a7-449">Skype</span></span>

- <span data-ttu-id="6f0a7-450">Se corrigió un problema por el que se podía producir un error al compartir la pantalla en un cliente de Skype Empresarial de 32 bits después de ejecutarlo durante varios días.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-450">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6f0a7-451">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="6f0a7-451">Office Suite</span></span>

- <span data-ttu-id="6f0a7-452">Se corrigió un problema que se producía al desactivar el autoguardado a través de la directiva de grupo: era posible que algunos documentos no mostraran el contenido más reciente de servidor al abrirse hasta que el usuario hiciera clic en "Actualizaciones disponibles".</span><span class="sxs-lookup"><span data-stu-id="6f0a7-452">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-july-14"></a><span data-ttu-id="6f0a7-454">Versión 2002: 14 de julio</span><span class="sxs-lookup"><span data-stu-id="6f0a7-454">Version 2002: July 14</span></span>
<span data-ttu-id="6f0a7-455">*Versión 2002 (compilación 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="6f0a7-455">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="6f0a7-456">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-456">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6f0a7-458">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6f0a7-458">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6f0a7-459">Excel</span><span class="sxs-lookup"><span data-stu-id="6f0a7-459">Excel</span></span>

- <span data-ttu-id="6f0a7-460">Acelere la carga de archivos que están disponibles en la carpeta de OneDrive local.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-460">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="6f0a7-461">Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta al guardar en SharePoint o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-461">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="6f0a7-462">Se ha corregido un problema que producía el siguiente mensaje de error: "No se puede cerrar el libro de trabajo debido a que otro libro hace referencia al mismo". El mensaje aparecía si los complementos se cargaban en orden alfabético en lugar de en un orden especificado por el usuario.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-462">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="6f0a7-463">Se ha corregido un problema que haría que un libro se ocultara al hacer clic en un hipervínculo a un lugar dentro de un libro ya abierto.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-463">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="6f0a7-464">Se ha corregido un problema por el que algunos vínculos de un gráfico copiado y pegado usaban direcciones de unidad asignadas, en lugar de direcciones universales.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-464">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="6f0a7-465">Se ha mejorado el rendimiento al eliminar columnas con celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-465">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="6f0a7-466">Se ha corregido un problema por el que los nombres de las impresoras podrían repetirse en la lista de impresoras en el cuadro de diálogo Imprimir.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-466">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="6f0a7-467">Se ha corregido un problema por el que las hojas de cálculo que contenían varias fórmulas con nombres definidos tardaban más en guardarse.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-467">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="6f0a7-468">Outlook</span><span class="sxs-lookup"><span data-stu-id="6f0a7-468">Outlook</span></span>

- <span data-ttu-id="6f0a7-469">Se ha corregido un problema por el que la ventana del Editor de métodos de entrada (IME) se superponía al texto subyacente escrito mediante el IME cuando se usaban varios monitores con resoluciones diferentes.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-469">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="6f0a7-470">Se ha corregido un problema que causaba que las citas o reuniones periódicas se mostraran en un momento incorrecto al tratar de cambiar la definición de una zona horaria.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-470">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="6f0a7-471">Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange", al actualizar sus reglas en Outlook.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-471">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="6f0a7-472">Se ha corregido un problema que causaba que faltara la opción "Permitir reenvío" en las "Opciones de respuesta" de la reunión de calendario compartida cuando NO está marcada Descargar carpeta compartida.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-472">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="6f0a7-473">Se ha corregido un problema que provocaba que las categorías desapareciesen en ocasiones de los mensajes de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-473">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="6f0a7-474">Se ha corregido un problema que provocaba que los delegados viesen distintas jerarquías de carpetas en diferentes equipos para los buzones compartidos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-474">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="6f0a7-475">Se ha corregido un problema que causaba que los delegados recibieran un error al editar una cita de calendario existente en el calendario de un administrador.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-475">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="6f0a7-476">Se ha corregido un problema que provocaba que el cuerpo de un mensaje NDR cambiara de Unicode a ASCII después de editar el asunto.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-476">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="6f0a7-477">Se ha corregido un problema que causaba que los usuarios experimentaran un bloqueo cuando dos complementos agregan un botón al mismo grupo de la cinta de opciones.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-477">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="6f0a7-478">Se ha corregido un problema que provocaba que los usuarios no pudieran dirigir mensajes de correo electrónico a una lista de distribución personal.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-478">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="6f0a7-479">Se ha corregido un problema que provocaba que los vínculos no se agregaran a los correos electrónicos con el permiso predeterminado incorrecto de espacio empresarial cuando el permiso predeterminado de espacio empresarial se configura como "cualquiera".</span><span class="sxs-lookup"><span data-stu-id="6f0a7-479">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="6f0a7-480">Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-480">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="6f0a7-481">Word</span><span class="sxs-lookup"><span data-stu-id="6f0a7-481">Word</span></span>

- <span data-ttu-id="6f0a7-482">Se ha corregido un problema de coautoría si se habilita la Directiva FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-482">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="6f0a7-483">Se ha corregido un problema en el que Word QuickPart no funciona al agregar un campo de búsqueda cuyo nombre se ha cambiado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-483">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6f0a7-484">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="6f0a7-484">Office Suite</span></span>

- <span data-ttu-id="6f0a7-485">Se ha corregido un problema que podía hacer que los usuarios experimentaran un uso excesivo de la red y de la CPU durante la coautoría en archivos de PowerPoint grandes.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-485">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="6f0a7-486">Hemos modificado la versión AppV51 para solucionar una regresión de la AppV51 anterior.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-486">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="6f0a7-487">Se ha corregido un problema de bloqueo con el host de Office en Windows cuando se activa un complemento mientras el valor del registro TabProcGrowth era del tipo REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-487">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-june-09"></a><span data-ttu-id="6f0a7-489">Versión 2002: 09 de junio</span><span class="sxs-lookup"><span data-stu-id="6f0a7-489">Version 2002: June 09</span></span>
<span data-ttu-id="6f0a7-490">*Versión 2002 (compilación 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="6f0a7-490">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="6f0a7-491">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-491">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6f0a7-493">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6f0a7-493">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6f0a7-494">Excel</span><span class="sxs-lookup"><span data-stu-id="6f0a7-494">Excel</span></span>

- <span data-ttu-id="6f0a7-495">Se ha corregido un problema que hacía que el vínculo externo dejara de funcionar después de que se volviera a abrir el archivo si su ruta de acceso era demasiado larga.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-495">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="6f0a7-496">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-496">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="6f0a7-497">Se ha corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-497">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="6f0a7-498">Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-498">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="6f0a7-499">Insertar una columna en una lista filtrada llevaba más tiempo de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-499">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="6f0a7-500">Se ha corregido un problema por el que un símbolo @ que inicia una fórmula se considera un operador de intersección implícita.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-500">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="6f0a7-501">Outlook</span><span class="sxs-lookup"><span data-stu-id="6f0a7-501">Outlook</span></span>

- <span data-ttu-id="6f0a7-502">Permite unirse a una reunión de Teams directamente a través del cliente nativo de Teams.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-502">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="6f0a7-503">Se ha corregido un problema por el que Outlook no pudo habilitar consejos de directiva para la Protección de pérdida de datos para usuarios que pagaron por el servicio con planes M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-503">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="6f0a7-504">Se ha corregido un problema que provocaba que los usuarios con la configuración de emulación de explorador incorrecta no pudieran completar el mensaje de autenticación de Gmail.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-504">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="6f0a7-505">Se ha corregido un problema que provocaba que los usuarios de Outlook en sistemas operativos de servidor vieran el error: "Estado del antivirus: no válido.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-505">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="6f0a7-506">Esta versión de Windows admite la detección del antivirus, pero no se encontró ninguno" a pesar de tener el antivirus correctamente configurado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-506">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="6f0a7-507">Word</span><span class="sxs-lookup"><span data-stu-id="6f0a7-507">Word</span></span>

- <span data-ttu-id="6f0a7-508">Se ha corregido un problema por el que la alineación de las palabras de un documento se descomponía al intentar editar después de imprimir con la impresión rápida.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-508">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6f0a7-509">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6f0a7-509">Office Suite</span></span>

- <span data-ttu-id="6f0a7-510">Se ha resuelto este problema mediante la actualización de los nombres de canal en el backstage con los nuevos nombres de canal en la bifurcación de enero de 2020.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-510">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="6f0a7-511">Se ha corregido este problema y en adelante, si un dispositivo se administra mediante directiva, no llamará a la API de audiencia de DMS.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-511">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="6f0a7-512">Se ha resuelto el problema en el que había una eliminación incompleta al agregar y quitar aplicaciones en una sola transacción.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-512">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="6f0a7-513">El host de Office se bloqueaba en Windows, cuando se activaba un complemento si la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth estaba establecida en cero.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-513">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="6f0a7-514">Este cambio arreglaría el problema.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-514">This change would fix this issue.</span></span>


[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-may-12"></a><span data-ttu-id="6f0a7-516">Versión 2002: 12 de mayo</span><span class="sxs-lookup"><span data-stu-id="6f0a7-516">Version 2002: May 12</span></span>
<span data-ttu-id="6f0a7-517">*Versión 2002 (compilación 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="6f0a7-517">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="6f0a7-518">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-518">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6f0a7-520">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6f0a7-520">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="6f0a7-521">Excel</span><span class="sxs-lookup"><span data-stu-id="6f0a7-521">Excel</span></span>

- <span data-ttu-id="6f0a7-522">La apertura de un libro de trabajo con referencias a muchos otros libros de trabajo, especialmente con ventanas ocultas, era más lento de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-522">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="6f0a7-523">La apertura de archivos CSV tardaba más de lo esperado en algunas circunstancias.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-523">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="6f0a7-524">Excel se bloqueaba en determinadas circunstancias al cambiar entre libros con diferentes niveles de zoom.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-524">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="6f0a7-525">Se ha corregido un problema con VBA por el que escribir valores en un rango era más lento de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-525">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="6f0a7-526">En ocasiones, los datos copiados de una columna filtrada por color no se pegaban correctamente.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-526">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="6f0a7-527">Se ha corregido un problema que hacía que Excel se bloqueara en ciertos casos después de copiar una hoja que contenía una tabla dinámica.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-527">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="6f0a7-528">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-528">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="6f0a7-529">Se ha corregido un problema por el que la propiedad "Value Crosses At" en el eje del gráfico cambiaba inesperadamente al guardar y volver a abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-529">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="6f0a7-530">El uso de un Range.Value y Range.Value2 (VBA) hacía que las fórmulas se escribieran como matrices dinámicas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-530">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="6f0a7-531">OneNote</span><span class="sxs-lookup"><span data-stu-id="6f0a7-531">OneNote</span></span>

- <span data-ttu-id="6f0a7-532">Localiza la notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-532">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="6f0a7-533">Muestra una notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-533">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="6f0a7-534">Sincronización y estabilidad de servicio mejoradas al reducir temporalmente el número y la frecuencia de sincronización de las páginas del historial de versiones en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-534">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="6f0a7-535">Mejora de la sincronización y la estabilidad del servicio al deshabilitar temporalmente la papelera de reciclaje en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-535">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="6f0a7-536">Cuando un usuario intenta eliminar datos que normalmente se enviarían a la papelera de reciclaje, se le preguntará si prefiere conservarlos o eliminarlos forma permanente.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-536">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="6f0a7-537">Mejora de la sincronización y la estabilidad del servicio al ajustar temporalmente la frecuencia de sincronización en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-537">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="6f0a7-538">Mejora de la sincronización y la estabilidad del servicio al diferir temporalmente la descarga de archivos e imágenes incrustados en los blocs de notas en línea hasta que el usuario navegue a la página en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-538">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="6f0a7-539">Se obtiene una mejora de la sincronización y la estabilidad del servicio al deshabilitar temporalmente la grabación de vídeo en la aplicación en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-539">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="6f0a7-540">La medida no afecta a los blocs de notas locales.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-540">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="6f0a7-541">Mejora de la sincronización y la estabilidad del servicio al reducir temporalmente el tamaño máximo de nuevos datos adjuntos insertados a 50 MB en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-541">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="6f0a7-542">Si los archivos superan este límite, los usuarios tendrán la opción de cargar el archivo a OneDrive e insertar un vínculo en OneNote.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-542">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="6f0a7-543">Outlook</span><span class="sxs-lookup"><span data-stu-id="6f0a7-543">Outlook</span></span>

- <span data-ttu-id="6f0a7-544">Se ha corregido un problema que provocaba que el ancho del panel de carpetas cambiara inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-544">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="6f0a7-545">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al intentar abrir archivos .msg y .oft después de una actualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-545">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="6f0a7-546">Se ha corregido un problema que hacía que los usuarios vieran truncado el cuerpo del mensaje al reenviar mensajes HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-546">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="6f0a7-547">Esta actualización corrige un problema en el que con Microsoft Outlook no muestra la etiqueta de confidencialidad actual al ver o redactar mensajes.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-547">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="6f0a7-548">Se ha corregido un problema que provocaba que los usuarios no pudieran dirigir mensajes de correo electrónico a una lista de distribución personal.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-548">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6f0a7-549">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6f0a7-549">PowerPoint</span></span>

- <span data-ttu-id="6f0a7-550">Se ha corregido un problema para transmitir mensajes correctos para los usuarios que abren una copia de un archivo con comentarios mejorados.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-550">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="6f0a7-551">Word</span><span class="sxs-lookup"><span data-stu-id="6f0a7-551">Word</span></span>

- <span data-ttu-id="6f0a7-552">Se ha corregido el problema por el que Access y Publisher podrían no iniciarse correctamente en función de los idiomas que se hubieran instalado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-552">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="6f0a7-553">Se ha corregido un problema con la característica Comparar de los documentos protegidos para la edición.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-553">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="6f0a7-554">Se ha corregido un problema al combinar 2 documentos en uno.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-554">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6f0a7-555">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6f0a7-555">Office Suite</span></span>

- <span data-ttu-id="6f0a7-556">Esta es una corrección para que la aplicación de Project no bloquee la red cuando el archivo se almacena en caché en el cliente.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-556">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="6f0a7-557">Hemos resuelto el problema por el que una operación interna producía una excepción en caso de error en lugar de registrarlo y continuar.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-557">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="6f0a7-558">Los usuarios afectados ya no serán bloqueados para recibir actualizaciones.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-558">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="6f0a7-559">Este cambio garantiza que el contorno Esbozado funcione correctamente en la cinta de opciones.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-559">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="6f0a7-560">Se ha corregido un problema al abrir archivos de ubicaciones locales con algunas configuraciones de proxy específicas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-560">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="6f0a7-561">Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-561">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="6f0a7-562">Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-562">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="6f0a7-563">Esta actualización corrige un problema en Microsoft Word por el que el texto que supera los 255 caracteres insertados durante la aplicación de una etiqueta de confidencialidad no se pudiese identificar y quitar posteriormente cambiando o quitando la etiqueta si la directiva de etiqueta aplicó un encabezado, un pie de página o una marca de agua.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-563">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="6f0a7-564">Se ha corregido un problema que elimina bloqueos durante las sesiones de entrega de Office y se ha mejorado la fiabilidad de la experiencia del usuario.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-564">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="6f0a7-565">Este error actualiza el extremo de la URL del servicio de configuración mejorada (ECS).</span><span class="sxs-lookup"><span data-stu-id="6f0a7-565">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="6f0a7-566">Llamar a este punto de conexión más reciente tiene una tasa de éxito superior para capturar desde ECS.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-566">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2002-april-14"></a><span data-ttu-id="6f0a7-568">Versión 2002: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="6f0a7-568">Version 2002: April 14</span></span>
<span data-ttu-id="6f0a7-569">*Versión 2002 (compilación 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="6f0a7-569">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="6f0a7-570">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-570">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="6f0a7-571">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="6f0a7-571">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="6f0a7-572">Excel</span><span class="sxs-lookup"><span data-stu-id="6f0a7-572">Excel</span></span>

- <span data-ttu-id="6f0a7-573">**Escriba una fórmula que devuelva varios valores:** Escriba rápidamente una fórmula que devuelva múltiples valores y se derramarán automáticamente en las celdas vecinas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-573">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="6f0a7-574">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-574">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="6f0a7-575">**Seis potentes funciones:** Seis potentes funciones: Hemos agregado seis nuevas funciones para mejorar las hojas de cálculo: FILTRAR, ORDENAR, ORDENARPOR, UNICOS, SECUENCIA y MATRIZALEAT.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-575">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="6f0a7-576">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-576">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="6f0a7-577">**Busque a la izquierda, busque a la derecha... BUSCARX ya está aquí**: fila por fila, busque lo que necesite en una tabla o un rango con BUSCARX.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-577">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  [<span data-ttu-id="6f0a7-578">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-578">Learn more</span></span>](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6f0a7-580">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6f0a7-580">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6f0a7-581">Excel</span><span class="sxs-lookup"><span data-stu-id="6f0a7-581">Excel</span></span>

- <span data-ttu-id="6f0a7-582">Excel se bloqueaba en ciertos casos cuando se volvía a abrir un libro incrustado en Word o PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-582">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="6f0a7-583">Cuando guarda como un archivo CSV, Excel podía combinar todas las columnas en una sola columna en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-583">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="6f0a7-584">Usar Range.ClearContents en un rango de una hoja protegida podía tardar más de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-584">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="6f0a7-585">Corregido un problema con la escala de texto en los controles de formulario cuando se mostraba en la Vista previa de impresión.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-585">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="6f0a7-586">Las macros de VBA que interactúan con la cinta de opciones se pueden ejecutar con ScreenUpdating establecido en True inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-586">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="6f0a7-587">Corregido un problema por el que los enlaces externos no se actualizaban al rellenar (rellenad hacia abajo, rellenar en otros, etc.) si el libro de origen estaba cerrado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-587">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="6f0a7-588">El uso de Application.Evaluate de VBA no funcionaba para funciones definidas por el usuario en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-588">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="6f0a7-589">Corregido un problema de rendimiento al crear gráficos a partir de plantillas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-589">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="6f0a7-590">Outlook</span><span class="sxs-lookup"><span data-stu-id="6f0a7-590">Outlook</span></span>

- <span data-ttu-id="6f0a7-591">Corregido un problema que hacía que el encabezado de grupo se expandiera de forma inesperada en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-591">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="6f0a7-592">Corregido un problema que provocaba que los usuarios experimentaran un bloqueo al seleccionar determinados resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-592">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="6f0a7-593">Corregido un problema que causaba que los usuarios experimentaran ocasionalmente un bloqueo al usar el botón X de su ratón.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-593">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="6f0a7-594">Corregido un problema que hacía que el botón Guardar en la nube faltara en las Herramientas de datos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-594">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6f0a7-595">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6f0a7-595">PowerPoint</span></span>

- <span data-ttu-id="6f0a7-596">Se ha mejorado un escenario de copiar y pegar: al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-596">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="6f0a7-597">Proyecto</span><span class="sxs-lookup"><span data-stu-id="6f0a7-597">Project</span></span>

- <span data-ttu-id="6f0a7-598">Corregido un problema por el que Project puede bloquearse al guardar proyectos creados con versiones anteriores de Project.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-598">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="6f0a7-599">Corregido un problema que hace que el evento ProjectBeforeTaskChange no detecte cuándo se ha desactivado o activado una tarea mediante el botón Desactivar.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-599">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="6f0a7-600">Word</span><span class="sxs-lookup"><span data-stu-id="6f0a7-600">Word</span></span>

- <span data-ttu-id="6f0a7-601">Corregido un problema que causaba que los usuarios experimentaran ocasionalmente un bloqueo al usar el botón X de su ratón.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-601">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="6f0a7-602">Corregido un problema con el ajuste de texto en una tabla.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-602">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="6f0a7-603">Corregido un problema donde al insertar líneas horizontales no eran más cortas ni centradas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-603">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-march-10"></a><span data-ttu-id="6f0a7-605">Versión 2002: 10 de marzo</span><span class="sxs-lookup"><span data-stu-id="6f0a7-605">Version 2002: March 10</span></span>
<span data-ttu-id="6f0a7-606">*Versión 2002 (compilación 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="6f0a7-606">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="6f0a7-607">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-607">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="6f0a7-609">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="6f0a7-609">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="6f0a7-610">Access</span><span class="sxs-lookup"><span data-stu-id="6f0a7-610">Access</span></span>

- <span data-ttu-id="6f0a7-611">**Buscar tablas vinculadas rápidamente:** nuestro nuevo cuadro de búsqueda hace que buscar tablas vinculadas sea mucho más sencillo.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-611">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="6f0a7-612">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-612">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="6f0a7-613">Excel</span><span class="sxs-lookup"><span data-stu-id="6f0a7-613">Excel</span></span>

- <span data-ttu-id="6f0a7-614">**Logre la atención de sus colegas con** @menciones:\@ use @menciones en los comentarios para avisar a los compañeros de trabajo cuando necesite su participación.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-614">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="6f0a7-615">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-615">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="6f0a7-616">**Encuentre lo que busca:** Realice búsquedas de comandos, personas, archivos, fotos, artículos en la web y más.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-616">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="6f0a7-617">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-617">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="6f0a7-618">**Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su libro.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-618">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="6f0a7-619">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-619">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="6f0a7-620">**Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-620">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="6f0a7-621">**Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. </span><span class="sxs-lookup"><span data-stu-id="6f0a7-621">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="6f0a7-622">**Resalte lo que queda por hacer**: seleccione Resolver para contraer los comentarios y hacer que resalten los elementos abiertos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-622">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="6f0a7-623">**Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-623">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="6f0a7-624">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-624">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="6f0a7-625">**Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los demás.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-625">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="6f0a7-626">**Complemento del visualizador de datos:** Crear rápidamente diagramas de flujo de Visio desde Excel.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-626">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="6f0a7-627">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-627">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="6f0a7-628">**Lea y responda sobre la marcha:** responda a los comentarios y las menciones directamente desde el correo electrónico, sin abrir el libro.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-628">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="6f0a7-629">**Obtenga estadísticas en el libro:** Estadísticas del libro da información general sobre el contenido de un libro, para ayudarle a descubrir más fácilmente su contenido.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-629">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="6f0a7-630">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-630">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="6f0a7-631">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-631">Find them at Insert > Icons.</span></span> [<span data-ttu-id="6f0a7-632">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-632">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="6f0a7-633">Outlook</span><span class="sxs-lookup"><span data-stu-id="6f0a7-633">Outlook</span></span>

- <span data-ttu-id="6f0a7-634">**Conecte su red de LinkedIn con Outlook:** Conecte de forma segura su cuenta de LinkedIn con su cuenta de Microsoft para ver la información de los perfiles de LinkedIn directamente en las tarjetas personales.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-634">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="6f0a7-635">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-635">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="6f0a7-p158">**Todas las opciones de cifrado en un solo lugar:** vaya a Opciones > Cifrar para elegir cómo proteger su mensaje de correo. [Más información](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-p158">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="6f0a7-638">**Insertar el menú de vínculos en Outlook inserta un vínculo con el permiso definido por el administrador de inquilinos:** un vínculo desde Insertar vínculo utilizado recientemente en Outlook insertaba un vínculo que solo funcionaba para los usuarios que ya tenían permisos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-638">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="6f0a7-639">A menudo esto causaba un intercambio continuo de mensajes de correo electrónico entre los usuarios que pedían acceso a un documento.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-639">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="6f0a7-640">Hemos actualizado esta experiencia para que ahora el vínculo se inserte con el permiso predeterminado establecido por el administrador de inquilinos. Para MSIT se trata de "la organización puede editar", por lo que todos los usuarios internos que reciban un vínculo compartido de esta manera podrán acceder a él.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-640">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="6f0a7-641">**Busque incluso con errores ortográficos o tipográficos:** Outlook encontrará lo que busca, aunque no coincida con la forma exacta en que lo escribió.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-641">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="6f0a7-642">**Ahora es más fácil detectar correos de suplantación de identidad:** los mensajes de correo no deseado y de suplantación de identidad tienen un aspecto diferente para que pueda identificarlos y eliminarlos fácilmente en la bandeja de entrada.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-642">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="6f0a7-643">**Protección avanzada frente a ataques**: con la Protección contra amenazas avanzada de Office 365, estará protegido frente a ataques mediante hipervínculos en asuntos de correos electrónicos, mensajes adjuntos, mensajes firmados, rutas de red, etc.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-643">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="6f0a7-644">**Deja que lo dibuje:** garabatee sobre las imágenes o agregue un Lienzo de dibujo para enviar sus pensamientos con la entrada de lápiz.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-644">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="6f0a7-645">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-645">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="6f0a7-646">**Ver mensajes relevantes en los resultados de búsqueda:** Outlook analiza los términos de búsqueda y muestra los mensajes de correo electrónico más relevantes en la parte superior de los resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-646">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="6f0a7-647">También verá todos los resultados ordenados por fecha en la sección de Resultados principales.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-647">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="6f0a7-648">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-648">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="6f0a7-649">**Obtenga sugerencias de ubicaciones:** Empiece a escribir en Ubicación cuando programe citas y reuniones, Outlook le sugerirá salas, direcciones y otros lugares recientes.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-649">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="6f0a7-650">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-650">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="6f0a7-651">**Encajar más mensajes en la pantalla:** seleccione Ver > Usar espaciado más estrecho para ajustar el espaciado entre mensajes.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-651">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="6f0a7-652">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-652">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="6f0a7-653">**Ver los mensajes bajo otra luz:** use el botón sol/luna para cambiar entre fondos claros y oscuros en el panel de lectura.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-653">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="6f0a7-654">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-654">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="6f0a7-655">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-655">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="6f0a7-656">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-656">Find them at Insert > Icons.</span></span> [<span data-ttu-id="6f0a7-657">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-657">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="6f0a7-658">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6f0a7-658">PowerPoint</span></span>

- <span data-ttu-id="6f0a7-659">**Colaboración rápida en tiempo real en PowerPoint:** colaboración rápida en tiempo real en PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6f0a7-659">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="6f0a7-660">**Nuevas herramientas de revisión:** no se preocupe de las palabras.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-660">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="6f0a7-661">Ahora en PowerPoint se ofrecen sugerencias de gramática y escritura.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-661">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="6f0a7-662">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-662">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="6f0a7-663">**Transcripción y subtítulos en directo:** las palabras del moderador se muestran automáticamente en la pantalla como subtítulos o se traducen en el idioma que prefiera.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-663">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="6f0a7-664">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-664">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="6f0a7-p168">**Usted calcula y nosotros le damos formato:** hemos convertido las expresiones matemáticas escritas a mano en caracteres estándar. Simplemente elija Entrada de lápiz a matemáticas y seleccione las notas escritas a mano para empezar. [Más información](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-p168">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="6f0a7-668">**Encuentre lo que busca:** use el cuadro de búsqueda para buscar texto, comandos, ayuda y mucho más.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-668">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="6f0a7-669">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-669">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="6f0a7-670">**Encuentre los títulos de diapositivas que faltan y escríbalos**: los títulos de diapositivas añaden fuerza a su discurso y permiten que las diapositivas sean accesibles para los usuarios de todas las capacidades.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-670">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="6f0a7-671">El comprobador de accesibilidad le muestra dónde faltan títulos para que pueda agregarlos en el momento.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-671">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="6f0a7-672">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-672">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="6f0a7-673">**Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su presentación.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-673">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="6f0a7-674">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-674">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="6f0a7-675">**Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-675">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="6f0a7-676">**Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. </span><span class="sxs-lookup"><span data-stu-id="6f0a7-676">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="6f0a7-677">**Guarde una ilustración como SVG:** guarde un gráfico, una forma o una ilustración como un gráfico vectorial escalable, que se puede cambiar de tamaño sin perder calidad de imagen.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-677">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="6f0a7-678">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-678">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="6f0a7-679">**Impresión de números de diapositiva en documentos:** los números de diapositiva se incluyen automáticamente en los documentos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-679">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="6f0a7-680">Ahora es usted quien decide si los deja o los quita.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-680">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="6f0a7-681">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-681">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="6f0a7-682">**Repetición de entrada de lápiz:** cuando haya entradas de lápiz en sus diapositivas, aplique una animación de reproducción para reproducir el dibujo real de la entrada de lápiz durante la presentación con diapositivas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-682">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="6f0a7-683">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-683">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="6f0a7-684">**Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-684">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="6f0a7-685">**Optimizar la presentación para todos:** el comprobador de accesibilidad le ayuda a organizar los objetos de las diapositivas pensando en los lectores de pantalla.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-685">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="6f0a7-686">**Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los usuarios.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-686">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="6f0a7-687">**Una experiencia de vídeo más segura:** las mejoras de seguridad hacen que la experiencia de vídeo en línea sea más segura.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-687">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="6f0a7-688">**¿Para que reinventar lo que puede reutilizar?:** ahorre tiempo usando de nuevo las diapositivas que haya creado o que otros usuarios han compartido con usted.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-688">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="6f0a7-689">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-689">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="6f0a7-690">**Transforme la entrada de lápiz en formas, texto o matemáticas en PowerPoint para Office 365:** convierta la entrada de lápiz en forma libre a formas, textos o expresiones matemáticas de Office en un par de trazos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-690">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="6f0a7-691">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-691">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="6f0a7-692">**Entrada de tinta para magníficas diapositivas:** convierta el texto de tinta en formas estándar y texto y obtenga ideas de diseño inteligente del Diseñador de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-692">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="6f0a7-693">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-693">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="6f0a7-694">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-694">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="6f0a7-695">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-695">Find them at Insert > Icons.</span></span> [<span data-ttu-id="6f0a7-696">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-696">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="6f0a7-697">Visio</span><span class="sxs-lookup"><span data-stu-id="6f0a7-697">Visio</span></span>

- <span data-ttu-id="6f0a7-698">**Vuelva a la escena del crimen:** use las nuevas plantillas Evidencia, Interior y Exterior en la plantilla Investigación de Escenas de Delitos para recrear con detalle escenarios de delitos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-698">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="6f0a7-699">**Cree diagramas de Visio elegantes en Excel:** cree un diagrama de flujo o un organigrama con solo escribir datos en una hoja de cálculo.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-699">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="6f0a7-700">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-700">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="6f0a7-701">Word</span><span class="sxs-lookup"><span data-stu-id="6f0a7-701">Word</span></span>

- <span data-ttu-id="6f0a7-702">**El Editor para currículum vítae incorpora el Asistente para currículum vítae de LinkedIn:** el Editor para currículum vítae ofrece una selección de comprobaciones gramaticales y de estilo especialmente adaptadas a los currículums, para que el texto sea más preciso y profesional.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-702">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="6f0a7-703">**Se ha corregido un problema relacionado con los documentos causados por la combinación de objetos 3D:** corrige un problema de daños en un documento producido por la combinación de objetos 3D.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-703">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="6f0a7-704">**Encuentre lo que busca:** use el cuadro de búsqueda para buscar texto, comandos, ayuda y mucho más.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-704">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="6f0a7-705">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-705">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="6f0a7-706">**Colaborando a todo color:** los comentarios y los cambios están codificados por color según la persona que contribuya, por lo que es fácil distinguir entre sus colaboradores.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-706">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="6f0a7-707">**Editar documentos habilitados para macros de forma conjunta:** guarde sus archivos .docm en OneDrive para la Empresa y edítelos con sus colaboradores en tiempo real.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-707">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="6f0a7-708">**Mejoras en la coautoría:** mejora del rendimiento de Word en coautoría en documentos con marcas de revisión.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-708">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="6f0a7-709">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-709">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="6f0a7-710">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-710">Find them at Insert > Icons.</span></span> [<span data-ttu-id="6f0a7-711">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-711">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="6f0a7-712">**Otros usuarios verán los cambios rápidamente**: las mejoras en la coautoría significan que los colaboradores podrán ver los cambios más rápido que nunca.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-712">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="6f0a7-713">**Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su documento.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-713">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="6f0a7-714">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-714">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="6f0a7-715">**Borrar con precisión:** elija entre dos tamaños de borrador para arreglar pequeñas imperfecciones de la entrada de lápiz.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-715">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="6f0a7-716">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-716">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="6f0a7-717">**Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-717">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="6f0a7-718">**Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. </span><span class="sxs-lookup"><span data-stu-id="6f0a7-718">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="6f0a7-719">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-719">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="6f0a7-720">**Mejoras en la coautoría:** mejora de la confiabilidad de la coautoría.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-720">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="6f0a7-721">**Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-721">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="6f0a7-722">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-722">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="6f0a7-723">**Convertir los archivos para mejorar la accesibilidad**: Actualice los archivos al formato moderno para que sean más accesibles para todos los usuarios.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-723">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="6f0a7-724">**Una experiencia de vídeo más segura:** las mejoras de seguridad hacen que la experiencia de vídeo en línea sea más segura.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-724">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="6f0a7-725">Más información</span><span class="sxs-lookup"><span data-stu-id="6f0a7-725">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6f0a7-728">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6f0a7-728">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="6f0a7-729">Acceso</span><span class="sxs-lookup"><span data-stu-id="6f0a7-729">Access</span></span>

- <span data-ttu-id="6f0a7-730">Esta actualización corrige un problema en Microsoft Access que puede causar el error "La consulta está dañada" cuando se ejecuta una consulta de actualización o cuando se usa una instrucción UPDATE en SQL.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-730">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="6f0a7-731">Esta actualización corrige un problema que puede hacer que Microsoft Access no identifique una Columna de identidad en una tabla vinculada de SQL Server, lo que puede provocar que las filas aparezcan como eliminadas de forma incorrecta.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-731">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="6f0a7-732">Esta actualización corrige un problema por el que al usar un objeto de grabación de ADODB</span><span class="sxs-lookup"><span data-stu-id="6f0a7-732">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="6f0a7-733">en el código de VB, se puede notificar un error incorrectamente.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-733">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="6f0a7-734">Las plantillas de Access ya no deberían causar errores en columnas de datos adjuntos en una base de datos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-734">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="6f0a7-735">Después de crear la instancia de una plantilla, ahora debería poder agregar un campo de datos adjuntos a la base de datos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-735">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="6f0a7-736">Excel</span><span class="sxs-lookup"><span data-stu-id="6f0a7-736">Excel</span></span>

- <span data-ttu-id="6f0a7-737">Corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-737">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="6f0a7-738">Este cambio evita un problema con ciertos controladores de gráficos Intel al aprovechar el procesamiento del software.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-738">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="6f0a7-739">Se ha corregido un problema que causaba que algunos usuarios experimentasen bloqueos al convertir texto en columnas con celdas que tienen una matriz derramada.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-739">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="6f0a7-740">Esta actualización corrige un problema que causaba que la barra de fórmulas mostrara texto en una fuente diferente a la esperada.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-740">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="6f0a7-741">La funcionalidad de Texto a columna puede fallar en algunas configuraciones regionales.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-741">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="6f0a7-742">Es posible que los usuarios vean un error si acceden a un rango con nombre oculto.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-742">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="6f0a7-743">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-743">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="6f0a7-744">Corregimos un problema en el que al seleccionar una celda luego de desplazar, podía resultar en la selección de la celda incorrecta.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-744">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="6f0a7-745">Excel puede tener problemas al editar un archivo protegido desde una red compartida no confiable.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-745">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="6f0a7-746">La funcionalidad de Texto a columna puede fallar en algunas localizaciones.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-746">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="6f0a7-747">Es posible que los usuarios vean un error si acceden a un rango con nombre oculto.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-747">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="6f0a7-748">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-748">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="6f0a7-749">Se ha corregido un problema que algunos usuarios pudieron sufrir con objetos incrustados y vinculados (OLE).</span><span class="sxs-lookup"><span data-stu-id="6f0a7-749">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="6f0a7-750">Se ha corregido el botón derecho en el menú de gráficos dinámicos para habilitar la opción de mostrar los detalles.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-750">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="6f0a7-751">Se ha resuelto un problema que puede haber causado un bloqueo al buscar archivos recientes cuando no hay ningún libro de trabajo abierto.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-751">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="6f0a7-752">Se ha corregido un problema por el que algunos usuarios pueden haber visto varias ventanas emergentes cuando hubiera vínculos externos presentes en el libro.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-752">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="6f0a7-753">Se ha corregido un problema por el que los comandos de comentario en el menú contextual no aparecían.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-753">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="6f0a7-754">Se ha resuelto un problema en el que no se cargaba la personalización de cinta de opciones al abrir un libro insertado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-754">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="6f0a7-755">Se ha solucionado un problema por el que las funciones CUBEVALUE a veces daban un resultado incorrecto.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-755">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="6f0a7-756">Outlook</span><span class="sxs-lookup"><span data-stu-id="6f0a7-756">Outlook</span></span>

- <span data-ttu-id="6f0a7-757">Corregido un problema que causó un bloqueo en la experiencia de los comentarios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-757">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="6f0a7-758">Corregido un problema que hacía que los usuarios no tuvieran respuesta de Outlook al recuperar la configuración de la nube.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-758">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="6f0a7-759">Se ha corregido un problema que provocaba que el cuadro de búsqueda estuviera mal alineado en modo de PPP alto.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-759">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="6f0a7-760">Corregido un problema que hacía que los usuarios observaran una fuga de memoria en el proceso de Outlook.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-760">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="6f0a7-761">Corregido un problema que hacía que los usuarios vieran correos electrónicos enviados a una dirección que no coincidía con la dirección SMTP mostrada en algunas circunstancias.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-761">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="6f0a7-762">Este cambio restaura la capacidad de ver sujetos de varias líneas en el encabezado del mensaje.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-762">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="6f0a7-763">Se ha corregido un problema que podía impedir que los archivos se guardaran en una ubicación de WebDAV.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-763">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="6f0a7-764">Corregido un problema con la selección del algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-764">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="6f0a7-765">Corregido un problema que provocaba que las aplicaciones de terceros no pudiesen enviar correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-765">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="6f0a7-766">Se ha solucionado un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "ok" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-766">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="6f0a7-767">Se ha corregido un problema que provocaba que los usuarios sufrieran un bloqueo durante la creación del perfil.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-767">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="6f0a7-768">Se ha corregido un problema por el que Outlook sincronizaba inesperadamente todo el correo, incluso cuando el deslizador de sincronización estaba configurado en un ajuste menor.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-768">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="6f0a7-769">Se corrigió un problema por el que los usuarios con el tema negro veían la lista desplegable "De" con un texto blanco sobre un fondo blanco.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-769">Addressed an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="6f0a7-770">Se ha corregido un problema que provocaba que los usuarios experimentaran un error al cancelar la configuración de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-770">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="6f0a7-771">Corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-771">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="6f0a7-772">Se ha corregido un problema que hacía que la opción deshabilitar el resaltado de elementos marcados no se pudiera respetar en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-772">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="6f0a7-773">Corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al abrir el cuadro de diálogo Reglas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-773">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="6f0a7-774">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-774">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="6f0a7-775">Corregido un problema que causaba una fuga de memoria en sesiones de Outlook muy largas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-775">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="6f0a7-776">Corregido un problema que podría resultar en un bloqueo del equipo cuando se veía el mismo elemento en varias ventanas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-776">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="6f0a7-777">Corregido un problema que hacía que los usuarios vieran un retraso notable al interactuar con sus carpetas de buzón de correo a través de métodos abreviados de teclado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-777">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="6f0a7-778">Se ha corregido un problema que provocaba que los usuarios no pudieran abrir algunas instancias de los elementos de calendario periódicos.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-778">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="6f0a7-779">Corregido un problema que provocaba que los usuarios con buzones en servidores de Exchange 2010 sufrieran problemas al agregar archivos adjuntos a elementos de calendario.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-779">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="6f0a7-780">Se ha corregido un problema que provocaba que los usuarios experimentaran problemas al responder a los mensajes firmados digitalmente.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-780">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="6f0a7-781">Se ha corregido un problema que provocaba que el campo Ubicación en las reuniones se actualizara de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-781">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="6f0a7-782">Corregido un problema que causaba que las comas en el campo de Ubicación de una reunión se convirtieran en punto y coma.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-782">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="6f0a7-783">Corregido un problema que provocaba que la ubicación de una reunión se añadiera a la reunión de forma inesperada después de haberla borrado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-783">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="6f0a7-784">Corregidos problemas relacionados con las reuniones y las citas establecidas en la zona horaria de la Brasil.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-784">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="6f0a7-785">Se corrigió un problema por el que se enviaban inesperadamente mensajes de correos electrónicos al presionar la tecla "S" después de cerrar el panel del comprobador de accesibilidad.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-785">Addressed an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="6f0a7-786">Esto actualiza la lógica de bloqueo de adjuntos en Outlook para bloquear también los adjuntos de Python.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-786">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="6f0a7-787">Se ha corregido un problema que provocaba que los complementos web accedieran a los mensajes administrados con derechos digitales.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-787">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="6f0a7-788">Se ha corregido un problema que provocaba que los usuarios sufrieran un bloqueo durante la creación del perfil.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-788">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="6f0a7-789">Corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-789">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6f0a7-790">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6f0a7-790">PowerPoint</span></span>

- <span data-ttu-id="6f0a7-791">Se ha corregido un problema con el método Shape.Paste: cuando el usuario copiaba y pegaba la forma con el método Shape.Paste, se cambiaba la selección a la forma pegada.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-791">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="6f0a7-792">Se ha corregido un problema que podía bloquear el equipo al usar el menú contextual en comentarios PPT heredados.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-792">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="6f0a7-793">Project</span><span class="sxs-lookup"><span data-stu-id="6f0a7-793">Project</span></span>

- <span data-ttu-id="6f0a7-794">Identificamos un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de solo lectura.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-794">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="6f0a7-795">Se ha corregido un problema por el que el 100 % de las tareas de tipo duración fija podían tener un cálculo del porcentaje incorrecto con menos del 100 % completado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-795">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="6f0a7-796">Se corrigió un problema en el que las fechas de las tareas de resumen no se calculaban siempre correctamente.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-796">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="6f0a7-797">Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-797">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="6f0a7-798">Word</span><span class="sxs-lookup"><span data-stu-id="6f0a7-798">Word</span></span>

- <span data-ttu-id="6f0a7-799">Corregido un problema ocasional en el que al guardar un archivo existente siempre aparece el cuadro de diálogo Guardar como, pero el archivo nunca se guarda.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-799">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="6f0a7-800">El organizador de bloques de creación puede mostrar una alerta no válida: "Ha modificado estilos, bloques de creación".</span><span class="sxs-lookup"><span data-stu-id="6f0a7-800">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="6f0a7-801">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6f0a7-801">Office Suite</span></span>

- <span data-ttu-id="6f0a7-802">Este cambio corrige el procesamiento lento de algunos gráficos de dispersión con marcadores.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-802">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="6f0a7-803">Este cambio resuelve problemas con adaptadores gráficos que aprovechan la GPU integrada de Intel.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-803">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="6f0a7-804">Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa solo funciona la primera vez que se establece. Ahora, la corrección permite establecer una fecha límite relativa para las actualizaciones posteriores.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-804">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="6f0a7-805">Se ha corregido un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-805">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="6f0a7-806">Corrige un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-806">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-february-11"></a><span data-ttu-id="6f0a7-808">Versión 1908: 11 de febrero</span><span class="sxs-lookup"><span data-stu-id="6f0a7-808">Version 1908: February 11</span></span>
<span data-ttu-id="6f0a7-809">*Versión 1908 (Compilación 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="6f0a7-809">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="6f0a7-810">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-810">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6f0a7-812">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6f0a7-812">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6f0a7-813">Excel</span><span class="sxs-lookup"><span data-stu-id="6f0a7-813">Excel</span></span>

- <span data-ttu-id="6f0a7-814">Esta actualización corrige un problema que provoca un error siempre que se utilizaba VBA para agregar una imagen al encabezado o pie de página de un gráfico.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-814">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="6f0a7-815">Se ha corregido un problema que hacía que el borde de un control de cuadro de grupo no estuviera visible en la vista previa de impresión o al imprimirlo.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-815">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="6f0a7-816">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-816">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="6f0a7-817">Se ha corregido un problema por el que el tamaño de archivo de las imágenes en los encabezados del gráfico aumentaba cuando se guardaba el libro que contenía el gráfico.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-817">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="6f0a7-818">Se ha corregido un problema que provoca la corrupción de caracteres DBCS en los libros con referencias cruzadas manteniendo los rangos de selección sincronizados con el libro con referencias cruzadas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-818">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="6f0a7-819">Se ha corregido un problema en el que los controles de casilla podían reducirse al usar el autoajuste para ajustar el alto de fila.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-819">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="6f0a7-820">Outlook</span><span class="sxs-lookup"><span data-stu-id="6f0a7-820">Outlook</span></span>

- <span data-ttu-id="6f0a7-821">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-821">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="6f0a7-822">Se ha corregido un problema que provocaba que los usuarios experimentaran errores de sincronización al procesar mensajes de conflicto.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-822">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="6f0a7-823">Se ha corregido un problema que provocaba que los usuarios experimentaran un error en la pantalla de carga del perfil al iniciar Outlook.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-823">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="6f0a7-824">Se ha corregido un problema que provocaba que los usuarios viesen bloqueos intermitentes al cambiar de vista.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-824">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="6f0a7-825">Se ha corregido un problema que causaba que los usuarios sufrieran un error al visualizar más de 30 calendarios en un entorno Citrix.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-825">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="6f0a7-826">[Aquí](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) está la KB individual, donde se ha documentado esto para versiones anteriores.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-826">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="6f0a7-827">Corrige un problema que provocaba que los usuarios tuvieran problemas al intentar sincronizar carpetas del calendario compartido con el OST, lo que producía errores en los permisos al tratar de interactuar con estas carpetas.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-827">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="6f0a7-828">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6f0a7-828">PowerPoint</span></span>

- <span data-ttu-id="6f0a7-829">Se ha mejorado un escenario de copiar y pegar. Al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-829">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="6f0a7-830">Se ha corregido un problema que producía un rendimiento más lento entre los usuarios de colaboración.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-830">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="6f0a7-831">Se ha corregido un problema que puede producirse cuando un archivo que se abre incrementalmente contiene una diapositiva con más de una secuencia multimedia incrustada.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-831">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="6f0a7-832">Se ha corregido un problema por el que es posible que la barra de mensajes de advertencia de seguridad no aparezca para los complementos en los que no se confía al iniciar PowerPoint por primera vez.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-832">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="6f0a7-833">Project</span><span class="sxs-lookup"><span data-stu-id="6f0a7-833">Project</span></span>

- <span data-ttu-id="6f0a7-834">Se ha corregido un problema en el que el trabajo real puede ser diferente entre el parte de horas y el plan del proyecto debido a que los calendarios de recursos no se actualizan cuando cambia el calendario base.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-834">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="6f0a7-835">Word</span><span class="sxs-lookup"><span data-stu-id="6f0a7-835">Word</span></span>

- <span data-ttu-id="6f0a7-836">Se ha corregido un bloqueo en Word al dejar una API obsoleta.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-836">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6f0a7-837">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6f0a7-837">Office Suite</span></span>

- <span data-ttu-id="6f0a7-838">Este cambio corrige el procesamiento de imágenes después de abrir un archivo dañado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-838">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-january-14"></a><span data-ttu-id="6f0a7-840">Versión 1908: 14 de enero</span><span class="sxs-lookup"><span data-stu-id="6f0a7-840">Version 1908: January 14</span></span>
<span data-ttu-id="6f0a7-841">*Versión 1908 (compilación 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="6f0a7-841">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="6f0a7-842">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6f0a7-842">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6f0a7-844">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6f0a7-844">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6f0a7-845">Excel</span><span class="sxs-lookup"><span data-stu-id="6f0a7-845">Excel</span></span>

- <span data-ttu-id="6f0a7-846">La información clave en holandés para el título del documento ha sido cambiada a Alt-G.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-846">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="6f0a7-847">Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo insertado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-847">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="6f0a7-848">Hubo un problema en el que no se podían seleccionar elementos del cuadro combinado de un formulario de WPF (Windows Presentation Foundation) que fue abierto por un complemento.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-848">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="6f0a7-849">Outlook</span><span class="sxs-lookup"><span data-stu-id="6f0a7-849">Outlook</span></span>

- <span data-ttu-id="6f0a7-850">Se ha corregido un problema por el que los usuarios notaban un retraso evidente al interactuar con sus carpetas de buzón mediante métodos abreviados de teclado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-850">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="6f0a7-851">Corregido un problema que hacía que no se mostraran las sugerencias de política cuando se utilizaba un remitente alternativo.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-851">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="6f0a7-852">Corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-852">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6f0a7-853">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6f0a7-853">PowerPoint</span></span>

- <span data-ttu-id="6f0a7-854">Arreglamos un problema cuando al copiar una diapositiva de una presentación a otra, se pueden crear patrones duplicados.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-854">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="6f0a7-855">Los archivos con nuevos comentarios modernos mostrarán una advertencia amarilla si se abren en una versión no soportada</span><span class="sxs-lookup"><span data-stu-id="6f0a7-855">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="6f0a7-856">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6f0a7-856">Office Suite</span></span>

- <span data-ttu-id="6f0a7-857">Se ha solucionado un problema por el que los mensajes de actualización de Office aparecían en un idioma diferente al esperado.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-857">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="6f0a7-858">En el futuro, los mensajes de actualización de Office coincidirán correctamente con el idioma de visualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-858">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="6f0a7-859">Corregido un problema en el que una actualización no se aplicaría en ciertos casos en los que el usuario no es un administrador y la cuenta del sistema no tenía conectividad de red.</span><span class="sxs-lookup"><span data-stu-id="6f0a7-859">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

> [!NOTE]
> <span data-ttu-id="6f0a7-861">Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="6f0a7-861">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (NO MODIFICAR EL INICIO DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20910|versión-08-diciembre-2008|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20760|versión-10-noviembre-2008|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|versión-13-octubre-2008|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-septiembre-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20988|version-2002-11-agosto|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|version-2002-july-14|)
[//]: # (NO MODIFICAR EL FIN DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
