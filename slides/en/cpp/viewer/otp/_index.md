---
title: View OTP in C++
url: /cpp/viewer/otp/
keywords: View OTP, Open OTP, OTP Viewer, OTP, C++ API, C++ Library, CPP
description: View OTP presentations in C++. Use Aspose.Slides for C++ to open OpenDocument presentation template files and save them as responsive HTML.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="View OTP in C++" h2="Use Aspose.Slides for C++ to open OTP files and save them as responsive HTML." >}}

{{% blocks/products/pf/feature-page-section h2="View OTP using Aspose.Slides" %}}

Aspose.Slides for C++ is a presentation processing library for opening, viewing, editing, and converting presentation files. You can load an OTP file with the `Presentation` class and save it as HTML for browser-based viewing.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="View OTP in C++" %}}
Use Aspose.Slides for C++ to load an OTP file and export it to responsive HTML with `ResponsiveHtmlController`, `HtmlOptions`, `HtmlFormatter`, and `SaveFormat::Html`.

{{% blocks/products/pf/agp/code-block title="C++ code for viewing OTP" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.otp");

auto controller = MakeObject<ResponsiveHtmlController>();
auto htmlOptions = MakeObject<HtmlOptions>();
htmlOptions->set_HtmlFormatter(HtmlFormatter::CreateCustomFormatter(controller));

presentation->Save(u"index.html", SaveFormat::Html, htmlOptions);
presentation->Dispose();
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to view OTP in C++" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install Aspose.Slides for C++. See [Installation](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the OTP file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `ResponsiveHtmlController` object for responsive HTML formatting.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create an `HtmlOptions` object and set the `HtmlFormatter` property.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the OTP presentation as HTML with `SaveFormat::Html`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the generated HTML file in a browser to view the OTP content.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}





{{< blocks/products/pf/agp/other-supported-section title="View other files" subTitle="You can also open and view presentations in other formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/ppt/" name="View PPT Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/pptx/" name="View PPTX Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/odp/" name="View ODP Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/pot/" name="View POT Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/potm/" name="View POTM Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/potx/" name="View POTX Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/pps/" name="View PPS Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/ppsm/" name="View PPSM Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/ppsx/" name="View PPSX Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/viewer/pptm/" name="View PPTM Presentation" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
