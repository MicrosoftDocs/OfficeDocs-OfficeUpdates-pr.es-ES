---
title: Notas de la versión del canal actual (versión preliminar)
ms.author: anankani
author: anankani
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Proporcionar a los participantes del Modo aplazado de Insider la lista más reciente de las nuevas características, correcciones o problemas conocidos
ms.openlocfilehash: a06b009c006645b9effb686be7f7b0d8a9286609
ms.sourcegitcommit: d08938d8d38c545afc40f3e4316990d916e0ba91
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 06/04/2021
ms.locfileid: "52742229"
---
# <a name="release-notes-for-office-current-channel-preview"></a><span data-ttu-id="abe28-103">Notas de la versión del canal actual de Office (versión preliminar)</span><span class="sxs-lookup"><span data-stu-id="abe28-103">Release Notes for Office Current Channel (Preview)</span></span>

<span data-ttu-id="abe28-104">En este artículo hay notas de la versión para las compilaciones del Canal actual (versión preliminar) de las versiones de escritorio de Word, Excel, PowerPoint, Outlook, Access, Project Y Teams para Windows.</span><span class="sxs-lookup"><span data-stu-id="abe28-104">This article contains release notes for Current Channel (Preview) builds of Word, Excel, PowerPoint, Outlook, Access, Project, and Teams for Windows desktop.</span></span> <span data-ttu-id="abe28-105">Todas las semanas se incluyen las nuevas características, correcciones importantes y los problemas principales de mayor interés para usted.</span><span class="sxs-lookup"><span data-stu-id="abe28-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="abe28-106">Tenga en cuenta que a menudo publicamos características (y a veces incluso correcciones) para el Canal actual (versión preliminar) durante un período de tiempo.</span><span class="sxs-lookup"><span data-stu-id="abe28-106">Note that we often roll out features (and sometimes even fixes) to Current Channel (Preview) over a period of time.</span></span> <span data-ttu-id="abe28-107">Esto nos permite asegurarnos de que todo funciona correctamente antes de publicar la característica para un público más amplio.</span><span class="sxs-lookup"><span data-stu-id="abe28-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="abe28-108">Por tanto, si a continuación no ve algo descrito, no se preocupe, lo recibirá con el tiempo.</span><span class="sxs-lookup"><span data-stu-id="abe28-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  


> [!NOTE]
> - <span data-ttu-id="abe28-109">La fecha de publicación de las notas de versión pueden no coincidir con la fecha real de lanzamiento de la compilación.</span><span class="sxs-lookup"><span data-stu-id="abe28-109">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="abe28-110">Las características de Microsoft Teams pueden diferir de la última versión preliminar del Canal actual publicada ya que tienen una cadencia de publicación más frecuente.</span><span class="sxs-lookup"><span data-stu-id="abe28-110">Microsoft Teams features may differ from the latest Current Channel Preview released as they have a more frequent release cadence.</span></span>

[//]: # (NO ELIMINAR)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

## <a name="version-2105-june-01"></a><span data-ttu-id="abe28-113">Versión 2105: 1 de junio</span><span class="sxs-lookup"><span data-stu-id="abe28-113">Version 2105: June 01</span></span>
<span data-ttu-id="abe28-114">*Versión 2105 (Compilación 14026.20254)*</span><span class="sxs-lookup"><span data-stu-id="abe28-114">*Version 2105 (Build 14026.20254)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-116">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-116">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-117">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-117">Outlook</span></span>

- <span data-ttu-id="abe28-118">**Último inicio de sesión/Inicio de sesión sospechoso:** Outlook ahora le indica cuándo y dónde iniciado sesión por última vez en su cuenta y le avisa si se detecta actividad de inicio de sesión sospechosa</span><span class="sxs-lookup"><span data-stu-id="abe28-118">**Last Sign In / Suspicious Sign In:** Outlook now tells you when and where you last signed into your account, and alerts you if any suspicious sign-in activity is detected</span></span>

- <span data-ttu-id="abe28-119">**Habilitar las mejoras del calendario compartido:** Outlook puede actualizar los calendarios compartidos en Office 365 con la API de REST.</span><span class="sxs-lookup"><span data-stu-id="abe28-119">**Turn on shared calendar improvements:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="abe28-120">Active la vista previa para obtener actualizaciones más rápidas y confiables de los calendarios compartidos.</span><span class="sxs-lookup"><span data-stu-id="abe28-120">Turn on the preview for faster and more reliable updates to shared calendars.</span></span><br /><span data-ttu-id="abe28-121">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/shared-calendars-improvements-in-outlook-for-windows)</span><span class="sxs-lookup"><span data-stu-id="abe28-121">See details in [blog post](https://insider.office.com/es-ES/blog/shared-calendars-improvements-in-outlook-for-windows)</span></span>

- <span data-ttu-id="abe28-122">**Sugerencia de productividad del Comprobador de accesibilidad al enviar correos electrónicos a usuarios externos de listas de distribución de gran tamaño:** Hemos agregado la funcionalidad para que mostrar automáticamente una notificación, mediante una información sobre correo, ante una infracción de accesibilidad al redactar un correo electrónico para grandes audiencias, usuarios externos, etc. Esta configuración se encuentra en Accesibilidad</span><span class="sxs-lookup"><span data-stu-id="abe28-122">**Accessibility Checker nudge when sending emails to large DL, external users:** We added the functionally to get prompted automatically, through a mailtip, of an accessibility violation while composing an email to large audiences, external users, etc. These settings live in the Ease of Access</span></span><br /><span data-ttu-id="abe28-123">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/sending-accessible-emails-in-outlook-for-windows)</span><span class="sxs-lookup"><span data-stu-id="abe28-123">See details in [blog post](https://insider.office.com/es-ES/blog/sending-accessible-emails-in-outlook-for-windows)</span></span>

### <a name="visio"></a><span data-ttu-id="abe28-124">Visio</span><span class="sxs-lookup"><span data-stu-id="abe28-124">Visio</span></span>

- <span data-ttu-id="abe28-125">**Formas y galerías de símbolos de AWS:** ahora tenemos galerías de símbolos con las formas de AWS más recientes para ayudarle a crear diagramas.</span><span class="sxs-lookup"><span data-stu-id="abe28-125">**AWS stencils and shapes:** We now have stencils with the latest AWS shapes to help you create diagrams.</span></span> [<span data-ttu-id="abe28-126">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-126">Learn more</span></span>](https://support.office.com/article/138206bf-d10f-4583-9f31-885ce706af49)




[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-129">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-129">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-130">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-130">Outlook</span></span>

- <span data-ttu-id="abe28-131">Hemos solucionado un problema que podía provocar un cierre inesperado al interactuar con el Correo de Outlook o las Vistas de Calendario.</span><span class="sxs-lookup"><span data-stu-id="abe28-131">We fixed an issue that may cause a unexpected close when interacting with Outlook Mail or Calendar Views.</span></span>




[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2105-may-23"></a><span data-ttu-id="abe28-133">Versión 2105: 23 de mayo</span><span class="sxs-lookup"><span data-stu-id="abe28-133">Version 2105: May 23</span></span>
<span data-ttu-id="abe28-134">*Versión 2105 (Compilación 14026.20246)*</span><span class="sxs-lookup"><span data-stu-id="abe28-134">*Version 2105 (Build 14026.20246)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-136">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-136">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="abe28-137">Teams</span><span class="sxs-lookup"><span data-stu-id="abe28-137">Teams</span></span>

- <span data-ttu-id="abe28-138">**Anuncio de las vistas del panel de datos de asistencia:** Ya no es necesario descargar manualmente los informes, ahora Teams le permite ver todos los datos agregados en la vista del panel con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="abe28-138">**Announcing attendance data dashboard views:** No longer do you need to manually download reports, Teams now allows you to view all aggregated data in a one click dashboard view</span></span>

- <span data-ttu-id="abe28-139">**Funciones de seguridad, cumplimiento y protección de datos para aplicaciones:** para las aplicaciones de Microsoft 365 Certified Teams, los administradores pueden ver las funciones de seguridad, cumplimiento y protección de datos en una nueva pestaña de la página de detalles de la aplicación en el Centro de administración de Teams.</span><span class="sxs-lookup"><span data-stu-id="abe28-139">**Security, compliance, and data protection capabilities for apps:** For Microsoft 365 Certified Teams apps, admins can view security, compliance, and data protection capabilities in a new tab on the app's detail page in the Teams Admin Center.</span></span> <span data-ttu-id="abe28-140">Esta transparencia ofrece a los clientes de Microsoft confianza en las aplicaciones que ejecutan sus organizaciones.</span><span class="sxs-lookup"><span data-stu-id="abe28-140">This transparency gives Microsoft customers trust in the applications that run their organizations.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-143">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-143">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-144">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-144">Outlook</span></span>

- <span data-ttu-id="abe28-145">Se ha corregido un problema que causaba que algunas instrucciones de la característica "Acortar reuniones" no estuvieran disponibles a través de las tecnologías de lector de pantalla.</span><span class="sxs-lookup"><span data-stu-id="abe28-145">We fixed an issue that caused some instructions for the "Shorten Meetings" feature to be unavailable through screen reader technologies.</span></span>


- <span data-ttu-id="abe28-146">Se ha corregido un problema que causaba que algunos usuarios se cerraran de forma inesperada al cargar tarjetas de persona.</span><span class="sxs-lookup"><span data-stu-id="abe28-146">We fixed an issue that caused some users to experience unexpectedly closed when loading person cards.</span></span>


- <span data-ttu-id="abe28-147">Hemos agregado una clave del Registro que deshabilita la nueva experiencia del Buscador de salas (la misma experiencia que en Outlook para Web) y habilita el Buscador de salas heredado con Horas sugeridas.</span><span class="sxs-lookup"><span data-stu-id="abe28-147">We added a registry key that disables the new Room Finder experience (the same experience as in Outlook for Web) and enables the legacy Room Finder with Suggested Times.</span></span>
    - <span data-ttu-id="abe28-148">Clave del Registro:</span><span class="sxs-lookup"><span data-stu-id="abe28-148">Registry Key:</span></span>

        > <span data-ttu-id="abe28-149">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span><span class="sxs-lookup"><span data-stu-id="abe28-149">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span></span> </br>
        > <span data-ttu-id="abe28-150">REG_DWORD “ShowLegacyRoomFinder”</span><span class="sxs-lookup"><span data-stu-id="abe28-150">REG_DWORD “ShowLegacyRoomFinder”</span></span></br></br>
        > <span data-ttu-id="abe28-151">0 (predeterminado): Outlook usa la nueva experiencia con tecnología del Buscador de salas de OWA cuando el usuario hace clic en el botón "Buscador de salas" para buscar salas disponibles.</span><span class="sxs-lookup"><span data-stu-id="abe28-151">0 (default) - Outlook uses new Room Finder OWA Powered eXperience when user clicks 'Room Finder' button to search for available rooms</span></span>  </br>
        > <span data-ttu-id="abe28-152">1: Outlook usa la interfaz de usuario del Buscador de salas heredada para buscar salas disponibles</span><span class="sxs-lookup"><span data-stu-id="abe28-152">1 - Outlook uses legacy Room Finder UI to search for available rooms</span></span> </br>


### <a name="project"></a><span data-ttu-id="abe28-153">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-153">Project</span></span>

- <span data-ttu-id="abe28-154">Se ha corregido un problema que hacía que las tareas de las tareas programadas manualmente se movieran a una fecha incorrecta.</span><span class="sxs-lookup"><span data-stu-id="abe28-154">Fixed an issue where assignments on manually scheduled tasks may be moved to an incorrect date.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2105-may-19"></a><span data-ttu-id="abe28-156">Versión 2105: 19 de mayo</span><span class="sxs-lookup"><span data-stu-id="abe28-156">Version 2105: May 19</span></span>
<span data-ttu-id="abe28-157">*Versión 2105 (Compilación 14026.20202)*</span><span class="sxs-lookup"><span data-stu-id="abe28-157">*Version 2105 (Build 14026.20202)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-159">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-159">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="abe28-160">Teams</span><span class="sxs-lookup"><span data-stu-id="abe28-160">Teams</span></span>

- <span data-ttu-id="abe28-161">**Los seminarios web de Teams se integran con Dynamics 365 Marketing para consolidar clientes potenciales:** Con esta característica, los organizadores de seminarios web pueden fomentar la participación posterior al evento con los asistentes al usar D365 Marketing.</span><span class="sxs-lookup"><span data-stu-id="abe28-161">**Teams Webinars integrate with Dynamics 365 Marketing to enable lead nurturing:** With this feature, webinar organizers can drive post event engagement with registrants by leveraging D365 Marketing.</span></span> <span data-ttu-id="abe28-162">Los datos de participación de los asistentes se sincronizan con la organización de D365 Marketing y habilitan recorridos de usuario automatizados</span><span class="sxs-lookup"><span data-stu-id="abe28-162">The attendee engagement data syncs with D365 Marketing org and enabled automated user journeys</span></span>

- <span data-ttu-id="abe28-163">**Oradores inteligentes:** Los oradores inteligentes son periféricos inteligentes para las salas de Microsoft Teams en Windows.</span><span class="sxs-lookup"><span data-stu-id="abe28-163">**Intelligent speakers:** Intelligent speakers are intelligent peripherals for Microsoft Teams Rooms on Windows.</span></span> <span data-ttu-id="abe28-164">Mostrarán una transcripción del orador correspondiente a los participantes de la sala de reuniones, lo que permitirá a los asistentes dedicar menos tiempo a tomar notas y seguir fácilmente lo que se dice en la sala.</span><span class="sxs-lookup"><span data-stu-id="abe28-164">They will bring speaker attributed transcription for participants in the meeting room, enabling attendees to spend less time note-taking and easily follow along who said what in the room.</span></span>

- <span data-ttu-id="abe28-165">**Permitir a los usuarios de Teams comprar aplicaciones de Teams a través del cliente de Teams:** Los usuarios de Teams ahora tienen la posibilidad de comprar suscripciones de la aplicación de Teams desde la tienda de Teams.</span><span class="sxs-lookup"><span data-stu-id="abe28-165">**Enable Teams users to purchase Teams apps through Teams client:** Teams users have now the ability to purchase Teams app subscriptions from the Teams store.</span></span>

- <span data-ttu-id="abe28-166">**Crear Teams con plantillas de equipo:** Con plantillas en Teams, los usuarios pueden elegir entre una variedad de plantillas personalizables al crear un nuevo equipo, lo que les ayuda a empezar con rapidez.</span><span class="sxs-lookup"><span data-stu-id="abe28-166">**Create Teams with Team Templates:** With Templates in Teams, users can choose from a variety of customizable templates when creating a new team, helping them get started quickly.</span></span> <span data-ttu-id="abe28-167">Asimismo, los administradores de TI pueden crear plantillas personalizadas para su organización, lo que les permite normalizar estructuras de equipo, preinstalar aplicaciones relevantes y escalar procedimientos recomendados.</span><span class="sxs-lookup"><span data-stu-id="abe28-167">IT Admins can also create custom templates for their organization, allowing them to standardize team structures, preinstall relevant apps, and scale best practices.</span></span> <span data-ttu-id="abe28-168">Los administradores de TI pueden elegir qué plantillas de Teams se mostrarán a los usuarios finales en el Centro de administración de Teams y, además, preconfigurar las pestañas del sitio web agregando direcciones URL a una pestaña del sitio web en una plantilla de equipo.</span><span class="sxs-lookup"><span data-stu-id="abe28-168">IT Admins can choose which team templates to show to end users in Teams Admin Center, and also preconfigure website tabs by adding URLs to a website tab in a team template.</span></span>

- <span data-ttu-id="abe28-169">**Usar anotaciones de lápiz y puntero láser en PowerPoint Live en Teams:** Estamos introduciendo el puntero láser virtual y las anotaciones para que los presentadores puedan compartir contenido de forma eficaz y atraer la atención del público hacia determinadas secciones de la presentación de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="abe28-169">**Use laser pointer and ink annotations in PowerPoint Live in Teams:** We are introducing virtual laser pointer and annotations so presenters can effectively share content and engage their audience by drawing attention to certain sections of the PowerPoint deck.</span></span> <span data-ttu-id="abe28-170">De la misma forma que usaría un punto láser físico en una sala, PowerPoint Live le permite apuntar de forma eficaz a diferentes lugares para que el público pueda seguir fácilmente lo que hay en la diapositiva.</span><span class="sxs-lookup"><span data-stu-id="abe28-170">Just as you would use a physical laser point in a room, PowerPoint Live allows you to effectively point at different places so the audience can easily follow along what’s on the slide.</span></span>

- <span data-ttu-id="abe28-171">**Recomendaciones de flujo de Power Automate con plantillas de equipo 1P:** Plantillas de flujo de Power Automate para Surface para equipos creados a partir de plantillas de equipo 1P</span><span class="sxs-lookup"><span data-stu-id="abe28-171">**Power Automate flow recommendations with 1P Team Templates:** Surface Power Automate flow templates for teams created from 1P team templates</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-174">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-174">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-175">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-175">Outlook</span></span>

- <span data-ttu-id="abe28-176">Hemos corregido un problema que causaba que la opción de comentarios no se mostrara a los usuarios de la versión preliminar de Office Perpetual 2021.</span><span class="sxs-lookup"><span data-stu-id="abe28-176">We fixed an issue that caused the feedback option unable to appear for users of the Office Perpetual 2021 preview.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2105-may-12"></a><span data-ttu-id="abe28-178">Versión 2105: 12 de mayo</span><span class="sxs-lookup"><span data-stu-id="abe28-178">Version 2105: May 12</span></span>
<span data-ttu-id="abe28-179">*Versión 2105 (compilación 14026.20164)*</span><span class="sxs-lookup"><span data-stu-id="abe28-179">*Version 2105 (Build 14026.20164)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-181">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-181">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="abe28-182">Teams</span><span class="sxs-lookup"><span data-stu-id="abe28-182">Teams</span></span>

- <span data-ttu-id="abe28-183">**Configuración de preferencias de usuario para abrir archivos de forma predeterminada en Escritorio (o) Explorador (o) Teams:** los usuarios pueden establecer su preferencia predeterminada como Explorador, Escritorio o Teams al abrir archivos de Office (Word, Excel y Power Point) que se comparten en Teams. La configuración de Escritorio puede seleccionarse si están instalados y activados los clientes de Office más recientes.</span><span class="sxs-lookup"><span data-stu-id="abe28-183">**User preference setting to open files by default in Desktop (or) Browser (or) Teams:** Users can set their default preference as Browser, Desktop or Teams when opening Office (Word, Excel, and Power Point) files that are shared in Teams.Desktop setting can be selected if latest Office clients are installed and activated</span></span>

- <span data-ttu-id="abe28-184">**Modo en paralelo y reportero en reuniones de Teams:** ahora puede aparecer junto al contenido para obtener una presentación y una experiencia de consumo más atractivas.</span><span class="sxs-lookup"><span data-stu-id="abe28-184">**Reporter and Side-by-Side Mode in Teams meetings:** You can now appear next to your content for a more engaging presentation and consumption experience</span></span>

- <span data-ttu-id="abe28-185">**Disponibilidad general de las capacidades de seminario web de Teams:** programe y realice seminarios web de 1 000 personas con la misma aplicación de Teams que usa para reuniones.</span><span class="sxs-lookup"><span data-stu-id="abe28-185">**Teams webinar capabilities general availability:** Schedule and deliver 1,000 person webinars with the same Teams app you use for meetings!</span></span> <span data-ttu-id="abe28-186">Las funcionalidades de seminario web admiten la creación de páginas de registro, confirmación de correo electrónico para los solicitantes de registro, administración del host para audio y vídeo de asistentes, informes de asistentes y características interactivas, como sondeos, chat y reacciones.</span><span class="sxs-lookup"><span data-stu-id="abe28-186">Webinar capabilities support registration page creation, email confirmation for registrants, host management for attendee video and audio, attendee reporting, plus interactive features like polls, chat and reactions.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-189">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-189">Resolved issues</span></span>
### <a name="word"></a><span data-ttu-id="abe28-190">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-190">Word</span></span>

- <span data-ttu-id="abe28-191">Se ha corregido un problema por el que las tarjetas contextuales de lienzo de ortografía y gramática mostraban botones de iconos, pero esos botones no tenían información sobre herramientas.</span><span class="sxs-lookup"><span data-stu-id="abe28-191">Fixed an issue where canvas contextual cards for spelling and grammar show icon buttons, but those buttons have no tooltips.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2105-may-07"></a><span data-ttu-id="abe28-193">Versión 2105: 07 de mayo</span><span class="sxs-lookup"><span data-stu-id="abe28-193">Version 2105: May 07</span></span>
<span data-ttu-id="abe28-194">*Versión 2105 (compilación 14026.20138)*</span><span class="sxs-lookup"><span data-stu-id="abe28-194">*Version 2105 (Build 14026.20138)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-196">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-196">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="abe28-197">Teams</span><span class="sxs-lookup"><span data-stu-id="abe28-197">Teams</span></span>

- <span data-ttu-id="abe28-198">**Presentamos los diseños en las reuniones de Teams:** ahora puede aparecer sobre todo el contenido para obtener una presentación y una experiencia de consumo más inmersivas</span><span class="sxs-lookup"><span data-stu-id="abe28-198">**Introducing layouts to Teams meetings:** Now you can appear overlaid ontop of content for a more immersive presentation and consumption experience</span></span>

- <span data-ttu-id="abe28-199">**Deshabilitar la cámara para asistentes específicos:** los organizadores de la reunión y los presentadores pueden deshabilitar las cámaras de asistentes específicos de una reunión de Teams para asegurarse de que no comparten el vídeo en la reunión.</span><span class="sxs-lookup"><span data-stu-id="abe28-199">**Disable Camera for Specific Attendees:** Meeting Organizers and Presenters can disable the cameras of specific Attendees in a Teams Meeting to make sure they don't share video in the meeting.</span></span>

- <span data-ttu-id="abe28-200">**Deshabilitar la cámara para todos los asistentes:** los organizadores de la reunión y los presentadores pueden deshabilitar las cámaras de todos los asistentes de una reunión de Teams para asegurarse de que no comparten el vídeo en la reunión.</span><span class="sxs-lookup"><span data-stu-id="abe28-200">**Disable Camera for All Attendees:** Meeting Organizers and Presenters can disable the cameras of all Attendees in a Teams Meeting to make sure they don't share video in the meeting.</span></span>

- <span data-ttu-id="abe28-201">**Los usuarios anónimos pueden presentar:** al hospedar un evento en directo de Teams, hemos agregado la capacidad de que los usuarios anónimos se unan a un evento en directo para que también puedan presentar durante el evento.</span><span class="sxs-lookup"><span data-stu-id="abe28-201">**Anonymous users can present:** When hosting a Teams live event, we added the ability for an anonymous users to join a Live Event and so that they can also present during the event.</span></span>

- <span data-ttu-id="abe28-202">**Administrar etiquetas en Teams mediante programación: las API de etiquetas de Microsoft Teams están ahora en versión preliminar pública:** este conjunto de API se puede usar para asignar mediante programación etiquetas de usuarios en un equipo, haciendo que la creación y el mantenimiento de etiquetas sea más rápido y más fácil.</span><span class="sxs-lookup"><span data-stu-id="abe28-202">**Manage tags in Teams programmatically - Microsoft Teams Tags APIs are now in public preview:** This set of APIs can be used to programmatically assign users tags in a team, making tag creation and maintenance faster and easier.</span></span>  <span data-ttu-id="abe28-203">Las etiquetas de Teams permiten a los usuarios llegar rápidamente a un grupo de personas sin tener que @mencionar o escribir el nombre de todos.</span><span class="sxs-lookup"><span data-stu-id="abe28-203">Tags in Teams let users quickly reach a group of people without having to @mention or type out everyone.</span></span> <span data-ttu-id="abe28-204">Para más información sobre las etiquetas en equipos, consulte Uso de etiquetas en Teams.</span><span class="sxs-lookup"><span data-stu-id="abe28-204">For more information on tag in teams, see Using tags in Teams.</span></span> <span data-ttu-id="abe28-205">Al usar estas nuevas API, los desarrolladores ahora pueden crear etiquetas en un equipo y asignar a usuarios, obtener una lista de etiquetas en un equipo, actualizar etiquetas y eliminar etiquetas</span><span class="sxs-lookup"><span data-stu-id="abe28-205">Using these new APIs, developers can nowCreate tags in a team and assign usersGet a list of tags in a team Update tagsDelete tags</span></span>

- <span data-ttu-id="abe28-206">**Presentar desde PowerPoint en Teams:** presente las diapositivas directamente desde la aplicación de PowerPoint en una reunión de Teams a través de PowerPoint Live.</span><span class="sxs-lookup"><span data-stu-id="abe28-206">**Present from PowerPoint to Teams:** Present your slides directly from the PowerPoint app to a Teams meeting via PowerPoint Live.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-209">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-209">Resolved issues</span></span>
### <a name="word"></a><span data-ttu-id="abe28-210">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-210">Word</span></span>

- <span data-ttu-id="abe28-211">Corrige un problema con el que no se abre en el panel del Editor.</span><span class="sxs-lookup"><span data-stu-id="abe28-211">Fixes an issue where the Editor Pane doesn't open.</span></span>


### <a name="office-suite"></a><span data-ttu-id="abe28-212">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-212">Office Suite</span></span>

- <span data-ttu-id="abe28-213">RelNotesNotNeeded</span><span class="sxs-lookup"><span data-stu-id="abe28-213">RelNotesNotNeeded</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2105-may-03"></a><span data-ttu-id="abe28-215">Versión 2105: 03 de mayo</span><span class="sxs-lookup"><span data-stu-id="abe28-215">Version 2105: May 03</span></span>
<span data-ttu-id="abe28-216">*Versión 2105 (Compilación 14026.20052)*</span><span class="sxs-lookup"><span data-stu-id="abe28-216">*Version 2105 (Build 14026.20052)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-218">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-218">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="abe28-219">Teams</span><span class="sxs-lookup"><span data-stu-id="abe28-219">Teams</span></span>

- <span data-ttu-id="abe28-220">**Poner en primer plano varios usuarios al mismo tiempo en una reunión:** Ahora los organizadores y los presentadores pueden poner en primer plano varios participantes simultáneamente durante las reuniones.</span><span class="sxs-lookup"><span data-stu-id="abe28-220">**Spotlight multiple users at the same time in a meeting:** Organizers and presenters can now spotlight multiple participants simultaneously during meetings.</span></span> <span data-ttu-id="abe28-221">El espacio de reunión mostrará a esos participantes en primer plano, con sus vídeos o avatares, para todos los demás participantes de la reunión.</span><span class="sxs-lookup"><span data-stu-id="abe28-221">The meeting stage will show these spotlighted participants, with their videos or avatars, to everyone in the meeting.</span></span>

- <span data-ttu-id="abe28-222">**Presentar desde PowerPoint en Teams:** Presente las diapositivas directamente desde la aplicación de PowerPoint en una reunión de Teams a través de PowerPoint Live.</span><span class="sxs-lookup"><span data-stu-id="abe28-222">**Present from PowerPoint to Teams:** Present your slides directly from the PowerPoint app to a Teams meeting via PowerPoint Live.</span></span>

- <span data-ttu-id="abe28-223">**Nueva experiencia de administración de etiquetas y otras mejoras:** Las Etiquetas en Teams permiten a los usuarios llegar rápidamente a un grupo de usuarios sin tener que @mencionar o escribir cada uno. La experiencia de administración de etiquetas ahora es una Pestaña. Las etiquetas ahora también tienen un campo de descripción para que pueda agregar más detalles a una etiqueta.</span><span class="sxs-lookup"><span data-stu-id="abe28-223">**New manage tag experience and other enhancements:** Tags in Teams let users quickly reach a group of people without having to @mention or type out everyone.The manage tags experience is now a Tab. Tags also now have a description field so that you can add more details to a tag.</span></span> <span data-ttu-id="abe28-224">La nueva Pestaña Etiquetas será la página de inicio de las notificaciones y la búsqueda de etiquetas, que también estará disponible próximamente.</span><span class="sxs-lookup"><span data-stu-id="abe28-224">The new Tags Tab will be the landing page for tag notifications and search for tags, which is also coming soon.</span></span>

- <span data-ttu-id="abe28-225">**Oradores inteligentes:** Los oradores inteligentes son periféricos inteligentes para las salas de Microsoft Teams en Windows.</span><span class="sxs-lookup"><span data-stu-id="abe28-225">**Intelligent Speakers:** Intelligent speakers are intelligent peripherals for Microsoft Teams Rooms on Windows.</span></span> <span data-ttu-id="abe28-226">Mostrarán una transcripción del orador correspondiente a los participantes de la sala de reuniones, lo que permitirá a los asistentes dedicar menos tiempo a tomar notas y seguir fácilmente lo que se dice en la sala.</span><span class="sxs-lookup"><span data-stu-id="abe28-226">They will bring speaker attributed transcription for participants in the meeting room, enabling attendees to spend less time note-taking and easily follow along who said what in the room.</span></span>

- <span data-ttu-id="abe28-227">**Cambiar la notificación nativa predeterminada para equipos púrpuras para nuevos usuarios:** Las notificaciones nativas ofrecen una serie de ventajas, como el soporte para el centro de acción, la accesibilidad, el soporte para el modo de asistencia de foco, etc. Actualmente el estilo de notificación predeterminado para un nuevo usuario en Microsoft Teams es el Equipo Púrpura.</span><span class="sxs-lookup"><span data-stu-id="abe28-227">**Changing default to native notification from teams purple for new users:** Native Notifications provide a host of benefits like support for action center, accessibility, support for focus assist mode e.t.c.Currently the default notification style for a new user in Microsoft teams is Teams Purple.</span></span> <span data-ttu-id="abe28-228">Con este cambio, el valor predeterminado para el nuevo usuario cambiará a Notificación nativa.</span><span class="sxs-lookup"><span data-stu-id="abe28-228">With this change the default for new user will change to Native Notification.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-231">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-231">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-232">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-232">Excel</span></span>

- <span data-ttu-id="abe28-233">Hemos corregido un problema que causaba que Excel se cerrara de forma inesperada al usar Office de 32 bits en Windows de 64 bits.</span><span class="sxs-lookup"><span data-stu-id="abe28-233">We fixed an issue that caused Excel to close unexpectedly when using 32 bit Office on 64 bit Windows.</span></span>


- <span data-ttu-id="abe28-234">Hemos corregido un problema que hacía que Excel se cerrara inesperadamente al desplazarse por los comentarios del panel Comentarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-234">We fixed an issue that caused Excel to close unexpectedly when moving through comments in the Comments pane.</span></span>


- <span data-ttu-id="abe28-235">Se ha corregido un problema por el que algunos complementos de automatización para Excel no se podían cargar.</span><span class="sxs-lookup"><span data-stu-id="abe28-235">Fixed an issue where some automation add-ins for Excel unable to load.</span></span>


- <span data-ttu-id="abe28-236">Hemos corregido un problema que causaba que Narrador leyese incorrectamente las propiedades de dos botones de la pestaña Encabezado y pie de página del cuadro de diálogo Configurar página.</span><span class="sxs-lookup"><span data-stu-id="abe28-236">We fixed an issue that caused Narrator to incorrectly read the properties of two buttons on the Header/Footer tab in the Page Setup dialog box.</span></span>


- <span data-ttu-id="abe28-237">Hemos corregido un problema que causaba que algunos libros vinculados en otras aplicaciones de Office se cerraran sin guardar los cambios al ejecutar el Vínculo de actualización.</span><span class="sxs-lookup"><span data-stu-id="abe28-237">We fixed an issue that caused some workbooks linked in other Office applications to close without saving changes when running Update Link.</span></span>


- <span data-ttu-id="abe28-238">Se ha corregido un problema en el que el complemento de Herramientas para análisis no funcionaba para algunos usuarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-238">Fixed an issue where the Analysis ToolPak add-in did not work for some users.</span></span>


- <span data-ttu-id="abe28-239">Hemos corregido un problema que en ocasiones producía errores al abrir algunos archivos en la Vista protegida.</span><span class="sxs-lookup"><span data-stu-id="abe28-239">We fixed an issue where some files would occasionally fail to open in Protected View</span></span>


- <span data-ttu-id="abe28-240">Hemos corregido un problema que causaba que el formato de fecha se mostrara de forma incorrecta en algunos idiomas al usar complementos.</span><span class="sxs-lookup"><span data-stu-id="abe28-240">We fixed an issue that caused date formatting to be displayed incorrectly in some languages when using add-ins.</span></span>


- <span data-ttu-id="abe28-241">Hemos corregido un problema que causaba que la barra de estado no indicara el estado de Listo para algunos usuarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-241">We fixed an issue that caused the status bar to not indicate a Ready state for some users.</span></span>


- <span data-ttu-id="abe28-242">Hemos realizado un cambio para permitir que el Administrador de nombres se abra en libros con un gran número de nombres ocultos.</span><span class="sxs-lookup"><span data-stu-id="abe28-242">We made a change to enable the Name Manager to open on books with a large number of hidden names.</span></span>


- <span data-ttu-id="abe28-p115">Hemos corregido un problema para ofrecer compatibilidad con versiones anteriores de Excel. El problema podía provocar que un archivo que se guardaba en una versión más reciente de Excel no se cargara correctamente en versiones anteriores de Excel debido a  funciones como SI.ERROR y BUSCARX agregadas a Excel desde Office 2007.</span><span class="sxs-lookup"><span data-stu-id="abe28-p115">We fixed an issue to support backward compatibility with older versions of Excel. The issue may cause a file that is saved in a more recent version of Excel failed to load properly in older versions of Excel due to  functions such as IFERROR and XLOOKUP added to Excel since Office 2007.</span></span>


- <span data-ttu-id="abe28-245">Hemos corregido un problema que podía provocar que Excel se cerrara de forma inesperada al usar Pegado especial con formatos en determinadas situaciones.</span><span class="sxs-lookup"><span data-stu-id="abe28-245">We fixed an issue which could cause Excel to close unexpectedly when using Paste Special with formats in certain situations.</span></span>


### <a name="outlook"></a><span data-ttu-id="abe28-246">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-246">Outlook</span></span>

- <span data-ttu-id="abe28-247">Hemos corregido un problema que causaba que Outlook anulara las preferencias de la Bandeja de entrada Prioritarios configuradas en OWA.</span><span class="sxs-lookup"><span data-stu-id="abe28-247">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>


- <span data-ttu-id="abe28-248">Hemos corregido un problema que provocaba que los usuarios de la configuración de itinerancia experimentaran bloqueos.</span><span class="sxs-lookup"><span data-stu-id="abe28-248">We fixed an issue that caused users of roaming settings to experience hangs .</span></span>


- <span data-ttu-id="abe28-249">Hemos corregido un problema que provocaba que se deshabilitara la resolución de nombres al enviar en nombre de otro usuario y al resolver en una libreta de direcciones que no era la Lista global de direcciones.</span><span class="sxs-lookup"><span data-stu-id="abe28-249">We fixed an issue that caused name resolution disabled when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


- <span data-ttu-id="abe28-250">Hemos corregido un problema que provocaba que algunos usuarios de la característica de uso compartido del calendario experimentaran problemas al interactuar con su calendario en el panel de navegación.</span><span class="sxs-lookup"><span data-stu-id="abe28-250">We fixed an issue that caused some users of the calendar sharing improvements feature to experience issues with interacting with their calendar in the navigation pane.</span></span>


- <span data-ttu-id="abe28-251">Hemos corregido un problema que causaba que Outlook se cerrara de forma inesperada al usar el modo de Contraste alto durante largos períodos de tiempo.</span><span class="sxs-lookup"><span data-stu-id="abe28-251">We fixed an issue where using High Contrast mode for extended periods of time would caused Outlook to close unexpectedly.</span></span>


- <span data-ttu-id="abe28-252">Hemos corregido un problema en el que los hipervínculos que incluyen dígitos se deshabilitarían al redactar un mensaje en Outlook en un idioma de derecha a izquierda.</span><span class="sxs-lookup"><span data-stu-id="abe28-252">We fixed an issue where hyperlinks including digits would be disable when composing a message in Outlook in a right-to-left language.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="abe28-253">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-253">PowerPoint</span></span>

- <span data-ttu-id="abe28-254">Se ha corregido un problema relacionado con las imágenes vinculadas.</span><span class="sxs-lookup"><span data-stu-id="abe28-254">Fixes an issue related to linked pictures.</span></span>


### <a name="project"></a><span data-ttu-id="abe28-255">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-255">Project</span></span>

- <span data-ttu-id="abe28-256">Hemos corregido un problema que provocaba que los cambios realizados con los Asistentes para planificación no siempre se capturaran con eventos de cambio.</span><span class="sxs-lookup"><span data-stu-id="abe28-256">We fixed an issue where changes done through Planning Wizards weren't always captured by change events.</span></span>


- <span data-ttu-id="abe28-257">Hemos corregido un problema en el que los usuarios no podían quitar proyectos del grupo de recursos.</span><span class="sxs-lookup"><span data-stu-id="abe28-257">We fixed an issue where users were unable to remove projects from the resource pool.</span></span>


### <a name="visio"></a><span data-ttu-id="abe28-258">Visio</span><span class="sxs-lookup"><span data-stu-id="abe28-258">Visio</span></span>

- <span data-ttu-id="abe28-259">Hemos corregido un problema que ha provocado que Visio se cerrara de forma inesperada con la compilación reciente.</span><span class="sxs-lookup"><span data-stu-id="abe28-259">We fixed an issue which caused Visio closed unexpectedly with recent build.</span></span>


### <a name="word"></a><span data-ttu-id="abe28-260">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-260">Word</span></span>

- <span data-ttu-id="abe28-261">Hemos corregido un problema por el cual se conservaba el formato de texto después de quitar los hipervínculos.</span><span class="sxs-lookup"><span data-stu-id="abe28-261">We fixed an issue where text formatting remains after removing hyperlinks.</span></span>


- <span data-ttu-id="abe28-262">Hemos corregido un problema que hacía que el texto de marcador de posición se recortara en los comentarios al usar idiomas de derecha a izquierda.</span><span class="sxs-lookup"><span data-stu-id="abe28-262">We fixed a issue where placeholder text was clipped in comments when using right-to-left languages.</span></span>


- <span data-ttu-id="abe28-263">Hemos corregido un problema que hacía que los comentarios no se mostraran después de filtrar por usuario.</span><span class="sxs-lookup"><span data-stu-id="abe28-263">We fixed an issue where comments are not displayed after filtering by people.</span></span>


- <span data-ttu-id="abe28-264">Hemos corregido un problema que impedía a Word combinar correspondencia con una base de datos de Access.</span><span class="sxs-lookup"><span data-stu-id="abe28-264">We fixed an issue where Word was unable to perform a Mail Merge with an Access database.</span></span>


- <span data-ttu-id="abe28-265">Hemos corregido un problema que hacía que estuviera disponible la capacidad de contraer los márgenes de los documentos que contuvieran varias columnas.</span><span class="sxs-lookup"><span data-stu-id="abe28-265">We fixed an issue that caused the ability to collapse margins in a document containing multiple columns to be available.</span></span>


- <span data-ttu-id="abe28-266">Hemos corregido un problema que impedía que algunos caracteres se mostraran correctamente en las celdas de la tabla cuando había comentarios en el documento.</span><span class="sxs-lookup"><span data-stu-id="abe28-266">We fixed an issue where some characters are not displayed correctly in table cells when there are comments in the document.</span></span>


- <span data-ttu-id="abe28-267">Hemos corregido un problema por el cual se producían los cambios en el formato de archivo al guardar documentos con el complemento AIP habilitado.</span><span class="sxs-lookup"><span data-stu-id="abe28-267">We fixed an issue where the file format changes occurred when saving documents with the AIP add-in enabled.</span></span>


- <span data-ttu-id="abe28-268">Hemos corregido un problema que hacía que Word no respondiera al editar campos.</span><span class="sxs-lookup"><span data-stu-id="abe28-268">We fixed an issue where Word would become unresponsive when editing fields.</span></span>


- <span data-ttu-id="abe28-269">Hemos corregido un problema por el que la etiqueta de confidencialidad desaparecía de un archivo en Word después de cargar el archivo en SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="abe28-269">We fixed an issue where the sensitivity label disappears from a file in Word after uploading the file to SharePoint Online.</span></span>


- <span data-ttu-id="abe28-270">Hemos corregido un problema por el cual no se solicitaba a los usuarios guardar documentos al usar un comando (en lugar del método abreviado de teclado CTRL+S).</span><span class="sxs-lookup"><span data-stu-id="abe28-270">We fixed an issue where users would not be prompted to save documents when using a command (rather than the CTRL+S keyboard shortcut).</span></span>


- <span data-ttu-id="abe28-271">Corregido un problema que podría provocar el cierre inesperado de Word al desconectarse debido a que el usuario cerraba o reiniciaba su equipo.</span><span class="sxs-lookup"><span data-stu-id="abe28-271">Fixes an issue that may caused Word unexpectedly closed when shutting down due to the user logging off or restarting their computer.</span></span>


- <span data-ttu-id="abe28-272">Hemos corregido un problema por el cual se conservaba el formato de texto después de quitar los hipervínculos.</span><span class="sxs-lookup"><span data-stu-id="abe28-272">We fixed an issue where text formatting remains after removing hyperlinks.</span></span>


### <a name="office-suite"></a><span data-ttu-id="abe28-273">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-273">Office Suite</span></span>

- <span data-ttu-id="abe28-274">Hemos corregido un problema que causaba que el botón de dictado estuviera mal alineado al agregar comentarios a un documento.</span><span class="sxs-lookup"><span data-stu-id="abe28-274">We fixed an issue that caused the Dictation button to be misaligned when adding comments to a document.</span></span>


- <span data-ttu-id="abe28-275">Se ha corregido un problema al analizar una cadena de procesamiento de emojis que hacía que la aplicación se cerrara inesperadamente al leer fuera de los límites de una matriz</span><span class="sxs-lookup"><span data-stu-id="abe28-275">Fixed an issue when parsing a string for emoji processing that casued application closed unexpectedly when reading outside of the bounds of an array</span></span>


- <span data-ttu-id="abe28-276">Hemos corregido un problema que hacía que algunos Scalable Vector Graphics (SVG) no se representasen correctamente.</span><span class="sxs-lookup"><span data-stu-id="abe28-276">We fixed an issue where some Scalable Vector Graphics (SVG) did not render correctly.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2104-april-28"></a><span data-ttu-id="abe28-278">Versión 2104: 28 de abril</span><span class="sxs-lookup"><span data-stu-id="abe28-278">Version 2104: April 28</span></span>
<span data-ttu-id="abe28-279">*Versión 2104 (compilación 13929.20296)*</span><span class="sxs-lookup"><span data-stu-id="abe28-279">*Version 2104 (Build 13929.20296)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-281">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-281">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="abe28-282">Teams</span><span class="sxs-lookup"><span data-stu-id="abe28-282">Teams</span></span>

- <span data-ttu-id="abe28-283">**Selector de emojis expandido:** La actualización de emojis expandida ofrece a los usuarios un lugar más divertido y expresivo en Teams.</span><span class="sxs-lookup"><span data-stu-id="abe28-283">**Expanded Emoji Picker:** The expanded emoji update offers people more fun and expressiveness in Teams.</span></span> <span data-ttu-id="abe28-284">También introduce una mayor variedad en términos de diversidad y representación.</span><span class="sxs-lookup"><span data-stu-id="abe28-284">It also introduces a wider range of diversity and representation.</span></span> <span data-ttu-id="abe28-285">El conjunto de emojis se ha expandido de 85 a más de 800 emojis, con selector de categorías, selector de tono de piel y selector de código abreviado.</span><span class="sxs-lookup"><span data-stu-id="abe28-285">The emoji set has expanded from 85 to over 800 emojis, with a category selector, skin tone selector and shortcode picker.</span></span>

- <span data-ttu-id="abe28-286">**Microsoft Teams: Experiencia de Compartir en reuniones revisada:** La interfaz de usuario de la característica Compartir en reuniones de Microsoft Teams se ha rediseñado para ayudar a los presentadores a encontrar más rápido y fácilmente el contenido deseado.</span><span class="sxs-lookup"><span data-stu-id="abe28-286">**Microsoft Teams: Revised in-meeting Share experience:** The user interface for the in-meeting Share feature in Microsoft Teams has been redesigned to help presenters find their desired content more quickly and easily.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-289">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-289">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-290">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-290">Excel</span></span>

- <span data-ttu-id="abe28-291">Se ha corregido un problema por el que algunos complementos de automatización de Excel no se cargan.</span><span class="sxs-lookup"><span data-stu-id="abe28-291">Fixed a problem where some automation add-ins for Excel failed to load.</span></span>


### <a name="outlook"></a><span data-ttu-id="abe28-292">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-292">Outlook</span></span>

- <span data-ttu-id="abe28-293">Hemos corregido un problema que provocaba que los usuarios experimentaran bloqueos.</span><span class="sxs-lookup"><span data-stu-id="abe28-293">We fixed an issue that caused users of roaming settings to experience hangs .</span></span>


### <a name="powerpoint"></a><span data-ttu-id="abe28-294">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-294">PowerPoint</span></span>

- <span data-ttu-id="abe28-295">Hemos corregido un problema relacionado con las imágenes vinculadas.</span><span class="sxs-lookup"><span data-stu-id="abe28-295">We fixed an issue related to linked pictures.</span></span>


### <a name="project"></a><span data-ttu-id="abe28-296">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-296">Project</span></span>

- <span data-ttu-id="abe28-297">Se ha corregido un problema en el que los usuarios no podían quitar proyectos del grupo de recursos.</span><span class="sxs-lookup"><span data-stu-id="abe28-297">Fixed an issue where users were unable to remove projects from the resource pool.</span></span>


### <a name="word"></a><span data-ttu-id="abe28-298">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-298">Word</span></span>

- <span data-ttu-id="abe28-299">Hemos realizado un cambio en la edición del objeto OLE.</span><span class="sxs-lookup"><span data-stu-id="abe28-299">We made a change on editing OLE object.</span></span>



[//]: # (NO QUITAR FINAL DE CONTENIDO CON DETALLES DE ERROR)

## <a name="version-2104-april-26"></a><span data-ttu-id="abe28-301">Versión 2104: 26 de abril</span><span class="sxs-lookup"><span data-stu-id="abe28-301">Version 2104: April 26</span></span>
<span data-ttu-id="abe28-302">*Versión 2104 (Compilación 13929.20254)*</span><span class="sxs-lookup"><span data-stu-id="abe28-302">*Version 2104 (Build 13929.20254)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-304">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-304">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-305">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-305">Outlook</span></span>

- <span data-ttu-id="abe28-306">**Habilitar las mejoras del calendario compartido:** Outlook puede actualizar los calendarios compartidos en Office 365 con la API de REST.</span><span class="sxs-lookup"><span data-stu-id="abe28-306">**Turn on shared calendar improvements:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="abe28-307">Active la vista previa para obtener actualizaciones más rápidas y confiables de los calendarios compartidos.</span><span class="sxs-lookup"><span data-stu-id="abe28-307">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-310">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-310">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-311">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-311">Excel</span></span>

- <span data-ttu-id="abe28-312">Hemos corregido un problema que en ocasiones producía errores al abrir algunos archivos en la Vista protegida.</span><span class="sxs-lookup"><span data-stu-id="abe28-312">We fixed an issue where some files would occasionally fail to open in Protected View</span></span>


### <a name="outlook"></a><span data-ttu-id="abe28-313">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-313">Outlook</span></span>

- <span data-ttu-id="abe28-314">Hemos corregido un problema que causaba que Outlook anulara las preferencias de la Bandeja de entrada Prioritarios configuradas en OWA.</span><span class="sxs-lookup"><span data-stu-id="abe28-314">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>



[//]: # (NO QUITAR FINAL DE CONTENIDO CON DETALLES DE ERROR)

## <a name="version-2104-april-19"></a><span data-ttu-id="abe28-316">Versión 2104: 19 de abril</span><span class="sxs-lookup"><span data-stu-id="abe28-316">Version 2104: April 19</span></span>
<span data-ttu-id="abe28-317">*Versión 2104 (compilación 13929.20216)*</span><span class="sxs-lookup"><span data-stu-id="abe28-317">*Version 2104 (Build 13929.20216)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-319">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-319">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-320">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-320">Excel</span></span>

- <span data-ttu-id="abe28-321">**Importar datos de matrices dinámicas:** ahora puede importar, dar forma y actualizar datos de matrices dinámicas en el libro actual.</span><span class="sxs-lookup"><span data-stu-id="abe28-321">**Import data from dynamic arrays:** You can now import, shape and refresh data from dynamic arrays in the current workbook.</span></span> [<span data-ttu-id="abe28-322">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-322">Learn more</span></span>](https://support.office.com/article/205c6b06-03ba-4151-89a1-87a7eb36e531)

### <a name="outlook"></a><span data-ttu-id="abe28-323">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-323">Outlook</span></span>

- <span data-ttu-id="abe28-324">**Búsqueda de Calendario mejorada:** mejoras en la búsqueda de Calendario, la mayor de las cuales es la capacidad de encontrar más fácilmente la siguiente repetición de una serie en los resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="abe28-324">**Improved Calendar Search:** Improvements have been made to Calendar search, largest of which is the ability to more easily find the next occurence of a series in search results.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-327">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-327">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="abe28-328">Access</span><span class="sxs-lookup"><span data-stu-id="abe28-328">Access</span></span>

- <span data-ttu-id="abe28-329">Este cambio corrige un problema por el que al ejecutar una consulta que pasara por SQL Server, se mostraba en algunos casos un mensaje de error que alertaba de un "estado de cursor no válido".</span><span class="sxs-lookup"><span data-stu-id="abe28-329">This change fixes an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


- <span data-ttu-id="abe28-330">Hemos corregido un problema por el que, cuando una aplicación externa solicitaba una interfaz de accesibilidad, nos impedía cerrar hasta que se liberaba su referencia.</span><span class="sxs-lookup"><span data-stu-id="abe28-330">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


### <a name="excel"></a><span data-ttu-id="abe28-331">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-331">Excel</span></span>

- <span data-ttu-id="abe28-332">Hemos corregido un problema que bloqueaba la capacidad de pegar como fórmulas en una hoja protegida.</span><span class="sxs-lookup"><span data-stu-id="abe28-332">We fixed a problem that was preventing the ability to paste as formulas on a protected sheet.</span></span>


- <span data-ttu-id="abe28-333">Hemos corregido un problema por el que los hipervínculos creados con la función HIPERVINCULO no funcionaban si el archivo se guardaba como un documento PDF.</span><span class="sxs-lookup"><span data-stu-id="abe28-333">We fixed an issue in which hyperlinks created using the HYPERLINK function would not work if the file was saved as a PDF document.</span></span>


- <span data-ttu-id="abe28-334">Hemos corregido un problema que causaba que se agregara un símbolo de operador implícito (@) a la fórmula con una referencia a un intervalo vacío y proporcionara potencialmente un resultado incorrecto.</span><span class="sxs-lookup"><span data-stu-id="abe28-334">We fixed an issue where an implicit operator (@) symbol would be added to the formula with a reference to an empty range and potentially give the incorrect result.</span></span>


### <a name="outlook"></a><span data-ttu-id="abe28-335">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-335">Outlook</span></span>

- <span data-ttu-id="abe28-336">Hemos corregido un problema que causaba que algunos usuarios experimentasen un cierre inesperado de Outlook al sincronizar los cambios en la jerarquía de carpetas.</span><span class="sxs-lookup"><span data-stu-id="abe28-336">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


- <span data-ttu-id="abe28-337">Hemos corregido un problema que causaba que los usuarios vieran por error un mensaje de "Esto puede tardar un poco" mientras añadían algún elemento a un calendario.</span><span class="sxs-lookup"><span data-stu-id="abe28-337">We fixed an issue that cause users to erroneously see a "This may take a while" message when adding a calendar.</span></span>


- <span data-ttu-id="abe28-338">Hemos solucionado un problema que hacía que los delegados aparecieran como organizadores de reuniones creadas en calendarios recién añadidos.</span><span class="sxs-lookup"><span data-stu-id="abe28-338">We fixed an issue that caused delegates to appear as the organizer of meetings created on newly added calendars.</span></span>  <span data-ttu-id="abe28-339">Las reuniones en este estado no aparecían en el calendario del principal.</span><span class="sxs-lookup"><span data-stu-id="abe28-339">Meetings in this state did not appear on the principal's calendar.</span></span>


- <span data-ttu-id="abe28-340">Hemos corregido un problema que provocaba que los usuarios experimentaran un bloqueo al buscar.</span><span class="sxs-lookup"><span data-stu-id="abe28-340">We fixed an issue that caused users to experience a crash when searching.</span></span>


- <span data-ttu-id="abe28-341">Hemos corregido un bloqueo relacionado con la búsqueda.</span><span class="sxs-lookup"><span data-stu-id="abe28-341">We fixed a search related crash.</span></span>


- <span data-ttu-id="abe28-342">Hemos corregido un problema que provocaba que los usuarios vieran desaparecer las firmas de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="abe28-342">We fixed an issue that caused users to see signatures disappear unexpectedly.</span></span>


- <span data-ttu-id="abe28-343">Hemos corregido un problema que podía provocar que los usuarios vieran el mensaje que indica que están redactando perder el foco de la interfaz de usuario.</span><span class="sxs-lookup"><span data-stu-id="abe28-343">We fixed an issue that could cause users to see the message that they are composing losing the UI focus.</span></span>


- <span data-ttu-id="abe28-344">Hemos corregido un problema que causaba que Outlook anulara las preferencias de la Bandeja de entrada Prioritarios configuradas en OWA.</span><span class="sxs-lookup"><span data-stu-id="abe28-344">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>


- <span data-ttu-id="abe28-345">Hemos corregido un problema que causaba que los usuarios de la característica Configuración de la nube vieran que se reemplazaba la configuración personalizada por la configuración predeterminada después de configurar Outlook en un nuevo dispositivo.</span><span class="sxs-lookup"><span data-stu-id="abe28-345">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="abe28-346">Hemos corregido un problema que causaba que algunas personas no pudieran tener acceso a las firmas asociadas con cuentas de correo secundarias.</span><span class="sxs-lookup"><span data-stu-id="abe28-346">We fixed an issue that caused some people to be unable to access signatures associated with secondary mail accounts.</span></span>


- <span data-ttu-id="abe28-347">Hemos corregido un problema que provocaba errores en la resolución de nombres al enviar en nombre de otro usuario y al resolver en una libreta de direcciones que no es la Lista global de direcciones.</span><span class="sxs-lookup"><span data-stu-id="abe28-347">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


- <span data-ttu-id="abe28-348">Hemos corregido un problema que provocaba errores en la resolución de nombres al enviar en nombre de otro usuario y al resolver en una libreta de direcciones que no es la Lista global de direcciones.</span><span class="sxs-lookup"><span data-stu-id="abe28-348">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


### <a name="project"></a><span data-ttu-id="abe28-349">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-349">Project</span></span>

- <span data-ttu-id="abe28-350">Se ha corregido un problema por el que, si el formato de fecha es W4/4, el selector de fecha puede mostrar un día y un año incorrectos.</span><span class="sxs-lookup"><span data-stu-id="abe28-350">Fixed an issue where if the date format is W4/4, the date picker may show the wrong day and year.</span></span>


### <a name="visio"></a><span data-ttu-id="abe28-351">Visio</span><span class="sxs-lookup"><span data-stu-id="abe28-351">Visio</span></span>

- <span data-ttu-id="abe28-352">Se ha corregido un problema que provocaba que Visio dejara de funcionar durante el cierre.</span><span class="sxs-lookup"><span data-stu-id="abe28-352">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="abe28-353">Se ha corregido la característica "Buscar forma" para que se muestren todos los resultados</span><span class="sxs-lookup"><span data-stu-id="abe28-353">Fixed "Search Shape" feature to display all the results</span></span>



### <a name="word"></a><span data-ttu-id="abe28-354">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-354">Word</span></span>

- <span data-ttu-id="abe28-p120">Con este error, Office no estaba respetando las directivas específicas (se mostraba un grupo de plantillas en la página principal cuando debían haber estado deshabilitadas). Con esta corrección, se respetan las directivas.</span><span class="sxs-lookup"><span data-stu-id="abe28-p120">In this bug, specific policies weren't being honored by Office (a group of templates were being shown on the Home Page when they should have been disabled). With this fix, the policies are being honored.</span></span>


- <span data-ttu-id="abe28-357">Al crear con coautoría un documento, el borrador activo no se borrará cuando se realicen cambios en el orden de los comentarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-357">When coauthoring a document, active draft is not cleared when comment order changes.</span></span>


- <span data-ttu-id="abe28-358">Se ha corregido un error en Comentarios modernos en el que los signos de puntuación y los números se mostraban en el lado incorrecto en algunos idiomas internacionales.</span><span class="sxs-lookup"><span data-stu-id="abe28-358">Fixed bug in Modern Commenting where punctuation and numbers would show up on the wrong side for some international languages.</span></span>


- <span data-ttu-id="abe28-359">Se ha corregido un problema por el que la combinación de "B" y ")" se convertía automáticamente en el emoji con gafas de sol, y ahora permanecerá como los caracteres individuales</span><span class="sxs-lookup"><span data-stu-id="abe28-359">Fixed an issue where the combination of 'B' and ')' would automatically turn into the sunglass wearing emoji and now remain as the individual characters</span></span>


- <span data-ttu-id="abe28-360">Texto actualizado en la llamada de autoguardado para los archivos guardados localmente.</span><span class="sxs-lookup"><span data-stu-id="abe28-360">Updates text on autosave callout for files saved locally.</span></span>


- <span data-ttu-id="abe28-361">Hemos corregido un problema con los comentarios durante la coautoría.</span><span class="sxs-lookup"><span data-stu-id="abe28-361">We fixed an issue with comments during coauthoring.</span></span>


- <span data-ttu-id="abe28-362">Hemos corregido un problema relacionado con el icono de comentario.</span><span class="sxs-lookup"><span data-stu-id="abe28-362">We fixed an issue relating to comment icon.</span></span>


- <span data-ttu-id="abe28-363">Se ha corregido un problema que hacía que los estilos copiados y pegados pudieran no ser iguales en el texto pegado.</span><span class="sxs-lookup"><span data-stu-id="abe28-363">We fixed an issue which copy and paste styles may not be same in pasted text.</span></span>


- <span data-ttu-id="abe28-364">Optimiza las condiciones para ofrecer previsiones de texto.</span><span class="sxs-lookup"><span data-stu-id="abe28-364">Optimizes conditions for text predictions to be offered.</span></span>


- <span data-ttu-id="abe28-365">Hemos corregido un problema relacionado con los hipervínculos.</span><span class="sxs-lookup"><span data-stu-id="abe28-365">We fixed an issue relating to hyperlink.</span></span>


- <span data-ttu-id="abe28-366">Algunos textos seleccionados no eran visibles al usar el tema modo oscuro en el modo Lectura.</span><span class="sxs-lookup"><span data-stu-id="abe28-366">Some select text not visible when using darkmode theme in reading mode.</span></span>


- <span data-ttu-id="abe28-367">Hemos corregido un problema con el Autoguardado.</span><span class="sxs-lookup"><span data-stu-id="abe28-367">We fixed an issue in auto save.</span></span>


- <span data-ttu-id="abe28-368">Hemos corregido Application.OnTime donde puede que no se desencadene correctamente.</span><span class="sxs-lookup"><span data-stu-id="abe28-368">We made a fix in Application.OnTime where it might not trigger correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="abe28-369">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-369">Office Suite</span></span>

- <span data-ttu-id="abe28-370">Se ha corregido un problema de rendimiento relacionado con la iteración de texto.</span><span class="sxs-lookup"><span data-stu-id="abe28-370">Fixed a performance issue related to iteration of text.</span></span>


- <span data-ttu-id="abe28-371">Soluciona un problema con el soporte técnico de GDI+ LineJoinMiterClipped en Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-371">Fixes an issue with support of GDI+ LineJoinMiterClipped in Office.</span></span>


- <span data-ttu-id="abe28-372">Esta versión mejora el control del contenido confidencial de línea cuando la palabra clave está en la primera línea de un documento.</span><span class="sxs-lookup"><span data-stu-id="abe28-372">This release improves handling of line-spanning sensitive content when the keyword is on the first line of a document.</span></span>



[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2103-april-13"></a><span data-ttu-id="abe28-374">Versión 2103: 13 de abril</span><span class="sxs-lookup"><span data-stu-id="abe28-374">Version 2103: April 13</span></span>
<span data-ttu-id="abe28-375">*Versión 2103 (Compilación 13901.20400)*</span><span class="sxs-lookup"><span data-stu-id="abe28-375">*Version 2103 (Build 13901.20400)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="abe28-376">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-376">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="abe28-377">Teams</span><span class="sxs-lookup"><span data-stu-id="abe28-377">Teams</span></span>

- <span data-ttu-id="abe28-378">**Vista dinámica** Vista dinámica optimiza automáticamente el contenido compartido y los participantes de vídeo en las reuniones de Teams.</span><span class="sxs-lookup"><span data-stu-id="abe28-378">**Dynamic view** Dynamic view automatically optimizes shared content and video participants in Teams meetings.</span></span> <span data-ttu-id="abe28-379">Los nuevos controles le permiten personalizar la vista para adaptarla a sus preferencias y necesidades, como la capacidad de mostrar el contenido compartido y participantes específicos en paralelo.</span><span class="sxs-lookup"><span data-stu-id="abe28-379">New controls let you personalize the view to suit your preferences and needs, such as the ability to show shared content and specific participants side-by-side.</span></span>

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO FINAL)

## <a name="version-2103-april-10"></a><span data-ttu-id="abe28-381">Versión 2103: 10 de abril</span><span class="sxs-lookup"><span data-stu-id="abe28-381">Version 2103: April 10</span></span>
<span data-ttu-id="abe28-382">*Versión 2103 (Compilación 13901.20400)*</span><span class="sxs-lookup"><span data-stu-id="abe28-382">*Version 2103 (Build 13901.20400)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-384">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-384">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-385">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-385">Excel</span></span>

- <span data-ttu-id="abe28-386">Se ha corregido un posible problema de contención de recursos en palabras mientras se dibujaba una imagen.</span><span class="sxs-lookup"><span data-stu-id="abe28-386">Fixed a potential resource contention issue in word when drawing an image.</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-387">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-387">Outlook</span></span>

- <span data-ttu-id="abe28-388">Hemos corregido un problema que causaba que los usuarios vieran por error un mensaje de "Esto puede tardar un poco" mientras añadían algún elemento a un calendario.</span><span class="sxs-lookup"><span data-stu-id="abe28-388">We fixed an issue that cause users to erroneously see a "This may take a while" message when adding a calendar.</span></span>

- <span data-ttu-id="abe28-389">Hemos solucionado un problema que hacía que los delegados aparecieran como organizadores de reuniones creadas en calendarios recién añadidos.</span><span class="sxs-lookup"><span data-stu-id="abe28-389">We fixed an issue that caused delegates to appear as the organizer of meetings created on newly added calendars.</span></span>  <span data-ttu-id="abe28-390">Las reuniones en este estado no aparecían en el calendario del principal.</span><span class="sxs-lookup"><span data-stu-id="abe28-390">Meetings in this state did not appear on the principal's calendar.</span></span>

- <span data-ttu-id="abe28-391">Se ha corregido un posible problema de contención de recursos en palabras mientras se dibujaba una imagen.</span><span class="sxs-lookup"><span data-stu-id="abe28-391">Fixed a potential resource contention issue in word when drawing an image.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="abe28-392">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-392">Powerpoint</span></span>

- <span data-ttu-id="abe28-393">Se ha corregido un posible problema de contención de recursos en palabras mientras se dibujaba una imagen.</span><span class="sxs-lookup"><span data-stu-id="abe28-393">Fixed a potential resource contention issue in word when drawing an image.</span></span>

### <a name="word"></a><span data-ttu-id="abe28-394">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-394">Word</span></span>

- <span data-ttu-id="abe28-395">Se ha corregido un posible problema de contención de recursos en palabras mientras se dibujaba una imagen.</span><span class="sxs-lookup"><span data-stu-id="abe28-395">Fixed a potential resource contention issue in word when drawing an image.</span></span>

- <span data-ttu-id="abe28-396">Se ha corregido un problema no dinámico en la vista previa de impresión.</span><span class="sxs-lookup"><span data-stu-id="abe28-396">Fixed a non-responsive issue while in Print preview.</span></span>

- <span data-ttu-id="abe28-397">Texto actualizado en la llamada de autoguardado para los archivos guardados localmente.</span><span class="sxs-lookup"><span data-stu-id="abe28-397">Updates text on autosave callout for files saved locally.</span></span>

### <a name="office-suite"></a><span data-ttu-id="abe28-398">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-398">Office Suite</span></span>

- <span data-ttu-id="abe28-399">Se ha corregido el problema del cambio de nombre cuando se abría un archivo SyncBacked fuera de línea y se le cambiaba el nombre en la aplicación antes de guardarlo.</span><span class="sxs-lookup"><span data-stu-id="abe28-399">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>



[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2103-april-02"></a><span data-ttu-id="abe28-401">Versión 2103: 02 de abril</span><span class="sxs-lookup"><span data-stu-id="abe28-401">Version 2103: April 02</span></span>
<span data-ttu-id="abe28-402">*Versión 2103 (Compilación 13901.20336)*</span><span class="sxs-lookup"><span data-stu-id="abe28-402">*Version 2103 (Build 13901.20336)*</span></span>
* <span data-ttu-id="abe28-403">Varias correcciones de errores y de rendimiento.</span><span class="sxs-lookup"><span data-stu-id="abe28-403">Various bugs and performance fixes.</span></span>

## <a name="version-2103-april-1"></a><span data-ttu-id="abe28-404">Versión 2103: 1° de abril</span><span class="sxs-lookup"><span data-stu-id="abe28-404">Version 2103: April 1</span></span>
<span data-ttu-id="abe28-405">*Versión 2103 (Compilación 13901.20148)*</span><span class="sxs-lookup"><span data-stu-id="abe28-405">*Version 2103 (Build 13901.20148)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="abe28-406">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-406">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="abe28-407">Teams</span><span class="sxs-lookup"><span data-stu-id="abe28-407">Teams</span></span>

- <span data-ttu-id="abe28-408">**Formato de fecha y hora** Con esta actualización, los formatos de fecha y hora en Teams coincidirán con la configuración regional de los sistemas operativos Windows y Mac.</span><span class="sxs-lookup"><span data-stu-id="abe28-408">**Date/Time format** With this update, the date/time formats in Teams will match the Mac and Windows operating system regional settings.</span></span> <span data-ttu-id="abe28-409">Anteriormente, Teams solo mostraba la fecha y hora en el formato correspondiente al idioma de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="abe28-409">Previously, Teams would only show date/time in the format corresponding to the application's language.</span></span> <span data-ttu-id="abe28-410">Es importante tener en cuenta que solo el calendario gregoriano es compatible, independientemente de la configuración de calendario del sistema operativo.</span><span class="sxs-lookup"><span data-stu-id="abe28-410">It's important to note that only the Gregorian calendar is supported regardless of the operating system's calendar setting.</span></span> 

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

## <a name="version-2103-march-30"></a><span data-ttu-id="abe28-412">Versión 2103: 30 de marzo</span><span class="sxs-lookup"><span data-stu-id="abe28-412">Version 2103: March 30</span></span>
<span data-ttu-id="abe28-413">*Versión 2103 (compilación 13901.20312)*</span><span class="sxs-lookup"><span data-stu-id="abe28-413">*Version 2103 (Build 13901.20312)*</span></span>
* <span data-ttu-id="abe28-414">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="abe28-414">Various bugs and performance fixes.</span></span>

## <a name="version-2103-march-28"></a><span data-ttu-id="abe28-415">Versión 2103: 28 de marzo</span><span class="sxs-lookup"><span data-stu-id="abe28-415">Version 2103: March 28</span></span>
<span data-ttu-id="abe28-416">*Versión 2103 (Compilación 13901.20306)*</span><span class="sxs-lookup"><span data-stu-id="abe28-416">*Version 2103 (Build 13901.20306)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-418">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-418">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-419">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-419">Outlook</span></span>

- <span data-ttu-id="abe28-420">Hemos corregido un problema que causaba que algunos usuarios experimentasen un cierre inesperado de Outlook al sincronizar los cambios en la jerarquía de carpetas.</span><span class="sxs-lookup"><span data-stu-id="abe28-420">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


- <span data-ttu-id="abe28-421">Se ha corregido un problema que causaba que algunos usuarios viesen sus lugares de cambio de calendario principal y secundario en el panel de navegación.</span><span class="sxs-lookup"><span data-stu-id="abe28-421">We fixed an issue that caused some users to see their primary and secondary calendar switching places in the Navigation Pane.</span></span>



[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2103-march-22"></a><span data-ttu-id="abe28-423">Versión 2103: 22 de marzo</span><span class="sxs-lookup"><span data-stu-id="abe28-423">Version 2103: March 22</span></span>
<span data-ttu-id="abe28-424">*Versión 2103 (Compilación 13901.20230)*</span><span class="sxs-lookup"><span data-stu-id="abe28-424">*Version 2103 (Build 13901.20230)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-426">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-426">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-427">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-427">Outlook</span></span>

- <span data-ttu-id="abe28-428">Hemos corregido un problema que provocaba que los usuarios vieran más firmas de las esperadas.</span><span class="sxs-lookup"><span data-stu-id="abe28-428">We fixed an issue that caused users to see more signatures than expected.</span></span>



[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2103-march-15"></a><span data-ttu-id="abe28-430">Versión 2103: 15 de marzo</span><span class="sxs-lookup"><span data-stu-id="abe28-430">Version 2103: March 15</span></span>
<span data-ttu-id="abe28-431">*Versión 2103 (compilación 13901.20170)*</span><span class="sxs-lookup"><span data-stu-id="abe28-431">*Version 2103 (Build 13901.20170)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-433">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-433">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="abe28-434">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-434">Project</span></span>

- <span data-ttu-id="abe28-435">Se ha corregido un problema que provocaba que Visio dejara de funcionar durante el cierre.</span><span class="sxs-lookup"><span data-stu-id="abe28-435">Fixed an issue where Visio could stop working during close.</span></span>


### <a name="visio"></a><span data-ttu-id="abe28-436">Visio</span><span class="sxs-lookup"><span data-stu-id="abe28-436">Visio</span></span>

- <span data-ttu-id="abe28-437">Se ha corregido un problema que provocaba que Visio dejara de funcionar durante el cierre.</span><span class="sxs-lookup"><span data-stu-id="abe28-437">Fixed an issue where Visio could stop working during close.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

[//]: # (NO QUITAR DETALLES DE CARACTERÍSTICAS CONTENIDO INICIO)
## <a name="version-2103-march-11"></a><span data-ttu-id="abe28-440">Versión 2103: 11 de marzo</span><span class="sxs-lookup"><span data-stu-id="abe28-440">Version 2103: March 11</span></span>
<span data-ttu-id="abe28-441">*Versión 2103 (compilación 13901.20148)*</span><span class="sxs-lookup"><span data-stu-id="abe28-441">*Version 2103 (Build 13901.20148)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="abe28-442">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-442">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-443">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-443">Excel</span></span>

- <span data-ttu-id="abe28-444">**Autoguardado y coautoría en documentos cifrados confidenciales:** no elija entre productividad y seguridad.</span><span class="sxs-lookup"><span data-stu-id="abe28-444">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="abe28-445">Con Microsoft Information Protection, los documentos que se cifran con etiquetas de confidencialidad ahora permiten el autoguardado y la coautoría con otras personas en tiempo real, igual que los documentos sin cifrar.</span><span class="sxs-lookup"><span data-stu-id="abe28-445">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="abe28-446">Requiere que el espacio empresarial opte por participar (más información: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="abe28-446">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-447">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-447">Outlook</span></span>

- <span data-ttu-id="abe28-448">**Nueva experiencia de reserva de sala de conferencias y área de trabajo:** se ha actualizado la experiencia de reserva de la sala de conferencias y, con ella, hemos agregado funcionalidades para permitirle programar áreas de trabajo individuales.</span><span class="sxs-lookup"><span data-stu-id="abe28-448">**New conference room and workspace booking experience:** The conference room booking experience has been refreshed, and with it we've added capabilities to allow you to schedule individual workspaces as well</span></span>

### <a name="powerpoint"></a><span data-ttu-id="abe28-449">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-449">PowerPoint</span></span>

- <span data-ttu-id="abe28-450">**Autoguardado y coautoría en documentos cifrados confidenciales:** no elija entre productividad y seguridad.</span><span class="sxs-lookup"><span data-stu-id="abe28-450">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="abe28-451">Con Microsoft Information Protection, los documentos que se cifran con etiquetas de confidencialidad ahora permiten el autoguardado y la coautoría con otras personas en tiempo real, igual que los documentos sin cifrar.</span><span class="sxs-lookup"><span data-stu-id="abe28-451">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="abe28-452">Requiere que el espacio empresarial opte por participar (más información: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="abe28-452">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="teams"></a><span data-ttu-id="abe28-453">Teams</span><span class="sxs-lookup"><span data-stu-id="abe28-453">Teams</span></span>

- <span data-ttu-id="abe28-454">**Estado fuera de la oficina** Configure un mensaje para avisar a otras personas de que no estás trabajando o de que estás de vacaciones, y que por lo tanto no estás disponible para responder si le envían un mensaje de chat.</span><span class="sxs-lookup"><span data-stu-id="abe28-454">**Out of Office status** Set up a message to let others know you're not working or on vacation so you're not available to reply when they send a chat message to you.</span></span> <span data-ttu-id="abe28-455">Su estado fuera de la oficina también se sincronizará con las Respuestas automáticas de su calendario de Outlook.</span><span class="sxs-lookup"><span data-stu-id="abe28-455">Your Out of Office status will also sync with Automatic Replies in your Outlook calendar.</span></span>

### <a name="visio"></a><span data-ttu-id="abe28-456">Visio</span><span class="sxs-lookup"><span data-stu-id="abe28-456">Visio</span></span>

- <span data-ttu-id="abe28-457">**Los iconos de Office tienen un nuevo aspecto:** los iconos de producto se han rediseñado para reflejar las sencillas, inteligentes y eficaces experiencias de Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-457">**Office icons have a new look:** The product icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span> [<span data-ttu-id="abe28-458">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-458">Learn more</span></span>](https://support.office.com/article/a6cdf19a-b2bd-4be1-9515-d74a37aa59bf)

### <a name="word"></a><span data-ttu-id="abe28-459">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-459">Word</span></span>

- <span data-ttu-id="abe28-460">**Modo oscuro para documentos de Word:** el modo oscuro puede ayudar a reducir la carga visual y adaptar la sensibilidad a la luz mientras trabaja en sus documentos.</span><span class="sxs-lookup"><span data-stu-id="abe28-460">**Dark Mode for Word documents:** Dark Mode may help reduce eye strain and accommodate light sensitivity while working on your documents.</span></span>

- <span data-ttu-id="abe28-461">**Autoguardado y coautoría en documentos cifrados confidenciales:** no elija entre productividad y seguridad.</span><span class="sxs-lookup"><span data-stu-id="abe28-461">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="abe28-462">Con Microsoft Information Protection, los documentos que se cifran con etiquetas de confidencialidad ahora permiten el autoguardado y la coautoría con otras personas en tiempo real, igual que los documentos sin cifrar.</span><span class="sxs-lookup"><span data-stu-id="abe28-462">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="abe28-463">Requiere que el espacio empresarial opte por participar (más información: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="abe28-463">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-466">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-466">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="abe28-467">Access</span><span class="sxs-lookup"><span data-stu-id="abe28-467">Access</span></span>

- <span data-ttu-id="abe28-468">Hemos corregido un problema que podría provocar que la aplicación se cerrara de forma inesperada al quitar una unidad externa.</span><span class="sxs-lookup"><span data-stu-id="abe28-468">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="abe28-469">Hemos corregido un problema por el que, cuando una aplicación externa solicitaba una interfaz de accesibilidad, nos impedía cerrar hasta que se liberaba su referencia.</span><span class="sxs-lookup"><span data-stu-id="abe28-469">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


### <a name="excel"></a><span data-ttu-id="abe28-470">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-470">Excel</span></span>

- <span data-ttu-id="abe28-471">Hemos corregido un problema que podría provocar que la aplicación se cerrara de forma inesperada al quitar una unidad externa.</span><span class="sxs-lookup"><span data-stu-id="abe28-471">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="abe28-472">Se ha corregido un problema que causaba que Excel se cerrara de forma inesperada al intentar mostrar la tarjeta tipos de datos porque una imagen no se podía recuperar.</span><span class="sxs-lookup"><span data-stu-id="abe28-472">Fixed an issue where Excel would sometimes close unexpectedly when trying to show the Data Types card due to a not being able to retrieve an image.</span></span>


- <span data-ttu-id="abe28-473">Hemos corregido un problema por el que la fuente cambiaría de forma inesperada al usar un signo de multiplicación o división con una fuente japonesa.</span><span class="sxs-lookup"><span data-stu-id="abe28-473">Corrected an issue where the font would change unexpectedly when using a multiplication or divide sign with a Japanese font.</span></span> <span data-ttu-id="abe28-474">Ahora continuamos usando la misma fuente si admite el carácter.</span><span class="sxs-lookup"><span data-stu-id="abe28-474">We now continue to use the same font if it supports the character.</span></span>


- <span data-ttu-id="abe28-475">Hemos corregido un problema que impedía a los usuarios exportar un libro de Excel a PDF.</span><span class="sxs-lookup"><span data-stu-id="abe28-475">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="abe28-476">Hemos corregido un problema que hace que las imágenes fueran más pequeñas de lo esperado al usar la opción Pegar imagen vinculada.</span><span class="sxs-lookup"><span data-stu-id="abe28-476">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="abe28-477">Hemos corregido un problema por el que se podía perder parte del formato al copiar una hoja mientras se trabajaba en autoría.</span><span class="sxs-lookup"><span data-stu-id="abe28-477">We fixed an issue where some formatting could be lost when copying a sheet while coauthoring.</span></span>


- <span data-ttu-id="abe28-478">Hemos corregido un problema por el que algunas notas se mostraban de forma inesperada al abrir un libro.</span><span class="sxs-lookup"><span data-stu-id="abe28-478">We fixed an issue where some notes were unexpectedly shown when opening a workbook.</span></span>


- <span data-ttu-id="abe28-479">Hemos corregido un problema que causaba que algunos formatos de tabla dinámica dañaran el libro al guardar en formato .xls o .xlt.</span><span class="sxs-lookup"><span data-stu-id="abe28-479">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


### <a name="outlook"></a><span data-ttu-id="abe28-480">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-480">Outlook</span></span>

- <span data-ttu-id="abe28-481">Hemos corregido un problema que podría provocar que la aplicación se cerrara de forma inesperada al quitar una unidad externa.</span><span class="sxs-lookup"><span data-stu-id="abe28-481">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="abe28-482">Hemos corregido el problema que causaba que los usuarios viesen grupos de calendario duplicados después de crear un grupo.</span><span class="sxs-lookup"><span data-stu-id="abe28-482">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="abe28-483">Hemos corregido un problema que causaba que los usuarios de las mejoras del calendario compartido no pudieran establecer el color de un calendario en amarillo o marrón.</span><span class="sxs-lookup"><span data-stu-id="abe28-483">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="abe28-484">Hemos corregido un problema por el que los usuarios no veían los calendarios agregados recientemente en el panel de navegación si no reiniciaban Outlook.</span><span class="sxs-lookup"><span data-stu-id="abe28-484">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="abe28-485">Hemos corregido un problema que causaba que los caracteres que no eran ASCII se exportaran de forma incorrecta al exportar a un archivo CSV.</span><span class="sxs-lookup"><span data-stu-id="abe28-485">We fixed an issue that caused non-ASCII characters to export incorrectly when exporting to CSV.</span></span>


- <span data-ttu-id="abe28-486">Hemos corregido un problema que causaba que algunos usuarios no pudieran tener acceso a las firmas asociadas con cuentas de correo secundarias.</span><span class="sxs-lookup"><span data-stu-id="abe28-486">We fixed an issue that caused some people to be unable to access signatures associated with secondary mail accounts.</span></span>


- <span data-ttu-id="abe28-487">Hemos corregido un problema que causaba que los usuarios de la característica Configuración de la nube vieran que se reemplazaba la configuración personalizada por la configuración predeterminada después de configurar Outlook en un nuevo dispositivo.</span><span class="sxs-lookup"><span data-stu-id="abe28-487">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="abe28-488">Hemos corregido un problema que provocaba que las firmas con contenido Unicode se dañasen.</span><span class="sxs-lookup"><span data-stu-id="abe28-488">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="abe28-489">Hemos corregido un problema que causaba que los usuarios de traducción directa no pudieran enviar comentarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-489">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="abe28-490">Hemos corregido un problema que provocaba que los usuarios vieran archivos adjuntos duplicados al quitar la protección de DRM.</span><span class="sxs-lookup"><span data-stu-id="abe28-490">We fixed an issue that caused users to see attachments getting duplicated when removing DRM protection.</span></span>


- <span data-ttu-id="abe28-491">Hemos corregido un problema que causaba que los usuarios no pudieran buscar un grupo de contactos con Comprobar nombres al redactar un correo.</span><span class="sxs-lookup"><span data-stu-id="abe28-491">We fixed an issue that caused users to be unable to look up a contact group with Check Names  when composing mail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="abe28-492">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-492">PowerPoint</span></span>

- <span data-ttu-id="abe28-493">Hemos corregido un problema que podría provocar que la aplicación se cerrara de forma inesperada al quitar una unidad externa.</span><span class="sxs-lookup"><span data-stu-id="abe28-493">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="abe28-494">Hemos corregido un problema que hacía que las flechas de los gráficos de líneas no aparecieran tal como se esperaba en el modo de presentación de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="abe28-494">We fixed an issue where arrows in line charts were not appearing as expected in PowerPoint slideshow mode.</span></span>


- <span data-ttu-id="abe28-495">Corregido un problema con la reproducción de animaciones y marcadores de audio.</span><span class="sxs-lookup"><span data-stu-id="abe28-495">Fixes an issue with looping animations and audio bookmarks.</span></span>


### <a name="project"></a><span data-ttu-id="abe28-496">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-496">Project</span></span>

- <span data-ttu-id="abe28-497">Se ha corregido un problema que provocaba que Visio dejara de funcionar durante el cierre.</span><span class="sxs-lookup"><span data-stu-id="abe28-497">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="abe28-498">Hemos corregido un problema que podría provocar que la aplicación se cerrara de forma inesperada al quitar una unidad externa.</span><span class="sxs-lookup"><span data-stu-id="abe28-498">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="abe28-499">Se ha corregido un problema por el que una tarea completada al 100 % podía aparecer como completada al 99 %.</span><span class="sxs-lookup"><span data-stu-id="abe28-499">Fixed an issue where a task that are 100% complete may revert back to 99% complete.</span></span>


- <span data-ttu-id="abe28-500">Se ha corregido un problema por el que Project se cerraba inesperadamente si ejecutaba JAWS e iba al diálogo de información de la tarea.</span><span class="sxs-lookup"><span data-stu-id="abe28-500">Fixed an issue where Project may close unexpectedly if you are running JAWS and go to the task information dialog.</span></span>


- <span data-ttu-id="abe28-501">Se ha corregido un problema por el que, si la columna de indicador no está en el primer lugar de la columna, al cortar una tarea de resumen, no se advierte de que también se quitarán las subtareas.</span><span class="sxs-lookup"><span data-stu-id="abe28-501">Fixed an issue where if the indicator column is not in the first column spot, when you cut a summary task you aren't warned that the subtasks will also be removed.</span></span>


- <span data-ttu-id="abe28-502">Se ha corregido un problema por el que, si un usuario seleccionaba la opción Agregar su usuario a una función de tarea en su Timesheet, no se podrían usar correctamente las unidades de disponibilidad de recursos en la tarea creada.</span><span class="sxs-lookup"><span data-stu-id="abe28-502">Fixed an issue where if a user selected the Add Yourself to a Task function on their Timesheet, the correctly resource availability units may not be used on the created assignment.</span></span>


- <span data-ttu-id="abe28-503">Se ha corregido un problema por el que es posible que las divisiones de tareas se creen de forma incorrecta al guardar un proyecto desde Project Web App en un archivo local.</span><span class="sxs-lookup"><span data-stu-id="abe28-503">Fixed an issue where task splits may be wrongly created when saving a project from Project web app to a local file.</span></span> <span data-ttu-id="abe28-504">Esto sucedía al usar un calendario de tareas con horas de trabajo no estándar.</span><span class="sxs-lookup"><span data-stu-id="abe28-504">This would happen if a task calendar with non-standard working times was being used.</span></span>


### <a name="publisher"></a><span data-ttu-id="abe28-505">Publisher</span><span class="sxs-lookup"><span data-stu-id="abe28-505">Publisher</span></span>

- <span data-ttu-id="abe28-506">Hemos corregido un problema que podría provocar que la aplicación se cerrara de forma inesperada al quitar una unidad externa.</span><span class="sxs-lookup"><span data-stu-id="abe28-506">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


### <a name="visio"></a><span data-ttu-id="abe28-507">Visio</span><span class="sxs-lookup"><span data-stu-id="abe28-507">Visio</span></span>

- <span data-ttu-id="abe28-508">Se ha corregido un problema que provocaba que Visio dejara de funcionar durante el cierre.</span><span class="sxs-lookup"><span data-stu-id="abe28-508">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="abe28-509">Hemos corregido un problema que podría provocar que la aplicación se cerrara de forma inesperada al quitar una unidad externa.</span><span class="sxs-lookup"><span data-stu-id="abe28-509">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


### <a name="word"></a><span data-ttu-id="abe28-510">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-510">Word</span></span>

- <span data-ttu-id="abe28-511">Hemos corregido un problema por el que, al abrir un archivo protegido con una etiqueta de Microsoft Information Protection (MIP), se puede colgar de forma indefinida si el usuario no ha iniciado sesión en una identidad que tiene acceso a la etiqueta protegida de MIP.</span><span class="sxs-lookup"><span data-stu-id="abe28-511">We fixed an issue where opening a file protected with a Microsoft Information Protection (MIP) label can hang indefinitely if the user is not signed in to an identity that has access to the MIP protected label.</span></span> <span data-ttu-id="abe28-512">El usuario no puede cancelar la apertura para mostrar la solicitud de inicio de sesión yno se puede completar correctamente gasta entonces.</span><span class="sxs-lookup"><span data-stu-id="abe28-512">The user is forced to cancel the open to show the sign-in prompt, and the open only succeeds after that point.</span></span> <span data-ttu-id="abe28-513">Para solucionar este problema, permita que se muestre la solicitud de inicio de sesión durante la apertura o descarga.</span><span class="sxs-lookup"><span data-stu-id="abe28-513">Fixing this issue by allowing the sign-in prompt to be shown during open/download.</span></span>


- <span data-ttu-id="abe28-514">Hemos corregido un problema que podría provocar que la aplicación se cerrara de forma inesperada al quitar una unidad externa.</span><span class="sxs-lookup"><span data-stu-id="abe28-514">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="abe28-515">Hemos corregido un problema al usar Dictado en el nuevo Comentarios de Word. Ahora, el botón de dictado de la tarjeta Comentarios se activa y desactivada correctamente.</span><span class="sxs-lookup"><span data-stu-id="abe28-515">We fixed an issue when using Dictation in the new Word Commenting, the Dictation button in the Comment card now correctly toggles on and off.</span></span>


- <span data-ttu-id="abe28-516">Al crear un documento en coautoría, el borrador activo no se borraba cuando cambiaba el orden de los comentarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-516">When coauthoring a document, active draft is not cleared when comment order changes.</span></span>


- <span data-ttu-id="abe28-517">Se ha corregido un problema por el que no se insertaba ningún espacio entre palabras cuando los usuarios dictaban en su documento.</span><span class="sxs-lookup"><span data-stu-id="abe28-517">Fixed an issue where there was no space being inserted between words when users dictated into their document.</span></span>


- <span data-ttu-id="abe28-518">Se ha corregido un problema en la canalización de representación relacionado con las capas de desplazamiento que contienen animaciones de desplazamiento o zoom.</span><span class="sxs-lookup"><span data-stu-id="abe28-518">Fixes an issue in the rendering pipeline related to scrolling layers that contain scroll or zoom animations.</span></span>


- <span data-ttu-id="abe28-519">Se ha corregido un problema con los colores aplicados a los iconos y a los gráficos SVG con efectos 3D.</span><span class="sxs-lookup"><span data-stu-id="abe28-519">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="abe28-520">Hemos corregido un problema con el Autoguardado.</span><span class="sxs-lookup"><span data-stu-id="abe28-520">We fixed an issue in AutoSave.</span></span>


- <span data-ttu-id="abe28-521">Hemos corregido un problema con la nota al pie.</span><span class="sxs-lookup"><span data-stu-id="abe28-521">We fixed an issue in footnote.</span></span>


- <span data-ttu-id="abe28-522">Hemos corregido un problema al publicar comentarios de varias líneas escritos en RTL que causaba que las líneas 2 en adelante se alineasen a la izquierda en lugar de a la derecha.</span><span class="sxs-lookup"><span data-stu-id="abe28-522">We fixed an issue when posting multi-line comments typed in RTL caused the 2nd and onward lines to be aligned to the left instead of the right.</span></span>


- <span data-ttu-id="abe28-523">Hemos corregido un problema con la alineación de varios comentarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-523">We fixed an issue with alignment of multiple comments.</span></span>


- <span data-ttu-id="abe28-524">Hemos corregido un problema en los métodos abreviados de teclado del panel de tareas Leer en voz alta.</span><span class="sxs-lookup"><span data-stu-id="abe28-524">We fixed an issue in Read Aloud task pane keyboard shortcuts.</span></span>


- <span data-ttu-id="abe28-525">Hemos corregido un problema por el que el Narrador podía omitir un párrafo.</span><span class="sxs-lookup"><span data-stu-id="abe28-525">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="abe28-526">Hemos corregido un problema que hacía que la revisión ortográfica cambiara entre dos menús contextuales de corrección ortográfica diferentes.</span><span class="sxs-lookup"><span data-stu-id="abe28-526">We fixed an issue where spell check switched between two different spelling correction context menus.</span></span>


- <span data-ttu-id="abe28-527">Hemos corregido un problema con los controles de contenido de texto enriquecido.</span><span class="sxs-lookup"><span data-stu-id="abe28-527">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="abe28-528">Hemos corregido un problema con la escritura al final de un párrafo oculto que podía provocar que la aplicación dejara de funcionar.</span><span class="sxs-lookup"><span data-stu-id="abe28-528">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


- <span data-ttu-id="abe28-529">Hemos corregido un problema en el que las columnas podían tener texto superpuesto.</span><span class="sxs-lookup"><span data-stu-id="abe28-529">We fixed an issue where columns might have overlapping text.</span></span>


- <span data-ttu-id="abe28-530">Hemos corregido un problema relacionado con el marcador.</span><span class="sxs-lookup"><span data-stu-id="abe28-530">We fixed an issue relating to bookmark.</span></span>


- <span data-ttu-id="abe28-531">Hemos corregido un problema relacionado con la resolución de conflictos durante la coautoría.</span><span class="sxs-lookup"><span data-stu-id="abe28-531">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


### <a name="office-suite"></a><span data-ttu-id="abe28-532">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-532">Office Suite</span></span>

- <span data-ttu-id="abe28-533">Las ubicaciones de OneDrive ahora se filtran según corresponda en la configuración de directiva de grupo.</span><span class="sxs-lookup"><span data-stu-id="abe28-533">OneDrive places are now filtered out as appropriate per the group policy setting.</span></span>


- <span data-ttu-id="abe28-534">Se ha corregido un problema al usar Narrador en un texto que contiene ecuaciones matemáticas.</span><span class="sxs-lookup"><span data-stu-id="abe28-534">Fixed an issue that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="abe28-535">Se ha corregido un problema de confiabilidad relacionado con la compatibilidad de las aplicaciones de Office que se ejecutan en la sesión 0.</span><span class="sxs-lookup"><span data-stu-id="abe28-535">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="abe28-536">Se ha corregido un problema de confiabilidad relacionado con la compatibilidad de las aplicaciones de Office que se ejecutan en la sesión 0.</span><span class="sxs-lookup"><span data-stu-id="abe28-536">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="abe28-537">Soluciona un problema relacionado con la falta de respuesta que puede producirse al cargar imágenes EMF.</span><span class="sxs-lookup"><span data-stu-id="abe28-537">Fixes an issue related to unresponsiveness that may occur when loading EMF images.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2102-march-03"></a><span data-ttu-id="abe28-539">Versión 2102: 03 de marzo</span><span class="sxs-lookup"><span data-stu-id="abe28-539">Version 2102: March 03</span></span>
<span data-ttu-id="abe28-540">*Versión 2102 (compilación 13801.20274)*</span><span class="sxs-lookup"><span data-stu-id="abe28-540">*Version 2102 (Build 13801.20274)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-542">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-542">Resolved issues</span></span>
### <a name="word"></a><span data-ttu-id="abe28-543">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-543">Word</span></span>

- <span data-ttu-id="abe28-544">Soluciona un problema con la información del tema que se aplica a los iconos y a los gráficos SVG.</span><span class="sxs-lookup"><span data-stu-id="abe28-544">Fixes an issue with theme information applied to icons and SVG graphics.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2102-march-01"></a><span data-ttu-id="abe28-546">Versión 2102: 01 de marzo</span><span class="sxs-lookup"><span data-stu-id="abe28-546">Version 2102: March 01</span></span>
<span data-ttu-id="abe28-547">*Versión 2102 (compilación 13801.20266)*</span><span class="sxs-lookup"><span data-stu-id="abe28-547">*Version 2102 (Build 13801.20266)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-549">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-549">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-550">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-550">Outlook</span></span>

- <span data-ttu-id="abe28-551">**Compartir con Teams:** comparta mensajes de Outlook con una persona o canal en Teams.</span><span class="sxs-lookup"><span data-stu-id="abe28-551">**Share to Teams:** Share messages from Outlook with a person or channel in Teams.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-554">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-554">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-555">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-555">Outlook</span></span>

- <span data-ttu-id="abe28-556">Hemos corregido el problema que causaba que los usuarios viesen grupos de calendario duplicados después de crear un grupo.</span><span class="sxs-lookup"><span data-stu-id="abe28-556">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="abe28-557">Hemos corregido un problema que causaba que los usuarios de las mejoras del calendario compartido no pudieran establecer el color de un calendario en amarillo o marrón.</span><span class="sxs-lookup"><span data-stu-id="abe28-557">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="abe28-558">Hemos corregido un problema que causaba que la app se cerrase para algunos usuarios al cerrar las ventanas de mensaje.</span><span class="sxs-lookup"><span data-stu-id="abe28-558">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="abe28-559">Hemos corregido un problema que provocaba que las firmas con contenido Unicode se dañasen.</span><span class="sxs-lookup"><span data-stu-id="abe28-559">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="abe28-560">Hemos corregido un problema que causaba que los usuarios de traducción directa no pudieran enviar comentarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-560">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2102-february-21"></a><span data-ttu-id="abe28-562">Versión 2102: 21 de febrero</span><span class="sxs-lookup"><span data-stu-id="abe28-562">Version 2102: February 21</span></span>
<span data-ttu-id="abe28-563">*Versión 2102 (compilación 13801.20182)*</span><span class="sxs-lookup"><span data-stu-id="abe28-563">*Version 2102 (Build 13801.20182)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-565">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-565">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-566">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-566">Outlook</span></span>

- <span data-ttu-id="abe28-567">**Escriba mensajes con su voz:** use la nueva barra de herramientas de dictado, los comandos de voz, la puntuación automática y mucho más para redactar mensajes.</span><span class="sxs-lookup"><span data-stu-id="abe28-567">**Draft messages with your voice:** Use the new dictation toolbar, voice commands, auto-punctuation, and more to compose messages.</span></span>

### <a name="word"></a><span data-ttu-id="abe28-568">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-568">Word</span></span>

- <span data-ttu-id="abe28-569">**Escriba documentos con su voz:** use la nueva barra de herramientas de dictado, los comandos de voz, la puntuación automática para redactar documentos.</span><span class="sxs-lookup"><span data-stu-id="abe28-569">**Draft documents with your voice:** Use the new dictation toolbar, voice commands and auto-punctuation to draft documents.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-572">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-572">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-573">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-573">Excel</span></span>

- <span data-ttu-id="abe28-574">Hemos corregido un problema que hace que las imágenes sean más pequeñas de lo esperado al usar la opción Pegar imagen vinculada.</span><span class="sxs-lookup"><span data-stu-id="abe28-574">We fixed an issue which caused images to bee smaller than expected when using the Paste Linked Picture option.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2102-february-16"></a><span data-ttu-id="abe28-576">Versión 2102: 16 de febrero</span><span class="sxs-lookup"><span data-stu-id="abe28-576">Version 2102: February 16</span></span>
<span data-ttu-id="abe28-577">*Versión 2102 (compilación 13801.20160)*</span><span class="sxs-lookup"><span data-stu-id="abe28-577">*Version 2102 (Build 13801.20160)*</span></span>
* <span data-ttu-id="abe28-578">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="abe28-578">Various bugs and performance fixes.</span></span>

## <a name="version-2102-february-15"></a><span data-ttu-id="abe28-579">Versión 2102: 15 de febrero</span><span class="sxs-lookup"><span data-stu-id="abe28-579">Version 2102: February 15</span></span>
<span data-ttu-id="abe28-580">*Versión 2102 (compilación 13801.20158)*</span><span class="sxs-lookup"><span data-stu-id="abe28-580">*Version 2102 (Build 13801.20158)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-582">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-582">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-583">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-583">Outlook</span></span>

- <span data-ttu-id="abe28-584">**Dictado está disponible en más idiomas:** ahora admite 7 idiomas nuevos: hindi, ruso, polaco, portugués (Portugal), coreano, tailandés y chino (Taiwán)</span><span class="sxs-lookup"><span data-stu-id="abe28-584">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>

### <a name="word"></a><span data-ttu-id="abe28-585">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-585">Word</span></span>

- <span data-ttu-id="abe28-586">**Dictado está disponible en más idiomas:** ahora admite 7 idiomas nuevos: hindi, ruso, polaco, portugués (Portugal), coreano, tailandés y chino (Taiwán)</span><span class="sxs-lookup"><span data-stu-id="abe28-586">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-589">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-589">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-590">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-590">Excel</span></span>

- <span data-ttu-id="abe28-591">Hemos corregido un problema que impedía a los usuarios exportar un libro de Excel a PDF.</span><span class="sxs-lookup"><span data-stu-id="abe28-591">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


### <a name="word"></a><span data-ttu-id="abe28-592">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-592">Word</span></span>

- <span data-ttu-id="abe28-593">Hemos corregido un problema relacionado con la resolución de conflictos durante la coautoría.</span><span class="sxs-lookup"><span data-stu-id="abe28-593">We fixed an issue in resolving conflicts while in coauthoring.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)


## <a name="version-2102-february-11"></a><span data-ttu-id="abe28-595">Versión 2102: 11 de febrero</span><span class="sxs-lookup"><span data-stu-id="abe28-595">Version 2102: February 11</span></span>
<span data-ttu-id="abe28-596">*Versión 2102 (compilación 13801.20158)*</span><span class="sxs-lookup"><span data-stu-id="abe28-596">*Version 2102 (Build 13801.20158)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-598">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-598">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="abe28-599">Teams</span><span class="sxs-lookup"><span data-stu-id="abe28-599">Teams</span></span>

- <span data-ttu-id="abe28-600">**Vídeo de 2x2 en los exploradores Microsoft Edge y Chrome en equipos Windows y Mac** Los usuarios pueden ver un máximo de 4 participantes en reuniones de Teams en los exploradores Microsoft Edge y Chrome en Windows y Mac.</span><span class="sxs-lookup"><span data-stu-id="abe28-600">**2x2 video on Edge and Chrome browsers on Windows and Mac** Users can see up to 4 participants' video in Teams meetings in Edge and Chrome browsers on Windows and Mac.</span></span> [<span data-ttu-id="abe28-601">Obtener más información</span><span class="sxs-lookup"><span data-stu-id="abe28-601">Learn more</span></span>](https://support.microsoft.com/office/using-video-in-microsoft-teams-3647fc29-7b92-4c26-8c2d-8a596904cdae#bkmk_videolayout)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

## <a name="version-2102-february-08"></a><span data-ttu-id="abe28-603">Versión 2102: 8 de febrero</span><span class="sxs-lookup"><span data-stu-id="abe28-603">Version 2102: February 08</span></span>
<span data-ttu-id="abe28-604">*Versión 2102 (Compilación 13801.20084)*</span><span class="sxs-lookup"><span data-stu-id="abe28-604">*Version 2102 (Build 13801.20084)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-606">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-606">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-607">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-607">Outlook</span></span>

- <span data-ttu-id="abe28-608">**Sugerencias de redacción con tecnología de Búsqueda de Microsoft (Para\CC\CCO):** ahora la adición de personas a la línea Para\CC usa la tecnología de Búsqueda de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="abe28-608">**Microsoft Search powered compose (To\CC\BCC) suggestions:** Adding people to the To\CC line is now powered by Microsoft Search.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-611">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-611">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="abe28-612">Access</span><span class="sxs-lookup"><span data-stu-id="abe28-612">Access</span></span>

- <span data-ttu-id="abe28-613">Ahora verá las pestañas seleccionadas más claramente en Access.</span><span class="sxs-lookup"><span data-stu-id="abe28-613">You will now see selected tabs clearer in Access.</span></span>


### <a name="excel"></a><span data-ttu-id="abe28-614">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-614">Excel</span></span>

- <span data-ttu-id="abe28-615">Se ha corregido un problema que hace que determinados gráficos que usan rangos de celdas discontinuos no se carguen al volver a abrir los archivos.</span><span class="sxs-lookup"><span data-stu-id="abe28-615">Fixes issue where certain charts using discontinuous ranges of cells would not load when files are re-opened.</span></span>


- <span data-ttu-id="abe28-616">Corrige un problema por el que Excel no se iniciaba o se cerraba inesperadamente si se estaba usando cierta configuración de protección contra vulnerabilidades de Seguridad de Windows (SimExec, CallerCheck).</span><span class="sxs-lookup"><span data-stu-id="abe28-616">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="abe28-617">Hemos corregido un problema por el que Excel dejaba de responder después de seleccionar una serie de datos en un gráfico.</span><span class="sxs-lookup"><span data-stu-id="abe28-617">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="abe28-618">Hemos corregido un problema en el que Excel se cerraba inesperadamente al agregar un nombre en el cuadro de diálogo Definir nombre.</span><span class="sxs-lookup"><span data-stu-id="abe28-618">We fixed an issue where Excel would unexpectedly quit when you added a Name in the Define Name dialog.</span></span>


- <span data-ttu-id="abe28-619">Se ha corregido un problema relacionado con las imágenes que conservaban su relación de aspecto durante una operación de recorte.</span><span class="sxs-lookup"><span data-stu-id="abe28-619">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="outlook"></a><span data-ttu-id="abe28-620">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-620">Outlook</span></span>

- <span data-ttu-id="abe28-621">Hemos corregido un problema por el que los mensajes de correo electrónico se enviaban como firmados digitalmente después de que el usuario desactivara esa opción.</span><span class="sxs-lookup"><span data-stu-id="abe28-621">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


- <span data-ttu-id="abe28-622">Hemos corregido un problema que causaba que no se mostrara el icono de cifrado de los correos electrónicos enviados con la opción Solo cifrar.</span><span class="sxs-lookup"><span data-stu-id="abe28-622">We fixed an issue that caused the encryption icon to fail to display for emails sent using the Encrypt Only option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="abe28-623">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-623">PowerPoint</span></span>

- <span data-ttu-id="abe28-624">Se ha corregido un problema relacionado con la muestra de emojis con color.</span><span class="sxs-lookup"><span data-stu-id="abe28-624">Fixed an issue related to displaying emojis with color.</span></span>


- <span data-ttu-id="abe28-625">Se ha corregido un problema relacionado con las imágenes que conservaban su relación de aspecto durante una operación de recorte.</span><span class="sxs-lookup"><span data-stu-id="abe28-625">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="visio"></a><span data-ttu-id="abe28-626">Visio</span><span class="sxs-lookup"><span data-stu-id="abe28-626">Visio</span></span>

- <span data-ttu-id="abe28-627">Ya se ha corregido el problema con la representación de formas de galerías de símbolos de CAD.</span><span class="sxs-lookup"><span data-stu-id="abe28-627">This issue on shape rendering from CAD stencils has now been fixed.</span></span> <span data-ttu-id="abe28-628">Los usuarios verán el problema resuelto en la compilación más reciente.</span><span class="sxs-lookup"><span data-stu-id="abe28-628">Users will see the issue resolved in the latest build.</span></span>


### <a name="word"></a><span data-ttu-id="abe28-629">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-629">Word</span></span>

- <span data-ttu-id="abe28-630">Esto corrige un problema que impedía que la escritura en tiempo real y la presencia se restauraran tras perder la conectividad a Internet durante un período de tiempo.</span><span class="sxs-lookup"><span data-stu-id="abe28-630">This fixes an issue that prevented real-time typing and presence from being restored after losing internet connectivity for a period of time.</span></span>


- <span data-ttu-id="abe28-631">Cuando un usuario selecciona texto en un comentario, ahora Word anula la selección del texto seleccionado en otros comentarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-631">When a user selects text in a comment, Word now unselects selected text in other comments.</span></span>


- <span data-ttu-id="abe28-632">Ahora Word permite copiar texto de comentarios en Excel.</span><span class="sxs-lookup"><span data-stu-id="abe28-632">Word now allows copying comment text into Excel.</span></span>


- <span data-ttu-id="abe28-633">Se corrigió un problema por el que, al ejecutar la macro de VBA ExportAsFixedFormat2, se produce un error que indica "Valor no válido de presentación (miembro desconocido)".</span><span class="sxs-lookup"><span data-stu-id="abe28-633">We fixed an issue when running the VBA macro ExportAsFixedFormat2 fails with an error stating "Presentation (unknown member) illegal value".</span></span>


- <span data-ttu-id="abe28-634">Se ha corregido un problema relacionado con las imágenes que conservaban su relación de aspecto durante una operación de recorte.</span><span class="sxs-lookup"><span data-stu-id="abe28-634">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


- <span data-ttu-id="abe28-635">Hemos corregido un problema que podía truncar un comentario con vínculos.</span><span class="sxs-lookup"><span data-stu-id="abe28-635">We fixed an issue which the comment may be truncated with links.</span></span>


- <span data-ttu-id="abe28-636">Hemos corregido un problema relacionado con guardar archivos en SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="abe28-636">We fixed an issue in saving to SharePoint Online</span></span>


- <span data-ttu-id="abe28-637">Hemos corregido un problema relacionado con la exportación de un documento de Word a PDF.</span><span class="sxs-lookup"><span data-stu-id="abe28-637">We fixed an issue in exporting Word document to PDF.</span></span>


- <span data-ttu-id="abe28-638">Se ha corregido un problema con la Autorrecuperación.</span><span class="sxs-lookup"><span data-stu-id="abe28-638">We fixed an issue with AutoRecover.</span></span>

- <span data-ttu-id="abe28-639">Se ha corregido un problema al trabajar con coautoría en archivos protegidos DRM</span><span class="sxs-lookup"><span data-stu-id="abe28-639">We fixed an issue when coauthoring with DRM protected files</span></span>


### <a name="office-suite"></a><span data-ttu-id="abe28-640">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-640">Office Suite</span></span>

- <span data-ttu-id="abe28-641">Solución de un error en PowerPoint que causaba que las viñetas desapareciesen al insertar viñetas como imágenes.</span><span class="sxs-lookup"><span data-stu-id="abe28-641">Fixing a bug in PowerPoint where inserting bullets as images would result in bullets disappearing.</span></span> <span data-ttu-id="abe28-642">Esta corrección hace que su representación sea más confiable.</span><span class="sxs-lookup"><span data-stu-id="abe28-642">This fix makes it so they render more reliably.</span></span>

- <span data-ttu-id="abe28-643">Se ha corregido un problema por el que, en algunas circunstancias, Office presentaba etiquetas de confidencialidad para una cuenta con la que se había iniciado sesión en lugar de presentarlas para otra cuenta diferente con la que se había iniciado sesión.</span><span class="sxs-lookup"><span data-stu-id="abe28-643">Fixed an issue where Office would in some circumstances present sensitivity labels for one signed-in account when it should present sensitivity labels for a different signed-in account.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2101-february-03"></a><span data-ttu-id="abe28-645">Versión 2101: 3 de febrero</span><span class="sxs-lookup"><span data-stu-id="abe28-645">Version 2101: February 03</span></span>
<span data-ttu-id="abe28-646">*Versión 2101 (compilación 13628.20330)*</span><span class="sxs-lookup"><span data-stu-id="abe28-646">*Version 2101 (Build 13628.20330)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-648">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-648">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-649">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-649">Outlook</span></span>

- <span data-ttu-id="abe28-650">Hemos corregido un problema que causaba errores al mostrar la firma predeterminada correcta en OWA.</span><span class="sxs-lookup"><span data-stu-id="abe28-650">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="abe28-651">Hemos corregido un problema que hacía que no se mostrara el icono de cifrado de los correos electrónicos enviados con la opción de solo cifrado.</span><span class="sxs-lookup"><span data-stu-id="abe28-651">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>



[//]: # (NO QUITAR FINAL DE CONTENIDO CON DETALLES DE ERROR)

## <a name="version-2101-february-02"></a><span data-ttu-id="abe28-653">Versión 2101: 02 de febrero</span><span class="sxs-lookup"><span data-stu-id="abe28-653">Version 2101: February 02</span></span>
<span data-ttu-id="abe28-654">*Versión 2101 (compilación 13628.20320)*</span><span class="sxs-lookup"><span data-stu-id="abe28-654">*Version 2101 (Build 13628.20320)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-656">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-656">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-657">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-657">Outlook</span></span>

- <span data-ttu-id="abe28-658">Hemos corregido un problema que causaba que los usuarios de Configuración de la nube tuviesen un error al actualizar la configuración.</span><span class="sxs-lookup"><span data-stu-id="abe28-658">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2101-january-25"></a><span data-ttu-id="abe28-660">Versión 2101: 25 de enero</span><span class="sxs-lookup"><span data-stu-id="abe28-660">Version 2101: January 25</span></span>
<span data-ttu-id="abe28-661">*Versión 2101 (Compilación 13628.20274)*</span><span class="sxs-lookup"><span data-stu-id="abe28-661">*Version 2101 (Build 13628.20274)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-663">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-663">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-664">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-664">Excel</span></span>

- <span data-ttu-id="abe28-665">**Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H.</span><span class="sxs-lookup"><span data-stu-id="abe28-665">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="abe28-666">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-666">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="abe28-667">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-667">Outlook</span></span>

- <span data-ttu-id="abe28-668">**Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H.</span><span class="sxs-lookup"><span data-stu-id="abe28-668">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="abe28-669">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-669">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a><span data-ttu-id="abe28-670">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-670">PowerPoint</span></span>

- <span data-ttu-id="abe28-671">**Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H.</span><span class="sxs-lookup"><span data-stu-id="abe28-671">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> <span data-ttu-id="abe28-672">[Más información](/microsoft-365/compliance/sensitivity-labels).</span><span class="sxs-lookup"><span data-stu-id="abe28-672">[Learn more](/microsoft-365/compliance/sensitivity-labels).</span></span>


### <a name="word"></a><span data-ttu-id="abe28-673">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-673">Word</span></span>

- <span data-ttu-id="abe28-674">**Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H.</span><span class="sxs-lookup"><span data-stu-id="abe28-674">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="abe28-675">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-675">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)


### <a name="resolved-issues"></a><span data-ttu-id="abe28-676">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-676">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-677">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-677">Outlook</span></span>

- <span data-ttu-id="abe28-678">Se ha corregido un problema que causaba que los usuarios que tienen buzones compartidos o delegados con jerarquías grandes en su perfil sufriesen bloqueos.</span><span class="sxs-lookup"><span data-stu-id="abe28-678">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)



## <a name="version-2101-january-18"></a><span data-ttu-id="abe28-680">Versión 2101: 18 de enero</span><span class="sxs-lookup"><span data-stu-id="abe28-680">Version 2101: January 18</span></span>
<span data-ttu-id="abe28-681">*Versión 2101 (compilación 13628.20158)*</span><span class="sxs-lookup"><span data-stu-id="abe28-681">*Version 2101 (Build 13628.20158)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)



[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-685">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-685">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="abe28-686">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-686">Project</span></span>

- <span data-ttu-id="abe28-687">Se ha corregido un problema en el que los bordes no se mostraban para las tareas en la vista Organizador de equipo.</span><span class="sxs-lookup"><span data-stu-id="abe28-687">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="abe28-688">Se ha corregido un problema en el que la opción de arrastrar y colocar no funcionaba para las tareas de la vista Organizador de equipo.</span><span class="sxs-lookup"><span data-stu-id="abe28-688">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2101-january-13"></a><span data-ttu-id="abe28-690">Versión 2101: 13 de enero</span><span class="sxs-lookup"><span data-stu-id="abe28-690">Version 2101: January 13</span></span>
<span data-ttu-id="abe28-691">*Versión 2101 (compilación 13628.20118)*</span><span class="sxs-lookup"><span data-stu-id="abe28-691">*Version 2101 (Build 13628.20118)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)
### <a name="feature-updates"></a><span data-ttu-id="abe28-693">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-693">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="abe28-694">Teams</span><span class="sxs-lookup"><span data-stu-id="abe28-694">Teams</span></span>
- <span data-ttu-id="abe28-695">**Más temas:** ahora hay nuevos temas disponibles para clientes web y de escritorio.</span><span class="sxs-lookup"><span data-stu-id="abe28-695">**More themes:** New themes are now available for desktop and web clients.</span></span>

- <span data-ttu-id="abe28-696">**Uso compartido de PPT:** vista Moderador en Teams. Una vez que seleccione un archivo de PowerPoint en la bandeja Compartir de Teams, la vista Moderador se abrirá automáticamente.</span><span class="sxs-lookup"><span data-stu-id="abe28-696">**PPT Sharing:** Presenter View in Teams Once you select a PowerPoint file from the Teams Share Tray, Presenter View is opened automatically.</span></span> <span data-ttu-id="abe28-697">Puede ver la diapositiva actual, las notas de las diapositivas y una franja de miniaturas de todas las diapositivas de la presentación para facilitar la navegación de diapositivas ad-hoc.</span><span class="sxs-lookup"><span data-stu-id="abe28-697">You can see the current slide, the slide notes, and a thumbnail strip of all the slides in the deck for easy ad-hoc slide navigation.</span></span> <span data-ttu-id="abe28-698">Esta vista está completamente en segundo plano y es privada para el moderador que tiene el control.</span><span class="sxs-lookup"><span data-stu-id="abe28-698">This view is completely behind the scenes, and it’s private to the presenter in control.</span></span> <span data-ttu-id="abe28-699">El público solo puede ver la diapositiva actual (resaltada en el cuadro rojo grande) o la diapositiva a la que decida navegar (si la navegación del público no está bloqueada por usted).</span><span class="sxs-lookup"><span data-stu-id="abe28-699">Your audience can only see your current slide (highlighted in the big red box), or the slide that they choose to navigate to (if audience navigation is not locked by you).</span></span> 

- <span data-ttu-id="abe28-700">**Incluir sonido de equipo al compartir ventanas o el escritorio en Mac** Al compartir un escritorio o ventana desde Teams en Mac, ahora puede incluir el sonido de su equipo para que las personas que se han unido a la reunión puedan escuchar el audio de reproducción del equipo.</span><span class="sxs-lookup"><span data-stu-id="abe28-700">**Include computer sound when desktop or window sharing on Mac** When you share a desktop or window from Teams on Mac, you can now include your computer's sound so people that have joined the meeting can hear the audio playing out of your computer.</span></span>

[//]: # (NO QUITAR DETALLES DE CARACTERÍSTICAS CONTENIDO FINAL)
<br/>

## <a name="version-2101-january-09"></a><span data-ttu-id="abe28-702">Versión 2101: 09 de enero</span><span class="sxs-lookup"><span data-stu-id="abe28-702">Version 2101: January 09</span></span>
<span data-ttu-id="abe28-703">*Versión 2101 (compilación 13628.20118)*</span><span class="sxs-lookup"><span data-stu-id="abe28-703">*Version 2101 (Build 13628.20118)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-705">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-705">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-706">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-706">Outlook</span></span>

- <span data-ttu-id="abe28-707">**Sugerencias de escritura con un solo clic:** Aplique sugerencias de escritura con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="abe28-707">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="abe28-708">El editor corrige la ortografía y la gramática y le da ideas para refinar su escritura.</span><span class="sxs-lookup"><span data-stu-id="abe28-708">Editor corrects spelling and grammar and gives you ideas for refining your writing.</span></span> [<span data-ttu-id="abe28-709">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-709">Learn more</span></span>](https://support.office.com/article/1e72a440-89a6-457c-bd76-cd5cea901dc0)<br /><span data-ttu-id="abe28-710">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/microsoft-editor-gets-an-upgrade)</span><span class="sxs-lookup"><span data-stu-id="abe28-710">See details in [blog post](https://insider.office.com/es-ES/blog/microsoft-editor-gets-an-upgrade)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-713">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-713">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-714">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-714">Outlook</span></span>

- <span data-ttu-id="abe28-715">Se ha corregido un problema que provocaba que Outlook se cerrara de forma inesperada para algunos usuarios en ciertos escenarios de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="abe28-715">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>



[//]: # (NO QUITAR LOS DETALLES DE ERROR AL FINAL DEL CONTENIDO)

## <a name="version-2101-january-07"></a><span data-ttu-id="abe28-717">Versión 2101: 7 de enero</span><span class="sxs-lookup"><span data-stu-id="abe28-717">Version 2101: January 07</span></span>
<span data-ttu-id="abe28-718">*Versión 2101 (compilación 13628.20030)*</span><span class="sxs-lookup"><span data-stu-id="abe28-718">*Version 2101 (Build 13628.20030)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-720">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-720">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-721">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-721">Excel</span></span>

- <span data-ttu-id="abe28-722">**Mostrar varias hojas de cálculo al mismo tiempo:** no es necesario que se muestren las hojas de una en una, ya que se pueden mostrar varias hojas ocultas al mismo tiempo.</span><span class="sxs-lookup"><span data-stu-id="abe28-722">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="abe28-723">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-723">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

- <span data-ttu-id="abe28-724">**Cuadros de diálogo de formato condicional mejorados:** Los diálogos de formato condicional ahora son de tamaño ajustable y se puede duplicar la regla con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="abe28-724">**Improved Conditional Formatting dialogs:** Conditional Formatting dialogs are now resizable, and now you can duplicate the rule with a single click.</span></span> [<span data-ttu-id="abe28-725">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-725">Learn more</span></span>](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-728">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-728">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-729">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-729">Excel</span></span>

- <span data-ttu-id="abe28-730">Se ha corregido un problema por el que Excel mostraba de forma incorrecta una barra de mensajes donde se indicaba que estaba disponible una nueva versión del archivo y obligaba al usuario a descartar los cambios o guardarlos en una copia del libro.</span><span class="sxs-lookup"><span data-stu-id="abe28-730">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="abe28-731">Se ha corregido un problema con los separadores de conmutación después de Selection.Parent.Copy.</span><span class="sxs-lookup"><span data-stu-id="abe28-731">Fixed an issue with switching separators after a Selection.Parent.Copy call.</span></span>


- <span data-ttu-id="abe28-732">Se realizó una mejora de rendimiento al aplicar estilos de formato a las tablas dinámicas.</span><span class="sxs-lookup"><span data-stu-id="abe28-732">Made a performance improvement when applying formatting styles to pivot tables.</span></span>


- <span data-ttu-id="abe28-733">Se ha corregido un problema que provocaba que Excel dejara macros deshabilitadas sin preguntar al abrir archivos de complemento de Excel que contuvieran macros Excel 4.0.</span><span class="sxs-lookup"><span data-stu-id="abe28-733">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="abe28-734">Actualización para que la configuración de los separadores decimales y de millares se mantenga al copiar un gráfico de Excel y pegarlo en Word.</span><span class="sxs-lookup"><span data-stu-id="abe28-734">Update so that decimal and thousands separators settings carryover when copying a chart from Excel and pasting into Word</span></span>


- <span data-ttu-id="abe28-735">Se ha corregido un problema por el que Excel se cerraba inesperadamente al abrir archivos UNC con atributos de archivo no válidos (hora de creación, fecha de modificación, etc.).</span><span class="sxs-lookup"><span data-stu-id="abe28-735">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="abe28-736">Se ha corregido un problema que podría provocar una alerta de "recursos insuficientes" al usar la función STOCKHISTORY.</span><span class="sxs-lookup"><span data-stu-id="abe28-736">Fixed an issue which could cause an "out of resources" alert when using the STOCKHISTORY function.</span></span>


- <span data-ttu-id="abe28-737">Se ha agregado una DLL FuzzyClustering a la lista de DLL PQ.</span><span class="sxs-lookup"><span data-stu-id="abe28-737">Added a FuzzyClustering dll to PQ dlls list.</span></span>


- <span data-ttu-id="abe28-738">Este cambio resuelve un problema relacionado con la modificación de los colores del contorno de imágenes SVG.</span><span class="sxs-lookup"><span data-stu-id="abe28-738">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="abe28-739">Se ha corregido un problema que provocaba que la vista previa del intervalo de Excel insertado en PowerPoint mostrara un tamaño incorrecto.</span><span class="sxs-lookup"><span data-stu-id="abe28-739">We have fixed an issue where Preview of embedded Excel range in PowerPoint shows incorrect size.</span></span>


### <a name="onenote"></a><span data-ttu-id="abe28-740">OneNote</span><span class="sxs-lookup"><span data-stu-id="abe28-740">OneNote</span></span>

- <span data-ttu-id="abe28-741">Este cambio resuelve un problema de representación que afecta a OneNote.</span><span class="sxs-lookup"><span data-stu-id="abe28-741">This change addresses a rendering issue affecting OneNote.</span></span>


### <a name="outlook"></a><span data-ttu-id="abe28-742">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-742">Outlook</span></span>

- <span data-ttu-id="abe28-743">Se ha corregido un problema que provocaba que los usuarios no pudiesen especificar durante cuánto tiempo querían permitir el acceso al iniciar una combinación de correo de Word, lo que hacía que se enviasen demasiados avisos.</span><span class="sxs-lookup"><span data-stu-id="abe28-743">We fixed an issue that caused users to be unable to specify how long they wanted to allow access for when starting a mail merge from Word, resulting in them getting excess prompts.</span></span>


- <span data-ttu-id="abe28-744">Este cambio permite a Outlook aprovechar una configuración de Exchange Server que suprime la presentación del buzón de correo de Exchange Online para usuarios finales.</span><span class="sxs-lookup"><span data-stu-id="abe28-744">This change enables Outlook to take advantage of an Exchange server setting that suppresses the display of the Exchange Online Archive Mailbox to end users.</span></span>


- <span data-ttu-id="abe28-745">Se ha corregido un problema que provocaba que Outlook se cerrara de forma inesperada para los usuarios de complementos basados en Redemption.</span><span class="sxs-lookup"><span data-stu-id="abe28-745">We fixed an issue that caused a Outlook to close unexpectedly for users of Redemption based Add-ins.</span></span>


- <span data-ttu-id="abe28-746">Se corrigió el problema que causaba que los usuarios no pudieran seleccionar más de una categoría para buscar.</span><span class="sxs-lookup"><span data-stu-id="abe28-746">We fixed and issue that caused users to be unable to select more than one category to search.</span></span>


- <span data-ttu-id="abe28-747">Se corrigió el problema que causaba que la hora de inicio de algunos elementos del calendario cambiara inesperadamente cuando el evento se copiaba de otra cita.</span><span class="sxs-lookup"><span data-stu-id="abe28-747">We fixed an issue that caused the start time of some calendar items to change unexpectedly when the event is copied from another appointment.</span></span>


- <span data-ttu-id="abe28-748">Se corrigió un problema por el que los mensajes de texto sin formato S/MIME se volvían ilegibles al enviarse.</span><span class="sxs-lookup"><span data-stu-id="abe28-748">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="abe28-749">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-749">PowerPoint</span></span>

- <span data-ttu-id="abe28-750">Este cambio resuelve un problema con las formas de combinar trabajar con texto.</span><span class="sxs-lookup"><span data-stu-id="abe28-750">This change addresses an issue with Merge Shapes working with text.</span></span>


- <span data-ttu-id="abe28-751">Este cambio resuelve un problema relacionado con la modificación de los colores del contorno de imágenes SVG.</span><span class="sxs-lookup"><span data-stu-id="abe28-751">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="abe28-752">Este cambio resuelve un problema en la reproducción de vídeos de fondo en bucle en la presentación con diapositivas.</span><span class="sxs-lookup"><span data-stu-id="abe28-752">This change addresses an issue with looping background videos playback in Slide Show.</span></span>


- <span data-ttu-id="abe28-753">Se ha corregido un problema por el que el comando tamaño de fuente, agregado a la herramienta de acceso rápido, se completaba automáticamente al tamaño de fuente definido más cercano al actualizarse.</span><span class="sxs-lookup"><span data-stu-id="abe28-753">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


### <a name="project"></a><span data-ttu-id="abe28-754">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-754">Project</span></span>

- <span data-ttu-id="abe28-755">Se ha corregido un problema que provocaba que las unidades máximas de un recurso no siempre reflejaran la actualización más reciente en las unidades máximas.</span><span class="sxs-lookup"><span data-stu-id="abe28-755">Fixed an issue where a resource's max units would not always reflect the latest update to max units.</span></span>


### <a name="visio"></a><span data-ttu-id="abe28-756">Visio</span><span class="sxs-lookup"><span data-stu-id="abe28-756">Visio</span></span>

- <span data-ttu-id="abe28-757">El problema se debe a una regresión reciente.</span><span class="sxs-lookup"><span data-stu-id="abe28-757">The issue occurred due to a recent regression.</span></span> <span data-ttu-id="abe28-758">Se ha resuelto el problema.</span><span class="sxs-lookup"><span data-stu-id="abe28-758">We have resolved the issue.</span></span> <span data-ttu-id="abe28-759">El cuadro de diálogo "Guardar como página web" ahora hará que los campos se rellenen correctamente en función de las entradas de usuario, y que los usuarios puedan guardar los archivos como páginas web sin problemas.</span><span class="sxs-lookup"><span data-stu-id="abe28-759">"Save as Web Page" dialog will now have the fields correctly populated as per the user inputs and users can seamlessly save their files as web pages.</span></span>


- <span data-ttu-id="abe28-p144">Este problema se ha corregido. Ahora se pueden insertar archivos de Visio como objetos en otras aplicaciones de Office, como PowerPoint y Word, y obtener acceso a ellos fácilmente desde estas aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="abe28-p144">This issue has been fixed. You can now embed Visio files as objects in other Office applications like PowerPoint and Word and seamlessly access them from within these applications.</span></span>


### <a name="word"></a><span data-ttu-id="abe28-762">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-762">Word</span></span>

- <span data-ttu-id="abe28-763">Se ha corregido un problema que provocaba que los equipos con la configuración de hash personalizada tuvieran problemas al estar en una sesión de colaboración con una configuración de hash diferente de sha512.</span><span class="sxs-lookup"><span data-stu-id="abe28-763">Fixed an issue where machines with custom hash settings were running in to issues when they got into a collab session with a hash setting other than sha512.</span></span>


- <span data-ttu-id="abe28-764">Este cambio resuelve un problema relacionado con la modificación de los colores del contorno de imágenes SVG.</span><span class="sxs-lookup"><span data-stu-id="abe28-764">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="abe28-765">Se ha corregido un problema al editar una entrada de comentario que incluía una @mención.</span><span class="sxs-lookup"><span data-stu-id="abe28-765">Fixed an issue when editing commenting post with @mention.</span></span>


- <span data-ttu-id="abe28-766">Se ha corregido un problema para mejorar la solidez de los comentarios modernos.</span><span class="sxs-lookup"><span data-stu-id="abe28-766">Fixed an issue to make Modern comments more robust.</span></span>


- <span data-ttu-id="abe28-767">Se ha corregido un problema en torno a la eliminación de los comentarios modernos en un control de contenido marcado como no editable.</span><span class="sxs-lookup"><span data-stu-id="abe28-767">We fixed an issue around deleting modern comments in a content control that is marked as not editable.</span></span>


- <span data-ttu-id="abe28-768">Animación corregida al escribir en la parte inferior de una tarjeta de comentario.</span><span class="sxs-lookup"><span data-stu-id="abe28-768">Fix animation when typing on the bottom of a comment card.</span></span>


- <span data-ttu-id="abe28-769">Corrección de un problema que provocaba que el cuadro de respuesta en una tarjeta de comentario apareciera fuera de la pantalla.</span><span class="sxs-lookup"><span data-stu-id="abe28-769">Fixes an issue where the reply box on a comment card is off the screen.</span></span>


- <span data-ttu-id="abe28-770">Corrección de un problema con una tarjeta de comentario que se mostraba en la parte superior de la página.</span><span class="sxs-lookup"><span data-stu-id="abe28-770">Fixes an issue with a comment card displaying at top of page.</span></span>


- <span data-ttu-id="abe28-771">Corrección de errores en comentarios en los que el texto podía desplazarse fuera de la pantalla.</span><span class="sxs-lookup"><span data-stu-id="abe28-771">Fixes bug in comments where text can scroll off screen.</span></span>


- <span data-ttu-id="abe28-772">Corrección de un problema con las barras de desplazamiento anidadas en el panel de comentarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-772">Fix and issue with nested scrollbars in the comments pane.</span></span>


- <span data-ttu-id="abe28-773">Los borradores de comentarios desaparecen al crear una nueva instancia de Word.</span><span class="sxs-lookup"><span data-stu-id="abe28-773">Comment drafts disappears when creating a new Word instance.</span></span>


- <span data-ttu-id="abe28-774">Se ha corregido un problema que causaba que Word se bloqueara al guardar un documento en PDF con texto oculto.</span><span class="sxs-lookup"><span data-stu-id="abe28-774">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2012-january-04"></a><span data-ttu-id="abe28-776">Versión 2012: 4 de enero</span><span class="sxs-lookup"><span data-stu-id="abe28-776">Version 2012: January 04</span></span>
<span data-ttu-id="abe28-777">*Versión 2012 (compilación 13530.20316)*</span><span class="sxs-lookup"><span data-stu-id="abe28-777">*Version 2012 (Build 13530.20316)*</span></span>
* <span data-ttu-id="abe28-778">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="abe28-778">Various bugs and performance fixes.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-780">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-780">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-781">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-781">Excel</span></span>

- <span data-ttu-id="abe28-782">**Etiqueta obligatoria:** usuarios con la Directiva de etiquetado obligatoria se debe establecer que los administradores les etiqueten sus documentos y mensajes de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="abe28-782">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="abe28-783">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-783">PowerPoint</span></span>

- <span data-ttu-id="abe28-784">**Etiqueta obligatoria:** usuarios con la Directiva de etiquetado obligatoria se debe establecer que los administradores les etiqueten sus documentos y mensajes de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="abe28-784">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="word"></a><span data-ttu-id="abe28-785">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-785">Word</span></span>

- <span data-ttu-id="abe28-786">**Etiqueta obligatoria:** usuarios con la Directiva de etiquetado obligatoria se debe establecer que los administradores les etiqueten sus documentos y mensajes de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="abe28-786">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

## <a name="version-2012-december-28"></a><span data-ttu-id="abe28-788">Versión 2012: 28 de diciembre</span><span class="sxs-lookup"><span data-stu-id="abe28-788">Version 2012: December 28</span></span>
<span data-ttu-id="abe28-789">*Versión 2012 (Build 13530.20264)*</span><span class="sxs-lookup"><span data-stu-id="abe28-789">*Version 2012 (Build 13530.20264)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-791">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-791">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-792">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-792">Outlook</span></span>

- <span data-ttu-id="abe28-793">Se ha arreglado un problema que causaba que algunos clientes experimentaran un cuelgue mientras cargaban sus calendarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-793">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>



[//]: # (NO QUITAR LOS DETALLES DE ERROR AL FINAL DEL CONTENIDO)

## <a name="version-2012-december-21"></a><span data-ttu-id="abe28-795">Versión 2012: 21 de diciembre</span><span class="sxs-lookup"><span data-stu-id="abe28-795">Version 2012: December 21</span></span>
<span data-ttu-id="abe28-796">*Versión 2012 (compilación 13530.20218)*</span><span class="sxs-lookup"><span data-stu-id="abe28-796">*Version 2012 (Build 13530.20218)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-798">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-798">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-799">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-799">Excel</span></span>

- <span data-ttu-id="abe28-800">**Envío de datos de auditoría sobre el etiquetado de confidencialidad a los administradores de M365:** cuando los usuarios apliquen, cambien o eliminen las etiquetas de confidencialidad en sus documentos y correos electrónicos, Office enviará datos de auditoría al back-end de auditoría de M365 para que los administradores los vean.</span><span class="sxs-lookup"><span data-stu-id="abe28-800">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="abe28-801">Esta es una funcionalidad silenciosa (sin interfaz de usuario) para beneficio del administrador.</span><span class="sxs-lookup"><span data-stu-id="abe28-801">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-802">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-802">Outlook</span></span>

- <span data-ttu-id="abe28-803">**Dar algo de tiempo entre reuniones consecutivas:** asigne a los asistentes el tiempo necesario para que descansen o se desplacen entre las distintas ubicaciones. Para ello haga que las reuniones empiecen de 5 a 10 minutos antes de forma predeterminada.</span><span class="sxs-lookup"><span data-stu-id="abe28-803">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="abe28-804">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-804">Learn more</span></span>](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

- <span data-ttu-id="abe28-805">**Envío de datos de auditoría sobre el etiquetado de confidencialidad a los administradores de M365:** cuando los usuarios apliquen, cambien o eliminen las etiquetas de confidencialidad en sus documentos y correos electrónicos, Office enviará datos de auditoría al back-end de auditoría de M365 para que los administradores los vean.</span><span class="sxs-lookup"><span data-stu-id="abe28-805">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="abe28-806">Esta es una funcionalidad silenciosa (sin interfaz de usuario) para beneficio del administrador.</span><span class="sxs-lookup"><span data-stu-id="abe28-806">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="abe28-807">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-807">PowerPoint</span></span>

- <span data-ttu-id="abe28-808">**Envío de datos de auditoría sobre el etiquetado de confidencialidad a los administradores de M365:** cuando los usuarios apliquen, cambien o eliminen las etiquetas de confidencialidad en sus documentos y correos electrónicos, Office enviará datos de auditoría al back-end de auditoría de M365 para que los administradores los vean.</span><span class="sxs-lookup"><span data-stu-id="abe28-808">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="abe28-809">Esta es una funcionalidad silenciosa (sin interfaz de usuario) para beneficio del administrador.</span><span class="sxs-lookup"><span data-stu-id="abe28-809">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="word"></a><span data-ttu-id="abe28-810">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-810">Word</span></span>

- <span data-ttu-id="abe28-811">**Envío de datos de auditoría sobre el etiquetado de confidencialidad a los administradores de M365:** cuando los usuarios apliquen, cambien o eliminen las etiquetas de confidencialidad en sus documentos y correos electrónicos, Office enviará datos de auditoría al back-end de auditoría de M365 para que los administradores los vean.</span><span class="sxs-lookup"><span data-stu-id="abe28-811">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="abe28-812">Esta es una funcionalidad silenciosa (sin interfaz de usuario) para beneficio del administrador.</span><span class="sxs-lookup"><span data-stu-id="abe28-812">This is a silent functionality (no UI) for administrator benefit.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-815">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-815">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="abe28-816">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-816">PowerPoint</span></span>

- <span data-ttu-id="abe28-817">Se ha corregido un problema por el que el comando tamaño de fuente, agregado a la herramienta de acceso rápido, se completaba automáticamente al tamaño de fuente definido más cercano al actualizarse.</span><span class="sxs-lookup"><span data-stu-id="abe28-817">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>



[//]: # (NO QUITAR NINGÚN DETALLE DE ERROR EN EL FINAL DEL CONTENIDO)

## <a name="version-2012-december-14"></a><span data-ttu-id="abe28-819">Versión 2012: 14 de diciembre</span><span class="sxs-lookup"><span data-stu-id="abe28-819">Version 2012: December 14</span></span>
<span data-ttu-id="abe28-820">*Versión 2012 (compilación 13530.20144)*</span><span class="sxs-lookup"><span data-stu-id="abe28-820">*Version 2012 (Build 13530.20144)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-822">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-822">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-823">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-823">Outlook</span></span>

- <span data-ttu-id="abe28-824">**Su configuración de Outlook en la nube:** elija la configuración de Outlook para Windows, como Respuestas automáticas, la Bandeja de entrada Prioritarios y Privacidad, y acceda a ellos desde cualquier PC.</span><span class="sxs-lookup"><span data-stu-id="abe28-824">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-827">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-827">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="abe28-828">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-828">Office Suite</span></span>

- <span data-ttu-id="abe28-829">Tamaño binario optimizado.</span><span class="sxs-lookup"><span data-stu-id="abe28-829">Optimized binary size.</span></span>


- <span data-ttu-id="abe28-830">Anaheim WebView aún no es compatible con Windows Information Protection.</span><span class="sxs-lookup"><span data-stu-id="abe28-830">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="abe28-831">Con esta corrección, la plataforma de complementos de Office retrocede al nivel inferior de WebView en un entorno habilitado para WIP.</span><span class="sxs-lookup"><span data-stu-id="abe28-831">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="abe28-832">Según el entorno de máquina del cliente, esto puede ser Edge Spartan WebView o Trident WebView.</span><span class="sxs-lookup"><span data-stu-id="abe28-832">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="abe28-833">Las vistas previas de nivel inferior son compatibles con WIP.</span><span class="sxs-lookup"><span data-stu-id="abe28-833">Both down level WebViews support WIP.</span></span>



[//]: # (NO QUITAR NINGÚN DETALLE DE ERROR EN EL FINAL DEL CONTENIDO)

## <a name="version-2012-december-07"></a><span data-ttu-id="abe28-835">Versión 2012: 7 de diciembre</span><span class="sxs-lookup"><span data-stu-id="abe28-835">Version 2012: December 07</span></span>
<span data-ttu-id="abe28-836">*Versión 2012 (compilación 13530.20064)*</span><span class="sxs-lookup"><span data-stu-id="abe28-836">*Version 2012 (Build 13530.20064)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-838">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-838">Feature updates</span></span>

### <a name="teams"></a><span data-ttu-id="abe28-839">Teams</span><span class="sxs-lookup"><span data-stu-id="abe28-839">Teams</span></span>

- <span data-ttu-id="abe28-840">**Las notificaciones nativas de Windows ahora son compatibles con Teams:** ahora los usuarios pueden seleccionar su forma preferida de entrega de notificaciones, ya sea a través de banners integrados en Teams o banners nativos de Windows.</span><span class="sxs-lookup"><span data-stu-id="abe28-840">**Windows Native Notification are now Supported on Teams:** Users can now select their preferred means of notification delivery, either through Teams built-in banners or the Windows native banners.</span></span>


- <span data-ttu-id="abe28-841">**Vista de galería 2x2 de reuniones de Microsoft Teams en Citrix y VMware VDI:** la característica vista de galería de VDI 2x2 en Microsoft Teams permitirá ver hasta cuatro vídeos de asistentes en la vista de galería de 2x2 en clientes de VDI de Citrix, VMWare cuando el cliente de Microsoft Teams está en modo optimizado para VDI.</span><span class="sxs-lookup"><span data-stu-id="abe28-841">**Teams Meetings 2x2 Gallery View in Citrix and VMWare VDI:** Teams on VDI 2x2 Gallery View feature will enable to view up to four attendees videos in 2x2 Gallery View on VDI clients from Citrix, VMWare when Teams client in VDI optimized mode.</span></span>


- <span data-ttu-id="abe28-842">**Reacciones de la reunión:**  las reacciones de la reunión son una nueva forma de interactuar en las reuniones.</span><span class="sxs-lookup"><span data-stu-id="abe28-842">**Meeting Reactions:**  Meeting reactions are a new way to interact in meetings.</span></span> <span data-ttu-id="abe28-843">Los participantes pueden enviar reacciones que se muestran como un flujo en el contenido que se comparte y en la persona que envió la reacción si se muestra en la fase de reunión.</span><span class="sxs-lookup"><span data-stu-id="abe28-843">Participants can send reactions which are shown as a stream on content that is being shared, and on the individual who sent the reaction if they're displayed on the meeting stage.</span></span> 


- <span data-ttu-id="abe28-844">**Modo Juntos y Galería grande para reuniones web:** la galería grande permite ver los vídeos de hasta 49 otras personas a la vez.</span><span class="sxs-lookup"><span data-stu-id="abe28-844">**Together Mode and Large Gallery for Web Meetings** Large Gallery enables you to see the videos of up to 49 other people at once.</span></span> <span data-ttu-id="abe28-845">Esta opción está disponible cuando al menos diez personas tienen las cámaras activadas.</span><span class="sxs-lookup"><span data-stu-id="abe28-845">This option is available when at least ten people have their cameras turned on.</span></span> <span data-ttu-id="abe28-846">El modo Juntos le permite sentir que está en el mismo espacio compartido con todos los usuarios de la reunión.</span><span class="sxs-lookup"><span data-stu-id="abe28-846">Together mode lets you feel like you're in the same shared space with everyone in the meeting.</span></span> <span data-ttu-id="abe28-847">El modo Juntos está disponible cuando hay al menos cinco personas en la reunión.</span><span class="sxs-lookup"><span data-stu-id="abe28-847">Together mode is available when there are at least five people in the meeting.</span></span> 


- <span data-ttu-id="abe28-848">**Combinación de llamadas** la combinación de llamadas permite a los usuarios combinar una nueva llamada que realizan o una nueva llamada entrante en su llamada con otra persona o grupal.</span><span class="sxs-lookup"><span data-stu-id="abe28-848">**Call Merge** Call Merge allows users to merge a new call they place, or a new incoming call, into their 1-1 or group call.</span></span> <span data-ttu-id="abe28-849">Esto se aplica para las llamadas de VoIP de Teams y las llamadas de RTC.</span><span class="sxs-lookup"><span data-stu-id="abe28-849">This applies to Teams VOIP calls and PSTN calls.</span></span> 


### <a name="visio"></a><span data-ttu-id="abe28-850">Visio</span><span class="sxs-lookup"><span data-stu-id="abe28-850">Visio</span></span>

- <span data-ttu-id="abe28-851">**Nuevas galerías de símbolos y formas de Azure:** Hemos agregado muchas más galerías de símbolos para ayudarle a crear diagramas de Azure actualizados.</span><span class="sxs-lookup"><span data-stu-id="abe28-851">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="abe28-852">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-852">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-855">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-855">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-856">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-856">Excel</span></span>

- <span data-ttu-id="abe28-857">Hemos corregido un problema en el que algunos elementos de la cinta de opciones no se localizaban en chino simplificado.</span><span class="sxs-lookup"><span data-stu-id="abe28-857">We fixed an issue where some Ribbon elements were not localized in Simplified Chinese.</span></span>


- <span data-ttu-id="abe28-858">Hemos corregido un problema en el que Excel se terminaba inesperadamente durante la actualización.</span><span class="sxs-lookup"><span data-stu-id="abe28-858">We fixed an issue where Excel terminated unexpectedly when updating.</span></span>


- <span data-ttu-id="abe28-859">Hemos corregido un problema por el cual el comando Insertar objeto no muestra el icono correcto cuando se inserta un archivo desde la carpeta de sincronización local de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="abe28-859">We fixed an issue where the Insert Object command does not show the correct icon when inserting a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="abe28-860">Se ha corregido un problema por el que la edición en idiomas que requieren el uso del IME funcionaba mal al editar en el modo de sobrescritura.</span><span class="sxs-lookup"><span data-stu-id="abe28-860">Fixed an issue where editing in languages that require use of IME would behave poorly when editing in overwrite mode.</span></span>


- <span data-ttu-id="abe28-861">Se ha corregido un problema por el que algunos usuarios veían incorrectamente una barra de mensajes que les informaba de una nueva versión de un archivo durante la coautoría.</span><span class="sxs-lookup"><span data-stu-id="abe28-861">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="abe28-862">Se ha corregido un problema que provocaba que Excel se cerrase de forma inesperada al copiar y pegar datos en la vista Fórmula.</span><span class="sxs-lookup"><span data-stu-id="abe28-862">Fixed an issue where Excel would close unexpectedly when copying and pasting data in formula view.</span></span>


- <span data-ttu-id="abe28-863">Se ha corregido un hipervínculo roto a un artículo de ayuda en una alerta que aparecía al deshabilitar Autoguardado.</span><span class="sxs-lookup"><span data-stu-id="abe28-863">Fixed a broken hyperlink to a help article in an alert in case Autosave becomes disabled.</span></span>


- <span data-ttu-id="abe28-864">Se ha corregido un problema que causaba que Excel dejara de funcionar cuando se escribían datos en determinados lenguajes.</span><span class="sxs-lookup"><span data-stu-id="abe28-864">We fixed an issue where when entering data while Excel is running in certain languages could cause Excel to stop working.</span></span>


- <span data-ttu-id="abe28-865">Este cambio soluciona un problema que impedía mostrar correctamente fuentes en ecuaciones.</span><span class="sxs-lookup"><span data-stu-id="abe28-865">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="abe28-866">Corregido un problema por el que Power Pivot no importaba correctamente un archivo de texto delimitado por tabulaciones.</span><span class="sxs-lookup"><span data-stu-id="abe28-866">This fixes an issue where Power Pivot wasn't able to correctly import a tab-delimited text file.</span></span>


### <a name="outlook"></a><span data-ttu-id="abe28-867">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-867">Outlook</span></span>

- <span data-ttu-id="abe28-868">Hemos corregido un problema que provocaba que el campo Para: quedara en blanco en los informes de estado de la tarea.</span><span class="sxs-lookup"><span data-stu-id="abe28-868">We fixed an issue that caused the To: field to be blank in task status reports.</span></span>


- <span data-ttu-id="abe28-869">Se ha corregido un problema que provocaba que se interrumpiera el evento MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="abe28-869">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="abe28-870">Corregido un problema que provocaba que los usuarios experimentaran problemas al enviar correo de Outlook desde aplicaciones que no son Outlook.</span><span class="sxs-lookup"><span data-stu-id="abe28-870">We fixed an issue that was causing users to experience some issues when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="abe28-871">Se ha corregido un problema que provocaba que SmartLinks perdiera el formato cuando se guardaba en Borradores.</span><span class="sxs-lookup"><span data-stu-id="abe28-871">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="abe28-872">Corregido un problema en el que la adición de un archivo adjunto a un mensaje abierto desde un archivo zip fallaba.</span><span class="sxs-lookup"><span data-stu-id="abe28-872">We fixed and issue where adding an attachment to a message opened from a zip file would fail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="abe28-873">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-873">PowerPoint</span></span>

- <span data-ttu-id="abe28-874">Se ha corregido un problema relacionado con copiar o pegar una ecuación de Word a PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="abe28-874">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="abe28-875">Este cambio resuelve un problema relacionado con los tiempos de espera experimentados durante el análisis de entrada de lápiz.</span><span class="sxs-lookup"><span data-stu-id="abe28-875">This change addresses an issue related to timeouts experienced during ink analysis.</span></span>


- <span data-ttu-id="abe28-876">Este cambio corrige un error gramatical en la interfaz de usuario Crear un archivo GIF animado.</span><span class="sxs-lookup"><span data-stu-id="abe28-876">This change addresses a grammatical error in the Create an Animated GIF user interface.</span></span>


- <span data-ttu-id="abe28-877">Este cambio resuelve un problema con el relleno de rutas al aplicar las operaciones de Combinar formas con determinadas geometrías.</span><span class="sxs-lookup"><span data-stu-id="abe28-877">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="abe28-878">Este cambio soluciona un problema que impedía mostrar correctamente fuentes en ecuaciones.</span><span class="sxs-lookup"><span data-stu-id="abe28-878">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="abe28-879">Este cambio resuelve un problema con el control de errores que se pueden producir durante la carga de vídeo.</span><span class="sxs-lookup"><span data-stu-id="abe28-879">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="abe28-880">Hemos corregido un problema de VBA por el cual Slide.Shapes.AddMediaObject2 se bloqueaba con formatos de vídeo heredados (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="abe28-880">We fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="abe28-881">Se ha corregido un problema que evitaba que el indicador de presencia de un coautor desconocido no se actualizara por completo cuando había disponible más información sobre el coautor.</span><span class="sxs-lookup"><span data-stu-id="abe28-881">We fixed an issue where an unknown coauthor's presence indicator does not get completely refreshed when more information about the coauthor is available.</span></span>


- <span data-ttu-id="abe28-882">Se ha corregido un puntero nulo al cambiar el tamaño de la vista con la regla activada.</span><span class="sxs-lookup"><span data-stu-id="abe28-882">Fixed a null pointer being dereferenced when slide view is resized with ruler turned on.</span></span>


- <span data-ttu-id="abe28-883">Se ha corregido un problema que evitaba que algunos archivos de PowerPoint corruptos se abrieran correctamente, incluso después de la operación de reparación de un documento.</span><span class="sxs-lookup"><span data-stu-id="abe28-883">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="abe28-884">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-884">Project</span></span>

- <span data-ttu-id="abe28-885">Hemos corregido un problema por el cual los usuarios creaban proyectos que supuestamente se guardaban con información actualizada pero en los que no había ninguna actualización.</span><span class="sxs-lookup"><span data-stu-id="abe28-885">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


- <span data-ttu-id="abe28-886">Hemos corregido un problema por el cual no se podían eliminar las dependencias de las entregas si el sitio de SharePoint en el que estaba asociada la entrega ya no existía.</span><span class="sxs-lookup"><span data-stu-id="abe28-886">We fixed an issue where you couldn't delete dependencies on the deliverables if the SharePoint site the deliverable was associated with no longer existed.</span></span>


- <span data-ttu-id="abe28-887">Se ha corregido un problema que alargaba demasiado el tiempo de apertura de un proyecto con muchos recursos.</span><span class="sxs-lookup"><span data-stu-id="abe28-887">Fixed an issue where opening a project with a lot of resources was taking a long time.</span></span>


- <span data-ttu-id="abe28-888">Se ha corregido un problema en el que los usuarios pueden ver varias tareas no asignadas asociadas a una tarea.</span><span class="sxs-lookup"><span data-stu-id="abe28-888">Fixed an issue where users may see multiple unassigned assignments associated with a task.</span></span>


- <span data-ttu-id="abe28-889">Se ha corregido un problema en el que los proyectos de gran tamaño pueden tardar más en especificar un nombre de tarea.</span><span class="sxs-lookup"><span data-stu-id="abe28-889">Fixed an issue where in large projects it can be very slow to enter a task name.</span></span>


- <span data-ttu-id="abe28-890">Se ha corregido un problema por el que algunos proyectos específicos podrían abrirse si había un problema con el archivo del proyecto en una parte específica de la carga.</span><span class="sxs-lookup"><span data-stu-id="abe28-890">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="abe28-891">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-891">Word</span></span>

- <span data-ttu-id="abe28-892">A menudo, Pegar como texto sin formato tiene preferencia sobre Pegar como texto enriquecido.</span><span class="sxs-lookup"><span data-stu-id="abe28-892">Paste as plain text is often preferred to pasting as rich text.</span></span> <span data-ttu-id="abe28-893">La corrección de este menú contextual permite al usuario pegar como texto sin formato.</span><span class="sxs-lookup"><span data-stu-id="abe28-893">This context menu fix allows the user to paste as plain text.</span></span> <span data-ttu-id="abe28-894">De lo contrario, el usuario tendría que copiarlo en un editor de texto sin formato como el Bloc de notas y, luego, copiarlo de allí a la aplicación de destino deseada.</span><span class="sxs-lookup"><span data-stu-id="abe28-894">Else the user would have to copy into a plain-text editor like Notepad and then copy from Notepad into the desired target app</span></span>


- <span data-ttu-id="abe28-895">Se ha corregido un problema relacionado con copiar o pegar una ecuación de Word a PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="abe28-895">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="abe28-896">Este cambio resuelve un problema con el cursor al editar un documento.</span><span class="sxs-lookup"><span data-stu-id="abe28-896">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="abe28-897">Hemos corregido un problema relacionado con las imágenes difuminadas por usar el zoom.</span><span class="sxs-lookup"><span data-stu-id="abe28-897">We fixed an issue related to pictures becoming blurry while zooming.</span></span>


- <span data-ttu-id="abe28-898">Hemos corregido un problema por el cual se truncaban hipervínculos largos.</span><span class="sxs-lookup"><span data-stu-id="abe28-898">We fixed an issue where long hyperlinks were getting truncated.</span></span>


### <a name="office-suite"></a><span data-ttu-id="abe28-899">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-899">Office Suite</span></span>

- <span data-ttu-id="abe28-900">Corregido un problema en el Conjunto de aplicaciones de Office por el que la instalación de una versión más reciente de Office sobre algunas versiones anteriores podía resultar en un deterioro de la funcionalidad (por ejemplo, no poder usar Power Query) debido a que faltaban entradas del registro.</span><span class="sxs-lookup"><span data-stu-id="abe28-900">Office Suite Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2011-december-01"></a><span data-ttu-id="abe28-902">Versión 2011: 1 de diciembre</span><span class="sxs-lookup"><span data-stu-id="abe28-902">Version 2011: December 01</span></span>
<span data-ttu-id="abe28-903">*Versión 2011 (compilación 13426.20306)*</span><span class="sxs-lookup"><span data-stu-id="abe28-903">*Version 2011 (Build 13426.20306)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-905">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-905">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-906">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-906">Outlook</span></span>

- <span data-ttu-id="abe28-907">**Todas las reuniones en línea:** facilite la programación de reuniones en línea con una nueva configuración para que todas las reuniones sean en línea de forma predeterminada.</span><span class="sxs-lookup"><span data-stu-id="abe28-907">**Every meeting online:** Make it easier to schedule online meetings with a new setting to make all your meetings online by default.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-910">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-910">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-911">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-911">Outlook</span></span>

- <span data-ttu-id="abe28-912">Se ha corregido un problema que provocaba que los asistentes originales de algunas reuniones reciban una cancelación cuando otro asistente reenviaba la reunión.</span><span class="sxs-lookup"><span data-stu-id="abe28-912">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="abe28-913">Se ha corregido un problema que causaba que algunos usuarios no vieran ninguna firma en la lista desplegable a pesar de que se configuraron una o varias firmas.</span><span class="sxs-lookup"><span data-stu-id="abe28-913">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


### <a name="project"></a><span data-ttu-id="abe28-914">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-914">Project</span></span>

- <span data-ttu-id="abe28-915">Se ha corregido un problema por el que algunos proyectos específicos podrían abrirse si había un problema con el archivo del proyecto en una parte específica de la carga.</span><span class="sxs-lookup"><span data-stu-id="abe28-915">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2011-november-24"></a><span data-ttu-id="abe28-917">Versión 2011: 24 de noviembre</span><span class="sxs-lookup"><span data-stu-id="abe28-917">Version 2011: November 24</span></span>
<span data-ttu-id="abe28-918">*Versión 2011 (Compilación 13426.20294)*</span><span class="sxs-lookup"><span data-stu-id="abe28-918">*Version 2011 (Build 13426.20294)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-920">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-920">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="abe28-921">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-921">Office Suite</span></span>

- <span data-ttu-id="abe28-922">Se ha corregido un problema relacionado con copiar o pegar una ecuación de Word a PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="abe28-922">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2011-november-21"></a><span data-ttu-id="abe28-924">Versión 2011: 21 de noviembre</span><span class="sxs-lookup"><span data-stu-id="abe28-924">Version 2011: November 21</span></span>
<span data-ttu-id="abe28-925">*Versión 2011 (compilación 13426.20274)*</span><span class="sxs-lookup"><span data-stu-id="abe28-925">*Version 2011 (Build 13426.20274)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-927">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-927">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="abe28-928">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-928">PowerPoint</span></span>

- <span data-ttu-id="abe28-929">**Biblioteca de vídeos:** Mejore sus documentos con una biblioteca de videos editados y libres de royalties disponibles en la aplicación.</span><span class="sxs-lookup"><span data-stu-id="abe28-929">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-932">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-932">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-933">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-933">Outlook</span></span>

- <span data-ttu-id="abe28-934">Se ha corregido un problema que provocaba que se interrumpiera el evento MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="abe28-934">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="abe28-935">Se ha agregado una clave de registro que permite a los clientes deshabilitar la inclusión de hora de archivo para los datos adjuntos en las operaciones de IDataObject (es decir, arrastrar y soltar, portapapeles).</span><span class="sxs-lookup"><span data-stu-id="abe28-935">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span> <span data-ttu-id="abe28-936">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="abe28-936">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="abe28-937">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="abe28-937">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="abe28-938">0 = se excluyen filetimes.</span><span class="sxs-lookup"><span data-stu-id="abe28-938">0 = filetimes are excluded.</span></span> <span data-ttu-id="abe28-939">1 = (predeterminado) filetimes se incluyen</span><span class="sxs-lookup"><span data-stu-id="abe28-939">1 = (default) filetimes are included</span></span>


- <span data-ttu-id="abe28-940">Se ha corregido un problema por el que las imágenes en línea desaparecían al responder a un mensaje con una etiqueta de protección de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="abe28-940">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2011-november-18"></a><span data-ttu-id="abe28-942">Versión 2011: 18 de noviembre</span><span class="sxs-lookup"><span data-stu-id="abe28-942">Version 2011: November 18</span></span>
<span data-ttu-id="abe28-943">*Versión 2011 (compilación 13426.20250)*</span><span class="sxs-lookup"><span data-stu-id="abe28-943">*Version 2011 (Build 13426.20250)*</span></span>
* <span data-ttu-id="abe28-944">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="abe28-944">Various bugs and performance fixes.</span></span>

## <a name="version-2011-november-16"></a><span data-ttu-id="abe28-945">Versión 2011: 16 de noviembre</span><span class="sxs-lookup"><span data-stu-id="abe28-945">Version 2011: November 16</span></span>
<span data-ttu-id="abe28-946">*Versión 2011 (compilación 13426.20234)*</span><span class="sxs-lookup"><span data-stu-id="abe28-946">*Version 2011 (Build 13426.20234)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-948">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-948">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-949">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-949">Outlook</span></span>

- <span data-ttu-id="abe28-950">**Misma firma, todos los dispositivos:** su firma se almacena en la nube.</span><span class="sxs-lookup"><span data-stu-id="abe28-950">**Same signature, all devices:** Your signature is stored in the cloud.</span></span> <span data-ttu-id="abe28-951">Créelo una vez y úselo en cualquier lugar donde use Outlook.</span><span class="sxs-lookup"><span data-stu-id="abe28-951">Create it once and use it everywhere you use Outlook.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-954">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-954">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-955">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-955">Outlook</span></span>

- <span data-ttu-id="abe28-956">Se ha corregido un problema que provocaba que el campo Para quedara vacío al enviar un informe de estado en una tarea.</span><span class="sxs-lookup"><span data-stu-id="abe28-956">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="abe28-957">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-957">PowerPoint</span></span>

- <span data-ttu-id="abe28-958">Corregimos un problema de VBA por el que Slide.Shapes.AddMediaObject2 se bloqueaba con formatos de vídeo heredados (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="abe28-958">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2011-november-09"></a><span data-ttu-id="abe28-960">Versión 2011: 9 de noviembre</span><span class="sxs-lookup"><span data-stu-id="abe28-960">Version 2011: November 09</span></span>
<span data-ttu-id="abe28-961">*Versión 2011 (compilación 13426.20184)*</span><span class="sxs-lookup"><span data-stu-id="abe28-961">*Version 2011 (Build 13426.20184)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-963">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-963">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-964">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-964">Excel</span></span>

- <span data-ttu-id="abe28-965">**Crear flujos de datos de Power Platform a partir de consultas:** ahora puede exportar sus consultas a plantillas de Power Query que se pueden usar para crear nuevos flujos de datos de Power Platform.</span><span class="sxs-lookup"><span data-stu-id="abe28-965">**Create Power Platform dataflows from queries:** You can now export your queries into Power Query templates that can be used to create new Power Platform dataflows</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-968">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-968">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="abe28-969">Acceso</span><span class="sxs-lookup"><span data-stu-id="abe28-969">Access</span></span>

- <span data-ttu-id="abe28-970">Corregimos un problema por el que algunos usuarios veían el error "recurso del sistema excedido" al intentar exportar una consulta de su carpeta sincronizada de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="abe28-970">We fixed an issue where some users were seeing the "system resource exceeded" error when they tried to export a query from their synced OneDrive folder.</span></span>


- <span data-ttu-id="abe28-971">Corregimos un problema en el que el cambio automático entre las ventanas de la forma estaba cambiando a otra forma.</span><span class="sxs-lookup"><span data-stu-id="abe28-971">We fixed an issue where 'auto'-switching between form windows was switching to another form.</span></span>


- <span data-ttu-id="abe28-972">Se ha corregido un problema que provocaba que, al utilizar DAO desde aplicaciones que no son de Office, la aplicación se cerrara de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="abe28-972">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="excel"></a><span data-ttu-id="abe28-973">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-973">Excel</span></span>

- <span data-ttu-id="abe28-974">Se ha corregido un problema por el que el nombre de archivo no cambiaba después de una operación Guardar como con complementos COM habilitados.</span><span class="sxs-lookup"><span data-stu-id="abe28-974">We fixed an issue where Filename was not changing after a SaveAs operation with COM add-ins enabled.</span></span>


- <span data-ttu-id="abe28-975">Se ha corregido un problema con Power Pivot cuando usa una conexión en una base de datos de Oracle.</span><span class="sxs-lookup"><span data-stu-id="abe28-975">Fixed an issue with Power Pivot when using a connection to an Oracle database.</span></span>


- <span data-ttu-id="abe28-976">Se ha corregido un problema cuando se produce un error de Autoguardado con un mensaje de error incorrecto o engañoso cuando hay una definición de medida incorrecta en el modelo de datos de Excel.</span><span class="sxs-lookup"><span data-stu-id="abe28-976">We fixed an issue when Auto-Save fails with incorrect/misleading error message when there's a bad measure definition in the Excel data model.</span></span>


- <span data-ttu-id="abe28-977">Se corrigió un problema por el que Excel terminó de forma inesperada cuando se activó el proceso de calcular MTR y la actualización de objetos de directiva de grupo (por ejemplo, a través de la actualización remota de la directiva de grupo).</span><span class="sxs-lookup"><span data-stu-id="abe28-977">We fixed an issue where Excel terminated unexpectedly when the process of MTR calc and Group Policy Object update (e.g. via Remote Group Policy Refresh) was triggered.</span></span>


- <span data-ttu-id="abe28-978">Corregido un problema por el que un usuario no podía abrir el archivo de atomsvc (UTF8 + BOM) desde SharePoint directamente.</span><span class="sxs-lookup"><span data-stu-id="abe28-978">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="abe28-979">Se ha corregido un problema en el que al acercar y alejar el área de presentación se daba una separación entre el recuadro de selección ampliado y el puntero del mouse.</span><span class="sxs-lookup"><span data-stu-id="abe28-979">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="abe28-980">Corregido un problema en el que Word parecía bloquearse al insertar un libro de Excel en un documento de Word.</span><span class="sxs-lookup"><span data-stu-id="abe28-980">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


### <a name="outlook"></a><span data-ttu-id="abe28-981">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-981">Outlook</span></span>

- <span data-ttu-id="abe28-982">Resuelto un problema que hacía que Outlook dejara de funcionar esporádicamente al agregar o guardar datos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="abe28-982">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


- <span data-ttu-id="abe28-p158">Se ha corregido un problema por el que la impresión rápida de los datos adjuntos de imagen provocaba un error “Windows no puede encontrar esta imagen. Compruebe la ubicación y vuelva a intentarlo”.</span><span class="sxs-lookup"><span data-stu-id="abe28-p158">We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture. Check the location, and then try again".</span></span>


- <span data-ttu-id="abe28-985">Se corrigió un problema que hacía que algunos usuarios vieran que Outlook se iniciaba en un estado sin conexión hasta que optaban manualmente por trabajar en línea.</span><span class="sxs-lookup"><span data-stu-id="abe28-985">We fixed an issue that caused some users to see Outlook start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="abe28-986">Corregimos un problema al pegar una dirección URL copiada desde la ubicación de la reunión a otro lugar (como un explorador), la dirección URL contiene un punto y coma al final.</span><span class="sxs-lookup"><span data-stu-id="abe28-986">We fixed an issue when pasting a URL copied from meeting location to somewhere else (such as a browser), the URL contains a semicolon at the end.</span></span>


- <span data-ttu-id="abe28-987">Se ha corregido un problema que impedía a los usuarios eliminar citas en el Calendario de Grupos de Microsoft 365 en autenticación básica.</span><span class="sxs-lookup"><span data-stu-id="abe28-987">We fixed an issue where users were unable to delete appointments in Calendar of Microsoft 365 Groups in Basic Auth.</span></span>


- <span data-ttu-id="abe28-988">Se ha corregido un problema que producía errores en el inicio de Outlook durante la carga de la caché de sobrenombres.</span><span class="sxs-lookup"><span data-stu-id="abe28-988">We fixed an issue where starting Outlook failed while loading nickname cache.</span></span>


- <span data-ttu-id="abe28-989">Se ha corregido un problema por el que el propietario de un buzón no podía administrar el permiso compartido en su propio Calendario de Outlook, ya que la opción se había desactivado.</span><span class="sxs-lookup"><span data-stu-id="abe28-989">We fixed an issue where a mailbox owner wasn't able to manage Shared permission for their own Calendar as the option was greyed out.</span></span>


- <span data-ttu-id="abe28-990">Corregido un problema por el cual Outlook no podía crear un mensaje con permisos restringidos.</span><span class="sxs-lookup"><span data-stu-id="abe28-990">We fixed an issue where Outlook was not able to create a message with restricted permission.</span></span>


- <span data-ttu-id="abe28-991">Se ha corregido un problema por el cual al guardar las plantillas de correo electrónico como .OFT se cambiaban los caracteres chinos por signos de interrogación.</span><span class="sxs-lookup"><span data-stu-id="abe28-991">We fixed an issue where saving email templates as .OFT changed Chinese characters to question marks.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="abe28-992">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-992">PowerPoint</span></span>

- <span data-ttu-id="abe28-993">Se ha corregido un problema que provocaba que, al acercar y alejar el área de presentación, apareciera una separación entre el recuadro de selección ampliado y el puntero del mouse.</span><span class="sxs-lookup"><span data-stu-id="abe28-993">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="abe28-994">Se ha corregido un problema que provocaba que el icono del marcador de posición de contenido junto a Imágenes no incluyera información sobre herramientas.</span><span class="sxs-lookup"><span data-stu-id="abe28-994">We fixed an issue where in content placeholder icon next to Pictures didn't have a tooltip.</span></span>


- <span data-ttu-id="abe28-995">Se ha corregido un problema debido al cual la Vista protegida de presentación con diapositivas, mostrada en archivo PPTSX, permitía la captura de pantalla de documentos protegidos por IRM.</span><span class="sxs-lookup"><span data-stu-id="abe28-995">We have fixed an issue where Protected view of slide show, shown by pptsx file, allows screen capture of IRM protected document.</span></span>


- <span data-ttu-id="abe28-996">Se ha corregido un problema por el cual las líneas de cuadrícula se desplazaban de las diapositivas al cerrar el panel Diseño.</span><span class="sxs-lookup"><span data-stu-id="abe28-996">We fixed an issue where grid lines were getting shifted from slides when closing design pane.</span></span>


- <span data-ttu-id="abe28-997">Corregimos un problema al duplicar la presentación con diapositivas en un monitor secundario, la presentación puede ocultarse detrás de la otra ventana.</span><span class="sxs-lookup"><span data-stu-id="abe28-997">We fixed an issue when duplicating slideshow to secondary monitor, the slideshow may hide behind other window.</span></span>


- <span data-ttu-id="abe28-998">Se ha corregido un problema por el que la barra de desplazamiento en la diapositiva comienza a ajustarse a sí misma después de detener la grabación de pantalla con el panel de selección abierto.</span><span class="sxs-lookup"><span data-stu-id="abe28-998">We fixed an issue where the scroll bar in the slide starts adjusting itself after stopping screen recording with selection pane opened.</span></span>


### <a name="project"></a><span data-ttu-id="abe28-999">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-999">Project</span></span>

- <span data-ttu-id="abe28-1000">Se ha corregido un problema por el que la NewVal en el evento ProjectBeforeTaskChagne no tiene el valor correcto si se cambia un retraso en una vista de tipo de formulario de tarea.</span><span class="sxs-lookup"><span data-stu-id="abe28-1000">Fixed an issue where the NewVal in the ProjectBeforeTaskChagne event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="abe28-1001">Corregimos un problema por el que el Proyecto puede finalizar inesperadamente al abrir archivos en los que se especificaban los contornos de los recursos de una determinada manera.</span><span class="sxs-lookup"><span data-stu-id="abe28-1001">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="abe28-1002">Se ha corregido un problema que provocaba que, al guardar un proyecto desde PWA en un archivo MPP local, ProjectBeforeTaskChangeEvent se desencadenara para datos no modificados por el usuario.</span><span class="sxs-lookup"><span data-stu-id="abe28-1002">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="abe28-1003">Se ha corregido un problema en el que las negociaciones de recursos buscaban un recurso por nombre en lugar de un GUID, lo que causaba problemas si había varios recursos con el mismo nombre.</span><span class="sxs-lookup"><span data-stu-id="abe28-1003">Fixed an issue where resource engagements searched for a resource by name instead of GUID which would cause issues if there were multiple resources with the same name.</span></span>


- <span data-ttu-id="abe28-1004">Se ha corregido un problema que hace que si tiene una lista de tareas en un sitio de proyecto y agrupa la lista de tareas, no pueda editar rápidamente la lista de tareas.</span><span class="sxs-lookup"><span data-stu-id="abe28-1004">Fixed an issue where if you have a task list in a project site and group the task list, you will not be able to quick edit the task list.</span></span>


- <span data-ttu-id="abe28-1005">Se ha corregido un problema que hace que si actualiza un recurso de empresa a través del CSOM, puede perderse la capacidad máxima del recurso.</span><span class="sxs-lookup"><span data-stu-id="abe28-1005">Fixed an issue where if you update an enterprise resource via CSOM, resource max units may be lost.</span></span>


### <a name="word"></a><span data-ttu-id="abe28-1006">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1006">Word</span></span>

- <span data-ttu-id="abe28-1007">Se ha corregido un problema en el que al acercar y alejar el área de presentación se daba una separación entre el recuadro de selección ampliado y el puntero del mouse.</span><span class="sxs-lookup"><span data-stu-id="abe28-1007">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="abe28-1008">Se ha corregido un problema por el que al hacer clic en la sugerencia de comentario no se mostraba la tarjeta comentario en la vista.</span><span class="sxs-lookup"><span data-stu-id="abe28-1008">We fixed an issue where clicking comment hint didn't zoom out to show comment card in view.</span></span>


- <span data-ttu-id="abe28-1009">Corregido un problema de diseño en el que la línea entre columnas podía cambiar.</span><span class="sxs-lookup"><span data-stu-id="abe28-1009">We fixed a layout issue which the line between columns might have shifted.</span></span>


- <span data-ttu-id="abe28-1010">Corregimos un problema en Control de cambios por el que a veces se podía mostrar un mensaje de error al abrir un documento de Word.</span><span class="sxs-lookup"><span data-stu-id="abe28-1010">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="abe28-1011">Corregido un problema en el que Word parecía bloquearse al insertar un libro de Excel en un documento de Word.</span><span class="sxs-lookup"><span data-stu-id="abe28-1011">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


- <span data-ttu-id="abe28-1012">Corregimos un problema de impresión cuando se aplica la etiqueta de carácter con marcas de agua.</span><span class="sxs-lookup"><span data-stu-id="abe28-1012">We fixed a print issue when sensitivity label with watermarks are applied.</span></span>


### <a name="office-suite"></a><span data-ttu-id="abe28-1013">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-1013">Office Suite</span></span>

- <span data-ttu-id="abe28-1014">Se ha corregido un problema en la Herramienta de implementación de Office que provocaba errores en la configuración al usar la característica RemoveMSI con el producto de Office 2007 "Informes de errores de aplicaciones de Microsoft".</span><span class="sxs-lookup"><span data-stu-id="abe28-1014">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="abe28-1015">Se ha corregido un problema por el que el inicio de sesión interactivo de la API de SSO devuelve un código de error.</span><span class="sxs-lookup"><span data-stu-id="abe28-1015">We fixed an issue where SSO API interactive Sign-In was returning an error code.</span></span>



[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2010-november-06"></a><span data-ttu-id="abe28-1017">Versión 2010: 6 de noviembre</span><span class="sxs-lookup"><span data-stu-id="abe28-1017">Version 2010: November 06</span></span>
<span data-ttu-id="abe28-1018">*Versión 2010 (compilación 13328.20356)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1018">*Version 2010 (Build 13328.20356)*</span></span>
* <span data-ttu-id="abe28-1019">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="abe28-1019">Various bugs and performance fixes.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)



[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

## <a name="version-2010-november-04"></a><span data-ttu-id="abe28-1022">Versión 2010: 4 de noviembre</span><span class="sxs-lookup"><span data-stu-id="abe28-1022">Version 2010: November 04</span></span>
<span data-ttu-id="abe28-1023">*Versión 2010 (compilación 13328.20340)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1023">*Version 2010 (Build 13328.20340)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1025">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1025">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-1026">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1026">Excel</span></span>

- <span data-ttu-id="abe28-1027">**Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="abe28-1027">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="abe28-1028">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1028">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a><span data-ttu-id="abe28-1029">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1029">Outlook</span></span>

- <span data-ttu-id="abe28-1030">**Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="abe28-1030">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="abe28-1031">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1031">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a><span data-ttu-id="abe28-1032">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1032">PowerPoint</span></span>

- <span data-ttu-id="abe28-1033">**Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="abe28-1033">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="abe28-1034">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1034">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="abe28-1035">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/svg-content-office-third-party-apps)</span><span class="sxs-lookup"><span data-stu-id="abe28-1035">See details in [blog post](https://insider.office.com/es-ES/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="abe28-1036">**Crear GIF con fondos transparentes:** cuando se exporta a un GIF animado, una nueva opción permite que el fondo sea transparente.</span><span class="sxs-lookup"><span data-stu-id="abe28-1036">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span><br /><span data-ttu-id="abe28-1037">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/export-animated-gifs-transparent-backgrounds)</span><span class="sxs-lookup"><span data-stu-id="abe28-1037">See details in [blog post](https://insider.office.com/es-ES/blog/export-animated-gifs-transparent-backgrounds)</span></span>

- <span data-ttu-id="abe28-1038">**Exportar GIF animado en un rango:** seleccione un intervalo de diapositivas cuando exporte a GIF animado</span><span class="sxs-lookup"><span data-stu-id="abe28-1038">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

### <a name="word"></a><span data-ttu-id="abe28-1039">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1039">Word</span></span>

- <span data-ttu-id="abe28-1040">**Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="abe28-1040">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="abe28-1041">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1041">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1044">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1044">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-1045">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1045">Outlook</span></span>

- <span data-ttu-id="abe28-1046">Se ha corregido un problema que provocaba que los usuarios no puedan conceder permisos de editor a los delegados.</span><span class="sxs-lookup"><span data-stu-id="abe28-1046">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


### <a name="office-suite"></a><span data-ttu-id="abe28-1047">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-1047">Office Suite</span></span>

- <span data-ttu-id="abe28-1048">Se ha corregido un problema que provocaba un error al intentar guardar archivos que habían pasado de sincronizados a solo en el servidor.</span><span class="sxs-lookup"><span data-stu-id="abe28-1048">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL FIN DE CONTENIDO)

## <a name="version-2010-october-27"></a><span data-ttu-id="abe28-1050">Versión 2010: 27 de octubre</span><span class="sxs-lookup"><span data-stu-id="abe28-1050">Version 2010: October 27</span></span>
<span data-ttu-id="abe28-1051">*Versión 2010 (compilación 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1051">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1055">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1055">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-1056">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1056">Outlook</span></span>

- <span data-ttu-id="abe28-1057">Se ha corregido un problema que, de forma predeterminada, impedía que se activara la configuración de la nube para los usuarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-1057">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="abe28-1058">Se ha corregido un problema que impedía guardar los cambios que se realizaran a la firma de un usuario.</span><span class="sxs-lookup"><span data-stu-id="abe28-1058">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL FIN DE CONTENIDO)

## <a name="version-2010-october-24"></a><span data-ttu-id="abe28-1060">Versión 2010: 24 de octubre</span><span class="sxs-lookup"><span data-stu-id="abe28-1060">Version 2010: October 24</span></span>
<span data-ttu-id="abe28-1061">*Versión 2010 (compilación 13328.20278)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1061">*Version 2010 (Build 13328.20278)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)



[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1065">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1065">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-1066">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1066">Outlook</span></span>

- <span data-ttu-id="abe28-1067">Se ha corregido un problema que provocaba que los encabezados de mensajes en chino no se pudieran leer al responder o reenviar.</span><span class="sxs-lookup"><span data-stu-id="abe28-1067">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="abe28-1068">Se ha corregido un problema que provocaba que los caracteres chinos se cambiaran a signos de interrogación al guardar como archivo .oft.</span><span class="sxs-lookup"><span data-stu-id="abe28-1068">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="project"></a><span data-ttu-id="abe28-1069">Proyecto</span><span class="sxs-lookup"><span data-stu-id="abe28-1069">Project</span></span>

- <span data-ttu-id="abe28-1070">Se ha corregido un problema que provocaba que, al guardar un proyecto desde PWA en un archivo MPP local, ProjectBeforeTaskChangeEvent se desencadenara para datos no modificados por el usuario.</span><span class="sxs-lookup"><span data-stu-id="abe28-1070">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="abe28-1071">Se ha corregido un problema que causaba que NewVal en el evento ProjectBeforeTaskChange no tuviera el valor correcto si se cambiaba un retraso en una vista de tipo de formulario de tarea.</span><span class="sxs-lookup"><span data-stu-id="abe28-1071">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL FIN DE CONTENIDO)

## <a name="version-2010-october-19"></a><span data-ttu-id="abe28-1073">Versión 2010: 19 de octubre</span><span class="sxs-lookup"><span data-stu-id="abe28-1073">Version 2010: October 19</span></span>
<span data-ttu-id="abe28-1074">*Versión 2010 (compilación 13328.20210)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1074">*Version 2010 (Build 13328.20210)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1076">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1076">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-1077">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1077">Outlook</span></span>

- <span data-ttu-id="abe28-1078">**Ahorre tiempo mientras redacta mensajes:** Outlook le muestra sugerencias de escritura que le ayudarán a redactar mensajes de manera rápida.</span><span class="sxs-lookup"><span data-stu-id="abe28-1078">**Save time while composing messages:** Outlook shows you writing suggestions that help you compose messages quickly.</span></span> <span data-ttu-id="abe28-1079">Para aceptar la sugerencia, solo tiene que usar la tecla TAB.</span><span class="sxs-lookup"><span data-stu-id="abe28-1079">To accept the suggestion, just use the Tab key.</span></span><br /><span data-ttu-id="abe28-1080">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/text-predictions-in-word-outlook)</span><span class="sxs-lookup"><span data-stu-id="abe28-1080">See details in [blog post](https://insider.office.com/es-ES/blog/text-predictions-in-word-outlook)</span></span>

- <span data-ttu-id="abe28-1081">**Rompa la barrera del idioma con un traductor incorporado:** Los complementos para la traducción ya no son necesarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-1081">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="abe28-1082">En un mensaje, haga clic con el botón derecho para traducir palabras o frases específicas, o todo el mensaje.</span><span class="sxs-lookup"><span data-stu-id="abe28-1082">In a message, right-click to translate specific words, phrases, or the whole message.</span></span> [<span data-ttu-id="abe28-1083">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1083">Learn more</span></span>](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

- <span data-ttu-id="abe28-1084">**Actualizaciones de la experiencia de usuario en Tareas:** Una actualización visual de los elementos de las tareas</span><span class="sxs-lookup"><span data-stu-id="abe28-1084">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

### <a name="powerpoint"></a><span data-ttu-id="abe28-1085">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1085">PowerPoint</span></span>

- <span data-ttu-id="abe28-1086">**Practique la presentación con el Asesor para moderadores:** Obtenga asesoramiento sobre las cosas que ayudan a mantener a la audiencia comprometida, como el ritmo, el uso excesivo de palabras, el lenguaje corporal y más.</span><span class="sxs-lookup"><span data-stu-id="abe28-1086">**Practice your presentation with Presenter Coach:** Get coaching on the things that help keep an audience engaged — like pacing, overused words, body language, and more.</span></span> [<span data-ttu-id="abe28-1087">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1087">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

### <a name="word"></a><span data-ttu-id="abe28-1088">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1088">Word</span></span>

- <span data-ttu-id="abe28-1089">**El panel del Editor Microsoft recibe una actualización en la versión de escritorio de Word:** Hemos actualizado la experiencia actual con el panel del Editor para los clientes de escritorio de Word.</span><span class="sxs-lookup"><span data-stu-id="abe28-1089">**Microsoft Editor pane gets an update in Word for desktop:** We have upgraded the current experience with the Editor pane in Word for desktop clients.</span></span>

- <span data-ttu-id="abe28-1090">**Sugerencias de escritura con un solo clic:** Aplique sugerencias de escritura con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="abe28-1090">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="abe28-1091">El panel del Editor actualizado facilita la navegación entre sugerencias.</span><span class="sxs-lookup"><span data-stu-id="abe28-1091">The updated Editor pane makes it easy to navigate between suggestions.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1094">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1094">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="abe28-1095">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1095">PowerPoint</span></span>

- <span data-ttu-id="abe28-1096">Esta es una solución para un problema por el que se muestra la solicitud de guardar en un bucle al cerrar el documento cuando hay un complemento que escucha al evento PresentationBeforeClose y comprueba la propiedad Presentation.Saved como parte del controlador de eventos.</span><span class="sxs-lookup"><span data-stu-id="abe28-1096">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL FIN DE CONTENIDO)

## <a name="version-2010-october-11"></a><span data-ttu-id="abe28-1098">Versión 2010: 11 de octubre</span><span class="sxs-lookup"><span data-stu-id="abe28-1098">Version 2010: October 11</span></span>
<span data-ttu-id="abe28-1099">*Versión 2010 (compilación 13328.20154)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1099">*Version 2010 (Build 13328.20154)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1101">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1101">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-1102">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1102">Excel</span></span>

- <span data-ttu-id="abe28-1103">**Ayude a proteger sus datos de archivos malintencionados:** Protección de aplicaciones le ayuda a protegerse contra el malware permitiéndole leer, imprimir y guardar los archivos de Office en un recipiente aislado.</span><span class="sxs-lookup"><span data-stu-id="abe28-1103">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="abe28-1104">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1104">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="powerpoint"></a><span data-ttu-id="abe28-1105">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1105">PowerPoint</span></span>

- <span data-ttu-id="abe28-1106">**Ayude a proteger sus datos de archivos malintencionados:** Protección de aplicaciones le ayuda a protegerse contra el malware permitiéndole leer, imprimir y guardar los archivos de Office en un recipiente aislado.</span><span class="sxs-lookup"><span data-stu-id="abe28-1106">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="abe28-1107">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1107">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="word"></a><span data-ttu-id="abe28-1108">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1108">Word</span></span>

- <span data-ttu-id="abe28-1109">**Ayude a proteger sus datos de archivos malintencionados:** Protección de aplicaciones le ayuda a protegerse contra el malware permitiéndole leer, imprimir y guardar los archivos de Office en un recipiente aislado.</span><span class="sxs-lookup"><span data-stu-id="abe28-1109">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="abe28-1110">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1110">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1113">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1113">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="abe28-1114">Access</span><span class="sxs-lookup"><span data-stu-id="abe28-1114">Access</span></span>

- <span data-ttu-id="abe28-1115">Se ha corregido un problema que provocaba que la posición de la barra de desplazamiento no se estableciera de manera correcta al cargar la ventana de consulta o relación guardada mientras se realizaba el desplazamiento.</span><span class="sxs-lookup"><span data-stu-id="abe28-1115">We fixed an issue where scrollbar position was not set correctly when loading query/relationship window saved while scrolled.</span></span>


- <span data-ttu-id="abe28-1116">Se ha corregido un problema que provocaba que el panel de tareas de Agregar tabla no mostrara de manera correcta los nombres que contenían "&".</span><span class="sxs-lookup"><span data-stu-id="abe28-1116">We fixed an issue where Add Table Task Pane was not displaying names containing '&' correctly.</span></span>


### <a name="excel"></a><span data-ttu-id="abe28-1117">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1117">Excel</span></span>

- <span data-ttu-id="abe28-1118">Se ha corregido un problema que provocaba que el intervalo manual de categoría multinivel no funcionara en los gráficos.</span><span class="sxs-lookup"><span data-stu-id="abe28-1118">We fixed an issue where multi-level category manual interval was not working in charts.</span></span>


- <span data-ttu-id="abe28-1119">Se ha corregido un problema con los gráficos de mapas 2D que provocaba que el uso de VBA para establecer los colores de los valores max, mid y min para una serie no funcione.</span><span class="sxs-lookup"><span data-stu-id="abe28-1119">Fixed an issue with 2D Map Charts where using VBA to set the colors for the max, mid, and min values for a series was not working.</span></span>


- <span data-ttu-id="abe28-1120">Se ha corregido un problema por el que Excel indicaba por error que se había quedado sin recursos al intentar calcular una o varias fórmulas.</span><span class="sxs-lookup"><span data-stu-id="abe28-1120">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="abe28-1121">Se ha corregido un problema que aparecía cuando se configuraba el idioma de Office en español. Este problema provocaba que las listas de validación de datos puedan no mostrar todos los elementos de la lista.</span><span class="sxs-lookup"><span data-stu-id="abe28-1121">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="abe28-1122">Se ha corregido un problema que provocaba un retraso considerable al cambiar entre hojas de cálculo con grandes cantidades de datos cuando la 'Vista previa de salto de página' estaba habilitada.</span><span class="sxs-lookup"><span data-stu-id="abe28-1122">Fixed an issue where there could be a noticeable delay when switching between worksheets with large amounts of data when 'Page Break Preview' was enabled.</span></span>


- <span data-ttu-id="abe28-1123">Se ha corregido un problema que hacía que no se actualizaran las opciones de todas las hojas del libro al agregar una tabla usada para la validación de datos.</span><span class="sxs-lookup"><span data-stu-id="abe28-1123">We fixed an issue where adding to a table used for Data Validation did not update options for all sheets in the workbook.</span></span>


- <span data-ttu-id="abe28-1124">Se ha corregido un problema que podía producir un bloqueo al actualizar las tablas dinámicas de OLAP.</span><span class="sxs-lookup"><span data-stu-id="abe28-1124">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="abe28-1125">Se ha corregido un problema que hacía que ChartSheet se bloqueara en ciertos casos cuando se insertaba una fórmula en la barra de fórmulas.</span><span class="sxs-lookup"><span data-stu-id="abe28-1125">Fixed an issue where ChartSheet crashed in some cases when a formula is entered through formula bar.</span></span>


- <span data-ttu-id="abe28-1126">Se corrigió un problema por el cual la barra de fórmulas de Excel no se mostraba completamente después de que se perdiera la conexión a un dispositivo, como una conexión o desconexión de sesión remota o un cambio de monitor.</span><span class="sxs-lookup"><span data-stu-id="abe28-1126">We fixed an issue where the Excel formula bar would not render completely after connection to a device was lost, such as a remote session connect/disconnect or a monitor change.</span></span>


### <a name="onenote"></a><span data-ttu-id="abe28-1127">OneNote</span><span class="sxs-lookup"><span data-stu-id="abe28-1127">OneNote</span></span>

- <span data-ttu-id="abe28-1128">Se ha corregido un problema que impedía al usuario seleccionar y copiar la dirección URL del bloc de notas del cuadro de texto en un archivo de OutSpace > Información.</span><span class="sxs-lookup"><span data-stu-id="abe28-1128">We fixed an issue where a user was unable to select and copy notebook URL from textbox in OutSpace File > Info.</span></span>


- <span data-ttu-id="abe28-1129">Se ha corregido un problema que hacía que, al pasar el ratón sobre el color verde en el selector de colores del bloc de notas, el elemento emergente indicara "red chalk" (tiza roja).</span><span class="sxs-lookup"><span data-stu-id="abe28-1129">We fixed an issue when you hover over green color in notebook color selector, the pop up reads "red chalk".</span></span>


- <span data-ttu-id="abe28-1130">Se ha corregido un problema que hacía que OneNote no respetara los colores de contraste alto en el lienzo para temas personalizados.</span><span class="sxs-lookup"><span data-stu-id="abe28-1130">We fixed an issue where OneNote didn't honor High Contrast colors in the canvas for custom themes.</span></span>


### <a name="outlook"></a><span data-ttu-id="abe28-1131">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1131">Outlook</span></span>

- <span data-ttu-id="abe28-1132">Corrige un problema que causaba el envío de los mensajes de correo electrónico generados automáticamente con el cuerpo del correo en blanco cuando el asunto estaba vacío.</span><span class="sxs-lookup"><span data-stu-id="abe28-1132">Addresses an issue that caused automatically generated emails to be sent with a blank body when the subject is blank.</span></span>


- <span data-ttu-id="abe28-1133">Se ha corregido un problema que provocaba que se almacenara en caché para carpetas el GUID de carpeta incorrecto.</span><span class="sxs-lookup"><span data-stu-id="abe28-1133">We fixed an issue where the wrong folder guid is cached for folders.</span></span>


- <span data-ttu-id="abe28-1134">Cuando un usuario copia y pega una dirección de correo electrónico en el campo del destinatario con el nombre para mostrar, la dirección de correo electrónico no siempre se analizaba de forma correcta, y esto generaba que aparezca una advertencia sobre una dirección de correo electrónico no válida.</span><span class="sxs-lookup"><span data-stu-id="abe28-1134">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="abe28-1135">Se ha corregido y, por tanto, el nombre y la dirección de correo electrónico se analizan de forma correcta para que ya no se muestre la advertencia.</span><span class="sxs-lookup"><span data-stu-id="abe28-1135">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


- <span data-ttu-id="abe28-1136">Se ha corregido un problema que causaba que las carpetas compartidas en línea no devolvieran el nombre de la carpeta principal.</span><span class="sxs-lookup"><span data-stu-id="abe28-1136">We fixed an issue where online shared folders did not return parent folder name.</span></span> <span data-ttu-id="abe28-1137">En lugar de dar error, devolvía una ruta de acceso vacía que pasaba incorrectamente a la cuenta principal.</span><span class="sxs-lookup"><span data-stu-id="abe28-1137">Intsead of failing, it returned an empty path which incorrectly went to the primary account.</span></span>


- <span data-ttu-id="abe28-1138">Se ha corregido un problema que impedía que la opción Guardar como estuviera disponible para los datos adjuntos clásicos.</span><span class="sxs-lookup"><span data-stu-id="abe28-1138">We fixed an issue where the Save As option was not available for classic attachments.</span></span>


- <span data-ttu-id="abe28-1139">Se ha corregido un problema para ofrecer a los usuarios una forma de personalizar el texto de justificación al anular una directiva.</span><span class="sxs-lookup"><span data-stu-id="abe28-1139">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="abe28-1140">Se ha corregido un problema que hacía que se activara el control de cambios después de reabrir el borrador desde el panel de vista previa de solo lectura.</span><span class="sxs-lookup"><span data-stu-id="abe28-1140">We fixed an issue where track changes turned on after reopening draft from read-only preview pane.</span></span>


- <span data-ttu-id="abe28-1141">Se ha corregido un problema que hacía que los correos electrónicos se ocultaran después de desactivar la Bandeja de entrada Prioritarios y ordenarlos.</span><span class="sxs-lookup"><span data-stu-id="abe28-1141">We fixed an issue with emails being hidden after turning Focused Inbox off and doing a sort.</span></span>


- <span data-ttu-id="abe28-1142">Se ha corregido un problema que hacía que Outlook creara una segunda firma vacía para las personas con la configuración de la nube habilitada.</span><span class="sxs-lookup"><span data-stu-id="abe28-1142">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="abe28-1143">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1143">PowerPoint</span></span>

- <span data-ttu-id="abe28-1144">Se ha corregido un problema que impedía a PowerPoint exportar las viñetas rectangulares al exportar a PDF.</span><span class="sxs-lookup"><span data-stu-id="abe28-1144">We fixed an issue where PowerPoint was not exporting rectangle bullet points while exporting to PDF.</span></span>


- <span data-ttu-id="abe28-1145">Se ha corregido un problema que hacía que los GIF solo mostraran la animación una vez en el editor y en las presentaciones.</span><span class="sxs-lookup"><span data-stu-id="abe28-1145">We fixed an issue where GIF's would animate only once in the editor and slide shows.</span></span>


- <span data-ttu-id="abe28-1146">Se ha corregido un problema que hacía que el gráfico de Excel vinculado cambiara incorrectamente a la hoja de Excel cuando el usuario cambiaba la ruta de origen a la carpeta de OneDrive local.</span><span class="sxs-lookup"><span data-stu-id="abe28-1146">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="abe28-1147">Se ha corregido un problema debido al cual, si se encuentra en la última diapositiva y pasa a la siguiente diapositiva tras pulsar "Finalizar sesión" y antes de que aparezca el resumen, el cuadro de diálogo de sesión final también aparece visible en la página de resumen.</span><span class="sxs-lookup"><span data-stu-id="abe28-1147">We fixed an issue that If you are on the last slide and if you swipe to the next slide after pressing 'End Session' and before the summary shows up, the End-Session dialog is visible on the summary page as well.</span></span>


### <a name="project"></a><span data-ttu-id="abe28-1148">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-1148">Project</span></span>

- <span data-ttu-id="abe28-1149">Se ha corregido un problema que puede hacer que el método VBA ConsolidateProjects produzca errores si se intenta agregar el mismo proyecto varias veces y AttachToSources está establecido en false.</span><span class="sxs-lookup"><span data-stu-id="abe28-1149">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="abe28-1150">Se ha corregido un problema por el que si se ejecuta un código de evento y se intenta realizar cambios desde la vista del Formulario de tareas, es posible que el botón Aceptar no confirme los cambios.</span><span class="sxs-lookup"><span data-stu-id="abe28-1150">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="abe28-1151">Se ha corregido un problema que puede hacer que el método VBA ConsolidateProjects produzca errores si se intenta agregar el mismo proyecto varias veces y AttachToSources está establecido en false.</span><span class="sxs-lookup"><span data-stu-id="abe28-1151">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="abe28-1152">Se ha corregido un problema debido al cual, si tiene campos personalizados con fórmulas que usan el valor acumulado, puede que observe que el rendimiento retrasa el cambio de vistas y la apertura de los detalles del proyecto/tarea.</span><span class="sxs-lookup"><span data-stu-id="abe28-1152">Fixed an issue where if you have custom fields with formulas and are using earned value, you may notice performance delays switching views and opening project/task details.</span></span>


- <span data-ttu-id="abe28-1153">Se ha corregido un problema que podía hacer que Project se bloqueara si aplicaba un grupo en la Vista de hoja o de uso de recursos y, a continuación, insertaba una columna.</span><span class="sxs-lookup"><span data-stu-id="abe28-1153">Fixed an issue where Project may crash if you apply a group by to the Resource Usage or Sheet view and then insert a column.</span></span>


### <a name="word"></a><span data-ttu-id="abe28-1154">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1154">Word</span></span>

- <span data-ttu-id="abe28-1155">Se ha corregido un problema que provocaba que los vínculos a los archivos habilitados de flujo de trabajo no se abrieran con normalidad.</span><span class="sxs-lookup"><span data-stu-id="abe28-1155">We fixed an issue where links to workflow enabled files were not opening as expected.</span></span>


- <span data-ttu-id="abe28-1156">Se ha corregido un problema que provocaba que el hecho que un usuario seleccionara una marca de revisión (inserción o eliminación) mostrara un comentario emergente.</span><span class="sxs-lookup"><span data-stu-id="abe28-1156">Fixed an issue where a user tapping on a tracked change (insertion/deletion) would bring up a comment pop-out.</span></span>


- <span data-ttu-id="abe28-1157">Se ha corregido un problema al eliminar llamadas de comentario en Word.</span><span class="sxs-lookup"><span data-stu-id="abe28-1157">We fixed an issue with deleting comment callouts in Word.</span></span>


- <span data-ttu-id="abe28-1158">Se ha corregido un problema con Outlook al establecer un mensaje en No reenviar</span><span class="sxs-lookup"><span data-stu-id="abe28-1158">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="abe28-1159">Se ha corregido un problema al guardar un documento de Word que contenía cita y ecuación.</span><span class="sxs-lookup"><span data-stu-id="abe28-1159">We fixed an issue with saving Word document that contains citation and equation.</span></span>


- <span data-ttu-id="abe28-1160">Se ha corregido un problema con el cuadro de diálogo Galería de estilos.</span><span class="sxs-lookup"><span data-stu-id="abe28-1160">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="abe28-1161">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-1161">Office Suite</span></span>

- <span data-ttu-id="abe28-p172">Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan tóners. Cambiar mensaje para mostrar "tóner/tinta bajos" & "no tóner/tinta".</span><span class="sxs-lookup"><span data-stu-id="abe28-p172">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2009-october-07"></a><span data-ttu-id="abe28-1165">Versión 2009: 7 de agosto</span><span class="sxs-lookup"><span data-stu-id="abe28-1165">Version 2009: October 07</span></span>
<span data-ttu-id="abe28-1166">*Versión 2009 (Compilación 13231.20360)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1166">*Version 2009 (Build 13231.20360)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1168">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1168">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-1169">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1169">Excel</span></span>

- <span data-ttu-id="abe28-1170">**Crear tipos de datos con Power Query:** crear tipos de datos enriquecidos con Power Query desde cualquier origen de datos</span><span class="sxs-lookup"><span data-stu-id="abe28-1170">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-1171">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1171">Outlook</span></span>

- <span data-ttu-id="abe28-1172">**La revisión gramatical se ha vuelto:** Outlook marca los errores gramaticales mientras escribe, por lo que puede aplicar sugerencias con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="abe28-1172">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> <br /><span data-ttu-id="abe28-1173">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/grammar-and-style-suggestions-available-in-outlook)</span><span class="sxs-lookup"><span data-stu-id="abe28-1173">See details in [blog post](https://insider.office.com/es-ES/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1176">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1176">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-1177">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1177">Outlook</span></span>

- <span data-ttu-id="abe28-1178">Corrige un problema que provocaba que la búsqueda no devuelve ningún resultado al buscar en los calendarios compartidos sin almacenamiento en caché.</span><span class="sxs-lookup"><span data-stu-id="abe28-1178">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="abe28-1179">Corrige un problema que causaba que algunos usuarios observaban Outlook de forma inesperada en un estado sin conexión.</span><span class="sxs-lookup"><span data-stu-id="abe28-1179">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="abe28-1180">Corrige un problema que causaba que los delegados vean errores intermitentes al abrir carpetas compartidas en otro buzón.</span><span class="sxs-lookup"><span data-stu-id="abe28-1180">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="abe28-1181">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1181">PowerPoint</span></span>

- <span data-ttu-id="abe28-1182">Corrección de seguridad para solucionar un problema que deshabilita las protecciones IRM al abrir un archivo de PowerPoint en la vista protegida.</span><span class="sxs-lookup"><span data-stu-id="abe28-1182">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="abe28-1183">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-1183">Office Suite</span></span>

- <span data-ttu-id="abe28-p173">Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan tóners. Cambiar mensaje para mostrar "tóner/tinta bajos" & "no tóner/tinta".</span><span class="sxs-lookup"><span data-stu-id="abe28-p173">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2009-september-26"></a><span data-ttu-id="abe28-1187">Versión 2009: 26 de septiembre</span><span class="sxs-lookup"><span data-stu-id="abe28-1187">Version 2009: September 26</span></span>
<span data-ttu-id="abe28-1188">*Versión 2009 (Compilación 13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1188">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1190">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1190">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-1191">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1191">Outlook</span></span>

- <span data-ttu-id="abe28-1192">Corrige un problema que causaba que se enviaran algunos mensajes de correo electrónico generados automáticamente con el cuerpo en blanco cuando la línea del asunto está en blanco.</span><span class="sxs-lookup"><span data-stu-id="abe28-1192">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="project"></a><span data-ttu-id="abe28-1193">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-1193">Project</span></span>

- <span data-ttu-id="abe28-1194">Se ha corregido un problema por el que si se ejecuta un código de evento y se intenta realizar cambios desde la vista del Formulario de tareas, es posible que el botón Aceptar no confirme los cambios.</span><span class="sxs-lookup"><span data-stu-id="abe28-1194">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


[//]: # (NO QUITAR EL CONTENIDO DE LOS DETALLES DE ERROR FINAL)

## <a name="version-2009-september-21"></a><span data-ttu-id="abe28-1196">Versión 2009: 21 de septiembre</span><span class="sxs-lookup"><span data-stu-id="abe28-1196">Version 2009: September 21</span></span>
<span data-ttu-id="abe28-1197">*Versión 2009 (Compilación 13231.20200)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1197">*Version 2009 (Build 13231.20200)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1199">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1199">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="abe28-1200">Acceso</span><span class="sxs-lookup"><span data-stu-id="abe28-1200">Access</span></span>

- <span data-ttu-id="abe28-1201">**Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="abe28-1201">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="abe28-1202">Vaya a Archivo > Opciones y seleccione "Usar configuración del sistema" junto al Tema de Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1202">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="abe28-1203">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1203">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="abe28-1204">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1204">Excel</span></span>

- <span data-ttu-id="abe28-1205">**Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1205">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="abe28-1206">No es necesario realizar ninguna conversión.</span><span class="sxs-lookup"><span data-stu-id="abe28-1206">No conversion required.</span></span><br /><span data-ttu-id="abe28-1207">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="abe28-1207">See details in [blog post](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="abe28-1208">**Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="abe28-1208">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="abe28-1209">Vaya a Archivo > Opciones y seleccione "Usar configuración del sistema" junto al Tema de Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1209">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="abe28-1210">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1210">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a><span data-ttu-id="abe28-1211">OneNote</span><span class="sxs-lookup"><span data-stu-id="abe28-1211">OneNote</span></span>

- <span data-ttu-id="abe28-1212">**Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="abe28-1212">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="abe28-1213">Vaya a Archivo > Opciones y seleccione "Usar configuración del sistema" junto al Tema de Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1213">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="abe28-1214">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1214">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="abe28-1215">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1215">Outlook</span></span>

- <span data-ttu-id="abe28-1216">**Eliminar conversación por propietario del mensaje:** esta característica permite eliminar una conversación por propietario del mensaje.</span><span class="sxs-lookup"><span data-stu-id="abe28-1216">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

- <span data-ttu-id="abe28-1217">**Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1217">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="abe28-1218">No es necesario realizar ninguna conversión.</span><span class="sxs-lookup"><span data-stu-id="abe28-1218">No conversion required.</span></span><br /><span data-ttu-id="abe28-1219">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="abe28-1219">See details in [blog post](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="abe28-1220">**Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="abe28-1220">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="abe28-1221">Vaya a Archivo > Opciones y seleccione "Usar configuración del sistema" junto al Tema de Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1221">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="abe28-1222">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1222">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="powerpoint"></a><span data-ttu-id="abe28-1223">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1223">PowerPoint</span></span>

- <span data-ttu-id="abe28-1224">**Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1224">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="abe28-1225">No es necesario realizar ninguna conversión.</span><span class="sxs-lookup"><span data-stu-id="abe28-1225">No conversion required.</span></span><br /><span data-ttu-id="abe28-1226">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="abe28-1226">See details in [blog post](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="abe28-1227">**Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="abe28-1227">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="abe28-1228">Vaya a Archivo > Opciones y seleccione "Usar configuración del sistema" junto al Tema de Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1228">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="abe28-1229">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1229">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a><span data-ttu-id="abe28-1230">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-1230">Project</span></span>

- <span data-ttu-id="abe28-1231">**Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="abe28-1231">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="abe28-1232">Vaya a Archivo > Opciones y seleccione "Usar configuración del sistema" junto al Tema de Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1232">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="abe28-1233">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1233">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="abe28-1234">Publisher</span><span class="sxs-lookup"><span data-stu-id="abe28-1234">Publisher</span></span>

- <span data-ttu-id="abe28-1235">**Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="abe28-1235">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="abe28-1236">Vaya a Archivo > Opciones y seleccione "Usar configuración del sistema" junto al Tema de Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1236">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="abe28-1237">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1237">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="abe28-1238">Visio</span><span class="sxs-lookup"><span data-stu-id="abe28-1238">Visio</span></span>

- <span data-ttu-id="abe28-1239">**Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="abe28-1239">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="abe28-1240">Vaya a Archivo > Opciones y seleccione "Usar configuración del sistema" junto al Tema de Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1240">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="abe28-1241">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1241">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="abe28-1242">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1242">Word</span></span>

- <span data-ttu-id="abe28-1243">**Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1243">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="abe28-1244">No es necesario realizar ninguna conversión.</span><span class="sxs-lookup"><span data-stu-id="abe28-1244">No conversion required.</span></span><br /><span data-ttu-id="abe28-1245">Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="abe28-1245">See details in [blog post](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="abe28-1246">**Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="abe28-1246">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="abe28-1247">Vaya a Archivo > Opciones y seleccione "Usar configuración del sistema" junto al Tema de Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1247">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="abe28-1248">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1248">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1251">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1251">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="abe28-1252">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1252">PowerPoint</span></span>

- <span data-ttu-id="abe28-1253">Se ha corregido un problema que provocaba la coautoría lenta en archivos que contienen números grandes de determinados tipos de objetos de datos (E2o).</span><span class="sxs-lookup"><span data-stu-id="abe28-1253">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>



[//]: # (NO QUITAR EL EXTREMO DEL CONTENIDO CON LOS DETALLES DEL ERROR)

## <a name="version-2009-september-14"></a><span data-ttu-id="abe28-1255">Versión 2009: 14 de septiembre</span><span class="sxs-lookup"><span data-stu-id="abe28-1255">Version 2009: September 14</span></span>
<span data-ttu-id="abe28-1256">*Versión 2009 (compilación 13231.20152)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1256">*Version 2009 (Build 13231.20152)*</span></span>
* <span data-ttu-id="abe28-1257">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="abe28-1257">Various bugs and performance fixes.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

## <a name="version-2009-september-10"></a><span data-ttu-id="abe28-1260">Versión 2009: 10 de septiembre</span><span class="sxs-lookup"><span data-stu-id="abe28-1260">Version 2009: September 10</span></span>
<span data-ttu-id="abe28-1261">*Versión 2009 (Compilación 13231.20126)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1261">*Version 2009 (Build 13231.20126)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1263">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1263">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="abe28-1264">Acceso</span><span class="sxs-lookup"><span data-stu-id="abe28-1264">Access</span></span>

- <span data-ttu-id="abe28-1265">Se ha corregido el problema y ya no se debería experimentar el bloqueo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1265">This issue has now been resolved and you should no longer experience a crash.</span></span>


- <span data-ttu-id="abe28-1266">Se ha corregido un problema por el que las conexiones a una base de datos ODBC no funcionaban con aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="abe28-1266">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>


### <a name="excel"></a><span data-ttu-id="abe28-1267">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1267">Excel</span></span>

- <span data-ttu-id="abe28-1268">Se corrigió un problema por el cual si abría un archivo que contiene la función LET, mostraba la alerta: "Encontramos un problema con el contenido en "su archivo.xlsx".</span><span class="sxs-lookup"><span data-stu-id="abe28-1268">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="abe28-1269">¿Quiere que intentemos recuperar todo lo que podamos?</span><span class="sxs-lookup"><span data-stu-id="abe28-1269">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="abe28-1270">Si confía en el origen de este libro, haga clic en Sí".</span><span class="sxs-lookup"><span data-stu-id="abe28-1270">If you trust the source of this workbook, click Yes".</span></span>


- <span data-ttu-id="abe28-1271">Hemos corregido un problema en el que si un usuario escribía el nombre de una fórmula, incluidos los paréntesis, e invocaba ayuda a través de F1, el tema de ayuda específico de esa fórmula no se mostraba.</span><span class="sxs-lookup"><span data-stu-id="abe28-1271">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>


- <span data-ttu-id="abe28-1272">Se ha corregido un problema por el que, al usar una macro para establecer la propiedad FormulaR1C1 para un rango, las referencias de celda eran incorrectas si una hoja de gráfico era la hoja activa.</span><span class="sxs-lookup"><span data-stu-id="abe28-1272">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="abe28-1273">Se corrigió un problema por el cual los usuarios no podían modificar un filtro de tabla dinámica porque estaba configurado en un valor que ya no estaba presente en una base de datos de Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="abe28-1273">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="abe28-1274">Se corrigió un bloqueo relacionado con las referencias de complementos XLAM y los rangos con nombre.</span><span class="sxs-lookup"><span data-stu-id="abe28-1274">Fixed a crash related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="abe28-p188">Se corrigió un problema por el que si un usuario aplicaba un estilo personalizado a una matriz dinámica, obtenía el error: "No se puede cambiar parte de una matriz". Se ha eliminado una restricción heredada.</span><span class="sxs-lookup"><span data-stu-id="abe28-p188">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array". This was a legacy restriction that has been removed.</span></span>


- <span data-ttu-id="abe28-1277">Se corrigió un problema que provocaba que los macros asignados a los botones no funcionen después de restaurar una versión anterior del archivo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1277">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>


- <span data-ttu-id="abe28-1278">Se ha corregido un problema por el que las entradas manuscritas podrían hacer que Excel dejara de responder.</span><span class="sxs-lookup"><span data-stu-id="abe28-1278">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="abe28-1279">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1279">Outlook</span></span>

- <span data-ttu-id="abe28-1280">Se corrigió un problema que proporciona más flexibilidad para habilitar o deshabilitar las opciones de registro predeterminadas mediante la directiva de grupo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1280">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>


- <span data-ttu-id="abe28-1281">Se corrigió un problema por el que el nombre de dominio heredado de un remitente de correo electrónico se conservaba y mostraba después de que se moviera un borrador del correo electrónico entre buzones con permisos de asistente y permisos de administrador.</span><span class="sxs-lookup"><span data-stu-id="abe28-1281">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>


- <span data-ttu-id="abe28-1282">Se corrigió un problema que provocaba que algunos usuarios vieran que Outlook se iniciaba en un estado sin conexión hasta que optaban manualmente por trabajar en línea.</span><span class="sxs-lookup"><span data-stu-id="abe28-1282">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="abe28-1283">Se corrigió un problema por el cual ejecutar el código VBA ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") después de habilitar Cinta de opciones de una línea (SLR) daba como resultado un error de tiempo de ejecución.</span><span class="sxs-lookup"><span data-stu-id="abe28-1283">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>


- <span data-ttu-id="abe28-1284">Se corrigió un problema por el cual los botones 'Aceptar' y 'Cancelar' en el cuadro de diálogo Respuestas automáticas no eran visibles en un sistema con una resolución alta (como 1750 x 1920) combinada con un tamaño de texto grande (como 175 %).</span><span class="sxs-lookup"><span data-stu-id="abe28-1284">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>


- <span data-ttu-id="abe28-1285">Se corrigió una condición por la que enviar una convocatoria de reunión desde un grupo de contactos vacío a otro grupo de contactos provocaba un bloqueo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1285">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>


- <span data-ttu-id="abe28-1286">Se corrigió un problema que provocaba que los usuarios experimentaran un bloqueo al abrir algunos correos electrónicos muy grandes.</span><span class="sxs-lookup"><span data-stu-id="abe28-1286">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="abe28-1287">Se corrigió un problema por el que si la directiva de grupo requiere que un complemento esté siempre habilitado, los complementos de supervisión no están disponibles para evitar que los usuarios deshabiliten el complemento.</span><span class="sxs-lookup"><span data-stu-id="abe28-1287">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>


- <span data-ttu-id="abe28-1288">Resuelve un problema debido al cual los usuarios podían enviar contenido de correo electrónico que incluía una directiva de "No reenviar" aplicada a OneNote al seleccionar más de un mensaje.</span><span class="sxs-lookup"><span data-stu-id="abe28-1288">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>


- <span data-ttu-id="abe28-1289">Se ha corregido un problema por el que los usuarios ahora pueden deshabilitar IRM (Information Rights Management) para Outlook sin tener que deshabilitarlo para el resto de las aplicaciones de Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1289">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="abe28-1290">Se ha corregido un problema que provocaba que los atributos de la cuenta de usuario de Active Directory para "otherTelephone" y "otherHomePhone" no se asignaran a los atributos LDAP correspondientes de Outlook.</span><span class="sxs-lookup"><span data-stu-id="abe28-1290">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>


- <span data-ttu-id="abe28-1291">Este cambio corrige un problema que hace que la página de Reunión continuara mostrándose después de que el usuario había cambiado de pestaña desde la página Reunión a la página del Asistente para programación.</span><span class="sxs-lookup"><span data-stu-id="abe28-1291">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="abe28-1292">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1292">PowerPoint</span></span>

- <span data-ttu-id="abe28-1293">Se ha corregido un problema que provocaba que los usuarios no pudieran ver la barra de herramientas o de título en ciertas condiciones.</span><span class="sxs-lookup"><span data-stu-id="abe28-1293">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>


- <span data-ttu-id="abe28-1294">Se corrigió un problema por el cual, después de iniciar PowerPoint, insertar una diapositiva y abrir y cerrar el panel de comentarios, las diapositivas en el panel de miniaturas se mostraban superpuestas.</span><span class="sxs-lookup"><span data-stu-id="abe28-1294">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>


- <span data-ttu-id="abe28-1295">Se corrigió un problema que deshabilitaba la funcionalidad para insertar un vídeo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1295">We fixed an issue where the functionality to insert a video was disabled.</span></span>


- <span data-ttu-id="abe28-1296">Se corrigió un problema que provocaba que los vídeos no se reproducieran de manera automática en las presentaciones.</span><span class="sxs-lookup"><span data-stu-id="abe28-1296">We fixed an issue where videos were not playing automatically in slideshows.</span></span>


### <a name="project"></a><span data-ttu-id="abe28-1297">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-1297">Project</span></span>

- <span data-ttu-id="abe28-1298">Se corrigió un problema por el cual si un recurso tiene varias tablas de tasas de coste, es posible que el coste restante no se calcule correctamente.</span><span class="sxs-lookup"><span data-stu-id="abe28-1298">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>


- <span data-ttu-id="abe28-1299">Se ha corregido un problema que provocaba que la fecha de finalización de Project no se actualice para los proyectos conectados a la lista de tareas de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="abe28-1299">We fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


### <a name="visio"></a><span data-ttu-id="abe28-1300">Visio</span><span class="sxs-lookup"><span data-stu-id="abe28-1300">Visio</span></span>

- <span data-ttu-id="abe28-1301">Los usuarios han reportado el bloqueo de la Vista previa dinámica en la alineación del texto.</span><span class="sxs-lookup"><span data-stu-id="abe28-1301">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="abe28-1302">Bloqueo al llegar a la parte superior en la bifurcación de repositorio de julio.</span><span class="sxs-lookup"><span data-stu-id="abe28-1302">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="abe28-1303">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1303">Word</span></span>

- <span data-ttu-id="abe28-1304">Se corrigió un problema por el cual la tarjeta de Comentarios mostraba un borde alrededor del texto del comentario si el usuario hacía clic en el comentario.</span><span class="sxs-lookup"><span data-stu-id="abe28-1304">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>


- <span data-ttu-id="abe28-1305">Se ha corregido un problema que provocaba que el icono de la imagen de viñeta no se mostrara de forma correcta.</span><span class="sxs-lookup"><span data-stu-id="abe28-1305">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>


- <span data-ttu-id="abe28-1306">Se ha corregido un problema que impedía al usuario salir del encabezado o pie de página al seleccionar un comentario.</span><span class="sxs-lookup"><span data-stu-id="abe28-1306">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>


- <span data-ttu-id="abe28-1307">Se ha corregido un problema que provocaba que Word se pudiera bloquear después de eliminar comentarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-1307">We fixed an issue where Word could crash after comments were deleted.</span></span>


- <span data-ttu-id="abe28-1308">Se corrigió un problema por el cual si un usuario creaba un borrador de comentario anclado a una línea que ya contenía comentarios comprometidos, el borrador se organizaba en el orden incorrecto en relación con el comentario comprometido en SideTrack.</span><span class="sxs-lookup"><span data-stu-id="abe28-1308">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>


- <span data-ttu-id="abe28-1309">Se corrigió un problema por el cual el foco no iba al panel de comentarios si el documento se ampliaba al 160 % o más y el panel de comentarios no estaba visible.</span><span class="sxs-lookup"><span data-stu-id="abe28-1309">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>


- <span data-ttu-id="abe28-1310">Hemos corregido un problema que impedía a los usuarios ver los hilos de comentarios que superaran el límite de la barra de los comentarios, porque el desplazamiento por dicha barra no funcionaba.</span><span class="sxs-lookup"><span data-stu-id="abe28-1310">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>


- <span data-ttu-id="abe28-1311">Hemos corregido un problema que impedía la búsqueda de comentarios resueltos en el panel de los comentarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-1311">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>


- <span data-ttu-id="abe28-1312">Se corrigió un problema por el cual los comentarios de un documento se mostraban en otros documentos abiertos después de cambiar entre varios documentos abiertos.</span><span class="sxs-lookup"><span data-stu-id="abe28-1312">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>


- <span data-ttu-id="abe28-1313">Se corrigió un problema que provocaba que los vínculos largos no se ajustaran al guardar un documento en formato HTML.</span><span class="sxs-lookup"><span data-stu-id="abe28-1313">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="abe28-1314">Se ha corregido un problema que provocaba que, en algunos casos, las viñetas no se mostraran de forma correcta en el correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="abe28-1314">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>


- <span data-ttu-id="abe28-1315">Se corrigió un problema con las macros que provocaba que AutoOpen se ejecutara antes de AutoExec.</span><span class="sxs-lookup"><span data-stu-id="abe28-1315">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>


### <a name="office-suite"></a><span data-ttu-id="abe28-1316">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-1316">Office Suite</span></span>

- <span data-ttu-id="abe28-1317">Se ha corregido un problema en la Herramienta de implementación de Office que provocaba errores en la configuración al usar la característica RemoveMSI con el producto de Office 2007 "Informes de errores de aplicaciones de Microsoft".</span><span class="sxs-lookup"><span data-stu-id="abe28-1317">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="abe28-1318">Se ha corregido un problema en el cuadro de diálogo Comprimir imágenes que impedía que se conservaran algunas opciones de configuración de PPP seleccionadas por el usuario.</span><span class="sxs-lookup"><span data-stu-id="abe28-1318">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>


- <span data-ttu-id="abe28-1319">Este cambio resuelve un problema con el cuadro de diálogo de Comprimir imagen, que no retiene determinadas configuraciones de usuario.</span><span class="sxs-lookup"><span data-stu-id="abe28-1319">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-september-04"></a><span data-ttu-id="abe28-1321">Versión 2008: 04 de septiembre</span><span class="sxs-lookup"><span data-stu-id="abe28-1321">Version 2008: September 04</span></span>
<span data-ttu-id="abe28-1322">*Versión 2008 (compilación 13127.20378)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1322">*Version 2008 (Build 13127.20378)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1324">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1324">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="abe28-1325">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-1325">Office Suite</span></span>

- <span data-ttu-id="abe28-1326">Este cambio resuelve un problema con el cuadro de diálogo de Comprimir imagen, que no retiene determinadas configuraciones de usuario.</span><span class="sxs-lookup"><span data-stu-id="abe28-1326">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-september-02"></a><span data-ttu-id="abe28-1328">Versión 2008: 02 de septiembre</span><span class="sxs-lookup"><span data-stu-id="abe28-1328">Version 2008: September 02</span></span>
<span data-ttu-id="abe28-1329">*Versión 2008 (compilación 13127.20360)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1329">*Version 2008 (Build 13127.20360)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1331">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1331">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-1332">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1332">Excel</span></span>

- <span data-ttu-id="abe28-1333">**Guarde formas como imágenes:** con tan solo unos pocos clics, guarde una forma, icono u otro objeto como archivo de imagen para que pueda volver a usarlo en otro lugar.</span><span class="sxs-lookup"><span data-stu-id="abe28-1333">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="abe28-1334">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1334">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="abe28-1335">**Realice cambios rápidos con el lápiz de Excel:** herramienta bolígrafo que le ayudará a escribir a mano y realizar cambios rápidos en los datos</span><span class="sxs-lookup"><span data-stu-id="abe28-1335">**Make quick edits using the Excel pen:** Pen Tool to help you handwrite and make quick edits to your data</span></span>



[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1338">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1338">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-1339">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1339">Excel</span></span>

- <span data-ttu-id="abe28-1340">Se ha corregido un problema que provocaba que Excel se bloqueara en determinadas circunstancias al usar Copiar formato.</span><span class="sxs-lookup"><span data-stu-id="abe28-1340">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="abe28-1341">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1341">Word</span></span>

- <span data-ttu-id="abe28-1342">Se ha corregido un problema por el cual los estilos base no se actualizaban con el estilo Normal.</span><span class="sxs-lookup"><span data-stu-id="abe28-1342">We fixed an issue which the base styles are not updated with Normal style.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-august-27"></a><span data-ttu-id="abe28-1344">Versión 2008: 27 de agosto</span><span class="sxs-lookup"><span data-stu-id="abe28-1344">Version 2008: August 27</span></span>
<span data-ttu-id="abe28-1345">*Versión 2008 (Compilación 13127.20296)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1345">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1349">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1349">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-1350">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1350">Outlook</span></span>

- <span data-ttu-id="abe28-1351">Corrige un problema que evitaba que los usuarios que intentaran crear una solicitud de reunión desde una cuenta secundaria añadida a su perfil vieran el campo De: en blanco en lugar de su dirección de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="abe28-1351">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="abe28-1352">Corrige un problema que evitaba que los usuarios se conectaran a las carpetas públicas luego de agregar un buzón compartido.</span><span class="sxs-lookup"><span data-stu-id="abe28-1352">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="abe28-1353">Corrige un problema que provocaba que los usuarios experimentaran bloqueos ocasionales al interactuar con datos adjuntos en la nube.</span><span class="sxs-lookup"><span data-stu-id="abe28-1353">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="abe28-1354">Esto corrige un problema que provocaba que los usuarios experimentaran bloqueos ocasionales al editar los destinatarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-1354">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="abe28-1355">Corrige un problema que provocaba que los usuarios vieran anomalías al usar la vista compacta.</span><span class="sxs-lookup"><span data-stu-id="abe28-1355">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

### <a name="word"></a><span data-ttu-id="abe28-1356">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1356">Word</span></span>

- <span data-ttu-id="abe28-1357">Este cambio corrige un problema que provocaba que las aplicaciones de Office se queden atascadas en un estado de error de guardado silencioso después de una sesión de coautoría anterior.</span><span class="sxs-lookup"><span data-stu-id="abe28-1357">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="abe28-1358">Se ha corregido un problema por el que se ejecuta la macro AutoOpen antes de AutoExec.</span><span class="sxs-lookup"><span data-stu-id="abe28-1358">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL FIN DE CONTENIDO)

## <a name="version-2008-august-25"></a><span data-ttu-id="abe28-1360">Versión 2008: 25 de agosto</span><span class="sxs-lookup"><span data-stu-id="abe28-1360">Version 2008: August 25</span></span>
<span data-ttu-id="abe28-1361">*Versión 2008 (Compilación 13127.20268)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1361">*Version 2008 (Build 13127.20268)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1363">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1363">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-1364">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1364">Outlook</span></span>

- <span data-ttu-id="abe28-1365">**Reciba sugerencias por correo electrónico al buscar por persona.:** A medida que escriba los términos de búsqueda en Outlook, recibirá los correos electrónicos más relevantes en las sugerencias.</span><span class="sxs-lookup"><span data-stu-id="abe28-1365">**Receive email suggestions when searching by person.:** As you type your search terms in Outlook you'll receive the most relevant emails surfaced in the suggestions.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1368">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1368">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-1369">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1369">Outlook</span></span>

- <span data-ttu-id="abe28-1370">Corrige un problema que provocaba que los usuarios recibieran el siguiente error al responder a un correo o al redactar uno nuevo: "Algunos archivos de esta página web no están en la ubicación esperada.</span><span class="sxs-lookup"><span data-stu-id="abe28-1370">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="abe28-1371">¿Desea descargarlos de todos modos?</span><span class="sxs-lookup"><span data-stu-id="abe28-1371">Do you want to download them anyway?</span></span> <span data-ttu-id="abe28-1372">Si está seguro de que la página web es una fuente de confianza, haga clic en Sí".</span><span class="sxs-lookup"><span data-stu-id="abe28-1372">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="abe28-1373">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-1373">Project</span></span>

- <span data-ttu-id="abe28-1374">Se ha corregido un problema debido al cual, si un recurso tenía más de una tabla de tasa de costo definida, el costo restante no siempre se calculaba correctamente.</span><span class="sxs-lookup"><span data-stu-id="abe28-1374">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


### <a name="word"></a><span data-ttu-id="abe28-1375">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1375">Word</span></span>

- <span data-ttu-id="abe28-1376">Corrige un problema que provocaba que los usuarios experimentaran un bloqueo al responder a un correo o al redactar uno nuevo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1376">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-august-17"></a><span data-ttu-id="abe28-1378">Versión 2008: 17 de agosto</span><span class="sxs-lookup"><span data-stu-id="abe28-1378">Version 2008: August 17</span></span>
<span data-ttu-id="abe28-1379">*Versión 2008 (Compilación 13127.20208)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1379">*Version 2008 (Build 13127.20208)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1381">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1381">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-1382">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1382">Outlook</span></span>

- <span data-ttu-id="abe28-1383">Se ha corregido un problema que provocaba un error en la eliminación de las reuniones del calendario de un administrador cuando un delegado las rechazaba en determinadas circunstancias.</span><span class="sxs-lookup"><span data-stu-id="abe28-1383">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="abe28-1384">Se ha corregido un problema que provocaba que los usuarios de algunos juegos de caracteres viesen nombres de archivo que se mostraban de forma incorrecta al agregar un vínculo inteligente a un archivo de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="abe28-1384">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="abe28-1385">Se ha corregido un problema que provocaba que los usuarios experimentaran un error al eliminar 4 o más mensajes de correo electrónico de una cuenta POP con la opción "Descargar solo encabezados" seleccionada.</span><span class="sxs-lookup"><span data-stu-id="abe28-1385">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="abe28-1386">Se ha corregido un problema que provocaba que el menú contextual del botón derecho no apareciera en los controles de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="abe28-1386">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-august-11"></a><span data-ttu-id="abe28-1388">Versión 2008: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="abe28-1388">Version 2008: August 11</span></span>
<span data-ttu-id="abe28-1389">*Versión 2008 (Compilación 13127.20164)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1389">*Version 2008 (Build 13127.20164)*</span></span>

<span data-ttu-id="abe28-1390">Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="abe28-1390">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1392">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1392">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="abe28-1393">Acceso</span><span class="sxs-lookup"><span data-stu-id="abe28-1393">Access</span></span>

- <span data-ttu-id="abe28-1394">Esta corrección resuelve un problema por el que al intentar ejecutar determinadas consultas anteriormente se generaba el mensaje de error "La consulta es demasiado compleja".</span><span class="sxs-lookup"><span data-stu-id="abe28-1394">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="abe28-1395">Si tiene Office 365 instalado, ya no necesita instalar el nuestro motor de Componente redistribuíble de ACE para exponer ACE fuera del ecosistema de Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1395">If you have Office 365 installed, you no longer need to install our ACE Redistributable Engine to expose ACE outside of the Office ecosystem.</span></span> <span data-ttu-id="abe28-1396">Por ello, los usuarios con Office 365 ya no necesitarán el motor de Componente redistribuíble de ACE por lo que no debería experimentar este problema.</span><span class="sxs-lookup"><span data-stu-id="abe28-1396">Therefore, for those with Office 365, you will no longer need the ACE Redist Engine, and consequently you should not experience this issue.</span></span>

- <span data-ttu-id="abe28-1397">Este problema se ha resuelto: ahora puede usar el controlador ODBC fuera de las aplicaciones de Hacer clic y ejecutar de Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1397">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="abe28-1398">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1398">Excel</span></span>

- <span data-ttu-id="abe28-1399">Se ha corregido un problema por el que si se cambia el orden de una serie de gráficos, la casilla de verificación correspondiente alineada con la serie no se reordenaba junto con la serie.</span><span class="sxs-lookup"><span data-stu-id="abe28-1399">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>

- <span data-ttu-id="abe28-1400">Se puede producir un error al intentar guardar un archivo que contiene una fórmula con la función LET().</span><span class="sxs-lookup"><span data-stu-id="abe28-1400">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="abe28-1401">Se corrigió un problema por el que los gráficos no siempre se actualizaban como se esperaba al habilitar "ForceFullCalculation" a través de VBA en el libro.</span><span class="sxs-lookup"><span data-stu-id="abe28-1401">We fixed an issue where charts were not always updated as expected when "ForceFullCalculation" was enabled via VBA for the workbook.</span></span>

- <span data-ttu-id="abe28-1402">Se corrigió un problema por el que una copia de una imagen con un relleno degradado radial no coincidía con el original.</span><span class="sxs-lookup"><span data-stu-id="abe28-1402">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="onenote"></a><span data-ttu-id="abe28-1403">OneNote</span><span class="sxs-lookup"><span data-stu-id="abe28-1403">OneNote</span></span>

- <span data-ttu-id="abe28-1404">Se ha corregido un problema que provocaba que el texto de marcador de posición en el cuadro de edición de búsqueda se desbordase si se reducía el tamaño de la ventana de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="abe28-1404">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-1405">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1405">Outlook</span></span>

- <span data-ttu-id="abe28-1406">Se corrigió un problema en la creación de varios perfiles en Outlook desde el mismo dominio de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="abe28-1406">We fixed an issue around creating multiple profiles in Outlookfrom the same email domain.</span></span>

- <span data-ttu-id="abe28-1407">Se corrigió un problema que impedía a algunos usuarios de la característica Mejoras del calendario compartido ver un calendario compartido recién agregado.</span><span class="sxs-lookup"><span data-stu-id="abe28-1407">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="abe28-1408">Se corrigió un problema por el que el icono de bloqueo no se mostraba en el encabezado de los mensajes cifrados S/MIME.</span><span class="sxs-lookup"><span data-stu-id="abe28-1408">Addressed an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>

- <span data-ttu-id="abe28-1409">Se corrigió un problema por el que la opción Permitir reenvío no aparecía en las Opciones de respuesta de las reuniones del calendario compartido en aquellos casos en los que la carpeta de descarga compartida NO se había comprobado.</span><span class="sxs-lookup"><span data-stu-id="abe28-1409">We fixed an issue where the "Allow Forwarding" option was missing from the shared calendar meeting "Response Options" if Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="abe28-1410">Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.</span><span class="sxs-lookup"><span data-stu-id="abe28-1410">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="abe28-1411">Se corrigió un problema por el que el botón Imprimir aparecía en un estado deshabilitado aunque el usuario tuviera los permisos de impresión adecuados.</span><span class="sxs-lookup"><span data-stu-id="abe28-1411">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

- <span data-ttu-id="abe28-1412">Se corrigió un problema por el que los datos adjuntos se quitaban de mensajes S/MIME al enviarse sin cifrar.</span><span class="sxs-lookup"><span data-stu-id="abe28-1412">Addressed an issue that caused attachments to get stripped from S/MIME messages when sending as unencrypted.</span></span>

- <span data-ttu-id="abe28-1413">Se corrigió un problema por el que los mensajes de texto sin formato S/MIME se volvían ilegibles al enviarse.</span><span class="sxs-lookup"><span data-stu-id="abe28-1413">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>

- <span data-ttu-id="abe28-1414">Se corrigió un problema por el que los datos adjuntos se dañaban al enviar un correo electrónico S/MIME sin cifrar.</span><span class="sxs-lookup"><span data-stu-id="abe28-1414">Addressed an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>

- <span data-ttu-id="abe28-1415">Se corrigió un problema por el que los destinatarios no podían guardar los mensajes con derechos protegidos incluso cuando el remitente otorgaba el permiso de Guardar como.</span><span class="sxs-lookup"><span data-stu-id="abe28-1415">Addressed an issue that cause recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>

- <span data-ttu-id="abe28-1416">Esta corrección aborda un problema que hacía que los usuarios no pudieran agregar una firma al responder a un mensaje administrado con derechos digitales desde una ventana de inspección cuando el usuario no tenía permisos de propietario sobre el mensaje al que se respondía.</span><span class="sxs-lookup"><span data-stu-id="abe28-1416">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>

- <span data-ttu-id="abe28-1417">La corrección aborda un problema que provocaba que Outlook no mostrara correctamente los saltos de línea en el contenido de Markdown.</span><span class="sxs-lookup"><span data-stu-id="abe28-1417">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

- <span data-ttu-id="abe28-1418">Se corrigió un problema por el que las etiquetas de algunas opciones de Búsqueda avanzada se truncaban en algunos idiomas.</span><span class="sxs-lookup"><span data-stu-id="abe28-1418">Addressed an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="abe28-1419">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1419">PowerPoint</span></span>

- <span data-ttu-id="abe28-1420">Se ha corregido un problema por el que una copia de una imagen con un relleno degradado radial no coincidía con el original.</span><span class="sxs-lookup"><span data-stu-id="abe28-1420">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="abe28-1421">Se corrigió un problema por el que el botón Formularios de PowerPoint no permitía la creación de formularios cuando no se permitía el acceso a la Tienda Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1421">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="abe28-1422">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-1422">Project</span></span>

- <span data-ttu-id="abe28-1423">Se corrigió un problema por el que las tareas que aparecen en la vista Panel de tareas no estaban sincronizadas con las del cuadro de diálogo Asignar recursos.</span><span class="sxs-lookup"><span data-stu-id="abe28-1423">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>

- <span data-ttu-id="abe28-1424">Se corrigió un problema que impedía al usuario guardar desde Project un PDF o XPS en una biblioteca de documentos de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="abe28-1424">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

- <span data-ttu-id="abe28-1425">Se corrigió un problema por el que si se copiaba y pegaba una tarea con varias dependencias, no se copiaban todas las dependencias correctamente.</span><span class="sxs-lookup"><span data-stu-id="abe28-1425">We fixed an issue where if you copied & pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

- <span data-ttu-id="abe28-1426">Se corrigió un problema por el que en una lista de tareas de SharePoint, los botones de la cinta de opciones en la segunda pestaña se podían deshabilitar.</span><span class="sxs-lookup"><span data-stu-id="abe28-1426">Fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="skype"></a><span data-ttu-id="abe28-1427">Skype</span><span class="sxs-lookup"><span data-stu-id="abe28-1427">Skype</span></span>

- <span data-ttu-id="abe28-1428">Se cambió el tono de piel del emoticono de baile a un color neutro</span><span class="sxs-lookup"><span data-stu-id="abe28-1428">Changed dancing emoticon skin tone to neutral color</span></span>

### <a name="visio"></a><span data-ttu-id="abe28-1429">Visio</span><span class="sxs-lookup"><span data-stu-id="abe28-1429">Visio</span></span>

- <span data-ttu-id="abe28-1430">Después de esta corrección, si el usuario detiene la ejecución del comando Delete con algún mecanismo intermedio (en este caso, con un complemento) la memoria no se verá afectada, y no afectará a todo el equipo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1430">After this fix, if the user halted the execution of delete command by any mechanism in between (in this case it was through add-in) the memory won't leak and the whole machine won't be impacted.</span></span>

### <a name="word"></a><span data-ttu-id="abe28-1431">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1431">Word</span></span>

- <span data-ttu-id="abe28-1432">Se ha corregido un problema que provocaba que Word dejara de responder después de pegar texto y una imagen en un cuadro de comentarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-1432">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>

- <span data-ttu-id="abe28-1433">Se corrigió un problema por el que una copia de una imagen con un relleno degradado radial no coincidía con el original.</span><span class="sxs-lookup"><span data-stu-id="abe28-1433">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="abe28-1434">Se ha corregido un problema que provocaba que el texto de marcador de posición en el cuadro de edición de búsqueda se desbordase si se reducía el tamaño de la ventana de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="abe28-1434">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

- <span data-ttu-id="abe28-1435">Se corrigió un problema por el que si se agregaba un comentario para realizar el seguimiento de un cambio, el panel de revisiones se abría de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="abe28-1435">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>

- <span data-ttu-id="abe28-1436">Se corrigió un problema por el que el comando Editor se deshabilitaba cuando el foco estaba en un cuadro de texto de comentario.</span><span class="sxs-lookup"><span data-stu-id="abe28-1436">We fixed an issue where the Editor command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="abe28-1437">Se corrigió un problema por el que el comando Mostrar marcas se deshabilitaba cuando el foco estaba en un cuadro de texto de comentario.</span><span class="sxs-lookup"><span data-stu-id="abe28-1437">We fixed an issue where the Show Markup command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="abe28-1438">Se corrigió un problema por el que el botón Nuevo comentario quedaba deshabilitado después de eliminar el último comentario.</span><span class="sxs-lookup"><span data-stu-id="abe28-1438">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

- <span data-ttu-id="abe28-1439">Se corrigió un problema por el que se deshabilitaba la opción Personas específicas de Control de cambios.</span><span class="sxs-lookup"><span data-stu-id="abe28-1439">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>

- <span data-ttu-id="abe28-1440">Se corrigió un problema por el que los vínculos a los documentos no se insertaban en el cuadro de comentarios a través de la lista desplegable Insertar > Vínculo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1440">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>

- <span data-ttu-id="abe28-1441">Se corrigió un bloqueo ocasional al abrir archivos HTML.</span><span class="sxs-lookup"><span data-stu-id="abe28-1441">We fixed an occasional hang while opening HTML files.</span></span>

- <span data-ttu-id="abe28-1442">Se corrigió un problema en un archivo XML personalizado en el que se podía perder el estado de los comentarios al abrir el documento.</span><span class="sxs-lookup"><span data-stu-id="abe28-1442">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

- <span data-ttu-id="abe28-1443">Se ha corregido un problema por el que el recuento de hipervínculos en la colección de hipervínculos de VBA no realizaba correctamente la iteración después de agregar una imagen que contenía un hipervínculo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1443">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

- <span data-ttu-id="abe28-p193">Para un antiguo panel de uso compartido basado en servicio no Web, al cerrar el documento mientras el panel de uso compartido está abierto, se podría producir un bloqueo. Este problema ya está solucionado.</span><span class="sxs-lookup"><span data-stu-id="abe28-p193">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash. This is now fixed.</span></span>

- <span data-ttu-id="abe28-1446">Se corrigió un problema en el que, después de abrir el usuario una nueva ventana de la aplicación desde la barra de tareas y crear un nuevo documento en blanco, se creaban archivos adicionales.</span><span class="sxs-lookup"><span data-stu-id="abe28-1446">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>

- <span data-ttu-id="abe28-1447">Se corrigió un problema por el que, si un usuario estaba editando un documento pero había perdido los permisos, no se informaba al usuario de que tenía que volver a autenticarse.</span><span class="sxs-lookup"><span data-stu-id="abe28-1447">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>



[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2007-august-05"></a><span data-ttu-id="abe28-1449">Versión 2007: 05 de agosto</span><span class="sxs-lookup"><span data-stu-id="abe28-1449">Version 2007: August 05</span></span>
<span data-ttu-id="abe28-1450">*Versión 2007 (compilación 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1450">*Version 2007 (Build 13029.20344)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)



[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1454">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1454">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-1455">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1455">Outlook</span></span>

- <span data-ttu-id="abe28-1456">Se corrigió un problema que provocaba que Outlook no pudiese recuperar sugerencias de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="abe28-1456">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="abe28-1457">Se corrigió un problema que provocaba que los usuarios se bloquearan en ocasiones al recuperar información personal.</span><span class="sxs-lookup"><span data-stu-id="abe28-1457">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="abe28-1458">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-1458">Project</span></span>

- <span data-ttu-id="abe28-1459">Se corrigió un problema por el que no se podía abrir un proyecto que estaba en mal estado.</span><span class="sxs-lookup"><span data-stu-id="abe28-1459">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2007-july-29"></a><span data-ttu-id="abe28-1461">Versión 2007: 29 de julio</span><span class="sxs-lookup"><span data-stu-id="abe28-1461">Version 2007: July 29</span></span>
<span data-ttu-id="abe28-1462">*Versión 2007 (compilación 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1462">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1464">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1464">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-1465">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1465">Excel</span></span>

- <span data-ttu-id="abe28-1466">**Obtenga datos de organización de Power BI mediante Tipos de datos:** los tipos de datos de Excel de Power BI se están publicando ahora para participantes de Office Insider en las organizaciones con Office 365 E5/A5 o Microsoft 365 E5/A5.</span><span class="sxs-lookup"><span data-stu-id="abe28-1466">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="abe28-1467">Obtener la información que necesita y actualizarla fácilmente es fundamental para muchos de los flujos de trabajo diarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-1467">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="abe28-1468">Le proporcionamos acceso a la información de Power BI de su empresa u organización como un tipo de datos en Excel, lo que amplía su capacidad de incorporar a las hojas de cálculo información vinculada.</span><span class="sxs-lookup"><span data-stu-id="abe28-1468">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="abe28-1469">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1469">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="abe28-1470">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="abe28-1470">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-1471">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1471">Outlook</span></span>

- <span data-ttu-id="abe28-1472">**Elija dónde buscar:** La nueva lista desplegable del ámbito de búsqueda le permite modificar de manera más sencilla su búsqueda y cambiar entre la carpeta actual y el buzón actual.</span><span class="sxs-lookup"><span data-stu-id="abe28-1472">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="abe28-1473">Gracias a todos los usuarios de Próximamente, quienes brindaron comentarios acerca de la nueva experiencia de búsqueda Search at Top.</span><span class="sxs-lookup"><span data-stu-id="abe28-1473">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="abe28-1474">¡Este diseño y actualización son el resultado de sus comentarios!</span><span class="sxs-lookup"><span data-stu-id="abe28-1474">This design and update came out of that feedback!</span></span>

### <a name="word"></a><span data-ttu-id="abe28-1475">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1475">Word</span></span>

- <span data-ttu-id="abe28-1476">**Mejor colaboración con comentarios modernos:** Agregue comentarios a objetos, @mencione compañeros y resuelva hilos de comentarios para disfrutar de una mejor experiencia de colaboración.</span><span class="sxs-lookup"><span data-stu-id="abe28-1476">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="abe28-1477">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1477">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1480">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1480">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-1481">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1481">Outlook</span></span>

- <span data-ttu-id="abe28-1482">Se ha corregido un problema que provocaba que los usuarios de CLP experimenten un bloqueo al cambiar la dirección del remitente en una respuesta desde un contexto protegido a uno no protegido.</span><span class="sxs-lookup"><span data-stu-id="abe28-1482">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="abe28-1483">Se ha corregido un problema que provocaba que la página del Asistente para programación no se mostrara.</span><span class="sxs-lookup"><span data-stu-id="abe28-1483">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="abe28-1484">Se ha abordado un problema que causaba problemas de formato en las alertas de notificación de incidentes.</span><span class="sxs-lookup"><span data-stu-id="abe28-1484">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2007-july-27"></a><span data-ttu-id="abe28-1486">Versión 2007: 27 de julio</span><span class="sxs-lookup"><span data-stu-id="abe28-1486">Version 2007: July 27</span></span>
<span data-ttu-id="abe28-1487">*Versión 2007 (compilación 13029.20292)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1487">*Version 2007 (Build 13029.20292)*</span></span>
* <span data-ttu-id="abe28-1488">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="abe28-1488">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-20"></a><span data-ttu-id="abe28-1489">Versión 2007: 20 de julio</span><span class="sxs-lookup"><span data-stu-id="abe28-1489">Version 2007: July 20</span></span>
<span data-ttu-id="abe28-1490">*Versión 2007 (compilación 13029.20236)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1490">*Version 2007 (Build 13029.20236)*</span></span>
* <span data-ttu-id="abe28-1491">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="abe28-1491">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-15"></a><span data-ttu-id="abe28-1492">Versión 2007: 15 de julio</span><span class="sxs-lookup"><span data-stu-id="abe28-1492">Version 2007: July 15</span></span>
<span data-ttu-id="abe28-1493">*Versión 2007 (compilación 13029.20200)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1493">*Version 2007 (Build 13029.20200)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1495">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1495">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-1496">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1496">Excel</span></span>

- <span data-ttu-id="abe28-1497">**Cree diagramas de Visio elegantes en Excel:** cree un diagrama de flujo o un organigrama con solo escribir datos en una hoja de cálculo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1497">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="abe28-1498">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1498">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1501">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1501">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="abe28-1502">Acceso</span><span class="sxs-lookup"><span data-stu-id="abe28-1502">Access</span></span>

- <span data-ttu-id="abe28-1503">Se ha corregido un problema por el que el administrador de tablas vinculadas solicitaba una clave principal al actualizar una tabla SQL vinculada.</span><span class="sxs-lookup"><span data-stu-id="abe28-1503">We fixed an issue where the linked table manager would prompt a primary key if a linked SQL table was refreshed.</span></span>

- <span data-ttu-id="abe28-1504">Se ha corregido un problema por el que las consultas en el Editor de consultas quedaban desplazadas fuera de la vista.</span><span class="sxs-lookup"><span data-stu-id="abe28-1504">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>

- <span data-ttu-id="abe28-1505">Se ha corregido un problema que provocaba que la ejecución de consultas tardara en completarse aproximadamente el doble del tiempo esperado.</span><span class="sxs-lookup"><span data-stu-id="abe28-1505">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="abe28-1506">Se ha corregido un problema que provocaba que Microsoft Access no identificara una Columna de identidad en una tabla vinculada de SQL Server, lo que podía hacer que las filas aparecieran como eliminadas de forma incorrecta.</span><span class="sxs-lookup"><span data-stu-id="abe28-1506">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="abe28-1507">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1507">Excel</span></span>

- <span data-ttu-id="abe28-1508">Se ha corregido un problema por el que las direcciones URL que no se basaban en http o https no se mostraban en la lista Utilizado recientemente.</span><span class="sxs-lookup"><span data-stu-id="abe28-1508">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

- <span data-ttu-id="abe28-1509">Se ha corregido un problema por el que podía producirse un error o bloqueo al cargar un libro con varias hojas en la vista previa de salto de página.</span><span class="sxs-lookup"><span data-stu-id="abe28-1509">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="abe28-1510">Se ha corregido un problema por el que las tablas del modelo de datos creadas en algunas versiones de Excel no se podían ver en "Vista previa de la tabla", pese a que no se había editado la consulta asociada a la tabla.</span><span class="sxs-lookup"><span data-stu-id="abe28-1510">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>

- <span data-ttu-id="abe28-1511">La opción "Omitir tipo de referencia (relativa o absoluta)" en el cuadro de diálogo "Definir nombre/Aplicar nombres" provocaba que las fórmulas no funcionaran.</span><span class="sxs-lookup"><span data-stu-id="abe28-1511">Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>

- <span data-ttu-id="abe28-1512">Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta personalizada al guardar un libro de trabajo en SharePoint o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="abe28-1512">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="abe28-1513">Se ha corregido un problema que provocaba que los libros de trabajo fueran de solo lectura cuando el archivo tenía activada la casilla "Se recomienda solo lectura".</span><span class="sxs-lookup"><span data-stu-id="abe28-1513">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

- <span data-ttu-id="abe28-1514">Se ha corregido un problema por el que podía producirse un error o bloqueo al cargar un libro con varias hojas en la vista previa de salto de página.</span><span class="sxs-lookup"><span data-stu-id="abe28-1514">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="abe28-1515">Se ha corregido un problema por el que no se podía aplicar el formato correcto a las líneas de cuadrícula principales de los gráficos radiales.</span><span class="sxs-lookup"><span data-stu-id="abe28-1515">We fixed an issue where the major gridlines of radar charts could not be formatted correctly.</span></span>


- <span data-ttu-id="abe28-1516">Se ha corregido un problema por el que al quitar filtros avanzados de datos se borraba el formato de tabla.</span><span class="sxs-lookup"><span data-stu-id="abe28-1516">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>


- <span data-ttu-id="abe28-1517">Se ha corregido un problema que provocaba que la ruta de acceso completa de un documento PDF incrustado se mostrara en el título del documento, en lugar de mostrarse solo en el nombre de archivo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1517">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>


- <span data-ttu-id="abe28-1518">Se ha corregido un problema por el que deshabilitar el CloudConnector de Wolfram y, a continuación, guardar y volver a abrir un libro de Excel podía dar lugar a un bloqueo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1518">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>


- <span data-ttu-id="abe28-1519">Se ha corregido un problema por el que iniciar Excel con el complemento Solver habilitado daba lugar a un bloqueo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1519">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>


### <a name="outlook"></a><span data-ttu-id="abe28-1520">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1520">Outlook</span></span>

- <span data-ttu-id="abe28-1521">Se ha corregido un problema por el que Outlook se bloqueaba si había más de 130 destinatarios en la línea "Para". Asimismo, se ha mejorado el rendimiento del procesamiento de texto.</span><span class="sxs-lookup"><span data-stu-id="abe28-1521">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>


- <span data-ttu-id="abe28-1522">Se ha corregido un problema por el que la ventana del Editor de métodos de entrada (IME) se superponía al texto subyacente escrito mediante el IME al utilizar varios monitores con resoluciones diferentes.</span><span class="sxs-lookup"><span data-stu-id="abe28-1522">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>


- <span data-ttu-id="abe28-1523">Se ha corregido un problema en la barra "Tareas Pendientes" que provocaba que los eventos que ocupaban más de dos días mostraran la misma hora de finalización para los siguientes días.</span><span class="sxs-lookup"><span data-stu-id="abe28-1523">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>


- <span data-ttu-id="abe28-1524">Se ha corregido un problema que causaba que la fecha de creación de datos adjuntos copiados en el sistema de archivos a través de la opción de arrastrar y soltar apareciera como el 1 de enero de 4501.</span><span class="sxs-lookup"><span data-stu-id="abe28-1524">Addresses an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="abe28-1525">Se ha corregido un problema por el que los usuarios no podían "Enviar como" o "Enviar en nombre de" en una lista de distribución.</span><span class="sxs-lookup"><span data-stu-id="abe28-1525">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>


- <span data-ttu-id="abe28-1526">Se ha corregido un problema que causaba que los delegados reciban un error al editar una cita de calendario existente en el calendario de un administrador.</span><span class="sxs-lookup"><span data-stu-id="abe28-1526">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="abe28-p198">Se ha corregido un problema que provocaba que los usuarios vieran el siguiente error al cerrar una cita guardada previamente: "No se puede guardar el elemento porque otro usuario lo modificó o se modificó en otra ventana. ¿Quiere realizar una copia en la carpeta predeterminada del elemento?".</span><span class="sxs-lookup"><span data-stu-id="abe28-p198">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved "The item cannot be saved because it was changed by another user or in another window. Do you want to make a copy in the default folder for the item?"</span></span>


- <span data-ttu-id="abe28-1529">Se ha corregido un problema que causaba que faltara la opción "Permitir reenvío" en las "Opciones de respuesta" de la reunión de calendario compartida cuando NO está marcado Descargar carpeta compartida.</span><span class="sxs-lookup"><span data-stu-id="abe28-1529">Addresses an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="abe28-1530">Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.</span><span class="sxs-lookup"><span data-stu-id="abe28-1530">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="abe28-1531">Se ha corregido un problema que provocaba que la lista de mensajes dejara de actualizarse durante varios minutos después de que los usuarios de Outlook usaran calendarios compartidos.</span><span class="sxs-lookup"><span data-stu-id="abe28-1531">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>


- <span data-ttu-id="abe28-1532">Se ha corregido un problema que impedía que los avisos del calendario mostraran la hora exacta de las reuniones programadas que iban a tener lugar en menos de una semana.</span><span class="sxs-lookup"><span data-stu-id="abe28-1532">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span> 


- <span data-ttu-id="abe28-1533">Se ha corregido un problema por el que, al insertar una imagen en un mensaje y, a continuación, guardar el mensaje como borrador, se cambiaba el tamaño de la imagen.</span><span class="sxs-lookup"><span data-stu-id="abe28-1533">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>


- <span data-ttu-id="abe28-1534">Se ha corregido un problema que provocaba que el cuerpo de un mensaje NDR cambiara de Unicode a ASCII después de editar el asunto.</span><span class="sxs-lookup"><span data-stu-id="abe28-1534">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>


- <span data-ttu-id="abe28-1535">Se ha corregido un problema por el que las fechas del minicalendario no se podían mostrar en negrita para los usuarios de Japón.</span><span class="sxs-lookup"><span data-stu-id="abe28-1535">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="abe28-1536">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1536">PowerPoint</span></span>

- <span data-ttu-id="abe28-1537">Se ha corregido un problema por el que el indicador de color de presencia de un usuario no se actualizaba en la galería de coautoría durante una sesión de coautoría en directo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1537">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>


- <span data-ttu-id="abe28-1538">Se ha corregido un problema por el que, al tratar de pegar código HTML en un área de texto en una diapositiva, el código se pegaba en un cuadro de texto creado en la parte superior de la diapositiva.</span><span class="sxs-lookup"><span data-stu-id="abe28-1538">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>


- <span data-ttu-id="abe28-1539">Se ha corregido un problema por el que, al seleccionar todas las diapositivas en la vista Moderador y, a continuación, salir de dicha vista mediante ALT+TAB, volver a la presentación con diapositivas y hacer clic en "Finalizar presentación", tenía lugar una excepción no controlada.</span><span class="sxs-lookup"><span data-stu-id="abe28-1539">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>


### <a name="project"></a><span data-ttu-id="abe28-1540">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-1540">Project</span></span>

- <span data-ttu-id="abe28-1541">Se ha corregido un problema que impedía guardar desde Project un PDF o XPS en una biblioteca de documentos de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="abe28-1541">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="abe28-1542">Se ha corregido un problema por el que los proyectos no se podían abrir en el cliente de escritorio de Project desde Project Web App si la dirección URL terminaba en .com.</span><span class="sxs-lookup"><span data-stu-id="abe28-1542">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="abe28-1543">Se ha corregido un problema que provocaba que Project se bloqueara al abrir determinados archivos XML.</span><span class="sxs-lookup"><span data-stu-id="abe28-1543">We fixed an issue where Project may crash when opening certain XML files.</span></span>


- <span data-ttu-id="abe28-1544">Se ha corregido un problema por el que los proyectos no se podían abrir en el cliente de escritorio de Project en Project Web App si la dirección URL finalizaba en ".com".</span><span class="sxs-lookup"><span data-stu-id="abe28-1544">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>


- <span data-ttu-id="abe28-1545">Se ha corregido un problema por el que si pegaba una tarea que tenía varias dependencias, no todas las dependencias se copiaban correctamente.</span><span class="sxs-lookup"><span data-stu-id="abe28-1545">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="abe28-1546">Se ha corregido un problema por el que la tarea seleccionada en el cuadro de diálogo de asignación de recursos no era la misma que la tarea seleccionada en la vista del panel de tareas.</span><span class="sxs-lookup"><span data-stu-id="abe28-1546">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="abe28-1547">Se ha corregido un problema que provocaba que el evento ProjectBeforeTaskChange no se activara al tener lugar un cambio en la tarea de resumen del proyecto, ya fuera en el campo de inicio o de tarea del proyecto.</span><span class="sxs-lookup"><span data-stu-id="abe28-1547">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>


- <span data-ttu-id="abe28-1548">Se ha corregido un problema por el que, si las tareas de duración fija estaban completas al 100 %, pero no se especificaba la fecha de finalización real, el porcentaje de finalización de la tarea se mostraba como inferior al 100 %.</span><span class="sxs-lookup"><span data-stu-id="abe28-1548">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

- <span data-ttu-id="abe28-1549">Se ha corregido un problema por el que una actualización o un restablecimiento de la línea base podía cambiar los recursos de trabajo o el costo presupuestado con fases temporales, y la línea base podía reflejar valores de presupuesto incorrectos.</span><span class="sxs-lookup"><span data-stu-id="abe28-1549">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>


- <span data-ttu-id="abe28-1550">Se ha corregido un problema que consistía en que los vínculos de Project Planner en entornos de Government Community Cloud habían sido deshabilitados.</span><span class="sxs-lookup"><span data-stu-id="abe28-1550">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>


- <span data-ttu-id="abe28-1551">Se ha corregido un problema por el que no se podía abrir un archivo de Project de una biblioteca de documentos de SharePoint si la biblioteca estaba en modo moderno.</span><span class="sxs-lookup"><span data-stu-id="abe28-1551">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>


### <a name="word"></a><span data-ttu-id="abe28-1552">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1552">Word</span></span>

- <span data-ttu-id="abe28-1553">Se ha corregido un problema por el que no funcionaba la opción de borrar el formato en el Panel Comentarios mediante el botón Borrar formato de la cinta de opciones de Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1553">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>


- <span data-ttu-id="abe28-1554">Se ha corregido un problema por el que el texto insertado en un archivo de gráficos vectoriales escalables (SVG) quedaba ilegible tras insertarlo en un archivo de Word, Excel o PowerPoint, guardar y cerrar el archivo y, a continuación, volver a abrirlo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1554">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>


- <span data-ttu-id="abe28-1555">Se ha corregido un problema que provocaba que otras aplicaciones que se ejecutaban en segundo plano comenzaran a parpadear al cambiar el tamaño de una tabla cuando la regla no se mostraba.</span><span class="sxs-lookup"><span data-stu-id="abe28-1555">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>


- <span data-ttu-id="abe28-1556">Se ha corregido un problema por el que, en el modo de coautoría, las respuestas a los comentarios no se mostraban en el panel de comentarios en ocasiones, pero eran visibles en el panel de revisiones.</span><span class="sxs-lookup"><span data-stu-id="abe28-1556">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>


- <span data-ttu-id="abe28-1557">Se ha corregido un problema en el modo de coautoría: cuando se produce un conflicto de fusión y el usuario ya ha elegido previamente descartar los cambios, ya no se muestra la opción que da a elegir entre guardar o descartar los cambios.</span><span class="sxs-lookup"><span data-stu-id="abe28-1557">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>


- <span data-ttu-id="abe28-1558">Se ha corregido un problema por el que el color de los hipervínculos HTML no se representaba correctamente.</span><span class="sxs-lookup"><span data-stu-id="abe28-1558">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>


- <span data-ttu-id="abe28-1559">Se ha corregido un problema por el que, si Word tenía una lista de más de 50 documentos abiertos con frecuencia, después de guardar y abrir un documento, se mostraba un historial de revisiones pese a que no se había modificado dicho documento.</span><span class="sxs-lookup"><span data-stu-id="abe28-1559">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>


- <span data-ttu-id="abe28-1560">Se ha corregido el problema con la opción de autoguardado durante la coautoría.</span><span class="sxs-lookup"><span data-stu-id="abe28-1560">We fixed in issue with autosave during coauthoring.</span></span>


- <span data-ttu-id="abe28-1561">Se ha corregido un problema por el que, al intentar guardar un archivo que contenía una macro con un nombre nuevo, este se guardaba con la extensión .docx y el nombre de archivo "WRO0004.docx", independientemente de lo que el usuario escribiera, lo que provocaba que el archivo no se pudiera volver a usar.</span><span class="sxs-lookup"><span data-stu-id="abe28-1561">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>


### <a name="office-suite"></a><span data-ttu-id="abe28-1562">Conjunto de programas de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-1562">Office Suite</span></span>

- <span data-ttu-id="abe28-1563">Un problema de temporización podía provocar un bloqueo al cerrar archivos de Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1563">A timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="abe28-1564">La corrección para este problema era asegurarse de que el servicio computase correctamente los productos agregados.</span><span class="sxs-lookup"><span data-stu-id="abe28-1564">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="abe28-1565">Se han filtrado los nuevos productos agregados (lo que garantiza que también se encuentren en la nueva configuración) y se han agregado al final de los ID de versión de producto existentes.</span><span class="sxs-lookup"><span data-stu-id="abe28-1565">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2006-july-09"></a><span data-ttu-id="abe28-1567">Versión 2006: 09 de julio</span><span class="sxs-lookup"><span data-stu-id="abe28-1567">Version 2006: July 09</span></span>
<span data-ttu-id="abe28-1568">*Versión 2006 (compilación 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1568">*Version 2006 (Build 13001.20384)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1570">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1570">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-1571">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1571">Excel</span></span>

- <span data-ttu-id="abe28-1572">**Realice una conexión PDF:** Conectar, importar, actualizar los datos de un PDF.</span><span class="sxs-lookup"><span data-stu-id="abe28-1572">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="abe28-1573">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1573">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="abe28-1574">**Crear variables para usar en fórmulas:** mejorar el rendimiento, la legibilidad y la composición con la función LET.</span><span class="sxs-lookup"><span data-stu-id="abe28-1574">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="abe28-1575">Esta función le permite crear variables con nombre en fórmulas nuevas o previamente existentes.</span><span class="sxs-lookup"><span data-stu-id="abe28-1575">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="abe28-1576">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1576">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="abe28-1577">Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span><span class="sxs-lookup"><span data-stu-id="abe28-1577">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="abe28-1578">**Métodos abreviados de teclado de Excel:** métodos abreviados de teclado actualizados para Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1578">**Keyboard shortcuts in Excel:** Updated keyboard shortcuts for Excel</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-1579">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1579">Outlook</span></span>

- <span data-ttu-id="abe28-1580">**Crear sondeos en Outlook con Sondeo rápido:** cree sondeos, recopile votos y vea los resultados rápidamente en un solo correo electrónico [Más información](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="abe28-1580">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="abe28-1581">**Mantenga la fidelidad de sus imágenes cuando las envíe como parte de un correo electrónico:** una nueva configuración de Outlook está disponible para limitar la compresión de imágenes cuando envía imágenes como parte de contenido del correo electrónico</span><span class="sxs-lookup"><span data-stu-id="abe28-1581">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1584">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1584">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="abe28-1585">Access</span><span class="sxs-lookup"><span data-stu-id="abe28-1585">Access</span></span>

- <span data-ttu-id="abe28-1586">Este problema se ha resuelto y ahora debería ser capaz de insertar correctamente tablas SQL vinculadas que incluyan un campo de identidad (por ejemplo, autonumeración) en Access.</span><span class="sxs-lookup"><span data-stu-id="abe28-1586">This issue is resolved, and you should expect to be able to successfully insert linked SQL tables that include an identity (e.g. autonumber) field into Access.</span></span>

### <a name="excel"></a><span data-ttu-id="abe28-1587">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1587">Excel</span></span>

- <span data-ttu-id="abe28-1588">Se ha corregido un bloqueo que podría producirse al intentar crear una conexión de datos si había cerrado la sesión de su cuenta.</span><span class="sxs-lookup"><span data-stu-id="abe28-1588">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-1589">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1589">Outlook</span></span>

- <span data-ttu-id="abe28-1590">Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.</span><span class="sxs-lookup"><span data-stu-id="abe28-1590">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="abe28-1591">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-1591">Office Suite</span></span>

- <span data-ttu-id="abe28-1592">Hemos modificado la versión AppV51 para solucionar una regresión de la AppV51 anterior.</span><span class="sxs-lookup"><span data-stu-id="abe28-1592">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="abe28-1593">El host de Office se bloqueaba en Windows al activar un complemento cuando el valor del registro TabProcGrowth era del tipo REG_SZ y tenía el valor "0".</span><span class="sxs-lookup"><span data-stu-id="abe28-1593">he office host was crashing in windows, when an add-in is being activated while the registry TabProcGrowth value is REG_SZ type and with value "0".</span></span>  <span data-ttu-id="abe28-1594">El valor de TabProcGrowth del registro puede encontrarse en una de estas cuatro rutas: HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER \Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE \Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER \Software\Policies\Microsoft\Internet Explorer\Main. Este cambio solucionaría el problema.</span><span class="sxs-lookup"><span data-stu-id="abe28-1594">That registry TabProcGrowth value can be under any one of 4 paths: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main This change would fix this issue.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2006-june-25"></a><span data-ttu-id="abe28-1596">Versión 2006: 25 de junio</span><span class="sxs-lookup"><span data-stu-id="abe28-1596">Version 2006: June 25</span></span>
<span data-ttu-id="abe28-1597">*Versión 2006 (compilación 13001.20266)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1597">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1599">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1599">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="abe28-1600">Visio</span><span class="sxs-lookup"><span data-stu-id="abe28-1600">Visio</span></span>

- <span data-ttu-id="abe28-1601">**Cree diagramas de Visio elegantes en Excel:** cree un diagrama de flujo o un organigrama basado en datos en una hoja de cálculo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1601">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart based on data in a worksheet.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1604">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1604">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="abe28-1605">Access</span><span class="sxs-lookup"><span data-stu-id="abe28-1605">Access</span></span>

- <span data-ttu-id="abe28-p203">Este problema se ha resuelto. Informe al equipo si tiene problemas con este proceso.</span><span class="sxs-lookup"><span data-stu-id="abe28-p203">This problem is now resolved. Please let the team know if you experience more issues with this process.</span></span>


### <a name="outlook"></a><span data-ttu-id="abe28-1608">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1608">Outlook</span></span>

- <span data-ttu-id="abe28-1609"><span style="display:inline !important;">Se ha corregido un problema que causaba que<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">la fecha de creación de&nbsp; datos adjuntos copiados en el sistema de archivos a través de la opción de arrastrar y soltar&nbsp; apareciera como el 1 de enero de 4501.</span></span><span class="sxs-lookup"><span data-stu-id="abe28-1609"><span style="display:inline !important;">Addresses an issue that caused users to see<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">the creation date of&nbsp; attachments that they copied to their file system via drag and drop getting&nbsp; set to January 1, 4501.</span></span></span><br>


- <span data-ttu-id="abe28-1610"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Se ha corregido un problema que provocaba que los usuarios de las mejoras del Calendario compartido vieran errores en el calendario.</span></span><span class="sxs-lookup"><span data-stu-id="abe28-1610"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span></span><br>


- <span data-ttu-id="abe28-1611"><span style="display:inline !important;">Se ha corregido un problema que provocaba que los usuarios de Outlook vieran continuamente un aviso para que ejecutaran la herramienta de Reparación de la bandeja de entrada.</span></span><span class="sxs-lookup"><span data-stu-id="abe28-1611"><span style="display:inline !important;">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span></span><br>


- <span data-ttu-id="abe28-1612"><span style="display:inline !important;">Se ha corregido un problema por el que la búsqueda de una característica en Sugerir una característica no devolvía resultados y no ofrecía al usuario ninguna opción para enviar una nueva característica.</span></span><span class="sxs-lookup"><span data-stu-id="abe28-1612"><span style="display:inline !important;">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span></span><br>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2006-june-18"></a><span data-ttu-id="abe28-1614">Versión 2006: 18 de junio</span><span class="sxs-lookup"><span data-stu-id="abe28-1614">Version 2006: June 18</span></span>
<span data-ttu-id="abe28-1615">*Versión 2006 (compilación 13001.20198)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1615">*Version 2006 (Build 13001.20198)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1617">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1617">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-1618">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1618">Excel</span></span>



- <span data-ttu-id="abe28-1619">**Guardar en Carpetas ancladas:** anclar tus carpetas hace que el almacenamiento de archivos de Office sea más fácil. Nuestros usuarios nos dijeron que querían tener más control sobre las carpetas disponibles al guardar un archivo nuevo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1619">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="abe28-1620">Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar.</span><span class="sxs-lookup"><span data-stu-id="abe28-1620">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="abe28-1621">Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.</span><span class="sxs-lookup"><span data-stu-id="abe28-1621">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="abe28-1622">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="abe28-1622">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="abe28-1623">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1623">PowerPoint</span></span>

- <span data-ttu-id="abe28-1624">**Guardar en Carpetas ancladas:** anclar tus carpetas hace que el almacenamiento de archivos de Office sea más fácil. Nuestros usuarios nos dijeron que querían tener más control sobre las carpetas disponibles al guardar un archivo nuevo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1624">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="abe28-1625">Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar.</span><span class="sxs-lookup"><span data-stu-id="abe28-1625">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="abe28-1626">Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.</span><span class="sxs-lookup"><span data-stu-id="abe28-1626">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="abe28-1627">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="abe28-1627">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="abe28-1628">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1628">Word</span></span>

- <span data-ttu-id="abe28-1629">**Guardar en Carpetas ancladas:** anclar tus carpetas hace que el almacenamiento de archivos de Office sea más fácil. Nuestros usuarios nos dijeron que querían tener más control sobre las carpetas disponibles al guardar un archivo nuevo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1629">**Save to Pinned Folders:** Pin your folders makes saving Office files easierWe received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="abe28-1630">Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar.</span><span class="sxs-lookup"><span data-stu-id="abe28-1630">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="abe28-1631">Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.</span><span class="sxs-lookup"><span data-stu-id="abe28-1631">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="abe28-1632">Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="abe28-1632">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1635">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1635">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-1636">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1636">Excel</span></span>

- <span data-ttu-id="abe28-1637">Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta al guardar en SharePoint o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="abe28-1637">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-1638">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1638">Outlook</span></span>

- <span data-ttu-id="abe28-1639">Se ha corregido un problema que provocaba que Ctrl + clic dejara de funcionar cuando se habilitaba la configuración de la nube.</span><span class="sxs-lookup"><span data-stu-id="abe28-1639">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>

### <a name="project"></a><span data-ttu-id="abe28-1640">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-1640">Project</span></span>

- <span data-ttu-id="abe28-1641">Se ha corregido un problema por el que una tarea marcada como completada al 100 % se mostraba por error no completada al 100 %.</span><span class="sxs-lookup"><span data-stu-id="abe28-1641">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2006-june-11"></a><span data-ttu-id="abe28-1643">Versión 2006: 11 de junio</span><span class="sxs-lookup"><span data-stu-id="abe28-1643">Version 2006: June 11</span></span>
<span data-ttu-id="abe28-1644">*Versión 2006 (compilación 13001.20144)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1644">*Version 2006 (Build 13001.20144)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1646">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1646">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="abe28-1647">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1647">PowerPoint</span></span>

- <span data-ttu-id="abe28-1648">**Mejor rendimiento de vídeos de Stream en PowerPoint:** hemos realizado mejoras en el rendimiento de la reproducción de los vídeos de Microsoft Stream para reducir el tiempo de carga de vídeo y crear una visualización más suave.</span><span class="sxs-lookup"><span data-stu-id="abe28-1648">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="abe28-1649">Use los vídeos corporativos de Microsoft Stream para crear presentaciones mejoradas.</span><span class="sxs-lookup"><span data-stu-id="abe28-1649">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="word"></a><span data-ttu-id="abe28-1650">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1650">Word</span></span>

- <span data-ttu-id="abe28-1651">**Retener texto en vectores:** ahora puede conservar el texto en mapas, gráficos y otros vectores de SVG al convertir estos objetos en Excel, Word y PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="abe28-1651">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1654">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1654">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-1655">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1655">Excel</span></span>

- <span data-ttu-id="abe28-1656">Se ha corregido un problema por el que Excel se cerraba ocasionalmente al utilizar OneDrive.</span><span class="sxs-lookup"><span data-stu-id="abe28-1656">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>

- <span data-ttu-id="abe28-1657">Se ha corregido un problema por el que los valores personalizados en el eje del gráfico no se aplicaban correctamente.</span><span class="sxs-lookup"><span data-stu-id="abe28-1657">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>

- <span data-ttu-id="abe28-1658">Se ha corregido un problema por el que las hojas de cálculo que contienen varias fórmulas con nombres definidos tardaban más en guardarse.</span><span class="sxs-lookup"><span data-stu-id="abe28-1658">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="abe28-1659">Hemos corregido un problema que provocaba que los nombres de las impresoras se duplicaran en la lista de impresoras disponibles.</span><span class="sxs-lookup"><span data-stu-id="abe28-1659">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span>

- <span data-ttu-id="abe28-1660">Hemos corregido un problema para que los usuarios tengan un mejor rendimiento al eliminar las columnas combinadas.</span><span class="sxs-lookup"><span data-stu-id="abe28-1660">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>

- <span data-ttu-id="abe28-1661">Se ha corregido un problema por el que aparecía el mensaje de error "No se puede cerrar el libro debido a que otro libro hace referencia a él" si los complementos se cargaban en orden alfabético en lugar de en un orden especificado por el usuario.</span><span class="sxs-lookup"><span data-stu-id="abe28-1661">We fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="abe28-1662">Se ha corregido un problema en el que administrar fuentes entre Excel y algunas aplicaciones tecnológicas de asistencia de terceros causaba problemas de memoria.</span><span class="sxs-lookup"><span data-stu-id="abe28-1662">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>

- <span data-ttu-id="abe28-1663">Se ha corregido un problema por el que al hacer clic en un hipervínculo marcado en el mismo libro hacía que el libro se ocultara.</span><span class="sxs-lookup"><span data-stu-id="abe28-1663">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="abe28-1664">Se ha corregido un problema por el que algunos vínculos de un gráfico copiado y pegado usaban direcciones de unidad asignadas, en lugar de direcciones universales.</span><span class="sxs-lookup"><span data-stu-id="abe28-1664">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="abe28-1665">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="abe28-1665">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

- <span data-ttu-id="abe28-1666">Se ha corregido un problema por el que Excel se bloqueaba cuando los complementos solicitaban elementos de host en hojas de cálculo que tuvieran formas con bloqueos noSelect.</span><span class="sxs-lookup"><span data-stu-id="abe28-1666">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="abe28-1667">Se ha corregido un problema por el que Excel se bloqueaba al intentar insertar tablas dinámicas en una hoja de gráfico.</span><span class="sxs-lookup"><span data-stu-id="abe28-1667">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-1668">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1668">Outlook</span></span>

- <span data-ttu-id="abe28-1669">Se ha corregido un problema por el que la ventana del Editor de métodos de entrada (IME) se superponía al texto subyacente escrito mediante el IME cuando se usaban varios monitores con resoluciones diferentes.</span><span class="sxs-lookup"><span data-stu-id="abe28-1669">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="abe28-1670">Se ha corregido un problema que causaba un bloqueo cuando se visualizaba una plantilla mientras se redactaba un nuevo mensaje de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="abe28-1670">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>

- <span data-ttu-id="abe28-1671">Se ha corregido un problema por el que los usuarios no podían intercambiar carpetas públicas de Exchange 2010 después de la versión 1911 de Outlook.</span><span class="sxs-lookup"><span data-stu-id="abe28-1671">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>

- <span data-ttu-id="abe28-1672">Se ha corregido un problema por el que se desactivaba el botón de Categorizar para los calendarios de grupo en la cinta de opciones de Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1672">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="abe28-1673">Se ha corregido un problema por el que Outlook no pudo habilitar consejos de directiva para la Protección de pérdida de datos para usuarios que pagaron por el servicio con planes M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="abe28-1673">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="abe28-1674">Se ha corregido un problema que provocaba que Outlook se bloqueara en algunas compilaciones de Windows.</span><span class="sxs-lookup"><span data-stu-id="abe28-1674">Addressed an issue that caused Outlook to crash on some Windows builds.</span></span>

- <span data-ttu-id="abe28-1675">Se ha corregido un problema por el que los usuarios no pudieron compartir un calendario con un usuario invitado.</span><span class="sxs-lookup"><span data-stu-id="abe28-1675">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

- <span data-ttu-id="abe28-1676">Se ha corregido un problema en el que los usuarios veían los elementos de calendario que pasaban de la medianoche como Eventos de todo el día.</span><span class="sxs-lookup"><span data-stu-id="abe28-1676">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>

- <span data-ttu-id="abe28-1677">Se ha corregido un problema por el que la lista desplegable en las propiedades de carpeta del Archivo en línea no aparecía en monitores con un alto nivel de ppp.</span><span class="sxs-lookup"><span data-stu-id="abe28-1677">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>

- <span data-ttu-id="abe28-1678">Se ha corregido un problema por el que el evento Folder.BeforeItemMove no se activaba correctamente cuando un usuario movía elementos entre carpetas.</span><span class="sxs-lookup"><span data-stu-id="abe28-1678">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>

- <span data-ttu-id="abe28-1679">Se ha corregido un problema por el que Outlook se bloqueaba cuando dos complementos agregaban un botón al mismo grupo en la cinta de opciones.</span><span class="sxs-lookup"><span data-stu-id="abe28-1679">We fixed an issue where Outlook crashed when two add-ins added a button to the same group in the ribbon.</span></span>

- <span data-ttu-id="abe28-1680">Se ha corregido un problema que provocaba un error en Outlook al trabajar con hipervínculos en mensajes de correo electrónico de texto sin formato.</span><span class="sxs-lookup"><span data-stu-id="abe28-1680">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>

- <span data-ttu-id="abe28-1681">Se ha corregido un problema que provocaba que Outlook no pudiera analizar nombres de archivo largos codificados con RFC2231.</span><span class="sxs-lookup"><span data-stu-id="abe28-1681">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>

- <span data-ttu-id="abe28-1682">Se ha corregido un problema que provocaba que los usuarios de Outlook experimentaran interrupciones intermitentes al usar lectores de pantalla.</span><span class="sxs-lookup"><span data-stu-id="abe28-1682">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

- <span data-ttu-id="abe28-1683">Se ha corregido un problema que hacía que los usuarios con contactos en conflicto experimentaran bloqueos en Outlook.</span><span class="sxs-lookup"><span data-stu-id="abe28-1683">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="abe28-1684">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1684">PowerPoint</span></span>

- <span data-ttu-id="abe28-1685">Se ha corregido un problema al abrir archivos configurados por el servidor con autenticación basada en formularios.</span><span class="sxs-lookup"><span data-stu-id="abe28-1685">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>

- <span data-ttu-id="abe28-1686">Se ha corregido un problema por el que los archivos de PowerPoint con gráficos o libros incrustados podrían causar errores al guardar el archivo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1686">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>

- <span data-ttu-id="abe28-1687">Se ha corregido un problema en el que al acercar y alejar el área de presentación se daba una separación entre el recuadro de selección ampliado y el puntero del mouse.</span><span class="sxs-lookup"><span data-stu-id="abe28-1687">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="abe28-1688">Se ha corregido un problema que hacía que las diapositivas no se centraran después de usar la rueda del mouse para hacer zoom.</span><span class="sxs-lookup"><span data-stu-id="abe28-1688">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

- <span data-ttu-id="abe28-1689">Hemos corregido un problema por el que la revisión ortográfica y los métodos abreviados del teclado no funcionaban de manera esperada al usar un teclado de Suiza (QWERTZ) en inglés.</span><span class="sxs-lookup"><span data-stu-id="abe28-1689">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

- <span data-ttu-id="abe28-1690">Se ha corregido un problema por el que un panel de Comentarios cerrado por el usuario se abría automáticamente de nuevo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1690">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>

- <span data-ttu-id="abe28-1691">Se ha corregido un problema por el que el editor de diapositivas de una diapositiva se superponía a la siguiente diapositiva.</span><span class="sxs-lookup"><span data-stu-id="abe28-1691">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="abe28-1692">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-1692">Project</span></span>

- <span data-ttu-id="abe28-1693">Se ha corregido un problema por el que el evento ProjectBeforeTaskChange no se activaba al darse un cambio en la tarea de resumen del proyecto: ya sea en el campo de inicio o tarea del proyecto.</span><span class="sxs-lookup"><span data-stu-id="abe28-1693">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="abe28-1694">Se ha corregido un problema por el que una tarea marcada como completada al 100 % se mostraba por error no completada al 100 %.</span><span class="sxs-lookup"><span data-stu-id="abe28-1694">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="abe28-1695">Se ha corregido un problema por el que Project se bloqueaba después de hacer clic en Opciones.</span><span class="sxs-lookup"><span data-stu-id="abe28-1695">We fixed an issue where Project would crash after clicking on Options.</span></span>

- <span data-ttu-id="abe28-1696">Se ha corregido un problema que impedía que las tareas huérfanas se eliminaran o reasignarán después de eliminar su plan primario.</span><span class="sxs-lookup"><span data-stu-id="abe28-1696">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="visio"></a><span data-ttu-id="abe28-1697">Visio</span><span class="sxs-lookup"><span data-stu-id="abe28-1697">Visio</span></span>

- <span data-ttu-id="abe28-1698">Se ha corregido la regresión en el código dependiente.</span><span class="sxs-lookup"><span data-stu-id="abe28-1698">There was regression in dependent code which has been fixed.</span></span> <span data-ttu-id="abe28-1699">Ahora, las imágenes se representan en los servicios de Visio que se ejecutan en SharePoint local.</span><span class="sxs-lookup"><span data-stu-id="abe28-1699">Now, the images are getting rendered in Visio services running on SharePoint Onprem.</span></span>

### <a name="word"></a><span data-ttu-id="abe28-1700">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1700">Word</span></span>

- <span data-ttu-id="abe28-1701">Se ha corregido un problema por el que las marcas de hora en los paneles de comentarios no se basaban en la hora de la configuración regional del sistema.</span><span class="sxs-lookup"><span data-stu-id="abe28-1701">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>

- <span data-ttu-id="abe28-1702">Se ha resuelto un problema al abrir documentos de Word desde la entrega de documentos personalizados (aspx) cuando la dirección URL contenía un componente de consulta.</span><span class="sxs-lookup"><span data-stu-id="abe28-1702">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="abe28-1703">Se ha corregido un problema por el que no se mostraba un texto copiado y pegado en un panel de comentarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-1703">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>

- <span data-ttu-id="abe28-1704">Se ha corregido un problema por el que los hipervínculos en los comentarios no funcionaban.</span><span class="sxs-lookup"><span data-stu-id="abe28-1704">We fixed an issue where hyperlinks in comments weren’t working.</span></span>

- <span data-ttu-id="abe28-1705">Se ha corregido un problema en el que al acercar y alejar el área de presentación se daba una separación entre el recuadro de selección ampliado y el puntero del mouse.</span><span class="sxs-lookup"><span data-stu-id="abe28-1705">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="abe28-1706">Se ha corregido un problema por el que los comentarios entre la aplicación web y la aplicación de escritorio no estaban sincronizados.</span><span class="sxs-lookup"><span data-stu-id="abe28-1706">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

- <span data-ttu-id="abe28-1707">Se ha corregido un problema en el que las burbujas de sugerencias de comentarios aparecían borrosas al 100 % de zoom.</span><span class="sxs-lookup"><span data-stu-id="abe28-1707">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>

- <span data-ttu-id="abe28-1708">Hemos corregido un problema en el que agregar un nuevo comentario en un documento en blanco no pasaba nada.</span><span class="sxs-lookup"><span data-stu-id="abe28-1708">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>

- <span data-ttu-id="abe28-1709">Se ha corregido un problema por el que no funcionaba pegar HTML en WordMail para Calendario.</span><span class="sxs-lookup"><span data-stu-id="abe28-1709">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>

- <span data-ttu-id="abe28-1710">Se ha corregido un problema por el que responder a un comentario en una sesión de coautoría podía bloquear Word.</span><span class="sxs-lookup"><span data-stu-id="abe28-1710">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

- <span data-ttu-id="abe28-1711">Hemos corregido un problema que haría que la aplicación se bloqueara cuando se insertara o actualizara un índice en un documento que contuviera más de cien entradas.</span><span class="sxs-lookup"><span data-stu-id="abe28-1711">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>

- <span data-ttu-id="abe28-1712">Se ha corregido un problema por el que habilitar la directiva de Word 2007 y, luego, los documentos binarios y de plantillas podía causar errores en ciertos casos de coautoría.</span><span class="sxs-lookup"><span data-stu-id="abe28-1712">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>

- <span data-ttu-id="abe28-1713">Hemos corregido un problema que provocaba que los archivos con valores XML personalizados se abrieran muy despacio.</span><span class="sxs-lookup"><span data-stu-id="abe28-1713">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

- <span data-ttu-id="abe28-1714">Se ha corregido un problema por el que no se abrían los archivos con nombres de ruta largos (mayores que 32 000 caracteres) y no se mostraba un mensaje de error adecuado.</span><span class="sxs-lookup"><span data-stu-id="abe28-1714">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="abe28-1715">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-1715">Office Suite</span></span>

- <span data-ttu-id="abe28-1716">Hemos estudiado y resuelto el problema por el que una implementación de Office 365 ProPlus a través de Intune se pausaba después de apagar el SO.</span><span class="sxs-lookup"><span data-stu-id="abe28-1716">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

- <span data-ttu-id="abe28-1717">Hemos corregido un problema en Visual Basic para las aplicaciones de Microsoft Office, por el que la aplicación de Office consideraba como corruptos ciertos proyectos de VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre o la ruta de la biblioteca.</span><span class="sxs-lookup"><span data-stu-id="abe28-1717">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="abe28-1718">Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.</span><span class="sxs-lookup"><span data-stu-id="abe28-1718">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2005-june-08"></a><span data-ttu-id="abe28-1720">Versión 2005: 8 de junio</span><span class="sxs-lookup"><span data-stu-id="abe28-1720">Version 2005: June 08</span></span>
<span data-ttu-id="abe28-1721">*Versión 2005 (compilación 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1721">*Version 2005 (Build 12827.20336)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1723">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1723">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="abe28-1724">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1724">PowerPoint</span></span>

- <span data-ttu-id="abe28-1725">Se ha corregido un problema en el cuadro de diálogo Reemplazar fuente, donde la lista desplegable Reemplazar fuente solo mostraba las fuentes de la presentación, en lugar de las fuentes instaladas en el sistema.</span><span class="sxs-lookup"><span data-stu-id="abe28-1725">We have fixed an issue with replace fonts dialog where replace font dropdown only shows fonts within the presentation instead of fonts installed on the system.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2005-june-04"></a><span data-ttu-id="abe28-1727">Versión 2005: 4 de junio</span><span class="sxs-lookup"><span data-stu-id="abe28-1727">Version 2005: June 04</span></span>
<span data-ttu-id="abe28-1728">*Versión 2005 (compilación 12827.20320)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1728">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1730">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1730">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="abe28-1731">Access</span><span class="sxs-lookup"><span data-stu-id="abe28-1731">Access</span></span>

- <span data-ttu-id="abe28-1732">**Manténgase al día con las horas. El tipo de datos Fecha y hora extendida tiene mayor precisión.:** Presentamos un tipo de datos nuevo y mejorado.</span><span class="sxs-lookup"><span data-stu-id="abe28-1732">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="abe28-1733">Para mejorar la compatibilidad de la sintaxis con SQL y la precisión y el nivel de detalle en los registros que incluyen fechas y horas, estamos implementando el tipo de datos DateTime2 en Access.</span><span class="sxs-lookup"><span data-stu-id="abe28-1733">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="abe28-1734">Este tipo de datos de fecha y hora adicional incluirá un intervalo de fechas mayor (de 0001-01-01 a 9999-12-31), con mayor precisión de tiempo (nanosegundos, en lugar de segundos) en el que se podrán ofrecer y realizar cálculos.</span><span class="sxs-lookup"><span data-stu-id="abe28-1734">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="abe28-1735">Para habilitarlo, seleccione Nuevo campo > Fecha y hora extendida.</span><span class="sxs-lookup"><span data-stu-id="abe28-1735">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="abe28-1736">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1736">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="abe28-1737">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1737">Excel</span></span>

- <span data-ttu-id="abe28-1738">**Crear tablas dinámicas de conjuntos de datos en Power BI desde Excel:** puede crear tablas dinámicas en Excel conectadas a los conjuntos de datos almacenados en Power BI con tan solo unos clics.</span><span class="sxs-lookup"><span data-stu-id="abe28-1738">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="abe28-1739">Así, podrá obtener lo mejor de las tablas dinámicas y de Power BI.</span><span class="sxs-lookup"><span data-stu-id="abe28-1739">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="abe28-1740">Calcule, resuma y analice los conjuntos de datos seguros de Power BI con las tablas dinámicas de Excel.</span><span class="sxs-lookup"><span data-stu-id="abe28-1740">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-1741">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1741">Outlook</span></span>

- <span data-ttu-id="abe28-1742">**Opción para volver a abrir rápidamente los elementos de la sesión anterior de Outlook:** hemos agregado una opción para volver a abrir rápidamente los elementos de una sesión anterior de Outlook.</span><span class="sxs-lookup"><span data-stu-id="abe28-1742">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1745">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1745">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="abe28-1746">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1746">PowerPoint</span></span>

- <span data-ttu-id="abe28-1747">Hemos corregido un bloqueo cuando el usuario tiene comentarios modernos y heredados en un archivo, lo que provoca una actualización de los comentarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-1747">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="abe28-1748">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-1748">Office Suite</span></span>

- <span data-ttu-id="abe28-1749">Hemos resuelto el problema de la tasa de error de ValidateInstall estableciendo la validación de instalación del Complemento de Bing como verdadera de forma predeterminada y considerando el éxito de devolución de MSI como una instalación con éxito.</span><span class="sxs-lookup"><span data-stu-id="abe28-1749">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2005-may-29"></a><span data-ttu-id="abe28-1751">Versión 2005: 29 de mayo</span><span class="sxs-lookup"><span data-stu-id="abe28-1751">Version 2005: May 29</span></span>
<span data-ttu-id="abe28-1752">*Versión 2005 (compilación 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1752">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1754">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1754">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="abe28-1755">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1755">Excel</span></span>

- <span data-ttu-id="abe28-1756">**Vista de hoja:** ordenar y filtrar cuando colabore con otras personas en la versión de escritorio de Excel.</span><span class="sxs-lookup"><span data-stu-id="abe28-1756">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-1757">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1757">Outlook</span></span>

- <span data-ttu-id="abe28-1758">**Se agregaron más botones a las notificaciones del sistema de Outlook:** los botones de Acción rápida aparecen ahora en las notificaciones del sistema de Outlook cuando se ejecuta Outlook en Windows 10.</span><span class="sxs-lookup"><span data-stu-id="abe28-1758">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1761">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1761">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="abe28-1762">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1762">Outlook</span></span>

- <span data-ttu-id="abe28-1763">Se ha corregido un problema que provocaba que los usuarios de las versiones de Windows 10 Server vieran la advertencia: "Estado de antivirus: no válido".</span><span class="sxs-lookup"><span data-stu-id="abe28-1763">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="abe28-1764">Esta versión de Windows admite la detección del antivirus, pero no se encontró ninguno a pesar de tener un antivirus correctamente instalado".</span><span class="sxs-lookup"><span data-stu-id="abe28-1764">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="abe28-1765">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-1765">Office Suite</span></span>

- <span data-ttu-id="abe28-p212">El host de Office se bloqueaba en Windows, cuando se activaba un complemento si la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth estaba establecida en cero. Este cambio solucionaría el problema.</span><span class="sxs-lookup"><span data-stu-id="abe28-p212">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero. This change would fix this issue.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2005-may-21"></a><span data-ttu-id="abe28-1769">Versión 2005: 21 de mayo</span><span class="sxs-lookup"><span data-stu-id="abe28-1769">Version 2005: May 21</span></span>
<span data-ttu-id="abe28-1770">*Versión 2005 (compilación 12827.20210)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1770">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)




[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1774">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1774">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-1775">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1775">Excel</span></span>

- <span data-ttu-id="abe28-1776">Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.</span><span class="sxs-lookup"><span data-stu-id="abe28-1776">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="abe28-1777">En algunos casos, al hacer clic en un hipervínculo que dirige a un lugar del mismo libro, el libro queda oculto.</span><span class="sxs-lookup"><span data-stu-id="abe28-1777">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="abe28-1778">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1778">Outlook</span></span>

- <span data-ttu-id="abe28-1779">Se ha corregido un problema con el evento de auditoría CLP para la etiqueta de responder o reenviar.</span><span class="sxs-lookup"><span data-stu-id="abe28-1779">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="abe28-1780">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al enviar comentarios desde una Notificación de administrador.</span><span class="sxs-lookup"><span data-stu-id="abe28-1780">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2005-may-14"></a><span data-ttu-id="abe28-1782">Versión 2005: 14 de mayo</span><span class="sxs-lookup"><span data-stu-id="abe28-1782">Version 2005: May 14</span></span>
<span data-ttu-id="abe28-1783">*Versión 2005 (compilación 12827.20160)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1783">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1785">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1785">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-1786">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1786">Excel</span></span>

- <span data-ttu-id="abe28-1787">**Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.</span><span class="sxs-lookup"><span data-stu-id="abe28-1787">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="abe28-1788">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1788">PowerPoint</span></span>

- <span data-ttu-id="abe28-1789">**No es necesario hacer clic: sus miniauriculares tienen que cubrir lo siguiente:** Usar sus Surface Earbuds para controlar sus presentaciones de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="abe28-1789">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="abe28-1790">Importante: Debe emparejar sus Surface Earbuds en la aplicación Surface Audio para Windows 10 para poder usar gestos para controlar las presentaciones.</span><span class="sxs-lookup"><span data-stu-id="abe28-1790">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="abe28-1791">Aquí encontrará instrucciones para empezar a usar la aplicación Surface Audio en Windows 10.</span><span class="sxs-lookup"><span data-stu-id="abe28-1791">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="abe28-1792">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1792">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="abe28-1793">**Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.</span><span class="sxs-lookup"><span data-stu-id="abe28-1793">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="abe28-1794">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1794">Word</span></span>

- <span data-ttu-id="abe28-1795">**Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.</span><span class="sxs-lookup"><span data-stu-id="abe28-1795">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1798">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1798">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="abe28-1799">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1799">Excel</span></span>

- <span data-ttu-id="abe28-1800">Se aumentó el tamaño de los controles de edición de referencia de celda en el cuadro de diálogo Barras de error personalizadas utilizado con gráficos.</span><span class="sxs-lookup"><span data-stu-id="abe28-1800">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="abe28-1801">Se ha corregido un problema por el que las tablas de datos de los gráficos podían representar incorrectamente los valores de un eje de fechas.</span><span class="sxs-lookup"><span data-stu-id="abe28-1801">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="abe28-1802">Se ha corregido un problema por el que los saltos de página no se podían deshabilitar después de ir al diseño de página o la vista previa de salto de página</span><span class="sxs-lookup"><span data-stu-id="abe28-1802">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="abe28-1803">Se ha corregido un problema por el que los estilos de línea de los gráficos podían perderse tras ocultar y mostrar columnas con datos de series.</span><span class="sxs-lookup"><span data-stu-id="abe28-1803">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="abe28-1804">Se ha corregido un problema por el que insertar una columna en una lista filtrada llevaba más tiempo de lo esperado.</span><span class="sxs-lookup"><span data-stu-id="abe28-1804">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="abe28-1805">Corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.</span><span class="sxs-lookup"><span data-stu-id="abe28-1805">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="abe28-1806">Se ha corregido un problema que hacía que el vínculo externo dejara de funcionar después de que se volviera a abrir el archivo si su ruta de acceso era demasiado larga.</span><span class="sxs-lookup"><span data-stu-id="abe28-1806">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="abe28-1807">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="abe28-1807">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="abe28-1808">Application.Evaluate (VBA) no funcionaba para funciones definidas por el usuario en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="abe28-1808">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="abe28-1809">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="abe28-1809">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="abe28-1810">Este cambio corrige un problema que hacía que la información de formato condicional (CF) no se guardase correctamente en los archivos XLSB.</span><span class="sxs-lookup"><span data-stu-id="abe28-1810">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="abe28-1811">Este cambio corrige un problema en el que el valor de la línea de tendencia del gráfico R-cuadrado (en el caso de la intersección forzada y) era incorrecto aunque la función de ESTIMACIÓN devuelva el valor correcto.</span><span class="sxs-lookup"><span data-stu-id="abe28-1811">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="abe28-1812">Este cambio arregla un problema en el que no siempre se guardaba el formato de la línea de tendencia de los gráficos personalizados.</span><span class="sxs-lookup"><span data-stu-id="abe28-1812">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="abe28-1813">Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "Libro compartido" heredado.</span><span class="sxs-lookup"><span data-stu-id="abe28-1813">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="abe28-1814">Se ha corregido el problema por el que el formato personalizado de un gráfico dinámico podía no guardarse si estaba habilitada la opción "Invertir si es negativo".</span><span class="sxs-lookup"><span data-stu-id="abe28-1814">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="abe28-1815">Se ha corregido un problema por el que el formato personalizado de un único punto de datos de un gráfico dinámico no se guardaba si estaba seleccionada la opción "invertir si es negativo".</span><span class="sxs-lookup"><span data-stu-id="abe28-1815">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="abe28-1816">Este cambio corrige un problema por el que el carácter "@" cargado en un archivo CSV causaba que la cadena tras el carácter "@" se convirtiera en una fórmula.</span><span class="sxs-lookup"><span data-stu-id="abe28-1816">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="abe28-1817">Se ha corregido un problema por el que los valores decimales de la función SECUENCIA no se redondeaban correctamente.</span><span class="sxs-lookup"><span data-stu-id="abe28-1817">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="abe28-1818">OneNote</span><span class="sxs-lookup"><span data-stu-id="abe28-1818">OneNote</span></span>

- <span data-ttu-id="abe28-1819">Corregido un problema en el que los saltos de línea se almacenaban como pestañas verticales.</span><span class="sxs-lookup"><span data-stu-id="abe28-1819">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-1820">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1820">Outlook</span></span>

- <span data-ttu-id="abe28-1821">Soluciona un problema que hacía que los usuarios no pudieran agregar un grupo de contactos personal como asistente de la reunión.</span><span class="sxs-lookup"><span data-stu-id="abe28-1821">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="abe28-1822">Corregido un problema por el que se desactivaba el botón de Categorizar para los calendarios de grupo en la cinta de opciones de Office.</span><span class="sxs-lookup"><span data-stu-id="abe28-1822">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="abe28-1823">Se ha corregido un problema que provocaba que Outlook se bloqueara al abrir archivos .msg y .oft guardados localmente después de una actualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="abe28-1823">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="abe28-1824">Se ha solucionado un problema por el que los clientes de las empresas con carpetas de grupo no implementadas o que no funcionaban, hacían que Outlook mostrara un mensaje de "no responde".</span><span class="sxs-lookup"><span data-stu-id="abe28-1824">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="abe28-1825">Corrige un problema por el que los safelinks muy largos en los que los usuarios hacían clic en el cliente de escritorio de Outlook no se podían cargar debido a un truncamiento.</span><span class="sxs-lookup"><span data-stu-id="abe28-1825">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="abe28-1826">Se ha corregido un problema por el que las carpetas de Outlook con nombres que contenían caracteres DBCS (conjunto de caracteres de doble byte) desaparecían intermitentemente al sincronizar con el servidor.</span><span class="sxs-lookup"><span data-stu-id="abe28-1826">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="abe28-1827">Esto sucedía si Outlook estaba configurado con una cuenta IMAP y se ejecutaba en un sistema con la configuración regional configurada en japonés.</span><span class="sxs-lookup"><span data-stu-id="abe28-1827">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="abe28-1828">Se solucionó un problema que hacía que las reglas de eliminación creadas para los buzones que no fueran el buzón principal del usuario dejaran de ser válidas.</span><span class="sxs-lookup"><span data-stu-id="abe28-1828">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="abe28-1829">Se solucionó un problema que hacía que los datos adjuntos se perdieran al reenviar un mensaje cifrado.</span><span class="sxs-lookup"><span data-stu-id="abe28-1829">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="abe28-1830">Se solucionó un problema que provocaba que las reuniones para las que faltan más de 2 meses no mostraran un tema de reunión en el Asistente de programación.</span><span class="sxs-lookup"><span data-stu-id="abe28-1830">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="abe28-1831">Se ha corregido un problema que hacía que los usuarios vieran truncado el cuerpo del mensaje al reenviar mensajes HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="abe28-1831">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="abe28-1832">Se agregó la capacidad de aplicar la configuración de firma predeterminada de S/MIME a través de la directiva de grupo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1832">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="abe28-1833">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1833">PowerPoint</span></span>

- <span data-ttu-id="abe28-1834">Se ha corregido un problema por el que el borrador de los comentarios dejaba de estar disponible si un usuario creaba un comentario sin publicarlo, cerraba el panel de comentarios, abría una nueva ventana, se desplazaba por varias diapositivas, cerraba la ventana y volvía a abrir el panel de comentarios en la presentación original.</span><span class="sxs-lookup"><span data-stu-id="abe28-1834">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="abe28-1835">Se ha solucionado un problema por el que al pasar el ratón por encima del símbolo del asterisco (\*) no aparecía el nombre de usuario y la fecha de la última persona que actualizó el documento.</span><span class="sxs-lookup"><span data-stu-id="abe28-1835">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="abe28-1836">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-1836">Project</span></span>

- <span data-ttu-id="abe28-1837">Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se activa un evento ProjectBeforeTaskChange adicional.</span><span class="sxs-lookup"><span data-stu-id="abe28-1837">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="abe28-1838">Se solucionó un problema por el cual Proyect podía bloquearse al cambiar el campo de estado del tablero en un proyecto que conectado a una lista de tareas de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="abe28-1838">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="abe28-1839">Corregido un problema por el que Project puede bloquearse al guardar proyectos creados con versiones anteriores de Project.</span><span class="sxs-lookup"><span data-stu-id="abe28-1839">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="abe28-1840">Se ha corregido un problema por el que, si Project estaba conectado a Project Web App y el separador decimal era una coma, el método TaskDependencies Add producía un error al agregar retardo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1840">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="abe28-1841">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1841">Word</span></span>

- <span data-ttu-id="abe28-1842">Se ha corregido un problema por el que la inserción de comentarios en un documento en el modo de colaboración no funcionaba en ocasiones.</span><span class="sxs-lookup"><span data-stu-id="abe28-1842">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="abe28-1843">Este cambio corrige un problema por el que la tarjeta de contactos parpadeaba si se hacía clic en la mención @.</span><span class="sxs-lookup"><span data-stu-id="abe28-1843">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="abe28-p215">Al habilitar la opción "Mostrar marcadores" no se mostrarán los marcadores. Este error se ha corregido.</span><span class="sxs-lookup"><span data-stu-id="abe28-p215">Enabling the option "Show bookmarks" would not display bookmarks. This has been fixed.</span></span>

- <span data-ttu-id="abe28-p216">Se ha corregido el problema por el que al cerrar un documento con borrador de comentarios se preguntaba al usuario si deseaba cerrar el documento sin guardar los comentarios del borrador. Al cancelar la solicitud, se cerraba el documento en lugar de quedar abierto.</span><span class="sxs-lookup"><span data-stu-id="abe28-p216">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments. Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="abe28-1848">Se ha corregido un problema al copiar y pegar títulos.</span><span class="sxs-lookup"><span data-stu-id="abe28-1848">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="abe28-1849">Se ha corregido un problema por el que al traducir un comentario publicado se producía el error "Error al insertar el texto traducido".</span><span class="sxs-lookup"><span data-stu-id="abe28-1849">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="abe28-1850">Este cambio soluciona un problema por el que el texto con hipervínculos podía no aparecer si la opción "Mostrar códigos de campo en lugar de sus valores" estaba activada.</span><span class="sxs-lookup"><span data-stu-id="abe28-1850">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="abe28-p217">En la Vista web o en el lector inmersivo, al hacer clic en una sugerencia se desplazaba a la parte superior incluso aunque ya estuviera a la vista. Este error se ha corregido.</span><span class="sxs-lookup"><span data-stu-id="abe28-p217">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view. This has been fixed.</span></span>

- <span data-ttu-id="abe28-1853">Se ha corregido un problema por el que al intentar guardar un archivo que contenía una macro con un nombre nuevo, este se guardaba con la extensión. docx y el nombre de archivo WRO0004.docx, independientemente de lo que el usuario escribiera, lo que hacía que el archivo no se pudiera volver a usar.</span><span class="sxs-lookup"><span data-stu-id="abe28-1853">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="abe28-1854">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-1854">Office Suite</span></span>

- <span data-ttu-id="abe28-1855">Cuando se asignaba a un usuario una directiva que lo llevaba a Teams solo, aún se podía usar el complemento para Outlook de Skype Empresarial para programar reuniones.</span><span class="sxs-lookup"><span data-stu-id="abe28-1855">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="abe28-1856">Tras esta actualización, ya no se podrán programar reuniones de Skype Empresarial después de que el cliente lea la directiva en la que se indica que el usuario participa en Teams solo y entra en la reunión como Unirse solo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1856">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="abe28-1857">Además, el complemento de Outlook para Skype Empresarial no se activará durante el inicio si ve que el cliente de Skype Empresarial se encuentra en modo de Unirse solo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1857">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="abe28-1858">Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.</span><span class="sxs-lookup"><span data-stu-id="abe28-1858">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="abe28-1859">Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.</span><span class="sxs-lookup"><span data-stu-id="abe28-1859">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2004-may-11"></a><span data-ttu-id="abe28-1861">Versión 2004: 11 de mayo</span><span class="sxs-lookup"><span data-stu-id="abe28-1861">Version 2004: May 11</span></span>
<span data-ttu-id="abe28-1862">*Versión 2004 (compilación 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1862">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1864">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1864">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-1865">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1865">Excel</span></span>

- <span data-ttu-id="abe28-1866">**Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.</span><span class="sxs-lookup"><span data-stu-id="abe28-1866">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-1867">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1867">Outlook</span></span>

- <span data-ttu-id="abe28-1868">**Vínculos mejorados en el correo electrónico:** al incluir un vínculo a un archivo, la dirección URL se reemplaza por el nombre del archivo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1868">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="abe28-1869">Puede cambiar los permisos para que todos los destinatarios tengan acceso.</span><span class="sxs-lookup"><span data-stu-id="abe28-1869">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="abe28-1870">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1870">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="abe28-1871">Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span><span class="sxs-lookup"><span data-stu-id="abe28-1871">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="abe28-1872">**Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office. Sus documentos han pasado a ser más elegantes.</span><span class="sxs-lookup"><span data-stu-id="abe28-1872">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="abe28-1873">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1873">PowerPoint</span></span>

- <span data-ttu-id="abe28-p220">**Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos ahora son más elegantes. [Más información](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01).</span><span class="sxs-lookup"><span data-stu-id="abe28-p220">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.  [Learn more](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span></span>

### <a name="word"></a><span data-ttu-id="abe28-1876">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1876">Word</span></span>

- <span data-ttu-id="abe28-1877">**Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.</span><span class="sxs-lookup"><span data-stu-id="abe28-1877">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1880">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1880">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-1881">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1881">Outlook</span></span>

- <span data-ttu-id="abe28-1882">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al mostrar las notificaciones del sistema.</span><span class="sxs-lookup"><span data-stu-id="abe28-1882">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2004-may-04"></a><span data-ttu-id="abe28-1884">Versión 2004: 4 de mayo</span><span class="sxs-lookup"><span data-stu-id="abe28-1884">Version 2004: May 04</span></span>
<span data-ttu-id="abe28-1885">*Versión 2004 (Compilación 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1885">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1887">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1887">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-1888">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1888">Outlook</span></span>

- <span data-ttu-id="abe28-1889">**Mejores resultados, en un instante:** actualizamos la experiencia de búsqueda para que sea más inteligente, rápida y fiable que nunca.</span><span class="sxs-lookup"><span data-stu-id="abe28-1889">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="abe28-1890">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1890">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="abe28-1891">**Notificación de incidentes para administradores de TI:** se notificará a los administradores globales de espacios empresariales de Microsoft 365 y a los administradores de aplicaciones de Office acerca de los incidentes de Outlook y Exchange de O365 que afectan a sus usuarios con una nueva notificación en el panel derecho en Outlook para Windows.</span><span class="sxs-lookup"><span data-stu-id="abe28-1891">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="abe28-1892">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-1892">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1895">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1895">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="abe28-1896">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-1896">Office Suite</span></span>

- <span data-ttu-id="abe28-1897">Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.</span><span class="sxs-lookup"><span data-stu-id="abe28-1897">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2004-april-29"></a><span data-ttu-id="abe28-1899">Versión 2004: 29 de abril</span><span class="sxs-lookup"><span data-stu-id="abe28-1899">Version 2004: April 29</span></span>
<span data-ttu-id="abe28-1900">*Versión 2004 (compilación 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1900">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1902">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1902">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-1903">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1903">Outlook</span></span>

- <span data-ttu-id="abe28-1904">**Protección de datos del grupo:** la etiqueta de confidencialidad que elija al crear un grupo se aplica al correo electrónico del grupo, a los documentos y a los sitios de equipo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1904">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1907">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1907">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-1908">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1908">Outlook</span></span>

- <span data-ttu-id="abe28-1909">Corrige un problema que causaba que Outlook se bloqueara en algunas compilaciones de Windows.</span><span class="sxs-lookup"><span data-stu-id="abe28-1909">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2004-april-25"></a><span data-ttu-id="abe28-1911">Versión 2004: 25 de abril</span><span class="sxs-lookup"><span data-stu-id="abe28-1911">Version 2004: April 25</span></span>
<span data-ttu-id="abe28-1912">*Versión 2004 (compilación 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1912">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1914">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1914">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-1915">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1915">Outlook</span></span>

- <span data-ttu-id="abe28-1916">Se ha corregido un problema que provocaba que Outlook se bloqueara al abrir archivos .msg y .oft guardados localmente después de una actualización de Windows.</span><span class="sxs-lookup"><span data-stu-id="abe28-1916">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="abe28-1917">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-1917">Project</span></span>

- <span data-ttu-id="abe28-1918">Se ha corregido un problema que hace que si está usando Project conectado a Project Web App y el separador decimal es una coma, el método TaskDependencies Add producirá un error al intentar agregar retardo a una dependencia.</span><span class="sxs-lookup"><span data-stu-id="abe28-1918">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="abe28-1919">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-1919">Office Suite</span></span>

- <span data-ttu-id="abe28-1920">Esta corrección resuelve un error que impide restringir el acceso y proteger los archivos con una contraseña de forma simultánea.</span><span class="sxs-lookup"><span data-stu-id="abe28-1920">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (NO ELIMINAR LOS DETALLES DEL CONTENIDO FINAL)

## <a name="version-2004-april-21"></a><span data-ttu-id="abe28-1922">Versión 2004: 21 de abril</span><span class="sxs-lookup"><span data-stu-id="abe28-1922">Version 2004: April 21</span></span>
<span data-ttu-id="abe28-1923">*Versión 2004 (compilación 12730.20182)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1923">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1925">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1925">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-1926">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1926">Outlook</span></span>

- <span data-ttu-id="abe28-1927">Corrige un problema que provocaba que el ancho del panel de carpetas cambiara de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="abe28-1927">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="abe28-1928">Corrige un problema que provocaba que los usuarios experimentaran un error al salir de Outlook.</span><span class="sxs-lookup"><span data-stu-id="abe28-1928">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2004-april-15"></a><span data-ttu-id="abe28-1930">Versión 2004: 15 de abril</span><span class="sxs-lookup"><span data-stu-id="abe28-1930">Version 2004: April 15</span></span>
<span data-ttu-id="abe28-1931">*Versión 2004 (compilación 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="abe28-1931">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-1933">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-1933">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-1934">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1934">Excel</span></span>

- <span data-ttu-id="abe28-1935">**El soporte para el conector de Facebook va a terminar:** a partir de abril de 2020. Excel ya no admitirá conexiones de datos externos que usen el conector de Facebook.</span><span class="sxs-lookup"><span data-stu-id="abe28-1935">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-1936">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1936">Outlook</span></span>

- <span data-ttu-id="abe28-1937">**Nueva opción para desactivar las sugerencias de @menciones al escribir correo en Outlook:**¿le resulta el selector de @menciones más molesto que útil?</span><span class="sxs-lookup"><span data-stu-id="abe28-1937">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="abe28-1938">Ahora puede desactivarlo si lo prefiere.</span><span class="sxs-lookup"><span data-stu-id="abe28-1938">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="abe28-1939">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1939">PowerPoint</span></span>

- <span data-ttu-id="abe28-1940">**Sincronice los cambios mientras realiza la presentación:** sincronice los cambios cuando se hagan aunque la presentación esté en el modo de presentación con diapositivas.</span><span class="sxs-lookup"><span data-stu-id="abe28-1940">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="abe28-1941">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1941">Word</span></span>

- <span data-ttu-id="abe28-1942">**Anote su copia privada:** cree notas escritas a mano privadas realizando una copia privada de un documento compartido.</span><span class="sxs-lookup"><span data-stu-id="abe28-1942">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="abe28-1943">Vaya a Ver > Crear una copia privada para empezar.</span><span class="sxs-lookup"><span data-stu-id="abe28-1943">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-1946">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-1946">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="abe28-1947">Access</span><span class="sxs-lookup"><span data-stu-id="abe28-1947">Access</span></span>

- <span data-ttu-id="abe28-1948">Se han corregido problema al cambiar el tamaño y actualizar tablas en el panel de tareas.</span><span class="sxs-lookup"><span data-stu-id="abe28-1948">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="abe28-1949">Se ha corregido un problema por el que las versiones internacionales de Access mostraban cadenas en inglés en la interfaz de usuario.</span><span class="sxs-lookup"><span data-stu-id="abe28-1949">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="abe28-1950">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-1950">Excel</span></span>

- <span data-ttu-id="abe28-1951">Se ha corregido un problema por el que seleccionar un rango de celdas en una hoja daba lugar a la selección de una sola celda.</span><span class="sxs-lookup"><span data-stu-id="abe28-1951">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="abe28-1952">En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.</span><span class="sxs-lookup"><span data-stu-id="abe28-1952">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="abe28-1953">Se ha corregido un problema que hacía que Excel se bloqueara en ciertos casos después de copiar una hoja que contenía una tabla dinámica.</span><span class="sxs-lookup"><span data-stu-id="abe28-1953">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="abe28-1954">Application.Evaluate (VBA) no funcionaba para funciones definidas por el usuario en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="abe28-1954">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="abe28-1955">Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al editar un rango de celdas grande por programación.</span><span class="sxs-lookup"><span data-stu-id="abe28-1955">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="abe28-1956">Se ha corregido un problema de rendimiento al abrir archivos CSV con entornos japoneses.</span><span class="sxs-lookup"><span data-stu-id="abe28-1956">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="abe28-1957">Se ha corregido un problema que provocaba que al insertar una plantilla de gráfico definida por el usuario como predeterminada se guardara como un gráfico de columnas.</span><span class="sxs-lookup"><span data-stu-id="abe28-1957">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="abe28-1958">Se ha corregido un problema por el que las etiquetas de datos en los gráficos se mostraban en blanco cuando las celdas de datos subyacentes no tuvieran un título.</span><span class="sxs-lookup"><span data-stu-id="abe28-1958">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="abe28-1959">Se ha corregido un problema que podía provocar que Excel dejara de responder al reducir el tamaño de un gráfico con algunos rangos de eje x.</span><span class="sxs-lookup"><span data-stu-id="abe28-1959">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="abe28-1960">Se ha corregido un problema por el que, en una hoja de Excel con referencia de celda F1C1 habilitada y en coautoría o compartida, al pasar el ratón por el icono de presencia del usuario no se mostraba la referencia de celda activa en modo F1C1.</span><span class="sxs-lookup"><span data-stu-id="abe28-1960">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="abe28-1961">Este cambio corrige retrasos al procesar imágenes con información de protocolo mal formada o incorrecta.</span><span class="sxs-lookup"><span data-stu-id="abe28-1961">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-1962">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-1962">Outlook</span></span>

- <span data-ttu-id="abe28-1963">Este cambio corrige retrasos al procesar imágenes con información de protocolo mal formada o incorrecta.</span><span class="sxs-lookup"><span data-stu-id="abe28-1963">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="abe28-1964">Este cambio corrige un problema por el que los cambios más recientes en los borradores de correo electrónico no se actualizaban.</span><span class="sxs-lookup"><span data-stu-id="abe28-1964">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="abe28-1965">Se corrigió un problema por el que hacer clic derecho del mouse en un archivo y usar "Enviar a" no funcionaba.</span><span class="sxs-lookup"><span data-stu-id="abe28-1965">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="abe28-1966">Se ha corregido un problema que provocaba que los delegados viesen distintas jerarquías de carpetas en diferentes equipos para los buzones compartidos.</span><span class="sxs-lookup"><span data-stu-id="abe28-1966">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="abe28-1967">Se ha corregido un problema que provocaba que las categorías desapareciesen en ocasiones de los mensajes de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="abe28-1967">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="abe28-1968">Se ha corregido un problema que provocaba que se produjesen errores en la activación de algunos avisos al cambiar la zona horaria en un equipo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1968">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="abe28-1969">Se ha corregido un problema que provocaba que los usuarios experimentasen un error al intentar ver las propiedades de un formulario de la organización.</span><span class="sxs-lookup"><span data-stu-id="abe28-1969">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="abe28-1970">Se corrigió un problema por el que si un usuario tenía una ruta de búsqueda personalizada para la libreta de direcciones, el ámbito de la resolución de nombres de Outlook se limitaba a la ruta personalizada, en lugar de incluir la lista global de direcciones (LGD).</span><span class="sxs-lookup"><span data-stu-id="abe28-1970">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="abe28-1971">Se ha corregido un problema que hacía que el botón "Guardar en la nube" faltara en las Herramientas de datos adjuntos.</span><span class="sxs-lookup"><span data-stu-id="abe28-1971">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="abe28-1972">Se ha corregido un problema que hacía que los usuarios no pudieran agregar una firma al responder a un mensaje administrado con derechos digitales desde una ventana de inspección cuando el usuario no tenía permiso de propietario sobre el mensaje al que se respondía.</span><span class="sxs-lookup"><span data-stu-id="abe28-1972">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="abe28-1973">Se ha corregido un problema que hacía que los usuarios no pudieran agregar archivos adjuntos adicionales desde una ubicación web a una reunión creada previamente.</span><span class="sxs-lookup"><span data-stu-id="abe28-1973">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="abe28-1974">Se ha corregido un problema que hacía que la fecha de "última modificación" de un archivo se actualizara al agregar un archivo adjunto a un correo electrónico o al guardar un archivo adjunto desde un correo arrastrándolo y colocándolo (en lugar de hacerlo a través de un menú).</span><span class="sxs-lookup"><span data-stu-id="abe28-1974">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="abe28-1975">Se ha corregido un problema que hacía que al presionar Entrar en el panel de búsqueda expandido no se iniciara la búsqueda y requería que los usuarios hiciesen clic en el botón de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="abe28-1975">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="abe28-1976">Se ha corregido un problema que hacía que al ordenar los resultados por categorías, en un conjunto de resultados de búsqueda devuelto no se mostraran los colores de la categoría.</span><span class="sxs-lookup"><span data-stu-id="abe28-1976">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="abe28-1977">Se ha corregido un problema por el que la búsqueda no mostraba información sobre los usuarios cuando se había deshabilitado la opción "Mostrar fotografías de usuario cuando estén disponibles".</span><span class="sxs-lookup"><span data-stu-id="abe28-1977">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="abe28-1978">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-1978">PowerPoint</span></span>

- <span data-ttu-id="abe28-1979">Este cambio corrige un error que podría causar que los archivos de PowerPoint que contienen emojis fallen al guardarlos.</span><span class="sxs-lookup"><span data-stu-id="abe28-1979">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="abe28-1980">Este cambio corrige un problema en el que es posible que no siempre se muestre el título del gráfico al representar un gráfico de Excel heredado incrustado como objeto OLE en PowerPoint o Word.</span><span class="sxs-lookup"><span data-stu-id="abe28-1980">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="abe28-1981">Se ha corregido un problema por el que al copiar texto de Excel en PowerPoint podía cambiar el formato.</span><span class="sxs-lookup"><span data-stu-id="abe28-1981">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="abe28-1982">Este cambio corrige un problema que provocaba que la búsqueda de caracteres especiales con "Buscar solo palabras completas" no siempre funcionase como se esperaba.</span><span class="sxs-lookup"><span data-stu-id="abe28-1982">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="abe28-1983">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-1983">Project</span></span>

- <span data-ttu-id="abe28-1984">Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.</span><span class="sxs-lookup"><span data-stu-id="abe28-1984">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="abe28-1985">Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="abe28-1985">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="abe28-1986">Se ha corregido un problema que hacía que el evento "ProjectBeforeTaskChange" de las aplicaciones de Visual Basic (VBA) no se activara cuando un usuario hacía clic en el botón "Desactivar" que se encuentra en la cinta de tareas en el grupo de programación.</span><span class="sxs-lookup"><span data-stu-id="abe28-1986">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="abe28-1987">Si establece los detalles de predecesor o sucesor desde una vista de tipo formulario, el evento de las aplicaciones de Visual Basic (VBA) ProjectBeforeTaskChange no siempre captura los cambios.</span><span class="sxs-lookup"><span data-stu-id="abe28-1987">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="abe28-1988">Por ejemplo, si ha eliminado una dependencia y ha hecho clic en Aceptar en el formulario, el evento no se ha desencadenado.</span><span class="sxs-lookup"><span data-stu-id="abe28-1988">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="abe28-1989">Este comportamiento se ha corregido.</span><span class="sxs-lookup"><span data-stu-id="abe28-1989">This behavior has been fixed.</span></span>

- <span data-ttu-id="abe28-1990">Se corrigió un problema por el que los valores más recientes del coste real del trabajo realizado (CRTR) no se mostraba después de realizar un cambio, como un cambio de fecha.</span><span class="sxs-lookup"><span data-stu-id="abe28-1990">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="abe28-1991">Se corrigió un problema por el que al abrir un proyecto con el menú Usados más recientemente se abría el archivo de proyecto con acceso de lectura y escritura.</span><span class="sxs-lookup"><span data-stu-id="abe28-1991">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="abe28-1992">Este cambio corrige un problema por el que si creaba una tarea manual con una fecha y hora de inicio (sin la duración), se mostraba con una hora incorrecta en la escala de tiempo.</span><span class="sxs-lookup"><span data-stu-id="abe28-1992">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="abe28-1993">Se corrigió un problema por el que la impresión de una escala de tiempo con el calendario Hijri saltaba un mes o lo duplicaba en la vista de impresión.</span><span class="sxs-lookup"><span data-stu-id="abe28-1993">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="abe28-1994">Este cambio resuelve un problema por el que trabajar en el Organizador de equipo con objetos de GDI podía provocar la sobreasignación de dichos objetos y crear condiciones de memoria insuficiente.</span><span class="sxs-lookup"><span data-stu-id="abe28-1994">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="abe28-1995">Se ha solucionado un problema por el que si se ejecuta "Lista de valores de campos personalizados GetItem" y no existe una tabla de búsqueda para el campo personalizado, se crea una tabla de búsqueda vacía aunque no debería existir.</span><span class="sxs-lookup"><span data-stu-id="abe28-1995">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="abe28-1996">Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se activa un evento ProjectBeforeTaskChange adicional.</span><span class="sxs-lookup"><span data-stu-id="abe28-1996">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="abe28-1997">Se corrigió un problema por el que el usuario no podía especificar el trabajo previsto con fases temporales al activar la configuración para proteger el trabajo real.</span><span class="sxs-lookup"><span data-stu-id="abe28-1997">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="abe28-1998">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-1998">Word</span></span>

- <span data-ttu-id="abe28-1999">Este cambio corrige un problema que provoca que al colocar el cursor sobre una sugerencia no se resalte la tarjeta.</span><span class="sxs-lookup"><span data-stu-id="abe28-1999">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="abe28-2000">Este cambio corrige un problema con varias páginas seleccionadas en el menú Ver, donde el panel de comentarios podía mostrarse en blanco.</span><span class="sxs-lookup"><span data-stu-id="abe28-2000">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="abe28-2001">Se corrigió un problema por el que se había deshabilitado la función para publicar comentarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-2001">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="abe28-2002">Este cambio corrige un problema que haría que el texto de las formas agrupadas desaparezca temporalmente al usar la herramienta Selección de lazo.</span><span class="sxs-lookup"><span data-stu-id="abe28-2002">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="abe28-2003">Este cambio corrige retrasos al procesar imágenes con información de protocolo mal formada o incorrecta.</span><span class="sxs-lookup"><span data-stu-id="abe28-2003">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="abe28-2004">Este cambio corrige un problema en el que es posible que no siempre se muestre el título del gráfico al representar un gráfico de Excel heredado incrustado como objeto OLE en PowerPoint o Word.</span><span class="sxs-lookup"><span data-stu-id="abe28-2004">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="abe28-2005">Este cambio resuelve un problema en el que el administrador de cuentas no enviaba mensajes, lo que provocaba un error en aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="abe28-2005">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="abe28-2006">Este cambio corrige un problema por el que, en la vista de dos páginas, al crear un comentario, el anclaje del comentario no siempre aparecía.</span><span class="sxs-lookup"><span data-stu-id="abe28-2006">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="abe28-2007">Se ha corregido un problema por el que al escribir o editar un comentario y usar Ctrl + A se seleccionaba texto en el lienzo en lugar de seleccionar texto en la tarjeta del comentario.</span><span class="sxs-lookup"><span data-stu-id="abe28-2007">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="abe28-2008">Se ha corregido un problema que hacía que si un párrafo con un estilo antecesor de un estilo estaba vinculado a una lista, se podía perder la numeración de la lista.</span><span class="sxs-lookup"><span data-stu-id="abe28-2008">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="abe28-2009">Este cambio corrige un problema en el que la tabla de contenido se actualizaba con estilos de título que no estaban presentes en el documento.</span><span class="sxs-lookup"><span data-stu-id="abe28-2009">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="abe28-2010">Se ha corregido un problema por el que la alineación de las palabras de un documento se puede codificar al intentar editar después de imprimir con la impresión rápida.</span><span class="sxs-lookup"><span data-stu-id="abe28-2010">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="abe28-2011">Se ha corregido un problema al combinar dos documentos en uno.</span><span class="sxs-lookup"><span data-stu-id="abe28-2011">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="abe28-2012">Se corrigió un problema por el que las firmas digitales guardadas en documentos de Word se eliminaban al enviar los documentos.</span><span class="sxs-lookup"><span data-stu-id="abe28-2012">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="abe28-2013">Se ha corregido un problema que hacía que el marcado de revisiones que impliquen ecuaciones ocasionase un error al guardar el archivo.</span><span class="sxs-lookup"><span data-stu-id="abe28-2013">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-april-14"></a><span data-ttu-id="abe28-2015">Versión 2003: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="abe28-2015">Version 2003: April 14</span></span>
<span data-ttu-id="abe28-2016">*Versión 2003 (compilación 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="abe28-2016">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="abe28-2017">Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="abe28-2017">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

- <span data-ttu-id="abe28-2019">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="abe28-2019">Various bugs and performance fixes.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

## <a name="version-2003-april-09"></a><span data-ttu-id="abe28-2021">Versión 2003: 09 de abril</span><span class="sxs-lookup"><span data-stu-id="abe28-2021">Version 2003: April 09</span></span>
<span data-ttu-id="abe28-2022">*Versión 2003 (compilación 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="abe28-2022">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-2024">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-2024">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-2025">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-2025">Excel</span></span>

- <span data-ttu-id="abe28-2026">**Selector de contenido de M365 Premium:** de vida a sus documentos.</span><span class="sxs-lookup"><span data-stu-id="abe28-2026">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="abe28-2027">Explore gratis miles de imágenes, iconos y adhesivos [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="abe28-2027">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-2028">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-2028">Outlook</span></span>

- <span data-ttu-id="abe28-2029">**Selector de contenido de M365 Premium:** de vida a sus documentos.</span><span class="sxs-lookup"><span data-stu-id="abe28-2029">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="abe28-2030">Explore gratis miles de imágenes, iconos y adhesivos [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="abe28-2030">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="abe28-2031">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-2031">PowerPoint</span></span>

- <span data-ttu-id="abe28-2032">**Selector de contenido de M365 Premium:** de vida a sus documentos.</span><span class="sxs-lookup"><span data-stu-id="abe28-2032">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="abe28-2033">Explore gratis miles de imágenes, iconos y adhesivos [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="abe28-2033">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="abe28-2034">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-2034">Word</span></span>

- <span data-ttu-id="abe28-2035">**Selector de contenido de M365 Premium:** de vida a sus documentos.</span><span class="sxs-lookup"><span data-stu-id="abe28-2035">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="abe28-2036">Explore gratis miles de imágenes, iconos y adhesivos [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="abe28-2036">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)




[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO FINAL)

## <a name="version-2003-april-03"></a><span data-ttu-id="abe28-2040">Versión 2003: 03 de abril</span><span class="sxs-lookup"><span data-stu-id="abe28-2040">Version 2003: April 03</span></span>
<span data-ttu-id="abe28-2041">*Versión 2003 (Compilación 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="abe28-2041">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-2043">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-2043">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-2044">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-2044">Excel</span></span>

- <span data-ttu-id="abe28-2045">El uso de la Aplicación VBA.Evaluar no trabajaba para las funciones definidas por el usuario en algunos casos.</span><span class="sxs-lookup"><span data-stu-id="abe28-2045">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-2046">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-2046">Outlook</span></span>

- <span data-ttu-id="abe28-2047">Abordó un problema que causó que los usuarios experimentaran ocasionalmente un choque al usar el botón "X" de su ratón.</span><span class="sxs-lookup"><span data-stu-id="abe28-2047">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="abe28-2048">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-2048">Project</span></span>

- <span data-ttu-id="abe28-2049">Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se dispara un ProyectoAntesdeCambiarTareaEvento extra.</span><span class="sxs-lookup"><span data-stu-id="abe28-2049">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="abe28-2050">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-2050">Word</span></span>

- <span data-ttu-id="abe28-2051">Abordó un problema que causó que los usuarios experimentaran ocasionalmente un choque al usar el botón "X" de su ratón.</span><span class="sxs-lookup"><span data-stu-id="abe28-2051">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-march-31"></a><span data-ttu-id="abe28-2053">Versión 2003: 31 de marzo</span><span class="sxs-lookup"><span data-stu-id="abe28-2053">Version 2003: March 31</span></span>
<span data-ttu-id="abe28-2054">*Versión 2003 (compilación 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="abe28-2054">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-2056">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-2056">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="abe28-2057">Access</span><span class="sxs-lookup"><span data-stu-id="abe28-2057">Access</span></span>

- <span data-ttu-id="abe28-2058">**Panel de tareas "Agregar tablas":** ¡Ya está disponible el acceso al nuevo panel de tareas "Agregar tablas"!</span><span class="sxs-lookup"><span data-stu-id="abe28-2058">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="abe28-2059">Esta característica le permite seleccionar y hacer selección múltiple de las tablas que desea agregar o quitar de forma sencilla en una ventana de consulta, sin tener que desplazarse hasta el cuadro de diálogo "Mostrar tablas" para las consultas y la vista de relación.</span><span class="sxs-lookup"><span data-stu-id="abe28-2059">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="abe28-2060">Esto también incluye una nueva pestaña "vínculos" para mostrar las tablas vinculadas, un cuadro de búsqueda para filtrar la lista actual, el comportamiento de "arrastrar y soltar", ¡y mucho más!</span><span class="sxs-lookup"><span data-stu-id="abe28-2060">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-2063">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-2063">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="abe28-2064">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-2064">Project</span></span>

- <span data-ttu-id="abe28-2065"><span style="display:inline !important;">Se corrigió un problema por el que el usuario no podía especificar el trabajo previsto con fases temporales al activar la configuración para proteger el trabajo real.</span></span><span class="sxs-lookup"><span data-stu-id="abe28-2065"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-march-25"></a><span data-ttu-id="abe28-2067">Versión 2003: 25 de marzo</span><span class="sxs-lookup"><span data-stu-id="abe28-2067">Version 2003: March 25</span></span>
<span data-ttu-id="abe28-2068">*Versión 2003 (compilación 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="abe28-2068">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="abe28-2069">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="abe28-2069">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="abe28-2070">Versión 2003: 23 de marzo</span><span class="sxs-lookup"><span data-stu-id="abe28-2070">Version 2003: March 23</span></span>
<span data-ttu-id="abe28-2071">*Versión 2003 (compilación 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="abe28-2071">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="abe28-2072">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="abe28-2072">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="abe28-2073">Versión 2003: 21 de marzo</span><span class="sxs-lookup"><span data-stu-id="abe28-2073">Version 2003: March 21</span></span>
<span data-ttu-id="abe28-2074">*Versión 2003 (compilación 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="abe28-2074">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-2076">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-2076">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-2077">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-2077">Outlook</span></span>

- <span data-ttu-id="abe28-2078">**Unirse a reuniones sin salir de la bandeja de entrada:** no es necesario cambiar al calendario para unirse a reuniones en línea.</span><span class="sxs-lookup"><span data-stu-id="abe28-2078">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="abe28-2079">Con el Calendario de Outlook anclado en el panel de tareas pendientes, únase a una reunión con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="abe28-2079">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="abe28-2080">**Actualización visual del calendario:** el año pasado, hemos incorporado una experiencia de correo actualizada y este año le toca al calendario tener una cara nueva.</span><span class="sxs-lookup"><span data-stu-id="abe28-2080">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="abe28-2081">Las actualizaciones son recientes pero son familiares, para que, como usuario de Outlook veterano, pueda empezar a ser más productivo en seguida.</span><span class="sxs-lookup"><span data-stu-id="abe28-2081">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="abe28-2082">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-2082">PowerPoint</span></span>

- <span data-ttu-id="abe28-2083">**Actualización de las diapositivas durante la presentación:** actualice diapositivas editadas por otros autores durante la presentación.</span><span class="sxs-lookup"><span data-stu-id="abe28-2083">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

## <a name="version-2003-march-16"></a><span data-ttu-id="abe28-2085">Versión 2003: 16 de marzo</span><span class="sxs-lookup"><span data-stu-id="abe28-2085">Version 2003: March 16</span></span>
<span data-ttu-id="abe28-2086">*Versión 2003 (compilación 12624,20224)*</span><span class="sxs-lookup"><span data-stu-id="abe28-2086">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (NO QUITAR DETALLES DE CARACTERÍSTICAS CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-2088">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-2088">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-2089">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-2089">Excel</span></span>

- <span data-ttu-id="abe28-2090">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="abe28-2090">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-2091">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-2091">Outlook</span></span>

- <span data-ttu-id="abe28-2092">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="abe28-2092">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="abe28-2093">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-2093">PowerPoint</span></span>

- <span data-ttu-id="abe28-2094">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="abe28-2094">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="abe28-2095">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-2095">Word</span></span>

- <span data-ttu-id="abe28-2096">**Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.</span><span class="sxs-lookup"><span data-stu-id="abe28-2096">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="abe28-2097">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-2097">Office Suite</span></span>

- <span data-ttu-id="abe28-2098">**Paneles con pestañas:** ahora puede cambiar entre varios paneles con la pestaña situada en la parte derecha de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="abe28-2098">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="abe28-2099">Esta interfaz de usuario solo será visible cuando haya dos o más paneles abiertos.</span><span class="sxs-lookup"><span data-stu-id="abe28-2099">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-2102">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-2102">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-2103">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-2103">Excel</span></span>

- <span data-ttu-id="abe28-2104">Se abordó un problema donde los enlaces externos no se actualizan cuando se cierra el libro de fuentes.</span><span class="sxs-lookup"><span data-stu-id="abe28-2104">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-2105">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-2105">Outlook</span></span>

- <span data-ttu-id="abe28-2106">Se abordó un problema que causó que los usuarios vieran que el proceso de Outlook permanecía en el administrador de tareas después de salir.</span><span class="sxs-lookup"><span data-stu-id="abe28-2106">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-march-10"></a><span data-ttu-id="abe28-2108">Versión 2003: 10 de marzo</span><span class="sxs-lookup"><span data-stu-id="abe28-2108">Version 2003: March 10</span></span>
<span data-ttu-id="abe28-2109">*Versión 2003 (compilación 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="abe28-2109">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="abe28-2110">Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="abe28-2110">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)
### <a name="feature-updates"></a><span data-ttu-id="abe28-2112">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-2112">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-2113">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-2113">Excel</span></span>
- <span data-ttu-id="abe28-2114">**Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados.</span><span class="sxs-lookup"><span data-stu-id="abe28-2114">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="abe28-2115">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-2115">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="abe28-2116">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-2116">PowerPoint</span></span>
- <span data-ttu-id="abe28-2117">**Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados.</span><span class="sxs-lookup"><span data-stu-id="abe28-2117">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="abe28-2118">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-2118">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="abe28-2119">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-2119">Word</span></span>
- <span data-ttu-id="abe28-2120">**Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados.</span><span class="sxs-lookup"><span data-stu-id="abe28-2120">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="abe28-2121">Más información</span><span class="sxs-lookup"><span data-stu-id="abe28-2121">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="abe28-2122">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-2122">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-2123">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-2123">Excel</span></span>

- <span data-ttu-id="abe28-2124">Se ha corregido un problema estético en el que el botón "Aceptar" del cuadro de diálogo de Archivo \ Opciones se mostraba atenuado, pero la función no se veía afectada.</span><span class="sxs-lookup"><span data-stu-id="abe28-2124">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="abe28-2125">Se ha corregido un problema que los usuarios pueden haber experimentado al cambiar el nombre de las medidas de tabla dinámica.</span><span class="sxs-lookup"><span data-stu-id="abe28-2125">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="abe28-2126">Se ha corregido un problema en el que el texto de una segmentación de datos no se escalaba correctamente en la vista previa de impresión.</span><span class="sxs-lookup"><span data-stu-id="abe28-2126">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="abe28-2127">Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al usar una macro de VBA para borrar el contenido de un rango.</span><span class="sxs-lookup"><span data-stu-id="abe28-2127">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="abe28-2128">Se ha corregido un problema que provocaba que la interfaz de usuario parpadeara cuando un usuario ejecutaba una macro que interactuaba con la cinta de opciones.</span><span class="sxs-lookup"><span data-stu-id="abe28-2128">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="abe28-2129">Se ha corregido un problema por el que los archivos CSV se cargaban de forma incorrecta cuando la primera palabra del archivo estaba era TABLE.</span><span class="sxs-lookup"><span data-stu-id="abe28-2129">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="abe28-2130">Se ha corregido un problema por el que los usuarios pueden haber sufrido bloqueos al cambiar entre dos libros que tienen diferentes niveles de zoom.</span><span class="sxs-lookup"><span data-stu-id="abe28-2130">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="abe28-2131">Se ha solucionado un problema por el que las funciones CUBEVALUE a veces daban un resultado incorrecto.</span><span class="sxs-lookup"><span data-stu-id="abe28-2131">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="abe28-2132">Este cambio resuelve un error en tiempo de ejecución en el modelo de objetos y el potencial bloqueo de la aplicación (Excel o Word) cuando los complementos pedían elementos host en documentos y hojas de cálculo que contienen formas con bloqueos noSelect.</span><span class="sxs-lookup"><span data-stu-id="abe28-2132">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="abe28-2133">Corrige un problema que causaba que los usuarios de Outlook experimentaran un error al sincronizar la configuración.</span><span class="sxs-lookup"><span data-stu-id="abe28-2133">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="abe28-2134">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-2134">Outlook</span></span>

- <span data-ttu-id="abe28-2135">Se ha corregido un problema que hacía que la creación de una regla con Outlook Web Access no se almacenara en el servidor de Exchange y produjera un conflicto.</span><span class="sxs-lookup"><span data-stu-id="abe28-2135">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="abe28-2136">Corregido un problema que causaba que los usuarios de Outlook experimentaran un error al sincronizar la configuración.</span><span class="sxs-lookup"><span data-stu-id="abe28-2136">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="abe28-2137">Se ha corregido un problema por el que, en el modo oscuro de Outlook, no se mostraba la lista desplegable en el campo "De:".</span><span class="sxs-lookup"><span data-stu-id="abe28-2137">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="abe28-2138">Se ha corregido un problema que hizo que Outlook generara inesperadamente resultados de registro en algunas situaciones, incluso cuando el registro se desactivaba.</span><span class="sxs-lookup"><span data-stu-id="abe28-2138">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="abe28-2139">Se ha corregido un problema que provocaba que los usuarios no puedan abrir mensajes de la carpeta pública cuando Outlook se dejaba en marcha durante la noche.</span><span class="sxs-lookup"><span data-stu-id="abe28-2139">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="abe28-2140">Se ha corregido una condición en la que los botones "Permitir" y "Denegar" de la página de permisos se deshabilitan durante el flujo de trabajo de autenticación para agregar una cuenta de Gmail.</span><span class="sxs-lookup"><span data-stu-id="abe28-2140">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="abe28-2141">Se ha corregido un problema que provocaba que los usuarios perdieran el acceso al cuadro de diálogo de permisos de calendario &quot;Opciones de disponibilidad&quot;.</span><span class="sxs-lookup"><span data-stu-id="abe28-2141">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="abe28-2142">Se ha corregido un problema que podría provocar alerta: &quot;"Lo sentimos, tenemos problemas para abrir este elemento"&quot; al abrir algunas instancias de reuniones periódicas que se han enviado desde una zona horaria diferente.</span><span class="sxs-lookup"><span data-stu-id="abe28-2142">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="abe28-2143">Se ha corregido un problema que podría ocasionar que los usuarios no puedan abrir un archivo .msg después de arrastrar y soltar datos adjuntos desde el mensaje.</span><span class="sxs-lookup"><span data-stu-id="abe28-2143">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="abe28-2144">Se ha corregido un problema por el que, después de cargar un archivo adjunto desde Outlook a OneDrive, se podía cambiar el nombre de archivo si el nombre de los datos adjuntos contenía paréntesis.</span><span class="sxs-lookup"><span data-stu-id="abe28-2144">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="abe28-2145">Corregido un problema por el que los usuarios no pueden adjuntar un archivo a un mensaje de correo electrónico a través del explorador de archivos cuando el archivo se abre en otra aplicación.</span><span class="sxs-lookup"><span data-stu-id="abe28-2145">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="abe28-2146">Corregido un problema que causaba que los usuarios de Outlook experimentaran un error al sincronizar la configuración.</span><span class="sxs-lookup"><span data-stu-id="abe28-2146">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="abe28-2147">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-2147">PowerPoint</span></span>

- <span data-ttu-id="abe28-2148">Se ha corregido un problema por el que las miniaturas recomendadas parpadean al pasar el ratón por encima de las miniaturas.</span><span class="sxs-lookup"><span data-stu-id="abe28-2148">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="abe28-2149">En algunos casos, esto provocaba un bloqueo de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="abe28-2149">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="abe28-2150">Se ha corregido un problema estético en el que el botón "Aceptar" del cuadro de diálogo de Archivo \ Opciones se mostraba atenuado, pero la función no se veía afectada.</span><span class="sxs-lookup"><span data-stu-id="abe28-2150">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="abe28-2151">Se ha corregido un problema que podría provocar un error al guardar un documento en PowerPoint o en Word con un gráfico de Excel.</span><span class="sxs-lookup"><span data-stu-id="abe28-2151">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="abe28-2152">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-2152">Project</span></span>

- <span data-ttu-id="abe28-2153">Corregido un problema por el que el porcentaje completado de la tarea se cambiaba incorrectamente a un valor inferior al 100 % después de que se marcara como completada.</span><span class="sxs-lookup"><span data-stu-id="abe28-2153">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="abe28-2154">Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="abe28-2154">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="abe28-2155">Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.</span><span class="sxs-lookup"><span data-stu-id="abe28-2155">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="abe28-2156">Visio</span><span class="sxs-lookup"><span data-stu-id="abe28-2156">Visio</span></span>

- <span data-ttu-id="abe28-p238">El panel información de la forma mostraba en la sección Datos de formas detalles que no coincidían con los del archivo al abrirlo en la aplicación de escritorio de Visio. Ya se ha corregido.</span><span class="sxs-lookup"><span data-stu-id="abe28-p238">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop. It has now been fixed.</span></span>

- <span data-ttu-id="abe28-2159">Los mapas de bits importados en versiones anteriores a 2016 no se representaban por motivos de seguridad.</span><span class="sxs-lookup"><span data-stu-id="abe28-2159">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="abe28-2160">Este problema se ha corregido en la suscripción de Visio.</span><span class="sxs-lookup"><span data-stu-id="abe28-2160">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="abe28-2161">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-2161">Word</span></span>

- <span data-ttu-id="abe28-2162">Se ha corregido un problema en el que las tarjetas con comentario no siempre se resaltan cuando se desplaza el puntero del mouse sobre la tarjeta del comentario.</span><span class="sxs-lookup"><span data-stu-id="abe28-2162">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="abe28-2163">Se ha corregido un problema por el que al ir a la tarjeta del comentario, el foco en el cuadro de edición del comentario no era visible.</span><span class="sxs-lookup"><span data-stu-id="abe28-2163">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="abe28-2164">Se ha corregido un problema estético en el que el botón "Aceptar" del cuadro de diálogo de Archivo \ Opciones se mostraba atenuado, pero la función no se veía afectada.</span><span class="sxs-lookup"><span data-stu-id="abe28-2164">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="abe28-p240">Durante una sesión de coautoría de documentos activos, agregar una imagen directamente en una tarjeta de comentario puede dar como resultado la adición de una etiqueta. Este problema se ha corregido.</span><span class="sxs-lookup"><span data-stu-id="abe28-p240">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag. This issue has been fixed.</span></span>

- <span data-ttu-id="abe28-2167">Si se inserta un control (como un control de contenido de texto) en una ecuación, al guardar y abrir el archivo se produce un error de contenido ilegible.</span><span class="sxs-lookup"><span data-stu-id="abe28-2167">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="abe28-2168">Se ha corregido un problema que hacía que no se pudiera guardar un archivo protegido con contraseña anteriormente en un almacenamiento en la nube.</span><span class="sxs-lookup"><span data-stu-id="abe28-2168">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="abe28-2169">Se ha corregido un problema con la característica Comparación para los documentos protegidos para la edición.</span><span class="sxs-lookup"><span data-stu-id="abe28-2169">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="abe28-2170">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-2170">Office Suite</span></span>

- <span data-ttu-id="abe28-2171">Al usar las propiedades Multichoice/Lookup/Managed-metadata con documentos de Word/Excel/PowerPoint y guardar en una biblioteca de documentos de SharePoint, estas propiedades se limitaban anteriormente a 255 caracteres.</span><span class="sxs-lookup"><span data-stu-id="abe28-2171">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="abe28-2172">Cuando estas propiedades superaban 255 caracteres, estos documentos no se podían guardar.</span><span class="sxs-lookup"><span data-stu-id="abe28-2172">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="abe28-2173">Con este cambio, este límite se ha aumentado a 2048 caracteres.</span><span class="sxs-lookup"><span data-stu-id="abe28-2173">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="abe28-2174">Se ha corregido un problema en Word/Excel/PowerPoint donde el nombre principal de usuario (UPN) ya no distingue entre mayúsculas y minúsculas, lo que provoca menos errores al trabajar con archivos en SharePoint.</span><span class="sxs-lookup"><span data-stu-id="abe28-2174">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="abe28-2175">Corregido un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.</span><span class="sxs-lookup"><span data-stu-id="abe28-2175">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-march-05"></a><span data-ttu-id="abe28-2177">Versión 2002: 05 de marzo</span><span class="sxs-lookup"><span data-stu-id="abe28-2177">Version 2002: March 05</span></span>
<span data-ttu-id="abe28-2178">*Versión 2002 (compilación 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="abe28-2178">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="abe28-2179">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="abe28-2179">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="abe28-2180">Versión 2002: 04 de marzo</span><span class="sxs-lookup"><span data-stu-id="abe28-2180">Version 2002: March 04</span></span>
<span data-ttu-id="abe28-2181">*Versión 2002 (compilación 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="abe28-2181">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-2183">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-2183">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="abe28-2184">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-2184">Project</span></span>
- <span data-ttu-id="abe28-2185">Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.</span><span class="sxs-lookup"><span data-stu-id="abe28-2185">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="abe28-2186">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-2186">Office Suite</span></span>
- <span data-ttu-id="abe28-2187">Corrige un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.</span><span class="sxs-lookup"><span data-stu-id="abe28-2187">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-march-01"></a><span data-ttu-id="abe28-2189">Versión 2002: 01 de marzo</span><span class="sxs-lookup"><span data-stu-id="abe28-2189">Version 2002: March 01</span></span>
<span data-ttu-id="abe28-2190">*Versión 2002 (compilación 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="abe28-2190">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="abe28-2191">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-2191">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-2192">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-2192">Outlook</span></span>

- <span data-ttu-id="abe28-2193">Corrige un problema que provocaba que las aplicaciones de terceros no pudiesen enviar correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="abe28-2193">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-february-24"></a><span data-ttu-id="abe28-2195">Versión de 2002: 24 de febrero</span><span class="sxs-lookup"><span data-stu-id="abe28-2195">Version 2002: February 24</span></span>
<span data-ttu-id="abe28-2196">*Versión de 2002 (compilación 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="abe28-2196">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="abe28-2197">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="abe28-2197">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="abe28-2198">Versión de 2002: 22 de febrero</span><span class="sxs-lookup"><span data-stu-id="abe28-2198">Version 2002: February 22</span></span>
<span data-ttu-id="abe28-2199">*Versión de 2002 (compilación 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="abe28-2199">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="abe28-2200">Varias correcciones de errores y rendimiento.</span><span class="sxs-lookup"><span data-stu-id="abe28-2200">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="abe28-2201">Versión 2002: 21 de febrero</span><span class="sxs-lookup"><span data-stu-id="abe28-2201">Version 2002: February 21</span></span>
<span data-ttu-id="abe28-2202">*Versión 2002 (compilación 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="abe28-2202">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-2204">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-2204">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="abe28-2205">Access</span><span class="sxs-lookup"><span data-stu-id="abe28-2205">Access</span></span>

- <span data-ttu-id="abe28-2206">**Aumente su productividad con el Diseñador de consultas, la vista SQL y la ventana Relaciones:** haga clic con el botón derecho en una tabla para abrirla, diseñarla, cambiar su tamaño y ocultarla.</span><span class="sxs-lookup"><span data-stu-id="abe28-2206">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="abe28-2207">Buscar y reemplazar texto en la vista SQL.</span><span class="sxs-lookup"><span data-stu-id="abe28-2207">Search and replace text in SQL View.</span></span> <span data-ttu-id="abe28-2208">Seleccione múltiples tablas en la ventana Relaciones.</span><span class="sxs-lookup"><span data-stu-id="abe28-2208">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-2209">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-2209">Outlook</span></span>

- <span data-ttu-id="abe28-2210">**Nueva experiencia para redes WiFi cautivas:** ¿alguna vez se ha unido a una red WiFi que requiere una página web para iniciar sesión?</span><span class="sxs-lookup"><span data-stu-id="abe28-2210">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="abe28-2211">Outlook ahora lo detecta y le ayuda a estar conectado.</span><span class="sxs-lookup"><span data-stu-id="abe28-2211">Outlook now detects this and helps you get connected.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-2214">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-2214">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="abe28-2215">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-2215">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="abe28-2216">Se ha corregido un problema por el que las funciones CUBEVALUE a veces daban un resultado incorrecto.&nbsp;<span style="display:inline !important;"></span></span><span class="sxs-lookup"><span data-stu-id="abe28-2216">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;<span style="display:inline !important;"></span></span></span><br>


### <a name="outlook"></a><span data-ttu-id="abe28-2217">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-2217">Outlook</span></span>

- <span data-ttu-id="abe28-2218">Corregido un tema que causó que las comas en el campo de ubicación de una reunión se convirtieran en punto y coma.</span><span class="sxs-lookup"><span data-stu-id="abe28-2218">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>


- <span data-ttu-id="abe28-2219">Corregido un problema que podría resultar en un choque al ver el mismo elemento en varias ventanas.</span><span class="sxs-lookup"><span data-stu-id="abe28-2219">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>


- <span data-ttu-id="abe28-2220">Corregido un problema que causó que Outlook sincronizara inesperadamente todo el correo, incluso cuando el deslizador de sincronización está configurado en un ajuste más pequeño.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="abe28-2220">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span>


- <span data-ttu-id="abe28-2221">Corregido un problema que causó que los usuarios con el Tema Negro vieran&quot;de&quot; el desplegable muestra un texto blanco sobre un fondo blanco.</span><span class="sxs-lookup"><span data-stu-id="abe28-2221">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>


- <span data-ttu-id="abe28-2222"><span style="display:inline !important;">Este cambio restaura la capacidad de ver sujetos de varias líneas en el encabezado del mensaje.</span></span><span class="sxs-lookup"><span data-stu-id="abe28-2222"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br>



[//]: # (NO ELIMINE EL CONTENIDO FINAL DE LOS DETALLES )

## <a name="version-2002-february-18"></a><span data-ttu-id="abe28-2224">Versión 2002: 18 de febrero</span><span class="sxs-lookup"><span data-stu-id="abe28-2224">Version 2002: February 18</span></span>
<span data-ttu-id="abe28-2225">*Versión 2002 (compilación 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="abe28-2225">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="abe28-2226">Versión 2002: 11 de febrero</span><span class="sxs-lookup"><span data-stu-id="abe28-2226">Version 2002: February 11</span></span>
<span data-ttu-id="abe28-2227">*Versión 2002 (compilación 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="abe28-2227">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="abe28-2228">Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="abe28-2228">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a><span data-ttu-id="abe28-2230">Actualizaciones de características</span><span class="sxs-lookup"><span data-stu-id="abe28-2230">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="abe28-2231">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-2231">Outlook</span></span>

- <span data-ttu-id="abe28-2232">**Arrastre el correo electrónico a un grupo de tu propiedad:** Mueva y copie mensajes y conversaciones arrastrándolos desde su bandeja de entrada.</span><span class="sxs-lookup"><span data-stu-id="abe28-2232">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="abe28-2233">Los mensajes que arrastres serán compartidos con todos los miembros del grupo.</span><span class="sxs-lookup"><span data-stu-id="abe28-2233">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="abe28-2234">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-2234">Word</span></span>

- <span data-ttu-id="abe28-2235">**Otros usuarios verán los cambios rápidamente**: las mejoras en la coautoría significan que los colaboradores podrán ver los cambios más rápido que nunca.</span><span class="sxs-lookup"><span data-stu-id="abe28-2235">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="abe28-2236">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-2236">Office Suite</span></span>

- <span data-ttu-id="abe28-2237">**Iconos de la barra de estado más nítidos:** los iconos de la barra de estado ahora son más fáciles de ver.</span><span class="sxs-lookup"><span data-stu-id="abe28-2237">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a><span data-ttu-id="abe28-2240">Problemas corregidos</span><span class="sxs-lookup"><span data-stu-id="abe28-2240">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="abe28-2241">Access</span><span class="sxs-lookup"><span data-stu-id="abe28-2241">Access</span></span>

- <span data-ttu-id="abe28-2242">Las plantillas de Access ya no deberían causar errores en columnas de datos adjuntos en una base de datos.</span><span class="sxs-lookup"><span data-stu-id="abe28-2242">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="abe28-2243">Después de crear la instancia de una plantilla, ahora debería poder agregar un campo de datos adjuntos a la base de datos.</span><span class="sxs-lookup"><span data-stu-id="abe28-2243">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="abe28-p246">Esta actualización corrige un problema por el que al usar un objeto ADODB. Recorder en código de VB podía notificarse un error incorrectamente.</span><span class="sxs-lookup"><span data-stu-id="abe28-p246">This update fixes an issue where using an ADODB. Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="abe28-2246">Esta actualización corrige un problema que puede hacer que Microsoft Access no identifique una Columna de identidad en una tabla vinculada de SQL Server, lo que puede provocar que las filas aparezcan como eliminadas de forma incorrecta.</span><span class="sxs-lookup"><span data-stu-id="abe28-2246">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="abe28-2247">Excel</span><span class="sxs-lookup"><span data-stu-id="abe28-2247">Excel</span></span>

- <span data-ttu-id="abe28-2248">Se ha corregido un problema por el que los comandos de comentario en el menú contextual no aparecían.</span><span class="sxs-lookup"><span data-stu-id="abe28-2248">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="abe28-2249">Se ha corregido un problema que causaba que algunos usuarios experimentasen bloqueos al convertir texto en columnas con celdas que tienen una matriz derramada.</span><span class="sxs-lookup"><span data-stu-id="abe28-2249">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="abe28-2250">Se ha corregido un problema por el que Excel se bloquea al usar la opción Texto a columnas con matrices dinámicas.</span><span class="sxs-lookup"><span data-stu-id="abe28-2250">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="abe28-2251">Outlook</span><span class="sxs-lookup"><span data-stu-id="abe28-2251">Outlook</span></span>

- <span data-ttu-id="abe28-2252">Se ha corregido un problema en el que el desplazamiento en el calendario con la vista de mes no muestra eventos de calendario anteriores.</span><span class="sxs-lookup"><span data-stu-id="abe28-2252">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="abe28-2253">Las carpetas guardadas en "favoritos" en el panel de navegación izquierdo podían desaparecer de forma esporádica.</span><span class="sxs-lookup"><span data-stu-id="abe28-2253">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="abe28-2254">Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.</span><span class="sxs-lookup"><span data-stu-id="abe28-2254">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="abe28-2255">Se ha corregido un problema que hacía que la opción deshabilitar el resaltado de elementos marcados no se pudiera respetar en algunos escenarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-2255">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="abe28-2256">Se ha corregido un problema que provocaba que los usuarios experimentaran un error al cancelar la configuración de la cuenta.</span><span class="sxs-lookup"><span data-stu-id="abe28-2256">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="abe28-2257">Se ha corregido un problema por el que los mensajes de correo electrónico que expiraban en función de una directiva de retención mostraban dos etiquetas.</span><span class="sxs-lookup"><span data-stu-id="abe28-2257">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="abe28-2258">Una mostraba que el correo expiraba en un día y otra que expiraba en dos días.</span><span class="sxs-lookup"><span data-stu-id="abe28-2258">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="abe28-2259">Se ha corregido un problema que causaba que los usuarios sufrieran un error al visualizar más de 30 calendarios en un entorno Citrix.</span><span class="sxs-lookup"><span data-stu-id="abe28-2259">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="abe28-2260">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="abe28-2260">PowerPoint</span></span>

- <span data-ttu-id="abe28-2261">Se ha corregido un problema por el que la entrada de lápiz no se procesaba por completo u se omitía al usarla en una animación de entrada de lápiz de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="abe28-2261">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="abe28-2262">Se ha corregido un problema que provocaba que, después de cerrar un archivo, PowerPoint no lo quitara inmediatamente de la colección Presentaciones si había algún controlador de eventos en ejecución.</span><span class="sxs-lookup"><span data-stu-id="abe28-2262">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="abe28-2263">Por lo tanto, el número de presentaciones que informa el modelo de objetos es incorrecto y se evita el cierre de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="abe28-2263">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="abe28-2264">Se ha corregido un problema con el marcador de resaltado: los textos blancos con un marcador oscuro se imprimen como negros en escala de grises.</span><span class="sxs-lookup"><span data-stu-id="abe28-2264">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="abe28-2265">Project</span><span class="sxs-lookup"><span data-stu-id="abe28-2265">Project</span></span>

- <span data-ttu-id="abe28-2266">Se ha corregido un problema por el que el 100 % de las tareas de tipo duración fija podían tener un cálculo del porcentaje incorrecto con menos del 100% completado.</span><span class="sxs-lookup"><span data-stu-id="abe28-2266">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="abe28-2267">Word</span><span class="sxs-lookup"><span data-stu-id="abe28-2267">Word</span></span>

- <span data-ttu-id="abe28-2268">Al actualizar y desplazarse por una tabla de contenido, es posible que se muestre un área gris en el documento.</span><span class="sxs-lookup"><span data-stu-id="abe28-2268">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="abe28-2269">Se ha corregido un problema por el que usar "Examinar" para guardar un archivo podía no funcionar si se escribió un comentario sin publicarlo y el usuario intentó guardar el archivo.</span><span class="sxs-lookup"><span data-stu-id="abe28-2269">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="abe28-2270">Se ha corregido un problema por el que al ir de una tarjeta de comentario a otra se podía mostrar el comentario seleccionado inicialmente con una selección resaltada.</span><span class="sxs-lookup"><span data-stu-id="abe28-2270">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="abe28-2271">Se ha corregido un problema por el que el formato de cursiva se perdía después de editar un comentario, ponerlo en cursiva y, después, publicarlo.</span><span class="sxs-lookup"><span data-stu-id="abe28-2271">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="abe28-2272">Se ha corregido un problema por el que la sugerencia de comentario no se veía en el modo lectura con el color de página invertido.</span><span class="sxs-lookup"><span data-stu-id="abe28-2272">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="abe28-2273">Se ha corregido un problema por el que si se trabajaba en coautoría en un documento, la versión de borrador de un comentario raíz podía no conservarse.</span><span class="sxs-lookup"><span data-stu-id="abe28-2273">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="abe28-2274">Con el Control de cambios habilitado y el panel de comentarios cerrado, Ctrl + Alt + M podía no funcionar para abrir el panel Comentarios.</span><span class="sxs-lookup"><span data-stu-id="abe28-2274">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="abe28-2275">Corregido un problema al agregar una @mención en una tabla que podía generar el mensaje de error: "Una tabla de este documento está dañada".</span><span class="sxs-lookup"><span data-stu-id="abe28-2275">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="abe28-2276">Se ha corregido un problema por el que los comandos de comentario (Modificar comentario, Responder a comentario, Eliminar comentario, Resolver comentario) en el menú contextual de comentarios no se mostraban.</span><span class="sxs-lookup"><span data-stu-id="abe28-2276">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="abe28-2277">Conjunto de aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="abe28-2277">Office Suite</span></span>

- <span data-ttu-id="abe28-2278">Resuelto un problema que podía causar que el paquete de herramientas de corrección de Noruega Nynorsk (NN-no) no se instalara correctamente.</span><span class="sxs-lookup"><span data-stu-id="abe28-2278">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="abe28-2279">Este cambio resuelve problemas con adaptadores gráficos que aprovechan la GPU integrada de Intel.</span><span class="sxs-lookup"><span data-stu-id="abe28-2279">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)
