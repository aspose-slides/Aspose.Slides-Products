---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Začernění souborů prezentací ODP pomocí Javy
url: /cs/java/redaction/odp/
description: Vyhledávejte a nahrazujte text v prezentacích ODP v Javě pomocí Aspose.Slides for Java.
keywords: začernění ODP, vyhledání a nahrazení textu v ODP, aktualizace prezentace ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Začernění ODP pomocí Javy" h2="Vytvářejte aplikace v Javě, které vyhledávají a nahrazují text v souborech prezentací pomocí serverových API." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Začernění prezentace ODP v Javě" variant="code" %}}

S [Aspose.Slides for Java](/slides/cs/java/) můžete vyhledávat a nahrazovat text v prezentacích ODP. Pomocí metody `SlideUtil.findAndReplaceText` prohledejte prezentaci a nahraďte odpovídající text novou hodnotou.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Začernění prezentace ODP pomocí Javy" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak začernit ODP v Javě" intro="Postupujte podle těchto kroků a začerněte prezentaci ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor ODP pomocí třídy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte metodu `SlideUtil.findAndReplaceText` pro vyhledání a nahrazení textu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte aktualizovanou prezentaci pomocí `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Vytvořeno pomocí Aspose.Slides" title="Začernění souborů ODP online" description="Bezplatná aplikace Aspose.Slides Redaction je vytvořena pomocí [Aspose.Slides for Java](https://products.aspose.com/slides/cs/java/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory ODP." button="Otevřít Aspose.Slides Redaction" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides vyhledává a nahrazuje text, ještě než napíšete kód.
- Vyhledejte a nahraďte text v souboru ODP, včetně regulárních výrazů.
- Stáhněte začerněný soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro začernění" subTitle="Pomocí Javy můžete začernit také následující formáty." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/java/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/java/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
