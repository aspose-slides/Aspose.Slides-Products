---
title: Slå samman bild till PDF i C#
url: /sv/net/merger/image-to-pdf/
keywords: Bild till PDF, Slå ihop bild till PDF, anslut bild till PDF, PDF, Bild, C# API, .NET Library
description: Slå samman bild till PDF i C#. Använd .NET library API för att kombinera bild och PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Slå samman bild till PDF i C#" h2="Kraftfullt plattformsoberoende .NET API för att slå samman bild till PDF-filer med C#-kod på NET Framework, .NET Core, Windows Azure, Mono eller Xamarin-plattformar" >}}

{{% blocks/products/pf/feature-page-section h2="Slå samman bild till PDF med Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/sv/net/) är ett kraftfullt .NET-bibliotek som används för att skapa, konvertera, slå samman och manipulera presentationer, PDF-filer, bilder, och andra filer. När du slår ihop bild till PDF, kombinerar du effektivt bilder för att få en enda PDF-fil.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Slå samman bild till PDF i C#" %}}
Med hjälp av [**Aspose.Slides for .NET**](https://products.aspose.com/slides/sv/net/) kan du snabbt slå samman bild till PDF med bara några rader kod

{{% blocks/products/pf/agp/code-block title="C#-kod för att slå samman bild till PDF" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image1.png"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, image);

    IPPImage image2 = pres.Images.AddImage(File.ReadAllBytes("image2.png"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, image2);

    pres.Save("MergedFile.pdf", SaveFormat.Pdf);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Hur man slår ihop bild till PDF i C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installera **Aspose.Slides för .NET**. Se [**Installation**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till biblioteket som referens i ditt projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Skapa en instans av klassen Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda bilderna du vill slå ihop som bildramar.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara den resulterande PDF-filen.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Slå samman PDF-filer online" sectionDescription="[Hur man sammanfogar PDF i Python](https://products.aspose.com/slides/sv/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Slå ihop andra filer" subTitle="Du kan också kombinera filer i andra format för att få en enda fil" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/jpg-to-jpg/" name="JPG to JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}