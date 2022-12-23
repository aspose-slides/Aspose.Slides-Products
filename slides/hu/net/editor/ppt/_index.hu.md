---
title: PPT szerkesztése C#-ban
url: /hu/net/editor/ppt/
keywords: PPT szerkesztése, PowerPoint szerkesztése, PPT, PowerPoint, C# API, .NET Library
description: Szerkessze a PPT-t C#-ban. Használja a .NET könyvtár API-t a PowerPoint bemutató szerkesztéséhez
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PPT szerkesztése C#-ban" h2="Hatékony, többplatformos .NET API a PPT szerkesztéséhez C# kóddal NET Framework, .NET Core, Windows Azure, Mono vagy Xamarin platformokon" >}}

{{% blocks/products/pf/feature-page-section h2="Szerkessze a PPT-t az Aspose.Slides segítségével" %}}

Az [**Aspose.Slides for .NET**](https://products.aspose.com/slides/hu/net/) egy hatékony .NET-könyvtár, amelyet prezentációk kezelésére és szerkesztésére használnak. A PPT prezentációt úgy szerkesztheti, hogy új szövegsort ad hozzá. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="PPT szerkesztése C#-ban" %}}
Az [**Aspose.Slides for .NET**](https://products.aspose.com/slides/hu/net/) használatával mindössze néhány sornyi kóddal új szövegsort adhat hozzá egy PPT-dokumentumhoz.

{{% blocks/products/pf/agp/code-block title="C# kód a PPT szerkesztéséhez" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="Hogyan lehet szerkeszteni a PPT-t C#-ban" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az **Aspose.Slides for .NET** alkalmazást. Lásd: [**Telepítés**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adja hozzá a könyvtárat referenciaként a projekthez.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hozzon létre egy példányt a Prezentáció osztályból.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Töltse be a szerkeszteni kívánt PPT-prezentációt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá egy új szövegsort.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mentse el a módosított PowerPoint fájlt.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Más fájlok szerkesztése" subTitle="Más formátumú fájlokat is szerkeszthet" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}