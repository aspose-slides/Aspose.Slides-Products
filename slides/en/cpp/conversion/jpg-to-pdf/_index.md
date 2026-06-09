---
title: Convert JPG to PDF in C++
url: /cpp/conversion/jpg-to-pdf/
keywords: JPG to PDF, Convert JPG to PDF, C++ API, C++ Library, JPG, PDF
description: Convert JPG to PDF in C++. Use the C++ library API to convert JPG files to PDF documents.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert JPG to PDF in C++" h2="Convert JPG files to PDF documents using Aspose.Slides for C++ without Microsoft PowerPoint." >}}

{{% blocks/products/pf/feature-page-section h2="Convert JPG to PDF in C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/cpp/) is a presentation processing API that can import JPG files into slides and save the result as a PDF document.

Aspose.Slides for C++ can convert JPG content to PDF documents and other presentation-related formats.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert JPG to PDF Using C++" %}}
To convert JPG to PDF, create a Presentation from the JPG file and save it as a PDF document.

{{% blocks/products/pf/agp/code-block title="C++ code for converting JPG into PDF" offSpacer="true" %}}

```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slide(0);

auto imageData = File::ReadAllBytes(u"image.jpg");
auto presentationImage = presentation->get_Images()->AddImage(imageData);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, presentationImage);

presentation->Save(u"presentation.pdf", SaveFormat::Pdf);
presentation->Dispose();
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Convert JPG to PDF Using Aspose.Slides for C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert JPG to PDF in C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for C++**](https://products.aspose.com/slides/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your C++ project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source JPG file in C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the result as a PDF file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert JPG to Other Supported Formats" subTitle="You can also convert JPG files and save them to other file formats. See all supported formats below." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
