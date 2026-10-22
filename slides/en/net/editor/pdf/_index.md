---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Edit PDF in C#
url: /net/editor/pdf/
keywords: Edit PDF, PDF, C# API, .NET Library
description: Edit PDF in C# using Aspose.Slides for .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Edit PDF in C#" h2="Edit PDF documents in C# using Aspose.Slides for .NET." related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit PDF in C#" variant="code" %}}

Using [Aspose.Slides for .NET](/slides/net/), you can update text imported from a PDF document with a few lines of C# code.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# code for editing PDF" >}}
```cs
using var presentation = new Presentation();
presentation.Slides.RemoveAt(0);
presentation.Slides.AddFromPdf("document.pdf");

var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.pdf", SaveFormat.Pdf);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit PDF Using Aspose.Slides" %}}

[Aspose.Slides for .NET](/slides/net/) can import PDF pages into a presentation, update slide content, and save the result as a PDF document.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Edit PDF" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for .NET](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load PDF content with `AddFromPdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Access the target slide and shape through variables.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Update the text through `TextFrame` and save with `SaveFormat.Pdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Edit other files" subTitle="You can also edit files in other formats" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/editor/ppt/" name="Edit PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
