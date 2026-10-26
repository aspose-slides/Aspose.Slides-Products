---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Vyhledávání textu v souborech prezentací PPTX pomocí Javy
url: /cs/java/search/pptx/
description: Vyhledávejte text v prezentacích PPTX v Javě pomocí Aspose.Slides for Java.
keywords: vyhledání slov v PPTX, vyhledání textu v PPTX, prohledání textu prezentace PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Vyhledávání textu v PPTX pomocí Javy" h2="Vytvářejte aplikace v Javě, které pomocí serverových API vyhledávají text v souborech prezentací." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Vyhledávání textu v prezentaci PPTX v Javě" variant="code" %}}

S [Aspose.Slides for Java](/slides/cs/java/) můžete vyhledávat text v prezentacích PPTX. Pomocí metody `SlideUtil.getAllTextBoxes` shromážděte textové rámce a poté prozkoumejte objekty `ITextFrame`, `IParagraph` a `IPortion`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Vyhledávání textu v prezentaci PPTX pomocí Javy" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.pptx");
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak vyhledat text v PPTX v Javě" intro="Postupujte podle těchto kroků a vyhledejte text v prezentaci PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPTX pomocí třídy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte metodu `SlideUtil.getAllTextBoxes` a shromážděte textové rámce z každého snímku.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Prozkoumejte objekty `ITextFrame`, `IParagraph` a `IPortion` a najděte odpovídající text.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Vytvořeno pomocí Aspose.Slides" title="Vyhledávání textu v souborech PPTX online" description="Bezplatná aplikace Aspose.Slides Search je vytvořena pomocí [Aspose.Slides for Java](https://products.aspose.com/slides/cs/java/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPTX." button="Otevřít Aspose.Slides Search" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides vyhledává text, ještě než napíšete kód.
- Prohledejte soubor PPTX podle prostého textu nebo regulárních výrazů.
- Stáhněte nalezené výsledky jako textový soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro vyhledávání" subTitle="Pomocí Javy můžete vyhledávat text také v následujících formátech." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/java/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
