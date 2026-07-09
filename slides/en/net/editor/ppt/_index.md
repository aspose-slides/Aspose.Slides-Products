---
title: Edit PPT in C#
url: /net/editor/ppt/
keywords: Edit PPT, Edit PowerPoint, PPT, PowerPoint, C# API, .NET Library
description: Edit PPT in C# using Aspose.Slides for .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edit PPT in C#" h2="Edit PPT presentations in C# using Aspose.Slides for .NET." >}}

{{% blocks/products/pf/feature-page-section h2="Edit PPT Using Aspose.Slides" %}}

[Aspose.Slides for .NET](/slides/net/) can load PPT presentations, update slide content, and save the result as a PPT file.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Edit PPT in C#" %}}
Using [Aspose.Slides for .NET](/slides/net/), you can update text in a PPT presentation with a few lines of C# code.

{{% blocks/products/pf/agp/code-block title="C# code for editing PPT" offSpacer="true" %}}
```cs
using var presentation = new Presentation("document.ppt");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.ppt", SaveFormat.Ppt);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to Edit PPT" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install [Aspose.Slides for .NET](https://docs.aspose.com/slides/net/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the PPT file with a `Presentation` object.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Access the target slide and shape through variables.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Update the text through `TextFrame` and save with `SaveFormat.Ppt`.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Edit other files" subTitle="You can also edit files in other formats" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/editor/pdf/" name="Edit PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/editor/html/" name="Edit HTML" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
