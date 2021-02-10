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
ms.openlocfilehash: 6b50195e2e84292b0b4b1e259254592f2c4a591b
ms.sourcegitcommit: 568fdf9ae96367ef3a4f601128df80944dd265a7
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 02/10/2021
ms.locfileid: "50173659"
---
# <a name="release-notes-for-semi-annual-enterprise-channel"></a><span data-ttu-id="cb83e-103">Notas de la versión para el canal semestral para empresas</span><span class="sxs-lookup"><span data-stu-id="cb83e-103">Release notes for Semi-Annual Enterprise Channel</span></span>

<span data-ttu-id="cb83e-104">Estas notas de la versión proporcionan información sobre las nuevas características y las actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones del canal semestral para empresas para las Aplicaciones de Microsoft 365 para empresas, las Aplicaciones de Microsoft 365 para negocios, y las versiones de suscripción de las aplicaciones de escritorio de Project y Visio.</span><span class="sxs-lookup"><span data-stu-id="cb83e-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="cb83e-105">Estamos realizando algunos cambios en los canales de actualización de las Aplicaciones de Microsoft 365, incluida la adición de un nuevo canal de actualización (canal empresarial mensual) y el cambio de los nombres de los canales de actualización existentes.</span><span class="sxs-lookup"><span data-stu-id="cb83e-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="cb83e-106">[Lea este artículo](https://go.microsoft.com/fwlink/p/?linkid=2127441) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="cb83e-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="cb83e-107">OneNote 2016 ahora se incluirá de forma predeterminada cuando un usuario en el canal empresarial semestral descargue e instale las Aplicaciones de Microsoft 365 en Windows 10 desde el Portal de Office.</span><span class="sxs-lookup"><span data-stu-id="cb83e-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-february-09"></a><span data-ttu-id="cb83e-109">Versión 2008: 09 de febrero</span><span class="sxs-lookup"><span data-stu-id="cb83e-109">Version 2008: February 09</span></span>
<span data-ttu-id="cb83e-110">*Versión 2008 (compilación 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-110">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="cb83e-111">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-113">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-113">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb83e-114">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-114">Excel</span></span>

- <span data-ttu-id="cb83e-115">Se ha corregido un problema por el que Excel se cerraba inesperadamente al abrir archivos UNC con atributos de archivo no válidos (hora de creación, fecha de modificación, etc.).</span><span class="sxs-lookup"><span data-stu-id="cb83e-115">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="cb83e-116">Hemos corregido un problema por el que la configuración de los separadores decimales y de millares no se mantenía al copiar un gráfico de Excel y pegarlo en Word o PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-116">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="cb83e-117">Hemos corregido un problema por el que el rendimiento de ejecutar una macro que implicaba el formato de rango de tabla dinámica sería peor cada vez que se ejecutase la macro.</span><span class="sxs-lookup"><span data-stu-id="cb83e-117">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="cb83e-118">Hemos corregido un problema por el que se eliminaron las reglas de formato condicional al copiar o mover hojas a otro libro.</span><span class="sxs-lookup"><span data-stu-id="cb83e-118">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="cb83e-119">Hemos corregido un problema por el que los usuarios no podían aplicar etiquetas de confidencialidad a los archivos de Excel cuando la pantalla de inicio de la aplicación estaba deshabilitada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-119">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="cb83e-120">Hemos corregido un problema al abrir archivos en la nube de la carpeta de sincronización de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="cb83e-120">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="cb83e-121">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-121">Outlook</span></span>

- <span data-ttu-id="cb83e-122">Resuelto un problema que hacía que Outlook dejara de funcionar esporádicamente al agregar o guardar datos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-122">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="cb83e-123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb83e-123">PowerPoint</span></span>

- <span data-ttu-id="cb83e-124">Se ha corregido un problema por el que el comando tamaño de fuente, agregado a la herramienta de acceso rápido, se completaba automáticamente al tamaño de fuente definido más cercano al actualizarse.</span><span class="sxs-lookup"><span data-stu-id="cb83e-124">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="cb83e-125">Se ha corregido un problema que causaba que, al copiar y pegar una diapositiva con la opción "Mantener formato de origen", a veces se copiara de forma inesperada sobre un nuevo patrón de diapositivas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-125">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="cb83e-126">Word</span><span class="sxs-lookup"><span data-stu-id="cb83e-126">Word</span></span>

- <span data-ttu-id="cb83e-127">Corregimos un problema en control de cambios que a veces es posible que abra un documento de Word.</span><span class="sxs-lookup"><span data-stu-id="cb83e-127">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="cb83e-128">Hemos corregido un problema al abrir archivos en la nube de la carpeta de sincronización de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="cb83e-128">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="cb83e-129">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-129">Office Suite</span></span>

- <span data-ttu-id="cb83e-130">Se ha corregido un problema que impedía abrir correctamente un archivo en Office.</span><span class="sxs-lookup"><span data-stu-id="cb83e-130">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="cb83e-131">Se ha corregido un problema por el que los documentos que contenían contornos esbozados aplicados a conectores a través de Copiar formato podrían dañarse.</span><span class="sxs-lookup"><span data-stu-id="cb83e-131">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2002-february-09"></a><span data-ttu-id="cb83e-133">Versión 2002: 09 de febrero</span><span class="sxs-lookup"><span data-stu-id="cb83e-133">Version 2002: February 09</span></span>
<span data-ttu-id="cb83e-134">*Versión 2002 (compilación 12527.21594)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-134">*Version 2002 (Build 12527.21594)*</span></span>

<span data-ttu-id="cb83e-135">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-135">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-137">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-137">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="cb83e-138">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-138">Office Suite</span></span>

- <span data-ttu-id="cb83e-139">Se ha corregido un problema por el que los documentos que contenían contornos esbozados aplicados a conectores a través de Copiar formato podrían dañarse.</span><span class="sxs-lookup"><span data-stu-id="cb83e-139">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-1908-february-09"></a><span data-ttu-id="cb83e-141">Versión 1908: 09 de febrero</span><span class="sxs-lookup"><span data-stu-id="cb83e-141">Version 1908: February 09</span></span>
<span data-ttu-id="cb83e-142">*Versión 1908 (compilación 11929.21008)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-142">*Version 1908 (Build 11929.21008)*</span></span>

<span data-ttu-id="cb83e-143">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-143">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2008-january-12"></a><span data-ttu-id="cb83e-144">Versión 2008: 12 de enero</span><span class="sxs-lookup"><span data-stu-id="cb83e-144">Version 2008: January 12</span></span>
<span data-ttu-id="cb83e-145">*Versión 2008 (compilación 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-145">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="cb83e-146">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-146">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="cb83e-148">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="cb83e-148">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="cb83e-149">Access</span><span class="sxs-lookup"><span data-stu-id="cb83e-149">Access</span></span>

- <span data-ttu-id="cb83e-150">**Aumente su productividad con el Diseñador de consultas, la vista SQL y la ventana Relaciones:** haga clic con el botón derecho en una tabla para abrirla, diseñarla, cambiar su tamaño y ocultarla.</span><span class="sxs-lookup"><span data-stu-id="cb83e-150">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="cb83e-151">Buscar y reemplazar texto en la vista SQL.</span><span class="sxs-lookup"><span data-stu-id="cb83e-151">Search and replace text in SQL View.</span></span> <span data-ttu-id="cb83e-152">Seleccione múltiples tablas en la ventana Relaciones.</span><span class="sxs-lookup"><span data-stu-id="cb83e-152">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="cb83e-153">**Agregue tablas con menos clics:** utilizar el panel de tareas agregar tablas, que permanece abierto mientras trabaja, para agregar tablas a relaciones y consultas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-153">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="cb83e-154">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-154">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="cb83e-155">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-155">Excel</span></span>

- <span data-ttu-id="cb83e-156">**Sus funciones favoritas de Excel se han vuelto más rápidas:** las funciones SUMAR.SI.CONJUNTO, CONTAR.SI.CONJUNTO, PROMEDIO.SI.CONJUNTO, MAX.SI.CONJUNTO y MIN.SI.CONJUNTO son más rápidas que nunca.</span><span class="sxs-lookup"><span data-stu-id="cb83e-156">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="cb83e-157">Llegue al final más rápidamente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-157">Get to the bottom line more quickly.</span></span> <span data-ttu-id="cb83e-158">Pruebe ahora una.</span><span class="sxs-lookup"><span data-stu-id="cb83e-158">Try one now.</span></span>

- <span data-ttu-id="cb83e-159">**Mejoras de RealTimeData (RTD):** En la versión Microsoft Office 365 2002 canal mensual y posterior, la función RealTimeData (RTD) de Excel es mucho más rápida que calcular datos en la hoja de cálculo en Excel 2010.</span><span class="sxs-lookup"><span data-stu-id="cb83e-159">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="cb83e-160">Hemos evitado atascos en su memoria subyacente y en las estructuras de datos, así como permitido el uso seguro de subprocesos para que se pueda calcular en todos los subprocesos disponibles de Recálculo multiproceso (MTR).</span><span class="sxs-lookup"><span data-stu-id="cb83e-160">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

- <span data-ttu-id="cb83e-161">**Gráficos de mapa mejorados:** hemos integrado los gráficos de mapa con los tipos de datos geográficos de Excel, para que revelen información de todo tipo sobre las ubicaciones que desee.</span><span class="sxs-lookup"><span data-stu-id="cb83e-161">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="cb83e-162">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-162">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="cb83e-163">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="cb83e-163">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="cb83e-164">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-164">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="cb83e-165">**Crear tablas dinámicas de conjuntos de datos en Power BI desde Excel:** puede crear tablas dinámicas en Excel conectadas a los conjuntos de datos almacenados en Power BI con tan solo unos clics.</span><span class="sxs-lookup"><span data-stu-id="cb83e-165">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="cb83e-166">Así, podrá obtener lo mejor de las tablas dinámicas y de Power BI.</span><span class="sxs-lookup"><span data-stu-id="cb83e-166">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="cb83e-167">Calcule, resuma y analice sus datos con tablas dinámicas desde sus conjuntos de datos seguros de Power BI.</span><span class="sxs-lookup"><span data-stu-id="cb83e-167">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="cb83e-168">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-168">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="cb83e-169">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-169">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="cb83e-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-170">Outlook</span></span>

- <span data-ttu-id="cb83e-171">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="cb83e-171">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="cb83e-172">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-172">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="cb83e-173">**El calendario se transforma:** vea las actualizaciones visuales que hacen que el calendario sea más fácil de examinar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-173">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="cb83e-174">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-174">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="cb83e-175">Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-175">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="cb83e-176">**Las actualizaciones del calendario compartido son más rápidas:** Outlook puede actualizar los calendarios compartidos en Office 365 con la API de REST.</span><span class="sxs-lookup"><span data-stu-id="cb83e-176">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="cb83e-177">Active la vista previa para obtener actualizaciones más rápidas y confiables en los calendarios compartidos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-177">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="cb83e-178">**Arrastre el correo electrónico a un grupo de tu propiedad:** Mueva y copie mensajes y conversaciones arrastrándolos desde su bandeja de entrada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-178">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="cb83e-179">Los mensajes que arrastres serán compartidos con todos los miembros del grupo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-179">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="cb83e-180">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-180">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="cb83e-181">**Unirse a reuniones sin salir de la bandeja de entrada:** no es necesario cambiar al calendario para unirse a reuniones en línea.</span><span class="sxs-lookup"><span data-stu-id="cb83e-181">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="cb83e-182">Con el Calendario de Outlook anclado en el panel de tareas pendientes, únase a una reunión con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="cb83e-182">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span> [<span data-ttu-id="cb83e-183">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-183">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="cb83e-184">**Nueva experiencia para redes WiFi cautivas:** ¿alguna vez se ha unido a una red WiFi que requiere una página web para iniciar sesión?</span><span class="sxs-lookup"><span data-stu-id="cb83e-184">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="cb83e-185">Outlook ahora lo detecta y le ayuda a estar conectado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-185">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="cb83e-186">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span><span class="sxs-lookup"><span data-stu-id="cb83e-186">See details in [blog post](https://insider.office.com/es-ES/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="cb83e-187">**Obtener sugerencias de correo electrónico cuando busca un contacto:** cuando escriba el nombre de una persona en el cuadro de búsqueda, se incluirán los mensajes de correo electrónico más relevantes con las sugerencias de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="cb83e-187">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="cb83e-188">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-188">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

- <span data-ttu-id="cb83e-189">**Mejores resultados, en un instante:** actualizamos la experiencia de búsqueda para que sea más inteligente, rápida y fiable que nunca.</span><span class="sxs-lookup"><span data-stu-id="cb83e-189">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="cb83e-190">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-190">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

### <a name="powerpoint"></a><span data-ttu-id="cb83e-191">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb83e-191">PowerPoint</span></span>

- <span data-ttu-id="cb83e-192">**GIF en un instante:** una diapositiva, un marco.</span><span class="sxs-lookup"><span data-stu-id="cb83e-192">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="cb83e-193">Cree fácilmente archivos GIF en bucle en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-193">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="cb83e-194">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-194">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="cb83e-195">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-195">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="cb83e-196">**Vínculo a la diapositiva:** Pídale a un compañero que participe en la presentación de diapositivas y llévelo directamente a la diapositiva con la que necesita ayuda.</span><span class="sxs-lookup"><span data-stu-id="cb83e-196">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="cb83e-197">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-197">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="cb83e-198">Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-198">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="cb83e-199">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="cb83e-199">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="cb83e-200">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-200">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="cb83e-201">**Gráficos de mapa mejorados:** hemos integrado los gráficos de mapa con los tipos de datos geográficos de Excel, para que revelen información de todo tipo sobre las ubicaciones que desee.</span><span class="sxs-lookup"><span data-stu-id="cb83e-201">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="cb83e-202">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-202">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="cb83e-203">**Mejores diagramas** con mejores conectores y un proceso de conversión de entrada de lápiz más fluido, puede aplicar sus ideas con más confianza.</span><span class="sxs-lookup"><span data-stu-id="cb83e-203">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="cb83e-204">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-204">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="cb83e-205">**Mejor rendimiento de vídeos de Stream en PowerPoint:** hemos realizado mejoras en el rendimiento de la reproducción de los vídeos de Microsoft Stream para reducir el tiempo de carga de vídeo y crear una visualización más suave.</span><span class="sxs-lookup"><span data-stu-id="cb83e-205">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="cb83e-206">Use los vídeos corporativos de Microsoft Stream para crear presentaciones mejoradas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-206">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

- <span data-ttu-id="cb83e-207">**Logre la atención de sus colegas con** @menciones:\@ use @menciones en los comentarios para avisar a los compañeros de trabajo cuando necesite su participación.</span><span class="sxs-lookup"><span data-stu-id="cb83e-207">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="cb83e-208">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-208">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="cb83e-209">**Sincronice los cambios mientras realiza la presentación:** sincronice los cambios cuando se hagan aunque la presentación esté en el modo de presentación con diapositivas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-209">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="cb83e-210">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-210">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="cb83e-211">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-211">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="cb83e-212">**Comentarios:** la nueva experiencia de comentarios en PowerPoint permite descubrir y agregar comentarios a los documentos de forma rápida y sencilla.</span><span class="sxs-lookup"><span data-stu-id="cb83e-212">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="cb83e-213">Modernice sus flujos de trabajo de colaboración con nuevas características como anclaje de comentarios, resuelva, tareas, notificaciones de menciones mejoradas y mucho más.</span><span class="sxs-lookup"><span data-stu-id="cb83e-213">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="cb83e-214">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-214">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

### <a name="word"></a><span data-ttu-id="cb83e-215">Word</span><span class="sxs-lookup"><span data-stu-id="cb83e-215">Word</span></span>

- <span data-ttu-id="cb83e-216">**Selección de lazo de la entrada de lápiz:** la herramienta Lazo en la pestaña Dibujar le ayuda a seleccionar objetos dibujados a mano.</span><span class="sxs-lookup"><span data-stu-id="cb83e-216">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="cb83e-217">Seleccione trazos individuales o palabras completas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-217">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="cb83e-218">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-218">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="cb83e-219">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="cb83e-219">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="cb83e-220">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-220">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="cb83e-221">**Gráficos de mapa mejorados:** hemos integrado los gráficos de mapa con los tipos de datos geográficos de Excel, para que revelen información de todo tipo sobre las ubicaciones que desee.</span><span class="sxs-lookup"><span data-stu-id="cb83e-221">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="cb83e-222">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-222">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="cb83e-223">**Confirmación de acción en lectores de pantalla:** la confirmación de la acción es un requisito de accesibilidad importante.</span><span class="sxs-lookup"><span data-stu-id="cb83e-223">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="cb83e-224">Con la introducción de una nueva API de notificación de Windows, ahora podemos alertar a los usuarios de lectores de pantalla sobre el éxito de sus acciones.</span><span class="sxs-lookup"><span data-stu-id="cb83e-224">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="cb83e-225">Las opciones de cortar, copiar, pegar, negrita, cursiva, subrayado, deshacer, rehacer, corrección automática y uso automático de mayúsculas ahora se anuncian a los usuarios del narrador en Word Win32.</span><span class="sxs-lookup"><span data-stu-id="cb83e-225">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="cb83e-226">Para habilitar esta característica, active el narrador presionando Windows + Ctrl + Entrar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-226">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="cb83e-227">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-227">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="cb83e-228">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-228">Office Suite</span></span>

- <span data-ttu-id="cb83e-229">**Etiquetas de confidencialidad:** ahora puede aplicar una etiqueta de confidencialidad que su organización ha configurado para solicitarle permisos personalizados.</span><span class="sxs-lookup"><span data-stu-id="cb83e-229">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-232">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-232">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="cb83e-233">Access</span><span class="sxs-lookup"><span data-stu-id="cb83e-233">Access</span></span>

- <span data-ttu-id="cb83e-234">Se ha corregido un problema por el que la aplicación se cerraba inesperadamente al usar la ventana zoom.</span><span class="sxs-lookup"><span data-stu-id="cb83e-234">Fixed an issue where the application would  close unexpectedly when using Zoom window.</span></span>


- <span data-ttu-id="cb83e-235">Esta corrección resuelve un problema por el que al intentar ejecutar determinadas consultas anteriormente se generaba el mensaje de error "La consulta es demasiado compleja".</span><span class="sxs-lookup"><span data-stu-id="cb83e-235">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>


- <span data-ttu-id="cb83e-236">Este cambio corrige un problema que podía provocar que Access se cerrara inesperadamente al iniciar el cuadro de Zoom (Mayús + F2) para editar el texto.</span><span class="sxs-lookup"><span data-stu-id="cb83e-236">This change fixes an issue that could cause Access to to close unexpectedly when launching the Zoom box (Shift + F2) to edit text.</span></span>


- <span data-ttu-id="cb83e-237">Se ha resuelto un problema al insertar tablas SQL vinculadas que incluyan un campo de identidad (por ejemplo, autonumeración).</span><span class="sxs-lookup"><span data-stu-id="cb83e-237">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>


- <span data-ttu-id="cb83e-238">Se ha corregido un problema que provocaba que la ejecución de consultas tardara en completarse aproximadamente el doble del tiempo esperado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-238">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>


- <span data-ttu-id="cb83e-239">Se ha corregido un problema para poder llamar al tipo de datos Fecha/Hora ampliado en el código sin tener problemas con la aplicación.</span><span class="sxs-lookup"><span data-stu-id="cb83e-239">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any issues in your app.</span></span>


- <span data-ttu-id="cb83e-240">Se ha corregido un problema de forma que ahora puede volver a la versión de Access más actualizada y usar DAO/VBA para administrar y editar un tipo de datos decimal.</span><span class="sxs-lookup"><span data-stu-id="cb83e-240">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>


- <span data-ttu-id="cb83e-241">Se ha corregido un problema que producía un error al intentar usar el generador de DSN de ODBC.</span><span class="sxs-lookup"><span data-stu-id="cb83e-241">We fixed an error issue when trying to use ODBC DSN builder</span></span>


- <span data-ttu-id="cb83e-242">Este problema se ha resuelto: ahora puede usar el controlador ODBC fuera de las aplicaciones de Hacer clic y ejecutar de Office.</span><span class="sxs-lookup"><span data-stu-id="cb83e-242">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>


### <a name="excel"></a><span data-ttu-id="cb83e-243">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-243">Excel</span></span>

- <span data-ttu-id="cb83e-244">Es posible que se haya producido una clasificación de documentos automática en los libros que se encontraban en modo de solo lectura.</span><span class="sxs-lookup"><span data-stu-id="cb83e-244">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>


- <span data-ttu-id="cb83e-245">Se ha corregido un problema que podía producirse al intentar crear una conexión de datos si se había cerrado la sesión en la cuenta.</span><span class="sxs-lookup"><span data-stu-id="cb83e-245">Fixed an issue that could happen when trying to create a data connection if you have signed out from your account.</span></span>


- <span data-ttu-id="cb83e-246">Se ha corregido un error con las API de PivotDateFilter por el que se revertían las condiciones de filtro "Antes" y "Después".</span><span class="sxs-lookup"><span data-stu-id="cb83e-246">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="cb83e-247">Se ha corregido un problema por el que Excel se cerraba inesperadamente al intentar insertar tablas dinámicas en una hoja de gráfico.</span><span class="sxs-lookup"><span data-stu-id="cb83e-247">Addressed an issue where Excel may close unexpectedly when attempting to insert PivotTables into a chart sheet.</span></span>


- <span data-ttu-id="cb83e-248">Se ha corregido un problema que provocaba que las tablas dinámicas no se pudieran editar y los libros no se pudieran guardar si se exportaban desde el plan de Project.</span><span class="sxs-lookup"><span data-stu-id="cb83e-248">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="cb83e-249">Se podía producir un error al intentar guardar un archivo que tuviera una fórmula con la función LET().</span><span class="sxs-lookup"><span data-stu-id="cb83e-249">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>


- <span data-ttu-id="cb83e-250">Se ha corregido un problema que provocaba que, en algunos casos, aparecieran varias barras de mensajes al abrir un archivo en modo de solo lectura.</span><span class="sxs-lookup"><span data-stu-id="cb83e-250">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="cb83e-251">Se ha corregido un problema que provocaba que los subtotales de esquema pudieran dejar de funcionar cuando había muchos valores de encabezado de columna duplicados.</span><span class="sxs-lookup"><span data-stu-id="cb83e-251">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="cb83e-252">Se ha corregido un problema por el que los libros de solo lectura dejaban de actualizar los datos de las tablas dinámicas al abrirlos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-252">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="cb83e-253">Este cambio corrige el siguiente problema: "Insertar objeto" de Excel no muestra el icono correcto cuando se inserta un archivo desde la carpeta de sincronización local de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="cb83e-253">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="cb83e-254">Se ha corregido un problema que provocaba que Excel dejara de funcionar cuando había una actualización del objeto de directiva de grupo (por ejemplo, mediante la actualización de la directiva de grupo remota) durante el recálculo multiproceso.</span><span class="sxs-lookup"><span data-stu-id="cb83e-254">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="cb83e-255">Se ha corregido un problema que provocaba que Excel dejara de funcionar cuando los usuarios utilizaban la función subtotal en más de 255 columnas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-255">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="cb83e-256">Interletraje de texto mejorado en PowerPoint cuando se copia contenido de Excel y se pega en PowerPoint con la opción Insertar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-256">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="cb83e-257">Se ha corregido un problema que impedía cambiar entre la vista previa de la tabla y el editor de consultas en PowerPivot.</span><span class="sxs-lookup"><span data-stu-id="cb83e-257">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="cb83e-258">Se ha corregido un problema que provocaba que el usuario no pudiera abrir el archivo atomsvc (UTF8+BOM) directamente desde SharePoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-258">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="cb83e-259">Se ha corregido un problema por el que los clientes recibían una notificación incorrecta sobre una nueva versión del archivo durante la coautoría.</span><span class="sxs-lookup"><span data-stu-id="cb83e-259">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="cb83e-260">Se ha corregido un problema de edición por el que al usar IME con el modo de sobrescritura se avanzaban incorrectamente caracteres adicionales.</span><span class="sxs-lookup"><span data-stu-id="cb83e-260">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="cb83e-261">Se ha corregido un problema que se producía al usar datos en tiempo real junto con la funcionalidad de recálculo multiproceso.</span><span class="sxs-lookup"><span data-stu-id="cb83e-261">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="cb83e-262">Corrige un problema por el que Excel no se podía iniciar o se bloqueaba inesperadamente si se usaba determinada configuración de protección contra vulnerabilidades de Seguridad de Windows (SimExec, CallerCheck).</span><span class="sxs-lookup"><span data-stu-id="cb83e-262">Fixes an issue where Excel would fail to launch or crash unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


- <span data-ttu-id="cb83e-263">Se ha corregido un problema por el que Excel se cerraba inesperadamente en determinadas circunstancias al usar Copiar formato.</span><span class="sxs-lookup"><span data-stu-id="cb83e-263">Fixed an issue where Excel could close unexpectedly in certain circumstances when using the Format Painter.</span></span>


- <span data-ttu-id="cb83e-264">Se corrigió un problema por el cual los usuarios no podían modificar un filtro de tabla dinámica porque estaba configurado en un valor que ya no estaba presente en una base de datos de Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="cb83e-264">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="cb83e-265">Se ha corregido un problema por el que Excel se cerraba inesperadamente al usar el Análisis rápido después de inmovilizar la fila superior de la hoja.</span><span class="sxs-lookup"><span data-stu-id="cb83e-265">Fixed an issue where Excel could close unexpectedly when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="cb83e-266">Se ha corregido un problema por el que algunas funciones podían tener un resultado incorrecto después de cargar un libro.</span><span class="sxs-lookup"><span data-stu-id="cb83e-266">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="cb83e-267">Se ha corregido un problema relacionado con las referencias de complemento de XLAM y los rangos con nombre que cerraba la aplicación de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-267">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="cb83e-268">Se ha corregido un problema por el que, al usar una macro para establecer la propiedad FormulaR1C1 para un rango, las referencias de celda eran incorrectas si una hoja de gráfico era la hoja activa.</span><span class="sxs-lookup"><span data-stu-id="cb83e-268">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="cb83e-269">Se ha corregido un problema por el que Excel indicaba por error que se había quedado sin recursos al intentar calcular una o varias fórmulas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-269">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="cb83e-270">Se ha corregido un problema que aparecía cuando se configuraba el idioma de Office en español. Este problema provocaba que las listas de validación de datos puedan no mostrar todos los elementos de la lista.</span><span class="sxs-lookup"><span data-stu-id="cb83e-270">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="cb83e-271">Se ha corregido un problema que podía producir un bloqueo al actualizar las tablas dinámicas de OLAP.</span><span class="sxs-lookup"><span data-stu-id="cb83e-271">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="cb83e-272">Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta al guardar en SharePoint o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="cb83e-272">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>


- <span data-ttu-id="cb83e-273">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="cb83e-273">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="cb83e-274">Se solucionó un problema por el cual, en algunos casos, al hacer clic en un hipervínculo a un lugar dentro del mismo libro de trabajo, el libro de trabajo se ocultaba.</span><span class="sxs-lookup"><span data-stu-id="cb83e-274">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


- <span data-ttu-id="cb83e-275">Application.Evaluate (VBA) no funcionaba para funciones definidas por el usuario en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-275">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>


- <span data-ttu-id="cb83e-276">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="cb83e-276">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


- <span data-ttu-id="cb83e-277">Se ha corregido un problema por el que Excel se cerraba inesperadamente en algunos casos después de copiar una hoja que contenía una tabla dinámica.</span><span class="sxs-lookup"><span data-stu-id="cb83e-277">Fixed an issue which would cause Excel to close unexpectedly in some cases after copying a sheet containing a PivotTable.</span></span>


- <span data-ttu-id="cb83e-278">Se ha corregido un problema por el que el vínculo externo dejaba de funcionar al volver a abrir un archivo si su ruta de acceso era demasiado larga.</span><span class="sxs-lookup"><span data-stu-id="cb83e-278">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>


- <span data-ttu-id="cb83e-279">Se ha corregido un problema por el que la aplicación podía cerrarse inesperadamente al usar datos en tiempo real junto con la funcionalidad de recálculo multiproceso.</span><span class="sxs-lookup"><span data-stu-id="cb83e-279">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality could cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="cb83e-280">Se ha corregido un problema por el que los enlaces externos no se actualizaban si el libro de origen estaba cerrado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-280">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>


- <span data-ttu-id="cb83e-281">Se ha corregido un problema que podía producir una advertencia acerca de un libro dañado si este contenía fórmulas que usan SI.ND().</span><span class="sxs-lookup"><span data-stu-id="cb83e-281">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


- <span data-ttu-id="cb83e-282">Se ha corregido un problema con Power Pivot. Ahora reconoce correctamente el delimitador de tabulaciones.</span><span class="sxs-lookup"><span data-stu-id="cb83e-282">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="onenote"></a><span data-ttu-id="cb83e-283">OneNote</span><span class="sxs-lookup"><span data-stu-id="cb83e-283">OneNote</span></span>

- <span data-ttu-id="cb83e-284">Se informa a los usuarios mediante la barra de información sobre los ajustes temporales de Microsoft OneNote que les ayudarán a mejorar la sincronización y la disponibilidad del servicio durante un uso mundial elevado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-284">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>


- <span data-ttu-id="cb83e-285">Mejora de la sincronización y la estabilidad del servicio al ajustar temporalmente la frecuencia de sincronización en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="cb83e-285">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>


- <span data-ttu-id="cb83e-286">Se mejoró la detección del estado de la coautoría para reducir el uso de recursos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-286">Improved detection of co-authoring status to reduce resource utilization.</span></span>


- <span data-ttu-id="cb83e-287">Mejora de la sincronización y la estabilidad del servicio al alterar temporalmente la frecuencia con la que se crean los historiales de las versiones de las páginas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-287">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>


- <span data-ttu-id="cb83e-288">Mejora de la sincronización y la estabilidad del servicio al reducir temporalmente el tamaño máximo de nuevos datos adjuntos insertados a 50 MB en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="cb83e-288">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="cb83e-289">Si los archivos superan este límite, los usuarios tendrán la opción de cargar el archivo a OneDrive e insertar un vínculo en OneNote.</span><span class="sxs-lookup"><span data-stu-id="cb83e-289">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>


- <span data-ttu-id="cb83e-290">Se obtiene una mejora de la sincronización y la estabilidad del servicio al deshabilitar temporalmente la grabación de vídeo en la aplicación en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="cb83e-290">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="cb83e-291">La medida no afecta a los blocs de notas locales.</span><span class="sxs-lookup"><span data-stu-id="cb83e-291">Local notebooks are not impacted by this measure.</span></span>


- <span data-ttu-id="cb83e-292">Se obtiene una mejora de la sincronización y la estabilidad del servicio al deshabilitar temporalmente el desplazamiento de páginas a la papelera de reciclaje.</span><span class="sxs-lookup"><span data-stu-id="cb83e-292">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="cb83e-293">A los usuarios que quieran eliminar una página se les mostrará un cuadro de diálogo en el que se le preguntará si quieren eliminar una página de forma permanente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-293">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>


- <span data-ttu-id="cb83e-294">Se ha corregido un problema por el que no se cargaba el menú de ortografía.</span><span class="sxs-lookup"><span data-stu-id="cb83e-294">We fixed an issue where the spelling menu was not loading.</span></span>


### <a name="outlook"></a><span data-ttu-id="cb83e-295">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-295">Outlook</span></span>

- <span data-ttu-id="cb83e-296">Se ha corregido un problema por el que las experiencias opcionales conectadas bloqueaban la carga de los complementos web.</span><span class="sxs-lookup"><span data-stu-id="cb83e-296">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <span data-ttu-id="cb83e-297">Vea más información aquí: https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/</span><span class="sxs-lookup"><span data-stu-id="cb83e-297">See more detail here:  https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/</span></span>


- <span data-ttu-id="cb83e-298">Se ha corregido un problema por el que los usuarios ahora pueden deshabilitar IRM (Information Rights Management) para Outlook sin tener que deshabilitarlo para el resto de las aplicaciones de Office.</span><span class="sxs-lookup"><span data-stu-id="cb83e-298">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="cb83e-299">Se ha corregido un problema que provocaba que los usuarios no pudieran conceder permisos de editor a los delegados.</span><span class="sxs-lookup"><span data-stu-id="cb83e-299">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="cb83e-300">Se ha corregido un problema que provocaba que la aplicación finalizara de forma abrupta cuando el cliente seleccionaba un resultado de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="cb83e-300">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="cb83e-301">Corrige un problema que evitaba que los usuarios que intentaran crear una solicitud de reunión desde una cuenta secundaria añadida a su perfil vieran el campo De: en blanco en lugar de su dirección de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="cb83e-301">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>


- <span data-ttu-id="cb83e-302">Corrige un problema que evitaba que los usuarios se conectaran a las carpetas públicas luego de agregar un buzón compartido.</span><span class="sxs-lookup"><span data-stu-id="cb83e-302">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


- <span data-ttu-id="cb83e-303">Se ha corregido un problema que provocaba un error al tratar de eliminar las reuniones del calendario de un administrador, cuando un delegado las rechazaba en determinadas circunstancias.</span><span class="sxs-lookup"><span data-stu-id="cb83e-303">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="cb83e-304">Se corrigió un problema que impedía a algunos usuarios de la característica Mejoras del calendario compartido ver un calendario compartido recién agregado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-304">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>


- <span data-ttu-id="cb83e-305">Corrige un problema que provocaba que los usuarios no pudieran cerrar los calendarios compartidos haciendo clic en la "X" de la esquina.</span><span class="sxs-lookup"><span data-stu-id="cb83e-305">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="cb83e-306">Corrige un problema que causaba que la configuración "Activar las mejoras del calendario compartido" en ocasiones no se pudiera aplicar a los calendarios compartidos existentes.</span><span class="sxs-lookup"><span data-stu-id="cb83e-306">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="cb83e-307">Se ha corregido un problema que provocaba que las búsquedas en calendarios de Grupo no dieran resultados.</span><span class="sxs-lookup"><span data-stu-id="cb83e-307">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="cb83e-308">Se ha corregido un problema que provocaba que los usuarios experimentaran cierres ocasionales al interactuar con datos adjuntos en la nube.</span><span class="sxs-lookup"><span data-stu-id="cb83e-308">Fixes an issue that caused users to experience occasional closures when interacting with Cloud attachments.</span></span>


- <span data-ttu-id="cb83e-309">Se ha corregido un problema que provocaba un error cuando los usuarios de CLP cambiaban la dirección del remitente en una respuesta desde un contexto protegido a uno no protegido.</span><span class="sxs-lookup"><span data-stu-id="cb83e-309">Addressed an issue that caused users of CLP to experience an issue when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="cb83e-310">Corrige un problema que provocaba que los usuarios vieran un error en la página de vínculos seguros en lugar del documento que intentaban abrir al abrir un archivo adjunto en la nube.</span><span class="sxs-lookup"><span data-stu-id="cb83e-310">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="cb83e-311">Se ha corregido un problema por el que Outlook no pudo habilitar consejos de directiva para la Protección de pérdida de datos para usuarios que pagaron por el servicio con planes M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="cb83e-311">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>


- <span data-ttu-id="cb83e-312">Se ha corregido un problema con el evento de auditoría CLP para la etiqueta de responder o reenviar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-312">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="cb83e-313">Se ha corregido un problema que provocaba que el ancho del panel de carpetas cambiara inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-313">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>


- <span data-ttu-id="cb83e-314">Se ha corregido un problema que provocaba que el campo "Para:" estuviera vacío al enviar un informe de estado en una tarea.</span><span class="sxs-lookup"><span data-stu-id="cb83e-314">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="cb83e-315">Se ha corregido un problema que provocaba que se interrumpiera el evento MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="cb83e-315">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="cb83e-316">Se ha corregido un problema que causaba que la fecha de creación de datos adjuntos copiados en el sistema de archivos a través de la opción de arrastrar y soltar apareciera como el 1 de enero de 4501.</span><span class="sxs-lookup"><span data-stu-id="cb83e-316">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>


- <span data-ttu-id="cb83e-317">Se ha corregido un problema que provocaba que los usuarios de algunos juegos de caracteres viesen nombres de archivo que se mostraban de forma incorrecta al agregar un vínculo inteligente a un archivo de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-317">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="cb83e-318">Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange", al actualizar sus reglas en Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-318">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>


- <span data-ttu-id="cb83e-319">Se corrigió un problema que provocaba que Outlook no pudiese recuperar sugerencias de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="cb83e-319">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="cb83e-320">Se ha corregido un problema que provocaba que los usuarios de las mejoras del Calendario compartido vieran errores en el calendario.</span><span class="sxs-lookup"><span data-stu-id="cb83e-320">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="cb83e-321">Se ha corregido un problema que causaba que los usuarios experimentaran cierres y bloqueos intermitentes en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="cb83e-321">Addressed an issue that caused users to experience intermittent hangs and closures in some scenarios.</span></span>


- <span data-ttu-id="cb83e-322">Se ha corregido un problema que provocaba que los usuarios experimentaran un error al eliminar 4 o más mensajes de correo electrónico de una cuenta POP con la opción "Descargar solo encabezados" seleccionada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-322">Addressed an issue which caused users to experience an issue when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="cb83e-323">Corregido un problema que causaba que los delegados sufrieran errores intermitentemente al abrir carpetas compartidas en otro buzón.</span><span class="sxs-lookup"><span data-stu-id="cb83e-323">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="cb83e-324">Corregido un problema que causaba que se enviaran algunos mensajes de correo electrónico generados automáticamente con el cuerpo en blanco cuando la línea del asunto estaba también en blanco.</span><span class="sxs-lookup"><span data-stu-id="cb83e-324">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="cb83e-325">Se ha corregido un problema que causaba que faltara la opción "Permitir reenvío" en las "Opciones de respuesta" de la reunión de calendario compartida cuando NO está marcada Descargar carpeta compartida.</span><span class="sxs-lookup"><span data-stu-id="cb83e-325">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="cb83e-326">Se ha corregido un problema que causaba que los delegados recibieran un error al editar una cita de calendario existente en el calendario de un administrador.</span><span class="sxs-lookup"><span data-stu-id="cb83e-326">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="cb83e-327">Se ha corregido un problema que provocaba que los usuarios experimentaran un error en aplicaciones MAPI de terceros.</span><span class="sxs-lookup"><span data-stu-id="cb83e-327">Addressed an issue that caused users to experience an issue in third party MAPI applications.</span></span>


- <span data-ttu-id="cb83e-328">Se ha corregido un problema que provocaba que Outlook se cerrara inesperadamente al abrir archivos .msg y .oft guardados localmente después de una actualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="cb83e-328">Addressed an issue that caused Outlook to close unexpectedly when opening .msg or .oft files that were saved locally after a Windows update.</span></span>


- <span data-ttu-id="cb83e-329">Se ha corregido un problema que provocaba que Outlook se cerrara inesperadamente en algunas compilaciones de Windows.</span><span class="sxs-lookup"><span data-stu-id="cb83e-329">Addressed an issue that caused Outlook to close unexpectedly on some builds of Windows.</span></span>


- <span data-ttu-id="cb83e-330">Se ha corregido un problema que provocaba que los usuarios de las versiones de Windows 10 Server vieran la advertencia "Estado del antivirus: no válido".</span><span class="sxs-lookup"><span data-stu-id="cb83e-330">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="cb83e-331">Esta versión de Windows admite la detección del antivirus, pero no se encontró ninguno” a pesar de tener un antivirus correctamente instalado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-331">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>


- <span data-ttu-id="cb83e-332">Se ha corregido un problema que provocaba que algunos usuarios experimentaran el cierre inesperado de la aplicación Outlook al enviar correo desde aplicaciones diferentes de Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-332">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="cb83e-333">Corrige un problema de rendimiento con la carga de archivos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-333">Addresses a performance issue with attachment upload.</span></span>


- <span data-ttu-id="cb83e-334">Se ha corregido un problema que provocaba que los usuarios de Outlook vieran continuamente un aviso para que ejecutaran la herramienta de reparación de la bandeja de entrada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-334">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="cb83e-335">Se ha corregido un problema que provocaba que los usuarios experimentaran ocasionalmente un error al usar el botón "X" de su ratón.</span><span class="sxs-lookup"><span data-stu-id="cb83e-335">Addressed an issue that caused users to occasionally experience an issue when using the "X" button on their mouse.</span></span>


- <span data-ttu-id="cb83e-336">Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.</span><span class="sxs-lookup"><span data-stu-id="cb83e-336">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="cb83e-337">Se ha corregido un problema que provocaba que los encabezados de mensajes en chino fueran ilegibles al responder o reenviar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-337">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>


- <span data-ttu-id="cb83e-338">Se ha corregido un problema que provocaba que la página del Asistente para programación no se mostrara.</span><span class="sxs-lookup"><span data-stu-id="cb83e-338">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="cb83e-339">Se ha corregido un problema que impedía a algunos usuarios visualizar correctamente la página del Asistente para programación.</span><span class="sxs-lookup"><span data-stu-id="cb83e-339">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>


- <span data-ttu-id="cb83e-340">Se ha corregido un problema que provocaba que los usuarios experimentaran un rendimiento degradado al mover varios elementos de correo entre carpetas en el modo en línea.</span><span class="sxs-lookup"><span data-stu-id="cb83e-340">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="cb83e-341">Se ha agregado una clave de registro que permite a los clientes deshabilitar la inclusión de hora de archivo para los datos adjuntos en las operaciones de IDataObject (es decir, arrastrar y soltar, portapapeles).</span><span class="sxs-lookup"><span data-stu-id="cb83e-341">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span> <span data-ttu-id="cb83e-342">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = horas de archivo están excluidas  1 = (determinado) horas de archivo están incluidas</span><span class="sxs-lookup"><span data-stu-id="cb83e-342">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="cb83e-343">Se ha corregido un problema que provocaba que las imágenes en línea desaparecieran al responder a un mensaje con una etiqueta de protección de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="cb83e-343">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="cb83e-344">Se ha corregido un problema que provocaba que el nombre de usuario se mostrara como un número de teléfono al enviar un correo de voz protegido de Azure, lo que provocaba que los usuarios de escritorio de Outlook no puedan abrir correos de voz de usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-344">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="cb83e-345">Se ha corregido un problema que provocaba que, al configurar OME, se agregaban datos adjuntos extraños en el elemento de correo que obligaban a Outlook a cifrar el mensaje aunque la opción DecryptAttachmentsForEncryptOnly estuviera configurada en el lado del servicio.</span><span class="sxs-lookup"><span data-stu-id="cb83e-345">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


- <span data-ttu-id="cb83e-346">Se ha corregido un problema que provocaba que se siguiesen habilitando en algunos escenarios las opciones Cifrar solo y No reenviar aunque estuviesen deshabilitadas por la directiva.</span><span class="sxs-lookup"><span data-stu-id="cb83e-346">We fixed an issue that caused the Encrypt Only and Do Not Forward options to continue to be enabled in some scenarios despite being disabled by policy.</span></span>


- <span data-ttu-id="cb83e-347">Se ha corregido un problema que provocaba que SmartLinks perdiera el formato cuando se guardaba en Borradores.</span><span class="sxs-lookup"><span data-stu-id="cb83e-347">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="cb83e-348">Se ha corregido un problema para proporcionar a los usuarios una forma de personalizar el texto de justificación al anular una directiva.</span><span class="sxs-lookup"><span data-stu-id="cb83e-348">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="cb83e-349">Se ha corregido un problema que provocaba que los caracteres chinos se cambiaran a signos de interrogación al guardar como archivo OFT.</span><span class="sxs-lookup"><span data-stu-id="cb83e-349">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="cb83e-350">Se ha corregido un problema que provocaba que los usuarios experimentaran ocasionalmente cierres inesperados al recuperar información personal.</span><span class="sxs-lookup"><span data-stu-id="cb83e-350">Addressed an issue that caused users to occasionally experience unexpected closures when retrieving persona information.</span></span>


- <span data-ttu-id="cb83e-351">Esto corrige un problema que provocaba que los usuarios experimentaran cierres ocasionales de la aplicación al editar los destinatarios.</span><span class="sxs-lookup"><span data-stu-id="cb83e-351">This fixes an issue that caused users to experience occasional application closures when editing recipients.</span></span>


- <span data-ttu-id="cb83e-352">Corrige un problema que provocaba que los usuarios vieran anomalías al usar la vista compacta.</span><span class="sxs-lookup"><span data-stu-id="cb83e-352">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>


- <span data-ttu-id="cb83e-353">Se ha corregido un problema que provocaba que los usuarios de Outlook tuvieran problemas con la navegación en vistas compactas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-353">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>


- <span data-ttu-id="cb83e-354">Se ha corregido un problema que provocaba que el menú contextual del botón derecho no apareciera en los controles de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="cb83e-354">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>


- <span data-ttu-id="cb83e-355">Corrige un problema que provocaba que los usuarios recibieran el siguiente error al responder a un correo o al redactar uno nuevo: "Algunos archivos de esta página web no están en la ubicación esperada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-355">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="cb83e-356">¿Desea descargarlos de todos modos?</span><span class="sxs-lookup"><span data-stu-id="cb83e-356">Do you want to download them anyway?</span></span> <span data-ttu-id="cb83e-357">Si está seguro de que la página web es una fuente de confianza, haga clic en Sí".</span><span class="sxs-lookup"><span data-stu-id="cb83e-357">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


- <span data-ttu-id="cb83e-358">Corrige un problema que provocaba que los usuarios experimentaran un error al salir de Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-358">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


- <span data-ttu-id="cb83e-359">Se ha corregido un problema que provocaba que la búsqueda de una característica en Sugerir una característica no devolviera resultados y no ofrecía al usuario ninguna opción para enviar una nueva idea de característica.</span><span class="sxs-lookup"><span data-stu-id="cb83e-359">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


- <span data-ttu-id="cb83e-360">Se ha abordado un problema que causaba problemas de formato en las alertas de notificación de incidentes.</span><span class="sxs-lookup"><span data-stu-id="cb83e-360">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>


- <span data-ttu-id="cb83e-361">Se ha corregido un problema que provocaba que los usuarios experimentaran bloqueos repentinos al enviar comentarios desde una Notificación de administrador.</span><span class="sxs-lookup"><span data-stu-id="cb83e-361">Addressed an issue that caused users to experience sudden closures when submitting feedback from an Admin Notification.</span></span>


- <span data-ttu-id="cb83e-362">Se ha corregido un problema para copiar y pegar imágenes SVG.</span><span class="sxs-lookup"><span data-stu-id="cb83e-362">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="cb83e-363">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb83e-363">PowerPoint</span></span>

- <span data-ttu-id="cb83e-364">Este cambio corrige un problema relacionado con la característica Exportar a GIF animado, en la que no se exporta al hacer clic en el botón Exportar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-364">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="cb83e-365">Se ha corregido un problema por el que el complemento de contenido de formularios no se representaba después de la inserción hasta que el usuario hiciera clic en otra diapositiva para hacer que apareciera.</span><span class="sxs-lookup"><span data-stu-id="cb83e-365">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


- <span data-ttu-id="cb83e-366">Corrección de seguridad para solucionar un problema que deshabilitaba las protecciones IRM al abrir un archivo de PowerPoint en la Vista protegida.</span><span class="sxs-lookup"><span data-stu-id="cb83e-366">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="cb83e-367">Se ha corregido un problema de VBA por el que Slide.Shapes.AddMediaObject2 se cerraba inesperadamente con formatos de vídeo heredados (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="cb83e-367">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="cb83e-368">Se ha corregido un problema por el que los gráficos vinculados de Excel cambiaban incorrectamente a hoja de Excel cuando el usuario cambiaba la ruta de origen de la carpeta de OneDrive local.</span><span class="sxs-lookup"><span data-stu-id="cb83e-368">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="cb83e-369">Se ha corregido un problema por el que los usuarios tenían comentarios tanto modernos como heredados en un archivo, lo que activaba una actualización de los comentarios.</span><span class="sxs-lookup"><span data-stu-id="cb83e-369">Fixed an issue when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


- <span data-ttu-id="cb83e-370">Se ha corregido un problema con el panel de sugerencias que podía provocar que la aplicación se cerrara inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-370">We have fixed an issue with suggestion pane that may cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="cb83e-371">Se ha corregido un problema en el cuadro de diálogo de configuración de acciones que provocaba que aplicación de PowerPoint se cerrara inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-371">We have fixed an issue in Action Settings dialog which was causing the PowerPoint app to close unexpectedly.</span></span>


- <span data-ttu-id="cb83e-372">Se ha corregido un problema con la aplicación de PowerPoint que podía provocar que se cerrara inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-372">We have fixed an issue with PowerPoint app that may cause it to close unexpectedly.</span></span>


- <span data-ttu-id="cb83e-373">Se ha corregido un problema que provocaba que la característica "Bienvenido de nuevo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-373">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="cb83e-374">Retomar el trabajo donde lo dejó en la oficina" no funcionara en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-374">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


- <span data-ttu-id="cb83e-375">Se ha corregido un problema que evitaba que algunos archivos de PowerPoint corruptos se abrieran correctamente, incluso después de la operación de reparación de un documento.</span><span class="sxs-lookup"><span data-stu-id="cb83e-375">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="cb83e-376">Se ha corregido un problema que evitaba que algunos archivos de PowerPoint corruptos se abrieran correctamente, incluso después de la operación de reparación de un documento.</span><span class="sxs-lookup"><span data-stu-id="cb83e-376">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="cb83e-377">Se ha corregido un problema por el que la presentación con diapositivas no funcionaba en la vista protegida.</span><span class="sxs-lookup"><span data-stu-id="cb83e-377">We fixed an issue where Slideshow in protected view was not working.</span></span>


### <a name="project"></a><span data-ttu-id="cb83e-378">Project</span><span class="sxs-lookup"><span data-stu-id="cb83e-378">Project</span></span>

- <span data-ttu-id="cb83e-379">Se ha corregido un problema por el que la tarea seleccionada en el cuadro de diálogo de asignación de recursos no era la misma que la tarea seleccionada en la vista del panel de tareas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-379">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="cb83e-380">Se ha corregido un problema debido al cual, si un recurso tenía más de una tabla de tasa de costo definida, el costo restante no siempre se calculaba correctamente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-380">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


- <span data-ttu-id="cb83e-381">Se ha corregido un problema en el que la fecha de finalización de Project no se actualiza para los proyectos conectados a la lista de tareas de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-381">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


- <span data-ttu-id="cb83e-382">Se ha corregido un problema que hace que si está usando Project conectado a Project Web App y el separador decimal es una coma, el método TaskDependencies Add producirá un error al intentar agregar retardo a una dependencia.</span><span class="sxs-lookup"><span data-stu-id="cb83e-382">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


- <span data-ttu-id="cb83e-383">Corregido un problema por el que el porcentaje completado de la tarea se cambiaba incorrectamente a un valor inferior al 100 % después de que se marcara como completada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-383">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>


- <span data-ttu-id="cb83e-384">Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="cb83e-384">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>


- <span data-ttu-id="cb83e-385">Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-385">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


- <span data-ttu-id="cb83e-386">Corregido un problema que hace que el evento ProjectBeforeTaskChange no detecte cuándo se ha desactivado o activado una tarea mediante el botón Desactivar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-386">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>


- <span data-ttu-id="cb83e-387">Se ha corregido un problema por el que cuando se editaban los datos del Predecesor/Sucesor dentro de una vista de formulario, se activaba un evento ProjectBeforeTaskChange adicional.</span><span class="sxs-lookup"><span data-stu-id="cb83e-387">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>


- <span data-ttu-id="cb83e-388">Se ha corregido un problema por el que Project podía cerrarse inesperadamente al guardar proyectos creados con versiones anteriores de Project.</span><span class="sxs-lookup"><span data-stu-id="cb83e-388">Fixed an issue where Project may close unexpectedly when saving projects created with older versions of Project.</span></span>


- <span data-ttu-id="cb83e-389">Se ha corregido un problema por el que el usuario no podía especificar el trabajo previsto con fases temporales si estaba activada la configuración para proteger el trabajo real.</span><span class="sxs-lookup"><span data-stu-id="cb83e-389">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>


- <span data-ttu-id="cb83e-390">Se ha corregido un problema que impedía guardar desde Project un PDF o XPS en una biblioteca de documentos de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-390">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="cb83e-391">Se ha corregido un problema por el que si pegaba una tarea que tenía varias dependencias, no todas las dependencias se copiaban correctamente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-391">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="cb83e-392">Se ha corregido un problema por el que los proyectos no se podían abrir en el cliente de escritorio de Project desde Project Web App si la dirección URL terminaba en .com.</span><span class="sxs-lookup"><span data-stu-id="cb83e-392">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="cb83e-393">Se ha corregido un problema por el que el evento ProjectBeforeTaskChange no se activaba al darse un cambio en la tarea de resumen del proyecto: ya sea en el campo de inicio o tarea del proyecto.</span><span class="sxs-lookup"><span data-stu-id="cb83e-393">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>


- <span data-ttu-id="cb83e-394">Se ha corregido un problema por el que una tarea marcada como completada al 100 % se mostraba por error no completada al 100 %.</span><span class="sxs-lookup"><span data-stu-id="cb83e-394">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>


- <span data-ttu-id="cb83e-395">Se ha corregido un problema por el que el Project podría finalizar inesperadamente al abrir archivos en los que se especificaban los contornos de los recursos de una determinada manera.</span><span class="sxs-lookup"><span data-stu-id="cb83e-395">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="cb83e-396">Skype</span><span class="sxs-lookup"><span data-stu-id="cb83e-396">Skype</span></span>

- <span data-ttu-id="cb83e-397">Se cambió el tono de piel del emoticono de baile a un color neutro</span><span class="sxs-lookup"><span data-stu-id="cb83e-397">Changed dancing emoticon skin tone to neutral color.</span></span>


- <span data-ttu-id="cb83e-398">Cuando se asignaba a un usuario una directiva que lo llevaba a Teams solo, aún se podía usar el complemento para Outlook de Skype Empresarial para programar reuniones.</span><span class="sxs-lookup"><span data-stu-id="cb83e-398">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="cb83e-399">Tras esta actualización, ya no se podrán programar reuniones de Skype Empresarial después de que el cliente lea la directiva en la que se indica que el usuario participa en Teams solo y entra en la reunión como Unirse solo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-399">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="cb83e-400">Además, el complemento de Outlook para Skype Empresarial no se activará durante el inicio si ve que el cliente de Skype Empresarial se encuentra en modo de Unirse solo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-400">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>


- <span data-ttu-id="cb83e-401">Se ha corregido un problema por el que el certificado TLS-DSK de un usuario no se renovaba en el momento esperado, solo se renovaba cuando le quedaban menos de doce horas de validez.</span><span class="sxs-lookup"><span data-stu-id="cb83e-401">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="cb83e-402">Se ha corregido un problema por el que la interfaz de usuario de Skype Empresarial se mostraba en blanco tras iniciar sesión si todavía no se tenía la licencia de Office.</span><span class="sxs-lookup"><span data-stu-id="cb83e-402">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="visio"></a><span data-ttu-id="cb83e-403">Visio</span><span class="sxs-lookup"><span data-stu-id="cb83e-403">Visio</span></span>

- <span data-ttu-id="cb83e-404">Se ha corregido un problema que provocaba que la Vista previa dinámica se cerrara inesperadamente al alinear texto.</span><span class="sxs-lookup"><span data-stu-id="cb83e-404">We fixed an issue that caused the Live preview to close unexpectedly on text alignment.</span></span>


- <span data-ttu-id="cb83e-405">Se ha corregido un problema que provocaba que los usuarios pudieran crear líneas rectas con conectores en Visio para Office 365, tanto para las galerías personalizadas de símbolos de Visio como para las plantillas predefinidas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-405">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="cb83e-406">Word</span><span class="sxs-lookup"><span data-stu-id="cb83e-406">Word</span></span>

- <span data-ttu-id="cb83e-407">Se ha resuelto un problema al abrir documentos de Word desde la entrega de documentos personalizados (aspx) cuando la dirección URL contenía un componente de consulta.</span><span class="sxs-lookup"><span data-stu-id="cb83e-407">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>


- <span data-ttu-id="cb83e-408">Este cambio corrige un problema que provocaba que las aplicaciones de Office se queden atascadas en un estado de error de guardado silencioso después de una sesión de coautoría anterior.</span><span class="sxs-lookup"><span data-stu-id="cb83e-408">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>


- <span data-ttu-id="cb83e-409">Corrige un problema que provocaba que los usuarios experimentaran un error al responder a un correo electrónico o redactar uno nuevo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-409">Addresses an issue that caused users to experience an issue when replying to or composing new email.</span></span>


- <span data-ttu-id="cb83e-410">Se ha corregido un problema que provocaba que los usuarios experimentaran ocasionalmente un error al usar el botón "X" de su ratón.</span><span class="sxs-lookup"><span data-stu-id="cb83e-410">Addressed an issue that caused users to occasionally experience an issue when using the "X" button on their mouse.</span></span>


- <span data-ttu-id="cb83e-411">Corrige un problema que provocaba que los usuarios experimentaran un error al abrir algunos correos electrónicos muy grandes.</span><span class="sxs-lookup"><span data-stu-id="cb83e-411">Fixes an issue that caused users to experience an issue when opening certain very large emails.</span></span>


- <span data-ttu-id="cb83e-412">Se ha corregido un problema por el que los títulos numerados pegados mostraban una sangría adicional.</span><span class="sxs-lookup"><span data-stu-id="cb83e-412">We fixed an issue where pasted numbered headings showed an additional indent.</span></span>


- <span data-ttu-id="cb83e-413">Se ha corregido un problema para copiar y pegar imágenes SVG.</span><span class="sxs-lookup"><span data-stu-id="cb83e-413">We fixed an issue for copy and paste SVG image.</span></span>


- <span data-ttu-id="cb83e-414">Se ha corregido un problema por el cual el usuario podría perder contenido al cambiar el tamaño de una forma.</span><span class="sxs-lookup"><span data-stu-id="cb83e-414">We fixed an issue where the user might lose content when resize a shape.</span></span>


- <span data-ttu-id="cb83e-415">Se ha corregido un problema por el que los usuarios podían experimentar un error al abrir un documento.</span><span class="sxs-lookup"><span data-stu-id="cb83e-415">We fixed an issue which user might experience issues when opening a document.</span></span>


- <span data-ttu-id="cb83e-416">Se ha corregido un problema por el que los vínculos largos no se ajustaban al guardar un documento en formato HTML.</span><span class="sxs-lookup"><span data-stu-id="cb83e-416">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="cb83e-417">Se ha corregido un problema por el que los estilos base no se actualizaban con el estilo Normal.</span><span class="sxs-lookup"><span data-stu-id="cb83e-417">We fixed an issue which the base styles are not updated with Normal style.</span></span>


- <span data-ttu-id="cb83e-418">Corrige un error con las extensiones de comentarios que provocaba que la respuesta a un comentario tuviera la misma extensión que el comentario principal.</span><span class="sxs-lookup"><span data-stu-id="cb83e-418">FIxes a bug with comment extensions where the comment reply would have the same extension as the parent comment.</span></span>


- <span data-ttu-id="cb83e-419">Se ha corregido un problema que provocaba que, si se respondía a un comentario primario que tenía extensiones desconocidas en una lista de extensiones, la respuesta obtuviera esas mismas extensiones.</span><span class="sxs-lookup"><span data-stu-id="cb83e-419">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="cb83e-420">Se ha solucionado un problema que podía causar que la aplicación se cerrara inesperadamente en el arranque.</span><span class="sxs-lookup"><span data-stu-id="cb83e-420">Resolved an issue that may have caused the application to close unexpectedly when booting.</span></span>


- <span data-ttu-id="cb83e-421">Se ha corregido un problema que se producía en Outlook al establecer un mensaje en No reenviar</span><span class="sxs-lookup"><span data-stu-id="cb83e-421">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="cb83e-422">Se ha corregido un problema con el cuadro de diálogo Galería de estilos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-422">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="cb83e-423">Se ha corregido un problema por el que se ejecutaba la macro AutoOpen antes de AutoExec.</span><span class="sxs-lookup"><span data-stu-id="cb83e-423">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>


### <a name="office-suite"></a><span data-ttu-id="cb83e-424">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-424">Office Suite</span></span>

- <span data-ttu-id="cb83e-425">Se ha corregido un problema con el antiguo panel de uso compartido basado en un servicio no web por el que la aplicación se podía cerrar inesperadamente al cerrar un documento mientras el panel de uso compartido estaba abierto.</span><span class="sxs-lookup"><span data-stu-id="cb83e-425">Fixed an issue for the old, non-web service based Share pane, where upon closing the document while the Share pane is open could cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="cb83e-426">Se ha corregido un problema de temporización que podía provocar que la aplicación se cerrara de forma inesperada al cerrar archivos de Office.</span><span class="sxs-lookup"><span data-stu-id="cb83e-426">Fixed a timing issue that could cause the application to close unexpectedly when closing office files.</span></span>


- <span data-ttu-id="cb83e-427">Soluciona un problema que impedía que los usuarios importaran listas de SPO cuando se deshabilitaba ADAL.</span><span class="sxs-lookup"><span data-stu-id="cb83e-427">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>


- <span data-ttu-id="cb83e-428">Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan toners</span><span class="sxs-lookup"><span data-stu-id="cb83e-428">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="cb83e-429">Cambiar mensaje para mostrar "tóner/Ink Low" & "no tóner/tinta".</span><span class="sxs-lookup"><span data-stu-id="cb83e-429">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="cb83e-430">Hemos resuelto el problema de la tasa de error de ValidateInstall estableciendo la validación de instalación del Complemento de Bing como verdadera de forma predeterminada y considerando el éxito de devolución de MSI como una instalación con éxito.</span><span class="sxs-lookup"><span data-stu-id="cb83e-430">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>


- <span data-ttu-id="cb83e-431">Hemos modificado la versión AppV51 para solucionar una regresión de la AppV51 anterior.</span><span class="sxs-lookup"><span data-stu-id="cb83e-431">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>


- <span data-ttu-id="cb83e-432">Se ha corregido un problema de hacer clic y ejecutar que generaba errores de actualización al intentar crear un vínculo físico para vínculos simbólicos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-432">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>


- <span data-ttu-id="cb83e-433">Se ha atendido un problema para los clientes comerciales que usan el System Center Configuration Manager u otras herramientas de administración para Office Update mediante la prevención de pérdida de datos del punto de conexión de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="cb83e-433">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>


- <span data-ttu-id="cb83e-434">Se ha corregido un problema que provocaba que se mostrara un mensaje de tiempo de ejecución aunque se completara la transición al producto completo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-434">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="cb83e-435">La corrección para este problema era asegurarse de que el servicio computase correctamente los productos agregados.</span><span class="sxs-lookup"><span data-stu-id="cb83e-435">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="cb83e-436">Se han filtrado los nuevos productos agregados (lo que garantiza que también se encuentren en la nueva configuración) y se han agregado al final de los ID de versión de producto existentes.</span><span class="sxs-lookup"><span data-stu-id="cb83e-436">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>


- <span data-ttu-id="cb83e-437">Se ha corregido un problema debido al cual los usuarios no podían visualizar el contenido o los elementos de la interfaz de usuario en determinadas condiciones, especialmente en la vista Moderador (o al salir de la misma) o al usar varios monitores.</span><span class="sxs-lookup"><span data-stu-id="cb83e-437">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>


- <span data-ttu-id="cb83e-438">Este cambio soluciona un problema relacionado con la apertura de archivos que contienen diagramas heredados.</span><span class="sxs-lookup"><span data-stu-id="cb83e-438">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="cb83e-439">Este cambio soluciona un problema con proxy de reserva de SVG que provocaba infracciones de acceso.</span><span class="sxs-lookup"><span data-stu-id="cb83e-439">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>


- <span data-ttu-id="cb83e-440">Corrige el uso elevado de la CPU en modo inactivo con un GIF o un modelo 3D animado</span><span class="sxs-lookup"><span data-stu-id="cb83e-440">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="cb83e-441">Este cambio resuelve posibles errores al cargar y reproducir contenido animado como GIF o modelos 3D.</span><span class="sxs-lookup"><span data-stu-id="cb83e-441">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>


- <span data-ttu-id="cb83e-442">Este cambio corrige un problema al iniciar las aplicaciones de Office debido a un error al cargar d2d1.dll.</span><span class="sxs-lookup"><span data-stu-id="cb83e-442">This change addresses a issue when launching Office apps due to failing to load d2d1.dll.</span></span>


- <span data-ttu-id="cb83e-443">El host de Office se cerraba inesperadamente en Windows al activar un complemento cuando la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth estaba establecida en cero.</span><span class="sxs-lookup"><span data-stu-id="cb83e-443">The office host was  close unexpectedly in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="cb83e-444">Este cambio solucionaría el problema.</span><span class="sxs-lookup"><span data-stu-id="cb83e-444">This change would fix this issue.</span></span>


- <span data-ttu-id="cb83e-445">Se corrige un problema por el que no funcionaba la API de mensajería para los complementos de Office.</span><span class="sxs-lookup"><span data-stu-id="cb83e-445">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>

- <span data-ttu-id="cb83e-446">Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.</span><span class="sxs-lookup"><span data-stu-id="cb83e-446">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


- <span data-ttu-id="cb83e-447">Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.</span><span class="sxs-lookup"><span data-stu-id="cb83e-447">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="cb83e-448">Esta corrección resuelve un error que impide restringir el acceso y proteger los archivos con una contraseña de forma simultánea.</span><span class="sxs-lookup"><span data-stu-id="cb83e-448">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="cb83e-449">Se ha corregido un problema que podría provocar un cierre inesperado al arrastrar contenido desde la aplicación.</span><span class="sxs-lookup"><span data-stu-id="cb83e-449">Resolved an issue that may have caused an unexpected closure when dragging some content from the app.</span></span>



[//]: # (NO QUITAR LOS DETALLES DE ERROR AL FINAL DEL CONTENIDO)

## <a name="version-2002-january-12"></a><span data-ttu-id="cb83e-451">Versión 2002: 12 de enero</span><span class="sxs-lookup"><span data-stu-id="cb83e-451">Version 2002: January 12</span></span>
<span data-ttu-id="cb83e-452">*Versión 2002 (compilación 12527.21504)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-452">*Version 2002 (Build 12527.21504)*</span></span>

<span data-ttu-id="cb83e-453">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-453">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-455">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-455">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb83e-456">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-456">Excel</span></span>

- <span data-ttu-id="cb83e-457">Se ha corregido un problema por el que la aplicación podía cerrarse inesperadamente al usar datos en tiempo real junto con la funcionalidad de recálculo multiproceso.</span><span class="sxs-lookup"><span data-stu-id="cb83e-457">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality could cause the application to close unexpectedly.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="cb83e-458">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb83e-458">PowerPoint</span></span>

- <span data-ttu-id="cb83e-459">Se ha corregido un problema que evitaba que algunos archivos de PowerPoint corruptos se abrieran correctamente, incluso después de la operación de reparación de un documento.</span><span class="sxs-lookup"><span data-stu-id="cb83e-459">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="word"></a><span data-ttu-id="cb83e-460">Word</span><span class="sxs-lookup"><span data-stu-id="cb83e-460">Word</span></span>

- <span data-ttu-id="cb83e-461">Corrige un error con las extensiones de comentarios que provocaba que la respuesta a un comentario tuviera la misma extensión que el comentario principal.</span><span class="sxs-lookup"><span data-stu-id="cb83e-461">Fixes a bug with comment extensions where the comment reply would have the same extension as the parent comment.</span></span>


[//]: # (NO QUITAR LOS DETALLES DE ERROR AL FINAL DEL CONTENIDO)

## <a name="version-1908-january-12"></a><span data-ttu-id="cb83e-463">Versión 1908: 12 de enero</span><span class="sxs-lookup"><span data-stu-id="cb83e-463">Version 1908: January 12</span></span>
<span data-ttu-id="cb83e-464">*Versión 1908 (compilación 11929.20994)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-464">*Version 1908 (Build 11929.20994)*</span></span>

<span data-ttu-id="cb83e-465">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-465">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-467">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-467">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="cb83e-468">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-468">Office Suite</span></span>

- <span data-ttu-id="cb83e-469">Este cambio soluciona un problema relacionado con la apertura de archivos que contienen diagramas heredados.</span><span class="sxs-lookup"><span data-stu-id="cb83e-469">This change addresses an issue related to opening files containing legacy diagrams.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-december-08"></a><span data-ttu-id="cb83e-471">Versión 2002: 08 de diciembre</span><span class="sxs-lookup"><span data-stu-id="cb83e-471">Version 2002: December 08</span></span>
<span data-ttu-id="cb83e-472">*Versión 2002 (compilación 12527.21416)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-472">*Version 2002 (Build 12527.21416)*</span></span>

<span data-ttu-id="cb83e-473">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-473">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-475">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-475">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb83e-476">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-476">Excel</span></span>

- <span data-ttu-id="cb83e-477">Interletraje de texto en PowerPoint mejorado cuando el contenido se copia desde Excel y se pega en PowerPoint con la opción Insertar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-477">Improved text kerning in PowerPoint when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="cb83e-478">Se ha corregido un problema que provocaba que Excel dejara de funcionar durante el recálculo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-478">We fixed an issue where Excel would stop working during recalc.</span></span>


- <span data-ttu-id="cb83e-479">Se ha corregido un problema que provocaba que el usuario no pudiera abrir el archivo atomsvc (UTF8+BOM) directamente desde SharePoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-479">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="cb83e-480">Se ha corregido un problema que impedía cambiar entre la vista previa de la tabla y el editor de consultas en PowerPivot.</span><span class="sxs-lookup"><span data-stu-id="cb83e-480">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="cb83e-481">Rendimiento mejorado para los archivos que usan muchas de las funciones recientemente publicadas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-481">Improved performance for files that are using many of the more recently released functions.</span></span>


### <a name="outlook"></a><span data-ttu-id="cb83e-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-482">Outlook</span></span>

- <span data-ttu-id="cb83e-483">Se ha corregido un problema que provocaba que, al configurar OME, se agregaran datos adjuntos extraños en el elemento de correo, que obligaban a Outlook a cifrar el mensaje aunque la opción DecryptAttachmentsForEncryptOnly estuviera configurada en el lado del servicio.</span><span class="sxs-lookup"><span data-stu-id="cb83e-483">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though DecryptAttachmentsForEncryptOnly option is setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="cb83e-484">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb83e-484">PowerPoint</span></span>

- <span data-ttu-id="cb83e-485">Se ha corregido un problema que provocaba que el gráfico de Excel vinculado cambiara incorrectamente a la hoja de Excel cuando el usuario cambiaba la ruta de origen a la carpeta de OneDrive local.</span><span class="sxs-lookup"><span data-stu-id="cb83e-485">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


### <a name="project"></a><span data-ttu-id="cb83e-486">Project</span><span class="sxs-lookup"><span data-stu-id="cb83e-486">Project</span></span>

- <span data-ttu-id="cb83e-487">Se ha corregido un problema que provocaba que los proyectos no se pudieran abrir en el cliente de escritorio de Project en Project Web App si la dirección URL terminaba en .com.</span><span class="sxs-lookup"><span data-stu-id="cb83e-487">We fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App is the URL ended in .com.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-december-08"></a><span data-ttu-id="cb83e-489">Versión 1908: 08 de diciembre</span><span class="sxs-lookup"><span data-stu-id="cb83e-489">Version 1908: December 08</span></span>
<span data-ttu-id="cb83e-490">*Versión 1908 (compilación 11929.20984)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-490">*Version 1908 (Build 11929.20984)*</span></span>

<span data-ttu-id="cb83e-491">Las actualizaciones de seguridad se muestran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-491">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-november-10"></a><span data-ttu-id="cb83e-492">Versión 2002: 10 de noviembre</span><span class="sxs-lookup"><span data-stu-id="cb83e-492">Version 2002: November 10</span></span>
<span data-ttu-id="cb83e-493">*Versión 2002 (compilación 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-493">*Version 2002 (Build 12527.21330)*</span></span>

<span data-ttu-id="cb83e-494">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-494">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-496">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-496">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb83e-497">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-497">Excel</span></span>

- <span data-ttu-id="cb83e-498">Se ha corregido un problema que aparecía cuando se configuraba el idioma de Office en español. Este problema provocaba que las listas de validación de datos puedan no mostrar todos los elementos de la lista.</span><span class="sxs-lookup"><span data-stu-id="cb83e-498">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="cb83e-499">Se ha corregido un problema que podía provocar un bloqueo al actualizar las tablas dinámicas de OLAP.</span><span class="sxs-lookup"><span data-stu-id="cb83e-499">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="cb83e-500">Se ha corregido un problema por el que algunas funciones podían tener un resultado incorrecto después de cargar un libro.</span><span class="sxs-lookup"><span data-stu-id="cb83e-500">Fixed a bug where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="cb83e-501">Se ha corregido un problema relacionado con las referencias de complemento de XLAM y los rangos con nombre que cerraba la aplicación de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-501">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="cb83e-502">Se ha corregido un problema que producía que la ejecución de la macro de filtro avanzada mostrara errores incorrectamente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-502">Fixed an issue where running the advanced filter macro would incorrectly report errors.</span></span>


### <a name="outlook"></a><span data-ttu-id="cb83e-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-503">Outlook</span></span>

- <span data-ttu-id="cb83e-504">Se ha corregido un problema por el que se deshabilitaban de forma inesperada complementos internos cuando se deshabilitaban las experiencias conectadas opcionales.</span><span class="sxs-lookup"><span data-stu-id="cb83e-504">We fixed an issue that caused internal add-ins to be unexpectedly disabled when optional connected experiences were disabled.</span></span>


- <span data-ttu-id="cb83e-505">Se ha corregido un problema que impedía a los usuarios enviar como (o en nombre de) una lista de distribución oculta para la lista global de direcciones.</span><span class="sxs-lookup"><span data-stu-id="cb83e-505">We fixed an issue that caused users to be unable to send as or on behalf of a Distribution List that was hidden from the Global Address List.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-november-10"></a><span data-ttu-id="cb83e-507">Versión 1908: 12 de noviembre</span><span class="sxs-lookup"><span data-stu-id="cb83e-507">Version 1908: November 10</span></span>
<span data-ttu-id="cb83e-508">*Versión 1908 (Build 11929,20300)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-508">*Version 1908 (Build 11929.20974)*</span></span>

<span data-ttu-id="cb83e-509">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-509">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-october-13"></a><span data-ttu-id="cb83e-510">Versión 2002: 13 de octubre</span><span class="sxs-lookup"><span data-stu-id="cb83e-510">Version 2002: October 13</span></span>
<span data-ttu-id="cb83e-511">*Versión 2002 (Compilación 12527.21104)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-511">*Version 2002 (Build 12527.21236)*</span></span>

<span data-ttu-id="cb83e-512">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-512">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-514">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-514">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="cb83e-515">Acceso</span><span class="sxs-lookup"><span data-stu-id="cb83e-515">Access</span></span>

- <span data-ttu-id="cb83e-516">Ya no debería recibir un error "La consulta es demasiado compleja" o de recurso del sistema excedido en su versión de 64 bits de Access, siempre y cuando cumpla con las directrices y requisitos de la base de datos de Access.</span><span class="sxs-lookup"><span data-stu-id="cb83e-516">You should no longer receive a "Query is too complex" or a system resource exceeded error on your 64-bit version of Access, as long as you are meeting Access database guidelines and requirements.</span></span>


- <span data-ttu-id="cb83e-517">Una vez que decida usar nuestra característica de filtro después de nuestro diseñador de consultas, la base de datos ya no debería bloquearse.</span><span class="sxs-lookup"><span data-stu-id="cb83e-517">Once you decide to use our filter feature after our query designer, your database should no longer crash.</span></span> <span data-ttu-id="cb83e-518">Compruebe lo que corresponda.</span><span class="sxs-lookup"><span data-stu-id="cb83e-518">Please check accordingly.</span></span>


### <a name="excel"></a><span data-ttu-id="cb83e-519">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-519">Excel</span></span>

- <span data-ttu-id="cb83e-520">Se corrigió un problema por el cual los usuarios no podían modificar un filtro de tabla dinámica porque estaba configurado en un valor que ya no estaba presente en una base de datos de Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="cb83e-520">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="cb83e-521">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb83e-521">PowerPoint</span></span>

- <span data-ttu-id="cb83e-522">Las nuevas presentaciones creadas a partir de una plantilla podían heredar una configuración que impedía una buena experiencia de coautoría.</span><span class="sxs-lookup"><span data-stu-id="cb83e-522">New presentations created from a template could inherit a setting that prevented  a good co-authoring experience.</span></span> <span data-ttu-id="cb83e-523">Esta corrección garantiza que la configuración se haya borrado en este caso.</span><span class="sxs-lookup"><span data-stu-id="cb83e-523">This fix ensures that the setting is cleared in this case.</span></span>


### <a name="word"></a><span data-ttu-id="cb83e-524">Word</span><span class="sxs-lookup"><span data-stu-id="cb83e-524">Word</span></span>

- <span data-ttu-id="cb83e-525">Se ha corregido un problema por el que al abrir documentos con saltos de página y columnas, el usuario podía encontrar un mensaje de error, "Ha excedido el número máximo de páginas admitidas por Microsoft Word, o el documento puede estar dañado"</span><span class="sxs-lookup"><span data-stu-id="cb83e-525">We fixed an issue which when opening documents with page breaks and columns, user might encountered an error message, " You have exceeded the maximum number of pages allowed by Microsoft Word supported, or the document may be damaged"</span></span>


### <a name="office-suite"></a><span data-ttu-id="cb83e-526">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-526">Office Suite</span></span>

- <span data-ttu-id="cb83e-527">Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan toners</span><span class="sxs-lookup"><span data-stu-id="cb83e-527">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="cb83e-528">Cambiar mensaje para mostrar "tóner/Ink Low" & "no tóner/tinta".</span><span class="sxs-lookup"><span data-stu-id="cb83e-528">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-october-13"></a><span data-ttu-id="cb83e-530">Versión 1908: 8 de octubre</span><span class="sxs-lookup"><span data-stu-id="cb83e-530">Version 1908: October 13</span></span>
<span data-ttu-id="cb83e-531">*Versión 1908 (compilación 11929.20516)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-531">*Version 1908 (Build 11929.20966)*</span></span>

<span data-ttu-id="cb83e-532">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-532">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-534">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-534">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="cb83e-535">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-535">Office Suite</span></span>

- <span data-ttu-id="cb83e-536">Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan toners</span><span class="sxs-lookup"><span data-stu-id="cb83e-536">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="cb83e-537">Cambiar mensaje para mostrar "tóner/Ink Low" & "no tóner/tinta".</span><span class="sxs-lookup"><span data-stu-id="cb83e-537">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-september-08"></a><span data-ttu-id="cb83e-539">Versión 2002: 08 de septiembre</span><span class="sxs-lookup"><span data-stu-id="cb83e-539">Version 2002: September 08</span></span>
<span data-ttu-id="cb83e-540">*Versión 2002 (Compilación 12527.21104)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-540">*Version 2002 (Build 12527.21104)*</span></span>

<span data-ttu-id="cb83e-541">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-541">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-543">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-543">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb83e-544">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-544">Excel</span></span>

- <span data-ttu-id="cb83e-545">Esto soluciona un problema en el que las conexiones creadas por el proveedor de datos SQL en versiones anteriores de Office establecerían las propiedades de la tabla interna de manera diferente a Office 365.</span><span class="sxs-lookup"><span data-stu-id="cb83e-545">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="cb83e-546">Esto provocó que el menú desplegable Vista previa de tabla / Editor de consultas se deshabilitara para los archivos con conexiones creadas en versiones anteriores de Office cuando se abrieron con Office 365.</span><span class="sxs-lookup"><span data-stu-id="cb83e-546">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>


- <span data-ttu-id="cb83e-547">Se corrigió un problema por el cual las entradas manuscritas podrían hacer que Excel dejara de responder.</span><span class="sxs-lookup"><span data-stu-id="cb83e-547">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="cb83e-548">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-548">Outlook</span></span>

- <span data-ttu-id="cb83e-549">Corrige un problema que evitaba que los usuarios se conectaran a las carpetas públicas luego de agregar un buzón compartido.</span><span class="sxs-lookup"><span data-stu-id="cb83e-549">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


### <a name="office-suite"></a><span data-ttu-id="cb83e-550">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-550">Office Suite</span></span>

- <span data-ttu-id="cb83e-551">Este cambio resuelve un problema con el cuadro de diálogo de Comprimir imagen, que no retiene determinadas configuraciones de usuario.</span><span class="sxs-lookup"><span data-stu-id="cb83e-551">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-september-08"></a><span data-ttu-id="cb83e-553">Versión 1908: 08 de septiembre</span><span class="sxs-lookup"><span data-stu-id="cb83e-553">Version 1908: September 08</span></span>
<span data-ttu-id="cb83e-554">*Versión 1908 (compilación 11929.20946)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-554">*Version 1908 (Build 11929.20946)*</span></span>

<span data-ttu-id="cb83e-555">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-555">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-august-11"></a><span data-ttu-id="cb83e-556">Versión 2002: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="cb83e-556">Version 2002: August 11</span></span>
<span data-ttu-id="cb83e-557">*Versión 2002 (compilación 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-557">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="cb83e-558">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-558">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-560">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-560">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb83e-561">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-561">Excel</span></span>

- <span data-ttu-id="cb83e-562">Se corrigió un problema por el que no se podía cambiar a la edición de archivos que se han abierto como "recomendado solo lectura".</span><span class="sxs-lookup"><span data-stu-id="cb83e-562">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="cb83e-563">OneNote</span><span class="sxs-lookup"><span data-stu-id="cb83e-563">OneNote</span></span>

- <span data-ttu-id="cb83e-564">Se quitaron las llamadas de identidad redundantes para reducir el uso de recursos</span><span class="sxs-lookup"><span data-stu-id="cb83e-564">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="cb83e-565">Se mejoró la detección del estado de la coautoría para reducir el uso de recursos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-565">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="cb83e-566">Se mejoró la función de detección de errores y la calidad de la experiencia de sincronización.</span><span class="sxs-lookup"><span data-stu-id="cb83e-566">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="cb83e-567">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-567">Outlook</span></span>

- <span data-ttu-id="cb83e-568">Se corrigió un problema que causaba un problema de rendimiento importante al iniciar Outlook en algunos espacios empresariales.</span><span class="sxs-lookup"><span data-stu-id="cb83e-568">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="cb83e-569">Skype</span><span class="sxs-lookup"><span data-stu-id="cb83e-569">Skype</span></span>

- <span data-ttu-id="cb83e-570">Se corrigió un problema por el que se podía producir un error al compartir la pantalla en un cliente de Skype Empresarial de 32 bits después de ejecutarlo durante varios días.</span><span class="sxs-lookup"><span data-stu-id="cb83e-570">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="cb83e-571">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-571">Office Suite</span></span>

- <span data-ttu-id="cb83e-572">Se corrigió un problema que se producía al desactivar el autoguardado a través de la directiva de grupo: era posible que algunos documentos no mostraran el contenido más reciente de servidor al abrirse hasta que el usuario hiciera clic en "Actualizaciones disponibles".</span><span class="sxs-lookup"><span data-stu-id="cb83e-572">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-august-11"></a><span data-ttu-id="cb83e-574">Versión 1908: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="cb83e-574">Version 1908: August 11</span></span>
<span data-ttu-id="cb83e-575">*Versión 1908 (compilación 11929.20934)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-575">*Version 1908 (Build 11929.20934)*</span></span>

<span data-ttu-id="cb83e-576">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-576">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1902-august-11"></a><span data-ttu-id="cb83e-577">Versión 1902: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="cb83e-577">Version 1902: August 11</span></span>
<span data-ttu-id="cb83e-578">*Versión 1902 (compilación 11328.20644)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-578">*Version 1902 (Build 11328.20644)*</span></span>

<span data-ttu-id="cb83e-579">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-579">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-july-14"></a><span data-ttu-id="cb83e-582">Versión 2002: 14 de julio</span><span class="sxs-lookup"><span data-stu-id="cb83e-582">Version 2002: July 14</span></span>
<span data-ttu-id="cb83e-583">*Versión 2002 (compilación 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-583">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="cb83e-584">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-584">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="cb83e-586">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="cb83e-586">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="cb83e-587">Access</span><span class="sxs-lookup"><span data-stu-id="cb83e-587">Access</span></span>

- <span data-ttu-id="cb83e-588">**Buscar tablas vinculadas rápidamente:** nuestro nuevo cuadro de búsqueda hace que buscar tablas vinculadas sea mucho más sencillo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-588">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="cb83e-589">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-589">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="cb83e-590">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-590">Excel</span></span>

- <span data-ttu-id="cb83e-591">**Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-591">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="cb83e-592">**Complemento del visualizador de datos:** Crear rápidamente diagramas de flujo de Visio desde Excel.</span><span class="sxs-lookup"><span data-stu-id="cb83e-592">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="cb83e-593">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-593">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="cb83e-594">**Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-594">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="cb83e-595">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-595">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="cb83e-596">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-596">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="cb83e-597">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-597">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="cb83e-598">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-598">Find them at Insert > Icons.</span></span> [<span data-ttu-id="cb83e-599">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-599">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="cb83e-600">**Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los demás.</span><span class="sxs-lookup"><span data-stu-id="cb83e-600">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="cb83e-601">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-601">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="cb83e-602">**Resalte lo que queda por hacer**: seleccione Resolver para contraer los comentarios y hacer que resalten los elementos abiertos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-602">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="cb83e-603">**Escriba una fórmula que devuelva varios valores:** Escriba rápidamente una fórmula que devuelva múltiples valores y se derramarán automáticamente en las celdas vecinas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-603">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="cb83e-604">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-604">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="cb83e-605">Ver detalles en [entrada de blog](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-605">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="cb83e-606">**Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. </span><span class="sxs-lookup"><span data-stu-id="cb83e-606">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="cb83e-607">**Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su libro.</span><span class="sxs-lookup"><span data-stu-id="cb83e-607">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="cb83e-608">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-608">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="cb83e-609">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-609">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="cb83e-610">**Encuentre lo que busca:** Realice búsquedas de comandos, personas, archivos, fotos, artículos en la web y más.</span><span class="sxs-lookup"><span data-stu-id="cb83e-610">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="cb83e-611">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-611">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="cb83e-612">**Seis potentes funciones:** Seis potentes funciones: Hemos agregado seis nuevas funciones para mejorar las hojas de cálculo: FILTRAR, ORDENAR, ORDENARPOR, UNICOS, SECUENCIA y MATRIZALEAT.</span><span class="sxs-lookup"><span data-stu-id="cb83e-612">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="cb83e-613">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-613">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="cb83e-614">**Busque a la izquierda, busque a la derecha... BUSCARX ya está aquí**: fila por fila, busque lo que necesite en una tabla o un rango con BUSCARX.</span><span class="sxs-lookup"><span data-stu-id="cb83e-614">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="cb83e-615">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-615">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="cb83e-616">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-616">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="cb83e-617">**Dominar el libro grande:** celdas, fórmulas, gráficos y tablas... Obtenga una instantánea de su libro con estadísticas de libros.</span><span class="sxs-lookup"><span data-stu-id="cb83e-617">**Tame your big workbook:** Cells, formulas, charts, tables... get a snapshot of your workbook with Workbook Statistics.</span></span>

- <span data-ttu-id="cb83e-618">**Lea y responda sobre la marcha:** responda a los comentarios y las menciones directamente desde el correo electrónico sin abrir el libro.</span><span class="sxs-lookup"><span data-stu-id="cb83e-618">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="cb83e-619">**Consiga su atención con\@menciones:** use @menciones en los comentarios para avisar a los compañeros de trabajo cuando necesite su participación.</span><span class="sxs-lookup"><span data-stu-id="cb83e-619">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="cb83e-620">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-620">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a><span data-ttu-id="cb83e-621">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-621">Outlook</span></span>

- <span data-ttu-id="cb83e-622">**Encajar más mensajes en la pantalla:** seleccione Ver > Usar espaciado más estrecho para ajustar el espaciado entre mensajes.</span><span class="sxs-lookup"><span data-stu-id="cb83e-622">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="cb83e-623">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-623">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="cb83e-624">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-624">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="cb83e-625">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-625">Find them at Insert > Icons.</span></span> [<span data-ttu-id="cb83e-626">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-626">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="cb83e-627">**Deja que lo dibuje:** garabatee sobre las imágenes o agregue un Lienzo de dibujo para enviar sus pensamientos con la entrada de lápiz.</span><span class="sxs-lookup"><span data-stu-id="cb83e-627">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="cb83e-628">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-628">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="cb83e-629">**Obtenga sugerencias de ubicaciones:** Empiece a escribir en Ubicación cuando programe citas y reuniones, Outlook le sugerirá salas, direcciones y otros lugares recientes.</span><span class="sxs-lookup"><span data-stu-id="cb83e-629">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="cb83e-630">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-630">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br /><span data-ttu-id="cb83e-631">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-631">See details in [blog post](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span></span>

- <span data-ttu-id="cb83e-632">**Protección avanzada frente a ataques**: con la Protección contra amenazas avanzada de Office 365, estará protegido frente a ataques mediante hipervínculos en asuntos de correos electrónicos, mensajes adjuntos, mensajes firmados, rutas de red, etc.</span><span class="sxs-lookup"><span data-stu-id="cb83e-632">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="cb83e-633">**Insertar el menú de vínculos en Outlook inserta un vínculo con el permiso definido por el administrador de inquilinos:** un vínculo desde Insertar vínculo utilizado recientemente en Outlook insertaba un vínculo que solo funcionaba para los usuarios que ya tenían permisos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-633">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="cb83e-634">A menudo esto causaba un intercambio continuo de mensajes de correo electrónico entre los usuarios que pedían acceso a un documento.</span><span class="sxs-lookup"><span data-stu-id="cb83e-634">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="cb83e-635">Hemos actualizado esta experiencia para que ahora el vínculo se inserte con el permiso predeterminado establecido por el administrador de inquilinos. Para MSIT se trata de "la organización puede editar", por lo que todos los usuarios internos que reciban un vínculo compartido de esta manera podrán acceder a él.</span><span class="sxs-lookup"><span data-stu-id="cb83e-635">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="cb83e-636">**Ver los mensajes bajo otra luz:** use el botón sol/luna para cambiar entre fondos claros y oscuros en el panel de lectura.</span><span class="sxs-lookup"><span data-stu-id="cb83e-636">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="cb83e-637">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-637">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="cb83e-638">**Ahora es más fácil detectar correos de suplantación de identidad:** los mensajes de correo no deseado y de suplantación de identidad tienen un aspecto diferente para que pueda identificarlos y eliminarlos fácilmente en la bandeja de entrada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-638">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="cb83e-p159">**Todas las opciones de cifrado en un solo lugar:** vaya a Opciones > Cifrar para elegir cómo proteger su mensaje de correo. [Más información](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="cb83e-p159">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="cb83e-641">**Busque incluso con errores ortográficos o tipográficos:** Outlook encontrará lo que busca, aunque no coincida con la forma exacta en que lo escribió.</span><span class="sxs-lookup"><span data-stu-id="cb83e-641">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="cb83e-642">**Conecte su red de LinkedIn con Outlook:** Conecte de forma segura su cuenta de LinkedIn con su cuenta de Microsoft para ver la información de los perfiles de LinkedIn directamente en las tarjetas personales.</span><span class="sxs-lookup"><span data-stu-id="cb83e-642">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="cb83e-643">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-643">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="cb83e-644">**Ver mensajes relevantes en los resultados de búsqueda:** Outlook analiza los términos de búsqueda y muestra los mensajes de correo electrónico más relevantes en la parte superior de los resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="cb83e-644">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="cb83e-645">También verá todos los resultados ordenados por fecha en la sección de Resultados principales.</span><span class="sxs-lookup"><span data-stu-id="cb83e-645">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="cb83e-646">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-646">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a><span data-ttu-id="cb83e-647">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb83e-647">PowerPoint</span></span>

- <span data-ttu-id="cb83e-p162">**Usted calcula y nosotros le damos formato:** hemos convertido las expresiones matemáticas escritas a mano en caracteres estándar. Simplemente elija Entrada de lápiz a matemáticas y seleccione las notas escritas a mano para empezar. [Más información](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="cb83e-p162">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="cb83e-651">**Encuentre lo que busca:** use el cuadro de búsqueda para buscar texto, comandos, ayuda y mucho más.</span><span class="sxs-lookup"><span data-stu-id="cb83e-651">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="cb83e-652">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-652">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="cb83e-653">**Entrada de tinta para magníficas diapositivas:** convierta el texto de tinta en formas estándar y texto y obtenga ideas de diseño inteligente del Diseñador de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-653">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="cb83e-654">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-654">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="cb83e-655">**Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su presentación.</span><span class="sxs-lookup"><span data-stu-id="cb83e-655">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="cb83e-656">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-656">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="cb83e-657">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-657">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="cb83e-658">**Repetición de entrada de lápiz:** cuando haya entradas de lápiz en sus diapositivas, aplique una animación de reproducción para reproducir el dibujo real de la entrada de lápiz durante la presentación con diapositivas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-658">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="cb83e-659">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-659">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br /><span data-ttu-id="cb83e-660">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-660">See details in [blog post](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span></span>

- <span data-ttu-id="cb83e-661">**Una experiencia de vídeo más segura:** las mejoras de seguridad hacen que la experiencia de vídeo en línea sea más segura.</span><span class="sxs-lookup"><span data-stu-id="cb83e-661">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="cb83e-662">**Guarde una ilustración como SVG:** guarde un gráfico, una forma o una ilustración como un gráfico vectorial escalable, que se puede cambiar de tamaño sin perder calidad de imagen.</span><span class="sxs-lookup"><span data-stu-id="cb83e-662">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="cb83e-663">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-663">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="cb83e-664">**Impresión de números de diapositiva en documentos:** los números de diapositiva se incluyen automáticamente en los documentos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-664">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="cb83e-665">Ahora es usted quien decide si los deja o los quita.</span><span class="sxs-lookup"><span data-stu-id="cb83e-665">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="cb83e-666">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-666">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="cb83e-667">**Encuentre los títulos de diapositivas que faltan y escríbalos**: los títulos de diapositivas añaden fuerza a su discurso y permiten que las diapositivas sean accesibles para los usuarios de todas las capacidades.</span><span class="sxs-lookup"><span data-stu-id="cb83e-667">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="cb83e-668">El comprobador de accesibilidad le muestra dónde faltan títulos para que pueda agregarlos en el momento.</span><span class="sxs-lookup"><span data-stu-id="cb83e-668">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="cb83e-669">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-669">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="cb83e-670">**Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los demás.</span><span class="sxs-lookup"><span data-stu-id="cb83e-670">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="cb83e-671">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-671">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="cb83e-672">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-672">**More icons to match your mood:** We've added more than 300 new icons.</span></span> <span data-ttu-id="cb83e-673">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-673">Find them at Insert > Icons.</span></span> [<span data-ttu-id="cb83e-674">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-674">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="cb83e-675">**Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-675">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span><br /><span data-ttu-id="cb83e-676">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-676">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="cb83e-677">**Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-677">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="cb83e-678">**Colaboración rápida en tiempo real en PowerPoint:** colaboración rápida en tiempo real en PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb83e-678">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="cb83e-679">**Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. </span><span class="sxs-lookup"><span data-stu-id="cb83e-679">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="cb83e-680">**Nuevas herramientas de revisión:** no se preocupe de las palabras.</span><span class="sxs-lookup"><span data-stu-id="cb83e-680">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="cb83e-681">Ahora en PowerPoint se ofrecen sugerencias de gramática y escritura.</span><span class="sxs-lookup"><span data-stu-id="cb83e-681">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="cb83e-682">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-682">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="cb83e-683">**Transcripción y subtítulos en directo:** las palabras del moderador se muestran automáticamente en la pantalla como subtítulos o se traducen en el idioma que prefiera.</span><span class="sxs-lookup"><span data-stu-id="cb83e-683">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="cb83e-684">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-684">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="cb83e-685">**Optimizar la presentación para todos:** el comprobador de accesibilidad le ayuda a organizar los objetos de las diapositivas pensando en los lectores de pantalla.</span><span class="sxs-lookup"><span data-stu-id="cb83e-685">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span><br /><span data-ttu-id="cb83e-686">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-686">See details in [blog post](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span></span>

- <span data-ttu-id="cb83e-687">**¿Para que reinventar lo que puede reutilizar?:** ahorre tiempo usando de nuevo las diapositivas que haya creado o que otros usuarios han compartido con usted.</span><span class="sxs-lookup"><span data-stu-id="cb83e-687">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="cb83e-688">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-688">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a><span data-ttu-id="cb83e-689">Visio</span><span class="sxs-lookup"><span data-stu-id="cb83e-689">Visio</span></span>

- <span data-ttu-id="cb83e-690">**Cree diagramas de Visio elegantes en Excel:** cree un diagrama de flujo o un organigrama con solo escribir datos en una hoja de cálculo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-690">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="cb83e-691">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-691">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="cb83e-692">**Vuelva a la escena del crimen:** use las nuevas plantillas Evidencia, Interior y Exterior en la plantilla Investigación de Escenas de Delitos para recrear con detalle escenarios de delitos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-692">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

### <a name="word"></a><span data-ttu-id="cb83e-693">Word</span><span class="sxs-lookup"><span data-stu-id="cb83e-693">Word</span></span>

- <span data-ttu-id="cb83e-694">**Una experiencia de vídeo más segura:** las mejoras de seguridad hacen que la experiencia de vídeo en línea sea más segura.</span><span class="sxs-lookup"><span data-stu-id="cb83e-694">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="cb83e-695">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-695">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="cb83e-696">**Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-696">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="cb83e-697">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-697">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="cb83e-698">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-698">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="cb83e-699">**Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-699">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="cb83e-700">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-700">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="cb83e-701">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-701">Find them at Insert > Icons.</span></span> [<span data-ttu-id="cb83e-702">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-702">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br /><span data-ttu-id="cb83e-703">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-703">See details in [blog post](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span></span>

- <span data-ttu-id="cb83e-704">**Borrar con precisión:** elija entre dos tamaños de borrador para arreglar pequeñas imperfecciones de la entrada de lápiz.</span><span class="sxs-lookup"><span data-stu-id="cb83e-704">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="cb83e-705">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-705">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="cb83e-706">**Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los demás.</span><span class="sxs-lookup"><span data-stu-id="cb83e-706">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="cb83e-707">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-707">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="cb83e-708">**Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su documento.</span><span class="sxs-lookup"><span data-stu-id="cb83e-708">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="cb83e-709">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-709">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="cb83e-710">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="cb83e-710">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="cb83e-711">**Encuentre lo que busca:** use el cuadro de búsqueda para buscar texto, comandos, ayuda y mucho más.</span><span class="sxs-lookup"><span data-stu-id="cb83e-711">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="cb83e-712">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-712">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="cb83e-713">**Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. </span><span class="sxs-lookup"><span data-stu-id="cb83e-713">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="cb83e-714">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-714">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="cb83e-715">**El Editor para currículum vítae incorpora el Asistente para currículum vítae de LinkedIn:** el Editor para currículum vítae ofrece una selección de comprobaciones gramaticales y de estilo especialmente adaptadas a los currículums, para que el texto sea más preciso y profesional.</span><span class="sxs-lookup"><span data-stu-id="cb83e-715">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="cb83e-716">**Otros usuarios verán los cambios rápidamente:** con las mejoras en la coautoría, los colaboradores podrán ver los cambios más rápido que nunca.</span><span class="sxs-lookup"><span data-stu-id="cb83e-716">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="cb83e-717">**Se ha corregido un problema relacionado con los documentos causados por la combinación de objetos 3D:** corrige un problema de daños en un documento producido por la combinación de objetos 3D.</span><span class="sxs-lookup"><span data-stu-id="cb83e-717">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="cb83e-718">**Mejoras en la coautoría:** mejora del rendimiento de Word en coautoría en documentos con marcas de revisión.</span><span class="sxs-lookup"><span data-stu-id="cb83e-718">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="cb83e-719">**Mejoras en la coautoría:** mejora de la confiabilidad de la coautoría.</span><span class="sxs-lookup"><span data-stu-id="cb83e-719">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="cb83e-720">**Colaborando a todo color:** los comentarios y los cambios están codificados por color según la persona que contribuya, por lo que es fácil distinguir entre sus colaboradores.</span><span class="sxs-lookup"><span data-stu-id="cb83e-720">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="cb83e-721">**Editar documentos habilitados para macros de forma conjunta:** guarde sus archivos .docm en OneDrive para la Empresa y edítelos con sus colaboradores en tiempo real.</span><span class="sxs-lookup"><span data-stu-id="cb83e-721">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="cb83e-722">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-722">Office Suite</span></span>

- <span data-ttu-id="cb83e-723">**Transforme la entrada de lápiz en formas, texto o matemáticas en PowerPoint para Office 365:** convierta la entrada de lápiz en forma libre a formas, textos o expresiones matemáticas de Office en un par de trazos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-723">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="cb83e-724">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-724">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-727">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-727">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="cb83e-728">Access</span><span class="sxs-lookup"><span data-stu-id="cb83e-728">Access</span></span>

- <span data-ttu-id="cb83e-729">Esta actualización corrige un problema por el que al usar un objeto de grabación de ADODB</span><span class="sxs-lookup"><span data-stu-id="cb83e-729">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="cb83e-730">en el código de VB, se puede notificar un error incorrectamente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-730">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="cb83e-731">Las plantillas de Access ya no deberían causar errores en columnas de datos adjuntos en una base de datos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-731">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="cb83e-732">Después de crear la instancia de una plantilla, ahora debería poder agregar un campo de datos adjuntos a la base de datos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-732">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="cb83e-733">Esta actualización corrige un problema que puede hacer que Microsoft Access no identifique una Columna de identidad en una tabla vinculada de SQL Server, lo que puede provocar que las filas aparezcan como eliminadas de forma incorrecta.</span><span class="sxs-lookup"><span data-stu-id="cb83e-733">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="cb83e-734">Esta actualización corrige un problema en Microsoft Access que puede causar el error "La consulta está dañada" cuando se ejecuta una consulta de actualización o cuando se usa una instrucción UPDATE en SQL.</span><span class="sxs-lookup"><span data-stu-id="cb83e-734">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="cb83e-735">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-735">Excel</span></span>

- <span data-ttu-id="cb83e-736">Acelere la carga de archivos que están disponibles en la carpeta de OneDrive local.</span><span class="sxs-lookup"><span data-stu-id="cb83e-736">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="cb83e-737">Se ha solucionado un problema por el que las funciones CUBEVALUE a veces daban un resultado incorrecto.</span><span class="sxs-lookup"><span data-stu-id="cb83e-737">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="cb83e-738">Resuelto un problema con la personalización de la cinta que no se cargaba al abrir el libro de trabajo incrustado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-738">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="cb83e-739">Excel se bloqueaba en ciertos casos cuando se volvía a abrir un libro incrustado en Word o PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-739">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="cb83e-740">Se ha corregido un problema por el que los comandos de comentario en el menú contextual no aparecían.</span><span class="sxs-lookup"><span data-stu-id="cb83e-740">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="cb83e-741">Se ha corregido el botón derecho en el menú de gráficos dinámicos para habilitar la opción de mostrar los detalles.</span><span class="sxs-lookup"><span data-stu-id="cb83e-741">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="cb83e-742">Se ha resuelto un problema que puede haber causado un bloqueo al buscar archivos recientes cuando no hay ningún libro de trabajo abierto.</span><span class="sxs-lookup"><span data-stu-id="cb83e-742">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="cb83e-743">Se ha corregido un problema que provocaba que, al hacer clic en un hipervínculo marcado en el propio libro, se ocultara dicho libro.</span><span class="sxs-lookup"><span data-stu-id="cb83e-743">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="cb83e-744">Cuando guarda como un archivo CSV, Excel podía combinar todas las columnas en una sola columna en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-744">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="cb83e-745">Usar Range.ClearContents en un rango de una hoja protegida podía tardar más de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-745">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="cb83e-746">Corregido un problema con la escala de texto en los controles de formulario cuando se mostraba en la Vista previa de impresión.</span><span class="sxs-lookup"><span data-stu-id="cb83e-746">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="cb83e-747">Las macros de VBA que interactúan con la cinta de opciones se pueden ejecutar con ScreenUpdating establecido en True inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-747">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="cb83e-748">Se ha corregido un problema que hacía que Excel se bloqueara en ciertos casos después de copiar una hoja que contenía una tabla dinámica.</span><span class="sxs-lookup"><span data-stu-id="cb83e-748">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="cb83e-749">La apertura de archivos CSV tardaba más de lo esperado en algunas circunstancias.</span><span class="sxs-lookup"><span data-stu-id="cb83e-749">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="cb83e-750">Excel se bloqueaba en determinadas circunstancias al cambiar entre libros con diferentes niveles de zoom.</span><span class="sxs-lookup"><span data-stu-id="cb83e-750">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="cb83e-751">Se ha corregido un problema con VBA por el que escribir valores en un rango era más lento de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-751">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="cb83e-752">En ocasiones, los datos copiados de una columna filtrada por color no se pegaban correctamente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-752">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="cb83e-753">La apertura de un libro de trabajo con referencias a muchos otros libros de trabajo, especialmente con ventanas ocultas, era más lenta de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-753">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="cb83e-754">Se ha corregido un problema por el que los enlaces externos no se actualizaban al rellenar (rellenar hacia abajo, rellenar en otros, etc.) si el libro de origen estaba cerrado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-754">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is& closed.</span></span>

- <span data-ttu-id="cb83e-755">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="cb83e-755">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="cb83e-756">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="cb83e-756">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="cb83e-757">Se ha corregido un problema por el que la propiedad "Valor se cruza en" en el eje del gráfico cambiaba inesperadamente al guardar y volver a abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-757">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="cb83e-758">Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta al guardar en SharePoint o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="cb83e-758">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="cb83e-759">Se ha mejorado el rendimiento al eliminar columnas con celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-759">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="cb83e-760">Se ha corregido un problema por el que los nombres de las impresoras podrían repetirse en la lista de impresoras en el cuadro de diálogo Imprimir.</span><span class="sxs-lookup"><span data-stu-id="cb83e-760">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="cb83e-761">Se ha corregido un problema que hacía que el vínculo externo dejara de funcionar después de que se volviera a abrir el archivo si su ruta de acceso era demasiado larga.</span><span class="sxs-lookup"><span data-stu-id="cb83e-761">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="cb83e-762">Se ha corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.</span><span class="sxs-lookup"><span data-stu-id="cb83e-762">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="cb83e-763">Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-763">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="cb83e-764">Insertar una columna en una lista filtrada llevaba más tiempo de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-764">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="cb83e-765">Se ha corregido un problema por el que algunos vínculos de un gráfico copiado y pegado usaban direcciones de unidad asignadas, en lugar de direcciones universales.</span><span class="sxs-lookup"><span data-stu-id="cb83e-765">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="cb83e-766">Se ha corregido un problema que producía el siguiente mensaje de error: "No se puede cerrar el libro de trabajo debido a que otro libro hace referencia al mismo". El mensaje aparecía si los complementos se cargaban en orden alfabético en lugar de en un orden especificado por el usuario.</span><span class="sxs-lookup"><span data-stu-id="cb83e-766">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="cb83e-767">Se ha corregido un problema que haría que un libro se ocultara al hacer clic en un hipervínculo a un lugar dentro de un libro ya abierto.</span><span class="sxs-lookup"><span data-stu-id="cb83e-767">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="cb83e-768">La apertura de un libro de trabajo con referencias a muchos otros libros de trabajo, especialmente con ventanas ocultas, era más lenta de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-768">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="cb83e-769">El uso de Application.Evaluate de VBA no funcionaba para funciones definidas por el usuario en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-769">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="cb83e-770">Se ha corregido un problema que algunos usuarios pudieron sufrir con objetos incrustados y vinculados (OLE).</span><span class="sxs-lookup"><span data-stu-id="cb83e-770">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="cb83e-771">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="cb83e-771">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="cb83e-772">Esta actualización corrige un problema que causaba que la barra de fórmulas mostrara texto en una fuente diferente a la esperada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-772">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="cb83e-773">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="cb83e-773">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="cb83e-774">Corregimos un problema en el que al seleccionar una celda luego de desplazar, podía resultar en la selección de la celda incorrecta.</span><span class="sxs-lookup"><span data-stu-id="cb83e-774">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="cb83e-775">Los usuarios pueden encontrar un error al acceder a un rango con nombre oculto.</span><span class="sxs-lookup"><span data-stu-id="cb83e-775">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="cb83e-776">Excel puede tener problemas al editar un archivo protegido desde una red compartida no confiable.</span><span class="sxs-lookup"><span data-stu-id="cb83e-776">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="cb83e-777">La funcionalidad de texto a columna puede fallar en algunas localizaciones.</span><span class="sxs-lookup"><span data-stu-id="cb83e-777">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="cb83e-778">Se ha corregido un problema de rendimiento al crear gráficos a partir de plantillas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-778">Addresses a performance issue when creating charts from templates.</span></span>

- <span data-ttu-id="cb83e-779">Se ha corregido un problema que causaba que algunos usuarios experimentasen bloqueos al convertir texto en columnas con celdas que tienen una matriz derramada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-779">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="cb83e-780">El uso de un Range.Value y Range.Value2 (VBA) hacía que las fórmulas se escribieran como matrices dinámicas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-780">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

- <span data-ttu-id="cb83e-781">Se ha corregido un problema por el que un símbolo @ que inicia una fórmula se considera un operador de intersección implícita.</span><span class="sxs-lookup"><span data-stu-id="cb83e-781">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

- <span data-ttu-id="cb83e-782">Se ha corregido un problema por el que las hojas de cálculo que contenían varias fórmulas con nombres definidos tardaban más en guardarse.</span><span class="sxs-lookup"><span data-stu-id="cb83e-782">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="cb83e-783">Este cambio evita un problema con ciertos controladores de gráficos Intel al aprovechar el procesamiento del software.</span><span class="sxs-lookup"><span data-stu-id="cb83e-783">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="cb83e-784">Se ha corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.</span><span class="sxs-lookup"><span data-stu-id="cb83e-784">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="onenote"></a><span data-ttu-id="cb83e-785">OneNote</span><span class="sxs-lookup"><span data-stu-id="cb83e-785">OneNote</span></span>

- <span data-ttu-id="cb83e-786">Mejora la sincronización y la estabilidad del servicio al ajustar temporalmente la frecuencia de sincronización en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="cb83e-786">Improve sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="cb83e-787">Mejora la sincronización y la estabilidad del servicio al diferir temporalmente la descarga de archivos e imágenes incrustados en los blocs de notas en línea hasta que el usuario navegue a la página en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="cb83e-787">Improve sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="cb83e-788">Mejora la sincronización y la estabilidad del servicio al deshabilitar temporalmente la papelera de reciclaje en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="cb83e-788">Improve sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="cb83e-789">Cuando un usuario intenta eliminar datos que normalmente se enviarían a la papelera de reciclaje, se le preguntará si prefiere conservarlos o eliminarlos forma permanente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-789">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="cb83e-790">Mejora la sincronización y estabilidad de servicio mejoradas al reducir temporalmente el número y la frecuencia de sincronización de las páginas del historial de versiones en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="cb83e-790">Improve sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="cb83e-791">Muestra una notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="cb83e-791">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="cb83e-792">Mejora la sincronización y la estabilidad del servicio al reducir temporalmente el tamaño máximo de nuevos datos adjuntos insertados a 50 MB en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="cb83e-792">Improve sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="cb83e-793">Si los archivos superan este límite, los usuarios tendrán la opción de cargar el archivo a OneDrive e insertar un vínculo en OneNote.</span><span class="sxs-lookup"><span data-stu-id="cb83e-793">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="cb83e-794">Mejora la sincronización y la estabilidad del servicio al deshabilitar temporalmente la grabación de vídeo en la aplicación en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="cb83e-794">Improve sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="cb83e-795">La medida no afecta a los blocs de notas locales.</span><span class="sxs-lookup"><span data-stu-id="cb83e-795">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="cb83e-796">Localiza la notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="cb83e-796">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="cb83e-797">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-797">Outlook</span></span>

- <span data-ttu-id="cb83e-798">Se ha corregido un problema por el que la ventana del Editor de métodos de entrada (IME) se superponía al texto subyacente escrito mediante el IME cuando se usaban varios monitores con resoluciones diferentes.</span><span class="sxs-lookup"><span data-stu-id="cb83e-798">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="cb83e-799">Se ha corregido un problema que provocaba que los usuarios vean bloqueos ocasionales en Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-799">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="cb83e-800">Esto actualiza la lógica de bloqueo de adjuntos en Outlook para bloquear también los adjuntos de Python.</span><span class="sxs-lookup"><span data-stu-id="cb83e-800">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="cb83e-801">Se ha corregido un problema que provocaba que los complementos web accedieran a los mensajes administrados con derechos digitales.</span><span class="sxs-lookup"><span data-stu-id="cb83e-801">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="cb83e-802">Se ha corregido un problema que causaba que las citas o reuniones periódicas se mostraran en un momento incorrecto al tratar de cambiar la definición de una zona horaria.</span><span class="sxs-lookup"><span data-stu-id="cb83e-802">Addresses an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="cb83e-803">Cuando se utiliza la zona horaria de Brasilia en el año 2019, las reuniones y citas recurrentes se muestran en la franja horaria equivocada para el año 2020.</span><span class="sxs-lookup"><span data-stu-id="cb83e-803">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="cb83e-804">Este cambio es relevante para los clientes establecidos en la zona horaria de Brasilia o para las reuniones y citas establecidas en esa zona horaria.</span><span class="sxs-lookup"><span data-stu-id="cb83e-804">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span><br><br><span data-ttu-id="cb83e-805">Este cambio permite a Outlook reemplazar algunas opciones de configuración de zona horaria utilizadas por Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-805">This change allows Outlook to override certain time zone settings used by Outlook.</span></span> <span data-ttu-id="cb83e-806">Para invocar una invalidación de zona horaria, debe establecer una clave del registro para el usuario actual.</span><span class="sxs-lookup"><span data-stu-id="cb83e-806">In order to invoke a time zone override you must set a registry key for the current user.</span></span> <span data-ttu-id="cb83e-807">El nombre de la clave del registro debe coincidir con el nombre interno de la zona horaria.</span><span class="sxs-lookup"><span data-stu-id="cb83e-807">The registry key name must match the internal name of the time zone.</span></span> <span data-ttu-id="cb83e-808">El valor indica el año en el que se va a usar la regla de zona horaria en vez del año efectivo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-808">The value indicates the time zone rule's year to be used in place of the effective year.</span></span> <span data-ttu-id="cb83e-809">Por ejemplo, el siguiente valor para reemplazar la clave del registro usará la regla de zona horaria de Brasil para el año 2020 como regla efectiva.</span><span class="sxs-lookup"><span data-stu-id="cb83e-809">For example, the following registry key override value will use the Brazilia time zone rule for the year 2020 as the effective rule.</span></span> <span data-ttu-id="cb83e-810">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span><span class="sxs-lookup"><span data-stu-id="cb83e-810">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span></span> <span data-ttu-id="cb83e-811">Hora estándar de Sudamérica"=dword:000007e4.</span><span class="sxs-lookup"><span data-stu-id="cb83e-811">South America Standard Time"=dword:000007e4.</span></span>

- <span data-ttu-id="cb83e-812">Se ha corregido un problema por el que los usuarios veían cambiar el campo de ubicación de las reuniones de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-812">Addresses an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="cb83e-813">Se ha corregido un problema que provocaba que el campo Ubicación en las reuniones se actualizara de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-813">Addresses an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="cb83e-814">Se ha corregido un problema que provocó que la ubicación de una reunión se volviera a añadir a la reunión de forma inesperada después de despejarla.</span><span class="sxs-lookup"><span data-stu-id="cb83e-814">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="cb83e-815">Se ha corregido un tema que causó que las comas en el campo de ubicación de una reunión se convirtieran en punto y coma.</span><span class="sxs-lookup"><span data-stu-id="cb83e-815">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="cb83e-816">Permite unirse a una reunión de Teams directamente a través del cliente nativo de Teams.</span><span class="sxs-lookup"><span data-stu-id="cb83e-816">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="cb83e-817">Se ha corregido un problema que provocaba que los usuarios con buzones en servidores de Exchange 2010 sufrieran problemas al agregar archivos adjuntos a elementos de calendario.</span><span class="sxs-lookup"><span data-stu-id="cb83e-817">Addresses an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="cb83e-818">Se ha corregido un problema que provocaba que los usuarios experimentaran problemas al responder a los mensajes firmados digitalmente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-818">Addresses an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="cb83e-819">Se ha corregido un problema que provocaba que los usuarios no pudieran abrir algunas instancias de los elementos de calendario periódicos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-819">Addresses an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="cb83e-820">Se ha corregido un problema que hacía que el encabezado de grupo se expandiera de forma inesperada en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="cb83e-820">Addresses an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="cb83e-821">Se ha corregido un problema que provocaba que el ancho del panel de carpetas cambiara de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-821">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="cb83e-822">Se ha corregido un problema por el que Outlook no pudo habilitar consejos de directiva para la Protección de pérdida de datos para usuarios que pagaron por el servicio con planes M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="cb83e-822">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="cb83e-823">Se ha corregido un problema por el que los usuarios notaban un retraso evidente al interactuar con sus carpetas de buzón mediante métodos abreviados de teclado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-823">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="cb83e-824">Se ha corregido un problema que podría resultar en un choque al ver el mismo elemento en varias ventanas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-824">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="cb83e-825">Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al actualizar sus reglas en Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-825">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="cb83e-826">Se ha corregido un problema que causaba una pérdida de memoria en sesiones de Outlook muy largas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-826">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="cb83e-827">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.</span><span class="sxs-lookup"><span data-stu-id="cb83e-827">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="cb83e-828">Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al abrir el cuadro de diálogo de Reglas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-828">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="cb83e-829">Se ha corregido un problema por el que la opción para deshabilitar el resaltado de elementos marcados no funcionaba en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="cb83e-829">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="cb83e-830">Se ha corregido un problema que provocaba que los usuarios vieran mensajes enviados inesperadamente al presionar la tecla "S" después de cerrar el panel del comprobador de accesibilidad.</span><span class="sxs-lookup"><span data-stu-id="cb83e-830">Addresses an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="cb83e-831">Se ha corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.</span><span class="sxs-lookup"><span data-stu-id="cb83e-831">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="cb83e-832">Se ha corregido un problema que provocaba que los usuarios experimentaran un error al cancelar la configuración de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="cb83e-832">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="cb83e-833">Se ha corregido un problema por el que Outlook sincronizaba inesperadamente todo el correo, incluso cuando el deslizador de sincronización estaba configurado en un ajuste menor.</span><span class="sxs-lookup"><span data-stu-id="cb83e-833">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="cb83e-834">Se ha corregido un problema que provocaba que los usuarios con el Tema negro vieran texto blanco sobre un fondo blanco en el desplegable "De".</span><span class="sxs-lookup"><span data-stu-id="cb83e-834">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="cb83e-835">Se ha corregido un problema que provocaba que los usuarios sufrieran un bloqueo durante la creación del perfil.</span><span class="sxs-lookup"><span data-stu-id="cb83e-835">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="cb83e-836">Se ha corregido un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "OK" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="cb83e-836">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="cb83e-837">Se ha corregido un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "OK" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="cb83e-837">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="cb83e-838">Se ha corregido un problema que provocaba que las aplicaciones de terceros no pudiesen enviar correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="cb83e-838">Addresses an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="cb83e-839">Se ha corregido un problema que provocaba que las categorías desapareciesen en ocasiones de los mensajes de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="cb83e-839">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="cb83e-840">Se ha corregido un problema que provocaba que los usuarios de Outlook en sistemas operativos de servidor vieran el error: "Estado del antivirus: no válido.</span><span class="sxs-lookup"><span data-stu-id="cb83e-840">Addresses an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="cb83e-841">Esta versión de Windows admite la detección del antivirus, pero no se encontró ninguno" a pesar de tener el antivirus correctamente configurado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-841">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

- <span data-ttu-id="cb83e-842">Se ha corregido un problema que provocaba que los delegados viesen distintas jerarquías de carpetas en diferentes equipos para los buzones compartidos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-842">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="cb83e-843">Se ha corregido un problema que causaba que los delegados reciban un error al editar una cita de calendario existente en el calendario de un administrador.</span><span class="sxs-lookup"><span data-stu-id="cb83e-843">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="cb83e-844">Se ha corregido un problema que provocaba que los usuarios con la configuración de emulación de explorador incorrecta no pudieran completar el mensaje de autenticación de Gmail.</span><span class="sxs-lookup"><span data-stu-id="cb83e-844">Addresses an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="cb83e-845">Se ha corregido un problema que causaba que faltara la opción "Permitir reenvío" en las "Opciones de respuesta" de la reunión de calendario compartida cuando NO está marcada Descargar carpeta compartida.</span><span class="sxs-lookup"><span data-stu-id="cb83e-845">Addresses an issue that caused the " Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="cb83e-846">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al intentar abrir archivos .msg y .oft después de una actualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="cb83e-846">Addresses an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="cb83e-847">Se ha corregido un problema que causaba que los usuarios experimentaran ocasionalmente un bloqueo al usar el botón X de su ratón.</span><span class="sxs-lookup"><span data-stu-id="cb83e-847">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="cb83e-848">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al seleccionar determinados resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="cb83e-848">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="cb83e-849">Se ha corregido un problema que hizo que el botón "Guardar en la nube" faltara en las herramientas de adjuntos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-849">Addresses an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="cb83e-850">Este cambio restaura la capacidad de ver sujetos de varias líneas en el encabezado del mensaje.</span><span class="sxs-lookup"><span data-stu-id="cb83e-850">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="cb83e-851">Se ha corregido un problema que causaba que los usuarios experimentaran un bloqueo cuando dos complementos agregan un botón al mismo grupo de la cinta de opciones.</span><span class="sxs-lookup"><span data-stu-id="cb83e-851">Addresses an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="cb83e-852">Se ha corregido un problema que provocaba que los vínculos no se agreguen a los correos electrónicos con el permiso predeterminado incorrecto de espacio empresarial cuando el permiso predeterminado de espacio empresarial se configura como "cualquiera".</span><span class="sxs-lookup"><span data-stu-id="cb83e-852">Addresses an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as "anyone".</span></span>

- <span data-ttu-id="cb83e-853">Se ha corregido un problema que provocaba que los usuarios no pudieran dirigir mensajes de correo electrónico a una lista de distribución personal.</span><span class="sxs-lookup"><span data-stu-id="cb83e-853">Addresses an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="cb83e-854">Se ha corregido un problema que hacía que los usuarios vieran el truncamiento del cuerpo del mensaje al reenviar mensajes HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="cb83e-854">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="cb83e-855">Se ha corregido un problema con la selección del algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="cb83e-855">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="cb83e-856">Se ha corregido un problema que podía impedir que los archivos se guardaran en una ubicación de WebDAV.</span><span class="sxs-lookup"><span data-stu-id="cb83e-856">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="cb83e-857">Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.</span><span class="sxs-lookup"><span data-stu-id="cb83e-857">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="cb83e-858">Se ha corregido un problema que provocaba que el cuerpo de un mensaje NDR cambiara de Unicode a ASCII después de editar el asunto.</span><span class="sxs-lookup"><span data-stu-id="cb83e-858">Addresses an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="cb83e-859">Se ha corregido un problema que hacía que los usuarios observaran una pérdida de memoria en el proceso de Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-859">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="cb83e-860">Corrige un problema que provocaba que los usuarios vieran mensajes de correo electrónico enviados a una dirección que no coincidía con la dirección SMTP mostrada en determinadas circunstancias.</span><span class="sxs-lookup"><span data-stu-id="cb83e-860">Addresses an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="cb83e-861">Se ha corregido un problema que provocaba que el cuadro de búsqueda estuviera mal alineado en modo de PPP alto.</span><span class="sxs-lookup"><span data-stu-id="cb83e-861">Addresses an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="cb83e-862">Se ha corregido un problema por el que los usuarios experimentan bloqueos en Outlook al recuperar la configuración de la nube.</span><span class="sxs-lookup"><span data-stu-id="cb83e-862">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="cb83e-863">Se ha corregido un problema que causó un bloqueo en la experiencia de los comentarios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="cb83e-863">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="cb83e-864">Se ha corregido un problema que provocaba que los usuarios vean bloqueos ocasionales en Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-864">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="cb83e-865">Se ha corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.</span><span class="sxs-lookup"><span data-stu-id="cb83e-865">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="cb83e-866">Se ha corregido un problema que provocaba que los usuarios sufrieran un bloqueo durante la creación del perfil.</span><span class="sxs-lookup"><span data-stu-id="cb83e-866">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="cb83e-867">Se ha corregido un problema que provocaba que los usuarios vean bloqueos ocasionales en Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-867">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="cb83e-868">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb83e-868">PowerPoint</span></span>

- <span data-ttu-id="cb83e-869">Se ha corregido un problema que podía bloquear el equipo al usar el menú contextual en comentarios PPT heredados.</span><span class="sxs-lookup"><span data-stu-id="cb83e-869">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

- <span data-ttu-id="cb83e-870">Se ha mejorado un escenario de copiar y pegar: al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.</span><span class="sxs-lookup"><span data-stu-id="cb83e-870">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="cb83e-871">Se ha corregido un problema para retransmitir la mensajería correcta a los usuarios que abren una copia de un archivo que ha mejorado los comentarios.</span><span class="sxs-lookup"><span data-stu-id="cb83e-871">Fixes an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="project"></a><span data-ttu-id="cb83e-872">Project</span><span class="sxs-lookup"><span data-stu-id="cb83e-872">Project</span></span>

- <span data-ttu-id="cb83e-873">Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-873">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="cb83e-874">Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="cb83e-874">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="cb83e-875">Corregido un problema que hace que el evento ProjectBeforeTaskChange no detecte cuándo se ha desactivado o activado una tarea mediante el botón Desactivar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-875">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="cb83e-876">Corregido un problema por el que Project puede bloquearse al guardar proyectos creados con versiones anteriores de Project.</span><span class="sxs-lookup"><span data-stu-id="cb83e-876">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="cb83e-877">Identificamos un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de solo lectura</span><span class="sxs-lookup"><span data-stu-id="cb83e-877">Identified an issue where users could get several messages when opening a read-only project</span></span>

- <span data-ttu-id="cb83e-878">Se ha corregido un problema por el que el 100 % de las tareas de tipo duración fija podían tener un cálculo del porcentaje incorrecto con menos del 100% completado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-878">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="cb83e-879">Word</span><span class="sxs-lookup"><span data-stu-id="cb83e-879">Word</span></span>

- <span data-ttu-id="cb83e-880">Se ha corregido un problema que causaba que los usuarios experimentaran ocasionalmente un bloqueo al usar el botón X de su ratón.</span><span class="sxs-lookup"><span data-stu-id="cb83e-880">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="cb83e-881">Se ha corregido un problema por el que la alineación de las palabras de un documento se descomponía al intentar editar después de imprimir con la impresión rápida.</span><span class="sxs-lookup"><span data-stu-id="cb83e-881">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="cb83e-882">Corregido un problema con el ajuste de texto en una tabla.</span><span class="sxs-lookup"><span data-stu-id="cb83e-882">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="cb83e-883">Corregido un problema donde al insertar líneas horizontales no eran más cortas ni centradas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-883">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>

- <span data-ttu-id="cb83e-884">El organizador de bloques de creación puede mostrar una alerta no válida: "Ha modificado estilos, bloques de creación".</span><span class="sxs-lookup"><span data-stu-id="cb83e-884">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

- <span data-ttu-id="cb83e-885">Se ha corregido un problema de coautoría si se habilita la Directiva FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="cb83e-885">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="cb83e-886">Se ha corregido un problema en el que Word QuickPart no funciona al agregar un campo de búsqueda cuyo nombre se ha cambiado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-886">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

- <span data-ttu-id="cb83e-887">Se ha corregido un problema al combinar dos documentos en uno.</span><span class="sxs-lookup"><span data-stu-id="cb83e-887">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="cb83e-888">Se ha corregido un problema con la característica Comparación para los documentos protegidos para la edición.</span><span class="sxs-lookup"><span data-stu-id="cb83e-888">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="cb83e-889">Esta actualización corrige un problema en Microsoft Word por el que el texto que supera los 255 caracteres insertados durante la aplicación de una etiqueta de confidencialidad no se pudiese identificar y quitar posteriormente cambiando o quitando la etiqueta si la directiva de etiqueta aplicó un encabezado, un pie de página o una marca de agua.</span><span class="sxs-lookup"><span data-stu-id="cb83e-889">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

### <a name="office-suite"></a><span data-ttu-id="cb83e-890">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-890">Office Suite</span></span>

- <span data-ttu-id="cb83e-891">Se ha corregido un problema en el que los usuarios puedan experimentar demasiado uso de la red y la CPU durante la coautoría en archivos de PowerPoint grandes.</span><span class="sxs-lookup"><span data-stu-id="cb83e-891">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="cb83e-892">Esta es una corrección para que la aplicación de Project no bloquee la red cuando el archivo se almacena en caché en el cliente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-892">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>


- <span data-ttu-id="cb83e-893">Se ha resuelto este problema mediante la actualización de los nombres de canal en el backstage con los nuevos nombres de canal en la bifurcación de enero de 2020.</span><span class="sxs-lookup"><span data-stu-id="cb83e-893">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="cb83e-894">Se ha corregido este problema y en adelante, si un dispositivo se administra mediante directiva, no llamará a la API de audiencia de DMS.</span><span class="sxs-lookup"><span data-stu-id="cb83e-894">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="cb83e-895">Se ha corregido un problema en el que había una eliminación incompleta al agregar y quitar aplicaciones en una sola transacción.</span><span class="sxs-lookup"><span data-stu-id="cb83e-895">We have resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="cb83e-896">Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.</span><span class="sxs-lookup"><span data-stu-id="cb83e-896">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="cb83e-897">Corrige un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.</span><span class="sxs-lookup"><span data-stu-id="cb83e-897">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="cb83e-898">Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.</span><span class="sxs-lookup"><span data-stu-id="cb83e-898">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="cb83e-899">Hemos modificado la versión AppV51 para solucionar una regresión de la AppV51 anterior.</span><span class="sxs-lookup"><span data-stu-id="cb83e-899">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="cb83e-900">Hemos resuelto el problema por el que una operación interna producía una excepción en caso de error en lugar de registrarlo y continuar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-900">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="cb83e-901">Los usuarios afectados ya no serán bloqueados para recibir actualizaciones.</span><span class="sxs-lookup"><span data-stu-id="cb83e-901">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="cb83e-902">Nuestro equipo ha agregado compatibilidad con clientes para informar la telemetría en los dominios de la red CDN en semianual Enterprise Preview.</span><span class="sxs-lookup"><span data-stu-id="cb83e-902">Our team has added client support for reporting telemetry on the Office CDN domains in Semi-Annual Enterprise Preview.</span></span>

- <span data-ttu-id="cb83e-903">Este cambio resuelve problemas con adaptadores gráficos que aprovechan la GPU integrada de Intel.</span><span class="sxs-lookup"><span data-stu-id="cb83e-903">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="cb83e-904">Este cambio garantiza que el contorno Esbozado funcione correctamente en la cinta de opciones.</span><span class="sxs-lookup"><span data-stu-id="cb83e-904">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="cb83e-905">Se ha corregido un problema al abrir archivos de ubicaciones locales con algunas configuraciones de proxy específicas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-905">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="cb83e-906">Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.</span><span class="sxs-lookup"><span data-stu-id="cb83e-906">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="cb83e-907">Se ha corregido un problema que elimina bloqueos durante las sesiones de entrega de Office y se ha mejorado la fiabilidad de la experiencia del usuario.</span><span class="sxs-lookup"><span data-stu-id="cb83e-907">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>

- <span data-ttu-id="cb83e-908">Este error actualiza el extremo de la URL del servicio de configuración mejorada (ECS).</span><span class="sxs-lookup"><span data-stu-id="cb83e-908">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="cb83e-909">Llamar a este punto de conexión más reciente tiene una tasa de éxito superior para capturar desde ECS.</span><span class="sxs-lookup"><span data-stu-id="cb83e-909">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

- <span data-ttu-id="cb83e-910">Esta actualización corrige un problema en el que con Microsoft Outlook no muestra la etiqueta de confidencialidad actual al ver o redactar mensajes.</span><span class="sxs-lookup"><span data-stu-id="cb83e-910">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="cb83e-911">Corrige un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-911">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

- <span data-ttu-id="cb83e-912">Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="cb83e-912">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="cb83e-913">El host de Office se cerraba en Windows al activar un complemento cuando la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth estaba establecida en cero.</span><span class="sxs-lookup"><span data-stu-id="cb83e-913">The office host was closing in windows, when an add-in is being activated while the registry key  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="cb83e-914">Este cambio solucionaría el problema.</span><span class="sxs-lookup"><span data-stu-id="cb83e-914">This change would fix this issue.</span></span>

- <span data-ttu-id="cb83e-915">Se ha corregido el problema por el que Access y Publisher podrían no iniciarse correctamente en función de los idiomas que se hubieran instalado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-915">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)





[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-july-14"></a><span data-ttu-id="cb83e-918">Versión 1908: 14 de julio</span><span class="sxs-lookup"><span data-stu-id="cb83e-918">Version 1908: July 14</span></span>
<span data-ttu-id="cb83e-919">*Versión 1908 (Compilación 11929.20904)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-919">*Version 1908 (Build 11929.20904)*</span></span>

<span data-ttu-id="cb83e-920">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-920">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-922">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-922">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="cb83e-923">Access</span><span class="sxs-lookup"><span data-stu-id="cb83e-923">Access</span></span>

- <span data-ttu-id="cb83e-924">Esta actualización corrige un problema en el que la agregación como la suma puede truncar el resultado a un valor entero.</span><span class="sxs-lookup"><span data-stu-id="cb83e-924">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="cb83e-925">Esta actualización corrige un problema por el que una consulta de Unión que incluye referencias a tablas remotas (por ejemplo, tablas de SQL Server) puede hacer que Access se cierre y se reinicie.</span><span class="sxs-lookup"><span data-stu-id="cb83e-925">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="cb83e-926">Esta actualización corrige un problema en Microsoft Access que puede causar el error "La consulta está dañada" cuando se ejecuta una consulta de actualización o cuando se usa una instrucción UPDATE en SQL.</span><span class="sxs-lookup"><span data-stu-id="cb83e-926">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="cb83e-927">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-927">Excel</span></span>

- <span data-ttu-id="cb83e-928">La información clave en holandés para el título del documento ha sido cambiada a Alt-G.</span><span class="sxs-lookup"><span data-stu-id="cb83e-928">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="cb83e-929">Se ha corregido un problema en Excel en el que las macros asignadas a formas o controles de formularios podían mostrar un mensaje de error incorrecto o funcionar en intervalos de destino incorrectos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-929">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="cb83e-930">Se resolvió un problema con buscar y reemplazar ese cambio donde el foco estaba en el diálogo después de encontrar el primer elemento.</span><span class="sxs-lookup"><span data-stu-id="cb83e-930">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="cb83e-931">Esto corrige un problema por el cual al cambiar la forma en que se ordena y actualiza una tabla dinámica mientras se está en una sesión de co autoría con otros usuarios se podía provocar un bloqueo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-931">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="cb83e-932">Arreglamos un problema cuando el filtro de una tabla dinámica OLAP se estableció en un valor que se había eliminado del cubo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-932">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="cb83e-933">Esta actualización corrige un problema que provoca un error siempre que se utilizaba VBA para agregar una imagen al encabezado o pie de página de un gráfico.</span><span class="sxs-lookup"><span data-stu-id="cb83e-933">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="cb83e-934">Se ha corregido un problema que podría haber provocado que los gráficos de líneas de dispersión no se representaran correctamente al cambiar la colección de series</span><span class="sxs-lookup"><span data-stu-id="cb83e-934">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span>

- <span data-ttu-id="cb83e-935">Se han corregido los colores que se usan en las vistas previas al insertar gráficos con plantillas de gráficos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-935">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="cb83e-936">Se resolvió un problema que causó que los gráficos de cascada y embudo se desincronizara con las tablas cuando se insertaban o eliminaban celdas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-936">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="cb83e-937">Se ha corregido un problema de conflicto de fusión en Excel que hacía que los usuarios tuvieran que volver a abrir el libro de trabajo para elegir los cambios.</span><span class="sxs-lookup"><span data-stu-id="cb83e-937">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="cb83e-938">Se resolvió un problema que causaba un error de tiempo de ejecución de la macro que activaba las ventanas minimizadas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-938">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="cb83e-939">Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-939">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="cb83e-940">Se resolvió un problema que causaba que las operaciones de cortar y pegar junto a una mesa fallaran cuando se co autoría con otros.</span><span class="sxs-lookup"><span data-stu-id="cb83e-940">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="cb83e-941">Se resolvió un problema que causaba interrupciones de co autoría cuando se cambiaban las propiedades personalizadas con macros en ejecución.</span><span class="sxs-lookup"><span data-stu-id="cb83e-941">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="cb83e-942">Hubo un problema en el que no se podían seleccionar elementos del cuadro combinado de un formulario de WPF (Windows Presentation Foundation) que fue abierto por un complemento.</span><span class="sxs-lookup"><span data-stu-id="cb83e-942">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="cb83e-943">Se ha resuelto un problema que puede haber causado un bloqueo al buscar archivos recientes cuando no hay ningún libro de trabajo abierto.</span><span class="sxs-lookup"><span data-stu-id="cb83e-943">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="cb83e-944">Se ha corregido un problema que hacía que el borde de un control de cuadro de grupo no estuviera visible en la vista previa de impresión o al imprimirlo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-944">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="cb83e-945">Se ha corregido un problema por el que algunos usuarios podían haber experimentado múltiples ventanas emergentes cuando los enlaces externos estaban presentes en el libro de trabajo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-945">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="cb83e-946">Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al usar una macro de VBA para borrar el contenido de un rango.</span><span class="sxs-lookup"><span data-stu-id="cb83e-946">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="cb83e-947">Se ha corregido un problema con VBA por el que escribir valores en un rango era más lento de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-947">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="cb83e-948">Se ha corregido un problema por el que la propiedad "Valor se cruza en" en el eje del gráfico cambiaba inesperadamente al guardar y volver a abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-948">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="cb83e-949">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="cb83e-949">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="cb83e-950">Se ha corregido un problema que provocaba un rendimiento lento al eliminar columnas que contenían celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-950">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="cb83e-951">Se ha corregido un problema con la escala de texto en los controles de formulario cuando se mostraba la Vista previa de impresión.</span><span class="sxs-lookup"><span data-stu-id="cb83e-951">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="cb83e-952">Cuando se copian datos filtrados por colores en una columna con un ancho diferente, los valores no se pegan.</span><span class="sxs-lookup"><span data-stu-id="cb83e-952">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="cb83e-953">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="cb83e-953">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="cb83e-954">Se ha corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.</span><span class="sxs-lookup"><span data-stu-id="cb83e-954">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="cb83e-955">Se ha corregido un problema que provocaba que, al hacer clic en un hipervínculo marcado en el propio libro, se ocultara dicho libro.</span><span class="sxs-lookup"><span data-stu-id="cb83e-955">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="cb83e-956">Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-956">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="cb83e-957">La funcionalidad de Texto a columna puede fallar en algunas configuraciones regionales.</span><span class="sxs-lookup"><span data-stu-id="cb83e-957">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="cb83e-958">Es posible que los usuarios vean un error si acceden a un rango con nombre oculto.</span><span class="sxs-lookup"><span data-stu-id="cb83e-958">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="cb83e-959">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="cb83e-959">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="cb83e-960">Se ha corregido un problema por el que el tamaño de archivo de las imágenes en los encabezados del gráfico aumentaba cuando se guardaba el libro que contenía el gráfico.</span><span class="sxs-lookup"><span data-stu-id="cb83e-960">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>

- <span data-ttu-id="cb83e-961">Problema de rendimiento con las Funciones Asincrónicas Definidas por el Usuario que hacía que se ejecutaran sincrónicamente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-961">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="cb83e-962">Mejoras significativas en el rendimiento de la eliminación de columnas con celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-962">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="cb83e-963">Se resolvió un problema en el que la selección de una celda después del desplazamiento podía dar lugar a que se seleccionara la celda incorrecta.</span><span class="sxs-lookup"><span data-stu-id="cb83e-963">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="cb83e-964">Se ha resuelto un problema en el que la función de búsqueda puede devolver un error.</span><span class="sxs-lookup"><span data-stu-id="cb83e-964">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="cb83e-965">Se ha corregido un problema que provoca la corrupción de caracteres DBCS en los libros con referencias cruzadas manteniendo los rangos de selección sincronizados con el libro con referencias cruzadas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-965">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="cb83e-966">Se ha corregido un problema en el que los controles de casilla podían reducirse al usar el autoajuste para ajustar el alto de fila.</span><span class="sxs-lookup"><span data-stu-id="cb83e-966">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>

- <span data-ttu-id="cb83e-967">Problema de rendimiento bajo al hacer clic en el botón Color de fuente cuando un archivo tiene un formato condicional extenso.</span><span class="sxs-lookup"><span data-stu-id="cb83e-967">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="cb83e-968">Se ha corregido un problema por el que el área de impresión en la vista previa de impresión no era correcta.</span><span class="sxs-lookup"><span data-stu-id="cb83e-968">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="cb83e-969">Excel puede tener problemas al editar un archivo protegido desde una red compartida no confiable.</span><span class="sxs-lookup"><span data-stu-id="cb83e-969">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="cb83e-970">Hemos mejorado significativamente el rendimiento del filtrado por color.</span><span class="sxs-lookup"><span data-stu-id="cb83e-970">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="cb83e-971">Se ha resuelto un problema por el que los libros de trabajo creados en versiones anteriores de Office podían hacer que Excel se colgara al abrirlos en las versiones actuales de Office.</span><span class="sxs-lookup"><span data-stu-id="cb83e-971">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="cb83e-972">Se habilitaron más de 16 complementos para que se muestren al navegar en el administrador de complementos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-972">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="cb83e-973">Se ha corregido un problema que impedía que los hipervínculos se pegaran en algunas hojas protegidas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-973">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="cb83e-974">Este cambio evita un problema con ciertos controladores de gráficos Intel al aprovechar el procesamiento del software.</span><span class="sxs-lookup"><span data-stu-id="cb83e-974">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="cb83e-975">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="cb83e-975">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="cb83e-976">Esta actualización corrige un error por el cual los documentos de Office pueden fallar al subirlos a OneDrive para la Empresa con el mensaje "Error al cargar".</span><span class="sxs-lookup"><span data-stu-id="cb83e-976">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="cb83e-977">Corregir problema en la característica Ideas de Excel, error al cargar el complemento haciendo clic en el botón Ideas en el cliente Win32.</span><span class="sxs-lookup"><span data-stu-id="cb83e-977">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span> 

### <a name="onenote"></a><span data-ttu-id="cb83e-978">OneNote</span><span class="sxs-lookup"><span data-stu-id="cb83e-978">OneNote</span></span>

- <span data-ttu-id="cb83e-979">Localiza la notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="cb83e-979">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="cb83e-980">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-980">Outlook</span></span>

- <span data-ttu-id="cb83e-981">Los vínculos de cid:image de los mensajes de Outlook ahora se pueden romper correctamente cuando se solicite.</span><span class="sxs-lookup"><span data-stu-id="cb83e-981">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="cb83e-982">Se ha corregido un problema que causaba que los usuarios que actualizaban su buzón de la autenticación básica a la moderna, terminaban con una cuenta incorrecta asociada a su perfil de Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-982">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="cb83e-983">Se ha corregido un problema que hacía que los complementos web accedieran a los mensajes de la administración de derechos digitales cuando no deberían hacerlo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-983">Addresses an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="cb83e-984">Se ha corregido un problema que causó que las URLS de enlace simple no se mostraran en algunos enlaces seguros.</span><span class="sxs-lookup"><span data-stu-id="cb83e-984">Addresses an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="cb83e-985">Esto actualiza la lógica de bloqueo de adjuntos en Outlook para bloquear también los adjuntos de Python.</span><span class="sxs-lookup"><span data-stu-id="cb83e-985">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="cb83e-986">Corrige un problema que causaba que un subconjunto de usuarios de POP3 viesen todos los correos electrónicos como texto sin formato, independientemente de la configuración.</span><span class="sxs-lookup"><span data-stu-id="cb83e-986">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="cb83e-987">Esta corrección restaurará la vista de los mensajes con formato HTML.</span><span class="sxs-lookup"><span data-stu-id="cb83e-987">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="cb83e-988">Se ha corregido un problema que hacía que los usuarios experimentaran un error de permiso al copiar elementos de su calendario principal a un calendario de grupo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-988">Addresses an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="cb83e-989">Se ha corregido un problema que hacía que los usuarios no pudieran acceder a las sugerencias de ubicación a través de un lector de pantalla.</span><span class="sxs-lookup"><span data-stu-id="cb83e-989">Addresses an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="cb83e-990">Se ha corregido un problema por el que los usuarios notaban un retraso evidente al interactuar con sus carpetas de buzón mediante métodos abreviados de teclado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-990">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="cb83e-991">Se ha corregido un problema que causaba una pérdida de memoria en sesiones de Outlook muy largas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-991">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="cb83e-992">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.</span><span class="sxs-lookup"><span data-stu-id="cb83e-992">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="cb83e-993">Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al abrir el cuadro de diálogo de Reglas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-993">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="cb83e-994">Se ha corregido un problema que haría que los usuarios experimentaran un bloqueo en Outlook al interactuar con ciertos vínculos seguros.</span><span class="sxs-lookup"><span data-stu-id="cb83e-994">Addresses an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="cb83e-995">Se ha corregido un problema que causaba ambigüedad para los administradores sobre si un delegado ya había respondido a una convocatoria de reunión determinada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-995">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="cb83e-996">Se ha corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.</span><span class="sxs-lookup"><span data-stu-id="cb83e-996">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="cb83e-997">Se ha corregido un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "OK" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="cb83e-997">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="cb83e-998">Este cambio permite a los administradores habilitar una política para preferir el correo electrónico de la cuenta proporcionada en los avisos de autorización de AutoDiscover sobre el UPN.</span><span class="sxs-lookup"><span data-stu-id="cb83e-998">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="cb83e-999">De forma predeterminada, detección automática prefiere el UPN de la cuenta, cuando está disponible.</span><span class="sxs-lookup"><span data-stu-id="cb83e-999">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="cb83e-1000">Se ha corregido un problema que provocaba que los usuarios vieran un error en la búsqueda con grupos modernos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1000">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="cb83e-1001">Se ha corregido un problema que causaba que los usuarios de Outlook se quedaran atascados en el estado "Necesita contraseña" en ciertos escenarios.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1001">Addresses an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="cb83e-1002">Se ha corregido un problema que provocaba que los usuarios experimentaran errores de sincronización al procesar mensajes de conflicto.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1002">Addresses an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="cb83e-1003">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al abrir archivos .msg y .oft después de aplicar una actualización reciente de Windows.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1003">Addresses an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="cb83e-1004">Se ha corregido un problema que provocaba que los usuarios experimentaran un error en la pantalla de "carga del perfil" al iniciar Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1004">Addresses an issue that caused users to experience a hang at the "Loading Profile" screen when Outlook is starting up.</span></span>

- <span data-ttu-id="cb83e-1005">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al seleccionar determinados resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1005">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="cb83e-1006">Se ha corregido un problema que hizo que el botón "Guardar en la nube" faltara en las herramientas de datos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1006">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="cb83e-1007">De forma predeterminada, las etiquetas de directivas de retención muestran el período de tiempo de retención entre paréntesis.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1007">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="cb83e-1008">Esto proporciona una clave del registro para permitir que los administradores especifiquen que solo se debería mostrar el nombre de la directiva.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1008">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="cb83e-1009">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = predeterminado 1 = solo se mostrará el PolicyName para el texto de la política de retención.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1009">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

- <span data-ttu-id="cb83e-1010">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al cerrar Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1010">Addresses an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="cb83e-1011">Se ha corregido un problema que provocaba que los clientes vieran una lista de salas vacías en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1011">Addresses an issue that caused customers to see an empty room list in some scenarios.</span></span>

- <span data-ttu-id="cb83e-1012">Se ha corregido un problema que provocaba que los usuarios viesen bloqueos intermitentes al cambiar de vista.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1012">Addresses an issue that caused users to see intermittent crashes when changing views.</span></span>

- <span data-ttu-id="cb83e-1013">Corrige un problema que provocaba que los usuarios tuvieran problemas al intentar sincronizar carpetas del calendario compartido con el OST, lo que producía errores en los permisos al tratar de interactuar con estas carpetas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1013">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>

- <span data-ttu-id="cb83e-1014">Se ha corregido un problema que causaba que los usuarios sufrieran un error al visualizar más de 30 calendarios en un entorno Citrix.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1014">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="cb83e-1015">Aquí está el [KB individual, donde se ha documentado esto para versiones anteriores](https://support.microsoft.com/es-ES/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span><span class="sxs-lookup"><span data-stu-id="cb83e-1015">Here's the individual [KB where this was documented for previous versions](https://support.microsoft.com/es-ES/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span></span>

- <span data-ttu-id="cb83e-1016">Corrige un problema con la selección de algoritmos SMIME.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1016">Corrects an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="cb83e-1017">Se ha corregido un problema que provocó que las sugerencias de la política no se mostraran al utilizar un remitente alternativo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1017">Addresses an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="cb83e-1018">Se ha corregido un problema que hizo que los usuarios vieran sugerencias de salas para reuniones que se produjeron fuera de las horas de disponibilidad de dichas salas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1018">Addresses an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="cb83e-1019">Se ha corregido un problema para los usuarios que no hablan inglés, en el que la línea de asunto de un correo electrónico era increíblemente pequeña.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1019">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="cb83e-1020">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al intentar crear una regla a partir de un mensaje de "Conversación perdida".</span><span class="sxs-lookup"><span data-stu-id="cb83e-1020">Addresses an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="cb83e-1021">Se ha corregido un problema que causaba que algunos usuarios vieran carpetas especiales duplicadas al agregar una cuenta de Exchange secundaria.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1021">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="cb83e-1022">Se ha corregido un problema que hacía que los usuarios vieran el truncamiento del cuerpo del mensaje al reenviar mensajes HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1022">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="cb83e-1023">Se ha corregido un problema que hacía que los usuarios observaran una pérdida de memoria en el proceso de Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1023">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="cb83e-1024">Se ha corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1024">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="cb83e-1025">Se ha corregido un problema que provocaba un error ocasional en la búsqueda de la carpeta actual.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1025">Addresses an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="cb83e-1026">Se ha corregido un problema que hizo que algunos usuarios encontraran errores de autenticación al intentar recuperar su configuración de nube para Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1026">Addresses an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="cb83e-1027">Se ha corregido un problema que causó un bloqueo en la experiencia de los comentarios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1027">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="cb83e-1028">Se ha corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1028">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="cb83e-1029">Se ha corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1029">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="cb83e-1030">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb83e-1030">PowerPoint</span></span>

- <span data-ttu-id="cb83e-1031">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="cb83e-1031">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="cb83e-1032">Este cambio restaura el nombre accesible de los controles de vídeo de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1032">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="cb83e-1033">Se ha corregido un problema que podría impedir que comiencen algunas animaciones</span><span class="sxs-lookup"><span data-stu-id="cb83e-1033">We fixed an issue which could prevent some animations from starting</span></span>

- <span data-ttu-id="cb83e-1034">Se ha corregido un problema en el que al copiar una diapositiva de una presentación a otra, se pueden crear patrones duplicados.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1034">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span><br>

- <span data-ttu-id="cb83e-1035">Se ha mejorado un escenario de copiar y pegar: al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1035">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="cb83e-1036">Se ha corregido un problema con el marcador de resaltado: los textos blancos con un marcador oscuro se imprimen como negros en escala de grises.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1036">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

- <span data-ttu-id="cb83e-1037">Los archivos con nuevos comentarios modernos mostrarán una advertencia amarilla si se abren en una versión no soportada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1037">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

- <span data-ttu-id="cb83e-1038">Se ha corregido un problema que producía un rendimiento más lento entre los usuarios de colaboración.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1038">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="cb83e-1039">Corrección de confiabilidad: se ha corregido un problema por el que el complemento de terceros podía bloquearse en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1039">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="cb83e-1040">Se ha corregido un problema que puede producirse cuando un archivo que se abre incrementalmente contiene una diapositiva con más de una secuencia multimedia incrustada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1040">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="cb83e-1041">Se ha corregido un problema con el método Shape.Paste: cuando el usuario copiaba y pegaba la forma con el método Shape.Paste, se cambiaba la selección a la forma pegada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1041">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="cb83e-1042">Se ha corregido un problema por el que es posible que la barra de mensajes de advertencia de seguridad no aparezca para los complementos en los que no se confía al iniciar PowerPoint por primera vez.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1042">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

- <span data-ttu-id="cb83e-1043">Se ha corregido un problema por el que algunos complementos producían errores inesperados alrededor de las formas en gráficos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1043">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="cb83e-1044">Evita que los usuarios de PowerPoint se encuentren con un error cuando intentan hacer una presentación en línea.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1044">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

### <a name="project"></a><span data-ttu-id="cb83e-1045">Project</span><span class="sxs-lookup"><span data-stu-id="cb83e-1045">Project</span></span>

- <span data-ttu-id="cb83e-1046">Se ha corregido un problema para permitir que los usuarios en Windows 7 puedan abrir proyectos desde Project Web App y sitios de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1046">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="cb83e-1047">Se identificó un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de sólo lectura.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1047">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="cb83e-1048">El comando Level All no resuelve adecuadamente una sobreasignación de recursos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1048">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="cb83e-1049">Si tiene una tarea sin nada de trabajo, es posible que la tarea no se pueda marcar como completada y siempre se mostrará en el 99 %.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1049">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

- <span data-ttu-id="cb83e-1050">Se ha corregido un problema en el que el trabajo real puede ser diferente entre el parte de horas y el plan del proyecto debido a que los calendarios de recursos no se actualizan cuando cambia el calendario base.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1050">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="skype"></a><span data-ttu-id="cb83e-1051">Skype</span><span class="sxs-lookup"><span data-stu-id="cb83e-1051">Skype</span></span>

- <span data-ttu-id="cb83e-1052">Se ha corregido el nombre del título de la conversación con pestañas mientras se mantenía más de una conversación.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1052">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="visio"></a><span data-ttu-id="cb83e-1053">Visio</span><span class="sxs-lookup"><span data-stu-id="cb83e-1053">Visio</span></span>

- <span data-ttu-id="cb83e-1054">La exportación como SVG de Visio estaba fallando por una variedad de formas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1054">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="cb83e-1055">Word</span><span class="sxs-lookup"><span data-stu-id="cb83e-1055">Word</span></span>

- <span data-ttu-id="cb83e-1056">Los vínculos de cid:image de los mensajes de Outlook ahora se pueden romper correctamente cuando se solicite.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1056">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="cb83e-1057">Se ha corregido un problema que podría haber provocado problemas de escala al imprimir en impresoras Deskjet</span><span class="sxs-lookup"><span data-stu-id="cb83e-1057">We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span>

- <span data-ttu-id="cb83e-1058">Se ha corregido un problema al Ajustar texto en la tabla.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1058">We fixed an issue in Fit Text in Table.</span></span>

- <span data-ttu-id="cb83e-1059">Hemos corregido un problema en los cambios de pista que a veces van en un bucle infinito.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1059">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="cb83e-1060">Corregido un problema ocasional en el que al guardar un archivo existente siempre aparece el cuadro de diálogo Guardar como, pero el archivo nunca se guarda.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1060">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="cb83e-1061">Se ha corregido un problema al combinar dos documentos en uno.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1061">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="cb83e-1062">Se ha corregido un problema con la característica Comparación para los documentos protegidos para la edición.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1062">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="cb83e-1063">Se han corregido varios problemas que hacían que la aplicación se colgara al apagarse.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1063">Fixes various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="cb83e-1064">También se corrigieron ciertos fallos relacionados con los complementos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1064">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="cb83e-1065">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-1065">Office Suite</span></span>

- <span data-ttu-id="cb83e-1066">Corregido el problema de la identificación incorrecta del nombre de la nueva era "Reiwa" en hiragana y kanji como una expresión mal escrita o poco gramatical.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1066">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="cb83e-1067">Corregido un problema que hacía que los usuarios recibieran el mensaje "Lo sentimos, algo nos impide compartir esto" al intentar compartir archivos almacenados en SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1067">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="cb83e-1068">Se ha solucionado un problema que podía causar la pérdida de datos en sesiones que implicaban tanto la co autoría como la edición fuera de línea en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1068">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="cb83e-1069">Esta es una solución para un fallo que los usuarios podrían sufrir al abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1069">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="cb83e-1070">En algunos casos, un archivo de sharepoint respaldado por un motor de sincronización podría mostrar "Guardado" pero no haber guardado realmente ningún cambio, lo que provocaría la pérdida de datos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1070">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="cb83e-1071">Se resolvió un problema que impedía a los usuarios guardar documentos de Word, Excel y PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1071">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="cb83e-1072">Este problema afecta a los usuarios que crean un nuevo archivo y muestra la opción "Guardar como diálogo" después de hacer clic en el icono Guardar o presionar Ctrl + S.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1072">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="cb83e-1073">Se ha corregido un bloqueo en Word al dejar una API obsoleta.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1073">Fixes a crash in Word by moving away from a deprecated API.</span></span>

- <span data-ttu-id="cb83e-1074">Se ha corregido un problema por el que los caracteres katakana de medio ancho no giraban correctamente cuando estaban en cuadros de texto verticales en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1074">Fixing an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="cb83e-1075">Se ha corregido un problema de perf en Win7 en el que la galería de formas de inserción de la cinta en todas las aplicaciones tardaba aproximadamente 4 segundos en aparecer.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1075">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="cb83e-1076">Corregido un error por el que la información de accesibilidad no se mostraba en la losa del lugar de información de los bastidores.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1076">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="cb83e-1077">Mejora de la fiabilidad del proceso de actualización de Office en lo que respecta a la integridad del registro.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1077">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="cb83e-1078">Hemos actualizado los nombres de canal para las bifurcaciones de enero y julio de 2019 con los nuevos nombres de canal.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1078">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="cb83e-1079">Se ha corregido un problema por el que las actualizaciones se bloqueaban inesperadamente en las redes de uso medido.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1079">Corrects an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="cb83e-1080">Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1080">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="cb83e-1081">En determinadas circunstancias, los accesos directos de Office pueden desaparecer tras una actualización.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1081">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="cb83e-1082">Esta actualización mejora la fiabilidad en la publicación de los accesos directos de Office.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1082">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="cb83e-1083">Corrige un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1083">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="cb83e-1084">Se ha corregido un problema en el que una actualización no se aplicaría en ciertos casos en los que el usuario no es un administrador y la cuenta del sistema no tenía conectividad de red.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1084">Resolves an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="cb83e-1085">Se ha solucionado un problema por el que los mensajes de actualización de Office aparecían en un idioma diferente al esperado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1085">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="cb83e-1086">En el futuro, los mensajes de actualización de Office coincidirán correctamente con el idioma de visualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1086">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="cb83e-1087">Se ha mejorado la confiabilidad al descargar las actualizaciones de Office al reanudar las descargas que pueden haberse interrumpido anteriormente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1087">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="cb83e-1088">Se han corregido los problemas relacionados con la propiedad Textbox/Shape Autofit en los plug-ins de terceros.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1088">Address issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="cb83e-1089">Este cambio corrige el procesamiento de imágenes después de abrir un archivo dañado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1089">This change addresses correctly rendering images after opening a corrupted file.</span></span>

- <span data-ttu-id="cb83e-1090">Este cambio corrige el procesamiento lento de algunos gráficos de dispersión con marcadores.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1090">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="cb83e-1091">Se ha corregido un problema por el que las vistas de árboles grandes podían dar lugar a un bloqueo</span><span class="sxs-lookup"><span data-stu-id="cb83e-1091">We fixed an issue where large tree views could result in a crash</span></span>

- <span data-ttu-id="cb83e-1092">Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1092">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="cb83e-1093">Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1093">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="cb83e-1094">Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1094">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-july-14"></a><span data-ttu-id="cb83e-1096">Versión 1902: 14 de julio</span><span class="sxs-lookup"><span data-stu-id="cb83e-1096">Version 1902: July 14</span></span>
<span data-ttu-id="cb83e-1097">*Versión 1902 (compilación 11328.20624)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-1097">*Version 1902 (Build 11328.20624)*</span></span>

<span data-ttu-id="cb83e-1098">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-1098">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1908-june-09"></a><span data-ttu-id="cb83e-1099">Versión 1908: 09 de junio</span><span class="sxs-lookup"><span data-stu-id="cb83e-1099">Version 1908: June 09</span></span>
<span data-ttu-id="cb83e-1100">*Versión 1908 (compilación 11929.20838)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-1100">*Version 1908 (Build 11929.20838)*</span></span>

<span data-ttu-id="cb83e-1101">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-1101">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-1103">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-1103">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb83e-1104">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-1104">Excel</span></span>

- <span data-ttu-id="cb83e-1105">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1105">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="cb83e-1106">Se ha corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1106">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="cb83e-1107">Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1107">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="cb83e-1108">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-1108">Outlook</span></span>

- <span data-ttu-id="cb83e-1109">Se ha corregido un problema que hacía que los usuarios vieran truncado el cuerpo del mensaje al reenviar mensajes HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1109">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

### <a name="office-suite"></a><span data-ttu-id="cb83e-1110">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-1110">Office Suite</span></span>

- <span data-ttu-id="cb83e-1111">Hemos actualizado los nombres de canal para las bifurcaciones de enero y julio de 2019 con los nuevos nombres de canal.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1111">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>


[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-june-09"></a><span data-ttu-id="cb83e-1113">Versión 1902: 09 de junio</span><span class="sxs-lookup"><span data-stu-id="cb83e-1113">Version 1902: June 09</span></span>
<span data-ttu-id="cb83e-1114">*Versión 1902 (compilación 11328.20602)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-1114">*Version 1902 (Build 11328.20602)*</span></span>

<span data-ttu-id="cb83e-1115">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-1115">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-1117">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-1117">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="cb83e-1118">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-1118">Office Suite</span></span>

- <span data-ttu-id="cb83e-1119">Hemos actualizado los nombres de canal para las bifurcaciones de enero y julio de 2019 con los nuevos nombres de canal.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1119">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="cb83e-1120">Se han eliminado las referencias obsoletas de los archivos de línea base que producian errores en la compilación C2R.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1120">We removed obsolete references from the baseline files that were breaking the C2R Build.</span></span>



[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-may-12"></a><span data-ttu-id="cb83e-1122">Versión 1908: 12 de mayo</span><span class="sxs-lookup"><span data-stu-id="cb83e-1122">Version 1908: May 12</span></span>
<span data-ttu-id="cb83e-1123">*Versión 1908 (compilación 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-1123">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="cb83e-1124">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-1124">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-1126">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-1126">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb83e-1127">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-1127">Excel</span></span>

- <span data-ttu-id="cb83e-1128">Cuando se copian datos filtrados por colores en una columna con un ancho diferente, los valores no se pegan.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1128">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

### <a name="outlook"></a><span data-ttu-id="cb83e-1129">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-1129">Outlook</span></span>

- <span data-ttu-id="cb83e-1130">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al abrir archivos .msg y .oft después de aplicar una actualización reciente de Windows.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1130">Addressed an issue that caused users to experience a crash when opening msg and .oft files after applying a recent Windows update.</span></span>

### <a name="word"></a><span data-ttu-id="cb83e-1131">Word</span><span class="sxs-lookup"><span data-stu-id="cb83e-1131">Word</span></span>

- <span data-ttu-id="cb83e-1132">Se ha corregido un problema al combinar 2 documentos en uno.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1132">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="cb83e-1133">Se ha corregido un problema con la característica Comparar de los documentos protegidos para la edición.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1133">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-1902-may-12"></a><span data-ttu-id="cb83e-1135">Versión 1902:12 de mayo</span><span class="sxs-lookup"><span data-stu-id="cb83e-1135">Version 1902: May 12</span></span>
<span data-ttu-id="cb83e-1136">*Versión 1902 (compilación 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-1136">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="cb83e-1137">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-1137">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-1139">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-1139">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="cb83e-1140">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-1140">Outlook</span></span>

- <span data-ttu-id="cb83e-1141">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al abrir archivos .msg y .oft después de aplicar una actualización reciente de Windows.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1141">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="cb83e-1142">De forma predeterminada, las etiquetas de directivas de retención muestran el período de tiempo de retención entre paréntesis.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1142">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="cb83e-1143">Esto proporciona una clave del registro para permitir que los administradores especifiquen que solo se debería mostrar el nombre de la directiva.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1143">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="cb83e-1144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="cb83e-1145">0 = predeterminado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1145">0 = Default.</span></span>  <span data-ttu-id="cb83e-1146">1 = solo se mostrará el nombre de directiva del texto de la directiva de retención.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1146">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-1908-may-04"></a><span data-ttu-id="cb83e-1148">Versión 1908: 4 de mayo</span><span class="sxs-lookup"><span data-stu-id="cb83e-1148">Version 1908: May 04</span></span>
<span data-ttu-id="cb83e-1149">*Versión 1908 (Compilación 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-1149">*Version 1908 (Build 11929.20752)*</span></span>

<span data-ttu-id="cb83e-1150">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-1150">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-1151">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-1151">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="cb83e-1152">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-1152">Outlook</span></span>

- <span data-ttu-id="cb83e-1153">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al seleccionar determinados resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1153">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="cb83e-1154">Se ha corregido un problema que hacía que el botón "Guardar en la nube" faltara en las Herramientas de datos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1154">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="cb83e-1155">De forma predeterminada, las etiquetas de directivas de retención muestran el período de tiempo de retención entre paréntesis.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1155">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="cb83e-1156">Esto proporciona una clave del registro para permitir que los administradores especifiquen que solo se debería mostrar el nombre de la directiva.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1156">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="cb83e-1157">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1157">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="cb83e-1158">0 = predeterminado 1 = solo se mostrará el nombre de directiva del texto de la directiva de retención.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1158">0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="office-suite"></a><span data-ttu-id="cb83e-1159">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-1159">Office Suite</span></span>

- <span data-ttu-id="cb83e-1160">Se ha corregido un problema en Visual Basic para las aplicaciones de Microsoft Office, por el que la aplicación de Office consideraba como corruptos ciertos proyectos de VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre o la ruta de la biblioteca.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1160">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="cb83e-1161">Versión 1902: 4 de mayo</span><span class="sxs-lookup"><span data-stu-id="cb83e-1161">Version 1902: May 04</span></span>
<span data-ttu-id="cb83e-1162">*Versión 1902 (compilación 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-1162">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-1163">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-1163">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="cb83e-1164">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-1164">Office Suite</span></span>

- <span data-ttu-id="cb83e-1165">Se ha corregido un problema en Visual Basic para las aplicaciones de Microsoft Office, por el que la aplicación de Office consideraba como corruptos ciertos proyectos de VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre o la ruta de la biblioteca.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1165">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1908-april-26"></a><span data-ttu-id="cb83e-1166">Versión 1908: 26 de abril</span><span class="sxs-lookup"><span data-stu-id="cb83e-1166">Version 1908: April 26</span></span>
<span data-ttu-id="cb83e-1167">*Versión 1908 (Compilación 11929.20736)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-1167">*Version 1908 (Build 11929.20736)*</span></span>

<span data-ttu-id="cb83e-1168">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-1168">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-1169">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-1169">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb83e-1170">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-1170">Excel</span></span>

- <span data-ttu-id="cb83e-1171">Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al usar una macro de VBA para borrar el contenido de un rango.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1171">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="cb83e-1172">Se ha corregido un problema con VBA por el que escribir valores en un rango era más lento de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1172">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="cb83e-1173">Se ha corregido un problema por el que la propiedad "Value Crosses At" en el eje del gráfico cambiaba inesperadamente al guardar y volver a abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1173">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="cb83e-1174">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1174">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


### <a name="onenote"></a><span data-ttu-id="cb83e-1175">OneNote</span><span class="sxs-lookup"><span data-stu-id="cb83e-1175">OneNote</span></span>

- <span data-ttu-id="cb83e-1176">Localiza la notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1176">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>


## <a name="version-1908-april-14"></a><span data-ttu-id="cb83e-1177">Versión 1908: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="cb83e-1177">Version 1908: April 14</span></span>
<span data-ttu-id="cb83e-1178">*Versión 1908 (compilación 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-1178">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="cb83e-1179">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-1179">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-1181">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-1181">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb83e-1182">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-1182">Excel</span></span>

- <span data-ttu-id="cb83e-1183">Se ha corregido un problema que provocaba un rendimiento lento al eliminar columnas que contenían celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1183">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="cb83e-1184">Se ha corregido un problema con la escala de texto en los controles de formulario cuando se mostraba la Vista previa de impresión.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1184">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="cb83e-1185">Skype</span><span class="sxs-lookup"><span data-stu-id="cb83e-1185">Skype</span></span>

- <span data-ttu-id="cb83e-1186">Se ha corregido el nombre del título de la conversación con pestañas mientras se mantenía más de una conversación.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1186">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="cb83e-1187">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-1187">Outlook</span></span>

- <span data-ttu-id="cb83e-1188">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al cerrar Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1188">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="cb83e-1189">Se ha corregido un problema que provocaba que los clientes vieran una lista de salas vacías en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1189">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="cb83e-1190">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb83e-1190">PowerPoint</span></span>

- <span data-ttu-id="cb83e-1191">Se ha corregido un problema con el marcador de resaltado: los textos blancos con un marcador oscuro se imprimen como negros en escala de grises.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1191">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="cb83e-1192">Word</span><span class="sxs-lookup"><span data-stu-id="cb83e-1192">Word</span></span>

- <span data-ttu-id="cb83e-1193">Se ha corregido un problema al Ajustar texto en la tabla.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1193">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="cb83e-1194">Versión 1902: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="cb83e-1194">Version 1902: April 14</span></span>
<span data-ttu-id="cb83e-1195">*Versión 1902 (compilación 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-1195">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="cb83e-1196">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-1196">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-march-10"></a><span data-ttu-id="cb83e-1198">Versión 1908: 10 de marzo</span><span class="sxs-lookup"><span data-stu-id="cb83e-1198">Version 1908: March 10</span></span>
<span data-ttu-id="cb83e-1199">*Versión 1908 (compilación 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-1199">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="cb83e-1200">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-1200">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-1202">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-1202">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb83e-1203">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-1203">Excel</span></span>

- <span data-ttu-id="cb83e-1204">Se ha corregido un problema por el que algunos usuarios podían haber experimentado múltiples ventanas emergentes cuando los enlaces externos estaban presentes en el libro de trabajo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1204">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="cb83e-1205">La funcionalidad de Texto a columna puede fallar en algunas configuraciones regionales.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1205">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="cb83e-1206">Los usuarios pueden encontrar un error al acceder a un rango con nombre oculto.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1206">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="cb83e-1207">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb83e-1207">PowerPoint</span></span>

- <span data-ttu-id="cb83e-1208">Se ha corregido un problema con el método Shape.Paste: cuando el usuario copiaba y pegaba la forma con el método Shape.Paste, se cambiaba la selección a la forma pegada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1208">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="cb83e-1209">Word</span><span class="sxs-lookup"><span data-stu-id="cb83e-1209">Word</span></span>

- <span data-ttu-id="cb83e-1210">Corregido un problema ocasional en el que al guardar un archivo existente siempre aparece el cuadro de diálogo Guardar como, pero el archivo nunca se guarda.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1210">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="cb83e-1211">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-1211">Office Suite</span></span>

- <span data-ttu-id="cb83e-1212">Este cambio corrige el procesamiento lento de algunos gráficos de dispersión con marcadores.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1212">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="cb83e-1213">Versión 1902: 10 de marzo</span><span class="sxs-lookup"><span data-stu-id="cb83e-1213">Version 1902: March 10</span></span>
<span data-ttu-id="cb83e-1214">*Versión 1902 (compilación 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-1214">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="cb83e-1215">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-1215">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-february-11"></a><span data-ttu-id="cb83e-1217">Versión 1908: 11 de febrero</span><span class="sxs-lookup"><span data-stu-id="cb83e-1217">Version 1908: February 11</span></span>
<span data-ttu-id="cb83e-1218">*Versión 1908 (Compilación 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-1218">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="cb83e-1219">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-1219">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-1221">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-1221">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb83e-1222">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-1222">Excel</span></span>

- <span data-ttu-id="cb83e-1223">Esta actualización corrige un problema que provoca un error siempre que se utilizaba VBA para agregar una imagen al encabezado o pie de página de un gráfico.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1223">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="cb83e-1224">Se ha corregido un problema que hacía que el borde de un control de cuadro de grupo no estuviera visible en la vista previa de impresión o al imprimirlo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1224">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="cb83e-1225">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1225">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="cb83e-1226">Se ha corregido un problema por el que el tamaño de archivo de las imágenes en los encabezados del gráfico aumentaba cuando se guardaba el libro que contenía el gráfico.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1226">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="cb83e-1227">Se ha corregido un problema que provoca la corrupción de caracteres DBCS en los libros con referencias cruzadas manteniendo los rangos de selección sincronizados con el libro con referencias cruzadas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1227">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="cb83e-1228">Se ha corregido un problema en el que los controles de casilla podían reducirse al usar el autoajuste para ajustar el alto de fila.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1228">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="cb83e-1229">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-1229">Outlook</span></span>

- <span data-ttu-id="cb83e-1230">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1230">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="cb83e-1231">Se ha corregido un problema que provocaba que los usuarios experimentaran errores de sincronización al procesar mensajes de conflicto.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1231">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="cb83e-1232">Se ha corregido un problema que provocaba que los usuarios experimentaran un error en la pantalla de carga del perfil al iniciar Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1232">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="cb83e-1233">Se ha corregido un problema que provocaba que los usuarios viesen bloqueos intermitentes al cambiar de vista.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1233">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="cb83e-1234">Se ha corregido un problema que causaba que los usuarios sufrieran un error al visualizar más de 30 calendarios en un entorno Citrix.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1234">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="cb83e-1235">[Aquí](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) está la KB individual, donde se ha documentado esto para versiones anteriores.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1235">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="cb83e-1236">Corrige un problema que provocaba que los usuarios tuvieran problemas al intentar sincronizar carpetas del calendario compartido con el OST, lo que producía errores en los permisos al tratar de interactuar con estas carpetas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1236">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="cb83e-1237">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb83e-1237">PowerPoint</span></span>

- <span data-ttu-id="cb83e-1238">Se ha mejorado un escenario de copiar y pegar. Al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1238">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="cb83e-1239">Se ha corregido un problema que producía un rendimiento más lento entre los usuarios de colaboración.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1239">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="cb83e-1240">Se ha corregido un problema que puede producirse cuando un archivo que se abre incrementalmente contiene una diapositiva con más de una secuencia multimedia incrustada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1240">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="cb83e-1241">Se ha corregido un problema por el que es posible que la barra de mensajes de advertencia de seguridad no aparezca para los complementos en los que no se confía al iniciar PowerPoint por primera vez.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1241">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="cb83e-1242">Project</span><span class="sxs-lookup"><span data-stu-id="cb83e-1242">Project</span></span>

- <span data-ttu-id="cb83e-1243">Se ha corregido un problema en el que el trabajo real puede ser diferente entre el parte de horas y el plan del proyecto debido a que los calendarios de recursos no se actualizan cuando cambia el calendario base.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1243">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="cb83e-1244">Word</span><span class="sxs-lookup"><span data-stu-id="cb83e-1244">Word</span></span>

- <span data-ttu-id="cb83e-1245">Se ha corregido un bloqueo en Word al dejar una API obsoleta.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1245">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="cb83e-1246">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-1246">Office Suite</span></span>

- <span data-ttu-id="cb83e-1247">Este cambio corrige el procesamiento de imágenes después de abrir un archivo dañado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1247">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-february-11"></a><span data-ttu-id="cb83e-1249">Versión 1902: 11 de febrero</span><span class="sxs-lookup"><span data-stu-id="cb83e-1249">Version 1902: February 11</span></span>
<span data-ttu-id="cb83e-1250">*Versión 1902 (Compilación 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-1250">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="cb83e-1251">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-1251">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-1253">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-1253">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="cb83e-1254">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-1254">Outlook</span></span>

- <span data-ttu-id="cb83e-1255">Corregido un problema que hizo que los usuarios encontraran errores de "algoritmo de cifrado no admitido" al enviar un correo electrónico cifrado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1255">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="cb83e-1256">Word</span><span class="sxs-lookup"><span data-stu-id="cb83e-1256">Word</span></span>

- <span data-ttu-id="cb83e-1257">Se ha corregido un bloqueo en Word al dejar una API obsoleta.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1257">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO INICIO)

## <a name="version-1808-february-11"></a><span data-ttu-id="cb83e-1260">Versión 1808: 11 de febrero</span><span class="sxs-lookup"><span data-stu-id="cb83e-1260">Version 1808: February 11</span></span>
<span data-ttu-id="cb83e-1261">*Versión 1808 (compilación 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-1261">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="cb83e-1262">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-1262">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-january-14"></a><span data-ttu-id="cb83e-1264">Versión 1908: 14 de enero</span><span class="sxs-lookup"><span data-stu-id="cb83e-1264">Version 1908: January 14</span></span>
<span data-ttu-id="cb83e-1265">*Versión 1908 (compilación 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-1265">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="cb83e-1266">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-1266">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="cb83e-1268">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="cb83e-1268">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="cb83e-1269">Access</span><span class="sxs-lookup"><span data-stu-id="cb83e-1269">Access</span></span>

- <span data-ttu-id="cb83e-1270">**Mantener un seguimiento de los objetos de base de datos:** ver claramente la pestaña activa, arrastrar las pestañas para reorganizarlas fácilmente y cerrar los objetos de base de datos con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1270">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="cb83e-1271">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1271">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="cb83e-1272">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1272">Switching between them has never been easier.</span></span> [<span data-ttu-id="cb83e-1273">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1273">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="cb83e-1274">**Zoom con más espacio:** agrandar el cuadro de Zoom, cambiar la fuente y hacer que Zoom lo recuerde todo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1274">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="cb83e-1275">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1275">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="cb83e-1276">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-1276">Excel</span></span>

- <span data-ttu-id="cb83e-1277">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1277">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="cb83e-1278">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1278">Switching between them has never been easier.</span></span> [<span data-ttu-id="cb83e-1279">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1279">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="cb83e-1280">**Aumentar el alcance de su contenido:** ¿necesita que las presentaciones sean accesibles?</span><span class="sxs-lookup"><span data-stu-id="cb83e-1280">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="cb83e-1281">Deje que el comprobador de accesibilidad le ayude sin estorbar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1281">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="cb83e-1282">Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1282">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="cb83e-1283">**Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente?</span><span class="sxs-lookup"><span data-stu-id="cb83e-1283">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="cb83e-1284">Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1284">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="cb83e-1285">**Vea cómo la hoja de cálculo cobra vida**: inserte gráficos 3D animados para ver corazones que laten, planetas en órbita y dinosaurios a toda velocidad por el libro.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1285">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="cb83e-1286">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1286">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="cb83e-p211">**Obtener más información sobre los datos:** el nuevo botón Ideas busca patrones en los datos y los usa para crear sugerencias inteligentes y personalizadas. [Más información](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="cb83e-p211">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="cb83e-1289">**La colaboración es ahora más fácil**: las mejoras en la coautoría significan que al trabajar con el formato condicional, los estilos de celda y otros elementos, los cambios se combinan perfectamente con los de los colaboradores.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1289">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="cb83e-1290">**Unir tablas en columnas similares:** obtener y transformar (Power Query) ahora ofrece una lógica de coincidencia de texto (también denominada coincidencia aproximada) al comparar columnas en la combinación de tablas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1290">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="cb83e-1291">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1291">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="cb83e-1292">**Programar rápidamente con mejoras de Power Query:** termine rápidamente el código con colores de sintaxis y la función de autocompletar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1292">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="cb83e-1293">Además, descubra fácilmente funciones, columnas y parámetros.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1293">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="cb83e-1294">**Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1294">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="cb83e-1295">Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1295">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="cb83e-1296">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1296">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="cb83e-1297">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-1297">Outlook</span></span>

- <span data-ttu-id="cb83e-1298">**Hemos actualizado la experiencia de usuario de Outlook para usted:** una experiencia simplificada, anteriormente disponible para su vista previa con Próximamente, diseñada para ayudarle a centrarse en lo más importante.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1298">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="cb83e-1299">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1299">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="cb83e-1300">**Una cinta simplificada que además es personalizable:** disfrute de una sola fila simplificada con los botones más usados.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1300">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="cb83e-1301">Cambie fácilmente entre la vista clásica y la simplificada, y ancle o desancle comandos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1301">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="cb83e-1302">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1302">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="cb83e-1303">**Seguir trabajando mientras mueve mensajes:** Outlook ahora mueve los mensajes en segundo plano, por lo que puede seguir trabajando mientras mueve una gran cantidad de mensajes entre carpetas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1303">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="cb83e-1304">**Creación en el tiempo entre las reuniones consecutivas:** asigne a los asistentes el tiempo para descansar o desplazarse entre las distintas ubicaciones al configurar reuniones para finalizar 5 a 10 minutos antes de forma predeterminada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1304">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="cb83e-1305">**Seleccione su acción favorita:** ¿no usa Etiquetar ni Eliminar?</span><span class="sxs-lookup"><span data-stu-id="cb83e-1305">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="cb83e-1306">¿Qué hay de Archivar o Marcar como leído?</span><span class="sxs-lookup"><span data-stu-id="cb83e-1306">How about Archive or Mark as Read?</span></span> <span data-ttu-id="cb83e-1307">Personalice el menú de acciones rápidas con los comandos que use más frecuentemente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1307">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="cb83e-p218">**Verán los memes que comparta:** cuando un texto o imágenes estáticas no consigan comunicar lo que desea, use un GIF animado para aclararlo. [Más información](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="cb83e-p218">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="cb83e-1310">**Una forma más rápida de agregar cuentas:** gracias a las mejoras de configuración de cuentas, es más fácil que nunca agregar cuentas de Outlook.com y Gmail que usen la autenticación en dos fases a Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1310">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="cb83e-1311">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1311">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="cb83e-1312">**Despídase de límites de sincronización:** las mejoras de Outlook significan que se ha eliminado el límite de carpetas y sincronizar los buzones compartidos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1312">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="cb83e-1313">**Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1313">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="cb83e-1314">Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1314">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="cb83e-1315">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1315">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="cb83e-1316">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb83e-1316">PowerPoint</span></span>

- <span data-ttu-id="cb83e-1317">**Mejor transformación:** asigne un nombre a las formas para tener más control sobre cómo se transforman.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1317">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="cb83e-1318">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1318">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="cb83e-1319">**Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente?</span><span class="sxs-lookup"><span data-stu-id="cb83e-1319">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="cb83e-1320">Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1320">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="cb83e-1321">**Aumentar el alcance de su contenido:** ¿necesita que las presentaciones sean accesibles?</span><span class="sxs-lookup"><span data-stu-id="cb83e-1321">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="cb83e-1322">Deje que el comprobador de accesibilidad le ayude sin estorbar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1322">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="cb83e-1323">Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1323">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="cb83e-1324">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1324">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="cb83e-1325">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1325">Switching between them has never been easier.</span></span> [<span data-ttu-id="cb83e-1326">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1326">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="cb83e-1327">**Los vídeos en línea tienen un nuevo hogar:** guarde un vídeo en Microsoft Stream para que puedan verlo todas las personas de su organización.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1327">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="cb83e-1328">Inserte el vínculo del vídeo y disfrute de una presentación multimedia en una fracción del tamaño del archivo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1328">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="cb83e-1329">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1329">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="cb83e-1330">**Guardar los cambios a medida que los realiza:** cargue el archivo en OneDrive para asegurarse de que todas las actualizaciones se guardan automáticamente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1330">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="cb83e-p226">**Pregunte a su público con un cuestionario o una encuesta:** coloque un cuestionario o una encuesta en una diapositiva. Office recopila y almacena las respuestas para usted. [Más información](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="cb83e-p226">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="cb83e-p227">**Nunca fue tan fácil insertar un vídeo en línea:** ¿quiere poner un vídeo de Vimeo o de YouTube en la diapositiva? Solo necesita el vínculo a la página del vídeo. [Más información](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="cb83e-p227">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="cb83e-1337">**Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1337">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="cb83e-1338">Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1338">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="cb83e-1339">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1339">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="cb83e-1340">Project</span><span class="sxs-lookup"><span data-stu-id="cb83e-1340">Project</span></span>

- <span data-ttu-id="cb83e-1341">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1341">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="cb83e-1342">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1342">Switching between them has never been easier.</span></span> [<span data-ttu-id="cb83e-1343">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1343">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="cb83e-1344">Visio</span><span class="sxs-lookup"><span data-stu-id="cb83e-1344">Visio</span></span>

- <span data-ttu-id="cb83e-1345">**Exportar diagramas de proceso a Word:** Agregue automáticamente contenido del diagrama, como formas y metadatos, a un documento de Word.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1345">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="cb83e-1346">Después, personalice el documento para crear instrucciones de procesos y manuales de funcionamiento.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1346">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="cb83e-1347">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1347">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="cb83e-1348">**Doble toma en diagramas de flujo de datos:** Los magníficos nuevos diseños para los diagramas de flujo del visualizador de datos son limpios, nítidos y fáciles de entender.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1348">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="cb83e-1349">Haga clic en la pestaña Diseño para ver las opciones.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1349">Click the Design tab for options.</span></span>

- <span data-ttu-id="cb83e-1350">**Galerías de símbolos integradas en Azure:** diseñe una aplicación de nube o planee una arquitectura con las múltiples galerías de símbolos de Azure.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1350">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="cb83e-1351">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1351">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="cb83e-p233">**Adiós a los vínculos rotos de Excel:** ¿no encuentra el libro de Excel vinculado a un diagrama de visualizador de datos? Solo tiene que vincularlo de nuevo y ¡listo! [Más información](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="cb83e-p233">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="cb83e-1355">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1355">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="cb83e-1356">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1356">Switching between them has never been easier.</span></span> [<span data-ttu-id="cb83e-1357">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1357">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="cb83e-1358">**Exportar objetos visuales de Visio desde Power BI**: los objetos visuales de Visio para Power BI ahora se mostrarán correctamente al exportar informes de Power BI como archivos PDF, archivos de PowerPoint, etc.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1358">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="cb83e-1359">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1359">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="cb83e-1360">Word</span><span class="sxs-lookup"><span data-stu-id="cb83e-1360">Word</span></span>

- <span data-ttu-id="cb83e-1361">**El modo herramientas de aprendizaje tiene soporte adicional para más colores de página:** las herramientas de aprendizaje de Word son compatibles con más colores de tema de página, lo que permite cambiar el color de fondo de la página.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1361">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="cb83e-1362">Muchas personas tienen dificultades para leer con un fondo totalmente blanco o negro, por lo que hemos ampliado la elección de colores en Word para PC y Mac.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1362">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="cb83e-p237">**Edición natural con el Editor para entradas de lápiz:** con un solo trazo, divida o una palabras, agregue una nueva línea o inserte palabras con el lápiz. [Más información](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="cb83e-p237">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="cb83e-p238">**Su documento: de estático a mágico:** transforme el documento en una página web interactiva y fácil de compartir con un aspecto fantástico en cualquier dispositivo. [Más información](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="cb83e-p238">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="cb83e-1367">**Aumentar el alcance de su contenido:** ¿necesita hacer que sus documentos sean accesibles?</span><span class="sxs-lookup"><span data-stu-id="cb83e-1367">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="cb83e-1368">Deje que el comprobador de accesibilidad le ayude sin estorbar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1368">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="cb83e-1369">Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1369">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="cb83e-1370">**Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente?</span><span class="sxs-lookup"><span data-stu-id="cb83e-1370">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="cb83e-1371">Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1371">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="cb83e-1372">**Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1372">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="cb83e-1373">Cambiar de una a otra nunca había sido tan fácil.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1373">Switching between them has never been easier.</span></span> [<span data-ttu-id="cb83e-1374">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1374">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="cb83e-p242">**Mejorar la comprensión con el foco de línea:** desplácese por un documento línea por línea sin distracciones. Ajuste el foco para ver una, tres o cinco líneas a la vista. [Más información](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="cb83e-p242">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="cb83e-1378">**Guarde sus cambios a medida que se produzcan:** Suba su archivo a OneDrive para asegurarse de que todas sus actualizaciones se guarden automáticamente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1378">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="cb83e-1379">**Consiga su atención con\@menciones:** use @menciones en los comentarios para avisar a los compañeros de trabajo cuando necesite su participación.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1379">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="cb83e-1380">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1380">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="cb83e-1381">**Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1381">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="cb83e-1382">Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1382">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="cb83e-1383">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1383">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="cb83e-1384">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-1384">Office Suite</span></span>

- <span data-ttu-id="cb83e-1385">**Encuentra ese archivo rápido:** ¿Busca un archivo en el que haya trabajado recientemente?</span><span class="sxs-lookup"><span data-stu-id="cb83e-1385">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="cb83e-1386">Sólo tiene que escribir en el cuadro de búsqueda de la pestaña Archivo > Abrir para encontrar el archivo que está buscando.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1386">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="cb83e-1387">**Guardar los cambios a medida que los realiza:** cargue el archivo en OneDrive para asegurarse de que todas las actualizaciones se guardan automáticamente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1387">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="cb83e-1388">**Controles de privacidad:** nuevos controles para datos de diagnóstico y experiencias conectadas, actualizados y mejorados.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1388">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="cb83e-1389">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1389">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="cb83e-1390">**Los iconos de Office tienen un nuevo aspecto:** los iconos de Office se han rediseñado para reflejar las sencillas, inteligentes y eficaces experiencias de Office.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1390">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="cb83e-1391">**Instalación de Microsoft Teams:** Microsoft Teams se instala de forma predeterminada en las instalaciones existentes de Office 365 ProPlus.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1391">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="cb83e-1392">Más información</span><span class="sxs-lookup"><span data-stu-id="cb83e-1392">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-1395">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-1395">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="cb83e-1396">Access</span><span class="sxs-lookup"><span data-stu-id="cb83e-1396">Access</span></span>

- <span data-ttu-id="cb83e-1397">Esta actualización corrige un problema en el que la agregación como la suma puede truncar el resultado a un valor entero.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1397">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="cb83e-1398">Esta actualización corrige un problema por el que una consulta de Unión que incluye referencias a tablas remotas (por ejemplo, tablas de SQL Server) puede hacer que Access se cierre y se reinicie.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1398">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="cb83e-1399">Esta actualización corrige un problema en Microsoft Access que puede causar el error &quot;La consulta está dañada&quot; cuando se ejecuta una consulta de actualización o cuando se usa una instrucción UPDATE en SQL.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1399">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="cb83e-1400">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-1400">Excel</span></span>

- <span data-ttu-id="cb83e-1401">La información clave en holandés para el título del documento ha sido cambiada a Alt-G.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1401">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="cb83e-1402">Se ha corregido un problema en Excel en el que las macros asignadas a formas o controles de formularios podían mostrar un mensaje de error incorrecto o funcionar en intervalos de destino incorrectos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1402">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="cb83e-1403">Se resolvió un problema con buscar y reemplazar ese cambio donde el foco estaba en el diálogo después de encontrar el primer elemento.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1403">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="cb83e-1404">Esto corrige un problema por el cual al cambiar la forma en que se ordena y actualiza una tabla dinámica mientras se está en una sesión de co autoría con otros usuarios se podía provocar un bloqueo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1404">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="cb83e-1405">Arreglamos un problema cuando el filtro de una tabla dinámica OLAP se estableció en un valor que se había eliminado del cubo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1405">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="cb83e-1406">Se han corregido los colores que se usan en las vistas previas al insertar gráficos con plantillas de gráficos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1406">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="cb83e-1407">Se ha corregido un problema que podía impedir que los gráficos de líneas de dispersión se representaran correctamente al cambiar la colección de series.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1407">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="cb83e-1408">Se resolvió un problema que causó que los gráficos de cascada y embudo se desincronizara con las tablas cuando se insertaban o eliminaban celdas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1408">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="cb83e-1409">Se ha corregido un problema de conflicto de fusión en Excel que hacía que los usuarios tuvieran que volver a abrir el libro de trabajo para elegir los cambios.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1409">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="cb83e-1410">Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1410">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="cb83e-1411">Se resolvió un problema que causaba un error de tiempo de ejecución de la macro que activaba las ventanas minimizadas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1411">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="cb83e-1412">Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1412">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="cb83e-1413">Se resolvió un problema que causaba que las operaciones de cortar y pegar junto a una mesa fallaran cuando se co autoría con otros.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1413">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="cb83e-1414">Se resolvió un problema que causaba interrupciones de co autoría cuando se cambiaban las propiedades personalizadas con macros en ejecución.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1414">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="cb83e-1415">Hubo un problema en el que no se podían seleccionar elementos del cuadro combinado de un formulario de WPF (Windows Presentation Foundation) que fue abierto por un complemento.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1415">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="cb83e-1416">Se ha resuelto un problema que puede haber causado un bloqueo al buscar archivos recientes cuando no hay ningún libro de trabajo abierto.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1416">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="cb83e-1417">Problema de rendimiento con las Funciones Asincrónicas Definidas por el Usuario que hacía que se ejecutaran sincrónicamente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1417">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="cb83e-1418">Mejoras significativas en el rendimiento de la eliminación de columnas con celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1418">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="cb83e-1419">Se resolvió un problema en el que la selección de una celda después del desplazamiento podía dar lugar a que se seleccionara la celda incorrecta.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1419">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="cb83e-1420">Se ha resuelto un problema en el que la función de búsqueda puede devolver un error.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1420">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="cb83e-1421">Se ha resuelto un problema por el que los libros de trabajo creados en versiones anteriores de Office podían hacer que Excel se colgara al abrirlos en las versiones actuales de Office.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1421">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="cb83e-1422">Problema de rendimiento bajo al hacer clic en el botón Color de fuente cuando un archivo tiene un formato condicional extenso.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1422">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="cb83e-1423">Se ha corregido un problema por el que el área de impresión en la vista previa de impresión no era correcta.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1423">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="cb83e-1424">Excel puede tener problemas al editar un archivo protegido desde una red compartida no confiable.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1424">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="cb83e-1425">Hemos mejorado significativamente el rendimiento del filtrado por color.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1425">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="cb83e-1426">Se resolvió un problema que impedía que los hipervínculos se pegaran en algunas hojas protegidas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1426">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="cb83e-1427">Se habilitó más de 16 complementos para que se muestren al navegar en el administrador de complementos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1427">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="cb83e-1428">Este cambio evita un problema con ciertos controladores de gráficos Intel aprovechando la renderización de software.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1428">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="cb83e-1429">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="cb83e-1429">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="cb83e-1430">Esta actualización corrige un error por el cual los documentos de Office pueden fallar al subirlos a OneDrive para la Empresa con el mensaje "Error al cargar".</span><span class="sxs-lookup"><span data-stu-id="cb83e-1430">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="cb83e-1431">Corregir problema en la característica Ideas de Excel, error al cargar el complemento haciendo clic en el botón Ideas en el cliente Win32.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1431">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="cb83e-1432">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-1432">Outlook</span></span>

- <span data-ttu-id="cb83e-1433">Los vínculos de cid:image de los mensajes de Outlook ahora se pueden romper correctamente cuando se solicite.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1433">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="cb83e-1434">Se ha corregido un problema que causaba que los usuarios que actualizaban su buzón de la autenticación básica a la moderna, terminaban con una cuenta incorrecta asociada a su perfil de Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1434">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="cb83e-1435">Corregido un problema que hizo que los complementos web accedieran a los mensajes de Digital Rights Managed cuando no deberían hacerlo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1435">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="cb83e-1436">Corregido un problema que causó que las URLS de enlace simple no se mostraran en algunos enlaces seguros.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1436">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="cb83e-1437">Esto actualiza la lógica de bloqueo de adjuntos en Outlook para bloquear también los adjuntos de Python.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1437">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="cb83e-1438">Corregido un problema que hacía que un subconjunto de usuarios POP3 viera todos sus correos electrónicos formateados en texto plano, independientemente de la configuración.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1438">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="cb83e-1439">Esta corrección restaurará la vista de los mensajes con formato HTML.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1439">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="cb83e-1440">Corregido un problema que hacía que los usuarios experimentaran un error de permiso al copiar elementos de su calendario principal a un calendario de grupo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1440">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="cb83e-1441">Corregido un problema que hacía que los usuarios no pudieran acceder a las sugerencias de ubicación a través de un lector de pantalla.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1441">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="cb83e-1442">Corregido un problema que hacía que los usuarios vieran un retraso notable al interactuar con sus carpetas de buzón de correo a través de métodos abreviados de teclado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1442">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="cb83e-1443">Corregido un problema que causaba una fuga de memoria en sesiones de Outlook muy largas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1443">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="cb83e-1444">Corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al abrir el cuadro de diálogo Reglas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1444">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="cb83e-1445">Corregido un problema que haría que los usuarios experimentaran un bloqueo en Outlook al interactuar con ciertos vínculos seguros.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1445">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="cb83e-1446">Corregido un problema que causó ambigüedad a los gerentes en cuanto a si un delegado ya había respondido o no a una determinada solicitud de reunión.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1446">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="cb83e-1447">Corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1447">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="cb83e-1448">Se ha solucionado un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "ok" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1448">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="cb83e-1449">Este cambio permite a los administradores habilitar una política para preferir el correo electrónico de la cuenta proporcionada en los avisos de autorización de AutoDiscover sobre el UPN.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1449">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="cb83e-1450">De forma predeterminada, detección automática prefiere el UPN de la cuenta, cuando está disponible.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1450">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="cb83e-1451">Se ha corregido un problema que provocaba que los usuarios vieran un error en la búsqueda con grupos modernos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1451">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="cb83e-1452">Solucionó un problema que causaba que los usuarios de Outlook se quedaran atascados en el estado "Necesita contraseña" en ciertos escenarios.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1452">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="cb83e-1453">Se abordó un problema que hizo que los usuarios vieran sugerencias de salas para reuniones que se produjeron fuera de las horas de disponibilidad de dichas salas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1453">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="cb83e-1454">Corregido un problema que hizo que los usuarios encontraran errores de "algoritmo de cifrado no admitido" al enviar un correo electrónico cifrado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1454">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="cb83e-1455">Corregido un problema para los usuarios que no hablan inglés, en el que la línea de asunto de un correo electrónico era increíblemente pequeña.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1455">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="cb83e-1456">Corregido un problema que hacía que algunos usuarios vieran duplicadas las carpetas especiales creadas al añadir una cuenta de Exchange secundaria.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1456">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="cb83e-1457">Corregido un problema que hacía que los usuarios experimentaran un bloqueo al intentar crear una regla a partir de un mensaje de "Conversación perdida".</span><span class="sxs-lookup"><span data-stu-id="cb83e-1457">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="cb83e-1458">Corregido un problema con la selección del algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1458">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="cb83e-1459">Corregido un problema que hacía que no se mostraran las sugerencias de política cuando se utilizaba un remitente alternativo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1459">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="cb83e-1460">Corregido un problema que hacía que los usuarios observaran una fuga de memoria en el proceso de Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1460">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="cb83e-1461">Corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1461">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="cb83e-1462">Corregido un problema que causaba que la búsqueda de la carpeta actual fallara de forma intermitente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1462">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="cb83e-1463">Corregido un problema que hizo que algunos usuarios encontraran errores de autenticación al intentar recuperar su configuración de nube para Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1463">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="cb83e-1464">Corregido un problema que causó un bloqueo en la experiencia de los comentarios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1464">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="cb83e-1465">Corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1465">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="cb83e-1466">Corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1466">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="cb83e-1467">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb83e-1467">PowerPoint</span></span>

- <span data-ttu-id="cb83e-1468">Se ha corregido un problema por el que algunos complementos producían errores inesperados alrededor de las formas en gráficos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1468">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="cb83e-1469">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="cb83e-1469">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="cb83e-1470">Este cambio restaura el nombre accesible de los controles de vídeo de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1470">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="cb83e-1471">Hemos corregido un problema que podría impedir que se inicien algunas animaciones.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1471">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="cb83e-1472">Hemos corregido un problema en el que al copiar una diapositiva de una presentación a otra, se pueden crear patrones duplicados.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1472">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="cb83e-1473">Los archivos con nuevos comentarios modernos mostrarán una advertencia amarilla si se abren en una versión no soportada</span><span class="sxs-lookup"><span data-stu-id="cb83e-1473">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="cb83e-1474">Fiabilidad fija: corregido un problema por el que el complemento de terceros podía bloquearse en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1474">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="cb83e-1475">Corregido un problema por el que los caracteres katakana de medio ancho no giraban correctamente cuando estaban en cuadros de texto verticales en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1475">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="cb83e-1476">Project</span><span class="sxs-lookup"><span data-stu-id="cb83e-1476">Project</span></span>

- <span data-ttu-id="cb83e-1477">Se ha corregido un problema para permitir que los usuarios en Windows 7 puedan abrir proyectos desde Project Web App y sitios de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1477">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="cb83e-1478">Se identificó un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de sólo lectura.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1478">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="cb83e-1479">El comando Level All no resuelve adecuadamente una sobreasignación de recursos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1479">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="cb83e-1480">Si tiene una tarea sin nada de trabajo, es posible que la tarea no se pueda marcar como completada y siempre se mostrará en el 99 %.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1480">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="cb83e-1481">Visio</span><span class="sxs-lookup"><span data-stu-id="cb83e-1481">Visio</span></span>

- <span data-ttu-id="cb83e-1482">La exportación como SVG de Visio estaba fallando por una variedad de formas.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1482">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="cb83e-1483">Word</span><span class="sxs-lookup"><span data-stu-id="cb83e-1483">Word</span></span>

- <span data-ttu-id="cb83e-1484">Este cambio conducirá a mejoras de rendimiento en la apertura de documentos utilizando Word.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1484">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="cb83e-1485">Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. </span><span class="sxs-lookup"><span data-stu-id="cb83e-1485">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="cb83e-1486">Hemos corregido un problema que podría haber causado problemas de escala al imprimir en impresoras Deskjet.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1486">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="cb83e-1487">Hemos corregido un problema en los cambios de pista que a veces van en un bucle infinito.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1487">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="cb83e-1488">Corregidos varios problemas que hacían que la aplicación se colgara al apagarse.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1488">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="cb83e-1489">También se corrigieron ciertos fallos relacionados con los complementos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1489">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="cb83e-1490">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="cb83e-1490">Office Suite</span></span>

- <span data-ttu-id="cb83e-1491">Corregido el problema de la identificación incorrecta del nombre de la nueva era "Reiwa" en hiragana y kanji como una expresión mal escrita o poco gramatical.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1491">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="cb83e-1492">Corregido un problema que hacía que los usuarios recibieran el mensaje "Lo sentimos, algo nos impide compartir esto" al intentar compartir archivos almacenados en SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1492">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="cb83e-1493">Se ha solucionado un problema que podía causar la pérdida de datos en sesiones que implicaban tanto la co autoría como la edición fuera de línea en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1493">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="cb83e-1494">Esta es una solución para un fallo que los usuarios podrían sufrir al abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1494">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="cb83e-1495">Evita que los usuarios de PowerPoint se encuentren con un error cuando intentan hacer una presentación en línea.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1495">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="cb83e-1496">En algunos casos, un archivo de sharepoint respaldado por un motor de sincronización podría mostrar "Guardado" pero no haber guardado realmente ningún cambio, lo que provocaría la pérdida de datos.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1496">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="cb83e-1497">Se resolvió un problema que impedía a los usuarios guardar documentos de Word, Excel y PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1497">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="cb83e-1498">Este problema afecta a los usuarios que crean un nuevo archivo y muestra la opción "Guardar como diálogo" después de hacer clic en el icono Guardar o presionar Ctrl + S.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1498">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="cb83e-1499">Se ha corregido un problema de perf en Win7 en el que la galería de formas de inserción de la cinta en todas las aplicaciones tardaba aproximadamente 4 segundos en aparecer.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1499">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="cb83e-1500">Corregido un error por el que la información de accesibilidad no se mostraba en la losa del lugar de información de los bastidores.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1500">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="cb83e-1501">Mejora de la fiabilidad del proceso de actualización de Office en lo que respecta a la integridad del registro.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1501">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="cb83e-1502">Se ha corregido un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1502">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="cb83e-1503">Se ha solucionado un problema por el que los mensajes de actualización de Office aparecían en un idioma diferente al esperado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1503">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="cb83e-1504">En el futuro, los mensajes de actualización de Office coincidirán correctamente con el idioma de visualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1504">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="cb83e-1505">Corregido un problema en el que una actualización no se aplicaría en ciertos casos en los que el usuario no es un administrador y la cuenta del sistema no tenía conectividad de red.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1505">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="cb83e-1506">En determinadas circunstancias, los accesos directos de Office pueden desaparecer tras una actualización.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1506">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="cb83e-1507">Esta actualización mejora la fiabilidad en la publicación de los accesos directos de Office.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1507">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="cb83e-1508">Se ha corregido un problema por el que las actualizaciones se bloqueaban inesperadamente en las redes de medición.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1508">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="cb83e-1509">Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1509">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="cb83e-1510">Mejora de la confiabilidad al descargar las actualizaciones de Office al reanudar las descargas que pueden haberse interrumpido anteriormente.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1510">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="cb83e-1511">Corregidos los problemas relacionados con la propiedad Textbox/Shape Autofit en los plug-ins de terceros.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1511">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="cb83e-1512">Hemos corregido un problema en el que las vistas de árboles grandes podían resultar en un choque.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1512">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="cb83e-1513">Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1513">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-january-14"></a><span data-ttu-id="cb83e-1515">Versión 1902: 14 de enero</span><span class="sxs-lookup"><span data-stu-id="cb83e-1515">Version 1902: January 14</span></span>
<span data-ttu-id="cb83e-1516">*VVersión 1902 (compilación 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-1516">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="cb83e-1517">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-1517">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="cb83e-1519">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="cb83e-1519">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb83e-1520">Excel</span><span class="sxs-lookup"><span data-stu-id="cb83e-1520">Excel</span></span>

- <span data-ttu-id="cb83e-1521">Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1521">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="cb83e-1522">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb83e-1522">Outlook</span></span>

- <span data-ttu-id="cb83e-1523">Corregido un problema que causó que los usuarios se encontraran con errores de "el algoritmo de cifrado no es compatible" al enviar un correo electrónico cifrado.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1523">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="cb83e-1524">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb83e-1524">PowerPoint</span></span>

- <span data-ttu-id="cb83e-1525">Los archivos con nuevos comentarios modernos mostrarán una advertencia amarilla si se abren en una versión no soportada.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1525">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="cb83e-1526">Word</span><span class="sxs-lookup"><span data-stu-id="cb83e-1526">Word</span></span>

- <span data-ttu-id="cb83e-1527">Este cambio conducirá a mejoras de rendimiento en la apertura de documentos utilizando Word.</span><span class="sxs-lookup"><span data-stu-id="cb83e-1527">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (NO ELIMINAR LOS DETALLES DEL CONTENIDO FINAL)

## <a name="version-1808-january-14"></a><span data-ttu-id="cb83e-1529">Versión 1808: 14 de enero</span><span class="sxs-lookup"><span data-stu-id="cb83e-1529">Version 1808: January 14</span></span>
<span data-ttu-id="cb83e-1530">*Versión 1808 (compilación 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="cb83e-1530">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="cb83e-1531">Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb83e-1531">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

> [!NOTE]
> <span data-ttu-id="cb83e-1533">Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="cb83e-1533">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (NO MODIFICAR EL INICIO DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
[//]: # (|Win32|DC|Production| |16.0.13127.21216|version-2008-february-09|)
[//]: # (| Win32 | CC | Producción | | 16.0.13127.21064 | versión-2008-enero-12 |)
[//]: # (| Win32 | DC | Producción | | 16.0.12527.21416 | versión-2002-diciembre-08 |)
[//]: # (| Win32 | DC | Producción | | 16.0.12527.21330 | versión-2002-noviembre-10 |)
[//]: # (| Win32 | CC | Producción | | 16.0.12527.20880 | versión-2002-julio-14 |)
[//]: # (|Win32|DC|Producción| |16.0.12527.21104|versión-2002-08-agosto|)
[//]: # (|Win32|DC|Producción| |16.0.12527.20988|versión-2002-11-agosto|)
[//]: # (| Win32 | CC | Producción | | 16.0.12527.20880 | versión-2002-julio-14 |)
[//]: # (NO MODIFICAR EL FIN DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
