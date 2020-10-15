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
ms.openlocfilehash: f7f3b39521132fb11226bc512f782e0adec5aba8
ms.sourcegitcommit: ef46a4fc154c7bca37e37a7456c36f92ffc15ebb
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 10/13/2020
ms.locfileid: "48453418"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-releases-in-2020"></a><span data-ttu-id="460b9-103">Notas de la versión para las versiones de canal empresarial semestral en 2020</span><span class="sxs-lookup"><span data-stu-id="460b9-103">Release notes for Semi-Annual Enterprise Channel releases in 2020</span></span>

<span data-ttu-id="460b9-104">Estas notas de la versión proporcionan información sobre las nuevas características y las actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones de canal empresarial semestral en 2020 para las Aplicaciones de Microsoft 365 para empresas, las Aplicaciones de Microsoft 365 para negocios y las versiones de suscripción de las aplicaciones de escritorio de Project y Visio.</span><span class="sxs-lookup"><span data-stu-id="460b9-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="460b9-p101">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="460b9-p101">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="460b9-107">OneNote 2016 ahora se incluirá de forma predeterminada cuando un usuario en el canal empresarial semestral descargue e instale las Aplicaciones de Microsoft 365 en Windows 10 desde el Portal de Office.</span><span class="sxs-lookup"><span data-stu-id="460b9-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO FINAL)

## <a name="version-2002-october-13"></a><span data-ttu-id="460b9-109">Versión 2002: 13 de octubre</span><span class="sxs-lookup"><span data-stu-id="460b9-109">Version 2002: October 13</span></span>
<span data-ttu-id="460b9-110">*Versión 2002 (compilación 12527.21236)*</span><span class="sxs-lookup"><span data-stu-id="460b9-110">*Version 2002 (Build 12527.21236)*</span></span>

<span data-ttu-id="460b9-111">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="460b9-113">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="460b9-113">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="460b9-114">Acceso</span><span class="sxs-lookup"><span data-stu-id="460b9-114">Access</span></span>

- <span data-ttu-id="460b9-115">Ya no debería recibir un error "La consulta es demasiado compleja" o de recurso del sistema excedido en su versión de 64 bits de Access, siempre y cuando cumpla con las directrices y requisitos de la base de datos de Access.</span><span class="sxs-lookup"><span data-stu-id="460b9-115">You should no longer receive a "Query is too complex" or a system resource exceeded error on your 64-bit version of Access, as long as you are meeting Access database guidelines and requirements.</span></span>


- <span data-ttu-id="460b9-116">Una vez que decida usar nuestra característica de filtro después de nuestro diseñador de consultas, la base de datos ya no debería bloquearse.</span><span class="sxs-lookup"><span data-stu-id="460b9-116">Once you decide to use our filter feature after our query designer, your database should no longer crash.</span></span> <span data-ttu-id="460b9-117">Compruebe lo que corresponda.</span><span class="sxs-lookup"><span data-stu-id="460b9-117">Please check accordingly.</span></span>


### <a name="excel"></a><span data-ttu-id="460b9-118">Excel</span><span class="sxs-lookup"><span data-stu-id="460b9-118">Excel</span></span>

- <span data-ttu-id="460b9-119">Se corrigió un problema por el cual los usuarios no podían modificar un filtro de tabla dinámica porque estaba configurado en un valor que ya no estaba presente en una base de datos de Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="460b9-119">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="460b9-120">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="460b9-120">PowerPoint</span></span>

- <span data-ttu-id="460b9-121">Las nuevas presentaciones creadas a partir de una plantilla podían heredar una configuración que impedía una buena experiencia de coautoría.</span><span class="sxs-lookup"><span data-stu-id="460b9-121">New presentations created from a template could inherit a setting that prevented  a good co-authoring experience.</span></span> <span data-ttu-id="460b9-122">Esta corrección garantiza que la configuración se haya borrado en este caso.</span><span class="sxs-lookup"><span data-stu-id="460b9-122">This fix ensures that the setting is cleared in this case.</span></span>


### <a name="word"></a><span data-ttu-id="460b9-123">Word</span><span class="sxs-lookup"><span data-stu-id="460b9-123">Word</span></span>

- <span data-ttu-id="460b9-124">Se ha corregido un problema por el que al abrir documentos con saltos de página y columnas, el usuario podía encontrar un mensaje de error, "Ha excedido el número máximo de páginas admitidas por Microsoft Word, o el documento puede estar dañado"</span><span class="sxs-lookup"><span data-stu-id="460b9-124">We fixed an issue which when opening documents with page breaks and columns, user might encountered an error message, " You have exceeded the maximum number of pages allowed by Microsoft Word supported, or the document may be damaged"</span></span>


### <a name="office-suite"></a><span data-ttu-id="460b9-125">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="460b9-125">Office Suite</span></span>

- <span data-ttu-id="460b9-126">Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan toners</span><span class="sxs-lookup"><span data-stu-id="460b9-126">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="460b9-127">Cambiar mensaje para mostrar "tóner/Ink Low" & "no tóner/tinta".</span><span class="sxs-lookup"><span data-stu-id="460b9-127">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO FINAL)

## <a name="version-1908-october-13"></a><span data-ttu-id="460b9-129">Versión 1908: 13 de octubre</span><span class="sxs-lookup"><span data-stu-id="460b9-129">Version 1908: October 13</span></span>
<span data-ttu-id="460b9-130">*Versión 1908 (compilación 11929.20966)*</span><span class="sxs-lookup"><span data-stu-id="460b9-130">*Version 1908 (Build 11929.20966)*</span></span>

<span data-ttu-id="460b9-131">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-131">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="460b9-133">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="460b9-133">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="460b9-134">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="460b9-134">Office Suite</span></span>

- <span data-ttu-id="460b9-135">Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan toners</span><span class="sxs-lookup"><span data-stu-id="460b9-135">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="460b9-136">Cambiar mensaje para mostrar "tóner/Ink Low" & "no tóner/tinta".</span><span class="sxs-lookup"><span data-stu-id="460b9-136">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO FINAL)

## <a name="version-2002-september-08"></a><span data-ttu-id="460b9-138">Versión 2002: 08 de septiembre</span><span class="sxs-lookup"><span data-stu-id="460b9-138">Version 2002: September 08</span></span>
<span data-ttu-id="460b9-139">*Versión 2002 (Compilación 12527.21104)*</span><span class="sxs-lookup"><span data-stu-id="460b9-139">*Version 2002 (Build 12527.21104)*</span></span>

<span data-ttu-id="460b9-140">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-140">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="460b9-142">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="460b9-142">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="460b9-143">Excel</span><span class="sxs-lookup"><span data-stu-id="460b9-143">Excel</span></span>

- <span data-ttu-id="460b9-144">Esto soluciona un problema en el que las conexiones creadas por el proveedor de datos SQL en versiones anteriores de Office establecerían las propiedades de la tabla interna de manera diferente a Office 365.</span><span class="sxs-lookup"><span data-stu-id="460b9-144">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="460b9-145">Esto provocó que el menú desplegable Vista previa de tabla / Editor de consultas se deshabilitara para los archivos con conexiones creadas en versiones anteriores de Office cuando se abrieron con Office 365.</span><span class="sxs-lookup"><span data-stu-id="460b9-145">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>


- <span data-ttu-id="460b9-146">Se corrigió un problema por el cual las entradas manuscritas podrían hacer que Excel dejara de responder.</span><span class="sxs-lookup"><span data-stu-id="460b9-146">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="460b9-147">Outlook</span><span class="sxs-lookup"><span data-stu-id="460b9-147">Outlook</span></span>

- <span data-ttu-id="460b9-148">Corrige un problema que evitaba que los usuarios se conectaran a las carpetas públicas luego de agregar un buzón compartido.</span><span class="sxs-lookup"><span data-stu-id="460b9-148">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


### <a name="office-suite"></a><span data-ttu-id="460b9-149">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="460b9-149">Office Suite</span></span>

- <span data-ttu-id="460b9-150">Este cambio resuelve un problema con el cuadro de diálogo de Comprimir imagen, que no retiene determinadas configuraciones de usuario.</span><span class="sxs-lookup"><span data-stu-id="460b9-150">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-september-08"></a><span data-ttu-id="460b9-152">Versión 1908: 08 de septiembre</span><span class="sxs-lookup"><span data-stu-id="460b9-152">Version 1908: September 08</span></span>
<span data-ttu-id="460b9-153">*Versión 1908 (compilación 11929.20946)*</span><span class="sxs-lookup"><span data-stu-id="460b9-153">*Version 1908 (Build 11929.20946)*</span></span>

