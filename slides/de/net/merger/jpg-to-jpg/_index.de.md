---
title: JPG-Bilder in C# zusammenführen
url: /de/net/merger/jpg-to-jpg/
keywords: JPG, JPEG mit JPG zusammenführen, JPG verbinden, JPG kombinieren, C#-API, .NET-Bibliothek
description: JPG mit JPG in C# zusammenführen. Verwenden Sie die .NET-Bibliotheks-API, um JPG-Dateien zu kombinieren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="JPG in C# zusammenführen" h2="Leistungsstarke plattformübergreifende .NET-API zum Zusammenführen von JPG-Bildern mit C#-Code auf NET Framework-, .NET Core-, Windows Azure-, Mono- oder Xamarin-Plattformen" >}}

{{% blocks/products/pf/feature-page-section h2="JPG mit Aspose.Slides zu JPG zusammenführen" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/de/net/) ist eine leistungsstarke .NET-Bibliothek zum Zusammenführen und Bearbeiten von Präsentationen, Bildern und anderen Dateien. Wenn Sie JPG zu JPG zusammenführen, kombinieren Sie effektiv zwei Bilder, um ein Bild zu erhalten.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="JPG mit JPG in C# zusammenführen" %}}
Mit [**Aspose.Slides for .NET**](https://products.aspose.com/slides/de/net/) können Sie JPG-Dateien schnell mit nur wenigen Codezeilen zusammenführen

{{% blocks/products/pf/agp/code-block title="C#-Code zum Zusammenführen von JPG mit JPG" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image1.jpg"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 360, 540, image);

    IPPImage image2 = pres.Images.AddImage(File.ReadAllBytes("image2.jpg"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 360, 0, 360, 540, image2);

    pres.Slides[0].GetThumbnail(new Size(960, 720)).Save($"merged-image.jpg", ImageFormat.Jpeg);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="So führen Sie JPG in C# zusammen" >}}


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
Laden Sie die JPG-Dateien, die Sie als Bilderrahmen zusammenführen möchten.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Speichern Sie das resultierende JPG-Bild.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="PDF-Dateien online zusammenführen" sectionDescription="[Wie man PDF in Python zusammenführt](https://products.aspose.com/slides/de/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere Dateien zusammenführen" subTitle="Sie können auch Dateien in anderen Formaten kombinieren, um eine einzige Datei zu erhalten" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}