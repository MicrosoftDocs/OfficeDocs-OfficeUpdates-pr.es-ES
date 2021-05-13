---
title: Historial de versiones de la Herramienta de implementación de Office (ODT)
ms.author: timda
author: TimDavenport
manager: TimDavenport
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: Historial de versiones de la Herramienta de implementación de Office (ODT) para los profesionales de TI
ms.openlocfilehash: 16814bd8ef3b67f3ff4bab2f60627fbb65a37e03
ms.sourcegitcommit: 8841de32b2d66cec6c0b07e7bc87faab0248c019
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 05/11/2021
ms.locfileid: "52322470"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="996bf-103">Historial de versiones de la Herramienta de implementación de Office</span><span class="sxs-lookup"><span data-stu-id="996bf-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="996bf-104">La Herramienta de implementación de Office (ODT) es una herramienta de línea de comandos que puede usar para descargar e implementar versiones de hacer clic y ejecutar de Office, como aplicaciones de Microsoft 365, en sus equipos cliente.</span><span class="sxs-lookup"><span data-stu-id="996bf-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="996bf-105">ODT le ofrece más control de la instalación de Office.</span><span class="sxs-lookup"><span data-stu-id="996bf-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="996bf-106">Le permite definir los productos e idiomas que se instalarán, cómo se actualizarán esos productos y si quiere o no mostrar la experiencia de instalación a los usuarios.</span><span class="sxs-lookup"><span data-stu-id="996bf-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="996bf-107">Para obtener información sobre cómo usar la ODT, vea [Información general sobre la herramienta de implementación de Office](/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="996bf-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="996bf-108">**Sistema operativo compatible**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="996bf-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="996bf-109">**Instrucciones de instalación**: Descargue y ejecute el archivo ejecutable autoextraíble de la Herramienta de implementación de Office (setup.exe) y un archivo de configuración de ejemplo (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="996bf-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="996bf-110">Descargar la Herramienta de implementación de Office</span><span class="sxs-lookup"><span data-stu-id="996bf-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="may-10-2021"></a><span data-ttu-id="996bf-111">10 de mayo de 2021</span><span class="sxs-lookup"><span data-stu-id="996bf-111">May 10, 2021</span></span>
<span data-ttu-id="996bf-112">Versión 16.0.13929.20296 (versión setup.exe 16.0.13929.20238)</span><span class="sxs-lookup"><span data-stu-id="996bf-112">Version 16.0.13929.20296 (setup.exe version 16.0.13929.20238)</span></span>
- <span data-ttu-id="996bf-113">Se ha corregido un problema por el que puede producirse un error en el modo /configure si un archivo de configuración incluye MigrateArch y RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="996bf-113">Fixed an issue where /configure mode may fail if a configuration file includes both MigrateArch and RemoveMSI</span></span>
- <span data-ttu-id="996bf-114">Mejoras de confiabilidad adicionales</span><span class="sxs-lookup"><span data-stu-id="996bf-114">Additional reliability improvements</span></span>

## <a name="april-13-2021"></a><span data-ttu-id="996bf-115">13 de abril de 2021</span><span class="sxs-lookup"><span data-stu-id="996bf-115">April 13, 2021</span></span>
<span data-ttu-id="996bf-116">Versión 16.0.13901.20336 (versión setup.exe 16.0.13901.20328)</span><span class="sxs-lookup"><span data-stu-id="996bf-116">Version 16.0.13901.20336 (setup.exe version 16.0.13901.20328)</span></span>
- <span data-ttu-id="996bf-117">Correcciones de confiabilidad para configurar operaciones que se ejecutan en dispositivos con Office ya instalado</span><span class="sxs-lookup"><span data-stu-id="996bf-117">Reliability fixes for configure operations that are run on devices with Office already installed</span></span>
- <span data-ttu-id="996bf-118">Correcciones para evitar mostrar la interfaz de usuario de progreso duplicada en algunos escenarios</span><span class="sxs-lookup"><span data-stu-id="996bf-118">Fixes to avoid showing duplicate progress UI in some scenarios</span></span>
- <span data-ttu-id="996bf-119">Mejoras en la precisión de código de error que se muestran en la interfaz de usuario</span><span class="sxs-lookup"><span data-stu-id="996bf-119">Improvements to error code accuracy shown in UI</span></span>
- <span data-ttu-id="996bf-120">Correcciones de confiabilidad para plataformas ARM</span><span class="sxs-lookup"><span data-stu-id="996bf-120">Reliability fixes for ARM platforms</span></span>

## <a name="march-23-2021"></a><span data-ttu-id="996bf-121">23 de marzo de 2021</span><span class="sxs-lookup"><span data-stu-id="996bf-121">March 23, 2021</span></span>
<span data-ttu-id="996bf-122">Versión 16.0.13801.20360 (versión setup.exe 16.0.13801.20340)</span><span class="sxs-lookup"><span data-stu-id="996bf-122">Version 16.0.13801.20360 (setup.exe version 16.0.13801.20340)</span></span>
- <span data-ttu-id="996bf-123">Cambios para dar soporte a próximas versiones de productos de Office</span><span class="sxs-lookup"><span data-stu-id="996bf-123">Changes to support upcoming Office product releases</span></span>
- <span data-ttu-id="996bf-124">Correcciones de confiabilidad para plataformas ARM</span><span class="sxs-lookup"><span data-stu-id="996bf-124">Reliability fixes for ARM platforms</span></span>


## <a name="february-25-2021"></a><span data-ttu-id="996bf-125">25 de febrero de 2021</span><span class="sxs-lookup"><span data-stu-id="996bf-125">February 25, 2021</span></span>
<span data-ttu-id="996bf-126">Versión 16.0.13628.20476 (versión setup.exe 16.0.13628.20462)</span><span class="sxs-lookup"><span data-stu-id="996bf-126">Version 16.0.13628.20476 (setup.exe version 16.0.13628.20462)</span></span>
- <span data-ttu-id="996bf-127">Se ha corregido un problema en el que se producían errores al validar archivos configuration.xml que especificaban docenas de idiomas</span><span class="sxs-lookup"><span data-stu-id="996bf-127">Fixed an issue where configuration.xml files specifying several dozen languages was failing to validate</span></span>
- <span data-ttu-id="996bf-128">Se ha corregido un problema por el que no se respetaba la propiedad FORCEAPPSHUTDOWN en los escenarios de MigrateArch</span><span class="sxs-lookup"><span data-stu-id="996bf-128">Fixed an issue where the FORCEAPPSHUTDOWN property was not being respected in MigrateArch scenarios</span></span>
- <span data-ttu-id="996bf-129">Se ha corregido un problema por el que se producía un error al especificar 2 o más atributos PIDKEY en configuration.xml al instalar las PIDKeys</span><span class="sxs-lookup"><span data-stu-id="996bf-129">Fixed an issue where specifying 2 or more PIDKEY attributes in configuration.xml failed to install the PIDKeys</span></span>



## <a name="february-9-2021"></a><span data-ttu-id="996bf-130">9 de febrero de 2021</span><span class="sxs-lookup"><span data-stu-id="996bf-130">February 9, 2021</span></span>
<span data-ttu-id="996bf-131">Versión 16.0.13628.20274 (versión setup.exe 16.0.13628.20246)</span><span class="sxs-lookup"><span data-stu-id="996bf-131">Version 16.0.13628.20274 (setup.exe version 16.0.13628.20246)</span></span>
- <span data-ttu-id="996bf-132">Validación agregada para advertir y evitar sobre instalaciones no compatibles en Windows 8.0</span><span class="sxs-lookup"><span data-stu-id="996bf-132">Added validation to warn about and prevent unsupported installations on Windows 8.0</span></span>
- <span data-ttu-id="996bf-133">Correcciones de confiabilidad para dispositivos ARM64</span><span class="sxs-lookup"><span data-stu-id="996bf-133">Reliability fixes for ARM64 devices</span></span>


## <a name="january-12-2021"></a><span data-ttu-id="996bf-134">12 de enero de 2021</span><span class="sxs-lookup"><span data-stu-id="996bf-134">January 12, 2021</span></span>
<span data-ttu-id="996bf-135">Versión 16.0.13530.20376 (versión setup.exe 16.0.13530.20334)</span><span class="sxs-lookup"><span data-stu-id="996bf-135">Version 16.0.13530.20376 (setup.exe version 16.0.13530.20334)</span></span>
- <span data-ttu-id="996bf-136">Se ha corregido un problema por el que un registro de producto dañado o no estándar podía provocar un error en las operaciones de RemoveMSI.</span><span class="sxs-lookup"><span data-stu-id="996bf-136">Fixed an issue where corrupted or non-standard product registration could cause RemoveMSI operations to fail</span></span>

## <a name="december-21-2020"></a><span data-ttu-id="996bf-137">21 de diciembre de 2020</span><span class="sxs-lookup"><span data-stu-id="996bf-137">December 21, 2020</span></span>
<span data-ttu-id="996bf-138">Versión 16.0.13426.20370 (versión setup.exe 16.0.13426.20352)</span><span class="sxs-lookup"><span data-stu-id="996bf-138">Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)</span></span>
- <span data-ttu-id="996bf-139">Se solucionó un problema que provocaba que fallaran las instalaciones de fuente local de ProofingTools del canal PerpetualVL2019</span><span class="sxs-lookup"><span data-stu-id="996bf-139">Fixed an issue where local source installations of ProofingTools from the PerpetualVL2019 channel were failing</span></span>
- <span data-ttu-id="996bf-140">Se solucionó un problema para garantizar que el cliente Hacer clic y ejecutar trate de actualizarse al agregar productos adicionales en idiomas incompletos de Office a una instalación ya existente</span><span class="sxs-lookup"><span data-stu-id="996bf-140">Fixed an issue to ensure that the Click-To-Run client attempts a self-update when adding additional products in non-full Office languages to an existing installation</span></span>


## <a name="december-8-2020"></a><span data-ttu-id="996bf-141">8 de diciembre de 2020</span><span class="sxs-lookup"><span data-stu-id="996bf-141">December 8, 2020</span></span>
<span data-ttu-id="996bf-142">Versión 16.0.13426.20308 (setup.exe versión 16.0.13426.20308)</span><span class="sxs-lookup"><span data-stu-id="996bf-142">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="996bf-143">Se ha corregido un problema que provocaba que el modo de descarga bloqueara las descargas del canal perpetuo 2019 si el dispositivo tenía un producto de Office instalado desde un canal 2019 no perpetuo.</span><span class="sxs-lookup"><span data-stu-id="996bf-143">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="996bf-144">Se ha corregido un problema que provocaba que una migración de arquitectura produjera un error en un origen local creado mediante el modo de descarga que había especificado una versión explícita en el XML de configuración.</span><span class="sxs-lookup"><span data-stu-id="996bf-144">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="996bf-145">23 de noviembre de 2020</span><span class="sxs-lookup"><span data-stu-id="996bf-145">November 23, 2020</span></span>
<span data-ttu-id="996bf-146">Versión 16.0.13328.20420 (setup.exe versión 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="996bf-146">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="996bf-147">Se ha corregido un problema que provocaba que las herramientas de corrección no se descargaran en el modo de /descarga</span><span class="sxs-lookup"><span data-stu-id="996bf-147">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="996bf-148">Se ha corregido un problema que provocaba un error en el modo de /descarga al ejecutarse en un contexto de usuario no elevado</span><span class="sxs-lookup"><span data-stu-id="996bf-148">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="996bf-149">Se ha corregido un problema que provocaba que, al especificar un atributo de versión en el archivo XML de configuración, no se completaran las descargas en el modo de /descarga</span><span class="sxs-lookup"><span data-stu-id="996bf-149">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="996bf-150">Se ha corregido un problema que provocaba que la Herramienta de implementación de Office no se denominara "setup.exe" al extraerse</span><span class="sxs-lookup"><span data-stu-id="996bf-150">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="996bf-151">Se ha corregido un problema relacionado con la prioridad de la instalación de origen cuando se proporcionaba un atributo de canal en el archivo XML de configuración</span><span class="sxs-lookup"><span data-stu-id="996bf-151">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="996bf-152">10 de noviembre de 2020</span><span class="sxs-lookup"><span data-stu-id="996bf-152">November 10, 2020</span></span>
<span data-ttu-id="996bf-153">Version 16.0.13328.20356 (setupODT.exe versión 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="996bf-153">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="996bf-154">Mejoras de confiabilidad y resiliencia</span><span class="sxs-lookup"><span data-stu-id="996bf-154">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="996bf-155">Para evitar confusiones y diagnosticar más fácilmente los errores de configuración, la ODT ahora se denomina setupODT.exe de manera predeterminada.</span><span class="sxs-lookup"><span data-stu-id="996bf-155">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="996bf-156">29 de octubre de 2020</span><span class="sxs-lookup"><span data-stu-id="996bf-156">October 29, 2020</span></span>
<span data-ttu-id="996bf-157">Versión 16.0.13328.20292 (setup.exe versión 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="996bf-157">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="996bf-158">Resuelva un problema por el que determinados productos de Office 2007 puedan bloquear la instalación inesperadamente al usar RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="996bf-158">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="996bf-159">14 de octubre de 2020</span><span class="sxs-lookup"><span data-stu-id="996bf-159">October 14, 2020</span></span>
<span data-ttu-id="996bf-160">Versión 16.0.13231.20368 (setup.exe versión 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="996bf-160">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="996bf-161">Todos los productos ahora usarán el Canal mensual de forma predeterminada cuando no se especifique ningún canal</span><span class="sxs-lookup"><span data-stu-id="996bf-161">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="996bf-162">Seguridad mejorada al ejecutar ODT desde un directorio que contiene otras DLL</span><span class="sxs-lookup"><span data-stu-id="996bf-162">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="996bf-163">Mejoras de confiabilidad y resiliencia</span><span class="sxs-lookup"><span data-stu-id="996bf-163">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="996bf-164">9 de junio de 2020</span><span class="sxs-lookup"><span data-stu-id="996bf-164">June 9, 2020</span></span>

<span data-ttu-id="996bf-165">Versión 16.0.12827.20268 (setup.exe versión 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="996bf-165">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="996bf-166">El Canal actual ahora es el canal predeterminado cuando no se especifica ningún canal</span><span class="sxs-lookup"><span data-stu-id="996bf-166">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="996bf-167">Se agregó soporte técnico para el Canal mensual para empresas</span><span class="sxs-lookup"><span data-stu-id="996bf-167">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="996bf-168">Se agregó soporte técnico para los nuevos nombres del canal</span><span class="sxs-lookup"><span data-stu-id="996bf-168">Added support for new channel names</span></span>
- <span data-ttu-id="996bf-169">Otras características de resistencia para continuar la instalación, si es posible, incluso cuando no estén disponibles algunos recursos de idioma.</span><span class="sxs-lookup"><span data-stu-id="996bf-169">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="996bf-170">Funciones MSIRemove expandidas para quitar productos de Office 2007</span><span class="sxs-lookup"><span data-stu-id="996bf-170">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="996bf-171">Funciones MSIRemove expandidas para quitar el Motor de acceso a la base de datos</span><span class="sxs-lookup"><span data-stu-id="996bf-171">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="996bf-172">15 de abril de 2020</span><span class="sxs-lookup"><span data-stu-id="996bf-172">April 15, 2020</span></span>

<span data-ttu-id="996bf-173">Versión 16.0.12624.20320 (setup.exe versión 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="996bf-173">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="996bf-174">Agrega soporte técnico para las versiones finales de Office específicas de Windows 7</span><span class="sxs-lookup"><span data-stu-id="996bf-174">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="996bf-175">Corrige un problema en el que la configuración de personalización puede no aplicarse como se esperaba</span><span class="sxs-lookup"><span data-stu-id="996bf-175">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="996bf-176">Corrige un problema por el que los archivos extraños .cat se pueden descargar de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="996bf-176">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="996bf-177">Enero de 16 de 2020</span><span class="sxs-lookup"><span data-stu-id="996bf-177">January 16, 2020</span></span>

<span data-ttu-id="996bf-178">Versión 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="996bf-178">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="996bf-179">Corrige un problema que causaba que la interfaz de usuario de instalación de Office aparezca en un idioma incorrecto al instalar varios idiomas.</span><span class="sxs-lookup"><span data-stu-id="996bf-179">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="996bf-180">Corrige un problema que causaba que la instalación de Office falle inesperadamente cuando se instalaban determinados paquetes de herramientas de corrección</span><span class="sxs-lookup"><span data-stu-id="996bf-180">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="996bf-181">Agrega soporte para controlar, opcionalmente, la implementación inicial de la [ característica Búsqueda de Microsoft en Bing](/deployoffice/microsoft-search-bing)</span><span class="sxs-lookup"><span data-stu-id="996bf-181">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](/deployoffice/microsoft-search-bing)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="996bf-182">31 de octubre de 2019</span><span class="sxs-lookup"><span data-stu-id="996bf-182">October 31, 2019</span></span>

<span data-ttu-id="996bf-183">Versión 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="996bf-183">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="996bf-184">Se ha corregido un problema que permite que Skype Empresarial Basic 2019 se instale con productos de licencia por volumen perpetuo 2019</span><span class="sxs-lookup"><span data-stu-id="996bf-184">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="996bf-185">Se ha corregido un problema que puede ocasionar que el modo de descarga ODT falle inesperadamente en determinadas circunstancias cuando se utiliza un proxy.</span><span class="sxs-lookup"><span data-stu-id="996bf-185">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="996bf-186">Se ha desarrollado una nueva capacidad que permite que el modo de descarga ODT descargue a través de HTTP utilizando un puerto distinto al puerto 80.</span><span class="sxs-lookup"><span data-stu-id="996bf-186">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="996bf-187">10 de julio de 2019</span><span class="sxs-lookup"><span data-stu-id="996bf-187">July 10, 2019</span></span>

<span data-ttu-id="996bf-188">Versión 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="996bf-188">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="996bf-189">Compatibilidad con productos adicionales cuando se instalan con Office 2019: Access Runtime, Skype Empresarial Basic.</span><span class="sxs-lookup"><span data-stu-id="996bf-189">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="996bf-190">Compatibilidad con la instalación condicional de productos independientes al actualizar desde MSI.</span><span class="sxs-lookup"><span data-stu-id="996bf-190">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="996bf-191">23 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="996bf-191">April 23, 2019</span></span>

<span data-ttu-id="996bf-192">Versión 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="996bf-192">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="996bf-193">Se ha corregido un error con RemoveMSI=True para limpiar las configuraciones de registro relacionadas.</span><span class="sxs-lookup"><span data-stu-id="996bf-193">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="996bf-194">Se han actualizado los códigos de error para dar información adicional sobre errores inesperados (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="996bf-194">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="996bf-195">16 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="996bf-195">April 16 2019</span></span>

<span data-ttu-id="996bf-196">Versión 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="996bf-196">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="996bf-197">Compatibilidad para actualizar de C2R 32 bits a C2R 64 bits con el nuevo atributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="996bf-197">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="996bf-198">Se ha actualizado la lógica para /configure. Ahora permite acceder a los archivos XML de configuración almacenados en ubicaciones Web (http y https).</span><span class="sxs-lookup"><span data-stu-id="996bf-198">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="996bf-199">Se ha agregado MatchInstalled como un nuevo atributo que permite a la ODT coincidir con la versión existente cuando se agreguen más productos o idiomas.</span><span class="sxs-lookup"><span data-stu-id="996bf-199">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="996bf-200">13 de marzo de 2019</span><span class="sxs-lookup"><span data-stu-id="996bf-200">March 13, 2019</span></span>

<span data-ttu-id="996bf-201">Versión 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="996bf-201">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="996bf-202">Mejoras en situaciones de actualización y migración.</span><span class="sxs-lookup"><span data-stu-id="996bf-202">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="996bf-203">14 de enero de 2019</span><span class="sxs-lookup"><span data-stu-id="996bf-203">January 14, 2019</span></span>

<span data-ttu-id="996bf-204">Versión 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="996bf-204">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="996bf-205">Mejoras en el registro y la telemetría para la configuración de implementación.</span><span class="sxs-lookup"><span data-stu-id="996bf-205">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="996bf-206">Vínculos relacionados</span><span class="sxs-lookup"><span data-stu-id="996bf-206">Related links</span></span>

[<span data-ttu-id="996bf-207">Centro de descarga de ODT</span><span class="sxs-lookup"><span data-stu-id="996bf-207">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)