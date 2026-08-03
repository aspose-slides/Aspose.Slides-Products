---
title: Convert PPT to Word in C++
url: /cpp/conversion/ppt-to-word/
keywords: Convert PPT to Word, PPT to Word, PPT to DOCX, PowerPoint to Word, C++ API, C++ Library, CPP
description: Convert PPT to Word in C++. Use Aspose.Slides for C++ and Aspose.Words for C++ to render PowerPoint slides as images in a Word document.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPT to Word in C++" h2="Render PowerPoint slides as images in Word using Aspose.Slides for C++ and Aspose.Words for C++." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PowerPoint to Word Using Aspose.Slides and Aspose.Words" %}}

[Aspose.Slides for C++](/slides/cpp/) can render presentation slides as images, while [Aspose.Words for C++](https://products.aspose.com/words/cpp/) can insert those images into a Word document and save it in DOCX format.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Convert PowerPoint to Word in C++" %}}

Use this C++ code to convert PPT to Word:

{{% blocks/products/pf/agp/code-block title="PPT to Word C++ Conversion Source Code" offSpacer="true" %}}

```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");
auto wordDocument = MakeObject<Aspose::Words::Document>();
auto documentBuilder = MakeObject<Aspose::Words::DocumentBuilder>(wordDocument);

auto slideSize = Size(1200, 800);
for (auto&& slide : presentation->get_Slides())
{
    auto slideImage = slide->GetImage(slideSize);
    auto imageStream = MakeObject<System::IO::MemoryStream>();
    slideImage->Save(imageStream, Aspose::Slides::ImageFormat::Png);
    imageStream->set_Position(0);

    documentBuilder->InsertImage(imageStream);

    imageStream->Dispose();
    slideImage->Dispose();

    documentBuilder->InsertBreak(Aspose::Words::BreakType::PageBreak);
}

wordDocument->Save(u"presentation.docx");
presentation->Dispose();
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section h2="How to Convert PPT to Word" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install `Aspose.Slides for C++` and `Aspose.Words for C++`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` instance from the source PPT file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a Word `Document` and `DocumentBuilder`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render slides with `GetImage`, insert the slide images with `DocumentBuilder`, and save the result as DOCX.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget appName="conversion" extension="ppt-to-word" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert PowerPoint to files in other formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
