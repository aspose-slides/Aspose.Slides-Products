---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Eliminar anotaciones de PPT con C++
url: /es/cpp/annotation/ppt/ 
description: Código fuente C++ para eliminar anotaciones de presentaciones PPT.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Eliminar comentarios y autores de comentarios de PPT en C++" h2="Cree aplicaciones C++ que manipulen comentarios y autores en archivos de presentación con API del lado del servidor." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Eliminar comentarios de PPT mediante C++" variant="code" %}}

Use [Aspose.Slides for C++](/slides/es/cpp/) para eliminar comentarios y autores de comentarios de presentaciones PPT. El siguiente ejemplo borra los comentarios de cada autor de `get_CommentAuthors` y, después, vacía la colección de autores de comentarios.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Borrar anotaciones de PPT – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"example.ppt");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo eliminar comentarios de PPT mediante C++" intro="Siga estos pasos para eliminar comentarios y autores de comentarios de una presentación PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale Aspose.Slides for C++. Consulte [Instalación](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo PPT con la clase `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Recorra los autores de comentarios de `get_CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Borre los comentarios de cada autor con `get_Comments()->Clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vacíe la colección de autores de comentarios.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde la presentación actualizada con `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Creado con Aspose.Slides" title="Eliminar comentarios de PPT en línea" description="La aplicación gratuita Aspose.Slides Annotation está creada con [Aspose.Slides for C++](https://products.aspose.com/slides/es/cpp/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPT." button="Abrir Aspose.Slides Annotation" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides elimina comentarios antes de escribir código.
- Elimine todos los comentarios de su archivo PPT.
- Descargue el archivo limpio.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con anotaciones" subTitle="Con C++, también puede eliminar anotaciones de otros formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
