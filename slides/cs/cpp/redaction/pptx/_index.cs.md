---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Začernění prezentací PPTX pomocí C++
url: /cs/cpp/redaction/pptx/
description: Začerňujte prezentace PPTX v C++. Pomocí Aspose.Slides for C++ vyhledávejte a nahrazujte citlivý text v souborech prezentací.
keywords: začernění PPTX, vyhledání a nahrazení textu v PPTX, aktualizace prezentace PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Začernění PPTX pomocí C++" h2="Pomocí Aspose.Slides for C++ vyhledávejte a nahrazujte citlivý text v souborech prezentací bez Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Začernění prezentace PPTX v C++" variant="code" %}}

Aspose.Slides for C++ umožňuje začernit prezentace PPTX nahrazením citlivého textu na snímcích. Pomocí `SlideUtil::FindAndReplaceText` s objektem `Presentation` prohledejte prezentaci a nahraďte odpovídající text ještě před uložením aktualizovaného souboru.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Začernění prezentace PPTX pomocí C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak začernit PPTX v C++" intro="Postupujte podle těchto kroků a začerněte prezentaci PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPTX pomocí třídy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pomocí metody [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) vyhledejte a nahraďte citlivý text.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte začerněný soubor pomocí `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Vytvořeno pomocí Aspose.Slides" title="Začernění souborů PPTX online" description="Bezplatná aplikace Aspose.Slides Redaction je vytvořena pomocí [Aspose.Slides for C++](https://products.aspose.com/slides/cs/cpp/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPTX." button="Otevřít Aspose.Slides Redaction" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides vyhledává a nahrazuje text, ještě než napíšete kód.
- Vyhledejte a nahraďte text v souboru PPTX, včetně regulárních výrazů.
- Stáhněte začerněný soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro začernění" subTitle="Pomocí C++ můžete začernit také následující formáty." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/cpp/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
