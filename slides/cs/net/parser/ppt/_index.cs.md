---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 70
title: Extrakce textu ze souborů PPT pomocí .NET
url: /cs/net/parser/ppt/ 
description: Zdrojový kód C# pro extrakci textu ze souborů PPT pomocí .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Parsování souborů PPT v C#" h2="Extrahujte text a zjišťujte formátování textu v souborech PPT pomocí serverových API .NET."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Parsování souboru PPT v C#" %}}

Pomocí [Aspose.Slides for .NET](/slides/cs/net/) extrahujete text z prezentací PPT. Nainstalujte balíček z [NuGet](https://www.nuget.org/packages/aspose.slides.net) nebo spusťte následující příkaz v konzole Správce balíčků.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Příkaz" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Parsování souborů PPT – C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
var textFrames = SlideUtil.GetAllTextFrames(presentation, true);

foreach (var textFrame in textFrames)
{
    foreach (var paragraph in textFrame.Paragraphs)
    {
        foreach (var portion in paragraph.Portions)
        {
            Console.WriteLine(portion.Text);
            Console.WriteLine(portion.PortionFormat.FontHeight);

            var latinFont = portion.PortionFormat.LatinFont;
            if (latinFont is not null)
            {
                Console.WriteLine(latinFont.FontName);
            }
        }
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak parsovat soubory PPT v C#" intro="Základní parsování dokumentů pomocí API [Aspose.Slides for .NET](/slides/cs/net/) vyžaduje jen několik řádků kódu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPT pomocí `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Získejte textové rámce pomocí `SlideUtil.GetAllTextFrames`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Projděte textové rámce, odstavce a části textu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Podle potřeby čtěte vlastnosti `Text`, `FontHeight` a `LatinFont.FontName`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systémové požadavky" intro="Je potřeba podporovaný běhový modul .NET a odkaz na balíček Aspose.Slides for .NET. Můžete použít Visual Studio nebo jiné kompatibilní vývojové prostředí C#." %}}

- Prostředí kompatibilní s .NET Framework, .NET, Mono nebo Xamarin
- Vývojové prostředí C#, například Visual Studio
- Aspose.Slides for .NET nainstalovaný z NuGet

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Vytvořeno pomocí Aspose.Slides" title="Extrakce textu a obrázků online" description="Bezplatná aplikace Aspose.Slides Parser je vytvořena pomocí [Aspose.Slides for .NET](https://products.aspose.com/slides/cs/net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPT." button="Otevřít Aspose.Slides Parser" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides čte vaše soubory, ještě než napíšete kód.
- Nahrajte soubor PPT a získejte jeho text a obrázky.
- Stáhněte vše jako jeden archiv ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

Soubor PPT je prezentace Microsoft PowerPoint 97-2003 v binárním formátu souborů. Obsahuje snímky s textem, odrážkami, obrázky, multimédii a vloženými objekty OLE. Novější verze PowerPoint používají formát PPTX založený na Office Open XML. Soubory PPT mohou vytvářet i aplikace jako OpenOffice Impress a Apple Keynote.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro parsování" subTitle="V C# můžete parsovat také následující formáty." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/net/parser/odp/" name="ODP" description="Prezentace OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/net/parser/pptx/" name="PPTX" description="Prezentace PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
