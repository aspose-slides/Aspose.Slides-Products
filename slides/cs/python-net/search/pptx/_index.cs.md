---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Vyhledávání textu v prezentacích PPTX pomocí Pythonu
url: /cs/python-net/search/pptx/
description: Vyhledávejte text v prezentacích PPTX pomocí Pythonu a Aspose.Slides.
keywords: vyhledání textu v PPTX, nalezení slov v PPTX, prohledání prezentace PPTX v Pythonu
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Vyhledávání textu v prezentacích PPTX pomocí Pythonu" h2="Vytvářejte aplikace v Pythonu, které pomocí Aspose.Slides vyhledávají text v prezentacích PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Vyhledávání textu v prezentaci PPTX pomocí Pythonu" variant="code" %}}

S [Aspose.Slides for Python via .NET](/slides/cs/python-net/) můžete pomocí [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) najít na každém snímku textové rámce, které obsahují zadaný řetězec.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Vyhledávání textu v prezentaci PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak vyhledat text v PPTX pomocí Pythonu" intro="Postupujte podle těchto kroků a vyhledejte text v prezentaci PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otevřete soubor PPTX pomocí `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Projděte snímky a pro každý zavolejte [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přečtěte vlastnost `text` každého nalezeného textového rámce.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Vytvořeno pomocí Aspose.Slides" title="Vyhledávání textu v souborech PPTX online" description="Bezplatná aplikace Aspose.Slides Search je vytvořena pomocí [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/cs/python-net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPTX." button="Otevřít Aspose.Slides Search" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides vyhledává text, ještě než napíšete kód.
- Prohledejte soubor PPTX podle prostého textu nebo regulárních výrazů.
- Stáhněte nalezené výsledky jako textový soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro vyhledávání" subTitle="Pomocí Pythonu můžete vyhledávat text i v dalších podporovaných formátech prezentací." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
