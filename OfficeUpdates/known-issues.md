---
title: Problemas conocidos de Office 365 ProPlus
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: Ofrece información acerca de los problemas conocidos de Office 365 ProPlus
ms.openlocfilehash: a8b385e197a6f61c10797bf160101cdd70285aaf
ms.sourcegitcommit: a6d8dba3ee51727c2d3a2dad89cb986595c1a7b8
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 09/20/2019
ms.locfileid: "37068064"
---
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="00ab2-103">Problemas conocidos de Office 365 ProPlus</span><span class="sxs-lookup"><span data-stu-id="00ab2-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="00ab2-104">Estos problemas conocidos proporcionan información sobre actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones del Canal mensual, SACT y SAC de Office 365 ProPlus 2019, Visio Pro para Office 365, el Cliente de escritorio de Project Online y Office 365 Empresa.</span><span class="sxs-lookup"><span data-stu-id="00ab2-104">These release notes provide information about new features and non-security updates that are included in Monthly Channel updates to Office 365 ProPlus in 2019, including Visio Pro for Office 365 and Project Online Desktop Client.</span></span>

<span data-ttu-id="00ab2-105">En esta tabla se ofrece un resumen de los problemas actualmente activos y los problemas resueltos.</span><span class="sxs-lookup"><span data-stu-id="00ab2-105">This table offers a summary of current active issues and those issues that have been resolved.</span></span>  <span data-ttu-id="00ab2-106">La siguiente tabla se actualizará con los problema importantes que se están investigando.</span><span class="sxs-lookup"><span data-stu-id="00ab2-106">We will update the table below with significant issues we are investigating.</span></span>

 > [!NOTE]
 >- <span data-ttu-id="00ab2-107">Esta lista no es exhaustiva.</span><span class="sxs-lookup"><span data-stu-id="00ab2-107">This list is not comprehensive.</span></span>

<br>

## <a name="september-2019"></a><span data-ttu-id="00ab2-108">Septiembre de 2019</span><span class="sxs-lookup"><span data-stu-id="00ab2-108">September 10, 2019</span></span>

|<span data-ttu-id="00ab2-109">Resumen</span><span class="sxs-lookup"><span data-stu-id="00ab2-109">Summary</span></span>|<span data-ttu-id="00ab2-110">Investigando</span><span class="sxs-lookup"><span data-stu-id="00ab2-110">Investigating</span></span>|<span data-ttu-id="00ab2-111">Resuelto</span><span class="sxs-lookup"><span data-stu-id="00ab2-111">Resolved</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="00ab2-112">**Outlook**</span><span class="sxs-lookup"><span data-stu-id="00ab2-112">**Outlook**</span></span>
<span data-ttu-id="00ab2-113">Se ha encontrado un problema que podía impedir guardar archivos en una ubicación de WebDAV</span><span class="sxs-lookup"><span data-stu-id="00ab2-113">We found an issue which could have prevented files from being saved to a WebDAV location.</span></span>|<span data-ttu-id="00ab2-114">Versión mensual 1909</span><span class="sxs-lookup"><span data-stu-id="00ab2-114">Monthly Version 1909</span></span>||
|<span data-ttu-id="00ab2-115">**Proyecto**</span><span class="sxs-lookup"><span data-stu-id="00ab2-115">**Project**</span></span>
<span data-ttu-id="00ab2-116">Tenga en cuenta el siguiente escenario.</span><span class="sxs-lookup"><span data-stu-id="00ab2-116">Consider the following scenario.</span></span> <span data-ttu-id="00ab2-117">Abra un proyecto</span><span class="sxs-lookup"><span data-stu-id="00ab2-117">You open a project.</span></span> <span data-ttu-id="00ab2-118">Haga clic en el menú Archivo, haga clic en exportar y haga clic en el botón Crear PDF/XPS.</span><span class="sxs-lookup"><span data-stu-id="00ab2-118">You click the File menu, click Export and click the Create PDF/XPS button.</span></span> <span data-ttu-id="00ab2-119">En el cuadro de diálogo Examinar, escriba un nombre de archivo y haga clic en Aceptar.</span><span class="sxs-lookup"><span data-stu-id="00ab2-119">Within the Browse dialog box, you enter a file name and click OK.</span></span> <span data-ttu-id="00ab2-120">En esta situación, descubre que no se crea el archivo PDF de XPS.</span><span class="sxs-lookup"><span data-stu-id="00ab2-120">In this situation, you find that the PDF of XPS file is not created.</span></span> |<span data-ttu-id="00ab2-121">Versión SAC 1902</span><span class="sxs-lookup"><span data-stu-id="00ab2-121">SAC Version 1902</span></span>||
|<span data-ttu-id="00ab2-122">**Word**</span><span class="sxs-lookup"><span data-stu-id="00ab2-122">**Word**</span></span>
<span data-ttu-id="00ab2-123">Encontramos un problema que se presenta a los usuarios al abrir un archivo.</span><span class="sxs-lookup"><span data-stu-id="00ab2-123">We found an issue users could hit on opening a file.</span></span>|<span data-ttu-id="00ab2-124">Versión mensual 1908</span><span class="sxs-lookup"><span data-stu-id="00ab2-124">Monthly Version 1908</span></span>||
<span data-ttu-id="00ab2-125">En el caso de archivos de Office sincronizados con el motor de sincronización de OneDrive, los metadatos de los documentos, como Requerir propiedades y requisitos de Tipo de contenido, ya no se validan al usar los comandos Guardar y Guardar como.</span><span class="sxs-lookup"><span data-stu-id="00ab2-125">For Office files synced by the OneDrive Sync Engine, document metadata such as Require Properties and Content Type requirements are no longer validated upon Save and Save As.</span></span>|<span data-ttu-id="00ab2-126">Versión SAC 1902</span><span class="sxs-lookup"><span data-stu-id="00ab2-126">SAC Version 1902</span></span>||

