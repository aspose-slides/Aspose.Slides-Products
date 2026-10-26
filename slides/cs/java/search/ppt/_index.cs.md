---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Vyhledávání textu v souborech prezentací PPT pomocí Javy
url: /cs/java/search/ppt/
description: Vyhledávejte text v prezentacích PPT v Javě pomocí Aspose.Slides for Java.
keywords: vyhledání slov v PPT, vyhledání textu v PPT, prohledání textu prezentace PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Vyhledávání textu v PPT pomocí Javy" h2="Vytvářejte aplikace v Javě, které pomocí serverových API vyhledávají text v souborech prezentací." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Vyhledávání textu v prezentaci PPT v Javě" variant="code" %}}

S [Aspose.Slides for Java](/slides/cs/java/) můžete vyhledávat text v prezentacích PPT. Pomocí metody `SlideUtil.getAllTextBoxes` shromážděte textové rámce a poté prozkoumejte objekty `ITextFrame`, `IParagraph` a `IPortion`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Vyhledávání textu v prezentaci PPT pomocí Javy" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak vyhledat text v PPT v Javě" intro="Postupujte podle těchto kroků a vyhledejte text v prezentaci PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPT pomocí třídy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte metodu `SlideUtil.getAllTextBoxes` a shromážděte textové rámce z každého snímku.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Prozkoumejte objekty `ITextFrame`, `IParagraph` a `IPortion` a najděte odpovídající text.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Vytvořeno pomocí Aspose.Slides" title="Vyhledávání textu v souborech PPT online" description="Bezplatná aplikace Aspose.Slides Search je vytvořena pomocí [Aspose.Slides for Java](https://products.aspose.com/slides/cs/java/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPT." button="Otevřít Aspose.Slides Search" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides vyhledává text, ještě než napíšete kód.
- Prohledejte soubor PPT podle prostého textu nebo regulárních výrazů.
- Stáhněte nalezené výsledky jako textový soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro vyhledávání" subTitle="Pomocí Javy můžete vyhledávat text také v následujících formátech." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/java/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
