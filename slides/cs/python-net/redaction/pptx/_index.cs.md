---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Začernění textu v prezentacích PPTX pomocí Pythonu
url: /cs/python-net/redaction/pptx/
description: Vyhledávejte a nahrazujte citlivý text v prezentacích PPTX pomocí Pythonu.
keywords: začernění PPTX, vyhledání a nahrazení textu v PPTX, aktualizace prezentace PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Začernění textu v prezentacích PPTX pomocí Pythonu" h2="Vytvářejte aplikace v Pythonu, které pomocí Aspose.Slides vyhledávají a nahrazují citlivý text v prezentacích." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Začernění textu v prezentaci PPTX pomocí Pythonu" variant="code" %}}

S [Aspose.Slides for Python via .NET](/slides/cs/python-net/) můžete nahradit citlivý text v celé prezentaci PPTX. Pomocí `Presentation.replace_text` s `TextSearchOptions` řiďte vyhledávání a poté upravenou prezentaci uložte.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Začernění textu v prezentaci PPTX – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.pptx") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak začernit text v prezentaci PPTX pomocí Pythonu" intro="Postupujte podle těchto kroků a nahraďte citlivý text v prezentaci PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otevřete soubor PPTX pomocí `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pomocí [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) s `TextSearchOptions` nahraďte požadovaný text.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte upravenou prezentaci pomocí `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Vytvořeno pomocí Aspose.Slides" title="Začernění souborů PPTX online" description="Bezplatná aplikace Aspose.Slides Redaction je vytvořena pomocí [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/cs/python-net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPTX." button="Otevřít Aspose.Slides Redaction" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides vyhledává a nahrazuje text, ještě než napíšete kód.
- Vyhledejte a nahraďte text v souboru PPTX, včetně regulárních výrazů.
- Stáhněte začerněný soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro začernění" subTitle="Pomocí Pythonu můžete začernit text i v dalších podporovaných formátech prezentací." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
