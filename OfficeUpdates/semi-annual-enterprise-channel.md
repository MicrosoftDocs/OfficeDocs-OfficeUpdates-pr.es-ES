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
ms.openlocfilehash: c719a54075f57b031cf99ef7459fe38c0cab63dc
ms.sourcegitcommit: 8e74984d0c36475374c34e76ed29c5d1ad81d971
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 11/10/2020
ms.locfileid: "48990079"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-releases-in-2020"></a><span data-ttu-id="faf5c-103">Notas de la versión para las versiones de canal empresarial semestral en 2020</span><span class="sxs-lookup"><span data-stu-id="faf5c-103">Release notes for Semi-Annual Enterprise Channel releases in 2020</span></span>

<span data-ttu-id="faf5c-104">Estas notas de la versión proporcionan información sobre las nuevas características y las actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones de canal empresarial semestral en 2020 para las Aplicaciones de Microsoft 365 para empresas, las Aplicaciones de Microsoft 365 para negocios y las versiones de suscripción de las aplicaciones de escritorio de Project y Visio.</span><span class="sxs-lookup"><span data-stu-id="faf5c-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="faf5c-p101">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="faf5c-p101">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="faf5c-107">OneNote 2016 ahora se incluirá de forma predeterminada cuando un usuario en el canal empresarial semestral descargue e instale las Aplicaciones de Microsoft 365 en Windows 10 desde el Portal de Office.</span><span class="sxs-lookup"><span data-stu-id="faf5c-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2002-november-10"></a><span data-ttu-id="faf5c-109">Versión 2002: 10 de noviembre</span><span class="sxs-lookup"><span data-stu-id="faf5c-109">Version 2002: November 10</span></span>
<span data-ttu-id="faf5c-110">*Versión 2002 (compilación 12527.21330)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-110">*Version 2002 (Build 12527.21330)*</span></span>

<span data-ttu-id="faf5c-111">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-113">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-113">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="faf5c-114">Excel</span><span class="sxs-lookup"><span data-stu-id="faf5c-114">Excel</span></span>

- <span data-ttu-id="faf5c-115">Se ha corregido un problema que aparecía cuando se configuraba el idioma de Office en español. Este problema provocaba que las listas de validación de datos pudieran no mostrar todos los elementos de la lista.</span><span class="sxs-lookup"><span data-stu-id="faf5c-115">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="faf5c-116">Se ha corregido un problema que podía producir un bloqueo al actualizar las tablas dinámicas de OLAP.</span><span class="sxs-lookup"><span data-stu-id="faf5c-116">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="faf5c-117">Se ha corregido un problema por el que algunas funciones podían tener un resultado incorrecto después de cargar un libro.</span><span class="sxs-lookup"><span data-stu-id="faf5c-117">Fixed a bug where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="faf5c-118">Se ha corregido un problema relacionado con las referencias de complemento de XLAM y los rangos con nombre que cerraba la aplicación de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="faf5c-118">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="faf5c-119">Se ha corregido un problema que producía que la ejecución de la macro de filtro avanzada mostrara errores incorrectamente.</span><span class="sxs-lookup"><span data-stu-id="faf5c-119">Fixed an issue where running the advanced filter macro would incorrectly report errors.</span></span>


### <a name="outlook"></a><span data-ttu-id="faf5c-120">Outlook</span><span class="sxs-lookup"><span data-stu-id="faf5c-120">Outlook</span></span>

- <span data-ttu-id="faf5c-121">Se ha corregido un problema por el que se deshabilitaban de forma inesperada complementos internos cuando se deshabilitaban las experiencias conectadas opcionales.</span><span class="sxs-lookup"><span data-stu-id="faf5c-121">We fixed an issue that caused internal add-ins to be unexpectedly disabled when optional connected experiences were disabled.</span></span>


- <span data-ttu-id="faf5c-122">Se ha corregido un problema que impedía a los usuarios enviar como (o en nombre de) una lista de distribución oculta para la lista global de direcciones.</span><span class="sxs-lookup"><span data-stu-id="faf5c-122">We fixed an issue that caused users to be unable to send as or on behalf of a Distribution List that was hidden from the Global Address List.</span></span>



[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-1908-november-10"></a><span data-ttu-id="faf5c-124">Versión 1908: 10 de noviembre</span><span class="sxs-lookup"><span data-stu-id="faf5c-124">Version 1908: November 10</span></span>
<span data-ttu-id="faf5c-125">*Versión 1908 (compilación 11929.20974)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-125">*Version 1908 (Build 11929.20974)*</span></span>

<span data-ttu-id="faf5c-126">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-126">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-october-13"></a><span data-ttu-id="faf5c-127">Versión 2002: 13 de octubre</span><span class="sxs-lookup"><span data-stu-id="faf5c-127">Version 2002: October 13</span></span>
<span data-ttu-id="faf5c-128">*Versión 2002 (compilación 12527.21236)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-128">*Version 2002 (Build 12527.21236)*</span></span>

<span data-ttu-id="faf5c-129">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-129">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-131">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-131">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="faf5c-132">Acceso</span><span class="sxs-lookup"><span data-stu-id="faf5c-132">Access</span></span>

- <span data-ttu-id="faf5c-133">Ya no debería recibir un error "La consulta es demasiado compleja" o de recurso del sistema excedido en su versión de 64 bits de Access, siempre y cuando cumpla con las directrices y requisitos de la base de datos de Access.</span><span class="sxs-lookup"><span data-stu-id="faf5c-133">You should no longer receive a "Query is too complex" or a system resource exceeded error on your 64-bit version of Access, as long as you are meeting Access database guidelines and requirements.</span></span>


- <span data-ttu-id="faf5c-134">Una vez que decida usar nuestra característica de filtro después de nuestro diseñador de consultas, la base de datos ya no debería bloquearse.</span><span class="sxs-lookup"><span data-stu-id="faf5c-134">Once you decide to use our filter feature after our query designer, your database should no longer crash.</span></span> <span data-ttu-id="faf5c-135">Compruebe lo que corresponda.</span><span class="sxs-lookup"><span data-stu-id="faf5c-135">Please check accordingly.</span></span>


### <a name="excel"></a><span data-ttu-id="faf5c-136">Excel</span><span class="sxs-lookup"><span data-stu-id="faf5c-136">Excel</span></span>

- <span data-ttu-id="faf5c-137">Se corrigió un problema por el cual los usuarios no podían modificar un filtro de tabla dinámica porque estaba configurado en un valor que ya no estaba presente en una base de datos de Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="faf5c-137">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="faf5c-138">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="faf5c-138">PowerPoint</span></span>

- <span data-ttu-id="faf5c-139">Las nuevas presentaciones creadas a partir de una plantilla podían heredar una configuración que impedía una buena experiencia de coautoría.</span><span class="sxs-lookup"><span data-stu-id="faf5c-139">New presentations created from a template could inherit a setting that prevented  a good co-authoring experience.</span></span> <span data-ttu-id="faf5c-140">Esta corrección garantiza que la configuración se haya borrado en este caso.</span><span class="sxs-lookup"><span data-stu-id="faf5c-140">This fix ensures that the setting is cleared in this case.</span></span>


### <a name="word"></a><span data-ttu-id="faf5c-141">Word</span><span class="sxs-lookup"><span data-stu-id="faf5c-141">Word</span></span>

- <span data-ttu-id="faf5c-142">Se ha corregido un problema por el que al abrir documentos con saltos de página y columnas, el usuario podía encontrar un mensaje de error, "Ha excedido el número máximo de páginas admitidas por Microsoft Word, o el documento puede estar dañado"</span><span class="sxs-lookup"><span data-stu-id="faf5c-142">We fixed an issue which when opening documents with page breaks and columns, user might encountered an error message, " You have exceeded the maximum number of pages allowed by Microsoft Word supported, or the document may be damaged"</span></span>


### <a name="office-suite"></a><span data-ttu-id="faf5c-143">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="faf5c-143">Office Suite</span></span>

- <span data-ttu-id="faf5c-144">Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan toners</span><span class="sxs-lookup"><span data-stu-id="faf5c-144">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="faf5c-145">Cambiar mensaje para mostrar "tóner/Ink Low" & "no tóner/tinta".</span><span class="sxs-lookup"><span data-stu-id="faf5c-145">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO FINAL)

## <a name="version-1908-october-13"></a><span data-ttu-id="faf5c-147">Versión 1908: 13 de octubre</span><span class="sxs-lookup"><span data-stu-id="faf5c-147">Version 1908: October 13</span></span>
<span data-ttu-id="faf5c-148">*Versión 1908 (compilación 11929.20966)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-148">*Version 1908 (Build 11929.20966)*</span></span>

<span data-ttu-id="faf5c-149">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-149">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-151">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-151">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="faf5c-152">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="faf5c-152">Office Suite</span></span>

- <span data-ttu-id="faf5c-153">Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan toners</span><span class="sxs-lookup"><span data-stu-id="faf5c-153">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="faf5c-154">Cambiar mensaje para mostrar "tóner/Ink Low" & "no tóner/tinta".</span><span class="sxs-lookup"><span data-stu-id="faf5c-154">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO FINAL)

## <a name="version-2002-september-08"></a><span data-ttu-id="faf5c-156">Versión 2002: 08 de septiembre</span><span class="sxs-lookup"><span data-stu-id="faf5c-156">Version 2002: September 08</span></span>
<span data-ttu-id="faf5c-157">*Versión 2002 (Compilación 12527.21104)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-157">*Version 2002 (Build 12527.21104)*</span></span>

<span data-ttu-id="faf5c-158">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-158">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-160">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-160">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="faf5c-161">Excel</span><span class="sxs-lookup"><span data-stu-id="faf5c-161">Excel</span></span>

- <span data-ttu-id="faf5c-162">Esto soluciona un problema en el que las conexiones creadas por el proveedor de datos SQL en versiones anteriores de Office establecerían las propiedades de la tabla interna de manera diferente a Office 365.</span><span class="sxs-lookup"><span data-stu-id="faf5c-162">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="faf5c-163">Esto provocó que el menú desplegable Vista previa de tabla / Editor de consultas se deshabilitara para los archivos con conexiones creadas en versiones anteriores de Office cuando se abrieron con Office 365.</span><span class="sxs-lookup"><span data-stu-id="faf5c-163">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>


- <span data-ttu-id="faf5c-164">Se corrigió un problema por el cual las entradas manuscritas podrían hacer que Excel dejara de responder.</span><span class="sxs-lookup"><span data-stu-id="faf5c-164">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="faf5c-165">Outlook</span><span class="sxs-lookup"><span data-stu-id="faf5c-165">Outlook</span></span>

- <span data-ttu-id="faf5c-166">Corrige un problema que evitaba que los usuarios se conectaran a las carpetas públicas luego de agregar un buzón compartido.</span><span class="sxs-lookup"><span data-stu-id="faf5c-166">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


### <a name="office-suite"></a><span data-ttu-id="faf5c-167">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="faf5c-167">Office Suite</span></span>

- <span data-ttu-id="faf5c-168">Este cambio resuelve un problema con el cuadro de diálogo de Comprimir imagen, que no retiene determinadas configuraciones de usuario.</span><span class="sxs-lookup"><span data-stu-id="faf5c-168">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-september-08"></a><span data-ttu-id="faf5c-170">Versión 1908: 08 de septiembre</span><span class="sxs-lookup"><span data-stu-id="faf5c-170">Version 1908: September 08</span></span>
<span data-ttu-id="faf5c-171">*Versión 1908 (compilación 11929.20946)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-171">*Version 1908 (Build 11929.20946)*</span></span>

