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
ms.openlocfilehash: 125f37f1fb4b21d2d63784e51703c1297d928f49
ms.sourcegitcommit: c7f7982f4d2d0d8db4fc4fbf961b79a03bc8b36e
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 12/08/2020
ms.locfileid: "49601415"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="d9038-103">Historial de versiones de la Herramienta de implementación de Office</span><span class="sxs-lookup"><span data-stu-id="d9038-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="d9038-104">La Herramienta de implementación de Office (ODT) es una herramienta de línea de comandos que puede usar para descargar e implementar versiones de hacer clic y ejecutar de Office, como aplicaciones de Microsoft 365, en sus equipos cliente.</span><span class="sxs-lookup"><span data-stu-id="d9038-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="d9038-105">ODT le ofrece más control de la instalación de Office.</span><span class="sxs-lookup"><span data-stu-id="d9038-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="d9038-106">Le permite definir los productos e idiomas que se instalarán, cómo se actualizarán esos productos y si quiere o no mostrar la experiencia de instalación a los usuarios.</span><span class="sxs-lookup"><span data-stu-id="d9038-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="d9038-107">Para obtener información sobre cómo usar la ODT, vea [Información general sobre la herramienta de implementación de Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="d9038-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="d9038-108">**Sistema operativo compatible**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="d9038-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="d9038-109">**Instrucciones de instalación**: Descargue y ejecute el archivo ejecutable autoextraíble de la Herramienta de implementación de Office (setup.exe) y un archivo de configuración de ejemplo (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="d9038-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="d9038-110">Descargar la Herramienta de implementación de Office</span><span class="sxs-lookup"><span data-stu-id="d9038-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="december-8-2020"></a><span data-ttu-id="d9038-111">8 de diciembre de 2020</span><span class="sxs-lookup"><span data-stu-id="d9038-111">December 8, 2020</span></span>
<span data-ttu-id="d9038-112">Versión 16.0.13426.20308 (setup.exe versión 16.0.13426.20308)</span><span class="sxs-lookup"><span data-stu-id="d9038-112">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="d9038-113">Se ha corregido un problema que provocaba que el modo de descarga bloqueara las descargas del canal perpetuo 2019 si el dispositivo tenía un producto de Office instalado desde un canal 2019 no perpetuo.</span><span class="sxs-lookup"><span data-stu-id="d9038-113">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="d9038-114">Se ha corregido un problema que provocaba que una migración de arquitectura produjera un error en un origen local creado mediante el modo de descarga que había especificado una versión explícita en el XML de configuración.</span><span class="sxs-lookup"><span data-stu-id="d9038-114">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="d9038-115">23 de noviembre de 2020</span><span class="sxs-lookup"><span data-stu-id="d9038-115">November 23, 2020</span></span>
<span data-ttu-id="d9038-116">Versión 16.0.13328.20420 (setup.exe versión 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="d9038-116">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="d9038-117">Se ha corregido un problema que provocaba que las herramientas de corrección no se descargaran en el modo de /descarga</span><span class="sxs-lookup"><span data-stu-id="d9038-117">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="d9038-118">Se ha corregido un problema que provocaba un error en el modo de /descarga al ejecutarse en un contexto de usuario no elevado</span><span class="sxs-lookup"><span data-stu-id="d9038-118">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="d9038-119">Se ha corregido un problema que provocaba que, al especificar un atributo de versión en el archivo XML de configuración, no se completaran las descargas en el modo de /descarga</span><span class="sxs-lookup"><span data-stu-id="d9038-119">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="d9038-120">Se ha corregido un problema que provocaba que la Herramienta de implementación de Office no se denominara "setup.exe" al extraerse</span><span class="sxs-lookup"><span data-stu-id="d9038-120">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="d9038-121">Se ha corregido un problema relacionado con la prioridad de la instalación de origen cuando se proporcionaba un atributo de canal en el archivo XML de configuración</span><span class="sxs-lookup"><span data-stu-id="d9038-121">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="d9038-122">10 de noviembre de 2020</span><span class="sxs-lookup"><span data-stu-id="d9038-122">November 10, 2020</span></span>
<span data-ttu-id="d9038-123">Version 16.0.13328.20356 (setupODT.exe versión 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="d9038-123">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="d9038-124">Mejoras de confiabilidad y resiliencia</span><span class="sxs-lookup"><span data-stu-id="d9038-124">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="d9038-125">Para evitar confusiones y diagnosticar más fácilmente los errores de configuración, la ODT ahora se denomina setupODT.exe de manera predeterminada.</span><span class="sxs-lookup"><span data-stu-id="d9038-125">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="d9038-126">29 de octubre de 2020</span><span class="sxs-lookup"><span data-stu-id="d9038-126">October 29, 2020</span></span>
<span data-ttu-id="d9038-127">Versión 16.0.13328.20292 (setup.exe versión 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="d9038-127">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="d9038-128">Resuelva un problema por el que determinados productos de Office 2007 puedan bloquear la instalación inesperadamente al usar RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="d9038-128">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="d9038-129">14 de octubre de 2020</span><span class="sxs-lookup"><span data-stu-id="d9038-129">October 14, 2020</span></span>
<span data-ttu-id="d9038-130">Versión 16.0.13231.20368 (setup.exe versión 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="d9038-130">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="d9038-131">Todos los productos ahora usarán el Canal mensual de forma predeterminada cuando no se especifique ningún canal</span><span class="sxs-lookup"><span data-stu-id="d9038-131">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="d9038-132">Seguridad mejorada al ejecutar ODT desde un directorio que contiene otras DLL</span><span class="sxs-lookup"><span data-stu-id="d9038-132">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="d9038-133">Mejoras de confiabilidad y resiliencia</span><span class="sxs-lookup"><span data-stu-id="d9038-133">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="d9038-134">9 de junio de 2020</span><span class="sxs-lookup"><span data-stu-id="d9038-134">June 9, 2020</span></span>

<span data-ttu-id="d9038-135">Versión 16.0.12827.20268 (setup.exe versión 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="d9038-135">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="d9038-136">El Canal actual ahora es el canal predeterminado cuando no se especifica ningún canal</span><span class="sxs-lookup"><span data-stu-id="d9038-136">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="d9038-137">Se agregó soporte técnico para el Canal mensual para empresas</span><span class="sxs-lookup"><span data-stu-id="d9038-137">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="d9038-138">Se agregó soporte técnico para los nuevos nombres del canal</span><span class="sxs-lookup"><span data-stu-id="d9038-138">Added support for new channel names</span></span>
- <span data-ttu-id="d9038-139">Otras características de resistencia para continuar la instalación, si es posible, incluso cuando no estén disponibles algunos recursos de idioma.</span><span class="sxs-lookup"><span data-stu-id="d9038-139">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="d9038-140">Funciones MSIRemove expandidas para quitar productos de Office 2007</span><span class="sxs-lookup"><span data-stu-id="d9038-140">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="d9038-141">Funciones MSIRemove expandidas para quitar el Motor de acceso a la base de datos</span><span class="sxs-lookup"><span data-stu-id="d9038-141">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="d9038-142">15 de abril de 2020</span><span class="sxs-lookup"><span data-stu-id="d9038-142">April 15, 2020</span></span>

<span data-ttu-id="d9038-143">Versión 16.0.12624.20320 (setup.exe versión 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="d9038-143">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="d9038-144">Agrega soporte técnico para las versiones finales de Office específicas de Windows 7</span><span class="sxs-lookup"><span data-stu-id="d9038-144">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="d9038-145">Corrige un problema en el que la configuración de personalización puede no aplicarse como se esperaba</span><span class="sxs-lookup"><span data-stu-id="d9038-145">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="d9038-146">Corrige un problema por el que los archivos extraños .cat se pueden descargar de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="d9038-146">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="d9038-147">Enero de 16 de 2020</span><span class="sxs-lookup"><span data-stu-id="d9038-147">January 16, 2020</span></span>

<span data-ttu-id="d9038-148">Versión 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="d9038-148">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="d9038-149">Corrige un problema que causaba que la interfaz de usuario de instalación de Office aparezca en un idioma incorrecto al instalar varios idiomas.</span><span class="sxs-lookup"><span data-stu-id="d9038-149">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="d9038-150">Corrige un problema que causaba que la instalación de Office falle inesperadamente cuando se instalaban determinados paquetes de herramientas de corrección</span><span class="sxs-lookup"><span data-stu-id="d9038-150">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="d9038-151">Agrega soporte para controlar, opcionalmente, la implementación inicial de la [ característica Búsqueda de Microsoft en Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span><span class="sxs-lookup"><span data-stu-id="d9038-151">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="d9038-152">31 de octubre de 2019</span><span class="sxs-lookup"><span data-stu-id="d9038-152">October 31, 2019</span></span>

<span data-ttu-id="d9038-153">Versión 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="d9038-153">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="d9038-154">Se ha corregido un problema que permite que Skype Empresarial Basic 2019 se instale con productos de licencia por volumen perpetuo 2019</span><span class="sxs-lookup"><span data-stu-id="d9038-154">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="d9038-155">Se ha corregido un problema que puede ocasionar que el modo de descarga ODT falle inesperadamente en determinadas circunstancias cuando se utiliza un proxy.</span><span class="sxs-lookup"><span data-stu-id="d9038-155">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="d9038-156">Se ha desarrollado una nueva capacidad que permite que el modo de descarga ODT descargue a través de HTTP utilizando un puerto distinto al puerto 80.</span><span class="sxs-lookup"><span data-stu-id="d9038-156">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="d9038-157">10 de julio de 2019</span><span class="sxs-lookup"><span data-stu-id="d9038-157">July 10, 2019</span></span>

<span data-ttu-id="d9038-158">Versión 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="d9038-158">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="d9038-159">Compatibilidad con productos adicionales cuando se instalan con Office 2019: Access Runtime, Skype Empresarial Basic.</span><span class="sxs-lookup"><span data-stu-id="d9038-159">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="d9038-160">Compatibilidad con la instalación condicional de productos independientes al actualizar desde MSI.</span><span class="sxs-lookup"><span data-stu-id="d9038-160">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="d9038-161">23 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="d9038-161">April 23, 2019</span></span>

<span data-ttu-id="d9038-162">Versión 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="d9038-162">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="d9038-163">Se ha corregido un error con RemoveMSI=True para limpiar las configuraciones de registro relacionadas.</span><span class="sxs-lookup"><span data-stu-id="d9038-163">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="d9038-164">Se han actualizado los códigos de error para dar información adicional sobre errores inesperados (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="d9038-164">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="d9038-165">16 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="d9038-165">April 16 2019</span></span>

<span data-ttu-id="d9038-166">Versión 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="d9038-166">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="d9038-167">Compatibilidad para actualizar de C2R 32 bits a C2R 64 bits con el nuevo atributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="d9038-167">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="d9038-168">Se ha actualizado la lógica para /configure. Ahora permite acceder a los archivos XML de configuración almacenados en ubicaciones Web (http y https).</span><span class="sxs-lookup"><span data-stu-id="d9038-168">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="d9038-169">Se ha agregado MatchInstalled como un nuevo atributo que permite a la ODT coincidir con la versión existente cuando se agreguen más productos o idiomas.</span><span class="sxs-lookup"><span data-stu-id="d9038-169">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="d9038-170">13 de marzo de 2019</span><span class="sxs-lookup"><span data-stu-id="d9038-170">March 13, 2019</span></span>

<span data-ttu-id="d9038-171">Versión 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="d9038-171">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="d9038-172">Mejoras en situaciones de actualización y migración.</span><span class="sxs-lookup"><span data-stu-id="d9038-172">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="d9038-173">14 de enero de 2019</span><span class="sxs-lookup"><span data-stu-id="d9038-173">January 14, 2019</span></span>

<span data-ttu-id="d9038-174">Versión 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="d9038-174">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="d9038-175">Mejoras en el registro y la telemetría para la configuración de implementación.</span><span class="sxs-lookup"><span data-stu-id="d9038-175">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="d9038-176">Vínculos relacionados</span><span class="sxs-lookup"><span data-stu-id="d9038-176">Related links</span></span>

[<span data-ttu-id="d9038-177">Centro de descarga de ODT</span><span class="sxs-lookup"><span data-stu-id="d9038-177">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)