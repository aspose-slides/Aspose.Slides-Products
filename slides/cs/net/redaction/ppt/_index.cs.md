---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Začernění souborů prezentací PPT pomocí .NET
url: /cs/net/redaction/ppt/
description: Zdrojový kód C# pro vyhledání a nahrazení textu v prezentacích PPT.
keywords: Začernění PPT, vyhledání a nahrazení textu v PPT, aktualizace prezentace PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Začernění souborů PPT pomocí C#" h2="Vytvářejte aplikace .NET, které vyhledávají a nahrazují text v prezentacích pomocí serverových API." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Začernění prezentace PPT pomocí C#" variant="code" %}}

S [Aspose.Slides for .NET](/slides/cs/net/) můžete vyhledat a nahradit text v prezentaci PPT. Pomocí `Presentation.ReplaceText` s `TextSearchOptions` řiďte vyhledávání a poté upravenou prezentaci uložte.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Začernění prezentace PPT pomocí C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak začernit prezentaci PPT pomocí C#" intro="Postupujte podle těchto kroků a nahraďte text v prezentaci PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPT pomocí `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pomocí [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) s `TextSearchOptions` nahraďte požadovaný text.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte upravenou prezentaci pomocí `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Vytvořeno pomocí Aspose.Slides" title="Začernění souborů PPT online" description="Bezplatná aplikace Aspose.Slides Redaction je vytvořena pomocí [Aspose.Slides for .NET](https://products.aspose.com/slides/cs/net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPT." button="Otevřít Aspose.Slides Redaction" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides vyhledává a nahrazuje text, ještě než napíšete kód.
- Vyhledejte a nahraďte text v souboru PPT, včetně regulárních výrazů.
- Stáhněte začerněný soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro začernění" subTitle="Pomocí C# můžete začernit také následující formáty." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
