---
title: Notas de la versión para las versiones de canal empresarial semestral en 2020
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Proporciona a los profesionales de TI las notas de la versión para las versiones del canal semestral de Aplicaciones de Microsoft 365 en 2020.
ms.openlocfilehash: 893b5374a24fefdbe1fbdc7788370dd5a87e0251
ms.sourcegitcommit: 96185aa6c5a06095c58b57ac36cb2800add8bea0
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 01/06/2021
ms.locfileid: "49760704"
---
# <a name="release-notes-for-semi-annual-enterprise-channel"></a><span data-ttu-id="6222e-103">Notas de la versión para el canal semestral para empresas</span><span class="sxs-lookup"><span data-stu-id="6222e-103">Release notes for Semi-Annual Enterprise Channel</span></span>

<span data-ttu-id="6222e-104">Estas notas de la versión proporcionan información sobre las nuevas características y las actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones del canal semestral para empresas para las Aplicaciones de Microsoft 365 para empresas, las Aplicaciones de Microsoft 365 para negocios, y las versiones de suscripción de las aplicaciones de escritorio de Project y Visio.</span><span class="sxs-lookup"><span data-stu-id="6222e-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="6222e-105">Estamos realizando algunos cambios en los canales de actualización de las Aplicaciones de Microsoft 365, incluida la adición de un nuevo canal de actualización (canal empresarial mensual) y el cambio de los nombres de los canales de actualización existentes.</span><span class="sxs-lookup"><span data-stu-id="6222e-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="6222e-106">[Lea este artículo](https://go.microsoft.com/fwlink/p/?linkid=2127441) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="6222e-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="6222e-107">OneNote 2016 ahora se incluirá de forma predeterminada cuando un usuario en el canal empresarial semestral descargue e instale las Aplicaciones de Microsoft 365 en Windows 10 desde el Portal de Office.</span><span class="sxs-lookup"><span data-stu-id="6222e-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-december-08"></a><span data-ttu-id="6222e-109">Versión 2002: 08 de diciembre</span><span class="sxs-lookup"><span data-stu-id="6222e-109">Version 2002: December 08</span></span>
<span data-ttu-id="6222e-110">*Versión 2002 (compilación 12527.21416)*</span><span class="sxs-lookup"><span data-stu-id="6222e-110">*Version 2002 (Build 12527.21416)*</span></span>

<span data-ttu-id="6222e-111">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6222e-113">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-113">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6222e-114">Excel</span><span class="sxs-lookup"><span data-stu-id="6222e-114">Excel</span></span>

- <span data-ttu-id="6222e-115">Interletraje de texto en PowerPoint mejorado cuando el contenido se copia desde Excel y se pega en PowerPoint con la opción Insertar.</span><span class="sxs-lookup"><span data-stu-id="6222e-115">Improved text kerning in PowerPoint when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="6222e-116">Se ha corregido un problema que provocaba que Excel dejara de funcionar durante el recálculo.</span><span class="sxs-lookup"><span data-stu-id="6222e-116">We fixed an issue where Excel would stop working during recalc.</span></span>


- <span data-ttu-id="6222e-117">Se ha corregido un problema que provocaba que el usuario no pudiera abrir el archivo atomsvc (UTF8+BOM) directamente desde SharePoint.</span><span class="sxs-lookup"><span data-stu-id="6222e-117">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="6222e-118">Se ha corregido un problema que impedía cambiar entre la vista previa de la tabla y el editor de consultas en PowerPivot.</span><span class="sxs-lookup"><span data-stu-id="6222e-118">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="6222e-119">Rendimiento mejorado para los archivos que usan muchas de las funciones recientemente publicadas.</span><span class="sxs-lookup"><span data-stu-id="6222e-119">Improved performance for files that are using many of the more recently released functions.</span></span>


### <a name="outlook"></a><span data-ttu-id="6222e-120">Outlook</span><span class="sxs-lookup"><span data-stu-id="6222e-120">Outlook</span></span>

- <span data-ttu-id="6222e-121">Se ha corregido un problema que provocaba que, al configurar OME, se agregaran datos adjuntos extraños en el elemento de correo, que obligaban a Outlook a cifrar el mensaje aunque la opción DecryptAttachmentsForEncryptOnly estuviera configurada en el lado del servicio.</span><span class="sxs-lookup"><span data-stu-id="6222e-121">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though DecryptAttachmentsForEncryptOnly option is setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="6222e-122">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6222e-122">PowerPoint</span></span>

- <span data-ttu-id="6222e-123">Se ha corregido un problema que provocaba que el gráfico de Excel vinculado cambiara incorrectamente a la hoja de Excel cuando el usuario cambiaba la ruta de origen a la carpeta de OneDrive local.</span><span class="sxs-lookup"><span data-stu-id="6222e-123">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


### <a name="project"></a><span data-ttu-id="6222e-124">Project</span><span class="sxs-lookup"><span data-stu-id="6222e-124">Project</span></span>

- <span data-ttu-id="6222e-125">Se ha corregido un problema que provocaba que los proyectos no se pudieran abrir en el cliente de escritorio de Project en Project Web App si la dirección URL terminaba en .com.</span><span class="sxs-lookup"><span data-stu-id="6222e-125">We fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App is the URL ended in .com.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-december-08"></a><span data-ttu-id="6222e-127">Versión 1908: 08 de diciembre</span><span class="sxs-lookup"><span data-stu-id="6222e-127">Version 1908: December 08</span></span>
<span data-ttu-id="6222e-128">*Versión 1908 (compilación 11929.20984)*</span><span class="sxs-lookup"><span data-stu-id="6222e-128">*Version 1908 (Build 11929.20984)*</span></span>

<span data-ttu-id="6222e-129">Las actualizaciones de seguridad se muestran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-129">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-november-10"></a><span data-ttu-id="6222e-130">Versión 2002: 10 de noviembre</span><span class="sxs-lookup"><span data-stu-id="6222e-130">Version 2002: November 10</span></span>
<span data-ttu-id="6222e-131">*Versión 2002 (compilación 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="6222e-131">*Version 2002 (Build 12527.21330)*</span></span>

<span data-ttu-id="6222e-132">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-132">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6222e-134">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-134">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6222e-135">Excel</span><span class="sxs-lookup"><span data-stu-id="6222e-135">Excel</span></span>

- <span data-ttu-id="6222e-136">Se ha corregido un problema que aparecía cuando se configuraba el idioma de Office en español. Este problema provocaba que las listas de validación de datos puedan no mostrar todos los elementos de la lista.</span><span class="sxs-lookup"><span data-stu-id="6222e-136">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="6222e-137">Se ha corregido un problema que podía provocar un bloqueo al actualizar las tablas dinámicas de OLAP.</span><span class="sxs-lookup"><span data-stu-id="6222e-137">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="6222e-138">Se ha corregido un problema por el que algunas funciones podían tener un resultado incorrecto después de cargar un libro.</span><span class="sxs-lookup"><span data-stu-id="6222e-138">Fixed a bug where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="6222e-139">Se ha corregido un problema relacionado con las referencias de complemento de XLAM y los rangos con nombre que cerraba la aplicación de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="6222e-139">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="6222e-140">Se ha corregido un problema que producía que la ejecución de la macro de filtro avanzada mostrara errores incorrectamente.</span><span class="sxs-lookup"><span data-stu-id="6222e-140">Fixed an issue where running the advanced filter macro would incorrectly report errors.</span></span>


### <a name="outlook"></a><span data-ttu-id="6222e-141">Outlook</span><span class="sxs-lookup"><span data-stu-id="6222e-141">Outlook</span></span>

- <span data-ttu-id="6222e-142">Se ha corregido un problema por el que se deshabilitaban de forma inesperada complementos internos cuando se deshabilitaban las experiencias conectadas opcionales.</span><span class="sxs-lookup"><span data-stu-id="6222e-142">We fixed an issue that caused internal add-ins to be unexpectedly disabled when optional connected experiences were disabled.</span></span>


- <span data-ttu-id="6222e-143">Se ha corregido un problema que impedía a los usuarios enviar como (o en nombre de) una lista de distribución oculta para la lista global de direcciones.</span><span class="sxs-lookup"><span data-stu-id="6222e-143">We fixed an issue that caused users to be unable to send as or on behalf of a Distribution List that was hidden from the Global Address List.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-november-10"></a><span data-ttu-id="6222e-145">Versión 1908: 12 de noviembre</span><span class="sxs-lookup"><span data-stu-id="6222e-145">Version 1908: November 10</span></span>
<span data-ttu-id="6222e-146">*Versión 1908 (Build 11929,20300)*</span><span class="sxs-lookup"><span data-stu-id="6222e-146">*Version 1908 (Build 11929.20974)*</span></span>

<span data-ttu-id="6222e-147">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-147">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-october-13"></a><span data-ttu-id="6222e-148">Versión 2002: 13 de octubre</span><span class="sxs-lookup"><span data-stu-id="6222e-148">Version 2002: October 13</span></span>
<span data-ttu-id="6222e-149">*Versión 2002 (Compilación 12527.21104)*</span><span class="sxs-lookup"><span data-stu-id="6222e-149">*Version 2002 (Build 12527.21236)*</span></span>

<span data-ttu-id="6222e-150">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-150">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6222e-152">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-152">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="6222e-153">Acceso</span><span class="sxs-lookup"><span data-stu-id="6222e-153">Access</span></span>

- <span data-ttu-id="6222e-154">Ya no debería recibir un error "La consulta es demasiado compleja" o de recurso del sistema excedido en su versión de 64 bits de Access, siempre y cuando cumpla con las directrices y requisitos de la base de datos de Access.</span><span class="sxs-lookup"><span data-stu-id="6222e-154">You should no longer receive a "Query is too complex" or a system resource exceeded error on your 64-bit version of Access, as long as you are meeting Access database guidelines and requirements.</span></span>


- <span data-ttu-id="6222e-155">Una vez que decida usar nuestra característica de filtro después de nuestro diseñador de consultas, la base de datos ya no debería bloquearse.</span><span class="sxs-lookup"><span data-stu-id="6222e-155">Once you decide to use our filter feature after our query designer, your database should no longer crash.</span></span> <span data-ttu-id="6222e-156">Compruebe lo que corresponda.</span><span class="sxs-lookup"><span data-stu-id="6222e-156">Please check accordingly.</span></span>


### <a name="excel"></a><span data-ttu-id="6222e-157">Excel</span><span class="sxs-lookup"><span data-stu-id="6222e-157">Excel</span></span>

- <span data-ttu-id="6222e-158">Se corrigió un problema por el cual los usuarios no podían modificar un filtro de tabla dinámica porque estaba configurado en un valor que ya no estaba presente en una base de datos de Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="6222e-158">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="6222e-159">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6222e-159">PowerPoint</span></span>

- <span data-ttu-id="6222e-160">Las nuevas presentaciones creadas a partir de una plantilla podían heredar una configuración que impedía una buena experiencia de coautoría.</span><span class="sxs-lookup"><span data-stu-id="6222e-160">New presentations created from a template could inherit a setting that prevented  a good co-authoring experience.</span></span> <span data-ttu-id="6222e-161">Esta corrección garantiza que la configuración se haya borrado en este caso.</span><span class="sxs-lookup"><span data-stu-id="6222e-161">This fix ensures that the setting is cleared in this case.</span></span>


### <a name="word"></a><span data-ttu-id="6222e-162">Word</span><span class="sxs-lookup"><span data-stu-id="6222e-162">Word</span></span>

- <span data-ttu-id="6222e-163">Se ha corregido un problema por el que al abrir documentos con saltos de página y columnas, el usuario podía encontrar un mensaje de error, "Ha excedido el número máximo de páginas admitidas por Microsoft Word, o el documento puede estar dañado"</span><span class="sxs-lookup"><span data-stu-id="6222e-163">We fixed an issue which when opening documents with page breaks and columns, user might encountered an error message, " You have exceeded the maximum number of pages allowed by Microsoft Word supported, or the document may be damaged"</span></span>


### <a name="office-suite"></a><span data-ttu-id="6222e-164">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6222e-164">Office Suite</span></span>

- <span data-ttu-id="6222e-165">Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan toners</span><span class="sxs-lookup"><span data-stu-id="6222e-165">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="6222e-166">Cambiar mensaje para mostrar "tóner/Ink Low" & "no tóner/tinta".</span><span class="sxs-lookup"><span data-stu-id="6222e-166">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-october-13"></a><span data-ttu-id="6222e-168">Versión 1908: 8 de octubre</span><span class="sxs-lookup"><span data-stu-id="6222e-168">Version 1908: October 13</span></span>
<span data-ttu-id="6222e-169">*Versión 1908 (compilación 11929.20516)*</span><span class="sxs-lookup"><span data-stu-id="6222e-169">*Version 1908 (Build 11929.20966)*</span></span>

<span data-ttu-id="6222e-170">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-170">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6222e-172">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-172">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="6222e-173">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6222e-173">Office Suite</span></span>

- <span data-ttu-id="6222e-174">Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan toners</span><span class="sxs-lookup"><span data-stu-id="6222e-174">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="6222e-175">Cambiar mensaje para mostrar "tóner/Ink Low" & "no tóner/tinta".</span><span class="sxs-lookup"><span data-stu-id="6222e-175">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-september-08"></a><span data-ttu-id="6222e-177">Versión 2002: 08 de septiembre</span><span class="sxs-lookup"><span data-stu-id="6222e-177">Version 2002: September 08</span></span>
<span data-ttu-id="6222e-178">*Versión 2002 (Compilación 12527.21104)*</span><span class="sxs-lookup"><span data-stu-id="6222e-178">*Version 2002 (Build 12527.21104)*</span></span>

<span data-ttu-id="6222e-179">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-179">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6222e-181">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-181">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6222e-182">Excel</span><span class="sxs-lookup"><span data-stu-id="6222e-182">Excel</span></span>

- <span data-ttu-id="6222e-183">Esto soluciona un problema en el que las conexiones creadas por el proveedor de datos SQL en versiones anteriores de Office establecerían las propiedades de la tabla interna de manera diferente a Office 365.</span><span class="sxs-lookup"><span data-stu-id="6222e-183">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="6222e-184">Esto provocó que el menú desplegable Vista previa de tabla / Editor de consultas se deshabilitara para los archivos con conexiones creadas en versiones anteriores de Office cuando se abrieron con Office 365.</span><span class="sxs-lookup"><span data-stu-id="6222e-184">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>


- <span data-ttu-id="6222e-185">Se corrigió un problema por el cual las entradas manuscritas podrían hacer que Excel dejara de responder.</span><span class="sxs-lookup"><span data-stu-id="6222e-185">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="6222e-186">Outlook</span><span class="sxs-lookup"><span data-stu-id="6222e-186">Outlook</span></span>

- <span data-ttu-id="6222e-187">Corrige un problema que evitaba que los usuarios se conectaran a las carpetas públicas luego de agregar un buzón compartido.</span><span class="sxs-lookup"><span data-stu-id="6222e-187">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


### <a name="office-suite"></a><span data-ttu-id="6222e-188">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6222e-188">Office Suite</span></span>

- <span data-ttu-id="6222e-189">Este cambio resuelve un problema con el cuadro de diálogo de Comprimir imagen, que no retiene determinadas configuraciones de usuario.</span><span class="sxs-lookup"><span data-stu-id="6222e-189">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-september-08"></a><span data-ttu-id="6222e-191">Versión 1908: 08 de septiembre</span><span class="sxs-lookup"><span data-stu-id="6222e-191">Version 1908: September 08</span></span>
<span data-ttu-id="6222e-192">*Versión 1908 (compilación 11929.20946)*</span><span class="sxs-lookup"><span data-stu-id="6222e-192">*Version 1908 (Build 11929.20946)*</span></span>

<span data-ttu-id="6222e-193">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-193">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-august-11"></a><span data-ttu-id="6222e-194">Versión 2002: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="6222e-194">Version 2002: August 11</span></span>
<span data-ttu-id="6222e-195">*Versión 2002 (compilación 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="6222e-195">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="6222e-196">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-196">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6222e-198">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-198">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6222e-199">Excel</span><span class="sxs-lookup"><span data-stu-id="6222e-199">Excel</span></span>

- <span data-ttu-id="6222e-200">Se corrigió un problema por el que no se podía cambiar a la edición de archivos que se han abierto como "recomendado solo lectura".</span><span class="sxs-lookup"><span data-stu-id="6222e-200">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="6222e-201">OneNote</span><span class="sxs-lookup"><span data-stu-id="6222e-201">OneNote</span></span>

- <span data-ttu-id="6222e-202">Se quitaron las llamadas de identidad redundantes para reducir el uso de recursos</span><span class="sxs-lookup"><span data-stu-id="6222e-202">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="6222e-203">Se mejoró la detección del estado de la coautoría para reducir el uso de recursos.</span><span class="sxs-lookup"><span data-stu-id="6222e-203">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="6222e-204">Se mejoró la función de detección de errores y la calidad de la experiencia de sincronización.</span><span class="sxs-lookup"><span data-stu-id="6222e-204">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="6222e-205">Outlook</span><span class="sxs-lookup"><span data-stu-id="6222e-205">Outlook</span></span>

- <span data-ttu-id="6222e-206">Se corrigió un problema que causaba un problema de rendimiento importante al iniciar Outlook en algunos espacios empresariales.</span><span class="sxs-lookup"><span data-stu-id="6222e-206">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="6222e-207">Skype</span><span class="sxs-lookup"><span data-stu-id="6222e-207">Skype</span></span>

- <span data-ttu-id="6222e-208">Se corrigió un problema por el que se podía producir un error al compartir la pantalla en un cliente de Skype Empresarial de 32 bits después de ejecutarlo durante varios días.</span><span class="sxs-lookup"><span data-stu-id="6222e-208">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6222e-209">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="6222e-209">Office Suite</span></span>

- <span data-ttu-id="6222e-210">Se corrigió un problema que se producía al desactivar el autoguardado a través de la directiva de grupo: era posible que algunos documentos no mostraran el contenido más reciente de servidor al abrirse hasta que el usuario hiciera clic en "Actualizaciones disponibles".</span><span class="sxs-lookup"><span data-stu-id="6222e-210">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-august-11"></a><span data-ttu-id="6222e-212">Versión 1908: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="6222e-212">Version 1908: August 11</span></span>
<span data-ttu-id="6222e-213">*Versión 1908 (compilación 11929.20934)*</span><span class="sxs-lookup"><span data-stu-id="6222e-213">*Version 1908 (Build 11929.20934)*</span></span>

<span data-ttu-id="6222e-214">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-214">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1902-august-11"></a><span data-ttu-id="6222e-215">Versión 1902: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="6222e-215">Version 1902: August 11</span></span>
<span data-ttu-id="6222e-216">*Versión 1902 (compilación 11328.20644)*</span><span class="sxs-lookup"><span data-stu-id="6222e-216">*Version 1902 (Build 11328.20644)*</span></span>

<span data-ttu-id="6222e-217">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-217">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-july-14"></a><span data-ttu-id="6222e-220">Versión 2002: 14 de julio</span><span class="sxs-lookup"><span data-stu-id="6222e-220">Version 2002: July 14</span></span>
<span data-ttu-id="6222e-221">*Versión 2002 (compilación 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="6222e-221">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="6222e-222">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-222">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="6222e-224">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="6222e-224">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="6222e-225">Access</span><span class="sxs-lookup"><span data-stu-id="6222e-225">Access</span></span>

- <span data-ttu-id="6222e-226">**Buscar tablas vinculadas rápidamente:** nuestro nuevo cuadro de búsqueda hace que buscar tablas vinculadas sea mucho más sencillo.</span><span class="sxs-lookup"><span data-stu-id="6222e-226">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="6222e-227">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-227">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="6222e-228">Excel</span><span class="sxs-lookup"><span data-stu-id="6222e-228">Excel</span></span>

- <span data-ttu-id="6222e-229">**Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="6222e-229">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="6222e-230">**Complemento del visualizador de datos:** Crear rápidamente diagramas de flujo de Visio desde Excel.</span><span class="sxs-lookup"><span data-stu-id="6222e-230">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="6222e-231">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-231">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="6222e-232">**Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.</span><span class="sxs-lookup"><span data-stu-id="6222e-232">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="6222e-233">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-233">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="6222e-234">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="6222e-234">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="6222e-235">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="6222e-235">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="6222e-236">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="6222e-236">Find them at Insert > Icons.</span></span> [<span data-ttu-id="6222e-237">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-237">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="6222e-238">**Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los demás.</span><span class="sxs-lookup"><span data-stu-id="6222e-238">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="6222e-239">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="6222e-239">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="6222e-240">**Resalte lo que queda por hacer**: seleccione Resolver para contraer los comentarios y hacer que resalten los elementos abiertos.</span><span class="sxs-lookup"><span data-stu-id="6222e-240">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="6222e-241">**Escriba una fórmula que devuelva varios valores:** Escriba rápidamente una fórmula que devuelva múltiples valores y se derramarán automáticamente en las celdas vecinas.</span><span class="sxs-lookup"><span data-stu-id="6222e-241">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="6222e-242">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-242">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="6222e-243">Ver detalles en [entrada de blog](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="6222e-243">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="6222e-244">**Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. </span><span class="sxs-lookup"><span data-stu-id="6222e-244">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="6222e-245">**Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su libro.</span><span class="sxs-lookup"><span data-stu-id="6222e-245">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="6222e-246">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-246">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="6222e-247">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="6222e-247">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="6222e-248">**Encuentre lo que busca:** Realice búsquedas de comandos, personas, archivos, fotos, artículos en la web y más.</span><span class="sxs-lookup"><span data-stu-id="6222e-248">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="6222e-249">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-249">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="6222e-250">**Seis potentes funciones:** Seis potentes funciones: Hemos agregado seis nuevas funciones para mejorar las hojas de cálculo: FILTRAR, ORDENAR, ORDENARPOR, UNICOS, SECUENCIA y MATRIZALEAT.</span><span class="sxs-lookup"><span data-stu-id="6222e-250">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="6222e-251">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-251">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="6222e-252">**Busque a la izquierda, busque a la derecha... BUSCARX ya está aquí**: fila por fila, busque lo que necesite en una tabla o un rango con BUSCARX.</span><span class="sxs-lookup"><span data-stu-id="6222e-252">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="6222e-253">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-253">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="6222e-254">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span><span class="sxs-lookup"><span data-stu-id="6222e-254">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="6222e-255">**Dominar el libro grande:** celdas, fórmulas, gráficos y tablas... Obtenga una instantánea de su libro con estadísticas de libros.</span><span class="sxs-lookup"><span data-stu-id="6222e-255">**Tame your big workbook:** Cells, formulas, charts, tables... get a snapshot of your workbook with Workbook Statistics.</span></span>

- <span data-ttu-id="6222e-256">**Lea y responda sobre la marcha:** responda a los comentarios y las menciones directamente desde el correo electrónico sin abrir el libro.</span><span class="sxs-lookup"><span data-stu-id="6222e-256">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="6222e-257">**Consiga su atención con\@menciones:** use @menciones en los comentarios para avisar a los compañeros de trabajo cuando necesite su participación.</span><span class="sxs-lookup"><span data-stu-id="6222e-257">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="6222e-258">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-258">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a><span data-ttu-id="6222e-259">Outlook</span><span class="sxs-lookup"><span data-stu-id="6222e-259">Outlook</span></span>

- <span data-ttu-id="6222e-260">**Encajar más mensajes en la pantalla:** seleccione Ver > Usar espaciado más estrecho para ajustar el espaciado entre mensajes.</span><span class="sxs-lookup"><span data-stu-id="6222e-260">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="6222e-261">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-261">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="6222e-262">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="6222e-262">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="6222e-263">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="6222e-263">Find them at Insert > Icons.</span></span> [<span data-ttu-id="6222e-264">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-264">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="6222e-265">**Deja que lo dibuje:** garabatee sobre las imágenes o agregue un Lienzo de dibujo para enviar sus pensamientos con la entrada de lápiz.</span><span class="sxs-lookup"><span data-stu-id="6222e-265">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="6222e-266">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-266">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="6222e-267">**Obtenga sugerencias de ubicaciones:** Empiece a escribir en Ubicación cuando programe citas y reuniones, Outlook le sugerirá salas, direcciones y otros lugares recientes.</span><span class="sxs-lookup"><span data-stu-id="6222e-267">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="6222e-268">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-268">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br /><span data-ttu-id="6222e-269">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="6222e-269">See details in [blog post](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span></span>

- <span data-ttu-id="6222e-270">**Protección avanzada frente a ataques**: con la Protección contra amenazas avanzada de Office 365, estará protegido frente a ataques mediante hipervínculos en asuntos de correos electrónicos, mensajes adjuntos, mensajes firmados, rutas de red, etc.</span><span class="sxs-lookup"><span data-stu-id="6222e-270">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="6222e-271">**Insertar el menú de vínculos en Outlook inserta un vínculo con el permiso definido por el administrador de inquilinos:** un vínculo desde Insertar vínculo utilizado recientemente en Outlook insertaba un vínculo que solo funcionaba para los usuarios que ya tenían permisos.</span><span class="sxs-lookup"><span data-stu-id="6222e-271">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="6222e-272">A menudo esto causaba un intercambio continuo de mensajes de correo electrónico entre los usuarios que pedían acceso a un documento.</span><span class="sxs-lookup"><span data-stu-id="6222e-272">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="6222e-273">Hemos actualizado esta experiencia para que ahora el vínculo se inserte con el permiso predeterminado establecido por el administrador de inquilinos. Para MSIT se trata de "la organización puede editar", por lo que todos los usuarios internos que reciban un vínculo compartido de esta manera podrán acceder a él.</span><span class="sxs-lookup"><span data-stu-id="6222e-273">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="6222e-274">**Ver los mensajes bajo otra luz:** use el botón sol/luna para cambiar entre fondos claros y oscuros en el panel de lectura.</span><span class="sxs-lookup"><span data-stu-id="6222e-274">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="6222e-275">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-275">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="6222e-276">**Ahora es más fácil detectar correos de suplantación de identidad:** los mensajes de correo no deseado y de suplantación de identidad tienen un aspecto diferente para que pueda identificarlos y eliminarlos fácilmente en la bandeja de entrada.</span><span class="sxs-lookup"><span data-stu-id="6222e-276">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="6222e-p123">**Todas las opciones de cifrado en un solo lugar:** vaya a Opciones > Cifrar para elegir cómo proteger su mensaje de correo. [Más información](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="6222e-p123">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="6222e-279">**Busque incluso con errores ortográficos o tipográficos:** Outlook encontrará lo que busca, aunque no coincida con la forma exacta en que lo escribió.</span><span class="sxs-lookup"><span data-stu-id="6222e-279">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="6222e-280">**Conecte su red de LinkedIn con Outlook:** Conecte de forma segura su cuenta de LinkedIn con su cuenta de Microsoft para ver la información de los perfiles de LinkedIn directamente en las tarjetas personales.</span><span class="sxs-lookup"><span data-stu-id="6222e-280">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="6222e-281">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-281">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="6222e-282">**Ver mensajes relevantes en los resultados de búsqueda:** Outlook analiza los términos de búsqueda y muestra los mensajes de correo electrónico más relevantes en la parte superior de los resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="6222e-282">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="6222e-283">También verá todos los resultados ordenados por fecha en la sección de Resultados principales.</span><span class="sxs-lookup"><span data-stu-id="6222e-283">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="6222e-284">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-284">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a><span data-ttu-id="6222e-285">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6222e-285">PowerPoint</span></span>

- <span data-ttu-id="6222e-p126">**Usted calcula y nosotros le damos formato:** hemos convertido las expresiones matemáticas escritas a mano en caracteres estándar. Simplemente elija Entrada de lápiz a matemáticas y seleccione las notas escritas a mano para empezar. [Más información](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="6222e-p126">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="6222e-289">**Encuentre lo que busca:** use el cuadro de búsqueda para buscar texto, comandos, ayuda y mucho más.</span><span class="sxs-lookup"><span data-stu-id="6222e-289">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="6222e-290">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-290">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="6222e-291">**Entrada de tinta para magníficas diapositivas:** convierta el texto de tinta en formas estándar y texto y obtenga ideas de diseño inteligente del Diseñador de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6222e-291">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="6222e-292">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-292">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="6222e-293">**Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su presentación.</span><span class="sxs-lookup"><span data-stu-id="6222e-293">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="6222e-294">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-294">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="6222e-295">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="6222e-295">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="6222e-296">**Repetición de entrada de lápiz:** cuando haya entradas de lápiz en sus diapositivas, aplique una animación de reproducción para reproducir el dibujo real de la entrada de lápiz durante la presentación con diapositivas.</span><span class="sxs-lookup"><span data-stu-id="6222e-296">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="6222e-297">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-297">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br /><span data-ttu-id="6222e-298">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="6222e-298">See details in [blog post](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span></span>

- <span data-ttu-id="6222e-299">**Una experiencia de vídeo más segura:** las mejoras de seguridad hacen que la experiencia de vídeo en línea sea más segura.</span><span class="sxs-lookup"><span data-stu-id="6222e-299">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="6222e-300">**Guarde una ilustración como SVG:** guarde un gráfico, una forma o una ilustración como un gráfico vectorial escalable, que se puede cambiar de tamaño sin perder calidad de imagen.</span><span class="sxs-lookup"><span data-stu-id="6222e-300">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="6222e-301">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-301">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="6222e-302">**Impresión de números de diapositiva en documentos:** los números de diapositiva se incluyen automáticamente en los documentos.</span><span class="sxs-lookup"><span data-stu-id="6222e-302">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="6222e-303">Ahora es usted quien decide si los deja o los quita.</span><span class="sxs-lookup"><span data-stu-id="6222e-303">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="6222e-304">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-304">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="6222e-305">**Encuentre los títulos de diapositivas que faltan y escríbalos**: los títulos de diapositivas añaden fuerza a su discurso y permiten que las diapositivas sean accesibles para los usuarios de todas las capacidades.</span><span class="sxs-lookup"><span data-stu-id="6222e-305">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="6222e-306">El comprobador de accesibilidad le muestra dónde faltan títulos para que pueda agregarlos en el momento.</span><span class="sxs-lookup"><span data-stu-id="6222e-306">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="6222e-307">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-307">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="6222e-308">**Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los demás.</span><span class="sxs-lookup"><span data-stu-id="6222e-308">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="6222e-309">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="6222e-309">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="6222e-310">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="6222e-310">**More icons to match your mood:** We've added more than 300 new icons.</span></span> <span data-ttu-id="6222e-311">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="6222e-311">Find them at Insert > Icons.</span></span> [<span data-ttu-id="6222e-312">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-312">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="6222e-313">**Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.</span><span class="sxs-lookup"><span data-stu-id="6222e-313">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span><br /><span data-ttu-id="6222e-314">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="6222e-314">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="6222e-315">**Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="6222e-315">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="6222e-316">**Colaboración rápida en tiempo real en PowerPoint:** colaboración rápida en tiempo real en PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6222e-316">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="6222e-317">**Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. </span><span class="sxs-lookup"><span data-stu-id="6222e-317">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="6222e-318">**Nuevas herramientas de revisión:** no se preocupe de las palabras.</span><span class="sxs-lookup"><span data-stu-id="6222e-318">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="6222e-319">Ahora en PowerPoint se ofrecen sugerencias de gramática y escritura.</span><span class="sxs-lookup"><span data-stu-id="6222e-319">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="6222e-320">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-320">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="6222e-321">**Transcripción y subtítulos en directo:** las palabras del moderador se muestran automáticamente en la pantalla como subtítulos o se traducen en el idioma que prefiera.</span><span class="sxs-lookup"><span data-stu-id="6222e-321">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="6222e-322">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-322">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="6222e-323">**Optimizar la presentación para todos:** el comprobador de accesibilidad le ayuda a organizar los objetos de las diapositivas pensando en los lectores de pantalla.</span><span class="sxs-lookup"><span data-stu-id="6222e-323">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span><br /><span data-ttu-id="6222e-324">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span><span class="sxs-lookup"><span data-stu-id="6222e-324">See details in [blog post](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span></span>

- <span data-ttu-id="6222e-325">**¿Para que reinventar lo que puede reutilizar?:** ahorre tiempo usando de nuevo las diapositivas que haya creado o que otros usuarios han compartido con usted.</span><span class="sxs-lookup"><span data-stu-id="6222e-325">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="6222e-326">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-326">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a><span data-ttu-id="6222e-327">Visio</span><span class="sxs-lookup"><span data-stu-id="6222e-327">Visio</span></span>

- <span data-ttu-id="6222e-328">**Cree diagramas de Visio elegantes en Excel:** cree un diagrama de flujo o un organigrama con solo escribir datos en una hoja de cálculo.</span><span class="sxs-lookup"><span data-stu-id="6222e-328">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="6222e-329">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-329">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="6222e-330">**Vuelva a la escena del crimen:** use las nuevas plantillas Evidencia, Interior y Exterior en la plantilla Investigación de Escenas de Delitos para recrear con detalle escenarios de delitos.</span><span class="sxs-lookup"><span data-stu-id="6222e-330">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

### <a name="word"></a><span data-ttu-id="6222e-331">Word</span><span class="sxs-lookup"><span data-stu-id="6222e-331">Word</span></span>

- <span data-ttu-id="6222e-332">**Una experiencia de vídeo más segura:** las mejoras de seguridad hacen que la experiencia de vídeo en línea sea más segura.</span><span class="sxs-lookup"><span data-stu-id="6222e-332">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="6222e-333">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-333">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="6222e-334">**Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.</span><span class="sxs-lookup"><span data-stu-id="6222e-334">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="6222e-335">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-335">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="6222e-336">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="6222e-336">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="6222e-337">**Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="6222e-337">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="6222e-338">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="6222e-338">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="6222e-339">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="6222e-339">Find them at Insert > Icons.</span></span> [<span data-ttu-id="6222e-340">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-340">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br /><span data-ttu-id="6222e-341">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span><span class="sxs-lookup"><span data-stu-id="6222e-341">See details in [blog post](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span></span>

- <span data-ttu-id="6222e-342">**Borrar con precisión:** elija entre dos tamaños de borrador para arreglar pequeñas imperfecciones de la entrada de lápiz.</span><span class="sxs-lookup"><span data-stu-id="6222e-342">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="6222e-343">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-343">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="6222e-344">**Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los demás.</span><span class="sxs-lookup"><span data-stu-id="6222e-344">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="6222e-345">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="6222e-345">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="6222e-346">**Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su documento.</span><span class="sxs-lookup"><span data-stu-id="6222e-346">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="6222e-347">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-347">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="6222e-348">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="6222e-348">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="6222e-349">**Encuentre lo que busca:** use el cuadro de búsqueda para buscar texto, comandos, ayuda y mucho más.</span><span class="sxs-lookup"><span data-stu-id="6222e-349">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="6222e-350">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-350">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="6222e-351">**Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. </span><span class="sxs-lookup"><span data-stu-id="6222e-351">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="6222e-352">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-352">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="6222e-353">**El Editor para currículum vítae incorpora el Asistente para currículum vítae de LinkedIn:** el Editor para currículum vítae ofrece una selección de comprobaciones gramaticales y de estilo especialmente adaptadas a los currículums, para que el texto sea más preciso y profesional.</span><span class="sxs-lookup"><span data-stu-id="6222e-353">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="6222e-354">**Otros usuarios verán los cambios rápidamente:** con las mejoras en la coautoría, los colaboradores podrán ver los cambios más rápido que nunca.</span><span class="sxs-lookup"><span data-stu-id="6222e-354">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="6222e-355">**Se ha corregido un problema relacionado con los documentos causados por la combinación de objetos 3D:** corrige un problema de daños en un documento producido por la combinación de objetos 3D.</span><span class="sxs-lookup"><span data-stu-id="6222e-355">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="6222e-356">**Mejoras en la coautoría:** mejora del rendimiento de Word en coautoría en documentos con marcas de revisión.</span><span class="sxs-lookup"><span data-stu-id="6222e-356">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="6222e-357">**Mejoras en la coautoría:** mejora de la confiabilidad de la coautoría.</span><span class="sxs-lookup"><span data-stu-id="6222e-357">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="6222e-358">**Colaborando a todo color:** los comentarios y los cambios están codificados por color según la persona que contribuya, por lo que es fácil distinguir entre sus colaboradores.</span><span class="sxs-lookup"><span data-stu-id="6222e-358">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="6222e-359">**Editar documentos habilitados para macros de forma conjunta:** guarde sus archivos .docm en OneDrive para la Empresa y edítelos con sus colaboradores en tiempo real.</span><span class="sxs-lookup"><span data-stu-id="6222e-359">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6222e-360">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6222e-360">Office Suite</span></span>

- <span data-ttu-id="6222e-361">**Transforme la entrada de lápiz en formas, texto o matemáticas en PowerPoint para Office 365:** convierta la entrada de lápiz en forma libre a formas, textos o expresiones matemáticas de Office en un par de trazos.</span><span class="sxs-lookup"><span data-stu-id="6222e-361">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="6222e-362">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-362">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6222e-365">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-365">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="6222e-366">Access</span><span class="sxs-lookup"><span data-stu-id="6222e-366">Access</span></span>

- <span data-ttu-id="6222e-367">Esta actualización corrige un problema por el que al usar un objeto de grabación de ADODB</span><span class="sxs-lookup"><span data-stu-id="6222e-367">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="6222e-368">en el código de VB, se puede notificar un error incorrectamente.</span><span class="sxs-lookup"><span data-stu-id="6222e-368">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="6222e-369">Las plantillas de Access ya no deberían causar errores en columnas de datos adjuntos en una base de datos.</span><span class="sxs-lookup"><span data-stu-id="6222e-369">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="6222e-370">Después de crear la instancia de una plantilla, ahora debería poder agregar un campo de datos adjuntos a la base de datos.</span><span class="sxs-lookup"><span data-stu-id="6222e-370">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="6222e-371">Esta actualización corrige un problema que puede hacer que Microsoft Access no identifique una Columna de identidad en una tabla vinculada de SQL Server, lo que puede provocar que las filas aparezcan como eliminadas de forma incorrecta.</span><span class="sxs-lookup"><span data-stu-id="6222e-371">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="6222e-372">Esta actualización corrige un problema en Microsoft Access que puede causar el error "La consulta está dañada" cuando se ejecuta una consulta de actualización o cuando se usa una instrucción UPDATE en SQL.</span><span class="sxs-lookup"><span data-stu-id="6222e-372">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="6222e-373">Excel</span><span class="sxs-lookup"><span data-stu-id="6222e-373">Excel</span></span>

- <span data-ttu-id="6222e-374">Acelere la carga de archivos que están disponibles en la carpeta de OneDrive local.</span><span class="sxs-lookup"><span data-stu-id="6222e-374">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="6222e-375">Se ha solucionado un problema por el que las funciones CUBEVALUE a veces daban un resultado incorrecto.</span><span class="sxs-lookup"><span data-stu-id="6222e-375">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="6222e-376">Resuelto un problema con la personalización de la cinta que no se cargaba al abrir el libro de trabajo incrustado.</span><span class="sxs-lookup"><span data-stu-id="6222e-376">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="6222e-377">Excel se bloqueaba en ciertos casos cuando se volvía a abrir un libro incrustado en Word o PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6222e-377">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="6222e-378">Se ha corregido un problema por el que los comandos de comentario en el menú contextual no aparecían.</span><span class="sxs-lookup"><span data-stu-id="6222e-378">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="6222e-379">Se ha corregido el botón derecho en el menú de gráficos dinámicos para habilitar la opción de mostrar los detalles.</span><span class="sxs-lookup"><span data-stu-id="6222e-379">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="6222e-380">Se ha resuelto un problema que puede haber causado un bloqueo al buscar archivos recientes cuando no hay ningún libro de trabajo abierto.</span><span class="sxs-lookup"><span data-stu-id="6222e-380">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="6222e-381">Se ha corregido un problema que provocaba que, al hacer clic en un hipervínculo marcado en el propio libro, se ocultara dicho libro.</span><span class="sxs-lookup"><span data-stu-id="6222e-381">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="6222e-382">Cuando guarda como un archivo CSV, Excel podía combinar todas las columnas en una sola columna en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="6222e-382">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="6222e-383">Usar Range.ClearContents en un rango de una hoja protegida podía tardar más de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="6222e-383">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="6222e-384">Corregido un problema con la escala de texto en los controles de formulario cuando se mostraba en la Vista previa de impresión.</span><span class="sxs-lookup"><span data-stu-id="6222e-384">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="6222e-385">Las macros de VBA que interactúan con la cinta de opciones se pueden ejecutar con ScreenUpdating establecido en True inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="6222e-385">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="6222e-386">Se ha corregido un problema que hacía que Excel se bloqueara en ciertos casos después de copiar una hoja que contenía una tabla dinámica.</span><span class="sxs-lookup"><span data-stu-id="6222e-386">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="6222e-387">La apertura de archivos CSV tardaba más de lo esperado en algunas circunstancias.</span><span class="sxs-lookup"><span data-stu-id="6222e-387">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="6222e-388">Excel se bloqueaba en determinadas circunstancias al cambiar entre libros con diferentes niveles de zoom.</span><span class="sxs-lookup"><span data-stu-id="6222e-388">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="6222e-389">Se ha corregido un problema con VBA por el que escribir valores en un rango era más lento de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="6222e-389">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="6222e-390">En ocasiones, los datos copiados de una columna filtrada por color no se pegaban correctamente.</span><span class="sxs-lookup"><span data-stu-id="6222e-390">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="6222e-391">La apertura de un libro de trabajo con referencias a muchos otros libros de trabajo, especialmente con ventanas ocultas, era más lenta de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="6222e-391">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="6222e-392">Se ha corregido un problema por el que los enlaces externos no se actualizaban al rellenar (rellenar hacia abajo, rellenar en otros, etc.) si el libro de origen estaba cerrado.</span><span class="sxs-lookup"><span data-stu-id="6222e-392">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is& closed.</span></span>

- <span data-ttu-id="6222e-393">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="6222e-393">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="6222e-394">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="6222e-394">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="6222e-395">Se ha corregido un problema por el que la propiedad "Valor se cruza en" en el eje del gráfico cambiaba inesperadamente al guardar y volver a abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="6222e-395">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="6222e-396">Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta al guardar en SharePoint o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="6222e-396">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="6222e-397">Se ha mejorado el rendimiento al eliminar columnas con celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="6222e-397">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="6222e-398">Se ha corregido un problema por el que los nombres de las impresoras podrían repetirse en la lista de impresoras en el cuadro de diálogo Imprimir.</span><span class="sxs-lookup"><span data-stu-id="6222e-398">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="6222e-399">Se ha corregido un problema que hacía que el vínculo externo dejara de funcionar después de que se volviera a abrir el archivo si su ruta de acceso era demasiado larga.</span><span class="sxs-lookup"><span data-stu-id="6222e-399">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="6222e-400">Se ha corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.</span><span class="sxs-lookup"><span data-stu-id="6222e-400">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="6222e-401">Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.</span><span class="sxs-lookup"><span data-stu-id="6222e-401">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="6222e-402">Insertar una columna en una lista filtrada llevaba más tiempo de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="6222e-402">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="6222e-403">Se ha corregido un problema por el que algunos vínculos de un gráfico copiado y pegado usaban direcciones de unidad asignadas, en lugar de direcciones universales.</span><span class="sxs-lookup"><span data-stu-id="6222e-403">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="6222e-404">Se ha corregido un problema que producía el siguiente mensaje de error: "No se puede cerrar el libro de trabajo debido a que otro libro hace referencia al mismo". El mensaje aparecía si los complementos se cargaban en orden alfabético en lugar de en un orden especificado por el usuario.</span><span class="sxs-lookup"><span data-stu-id="6222e-404">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="6222e-405">Se ha corregido un problema que haría que un libro se ocultara al hacer clic en un hipervínculo a un lugar dentro de un libro ya abierto.</span><span class="sxs-lookup"><span data-stu-id="6222e-405">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="6222e-406">La apertura de un libro de trabajo con referencias a muchos otros libros de trabajo, especialmente con ventanas ocultas, era más lenta de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="6222e-406">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="6222e-407">El uso de Application.Evaluate de VBA no funcionaba para funciones definidas por el usuario en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="6222e-407">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="6222e-408">Se ha corregido un problema que algunos usuarios pudieron sufrir con objetos incrustados y vinculados (OLE).</span><span class="sxs-lookup"><span data-stu-id="6222e-408">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="6222e-409">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="6222e-409">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="6222e-410">Esta actualización corrige un problema que causaba que la barra de fórmulas mostrara texto en una fuente diferente a la esperada.</span><span class="sxs-lookup"><span data-stu-id="6222e-410">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="6222e-411">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="6222e-411">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="6222e-412">Corregimos un problema en el que al seleccionar una celda luego de desplazar, podía resultar en la selección de la celda incorrecta.</span><span class="sxs-lookup"><span data-stu-id="6222e-412">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="6222e-413">Los usuarios pueden encontrar un error al acceder a un rango con nombre oculto.</span><span class="sxs-lookup"><span data-stu-id="6222e-413">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="6222e-414">Excel puede tener problemas al editar un archivo protegido desde una red compartida no confiable.</span><span class="sxs-lookup"><span data-stu-id="6222e-414">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="6222e-415">La funcionalidad de texto a columna puede fallar en algunas localizaciones.</span><span class="sxs-lookup"><span data-stu-id="6222e-415">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="6222e-416">Se ha corregido un problema de rendimiento al crear gráficos a partir de plantillas.</span><span class="sxs-lookup"><span data-stu-id="6222e-416">Addresses a performance issue when creating charts from templates.</span></span>

- <span data-ttu-id="6222e-417">Se ha corregido un problema que causaba que algunos usuarios experimentasen bloqueos al convertir texto en columnas con celdas que tienen una matriz derramada.</span><span class="sxs-lookup"><span data-stu-id="6222e-417">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="6222e-418">El uso de un Range.Value y Range.Value2 (VBA) hacía que las fórmulas se escribieran como matrices dinámicas.</span><span class="sxs-lookup"><span data-stu-id="6222e-418">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

- <span data-ttu-id="6222e-419">Se ha corregido un problema por el que un símbolo @ que inicia una fórmula se considera un operador de intersección implícita.</span><span class="sxs-lookup"><span data-stu-id="6222e-419">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

- <span data-ttu-id="6222e-420">Se ha corregido un problema por el que las hojas de cálculo que contenían varias fórmulas con nombres definidos tardaban más en guardarse.</span><span class="sxs-lookup"><span data-stu-id="6222e-420">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="6222e-421">Este cambio evita un problema con ciertos controladores de gráficos Intel al aprovechar el procesamiento del software.</span><span class="sxs-lookup"><span data-stu-id="6222e-421">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="6222e-422">Se ha corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.</span><span class="sxs-lookup"><span data-stu-id="6222e-422">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="onenote"></a><span data-ttu-id="6222e-423">OneNote</span><span class="sxs-lookup"><span data-stu-id="6222e-423">OneNote</span></span>

- <span data-ttu-id="6222e-424">Mejora la sincronización y la estabilidad del servicio al ajustar temporalmente la frecuencia de sincronización en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="6222e-424">Improve sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="6222e-425">Mejora la sincronización y la estabilidad del servicio al diferir temporalmente la descarga de archivos e imágenes incrustados en los blocs de notas en línea hasta que el usuario navegue a la página en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="6222e-425">Improve sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="6222e-426">Mejora la sincronización y la estabilidad del servicio al deshabilitar temporalmente la papelera de reciclaje en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="6222e-426">Improve sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="6222e-427">Cuando un usuario intenta eliminar datos que normalmente se enviarían a la papelera de reciclaje, se le preguntará si prefiere conservarlos o eliminarlos forma permanente.</span><span class="sxs-lookup"><span data-stu-id="6222e-427">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="6222e-428">Mejora la sincronización y estabilidad de servicio mejoradas al reducir temporalmente el número y la frecuencia de sincronización de las páginas del historial de versiones en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="6222e-428">Improve sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="6222e-429">Muestra una notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="6222e-429">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="6222e-430">Mejora la sincronización y la estabilidad del servicio al reducir temporalmente el tamaño máximo de nuevos datos adjuntos insertados a 50 MB en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="6222e-430">Improve sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="6222e-431">Si los archivos superan este límite, los usuarios tendrán la opción de cargar el archivo a OneDrive e insertar un vínculo en OneNote.</span><span class="sxs-lookup"><span data-stu-id="6222e-431">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="6222e-432">Mejora la sincronización y la estabilidad del servicio al deshabilitar temporalmente la grabación de vídeo en la aplicación en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="6222e-432">Improve sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="6222e-433">La medida no afecta a los blocs de notas locales.</span><span class="sxs-lookup"><span data-stu-id="6222e-433">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="6222e-434">Localiza la notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="6222e-434">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="6222e-435">Outlook</span><span class="sxs-lookup"><span data-stu-id="6222e-435">Outlook</span></span>

- <span data-ttu-id="6222e-436">Se ha corregido un problema por el que la ventana del Editor de métodos de entrada (IME) se superponía al texto subyacente escrito mediante el IME cuando se usaban varios monitores con resoluciones diferentes.</span><span class="sxs-lookup"><span data-stu-id="6222e-436">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="6222e-437">Se ha corregido un problema que provocaba que los usuarios vean bloqueos ocasionales en Outlook.</span><span class="sxs-lookup"><span data-stu-id="6222e-437">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="6222e-438">Esto actualiza la lógica de bloqueo de adjuntos en Outlook para bloquear también los adjuntos de Python.</span><span class="sxs-lookup"><span data-stu-id="6222e-438">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="6222e-439">Se ha corregido un problema que provocaba que los complementos web accedieran a los mensajes administrados con derechos digitales.</span><span class="sxs-lookup"><span data-stu-id="6222e-439">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="6222e-440">Se ha corregido un problema que causaba que las citas o reuniones periódicas se mostraran en un momento incorrecto al tratar de cambiar la definición de una zona horaria.</span><span class="sxs-lookup"><span data-stu-id="6222e-440">Addresses an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="6222e-441">Cuando se utiliza la zona horaria de Brasilia en el año 2019, las reuniones y citas recurrentes se muestran en la franja horaria equivocada para el año 2020.</span><span class="sxs-lookup"><span data-stu-id="6222e-441">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="6222e-442">Este cambio es relevante para los clientes establecidos en la zona horaria de Brasilia o para las reuniones y citas establecidas en esa zona horaria.</span><span class="sxs-lookup"><span data-stu-id="6222e-442">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span><br><br><span data-ttu-id="6222e-443">Este cambio permite a Outlook reemplazar algunas opciones de configuración de zona horaria utilizadas por Outlook.</span><span class="sxs-lookup"><span data-stu-id="6222e-443">This change allows Outlook to override certain time zone settings used by Outlook.</span></span> <span data-ttu-id="6222e-444">Para invocar una invalidación de zona horaria, debe establecer una clave del registro para el usuario actual.</span><span class="sxs-lookup"><span data-stu-id="6222e-444">In order to invoke a time zone override you must set a registry key for the current user.</span></span> <span data-ttu-id="6222e-445">El nombre de la clave del registro debe coincidir con el nombre interno de la zona horaria.</span><span class="sxs-lookup"><span data-stu-id="6222e-445">The registry key name must match the internal name of the time zone.</span></span> <span data-ttu-id="6222e-446">El valor indica el año en el que se va a usar la regla de zona horaria en vez del año efectivo.</span><span class="sxs-lookup"><span data-stu-id="6222e-446">The value indicates the time zone rule's year to be used in place of the effective year.</span></span> <span data-ttu-id="6222e-447">Por ejemplo, el siguiente valor para reemplazar la clave del registro usará la regla de zona horaria de Brasil para el año 2020 como regla efectiva.</span><span class="sxs-lookup"><span data-stu-id="6222e-447">For example, the following registry key override value will use the Brazilia time zone rule for the year 2020 as the effective rule.</span></span> <span data-ttu-id="6222e-448">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span><span class="sxs-lookup"><span data-stu-id="6222e-448">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span></span> <span data-ttu-id="6222e-449">Hora estándar de Sudamérica"=dword:000007e4.</span><span class="sxs-lookup"><span data-stu-id="6222e-449">South America Standard Time"=dword:000007e4.</span></span>

- <span data-ttu-id="6222e-450">Se ha corregido un problema por el que los usuarios veían cambiar el campo de ubicación de las reuniones de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="6222e-450">Addresses an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="6222e-451">Se ha corregido un problema que provocaba que el campo Ubicación en las reuniones se actualizara de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="6222e-451">Addresses an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="6222e-452">Se ha corregido un problema que provocó que la ubicación de una reunión se volviera a añadir a la reunión de forma inesperada después de despejarla.</span><span class="sxs-lookup"><span data-stu-id="6222e-452">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="6222e-453">Se ha corregido un tema que causó que las comas en el campo de ubicación de una reunión se convirtieran en punto y coma.</span><span class="sxs-lookup"><span data-stu-id="6222e-453">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="6222e-454">Permite unirse a una reunión de Teams directamente a través del cliente nativo de Teams.</span><span class="sxs-lookup"><span data-stu-id="6222e-454">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="6222e-455">Se ha corregido un problema que provocaba que los usuarios con buzones en servidores de Exchange 2010 sufrieran problemas al agregar archivos adjuntos a elementos de calendario.</span><span class="sxs-lookup"><span data-stu-id="6222e-455">Addresses an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="6222e-456">Se ha corregido un problema que provocaba que los usuarios experimentaran problemas al responder a los mensajes firmados digitalmente.</span><span class="sxs-lookup"><span data-stu-id="6222e-456">Addresses an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="6222e-457">Se ha corregido un problema que provocaba que los usuarios no pudieran abrir algunas instancias de los elementos de calendario periódicos.</span><span class="sxs-lookup"><span data-stu-id="6222e-457">Addresses an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="6222e-458">Se ha corregido un problema que hacía que el encabezado de grupo se expandiera de forma inesperada en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="6222e-458">Addresses an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="6222e-459">Se ha corregido un problema que provocaba que el ancho del panel de carpetas cambiara de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="6222e-459">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="6222e-460">Se ha corregido un problema por el que Outlook no pudo habilitar consejos de directiva para la Protección de pérdida de datos para usuarios que pagaron por el servicio con planes M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="6222e-460">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="6222e-461">Se ha corregido un problema por el que los usuarios notaban un retraso evidente al interactuar con sus carpetas de buzón mediante métodos abreviados de teclado.</span><span class="sxs-lookup"><span data-stu-id="6222e-461">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="6222e-462">Se ha corregido un problema que podría resultar en un choque al ver el mismo elemento en varias ventanas.</span><span class="sxs-lookup"><span data-stu-id="6222e-462">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="6222e-463">Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al actualizar sus reglas en Outlook.</span><span class="sxs-lookup"><span data-stu-id="6222e-463">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="6222e-464">Se ha corregido un problema que causaba una pérdida de memoria en sesiones de Outlook muy largas.</span><span class="sxs-lookup"><span data-stu-id="6222e-464">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="6222e-465">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.</span><span class="sxs-lookup"><span data-stu-id="6222e-465">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="6222e-466">Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al abrir el cuadro de diálogo de Reglas.</span><span class="sxs-lookup"><span data-stu-id="6222e-466">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="6222e-467">Se ha corregido un problema por el que la opción para deshabilitar el resaltado de elementos marcados no funcionaba en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="6222e-467">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="6222e-468">Se ha corregido un problema que provocaba que los usuarios vieran mensajes enviados inesperadamente al presionar la tecla "S" después de cerrar el panel del comprobador de accesibilidad.</span><span class="sxs-lookup"><span data-stu-id="6222e-468">Addresses an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="6222e-469">Se ha corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.</span><span class="sxs-lookup"><span data-stu-id="6222e-469">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="6222e-470">Se ha corregido un problema que provocaba que los usuarios experimentaran un error al cancelar la configuración de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="6222e-470">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="6222e-471">Se ha corregido un problema por el que Outlook sincronizaba inesperadamente todo el correo, incluso cuando el deslizador de sincronización estaba configurado en un ajuste menor.</span><span class="sxs-lookup"><span data-stu-id="6222e-471">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="6222e-472">Se ha corregido un problema que provocaba que los usuarios con el Tema negro vieran texto blanco sobre un fondo blanco en el desplegable "De".</span><span class="sxs-lookup"><span data-stu-id="6222e-472">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="6222e-473">Se ha corregido un problema que provocaba que los usuarios sufrieran un bloqueo durante la creación del perfil.</span><span class="sxs-lookup"><span data-stu-id="6222e-473">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="6222e-474">Se ha corregido un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "OK" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="6222e-474">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="6222e-475">Se ha corregido un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "OK" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="6222e-475">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="6222e-476">Se ha corregido un problema que provocaba que las aplicaciones de terceros no pudiesen enviar correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="6222e-476">Addresses an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="6222e-477">Se ha corregido un problema que provocaba que las categorías desapareciesen en ocasiones de los mensajes de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="6222e-477">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="6222e-478">Se ha corregido un problema que provocaba que los usuarios de Outlook en sistemas operativos de servidor vieran el error: "Estado del antivirus: no válido.</span><span class="sxs-lookup"><span data-stu-id="6222e-478">Addresses an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="6222e-479">Esta versión de Windows admite la detección del antivirus, pero no se encontró ninguno" a pesar de tener el antivirus correctamente configurado.</span><span class="sxs-lookup"><span data-stu-id="6222e-479">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

- <span data-ttu-id="6222e-480">Se ha corregido un problema que provocaba que los delegados viesen distintas jerarquías de carpetas en diferentes equipos para los buzones compartidos.</span><span class="sxs-lookup"><span data-stu-id="6222e-480">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="6222e-481">Se ha corregido un problema que causaba que los delegados reciban un error al editar una cita de calendario existente en el calendario de un administrador.</span><span class="sxs-lookup"><span data-stu-id="6222e-481">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="6222e-482">Se ha corregido un problema que provocaba que los usuarios con la configuración de emulación de explorador incorrecta no pudieran completar el mensaje de autenticación de Gmail.</span><span class="sxs-lookup"><span data-stu-id="6222e-482">Addresses an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="6222e-483">Se ha corregido un problema que causaba que faltara la opción "Permitir reenvío" en las "Opciones de respuesta" de la reunión de calendario compartida cuando NO está marcada Descargar carpeta compartida.</span><span class="sxs-lookup"><span data-stu-id="6222e-483">Addresses an issue that caused the " Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="6222e-484">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al intentar abrir archivos .msg y .oft después de una actualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="6222e-484">Addresses an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="6222e-485">Se ha corregido un problema que causaba que los usuarios experimentaran ocasionalmente un bloqueo al usar el botón X de su ratón.</span><span class="sxs-lookup"><span data-stu-id="6222e-485">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="6222e-486">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al seleccionar determinados resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="6222e-486">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="6222e-487">Se ha corregido un problema que hizo que el botón "Guardar en la nube" faltara en las herramientas de adjuntos.</span><span class="sxs-lookup"><span data-stu-id="6222e-487">Addresses an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="6222e-488">Este cambio restaura la capacidad de ver sujetos de varias líneas en el encabezado del mensaje.</span><span class="sxs-lookup"><span data-stu-id="6222e-488">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="6222e-489">Se ha corregido un problema que causaba que los usuarios experimentaran un bloqueo cuando dos complementos agregan un botón al mismo grupo de la cinta de opciones.</span><span class="sxs-lookup"><span data-stu-id="6222e-489">Addresses an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="6222e-490">Se ha corregido un problema que provocaba que los vínculos no se agreguen a los correos electrónicos con el permiso predeterminado incorrecto de espacio empresarial cuando el permiso predeterminado de espacio empresarial se configura como "cualquiera".</span><span class="sxs-lookup"><span data-stu-id="6222e-490">Addresses an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as "anyone".</span></span>

- <span data-ttu-id="6222e-491">Se ha corregido un problema que provocaba que los usuarios no pudieran dirigir mensajes de correo electrónico a una lista de distribución personal.</span><span class="sxs-lookup"><span data-stu-id="6222e-491">Addresses an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="6222e-492">Se ha corregido un problema que hacía que los usuarios vieran el truncamiento del cuerpo del mensaje al reenviar mensajes HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="6222e-492">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="6222e-493">Se ha corregido un problema con la selección del algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="6222e-493">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="6222e-494">Se ha corregido un problema que podía impedir que los archivos se guardaran en una ubicación de WebDAV.</span><span class="sxs-lookup"><span data-stu-id="6222e-494">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="6222e-495">Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.</span><span class="sxs-lookup"><span data-stu-id="6222e-495">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="6222e-496">Se ha corregido un problema que provocaba que el cuerpo de un mensaje NDR cambiara de Unicode a ASCII después de editar el asunto.</span><span class="sxs-lookup"><span data-stu-id="6222e-496">Addresses an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="6222e-497">Se ha corregido un problema que hacía que los usuarios observaran una pérdida de memoria en el proceso de Outlook.</span><span class="sxs-lookup"><span data-stu-id="6222e-497">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="6222e-498">Corrige un problema que provocaba que los usuarios vieran mensajes de correo electrónico enviados a una dirección que no coincidía con la dirección SMTP mostrada en determinadas circunstancias.</span><span class="sxs-lookup"><span data-stu-id="6222e-498">Addresses an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="6222e-499">Se ha corregido un problema que provocaba que el cuadro de búsqueda estuviera mal alineado en modo de PPP alto.</span><span class="sxs-lookup"><span data-stu-id="6222e-499">Addresses an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="6222e-500">Se ha corregido un problema por el que los usuarios experimentan bloqueos en Outlook al recuperar la configuración de la nube.</span><span class="sxs-lookup"><span data-stu-id="6222e-500">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="6222e-501">Se ha corregido un problema que causó un bloqueo en la experiencia de los comentarios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="6222e-501">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="6222e-502">Se ha corregido un problema que provocaba que los usuarios vean bloqueos ocasionales en Outlook.</span><span class="sxs-lookup"><span data-stu-id="6222e-502">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="6222e-503">Se ha corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.</span><span class="sxs-lookup"><span data-stu-id="6222e-503">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="6222e-504">Se ha corregido un problema que provocaba que los usuarios sufrieran un bloqueo durante la creación del perfil.</span><span class="sxs-lookup"><span data-stu-id="6222e-504">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="6222e-505">Se ha corregido un problema que provocaba que los usuarios vean bloqueos ocasionales en Outlook.</span><span class="sxs-lookup"><span data-stu-id="6222e-505">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6222e-506">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6222e-506">PowerPoint</span></span>

- <span data-ttu-id="6222e-507">Se ha corregido un problema que podía bloquear el equipo al usar el menú contextual en comentarios PPT heredados.</span><span class="sxs-lookup"><span data-stu-id="6222e-507">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

- <span data-ttu-id="6222e-508">Se ha mejorado un escenario de copiar y pegar: al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.</span><span class="sxs-lookup"><span data-stu-id="6222e-508">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="6222e-509">Se ha corregido un problema para retransmitir la mensajería correcta a los usuarios que abren una copia de un archivo que ha mejorado los comentarios.</span><span class="sxs-lookup"><span data-stu-id="6222e-509">Fixes an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="project"></a><span data-ttu-id="6222e-510">Project</span><span class="sxs-lookup"><span data-stu-id="6222e-510">Project</span></span>

- <span data-ttu-id="6222e-511">Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.</span><span class="sxs-lookup"><span data-stu-id="6222e-511">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="6222e-512">Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="6222e-512">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="6222e-513">Corregido un problema que hace que el evento ProjectBeforeTaskChange no detecte cuándo se ha desactivado o activado una tarea mediante el botón Desactivar.</span><span class="sxs-lookup"><span data-stu-id="6222e-513">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="6222e-514">Corregido un problema por el que Project puede bloquearse al guardar proyectos creados con versiones anteriores de Project.</span><span class="sxs-lookup"><span data-stu-id="6222e-514">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="6222e-515">Identificamos un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de solo lectura</span><span class="sxs-lookup"><span data-stu-id="6222e-515">Identified an issue where users could get several messages when opening a read-only project</span></span>

- <span data-ttu-id="6222e-516">Se ha corregido un problema por el que el 100 % de las tareas de tipo duración fija podían tener un cálculo del porcentaje incorrecto con menos del 100% completado.</span><span class="sxs-lookup"><span data-stu-id="6222e-516">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="6222e-517">Word</span><span class="sxs-lookup"><span data-stu-id="6222e-517">Word</span></span>

- <span data-ttu-id="6222e-518">Se ha corregido un problema que causaba que los usuarios experimentaran ocasionalmente un bloqueo al usar el botón X de su ratón.</span><span class="sxs-lookup"><span data-stu-id="6222e-518">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="6222e-519">Se ha corregido un problema por el que la alineación de las palabras de un documento se descomponía al intentar editar después de imprimir con la impresión rápida.</span><span class="sxs-lookup"><span data-stu-id="6222e-519">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="6222e-520">Corregido un problema con el ajuste de texto en una tabla.</span><span class="sxs-lookup"><span data-stu-id="6222e-520">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="6222e-521">Corregido un problema donde al insertar líneas horizontales no eran más cortas ni centradas.</span><span class="sxs-lookup"><span data-stu-id="6222e-521">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>

- <span data-ttu-id="6222e-522">El organizador de bloques de creación puede mostrar una alerta no válida: "Ha modificado estilos, bloques de creación".</span><span class="sxs-lookup"><span data-stu-id="6222e-522">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

- <span data-ttu-id="6222e-523">Se ha corregido un problema de coautoría si se habilita la Directiva FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="6222e-523">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="6222e-524">Se ha corregido un problema en el que Word QuickPart no funciona al agregar un campo de búsqueda cuyo nombre se ha cambiado.</span><span class="sxs-lookup"><span data-stu-id="6222e-524">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

- <span data-ttu-id="6222e-525">Se ha corregido un problema al combinar dos documentos en uno.</span><span class="sxs-lookup"><span data-stu-id="6222e-525">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="6222e-526">Se ha corregido un problema con la característica Comparación para los documentos protegidos para la edición.</span><span class="sxs-lookup"><span data-stu-id="6222e-526">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="6222e-527">Esta actualización corrige un problema en Microsoft Word por el que el texto que supera los 255 caracteres insertados durante la aplicación de una etiqueta de confidencialidad no se pudiese identificar y quitar posteriormente cambiando o quitando la etiqueta si la directiva de etiqueta aplicó un encabezado, un pie de página o una marca de agua.</span><span class="sxs-lookup"><span data-stu-id="6222e-527">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6222e-528">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6222e-528">Office Suite</span></span>

- <span data-ttu-id="6222e-529">Se ha corregido un problema en el que los usuarios puedan experimentar demasiado uso de la red y la CPU durante la coautoría en archivos de PowerPoint grandes.</span><span class="sxs-lookup"><span data-stu-id="6222e-529">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="6222e-530">Esta es una corrección para que la aplicación de Project no bloquee la red cuando el archivo se almacena en caché en el cliente.</span><span class="sxs-lookup"><span data-stu-id="6222e-530">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>


- <span data-ttu-id="6222e-531">Se ha resuelto este problema mediante la actualización de los nombres de canal en el backstage con los nuevos nombres de canal en la bifurcación de enero de 2020.</span><span class="sxs-lookup"><span data-stu-id="6222e-531">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="6222e-532">Se ha corregido este problema y en adelante, si un dispositivo se administra mediante directiva, no llamará a la API de audiencia de DMS.</span><span class="sxs-lookup"><span data-stu-id="6222e-532">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="6222e-533">Se ha corregido un problema en el que había una eliminación incompleta al agregar y quitar aplicaciones en una sola transacción.</span><span class="sxs-lookup"><span data-stu-id="6222e-533">We have resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="6222e-534">Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.</span><span class="sxs-lookup"><span data-stu-id="6222e-534">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="6222e-535">Corrige un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.</span><span class="sxs-lookup"><span data-stu-id="6222e-535">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="6222e-536">Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.</span><span class="sxs-lookup"><span data-stu-id="6222e-536">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="6222e-537">Hemos modificado la versión AppV51 para solucionar una regresión de la AppV51 anterior.</span><span class="sxs-lookup"><span data-stu-id="6222e-537">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="6222e-538">Hemos resuelto el problema por el que una operación interna producía una excepción en caso de error en lugar de registrarlo y continuar.</span><span class="sxs-lookup"><span data-stu-id="6222e-538">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="6222e-539">Los usuarios afectados ya no serán bloqueados para recibir actualizaciones.</span><span class="sxs-lookup"><span data-stu-id="6222e-539">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="6222e-540">Nuestro equipo ha agregado compatibilidad con clientes para informar la telemetría en los dominios de la red CDN en semianual Enterprise Preview.</span><span class="sxs-lookup"><span data-stu-id="6222e-540">Our team has added client support for reporting telemetry on the Office CDN domains in Semi-Annual Enterprise Preview.</span></span>

- <span data-ttu-id="6222e-541">Este cambio resuelve problemas con adaptadores gráficos que aprovechan la GPU integrada de Intel.</span><span class="sxs-lookup"><span data-stu-id="6222e-541">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="6222e-542">Este cambio garantiza que el contorno Esbozado funcione correctamente en la cinta de opciones.</span><span class="sxs-lookup"><span data-stu-id="6222e-542">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="6222e-543">Se ha corregido un problema al abrir archivos de ubicaciones locales con algunas configuraciones de proxy específicas.</span><span class="sxs-lookup"><span data-stu-id="6222e-543">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="6222e-544">Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.</span><span class="sxs-lookup"><span data-stu-id="6222e-544">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="6222e-545">Se ha corregido un problema que elimina bloqueos durante las sesiones de entrega de Office y se ha mejorado la fiabilidad de la experiencia del usuario.</span><span class="sxs-lookup"><span data-stu-id="6222e-545">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>

- <span data-ttu-id="6222e-546">Este error actualiza el extremo de la URL del servicio de configuración mejorada (ECS).</span><span class="sxs-lookup"><span data-stu-id="6222e-546">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="6222e-547">Llamar a este punto de conexión más reciente tiene una tasa de éxito superior para capturar desde ECS.</span><span class="sxs-lookup"><span data-stu-id="6222e-547">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

- <span data-ttu-id="6222e-548">Esta actualización corrige un problema en el que con Microsoft Outlook no muestra la etiqueta de confidencialidad actual al ver o redactar mensajes.</span><span class="sxs-lookup"><span data-stu-id="6222e-548">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="6222e-549">Corrige un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.</span><span class="sxs-lookup"><span data-stu-id="6222e-549">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

- <span data-ttu-id="6222e-550">Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="6222e-550">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="6222e-551">El host de Office se bloqueaba en Windows, cuando se activaba un complemento si la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth estaba establecida en cero.</span><span class="sxs-lookup"><span data-stu-id="6222e-551">The office host was crashing in windows, when an add-in is being activated while the registry key  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="6222e-552">Este cambio arreglaría el problema.</span><span class="sxs-lookup"><span data-stu-id="6222e-552">This change would fix this issue.</span></span>

- <span data-ttu-id="6222e-553">Se ha corregido un problema de bloqueo con el host de Office en Windows cuando se activa un complemento mientras el valor del registro TabProcGrowth era del tipo REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="6222e-553">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="6222e-554">Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.</span><span class="sxs-lookup"><span data-stu-id="6222e-554">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="6222e-555">Se ha corregido el problema por el que Access y Publisher podrían no iniciarse correctamente en función de los idiomas que se hubieran instalado.</span><span class="sxs-lookup"><span data-stu-id="6222e-555">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)





[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-july-14"></a><span data-ttu-id="6222e-558">Versión 1908: 14 de julio</span><span class="sxs-lookup"><span data-stu-id="6222e-558">Version 1908: July 14</span></span>
<span data-ttu-id="6222e-559">*Versión 1908 (Compilación 11929.20904)*</span><span class="sxs-lookup"><span data-stu-id="6222e-559">*Version 1908 (Build 11929.20904)*</span></span>

<span data-ttu-id="6222e-560">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-560">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6222e-562">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-562">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="6222e-563">Access</span><span class="sxs-lookup"><span data-stu-id="6222e-563">Access</span></span>

- <span data-ttu-id="6222e-564">Esta actualización corrige un problema en el que la agregación como la suma puede truncar el resultado a un valor entero.</span><span class="sxs-lookup"><span data-stu-id="6222e-564">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="6222e-565">Esta actualización corrige un problema por el que una consulta de Unión que incluye referencias a tablas remotas (por ejemplo, tablas de SQL Server) puede hacer que Access se cierre y se reinicie.</span><span class="sxs-lookup"><span data-stu-id="6222e-565">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="6222e-566">Esta actualización corrige un problema en Microsoft Access que puede causar el error "La consulta está dañada" cuando se ejecuta una consulta de actualización o cuando se usa una instrucción UPDATE en SQL.</span><span class="sxs-lookup"><span data-stu-id="6222e-566">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="6222e-567">Excel</span><span class="sxs-lookup"><span data-stu-id="6222e-567">Excel</span></span>

- <span data-ttu-id="6222e-568">La información clave en holandés para el título del documento ha sido cambiada a Alt-G.</span><span class="sxs-lookup"><span data-stu-id="6222e-568">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="6222e-569">Se ha corregido un problema en Excel en el que las macros asignadas a formas o controles de formularios podían mostrar un mensaje de error incorrecto o funcionar en intervalos de destino incorrectos.</span><span class="sxs-lookup"><span data-stu-id="6222e-569">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="6222e-570">Se resolvió un problema con buscar y reemplazar ese cambio donde el foco estaba en el diálogo después de encontrar el primer elemento.</span><span class="sxs-lookup"><span data-stu-id="6222e-570">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="6222e-571">Esto corrige un problema por el cual al cambiar la forma en que se ordena y actualiza una tabla dinámica mientras se está en una sesión de co autoría con otros usuarios se podía provocar un bloqueo.</span><span class="sxs-lookup"><span data-stu-id="6222e-571">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="6222e-572">Arreglamos un problema cuando el filtro de una tabla dinámica OLAP se estableció en un valor que se había eliminado del cubo.</span><span class="sxs-lookup"><span data-stu-id="6222e-572">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="6222e-573">Esta actualización corrige un problema que provoca un error siempre que se utilizaba VBA para agregar una imagen al encabezado o pie de página de un gráfico.</span><span class="sxs-lookup"><span data-stu-id="6222e-573">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="6222e-574">Se ha corregido un problema que podría haber provocado que los gráficos de líneas de dispersión no se representaran correctamente al cambiar la colección de series</span><span class="sxs-lookup"><span data-stu-id="6222e-574">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span>

- <span data-ttu-id="6222e-575">Se han corregido los colores que se usan en las vistas previas al insertar gráficos con plantillas de gráficos.</span><span class="sxs-lookup"><span data-stu-id="6222e-575">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="6222e-576">Se resolvió un problema que causó que los gráficos de cascada y embudo se desincronizara con las tablas cuando se insertaban o eliminaban celdas.</span><span class="sxs-lookup"><span data-stu-id="6222e-576">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="6222e-577">Se ha corregido un problema de conflicto de fusión en Excel que hacía que los usuarios tuvieran que volver a abrir el libro de trabajo para elegir los cambios.</span><span class="sxs-lookup"><span data-stu-id="6222e-577">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="6222e-578">Se resolvió un problema que causaba un error de tiempo de ejecución de la macro que activaba las ventanas minimizadas.</span><span class="sxs-lookup"><span data-stu-id="6222e-578">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="6222e-579">Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.</span><span class="sxs-lookup"><span data-stu-id="6222e-579">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="6222e-580">Se resolvió un problema que causaba que las operaciones de cortar y pegar junto a una mesa fallaran cuando se co autoría con otros.</span><span class="sxs-lookup"><span data-stu-id="6222e-580">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="6222e-581">Se resolvió un problema que causaba interrupciones de co autoría cuando se cambiaban las propiedades personalizadas con macros en ejecución.</span><span class="sxs-lookup"><span data-stu-id="6222e-581">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="6222e-582">Hubo un problema en el que no se podían seleccionar elementos del cuadro combinado de un formulario de WPF (Windows Presentation Foundation) que fue abierto por un complemento.</span><span class="sxs-lookup"><span data-stu-id="6222e-582">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="6222e-583">Se ha resuelto un problema que puede haber causado un bloqueo al buscar archivos recientes cuando no hay ningún libro de trabajo abierto.</span><span class="sxs-lookup"><span data-stu-id="6222e-583">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="6222e-584">Se ha corregido un problema que hacía que el borde de un control de cuadro de grupo no estuviera visible en la vista previa de impresión o al imprimirlo.</span><span class="sxs-lookup"><span data-stu-id="6222e-584">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="6222e-585">Se ha corregido un problema por el que algunos usuarios podían haber experimentado múltiples ventanas emergentes cuando los enlaces externos estaban presentes en el libro de trabajo.</span><span class="sxs-lookup"><span data-stu-id="6222e-585">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="6222e-586">Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al usar una macro de VBA para borrar el contenido de un rango.</span><span class="sxs-lookup"><span data-stu-id="6222e-586">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="6222e-587">Se ha corregido un problema con VBA por el que escribir valores en un rango era más lento de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="6222e-587">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="6222e-588">Se ha corregido un problema por el que la propiedad "Valor se cruza en" en el eje del gráfico cambiaba inesperadamente al guardar y volver a abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="6222e-588">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="6222e-589">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="6222e-589">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="6222e-590">Se ha corregido un problema que provocaba un rendimiento lento al eliminar columnas que contenían celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="6222e-590">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="6222e-591">Se ha corregido un problema con la escala de texto en los controles de formulario cuando se mostraba la Vista previa de impresión.</span><span class="sxs-lookup"><span data-stu-id="6222e-591">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="6222e-592">Cuando se copian datos filtrados por colores en una columna con un ancho diferente, los valores no se pegan.</span><span class="sxs-lookup"><span data-stu-id="6222e-592">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="6222e-593">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="6222e-593">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="6222e-594">Se ha corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.</span><span class="sxs-lookup"><span data-stu-id="6222e-594">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="6222e-595">Se ha corregido un problema que provocaba que, al hacer clic en un hipervínculo marcado en el propio libro, se ocultara dicho libro.</span><span class="sxs-lookup"><span data-stu-id="6222e-595">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="6222e-596">Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.</span><span class="sxs-lookup"><span data-stu-id="6222e-596">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="6222e-597">La funcionalidad de Texto a columna puede fallar en algunas configuraciones regionales.</span><span class="sxs-lookup"><span data-stu-id="6222e-597">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="6222e-598">Es posible que los usuarios vean un error si acceden a un rango con nombre oculto.</span><span class="sxs-lookup"><span data-stu-id="6222e-598">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="6222e-599">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="6222e-599">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="6222e-600">Se ha corregido un problema por el que el tamaño de archivo de las imágenes en los encabezados del gráfico aumentaba cuando se guardaba el libro que contenía el gráfico.</span><span class="sxs-lookup"><span data-stu-id="6222e-600">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>

- <span data-ttu-id="6222e-601">Problema de rendimiento con las Funciones Asincrónicas Definidas por el Usuario que hacía que se ejecutaran sincrónicamente.</span><span class="sxs-lookup"><span data-stu-id="6222e-601">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="6222e-602">Mejoras significativas en el rendimiento de la eliminación de columnas con celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="6222e-602">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="6222e-603">Se resolvió un problema en el que la selección de una celda después del desplazamiento podía dar lugar a que se seleccionara la celda incorrecta.</span><span class="sxs-lookup"><span data-stu-id="6222e-603">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="6222e-604">Se ha resuelto un problema en el que la función de búsqueda puede devolver un error.</span><span class="sxs-lookup"><span data-stu-id="6222e-604">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="6222e-605">Se ha corregido un problema que provoca la corrupción de caracteres DBCS en los libros con referencias cruzadas manteniendo los rangos de selección sincronizados con el libro con referencias cruzadas.</span><span class="sxs-lookup"><span data-stu-id="6222e-605">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="6222e-606">Se ha corregido un problema en el que los controles de casilla podían reducirse al usar el autoajuste para ajustar el alto de fila.</span><span class="sxs-lookup"><span data-stu-id="6222e-606">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>

- <span data-ttu-id="6222e-607">Problema de rendimiento bajo al hacer clic en el botón Color de fuente cuando un archivo tiene un formato condicional extenso.</span><span class="sxs-lookup"><span data-stu-id="6222e-607">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="6222e-608">Se ha corregido un problema por el que el área de impresión en la vista previa de impresión no era correcta.</span><span class="sxs-lookup"><span data-stu-id="6222e-608">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="6222e-609">Excel puede tener problemas al editar un archivo protegido desde una red compartida no confiable.</span><span class="sxs-lookup"><span data-stu-id="6222e-609">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="6222e-610">Hemos mejorado significativamente el rendimiento del filtrado por color.</span><span class="sxs-lookup"><span data-stu-id="6222e-610">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="6222e-611">Se ha resuelto un problema por el que los libros de trabajo creados en versiones anteriores de Office podían hacer que Excel se colgara al abrirlos en las versiones actuales de Office.</span><span class="sxs-lookup"><span data-stu-id="6222e-611">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="6222e-612">Se habilitaron más de 16 complementos para que se muestren al navegar en el administrador de complementos.</span><span class="sxs-lookup"><span data-stu-id="6222e-612">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="6222e-613">Se ha corregido un problema que impedía que los hipervínculos se pegaran en algunas hojas protegidas.</span><span class="sxs-lookup"><span data-stu-id="6222e-613">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="6222e-614">Este cambio evita un problema con ciertos controladores de gráficos Intel al aprovechar el procesamiento del software.</span><span class="sxs-lookup"><span data-stu-id="6222e-614">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="6222e-615">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="6222e-615">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="6222e-616">Esta actualización corrige un error por el cual los documentos de Office pueden fallar al subirlos a OneDrive para la Empresa con el mensaje "Error al cargar".</span><span class="sxs-lookup"><span data-stu-id="6222e-616">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="6222e-617">Corregir problema en la característica Ideas de Excel, error al cargar el complemento haciendo clic en el botón Ideas en el cliente Win32.</span><span class="sxs-lookup"><span data-stu-id="6222e-617">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span> 

### <a name="onenote"></a><span data-ttu-id="6222e-618">OneNote</span><span class="sxs-lookup"><span data-stu-id="6222e-618">OneNote</span></span>

- <span data-ttu-id="6222e-619">Localiza la notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="6222e-619">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="6222e-620">Outlook</span><span class="sxs-lookup"><span data-stu-id="6222e-620">Outlook</span></span>

- <span data-ttu-id="6222e-621">Los vínculos de cid:image de los mensajes de Outlook ahora se pueden romper correctamente cuando se solicite.</span><span class="sxs-lookup"><span data-stu-id="6222e-621">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="6222e-622">Se ha corregido un problema que causaba que los usuarios que actualizaban su buzón de la autenticación básica a la moderna, terminaban con una cuenta incorrecta asociada a su perfil de Outlook.</span><span class="sxs-lookup"><span data-stu-id="6222e-622">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="6222e-623">Se ha corregido un problema que hacía que los complementos web accedieran a los mensajes de la administración de derechos digitales cuando no deberían hacerlo.</span><span class="sxs-lookup"><span data-stu-id="6222e-623">Addresses an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="6222e-624">Se ha corregido un problema que causó que las URLS de enlace simple no se mostraran en algunos enlaces seguros.</span><span class="sxs-lookup"><span data-stu-id="6222e-624">Addresses an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="6222e-625">Esto actualiza la lógica de bloqueo de adjuntos en Outlook para bloquear también los adjuntos de Python.</span><span class="sxs-lookup"><span data-stu-id="6222e-625">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="6222e-626">Corrige un problema que causaba que un subconjunto de usuarios de POP3 viesen todos los correos electrónicos como texto sin formato, independientemente de la configuración.</span><span class="sxs-lookup"><span data-stu-id="6222e-626">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="6222e-627">Esta corrección restaurará la vista de los mensajes con formato HTML.</span><span class="sxs-lookup"><span data-stu-id="6222e-627">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="6222e-628">Se ha corregido un problema que hacía que los usuarios experimentaran un error de permiso al copiar elementos de su calendario principal a un calendario de grupo.</span><span class="sxs-lookup"><span data-stu-id="6222e-628">Addresses an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="6222e-629">Se ha corregido un problema que hacía que los usuarios no pudieran acceder a las sugerencias de ubicación a través de un lector de pantalla.</span><span class="sxs-lookup"><span data-stu-id="6222e-629">Addresses an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="6222e-630">Se ha corregido un problema por el que los usuarios notaban un retraso evidente al interactuar con sus carpetas de buzón mediante métodos abreviados de teclado.</span><span class="sxs-lookup"><span data-stu-id="6222e-630">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="6222e-631">Se ha corregido un problema que causaba una pérdida de memoria en sesiones de Outlook muy largas.</span><span class="sxs-lookup"><span data-stu-id="6222e-631">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="6222e-632">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.</span><span class="sxs-lookup"><span data-stu-id="6222e-632">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="6222e-633">Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al abrir el cuadro de diálogo de Reglas.</span><span class="sxs-lookup"><span data-stu-id="6222e-633">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="6222e-634">Se ha corregido un problema que haría que los usuarios experimentaran un bloqueo en Outlook al interactuar con ciertos vínculos seguros.</span><span class="sxs-lookup"><span data-stu-id="6222e-634">Addresses an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="6222e-635">Se ha corregido un problema que causaba ambigüedad para los administradores sobre si un delegado ya había respondido a una convocatoria de reunión determinada.</span><span class="sxs-lookup"><span data-stu-id="6222e-635">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="6222e-636">Se ha corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.</span><span class="sxs-lookup"><span data-stu-id="6222e-636">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="6222e-637">Se ha corregido un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "OK" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="6222e-637">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="6222e-638">Este cambio permite a los administradores habilitar una política para preferir el correo electrónico de la cuenta proporcionada en los avisos de autorización de AutoDiscover sobre el UPN.</span><span class="sxs-lookup"><span data-stu-id="6222e-638">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="6222e-639">De forma predeterminada, detección automática prefiere el UPN de la cuenta, cuando está disponible.</span><span class="sxs-lookup"><span data-stu-id="6222e-639">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="6222e-640">Se ha corregido un problema que provocaba que los usuarios vieran un error en la búsqueda con grupos modernos.</span><span class="sxs-lookup"><span data-stu-id="6222e-640">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="6222e-641">Se ha corregido un problema que causaba que los usuarios de Outlook se quedaran atascados en el estado "Necesita contraseña" en ciertos escenarios.</span><span class="sxs-lookup"><span data-stu-id="6222e-641">Addresses an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="6222e-642">Se ha corregido un problema que provocaba que los usuarios experimentaran errores de sincronización al procesar mensajes de conflicto.</span><span class="sxs-lookup"><span data-stu-id="6222e-642">Addresses an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="6222e-643">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al abrir archivos .msg y .oft después de aplicar una actualización reciente de Windows.</span><span class="sxs-lookup"><span data-stu-id="6222e-643">Addresses an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="6222e-644">Se ha corregido un problema que provocaba que los usuarios experimentaran un error en la pantalla de "carga del perfil" al iniciar Outlook.</span><span class="sxs-lookup"><span data-stu-id="6222e-644">Addresses an issue that caused users to experience a hang at the "Loading Profile" screen when Outlook is starting up.</span></span>

- <span data-ttu-id="6222e-645">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al seleccionar determinados resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="6222e-645">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="6222e-646">Se ha corregido un problema que hizo que el botón "Guardar en la nube" faltara en las herramientas de datos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="6222e-646">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="6222e-647">De forma predeterminada, las etiquetas de directivas de retención muestran el período de tiempo de retención entre paréntesis.</span><span class="sxs-lookup"><span data-stu-id="6222e-647">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="6222e-648">Esto proporciona una clave del registro para permitir que los administradores especifiquen que solo se debería mostrar el nombre de la directiva.</span><span class="sxs-lookup"><span data-stu-id="6222e-648">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="6222e-649">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = predeterminado 1 = solo se mostrará el PolicyName para el texto de la política de retención.</span><span class="sxs-lookup"><span data-stu-id="6222e-649">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

- <span data-ttu-id="6222e-650">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al cerrar Outlook.</span><span class="sxs-lookup"><span data-stu-id="6222e-650">Addresses an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="6222e-651">Se ha corregido un problema que provocaba que los clientes vieran una lista de salas vacías en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="6222e-651">Addresses an issue that caused customers to see an empty room list in some scenarios.</span></span>

- <span data-ttu-id="6222e-652">Se ha corregido un problema que provocaba que los usuarios viesen bloqueos intermitentes al cambiar de vista.</span><span class="sxs-lookup"><span data-stu-id="6222e-652">Addresses an issue that caused users to see intermittent crashes when changing views.</span></span>

- <span data-ttu-id="6222e-653">Corrige un problema que provocaba que los usuarios tuvieran problemas al intentar sincronizar carpetas del calendario compartido con el OST, lo que producía errores en los permisos al tratar de interactuar con estas carpetas.</span><span class="sxs-lookup"><span data-stu-id="6222e-653">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>

- <span data-ttu-id="6222e-654">Se ha corregido un problema que causaba que los usuarios sufrieran un error al visualizar más de 30 calendarios en un entorno Citrix.</span><span class="sxs-lookup"><span data-stu-id="6222e-654">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="6222e-655">Aquí está el [KB individual, donde se ha documentado esto para versiones anteriores](https://support.microsoft.com/es-ES/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span><span class="sxs-lookup"><span data-stu-id="6222e-655">Here's the individual [KB where this was documented for previous versions](https://support.microsoft.com/es-ES/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span></span>

- <span data-ttu-id="6222e-656">Corrige un problema con la selección de algoritmos SMIME.</span><span class="sxs-lookup"><span data-stu-id="6222e-656">Corrects an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="6222e-657">Se ha corregido un problema que provocó que las sugerencias de la política no se mostraran al utilizar un remitente alternativo.</span><span class="sxs-lookup"><span data-stu-id="6222e-657">Addresses an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="6222e-658">Se ha corregido un problema que hizo que los usuarios vieran sugerencias de salas para reuniones que se produjeron fuera de las horas de disponibilidad de dichas salas.</span><span class="sxs-lookup"><span data-stu-id="6222e-658">Addresses an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="6222e-659">Se ha corregido un problema para los usuarios que no hablan inglés, en el que la línea de asunto de un correo electrónico era increíblemente pequeña.</span><span class="sxs-lookup"><span data-stu-id="6222e-659">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="6222e-660">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al intentar crear una regla a partir de un mensaje de "Conversación perdida".</span><span class="sxs-lookup"><span data-stu-id="6222e-660">Addresses an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="6222e-661">Se ha corregido un problema que causaba que algunos usuarios vieran carpetas especiales duplicadas al agregar una cuenta de Exchange secundaria.</span><span class="sxs-lookup"><span data-stu-id="6222e-661">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="6222e-662">Se ha corregido un problema que hacía que los usuarios vieran el truncamiento del cuerpo del mensaje al reenviar mensajes HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="6222e-662">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="6222e-663">Se ha corregido un problema que hacía que los usuarios observaran una pérdida de memoria en el proceso de Outlook.</span><span class="sxs-lookup"><span data-stu-id="6222e-663">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="6222e-664">Se ha corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.</span><span class="sxs-lookup"><span data-stu-id="6222e-664">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="6222e-665">Se ha corregido un problema que provocaba un error ocasional en la búsqueda de la carpeta actual.</span><span class="sxs-lookup"><span data-stu-id="6222e-665">Addresses an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="6222e-666">Se ha corregido un problema que hizo que algunos usuarios encontraran errores de autenticación al intentar recuperar su configuración de nube para Outlook.</span><span class="sxs-lookup"><span data-stu-id="6222e-666">Addresses an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="6222e-667">Se ha corregido un problema que causó un bloqueo en la experiencia de los comentarios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="6222e-667">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="6222e-668">Se ha corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.</span><span class="sxs-lookup"><span data-stu-id="6222e-668">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="6222e-669">Se ha corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.</span><span class="sxs-lookup"><span data-stu-id="6222e-669">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6222e-670">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6222e-670">PowerPoint</span></span>

- <span data-ttu-id="6222e-671">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="6222e-671">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="6222e-672">Este cambio restaura el nombre accesible de los controles de vídeo de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6222e-672">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="6222e-673">Se ha corregido un problema que podría impedir que comiencen algunas animaciones</span><span class="sxs-lookup"><span data-stu-id="6222e-673">We fixed an issue which could prevent some animations from starting</span></span>

- <span data-ttu-id="6222e-674">Se ha corregido un problema en el que al copiar una diapositiva de una presentación a otra, se pueden crear patrones duplicados.</span><span class="sxs-lookup"><span data-stu-id="6222e-674">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span><br>

- <span data-ttu-id="6222e-675">Se ha mejorado un escenario de copiar y pegar: al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.</span><span class="sxs-lookup"><span data-stu-id="6222e-675">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="6222e-676">Se ha corregido un problema con el marcador de resaltado: los textos blancos con un marcador oscuro se imprimen como negros en escala de grises.</span><span class="sxs-lookup"><span data-stu-id="6222e-676">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

- <span data-ttu-id="6222e-677">Los archivos con nuevos comentarios modernos mostrarán una advertencia amarilla si se abren en una versión no soportada.</span><span class="sxs-lookup"><span data-stu-id="6222e-677">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

- <span data-ttu-id="6222e-678">Se ha corregido un problema que producía un rendimiento más lento entre los usuarios de colaboración.</span><span class="sxs-lookup"><span data-stu-id="6222e-678">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="6222e-679">Corrección de confiabilidad: se ha corregido un problema por el que el complemento de terceros podía bloquearse en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6222e-679">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="6222e-680">Se ha corregido un problema que puede producirse cuando un archivo que se abre incrementalmente contiene una diapositiva con más de una secuencia multimedia incrustada.</span><span class="sxs-lookup"><span data-stu-id="6222e-680">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="6222e-681">Se ha corregido un problema con el método Shape.Paste: cuando el usuario copiaba y pegaba la forma con el método Shape.Paste, se cambiaba la selección a la forma pegada.</span><span class="sxs-lookup"><span data-stu-id="6222e-681">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="6222e-682">Se ha corregido un problema por el que es posible que la barra de mensajes de advertencia de seguridad no aparezca para los complementos en los que no se confía al iniciar PowerPoint por primera vez.</span><span class="sxs-lookup"><span data-stu-id="6222e-682">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

- <span data-ttu-id="6222e-683">Se ha corregido un problema por el que algunos complementos producían errores inesperados alrededor de las formas en gráficos.</span><span class="sxs-lookup"><span data-stu-id="6222e-683">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="6222e-684">Evita que los usuarios de PowerPoint se encuentren con un error cuando intentan hacer una presentación en línea.</span><span class="sxs-lookup"><span data-stu-id="6222e-684">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

### <a name="project"></a><span data-ttu-id="6222e-685">Project</span><span class="sxs-lookup"><span data-stu-id="6222e-685">Project</span></span>

- <span data-ttu-id="6222e-686">Se ha corregido un problema para permitir que los usuarios en Windows 7 puedan abrir proyectos desde Project Web App y sitios de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="6222e-686">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="6222e-687">Se identificó un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de sólo lectura.</span><span class="sxs-lookup"><span data-stu-id="6222e-687">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="6222e-688">El comando Level All no resuelve adecuadamente una sobreasignación de recursos.</span><span class="sxs-lookup"><span data-stu-id="6222e-688">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="6222e-689">Si tiene una tarea sin nada de trabajo, es posible que la tarea no se pueda marcar como completada y siempre se mostrará en el 99 %.</span><span class="sxs-lookup"><span data-stu-id="6222e-689">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

- <span data-ttu-id="6222e-690">Se ha corregido un problema en el que el trabajo real puede ser diferente entre el parte de horas y el plan del proyecto debido a que los calendarios de recursos no se actualizan cuando cambia el calendario base.</span><span class="sxs-lookup"><span data-stu-id="6222e-690">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="skype"></a><span data-ttu-id="6222e-691">Skype</span><span class="sxs-lookup"><span data-stu-id="6222e-691">Skype</span></span>

- <span data-ttu-id="6222e-692">Se ha corregido el nombre del título de la conversación con pestañas mientras se mantenía más de una conversación.</span><span class="sxs-lookup"><span data-stu-id="6222e-692">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="visio"></a><span data-ttu-id="6222e-693">Visio</span><span class="sxs-lookup"><span data-stu-id="6222e-693">Visio</span></span>

- <span data-ttu-id="6222e-694">La exportación como SVG de Visio estaba fallando por una variedad de formas.</span><span class="sxs-lookup"><span data-stu-id="6222e-694">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="6222e-695">Word</span><span class="sxs-lookup"><span data-stu-id="6222e-695">Word</span></span>

- <span data-ttu-id="6222e-696">Los vínculos de cid:image de los mensajes de Outlook ahora se pueden romper correctamente cuando se solicite.</span><span class="sxs-lookup"><span data-stu-id="6222e-696">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="6222e-697">Se ha corregido un problema que podría haber provocado problemas de escala al imprimir en impresoras Deskjet</span><span class="sxs-lookup"><span data-stu-id="6222e-697">We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span>

- <span data-ttu-id="6222e-698">Se ha corregido un problema al Ajustar texto en la tabla.</span><span class="sxs-lookup"><span data-stu-id="6222e-698">We fixed an issue in Fit Text in Table.</span></span>

- <span data-ttu-id="6222e-699">Hemos corregido un problema en los cambios de pista que a veces van en un bucle infinito.</span><span class="sxs-lookup"><span data-stu-id="6222e-699">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="6222e-700">Corregido un problema ocasional en el que al guardar un archivo existente siempre aparece el cuadro de diálogo Guardar como, pero el archivo nunca se guarda.</span><span class="sxs-lookup"><span data-stu-id="6222e-700">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="6222e-701">Se ha corregido un problema al combinar dos documentos en uno.</span><span class="sxs-lookup"><span data-stu-id="6222e-701">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="6222e-702">Se ha corregido un problema con la característica Comparación para los documentos protegidos para la edición.</span><span class="sxs-lookup"><span data-stu-id="6222e-702">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="6222e-703">Se han corregido varios problemas que hacían que la aplicación se colgara al apagarse.</span><span class="sxs-lookup"><span data-stu-id="6222e-703">Fixes various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="6222e-704">También se corrigieron ciertos fallos relacionados con los complementos.</span><span class="sxs-lookup"><span data-stu-id="6222e-704">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6222e-705">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="6222e-705">Office Suite</span></span>

- <span data-ttu-id="6222e-706">Corregido el problema de la identificación incorrecta del nombre de la nueva era "Reiwa" en hiragana y kanji como una expresión mal escrita o poco gramatical.</span><span class="sxs-lookup"><span data-stu-id="6222e-706">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="6222e-707">Corregido un problema que hacía que los usuarios recibieran el mensaje "Lo sentimos, algo nos impide compartir esto" al intentar compartir archivos almacenados en SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="6222e-707">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="6222e-708">Se ha solucionado un problema que podía causar la pérdida de datos en sesiones que implicaban tanto la co autoría como la edición fuera de línea en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6222e-708">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="6222e-709">Esta es una solución para un fallo que los usuarios podrían sufrir al abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="6222e-709">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="6222e-710">En algunos casos, un archivo de sharepoint respaldado por un motor de sincronización podría mostrar "Guardado" pero no haber guardado realmente ningún cambio, lo que provocaría la pérdida de datos.</span><span class="sxs-lookup"><span data-stu-id="6222e-710">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="6222e-711">Se resolvió un problema que impedía a los usuarios guardar documentos de Word, Excel y PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6222e-711">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="6222e-712">Este problema afecta a los usuarios que crean un nuevo archivo y muestra la opción "Guardar como diálogo" después de hacer clic en el icono Guardar o presionar Ctrl + S.</span><span class="sxs-lookup"><span data-stu-id="6222e-712">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="6222e-713">Se ha corregido un bloqueo en Word al dejar una API obsoleta.</span><span class="sxs-lookup"><span data-stu-id="6222e-713">Fixes a crash in Word by moving away from a deprecated API.</span></span>

- <span data-ttu-id="6222e-714">Se ha corregido un problema por el que los caracteres katakana de medio ancho no giraban correctamente cuando estaban en cuadros de texto verticales en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6222e-714">Fixing an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="6222e-715">Se ha corregido un problema de perf en Win7 en el que la galería de formas de inserción de la cinta en todas las aplicaciones tardaba aproximadamente 4 segundos en aparecer.</span><span class="sxs-lookup"><span data-stu-id="6222e-715">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="6222e-716">Corregido un error por el que la información de accesibilidad no se mostraba en la losa del lugar de información de los bastidores.</span><span class="sxs-lookup"><span data-stu-id="6222e-716">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="6222e-717">Mejora de la fiabilidad del proceso de actualización de Office en lo que respecta a la integridad del registro.</span><span class="sxs-lookup"><span data-stu-id="6222e-717">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="6222e-718">Hemos actualizado los nombres de canal para las bifurcaciones de enero y julio de 2019 con los nuevos nombres de canal.</span><span class="sxs-lookup"><span data-stu-id="6222e-718">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="6222e-719">Se ha corregido un problema por el que las actualizaciones se bloqueaban inesperadamente en las redes de uso medido.</span><span class="sxs-lookup"><span data-stu-id="6222e-719">Corrects an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="6222e-720">Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.</span><span class="sxs-lookup"><span data-stu-id="6222e-720">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="6222e-721">En determinadas circunstancias, los accesos directos de Office pueden desaparecer tras una actualización.</span><span class="sxs-lookup"><span data-stu-id="6222e-721">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="6222e-722">Esta actualización mejora la fiabilidad en la publicación de los accesos directos de Office.</span><span class="sxs-lookup"><span data-stu-id="6222e-722">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="6222e-723">Corrige un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.</span><span class="sxs-lookup"><span data-stu-id="6222e-723">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="6222e-724">Se ha corregido un problema en el que una actualización no se aplicaría en ciertos casos en los que el usuario no es un administrador y la cuenta del sistema no tenía conectividad de red.</span><span class="sxs-lookup"><span data-stu-id="6222e-724">Resolves an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="6222e-725">Se ha solucionado un problema por el que los mensajes de actualización de Office aparecían en un idioma diferente al esperado.</span><span class="sxs-lookup"><span data-stu-id="6222e-725">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="6222e-726">En el futuro, los mensajes de actualización de Office coincidirán correctamente con el idioma de visualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="6222e-726">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="6222e-727">Se ha mejorado la confiabilidad al descargar las actualizaciones de Office al reanudar las descargas que pueden haberse interrumpido anteriormente.</span><span class="sxs-lookup"><span data-stu-id="6222e-727">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="6222e-728">Se han corregido los problemas relacionados con la propiedad Textbox/Shape Autofit en los plug-ins de terceros.</span><span class="sxs-lookup"><span data-stu-id="6222e-728">Address issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="6222e-729">Este cambio corrige el procesamiento de imágenes después de abrir un archivo dañado.</span><span class="sxs-lookup"><span data-stu-id="6222e-729">This change addresses correctly rendering images after opening a corrupted file.</span></span>

- <span data-ttu-id="6222e-730">Este cambio corrige el procesamiento lento de algunos gráficos de dispersión con marcadores.</span><span class="sxs-lookup"><span data-stu-id="6222e-730">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="6222e-731">Se ha corregido un problema por el que las vistas de árboles grandes podían dar lugar a un bloqueo</span><span class="sxs-lookup"><span data-stu-id="6222e-731">We fixed an issue where large tree views could result in a crash</span></span>

- <span data-ttu-id="6222e-732">Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.</span><span class="sxs-lookup"><span data-stu-id="6222e-732">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="6222e-733">Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="6222e-733">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="6222e-734">Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="6222e-734">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-july-14"></a><span data-ttu-id="6222e-736">Versión 1902: 14 de julio</span><span class="sxs-lookup"><span data-stu-id="6222e-736">Version 1902: July 14</span></span>
<span data-ttu-id="6222e-737">*Versión 1902 (compilación 11328.20624)*</span><span class="sxs-lookup"><span data-stu-id="6222e-737">*Version 1902 (Build 11328.20624)*</span></span>

<span data-ttu-id="6222e-738">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-738">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1908-june-09"></a><span data-ttu-id="6222e-739">Versión 1908: 09 de junio</span><span class="sxs-lookup"><span data-stu-id="6222e-739">Version 1908: June 09</span></span>
<span data-ttu-id="6222e-740">*Versión 1908 (compilación 11929.20838)*</span><span class="sxs-lookup"><span data-stu-id="6222e-740">*Version 1908 (Build 11929.20838)*</span></span>

<span data-ttu-id="6222e-741">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-741">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6222e-743">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-743">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6222e-744">Excel</span><span class="sxs-lookup"><span data-stu-id="6222e-744">Excel</span></span>

- <span data-ttu-id="6222e-745">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="6222e-745">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="6222e-746">Se ha corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.</span><span class="sxs-lookup"><span data-stu-id="6222e-746">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="6222e-747">Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.</span><span class="sxs-lookup"><span data-stu-id="6222e-747">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="6222e-748">Outlook</span><span class="sxs-lookup"><span data-stu-id="6222e-748">Outlook</span></span>

- <span data-ttu-id="6222e-749">Se ha corregido un problema que hacía que los usuarios vieran truncado el cuerpo del mensaje al reenviar mensajes HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="6222e-749">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6222e-750">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6222e-750">Office Suite</span></span>

- <span data-ttu-id="6222e-751">Hemos actualizado los nombres de canal para las bifurcaciones de enero y julio de 2019 con los nuevos nombres de canal.</span><span class="sxs-lookup"><span data-stu-id="6222e-751">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>


[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-june-09"></a><span data-ttu-id="6222e-753">Versión 1902: 09 de junio</span><span class="sxs-lookup"><span data-stu-id="6222e-753">Version 1902: June 09</span></span>
<span data-ttu-id="6222e-754">*Versión 1902 (compilación 11328.20602)*</span><span class="sxs-lookup"><span data-stu-id="6222e-754">*Version 1902 (Build 11328.20602)*</span></span>

<span data-ttu-id="6222e-755">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-755">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6222e-757">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-757">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="6222e-758">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6222e-758">Office Suite</span></span>

- <span data-ttu-id="6222e-759">Hemos actualizado los nombres de canal para las bifurcaciones de enero y julio de 2019 con los nuevos nombres de canal.</span><span class="sxs-lookup"><span data-stu-id="6222e-759">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="6222e-760">Se han eliminado las referencias obsoletas de los archivos de línea base que producian errores en la compilación C2R.</span><span class="sxs-lookup"><span data-stu-id="6222e-760">We removed obsolete references from the baseline files that were breaking the C2R Build.</span></span>



[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-may-12"></a><span data-ttu-id="6222e-762">Versión 1908: 12 de mayo</span><span class="sxs-lookup"><span data-stu-id="6222e-762">Version 1908: May 12</span></span>
<span data-ttu-id="6222e-763">*Versión 1908 (compilación 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="6222e-763">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="6222e-764">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-764">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6222e-766">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-766">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6222e-767">Excel</span><span class="sxs-lookup"><span data-stu-id="6222e-767">Excel</span></span>

- <span data-ttu-id="6222e-768">Cuando se copian datos filtrados por colores en una columna con un ancho diferente, los valores no se pegan.</span><span class="sxs-lookup"><span data-stu-id="6222e-768">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

### <a name="outlook"></a><span data-ttu-id="6222e-769">Outlook</span><span class="sxs-lookup"><span data-stu-id="6222e-769">Outlook</span></span>

- <span data-ttu-id="6222e-770">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al abrir archivos .msg y .oft después de aplicar una actualización reciente de Windows.</span><span class="sxs-lookup"><span data-stu-id="6222e-770">Addressed an issue that caused users to experience a crash when opening msg and .oft files after applying a recent Windows update.</span></span>

### <a name="word"></a><span data-ttu-id="6222e-771">Word</span><span class="sxs-lookup"><span data-stu-id="6222e-771">Word</span></span>

- <span data-ttu-id="6222e-772">Se ha corregido un problema al combinar 2 documentos en uno.</span><span class="sxs-lookup"><span data-stu-id="6222e-772">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="6222e-773">Se ha corregido un problema con la característica Comparar de los documentos protegidos para la edición.</span><span class="sxs-lookup"><span data-stu-id="6222e-773">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-1902-may-12"></a><span data-ttu-id="6222e-775">Versión 1902:12 de mayo</span><span class="sxs-lookup"><span data-stu-id="6222e-775">Version 1902: May 12</span></span>
<span data-ttu-id="6222e-776">*Versión 1902 (compilación 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="6222e-776">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="6222e-777">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-777">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6222e-779">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-779">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="6222e-780">Outlook</span><span class="sxs-lookup"><span data-stu-id="6222e-780">Outlook</span></span>

- <span data-ttu-id="6222e-781">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al abrir archivos .msg y .oft después de aplicar una actualización reciente de Windows.</span><span class="sxs-lookup"><span data-stu-id="6222e-781">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="6222e-782">De forma predeterminada, las etiquetas de directivas de retención muestran el período de tiempo de retención entre paréntesis.</span><span class="sxs-lookup"><span data-stu-id="6222e-782">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="6222e-783">Esto proporciona una clave del registro para permitir que los administradores especifiquen que solo se debería mostrar el nombre de la directiva.</span><span class="sxs-lookup"><span data-stu-id="6222e-783">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="6222e-784">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="6222e-784">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="6222e-785">0 = predeterminado.</span><span class="sxs-lookup"><span data-stu-id="6222e-785">0 = Default.</span></span>  <span data-ttu-id="6222e-786">1 = solo se mostrará el nombre de directiva del texto de la directiva de retención.</span><span class="sxs-lookup"><span data-stu-id="6222e-786">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-1908-may-04"></a><span data-ttu-id="6222e-788">Versión 1908: 4 de mayo</span><span class="sxs-lookup"><span data-stu-id="6222e-788">Version 1908: May 04</span></span>
<span data-ttu-id="6222e-789">*Versión 1908 (Compilación 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="6222e-789">*Version 1908 (Build 11929.20752)*</span></span>

<span data-ttu-id="6222e-790">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-790">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="6222e-791">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-791">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="6222e-792">Outlook</span><span class="sxs-lookup"><span data-stu-id="6222e-792">Outlook</span></span>

- <span data-ttu-id="6222e-793">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al seleccionar determinados resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="6222e-793">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="6222e-794">Se ha corregido un problema que hacía que el botón "Guardar en la nube" faltara en las Herramientas de datos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="6222e-794">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="6222e-795">De forma predeterminada, las etiquetas de directivas de retención muestran el período de tiempo de retención entre paréntesis.</span><span class="sxs-lookup"><span data-stu-id="6222e-795">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="6222e-796">Esto proporciona una clave del registro para permitir que los administradores especifiquen que solo se debería mostrar el nombre de la directiva.</span><span class="sxs-lookup"><span data-stu-id="6222e-796">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="6222e-797">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="6222e-797">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="6222e-798">0 = predeterminado 1 = solo se mostrará el nombre de directiva del texto de la directiva de retención.</span><span class="sxs-lookup"><span data-stu-id="6222e-798">0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6222e-799">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6222e-799">Office Suite</span></span>

- <span data-ttu-id="6222e-800">Se ha corregido un problema en Visual Basic para las aplicaciones de Microsoft Office, por el que la aplicación de Office consideraba como corruptos ciertos proyectos de VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre o la ruta de la biblioteca.</span><span class="sxs-lookup"><span data-stu-id="6222e-800">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="6222e-801">Versión 1902: 4 de mayo</span><span class="sxs-lookup"><span data-stu-id="6222e-801">Version 1902: May 04</span></span>
<span data-ttu-id="6222e-802">*Versión 1902 (compilación 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="6222e-802">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="6222e-803">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-803">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="6222e-804">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6222e-804">Office Suite</span></span>

- <span data-ttu-id="6222e-805">Se ha corregido un problema en Visual Basic para las aplicaciones de Microsoft Office, por el que la aplicación de Office consideraba como corruptos ciertos proyectos de VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre o la ruta de la biblioteca.</span><span class="sxs-lookup"><span data-stu-id="6222e-805">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1908-april-26"></a><span data-ttu-id="6222e-806">Versión 1908: 26 de abril</span><span class="sxs-lookup"><span data-stu-id="6222e-806">Version 1908: April 26</span></span>
<span data-ttu-id="6222e-807">*Versión 1908 (Compilación 11929.20736)*</span><span class="sxs-lookup"><span data-stu-id="6222e-807">*Version 1908 (Build 11929.20736)*</span></span>

<span data-ttu-id="6222e-808">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-808">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="6222e-809">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-809">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6222e-810">Excel</span><span class="sxs-lookup"><span data-stu-id="6222e-810">Excel</span></span>

- <span data-ttu-id="6222e-811">Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al usar una macro de VBA para borrar el contenido de un rango.</span><span class="sxs-lookup"><span data-stu-id="6222e-811">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="6222e-812">Se ha corregido un problema con VBA por el que escribir valores en un rango era más lento de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="6222e-812">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="6222e-813">Se ha corregido un problema por el que la propiedad "Value Crosses At" en el eje del gráfico cambiaba inesperadamente al guardar y volver a abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="6222e-813">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="6222e-814">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="6222e-814">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


### <a name="onenote"></a><span data-ttu-id="6222e-815">OneNote</span><span class="sxs-lookup"><span data-stu-id="6222e-815">OneNote</span></span>

- <span data-ttu-id="6222e-816">Localiza la notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="6222e-816">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>


## <a name="version-1908-april-14"></a><span data-ttu-id="6222e-817">Versión 1908: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="6222e-817">Version 1908: April 14</span></span>
<span data-ttu-id="6222e-818">*Versión 1908 (compilación 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="6222e-818">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="6222e-819">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-819">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6222e-821">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-821">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6222e-822">Excel</span><span class="sxs-lookup"><span data-stu-id="6222e-822">Excel</span></span>

- <span data-ttu-id="6222e-823">Se ha corregido un problema que provocaba un rendimiento lento al eliminar columnas que contenían celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="6222e-823">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="6222e-824">Se ha corregido un problema con la escala de texto en los controles de formulario cuando se mostraba la Vista previa de impresión.</span><span class="sxs-lookup"><span data-stu-id="6222e-824">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="6222e-825">Skype</span><span class="sxs-lookup"><span data-stu-id="6222e-825">Skype</span></span>

- <span data-ttu-id="6222e-826">Se ha corregido el nombre del título de la conversación con pestañas mientras se mantenía más de una conversación.</span><span class="sxs-lookup"><span data-stu-id="6222e-826">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="6222e-827">Outlook</span><span class="sxs-lookup"><span data-stu-id="6222e-827">Outlook</span></span>

- <span data-ttu-id="6222e-828">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al cerrar Outlook.</span><span class="sxs-lookup"><span data-stu-id="6222e-828">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="6222e-829">Se ha corregido un problema que provocaba que los clientes vieran una lista de salas vacías en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="6222e-829">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6222e-830">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6222e-830">PowerPoint</span></span>

- <span data-ttu-id="6222e-831">Se ha corregido un problema con el marcador de resaltado: los textos blancos con un marcador oscuro se imprimen como negros en escala de grises.</span><span class="sxs-lookup"><span data-stu-id="6222e-831">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="6222e-832">Word</span><span class="sxs-lookup"><span data-stu-id="6222e-832">Word</span></span>

- <span data-ttu-id="6222e-833">Se ha corregido un problema al Ajustar texto en la tabla.</span><span class="sxs-lookup"><span data-stu-id="6222e-833">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="6222e-834">Versión 1902: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="6222e-834">Version 1902: April 14</span></span>
<span data-ttu-id="6222e-835">*Versión 1902 (compilación 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="6222e-835">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="6222e-836">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-836">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-march-10"></a><span data-ttu-id="6222e-838">Versión 1908: 10 de marzo</span><span class="sxs-lookup"><span data-stu-id="6222e-838">Version 1908: March 10</span></span>
<span data-ttu-id="6222e-839">*Versión 1908 (compilación 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="6222e-839">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="6222e-840">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-840">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6222e-842">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-842">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6222e-843">Excel</span><span class="sxs-lookup"><span data-stu-id="6222e-843">Excel</span></span>

- <span data-ttu-id="6222e-844">Se ha corregido un problema por el que algunos usuarios podían haber experimentado múltiples ventanas emergentes cuando los enlaces externos estaban presentes en el libro de trabajo.</span><span class="sxs-lookup"><span data-stu-id="6222e-844">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="6222e-845">La funcionalidad de Texto a columna puede fallar en algunas configuraciones regionales.</span><span class="sxs-lookup"><span data-stu-id="6222e-845">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="6222e-846">Los usuarios pueden encontrar un error al acceder a un rango con nombre oculto.</span><span class="sxs-lookup"><span data-stu-id="6222e-846">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="6222e-847">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6222e-847">PowerPoint</span></span>

- <span data-ttu-id="6222e-848">Se ha corregido un problema con el método Shape.Paste: cuando el usuario copiaba y pegaba la forma con el método Shape.Paste, se cambiaba la selección a la forma pegada.</span><span class="sxs-lookup"><span data-stu-id="6222e-848">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="6222e-849">Word</span><span class="sxs-lookup"><span data-stu-id="6222e-849">Word</span></span>

- <span data-ttu-id="6222e-850">Corregido un problema ocasional en el que al guardar un archivo existente siempre aparece el cuadro de diálogo Guardar como, pero el archivo nunca se guarda.</span><span class="sxs-lookup"><span data-stu-id="6222e-850">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="6222e-851">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6222e-851">Office Suite</span></span>

- <span data-ttu-id="6222e-852">Este cambio corrige el procesamiento lento de algunos gráficos de dispersión con marcadores.</span><span class="sxs-lookup"><span data-stu-id="6222e-852">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="6222e-853">Versión 1902: 10 de marzo</span><span class="sxs-lookup"><span data-stu-id="6222e-853">Version 1902: March 10</span></span>
<span data-ttu-id="6222e-854">*Versión 1902 (compilación 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="6222e-854">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="6222e-855">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-855">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-february-11"></a><span data-ttu-id="6222e-857">Versión 1908: 11 de febrero</span><span class="sxs-lookup"><span data-stu-id="6222e-857">Version 1908: February 11</span></span>
<span data-ttu-id="6222e-858">*Versión 1908 (Compilación 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="6222e-858">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="6222e-859">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-859">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6222e-861">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-861">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6222e-862">Excel</span><span class="sxs-lookup"><span data-stu-id="6222e-862">Excel</span></span>

- <span data-ttu-id="6222e-863">Esta actualización corrige un problema que provoca un error siempre que se utilizaba VBA para agregar una imagen al encabezado o pie de página de un gráfico.</span><span class="sxs-lookup"><span data-stu-id="6222e-863">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="6222e-864">Se ha corregido un problema que hacía que el borde de un control de cuadro de grupo no estuviera visible en la vista previa de impresión o al imprimirlo.</span><span class="sxs-lookup"><span data-stu-id="6222e-864">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="6222e-865">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="6222e-865">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="6222e-866">Se ha corregido un problema por el que el tamaño de archivo de las imágenes en los encabezados del gráfico aumentaba cuando se guardaba el libro que contenía el gráfico.</span><span class="sxs-lookup"><span data-stu-id="6222e-866">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="6222e-867">Se ha corregido un problema que provoca la corrupción de caracteres DBCS en los libros con referencias cruzadas manteniendo los rangos de selección sincronizados con el libro con referencias cruzadas.</span><span class="sxs-lookup"><span data-stu-id="6222e-867">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="6222e-868">Se ha corregido un problema en el que los controles de casilla podían reducirse al usar el autoajuste para ajustar el alto de fila.</span><span class="sxs-lookup"><span data-stu-id="6222e-868">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="6222e-869">Outlook</span><span class="sxs-lookup"><span data-stu-id="6222e-869">Outlook</span></span>

- <span data-ttu-id="6222e-870">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.</span><span class="sxs-lookup"><span data-stu-id="6222e-870">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="6222e-871">Se ha corregido un problema que provocaba que los usuarios experimentaran errores de sincronización al procesar mensajes de conflicto.</span><span class="sxs-lookup"><span data-stu-id="6222e-871">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="6222e-872">Se ha corregido un problema que provocaba que los usuarios experimentaran un error en la pantalla de carga del perfil al iniciar Outlook.</span><span class="sxs-lookup"><span data-stu-id="6222e-872">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="6222e-873">Se ha corregido un problema que provocaba que los usuarios viesen bloqueos intermitentes al cambiar de vista.</span><span class="sxs-lookup"><span data-stu-id="6222e-873">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="6222e-874">Se ha corregido un problema que causaba que los usuarios sufrieran un error al visualizar más de 30 calendarios en un entorno Citrix.</span><span class="sxs-lookup"><span data-stu-id="6222e-874">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="6222e-875">[Aquí](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) está la KB individual, donde se ha documentado esto para versiones anteriores.</span><span class="sxs-lookup"><span data-stu-id="6222e-875">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="6222e-876">Corrige un problema que provocaba que los usuarios tuvieran problemas al intentar sincronizar carpetas del calendario compartido con el OST, lo que producía errores en los permisos al tratar de interactuar con estas carpetas.</span><span class="sxs-lookup"><span data-stu-id="6222e-876">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="6222e-877">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6222e-877">PowerPoint</span></span>

- <span data-ttu-id="6222e-878">Se ha mejorado un escenario de copiar y pegar. Al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.</span><span class="sxs-lookup"><span data-stu-id="6222e-878">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="6222e-879">Se ha corregido un problema que producía un rendimiento más lento entre los usuarios de colaboración.</span><span class="sxs-lookup"><span data-stu-id="6222e-879">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="6222e-880">Se ha corregido un problema que puede producirse cuando un archivo que se abre incrementalmente contiene una diapositiva con más de una secuencia multimedia incrustada.</span><span class="sxs-lookup"><span data-stu-id="6222e-880">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="6222e-881">Se ha corregido un problema por el que es posible que la barra de mensajes de advertencia de seguridad no aparezca para los complementos en los que no se confía al iniciar PowerPoint por primera vez.</span><span class="sxs-lookup"><span data-stu-id="6222e-881">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="6222e-882">Project</span><span class="sxs-lookup"><span data-stu-id="6222e-882">Project</span></span>

- <span data-ttu-id="6222e-883">Se ha corregido un problema en el que el trabajo real puede ser diferente entre el parte de horas y el plan del proyecto debido a que los calendarios de recursos no se actualizan cuando cambia el calendario base.</span><span class="sxs-lookup"><span data-stu-id="6222e-883">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="6222e-884">Word</span><span class="sxs-lookup"><span data-stu-id="6222e-884">Word</span></span>

- <span data-ttu-id="6222e-885">Se ha corregido un bloqueo en Word al dejar una API obsoleta.</span><span class="sxs-lookup"><span data-stu-id="6222e-885">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6222e-886">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6222e-886">Office Suite</span></span>

- <span data-ttu-id="6222e-887">Este cambio corrige el procesamiento de imágenes después de abrir un archivo dañado.</span><span class="sxs-lookup"><span data-stu-id="6222e-887">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-february-11"></a><span data-ttu-id="6222e-889">Versión 1902: 11 de febrero</span><span class="sxs-lookup"><span data-stu-id="6222e-889">Version 1902: February 11</span></span>
<span data-ttu-id="6222e-890">*Versión 1902 (Compilación 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="6222e-890">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="6222e-891">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-891">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6222e-893">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-893">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="6222e-894">Outlook</span><span class="sxs-lookup"><span data-stu-id="6222e-894">Outlook</span></span>

- <span data-ttu-id="6222e-895">Corregido un problema que hizo que los usuarios encontraran errores de "algoritmo de cifrado no admitido" al enviar un correo electrónico cifrado.</span><span class="sxs-lookup"><span data-stu-id="6222e-895">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="6222e-896">Word</span><span class="sxs-lookup"><span data-stu-id="6222e-896">Word</span></span>

- <span data-ttu-id="6222e-897">Se ha corregido un bloqueo en Word al dejar una API obsoleta.</span><span class="sxs-lookup"><span data-stu-id="6222e-897">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO INICIO)

## <a name="version-1808-february-11"></a><span data-ttu-id="6222e-900">Versión 1808: 11 de febrero</span><span class="sxs-lookup"><span data-stu-id="6222e-900">Version 1808: February 11</span></span>
<span data-ttu-id="6222e-901">*Versión 1808 (compilación 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="6222e-901">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="6222e-902">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-902">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-january-14"></a><span data-ttu-id="6222e-904">Versión 1908: 14 de enero</span><span class="sxs-lookup"><span data-stu-id="6222e-904">Version 1908: January 14</span></span>
<span data-ttu-id="6222e-905">*Versión 1908 (compilación 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="6222e-905">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="6222e-906">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-906">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="6222e-908">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="6222e-908">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="6222e-909">Access</span><span class="sxs-lookup"><span data-stu-id="6222e-909">Access</span></span>

- <span data-ttu-id="6222e-910">**Mantener un seguimiento de los objetos de base de datos:** ver claramente la pestaña activa, arrastrar las pestañas para reorganizarlas fácilmente y cerrar los objetos de base de datos con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="6222e-910">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="6222e-911">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="6222e-911">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="6222e-912">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="6222e-912">Switching between them has never been easier.</span></span> [<span data-ttu-id="6222e-913">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-913">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="6222e-914">**Zoom con más espacio:** agrandar el cuadro de Zoom, cambiar la fuente y hacer que Zoom lo recuerde todo.</span><span class="sxs-lookup"><span data-stu-id="6222e-914">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="6222e-915">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-915">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="6222e-916">Excel</span><span class="sxs-lookup"><span data-stu-id="6222e-916">Excel</span></span>

- <span data-ttu-id="6222e-917">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="6222e-917">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="6222e-918">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="6222e-918">Switching between them has never been easier.</span></span> [<span data-ttu-id="6222e-919">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-919">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="6222e-920">**Aumentar el alcance de su contenido:** ¿necesita que las presentaciones sean accesibles?</span><span class="sxs-lookup"><span data-stu-id="6222e-920">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="6222e-921">Deje que el comprobador de accesibilidad le ayude sin estorbar.</span><span class="sxs-lookup"><span data-stu-id="6222e-921">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="6222e-922">Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.</span><span class="sxs-lookup"><span data-stu-id="6222e-922">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="6222e-923">**Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente?</span><span class="sxs-lookup"><span data-stu-id="6222e-923">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="6222e-924">Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.</span><span class="sxs-lookup"><span data-stu-id="6222e-924">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="6222e-925">**Vea cómo la hoja de cálculo cobra vida**: inserte gráficos 3D animados para ver corazones que laten, planetas en órbita y dinosaurios a toda velocidad por el libro.</span><span class="sxs-lookup"><span data-stu-id="6222e-925">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="6222e-926">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-926">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="6222e-p175">**Obtener más información sobre los datos:** el nuevo botón Ideas busca patrones en los datos y los usa para crear sugerencias inteligentes y personalizadas. [Más información](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="6222e-p175">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="6222e-929">**La colaboración es ahora más fácil**: las mejoras en la coautoría significan que al trabajar con el formato condicional, los estilos de celda y otros elementos, los cambios se combinan perfectamente con los de los colaboradores.</span><span class="sxs-lookup"><span data-stu-id="6222e-929">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="6222e-930">**Unir tablas en columnas similares:** obtener y transformar (Power Query) ahora ofrece una lógica de coincidencia de texto (también denominada coincidencia aproximada) al comparar columnas en la combinación de tablas.</span><span class="sxs-lookup"><span data-stu-id="6222e-930">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="6222e-931">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-931">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="6222e-932">**Programar rápidamente con mejoras de Power Query:** termine rápidamente el código con colores de sintaxis y la función de autocompletar.</span><span class="sxs-lookup"><span data-stu-id="6222e-932">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="6222e-933">Además, descubra fácilmente funciones, columnas y parámetros.</span><span class="sxs-lookup"><span data-stu-id="6222e-933">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="6222e-934">**Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea.</span><span class="sxs-lookup"><span data-stu-id="6222e-934">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="6222e-935">Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.</span><span class="sxs-lookup"><span data-stu-id="6222e-935">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="6222e-936">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-936">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="6222e-937">Outlook</span><span class="sxs-lookup"><span data-stu-id="6222e-937">Outlook</span></span>

- <span data-ttu-id="6222e-938">**Hemos actualizado la experiencia de usuario de Outlook para usted:** una experiencia simplificada, anteriormente disponible para su vista previa con Próximamente, diseñada para ayudarle a centrarse en lo más importante.</span><span class="sxs-lookup"><span data-stu-id="6222e-938">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="6222e-939">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-939">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="6222e-940">**Una cinta simplificada que además es personalizable:** disfrute de una sola fila simplificada con los botones más usados.</span><span class="sxs-lookup"><span data-stu-id="6222e-940">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="6222e-941">Cambie fácilmente entre la vista clásica y la simplificada, y ancle o desancle comandos.</span><span class="sxs-lookup"><span data-stu-id="6222e-941">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="6222e-942">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-942">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="6222e-943">**Seguir trabajando mientras mueve mensajes:** Outlook ahora mueve los mensajes en segundo plano, por lo que puede seguir trabajando mientras mueve una gran cantidad de mensajes entre carpetas.</span><span class="sxs-lookup"><span data-stu-id="6222e-943">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="6222e-944">**Creación en el tiempo entre las reuniones consecutivas:** asigne a los asistentes el tiempo para descansar o desplazarse entre las distintas ubicaciones al configurar reuniones para finalizar 5 a 10 minutos antes de forma predeterminada.</span><span class="sxs-lookup"><span data-stu-id="6222e-944">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="6222e-945">**Seleccione su acción favorita:** ¿no usa Etiquetar ni Eliminar?</span><span class="sxs-lookup"><span data-stu-id="6222e-945">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="6222e-946">¿Qué hay de Archivar o Marcar como leído?</span><span class="sxs-lookup"><span data-stu-id="6222e-946">How about Archive or Mark as Read?</span></span> <span data-ttu-id="6222e-947">Personalice el menú de acciones rápidas con los comandos que use más frecuentemente.</span><span class="sxs-lookup"><span data-stu-id="6222e-947">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="6222e-p182">**Verán los memes que comparta:** cuando un texto o imágenes estáticas no consigan comunicar lo que desea, use un GIF animado para aclararlo. [Más información](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="6222e-p182">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="6222e-950">**Una forma más rápida de agregar cuentas:** gracias a las mejoras de configuración de cuentas, es más fácil que nunca agregar cuentas de Outlook.com y Gmail que usen la autenticación en dos fases a Outlook.</span><span class="sxs-lookup"><span data-stu-id="6222e-950">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="6222e-951">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-951">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="6222e-952">**Despídase de límites de sincronización:** las mejoras de Outlook significan que se ha eliminado el límite de carpetas y sincronizar los buzones compartidos.</span><span class="sxs-lookup"><span data-stu-id="6222e-952">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="6222e-953">**Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea.</span><span class="sxs-lookup"><span data-stu-id="6222e-953">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="6222e-954">Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.</span><span class="sxs-lookup"><span data-stu-id="6222e-954">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="6222e-955">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-955">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="6222e-956">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6222e-956">PowerPoint</span></span>

- <span data-ttu-id="6222e-957">**Mejor transformación:** asigne un nombre a las formas para tener más control sobre cómo se transforman.</span><span class="sxs-lookup"><span data-stu-id="6222e-957">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="6222e-958">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-958">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="6222e-959">**Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente?</span><span class="sxs-lookup"><span data-stu-id="6222e-959">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="6222e-960">Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.</span><span class="sxs-lookup"><span data-stu-id="6222e-960">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="6222e-961">**Aumentar el alcance de su contenido:** ¿necesita que las presentaciones sean accesibles?</span><span class="sxs-lookup"><span data-stu-id="6222e-961">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="6222e-962">Deje que el comprobador de accesibilidad le ayude sin estorbar.</span><span class="sxs-lookup"><span data-stu-id="6222e-962">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="6222e-963">Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.</span><span class="sxs-lookup"><span data-stu-id="6222e-963">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="6222e-964">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="6222e-964">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="6222e-965">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="6222e-965">Switching between them has never been easier.</span></span> [<span data-ttu-id="6222e-966">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-966">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="6222e-967">**Los vídeos en línea tienen un nuevo hogar:** guarde un vídeo en Microsoft Stream para que puedan verlo todas las personas de su organización.</span><span class="sxs-lookup"><span data-stu-id="6222e-967">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="6222e-968">Inserte el vínculo del vídeo y disfrute de una presentación multimedia en una fracción del tamaño del archivo.</span><span class="sxs-lookup"><span data-stu-id="6222e-968">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="6222e-969">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-969">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="6222e-970">**Guardar los cambios a medida que los realiza:** cargue el archivo en OneDrive para asegurarse de que todas las actualizaciones se guardan automáticamente.</span><span class="sxs-lookup"><span data-stu-id="6222e-970">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="6222e-p190">**Pregunte a su público con un cuestionario o una encuesta:** coloque un cuestionario o una encuesta en una diapositiva. Office recopila y almacena las respuestas para usted. [Más información](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="6222e-p190">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="6222e-p191">**Nunca fue tan fácil insertar un vídeo en línea:** ¿quiere poner un vídeo de Vimeo o de YouTube en la diapositiva? Solo necesita el vínculo a la página del vídeo. [Más información](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="6222e-p191">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="6222e-977">**Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea.</span><span class="sxs-lookup"><span data-stu-id="6222e-977">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="6222e-978">Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.</span><span class="sxs-lookup"><span data-stu-id="6222e-978">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="6222e-979">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-979">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="6222e-980">Project</span><span class="sxs-lookup"><span data-stu-id="6222e-980">Project</span></span>

- <span data-ttu-id="6222e-981">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="6222e-981">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="6222e-982">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="6222e-982">Switching between them has never been easier.</span></span> [<span data-ttu-id="6222e-983">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-983">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="6222e-984">Visio</span><span class="sxs-lookup"><span data-stu-id="6222e-984">Visio</span></span>

- <span data-ttu-id="6222e-985">**Exportar diagramas de proceso a Word:** Agregue automáticamente contenido del diagrama, como formas y metadatos, a un documento de Word.</span><span class="sxs-lookup"><span data-stu-id="6222e-985">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="6222e-986">Después, personalice el documento para crear instrucciones de procesos y manuales de funcionamiento.</span><span class="sxs-lookup"><span data-stu-id="6222e-986">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="6222e-987">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-987">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="6222e-988">**Doble toma en diagramas de flujo de datos:** Los magníficos nuevos diseños para los diagramas de flujo del visualizador de datos son limpios, nítidos y fáciles de entender.</span><span class="sxs-lookup"><span data-stu-id="6222e-988">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="6222e-989">Haga clic en la pestaña Diseño para ver las opciones.</span><span class="sxs-lookup"><span data-stu-id="6222e-989">Click the Design tab for options.</span></span>

- <span data-ttu-id="6222e-990">**Galerías de símbolos integradas en Azure:** diseñe una aplicación de nube o planee una arquitectura con las múltiples galerías de símbolos de Azure.</span><span class="sxs-lookup"><span data-stu-id="6222e-990">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="6222e-991">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-991">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="6222e-p197">**Adiós a los vínculos rotos de Excel:** ¿no encuentra el libro de Excel vinculado a un diagrama de visualizador de datos? Solo tiene que vincularlo de nuevo y ¡listo! [Más información](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="6222e-p197">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="6222e-995">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="6222e-995">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="6222e-996">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="6222e-996">Switching between them has never been easier.</span></span> [<span data-ttu-id="6222e-997">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-997">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="6222e-998">**Exportar objetos visuales de Visio desde Power BI**: los objetos visuales de Visio para Power BI ahora se mostrarán correctamente al exportar informes de Power BI como archivos PDF, archivos de PowerPoint, etc.</span><span class="sxs-lookup"><span data-stu-id="6222e-998">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="6222e-999">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-999">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="6222e-1000">Word</span><span class="sxs-lookup"><span data-stu-id="6222e-1000">Word</span></span>

- <span data-ttu-id="6222e-1001">**El modo herramientas de aprendizaje tiene soporte adicional para más colores de página:** las herramientas de aprendizaje de Word son compatibles con más colores de tema de página, lo que permite cambiar el color de fondo de la página.</span><span class="sxs-lookup"><span data-stu-id="6222e-1001">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="6222e-1002">Muchas personas tienen dificultades para leer con un fondo totalmente blanco o negro, por lo que hemos ampliado la elección de colores en Word para PC y Mac.</span><span class="sxs-lookup"><span data-stu-id="6222e-1002">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="6222e-p201">**Edición natural con el Editor para entradas de lápiz:** con un solo trazo, divida o una palabras, agregue una nueva línea o inserte palabras con el lápiz. [Más información](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="6222e-p201">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="6222e-p202">**Su documento: de estático a mágico:** transforme el documento en una página web interactiva y fácil de compartir con un aspecto fantástico en cualquier dispositivo. [Más información](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="6222e-p202">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="6222e-1007">**Aumentar el alcance de su contenido:** ¿necesita hacer que sus documentos sean accesibles?</span><span class="sxs-lookup"><span data-stu-id="6222e-1007">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="6222e-1008">Deje que el comprobador de accesibilidad le ayude sin estorbar.</span><span class="sxs-lookup"><span data-stu-id="6222e-1008">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="6222e-1009">Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.</span><span class="sxs-lookup"><span data-stu-id="6222e-1009">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="6222e-1010">**Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente?</span><span class="sxs-lookup"><span data-stu-id="6222e-1010">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="6222e-1011">Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.</span><span class="sxs-lookup"><span data-stu-id="6222e-1011">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="6222e-1012">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="6222e-1012">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="6222e-1013">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="6222e-1013">Switching between them has never been easier.</span></span> [<span data-ttu-id="6222e-1014">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-1014">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="6222e-p206">**Mejorar la comprensión con el foco de línea:** desplácese por un documento línea por línea sin distracciones. Ajuste el foco para ver una, tres o cinco líneas a la vista. [Más información](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="6222e-p206">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="6222e-1018">**Guarde sus cambios a medida que se produzcan:** Suba su archivo a OneDrive para asegurarse de que todas sus actualizaciones se guarden automáticamente.</span><span class="sxs-lookup"><span data-stu-id="6222e-1018">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="6222e-1019">**Consiga su atención con\@menciones:** use @menciones en los comentarios para avisar a los compañeros de trabajo cuando necesite su participación.</span><span class="sxs-lookup"><span data-stu-id="6222e-1019">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="6222e-1020">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-1020">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="6222e-1021">**Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea.</span><span class="sxs-lookup"><span data-stu-id="6222e-1021">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="6222e-1022">Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.</span><span class="sxs-lookup"><span data-stu-id="6222e-1022">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="6222e-1023">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-1023">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="6222e-1024">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="6222e-1024">Office Suite</span></span>

- <span data-ttu-id="6222e-1025">**Encuentra ese archivo rápido:** ¿Busca un archivo en el que haya trabajado recientemente?</span><span class="sxs-lookup"><span data-stu-id="6222e-1025">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="6222e-1026">Sólo tiene que escribir en el cuadro de búsqueda de la pestaña Archivo > Abrir para encontrar el archivo que está buscando.</span><span class="sxs-lookup"><span data-stu-id="6222e-1026">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="6222e-1027">**Guardar los cambios a medida que los realiza:** cargue el archivo en OneDrive para asegurarse de que todas las actualizaciones se guardan automáticamente.</span><span class="sxs-lookup"><span data-stu-id="6222e-1027">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="6222e-1028">**Controles de privacidad:** nuevos controles para datos de diagnóstico y experiencias conectadas, actualizados y mejorados.</span><span class="sxs-lookup"><span data-stu-id="6222e-1028">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="6222e-1029">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-1029">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="6222e-1030">**Los iconos de Office tienen un nuevo aspecto:** los iconos de Office se han rediseñado para reflejar las sencillas, inteligentes y eficaces experiencias de Office.</span><span class="sxs-lookup"><span data-stu-id="6222e-1030">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="6222e-1031">**Instalación de Microsoft Teams:** Microsoft Teams se instala de forma predeterminada en las instalaciones existentes de Office 365 ProPlus.</span><span class="sxs-lookup"><span data-stu-id="6222e-1031">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="6222e-1032">Más información</span><span class="sxs-lookup"><span data-stu-id="6222e-1032">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6222e-1035">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-1035">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="6222e-1036">Access</span><span class="sxs-lookup"><span data-stu-id="6222e-1036">Access</span></span>

- <span data-ttu-id="6222e-1037">Esta actualización corrige un problema en el que la agregación como la suma puede truncar el resultado a un valor entero.</span><span class="sxs-lookup"><span data-stu-id="6222e-1037">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="6222e-1038">Esta actualización corrige un problema por el que una consulta de Unión que incluye referencias a tablas remotas (por ejemplo, tablas de SQL Server) puede hacer que Access se cierre y se reinicie.</span><span class="sxs-lookup"><span data-stu-id="6222e-1038">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="6222e-1039">Esta actualización corrige un problema en Microsoft Access que puede causar el error &quot;La consulta está dañada&quot; cuando se ejecuta una consulta de actualización o cuando se usa una instrucción UPDATE en SQL.</span><span class="sxs-lookup"><span data-stu-id="6222e-1039">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="6222e-1040">Excel</span><span class="sxs-lookup"><span data-stu-id="6222e-1040">Excel</span></span>

- <span data-ttu-id="6222e-1041">La información clave en holandés para el título del documento ha sido cambiada a Alt-G.</span><span class="sxs-lookup"><span data-stu-id="6222e-1041">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="6222e-1042">Se ha corregido un problema en Excel en el que las macros asignadas a formas o controles de formularios podían mostrar un mensaje de error incorrecto o funcionar en intervalos de destino incorrectos.</span><span class="sxs-lookup"><span data-stu-id="6222e-1042">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="6222e-1043">Se resolvió un problema con buscar y reemplazar ese cambio donde el foco estaba en el diálogo después de encontrar el primer elemento.</span><span class="sxs-lookup"><span data-stu-id="6222e-1043">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="6222e-1044">Esto corrige un problema por el cual al cambiar la forma en que se ordena y actualiza una tabla dinámica mientras se está en una sesión de co autoría con otros usuarios se podía provocar un bloqueo.</span><span class="sxs-lookup"><span data-stu-id="6222e-1044">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="6222e-1045">Arreglamos un problema cuando el filtro de una tabla dinámica OLAP se estableció en un valor que se había eliminado del cubo.</span><span class="sxs-lookup"><span data-stu-id="6222e-1045">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="6222e-1046">Se han corregido los colores que se usan en las vistas previas al insertar gráficos con plantillas de gráficos.</span><span class="sxs-lookup"><span data-stu-id="6222e-1046">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="6222e-1047">Se ha corregido un problema que podía impedir que los gráficos de líneas de dispersión se representaran correctamente al cambiar la colección de series.</span><span class="sxs-lookup"><span data-stu-id="6222e-1047">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="6222e-1048">Se resolvió un problema que causó que los gráficos de cascada y embudo se desincronizara con las tablas cuando se insertaban o eliminaban celdas.</span><span class="sxs-lookup"><span data-stu-id="6222e-1048">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="6222e-1049">Se ha corregido un problema de conflicto de fusión en Excel que hacía que los usuarios tuvieran que volver a abrir el libro de trabajo para elegir los cambios.</span><span class="sxs-lookup"><span data-stu-id="6222e-1049">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="6222e-1050">Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.</span><span class="sxs-lookup"><span data-stu-id="6222e-1050">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="6222e-1051">Se resolvió un problema que causaba un error de tiempo de ejecución de la macro que activaba las ventanas minimizadas.</span><span class="sxs-lookup"><span data-stu-id="6222e-1051">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="6222e-1052">Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.</span><span class="sxs-lookup"><span data-stu-id="6222e-1052">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="6222e-1053">Se resolvió un problema que causaba que las operaciones de cortar y pegar junto a una mesa fallaran cuando se co autoría con otros.</span><span class="sxs-lookup"><span data-stu-id="6222e-1053">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="6222e-1054">Se resolvió un problema que causaba interrupciones de co autoría cuando se cambiaban las propiedades personalizadas con macros en ejecución.</span><span class="sxs-lookup"><span data-stu-id="6222e-1054">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="6222e-1055">Hubo un problema en el que no se podían seleccionar elementos del cuadro combinado de un formulario de WPF (Windows Presentation Foundation) que fue abierto por un complemento.</span><span class="sxs-lookup"><span data-stu-id="6222e-1055">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="6222e-1056">Se ha resuelto un problema que puede haber causado un bloqueo al buscar archivos recientes cuando no hay ningún libro de trabajo abierto.</span><span class="sxs-lookup"><span data-stu-id="6222e-1056">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="6222e-1057">Problema de rendimiento con las Funciones Asincrónicas Definidas por el Usuario que hacía que se ejecutaran sincrónicamente.</span><span class="sxs-lookup"><span data-stu-id="6222e-1057">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="6222e-1058">Mejoras significativas en el rendimiento de la eliminación de columnas con celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="6222e-1058">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="6222e-1059">Se resolvió un problema en el que la selección de una celda después del desplazamiento podía dar lugar a que se seleccionara la celda incorrecta.</span><span class="sxs-lookup"><span data-stu-id="6222e-1059">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="6222e-1060">Se ha resuelto un problema en el que la función de búsqueda puede devolver un error.</span><span class="sxs-lookup"><span data-stu-id="6222e-1060">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="6222e-1061">Se ha resuelto un problema por el que los libros de trabajo creados en versiones anteriores de Office podían hacer que Excel se colgara al abrirlos en las versiones actuales de Office.</span><span class="sxs-lookup"><span data-stu-id="6222e-1061">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="6222e-1062">Problema de rendimiento bajo al hacer clic en el botón Color de fuente cuando un archivo tiene un formato condicional extenso.</span><span class="sxs-lookup"><span data-stu-id="6222e-1062">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="6222e-1063">Se ha corregido un problema por el que el área de impresión en la vista previa de impresión no era correcta.</span><span class="sxs-lookup"><span data-stu-id="6222e-1063">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="6222e-1064">Excel puede tener problemas al editar un archivo protegido desde una red compartida no confiable.</span><span class="sxs-lookup"><span data-stu-id="6222e-1064">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="6222e-1065">Hemos mejorado significativamente el rendimiento del filtrado por color.</span><span class="sxs-lookup"><span data-stu-id="6222e-1065">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="6222e-1066">Se resolvió un problema que impedía que los hipervínculos se pegaran en algunas hojas protegidas.</span><span class="sxs-lookup"><span data-stu-id="6222e-1066">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="6222e-1067">Se habilitó más de 16 complementos para que se muestren al navegar en el administrador de complementos.</span><span class="sxs-lookup"><span data-stu-id="6222e-1067">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="6222e-1068">Este cambio evita un problema con ciertos controladores de gráficos Intel aprovechando la renderización de software.</span><span class="sxs-lookup"><span data-stu-id="6222e-1068">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="6222e-1069">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="6222e-1069">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="6222e-1070">Esta actualización corrige un error por el cual los documentos de Office pueden fallar al subirlos a OneDrive para la Empresa con el mensaje "Error al cargar".</span><span class="sxs-lookup"><span data-stu-id="6222e-1070">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="6222e-1071">Corregir problema en la característica Ideas de Excel, error al cargar el complemento haciendo clic en el botón Ideas en el cliente Win32.</span><span class="sxs-lookup"><span data-stu-id="6222e-1071">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="6222e-1072">Outlook</span><span class="sxs-lookup"><span data-stu-id="6222e-1072">Outlook</span></span>

- <span data-ttu-id="6222e-1073">Los vínculos de cid:image de los mensajes de Outlook ahora se pueden romper correctamente cuando se solicite.</span><span class="sxs-lookup"><span data-stu-id="6222e-1073">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="6222e-1074">Se ha corregido un problema que causaba que los usuarios que actualizaban su buzón de la autenticación básica a la moderna, terminaban con una cuenta incorrecta asociada a su perfil de Outlook.</span><span class="sxs-lookup"><span data-stu-id="6222e-1074">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="6222e-1075">Corregido un problema que hizo que los complementos web accedieran a los mensajes de Digital Rights Managed cuando no deberían hacerlo.</span><span class="sxs-lookup"><span data-stu-id="6222e-1075">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="6222e-1076">Corregido un problema que causó que las URLS de enlace simple no se mostraran en algunos enlaces seguros.</span><span class="sxs-lookup"><span data-stu-id="6222e-1076">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="6222e-1077">Esto actualiza la lógica de bloqueo de adjuntos en Outlook para bloquear también los adjuntos de Python.</span><span class="sxs-lookup"><span data-stu-id="6222e-1077">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="6222e-1078">Corregido un problema que hacía que un subconjunto de usuarios POP3 viera todos sus correos electrónicos formateados en texto plano, independientemente de la configuración.</span><span class="sxs-lookup"><span data-stu-id="6222e-1078">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="6222e-1079">Esta corrección restaurará la vista de los mensajes con formato HTML.</span><span class="sxs-lookup"><span data-stu-id="6222e-1079">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="6222e-1080">Corregido un problema que hacía que los usuarios experimentaran un error de permiso al copiar elementos de su calendario principal a un calendario de grupo.</span><span class="sxs-lookup"><span data-stu-id="6222e-1080">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="6222e-1081">Corregido un problema que hacía que los usuarios no pudieran acceder a las sugerencias de ubicación a través de un lector de pantalla.</span><span class="sxs-lookup"><span data-stu-id="6222e-1081">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="6222e-1082">Corregido un problema que hacía que los usuarios vieran un retraso notable al interactuar con sus carpetas de buzón de correo a través de métodos abreviados de teclado.</span><span class="sxs-lookup"><span data-stu-id="6222e-1082">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="6222e-1083">Corregido un problema que causaba una fuga de memoria en sesiones de Outlook muy largas.</span><span class="sxs-lookup"><span data-stu-id="6222e-1083">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="6222e-1084">Corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al abrir el cuadro de diálogo Reglas.</span><span class="sxs-lookup"><span data-stu-id="6222e-1084">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="6222e-1085">Corregido un problema que haría que los usuarios experimentaran un bloqueo en Outlook al interactuar con ciertos vínculos seguros.</span><span class="sxs-lookup"><span data-stu-id="6222e-1085">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="6222e-1086">Corregido un problema que causó ambigüedad a los gerentes en cuanto a si un delegado ya había respondido o no a una determinada solicitud de reunión.</span><span class="sxs-lookup"><span data-stu-id="6222e-1086">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="6222e-1087">Corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.</span><span class="sxs-lookup"><span data-stu-id="6222e-1087">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="6222e-1088">Se ha solucionado un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "ok" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="6222e-1088">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="6222e-1089">Este cambio permite a los administradores habilitar una política para preferir el correo electrónico de la cuenta proporcionada en los avisos de autorización de AutoDiscover sobre el UPN.</span><span class="sxs-lookup"><span data-stu-id="6222e-1089">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="6222e-1090">De forma predeterminada, detección automática prefiere el UPN de la cuenta, cuando está disponible.</span><span class="sxs-lookup"><span data-stu-id="6222e-1090">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="6222e-1091">Se ha corregido un problema que provocaba que los usuarios vieran un error en la búsqueda con grupos modernos.</span><span class="sxs-lookup"><span data-stu-id="6222e-1091">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="6222e-1092">Solucionó un problema que causaba que los usuarios de Outlook se quedaran atascados en el estado "Necesita contraseña" en ciertos escenarios.</span><span class="sxs-lookup"><span data-stu-id="6222e-1092">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="6222e-1093">Se abordó un problema que hizo que los usuarios vieran sugerencias de salas para reuniones que se produjeron fuera de las horas de disponibilidad de dichas salas.</span><span class="sxs-lookup"><span data-stu-id="6222e-1093">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="6222e-1094">Corregido un problema que hizo que los usuarios encontraran errores de "algoritmo de cifrado no admitido" al enviar un correo electrónico cifrado.</span><span class="sxs-lookup"><span data-stu-id="6222e-1094">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="6222e-1095">Corregido un problema para los usuarios que no hablan inglés, en el que la línea de asunto de un correo electrónico era increíblemente pequeña.</span><span class="sxs-lookup"><span data-stu-id="6222e-1095">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="6222e-1096">Corregido un problema que hacía que algunos usuarios vieran duplicadas las carpetas especiales creadas al añadir una cuenta de Exchange secundaria.</span><span class="sxs-lookup"><span data-stu-id="6222e-1096">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="6222e-1097">Corregido un problema que hacía que los usuarios experimentaran un bloqueo al intentar crear una regla a partir de un mensaje de "Conversación perdida".</span><span class="sxs-lookup"><span data-stu-id="6222e-1097">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="6222e-1098">Corregido un problema con la selección del algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="6222e-1098">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="6222e-1099">Corregido un problema que hacía que no se mostraran las sugerencias de política cuando se utilizaba un remitente alternativo.</span><span class="sxs-lookup"><span data-stu-id="6222e-1099">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="6222e-1100">Corregido un problema que hacía que los usuarios observaran una fuga de memoria en el proceso de Outlook.</span><span class="sxs-lookup"><span data-stu-id="6222e-1100">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="6222e-1101">Corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.</span><span class="sxs-lookup"><span data-stu-id="6222e-1101">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="6222e-1102">Corregido un problema que causaba que la búsqueda de la carpeta actual fallara de forma intermitente.</span><span class="sxs-lookup"><span data-stu-id="6222e-1102">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="6222e-1103">Corregido un problema que hizo que algunos usuarios encontraran errores de autenticación al intentar recuperar su configuración de nube para Outlook.</span><span class="sxs-lookup"><span data-stu-id="6222e-1103">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="6222e-1104">Corregido un problema que causó un bloqueo en la experiencia de los comentarios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="6222e-1104">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="6222e-1105">Corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.</span><span class="sxs-lookup"><span data-stu-id="6222e-1105">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="6222e-1106">Corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.</span><span class="sxs-lookup"><span data-stu-id="6222e-1106">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6222e-1107">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6222e-1107">PowerPoint</span></span>

- <span data-ttu-id="6222e-1108">Se ha corregido un problema por el que algunos complementos producían errores inesperados alrededor de las formas en gráficos.</span><span class="sxs-lookup"><span data-stu-id="6222e-1108">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="6222e-1109">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="6222e-1109">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="6222e-1110">Este cambio restaura el nombre accesible de los controles de vídeo de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6222e-1110">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="6222e-1111">Hemos corregido un problema que podría impedir que se inicien algunas animaciones.</span><span class="sxs-lookup"><span data-stu-id="6222e-1111">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="6222e-1112">Hemos corregido un problema en el que al copiar una diapositiva de una presentación a otra, se pueden crear patrones duplicados.</span><span class="sxs-lookup"><span data-stu-id="6222e-1112">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="6222e-1113">Los archivos con nuevos comentarios modernos mostrarán una advertencia amarilla si se abren en una versión no soportada</span><span class="sxs-lookup"><span data-stu-id="6222e-1113">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="6222e-1114">Fiabilidad fija: corregido un problema por el que el complemento de terceros podía bloquearse en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6222e-1114">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="6222e-1115">Corregido un problema por el que los caracteres katakana de medio ancho no giraban correctamente cuando estaban en cuadros de texto verticales en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6222e-1115">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="6222e-1116">Project</span><span class="sxs-lookup"><span data-stu-id="6222e-1116">Project</span></span>

- <span data-ttu-id="6222e-1117">Se ha corregido un problema para permitir que los usuarios en Windows 7 puedan abrir proyectos desde Project Web App y sitios de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="6222e-1117">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="6222e-1118">Se identificó un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de sólo lectura.</span><span class="sxs-lookup"><span data-stu-id="6222e-1118">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="6222e-1119">El comando Level All no resuelve adecuadamente una sobreasignación de recursos.</span><span class="sxs-lookup"><span data-stu-id="6222e-1119">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="6222e-1120">Si tiene una tarea sin nada de trabajo, es posible que la tarea no se pueda marcar como completada y siempre se mostrará en el 99 %.</span><span class="sxs-lookup"><span data-stu-id="6222e-1120">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="6222e-1121">Visio</span><span class="sxs-lookup"><span data-stu-id="6222e-1121">Visio</span></span>

- <span data-ttu-id="6222e-1122">La exportación como SVG de Visio estaba fallando por una variedad de formas.</span><span class="sxs-lookup"><span data-stu-id="6222e-1122">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="6222e-1123">Word</span><span class="sxs-lookup"><span data-stu-id="6222e-1123">Word</span></span>

- <span data-ttu-id="6222e-1124">Este cambio conducirá a mejoras de rendimiento en la apertura de documentos utilizando Word.</span><span class="sxs-lookup"><span data-stu-id="6222e-1124">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="6222e-1125">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="6222e-1125">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="6222e-1126">Hemos corregido un problema que podría haber causado problemas de escala al imprimir en impresoras Deskjet.</span><span class="sxs-lookup"><span data-stu-id="6222e-1126">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="6222e-1127">Hemos corregido un problema en los cambios de pista que a veces van en un bucle infinito.</span><span class="sxs-lookup"><span data-stu-id="6222e-1127">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="6222e-1128">Corregidos varios problemas que hacían que la aplicación se colgara al apagarse.</span><span class="sxs-lookup"><span data-stu-id="6222e-1128">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="6222e-1129">También se corrigieron ciertos fallos relacionados con los complementos.</span><span class="sxs-lookup"><span data-stu-id="6222e-1129">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6222e-1130">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="6222e-1130">Office Suite</span></span>

- <span data-ttu-id="6222e-1131">Corregido el problema de la identificación incorrecta del nombre de la nueva era "Reiwa" en hiragana y kanji como una expresión mal escrita o poco gramatical.</span><span class="sxs-lookup"><span data-stu-id="6222e-1131">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="6222e-1132">Corregido un problema que hacía que los usuarios recibieran el mensaje "Lo sentimos, algo nos impide compartir esto" al intentar compartir archivos almacenados en SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="6222e-1132">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="6222e-1133">Se ha solucionado un problema que podía causar la pérdida de datos en sesiones que implicaban tanto la co autoría como la edición fuera de línea en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6222e-1133">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="6222e-1134">Esta es una solución para un fallo que los usuarios podrían sufrir al abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="6222e-1134">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="6222e-1135">Evita que los usuarios de PowerPoint se encuentren con un error cuando intentan hacer una presentación en línea.</span><span class="sxs-lookup"><span data-stu-id="6222e-1135">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="6222e-1136">En algunos casos, un archivo de sharepoint respaldado por un motor de sincronización podría mostrar "Guardado" pero no haber guardado realmente ningún cambio, lo que provocaría la pérdida de datos.</span><span class="sxs-lookup"><span data-stu-id="6222e-1136">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="6222e-1137">Se resolvió un problema que impedía a los usuarios guardar documentos de Word, Excel y PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6222e-1137">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="6222e-1138">Este problema afecta a los usuarios que crean un nuevo archivo y muestra la opción "Guardar como diálogo" después de hacer clic en el icono Guardar o presionar Ctrl + S.</span><span class="sxs-lookup"><span data-stu-id="6222e-1138">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="6222e-1139">Se ha corregido un problema de perf en Win7 en el que la galería de formas de inserción de la cinta en todas las aplicaciones tardaba aproximadamente 4 segundos en aparecer.</span><span class="sxs-lookup"><span data-stu-id="6222e-1139">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="6222e-1140">Corregido un error por el que la información de accesibilidad no se mostraba en la losa del lugar de información de los bastidores.</span><span class="sxs-lookup"><span data-stu-id="6222e-1140">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="6222e-1141">Mejora de la fiabilidad del proceso de actualización de Office en lo que respecta a la integridad del registro.</span><span class="sxs-lookup"><span data-stu-id="6222e-1141">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="6222e-1142">Se ha corregido un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.</span><span class="sxs-lookup"><span data-stu-id="6222e-1142">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="6222e-1143">Se ha solucionado un problema por el que los mensajes de actualización de Office aparecían en un idioma diferente al esperado.</span><span class="sxs-lookup"><span data-stu-id="6222e-1143">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="6222e-1144">En el futuro, los mensajes de actualización de Office coincidirán correctamente con el idioma de visualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="6222e-1144">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="6222e-1145">Corregido un problema en el que una actualización no se aplicaría en ciertos casos en los que el usuario no es un administrador y la cuenta del sistema no tenía conectividad de red.</span><span class="sxs-lookup"><span data-stu-id="6222e-1145">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="6222e-1146">En determinadas circunstancias, los accesos directos de Office pueden desaparecer tras una actualización.</span><span class="sxs-lookup"><span data-stu-id="6222e-1146">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="6222e-1147">Esta actualización mejora la fiabilidad en la publicación de los accesos directos de Office.</span><span class="sxs-lookup"><span data-stu-id="6222e-1147">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="6222e-1148">Se ha corregido un problema por el que las actualizaciones se bloqueaban inesperadamente en las redes de medición.</span><span class="sxs-lookup"><span data-stu-id="6222e-1148">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="6222e-1149">Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.</span><span class="sxs-lookup"><span data-stu-id="6222e-1149">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="6222e-1150">Mejora de la confiabilidad al descargar las actualizaciones de Office al reanudar las descargas que pueden haberse interrumpido anteriormente.</span><span class="sxs-lookup"><span data-stu-id="6222e-1150">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="6222e-1151">Corregidos los problemas relacionados con la propiedad Textbox/Shape Autofit en los plug-ins de terceros.</span><span class="sxs-lookup"><span data-stu-id="6222e-1151">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="6222e-1152">Hemos corregido un problema en el que las vistas de árboles grandes podían resultar en un choque.</span><span class="sxs-lookup"><span data-stu-id="6222e-1152">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="6222e-1153">Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="6222e-1153">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-january-14"></a><span data-ttu-id="6222e-1155">Versión 1902: 14 de enero</span><span class="sxs-lookup"><span data-stu-id="6222e-1155">Version 1902: January 14</span></span>
<span data-ttu-id="6222e-1156">*VVersión 1902 (compilación 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="6222e-1156">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="6222e-1157">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-1157">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="6222e-1159">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="6222e-1159">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6222e-1160">Excel</span><span class="sxs-lookup"><span data-stu-id="6222e-1160">Excel</span></span>

- <span data-ttu-id="6222e-1161">Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.</span><span class="sxs-lookup"><span data-stu-id="6222e-1161">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="6222e-1162">Outlook</span><span class="sxs-lookup"><span data-stu-id="6222e-1162">Outlook</span></span>

- <span data-ttu-id="6222e-1163">Corregido un problema que causó que los usuarios se encontraran con errores de "el algoritmo de cifrado no es compatible" al enviar un correo electrónico cifrado.</span><span class="sxs-lookup"><span data-stu-id="6222e-1163">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6222e-1164">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6222e-1164">PowerPoint</span></span>

- <span data-ttu-id="6222e-1165">Los archivos con nuevos comentarios modernos mostrarán una advertencia amarilla si se abren en una versión no soportada.</span><span class="sxs-lookup"><span data-stu-id="6222e-1165">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="6222e-1166">Word</span><span class="sxs-lookup"><span data-stu-id="6222e-1166">Word</span></span>

- <span data-ttu-id="6222e-1167">Este cambio conducirá a mejoras de rendimiento en la apertura de documentos utilizando Word.</span><span class="sxs-lookup"><span data-stu-id="6222e-1167">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (NO ELIMINAR LOS DETALLES DEL CONTENIDO FINAL)

## <a name="version-1808-january-14"></a><span data-ttu-id="6222e-1169">Versión 1808: 14 de enero</span><span class="sxs-lookup"><span data-stu-id="6222e-1169">Version 1808: January 14</span></span>
<span data-ttu-id="6222e-1170">*Versión 1808 (compilación 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="6222e-1170">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="6222e-1171">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="6222e-1171">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

> [!NOTE]
> <span data-ttu-id="6222e-1173">Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="6222e-1173">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (NO MODIFICAR EL INICIO DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
[//]: # (| Win32 | DC | Producción | | 16.0.12527.21416 | versión-2002-diciembre-08 |)
[//]: # (| Win32 | DC | Producción | | 16.0.12527.21330 | versión-2002-noviembre-10 |)
[//]: # (| Win32 | CC | Producción | | 16.0.12527.20880 | versión-2002-julio-14 |)
[//]: # (|Win32|DC|Producción| |16.0.12527.21104|versión-2002-08-agosto|)
[//]: # (|Win32|DC|Producción| |16.0.12527.20988|versión-2002-11-agosto|)
[//]: # (| Win32 | CC | Producción | | 16.0.12527.20880 | versión-2002-julio-14 |)
[//]: # (NO MODIFICAR EL FIN DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
