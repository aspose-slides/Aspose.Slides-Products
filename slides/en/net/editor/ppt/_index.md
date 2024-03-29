---
title:  Edit PPT in C#
url: /net/editor/ppt/
keywords: Edit PPT, Edit PowerPoint, PPT, PowerPoint, C# API, .NET Library
description: Edit PPT in C#. Use .NET library API to edit PowerPoint presentation
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edit PPT in C#" h2="Powerful cross-platform .NET API for editing PPT using C# code on NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms" >}}

{{% blocks/products/pf/feature-page-section h2="Edit PPT using Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/net/) is a powerful .NET library used to manipulate and edit presentations. You can edit a PPT presentation by adding a new line of text to it. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Edit PPT in C#" %}}
Using [**Aspose.Slides for .NET**](https://products.aspose.com/slides/net/), you can add a new line of text to a PPT document with just a few lines of code.

{{% blocks/products/pf/agp/code-block title="C# code for editing PPT" offSpacer="true" %}}
```cs
using (Presentation presentation = new Presentation("pres.ppt"))
{
    AutoShape shape = (AutoShape)presentation.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";
    presentation.Save("pres.ppt", SaveFormat.Ppt);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to edit PPT in C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for .NET**. See [**Installation**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create an instance of the Presentation class.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load the PPT presentation you want to edit.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a new line of text.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the changed PowerPoint file.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Edit other files" subTitle="You can also edit files in other formats" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}