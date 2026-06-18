---
title: Convert SVG to PNG in C++
url: /cpp/conversion/svg-to-png/
keywords: SVG to PNG, Convert SVG to PNG, C++ API, C++ Library, SVG, PNG
description: Convert SVG to PNG in C++. Use Aspose.Slides for C++ to place an SVG image on a slide and render it as a PNG file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert SVG to PNG in C++" h2="Convert SVG images to PNG using Aspose.Slides for C++ without Microsoft PowerPoint." >}}

{{% blocks/products/pf/feature-page-section h2="Convert SVG to PNG in C++" %}}

[Aspose.Slides for C++](/slides/cpp/) can add SVG images to slides and render those slides as PNG files. Use this approach when you need to convert an SVG asset to a raster image in a C++ application.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Convert SVG to PNG Using C++" %}}

To convert SVG to PNG, create a `Presentation`, add the SVG image to a slide, render the slide with `GetImage`, and save the rendered image with `ImageFormat::Png`.

{{% blocks/products/pf/agp/code-block title="SVG to PNG C++ Conversion Source Code" offSpacer="true" %}}

```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slide(0);

auto svgContent = File::ReadAllText(u"image.svg");
auto svgImage = MakeObject<SvgImage>(svgContent);
auto presentationImage = presentation->get_Images()->AddImage(svgImage);
slide->get_Shapes()->AddPictureFrame(
    ShapeType::Rectangle,
    0,
    0,
    presentationImage->get_Width(),
    presentationImage->get_Height(),
    presentationImage);

auto image = slide->GetImage(2.0, 2.0);
image->Save(u"image.png", ImageFormat::Png);
image->Dispose();

presentation->Dispose();
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section h2="How to Convert SVG to PNG Using Aspose.Slides for C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert SVG to PNG in C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [Aspose.Slides for C++](/slides/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference to your C++ project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create a `Presentation` instance and add the SVG image to a slide.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Render the slide with `GetImage` and save the image with `ImageFormat::Png`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget appName="conversion" extension="svg-to-png" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert SVG to Other Supported Formats" subTitle="You can also convert SVG images and save them to other file formats." >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}