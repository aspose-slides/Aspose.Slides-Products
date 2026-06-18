---
title: Edit HTML in Java
url: /java/editor/html/
keywords: Edit HTML, HTML, Java API, Java Library
description: Edit HTML files in Java. Use Aspose.Slides for Java to modify HTML content and save the edited file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edit HTML in Java" h2="Use Aspose.Slides for Java to edit HTML files in Java applications." >}}

{{% blocks/products/pf/feature-page-section h2="Edit HTML using Aspose.Slides" %}}

[Aspose.Slides for Java](/slides/java/) is a Java API for working with presentation content. You can import an `HTML` file into a `Presentation`, add a text shape, and save the edited content as `HTML`.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Edit HTML in Java" %}}
Using [Aspose.Slides for Java](/slides/java/), you can edit an `HTML` file by adding a text shape and saving the result with `SaveFormat.Html`.

{{% blocks/products/pf/agp/code-block title="Java code for editing HTML" offSpacer="true" %}}
```java
Presentation presentation = new Presentation();
try {
    presentation.getSlides().removeAt(0);
    FileInputStream htmlInputStream = new FileInputStream("page.html");
    try {
        presentation.getSlides().addFromHtml(htmlInputStream);
    } finally {
        htmlInputStream.close();
    }

    ISlide slide = presentation.getSlides().get_Item(0);
    IAutoShape textBox = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    textBox.getTextFrame().setText("New text");

    presentation.save("page.html", SaveFormat.Html);
} finally {
    presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to edit HTML in Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create a `Presentation` instance and import the source `HTML` content.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Access the slide you want to edit.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a text shape with `addAutoShape` and `setText`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the edited `HTML` file with `SaveFormat.Html`.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Edit other files" subTitle="You can also edit files in other formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/editor/ppt/" name="Edit PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/editor/pdf/" name="Edit PDF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
