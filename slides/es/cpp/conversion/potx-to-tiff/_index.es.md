---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convierta POTX a TIFF a través de la aplicación C ++
weight: 370
url: /es/cpp/conversion/potx-to-tiff/ 
description: Ejemplo de código de conversión de C++ para documento POTX a formato TIFF. Utilice un código de ejemplo para la conversión por lotes de POTX a TIFF dentro de cualquier aplicación C++.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convierta POTX a TIFF a través de C++" h2="Conversión de POTX a TIFF de alto rendimiento utilizando la biblioteca C++ sin necesidad de instalar Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cómo convertir POTX a TIFF usando C++" %}}

Para convertir POTX a TIFF, usaremos
 [Aspose.Slides para C++](https://products.aspose.com/slides/cpp/)
 API que es una API de manipulación y conversión de documentos rica en funciones, potente y fácil de usar para la plataforma C ++. Puede descargar su última versión directamente, simplemente abra
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 administrador de paquetes, busque
 Aspose.Slides.Cpp
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Código fuente de conversión de POTX a TIFF C++" >}}
```cs
// Load the POTX.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.potx");
// Save in TIFF format.
prs->Save(u"convertedFile.tiff", Aspose::Slides::Export::SaveFormat::Tiff);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Pasos para convertir POTX a TIFF a través de C++" intro="Los desarrolladores de C++ pueden convertir fácilmente un archivo POTX a TIFF con solo unas pocas líneas de código." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo POTX con Aspose.Slides para C++ Presentation Object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame al método Save().{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pase la ruta del archivo de salida con extensión de archivo (TIFF).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}El archivo TIFF se guardará en la ruta especificada.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra el archivo TIFF en un programa compatible.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisitos del sistema" intro="Antes de ejecutar el código de ejemplo de conversión de C++, asegúrese de tener los siguientes requisitos previos." %}}

- Microsoft Windows o un sistema operativo compatible con C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits y Linux de 64 bits.
- Aspose.Slides para C++ DLL a la que se hace referencia en su proyecto.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Aplicación gratuita para convertir POTX a TIFF"
  description="[Pruebe nuestra aplicación gratuita Text To Gif](https://products.aspose.app/slides/text-to-gif/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otras conversiones admitidas" subTitle="También puede convertir POTX a muchos otros formatos de archivo, incluidos algunos de los que se enumeran a continuación." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-bmp/" name="POTX TO BMP" description="Imagen de mapa de bits" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-emf/" name="POTX TO EMF" description="Formato de metarchivo mejorado" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-gif/" name="POTX TO GIF" description="Formato de intercambio gráfico" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-html/" name="POTX TO HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-jpeg/" name="POTX TO JPEG" description="Imagen JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-odp/" name="POTX TO ODP" description="Formato de presentación de OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-otp/" name="POTX TO OTP" description="Formato estándar de OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-pdf/" name="POTX TO PDF" description="Formato de Documento Portable" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-png/" name="POTX TO PNG" description="Gráficos de red portátiles" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-pot/" name="POTX TO POT" description="Archivos de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-potm/" name="POTX TO POTM" description="Archivo de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-pps/" name="POTX TO PPS" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-ppsm/" name="POTX TO PPSM" description="Presentación de diapositivas habilitada para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-ppt/" name="POTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-pptm/" name="POTX TO PPTM" description="Archivo de presentación habilitado para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-pptx/" name="POTX TO PPTX" description="Formato de presentación XML abierto" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-svg/" name="POTX TO SVG" description="gráficas vectoriales escalables" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-xml/" name="POTX TO XML" description="Lenguaje de marcado extensible" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-xps/" name="POTX TO XPS" description="Especificaciones de papel XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
