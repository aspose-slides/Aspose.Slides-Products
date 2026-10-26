---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Buscar texto en presentaciones PPTX con C++
url: /es/cpp/search/pptx/
description: Busque texto en presentaciones PPTX en C++. Use Aspose.Slides for C++ para encontrar texto en archivos de presentación.
keywords: buscar palabras en PPTX, encontrar texto en PPTX, buscar texto de presentación PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Buscar texto en PPTX con C++" h2="Use Aspose.Slides for C++ para encontrar texto en archivos de presentación sin Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Buscar texto en una presentación PPTX mediante C++" variant="code" %}}

Aspose.Slides for C++ le permite buscar texto en presentaciones PPTX. Use `SlideUtil::GetAllTextBoxes` para reunir los marcos de texto de una diapositiva y, después, compruebe si su texto contiene la frase necesaria.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Buscar texto en una presentación PPTX con C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo buscar texto en PPTX mediante C++" intro="Siga estos pasos para buscar texto en una presentación PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo PPTX con la clase `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Obtenga la diapositiva necesaria con `Presentation::get_Slides` y recupere sus marcos de texto con [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Compruebe si el texto de cada marco contiene la frase necesaria.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Creado con Aspose.Slides" title="Buscar texto en archivos PPTX en línea" description="La aplicación gratuita Aspose.Slides Search está creada con [Aspose.Slides for C++](https://products.aspose.com/slides/es/cpp/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPTX." button="Abrir Aspose.Slides Search" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides encuentra texto antes de escribir código.
- Busque texto sin formato o expresiones regulares en su archivo PPTX.
- Descargue las coincidencias como archivo de texto.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con la búsqueda" subTitle="Con C++, también puede buscar texto en los siguientes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
