---
title: Convert PPT to Word in Java
url: /java/conversion/ppt-to-word/
keywords: Convert PPT to Word, PPT to Word, PPT to DOC, PowerPoint to Word, Java API, Java Library
description: Convert PPT to Word in Java. Use Aspose.Slides for Java and Aspose.Words for Java to render PowerPoint slides as images in a Word document.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPT to Word in Java" h2="Render PowerPoint slides as images in a Word document using Java code without Microsoft PowerPoint or Office" >}}

{{% blocks/products/pf/feature-page-section h2="Convert PowerPoint to Word using Aspose.Slides and Aspose.Words" %}}

[Aspose.Slides for Java](/slides/java/) and [Aspose.Words for Java](https://products.aspose.com/words/java/) let Java applications read PowerPoint presentations and create Word documents. The example renders each PPT slide as an image and inserts that image into a `Document`.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Convert PowerPoint to Word in Java" %}}
Use this Java code to convert `PPT` to Word:

{{% blocks/products/pf/agp/code-block title="Java code for converting PowerPoint to Word" offSpacer="true" %}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    Document document = new Document();
    DocumentBuilder documentBuilder = new DocumentBuilder(document);

    for (ISlide slide : presentation.getSlides()) {
        IImage slideImage = slide.getImage(1f, 1f);
        try {
            ByteArrayOutputStream imageStream = new ByteArrayOutputStream();
            slideImage.save(imageStream, ImageFormat.Png);
            documentBuilder.insertImage(imageStream.toByteArray());
        } finally {
            slideImage.dispose();
        }

        documentBuilder.insertBreak(BreakType.PAGE_BREAK);
    }

    document.save("output.docx");
} finally {
    presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to convert PPT to Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install `Aspose.Slides for Java` and `Aspose.Words for Java`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the `PPT` presentation with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a Word `Document` and a `DocumentBuilder`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render slide images with `getImage` and insert them with `DocumentBuilder`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the resulting Word document.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="ppt-to-word" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert PowerPoint to files in other formats" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/ppt-to-xps/" name="PPT TO XPS" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
