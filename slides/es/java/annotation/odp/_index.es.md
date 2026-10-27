---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1790
title: Eliminar anotaciones de ODP con Java
url: /es/java/annotation/odp/ 
description: Elimine comentarios y autores de comentarios de presentaciones ODP en Java con Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Eliminar comentarios y autores de comentarios de ODP en Java" h2="Use Aspose.Slides for Java para eliminar comentarios y autores de comentarios de archivos de presentación." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Eliminar comentarios de ODP mediante Java" variant="code" %}}

Aspose.Slides for Java le permite eliminar comentarios y autores de comentarios de presentaciones ODP. Cargue un archivo con la clase `Presentation`, recorra los objetos `ICommentAuthor` de `getCommentAuthors`, borre sus comentarios y guarde la presentación actualizada.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Borrar anotaciones de ODP – Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo eliminar comentarios de ODP mediante Java" intro="Siga estos pasos para eliminar comentarios y autores de comentarios de una presentación ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale Aspose.Slides for Java. Consulte [Instalación](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo ODP con la clase `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Recorra los objetos `ICommentAuthor` de `getCommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Borre los comentarios de cada autor con `getComments().clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vacíe la colección de autores de comentarios y guarde el archivo ODP actualizado.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Creado con Aspose.Slides" title="Eliminar comentarios de ODP en línea" description="La aplicación gratuita Aspose.Slides Annotation está creada con [Aspose.Slides for Java](https://products.aspose.com/slides/es/java/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos ODP." button="Abrir Aspose.Slides Annotation" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides elimina comentarios antes de escribir código.
- Elimine todos los comentarios de su archivo ODP.
- Descargue el archivo limpio.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con anotaciones" subTitle="Con Java, también puede eliminar anotaciones de otros formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/java/annotation/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/java/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
