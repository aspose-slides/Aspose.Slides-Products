---
title: Wasserzeichen zu PPT-Präsentationsdateien mit Java hinzufügen
url: /de/java/watermark/ppt/
keywords: Wasserzeichen hinzufügen PPT, Textwasserzeichen hinzufügen PPT, Bildwasserzeichen hinzufügen PPT
description: Java-Quellcode zum Hinzufügen eines Wasserzeichens zur PPT-Präsentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Wasserzeichen zur PPT-Präsentation mit Java hinzufügen" h2="Erstellen Sie Ihre eigenen Java-Apps, um mithilfe serverseitiger APIs Text- oder Bildwasserzeichen in PPT-, PPTX- oder ODP-Präsentationen einzufügen." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Wasserzeichen zur PPT-Präsentation über Java hinzufügen" %}}
Mit Aspose.Slides for Java können Sie der Präsentation von PPT ein Wasserzeichen hinzufügen. Wasserzeichen sind ein wesentlicher Bestandteil jeder Präsentation. Sie dienen dazu, den Inhalt der Präsentation vor der Vervielfältigung oder unerlaubten Verwendung zu schützen. Ein Wasserzeichen ist ein sichtbares oder unsichtbares Bild oder Text, das über der Präsentation platziert wird. Es kann verwendet werden, um den Eigentümer der Präsentation zu identifizieren und eine unbefugte Nutzung zu verhindern. Wasserzeichen können auch verwendet werden, um der Präsentation eine professionelle Note zu verleihen und sie eleganter aussehen zu lassen. 
{{% blocks/products/pf/agp/code-block title="Textwasserzeichen zu PPT mit Java hinzufügen" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IMasterSlide master = pres.getMasters().get_Item(0);
    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");

    pres.save("watermark.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Bildwasserzeichen zur PPT-Präsentation mit Java hinzufügen" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("watermark.png")));

    IMasterSlide master = pres.getMasters().get_Item(0);

    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 100, 100);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(image);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    pres.save("watermark2.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So fügen Sie über Java ein Wasserzeichen zu PPT hinzu" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Hinzufügen von Textwasserzeichen zu PPT-Dateien." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie PPT mit einer Präsentationsinstanz
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Wählen Sie die Masterpräsentation aus
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie einen Formtyp mit der AddAutoShape-Methode hinzu
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie Wasserzeichentext mit der AddTextFrame-Methode hinzu
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis im Format PPT speichern
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Formate" subTitle="Mit Java können Sie Wasserzeichen auch zu den folgenden Formaten hinzufügen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}