---
title: Wasserzeichen zu PPT-Präsentationsdateien mit .NET hinzufügen
url: /de/net/watermark/ppt/
keywords: Wasserzeichen hinzufügen PPT, Textwasserzeichen hinzufügen PPT, Bildwasserzeichen hinzufügen PPT
description: C#-Quellcode zum Hinzufügen eines Wasserzeichens zur PPT-Präsentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Wasserzeichen zur PPT-Präsentation mit C# hinzufügen" h2="Erstellen Sie Ihre eigenen .NET-Apps, um mithilfe serverseitiger APIs Text- oder Bildwasserzeichen in PPT-, PPTX- oder ODP-Präsentationen einzufügen." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Wasserzeichen zur PPT-Präsentation über C# hinzufügen" %}}
Mit Aspose.Slides for .NET können Sie der Präsentation von PPT ein Wasserzeichen hinzufügen. Wasserzeichen sind ein wesentlicher Bestandteil jeder Präsentation. Sie dienen dazu, den Inhalt der Präsentation vor der Vervielfältigung oder unerlaubten Verwendung zu schützen. Ein Wasserzeichen ist ein sichtbares oder unsichtbares Bild oder Text, das über der Präsentation platziert wird. Es kann verwendet werden, um den Eigentümer der Präsentation zu identifizieren und eine unbefugte Nutzung zu verhindern. Wasserzeichen können auch verwendet werden, um der Präsentation eine professionelle Note zu verleihen und sie eleganter aussehen zu lassen. 
{{% blocks/products/pf/agp/code-block title="Textwasserzeichen zu PPT mit C# hinzufügen" offSpacer="true" %}}

```cs

using (var presentation = new Presentation())
{
    ISlide slide = presentation.Slides[0];
    IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");

    presentation.Save("watermark.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Bildwasserzeichen zur PPT-Präsentation mit C# hinzufügen" offSpacer="true" %}}

```cs

using (var presentation = new Presentation())
{
    ISlide slide = presentation.Slides[0];
    IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 0, 0);

    IPPImage image = presentation.Images.AddImage(File.ReadAllBytes("watermark.png"));

    watermarkShape.FillFormat.FillType = FillType.Picture;
    watermarkShape.FillFormat.PictureFillFormat.Picture.Image = image;
    watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

    presentation.Save("watermark2.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So fügen Sie über C# ein Wasserzeichen zu PPT hinzu" >}}

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

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Formate" subTitle="Mit C# können Sie Wasserzeichen auch zu den folgenden Formaten hinzufügen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}