---
title: Convert HTML to Image in C++
url: /cpp/conversion/html-to-image/
keywords: HTML to Image, Convert HTML to Image, C++ API, C++ Library, HTML, Image
description: Convert HTML to Image in C++. Use C++ library API to convert HTML files to Images
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert HTML to Image in C++" h2="High-speed and cross-platform C++ Library that helps in developing applications with the ability to create, merge, inspect, or convert Microsoft PowerPoint and OpenOffice presentation files without the use of any software like Microsoft or Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convert HTML to Image in C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/cpp/) is a powerful C++ library for creating and manipulating presentation files. Moreover, it provides flexible ways to convert HTML to Image. Using **Aspose.Slides for C++**, any developer or application can convert HTML to Image files with just a few lines of C++ code.

As a modern document processing API, Aspose.Slides for C++ exports HTML files to Image file formats quickly. Aspose PowerPoint library allows you to convert HTML to Images and many other file formats

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert HTML to Image using C++" %}}
To convert the HTML to Image, you will need to create Presentation from HTML file and save it as Image.

{{% blocks/products/pf/agp/code-block title="C++ code for converting HTML into Image" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
auto htmlStream = System::IO::File::OpenRead(u"page.html");
pres->get_Slides()->AddFromHtml(htmlStream);

for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto slide = pres->get_Slides()->idx_get(index);
    auto fileName = String::Format(u"slide_{0}.png", index);
    slide->GetThumbnail()->Save(fileName, ImageFormat::get_Png());
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert HTML to Image using Aspose.Slides for C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert HTML to Image in C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for C++**](https://products.aspose.com/slides/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your C++ project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source HTML files in C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result as Image file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[How to Convert PPT to HTML in Python](https://products.aspose.com/slides/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert HTML To Other Supported Formats" subTitle="You can also convert HTML and save to other file formats. See all supported formats below" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}