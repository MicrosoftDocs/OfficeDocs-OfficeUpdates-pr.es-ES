---
title: Notas de la versión para las versiones del Canal mensual para empresas
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Proporciona a los profesionales de TI las notas de la versión para las versiones del Canal mensual para empresas para Aplicaciones de Microsoft 365
ms.openlocfilehash: 96a76ed1ed1849753422dae92626484a77cec2a4
ms.sourcegitcommit: 4f5536e809f58462d81c708c153390ebfd1abc4e
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 07/13/2021
ms.locfileid: "53409566"
---
# <a name="release-notes-for-monthly-enterprise-channel"></a><span data-ttu-id="3b507-103">Notas de la versión para el Canal mensual para empresas</span><span class="sxs-lookup"><span data-stu-id="3b507-103">Release notes for Monthly Enterprise Channel</span></span>

<span data-ttu-id="3b507-104">Estas notas de la versión proporcionan información sobre las nuevas características y las actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones del Canal de empresa mensual para Aplicaciones de Microsoft 365 para empresas, Aplicaciones de Microsoft 365 para negocios y las versiones de suscripción de las aplicaciones de escritorio de Project y Visio.</span><span class="sxs-lookup"><span data-stu-id="3b507-104">These release notes provide information about new features and non-security updates that are included in Monthly Enterprise Channel updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>


