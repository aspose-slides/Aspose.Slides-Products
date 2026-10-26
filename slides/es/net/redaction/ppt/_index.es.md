---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Censurar archivos de presentación PPT con .NET
url: /es/net/redaction/ppt/
description: Código fuente C# para buscar y reemplazar texto en presentaciones PPT.
keywords: Censurar PPT, buscar y reemplazar texto en PPT, actualizar presentación PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Censurar archivos PPT con C#" h2="Cree aplicaciones .NET que busquen y reemplacen texto en presentaciones con API del lado del servidor." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Censurar una presentación PPT con C#" variant="code" %}}

Con [Aspose.Slides for .NET](/slides/es/net/), puede buscar y reemplazar texto en una presentación PPT. Use `Presentation.ReplaceText` con `TextSearchOptions` para controlar la búsqueda y, a continuación, guarde la presentación modificada.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Censurar una presentación PPT con C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo censurar una presentación PPT con C#" intro="Siga estos pasos para reemplazar texto en una presentación PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo PPT con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) con `TextSearchOptions` para reemplazar el texto necesario.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde la presentación modificada con `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Creado con Aspose.Slides" title="Censurar archivos PPT en línea" description="La aplicación gratuita Aspose.Slides Redaction está creada con [Aspose.Slides for .NET](https://products.aspose.com/slides/es/net/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPT." button="Abrir Aspose.Slides Redaction" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides busca y reemplaza texto antes de escribir código.
- Busque y reemplace texto en su archivo PPT, incluso con expresiones regulares.
- Descargue el archivo censurado.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con la censura" subTitle="Con C#, también puede censurar los siguientes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
