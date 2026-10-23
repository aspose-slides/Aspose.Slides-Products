---
lastmod: 2023-01-16
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Upravit HTML v C#
url: /cs/net/editor/html/
keywords: Upravit HTML, HTML, C# API, .NET knihovnu
description: Upravte HTML v C#. K úpravě souboru HTML použijte rozhraní API knihovny .NET
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Upravit HTML v C#" h2="Výkonné rozhraní .NET API pro různé platformy pro úpravy HTML pomocí kódu C# na platformách NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin" related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Upravit HTML v C#" variant="code" %}}

Pomocí [**Aspose.Slides for .NET**](https://products.aspose.com/slides/cs/net/) můžete do dokumentu HTML přidat nový řádek textu pomocí pouhých několika řádků kódu.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# kód pro úpravu HTML" >}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // removes default empty slide
    pres.Slides.AddFromHtml("page.html");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("page.html", SaveFormat.Html);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Upravte HTML pomocí Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/cs/net/) je výkonná knihovna .NET používaná k manipulaci a úpravám prezentací, dokumentů HTML a dalších souborů. Dokument HTML můžete upravit přidáním nového řádku textu.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak upravit HTML v C#" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte **Aspose.Slides for .NET**. Viz [**Instalace**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte knihovnu jako referenci do svého projektu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vytvořte instanci třídy Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte dokument HTML, který chcete upravit.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte nový řádek textu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte změněný soubor HTML.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Vytvořeno pomocí Aspose.Slides" title="Upravujte soubory PPTX online" description="Bezplatná aplikace Aspose.Slides Editor je vytvořena pomocí [Aspose.Slides for .NET](https://products.aspose.com/slides/cs/net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPTX." button="Otevřít Aspose.Slides Editor" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides zpracuje vaše soubory, ještě než napíšete kód.
- Nahrajte soubory PPTX a okamžitě je upravte.
- Uložte a stáhněte upravený soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Upravte další soubory" subTitle="Můžete také upravovat soubory v jiných formátech" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/net/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
