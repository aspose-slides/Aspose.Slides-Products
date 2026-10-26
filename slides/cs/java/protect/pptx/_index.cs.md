---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Ochrana souborů prezentací PPTX pomocí Javy
url: /cs/java/protect/pptx/
description: Chraňte prezentace PPTX v Javě. Pomocí Aspose.Slides for Java šifrujte soubory prezentací a nastavujte ochranu proti zápisu.
keywords: Ochrana proti zápisu PPTX, šifrování souboru PPTX, uzamčení prezentace PPTX, ochrana PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Uzamčení nebo ochrana PPTX heslem pomocí Javy" h2="Vytvářejte aplikace v Javě, které chrání soubory prezentací pomocí serverových API." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ochrana prezentace PPTX pomocí Javy" variant="code" %}}

S [Aspose.Slides for Java](/slides/cs/java/) můžete prezentaci PPTX chránit před otevřením nebo úpravami nastavením hesla. Pomocí objektu `ProtectionManager` třídy `Presentation` volejte metody jako `encrypt` a `setWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Šifrování prezentace PPTX pomocí Javy" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Nastavení ochrany proti zápisu prezentace PPTX pomocí Javy" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak chránit PPTX heslem pomocí Javy" intro="Postupujte podle těchto kroků a ochraňte prezentaci PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPTX pomocí třídy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte metodu `encrypt` nebo metodu `setWriteProtection` objektu `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte chráněný soubor pomocí `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Vytvořeno pomocí Aspose.Slides" title="Ochrana souborů PPTX heslem online" description="Bezplatná aplikace Aspose.Slides Lock je vytvořena pomocí [Aspose.Slides for Java](https://products.aspose.com/slides/cs/java/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPTX." button="Otevřít Aspose.Slides Lock" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides chrání prezentace, ještě než začnete psát kód.
- Nastavte heslo pro otevření nebo úpravy souboru PPTX.
- Stáhněte chráněný soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro ochranu" subTitle="Pomocí Javy můžete chránit také následující formáty." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/java/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
