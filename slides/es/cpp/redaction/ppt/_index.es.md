---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Censurar presentaciones PPT con C++
url: /es/cpp/redaction/ppt/
description: Censure presentaciones PPT en C++. Use Aspose.Slides for C++ para buscar y reemplazar texto confidencial en archivos de presentación.
keywords: censurar PPT, buscar y reemplazar texto en PPT, actualizar presentación PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Censurar un PPT con C++" h2="Use Aspose.Slides for C++ para buscar y reemplazar texto confidencial en archivos de presentación sin Microsoft PowerPoint." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Censurar una presentación PPT mediante C++" variant="code" %}}

Aspose.Slides for C++ le permite censurar presentaciones PPT reemplazando el texto confidencial de las diapositivas. Use `SlideUtil::FindAndReplaceText` con un objeto `Presentation` para buscar en la presentación y reemplazar el texto coincidente antes de guardar el archivo actualizado.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Censurar una presentación PPT con C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo censurar un PPT mediante C++" intro="Siga estos pasos para censurar una presentación PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo PPT con la clase `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use el método [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) para buscar y reemplazar texto confidencial.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde el archivo censurado con `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Creado con Aspose.Slides" title="Censurar archivos PPT en línea" description="La aplicación gratuita Aspose.Slides Redaction está creada con [Aspose.Slides for C++](https://products.aspose.com/slides/es/cpp/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPT." button="Abrir Aspose.Slides Redaction" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides busca y reemplaza texto antes de escribir código.
- Busque y reemplace texto en su archivo PPT, incluso con expresiones regulares.
- Descargue el archivo censurado.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con la censura" subTitle="Con C++, también puede censurar los siguientes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
