---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Začernění souborů prezentací PPTX pomocí .NET
url: /cs/net/redaction/pptx/
description: Zdrojový kód C# pro vyhledání a nahrazení textu v prezentacích PPTX.
keywords: Začernění PPTX, vyhledání a nahrazení textu v PPTX, aktualizace prezentace PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Začernění souborů PPTX pomocí C#" h2="Vytvářejte aplikace .NET, které vyhledávají a nahrazují text v prezentacích pomocí serverových API." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Začernění prezentace PPTX pomocí C#" variant="code" %}}

S [Aspose.Slides for .NET](/slides/cs/net/) můžete vyhledat a nahradit text v prezentaci PPTX. Pomocí `Presentation.ReplaceText` s `TextSearchOptions` řiďte vyhledávání a poté upravenou prezentaci uložte.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Začernění prezentace PPTX pomocí C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak začernit prezentaci PPTX pomocí C#" intro="Postupujte podle těchto kroků a nahraďte text v prezentaci PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPTX pomocí `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pomocí [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) s `TextSearchOptions` nahraďte požadovaný text.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte upravenou prezentaci pomocí `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Vytvořeno pomocí Aspose.Slides" title="Začernění souborů PPTX online" description="Bezplatná aplikace Aspose.Slides Redaction je vytvořena pomocí [Aspose.Slides for .NET](https://products.aspose.com/slides/cs/net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPTX." button="Otevřít Aspose.Slides Redaction" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides vyhledává a nahrazuje text, ještě než napíšete kód.
- Vyhledejte a nahraďte text v souboru PPTX, včetně regulárních výrazů.
- Stáhněte začerněný soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro začernění" subTitle="Pomocí C# můžete začernit také následující formáty." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/net/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
