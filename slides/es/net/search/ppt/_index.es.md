---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Buscar texto en archivos de presentación PPT con .NET
url: /es/net/search/ppt/
description: Código fuente C# para buscar texto en presentaciones PPT.
keywords: Buscar texto en PPT, encontrar texto en PPT, buscar texto de presentación PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Buscar texto en archivos PPT con C#" h2="Cree aplicaciones .NET que encuentren texto en presentaciones con API del lado del servidor." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Buscar texto en una presentación PPT con C#" variant="code" %}}

Con [Aspose.Slides for .NET](/slides/es/net/), puede buscar texto en una presentación PPT. Obtenga los marcos de texto de una diapositiva con `SlideUtil.GetAllTextBoxes` y revise sus valores `Text` en busca de la frase necesaria.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Buscar texto en una presentación PPT con C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var slideIndex = 0;
var slide = presentation.Slides[slideIndex];
var textFrames = Aspose.Slides.Util.SlideUtil.GetAllTextBoxes(slide);

foreach (var textFrame in textFrames)
{
    var text = textFrame.Text;
    if (text.Contains("PowerPoint", System.StringComparison.OrdinalIgnoreCase))
    {
        Console.WriteLine(text);
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo buscar texto en una presentación PPT con C#" intro="Siga estos pasos para buscar texto en una presentación PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo PPT con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Obtenga la diapositiva necesaria de `Presentation.Slides` y asígnela a una variable.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Obtenga sus marcos de texto con [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Compruebe si el valor `Text` de cada marco contiene la frase necesaria.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Creado con Aspose.Slides" title="Buscar texto en archivos PPT en línea" description="La aplicación gratuita Aspose.Slides Search está creada con [Aspose.Slides for .NET](https://products.aspose.com/slides/es/net/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPT." button="Abrir Aspose.Slides Search" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides encuentra texto antes de escribir código.
- Busque texto sin formato o expresiones regulares en su archivo PPT.
- Descargue las coincidencias como archivo de texto.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con la búsqueda" subTitle="Con C#, también puede buscar texto en los siguientes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
