---
title: Slå samman TIFF till PDF i C#
url: /sv/net/merger/tiff-to-pdf/
keywords: TIFF till PDF, slå samman TIFF till PDF, gå med TIFF till PDF, PDF, TIFF, C# API, .NET Library
description: Slå samman TIFF till PDF i C#. Använd .NET library API för att kombinera TIFF och PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Slå samman TIFF till PDF i C#" h2="Kraftfullt plattformsoberoende .NET API för sammanslagning av TIFF till PDF-filer med C#-kod på NET Framework, .NET Core, Windows Azure, Mono eller Xamarin-plattformar" >}}

{{% blocks/products/pf/feature-page-section h2="Slå samman TIFF till PDF med Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/sv/net/) är ett kraftfullt .NET-bibliotek som används för att skapa, konvertera, slå samman och manipulera presentationer, PDF-filer, bilder, och andra filer. När du slår samman TIFF till PDF, kombinerar du effektivt bilder för att få en enda PDF-fil.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Slå samman TIFF till PDF i C#" %}}
Genom att använda [**Aspose.Slides for .NET**](https://products.aspose.com/slides/sv/net/) kan du snabbt slå samman TIFF till PDF med bara några rader kod

{{% blocks/products/pf/agp/code-block title="C#-kod för att slå samman TIFF till PDF" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage tiff1 = pres.Images.AddImage(File.ReadAllBytes("image1.tiff"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, tiff1);

    IPPImage tiff2 = pres.Images.AddImage(File.ReadAllBytes("image2.tiff"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, tiff2);

    pres.Save("MergedFile.pdf", SaveFormat.Pdf);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Hur man slår samman TIFF till PDF i C#" >}}


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
Ladda TIFF-filerna du vill slå ihop som bildramar.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara den resulterande PDF-filen.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Slå ihop andra filer" subTitle="Du kan också kombinera filer i andra format för att få en enda fil" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}