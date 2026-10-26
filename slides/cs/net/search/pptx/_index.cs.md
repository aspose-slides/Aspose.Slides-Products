---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Vyhledávání textu v souborech prezentací PPTX pomocí .NET
url: /cs/net/search/pptx/
description: Zdrojový kód C# pro vyhledávání textu v prezentacích PPTX.
keywords: Vyhledání textu v PPTX, nalezení textu v PPTX, prohledání textu prezentace PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Vyhledávání textu v souborech PPTX pomocí C#" h2="Vytvářejte aplikace .NET, které pomocí serverových API vyhledávají text v prezentacích." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Vyhledávání textu v prezentaci PPTX pomocí C#" variant="code" %}}

S [Aspose.Slides for .NET](/slides/cs/net/) můžete vyhledávat text v prezentaci PPTX. Pomocí `SlideUtil.GetAllTextBoxes` získejte textové rámce snímku a poté v jejich hodnotách `Text` vyhledejte požadovanou frázi.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Vyhledávání textu v prezentaci PPTX pomocí C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var slideIndex = 0;
var slide = presentation.Slides[slideIndex];
var textFrames = Aspose.Slides.Util.SlideUtil.GetAllTextBoxes(slide);

foreach (var textFrame in textFrames)
{
    var text = textFrame.Text;
    if (text.Contains("PowerPoint", System.StringComparison.OrdinalIgnoreCase))
    {
        Console.WriteLine(text);
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak vyhledat text v prezentaci PPTX pomocí C#" intro="Postupujte podle těchto kroků a vyhledejte text v prezentaci PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPTX pomocí `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Získejte požadovaný snímek z `Presentation.Slides` a přiřaďte ho do proměnné.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Získejte jeho textové rámce pomocí [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zkontrolujte, zda hodnota `Text` každého rámce obsahuje požadovanou frázi.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Vytvořeno pomocí Aspose.Slides" title="Vyhledávání textu v souborech PPTX online" description="Bezplatná aplikace Aspose.Slides Search je vytvořena pomocí [Aspose.Slides for .NET](https://products.aspose.com/slides/cs/net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPTX." button="Otevřít Aspose.Slides Search" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides vyhledává text, ještě než napíšete kód.
- Prohledejte soubor PPTX podle prostého textu nebo regulárních výrazů.
- Stáhněte nalezené výsledky jako textový soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro vyhledávání" subTitle="Pomocí C# můžete vyhledávat text také v následujících formátech." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/net/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
