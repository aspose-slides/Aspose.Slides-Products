---
title:  View PPT in Python
url: /python-net/viewer/ppt/
keywords: View PPT, View PowerPoint, Open PPT, PPT Viewer, PPT, PowerPoint, Python API, Python Library
description: View PPT in Python. Use Python library API to open and view PowerPoint presentation
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="View PPT in Python" h2="Powerful cross-platform Python API for opening and viewing PPT using Python code" >}}

{{% blocks/products/pf/feature-page-section h2="View PPT using Aspose.Slides" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/python-net/) is a powerful Python library used to open and view, manipulate or edit presentations, import presentations from images or documents, and convert presentations to files in other formats.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="View PPT in Python" %}}
Using [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/python-net/), you can load and view a presentation with a few lines of code.

{{% blocks/products/pf/agp/code-block title="Python code for viewing PPT" offSpacer="true" %}}
```py
string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// Instantiates a Presentation object & loads the PPT file
using (var presentation = new Aspose.Slides.Presentation("sample.ppt"))
{
    // Creates HTML export controller
    var controller = new Aspose.Slides.Export.ResponsiveHtmlController();
    // Creates an instance of HtmlOptions and sets the HtmlFormatter property
    var htmlOptions = new Aspose.Slides.Export.HtmlOptions 
    { 
        HtmlFormatter = Aspose.Slides.Export.HtmlFormatter.CreateCustomFormatter(controller) 
    };

    // Saves the presentation in HTML
    presentation.Save(output, Aspose.Slides.Export.SaveFormat.Html, htmlOptions);
}
System.Diagnostics.Process.Start(output);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to view PPT in Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instantiate a Presentation object and load the PPT file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create an instance of the ResponsiveHtmlController for formatting.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create an instance of HtmlOptions and set the HtmlFormatter property.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the PPT presentation as HTML.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}





{{< blocks/products/pf/agp/other-supported-section title="View other files" subTitle="You can also open and view presentations in other formats" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/viewer/pptx/" name="View PPTX Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/viewer/odp/" name="View ODP Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/viewer/otp/" name="View OTP Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/viewer/pot/" name="View POT Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/viewer/potm/" name="View POTM Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/viewer/potx/" name="View POTX Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/viewer/pps/" name="View PPS Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/viewer/ppsm/" name="View PPSM Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/viewer/ppsx/" name="View PPSX Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/viewer/pptm/" name="View PPTM Presentation" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}