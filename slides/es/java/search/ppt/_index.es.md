---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Buscar texto en archivos de presentación PPT con Java
url: /es/java/search/ppt/
description: Busque texto en presentaciones PPT en Java con Aspose.Slides for Java.
keywords: buscar palabras en PPT, buscar texto en PPT, buscar texto de presentación PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Buscar texto en PPT con Java" h2="Cree aplicaciones Java que busquen texto en archivos de presentación con API del lado del servidor." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Buscar texto en una presentación PPT mediante Java" variant="code" %}}

Con [Aspose.Slides for Java](/slides/es/java/), puede buscar texto en presentaciones PPT. Use el método `SlideUtil.getAllTextBoxes` para reunir los marcos de texto y, después, revise los objetos `ITextFrame`, `IParagraph` e `IPortion`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Buscar texto en una presentación PPT con Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo buscar texto en PPT mediante Java" intro="Siga estos pasos para buscar texto en una presentación PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo PPT con la clase `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame al método `SlideUtil.getAllTextBoxes` para reunir los marcos de texto de cada diapositiva.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Revise los objetos `ITextFrame`, `IParagraph` e `IPortion` para encontrar el texto coincidente.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Creado con Aspose.Slides" title="Buscar texto en archivos PPT en línea" description="La aplicación gratuita Aspose.Slides Search está creada con [Aspose.Slides for Java](https://products.aspose.com/slides/es/java/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPT." button="Abrir Aspose.Slides Search" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides encuentra texto antes de escribir código.
- Busque texto sin formato o expresiones regulares en su archivo PPT.
- Descargue las coincidencias como archivo de texto.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con la búsqueda" subTitle="Con Java, también puede buscar texto en los siguientes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/java/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
