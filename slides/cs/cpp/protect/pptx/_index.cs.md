---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Ochrana prezentací PPTX pomocí C++
url: /cs/cpp/protect/pptx/
description: Chraňte prezentace PPTX v C++. Pomocí Aspose.Slides for C++ šifrujte soubory a nastavujte ochranu proti zápisu.
keywords: Ochrana proti zápisu PPTX, šifrování PPTX, uzamčení prezentace PPTX, ochrana PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Uzamčení nebo ochrana PPTX heslem pomocí C++" h2="Pomocí Aspose.Slides for C++ šifrujte prezentace a nastavujte ochranu proti zápisu bez aplikace Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ochrana prezentace PPTX pomocí C++" variant="code" %}}

Aspose.Slides for C++ umožňuje chránit prezentace PPTX před otevřením nebo úpravami. Pomocí objektu `ProtectionManager` třídy `Presentation` zašifrujte soubor metodou `Encrypt` nebo omezte úpravy metodou `SetWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Šifrování prezentace PPTX pomocí C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Nastavení ochrany proti zápisu prezentace PPTX pomocí C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak chránit PPTX heslem pomocí C++" intro="Postupujte podle těchto kroků a ochraňte prezentaci PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPTX pomocí třídy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ochraňte prezentaci pomocí objektu `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Použijte `Encrypt` pro ochranu heslem nebo `SetWriteProtection` pro ochranu proti zápisu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte chráněný soubor pomocí `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Vytvořeno pomocí Aspose.Slides" title="Ochrana souborů PPTX heslem online" description="Bezplatná aplikace Aspose.Slides Lock je vytvořena pomocí [Aspose.Slides for C++](https://products.aspose.com/slides/cs/cpp/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPTX." button="Otevřít Aspose.Slides Lock" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides chrání prezentace, ještě než začnete psát kód.
- Nastavte heslo pro otevření nebo úpravy souboru PPTX.
- Stáhněte chráněný soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro ochranu" subTitle="Pomocí C++ můžete chránit také následující formáty." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/cpp/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