<span data-ttu-id="460b9-154">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-154">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-august-11"></a><span data-ttu-id="460b9-155">Versión 2002: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="460b9-155">Version 2002: August 11</span></span>
<span data-ttu-id="460b9-156">*Versión 2002 (compilación 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="460b9-156">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="460b9-157">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-157">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="460b9-159">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="460b9-159">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="460b9-160">Excel</span><span class="sxs-lookup"><span data-stu-id="460b9-160">Excel</span></span>

- <span data-ttu-id="460b9-161">Se corrigió un problema por el que no se podía cambiar a la edición de archivos que se han abierto como "recomendado solo lectura".</span><span class="sxs-lookup"><span data-stu-id="460b9-161">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="460b9-162">OneNote</span><span class="sxs-lookup"><span data-stu-id="460b9-162">OneNote</span></span>

- <span data-ttu-id="460b9-163">Se quitaron las llamadas de identidad redundantes para reducir el uso de recursos</span><span class="sxs-lookup"><span data-stu-id="460b9-163">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="460b9-164">Se mejoró la detección del estado de la coautoría para reducir el uso de recursos.</span><span class="sxs-lookup"><span data-stu-id="460b9-164">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="460b9-165">Se mejoró la función de detección de errores y la calidad de la experiencia de sincronización.</span><span class="sxs-lookup"><span data-stu-id="460b9-165">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="460b9-166">Outlook</span><span class="sxs-lookup"><span data-stu-id="460b9-166">Outlook</span></span>

- <span data-ttu-id="460b9-167">Se corrigió un problema que causaba un problema de rendimiento importante al iniciar Outlook en algunos espacios empresariales.</span><span class="sxs-lookup"><span data-stu-id="460b9-167">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="460b9-168">Skype</span><span class="sxs-lookup"><span data-stu-id="460b9-168">Skype</span></span>

- <span data-ttu-id="460b9-169">Se corrigió un problema por el que se podía producir un error al compartir la pantalla en un cliente de Skype Empresarial de 32 bits después de ejecutarlo durante varios días.</span><span class="sxs-lookup"><span data-stu-id="460b9-169">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="460b9-170">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="460b9-170">Office Suite</span></span>

- <span data-ttu-id="460b9-171">Se corrigió un problema que se producía al desactivar el autoguardado a través de la directiva de grupo: era posible que algunos documentos no mostraran el contenido más reciente de servidor al abrirse hasta que el usuario hiciera clic en "Actualizaciones disponibles".</span><span class="sxs-lookup"><span data-stu-id="460b9-171">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-august-11"></a><span data-ttu-id="460b9-173">Versión 1908: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="460b9-173">Version 1908: August 11</span></span>
<span data-ttu-id="460b9-174">*Versión 1908 (compilación 11929.20934)*</span><span class="sxs-lookup"><span data-stu-id="460b9-174">*Version 1908 (Build 11929.20934)*</span></span>

<span data-ttu-id="460b9-175">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-175">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1902-august-11"></a><span data-ttu-id="460b9-176">Versión 1902: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="460b9-176">Version 1902: August 11</span></span>
<span data-ttu-id="460b9-177">*Versión 1902 (compilación 11328.20644)*</span><span class="sxs-lookup"><span data-stu-id="460b9-177">*Version 1902 (Build 11328.20644)*</span></span>

<span data-ttu-id="460b9-178">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-178">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-july-14"></a><span data-ttu-id="460b9-181">Versión 2002: 14 de julio</span><span class="sxs-lookup"><span data-stu-id="460b9-181">Version 2002: July 14</span></span>
<span data-ttu-id="460b9-182">*Versión 2002 (compilación 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="460b9-182">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="460b9-183">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-183">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="460b9-185">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="460b9-185">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="460b9-186">Access</span><span class="sxs-lookup"><span data-stu-id="460b9-186">Access</span></span>

- <span data-ttu-id="460b9-187">**Buscar tablas vinculadas rápidamente:** nuestro nuevo cuadro de búsqueda hace que buscar tablas vinculadas sea mucho más sencillo.</span><span class="sxs-lookup"><span data-stu-id="460b9-187">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="460b9-188">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-188">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="460b9-189">Excel</span><span class="sxs-lookup"><span data-stu-id="460b9-189">Excel</span></span>

- <span data-ttu-id="460b9-190">**Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="460b9-190">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="460b9-191">**Complemento del visualizador de datos:** Crear rápidamente diagramas de flujo de Visio desde Excel.</span><span class="sxs-lookup"><span data-stu-id="460b9-191">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="460b9-192">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-192">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="460b9-193">**Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.</span><span class="sxs-lookup"><span data-stu-id="460b9-193">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="460b9-194">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-194">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="460b9-195">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="460b9-195">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="460b9-196">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="460b9-196">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="460b9-197">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="460b9-197">Find them at Insert > Icons.</span></span> [<span data-ttu-id="460b9-198">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-198">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="460b9-199">**Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los demás.</span><span class="sxs-lookup"><span data-stu-id="460b9-199">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="460b9-200">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="460b9-200">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="460b9-201">**Resalte lo que queda por hacer**: seleccione Resolver para contraer los comentarios y hacer que resalten los elementos abiertos.</span><span class="sxs-lookup"><span data-stu-id="460b9-201">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="460b9-202">\*\*Escriba una fórmula que devuelva varios valores: \*\*Escriba rápidamente una fórmula que devuelva múltiples valores y se derramarán automáticamente en las celdas vecinas.</span><span class="sxs-lookup"><span data-stu-id="460b9-202">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="460b9-203">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-203">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="460b9-204">Ver detalles en [entrada de blog](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="460b9-204">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="460b9-205">**Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. </span><span class="sxs-lookup"><span data-stu-id="460b9-205">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="460b9-206">**Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su libro.</span><span class="sxs-lookup"><span data-stu-id="460b9-206">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="460b9-207">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-207">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="460b9-208">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="460b9-208">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="460b9-209">**Encuentre lo que busca:** Realice búsquedas de comandos, personas, archivos, fotos, artículos en la web y más.</span><span class="sxs-lookup"><span data-stu-id="460b9-209">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="460b9-210">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-210">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="460b9-211">**Seis potentes funciones:** Seis potentes funciones: Hemos agregado seis nuevas funciones para mejorar las hojas de cálculo: FILTRAR, ORDENAR, ORDENARPOR, UNICOS, SECUENCIA y MATRIZALEAT.</span><span class="sxs-lookup"><span data-stu-id="460b9-211">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="460b9-212">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-212">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="460b9-213">**Busque a la izquierda, busque a la derecha... BUSCARX ya está aquí**: fila por fila, busque lo que necesite en una tabla o un rango con BUSCARX.</span><span class="sxs-lookup"><span data-stu-id="460b9-213">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="460b9-214">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-214">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="460b9-215">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span><span class="sxs-lookup"><span data-stu-id="460b9-215">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="460b9-216">**Dominar el libro grande:** celdas, fórmulas, gráficos y tablas... Obtenga una instantánea de su libro con estadísticas de libros.</span><span class="sxs-lookup"><span data-stu-id="460b9-216">**Tame your big workbook:** Cells, formulas, charts, tables... get a snapshot of your workbook with Workbook Statistics.</span></span>

- <span data-ttu-id="460b9-217">\*\*Lea y responda sobre la marcha: \*\*responda a los comentarios y las menciones directamente desde el correo electrónico sin abrir el libro.</span><span class="sxs-lookup"><span data-stu-id="460b9-217">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="460b9-218">**Consiga su atención con\@menciones:** use @menciones en los comentarios para avisar a los compañeros de trabajo cuando necesite su participación.</span><span class="sxs-lookup"><span data-stu-id="460b9-218">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="460b9-219">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-219">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a><span data-ttu-id="460b9-220">Outlook</span><span class="sxs-lookup"><span data-stu-id="460b9-220">Outlook</span></span>

- <span data-ttu-id="460b9-221">**Encajar más mensajes en la pantalla:** seleccione Ver > Usar espaciado más estrecho para ajustar el espaciado entre mensajes.</span><span class="sxs-lookup"><span data-stu-id="460b9-221">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="460b9-222">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-222">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="460b9-223">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="460b9-223">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="460b9-224">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="460b9-224">Find them at Insert > Icons.</span></span> [<span data-ttu-id="460b9-225">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-225">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="460b9-226">**Deja que lo dibuje:** garabatee sobre las imágenes o agregue un Lienzo de dibujo para enviar sus pensamientos con la entrada de lápiz.</span><span class="sxs-lookup"><span data-stu-id="460b9-226">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="460b9-227">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-227">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="460b9-228">**Obtenga sugerencias de ubicaciones:** Empiece a escribir en Ubicación cuando programe citas y reuniones, Outlook le sugerirá salas, direcciones y otros lugares recientes.</span><span class="sxs-lookup"><span data-stu-id="460b9-228">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="460b9-229">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-229">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br /><span data-ttu-id="460b9-230">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="460b9-230">See details in [blog post](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span></span>

- <span data-ttu-id="460b9-231">**Protección avanzada frente a ataques**: con la Protección contra amenazas avanzada de Office 365, estará protegido frente a ataques mediante hipervínculos en asuntos de correos electrónicos, mensajes adjuntos, mensajes firmados, rutas de red, etc.</span><span class="sxs-lookup"><span data-stu-id="460b9-231">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="460b9-232">**Insertar el menú de vínculos en Outlook inserta un vínculo con el permiso definido por el administrador de inquilinos:** un vínculo desde Insertar vínculo utilizado recientemente en Outlook insertaba un vínculo que solo funcionaba para los usuarios que ya tenían permisos.</span><span class="sxs-lookup"><span data-stu-id="460b9-232">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="460b9-233">A menudo esto causaba un intercambio continuo de mensajes de correo electrónico entre los usuarios que pedían acceso a un documento.</span><span class="sxs-lookup"><span data-stu-id="460b9-233">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="460b9-234">Hemos actualizado esta experiencia para que ahora el vínculo se inserte con el permiso predeterminado establecido por el administrador de inquilinos. Para MSIT se trata de "la organización puede editar", por lo que todos los usuarios internos que reciban un vínculo compartido de esta manera podrán acceder a él.</span><span class="sxs-lookup"><span data-stu-id="460b9-234">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="460b9-235">**Ver los mensajes bajo otra luz:** use el botón sol/luna para cambiar entre fondos claros y oscuros en el panel de lectura.</span><span class="sxs-lookup"><span data-stu-id="460b9-235">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="460b9-236">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-236">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="460b9-237">**Ahora es más fácil detectar correos de suplantación de identidad:** los mensajes de correo no deseado y de suplantación de identidad tienen un aspecto diferente para que pueda identificarlos y eliminarlos fácilmente en la bandeja de entrada.</span><span class="sxs-lookup"><span data-stu-id="460b9-237">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="460b9-p123">**Todas las opciones de cifrado en un solo lugar:** vaya a Opciones > Cifrar para elegir cómo proteger su mensaje de correo. [Más información](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="460b9-p123">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="460b9-240">**Busque incluso con errores ortográficos o tipográficos:** Outlook encontrará lo que busca, aunque no coincida con la forma exacta en que lo escribió.</span><span class="sxs-lookup"><span data-stu-id="460b9-240">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="460b9-241">**Conecte su red de LinkedIn con Outlook:** Conecte de forma segura su cuenta de LinkedIn con su cuenta de Microsoft para ver la información de los perfiles de LinkedIn directamente en las tarjetas personales.</span><span class="sxs-lookup"><span data-stu-id="460b9-241">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="460b9-242">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-242">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="460b9-243">**Ver mensajes relevantes en los resultados de búsqueda:** Outlook analiza los términos de búsqueda y muestra los mensajes de correo electrónico más relevantes en la parte superior de los resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="460b9-243">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="460b9-244">También verá todos los resultados ordenados por fecha en la sección de Resultados principales.</span><span class="sxs-lookup"><span data-stu-id="460b9-244">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="460b9-245">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-245">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a><span data-ttu-id="460b9-246">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="460b9-246">PowerPoint</span></span>

- <span data-ttu-id="460b9-p126">**Usted calcula y nosotros le damos formato:** hemos convertido las expresiones matemáticas escritas a mano en caracteres estándar. Simplemente elija Entrada de lápiz a matemáticas y seleccione las notas escritas a mano para empezar. [Más información](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="460b9-p126">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="460b9-250">**Encuentre lo que busca:** use el cuadro de búsqueda para buscar texto, comandos, ayuda y mucho más.</span><span class="sxs-lookup"><span data-stu-id="460b9-250">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="460b9-251">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-251">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="460b9-252">**Entrada de tinta para magníficas diapositivas:** convierta el texto de tinta en formas estándar y texto y obtenga ideas de diseño inteligente del Diseñador de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="460b9-252">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="460b9-253">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-253">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="460b9-254">**Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su presentación.</span><span class="sxs-lookup"><span data-stu-id="460b9-254">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="460b9-255">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-255">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="460b9-256">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="460b9-256">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="460b9-257">**Repetición de entrada de lápiz:** cuando haya entradas de lápiz en sus diapositivas, aplique una animación de reproducción para reproducir el dibujo real de la entrada de lápiz durante la presentación con diapositivas.</span><span class="sxs-lookup"><span data-stu-id="460b9-257">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="460b9-258">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-258">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br /><span data-ttu-id="460b9-259">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="460b9-259">See details in [blog post](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span></span>

- <span data-ttu-id="460b9-260">**Una experiencia de vídeo más segura:** las mejoras de seguridad hacen que la experiencia de vídeo en línea sea más segura.</span><span class="sxs-lookup"><span data-stu-id="460b9-260">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="460b9-261">**Guarde una ilustración como SVG:** guarde un gráfico, una forma o una ilustración como un gráfico vectorial escalable, que se puede cambiar de tamaño sin perder calidad de imagen.</span><span class="sxs-lookup"><span data-stu-id="460b9-261">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="460b9-262">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-262">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="460b9-263">**Impresión de números de diapositiva en documentos:** los números de diapositiva se incluyen automáticamente en los documentos.</span><span class="sxs-lookup"><span data-stu-id="460b9-263">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="460b9-264">Ahora es usted quien decide si los deja o los quita.</span><span class="sxs-lookup"><span data-stu-id="460b9-264">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="460b9-265">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-265">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="460b9-266">**Encuentre los títulos de diapositivas que faltan y escríbalos**: los títulos de diapositivas añaden fuerza a su discurso y permiten que las diapositivas sean accesibles para los usuarios de todas las capacidades.</span><span class="sxs-lookup"><span data-stu-id="460b9-266">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="460b9-267">El comprobador de accesibilidad le muestra dónde faltan títulos para que pueda agregarlos en el momento.</span><span class="sxs-lookup"><span data-stu-id="460b9-267">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="460b9-268">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-268">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="460b9-269">**Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los demás.</span><span class="sxs-lookup"><span data-stu-id="460b9-269">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="460b9-270">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="460b9-270">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="460b9-271">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="460b9-271">**More icons to match your mood:** We've added more than 300 new icons.</span></span> <span data-ttu-id="460b9-272">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="460b9-272">Find them at Insert > Icons.</span></span> [<span data-ttu-id="460b9-273">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-273">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="460b9-274">**Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.</span><span class="sxs-lookup"><span data-stu-id="460b9-274">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span><br /><span data-ttu-id="460b9-275">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="460b9-275">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="460b9-276">**Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="460b9-276">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="460b9-277">**Colaboración rápida en tiempo real en PowerPoint:** colaboración rápida en tiempo real en PowerPoint</span><span class="sxs-lookup"><span data-stu-id="460b9-277">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="460b9-278">**Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. </span><span class="sxs-lookup"><span data-stu-id="460b9-278">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="460b9-279">**Nuevas herramientas de revisión:** no se preocupe de las palabras.</span><span class="sxs-lookup"><span data-stu-id="460b9-279">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="460b9-280">Ahora en PowerPoint se ofrecen sugerencias de gramática y escritura.</span><span class="sxs-lookup"><span data-stu-id="460b9-280">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="460b9-281">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-281">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="460b9-282">**Transcripción y subtítulos en directo:** las palabras del moderador se muestran automáticamente en la pantalla como subtítulos o se traducen en el idioma que prefiera.</span><span class="sxs-lookup"><span data-stu-id="460b9-282">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="460b9-283">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-283">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="460b9-284">**Optimizar la presentación para todos:** el comprobador de accesibilidad le ayuda a organizar los objetos de las diapositivas pensando en los lectores de pantalla.</span><span class="sxs-lookup"><span data-stu-id="460b9-284">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span><br /><span data-ttu-id="460b9-285">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span><span class="sxs-lookup"><span data-stu-id="460b9-285">See details in [blog post](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span></span>

- <span data-ttu-id="460b9-286">**¿Para que reinventar lo que puede reutilizar?:** ahorre tiempo usando de nuevo las diapositivas que haya creado o que otros usuarios han compartido con usted.</span><span class="sxs-lookup"><span data-stu-id="460b9-286">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="460b9-287">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-287">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a><span data-ttu-id="460b9-288">Visio</span><span class="sxs-lookup"><span data-stu-id="460b9-288">Visio</span></span>

- <span data-ttu-id="460b9-289">**Cree diagramas de Visio elegantes en Excel:** cree un diagrama de flujo o un organigrama con solo escribir datos en una hoja de cálculo.</span><span class="sxs-lookup"><span data-stu-id="460b9-289">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="460b9-290">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-290">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="460b9-291">**Vuelva a la escena del crimen:** use las nuevas plantillas Evidencia, Interior y Exterior en la plantilla Investigación de Escenas de Delitos para recrear con detalle escenarios de delitos.</span><span class="sxs-lookup"><span data-stu-id="460b9-291">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

### <a name="word"></a><span data-ttu-id="460b9-292">Word</span><span class="sxs-lookup"><span data-stu-id="460b9-292">Word</span></span>

- <span data-ttu-id="460b9-293">**Una experiencia de vídeo más segura:** las mejoras de seguridad hacen que la experiencia de vídeo en línea sea más segura.</span><span class="sxs-lookup"><span data-stu-id="460b9-293">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="460b9-294">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-294">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="460b9-295">**Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.</span><span class="sxs-lookup"><span data-stu-id="460b9-295">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="460b9-296">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-296">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="460b9-297">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="460b9-297">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="460b9-298">**Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="460b9-298">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="460b9-299">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="460b9-299">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="460b9-300">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="460b9-300">Find them at Insert > Icons.</span></span> [<span data-ttu-id="460b9-301">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-301">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br /><span data-ttu-id="460b9-302">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span><span class="sxs-lookup"><span data-stu-id="460b9-302">See details in [blog post](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span></span>

- <span data-ttu-id="460b9-303">**Borrar con precisión:** elija entre dos tamaños de borrador para arreglar pequeñas imperfecciones de la entrada de lápiz.</span><span class="sxs-lookup"><span data-stu-id="460b9-303">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="460b9-304">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-304">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="460b9-305">**Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los demás.</span><span class="sxs-lookup"><span data-stu-id="460b9-305">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="460b9-306">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="460b9-306">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="460b9-307">**Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su documento.</span><span class="sxs-lookup"><span data-stu-id="460b9-307">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="460b9-308">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-308">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="460b9-309">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="460b9-309">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="460b9-310">**Encuentre lo que busca:** use el cuadro de búsqueda para buscar texto, comandos, ayuda y mucho más.</span><span class="sxs-lookup"><span data-stu-id="460b9-310">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="460b9-311">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-311">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="460b9-312">**Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. </span><span class="sxs-lookup"><span data-stu-id="460b9-312">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="460b9-313">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-313">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="460b9-314">**El Editor para currículum vítae incorpora el Asistente para currículum vítae de LinkedIn:** el Editor para currículum vítae ofrece una selección de comprobaciones gramaticales y de estilo especialmente adaptadas a los currículums, para que el texto sea más preciso y profesional.</span><span class="sxs-lookup"><span data-stu-id="460b9-314">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="460b9-315">**Otros usuarios verán los cambios rápidamente:** con las mejoras en la coautoría, los colaboradores podrán ver los cambios más rápido que nunca.</span><span class="sxs-lookup"><span data-stu-id="460b9-315">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="460b9-316">**Se ha corregido un problema relacionado con los documentos causados por la combinación de objetos 3D:** corrige un problema de daños en un documento producido por la combinación de objetos 3D.</span><span class="sxs-lookup"><span data-stu-id="460b9-316">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="460b9-317">**Mejoras en la coautoría:** mejora del rendimiento de Word en coautoría en documentos con marcas de revisión.</span><span class="sxs-lookup"><span data-stu-id="460b9-317">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="460b9-318">**Mejoras en la coautoría:** mejora de la confiabilidad de la coautoría.</span><span class="sxs-lookup"><span data-stu-id="460b9-318">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="460b9-319">**Colaborando a todo color:** los comentarios y los cambios están codificados por color según la persona que contribuya, por lo que es fácil distinguir entre sus colaboradores.</span><span class="sxs-lookup"><span data-stu-id="460b9-319">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="460b9-320">**Editar documentos habilitados para macros de forma conjunta:** guarde sus archivos .docm en OneDrive para la Empresa y edítelos con sus colaboradores en tiempo real.</span><span class="sxs-lookup"><span data-stu-id="460b9-320">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="460b9-321">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="460b9-321">Office Suite</span></span>

- <span data-ttu-id="460b9-322">**Transforme la entrada de lápiz en formas, texto o matemáticas en PowerPoint para Office 365:** convierta la entrada de lápiz en forma libre a formas, textos o expresiones matemáticas de Office en un par de trazos.</span><span class="sxs-lookup"><span data-stu-id="460b9-322">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="460b9-323">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-323">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="460b9-326">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="460b9-326">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="460b9-327">Access</span><span class="sxs-lookup"><span data-stu-id="460b9-327">Access</span></span>

- <span data-ttu-id="460b9-328">Esta actualización corrige un problema por el que al usar un objeto de grabación de ADODB</span><span class="sxs-lookup"><span data-stu-id="460b9-328">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="460b9-329">en el código de VB, se puede notificar un error incorrectamente.</span><span class="sxs-lookup"><span data-stu-id="460b9-329">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="460b9-330">Las plantillas de Access ya no deberían causar errores en columnas de datos adjuntos en una base de datos.</span><span class="sxs-lookup"><span data-stu-id="460b9-330">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="460b9-331">Después de crear la instancia de una plantilla, ahora debería poder agregar un campo de datos adjuntos a la base de datos.</span><span class="sxs-lookup"><span data-stu-id="460b9-331">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="460b9-332">Esta actualización corrige un problema que puede hacer que Microsoft Access no identifique una Columna de identidad en una tabla vinculada de SQL Server, lo que puede provocar que las filas aparezcan como eliminadas de forma incorrecta.</span><span class="sxs-lookup"><span data-stu-id="460b9-332">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="460b9-333">Esta actualización corrige un problema en Microsoft Access que puede causar el error "La consulta está dañada" cuando se ejecuta una consulta de actualización o cuando se usa una instrucción UPDATE en SQL.</span><span class="sxs-lookup"><span data-stu-id="460b9-333">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="460b9-334">Excel</span><span class="sxs-lookup"><span data-stu-id="460b9-334">Excel</span></span>

- <span data-ttu-id="460b9-335">Acelere la carga de archivos que están disponibles en la carpeta de OneDrive local.</span><span class="sxs-lookup"><span data-stu-id="460b9-335">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="460b9-336">Se ha solucionado un problema por el que las funciones CUBEVALUE a veces daban un resultado incorrecto.</span><span class="sxs-lookup"><span data-stu-id="460b9-336">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="460b9-337">Resuelto un problema con la personalización de la cinta que no se cargaba al abrir el libro de trabajo incrustado.</span><span class="sxs-lookup"><span data-stu-id="460b9-337">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="460b9-338">Excel se bloqueaba en ciertos casos cuando se volvía a abrir un libro incrustado en Word o PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="460b9-338">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="460b9-339">Se ha corregido un problema por el que los comandos de comentario en el menú contextual no aparecían.</span><span class="sxs-lookup"><span data-stu-id="460b9-339">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="460b9-340">Se ha corregido el botón derecho en el menú de gráficos dinámicos para habilitar la opción de mostrar los detalles.</span><span class="sxs-lookup"><span data-stu-id="460b9-340">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="460b9-341">Se ha resuelto un problema que puede haber causado un bloqueo al buscar archivos recientes cuando no hay ningún libro de trabajo abierto.</span><span class="sxs-lookup"><span data-stu-id="460b9-341">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="460b9-342">Se ha corregido un problema que provocaba que, al hacer clic en un hipervínculo marcado en el propio libro, se ocultara dicho libro.</span><span class="sxs-lookup"><span data-stu-id="460b9-342">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="460b9-343">Cuando guarda como un archivo CSV, Excel podía combinar todas las columnas en una sola columna en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="460b9-343">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="460b9-344">Usar Range.ClearContents en un rango de una hoja protegida podía tardar más de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="460b9-344">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="460b9-345">Corregido un problema con la escala de texto en los controles de formulario cuando se mostraba en la Vista previa de impresión.</span><span class="sxs-lookup"><span data-stu-id="460b9-345">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="460b9-346">Las macros de VBA que interactúan con la cinta de opciones se pueden ejecutar con ScreenUpdating establecido en True inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="460b9-346">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="460b9-347">Se ha corregido un problema que hacía que Excel se bloqueara en ciertos casos después de copiar una hoja que contenía una tabla dinámica.</span><span class="sxs-lookup"><span data-stu-id="460b9-347">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="460b9-348">La apertura de archivos CSV tardaba más de lo esperado en algunas circunstancias.</span><span class="sxs-lookup"><span data-stu-id="460b9-348">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="460b9-349">Excel se bloqueaba en determinadas circunstancias al cambiar entre libros con diferentes niveles de zoom.</span><span class="sxs-lookup"><span data-stu-id="460b9-349">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="460b9-350">Se ha corregido un problema con VBA por el que escribir valores en un rango era más lento de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="460b9-350">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="460b9-351">En ocasiones, los datos copiados de una columna filtrada por color no se pegaban correctamente.</span><span class="sxs-lookup"><span data-stu-id="460b9-351">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="460b9-352">La apertura de un libro de trabajo con referencias a muchos otros libros de trabajo, especialmente con ventanas ocultas, era más lenta de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="460b9-352">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="460b9-353">Se ha corregido un problema por el que los enlaces externos no se actualizaban al rellenar (rellenar hacia abajo, rellenar en otros, etc.) si el libro de origen estaba cerrado.</span><span class="sxs-lookup"><span data-stu-id="460b9-353">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is& closed.</span></span>

- <span data-ttu-id="460b9-354">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="460b9-354">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="460b9-355">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="460b9-355">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="460b9-356">Se ha corregido un problema por el que la propiedad "Valor se cruza en" en el eje del gráfico cambiaba inesperadamente al guardar y volver a abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="460b9-356">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="460b9-357">Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta al guardar en SharePoint o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="460b9-357">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="460b9-358">Se ha mejorado el rendimiento al eliminar columnas con celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="460b9-358">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="460b9-359">Se ha corregido un problema por el que los nombres de las impresoras podrían repetirse en la lista de impresoras en el cuadro de diálogo Imprimir.</span><span class="sxs-lookup"><span data-stu-id="460b9-359">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="460b9-360">Se ha corregido un problema que hacía que el vínculo externo dejara de funcionar después de que se volviera a abrir el archivo si su ruta de acceso era demasiado larga.</span><span class="sxs-lookup"><span data-stu-id="460b9-360">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="460b9-361">Se ha corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.</span><span class="sxs-lookup"><span data-stu-id="460b9-361">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="460b9-362">Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.</span><span class="sxs-lookup"><span data-stu-id="460b9-362">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="460b9-363">Insertar una columna en una lista filtrada llevaba más tiempo de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="460b9-363">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="460b9-364">Se ha corregido un problema por el que algunos vínculos de un gráfico copiado y pegado usaban direcciones de unidad asignadas, en lugar de direcciones universales.</span><span class="sxs-lookup"><span data-stu-id="460b9-364">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="460b9-365">Se ha corregido un problema que producía el siguiente mensaje de error: "No se puede cerrar el libro de trabajo debido a que otro libro hace referencia al mismo". El mensaje aparecía si los complementos se cargaban en orden alfabético en lugar de en un orden especificado por el usuario.</span><span class="sxs-lookup"><span data-stu-id="460b9-365">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="460b9-366">Se ha corregido un problema que haría que un libro se ocultara al hacer clic en un hipervínculo a un lugar dentro de un libro ya abierto.</span><span class="sxs-lookup"><span data-stu-id="460b9-366">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="460b9-367">La apertura de un libro de trabajo con referencias a muchos otros libros de trabajo, especialmente con ventanas ocultas, era más lenta de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="460b9-367">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="460b9-368">El uso de Application.Evaluate de VBA no funcionaba para funciones definidas por el usuario en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="460b9-368">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="460b9-369">Se ha corregido un problema que algunos usuarios pudieron sufrir con objetos incrustados y vinculados (OLE).</span><span class="sxs-lookup"><span data-stu-id="460b9-369">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="460b9-370">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="460b9-370">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="460b9-371">Esta actualización corrige un problema que causaba que la barra de fórmulas mostrara texto en una fuente diferente a la esperada.</span><span class="sxs-lookup"><span data-stu-id="460b9-371">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="460b9-372">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="460b9-372">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="460b9-373">Corregimos un problema en el que al seleccionar una celda luego de desplazar, podía resultar en la selección de la celda incorrecta.</span><span class="sxs-lookup"><span data-stu-id="460b9-373">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="460b9-374">Los usuarios pueden encontrar un error al acceder a un rango con nombre oculto.</span><span class="sxs-lookup"><span data-stu-id="460b9-374">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="460b9-375">Excel puede tener problemas al editar un archivo protegido desde una red compartida no confiable.</span><span class="sxs-lookup"><span data-stu-id="460b9-375">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="460b9-376">La funcionalidad de texto a columna puede fallar en algunas localizaciones.</span><span class="sxs-lookup"><span data-stu-id="460b9-376">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="460b9-377">Se ha corregido un problema de rendimiento al crear gráficos a partir de plantillas.</span><span class="sxs-lookup"><span data-stu-id="460b9-377">Addresses a performance issue when creating charts from templates.</span></span>

- <span data-ttu-id="460b9-378">Se ha corregido un problema que causaba que algunos usuarios experimentasen bloqueos al convertir texto en columnas con celdas que tienen una matriz derramada.</span><span class="sxs-lookup"><span data-stu-id="460b9-378">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="460b9-379">El uso de un Range.Value y Range.Value2 (VBA) hacía que las fórmulas se escribieran como matrices dinámicas.</span><span class="sxs-lookup"><span data-stu-id="460b9-379">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

- <span data-ttu-id="460b9-380">Se ha corregido un problema por el que un símbolo @ que inicia una fórmula se considera un operador de intersección implícita.</span><span class="sxs-lookup"><span data-stu-id="460b9-380">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

- <span data-ttu-id="460b9-381">Se ha corregido un problema por el que las hojas de cálculo que contenían varias fórmulas con nombres definidos tardaban más en guardarse.</span><span class="sxs-lookup"><span data-stu-id="460b9-381">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="460b9-382">Este cambio evita un problema con ciertos controladores de gráficos Intel al aprovechar el procesamiento del software.</span><span class="sxs-lookup"><span data-stu-id="460b9-382">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="460b9-383">Se ha corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.</span><span class="sxs-lookup"><span data-stu-id="460b9-383">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="onenote"></a><span data-ttu-id="460b9-384">OneNote</span><span class="sxs-lookup"><span data-stu-id="460b9-384">OneNote</span></span>

- <span data-ttu-id="460b9-385">Mejora la sincronización y la estabilidad del servicio al ajustar temporalmente la frecuencia de sincronización en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="460b9-385">Improve sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="460b9-386">Mejora la sincronización y la estabilidad del servicio al diferir temporalmente la descarga de archivos e imágenes incrustados en los blocs de notas en línea hasta que el usuario navegue a la página en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="460b9-386">Improve sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="460b9-387">Mejora la sincronización y la estabilidad del servicio al deshabilitar temporalmente la papelera de reciclaje en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="460b9-387">Improve sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="460b9-388">Cuando un usuario intenta eliminar datos que normalmente se enviarían a la papelera de reciclaje, se le preguntará si prefiere conservarlos o eliminarlos forma permanente.</span><span class="sxs-lookup"><span data-stu-id="460b9-388">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="460b9-389">Mejora la sincronización y estabilidad de servicio mejoradas al reducir temporalmente el número y la frecuencia de sincronización de las páginas del historial de versiones en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="460b9-389">Improve sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="460b9-390">Muestra una notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="460b9-390">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="460b9-391">Mejora la sincronización y la estabilidad del servicio al reducir temporalmente el tamaño máximo de nuevos datos adjuntos insertados a 50 MB en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="460b9-391">Improve sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="460b9-392">Si los archivos superan este límite, los usuarios tendrán la opción de cargar el archivo a OneDrive e insertar un vínculo en OneNote.</span><span class="sxs-lookup"><span data-stu-id="460b9-392">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="460b9-393">Mejora la sincronización y la estabilidad del servicio al deshabilitar temporalmente la grabación de vídeo en la aplicación en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="460b9-393">Improve sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="460b9-394">La medida no afecta a los blocs de notas locales.</span><span class="sxs-lookup"><span data-stu-id="460b9-394">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="460b9-395">Localiza la notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="460b9-395">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="460b9-396">Outlook</span><span class="sxs-lookup"><span data-stu-id="460b9-396">Outlook</span></span>

- <span data-ttu-id="460b9-397">Se ha corregido un problema por el que la ventana del Editor de métodos de entrada (IME) se superponía al texto subyacente escrito mediante el IME cuando se usaban varios monitores con resoluciones diferentes.</span><span class="sxs-lookup"><span data-stu-id="460b9-397">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="460b9-398">Se ha corregido un problema que provocaba que los usuarios vean bloqueos ocasionales en Outlook.</span><span class="sxs-lookup"><span data-stu-id="460b9-398">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="460b9-399">Esto actualiza la lógica de bloqueo de adjuntos en Outlook para bloquear también los adjuntos de Python.</span><span class="sxs-lookup"><span data-stu-id="460b9-399">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="460b9-400">Se ha corregido un problema que provocaba que los complementos web accedieran a los mensajes administrados con derechos digitales.</span><span class="sxs-lookup"><span data-stu-id="460b9-400">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="460b9-401">Se ha corregido un problema que causaba que las citas o reuniones periódicas se mostraran en un momento incorrecto al tratar de cambiar la definición de una zona horaria.</span><span class="sxs-lookup"><span data-stu-id="460b9-401">Addresses an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="460b9-402">Cuando se utiliza la zona horaria de Brasilia en el año 2019, las reuniones y citas recurrentes se muestran en la franja horaria equivocada para el año 2020.</span><span class="sxs-lookup"><span data-stu-id="460b9-402">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="460b9-403">Este cambio es relevante para los clientes establecidos en la zona horaria de Brasilia o para las reuniones y citas establecidas en esa zona horaria.</span><span class="sxs-lookup"><span data-stu-id="460b9-403">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span><br><br><span data-ttu-id="460b9-404">Este cambio permite a Outlook reemplazar algunas opciones de configuración de zona horaria utilizadas por Outlook.</span><span class="sxs-lookup"><span data-stu-id="460b9-404">This change allows Outlook to override certain time zone settings used by Outlook.</span></span> <span data-ttu-id="460b9-405">Para invocar una invalidación de zona horaria, debe establecer una clave del registro para el usuario actual.</span><span class="sxs-lookup"><span data-stu-id="460b9-405">In order to invoke a time zone override you must set a registry key for the current user.</span></span> <span data-ttu-id="460b9-406">El nombre de la clave del registro debe coincidir con el nombre interno de la zona horaria.</span><span class="sxs-lookup"><span data-stu-id="460b9-406">The registry key name must match the internal name of the time zone.</span></span> <span data-ttu-id="460b9-407">El valor indica el año en el que se va a usar la regla de zona horaria en vez del año efectivo.</span><span class="sxs-lookup"><span data-stu-id="460b9-407">The value indicates the time zone rule's year to be used in place of the effective year.</span></span> <span data-ttu-id="460b9-408">Por ejemplo, el siguiente valor para reemplazar la clave del registro usará la regla de zona horaria de Brasil para el año 2020 como regla efectiva.</span><span class="sxs-lookup"><span data-stu-id="460b9-408">For example, the following registry key override value will use the Brazilia time zone rule for the year 2020 as the effective rule.</span></span> <span data-ttu-id="460b9-409">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span><span class="sxs-lookup"><span data-stu-id="460b9-409">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span></span> <span data-ttu-id="460b9-410">Hora estándar de Sudamérica"=dword:000007e4.</span><span class="sxs-lookup"><span data-stu-id="460b9-410">South America Standard Time"=dword:000007e4.</span></span>

- <span data-ttu-id="460b9-411">Se ha corregido un problema por el que los usuarios veían cambiar el campo de ubicación de las reuniones de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="460b9-411">Addresses an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="460b9-412">Se ha corregido un problema que provocaba que el campo Ubicación en las reuniones se actualizara de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="460b9-412">Addresses an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="460b9-413">Se ha corregido un problema que provocó que la ubicación de una reunión se volviera a añadir a la reunión de forma inesperada después de despejarla.</span><span class="sxs-lookup"><span data-stu-id="460b9-413">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="460b9-414">Se ha corregido un tema que causó que las comas en el campo de ubicación de una reunión se convirtieran en punto y coma.</span><span class="sxs-lookup"><span data-stu-id="460b9-414">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="460b9-415">Permite unirse a una reunión de Teams directamente a través del cliente nativo de Teams.</span><span class="sxs-lookup"><span data-stu-id="460b9-415">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="460b9-416">Se ha corregido un problema que provocaba que los usuarios con buzones en servidores de Exchange 2010 sufrieran problemas al agregar archivos adjuntos a elementos de calendario.</span><span class="sxs-lookup"><span data-stu-id="460b9-416">Addresses an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="460b9-417">Se ha corregido un problema que provocaba que los usuarios experimentaran problemas al responder a los mensajes firmados digitalmente.</span><span class="sxs-lookup"><span data-stu-id="460b9-417">Addresses an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="460b9-418">Se ha corregido un problema que provocaba que los usuarios no pudieran abrir algunas instancias de los elementos de calendario periódicos.</span><span class="sxs-lookup"><span data-stu-id="460b9-418">Addresses an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="460b9-419">Se ha corregido un problema que hacía que el encabezado de grupo se expandiera de forma inesperada en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="460b9-419">Addresses an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="460b9-420">Se ha corregido un problema que provocaba que el ancho del panel de carpetas cambiara de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="460b9-420">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="460b9-421">Se ha corregido un problema por el que Outlook no pudo habilitar consejos de directiva para la Protección de pérdida de datos para usuarios que pagaron por el servicio con planes M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="460b9-421">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="460b9-422">Se ha corregido un problema por el que los usuarios notaban un retraso evidente al interactuar con sus carpetas de buzón mediante métodos abreviados de teclado.</span><span class="sxs-lookup"><span data-stu-id="460b9-422">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="460b9-423">Se ha corregido un problema que podría resultar en un choque al ver el mismo elemento en varias ventanas.</span><span class="sxs-lookup"><span data-stu-id="460b9-423">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="460b9-424">Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al actualizar sus reglas en Outlook.</span><span class="sxs-lookup"><span data-stu-id="460b9-424">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="460b9-425">Se ha corregido un problema que causaba una pérdida de memoria en sesiones de Outlook muy largas.</span><span class="sxs-lookup"><span data-stu-id="460b9-425">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="460b9-426">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.</span><span class="sxs-lookup"><span data-stu-id="460b9-426">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="460b9-427">Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al abrir el cuadro de diálogo de Reglas.</span><span class="sxs-lookup"><span data-stu-id="460b9-427">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="460b9-428">Se ha corregido un problema por el que la opción para deshabilitar el resaltado de elementos marcados no funcionaba en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="460b9-428">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="460b9-429">Se ha corregido un problema que provocaba que los usuarios vieran mensajes enviados inesperadamente al presionar la tecla "S" después de cerrar el panel del comprobador de accesibilidad.</span><span class="sxs-lookup"><span data-stu-id="460b9-429">Addresses an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="460b9-430">Se ha corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.</span><span class="sxs-lookup"><span data-stu-id="460b9-430">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="460b9-431">Se ha corregido un problema que provocaba que los usuarios experimentaran un error al cancelar la configuración de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="460b9-431">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="460b9-432">Se ha corregido un problema por el que Outlook sincronizaba inesperadamente todo el correo, incluso cuando el deslizador de sincronización estaba configurado en un ajuste menor.</span><span class="sxs-lookup"><span data-stu-id="460b9-432">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="460b9-433">Se ha corregido un problema que provocaba que los usuarios con el Tema negro vieran texto blanco sobre un fondo blanco en el desplegable "De".</span><span class="sxs-lookup"><span data-stu-id="460b9-433">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="460b9-434">Se ha corregido un problema que provocaba que los usuarios sufrieran un bloqueo durante la creación del perfil.</span><span class="sxs-lookup"><span data-stu-id="460b9-434">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="460b9-435">Se ha corregido un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "OK" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="460b9-435">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="460b9-436">Se ha corregido un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "OK" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="460b9-436">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="460b9-437">Se ha corregido un problema que provocaba que las aplicaciones de terceros no pudiesen enviar correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="460b9-437">Addresses an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="460b9-438">Se ha corregido un problema que provocaba que las categorías desapareciesen en ocasiones de los mensajes de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="460b9-438">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="460b9-439">Se ha corregido un problema que provocaba que los usuarios de Outlook en sistemas operativos de servidor vieran el error: "Estado del antivirus: no válido.</span><span class="sxs-lookup"><span data-stu-id="460b9-439">Addresses an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="460b9-440">Esta versión de Windows admite la detección del antivirus, pero no se encontró ninguno" a pesar de tener el antivirus correctamente configurado.</span><span class="sxs-lookup"><span data-stu-id="460b9-440">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

- <span data-ttu-id="460b9-441">Se ha corregido un problema que provocaba que los delegados viesen distintas jerarquías de carpetas en diferentes equipos para los buzones compartidos.</span><span class="sxs-lookup"><span data-stu-id="460b9-441">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="460b9-442">Se ha corregido un problema que causaba que los delegados reciban un error al editar una cita de calendario existente en el calendario de un administrador.</span><span class="sxs-lookup"><span data-stu-id="460b9-442">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="460b9-443">Se ha corregido un problema que provocaba que los usuarios con la configuración de emulación de explorador incorrecta no pudieran completar el mensaje de autenticación de Gmail.</span><span class="sxs-lookup"><span data-stu-id="460b9-443">Addresses an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="460b9-444">Se ha corregido un problema que causaba que faltara la opción "Permitir reenvío" en las "Opciones de respuesta" de la reunión de calendario compartida cuando NO está marcada Descargar carpeta compartida.</span><span class="sxs-lookup"><span data-stu-id="460b9-444">Addresses an issue that caused the " Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="460b9-445">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al intentar abrir archivos .msg y .oft después de una actualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="460b9-445">Addresses an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="460b9-446">Se ha corregido un problema que causaba que los usuarios experimentaran ocasionalmente un bloqueo al usar el botón X de su ratón.</span><span class="sxs-lookup"><span data-stu-id="460b9-446">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="460b9-447">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al seleccionar determinados resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="460b9-447">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="460b9-448">Se ha corregido un problema que hizo que el botón "Guardar en la nube" faltara en las herramientas de adjuntos.</span><span class="sxs-lookup"><span data-stu-id="460b9-448">Addresses an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="460b9-449">Este cambio restaura la capacidad de ver sujetos de varias líneas en el encabezado del mensaje.</span><span class="sxs-lookup"><span data-stu-id="460b9-449">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="460b9-450">Se ha corregido un problema que causaba que los usuarios experimentaran un bloqueo cuando dos complementos agregan un botón al mismo grupo de la cinta de opciones.</span><span class="sxs-lookup"><span data-stu-id="460b9-450">Addresses an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="460b9-451">Se ha corregido un problema que provocaba que los vínculos no se agreguen a los correos electrónicos con el permiso predeterminado incorrecto de espacio empresarial cuando el permiso predeterminado de espacio empresarial se configura como "cualquiera".</span><span class="sxs-lookup"><span data-stu-id="460b9-451">Addresses an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as "anyone".</span></span>

- <span data-ttu-id="460b9-452">Se ha corregido un problema que provocaba que los usuarios no pudieran dirigir mensajes de correo electrónico a una lista de distribución personal.</span><span class="sxs-lookup"><span data-stu-id="460b9-452">Addresses an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="460b9-453">Se ha corregido un problema que hacía que los usuarios vieran el truncamiento del cuerpo del mensaje al reenviar mensajes HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="460b9-453">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="460b9-454">Se ha corregido un problema con la selección del algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="460b9-454">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="460b9-455">Se ha corregido un problema que podía impedir que los archivos se guardaran en una ubicación de WebDAV.</span><span class="sxs-lookup"><span data-stu-id="460b9-455">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="460b9-456">Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.</span><span class="sxs-lookup"><span data-stu-id="460b9-456">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="460b9-457">Se ha corregido un problema que provocaba que el cuerpo de un mensaje NDR cambiara de Unicode a ASCII después de editar el asunto.</span><span class="sxs-lookup"><span data-stu-id="460b9-457">Addresses an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="460b9-458">Se ha corregido un problema que hacía que los usuarios observaran una pérdida de memoria en el proceso de Outlook.</span><span class="sxs-lookup"><span data-stu-id="460b9-458">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="460b9-459">Corrige un problema que provocaba que los usuarios vieran mensajes de correo electrónico enviados a una dirección que no coincidía con la dirección SMTP mostrada en determinadas circunstancias.</span><span class="sxs-lookup"><span data-stu-id="460b9-459">Addresses an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="460b9-460">Se ha corregido un problema que provocaba que el cuadro de búsqueda estuviera mal alineado en modo de PPP alto.</span><span class="sxs-lookup"><span data-stu-id="460b9-460">Addresses an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="460b9-461">Se ha corregido un problema por el que los usuarios experimentan bloqueos en Outlook al recuperar la configuración de la nube.</span><span class="sxs-lookup"><span data-stu-id="460b9-461">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="460b9-462">Se ha corregido un problema que causó un bloqueo en la experiencia de los comentarios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="460b9-462">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="460b9-463">Se ha corregido un problema que provocaba que los usuarios vean bloqueos ocasionales en Outlook.</span><span class="sxs-lookup"><span data-stu-id="460b9-463">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="460b9-464">Se ha corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.</span><span class="sxs-lookup"><span data-stu-id="460b9-464">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="460b9-465">Se ha corregido un problema que provocaba que los usuarios sufrieran un bloqueo durante la creación del perfil.</span><span class="sxs-lookup"><span data-stu-id="460b9-465">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="460b9-466">Se ha corregido un problema que provocaba que los usuarios vean bloqueos ocasionales en Outlook.</span><span class="sxs-lookup"><span data-stu-id="460b9-466">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="460b9-467">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="460b9-467">PowerPoint</span></span>

- <span data-ttu-id="460b9-468">Se ha corregido un problema que podía bloquear el equipo al usar el menú contextual en comentarios PPT heredados.</span><span class="sxs-lookup"><span data-stu-id="460b9-468">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

- <span data-ttu-id="460b9-469">Se ha mejorado un escenario de copiar y pegar: al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.</span><span class="sxs-lookup"><span data-stu-id="460b9-469">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="460b9-470">Se ha corregido un problema para retransmitir la mensajería correcta a los usuarios que abren una copia de un archivo que ha mejorado los comentarios.</span><span class="sxs-lookup"><span data-stu-id="460b9-470">Fixes an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="project"></a><span data-ttu-id="460b9-471">Project</span><span class="sxs-lookup"><span data-stu-id="460b9-471">Project</span></span>

- <span data-ttu-id="460b9-472">Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.</span><span class="sxs-lookup"><span data-stu-id="460b9-472">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="460b9-473">Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="460b9-473">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="460b9-474">Corregido un problema que hace que el evento ProjectBeforeTaskChange no detecte cuándo se ha desactivado o activado una tarea mediante el botón Desactivar.</span><span class="sxs-lookup"><span data-stu-id="460b9-474">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="460b9-475">Corregido un problema por el que Project puede bloquearse al guardar proyectos creados con versiones anteriores de Project.</span><span class="sxs-lookup"><span data-stu-id="460b9-475">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="460b9-476">Identificamos un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de solo lectura</span><span class="sxs-lookup"><span data-stu-id="460b9-476">Identified an issue where users could get several messages when opening a read-only project</span></span>

- <span data-ttu-id="460b9-477">Se ha corregido un problema por el que el 100 % de las tareas de tipo duración fija podían tener un cálculo del porcentaje incorrecto con menos del 100% completado.</span><span class="sxs-lookup"><span data-stu-id="460b9-477">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="460b9-478">Word</span><span class="sxs-lookup"><span data-stu-id="460b9-478">Word</span></span>

- <span data-ttu-id="460b9-479">Se ha corregido un problema que causaba que los usuarios experimentaran ocasionalmente un bloqueo al usar el botón X de su ratón.</span><span class="sxs-lookup"><span data-stu-id="460b9-479">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="460b9-480">Se ha corregido un problema por el que la alineación de las palabras de un documento se descomponía al intentar editar después de imprimir con la impresión rápida.</span><span class="sxs-lookup"><span data-stu-id="460b9-480">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="460b9-481">Corregido un problema con el ajuste de texto en una tabla.</span><span class="sxs-lookup"><span data-stu-id="460b9-481">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="460b9-482">Corregido un problema donde al insertar líneas horizontales no eran más cortas ni centradas.</span><span class="sxs-lookup"><span data-stu-id="460b9-482">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>

- <span data-ttu-id="460b9-483">El organizador de bloques de creación puede mostrar una alerta no válida: "Ha modificado estilos, bloques de creación".</span><span class="sxs-lookup"><span data-stu-id="460b9-483">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

- <span data-ttu-id="460b9-484">Se ha corregido un problema de coautoría si se habilita la Directiva FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="460b9-484">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="460b9-485">Se ha corregido un problema en el que Word QuickPart no funciona al agregar un campo de búsqueda cuyo nombre se ha cambiado.</span><span class="sxs-lookup"><span data-stu-id="460b9-485">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

- <span data-ttu-id="460b9-486">Se ha corregido un problema al combinar dos documentos en uno.</span><span class="sxs-lookup"><span data-stu-id="460b9-486">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="460b9-487">Se ha corregido un problema con la característica Comparación para los documentos protegidos para la edición.</span><span class="sxs-lookup"><span data-stu-id="460b9-487">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="460b9-488">Esta actualización corrige un problema en Microsoft Word por el que el texto que supera los 255 caracteres insertados durante la aplicación de una etiqueta de confidencialidad no se pudiese identificar y quitar posteriormente cambiando o quitando la etiqueta si la directiva de etiqueta aplicó un encabezado, un pie de página o una marca de agua.</span><span class="sxs-lookup"><span data-stu-id="460b9-488">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

### <a name="office-suite"></a><span data-ttu-id="460b9-489">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="460b9-489">Office Suite</span></span>

- <span data-ttu-id="460b9-490">Se ha corregido un problema en el que los usuarios puedan experimentar demasiado uso de la red y la CPU durante la coautoría en archivos de PowerPoint grandes.</span><span class="sxs-lookup"><span data-stu-id="460b9-490">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="460b9-491">Esta es una corrección para que la aplicación de Project no bloquee la red cuando el archivo se almacena en caché en el cliente.</span><span class="sxs-lookup"><span data-stu-id="460b9-491">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>


- <span data-ttu-id="460b9-492">Se ha resuelto este problema mediante la actualización de los nombres de canal en el backstage con los nuevos nombres de canal en la bifurcación de enero de 2020.</span><span class="sxs-lookup"><span data-stu-id="460b9-492">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="460b9-493">Se ha corregido este problema y en adelante, si un dispositivo se administra mediante directiva, no llamará a la API de audiencia de DMS.</span><span class="sxs-lookup"><span data-stu-id="460b9-493">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="460b9-494">Se ha corregido un problema en el que había una eliminación incompleta al agregar y quitar aplicaciones en una sola transacción.</span><span class="sxs-lookup"><span data-stu-id="460b9-494">We have resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="460b9-495">Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.</span><span class="sxs-lookup"><span data-stu-id="460b9-495">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="460b9-496">Corrige un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.</span><span class="sxs-lookup"><span data-stu-id="460b9-496">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="460b9-497">Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.</span><span class="sxs-lookup"><span data-stu-id="460b9-497">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="460b9-498">Hemos modificado la versión AppV51 para solucionar una regresión de la AppV51 anterior.</span><span class="sxs-lookup"><span data-stu-id="460b9-498">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="460b9-499">Hemos resuelto el problema por el que una operación interna producía una excepción en caso de error en lugar de registrarlo y continuar.</span><span class="sxs-lookup"><span data-stu-id="460b9-499">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="460b9-500">Los usuarios afectados ya no serán bloqueados para recibir actualizaciones.</span><span class="sxs-lookup"><span data-stu-id="460b9-500">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="460b9-501">Nuestro equipo ha agregado compatibilidad con clientes para informar la telemetría en los dominios de la red CDN en semianual Enterprise Preview.</span><span class="sxs-lookup"><span data-stu-id="460b9-501">Our team has added client support for reporting telemetry on the Office CDN domains in Semi-Annual Enterprise Preview.</span></span>

- <span data-ttu-id="460b9-502">Este cambio resuelve problemas con adaptadores gráficos que aprovechan la GPU integrada de Intel.</span><span class="sxs-lookup"><span data-stu-id="460b9-502">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="460b9-503">Este cambio garantiza que el contorno Esbozado funcione correctamente en la cinta de opciones.</span><span class="sxs-lookup"><span data-stu-id="460b9-503">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="460b9-504">Se ha corregido un problema al abrir archivos de ubicaciones locales con algunas configuraciones de proxy específicas.</span><span class="sxs-lookup"><span data-stu-id="460b9-504">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="460b9-505">Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.</span><span class="sxs-lookup"><span data-stu-id="460b9-505">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="460b9-506">Se ha corregido un problema que elimina bloqueos durante las sesiones de entrega de Office y se ha mejorado la fiabilidad de la experiencia del usuario.</span><span class="sxs-lookup"><span data-stu-id="460b9-506">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>

- <span data-ttu-id="460b9-507">Este error actualiza el extremo de la URL del servicio de configuración mejorada (ECS).</span><span class="sxs-lookup"><span data-stu-id="460b9-507">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="460b9-508">Llamar a este punto de conexión más reciente tiene una tasa de éxito superior para capturar desde ECS.</span><span class="sxs-lookup"><span data-stu-id="460b9-508">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

- <span data-ttu-id="460b9-509">Esta actualización corrige un problema en el que con Microsoft Outlook no muestra la etiqueta de confidencialidad actual al ver o redactar mensajes.</span><span class="sxs-lookup"><span data-stu-id="460b9-509">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="460b9-510">Corrige un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.</span><span class="sxs-lookup"><span data-stu-id="460b9-510">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

- <span data-ttu-id="460b9-511">Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="460b9-511">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="460b9-512">El host de Office se bloqueaba en Windows, cuando se activaba un complemento si la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth estaba establecida en cero.</span><span class="sxs-lookup"><span data-stu-id="460b9-512">The office host was crashing in windows, when an add-in is being activated while the registry key  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="460b9-513">Este cambio arreglaría el problema.</span><span class="sxs-lookup"><span data-stu-id="460b9-513">This change would fix this issue.</span></span>

- <span data-ttu-id="460b9-514">Se ha corregido un problema de bloqueo con el host de Office en Windows cuando se activa un complemento mientras el valor del registro TabProcGrowth era del tipo REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="460b9-514">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="460b9-515">Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.</span><span class="sxs-lookup"><span data-stu-id="460b9-515">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="460b9-516">Se ha corregido el problema por el que Access y Publisher podrían no iniciarse correctamente en función de los idiomas que se hubieran instalado.</span><span class="sxs-lookup"><span data-stu-id="460b9-516">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)





[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-july-14"></a><span data-ttu-id="460b9-519">Versión 1908: 14 de julio</span><span class="sxs-lookup"><span data-stu-id="460b9-519">Version 1908: July 14</span></span>
<span data-ttu-id="460b9-520">*Versión 1908 (Compilación 11929.20904)*</span><span class="sxs-lookup"><span data-stu-id="460b9-520">*Version 1908 (Build 11929.20904)*</span></span>

<span data-ttu-id="460b9-521">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-521">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="460b9-523">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="460b9-523">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="460b9-524">Access</span><span class="sxs-lookup"><span data-stu-id="460b9-524">Access</span></span>

- <span data-ttu-id="460b9-525">Esta actualización corrige un problema en el que la agregación como la suma puede truncar el resultado a un valor entero.</span><span class="sxs-lookup"><span data-stu-id="460b9-525">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="460b9-526">Esta actualización corrige un problema por el que una consulta de Unión que incluye referencias a tablas remotas (por ejemplo, tablas de SQL Server) puede hacer que Access se cierre y se reinicie.</span><span class="sxs-lookup"><span data-stu-id="460b9-526">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="460b9-527">Esta actualización corrige un problema en Microsoft Access que puede causar el error "La consulta está dañada" cuando se ejecuta una consulta de actualización o cuando se usa una instrucción UPDATE en SQL.</span><span class="sxs-lookup"><span data-stu-id="460b9-527">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="460b9-528">Excel</span><span class="sxs-lookup"><span data-stu-id="460b9-528">Excel</span></span>

- <span data-ttu-id="460b9-529">La información clave en holandés para el título del documento ha sido cambiada a Alt-G.</span><span class="sxs-lookup"><span data-stu-id="460b9-529">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="460b9-530">Se ha corregido un problema en Excel en el que las macros asignadas a formas o controles de formularios podían mostrar un mensaje de error incorrecto o funcionar en intervalos de destino incorrectos.</span><span class="sxs-lookup"><span data-stu-id="460b9-530">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="460b9-531">Se resolvió un problema con buscar y reemplazar ese cambio donde el foco estaba en el diálogo después de encontrar el primer elemento.</span><span class="sxs-lookup"><span data-stu-id="460b9-531">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="460b9-532">Esto corrige un problema por el cual al cambiar la forma en que se ordena y actualiza una tabla dinámica mientras se está en una sesión de co autoría con otros usuarios se podía provocar un bloqueo.</span><span class="sxs-lookup"><span data-stu-id="460b9-532">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="460b9-533">Arreglamos un problema cuando el filtro de una tabla dinámica OLAP se estableció en un valor que se había eliminado del cubo.</span><span class="sxs-lookup"><span data-stu-id="460b9-533">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="460b9-534">Esta actualización corrige un problema que provoca un error siempre que se utilizaba VBA para agregar una imagen al encabezado o pie de página de un gráfico.</span><span class="sxs-lookup"><span data-stu-id="460b9-534">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="460b9-535">Se ha corregido un problema que podría haber provocado que los gráficos de líneas de dispersión no se representaran correctamente al cambiar la colección de series</span><span class="sxs-lookup"><span data-stu-id="460b9-535">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span>

- <span data-ttu-id="460b9-536">Se han corregido los colores que se usan en las vistas previas al insertar gráficos con plantillas de gráficos.</span><span class="sxs-lookup"><span data-stu-id="460b9-536">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="460b9-537">Se resolvió un problema que causó que los gráficos de cascada y embudo se desincronizara con las tablas cuando se insertaban o eliminaban celdas.</span><span class="sxs-lookup"><span data-stu-id="460b9-537">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="460b9-538">Se ha corregido un problema de conflicto de fusión en Excel que hacía que los usuarios tuvieran que volver a abrir el libro de trabajo para elegir los cambios.</span><span class="sxs-lookup"><span data-stu-id="460b9-538">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="460b9-539">Se resolvió un problema que causaba un error de tiempo de ejecución de la macro que activaba las ventanas minimizadas.</span><span class="sxs-lookup"><span data-stu-id="460b9-539">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="460b9-540">Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.</span><span class="sxs-lookup"><span data-stu-id="460b9-540">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="460b9-541">Se resolvió un problema que causaba que las operaciones de cortar y pegar junto a una mesa fallaran cuando se co autoría con otros.</span><span class="sxs-lookup"><span data-stu-id="460b9-541">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="460b9-542">Se resolvió un problema que causaba interrupciones de co autoría cuando se cambiaban las propiedades personalizadas con macros en ejecución.</span><span class="sxs-lookup"><span data-stu-id="460b9-542">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="460b9-543">Hubo un problema en el que no se podían seleccionar elementos del cuadro combinado de un formulario de WPF (Windows Presentation Foundation) que fue abierto por un complemento.</span><span class="sxs-lookup"><span data-stu-id="460b9-543">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="460b9-544">Se ha resuelto un problema que puede haber causado un bloqueo al buscar archivos recientes cuando no hay ningún libro de trabajo abierto.</span><span class="sxs-lookup"><span data-stu-id="460b9-544">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="460b9-545">Se ha corregido un problema que hacía que el borde de un control de cuadro de grupo no estuviera visible en la vista previa de impresión o al imprimirlo.</span><span class="sxs-lookup"><span data-stu-id="460b9-545">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="460b9-546">Se ha corregido un problema por el que algunos usuarios podían haber experimentado múltiples ventanas emergentes cuando los enlaces externos estaban presentes en el libro de trabajo.</span><span class="sxs-lookup"><span data-stu-id="460b9-546">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="460b9-547">Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al usar una macro de VBA para borrar el contenido de un rango.</span><span class="sxs-lookup"><span data-stu-id="460b9-547">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="460b9-548">Se ha corregido un problema con VBA por el que escribir valores en un rango era más lento de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="460b9-548">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="460b9-549">Se ha corregido un problema por el que la propiedad "Valor se cruza en" en el eje del gráfico cambiaba inesperadamente al guardar y volver a abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="460b9-549">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="460b9-550">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="460b9-550">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="460b9-551">Se ha corregido un problema que provocaba un rendimiento lento al eliminar columnas que contenían celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="460b9-551">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="460b9-552">Se ha corregido un problema con la escala de texto en los controles de formulario cuando se mostraba la Vista previa de impresión.</span><span class="sxs-lookup"><span data-stu-id="460b9-552">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="460b9-553">Cuando se copian datos filtrados por colores en una columna con un ancho diferente, los valores no se pegan.</span><span class="sxs-lookup"><span data-stu-id="460b9-553">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="460b9-554">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="460b9-554">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="460b9-555">Se ha corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.</span><span class="sxs-lookup"><span data-stu-id="460b9-555">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="460b9-556">Se ha corregido un problema que provocaba que, al hacer clic en un hipervínculo marcado en el propio libro, se ocultara dicho libro.</span><span class="sxs-lookup"><span data-stu-id="460b9-556">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="460b9-557">Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.</span><span class="sxs-lookup"><span data-stu-id="460b9-557">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="460b9-558">La funcionalidad de Texto a columna puede fallar en algunas configuraciones regionales.</span><span class="sxs-lookup"><span data-stu-id="460b9-558">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="460b9-559">Es posible que los usuarios vean un error si acceden a un rango con nombre oculto.</span><span class="sxs-lookup"><span data-stu-id="460b9-559">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="460b9-560">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="460b9-560">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="460b9-561">Se ha corregido un problema por el que el tamaño de archivo de las imágenes en los encabezados del gráfico aumentaba cuando se guardaba el libro que contenía el gráfico.</span><span class="sxs-lookup"><span data-stu-id="460b9-561">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>

- <span data-ttu-id="460b9-562">Problema de rendimiento con las Funciones Asincrónicas Definidas por el Usuario que hacía que se ejecutaran sincrónicamente.</span><span class="sxs-lookup"><span data-stu-id="460b9-562">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="460b9-563">Mejoras significativas en el rendimiento de la eliminación de columnas con celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="460b9-563">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="460b9-564">Se resolvió un problema en el que la selección de una celda después del desplazamiento podía dar lugar a que se seleccionara la celda incorrecta.</span><span class="sxs-lookup"><span data-stu-id="460b9-564">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="460b9-565">Se ha resuelto un problema en el que la función de búsqueda puede devolver un error.</span><span class="sxs-lookup"><span data-stu-id="460b9-565">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="460b9-566">Se ha corregido un problema que provoca la corrupción de caracteres DBCS en los libros con referencias cruzadas manteniendo los rangos de selección sincronizados con el libro con referencias cruzadas.</span><span class="sxs-lookup"><span data-stu-id="460b9-566">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="460b9-567">Se ha corregido un problema en el que los controles de casilla podían reducirse al usar el autoajuste para ajustar el alto de fila.</span><span class="sxs-lookup"><span data-stu-id="460b9-567">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>

- <span data-ttu-id="460b9-568">Problema de rendimiento bajo al hacer clic en el botón Color de fuente cuando un archivo tiene un formato condicional extenso.</span><span class="sxs-lookup"><span data-stu-id="460b9-568">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="460b9-569">Se ha corregido un problema por el que el área de impresión en la vista previa de impresión no era correcta.</span><span class="sxs-lookup"><span data-stu-id="460b9-569">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="460b9-570">Excel puede tener problemas al editar un archivo protegido desde una red compartida no confiable.</span><span class="sxs-lookup"><span data-stu-id="460b9-570">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="460b9-571">Hemos mejorado significativamente el rendimiento del filtrado por color.</span><span class="sxs-lookup"><span data-stu-id="460b9-571">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="460b9-572">Se ha resuelto un problema por el que los libros de trabajo creados en versiones anteriores de Office podían hacer que Excel se colgara al abrirlos en las versiones actuales de Office.</span><span class="sxs-lookup"><span data-stu-id="460b9-572">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="460b9-573">Se habilitaron más de 16 complementos para que se muestren al navegar en el administrador de complementos.</span><span class="sxs-lookup"><span data-stu-id="460b9-573">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="460b9-574">Se ha corregido un problema que impedía que los hipervínculos se pegaran en algunas hojas protegidas.</span><span class="sxs-lookup"><span data-stu-id="460b9-574">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="460b9-575">Este cambio evita un problema con ciertos controladores de gráficos Intel al aprovechar el procesamiento del software.</span><span class="sxs-lookup"><span data-stu-id="460b9-575">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="460b9-576">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="460b9-576">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="460b9-577">Esta actualización corrige un error por el cual los documentos de Office pueden fallar al subirlos a OneDrive para la Empresa con el mensaje "Error al cargar".</span><span class="sxs-lookup"><span data-stu-id="460b9-577">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="460b9-578">Corregir problema en la característica Ideas de Excel, error al cargar el complemento haciendo clic en el botón Ideas en el cliente Win32.</span><span class="sxs-lookup"><span data-stu-id="460b9-578">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span> 

### <a name="onenote"></a><span data-ttu-id="460b9-579">OneNote</span><span class="sxs-lookup"><span data-stu-id="460b9-579">OneNote</span></span>

- <span data-ttu-id="460b9-580">Localiza la notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="460b9-580">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="460b9-581">Outlook</span><span class="sxs-lookup"><span data-stu-id="460b9-581">Outlook</span></span>

- <span data-ttu-id="460b9-582">Los vínculos de cid:image de los mensajes de Outlook ahora se pueden romper correctamente cuando se solicite.</span><span class="sxs-lookup"><span data-stu-id="460b9-582">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="460b9-583">Se ha corregido un problema que causaba que los usuarios que actualizaban su buzón de la autenticación básica a la moderna, terminaban con una cuenta incorrecta asociada a su perfil de Outlook.</span><span class="sxs-lookup"><span data-stu-id="460b9-583">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="460b9-584">Se ha corregido un problema que hacía que los complementos web accedieran a los mensajes de la administración de derechos digitales cuando no deberían hacerlo.</span><span class="sxs-lookup"><span data-stu-id="460b9-584">Addresses an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="460b9-585">Se ha corregido un problema que causó que las URLS de enlace simple no se mostraran en algunos enlaces seguros.</span><span class="sxs-lookup"><span data-stu-id="460b9-585">Addresses an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="460b9-586">Esto actualiza la lógica de bloqueo de adjuntos en Outlook para bloquear también los adjuntos de Python.</span><span class="sxs-lookup"><span data-stu-id="460b9-586">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="460b9-587">Corrige un problema que causaba que un subconjunto de usuarios de POP3 viesen todos los correos electrónicos como texto sin formato, independientemente de la configuración.</span><span class="sxs-lookup"><span data-stu-id="460b9-587">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="460b9-588">Esta corrección restaurará la vista de los mensajes con formato HTML.</span><span class="sxs-lookup"><span data-stu-id="460b9-588">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="460b9-589">Se ha corregido un problema que hacía que los usuarios experimentaran un error de permiso al copiar elementos de su calendario principal a un calendario de grupo.</span><span class="sxs-lookup"><span data-stu-id="460b9-589">Addresses an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="460b9-590">Se ha corregido un problema que hacía que los usuarios no pudieran acceder a las sugerencias de ubicación a través de un lector de pantalla.</span><span class="sxs-lookup"><span data-stu-id="460b9-590">Addresses an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="460b9-591">Se ha corregido un problema por el que los usuarios notaban un retraso evidente al interactuar con sus carpetas de buzón mediante métodos abreviados de teclado.</span><span class="sxs-lookup"><span data-stu-id="460b9-591">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="460b9-592">Se ha corregido un problema que causaba una pérdida de memoria en sesiones de Outlook muy largas.</span><span class="sxs-lookup"><span data-stu-id="460b9-592">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="460b9-593">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.</span><span class="sxs-lookup"><span data-stu-id="460b9-593">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="460b9-594">Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al abrir el cuadro de diálogo de Reglas.</span><span class="sxs-lookup"><span data-stu-id="460b9-594">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="460b9-595">Se ha corregido un problema que haría que los usuarios experimentaran un bloqueo en Outlook al interactuar con ciertos vínculos seguros.</span><span class="sxs-lookup"><span data-stu-id="460b9-595">Addresses an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="460b9-596">Se ha corregido un problema que causaba ambigüedad para los administradores sobre si un delegado ya había respondido a una convocatoria de reunión determinada.</span><span class="sxs-lookup"><span data-stu-id="460b9-596">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="460b9-597">Se ha corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.</span><span class="sxs-lookup"><span data-stu-id="460b9-597">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="460b9-598">Se ha corregido un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "OK" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="460b9-598">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="460b9-599">Este cambio permite a los administradores habilitar una política para preferir el correo electrónico de la cuenta proporcionada en los avisos de autorización de AutoDiscover sobre el UPN.</span><span class="sxs-lookup"><span data-stu-id="460b9-599">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="460b9-600">De forma predeterminada, detección automática prefiere el UPN de la cuenta, cuando está disponible.</span><span class="sxs-lookup"><span data-stu-id="460b9-600">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="460b9-601">Se ha corregido un problema que provocaba que los usuarios vieran un error en la búsqueda con grupos modernos.</span><span class="sxs-lookup"><span data-stu-id="460b9-601">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="460b9-602">Se ha corregido un problema que causaba que los usuarios de Outlook se quedaran atascados en el estado "Necesita contraseña" en ciertos escenarios.</span><span class="sxs-lookup"><span data-stu-id="460b9-602">Addresses an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="460b9-603">Se ha corregido un problema que provocaba que los usuarios experimentaran errores de sincronización al procesar mensajes de conflicto.</span><span class="sxs-lookup"><span data-stu-id="460b9-603">Addresses an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="460b9-604">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al abrir archivos .msg y .oft después de aplicar una actualización reciente de Windows.</span><span class="sxs-lookup"><span data-stu-id="460b9-604">Addresses an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="460b9-605">Se ha corregido un problema que provocaba que los usuarios experimentaran un error en la pantalla de "carga del perfil" al iniciar Outlook.</span><span class="sxs-lookup"><span data-stu-id="460b9-605">Addresses an issue that caused users to experience a hang at the "Loading Profile" screen when Outlook is starting up.</span></span>

- <span data-ttu-id="460b9-606">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al seleccionar determinados resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="460b9-606">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="460b9-607">Se ha corregido un problema que hizo que el botón "Guardar en la nube" faltara en las herramientas de datos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="460b9-607">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="460b9-608">De forma predeterminada, las etiquetas de directivas de retención muestran el período de tiempo de retención entre paréntesis.</span><span class="sxs-lookup"><span data-stu-id="460b9-608">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="460b9-609">Esto proporciona una clave del registro para permitir que los administradores especifiquen que solo se debería mostrar el nombre de la directiva.</span><span class="sxs-lookup"><span data-stu-id="460b9-609">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="460b9-610">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = predeterminado 1 = solo se mostrará el PolicyName para el texto de la política de retención.</span><span class="sxs-lookup"><span data-stu-id="460b9-610">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

- <span data-ttu-id="460b9-611">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al cerrar Outlook.</span><span class="sxs-lookup"><span data-stu-id="460b9-611">Addresses an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="460b9-612">Se ha corregido un problema que provocaba que los clientes vieran una lista de salas vacías en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="460b9-612">Addresses an issue that caused customers to see an empty room list in some scenarios.</span></span>

- <span data-ttu-id="460b9-613">Se ha corregido un problema que provocaba que los usuarios viesen bloqueos intermitentes al cambiar de vista.</span><span class="sxs-lookup"><span data-stu-id="460b9-613">Addresses an issue that caused users to see intermittent crashes when changing views.</span></span>

- <span data-ttu-id="460b9-614">Corrige un problema que provocaba que los usuarios tuvieran problemas al intentar sincronizar carpetas del calendario compartido con el OST, lo que producía errores en los permisos al tratar de interactuar con estas carpetas.</span><span class="sxs-lookup"><span data-stu-id="460b9-614">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>

- <span data-ttu-id="460b9-615">Se ha corregido un problema que causaba que los usuarios sufrieran un error al visualizar más de 30 calendarios en un entorno Citrix.</span><span class="sxs-lookup"><span data-stu-id="460b9-615">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="460b9-616">Aquí está el [KB individual, donde se ha documentado esto para versiones anteriores](https://support.microsoft.com/es-ES/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span><span class="sxs-lookup"><span data-stu-id="460b9-616">Here's the individual [KB where this was documented for previous versions](https://support.microsoft.com/es-ES/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span></span>

- <span data-ttu-id="460b9-617">Corrige un problema con la selección de algoritmos SMIME.</span><span class="sxs-lookup"><span data-stu-id="460b9-617">Corrects an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="460b9-618">Se ha corregido un problema que provocó que las sugerencias de la política no se mostraran al utilizar un remitente alternativo.</span><span class="sxs-lookup"><span data-stu-id="460b9-618">Addresses an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="460b9-619">Se ha corregido un problema que hizo que los usuarios vieran sugerencias de salas para reuniones que se produjeron fuera de las horas de disponibilidad de dichas salas.</span><span class="sxs-lookup"><span data-stu-id="460b9-619">Addresses an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="460b9-620">Se ha corregido un problema para los usuarios que no hablan inglés, en el que la línea de asunto de un correo electrónico era increíblemente pequeña.</span><span class="sxs-lookup"><span data-stu-id="460b9-620">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="460b9-621">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al intentar crear una regla a partir de un mensaje de "Conversación perdida".</span><span class="sxs-lookup"><span data-stu-id="460b9-621">Addresses an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="460b9-622">Se ha corregido un problema que causaba que algunos usuarios vieran carpetas especiales duplicadas al agregar una cuenta de Exchange secundaria.</span><span class="sxs-lookup"><span data-stu-id="460b9-622">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="460b9-623">Se ha corregido un problema que hacía que los usuarios vieran el truncamiento del cuerpo del mensaje al reenviar mensajes HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="460b9-623">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="460b9-624">Se ha corregido un problema que hacía que los usuarios observaran una pérdida de memoria en el proceso de Outlook.</span><span class="sxs-lookup"><span data-stu-id="460b9-624">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="460b9-625">Se ha corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.</span><span class="sxs-lookup"><span data-stu-id="460b9-625">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="460b9-626">Se ha corregido un problema que provocaba un error ocasional en la búsqueda de la carpeta actual.</span><span class="sxs-lookup"><span data-stu-id="460b9-626">Addresses an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="460b9-627">Se ha corregido un problema que hizo que algunos usuarios encontraran errores de autenticación al intentar recuperar su configuración de nube para Outlook.</span><span class="sxs-lookup"><span data-stu-id="460b9-627">Addresses an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="460b9-628">Se ha corregido un problema que causó un bloqueo en la experiencia de los comentarios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="460b9-628">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="460b9-629">Se ha corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.</span><span class="sxs-lookup"><span data-stu-id="460b9-629">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="460b9-630">Se ha corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.</span><span class="sxs-lookup"><span data-stu-id="460b9-630">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="460b9-631">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="460b9-631">PowerPoint</span></span>

- <span data-ttu-id="460b9-632">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="460b9-632">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="460b9-633">Este cambio restaura el nombre accesible de los controles de vídeo de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="460b9-633">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="460b9-634">Se ha corregido un problema que podría impedir que comiencen algunas animaciones</span><span class="sxs-lookup"><span data-stu-id="460b9-634">We fixed an issue which could prevent some animations from starting</span></span>

- <span data-ttu-id="460b9-635">Se ha corregido un problema en el que al copiar una diapositiva de una presentación a otra, se pueden crear patrones duplicados.</span><span class="sxs-lookup"><span data-stu-id="460b9-635">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span><br>

- <span data-ttu-id="460b9-636">Se ha mejorado un escenario de copiar y pegar: al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.</span><span class="sxs-lookup"><span data-stu-id="460b9-636">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="460b9-637">Se ha corregido un problema con el marcador de resaltado: los textos blancos con un marcador oscuro se imprimen como negros en escala de grises.</span><span class="sxs-lookup"><span data-stu-id="460b9-637">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

- <span data-ttu-id="460b9-638">Los archivos con nuevos comentarios modernos mostrarán una advertencia amarilla si se abren en una versión no soportada.</span><span class="sxs-lookup"><span data-stu-id="460b9-638">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

- <span data-ttu-id="460b9-639">Se ha corregido un problema que producía un rendimiento más lento entre los usuarios de colaboración.</span><span class="sxs-lookup"><span data-stu-id="460b9-639">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="460b9-640">Corrección de confiabilidad: se ha corregido un problema por el que el complemento de terceros podía bloquearse en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="460b9-640">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="460b9-641">Se ha corregido un problema que puede producirse cuando un archivo que se abre incrementalmente contiene una diapositiva con más de una secuencia multimedia incrustada.</span><span class="sxs-lookup"><span data-stu-id="460b9-641">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="460b9-642">Se ha corregido un problema con el método Shape.Paste: cuando el usuario copiaba y pegaba la forma con el método Shape.Paste, se cambiaba la selección a la forma pegada.</span><span class="sxs-lookup"><span data-stu-id="460b9-642">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="460b9-643">Se ha corregido un problema por el que es posible que la barra de mensajes de advertencia de seguridad no aparezca para los complementos en los que no se confía al iniciar PowerPoint por primera vez.</span><span class="sxs-lookup"><span data-stu-id="460b9-643">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

- <span data-ttu-id="460b9-644">Se ha corregido un problema por el que algunos complementos producían errores inesperados alrededor de las formas en gráficos.</span><span class="sxs-lookup"><span data-stu-id="460b9-644">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="460b9-645">Evita que los usuarios de PowerPoint se encuentren con un error cuando intentan hacer una presentación en línea.</span><span class="sxs-lookup"><span data-stu-id="460b9-645">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

### <a name="project"></a><span data-ttu-id="460b9-646">Project</span><span class="sxs-lookup"><span data-stu-id="460b9-646">Project</span></span>

- <span data-ttu-id="460b9-647">Se ha corregido un problema para permitir que los usuarios en Windows 7 puedan abrir proyectos desde Project Web App y sitios de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="460b9-647">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="460b9-648">Se identificó un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de sólo lectura.</span><span class="sxs-lookup"><span data-stu-id="460b9-648">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="460b9-649">El comando Level All no resuelve adecuadamente una sobreasignación de recursos.</span><span class="sxs-lookup"><span data-stu-id="460b9-649">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="460b9-650">Si tiene una tarea sin nada de trabajo, es posible que la tarea no se pueda marcar como completada y siempre se mostrará en el 99 %.</span><span class="sxs-lookup"><span data-stu-id="460b9-650">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

- <span data-ttu-id="460b9-651">Se ha corregido un problema en el que el trabajo real puede ser diferente entre el parte de horas y el plan del proyecto debido a que los calendarios de recursos no se actualizan cuando cambia el calendario base.</span><span class="sxs-lookup"><span data-stu-id="460b9-651">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="skype"></a><span data-ttu-id="460b9-652">Skype</span><span class="sxs-lookup"><span data-stu-id="460b9-652">Skype</span></span>

- <span data-ttu-id="460b9-653">Se ha corregido el nombre del título de la conversación con pestañas mientras se mantenía más de una conversación.</span><span class="sxs-lookup"><span data-stu-id="460b9-653">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="visio"></a><span data-ttu-id="460b9-654">Visio</span><span class="sxs-lookup"><span data-stu-id="460b9-654">Visio</span></span>

- <span data-ttu-id="460b9-655">La exportación como SVG de Visio estaba fallando por una variedad de formas.</span><span class="sxs-lookup"><span data-stu-id="460b9-655">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="460b9-656">Word</span><span class="sxs-lookup"><span data-stu-id="460b9-656">Word</span></span>

- <span data-ttu-id="460b9-657">Los vínculos de cid:image de los mensajes de Outlook ahora se pueden romper correctamente cuando se solicite.</span><span class="sxs-lookup"><span data-stu-id="460b9-657">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="460b9-658">Se ha corregido un problema que podría haber provocado problemas de escala al imprimir en impresoras Deskjet</span><span class="sxs-lookup"><span data-stu-id="460b9-658">We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span>

- <span data-ttu-id="460b9-659">Se ha corregido un problema al Ajustar texto en la tabla.</span><span class="sxs-lookup"><span data-stu-id="460b9-659">We fixed an issue in Fit Text in Table.</span></span>

- <span data-ttu-id="460b9-660">Hemos corregido un problema en los cambios de pista que a veces van en un bucle infinito.</span><span class="sxs-lookup"><span data-stu-id="460b9-660">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="460b9-661">Corregido un problema ocasional en el que al guardar un archivo existente siempre aparece el cuadro de diálogo Guardar como, pero el archivo nunca se guarda.</span><span class="sxs-lookup"><span data-stu-id="460b9-661">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="460b9-662">Se ha corregido un problema al combinar dos documentos en uno.</span><span class="sxs-lookup"><span data-stu-id="460b9-662">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="460b9-663">Se ha corregido un problema con la característica Comparación para los documentos protegidos para la edición.</span><span class="sxs-lookup"><span data-stu-id="460b9-663">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="460b9-664">Se han corregido varios problemas que hacían que la aplicación se colgara al apagarse.</span><span class="sxs-lookup"><span data-stu-id="460b9-664">Fixes various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="460b9-665">También se corrigieron ciertos fallos relacionados con los complementos.</span><span class="sxs-lookup"><span data-stu-id="460b9-665">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="460b9-666">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="460b9-666">Office Suite</span></span>

- <span data-ttu-id="460b9-667">Corregido el problema de la identificación incorrecta del nombre de la nueva era "Reiwa" en hiragana y kanji como una expresión mal escrita o poco gramatical.</span><span class="sxs-lookup"><span data-stu-id="460b9-667">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="460b9-668">Corregido un problema que hacía que los usuarios recibieran el mensaje "Lo sentimos, algo nos impide compartir esto" al intentar compartir archivos almacenados en SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="460b9-668">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="460b9-669">Se ha solucionado un problema que podía causar la pérdida de datos en sesiones que implicaban tanto la co autoría como la edición fuera de línea en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="460b9-669">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="460b9-670">Esta es una solución para un fallo que los usuarios podrían sufrir al abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="460b9-670">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="460b9-671">En algunos casos, un archivo de sharepoint respaldado por un motor de sincronización podría mostrar "Guardado" pero no haber guardado realmente ningún cambio, lo que provocaría la pérdida de datos.</span><span class="sxs-lookup"><span data-stu-id="460b9-671">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="460b9-672">Se resolvió un problema que impedía a los usuarios guardar documentos de Word, Excel y PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="460b9-672">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="460b9-673">Este problema afecta a los usuarios que crean un nuevo archivo y muestra la opción "Guardar como diálogo" después de hacer clic en el icono Guardar o presionar Ctrl + S.</span><span class="sxs-lookup"><span data-stu-id="460b9-673">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="460b9-674">Se ha corregido un bloqueo en Word al dejar una API obsoleta.</span><span class="sxs-lookup"><span data-stu-id="460b9-674">Fixes a crash in Word by moving away from a deprecated API.</span></span>

- <span data-ttu-id="460b9-675">Se ha corregido un problema por el que los caracteres katakana de medio ancho no giraban correctamente cuando estaban en cuadros de texto verticales en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="460b9-675">Fixing an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="460b9-676">Se ha corregido un problema de perf en Win7 en el que la galería de formas de inserción de la cinta en todas las aplicaciones tardaba aproximadamente 4 segundos en aparecer.</span><span class="sxs-lookup"><span data-stu-id="460b9-676">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="460b9-677">Corregido un error por el que la información de accesibilidad no se mostraba en la losa del lugar de información de los bastidores.</span><span class="sxs-lookup"><span data-stu-id="460b9-677">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="460b9-678">Mejora de la fiabilidad del proceso de actualización de Office en lo que respecta a la integridad del registro.</span><span class="sxs-lookup"><span data-stu-id="460b9-678">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="460b9-679">Hemos actualizado los nombres de canal para las bifurcaciones de enero y julio de 2019 con los nuevos nombres de canal.</span><span class="sxs-lookup"><span data-stu-id="460b9-679">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="460b9-680">Se ha corregido un problema por el que las actualizaciones se bloqueaban inesperadamente en las redes de uso medido.</span><span class="sxs-lookup"><span data-stu-id="460b9-680">Corrects an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="460b9-681">Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.</span><span class="sxs-lookup"><span data-stu-id="460b9-681">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="460b9-682">En determinadas circunstancias, los accesos directos de Office pueden desaparecer tras una actualización.</span><span class="sxs-lookup"><span data-stu-id="460b9-682">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="460b9-683">Esta actualización mejora la fiabilidad en la publicación de los accesos directos de Office.</span><span class="sxs-lookup"><span data-stu-id="460b9-683">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="460b9-684">Corrige un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.</span><span class="sxs-lookup"><span data-stu-id="460b9-684">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="460b9-685">Se ha corregido un problema en el que una actualización no se aplicaría en ciertos casos en los que el usuario no es un administrador y la cuenta del sistema no tenía conectividad de red.</span><span class="sxs-lookup"><span data-stu-id="460b9-685">Resolves an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="460b9-686">Se ha solucionado un problema por el que los mensajes de actualización de Office aparecían en un idioma diferente al esperado.</span><span class="sxs-lookup"><span data-stu-id="460b9-686">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="460b9-687">En el futuro, los mensajes de actualización de Office coincidirán correctamente con el idioma de visualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="460b9-687">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="460b9-688">Se ha mejorado la confiabilidad al descargar las actualizaciones de Office al reanudar las descargas que pueden haberse interrumpido anteriormente.</span><span class="sxs-lookup"><span data-stu-id="460b9-688">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="460b9-689">Se han corregido los problemas relacionados con la propiedad Textbox/Shape Autofit en los plug-ins de terceros.</span><span class="sxs-lookup"><span data-stu-id="460b9-689">Address issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="460b9-690">Este cambio corrige el procesamiento de imágenes después de abrir un archivo dañado.</span><span class="sxs-lookup"><span data-stu-id="460b9-690">This change addresses correctly rendering images after opening a corrupted file.</span></span>

- <span data-ttu-id="460b9-691">Este cambio corrige el procesamiento lento de algunos gráficos de dispersión con marcadores.</span><span class="sxs-lookup"><span data-stu-id="460b9-691">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="460b9-692">Se ha corregido un problema por el que las vistas de árboles grandes podían dar lugar a un bloqueo</span><span class="sxs-lookup"><span data-stu-id="460b9-692">We fixed an issue where large tree views could result in a crash</span></span>

- <span data-ttu-id="460b9-693">Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.</span><span class="sxs-lookup"><span data-stu-id="460b9-693">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="460b9-694">Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="460b9-694">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="460b9-695">Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="460b9-695">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-july-14"></a><span data-ttu-id="460b9-697">Versión 1902: 14 de julio</span><span class="sxs-lookup"><span data-stu-id="460b9-697">Version 1902: July 14</span></span>
<span data-ttu-id="460b9-698">*Versión 1902 (compilación 11328.20624)*</span><span class="sxs-lookup"><span data-stu-id="460b9-698">*Version 1902 (Build 11328.20624)*</span></span>

<span data-ttu-id="460b9-699">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-699">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1908-june-09"></a><span data-ttu-id="460b9-700">Versión 1908: 09 de junio</span><span class="sxs-lookup"><span data-stu-id="460b9-700">Version 1908: June 09</span></span>
<span data-ttu-id="460b9-701">*Versión 1908 (compilación 11929.20838)*</span><span class="sxs-lookup"><span data-stu-id="460b9-701">*Version 1908 (Build 11929.20838)*</span></span>

<span data-ttu-id="460b9-702">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-702">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="460b9-704">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="460b9-704">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="460b9-705">Excel</span><span class="sxs-lookup"><span data-stu-id="460b9-705">Excel</span></span>

- <span data-ttu-id="460b9-706">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="460b9-706">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="460b9-707">Se ha corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.</span><span class="sxs-lookup"><span data-stu-id="460b9-707">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="460b9-708">Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.</span><span class="sxs-lookup"><span data-stu-id="460b9-708">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="460b9-709">Outlook</span><span class="sxs-lookup"><span data-stu-id="460b9-709">Outlook</span></span>

- <span data-ttu-id="460b9-710">Se ha corregido un problema que hacía que los usuarios vieran truncado el cuerpo del mensaje al reenviar mensajes HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="460b9-710">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

### <a name="office-suite"></a><span data-ttu-id="460b9-711">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="460b9-711">Office Suite</span></span>

- <span data-ttu-id="460b9-712">Hemos actualizado los nombres de canal para las bifurcaciones de enero y julio de 2019 con los nuevos nombres de canal.</span><span class="sxs-lookup"><span data-stu-id="460b9-712">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>


[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-june-09"></a><span data-ttu-id="460b9-714">Versión 1902: 09 de junio</span><span class="sxs-lookup"><span data-stu-id="460b9-714">Version 1902: June 09</span></span>
<span data-ttu-id="460b9-715">*Versión 1902 (compilación 11328.20602)*</span><span class="sxs-lookup"><span data-stu-id="460b9-715">*Version 1902 (Build 11328.20602)*</span></span>

<span data-ttu-id="460b9-716">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-716">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="460b9-718">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="460b9-718">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="460b9-719">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="460b9-719">Office Suite</span></span>

- <span data-ttu-id="460b9-720">Hemos actualizado los nombres de canal para las bifurcaciones de enero y julio de 2019 con los nuevos nombres de canal.</span><span class="sxs-lookup"><span data-stu-id="460b9-720">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="460b9-721">Se han eliminado las referencias obsoletas de los archivos de línea base que producian errores en la compilación C2R.</span><span class="sxs-lookup"><span data-stu-id="460b9-721">We removed obsolete references from the baseline files that were breaking the C2R Build.</span></span>



[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-may-12"></a><span data-ttu-id="460b9-723">Versión 1908: 12 de mayo</span><span class="sxs-lookup"><span data-stu-id="460b9-723">Version 1908: May 12</span></span>
<span data-ttu-id="460b9-724">*Versión 1908 (compilación 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="460b9-724">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="460b9-725">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-725">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="460b9-727">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="460b9-727">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="460b9-728">Excel</span><span class="sxs-lookup"><span data-stu-id="460b9-728">Excel</span></span>

- <span data-ttu-id="460b9-729">Cuando se copian datos filtrados por colores en una columna con un ancho diferente, los valores no se pegan.</span><span class="sxs-lookup"><span data-stu-id="460b9-729">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

### <a name="outlook"></a><span data-ttu-id="460b9-730">Outlook</span><span class="sxs-lookup"><span data-stu-id="460b9-730">Outlook</span></span>

- <span data-ttu-id="460b9-731">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al abrir archivos .msg y .oft después de aplicar una actualización reciente de Windows.</span><span class="sxs-lookup"><span data-stu-id="460b9-731">Addressed an issue that caused users to experience a crash when opening msg and .oft files after applying a recent Windows update.</span></span>

### <a name="word"></a><span data-ttu-id="460b9-732">Word</span><span class="sxs-lookup"><span data-stu-id="460b9-732">Word</span></span>

- <span data-ttu-id="460b9-733">Se ha corregido un problema al combinar dos documentos en uno.</span><span class="sxs-lookup"><span data-stu-id="460b9-733">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="460b9-734">Se ha corregido un problema con la característica Comparación para los documentos protegidos para la edición.</span><span class="sxs-lookup"><span data-stu-id="460b9-734">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-may-12"></a><span data-ttu-id="460b9-736">Versión 1902:12 de mayo</span><span class="sxs-lookup"><span data-stu-id="460b9-736">Version 1902: May 12</span></span>
<span data-ttu-id="460b9-737">*Versión 1902 (compilación 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="460b9-737">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="460b9-738">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-738">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="460b9-740">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="460b9-740">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="460b9-741">Outlook</span><span class="sxs-lookup"><span data-stu-id="460b9-741">Outlook</span></span>

- <span data-ttu-id="460b9-742">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al abrir archivos .msg y .oft después de aplicar una actualización reciente de Windows.</span><span class="sxs-lookup"><span data-stu-id="460b9-742">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="460b9-743">De forma predeterminada, las etiquetas de directivas de retención muestran el período de tiempo de retención entre paréntesis.</span><span class="sxs-lookup"><span data-stu-id="460b9-743">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="460b9-744">Esto proporciona una clave del registro para permitir que los administradores especifiquen que solo se debería mostrar el nombre de la directiva.</span><span class="sxs-lookup"><span data-stu-id="460b9-744">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="460b9-745">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="460b9-745">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="460b9-746">0 = predeterminado.</span><span class="sxs-lookup"><span data-stu-id="460b9-746">0 = Default.</span></span>  <span data-ttu-id="460b9-747">1 = solo se mostrará el nombre de directiva del texto de la directiva de retención.</span><span class="sxs-lookup"><span data-stu-id="460b9-747">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-1908-may-04"></a><span data-ttu-id="460b9-749">Versión 1908: 4 de mayo</span><span class="sxs-lookup"><span data-stu-id="460b9-749">Version 1908: May 04</span></span>
<span data-ttu-id="460b9-750">*Versión 1908 (Compilación 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="460b9-750">*Version 1908 (Build 11929.20752)*</span></span>

<span data-ttu-id="460b9-751">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-751">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="460b9-752">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="460b9-752">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="460b9-753">Outlook</span><span class="sxs-lookup"><span data-stu-id="460b9-753">Outlook</span></span>

- <span data-ttu-id="460b9-754">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al seleccionar determinados resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="460b9-754">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="460b9-755">Se ha corregido un problema que hacía que el botón "Guardar en la nube" faltara en las Herramientas de datos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="460b9-755">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="460b9-756">De forma predeterminada, las etiquetas de directivas de retención muestran el período de tiempo de retención entre paréntesis.</span><span class="sxs-lookup"><span data-stu-id="460b9-756">By default, retention policy labels display the retention time period in parenthesis.</span></span><span data-ttu-id="460b9-757">Esto proporciona una clave del registro para permitir que los administradores especifiquen que solo se debería mostrar el nombre de la directiva.</span><span class="sxs-lookup"><span data-stu-id="460b9-757"> This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span><span data-ttu-id="460b9-758">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="460b9-758"> HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span><span data-ttu-id="460b9-759">0 = predeterminado 1 = solo se mostrará el nombre de directiva del texto de la directiva de retención.</span><span class="sxs-lookup"><span data-stu-id="460b9-759"> 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="office-suite"></a><span data-ttu-id="460b9-760">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="460b9-760">Office Suite</span></span>

- <span data-ttu-id="460b9-761">Se ha corregido un problema en Visual Basic para las aplicaciones de Microsoft Office, por el que la aplicación de Office consideraba como corruptos ciertos proyectos de VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre o la ruta de la biblioteca.</span><span class="sxs-lookup"><span data-stu-id="460b9-761">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="460b9-762">Versión 1902: 4 de mayo</span><span class="sxs-lookup"><span data-stu-id="460b9-762">Version 1902: May 04</span></span>
<span data-ttu-id="460b9-763">*Versión 1902 (compilación 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="460b9-763">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="460b9-764">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="460b9-764">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="460b9-765">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="460b9-765">Office Suite</span></span>

- <span data-ttu-id="460b9-766">Se ha corregido un problema en Visual Basic para las aplicaciones de Microsoft Office, por el que la aplicación de Office consideraba como corruptos ciertos proyectos de VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre o la ruta de la biblioteca.</span><span class="sxs-lookup"><span data-stu-id="460b9-766">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version1908april-26"></a><span data-ttu-id="460b9-767">Versión 1908: 26 de abril</span><span class="sxs-lookup"><span data-stu-id="460b9-767">Version 1908: April 26</span></span>
<span data-ttu-id="460b9-768">*Versión 1908 (Compilación 11929.20736)*</span><span class="sxs-lookup"><span data-stu-id="460b9-768">*Version 1908 (Build 11929.20736)*</span></span>

<span data-ttu-id="460b9-769">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-769">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="460b9-770">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="460b9-770">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="460b9-771">Excel</span><span class="sxs-lookup"><span data-stu-id="460b9-771">Excel</span></span>

- <span data-ttu-id="460b9-772">Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al usar una macro de VBA para borrar el contenido de un rango.</span><span class="sxs-lookup"><span data-stu-id="460b9-772">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="460b9-773">Se ha corregido un problema con VBA por el que escribir valores en un rango era más lento de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="460b9-773">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="460b9-774">Se ha corregido un problema por el que la propiedad "Value Crosses At" en el eje del gráfico cambiaba inesperadamente al guardar y volver a abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="460b9-774">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="460b9-775">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="460b9-775">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


### <a name="onenote"></a><span data-ttu-id="460b9-776">OneNote</span><span class="sxs-lookup"><span data-stu-id="460b9-776">OneNote</span></span>

- <span data-ttu-id="460b9-777">Localiza la notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="460b9-777">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>


## <a name="version-1908-april-14"></a><span data-ttu-id="460b9-778">Versión 1908: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="460b9-778">Version 1908: April 14</span></span>
<span data-ttu-id="460b9-779">*Versión 1908 (compilación 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="460b9-779">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="460b9-780">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-780">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="460b9-782">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="460b9-782">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="460b9-783">Excel</span><span class="sxs-lookup"><span data-stu-id="460b9-783">Excel</span></span>

- <span data-ttu-id="460b9-784">Se ha corregido un problema que provocaba un rendimiento lento al eliminar columnas que contenían celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="460b9-784">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="460b9-785">Se ha corregido un problema con la escala de texto en los controles de formulario cuando se mostraba la Vista previa de impresión.</span><span class="sxs-lookup"><span data-stu-id="460b9-785">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="460b9-786">Skype</span><span class="sxs-lookup"><span data-stu-id="460b9-786">Skype</span></span>

- <span data-ttu-id="460b9-787">Se ha corregido el nombre del título de la conversación con pestañas mientras se mantenía más de una conversación.</span><span class="sxs-lookup"><span data-stu-id="460b9-787">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="460b9-788">Outlook</span><span class="sxs-lookup"><span data-stu-id="460b9-788">Outlook</span></span>

- <span data-ttu-id="460b9-789">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al cerrar Outlook.</span><span class="sxs-lookup"><span data-stu-id="460b9-789">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="460b9-790">Se ha corregido un problema que provocaba que los clientes vieran una lista de salas vacías en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="460b9-790">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="460b9-791">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="460b9-791">PowerPoint</span></span>

- <span data-ttu-id="460b9-792">Se ha corregido un problema con el marcador de resaltado: los textos blancos con un marcador oscuro se imprimen como negros en escala de grises.</span><span class="sxs-lookup"><span data-stu-id="460b9-792">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="460b9-793">Word</span><span class="sxs-lookup"><span data-stu-id="460b9-793">Word</span></span>

- <span data-ttu-id="460b9-794">Se ha corregido un problema al Ajustar texto en la tabla.</span><span class="sxs-lookup"><span data-stu-id="460b9-794">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="460b9-795">Versión 1902: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="460b9-795">Version 1902: April 14</span></span>
<span data-ttu-id="460b9-796">*Versión 1902 (compilación 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="460b9-796">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="460b9-797">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-797">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-march-10"></a><span data-ttu-id="460b9-799">Versión 1908: 10 de marzo</span><span class="sxs-lookup"><span data-stu-id="460b9-799">Version 1908: March 10</span></span>
<span data-ttu-id="460b9-800">*Versión 1908 (compilación 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="460b9-800">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="460b9-801">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-801">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="460b9-803">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="460b9-803">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="460b9-804">Excel</span><span class="sxs-lookup"><span data-stu-id="460b9-804">Excel</span></span>

- <span data-ttu-id="460b9-805">Se ha corregido un problema por el que algunos usuarios podían haber experimentado múltiples ventanas emergentes cuando los enlaces externos estaban presentes en el libro de trabajo.</span><span class="sxs-lookup"><span data-stu-id="460b9-805">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="460b9-806">La funcionalidad de Texto a columna puede fallar en algunas configuraciones regionales.</span><span class="sxs-lookup"><span data-stu-id="460b9-806">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="460b9-807">Los usuarios pueden encontrar un error al acceder a un rango con nombre oculto.</span><span class="sxs-lookup"><span data-stu-id="460b9-807">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="460b9-808">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="460b9-808">PowerPoint</span></span>

- <span data-ttu-id="460b9-809">Se ha corregido un problema con el método Shape.Paste: cuando el usuario copiaba y pegaba la forma con el método Shape.Paste, se cambiaba la selección a la forma pegada.</span><span class="sxs-lookup"><span data-stu-id="460b9-809">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="460b9-810">Word</span><span class="sxs-lookup"><span data-stu-id="460b9-810">Word</span></span>

- <span data-ttu-id="460b9-811">Corregido un problema ocasional en el que al guardar un archivo existente siempre aparece el cuadro de diálogo Guardar como, pero el archivo nunca se guarda.</span><span class="sxs-lookup"><span data-stu-id="460b9-811">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="460b9-812">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="460b9-812">Office Suite</span></span>

- <span data-ttu-id="460b9-813">Este cambio corrige el procesamiento lento de algunos gráficos de dispersión con marcadores.</span><span class="sxs-lookup"><span data-stu-id="460b9-813">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="460b9-814">Versión 1902: 10 de marzo</span><span class="sxs-lookup"><span data-stu-id="460b9-814">Version 1902: March 10</span></span>
<span data-ttu-id="460b9-815">*Versión 1902 (compilación 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="460b9-815">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="460b9-816">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-816">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-february-11"></a><span data-ttu-id="460b9-818">Versión 1908: 11 de febrero</span><span class="sxs-lookup"><span data-stu-id="460b9-818">Version 1908: February 11</span></span>
<span data-ttu-id="460b9-819">*Versión 1908 (Compilación 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="460b9-819">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="460b9-820">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-820">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="460b9-822">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="460b9-822">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="460b9-823">Excel</span><span class="sxs-lookup"><span data-stu-id="460b9-823">Excel</span></span>

- <span data-ttu-id="460b9-824">Esta actualización corrige un problema que provoca un error siempre que se utilizaba VBA para agregar una imagen al encabezado o pie de página de un gráfico.</span><span class="sxs-lookup"><span data-stu-id="460b9-824">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="460b9-825">Se ha corregido un problema que hacía que el borde de un control de cuadro de grupo no estuviera visible en la vista previa de impresión o al imprimirlo.</span><span class="sxs-lookup"><span data-stu-id="460b9-825">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="460b9-826">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="460b9-826">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="460b9-827">Se ha corregido un problema por el que el tamaño de archivo de las imágenes en los encabezados del gráfico aumentaba cuando se guardaba el libro que contenía el gráfico.</span><span class="sxs-lookup"><span data-stu-id="460b9-827">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="460b9-828">Se ha corregido un problema que provoca la corrupción de caracteres DBCS en los libros con referencias cruzadas manteniendo los rangos de selección sincronizados con el libro con referencias cruzadas.</span><span class="sxs-lookup"><span data-stu-id="460b9-828">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="460b9-829">Se ha corregido un problema en el que los controles de casilla podían reducirse al usar el autoajuste para ajustar el alto de fila.</span><span class="sxs-lookup"><span data-stu-id="460b9-829">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="460b9-830">Outlook</span><span class="sxs-lookup"><span data-stu-id="460b9-830">Outlook</span></span>

- <span data-ttu-id="460b9-831">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.</span><span class="sxs-lookup"><span data-stu-id="460b9-831">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="460b9-832">Se ha corregido un problema que provocaba que los usuarios experimentaran errores de sincronización al procesar mensajes de conflicto.</span><span class="sxs-lookup"><span data-stu-id="460b9-832">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="460b9-833">Se ha corregido un problema que provocaba que los usuarios experimentaran un error en la pantalla de carga del perfil al iniciar Outlook.</span><span class="sxs-lookup"><span data-stu-id="460b9-833">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="460b9-834">Se ha corregido un problema que provocaba que los usuarios viesen bloqueos intermitentes al cambiar de vista.</span><span class="sxs-lookup"><span data-stu-id="460b9-834">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="460b9-835">Se ha corregido un problema que causaba que los usuarios sufrieran un error al visualizar más de 30 calendarios en un entorno Citrix.</span><span class="sxs-lookup"><span data-stu-id="460b9-835">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="460b9-836">[Aquí](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) está la KB individual, donde se ha documentado esto para versiones anteriores.</span><span class="sxs-lookup"><span data-stu-id="460b9-836">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="460b9-837">Corrige un problema que provocaba que los usuarios tuvieran problemas al intentar sincronizar carpetas del calendario compartido con el OST, lo que producía errores en los permisos al tratar de interactuar con estas carpetas.</span><span class="sxs-lookup"><span data-stu-id="460b9-837">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="460b9-838">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="460b9-838">PowerPoint</span></span>

- <span data-ttu-id="460b9-839">Se ha mejorado un escenario de copiar y pegar. Al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.</span><span class="sxs-lookup"><span data-stu-id="460b9-839">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="460b9-840">Se ha corregido un problema que producía un rendimiento más lento entre los usuarios de colaboración.</span><span class="sxs-lookup"><span data-stu-id="460b9-840">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="460b9-841">Se ha corregido un problema que puede producirse cuando un archivo que se abre incrementalmente contiene una diapositiva con más de una secuencia multimedia incrustada.</span><span class="sxs-lookup"><span data-stu-id="460b9-841">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="460b9-842">Se ha corregido un problema por el que es posible que la barra de mensajes de advertencia de seguridad no aparezca para los complementos en los que no se confía al iniciar PowerPoint por primera vez.</span><span class="sxs-lookup"><span data-stu-id="460b9-842">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="460b9-843">Project</span><span class="sxs-lookup"><span data-stu-id="460b9-843">Project</span></span>

- <span data-ttu-id="460b9-844">Se ha corregido un problema en el que el trabajo real puede ser diferente entre el parte de horas y el plan del proyecto debido a que los calendarios de recursos no se actualizan cuando cambia el calendario base.</span><span class="sxs-lookup"><span data-stu-id="460b9-844">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="460b9-845">Word</span><span class="sxs-lookup"><span data-stu-id="460b9-845">Word</span></span>

- <span data-ttu-id="460b9-846">Se ha corregido un bloqueo en Word al dejar una API obsoleta.</span><span class="sxs-lookup"><span data-stu-id="460b9-846">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="460b9-847">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="460b9-847">Office Suite</span></span>

- <span data-ttu-id="460b9-848">Este cambio corrige el procesamiento de imágenes después de abrir un archivo dañado.</span><span class="sxs-lookup"><span data-stu-id="460b9-848">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-february-11"></a><span data-ttu-id="460b9-850">Versión 1902: 11 de febrero</span><span class="sxs-lookup"><span data-stu-id="460b9-850">Version 1902: February 11</span></span>
<span data-ttu-id="460b9-851">*Versión 1902 (Compilación 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="460b9-851">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="460b9-852">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-852">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="460b9-854">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="460b9-854">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="460b9-855">Outlook</span><span class="sxs-lookup"><span data-stu-id="460b9-855">Outlook</span></span>

- <span data-ttu-id="460b9-856">Corregido un problema que hizo que los usuarios encontraran errores de "algoritmo de cifrado no admitido" al enviar un correo electrónico cifrado.</span><span class="sxs-lookup"><span data-stu-id="460b9-856">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="460b9-857">Word</span><span class="sxs-lookup"><span data-stu-id="460b9-857">Word</span></span>

- <span data-ttu-id="460b9-858">Se ha corregido un bloqueo en Word al dejar una API obsoleta.</span><span class="sxs-lookup"><span data-stu-id="460b9-858">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO INICIO)

## <a name="version-1808-february-11"></a><span data-ttu-id="460b9-861">Versión 1808: 11 de febrero</span><span class="sxs-lookup"><span data-stu-id="460b9-861">Version 1808: February 11</span></span>
<span data-ttu-id="460b9-862">*Versión 1808 (compilación 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="460b9-862">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="460b9-863">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-863">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-january-14"></a><span data-ttu-id="460b9-865">Versión 1908: 14 de enero</span><span class="sxs-lookup"><span data-stu-id="460b9-865">Version 1908: January 14</span></span>
<span data-ttu-id="460b9-866">*Versión 1908 (compilación 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="460b9-866">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="460b9-867">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-867">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="460b9-869">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="460b9-869">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="460b9-870">Access</span><span class="sxs-lookup"><span data-stu-id="460b9-870">Access</span></span>

- <span data-ttu-id="460b9-871">**Mantener un seguimiento de los objetos de base de datos:** ver claramente la pestaña activa, arrastrar las pestañas para reorganizarlas fácilmente y cerrar los objetos de base de datos con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="460b9-871">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="460b9-872">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="460b9-872">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="460b9-873">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="460b9-873">Switching between them has never been easier.</span></span> [<span data-ttu-id="460b9-874">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-874">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="460b9-875">**Zoom con más espacio:** agrandar el cuadro de Zoom, cambiar la fuente y hacer que Zoom lo recuerde todo.</span><span class="sxs-lookup"><span data-stu-id="460b9-875">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="460b9-876">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-876">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="460b9-877">Excel</span><span class="sxs-lookup"><span data-stu-id="460b9-877">Excel</span></span>

- <span data-ttu-id="460b9-878">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="460b9-878">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="460b9-879">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="460b9-879">Switching between them has never been easier.</span></span> [<span data-ttu-id="460b9-880">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-880">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="460b9-881">**Aumentar el alcance de su contenido:** ¿necesita que las presentaciones sean accesibles?</span><span class="sxs-lookup"><span data-stu-id="460b9-881">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="460b9-882">Deje que el comprobador de accesibilidad le ayude sin estorbar.</span><span class="sxs-lookup"><span data-stu-id="460b9-882">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="460b9-883">Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.</span><span class="sxs-lookup"><span data-stu-id="460b9-883">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="460b9-884">**Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente?</span><span class="sxs-lookup"><span data-stu-id="460b9-884">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="460b9-885">Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.</span><span class="sxs-lookup"><span data-stu-id="460b9-885">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="460b9-886">**Vea cómo la hoja de cálculo cobra vida**: inserte gráficos 3D animados para ver corazones que laten, planetas en órbita y dinosaurios a toda velocidad por el libro.</span><span class="sxs-lookup"><span data-stu-id="460b9-886">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="460b9-887">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-887">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="460b9-p175">**Obtener más información sobre los datos:** el nuevo botón Ideas busca patrones en los datos y los usa para crear sugerencias inteligentes y personalizadas. [Más información](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="460b9-p175">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="460b9-890">**La colaboración es ahora más fácil**: las mejoras en la coautoría significan que al trabajar con el formato condicional, los estilos de celda y otros elementos, los cambios se combinan perfectamente con los de los colaboradores.</span><span class="sxs-lookup"><span data-stu-id="460b9-890">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="460b9-891">**Unir tablas en columnas similares:** obtener y transformar (Power Query) ahora ofrece una lógica de coincidencia de texto (también denominada coincidencia aproximada) al comparar columnas en la combinación de tablas.</span><span class="sxs-lookup"><span data-stu-id="460b9-891">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="460b9-892">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-892">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="460b9-893">**Programar rápidamente con mejoras de Power Query:** termine rápidamente el código con colores de sintaxis y la función de autocompletar.</span><span class="sxs-lookup"><span data-stu-id="460b9-893">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="460b9-894">Además, descubra fácilmente funciones, columnas y parámetros.</span><span class="sxs-lookup"><span data-stu-id="460b9-894">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="460b9-895">**Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea.</span><span class="sxs-lookup"><span data-stu-id="460b9-895">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="460b9-896">Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.</span><span class="sxs-lookup"><span data-stu-id="460b9-896">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="460b9-897">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-897">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="460b9-898">Outlook</span><span class="sxs-lookup"><span data-stu-id="460b9-898">Outlook</span></span>

- <span data-ttu-id="460b9-899">**Hemos actualizado la experiencia de usuario de Outlook para usted:** una experiencia simplificada, anteriormente disponible para su vista previa con Próximamente, diseñada para ayudarle a centrarse en lo más importante.</span><span class="sxs-lookup"><span data-stu-id="460b9-899">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="460b9-900">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-900">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="460b9-901">**Una cinta simplificada que además es personalizable:** disfrute de una sola fila simplificada con los botones más usados.</span><span class="sxs-lookup"><span data-stu-id="460b9-901">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="460b9-902">Cambie fácilmente entre la vista clásica y la simplificada, y ancle o desancle comandos.</span><span class="sxs-lookup"><span data-stu-id="460b9-902">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="460b9-903">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-903">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="460b9-904">**Seguir trabajando mientras mueve mensajes:** Outlook ahora mueve los mensajes en segundo plano, por lo que puede seguir trabajando mientras mueve una gran cantidad de mensajes entre carpetas.</span><span class="sxs-lookup"><span data-stu-id="460b9-904">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="460b9-905">**Creación en el tiempo entre las reuniones consecutivas:** asigne a los asistentes el tiempo para descansar o desplazarse entre las distintas ubicaciones al configurar reuniones para finalizar 5 a 10 minutos antes de forma predeterminada.</span><span class="sxs-lookup"><span data-stu-id="460b9-905">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="460b9-906">**Seleccione su acción favorita:** ¿no usa Etiquetar ni Eliminar?</span><span class="sxs-lookup"><span data-stu-id="460b9-906">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="460b9-907">¿Qué hay de Archivar o Marcar como leído?</span><span class="sxs-lookup"><span data-stu-id="460b9-907">How about Archive or Mark as Read?</span></span> <span data-ttu-id="460b9-908">Personalice el menú de acciones rápidas con los comandos que use más frecuentemente.</span><span class="sxs-lookup"><span data-stu-id="460b9-908">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="460b9-p182">**Verán los memes que comparta:** cuando un texto o imágenes estáticas no consigan comunicar lo que desea, use un GIF animado para aclararlo. [Más información](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="460b9-p182">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="460b9-911">**Una forma más rápida de agregar cuentas:** gracias a las mejoras de configuración de cuentas, es más fácil que nunca agregar cuentas de Outlook.com y Gmail que usen la autenticación en dos fases a Outlook.</span><span class="sxs-lookup"><span data-stu-id="460b9-911">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="460b9-912">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-912">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="460b9-913">**Despídase de límites de sincronización:** las mejoras de Outlook significan que se ha eliminado el límite de carpetas y sincronizar los buzones compartidos.</span><span class="sxs-lookup"><span data-stu-id="460b9-913">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="460b9-914">**Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea.</span><span class="sxs-lookup"><span data-stu-id="460b9-914">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="460b9-915">Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.</span><span class="sxs-lookup"><span data-stu-id="460b9-915">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="460b9-916">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-916">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="460b9-917">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="460b9-917">PowerPoint</span></span>

- <span data-ttu-id="460b9-918">**Mejor transformación:** asigne un nombre a las formas para tener más control sobre cómo se transforman.</span><span class="sxs-lookup"><span data-stu-id="460b9-918">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="460b9-919">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-919">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="460b9-920">**Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente?</span><span class="sxs-lookup"><span data-stu-id="460b9-920">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="460b9-921">Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.</span><span class="sxs-lookup"><span data-stu-id="460b9-921">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="460b9-922">**Aumentar el alcance de su contenido:** ¿necesita que las presentaciones sean accesibles?</span><span class="sxs-lookup"><span data-stu-id="460b9-922">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="460b9-923">Deje que el comprobador de accesibilidad le ayude sin estorbar.</span><span class="sxs-lookup"><span data-stu-id="460b9-923">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="460b9-924">Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.</span><span class="sxs-lookup"><span data-stu-id="460b9-924">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="460b9-925">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="460b9-925">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="460b9-926">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="460b9-926">Switching between them has never been easier.</span></span> [<span data-ttu-id="460b9-927">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-927">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="460b9-928">**Los vídeos en línea tienen un nuevo hogar:** guarde un vídeo en Microsoft Stream para que puedan verlo todas las personas de su organización.</span><span class="sxs-lookup"><span data-stu-id="460b9-928">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="460b9-929">Inserte el vínculo del vídeo y disfrute de una presentación multimedia en una fracción del tamaño del archivo.</span><span class="sxs-lookup"><span data-stu-id="460b9-929">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="460b9-930">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-930">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="460b9-931">**Guardar los cambios a medida que los realiza:** cargue el archivo en OneDrive para asegurarse de que todas las actualizaciones se guardan automáticamente.</span><span class="sxs-lookup"><span data-stu-id="460b9-931">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="460b9-p190">**Pregunte a su público con un cuestionario o una encuesta:** coloque un cuestionario o una encuesta en una diapositiva. Office recopila y almacena las respuestas para usted. [Más información](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="460b9-p190">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="460b9-p191">**Nunca fue tan fácil insertar un vídeo en línea:** ¿quiere poner un vídeo de Vimeo o de YouTube en la diapositiva? Solo necesita el vínculo a la página del vídeo. [Más información](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="460b9-p191">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="460b9-938">**Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea.</span><span class="sxs-lookup"><span data-stu-id="460b9-938">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="460b9-939">Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.</span><span class="sxs-lookup"><span data-stu-id="460b9-939">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="460b9-940">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-940">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="460b9-941">Project</span><span class="sxs-lookup"><span data-stu-id="460b9-941">Project</span></span>

- <span data-ttu-id="460b9-942">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="460b9-942">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="460b9-943">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="460b9-943">Switching between them has never been easier.</span></span> [<span data-ttu-id="460b9-944">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-944">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="460b9-945">Visio</span><span class="sxs-lookup"><span data-stu-id="460b9-945">Visio</span></span>

- <span data-ttu-id="460b9-946">**Exportar diagramas de proceso a Word:** Agregue automáticamente contenido del diagrama, como formas y metadatos, a un documento de Word.</span><span class="sxs-lookup"><span data-stu-id="460b9-946">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="460b9-947">Después, personalice el documento para crear instrucciones de procesos y manuales de funcionamiento.</span><span class="sxs-lookup"><span data-stu-id="460b9-947">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="460b9-948">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-948">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="460b9-949">**Doble toma en diagramas de flujo de datos:** Los magníficos nuevos diseños para los diagramas de flujo del visualizador de datos son limpios, nítidos y fáciles de entender.</span><span class="sxs-lookup"><span data-stu-id="460b9-949">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="460b9-950">Haga clic en la pestaña Diseño para ver las opciones.</span><span class="sxs-lookup"><span data-stu-id="460b9-950">Click the Design tab for options.</span></span>

- <span data-ttu-id="460b9-951">**Galerías de símbolos integradas en Azure:** diseñe una aplicación de nube o planee una arquitectura con las múltiples galerías de símbolos de Azure.</span><span class="sxs-lookup"><span data-stu-id="460b9-951">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="460b9-952">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-952">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="460b9-p197">**Adiós a los vínculos rotos de Excel:** ¿no encuentra el libro de Excel vinculado a un diagrama de visualizador de datos? Solo tiene que vincularlo de nuevo y ¡listo! [Más información](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="460b9-p197">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="460b9-956">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="460b9-956">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="460b9-957">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="460b9-957">Switching between them has never been easier.</span></span> [<span data-ttu-id="460b9-958">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-958">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="460b9-959">**Exportar objetos visuales de Visio desde Power BI**: los objetos visuales de Visio para Power BI ahora se mostrarán correctamente al exportar informes de Power BI como archivos PDF, archivos de PowerPoint, etc.</span><span class="sxs-lookup"><span data-stu-id="460b9-959">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="460b9-960">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-960">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="460b9-961">Word</span><span class="sxs-lookup"><span data-stu-id="460b9-961">Word</span></span>

- <span data-ttu-id="460b9-962">\*\*El modo herramientas de aprendizaje tiene soporte adicional para más colores de página: \*\*las herramientas de aprendizaje de Word son compatibles con más colores de tema de página, lo que permite cambiar el color de fondo de la página.</span><span class="sxs-lookup"><span data-stu-id="460b9-962">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="460b9-963">Muchas personas tienen dificultades para leer con un fondo totalmente blanco o negro, por lo que hemos ampliado la elección de colores en Word para PC y Mac.</span><span class="sxs-lookup"><span data-stu-id="460b9-963">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="460b9-p201">**Edición natural con el Editor para entradas de lápiz:** con un solo trazo, divida o una palabras, agregue una nueva línea o inserte palabras con el lápiz. [Más información](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="460b9-p201">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="460b9-p202">**Su documento: de estático a mágico:** transforme el documento en una página web interactiva y fácil de compartir con un aspecto fantástico en cualquier dispositivo. [Más información](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="460b9-p202">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="460b9-968">**Aumentar el alcance de su contenido:** ¿necesita hacer que sus documentos sean accesibles?</span><span class="sxs-lookup"><span data-stu-id="460b9-968">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="460b9-969">Deje que el comprobador de accesibilidad le ayude sin estorbar.</span><span class="sxs-lookup"><span data-stu-id="460b9-969">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="460b9-970">Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.</span><span class="sxs-lookup"><span data-stu-id="460b9-970">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="460b9-971">**Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente?</span><span class="sxs-lookup"><span data-stu-id="460b9-971">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="460b9-972">Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.</span><span class="sxs-lookup"><span data-stu-id="460b9-972">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="460b9-973">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="460b9-973">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="460b9-974">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="460b9-974">Switching between them has never been easier.</span></span> [<span data-ttu-id="460b9-975">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-975">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="460b9-p206">**Mejorar la comprensión con el foco de línea:** desplácese por un documento línea por línea sin distracciones. Ajuste el foco para ver una, tres o cinco líneas a la vista. [Más información](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="460b9-p206">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="460b9-979">**Guarde sus cambios a medida que se produzcan:** Suba su archivo a OneDrive para asegurarse de que todas sus actualizaciones se guarden automáticamente.</span><span class="sxs-lookup"><span data-stu-id="460b9-979">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="460b9-980">**Consiga su atención con\@menciones:** use @menciones en los comentarios para avisar a los compañeros de trabajo cuando necesite su participación.</span><span class="sxs-lookup"><span data-stu-id="460b9-980">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="460b9-981">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-981">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="460b9-982">**Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea.</span><span class="sxs-lookup"><span data-stu-id="460b9-982">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="460b9-983">Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.</span><span class="sxs-lookup"><span data-stu-id="460b9-983">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="460b9-984">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-984">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="460b9-985">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="460b9-985">Office Suite</span></span>

- <span data-ttu-id="460b9-986">**Encuentra ese archivo rápido:** ¿Busca un archivo en el que haya trabajado recientemente?</span><span class="sxs-lookup"><span data-stu-id="460b9-986">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="460b9-987">Sólo tiene que escribir en el cuadro de búsqueda de la pestaña Archivo > Abrir para encontrar el archivo que está buscando.</span><span class="sxs-lookup"><span data-stu-id="460b9-987">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="460b9-988">**Guardar los cambios a medida que los realiza:** cargue el archivo en OneDrive para asegurarse de que todas las actualizaciones se guardan automáticamente.</span><span class="sxs-lookup"><span data-stu-id="460b9-988">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="460b9-989">**Controles de privacidad:** nuevos controles para datos de diagnóstico y experiencias conectadas, actualizados y mejorados.</span><span class="sxs-lookup"><span data-stu-id="460b9-989">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="460b9-990">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-990">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="460b9-991">**Los iconos de Office tienen un nuevo aspecto:** los iconos de Office se han rediseñado para reflejar las sencillas, inteligentes y eficaces experiencias de Office.</span><span class="sxs-lookup"><span data-stu-id="460b9-991">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="460b9-992">**Instalación de Microsoft Teams:** Microsoft Teams se instala de forma predeterminada en las instalaciones existentes de Office 365 ProPlus.</span><span class="sxs-lookup"><span data-stu-id="460b9-992">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="460b9-993">Más información</span><span class="sxs-lookup"><span data-stu-id="460b9-993">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="460b9-996">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="460b9-996">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="460b9-997">Access</span><span class="sxs-lookup"><span data-stu-id="460b9-997">Access</span></span>

- <span data-ttu-id="460b9-998">Esta actualización corrige un problema en el que la agregación como la suma puede truncar el resultado a un valor entero.</span><span class="sxs-lookup"><span data-stu-id="460b9-998">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="460b9-999">Esta actualización corrige un problema por el que una consulta de Unión que incluye referencias a tablas remotas (por ejemplo, tablas de SQL Server) puede hacer que Access se cierre y se reinicie.</span><span class="sxs-lookup"><span data-stu-id="460b9-999">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="460b9-1000">Esta actualización corrige un problema en Microsoft Access que puede causar el error &quot;La consulta está dañada&quot; cuando se ejecuta una consulta de actualización o cuando se usa una instrucción UPDATE en SQL.</span><span class="sxs-lookup"><span data-stu-id="460b9-1000">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="460b9-1001">Excel</span><span class="sxs-lookup"><span data-stu-id="460b9-1001">Excel</span></span>

- <span data-ttu-id="460b9-1002">La información clave en holandés para el título del documento ha sido cambiada a Alt-G.</span><span class="sxs-lookup"><span data-stu-id="460b9-1002">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="460b9-1003">Se ha corregido un problema en Excel en el que las macros asignadas a formas o controles de formularios podían mostrar un mensaje de error incorrecto o funcionar en intervalos de destino incorrectos.</span><span class="sxs-lookup"><span data-stu-id="460b9-1003">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="460b9-1004">Se resolvió un problema con buscar y reemplazar ese cambio donde el foco estaba en el diálogo después de encontrar el primer elemento.</span><span class="sxs-lookup"><span data-stu-id="460b9-1004">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="460b9-1005">Esto corrige un problema por el cual al cambiar la forma en que se ordena y actualiza una tabla dinámica mientras se está en una sesión de co autoría con otros usuarios se podía provocar un bloqueo.</span><span class="sxs-lookup"><span data-stu-id="460b9-1005">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="460b9-1006">Arreglamos un problema cuando el filtro de una tabla dinámica OLAP se estableció en un valor que se había eliminado del cubo.</span><span class="sxs-lookup"><span data-stu-id="460b9-1006">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="460b9-1007">Se han corregido los colores que se usan en las vistas previas al insertar gráficos con plantillas de gráficos.</span><span class="sxs-lookup"><span data-stu-id="460b9-1007">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="460b9-1008">Se ha corregido un problema que podía impedir que los gráficos de líneas de dispersión se representaran correctamente al cambiar la colección de series.</span><span class="sxs-lookup"><span data-stu-id="460b9-1008">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="460b9-1009">Se resolvió un problema que causó que los gráficos de cascada y embudo se desincronizara con las tablas cuando se insertaban o eliminaban celdas.</span><span class="sxs-lookup"><span data-stu-id="460b9-1009">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="460b9-1010">Se ha corregido un problema de conflicto de fusión en Excel que hacía que los usuarios tuvieran que volver a abrir el libro de trabajo para elegir los cambios.</span><span class="sxs-lookup"><span data-stu-id="460b9-1010">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="460b9-1011">Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.</span><span class="sxs-lookup"><span data-stu-id="460b9-1011">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="460b9-1012">Se resolvió un problema que causaba un error de tiempo de ejecución de la macro que activaba las ventanas minimizadas.</span><span class="sxs-lookup"><span data-stu-id="460b9-1012">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="460b9-1013">Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.</span><span class="sxs-lookup"><span data-stu-id="460b9-1013">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="460b9-1014">Se resolvió un problema que causaba que las operaciones de cortar y pegar junto a una mesa fallaran cuando se co autoría con otros.</span><span class="sxs-lookup"><span data-stu-id="460b9-1014">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="460b9-1015">Se resolvió un problema que causaba interrupciones de co autoría cuando se cambiaban las propiedades personalizadas con macros en ejecución.</span><span class="sxs-lookup"><span data-stu-id="460b9-1015">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="460b9-1016">Hubo un problema en el que no se podían seleccionar elementos del cuadro combinado de un formulario de WPF (Windows Presentation Foundation) que fue abierto por un complemento.</span><span class="sxs-lookup"><span data-stu-id="460b9-1016">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="460b9-1017">Se ha resuelto un problema que puede haber causado un bloqueo al buscar archivos recientes cuando no hay ningún libro de trabajo abierto.</span><span class="sxs-lookup"><span data-stu-id="460b9-1017">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="460b9-1018">Problema de rendimiento con las Funciones Asincrónicas Definidas por el Usuario que hacía que se ejecutaran sincrónicamente.</span><span class="sxs-lookup"><span data-stu-id="460b9-1018">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="460b9-1019">Mejoras significativas en el rendimiento de la eliminación de columnas con celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="460b9-1019">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="460b9-1020">Se resolvió un problema en el que la selección de una celda después del desplazamiento podía dar lugar a que se seleccionara la celda incorrecta.</span><span class="sxs-lookup"><span data-stu-id="460b9-1020">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="460b9-1021">Se ha resuelto un problema en el que la función de búsqueda puede devolver un error.</span><span class="sxs-lookup"><span data-stu-id="460b9-1021">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="460b9-1022">Se ha resuelto un problema por el que los libros de trabajo creados en versiones anteriores de Office podían hacer que Excel se colgara al abrirlos en las versiones actuales de Office.</span><span class="sxs-lookup"><span data-stu-id="460b9-1022">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="460b9-1023">Problema de rendimiento bajo al hacer clic en el botón Color de fuente cuando un archivo tiene un formato condicional extenso.</span><span class="sxs-lookup"><span data-stu-id="460b9-1023">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="460b9-1024">Se ha corregido un problema por el que el área de impresión en la vista previa de impresión no era correcta.</span><span class="sxs-lookup"><span data-stu-id="460b9-1024">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="460b9-1025">Excel puede tener problemas al editar un archivo protegido desde una red compartida no confiable.</span><span class="sxs-lookup"><span data-stu-id="460b9-1025">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="460b9-1026">Hemos mejorado significativamente el rendimiento del filtrado por color.</span><span class="sxs-lookup"><span data-stu-id="460b9-1026">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="460b9-1027">Se resolvió un problema que impedía que los hipervínculos se pegaran en algunas hojas protegidas.</span><span class="sxs-lookup"><span data-stu-id="460b9-1027">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="460b9-1028">Se habilitó más de 16 complementos para que se muestren al navegar en el administrador de complementos.</span><span class="sxs-lookup"><span data-stu-id="460b9-1028">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="460b9-1029">Este cambio evita un problema con ciertos controladores de gráficos Intel aprovechando la renderización de software.</span><span class="sxs-lookup"><span data-stu-id="460b9-1029">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="460b9-1030">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="460b9-1030">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="460b9-1031">Esta actualización corrige un error por el cual los documentos de Office pueden fallar al subirlos a OneDrive para la Empresa con el mensaje "Error al cargar".</span><span class="sxs-lookup"><span data-stu-id="460b9-1031">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="460b9-1032">Corregir problema en la característica Ideas de Excel, error al cargar el complemento haciendo clic en el botón Ideas en el cliente Win32.</span><span class="sxs-lookup"><span data-stu-id="460b9-1032">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="460b9-1033">Outlook</span><span class="sxs-lookup"><span data-stu-id="460b9-1033">Outlook</span></span>

- <span data-ttu-id="460b9-1034">Los vínculos de cid:image de los mensajes de Outlook ahora se pueden romper correctamente cuando se solicite.</span><span class="sxs-lookup"><span data-stu-id="460b9-1034">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="460b9-1035">Se ha corregido un problema que causaba que los usuarios que actualizaban su buzón de la autenticación básica a la moderna, terminaban con una cuenta incorrecta asociada a su perfil de Outlook.</span><span class="sxs-lookup"><span data-stu-id="460b9-1035">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="460b9-1036">Corregido un problema que hizo que los complementos web accedieran a los mensajes de Digital Rights Managed cuando no deberían hacerlo.</span><span class="sxs-lookup"><span data-stu-id="460b9-1036">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="460b9-1037">Corregido un problema que causó que las URLS de enlace simple no se mostraran en algunos enlaces seguros.</span><span class="sxs-lookup"><span data-stu-id="460b9-1037">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="460b9-1038">Esto actualiza la lógica de bloqueo de adjuntos en Outlook para bloquear también los adjuntos de Python.</span><span class="sxs-lookup"><span data-stu-id="460b9-1038">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="460b9-1039">Corregido un problema que hacía que un subconjunto de usuarios POP3 viera todos sus correos electrónicos formateados en texto plano, independientemente de la configuración.</span><span class="sxs-lookup"><span data-stu-id="460b9-1039">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="460b9-1040">Esta corrección restaurará la vista de los mensajes con formato HTML.</span><span class="sxs-lookup"><span data-stu-id="460b9-1040">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="460b9-1041">Corregido un problema que hacía que los usuarios experimentaran un error de permiso al copiar elementos de su calendario principal a un calendario de grupo.</span><span class="sxs-lookup"><span data-stu-id="460b9-1041">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="460b9-1042">Corregido un problema que hacía que los usuarios no pudieran acceder a las sugerencias de ubicación a través de un lector de pantalla.</span><span class="sxs-lookup"><span data-stu-id="460b9-1042">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="460b9-1043">Corregido un problema que hacía que los usuarios vieran un retraso notable al interactuar con sus carpetas de buzón de correo a través de métodos abreviados de teclado.</span><span class="sxs-lookup"><span data-stu-id="460b9-1043">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="460b9-1044">Corregido un problema que causaba una fuga de memoria en sesiones de Outlook muy largas.</span><span class="sxs-lookup"><span data-stu-id="460b9-1044">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="460b9-1045">Corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al abrir el cuadro de diálogo Reglas.</span><span class="sxs-lookup"><span data-stu-id="460b9-1045">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="460b9-1046">Corregido un problema que haría que los usuarios experimentaran un bloqueo en Outlook al interactuar con ciertos vínculos seguros.</span><span class="sxs-lookup"><span data-stu-id="460b9-1046">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="460b9-1047">Corregido un problema que causó ambigüedad a los gerentes en cuanto a si un delegado ya había respondido o no a una determinada solicitud de reunión.</span><span class="sxs-lookup"><span data-stu-id="460b9-1047">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="460b9-1048">Corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.</span><span class="sxs-lookup"><span data-stu-id="460b9-1048">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="460b9-1049">Se ha solucionado un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "ok" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="460b9-1049">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="460b9-1050">Este cambio permite a los administradores habilitar una política para preferir el correo electrónico de la cuenta proporcionada en los avisos de autorización de AutoDiscover sobre el UPN.</span><span class="sxs-lookup"><span data-stu-id="460b9-1050">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="460b9-1051">De forma predeterminada, detección automática prefiere el UPN de la cuenta, cuando está disponible.</span><span class="sxs-lookup"><span data-stu-id="460b9-1051">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="460b9-1052">Se ha corregido un problema que provocaba que los usuarios vieran un error en la búsqueda con grupos modernos.</span><span class="sxs-lookup"><span data-stu-id="460b9-1052">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="460b9-1053">Solucionó un problema que causaba que los usuarios de Outlook se quedaran atascados en el estado "Necesita contraseña" en ciertos escenarios.</span><span class="sxs-lookup"><span data-stu-id="460b9-1053">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="460b9-1054">Se abordó un problema que hizo que los usuarios vieran sugerencias de salas para reuniones que se produjeron fuera de las horas de disponibilidad de dichas salas.</span><span class="sxs-lookup"><span data-stu-id="460b9-1054">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="460b9-1055">Corregido un problema que hizo que los usuarios encontraran errores de "algoritmo de cifrado no admitido" al enviar un correo electrónico cifrado.</span><span class="sxs-lookup"><span data-stu-id="460b9-1055">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="460b9-1056">Corregido un problema para los usuarios que no hablan inglés, en el que la línea de asunto de un correo electrónico era increíblemente pequeña.</span><span class="sxs-lookup"><span data-stu-id="460b9-1056">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="460b9-1057">Corregido un problema que hacía que algunos usuarios vieran duplicadas las carpetas especiales creadas al añadir una cuenta de Exchange secundaria.</span><span class="sxs-lookup"><span data-stu-id="460b9-1057">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="460b9-1058">Corregido un problema que hacía que los usuarios experimentaran un bloqueo al intentar crear una regla a partir de un mensaje de "Conversación perdida".</span><span class="sxs-lookup"><span data-stu-id="460b9-1058">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="460b9-1059">Corregido un problema con la selección del algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="460b9-1059">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="460b9-1060">Corregido un problema que hacía que no se mostraran las sugerencias de política cuando se utilizaba un remitente alternativo.</span><span class="sxs-lookup"><span data-stu-id="460b9-1060">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="460b9-1061">Corregido un problema que hacía que los usuarios observaran una fuga de memoria en el proceso de Outlook.</span><span class="sxs-lookup"><span data-stu-id="460b9-1061">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="460b9-1062">Corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.</span><span class="sxs-lookup"><span data-stu-id="460b9-1062">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="460b9-1063">Corregido un problema que causaba que la búsqueda de la carpeta actual fallara de forma intermitente.</span><span class="sxs-lookup"><span data-stu-id="460b9-1063">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="460b9-1064">Corregido un problema que hizo que algunos usuarios encontraran errores de autenticación al intentar recuperar su configuración de nube para Outlook.</span><span class="sxs-lookup"><span data-stu-id="460b9-1064">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="460b9-1065">Corregido un problema que causó un bloqueo en la experiencia de los comentarios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="460b9-1065">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="460b9-1066">Corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.</span><span class="sxs-lookup"><span data-stu-id="460b9-1066">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="460b9-1067">Corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.</span><span class="sxs-lookup"><span data-stu-id="460b9-1067">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="460b9-1068">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="460b9-1068">PowerPoint</span></span>

- <span data-ttu-id="460b9-1069">Se ha corregido un problema por el que algunos complementos producían errores inesperados alrededor de las formas en gráficos.</span><span class="sxs-lookup"><span data-stu-id="460b9-1069">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="460b9-1070">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="460b9-1070">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="460b9-1071">Este cambio restaura el nombre accesible de los controles de vídeo de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="460b9-1071">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="460b9-1072">Hemos corregido un problema que podría impedir que se inicien algunas animaciones.</span><span class="sxs-lookup"><span data-stu-id="460b9-1072">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="460b9-1073">Hemos corregido un problema en el que al copiar una diapositiva de una presentación a otra, se pueden crear patrones duplicados.</span><span class="sxs-lookup"><span data-stu-id="460b9-1073">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="460b9-1074">Los archivos con nuevos comentarios modernos mostrarán una advertencia amarilla si se abren en una versión no soportada</span><span class="sxs-lookup"><span data-stu-id="460b9-1074">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="460b9-1075">Fiabilidad fija: corregido un problema por el que el complemento de terceros podía bloquearse en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="460b9-1075">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="460b9-1076">Corregido un problema por el que los caracteres katakana de medio ancho no giraban correctamente cuando estaban en cuadros de texto verticales en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="460b9-1076">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="460b9-1077">Project</span><span class="sxs-lookup"><span data-stu-id="460b9-1077">Project</span></span>

- <span data-ttu-id="460b9-1078">Se ha corregido un problema para permitir que los usuarios en Windows 7 puedan abrir proyectos desde Project Web App y sitios de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="460b9-1078">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="460b9-1079">Se identificó un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de sólo lectura.</span><span class="sxs-lookup"><span data-stu-id="460b9-1079">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="460b9-1080">El comando Level All no resuelve adecuadamente una sobreasignación de recursos.</span><span class="sxs-lookup"><span data-stu-id="460b9-1080">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="460b9-1081">Si tiene una tarea sin nada de trabajo, es posible que la tarea no se pueda marcar como completada y siempre se mostrará en el 99 %.</span><span class="sxs-lookup"><span data-stu-id="460b9-1081">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="460b9-1082">Visio</span><span class="sxs-lookup"><span data-stu-id="460b9-1082">Visio</span></span>

- <span data-ttu-id="460b9-1083">La exportación como SVG de Visio estaba fallando por una variedad de formas.</span><span class="sxs-lookup"><span data-stu-id="460b9-1083">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="460b9-1084">Word</span><span class="sxs-lookup"><span data-stu-id="460b9-1084">Word</span></span>

- <span data-ttu-id="460b9-1085">Este cambio conducirá a mejoras de rendimiento en la apertura de documentos utilizando Word.</span><span class="sxs-lookup"><span data-stu-id="460b9-1085">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="460b9-1086">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="460b9-1086">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="460b9-1087">Hemos corregido un problema que podría haber causado problemas de escala al imprimir en impresoras Deskjet.</span><span class="sxs-lookup"><span data-stu-id="460b9-1087">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="460b9-1088">Hemos corregido un problema en los cambios de pista que a veces van en un bucle infinito.</span><span class="sxs-lookup"><span data-stu-id="460b9-1088">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="460b9-1089">Corregidos varios problemas que hacían que la aplicación se colgara al apagarse.</span><span class="sxs-lookup"><span data-stu-id="460b9-1089">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="460b9-1090">También se corrigieron ciertos fallos relacionados con los complementos.</span><span class="sxs-lookup"><span data-stu-id="460b9-1090">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="460b9-1091">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="460b9-1091">Office Suite</span></span>

- <span data-ttu-id="460b9-1092">Corregido el problema de la identificación incorrecta del nombre de la nueva era "Reiwa" en hiragana y kanji como una expresión mal escrita o poco gramatical.</span><span class="sxs-lookup"><span data-stu-id="460b9-1092">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="460b9-1093">Corregido un problema que hacía que los usuarios recibieran el mensaje "Lo sentimos, algo nos impide compartir esto" al intentar compartir archivos almacenados en SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="460b9-1093">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="460b9-1094">Se ha solucionado un problema que podía causar la pérdida de datos en sesiones que implicaban tanto la co autoría como la edición fuera de línea en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="460b9-1094">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="460b9-1095">Esta es una solución para un fallo que los usuarios podrían sufrir al abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="460b9-1095">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="460b9-1096">Evita que los usuarios de PowerPoint se encuentren con un error cuando intentan hacer una presentación en línea.</span><span class="sxs-lookup"><span data-stu-id="460b9-1096">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="460b9-1097">En algunos casos, un archivo de sharepoint respaldado por un motor de sincronización podría mostrar "Guardado" pero no haber guardado realmente ningún cambio, lo que provocaría la pérdida de datos.</span><span class="sxs-lookup"><span data-stu-id="460b9-1097">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="460b9-1098">Se resolvió un problema que impedía a los usuarios guardar documentos de Word, Excel y PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="460b9-1098">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="460b9-1099">Este problema afecta a los usuarios que crean un nuevo archivo y muestra la opción "Guardar como diálogo" después de hacer clic en el icono Guardar o presionar Ctrl + S.</span><span class="sxs-lookup"><span data-stu-id="460b9-1099">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="460b9-1100">Se ha corregido un problema de perf en Win7 en el que la galería de formas de inserción de la cinta en todas las aplicaciones tardaba aproximadamente 4 segundos en aparecer.</span><span class="sxs-lookup"><span data-stu-id="460b9-1100">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="460b9-1101">Corregido un error por el que la información de accesibilidad no se mostraba en la losa del lugar de información de los bastidores.</span><span class="sxs-lookup"><span data-stu-id="460b9-1101">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="460b9-1102">Mejora de la fiabilidad del proceso de actualización de Office en lo que respecta a la integridad del registro.</span><span class="sxs-lookup"><span data-stu-id="460b9-1102">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="460b9-1103">Se ha corregido un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.</span><span class="sxs-lookup"><span data-stu-id="460b9-1103">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="460b9-1104">Se ha solucionado un problema por el que los mensajes de actualización de Office aparecían en un idioma diferente al esperado.</span><span class="sxs-lookup"><span data-stu-id="460b9-1104">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="460b9-1105">En el futuro, los mensajes de actualización de Office coincidirán correctamente con el idioma de visualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="460b9-1105">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="460b9-1106">Corregido un problema en el que una actualización no se aplicaría en ciertos casos en los que el usuario no es un administrador y la cuenta del sistema no tenía conectividad de red.</span><span class="sxs-lookup"><span data-stu-id="460b9-1106">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="460b9-1107">En determinadas circunstancias, los accesos directos de Office pueden desaparecer tras una actualización.</span><span class="sxs-lookup"><span data-stu-id="460b9-1107">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="460b9-1108">Esta actualización mejora la fiabilidad en la publicación de los accesos directos de Office.</span><span class="sxs-lookup"><span data-stu-id="460b9-1108">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="460b9-1109">Se ha corregido un problema por el que las actualizaciones se bloqueaban inesperadamente en las redes de medición.</span><span class="sxs-lookup"><span data-stu-id="460b9-1109">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="460b9-1110">Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.</span><span class="sxs-lookup"><span data-stu-id="460b9-1110">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="460b9-1111">Mejora de la confiabilidad al descargar las actualizaciones de Office al reanudar las descargas que pueden haberse interrumpido anteriormente.</span><span class="sxs-lookup"><span data-stu-id="460b9-1111">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="460b9-1112">Corregidos los problemas relacionados con la propiedad Textbox/Shape Autofit en los plug-ins de terceros.</span><span class="sxs-lookup"><span data-stu-id="460b9-1112">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="460b9-1113">Hemos corregido un problema en el que las vistas de árboles grandes podían resultar en un choque.</span><span class="sxs-lookup"><span data-stu-id="460b9-1113">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="460b9-1114">Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="460b9-1114">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-january-14"></a><span data-ttu-id="460b9-1116">Versión 1902: 14 de enero</span><span class="sxs-lookup"><span data-stu-id="460b9-1116">Version 1902: January 14</span></span>
<span data-ttu-id="460b9-1117">*VVersión 1902 (compilación 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="460b9-1117">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="460b9-1118">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-1118">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="460b9-1120">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="460b9-1120">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="460b9-1121">Excel</span><span class="sxs-lookup"><span data-stu-id="460b9-1121">Excel</span></span>

- <span data-ttu-id="460b9-1122">Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.</span><span class="sxs-lookup"><span data-stu-id="460b9-1122">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="460b9-1123">Outlook</span><span class="sxs-lookup"><span data-stu-id="460b9-1123">Outlook</span></span>

- <span data-ttu-id="460b9-1124">Corregido un problema que causó que los usuarios se encontraran con errores de "el algoritmo de cifrado no es compatible" al enviar un correo electrónico cifrado.</span><span class="sxs-lookup"><span data-stu-id="460b9-1124">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="460b9-1125">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="460b9-1125">PowerPoint</span></span>

- <span data-ttu-id="460b9-1126">Los archivos con nuevos comentarios modernos mostrarán una advertencia amarilla si se abren en una versión no soportada.</span><span class="sxs-lookup"><span data-stu-id="460b9-1126">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="460b9-1127">Word</span><span class="sxs-lookup"><span data-stu-id="460b9-1127">Word</span></span>

- <span data-ttu-id="460b9-1128">Este cambio conducirá a mejoras de rendimiento en la apertura de documentos utilizando Word.</span><span class="sxs-lookup"><span data-stu-id="460b9-1128">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (NO ELIMINAR LOS DETALLES DEL CONTENIDO FINAL)

## <a name="version-1808-january-14"></a><span data-ttu-id="460b9-1130">Versión 1808: 14 de enero</span><span class="sxs-lookup"><span data-stu-id="460b9-1130">Version 1808: January 14</span></span>
<span data-ttu-id="460b9-1131">*Versión 1808 (compilación 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="460b9-1131">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="460b9-1132">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="460b9-1132">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

> [!NOTE]
> <span data-ttu-id="460b9-1134">Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="460b9-1134">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (NO MODIFICAR INICIO DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
[//]: # (|Win32|DC|Production| |16.0.12527.21236|versión-2002-13-octubre|)
[//]: # (|Win32|DC|Producción| |16.0.12527.21104|versión-2002-08-agosto|)
[//]: # (|Win32|DC|Producción| |16.0.12527.20988|versión-2002-11-agosto|)
[//]: # (| Win32 | CC | Producción | | 16.0.12527.20880 | versión-2002-julio-14 |)
[//]: # (NO MODIFICAR EL FIN DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
