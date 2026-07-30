---
title: Convert HTML to JPG in C++
url: /cpp/conversion/html-to-jpg/
keywords: HTML to JPG, Convert HTML to JPG, C++ API, C++ Library, HTML, JPG
description: Convert HTML to JPG in C++. Use the C++ library API to convert HTML files to JPG images.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert HTML to JPG in C++" h2="Convert HTML files to JPG images using Aspose.Slides for C++ without Microsoft PowerPoint." >}}

{{% blocks/products/pf/feature-page-section h2="Convert HTML to JPG in C++" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a presentation processing API that can import HTML content and render slides as JPG images.

Aspose.Slides for C++ can convert HTML content to JPG images and other presentation-related formats.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert HTML to JPG Using C++" %}}
To convert HTML to JPG, create a new Presentation, remove its default slide, import the HTML content with `AddFromHtml`, and save each resulting slide as a JPG image.

{{% blocks/products/pf/agp/code-block title="C++ code for converting HTML into JPG" offSpacer="true" %}}

```cpp
auto presentation = MakeObject<Presentation>();

presentation->get_Slides()->RemoveAt(0);
auto htmlStream = File::OpenRead(u"page.html");
presentation->get_Slides()->AddFromHtml(htmlStream);
htmlStream->Dispose();

auto slideCount = presentation->get_Slides()->get_Count();
for (int index = 0; index < slideCount; index++)
{
    auto slide = presentation->get_Slide(index);
    auto fileName = String::Format(u"slide_{0}.jpg", index);
    auto image = slide->GetImage();
    image->Save(fileName);
    image->Dispose();
}

presentation->Dispose();
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Convert HTML to JPG Using Aspose.Slides for C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert HTML to JPG in C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for C++**](/slides/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your C++ project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source HTML file in C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the result as a JPG file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert HTML to Other Supported Formats" subTitle="You can also convert HTML and save it to other file formats. See all supported formats below." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
