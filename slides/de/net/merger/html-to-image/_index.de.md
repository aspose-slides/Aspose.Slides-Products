---
title: HTML mit Bild in C# zusammenführen
url: /de/net/merger/html-to-image/
keywords: HTML mit Bild zusammenführen, HTML mit Bild, HTML verbinden, HTML kombinieren, Bild, C#-API, .NET-Bibliothek
description: HTML mit Bild in C# zusammenführen. Verwenden Sie die .NET-Bibliotheks-API, um HTML mit Bildern zu kombinieren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Bild in C# zusammenführen" h2="Leistungsstarke plattformübergreifende .NET-API zum Zusammenführen von HTML mit Bild mithilfe von C#-Code auf NET Framework-, .NET Core-, Windows Azure-, Mono- oder Xamarin-Plattformen" >}}

{{% blocks/products/pf/feature-page-section h2="Fügen Sie HTML mit Aspose.Slides zu einem Bild zusammen" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/de/net/) ist eine leistungsstarke .NET-Bibliothek zum Zusammenführen und Bearbeiten von Präsentationen, HTML-Dokumenten und anderen Dateien. Wenn Sie HTML mit Bild zusammenführen, kombinieren Sie effektiv die Inhalte in HTML-Dokumenten, um ein einzelnes Bild zu erhalten. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="HTML mit Bild in C# zusammenführen" %}}
Mit [**Aspose.Slides for .NET**](https://products.aspose.com/slides/de/net/) können Sie Bilddateien schnell mit nur wenigen Codezeilen zusammenführen

{{% blocks/products/pf/agp/code-block title="C#-Code zum Zusammenführen von HTML mit Bild" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // removes default empty slide

    pres.Slides.AddFromHtml("page_1.html");
    pres.Slides.AddFromHtml("page_2.html");

    pres.Slides[0].GetThumbnail(new Size(960, 720)).Save("MergedFile.png", ImageFormat.Png);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="So führen Sie HTML mit Bild in C# zusammen" >}}


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
Laden Sie die HTML-Dokumente, die Sie zusammenführen möchten.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Speichern Sie das resultierende Bild.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Andere Dateien zusammenführen" subTitle="Sie können auch Dateien in anderen Formaten kombinieren, um eine einzige Datei zu erhalten" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
    
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}