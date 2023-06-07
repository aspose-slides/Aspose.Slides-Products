---
title:  View POTM in C#
url: /net/viewer/potm/
keywords: View POTM, View Macro-enabled PowerPoint Template, Open POTM, POTM Viewer, POTM, PowerPoint, C# API, .NET Library
description: View POTM in C#. Use .NET library API to open and view Macro-enabled PowerPoint Template
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="View POTM in C#" h2="Powerful cross-platform .NET API for opening and viewing POTM using C# code on NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms" >}}

{{% blocks/products/pf/feature-page-section h2="View POTM using Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/net/) is a powerful .NET library used to open and view, manipulate or edit presentations, import presentations from images or documents, and convert presentations to files in other formats.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="View POTM in C#" %}}
Using [**Aspose.Slides for .NET**](https://products.aspose.com/slides/net/), you can load and view a presentation with a few lines of code.

{{% blocks/products/pf/agp/code-block title="C# code for viewing POTM" offSpacer="true" %}}
```cs
string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// instantiate a Presentation object & load the POTM file
using (var presentation = new Aspose.Slides.Presentation("sample.potm"))
{
    // create HTML export controller
    var controller = new Aspose.Slides.Export.ResponsiveHtmlController();
    // create an instance of HtmlOptions and set HtmlFormatter property
    var htmlOptions = new Aspose.Slides.Export.HtmlOptions 
    { 
        HtmlFormatter = Aspose.Slides.Export.HtmlFormatter.CreateCustomFormatter(controller) 
    };

    // save the presentation in HTML
    presentation.Save(output, Aspose.Slides.Export.SaveFormat.Html, htmlOptions);
}
// load HTML to view the presentation content
System.Diagnostics.Process.Start(output);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to view POTM in C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for .NET**. See [**Installation**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instantiate a Presentation object and load the POTM file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create an instance of the ResponsiveHtmlController for formatting.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create an instance of HtmlOptions and set the HtmlFormatter property.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the POTM presentation as HTML.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Call Process.Start with path to resulting HTML to load POTM content.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}





{{< blocks/products/pf/agp/other-supported-section title="View other files" subTitle="You can also open and view presentations in other formats" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/ppt/" name="View PPT Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/pptx/" name="View PPTX Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/odp/" name="View ODP Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/otp/" name="View OTP Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/pot/" name="View POT Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/potx/" name="View POTX Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/pps/" name="View PPS Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/ppsm/" name="View PPSM Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/ppsx/" name="View PPSX Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/pptm/" name="View PPTM Presentation" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}