---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PNG to SVG in C++
url: /cpp/conversion/png-to-svg/
keywords: PNG to SVG, Convert PNG to SVG, C++ API, C++ Library, PNG, SVG
description: Convert PNG to SVG in C++. Use the C++ library API to add PNG images to slides and save slides as SVG files.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PNG to SVG in C++" h2="Convert PNG images to SVG using Aspose.Slides for C++ without Microsoft PowerPoint." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PNG to SVG in C++" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a presentation processing API that can create slides from images and write slides as SVG files. Using **Aspose.Slides for C++**, developers can convert PNG images to SVG with just a few lines of C++ code.

Aspose.Slides for C++ can place PNG images on slides and export the slides as SVG and other related formats.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PNG to SVG Using C++" %}}
To convert PNG to SVG, create a `Presentation`, add the PNG image to a slide, and write the slide to an SVG file.

{{% blocks/products/pf/agp/code-block title="C++ code for converting PNG into SVG" offSpacer="true" %}}

```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slide(0);
auto slideSize = presentation->get_SlideSize()->get_Size();

auto imageData = File::ReadAllBytes(u"image.png");
auto presentationImage = presentation->get_Images()->AddImage(imageData);
slide->get_Shapes()->AddPictureFrame(
    ShapeType::Rectangle,
    0,
    0,
    slideSize.get_Width(),
    slideSize.get_Height(),
    presentationImage);

auto fileStream = MakeObject<FileStream>(u"document.svg", FileMode::Create, FileAccess::Write);
slide->WriteAsSvg(fileStream);
fileStream->Dispose();

presentation->Dispose();
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PNG to SVG using Aspose.Slides for C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert PNG to SVG in C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for C++**](/slides/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference to your C++ project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` instance and add the PNG image to a slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Write the slide to an SVG file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="png-to-svg" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PNG to Other Supported Formats" subTitle="You can also convert PNG images and save them to other file formats. See all supported formats below." >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
