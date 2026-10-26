---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Vyhledávání textu v prezentacích ODP pomocí C++
url: /cs/cpp/search/odp/
description: Vyhledávejte text v prezentacích ODP v C++. Pomocí Aspose.Slides for C++ najdete text v souborech prezentací.
keywords: vyhledání slov v ODP, nalezení textu v ODP, prohledání textu prezentace ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Vyhledávání textu v ODP pomocí C++" h2="Pomocí Aspose.Slides for C++ najdete text v souborech prezentací bez Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Vyhledávání textu v prezentaci ODP v C++" variant="code" %}}

Aspose.Slides for C++ umožňuje vyhledávat text v prezentacích ODP. Pomocí `SlideUtil::GetAllTextBoxes` shromážděte textové rámce snímku a poté zkontrolujte, zda jejich text obsahuje požadovanou frázi.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Vyhledávání textu v prezentaci ODP pomocí C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak vyhledat text v ODP v C++" intro="Postupujte podle těchto kroků a vyhledejte text v prezentaci ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor ODP pomocí třídy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Získejte požadovaný snímek pomocí `Presentation::get_Slides` a jeho textové rámce pomocí [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zkontrolujte, zda text každého rámce obsahuje požadovanou frázi.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Vytvořeno pomocí Aspose.Slides" title="Vyhledávání textu v souborech ODP online" description="Bezplatná aplikace Aspose.Slides Search je vytvořena pomocí [Aspose.Slides for C++](https://products.aspose.com/slides/cs/cpp/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory ODP." button="Otevřít Aspose.Slides Search" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides vyhledává text, ještě než napíšete kód.
- Prohledejte soubor ODP podle prostého textu nebo regulárních výrazů.
- Stáhněte nalezené výsledky jako textový soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro vyhledávání" subTitle="Pomocí C++ můžete vyhledávat text také v následujících formátech." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/cpp/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/cpp/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
