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
ms.openlocfilehash: d6c48db35445d15503c246506bc7d03da3ca0548
ms.sourcegitcommit: 4a2190fd43c552c92d8194ec4520673d75af22f1
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/13/2021
ms.locfileid: "51748968"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="66433-103">Notas de la versión para el canal semestral para empresas (vista previa)</span><span class="sxs-lookup"><span data-stu-id="66433-103">Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="66433-104">Estas notas de la versión proporcionan información sobre las nuevas características y las actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones del canal semestral para empresas (vista previa) para las Aplicaciones de Microsoft 365 para empresas, las Aplicaciones de Microsoft 365 para negocios, y las versiones de suscripción de las aplicaciones de escritorio de Project y Visio.</span><span class="sxs-lookup"><span data-stu-id="66433-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="66433-105">Estamos realizando algunos cambios en los canales de actualización de las Aplicaciones de Microsoft 365, incluida la adición de un nuevo canal de actualización (canal empresarial mensual) y el cambio de los nombres de los canales de actualización existentes.</span><span class="sxs-lookup"><span data-stu-id="66433-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="66433-106">[Lea este artículo](/DeployOffice/update-channels-changes) para más información.</span><span class="sxs-lookup"><span data-stu-id="66433-106">To learn more, [read this article](/DeployOffice/update-channels-changes).</span></span>


## <a name="version-2102-april-13"></a><span data-ttu-id="66433-107">Versión 2102: 13 de abril</span><span class="sxs-lookup"><span data-stu-id="66433-107">Version 2102: April 13</span></span>
<span data-ttu-id="66433-108">*Versión 2102 (Compilación 13801.20506)*</span><span class="sxs-lookup"><span data-stu-id="66433-108">*Version 2102 (Build 13801.20506)*</span></span>

<span data-ttu-id="66433-109">Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="66433-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="66433-111">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="66433-111">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="66433-112">Access</span><span class="sxs-lookup"><span data-stu-id="66433-112">Access</span></span>

- <span data-ttu-id="66433-113">Se ha corregido un problema por el que al ejecutar una consulta que pasara por SQL Server, se mostraba en algunos casos un mensaje de error que alertaba de un "estado de cursor no válido".</span><span class="sxs-lookup"><span data-stu-id="66433-113">Fixed an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="66433-114">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-114">Excel</span></span>

- <span data-ttu-id="66433-115">Se ha corregido un problema por el que los comandos deshabilitados de la cinta de opciones de Office tenían el icono (pero no el texto) atenuado en el tema de Office Gris oscuro.</span><span class="sxs-lookup"><span data-stu-id="66433-115">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="66433-116">Hemos corregido un problema en el que la validación de datos se podía aplicar a celdas de forma inesperada después de añadir filas a una tabla o a otra hoja.</span><span class="sxs-lookup"><span data-stu-id="66433-116">We fixed an issue in which data validation could be applied to cells unexpectedly after adding rows to a table on another sheet.</span></span>


- <span data-ttu-id="66433-117">Hemos corregido un problema donde la función de mostrar DialogSheets no funcionaba en la versión de 32 bit de Excel.</span><span class="sxs-lookup"><span data-stu-id="66433-117">We fixed an issue where the DialogSheets show function was not working on 32 bit versions of Excel</span></span>


### <a name="outlook"></a><span data-ttu-id="66433-118">Outlook</span><span class="sxs-lookup"><span data-stu-id="66433-118">Outlook</span></span>

- <span data-ttu-id="66433-119">Hemos corregido un problema que provocaba que Outlook se bloquease cuando estaba inactivo.</span><span class="sxs-lookup"><span data-stu-id="66433-119">We fixed an issue that caused Outlook to crash when idle.</span></span>


- <span data-ttu-id="66433-120">Hemos corregido un problema que causaba que los usuarios de la característica Configuración de la nube vieran que se reemplazaba la configuración personalizada por la configuración predeterminada después de configurar Outlook en un nuevo dispositivo.</span><span class="sxs-lookup"><span data-stu-id="66433-120">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="66433-121">Hemos corregido un problema que provocaba que los usuarios vieran más firmas de las esperadas.</span><span class="sxs-lookup"><span data-stu-id="66433-121">We fixed an issue that caused users to see more signatures than expected.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="66433-122">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66433-122">PowerPoint</span></span>

- <span data-ttu-id="66433-123">Se ha corregido un problema por el que los comandos deshabilitados de la cinta de opciones de Office tenían el icono (pero no el texto) atenuado en el tema de Office Gris oscuro.</span><span class="sxs-lookup"><span data-stu-id="66433-123">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="word"></a><span data-ttu-id="66433-124">Word</span><span class="sxs-lookup"><span data-stu-id="66433-124">Word</span></span>

- <span data-ttu-id="66433-125">Se ha corregido un problema por el que los comandos deshabilitados de la cinta de opciones de Office tenían el icono (pero no el texto) atenuado en el tema de Office Gris oscuro.</span><span class="sxs-lookup"><span data-stu-id="66433-125">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="66433-126">Se ha corregido un problema con copiar y pegar.</span><span class="sxs-lookup"><span data-stu-id="66433-126">We fixed an issue relating to copy and paste.</span></span>


- <span data-ttu-id="66433-127">Hemos corregido un problema con la escritura al final de un párrafo oculto que podía provocar que la aplicación dejara de funcionar.</span><span class="sxs-lookup"><span data-stu-id="66433-127">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


### <a name="office-suite"></a><span data-ttu-id="66433-128">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="66433-128">Office Suite</span></span>

- <span data-ttu-id="66433-129">Se ha corregido un problema por el que los usuarios no podían guardar un archivo al abrirlo, realizar modificaciones sin guardar y eliminarlo.</span><span class="sxs-lookup"><span data-stu-id="66433-129">Fixed an issue where users are unable to save file when open a previously opened file with edits not saved but now the file has been deleted.</span></span> <span data-ttu-id="66433-130">Después de la corrección, los usuarios recibirán un mensaje descriptivo para informarles de que el archivo se ha eliminado, de modo que podrán descartar cambios o usar la opción Guardar como.</span><span class="sxs-lookup"><span data-stu-id="66433-130">After the fix, users will get a friendly message to inform them that the file is deleted, thus user can choose to discard changes, or SaveAs the file.</span></span>


- <span data-ttu-id="66433-131">Se ha corregido el problema del cambio de nombre cuando se abría un archivo SyncBacked fuera de línea y se le cambiaba el nombre en la aplicación antes de guardarlo.</span><span class="sxs-lookup"><span data-stu-id="66433-131">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>


- <span data-ttu-id="66433-132">Se ha corregido un problema que impedía la opción Dictado para usuarios de GCC.</span><span class="sxs-lookup"><span data-stu-id="66433-132">Fixed an issue where Dictation was disabled for GCC users</span></span>


- <span data-ttu-id="66433-133">Se ha corregido un problema que a veces provocaba que el texto en Outlook se viera transparente y no fuera legible.</span><span class="sxs-lookup"><span data-stu-id="66433-133">Fixed an issue that could sometimes lead to text in Outlook becoming transparent and thereby not legible.</span></span>


