---
title: Convert JPG to PNG in C++
url: /cpp/conversion/jpg-to-png/
keywords: JPG to PNG, Convert JPG to PNG, C++ API, C++ Library, JPG, PNG
description: Convert JPG to PNG in C++. Use the C++ library API to convert JPG files to PNG images.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert JPG to PNG in C++" h2="Convert JPG files to PNG images using Aspose.Slides for C++ without Microsoft PowerPoint." >}}

{{% blocks/products/pf/feature-page-section h2="Convert JPG to PNG in C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/cpp/) is a presentation processing API that can import JPG files into slides and render the result as PNG images. Using **Aspose.Slides for C++**, developers can convert JPG files to PNG images with just a few lines of C++ code.

Aspose.Slides for C++ can convert JPG content to PNG images and other presentation-related formats.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert JPG to PNG Using C++" %}}
To convert JPG to PNG, create a Presentation from the JPG file and render each slide as a PNG image.

{{% blocks/products/pf/agp/code-block title="C++ code for converting JPG into PNG" offSpacer="true" %}}

```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slide(0);

auto imageData = File::ReadAllBytes(u"image.jpg");
auto presentationImage = presentation->get_Images()->AddImage(imageData);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, presentationImage);

// Render the slide to an image.
auto slideImage = slide->GetImage(2.0f, 2.0f);

// Save the image in PNG format.
slideImage->Save(u"slide.png", ImageFormat::Png);
slideImage->Dispose();

presentation->Dispose();
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert JPG to PNG using Aspose.Slides for C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert JPG to PNG in C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for C++**](https://products.aspose.com/slides/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference to your C++ project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source JPG file in C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the result as a PNG image.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert JPG to Other Supported Formats" subTitle="You can also convert JPG files and save them to other file formats. See all supported formats below." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