[//]: # (NO ELIMINAR)



## <a name="version-2105-july-13"></a><span data-ttu-id="3b507-106">Versión 2105: 13 de julio</span><span class="sxs-lookup"><span data-stu-id="3b507-106">Version 2105: July 13</span></span>
<span data-ttu-id="3b507-107">*Versión 2105 (compilación 14026.20334)*</span><span class="sxs-lookup"><span data-stu-id="3b507-107">*Version 2105 (Build 14026.20334)*</span></span>

<span data-ttu-id="3b507-108">Lista de actualizaciones de seguridad [aquí](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="3b507-108">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="3b507-110">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="3b507-110">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="3b507-111">Outlook</span><span class="sxs-lookup"><span data-stu-id="3b507-111">Outlook</span></span>

- <span data-ttu-id="3b507-112">**Obtenga sugerencias relevantes de archivo al buscar:** Al escribir en el cuadro de búsqueda, los archivos más relevantes relacionados con la búsqueda se incluirán en sus sugerencias.</span><span class="sxs-lookup"><span data-stu-id="3b507-112">**Get relevant file suggestions when you search:** When you type in the Search box, the most relevant files related to your search will be included in your suggestions.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="3b507-115">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="3b507-115">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3b507-116">Excel</span><span class="sxs-lookup"><span data-stu-id="3b507-116">Excel</span></span>

- <span data-ttu-id="3b507-117">Hemos corregido un problema para permitir que el Administrador de nombres se abra en libros con un gran número de nombres ocultos.</span><span class="sxs-lookup"><span data-stu-id="3b507-117">Fixed an issue to enable the Name Manager to open on books with a large number of hidden names.</span></span>


- <span data-ttu-id="3b507-118">Hemos corregido un problema que hacía que a algunos usuarios les aparecieran entradas adicionales en la lista del complemento de Excel.</span><span class="sxs-lookup"><span data-stu-id="3b507-118">We fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>


- <span data-ttu-id="3b507-119">Se ha corregido un problema en el que el complemento de Herramientas para análisis no funcionaba para algunos usuarios.</span><span class="sxs-lookup"><span data-stu-id="3b507-119">Fixed an issue where the Analysis ToolPak add-in did not work for some users.</span></span>


### <a name="outlook"></a><span data-ttu-id="3b507-120">Outlook</span><span class="sxs-lookup"><span data-stu-id="3b507-120">Outlook</span></span>

- <span data-ttu-id="3b507-121">El cambio se está realizando en segundo plano y bajo una puerta de cambio, por lo que, si hay problemas, se puede desactivar rápidamente.</span><span class="sxs-lookup"><span data-stu-id="3b507-121">Change is going in dark and under a change gate so if there are issues it can be turned off quickly.</span></span>


- <span data-ttu-id="3b507-122">Hemos agregado una clave del Registro que deshabilita la nueva experiencia del Buscador de salas (la misma experiencia que en Outlook para Web) y habilita el Buscador de salas heredado con Horas sugeridas.</span><span class="sxs-lookup"><span data-stu-id="3b507-122">We added a registry key that disables the new Room Finder experience (the same experience as in Outlook for Web) and enables the legacy Room Finder with Suggested Times.</span></span>

   <span data-ttu-id="3b507-123">Clave del Registro:</span><span class="sxs-lookup"><span data-stu-id="3b507-123">Registry Key:</span></span>

    ><span data-ttu-id="3b507-124">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar REG_DWORD “ShowLegacyRoomFinder”</span><span class="sxs-lookup"><span data-stu-id="3b507-124">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar REG_DWORD “ShowLegacyRoomFinder”</span></span>

    ><span data-ttu-id="3b507-125">0 (predeterminado): Outlook usa la nueva experiencia con tecnología del Buscador de salas de OWA cuando el usuario hace clic en el botón "Buscador de salas" para buscar salas disponibles.</span><span class="sxs-lookup"><span data-stu-id="3b507-125">0 (default) - Outlook uses new Room Finder OWA Powered eXperience when user clicks 'Room Finder' button to search for available rooms</span></span></br>
    ><span data-ttu-id="3b507-126">1: Outlook usa la interfaz de usuario del Buscador de salas heredada para buscar salas disponibles</span><span class="sxs-lookup"><span data-stu-id="3b507-126">1 - Outlook uses legacy Room Finder UI to search for available rooms</span></span>


- <span data-ttu-id="3b507-127">Este cambio permite a los usuarios enviar comentarios a través de nuestro nuevo sistema de comentarios.</span><span class="sxs-lookup"><span data-stu-id="3b507-127">This change enables users to submit feedback through our new feedback system.</span></span>


- <span data-ttu-id="3b507-128">Hemos corregido un problema que causaba que la opción de comentarios no estuviese habilitada para los usuarios de la versión preliminar de Office Perpetual 2021.</span><span class="sxs-lookup"><span data-stu-id="3b507-128">We fixed an issue that caused the feedback option to be disabled for users of the Office Perpetual 2021 preview.</span></span>


- <span data-ttu-id="3b507-129">Se ha corregido un problema que provocaba que los usuarios reciban un error al seleccionar "Abrir propiedades de Outlook" en el menú contextual del botón derecho de un destinatario en un correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="3b507-129">We fixed an issue that caused users to get an error when selecting "Open Outlook Properties" from the right click context menu for a recipient on an email.</span></span>


- <span data-ttu-id="3b507-130">Se ha corregido un problema que causaba que algunos usuarios experimentasen un cierre inesperado de la app al cargar tarjetas de persona.</span><span class="sxs-lookup"><span data-stu-id="3b507-130">We fixed an issue that caused some users to experience unexpected app close when loading person cards.</span></span>


- <span data-ttu-id="3b507-131">Hemos corregido un problema que causaba que los usuarios experimentasen un cierre inesperado al quitar carpetas de un almacén de archivos.</span><span class="sxs-lookup"><span data-stu-id="3b507-131">We fixed an issue that caused users to experience a unexpected close when removing folders from an archive store.</span></span>


- <span data-ttu-id="3b507-132">Se ha corregido un problema que causaba que algunas instrucciones de la característica "Acortar reuniones" estuvieran deshabilitadas a través de las tecnologías de lector de pantalla.</span><span class="sxs-lookup"><span data-stu-id="3b507-132">We fixed an issue that caused some instructions for the "Shorten Meetings" feature to be disabled through screen reader technologies.</span></span>


- <span data-ttu-id="3b507-133">Hemos corregido un problema que provocaba que los usuarios experimentaran un aviso de cambio de propiedad inesperado al cerrar un mensaje al que habían respondido o que habían reenviado.</span><span class="sxs-lookup"><span data-stu-id="3b507-133">We fixed an issue that caused users to experience an unexpected property change prompt when closing a message they had replied to or forwarded.</span></span>


- <span data-ttu-id="3b507-134">Hemos solucionado un problema que podía provocar un cierre inesperado al interactuar con el Correo de Outlook o las Vistas de Calendario.</span><span class="sxs-lookup"><span data-stu-id="3b507-134">We fixed an issue that may cause a unexpected close when interacting with Outlook Mail or Calendar Views.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3b507-135">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3b507-135">PowerPoint</span></span>

- <span data-ttu-id="3b507-136">Se ha corregido un problema por el que la opción de Reutilizar diapositivas no estaba disponible para unos pocos usuarios.</span><span class="sxs-lookup"><span data-stu-id="3b507-136">Fixed an issue where Reuse Slides option was not available for few users.</span></span>


### <a name="project"></a><span data-ttu-id="3b507-137">Project</span><span class="sxs-lookup"><span data-stu-id="3b507-137">Project</span></span>

- <span data-ttu-id="3b507-138">Se ha corregido un problema que hacía que las tareas de las tareas programadas manualmente se movieran a una fecha incorrecta.</span><span class="sxs-lookup"><span data-stu-id="3b507-138">Fixed an issue where assignments on manually scheduled tasks moved to an incorrect date.</span></span>


- <span data-ttu-id="3b507-139">Se ha corregido un problema por el que, si crea una fórmula de campo personalizada que usa las funciones ProjectDate */ProjectDur* y si el segundo parámetro son las funciones Fecha(), Ahora() u Hora() de fecha y hora, se genera un #ERROR.</span><span class="sxs-lookup"><span data-stu-id="3b507-139">Fixed an issue where if you create a custom field formula which uses the ProjectDate */ProjectDur* functions and if the second parameter is the Date(), Now() or Time() date and time functions, then a #ERROR results.</span></span>


### <a name="word"></a><span data-ttu-id="3b507-140">Word</span><span class="sxs-lookup"><span data-stu-id="3b507-140">Word</span></span>

- <span data-ttu-id="3b507-141">Corrige un problema con el que no se abre en el panel del Editor.</span><span class="sxs-lookup"><span data-stu-id="3b507-141">Fixes an issue where the Editor Pane doesn't open.</span></span>


- <span data-ttu-id="3b507-142">Se ha corregido un problema por el que las tarjetas contextuales de lienzo de ortografía y gramática mostraban botones de iconos, pero esos botones no tenían información sobre herramientas.</span><span class="sxs-lookup"><span data-stu-id="3b507-142">Fixed an issue where canvas contextual cards for spelling and grammar show icon buttons, but those buttons have no tooltips.</span></span>


### <a name="office-suite"></a><span data-ttu-id="3b507-143">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="3b507-143">Office Suite</span></span>

- <span data-ttu-id="3b507-144">Se ha corregido un problema de localización por el que ahora en-gb, fr-ca y es-mx coincidirán con sus respectivas versiones primarias.</span><span class="sxs-lookup"><span data-stu-id="3b507-144">Fixed a localization issue where en-gb, fr-ca, and es-mx will now be matched with their respective parent versions.</span></span>


- <span data-ttu-id="3b507-145">Se ha corregido un cierre inesperado al volver a abrir determinados archivos.</span><span class="sxs-lookup"><span data-stu-id="3b507-145">Fixed a unexpected close when reopening certain files.</span></span>


- <span data-ttu-id="3b507-146">Se ha corregido una regresión de rendimiento al abrir archivos SyncBacked.</span><span class="sxs-lookup"><span data-stu-id="3b507-146">Fixed a performance regression on opening SyncBacked files.</span></span>


- <span data-ttu-id="3b507-147">Se ha corregido un problema que provocaba que el usuario no pudiera editar determinados documentos almacenados en servidores locales de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="3b507-147">Fixed an issue where user is unable to edit certain documents stored in OnPrem sharepoint servers.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2104-july-13"></a><span data-ttu-id="3b507-149">Versión 2104: 13 de julio</span><span class="sxs-lookup"><span data-stu-id="3b507-149">Version 2104: July 13</span></span>
<span data-ttu-id="3b507-150">*Versión 2104 (compilación 13929.20434)*</span><span class="sxs-lookup"><span data-stu-id="3b507-150">*Version 2104 (Build 13929.20434)*</span></span>

<span data-ttu-id="3b507-151">Las actualizaciones de seguridad se enumeran [aquí](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="3b507-151">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2104-june-08"></a><span data-ttu-id="3b507-152">Versión 2104: 8 de junio</span><span class="sxs-lookup"><span data-stu-id="3b507-152">Version 2104: June 08</span></span>
<span data-ttu-id="3b507-153">*Versión 2104 (Compilación 13929.20408)*</span><span class="sxs-lookup"><span data-stu-id="3b507-153">*Version 2104 (Build 13929.20408)*</span></span>

<span data-ttu-id="3b507-154">Lista de actualizaciones de seguridad [aquí](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="3b507-154">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="3b507-156">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="3b507-156">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="3b507-157">Excel</span><span class="sxs-lookup"><span data-stu-id="3b507-157">Excel</span></span>

- <span data-ttu-id="3b507-158">**Autoguardado y coautoría en documentos cifrados confidenciales:** no elija entre productividad y seguridad.</span><span class="sxs-lookup"><span data-stu-id="3b507-158">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="3b507-159">Con Microsoft Information Protection, los documentos que se cifran con etiquetas de confidencialidad ahora permiten el autoguardado y la coautoría con otras personas en tiempo real, igual que los documentos sin cifrar.</span><span class="sxs-lookup"><span data-stu-id="3b507-159">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="3b507-160">Requiere que el espacio empresarial opte por participar (más información: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="3b507-160">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3b507-161">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3b507-161">PowerPoint</span></span>

- <span data-ttu-id="3b507-162">**Autoguardado y coautoría en documentos cifrados confidenciales:** no elija entre productividad y seguridad.</span><span class="sxs-lookup"><span data-stu-id="3b507-162">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="3b507-163">Con Microsoft Information Protection, los documentos que se cifran con etiquetas de confidencialidad ahora permiten el autoguardado y la coautoría con otras personas en tiempo real, igual que los documentos sin cifrar.</span><span class="sxs-lookup"><span data-stu-id="3b507-163">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="3b507-164">Requiere que el espacio empresarial opte por participar (más información: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="3b507-164">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="word"></a><span data-ttu-id="3b507-165">Word</span><span class="sxs-lookup"><span data-stu-id="3b507-165">Word</span></span>

- <span data-ttu-id="3b507-166">**Autoguardado y coautoría en documentos cifrados confidenciales:** no elija entre productividad y seguridad.</span><span class="sxs-lookup"><span data-stu-id="3b507-166">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="3b507-167">Con Microsoft Information Protection, los documentos que se cifran con etiquetas de confidencialidad ahora permiten el autoguardado y la coautoría con otras personas en tiempo real, igual que los documentos sin cifrar.</span><span class="sxs-lookup"><span data-stu-id="3b507-167">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="3b507-168">Requiere que el espacio empresarial opte por participar (más información: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="3b507-168">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="3b507-171">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="3b507-171">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3b507-172">Excel</span><span class="sxs-lookup"><span data-stu-id="3b507-172">Excel</span></span>

- <span data-ttu-id="3b507-173">Se ha corregido un problema que en ocasiones producía errores al abrir algunos archivos en la Vista protegida.</span><span class="sxs-lookup"><span data-stu-id="3b507-173">We fixed an issue where some files would occasionally fail to open in Protected View.</span></span>


- <span data-ttu-id="3b507-174">Se ha corregido un problema que causaba que el formato de fecha se mostrara de forma incorrecta en algunos idiomas al usar complementos.</span><span class="sxs-lookup"><span data-stu-id="3b507-174">We fixed an issue that caused date formatting to be displayed incorrectly in some languages when using add-ins.</span></span>


- <span data-ttu-id="3b507-175">Se ha corregido un problema por el que el complemento de Herramientas para análisis no funcionaba para algunos usuarios.</span><span class="sxs-lookup"><span data-stu-id="3b507-175">Fixed an issue where the Analysis ToolPak add-in did not work for some users.</span></span>


- <span data-ttu-id="3b507-176">Se ha corregido un problema que hacía que a algunos usuarios les aparecieran entradas adicionales en la lista del complemento de Excel.</span><span class="sxs-lookup"><span data-stu-id="3b507-176">Fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>


- <span data-ttu-id="3b507-177">Corrección de un problema por el que una reversión de compilación de versión principal podía provocar la finalización de la aplicación al abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="3b507-177">Fix for an issue where a major version build rollback could result in the application terminating on file open.</span></span>


### <a name="outlook"></a><span data-ttu-id="3b507-178">Outlook</span><span class="sxs-lookup"><span data-stu-id="3b507-178">Outlook</span></span>

- <span data-ttu-id="3b507-179">Hemos corregido un problema que provocaba que algunos usuarios de la característica de uso compartido del calendario experimentaran problemas al interactuar con su calendario en el panel de navegación.</span><span class="sxs-lookup"><span data-stu-id="3b507-179">We fixed an issue that caused some users of the calendar sharing improvements feature to experience issues with interacting with their calendar in the navigation pane.</span></span>


- <span data-ttu-id="3b507-180">Hemos agregado una clave del Registro que deshabilita la nueva experiencia del Buscador de salas (la misma experiencia que en Outlook para Web) y habilita el Buscador de salas heredado con Horas sugeridas.</span><span class="sxs-lookup"><span data-stu-id="3b507-180">We added a registry key that disables the new Room Finder experience (the same experience as in Outlook for Web) and enables the legacy Room Finder with Suggested Times.</span></span>
    
    <span data-ttu-id="3b507-181">Clave del Registro:</span><span class="sxs-lookup"><span data-stu-id="3b507-181">Registry Key:</span></span>

    ><span data-ttu-id="3b507-182">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span><span class="sxs-lookup"><span data-stu-id="3b507-182">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span></span> </br>
    ><span data-ttu-id="3b507-183">REG_DWORD “ShowLegacyRoomFinder”</span><span class="sxs-lookup"><span data-stu-id="3b507-183">REG_DWORD “ShowLegacyRoomFinder”</span></span></br></br>
    > <span data-ttu-id="3b507-184">0 (predeterminado): Outlook usa la nueva experiencia con tecnología del Buscador de salas de OWA cuando el usuario hace clic en el botón "Buscador de salas" para buscar salas disponibles.</span><span class="sxs-lookup"><span data-stu-id="3b507-184">0 (default) - Outlook uses new Room Finder OWA Powered eXperience when user clicks 'Room Finder' button to search for available rooms</span></span>  </br>
    > <span data-ttu-id="3b507-185">1: Outlook usa la interfaz de usuario del Buscador de salas heredada para buscar salas disponibles</span><span class="sxs-lookup"><span data-stu-id="3b507-185">1 - Outlook uses legacy Room Finder UI to search for available rooms</span></span> </br>


- <span data-ttu-id="3b507-186">Hemos corregido un problema que provocaba errores en la resolución de nombres al enviar en nombre de otro usuario y al resolver en una libreta de direcciones que no es la Lista global de direcciones.</span><span class="sxs-lookup"><span data-stu-id="3b507-186">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


- <span data-ttu-id="3b507-187">Hemos corregido un problema que causaba que la opción de comentarios no se mostrara a los usuarios de la versión preliminar de Office Perpetual 2021.</span><span class="sxs-lookup"><span data-stu-id="3b507-187">We fixed an issue that caused the feedback option to fail to appear for users of the Office Perpetual 2021 preview.</span></span>


- <span data-ttu-id="3b507-188">Hemos corregido un problema que podía provocar que los usuarios vieran el mensaje que indica que están redactando perder el foco de la interfaz de usuario.</span><span class="sxs-lookup"><span data-stu-id="3b507-188">We fixed an issue that could cause users to see the message that they are composing losing the UI focus.</span></span>


- <span data-ttu-id="3b507-189">Hemos corregido un problema que causaba que Outlook anulara las preferencias de la Bandeja de entrada Prioritarios configuradas en OWA.</span><span class="sxs-lookup"><span data-stu-id="3b507-189">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>


- <span data-ttu-id="3b507-190">Hemos corregido un problema que provocaba que los usuarios vieran desaparecer las firmas de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="3b507-190">We fixed an issue that caused users to see signatures disappear unexpectedly.</span></span>


- <span data-ttu-id="3b507-191">Hemos corregido un problema que provocaba que los usuarios de la configuración de itinerancia experimentaran falta de respuesta.</span><span class="sxs-lookup"><span data-stu-id="3b507-191">We fixed an issue that caused users of roaming settings to experience unresponsiveness.</span></span>


- <span data-ttu-id="3b507-192">Hemos corregido un problema que causaba que los usuarios experimentaran la finalización inesperada del proceso durante una búsqueda.</span><span class="sxs-lookup"><span data-stu-id="3b507-192">We fixed an issue that caused users to experience the process terminating unexpectedly when searching.</span></span>


- <span data-ttu-id="3b507-193">Hemos corregido un cierre inesperado relacionado con la búsqueda.</span><span class="sxs-lookup"><span data-stu-id="3b507-193">We fixed a search-related unexpected close.</span></span>


- <span data-ttu-id="3b507-194">Hemos corregido un problema que provocaba que el selector de usuarios en Outlook se expandiera hacia arriba en lugar de hacia abajo para los usuarios con una licencia permanente.</span><span class="sxs-lookup"><span data-stu-id="3b507-194">We fixed an issue that caused the people picker in Outlook to expand upwards rather than downwards for users with a perpetual license.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3b507-195">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3b507-195">PowerPoint</span></span>

- <span data-ttu-id="3b507-196">Se ha corregido un problema por el que la opción de Reutilizar diapositivas no estaba disponible para unos pocos usuarios.</span><span class="sxs-lookup"><span data-stu-id="3b507-196">Fixed an issue where Reuse Slides option was not available for a few users.</span></span>


- <span data-ttu-id="3b507-197">Hemos corregido un problema relacionado con las imágenes vinculadas.</span><span class="sxs-lookup"><span data-stu-id="3b507-197">We fixed an issue related to linked pictures.</span></span>


- <span data-ttu-id="3b507-198">Se ha corregido un problema por el que una reversión de compilación de versión principal podía provocar un cierre inesperado al abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="3b507-198">Fixed an issue where a major version build rollback could result in an unexpected close on file open.</span></span>


### <a name="project"></a><span data-ttu-id="3b507-199">Project</span><span class="sxs-lookup"><span data-stu-id="3b507-199">Project</span></span>

- <span data-ttu-id="3b507-200">Se ha corregido un problema en el que los usuarios no podían quitar proyectos del grupo de recursos.</span><span class="sxs-lookup"><span data-stu-id="3b507-200">Fixed an issue where users were unable to remove projects from the resource pool.</span></span>


### <a name="word"></a><span data-ttu-id="3b507-201">Word</span><span class="sxs-lookup"><span data-stu-id="3b507-201">Word</span></span>

- <span data-ttu-id="3b507-202">Hemos corregido un problema que requería un cambio en la edición de Objeto OLE.</span><span class="sxs-lookup"><span data-stu-id="3b507-202">We fixed an issue which required a change on editing OLE object.</span></span>


- <span data-ttu-id="3b507-203">Se ha corregido un problema por el que algunos textos de selección no se veían al usar el tema del modo oscuro en el modo lectura.</span><span class="sxs-lookup"><span data-stu-id="3b507-203">We fixed an issue where some select text was not visible when using darkmode theme in reading mode.</span></span>


- <span data-ttu-id="3b507-204">Se ha corregido un problema que puede provocar que Word se cierre inesperadamente al cerrarse debido a que el usuario cierra o reinicia el equipo.</span><span class="sxs-lookup"><span data-stu-id="3b507-204">Fixed an issue that may cause Word to unexpectedly close when shutting down due to the user logging off or restarting their computer.</span></span>


- <span data-ttu-id="3b507-205">Se ha corregido un problema que actualiza el texto en la llamada de autoguardado para los archivos guardados localmente.</span><span class="sxs-lookup"><span data-stu-id="3b507-205">We fixed an issue that updates text on autosave callout for files saved locally.</span></span>


- <span data-ttu-id="3b507-206">Se ha corregido un problema por el que una reversión de compilación de versión principal podía provocar un cierre inesperado al abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="3b507-206">Fixed an issue where a major version build rollback could result in an unexpected close on file open.</span></span>


### <a name="office-suite"></a><span data-ttu-id="3b507-207">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="3b507-207">Office Suite</span></span>

- <span data-ttu-id="3b507-208">Se ha corregido un problema que causaba que no se pudiera abrir el documento en la nube.</span><span class="sxs-lookup"><span data-stu-id="3b507-208">Fixed an issue that would cause cloud document to fail to open.</span></span>


- <span data-ttu-id="3b507-209">Este cambio analiza el nuevo atributo TenantId enviado a través de las respuestas de Cobalt y lo almacena en la Tabla Central.</span><span class="sxs-lookup"><span data-stu-id="3b507-209">This change parses the new TenantId attribute sent on Cobalt responses and stores it in the Central Table.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2103-june-08"></a><span data-ttu-id="3b507-211">Versión 2103: 8 de junio</span><span class="sxs-lookup"><span data-stu-id="3b507-211">Version 2103: June 08</span></span>
<span data-ttu-id="3b507-212">*Versión 2103 (Compilación 13901.20554)*</span><span class="sxs-lookup"><span data-stu-id="3b507-212">*Version 2103 (Build 13901.20554)*</span></span>

<span data-ttu-id="3b507-213">Lista de actualizaciones de seguridad [aquí](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="3b507-213">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="3b507-215">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="3b507-215">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3b507-216">Excel</span><span class="sxs-lookup"><span data-stu-id="3b507-216">Excel</span></span>

- <span data-ttu-id="3b507-217">Corrige un problema que hacía que a algunos usuarios les aparecieran entradas adicionales en la lista del complemento de Excel.</span><span class="sxs-lookup"><span data-stu-id="3b507-217">Fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>


### <a name="office-suite"></a><span data-ttu-id="3b507-218">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="3b507-218">Office Suite</span></span>

- <span data-ttu-id="3b507-219">Se ha corregido un problema por el cual Word, PowerPoint y Excel no podían abrir un documento en la nube al revertir a una compilación anterior</span><span class="sxs-lookup"><span data-stu-id="3b507-219">Fix an issue Word, Powerpoint and Excel would fail to open cloud document if rolling back to a previous build</span></span>



[//]: # (NO QUITAR FINAL DE CONTENIDO CON DETALLES DE ERROR)

## <a name="version-2103-may-11"></a><span data-ttu-id="3b507-221">Versión 2103: 11 de mayo</span><span class="sxs-lookup"><span data-stu-id="3b507-221">Version 2103: May 11</span></span>
<span data-ttu-id="3b507-222">*Versión 2103 (compilación 13901.20516)*</span><span class="sxs-lookup"><span data-stu-id="3b507-222">*Version 2103 (Build 13901.20516)*</span></span>

<span data-ttu-id="3b507-223">Lista de actualizaciones de seguridad [aquí](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="3b507-223">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="3b507-225">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="3b507-225">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="3b507-226">Excel</span><span class="sxs-lookup"><span data-stu-id="3b507-226">Excel</span></span>

- <span data-ttu-id="3b507-227">**Usar automáticamente los nuevos tipos de datos**: al digitar un valor de datos que se asemeja a una ubicación geográfica o cotización, Excel ofrece la posibilidad de convertirlo en el tipo de datos conectado apropiado (cotizaciones o geografía).</span><span class="sxs-lookup"><span data-stu-id="3b507-227">**Automatically use new data types:** When you type a data value that resembles a stock or a geographic location, Excel offers to convert it to the right connected data type - Stocks or Geography.</span></span> [<span data-ttu-id="3b507-228">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-228">Learn more</span></span>](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- <span data-ttu-id="3b507-229">**Tipos de datos vinculados: datos reales para la vida real:** los nuevos tipos de datos vinculados le aportan hechos y datos sobre cientos de temas para ayudarle a lograr sus objetivos directamente en Excel.</span><span class="sxs-lookup"><span data-stu-id="3b507-229">**Linked data types: Real data for real life:** New linked data types bring you facts and data on hundreds of subjects to help you accomplish your goals right in Excel.</span></span>

### <a name="outlook"></a><span data-ttu-id="3b507-230">Outlook</span><span class="sxs-lookup"><span data-stu-id="3b507-230">Outlook</span></span>

- <span data-ttu-id="3b507-231">**Rompa la barrera del idioma con un traductor incorporado:** Los complementos para la traducción ya no son necesarios.</span><span class="sxs-lookup"><span data-stu-id="3b507-231">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="3b507-232">Ahora puede usar el Traductor inteligente en Outlook.</span><span class="sxs-lookup"><span data-stu-id="3b507-232">You can now use the Intelligent Translator in Outlook.</span></span> <span data-ttu-id="3b507-233">Cuando reciba un mensaje en otro idioma, aparecerá una ventana de notificación para preguntarle si le gustaría que Outlook lo tradujera en el idioma predeterminado.</span><span class="sxs-lookup"><span data-stu-id="3b507-233">When you receive a message in another language, a prompt will appear on top of the message asking if you’d like Outlook to translate it to your default language.</span></span>
<span data-ttu-id="3b507-234">También puede hacer clic con el botón derecho para traducir palabras específicas, oraciones o el mensaje completo.</span><span class="sxs-lookup"><span data-stu-id="3b507-234">You can also right-click to translate specific words, phrases, or the whole message.</span></span> [<span data-ttu-id="3b507-235">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-235">Learn more</span></span>](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

### <a name="visio"></a><span data-ttu-id="3b507-236">Visio</span><span class="sxs-lookup"><span data-stu-id="3b507-236">Visio</span></span>

- <span data-ttu-id="3b507-237">**Gráficos preparados para los diagramas:** elija entre una gran biblioteca de íconos, imágenes de fotografías de archivo, personas recortadas y adhesivos que puede agregar a sus dibujos de Visio.</span><span class="sxs-lookup"><span data-stu-id="3b507-237">**Ready-made graphics for your diagrams:** Choose from a large library of icons, stock photo images, cutout people, and stickers that you can add to your Visio drawings.</span></span> [<span data-ttu-id="3b507-238">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-238">Learn more</span></span>](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)<br /><span data-ttu-id="3b507-239">Ver detalles en [entrada de blog](https://insider.office.com/es-ES/blog/access-illustrations-icons-in-visio)</span><span class="sxs-lookup"><span data-stu-id="3b507-239">See details in [blog post](https://insider.office.com/es-ES/blog/access-illustrations-icons-in-visio)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="3b507-242">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="3b507-242">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="3b507-243">Acceso</span><span class="sxs-lookup"><span data-stu-id="3b507-243">Access</span></span>

- <span data-ttu-id="3b507-244">Hemos corregido un problema por el que, cuando una aplicación externa solicitaba una interfaz de accesibilidad, nos impedía cerrar hasta que se liberaba su referencia.</span><span class="sxs-lookup"><span data-stu-id="3b507-244">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


- <span data-ttu-id="3b507-245">Este cambio corrige un problema por el que al ejecutar una consulta que pasara por SQL Server, se mostraba en algunos casos un mensaje de error que alertaba de un "estado de cursor no válido".</span><span class="sxs-lookup"><span data-stu-id="3b507-245">This change fixes an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="3b507-246">Excel</span><span class="sxs-lookup"><span data-stu-id="3b507-246">Excel</span></span>

- <span data-ttu-id="3b507-247">Se ha corregido un problema que causaba que el formato de fecha se mostrara de forma incorrecta en algunos idiomas al usar complementos.</span><span class="sxs-lookup"><span data-stu-id="3b507-247">We fixed an issue that caused date formatting to be displayed incorrectly in some languages when using add-ins.</span></span>


- <span data-ttu-id="3b507-248">Se ha corregido un problema por el que el complemento de Herramientas para análisis no funcionaba para algunos usuarios.</span><span class="sxs-lookup"><span data-stu-id="3b507-248">Fixed an issue where the Analysis ToolPak add-in did not work for some users.</span></span>


- <span data-ttu-id="3b507-249">Se ha corregido un problema por el que Word podía bloquearse al dibujar una imagen.</span><span class="sxs-lookup"><span data-stu-id="3b507-249">Fixed a potential hang in Word when drawing an image.</span></span>


### <a name="outlook"></a><span data-ttu-id="3b507-250">Outlook</span><span class="sxs-lookup"><span data-stu-id="3b507-250">Outlook</span></span>

- <span data-ttu-id="3b507-251">Hemos corregido un problema que provocaba errores en la resolución de nombres al enviar en nombre de otro usuario y al resolver en una libreta de direcciones que no es la Lista global de direcciones.</span><span class="sxs-lookup"><span data-stu-id="3b507-251">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


- <span data-ttu-id="3b507-252">Se ha corregido un problema que causaba que Outlook anulara las preferencias de la Bandeja de entrada Prioritarios configuradas en OWA.</span><span class="sxs-lookup"><span data-stu-id="3b507-252">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>


- <span data-ttu-id="3b507-253">Se ha corregido un problema que causaba que algunas personas no pudieran tener acceso a las firmas asociadas a cuentas de correo secundarias.</span><span class="sxs-lookup"><span data-stu-id="3b507-253">We fixed an issue that caused some people to be unable to access signatures associated with secondary mail accounts.</span></span>


- <span data-ttu-id="3b507-254">Se ha corregido un problema que causaba que los usuarios vieran más firmas de las esperadas.</span><span class="sxs-lookup"><span data-stu-id="3b507-254">We fixed an issue that caused users to see more signatures than expected.</span></span>


- <span data-ttu-id="3b507-255">Se ha corregido un problema que causaba que algunos usuarios vieran sus calendarios principal y secundario cambiando de lugar en el panel de navegación.</span><span class="sxs-lookup"><span data-stu-id="3b507-255">We fixed an issue that caused some users to see their primary and secondary calendar switching places in the Navigation Pane.</span></span>


- <span data-ttu-id="3b507-256">Hemos corregido un problema que causaba que los usuarios vieran por error un mensaje de "Esto puede tardar un poco" mientras añadían algún elemento a un calendario.</span><span class="sxs-lookup"><span data-stu-id="3b507-256">We fixed an issue that cause users to erroneously see a "This may take a while" message when adding a calendar.</span></span>


- <span data-ttu-id="3b507-257">Hemos solucionado un problema que hacía que los delegados aparecieran como organizadores de reuniones creadas en calendarios recién añadidos.</span><span class="sxs-lookup"><span data-stu-id="3b507-257">We fixed an issue that caused delegates to appear as the organizer of meetings created on newly added calendars.</span></span>  <span data-ttu-id="3b507-258">Las reuniones en este estado no aparecían en el calendario del principal.</span><span class="sxs-lookup"><span data-stu-id="3b507-258">Meetings in this state did not appear on the principal's calendar.</span></span>


- <span data-ttu-id="3b507-259">Se ha corregido un problema en un componente de Outlook que se usa en las aplicaciones habilitadas para MAPI en equipos con procesadores ARM.</span><span class="sxs-lookup"><span data-stu-id="3b507-259">We fixed an issue in a component of Outlook that is used by MAPI-enabled applications on computers with ARM processors.</span></span> <span data-ttu-id="3b507-260">El problema podría provocar errores en la búsqueda o causar una carga adicional en el equipo al reiniciar las aplicaciones en segundo plano varias veces.</span><span class="sxs-lookup"><span data-stu-id="3b507-260">The issue could cause search to fail or cause extra load on the computer as background apps restarted repeatedly.</span></span>


- <span data-ttu-id="3b507-261">Se ha corregido un problema que causaba que algunos usuarios experimentaran un cierre inesperado de Outlook al sincronizar los cambios en la jerarquía de carpetas.</span><span class="sxs-lookup"><span data-stu-id="3b507-261">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


- <span data-ttu-id="3b507-262">Se ha corregido un problema por el que Word podía bloquearse al dibujar una imagen.</span><span class="sxs-lookup"><span data-stu-id="3b507-262">Fixed a potential hang in Word when drawing an image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3b507-263">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3b507-263">PowerPoint</span></span>

- <span data-ttu-id="3b507-264">Hemos corregido un problema relacionado con las imágenes vinculadas.</span><span class="sxs-lookup"><span data-stu-id="3b507-264">We fixed an issue related to linked pictures.</span></span>


- <span data-ttu-id="3b507-265">Se ha corregido un problema por el que Word podía bloquearse al dibujar una imagen.</span><span class="sxs-lookup"><span data-stu-id="3b507-265">Fixed a potential hang in Word when drawing an image.</span></span>


### <a name="project"></a><span data-ttu-id="3b507-266">Project</span><span class="sxs-lookup"><span data-stu-id="3b507-266">Project</span></span>

- <span data-ttu-id="3b507-267">Se ha corregido un problema que provocaba que Visio dejara de funcionar durante el cierre.</span><span class="sxs-lookup"><span data-stu-id="3b507-267">Fixed an issue where Visio could stop working during close.</span></span>


### <a name="visio"></a><span data-ttu-id="3b507-268">Visio</span><span class="sxs-lookup"><span data-stu-id="3b507-268">Visio</span></span>

- <span data-ttu-id="3b507-269">Se ha corregido un problema que provocaba que Visio dejara de funcionar durante el cierre.</span><span class="sxs-lookup"><span data-stu-id="3b507-269">Fixed an issue where Visio could stop working during close.</span></span>


### <a name="word"></a><span data-ttu-id="3b507-270">Word</span><span class="sxs-lookup"><span data-stu-id="3b507-270">Word</span></span>

- <span data-ttu-id="3b507-271">Se ha corregido un problema para optimizar las condiciones para ofrecer previsiones de texto.</span><span class="sxs-lookup"><span data-stu-id="3b507-271">Fixed an issue to optimizes conditions for text predictions to be offered.</span></span>


- <span data-ttu-id="3b507-272">Se ha corregido un problema para actualizar el texto en la llamada de Autoguardado para los archivos guardados localmente.</span><span class="sxs-lookup"><span data-stu-id="3b507-272">Fixed an issue where updates text on autosave callout for files saved locally.</span></span>


- <span data-ttu-id="3b507-273">Se ha corregido un problema por el que al trabajar en un documento en coautoría, el borrador activo no se borraba cuando cambiaba el orden de los comentarios.</span><span class="sxs-lookup"><span data-stu-id="3b507-273">Fixed an issue when coauthoring a document, active draft is not cleared when comment order changes.</span></span>


- <span data-ttu-id="3b507-274">Corrige un problema por el que la vista previa de impresión se cerraba de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="3b507-274">Fixes an issue where Print preview closed unexpectedly.</span></span>


- <span data-ttu-id="3b507-275">Se ha corregido un problema por el que Word podía bloquearse al dibujar una imagen.</span><span class="sxs-lookup"><span data-stu-id="3b507-275">Fixed a potential hang in Word when drawing an image.</span></span>



### <a name="office-suite"></a><span data-ttu-id="3b507-276">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="3b507-276">Office Suite</span></span>

- <span data-ttu-id="3b507-277">Se ha corregido un problema de confiabilidad relacionado con la compatibilidad de las aplicaciones de Office que se ejecutan en la sesión 0.</span><span class="sxs-lookup"><span data-stu-id="3b507-277">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="3b507-278">Se ha corregido un problema por el que el cambio de nombre no respondía cuando se abría un archivo SyncBacked fuera de línea y se le cambiaba el nombre en la aplicación antes de guardarlo.</span><span class="sxs-lookup"><span data-stu-id="3b507-278">Fixed an issue which rename was unresponsive when opened a SyncBacked file offline then renamed the file in app before saving file.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2102-may-11"></a><span data-ttu-id="3b507-280">Versión 2102: 11 de mayo</span><span class="sxs-lookup"><span data-stu-id="3b507-280">Version 2102: May 11</span></span>
<span data-ttu-id="3b507-281">*Versión 2102 (compilación 13801.20638)*</span><span class="sxs-lookup"><span data-stu-id="3b507-281">*Version 2102 (Build 13801.20638)*</span></span>

<span data-ttu-id="3b507-282">Lista de actualizaciones de seguridad [aquí](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="3b507-282">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="3b507-284">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="3b507-284">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3b507-285">Excel</span><span class="sxs-lookup"><span data-stu-id="3b507-285">Excel</span></span>

- <span data-ttu-id="3b507-286">Se ha corregido un problema que causaba que el formato de fecha se mostrara de forma incorrecta en algunos idiomas al usar complementos.</span><span class="sxs-lookup"><span data-stu-id="3b507-286">We fixed an issue that caused date formatting to be displayed incorrectly on some languages when using Add-ins.</span></span>


- <span data-ttu-id="3b507-287">Hemos corregido un problema que bloqueaba la capacidad de pegar como fórmulas en una hoja protegida.</span><span class="sxs-lookup"><span data-stu-id="3b507-287">We fixed an issue that was preventing the ability to paste as formulas on a protected sheet.</span></span>


### <a name="outlook"></a><span data-ttu-id="3b507-288">Outlook</span><span class="sxs-lookup"><span data-stu-id="3b507-288">Outlook</span></span>

- <span data-ttu-id="3b507-289">Esto permite a los usuarios finales configurar Outlook para agregar una reunión en línea a cada reunión que creen.</span><span class="sxs-lookup"><span data-stu-id="3b507-289">This enables end users to configure Outlook to add an online meeting to every meeting they create.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3b507-290">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3b507-290">PowerPoint</span></span>

- <span data-ttu-id="3b507-291">Hemos corregido un problema relacionado con las imágenes vinculadas.</span><span class="sxs-lookup"><span data-stu-id="3b507-291">We fixed an issue related to linked pictures.</span></span>


### <a name="word"></a><span data-ttu-id="3b507-292">Word</span><span class="sxs-lookup"><span data-stu-id="3b507-292">Word</span></span>

- <span data-ttu-id="3b507-293">Soluciona un problema de WordMail por el que el usuario recibía el error "No se puede enviar este elemento" cuando el número 2084 de un vínculo era un carácter de escape.</span><span class="sxs-lookup"><span data-stu-id="3b507-293">Fixes an issue in Wordmail where someone cannot send this item' when the 2084th character in a link is an escaped character.</span></span>


### <a name="office-suite"></a><span data-ttu-id="3b507-294">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="3b507-294">Office Suite</span></span>

- <span data-ttu-id="3b507-295">Se ha corregido un problema que causaba que Word se cerrara de forma inesperada al imprimir documentos largos.</span><span class="sxs-lookup"><span data-stu-id="3b507-295">Fixed an issue that caused Word to close unexpectedly while printing long documents.</span></span>


- <span data-ttu-id="3b507-296">Antes de este cambio, las plantillas de Office se mostraban incluso aunque el GPO estuviera activado para deshabilitarlas.</span><span class="sxs-lookup"><span data-stu-id="3b507-296">Before this change, Office templates were displaying even if GPO for disabling them was turned on.</span></span> <span data-ttu-id="3b507-297">Con este cambio, las plantillas ahora respetan correctamente el GPO y se muestran u ocultan según se solicite.</span><span class="sxs-lookup"><span data-stu-id="3b507-297">With this change, templates now honor the GPO correctly and display/hide as requested.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2102-april-13"></a><span data-ttu-id="3b507-299">Versión 2102: 13 de abril</span><span class="sxs-lookup"><span data-stu-id="3b507-299">Version 2102: April 13</span></span>
<span data-ttu-id="3b507-300">*Versión 2102 (Compilación 13801.20506)*</span><span class="sxs-lookup"><span data-stu-id="3b507-300">*Version 2102 (Build 13801.20506)*</span></span>

<span data-ttu-id="3b507-301">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3b507-301">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="3b507-303">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="3b507-303">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="3b507-304">Excel</span><span class="sxs-lookup"><span data-stu-id="3b507-304">Excel</span></span>

- <span data-ttu-id="3b507-305">**Usar el cuadro de diálogo Opciones avanzadas para crear tipos de datos:** el cuadro de diálogo Opciones avanzadas le permite seleccionar manualmente las columnas que combinan el tipo de datos que está creando.</span><span class="sxs-lookup"><span data-stu-id="3b507-305">**Use the Advanced Dialog to Create Data Types:** The Advanced Dialog allows you to manually select the columns which combine the Data Type you are creating.</span></span>

- <span data-ttu-id="3b507-306">**Mostrar varias hojas de cálculo al mismo tiempo:** no es necesario que se muestren las hojas de una en una, ya que se pueden mostrar varias hojas ocultas al mismo tiempo.</span><span class="sxs-lookup"><span data-stu-id="3b507-306">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="3b507-307">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-307">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)


### <a name="outlook"></a><span data-ttu-id="3b507-308">Outlook</span><span class="sxs-lookup"><span data-stu-id="3b507-308">Outlook</span></span>

- <span data-ttu-id="3b507-309">**La configuración de la bandeja de entrada prioritaria permanece igual en todos los dispositivos:** ahora, las preferencias de la Bandeja de entrada Prioritarios se almacenan en la nube.</span><span class="sxs-lookup"><span data-stu-id="3b507-309">**Focused Inbox settings remain the same across devices:** Your Focused Inbox preferences are now stored in the cloud.</span></span> <span data-ttu-id="3b507-310">Disfrute de la misma experiencia al usar Outlook para Windows en cualquier equipo y Outlook en la Web.</span><span class="sxs-lookup"><span data-stu-id="3b507-310">Enjoy the same experience when you use Outlook for Windows on any computer and Outlook on the web.</span></span> [<span data-ttu-id="3b507-311">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-311">Learn more</span></span>](https://support.office.com/article/d77a442e-a86c-4bf8-b3dd-5571ae556986)

- <span data-ttu-id="3b507-312">**Su configuración de Outlook en la nube:** elija la configuración de Outlook para Windows, como Respuestas automáticas, la Bandeja de entrada Prioritarios y Privacidad, y acceda a ellos desde cualquier PC.</span><span class="sxs-lookup"><span data-stu-id="3b507-312">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>

- <span data-ttu-id="3b507-313">**Elija dónde buscar:** La nueva lista desplegable del ámbito de búsqueda le permite modificar de manera más sencilla su búsqueda y cambiar entre la carpeta actual y el buzón actual.</span><span class="sxs-lookup"><span data-stu-id="3b507-313">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="3b507-314">Gracias a todos los usuarios de Próximamente, quienes brindaron comentarios acerca de la nueva experiencia de búsqueda Search at Top.</span><span class="sxs-lookup"><span data-stu-id="3b507-314">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="3b507-315">¡Este diseño y actualización son el resultado de sus comentarios!</span><span class="sxs-lookup"><span data-stu-id="3b507-315">This design and update came out of that feedback!</span></span>

- <span data-ttu-id="3b507-316">**Escriba mensajes con su voz:** use la nueva barra de herramientas de dictado, los comandos de voz, la puntuación automática y mucho más para redactar mensajes.</span><span class="sxs-lookup"><span data-stu-id="3b507-316">**Draft messages with your voice:** Use the new dictation toolbar, voice commands, auto-punctuation, and more to compose messages.</span></span>

### <a name="word"></a><span data-ttu-id="3b507-317">Word</span><span class="sxs-lookup"><span data-stu-id="3b507-317">Word</span></span>

- <span data-ttu-id="3b507-318">**Escriba documentos con su voz:** use la nueva barra de herramientas de dictado, los comandos de voz, la puntuación automática para redactar documentos.</span><span class="sxs-lookup"><span data-stu-id="3b507-318">**Draft documents with your voice:** Use the new dictation toolbar, voice commands and auto-punctuation to draft documents.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="3b507-321">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="3b507-321">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="3b507-322">Access</span><span class="sxs-lookup"><span data-stu-id="3b507-322">Access</span></span>

- <span data-ttu-id="3b507-323">Se ha corregido un problema por el que al ejecutar una consulta que pasara por SQL Server, se mostraba en algunos casos un mensaje de error que alertaba de un "estado de cursor no válido".</span><span class="sxs-lookup"><span data-stu-id="3b507-323">Fixed an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>



### <a name="excel"></a><span data-ttu-id="3b507-324">Excel</span><span class="sxs-lookup"><span data-stu-id="3b507-324">Excel</span></span>

- <span data-ttu-id="3b507-325">Hemos corregido un error en el que la validación de datos se podía aplicar a celdas de forma inesperada después de añadir filas a una tabla o a otra hoja.</span><span class="sxs-lookup"><span data-stu-id="3b507-325">We fixed a bug in which data validation could be applied to cells unexpectedly after adding rows to a table on another sheet.</span></span>


- <span data-ttu-id="3b507-326">Hemos corregido un problema donde la función de mostrar DialogSheets no funcionaba en la versión de 32 bit de Excel.</span><span class="sxs-lookup"><span data-stu-id="3b507-326">We fixed an issue where the DialogSheets show function was not working on 32 bit versions of Excel</span></span>


- <span data-ttu-id="3b507-327">Hemos corregido un problema que hace que las imágenes fueran más pequeñas de lo esperado al usar la opción Pegar imagen vinculada.</span><span class="sxs-lookup"><span data-stu-id="3b507-327">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="3b507-328">Hemos corregido un problema que causaba que algunos formatos de tabla dinámica dañaran el libro al guardar en formato .xls o .xlt.</span><span class="sxs-lookup"><span data-stu-id="3b507-328">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="3b507-329">Hemos corregido un problema que impedía a los usuarios exportar un libro de Excel a PDF.</span><span class="sxs-lookup"><span data-stu-id="3b507-329">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="3b507-330">Se ha corregido un problema por el que los comandos deshabilitados de la cinta de opciones de Office tenían el icono (pero no el texto) atenuado en el tema de Office Gris oscuro.</span><span class="sxs-lookup"><span data-stu-id="3b507-330">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="outlook"></a><span data-ttu-id="3b507-331">Outlook</span><span class="sxs-lookup"><span data-stu-id="3b507-331">Outlook</span></span>

- <span data-ttu-id="3b507-332">Hemos corregido un problema que causaba que los usuarios de traducción directa no pudieran enviar comentarios.</span><span class="sxs-lookup"><span data-stu-id="3b507-332">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="3b507-333">Hemos corregido un problema que provocaba que las firmas con contenido Unicode se dañasen.</span><span class="sxs-lookup"><span data-stu-id="3b507-333">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="3b507-334">Hemos corregido un problema que provocaba que los usuarios vieran más firmas de las esperadas.</span><span class="sxs-lookup"><span data-stu-id="3b507-334">We fixed an issue that caused users to see more signatures than expected.</span></span>


- <span data-ttu-id="3b507-335">Hemos corregido un problema que provocaba que Outlook se bloquease cuando estaba inactivo.</span><span class="sxs-lookup"><span data-stu-id="3b507-335">We fixed an issue that caused Outlook to crash when idle.</span></span>


- <span data-ttu-id="3b507-336">Hemos corregido un problema que causaba que la app se cerrase para algunos usuarios al cerrar las ventanas de mensaje.</span><span class="sxs-lookup"><span data-stu-id="3b507-336">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="3b507-337">Hemos corregido un problema que causaba que los usuarios de las mejoras del calendario compartido no pudieran establecer el color de un calendario en amarillo o marrón.</span><span class="sxs-lookup"><span data-stu-id="3b507-337">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="3b507-338">Hemos corregido el problema que causaba que los usuarios viesen grupos de calendario duplicados después de crear un grupo.</span><span class="sxs-lookup"><span data-stu-id="3b507-338">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="3b507-339">Hemos corregido un problema por el que los usuarios no veían los calendarios agregados recientemente en el panel de navegación si no reiniciaban Outlook.</span><span class="sxs-lookup"><span data-stu-id="3b507-339">We fixed an issue that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3b507-340">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3b507-340">PowerPoint</span></span>

- <span data-ttu-id="3b507-341">Se ha corregido un problema por el que los comandos deshabilitados de la cinta de opciones de Office tenían el icono (pero no el texto) atenuado en el tema de Office Gris oscuro.</span><span class="sxs-lookup"><span data-stu-id="3b507-341">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="word"></a><span data-ttu-id="3b507-342">Word</span><span class="sxs-lookup"><span data-stu-id="3b507-342">Word</span></span>

- <span data-ttu-id="3b507-343">Hemos corregido un problema relacionado con la resolución de conflictos durante la coautoría.</span><span class="sxs-lookup"><span data-stu-id="3b507-343">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


- <span data-ttu-id="3b507-344">Hemos corregido un problema con los controles de contenido de texto enriquecido.</span><span class="sxs-lookup"><span data-stu-id="3b507-344">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="3b507-345">Hemos corregido un problema con la escritura al final de un párrafo oculto que podía provocar que la aplicación dejara de funcionar.</span><span class="sxs-lookup"><span data-stu-id="3b507-345">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


- <span data-ttu-id="3b507-346">Hemos corregido un problema por el que el Narrador podía omitir un párrafo.</span><span class="sxs-lookup"><span data-stu-id="3b507-346">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="3b507-347">Se ha corregido un problema con copiar y pegar.</span><span class="sxs-lookup"><span data-stu-id="3b507-347">We fixed an issue relating to copy and paste.</span></span>


- <span data-ttu-id="3b507-348">Se ha corregido un problema con los colores aplicados a los iconos y a los gráficos SVG con efectos 3D.</span><span class="sxs-lookup"><span data-stu-id="3b507-348">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="3b507-349">Se ha corregido un problema por el que los comandos deshabilitados de la cinta de opciones de Office tenían el icono (pero no el texto) atenuado en el tema de Office Gris oscuro.</span><span class="sxs-lookup"><span data-stu-id="3b507-349">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="office-suite"></a><span data-ttu-id="3b507-350">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="3b507-350">Office Suite</span></span>

- <span data-ttu-id="3b507-351">Se ha corregido un problema de confiabilidad relacionado con la compatibilidad de las aplicaciones de Office que se ejecutan en la sesión 0.</span><span class="sxs-lookup"><span data-stu-id="3b507-351">We fixed a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="3b507-352">Se ha corregido un problema que a veces provocaba que el texto en Outlook se viera transparente y no fuera legible.</span><span class="sxs-lookup"><span data-stu-id="3b507-352">Fixed an issue that could sometimes lead to text in Outlook becoming transparent and thereby not legible.</span></span>


- <span data-ttu-id="3b507-353">Se ha corregido un problema al usar Narrador en un texto que contiene ecuaciones matemáticas.</span><span class="sxs-lookup"><span data-stu-id="3b507-353">Fixed an issue that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="3b507-354">Se ha corregido un problema que impedía la opción Dictado para usuarios de GCC.</span><span class="sxs-lookup"><span data-stu-id="3b507-354">Fixed an issue where Dictation was disabled for GCC users</span></span>


- <span data-ttu-id="3b507-355">Se ha corregido un problema por el que los usuarios no podían guardar un archivo al abrirlo, realizar modificaciones sin guardar y eliminarlo.</span><span class="sxs-lookup"><span data-stu-id="3b507-355">Fixed an issue where users are unable to save file when open a previously opened file with edits not saved but now the file has been deleted.</span></span> <span data-ttu-id="3b507-356">Después de la corrección, los usuarios recibirán un mensaje descriptivo para informarles de que el archivo se ha eliminado, de modo que podrán descartar cambios o usar la opción Guardar como.</span><span class="sxs-lookup"><span data-stu-id="3b507-356">After the fix, users will get a friendly message to inform them that the file is deleted, thus user can choose to discard changes, or SaveAs the file.</span></span>


- <span data-ttu-id="3b507-357">Se ha corregido el problema del cambio de nombre cuando se abría un archivo SyncBacked fuera de línea y se le cambiaba el nombre en la aplicación antes de guardarlo.</span><span class="sxs-lookup"><span data-stu-id="3b507-357">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL )

## <a name="version-2101-april-13"></a><span data-ttu-id="3b507-359">Versión 2101: 13 de abril</span><span class="sxs-lookup"><span data-stu-id="3b507-359">Version 2101: April 13</span></span>
<span data-ttu-id="3b507-360">*Versión 2101 (Compilación 13628.20664)*</span><span class="sxs-lookup"><span data-stu-id="3b507-360">*Version 2101 (Build 13628.20664)*</span></span>

<span data-ttu-id="3b507-361">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3b507-361">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2101-march-09"></a><span data-ttu-id="3b507-362">Versión 2101: 9 de enero</span><span class="sxs-lookup"><span data-stu-id="3b507-362">Version 2101: March 09</span></span>
<span data-ttu-id="3b507-363">*Versión 2101 (Compilación 13628.20528)*</span><span class="sxs-lookup"><span data-stu-id="3b507-363">*Version 2101 (Build 13628.20528)*</span></span>

<span data-ttu-id="3b507-364">Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="3b507-364">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="3b507-366">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="3b507-366">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3b507-367">Excel</span><span class="sxs-lookup"><span data-stu-id="3b507-367">Excel</span></span>

- <span data-ttu-id="3b507-368">Corrige un problema por el que Excel no se iniciaba o se cerraba inesperadamente si se estaba usando cierta configuración de protección contra vulnerabilidades de Seguridad de Windows (SimExec, CallerCheck).</span><span class="sxs-lookup"><span data-stu-id="3b507-368">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="3b507-369">Outlook</span><span class="sxs-lookup"><span data-stu-id="3b507-369">Outlook</span></span>

- <span data-ttu-id="3b507-370">Hemos corregido un problema que hacía que no se mostrara el icono de cifrado de los correos electrónicos enviados con la opción de solo cifrado.</span><span class="sxs-lookup"><span data-stu-id="3b507-370">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>


- <span data-ttu-id="3b507-371">Hemos corregido un problema por el que los mensajes de correo electrónico se enviaban como firmados digitalmente después de que el usuario desactivara esa opción.</span><span class="sxs-lookup"><span data-stu-id="3b507-371">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


- <span data-ttu-id="3b507-372">Hemos corregido un problema que causaba errores al mostrar la firma predeterminada correcta en OWA.</span><span class="sxs-lookup"><span data-stu-id="3b507-372">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="3b507-373">Hemos corregido un problema que causaba que los usuarios de Configuración de la nube tuviesen un error al actualizar la configuración.</span><span class="sxs-lookup"><span data-stu-id="3b507-373">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>


- <span data-ttu-id="3b507-374">Hemos corregido un problema que causaba que la aplicación se cerrara de forma inesperada al buscar en Outlook.</span><span class="sxs-lookup"><span data-stu-id="3b507-374">We fixed an issue that caused the app to sometimes close unexpectedly when users were searching in Outlook.</span></span>


- <span data-ttu-id="3b507-375">Se ha corregido un problema que causaba que los usuarios que tienen buzones compartidos o delegados con jerarquías grandes en su perfil sufriesen bloqueos.</span><span class="sxs-lookup"><span data-stu-id="3b507-375">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="3b507-376">Se ha corregido un problema que provocaba que Outlook se cerrara de forma inesperada para algunos usuarios en ciertos escenarios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="3b507-376">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


### <a name="project"></a><span data-ttu-id="3b507-377">Project</span><span class="sxs-lookup"><span data-stu-id="3b507-377">Project</span></span>

- <span data-ttu-id="3b507-378">Se corrigió un problema por el que, cuando se asignó un recurso de costo a una tarea hito, el costo de línea base no se acumulaba correctamente.</span><span class="sxs-lookup"><span data-stu-id="3b507-378">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


- <span data-ttu-id="3b507-379">Se ha corregido un problema en el que los bordes no se mostraban para las tareas en la vista Organizador de equipo.</span><span class="sxs-lookup"><span data-stu-id="3b507-379">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="3b507-380">Se ha corregido un problema en el que la opción de arrastrar y colocar no funcionaba para las tareas de la vista Organizador de equipo.</span><span class="sxs-lookup"><span data-stu-id="3b507-380">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


### <a name="office-suite"></a><span data-ttu-id="3b507-381">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="3b507-381">Office Suite</span></span>

- <span data-ttu-id="3b507-382">Soluciona un problema relacionado con las notificaciones de eventos del controlador multimedia.</span><span class="sxs-lookup"><span data-stu-id="3b507-382">Fixes an issue related to media controller event notifications.</span></span>


- <span data-ttu-id="3b507-383">Soluciona un problema relacionado con los intervalos de los motores del reproductor multimedia.</span><span class="sxs-lookup"><span data-stu-id="3b507-383">Fixes an issue related to media player engine timing.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2012-march-09"></a><span data-ttu-id="3b507-385">Versión 2012: 09 de febrero</span><span class="sxs-lookup"><span data-stu-id="3b507-385">Version 2012: March 09</span></span>
<span data-ttu-id="3b507-386">*Versión 2012 (compilación 13530.20628)*</span><span class="sxs-lookup"><span data-stu-id="3b507-386">*Version 2012 (Build 13530.20628)*</span></span>

<span data-ttu-id="3b507-387">Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="3b507-387">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="3b507-389">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="3b507-389">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="3b507-390">Excel</span><span class="sxs-lookup"><span data-stu-id="3b507-390">Excel</span></span>

- <span data-ttu-id="3b507-391">**Requerir que los usuarios apliquen etiquetas de confidencialidad:** Se pedirá a los usuarios que apliquen una etiqueta de confidencialidad si la directiva de su organización lo requiere.</span><span class="sxs-lookup"><span data-stu-id="3b507-391">**Require users to apply sensitivity labels:** Users will be prompted to apply a sensitivity label if their organization's policy requires it.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3b507-392">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3b507-392">PowerPoint</span></span>

- <span data-ttu-id="3b507-393">**Requerir que los usuarios apliquen etiquetas de confidencialidad:** Se pedirá a los usuarios que apliquen una etiqueta de confidencialidad si la directiva de su organización lo requiere.</span><span class="sxs-lookup"><span data-stu-id="3b507-393">**Require users to apply sensitivity labels:** Users will be prompted to apply a sensitivity label if their organization's policy requires it.</span></span>

### <a name="word"></a><span data-ttu-id="3b507-394">Word</span><span class="sxs-lookup"><span data-stu-id="3b507-394">Word</span></span>

- <span data-ttu-id="3b507-395">**Requerir que los usuarios apliquen etiquetas de confidencialidad:** Se pedirá a los usuarios que apliquen una etiqueta de confidencialidad si la directiva de su organización lo requiere.</span><span class="sxs-lookup"><span data-stu-id="3b507-395">**Require users to apply sensitivity labels:** Users will be prompted to apply a sensitivity label if their organization's policy requires it.</span></span>


## <a name="version-2012-february-09"></a><span data-ttu-id="3b507-396">Versión 2012: 09 de febrero</span><span class="sxs-lookup"><span data-stu-id="3b507-396">Version 2012: February 09</span></span>
<span data-ttu-id="3b507-397">*Versión 2012 (compilación 13530.20528)*</span><span class="sxs-lookup"><span data-stu-id="3b507-397">*Version 2012 (Build 13530.20528)*</span></span>

<span data-ttu-id="3b507-398">Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="3b507-398">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="3b507-400">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="3b507-400">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="3b507-401">Excel</span><span class="sxs-lookup"><span data-stu-id="3b507-401">Excel</span></span>

- <span data-ttu-id="3b507-402">**Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="3b507-402">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="3b507-403">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-403">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="3b507-404">**Registro de auditoría de etiquetas de confidencialidad:** cuando los usuarios aplican, cambian o quitan etiquetas de confidencialidad en sus documentos y correos electrónicos, esa información está ahora disponible para los administradores en los registros de auditoría de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="3b507-404">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="3b507-405">**Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H.</span><span class="sxs-lookup"><span data-stu-id="3b507-405">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="3b507-406">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-406">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="3b507-407">Outlook</span><span class="sxs-lookup"><span data-stu-id="3b507-407">Outlook</span></span>

- <span data-ttu-id="3b507-408">**Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="3b507-408">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="3b507-409">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-409">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="3b507-410">**Dar algo de tiempo entre reuniones consecutivas:** asigne a los asistentes el tiempo necesario para que descansen o se desplacen entre las distintas ubicaciones. Para ello haga que las reuniones empiecen de 5 a 10 minutos antes de forma predeterminada.</span><span class="sxs-lookup"><span data-stu-id="3b507-410">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="3b507-411">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-411">Learn more</span></span>](https://support.office.com/article/ebb4c4c9-6992-4ea7-9772-8b5883df8500)

- <span data-ttu-id="3b507-412">**Registro de auditoría de etiquetas de confidencialidad:** cuando los usuarios aplican, cambian o quitan etiquetas de confidencialidad en sus documentos y correos electrónicos, esa información está ahora disponible para los administradores en los registros de auditoría de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="3b507-412">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="3b507-413">**Todas las reuniones en línea:** Actualice la configuración del calendario para que cada reunión que cree se cree sea una reunión de Teams de forma predeterminada, de modo que no tenga que recordar hacer clic en la opción Reunión de Teams</span><span class="sxs-lookup"><span data-stu-id="3b507-413">**Every meeting online:** Update your calendar settings to make every meeting you create a Teams Meeting by default so you no longer need to remember to click the Teams Meeting option.</span></span>

- <span data-ttu-id="3b507-414">**Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H.</span><span class="sxs-lookup"><span data-stu-id="3b507-414">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="3b507-415">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-415">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

- <span data-ttu-id="3b507-416">**Todas las reuniones en línea:** Actualice la configuración del calendario para que cada reunión que cree se cree sea una reunión de Teams de forma predeterminada, de modo que no tenga que recordar hacer clic en la opción Reunión de Teams</span><span class="sxs-lookup"><span data-stu-id="3b507-416">**Every meeting online:** Update your calendar settings to make every meeting you create a Teams Meeting by default so you no longer need to remember to click the Teams Meeting option.</span></span>

- <span data-ttu-id="3b507-417">**Nuevo buscador de salas:** búsqueda de salas de conferencias por distintas funcionalidades.</span><span class="sxs-lookup"><span data-stu-id="3b507-417">**New room finder:** Search for conference rooms by different capabilities.</span></span>

- <span data-ttu-id="3b507-418">**Nueva experiencia de reserva de sala de conferencias y área de trabajo:** se ha actualizado la experiencia de reserva de la sala de conferencias y, con ella, hemos agregado funcionalidades para permitirle programar áreas de trabajo individuales.</span><span class="sxs-lookup"><span data-stu-id="3b507-418">**New conference room and workspace booking experience:** The conference room booking experience has been refreshed, and with it we've added capabilities to allow you to schedule individual workspaces as well</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3b507-419">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3b507-419">PowerPoint</span></span>

- <span data-ttu-id="3b507-420">**Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="3b507-420">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="3b507-421">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-421">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="3b507-422">Ver detalles en [entrada de blog](https://insider.office.com/es-ES/blog/svg-content-office-third-party-apps)</span><span class="sxs-lookup"><span data-stu-id="3b507-422">See details in [blog post](https://insider.office.com/es-ES/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="3b507-423">**Registro de auditoría de etiquetas de confidencialidad:** cuando los usuarios aplican, cambian o quitan etiquetas de confidencialidad en sus documentos y correos electrónicos, esa información está ahora disponible para los administradores en los registros de auditoría de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="3b507-423">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="3b507-424">**Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H.</span><span class="sxs-lookup"><span data-stu-id="3b507-424">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="3b507-425">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-425">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="visio"></a><span data-ttu-id="3b507-426">Visio</span><span class="sxs-lookup"><span data-stu-id="3b507-426">Visio</span></span>

- <span data-ttu-id="3b507-427">**Nuevas galerías de símbolos y formas de Azure:** Hemos agregado muchas más galerías de símbolos para ayudarle a crear diagramas de Azure actualizados.</span><span class="sxs-lookup"><span data-stu-id="3b507-427">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="3b507-428">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-428">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a><span data-ttu-id="3b507-429">Word</span><span class="sxs-lookup"><span data-stu-id="3b507-429">Word</span></span>

- <span data-ttu-id="3b507-430">**Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="3b507-430">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="3b507-431">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-431">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="3b507-432">**Registro de auditoría de etiquetas de confidencialidad:** cuando los usuarios aplican, cambian o quitan etiquetas de confidencialidad en sus documentos y correos electrónicos, esa información está ahora disponible para los administradores en los registros de auditoría de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="3b507-432">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="3b507-433">**Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H.</span><span class="sxs-lookup"><span data-stu-id="3b507-433">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="3b507-434">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-434">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="3b507-437">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="3b507-437">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3b507-438">Excel</span><span class="sxs-lookup"><span data-stu-id="3b507-438">Excel</span></span>

- <span data-ttu-id="3b507-439">Este cambio soluciona un problema que impedía mostrar correctamente fuentes en ecuaciones.</span><span class="sxs-lookup"><span data-stu-id="3b507-439">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="3b507-440">Se ha corregido un problema por el que algunos usuarios veían incorrectamente una barra de mensajes que les informaba de una nueva versión de un archivo durante la coautoría.</span><span class="sxs-lookup"><span data-stu-id="3b507-440">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="3b507-441">Se ha corregido un problema que provocaba que Excel dejara macros deshabilitadas sin preguntar al abrir archivos de complemento de Excel que contuvieran macros Excel 4.0.</span><span class="sxs-lookup"><span data-stu-id="3b507-441">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="3b507-442">Corrige un problema por el que Excel no se iniciaba o se cerraba inesperadamente si se estaba usando cierta configuración de protección contra vulnerabilidades de Seguridad de Windows (SimExec, CallerCheck).</span><span class="sxs-lookup"><span data-stu-id="3b507-442">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="3b507-443">Se ha corregido un problema que provocaba que Excel se cerrara de manera inesperada al usar el menú "Mostrar valores como" para una tabla dinámica.</span><span class="sxs-lookup"><span data-stu-id="3b507-443">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="3b507-444">Hemos corregido un problema que interrumpía algunas macros heredadas de Excel 4.0 y Excel 5.0, así como algunas llamadas de VBA a dialogsheets.show.</span><span class="sxs-lookup"><span data-stu-id="3b507-444">We fixed an issue that broke some legacy Excel 4.0 and Excel 5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


### <a name="outlook"></a><span data-ttu-id="3b507-445">Outlook</span><span class="sxs-lookup"><span data-stu-id="3b507-445">Outlook</span></span>

- <span data-ttu-id="3b507-446">Se ha corregido un problema por el que la firma editada no podía guardarse tras pedirle al usuario que lo hiciera.</span><span class="sxs-lookup"><span data-stu-id="3b507-446">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>


- <span data-ttu-id="3b507-447">Se ha corregido un problema que provocaba que Outlook se cerrara de forma inesperada para algunos usuarios en ciertos escenarios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="3b507-447">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="3b507-448">Se ha corregido un problema que causaba que algunos clientes experimentaran un cuelgue mientras cargaban sus calendarios.</span><span class="sxs-lookup"><span data-stu-id="3b507-448">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


- <span data-ttu-id="3b507-449">Se ha corregido un problema que causaba que los usuarios que tienen buzones compartidos o delegados con jerarquías grandes en su perfil sufriesen bloqueos.</span><span class="sxs-lookup"><span data-stu-id="3b507-449">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3b507-450">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3b507-450">PowerPoint</span></span>

- <span data-ttu-id="3b507-451">Se ha corregido un problema por el que el comando tamaño de fuente, agregado a la herramienta de acceso rápido, se completaba automáticamente al tamaño de fuente definido más cercano al actualizarse.</span><span class="sxs-lookup"><span data-stu-id="3b507-451">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="3b507-452">Este cambio soluciona un problema que impedía mostrar correctamente fuentes en ecuaciones.</span><span class="sxs-lookup"><span data-stu-id="3b507-452">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="3b507-453">Este cambio resuelve un problema con el relleno de rutas al aplicar las operaciones de Combinar formas con determinadas geometrías.</span><span class="sxs-lookup"><span data-stu-id="3b507-453">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


### <a name="office-suite"></a><span data-ttu-id="3b507-454">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="3b507-454">Office Suite</span></span>

- <span data-ttu-id="3b507-455">Anaheim WebView aún no es compatible con Windows Information Protection.</span><span class="sxs-lookup"><span data-stu-id="3b507-455">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="3b507-456">Con esta corrección, la plataforma de complementos de Office retrocede al nivel inferior de WebView en un entorno habilitado para WIP.</span><span class="sxs-lookup"><span data-stu-id="3b507-456">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="3b507-457">Según el entorno de máquina del cliente, esto puede ser Edge Spartan WebView o Trident WebView.</span><span class="sxs-lookup"><span data-stu-id="3b507-457">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="3b507-458">Las vistas previas de nivel inferior son compatibles con WIP.</span><span class="sxs-lookup"><span data-stu-id="3b507-458">Both down level WebViews support WIP.</span></span>


- <span data-ttu-id="3b507-459">Tamaño binario optimizado.</span><span class="sxs-lookup"><span data-stu-id="3b507-459">Optimized binary size.</span></span>


- <span data-ttu-id="3b507-460">Se ha corregido la secuencia de cierre de archivos para que todos los componentes interdependientes se cierren correctamente.</span><span class="sxs-lookup"><span data-stu-id="3b507-460">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2011-february-09"></a><span data-ttu-id="3b507-462">Versión 2011: 09 de febrero</span><span class="sxs-lookup"><span data-stu-id="3b507-462">Version 2011: February 09</span></span>
<span data-ttu-id="3b507-463">*Versión 2011 (compilación 13426.20658)*</span><span class="sxs-lookup"><span data-stu-id="3b507-463">*Version 2011 (Build 13426.20658)*</span></span>

<span data-ttu-id="3b507-464">Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="3b507-464">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2011-january-12"></a><span data-ttu-id="3b507-465">Versión 2011: 12 de enero</span><span class="sxs-lookup"><span data-stu-id="3b507-465">Version 2011: January 12</span></span>
<span data-ttu-id="3b507-466">*Versión 2011 (Compilación 13426.20526)*</span><span class="sxs-lookup"><span data-stu-id="3b507-466">*Version 2011 (Build 13426.20526)*</span></span>

<span data-ttu-id="3b507-467">Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="3b507-467">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="3b507-469">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="3b507-469">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="3b507-470">Acceso</span><span class="sxs-lookup"><span data-stu-id="3b507-470">Access</span></span>

- <span data-ttu-id="3b507-471">**Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="3b507-471">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="3b507-472">Vaya a Archivos > Cuenta y elija "Usar la opción del sistema" en la lista desplegable Temas de Office.</span><span class="sxs-lookup"><span data-stu-id="3b507-472">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="3b507-473">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-473">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="3b507-474">Excel</span><span class="sxs-lookup"><span data-stu-id="3b507-474">Excel</span></span>

- <span data-ttu-id="3b507-475">**Crear variables para usar en fórmulas:** mejorar el rendimiento, la legibilidad y la composición con la función LET.</span><span class="sxs-lookup"><span data-stu-id="3b507-475">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="3b507-476">Esta función le permite crear variables con nombre en fórmulas nuevas o previamente existentes.</span><span class="sxs-lookup"><span data-stu-id="3b507-476">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="3b507-477">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-477">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="3b507-478">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span><span class="sxs-lookup"><span data-stu-id="3b507-478">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="3b507-479">**Crear un tipo de datos personalizado en Power Query:** use cualquier origen de datos para crear un tipo de datos personalizado que le permita cargar varias piezas de información relacionadas en una columna.</span><span class="sxs-lookup"><span data-stu-id="3b507-479">**Create a custom data type in Power Query:** Use any data source to create a custom data type that lets you load multiple related pieces of information into one column.</span></span> [<span data-ttu-id="3b507-480">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-480">Learn more</span></span>](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br /><span data-ttu-id="3b507-481">Ver detalles en [entrada de blog](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span><span class="sxs-lookup"><span data-stu-id="3b507-481">See details in [blog post](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span></span>

- <span data-ttu-id="3b507-482">**Dele un nombre a la nueva hoja después de la consulta de origen:** cuando se carguen los datos en la nueva hoja, la hoja recibirá un nombre basado en el nombre de la consulta de origen.</span><span class="sxs-lookup"><span data-stu-id="3b507-482">**Name the new sheet after the source query:** When the data is loaded into the new sheet, the sheet will be named based on the name of the source query.</span></span>

- <span data-ttu-id="3b507-483">**Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="3b507-483">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="3b507-484">Vaya a Archivos > Cuenta y elija "Usar la opción del sistema" en la lista desplegable Temas de Office.</span><span class="sxs-lookup"><span data-stu-id="3b507-484">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="3b507-485">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-485">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a><span data-ttu-id="3b507-486">OneNote</span><span class="sxs-lookup"><span data-stu-id="3b507-486">OneNote</span></span>

- <span data-ttu-id="3b507-487">**Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="3b507-487">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="3b507-488">Vaya a Archivos > Cuenta y elija "Usar la opción del sistema" en la lista desplegable Temas de Office.</span><span class="sxs-lookup"><span data-stu-id="3b507-488">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="3b507-489">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-489">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="3b507-490">Outlook</span><span class="sxs-lookup"><span data-stu-id="3b507-490">Outlook</span></span>

- <span data-ttu-id="3b507-491">**Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="3b507-491">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="3b507-492">Vaya a Archivos > Cuenta y elija "Usar la opción del sistema" en la lista desplegable Temas de Office.</span><span class="sxs-lookup"><span data-stu-id="3b507-492">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="3b507-493">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-493">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


### <a name="powerpoint"></a><span data-ttu-id="3b507-494">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3b507-494">PowerPoint</span></span>

- <span data-ttu-id="3b507-495">**Biblioteca de vídeos:** Mejore sus documentos con una biblioteca de videos seleccionados y libres de regalías disponibles en la aplicación.</span><span class="sxs-lookup"><span data-stu-id="3b507-495">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app.</span></span>

- <span data-ttu-id="3b507-496">**Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="3b507-496">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="3b507-497">Vaya a Archivos > Cuenta y elija "Usar la opción del sistema" en la lista desplegable Temas de Office.</span><span class="sxs-lookup"><span data-stu-id="3b507-497">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="3b507-498">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-498">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a><span data-ttu-id="3b507-499">Project</span><span class="sxs-lookup"><span data-stu-id="3b507-499">Project</span></span>

- <span data-ttu-id="3b507-500">**Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="3b507-500">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="3b507-501">Vaya a Archivos > Cuenta y elija "Usar la opción del sistema" en la lista desplegable Temas de Office.</span><span class="sxs-lookup"><span data-stu-id="3b507-501">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="3b507-502">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-502">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="3b507-503">Publisher</span><span class="sxs-lookup"><span data-stu-id="3b507-503">Publisher</span></span>

- <span data-ttu-id="3b507-504">**Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="3b507-504">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="3b507-505">Vaya a Archivos > Cuenta y elija "Usar la opción del sistema" en la lista desplegable Temas de Office.</span><span class="sxs-lookup"><span data-stu-id="3b507-505">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="3b507-506">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-506">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="3b507-507">Visio</span><span class="sxs-lookup"><span data-stu-id="3b507-507">Visio</span></span>

- <span data-ttu-id="3b507-508">**Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="3b507-508">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="3b507-509">Vaya a Archivos > Cuenta y elija "Usar la opción del sistema" en la lista desplegable Temas de Office.</span><span class="sxs-lookup"><span data-stu-id="3b507-509">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="3b507-510">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-510">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="3b507-511">Word</span><span class="sxs-lookup"><span data-stu-id="3b507-511">Word</span></span>

- <span data-ttu-id="3b507-512">**Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="3b507-512">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="3b507-513">Vaya a Archivos > Cuenta y elija "Usar la opción del sistema" en la lista desplegable Temas de Office.</span><span class="sxs-lookup"><span data-stu-id="3b507-513">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="3b507-514">Más información</span><span class="sxs-lookup"><span data-stu-id="3b507-514">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="3b507-517">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="3b507-517">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3b507-518">Excel</span><span class="sxs-lookup"><span data-stu-id="3b507-518">Excel</span></span>

- <span data-ttu-id="3b507-519">Se ha corregido un problema por el que Excel mostraba de forma incorrecta una barra de mensajes donde se indicaba que estaba disponible una nueva versión del archivo y obligaba al usuario a descartar los cambios o guardarlos en una copia del libro.</span><span class="sxs-lookup"><span data-stu-id="3b507-519">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="3b507-520">Se solucionó un problema que provocaba que Excel dejara macros deshabilitadas sin preguntar al abrir archivos de complemento de Excel que contuvieran macros Excel 4.0.</span><span class="sxs-lookup"><span data-stu-id="3b507-520">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


### <a name="outlook"></a><span data-ttu-id="3b507-521">Outlook</span><span class="sxs-lookup"><span data-stu-id="3b507-521">Outlook</span></span>

- <span data-ttu-id="3b507-522">Se ha corregido un problema que causaba que algunos usuarios no vieran ninguna firma en la lista desplegable a pesar de que se configuraron una o varias firmas.</span><span class="sxs-lookup"><span data-stu-id="3b507-522">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


- <span data-ttu-id="3b507-523">Se ha agregado una clave de registro que permite a los clientes deshabilitar la inclusión de hora de archivo para datos adjuntos en operaciones de IDataObject (es decir, arrastrar y soltar, portapapeles).</span><span class="sxs-lookup"><span data-stu-id="3b507-523">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="3b507-524">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="3b507-524">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="3b507-525">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="3b507-525">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="3b507-526">0 = se excluyen horas de archivo.</span><span class="sxs-lookup"><span data-stu-id="3b507-526">0 = filetimes are excluded.</span></span> <span data-ttu-id="3b507-527">1 = (predeterminado) se incluyen horas de archivo.</span><span class="sxs-lookup"><span data-stu-id="3b507-527">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="3b507-528">Se ha corregido un problema que provocaba que las imágenes en línea desaparecieran al responder a un mensaje con una etiqueta de protección de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="3b507-528">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="3b507-529">Se ha corregido un problema que interrumpía el evento MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="3b507-529">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="3b507-530">Se ha corregido un problema por el que el campo "Para" quedaba vacío al enviar un informe de estado en una tarea.</span><span class="sxs-lookup"><span data-stu-id="3b507-530">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="3b507-531">Se ha corregido un problema por el que los asistentes originales de algunas reuniones recibían una cancelación cuando otro asistente reenviaba la reunión.</span><span class="sxs-lookup"><span data-stu-id="3b507-531">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3b507-532">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3b507-532">PowerPoint</span></span>

- <span data-ttu-id="3b507-533">Se ha corregido un problema por el que algunos archivos de PowerPoint corruptos no se abrían correctamente, incluso después de una operación de reparación de documento.</span><span class="sxs-lookup"><span data-stu-id="3b507-533">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="3b507-534">Se ha corregido un problema que provocaba un error al guardar el archivo después de duplicar una diapositiva que contuviera un audio grabado recientemente.</span><span class="sxs-lookup"><span data-stu-id="3b507-534">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="3b507-535">Se ha corregido un problema de VBA por el que Slide.Shapes.AddMediaObject2 se bloqueaba con formatos de vídeo heredados (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="3b507-535">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="3b507-536">Este cambio resuelve un problema con el control de errores que pueden producirse durante la carga de vídeo.</span><span class="sxs-lookup"><span data-stu-id="3b507-536">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="3b507-537">Se ha corregido un problema relacionado con la función de copiar y pegar una ecuación de Word a PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3b507-537">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


### <a name="project"></a><span data-ttu-id="3b507-538">Project</span><span class="sxs-lookup"><span data-stu-id="3b507-538">Project</span></span>

- <span data-ttu-id="3b507-539">Se ha corregido un problema por el que algunos proyectos específicos podrían abrirse si había un problema con el archivo del proyecto en una parte específica de la carga.</span><span class="sxs-lookup"><span data-stu-id="3b507-539">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="3b507-540">Word</span><span class="sxs-lookup"><span data-stu-id="3b507-540">Word</span></span>

- <span data-ttu-id="3b507-541">Se ha corregido un error de aserción expuesto por puertas optimizadas que afectaba a Word.</span><span class="sxs-lookup"><span data-stu-id="3b507-541">Fix an assert bug exposed by optimized gates affecting Word.</span></span>


- <span data-ttu-id="3b507-542">Se ha corregido un problema que reemplazaba los estilos del documento con otros estilos de la plantilla.</span><span class="sxs-lookup"><span data-stu-id="3b507-542">We fixed an issue which document styles are replaced with other styles from the template.</span></span>


- <span data-ttu-id="3b507-543">Este cambio resuelve un problema con el cursor al editar un documento.</span><span class="sxs-lookup"><span data-stu-id="3b507-543">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="3b507-544">Se ha corregido un problema relacionado con la función de copiar y pegar una ecuación de Word a PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3b507-544">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


### <a name="office-suite"></a><span data-ttu-id="3b507-545">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="3b507-545">Office Suite</span></span>

- <span data-ttu-id="3b507-546">Se ha corregido un problema por el que la instalación de una versión más reciente de Office sobre algunas versiones anteriores podía resultar en un deterioro de la funcionalidad (por ejemplo, la imposibilidad de usar Power Query) debido a la falta de entradas del registro.</span><span class="sxs-lookup"><span data-stu-id="3b507-546">Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>


- <span data-ttu-id="3b507-547">Se ha corregido un problema por el que un archivo se abría como NO SyncBacked cuando la dirección URL de la memoria caché y la dirección URL de OneDrive NO coincidían.</span><span class="sxs-lookup"><span data-stu-id="3b507-547">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>


- <span data-ttu-id="3b507-548">Se ha corregido un problema que provocaba que SaveRequestManagerCam causara que la aplicación se cerrara en lugar de devolver un error.</span><span class="sxs-lookup"><span data-stu-id="3b507-548">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2010-january-12"></a><span data-ttu-id="3b507-550">Versión 2010: 12 de enero</span><span class="sxs-lookup"><span data-stu-id="3b507-550">Version 2010: January 12</span></span>
<span data-ttu-id="3b507-551">*Versión 2010 (compilación 13328.20550)*</span><span class="sxs-lookup"><span data-stu-id="3b507-551">*Version 2010 (Build 13328.20550)*</span></span>

<span data-ttu-id="3b507-552">Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="3b507-552">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

[//]: # (NO QUITAR FINAL)

> [!NOTE]
> <span data-ttu-id="3b507-556">Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="3b507-556">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (NO MODIFICAR EL INICIO DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
[//]: # (|Win32|MEC|Production|Feature|16.0.14026.20334|version-2105-july-13|)
[//]: # (|Win32|MEC|Producción|Característica|16.0.13929.20408|version-2104-junio-08|)
[//]: # (|Win32|MEC|Producción|Característica|16.0.13901.20516|version-11-marzo-2103|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13801.20506|versión-2102-13-abril|)
[//]: # (|Win32|MEC|Producción|Característica|16.0.13628.20528|version-2101-marzo-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13530.20528|version-2012-february-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13426.20526|version-2011-january-12|)
[//]: # (|Win32|MEC|Producción|Característica|16.0.13328.20478|versión-08-diciembre-2010|)
[//]: # (|Win32|MEC|Producción|Característica|16.0.13231.20514|versión-10-noviembre-2009|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13127.20638|versión-13-octubre-2008|)
[//]: # (NO MODIFICAR EL FIN DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
