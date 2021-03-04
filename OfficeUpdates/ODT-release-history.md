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
ms.openlocfilehash: 9425577c975122e0ebeffcefed1734a9e024fa8c
ms.sourcegitcommit: ab151c4f3172c007249a556fa02854b0765d24b9
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 03/04/2021
ms.locfileid: "50421415"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="3110f-103">Historial de versiones de la Herramienta de implementación de Office</span><span class="sxs-lookup"><span data-stu-id="3110f-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="3110f-104">La Herramienta de implementación de Office (ODT) es una herramienta de línea de comandos que puede usar para descargar e implementar versiones de hacer clic y ejecutar de Office, como aplicaciones de Microsoft 365, en sus equipos cliente.</span><span class="sxs-lookup"><span data-stu-id="3110f-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="3110f-105">ODT le ofrece más control de la instalación de Office.</span><span class="sxs-lookup"><span data-stu-id="3110f-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="3110f-106">Le permite definir los productos e idiomas que se instalarán, cómo se actualizarán esos productos y si quiere o no mostrar la experiencia de instalación a los usuarios.</span><span class="sxs-lookup"><span data-stu-id="3110f-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="3110f-107">Para obtener información sobre cómo usar la ODT, vea [Información general sobre la herramienta de implementación de Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="3110f-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="3110f-108">**Sistema operativo compatible**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="3110f-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="3110f-109">**Instrucciones de instalación**: Descargue y ejecute el archivo ejecutable autoextraíble de la Herramienta de implementación de Office (setup.exe) y un archivo de configuración de ejemplo (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="3110f-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="3110f-110">Descargar la Herramienta de implementación de Office</span><span class="sxs-lookup"><span data-stu-id="3110f-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="february-25-2021"></a><span data-ttu-id="3110f-111">25 de febrero de 2021</span><span class="sxs-lookup"><span data-stu-id="3110f-111">February 25, 2021</span></span>
<span data-ttu-id="3110f-112">Versión 16.0.13628.20476 (versión setup.exe 16.0.13628.20462)</span><span class="sxs-lookup"><span data-stu-id="3110f-112">Version 16.0.13628.20476 (setup.exe version 16.0.13628.20462)</span></span>
- <span data-ttu-id="3110f-113">Se ha corregido un problema en el que se producían errores al validar archivos configuration.xml que especificaban docenas de idiomas</span><span class="sxs-lookup"><span data-stu-id="3110f-113">Fixed an issue where configuration.xml files specifying several dozen languages was failing to validate</span></span>
- <span data-ttu-id="3110f-114">Se ha corregido un problema por el que no se respetaba la propiedad FORCEAPPSHUTDOWN en los escenarios de MigrateArch</span><span class="sxs-lookup"><span data-stu-id="3110f-114">Fixed an issue where the FORCEAPPSHUTDOWN property was not being respected in MigrateArch scenarios</span></span>
- <span data-ttu-id="3110f-115">Se ha corregido un problema por el que se producía un error al especificar 2 o más atributos PIDKEY en configuration.xml al instalar las PIDKeys</span><span class="sxs-lookup"><span data-stu-id="3110f-115">Fixed an issue where specifying 2 or more PIDKEY attributes in configuration.xml failed to install the PIDKeys</span></span>



## <a name="february-9-2021"></a><span data-ttu-id="3110f-116">9 de febrero de 2021</span><span class="sxs-lookup"><span data-stu-id="3110f-116">February 9, 2021</span></span>
<span data-ttu-id="3110f-117">Versión 16.0.13628.20274 (versión setup.exe 16.0.13628.20246)</span><span class="sxs-lookup"><span data-stu-id="3110f-117">Version 16.0.13628.20274 (setup.exe version 16.0.13628.20246)</span></span>
- <span data-ttu-id="3110f-118">Validación agregada para advertir y evitar sobre instalaciones no compatibles en Windows 8.0</span><span class="sxs-lookup"><span data-stu-id="3110f-118">Added validation to warn about and prevent unsupported installations on Windows 8.0</span></span>
- <span data-ttu-id="3110f-119">Correcciones de confiabilidad para dispositivos ARM64</span><span class="sxs-lookup"><span data-stu-id="3110f-119">Reliability fixes for ARM64 devices</span></span>


## <a name="january-12-2021"></a><span data-ttu-id="3110f-120">12 de enero de 2021</span><span class="sxs-lookup"><span data-stu-id="3110f-120">January 12, 2021</span></span>
<span data-ttu-id="3110f-121">Versión 16.0.13530.20376 (versión setup.exe 16.0.13530.20334)</span><span class="sxs-lookup"><span data-stu-id="3110f-121">Version 16.0.13530.20376 (setup.exe version 16.0.13530.20334)</span></span>
- <span data-ttu-id="3110f-122">Se ha corregido un problema por el que un registro de producto dañado o no estándar podía provocar un error en las operaciones de RemoveMSI.</span><span class="sxs-lookup"><span data-stu-id="3110f-122">Fixed an issue where corrupted or non-standard product registration could cause RemoveMSI operations to fail</span></span>

## <a name="december-21-2020"></a><span data-ttu-id="3110f-123">21 de diciembre de 2020</span><span class="sxs-lookup"><span data-stu-id="3110f-123">December 21, 2020</span></span>
<span data-ttu-id="3110f-124">Versión 16.0.13426.20370 (versión setup.exe 16.0.13426.20352)</span><span class="sxs-lookup"><span data-stu-id="3110f-124">Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)</span></span>
- <span data-ttu-id="3110f-125">Se solucionó un problema que provocaba que fallaran las instalaciones de fuente local de ProofingTools del canal PerpetualVL2019</span><span class="sxs-lookup"><span data-stu-id="3110f-125">Fixed an issue where local source installations of ProofingTools from the PerpetualVL2019 channel were failing</span></span>
- <span data-ttu-id="3110f-126">Se solucionó un problema para garantizar que el cliente Hacer clic y ejecutar trate de actualizarse al agregar productos adicionales en idiomas incompletos de Office a una instalación ya existente</span><span class="sxs-lookup"><span data-stu-id="3110f-126">Fixed an issue to ensure that the Click-To-Run client attempts a self-update when adding additional products in non-full Office languages to an existing installation</span></span>


## <a name="december-8-2020"></a><span data-ttu-id="3110f-127">8 de diciembre de 2020</span><span class="sxs-lookup"><span data-stu-id="3110f-127">December 8, 2020</span></span>
<span data-ttu-id="3110f-128">Versión 16.0.13426.20308 (setup.exe versión 16.0.13426.20308)</span><span class="sxs-lookup"><span data-stu-id="3110f-128">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="3110f-129">Se ha corregido un problema que provocaba que el modo de descarga bloqueara las descargas del canal perpetuo 2019 si el dispositivo tenía un producto de Office instalado desde un canal 2019 no perpetuo.</span><span class="sxs-lookup"><span data-stu-id="3110f-129">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="3110f-130">Se ha corregido un problema que provocaba que una migración de arquitectura produjera un error en un origen local creado mediante el modo de descarga que había especificado una versión explícita en el XML de configuración.</span><span class="sxs-lookup"><span data-stu-id="3110f-130">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="3110f-131">23 de noviembre de 2020</span><span class="sxs-lookup"><span data-stu-id="3110f-131">November 23, 2020</span></span>
<span data-ttu-id="3110f-132">Versión 16.0.13328.20420 (setup.exe versión 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="3110f-132">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="3110f-133">Se ha corregido un problema que provocaba que las herramientas de corrección no se descargaran en el modo de /descarga</span><span class="sxs-lookup"><span data-stu-id="3110f-133">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="3110f-134">Se ha corregido un problema que provocaba un error en el modo de /descarga al ejecutarse en un contexto de usuario no elevado</span><span class="sxs-lookup"><span data-stu-id="3110f-134">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="3110f-135">Se ha corregido un problema que provocaba que, al especificar un atributo de versión en el archivo XML de configuración, no se completaran las descargas en el modo de /descarga</span><span class="sxs-lookup"><span data-stu-id="3110f-135">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="3110f-136">Se ha corregido un problema que provocaba que la Herramienta de implementación de Office no se denominara "setup.exe" al extraerse</span><span class="sxs-lookup"><span data-stu-id="3110f-136">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="3110f-137">Se ha corregido un problema relacionado con la prioridad de la instalación de origen cuando se proporcionaba un atributo de canal en el archivo XML de configuración</span><span class="sxs-lookup"><span data-stu-id="3110f-137">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="3110f-138">10 de noviembre de 2020</span><span class="sxs-lookup"><span data-stu-id="3110f-138">November 10, 2020</span></span>
<span data-ttu-id="3110f-139">Version 16.0.13328.20356 (setupODT.exe versión 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="3110f-139">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="3110f-140">Mejoras de confiabilidad y resiliencia</span><span class="sxs-lookup"><span data-stu-id="3110f-140">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="3110f-141">Para evitar confusiones y diagnosticar más fácilmente los errores de configuración, la ODT ahora se denomina setupODT.exe de manera predeterminada.</span><span class="sxs-lookup"><span data-stu-id="3110f-141">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="3110f-142">29 de octubre de 2020</span><span class="sxs-lookup"><span data-stu-id="3110f-142">October 29, 2020</span></span>
<span data-ttu-id="3110f-143">Versión 16.0.13328.20292 (setup.exe versión 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="3110f-143">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="3110f-144">Resuelva un problema por el que determinados productos de Office 2007 puedan bloquear la instalación inesperadamente al usar RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="3110f-144">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="3110f-145">14 de octubre de 2020</span><span class="sxs-lookup"><span data-stu-id="3110f-145">October 14, 2020</span></span>
<span data-ttu-id="3110f-146">Versión 16.0.13231.20368 (setup.exe versión 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="3110f-146">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="3110f-147">Todos los productos ahora usarán el Canal mensual de forma predeterminada cuando no se especifique ningún canal</span><span class="sxs-lookup"><span data-stu-id="3110f-147">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="3110f-148">Seguridad mejorada al ejecutar ODT desde un directorio que contiene otras DLL</span><span class="sxs-lookup"><span data-stu-id="3110f-148">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="3110f-149">Mejoras de confiabilidad y resiliencia</span><span class="sxs-lookup"><span data-stu-id="3110f-149">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="3110f-150">9 de junio de 2020</span><span class="sxs-lookup"><span data-stu-id="3110f-150">June 9, 2020</span></span>

<span data-ttu-id="3110f-151">Versión 16.0.12827.20268 (setup.exe versión 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="3110f-151">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="3110f-152">El Canal actual ahora es el canal predeterminado cuando no se especifica ningún canal</span><span class="sxs-lookup"><span data-stu-id="3110f-152">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="3110f-153">Se agregó soporte técnico para el Canal mensual para empresas</span><span class="sxs-lookup"><span data-stu-id="3110f-153">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="3110f-154">Se agregó soporte técnico para los nuevos nombres del canal</span><span class="sxs-lookup"><span data-stu-id="3110f-154">Added support for new channel names</span></span>
- <span data-ttu-id="3110f-155">Otras características de resistencia para continuar la instalación, si es posible, incluso cuando no estén disponibles algunos recursos de idioma.</span><span class="sxs-lookup"><span data-stu-id="3110f-155">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="3110f-156">Funciones MSIRemove expandidas para quitar productos de Office 2007</span><span class="sxs-lookup"><span data-stu-id="3110f-156">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="3110f-157">Funciones MSIRemove expandidas para quitar el Motor de acceso a la base de datos</span><span class="sxs-lookup"><span data-stu-id="3110f-157">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="3110f-158">15 de abril de 2020</span><span class="sxs-lookup"><span data-stu-id="3110f-158">April 15, 2020</span></span>

<span data-ttu-id="3110f-159">Versión 16.0.12624.20320 (setup.exe versión 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="3110f-159">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="3110f-160">Agrega soporte técnico para las versiones finales de Office específicas de Windows 7</span><span class="sxs-lookup"><span data-stu-id="3110f-160">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="3110f-161">Corrige un problema en el que la configuración de personalización puede no aplicarse como se esperaba</span><span class="sxs-lookup"><span data-stu-id="3110f-161">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="3110f-162">Corrige un problema por el que los archivos extraños .cat se pueden descargar de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="3110f-162">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="3110f-163">Enero de 16 de 2020</span><span class="sxs-lookup"><span data-stu-id="3110f-163">January 16, 2020</span></span>

<span data-ttu-id="3110f-164">Versión 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="3110f-164">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="3110f-165">Corrige un problema que causaba que la interfaz de usuario de instalación de Office aparezca en un idioma incorrecto al instalar varios idiomas.</span><span class="sxs-lookup"><span data-stu-id="3110f-165">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="3110f-166">Corrige un problema que causaba que la instalación de Office falle inesperadamente cuando se instalaban determinados paquetes de herramientas de corrección</span><span class="sxs-lookup"><span data-stu-id="3110f-166">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="3110f-167">Agrega soporte para controlar, opcionalmente, la implementación inicial de la [ característica Búsqueda de Microsoft en Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span><span class="sxs-lookup"><span data-stu-id="3110f-167">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="3110f-168">31 de octubre de 2019</span><span class="sxs-lookup"><span data-stu-id="3110f-168">October 31, 2019</span></span>

<span data-ttu-id="3110f-169">Versión 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="3110f-169">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="3110f-170">Se ha corregido un problema que permite que Skype Empresarial Basic 2019 se instale con productos de licencia por volumen perpetuo 2019</span><span class="sxs-lookup"><span data-stu-id="3110f-170">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="3110f-171">Se ha corregido un problema que puede ocasionar que el modo de descarga ODT falle inesperadamente en determinadas circunstancias cuando se utiliza un proxy.</span><span class="sxs-lookup"><span data-stu-id="3110f-171">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="3110f-172">Se ha desarrollado una nueva capacidad que permite que el modo de descarga ODT descargue a través de HTTP utilizando un puerto distinto al puerto 80.</span><span class="sxs-lookup"><span data-stu-id="3110f-172">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="3110f-173">10 de julio de 2019</span><span class="sxs-lookup"><span data-stu-id="3110f-173">July 10, 2019</span></span>

<span data-ttu-id="3110f-174">Versión 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="3110f-174">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="3110f-175">Compatibilidad con productos adicionales cuando se instalan con Office 2019: Access Runtime, Skype Empresarial Basic.</span><span class="sxs-lookup"><span data-stu-id="3110f-175">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="3110f-176">Compatibilidad con la instalación condicional de productos independientes al actualizar desde MSI.</span><span class="sxs-lookup"><span data-stu-id="3110f-176">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="3110f-177">23 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="3110f-177">April 23, 2019</span></span>

<span data-ttu-id="3110f-178">Versión 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="3110f-178">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="3110f-179">Se ha corregido un error con RemoveMSI=True para limpiar las configuraciones de registro relacionadas.</span><span class="sxs-lookup"><span data-stu-id="3110f-179">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="3110f-180">Se han actualizado los códigos de error para dar información adicional sobre errores inesperados (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="3110f-180">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="3110f-181">16 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="3110f-181">April 16 2019</span></span>

<span data-ttu-id="3110f-182">Versión 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="3110f-182">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="3110f-183">Compatibilidad para actualizar de C2R 32 bits a C2R 64 bits con el nuevo atributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="3110f-183">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="3110f-184">Se ha actualizado la lógica para /configure. Ahora permite acceder a los archivos XML de configuración almacenados en ubicaciones Web (http y https).</span><span class="sxs-lookup"><span data-stu-id="3110f-184">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="3110f-185">Se ha agregado MatchInstalled como un nuevo atributo que permite a la ODT coincidir con la versión existente cuando se agreguen más productos o idiomas.</span><span class="sxs-lookup"><span data-stu-id="3110f-185">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="3110f-186">13 de marzo de 2019</span><span class="sxs-lookup"><span data-stu-id="3110f-186">March 13, 2019</span></span>

<span data-ttu-id="3110f-187">Versión 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="3110f-187">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="3110f-188">Mejoras en situaciones de actualización y migración.</span><span class="sxs-lookup"><span data-stu-id="3110f-188">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="3110f-189">14 de enero de 2019</span><span class="sxs-lookup"><span data-stu-id="3110f-189">January 14, 2019</span></span>

<span data-ttu-id="3110f-190">Versión 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="3110f-190">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="3110f-191">Mejoras en el registro y la telemetría para la configuración de implementación.</span><span class="sxs-lookup"><span data-stu-id="3110f-191">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="3110f-192">Vínculos relacionados</span><span class="sxs-lookup"><span data-stu-id="3110f-192">Related links</span></span>

[<span data-ttu-id="3110f-193">Centro de descarga de ODT</span><span class="sxs-lookup"><span data-stu-id="3110f-193">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)