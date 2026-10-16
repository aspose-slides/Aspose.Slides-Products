---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convierta PPTX a SVG a través de la aplicación C++
weight: 880
url: /es/cpp/conversion/pptx-to-svg/ 
description: Ejemplo de código de conversión de C++ para documentos PPTX a formato SVG. Utilice un código de ejemplo para la conversión por lotes de PPTX a SVG dentro de cualquier aplicación C++.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convierta PPTX a SVG a través de C++" h2="Conversión de PPTX a SVG de alto rendimiento utilizando la biblioteca C++ sin necesidad de instalar Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cómo convertir PPTX a SVG usando C++" %}}

Para convertir PPTX a SVG, usaremos
 [Aspose.Slides para C++](https://products.aspose.com/slides/es/cpp/)
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Código fuente de conversión de PPTX a SVG C++" >}}
```cs
// Load the PPTX.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.pptx");
// Save in SVG format.
for (int32_t index = 0; index < prs->get_Slides()->get_Count(); index++)
{
    auto fileName = String::Format(u"slide-{0}.svg", index);
    auto fileStream = System::MakeObject<FileStream>(fileName, FileMode::Create, FileAccess::Write);

    auto slide = prs->get_Slides()->idx_get(index);
    slide->WriteAsSvg(fileStream);
}

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Pasos para convertir PPTX a SVG a través de C++" intro="Los desarrolladores de C++ pueden convertir fácilmente un archivo PPTX a SVG con solo unas pocas líneas de código." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo PPTX con Aspose.Slides para C++ Presentation Object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame al método Save().{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pase la ruta del archivo de salida con la extensión de archivo (SVG).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}El archivo SVG se guardará en la ruta especificada.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra el archivo SVG en un programa compatible.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisitos del sistema" intro="Antes de ejecutar el código de ejemplo de conversión de C++, asegúrese de tener los siguientes requisitos previos." %}}

- Microsoft Windows o un sistema operativo compatible con C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits y Linux de 64 bits.
- Aspose.Slides para C++ DLL a la que se hace referencia en su proyecto.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension="pptx-to-svg"
  title="Aplicación gratuita para convertir PPTX a SVG"
  description="[Pruebe nuestra aplicación gratuita Text To Gif](https://products.aspose.app/slides/text-to-gif/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otras conversiones admitidas" subTitle="También puede convertir PPTX a muchos otros formatos de archivo, incluidos algunos de los que se enumeran a continuación." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="Imagen de mapa de bits" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-emf/" name="PPTX TO EMF" description="Formato de metarchivo mejorado" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-gif/" name="PPTX TO GIF" description="Formato de intercambio gráfico" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-html/" name="PPTX TO HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" description="Imagen JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-odp/" name="PPTX TO ODP" description="Formato de presentación de OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-otp/" name="PPTX TO OTP" description="Formato estándar de OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="Formato de Documento Portable" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-png/" name="PPTX TO PNG" description="Gráficos de red portátiles" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-pot/" name="PPTX TO POT" description="Archivos de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-potm/" name="PPTX TO POTM" description="Archivo de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Presentación de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-pps/" name="PPTX TO PPS" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Presentación de diapositivas habilitada para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="Archivo de presentación habilitado para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Formato de imagen etiquetada" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-xml/" name="PPTX TO XML" description="Lenguaje de marcado extensible" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/cpp/conversion/pptx-to-xps/" name="PPTX TO XPS" description="Especificaciones de papel XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
