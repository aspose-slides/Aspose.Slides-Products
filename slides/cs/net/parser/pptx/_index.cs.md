---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1480
title: Extrakce textu ze souborů PPTX pomocí .NET
url: /cs/net/parser/pptx/ 
description: Zdrojový kód C# pro extrakci textu ze souborů PPTX pomocí .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Parsování souborů PPTX v C#" h2="Extrahujte text a zjišťujte formátování textu v souborech PPTX pomocí serverových API .NET."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Parsování souboru PPTX v C#" %}}

Pomocí [Aspose.Slides for .NET](/slides/cs/net/) extrahujete text z prezentací PPTX. Nainstalujte balíček z [NuGet](https://www.nuget.org/packages/aspose.slides.net) nebo spusťte následující příkaz v konzole Správce balíčků.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Příkaz" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Parsování souborů PPTX – C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak parsovat soubory PPTX v C#" intro="Základní parsování dokumentů pomocí API [Aspose.Slides for .NET](/slides/cs/net/) vyžaduje jen několik řádků kódu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPTX pomocí `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Vytvořeno pomocí Aspose.Slides" title="Extrakce textu a obrázků online" description="Bezplatná aplikace Aspose.Slides Parser je vytvořena pomocí [Aspose.Slides for .NET](https://products.aspose.com/slides/cs/net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPTX." button="Otevřít Aspose.Slides Parser" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides čte vaše soubory, ještě než napíšete kód.
- Nahrajte soubor PPTX a získejte jeho text a obrázky.
- Stáhněte vše jako jeden archiv ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

PPTX files are presentations created with Microsoft PowerPoint. Unlike the binary PPT format, PPTX uses the Office Open XML format. A presentation contains slides with text, images, formatting, animations, and other media that are shown as a slideshow.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro parsování" subTitle="V C# můžete parsovat také následující formáty." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/net/parser/odp/" name="ODP" description="Prezentace OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/net/parser/ppt/" name="PPT" description="Prezentace PowerPoint 97–2003" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
