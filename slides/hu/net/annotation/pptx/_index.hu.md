---
title: Távolítsa el a PPTX megjegyzést .NET használatával
weight: 4380
url: /hu/net/annotation/pptx/ 
description: C# forráskód a PPTX formátumú megjegyzések törléséhez .NET Framework, .NET Core, Windows Azure, Mono vagy Xamarin platformokon.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Megjegyzések és megjegyzések szerzőinek eltávolítása a PPTX-ből C#-ban" h2="Készítse el saját .NET-alkalmazásait a dokumentumfájlok megjegyzéseinek és szerzőinek manipulálásához szerveroldali API-k segítségével." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Megjegyzések eltávolítása a PPTX-ből C#-on keresztül" %}}
A megjegyzések PPTX-fájlból való eltávolításához az [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net) API-t használjuk, amely funkciókban gazdag, hatékony és könnyen használható. dokumentummanipulációs API C# platformhoz.
{{% blocks/products/pf/agp/code-block title="Megjegyzések törlése a PPTX-ből - C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("example.pptx"))
{
    // Deletes all comments from the presentation
    foreach (var author in presentation.CommentAuthors)
    {
        author.Comments.Clear();
    }

    // Deletes all authors
    presentation.CommentAuthors.Clear();

    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Hogyan távolítsuk el a megjegyzéseket a PPTX-ről C#-on keresztül" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az **Aspose.Slides for .NET** alkalmazást. Lásd: [**Telepítés**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Töltse be a PPTX-t a Presentation osztály egy példányával
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ismételje meg a betöltött PPTX összes szerzőjét
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Távolítsa el a szerző összes megjegyzését
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
A végén távolítsa el az összes szerzőt
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott megjegyzésformátumok" subTitle="A C# használatával könnyen feljegyezhet más formátumokat, beleértve." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}