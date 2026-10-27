---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 3630
title: Eliminar anotaciones de PPT con Java
url: /es/java/annotation/ppt/ 
description: Elimine comentarios y autores de comentarios de presentaciones PPT en Java con Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Eliminar comentarios y autores de comentarios de PPT en Java" h2="Use Aspose.Slides for Java para eliminar comentarios y autores de comentarios de archivos de presentación." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Eliminar comentarios de PPT mediante Java" variant="code" %}}

Aspose.Slides for Java le permite eliminar comentarios y autores de comentarios de presentaciones PPT. Cargue un archivo con la clase `Presentation`, recorra los objetos `ICommentAuthor` de `getCommentAuthors`, borre sus comentarios y guarde la presentación actualizada.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Borrar anotaciones de PPT – Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo eliminar comentarios de PPT mediante Java" intro="Siga estos pasos para eliminar comentarios y autores de comentarios de una presentación PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale Aspose.Slides for Java. Consulte [Instalación](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo PPT con la clase `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Recorra los objetos `ICommentAuthor` de `getCommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Borre los comentarios de cada autor con `getComments().clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vacíe la colección de autores de comentarios y guarde el archivo PPT actualizado.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Creado con Aspose.Slides" title="Eliminar comentarios de PPT en línea" description="La aplicación gratuita Aspose.Slides Annotation está creada con [Aspose.Slides for Java](https://products.aspose.com/slides/es/java/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPT." button="Abrir Aspose.Slides Annotation" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides elimina comentarios antes de escribir código.
- Elimine todos los comentarios de su archivo PPT.
- Descargue el archivo limpio.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con anotaciones" subTitle="Con Java, también puede eliminar anotaciones de otros formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/java/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
