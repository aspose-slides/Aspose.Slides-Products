---
title: Convierta PPTX a GIF a través de la aplicación C ++
weight: 8510
url: /es/cpp/conversion/pptx-to-gif/ 
description: Ejemplo de código de conversión de C++ para documentos PPTX a formato GIF. Use un código de ejemplo para la conversión por lotes de PPTX a GIF dentro de cualquier aplicación C++.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Convierte PPTX a GIF a través de C++" h2="Conversión de PPTX a GIF de alto rendimiento utilizando la biblioteca C++ sin necesidad de instalar Microsoft PowerPoint." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir PPTX a GIF usando C++" %}}

 Para convertir PPTX a GIF, usaremos
 [Aspose.Slides para C++](https://products.aspose.com/slides/es/cpp)
 API que es una API de manipulación y conversión de documentos rica en funciones, potente y fácil de usar para la plataforma C ++. Puede descargar su última versión directamente, simplemente abra
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 administrador de paquetes, busque
 Aspose.Slides.Cpp
 e instalar También puede usar el siguiente comando desde la Consola del administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Dominio" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir PPTX a GIF a través de C++" %}}

{{% blocks/products/pf/agp/text %}}

 Los desarrolladores de C++ pueden convertir fácilmente un archivo PPTX a GIF con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargue el archivo PPTX con Aspose.Slides para C++ Presentation Object.
1. Seleccione la primera diapositiva.
1. Establezca las dimensiones deseadas.
1. Obtenga la miniatura con las dimensiones deseadas.
1. Llame al método Save() que tiene el parámetro de salida GIF.
1. Abra el archivo GIF en un programa compatible.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código de ejemplo de conversión de C++, asegúrese de tener los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits y Linux de 64 bits.
- Aspose.Slides para C++ DLL a la que se hace referencia en su proyecto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código fuente de conversión de PPTX a GIF C++" offSpacer="" %}}

```cs
// Load the PPTX
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.pptx");

// Access the first slide
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// User defined dimension
int desiredX = 1200;
int desiredY = 800;

// Getting scaled value  of X and Y
float ScaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float ScaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

// Create a custom scale image
auto bitmap = slide->GetThumbnail(ScaleX, ScaleY);

bitmap->Save(u"output.gif", ImageFormat::get_Gif());
	
//Iterate through each slide via index and convert

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="pptx-to-gif"
        sectionTitle="Aplicación gratuita para convertir PPTX a GIF" 
        sectionDescription="[Pruebe nuestra aplicación gratuita Collage](https://products.aspose.app/slides/collage/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir PPTX a muchos otros formatos de archivo, incluidos algunos de los que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="Imagen de mapa de bits" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-emf/" name="PPTX TO EMF" description="Formato de metarchivo mejorado" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-html/" name="PPTX TO HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" description="Imagen JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-odp/" name="PPTX TO ODP" description="Formato de presentación de OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-otp/" name="PPTX TO OTP" description="Formato estándar de OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="Formato de Documento Portable" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-png/" name="PPTX TO PNG" description="Gráficos de red portátiles" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-pot/" name="PPTX TO POT" description="Archivos de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-potm/" name="PPTX TO POTM" description="Archivo de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Presentación de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-pps/" name="PPTX TO PPS" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Presentación de diapositivas habilitada para macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="Archivo de presentación habilitado para macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-svg/" name="PPTX TO SVG" description="gráficas vectoriales escalables" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Formato de imagen etiquetada" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-xml/" name="PPTX TO XML" description="Lenguaje de marcado extensible" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-xps/" name="PPTX TO XPS" description="Especificaciones de papel XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}