[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2102-march-09"></a><span data-ttu-id="66433-135">Versión 2102: 9 de marzo</span><span class="sxs-lookup"><span data-stu-id="66433-135">Version 2102: March 09</span></span>
<span data-ttu-id="66433-136">*Versión 2102 (Compilación 13801.20294)*</span><span class="sxs-lookup"><span data-stu-id="66433-136">*Version 2102 (Build 13801.20294)*</span></span>

<span data-ttu-id="66433-137">Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="66433-137">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="66433-139">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="66433-139">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="66433-140">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-140">Excel</span></span>

- <span data-ttu-id="66433-141">**Lazo y borrador en el Cuadro de herramientas de entrada de lápiz:** al usar las herramientas de dibujo, el lazo y el borrador están ahora disponibles en Cuadro de herramientas de entrada de lápiz.</span><span class="sxs-lookup"><span data-stu-id="66433-141">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="66433-142">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span><span class="sxs-lookup"><span data-stu-id="66433-142">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="66433-143">**Realice una conexión PDF:** Conectar, importar, actualizar los datos de un PDF.</span><span class="sxs-lookup"><span data-stu-id="66433-143">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="66433-144">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-144">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="66433-145">**Crear variables para usar en fórmulas:** mejorar el rendimiento, la legibilidad y la composición con la función LET.</span><span class="sxs-lookup"><span data-stu-id="66433-145">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="66433-146">Esta función le permite crear variables con nombre en fórmulas nuevas o previamente existentes.</span><span class="sxs-lookup"><span data-stu-id="66433-146">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="66433-147">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-147">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="66433-148">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span><span class="sxs-lookup"><span data-stu-id="66433-148">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="66433-149">**Guardar en carpetas fijadas:** anclar las carpetas facilita el almacenamiento de archivos de Office.</span><span class="sxs-lookup"><span data-stu-id="66433-149">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="66433-150">Recibimos un comentario en el que se nos informa de que los usuarios desean tener más control sobre las carpetas disponibles al guardar un archivo nuevo.</span><span class="sxs-lookup"><span data-stu-id="66433-150">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="66433-151">Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar.</span><span class="sxs-lookup"><span data-stu-id="66433-151">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="66433-152">Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.</span><span class="sxs-lookup"><span data-stu-id="66433-152">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="66433-153">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-153">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="66433-154">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="66433-154">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="66433-155">**Obtenga datos de organización de Power BI mediante tipos de datos:** los tipos de datos de Excel de Power BI se están publicando ahora para participantes de Insider en las organizaciones con Office 365 o Microsoft 365 y el plan de servicio Power BI Pro.</span><span class="sxs-lookup"><span data-stu-id="66433-155">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 / Microsoft 365 and the Power BI Pro service plan.</span></span> <span data-ttu-id="66433-156">Obtener la información que necesita y actualizarla fácilmente es fundamental para muchos de los flujos de trabajo diarios.</span><span class="sxs-lookup"><span data-stu-id="66433-156">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="66433-157">Le proporcionamos acceso a la información de Power BI de su empresa u organización como un tipo de datos en Excel, lo que amplía su capacidad de incorporar a las hojas de cálculo información vinculada.</span><span class="sxs-lookup"><span data-stu-id="66433-157">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="66433-158">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-158">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="66433-159">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="66433-159">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="66433-160">**Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office.</span><span class="sxs-lookup"><span data-stu-id="66433-160">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="66433-161">No es necesario realizar ninguna conversión.</span><span class="sxs-lookup"><span data-stu-id="66433-161">No conversion required.</span></span><br /><span data-ttu-id="66433-162">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="66433-162">See details in [blog post](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="66433-163">**Crear diagramas de Visio elegantes en Excel:** cree diagramas basados en datos como diagramas de flujo u organigramas a partir de datos en una hoja de cálculo.</span><span class="sxs-lookup"><span data-stu-id="66433-163">**Make polished Visio diagrams in Excel:** Create data-driven diagrams like flowcharts or organizational charts from data in a worksheet.</span></span> [<span data-ttu-id="66433-164">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-164">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a><span data-ttu-id="66433-165">Outlook</span><span class="sxs-lookup"><span data-stu-id="66433-165">Outlook</span></span>

- <span data-ttu-id="66433-166">**Protección de datos del grupo:** la etiqueta de confidencialidad que elija al crear un grupo se aplica al correo electrónico del grupo, a los documentos y a los sitios de equipo.</span><span class="sxs-lookup"><span data-stu-id="66433-166">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>

- <span data-ttu-id="66433-167">**Notificación de incidentes para administradores de TI:** se notificará a los administradores globales de espacios empresariales de Microsoft 365 y a los administradores de aplicaciones de Office acerca de los incidentes de Outlook y Exchange de O365 que afectan a sus usuarios con una nueva notificación en el panel derecho en Outlook para Windows.</span><span class="sxs-lookup"><span data-stu-id="66433-167">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="66433-168">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-168">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="66433-169">**Crear sondeos en Outlook con Sondeo rápido:** cree sondeos, recopile votos y vea los resultados rápidamente en un solo correo electrónico [Más información](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="66433-169">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="66433-170">**Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office.</span><span class="sxs-lookup"><span data-stu-id="66433-170">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="66433-171">No es necesario realizar ninguna conversión.</span><span class="sxs-lookup"><span data-stu-id="66433-171">No conversion required.</span></span><br /><span data-ttu-id="66433-172">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="66433-172">See details in [blog post](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="66433-173">**Nuevo buscador de salas:** búsqueda de salas de conferencias por distintas funcionalidades.</span><span class="sxs-lookup"><span data-stu-id="66433-173">**New room finder:** Search for conference rooms by different capabilities.</span></span>

- <span data-ttu-id="66433-174">**Búscalo tal y como tú lo dirías:** Usa un lenguaje cotidiano como "cita con el veterinario de la semana pasada" para filtrar y limitar la búsqueda.</span><span class="sxs-lookup"><span data-stu-id="66433-174">**Search for it the way you'd say it:** Use everyday language like "vet appointment last week" to filter and narrow your search.</span></span>

- <span data-ttu-id="66433-175">**Opción para volver a abrir rápidamente los elementos de la sesión anterior de Outlook:** hemos agregado una opción para volver a abrir rápidamente los elementos de una sesión anterior de Outlook.</span><span class="sxs-lookup"><span data-stu-id="66433-175">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span><br /><span data-ttu-id="66433-176">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/automatically-restore-windows-in-outlook)</span><span class="sxs-lookup"><span data-stu-id="66433-176">See details in [blog post](https://insider.office.com/es-ES/blog/automatically-restore-windows-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="66433-177">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66433-177">PowerPoint</span></span>

- <span data-ttu-id="66433-178">**Lazo y borrador en el Cuadro de herramientas de entrada de lápiz:** al usar las herramientas de dibujo, el lazo y el borrador están ahora disponibles en Cuadro de herramientas de entrada de lápiz.</span><span class="sxs-lookup"><span data-stu-id="66433-178">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="66433-179">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span><span class="sxs-lookup"><span data-stu-id="66433-179">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="66433-180">**Guardar en carpetas fijadas:** anclar las carpetas facilita el almacenamiento de archivos de Office.</span><span class="sxs-lookup"><span data-stu-id="66433-180">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="66433-181">Recibimos un comentario en el que se nos informa de que los usuarios desean tener más control sobre las carpetas disponibles al guardar un archivo nuevo.</span><span class="sxs-lookup"><span data-stu-id="66433-181">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="66433-182">Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar.</span><span class="sxs-lookup"><span data-stu-id="66433-182">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="66433-183">Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.</span><span class="sxs-lookup"><span data-stu-id="66433-183">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="66433-184">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-184">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="66433-185">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="66433-185">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="66433-186">**Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office.</span><span class="sxs-lookup"><span data-stu-id="66433-186">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="66433-187">No es necesario realizar ninguna conversión.</span><span class="sxs-lookup"><span data-stu-id="66433-187">No conversion required.</span></span><br /><span data-ttu-id="66433-188">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="66433-188">See details in [blog post](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="visio"></a><span data-ttu-id="66433-189">Visio</span><span class="sxs-lookup"><span data-stu-id="66433-189">Visio</span></span>

- <span data-ttu-id="66433-190">**Nuevas galerías de símbolos y formas de Azure:** Hemos agregado muchas más galerías de símbolos para ayudarle a crear diagramas de Azure actualizados.</span><span class="sxs-lookup"><span data-stu-id="66433-190">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="66433-191">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-191">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a><span data-ttu-id="66433-192">Word</span><span class="sxs-lookup"><span data-stu-id="66433-192">Word</span></span>

- <span data-ttu-id="66433-193">**Lazo y borrador en el Cuadro de herramientas de entrada de lápiz:** al usar las herramientas de dibujo, el lazo y el borrador están ahora disponibles en Cuadro de herramientas de entrada de lápiz.</span><span class="sxs-lookup"><span data-stu-id="66433-193">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="66433-194">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span><span class="sxs-lookup"><span data-stu-id="66433-194">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="66433-195">**Guardar en carpetas fijadas:** anclar las carpetas facilita el almacenamiento de archivos de Office.</span><span class="sxs-lookup"><span data-stu-id="66433-195">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="66433-196">Recibimos un comentario en el que se nos informa de que los usuarios desean tener más control sobre las carpetas disponibles al guardar un archivo nuevo.</span><span class="sxs-lookup"><span data-stu-id="66433-196">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="66433-197">Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar.</span><span class="sxs-lookup"><span data-stu-id="66433-197">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="66433-198">Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.</span><span class="sxs-lookup"><span data-stu-id="66433-198">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="66433-199">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-199">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="66433-200">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="66433-200">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="66433-201">**Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office.</span><span class="sxs-lookup"><span data-stu-id="66433-201">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="66433-202">No es necesario realizar ninguna conversión.</span><span class="sxs-lookup"><span data-stu-id="66433-202">No conversion required.</span></span><br /><span data-ttu-id="66433-203">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="66433-203">See details in [blog post](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="office-suite"></a><span data-ttu-id="66433-204">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="66433-204">Office Suite</span></span>

- <span data-ttu-id="66433-205">**Paneles con pestañas:** ahora puede cambiar entre varios paneles con la pestaña situada en la parte derecha de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="66433-205">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="66433-206">Esta interfaz de usuario solo será visible cuando haya dos o más paneles abiertos.</span><span class="sxs-lookup"><span data-stu-id="66433-206">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="66433-207">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span><span class="sxs-lookup"><span data-stu-id="66433-207">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="66433-210">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="66433-210">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="66433-211">Acceso</span><span class="sxs-lookup"><span data-stu-id="66433-211">Access</span></span>

- <span data-ttu-id="66433-212">Se ha corregido un problema que provocaba que, al utilizar DAO desde aplicaciones que no son de Office, la aplicación se cerrara de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="66433-212">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="66433-213">Hemos corregido un problema por el que los usuarios estaban recibiendo el cuadro de diálogo de error "Estado de cursor no válido".</span><span class="sxs-lookup"><span data-stu-id="66433-213">We fixed an issue where users were getting an error dialog " Invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="66433-214">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-214">Excel</span></span>

- <span data-ttu-id="66433-215">Hemos corregido un problema que interrumpía algunas macros heredadas de Excel 4.0 y Excel 5.0, así como algunas llamadas de VBA a dialogsheets.show.</span><span class="sxs-lookup"><span data-stu-id="66433-215">We fixed an issue that broke some legacy Excel 4.0 and Excel 5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


- <span data-ttu-id="66433-216">Se ha corregido un problema que provocaba que Excel se cerrara de manera inesperada al usar el menú "Mostrar valores como" para una tabla dinámica.</span><span class="sxs-lookup"><span data-stu-id="66433-216">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="66433-217">Hemos corregido un problema que impedía a los usuarios exportar un libro de Excel a PDF.</span><span class="sxs-lookup"><span data-stu-id="66433-217">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="66433-218">Hemos corregido un problema que hace que las imágenes fueran más pequeñas de lo esperado al usar la opción Pegar imagen vinculada.</span><span class="sxs-lookup"><span data-stu-id="66433-218">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="66433-219">Hemos corregido un problema que causaba que algunos formatos de tabla dinámica dañaran el libro al guardar en formato .xls o .xlt.</span><span class="sxs-lookup"><span data-stu-id="66433-219">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="66433-220">Se ha corregido un problema que provocaba que Excel dejara macros deshabilitadas sin preguntar al abrir archivos de complemento de Excel que contuvieran macros Excel 4.0.</span><span class="sxs-lookup"><span data-stu-id="66433-220">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="66433-221">Se ha corregido un problema por el que Excel mostraba de forma incorrecta una barra de mensajes donde se indicaba que estaba disponible una nueva versión del archivo y obligaba al usuario a descartar los cambios o guardarlos en una copia del libro.</span><span class="sxs-lookup"><span data-stu-id="66433-221">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="66433-222">Se ha corregido un problema por el que algunos usuarios veían incorrectamente una barra de mensajes que les informaba de una nueva versión de un archivo durante la coautoría.</span><span class="sxs-lookup"><span data-stu-id="66433-222">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="66433-223">Corrige un problema por el que Excel no se iniciaba o se cerraba inesperadamente si se estaba usando cierta configuración de protección contra vulnerabilidades de Seguridad de Windows (SimExec, CallerCheck).</span><span class="sxs-lookup"><span data-stu-id="66433-223">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="66433-224">Hemos corregido un problema por el que Excel dejaba de responder después de seleccionar una serie de datos en un gráfico.</span><span class="sxs-lookup"><span data-stu-id="66433-224">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="66433-225">Este cambio soluciona un problema que impedía mostrar correctamente las fuentes en ecuaciones.</span><span class="sxs-lookup"><span data-stu-id="66433-225">This change addresses an issue with properly displaying fonts within equations.</span></span>


### <a name="outlook"></a><span data-ttu-id="66433-226">Outlook</span><span class="sxs-lookup"><span data-stu-id="66433-226">Outlook</span></span>

- <span data-ttu-id="66433-227">Se ha corregido un problema que provocaba que los usuarios no puedan conceder permisos de editor a los delegados.</span><span class="sxs-lookup"><span data-stu-id="66433-227">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="66433-228">Se ha corregido un problema que provocaba que Outlook se cerrara de forma inesperada para algunos usuarios en ciertos escenarios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="66433-228">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="66433-229">Se ha corregido un problema que provocaba que los usuarios que tienen buzones compartidos o delegados con jerarquías grandes en su perfil experimentaran bloqueos.</span><span class="sxs-lookup"><span data-stu-id="66433-229">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="66433-230">Corregido un problema que causaba que se enviaran algunos mensajes de correo electrónico generados automáticamente con el cuerpo en blanco cuando la línea del asunto estaba también en blanco.</span><span class="sxs-lookup"><span data-stu-id="66433-230">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="66433-231">Corregido un problema que causaba que algunos usuarios vieran Outlook de forma inesperada en un estado sin conexión.</span><span class="sxs-lookup"><span data-stu-id="66433-231">Addressed an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="66433-232">Corregido un problema que causaba que los delegados sufrieran errores intermitentemente al abrir carpetas compartidas en otro buzón.</span><span class="sxs-lookup"><span data-stu-id="66433-232">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="66433-233">Se ha corregido un problema que provocaba que la aplicación finalizara de forma abrupta cuando el cliente seleccionaba un resultado de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="66433-233">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="66433-234">Se ha corregido un problema que causaba que algunos clientes experimentaran un cuelgue mientras cargaban sus calendarios.</span><span class="sxs-lookup"><span data-stu-id="66433-234">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


- <span data-ttu-id="66433-235">Se ha corregido un problema que provocaba que los asistentes originales de algunas reuniones reciban una cancelación cuando otro asistente reenviaba la reunión.</span><span class="sxs-lookup"><span data-stu-id="66433-235">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="66433-236">Hemos corregido el problema que causaba que los usuarios viesen grupos de calendario duplicados después de crear un grupo.</span><span class="sxs-lookup"><span data-stu-id="66433-236">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="66433-237">Hemos corregido un problema que causaba que los usuarios de las mejoras del calendario compartido no pudieran establecer el color de un calendario en amarillo o marrón.</span><span class="sxs-lookup"><span data-stu-id="66433-237">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="66433-238">Hemos corregido un problema por el que los usuarios no veían los calendarios agregados recientemente en el panel de navegación si no reiniciaban Outlook.</span><span class="sxs-lookup"><span data-stu-id="66433-238">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="66433-239">Corregido un problema que provocaba que la búsqueda no devolviera ningún resultado al buscar en los calendarios compartidos sin almacenamiento en caché.</span><span class="sxs-lookup"><span data-stu-id="66433-239">Addressed an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="66433-240">Hemos corregido un problema que causaba que la app se cerrase para algunos usuarios al cerrar las ventanas de mensaje.</span><span class="sxs-lookup"><span data-stu-id="66433-240">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="66433-241">Se ha corregido un problema que provocaba que el campo "Para;" quedara vacío al enviar un informe de estado en una tarea.</span><span class="sxs-lookup"><span data-stu-id="66433-241">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="66433-242">Se ha corregido un problema que provocaba que se interrumpiera el evento MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="66433-242">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="66433-243">Se ha corregido un problema que provocaba que Outlook se cerrara de forma inesperada para algunos usuarios en ciertos escenarios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="66433-243">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="66433-244">Hemos corregido un problema que causaba que la aplicación se cerrara de forma inesperada al buscar en Outlook.</span><span class="sxs-lookup"><span data-stu-id="66433-244">We fixed an issue that caused the app to sometimes close unexpectedly when users were searching in Outlook.</span></span>


- <span data-ttu-id="66433-245">Hemos corregido un problema que causaba que los usuarios de Configuración de la nube tuviesen un error al actualizar la configuración.</span><span class="sxs-lookup"><span data-stu-id="66433-245">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>


- <span data-ttu-id="66433-246">Se ha corregido un problema por el que la firma editada no podía guardarse tras pedirle al usuario que lo hiciera.</span><span class="sxs-lookup"><span data-stu-id="66433-246">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>


- <span data-ttu-id="66433-247">Se ha corregido un problema que causaba que algunos usuarios no vieran ninguna firma en la lista desplegable a pesar de que se configuraron una o varias firmas.</span><span class="sxs-lookup"><span data-stu-id="66433-247">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


- <span data-ttu-id="66433-248">Se ha corregido un problema que, de forma predeterminada, impedía que se activara la configuración de la nube para los usuarios.</span><span class="sxs-lookup"><span data-stu-id="66433-248">We fixed an issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="66433-249">Se ha corregido un problema que impedía guardar los cambios que se realizaran a la firma de un usuario.</span><span class="sxs-lookup"><span data-stu-id="66433-249">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


- <span data-ttu-id="66433-250">Se ha corregido un problema que hacía que Outlook creara una segunda firma vacía para las personas que tuvieran habilitada la configuración de la nube.</span><span class="sxs-lookup"><span data-stu-id="66433-250">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="66433-251">Hemos corregido un problema que causaba errores al mostrar la firma predeterminada correcta en OWA.</span><span class="sxs-lookup"><span data-stu-id="66433-251">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="66433-252">Hemos corregido un problema que provocaba que las firmas con contenido Unicode se dañasen.</span><span class="sxs-lookup"><span data-stu-id="66433-252">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="66433-253">Hemos corregido un problema que causaba que los usuarios de traducción directa no pudieran enviar comentarios.</span><span class="sxs-lookup"><span data-stu-id="66433-253">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="66433-254">Se ha corregido un problema que provocaba que los encabezados de mensajes en chino no se pudieran leer al responder o reenviar.</span><span class="sxs-lookup"><span data-stu-id="66433-254">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="66433-255">Se ha corregido un problema que provocaba que los caracteres chinos se cambiaran a signos de interrogación al guardar como archivo OFT.</span><span class="sxs-lookup"><span data-stu-id="66433-255">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="66433-256">Se ha agregado una clave de registro que permite a los clientes deshabilitar la inclusión de hora de archivo para los datos adjuntos en las operaciones de IDataObject (es decir, arrastrar y soltar, portapapeles).</span><span class="sxs-lookup"><span data-stu-id="66433-256">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="66433-257">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="66433-257">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span>  <span data-ttu-id="66433-258">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="66433-258">REG_DWORD IncludeFileTimesInDataObject.</span></span>  <span data-ttu-id="66433-259">0 = se excluyen horas de archivo.</span><span class="sxs-lookup"><span data-stu-id="66433-259">0 = filetimes are excluded.</span></span>  <span data-ttu-id="66433-260">1 = (predeterminado) se incluyen horas de archivo.</span><span class="sxs-lookup"><span data-stu-id="66433-260">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="66433-261">Se ha corregido un problema que provocaba que las imágenes en línea desaparecieran al responder a un mensaje con una etiqueta de protección de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="66433-261">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="66433-262">Hemos corregido un problema que hacía que no se mostrara el icono de cifrado de los correos electrónicos enviados con la opción de solo cifrado.</span><span class="sxs-lookup"><span data-stu-id="66433-262">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>


- <span data-ttu-id="66433-263">Hemos corregido un problema por el que los mensajes de correo electrónico se enviaban como firmados digitalmente después de que el usuario desactivara esa opción.</span><span class="sxs-lookup"><span data-stu-id="66433-263">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="66433-264">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66433-264">PowerPoint</span></span>

- <span data-ttu-id="66433-265">Se ha corregido un problema que podía provocar que la aplicación se cerrara de forma inesperada cuando se producía un error al guardar un documento.</span><span class="sxs-lookup"><span data-stu-id="66433-265">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="66433-266">Se ha corregido un problema relacionado con la función de copiar y pegar una ecuación de Word a PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="66433-266">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="66433-267">Este cambio resuelve un problema con el relleno de rutas al aplicar las operaciones de Combinar formas con determinadas geometrías.</span><span class="sxs-lookup"><span data-stu-id="66433-267">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="66433-268">Este cambio soluciona un problema que impedía mostrar correctamente fuentes en ecuaciones.</span><span class="sxs-lookup"><span data-stu-id="66433-268">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="66433-269">Este cambio resuelve un problema con el control de errores que se pueden producir durante la carga de vídeo.</span><span class="sxs-lookup"><span data-stu-id="66433-269">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="66433-270">Se ha corregido un problema de VBA por el que Slide.Shapes.AddMediaObject2 se cerraba inesperadamente con formatos de vídeo heredados (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="66433-270">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="66433-271">Se ha corregido un problema por el que el comando tamaño de fuente, agregado a la herramienta de acceso rápido, se completaba automáticamente al tamaño de fuente definido más cercano al actualizarse.</span><span class="sxs-lookup"><span data-stu-id="66433-271">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="66433-272">Se ha corregido un problema que provocaba un error al guardar el archivo después de duplicar una diapositiva que contuviera un audio grabado recientemente.</span><span class="sxs-lookup"><span data-stu-id="66433-272">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="66433-273">Se ha corregido un problema en el que el complemento de contenido de formularios no se reproducía después de la inserción hasta que el usuario hiciera clic en otra diapositiva para hacer que aparezca.</span><span class="sxs-lookup"><span data-stu-id="66433-273">We fixed an issue where Forms content add-in doesn't render after insertion until user clicks to another slide to make it show.</span></span>


- <span data-ttu-id="66433-274">Corregido un problema que deshabilita las protecciones IRM al abrir un archivo de PowerPoint en la Vista protegida.</span><span class="sxs-lookup"><span data-stu-id="66433-274">We fixed an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="66433-275">Se ha corregido un problema que provocaba la coautoría lenta en archivos que contienen números grandes de determinados tipos de objetos de datos (E2o).</span><span class="sxs-lookup"><span data-stu-id="66433-275">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


- <span data-ttu-id="66433-276">Corrección de un problema al usar IRM o documentos protegidos durante un error de combinación.</span><span class="sxs-lookup"><span data-stu-id="66433-276">Fix to address a an issue when using IRM/protected documents during a merge error.</span></span>


- <span data-ttu-id="66433-277">Esta es una solución para un problema por el que se muestra la solicitud de guardar en un bucle al cerrar el documento cuando hay un complemento que escucha al evento PresentationBeforeClose y comprueba la propiedad Presentation.Saved como parte del controlador de eventos.</span><span class="sxs-lookup"><span data-stu-id="66433-277">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


- <span data-ttu-id="66433-278">Se ha corregido un problema que evitaba que algunos archivos de PowerPoint corruptos se abrieran correctamente, incluso después de la operación de reparación de un documento.</span><span class="sxs-lookup"><span data-stu-id="66433-278">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="66433-279">Corrige un problema que hacía que, en algunos casos, se elimina la etiqueta de Clasificación de datos al seleccionar una idea de diseño.</span><span class="sxs-lookup"><span data-stu-id="66433-279">Addresses an issue where selecting a Design Idea removes the presentation's Data Classification Label, in certain cases.</span></span>


### <a name="project"></a><span data-ttu-id="66433-280">Project</span><span class="sxs-lookup"><span data-stu-id="66433-280">Project</span></span>

- <span data-ttu-id="66433-281">Se ha corregido un problema que provocaba que, al guardar un proyecto desde PWA en un archivo MPP local, ProjectBeforeTaskChangeEvent se desencadenara para datos no modificados por el usuario.</span><span class="sxs-lookup"><span data-stu-id="66433-281">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="66433-282">Se ha corregido un problema que causaba que NewVal en el evento ProjectBeforeTaskChange no tuviera el valor correcto si se cambiaba un retraso en una vista de tipo de formulario de tarea.</span><span class="sxs-lookup"><span data-stu-id="66433-282">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="66433-283">Se ha corregido un problema por el que si se ejecuta un código de evento y se intenta realizar cambios desde la vista del Formulario de tareas, es posible que el botón Aceptar no confirme los cambios.</span><span class="sxs-lookup"><span data-stu-id="66433-283">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="66433-284">Se ha corregido un problema que podía hacer que Project se cerrara de manera inesperada al abrir archivos en los que se especificaban los contornos de los recursos de una determinada manera.</span><span class="sxs-lookup"><span data-stu-id="66433-284">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="66433-285">Se ha corregido un problema por el que algunos proyectos específicos podrían abrirse si había un problema con el archivo del proyecto en una parte específica de la carga.</span><span class="sxs-lookup"><span data-stu-id="66433-285">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


- <span data-ttu-id="66433-286">Se ha corregido un problema en el que los bordes no se mostraban para las tareas en la vista Organizador de equipo.</span><span class="sxs-lookup"><span data-stu-id="66433-286">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="66433-287">Se ha corregido un problema en el que la opción de arrastrar y colocar no funcionaba para las tareas de la vista Organizador de equipo.</span><span class="sxs-lookup"><span data-stu-id="66433-287">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="66433-288">Se corrigió un problema que provocaba que, cuando se asignaba un recurso de costo a una tarea hito, el costo de línea base no se acumulara correctamente.</span><span class="sxs-lookup"><span data-stu-id="66433-288">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


### <a name="visio"></a><span data-ttu-id="66433-289">Visio</span><span class="sxs-lookup"><span data-stu-id="66433-289">Visio</span></span>

- <span data-ttu-id="66433-290">Se ha corregido un problema que provocaba que los usuarios pudieran crear líneas rectas con conectores en Visio para Office 365, tanto para las galerías personalizadas de símbolos de Visio como para las plantillas predefinidas.</span><span class="sxs-lookup"><span data-stu-id="66433-290">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="66433-291">Word</span><span class="sxs-lookup"><span data-stu-id="66433-291">Word</span></span>

- <span data-ttu-id="66433-292">Se ha corregido un problema que podía provocar que la aplicación se cerrara de forma inesperada cuando se producía un error al guardar un documento.</span><span class="sxs-lookup"><span data-stu-id="66433-292">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="66433-293">Se ha corregido un problema relacionado con la función de copiar y pegar una ecuación de Word a PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="66433-293">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="66433-294">Este cambio resuelve un problema con el cursor al editar un documento.</span><span class="sxs-lookup"><span data-stu-id="66433-294">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="66433-295">Soluciona un problema con los colores aplicados a los efectos en 3D y a los gráficos SVG.</span><span class="sxs-lookup"><span data-stu-id="66433-295">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="66433-296">Hemos corregido un problema por el que el Narrador podía omitir un párrafo.</span><span class="sxs-lookup"><span data-stu-id="66433-296">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="66433-297">Hemos corregido un problema con los controles de contenido de texto enriquecido.</span><span class="sxs-lookup"><span data-stu-id="66433-297">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="66433-298">Hemos corregido un problema con el cuadro de diálogo Galería de estilos.</span><span class="sxs-lookup"><span data-stu-id="66433-298">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="66433-299">Hemos corregido un problema para resolver conflictos en coautoría.</span><span class="sxs-lookup"><span data-stu-id="66433-299">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


- <span data-ttu-id="66433-300">Hemos corregido un problema que reemplazaba los estilos del documento con otros estilos de la plantilla.</span><span class="sxs-lookup"><span data-stu-id="66433-300">We fixed an issue which document styles are replaced with other styles from the template.</span></span>


- <span data-ttu-id="66433-301">Se ha corregido un error de aserción expuesto por puertas optimizadas que afectaba a Word.</span><span class="sxs-lookup"><span data-stu-id="66433-301">Fix an assert bug exposed by optimized gates affecting Word.</span></span>


### <a name="office-suite"></a><span data-ttu-id="66433-302">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="66433-302">Office Suite</span></span>

- <span data-ttu-id="66433-303">Se ha corregido un problema que provocaba un error al intentar guardar archivos que habían pasado de sincronizados a solo en el servidor.</span><span class="sxs-lookup"><span data-stu-id="66433-303">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>


- <span data-ttu-id="66433-304">Corregido un problema que producía un error al intentar Guardar como en ciertos escenarios.</span><span class="sxs-lookup"><span data-stu-id="66433-304">Fixed an issue where trying to do a SaveAs would fail in certain scenarios.</span></span>


- <span data-ttu-id="66433-305">Hemos corregido un problema que provocaba que SaveRequestManagerCam causara que la aplicación se cerrara en lugar de devolver un error.</span><span class="sxs-lookup"><span data-stu-id="66433-305">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span>


- <span data-ttu-id="66433-306">Se ha corregido la secuencia de cierre de archivos para que todos los componentes interdependientes se cierren correctamente.</span><span class="sxs-lookup"><span data-stu-id="66433-306">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>


- <span data-ttu-id="66433-307">Se ha corregido un problema por el que un archivo se abría como NO SyncBacked cuando la dirección URL de la memoria caché y la dirección URL de OneDrive NO coincidían.</span><span class="sxs-lookup"><span data-stu-id="66433-307">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>


- <span data-ttu-id="66433-308">Se está corrigiendo un problema que hacía que copiar y pegar en los mensajes de Skype Empresarial hacía que se mostrara el siguiente aviso: "Se ha producido un error al pegar el contenido".</span><span class="sxs-lookup"><span data-stu-id="66433-308">Fixing a bug where copy/paste in Skype for Business messages resulted in a dialog displaying "Something went wrong when pasting your content".</span></span>


- <span data-ttu-id="66433-309">Se ha corregido un problema que provocaba que se produjera un error al copiar o pegar texto de un comentario en Excel.</span><span class="sxs-lookup"><span data-stu-id="66433-309">Fixed an issue where an error would occur when copy/paste text from a comment into Excel</span></span>


- <span data-ttu-id="66433-310">Corrige un bloqueo al usar un narrador sin un texto con ecuaciones matemáticas.</span><span class="sxs-lookup"><span data-stu-id="66433-310">Fix a crash that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="66433-311">Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan toners</span><span class="sxs-lookup"><span data-stu-id="66433-311">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="66433-312">Cambiar mensaje para mostrar "tóner/Ink Low" & "no tóner/tinta".</span><span class="sxs-lookup"><span data-stu-id="66433-312">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="66433-313">Se ha corregido un problema por el que la instalación de una versión más reciente de Office sobre algunas versiones anteriores podía resultar en un deterioro de la funcionalidad (por ejemplo, la imposibilidad de usar Power Query) debido a la falta de entradas del registro.</span><span class="sxs-lookup"><span data-stu-id="66433-313">Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>


- <span data-ttu-id="66433-314">Se ha corregido un problema por el que la prevención de pérdida de datos de Microsoft 365 Endpoint no pudo clasificar documentos de Office en disco.</span><span class="sxs-lookup"><span data-stu-id="66433-314">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


- <span data-ttu-id="66433-315">Hemos corregido un problema con el cuadro de diálogo de Comprimir imagen, que no retiene determinadas configuraciones de usuario.</span><span class="sxs-lookup"><span data-stu-id="66433-315">We fixed an issue with the Compress Picture dialog not retaining certain user settings.</span></span>


- <span data-ttu-id="66433-316">Soluciona un problema relacionado con las notificaciones de eventos del controlador multimedia.</span><span class="sxs-lookup"><span data-stu-id="66433-316">Fixes an issue related to media controller event notifications.</span></span>


- <span data-ttu-id="66433-317">Soluciona un problema relacionado con los intervalos de los motores del reproductor multimedia.</span><span class="sxs-lookup"><span data-stu-id="66433-317">Fixes an issue related to media player engine timing.</span></span>


- <span data-ttu-id="66433-318">Tamaño binario optimizado.</span><span class="sxs-lookup"><span data-stu-id="66433-318">Optimized binary size.</span></span>


- <span data-ttu-id="66433-319">Anaheim WebView aún no es compatible con Windows Information Protection.</span><span class="sxs-lookup"><span data-stu-id="66433-319">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="66433-320">Con esta corrección, la plataforma de complementos de Office retrocede al nivel inferior de WebView en un entorno habilitado para WIP.</span><span class="sxs-lookup"><span data-stu-id="66433-320">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="66433-321">Según el entorno de máquina del cliente, esto puede ser Edge Spartan WebView o Trident WebView.</span><span class="sxs-lookup"><span data-stu-id="66433-321">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="66433-322">Las vistas previas de nivel inferior son compatibles con WIP.</span><span class="sxs-lookup"><span data-stu-id="66433-322">Both down level WebViews support WIP.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-february-09"></a><span data-ttu-id="66433-324">Versión 2008: 09 de febrero</span><span class="sxs-lookup"><span data-stu-id="66433-324">Version 2008: February 09</span></span>
<span data-ttu-id="66433-325">*Versión 2008 (compilación 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="66433-325">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="66433-326">Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="66433-326">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="66433-328">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="66433-328">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="66433-329">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-329">Excel</span></span>

- <span data-ttu-id="66433-330">Se ha corregido un problema por el que Excel se cerraba inesperadamente al abrir archivos UNC con atributos de archivo no válidos (hora de creación, fecha de modificación, etc.).</span><span class="sxs-lookup"><span data-stu-id="66433-330">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="66433-331">Hemos corregido un problema por el que la configuración de los separadores decimales y de millares no se mantenía al copiar un gráfico de Excel y pegarlo en Word o PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="66433-331">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="66433-332">Hemos corregido un problema por el que el rendimiento de ejecutar una macro que implicaba el formato de rango de tabla dinámica sería peor cada vez que se ejecutase la macro.</span><span class="sxs-lookup"><span data-stu-id="66433-332">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="66433-333">Hemos corregido un problema por el que se eliminaron las reglas de formato condicional al copiar o mover hojas a otro libro.</span><span class="sxs-lookup"><span data-stu-id="66433-333">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="66433-334">Hemos corregido un problema por el que los usuarios no podían aplicar etiquetas de confidencialidad a los archivos de Excel cuando la pantalla de inicio de la aplicación estaba deshabilitada.</span><span class="sxs-lookup"><span data-stu-id="66433-334">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="66433-335">Hemos corregido un problema al abrir archivos en la nube de la carpeta de sincronización de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="66433-335">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="66433-336">Outlook</span><span class="sxs-lookup"><span data-stu-id="66433-336">Outlook</span></span>

- <span data-ttu-id="66433-337">Resuelto un problema que hacía que Outlook dejara de funcionar esporádicamente al agregar o guardar datos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="66433-337">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="66433-338">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66433-338">PowerPoint</span></span>

- <span data-ttu-id="66433-339">Se ha corregido un problema por el que el comando tamaño de fuente, agregado a la herramienta de acceso rápido, se completaba automáticamente al tamaño de fuente definido más cercano al actualizarse.</span><span class="sxs-lookup"><span data-stu-id="66433-339">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="66433-340">Se ha corregido un problema que causaba que, al copiar y pegar una diapositiva con la opción "Mantener formato de origen", a veces se copiara de forma inesperada sobre un nuevo patrón de diapositivas.</span><span class="sxs-lookup"><span data-stu-id="66433-340">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="66433-341">Word</span><span class="sxs-lookup"><span data-stu-id="66433-341">Word</span></span>

- <span data-ttu-id="66433-342">Corregimos un problema en control de cambios que a veces es posible que abra un documento de Word.</span><span class="sxs-lookup"><span data-stu-id="66433-342">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="66433-343">Hemos corregido un problema al abrir archivos en la nube de la carpeta de sincronización de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="66433-343">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="66433-344">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="66433-344">Office Suite</span></span>

- <span data-ttu-id="66433-345">Se ha corregido un problema que impedía abrir correctamente un archivo en Office.</span><span class="sxs-lookup"><span data-stu-id="66433-345">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="66433-346">Se ha corregido un problema por el que los documentos que contenían contornos esbozados aplicados a conectores a través de Copiar formato podrían dañarse.</span><span class="sxs-lookup"><span data-stu-id="66433-346">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-january-12"></a><span data-ttu-id="66433-348">Versión 2008: 12 de enero</span><span class="sxs-lookup"><span data-stu-id="66433-348">Version 2008: January 12</span></span>
<span data-ttu-id="66433-349">*Versión 2008 (compilación 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="66433-349">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="66433-350">Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="66433-350">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="66433-352">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="66433-352">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="66433-353">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-353">Excel</span></span>

- <span data-ttu-id="66433-354">Se ha corregido un problema por el que los libros de solo lectura dejaban de actualizar los datos de las tablas dinámicas al abrirlos.</span><span class="sxs-lookup"><span data-stu-id="66433-354">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="66433-355">Este cambio corrige el siguiente problema: "Insertar objeto" de Excel no muestra el icono correcto cuando se inserta un archivo desde la carpeta de sincronización local de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="66433-355">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="66433-356">Se ha corregido un problema por el que los clientes recibían una notificación incorrecta sobre una nueva versión del archivo durante la coautoría.</span><span class="sxs-lookup"><span data-stu-id="66433-356">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="66433-357">Se ha corregido un problema de edición por el que al usar IME con el modo de sobrescritura se avanzaban incorrectamente caracteres adicionales.</span><span class="sxs-lookup"><span data-stu-id="66433-357">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="66433-358">Se ha corregido un problema que se producía al usar datos en tiempo real junto con la funcionalidad de recálculo multiproceso.</span><span class="sxs-lookup"><span data-stu-id="66433-358">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="66433-359">Corrige un problema por el que Excel no se iniciaba o se cerraba inesperadamente si se estaba usando cierta configuración de protección contra vulnerabilidades de Seguridad de Windows (SimExec, CallerCheck).</span><span class="sxs-lookup"><span data-stu-id="66433-359">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="66433-360">Outlook</span><span class="sxs-lookup"><span data-stu-id="66433-360">Outlook</span></span>

- <span data-ttu-id="66433-361">Se ha corregido un problema que provocaba que SmartLinks perdiera el formato cuando se guardaba en Borradores.</span><span class="sxs-lookup"><span data-stu-id="66433-361">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="66433-362">Se ha corregido un problema para proporcionar a los usuarios una forma de personalizar el texto de justificación al anular una directiva.</span><span class="sxs-lookup"><span data-stu-id="66433-362">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="66433-363">Se ha corregido un problema que provocaba que los caracteres chinos se cambiaran a signos de interrogación al guardar como archivo OFT.</span><span class="sxs-lookup"><span data-stu-id="66433-363">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="66433-364">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66433-364">PowerPoint</span></span>

- <span data-ttu-id="66433-365">Se ha corregido un problema de VBA por el que Slide.Shapes.AddMediaObject2 se cerraba inesperadamente con formatos de vídeo heredados (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="66433-365">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="66433-366">Se ha corregido un problema que evitaba que algunos archivos de PowerPoint corruptos se abrieran correctamente, incluso después de la operación de reparación de un documento.</span><span class="sxs-lookup"><span data-stu-id="66433-366">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="66433-367">Project</span><span class="sxs-lookup"><span data-stu-id="66433-367">Project</span></span>

- <span data-ttu-id="66433-368">Corregimos un problema por el que el Proyecto puede finalizar inesperadamente al abrir archivos en los que se especificaban los contornos de los recursos de una determinada manera.</span><span class="sxs-lookup"><span data-stu-id="66433-368">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="66433-369">Skype</span><span class="sxs-lookup"><span data-stu-id="66433-369">Skype</span></span>

- <span data-ttu-id="66433-370">Se ha corregido un problema por el que el certificado TLS-DSK de un usuario no se renovaba en el momento esperado, solo se renovaba cuando le quedaban menos de 12 horas de validez.</span><span class="sxs-lookup"><span data-stu-id="66433-370">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="66433-371">Se ha corregido un problema por el que la interfaz de usuario de Skype Empresarial se mostraba en blanco tras iniciar sesión si todavía no se tenía la licencia de Office.</span><span class="sxs-lookup"><span data-stu-id="66433-371">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="66433-372">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="66433-372">Office Suite</span></span>

- <span data-ttu-id="66433-373">Este cambio soluciona un problema relacionado con la apertura de archivos que contienen diagramas heredados.</span><span class="sxs-lookup"><span data-stu-id="66433-373">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="66433-374">Este cambio soluciona un problema con proxy de reserva de SVG que provocaba infracciones de acceso.</span><span class="sxs-lookup"><span data-stu-id="66433-374">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO FINAL)

## <a name="version-2008-december-08"></a><span data-ttu-id="66433-376">Versión 2008: 08 de diciembre</span><span class="sxs-lookup"><span data-stu-id="66433-376">Version 2008: December 08</span></span>
<span data-ttu-id="66433-377">*Versión 2008 (Compilación 13127.20910)*</span><span class="sxs-lookup"><span data-stu-id="66433-377">*Version 2008 (Build 13127.20910)*</span></span>

<span data-ttu-id="66433-378">Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="66433-378">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="66433-380">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="66433-380">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="66433-381">Access</span><span class="sxs-lookup"><span data-stu-id="66433-381">Access</span></span>

- <span data-ttu-id="66433-382">Se ha corregido un problema de error al intentar usar el generador de DSN de ODBC</span><span class="sxs-lookup"><span data-stu-id="66433-382">We fixed an error issue when trying to use ODBC DSN builder</span></span>


### <a name="excel"></a><span data-ttu-id="66433-383">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-383">Excel</span></span>

- <span data-ttu-id="66433-384">Se ha corregido un problema que provocaba que las tablas dinámicas no se pudieran editar y los libros no se pudieran guardar si se exportaban desde el plan de Project.</span><span class="sxs-lookup"><span data-stu-id="66433-384">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="66433-385">Se ha corregido un problema que provocaba que, en algunos casos, aparecieran varias barras de mensajes al abrir un archivo en modo de solo lectura.</span><span class="sxs-lookup"><span data-stu-id="66433-385">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="66433-386">Se ha corregido un problema que provocaba que los subtotales de esquema pudieran dejar de funcionar cuando había muchos valores de encabezado de columna duplicados.</span><span class="sxs-lookup"><span data-stu-id="66433-386">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="66433-387">Se ha corregido un problema que provocaba que Excel dejara de funcionar cuando había una actualización del objeto de directiva de grupo (por ejemplo, mediante la actualización de la directiva de grupo remota) durante el recálculo multiproceso.</span><span class="sxs-lookup"><span data-stu-id="66433-387">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="66433-388">Se ha corregido un problema que provocaba que Excel dejara de funcionar cuando los usuarios utilizaban la función subtotal en más de 255 columnas.</span><span class="sxs-lookup"><span data-stu-id="66433-388">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="66433-389">Interletraje de texto mejorado en PowerPoint cuando se copia contenido de Excel y se pega en PowerPoint con la opción Insertar.</span><span class="sxs-lookup"><span data-stu-id="66433-389">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="66433-390">Se ha corregido un problema que impedía cambiar entre la vista previa de la tabla y el editor de consultas en PowerPivot.</span><span class="sxs-lookup"><span data-stu-id="66433-390">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="66433-391">Se ha corregido un problema que provocaba que el usuario no pudiera abrir el archivo atomsvc (UTF8+BOM) directamente desde SharePoint.</span><span class="sxs-lookup"><span data-stu-id="66433-391">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="66433-392">Se ha corregido un problema con Power Pivot. Ahora reconoce correctamente el delimitador de tabulaciones.</span><span class="sxs-lookup"><span data-stu-id="66433-392">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="outlook"></a><span data-ttu-id="66433-393">Outlook</span><span class="sxs-lookup"><span data-stu-id="66433-393">Outlook</span></span>

- <span data-ttu-id="66433-394">Se ha corregido un problema que provocaba que el campo "Para:" estuviera vacío al enviar un informe de estado en una tarea.</span><span class="sxs-lookup"><span data-stu-id="66433-394">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="66433-395">Se ha corregido un problema que provocaba que se interrumpiera el evento MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="66433-395">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="66433-396">Se ha corregido un problema que provocaba que algunos usuarios experimentaran el cierre inesperado de la aplicación Outlook al enviar correo desde aplicaciones diferentes de Outlook.</span><span class="sxs-lookup"><span data-stu-id="66433-396">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="66433-397">Se ha corregido un problema que provocaba que los usuarios experimentaran un rendimiento degradado al mover varios elementos de correo entre carpetas en el modo en línea.</span><span class="sxs-lookup"><span data-stu-id="66433-397">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="66433-398">Se ha agregado una clave de registro que permite a los clientes deshabilitar la inclusión de hora de archivo para los datos adjuntos en las operaciones de IDataObject (es decir, arrastrar y soltar, portapapeles).</span><span class="sxs-lookup"><span data-stu-id="66433-398">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="66433-399">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = horas de archivo están excluidas  1 = (determinado) horas de archivo están incluidas</span><span class="sxs-lookup"><span data-stu-id="66433-399">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="66433-400">Se ha corregido un problema que provocaba que las imágenes en línea desaparecieran al responder a un mensaje con una etiqueta de protección de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="66433-400">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="66433-401">Se ha corregido un problema que provocaba que el nombre de usuario se mostrara como un número de teléfono al enviar un correo de voz protegido de Azure, lo que provocaba que los usuarios de escritorio de Outlook no puedan abrir correos de voz de usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="66433-401">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="66433-402">Se ha corregido un problema que provocaba que, al configurar OME, se agregaban datos adjuntos extraños en el elemento de correo que obligaban a Outlook a cifrar el mensaje aunque la opción DecryptAttachmentsForEncryptOnly estuviera configurada en el lado del servicio.</span><span class="sxs-lookup"><span data-stu-id="66433-402">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="66433-403">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66433-403">PowerPoint</span></span>

- <span data-ttu-id="66433-404">Se ha corregido un problema que provocaba que el gráfico de Excel vinculado cambiara incorrectamente a la hoja de Excel cuando el usuario cambiaba la ruta de origen a la carpeta de OneDrive local.</span><span class="sxs-lookup"><span data-stu-id="66433-404">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="66433-405">Se ha corregido un problema que provocaba que la característica "Bienvenido de nuevo.</span><span class="sxs-lookup"><span data-stu-id="66433-405">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="66433-406">Retomar el trabajo donde lo dejó en la oficina" no funcionara en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="66433-406">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


### <a name="visio"></a><span data-ttu-id="66433-407">Visio</span><span class="sxs-lookup"><span data-stu-id="66433-407">Visio</span></span>

- <span data-ttu-id="66433-408">Se ha corregido un problema que provocaba que los usuarios pudieran crear líneas rectas con conectores en Visio para Office 365, tanto para las galerías personalizadas de símbolos de Visio como para las plantillas predefinidas.</span><span class="sxs-lookup"><span data-stu-id="66433-408">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="66433-409">Word</span><span class="sxs-lookup"><span data-stu-id="66433-409">Word</span></span>

- <span data-ttu-id="66433-410">Se corrigió un problema que provocaba que los vínculos largos no se ajustaran al guardar un documento en formato HTML.</span><span class="sxs-lookup"><span data-stu-id="66433-410">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="66433-411">Se ha corregido un problema que provocaba que, si se respondía a un comentario primario que tenía extensiones desconocidas en una lista de extensiones, la respuesta obtuviera esas mismas extensiones.</span><span class="sxs-lookup"><span data-stu-id="66433-411">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="66433-412">Se ha corregido un problema con Outlook al establecer un mensaje en No reenviar</span><span class="sxs-lookup"><span data-stu-id="66433-412">We fixed an issue with Outlook with message set to Do not forward.</span></span>


### <a name="office-suite"></a><span data-ttu-id="66433-413">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="66433-413">Office Suite</span></span>

- <span data-ttu-id="66433-414">Soluciona un problema que impedía que los usuarios importaran listas de SPO cuando se deshabilitaba ADAL.</span><span class="sxs-lookup"><span data-stu-id="66433-414">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-november-10"></a><span data-ttu-id="66433-416">Versión 2008: 10 de julio</span><span class="sxs-lookup"><span data-stu-id="66433-416">Version 2008: November 10</span></span>
<span data-ttu-id="66433-417">*La versión prevista es la versión 2008 (compilación 13127.20760).*</span><span class="sxs-lookup"><span data-stu-id="66433-417">*Version 2008 (Build 13127.20760)*</span></span>

<span data-ttu-id="66433-418">Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="66433-418">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="66433-420">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="66433-420">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="66433-421">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-421">Excel</span></span>

- <span data-ttu-id="66433-422">Se ha corregido un problema por el que algunas funciones podían tener un resultado incorrecto después de cargar un libro.</span><span class="sxs-lookup"><span data-stu-id="66433-422">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="66433-423">Se ha corregido un problema relacionado con las referencias de complemento de XLAM y los rangos con nombre que cerraba la aplicación de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="66433-423">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="66433-424">Se ha corregido un problema por el que, al usar una macro para establecer la propiedad FormulaR1C1 para un rango, las referencias de celda eran incorrectas si una hoja de gráfico era la hoja activa.</span><span class="sxs-lookup"><span data-stu-id="66433-424">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="66433-425">Se ha corregido un problema por el que Excel indicaba por error que se había quedado sin recursos al intentar calcular una o varias fórmulas.</span><span class="sxs-lookup"><span data-stu-id="66433-425">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="66433-426">Se ha corregido un problema que aparecía cuando se configuraba el idioma de Office en español. Este problema provocaba que las listas de validación de datos puedan no mostrar todos los elementos de la lista.</span><span class="sxs-lookup"><span data-stu-id="66433-426">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="66433-427">Se ha corregido un problema que podía producir un bloqueo al actualizar las tablas dinámicas de OLAP.</span><span class="sxs-lookup"><span data-stu-id="66433-427">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>

### <a name="outlook"></a><span data-ttu-id="66433-428">Outlook</span><span class="sxs-lookup"><span data-stu-id="66433-428">Outlook</span></span>

- <span data-ttu-id="66433-429">Se ha corregido un problema por el que los usuarios ahora pueden deshabilitar IRM (Information Rights Management) para Outlook sin tener que deshabilitarlo para el resto de las aplicaciones de Office.</span><span class="sxs-lookup"><span data-stu-id="66433-429">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="66433-430">Se ha corregido un problema que provocaba que los usuarios no pudieran conceder permisos de editor a los delegados.</span><span class="sxs-lookup"><span data-stu-id="66433-430">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="66433-431">Se ha corregido un problema que provocaba que la aplicación finalizara de forma abrupta cuando el cliente seleccionaba un resultado de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="66433-431">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="66433-432">Se ha corregido un problema que provocaba que las búsquedas en calendarios de Grupo no dieran resultados.</span><span class="sxs-lookup"><span data-stu-id="66433-432">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="66433-433">Corregido un problema que causaba que los delegados sufrieran errores intermitentemente al abrir carpetas compartidas en otro buzón.</span><span class="sxs-lookup"><span data-stu-id="66433-433">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="66433-434">Corregido un problema que causaba que se enviaran algunos mensajes de correo electrónico generados automáticamente con el cuerpo en blanco cuando la línea del asunto estaba también en blanco.</span><span class="sxs-lookup"><span data-stu-id="66433-434">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="66433-435">Se ha corregido un problema que provocaba que los encabezados de mensajes en chino fueran ilegibles al responder o reenviar.</span><span class="sxs-lookup"><span data-stu-id="66433-435">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>

- <span data-ttu-id="66433-436">Se ha corregido un problema por el que las experiencias opcionales conectadas bloqueaban la carga de los complementos web.</span><span class="sxs-lookup"><span data-stu-id="66433-436">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <br /><span data-ttu-id="66433-437">Ver detalles en la [entrada de blog](https://developer.microsoft.com/es-ES/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span><span class="sxs-lookup"><span data-stu-id="66433-437">See details in [blog post](https://developer.microsoft.com/es-ES/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span></span>


### <a name="powerpoint"></a><span data-ttu-id="66433-438">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66433-438">PowerPoint</span></span>

- <span data-ttu-id="66433-439">Se ha corregido un problema en el que el complemento de contenido de formularios no se reproducía después de la inserción hasta que el usuario hiciera clic en otra diapositiva para hacer que aparezca.</span><span class="sxs-lookup"><span data-stu-id="66433-439">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


### <a name="office-suite"></a><span data-ttu-id="66433-440">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="66433-440">Office Suite</span></span>

- <span data-ttu-id="66433-441">Se ha atendido un problema para los clientes comerciales que usan el System Center Configuration Manager u otras herramientas de administración para Office Update mediante la prevención de pérdida de datos del punto de conexión de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="66433-441">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>

- <span data-ttu-id="66433-442">Corrección de un problema por el que no funcionaba la API de mensajería para los complementos de Office.</span><span class="sxs-lookup"><span data-stu-id="66433-442">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>



[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2008-october-13"></a><span data-ttu-id="66433-444">Versión 2008: 13 de octubre</span><span class="sxs-lookup"><span data-stu-id="66433-444">Version 2008: October 13</span></span>
<span data-ttu-id="66433-445">*Versión 2008 (compilación 13127.20638)*</span><span class="sxs-lookup"><span data-stu-id="66433-445">*Version 2008 (Build 13127.20638)*</span></span>

<span data-ttu-id="66433-446">Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="66433-446">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="66433-448">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="66433-448">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="66433-449">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-449">Excel</span></span>

- <span data-ttu-id="66433-450">Se ha corregido un error con las API de PivotDateFilter en el que las condiciones de filtro 'Antes' y 'Después' se revertían.</span><span class="sxs-lookup"><span data-stu-id="66433-450">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="66433-451">Se corrigió un problema por el cual los usuarios no podían modificar un filtro de tabla dinámica porque estaba configurado en un valor que ya no estaba presente en una base de datos de Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="66433-451">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="66433-452">Se ha corregido un problema que provocaba que Excel se bloqueara al usar el Análisis rápido después de inmovilizar la fila superior de la hoja.</span><span class="sxs-lookup"><span data-stu-id="66433-452">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="66433-453">Se ha corregido un problema que podía producir una advertencia acerca de un libro dañado si contenía fórmulas que usan SI.ND.</span><span class="sxs-lookup"><span data-stu-id="66433-453">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="66433-454">Outlook</span><span class="sxs-lookup"><span data-stu-id="66433-454">Outlook</span></span>

- <span data-ttu-id="66433-455">Corrige un problema que provocaba que los usuarios no pudieran cerrar los calendarios compartidos haciendo clic en la "X" de la esquina.</span><span class="sxs-lookup"><span data-stu-id="66433-455">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="66433-456">Corrige un problema que causaba que la configuración "Activar las mejoras del calendario compartido" en ocasiones no se pudiera aplicar a los calendarios compartidos existentes.</span><span class="sxs-lookup"><span data-stu-id="66433-456">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="66433-457">Corrige un problema que provocaba que los usuarios vieran un error en la página de vínculos seguros en lugar del documento que intentaban abrir al abrir un archivo adjunto en la nube.</span><span class="sxs-lookup"><span data-stu-id="66433-457">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="66433-458">Corrige un problema de rendimiento con la carga de archivos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="66433-458">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="66433-459">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66433-459">PowerPoint</span></span>

- <span data-ttu-id="66433-460">Este cambio corrige un problema relacionado con la característica Exportar a GIF animado, en la que no se exporta al hacer clic en el botón Exportar.</span><span class="sxs-lookup"><span data-stu-id="66433-460">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="66433-461">Corrección de seguridad para solucionar un problema que deshabilita las protecciones IRM al abrir un archivo de PowerPoint en la Vista protegida.</span><span class="sxs-lookup"><span data-stu-id="66433-461">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>

- <span data-ttu-id="66433-462">Se ha corregido un problema en la configuración de la Acción que provocaba un bloqueo en la aplicación PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="66433-462">We have fixed an issue in Action Settings dialog which was causing a crash in PowerPoint app.</span></span>

### <a name="visio"></a><span data-ttu-id="66433-463">Visio</span><span class="sxs-lookup"><span data-stu-id="66433-463">Visio</span></span>

- <span data-ttu-id="66433-464">Se ha corregido un problema que provocaba que la Vista previa en directo se bloqueara en la alineación del texto.</span><span class="sxs-lookup"><span data-stu-id="66433-464">We fixed an issue that caused the Live preview to crash on text alignment.</span></span>


### <a name="word"></a><span data-ttu-id="66433-465">Word</span><span class="sxs-lookup"><span data-stu-id="66433-465">Word</span></span>

- <span data-ttu-id="66433-466">Corrige un problema que provocaba que los usuarios experimentaran un bloqueo al abrir algunos correos electrónicos muy grandes.</span><span class="sxs-lookup"><span data-stu-id="66433-466">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="66433-467">Se ha corregido un problema por el que el usuario podría experimentar un error al abrir un documento.</span><span class="sxs-lookup"><span data-stu-id="66433-467">We fixed an issue which user might experience crash when opening a document.</span></span>


- <span data-ttu-id="66433-468">Se ha corregido un problema que podía provocar un bloqueo al iniciar Word.</span><span class="sxs-lookup"><span data-stu-id="66433-468">Resolved an issue that may have caused a crash when booting Word.</span></span>


- <span data-ttu-id="66433-469">Se ha corregido un problema con el cuadro de diálogo Galería de estilos.</span><span class="sxs-lookup"><span data-stu-id="66433-469">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="66433-470">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="66433-470">Office Suite</span></span>

- <span data-ttu-id="66433-471">Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan toners</span><span class="sxs-lookup"><span data-stu-id="66433-471">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="66433-472">Cambiar mensaje para mostrar "tóner/Ink Low" & "no tóner/tinta".</span><span class="sxs-lookup"><span data-stu-id="66433-472">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="66433-473">Corrige el uso elevado de la CPU en modo inactivo con un GIF o un modelo 3D animado</span><span class="sxs-lookup"><span data-stu-id="66433-473">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="66433-474">Este cambio corrige un bloqueo al iniciar las aplicaciones de Office debido a un error al cargar d2d1.dll.</span><span class="sxs-lookup"><span data-stu-id="66433-474">This change addresses a crash when launching Office apps due to failing to load d2d1.dll.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO FINAL)

## <a name="version-2008-september-08"></a><span data-ttu-id="66433-476">Versión 2008: 08 de septiembre</span><span class="sxs-lookup"><span data-stu-id="66433-476">Version 2008: September 08</span></span>
<span data-ttu-id="66433-477">*Versión 2008 (Compilación 13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="66433-477">*Version 2008 (Build 13127.20408)*</span></span>

<span data-ttu-id="66433-478">Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="66433-478">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="66433-480">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="66433-480">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="66433-481">Access</span><span class="sxs-lookup"><span data-stu-id="66433-481">Access</span></span>

- <span data-ttu-id="66433-482">**Aumente su productividad con el Diseñador de consultas, la vista SQL y la ventana Relaciones:** haga clic con el botón derecho en una tabla para abrirla, diseñarla, cambiar su tamaño y ocultarla.</span><span class="sxs-lookup"><span data-stu-id="66433-482">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="66433-483">Buscar y reemplazar texto en la vista SQL.</span><span class="sxs-lookup"><span data-stu-id="66433-483">Search and replace text in SQL View.</span></span> <span data-ttu-id="66433-484">Seleccione múltiples tablas en la ventana Relaciones.</span><span class="sxs-lookup"><span data-stu-id="66433-484">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="66433-485">**Agregue tablas con menos clics:** utilizar el panel de tareas agregar tablas, que permanece abierto mientras trabaja, para agregar tablas a relaciones y consultas.</span><span class="sxs-lookup"><span data-stu-id="66433-485">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="66433-486">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-486">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="66433-487">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-487">Excel</span></span>

- <span data-ttu-id="66433-488">**Gráficos de mapa mejorados:** hemos integrado los gráficos de mapa con los tipos de datos geográficos de Excel, para que revelen información de todo tipo sobre las ubicaciones que desee.</span><span class="sxs-lookup"><span data-stu-id="66433-488">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="66433-489">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-489">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="66433-490">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="66433-490">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="66433-491">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="66433-491">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="66433-492">**Crear tablas dinámicas de conjuntos de datos en Power BI desde Excel:** puede crear tablas dinámicas en Excel conectadas a los conjuntos de datos almacenados en Power BI con tan solo unos clics.</span><span class="sxs-lookup"><span data-stu-id="66433-492">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="66433-493">Así, podrá obtener lo mejor de las tablas dinámicas y de Power BI.</span><span class="sxs-lookup"><span data-stu-id="66433-493">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="66433-494">Calcule, resuma y analice sus datos con tablas dinámicas desde sus conjuntos de datos seguros de Power BI.</span><span class="sxs-lookup"><span data-stu-id="66433-494">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="66433-495">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-495">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="66433-496">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="66433-496">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="66433-497">**Sus funciones favoritas de Excel se han vuelto más rápidas:** las funciones SUMAR.SI.CONJUNTO, CONTAR.SI.CONJUNTO, PROMEDIO.SI.CONJUNTO, MAX.SI.CONJUNTO y MIN.SI.CONJUNTO son más rápidas que nunca.</span><span class="sxs-lookup"><span data-stu-id="66433-497">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="66433-498">Llegue al final más rápidamente.</span><span class="sxs-lookup"><span data-stu-id="66433-498">Get to the bottom line more quickly.</span></span> <span data-ttu-id="66433-499">Pruebe ahora una.</span><span class="sxs-lookup"><span data-stu-id="66433-499">Try one now.</span></span>

- <span data-ttu-id="66433-500">**Mejoras de RealTimeData (RTD):** En la versión Microsoft Office 365 2002 canal mensual y posterior, la función RealTimeData (RTD) de Excel es mucho más rápida que calcular datos en la hoja de cálculo en Excel 2010.</span><span class="sxs-lookup"><span data-stu-id="66433-500">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="66433-501">Hemos evitado atascos en su memoria subyacente y en las estructuras de datos, así como permitido el uso seguro de subprocesos para que se pueda calcular en todos los subprocesos disponibles de Recálculo multiproceso (MTR).</span><span class="sxs-lookup"><span data-stu-id="66433-501">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="66433-502">Outlook</span><span class="sxs-lookup"><span data-stu-id="66433-502">Outlook</span></span>

- <span data-ttu-id="66433-503">**Las actualizaciones del calendario compartido son más rápidas:** Outlook puede actualizar los calendarios compartidos en Office 365 con la API de REST.</span><span class="sxs-lookup"><span data-stu-id="66433-503">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="66433-504">Active la vista previa para obtener actualizaciones más rápidas y confiables en los calendarios compartidos.</span><span class="sxs-lookup"><span data-stu-id="66433-504">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="66433-505">**Mejores resultados, en un instante:** actualizamos la experiencia de búsqueda para que sea más inteligente, rápida y fiable que nunca.</span><span class="sxs-lookup"><span data-stu-id="66433-505">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="66433-506">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-506">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="66433-507">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="66433-507">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="66433-508">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="66433-508">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="66433-509">**Arrastre el correo electrónico a un grupo de tu propiedad:** Mueva y copie mensajes y conversaciones arrastrándolos desde su bandeja de entrada.</span><span class="sxs-lookup"><span data-stu-id="66433-509">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="66433-510">Los mensajes que arrastres serán compartidos con todos los miembros del grupo.</span><span class="sxs-lookup"><span data-stu-id="66433-510">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="66433-511">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span><span class="sxs-lookup"><span data-stu-id="66433-511">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="66433-512">**El calendario se transforma:** vea las actualizaciones visuales que hacen que el calendario sea más fácil de examinar.</span><span class="sxs-lookup"><span data-stu-id="66433-512">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="66433-513">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-513">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="66433-514">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="66433-514">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="66433-515">**Unirse a reuniones sin salir de la bandeja de entrada:** no es necesario cambiar al calendario para unirse a reuniones en línea.</span><span class="sxs-lookup"><span data-stu-id="66433-515">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="66433-516">Con el Calendario de Outlook anclado en el panel de tareas pendientes, únase a una reunión con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="66433-516">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span> [<span data-ttu-id="66433-517">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-517">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="66433-518">**Nueva experiencia para redes WiFi cautivas:** ¿alguna vez se ha unido a una red WiFi que requiere una página web para iniciar sesión?</span><span class="sxs-lookup"><span data-stu-id="66433-518">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="66433-519">Outlook ahora lo detecta y le ayuda a estar conectado.</span><span class="sxs-lookup"><span data-stu-id="66433-519">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="66433-520">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span><span class="sxs-lookup"><span data-stu-id="66433-520">See details in [blog post](https://insider.office.com/es-ES/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="66433-521">**Obtener sugerencias de correo electrónico cuando busca un contacto:** cuando escriba el nombre de una persona en el cuadro de búsqueda, se incluirán los mensajes de correo electrónico más relevantes con las sugerencias de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="66433-521">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="66433-522">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-522">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a><span data-ttu-id="66433-523">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66433-523">PowerPoint</span></span>

- <span data-ttu-id="66433-524">**Logre la atención de sus colegas con** @menciones:\@ use @menciones en los comentarios para avisar a los compañeros de trabajo cuando necesite su participación.</span><span class="sxs-lookup"><span data-stu-id="66433-524">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="66433-525">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-525">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="66433-526">**Gráficos de mapa mejorados:** hemos integrado los gráficos de mapa con los tipos de datos geográficos de Excel, para que revelen información de todo tipo sobre las ubicaciones que desee.</span><span class="sxs-lookup"><span data-stu-id="66433-526">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="66433-527">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-527">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="66433-528">**GIF en un instante:** una diapositiva, un marco.</span><span class="sxs-lookup"><span data-stu-id="66433-528">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="66433-529">Cree fácilmente archivos GIF en bucle en PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="66433-529">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="66433-530">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-530">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="66433-531">Ver detalles en [entrada de blog](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="66433-531">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="66433-532">**Mejores diagramas** con mejores conectores y un proceso de conversión de entrada de lápiz más fluido, puede aplicar sus ideas con más confianza.</span><span class="sxs-lookup"><span data-stu-id="66433-532">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="66433-533">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-533">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="66433-534">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="66433-534">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="66433-535">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="66433-535">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="66433-536">**Comentarios:** la nueva experiencia de comentarios en PowerPoint permite descubrir y agregar comentarios a los documentos de forma rápida y sencilla.</span><span class="sxs-lookup"><span data-stu-id="66433-536">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="66433-537">Modernice sus flujos de trabajo de colaboración con nuevas características como anclaje de comentarios, resuelva, tareas, notificaciones de menciones mejoradas y mucho más.</span><span class="sxs-lookup"><span data-stu-id="66433-537">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="66433-538">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-538">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- <span data-ttu-id="66433-539">**Sincronice los cambios mientras realiza la presentación:** sincronice los cambios cuando se hagan aunque la presentación esté en el modo de presentación con diapositivas.</span><span class="sxs-lookup"><span data-stu-id="66433-539">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="66433-540">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-540">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="66433-541">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="66433-541">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="66433-542">**Vínculo a la diapositiva:** Pídale a un compañero que participe en la presentación de diapositivas y llévelo directamente a la diapositiva con la que necesita ayuda.</span><span class="sxs-lookup"><span data-stu-id="66433-542">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="66433-543">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-543">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="66433-544">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span><span class="sxs-lookup"><span data-stu-id="66433-544">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="66433-545">**Mejor rendimiento de vídeos de Stream en PowerPoint:** hemos realizado mejoras en el rendimiento de la reproducción de los vídeos de Microsoft Stream para reducir el tiempo de carga de vídeo y crear una visualización más suave.</span><span class="sxs-lookup"><span data-stu-id="66433-545">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="66433-546">Use los vídeos corporativos de Microsoft Stream para crear presentaciones mejoradas.</span><span class="sxs-lookup"><span data-stu-id="66433-546">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>


### <a name="word"></a><span data-ttu-id="66433-547">Word</span><span class="sxs-lookup"><span data-stu-id="66433-547">Word</span></span>

- <span data-ttu-id="66433-548">**Gráficos de mapa mejorados:** hemos integrado los gráficos de mapa con los tipos de datos geográficos de Excel, para que revelen información de todo tipo sobre las ubicaciones que desee.</span><span class="sxs-lookup"><span data-stu-id="66433-548">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="66433-549">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-549">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="66433-550">**Selección de lazo de la entrada de lápiz:** la herramienta Lazo en la pestaña Dibujar le ayuda a seleccionar objetos dibujados a mano.</span><span class="sxs-lookup"><span data-stu-id="66433-550">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="66433-551">Seleccione trazos individuales o palabras completas.</span><span class="sxs-lookup"><span data-stu-id="66433-551">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="66433-552">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-552">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="66433-553">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="66433-553">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="66433-554">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="66433-554">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="66433-555">**Confirmación de acción en lectores de pantalla:** la confirmación de la acción es un requisito de accesibilidad importante.</span><span class="sxs-lookup"><span data-stu-id="66433-555">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="66433-556">Con la introducción de una nueva API de notificación de Windows, ahora podemos alertar a los usuarios de lectores de pantalla sobre el éxito de sus acciones.</span><span class="sxs-lookup"><span data-stu-id="66433-556">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="66433-557">Las opciones de cortar, copiar, pegar, negrita, cursiva, subrayado, deshacer, rehacer, corrección automática y uso automático de mayúsculas ahora se anuncian a los usuarios del narrador en Word Win32.</span><span class="sxs-lookup"><span data-stu-id="66433-557">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="66433-558">Para habilitar esta característica, active el narrador presionando Windows + Ctrl + Entrar.</span><span class="sxs-lookup"><span data-stu-id="66433-558">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="66433-559">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="66433-559">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="66433-560">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="66433-560">Office Suite</span></span>

- <span data-ttu-id="66433-561">**Etiquetas de confidencialidad:** ahora puede aplicar una etiqueta de confidencialidad que su organización ha configurado para solicitarle permisos personalizados.</span><span class="sxs-lookup"><span data-stu-id="66433-561">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="66433-564">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="66433-564">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="66433-565">Acceso</span><span class="sxs-lookup"><span data-stu-id="66433-565">Access</span></span>

- <span data-ttu-id="66433-566">Se ha resuelto un problema al insertar tablas SQL vinculadas que incluyan un campo de identidad (por ejemplo, autonumeración).</span><span class="sxs-lookup"><span data-stu-id="66433-566">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

- <span data-ttu-id="66433-567">Se ha corregido un problema que provocaba que la ejecución de consultas tardara en completarse aproximadamente el doble del tiempo esperado.</span><span class="sxs-lookup"><span data-stu-id="66433-567">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="66433-568">Se ha corregido un problema para poder llamar al tipo de datos Fecha/Hora ampliado en el código sin tener que bloquear la aplicación.</span><span class="sxs-lookup"><span data-stu-id="66433-568">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span>

- <span data-ttu-id="66433-569">Se ha corregido un problema de forma que ahora puede volver a la versión de Access más actualizada y usar DAO/VBA para administrar y editar un tipo de datos decimal.</span><span class="sxs-lookup"><span data-stu-id="66433-569">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>

- <span data-ttu-id="66433-570">Esta corrección resuelve un problema por el que al intentar ejecutar determinadas consultas anteriormente se generaba el mensaje de error "La consulta es demasiado compleja".</span><span class="sxs-lookup"><span data-stu-id="66433-570">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="66433-571">Access ha corregido este problema actual, pero se está investigando nuestra interfaz adicional para asegurarnos de que este problema no se conserva.</span><span class="sxs-lookup"><span data-stu-id="66433-571">Access has fixed this current issue, but will be investigating our additional interfaces to ensure that this problem does not persist.</span></span> <span data-ttu-id="66433-572">El equipo le informará en actualizaciones futuras. Agradecemos su paciencia.</span><span class="sxs-lookup"><span data-stu-id="66433-572">The team will inform you with future updates; we appreciate your patience.</span></span>

- <span data-ttu-id="66433-573">Este problema fue resuelto: ahora puede usar el controlador ODBC fuera de las aplicaciones de Hacer clic y ejecutar de Office.</span><span class="sxs-lookup"><span data-stu-id="66433-573">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="66433-574">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-574">Excel</span></span>

- <span data-ttu-id="66433-575">Es posible que se haya producido una clasificación de documentos automática en los libros que se encontraban en modo de solo lectura.</span><span class="sxs-lookup"><span data-stu-id="66433-575">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="66433-576">Se ha corregido un bloqueo que podría producirse al intentar crear una conexión de datos si había cerrado la sesión de su cuenta.</span><span class="sxs-lookup"><span data-stu-id="66433-576">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

- <span data-ttu-id="66433-577">Se ha corregido un problema por el que Excel se bloqueaba al intentar insertar tablas dinámicas en una hoja de gráfico.</span><span class="sxs-lookup"><span data-stu-id="66433-577">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

- <span data-ttu-id="66433-578">Se puede producir un error al intentar guardar un archivo que contiene una fórmula con la función LET().</span><span class="sxs-lookup"><span data-stu-id="66433-578">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="66433-579">Se ha corregido un problema que provocaba que Excel se bloqueara en determinadas circunstancias al usar Copiar formato.</span><span class="sxs-lookup"><span data-stu-id="66433-579">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>

- <span data-ttu-id="66433-580">Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta al guardar en SharePoint o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="66433-580">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="66433-581">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="66433-581">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="66433-582">Se solucionó un problema por el cual, en algunos casos, al hacer clic en un hipervínculo a un lugar dentro del mismo libro de trabajo, el libro de trabajo se ocultaba.</span><span class="sxs-lookup"><span data-stu-id="66433-582">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

- <span data-ttu-id="66433-583">Se ha corregido un problema que hacía que el vínculo externo dejara de funcionar después de que se volviera a abrir un archivo si su ruta de acceso era demasiado larga.</span><span class="sxs-lookup"><span data-stu-id="66433-583">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="66433-584">Application.Evaluate (VBA) no funcionaba para funciones definidas por el usuario en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="66433-584">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="66433-585">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="66433-585">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="66433-586">Se ha corregido un problema que hacía que Excel se bloqueara en ciertos casos después de copiar una hoja que contenía una tabla dinámica.</span><span class="sxs-lookup"><span data-stu-id="66433-586">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="66433-587">Esto soluciona un problema en el que las conexiones creadas por el proveedor de datos SQL en versiones anteriores de Office establecerían las propiedades de la tabla interna de manera diferente a Office 365.</span><span class="sxs-lookup"><span data-stu-id="66433-587">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="66433-588">Esto provocó que el menú desplegable Vista previa de tabla / Editor de consultas se deshabilitara para los archivos con conexiones creadas en versiones anteriores de Office cuando se abrieron con Office 365.</span><span class="sxs-lookup"><span data-stu-id="66433-588">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>

- <span data-ttu-id="66433-589">Corregido un problema por el que los enlaces externos no se actualizaban si el libro de origen estaba cerrado.</span><span class="sxs-lookup"><span data-stu-id="66433-589">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="66433-590">Se corrigió un problema por el cual las entradas manuscritas podrían hacer que Excel dejara de responder.</span><span class="sxs-lookup"><span data-stu-id="66433-590">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="onenote"></a><span data-ttu-id="66433-591">OneNote</span><span class="sxs-lookup"><span data-stu-id="66433-591">OneNote</span></span>

- <span data-ttu-id="66433-592">Se informa a los usuarios mediante la barra de información sobre los ajustes temporales de Microsoft OneNote que les ayudarán a mejorar la sincronización y la disponibilidad del servicio durante un uso mundial elevado.</span><span class="sxs-lookup"><span data-stu-id="66433-592">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

- <span data-ttu-id="66433-593">Mejora de la sincronización y la estabilidad del servicio al ajustar temporalmente la frecuencia de sincronización en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="66433-593">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="66433-594">Se mejoró la detección del estado de la coautoría para reducir el uso de recursos.</span><span class="sxs-lookup"><span data-stu-id="66433-594">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="66433-595">Se obtiene una mejora de la sincronización y la estabilidad del servicio al reducir temporalmente el tamaño máximo de nuevos datos adjuntos insertados a 50 MB en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="66433-595">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="66433-596">Si los archivos superan este límite, los usuarios tendrán la opción de cargar el archivo a OneDrive e insertar un vínculo en OneNote.</span><span class="sxs-lookup"><span data-stu-id="66433-596">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="66433-597">Se obtiene una mejora de la sincronización y la estabilidad del servicio al deshabilitar temporalmente la grabación de vídeo en la aplicación en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="66433-597">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="66433-598">La medida no afecta a los blocs de notas locales.</span><span class="sxs-lookup"><span data-stu-id="66433-598">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="66433-599">Se obtiene una mejora de la sincronización y la estabilidad del servicio al alterar temporalmente la frecuencia con la que se crean los historiales de las versiones de las páginas.</span><span class="sxs-lookup"><span data-stu-id="66433-599">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>

- <span data-ttu-id="66433-600">Se obtiene una mejora de la sincronización y la estabilidad del servicio al deshabilitar temporalmente el desplazamiento de páginas a la papelera de reciclaje.</span><span class="sxs-lookup"><span data-stu-id="66433-600">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="66433-601">A los usuarios que quieran eliminar una página se les mostrará un cuadro de diálogo en el que se le preguntará si quieren eliminar una página de forma permanente.</span><span class="sxs-lookup"><span data-stu-id="66433-601">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>

### <a name="outlook"></a><span data-ttu-id="66433-602">Outlook</span><span class="sxs-lookup"><span data-stu-id="66433-602">Outlook</span></span>

- <span data-ttu-id="66433-603">Corrige un problema que evitaba que los usuarios que intentaran crear una solicitud de reunión desde una cuenta secundaria añadida a su perfil vieran el campo De: en blanco en lugar de su dirección de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="66433-603">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="66433-604">Corrige un problema que evitaba que los usuarios se conectaran a las carpetas públicas luego de agregar un buzón compartido.</span><span class="sxs-lookup"><span data-stu-id="66433-604">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="66433-605">Se ha corregido un problema que provocaba un error al tratar de eliminar las reuniones del calendario de un administrador, cuando un delegado las rechazaba en determinadas circunstancias.</span><span class="sxs-lookup"><span data-stu-id="66433-605">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="66433-606">Se corrigió un problema que impedía a algunos usuarios de la característica Mejoras del calendario compartido ver un calendario compartido recién agregado.</span><span class="sxs-lookup"><span data-stu-id="66433-606">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="66433-607">Corrige un problema que provocaba que los usuarios experimentaran bloqueos ocasionales al interactuar con los datos adjuntos en la nube.</span><span class="sxs-lookup"><span data-stu-id="66433-607">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="66433-608">Se ha corregido un problema que provocaba que los usuarios de CLP experimenten un bloqueo al cambiar la dirección del remitente en una respuesta desde un contexto protegido a uno no protegido.</span><span class="sxs-lookup"><span data-stu-id="66433-608">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>

- <span data-ttu-id="66433-609">Se ha corregido un problema por el que Outlook no pudo habilitar consejos de directiva para la Protección de pérdida de datos para usuarios que pagaron por el servicio con planes M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="66433-609">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="66433-610">Se ha corregido un problema con el evento de auditoría CLP para la etiqueta de responder o reenviar.</span><span class="sxs-lookup"><span data-stu-id="66433-610">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="66433-611">Se ha corregido un problema que provocaba que el ancho del panel de carpetas cambiara inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="66433-611">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="66433-612">Se ha corregido un problema que causaba que la fecha de creación de datos adjuntos copiados en el sistema de archivos a través de la opción de arrastrar y soltar apareciera como el 1 de enero de 4501.</span><span class="sxs-lookup"><span data-stu-id="66433-612">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>

- <span data-ttu-id="66433-613">Se ha corregido un problema que provocaba que los usuarios de algunos juegos de caracteres viesen nombres de archivo que se mostraban de forma incorrecta al agregar un vínculo inteligente a un archivo de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="66433-613">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="66433-614">Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange", al actualizar sus reglas en Outlook.</span><span class="sxs-lookup"><span data-stu-id="66433-614">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="66433-615">Se corrigió un problema que provocaba que Outlook no pudiese recuperar sugerencias de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="66433-615">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>

- <span data-ttu-id="66433-616">Se ha corregido un problema que provocaba que los usuarios de las mejoras del Calendario compartido vieran errores en el calendario.</span><span class="sxs-lookup"><span data-stu-id="66433-616">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="66433-617">Se ha corregido un problema que causaba que los usuarios experimentasen bloqueos y errores intermitentes en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="66433-617">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>

- <span data-ttu-id="66433-618">Se ha corregido un problema que provocaba que los usuarios experimentaran un error al eliminar 4 o más mensajes de correo electrónico de una cuenta POP con la opción "Descargar solo encabezados" seleccionada.</span><span class="sxs-lookup"><span data-stu-id="66433-618">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="66433-619">Se ha corregido un problema que causaba que faltara la opción "Permitir reenvío" en las "Opciones de respuesta" de la reunión de calendario compartida cuando NO está marcada Descargar carpeta compartida.</span><span class="sxs-lookup"><span data-stu-id="66433-619">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="66433-620">Se ha corregido un problema que causaba que los delegados recibieran un error al editar una cita de calendario existente en el calendario de un administrador.</span><span class="sxs-lookup"><span data-stu-id="66433-620">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="66433-621">Se ha corregido un problema que provocaba que los usuarios experimentaran bloqueos en aplicaciones MAPI de terceros.</span><span class="sxs-lookup"><span data-stu-id="66433-621">Addressed an issue that caused users to experience crashes in third party MAPI applications.</span></span>

- <span data-ttu-id="66433-622">Se ha corregido un problema que provocaba que Outlook se bloqueara al abrir archivos .msg y .oft guardados localmente después de una actualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="66433-622">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="66433-623">Se ha corregido un problema que provocaba que Outlook se bloqueara en algunas compilaciones de Windows.</span><span class="sxs-lookup"><span data-stu-id="66433-623">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="66433-624">Se ha corregido un problema que provocaba que los usuarios de las versiones de Windows 10 Server vieran la advertencia "Estado del antivirus: no válido".</span><span class="sxs-lookup"><span data-stu-id="66433-624">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="66433-625">Esta versión de Windows admite la detección del antivirus, pero no se encontró ninguno” a pesar de tener un antivirus correctamente instalado.</span><span class="sxs-lookup"><span data-stu-id="66433-625">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="66433-626">Se ha corregido un problema que provocaba que Outlook se bloqueara al abrir archivos .msg y .oft guardados localmente después de una actualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="66433-626">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="66433-627">Se ha corregido un problema que provocaba que Outlook se bloqueara en algunas compilaciones de Windows.</span><span class="sxs-lookup"><span data-stu-id="66433-627">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="66433-628">Se ha corregido un problema que provocaba que los usuarios de Outlook vieran continuamente un aviso para que ejecutaran la herramienta de reparación de la bandeja de entrada.</span><span class="sxs-lookup"><span data-stu-id="66433-628">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="66433-629">Abordó un problema que causó que los usuarios experimentaran ocasionalmente un choque al usar el botón "X" de su ratón.</span><span class="sxs-lookup"><span data-stu-id="66433-629">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="66433-630">Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.</span><span class="sxs-lookup"><span data-stu-id="66433-630">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="66433-631">Se ha corregido un problema que provocaba que la página del Asistente para programación no se mostrara.</span><span class="sxs-lookup"><span data-stu-id="66433-631">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="66433-632">Se ha corregido un problema que impedía a algunos usuarios visualizar correctamente la página del Asistente para programación.</span><span class="sxs-lookup"><span data-stu-id="66433-632">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="66433-633">Se corrigió un problema que provocaba que los usuarios se bloquearan en ocasiones al recuperar información personal.</span><span class="sxs-lookup"><span data-stu-id="66433-633">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>

- <span data-ttu-id="66433-634">Esto corrige un problema que provocaba que los usuarios experimentaran bloqueos ocasionales al editar los destinatarios.</span><span class="sxs-lookup"><span data-stu-id="66433-634">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="66433-635">Corrige un problema que provocaba que los usuarios vieran anomalías al usar la vista compacta.</span><span class="sxs-lookup"><span data-stu-id="66433-635">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="66433-636">Se ha corregido un problema que provocaba que los usuarios de Outlook tuvieran problemas con la navegación en vistas compactas.</span><span class="sxs-lookup"><span data-stu-id="66433-636">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>

- <span data-ttu-id="66433-637">Se ha corregido un problema que provocaba que el menú contextual del botón derecho no apareciera en los controles de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="66433-637">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="66433-638">Corrige un problema que provocaba que los usuarios recibieran el siguiente error al responder a un correo o al redactar uno nuevo: "Algunos archivos de esta página web no están en la ubicación esperada.</span><span class="sxs-lookup"><span data-stu-id="66433-638">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="66433-639">¿Desea descargarlos de todos modos?</span><span class="sxs-lookup"><span data-stu-id="66433-639">Do you want to download them anyway?</span></span> <span data-ttu-id="66433-640">Si está seguro de que la página web es una fuente de confianza, haga clic en Sí".</span><span class="sxs-lookup"><span data-stu-id="66433-640">If you’re sure the Web page is from a trusted source, click Yes"</span></span>

- <span data-ttu-id="66433-641">Corrige un problema que provocaba que los usuarios experimentaran un error al salir de Outlook.</span><span class="sxs-lookup"><span data-stu-id="66433-641">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>

- <span data-ttu-id="66433-642">Se ha corregido un problema que provocaba que la búsqueda de una característica en Sugerir una característica no devolviera resultados y no ofrecía al usuario ninguna opción para enviar una nueva idea de característica.</span><span class="sxs-lookup"><span data-stu-id="66433-642">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="66433-643">Se ha abordado un problema que causaba problemas de formato en las alertas de notificación de incidentes.</span><span class="sxs-lookup"><span data-stu-id="66433-643">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

- <span data-ttu-id="66433-644">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al enviar comentarios desde una Notificación de administrador.</span><span class="sxs-lookup"><span data-stu-id="66433-644">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="66433-645">Se ha corregido un problema para copiar y pegar imágenes SVG.</span><span class="sxs-lookup"><span data-stu-id="66433-645">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="66433-646">Esto corrige un problema que provocaba que los usuarios experimentaran bloqueos ocasionales al editar los destinatarios.</span><span class="sxs-lookup"><span data-stu-id="66433-646">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="66433-647">Se ha corregido un problema para copiar y pegar imágenes SVG.</span><span class="sxs-lookup"><span data-stu-id="66433-647">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="66433-648">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66433-648">PowerPoint</span></span>

- <span data-ttu-id="66433-649">Se corrigió un bloqueo cuando los usuarios tenían comentarios tanto modernos como heredados en un archivo, lo que activaba una actualización de los comentarios.</span><span class="sxs-lookup"><span data-stu-id="66433-649">Fixed a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

- <span data-ttu-id="66433-650">Se ha corregido un problema de bloqueo con la aplicación de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="66433-650">We have fixed a crash issue with PowerPoint app.</span></span>

- <span data-ttu-id="66433-651">Se ha corregido un problema de bloqueo en el panel de sugerencias.</span><span class="sxs-lookup"><span data-stu-id="66433-651">We have fixed a crash issue with suggestion pane.</span></span>

### <a name="project"></a><span data-ttu-id="66433-652">Project</span><span class="sxs-lookup"><span data-stu-id="66433-652">Project</span></span>

- <span data-ttu-id="66433-653">Se solucionó un problema cuando los datos del Predecesor/Sucesor se editaban dentro de una vista de formulario, se activaba un evento ProjectBeforeTaskChange adicional.</span><span class="sxs-lookup"><span data-stu-id="66433-653">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="66433-654">Corregido un problema por el que Project puede bloquearse al guardar proyectos creados con versiones anteriores de Project.</span><span class="sxs-lookup"><span data-stu-id="66433-654">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="66433-655">Se corrigió un problema por el que el usuario no podía especificar el trabajo previsto con fases temporales al activar la configuración para proteger el trabajo real.</span><span class="sxs-lookup"><span data-stu-id="66433-655">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

- <span data-ttu-id="66433-656">Corregido un problema por el que el porcentaje completado de la tarea se cambiaba incorrectamente a un valor inferior al 100 % después de que se marcara como completada. </span><span class="sxs-lookup"><span data-stu-id="66433-656">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="66433-657">Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="66433-657">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="66433-658">Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.</span><span class="sxs-lookup"><span data-stu-id="66433-658">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="66433-659">Corregido un problema que hace que el evento ProjectBeforeTaskChange no detecte cuándo se ha desactivado o activado una tarea mediante el botón Desactivar.</span><span class="sxs-lookup"><span data-stu-id="66433-659">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="66433-660">Se ha corregido un problema que hace que si está usando Project conectado a Project Web App y el separador decimal es una coma, el método TaskDependencies Add producirá un error al intentar agregar retardo a una dependencia.</span><span class="sxs-lookup"><span data-stu-id="66433-660">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

- <span data-ttu-id="66433-661">Se ha corregido un problema por el que los proyectos no se podían abrir en el cliente de escritorio de Project desde Project Web App si la dirección URL terminaba en .com.</span><span class="sxs-lookup"><span data-stu-id="66433-661">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>

- <span data-ttu-id="66433-662">Se ha corregido un problema por el que si pegaba una tarea que tenía varias dependencias, no todas las dependencias se copiaban correctamente.</span><span class="sxs-lookup"><span data-stu-id="66433-662">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="66433-663">Se ha corregido un problema que impedía guardar desde Project un PDF o XPS en una biblioteca de documentos de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="66433-663">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>

- <span data-ttu-id="66433-664">Se ha corregido un problema por el que una tarea marcada como completada al 100 % se mostraba por error no completada al 100 %.</span><span class="sxs-lookup"><span data-stu-id="66433-664">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="66433-665">Se ha corregido un problema por el que el evento ProjectBeforeTaskChange no se activaba al darse un cambio en la tarea de resumen del proyecto: ya sea en el campo de inicio o tarea del proyecto.</span><span class="sxs-lookup"><span data-stu-id="66433-665">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="66433-666">Se ha corregido un problema debido al cual, si un recurso tenía más de una tabla de tasa de costo definida, el costo restante no siempre se calculaba correctamente.</span><span class="sxs-lookup"><span data-stu-id="66433-666">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

- <span data-ttu-id="66433-667">Se ha corregido un problema en el que la fecha de finalización de Project no se actualiza para los proyectos conectados a la lista de tareas de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="66433-667">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="66433-668">Se ha corregido un problema por el que la tarea seleccionada en el cuadro de diálogo de asignación de recursos no era la misma que la tarea seleccionada en la vista del panel de tareas.</span><span class="sxs-lookup"><span data-stu-id="66433-668">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="66433-669">Se corrigió un problema por el que no se podía abrir un proyecto que estaba en mal estado.</span><span class="sxs-lookup"><span data-stu-id="66433-669">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>

### <a name="skype"></a><span data-ttu-id="66433-670">Skype</span><span class="sxs-lookup"><span data-stu-id="66433-670">Skype</span></span>

- <span data-ttu-id="66433-671">Cuando se asignaba a un usuario una directiva que lo llevaba a Teams solo, aún se podía usar el complemento para Outlook de Skype Empresarial para programar reuniones.</span><span class="sxs-lookup"><span data-stu-id="66433-671">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="66433-672">Tras esta actualización, ya no se podrán programar reuniones de Skype Empresarial después de que el cliente lea la directiva en la que se indica que el usuario participa en Teams solo y entra en la reunión como Unirse solo.</span><span class="sxs-lookup"><span data-stu-id="66433-672">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="66433-673">Además, el complemento de Outlook para Skype Empresarial no se activará durante el inicio si ve que el cliente de Skype Empresarial se encuentra en modo de Unirse solo.</span><span class="sxs-lookup"><span data-stu-id="66433-673">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="66433-674">Se cambió el tono de piel del emoticono de baile a un color neutro</span><span class="sxs-lookup"><span data-stu-id="66433-674">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="66433-675">Word</span><span class="sxs-lookup"><span data-stu-id="66433-675">Word</span></span>

- <span data-ttu-id="66433-676">Se ha resuelto un problema al abrir documentos de Word desde la entrega de documentos personalizados (aspx) cuando la dirección URL contenía un componente de consulta.</span><span class="sxs-lookup"><span data-stu-id="66433-676">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="66433-677">Este cambio corrige un problema que provocaba que las aplicaciones de Office se queden atascadas en un estado de error de guardado silencioso después de una sesión de coautoría anterior.</span><span class="sxs-lookup"><span data-stu-id="66433-677">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="66433-678">Corrige un problema que provocaba que los usuarios experimentaran un bloqueo al responder o redactar un correo nuevo.</span><span class="sxs-lookup"><span data-stu-id="66433-678">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="66433-679">Abordó un problema que causó que los usuarios experimentaran ocasionalmente un choque al usar el botón "X" de su ratón.</span><span class="sxs-lookup"><span data-stu-id="66433-679">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="66433-680">Se ha corregido un problema para copiar y pegar imágenes SVG.</span><span class="sxs-lookup"><span data-stu-id="66433-680">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="66433-681">Se ha corregido un problema por el cual el usuario podría perder contenido al cambiar el tamaño de una forma.</span><span class="sxs-lookup"><span data-stu-id="66433-681">We fixed an issue where the user might lose content when resize a shape.</span></span>

- <span data-ttu-id="66433-682">Se ha corregido un problema por el cual los estilos base no se actualizaban con el estilo Normal.</span><span class="sxs-lookup"><span data-stu-id="66433-682">We fixed an issue which the base styles are not updated with Normal style.</span></span>

- <span data-ttu-id="66433-683">Se ha corregido un problema por el que se ejecuta la macro AutoOpen antes de AutoExec.</span><span class="sxs-lookup"><span data-stu-id="66433-683">We fixed an issue where macro AutoOpen runs before AutoExec.</span></span>

- <span data-ttu-id="66433-684">Se ha corregido un problema para copiar y pegar imágenes SVG.</span><span class="sxs-lookup"><span data-stu-id="66433-684">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="66433-685">Se ha corregido un problema que podría haber provocado un bloqueo al arrastrar contenido desde la aplicación.</span><span class="sxs-lookup"><span data-stu-id="66433-685">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="66433-686">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="66433-686">Office Suite</span></span>

- <span data-ttu-id="66433-687">Para un antiguo panel de uso compartido basado en servicio no Web, al cerrar el documento mientras el panel de uso compartido está abierto, se podría producir un bloqueo.</span><span class="sxs-lookup"><span data-stu-id="66433-687">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="66433-688">Este problema ya está solucionado.</span><span class="sxs-lookup"><span data-stu-id="66433-688">This is now fixed.</span></span>

- <span data-ttu-id="66433-689">Se corrigió un problema de temporización que podía provocar un bloqueo al cerrar archivos de Office.</span><span class="sxs-lookup"><span data-stu-id="66433-689">Fixed a timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="66433-690">Hemos resuelto el problema de la tasa de error de ValidateInstall estableciendo la validación de instalación del Complemento de Bing como verdadera de forma predeterminada y considerando el éxito de devolución de MSI como una instalación con éxito.</span><span class="sxs-lookup"><span data-stu-id="66433-690">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>

- <span data-ttu-id="66433-691">Hemos modificado la versión AppV51 para solucionar una regresión de la AppV51 anterior.</span><span class="sxs-lookup"><span data-stu-id="66433-691">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="66433-692">Se ha corregido un problema de hacer clic y ejecutar que generaba errores de actualización al intentar crear un vínculo físico para vínculos simbólicos.</span><span class="sxs-lookup"><span data-stu-id="66433-692">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>

- <span data-ttu-id="66433-693">Se ha corregido un problema que provocaba que se mostrara un mensaje de tiempo de ejecución aunque se completara la transición al producto completo.</span><span class="sxs-lookup"><span data-stu-id="66433-693">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="66433-694">La corrección para este problema era asegurarse de que el servicio computase correctamente los productos agregados.</span><span class="sxs-lookup"><span data-stu-id="66433-694">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="66433-695">Se han filtrado los nuevos productos agregados (lo que garantiza que también se encuentren en la nueva configuración) y se han agregado al final de los ID de versión de producto existentes.</span><span class="sxs-lookup"><span data-stu-id="66433-695">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>

- <span data-ttu-id="66433-696">Se ha corregido un problema debido al cual los usuarios no podían visualizar el contenido o los elementos de la interfaz de usuario en determinadas condiciones, especialmente en la vista Moderador (o al salir de la misma) o al usar varios monitores.</span><span class="sxs-lookup"><span data-stu-id="66433-696">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>

- <span data-ttu-id="66433-697">Este cambio resuelve posibles errores al cargar y reproducir contenido animado como GIF o modelos 3D.</span><span class="sxs-lookup"><span data-stu-id="66433-697">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>

- <span data-ttu-id="66433-698">Este cambio resuelve un problema con el cuadro de diálogo de Comprimir imagen, que no retiene determinadas configuraciones de usuario.</span><span class="sxs-lookup"><span data-stu-id="66433-698">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>

- <span data-ttu-id="66433-699">Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.</span><span class="sxs-lookup"><span data-stu-id="66433-699">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="66433-700">Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.</span><span class="sxs-lookup"><span data-stu-id="66433-700">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="66433-701">Esta corrección resuelve un error que impide restringir el acceso y proteger los archivos con una contraseña de forma simultánea.</span><span class="sxs-lookup"><span data-stu-id="66433-701">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="66433-702">Se ha corregido un problema de bloqueo con el host de Office en Windows cuando se activa un complemento mientras el valor del registro TabProcGrowth era del tipo REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="66433-702">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="66433-703">El host de Office se bloqueaba en Windows, cuando se activaba un complemento si la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth estaba establecida en cero.</span><span class="sxs-lookup"><span data-stu-id="66433-703">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="66433-704">Este cambio arreglaría el problema.</span><span class="sxs-lookup"><span data-stu-id="66433-704">This change would fix this issue.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-august-11"></a><span data-ttu-id="66433-706">Versión 2002: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="66433-706">Version 2002: August 11</span></span>
<span data-ttu-id="66433-707">*Versión 2002 (compilación 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="66433-707">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="66433-708">Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="66433-708">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="66433-710">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="66433-710">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="66433-711">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-711">Excel</span></span>

- <span data-ttu-id="66433-712">Se corrigió un problema por el que no se podía cambiar a la edición de archivos que se han abierto como "recomendado solo lectura".</span><span class="sxs-lookup"><span data-stu-id="66433-712">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="66433-713">OneNote</span><span class="sxs-lookup"><span data-stu-id="66433-713">OneNote</span></span>

- <span data-ttu-id="66433-714">Se quitaron las llamadas de identidad redundantes para reducir el uso de recursos</span><span class="sxs-lookup"><span data-stu-id="66433-714">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="66433-715">Se mejoró la detección del estado de la coautoría para reducir el uso de recursos.</span><span class="sxs-lookup"><span data-stu-id="66433-715">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="66433-716">Se mejoró la función de detección de errores y la calidad de la experiencia de sincronización.</span><span class="sxs-lookup"><span data-stu-id="66433-716">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="66433-717">Outlook</span><span class="sxs-lookup"><span data-stu-id="66433-717">Outlook</span></span>

- <span data-ttu-id="66433-718">Se corrigió un problema que causaba un problema de rendimiento importante al iniciar Outlook en algunos espacios empresariales.</span><span class="sxs-lookup"><span data-stu-id="66433-718">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="66433-719">Skype</span><span class="sxs-lookup"><span data-stu-id="66433-719">Skype</span></span>

- <span data-ttu-id="66433-720">Se corrigió un problema por el que se podía producir un error al compartir la pantalla en un cliente de Skype Empresarial de 32 bits después de ejecutarlo durante varios días.</span><span class="sxs-lookup"><span data-stu-id="66433-720">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="66433-721">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="66433-721">Office Suite</span></span>

- <span data-ttu-id="66433-722">Se corrigió un problema que se producía al desactivar el autoguardado a través de la directiva de grupo: era posible que algunos documentos no mostraran el contenido más reciente de servidor al abrirse hasta que el usuario hiciera clic en "Actualizaciones disponibles".</span><span class="sxs-lookup"><span data-stu-id="66433-722">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-july-14"></a><span data-ttu-id="66433-724">Versión 2002: 14 de julio</span><span class="sxs-lookup"><span data-stu-id="66433-724">Version 2002: July 14</span></span>
<span data-ttu-id="66433-725">*Versión 2002 (compilación 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="66433-725">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="66433-726">Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="66433-726">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="66433-728">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="66433-728">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="66433-729">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-729">Excel</span></span>

- <span data-ttu-id="66433-730">Acelere la carga de archivos que están disponibles en la carpeta de OneDrive local.</span><span class="sxs-lookup"><span data-stu-id="66433-730">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="66433-731">Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta al guardar en SharePoint o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="66433-731">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="66433-732">Se ha corregido un problema que producía el siguiente mensaje de error: "No se puede cerrar el libro de trabajo debido a que otro libro hace referencia al mismo". El mensaje aparecía si los complementos se cargaban en orden alfabético en lugar de en un orden especificado por el usuario.</span><span class="sxs-lookup"><span data-stu-id="66433-732">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="66433-733">Se ha corregido un problema que haría que un libro se ocultara al hacer clic en un hipervínculo a un lugar dentro de un libro ya abierto.</span><span class="sxs-lookup"><span data-stu-id="66433-733">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="66433-734">Se ha corregido un problema por el que algunos vínculos de un gráfico copiado y pegado usaban direcciones de unidad asignadas, en lugar de direcciones universales.</span><span class="sxs-lookup"><span data-stu-id="66433-734">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="66433-735">Se ha mejorado el rendimiento al eliminar columnas con celdas combinadas.</span><span class="sxs-lookup"><span data-stu-id="66433-735">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="66433-736">Se ha corregido un problema por el que los nombres de las impresoras podrían repetirse en la lista de impresoras en el cuadro de diálogo Imprimir.</span><span class="sxs-lookup"><span data-stu-id="66433-736">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="66433-737">Se ha corregido un problema por el que las hojas de cálculo que contenían varias fórmulas con nombres definidos tardaban más en guardarse.</span><span class="sxs-lookup"><span data-stu-id="66433-737">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="66433-738">Outlook</span><span class="sxs-lookup"><span data-stu-id="66433-738">Outlook</span></span>

- <span data-ttu-id="66433-739">Se ha corregido un problema por el que la ventana del Editor de métodos de entrada (IME) se superponía al texto subyacente escrito mediante el IME cuando se usaban varios monitores con resoluciones diferentes.</span><span class="sxs-lookup"><span data-stu-id="66433-739">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="66433-740">Se ha corregido un problema que causaba que las citas o reuniones periódicas se mostraran en un momento incorrecto al tratar de cambiar la definición de una zona horaria.</span><span class="sxs-lookup"><span data-stu-id="66433-740">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="66433-741">Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange", al actualizar sus reglas en Outlook.</span><span class="sxs-lookup"><span data-stu-id="66433-741">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="66433-742">Se ha corregido un problema que causaba que faltara la opción "Permitir reenvío" en las "Opciones de respuesta" de la reunión de calendario compartida cuando NO está marcada Descargar carpeta compartida.</span><span class="sxs-lookup"><span data-stu-id="66433-742">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="66433-743">Se ha corregido un problema que provocaba que las categorías desapareciesen en ocasiones de los mensajes de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="66433-743">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="66433-744">Se ha corregido un problema que provocaba que los delegados viesen distintas jerarquías de carpetas en diferentes equipos para los buzones compartidos.</span><span class="sxs-lookup"><span data-stu-id="66433-744">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="66433-745">Se ha corregido un problema que causaba que los delegados recibieran un error al editar una cita de calendario existente en el calendario de un administrador.</span><span class="sxs-lookup"><span data-stu-id="66433-745">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="66433-746">Se ha corregido un problema que provocaba que el cuerpo de un mensaje NDR cambiara de Unicode a ASCII después de editar el asunto.</span><span class="sxs-lookup"><span data-stu-id="66433-746">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="66433-747">Se ha corregido un problema que causaba que los usuarios experimentaran un bloqueo cuando dos complementos agregan un botón al mismo grupo de la cinta de opciones.</span><span class="sxs-lookup"><span data-stu-id="66433-747">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="66433-748">Se ha corregido un problema que provocaba que los usuarios no pudieran dirigir mensajes de correo electrónico a una lista de distribución personal.</span><span class="sxs-lookup"><span data-stu-id="66433-748">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="66433-749">Se ha corregido un problema que provocaba que los vínculos no se agregaran a los correos electrónicos con el permiso predeterminado incorrecto de espacio empresarial cuando el permiso predeterminado de espacio empresarial se configura como "cualquiera".</span><span class="sxs-lookup"><span data-stu-id="66433-749">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="66433-750">Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.</span><span class="sxs-lookup"><span data-stu-id="66433-750">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="66433-751">Word</span><span class="sxs-lookup"><span data-stu-id="66433-751">Word</span></span>

- <span data-ttu-id="66433-752">Se ha corregido un problema de coautoría si se habilita la Directiva FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="66433-752">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="66433-753">Se ha corregido un problema en el que Word QuickPart no funciona al agregar un campo de búsqueda cuyo nombre se ha cambiado.</span><span class="sxs-lookup"><span data-stu-id="66433-753">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="66433-754">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="66433-754">Office Suite</span></span>

- <span data-ttu-id="66433-755">Se ha corregido un problema que podía hacer que los usuarios experimentaran un uso excesivo de la red y de la CPU durante la coautoría en archivos de PowerPoint grandes.</span><span class="sxs-lookup"><span data-stu-id="66433-755">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="66433-756">Hemos modificado la versión AppV51 para solucionar una regresión de la AppV51 anterior.</span><span class="sxs-lookup"><span data-stu-id="66433-756">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="66433-757">Se ha corregido un problema de bloqueo con el host de Office en Windows cuando se activa un complemento mientras el valor del registro TabProcGrowth era del tipo REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="66433-757">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-june-09"></a><span data-ttu-id="66433-759">Versión 2002: 09 de junio</span><span class="sxs-lookup"><span data-stu-id="66433-759">Version 2002: June 09</span></span>
<span data-ttu-id="66433-760">*Versión 2002 (compilación 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="66433-760">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="66433-761">Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="66433-761">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="66433-763">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="66433-763">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="66433-764">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-764">Excel</span></span>

- <span data-ttu-id="66433-765">Se ha corregido un problema que hacía que el vínculo externo dejara de funcionar después de que se volviera a abrir el archivo si su ruta de acceso era demasiado larga.</span><span class="sxs-lookup"><span data-stu-id="66433-765">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="66433-766">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="66433-766">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="66433-767">Se ha corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.</span><span class="sxs-lookup"><span data-stu-id="66433-767">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="66433-768">Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.</span><span class="sxs-lookup"><span data-stu-id="66433-768">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="66433-769">Insertar una columna en una lista filtrada llevaba más tiempo de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="66433-769">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="66433-770">Se ha corregido un problema por el que un símbolo @ que inicia una fórmula se considera un operador de intersección implícita.</span><span class="sxs-lookup"><span data-stu-id="66433-770">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="66433-771">Outlook</span><span class="sxs-lookup"><span data-stu-id="66433-771">Outlook</span></span>

- <span data-ttu-id="66433-772">Permite unirse a una reunión de Teams directamente a través del cliente nativo de Teams.</span><span class="sxs-lookup"><span data-stu-id="66433-772">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="66433-773">Se ha corregido un problema por el que Outlook no pudo habilitar consejos de directiva para la Protección de pérdida de datos para usuarios que pagaron por el servicio con planes M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="66433-773">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="66433-774">Se ha corregido un problema que provocaba que los usuarios con la configuración de emulación de explorador incorrecta no pudieran completar el mensaje de autenticación de Gmail.</span><span class="sxs-lookup"><span data-stu-id="66433-774">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="66433-775">Se ha corregido un problema que provocaba que los usuarios de Outlook en sistemas operativos de servidor vieran el error: "Estado del antivirus: no válido.</span><span class="sxs-lookup"><span data-stu-id="66433-775">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="66433-776">Esta versión de Windows admite la detección del antivirus, pero no se encontró ninguno" a pesar de tener el antivirus correctamente configurado.</span><span class="sxs-lookup"><span data-stu-id="66433-776">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="66433-777">Word</span><span class="sxs-lookup"><span data-stu-id="66433-777">Word</span></span>

- <span data-ttu-id="66433-778">Se ha corregido un problema por el que la alineación de las palabras de un documento se descomponía al intentar editar después de imprimir con la impresión rápida.</span><span class="sxs-lookup"><span data-stu-id="66433-778">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="66433-779">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="66433-779">Office Suite</span></span>

- <span data-ttu-id="66433-780">Se ha resuelto este problema mediante la actualización de los nombres de canal en el backstage con los nuevos nombres de canal en la bifurcación de enero de 2020.</span><span class="sxs-lookup"><span data-stu-id="66433-780">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="66433-781">Se ha corregido este problema y en adelante, si un dispositivo se administra mediante directiva, no llamará a la API de audiencia de DMS.</span><span class="sxs-lookup"><span data-stu-id="66433-781">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="66433-782">Se ha resuelto el problema en el que había una eliminación incompleta al agregar y quitar aplicaciones en una sola transacción.</span><span class="sxs-lookup"><span data-stu-id="66433-782">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="66433-783">El host de Office se bloqueaba en Windows, cuando se activaba un complemento si la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth estaba establecida en cero.</span><span class="sxs-lookup"><span data-stu-id="66433-783">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="66433-784">Este cambio arreglaría el problema.</span><span class="sxs-lookup"><span data-stu-id="66433-784">This change would fix this issue.</span></span>


[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-may-12"></a><span data-ttu-id="66433-786">Versión 2002: 12 de mayo</span><span class="sxs-lookup"><span data-stu-id="66433-786">Version 2002: May 12</span></span>
<span data-ttu-id="66433-787">*Versión 2002 (compilación 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="66433-787">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="66433-788">Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="66433-788">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="66433-790">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="66433-790">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="66433-791">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-791">Excel</span></span>

- <span data-ttu-id="66433-792">La apertura de un libro de trabajo con referencias a muchos otros libros de trabajo, especialmente con ventanas ocultas, era más lento de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="66433-792">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="66433-793">La apertura de archivos CSV tardaba más de lo esperado en algunas circunstancias.</span><span class="sxs-lookup"><span data-stu-id="66433-793">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="66433-794">Excel se bloqueaba en determinadas circunstancias al cambiar entre libros con diferentes niveles de zoom.</span><span class="sxs-lookup"><span data-stu-id="66433-794">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="66433-795">Se ha corregido un problema con VBA por el que escribir valores en un rango era más lento de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="66433-795">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="66433-796">En ocasiones, los datos copiados de una columna filtrada por color no se pegaban correctamente.</span><span class="sxs-lookup"><span data-stu-id="66433-796">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="66433-797">Se ha corregido un problema que hacía que Excel se bloqueara en ciertos casos después de copiar una hoja que contenía una tabla dinámica.</span><span class="sxs-lookup"><span data-stu-id="66433-797">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="66433-798">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="66433-798">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="66433-799">Se ha corregido un problema por el que la propiedad "Value Crosses At" en el eje del gráfico cambiaba inesperadamente al guardar y volver a abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="66433-799">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="66433-800">El uso de un Range.Value y Range.Value2 (VBA) hacía que las fórmulas se escribieran como matrices dinámicas.</span><span class="sxs-lookup"><span data-stu-id="66433-800">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="66433-801">OneNote</span><span class="sxs-lookup"><span data-stu-id="66433-801">OneNote</span></span>

- <span data-ttu-id="66433-802">Localiza la notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="66433-802">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="66433-803">Muestra una notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.</span><span class="sxs-lookup"><span data-stu-id="66433-803">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="66433-804">Sincronización y estabilidad de servicio mejoradas al reducir temporalmente el número y la frecuencia de sincronización de las páginas del historial de versiones en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="66433-804">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="66433-805">Mejora de la sincronización y la estabilidad del servicio al deshabilitar temporalmente la papelera de reciclaje en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="66433-805">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="66433-806">Cuando un usuario intenta eliminar datos que normalmente se enviarían a la papelera de reciclaje, se le preguntará si prefiere conservarlos o eliminarlos forma permanente.</span><span class="sxs-lookup"><span data-stu-id="66433-806">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="66433-807">Mejora de la sincronización y la estabilidad del servicio al ajustar temporalmente la frecuencia de sincronización en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="66433-807">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="66433-808">Mejora de la sincronización y la estabilidad del servicio al diferir temporalmente la descarga de archivos e imágenes incrustados en los blocs de notas en línea hasta que el usuario navegue a la página en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="66433-808">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="66433-809">Se obtiene una mejora de la sincronización y la estabilidad del servicio al deshabilitar temporalmente la grabación de vídeo en la aplicación en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="66433-809">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="66433-810">La medida no afecta a los blocs de notas locales.</span><span class="sxs-lookup"><span data-stu-id="66433-810">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="66433-811">Mejora de la sincronización y la estabilidad del servicio al reducir temporalmente el tamaño máximo de nuevos datos adjuntos insertados a 50 MB en OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="66433-811">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="66433-812">Si los archivos superan este límite, los usuarios tendrán la opción de cargar el archivo a OneDrive e insertar un vínculo en OneNote.</span><span class="sxs-lookup"><span data-stu-id="66433-812">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="66433-813">Outlook</span><span class="sxs-lookup"><span data-stu-id="66433-813">Outlook</span></span>

- <span data-ttu-id="66433-814">Se ha corregido un problema que provocaba que el ancho del panel de carpetas cambiara inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="66433-814">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="66433-815">Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al intentar abrir archivos .msg y .oft después de una actualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="66433-815">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="66433-816">Se ha corregido un problema que hacía que los usuarios vieran truncado el cuerpo del mensaje al reenviar mensajes HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="66433-816">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="66433-817">Esta actualización corrige un problema en el que con Microsoft Outlook no muestra la etiqueta de confidencialidad actual al ver o redactar mensajes.</span><span class="sxs-lookup"><span data-stu-id="66433-817">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="66433-818">Se ha corregido un problema que provocaba que los usuarios no pudieran dirigir mensajes de correo electrónico a una lista de distribución personal.</span><span class="sxs-lookup"><span data-stu-id="66433-818">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="66433-819">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66433-819">PowerPoint</span></span>

- <span data-ttu-id="66433-820">Se ha corregido un problema para transmitir mensajes correctos para los usuarios que abren una copia de un archivo con comentarios mejorados.</span><span class="sxs-lookup"><span data-stu-id="66433-820">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="66433-821">Word</span><span class="sxs-lookup"><span data-stu-id="66433-821">Word</span></span>

- <span data-ttu-id="66433-822">Se ha corregido el problema por el que Access y Publisher podrían no iniciarse correctamente en función de los idiomas que se hubieran instalado.</span><span class="sxs-lookup"><span data-stu-id="66433-822">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="66433-823">Se ha corregido un problema con la característica Comparar de los documentos protegidos para la edición.</span><span class="sxs-lookup"><span data-stu-id="66433-823">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="66433-824">Se ha corregido un problema al combinar 2 documentos en uno.</span><span class="sxs-lookup"><span data-stu-id="66433-824">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="66433-825">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="66433-825">Office Suite</span></span>

- <span data-ttu-id="66433-826">Esta es una corrección para que la aplicación de Project no bloquee la red cuando el archivo se almacena en caché en el cliente.</span><span class="sxs-lookup"><span data-stu-id="66433-826">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="66433-827">Hemos resuelto el problema por el que una operación interna producía una excepción en caso de error en lugar de registrarlo y continuar.</span><span class="sxs-lookup"><span data-stu-id="66433-827">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="66433-828">Los usuarios afectados ya no serán bloqueados para recibir actualizaciones.</span><span class="sxs-lookup"><span data-stu-id="66433-828">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="66433-829">Este cambio garantiza que el contorno Esbozado funcione correctamente en la cinta de opciones.</span><span class="sxs-lookup"><span data-stu-id="66433-829">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="66433-830">Se ha corregido un problema al abrir archivos de ubicaciones locales con algunas configuraciones de proxy específicas.</span><span class="sxs-lookup"><span data-stu-id="66433-830">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="66433-831">Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.</span><span class="sxs-lookup"><span data-stu-id="66433-831">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="66433-832">Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.</span><span class="sxs-lookup"><span data-stu-id="66433-832">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="66433-833">Esta actualización corrige un problema en Microsoft Word por el que el texto que supera los 255 caracteres insertados durante la aplicación de una etiqueta de confidencialidad no se pudiese identificar y quitar posteriormente cambiando o quitando la etiqueta si la directiva de etiqueta aplicó un encabezado, un pie de página o una marca de agua.</span><span class="sxs-lookup"><span data-stu-id="66433-833">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="66433-834">Se ha corregido un problema que elimina bloqueos durante las sesiones de entrega de Office y se ha mejorado la fiabilidad de la experiencia del usuario.</span><span class="sxs-lookup"><span data-stu-id="66433-834">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="66433-835">Este error actualiza el extremo de la URL del servicio de configuración mejorada (ECS).</span><span class="sxs-lookup"><span data-stu-id="66433-835">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="66433-836">Llamar a este punto de conexión más reciente tiene una tasa de éxito superior para capturar desde ECS.</span><span class="sxs-lookup"><span data-stu-id="66433-836">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2002-april-14"></a><span data-ttu-id="66433-838">Versión 2002: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="66433-838">Version 2002: April 14</span></span>
<span data-ttu-id="66433-839">*Versión 2002 (compilación 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="66433-839">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="66433-840">Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="66433-840">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="66433-841">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="66433-841">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="66433-842">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-842">Excel</span></span>

- <span data-ttu-id="66433-843">**Escriba una fórmula que devuelva varios valores:** Escriba rápidamente una fórmula que devuelva múltiples valores y se derramarán automáticamente en las celdas vecinas.</span><span class="sxs-lookup"><span data-stu-id="66433-843">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="66433-844">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-844">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="66433-845">**Seis potentes funciones:** Seis potentes funciones: Hemos agregado seis nuevas funciones para mejorar las hojas de cálculo: FILTRAR, ORDENAR, ORDENARPOR, UNICOS, SECUENCIA y MATRIZALEAT.</span><span class="sxs-lookup"><span data-stu-id="66433-845">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="66433-846">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-846">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="66433-847">**Busque a la izquierda, busque a la derecha... BUSCARX ya está aquí**: fila por fila, busque lo que necesite en una tabla o un rango con BUSCARX.</span><span class="sxs-lookup"><span data-stu-id="66433-847">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  <span data-ttu-id="66433-848">
  [Más información](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span><span class="sxs-lookup"><span data-stu-id="66433-848">[Learn more](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="66433-850">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="66433-850">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="66433-851">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-851">Excel</span></span>

- <span data-ttu-id="66433-852">Excel se bloqueaba en ciertos casos cuando se volvía a abrir un libro incrustado en Word o PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="66433-852">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="66433-853">Cuando guarda como un archivo CSV, Excel podía combinar todas las columnas en una sola columna en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="66433-853">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="66433-854">Usar Range.ClearContents en un rango de una hoja protegida podía tardar más de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="66433-854">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="66433-855">Corregido un problema con la escala de texto en los controles de formulario cuando se mostraba en la Vista previa de impresión.</span><span class="sxs-lookup"><span data-stu-id="66433-855">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="66433-856">Las macros de VBA que interactúan con la cinta de opciones se pueden ejecutar con ScreenUpdating establecido en True inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="66433-856">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="66433-857">Corregido un problema por el que los enlaces externos no se actualizaban al rellenar (rellenad hacia abajo, rellenar en otros, etc.) si el libro de origen estaba cerrado.</span><span class="sxs-lookup"><span data-stu-id="66433-857">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="66433-858">El uso de Application.Evaluate de VBA no funcionaba para funciones definidas por el usuario en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="66433-858">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="66433-859">Corregido un problema de rendimiento al crear gráficos a partir de plantillas.</span><span class="sxs-lookup"><span data-stu-id="66433-859">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="66433-860">Outlook</span><span class="sxs-lookup"><span data-stu-id="66433-860">Outlook</span></span>

- <span data-ttu-id="66433-861">Corregido un problema que hacía que el encabezado de grupo se expandiera de forma inesperada en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="66433-861">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="66433-862">Corregido un problema que provocaba que los usuarios experimentaran un bloqueo al seleccionar determinados resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="66433-862">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="66433-863">Corregido un problema que causaba que los usuarios experimentaran ocasionalmente un bloqueo al usar el botón X de su ratón.</span><span class="sxs-lookup"><span data-stu-id="66433-863">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="66433-864">Corregido un problema que hacía que el botón Guardar en la nube faltara en las Herramientas de datos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="66433-864">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="66433-865">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66433-865">PowerPoint</span></span>

- <span data-ttu-id="66433-866">Se ha mejorado un escenario de copiar y pegar: al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.</span><span class="sxs-lookup"><span data-stu-id="66433-866">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="66433-867">Proyecto</span><span class="sxs-lookup"><span data-stu-id="66433-867">Project</span></span>

- <span data-ttu-id="66433-868">Corregido un problema por el que Project puede bloquearse al guardar proyectos creados con versiones anteriores de Project.</span><span class="sxs-lookup"><span data-stu-id="66433-868">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="66433-869">Corregido un problema que hace que el evento ProjectBeforeTaskChange no detecte cuándo se ha desactivado o activado una tarea mediante el botón Desactivar.</span><span class="sxs-lookup"><span data-stu-id="66433-869">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="66433-870">Word</span><span class="sxs-lookup"><span data-stu-id="66433-870">Word</span></span>

- <span data-ttu-id="66433-871">Corregido un problema que causaba que los usuarios experimentaran ocasionalmente un bloqueo al usar el botón X de su ratón.</span><span class="sxs-lookup"><span data-stu-id="66433-871">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="66433-872">Corregido un problema con el ajuste de texto en una tabla.</span><span class="sxs-lookup"><span data-stu-id="66433-872">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="66433-873">Corregido un problema donde al insertar líneas horizontales no eran más cortas ni centradas.</span><span class="sxs-lookup"><span data-stu-id="66433-873">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-march-10"></a><span data-ttu-id="66433-875">Versión 2002: 10 de marzo</span><span class="sxs-lookup"><span data-stu-id="66433-875">Version 2002: March 10</span></span>
<span data-ttu-id="66433-876">*Versión 2002 (compilación 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="66433-876">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="66433-877">Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="66433-877">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="66433-879">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="66433-879">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="66433-880">Access</span><span class="sxs-lookup"><span data-stu-id="66433-880">Access</span></span>

- <span data-ttu-id="66433-881">**Buscar tablas vinculadas rápidamente:** nuestro nuevo cuadro de búsqueda hace que buscar tablas vinculadas sea mucho más sencillo.</span><span class="sxs-lookup"><span data-stu-id="66433-881">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="66433-882">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-882">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="66433-883">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-883">Excel</span></span>

- <span data-ttu-id="66433-884">**Logre la atención de sus colegas con** @menciones:\@ use @menciones en los comentarios para avisar a los compañeros de trabajo cuando necesite su participación.</span><span class="sxs-lookup"><span data-stu-id="66433-884">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="66433-885">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-885">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="66433-886">**Encuentre lo que busca:** Realice búsquedas de comandos, personas, archivos, fotos, artículos en la web y más.</span><span class="sxs-lookup"><span data-stu-id="66433-886">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="66433-887">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-887">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="66433-888">**Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su libro.</span><span class="sxs-lookup"><span data-stu-id="66433-888">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="66433-889">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-889">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="66433-890">**Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="66433-890">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="66433-891">**Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. </span><span class="sxs-lookup"><span data-stu-id="66433-891">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="66433-892">**Resalte lo que queda por hacer**: seleccione Resolver para contraer los comentarios y hacer que resalten los elementos abiertos.</span><span class="sxs-lookup"><span data-stu-id="66433-892">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="66433-893">**Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.</span><span class="sxs-lookup"><span data-stu-id="66433-893">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="66433-894">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-894">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="66433-895">**Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los demás.</span><span class="sxs-lookup"><span data-stu-id="66433-895">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="66433-896">**Complemento del visualizador de datos:** Crear rápidamente diagramas de flujo de Visio desde Excel.</span><span class="sxs-lookup"><span data-stu-id="66433-896">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="66433-897">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-897">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="66433-898">**Lea y responda sobre la marcha:** responda a los comentarios y las menciones directamente desde el correo electrónico, sin abrir el libro.</span><span class="sxs-lookup"><span data-stu-id="66433-898">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="66433-899">**Obtenga estadísticas en el libro:** Estadísticas del libro da información general sobre el contenido de un libro, para ayudarle a descubrir más fácilmente su contenido.</span><span class="sxs-lookup"><span data-stu-id="66433-899">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="66433-900">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="66433-900">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="66433-901">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="66433-901">Find them at Insert > Icons.</span></span> [<span data-ttu-id="66433-902">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-902">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="66433-903">Outlook</span><span class="sxs-lookup"><span data-stu-id="66433-903">Outlook</span></span>

- <span data-ttu-id="66433-904">**Conecte su red de LinkedIn con Outlook:** Conecte de forma segura su cuenta de LinkedIn con su cuenta de Microsoft para ver la información de los perfiles de LinkedIn directamente en las tarjetas personales.</span><span class="sxs-lookup"><span data-stu-id="66433-904">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="66433-905">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-905">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="66433-p176">**Todas las opciones de cifrado en un solo lugar:** vaya a Opciones > Cifrar para elegir cómo proteger su mensaje de correo. [Más información](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="66433-p176">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="66433-908">**Insertar el menú de vínculos en Outlook inserta un vínculo con el permiso definido por el administrador de inquilinos:** un vínculo desde Insertar vínculo utilizado recientemente en Outlook insertaba un vínculo que solo funcionaba para los usuarios que ya tenían permisos.</span><span class="sxs-lookup"><span data-stu-id="66433-908">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="66433-909">A menudo esto causaba un intercambio continuo de mensajes de correo electrónico entre los usuarios que pedían acceso a un documento.</span><span class="sxs-lookup"><span data-stu-id="66433-909">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="66433-910">Hemos actualizado esta experiencia para que ahora el vínculo se inserte con el permiso predeterminado establecido por el administrador de inquilinos. Para MSIT se trata de "la organización puede editar", por lo que todos los usuarios internos que reciban un vínculo compartido de esta manera podrán acceder a él.</span><span class="sxs-lookup"><span data-stu-id="66433-910">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="66433-911">**Busque incluso con errores ortográficos o tipográficos:** Outlook encontrará lo que busca, aunque no coincida con la forma exacta en que lo escribió.</span><span class="sxs-lookup"><span data-stu-id="66433-911">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="66433-912">**Ahora es más fácil detectar correos de suplantación de identidad:** los mensajes de correo no deseado y de suplantación de identidad tienen un aspecto diferente para que pueda identificarlos y eliminarlos fácilmente en la bandeja de entrada.</span><span class="sxs-lookup"><span data-stu-id="66433-912">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="66433-913">**Protección avanzada frente a ataques**: con la Protección contra amenazas avanzada de Office 365, estará protegido frente a ataques mediante hipervínculos en asuntos de correos electrónicos, mensajes adjuntos, mensajes firmados, rutas de red, etc.</span><span class="sxs-lookup"><span data-stu-id="66433-913">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="66433-914">**Deja que lo dibuje:** garabatee sobre las imágenes o agregue un Lienzo de dibujo para enviar sus pensamientos con la entrada de lápiz.</span><span class="sxs-lookup"><span data-stu-id="66433-914">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="66433-915">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-915">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="66433-916">**Ver mensajes relevantes en los resultados de búsqueda:** Outlook analiza los términos de búsqueda y muestra los mensajes de correo electrónico más relevantes en la parte superior de los resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="66433-916">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="66433-917">También verá todos los resultados ordenados por fecha en la sección de Resultados principales.</span><span class="sxs-lookup"><span data-stu-id="66433-917">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="66433-918">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-918">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="66433-919">**Obtenga sugerencias de ubicaciones:** Empiece a escribir en Ubicación cuando programe citas y reuniones, Outlook le sugerirá salas, direcciones y otros lugares recientes.</span><span class="sxs-lookup"><span data-stu-id="66433-919">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="66433-920">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-920">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="66433-921">**Encajar más mensajes en la pantalla:** seleccione Ver > Usar espaciado más estrecho para ajustar el espaciado entre mensajes.</span><span class="sxs-lookup"><span data-stu-id="66433-921">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="66433-922">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-922">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="66433-923">**Ver los mensajes bajo otra luz:** use el botón sol/luna para cambiar entre fondos claros y oscuros en el panel de lectura.</span><span class="sxs-lookup"><span data-stu-id="66433-923">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="66433-924">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-924">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="66433-925">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="66433-925">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="66433-926">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="66433-926">Find them at Insert > Icons.</span></span> [<span data-ttu-id="66433-927">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-927">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="66433-928">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66433-928">PowerPoint</span></span>

- <span data-ttu-id="66433-929">**Colaboración rápida en tiempo real en PowerPoint:** colaboración rápida en tiempo real en PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66433-929">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="66433-930">**Nuevas herramientas de revisión:** no se preocupe de las palabras.</span><span class="sxs-lookup"><span data-stu-id="66433-930">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="66433-931">Ahora en PowerPoint se ofrecen sugerencias de gramática y escritura.</span><span class="sxs-lookup"><span data-stu-id="66433-931">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="66433-932">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-932">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="66433-933">**Transcripción y subtítulos en directo:** las palabras del moderador se muestran automáticamente en la pantalla como subtítulos o se traducen en el idioma que prefiera.</span><span class="sxs-lookup"><span data-stu-id="66433-933">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="66433-934">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-934">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="66433-p186">**Usted calcula y nosotros le damos formato:** hemos convertido las expresiones matemáticas escritas a mano en caracteres estándar. Simplemente elija Entrada de lápiz a matemáticas y seleccione las notas escritas a mano para empezar. [Más información](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="66433-p186">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="66433-938">**Encuentre lo que busca:** use el cuadro de búsqueda para buscar texto, comandos, ayuda y mucho más.</span><span class="sxs-lookup"><span data-stu-id="66433-938">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="66433-939">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-939">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="66433-940">**Encuentre los títulos de diapositivas que faltan y escríbalos**: los títulos de diapositivas añaden fuerza a su discurso y permiten que las diapositivas sean accesibles para los usuarios de todas las capacidades.</span><span class="sxs-lookup"><span data-stu-id="66433-940">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="66433-941">El comprobador de accesibilidad le muestra dónde faltan títulos para que pueda agregarlos en el momento.</span><span class="sxs-lookup"><span data-stu-id="66433-941">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="66433-942">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-942">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="66433-943">**Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su presentación.</span><span class="sxs-lookup"><span data-stu-id="66433-943">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="66433-944">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-944">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="66433-945">**Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="66433-945">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="66433-946">**Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. </span><span class="sxs-lookup"><span data-stu-id="66433-946">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="66433-947">**Guarde una ilustración como SVG:** guarde un gráfico, una forma o una ilustración como un gráfico vectorial escalable, que se puede cambiar de tamaño sin perder calidad de imagen.</span><span class="sxs-lookup"><span data-stu-id="66433-947">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="66433-948">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-948">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="66433-949">**Impresión de números de diapositiva en documentos:** los números de diapositiva se incluyen automáticamente en los documentos.</span><span class="sxs-lookup"><span data-stu-id="66433-949">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="66433-950">Ahora es usted quien decide si los deja o los quita.</span><span class="sxs-lookup"><span data-stu-id="66433-950">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="66433-951">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-951">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="66433-952">**Repetición de entrada de lápiz:** cuando haya entradas de lápiz en sus diapositivas, aplique una animación de reproducción para reproducir el dibujo real de la entrada de lápiz durante la presentación con diapositivas.</span><span class="sxs-lookup"><span data-stu-id="66433-952">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="66433-953">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-953">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="66433-954">**Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.</span><span class="sxs-lookup"><span data-stu-id="66433-954">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="66433-955">**Optimizar la presentación para todos:** el comprobador de accesibilidad le ayuda a organizar los objetos de las diapositivas pensando en los lectores de pantalla.</span><span class="sxs-lookup"><span data-stu-id="66433-955">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="66433-956">**Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los usuarios.</span><span class="sxs-lookup"><span data-stu-id="66433-956">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="66433-957">**Una experiencia de vídeo más segura:** las mejoras de seguridad hacen que la experiencia de vídeo en línea sea más segura.</span><span class="sxs-lookup"><span data-stu-id="66433-957">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="66433-958">**¿Para que reinventar lo que puede reutilizar?:** ahorre tiempo usando de nuevo las diapositivas que haya creado o que otros usuarios han compartido con usted.</span><span class="sxs-lookup"><span data-stu-id="66433-958">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="66433-959">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-959">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="66433-960">**Transforme la entrada de lápiz en formas, texto o matemáticas en PowerPoint para Office 365:** convierta la entrada de lápiz en forma libre a formas, textos o expresiones matemáticas de Office en un par de trazos.</span><span class="sxs-lookup"><span data-stu-id="66433-960">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="66433-961">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-961">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="66433-962">**Entrada de tinta para magníficas diapositivas:** convierta el texto de tinta en formas estándar y texto y obtenga ideas de diseño inteligente del Diseñador de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="66433-962">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="66433-963">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-963">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="66433-964">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="66433-964">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="66433-965">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="66433-965">Find them at Insert > Icons.</span></span> [<span data-ttu-id="66433-966">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-966">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="66433-967">Visio</span><span class="sxs-lookup"><span data-stu-id="66433-967">Visio</span></span>

- <span data-ttu-id="66433-968">**Vuelva a la escena del crimen:** use las nuevas plantillas Evidencia, Interior y Exterior en la plantilla Investigación de Escenas de Delitos para recrear con detalle escenarios de delitos.</span><span class="sxs-lookup"><span data-stu-id="66433-968">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="66433-969">**Cree diagramas de Visio elegantes en Excel:** cree un diagrama de flujo o un organigrama con solo escribir datos en una hoja de cálculo.</span><span class="sxs-lookup"><span data-stu-id="66433-969">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="66433-970">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-970">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="66433-971">Word</span><span class="sxs-lookup"><span data-stu-id="66433-971">Word</span></span>

- <span data-ttu-id="66433-972">**El Editor para currículum vítae incorpora el Asistente para currículum vítae de LinkedIn:** el Editor para currículum vítae ofrece una selección de comprobaciones gramaticales y de estilo especialmente adaptadas a los currículums, para que el texto sea más preciso y profesional.</span><span class="sxs-lookup"><span data-stu-id="66433-972">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="66433-973">**Se ha corregido un problema relacionado con los documentos causados por la combinación de objetos 3D:** corrige un problema de daños en un documento producido por la combinación de objetos 3D.</span><span class="sxs-lookup"><span data-stu-id="66433-973">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="66433-974">**Encuentre lo que busca:** use el cuadro de búsqueda para buscar texto, comandos, ayuda y mucho más.</span><span class="sxs-lookup"><span data-stu-id="66433-974">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="66433-975">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-975">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="66433-976">**Colaborando a todo color:** los comentarios y los cambios están codificados por color según la persona que contribuya, por lo que es fácil distinguir entre sus colaboradores.</span><span class="sxs-lookup"><span data-stu-id="66433-976">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="66433-977">**Editar documentos habilitados para macros de forma conjunta:** guarde sus archivos .docm en OneDrive para la Empresa y edítelos con sus colaboradores en tiempo real.</span><span class="sxs-lookup"><span data-stu-id="66433-977">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="66433-978">**Mejoras en la coautoría:** mejora del rendimiento de Word en coautoría en documentos con marcas de revisión.</span><span class="sxs-lookup"><span data-stu-id="66433-978">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="66433-979">**Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos.</span><span class="sxs-lookup"><span data-stu-id="66433-979">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="66433-980">Encuéntrelos en Insertar > Iconos.</span><span class="sxs-lookup"><span data-stu-id="66433-980">Find them at Insert > Icons.</span></span> [<span data-ttu-id="66433-981">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-981">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="66433-982">**Otros usuarios verán los cambios rápidamente**: las mejoras en la coautoría significan que los colaboradores podrán ver los cambios más rápido que nunca.</span><span class="sxs-lookup"><span data-stu-id="66433-982">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="66433-983">**Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su documento.</span><span class="sxs-lookup"><span data-stu-id="66433-983">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="66433-984">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-984">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="66433-985">**Borrar con precisión:** elija entre dos tamaños de borrador para arreglar pequeñas imperfecciones de la entrada de lápiz.</span><span class="sxs-lookup"><span data-stu-id="66433-985">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="66433-986">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-986">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="66433-987">**Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.</span><span class="sxs-lookup"><span data-stu-id="66433-987">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="66433-988">**Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. </span><span class="sxs-lookup"><span data-stu-id="66433-988">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="66433-989">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-989">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="66433-990">**Mejoras en la coautoría:** mejora de la confiabilidad de la coautoría.</span><span class="sxs-lookup"><span data-stu-id="66433-990">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="66433-991">**Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.</span><span class="sxs-lookup"><span data-stu-id="66433-991">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="66433-992">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-992">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="66433-993">**Convertir los archivos para mejorar la accesibilidad**: Actualice los archivos al formato moderno para que sean más accesibles para todos los usuarios.</span><span class="sxs-lookup"><span data-stu-id="66433-993">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="66433-994">**Una experiencia de vídeo más segura:** las mejoras de seguridad hacen que la experiencia de vídeo en línea sea más segura.</span><span class="sxs-lookup"><span data-stu-id="66433-994">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="66433-995">Más información</span><span class="sxs-lookup"><span data-stu-id="66433-995">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="66433-998">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="66433-998">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="66433-999">Acceso</span><span class="sxs-lookup"><span data-stu-id="66433-999">Access</span></span>

- <span data-ttu-id="66433-1000">Esta actualización corrige un problema en Microsoft Access que puede causar el error "La consulta está dañada" cuando se ejecuta una consulta de actualización o cuando se usa una instrucción UPDATE en SQL.</span><span class="sxs-lookup"><span data-stu-id="66433-1000">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="66433-1001">Esta actualización corrige un problema que puede hacer que Microsoft Access no identifique una Columna de identidad en una tabla vinculada de SQL Server, lo que puede provocar que las filas aparezcan como eliminadas de forma incorrecta.</span><span class="sxs-lookup"><span data-stu-id="66433-1001">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="66433-1002">Esta actualización corrige un problema por el que al usar un objeto de grabación de ADODB</span><span class="sxs-lookup"><span data-stu-id="66433-1002">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="66433-1003">en el código de VB, se puede notificar un error incorrectamente.</span><span class="sxs-lookup"><span data-stu-id="66433-1003">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="66433-1004">Las plantillas de Access ya no deberían causar errores en columnas de datos adjuntos en una base de datos.</span><span class="sxs-lookup"><span data-stu-id="66433-1004">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="66433-1005">Después de crear la instancia de una plantilla, ahora debería poder agregar un campo de datos adjuntos a la base de datos.</span><span class="sxs-lookup"><span data-stu-id="66433-1005">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="66433-1006">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-1006">Excel</span></span>

- <span data-ttu-id="66433-1007">Corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.</span><span class="sxs-lookup"><span data-stu-id="66433-1007">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="66433-1008">Este cambio evita un problema con ciertos controladores de gráficos Intel al aprovechar el procesamiento del software.</span><span class="sxs-lookup"><span data-stu-id="66433-1008">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="66433-1009">Se ha corregido un problema que causaba que algunos usuarios experimentasen bloqueos al convertir texto en columnas con celdas que tienen una matriz derramada.</span><span class="sxs-lookup"><span data-stu-id="66433-1009">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="66433-1010">Esta actualización corrige un problema que causaba que la barra de fórmulas mostrara texto en una fuente diferente a la esperada.</span><span class="sxs-lookup"><span data-stu-id="66433-1010">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="66433-1011">La funcionalidad de Texto a columna puede fallar en algunas configuraciones regionales.</span><span class="sxs-lookup"><span data-stu-id="66433-1011">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="66433-1012">Es posible que los usuarios vean un error si acceden a un rango con nombre oculto.</span><span class="sxs-lookup"><span data-stu-id="66433-1012">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="66433-1013">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="66433-1013">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="66433-1014">Corregimos un problema en el que al seleccionar una celda luego de desplazar, podía resultar en la selección de la celda incorrecta.</span><span class="sxs-lookup"><span data-stu-id="66433-1014">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="66433-1015">Excel puede tener problemas al editar un archivo protegido desde una red compartida no confiable.</span><span class="sxs-lookup"><span data-stu-id="66433-1015">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="66433-1016">La funcionalidad de Texto a columna puede fallar en algunas localizaciones.</span><span class="sxs-lookup"><span data-stu-id="66433-1016">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="66433-1017">Es posible que los usuarios vean un error si acceden a un rango con nombre oculto.</span><span class="sxs-lookup"><span data-stu-id="66433-1017">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="66433-1018">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="66433-1018">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="66433-1019">Se ha corregido un problema que algunos usuarios pudieron sufrir con objetos incrustados y vinculados (OLE).</span><span class="sxs-lookup"><span data-stu-id="66433-1019">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="66433-1020">Se ha corregido el botón derecho en el menú de gráficos dinámicos para habilitar la opción de mostrar los detalles.</span><span class="sxs-lookup"><span data-stu-id="66433-1020">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="66433-1021">Se ha resuelto un problema que puede haber causado un bloqueo al buscar archivos recientes cuando no hay ningún libro de trabajo abierto.</span><span class="sxs-lookup"><span data-stu-id="66433-1021">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="66433-1022">Se ha corregido un problema por el que algunos usuarios pueden haber visto varias ventanas emergentes cuando hubiera vínculos externos presentes en el libro.</span><span class="sxs-lookup"><span data-stu-id="66433-1022">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="66433-1023">Se ha corregido un problema por el que los comandos de comentario en el menú contextual no aparecían.</span><span class="sxs-lookup"><span data-stu-id="66433-1023">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="66433-1024">Se ha resuelto un problema en el que no se cargaba la personalización de cinta de opciones al abrir un libro insertado.</span><span class="sxs-lookup"><span data-stu-id="66433-1024">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="66433-1025">Se ha solucionado un problema por el que las funciones CUBEVALUE a veces daban un resultado incorrecto.</span><span class="sxs-lookup"><span data-stu-id="66433-1025">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="66433-1026">Outlook</span><span class="sxs-lookup"><span data-stu-id="66433-1026">Outlook</span></span>

- <span data-ttu-id="66433-1027">Corregido un problema que causó un bloqueo en la experiencia de los comentarios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="66433-1027">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="66433-1028">Corregido un problema que hacía que los usuarios no tuvieran respuesta de Outlook al recuperar la configuración de la nube.</span><span class="sxs-lookup"><span data-stu-id="66433-1028">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="66433-1029">Se ha corregido un problema que provocaba que el cuadro de búsqueda estuviera mal alineado en modo de PPP alto.</span><span class="sxs-lookup"><span data-stu-id="66433-1029">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="66433-1030">Corregido un problema que hacía que los usuarios observaran una fuga de memoria en el proceso de Outlook.</span><span class="sxs-lookup"><span data-stu-id="66433-1030">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="66433-1031">Corregido un problema que hacía que los usuarios vieran correos electrónicos enviados a una dirección que no coincidía con la dirección SMTP mostrada en algunas circunstancias.</span><span class="sxs-lookup"><span data-stu-id="66433-1031">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="66433-1032">Este cambio restaura la capacidad de ver sujetos de varias líneas en el encabezado del mensaje.</span><span class="sxs-lookup"><span data-stu-id="66433-1032">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="66433-1033">Se ha corregido un problema que podía impedir que los archivos se guardaran en una ubicación de WebDAV.</span><span class="sxs-lookup"><span data-stu-id="66433-1033">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="66433-1034">Corregido un problema con la selección del algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="66433-1034">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="66433-1035">Corregido un problema que provocaba que las aplicaciones de terceros no pudiesen enviar correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="66433-1035">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="66433-1036">Se ha solucionado un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "ok" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="66433-1036">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="66433-1037">Se ha corregido un problema que provocaba que los usuarios sufrieran un bloqueo durante la creación del perfil.</span><span class="sxs-lookup"><span data-stu-id="66433-1037">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="66433-1038">Se ha corregido un problema por el que Outlook sincronizaba inesperadamente todo el correo, incluso cuando el deslizador de sincronización estaba configurado en un ajuste menor.</span><span class="sxs-lookup"><span data-stu-id="66433-1038">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="66433-1039">Se corrigió un problema por el que los usuarios con el tema negro veían la lista desplegable "De" con un texto blanco sobre un fondo blanco.</span><span class="sxs-lookup"><span data-stu-id="66433-1039">Addressed an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="66433-1040">Se ha corregido un problema que provocaba que los usuarios experimentaran un error al cancelar la configuración de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="66433-1040">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="66433-1041">Corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.</span><span class="sxs-lookup"><span data-stu-id="66433-1041">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="66433-1042">Se ha corregido un problema que hacía que la opción deshabilitar el resaltado de elementos marcados no se pudiera respetar en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="66433-1042">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="66433-1043">Corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al abrir el cuadro de diálogo Reglas.</span><span class="sxs-lookup"><span data-stu-id="66433-1043">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="66433-1044">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.</span><span class="sxs-lookup"><span data-stu-id="66433-1044">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="66433-1045">Corregido un problema que causaba una fuga de memoria en sesiones de Outlook muy largas.</span><span class="sxs-lookup"><span data-stu-id="66433-1045">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="66433-1046">Corregido un problema que podría resultar en un bloqueo del equipo cuando se veía el mismo elemento en varias ventanas.</span><span class="sxs-lookup"><span data-stu-id="66433-1046">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="66433-1047">Corregido un problema que hacía que los usuarios vieran un retraso notable al interactuar con sus carpetas de buzón de correo a través de métodos abreviados de teclado.</span><span class="sxs-lookup"><span data-stu-id="66433-1047">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="66433-1048">Se ha corregido un problema que provocaba que los usuarios no pudieran abrir algunas instancias de los elementos de calendario periódicos.</span><span class="sxs-lookup"><span data-stu-id="66433-1048">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="66433-1049">Corregido un problema que provocaba que los usuarios con buzones en servidores de Exchange 2010 sufrieran problemas al agregar archivos adjuntos a elementos de calendario.</span><span class="sxs-lookup"><span data-stu-id="66433-1049">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="66433-1050">Se ha corregido un problema que provocaba que los usuarios experimentaran problemas al responder a los mensajes firmados digitalmente.</span><span class="sxs-lookup"><span data-stu-id="66433-1050">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="66433-1051">Se ha corregido un problema que provocaba que el campo Ubicación en las reuniones se actualizara de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="66433-1051">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="66433-1052">Corregido un problema que causaba que las comas en el campo de Ubicación de una reunión se convirtieran en punto y coma.</span><span class="sxs-lookup"><span data-stu-id="66433-1052">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="66433-1053">Corregido un problema que provocaba que la ubicación de una reunión se añadiera a la reunión de forma inesperada después de haberla borrado.</span><span class="sxs-lookup"><span data-stu-id="66433-1053">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="66433-1054">Corregidos problemas relacionados con las reuniones y las citas establecidas en la zona horaria de la Brasil.</span><span class="sxs-lookup"><span data-stu-id="66433-1054">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="66433-1055">Se corrigió un problema por el que se enviaban inesperadamente mensajes de correos electrónicos al presionar la tecla "S" después de cerrar el panel del comprobador de accesibilidad.</span><span class="sxs-lookup"><span data-stu-id="66433-1055">Addressed an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="66433-1056">Esto actualiza la lógica de bloqueo de adjuntos en Outlook para bloquear también los adjuntos de Python.</span><span class="sxs-lookup"><span data-stu-id="66433-1056">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="66433-1057">Se ha corregido un problema que provocaba que los complementos web accedieran a los mensajes administrados con derechos digitales.</span><span class="sxs-lookup"><span data-stu-id="66433-1057">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="66433-1058">Se ha corregido un problema que provocaba que los usuarios sufrieran un bloqueo durante la creación del perfil.</span><span class="sxs-lookup"><span data-stu-id="66433-1058">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="66433-1059">Corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.</span><span class="sxs-lookup"><span data-stu-id="66433-1059">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="66433-1060">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66433-1060">PowerPoint</span></span>

- <span data-ttu-id="66433-1061">Se ha corregido un problema con el método Shape.Paste: cuando el usuario copiaba y pegaba la forma con el método Shape.Paste, se cambiaba la selección a la forma pegada.</span><span class="sxs-lookup"><span data-stu-id="66433-1061">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="66433-1062">Se ha corregido un problema que podía bloquear el equipo al usar el menú contextual en comentarios PPT heredados.</span><span class="sxs-lookup"><span data-stu-id="66433-1062">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="66433-1063">Project</span><span class="sxs-lookup"><span data-stu-id="66433-1063">Project</span></span>

- <span data-ttu-id="66433-1064">Identificamos un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de solo lectura.</span><span class="sxs-lookup"><span data-stu-id="66433-1064">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="66433-1065">Se ha corregido un problema por el que el 100 % de las tareas de tipo duración fija podían tener un cálculo del porcentaje incorrecto con menos del 100 % completado.</span><span class="sxs-lookup"><span data-stu-id="66433-1065">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="66433-1066">Se corrigió un problema en el que las fechas de las tareas de resumen no se calculaban siempre correctamente.</span><span class="sxs-lookup"><span data-stu-id="66433-1066">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="66433-1067">Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="66433-1067">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="66433-1068">Word</span><span class="sxs-lookup"><span data-stu-id="66433-1068">Word</span></span>

- <span data-ttu-id="66433-1069">Corregido un problema ocasional en el que al guardar un archivo existente siempre aparece el cuadro de diálogo Guardar como, pero el archivo nunca se guarda.</span><span class="sxs-lookup"><span data-stu-id="66433-1069">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="66433-1070">El organizador de bloques de creación puede mostrar una alerta no válida: "Ha modificado estilos, bloques de creación".</span><span class="sxs-lookup"><span data-stu-id="66433-1070">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="66433-1071">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="66433-1071">Office Suite</span></span>

- <span data-ttu-id="66433-1072">Este cambio corrige el procesamiento lento de algunos gráficos de dispersión con marcadores.</span><span class="sxs-lookup"><span data-stu-id="66433-1072">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="66433-1073">Este cambio resuelve problemas con adaptadores gráficos que aprovechan la GPU integrada de Intel.</span><span class="sxs-lookup"><span data-stu-id="66433-1073">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="66433-1074">Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa solo funciona la primera vez que se establece. Ahora, la corrección permite establecer una fecha límite relativa para las actualizaciones posteriores.</span><span class="sxs-lookup"><span data-stu-id="66433-1074">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="66433-1075">Se ha corregido un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.</span><span class="sxs-lookup"><span data-stu-id="66433-1075">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="66433-1076">Corrige un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.</span><span class="sxs-lookup"><span data-stu-id="66433-1076">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-february-11"></a><span data-ttu-id="66433-1078">Versión 1908: 11 de febrero</span><span class="sxs-lookup"><span data-stu-id="66433-1078">Version 1908: February 11</span></span>
<span data-ttu-id="66433-1079">*Versión 1908 (Compilación 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="66433-1079">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="66433-1080">Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="66433-1080">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="66433-1082">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="66433-1082">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="66433-1083">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-1083">Excel</span></span>

- <span data-ttu-id="66433-1084">Esta actualización corrige un problema que provoca un error siempre que se utilizaba VBA para agregar una imagen al encabezado o pie de página de un gráfico.</span><span class="sxs-lookup"><span data-stu-id="66433-1084">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="66433-1085">Se ha corregido un problema que hacía que el borde de un control de cuadro de grupo no estuviera visible en la vista previa de impresión o al imprimirlo.</span><span class="sxs-lookup"><span data-stu-id="66433-1085">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="66433-1086">Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.</span><span class="sxs-lookup"><span data-stu-id="66433-1086">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="66433-1087">Se ha corregido un problema por el que el tamaño de archivo de las imágenes en los encabezados del gráfico aumentaba cuando se guardaba el libro que contenía el gráfico.</span><span class="sxs-lookup"><span data-stu-id="66433-1087">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="66433-1088">Se ha corregido un problema que provoca la corrupción de caracteres DBCS en los libros con referencias cruzadas manteniendo los rangos de selección sincronizados con el libro con referencias cruzadas.</span><span class="sxs-lookup"><span data-stu-id="66433-1088">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="66433-1089">Se ha corregido un problema en el que los controles de casilla podían reducirse al usar el autoajuste para ajustar el alto de fila.</span><span class="sxs-lookup"><span data-stu-id="66433-1089">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="66433-1090">Outlook</span><span class="sxs-lookup"><span data-stu-id="66433-1090">Outlook</span></span>

- <span data-ttu-id="66433-1091">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.</span><span class="sxs-lookup"><span data-stu-id="66433-1091">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="66433-1092">Se ha corregido un problema que provocaba que los usuarios experimentaran errores de sincronización al procesar mensajes de conflicto.</span><span class="sxs-lookup"><span data-stu-id="66433-1092">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="66433-1093">Se ha corregido un problema que provocaba que los usuarios experimentaran un error en la pantalla de carga del perfil al iniciar Outlook.</span><span class="sxs-lookup"><span data-stu-id="66433-1093">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="66433-1094">Se ha corregido un problema que provocaba que los usuarios viesen bloqueos intermitentes al cambiar de vista.</span><span class="sxs-lookup"><span data-stu-id="66433-1094">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="66433-1095">Se ha corregido un problema que causaba que los usuarios sufrieran un error al visualizar más de 30 calendarios en un entorno Citrix.</span><span class="sxs-lookup"><span data-stu-id="66433-1095">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="66433-1096">[Aquí](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) está la KB individual, donde se ha documentado esto para versiones anteriores.</span><span class="sxs-lookup"><span data-stu-id="66433-1096">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="66433-1097">Corrige un problema que provocaba que los usuarios tuvieran problemas al intentar sincronizar carpetas del calendario compartido con el OST, lo que producía errores en los permisos al tratar de interactuar con estas carpetas.</span><span class="sxs-lookup"><span data-stu-id="66433-1097">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="66433-1098">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66433-1098">PowerPoint</span></span>

- <span data-ttu-id="66433-1099">Se ha mejorado un escenario de copiar y pegar. Al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.</span><span class="sxs-lookup"><span data-stu-id="66433-1099">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="66433-1100">Se ha corregido un problema que producía un rendimiento más lento entre los usuarios de colaboración.</span><span class="sxs-lookup"><span data-stu-id="66433-1100">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="66433-1101">Se ha corregido un problema que puede producirse cuando un archivo que se abre incrementalmente contiene una diapositiva con más de una secuencia multimedia incrustada.</span><span class="sxs-lookup"><span data-stu-id="66433-1101">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="66433-1102">Se ha corregido un problema por el que es posible que la barra de mensajes de advertencia de seguridad no aparezca para los complementos en los que no se confía al iniciar PowerPoint por primera vez.</span><span class="sxs-lookup"><span data-stu-id="66433-1102">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="66433-1103">Project</span><span class="sxs-lookup"><span data-stu-id="66433-1103">Project</span></span>

- <span data-ttu-id="66433-1104">Se ha corregido un problema en el que el trabajo real puede ser diferente entre el parte de horas y el plan del proyecto debido a que los calendarios de recursos no se actualizan cuando cambia el calendario base.</span><span class="sxs-lookup"><span data-stu-id="66433-1104">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="66433-1105">Word</span><span class="sxs-lookup"><span data-stu-id="66433-1105">Word</span></span>

- <span data-ttu-id="66433-1106">Se ha corregido un bloqueo en Word al dejar una API obsoleta.</span><span class="sxs-lookup"><span data-stu-id="66433-1106">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="66433-1107">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="66433-1107">Office Suite</span></span>

- <span data-ttu-id="66433-1108">Este cambio corrige el procesamiento de imágenes después de abrir un archivo dañado.</span><span class="sxs-lookup"><span data-stu-id="66433-1108">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-january-14"></a><span data-ttu-id="66433-1110">Versión 1908: 14 de enero</span><span class="sxs-lookup"><span data-stu-id="66433-1110">Version 1908: January 14</span></span>
<span data-ttu-id="66433-1111">*Versión 1908 (compilación 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="66433-1111">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="66433-1112">Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="66433-1112">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="66433-1114">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="66433-1114">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="66433-1115">Excel</span><span class="sxs-lookup"><span data-stu-id="66433-1115">Excel</span></span>

- <span data-ttu-id="66433-1116">La información clave en holandés para el título del documento ha sido cambiada a Alt-G.</span><span class="sxs-lookup"><span data-stu-id="66433-1116">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="66433-1117">Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo insertado.</span><span class="sxs-lookup"><span data-stu-id="66433-1117">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="66433-1118">Hubo un problema en el que no se podían seleccionar elementos del cuadro combinado de un formulario de WPF (Windows Presentation Foundation) que fue abierto por un complemento.</span><span class="sxs-lookup"><span data-stu-id="66433-1118">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="66433-1119">Outlook</span><span class="sxs-lookup"><span data-stu-id="66433-1119">Outlook</span></span>

- <span data-ttu-id="66433-1120">Se ha corregido un problema por el que los usuarios notaban un retraso evidente al interactuar con sus carpetas de buzón mediante métodos abreviados de teclado.</span><span class="sxs-lookup"><span data-stu-id="66433-1120">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="66433-1121">Corregido un problema que hacía que no se mostraran las sugerencias de política cuando se utilizaba un remitente alternativo.</span><span class="sxs-lookup"><span data-stu-id="66433-1121">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="66433-1122">Corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.</span><span class="sxs-lookup"><span data-stu-id="66433-1122">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="66433-1123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66433-1123">PowerPoint</span></span>

- <span data-ttu-id="66433-1124">Arreglamos un problema cuando al copiar una diapositiva de una presentación a otra, se pueden crear patrones duplicados.</span><span class="sxs-lookup"><span data-stu-id="66433-1124">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="66433-1125">Los archivos con nuevos comentarios modernos mostrarán una advertencia amarilla si se abren en una versión no soportada</span><span class="sxs-lookup"><span data-stu-id="66433-1125">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="66433-1126">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="66433-1126">Office Suite</span></span>

- <span data-ttu-id="66433-1127">Se ha solucionado un problema por el que los mensajes de actualización de Office aparecían en un idioma diferente al esperado.</span><span class="sxs-lookup"><span data-stu-id="66433-1127">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="66433-1128">En el futuro, los mensajes de actualización de Office coincidirán correctamente con el idioma de visualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="66433-1128">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="66433-1129">Corregido un problema en el que una actualización no se aplicaría en ciertos casos en los que el usuario no es un administrador y la cuenta del sistema no tenía conectividad de red.</span><span class="sxs-lookup"><span data-stu-id="66433-1129">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

> [!NOTE]
> <span data-ttu-id="66433-1131">Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="66433-1131">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (NO MODIFICAR EL INICIO DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20506|version-2102-abril-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20294|versión-2102-marzo-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21216|versión-9-febrero-2008|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21064|versión-12-enero-2008|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20910|versión-08-diciembre-2008|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20760|versión-10-noviembre-2008|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|versión-13-octubre-2008|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-septiembre-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20988|version-2002-11-agosto|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|version-2002-july-14|)
[//]: # (NO MODIFICAR EL FIN DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
