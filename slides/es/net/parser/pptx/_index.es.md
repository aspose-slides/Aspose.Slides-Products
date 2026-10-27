---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1480
title: Extraer texto de archivos PPTX con .NET
url: /es/net/parser/pptx/ 
description: Código fuente C# para extraer texto de archivos PPTX con .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Analizar archivos PPTX con C#" h2="Extraiga texto e inspeccione el formato del texto en archivos PPTX con API de .NET del lado del servidor."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Analizar un archivo PPTX con C#" %}}

Use [Aspose.Slides for .NET](/slides/es/net/) para extraer texto de presentaciones PPTX. Instale el paquete desde [NuGet](https://www.nuget.org/packages/aspose.slides.net) o ejecute el siguiente comando en la Consola del Administrador de paquetes.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Comando" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Analizar archivos PPTX – C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
var textFrames = SlideUtil.GetAllTextFrames(presentation, true);

foreach (var textFrame in textFrames)
{
    foreach (var paragraph in textFrame.Paragraphs)
    {
        foreach (var portion in paragraph.Portions)
        {
            Console.WriteLine(portion.Text);
            Console.WriteLine(portion.PortionFormat.FontHeight);

            var latinFont = portion.PortionFormat.LatinFont;
            if (latinFont is not null)
            {
                Console.WriteLine(latinFont.FontName);
            }
        }
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo analizar archivos PPTX en C#" intro="El análisis básico de documentos con la API [Aspose.Slides for .NET](/slides/es/net/) solo requiere unas pocas líneas de código." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo PPTX con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Obtenga los marcos de texto con `SlideUtil.GetAllTextFrames`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Recorra los marcos de texto, los párrafos y las porciones.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lea las propiedades `Text`, `FontHeight` y `LatinFont.FontName` según sea necesario.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisitos del sistema" intro="Se necesita un entorno de ejecución .NET compatible y una referencia al paquete Aspose.Slides for .NET. Puede usar Visual Studio u otro entorno de desarrollo C# compatible." %}}

- Entorno compatible con .NET Framework, .NET, Mono o Xamarin
- Un entorno de desarrollo C# como Visual Studio
- Aspose.Slides for .NET instalado desde NuGet

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Creado con Aspose.Slides" title="Extraer texto e imágenes en línea" description="La aplicación gratuita Aspose.Slides Parser está creada con [Aspose.Slides for .NET](https://products.aspose.com/slides/es/net/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPTX." button="Abrir Aspose.Slides Parser" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides lee sus archivos antes de escribir código.
- Cargue un archivo PPTX y obtenga su texto e imágenes.
- Descargue todo en un único archivo ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

Los archivos PPTX son presentaciones creadas con Microsoft PowerPoint. A diferencia del formato binario PPT, PPTX usa el formato Office Open XML. Una presentación contiene diapositivas con texto, imágenes, formato, animaciones y otros medios que se muestran como una presentación.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos de análisis compatibles" subTitle="Con C#, también puede analizar los siguientes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/net/parser/odp/" name="ODP" description="Presentación OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/net/parser/ppt/" name="PPT" description="Presentación de PowerPoint 97-2003" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
