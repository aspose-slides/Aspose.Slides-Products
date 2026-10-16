---
lastmod: 2026-07-30
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPT to Word in C++
url: /cpp/conversion/ppt-to-word/
keywords: Convert PPT to Word, PPT to Word, PPT to DOCX, PowerPoint to Word, C++ API, C++ Library, CPP
description: Convert PPT to Word in C++. Use Aspose.Slides for C++ and Aspose.Words for C++ to render PowerPoint slides as images in a Word document.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPT to Word in C++" h2="Render PowerPoint slides as images in Word using Aspose.Slides for C++ and Aspose.Words for C++." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PowerPoint to Word in C++" variant="code" %}}

Use this C++ code to convert PPT to Word:

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT to Word C++ Conversion Source Code" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PowerPoint to Word Using Aspose.Slides and Aspose.Words" %}}

[Aspose.Slides for C++](/slides/cpp/) can render presentation slides as images, while [Aspose.Words for C++](https://products.aspose.com/words/cpp/) can insert those images into a Word document and save it in DOCX format.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PPT to Word" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install `Aspose.Slides for C++` and `Aspose.Words for C++`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` instance from the source PPT file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a Word `Document` and `DocumentBuilder`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Render slides with `GetImage`, insert the slide images with `DocumentBuilder`, and save the result as DOCX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension="ppt-to-word"
  title="Free Online Converter"
  description="Convert presentations and slides online." >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="You can also convert PowerPoint to files in other formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
