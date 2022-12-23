---
title: Upravit PPT v C#
url: /cs/net/editor/ppt/
keywords: Edit PPT, Edit PowerPoint, PPT, PowerPoint, C# API, .NET Library
description: Upravit PPT v C#. K úpravám PowerPointových prezentací použijte rozhraní API knihovny .NET
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Upravit PPT v C#" h2="Výkonné multiplatformní rozhraní .NET API pro úpravy PPT pomocí kódu C# na platformách NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Upravte PPT pomocí Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/cs/net/) je výkonná knihovna .NET používaná k manipulaci a úpravám prezentací. Prezentaci PPT můžete upravit přidáním nového řádku textu. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Upravit PPT v C#" %}}
Pomocí [**Aspose.Slides for .NET**](https://products.aspose.com/slides/cs/net/) můžete do dokumentu PPT přidat nový řádek textu pomocí pouhých několika řádků kódu.

{{% blocks/products/pf/agp/code-block title="C# kód pro úpravu PPT" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="Jak upravit PPT v C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte **Apose.Slides for .NET**. Viz [**Instalace**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte knihovnu jako referenci do svého projektu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vytvořte instanci třídy Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte PPT prezentaci, kterou chcete upravit.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte nový řádek textu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte změněný soubor PowerPoint.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Upravte další soubory" subTitle="Můžete také upravovat soubory v jiných formátech" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}