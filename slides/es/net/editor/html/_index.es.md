---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Editar HTML en C#
url: /es/net/editor/html/
keywords: Editar HTML, HTML, C# API, biblioteca .NET
description: Editar HTML en C#. Use la API de la biblioteca .NET para editar el archivo HTML
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Editar HTML en C#" h2="Potente API .NET multiplataforma para editar HTML usando código C# en plataformas NET Framework, .NET Core, Windows Azure, Mono o Xamarin" related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Editar HTML en C#" variant="code" %}}

Con [**Aspose.Slides for .NET**](https://products.aspose.com/slides/es/net/), puede agregar una nueva línea de texto a un documento HTML con solo unas pocas líneas de código.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Código C# para editar HTML" >}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // removes default empty slide
    pres.Slides.AddFromHtml("page.html");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("page.html", SaveFormat.Html);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Editar HTML usando Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/es/net/) es una potente biblioteca .NET que se utiliza para manipular y editar presentaciones, documentos HTML y otros archivos. Puede editar un documento HTML añadiéndole una nueva línea de texto.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo editar HTML en C#" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale **Aspose.Slides para .NET**. Consulte [**Instalación**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Agregue la biblioteca como referencia en su proyecto.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Crea una instancia de la clase Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el documento HTML que desea editar.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Agrega una nueva línea de texto.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde el archivo HTML modificado.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Creado con Aspose.Slides" title="Edite archivos PPTX en línea" description="La aplicación gratuita Aspose.Slides Editor está creada con [Aspose.Slides for .NET](https://products.aspose.com/slides/es/net/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPTX." button="Abrir Aspose.Slides Editor" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides procesa sus archivos antes de escribir código.
- Cargue sus archivos PPTX y edítelos al instante.
- Guarde y descargue el archivo editado.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Editar otros archivos" subTitle="También puedes editar archivos en otros formatos" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
