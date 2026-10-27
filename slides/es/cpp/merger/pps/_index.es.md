---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Combinar archivos PPS a través de C++
weight: 8570
url: /es/cpp/merger/pps/ 
description: Código de ejemplo de C++ para combinar documentos PPS en C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits y Linux de 64 bits.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Combinar archivos PPS usando C++" h2="Fusión de documentos PPS utilizando las API de C++ del lado del servidor."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,OTP,POT,POTM,POTX,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cómo fusionar un archivo PPS usando C++" %}}

Para fusionar el archivo PPS, usaremos
 [Aspose.Slides para C++](https://products.aspose.com/slides/es/cpp/)
 API que es una API de fusión de documentos rica en funciones, potente y fácil de usar para la plataforma C ++. Puede descargar su última versión directamente, simplemente abra
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 administrador de paquetes, busque
 **Aspose.Slides.Cpp**
 e instalar También puede usar el siguiente comando desde la Consola del administrador de paquetes.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Dominio" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Fusionar archivos PPS - C++" >}}
```cs
// The path to the documents directory.
const String sourceFilePath1 = u"SourceFile2.pps";
const String sourceFilePath2 = u"SourceFile3.pps";
const String outputFilePath = u"mergedOutput.pps";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides()){
	// Merge from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Pps);  

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Pasos para fusionar archivos PPS en C++" intro="Se puede realizar una fusión y concatenación de documentos básicos con [Aspose.Slides for C++](https://products.aspose.com/slides/es/cpp/) API con solo unas pocas líneas de código." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue ambos archivos PPS.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use el método get\_Slides() para recorrer cada diapositiva.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utilice la función AddClone para combinar con el archivo deseado.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utilice el método Save() para guardar en la ruta especificada{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisitos del sistema" intro="Aspose.Slides para C++ es compatible con todas las principales plataformas y sistemas operativos. Por favor, asegúrese de que tiene los siguientes requisitos previos." %}}

- Microsoft Windows o un sistema operativo compatible con C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits y Linux de 64 bits.
- Aspose.Slides para C++ DLL a la que se hace referencia en su proyecto.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="Combinar archivos PDF en línea"
  description="[Cómo fusionar PDF en Python](https://products.aspose.com/slides/es/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPS" readMoreLink="https://docs.fileformat.com/presentation/pps/" %}}

PPS (presentación con diapositivas de PowerPoint) es el formato binario de presentación con diapositivas que usa PowerPoint 97–2003. PPSX es el formato más reciente, basado en el estándar Office Open XML. Las versiones actuales de PowerPoint pueden abrir archivos PPS y todavía pueden guardar presentaciones en formato PPS. Al abrirse de forma normal, un archivo PPS se inicia en modo de presentación, mientras que un archivo PPT se abre en modo de edición.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos de fusión admitidos" subTitle="Con C++, One también puede fusionar muchos otros formatos de archivo, incluidos..." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/merger/odp/" name="ODP" description="Formato de presentación de OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/merger/otp/" name="OTP" description="Formato estándar de OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/merger/pot/" name="POT" description="Archivos de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/merger/potm/" name="POTM" description="Archivo de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/merger/potx/" name="POTX" description="Presentación de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/merger/ppsm/" name="PPSM" description="Presentación de diapositivas habilitada para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/merger/ppsx/" name="PPSX" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/merger/pptm/" name="PPTM" description="Archivo de presentación habilitado para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/merger/pptx/" name="PPTX" description="Formato de presentación XML abierto" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
