---
title: Bild in C# in PPT konvertieren
url: /de/net/conversion/image-to-ppt/
keywords: Konvertieren Sie Bild in PPT, Bild in PPT, PowerPoint, Bild, PPT, C#-API, .NET-Bibliothek
description: Konvertieren Sie das Bild in C# in PPT. Verwenden Sie die .NET-Bibliotheks-API, um Bilder in PowerPoint zu konvertieren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Bild in C# in PPT konvertieren" h2="Leistungsstarke plattformübergreifende .NET-API zum Konvertieren von Bildern in PPT mithilfe von C#-Code auf NET Framework-, .NET Core-, Windows Azure-, Mono- oder Xamarin-Plattformen" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Bilder mit Aspose.Slides in PPT" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/de/net/) ist eine leistungsstarke .NET-Bibliothek zum Erstellen, Konvertieren und Bearbeiten von PowerPoint-Präsentationen, PDFs, HTML-Dokumenten, und andere Dateien. Wenn Sie Bilder in PPT konvertieren, erstellen Sie im Wesentlichen eine PowerPoint-Präsentation, die Folien enthält, die auf diesen Bildern basieren.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Bild in C# in PPT konvertieren" %}}
Mit [**Aspose.Slides for .NET**](https://products.aspose.com/slides/de/net/) können Sie Bilder mit nur wenigen Codezeilen in eine PowerPoint-Präsentation konvertieren:

{{% blocks/products/pf/agp/code-block title="C#-Code zum Konvertieren von Bildern in PPT" offSpacer="true" %}}
```cs

using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.jpg"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);
    pres.Save("Presentation.ppt", SaveFormat.Ppt);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="So konvertieren Sie Bilder in PPT in C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie **Aspose.Slides für .NET**. Siehe [**Installation**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie die Bibliothek als Referenz in Ihrem Projekt hinzu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Erstellen Sie eine Instanz der Presentation-Klasse.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie das Bild, das Sie in PPT konvertieren möchten.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Speichern Sie die resultierende Datei als PPT-Präsentation.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte PowerPoint-Konvertierungen" subTitle="Sie können auch Dateien in anderen Formaten in PowerPoint konvertieren" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}