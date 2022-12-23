---
title: Redigera PPT i C#
url: /sv/net/editor/ppt/
keywords: Redigera PPT, Redigera PowerPoint, PPT, PowerPoint, C# API, .NET Library
description: Redigera PPT i C#. Använd .NET library API för att redigera PowerPoint-presentation
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Redigera PPT i C#" h2="Kraftfullt plattformsoberoende .NET API för redigering av PPT med C#-kod på NET Framework, .NET Core, Windows Azure, Mono eller Xamarin-plattformar" >}}

{{% blocks/products/pf/feature-page-section h2="Redigera PPT med Aspose.Slides" %}}

[**Aspose.Slides för .NET**](https://products.aspose.com/slides/sv/net/) är ett kraftfullt .NET-bibliotek som används för att manipulera och redigera presentationer. Du kan redigera en PPT-presentation genom att lägga till en ny textrad till den. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Redigera PPT i C#" %}}
Med hjälp av [**Aspose.Slides for .NET**](https://products.aspose.com/slides/sv/net/) kan du lägga till en ny textrad till ett PPT-dokument med bara några rader kod.

{{% blocks/products/pf/agp/code-block title="C#-kod för redigering av PPT" offSpacer="true" %}}
```cs
using (Presentation presentation = new Presentation("pres.ppt"))
{
    AutoShape shape = (AutoShape)presentation.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";
    presentation.Save("pres.ppt", SaveFormat.Ppt);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Hur man redigerar PPT i C#" >}}


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
Ladda PPT-presentationen du vill redigera.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en ny textrad.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara den ändrade PowerPoint-filen.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Redigera andra filer" subTitle="Du kan även redigera filer i andra format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}