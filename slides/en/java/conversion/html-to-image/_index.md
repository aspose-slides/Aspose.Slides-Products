---
title: Convert HTML to Image in Java
url: /java/conversion/html-to-image/
keywords: HTML to Image, Convert HTML to Image, Java API, Java Library, HTML, Image
description: Convert HTML to Image in Java. Use Java library API to convert HTML files to Images
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert HTML to Image in Java" h2="Convert HTML files to image files using Aspose.Slides for Java without Microsoft PowerPoint." >}}

{{% blocks/products/pf/feature-page-section h2="Convert HTML to Image in Java" %}}

[**Aspose.Slides for Java**](/slides/java/) is a presentation processing API that can import `HTML` content and render the resulting slides as image files.

You can load an `HTML` file into a `Presentation`, render each `ISlide` as an `IImage`, and save the output in an image format such as `PNG`.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert HTML to Image using Java" %}}
To convert `HTML` to image files, create a `Presentation` from the source file and render its slides.

{{% blocks/products/pf/agp/code-block title="Java code for converting HTML into Image" offSpacer="true" %}}

```java
Presentation presentation = new Presentation();
try {
    presentation.getSlides().removeAt(0);
    try (FileInputStream htmlStream = new FileInputStream("page.html")) {
        presentation.getSlides().addFromHtml(htmlStream);
    }

    for (int slideIndex = 0; slideIndex < presentation.getSlides().size(); slideIndex++) {
        ISlide slide = presentation.getSlides().get_Item(slideIndex);
        IImage slideImage = slide.getImage(1f, 1f);
        try {
            slideImage.save("slide_" + (slideIndex + 1) + ".png", ImageFormat.Png);
        } finally {
            slideImage.dispose();
        }
    }
} finally {
    presentation.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert HTML to Image using Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert HTML to Image in Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for Java**](/slides/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your Java project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source `HTML` file into a `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render each `ISlide` as an `IImage` and save it as an image file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert HTML To Other Supported Formats" subTitle="You can also convert HTML and save it to other file formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
