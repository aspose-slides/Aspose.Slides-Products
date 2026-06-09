---
title: Convert HTML to PPTX in C++
url: /cpp/conversion/html-to-pptx/
keywords: Convert HTML to PPTX, HTML to PPTX, PowerPoint, HTML, PPTX, C++ API, C++ Library
description: Convert HTML to PPTX in C++. Use the C++ library API to convert HTML files to PowerPoint presentations.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert HTML to PPTX in C++" h2="Convert HTML files to PPTX presentations using Aspose.Slides for C++ without Microsoft PowerPoint." >}}

{{% blocks/products/pf/feature-page-section h2="Convert HTML to PPTX Using Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/cpp/) is a presentation processing API that can import HTML content and save it as a PowerPoint presentation.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Convert HTML to PPTX in C++" %}}
Using [**Aspose.Slides for C++**](https://products.aspose.com/slides/cpp/), you can convert an HTML file to a PowerPoint presentation with just a few lines of code:

{{% blocks/products/pf/agp/code-block title="C++ code for converting HTML to PPTX" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->RemoveAt(0);

auto htmlStream = File::OpenRead(u"page.html");
presentation->get_Slides()->AddFromHtml(htmlStream);
htmlStream->Dispose();

presentation->Save(u"presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to Convert HTML to PPTX in C++" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for C++**. See [**Installation**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create an instance of the Presentation class.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load the HTML file you want to convert to PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the resulting file as a PPTX presentation.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported PowerPoint Conversions" subTitle="You can also convert files in other formats to PowerPoint." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
