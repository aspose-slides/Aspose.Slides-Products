---
title: View PPTM in C++
url: /cpp/viewer/pptm/
keywords: View PPTM, Open PPTM, PPTM Viewer, PPTM, C++ API, C++ Library, CPP
description: View PPTM presentations in C++. Use Aspose.Slides for C++ to open macro-enabled PowerPoint presentation files and save them as responsive HTML.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="View PPTM in C++" h2="Use Aspose.Slides for C++ to open PPTM files and save them as responsive HTML." >}}

{{% blocks/products/pf/feature-page-section h2="View PPTM using Aspose.Slides" %}}

Aspose.Slides for C++ is a presentation processing library for opening, viewing, editing, and converting presentation files. You can load a PPTM file with the `Presentation` class and save it as HTML for browser-based viewing.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="View PPTM in C++" %}}
Use Aspose.Slides for C++ to load a PPTM file and export it to responsive HTML with `ResponsiveHtmlController`, `HtmlOptions`, `HtmlFormatter`, and `SaveFormat::Html`.

{{% blocks/products/pf/agp/code-block title="C++ code for viewing PPTM" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptm");

auto controller = MakeObject<ResponsiveHtmlController>();
auto htmlOptions = MakeObject<HtmlOptions>();
htmlOptions->set_HtmlFormatter(HtmlFormatter::CreateCustomFormatter(controller));

presentation->Save(u"index.html", SaveFormat::Html, htmlOptions);
presentation->Dispose();
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to view PPTM in C++" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install Aspose.Slides for C++. See [Installation](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load the PPTM file with the `Presentation` class.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create a `ResponsiveHtmlController` object for responsive HTML formatting.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create an `HtmlOptions` object and set the `HtmlFormatter` property.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the PPTM presentation as HTML with `SaveFormat::Html`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the generated HTML file in a browser to view the PPTM content.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}





{{< blocks/products/pf/agp/other-supported-section title="View other files" subTitle="You can also open and view presentations in other formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/ppt/" name="View PPT Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/pptx/" name="View PPTX Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/odp/" name="View ODP Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/otp/" name="View OTP Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/pot/" name="View POT Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/potm/" name="View POTM Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/potx/" name="View POTX Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/pps/" name="View PPS Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/ppsm/" name="View PPSM Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/ppsx/" name="View PPSX Presentation" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