## <a name="may-2019---sample"></a><span data-ttu-id="00ab2-127">Mayo de 2019 - MUESTRA</span><span class="sxs-lookup"><span data-stu-id="00ab2-127">May 2019 - SAMPLE</span></span>

|<span data-ttu-id="00ab2-128">Resumen</span><span class="sxs-lookup"><span data-stu-id="00ab2-128">Summary</span></span>|<span data-ttu-id="00ab2-129">Investigando</span><span class="sxs-lookup"><span data-stu-id="00ab2-129">Investigating</span></span>|<span data-ttu-id="00ab2-130">Resuelto</span><span class="sxs-lookup"><span data-stu-id="00ab2-130">Resolved</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="00ab2-131">**Excel**</span><span class="sxs-lookup"><span data-stu-id="00ab2-131">**Excel**</span></span>
<span data-ttu-id="00ab2-132">Ejemplo resuelto en varias compilaciones. Hemos detectado un problema por el que los gráficos de cascada y embudo dejaban de estar sincronizados con las tablas al insertar o eliminar celdas.</span><span class="sxs-lookup"><span data-stu-id="00ab2-132">Sample resoved in multiple builds -- We found an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>||<span data-ttu-id="00ab2-133">Versión SAC 1902</span><span class="sxs-lookup"><span data-stu-id="00ab2-133">SAC Version 1902</span></span> <br> <span data-ttu-id="00ab2-134">(16.0.11328.20306)</span><span class="sxs-lookup"><span data-stu-id="00ab2-134">(16.0.11328.20306)</span></span> <br> <span data-ttu-id="00ab2-135">Versión mensual 1905</span><span class="sxs-lookup"><span data-stu-id="00ab2-135">Monthly Version 1905</span></span> <br> <span data-ttu-id="00ab2-136">(16.0.11629.20210)</span><span class="sxs-lookup"><span data-stu-id="00ab2-136">(16.0.11629.20210)</span></span>|
|<span data-ttu-id="00ab2-137">**Word**</span><span class="sxs-lookup"><span data-stu-id="00ab2-137">**Word**</span></span>
<span data-ttu-id="00ab2-138">Ejemplo resuelto en algunas compilaciones, no en todas. Hemos detectado un problema con el rendimiento al habilitar Elementos rápidos para Propiedades del documento.</span><span class="sxs-lookup"><span data-stu-id="00ab2-138">Sample resoved in some builds, not all -- We found an issue with performance when enabling Quick Parts for Document propertiesk.</span></span>|<span data-ttu-id="00ab2-139">Versión SAC 1808</span><span class="sxs-lookup"><span data-stu-id="00ab2-139">SAC Version 1808</span></span>|<span data-ttu-id="00ab2-140">Versión SAC 1902</span><span class="sxs-lookup"><span data-stu-id="00ab2-140">SAC Version 1902</span></span> <br> <span data-ttu-id="00ab2-141">(16.0.11328.20340)</span><span class="sxs-lookup"><span data-stu-id="00ab2-141">(16.0.11328.20340)</span></span>|

<br>
<br>

> [!NOTE]
> <span data-ttu-id="00ab2-142">Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="00ab2-142">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
