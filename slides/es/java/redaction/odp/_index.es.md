---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Censurar archivos de presentación ODP con Java
url: /es/java/redaction/odp/
description: Busque y reemplace texto en presentaciones ODP en Java con Aspose.Slides for Java.
keywords: censurar ODP, buscar y reemplazar texto en ODP, actualizar presentación ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Censurar un ODP con Java" h2="Cree aplicaciones Java que busquen y reemplacen texto en archivos de presentación con API del lado del servidor." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Censurar una presentación ODP mediante Java" variant="code" %}}

Con [Aspose.Slides for Java](/slides/es/java/), puede buscar y reemplazar texto en presentaciones ODP. Use el método `SlideUtil.findAndReplaceText` para buscar en la presentación y reemplazar el texto coincidente por un valor nuevo.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Censurar una presentación ODP con Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo censurar un ODP mediante Java" intro="Siga estos pasos para censurar una presentación ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo ODP con la clase `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame al método `SlideUtil.findAndReplaceText` para buscar y reemplazar texto.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde la presentación actualizada con `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Creado con Aspose.Slides" title="Censurar archivos ODP en línea" description="La aplicación gratuita Aspose.Slides Redaction está creada con [Aspose.Slides for Java](https://products.aspose.com/slides/es/java/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos ODP." button="Abrir Aspose.Slides Redaction" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides busca y reemplaza texto antes de escribir código.
- Busque y reemplace texto en su archivo ODP, incluso con expresiones regulares.
- Descargue el archivo censurado.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con la censura" subTitle="Con Java, también puede censurar los siguientes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/java/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/java/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
