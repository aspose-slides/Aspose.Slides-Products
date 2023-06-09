---
title: Convert JPG to PNG in C++
url: /cpp/conversion/jpg-to-png/
keywords: JPG to PNG, Convert JPG to PNG, C++ API, C++ Library, JPG, PNG
description: Convert JPG to PNG in C++. Use C++ library API to convert JPG files to PNGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert JPG to PNG in C++" h2="High-speed and cross-platform C++ Library that helps in developing applications with the ability to create, merge, inspect, or convert Microsoft PowerPoint and OpenOffice presentation files without the use of any software like Microsoft or Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convert JPG to PNG in C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/cpp/) is a powerful C++ library for creating and manipulating presentation files. Moreover, it provides flexible ways to convert JPG to PNG. Using **Aspose.Slides for C++**, any developer or application can convert JPG to PNG files with just a few lines of C++ code.

As a modern document processing API, Aspose.Slides for C++ exports JPG files to PNG file formats quickly. Aspose PowerPoint library allows you to convert JPG to PNGs and many other file formats

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert JPG to PNG using C++" %}}
To convert the JPG to PNG, you will need to create Presentation from JPG file and save it as PNG.

{{% blocks/products/pf/agp/code-block title="C++ code for converting JPG into PNG" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
for (int32_t i = 0; i < pres->get_Slides()->get_Count(); i++)
{
    // Control hidden slides (do not render hidden slides)
    if (pres->get_Slides()->idx_get(i)->get_Hidden())
    {
        continue;
    }
    
    // Convert slide to a Bitmap object
    System::SharedPtr<Bitmap> bmp = pres->get_Slides()->idx_get(i)->GetThumbnail(2.f, 2.f);

    // Create file name for an image
    System::String outputFilePath = Path::Combine(outputDir, System::String(u"Slide_") + i + u".png");
    
    // Save the image in PNG format
    bmp->Save(outputFilePath, ImageFormat::get_Png());
}

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert JPG to PNG using Aspose.Slides for C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert JPG to PNG in C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for C++**](https://products.aspose.com/slides/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your C++ project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source JPG files in C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result as PNG file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[How to Convert PPT to HTML in Python](https://products.aspose.com/slides/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert JPG To Other Supported Formats" subTitle="You can also convert JPG and save to other file formats. See all supported formats below" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}