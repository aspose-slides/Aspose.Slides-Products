---
title: Combinar archivos PPT a través de .NET
weight: 7610
url: /es/net/merger/ppt/ 
description: Código fuente C# para combinar documentos PPT en plataformas .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Combinar formatos PPT en C#" h2="Fusión de documentos PPT nativos y de alto rendimiento utilizando Aspose.Slides del lado del servidor para las API de .NET, sin el uso de ningún software como Microsoft u Open Office, Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo fusionar archivos PPT usando C#" %}}

 Para fusionar el archivo PPT, usaremos
 [Aspose.Slides para .NET](https://products.aspose.com/slides/net)
 API, que es una API de combinación y manipulación de documentos rica en funciones, potente y fácil de usar para la plataforma C#. Abierto
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 administrador de paquetes, busque
 **Aspose.Diapositivas**
 e instalar También puede usar el siguiente comando desde la Consola del administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Dominio" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Pasos para fusionar archivos PPT en C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Se puede realizar una fusión y concatenación de documentos básicos con [Aspose.Slides for .NET](https://products.aspose.com/slides/net) API con solo unas pocas líneas de código." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue todos los archivos PPT con la ruta completa.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hacer un documento como el archivo base
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Llame al método relevante para concatenar y fusionar archivos uno por uno.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Llame al método Save() y pase el nombre del archivo (ruta completa) y el formato (PPT) como parámetro.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ahora puede abrir y usar el archivo PPT en Microsoft Office, Adobe PDF o cualquier otro programa compatible.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Nuestras API son compatibles con todas las principales plataformas y sistemas operativos. Antes de ejecutar el código a continuación, asegúrese de tener los siguientes requisitos previos en su sistema.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con las plataformas .NET Framework, .NET Core, Windows Azure, Mono o Xamarin
- Entorno de desarrollo como Microsoft Visual Studio
- Aspose.Slides para .NET DLL a la que se hace referencia en su proyecto - Instale desde NuGet usando el botón Descargar arriba

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Combinar archivos PPT - C#" offSpacer="" %}}

```cs
var ps1 = new Presentation("presen1.ppt");
    var ps2 = new Presentation("presen2.pptx");
    
    //merged Presentation 
    var mp = new Presentation("template.pptx");
    while (mp.Slides.Count > 0){
        mp.Slides.RemoveAt(0);
    }
    // master slide
    var ms = mp.Masters[0];
    
    // The first PPT presentation is added with its own styles.
    foreach (var slide in ps1.Slides){
        mp.Slides.AddClone(slide);
    }
    
    // The second PPTX presentation is added with template presentation styles using.
    foreach (var slide in ps2.Slides){
        mp.Slides.AddClone(slide, ms, true);
    }
    
    // It is possible to save the merged presentation to any supported format.
    mp.Save("mp.pptx", SaveFormat.Pptx);
    mp.Save("mp.pptx", SaveFormat.Pdf);  

    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Acerca de Aspose.Slides para la API de .NET" %}}

 Aspose.Slides API se puede utilizar para leer, escribir, manipular y convertir documentos de Microsoft PowerPoint a PDF, XPS, HTML, TIFF, ODP y varios otros formatos. Uno puede crear nuevos archivos desde cero y guardarlos en los formatos compatibles relevantes. Aspose.Slides es una API independiente para crear, analizar o manipular presentaciones, diapositivas y elementos y no depende de ningún software como Microsoft u OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online PPT Merger Live Demos" sectionDescription="Merge PPT documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/merger). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your PPT files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be merged and concatenated instantly." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos de fusión admitidos" subTitle="Usando C#, One también puede fusionar muchos otros formatos de archivo, incluidos." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merger/odp/" name="ODP" description="Formato de presentación de OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merger/otp/" name="OTP" description="Formato estándar de OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merger/pot/" name="POT" description="Archivos de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merger/potm/" name="POTM" description="Archivo de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merger/potx/" name="POTX" description="Presentación de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merger/pps/" name="PPS" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merger/ppsm/" name="PPSM" description="Presentación de diapositivas habilitada para macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merger/ppsx/" name="PPSX" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merger/pptm/" name="PPTM" description="Archivo de presentación habilitado para macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merger/pptx/" name="PPTX" description="Formato de presentación XML abierto" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}