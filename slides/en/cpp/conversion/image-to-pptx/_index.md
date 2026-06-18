---
title: Convert Image to PPTX in C++
url: /cpp/conversion/image-to-pptx/
keywords: Image to PPTX, Convert Image to PPTX, C++ API, C++ Library, Image, PPTX
description: Convert image to PPTX in C++. Use the C++ library API to convert image files to PowerPoint presentations.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert Image to PPTX in C++" h2="Convert image files to PPTX presentations using Aspose.Slides for C++ without Microsoft PowerPoint." >}}

{{% blocks/products/pf/feature-page-section h2="Convert Image to PPTX in C++" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a presentation processing API that can import images into slides and save the result as a PPTX presentation.

Aspose.Slides for C++ can convert image content to PPTX presentations and other presentation-related formats.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert Image to PPTX Using C++" %}}
To convert an image to PPTX, create a Presentation from the image file and save it as a PPTX presentation.

{{% blocks/products/pf/agp/code-block title="C++ code for converting Image into PPTX" offSpacer="true" %}}

```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slide(0);

auto imageData = File::ReadAllBytes(u"image.jpg");
auto presentationImage = presentation->get_Images()->AddImage(imageData);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0, 0, 720, 540, presentationImage);

presentation->Save(u"presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Convert Image to PPTX Using Aspose.Slides for C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert Image to PPTX in C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for C++**](/slides/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your C++ project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source image file in C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the result as a PPTX file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert Image to Other Supported Formats" subTitle="You can also convert images and save them to other file formats. See all supported formats below." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
