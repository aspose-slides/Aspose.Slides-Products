---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Odemčení souborů prezentací ODP pomocí Javy
url: /cs/java/unlock/odp/
description: Odeberte hesla a ochranu proti zápisu z prezentací ODP v Javě pomocí Aspose.Slides for Java.
keywords: Odebrání ochrany proti zápisu ODP, dešifrování ODP, odemčení prezentace ODP, zrušení ochrany ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Odemčení ODP pomocí Javy" h2="Vytvářejte aplikace v Javě, které pomocí serverových API odebírají ze souborů prezentací hesla a ochranu proti zápisu." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Odebrání ochrany z prezentace ODP pomocí Javy" variant="code" %}}

S [Aspose.Slides for Java](/slides/cs/java/) můžete z prezentace ODP odebrat šifrování nebo ochranu proti zápisu. Pomocí `LoadOptions.setPassword` otevřete šifrovanou prezentaci a metodami `removeEncryption` a `removeWriteProtection` objektu `ProtectionManager` odeberete nastavení ochrany.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Odebrání ochrany heslem z ODP pomocí Javy" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.odp", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Odebrání ochrany proti zápisu z prezentace ODP pomocí Javy" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak odebrat heslo z ODP pomocí Javy" intro="Postupujte podle těchto kroků a odeberte ochranu z prezentace ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor ODP pomocí třídy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pokud je prezentace šifrovaná, použijte `LoadOptions.setPassword`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte `removeEncryption` nebo `removeWriteProtection` objektu `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte odemčenou prezentaci pomocí `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Vytvořeno pomocí Aspose.Slides" title="Odemčení souborů ODP online" description="Bezplatná aplikace Aspose.Slides Unlock je vytvořena pomocí [Aspose.Slides for Java](https://products.aspose.com/slides/cs/java/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory ODP." button="Otevřít Aspose.Slides Unlock" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides odebírá ochranu, ještě než začnete psát kód.
- Odeberte heslo nebo ochranu proti zápisu ze souboru ODP.
- Stáhněte odemčený soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro odemčení" subTitle="Pomocí Javy můžete odebrat ochranu také z následujících formátů." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/java/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/java/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
