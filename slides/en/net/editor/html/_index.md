---
title: Edit HTML in C#
url: /net/editor/html/
keywords: Edit HTML, HTML, C# API, .NET Library
description: Edit HTML in C# using Aspose.Slides for .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edit HTML in C#" h2="Edit HTML documents in C# using Aspose.Slides for .NET." >}}

{{% blocks/products/pf/feature-page-section h2="Edit HTML Using Aspose.Slides" %}}

[Aspose.Slides for .NET](/slides/net/) can load HTML into a presentation, update slide content, and save the result back to HTML.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Edit HTML in C#" %}}
Using [Aspose.Slides for .NET](/slides/net/), you can update text imported from an HTML document with a few lines of C# code.

{{% blocks/products/pf/agp/code-block title="C# code for editing HTML" offSpacer="true" %}}
```cs
using var presentation = new Presentation();
presentation.Slides.RemoveAt(0);
presentation.Slides.AddFromHtml("page.html");

var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("page.html", SaveFormat.Html);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Edit HTML" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` object.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load HTML content with `AddFromHtml`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Access the target slide and shape through variables.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Update the text through `TextFrame` and save with `SaveFormat.Html`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="editor" extension="html" sectionTitle="Free Online HTML Editor" sectionDescription="Edit presentation and HTML files online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Edit other files" subTitle="You can also edit files in other formats" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/editor/ppt/" name="Edit PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/editor/pdf/" name="Edit PDF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
