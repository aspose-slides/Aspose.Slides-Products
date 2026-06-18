---
title: Edit PDF in Java
url: /java/editor/pdf/
keywords: Edit PDF, PDF, Java API, Java Library
description: Edit PDF files in Java. Use Aspose.Slides for Java to modify PDF content and save the edited file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edit PDF in Java" h2="Use Aspose.Slides for Java to edit PDF files in Java applications." >}}

{{% blocks/products/pf/feature-page-section h2="Edit PDF using Aspose.Slides" %}}

[Aspose.Slides for Java](/slides/java/) is a Java API for working with presentation content. You can import a `PDF` file into a `Presentation`, add a text shape, and save the edited content as `PDF`.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Edit PDF in Java" %}}
Using [Aspose.Slides for Java](/slides/java/), you can edit a `PDF` file by adding a text shape and saving the result with `SaveFormat.Pdf`.

{{% blocks/products/pf/agp/code-block title="Java code for editing PDF" offSpacer="true" %}}
```java
Presentation presentation = new Presentation();
try {
    presentation.getSlides().removeAt(0);
    presentation.getSlides().addFromPdf("document.pdf");

    ISlide slide = presentation.getSlides().get_Item(0);
    IAutoShape textBox = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    textBox.getTextFrame().setText("New text");

    presentation.save("document.pdf", SaveFormat.Pdf);
} finally {
    presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to edit PDF in Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create a `Presentation` instance and import the source `PDF` content.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Access the slide you want to edit.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a text shape with `addAutoShape` and `setText`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the edited file with `SaveFormat.Pdf`.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Edit other files" subTitle="You can also edit files in other formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/editor/ppt/" name="Edit PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/editor/html/" name="Edit HTML" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
