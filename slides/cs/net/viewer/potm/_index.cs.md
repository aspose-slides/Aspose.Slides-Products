---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Zobrazení POTM v C#
keywords: Zobrazit POTM, Otevřít POTM, Prohlížeč POTM, POTM, PowerPoint, C# API, Knihovna .NET
weight: 3310
url: /cs/net/viewer/potm/ 
description: Zobrazujte soubory POTM v C#. Pomocí Aspose.Slides for .NET otevřete soubory prezentací a uložíte je jako HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Zobrazení POTM v C#" h2="C# API pro otevírání souborů POTM a jejich ukládání jako responzivní HTML."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Zobrazení POTM pomocí Aspose.Slides" %}}

K zobrazení souborů POTM použijte [Aspose.Slides for .NET](https://products.aspose.com/slides/cs/net/), výkonné a snadno použitelné API pro C# s bohatou funkčností. Otevřete správce balíčků [NuGet](https://www.nuget.org/packages/aspose.slides.net), vyhledejte **Aspose.Slides** a nainstalujte jej. Můžete také spustit následující příkaz v konzole Správce balíčků.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Příkaz konzole Správce balíčků" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

Pomocí [**Aspose.Slides for .NET**](/slides/cs/net/) můžete načíst soubor POTM a uložit jej jako responzivní HTML pomocí několika řádků kódu.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kód C# pro zobrazení POTM" >}}
```cs
using var presentation = new Presentation("presentation.potm");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak zobrazit POTM v C#" intro="Aspose.Slides umožňuje vývojářům zobrazit soubory POTM pomocí několika řádků kódu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte **Aspose.Slides for .NET**. Viz [**Instalace**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte knihovnu jako referenci do svého projektu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor `POTM` pomocí třídy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vytvořte objekt `ResponsiveHtmlController` pro responzivní výstup HTML.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vytvořte objekt `HtmlOptions` a nastavte vlastnost `HtmlFormatter`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte soubor POTM jako HTML pomocí `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systémové požadavky" intro="Aspose.Slides for .NET podporuje všechny hlavní operační systémy. Ujistěte se, že máte splněny následující předpoklady." %}}

- Microsoft Windows nebo kompatibilní OS s .NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin
- Vývojové prostředí, například Microsoft Visual Studio
- Odkaz na Aspose.Slides for .NET ve vašem projektu

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Vytvořeno pomocí Aspose.Slides" title="Prohlížejte soubory POTM online" description="Bezplatná aplikace Aspose.Slides Viewer je vytvořena pomocí [Aspose.Slides for .NET](https://products.aspose.com/slides/cs/net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory POTM." button="Otevřít Aspose.Slides Viewer" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides vykreslí vaše soubory, ještě než napíšete kód.
- Nahrajte soubor POTM a okamžitě si prohlédněte jeho snímky.
- Funguje na počítači i v mobilu, bez PowerPointu.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POTM" readMoreLink="https://docs.fileformat.com/presentation/potm/" %}}

Soubory s příponou `.POTM` jsou šablony Microsoft PowerPoint s podporou maker, zavedené v PowerPoint 2007. Mohou ukládat opakovaně použitelná nastavení prezentace, jako jsou rozložení, styly, pozadí, barevné palety, písma, výchozí formátování a makra VBA. PowerPoint 2007 a novější umí soubory POTM otevírat a upravovat.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Zobrazení dalších souborů" subTitle="Otevírat a zobrazovat můžete také prezentace v dalších formátech." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/net/viewer/odp/" name="ODP" description="Prezentace OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/net/viewer/otp/" name="OTP" description="Šablona prezentace OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/net/viewer/pot/" name="POT" description="Šablona PowerPoint 97–2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/net/viewer/potx/" name="POTX" description="Šablona PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/net/viewer/pps/" name="PPS" description="Prezentace PowerPoint 97–2003 ke spuštění" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/net/viewer/ppsm/" name="PPSM" description="Prezentace PowerPoint ke spuštění s makry" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/net/viewer/ppsx/" name="PPSX" description="Prezentace PowerPoint ke spuštění" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/net/viewer/ppt/" name="PPT" description="Prezentace PowerPoint 97–2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/net/viewer/pptm/" name="PPTM" description="Prezentace PowerPoint s makry" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/net/viewer/pptx/" name="PPTX" description="Prezentace PowerPoint" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
