---
title: Convert PNG to PDF in Java
url: /java/conversion/png-to-pdf/
keywords: PNG to PDF, Convert PNG to PDF, Java API, Java Library, PNG, PDF
description: Convert PNG to PDF in Java. Use Java library API to convert PNG files to PDFs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PNG to PDF in Java" h2="High-speed and cross-platform Java Library that helps in developing applications with the ability to create, merge, inspect, or convert Microsoft PowerPoint and OpenOffice presentation files without the use of any software like Microsoft or Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PNG to PDF in Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/java/) is a powerful Java library for creating and manipulating presentation files. Moreover, it provides flexible ways to convert PNG to PDF. Using **Aspose.Slides for Java**, any developer or application can convert PNG to PDF files with just a few lines of Java code.

As a modern document processing API, Aspose.Slides for Java exports PNG files to PDF file formats quickly. Aspose PowerPoint library allows you to convert PNG to PDFs and many other file formats

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PNG to PDF using Java" %}}
To convert the PNG to PDF, you will need to create Presentation from PNG file and save it as PDF.

{{% blocks/products/pf/agp/code-block title="Java code for converting PNG into PDF" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    pres.save("index.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PNG to PDF using Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert PNG to PDF in Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for Java**](https://products.aspose.com/slides/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your Java project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source PNG files in Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result as PDF file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[How to Convert PPT to HTML in Python](https://products.aspose.com/slides/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PNG To Other Supported Formats" subTitle="You can also convert PNG and save to other file formats. See all supported formats below" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/png-to-svg/" name="PNG TO SVG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}