---
title: Convert JPG to PPTX in Java
url: /java/conversion/jpg-to-pptx/
keywords: Convert JPG to PPTX, JPG to PPTX, PowerPoint, JPG, PPTX, Java API, Java Library
description: Convert JPG to PPTX in Java. Use Aspose.Slides for Java to add a JPG image to a slide and save it as a PPTX presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert JPG to PPTX in Java" h2="Convert JPG images to PPTX presentations using Aspose.Slides for Java without Microsoft PowerPoint." >}}

{{% blocks/products/pf/feature-page-section h2="Convert JPG to PPTX using Aspose.Slides" %}}

[**Aspose.Slides for Java**](/slides/java/) is a presentation processing API that can add `JPG` images to slides and save the result as a `PPTX` presentation.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Convert JPG to PPTX in Java" %}}
Using [**Aspose.Slides for Java**](/slides/java/), you can convert a `JPG` image to a `PPTX` presentation with just a few lines of code:

{{% blocks/products/pf/agp/code-block title="Java code for converting JPG to PPTX" offSpacer="true" %}}
```java
Presentation presentation = new Presentation();
try {
    ISlide slide = presentation.getSlides().get_Item(0);

    byte[] imageData = Files.readAllBytes(Paths.get("image.jpg"));
    IPPImage presentationImage = presentation.getImages().addImage(imageData);
    slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, presentationImage);

    presentation.save("presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to convert JPG to PPTX in Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Java**. See [**Installation**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create an instance of the `Presentation` class.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load the `JPG` image as an `IPPImage`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the resulting file as a `PPTX` presentation.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported PowerPoint Conversions" subTitle="You can also convert files in other formats to PowerPoint." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
