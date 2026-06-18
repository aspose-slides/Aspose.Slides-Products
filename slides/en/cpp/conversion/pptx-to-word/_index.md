---
title: Convert PPTX to Word in C++
url: /cpp/conversion/pptx-to-word/
keywords: Convert PPTX to Word, PPTX to Word, PPTX to DOCX, PowerPoint to Word, C++ API, C++ Library, CPP
description: Convert PPTX to Word in C++. Use Aspose.Slides for C++ and Aspose.Words for C++ to export PowerPoint slide images to a Word document.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPTX to Word in C++" h2="Export PowerPoint slide content to Word using Aspose.Slides for C++ and Aspose.Words for C++." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PowerPoint to Word Using Aspose.Slides and Aspose.Words" %}}

[Aspose.Slides for C++](/slides/cpp/) can render slides as images, while [Aspose.Words for C++](https://products.aspose.com/words/cpp/) can create and save Word documents. Use both APIs when you need to move PPTX slide content into a DOCX document.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Convert PowerPoint to Word in C++" %}}

Use this C++ code to convert PPTX to Word:

{{% blocks/products/pf/agp/code-block title="PPTX to Word C++ Conversion Source Code" offSpacer="true" %}}

```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto wordDocument = MakeObject<Aspose::Words::Document>();
auto documentBuilder = MakeObject<Aspose::Words::DocumentBuilder>(wordDocument);

auto slideSize = Size(1200, 800);
for (auto&& slide : presentation->get_Slides())
{
    auto slideImage = slide->GetImage(slideSize);
    documentBuilder->InsertImage(slideImage);
    slideImage->Dispose();

    documentBuilder->InsertBreak(Aspose::Words::BreakType::PageBreak);
}

wordDocument->Save(u"presentation.docx");
presentation->Dispose();
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section h2="How to Convert PPTX to Word" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install `Aspose.Slides for C++` and `Aspose.Words for C++`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create a `Presentation` instance from the source PPTX file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create a Word `Document` and `DocumentBuilder`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Render slides with `GetImage`, insert the rendered images with `DocumentBuilder`, and save the result as DOCX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget appName="conversion" extension="pptx-to-word" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert PowerPoint to files in other formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}