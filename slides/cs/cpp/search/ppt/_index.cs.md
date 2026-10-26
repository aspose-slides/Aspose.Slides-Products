---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Vyhledávání textu v prezentacích PPT pomocí C++
url: /cs/cpp/search/ppt/
description: Vyhledávejte text v prezentacích PPT v C++. Pomocí Aspose.Slides for C++ najdete text v souborech prezentací.
keywords: vyhledání slov v PPT, nalezení textu v PPT, prohledání textu prezentace PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Vyhledávání textu v PPT pomocí C++" h2="Pomocí Aspose.Slides for C++ najdete text v souborech prezentací bez Microsoft PowerPoint." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Vyhledávání textu v prezentaci PPT v C++" variant="code" %}}

Aspose.Slides for C++ umožňuje vyhledávat text v prezentacích PPT. Pomocí `SlideUtil::GetAllTextBoxes` shromážděte textové rámce snímku a poté zkontrolujte, zda jejich text obsahuje požadovanou frázi.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Vyhledávání textu v prezentaci PPT pomocí C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak vyhledat text v PPT v C++" intro="Postupujte podle těchto kroků a vyhledejte text v prezentaci PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPT pomocí třídy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Získejte požadovaný snímek pomocí `Presentation::get_Slides` a jeho textové rámce pomocí [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zkontrolujte, zda text každého rámce obsahuje požadovanou frázi.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Vytvořeno pomocí Aspose.Slides" title="Vyhledávání textu v souborech PPT online" description="Bezplatná aplikace Aspose.Slides Search je vytvořena pomocí [Aspose.Slides for C++](https://products.aspose.com/slides/cs/cpp/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPT." button="Otevřít Aspose.Slides Search" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides vyhledává text, ještě než napíšete kód.
- Prohledejte soubor PPT podle prostého textu nebo regulárních výrazů.
- Stáhněte nalezené výsledky jako textový soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro vyhledávání" subTitle="Pomocí C++ můžete vyhledávat text také v následujících formátech." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/cpp/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
