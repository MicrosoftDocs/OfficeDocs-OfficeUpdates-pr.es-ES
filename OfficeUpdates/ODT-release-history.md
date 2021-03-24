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
ms.openlocfilehash: 046054dfb781c3cd19ca6505e5ae5f2f362f6a86
ms.sourcegitcommit: 04f3aa30703f4f1cf89721853a7c052fcca2b97f
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2021
ms.locfileid: "51169969"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="c4a19-103">Historial de versiones de la Herramienta de implementación de Office</span><span class="sxs-lookup"><span data-stu-id="c4a19-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="c4a19-104">La Herramienta de implementación de Office (ODT) es una herramienta de línea de comandos que puede usar para descargar e implementar versiones de hacer clic y ejecutar de Office, como aplicaciones de Microsoft 365, en sus equipos cliente.</span><span class="sxs-lookup"><span data-stu-id="c4a19-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="c4a19-105">ODT le ofrece más control de la instalación de Office.</span><span class="sxs-lookup"><span data-stu-id="c4a19-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="c4a19-106">Le permite definir los productos e idiomas que se instalarán, cómo se actualizarán esos productos y si quiere o no mostrar la experiencia de instalación a los usuarios.</span><span class="sxs-lookup"><span data-stu-id="c4a19-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="c4a19-107">Para obtener información sobre cómo usar la ODT, vea [Información general sobre la herramienta de implementación de Office](/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="c4a19-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="c4a19-108">**Sistema operativo compatible**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="c4a19-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="c4a19-109">**Instrucciones de instalación**: Descargue y ejecute el archivo ejecutable autoextraíble de la Herramienta de implementación de Office (setup.exe) y un archivo de configuración de ejemplo (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="c4a19-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="c4a19-110">Descargar la Herramienta de implementación de Office</span><span class="sxs-lookup"><span data-stu-id="c4a19-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="march-23-2021"></a><span data-ttu-id="c4a19-111">23 de marzo de 2021</span><span class="sxs-lookup"><span data-stu-id="c4a19-111">March 23, 2021</span></span>
<span data-ttu-id="c4a19-112">Versión 16.0.13801.20360 (versión setup.exe 16.0.13801.20340)</span><span class="sxs-lookup"><span data-stu-id="c4a19-112">Version 16.0.13801.20360 (setup.exe version 16.0.13801.20340)</span></span>
- <span data-ttu-id="c4a19-113">Cambios para dar soporte a próximas versiones de productos de Office</span><span class="sxs-lookup"><span data-stu-id="c4a19-113">Changes to support upcoming Office product releases</span></span>
- <span data-ttu-id="c4a19-114">Correcciones de confiabilidad para plataformas ARM</span><span class="sxs-lookup"><span data-stu-id="c4a19-114">Reliability fixes for ARM platforms</span></span>


## <a name="february-25-2021"></a><span data-ttu-id="c4a19-115">25 de febrero de 2021</span><span class="sxs-lookup"><span data-stu-id="c4a19-115">February 25, 2021</span></span>
<span data-ttu-id="c4a19-116">Versión 16.0.13628.20476 (versión setup.exe 16.0.13628.20462)</span><span class="sxs-lookup"><span data-stu-id="c4a19-116">Version 16.0.13628.20476 (setup.exe version 16.0.13628.20462)</span></span>
- <span data-ttu-id="c4a19-117">Se ha corregido un problema en el que se producían errores al validar archivos configuration.xml que especificaban docenas de idiomas</span><span class="sxs-lookup"><span data-stu-id="c4a19-117">Fixed an issue where configuration.xml files specifying several dozen languages was failing to validate</span></span>
- <span data-ttu-id="c4a19-118">Se ha corregido un problema por el que no se respetaba la propiedad FORCEAPPSHUTDOWN en los escenarios de MigrateArch</span><span class="sxs-lookup"><span data-stu-id="c4a19-118">Fixed an issue where the FORCEAPPSHUTDOWN property was not being respected in MigrateArch scenarios</span></span>
- <span data-ttu-id="c4a19-119">Se ha corregido un problema por el que se producía un error al especificar 2 o más atributos PIDKEY en configuration.xml al instalar las PIDKeys</span><span class="sxs-lookup"><span data-stu-id="c4a19-119">Fixed an issue where specifying 2 or more PIDKEY attributes in configuration.xml failed to install the PIDKeys</span></span>



## <a name="february-9-2021"></a><span data-ttu-id="c4a19-120">9 de febrero de 2021</span><span class="sxs-lookup"><span data-stu-id="c4a19-120">February 9, 2021</span></span>
<span data-ttu-id="c4a19-121">Versión 16.0.13628.20274 (versión setup.exe 16.0.13628.20246)</span><span class="sxs-lookup"><span data-stu-id="c4a19-121">Version 16.0.13628.20274 (setup.exe version 16.0.13628.20246)</span></span>
- <span data-ttu-id="c4a19-122">Validación agregada para advertir y evitar sobre instalaciones no compatibles en Windows 8.0</span><span class="sxs-lookup"><span data-stu-id="c4a19-122">Added validation to warn about and prevent unsupported installations on Windows 8.0</span></span>
- <span data-ttu-id="c4a19-123">Correcciones de confiabilidad para dispositivos ARM64</span><span class="sxs-lookup"><span data-stu-id="c4a19-123">Reliability fixes for ARM64 devices</span></span>


## <a name="january-12-2021"></a><span data-ttu-id="c4a19-124">12 de enero de 2021</span><span class="sxs-lookup"><span data-stu-id="c4a19-124">January 12, 2021</span></span>
<span data-ttu-id="c4a19-125">Versión 16.0.13530.20376 (versión setup.exe 16.0.13530.20334)</span><span class="sxs-lookup"><span data-stu-id="c4a19-125">Version 16.0.13530.20376 (setup.exe version 16.0.13530.20334)</span></span>
- <span data-ttu-id="c4a19-126">Se ha corregido un problema por el que un registro de producto dañado o no estándar podía provocar un error en las operaciones de RemoveMSI.</span><span class="sxs-lookup"><span data-stu-id="c4a19-126">Fixed an issue where corrupted or non-standard product registration could cause RemoveMSI operations to fail</span></span>

## <a name="december-21-2020"></a><span data-ttu-id="c4a19-127">21 de diciembre de 2020</span><span class="sxs-lookup"><span data-stu-id="c4a19-127">December 21, 2020</span></span>
<span data-ttu-id="c4a19-128">Versión 16.0.13426.20370 (versión setup.exe 16.0.13426.20352)</span><span class="sxs-lookup"><span data-stu-id="c4a19-128">Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)</span></span>
- <span data-ttu-id="c4a19-129">Se solucionó un problema que provocaba que fallaran las instalaciones de fuente local de ProofingTools del canal PerpetualVL2019</span><span class="sxs-lookup"><span data-stu-id="c4a19-129">Fixed an issue where local source installations of ProofingTools from the PerpetualVL2019 channel were failing</span></span>
- <span data-ttu-id="c4a19-130">Se solucionó un problema para garantizar que el cliente Hacer clic y ejecutar trate de actualizarse al agregar productos adicionales en idiomas incompletos de Office a una instalación ya existente</span><span class="sxs-lookup"><span data-stu-id="c4a19-130">Fixed an issue to ensure that the Click-To-Run client attempts a self-update when adding additional products in non-full Office languages to an existing installation</span></span>


## <a name="december-8-2020"></a><span data-ttu-id="c4a19-131">8 de diciembre de 2020</span><span class="sxs-lookup"><span data-stu-id="c4a19-131">December 8, 2020</span></span>
<span data-ttu-id="c4a19-132">Versión 16.0.13426.20308 (setup.exe versión 16.0.13426.20308)</span><span class="sxs-lookup"><span data-stu-id="c4a19-132">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="c4a19-133">Se ha corregido un problema que provocaba que el modo de descarga bloqueara las descargas del canal perpetuo 2019 si el dispositivo tenía un producto de Office instalado desde un canal 2019 no perpetuo.</span><span class="sxs-lookup"><span data-stu-id="c4a19-133">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="c4a19-134">Se ha corregido un problema que provocaba que una migración de arquitectura produjera un error en un origen local creado mediante el modo de descarga que había especificado una versión explícita en el XML de configuración.</span><span class="sxs-lookup"><span data-stu-id="c4a19-134">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="c4a19-135">23 de noviembre de 2020</span><span class="sxs-lookup"><span data-stu-id="c4a19-135">November 23, 2020</span></span>
<span data-ttu-id="c4a19-136">Versión 16.0.13328.20420 (setup.exe versión 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="c4a19-136">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="c4a19-137">Se ha corregido un problema que provocaba que las herramientas de corrección no se descargaran en el modo de /descarga</span><span class="sxs-lookup"><span data-stu-id="c4a19-137">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="c4a19-138">Se ha corregido un problema que provocaba un error en el modo de /descarga al ejecutarse en un contexto de usuario no elevado</span><span class="sxs-lookup"><span data-stu-id="c4a19-138">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="c4a19-139">Se ha corregido un problema que provocaba que, al especificar un atributo de versión en el archivo XML de configuración, no se completaran las descargas en el modo de /descarga</span><span class="sxs-lookup"><span data-stu-id="c4a19-139">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="c4a19-140">Se ha corregido un problema que provocaba que la Herramienta de implementación de Office no se denominara "setup.exe" al extraerse</span><span class="sxs-lookup"><span data-stu-id="c4a19-140">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="c4a19-141">Se ha corregido un problema relacionado con la prioridad de la instalación de origen cuando se proporcionaba un atributo de canal en el archivo XML de configuración</span><span class="sxs-lookup"><span data-stu-id="c4a19-141">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="c4a19-142">10 de noviembre de 2020</span><span class="sxs-lookup"><span data-stu-id="c4a19-142">November 10, 2020</span></span>
<span data-ttu-id="c4a19-143">Version 16.0.13328.20356 (setupODT.exe versión 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="c4a19-143">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="c4a19-144">Mejoras de confiabilidad y resiliencia</span><span class="sxs-lookup"><span data-stu-id="c4a19-144">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="c4a19-145">Para evitar confusiones y diagnosticar más fácilmente los errores de configuración, la ODT ahora se denomina setupODT.exe de manera predeterminada.</span><span class="sxs-lookup"><span data-stu-id="c4a19-145">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="c4a19-146">29 de octubre de 2020</span><span class="sxs-lookup"><span data-stu-id="c4a19-146">October 29, 2020</span></span>
<span data-ttu-id="c4a19-147">Versión 16.0.13328.20292 (setup.exe versión 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="c4a19-147">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="c4a19-148">Resuelva un problema por el que determinados productos de Office 2007 puedan bloquear la instalación inesperadamente al usar RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="c4a19-148">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="c4a19-149">14 de octubre de 2020</span><span class="sxs-lookup"><span data-stu-id="c4a19-149">October 14, 2020</span></span>
<span data-ttu-id="c4a19-150">Versión 16.0.13231.20368 (setup.exe versión 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="c4a19-150">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="c4a19-151">Todos los productos ahora usarán el Canal mensual de forma predeterminada cuando no se especifique ningún canal</span><span class="sxs-lookup"><span data-stu-id="c4a19-151">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="c4a19-152">Seguridad mejorada al ejecutar ODT desde un directorio que contiene otras DLL</span><span class="sxs-lookup"><span data-stu-id="c4a19-152">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="c4a19-153">Mejoras de confiabilidad y resiliencia</span><span class="sxs-lookup"><span data-stu-id="c4a19-153">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="c4a19-154">9 de junio de 2020</span><span class="sxs-lookup"><span data-stu-id="c4a19-154">June 9, 2020</span></span>

<span data-ttu-id="c4a19-155">Versión 16.0.12827.20268 (setup.exe versión 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="c4a19-155">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="c4a19-156">El Canal actual ahora es el canal predeterminado cuando no se especifica ningún canal</span><span class="sxs-lookup"><span data-stu-id="c4a19-156">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="c4a19-157">Se agregó soporte técnico para el Canal mensual para empresas</span><span class="sxs-lookup"><span data-stu-id="c4a19-157">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="c4a19-158">Se agregó soporte técnico para los nuevos nombres del canal</span><span class="sxs-lookup"><span data-stu-id="c4a19-158">Added support for new channel names</span></span>
- <span data-ttu-id="c4a19-159">Otras características de resistencia para continuar la instalación, si es posible, incluso cuando no estén disponibles algunos recursos de idioma.</span><span class="sxs-lookup"><span data-stu-id="c4a19-159">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="c4a19-160">Funciones MSIRemove expandidas para quitar productos de Office 2007</span><span class="sxs-lookup"><span data-stu-id="c4a19-160">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="c4a19-161">Funciones MSIRemove expandidas para quitar el Motor de acceso a la base de datos</span><span class="sxs-lookup"><span data-stu-id="c4a19-161">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="c4a19-162">15 de abril de 2020</span><span class="sxs-lookup"><span data-stu-id="c4a19-162">April 15, 2020</span></span>

<span data-ttu-id="c4a19-163">Versión 16.0.12624.20320 (setup.exe versión 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="c4a19-163">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="c4a19-164">Agrega soporte técnico para las versiones finales de Office específicas de Windows 7</span><span class="sxs-lookup"><span data-stu-id="c4a19-164">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="c4a19-165">Corrige un problema en el que la configuración de personalización puede no aplicarse como se esperaba</span><span class="sxs-lookup"><span data-stu-id="c4a19-165">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="c4a19-166">Corrige un problema por el que los archivos extraños .cat se pueden descargar de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="c4a19-166">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="c4a19-167">Enero de 16 de 2020</span><span class="sxs-lookup"><span data-stu-id="c4a19-167">January 16, 2020</span></span>

<span data-ttu-id="c4a19-168">Versión 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="c4a19-168">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="c4a19-169">Corrige un problema que causaba que la interfaz de usuario de instalación de Office aparezca en un idioma incorrecto al instalar varios idiomas.</span><span class="sxs-lookup"><span data-stu-id="c4a19-169">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="c4a19-170">Corrige un problema que causaba que la instalación de Office falle inesperadamente cuando se instalaban determinados paquetes de herramientas de corrección</span><span class="sxs-lookup"><span data-stu-id="c4a19-170">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="c4a19-171">Agrega soporte para controlar, opcionalmente, la implementación inicial de la [ característica Búsqueda de Microsoft en Bing](/deployoffice/microsoft-search-bing)</span><span class="sxs-lookup"><span data-stu-id="c4a19-171">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](/deployoffice/microsoft-search-bing)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="c4a19-172">31 de octubre de 2019</span><span class="sxs-lookup"><span data-stu-id="c4a19-172">October 31, 2019</span></span>

<span data-ttu-id="c4a19-173">Versión 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="c4a19-173">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="c4a19-174">Se ha corregido un problema que permite que Skype Empresarial Basic 2019 se instale con productos de licencia por volumen perpetuo 2019</span><span class="sxs-lookup"><span data-stu-id="c4a19-174">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="c4a19-175">Se ha corregido un problema que puede ocasionar que el modo de descarga ODT falle inesperadamente en determinadas circunstancias cuando se utiliza un proxy.</span><span class="sxs-lookup"><span data-stu-id="c4a19-175">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="c4a19-176">Se ha desarrollado una nueva capacidad que permite que el modo de descarga ODT descargue a través de HTTP utilizando un puerto distinto al puerto 80.</span><span class="sxs-lookup"><span data-stu-id="c4a19-176">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="c4a19-177">10 de julio de 2019</span><span class="sxs-lookup"><span data-stu-id="c4a19-177">July 10, 2019</span></span>

<span data-ttu-id="c4a19-178">Versión 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="c4a19-178">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="c4a19-179">Compatibilidad con productos adicionales cuando se instalan con Office 2019: Access Runtime, Skype Empresarial Basic.</span><span class="sxs-lookup"><span data-stu-id="c4a19-179">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="c4a19-180">Compatibilidad con la instalación condicional de productos independientes al actualizar desde MSI.</span><span class="sxs-lookup"><span data-stu-id="c4a19-180">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="c4a19-181">23 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="c4a19-181">April 23, 2019</span></span>

<span data-ttu-id="c4a19-182">Versión 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="c4a19-182">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="c4a19-183">Se ha corregido un error con RemoveMSI=True para limpiar las configuraciones de registro relacionadas.</span><span class="sxs-lookup"><span data-stu-id="c4a19-183">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="c4a19-184">Se han actualizado los códigos de error para dar información adicional sobre errores inesperados (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="c4a19-184">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="c4a19-185">16 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="c4a19-185">April 16 2019</span></span>

<span data-ttu-id="c4a19-186">Versión 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="c4a19-186">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="c4a19-187">Compatibilidad para actualizar de C2R 32 bits a C2R 64 bits con el nuevo atributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="c4a19-187">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="c4a19-188">Se ha actualizado la lógica para /configure. Ahora permite acceder a los archivos XML de configuración almacenados en ubicaciones Web (http y https).</span><span class="sxs-lookup"><span data-stu-id="c4a19-188">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="c4a19-189">Se ha agregado MatchInstalled como un nuevo atributo que permite a la ODT coincidir con la versión existente cuando se agreguen más productos o idiomas.</span><span class="sxs-lookup"><span data-stu-id="c4a19-189">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="c4a19-190">13 de marzo de 2019</span><span class="sxs-lookup"><span data-stu-id="c4a19-190">March 13, 2019</span></span>

<span data-ttu-id="c4a19-191">Versión 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="c4a19-191">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="c4a19-192">Mejoras en situaciones de actualización y migración.</span><span class="sxs-lookup"><span data-stu-id="c4a19-192">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="c4a19-193">14 de enero de 2019</span><span class="sxs-lookup"><span data-stu-id="c4a19-193">January 14, 2019</span></span>

<span data-ttu-id="c4a19-194">Versión 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="c4a19-194">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="c4a19-195">Mejoras en el registro y la telemetría para la configuración de implementación.</span><span class="sxs-lookup"><span data-stu-id="c4a19-195">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="c4a19-196">Vínculos relacionados</span><span class="sxs-lookup"><span data-stu-id="c4a19-196">Related links</span></span>

[<span data-ttu-id="c4a19-197">Centro de descarga de ODT</span><span class="sxs-lookup"><span data-stu-id="c4a19-197">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)