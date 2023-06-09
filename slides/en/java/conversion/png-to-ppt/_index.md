---
title:  Convert PNG to PPT in Java
url: /java/conversion/png-to-ppt/
keywords: Convert PNG to PPT, PNG to PPT, PowerPoint, PNG, PPT, Java API, Java Library
description: Convert PNG to PPT in Java. Use Java library API to convert PNG images to PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PNG to PPT in Java" h2="Powerful cross-platform Java API for converting PNG to PPT using Java code" >}}

{{% blocks/products/pf/feature-page-section h2="Convert PNG to PPT using Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/java/) is a powerful Java library used to create, convert, and manipulate PowerPoint presentations, PDFs, HTML docs, and other files. When you convert PNG to PPT, you are essentially creating a PowerPoint presentation that contains slides based on PNG images.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Convert PNG to PPT in Java" %}}
Using [**Aspose.Slides for Java**](https://products.aspose.com/slides/java/), you can convert PNG image to PowerPoint presentation with just a few lines of code:

{{% blocks/products/pf/agp/code-block title="Java code for converting PNG to PPT" offSpacer="true" %}}
```java
Presentation pres = new Presentation();
try {
	ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);

	pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
	if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to convert PNG to PPT in Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Java**. See [**Installation**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create an instance of the Presentation class.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load the PNG image you want to convert to PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the resulting file as a PPT presentation.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[How to Convert PPT to HTML in Python](https://products.aspose.com/slides/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported PowerPoint Conversions" subTitle="You can also convert files in other formats to PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}