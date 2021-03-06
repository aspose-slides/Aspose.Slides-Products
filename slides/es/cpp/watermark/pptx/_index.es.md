---
title: Documento de marca de agua PPTX a través de C ++
weight: 2900
url: /es/cpp/watermark/pptx/ 
description: Código de ejemplo de C++ para agregar o eliminar una marca de agua en un archivo PPTX en C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits y Linux de 64 bits.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Agregar marca de agua de texto a PPTX a través de C++" h2="Cree sus propias aplicaciones de C++ para marcar con agua archivos PPTX utilizando las API del lado del servidor." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo poner una marca de agua en un archivo PPTX usando C++" %}}

 Para agregar una marca de agua al archivo PPTX, usaremos
 [Aspose.Slides para C++](https://products.aspose.com/slides/es/cpp)
 API que es una API de marca de agua de documentos rica en funciones, potente y fácil de usar para la plataforma C ++. Puede descargar su última versión directamente, simplemente abra
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 administrador de paquetes, busque
 **Aspose.Slides.Cpp**
 e instalar También puede usar el siguiente comando desde la Consola del administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Dominio" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Pasos para agregar una marca de agua a PPTX a través de C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Necesita [aspose.slides.dll](https://downloads.aspose.com/slides/cpp) para probar el siguiente flujo de trabajo en su propio entorno." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue archivos PPTX con una instancia de clase de presentación
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Obtener la primera diapositiva
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregar una autoforma de tipo rectángulo
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Añadir TextFrame al Rectángulo
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crear el objeto Párrafo para marco de texto
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crear objeto de porción para párrafo
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregar marca de agua usando set\_Text()
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guardar documento
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides para C++ es compatible con todas las principales plataformas y sistemas operativos. Por favor, asegúrese de que tiene los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Añadir marca de agua a PPTX - C++" offSpacer="" %}}

```cs

// Load the desired PPTX File
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"templatePath.pptx");

// Access first slide
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150, 75, 150, 50);

ashp->get_FillFormat()->set_FillType(FillType::NoFill);

// Add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");

// Accessing the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();

// Create the Paragraph object for text frame
SharedPtr<IParagraph> paragraph = txtFrame->get_Paragraphs()->idx_get(0);

// Create Portion object for paragraph
SharedPtr<IPortion> portion = paragraph->get_Portions()->idx_get(0);
portion->set_Text(u"Watermark Text Watermark Text Watermark Text");

//Adding another shape
SharedPtr<IAutoShape>  ashape2 = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 200, 365, 400, 150);

//Reorder shape
slide->get_Shapes()->Reorder(2, ashape2);

// Save PPTX to Disk
pres->Save(u"outPath.pptx", Aspose::Slides::Export::SaveFormat::Pptx);  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Acerca de Aspose.Slides para la API de C++" %}}

 Aspose.Slides API se puede utilizar para leer, escribir, manipular y convertir documentos de Microsoft PowerPoint a PDF, XPS, HTML, TIFF, ODP y varios otros formatos. Uno puede crear nuevos archivos desde cero y guardarlos en los formatos compatibles relevantes. Aspose.Slides es una API independiente para crear, analizar o manipular presentaciones, diapositivas y elementos y no depende de ningún software como Microsoft u OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Watermark PPTX via Online App" sectionDescription="Add watermark to PPTX documents by visiting our [Live Demos website](https://products.aspose.app/slides/watermark). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your PPTX file, set your watermark and hit \"Add\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" >}}
Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos de marca de agua admitidos" subTitle="Usando C ++, uno puede marcar fácilmente diferentes formatos, incluidos." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/watermark/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}