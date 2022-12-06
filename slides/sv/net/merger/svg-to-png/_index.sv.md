---
title: Slå samman SVG till PNG i C#
url: /sv/net/merger/svg-to-png/
keywords: Slå samman SVG till PNG, SVG till PNG, anslut SVG till PNG, Kombinera SVG till PNG, C# API, .NET Library
description: Slå samman SVG till PNG i C#. Använd .NET library API för att kombinera SVG- och PNG-filer
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Slå samman SVG till PNG i C#" h2="Kraftfullt plattformsoberoende .NET API för sammanslagning av SVG- till PNG-bilder med C#-kod på NET Framework, .NET Core, Windows Azure, Mono eller Xamarin Platforms" >}}

{{% blocks/products/pf/feature-page-section h2="Slå ihop SVG till PNG med Aspose.Slides" %}}

[**Aspose.Slides för .NET**](https://products.aspose.com/slides/sv/net/) är ett kraftfullt .NET-bibliotek som används för att slå samman och manipulera presentationer, bilder och andra filer. När du slår ihop SVG till PNG, kombinerar du effektivt SVG-bilder för att få en PNG-bild.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Slå samman SVG till PNG i C#" %}}
Genom att använda [**Aspose.Slides for .NET**](https://products.aspose.com/slides/sv/net/) kan du snabbt slå ihop SVG- till PNG-filer med bara några rader kod

{{% blocks/products/pf/agp/code-block title="C#-kod för att slå samman SVG till PNG" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    ISvgImage svgImage = new SvgImage("doc.svg");
    IPPImage image = pres.Images.AddImage(svgImage);
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 360, 540, image);

    ISvgImage svgImage2 = new SvgImage("doc.svg");
    IPPImage image2 = pres.Images.AddImage(svgImage);
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 360, 0, 360, 540, image2);

    pres.Slides[0].GetThumbnail(new Size(960, 720)).Save("MergedFile.png", ImageFormat.Png);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Hur man slår ihop SVG till PNG i C#" >}}


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
Ladda SVG-filerna du vill slå ihop.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara den resulterande PNG-bilden.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Slå ihop andra filer" subTitle="Du kan också kombinera filer i andra format för att få en enda fil" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}