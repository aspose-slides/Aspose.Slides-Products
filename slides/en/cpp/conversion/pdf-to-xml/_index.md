---
title: Convert PDF to XML in C++
url: /cpp/conversion/pdf-to-xml/
keywords: PDF to XML, Convert PDF to XML, C++ API, C++ Library, PDF, XML
description: Convert PDF to XML in C++. Use the C++ library API to import PDF files and save them as XML files.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PDF to XML in C++" h2="Convert PDF files to XML using Aspose.Slides for C++ without Adobe Acrobat or Microsoft PowerPoint." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PDF to XML in C++" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a presentation processing API that can import PDF pages into a presentation and save the result as XML. Using **Aspose.Slides for C++**, developers can convert PDF files to XML with just a few lines of C++ code.

Aspose.Slides for C++ can convert PDF content to XML and other presentation-related formats.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to XML Using C++" %}}
To convert PDF to XML, create a `Presentation`, remove the default slide, import the PDF pages, and save the presentation in XML format.

{{% blocks/products/pf/agp/code-block title="C++ code for converting PDF into XML" offSpacer="true" %}}

```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->RemoveAt(0);
presentation->get_Slides()->AddFromPdf(u"input.pdf");

presentation->Save(u"document.xml", SaveFormat::Xml);
presentation->Dispose();
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PDF to XML using Aspose.Slides for C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert PDF to XML in C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for C++**](/slides/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference to your C++ project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Remove the default slide and import the source PDF file into the `Presentation` object.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the presentation as a XML file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="pdf-to-xml" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF files and save them to other file formats. See all supported formats below." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
