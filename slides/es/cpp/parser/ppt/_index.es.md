---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 2780
title: Extraer texto de presentaciones PPT con C++
url: /es/cpp/parser/ppt/ 
description: Extraiga texto de presentaciones PPT en C++. Use Aspose.Slides for C++ para analizar diapositivas, marcos de texto, párrafos y porciones.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Analizar presentaciones PPT en C++" h2="Use Aspose.Slides for C++ para extraer texto de las diapositivas sin Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Analizar un archivo PPT con C++" %}}

Use Aspose.Slides for C++ para analizar archivos de presentación PPT y extraer texto de las diapositivas. La API expone el texto de las diapositivas mediante `SlideUtil::GetAllTextBoxes`, `ITextFrame`, `IParagraph` e `IPortion`, por lo que puede leer el contenido de texto sin automatizar Microsoft PowerPoint. Instale el paquete [`Aspose.Slides.Cpp`](https://www.nuget.org/packages/Aspose.Slides.Cpp/) desde NuGet o use el siguiente comando en la Consola del Administrador de paquetes.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Comando" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Analizar archivos PPT – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");
auto textFrames = SlideUtil::GetAllTextBoxes(presentation->get_Slide(0));

for (auto&& textFrame : textFrames)
{
    for (auto&& paragraph : textFrame->get_Paragraphs())
    {
        for (auto&& portion : paragraph->get_Portions())
        {
            Console::WriteLine(portion->get_Text());
        }
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo analizar archivos PPT en C++" intro="Extraiga texto de archivos PPT con Aspose.Slides for C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo PPT con la clase `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Obtenga los objetos `ITextFrame` de la primera diapositiva con `SlideUtil::GetAllTextBoxes`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Recorra los objetos `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Recorra los objetos `IParagraph` de cada `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Recorra los objetos `IPortion` de cada `IParagraph`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lea el texto con `get_Text`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisitos del sistema" intro="Aspose.Slides for C++ es compatible con las principales plataformas de escritorio y servidor. Asegúrese de que su proyecto cumpla los siguientes requisitos previos." %}}

-  Microsoft Windows, Linux, macOS u otro sistema operativo compatible con el entorno de ejecución de C++ admitido.
-  La biblioteca Aspose.Slides for C++ referenciada en su proyecto.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Creado con Aspose.Slides" title="Extraer texto e imágenes en línea" description="La aplicación gratuita Aspose.Slides Parser está creada con [Aspose.Slides for C++](https://products.aspose.com/slides/es/cpp/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPT." button="Abrir Aspose.Slides Parser" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides lee sus archivos antes de escribir código.
- Cargue un archivo PPT y obtenga su texto e imágenes.
- Descargue todo en un único archivo ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

Un archivo PPT es un archivo de presentación de Microsoft PowerPoint 97-2003. Almacena diapositivas, texto, imágenes, multimedia y objetos incrustados en el formato de archivo binario de PowerPoint usado antes del formato Open XML PPTX.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos de análisis compatibles" subTitle="Con C++, también puede analizar otros formatos de presentación." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/parser/odp/" name="ODP" description="Presentación OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/parser/pptx/" name="PPTX" description="Presentación de PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
