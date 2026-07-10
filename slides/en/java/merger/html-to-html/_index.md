---
title: Merge HTML Files in Java
url: /java/merger/html-to-html/
keywords: Merge HTML, HTML to HTML, Join HTML, Combine HTML, Java API, Java Library
description: Merge HTML files in Java. Use Aspose.Slides for Java to combine HTML files and save the merged content as HTML.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge HTML in Java" h2="Use Aspose.Slides for Java to merge HTML files in Java applications." >}}

{{% blocks/products/pf/feature-page-section h2="Merge HTML to HTML using Aspose.Slides" %}}

[Aspose.Slides for Java](/slides/java/) is a Java API for creating, editing, converting, and merging presentation content. You can place `HTML` files into a `Presentation` and save the merged content as an `HTML` file.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge HTML to HTML in Java" %}}
Using [Aspose.Slides for Java](/slides/java/), you can merge HTML files and create an `HTML` result with a few lines of Java code.

{{% blocks/products/pf/agp/code-block title="Java code for merging HTML to HTML" offSpacer="true" %}}
```java
Presentation presentation = new Presentation();
try {
    presentation.getSlides().removeAt(0);

    FileInputStream firstHtmlStream = new FileInputStream("file1.html");
    try {
        presentation.getSlides().addFromHtml(firstHtmlStream);
    } finally {
        firstHtmlStream.close();
    }

    FileInputStream secondHtmlStream = new FileInputStream("file2.html");
    try {
        presentation.getSlides().addFromHtml(secondHtmlStream);
    } finally {
        secondHtmlStream.close();
    }

    presentation.save("merged.html", SaveFormat.Html);
} finally {
    presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to merge HTML files in Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` instance.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the source `HTML` files with `addFromHtml`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the merged content with `SaveFormat.Html`.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="html-to-html" sectionTitle="Merge Files Online" sectionDescription="Merge presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge other files" subTitle="You can also combine files in other formats to get a single file." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/image-to-bmp/" name="IMAGE TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/svg-to-png/" name="SVG TO PNG" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
