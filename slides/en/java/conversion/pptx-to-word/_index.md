---
title: Convert PPTX to Word in Java
url: /java/conversion/pptx-to-word/
keywords: Convert PPTX to Word, PPTX to Word, PPTX to DOC, PowerPoint to Word, Java API, Java Library
description: Convert PPTX to Word in Java. Use Aspose.Slides for Java and Aspose.Words for Java to render PowerPoint slides into a Word document.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPTX to Word in Java" h2="Convert PowerPoint slides to a Word document using Java code without Microsoft PowerPoint or Office" >}}

{{% blocks/products/pf/feature-page-section h2="Convert PowerPoint to Word using Aspose.Slides and Aspose.Words" %}}

[Aspose.Slides for Java](/slides/java/) and [Aspose.Words for Java](https://products.aspose.com/words/java/) let Java applications read PowerPoint presentations and create Word documents. A `PPTX` to Word workflow can render each slide as an image and insert the images into a `Document`.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Convert PowerPoint to Word in Java" %}}
Use this Java code to convert `PPTX` to Word:

{{% blocks/products/pf/agp/code-block title="Java code for converting PowerPoint to Word" offSpacer="true" %}}
```java
Presentation presentation = new Presentation("presentation.pptx");
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




{{< blocks/products/pf/feature-page-section  h2="How to convert PPTX to Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install `Aspose.Slides for Java` and `Aspose.Words for Java`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load the `PPTX` presentation with the `Presentation` class.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create a Word `Document` and a `DocumentBuilder`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Render each slide with `getImage` and insert the image into the Word document.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the resulting Word document.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="pptx-to-word" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert PowerPoint to files in other formats" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-odp/" name="PPTX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-otp/" name="PPTX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-pot/" name="PPTX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-potm/" name="PPTX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-potx/" name="PPTX TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-pps/" name="PPTX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-ppt/" name="PPTX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-pptm/" name="PPTX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-swf/" name="PPTX TO SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-tiff/" name="PPTX TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-video/" name="PPTX TO VIDEO" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pptx-to-xps/" name="PPTX TO XPS" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