<span data-ttu-id="faf5c-172">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-172">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-august-11"></a><span data-ttu-id="faf5c-173">Versión 2002: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="faf5c-173">Version 2002: August 11</span></span>
<span data-ttu-id="faf5c-174">*Versión 2002 (compilación 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-174">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="faf5c-175">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-175">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-177">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-177">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="faf5c-178">Excel</span><span class="sxs-lookup"><span data-stu-id="faf5c-178">Excel</span></span>

- <span data-ttu-id="faf5c-179">Se corrigió un problema por el que no se podía cambiar a la edición de archivos que se han abierto como "recomendado solo lectura".</span><span class="sxs-lookup"><span data-stu-id="faf5c-179">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="faf5c-180">OneNote</span><span class="sxs-lookup"><span data-stu-id="faf5c-180">OneNote</span></span>

- <span data-ttu-id="faf5c-181">Se quitaron las llamadas de identidad redundantes para reducir el uso de recursos</span><span class="sxs-lookup"><span data-stu-id="faf5c-181">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="faf5c-182">Se mejoró la detección del estado de la coautoría para reducir el uso de recursos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-182">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="faf5c-183">Se mejoró la función de detección de errores y la calidad de la experiencia de sincronización.</span><span class="sxs-lookup"><span data-stu-id="faf5c-183">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="faf5c-184">Outlook</span><span class="sxs-lookup"><span data-stu-id="faf5c-184">Outlook</span></span>

- <span data-ttu-id="faf5c-185">Se corrigió un problema que causaba un problema de rendimiento importante al iniciar Outlook en algunos espacios empresariales.</span><span class="sxs-lookup"><span data-stu-id="faf5c-185">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="faf5c-186">Skype</span><span class="sxs-lookup"><span data-stu-id="faf5c-186">Skype</span></span>

- <span data-ttu-id="faf5c-187">Se corrigió un problema por el que se podía producir un error al compartir la pantalla en un cliente de Skype Empresarial de 32 bits después de ejecutarlo durante varios días.</span><span class="sxs-lookup"><span data-stu-id="faf5c-187">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="faf5c-188">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="faf5c-188">Office Suite</span></span>

- <span data-ttu-id="faf5c-189">Se corrigió un problema que se producía al desactivar el autoguardado a través de la directiva de grupo: era posible que algunos documentos no mostraran el contenido más reciente de servidor al abrirse hasta que el usuario hiciera clic en "Actualizaciones disponibles".</span><span class="sxs-lookup"><span data-stu-id="faf5c-189">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-august-11"></a><span data-ttu-id="faf5c-191">Versión 1908: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="faf5c-191">Version 1908: August 11</span></span>
<span data-ttu-id="faf5c-192">*Versión 1908 (compilación 11929.20934)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-192">*Version 1908 (Build 11929.20934)*</span></span>

<span data-ttu-id="faf5c-193">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-193">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1902-august-11"></a><span data-ttu-id="faf5c-194">Versión 1902: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="faf5c-194">Version 1902: August 11</span></span>
<span data-ttu-id="faf5c-195">*Versión 1902 (compilación 11328.20644)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-195">*Version 1902 (Build 11328.20644)*</span></span>

<span data-ttu-id="faf5c-196">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-196">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-july-14"></a><span data-ttu-id="faf5c-199">Versión 2002: 14 de julio</span><span class="sxs-lookup"><span data-stu-id="faf5c-199">Version 2002: July 14</span></span>
<span data-ttu-id="faf5c-200">*Versión 2002 (compilación 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-200">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="faf5c-201">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-201">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="faf5c-203">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="faf5c-203">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="faf5c-204">Access</span><span class="sxs-lookup"><span data-stu-id="faf5c-204">Access</span></span>

- <span data-ttu-id="faf5c-205">**Buscar tablas vinculadas rápidamente:** nuestro nuevo cuadro de búsqueda hace que buscar tablas vinculadas sea mucho más sencillo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-205">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="faf5c-206">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-206">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="faf5c-207">Excel</span><span class="sxs-lookup"><span data-stu-id="faf5c-207">Excel</span></span>

- <span data-ttu-id="faf5c-208">**Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-208">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="faf5c-209">**Complemento del visualizador de datos:** Crear rápidamente diagramas de flujo de Visio desde Excel.</span><span class="sxs-lookup"><span data-stu-id="faf5c-209">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="faf5c-210">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-210">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="faf5c-211">**Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.</span><span class="sxs-lookup"><span data-stu-id="faf5c-211">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="faf5c-212">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-212">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="faf5c-213">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="faf5c-213">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="faf5c-214">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-214">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="faf5c-215">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-215">Find them at Insert > Icons.</span></span> [<span data-ttu-id="faf5c-216">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-216">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="faf5c-217">**Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los demás.</span><span class="sxs-lookup"><span data-stu-id="faf5c-217">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="faf5c-218">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="faf5c-218">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="faf5c-219">**Resalte lo que queda por hacer**: seleccione Resolver para contraer los comentarios y hacer que resalten los elementos abiertos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-219">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="faf5c-220">**Escriba una fórmula que devuelva varios valores:** Escriba rápidamente una fórmula que devuelva múltiples valores y se derramarán automáticamente en las celdas vecinas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-220">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="faf5c-221">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-221">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="faf5c-222">Ver detalles en [entrada de blog](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="faf5c-222">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="faf5c-223">**Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. </span><span class="sxs-lookup"><span data-stu-id="faf5c-223">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="faf5c-224">**Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su libro.</span><span class="sxs-lookup"><span data-stu-id="faf5c-224">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="faf5c-225">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-225">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="faf5c-226">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="faf5c-226">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="faf5c-227">**Encuentre lo que busca:** Realice búsquedas de comandos, personas, archivos, fotos, artículos en la web y más.</span><span class="sxs-lookup"><span data-stu-id="faf5c-227">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="faf5c-228">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-228">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="faf5c-229">**Seis potentes funciones:** Seis potentes funciones: Hemos agregado seis nuevas funciones para mejorar las hojas de cálculo: FILTRAR, ORDENAR, ORDENARPOR, UNICOS, SECUENCIA y MATRIZALEAT.</span><span class="sxs-lookup"><span data-stu-id="faf5c-229">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="faf5c-230">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-230">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="faf5c-231">**Busque a la izquierda, busque a la derecha... BUSCARX ya está aquí**: fila por fila, busque lo que necesite en una tabla o un rango con BUSCARX.</span><span class="sxs-lookup"><span data-stu-id="faf5c-231">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="faf5c-232">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-232">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="faf5c-233">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span><span class="sxs-lookup"><span data-stu-id="faf5c-233">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="faf5c-234">**Dominar el libro grande:** celdas, fórmulas, gráficos y tablas... Obtenga una instantánea de su libro con estadísticas de libros.</span><span class="sxs-lookup"><span data-stu-id="faf5c-234">**Tame your big workbook:** Cells, formulas, charts, tables... get a snapshot of your workbook with Workbook Statistics.</span></span>

- <span data-ttu-id="faf5c-235">**Lea y responda sobre la marcha:** responda a los comentarios y las menciones directamente desde el correo electrónico sin abrir el libro.</span><span class="sxs-lookup"><span data-stu-id="faf5c-235">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="faf5c-236">**Consiga su atención con\@menciones:** use @menciones en los comentarios para avisar a los compañeros de trabajo cuando necesite su participación.</span><span class="sxs-lookup"><span data-stu-id="faf5c-236">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="faf5c-237">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-237">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a><span data-ttu-id="faf5c-238">Outlook</span><span class="sxs-lookup"><span data-stu-id="faf5c-238">Outlook</span></span>

- <span data-ttu-id="faf5c-239">**Encajar más mensajes en la pantalla:** seleccione Ver > Usar espaciado más estrecho para ajustar el espaciado entre mensajes.</span><span class="sxs-lookup"><span data-stu-id="faf5c-239">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="faf5c-240">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-240">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="faf5c-241">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-241">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="faf5c-242">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-242">Find them at Insert > Icons.</span></span> [<span data-ttu-id="faf5c-243">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-243">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="faf5c-244">**Deja que lo dibuje:** garabatee sobre las imágenes o agregue un Lienzo de dibujo para enviar sus pensamientos con la entrada de lápiz.</span><span class="sxs-lookup"><span data-stu-id="faf5c-244">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="faf5c-245">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-245">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="faf5c-246">**Obtenga sugerencias de ubicaciones:** Empiece a escribir en Ubicación cuando programe citas y reuniones, Outlook le sugerirá salas, direcciones y otros lugares recientes.</span><span class="sxs-lookup"><span data-stu-id="faf5c-246">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="faf5c-247">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-247">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br /><span data-ttu-id="faf5c-248">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="faf5c-248">See details in [blog post](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span></span>

- <span data-ttu-id="faf5c-249">**Protección avanzada frente a ataques**: con la Protección contra amenazas avanzada de Office 365, estará protegido frente a ataques mediante hipervínculos en asuntos de correos electrónicos, mensajes adjuntos, mensajes firmados, rutas de red, etc.</span><span class="sxs-lookup"><span data-stu-id="faf5c-249">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="faf5c-250">**Insertar el menú de vínculos en Outlook inserta un vínculo con el permiso definido por el administrador de inquilinos:** un vínculo desde Insertar vínculo utilizado recientemente en Outlook insertaba un vínculo que solo funcionaba para los usuarios que ya tenían permisos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-250">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="faf5c-251">A menudo esto causaba un intercambio continuo de mensajes de correo electrónico entre los usuarios que pedían acceso a un documento.</span><span class="sxs-lookup"><span data-stu-id="faf5c-251">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="faf5c-252">Hemos actualizado esta experiencia para que ahora el vínculo se inserte con el permiso predeterminado establecido por el administrador de inquilinos. Para MSIT se trata de "la organización puede editar", por lo que todos los usuarios internos que reciban un vínculo compartido de esta manera podrán acceder a él.</span><span class="sxs-lookup"><span data-stu-id="faf5c-252">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="faf5c-253">**Ver los mensajes bajo otra luz:** use el botón sol/luna para cambiar entre fondos claros y oscuros en el panel de lectura.</span><span class="sxs-lookup"><span data-stu-id="faf5c-253">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="faf5c-254">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-254">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="faf5c-255">**Ahora es más fácil detectar correos de suplantación de identidad:** los mensajes de correo no deseado y de suplantación de identidad tienen un aspecto diferente para que pueda identificarlos y eliminarlos fácilmente en la bandeja de entrada.</span><span class="sxs-lookup"><span data-stu-id="faf5c-255">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="faf5c-p123">**Todas las opciones de cifrado en un solo lugar:** vaya a Opciones > Cifrar para elegir cómo proteger su mensaje de correo. [Más información](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="faf5c-p123">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="faf5c-258">**Busque incluso con errores ortográficos o tipográficos:** Outlook encontrará lo que busca, aunque no coincida con la forma exacta en que lo escribió.</span><span class="sxs-lookup"><span data-stu-id="faf5c-258">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="faf5c-259">**Conecte su red de LinkedIn con Outlook:** Conecte de forma segura su cuenta de LinkedIn con su cuenta de Microsoft para ver la información de los perfiles de LinkedIn directamente en las tarjetas personales.</span><span class="sxs-lookup"><span data-stu-id="faf5c-259">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="faf5c-260">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-260">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="faf5c-261">**Ver mensajes relevantes en los resultados de búsqueda:** Outlook analiza los términos de búsqueda y muestra los mensajes de correo electrónico más relevantes en la parte superior de los resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="faf5c-261">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="faf5c-262">También verá todos los resultados ordenados por fecha en la sección de Resultados principales.</span><span class="sxs-lookup"><span data-stu-id="faf5c-262">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="faf5c-263">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-263">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a><span data-ttu-id="faf5c-264">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="faf5c-264">PowerPoint</span></span>

- <span data-ttu-id="faf5c-p126">**Usted calcula y nosotros le damos formato:** hemos convertido las expresiones matemáticas escritas a mano en caracteres estándar. Simplemente elija Entrada de lápiz a matemáticas y seleccione las notas escritas a mano para empezar. [Más información](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="faf5c-p126">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="faf5c-268">**Encuentre lo que busca:** use el cuadro de búsqueda para buscar texto, comandos, ayuda y mucho más.</span><span class="sxs-lookup"><span data-stu-id="faf5c-268">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="faf5c-269">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-269">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="faf5c-270">**Entrada de tinta para magníficas diapositivas:** convierta el texto de tinta en formas estándar y texto y obtenga ideas de diseño inteligente del Diseñador de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="faf5c-270">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="faf5c-271">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-271">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="faf5c-272">**Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su presentación.</span><span class="sxs-lookup"><span data-stu-id="faf5c-272">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="faf5c-273">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-273">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="faf5c-274">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="faf5c-274">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="faf5c-275">**Repetición de entrada de lápiz:** cuando haya entradas de lápiz en sus diapositivas, aplique una animación de reproducción para reproducir el dibujo real de la entrada de lápiz durante la presentación con diapositivas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-275">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="faf5c-276">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-276">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br /><span data-ttu-id="faf5c-277">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="faf5c-277">See details in [blog post](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span></span>

- <span data-ttu-id="faf5c-278">**Una experiencia de vídeo más segura:** las mejoras de seguridad hacen que la experiencia de vídeo en línea sea más segura.</span><span class="sxs-lookup"><span data-stu-id="faf5c-278">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="faf5c-279">**Guarde una ilustración como SVG:** guarde un gráfico, una forma o una ilustración como un gráfico vectorial escalable, que se puede cambiar de tamaño sin perder calidad de imagen.</span><span class="sxs-lookup"><span data-stu-id="faf5c-279">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="faf5c-280">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-280">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="faf5c-281">**Impresión de números de diapositiva en documentos:** los números de diapositiva se incluyen automáticamente en los documentos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-281">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="faf5c-282">Ahora es usted quien decide si los deja o los quita.</span><span class="sxs-lookup"><span data-stu-id="faf5c-282">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="faf5c-283">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-283">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="faf5c-284">**Encuentre los títulos de diapositivas que faltan y escríbalos**: los títulos de diapositivas añaden fuerza a su discurso y permiten que las diapositivas sean accesibles para los usuarios de todas las capacidades.</span><span class="sxs-lookup"><span data-stu-id="faf5c-284">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="faf5c-285">El comprobador de accesibilidad le muestra dónde faltan títulos para que pueda agregarlos en el momento.</span><span class="sxs-lookup"><span data-stu-id="faf5c-285">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="faf5c-286">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-286">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="faf5c-287">**Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los demás.</span><span class="sxs-lookup"><span data-stu-id="faf5c-287">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="faf5c-288">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="faf5c-288">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="faf5c-289">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-289">**More icons to match your mood:** We've added more than 300 new icons.</span></span> <span data-ttu-id="faf5c-290">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-290">Find them at Insert > Icons.</span></span> [<span data-ttu-id="faf5c-291">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-291">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="faf5c-292">**Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.</span><span class="sxs-lookup"><span data-stu-id="faf5c-292">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span><br /><span data-ttu-id="faf5c-293">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="faf5c-293">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="faf5c-294">**Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-294">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="faf5c-295">**Colaboración rápida en tiempo real en PowerPoint:** colaboración rápida en tiempo real en PowerPoint</span><span class="sxs-lookup"><span data-stu-id="faf5c-295">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="faf5c-296">**Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. </span><span class="sxs-lookup"><span data-stu-id="faf5c-296">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="faf5c-297">**Nuevas herramientas de revisión:** no se preocupe de las palabras.</span><span class="sxs-lookup"><span data-stu-id="faf5c-297">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="faf5c-298">Ahora en PowerPoint se ofrecen sugerencias de gramática y escritura.</span><span class="sxs-lookup"><span data-stu-id="faf5c-298">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="faf5c-299">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-299">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="faf5c-300">**Transcripción y subtítulos en directo:** las palabras del moderador se muestran automáticamente en la pantalla como subtítulos o se traducen en el idioma que prefiera.</span><span class="sxs-lookup"><span data-stu-id="faf5c-300">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="faf5c-301">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-301">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="faf5c-302">**Optimizar la presentación para todos:** el comprobador de accesibilidad le ayuda a organizar los objetos de las diapositivas pensando en los lectores de pantalla.</span><span class="sxs-lookup"><span data-stu-id="faf5c-302">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span><br /><span data-ttu-id="faf5c-303">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span><span class="sxs-lookup"><span data-stu-id="faf5c-303">See details in [blog post](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span></span>

- <span data-ttu-id="faf5c-304">**¿Para que reinventar lo que puede reutilizar?:** ahorre tiempo usando de nuevo las diapositivas que haya creado o que otros usuarios han compartido con usted.</span><span class="sxs-lookup"><span data-stu-id="faf5c-304">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="faf5c-305">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-305">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a><span data-ttu-id="faf5c-306">Visio</span><span class="sxs-lookup"><span data-stu-id="faf5c-306">Visio</span></span>

- <span data-ttu-id="faf5c-307">**Cree diagramas de Visio elegantes en Excel:** cree un diagrama de flujo o un organigrama con solo escribir datos en una hoja de cálculo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-307">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="faf5c-308">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-308">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="faf5c-309">**Vuelva a la escena del crimen:** use las nuevas plantillas Evidencia, Interior y Exterior en la plantilla Investigación de Escenas de Delitos para recrear con detalle escenarios de delitos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-309">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

### <a name="word"></a><span data-ttu-id="faf5c-310">Word</span><span class="sxs-lookup"><span data-stu-id="faf5c-310">Word</span></span>

- <span data-ttu-id="faf5c-311">**Una experiencia de vídeo más segura:** las mejoras de seguridad hacen que la experiencia de vídeo en línea sea más segura.</span><span class="sxs-lookup"><span data-stu-id="faf5c-311">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="faf5c-312">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-312">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="faf5c-313">**Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.</span><span class="sxs-lookup"><span data-stu-id="faf5c-313">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="faf5c-314">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-314">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="faf5c-315">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="faf5c-315">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="faf5c-316">**Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-316">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="faf5c-317">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-317">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="faf5c-318">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-318">Find them at Insert > Icons.</span></span> [<span data-ttu-id="faf5c-319">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-319">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br /><span data-ttu-id="faf5c-320">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span><span class="sxs-lookup"><span data-stu-id="faf5c-320">See details in [blog post](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span></span>

- <span data-ttu-id="faf5c-321">**Borrar con precisión:** elija entre dos tamaños de borrador para arreglar pequeñas imperfecciones de la entrada de lápiz.</span><span class="sxs-lookup"><span data-stu-id="faf5c-321">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="faf5c-322">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-322">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="faf5c-323">**Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los demás.</span><span class="sxs-lookup"><span data-stu-id="faf5c-323">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="faf5c-324">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="faf5c-324">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="faf5c-325">**Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su documento.</span><span class="sxs-lookup"><span data-stu-id="faf5c-325">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="faf5c-326">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-326">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="faf5c-327">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="faf5c-327">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="faf5c-328">**Encuentre lo que busca:** use el cuadro de búsqueda para buscar texto, comandos, ayuda y mucho más.</span><span class="sxs-lookup"><span data-stu-id="faf5c-328">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="faf5c-329">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-329">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="faf5c-330">**Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. </span><span class="sxs-lookup"><span data-stu-id="faf5c-330">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="faf5c-331">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-331">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="faf5c-332">**El Editor para currículum vítae incorpora el Asistente para currículum vítae de LinkedIn:** el Editor para currículum vítae ofrece una selección de comprobaciones gramaticales y de estilo especialmente adaptadas a los currículums, para que el texto sea más preciso y profesional.</span><span class="sxs-lookup"><span data-stu-id="faf5c-332">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="faf5c-333">**Otros usuarios verán los cambios rápidamente:** con las mejoras en la coautoría, los colaboradores podrán ver los cambios más rápido que nunca.</span><span class="sxs-lookup"><span data-stu-id="faf5c-333">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="faf5c-334">**Se ha corregido un problema relacionado con los documentos causados por la combinación de objetos 3D:** corrige un problema de daños en un documento producido por la combinación de objetos 3D.</span><span class="sxs-lookup"><span data-stu-id="faf5c-334">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="faf5c-335">**Mejoras en la coautoría:** mejora del rendimiento de Word en coautoría en documentos con marcas de revisión.</span><span class="sxs-lookup"><span data-stu-id="faf5c-335">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="faf5c-336">**Mejoras en la coautoría:** mejora de la confiabilidad de la coautoría.</span><span class="sxs-lookup"><span data-stu-id="faf5c-336">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="faf5c-337">**Colaborando a todo color:** los comentarios y los cambios están codificados por color según la persona que contribuya, por lo que es fácil distinguir entre sus colaboradores.</span><span class="sxs-lookup"><span data-stu-id="faf5c-337">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="faf5c-338">**Editar documentos habilitados para macros de forma conjunta:** guarde sus archivos .docm en OneDrive para la Empresa y edítelos con sus colaboradores en tiempo real.</span><span class="sxs-lookup"><span data-stu-id="faf5c-338">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="faf5c-339">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="faf5c-339">Office Suite</span></span>

- <span data-ttu-id="faf5c-340">**Transforme la entrada de lápiz en formas, texto o matemáticas en PowerPoint para Office 365:** convierta la entrada de lápiz en forma libre a formas, textos o expresiones matemáticas de Office en un par de trazos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-340">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="faf5c-341">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-341">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-344">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-344">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="faf5c-345">Access</span><span class="sxs-lookup"><span data-stu-id="faf5c-345">Access</span></span>

- <span data-ttu-id="faf5c-346">Esta actualización corrige un problema por el que al usar un objeto de grabación de ADODB</span><span class="sxs-lookup"><span data-stu-id="faf5c-346">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="faf5c-347">en el código de VB, se puede notificar un error incorrectamente.</span><span class="sxs-lookup"><span data-stu-id="faf5c-347">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="faf5c-348">Las plantillas de Access ya no deberían causar errores en columnas de datos adjuntos en una base de datos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-348">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="faf5c-349">Después de crear la instancia de una plantilla, ahora debería poder agregar un campo de datos adjuntos a la base de datos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-349">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="faf5c-350">Esta actualización corrige un problema que puede hacer que Microsoft Access no identifique una Columna de identidad en una tabla vinculada de SQL Server, lo que puede provocar que las filas aparezcan como eliminadas de forma incorrecta.</span><span class="sxs-lookup"><span data-stu-id="faf5c-350">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="faf5c-351">Esta actualización corrige un problema en Microsoft Access que puede causar el error "La consulta está dañada" cuando se ejecuta una consulta de actualización o cuando se usa una instrucción UPDATE en SQL.</span><span class="sxs-lookup"><span data-stu-id="faf5c-351">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="faf5c-352">Excel</span><span class="sxs-lookup"><span data-stu-id="faf5c-352">Excel</span></span>

- <span data-ttu-id="faf5c-353">Acelere la carga de archivos que están disponibles en la carpeta de OneDrive local.</span><span class="sxs-lookup"><span data-stu-id="faf5c-353">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="faf5c-354">Se ha solucionado un problema por el que las funciones CUBEVALUE a veces daban un resultado incorrecto.</span><span class="sxs-lookup"><span data-stu-id="faf5c-354">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="faf5c-355">Resuelto un problema con la personalización de la cinta que no se cargaba al abrir el libro de trabajo incrustado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-355">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="faf5c-356">Excel se bloqueaba en ciertos casos cuando se volvía a abrir un libro incrustado en Word o PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="faf5c-356">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="faf5c-357">Se ha corregido un problema por el que los comandos de comentario en el menú contextual no aparecían.</span><span class="sxs-lookup"><span data-stu-id="faf5c-357">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="faf5c-358">Se ha corregido el botón derecho en el menú de gráficos dinámicos para habilitar la opción de mostrar los detalles.</span><span class="sxs-lookup"><span data-stu-id="faf5c-358">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="faf5c-359">Se ha resuelto un problema que puede haber causado un bloqueo al buscar archivos recientes cuando no hay ningún libro de trabajo abierto.</span><span class="sxs-lookup"><span data-stu-id="faf5c-359">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="faf5c-360">Se ha corregido un problema que provocaba que, al hacer clic en un hipervínculo marcado en el propio libro, se ocultara dicho libro.</span><span class="sxs-lookup"><span data-stu-id="faf5c-360">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="faf5c-361">Cuando guarda como un archivo CSV, Excel podía combinar todas las columnas en una sola columna en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-361">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="faf5c-362">Usar Range.ClearContents en un rango de una hoja protegida podía tardar más de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-362">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="faf5c-363">Corregido un problema con la escala de texto en los controles de formulario cuando se mostraba en la Vista previa de impresión.</span><span class="sxs-lookup"><span data-stu-id="faf5c-363">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="faf5c-364">Las macros de VBA que interactúan con la cinta de opciones se pueden ejecutar con ScreenUpdating establecido en True inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="faf5c-364">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="faf5c-365">Se ha corregido un problema que hacía que Excel se bloqueara en ciertos casos después de copiar una hoja que contenía una tabla dinámica.</span><span class="sxs-lookup"><span data-stu-id="faf5c-365">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="faf5c-366">La apertura de archivos CSV tardaba más de lo esperado en algunas circunstancias.</span><span class="sxs-lookup"><span data-stu-id="faf5c-366">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="faf5c-367">Excel se bloqueaba en determinadas circunstancias al cambiar entre libros con diferentes niveles de zoom.</span><span class="sxs-lookup"><span data-stu-id="faf5c-367">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="faf5c-368">Se ha corregido un problema con VBA por el que escribir valores en un rango era más lento de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-368">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="faf5c-369">En ocasiones, los datos copiados de una columna filtrada por color no se pegaban correctamente.</span><span class="sxs-lookup"><span data-stu-id="faf5c-369">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="faf5c-370">La apertura de un libro de trabajo con referencias a muchos otros libros de trabajo, especialmente con ventanas ocultas, era más lenta de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-370">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="faf5c-371">Se ha corregido un problema por el que los enlaces externos no se actualizaban al rellenar (rellenar hacia abajo, rellenar en otros, etc.) si el libro de origen estaba cerrado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-371">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is& closed.</span></span>

- <span data-ttu-id="faf5c-372">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="faf5c-372">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="faf5c-373">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="faf5c-373">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="faf5c-374">Se ha corregido un problema por el que la propiedad "Valor se cruza en" en el eje del gráfico cambiaba inesperadamente al guardar y volver a abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-374">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="faf5c-375">Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta al guardar en SharePoint o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="faf5c-375">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="faf5c-376">Se ha mejorado el rendimiento al eliminar columnas con celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-376">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="faf5c-377">Se ha corregido un problema por el que los nombres de las impresoras podrían repetirse en la lista de impresoras en el cuadro de diálogo Imprimir.</span><span class="sxs-lookup"><span data-stu-id="faf5c-377">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="faf5c-378">Se ha corregido un problema que hacía que el vínculo externo dejara de funcionar después de que se volviera a abrir el archivo si su ruta de acceso era demasiado larga.</span><span class="sxs-lookup"><span data-stu-id="faf5c-378">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="faf5c-379">Se ha corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.</span><span class="sxs-lookup"><span data-stu-id="faf5c-379">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="faf5c-380">Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-380">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="faf5c-381">Insertar una columna en una lista filtrada llevaba más tiempo de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-381">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="faf5c-382">Se ha corregido un problema por el que algunos vínculos de un gráfico copiado y pegado usaban direcciones de unidad asignadas, en lugar de direcciones universales.</span><span class="sxs-lookup"><span data-stu-id="faf5c-382">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="faf5c-383">Se ha corregido un problema que producía el siguiente mensaje de error: "No se puede cerrar el libro de trabajo debido a que otro libro hace referencia al mismo". El mensaje aparecía si los complementos se cargaban en orden alfabético en lugar de en un orden especificado por el usuario.</span><span class="sxs-lookup"><span data-stu-id="faf5c-383">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="faf5c-384">Se ha corregido un problema que haría que un libro se ocultara al hacer clic en un hipervínculo a un lugar dentro de un libro ya abierto.</span><span class="sxs-lookup"><span data-stu-id="faf5c-384">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="faf5c-385">La apertura de un libro de trabajo con referencias a muchos otros libros de trabajo, especialmente con ventanas ocultas, era más lenta de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-385">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="faf5c-386">El uso de Application.Evaluate de VBA no funcionaba para funciones definidas por el usuario en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-386">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="faf5c-387">Se ha corregido un problema que algunos usuarios pudieron sufrir con objetos incrustados y vinculados (OLE).</span><span class="sxs-lookup"><span data-stu-id="faf5c-387">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="faf5c-388">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="faf5c-388">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="faf5c-389">Esta actualización corrige un problema que causaba que la barra de fórmulas mostrara texto en una fuente diferente a la esperada.</span><span class="sxs-lookup"><span data-stu-id="faf5c-389">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="faf5c-390">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="faf5c-390">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="faf5c-391">Corregimos un problema en el que al seleccionar una celda luego de desplazar, podía resultar en la selección de la celda incorrecta.</span><span class="sxs-lookup"><span data-stu-id="faf5c-391">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="faf5c-392">Los usuarios pueden encontrar un error al acceder a un rango con nombre oculto.</span><span class="sxs-lookup"><span data-stu-id="faf5c-392">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="faf5c-393">Excel puede tener problemas al editar un archivo protegido desde una red compartida no confiable.</span><span class="sxs-lookup"><span data-stu-id="faf5c-393">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="faf5c-394">La funcionalidad de texto a columna puede fallar en algunas localizaciones.</span><span class="sxs-lookup"><span data-stu-id="faf5c-394">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="faf5c-395">Se ha corregido un problema de rendimiento al crear gráficos a partir de plantillas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-395">Addresses a performance issue when creating charts from templates.</span></span>

- <span data-ttu-id="faf5c-396">Se ha corregido un problema que causaba que algunos usuarios experimentasen bloqueos al convertir texto en columnas con celdas que tienen una matriz derramada.</span><span class="sxs-lookup"><span data-stu-id="faf5c-396">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="faf5c-397">El uso de un Range.Value y Range.Value2 (VBA) hacía que las fórmulas se escribieran como matrices dinámicas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-397">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

- <span data-ttu-id="faf5c-398">Se ha corregido un problema por el que un símbolo @ que inicia una fórmula se considera un operador de intersección implícita.</span><span class="sxs-lookup"><span data-stu-id="faf5c-398">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

- <span data-ttu-id="faf5c-399">Se ha corregido un problema por el que las hojas de cálculo que contenían varias fórmulas con nombres definidos tardaban más en guardarse.</span><span class="sxs-lookup"><span data-stu-id="faf5c-399">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="faf5c-400">Este cambio evita un problema con ciertos controladores de gráficos Intel al aprovechar el procesamiento del software.</span><span class="sxs-lookup"><span data-stu-id="faf5c-400">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="faf5c-401">Se ha corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.</span><span class="sxs-lookup"><span data-stu-id="faf5c-401">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="onenote"></a><span data-ttu-id="faf5c-402">OneNote</span><span class="sxs-lookup"><span data-stu-id="faf5c-402">OneNote</span></span>

- <span data-ttu-id="faf5c-403">Mejora la sincronización y la estabilidad del servicio al ajustar temporalmente la frecuencia de sincronización en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="faf5c-403">Improve sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="faf5c-404">Mejora la sincronización y la estabilidad del servicio al diferir temporalmente la descarga de archivos e imágenes incrustados en los blocs de notas en línea hasta que el usuario navegue a la página en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="faf5c-404">Improve sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="faf5c-405">Mejora la sincronización y la estabilidad del servicio al deshabilitar temporalmente la papelera de reciclaje en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="faf5c-405">Improve sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="faf5c-406">Cuando un usuario intenta eliminar datos que normalmente se enviarían a la papelera de reciclaje, se le preguntará si prefiere conservarlos o eliminarlos forma permanente.</span><span class="sxs-lookup"><span data-stu-id="faf5c-406">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="faf5c-407">Mejora la sincronización y estabilidad de servicio mejoradas al reducir temporalmente el número y la frecuencia de sincronización de las páginas del historial de versiones en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="faf5c-407">Improve sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="faf5c-408">Muestra una notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="faf5c-408">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="faf5c-409">Mejora la sincronización y la estabilidad del servicio al reducir temporalmente el tamaño máximo de nuevos datos adjuntos insertados a 50 MB en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="faf5c-409">Improve sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="faf5c-410">Si los archivos superan este límite, los usuarios tendrán la opción de cargar el archivo a OneDrive e insertar un vínculo en OneNote.</span><span class="sxs-lookup"><span data-stu-id="faf5c-410">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="faf5c-411">Mejora la sincronización y la estabilidad del servicio al deshabilitar temporalmente la grabación de vídeo en la aplicación en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="faf5c-411">Improve sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="faf5c-412">La medida no afecta a los blocs de notas locales.</span><span class="sxs-lookup"><span data-stu-id="faf5c-412">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="faf5c-413">Localiza la notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="faf5c-413">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="faf5c-414">Outlook</span><span class="sxs-lookup"><span data-stu-id="faf5c-414">Outlook</span></span>

- <span data-ttu-id="faf5c-415">Se ha corregido un problema por el que la ventana del Editor de métodos de entrada (IME) se superponía al texto subyacente escrito mediante el IME cuando se usaban varios monitores con resoluciones diferentes.</span><span class="sxs-lookup"><span data-stu-id="faf5c-415">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="faf5c-416">Se ha corregido un problema que provocaba que los usuarios vean bloqueos ocasionales en Outlook.</span><span class="sxs-lookup"><span data-stu-id="faf5c-416">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="faf5c-417">Esto actualiza la lógica de bloqueo de adjuntos en Outlook para bloquear también los adjuntos de Python.</span><span class="sxs-lookup"><span data-stu-id="faf5c-417">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="faf5c-418">Se ha corregido un problema que provocaba que los complementos web accedieran a los mensajes administrados con derechos digitales.</span><span class="sxs-lookup"><span data-stu-id="faf5c-418">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="faf5c-419">Se ha corregido un problema que causaba que las citas o reuniones periódicas se mostraran en un momento incorrecto al tratar de cambiar la definición de una zona horaria.</span><span class="sxs-lookup"><span data-stu-id="faf5c-419">Addresses an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="faf5c-420">Cuando se utiliza la zona horaria de Brasilia en el año 2019, las reuniones y citas recurrentes se muestran en la franja horaria equivocada para el año 2020.</span><span class="sxs-lookup"><span data-stu-id="faf5c-420">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="faf5c-421">Este cambio es relevante para los clientes establecidos en la zona horaria de Brasilia o para las reuniones y citas establecidas en esa zona horaria.</span><span class="sxs-lookup"><span data-stu-id="faf5c-421">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span><br><br><span data-ttu-id="faf5c-422">Este cambio permite a Outlook reemplazar algunas opciones de configuración de zona horaria utilizadas por Outlook.</span><span class="sxs-lookup"><span data-stu-id="faf5c-422">This change allows Outlook to override certain time zone settings used by Outlook.</span></span> <span data-ttu-id="faf5c-423">Para invocar una invalidación de zona horaria, debe establecer una clave del registro para el usuario actual.</span><span class="sxs-lookup"><span data-stu-id="faf5c-423">In order to invoke a time zone override you must set a registry key for the current user.</span></span> <span data-ttu-id="faf5c-424">El nombre de la clave del registro debe coincidir con el nombre interno de la zona horaria.</span><span class="sxs-lookup"><span data-stu-id="faf5c-424">The registry key name must match the internal name of the time zone.</span></span> <span data-ttu-id="faf5c-425">El valor indica el año en el que se va a usar la regla de zona horaria en vez del año efectivo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-425">The value indicates the time zone rule's year to be used in place of the effective year.</span></span> <span data-ttu-id="faf5c-426">Por ejemplo, el siguiente valor para reemplazar la clave del registro usará la regla de zona horaria de Brasil para el año 2020 como regla efectiva.</span><span class="sxs-lookup"><span data-stu-id="faf5c-426">For example, the following registry key override value will use the Brazilia time zone rule for the year 2020 as the effective rule.</span></span> <span data-ttu-id="faf5c-427">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span><span class="sxs-lookup"><span data-stu-id="faf5c-427">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span></span> <span data-ttu-id="faf5c-428">Hora estándar de Sudamérica"=dword:000007e4.</span><span class="sxs-lookup"><span data-stu-id="faf5c-428">South America Standard Time"=dword:000007e4.</span></span>

- <span data-ttu-id="faf5c-429">Se ha corregido un problema por el que los usuarios veían cambiar el campo de ubicación de las reuniones de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="faf5c-429">Addresses an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="faf5c-430">Se ha corregido un problema que provocaba que el campo Ubicación en las reuniones se actualizara de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="faf5c-430">Addresses an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="faf5c-431">Se ha corregido un problema que provocó que la ubicación de una reunión se volviera a añadir a la reunión de forma inesperada después de despejarla.</span><span class="sxs-lookup"><span data-stu-id="faf5c-431">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="faf5c-432">Se ha corregido un tema que causó que las comas en el campo de ubicación de una reunión se convirtieran en punto y coma.</span><span class="sxs-lookup"><span data-stu-id="faf5c-432">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="faf5c-433">Permite unirse a una reunión de Teams directamente a través del cliente nativo de Teams.</span><span class="sxs-lookup"><span data-stu-id="faf5c-433">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="faf5c-434">Se ha corregido un problema que provocaba que los usuarios con buzones en servidores de Exchange 2010 sufrieran problemas al agregar archivos adjuntos a elementos de calendario.</span><span class="sxs-lookup"><span data-stu-id="faf5c-434">Addresses an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="faf5c-435">Se ha corregido un problema que provocaba que los usuarios experimentaran problemas al responder a los mensajes firmados digitalmente.</span><span class="sxs-lookup"><span data-stu-id="faf5c-435">Addresses an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="faf5c-436">Se ha corregido un problema que provocaba que los usuarios no pudieran abrir algunas instancias de los elementos de calendario periódicos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-436">Addresses an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="faf5c-437">Se ha corregido un problema que hacía que el encabezado de grupo se expandiera de forma inesperada en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="faf5c-437">Addresses an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="faf5c-438">Se ha corregido un problema que provocaba que el ancho del panel de carpetas cambiara de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="faf5c-438">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="faf5c-439">Se ha corregido un problema por el que Outlook no pudo habilitar consejos de directiva para la Protección de pérdida de datos para usuarios que pagaron por el servicio con planes M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="faf5c-439">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="faf5c-440">Se ha corregido un problema por el que los usuarios notaban un retraso evidente al interactuar con sus carpetas de buzón mediante métodos abreviados de teclado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-440">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="faf5c-441">Se ha corregido un problema que podría resultar en un choque al ver el mismo elemento en varias ventanas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-441">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="faf5c-442">Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al actualizar sus reglas en Outlook.</span><span class="sxs-lookup"><span data-stu-id="faf5c-442">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="faf5c-443">Se ha corregido un problema que causaba una pérdida de memoria en sesiones de Outlook muy largas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-443">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="faf5c-444">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.</span><span class="sxs-lookup"><span data-stu-id="faf5c-444">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="faf5c-445">Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al abrir el cuadro de diálogo de Reglas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-445">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="faf5c-446">Se ha corregido un problema por el que la opción para deshabilitar el resaltado de elementos marcados no funcionaba en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="faf5c-446">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="faf5c-447">Se ha corregido un problema que provocaba que los usuarios vieran mensajes enviados inesperadamente al presionar la tecla "S" después de cerrar el panel del comprobador de accesibilidad.</span><span class="sxs-lookup"><span data-stu-id="faf5c-447">Addresses an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="faf5c-448">Se ha corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.</span><span class="sxs-lookup"><span data-stu-id="faf5c-448">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="faf5c-449">Se ha corregido un problema que provocaba que los usuarios experimentaran un error al cancelar la configuración de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="faf5c-449">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="faf5c-450">Se ha corregido un problema por el que Outlook sincronizaba inesperadamente todo el correo, incluso cuando el deslizador de sincronización estaba configurado en un ajuste menor.</span><span class="sxs-lookup"><span data-stu-id="faf5c-450">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="faf5c-451">Se ha corregido un problema que provocaba que los usuarios con el Tema negro vieran texto blanco sobre un fondo blanco en el desplegable "De".</span><span class="sxs-lookup"><span data-stu-id="faf5c-451">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="faf5c-452">Se ha corregido un problema que provocaba que los usuarios sufrieran un bloqueo durante la creación del perfil.</span><span class="sxs-lookup"><span data-stu-id="faf5c-452">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="faf5c-453">Se ha corregido un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "OK" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="faf5c-453">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="faf5c-454">Se ha corregido un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "OK" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="faf5c-454">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="faf5c-455">Se ha corregido un problema que provocaba que las aplicaciones de terceros no pudiesen enviar correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="faf5c-455">Addresses an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="faf5c-456">Se ha corregido un problema que provocaba que las categorías desapareciesen en ocasiones de los mensajes de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="faf5c-456">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="faf5c-457">Se ha corregido un problema que provocaba que los usuarios de Outlook en sistemas operativos de servidor vieran el error: "Estado del antivirus: no válido.</span><span class="sxs-lookup"><span data-stu-id="faf5c-457">Addresses an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="faf5c-458">Esta versión de Windows admite la detección del antivirus, pero no se encontró ninguno" a pesar de tener el antivirus correctamente configurado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-458">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

- <span data-ttu-id="faf5c-459">Se ha corregido un problema que provocaba que los delegados viesen distintas jerarquías de carpetas en diferentes equipos para los buzones compartidos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-459">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="faf5c-460">Se ha corregido un problema que causaba que los delegados reciban un error al editar una cita de calendario existente en el calendario de un administrador.</span><span class="sxs-lookup"><span data-stu-id="faf5c-460">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="faf5c-461">Se ha corregido un problema que provocaba que los usuarios con la configuración de emulación de explorador incorrecta no pudieran completar el mensaje de autenticación de Gmail.</span><span class="sxs-lookup"><span data-stu-id="faf5c-461">Addresses an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="faf5c-462">Se ha corregido un problema que causaba que faltara la opción "Permitir reenvío" en las "Opciones de respuesta" de la reunión de calendario compartida cuando NO está marcada Descargar carpeta compartida.</span><span class="sxs-lookup"><span data-stu-id="faf5c-462">Addresses an issue that caused the " Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="faf5c-463">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al intentar abrir archivos .msg y .oft después de una actualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="faf5c-463">Addresses an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="faf5c-464">Se ha corregido un problema que causaba que los usuarios experimentaran ocasionalmente un bloqueo al usar el botón X de su ratón.</span><span class="sxs-lookup"><span data-stu-id="faf5c-464">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="faf5c-465">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al seleccionar determinados resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="faf5c-465">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="faf5c-466">Se ha corregido un problema que hizo que el botón "Guardar en la nube" faltara en las herramientas de adjuntos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-466">Addresses an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="faf5c-467">Este cambio restaura la capacidad de ver sujetos de varias líneas en el encabezado del mensaje.</span><span class="sxs-lookup"><span data-stu-id="faf5c-467">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="faf5c-468">Se ha corregido un problema que causaba que los usuarios experimentaran un bloqueo cuando dos complementos agregan un botón al mismo grupo de la cinta de opciones.</span><span class="sxs-lookup"><span data-stu-id="faf5c-468">Addresses an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="faf5c-469">Se ha corregido un problema que provocaba que los vínculos no se agreguen a los correos electrónicos con el permiso predeterminado incorrecto de espacio empresarial cuando el permiso predeterminado de espacio empresarial se configura como "cualquiera".</span><span class="sxs-lookup"><span data-stu-id="faf5c-469">Addresses an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as "anyone".</span></span>

- <span data-ttu-id="faf5c-470">Se ha corregido un problema que provocaba que los usuarios no pudieran dirigir mensajes de correo electrónico a una lista de distribución personal.</span><span class="sxs-lookup"><span data-stu-id="faf5c-470">Addresses an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="faf5c-471">Se ha corregido un problema que hacía que los usuarios vieran el truncamiento del cuerpo del mensaje al reenviar mensajes HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="faf5c-471">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="faf5c-472">Se ha corregido un problema con la selección del algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="faf5c-472">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="faf5c-473">Se ha corregido un problema que podía impedir que los archivos se guardaran en una ubicación de WebDAV.</span><span class="sxs-lookup"><span data-stu-id="faf5c-473">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="faf5c-474">Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.</span><span class="sxs-lookup"><span data-stu-id="faf5c-474">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="faf5c-475">Se ha corregido un problema que provocaba que el cuerpo de un mensaje NDR cambiara de Unicode a ASCII después de editar el asunto.</span><span class="sxs-lookup"><span data-stu-id="faf5c-475">Addresses an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="faf5c-476">Se ha corregido un problema que hacía que los usuarios observaran una pérdida de memoria en el proceso de Outlook.</span><span class="sxs-lookup"><span data-stu-id="faf5c-476">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="faf5c-477">Corrige un problema que provocaba que los usuarios vieran mensajes de correo electrónico enviados a una dirección que no coincidía con la dirección SMTP mostrada en determinadas circunstancias.</span><span class="sxs-lookup"><span data-stu-id="faf5c-477">Addresses an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="faf5c-478">Se ha corregido un problema que provocaba que el cuadro de búsqueda estuviera mal alineado en modo de PPP alto.</span><span class="sxs-lookup"><span data-stu-id="faf5c-478">Addresses an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="faf5c-479">Se ha corregido un problema por el que los usuarios experimentan bloqueos en Outlook al recuperar la configuración de la nube.</span><span class="sxs-lookup"><span data-stu-id="faf5c-479">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="faf5c-480">Se ha corregido un problema que causó un bloqueo en la experiencia de los comentarios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="faf5c-480">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="faf5c-481">Se ha corregido un problema que provocaba que los usuarios vean bloqueos ocasionales en Outlook.</span><span class="sxs-lookup"><span data-stu-id="faf5c-481">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="faf5c-482">Se ha corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.</span><span class="sxs-lookup"><span data-stu-id="faf5c-482">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="faf5c-483">Se ha corregido un problema que provocaba que los usuarios sufrieran un bloqueo durante la creación del perfil.</span><span class="sxs-lookup"><span data-stu-id="faf5c-483">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="faf5c-484">Se ha corregido un problema que provocaba que los usuarios vean bloqueos ocasionales en Outlook.</span><span class="sxs-lookup"><span data-stu-id="faf5c-484">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="faf5c-485">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="faf5c-485">PowerPoint</span></span>

- <span data-ttu-id="faf5c-486">Se ha corregido un problema que podía bloquear el equipo al usar el menú contextual en comentarios PPT heredados.</span><span class="sxs-lookup"><span data-stu-id="faf5c-486">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

- <span data-ttu-id="faf5c-487">Se ha mejorado un escenario de copiar y pegar: al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.</span><span class="sxs-lookup"><span data-stu-id="faf5c-487">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="faf5c-488">Se ha corregido un problema para retransmitir la mensajería correcta a los usuarios que abren una copia de un archivo que ha mejorado los comentarios.</span><span class="sxs-lookup"><span data-stu-id="faf5c-488">Fixes an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="project"></a><span data-ttu-id="faf5c-489">Project</span><span class="sxs-lookup"><span data-stu-id="faf5c-489">Project</span></span>

- <span data-ttu-id="faf5c-490">Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.</span><span class="sxs-lookup"><span data-stu-id="faf5c-490">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="faf5c-491">Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="faf5c-491">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="faf5c-492">Corregido un problema que hace que el evento ProjectBeforeTaskChange no detecte cuándo se ha desactivado o activado una tarea mediante el botón Desactivar.</span><span class="sxs-lookup"><span data-stu-id="faf5c-492">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="faf5c-493">Corregido un problema por el que Project puede bloquearse al guardar proyectos creados con versiones anteriores de Project.</span><span class="sxs-lookup"><span data-stu-id="faf5c-493">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="faf5c-494">Identificamos un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de solo lectura</span><span class="sxs-lookup"><span data-stu-id="faf5c-494">Identified an issue where users could get several messages when opening a read-only project</span></span>

- <span data-ttu-id="faf5c-495">Se ha corregido un problema por el que el 100 % de las tareas de tipo duración fija podían tener un cálculo del porcentaje incorrecto con menos del 100% completado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-495">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="faf5c-496">Word</span><span class="sxs-lookup"><span data-stu-id="faf5c-496">Word</span></span>

- <span data-ttu-id="faf5c-497">Se ha corregido un problema que causaba que los usuarios experimentaran ocasionalmente un bloqueo al usar el botón X de su ratón.</span><span class="sxs-lookup"><span data-stu-id="faf5c-497">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="faf5c-498">Se ha corregido un problema por el que la alineación de las palabras de un documento se descomponía al intentar editar después de imprimir con la impresión rápida.</span><span class="sxs-lookup"><span data-stu-id="faf5c-498">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="faf5c-499">Corregido un problema con el ajuste de texto en una tabla.</span><span class="sxs-lookup"><span data-stu-id="faf5c-499">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="faf5c-500">Corregido un problema donde al insertar líneas horizontales no eran más cortas ni centradas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-500">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>

- <span data-ttu-id="faf5c-501">El organizador de bloques de creación puede mostrar una alerta no válida: "Ha modificado estilos, bloques de creación".</span><span class="sxs-lookup"><span data-stu-id="faf5c-501">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

- <span data-ttu-id="faf5c-502">Se ha corregido un problema de coautoría si se habilita la Directiva FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="faf5c-502">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="faf5c-503">Se ha corregido un problema en el que Word QuickPart no funciona al agregar un campo de búsqueda cuyo nombre se ha cambiado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-503">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

- <span data-ttu-id="faf5c-504">Se ha corregido un problema al combinar dos documentos en uno.</span><span class="sxs-lookup"><span data-stu-id="faf5c-504">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="faf5c-505">Se ha corregido un problema con la característica Comparación para los documentos protegidos para la edición.</span><span class="sxs-lookup"><span data-stu-id="faf5c-505">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="faf5c-506">Esta actualización corrige un problema en Microsoft Word por el que el texto que supera los 255 caracteres insertados durante la aplicación de una etiqueta de confidencialidad no se pudiese identificar y quitar posteriormente cambiando o quitando la etiqueta si la directiva de etiqueta aplicó un encabezado, un pie de página o una marca de agua.</span><span class="sxs-lookup"><span data-stu-id="faf5c-506">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

### <a name="office-suite"></a><span data-ttu-id="faf5c-507">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="faf5c-507">Office Suite</span></span>

- <span data-ttu-id="faf5c-508">Se ha corregido un problema en el que los usuarios puedan experimentar demasiado uso de la red y la CPU durante la coautoría en archivos de PowerPoint grandes.</span><span class="sxs-lookup"><span data-stu-id="faf5c-508">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="faf5c-509">Esta es una corrección para que la aplicación de Project no bloquee la red cuando el archivo se almacena en caché en el cliente.</span><span class="sxs-lookup"><span data-stu-id="faf5c-509">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>


- <span data-ttu-id="faf5c-510">Se ha resuelto este problema mediante la actualización de los nombres de canal en el backstage con los nuevos nombres de canal en la bifurcación de enero de 2020.</span><span class="sxs-lookup"><span data-stu-id="faf5c-510">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="faf5c-511">Se ha corregido este problema y en adelante, si un dispositivo se administra mediante directiva, no llamará a la API de audiencia de DMS.</span><span class="sxs-lookup"><span data-stu-id="faf5c-511">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="faf5c-512">Se ha corregido un problema en el que había una eliminación incompleta al agregar y quitar aplicaciones en una sola transacción.</span><span class="sxs-lookup"><span data-stu-id="faf5c-512">We have resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="faf5c-513">Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.</span><span class="sxs-lookup"><span data-stu-id="faf5c-513">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="faf5c-514">Corrige un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.</span><span class="sxs-lookup"><span data-stu-id="faf5c-514">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="faf5c-515">Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.</span><span class="sxs-lookup"><span data-stu-id="faf5c-515">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="faf5c-516">Hemos modificado la versión AppV51 para solucionar una regresión de la AppV51 anterior.</span><span class="sxs-lookup"><span data-stu-id="faf5c-516">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="faf5c-517">Hemos resuelto el problema por el que una operación interna producía una excepción en caso de error en lugar de registrarlo y continuar.</span><span class="sxs-lookup"><span data-stu-id="faf5c-517">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="faf5c-518">Los usuarios afectados ya no serán bloqueados para recibir actualizaciones.</span><span class="sxs-lookup"><span data-stu-id="faf5c-518">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="faf5c-519">Nuestro equipo ha agregado compatibilidad con clientes para informar la telemetría en los dominios de la red CDN en semianual Enterprise Preview.</span><span class="sxs-lookup"><span data-stu-id="faf5c-519">Our team has added client support for reporting telemetry on the Office CDN domains in Semi-Annual Enterprise Preview.</span></span>

- <span data-ttu-id="faf5c-520">Este cambio resuelve problemas con adaptadores gráficos que aprovechan la GPU integrada de Intel.</span><span class="sxs-lookup"><span data-stu-id="faf5c-520">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="faf5c-521">Este cambio garantiza que el contorno Esbozado funcione correctamente en la cinta de opciones.</span><span class="sxs-lookup"><span data-stu-id="faf5c-521">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="faf5c-522">Se ha corregido un problema al abrir archivos de ubicaciones locales con algunas configuraciones de proxy específicas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-522">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="faf5c-523">Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.</span><span class="sxs-lookup"><span data-stu-id="faf5c-523">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="faf5c-524">Se ha corregido un problema que elimina bloqueos durante las sesiones de entrega de Office y se ha mejorado la fiabilidad de la experiencia del usuario.</span><span class="sxs-lookup"><span data-stu-id="faf5c-524">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>

- <span data-ttu-id="faf5c-525">Este error actualiza el extremo de la URL del servicio de configuración mejorada (ECS).</span><span class="sxs-lookup"><span data-stu-id="faf5c-525">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="faf5c-526">Llamar a este punto de conexión más reciente tiene una tasa de éxito superior para capturar desde ECS.</span><span class="sxs-lookup"><span data-stu-id="faf5c-526">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

- <span data-ttu-id="faf5c-527">Esta actualización corrige un problema en el que con Microsoft Outlook no muestra la etiqueta de confidencialidad actual al ver o redactar mensajes.</span><span class="sxs-lookup"><span data-stu-id="faf5c-527">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="faf5c-528">Corrige un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-528">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

- <span data-ttu-id="faf5c-529">Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="faf5c-529">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="faf5c-530">El host de Office se bloqueaba en Windows, cuando se activaba un complemento si la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth estaba establecida en cero.</span><span class="sxs-lookup"><span data-stu-id="faf5c-530">The office host was crashing in windows, when an add-in is being activated while the registry key  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="faf5c-531">Este cambio arreglaría el problema.</span><span class="sxs-lookup"><span data-stu-id="faf5c-531">This change would fix this issue.</span></span>

- <span data-ttu-id="faf5c-532">Se ha corregido un problema de bloqueo con el host de Office en Windows cuando se activa un complemento mientras el valor del registro TabProcGrowth era del tipo REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="faf5c-532">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="faf5c-533">Esta actualización corrige un problema en Microsoft Office en el que los proyectos de VBA con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.</span><span class="sxs-lookup"><span data-stu-id="faf5c-533">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="faf5c-534">Se ha corregido el problema por el que Access y Publisher podrían no iniciarse correctamente en función de los idiomas que se hubieran instalado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-534">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)





[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-july-14"></a><span data-ttu-id="faf5c-537">Versión 1908: 14 de julio</span><span class="sxs-lookup"><span data-stu-id="faf5c-537">Version 1908: July 14</span></span>
<span data-ttu-id="faf5c-538">*Versión 1908 (Compilación 11929.20904)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-538">*Version 1908 (Build 11929.20904)*</span></span>

<span data-ttu-id="faf5c-539">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-539">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-541">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-541">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="faf5c-542">Access</span><span class="sxs-lookup"><span data-stu-id="faf5c-542">Access</span></span>

- <span data-ttu-id="faf5c-543">Esta actualización corrige un problema en el que la agregación como la suma puede truncar el resultado a un valor entero.</span><span class="sxs-lookup"><span data-stu-id="faf5c-543">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="faf5c-544">Esta actualización corrige un problema por el que una consulta de Unión que incluye referencias a tablas remotas (por ejemplo, tablas de SQL Server) puede hacer que Access se cierre y se reinicie.</span><span class="sxs-lookup"><span data-stu-id="faf5c-544">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="faf5c-545">Esta actualización corrige un problema en Microsoft Access que puede causar el error "La consulta está dañada" cuando se ejecuta una consulta de actualización o cuando se usa una instrucción UPDATE en SQL.</span><span class="sxs-lookup"><span data-stu-id="faf5c-545">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="faf5c-546">Excel</span><span class="sxs-lookup"><span data-stu-id="faf5c-546">Excel</span></span>

- <span data-ttu-id="faf5c-547">La información clave en holandés para el título del documento ha sido cambiada a Alt-G.</span><span class="sxs-lookup"><span data-stu-id="faf5c-547">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="faf5c-548">Se ha corregido un problema en Excel en el que las macros asignadas a formas o controles de formularios podían mostrar un mensaje de error incorrecto o funcionar en intervalos de destino incorrectos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-548">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="faf5c-549">Se resolvió un problema con buscar y reemplazar ese cambio donde el foco estaba en el diálogo después de encontrar el primer elemento.</span><span class="sxs-lookup"><span data-stu-id="faf5c-549">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="faf5c-550">Esto corrige un problema por el cual al cambiar la forma en que se ordena y actualiza una tabla dinámica mientras se está en una sesión de co autoría con otros usuarios se podía provocar un bloqueo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-550">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="faf5c-551">Arreglamos un problema cuando el filtro de una tabla dinámica OLAP se estableció en un valor que se había eliminado del cubo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-551">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="faf5c-552">Esta actualización corrige un problema que provoca un error siempre que se utilizaba VBA para agregar una imagen al encabezado o pie de página de un gráfico.</span><span class="sxs-lookup"><span data-stu-id="faf5c-552">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="faf5c-553">Se ha corregido un problema que podría haber provocado que los gráficos de líneas de dispersión no se representaran correctamente al cambiar la colección de series</span><span class="sxs-lookup"><span data-stu-id="faf5c-553">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span>

- <span data-ttu-id="faf5c-554">Se han corregido los colores que se usan en las vistas previas al insertar gráficos con plantillas de gráficos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-554">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="faf5c-555">Se resolvió un problema que causó que los gráficos de cascada y embudo se desincronizara con las tablas cuando se insertaban o eliminaban celdas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-555">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="faf5c-556">Se ha corregido un problema de conflicto de fusión en Excel que hacía que los usuarios tuvieran que volver a abrir el libro de trabajo para elegir los cambios.</span><span class="sxs-lookup"><span data-stu-id="faf5c-556">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="faf5c-557">Se resolvió un problema que causaba un error de tiempo de ejecución de la macro que activaba las ventanas minimizadas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-557">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="faf5c-558">Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-558">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="faf5c-559">Se resolvió un problema que causaba que las operaciones de cortar y pegar junto a una mesa fallaran cuando se co autoría con otros.</span><span class="sxs-lookup"><span data-stu-id="faf5c-559">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="faf5c-560">Se resolvió un problema que causaba interrupciones de co autoría cuando se cambiaban las propiedades personalizadas con macros en ejecución.</span><span class="sxs-lookup"><span data-stu-id="faf5c-560">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="faf5c-561">Hubo un problema en el que no se podían seleccionar elementos del cuadro combinado de un formulario de WPF (Windows Presentation Foundation) que fue abierto por un complemento.</span><span class="sxs-lookup"><span data-stu-id="faf5c-561">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="faf5c-562">Se ha resuelto un problema que puede haber causado un bloqueo al buscar archivos recientes cuando no hay ningún libro de trabajo abierto.</span><span class="sxs-lookup"><span data-stu-id="faf5c-562">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="faf5c-563">Se ha corregido un problema que hacía que el borde de un control de cuadro de grupo no estuviera visible en la vista previa de impresión o al imprimirlo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-563">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="faf5c-564">Se ha corregido un problema por el que algunos usuarios podían haber experimentado múltiples ventanas emergentes cuando los enlaces externos estaban presentes en el libro de trabajo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-564">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="faf5c-565">Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al usar una macro de VBA para borrar el contenido de un rango.</span><span class="sxs-lookup"><span data-stu-id="faf5c-565">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="faf5c-566">Se ha corregido un problema con VBA por el que escribir valores en un rango era más lento de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-566">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="faf5c-567">Se ha corregido un problema por el que la propiedad "Valor se cruza en" en el eje del gráfico cambiaba inesperadamente al guardar y volver a abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-567">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="faf5c-568">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="faf5c-568">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="faf5c-569">Se ha corregido un problema que provocaba un rendimiento lento al eliminar columnas que contenían celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-569">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="faf5c-570">Se ha corregido un problema con la escala de texto en los controles de formulario cuando se mostraba la Vista previa de impresión.</span><span class="sxs-lookup"><span data-stu-id="faf5c-570">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="faf5c-571">Cuando se copian datos filtrados por colores en una columna con un ancho diferente, los valores no se pegan.</span><span class="sxs-lookup"><span data-stu-id="faf5c-571">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="faf5c-572">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="faf5c-572">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="faf5c-573">Se ha corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.</span><span class="sxs-lookup"><span data-stu-id="faf5c-573">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="faf5c-574">Se ha corregido un problema que provocaba que, al hacer clic en un hipervínculo marcado en el propio libro, se ocultara dicho libro.</span><span class="sxs-lookup"><span data-stu-id="faf5c-574">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="faf5c-575">Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-575">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="faf5c-576">La funcionalidad de Texto a columna puede fallar en algunas configuraciones regionales.</span><span class="sxs-lookup"><span data-stu-id="faf5c-576">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="faf5c-577">Es posible que los usuarios vean un error si acceden a un rango con nombre oculto.</span><span class="sxs-lookup"><span data-stu-id="faf5c-577">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="faf5c-578">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="faf5c-578">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="faf5c-579">Se ha corregido un problema por el que el tamaño de archivo de las imágenes en los encabezados del gráfico aumentaba cuando se guardaba el libro que contenía el gráfico.</span><span class="sxs-lookup"><span data-stu-id="faf5c-579">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>

- <span data-ttu-id="faf5c-580">Problema de rendimiento con las Funciones Asincrónicas Definidas por el Usuario que hacía que se ejecutaran sincrónicamente.</span><span class="sxs-lookup"><span data-stu-id="faf5c-580">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="faf5c-581">Mejoras significativas en el rendimiento de la eliminación de columnas con celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-581">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="faf5c-582">Se resolvió un problema en el que la selección de una celda después del desplazamiento podía dar lugar a que se seleccionara la celda incorrecta.</span><span class="sxs-lookup"><span data-stu-id="faf5c-582">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="faf5c-583">Se ha resuelto un problema en el que la función de búsqueda puede devolver un error.</span><span class="sxs-lookup"><span data-stu-id="faf5c-583">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="faf5c-584">Se ha corregido un problema que provoca la corrupción de caracteres DBCS en los libros con referencias cruzadas manteniendo los rangos de selección sincronizados con el libro con referencias cruzadas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-584">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="faf5c-585">Se ha corregido un problema en el que los controles de casilla podían reducirse al usar el autoajuste para ajustar el alto de fila.</span><span class="sxs-lookup"><span data-stu-id="faf5c-585">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>

- <span data-ttu-id="faf5c-586">Problema de rendimiento bajo al hacer clic en el botón Color de fuente cuando un archivo tiene un formato condicional extenso.</span><span class="sxs-lookup"><span data-stu-id="faf5c-586">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="faf5c-587">Se ha corregido un problema por el que el área de impresión en la vista previa de impresión no era correcta.</span><span class="sxs-lookup"><span data-stu-id="faf5c-587">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="faf5c-588">Excel puede tener problemas al editar un archivo protegido desde una red compartida no confiable.</span><span class="sxs-lookup"><span data-stu-id="faf5c-588">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="faf5c-589">Hemos mejorado significativamente el rendimiento del filtrado por color.</span><span class="sxs-lookup"><span data-stu-id="faf5c-589">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="faf5c-590">Se ha resuelto un problema por el que los libros de trabajo creados en versiones anteriores de Office podían hacer que Excel se colgara al abrirlos en las versiones actuales de Office.</span><span class="sxs-lookup"><span data-stu-id="faf5c-590">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="faf5c-591">Se habilitaron más de 16 complementos para que se muestren al navegar en el administrador de complementos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-591">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="faf5c-592">Se ha corregido un problema que impedía que los hipervínculos se pegaran en algunas hojas protegidas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-592">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="faf5c-593">Este cambio evita un problema con ciertos controladores de gráficos Intel al aprovechar el procesamiento del software.</span><span class="sxs-lookup"><span data-stu-id="faf5c-593">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="faf5c-594">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="faf5c-594">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="faf5c-595">Esta actualización corrige un error por el cual los documentos de Office pueden fallar al subirlos a OneDrive para la Empresa con el mensaje "Error al cargar".</span><span class="sxs-lookup"><span data-stu-id="faf5c-595">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="faf5c-596">Corregir problema en la característica Ideas de Excel, error al cargar el complemento haciendo clic en el botón Ideas en el cliente Win32.</span><span class="sxs-lookup"><span data-stu-id="faf5c-596">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span> 

### <a name="onenote"></a><span data-ttu-id="faf5c-597">OneNote</span><span class="sxs-lookup"><span data-stu-id="faf5c-597">OneNote</span></span>

- <span data-ttu-id="faf5c-598">Localiza la notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="faf5c-598">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="faf5c-599">Outlook</span><span class="sxs-lookup"><span data-stu-id="faf5c-599">Outlook</span></span>

- <span data-ttu-id="faf5c-600">Los vínculos de cid:image de los mensajes de Outlook ahora se pueden romper correctamente cuando se solicite.</span><span class="sxs-lookup"><span data-stu-id="faf5c-600">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="faf5c-601">Se ha corregido un problema que causaba que los usuarios que actualizaban su buzón de la autenticación básica a la moderna, terminaban con una cuenta incorrecta asociada a su perfil de Outlook.</span><span class="sxs-lookup"><span data-stu-id="faf5c-601">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="faf5c-602">Se ha corregido un problema que hacía que los complementos web accedieran a los mensajes de la administración de derechos digitales cuando no deberían hacerlo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-602">Addresses an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="faf5c-603">Se ha corregido un problema que causó que las URLS de enlace simple no se mostraran en algunos enlaces seguros.</span><span class="sxs-lookup"><span data-stu-id="faf5c-603">Addresses an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="faf5c-604">Esto actualiza la lógica de bloqueo de adjuntos en Outlook para bloquear también los adjuntos de Python.</span><span class="sxs-lookup"><span data-stu-id="faf5c-604">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="faf5c-605">Corrige un problema que causaba que un subconjunto de usuarios de POP3 viesen todos los correos electrónicos como texto sin formato, independientemente de la configuración.</span><span class="sxs-lookup"><span data-stu-id="faf5c-605">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="faf5c-606">Esta corrección restaurará la vista de los mensajes con formato HTML.</span><span class="sxs-lookup"><span data-stu-id="faf5c-606">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="faf5c-607">Se ha corregido un problema que hacía que los usuarios experimentaran un error de permiso al copiar elementos de su calendario principal a un calendario de grupo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-607">Addresses an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="faf5c-608">Se ha corregido un problema que hacía que los usuarios no pudieran acceder a las sugerencias de ubicación a través de un lector de pantalla.</span><span class="sxs-lookup"><span data-stu-id="faf5c-608">Addresses an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="faf5c-609">Se ha corregido un problema por el que los usuarios notaban un retraso evidente al interactuar con sus carpetas de buzón mediante métodos abreviados de teclado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-609">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="faf5c-610">Se ha corregido un problema que causaba una pérdida de memoria en sesiones de Outlook muy largas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-610">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="faf5c-611">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.</span><span class="sxs-lookup"><span data-stu-id="faf5c-611">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="faf5c-612">Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al abrir el cuadro de diálogo de Reglas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-612">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="faf5c-613">Se ha corregido un problema que haría que los usuarios experimentaran un bloqueo en Outlook al interactuar con ciertos vínculos seguros.</span><span class="sxs-lookup"><span data-stu-id="faf5c-613">Addresses an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="faf5c-614">Se ha corregido un problema que causaba ambigüedad para los administradores sobre si un delegado ya había respondido a una convocatoria de reunión determinada.</span><span class="sxs-lookup"><span data-stu-id="faf5c-614">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="faf5c-615">Se ha corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.</span><span class="sxs-lookup"><span data-stu-id="faf5c-615">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="faf5c-616">Se ha corregido un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "OK" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="faf5c-616">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="faf5c-617">Este cambio permite a los administradores habilitar una política para preferir el correo electrónico de la cuenta proporcionada en los avisos de autorización de AutoDiscover sobre el UPN.</span><span class="sxs-lookup"><span data-stu-id="faf5c-617">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="faf5c-618">De forma predeterminada, detección automática prefiere el UPN de la cuenta, cuando está disponible.</span><span class="sxs-lookup"><span data-stu-id="faf5c-618">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="faf5c-619">Se ha corregido un problema que provocaba que los usuarios vieran un error en la búsqueda con grupos modernos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-619">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="faf5c-620">Se ha corregido un problema que causaba que los usuarios de Outlook se quedaran atascados en el estado "Necesita contraseña" en ciertos escenarios.</span><span class="sxs-lookup"><span data-stu-id="faf5c-620">Addresses an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="faf5c-621">Se ha corregido un problema que provocaba que los usuarios experimentaran errores de sincronización al procesar mensajes de conflicto.</span><span class="sxs-lookup"><span data-stu-id="faf5c-621">Addresses an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="faf5c-622">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al abrir archivos .msg y .oft después de aplicar una actualización reciente de Windows.</span><span class="sxs-lookup"><span data-stu-id="faf5c-622">Addresses an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="faf5c-623">Se ha corregido un problema que provocaba que los usuarios experimentaran un error en la pantalla de "carga del perfil" al iniciar Outlook.</span><span class="sxs-lookup"><span data-stu-id="faf5c-623">Addresses an issue that caused users to experience a hang at the "Loading Profile" screen when Outlook is starting up.</span></span>

- <span data-ttu-id="faf5c-624">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al seleccionar determinados resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="faf5c-624">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="faf5c-625">Se ha corregido un problema que hizo que el botón "Guardar en la nube" faltara en las herramientas de datos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-625">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="faf5c-626">De forma predeterminada, las etiquetas de directivas de retención muestran el período de tiempo de retención entre paréntesis.</span><span class="sxs-lookup"><span data-stu-id="faf5c-626">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="faf5c-627">Esto proporciona una clave del registro para permitir que los administradores especifiquen que solo se debería mostrar el nombre de la directiva.</span><span class="sxs-lookup"><span data-stu-id="faf5c-627">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="faf5c-628">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = predeterminado 1 = solo se mostrará el PolicyName para el texto de la política de retención.</span><span class="sxs-lookup"><span data-stu-id="faf5c-628">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

- <span data-ttu-id="faf5c-629">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al cerrar Outlook.</span><span class="sxs-lookup"><span data-stu-id="faf5c-629">Addresses an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="faf5c-630">Se ha corregido un problema que provocaba que los clientes vieran una lista de salas vacías en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="faf5c-630">Addresses an issue that caused customers to see an empty room list in some scenarios.</span></span>

- <span data-ttu-id="faf5c-631">Se ha corregido un problema que provocaba que los usuarios viesen bloqueos intermitentes al cambiar de vista.</span><span class="sxs-lookup"><span data-stu-id="faf5c-631">Addresses an issue that caused users to see intermittent crashes when changing views.</span></span>

- <span data-ttu-id="faf5c-632">Corrige un problema que provocaba que los usuarios tuvieran problemas al intentar sincronizar carpetas del calendario compartido con el OST, lo que producía errores en los permisos al tratar de interactuar con estas carpetas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-632">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>

- <span data-ttu-id="faf5c-633">Se ha corregido un problema que causaba que los usuarios sufrieran un error al visualizar más de 30 calendarios en un entorno Citrix.</span><span class="sxs-lookup"><span data-stu-id="faf5c-633">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="faf5c-634">Aquí está el [KB individual, donde se ha documentado esto para versiones anteriores](https://support.microsoft.com/es-ES/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span><span class="sxs-lookup"><span data-stu-id="faf5c-634">Here's the individual [KB where this was documented for previous versions](https://support.microsoft.com/es-ES/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span></span>

- <span data-ttu-id="faf5c-635">Corrige un problema con la selección de algoritmos SMIME.</span><span class="sxs-lookup"><span data-stu-id="faf5c-635">Corrects an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="faf5c-636">Se ha corregido un problema que provocó que las sugerencias de la política no se mostraran al utilizar un remitente alternativo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-636">Addresses an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="faf5c-637">Se ha corregido un problema que hizo que los usuarios vieran sugerencias de salas para reuniones que se produjeron fuera de las horas de disponibilidad de dichas salas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-637">Addresses an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="faf5c-638">Se ha corregido un problema para los usuarios que no hablan inglés, en el que la línea de asunto de un correo electrónico era increíblemente pequeña.</span><span class="sxs-lookup"><span data-stu-id="faf5c-638">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="faf5c-639">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al intentar crear una regla a partir de un mensaje de "Conversación perdida".</span><span class="sxs-lookup"><span data-stu-id="faf5c-639">Addresses an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="faf5c-640">Se ha corregido un problema que causaba que algunos usuarios vieran carpetas especiales duplicadas al agregar una cuenta de Exchange secundaria.</span><span class="sxs-lookup"><span data-stu-id="faf5c-640">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="faf5c-641">Se ha corregido un problema que hacía que los usuarios vieran el truncamiento del cuerpo del mensaje al reenviar mensajes HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="faf5c-641">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="faf5c-642">Se ha corregido un problema que hacía que los usuarios observaran una pérdida de memoria en el proceso de Outlook.</span><span class="sxs-lookup"><span data-stu-id="faf5c-642">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="faf5c-643">Se ha corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.</span><span class="sxs-lookup"><span data-stu-id="faf5c-643">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="faf5c-644">Se ha corregido un problema que provocaba un error ocasional en la búsqueda de la carpeta actual.</span><span class="sxs-lookup"><span data-stu-id="faf5c-644">Addresses an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="faf5c-645">Se ha corregido un problema que hizo que algunos usuarios encontraran errores de autenticación al intentar recuperar su configuración de nube para Outlook.</span><span class="sxs-lookup"><span data-stu-id="faf5c-645">Addresses an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="faf5c-646">Se ha corregido un problema que causó un bloqueo en la experiencia de los comentarios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="faf5c-646">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="faf5c-647">Se ha corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.</span><span class="sxs-lookup"><span data-stu-id="faf5c-647">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="faf5c-648">Se ha corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.</span><span class="sxs-lookup"><span data-stu-id="faf5c-648">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="faf5c-649">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="faf5c-649">PowerPoint</span></span>

- <span data-ttu-id="faf5c-650">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="faf5c-650">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="faf5c-651">Este cambio restaura el nombre accesible de los controles de vídeo de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="faf5c-651">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="faf5c-652">Se ha corregido un problema que podría impedir que comiencen algunas animaciones</span><span class="sxs-lookup"><span data-stu-id="faf5c-652">We fixed an issue which could prevent some animations from starting</span></span>

- <span data-ttu-id="faf5c-653">Se ha corregido un problema en el que al copiar una diapositiva de una presentación a otra, se pueden crear patrones duplicados.</span><span class="sxs-lookup"><span data-stu-id="faf5c-653">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span><br>

- <span data-ttu-id="faf5c-654">Se ha mejorado un escenario de copiar y pegar: al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.</span><span class="sxs-lookup"><span data-stu-id="faf5c-654">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="faf5c-655">Se ha corregido un problema con el marcador de resaltado: los textos blancos con un marcador oscuro se imprimen como negros en escala de grises.</span><span class="sxs-lookup"><span data-stu-id="faf5c-655">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

- <span data-ttu-id="faf5c-656">Los archivos con nuevos comentarios modernos mostrarán una advertencia amarilla si se abren en una versión no soportada.</span><span class="sxs-lookup"><span data-stu-id="faf5c-656">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

- <span data-ttu-id="faf5c-657">Se ha corregido un problema que producía un rendimiento más lento entre los usuarios de colaboración.</span><span class="sxs-lookup"><span data-stu-id="faf5c-657">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="faf5c-658">Corrección de confiabilidad: se ha corregido un problema por el que el complemento de terceros podía bloquearse en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="faf5c-658">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="faf5c-659">Se ha corregido un problema que puede producirse cuando un archivo que se abre incrementalmente contiene una diapositiva con más de una secuencia multimedia incrustada.</span><span class="sxs-lookup"><span data-stu-id="faf5c-659">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="faf5c-660">Se ha corregido un problema con el método Shape.Paste: cuando el usuario copiaba y pegaba la forma con el método Shape.Paste, se cambiaba la selección a la forma pegada.</span><span class="sxs-lookup"><span data-stu-id="faf5c-660">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="faf5c-661">Se ha corregido un problema por el que es posible que la barra de mensajes de advertencia de seguridad no aparezca para los complementos en los que no se confía al iniciar PowerPoint por primera vez.</span><span class="sxs-lookup"><span data-stu-id="faf5c-661">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

- <span data-ttu-id="faf5c-662">Se ha corregido un problema por el que algunos complementos producían errores inesperados alrededor de las formas en gráficos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-662">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="faf5c-663">Evita que los usuarios de PowerPoint se encuentren con un error cuando intentan hacer una presentación en línea.</span><span class="sxs-lookup"><span data-stu-id="faf5c-663">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

### <a name="project"></a><span data-ttu-id="faf5c-664">Project</span><span class="sxs-lookup"><span data-stu-id="faf5c-664">Project</span></span>

- <span data-ttu-id="faf5c-665">Se ha corregido un problema para permitir que los usuarios en Windows 7 puedan abrir proyectos desde Project Web App y sitios de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="faf5c-665">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="faf5c-666">Se identificó un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de sólo lectura.</span><span class="sxs-lookup"><span data-stu-id="faf5c-666">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="faf5c-667">El comando Level All no resuelve adecuadamente una sobreasignación de recursos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-667">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="faf5c-668">Si tiene una tarea sin nada de trabajo, es posible que la tarea no se pueda marcar como completada y siempre se mostrará en el 99 %.</span><span class="sxs-lookup"><span data-stu-id="faf5c-668">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

- <span data-ttu-id="faf5c-669">Se ha corregido un problema en el que el trabajo real puede ser diferente entre el parte de horas y el plan del proyecto debido a que los calendarios de recursos no se actualizan cuando cambia el calendario base.</span><span class="sxs-lookup"><span data-stu-id="faf5c-669">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="skype"></a><span data-ttu-id="faf5c-670">Skype</span><span class="sxs-lookup"><span data-stu-id="faf5c-670">Skype</span></span>

- <span data-ttu-id="faf5c-671">Se ha corregido el nombre del título de la conversación con pestañas mientras se mantenía más de una conversación.</span><span class="sxs-lookup"><span data-stu-id="faf5c-671">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="visio"></a><span data-ttu-id="faf5c-672">Visio</span><span class="sxs-lookup"><span data-stu-id="faf5c-672">Visio</span></span>

- <span data-ttu-id="faf5c-673">La exportación como SVG de Visio estaba fallando por una variedad de formas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-673">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="faf5c-674">Word</span><span class="sxs-lookup"><span data-stu-id="faf5c-674">Word</span></span>

- <span data-ttu-id="faf5c-675">Los vínculos de cid:image de los mensajes de Outlook ahora se pueden romper correctamente cuando se solicite.</span><span class="sxs-lookup"><span data-stu-id="faf5c-675">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="faf5c-676">Se ha corregido un problema que podría haber provocado problemas de escala al imprimir en impresoras Deskjet</span><span class="sxs-lookup"><span data-stu-id="faf5c-676">We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span>

- <span data-ttu-id="faf5c-677">Se ha corregido un problema al Ajustar texto en la tabla.</span><span class="sxs-lookup"><span data-stu-id="faf5c-677">We fixed an issue in Fit Text in Table.</span></span>

- <span data-ttu-id="faf5c-678">Hemos corregido un problema en los cambios de pista que a veces van en un bucle infinito.</span><span class="sxs-lookup"><span data-stu-id="faf5c-678">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="faf5c-679">Corregido un problema ocasional en el que al guardar un archivo existente siempre aparece el cuadro de diálogo Guardar como, pero el archivo nunca se guarda.</span><span class="sxs-lookup"><span data-stu-id="faf5c-679">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="faf5c-680">Se ha corregido un problema al combinar dos documentos en uno.</span><span class="sxs-lookup"><span data-stu-id="faf5c-680">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="faf5c-681">Se ha corregido un problema con la característica Comparación para los documentos protegidos para la edición.</span><span class="sxs-lookup"><span data-stu-id="faf5c-681">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="faf5c-682">Se han corregido varios problemas que hacían que la aplicación se colgara al apagarse.</span><span class="sxs-lookup"><span data-stu-id="faf5c-682">Fixes various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="faf5c-683">También se corrigieron ciertos fallos relacionados con los complementos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-683">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="faf5c-684">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="faf5c-684">Office Suite</span></span>

- <span data-ttu-id="faf5c-685">Corregido el problema de la identificación incorrecta del nombre de la nueva era "Reiwa" en hiragana y kanji como una expresión mal escrita o poco gramatical.</span><span class="sxs-lookup"><span data-stu-id="faf5c-685">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="faf5c-686">Corregido un problema que hacía que los usuarios recibieran el mensaje "Lo sentimos, algo nos impide compartir esto" al intentar compartir archivos almacenados en SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="faf5c-686">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="faf5c-687">Se ha solucionado un problema que podía causar la pérdida de datos en sesiones que implicaban tanto la co autoría como la edición fuera de línea en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="faf5c-687">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="faf5c-688">Esta es una solución para un fallo que los usuarios podrían sufrir al abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-688">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="faf5c-689">En algunos casos, un archivo de sharepoint respaldado por un motor de sincronización podría mostrar "Guardado" pero no haber guardado realmente ningún cambio, lo que provocaría la pérdida de datos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-689">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="faf5c-690">Se resolvió un problema que impedía a los usuarios guardar documentos de Word, Excel y PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="faf5c-690">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="faf5c-691">Este problema afecta a los usuarios que crean un nuevo archivo y muestra la opción "Guardar como diálogo" después de hacer clic en el icono Guardar o presionar Ctrl + S.</span><span class="sxs-lookup"><span data-stu-id="faf5c-691">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="faf5c-692">Se ha corregido un bloqueo en Word al dejar una API obsoleta.</span><span class="sxs-lookup"><span data-stu-id="faf5c-692">Fixes a crash in Word by moving away from a deprecated API.</span></span>

- <span data-ttu-id="faf5c-693">Se ha corregido un problema por el que los caracteres katakana de medio ancho no giraban correctamente cuando estaban en cuadros de texto verticales en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="faf5c-693">Fixing an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="faf5c-694">Se ha corregido un problema de perf en Win7 en el que la galería de formas de inserción de la cinta en todas las aplicaciones tardaba aproximadamente 4 segundos en aparecer.</span><span class="sxs-lookup"><span data-stu-id="faf5c-694">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="faf5c-695">Corregido un error por el que la información de accesibilidad no se mostraba en la losa del lugar de información de los bastidores.</span><span class="sxs-lookup"><span data-stu-id="faf5c-695">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="faf5c-696">Mejora de la fiabilidad del proceso de actualización de Office en lo que respecta a la integridad del registro.</span><span class="sxs-lookup"><span data-stu-id="faf5c-696">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="faf5c-697">Hemos actualizado los nombres de canal para las bifurcaciones de enero y julio de 2019 con los nuevos nombres de canal.</span><span class="sxs-lookup"><span data-stu-id="faf5c-697">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="faf5c-698">Se ha corregido un problema por el que las actualizaciones se bloqueaban inesperadamente en las redes de uso medido.</span><span class="sxs-lookup"><span data-stu-id="faf5c-698">Corrects an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="faf5c-699">Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.</span><span class="sxs-lookup"><span data-stu-id="faf5c-699">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="faf5c-700">En determinadas circunstancias, los accesos directos de Office pueden desaparecer tras una actualización.</span><span class="sxs-lookup"><span data-stu-id="faf5c-700">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="faf5c-701">Esta actualización mejora la fiabilidad en la publicación de los accesos directos de Office.</span><span class="sxs-lookup"><span data-stu-id="faf5c-701">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="faf5c-702">Corrige un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.</span><span class="sxs-lookup"><span data-stu-id="faf5c-702">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="faf5c-703">Se ha corregido un problema en el que una actualización no se aplicaría en ciertos casos en los que el usuario no es un administrador y la cuenta del sistema no tenía conectividad de red.</span><span class="sxs-lookup"><span data-stu-id="faf5c-703">Resolves an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="faf5c-704">Se ha solucionado un problema por el que los mensajes de actualización de Office aparecían en un idioma diferente al esperado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-704">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="faf5c-705">En el futuro, los mensajes de actualización de Office coincidirán correctamente con el idioma de visualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="faf5c-705">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="faf5c-706">Se ha mejorado la confiabilidad al descargar las actualizaciones de Office al reanudar las descargas que pueden haberse interrumpido anteriormente.</span><span class="sxs-lookup"><span data-stu-id="faf5c-706">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="faf5c-707">Se han corregido los problemas relacionados con la propiedad Textbox/Shape Autofit en los plug-ins de terceros.</span><span class="sxs-lookup"><span data-stu-id="faf5c-707">Address issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="faf5c-708">Este cambio corrige el procesamiento de imágenes después de abrir un archivo dañado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-708">This change addresses correctly rendering images after opening a corrupted file.</span></span>

- <span data-ttu-id="faf5c-709">Este cambio corrige el procesamiento lento de algunos gráficos de dispersión con marcadores.</span><span class="sxs-lookup"><span data-stu-id="faf5c-709">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="faf5c-710">Se ha corregido un problema por el que las vistas de árboles grandes podían dar lugar a un bloqueo</span><span class="sxs-lookup"><span data-stu-id="faf5c-710">We fixed an issue where large tree views could result in a crash</span></span>

- <span data-ttu-id="faf5c-711">Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.</span><span class="sxs-lookup"><span data-stu-id="faf5c-711">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="faf5c-712">Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="faf5c-712">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="faf5c-713">Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="faf5c-713">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-july-14"></a><span data-ttu-id="faf5c-715">Versión 1902: 14 de julio</span><span class="sxs-lookup"><span data-stu-id="faf5c-715">Version 1902: July 14</span></span>
<span data-ttu-id="faf5c-716">*Versión 1902 (compilación 11328.20624)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-716">*Version 1902 (Build 11328.20624)*</span></span>

<span data-ttu-id="faf5c-717">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-717">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1908-june-09"></a><span data-ttu-id="faf5c-718">Versión 1908: 09 de junio</span><span class="sxs-lookup"><span data-stu-id="faf5c-718">Version 1908: June 09</span></span>
<span data-ttu-id="faf5c-719">*Versión 1908 (compilación 11929.20838)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-719">*Version 1908 (Build 11929.20838)*</span></span>

<span data-ttu-id="faf5c-720">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-720">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-722">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-722">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="faf5c-723">Excel</span><span class="sxs-lookup"><span data-stu-id="faf5c-723">Excel</span></span>

- <span data-ttu-id="faf5c-724">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="faf5c-724">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="faf5c-725">Se ha corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.</span><span class="sxs-lookup"><span data-stu-id="faf5c-725">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="faf5c-726">Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-726">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="faf5c-727">Outlook</span><span class="sxs-lookup"><span data-stu-id="faf5c-727">Outlook</span></span>

- <span data-ttu-id="faf5c-728">Se ha corregido un problema que hacía que los usuarios vieran truncado el cuerpo del mensaje al reenviar mensajes HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="faf5c-728">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

### <a name="office-suite"></a><span data-ttu-id="faf5c-729">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="faf5c-729">Office Suite</span></span>

- <span data-ttu-id="faf5c-730">Hemos actualizado los nombres de canal para las bifurcaciones de enero y julio de 2019 con los nuevos nombres de canal.</span><span class="sxs-lookup"><span data-stu-id="faf5c-730">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>


[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-june-09"></a><span data-ttu-id="faf5c-732">Versión 1902: 09 de junio</span><span class="sxs-lookup"><span data-stu-id="faf5c-732">Version 1902: June 09</span></span>
<span data-ttu-id="faf5c-733">*Versión 1902 (compilación 11328.20602)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-733">*Version 1902 (Build 11328.20602)*</span></span>

<span data-ttu-id="faf5c-734">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-734">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-736">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-736">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="faf5c-737">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="faf5c-737">Office Suite</span></span>

- <span data-ttu-id="faf5c-738">Hemos actualizado los nombres de canal para las bifurcaciones de enero y julio de 2019 con los nuevos nombres de canal.</span><span class="sxs-lookup"><span data-stu-id="faf5c-738">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="faf5c-739">Se han eliminado las referencias obsoletas de los archivos de línea base que producian errores en la compilación C2R.</span><span class="sxs-lookup"><span data-stu-id="faf5c-739">We removed obsolete references from the baseline files that were breaking the C2R Build.</span></span>



[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-may-12"></a><span data-ttu-id="faf5c-741">Versión 1908: 12 de mayo</span><span class="sxs-lookup"><span data-stu-id="faf5c-741">Version 1908: May 12</span></span>
<span data-ttu-id="faf5c-742">*Versión 1908 (compilación 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-742">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="faf5c-743">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-743">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-745">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-745">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="faf5c-746">Excel</span><span class="sxs-lookup"><span data-stu-id="faf5c-746">Excel</span></span>

- <span data-ttu-id="faf5c-747">Cuando se copian datos filtrados por colores en una columna con un ancho diferente, los valores no se pegan.</span><span class="sxs-lookup"><span data-stu-id="faf5c-747">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

### <a name="outlook"></a><span data-ttu-id="faf5c-748">Outlook</span><span class="sxs-lookup"><span data-stu-id="faf5c-748">Outlook</span></span>

- <span data-ttu-id="faf5c-749">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al abrir archivos .msg y .oft después de aplicar una actualización reciente de Windows.</span><span class="sxs-lookup"><span data-stu-id="faf5c-749">Addressed an issue that caused users to experience a crash when opening msg and .oft files after applying a recent Windows update.</span></span>

### <a name="word"></a><span data-ttu-id="faf5c-750">Word</span><span class="sxs-lookup"><span data-stu-id="faf5c-750">Word</span></span>

- <span data-ttu-id="faf5c-751">Se ha corregido un problema al combinar 2 documentos en uno.</span><span class="sxs-lookup"><span data-stu-id="faf5c-751">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="faf5c-752">Se ha corregido un problema con la característica Comparar de los documentos protegidos para la edición.</span><span class="sxs-lookup"><span data-stu-id="faf5c-752">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-1902-may-12"></a><span data-ttu-id="faf5c-754">Versión 1902:12 de mayo</span><span class="sxs-lookup"><span data-stu-id="faf5c-754">Version 1902: May 12</span></span>
<span data-ttu-id="faf5c-755">*Versión 1902 (compilación 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-755">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="faf5c-756">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-756">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-758">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-758">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="faf5c-759">Outlook</span><span class="sxs-lookup"><span data-stu-id="faf5c-759">Outlook</span></span>

- <span data-ttu-id="faf5c-760">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al abrir archivos .msg y .oft después de aplicar una actualización reciente de Windows.</span><span class="sxs-lookup"><span data-stu-id="faf5c-760">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="faf5c-761">De forma predeterminada, las etiquetas de directivas de retención muestran el período de tiempo de retención entre paréntesis.</span><span class="sxs-lookup"><span data-stu-id="faf5c-761">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="faf5c-762">Esto proporciona una clave del registro para permitir que los administradores especifiquen que solo se debería mostrar el nombre de la directiva.</span><span class="sxs-lookup"><span data-stu-id="faf5c-762">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="faf5c-763">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="faf5c-763">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="faf5c-764">0 = predeterminado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-764">0 = Default.</span></span>  <span data-ttu-id="faf5c-765">1 = solo se mostrará el nombre de directiva del texto de la directiva de retención.</span><span class="sxs-lookup"><span data-stu-id="faf5c-765">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-1908-may-04"></a><span data-ttu-id="faf5c-767">Versión 1908: 4 de mayo</span><span class="sxs-lookup"><span data-stu-id="faf5c-767">Version 1908: May 04</span></span>
<span data-ttu-id="faf5c-768">*Versión 1908 (Compilación 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-768">*Version 1908 (Build 11929.20752)*</span></span>

<span data-ttu-id="faf5c-769">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-769">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-770">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-770">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="faf5c-771">Outlook</span><span class="sxs-lookup"><span data-stu-id="faf5c-771">Outlook</span></span>

- <span data-ttu-id="faf5c-772">Corregido un problema que provocaba que los usuarios experimentaran un bloqueo al seleccionar determinados resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="faf5c-772">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="faf5c-773">Se ha corregido un problema que hacía que el botón "Guardar en la nube" faltara en las Herramientas de datos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-773">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="faf5c-774">De forma predeterminada, las etiquetas de directivas de retención muestran el período de tiempo de retención entre paréntesis.</span><span class="sxs-lookup"><span data-stu-id="faf5c-774">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="faf5c-775">Esto proporciona una clave del registro para permitir que los administradores especifiquen que solo se debería mostrar el nombre de la directiva.</span><span class="sxs-lookup"><span data-stu-id="faf5c-775">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="faf5c-776">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="faf5c-776">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="faf5c-777">0 = predeterminado 1 = solo se mostrará el nombre de directiva del texto de la directiva de retención.</span><span class="sxs-lookup"><span data-stu-id="faf5c-777">0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="office-suite"></a><span data-ttu-id="faf5c-778">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="faf5c-778">Office Suite</span></span>

- <span data-ttu-id="faf5c-779">Se ha corregido un problema en Visual Basic para las aplicaciones de Microsoft Office, por el que la aplicación de Office consideraba como corruptos ciertos proyectos de VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre o la ruta de la biblioteca.</span><span class="sxs-lookup"><span data-stu-id="faf5c-779">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="faf5c-780">Versión 1902: 4 de mayo</span><span class="sxs-lookup"><span data-stu-id="faf5c-780">Version 1902: May 04</span></span>
<span data-ttu-id="faf5c-781">*Versión 1902 (compilación 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-781">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-782">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-782">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="faf5c-783">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="faf5c-783">Office Suite</span></span>

- <span data-ttu-id="faf5c-784">Se ha corregido un problema en VBA de Microsoft Office, por el que la aplicación de Office consideraba como corruptos ciertos proyectos de VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre o la ruta de la biblioteca.</span><span class="sxs-lookup"><span data-stu-id="faf5c-784">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1908-april-26"></a><span data-ttu-id="faf5c-785">Versión 1908: 26 de abril</span><span class="sxs-lookup"><span data-stu-id="faf5c-785">Version 1908: April 26</span></span>
<span data-ttu-id="faf5c-786">*Versión 1908 (Compilación 11929.20736)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-786">*Version 1908 (Build 11929.20736)*</span></span>

<span data-ttu-id="faf5c-787">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-787">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-788">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-788">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="faf5c-789">Excel</span><span class="sxs-lookup"><span data-stu-id="faf5c-789">Excel</span></span>

- <span data-ttu-id="faf5c-790">Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al usar una macro de VBA para borrar el contenido de un rango.</span><span class="sxs-lookup"><span data-stu-id="faf5c-790">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="faf5c-791">Se ha corregido un problema con VBA por el que escribir valores en un rango era más lento de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-791">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="faf5c-792">Se ha corregido un problema por el que la propiedad "Value Crosses At" en el eje del gráfico cambiaba inesperadamente al guardar y volver a abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-792">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="faf5c-793">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="faf5c-793">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


### <a name="onenote"></a><span data-ttu-id="faf5c-794">OneNote</span><span class="sxs-lookup"><span data-stu-id="faf5c-794">OneNote</span></span>

- <span data-ttu-id="faf5c-795">Localiza la notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="faf5c-795">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>


## <a name="version-1908-april-14"></a><span data-ttu-id="faf5c-796">Versión 1908: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="faf5c-796">Version 1908: April 14</span></span>
<span data-ttu-id="faf5c-797">*Versión 1908 (compilación 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-797">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="faf5c-798">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-798">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-800">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-800">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="faf5c-801">Excel</span><span class="sxs-lookup"><span data-stu-id="faf5c-801">Excel</span></span>

- <span data-ttu-id="faf5c-802">Se ha corregido un problema que provocaba un rendimiento lento al eliminar columnas que contenían celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-802">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="faf5c-803">Se ha corregido un problema con la escala de texto en los controles de formulario cuando se mostraba la Vista previa de impresión.</span><span class="sxs-lookup"><span data-stu-id="faf5c-803">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="faf5c-804">Skype</span><span class="sxs-lookup"><span data-stu-id="faf5c-804">Skype</span></span>

- <span data-ttu-id="faf5c-805">Se ha corregido el nombre del título de la conversación con pestañas mientras se mantenía más de una conversación.</span><span class="sxs-lookup"><span data-stu-id="faf5c-805">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="faf5c-806">Outlook</span><span class="sxs-lookup"><span data-stu-id="faf5c-806">Outlook</span></span>

- <span data-ttu-id="faf5c-807">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al cerrar Outlook.</span><span class="sxs-lookup"><span data-stu-id="faf5c-807">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="faf5c-808">Se ha corregido un problema que provocaba que los clientes vieran una lista de salas vacías en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="faf5c-808">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="faf5c-809">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="faf5c-809">PowerPoint</span></span>

- <span data-ttu-id="faf5c-810">Se ha corregido un problema con el marcador de resaltado: los textos blancos con un marcador oscuro se imprimen como negros en escala de grises.</span><span class="sxs-lookup"><span data-stu-id="faf5c-810">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="faf5c-811">Word</span><span class="sxs-lookup"><span data-stu-id="faf5c-811">Word</span></span>

- <span data-ttu-id="faf5c-812">Se ha corregido un problema al Ajustar texto en la tabla.</span><span class="sxs-lookup"><span data-stu-id="faf5c-812">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="faf5c-813">Versión 1902: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="faf5c-813">Version 1902: April 14</span></span>
<span data-ttu-id="faf5c-814">*Versión 1902 (compilación 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-814">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="faf5c-815">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-815">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-march-10"></a><span data-ttu-id="faf5c-817">Versión 1908: 10 de marzo</span><span class="sxs-lookup"><span data-stu-id="faf5c-817">Version 1908: March 10</span></span>
<span data-ttu-id="faf5c-818">*Versión 1908 (compilación 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-818">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="faf5c-819">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-819">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-821">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-821">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="faf5c-822">Excel</span><span class="sxs-lookup"><span data-stu-id="faf5c-822">Excel</span></span>

- <span data-ttu-id="faf5c-823">Se ha corregido un problema por el que algunos usuarios podían haber experimentado múltiples ventanas emergentes cuando los enlaces externos estaban presentes en el libro de trabajo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-823">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="faf5c-824">La funcionalidad de Texto a columna puede fallar en algunas configuraciones regionales.</span><span class="sxs-lookup"><span data-stu-id="faf5c-824">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="faf5c-825">Los usuarios pueden encontrar un error al acceder a un rango con nombre oculto.</span><span class="sxs-lookup"><span data-stu-id="faf5c-825">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="faf5c-826">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="faf5c-826">PowerPoint</span></span>

- <span data-ttu-id="faf5c-827">Se ha corregido un problema con el método Shape.Paste: cuando el usuario copiaba y pegaba la forma con el método Shape.Paste, se cambiaba la selección a la forma pegada.</span><span class="sxs-lookup"><span data-stu-id="faf5c-827">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="faf5c-828">Word</span><span class="sxs-lookup"><span data-stu-id="faf5c-828">Word</span></span>

- <span data-ttu-id="faf5c-829">Corregido un problema ocasional en el que al guardar un archivo existente siempre aparece el cuadro de diálogo Guardar como, pero el archivo nunca se guarda.</span><span class="sxs-lookup"><span data-stu-id="faf5c-829">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="faf5c-830">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="faf5c-830">Office Suite</span></span>

- <span data-ttu-id="faf5c-831">Este cambio corrige el procesamiento lento de algunos gráficos de dispersión con marcadores.</span><span class="sxs-lookup"><span data-stu-id="faf5c-831">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="faf5c-832">Versión 1902: 10 de marzo</span><span class="sxs-lookup"><span data-stu-id="faf5c-832">Version 1902: March 10</span></span>
<span data-ttu-id="faf5c-833">*Versión 1902 (compilación 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-833">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="faf5c-834">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-834">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-february-11"></a><span data-ttu-id="faf5c-836">Versión 1908: 11 de febrero</span><span class="sxs-lookup"><span data-stu-id="faf5c-836">Version 1908: February 11</span></span>
<span data-ttu-id="faf5c-837">*Versión 1908 (Compilación 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-837">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="faf5c-838">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-838">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-840">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-840">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="faf5c-841">Excel</span><span class="sxs-lookup"><span data-stu-id="faf5c-841">Excel</span></span>

- <span data-ttu-id="faf5c-842">Esta actualización corrige un problema que provoca un error siempre que se utilizaba VBA para agregar una imagen al encabezado o pie de página de un gráfico.</span><span class="sxs-lookup"><span data-stu-id="faf5c-842">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="faf5c-843">Se ha corregido un problema que hacía que el borde de un control de cuadro de grupo no estuviera visible en la vista previa de impresión o al imprimirlo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-843">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="faf5c-844">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="faf5c-844">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="faf5c-845">Se ha corregido un problema por el que el tamaño de archivo de las imágenes en los encabezados del gráfico aumentaba cuando se guardaba el libro que contenía el gráfico.</span><span class="sxs-lookup"><span data-stu-id="faf5c-845">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="faf5c-846">Se ha corregido un problema que provoca la corrupción de caracteres DBCS en los libros con referencias cruzadas manteniendo los rangos de selección sincronizados con el libro con referencias cruzadas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-846">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="faf5c-847">Se ha corregido un problema en el que los controles de casilla podían reducirse al usar el autoajuste para ajustar el alto de fila.</span><span class="sxs-lookup"><span data-stu-id="faf5c-847">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="faf5c-848">Outlook</span><span class="sxs-lookup"><span data-stu-id="faf5c-848">Outlook</span></span>

- <span data-ttu-id="faf5c-849">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.</span><span class="sxs-lookup"><span data-stu-id="faf5c-849">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="faf5c-850">Se ha corregido un problema que provocaba que los usuarios experimentaran errores de sincronización al procesar mensajes de conflicto.</span><span class="sxs-lookup"><span data-stu-id="faf5c-850">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="faf5c-851">Se ha corregido un problema que provocaba que los usuarios experimentaran un error en la pantalla de carga del perfil al iniciar Outlook.</span><span class="sxs-lookup"><span data-stu-id="faf5c-851">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="faf5c-852">Se ha corregido un problema que provocaba que los usuarios viesen bloqueos intermitentes al cambiar de vista.</span><span class="sxs-lookup"><span data-stu-id="faf5c-852">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="faf5c-853">Se ha corregido un problema que causaba que los usuarios sufrieran un error al visualizar más de 30 calendarios en un entorno Citrix.</span><span class="sxs-lookup"><span data-stu-id="faf5c-853">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="faf5c-854">[Aquí](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) está la KB individual, donde se ha documentado esto para versiones anteriores.</span><span class="sxs-lookup"><span data-stu-id="faf5c-854">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="faf5c-855">Corrige un problema que provocaba que los usuarios tuvieran problemas al intentar sincronizar carpetas del calendario compartido con el OST, lo que producía errores en los permisos al tratar de interactuar con estas carpetas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-855">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="faf5c-856">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="faf5c-856">PowerPoint</span></span>

- <span data-ttu-id="faf5c-857">Se ha mejorado un escenario de copiar y pegar. Al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.</span><span class="sxs-lookup"><span data-stu-id="faf5c-857">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="faf5c-858">Se ha corregido un problema que producía un rendimiento más lento entre los usuarios de colaboración.</span><span class="sxs-lookup"><span data-stu-id="faf5c-858">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="faf5c-859">Se ha corregido un problema que puede producirse cuando un archivo que se abre incrementalmente contiene una diapositiva con más de una secuencia multimedia incrustada.</span><span class="sxs-lookup"><span data-stu-id="faf5c-859">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="faf5c-860">Se ha corregido un problema por el que es posible que la barra de mensajes de advertencia de seguridad no aparezca para los complementos en los que no se confía al iniciar PowerPoint por primera vez.</span><span class="sxs-lookup"><span data-stu-id="faf5c-860">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="faf5c-861">Project</span><span class="sxs-lookup"><span data-stu-id="faf5c-861">Project</span></span>

- <span data-ttu-id="faf5c-862">Se ha corregido un problema en el que el trabajo real puede ser diferente entre el parte de horas y el plan del proyecto debido a que los calendarios de recursos no se actualizan cuando cambia el calendario base.</span><span class="sxs-lookup"><span data-stu-id="faf5c-862">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="faf5c-863">Word</span><span class="sxs-lookup"><span data-stu-id="faf5c-863">Word</span></span>

- <span data-ttu-id="faf5c-864">Se ha corregido un bloqueo en Word al dejar una API obsoleta.</span><span class="sxs-lookup"><span data-stu-id="faf5c-864">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="faf5c-865">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="faf5c-865">Office Suite</span></span>

- <span data-ttu-id="faf5c-866">Este cambio corrige el procesamiento de imágenes después de abrir un archivo dañado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-866">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-february-11"></a><span data-ttu-id="faf5c-868">Versión 1902: 11 de febrero</span><span class="sxs-lookup"><span data-stu-id="faf5c-868">Version 1902: February 11</span></span>
<span data-ttu-id="faf5c-869">*Versión 1902 (Compilación 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-869">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="faf5c-870">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-870">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-872">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-872">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="faf5c-873">Outlook</span><span class="sxs-lookup"><span data-stu-id="faf5c-873">Outlook</span></span>

- <span data-ttu-id="faf5c-874">Corregido un problema que hizo que los usuarios encontraran errores de "algoritmo de cifrado no admitido" al enviar un correo electrónico cifrado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-874">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="faf5c-875">Word</span><span class="sxs-lookup"><span data-stu-id="faf5c-875">Word</span></span>

- <span data-ttu-id="faf5c-876">Se ha corregido un bloqueo en Word al dejar una API obsoleta.</span><span class="sxs-lookup"><span data-stu-id="faf5c-876">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO INICIO)

## <a name="version-1808-february-11"></a><span data-ttu-id="faf5c-879">Versión 1808: 11 de febrero</span><span class="sxs-lookup"><span data-stu-id="faf5c-879">Version 1808: February 11</span></span>
<span data-ttu-id="faf5c-880">*Versión 1808 (compilación 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-880">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="faf5c-881">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-881">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-january-14"></a><span data-ttu-id="faf5c-883">Versión 1908: 14 de enero</span><span class="sxs-lookup"><span data-stu-id="faf5c-883">Version 1908: January 14</span></span>
<span data-ttu-id="faf5c-884">*Versión 1908 (compilación 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-884">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="faf5c-885">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-885">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="faf5c-887">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="faf5c-887">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="faf5c-888">Access</span><span class="sxs-lookup"><span data-stu-id="faf5c-888">Access</span></span>

- <span data-ttu-id="faf5c-889">**Mantener un seguimiento de los objetos de base de datos:** ver claramente la pestaña activa, arrastrar las pestañas para reorganizarlas fácilmente y cerrar los objetos de base de datos con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="faf5c-889">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="faf5c-890">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="faf5c-890">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="faf5c-891">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="faf5c-891">Switching between them has never been easier.</span></span> [<span data-ttu-id="faf5c-892">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-892">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="faf5c-893">**Zoom con más espacio:** agrandar el cuadro de Zoom, cambiar la fuente y hacer que Zoom lo recuerde todo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-893">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="faf5c-894">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-894">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="faf5c-895">Excel</span><span class="sxs-lookup"><span data-stu-id="faf5c-895">Excel</span></span>

- <span data-ttu-id="faf5c-896">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="faf5c-896">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="faf5c-897">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="faf5c-897">Switching between them has never been easier.</span></span> [<span data-ttu-id="faf5c-898">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-898">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="faf5c-899">**Aumentar el alcance de su contenido:** ¿necesita que las presentaciones sean accesibles?</span><span class="sxs-lookup"><span data-stu-id="faf5c-899">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="faf5c-900">Deje que el comprobador de accesibilidad le ayude sin estorbar.</span><span class="sxs-lookup"><span data-stu-id="faf5c-900">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="faf5c-901">Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-901">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="faf5c-902">**Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente?</span><span class="sxs-lookup"><span data-stu-id="faf5c-902">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="faf5c-903">Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.</span><span class="sxs-lookup"><span data-stu-id="faf5c-903">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="faf5c-904">**Vea cómo la hoja de cálculo cobra vida**: inserte gráficos 3D animados para ver corazones que laten, planetas en órbita y dinosaurios a toda velocidad por el libro.</span><span class="sxs-lookup"><span data-stu-id="faf5c-904">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="faf5c-905">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-905">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="faf5c-p175">**Obtener más información sobre los datos:** el nuevo botón Ideas busca patrones en los datos y los usa para crear sugerencias inteligentes y personalizadas. [Más información](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="faf5c-p175">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="faf5c-908">**La colaboración es ahora más fácil**: las mejoras en la coautoría significan que al trabajar con el formato condicional, los estilos de celda y otros elementos, los cambios se combinan perfectamente con los de los colaboradores.</span><span class="sxs-lookup"><span data-stu-id="faf5c-908">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="faf5c-909">**Unir tablas en columnas similares:** obtener y transformar (Power Query) ahora ofrece una lógica de coincidencia de texto (también denominada coincidencia aproximada) al comparar columnas en la combinación de tablas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-909">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="faf5c-910">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-910">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="faf5c-911">**Programar rápidamente con mejoras de Power Query:** termine rápidamente el código con colores de sintaxis y la función de autocompletar.</span><span class="sxs-lookup"><span data-stu-id="faf5c-911">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="faf5c-912">Además, descubra fácilmente funciones, columnas y parámetros.</span><span class="sxs-lookup"><span data-stu-id="faf5c-912">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="faf5c-913">**Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea.</span><span class="sxs-lookup"><span data-stu-id="faf5c-913">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="faf5c-914">Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.</span><span class="sxs-lookup"><span data-stu-id="faf5c-914">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="faf5c-915">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-915">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="faf5c-916">Outlook</span><span class="sxs-lookup"><span data-stu-id="faf5c-916">Outlook</span></span>

- <span data-ttu-id="faf5c-917">**Hemos actualizado la experiencia de usuario de Outlook para usted:** una experiencia simplificada, anteriormente disponible para su vista previa con Próximamente, diseñada para ayudarle a centrarse en lo más importante.</span><span class="sxs-lookup"><span data-stu-id="faf5c-917">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="faf5c-918">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-918">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="faf5c-919">**Una cinta simplificada que además es personalizable:** disfrute de una sola fila simplificada con los botones más usados.</span><span class="sxs-lookup"><span data-stu-id="faf5c-919">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="faf5c-920">Cambie fácilmente entre la vista clásica y la simplificada, y ancle o desancle comandos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-920">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="faf5c-921">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-921">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="faf5c-922">**Seguir trabajando mientras mueve mensajes:** Outlook ahora mueve los mensajes en segundo plano, por lo que puede seguir trabajando mientras mueve una gran cantidad de mensajes entre carpetas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-922">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="faf5c-923">**Creación en el tiempo entre las reuniones consecutivas:** asigne a los asistentes el tiempo para descansar o desplazarse entre las distintas ubicaciones al configurar reuniones para finalizar 5 a 10 minutos antes de forma predeterminada.</span><span class="sxs-lookup"><span data-stu-id="faf5c-923">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="faf5c-924">**Seleccione su acción favorita:** ¿no usa Etiquetar ni Eliminar?</span><span class="sxs-lookup"><span data-stu-id="faf5c-924">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="faf5c-925">¿Qué hay de Archivar o Marcar como leído?</span><span class="sxs-lookup"><span data-stu-id="faf5c-925">How about Archive or Mark as Read?</span></span> <span data-ttu-id="faf5c-926">Personalice el menú de acciones rápidas con los comandos que use más frecuentemente.</span><span class="sxs-lookup"><span data-stu-id="faf5c-926">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="faf5c-p182">**Verán los memes que comparta:** cuando un texto o imágenes estáticas no consigan comunicar lo que desea, use un GIF animado para aclararlo. [Más información](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="faf5c-p182">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="faf5c-929">**Una forma más rápida de agregar cuentas:** gracias a las mejoras de configuración de cuentas, es más fácil que nunca agregar cuentas de Outlook.com y Gmail que usen la autenticación en dos fases a Outlook.</span><span class="sxs-lookup"><span data-stu-id="faf5c-929">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="faf5c-930">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-930">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="faf5c-931">**Despídase de límites de sincronización:** las mejoras de Outlook significan que se ha eliminado el límite de carpetas y sincronizar los buzones compartidos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-931">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="faf5c-932">**Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea.</span><span class="sxs-lookup"><span data-stu-id="faf5c-932">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="faf5c-933">Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.</span><span class="sxs-lookup"><span data-stu-id="faf5c-933">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="faf5c-934">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-934">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="faf5c-935">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="faf5c-935">PowerPoint</span></span>

- <span data-ttu-id="faf5c-936">**Mejor transformación:** asigne un nombre a las formas para tener más control sobre cómo se transforman.</span><span class="sxs-lookup"><span data-stu-id="faf5c-936">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="faf5c-937">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-937">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="faf5c-938">**Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente?</span><span class="sxs-lookup"><span data-stu-id="faf5c-938">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="faf5c-939">Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.</span><span class="sxs-lookup"><span data-stu-id="faf5c-939">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="faf5c-940">**Aumentar el alcance de su contenido:** ¿necesita que las presentaciones sean accesibles?</span><span class="sxs-lookup"><span data-stu-id="faf5c-940">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="faf5c-941">Deje que el comprobador de accesibilidad le ayude sin estorbar.</span><span class="sxs-lookup"><span data-stu-id="faf5c-941">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="faf5c-942">Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-942">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="faf5c-943">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="faf5c-943">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="faf5c-944">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="faf5c-944">Switching between them has never been easier.</span></span> [<span data-ttu-id="faf5c-945">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-945">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="faf5c-946">**Los vídeos en línea tienen un nuevo hogar:** guarde un vídeo en Microsoft Stream para que puedan verlo todas las personas de su organización.</span><span class="sxs-lookup"><span data-stu-id="faf5c-946">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="faf5c-947">Inserte el vínculo del vídeo y disfrute de una presentación multimedia en una fracción del tamaño del archivo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-947">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="faf5c-948">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-948">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="faf5c-949">**Guardar los cambios a medida que los realiza:** cargue el archivo en OneDrive para asegurarse de que todas las actualizaciones se guardan automáticamente.</span><span class="sxs-lookup"><span data-stu-id="faf5c-949">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="faf5c-p190">**Pregunte a su público con un cuestionario o una encuesta:** coloque un cuestionario o una encuesta en una diapositiva. Office recopila y almacena las respuestas para usted. [Más información](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="faf5c-p190">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="faf5c-p191">**Nunca fue tan fácil insertar un vídeo en línea:** ¿quiere poner un vídeo de Vimeo o de YouTube en la diapositiva? Solo necesita el vínculo a la página del vídeo. [Más información](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="faf5c-p191">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="faf5c-956">**Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea.</span><span class="sxs-lookup"><span data-stu-id="faf5c-956">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="faf5c-957">Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.</span><span class="sxs-lookup"><span data-stu-id="faf5c-957">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="faf5c-958">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-958">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="faf5c-959">Project</span><span class="sxs-lookup"><span data-stu-id="faf5c-959">Project</span></span>

- <span data-ttu-id="faf5c-960">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="faf5c-960">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="faf5c-961">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="faf5c-961">Switching between them has never been easier.</span></span> [<span data-ttu-id="faf5c-962">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-962">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="faf5c-963">Visio</span><span class="sxs-lookup"><span data-stu-id="faf5c-963">Visio</span></span>

- <span data-ttu-id="faf5c-964">**Exportar diagramas de proceso a Word:** Agregue automáticamente contenido del diagrama, como formas y metadatos, a un documento de Word.</span><span class="sxs-lookup"><span data-stu-id="faf5c-964">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="faf5c-965">Después, personalice el documento para crear instrucciones de procesos y manuales de funcionamiento.</span><span class="sxs-lookup"><span data-stu-id="faf5c-965">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="faf5c-966">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-966">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="faf5c-967">**Doble toma en diagramas de flujo de datos:** Los magníficos nuevos diseños para los diagramas de flujo del visualizador de datos son limpios, nítidos y fáciles de entender.</span><span class="sxs-lookup"><span data-stu-id="faf5c-967">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="faf5c-968">Haga clic en la pestaña Diseño para ver las opciones.</span><span class="sxs-lookup"><span data-stu-id="faf5c-968">Click the Design tab for options.</span></span>

- <span data-ttu-id="faf5c-969">**Galerías de símbolos integradas en Azure:** diseñe una aplicación de nube o planee una arquitectura con las múltiples galerías de símbolos de Azure.</span><span class="sxs-lookup"><span data-stu-id="faf5c-969">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="faf5c-970">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-970">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="faf5c-p197">**Adiós a los vínculos rotos de Excel:** ¿no encuentra el libro de Excel vinculado a un diagrama de visualizador de datos? Solo tiene que vincularlo de nuevo y ¡listo! [Más información](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="faf5c-p197">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="faf5c-974">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="faf5c-974">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="faf5c-975">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="faf5c-975">Switching between them has never been easier.</span></span> [<span data-ttu-id="faf5c-976">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-976">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="faf5c-977">**Exportar objetos visuales de Visio desde Power BI**: los objetos visuales de Visio para Power BI ahora se mostrarán correctamente al exportar informes de Power BI como archivos PDF, archivos de PowerPoint, etc.</span><span class="sxs-lookup"><span data-stu-id="faf5c-977">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="faf5c-978">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-978">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="faf5c-979">Word</span><span class="sxs-lookup"><span data-stu-id="faf5c-979">Word</span></span>

- <span data-ttu-id="faf5c-980">**El modo herramientas de aprendizaje tiene soporte adicional para más colores de página:** las herramientas de aprendizaje de Word son compatibles con más colores de tema de página, lo que permite cambiar el color de fondo de la página.</span><span class="sxs-lookup"><span data-stu-id="faf5c-980">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="faf5c-981">Muchas personas tienen dificultades para leer con un fondo totalmente blanco o negro, por lo que hemos ampliado la elección de colores en Word para PC y Mac.</span><span class="sxs-lookup"><span data-stu-id="faf5c-981">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="faf5c-p201">**Edición natural con el Editor para entradas de lápiz:** con un solo trazo, divida o una palabras, agregue una nueva línea o inserte palabras con el lápiz. [Más información](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="faf5c-p201">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="faf5c-p202">**Su documento: de estático a mágico:** transforme el documento en una página web interactiva y fácil de compartir con un aspecto fantástico en cualquier dispositivo. [Más información](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="faf5c-p202">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="faf5c-986">**Aumentar el alcance de su contenido:** ¿necesita hacer que sus documentos sean accesibles?</span><span class="sxs-lookup"><span data-stu-id="faf5c-986">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="faf5c-987">Deje que el comprobador de accesibilidad le ayude sin estorbar.</span><span class="sxs-lookup"><span data-stu-id="faf5c-987">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="faf5c-988">Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-988">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="faf5c-989">**Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente?</span><span class="sxs-lookup"><span data-stu-id="faf5c-989">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="faf5c-990">Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.</span><span class="sxs-lookup"><span data-stu-id="faf5c-990">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="faf5c-991">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="faf5c-991">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="faf5c-992">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="faf5c-992">Switching between them has never been easier.</span></span> [<span data-ttu-id="faf5c-993">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-993">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="faf5c-p206">**Mejorar la comprensión con el foco de línea:** desplácese por un documento línea por línea sin distracciones. Ajuste el foco para ver una, tres o cinco líneas a la vista. [Más información](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="faf5c-p206">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="faf5c-997">**Guarde sus cambios a medida que se produzcan:** Suba su archivo a OneDrive para asegurarse de que todas sus actualizaciones se guarden automáticamente.</span><span class="sxs-lookup"><span data-stu-id="faf5c-997">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="faf5c-998">**Consiga su atención con\@menciones:** use @menciones en los comentarios para avisar a los compañeros de trabajo cuando necesite su participación.</span><span class="sxs-lookup"><span data-stu-id="faf5c-998">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="faf5c-999">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-999">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="faf5c-1000">**Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1000">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="faf5c-1001">Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1001">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="faf5c-1002">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-1002">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="faf5c-1003">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="faf5c-1003">Office Suite</span></span>

- <span data-ttu-id="faf5c-1004">**Encuentra ese archivo rápido:** ¿Busca un archivo en el que haya trabajado recientemente?</span><span class="sxs-lookup"><span data-stu-id="faf5c-1004">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="faf5c-1005">Sólo tiene que escribir en el cuadro de búsqueda de la pestaña Archivo > Abrir para encontrar el archivo que está buscando.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1005">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="faf5c-1006">**Guardar los cambios a medida que los realiza:** cargue el archivo en OneDrive para asegurarse de que todas las actualizaciones se guardan automáticamente.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1006">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="faf5c-1007">**Controles de privacidad:** nuevos controles para datos de diagnóstico y experiencias conectadas, actualizados y mejorados.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1007">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="faf5c-1008">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-1008">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="faf5c-1009">**Los iconos de Office tienen un nuevo aspecto:** los iconos de Office se han rediseñado para reflejar las sencillas, inteligentes y eficaces experiencias de Office.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1009">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="faf5c-1010">**Instalación de Microsoft Teams:** Microsoft Teams se instala de forma predeterminada en las instalaciones existentes de Office 365 ProPlus.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1010">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="faf5c-1011">Más información</span><span class="sxs-lookup"><span data-stu-id="faf5c-1011">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-1014">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-1014">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="faf5c-1015">Access</span><span class="sxs-lookup"><span data-stu-id="faf5c-1015">Access</span></span>

- <span data-ttu-id="faf5c-1016">Esta actualización corrige un problema en el que la agregación como la suma puede truncar el resultado a un valor entero.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1016">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="faf5c-1017">Esta actualización corrige un problema por el que una consulta de Unión que incluye referencias a tablas remotas (por ejemplo, tablas de SQL Server) puede hacer que Access se cierre y se reinicie.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1017">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="faf5c-1018">Esta actualización corrige un problema en Microsoft Access que puede causar el error &quot;La consulta está dañada&quot; cuando se ejecuta una consulta de actualización o cuando se usa una instrucción UPDATE en SQL.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1018">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="faf5c-1019">Excel</span><span class="sxs-lookup"><span data-stu-id="faf5c-1019">Excel</span></span>

- <span data-ttu-id="faf5c-1020">La información clave en holandés para el título del documento ha sido cambiada a Alt-G.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1020">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="faf5c-1021">Se ha corregido un problema en Excel en el que las macros asignadas a formas o controles de formularios podían mostrar un mensaje de error incorrecto o funcionar en intervalos de destino incorrectos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1021">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="faf5c-1022">Se resolvió un problema con buscar y reemplazar ese cambio donde el foco estaba en el diálogo después de encontrar el primer elemento.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1022">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="faf5c-1023">Esto corrige un problema por el cual al cambiar la forma en que se ordena y actualiza una tabla dinámica mientras se está en una sesión de co autoría con otros usuarios se podía provocar un bloqueo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1023">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="faf5c-1024">Arreglamos un problema cuando el filtro de una tabla dinámica OLAP se estableció en un valor que se había eliminado del cubo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1024">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="faf5c-1025">Se han corregido los colores que se usan en las vistas previas al insertar gráficos con plantillas de gráficos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1025">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="faf5c-1026">Se ha corregido un problema que podía impedir que los gráficos de líneas de dispersión se representaran correctamente al cambiar la colección de series.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1026">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="faf5c-1027">Se resolvió un problema que causó que los gráficos de cascada y embudo se desincronizara con las tablas cuando se insertaban o eliminaban celdas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1027">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="faf5c-1028">Se ha corregido un problema de conflicto de fusión en Excel que hacía que los usuarios tuvieran que volver a abrir el libro de trabajo para elegir los cambios.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1028">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="faf5c-1029">Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1029">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="faf5c-1030">Se resolvió un problema que causaba un error de tiempo de ejecución de la macro que activaba las ventanas minimizadas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1030">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="faf5c-1031">Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1031">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="faf5c-1032">Se resolvió un problema que causaba que las operaciones de cortar y pegar junto a una mesa fallaran cuando se co autoría con otros.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1032">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="faf5c-1033">Se resolvió un problema que causaba interrupciones de co autoría cuando se cambiaban las propiedades personalizadas con macros en ejecución.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1033">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="faf5c-1034">Hubo un problema en el que no se podían seleccionar elementos del cuadro combinado de un formulario de WPF (Windows Presentation Foundation) que fue abierto por un complemento.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1034">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="faf5c-1035">Se ha resuelto un problema que puede haber causado un bloqueo al buscar archivos recientes cuando no hay ningún libro de trabajo abierto.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1035">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="faf5c-1036">Problema de rendimiento con las Funciones Asincrónicas Definidas por el Usuario que hacía que se ejecutaran sincrónicamente.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1036">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="faf5c-1037">Mejoras significativas en el rendimiento de la eliminación de columnas con celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1037">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="faf5c-1038">Se resolvió un problema en el que la selección de una celda después del desplazamiento podía dar lugar a que se seleccionara la celda incorrecta.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1038">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="faf5c-1039">Se ha resuelto un problema en el que la función de búsqueda puede devolver un error.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1039">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="faf5c-1040">Se ha resuelto un problema por el que los libros de trabajo creados en versiones anteriores de Office podían hacer que Excel se colgara al abrirlos en las versiones actuales de Office.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1040">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="faf5c-1041">Problema de rendimiento bajo al hacer clic en el botón Color de fuente cuando un archivo tiene un formato condicional extenso.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1041">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="faf5c-1042">Se ha corregido un problema por el que el área de impresión en la vista previa de impresión no era correcta.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1042">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="faf5c-1043">Excel puede tener problemas al editar un archivo protegido desde una red compartida no confiable.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1043">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="faf5c-1044">Hemos mejorado significativamente el rendimiento del filtrado por color.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1044">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="faf5c-1045">Se resolvió un problema que impedía que los hipervínculos se pegaran en algunas hojas protegidas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1045">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="faf5c-1046">Se habilitó más de 16 complementos para que se muestren al navegar en el administrador de complementos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1046">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="faf5c-1047">Este cambio evita un problema con ciertos controladores de gráficos Intel aprovechando la renderización de software.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1047">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="faf5c-1048">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="faf5c-1048">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="faf5c-1049">Esta actualización corrige un error por el cual los documentos de Office pueden fallar al subirlos a OneDrive para la Empresa con el mensaje "Error al cargar".</span><span class="sxs-lookup"><span data-stu-id="faf5c-1049">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="faf5c-1050">Corregir problema en la característica Ideas de Excel, error al cargar el complemento haciendo clic en el botón Ideas en el cliente Win32.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1050">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="faf5c-1051">Outlook</span><span class="sxs-lookup"><span data-stu-id="faf5c-1051">Outlook</span></span>

- <span data-ttu-id="faf5c-1052">Los vínculos de cid:image de los mensajes de Outlook ahora se pueden romper correctamente cuando se solicite.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1052">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="faf5c-1053">Se ha corregido un problema que causaba que los usuarios que actualizaban su buzón de la autenticación básica a la moderna, terminaban con una cuenta incorrecta asociada a su perfil de Outlook.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1053">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="faf5c-1054">Corregido un problema que hizo que los complementos web accedieran a los mensajes de Digital Rights Managed cuando no deberían hacerlo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1054">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="faf5c-1055">Corregido un problema que causó que las URLS de enlace simple no se mostraran en algunos enlaces seguros.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1055">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="faf5c-1056">Esto actualiza la lógica de bloqueo de adjuntos en Outlook para bloquear también los adjuntos de Python.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1056">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="faf5c-1057">Corregido un problema que hacía que un subconjunto de usuarios POP3 viera todos sus correos electrónicos formateados en texto plano, independientemente de la configuración.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1057">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="faf5c-1058">Esta corrección restaurará la vista de los mensajes con formato HTML.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1058">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="faf5c-1059">Corregido un problema que hacía que los usuarios experimentaran un error de permiso al copiar elementos de su calendario principal a un calendario de grupo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1059">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="faf5c-1060">Corregido un problema que hacía que los usuarios no pudieran acceder a las sugerencias de ubicación a través de un lector de pantalla.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1060">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="faf5c-1061">Corregido un problema que hacía que los usuarios vieran un retraso notable al interactuar con sus carpetas de buzón de correo a través de métodos abreviados de teclado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1061">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="faf5c-1062">Corregido un problema que causaba una fuga de memoria en sesiones de Outlook muy largas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1062">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="faf5c-1063">Corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al abrir el cuadro de diálogo Reglas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1063">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="faf5c-1064">Corregido un problema que haría que los usuarios experimentaran un bloqueo en Outlook al interactuar con ciertos vínculos seguros.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1064">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="faf5c-1065">Corregido un problema que causó ambigüedad a los gerentes en cuanto a si un delegado ya había respondido o no a una determinada solicitud de reunión.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1065">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="faf5c-1066">Corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1066">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="faf5c-1067">Se ha solucionado un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "ok" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1067">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="faf5c-1068">Este cambio permite a los administradores habilitar una política para preferir el correo electrónico de la cuenta proporcionada en los avisos de autorización de AutoDiscover sobre el UPN.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1068">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="faf5c-1069">De forma predeterminada, detección automática prefiere el UPN de la cuenta, cuando está disponible.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1069">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="faf5c-1070">Se ha corregido un problema que provocaba que los usuarios vieran un error en la búsqueda con grupos modernos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1070">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="faf5c-1071">Solucionó un problema que causaba que los usuarios de Outlook se quedaran atascados en el estado "Necesita contraseña" en ciertos escenarios.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1071">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="faf5c-1072">Se abordó un problema que hizo que los usuarios vieran sugerencias de salas para reuniones que se produjeron fuera de las horas de disponibilidad de dichas salas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1072">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="faf5c-1073">Corregido un problema que hizo que los usuarios encontraran errores de "algoritmo de cifrado no admitido" al enviar un correo electrónico cifrado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1073">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="faf5c-1074">Corregido un problema para los usuarios que no hablan inglés, en el que la línea de asunto de un correo electrónico era increíblemente pequeña.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1074">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="faf5c-1075">Corregido un problema que hacía que algunos usuarios vieran duplicadas las carpetas especiales creadas al añadir una cuenta de Exchange secundaria.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1075">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="faf5c-1076">Corregido un problema que hacía que los usuarios experimentaran un bloqueo al intentar crear una regla a partir de un mensaje de "Conversación perdida".</span><span class="sxs-lookup"><span data-stu-id="faf5c-1076">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="faf5c-1077">Corregido un problema con la selección del algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1077">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="faf5c-1078">Corregido un problema que hacía que no se mostraran las sugerencias de política cuando se utilizaba un remitente alternativo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1078">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="faf5c-1079">Corregido un problema que hacía que los usuarios observaran una fuga de memoria en el proceso de Outlook.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1079">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="faf5c-1080">Corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1080">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="faf5c-1081">Corregido un problema que causaba que la búsqueda de la carpeta actual fallara de forma intermitente.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1081">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="faf5c-1082">Corregido un problema que hizo que algunos usuarios encontraran errores de autenticación al intentar recuperar su configuración de nube para Outlook.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1082">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="faf5c-1083">Corregido un problema que causó un bloqueo en la experiencia de los comentarios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1083">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="faf5c-1084">Corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1084">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="faf5c-1085">Corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1085">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="faf5c-1086">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="faf5c-1086">PowerPoint</span></span>

- <span data-ttu-id="faf5c-1087">Se ha corregido un problema por el que algunos complementos producían errores inesperados alrededor de las formas en gráficos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1087">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="faf5c-1088">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="faf5c-1088">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="faf5c-1089">Este cambio restaura el nombre accesible de los controles de vídeo de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1089">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="faf5c-1090">Hemos corregido un problema que podría impedir que se inicien algunas animaciones.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1090">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="faf5c-1091">Hemos corregido un problema en el que al copiar una diapositiva de una presentación a otra, se pueden crear patrones duplicados.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1091">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="faf5c-1092">Los archivos con nuevos comentarios modernos mostrarán una advertencia amarilla si se abren en una versión no soportada</span><span class="sxs-lookup"><span data-stu-id="faf5c-1092">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="faf5c-1093">Fiabilidad fija: corregido un problema por el que el complemento de terceros podía bloquearse en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1093">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="faf5c-1094">Corregido un problema por el que los caracteres katakana de medio ancho no giraban correctamente cuando estaban en cuadros de texto verticales en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1094">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="faf5c-1095">Project</span><span class="sxs-lookup"><span data-stu-id="faf5c-1095">Project</span></span>

- <span data-ttu-id="faf5c-1096">Se ha corregido un problema para permitir que los usuarios en Windows 7 puedan abrir proyectos desde Project Web App y sitios de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1096">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="faf5c-1097">Se identificó un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de sólo lectura.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1097">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="faf5c-1098">El comando Level All no resuelve adecuadamente una sobreasignación de recursos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1098">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="faf5c-1099">Si tiene una tarea sin nada de trabajo, es posible que la tarea no se pueda marcar como completada y siempre se mostrará en el 99 %.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1099">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="faf5c-1100">Visio</span><span class="sxs-lookup"><span data-stu-id="faf5c-1100">Visio</span></span>

- <span data-ttu-id="faf5c-1101">La exportación como SVG de Visio estaba fallando por una variedad de formas.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1101">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="faf5c-1102">Word</span><span class="sxs-lookup"><span data-stu-id="faf5c-1102">Word</span></span>

- <span data-ttu-id="faf5c-1103">Este cambio conducirá a mejoras de rendimiento en la apertura de documentos utilizando Word.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1103">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="faf5c-1104">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="faf5c-1104">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="faf5c-1105">Hemos corregido un problema que podría haber causado problemas de escala al imprimir en impresoras Deskjet.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1105">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="faf5c-1106">Hemos corregido un problema en los cambios de pista que a veces van en un bucle infinito.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1106">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="faf5c-1107">Corregidos varios problemas que hacían que la aplicación se colgara al apagarse.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1107">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="faf5c-1108">También se corrigieron ciertos fallos relacionados con los complementos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1108">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="faf5c-1109">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="faf5c-1109">Office Suite</span></span>

- <span data-ttu-id="faf5c-1110">Corregido el problema de la identificación incorrecta del nombre de la nueva era "Reiwa" en hiragana y kanji como una expresión mal escrita o poco gramatical.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1110">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="faf5c-1111">Corregido un problema que hacía que los usuarios recibieran el mensaje "Lo sentimos, algo nos impide compartir esto" al intentar compartir archivos almacenados en SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1111">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="faf5c-1112">Se ha solucionado un problema que podía causar la pérdida de datos en sesiones que implicaban tanto la co autoría como la edición fuera de línea en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1112">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="faf5c-1113">Esta es una solución para un fallo que los usuarios podrían sufrir al abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1113">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="faf5c-1114">Evita que los usuarios de PowerPoint se encuentren con un error cuando intentan hacer una presentación en línea.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1114">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="faf5c-1115">En algunos casos, un archivo de sharepoint respaldado por un motor de sincronización podría mostrar "Guardado" pero no haber guardado realmente ningún cambio, lo que provocaría la pérdida de datos.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1115">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="faf5c-1116">Se resolvió un problema que impedía a los usuarios guardar documentos de Word, Excel y PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1116">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="faf5c-1117">Este problema afecta a los usuarios que crean un nuevo archivo y muestra la opción "Guardar como diálogo" después de hacer clic en el icono Guardar o presionar Ctrl + S.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1117">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="faf5c-1118">Se ha corregido un problema de perf en Win7 en el que la galería de formas de inserción de la cinta en todas las aplicaciones tardaba aproximadamente 4 segundos en aparecer.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1118">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="faf5c-1119">Corregido un error por el que la información de accesibilidad no se mostraba en la losa del lugar de información de los bastidores.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1119">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="faf5c-1120">Mejora de la fiabilidad del proceso de actualización de Office en lo que respecta a la integridad del registro.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1120">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="faf5c-1121">Se ha corregido un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1121">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="faf5c-1122">Se ha solucionado un problema por el que los mensajes de actualización de Office aparecían en un idioma diferente al esperado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1122">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="faf5c-1123">En el futuro, los mensajes de actualización de Office coincidirán correctamente con el idioma de visualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1123">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="faf5c-1124">Corregido un problema en el que una actualización no se aplicaría en ciertos casos en los que el usuario no es un administrador y la cuenta del sistema no tenía conectividad de red.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1124">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="faf5c-1125">En determinadas circunstancias, los accesos directos de Office pueden desaparecer tras una actualización.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1125">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="faf5c-1126">Esta actualización mejora la fiabilidad en la publicación de los accesos directos de Office.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1126">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="faf5c-1127">Se ha corregido un problema por el que las actualizaciones se bloqueaban inesperadamente en las redes de medición.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1127">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="faf5c-1128">Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1128">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="faf5c-1129">Mejora de la confiabilidad al descargar las actualizaciones de Office al reanudar las descargas que pueden haberse interrumpido anteriormente.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1129">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="faf5c-1130">Corregidos los problemas relacionados con la propiedad Textbox/Shape Autofit en los plug-ins de terceros.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1130">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="faf5c-1131">Hemos corregido un problema en el que las vistas de árboles grandes podían resultar en un choque.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1131">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="faf5c-1132">Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1132">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-january-14"></a><span data-ttu-id="faf5c-1134">Versión 1902: 14 de enero</span><span class="sxs-lookup"><span data-stu-id="faf5c-1134">Version 1902: January 14</span></span>
<span data-ttu-id="faf5c-1135">*VVersión 1902 (compilación 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-1135">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="faf5c-1136">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-1136">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="faf5c-1138">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="faf5c-1138">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="faf5c-1139">Excel</span><span class="sxs-lookup"><span data-stu-id="faf5c-1139">Excel</span></span>

- <span data-ttu-id="faf5c-1140">Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1140">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="faf5c-1141">Outlook</span><span class="sxs-lookup"><span data-stu-id="faf5c-1141">Outlook</span></span>

- <span data-ttu-id="faf5c-1142">Corregido un problema que causó que los usuarios se encontraran con errores de "el algoritmo de cifrado no es compatible" al enviar un correo electrónico cifrado.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1142">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="faf5c-1143">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="faf5c-1143">PowerPoint</span></span>

- <span data-ttu-id="faf5c-1144">Los archivos con nuevos comentarios modernos mostrarán una advertencia amarilla si se abren en una versión no soportada.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1144">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="faf5c-1145">Word</span><span class="sxs-lookup"><span data-stu-id="faf5c-1145">Word</span></span>

- <span data-ttu-id="faf5c-1146">Este cambio conducirá a mejoras de rendimiento en la apertura de documentos utilizando Word.</span><span class="sxs-lookup"><span data-stu-id="faf5c-1146">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (NO ELIMINAR LOS DETALLES DEL CONTENIDO FINAL)

## <a name="version-1808-january-14"></a><span data-ttu-id="faf5c-1148">Versión 1808: 14 de enero</span><span class="sxs-lookup"><span data-stu-id="faf5c-1148">Version 1808: January 14</span></span>
<span data-ttu-id="faf5c-1149">*Versión 1808 (compilación 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="faf5c-1149">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="faf5c-1150">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="faf5c-1150">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

> [!NOTE]
> <span data-ttu-id="faf5c-1152">Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="faf5c-1152">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (NO MODIFICAR INICIO DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
[//]: # (|Win32|DC|Production| |16.0.12527.21330|versión-10-noviembre-2002|)
[//]: # (|Win32|DC|Production| |16.0.12527.21236|versión-13-octubre-2002|)
[//]: # (|Win32|DC|Producción| |16.0.12527.21104|versión-2002-08-agosto|)
[//]: # (|Win32|DC|Producción| |16.0.12527.20988|versión-2002-11-agosto|)
[//]: # (| Win32 | CC | Producción | | 16.0.12527.20880 | versión-2002-julio-14 |)
[//]: # (NO MODIFICAR EL FIN DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
