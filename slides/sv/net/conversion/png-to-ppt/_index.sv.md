---
title: Konvertera PNG till PPT i C#
url: /sv/net/conversion/png-to-ppt/
keywords: Konvertera PNG till PPT, PNG till PPT, PowerPoint, PNG, PPT, C# API, .NET Library
description: Konvertera PNG till PPT i C#. Använd .NET library API för att konvertera PNG-bilder till PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertera PNG till PPT i C#" h2="Kraftfullt plattformsoberoende .NET API för att konvertera PNG till PPT med C#-kod på NET Framework, .NET Core, Windows Azure, Mono eller Xamarin-plattformar" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera PNG till PPT med Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/sv/net/) är ett kraftfullt .NET-bibliotek som används för att skapa, konvertera och manipulera PowerPoint-presentationer, PDF-filer, HTML-dokument, och andra filer. När du konverterar PNG till PPT skapar du i huvudsak en PowerPoint-presentation som innehåller bilder baserade på PNG-bilder.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Konvertera PNG till PPT i C#" %}}
Med hjälp av [**Aspose.Slides for .NET**](https://products.aspose.com/slides/sv/net/) kan du konvertera PNG-bild till PowerPoint-presentation med bara några rader kod:

{{% blocks/products/pf/agp/code-block title="C#-kod för att konvertera PNG till PPT" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.png"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);
    pres.Save("Presentation.ppt", SaveFormat.Ppt);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Hur man konverterar PNG till PPT i C#" >}}


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
Ladda PNG-bilden du vill konvertera till PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara den resulterande filen som en PPT-presentation.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Gratis onlinekonverterare" sectionDescription="[Hur man konverterar PPT till HTML i Python](https://products.aspose.com/slides/sv/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra PowerPoint-konverteringar som stöds" subTitle="Du kan också konvertera filer i andra format till PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}